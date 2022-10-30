# 2022-11-05

## 本周见闻

* [kernl](https://github.com/ELS-RD/kernl)
  * OpenAI提出的Transformer类模型新加速库, 最高有12倍加速比(相对于huggging face)
  * 对Torch的transformer模型算子进行wrapper替换
  * 使用[triton语言](https://triton-lang.org/master/getting-started/installation.html)(not triton form NV)进行算子高效实现
  * 使用[CUDA Graph](https://pytorch.org/blog/accelerating-pytorch-with-cuda-graphs/)进行图调度,节省时间
  * 实用[torch Dynamo](https://github.com/pytorch/torchdynamo/)进行动态图构建