# 编程语言

## 博客教程

### python

* Organize Python code like a PRO: [blog](https://guicommits.com/organize-python-code-like-a-pro/)
* conda: [doc](https://docs.conda.io/projects/conda/en/latest/user-guide/concepts/index.html), python环境管理工具

### Java

* 调试 JNI: [blog](http://longed.top/index.php/2019/11/30/%E8%B0%83%E8%AF%95-jni/), 使用jdb和gdb调试JNI的C++代码
* Java中的native是如何实现的（JNI）: [blog](https://segmentfault.com/a/1190000022812099), JNI的使用方法

### C++

* Bazel Tutorial: Build a C++ Project: [doc](https://docs.bazel.build/versions/main/tutorial/cpp.html), bazel使用手册, 工程编译工具, [github release](https://github.com/bazelbuild/bazel/releases), 
* 记录一些bazel适配用编译选项: [blog](https://owent.net/2022/2202.html)
* Bazel自定义规则实现将多个静态库合并为一个动态库或静态库: [zhihu](https://zhuanlan.zhihu.com/p/202663666)
* glog error- ‘google’ has not been declared: [github issue](https://github.com/facebook/rocksdb/issues/139), 添加```#include <gflags/gflags.h>```

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

#### [Policy](http://www.modernescpp.com/index.php/policy-and-traits)

* C++新特性; 本网站值得关注

#### [#python Think in Python 2e](https://tairraos.github.io/ThinkPython/index.html)

* 一本python教程

#### [#C++ C++程序设计](https://www.bilibili.com/video/BV1Vf4y1P7pq?spm_id_from=333.999.0.0)

* b站课程; 南方科大于仕琪(openCV中国团队负责人), 另外主页还有[HID2021](https://space.bilibili.com/519963684/channel/seriesdetail?sid=323687&ctype=0)和[HID2020](https://space.bilibili.com/519963684/channel/seriesdetail?sid=323689&ctype=0)的论文解读

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

#### 详解函数式编程、再聊设计模式: [微信](https://mp.weixin.qq.com/mp/appmsgalbum?__biz=MzI3MzEzMDI1OQ==&action=getalbum&album_id=2423505869138100225&scene=173&from_msgid=2651835694&from_itemidx=1&count=3&nolastread=1), 布鲁斯 • 埃克尔（Bruce Eckel），C++ 标准委员会的创始成员之一，知名技术顾问，专注于编程语言和软件系统设计方面的研究.

* Python Design Patterns: [github](https://github.com/brandon-rhodes/python-patterns), [book](https://python-patterns.guide/)

## 推荐资料

### 图书

* C++ primer
* effective C++

### 视频

暂无.