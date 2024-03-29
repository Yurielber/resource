## RPM search: search service can find package by either name, provides, absolute file names (/usr/bin/apache), binaries (gprof) or shared libraries  
[RPM search Engine](https://rpmfind.net/linux/rpm2html/)  

## GDB guide  
[Quick Guide to Gdb](https://condor.depaul.edu/glancast/373class/docs/gdb.html)  

## GDB debug with JVM  
*Stack Overflow* *Handle SIGSEGV when debuging JVM with GDB* [Why does java app crash in gdb but runs normally in real life?](https://stackoverflow.com/questions/27241575/why-does-java-app-crash-in-gdb-but-runs-normally-in-real-life)  
`(gdb) handle SIGSEGV nostop noprint pass`  

## GDB debug with python  
*Python Official Guide* [Debugging With Gdb](https://wiki.python.org/moin/DebuggingWithGdb)  

## GDB command reference card  
[GDB QUICK REFERENCE](https://users.ece.utexas.edu/~adnan/gdb-refcard.pdf)  

## Shared Library explain (so file)  
[Linux Shared Libraries Howto](https://tldp.org/HOWTO/Program-Library-HOWTO/shared-libraries.html)  
1. debuging shared library with Environment Variables `export LD_DEBUG=files`  

## Binary file analyze & toolkit  
1. gdb 调试利器
1. ldd 查看程序依赖库
1. lsof 一切皆文件
1. ps 进程查看器
1. pstack 跟踪进程栈
1. strace 跟踪进程中的系统调用
1. ipcs 查询进程间通信状态
1. top linux下的任务管理器
1. free 查询可用内存
1. vmstat 监视内存使用情况
1. iostat 监视I/O子系统
1. sar 找出系统瓶颈的利器
1. readelf elf文件格式分析
1. objdump 二进制文件分析
1. nm 目标文件格式分析
1. size 查看程序内存映像大小
1. wget 文件下载
1. scp 跨机远程拷贝
1. crontab 定时任务  

## compile  
*Stack Overflow* [How can I link to a specific glibc version?](https://stackoverflow.com/questions/2856438/how-can-i-link-to-a-specific-glibc-version)  

## Case study  
*Jpype* [SegFault when using jpype with numpy.linalg](https://github.com/jpype-project/jpype/issues/808)  
*Jpype* [Unable to use JPype on IBM I series](https://github.com/jpype-project/jpype/issues/719)  
*ELF versioned symbols* [What does version info in ldd -v mean?](https://stackoverflow.com/questions/36368588/what-does-version-info-in-ldd-v-mean/36387635#36387635)  
*GDB* [Debugger Command Reference (GDB Mode)](https://scc.ustc.edu.cn/zlsc/sugon/intel/debugger/cl/main/bk_command_ref_gdb.htm)  
[Using GNU's GDB Debugger Memory Layout And The Stack](https://www.comp.nus.edu.sg/~liangzk/cs5231/stacklayout.pdf)  
[Debugging with GDB](https://sourceware.org/gdb/current/onlinedocs/gdb/index.html)  
[我们是怎么发现C++异常从堆栈追踪中消失的原因的](https://abcdabcd987.com/libstdc++-bug/)  

* Linux内核完全注释
[Linux内核0.12完全注释：修正版V5.0](http://www.oldlinux.org/download/CLK-5.0-WithCover.pdf)  
[Linux内核完全注释：内核版本0.11](http://www.oldlinux.org/download/clk011c-3.0.pdf)
[Linux内核源代码情景分析](https://github.com/jyfc/ebook/tree/master/03_operating_system)

## 内核参数(TCP/IP 协议栈)
[Linux系统的几个重要内核参数](https://www.cnblogs.com/kevingrace/p/6656095.html)

## 内核学习
[《Linux内核源代码情景分析》笔记](https://cataloc.gitee.io/blog/2021/07/02/Linux%E5%86%85%E6%A0%B8%E6%BA%90%E4%BB%A3%E7%A0%81%E6%83%85%E6%99%AF%E5%88%86%E6%9E%90%E8%AF%BB%E4%B9%A6%E7%AC%94%E8%AE%B0/#%E7%AC%94%E8%AE%B0)
[了解linux内核必读的五本书](https://zhuanlan.zhihu.com/p/359049747)
