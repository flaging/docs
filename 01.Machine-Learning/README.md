# 机器学习

## 图书教程

* [Deep Learning Interviews book](https://github.com/BoltzmannEntropy/interviews.ai): [PDF](https://arxiv.org/ftp/arxiv/papers/2201/2201.00650.pdf)

## 开源模型

名称|地址|论文|说明
--|:-:|:-:|--
OPT: Open Pre-trained Transformer Language Models|[github](https://github.com/facebookresearch/metaseq)|[arxiv](https://arxiv.org/abs/2205.01068)| facebook

* GLM-130B : [github](https://github.com/THUDM/GLM-130B), [demo](https://huggingface.co/spaces/THUDM/GLM-130B), [blog](http://keg.cs.tsinghua.edu.cn/glm-130b/posts/glm-130b/)
* PanGu-Coder: Program Synthesis with Function-Level Language Modeling: [arxiv](https://arxiv.org/abs/2207.11280), 盘古, 华为开源的copilot工具
* hybird AI: [blog](https://ai.googleblog.com/2022/07/ml-enhanced-code-completion-improves.html?m=1)
## 框架原理

* [TVM 自底向上](https://zhuanlan.zhihu.com/p/532873577)
* 静态图 VS 动态图: [blog](https://test.eson.org/wiki/ML/deep%20learning/toolbox/-%E9%9D%99%E6%80%81%E5%9B%BE-%E5%8A%A8%E6%80%81%E5%9B%BE/%E9%9D%99%E6%80%81%E5%9B%BE%20VS%20%E5%8A%A8%E6%80%81%E5%9B%BE/)

## 具体实现

* torchmetrics: [doc](https://torchmetrics.readthedocs.io/en/stable/pages/quickstart.html), 精度计算工具
* torch script简介: [doc](https://pytorch.panchuang.net/EigthSection/torchScript/), 解析[blog](https://zhpmatrix.github.io/2019/03/09/torch-jit-pytorch/)
* PaddlePaddle文档: [doc](https://www.paddlepaddle.org.cn/documentation/docs/zh/guides/index_cn.html)
* Jittor: a Just-in-time(JIT) deep learning framework: [github](https://github.com/Jittor/jittor), 清华大学, 自动融合算子的框架
* MindSpore编程指南: [doc](https://mindspore.cn/docs/programming_guide/zh-CN/r1.5/index.html), 华为训练框架

## 解决问题

* Issues installing PyTorch 1.4 - "No matching distribution found for torch===1.4.0": [stackoverflow](https://stackoverflow.com/questions/60137572/issues-installing-pytorch-1-4-no-matching-distribution-found-for-torch-1-4)
```
pip install https://download.pytorch.org/whl/cu101/torch-1.4.0-cp38-cp38-win_amd64.whl
pip install torch===1.6.0 torchvision===0.7.0 -f https://download.pytorch.org/whl/torch_stable.html
```

## 论文框架

#### [The Hugging Face Deep Reinforcement Learning Class](https://github.com/huggingface/deep-rl-class)

#### [复旦大学邱锡鹏](https://xpqiu.github.io/)

* NLP论文集
* [如何写好科研论文](https://xpqiu.github.io/slides/%E5%A6%82%E4%BD%95%E5%86%99%E7%A7%91%E7%A0%94%E8%AE%BA%E6%96%87202203.pdf)

#### [知识图谱可视化技术在美团的实践与探索](https://tech.meituan.com/2022/04/14/the-practice-and-exploration-of-knowledge-graph-visualization-technology-in-meituan.html)

#### [The Kaggle Book](https://github.com/PacktPublishing/The-Kaggle-Book)

* kaggle竞赛讲解

#### [DALL-E 2 - Pytorch](https://github.com/lucidrains/DALLE2-pytorch)

* text-to-image

#### [imagen-torch](https://github.com/lucidrains/imagen-pytorch): text to image, pytorch, imagen

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

#### [ColossalAI](https://github.com/hpcaitech/ColossalAI)

* 大规模深度学习训练平台, 支持分布式

#### [MLPerf Inference Benchmark Suites](https://github.com/mlcommons/inference)

#### [onnx-util](https://github.com/saurabh-shandilya/onnx-utils)

* onnx剪辑工具

#### [Huggingface transformers](https://github.com/huggingface/transformers)

* transformer的推理库

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


## 开源模型

#### [yolo v7](https://github.com/jinfagang/yolov7)

* 添加对transformer的支持
* 对NV GPU的适配

#### [min-dalle](https://github.com/kuprel/min-dalle)

* DALLE的精简版实现(for 推理)

#### [美团:基于强化学习的信息流广告分配方法CrossDQN](https://mp.weixin.qq.com/s/4Eq2ldcqb6TwOiDtVp7nAQ)

* 广告推荐算法
* [论文预印版](https://arxiv.org/abs/2109.04353)

#### [图学习？Transformer：我也行！](https://mp.weixin.qq.com/s/EBFs7ptwgyCAmRJS8_dcYQ)

* transformer在图学习领域应用,介绍了四篇主要工作

#### [教程: Transformer United(Stanford)](https://web.stanford.edu/class/cs25/):[Youtube](https://www.youtube.com/playlist?list=PLoROMvodv4rNiJRchCzutFw5ItR_Z27CM)

#### 教程: Attention Mechanisms: [Youtube](https://www.youtube.com/watch?v=s4xohg-t7RI), [slides](https://drive.google.com/file/d/1FYXSr_WmwRzxSaSPSQn_Bm1ZlzsZKDit/view)

#### 清华大学刘知远预训练模型:[b站](https://weibo.cn/sinaurl?u=https%3A%2F%2Fwww.bilibili.com%2Fvideo%2FBV1UG411p7zv%3Fspm_id_from%3D333.999.0.0%26vd_source%3D7602c84c24e4a2630c111cbc2b727f59)

#### OneFlow源码阅读6：自动微分机制: [blog](https://segmentfault.com/a/1190000042199820)

#### 盘点22年各大顶会，对比学习它来了！: [微信](https://mp.weixin.qq.com/s/bly6xM4NxbdYfXjam-XMKA)

#### AI-GPU显存优化领域前沿工作发展史:[知乎](https://zhuanlan.zhihu.com/p/536940298?utm_source=ZHShareTargetIDMore&utm_medium=social&utm_oi=49336847171584)

#### Improving Efficiency and Robustness of Transformer-based Information Retrieval Systems: [github](https://github.com/ebegoli/SIGIR2022-Efficient-Transfomers), [ppt](https://github.com/ebegoli/SIGIR2022-Efficient-Transfomers/blob/main/SIGIR%202022%20-%20Efficient%20Transformers%20for%20IR.pdf), Transformer信息检索效率和鲁棒性

* A visual introduction to information theory: [arxiv](https://arxiv.org/pdf/2206.07867.pdf)
* A Survey on Vision Transformer: [arxiv](https://arxiv.org/pdf/2012.12556.pdf), 中科院vit综述论文
* 评估和选择最佳学习模型的一些指标总结: [微信](https://mp.weixin.qq.com/s/aD1ZJ9qOjM2o3vfcNzyByA)
* theseus: [github](https://github.com/facebookresearch/theseus), [homepage](https://sites.google.com/view/theseus-ai), [paper](https://paperswithcode.com/paper/theseus-a-library-for-differentiable), FB开源的非线性函数优化库,可与nn模型联合使用
* Dive into Big Model Training: [blog](https://github.com/qhliu26/bm-training), 大模型训练经典论文集