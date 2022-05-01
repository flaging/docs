# 福来鸽的网络周报

## 2022-04-30

### 机器学习

#### [数据中心白皮书](http://www.caict.ac.cn/kxyj/qwfb/bps/202204/t20220422_400391.htm)

* 中国信通原报告;2022年4月;全文下载:[PDF](http://www.caict.ac.cn/kxyj/qwfb/bps/202204/P020220422707354529853.pdf)

#### [Real World Recommendation System - Part 1](https://blog.fennel.ai/p/real-world-recommendation-system?s=r)

* 推荐系统介绍,第二部分尚未更新

#### [【Transformer 所有模型串讲】Auto-encoding模型 -Bert 1](https://zhuanlan.zhihu.com/p/493932190)

* 简介transformer;[专栏](https://www.zhihu.com/column/c_1380571607480651776)共有5节.

#### [Transformer性能优化：运算和显存](https://zhuanlan.zhihu.com/p/474554018)

* transformer分析和优化.

#### [onnx-opcounter](https://github.com/gmalivenko/onnx-opcounter)

* onnx的数据量和计算量解析工具,并不是特别好用

#### [onnx2torch](https://github.com/ENOT-AutoDL/onnx2torch?fbclid=IwAR1HpWxialVy-ILdHUYR8CJ_EsUyxbjhrMkZbWPWkQ0DuNuwvYDEpNVuhqc)

* onnx转pytorch工具: 看起来是转换了,但是对象类型还是和原生pytorch代码不太一样

#### [onnx-simplifier](https://github.com/daquexian/onnx-simplifier)

* onnx简化工具

#### [PaddleDetection](https://github.com/PaddlePaddle/PaddleDetection)

* paddle目标检测套件

#### [Can't find model 'de_core_news_sm'... only on debug mod](https://github.com/explosion/spaCy/issues/4638)

* 数据集下载问题
* ```python -m spacy download de_core_news_sm```

#### [ONNX 模型分析与使用](https://zhuanlan.zhihu.com/p/371177698)

* ONNX proto的解析, 万物皆可proto

#### [pytorch-opCounter](https://github.com/Lyken17/pytorch-OpCounter)

* thop, 计算量和数据量检测
* 同类产品还有torchsummary/torchstat

#### [onnx2torch](https://github.com/ENOT-AutoDL/onnx2torch)

* onnx转换为torch
* 但是转换后的torch模型并不能用thop计算数据量

#### [PyTorch 内部机制(翻译)](https://archwalker.github.io/blog/2019/05/27/pytorch-internals.html)

* pytorch原理解析
* 另原版本在[这里](http://blog.ezyang.com/2019/05/pytorch-internals/)

#### [Tensorflow Proto](https://github.com/tensorflow/tensorflow/blob/master/tensorflow/core/protobuf/meta_graph.proto)

* Tensorflow的Proto定义

#### [基于onnx的网络裁剪](https://zhuanlan.zhihu.com/p/212893519)

* onnx网络修改方法介绍

### 编程语言

#### [Policy](http://www.modernescpp.com/index.php/policy-and-traits)

* C++新特性; 本网站值得关注

#### [#python Think in Python 2e](https://tairraos.github.io/ThinkPython/index.html)

* 一本python教程

#### [#C++ C++程序设计](https://www.bilibili.com/video/BV1Vf4y1P7pq?spm_id_from=333.999.0.0)

* b站课程; 南方科大于仕琪(openCV中国团队负责人), 另外主页还有[HID2021](https://space.bilibili.com/519963684/channel/seriesdetail?sid=323687&ctype=0)和[HID2020](https://space.bilibili.com/519963684/channel/seriesdetail?sid=323689&ctype=0)的论文解读

### 异构硬件

#### [FPGA并行编程](xupsh.github.io/pp4fpgas-cn/)

* FPGA编程;Parallel Programming for FPGAs的中文翻译版

### 系统原理

#### [You should be reading academic computer science papers](https://stackoverflow.blog/2022/04/07/you-should-be-reading-academic-computer-science-papers/)

* stackoverflow 官方博客推荐阅读计算机论文
* 论文集
  * [Great Papers in Computer Science(1996)](https://www.google.com/books/edition/Great_Papers_in_Computer_Science/GmgZAQAAIAAJ?hl=en&kptab=overview)
  * [Ideas That Created the Future--Classic Papers of Computer Science(2021)](https://mitpress.mit.edu/books/ideas-created-future)
  * [Papers we love(github)](https://github.com/papers-we-love/papers-we-love)
* 论文
  * [Dynamo: Amazon's High Available Key Value Store](https://github.com/papers-we-love/papers-we-love/blob/f28b9c9f6c52a81aa9e60521c794f1c3aeafa9a7/datastores/dynamo-amazons-highly-available-key-value-store.pdf)
  * [A Unified Theory of Garbage Collection](https://www.cs.cornell.edu/courses/cs6120/2019fa/blog/unified-theory-gc/)
  * [Communicating Sequential Processes](http://www.cs.ucf.edu/courses/cop4020/sum2009/CSP-hoare.pdf)
  * [Out of the Tar Pit](https://github.com/papers-we-love/papers-we-love/blob/f28b9c9f6c52a81aa9e60521c794f1c3aeafa9a7/design/out-of-the-tar-pit.pdf)
* 视频集
  [Youtube: PapersWeLove](https://www.youtube.com/c/PapersWeLove/videos)


#### [Docker中如何限制CPU的使用](http://learn.lianglianglee.com/%E4%B8%93%E6%A0%8F/%E5%AE%B9%E5%99%A8%E5%AE%9E%E6%88%98%E9%AB%98%E6%89%8B%E8%AF%BE/05%20%E5%AE%B9%E5%99%A8CPU%EF%BC%881%EF%BC%89%EF%BC%9A%E6%80%8E%E4%B9%88%E9%99%90%E5%88%B6%E5%AE%B9%E5%99%A8%E7%9A%84CPU%E4%BD%BF%E7%94%A8%EF%BC%9F.md)

* 限制CPU使用的原理

#### [LLVM之父Chris Lattner：编译器的黄金时代](https://zhuanlan.zhihu.com/p/500904014?utm_source=com.microsoft.todos&utm_medium=social&utm_oi=49336847171584)

* 编译器从AI编译器开始复兴, 目前已经有星星之火可以燎原之势了.

#### [TCP性能和发送接收窗口、Buffer的关系](https://plantegg.github.io/2019/09/28/%E5%B0%B1%E6%98%AF%E8%A6%81%E4%BD%A0%E6%87%82TCP--%E6%80%A7%E8%83%BD%E5%92%8C%E5%8F%91%E9%80%81%E6%8E%A5%E6%94%B6Buffer%E7%9A%84%E5%85%B3%E7%B3%BB/)

* 网络协议栈解析

#### [CS-143 斯坦福编译原理(中文翻译)](https://www.bilibili.com/video/BV1cE411f78c/)

本文是bilibili搬运版,并且不完整;课程在[斯坦福页面官网](https://web.stanford.edu/class/cs143/), youtube上有15集的英文版(在[这里](https://www.youtube.com/watch?v=SNWHmnWzJAI&list=PLoCMsyE1cvdUZRe1udlyjpzTww1U5olL2&ab_channel=LectureArchive)), b站还有该课程的[补充部分](https://www.bilibili.com/video/BV1oE411V7cd/)

#### [现代存储系统背后的算法](https://iswade.github.io/translate/btree_vs_lsmtree/)

* 主要讲解存储系统的B-tree和LSM-tree区别

#### [2015 CMU 15-213 CSAPP 深入理解计算机系统 课程视频](https://www.bilibili.com/video/BV1iW411d7hd?from=search&seid=11952614108851410743)

* 视频教程;字幕在[这里](https://github.com/EugeneLiu/translationCSAPP)

#### [从零开始的UEFI裸机编程](https://kagurazakakotori.github.io/ubmp-cn/index.html)

* UEFI编程教程;无需依赖库

#### [Implementing a Key-Value Store](https://codecapsule.com/2012/11/07/ikvs-implementing-a-key-value-store-table-of-contents/?continueFlag=0c2f362fd425fbeef707eadd88e1a6bd)

* KV存储也是一个可以研究的话题

#### [eBPF入门与实践指南](https://mp.weixin.qq.com/s/7PzowwNYSwmSNe-3NxX2gw)

* eBPF成为了一个标准的高性能执行引擎

#### [计算机体系结构基础(胡伟武)](https://github.com/foxsen/archbase)

* 龙芯版教材

### 实用工具

#### [打印源代码行](https://wizardforcel.gitbooks.io/100-gdb-tips/content/print-source-lines.html)

* gdb打印源代码技巧

#### [gdb调试的layout使用](https://www.cnblogs.com/dylancao/p/9213235.html)

* gdb有不同的layout, 比如src/asm/split等

#### [用Valgrind检测内存泄漏](https://yuanfentiank789.github.io/2018/11/01/%E7%94%A8Valgrind%E6%A3%80%E6%B5%8B%E5%86%85%E5%AD%98%E6%B3%84%E6%BC%8F/)

* valgrind使用教程

#### [Creating a cluster with kubeadm](https://kubernetes.io/docs/setup/production-environment/tools/kubeadm/create-cluster-kubeadm/)

* 创建k8s集群

#### [如何使用 pprof 调试 golang 应用](https://wallenotes.github.io/2020/04/05/%E7%BC%96%E7%A8%8B/%E8%B0%83%E8%AF%95/how-to-use-go-pprof/)

* gperftool使用方式
* 使用教程2:[cpuprofiler](https://gperftools.github.io/gperftools/cpuprofile.html),[heapprofiler](https://gperftools.github.io/gperftools/heapprofile.html)
* 使用教程3:[网址](https://cloud.tencent.com/developer/article/1433465)
* 使用教程4:[网址](https://www.openjq.com/thread-6858-1-1.html)
* 使用教程5:[网址](https://github.com/NIGHTFIGHTING/gperftools-tutorial)

#### [Execute an instruction/command in gdb](https://stackoverflow.com/questions/63533955/execute-an-instruction-command-in-gdb)

* starti命令无法使用

#### [Linux-Shell](http://datascript.top/2021/06/03/linux-shell/?continueFlag=7518eeeb402c5210c2d1940add6896ba)

* 博主整理的一些常用linux命令

#### [Dockerfile ENV](https://yeasy.gitbook.io/docker_practice/image/dockerfile/env)

* ```ENV <KEY1>=<VAL1> <KEY2>=<VAL2> ...```
* ```ARG <KEY1>=<VAL1> <KEY2>=<VAL2> ...```, 见[这里](https://zhuanlan.zhihu.com/p/119301742)

#### [in linux which source return nothing](https://stackoverflow.com/questions/17487514/in-linux-which-source-returns-nothing)

* source是bash命令,在sh中没有,所以某些docker中sh运行脚本时候source找不到命令

#### [Docker容器中运行ls，出现ls: can't open '.': Permission denied错误](https://blog.csdn.net/weixin_38469592/article/details/92803993)

* docker内ls失败的错误: selinux权限严格
* 解决方法
  * 临时: 添加参数```--privileged=true```
  * 更改权限:```chcon -Rt svirt_sandbox_file_t <dir>```
  * 更改selinux配置:```setenforce 0```

#### [Copy directory to another directory using ADD command](https://stackoverflow.com/questions/26504846/copy-directory-to-another-directory-using-add-command)

* 向docker中拷贝文件夹; Dockerfile
* ```ADD go /usr/local/```

#### [Linux lsof command explained with 12 practical examples](https://vitux.com/linux-lsof-command-explained-with-12-practical-examples/)

* lsof命令介绍

#### [lookscanned](https://github.com/rwv/lookscanned.io)

* 将PDF转换为扫码格式

#### [60秒完成Linux系统的性能分析(译)](https://jeremyxu2010.github.io/2019/12/60%E7%A7%92%E5%AE%8C%E6%88%90linux%E7%B3%BB%E7%BB%9F%E7%9A%84%E6%80%A7%E8%83%BD%E5%88%86%E6%9E%90%E8%AF%91/#heading)

* 一些排查工具介绍; 原文在[这里](https://netflixtechblog.com/linux-performance-analysis-in-60-000-milliseconds-accc10403c55)
* 同系列:[其他排查工具介绍](https://netflixtechblog.com/netflix-at-velocity-2015-linux-performance-tools-51964ddb81cf)

#### [netstat的实现方法分析](http://jialeicui.github.io/blog/netstat.html)

* linux万物皆文件, 可以从虚拟文件系统中找到对应的状态值.

#### [docker从入门到实践](https://yeasy.gitbook.io/docker_practice/)

* docker使用教程

#### [新式 Linux 命令行工具大全](https://linux.cn/article-14488-1.html?utm_source=rss&utm_medium=rss)

* Linux工具类型和功能整理

#### [The AWK Programming Language(中译)](github.com/wuzhouhui/awk)

* awk也可以被看作为一种语言

#### [Shell 程序设计教程](http://kuanghy.github.io/shell-tutorial/)

* 一个shell教程

#### [强制删除 StatefulSet 中的 Pods](https://kubernetes.io/zh/docs/tasks/run-application/force-delete-stateful-set-pod/)

* ```kubectl delete pods <pod> --grace-period=0 --force```

#### [ui.vision](https://ui.vision/)

* 网页自动化工具;自动化表单填写

#### [mermaid](https://github.com/mermaid-js/mermaid)

* 流程图引擎;github已支持,但gitpage尚未支持

### 工作生活

#### [微博-微彰琦谈:哑铃型读书策略](https://weibo.com/1102141664/LpJF6tZOf)

* 哑铃型读书策略
  * 一头重点读最经典的框架性基础书籍，比如历史，哲学和经济学基础书籍
  * 另一头是所在领域的工具书，以证券领域为例，证券、基金等从业资格丛书系列，CFA和CPA系列
* 基础书籍推荐
  * 乔治·韦尔斯 《全球通史》
  * 《剑桥中国史》
  * 冯友兰 《中国哲学简史》
  * 理查德·塔纳斯 《西方思想史》
  * 何兆武 《西方哲学精神》
  * 吴国盛 《科学的历程》
  * 萨缪尔森 《经济学 18版》
  * 托马斯·索维尔 《经济学的思维方式》

#### [微博视频:风骚律师前情回顾](https://weibo.com/tv/show/1034:4760808513798230?from=old_pc_videoshow)

* 据说最新一季评分很高哦

#### [handle-汉兜](https://github.com/antfu/handle)

* 填词小游戏,每天更新所猜的词语

#### [New graduate EU offers - is It possible to negotiate?](https://ludoro.github.io/blog/career/2022/02/14/newgrad.html)

* 博主介绍了欧洲公司的招聘和面试情况

#### [Cook](https://github.com/YunYouJun/cook)

* 隔离食材做饭教程; 本教程还参考了一个名为"隔离食用大全"的[腾讯文档](https://docs.qq.com/sheet/DZUpJS0tQZm1YYWlt?tab=9ups24).

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
