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
