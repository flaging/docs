# 福来鸽的网络周报

## 2022-04-23

### 机器学习

#### [ColossalAI](https://github.com/hpcaitech/ColossalAI)

* 大规模深度学习训练平台, 支持分布式

#### [MLPerf Inference Benchmark Suites](https://github.com/mlcommons/inference)

#### [onnx-util](https://github.com/saurabh-shandilya/onnx-utils)

* onnx剪辑工具

#### [Huggingface transformers](https://github.com/huggingface/transformers)

* transformer的推理库

### 编程语言

#### [TypeError: only length-1 arrays can be converted to Python scalars while plot showing](https://stackoverflow.com/questions/36680402/typeerror-only-length-1-arrays-can-be-converted-to-python-scalars-while-plot-sh)

* python matplotlib输入需要是一组数

#### [python基础_格式化输出（%用法和format用法）](https://www.cnblogs.com/fat39/p/7159881.html)

* ``` print('%o' % 20) ```
* ``` print('d1: {d1} \td2: {d2}'.format(d1=1, d2=2)) ```
* ``` print('d1: {2} \td2: {1}'.format(d2, d1)) ```
* ``` print('{0:b}'.format(3)) #二进制输出```
* format还有更多用法

格式|含义|格式|含义|格式|含义
:-:|:-:|:-:|:-:|:-:|:-:
%o|8进制|%d|10进制|%x|16进制
%f|float|%e|科学计数法|%g|科学计数法/小数
round(1.123, 2)|取整|%3.2f|前三位对齐,保留2位|%s|字符串
%10s|占10位右对齐|%-10s|左对齐占10位|%.2s|截取两位
%i|整数|%c|字符|%u|无符号数
%X|大写16进制|%%|文字

#### [Rust语言圣经](https://course.rs/about-book.html)

* Rust教程

#### [30天自制C++服务器](https://github.com/yuesong-feng/30dayMakeCppServer)

* C++教程; C++服务开发

#### [#Python How To Use A Variable Number of Arguments in Python Functions](https://towardsdatascience.com/how-to-use-variable-number-of-arguments-in-python-functions-d3a49a9b7db6)

* python不定参数数量的方法
  * args 按位置输入
  * **kwargs 输入dict

#### [CS110L: Safety in System Programing](https://reberhardt.com/cs110l/spring-2021/)

* 斯坦福大学课程; Rust

### 异构硬件

#### [CPU性能和Cache](https://plantegg.github.io/2021/07/19/CPU%E6%80%A7%E8%83%BD%E5%92%8CCACHE/)

* CPU性能介绍

#### [CPU相关书籍推荐和部分芯片微架构](https://zhuanlan.zhihu.com/p/497495797?utm_source=com.microsoft.todos&utm_medium=social&utm_oi=49336847171584)

* CPU相关图书推荐; 另有多张CPU架构图片(如RISC-V)

#### [Tensil tutorial for YOLO v4 Tiny on Ultra96 V2](https://k155la3.blog/2022/04/04/tensil-tutorial-for-yolo-v4-tiny-on-ultra96-v2/?continueFlag=bfad8aef2f2b537615f634a87deb0d67)

* 在FPGA上实现了一个深度神经网络

### 系统原理

#### [openSUSE:系统分析和优化指南](https://thirdyouth.github.io/suse-system-tuning/index.html)

* 官方性能分析文档的中文翻译版

#### [PDF计算机体系结构:量化方法(PDF)](https://github.com/QSCTech/zju-icicles/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E4%BD%93%E7%B3%BB%E7%BB%93%E6%9E%84/%E6%95%99%E6%9D%90/%E7%AC%AC5%E7%89%88/%E8%AE%A1%E7%AE%97%E6%9C%BA%E4%BD%93%E7%B3%BB%E7%BB%93%E6%9E%84%EF%BC%9A%E9%87%8F%E5%8C%96%E7%A0%94%E7%A9%B6%E6%96%B9%E6%B3%95%EF%BC%88%E7%AC%AC%E4%BA%94%E7%89%88%EF%BC%89%EF%BC%88%E4%B8%AD%E6%96%87%E7%89%88%EF%BC%89.pdf)

* 教材推荐; 所在[repo](https://github.com/QSCTech/zju-icicles)为浙大计算机课程整理.

#### [eBPF完全入门指南](https://mp.weixin.qq.com/s?__biz=MzU1MzY4NzQ1OA==&mid=2247504531&idx=1&sn=a21527de08fcc3b2966f63b938e158f2&utm_source=tuicool&utm_medium=referral)

* eBPF介绍文章

#### [软件理论基础与实践](https://xiongyingfei.github.io/SF/2022/lectures)

* 北大课程;数理逻辑、形式语义、类型系统、Coq; 熊英飞

#### [chibicc](https://github.com/rui314/chibicc)

* c编译器实现;code 1w行;commit bugfree;

#### [osdt-weekly](https://github.com/hellogcc/osdt-weekly)

* 开源开发者工具周报; LLVM/GDB/TVM/QEMU/GCC等;

#### [南京大学:计算机系统基础](https://nju-projectn.github.io/ics-pa-gitbook/ics2022/)

* 与蒋炎岩操作系统基础一脉相承

### 博客推荐

#### [Interview Questions](https://github.com/cloudnloud/interview-questions)

* k8s/linux/git/docker/db等分领域问题

#### [博客推荐:关于数据库的一切](http://www.fmwconcepts.com/imagemagick/space/index.php)

* 博主: 罗济高; 数据库领域; PostgreSQL

#### [博客推荐:MorningSpace](https://morningspace.github.io/)

* k8s, git;

#### [计算机大佬博客推荐](https://weibo.com/7483028645/LoqqIvd5A)

* 个人:[yoshuabengio](https://yoshuabengio.org/?continueFlag=cdb48726f74fe95a2e0a2009a9d8d5b8)/[Peter Norvig](https://norvig.com/?continueFlag=cdb48726f74fe95a2e0a2009a9d8d5b8)/[Paul Graham(Y combinator)](http://www.paulgraham.com/?continueFlag=cdb48726f74fe95a2e0a2009a9d8d5b8)/[Scott Meyers](http://scottmeyers.blogspot.com/?continueFlag=cdb48726f74fe95a2e0a2009a9d8d5b8)
* 组织: [Microsoft Research](https://www.microsoft.com/en-us/research/blog/)/[MSRA](https://www.msra.cn/zh-cn/news)/[Google Research](https://ai.googleblog.com/?continueFlag=cdb48726f74fe95a2e0a2009a9d8d5b8)/[Meta Research](https://research.facebook.com/blog/)/[Linux Foundation](https://www.linuxfoundation.org/blog/?continueFlag=cdb48726f74fe95a2e0a2009a9d8d5b8)/[OREILLY](https://www.oreilly.com/radar/?continueFlag=cdb48726f74fe95a2e0a2009a9d8d5b8)/[MIT](https://news.mit.edu/)/[Y Combinator](https://www.ycombinator.com/blog?continueFlag=cdb48726f74fe95a2e0a2009a9d8d5b8)
* 语言: [Rust](https://blog.rust-lang.org/)/[C++](https://abseil.io/blog/?continueFlag=cdb48726f74fe95a2e0a2009a9d8d5b8)/[Test](https://testing.googleblog.com/?continueFlag=cdb48726f74fe95a2e0a2009a9d8d5b8)

#### [BlogHub](https://bloghub.fun/?utm_campaign=%E9%87%8E%E7%94%9F%E6%9E%B6%E6%9E%84%E5%B8%88&utm_medium=email&utm_source=Revue%20newsletter)

* 国内技术博客聚合

#### [GithubRank](https://githubrank.com/?utm_campaign=%E9%87%8E%E7%94%9F%E6%9E%B6%E6%9E%84%E5%B8%88&utm_medium=email&utm_source=Revue%20newsletter)

* github大佬排名

### 实用工具

#### [vim帮助文档](https://yianwillis.github.io/vimcdoc/doc/help.html)
#### [gperftools](https://luyuhuang.tech/2022/04/10/gperftools.html)

* gperf tools的几种使用方法

#### 图书下载网站

* [bookzz](https://www.bookzz.ren/?continueFlag=cdb48726f74fe95a2e0a2009a9d8d5b8)
* [zlib](https://zh.libsolutions.net/?continueFlag=cdb48726f74fe95a2e0a2009a9d8d5b8)
* [libgen](https://libgen.li/index.php)

#### [VSCode解决Vim插件不能使用ctrl-c的问题](https://blog.csdn.net/sea_snow/article/details/83375726)

* File -> Preference -> Settings->vim.useCtrlKeys:false

#### [Markdown表格内如何进行换行?](https://blog.csdn.net/microcosmv/article/details/51868178)

* html换行符```<br>```

#### [Linux下调试与性能分析工具的总结](https://developer.aliyun.com/article/632400)

* kernel ftrace工具使用
  * 位于/sys/kernel/debug/trace路径下
* gdb的一些使用命令
* valgrind使用命令

#### [Fred's ImageMagick Scripts](http://www.fmwconcepts.com/imagemagick/space/index.php)

* 图像处理脚本

#### [How to add a new audio (not mixing) into a video using ffmpeg?](https://stackoverflow.com/questions/11779490/how-to-add-a-new-audio-not-mixing-into-a-video-using-ffmpeg#11783474)

* 详细解释了如何使用ffmpeg为视频增加音轨

#### [awesome-latex-drawing](https://github.com/xinychen/awesome-latex-drawing)

* latex画图教程

#### [魔都头像生成器](https://h5.moo-e.com/roomis/?continueFlag=cdb48726f74fe95a2e0a2009a9d8d5b8)

#### [warp](https://www.warp.dev/)

* 新型终端; MacOS

#### [nitter](https://nitter.net/)

* twitter的新浏览方式, 可以直接搜索用户并浏览, 风格清爽; 代码库在[这里](https://github.com/zedeus/nitter)

#### [HertzBeat](https://github.com/dromara/hertzbeat)

* 云监控系统

### 日常生活

#### [非常时期囤货指南](https://github.com/toutiaoio/A-Guide-To-Stockpiling)

* 列举封城前需要购买的物资

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

#### [How to solve "ptrace operation not permitted" when trying to attach GDB to a process?](https://stackoverflow.com/questions/19215177/how-to-solve-ptrace-operation-not-permitted-when-trying-to-attach-gdb-to-a-pro)

* ptrace can't run with gdb

#### [tmux: Getting extra characters when pasting](https://github.com/ChrisJohnsen/tmux-MacOSX-pasteboard/issues/31#issuecomment-56107455)

* tmux 粘贴时候有多余字符: ```printf '\e[?2004l'``` 或者 ```printf '\e[?2004h'```

#### [strace: 谁杀了我的进程](https://www.cnblogs.com/xybaby/p/8098229.html)

* ```strace -T -tt -e trace=all -p 1035```
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
