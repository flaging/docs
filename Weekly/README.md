# 福来鸽的网络周报

## 2022-05-07

### 机器学习

#### [Deep Learning Interviews book: Hundreds of fully solved job interview questions from a wide range of key topics in AI.](https://github.com/BoltzmannEntropy/interviews.ai)

* AI interview教程

#### [MetaSeq](https://github.com/facebookresearch/metaseq)

* OPT: Open Pretrained Transformer

#### [The Hugging Face Deep Reinforcement Learning Class](https://github.com/huggingface/deep-rl-class)

#### [论文:OPT: Open Pre-trained Transformer Language Models](https://arxiv.org/abs/2205.01068)

* 程序在[这里](https://github.com/facebookresearch/metaseq), 论文在[这里](https://arxiv.org/pdf/2205.01068)

#### [复旦大学邱锡鹏](https://xpqiu.github.io/)

* NLP论文集
* [如何写好科研论文](https://xpqiu.github.io/slides/%E5%A6%82%E4%BD%95%E5%86%99%E7%A7%91%E7%A0%94%E8%AE%BA%E6%96%87202203.pdf)

#### [知识图谱可视化技术在美团的实践与探索](https://tech.meituan.com/2022/04/14/the-practice-and-exploration-of-knowledge-graph-visualization-technology-in-meituan.html)

#### [The Kaggle Book](https://github.com/PacktPublishing/The-Kaggle-Book)

* kaggle竞赛讲解

#### [DALL-E 2 - Pytorch](https://github.com/lucidrains/DALLE2-pytorch)

* text-to-image

#### [在 Python 中使用机器学习来检测钓鱼链接](https://linux.cn/article-14535-1.html?utm_source=feedly&utm_medium=rss)

* 随机森林

#### [Text Summarization with Huggingface Transformers and Python](https://rubikscode.net/2022/04/25/text-summarization-with-huggingface-transformers/)

* 文本摘要

#### [paperwithcode:Bringing Old Films Back to Life](https://paperswithcode.com/paper/bringing-old-films-back-to-life)

#### [ML and NLP Publications in 2021](https://www.marekrei.com/blog/ml-and-nlp-publications-in-2021/)

* 机器学习趋势总结

#### [NLP-Paper](https://github.com/DengBoCong/nlp-paper)

* 字节跳动; NLP论文代码整理;
* 包含 NLP 领域下的对话语音领域，复现模型以及数据处理

#### [斯坦福Chris Manning: 大模型剑指通用人工智能？](https://mp.weixin.qq.com/s/pnd2Q-5duMtL0OLzrDJ2JA)

#### [Goopt](https://github.com/jokenox/Goopt)

* 基于GPT-3的搜索引擎

#### [huggingface onnx export](https://github.com/huggingface/notebooks/blob/main/examples/onnx-export.ipynb)

* huggingface官方文档:onnx模型导出

#### [第十七章 模型压缩及移动端部署](https://csbwang.github.io/dl_ch17)

* 深度学习教程;共18章,全文可看[这里](https://csbwang.github.io/tags.html)

#### [Tvm一些基本技术](https://wujianming110117.blog.csdn.net/article/details/115782177)

* 算子融合;数据变换;张量优化

#### [Welcome to Paddle-Inference’s documentation!](https://paddle-inference.readthedocs.io/en/latest/)

* paddle推理引擎

#### [transformer库快速体验文本生成](https://weibo.com/1402400261/Lqc4B8JGw)

![图片](https://wx3.sinaimg.cn/mw2000/5396ee05ly1h1muj5to5yj21ey0tujx5.jpg)

#### [ML-Notebooks](https://github.com/dair-ai/ML-Notebooks)

* pytorch教程

### 异构硬件

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

### 编程语言

#### [Svar, A Tiny Modern C++ Header Brings Unified Interface for Different Languages](https://github.com/zdzhaoyong/Svar)

* 多语言接口

#### [Go编程语言与环境](https://dl.acm.org/doi/10.1145/3488716)

* go语言综述,来自语言核心团队,pdf版在[这里](https://dl.acm.org/doi/pdf/10.1145/3488716)

#### [BTree implementation for Go](https://github.com/google/btree)

* google官方的go语言btree实现

#### [PL Papers You Might Love](https://newsletter.papersyoumightlove.pl/)

* program language papers, rss链接在[这里](https://newsletter.papersyoumightlove.pl/)

#### [现代化 C 使用体验](https://liujiacai.net/blog/2022/04/30/modern-c/)

#### [Using std::chrono](https://akrzemi1.wordpress.com/2022/04/11/using-stdchrono/)

* chrono库介绍

#### [Three Benchmarks of C++20 Ranges vs Standard Algorithms](https://www.cppstories.com/2022/ranges-perf/)

* C++测试

#### [reloadium](https://github.com/reloadware/reloadium)

* python 变量实时显示插件; 目前只支持pycharm

#### [C 语言编程透视](https://tinylab-1.gitbook.io/cbook/?continueFlag=5736f6f7a67304664b0f56b2e45e0238)

* C语言教程

#### [learncpp](https://www.learncpp.com/)

* C++知识点查阅

#### [redb](https://github.com/cberner/redb)

* KV-store;rust

#### [C++ Concurrency in Action 2ed 笔记](https://github.com/downdemo/Cpp-Concurrency-in-Action-2ed)

#### [C++编译器中的优化](fuzhe1989.github.io/2020/01/22/optimizations-in-cpp-compilers/)

* 编译器和代码生产方面的概念
* 编译器为你所做的令人印象深刻的转换工作
* 优化方式的一些实际例子

#### [Linux下跨语言调用C++实践](https://tech.meituan.com/2022/04/21/cross-language-call.html)

* 美团;java/python调用C++

#### [Go语言从入门到精通](https://github.com/java-aodeng/golang-examples)

* go语言教程

### 系统原理

#### [@博客推荐: 何照江的微博](https://hezhaojiang.github.io/)

* 音视频算法与数据结构

#### [Computer Network: A Top-Down approach 8-th edition](https://gaia.cs.umass.edu/kurose_ross/wireshark.php)

* 教材

#### [谷歌工程实践文档](https://jimmysong.io/eng-practices/)

* 内含[代码审查者指南](https://jimmysong.io/eng-practices/docs/review/reviewer/)和[代码开发者指南](https://jimmysong.io/eng-practices/docs/review/developer/)

#### [如何写出高性能代码之优化内存回收(GC)](https://segmentfault.com/a/1190000041787331)

#### [Linux中基于eBPF的恶意利用与检测机制](https://tech.meituan.com/2022/03/29/how-to-detect-bad-ebpf-used-in-linux.html)

#### [CMU-15445 数据库内核(中文讲解)](https://www.bilibili.com/video/BV1bQ4y1Y7iT/?spm_id_from=333.788)

* 将课程用中文讲解了一遍,适合中文选手
* 作者微博[@许晓笛](https://weibo.com/u/1068096134)

#### [关于 TCP, 我学到什么](https://111hunter.github.io/2021-01-08-tcp/)

#### [Distributed Systems Shibboleths](https://jolynch.github.io/posts/distsys_shibboleths/)

* 分布式系统的一些观点

#### [一个周末掌握光线追踪教程](https://xjoshua.github.io/tags/#Render)

* 光线追踪,图形学

#### [LLVM GPU Working Group Meeting Agenda / Notes](https://docs.google.com/document/d/1m_oSe1HwtWdQ2JUmMRTAVHbUS7Dv4MRsqptiYcgK6iI/mobilebasic#bookmark=id.i5jobxbcv8r7)

* LLVM GPU组的会议记要,格式十分好看

#### [PranaDB](https://github.com/cashapp/pranadb)

* ```PranaDB = kafka + SQL```

#### [Operating Systems](https://oscourse.org/)

* 浙大操作系统教学网站

#### [分布式论文经典《Time, Clocks, and the Ordering of Events in a Distributed System》](https://www.microsoft.com/en-us/research/publication/time-clocks-ordering-events-distributed-system/)

* [中文译文](https://ouonline.net/time-clocks-and-the-ordering-of-events-in-a-distributed-system-cn?continueFlag=662acb971541af40cb0fe9bfa562324c)
* 微博[@张铁蕾](https://weibo.com/n/%E5%BC%A0%E9%93%81%E8%95%BE)解读:[全文](http://zhangtielei.com/posts/blog-time-clock-ordering.html?continueFlag=662acb971541af40cb0fe9bfa562324c)

#### [写给入门者的LLVM介绍](https://zhuanlan.zhihu.com/p/472813616)

#### [四大功能！带你初识 Fabric | 容器网络系列第2期](http://weekly.dockone.io/article/2434894)

* 容器网络介绍

#### [ETCD源码剖析](https://csunny.gitbook.io/etcd)

#### [深入分析LINUX内核源码](http://www.kerneltravel.net/book/)

* Linux内核源码解读;
* [本博客](http://www.kerneltravel.net/)还有许多内核相关资料

#### [http2 explained](https://http2-explained.haxx.se/zh/part1)

* http2介绍;多语言支持(中英等)

#### [redis-3.0-annotated](https://github.com/huangz1990/redis-3.0-annotated)

* redis注释版

#### [The Adventures of OS: Making a RISC-V Operating System using Rust](https://osblog.stephenmarz.com/)

* rust;risc-v;OS
* 后续更新在[这里](https://blog.stephenmarz.com/category/os/)

#### [eBPF编程指北](https://mp.weixin.qq.com/s/6CU61NDq-_96jVv8aVar_g)

* eBPF编程教程

#### [udev文件系统的使用和基本工作原理分析](https://blog.51cto.com/lukeguo/1242460)

* udev介绍;[简介2](https://www.cnblogs.com/zhouhbing/p/4025748.html);

#### [设计模式二三事](https://tech.meituan.com/2022/03/10/interesting-talk-about-design-patterns.html)

* 美团技术:[网站](https://tech.meituan.com/)

#### [Transparently running binaries from any architecture in Linux with QEMU and binfmt_misc](https://ownyourbits.com/2018/06/13/transparently-running-binaries-from-any-architecture-in-linux-with-qemu-and-binfmt_misc/?continueFlag=5736f6f7a67304664b0f56b2e45e0238)

* 应用运行,虚拟,QEMU,Linux

#### [《设计数据密集型应用》中文翻译](https://github.com/Vonng/ddia)

* 数据密集型应用; 设计

#### [60秒完成Linux系统的性能分析(译)](https://jeremyxu2010.github.io/2019/12/60%E7%A7%92%E5%AE%8C%E6%88%90linux%E7%B3%BB%E7%BB%9F%E7%9A%84%E6%80%A7%E8%83%BD%E5%88%86%E6%9E%90%E8%AF%91/)

* netflix, [原文](https://medium.com/netflix-techblog/linux-performance-analysis-in-60-000-milliseconds-accc10403c55)

#### [操作系统-死锁](jasonxqh.github.io/2021/05/17/操作系统-死锁/)

* 什么是死锁、死锁的条件是什么、死锁如何预防、活锁是什么等

#### [分布式系统的一致性与共识算法的博文](https://weibo.com/2194035935/LpTU7gj1j)

* [分布式系统的一致性与共识算法-基础理论](chinalhr.github.io/post/distributed-systems-consistency-consensus-algorithm/)
* [分布式系统的一致性与共识算法-Paxos](chinalhr.github.io/post/distributed-systems-consensus-algorithm-paxos/)​​​

#### [Algorithms for Decision Making](https://algorithmsbook.com/files/dm.pdf)

* 决策算法;另有同类图书,在[这里](https://algorithmsbook.com/optimization/#)

#### [Linux网络内核源码分析](xingkunz.github.io/tags/源码/)

* 共5篇,内核源码分析类

#### [从0开始的计算机科学-状态与编码](suquark.github.io/lecture/2017/08/01/cs_from0_state_and_encode.html)

* 计算机的一些最基本的要素的认知

#### [linux内核环形队列kfifo](jarsonfang.github.io/Kernel/内核数据结构/kfifo/)

* kfifo, kernel内的fifo实现

### 实用工具

#### []

#### [What are your most used self-hosted applications? (noted.lol)](https://news.ycombinator.com/item?id=31260061)

* [Nginx Proxy Manager](https://github.com/NginxProxyManager/nginx-proxy-manager): Proxy for self hosted service
* [Portainer](https://github.com/portainer/portainer): Docker management
* [Ghost](https://github.com/TryGhost/Ghost): writing materials management
* [filebrowser](https://github.com/filebrowser/filebrowser): files
* [AzuraCast](https://github.com/AzuraCast/AzuraCast): music stream
* [Tube Archivist](https://github.com/tubearchivist/tubearchivist): youtube media server
* [grafana](https://github.com/grafana/grafana): monitor
* [Linkding](https://github.com/sissbruecker/linkding): bookmarks
* [Audiobookshelf](https://github.com/advplyr/audiobookshelf)
* [Final Notes and Thoughts](https://noted.lol/tag/self-hosting/): notes
* Nextcloud: for caldav and carddav calendar, contacts, and tasks
* Xbrowsersync - sync bookmarks across device
* Synchthing - backup data from my phone. I use Neo Backup to take a snapshot of all apps, so the phone should theoretically be restorable from scratch.
* Jellyfin - Spotify replacement. The Finamp app is fantastic.
* Home Assistant - automate my media center, as well as control outdoor lights and door locks, and check if any doors or windows are open or unlocked when I'm away.
* OPNSense on a protectli box - amazing open source gateway software that does everything.
* AdGuard Home (on OPNSense) - DNS based ad blocking
* Wireguard (on OPNSense) - allows me to have an always on partial tunnel VPN on my phone and laptops that allows access to home services while remote, and also allows me to use my Ad Guard DNS.
* HAProxy + LetsEncrypt (on OPNSense) - setup to provide subdomains for each of the services at home. Only a couple are public (contacts and calendar), but the rest become available when the VPN is on.
* Smokeping - use it to collect data to rub into Spectrums face when they go down.
* Pintry - Pinterest clone
* Xbrowsersync - sync bookmarks across device

* cadvisor - simple graphs of resource consumption, insights per docker stack
* cyberchef - a LOT of handy operations packed into one small app. Encode/decode any secrets you need and don't bother about privacy
* dozzle - logs browser from all docker stacks
* gogs - git mirror
* heimdall - all apps main panel
* minio - private S3 for my side projects
* nextcloud - private google drive / dropbox
* photoprism - photo management
* pypiserver - private pypi
* registry - docker registry (with UI)
* traefik - reverse proxy of all these services
* portainer - easily manage all of the above.
* Wiki (linked from one of the githubs, has links to all apps and more info than the githubs): https://wiki.servarr.com/
* Lidarr (Music): https://github.com/Lidarr/Lidarr
* Radarr (Movies): https://github.com/radarr/radarr
* Readarr (Books): https://github.com/readarr/readarr
* Sonarr (TV): https://github.com/sonarr/sonarr
* Router - pfSense - https://www.pfsense.org/
* Movies/TV/Home Videos - Plex
* Minecraft Server - AMP - https://cubecoders.com/AMPInstall
* Music - Roon - https://roonlabs.com/
* Automation - HomeAssistant - https://www.home-assistant.io/
* Unifi Controller
* Email - Zimbra - https://www.zimbra.com/downloads/
* Files - Synology

#### [Bash-Oneliner](https://github.com/onceupon/Bash-Oneliner)

* 脚本命令解析

#### [Google 开源项目风格指南——中文版](https://zh-google-styleguide.readthedocs.io/en/latest/)

#### [中文技术文档写作风格指南¶](https://zh-style-guide.readthedocs.io/zh_CN/latest/index.html)

#### [Weibo Spider](https://github.com/dataabc/weiboSpider)

* 微博用户爬虫工具

#### [一日一技：如何批量给PDF添加水印？](https://www.kingname.info/2022/05/05/add-watermark-on-pdf/#more)

#### [Starship](https://starship.rs/zh-cn/)

* 终端,在多端上有相同的使用体验

#### [微博@plantegg:脚本执行时候的一些错误](https://weibo.com/1667773473/LrzEtk4cn)

* login shell与no-login shell的区别
  * login shell: /etc/profile --> ~/.bash_profile --> ~/.bashrc --> /etc/bashrc
  * no-login shell: ~/.bashrc --> /etc/bashrc
* sh 跟bash的区别
  * 实际上是bash有没开启POSIX模式的区别
  * /bin/sh 相当于/bin/bash --posix

#### [Super Fast YouTube to MP3/MP4 Converter](https://4fuun.com/)

#### [Mac Setup for Web Development [2022]](https://www.robinwieruch.de/mac-setup-web-development/)

* Mac配置流程

#### [bilibili2local](https://github.com/sansui-orz/bilibili2local)

* B站视频下载工具

#### [Linux 二零](https://itboon.github.io/linux-20/)

* debian/ubuntu实用教程

#### [kill the newsletter](https://kill-the-newsletter.com/)

* 将newsletter转换为RSS

#### [cheatsheets](https://github.com/laylacodes/cheatsheets)

* 一些速查清单
* SQLjoin的解释清单:[这里](https://github.com/laylacodes/cheatsheets/blob/main/SQL_joins_cheatsheet.pdf)

#### [macosicons](https://macosicons.com/#/)

* Mac下的图标下载

#### [Blush](https://github.com/arsham/blush)

* Grep with colours

#### [gdb cheetsheet](https://www-users.york.ac.uk/~mijp1/teaching/2nd_year_Comp_Lab/guides/GDB_Cheat_Sheet.pdf)

#### [contentideas](https://contentideas.io/)

* 类似搜索引擎

#### [技术博客地址合集:blogsurf](https://blogsurf.io/directory)

#### [抖珍藏](https://douzhencang.com/)

* 抖音下载插件, 下载在[这里](https://microsoftedge.microsoft.com/addons/detail/kaepaapgaokpobjhamjjekinijbcoihe)

#### [youtube-enhancer](https://chrome.google.com/webstore/detail/youtube-enhancer/ejcniippeghnejiodjkkmndlelbagmah)

* chrome插件

#### [缩短命令、调整按键、自动补全，这些代码值得你放进 PowerShell 配置文件](https://sspai.com/post/73019)

#### [素生](https://z.arlmy.me/)

* 博客推荐

#### [blog finder](https://bf.zzxworld.com/)

* 博客集

#### [Best Paper Awards in Computer Science](https://jeffhuang.com/best_paper_awards/)

* 历年最佳论文

#### [Azure Speech Download](https://www.appinn.com/azure-speech-download/)

* 微软文字转语音功能
* 下载:[油猴脚本](https://greasyfork.org/zh-CN/scripts/444347-azure-speech-download), [命令行工具](https://github.com/kxxt/aspeak)

#### [mirror-leech-telegram-bot](https://github.com/anasty17/mirror-leech-telegram-bot)

* Aria/qBittorrent Telegram mirror/leech bot
* 将torrent备份至telegram或者google drive

#### [Containerization of CUDA environment using VSCode](https://blog.kbegiedza.eu/setup-cuda-developement-with-vscode)

* vscode cuda环境

#### [Meilisearch](https://github.com/meilisearch/meilisearch)

* 搜索系统,官网在[这里](https://www.meilisearch.com/)

#### [Brendan Gregg's Blog](https://www.brendangregg.com/blog/2022-05-02/brendan-at-intel.html)

* 火焰图作者跳槽去了intel, 他的博客有许多性能分析相关内容和教程
* 博客在[这里](https://www.brendangregg.com/)
* 这条信息的[HN](https://news.ycombinator.com/item?id=31236157)中, 还有一些其他好玩的信息
  * [Unusual Disk Latency](https://www.brendangregg.com/blog/2008-12-31/unusual-disk-latency.html)
    * 声音对硬盘延迟有很大影响
    * 实验视频:[Youtube](https://youtu.be/tDacjrSCeq4)
  * [magic-trace](https://github.com/janestreet/magic-trace)
  * [finding a guiding principal for work](https://www.youtube-nocookie.com/embed/PUv66718DII)

#### [Spacedrive](https://github.com/spacedriveapp/spacedrive)

* 文件管理器,MacOS, 将来会支持所有端

#### [Blog is A Room](http://nicodechal.github.io/)

* 内容主要是算法分析、计算机理论基础、VSCode源码分析等

#### [Catalogue](https://github.com/G33kzD3n/Catalogue)

* 一些图书

#### [How to professionally say](https://howtoprofessionallysay.akashrajpurohit.com/)

* 网站:能够将你想表达的意思更加专业的表达出来

#### [使用 pprof 对 Go 程序进行分析优化](https://www.debuginn.cn/7444.html)

* gperftool实用示例

#### [地图资源下载](https://weibo.com/5198011111/LoZJYgHtX)

* [天地图](https://www.tianditu.gov.cn/)
* [标准地图服务](http://bzdt.ch.mnr.gov.cn/)
* [阿里云数据可视化平台](http://datav.aliyun.com/portal/school/atlas/area_selector)
* [国家地球系统科学数据中心共享服务平台](http://www.geodata.cn)
* [气象地球](https://earth.nullschool.net/#current/wind/surface/level/orthographic=-259.66,16.17,378)
* [天文通](https://www.darkmap.cn/)
* [NB三维地图](https://nbcharts.com/map/map.php)
* [windy-气象地图](https://www.windy.com/?22.291,114.150,5)
* [中国历史地图集](http://www.ccamc.co/chinese_historical_map/index.php)
* [中国诗人地图](https://sou-yun.cn/IndexByMap.aspx)

#### [9 个去中心化、端到端、开源的主流社交媒体平台替代品](https://linux.cn/article-14529-1.html?utm_source=rss&utm_medium=rss)

* 最著名的还是mastodon和signal了

#### [Awesome Github REPO](https://github.com/Wechat-ggGitHub/Awesome-GitHub-Repo)

* github repo推荐

#### [actual](https://github.com/actualbudget/actual)

* 个人财务管理系统,目前只支持web后续会支持多端;
* [介绍网站](https://actualbudget.com/)
* [server端代码](https://github.com/actualbudget/actual-server)

#### [Git权威指南](https://gotgit.readthedocs.io/en/latest/)

#### [GDB dashboard](https://github.com/cyrus-and/gdb-dashboard)

* python GDB工具

#### [ipip.net](http://myip.ipip.net/)

* IP位置工具;微博归属地功能

#### [手写模拟](https://github.com/why20021008/hand-write)

* 模拟手写的效果

#### [Memray](https://github.com/bloomberg/memray)

* python内存profiler

#### [fccf: Fast C/C++ Code Finder](https://github.com/p-ranav/fccf)

* 代码搜索工具

#### [Debian 参考手册](https://www.debian.org/doc/manuals/debian-reference/index.zh-cn.html)

* 官方中文版参考手册

#### [go-zero](https://github.com/zeromicro/go-zero)

* rpc框架;[中文文档](https://go-zero.dev/cn/), [英文文档](https://go-zero.dev/en/)

#### [The Linux Perf Master](https://riboseyim.gitbook.io/perf/)

* Linux性能分析工具上手

#### [scarsu](https://www.scarsu.com/)

* 前端女程序猿;有个月刊tag挺不错的

#### [国家智慧教育平台](https://www.smartedu.cn/)

* 国家级网课平台,覆盖义务教育和职业教育

#### [可乐的周报](http://coke.do/)

* 定期分享整理消息

#### [NIVOS](github.com/TheSadError/NIVOS)

* 一个开源的 Python 工具包，可用于深入扫描、破解 WIFI，适用于所有 Linux 系统，部分功能仍在持续升级中

#### [Fan Control](https://github.com/Rem0o/FanControl.Releases)

* 风扇转速控制工具

#### [感受Vim的强大：进阶技巧](https://harttle.land/2015/07/17/vim-advanced.html)

#### [vim-dirtytalk: spellcheck dictionary for programmers](https://github.com/psliwka/vim-dirtytalk)

#### [AI paper collector](https://github.com/MLNLP-World/AI-Paper-collector)

* AI论文搜索工具

#### [vim cheetsheet for programers](http://michael.peopleofhonoronly.com/vim/?continueFlag=5736f6f7a67304664b0f56b2e45e0238)

* 图片版

#### [Bash Shell 脚本编程实践](http://www.uinio.com/Linux/Shell/)

* bash教程

#### [LeetCode难题代码和算法要点分析](https://github.com/wisdompeak/LeetCode)

* 力扣难题解析

#### [Warp](https://github.com/warpdotdev/Warp)

* ssh工具,网站在[这里](https://warp.dev/)

#### [track awesome list](https://www.trackawesomelist.com/)

* 用于追踪github awesome list工具的网站, 也支持[RSS](https://www.trackawesomelist.com/rss.xml)

#### [selenium](https://selenium-python.readthedocs.io/)

* 基于python的web自动化工具

#### [快乐的 Linux 命令行](http://billie66.github.io/TLCL/book/)

* Linux教程

### 工作生活

#### [计算机日常易读错单词](https://cpwp.netlify.app/)

#### [逻辑学简短入门(牛津通识读本)](https://wxflogic.gitbook.io/logic)

#### [天涯神贴「2010年的房地产调控，我们收获了什么？写在房价暴涨前」脱水版](https://github.com/shengcaishizhan/kkndme_tianya)

#### [如何提高情绪阈值？](http://wufazhuce.com/question/3367)

#### [自卑的本质是什么?](http://wufazhuce.com/question/3362)

#### [深度“解码”Y/Z世代 洞察消费新趋势——2021新消费人群报告](http://mi.talkingdata.com/report-detail.html?id=1105)

#### [关于做学术讲演的几条经验](https://zengfk.com.cn/2021/05/25/%E5%85%B3%E4%BA%8E%E5%81%9A%E8%AE%B2%E6%BC%94%E7%9A%84%E5%87%A0%E6%9D%A1%E7%BB%8F%E9%AA%8C/)

* 作者主业数学

#### 疫情下的社区居民自治

* [疫情下的社区居民自治（上）—— 模式总结](https://mp.weixin.qq.com/s/vAAwOSsB-CAde92lhH0dEg)
* [疫情下的社区居民自治（下）—— 工具包](https://mp.weixin.qq.com/s/DqzXwOwgUi0qaNNxwJvLZQ)

#### [凯文·凯利70岁生日写的103条人生忠告（中文翻译）](https://justinyan.me/post/4911)

#### [Jacob Press on Github](https://jacobzuo.github.io/)

* 科普网站

#### [给女儿的16条建议](https://weibo.com/2365961811/Lr1zPnqke)

#### [物理学咬文嚼字专栏](http://iop.cas.cn/kxcb/kpwz/ywjzzl/)

* 中科院物理所,物理学名词解析

#### [FLY_US](https://github.com/F4bwDP6a6W/FLY_US)

* 美国大学备考资料,GRE和面试等

#### [约会最让人“下头”的13件事，你最讨厌第几件？](https://zhuanlan.zhihu.com/p/507864082)

* 假装你们有着相似的兴趣爱好
* 炫耀你的资产数目和权力，吹嘘你有多成功
* 吹嘘你是多么地受欢迎，故意让对方嫉妒
* 过分炫耀身材
* 一边飙车一边开着高分贝音响
* 过于刻意地取悦对方
* 谈论自己睡过多少人
* 谈论前任
* 刻薄
* 说谎
* 过早地表现出脆弱
* 在犯错的时候不道歉
* 对了解ta的事不感兴趣

#### [How I put my whole life into a single database](https://krausefx.com//blog/how-i-put-my-whole-life-into-a-single-database)

* 作者将自己的所有时间整理成数据库,分析了一些有趣的结果.

#### [looptap](https://looptap.vasanthv.com/)

* 休闲网页小游戏

#### [视频:欧洲少林寺八段锦](https://f.video.weibocdn.com/o0/FeERMFJAlx07VCR34g9a010412045xw20E020.mp4?label=mp4_hd&template=852x480.25.0&ori=0&ps=1BThihd3VLAY5R&Expires=1651574911&ssig=sGjUTaPkhP&KID=unistore,video)

* 刚柔并济

#### [怎样让别人觉得自己很靠谱？](http://wufazhuce.com/question/3366)

* 明确自己的能力边界
* 帮助对方明确任务的规划和想法
* 不要完美主义，先把事情做出去
* 学会邀功

#### [中国芯片替代方案公司名单公布（70个类别）](https://www.dx2025.com/archives/167059.html)

* 东西智库

#### [自我塑造：成功五要素](https://www.cmgemooc.com/course/HIT04011000110_CMGE/10318295?channel=i.area.home_course_ad)

* 哈工大课程

#### [An Amateur Programmer's Blogs](dirtysalt.github.io/html/blogs.html)

* 技术方面以C、算法、高性能计算为主

#### [物资储备指南](https://dig.chouti.com/pic/show?nid=4ae78296f7c9c7cc2e29bb43b56b0290&lid=34821334)

* 指南链接:[指南](https://dig.chouti.com/pic/show?nid=4ae78296f7c9c7cc2e29bb43b56b0290&lid=34821334)

#### [程序员副业交流](https://mobile.twitter.com/waylybaye/status/1517111176999862273)

* 录音也上传到了[google driver](https://drive.google.com/file/d/1_5s4Dfk7_3bYRdluqT4sftAM01ADWUQC/view)
* 总结在[这里](https://mobile.twitter.com/madawei2699/status/1517150616333656066/photo/1)

#### [代码大全读书笔记](https://pegasuswang.readthedocs.io/zh/latest/code/%E4%BB%A3%E7%A0%81%E5%A4%A7%E5%85%A8/)

* 作者的代码大全读书笔记
* 作者还读了一些其他图书,可以看[这里](https://pegasuswang.readthedocs.io/zh/latest/)

#### [开发者代码审查指南](https://jimmysong.io/eng-practices/docs/review/?utm_campaign=%E9%87%8E%E7%94%9F%E6%9E%B6%E6%9E%84%E5%B8%88&utm_medium=email&utm_source=Revue%20newsletter)

* 作者翻译的谷歌CR代码指南

#### [成为职场优秀程序员的 5 个建议](http://weekly.codelc.com/issues/5-1146179)

* 编写与众不同的简历:[示例1](https://codelc.com/intro_2013/?utm_campaign=%E9%87%8E%E7%94%9F%E6%9E%B6%E6%9E%84%E5%B8%88&utm_medium=email&utm_source=Revue%20newsletter), [示例2](https://github.com/lcomplete/coderinfo?utm_campaign=%E9%87%8E%E7%94%9F%E6%9E%B6%E6%9E%84%E5%B8%88&utm_medium=email&utm_source=Revue%20newsletter)
* 注重实效，做个敏捷的程序员
* 制定工作检查清单，做事周全到令他人惊讶
* 持续扩大在团队中的影响力，但一定要谦虚
* 持续优化编码方法，在工作中始终保持进步

#### [2022年版60家中国IC设计初创公司（Fabless Startup）调研分析报告](https://www.eet-china.com/news/2022041114233.html)

* 报告介绍了国内主要IC设计公司及其主要涉及领域

#### [来说说这些年相亲遇到的女方伎俩](https://ngabbs.com/read.php?tid=26335583&rand=783)

* bbs论坛大神帖子,共总结了20余条, 心机女如何PUA男生

#### [想找个女朋友，不知道怎么开始](https://www.v2ex.com/t/848795)

* 心态:要自信,找女朋友和月薪没有关系,和身高也没有关系,和年龄也没有关系,不做舔狗
* 打扮:穿有质感的衣服,经常洗头洗澡,刮胡子,护肤
* 沟通:提高沟通技巧,学会撩妹,提供情绪价值
* 接触:心态放平,主动尝试,多去能接触女生的地方(图书馆/学校/羽毛球场),出门走走,扩大朋友圈,多参与集体活动
* 目标:明确自己喜欢的类型,给出明确指标和要求,然后与接触到的女生匹配,以朋友心态相处
* 表现:要表现自己,使自己看起来值得信任
* 心理:与女生交朋友,了解女生的想法和选择,提高沟通效率

#### [这部年度好片，一秒都不想快进](https://post.smzdm.com/p/a8x7r990/)

* 电影推荐:无主之作;另外导演还有另一部窃听风暴值得看

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

* CPU性能介绍, 作者是[plantgg](https://weibo.com/n/plantegg)
* [CPU的制造和概念](https://plantegg.github.io/2021/06/01/CPU的制造和概念)
* [十年后数据库还是不敢拥抱NUMA](https://plantegg.github.io/2021/05/14/十年后数据库还是不敢拥抱NUMA/)

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
