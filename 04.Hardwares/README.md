# 异构硬件

#### [Multi-GPU Programming with Standard Parallel C++, Part 1](https://developer.nvidia.com/blog/multi-gpu-programming-with-standard-parallel-c-part-1)

#### [NVIDIA CUDA Programing Guide 2.0 Final](https://www.nvidia.cn/docs/IO/57399/NVIDIA_CUDA_Programming_Guide_2.0Final.pdf)

* 看起来nv在2008年cuda接口就基本稳定了

#### [WinnieS的微博:图书推荐](https://weibo.com/2144454703/LrzAQcqD4)

* 手把手教你设计CPU--RISC-V处理器
* RISC-V架构与嵌入开发快速入门

#### [M1 CPU 那么多的核，macOS 是怎样管理的？](https://sspai.com/post/73048)

* MacOS的E核(Efficiency Core)和P核(Performancs Core的调度策略)
* 应用程序通常由 Grand Central Dispatch 使用 QoS 管理
  * 最低 QoS 线程只在 E 集群上运行
  * 用户进程优先分配P核,过多后再分配E核
  * 引导或者更新后,系统可能处于单E核运行状态

![图片](https://cdn.sspai.com/editor/u_/c9q8lhtb34t9etjhlvq0.png?imageView2/2/w/1120/q/90/interlace/1/ignore-error/1)

#### [深入理解混合精度训练：从 Tensor Core 到 CUDA 编程](https://mp.weixin.qq.com/s/CBGymNbAN4pD31oe70-Klw)

* 介绍tensorcore的调用接口
  * cuda warpper接口
  * cudnn封装接口

#### [OpenSource GPU](https://github.com/hughperkins/VeriGPU)

* veriGPU, 基于RISC-V ISA的verilog GPU开源项目

#### [CUDA多个流的使用](https://blog.51cto.com/u_15127618/3929160)

* cuda多stream编程示例
* [其他多stream教程](https://zhuanlan.zhihu.com/p/51402722)

#### [SmartNICs to xPUs – Why is the Use of Accelerators Accelerating?](https://www.brighttalk.com/webcast/663/536971)

* 会议:2022-05-20

#### [CPU缓存一致性协议- 深入理解内存屏障](icefrozen.github.io/article/why-memory-barriers-1/)

* CPU缓存一致性协议解析

#### [FPGA并行编程](xupsh.github.io/pp4fpgas-cn/)

* FPGA编程;Parallel Programming for FPGAs的中文翻译版

#### [CPU性能和Cache](https://plantegg.github.io/2021/07/19/CPU%E6%80%A7%E8%83%BD%E5%92%8CCACHE/)

* CPU性能介绍, 作者是[plantgg](https://weibo.com/n/plantegg)
* [CPU的制造和概念](https://plantegg.github.io/2021/06/01/CPU的制造和概念)
* [十年后数据库还是不敢拥抱NUMA](https://plantegg.github.io/2021/05/14/十年后数据库还是不敢拥抱NUMA/)

#### [CPU相关书籍推荐和部分芯片微架构](https://zhuanlan.zhihu.com/p/497495797?utm_source=com.microsoft.todos&utm_medium=social&utm_oi=49336847171584)

* CPU相关图书推荐; 另有多张CPU架构图片(如RISC-V)

#### [Tensil tutorial for YOLO v4 Tiny on Ultra96 V2](https://k155la3.blog/2022/04/04/tensil-tutorial-for-yolo-v4-tiny-on-ultra96-v2/?continueFlag=bfad8aef2f2b537615f634a87deb0d67)

* 在FPGA上实现了一个深度神经网络

#### [讲座:开源,让天下没有难做的芯片](https://mp.weixin.qq.com/s/R8a7F7_QLoBuBpi-bncqAg)

* 包云岗; 香山RISC-V; 芯片简介; 内有视频

#### [Nvidia MPS 总结](https://asphelzhn.github.io/2019/04/14/tensor_09_MPS/)

* MPS: Multi-Process Scheduling
* 多个进程向驱动提交指令, 驱动只有一个队列, 减少context切换导致的性能损失

#### [CPU和GPU线程概念的异同(英文)](https://itnext.io/graphics-processors-gpus-under-the-hood-4522dbec777d)

* 相同点
  * 都有程序计数器/线程ID/计算单元等内容
* 不同点
  * GPU线程必须执行相同指令流, 处理的数据可以不相同
  * CPU线程上限受限于从内存中读取的指令数据数量, GPU没有此限制, 所以线程数大于CPU
  * GPU中对于只访问一次(没有数据依赖)的尽量不用for循环
  * [Nvidia CUDA C++ 编程指南](https://docs.nvidia.com/cuda/cuda-c-programming-guide/index.html)
  * [CUDA 汇编参考手册](https://docs.nvidia.com/cuda/cuda-binary-utilities/index.html#instruction-set-ref)

