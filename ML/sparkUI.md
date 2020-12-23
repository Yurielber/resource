## loginfo ##

      20/07/17 03:50:44 INFO Utils: Successfully started service 'SparkUI' on port 4040.
      20/07/17 03:50:44 INFO SparkUI: Bound SparkUI to 172.18.0.59, and started at http://100.95.69.196:4040
      
      20/07/17 03:50:44 INFO SparkEnv: Registering OutputCommitCoordinator
      20/07/17 03:50:44 INFO Utils: Successfully started service 'SparkUI' on port 4040.
      20/07/17 03:50:44 INFO SparkUI: Bound SparkUI to 172.18.0.59, and started at http://100.95.69.196:4040
      
      20/07/17 03:51:15 INFO Client: Application report for application_1589882538336_868287 (state: ACCEPTED)
      20/07/17 03:51:15 INFO YarnSchedulerBackend$YarnSchedulerEndpoint: ApplicationMaster registered as NettyRpcEndpointRef(null)
      20/07/17 03:51:15 INFO YarnClientSchedulerBackend: Add WebUI Filter. org.apache.hadoop.yarn.server.webproxy.amfilter.AmIpFilter, Map(PROXY_HOSTS -> kwegtsfi006-mg,kwegtsfi005-mg, PROXY_URI_BASES -> https://kwegtsfi006-mg:26001/proxy/application_1589882538336_868287,https://kwegtsfi005-mg:26001/proxy/application_1589882538336_868287), /proxy/application_1589882538336_868287
      20/07/17 03:51:15 INFO JettyUtils: Adding filter: org.apache.hadoop.yarn.server.webproxy.amfilter.AmIpFilter
      20/07/17 03:51:16 INFO Client: Application report for application_1589882538336_868287 (state: RUNNING)

## Spark 2.1 ##


### org.apache.spark.scheduler.cluster.CoarseGrainedClusterMessages.AddWebUIFilter ###
      // Exchanged between the driver and the AM in Yarn client mode
      case class AddWebUIFilter(
          filterName: String, filterParams: Map[String, String], proxyBase: String)
        extends CoarseGrainedClusterMessage

### yarn/src/main/scala/org/apache/spark/scheduler/cluster/YarnSchedulerBackend.scala:258 ###
        case AddWebUIFilter(filterName, filterParams, proxyBase) =>
          addWebUIFilter(filterName, filterParams, proxyBase)

### yarn/src/main/scala/org/apache/spark/scheduler/cluster/YarnSchedulerBackend.scala:159 ###
    
    /**
     * Add filters to the SparkUI.
     */
      private def addWebUIFilter(
          filterName: String,
          filterParams: Map[String, String],
          proxyBase: String): Unit = {
        if (proxyBase != null && proxyBase.nonEmpty) {
          System.setProperty("spark.ui.proxyBase", proxyBase)
        }

        val hasFilter =
          filterName != null && filterName.nonEmpty &&
          filterParams != null && filterParams.nonEmpty
        if (hasFilter) {
          logInfo(s"Add WebUI Filter. $filterName, $filterParams, $proxyBase") <----
          conf.set("spark.ui.filters", filterName)
          filterParams.foreach { case (k, v) => conf.set(s"spark.$filterName.param.$k", v) }
          scheduler.sc.ui.foreach { ui => JettyUtils.addFilters(ui.getHandlers, conf) }
        }
      }


### org.apache.spark.ui.WebUI#bind ###
    /** Bind to the HTTP server behind this web interface. */
      def bind() {
        assert(!serverInfo.isDefined, s"Attempted to bind $className more than once!")
        try {
          val host = Option(conf.getenv("SPARK_LOCAL_IP")).getOrElse("0.0.0.0")
          serverInfo = Some(startJettyServer(host, port, sslOptions, handlers, conf, name)) <----
          logInfo(s"Bound $className to $host, and started at $webUrl")
        } catch {
          case e: Exception =>
            logError(s"Failed to bind $className", e)
            System.exit(1)
        }
      }

## Spark on Yarn analyse ##

[Spark on Yarn源码分析](https://marsishandsome.github.io/2018/03/Spark_on_Yarn%E6%BA%90%E7%A0%81%E5%88%86%E6%9E%90)  
![结构](https://marsishandsome.github.io/images/spark_on_yarn_arch.png)  
*CSDN* [Spark2.1.0——SparkUI的实现](https://blog.csdn.net/beliefer/article/details/84101135)  

## Spark UI FAQ ##
[Can't access to SparkUI though YARN](https://stackoverflow.com/questions/51105320/cant-access-to-sparkui-though-yarn)

## Case Study on AWS EMR  
[Apache Spark Web UI on Amazon EMR](https://laujohn.com/2018/09/22/Apache-Spark-Web-UI-on-Amazon-EMR/)  
[FLIP-26: Service Authorization (SSL Mutual Authentication)](https://cwiki.apache.org/confluence/pages/viewpage.action?pageId=80453255)  

## live update Spark UI  
[Spree: A Live-Updating Web UI for Spark](https://www.hammerlab.org/2015/07/25/spree-58-a-live-updating-web-ui-for-spark/)  
