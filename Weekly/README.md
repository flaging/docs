# 福来鸽的网络周报

## 2022-04-16

### 机器学习

#### [Tensorflow2 深度学习开源书(龙书)](https://github.com/dragen1860/Deep-Learning-with-TensorFlow-book)

* 中文图书, PDF版, 深度学习, tensorflow2

#### [FinRL: Deep Reinforcement Learning for Quantitative Finance](https://github.com/AI4Finance-Foundation/FinRL)

* 基于强化学习的量化交易框架

#### [Data Science Cheatsheets](https://github.com/FavioVazquez/ds-cheatsheets)

* 数据科学;总结

#### [MetaSpore](https://github.com/meta-soul/MetaSpore)

* 一站式机器学习开发平台; 框架

#### [AI:Scaling Up Your Kenrels to 31x31: Revisiting Large Kernel Design in CNN](https://paperswithcode.com/paper/scaling-up-your-kernels-to-31x31-revisiting)

* 通过大卷积核实现好的训练效果

#### [AI:Transformers in Time Series: A Survey](https://paperswithcode.com/paper/transformers-in-time-series-a-survey)

* Transformer 综述论文

#### [AI:中国信通院:人工智能白皮书(2022)](http://www.caict.ac.cn/kxyj/qwfb/bps/202204/t20220412_399752.htm)

* [下载](http://www.caict.ac.cn/kxyj/qwfb/bps/202204/P020220412613255124271.pdf)

### 编程语言

#### [资料:Free Programming Books](https://ebookfoundation.github.io/free-programming-books/)

* 免费的编程书; 中文图书见[这里](https://ebookfoundation.github.io/free-programming-books/books/free-programming-books-zh.html)

#### [design pattern for humans](https://github.com/kamranahmedse/design-patterns-for-humans)

* 设计模式, 读书笔记, PHP 语言

#### [C++ vs Rust](https://mp.weixin.qq.com/s/HDPybSPNdOLe5SIu7h8ZQQ)

* C++ 与 Rust 的一些不同,仅供参考

#### [C++ Best Practices](https://salttiger.com/cpp-best-practices/)

* [图书介绍](https://leanpub.com/cppbestpractices), [图书下载](https://pan.baidu.com/s/1L3Oh05FKTou9BdtdfkJcKg?pwd=dfse)

#### [王很水的博客](https://wanghenshui.github.io/archives.html)

* C++ and NoSQL
* 作者还维护了一个C++新闻周报, 地址在[这里](https://wanghenshui.github.io/cppweeklynews/), RSS地址在[这里](https://github.com/wanghenshui/cppweeklynews/releases.atom)

#### [std::this_thread::get_id()](https://en.cppreference.com/w/cpp/thread/get_id)

* C++ 线程号获取接口, C++11

#### [CXX — safe interop between Rust and C++](https://cxx.rs/?continueFlag=bfad8aef2f2b537615f634a87deb0d67)

* C++ 和 Rust 之间的一些安全互操作

#### [OpenCV Fourier Transform using C++](https://anothertechs.com/programming/cpp/opencv-fourier-transform-cpp/?continueFlag=bfad8aef2f2b537615f634a87deb0d67)

* 使用OpenCV C++进行傅里叶变换

#### [Python:How can I sort a dictionary by key?](https://stackoverflow.com/questions/9001509/how-can-i-sort-a-dictionary-by-key)

* python dict排序的几种方法
  * import collections; collections.OrderedDict(sorted(unorderd.item()))
  * for python > 3.7
    * sorted_dict = dict(sorted(unsorted_dict.items()))
    * dict本来就是有序的,可以直接使用: for k, v in od.items(): print(k, v)

#### [Python:appending list but error 'NoneType' object has no attribute 'append' [duplicate]](https://stackoverflow.com/questions/12894795/appending-list-but-error-nonetype-object-has-no-attribute-append)

* 将```last_list=last_list.append(p.last_name)```替换为```last_list.append(p.last_name)```

### 异构硬件

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

### 系统原理

#### [Linux性能优化实战](http://xiaozhazi.github.io/tags/Linux%E6%80%A7%E8%83%BD%E4%BC%98%E5%8C%96%E5%AE%9E%E6%88%98/)

* 个人博客系列, 源自极客时间同名课程的学习笔记

#### [Linux signals](https://devopedia.org/linux-signals)

* Linux信号量解读博客

#### [Google LLVM projects](https://llvm.org/OpenProjects.html#gsoc22)

* 谷歌与LLVM相关的工程

#### [LLVM](https://llvm.org/)

* LLVM社区官网
* [Getting Started/Tutorials](https://llvm.org/docs/GettingStartedTutorials.html)
* [Introducing to the LLVM Compiler](https://llvm.org/pubs/2008-10-04-ACAT-LLVM-Intro.html)
* [User Guide](https://llvm.org/docs/UserGuides.html)
* [References](https://llvm.org/docs/UserGuides.html)
* [Introducing to LLVM](http://www.aosabook.org/en/llvm.html)
* 介绍文档:[LLVM: A Compilation Framework for Lifelong Program Analysis & Transformation](https://llvm.org/pubs/2004-01-30-CGO-LLVM.html), [LLVM: An Infrastructure for Multi-Stage Optimization](https://llvm.org/pubs/2002-12-LattnerMSThesis.html)

#### [rCore Tutorial book](https://github.com/rcore-os/rCore-Tutorial-Book-v3)

* 基于RISC-V的操作系统教程, 编写类Unix系统

#### [从零开始编写一个简单的操作系统(英语)](https://www.cs.bham.ac.uk/~exr/lectures/opsys/10_11/lectures/os-dev.pdf?continueFlag=bfad8aef2f2b537615f634a87deb0d67)

* 图书;操作系统;英语;教材;英国伯明翰大学计算机学院
* 简短: 共77页

#### [Linux Kernel in a Nutshell](http://www.kroah.com/lkn/?continueFlag=702368c2545a5a025030138fa035365c)

* [图书下载](http://files.kroah.com/lkn/lkn_pdf.tar.gz)

#### [Istio in Action](https://salttiger.com/istio-in-action/)

* [图书介绍](https://www.manning.com/books/istio-in-action), [图书下载](https://pan.baidu.com/s/1cCFdiaRRpUsaWOCGktjM-A?pwd=3qpb)

#### [博客推荐: 编程之禅](https://wangjunstf.github.io/)

* 操作系统/数据结构/Rust/Linux/GDB

#### [视频: 计算机软件方法导论](https://www.bilibili.com/video/BV1u3411s7Jy?spm_id_from=333.905.b_72656c61746564.6)

* 共五讲, 约3.5小时, 魏永明

#### [博客推荐:ARTHURCHIAO'S BLOG](http://arthurchiao.art/?continueFlag=bfad8aef2f2b537615f634a87deb0d67)

* Linux/k8s/network为主, 很多中文的高质量译文

#### [教程:Operating System: Three Easy Pieces(OSTEP)](http://pages.cs.wisc.edu/~remzi/OSTEP/)

* 操作系统神书, [英文版](http://pages.cs.wisc.edu/~remzi/OSTEP/)/[中文版](http://pages.cs.wisc.edu/~remzi/OSTEP/Chinese/)

#### [博客推荐:Luyu Huang's Tech Blog](https://luyuhuang.tech/?continueFlag=bfad8aef2f2b537615f634a87deb0d67)

* 编程/算法/数学

#### [博客推荐:dunwu](https://dunwu.github.io/)

* 分布式/操作系统/设计模式/网络/大数据/架构设计等都有涉及

### 实用工具

名称|平台|同类|教程|说明
:-|:-:|:-:|:-:|--
tiptop|[Linux](https://github.com/nschloe/tiptop)|top|-|操作系统资源监控工具, TUI较为精美
LOL先知|[Win](https://github.com/real-web-world/hh-lol-prophet)|-|-|根据客户端接口预测对局中的大腿
Linux工具使用手册|Linux|-|[教程](https://linuxtools-rst.readthedocs.io/zh_CN/latest/base/index.html)|作者整理的doc
gperftool|[Linux](https://github.com/gperftools/gperftools)|perf|[教程1](https://gperftools.github.io/gperftools/heapprofile.html)<br>[教程2](https://www.cnblogs.com/GODYCA/archive/2013/05/28/3104281.html)|gperftool可用于分析性能和内存使用
warpd|[Mac/Linux](https://github.com/rvaiya/warpd)|vimium|-|键盘控制鼠标,上手难度较大
Efficient Linux at the Command Line|Linux|-|[教程](https://pan.baidu.com/s/1lwsJ2dvDJZ_2iTOkDsrAGg?pwd=ts5z)|-|[图书介绍](https://www.oreilly.com/library/view/efficient-linux-at/9781098113391/)
爬取你需要的数据:爬虫技术|*|-|[教程](https://book.crifan.org/books/crawl_your_data_spider_technology/website/)|[同类型教程](https://github.com/crifan/crifan_ebook_readme)
[espanso](https://espanso.org/)|[Win/Mac/Linux](https://espanso.org/)|-|[教程](https://espanso.org/docs/get-started/)|增强打字体验的工具
[licecap](https://www.cockos.com/licecap/)|[Win](https://www.cockos.com/licecap/licecap128-install.exe)/[Mac](https://www.cockos.com/licecap/licecap131.dmg)|-|-|截屏并保存至gif
[TranslucentTB](https://github.com/TranslucentTB/TranslucentTB)|[Win](https://github.com/TranslucentTB/TranslucentTB)|-|-|任务栏美化工具, 透明工具栏
[QuickLook](https://www.microsoft.com/zh-cn/p/quicklook/9nv4bs3l1h4s#activetab=pivot:overviewtab)|[Win-Store](https://www.microsoft.com/zh-cn/p/quicklook/9nv4bs3l1h4s#activetab=pivot:overviewtab)|-|-|用空格键预览文件
[EarTrumpet](https://eartrumpet.app/)|[Win](https://eartrumpet.app)|-|-|应用音量单独调整
[mouseinc](https://shuax.com/project/mouseinc/)|[Win](https://shuax.com/project/mouseinc/)|-|-|鼠标手势工具
[Total Commander](https://www.ghisler.com/)|[Win](https://www.ghisler.com/)|explorer|-|老牌文件管理器
[SurfingKeys](https://github.com/brookhong/Surfingkeys)|[Chrome](https://chrome.google.com/webstore/detail/surfingkeys/gfbliohnnapiefjpjlpjnehglfpaknnc)|[Vimium](https://chrome.google.com/webstore/detail/vimium/dbepggeogbaibhgnhhndojpepiihcmeb)|-|快捷键工具
[WizTree](https://diskanalyzer.com/)|[Win](https://diskanalyzer.com/files/wiztree_4_08_setup.exe)|[spacesniffer](http://www.uderzo.it/main_products/space_sniffer/)|-|磁盘空间显示
[Ditto](https://ditto-cp.sourceforge.io/)|[Win/Mac/Linux](https://ditto-cp.sourceforge.io/)|-|-|剪切板管理工具
[油猴脚本: Open link directly](https://greasyfork.org/zh-CN/scripts/442187-open-the-link-directly)|[Chrome](https://greasyfork.org/zh-CN/scripts/442187-open-the-link-directly)|-|-|跳过第三方跳转
[My MacOS HotKeys](https://www.jamieonkeys.dev/posts/keyboard-shortcuts/)|Mac|-|[教程](https://www.jamieonkeys.dev/posts/keyboard-shortcuts/)|作者的一些Mac快捷键, 供参考
[Raycast](https://www.raycast.com/)|[Mac](https://www.raycast.com/)|utools|[教程](https://sspai.com/post/72540)|MacOS启动器类应用:<br><tab>剪贴板历史: 类似Windows下Ditto<br>窗口管理: 替代Rectangle<br>卸载应用: 腾讯柠檬<br>Snippets: 文本替换<br>状态栏菜单<br>查词: dictionary<br>有第三方extention
[Git for Professionals](https://youtu.be/Uszj_k0DGsg)|-|-|[视频](https://youtu.be/Uszj_k0DGsg)|Youtube视频
[proxyman](https://proxyman.io/?continueFlag=bfad8aef2f2b537615f634a87deb0d67)|[Mac](https://proxyman.io/?continueFlag=bfad8aef2f2b537615f634a87deb0d67)|-|-|抓包工具
[Bash One-Liner Explained](https://kodango.com/bash-one-liners-explained-part-one?continueFlag=bfad8aef2f2b537615f634a87deb0d67)|-|-|[教程](https://kodango.com/bash-one-liners-explained-part-one?continueFlag=bfad8aef2f2b537615f634a87deb0d67)|一行bash命令实现一个功能, 带解释, 中文翻译版
traceroute|Linux yum|-|[教程](https://wangchujiang.com/linux-command/c/traceroute.html)|网络追踪工具

### 日常生活

#### [如何成为一个学习机器](http://blog.jiayuanzhang.com/post/how-to-be-a-learning-machine/?utm_campaign=%E9%87%8E%E7%94%9F%E6%9E%B6%E6%9E%84%E5%B8%88&utm_medium=email&utm_source=Revue%20newsletter)

* 人脑和计算机一样: 给一定的输入, 就会有对应的输出
* 通过阅读管理知识
  * 早起读书: 解决没时间问题
  * 进行主题阅读: 同时读同主题的多本书, 并剪辑有用部分
  * 使用Anki同类工具进行一定复习, 并打通学习流程
* T 型人才: 广泛涉猎多方向, 熟悉一个方向

#### [居家运动指南](https://mp.weixin.qq.com/s/rL4GW-YfJL39GznOtHRSgA)

* 每周需要150分钟中等强度的有氧运动和两次力量练习
  * 中等有氧运动: 最大心率的60%~85%, 可连续做3分钟及以上, 快走/慢跑/慢节奏健身操等
  * 力量练习: 只能坚持几秒钟~2分钟, 肌肉有酸痛感
* 一些运动姿势, 比较简单, 可供参考

#### [Awesome PHD Advice](https://github.com/pliang279/awesome-phd-advice)

* 给PHD的一些建议文章

#### [生活建议: 高效利用下班后的时间](https://sspai.com/post/72494)

* 减少花在必要事件的时间
  * 养成习惯和计划, 不需要浪费时间决策
  * 增强做完事情的正反馈
  * 将事件拆分成小的任务
* 如何提高执行效率
  * 寻找做事情效率最高的时间段
  * 确认高效率的环境因素/持续时间/被打断的因素
  * 饮食: 提神食物/减少碳水/避免饥饿
* 记录与复盘

#### [新闻:从分割走向整合：推进国内统一大市场建设的阻力与对策](https://mp.weixin.qq.com/s/P121K8I0dsWUgQbwyItFjg)

* 统一大市场的讨论
