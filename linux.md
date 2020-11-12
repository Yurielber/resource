## RPM search: search service can find package by either name, provides, absolute file names (/usr/bin/apache), binaries (gprof) or shared libraries  
[RPM search Engine](https://rpmfind.net/linux/rpm2html/)  

## GDB guide  
[Quick Guide to Gdb](https://condor.depaul.edu/glancast/373class/docs/gdb.html)  

## GDB debug with JVM  
*Stack Overflow* [Handle SIGSEGV when debuging JVM with GDB](https://stackoverflow.com/questions/27241575/why-does-java-app-crash-in-gdb-but-runs-normally-in-real-life)  
`(gdb) handle SIGSEGV nostop noprint pass`  

## GDB debug with python  
*Python Official Guide* [Debugging With Gdb](https://wiki.python.org/moin/DebuggingWithGdb)  

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
