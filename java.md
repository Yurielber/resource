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

## Netty ##
http://qiankunli.github.io/2016/04/22/Java-Netty5.html  
https://github.com/arturmkrtchyan/hello-netty/blob/master/src/main/java/com/arturmkrtchyan/HelloClient.java  
[Netty Tutorial Part 1.5: On Channel Handlers and Channel Options](http://seeallhearall.blogspot.sg/2012/06/netty-tutorial-part-15-on-channel.html)  
[Netty Best Practices a.k.a Faster == Better](http://normanmaurer.me/presentations/2014-facebook-eng-netty/slides.html)  

#### Head first Netty ####
https://caorong.github.io/2016/11/24/netty-in-picture/  
https://caorong.github.io/2016/12/25/head-first-netty-2/  
https://caorong.github.io/2017/01/16/head-first-netty-3/  

## Restlet ##
http://restlet.com/company/blog/page/2/  
http://restlet.com/company/blog/2016/03/23/customizing-the-jackson-converter-of-restlet-framework/  

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


## JAVA native Memory Leak ? ##
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
