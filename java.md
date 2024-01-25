## Java API ##
[Java Stream API](https://docs.oracle.com/javase/tutorial/collections/streams/)  
[Java concurrent collections introductions](http://www.codejava.net/java-core/collections/understanding-collections-and-thread-safety-in-java)  

## Design Pattern ##
[Double checked Locking](https://www.cs.umd.edu/~pugh/java/memoryModel/DoubleCheckedLocking.html)  
[Facade Pattern](https://dzone.com/articles/design-patterns-uncovered-1)  

## Java source code Obfuscate ##
[Protect Your Java Code — Through Obfuscators And Beyond](https://web.archive.org/web/20161217190546/http://www.excelsior-usa.com/articles/java-obfuscators.html)  
[ProGuard: Real World Example](https://www.alexeyshmalko.com/2014/proguard-real-world-example/)  
[Android Getting Started with ProGuard](https://www.raywenderlich.com/7449-getting-started-with-proguard)  
[AndroidProguardGuide](https://github.com/inferjay/AndroidProguardGuide)  

## JMX ##
[Jolokia is an HTTP/JSON bridge for remote JMX access](https://jolokia.org/features-nb.html)    
[Java Platform, Standard Edition Monitoring and Management Guide](https://docs.oracle.com/javase/9/management/toc.htm)

## Hibernate ##
[Hibernate SQLQuery Manual](https://docs.jboss.org/hibernate/orm/4.1/devguide/en-US/html/ch13.html)  

## Spring ##
[Tips for debugging Spring's @Transactional annotation](https://tim.mattison.org/java-hacks/tips-for-debugging-springs-transactional-annotation)

## Netty ##
http://qiankunli.github.io/2016/04/22/Java-Netty5.html  
https://github.com/arturmkrtchyan/hello-netty/blob/master/src/main/java/com/arturmkrtchyan/HelloClient.java  
[Netty Tutorial Part 1.5: On Channel Handlers and Channel Options](http://seeallhearall.blogspot.sg/2012/06/netty-tutorial-part-15-on-channel.html)  
[Netty Best Practices a.k.a Faster == Better](http://normanmaurer.me/presentations/2014-facebook-eng-netty/slides.html)  
[我为 Netty 贡献源码 | 且看 Netty 如何应对 TCP 连接的正常关闭，异常关闭，半关闭场景](https://mp.weixin.qq.com/s?__biz=MzkyMTIzMTkzNA==&mid=2247586378&idx=2&sn=4527d43dd448b553dcaf5fc686dcca88&chksm=c185651bf6f2ec0da6cd7fc8d1e86c50d3a1b0ee8951561f392586516f2432ca51fbf849fdcd&scene=126&&sessionid=0)  
[一次 Netty 代码不健壮导致的大量 CLOSE_WAIT 连接原因分析](https://cloud.tencent.com/developer/article/2186370)  

#### Head first Netty ####
https://caorong.github.io/2016/11/24/netty-in-picture/  
https://caorong.github.io/2016/12/25/head-first-netty-2/  
https://caorong.github.io/2017/01/16/head-first-netty-3/  

## Restlet ##
http://restlet.com/company/blog/page/2/  
http://restlet.com/company/blog/2016/03/23/customizing-the-jackson-converter-of-restlet-framework/  

## Java String Maximum length ##  
[https://www.programmersought.com/article/83356655073/](The length limit of String in Java)  


## Memory Leak ##
[Native Memory Tracking in JVM](https://www.baeldung.com/native-memory-tracking-in-jvm)  
describes native memory categories used by NMT  
[NMT Memory Categories](https://docs.oracle.com/javase/8/docs/technotes/guides/troubleshoot/tooldescr022.html)  
[How to monitor JVM native memory usage by enabling native memory tracking](https://help.mulesoft.com/s/article/How-to-monitor-JVM-native-memory-usage-by-enabling-native-memory-tracking)  
[Java Platform, Standard Edition Troubleshooting Guide Native Memory Tracking](https://docs.oracle.com/javase/8/docs/technotes/guides/troubleshoot/tooldescr007.html)  
[聊聊HotSpot VM的Native Memory Tracking](https://juejin.im/post/6844903806468096013)  
[JVM Anatomy Quark #12: Native Memory Tracking](https://shipilev.net/jvm/anatomy-quarks/12-native-memory-tracking/)  
This article explains the internal architecture of the Java Virtual Machine (JVM)  
[JVM Internals](https://blog.jamesdbloom.com/JVMInternals.html)  
[Java Memory Management](https://dzone.com/articles/java-memory-management)  
[Troubleshooting Problems With Native (Off-Heap) Memory in Java Applications](https://dzone.com/articles/troubleshooting-problems-with-native-off-heap-memo)  
[Introduction to JVM Code Cache](https://www.baeldung.com/jvm-code-cache#:~:text=To%20avoid%20this%2C%20we%20can,code%20cache%2C%2032KB%20or%2064KB)  
[StackOverflow.com--Difference between Resident Set Size (RSS) and Java total committed memory (NMT) for a JVM running in Docker container](https://stackoverflow.com/questions/38597965/difference-between-resident-set-size-rss-and-java-total-committed-memory-nmt)  
[StackOverflow.com--Is CompressedClassSpaceSize area contains MaxMetaspaceSize area?](https://stackoverflow.com/questions/54250638/is-compressedclassspacesize-area-contains-maxmetaspacesize-area)  
[Tracking Memory Consumption Using Pmap](https://milianw.de/code-snippets/tracking-memory-consumption-using-pmap.html)  
[pmap(1) - Linux man page](https://linux.die.net/man/1/pmap)  
[Java Memory Leaks: Tools, Fixes, and More](https://dzone.com/articles/what-to-do-about-java-memory-leaks-tools-fixes-and)  


## JAVA native Memory Leak ? ##  
[Dawn of the Dead Ends: Fixing a Memory Leak in Apache Kafka](https://blog.heroku.com/fixing-kafka-memory-leak)  
[Using jemalloc to get to the bottom of a memory leak](https://technology.blog.gov.uk/2015/12/11/using-jemalloc-to-get-to-the-bottom-of-a-memory-leak/)  
[Debugging Java Native Memory Leaks](https://www.evanjones.ca/java-native-leak-bug.html)  
[Tuning Glibc Environment Variables (e.g. MALLOC_ARENA_MAX)](https://github.com/cloudfoundry/java-buildpack/issues/320)  
[Consider lowering MALLOC_ARENA_MAX to prevent native memory OOM](https://github.com/prestodb/presto/issues/8993)  
*about MALLOC_ARENA_MAX*  
The default maximum arena size is 1MB on 32-bit and 64MB on 64-bit. The default maximum number of arenas is the number of cores multiplied by 2 for 32-bit and 8 for 64-bit.
This can increase fragmentation because the free trees are separate.
[IBM about MALLOC_ARENA_MAX](https://web.archive.org/web/20200105040127/https://publib.boulder.ibm.com/httpserv/cookbook/Operating_Systems-Linux.html?lang=en#Operating_Systems-Linux-Physical_Memory_RAM-MALLOC_ARENA_MAX)  
[StackOverflow.com--Virtual Memory Usage from Java under Linux, too much memory used](https://stackoverflow.com/questions/561245/virtual-memory-usage-from-java-under-linux-too-much-memory-used)  
[How To: MALLOC_ARENA_MAX](https://web.archive.org/web/20161228221330/https://infobright.com/blog/malloc_arena_max/)  
[https://devcenter.heroku.com/articles/tuning-glibc-memory-behavior](https://devcenter.heroku.com/articles/tuning-glibc-memory-behavior)  


## Apache Curator ##
[Apache Curator Recipes Documents](https://curator.apache.org/curator-recipes/)  
[ZK](http://zookeeper.apache.org/doc/r3.1.2/zookeeperProgrammers.html)  
[Java Code Examples for org.apache.curator.framework.recipes.locks.InterProcessMutex](https://www.programcreek.com/java-api-examples/index.php?api=org.apache.curator.framework.recipes.locks.InterProcessMutex)  
[com.github.ibole.microservice.remoting.curator.lock.DistributedLockServiceCuratorImpl](https://www.programcreek.com/java-api-examples/?code=benson-git/ibole-microservice/ibole-microservice-master/microservice-remoting/src/main/java/com/github/ibole/microservice/remoting/curator/lock/DistributedLockServiceCuratorImpl.java)  
[Distributed Systems Get Simpler with Apache Helix](http://blog.cloudera.com/blog/2013/09/distributed-systems-get-simpler-with-apache-helix/)  
[Test of ZK Curator InterProcessMutex](https://gist.github.com/quux00/f6be8fe223a7832ef514)  
[a series of blogs introducing Apache ZooKeeper](http://www.sleberknight.com/blog/sleberkn/tags/zookeeper)  

## unclassified ##
[IBM article Dealing with InterruptedException](https://www.ibm.com/developerworks/java/library/j-jtp05236/index.html)  
[JVM Classloading](https://dev.vividbreeze.com/jvm-classloading/)  

# OSGi Version #  
[OSGi Version](https://www.eclipse.org/virgo/documentation/virgo-documentation-3.7.0.M01/docs/virgo-user-guide/html/ch02s02.html)  

# blogs #  
[Quartz scheduler misfire instructions explained](https://www.nurkiewicz.com/2012/04/quartz-scheduler-misfire-instructions.html)  
[Java Compare and Swap Example – CAS Algorithm](https://howtodoinjava.com/java/multi-threading/compare-and-swap-cas-algorithm/)  

## Debug toolkit  
* [jmap Utility -- The jmap command-line utility prints memory-related statistics for a running VM or core file](https://docs.oracle.com/javase/8/docs/technotes/guides/troubleshoot/tooldescr014.html)  
* [Analyze JVM Core file](https://stackoverflow.com/questions/36109313/best-way-on-how-to-solve-debug-jvm-crash-sigsegv)`jmap -dump:format=b,file=dump.hprof /usr/bin/java core_file`  
* [How to Use Verbose Options in Java -verbose:class|jni|gc](https://dzone.com/articles/how-use-verbose-options-java)  
* [Troubleshooting JAVA SSL with certificates](https://opennms.discourse.group/t/troubleshoot-java-with-self-signed-certificates/55)  

## case study (JVM SIGSEGV)  
[Best way on how to solve/debug JVM crash (SIGSEGV)](https://stackoverflow.com/questions/36109313/best-way-on-how-to-solve-debug-jvm-crash-sigsegv)  
[Why does java app crash in gdb but runs normally in real life?](https://stackoverflow.com/questions/27241575/why-does-java-app-crash-in-gdb-but-runs-normally-in-real-life)  
[Native Java Debugging on Alpine Linux: GDB, OpenJDK and the Mysterious Unknown Signal](https://www.overops.com/blog/native-java-debugging-on-alpine-linux-gdb-openjdk-and-the-mysterious-unknown-signal/)  
[Determine Where the Crash Occurred](https://docs.oracle.com/javase/8/docs/technotes/guides/troubleshoot/crashes001.html#CIHJABGA)  

## Testing  
[BDD Testing, Cucumber 10 Minute Tutorial](https://cucumber.io/docs/guides/10-minute-tutorial/)  

