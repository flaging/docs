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

#### [图书: The Art of Multiprocessor Programming](http://cs.ipm.ac.ir/asoc2016/Resources/Theartofmulticore.pdf)

#### [Everything You Need to Know About the NVMe® 2.0 Specifications and New Technical Proposals](https://nvmexpress.org/everything-you-need-to-know-about-the-nvme-2-0-specifications-and-new-technical-proposals/): NVMe 2.0

#### NVMe® Key Value Command Set Provides the Key to Storage Efficiency: [blog](https://nvmexpress.org/nvme-key-value-command-set-provides-the-key-to-storage-efficiency/), NVMe KVS

* Rust for Linux | 用 Rust 写 Linux 内核模块: [微信](https://mp.weixin.qq.com/s/m2eZ0lEzQHjrNVC6YCC_IA)
* OneAPI documnents: [docs](https://www.intel.cn/content/www/cn/zh/developer/tools/oneapi/documentation-library.html?s=Newest), Intel Libs Documents, [sycl docs](https://www.intel.cn/content/www/cn/zh/developer/tools/oneapi/data-parallel-c-plus-plus.html#gs.6oqu0b), [DPC++ books](https://resource-cms.springernature.com/springer-cms/rest/v1/content/17382710/data/v1)


## NVIDIA CUDA

### 教程

* [GPU development with Python 101 Tutorial](https://github.com/jacobtomlinson/gpu-python-tutorial): 用Python开发GPU程序
* TRAINING VS INFERENCE – NUMERICAL PRECISION: [blog](https://frankdenneman.nl/2022/07/26/training-vs-inference-numerical-precision/), AI训练和推理中的数据精度, 好文系列

### 使用技巧

* [A100系列需要11.1及以上版版本cuda的pytorch才能运行](https://stackoverflow.com/questions/66992585/how-does-one-use-pytorch-cuda-with-an-a100-gpu)

  ```bash
  pip3 install torch==1.9.0+cu111 torchvision==0.10.0+cu111 torchaudio==0.9.0 -f https://download.pytorch.org/whl/torch_stable.html
  ```
* [CUDA_VISIABLE_DEVICES="0,1,2"可以控制使用的卡](https://developer.nvidia.com/zh-cn/blog/cuda-pro-tip-control-gpu-visibility-cuda_visible_devices/)
* Train With Mixed Precision: [doc](https://docs.nvidia.com/deeplearning/performance/mixed-precision-training/index.html), [pdf](https://docs.nvidia.com/deeplearning/performance/pdf/Training-Mixed-Precision-User-Guide.pdf), NV混合精度训练文档, 中文翻译版[csdn](https://blog.csdn.net/baidu_32048673/article/details/103715333)
* TorchScript GELU error: [issue](https://github.com/triton-inference-server/server/issues/3909), torch版本问题, 需要NV官方docker```nvcr.io/Nvidia/pytorch:21.12-py3```以后能解决, 也可以将镜像内/opt/下的torch及编译的依赖库拷贝出来编译安装
* NVIDIA Deep Learning Frameworks: [doc](https://docs.nvidia.com/deeplearning/frameworks/index.html), NV支持的深度学习库更新的release note
* NVIDIA AI Platform Delivers Big Gains for Large Language Models: [blog](https://developer.nvidia.com/blog/nvidia-ai-platform-delivers-big-gains-for-large-language-models/), NV加速大型语言模型训练,最多有30%
* [pytorch cuda kernel gelu](https://github.com/pytorch/pytorch/blob/master/aten/src/ATen/native/cuda/ActivationGeluKernel.cu): gelu的pytorch实现
* [Nvidia profiling工具](https://indico-jsc.fz-juelich.de/event/32/material/0/5.pdf)
  * nvprof, 另外还有nsys