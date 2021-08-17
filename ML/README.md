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
1. [https://runawayhorse001.github.io/LearningApacheSpark/index.html](Learning Apache Spark with Python)  
1. PDF Version[https://runawayhorse001.github.io/LearningApacheSpark/pyspark.pdf](Learning Apache Spark with Python - PDF version)  

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
1. [xgboost系列丨xgboost原理及公式推导](https://mp.weixin.qq.com/s/4RMKpfOsr8zCzToqKnTiLg)  

## notebook  
1. [Explore Notebooks](https://www.zepl.com/explore)  
1. [Apache Zeppelin on Kubernetes with Spark and Kafka](https://www.slideshare.net/apachezeppelin/apache-zeppelin-on-kubernetes-with-spark-and-kafka-meetup-twitter)  

## Hive work with Spark  
[Spark2.1.0入门：连接Hive读写数据（DataFrame）](http://dblab.xmu.edu.cn/blog/1383-2/)  
[Hive with Spark 实战](https://www.jianshu.com/p/60e7e16fb3ce)  
[Yarn-Cluster模式下Spark连接Hive报错Delegation Token can be issued only](https://bbs.huaweicloud.com/forum/thread-102343-1-1.html)  

## AutoML  
[Meta-Learning: Learning to Learn Fast](https://lilianweng.github.io/lil-log/2018/11/30/meta-learning.html)  
SlideShare [AutoML lectures (ACDL 2019)](https://www.slideshare.net/JoaquinVanschoren/automl-lectures-acdl-2019)  
[AutoML.org](http://www.automl.org/book/) PDF E-book [Automated Machine Learning-Methods,Systems,Challenges](https://www.automl.org/wp-content/uploads/2019/05/AutoML_Book.pdf)  
[【值得读】自动机器学习: 最新进展综述与开放挑战 | AutoML](https://blog.csdn.net/u9Oo9xkM169LeLDR84/article/details/93552223?utm_medium=distribute.pc_relevant.none-task-blog-BlogCommendFromMachineLearnPai2-10.nonecase&depth_1-utm_source=distribute.pc_relevant.none-task-blog-BlogCommendFromMachineLearnPai2-10.nonecase)  
[Efficient and Robust Automated Machine Learning](https://proceedings.neurips.cc/paper/2015/file/11d0e6287202fced83f79975ec59a3a6-Paper.pdf)  

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


## Hadoop YARN analysis  
[Official Web Application Proxy](http://archive.cloudera.com/cdh5/cdh/5/hadoop/hadoop-yarn/hadoop-yarn-site/WebApplicationProxy.html)  
[Hadoop Two Web Proxy Server](http://johnjianfang.blogspot.com/2014/09/hadoop-two-web-proxy-server.html)  
----[Hadoop Internals Series -- Hadoop Architecture Overview](http://ercoppa.github.io/HadoopInternals/HadoopArchitectureOverview.html)  

## Random Forest Analysis  
[Spark 随机森林算法原理、源码分析及案例实战](https://developer.ibm.com/zh/articles/os-cn-spark-random-forest/)  
[RandomForest in Spark MLLib](https://www.cnblogs.com/luweiseu/p/7771304.html)  
[Random Forest Algorithm - Random Forest Explained | Random Forest In Machine Learning | Simplilearn](https://www.slideshare.net/Simplilearn/random-forest-algorithm-random-forest-explained-random-forest-in-machine-learning-simplilearn-91647398)  
[Building Random Forest at Scale](https://www.slideshare.net/0xdata/rf-brighttalk)  
[Improving Ensemble of Trees in MLlib](http://www.zhiyuanlin.com/uploads/5/8/8/1/58812849/improvingmllib.pdf)  
[Spark MLlib Random Forest tuning guide Usage tips V1.2.2](https://spark.apache.org/docs/1.2.2/mllib-ensembles.html)  
[Hyperparameter Tuning the Random Forest in Python](https://towardsdatascience.com/hyperparameter-tuning-the-random-forest-in-python-using-scikit-learn-28d2aa77dd74)  
[Decoding the probabilities in Random Forest](https://www.linkedin.com/pulse/decoding-probabilities-random-forest-sanchit-tiwari/)  
[Are you sure that's a probability?](https://kiwidamien.github.io/are-you-sure-thats-a-probability.html)  

## Visualize  
[Plotting in Jupyter Notebooks with Scala and EvilPlot](https://medium.com/swlh/plotting-in-jupyter-notebooks-with-scala-and-evilplot-aacab63a896)  
[How to visualize a single Decision Tree from the Random Forest in Scikit-Learn (Python)?](https://mljar.com/blog/visualize-tree-from-random-forest/)  
[Visualize a Decision Tree in 4 Ways with Scikit-Learn and Python](https://mljar.com/blog/visualize-decision-tree/)  

## gensim Word2Vec Doc2Vec  
[How to reproduce the doc2vec ‘Paragraph Vector’ paper](https://radimrehurek.com/gensim/auto_examples/howtos/run_doc2vec_imdb.html#how-to-reproduce-the-doc2vec-paragraph-vector-paper)  
[Ensure the gensim generate the same Word2Vec model for different runs on the same data](https://stackoverflow.com/questions/34831551/ensure-the-gensim-generate-the-same-word2vec-model-for-different-runs-on-the-sam)  

## Apache Flink for Machine Learning  
[How TensorFlow on Flink Works: Flink Advanced Tutorials](https://medium.datadriveninvestor.com/how-tensorflow-on-flink-works-flink-advanced-tutorials-3bce16db047)  
Flink’s features:  
1. Stateful iterations •  Keep state across iterations  
2. Delta iterations •  Limit computation to elements which matter  
3. Pipelining •  Avoiding materialization of large intermediate state  

[Machine Learning with Apache Flink at Stockholm Machine Learning Group](https://www.slideshare.net/tillrohrmann/machine-learning-with-apache-flink)  
[Spark versus Flink: Understanding Performance in Big Data Analytics Frameworks](https://hal.inria.fr/hal-01347638v2/document)  

## U-Net explained ##  
slideshare [Multiphoton Vasculature Segmentation #5: U-Net](https://www.slideshare.net/PetteriTeikariPhD/multiphoton-vasculature-segmentation-5-unet)  
[UNet: semantic segmentation with PyTorch](https://github.com/milesial/Pytorch-UNet)  
[U-Net for brain segmentation](https://github.com/mateuszbuda/brain-segmentation-pytorch)  
[Understanding UNET](https://bond-kirill-alexandrovich.medium.com/understanding-unet-27de538e08d8)  
[UNET-TGS/TGS UNET.ipynb](https://github.com/hlamba28/UNET-TGS/blob/master/TGS%20UNET.ipynb)  
[UNet — Line by Line Explanation](https://towardsdatascience.com/unet-line-by-line-explanation-9b191c76baf5)  
[U-Net Copy and Crop
 Reason for crop: Now when merging since the resolution of the two feature maps is not the same they are cropped. Before concatenating (572x572) with (392x392) it needs to be cropped.](https://stackoverflow.com/questions/53068877/u-net-copy-and-crop)  
[Deep Learning for Image Segmentation: U-Net Architecture](https://heartbeat.fritz.ai/deep-learning-for-image-segmentation-u-net-architecture-ff17f6e4c1cf)  
[machine-learning-models/UNet/test.ipynb](https://github.com/MJeremy2017/machine-learning-models/blob/master/UNet/test.ipynb)  

## Meter Reading ##  
[How to use deep learning & OCR for data extraction from meter readings](https://nanonets.com/blog/sub-meter-reading-using-deep-learning/)  
[Analogue Gauge Reader using Computer Vision](https://medium.com/@nayak.abhijeet1/analogue-gauge-reader-using-computer-vision-62fbd6ec84cc)  
[Reading a pressure gauge with a CNN](https://stats.stackexchange.com/questions/448028/reading-a-pressure-gauge-with-a-cnn)  


[An Idea From Physics Helps AI See in Higher Dimensions](https://www.quantamagazine.org/an-idea-from-physics-helps-ai-see-in-higher-dimensions-20200109/)  
[An Introduction to different Types of Convolutions in Deep Learning](https://towardsdatascience.com/types-of-convolutions-in-deep-learning-717013397f4d)  

## Handle NaN error ##  
[Beginner question: model returns NAN](https://discuss.pytorch.org/t/beginner-question-model-returns-nan/110663)  
[Losses end up becoming NAN during training. how to debug and fix them?](https://discuss.pytorch.org/t/losses-end-up-becoming-nan-during-training-how-to-debug-and-fix-them/99291)  
[How to prevent inf while working with exponential](https://stackoverflow.com/questions/60903821/how-to-prevent-inf-while-working-with-exponential)  
[Dealing with NaNs and infs](https://stable-baselines3.readthedocs.io/en/master/guide/checking_nan.html)  

## Nvidia Document ##  
[Nvdia Mixed Precision Training](https://docs.nvidia.com/deeplearning/performance/mixed-precision-training/index.html#pytorch)  

## Spark ##  
[How to Manage Python Dependencies in PySpark](https://databricks.com/blog/2020/12/22/how-to-manage-python-dependencies-in-pyspark.html)  
[Diving Into Spark 2.1.0 Blacklisting Feature](https://blog.yuvalitzchakov.com/diving-into-spark-2.1.0-blacklisting-feature/)  

[Understanding SSD MultiBox — Real-Time Object Detection In Deep Learning](https://towardsdatascience.com/understanding-ssd-multibox-real-time-object-detection-in-deep-learning-495ef744fab)  

## Image Labelling and Annotation ##  
[Image Data Labelling and Annotation - Everything you need to know](https://www.xailient.com/post/image-data-labelling-and-annotation)  
[Create COCO Annotations From Scratch](https://www.immersivelimit.com/tutorials/create-coco-annotations-from-scratch)  

## Hardware for Deep Learning ##  
[Hardware for Deep Learning. Part 1: Introduction](https://blog.inten.to/hardware-for-deep-learning-current-state-and-trends-51c01ebbb6dc)  
[Hardware for Deep Learning. Part 2: CPU](https://blog.inten.to/cpu-hardware-for-deep-learning-b91f53cb18af)  
[Hardware for Deep Learning. Part 3: GPU](https://blog.inten.to/hardware-for-deep-learning-part-3-gpu-8906c1644664)  
[Hardware for Deep Learning. Part 4: ASIC](https://blog.inten.to/hardware-for-deep-learning-part-4-asic-96a542fe6a81)  

## AIOps ##  
[时序数据异常检测做到这种段位，还怕什么告警风暴](https://dbaplus.cn/news-134-3515-1.html)  

## Transfer learning ##  
[Transfer learning and the art of using Pre-trained Models in Deep Learning](https://www.analyticsvidhya.com/blog/2017/06/transfer-learning-the-art-of-fine-tuning-a-pre-trained-model/)  

[Head Pose Estimation with Computer Vision](https://indatalabs.com/blog/head-pose-estimation-with-cv)  
[不同的AI视频推理场景下，如何构建通用高效的抽帧工具？](https://mp.weixin.qq.com/s?__biz=MzI0MjczMjM2NA==&mid=2247492631&idx=1&sn=d5271e21f25eddc7c997442aa9d1e40b&chksm=e9757834de02f122dbf9258c889b83d9e103911ec6c4aeb82465ea48b2212ad9ea8b4be9d15d&scene=178&cur_album_id=1604543620324360193#rd)  

OpenCV  
[Computer Vision on the GPU with OpenCV](http://developer.download.nvidia.com/GTC/PDF/1085_Fung.pdf)  
[OpenCV on a GPU](https://on-demand.gputechconf.com/gtc/2013/webinar/opencv-gtc-express-shalini-gupta.pdf)  
