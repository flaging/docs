# 操作系统

计算机操作系统, CPU体系结构和相关软硬件优化技术.

## 博客

* Rust linux kernel development: [blog](https://www.jackos.io/rust-kernel/rust-for-linux.html)
* Linux kernel development: [blog](https://www.kernel.org/doc/html/v4.16/process/howto.html)
* NUMA DEEP DIVE: [目录](https://frankdenneman.nl/2016/07/06/introduction-2016-numa-deep-dive-series/), 共分为[part1](https://frankdenneman.nl/2016/07/07/numa-deep-dive-part-1-uma-numa/), [part2](https://frankdenneman.nl/2016/07/08/numa-deep-dive-part-2-system-architecture/), [part3](https://frankdenneman.nl/2016/07/11/numa-deep-dive-part-3-cache-coherency/), [part4](https://frankdenneman.nl/2016/07/13/numa-deep-dive-4-local-memory-optimization/), [part5](https://frankdenneman.nl/2016/08/22/numa-deep-dive-part-5-esxi-vmkernel-numa-constructs/)
* Linux CPU 性能优化指南: [blog](https://cloud.tencent.com/developer/article/1677341?fromSource=gwzcw.1293314.1293314.1293314&cps_key=ad1dd5b36e1c498308f7302ab4cdabb7)
* Linux tracing/profiling 基础：符号表、调用栈、perf/bpftrace 示例等（2022）: [blog](http://arthurchiao.art/blog/linux-tracing-basis-zh/)
* xv6-riscv: [github](https://github.com/mit-pdos/xv6-riscv), 教学操作系统xv6的risc-v版本


## 图书

* Operating system: Three Easy Piece(OSTEP): [英文版](http://pages.cs.wisc.edu/~remzi/OSTEP/)/[中文版](http://pages.cs.wisc.edu/~remzi/OSTEP/Chinese/)
* Computer System: A Programmer's Perspective(CSAPP)
* [The Art of Unix Programming](https://archive.org/details/ost-computer-science-the_art_of_unix_programming-1/page/n37/mode/2up?continueFlag=139a2ddd232637f566f76a1678299ff7): UNIX编程艺术;本书主要介绍了Unix系统领域中的设计和开发哲学、思想文化体系、原则与经验，由公认的Unix编程大师、开源运动领袖人物之一Eric S. Raymond倾力多年写作而成。

## 视频

* [\[完结\] 2020 南京大学 “操作系统：设计与实现” (蒋炎岩)](https://www.bilibili.com/video/BV1N741177F5?p=1)

#### 从一次经历谈 TIME_WAIT 的那些事: [blog](https://coolshell.cn/articles/22263.html)

#### 2021.07.13 我们是这样崩的: [微信](https://mp.weixin.qq.com/s?__biz=Mzg3Njc0NTgwMg==&mid=2247487272&idx=1&sn=038a30ce61706c97e3397eee982b1486&scene=21#wechat_redirect), 使用的[OpenResty XRay工具介绍](https://mp.weixin.qq.com/s/YWucrzAH5LnVYLel4zpUOw?v_p=90&WBAPIAnalysisOriUICodes=10000001&launchid=10000365--x&wm=3333_2001&aid=01A2GUVvCiJ0bN45VH0AOVftc20OVPaYUZmVa1h1s_8-8xrdg.&from=10C7193010), [介绍](https://blog.openresty.com.cn/cn/lua-cpu-flame-graph/), [Ylang](https://blog.openresty.com/en/ylang-intro-part1/)

* How Computers Work ：Processor and Main Memory: [books](http://www.fastchip.net/howcomputerswork/p1.html), [pdf](http://www.fastchip.net/howcomputerswork/bookbpdf.pdf)

### 操作系统课

#### P15[虚拟化]:Linux地址进程空间

pmap $pid 查看程序的内存空间
mmap()/munmap(): 系统调用, 文件映射到进程地址空间
pmap调用:strace pmap $pid
proc fs: /proc/$pid/maps
gdb starti: 在第一条停下来
ld.so用于加载libc
vdso: 不陷入内核的系统调用(要求只读)
vvar: 内核和进程共享的数据
vsyscall: 系统调用地址
