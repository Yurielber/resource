## Preface  
1. [Comparison of deep-learning software](https://en.wikipedia.org/wiki/Comparison_of_deep-learning_software)  
2. [Getting Started With MachineLearning - Jim Liang - 梁劲](https://pan.baidu.com/s/1tNXYQNadAsDGfPvuuj7_Tw)

## Hadoop    
1. [Hadoop Delegation Tokens Explained](https://blog.cloudera.com/hadoop-delegation-tokens-explained/)  
1. [Hadoop and Kerberos: The Madness beyond the Gate](https://steveloughran.gitbooks.io/kerberos_and_hadoop/content/)  
1. [How Spark Uses Kerberos Authentication](https://andriymz.github.io/spark/how-spark-uses-kerberos-authentication/)  
1. [Delegation Token Handling In Spark](https://github.com/apache/spark/blob/master/core/src/main/scala/org/apache/spark/deploy/security/README.md)  
1. [Introducing Hadoop Tokens](https://steveloughran.gitbooks.io/kerberos_and_hadoop/content/sections/hadoop_tokens.html)  
1. [Submitting Spark batch applications](https://www.ibm.com/support/knowledgecenter/SSZU2E_2.2.1/managing_applications/applications_submit.html)
1. [Hadoop Kerberos的那些坑 --顾亮亮 --2015.11.03](https://marsishandsome.github.io/slides/gen/HadoopSecurity.html)  
1. [Debugging Apache Hadoop YARN Cluster in Production](https://www.slideshare.net/HadoopSummit/debugging-apache-hadoop-yarn-cluster-in-production-63887902)  
1. [Apache Hadoop 机器学习引擎 Submarine 及生态-刘勋](http://dl.zhangluya.com/Qcon/qconbj2019/Apache%20Hadoop%20%E6%9C%BA%E5%99%A8%E5%AD%A6%E4%B9%A0%E5%BC%95%E6%93%8E%20Submarine%20%E5%8F%8A%E7%94%9F%E6%80%81-%E5%88%98%E5%8B%8B.pdf)  
1. [TESTING BIGDATA PROJECTS](https://layer4.fr/blog/2017/02/23/testing-bigdata-hadoop/)  
1. [Amazon S3 Best Practice and Tuning for Hadoop/Spark in the Cloud](https://www.slideshare.net/ssuserca76a5/amazon-s3-best-practice-and-tuning-for-hadoopspark-in-the-cloud)  
1. [YARN Application Security](https://hadoop.apache.org/docs/current/hadoop-yarn/hadoop-yarn-site/YarnApplicationSecurity.html)  
1. [Understanding how Spark runs on YARN with HDFS](https://blog.knoldus.com/understanding-how-spark-runs-on-yarn-with-hdfs/)  
1. [How to collect Hadoop metrics](https://www.datadoghq.com/blog/collecting-hadoop-metrics/)  
1. [Spark and Kerberos: a safe story](https://www.stratio.com/blog/spark-kerberos-safe-story/)  
1. [Apache Zeppelin + Livy: Bringing Multi Tenancy to Interactive Data Analysis](https://www.slideshare.net/HadoopSummit/apache-zeppelin-livy-bringing-multi-tenancy-to-interactive-data-analysis)  
1. [Connecting Livy to a Secured Kerberized HDP Cluster](https://henning.kropponline.de/2016/11/06/connecting-livy-to-a-secured-kerberized-hdp-cluster/)  
1.[Hive tuning](https://www.slideshare.net/ye.mikez/hive-tuning)  

## Hadoop Case Study  
1. `libhdfs` is a JNI based C API for Hadoop’s Distributed File System (HDFS)  
1. Hadoop Native Libraries Guide  
1. [记录使用libhdfs访问hdfs的关键问题](https://www.cnblogs.com/qq120848369/p/3666757.html)  
`libhdfs.so --> libjvm.so --> Hadoop Jars(CLASSPATH)`  

## Kafka ##
[Apache Kafka Mailing Lists](https://mail-archives.apache.org/mod_mbox/kafka-users/)  
[Apache Kafka Official Documentation](https://kafka.apache.org/documentation/)  
[Kafka data structures in Zookeeper](https://cwiki.apache.org/confluence/display/KAFKA/Kafka+data+structures+in+Zookeeper)  
[0.8.0 SimpleConsumer Example](https://cwiki.apache.org/confluence/display/KAFKA/0.8.0+SimpleConsumer+Example)  
[Kafka Pages](https://cwiki.apache.org/confluence/collector/pages.action?key=KAFKA)  
[*kafka-users mailing list*: Kafka behind NAT](http://mail-archives.apache.org/mod_mbox/kafka-users/201608.mbox/browser)  

## Spark Metrics System  
1. [Monitoring and Instrumentation](https://spark.apache.org/docs/2.1.0/monitoring.html)  
1. [Executor-level metrics are sent from each executor to the driver as part of the Heartbeat to describe the performance metrics of Executor itself like JVM heap memory, GC information.](https://github.com/apache/spark/blob/master/docs/monitoring.md#source--jvm-source)  
1. [Sending Heartbeats and Active Tasks Metrics](https://mallikarjuna_g.gitbooks.io/spark/content/spark-executor.html)  
1. [度量系统--Metrics](https://www.jianshu.com/p/0b44b4a23c8a)  
1. [spark 监控--WebUi、Metrics System](https://www.jianshu.com/p/f67556228ff5)  
1. [Build an Online Performance Dashboard for Apache Spark](https://github.com/LucaCanali/Miscellaneous/tree/master/Spark_Dashboard)  
1. [Spark Metrics (CSV format)](https://zqhxuyuan.github.io/2017/05/01/Spark-Metrics/)  
1. [Notes: Spark metrics](https://www.raychase.net/3681)  
1. [Apache Spark metrics samples](https://github.com/elmiko/spark-metrics-samples)  
1. [A Kafka metric sink for Apache Spark](https://github.com/erikerlandson/spark-kafka-sink)  
1. [Spark推送数据到open-falcon](https://github.com/shangwen/SparkOpenFalconSink)  
1. [A spark metrics sink that pushes to InfluxDb](https://github.com/palantir/spark-influx-sink)  
1. [Py4J Issue: Evidence • Memory spiked during loading of trained ML models into python process. • Only on driver! Memory spikes Python Process Memory](https://www.slideshare.net/SparkSummit/monitoring-the-dynamic-resource-usage-of-scala-and-python-spark-jobs-in-yarn-spark-summit-east-talk-by-ed-barnes-and-ruslan-vaulin)  
[PySpark Internals](https://cwiki.apache.org/confluence/display/SPARK/PySpark+Internals)  
1. [Getting The Best Performance With PySpark](https://www.slideshare.net/SparkSummit/getting-the-best-performance-with-pyspark)  

## Spark Monitor (Krishnan R)  
1. [Spark Monitor — Big Data Tools for Physics Analysis](https://medium.com/@krishnanr/sparkmonitor-big-data-tools-for-physics-analysis-bbcdef68b35a)  
1. [Spark Monitor - An extension for Jupyter Notebook](https://github.com/krishnan-r/sparkmonitor)  
1. [sparkTraining](https://github.com/prasanthkothuri/sparkTraining)  
1. [Spark Monitor - How the extension works](https://krishnan-r.github.io/sparkmonitor/how.html)  
1. *Jupyterlab* [Jupyterlab Spark Monitor](https://github.com/itsjafer/jupyterlab-sparkmonitor)  
1. *Spark+AI Summit 2019*[Performance Troubleshooting Using Apache Spark Metrics](https://www.slideshare.net/databricks/performance-troubleshooting-using-apache-spark-metrics)  

## Spark PySpark ##
1. [PySpark 的背后原理](http://sharkdtu.com/posts/pyspark-internal.html)  
1. [GPU Computing with Apache Spark and Python](https://www.slideshare.net/continuumio/gpu-computing-with-apache-spark-and-python)  
1. [PySpark Cheat Sheet: Spark DataFrames in Python](https://www.datacamp.com/community/blog/pyspark-sql-cheat-sheet)
1. [Python For Data Science Cheat Sheet](https://s3.amazonaws.com/assets.datacamp.com/blog_assets/PySpark_SQL_Cheat_Sheet_Python.pdf)  
1. [https://github.com/runawayhorse001/CheatSheet/blob/master/cheatSheet_pyspark.pdf](https://github.com/runawayhorse001/CheatSheet/blob/master/cheatSheet_pyspark.pdf)  

## Kubeflow  
1. [Introduction to Kubeflow - 11th October 2018 World AI Summit 2018](https://cdn2.hubspot.net/hubfs/4149027/WSAI/DAY%202%20-%20STREAMS/16:05%20-%2016:20%20-%20Marc-Etienne%20Ouimette,%20Director%20of%20Public%20Policy,%20Element%20AI%20-%20Overview%20of%20the%20AI%20landscape%20in%20Canada%20from%20Element%20AI,%20pioneers%20of%20an%20AI-First%20world%20by%20turning%20cutting-edge%20AI%20research%20into%20transformative%20business%20applications.pdf)  
1. [Machine Learning as Code: A Year of Democratizing ML with Kubernetes and Kubeflow - David Aronchick Jason “Jay” Smith](https://github.com/warmchang/KubeCon-North-America-2018/blob/master/Machine%20Learning%20as%20Code%20and%20Kubernetes%20with%20Kubeflow.pdf)  

## Jupyter  
1. [https://jupyter-client.readthedocs.io/en/stable/messaging.html](https://jupyter-client.readthedocs.io/en/stable/messaging.html)  
1. [Comprehensive Beginner’s Guide to Jupyter Notebooks for Data Science & Machine Learning](https://www.analyticsvidhya.com/blog/2018/05/starters-guide-jupyter-notebook/)  
1. [Python Data Science Handbook--Essential Tools for Working with Data](https://jakevdp.github.io/PythonDataScienceHandbook/index.html)  
1. [IPython Cookbook, Second Edition (2018)](https://ipython-books.github.io/)  
1. [Jupyter Tutorial](https://www.tutorialspoint.com/jupyter/index.htm)  

## unclassified  
1. [Auto-scaling scikit-learn with Apache Spark](https://databricks.com/blog/2016/02/08/auto-scaling-scikit-learn-with-apache-spark.html)   
1. [分布式Tensorflow原理初探](https://zhuanlan.zhihu.com/p/39731797)  
1. [TensorFlow Core for beginners](https://www.tensorflow.org/tutorials)  
1. [【知乎】分布式TensorFlow入门教程](https://zhuanlan.zhihu.com/p/35083779)  
1. [Qubole Data Service](https://docs.qubole.com/en/latest/index.html)  
1. [基于DNS数据分析的恶意域名检测](https://blog.csdn.net/qq_38262728/article/details/83211181)  
1. [On solving an extremely wired issue of deploying spark-on-k8s](https://recursive.in/2017/12/08/solving-a-strange-issue-of-spark-on-k8s/)  

## notebook  
1. [Explore Notebooks](https://www.zepl.com/explore)  
1. [Apache Zeppelin on Kubernetes with Spark and Kafka](https://www.slideshare.net/apachezeppelin/apache-zeppelin-on-kubernetes-with-spark-and-kafka-meetup-twitter)  

## AutoML  
SlideShare [AutoML lectures (ACDL 2019)](https://www.slideshare.net/JoaquinVanschoren/automl-lectures-acdl-2019)  
[AutoML.org](http://www.automl.org/book/) PDF E-book [Automated Machine Learning-Methods,Systems,Challenges](https://www.automl.org/wp-content/uploads/2019/05/AutoML_Book.pdf)  
[【值得读】自动机器学习: 最新进展综述与开放挑战 | AutoML](https://blog.csdn.net/u9Oo9xkM169LeLDR84/article/details/93552223?utm_medium=distribute.pc_relevant.none-task-blog-BlogCommendFromMachineLearnPai2-10.nonecase&depth_1-utm_source=distribute.pc_relevant.none-task-blog-BlogCommendFromMachineLearnPai2-10.nonecase)  

## 概念漂移 & 模型漂移
[Concept Drift and Model Decay in Machine Learning](https://towardsdatascience.com/concept-drift-and-model-decay-in-machine-learning-a98a809ea8d4)  
[Model Drift in Machine Learning](https://towardsdatascience.com/model-drift-in-machine-learning-models-8f7e7413b563)  
[What is Model Drift?](https://blog.datatron.com/what-is-model-drift/)  

## Spark Model Evaluation ##
[A Tale of Three Apache Spark APIs: RDDs vs DataFrames and Datasets](https://databricks.com/blog/2016/07/14/a-tale-of-three-apache-spark-apis-rdds-dataframes-and-datasets.html)  
[Evaluation Metrics - RDD-based API](http://spark.apache.org/docs/latest/mllib-evaluation-metrics.html#evaluation-metrics-rdd-based-api)  

## Machine Learning Tutorial ##  
[Classifying flowers in Iris Dataset using Scala](https://hub.packtpub.com/classifying-flowers-in-iris-dataset-using-scala-tutorial/)  
[Regression through the Origin](http://web.ist.utl.pt/~ist11038/compute/errtheory/,regression/regrthroughorigin.pdf)  
[How to zip two (or more) DataFrame in Spark](https://stackoverflow.com/questions/32882529/how-to-zip-two-or-more-dataframe-in-spark)  
[Introduction to pattern recognition](https://www.slideshare.net/lgustavomartins/introduction-to-pattern-recognition)  

## Machine Learning ##  
[How to Handle Imbalanced Classes in Machine Learning](https://elitedatascience.com/imbalanced-classes)  
[Computing the sparse matrix vector product using block-based kernels without zero padding on processors with AVX-512 instructions](https://peerj.com/articles/cs-151/)  

## the TVM ##  
[Apache TVM](https://tvm.apache.org/)  

## Deep Learning ##  
[Python for Image Understanding: Deep Learning with Convolutional Neural Nets](https://www.slideshare.net/roelofp/python-for-image-understanding-deep-learning-with-convolutional-neural-nets)  
[Deep learning - Conceptual understanding and applications](https://www.slideshare.net/BuhwanJeong/deep-learning-c-43529709)  

## dataset case study  
*Reuters-21578* *word2vec* [Applying Bag of Words and Word2Vec models on Reuters-21578 Dataset](https://elvinouyang.github.io/project/reuters-w2v-bow-get-started/)  

## MachineLearning Model Visualization  
[How to Visualize a Decision Tree from a Random Forest in Python using Scikit-Learn](https://towardsdatascience.com/how-to-visualize-a-decision-tree-from-a-random-forest-in-python-using-scikit-learn-38ad2d75f21c)  

## Hadoop YARN analysis  
[Official Web Application Proxy](http://archive.cloudera.com/cdh5/cdh/5/hadoop/hadoop-yarn/hadoop-yarn-site/WebApplicationProxy.html)  
[Hadoop Two Web Proxy Server](http://johnjianfang.blogspot.com/2014/09/hadoop-two-web-proxy-server.html)  
[Hadoop Architecture Overview](http://ercoppa.github.io/HadoopInternals/HadoopArchitectureOverview.html)  
