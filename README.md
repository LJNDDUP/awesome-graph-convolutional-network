# awesome Graph Convolutional Network
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-YES-green.svg)](https://github.com/iCGY96/awesome_OpenSetRecognition_list/graphs/commit-activity)


## 2021
### ICCV
+ [GraphFPN: Graph Feature Pyramid Network for Object Detection](https://arxiv.org/pdf/2108.00580.pdf). Gangming Zhao. 复旦大学. 
    - Task-related
    - SOTA多尺度特征学习方法使用固定拓扑结构的神经网络进行跨空间、跨尺度的特征交互
    - 提出图特征金字塔网络，能够自适应地调整拓扑结构以适应不同的内在图像结构，支持在所有尺度上同时地进行特征交互


## 2020
### ICML
+ [Simple and Deep Graph Convolutional Networks](https://arxiv.org/pdf/2007.02133.pdf). Ming Chen. 中国人民大学信息学院. [code](https://github.com/chennnM/GCNII). 
![](https://img.shields.io/github/stars/chennnM/GCNII.svg) 
    - Operations on graph
    - 由于过平滑问题，大多数GCN模型都很浅，本文研究深层GCN的设计
    - 提出GCNII，其中使用了两种简单而有效的技术：初始残差和恒等映射


## 2019
### CVPR
+ [Multi-Label Image Recognition with Graph Convolutional Networks](https://arxiv.org/pdf/1904.03582.pdf). Zhao-Min Chen. 南京大学新型软件技术国家重点实验室. [code](https://github.com/Megvii-Nanjing/ML-GCN).
![](https://img.shields.io/github/stars/Megvii-Nanjing/ML-GCN.svg)
    - Task-related
    - 提出一个基于图的多标签分类模型，其中每个节点（标签）由标签的Embedding表示
    - GCN通过学习将标签图映射为一组相互依赖的目标分类器，再将这些分类器应用到由另一个子网络提取的图像描述子上，组成端到端的网络
    - 提出一种新的重加权方案来创建一个有效的标签关联矩阵，指导信息在节点之间传播

### ICCV
+ [DeepGCNs: Can GCNs Go As Deep As CNNs?](https://openaccess.thecvf.com/content_ICCV_2019/papers/Li_DeepGCNs_Can_GCNs_Go_As_Deep_As_CNNs_ICCV_2019_paper.pdf). Guohao Li. 沙特阿拉伯，图瓦尔，KAUST可视化计算中心. [code](https://github.com/lightaime/deep_gcns_torch). 
![](https://img.shields.io/github/stars/lightaime/deep_gcns_torch.svg) 
    - Operations on graph
    - 之前的GCN局限于非常浅的网络，网络一深就会导致梯度消失，层数加深后损失下降显著变慢
    - 把CNN中残差/密集连接和扩张卷积等概念应用到GCN中，使得GCN也能训练非常深的网络
    - 构建了56层的GCN，在点云语义分割任务上比SOTA提高了3.7%mIoU


## 2018
### ICLR
+ [Graph Attention Networks](https://arxiv.org/pdf/1710.10903.pdf). Petar Velickovic. 剑桥大学计算机科学与技术系. [code](https://github.com/PetarV-/GAT).
![](https://img.shields.io/github/stars/PetarV-/GAT.svg)
    - Operations on graph
    - 通过使用masked自注意力机制层，以共享的方式应用在所有边上，因此不需要预先访问图结构，更有利于给相同邻域的不同节点分配不同的重要性，且更具解释性


## 2017
### ICLR
+ [Semi-Supervised Classification with Graph Convolutional Networks](https://arxiv.org/pdf/1609.02907.pdf). Thomas N. Kipf. 阿姆斯特丹大学. [code](https://github.com/tkipf/gcn).
![](https://img.shields.io/github/stars/tkipf/gcn.svg)
    - Operations on graph
    - 通过谱图卷积的局部一阶近似，来构建卷积网络结构
    - 通过图结构中部分有标签的节点数据对卷积神经网络结构模型训练，使得模型对无标签的节点数据进行分类


## 基础知识
+ [谱图理论](https://zhuanlan.zhihu.com/p/362416124).
+ [从CNN到GCN的联系与区别](https://www.zhihu.com/question/54504471/answer/332657604).
