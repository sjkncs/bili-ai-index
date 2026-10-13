# AI 课程与教程

> Source: **ShusenWang, 霹雳吧啦Wz, 刘二大人, 王木头学科学, Bubbliiiing, 啥都会一点的研究生, RethinkFun, 我是傅傅猪, 唐国梁Tommy, 九天Hector** - Snapshot: **2026-10-13** - **1431** episodes.
> Data: [`items.json`](items.json)

## Data source / method / limits

**Data source**: `seasons_archives_list` for the episode list; `x/web-interface/view`
per video for its **`desc`** field.

**Method**: this source's titles are already short and complete (no 80-char truncation
observed), so **the title is the record** and no paper/venue/speaker parsing is attempted.
The description is scanned only for links, and links are de-duplicated per episode.

**Limits**: descriptions are shallow and highly repetitive -- the most frequent link
appears on 42 of 106 episodes (an authoritative paper-list repo), another on 29 (a course
homepage) -- so links points at entry points rather than at each individual paper.
**No venue, arXiv id or speaker is available for most entries, and none is invented.**
16 of 106 descriptions are empty entirely.

## All 1431 episodes

| # | speaker | affiliation | topic | length | B station |
|---:|---|---|---|---:|---|
| 1 | - | - | RNN模型与NLP应用(1/9)：数据处理基础 | 10:53 | [link](https://www.bilibili.com/video/BV1w54y1L7xK) |
| 2 | - | - | RNN模型与NLP应用(2/9)：文本处理与词嵌入 | 16:10 | [link](https://www.bilibili.com/video/BV1fp4y147Lc) |
| 3 | - | - | RNN模型与NLP应用(3/9)：Simple RNN模型 | 20:46 | [link](https://www.bilibili.com/video/BV1dq4y1f7ep) |
| 4 | - | - | RNN模型与NLP应用(4/9)：LSTM模型 | 12:59 | [link](https://www.bilibili.com/video/BV1UK4y1d7xa) |
| 5 | - | - | RNN模型与NLP应用(5/9)：多层RNN、双向RNN、预训练 | 12:11 | [link](https://www.bilibili.com/video/BV1Ab4y1f73K) |
| 6 | - | - | RNN模型与NLP应用(6/9)：Text Generation (自动文本生成) | 23:21 | [link](https://www.bilibili.com/video/BV1Xh411e7ZR) |
| 7 | - | - | RNN模型与NLP应用(7/9)：机器翻译与Seq2Seq模型 | 19:37 | [link](https://www.bilibili.com/video/BV1964y127Vz) |
| 8 | - | - | RNN模型与NLP应用(8/9)：Attention (注意力机制) | 16:48 | [link](https://www.bilibili.com/video/BV1YA411G7Ep) |
| 9 | - | - | RNN模型与NLP应用(9/9)：Self-Attention (自注意力机制) | 7:13 | [link](https://www.bilibili.com/video/BV17B4y1F7oy) |
| 10 | - | - | Transformer模型(1/2): 剥离RNN，保留Attention | 24:02 | [link](https://www.bilibili.com/video/BV1SK4y1d7Qh) |
| 11 | - | - | Transformer模型(2/2): 从Attention层到Transformer网络 | 14:33 | [link](https://www.bilibili.com/video/BV1N54y1L7N5) |
| 12 | - | - | BERT (预训练Transformer模型) | 11:25 | [link](https://www.bilibili.com/video/BV1y64y127bF) |
| 13 | - | - | Vision Transformer (ViT) 用于图片分类 | 13:09 | [link](https://www.bilibili.com/video/BV18Q4y1o7NY) |
| 14 | - | - | 10-1: 图的基本概念和数据结构 Graph Basics and Data Structures | 10:39 | [link](https://www.bilibili.com/video/BV1k44y1z7g6) |
| 15 | - | - | 11-1: 图中的路径和最短路 Shortest Path | 10:16 | [link](https://www.bilibili.com/video/BV1WB4y1g7tW) |
| 16 | - | - | 11-2: 无权图的最短路算法 Finding Shortest Path in Unweighted Graphs | 16:25 | [link](https://www.bilibili.com/video/BV1CK4y1X7BT) |
| 17 | - | - | 11-3: Dijkstra 算法 寻找有权图中最短路 Finding Shortest Path in Weighted Graphs | 20:31 | [link](https://www.bilibili.com/video/BV19K4y1g75e) |
| 18 | - | - | 12-3: Kruskal算法 寻找最小生成树 Kruskal's Algorithm for Minimum Spanning Trees | 11:10 | [link](https://www.bilibili.com/video/BV1Sv411V781) |
| 19 | - | - | 12-2: Prim算法 寻找最小生成树 Prim's Algorithm for Minimum Spanning Trees | 6:19 | [link](https://www.bilibili.com/video/BV1A5411M7zc) |
| 20 | - | - | 12-1: 最小生成树 Minimum Spanning Trees | 8:46 | [link](https://www.bilibili.com/video/BV145411M7xL) |
| 21 | - | - | 13-1: 网络流问题基础 Network Flow Problems | 15:54 | [link](https://www.bilibili.com/video/BV1K64y1C7Do) |
| 22 | - | - | 13-2: Ford-Fulkerson Algorithm 寻找网络最大流 | 13:34 | [link](https://www.bilibili.com/video/BV1Pv41157xh) |
| 23 | - | - | 13-3: Edmonds-Karp Algorithm 寻找网络最大流 | 4:28 | [link](https://www.bilibili.com/video/BV1uQ4y197Le) |
| 24 | - | - | 13-4: Dinic's Algorithm 寻找网络最大流 | 14:13 | [link](https://www.bilibili.com/video/BV1j64y1R7yK) |
| 25 | - | - | 13-5: 最小割 Min-Cut | 8:11 | [link](https://www.bilibili.com/video/BV1T64y1R7ZK) |
| 26 | - | - | 14-1: 二部图及其判定算法 Bipartite Graphs | 13:56 | [link](https://www.bilibili.com/video/BV14q4y1j776) |
| 27 | - | - | 14-2: 无权二部图中的最大匹配 Maximum-Cardinality Bipartite Matching (MCBM) | 7:26 | [link](https://www.bilibili.com/video/BV1G54y157HA) |
| 28 | - | - | 14-3: 有权二部图中的最大匹配 Maximum-Weight Bipartite Matching | 6:02 | [link](https://www.bilibili.com/video/BV1MB4y1g7Fx) |
| 29 | - | - | 14-4: 匈牙利算法 Hungarian Algorithm | 15:59 | [link](https://www.bilibili.com/video/BV16K4y1X7Ph) |
| 30 | - | - | 14-5: 稳定婚配问题 Stable Marriage Problem | 6:31 | [link](https://www.bilibili.com/video/BV1V44y167n3) |
| 31 | - | - | 14-6: Gale-Shapley 算法 寻找稳定婚配 | 10:32 | [link](https://www.bilibili.com/video/BV1uq4y177Hc) |
| 32 | - | - | 概要01：推荐系统的基本概念 | 9:18 | [link](https://www.bilibili.com/video/BV1PS4y1A7za) |
| 33 | - | - | 概要02：推荐系统的链路 | 7:35 | [link](https://www.bilibili.com/video/BV1hF411M7b5) |
| 34 | - | - | 概要03：推荐系统的AB测试 | 16:26 | [link](https://www.bilibili.com/video/BV1J44y1o7gf) |
| 35 | - | - | 召回01：基于物品的协同过滤（ItemCF） | 15:36 | [link](https://www.bilibili.com/video/BV1mA4y1Q7RN) |
| 36 | - | - | 召回02：Swing 模型 | 7:46 | [link](https://www.bilibili.com/video/BV1DA4y1Q7rB) |
| 37 | - | - | 召回03：基于用户的协同过滤（UserCF） | 15:06 | [link](https://www.bilibili.com/video/BV1HY4y1Y7P1) |
| 38 | - | - | 召回04：离散特征处理 | 8:11 | [link](https://www.bilibili.com/video/BV1pS4y1a7QT) |
| 39 | - | - | 召回05：矩阵补充、最近邻查找 | 16:29 | [link](https://www.bilibili.com/video/BV1b34y1e7En) |
| 40 | - | - | 召回06：双塔模型——模型结构、训练方法 | 14:13 | [link](https://www.bilibili.com/video/BV1YA4y1D75Q) |
| 41 | - | - | 召回07：双塔模型——正负样本 | 13:09 | [link](https://www.bilibili.com/video/BV133411T7ue) |
| 42 | - | - | 召回08：双塔模型——线上服务、模型更新 | 13:21 | [link](https://www.bilibili.com/video/BV1KY4y1h73Y) |
| 43 | - | - | 召回09：双塔模型+自监督学习 | 20:20 | [link](https://www.bilibili.com/video/BV1v24y1B7JH) |
| 44 | - | - | 召回10：Deep Retrieval 召回 | 28:29 | [link](https://www.bilibili.com/video/BV1Fu4y1b7PL) |
| 45 | - | - | 召回11：地理位置召回、作者召回、缓存召回 | 8:38 | [link](https://www.bilibili.com/video/BV1m5411R7nd) |
| 46 | - | - | 召回12：曝光过滤 & Bloom Filter | 11:58 | [link](https://www.bilibili.com/video/BV1sa4y137LF) |
| 47 | - | - | 排序01：多目标模型 | 9:49 | [link](https://www.bilibili.com/video/BV19t4y1p7UM) |
| 48 | - | - | 排序02：Multi-gate Mixture-of-Experts (MMoE) | 6:27 | [link](https://www.bilibili.com/video/BV14Y411M74v) |
| 49 | - | - | 排序03：预估分数融合 | 3:55 | [link](https://www.bilibili.com/video/BV1YT411578u) |
| 50 | - | - | 排序04：视频播放建模 | 7:35 | [link](https://www.bilibili.com/video/BV1394y1277M) |
| 51 | - | - | 排序05：排序模型的特征 | 12:32 | [link](https://www.bilibili.com/video/BV1gN4y157TM) |
| 52 | - | - | 排序06：粗排模型 | 8:25 | [link](https://www.bilibili.com/video/BV1Dd4y1m7KT) |
| 53 | - | - | 特征交叉01：Factorized Machine (FM) 因式分解机 | 5:59 | [link](https://www.bilibili.com/video/BV15V4y1x7Ht) |
| 54 | - | - | 特征交叉02：DCN 深度交叉网络 | 7:26 | [link](https://www.bilibili.com/video/BV1LP411L7Z2) |
| 55 | - | - | 特征交叉03：LHUC (PPNet) | 4:11 | [link](https://www.bilibili.com/video/BV1jU4y1z7Tc) |
| 56 | - | - | 特征交叉04：SENet 和 Bilinear 交叉 | 8:36 | [link](https://www.bilibili.com/video/BV1SY4y1M7bD) |
| 57 | - | - | 行为序列01：用户历史行为序列建模 | 3:09 | [link](https://www.bilibili.com/video/BV1GG4y1B7Yh) |
| 58 | - | - | 行为序列02：DIN模型（注意力机制） | 4:38 | [link](https://www.bilibili.com/video/BV1bT411T7u4) |
| 59 | - | - | 行为序列03：SIM模型（长序列建模） | 8:42 | [link](https://www.bilibili.com/video/BV1Ze4y1B7JL) |
| 60 | - | - | 重排01：物品相似性的度量、提升多样性的方法 | 8:00 | [link](https://www.bilibili.com/video/BV1ne4y1v7mC) |
| 61 | - | - | 重排02：MMR 多样性算法（Maximal Marginal Relevance） | 8:01 | [link](https://www.bilibili.com/video/BV1dV4y1V7Kg) |
| 62 | - | - | 重排03：业务规则约束下的多样性算法 | 4:43 | [link](https://www.bilibili.com/video/BV1om4y1F7y5) |
| 63 | - | - | 重排04：DPP 多样性算法（上） | 9:39 | [link](https://www.bilibili.com/video/BV1re411F7cp) |
| 64 | - | - | 重排05：DPP 多样性算法（下） | 13:55 | [link](https://www.bilibili.com/video/BV1Md4y1c7uB) |
| 65 | - | - | 物品冷启01：优化目标 & 评价指标 | 12:06 | [link](https://www.bilibili.com/video/BV1eZ4y1a7tG) |
| 66 | - | - | 物品冷启02：简单的召回通道 | 10:47 | [link](https://www.bilibili.com/video/BV1HY4y157Ri) |
| 67 | - | - | 物品冷启03：聚类召回 | 8:29 | [link](https://www.bilibili.com/video/BV1YT4y1q7zC) |
| 68 | - | - | 物品冷启04：Look-Alike 召回 | 5:49 | [link](https://www.bilibili.com/video/BV1U5411X7ud) |
| 69 | - | - | 物品冷启05：流量调控 | 14:57 | [link](https://www.bilibili.com/video/BV1vS4y1z7sC) |
| 70 | - | - | 物品冷启06：冷启的AB测试 | 15:40 | [link](https://www.bilibili.com/video/BV12341137Cq) |
| 71 | - | - | 推荐系统涨指标的方法01：概述 | 5:15 | [link](https://www.bilibili.com/video/BV1fc41167jK) |
| 72 | - | - | 推荐系统涨指标的方法02：召回 | 13:29 | [link](https://www.bilibili.com/video/BV13H4y127Tt) |
| 73 | - | - | 推荐系统涨指标的方法03：排序模型 | 24:13 | [link](https://www.bilibili.com/video/BV1fQ4y1G72F) |
| 74 | - | - | 推荐系统涨指标的方法04：多样性 | 11:57 | [link](https://www.bilibili.com/video/BV1eN4y1z7vs) |
| 75 | - | - | 推荐系统涨指标的方法05：特殊用户人群 | 19:01 | [link](https://www.bilibili.com/video/BV15g4y1m7P4) |
| 76 | - | - | 推荐系统涨指标的方法06：交互行为（关注、转发、评论） | 19:07 | [link](https://www.bilibili.com/video/BV1tg4y127rS) |
| 77 | - | - | 神经网络结构搜索 (1/3): 基本概念和随机搜索   Neural Architecture Search: Basics & Random Search | 10:21 | [link](https://www.bilibili.com/video/BV14q4y177gQ) |
| 78 | - | - | 神经网络结构搜索 (2/3): RNN + RL   Neural Architecture Search: RNN + RL | 24:07 | [link](https://www.bilibili.com/video/BV15K4y1A7hq) |
| 79 | - | - | 神经网络结构搜索 (3/3): 可微方法   Differentiable Neural Architecture Search | 23:48 | [link](https://www.bilibili.com/video/BV1C64y127Fv) |
| 80 | - | - | 概要01：搜索引擎的基本概念 | 12:16 | [link](https://www.bilibili.com/video/BV1Wr421b7uP) |
| 81 | - | - | 概要02：相关性、内容质量、时效性、个性化（决定搜索满意度的因素） | 26:18 | [link](https://www.bilibili.com/video/BV1Lm421J7Xz) |
| 82 | - | - | 概要03：搜索引擎的评价指标 | 24:57 | [link](https://www.bilibili.com/video/BV1BT421m7UQ) |
| 83 | - | - | 概要04：搜索引擎的链路（查询词处理、召回、排序） | 20:34 | [link](https://www.bilibili.com/video/BV1UM4m1D7L3) |
| 84 | - | - | 相关性01：搜索相关性的定义与分档 | 21:06 | [link](https://www.bilibili.com/video/BV1Xp421S7Kb) |
| 85 | - | - | 相关性02：评价指标（AUC、正逆序比、DCG） | 21:10 | [link](https://www.bilibili.com/video/BV1VD421N7K7) |
| 86 | - | - | 相关性03：文本匹配（TF-IDF、BM25、词距） | 19:17 | [link](https://www.bilibili.com/video/BV1XT421Q7fw) |
| 87 | - | - | 相关性04：BERT模型 (Part 1) - 模型结构、线上推理 | 13:58 | [link](https://www.bilibili.com/video/BV17T421D72u) |
| 88 | - | - | 相关性05：BERT模型 (Part 2) - 模型训练 | 25:24 | [link](https://www.bilibili.com/video/BV1pz421e7GS) |
| 89 | - | - | Few-Shot Learning (1/3): 基本概念 | 17:11 | [link](https://www.bilibili.com/video/BV1V44y1r7cx) |
| 90 | - | - | Few-Shot Learning (2/3): Siamese Network (孪生网络) | 15:14 | [link](https://www.bilibili.com/video/BV1vQ4y1R7dr) |
| 91 | - | - | Few-Shot Learning (3/3)：Pretraining + Fine Tuning | 18:50 | [link](https://www.bilibili.com/video/BV1B44y1r75K) |
| 92 | - | - | 语义分割前言 | 23:51 | [link](https://www.bilibili.com/video/BV1ev411P7dR) |
| 93 | - | - | 转置卷积（transposed convolution） | 19:11 | [link](https://www.bilibili.com/video/BV1mh411J7U4) |
| 94 | - | - | FCN网络结构详解(语义分割) | 31:53 | [link](https://www.bilibili.com/video/BV1J3411C7zd) |
| 95 | - | - | 膨胀卷积(Dilated convolution)详解 | 19:04 | [link](https://www.bilibili.com/video/BV1Bf4y1g7j8) |
| 96 | - | - | Pytorch官方实现的FCN网络结构 | 6:18 | [link](https://www.bilibili.com/video/BV1ev411u7TX) |
| 97 | - | - | DeepLabV1网络简介(语义分割) | 15:51 | [link](https://www.bilibili.com/video/BV1SU4y1N7Ao) |
| 98 | - | - | DeepLabV2网络简介(语义分割) | 14:51 | [link](https://www.bilibili.com/video/BV1gP4y1G7TC) |
| 99 | - | - | DeepLabV3网络简介(语义分割) | 20:04 | [link](https://www.bilibili.com/video/BV1Jb4y1q7j7) |
| 100 | - | - | LR-ASPP模型简介(语义分割) | 5:56 | [link](https://www.bilibili.com/video/BV1LS4y1M76E) |
| 101 | - | - | LR-ASPP源码讲解(Pytorch) | 12:52 | [link](https://www.bilibili.com/video/BV13D4y1F7ML) |
| 102 | - | - | U-Net网络结构讲解(语义分割) | 12:15 | [link](https://www.bilibili.com/video/BV1Vq4y127fB) |
| 103 | - | - | U2Net网络结构讲解 | 19:09 | [link](https://www.bilibili.com/video/BV1yB4y1z7mj) |
| 104 | - | - | 验证时Batch Size要设置成1？ | 3:39 | [link](https://www.bilibili.com/video/BV1AP4y1m7qt) |
| 105 | - | - | 网络训练前需要热身？ | 4:02 | [link](https://www.bilibili.com/video/BV1sd4y1b72w) |
| 106 | - | - | 为啥我保存的权重文件那么大？ | 3:44 | [link](https://www.bilibili.com/video/BV13P41137uM) |
| 107 | - | - | 如何精确统计模型推理时间 | 12:58 | [link](https://www.bilibili.com/video/BV1km4SeuEim) |
| 108 | - | - | 1.1 卷积神经网络基础 | 26:11 | [link](https://www.bilibili.com/video/BV1b7411T7DA) |
| 109 | - | - | 1.2 卷积神经网络基础补充 | 27:50 | [link](https://www.bilibili.com/video/BV1M7411M7D2) |
| 110 | - | - | 2.1 pytorch官方demo(Lenet) | 49:48 | [link](https://www.bilibili.com/video/BV187411T7Ye) |
| 111 | - | - | 2.2 tensorflow2官方demo | 37:37 | [link](https://www.bilibili.com/video/BV1n7411T7o6) |
| 112 | - | - | 3.1 AlexNet网络结构详解与花分类数据集下载 | 14:10 | [link](https://www.bilibili.com/video/BV1p7411T7Pc) |
| 113 | - | - | 3.2 使用pytorch搭建AlexNet并训练花分类数据集 | 32:32 | [link](https://www.bilibili.com/video/BV1W7411T7qc) |
| 114 | - | - | 3.3 使用tensorflow2搭建Alexnet | 39:13 | [link](https://www.bilibili.com/video/BV1s7411T7vs) |
| 115 | - | - | 4.1 VGG网络详解及感受野的计算 | 12:39 | [link](https://www.bilibili.com/video/BV1q7411T7Y6) |
| 116 | - | - | 4.2 使用pytorch搭建VGG网络 | 19:54 | [link](https://www.bilibili.com/video/BV1i7411T7ZN) |
| 117 | - | - | 4.3 使用tensorflow搭建VGG网络 | 17:19 | [link](https://www.bilibili.com/video/BV1q7411T76b) |
| 118 | - | - | 5.1 GoogLeNet网络详解 | 16:40 | [link](https://www.bilibili.com/video/BV1z7411T7ie) |
| 119 | - | - | 5.2 使用pytorch搭建GoogLeNet网络 | 29:03 | [link](https://www.bilibili.com/video/BV1r7411T7M5) |
| 120 | - | - | 5.3 使用tensorflow搭建GoogLeNet网络 | 24:10 | [link](https://www.bilibili.com/video/BV1a7411T7Ht) |
| 121 | - | - | 6.1 ResNet网络结构，BN以及迁移学习详解 | 34:08 | [link](https://www.bilibili.com/video/BV1T7411T7wa) |
| 122 | - | - | 6.1.2 ResNeXt网络结构 | 17:24 | [link](https://www.bilibili.com/video/BV1Ap4y1p71v) |
| 123 | - | - | 6.2 使用pytorch搭建ResNet并基于迁移学习训练 | 39:22 | [link](https://www.bilibili.com/video/BV14E411H7Uw) |
| 124 | - | - | 6.2.2 使用pytorch搭建ResNeXt并基于迁移学习训练 | 13:03 | [link](https://www.bilibili.com/video/BV1rX4y1N7tE) |
| 125 | - | - | 6.3 使用tensorflow搭建ResNet网络并基于迁移学习的方法进行训练 | 36:45 | [link](https://www.bilibili.com/video/BV1WE41177Ya) |
| 126 | - | - | 7.1 MobileNet网络详解 | 27:29 | [link](https://www.bilibili.com/video/BV1yE411p7L7) |
| 127 | - | - | 7.1.2 MobileNetv3网络详解 | 20:28 | [link](https://www.bilibili.com/video/BV1GK4y1p7uE) |
| 128 | - | - | 7.2 使用pytorch搭建MobileNetV2并基于迁移学习训练 | 29:08 | [link](https://www.bilibili.com/video/BV1qE411T7qZ) |
| 129 | - | - | 7.2.2 使用Pytorch搭建MobileNetV3并基于迁移学习训练 | 33:54 | [link](https://www.bilibili.com/video/BV1zT4y1P7pd) |
| 130 | - | - | 7.3 使用tensorflow搭建MobileNetV2模型并基于迁移学习训练 | 30:08 | [link](https://www.bilibili.com/video/BV1NE411K7tX) |
| 131 | - | - | 7.3.2 使用Tensorflow2搭建MobileNetV3并基于迁移学习训练 | 31:11 | [link](https://www.bilibili.com/video/BV1KA411g7wX) |
| 132 | - | - | 8.1 ShuffleNet v1 v2理论讲解 | 39:58 | [link](https://www.bilibili.com/video/BV15y4y1Y7SY) |
| 133 | - | - | 8.2 使用Pytorch搭建ShuffleNetv2 | 30:50 | [link](https://www.bilibili.com/video/BV1dh411r76X) |
| 134 | - | - | 8.3 使用Tensorflow2搭建ShuffleNetv2 | 22:48 | [link](https://www.bilibili.com/video/BV1kr4y1N7bh) |
| 135 | - | - | 9.1 EfficientNet网络详解 | 19:32 | [link](https://www.bilibili.com/video/BV1XK4y1U7PX) |
| 136 | - | - | 9.2使用Pytorch搭建EfficientNet网络 | 41:28 | [link](https://www.bilibili.com/video/BV19z4y1179h) |
| 137 | - | - | 9.3 使用Tensorflow2搭建EfficientNet网络 | 31:29 | [link](https://www.bilibili.com/video/BV1PK4y1S7Jf) |
| 138 | - | - | 10.1 EfficientNetV2网络详解 | 30:59 | [link](https://www.bilibili.com/video/BV19v41157AU) |
| 139 | - | - | 10.2 使用Pytorch搭建EfficientNetV2网络 | 26:22 | [link](https://www.bilibili.com/video/BV1Xy4y1g74u) |
| 140 | - | - | 10.3 使用tensorflow搭建EfficientNetV2并基于迁移学习训练 | 40:35 | [link](https://www.bilibili.com/video/BV19K4y1g7m4) |
| 141 | - | - | Transformer中Self-Attention以及Multi-Head Attention详解 | 18:23 | [link](https://www.bilibili.com/video/BV15v411W78M) |
| 142 | - | - | 11.1 Vision Transformer(vit)网络详解 | 25:26 | [link](https://www.bilibili.com/video/BV1Jh411Y7WQ) |
| 143 | - | - | 11.2 使用pytorch搭建Vision Transformer(vit)模型 | 40:27 | [link](https://www.bilibili.com/video/BV1AL411W7dT) |
| 144 | - | - | 11.3 使用tensorflow2搭建vision transformer(ViT)模型，并基于迁移学习训练 | 39:25 | [link](https://www.bilibili.com/video/BV1q64y1X7GY) |
| 145 | - | - | 12.1 Swin-Transformer网络结构详解 | 51:08 | [link](https://www.bilibili.com/video/BV1pL4y1v7jC) |
| 146 | - | - | 12.2 使用Pytorch搭建Swin-Transformer网络 | 79:44 | [link](https://www.bilibili.com/video/BV1yg411K7Yc) |
| 147 | - | - | 12.3 使用tensorflow2搭建Swin-Transformer网络 | 23:29 | [link](https://www.bilibili.com/video/BV1bR4y1t7qT) |
| 148 | - | - | 13.1 ConvNeXt网络讲解 | 19:33 | [link](https://www.bilibili.com/video/BV1SS4y157fu) |
| 149 | - | - | 13.2 使用Pytorch搭建ConvNeXt网络 | 18:45 | [link](https://www.bilibili.com/video/BV14S4y1L791) |
| 150 | - | - | 13.3 使用Tensorflow2搭建ConvNeXt网络 | 14:32 | [link](https://www.bilibili.com/video/BV1TS4y1V7Gz) |
| 151 | - | - | 14.1 RepVGG网络讲解 | 32:07 | [link](https://www.bilibili.com/video/BV15f4y1o7QR) |
| 152 | - | - | 15.1 MobileViT网络讲解 | 26:03 | [link](https://www.bilibili.com/video/BV1TG41137sb) |
| 153 | - | - | 15.2 MobileViT源码解析(Pytorch) | 31:30 | [link](https://www.bilibili.com/video/BV1ae411L7Ki) |
| 154 | - | - | 大雁顶vlog | 7:09 | [link](https://www.bilibili.com/video/BV1NVsCenE2h) |
| 155 | - | - | 告别2024-穿越东西涌（冲） | 8:53 | [link](https://www.bilibili.com/video/BV1bJrwYAE9M) |
| 156 | - | - | 路过万达看到有人唱歌，头脑一热也上去唱了一首（有好几处没唱好，见谅） | 2:39 | [link](https://www.bilibili.com/video/BV1eHRfYNEpp) |
| 157 | - | - | 图像生成开篇 | 27:12 | [link](https://www.bilibili.com/video/BV1617T6iEGb) |
| 158 | - | - | DDPM介绍与公式推导 | 66:46 | [link](https://www.bilibili.com/video/BV15ZN66WERR) |
| 159 | - | - | Latent Diffusion Model | 20:12 | [link](https://www.bilibili.com/video/BV15DY36CE5p) |
| 160 | - | - | Scalable Diffusion Model with Transformers (DiTs) | 17:45 | [link](https://www.bilibili.com/video/BV1wLha63EHz) |
| 161 | - | - | 2021级寒假导学·2021.12.29直播回放——寒假导学 | 155:16 | [link](https://www.bilibili.com/video/BV1Pm4y1Q7zG) |
| 162 | - | - | 2021级寒假导学·2021.01.06直播回放——如何准备竞赛 | 111:01 | [link](https://www.bilibili.com/video/BV1s44y1j76u) |
| 163 | - | - | 2021级寒假导学·2021.01.11直播回放——数字电路 | 74:59 | [link](https://www.bilibili.com/video/BV1QZ4y1S77q) |
| 164 | - | - | 2021级寒假导学·2021.01.13直播回放——整数类型 | 95:09 | [link](https://www.bilibili.com/video/BV1SP4y1j7EG) |
| 165 | - | - | 2021级寒假导学·2021.01.17直播回放——浮点数与类型转换 | 101:49 | [link](https://www.bilibili.com/video/BV1v34y1B7UG) |
| 166 | - | - | 2021级寒假导学·2021.01.19直播回放——IO与行业历史八卦 | 113:59 | [link](https://www.bilibili.com/video/BV1h44y1L7V8) |
| 167 | - | - | 2021级寒假导学·2021.01.20直播回放——IO与缓冲机制 | 88:00 | [link](https://www.bilibili.com/video/BV11L411c7Q3) |
| 168 | - | - | 2021级寒假导学·2021.02.03直播回放——物理空间到信息空间（数学建模和数组） | 102:51 | [link](https://www.bilibili.com/video/BV1cr4y1h7kZ) |
| 169 | - | - | 2021级寒假导学·2021.02.05直播回放——项目与调试 | 79:48 | [link](https://www.bilibili.com/video/BV1h34y1y7Dq) |
| 170 | - | - | 2021级寒假导学·2021.02.08直播回放——指针与内存 | 90:11 | [link](https://www.bilibili.com/video/BV16m4y1Z78E) |
| 171 | - | - | 2021级寒假导学·2021.02.09直播回放——指针、IO与内存对齐 | 76:30 | [link](https://www.bilibili.com/video/BV13i4y1f7hY) |
| 172 | - | - | 从“卷积”、到“图像卷积操作”、再到“卷积神经网络”，“卷积”意义的3次改变 | 26:58 | [link](https://www.bilibili.com/video/BV1VV411478E) |
| 173 | - | - | 卷积神经网络的底层是傅里叶变换，傅里叶变换的底层是希尔伯特空间坐标变换 | 38:26 | [link](https://www.bilibili.com/video/BV1ce4y1p7jF) |
| 174 | - | - | “L1和L2正则化”直观理解(之一)，从拉格朗日乘数法角度进行理解 | 28:00 | [link](https://www.bilibili.com/video/BV1Z44y147xA) |
| 175 | - | - | “L1和L2正则化”直观理解(之二)，为什么又叫权重衰减？到底哪里衰减了？ | 35:04 | [link](https://www.bilibili.com/video/BV1gf4y1c7Gg) |
| 176 | - | - | 贝叶斯解释“L1和L2正则化”，本质上是最大后验估计。如何深入理解贝叶斯公式？ | 35:55 | [link](https://www.bilibili.com/video/BV1fR4y177jP) |
| 177 | - | - | 用VC维度理解SVM的结构风险最小化 & VC维是理解正则化的第4个角度 | 30:28 | [link](https://www.bilibili.com/video/BV1ML41177qc) |
| 178 | - | - | 1. 非计算机专业学编程难在哪？ | 6:15 | [link](https://www.bilibili.com/video/BV123411p7rf) |
| 179 | - | - | 2. 为什么所有编程语言都是数据+指令？ | 18:48 | [link](https://www.bilibili.com/video/BV1Za411t7c6) |
| 180 | - | - | 3. 编程是如何用数学解决现实问题的？ | 22:20 | [link](https://www.bilibili.com/video/BV1gr4y1W7As) |
| 181 | - | - | 4. 用“λ演算法”去理解，为什么函数式编程会有更少的bug | 37:09 | [link](https://www.bilibili.com/video/BV1d34y1v7xr) |
| 182 | - | - | 5. 深度学习和元胞自动机有什么关系？会给编程带来什么样的颠覆性改变？ | 47:48 | [link](https://www.bilibili.com/video/BV1BF411T7wh) |
| 183 | - | - | 6. 软件工程背后的思想是如何影响编程的 | 47:32 | [link](https://www.bilibili.com/video/BV1h3411G741) |
| 184 | - | - | 7. 程序员的性格为什么那么轴，那都是有原因的 | 29:47 | [link](https://www.bilibili.com/video/BV1gK411D7zc) |
| 185 | - | - | 从头开始，把概率论、统计、信息论中零散的知识统一起来 | 55:54 | [link](https://www.bilibili.com/video/BV1vv4y1B714) |
| 186 | - | - | 如何用概率论解决真实问题？用随机变量去建模，最大的难题是相关关系 | 57:22 | [link](https://www.bilibili.com/video/BV1Xs4y1z72n) |
| 187 | - | - | 直观理解概率论里的“依概率收敛” “几乎处处收敛”“以分布收敛” | 9:47 | [link](https://www.bilibili.com/video/BV1Lm4y1q7pQ) |
| 188 | - | - | 概率论里的特征函数，如何用卷积定理去理解 | 4:23 | [link](https://www.bilibili.com/video/BV1Fj411X7nP) |
| 189 | - | - | 真随机存在吗？量子力学如何超越概率论？经典概率和量子概率的联系与区别 | 128:00 | [link](https://www.bilibili.com/video/BV1r14y1q761) |
| 190 | - | - | 从编解码和词嵌入开始，一步一步理解Transformer，注意力机制(Attention)的本质是卷积神经网络(CNN) | 105:12 | [link](https://www.bilibili.com/video/BV1XH4y1T76e) |
| 191 | - | - | 学习分享一年，对神经网络的理解全都在这40分钟里了 | 43:18 | [link](https://www.bilibili.com/video/BV1FP411j7oW) |
| 192 | - | - | 什么是SVM，如何理解软间隔？什么是合叶损失函数、铰链损失函数？SVM与感知机横向对比，挖掘机器学习本质 | 36:38 | [link](https://www.bilibili.com/video/BV1zq4y1g74J) |
| 193 | - | - | “交叉熵”如何做损失函数？打包理解“信息量”、“比特”、“熵”、“KL散度”、“交叉熵” | 30:17 | [link](https://www.bilibili.com/video/BV15V411W7VB) |
| 194 | - | - | “损失函数”是如何设计出来的？直观理解“最小二乘法”和“极大似然估计法” | 22:07 | [link](https://www.bilibili.com/video/BV1Y64y1Q7hi) |
| 195 | - | - | softmax是为了解决归一问题凑出来的吗？和最大熵是什么关系？最大熵对机器学习为什么非常重要？ | 59:47 | [link](https://www.bilibili.com/video/BV1cP4y1t7cP) |
| 196 | - | - | 如何理解“梯度下降法”？什么是“反向传播”？通过一个视频，一步一步全部搞明白 | 49:48 | [link](https://www.bilibili.com/video/BV1Zg411T71b) |
| 197 | - | - | “随机梯度下降、牛顿法、动量法、Nesterov、AdaGrad、RMSprop、Adam”，打包理解对梯度下降法的优化 | 34:28 | [link](https://www.bilibili.com/video/BV1r64y1s7fU) |
| 198 | - | - | 如果大数定律失效，机器学习还能学吗？幂律分布可以告诉你答案 | 30:14 | [link](https://www.bilibili.com/video/BV1QR4y1W7eK) |
| 199 | - | - | VC维是如何推导出来的？为什么说它是机器学习理论最重要的发明？ | 73:30 | [link](https://www.bilibili.com/video/BV1Nr4y1i7or) |
| 200 | - | - | 直观解释：为什么噪声不是过拟合的原因?又什么只要没有过拟合就一定有噪声? | 47:23 | [link](https://www.bilibili.com/video/BV1a44y1M7qx) |
| 201 | - | - | Pytorch 搭建自己的Ghostnet-YoloV4目标检测平台（Bubbliiiing）-Ghostnet网络介绍与构建 | 24:13 | [link](https://www.bilibili.com/video/BV1KS4y1g7yz) |
| 202 | - | - | Pytorch 搭建自己的Ghostnet-YoloV4目标检测平台（Bubbliiiing）-将Ghostnet添加到YoloV4当中 | 3:55 | [link](https://www.bilibili.com/video/BV1q34y1t7rJ) |
| 203 | - | - | Pytorch 搭建自己的Ghostnet-YoloV4目标检测平台（Bubbliiiing）-训练与预测 | 2:29 | [link](https://www.bilibili.com/video/BV1cF411x7aa) |
| 204 | - | - | 如何下载与打开一个Github深度学习库 | 12:43 | [link](https://www.bilibili.com/video/BV1GY4y1t7Cc) |
| 205 | - | - | 如何使用一个Github深度学习库 | 13:57 | [link](https://www.bilibili.com/video/BV1nY411w7tr) |
| 206 | - | - | 如何分解与学习一个深度学习库 | 22:15 | [link](https://www.bilibili.com/video/BV1UB4y197pQ) |
| 207 | - | - | 如何修改一个深度学习库 | 12:10 | [link](https://www.bilibili.com/video/BV1FF411j7BP) |
| 208 | - | - | Pytorch 搭建自己的YoloV5目标检测平台（Bubbliiiing 源码详解 训练 预测）-YoloV5整体结构介绍 | 4:30 | [link](https://www.bilibili.com/video/BV1FZ4y1m777) |
| 209 | - | - | Pytorch 搭建自己的YoloV5目标检测平台（Bubbliiiing 源码详解 训练 预测）-主干网络介绍 | 17:20 | [link](https://www.bilibili.com/video/BV1FL4y1L7t1) |
| 210 | - | - | Pytorch 搭建自己的YoloV5目标检测平台（Bubbliiiing 源码详解 训练 预测）-加强特征提取网络介绍 | 10:27 | [link](https://www.bilibili.com/video/BV1cS4y1A7Wi) |
| 211 | - | - | Pytorch 搭建自己的YoloV5目标检测平台（Bubbliiiing 源码详解 训练 预测）-先验框原理介绍 | 20:03 | [link](https://www.bilibili.com/video/BV1AB4y1U7qX) |
| 212 | - | - | Pytorch 搭建自己的YoloV5目标检测平台（Bubbliiiing 源码详解 训练 预测）-Yolo Head介绍 | 9:21 | [link](https://www.bilibili.com/video/BV14Y4y1e7XC) |
| 213 | - | - | Pytorch 搭建自己的YoloV5目标检测平台（Bubbliiiing 源码详解 训练 预测）-预测过程介绍 | 17:28 | [link](https://www.bilibili.com/video/BV1R94y1d7yf) |
| 214 | - | - | Pytorch 搭建自己的YoloV5目标检测平台（Bubbliiiing 源码详解 训练 预测）-数据集格式介绍 | 5:02 | [link](https://www.bilibili.com/video/BV1kT4y1h7Jp) |
| 215 | - | - | Pytorch 搭建自己的YoloV5目标检测平台（Bubbliiiing 源码详解 训练 预测）-YoloV5训练参数解析 | 12:07 | [link](https://www.bilibili.com/video/BV1VY4y1p7yR) |
| 216 | - | - | Pytorch 搭建自己的YoloV5目标检测平台（Bubbliiiing 源码详解 训练 预测）-训练VOC数据集 | 6:04 | [link](https://www.bilibili.com/video/BV1iu411C7qa) |
| 217 | - | - | Pytorch 搭建自己的YoloV5目标检测平台（Bubbliiiing 源码详解 训练 预测）-训练自己的数据集 | 9:33 | [link](https://www.bilibili.com/video/BV1vS4y1w75r) |
| 218 | - | - | Pytorch 搭建自己的YoloV5目标检测平台（Bubbliiiing 源码详解 训练 预测）-模型预测 | 7:07 | [link](https://www.bilibili.com/video/BV1m94y1d7ja) |
| 219 | - | - | Pytorch 搭建自己的YoloV5目标检测平台（Bubbliiiing 源码详解 训练 预测）-模型训练前的数据预处理 | 9:13 | [link](https://www.bilibili.com/video/BV1i541127QC) |
| 220 | - | - | Pytorch 搭建自己的YoloV5目标检测平台（Bubbliiiing 源码详解 训练 预测）-模型的损失构建 | 30:44 | [link](https://www.bilibili.com/video/BV1nB4y1U7zY) |
| 221 | - | - | AI写真现在这么卷了吗？不仅可以单人SOLO，还可以有闺蜜照和漫画风？ | 18:36 | [link](https://www.bilibili.com/video/BV1c34y1K7by) |
| 222 | - | - | EasyPhoto双人写真实现-闺蜜照？兄弟照？指不定还能团体照！ | 9:10 | [link](https://www.bilibili.com/video/BV1bh4y1v7Vx) |
| 223 | - | - | 深入浅出Self-Attention自注意力机制与Transformer模块-自注意力机制详解 | 16:27 | [link](https://www.bilibili.com/video/BV1Rm411S7ML) |
| 224 | - | - | Keras 搭建自己的Ghostnet-YoloV4目标检测平台（Bubbliiiing）-Ghostnet网络介绍与构建 | 20:19 | [link](https://www.bilibili.com/video/BV19q4y1t7fJ) |
| 225 | - | - | Keras 搭建自己的Ghostnet-YoloV4目标检测平台（Bubbliiiing）-将Ghostnet添加到YoloV4当中 | 6:48 | [link](https://www.bilibili.com/video/BV1Ku411X7JY) |
| 226 | - | - | Keras 搭建自己的Ghostnet-YoloV4目标检测平台（Bubbliiiing）-训练与预测 | 2:28 | [link](https://www.bilibili.com/video/BV15S4y1F7aM) |
| 227 | - | - | 整理了几个100%会踩的Python细节坑，提前防止脑血栓 | 3:16 | [link](https://www.bilibili.com/video/BV1Vd4y1g7gX) |
| 228 | - | - | 整理了十个100%提高效率的Python编程技巧，再上一层楼 | 3:47 | [link](https://www.bilibili.com/video/BV1NT411M7DM) |
| 229 | - | - | 这些包括我在内都有的Python编程陋习，趁早改掉 | 3:39 | [link](https://www.bilibili.com/video/BV1nG411w7qw) |
| 230 | - | - | 列表推导式，Python最好的特性？可读性？ | 3:27 | [link](https://www.bilibili.com/video/BV13d4y1b7md) |
| 231 | - | - | 元组啊，不就是不可变的列表吗 | 5:58 | [link](https://www.bilibili.com/video/BV1yt4y1N7kh) |
| 232 | - | - | Python可变类型的坑，不要再踩了 | 4:29 | [link](https://www.bilibili.com/video/BV1rG4y1d7SV) |
| 233 | - | - | 科研第一课，流程与工具全梳理 | 60:48 | [link](https://www.bilibili.com/video/BV11VSwY1EkP) |
| 234 | - | - | 十年投稿经验，一小时拿去 | 59:54 | [link](https://www.bilibili.com/video/BV1qRmiYZE2d) |
| 235 | - | - | 科研论文写作实操，哪些是重点？哪些要规避？ | 55:05 | [link](https://www.bilibili.com/video/BV19TBsYfEsm) |
| 236 | - | - | 科研论文各模块到底咋写？摘要/引言/方法/实验/总结 | 54:05 | [link](https://www.bilibili.com/video/BV1KUBjYfEwQ) |
| 237 | - | - | 科研论文写作实操-如何魔改、命名/图表排版与美观/实验占比与工作饱和度 | 59:06 | [link](https://www.bilibili.com/video/BV1QJkYY4EEo) |
| 238 | - | - | 论文Rebuttal真的有用！ | 57:42 | [link](https://www.bilibili.com/video/BV1gw6hY5ENm) |
| 239 | - | - | 论文投稿后务必知晓的注意事项！ | 48:22 | [link](https://www.bilibili.com/video/BV1WerPYhEoy) |
| 240 | - | - | 别让审稿人费劲！硕博毕业大论文从盲审到答辩的写作3大核心 | 58:38 | [link](https://www.bilibili.com/video/BV128c4z6Ec3) |
| 241 | - | - | 巧取SCI/CCF论文！审稿人亲述顶会写作投稿致命问题及解决方案 | 58:19 | [link](https://www.bilibili.com/video/BV1SGAYzPE8f) |
| 242 | - | - | 如何提高毕业大论文通过率？全流程解析从格式规范到盲审与答辩的实用技巧 | 58:12 | [link](https://www.bilibili.com/video/BV1pWQSBrE7E) |
| 243 | - | - | 论文写作避坑！大模型效率优化论文速成指南——AI辅助提效+中稿技巧 | 43:07 | [link](https://www.bilibili.com/video/BV1xo9DBRE91) |
| 244 | - | - | 3h精通Opencv-Python | 189:08 | [link](https://www.bilibili.com/video/BV16K411W7x9) |
| 245 | - | - | 4h上手C++版Opencv | 237:04 | [link](https://www.bilibili.com/video/BV11A411T7rL) |
| 246 | - | - | 做了个一键转换与编辑图像标注文件软件，极大提高效率 | 7:29 | [link](https://www.bilibili.com/video/BV1aP4y1Z7f3) |
| 247 | - | - | 图片数据不够？我做了一个免费的图像增强软件 | 5:20 | [link](https://www.bilibili.com/video/BV1kR4y1T766) |
| 248 | - | - | 图像增强软件V2.0，适用于/目标检测/图像分割/图像分类/ | 5:38 | [link](https://www.bilibili.com/video/BV1gZ4y1C7Ex) |
| 249 | - | - | 图像增强软件V3.0，我不允许你的数据比别人少 | 4:01 | [link](https://www.bilibili.com/video/BV1Sv4y1S7yb) |
| 250 | - | - | 【Pytorch 与神经网络】pytorch 环境安装和基础操作，由浅及深彻底掌握Pytorch | 65:07 | [link](https://www.bilibili.com/video/BV1Vj421R7HD) |
| 251 | - | - | 【Pytorch 与神经网络】一节课搞定数据集处理｜模型训练+分布式训练 | 119:00 | [link](https://www.bilibili.com/video/BV1hr421x7qH) |
| 252 | - | - | 【Pytorch 与神经网络】机器视觉概念+代码实战教程 | 60:32 | [link](https://www.bilibili.com/video/BV1dz421k7AG) |
| 253 | - | - | 【Pytorch 与神经网络】机器视觉任务介绍+代码实战教程 | 59:28 | [link](https://www.bilibili.com/video/BV1sK421a7Rm) |
| 254 | - | - | 【Pytorch 与神经网络】nlp模型介绍+代码实战教程 | 57:17 | [link](https://www.bilibili.com/video/BV1xE421T7xb) |
| 255 | - | - | 【Pytorch 与神经网络】nlp任务介绍+代码复现 | 57:36 | [link](https://www.bilibili.com/video/BV1GT421U742) |
| 256 | - | - | 【Pytorch 与神经网络】生成式模型介绍，附：代码实战教程 | 40:55 | [link](https://www.bilibili.com/video/BV1km411B7cj) |
| 257 | - | - | Pytorch与神经网络 / 模型训练/学习方式 | 55:21 | [link](https://www.bilibili.com/video/BV15s421K76x) |
| 258 | - | - | 1.入门知识与子词分词器实现-从零到一搭建Transformer项目 | 81:18 | [link](https://www.bilibili.com/video/BV17UwyzLE9y) |
| 259 | - | - | 2.多头注意力与位置编码-从零到一搭建Transformer项目 | 90:15 | [link](https://www.bilibili.com/video/BV1EUwyzLEG1) |
| 260 | - | - | 3.构建Transformer模型-从零到一搭建Transformer项目 | 83:15 | [link](https://www.bilibili.com/video/BV129AJzZE3M) |
| 261 | - | - | 具身智能——LLM for robotics | 57:09 | [link](https://www.bilibili.com/video/BV1CH4y1G7wx) |
| 262 | - | - | 具身智能——LLM for robotics(2) | 56:53 | [link](https://www.bilibili.com/video/BV16x4y1v7EU) |
| 263 | - | - | 一节课搞定YOLO-World项目实战与轻量化部署 | 86:13 | [link](https://www.bilibili.com/video/BV1eK3uz8E43) |
| 264 | - | - | 一节课搞定自动驾驶点云目标检测 | 85:37 | [link](https://www.bilibili.com/video/BV1JL39zwEXZ) |
| 265 | - | - | 一节课搞定YOLOv9详解/代码实战/轻量部署 | 72:47 | [link](https://www.bilibili.com/video/BV1rnGnzkEws) |
| 266 | - | - | 一节课搞定YOLOv10原理&代码实战 | 73:05 | [link](https://www.bilibili.com/video/BV1FPGgzyE5w) |
| 267 | - | - | 一节课搞定YOLOv8项目实战 | 96:26 | [link](https://www.bilibili.com/video/BV1FHuFzrEWg) |
| 268 | - | - | 一节课看尽深度学习目标检测这十年！ | 83:18 | [link](https://www.bilibili.com/video/BV1Cju1zrEAD) |
| 269 | - | - | 一节课搞懂机器人中的多模态及代码实战 | 60:01 | [link](https://www.bilibili.com/video/BV1NcgwzoESp) |
| 270 | - | - | 超越YOLO！一节课搞懂新生代目标检测器Grounding DINO | 62:28 | [link](https://www.bilibili.com/video/BV1rjgBzHEBW) |
| 271 | - | - | 一节课搞定YOLOv8多目标实例分割与跟踪详解+实战 | 78:00 | [link](https://www.bilibili.com/video/BV15n8czXEBu) |
| 272 | - | - | 一节课搞懂医学分割终结者模型MedSAM | 68:38 | [link](https://www.bilibili.com/video/BV1GP8ezCEa2) |
| 273 | - | - | 一节课搞懂基于mamba的自动驾驶感知 | 53:21 | [link](https://www.bilibili.com/video/BV1318RzKEeT) |
| 274 | - | - | 自动驾驶大一统新作，一节课搞懂DriveTransformer | 46:24 | [link](https://www.bilibili.com/video/BV1WthHzaEa8) |
| 275 | - | - | 超越所有OCC视觉方案，一节课搞懂CVT-OCC算法 | 56:51 | [link](https://www.bilibili.com/video/BV14RtJzsENU) |
| 276 | - | - | 分割一切医学图像，一节课搞懂超级模块MedSAM | 72:57 | [link](https://www.bilibili.com/video/BV1dTtqznECo) |
| 277 | - | - | 实现自动驾驶实时协同感知，一节课速通Mamba高阶魔改 | 53:24 | [link](https://www.bilibili.com/video/BV1JLtoz2EKs) |
| 278 | - | - | 迈向3D全景分割大一统，一节课速通PanoOcc算法 | 57:06 | [link](https://www.bilibili.com/video/BV1XqbWzjEzW) |
| 279 | - | - | 多模态大模型高效微调方法，视觉语言融合SOTA | 54:19 | [link](https://www.bilibili.com/video/BV1aae8zkEja) |
| 280 | - | - | 车企人眼中的3D占用预测网络，一节课速通CVT-OCC | 48:58 | [link](https://www.bilibili.com/video/BV1zrvNzpEW6) |
| 281 | - | - | 多模态大模型+具身智能，一节课解锁RoboBrain顶会创新 | 59:53 | [link](https://www.bilibili.com/video/BV1rEptzWEqT) |
| 282 | - | - | 顶会论文写作与实例分享，用对方法篇篇都是SCI！ | 61:41 | [link](https://www.bilibili.com/video/BV1zHW3z3EMw) |
| 283 | - | - | 一节课掌握多模态大模型统一分割框架： OMG-LLaVA | 54:36 | [link](https://www.bilibili.com/video/BV1e8nwzAEPh) |
| 284 | - | - | 大模型微调效率巅峰，一节课速通顶会微调思路VB-LoRA | 55:02 | [link](https://www.bilibili.com/video/BV1GMngznEVi) |
| 285 | - | - | 基于transformer的跨模态3D目标检测SOTA！易复现！ | 43:45 | [link](https://www.bilibili.com/video/BV1LRsnzYEaf) |
| 286 | - | - | 2025新拐点！一节课概览端到端自动驾驶，直击技术最前沿 | 76:07 | [link](https://www.bilibili.com/video/BV1qR1CBeEeu) |
| 287 | - | - | 自动驾驶OCC感知算法大爆！全方位解读Flash-OCC | 84:46 | [link](https://www.bilibili.com/video/BV1bP2ABgEQU) |
| 288 | - | - | 自动驾驶感知是否已接近极限？一节课全面盘点技术前沿！ | 42:11 | [link](https://www.bilibili.com/video/BV1PXkkBKEej) |
| 289 | - | - | 一节课搞定自动驾驶视觉感知算法-BEVFormer | 65:42 | [link](https://www.bilibili.com/video/BV1FCyGBmEf6) |
| 290 | - | - | 实现高级别自动驾驶的关键：一节课搞定多传感器融合 | 71:46 | [link](https://www.bilibili.com/video/BV1E1ycB2Ehp) |
| 291 | - | - | 老兵不死！百度开源BEVWorld：BEV潜在空间构建多模态世界模型，全面理解自动驾驶~ | 65:11 | [link](https://www.bilibili.com/video/BV1g2UQBXEy2) |
| 292 | - | - | 自动驾驶绕不开的前沿技术，一节课聊聊点云深度学习的二三事 | 79:40 | [link](https://www.bilibili.com/video/BV1vwStBbEap) |
| 293 | - | - | 一节课搞定自动驾驶之规控与预测，研梦非凡自动驾驶必学系列 | 47:17 | [link](https://www.bilibili.com/video/BV1nQmxB8E1y) |
| 294 | - | - | 一节课搞定毫米波雷达必知必学15个知识点，研梦非凡自动驾驶必学系列 | 42:24 | [link](https://www.bilibili.com/video/BV1smq8BpERr) |
| 295 | - | - | 一节课认知基于分层强化学习的规控算法，研梦非凡自动驾驶必学系列 | 58:08 | [link](https://www.bilibili.com/video/BV1UPBKBtEz5) |
| 296 | - | - | 自动驾驶热门方向：一节课掌握基于提示学习的VLM蒸馏新方法！ | 55:46 | [link](https://www.bilibili.com/video/BV1zavWBHEnz) |
| 297 | - | - | 大语言模型对时间序列预测有用吗？带你详拆一篇ICLR佳作 | 77:20 | [link](https://www.bilibili.com/video/BV1x6i9BHEE1) |
| 298 | - | - | 吊打一切卷积方法！审稿人带你看摸透Transformer+语义分割 | 46:06 | [link](https://www.bilibili.com/video/BV1ESkFBME7F) |
| 299 | - | - | 重温魔改Mamba核心：超车Transformer，备战今年CV各大顶会！ | 61:53 | [link](https://www.bilibili.com/video/BV1th6gBVEJc) |
| 300 | - | - | 一节课看懂分割一切视觉大模型，FastSAM论文/代码以及在工业场景中的应用 | 71:15 | [link](https://www.bilibili.com/video/BV1mRcEzHEr9) |
| 301 | - | - | 一节课看懂分割一切视觉大模型，FastSAM论文/代码以及在工业场景中的应用 | 77:01 | [link](https://www.bilibili.com/video/BV1PpfbBTEUJ) |
| 302 | - | - | VoxFormer算法解析：自驾感知算法革命，英伟达技术力拉满！ | 49:17 | [link](https://www.bilibili.com/video/BV1Sxwcz3EZa) |
| 303 | - | - | VoxFormer深度剖析：自驾感知算法革命，英伟达技术力拉满！ | 37:48 | [link](https://www.bilibili.com/video/BV1Sxwcz3EqZ) |
| 304 | - | - | 大模型加速算法：FlashAttention-V1原理篇，不会CUDA也能轻松看懂！ | 60:17 | [link](https://www.bilibili.com/video/BV1VVDLB4Ecw) |
| 305 | - | - | 大模型加速算法：FlashAttention-V2原理篇，不会CUDA也能轻松看懂！ | 81:10 | [link](https://www.bilibili.com/video/BV1SnD4BnEJ8) |
| 306 | - | - | 大模型加速算法：FlashAttention-V3原理篇，不会CUDA也能轻松看懂！ | 60:27 | [link](https://www.bilibili.com/video/BV1p7QwBgETM) |
| 307 | - | - | 大模型加速算法：FlashAttention论文解读，不会CUDA也能轻松看懂！ | 58:49 | [link](https://www.bilibili.com/video/BV1KFQEBoEo9) |
| 308 | - | - | YOLOE：实时通用目标检测的感知一切，开放词汇系列顶会文献精读 | 50:35 | [link](https://www.bilibili.com/video/BV1h7d5BYEee) |
| 309 | - | - | /AI学习路线分享/做完这些，你已经成为机器学习方面的专家 | 4:44 | [link](https://www.bilibili.com/video/BV16341177c1) |
| 310 | - | - | 非科班上岸算法工程师，我的心得分享 | 6:36 | [link](https://www.bilibili.com/video/BV1M34y117gp) |
| 311 | - | - | 『帮帮TA』导师佛系无实习无成果无项目，救救孩子 | 3:36 | [link](https://www.bilibili.com/video/BV1ri4y127YT) |
| 312 | - | - | 『帮帮TA』导师的首届学生/组会频繁/非科班/基础差 | 6:27 | [link](https://www.bilibili.com/video/BV1Pa411878V) |
| 313 | - | - | 关于裁员，我对读研期间所见所闻进行了复盘 | 6:43 | [link](https://www.bilibili.com/video/BV12S4y1N7nG) |
| 314 | - | - | 这份实用校招指南，请查收 | 5:25 | [link](https://www.bilibili.com/video/BV17Z4y1e7zk) |
| 315 | - | - | 【一个月吃透深度学习】零基础都能看懂，人工智能基础入门必看！ | 85:48 | [link](https://www.bilibili.com/video/BV1u5411i7K7) |
| 316 | - | - | 【一个月吃透深度学习】长短期记忆网络教程，零基础人工智能入门必备！ | 47:09 | [link](https://www.bilibili.com/video/BV1Tg4y1U7Lp) |
| 317 | - | - | 【一个月吃透深度学习】循环网络与一维卷积的应用，零基础都能看懂，人工智能入门必看！ | 72:24 | [link](https://www.bilibili.com/video/BV1qK4y1z7AN) |
| 318 | - | - | 【一个月吃透深度学习】项目实战【数据数值化（张量化）覆写torch下的Dataset类】，零基础人工智能入门必备！ | 110:33 | [link](https://www.bilibili.com/video/BV1DB421z7E8) |
| 319 | - | - | 【一个月吃透深度学习】项目实战（Pytorch实现卷积网络的文本分类），零基础人工智能入门必备！ | 54:21 | [link](https://www.bilibili.com/video/BV1xB421z7HU) |
| 320 | - | - | 【一个月吃透深度学习】项目实战（Pytorch实现神经网络的文本分类），零基础人工智能入门必备！ | 58:52 | [link](https://www.bilibili.com/video/BV1zb4y1N72M) |
| 321 | - | - | 【一个月吃透深度学习】Pytorch实现文本分类｜IMDB电影评论分析项目实战，零基础入门必备！ | 105:20 | [link](https://www.bilibili.com/video/BV1j642137J4) |
| 322 | - | - | 吃透《统计学习方法》 | 115:12 | [link](https://www.bilibili.com/video/BV1tZ4y1U7ot) |
| 323 | - | - | 《统计学习方法》第一章课后习题解答 | 71:39 | [link](https://www.bilibili.com/video/BV1pP411M7DX) |
| 324 | - | - | 《统计学习方法》第二章：感知机 | 71:54 | [link](https://www.bilibili.com/video/BV1C44y1P7tA) |
| 325 | - | - | 《统计学习方法》第三章：K近邻 | 65:07 | [link](https://www.bilibili.com/video/BV1pi4y1D7Y3) |
| 326 | - | - | 《统计学习方法》第四章：朴素贝叶斯 | 132:36 | [link](https://www.bilibili.com/video/BV1sS4y1Y7mN) |
| 327 | - | - | 《统计学习方法》第五章：决策树 | 337:09 | [link](https://www.bilibili.com/video/BV19B4y127Nv) |
| 328 | - | - | 《统计学习方法》第六章：逻辑回归 | 79:55 | [link](https://www.bilibili.com/video/BV1aa411a7P8) |
| 329 | - | - | 《统计学习方法》第七章：最大熵模型 | 326:41 | [link](https://www.bilibili.com/video/BV1jY4y1t7Jt) |
| 330 | - | - | 《统计学习方法》第八章：支持向量机 | 429:52 | [link](https://www.bilibili.com/video/BV1ct4y157B1) |
| 331 | - | - | 《统计学习方法》第九章：提升方法 | 250:40 | [link](https://www.bilibili.com/video/BV1iP41177MY) |
| 332 | - | - | 《统计学习方法》第十章：EM算法 | 263:59 | [link](https://www.bilibili.com/video/BV12P411N7sj) |
| 333 | - | - | 《统计学习方法》第十一章：隐马尔可夫模型 | 270:40 | [link](https://www.bilibili.com/video/BV1HN411x736) |
| 334 | - | - | 《统计学习方法》第十二章：条件随机场 | 319:20 | [link](https://www.bilibili.com/video/BV11b4y1K7tN) |
| 335 | - | - | 《统计学习方法》第十三章：无监督学习 | 66:11 | [link](https://www.bilibili.com/video/BV1cxdaYrE2J) |
| 336 | - | - | 《统计学习方法》第十四章：聚类 | 88:16 | [link](https://www.bilibili.com/video/BV1Swj3zBEM2) |
| 337 | - | - | YOLOV8详解与轻量部署--YOLO基础篇 | 21:48 | [link](https://www.bilibili.com/video/BV1b6cwe7ETq) |
| 338 | - | - | YOLOV8详解与轻量部署--YOLOv5、YOLOv8解析 | 19:59 | [link](https://www.bilibili.com/video/BV1bAcBeJEfT) |
| 339 | - | - | YOLOV8详解与轻量部署--代码实战 | 18:48 | [link](https://www.bilibili.com/video/BV1aJwweREvx) |
| 340 | - | - | YOLOV8详解与轻量部署--推理部署 | 22:00 | [link](https://www.bilibili.com/video/BV16GfhYGELa) |
| 341 | - | - | 论文泛读-如何快速了解一篇文章（大模型方向为例） | 19:22 | [link](https://www.bilibili.com/video/BV18SNWexEdk) |
| 342 | - | - | 论文泛读-题目/作者/单位/摘要/结论怎么看？ | 13:46 | [link](https://www.bilibili.com/video/BV1sKNSeDEA9) |
| 343 | - | - | 论文泛读-图、表、公式、实验很重要 | 18:00 | [link](https://www.bilibili.com/video/BV1VNAVeZEG4) |
| 344 | - | - | 我将维护一个集成各主干网络的图像分类项目 | 14:14 | [link](https://www.bilibili.com/video/BV1SY411P7Nd) |
| 345 | - | - | 最新Windows配置VSCode与Anaconda环境 | 5:43 | [link](https://www.bilibili.com/video/BV1QD4y147ek) |
| 346 | - | - | 『图像分类』从零环境搭建&快速开始 | 4:01 | [link](https://www.bilibili.com/video/BV1fe4y1s77Q) |
| 347 | - | - | 『图像分类』模型如何搭建/文件如何调用 | 11:37 | [link](https://www.bilibili.com/video/BV12a411772h) |
| 348 | - | - | 『图像分类』数据预处理/数据增强 | 10:16 | [link](https://www.bilibili.com/video/BV1zY4y167Ju) |
| 349 | - | - | 『图像分类』学习率更新策略/优化器 | 9:02 | [link](https://www.bilibili.com/video/BV1WT4y1q7qN) |
| 350 | - | - | 『图像分类』配置文件补充说明 | 4:15 | [link](https://www.bilibili.com/video/BV1bt4y1W7mm) |
| 351 | - | - | 【一个月吃透机器学习】李航《统计学习方法》，零基础同学必学课程！！！ | 54:53 | [link](https://www.bilibili.com/video/BV14j421U7oW) |
| 352 | - | - | 【一个月吃透机器学习】K近邻，感知机，手把手代码实战教程！！！ | 143:37 | [link](https://www.bilibili.com/video/BV1zC411p7N6) |
| 353 | - | - | 【一个月吃透机器学习】朴素贝叶斯原理，及手把手代码实战教程！！！ | 35:40 | [link](https://www.bilibili.com/video/BV17W421A73j) |
| 354 | - | - | 【一个月吃透机器学习】朴素贝叶斯知识点讲解，手把手代码实战教程！ | 126:15 | [link](https://www.bilibili.com/video/BV1ax421C7oH) |
| 355 | - | - | 【一个月吃透机器学习】朴素贝叶斯代码实战，手把手教你写代码 | 78:46 | [link](https://www.bilibili.com/video/BV1LZ421t7oS) |
| 356 | - | - | 【一个月吃透机器学习】PageRank算法前沿理论详解＋代码实战教程 | 124:52 | [link](https://www.bilibili.com/video/BV1sf421f7iq) |
| 357 | - | - | 【一个月吃透机器学习】支持向量机SVM前沿理论详解＋实现代码复现详程 | 102:22 | [link](https://www.bilibili.com/video/BV19K421a7Xy) |
| 358 | - | - | AI对程序员的冲击 | 7:51 | [link](https://www.bilibili.com/video/BV1tDRCBzEzj) |
| 359 | - | - | 你真的需要和大模型聊一下人生 | 4:32 | [link](https://www.bilibili.com/video/BV1t35g62E2v) |
| 360 | - | - | AGI来了，人类最大的危机不是失业 | 4:27 | [link](https://www.bilibili.com/video/BV1hiMM6FEFT) |
| 361 | - | - | 美国政府为什么要持股OpenAI？ 答案比你想的更可怕 | 7:52 | [link](https://www.bilibili.com/video/BV17ET16VErB) |
| 362 | - | - | 调用大模型到底是英文好还是中文好？ | 8:04 | [link](https://www.bilibili.com/video/BV1hjMa6cEvB) |
| 363 | - | - | Anthropic最新论文：大模型也会口是心非 | 8:42 | [link](https://www.bilibili.com/video/BV1FCNL6oEta) |
| 364 | - | - | 什么是HarnessEngineering？驾驭工程 | 22:50 | [link](https://www.bilibili.com/video/BV13uojB6Eyh) |
| 365 | - | - | HarnessEngineering 如何进行任务拆分 | 20:03 | [link](https://www.bilibili.com/video/BV1iwojBLEN5) |
| 366 | - | - | HarnessEngineering 如何引入外部知识 RAG，PageIndex，知识图谱，百科 | 41:18 | [link](https://www.bilibili.com/video/BV118RMBNE6j) |
| 367 | - | - | Harness 记忆 如何给智能体增加记忆 | 14:01 | [link](https://www.bilibili.com/video/BV1545m6cEqu) |
| 368 | - | - | Function Calling、MCP、CLI 到底差在哪？AI Agent 工具调用一次讲清 | 25:56 | [link](https://www.bilibili.com/video/BV1SsE368ELz) |
| 369 | - | - | AI Agent 沙箱技术演进史 容器 虚拟机 E2B | 24:40 | [link](https://www.bilibili.com/video/BV1jKj66JE8W) |
| 370 | - | - | 什么是强化学习《RethinFun强化学习》1.1 | 8:36 | [link](https://www.bilibili.com/video/BV14swKz7Ego) |
| 371 | - | - | 马尔科夫决策过程《RethinFun强化学习》1.2 | 30:31 | [link](https://www.bilibili.com/video/BV1rXwNzuEmJ) |
| 372 | - | - | 价值函数《RethinFun强化学习》1.3 | 9:12 | [link](https://www.bilibili.com/video/BV1kDwNz6EgY) |
| 373 | - | - | 贝尔曼方程《RethinFun强化学习》1.4 | 22:23 | [link](https://www.bilibili.com/video/BV1kDwNz6EZd) |
| 374 | - | - | 动态规划《RethinFun强化学习》2.1 | 20:42 | [link](https://www.bilibili.com/video/BV1ECAAzaECF) |
| 375 | - | - | 无模型方法MC、TD、SARSA、Q-Learning《RethinFun强化学习》2.2 | 16:34 | [link](https://www.bilibili.com/video/BV1riAAzKEkJ) |
| 376 | - | - | 动手实现悬崖漫步 SARSA、Q-Learning《RethinFun强化学习》2.3 | 8:31 | [link](https://www.bilibili.com/video/BV1wiAAzTEun) |
| 377 | - | - | DQN原理及核心机制：经验回放/目标网络《RethinFun强化学习》3.1 | 14:53 | [link](https://www.bilibili.com/video/BV1rkQcBPE8q) |
| 378 | - | - | DQN的进阶技巧：Double DQN / DuelingDQN《RethinFun强化学习》3.2 | 13:29 | [link](https://www.bilibili.com/video/BV1w6QcBiEHy) |
| 379 | - | - | DQN动手实现“登月舱”：Lunar Lander《RethinFun强化学习》3.3 | 11:31 | [link](https://www.bilibili.com/video/BV1w6QcBiEqf) |
| 380 | - | - | 强化学习策略网络Policy Network | 3:21 | [link](https://www.bilibili.com/video/BV1nz5t6nEYX) |
| 381 | - | - | 强化学习策略梯度算法原理 | 10:45 | [link](https://www.bilibili.com/video/BV1nz5t6nEyE) |
| 382 | - | - | 强化学习REINFORCE算法 | 7:22 | [link](https://www.bilibili.com/video/BV1fC5t6mEjf) |
| 383 | - | - | 强化学习增加Baseline | 2:59 | [link](https://www.bilibili.com/video/BV1EC5t6mES8) |
| 384 | - | - | Actor-Critic算法 A2C | 18:15 | [link](https://www.bilibili.com/video/BV1TBVN6fEuG) |
| 385 | - | - | GAE广义优势估计 | 9:50 | [link](https://www.bilibili.com/video/BV1EdVN67E5h) |
| 386 | - | - | PPO近端策略优化 | 12:32 | [link](https://www.bilibili.com/video/BV1zdVN67EVD) |
| 387 | - | - | PPO的Loss函数Entropy Loss | 5:38 | [link](https://www.bilibili.com/video/BV1f9VN6mEJm) |
| 388 | - | - | PPO的代码实现 | 11:00 | [link](https://www.bilibili.com/video/BV1f9VN6mE2p) |
| 389 | - | - | 生成算法数学基础（凸函数，Jensen不等式，KL散度） | 10:52 | [link](https://www.bilibili.com/video/BV1gexMzpEc7) |
| 390 | - | - | VAE算法讲解 （变分自编码器 Variational Auto-Encoder） | 30:18 | [link](https://www.bilibili.com/video/BV1xFxMz1EMS) |
| 391 | - | - | 图像生成 扩散模型 DDPM算法讲解（一）：直观理解 | 19:54 | [link](https://www.bilibili.com/video/BV16ZsPz4ECF) |
| 392 | - | - | 图像生成 扩散模型 DDPM算法讲解（二）：数学推导和代码实现 | 22:58 | [link](https://www.bilibili.com/video/BV11KsPzwE2m) |
| 393 | - | - | FlowMatching的直观理解 | 10:18 | [link](https://www.bilibili.com/video/BV142C2BSEbm) |
| 394 | - | - | FlowMatching的公式推导和源码实现 | 27:27 | [link](https://www.bilibili.com/video/BV1K2C2BSEZB) |
| 395 | - | - | Score Based Model 直观理解 | 16:48 | [link](https://www.bilibili.com/video/BV19cBMBMEzp) |
| 396 | - | - | Score Based Model公式推导及源码实现 | 14:03 | [link](https://www.bilibili.com/video/BV1GNBMBiEch) |
| 397 | - | - | 扩散模型：SDE，统一Score模型和DDPM | 28:43 | [link](https://www.bilibili.com/video/BV1PervBGEeY) |
| 398 | - | - | 条件和引导生成，conditional generation，Classifier Guidance，Classifier-Free Guidance，CFG | 18:05 | [link](https://www.bilibili.com/video/BV1EWBfBxENc) |
| 399 | - | - | DeepSeek-MOE原理讲解 | 18:20 | [link](https://www.bilibili.com/video/BV1uUPieDEK1) |
| 400 | - | - | DeepSeek-v2 MLA 原理讲解 | 16:58 | [link](https://www.bilibili.com/video/BV1BYXRYWEMj) |
| 401 | - | - | DeepSeek-v3原理讲解多token预测 MTP | 14:56 | [link](https://www.bilibili.com/video/BV1jA9HYfEAC) |
| 402 | - | - | DeepSeek-GRPO | 18:02 | [link](https://www.bilibili.com/video/BV1enQLYKEA5) |
| 403 | - | - | DeepSeekMathv2模型讲解/迈向自我验证的数学推理 | 18:55 | [link](https://www.bilibili.com/video/BV1C2S4BzECy) |
| 404 | - | - | DINO v1 算法讲解 | 22:46 | [link](https://www.bilibili.com/video/BV18AULBjED6) |
| 405 | - | - | DINO v2 算法讲解 | 21:19 | [link](https://www.bilibili.com/video/BV19nUDBDEd8) |
| 406 | - | - | DINO v3 算法讲解 | 21:02 | [link](https://www.bilibili.com/video/BV1ExUfBnEts) |
| 407 | - | - | PCA 主成分分析算法讲解(Principal Component Analysis) | 28:44 | [link](https://www.bilibili.com/video/BV1sty6BaE5J) |
| 408 | - | - | 《RethinkFun深度学习教程》：前言 | 1:57 | [link](https://www.bilibili.com/video/BV1do3LzUE6q) |
| 409 | - | - | 《RethinkFun深度学习教程》：1.1什么是深度学习 | 8:02 | [link](https://www.bilibili.com/video/BV1do3LzUEzr) |
| 410 | - | - | 《RethinkFun深度学习教程》：1.2如何学习深度学习 | 3:22 | [link](https://www.bilibili.com/video/BV1oo3LzUETV) |
| 411 | - | - | 《RethinkFun深度学习教程》：第二章 线性代数 2.1什么是向量 | 6:18 | [link](https://www.bilibili.com/video/BV1oo3LzUE83) |
| 412 | - | - | 《RethinkFun深度学习教程》：2.2向量的基 | 6:02 | [link](https://www.bilibili.com/video/BV1jo3LzSE4b) |
| 413 | - | - | 《RethinkFun深度学习教程》：2.3线性变换和矩阵 | 14:07 | [link](https://www.bilibili.com/video/BV1oo3LzUEsU) |
| 414 | - | - | 《RethinkFun深度学习教程》：2.4向量的点乘 | 8:19 | [link](https://www.bilibili.com/video/BV1io3LzSEqC) |
| 415 | - | - | 《RethinkFun深度学习教程》：2.5向量的叉乘 | 6:05 | [link](https://www.bilibili.com/video/BV1oo3LzUE3r) |
| 416 | - | - | 《RethinkFun深度学习教程》：3.1函数的极限 | 5:01 | [link](https://www.bilibili.com/video/BV1nu3SzSE8f) |
| 417 | - | - | 《RethinkFun深度学习教程》：3.2导数的定义 | 8:10 | [link](https://www.bilibili.com/video/BV1pN3SzpE1z) |
| 418 | - | - | 《RethinkFun深度学习教程》：3.3常用求导公式 | 4:01 | [link](https://www.bilibili.com/video/BV1jA3XzHEY1) |
| 419 | - | - | 《RethinkFun深度学习教程》：3.4导数运算法则 | 9:07 | [link](https://www.bilibili.com/video/BV1erGFzBEx5) |
| 420 | - | - | 《RethinkFun深度学习教程》：3.5一元函数微分 | 5:56 | [link](https://www.bilibili.com/video/BV1EU3iz1Eit) |
| 421 | - | - | 《RethinkFun深度学习教程》：3.6偏导数 | 3:39 | [link](https://www.bilibili.com/video/BV1883BziECP) |
| 422 | - | - | 《RethinkFun深度学习教程》：3.7全微分 | 7:58 | [link](https://www.bilibili.com/video/BV19k3qzBELC) |
| 423 | - | - | 《RethinkFun深度学习教程》：3.8方向导数与梯度 | 7:48 | [link](https://www.bilibili.com/video/BV1Ae3CzuE9M) |
| 424 | - | - | 《RethinkFun深度学习教程》：3.9定积分 | 6:41 | [link](https://www.bilibili.com/video/BV1Yh3kzHEdu) |
| 425 | - | - | 《RethinkFun深度学习教程》：第四章：深度学习里的概率与统计 | 9:17 | [link](https://www.bilibili.com/video/BV14U3yzmEFz) |
| 426 | - | - | 《RethinkFun深度学习教程》：4.2 概率里的基本运算 | 4:41 | [link](https://www.bilibili.com/video/BV16J3yzqEWw) |
| 427 | - | - | 《RethinkFun深度学习教程》：4.3随机变量及其分布 | 11:06 | [link](https://www.bilibili.com/video/BV1yHGpzSEKR) |
| 428 | - | - | 《RethinkFun深度学习教程》：4.4数学期望与方差 | 9:47 | [link](https://www.bilibili.com/video/BV1FUGHzVE14) |
| 429 | - | - | 《RethinkFun深度学习教程》：4.5大数定律 | 1:54 | [link](https://www.bilibili.com/video/BV1AkGHz7EiQ) |
| 430 | - | - | 《RethinkFun深度学习教程》：4.6 条件概率 | 6:38 | [link](https://www.bilibili.com/video/BV1JSGHzkEku) |
| 431 | - | - | 《RethinkFun深度学习教程》：4.7中心极限定理和正态分布 | 6:43 | [link](https://www.bilibili.com/video/BV14XGnzDEkn) |
| 432 | - | - | 《RethinkFun深度学习教程》：4.8极大似然估计 | 6:22 | [link](https://www.bilibili.com/video/BV1kPGHzVEup) |
| 433 | - | - | 《RethinkFun深度学习教程》：第五章 线性回归 5.1 一元线性回归 | 12:10 | [link](https://www.bilibili.com/video/BV1hDuPzTED5) |
| 434 | - | - | 《RethinkFun深度学习教程》：5.2 给线性回归增加偏置 | 3:01 | [link](https://www.bilibili.com/video/BV1ocu6zjEUq) |
| 435 | - | - | 《RethinkFun深度学习教程》5.3 梯度下降算法 | 11:33 | [link](https://www.bilibili.com/video/BV1wguzzpE4Z) |
| 436 | - | - | 《RethinkFun深度学习教程》5.4 多元线性回归 | 2:09 | [link](https://www.bilibili.com/video/BV1J5uzzUEhW) |
| 437 | - | - | 《RethinkFun深度学习教程》：5.5动手实现多元线性回归 | 3:39 | [link](https://www.bilibili.com/video/BV1J5uzzUE7F) |
| 438 | - | - | 《RethinkFun深度学习教程》：5.6线性回归只能拟合直线吗？ | 4:24 | [link](https://www.bilibili.com/video/BV1J5uzzUEWX) |
| 439 | - | - | 《RethinkFun深度学习教程》：第六章 线性回归 6.1 PyTorch简介 | 3:27 | [link](https://www.bilibili.com/video/BV1eVuHzxEyq) |
| 440 | - | - | 《RethinkFun深度学习教程》：6.2 CPU环境下的PyTorch安装 | 8:49 | [link](https://www.bilibili.com/video/BV1V9uJznENq) |
| 441 | - | - | 一次搞定Anaconda，PyTorch，CUDA，VS Code的安装 | 9:24 | [link](https://www.bilibili.com/video/BV131upzWETr) |
| 442 | - | - | 一次学懂PyTorch里的Tensor | 18:44 | [link](https://www.bilibili.com/video/BV1G1umz8EKH) |
| 443 | - | - | 《RethinkFun深度学习教程》：6.5 计算图与自动求梯度 | 3:12 | [link](https://www.bilibili.com/video/BV1KZumzHEZS) |
| 444 | - | - | 《RethinkFun深度学习教程》：6.6 用PyTorch实现线性回归 | 3:45 | [link](https://www.bilibili.com/video/BV1ppumzLEdG) |
| 445 | - | - | 《RethinkFun深度学习教程》：6.7 优美的Loss曲线 | 4:37 | [link](https://www.bilibili.com/video/BV1ALuRzPEmS) |
| 446 | - | - | 为什么深度学习需要做Normalization？ | 8:53 | [link](https://www.bilibili.com/video/BV1kJuozTE14) |
| 447 | - | - | 逻辑回归和线性回归有什么关系？ | 8:40 | [link](https://www.bilibili.com/video/BV1q3udzREu4) |
| 448 | - | - | 逻辑回归的loss为什么不用MSE | 4:44 | [link](https://www.bilibili.com/video/BV1KGgbzPEcD) |
| 449 | - | - | 《RethinkFun深度学习教程》：7.3多元逻辑回归 | 5:51 | [link](https://www.bilibili.com/video/BV1NLgbzwE6X) |
| 450 | - | - | 为什么要区分训练集和验证集？ | 6:18 | [link](https://www.bilibili.com/video/BV1ejg8zJE9a) |
| 451 | - | - | 《RethinkFun深度学习教程》：7.5 欠拟合和过拟合 | 4:34 | [link](https://www.bilibili.com/video/BV1sig8ziEBa) |
| 452 | - | - | 《RethinkFun深度学习教程》：7.6 二分类模型的评价指标 | 7:16 | [link](https://www.bilibili.com/video/BV1XCghzSEKu) |
| 453 | - | - | 《RethinkFun深度学习教程》：7.7 梯度下降算法的改进 | 4:02 | [link](https://www.bilibili.com/video/BV1ZngezAEFn) |
| 454 | - | - | PyTorch+逻辑回归进行Titanic生存预测 | 5:26 | [link](https://www.bilibili.com/video/BV1dUg5zGERE) |
| 455 | - | - | 《RethinkFun深度学习教程》：7.9 PyTorch里的Dataset和DataLoader | 3:40 | [link](https://www.bilibili.com/video/BV1vUg5zGEEX) |
| 456 | - | - | 《RethinkFun深度学习教程》：7.10 利用PyTorch定义逻辑回归模型 | 4:49 | [link](https://www.bilibili.com/video/BV1i2g5zCEqG) |
| 457 | - | - | 《RethinkFun深度学习教程》：7.11 用逻辑回归对Titanic数据进行训练 | 7:18 | [link](https://www.bilibili.com/video/BV1i2g5zCEMw) |
| 458 | - | - | 换个角度理解神经网络：从逻辑回归到神经网络 | 5:30 | [link](https://www.bilibili.com/video/BV13XgWzhE4q) |
| 459 | - | - | 《RethinkFun深度学习教程》：8.2 大脑与神经网络 | 5:13 | [link](https://www.bilibili.com/video/BV1RTgWzwEbv) |
| 460 | - | - | 《RethinkFun深度学习教程》：8.3 神经网络与矩阵计算 | 5:09 | [link](https://www.bilibili.com/video/BV1xWgWznEQK) |
| 461 | - | - | 《RethinkFun深度学习教程》：8.4 激活函数 | 4:47 | [link](https://www.bilibili.com/video/BV1y1gpzjEAB) |
| 462 | - | - | 《RethinkFun深度学习教程》：8.5 神经网络的多分类 | 6:43 | [link](https://www.bilibili.com/video/BV1RWgpzhEM2) |
| 463 | - | - | 不用PyTorch，自己动手实现神经网络训练 | 21:48 | [link](https://www.bilibili.com/video/BV1kRbkz2Eyr) |
| 464 | - | - | 《RethinkFun深度学习教程》：8.7 梯度消失梯度爆炸 | 7:14 | [link](https://www.bilibili.com/video/BV1kRbkz2ECU) |
| 465 | - | - | 《RethinkFun深度学习教程》：8.8 手动实现多分类神经网络 | 6:49 | [link](https://www.bilibili.com/video/BV1xab1zFERW) |
| 466 | - | - | 《RethinkFun深度学习教程》：8.9 用PyTorch实现多分类神经网络 | 2:22 | [link](https://www.bilibili.com/video/BV14Yb1zbEwZ) |
| 467 | - | - | 《RethinkFun深度学习教程》：8.10 为什么神经网络可以拟合任意函数 | 8:29 | [link](https://www.bilibili.com/video/BV1E2b1zSECH) |
| 468 | - | - | 《RethinkFun深度学习教程》：9.1 L1和L2正则化 | 6:18 | [link](https://www.bilibili.com/video/BV198bQzRE4q) |
| 469 | - | - | 《RethinkFun深度学习教程》：9.2 指数加权平均 | 6:13 | [link](https://www.bilibili.com/video/BV1XUbDzXEUJ) |
| 470 | - | - | 《RethinkFun深度学习教程》：9.3 动量梯度下降 | 3:52 | [link](https://www.bilibili.com/video/BV1yTbQz6EtT) |
| 471 | - | - | 《RethinkFun深度学习教程》：9.4 RMSProp | 2:35 | [link](https://www.bilibili.com/video/BV1AgbQzzEtE) |
| 472 | - | - | 《RethinkFun深度学习教程》：9.5 Adam优化器 | 2:02 | [link](https://www.bilibili.com/video/BV142b9zQE2X) |
| 473 | - | - | 《RethinkFun深度学习教程》：9.6 权重衰减 | 2:47 | [link](https://www.bilibili.com/video/BV186b9zdEXR) |
| 474 | - | - | 《RethinkFun深度学习教程》：9.7 Dropout | 2:46 | [link](https://www.bilibili.com/video/BV1Yvb9zFEUD) |
| 475 | - | - | 《RethinkFun深度学习教程》：9.8 批量归一化 | 6:49 | [link](https://www.bilibili.com/video/BV1Yvb9zFEet) |
| 476 | - | - | 《RethinkFun深度学习教程》：10.1 计算机视觉问题的特点 | 3:30 | [link](https://www.bilibili.com/video/BV1EU8bzME3z) |
| 477 | - | - | 《RethinkFun深度学习教程》：10.2 卷积操作 | 10:23 | [link](https://www.bilibili.com/video/BV1T88bznEbf) |
| 478 | - | - | 《RethinkFun深度学习教程》：10.3 卷积的进阶操作 | 9:50 | [link](https://www.bilibili.com/video/BV1ik8ez2Euv) |
| 479 | - | - | 《RethinkFun深度学习教程》：10.4 池化层 | 5:43 | [link](https://www.bilibili.com/video/BV1Uj8ezvERH) |
| 480 | - | - | 《RethinkFun深度学习教程》：10.5 一个完整的卷积神经网络 | 6:59 | [link](https://www.bilibili.com/video/BV1QV8iz5En2) |
| 481 | - | - | 《RethinkFun深度学习教程》：10.6 1乘1卷积和全局平均池化层 | 7:16 | [link](https://www.bilibili.com/video/BV18V83zMEMN) |
| 482 | - | - | 《RethinkFun深度学习教程》：10.7 用PyTorch实现卷积神经网络 | 5:56 | [link](https://www.bilibili.com/video/BV1cT8gzWE5E) |
| 483 | - | - | 《RethinkFun深度学习教程》：10.8 图像增强 | 6:56 | [link](https://www.bilibili.com/video/BV1yj8EzJEf2) |
| 484 | - | - | 《RethinkFun深度学习教程》：11.1 LeNet | 4:21 | [link](https://www.bilibili.com/video/BV11F8HzoEKx) |
| 485 | - | - | 《RethinkFun深度学习教程》：11.2 AlexNet | 7:21 | [link](https://www.bilibili.com/video/BV1638HzJEM6) |
| 486 | - | - | 《RethinkFun深度学习教程》：11.3 GoogLeNet | 6:54 | [link](https://www.bilibili.com/video/BV1cM8HzpEen) |
| 487 | - | - | 《RethinkFun深度学习教程》：11.4 VGGNet | 4:04 | [link](https://www.bilibili.com/video/BV1oi8nzVE7b) |
| 488 | - | - | ResNet原理及实现 | 5:15 | [link](https://www.bilibili.com/video/BV13ChwzDEwU) |
| 489 | - | - | 《RethinkFun深度学习教程》：11.6 ResNet实现 | 17:48 | [link](https://www.bilibili.com/video/BV1UUhwzjE4W) |
| 490 | - | - | 什么是迁移学习？ | 9:05 | [link](https://www.bilibili.com/video/BV1UUhwzjEFR) |
| 491 | - | - | 快速了解什么是目标检测 | 11:25 | [link](https://www.bilibili.com/video/BV1b2hwzmEGh) |
| 492 | - | - | 什么是语义分割？ | 8:13 | [link](https://www.bilibili.com/video/BV1Sn8Bz7ER4) |
| 493 | - | - | 《RethinkFun深度学习教程》：11.10 其他应用 | 5:34 | [link](https://www.bilibili.com/video/BV1DE8BzUE1N) |
| 494 | - | - | 《RethinkFun深度学习教程》：12.1 自然语言处理的发展 | 7:59 | [link](https://www.bilibili.com/video/BV15h8qzQEgd) |
| 495 | - | - | 《RethinkFun深度学习教程》：12.2 NLP的常见任务 | 8:33 | [link](https://www.bilibili.com/video/BV1Sf8izCEx5) |
| 496 | - | - | 《RethinkFun深度学习教程》：12.3词典生成 | 8:04 | [link](https://www.bilibili.com/video/BV14J81zwE6c) |
| 497 | - | - | 《RethinkFun深度学习教程》：12.4 Token编码 | 10:42 | [link](https://www.bilibili.com/video/BV1sW81zbENS) |
| 498 | - | - | 《RethinkFun深度学习教程》：12.5 语言模型采样 | 6:13 | [link](https://www.bilibili.com/video/BV1NM8UzTEfV) |
| 499 | - | - | 《RethinkFun深度学习教程》：13.1 RNN | 8:50 | [link](https://www.bilibili.com/video/BV1FJ8UzfEJX) |
| 500 | - | - | 《RethinkFun深度学习教程》：13.2 RNN的不同类型 | 3:27 | [link](https://www.bilibili.com/video/BV1wL8UzaEKg) |
| 501 | - | - | 一次学懂LSTM 长短期记忆网络 | 7:31 | [link](https://www.bilibili.com/video/BV1CahHzfEcD) |
| 502 | - | - | 《RethinkFun深度学习教程》：13.4 GRU | 4:10 | [link](https://www.bilibili.com/video/BV1a5hHz3EAU) |
| 503 | - | - | 《RethinkFun深度学习教程》：13.5 双向循环神经网络 | 2:33 | [link](https://www.bilibili.com/video/BV1RuhHzyEM5) |
| 504 | - | - | 《RethinkFun深度学习教程》：13.6 深度循环神经网络 | 3:20 | [link](https://www.bilibili.com/video/BV1TkhnzPEkV) |
| 505 | - | - | 《RethinkFun深度学习教程》：13.7 注意力机制 | 8:12 | [link](https://www.bilibili.com/video/BV112hnz8E7F) |
| 506 | - | - | 《RethinkFun深度学习教程》：14.1 数据准备 | 6:08 | [link](https://www.bilibili.com/video/BV11dhPzJEUD) |
| 507 | - | - | 《RethinkFun深度学习教程》：14.2 BLEU评价指标 | 9:32 | [link](https://www.bilibili.com/video/BV1XThMzBEQ2) |
| 508 | - | - | 《RethinkFun深度学习教程》：14.3 模型定义 | 13:51 | [link](https://www.bilibili.com/video/BV1b2hVz7EyR) |
| 509 | - | - | 《RethinkFun深度学习教程》：14.4 模型评估 | 4:19 | [link](https://www.bilibili.com/video/BV1yhhGzBEoH) |
| 510 | - | - | 《RethinkFun深度学习教程》：15.1 动机与影响 | 4:49 | [link](https://www.bilibili.com/video/BV1WXtVzaE4g) |
| 511 | - | - | 《RethinkFun深度学习教程》：15.2 注意力机制 | 17:40 | [link](https://www.bilibili.com/video/BV1wZtVzFEhc) |
| 512 | - | - | 《RethinkFun深度学习教程》：15.3 层归一化 | 3:02 | [link](https://www.bilibili.com/video/BV1E5tnzrEtP) |
| 513 | - | - | 《RethinkFun深度学习教程》：15.4 位置编码 | 7:05 | [link](https://www.bilibili.com/video/BV1iztJzvEKZ) |
| 514 | - | - | 《RethinkFun深度学习教程》：15.5 把这一切组装起来 | 11:23 | [link](https://www.bilibili.com/video/BV1VktJzaE35) |
| 515 | - | - | 《RethinkFun深度学习教程》：15.6 利用Transformer实现模型翻译 | 3:09 | [link](https://www.bilibili.com/video/BV1R74dzaE4b) |
| 516 | - | - | 《RethinkFun深度学习教程》：16.1 GPT1 | 8:39 | [link](https://www.bilibili.com/video/BV1R74dzaELB) |
| 517 | - | - | 《RethinkFun深度学习教程》：16.2 BERT | 8:59 | [link](https://www.bilibili.com/video/BV1cP4dzGEyf) |
| 518 | - | - | 《RethinkFun深度学习教程》：16.3 GPT2 | 3:29 | [link](https://www.bilibili.com/video/BV1cP4dzGEoh) |
| 519 | - | - | 《RethinkFun深度学习教程》：16.4 GPT3和GPT4 | 5:11 | [link](https://www.bilibili.com/video/BV1cP4dzGEX5) |
| 520 | - | - | 《RethinkFun深度学习教程》：17.1 Llama1 | 5:12 | [link](https://www.bilibili.com/video/BV1BrtczHEYw) |
| 521 | - | - | 《RethinkFun深度学习教程》：17.2 旋转位置编码 | 9:50 | [link](https://www.bilibili.com/video/BV17rtczHEDc) |
| 522 | - | - | 《RethinkFun深度学习教程》：17.3 Llama2 | 5:23 | [link](https://www.bilibili.com/video/BV17rtczHESw) |
| 523 | - | - | 《RethinkFun深度学习教程》：17.4 Llama3 | 4:40 | [link](https://www.bilibili.com/video/BV17rtczHEk2) |
| 524 | - | - | 《RethinkFun深度学习教程》：18.1 MOE | 11:25 | [link](https://www.bilibili.com/video/BV1i1tczUEgr) |
| 525 | - | - | 《RethinkFun深度学习教程》：18.2 DeepSeekMOE | 6:24 | [link](https://www.bilibili.com/video/BV1v1tczUEUE) |
| 526 | - | - | 《RethinkFun深度学习教程》：18.3 DeepSeekV2 | 16:52 | [link](https://www.bilibili.com/video/BV1j1tczUEMF) |
| 527 | - | - | 《RethinkFun深度学习教程》：18.4 DeepSeekV3 | 14:49 | [link](https://www.bilibili.com/video/BV1i1tczUEao) |
| 528 | - | - | 《RethinkFun深度学习教程》完结！ | 1:24 | [link](https://www.bilibili.com/video/BV13ftAzmEM2) |
| 529 | - | - | VIT （Vision Transformer）深度讲解 | 14:52 | [link](https://www.bilibili.com/video/BV15RDtYqE4r) |
| 530 | - | - | 多模态模型CLIP深度讲解 | 20:10 | [link](https://www.bilibili.com/video/BV1pYmDYgEDW) |
| 531 | - | - | 一次学懂对比学习：MOCO | 14:39 | [link](https://www.bilibili.com/video/BV1dtSuY7Evj) |
| 532 | - | - | 一次学懂多模态算法：ALBEF模型 | 16:52 | [link](https://www.bilibili.com/video/BV1uMUDYnEKu) |
| 533 | - | - | 一次学懂BLIP多模态算法 | 14:52 | [link](https://www.bilibili.com/video/BV1g7BmYHEJn) |
| 534 | - | - | 一次学懂多模态算法：flamingo | 15:25 | [link](https://www.bilibili.com/video/BV1QszNYzE1r) |
| 535 | - | - | 一次学懂多模态算法：BLIP2   BLIP-2 | 10:14 | [link](https://www.bilibili.com/video/BV1bVBRYTEpL) |
| 536 | - | - | 看傻眼！LLaVA多模态模型最简单的模型，最强的效果！LLaVA LLaVA-1.5 LLaVA-NeXT | 15:14 | [link](https://www.bilibili.com/video/BV12PznYuExg) |
| 537 | - | - | LLama 3.2 Vision 多模态大模型原理讲解 | 10:06 | [link](https://www.bilibili.com/video/BV1QrBEY3Eax) |
| 538 | - | - | 大模型预训练看这个视频就够了 | 14:56 | [link](https://www.bilibili.com/video/BV1xhYtewEum) |
| 539 | - | - | 大模型微调看这个视频就够了 SFT NEFTune | 13:23 | [link](https://www.bilibili.com/video/BV1gmWDeLEMZ) |
| 540 | - | - | 零基础学习强化学习算法：ppo | 31:01 | [link](https://www.bilibili.com/video/BV1iz421h7gb) |
| 541 | - | - | 代码实现大模型强化学习(PPO)，看这个视频就够了。 | 23:59 | [link](https://www.bilibili.com/video/BV1rixye7ET6) |
| 542 | - | - | 模型量化一：量化基础 对称量化 非对称量化 极大值量化 零点量化 | 10:35 | [link](https://www.bilibili.com/video/BV1EE42157Ms) |
| 543 | - | - | 模型量化二：训练后动态量化 PTQ PTDQ，pytorch里进行模型训练后动态量化 | 5:27 | [link](https://www.bilibili.com/video/BV1pZ421J7ga) |
| 544 | - | - | 模型量化三：训练后静态量化 PTQ PTSQ pytorch里进行模型训练后静态量化 | 5:31 | [link](https://www.bilibili.com/video/BV17m411C77i) |
| 545 | - | - | 模型量化四：量化感知训练 QAT pytorch里进行量化感知训练 | 2:56 | [link](https://www.bilibili.com/video/BV1pt421w7u4) |
| 546 | - | - | 模型量化五：LLM.int8() Bitsandbytes HuggingFace 默认大模型量化方法 | 6:04 | [link](https://www.bilibili.com/video/BV1mm421p7GD) |
| 547 | - | - | 模型量化六：QLoRA 4bit 量化 NormalFloat4 量化 | 9:05 | [link](https://www.bilibili.com/video/BV15y411a7so) |
| 548 | - | - | 大模型修炼之道(一): Transformer Attention is all you need | 28:02 | [link](https://www.bilibili.com/video/BV1FH4y157ZC) |
| 549 | - | - | 大模型修炼之道(二): GPT系列GPT1，GPT2，GPT3，GPT4 | 17:39 | [link](https://www.bilibili.com/video/BV1ZJ4m1K73s) |
| 550 | - | - | 大模型修炼之道(三): Llama系列讲解 Llama1，Llama2, Llama3 | 15:15 | [link](https://www.bilibili.com/video/BV1Ds421c7JP) |
| 551 | - | - | Pytorch里的register_parameter和register_buffer是干什么的？ | 5:06 | [link](https://www.bilibili.com/video/BV1cr421J7Su) |
| 552 | - | - | MOE的实现-从Top-K到专家路由和Token Dispatch/Combine | 21:03 | [link](https://www.bilibili.com/video/BV1Ehpj6iEnE) |
| 553 | - | - | ai infra购课平台上线了～ | 5:22 | [link](https://www.bilibili.com/video/BV13kvKzrEa9) |
| 554 | - | - | 8月13日-学员会议-从零开始的AI Infra学习规划 | 36:33 | [link](https://www.bilibili.com/video/BV1WSYyzYEiY) |
| 555 | - | - | 一次对ai-infra新学员的规划课 | 36:37 | [link](https://www.bilibili.com/video/BV1TuYqzmEhh) |
| 556 | - | - | AI Infra 2025年秋招经验分享 | 94:31 | [link](https://www.bilibili.com/video/BV17tEvzdE4x) |
| 557 | - | - | 大模型推理加速-AI Infra的简历应该怎么写？ | 3:34 | [link](https://www.bilibili.com/video/BV1S6EyzBEZX) |
| 558 | - | - | AI Infra 2025年暑期实习经验分享 | 112:27 | [link](https://www.bilibili.com/video/BV1pCL6zgEhw) |
| 559 | - | - | AI Infra秋招项目-用CUDA写一个支持qwen3的大模型推理框架 | 7:55 | [link](https://www.bilibili.com/video/BV1jvNnzmEik) |
| 560 | - | - | 如何写一份合格的AI-Infra岗位秋招简历 | 12:08 | [link](https://www.bilibili.com/video/BV1iEpgz8EUE) |
| 561 | - | - | Ai-Infra面试实录—大模型推理框架开发实习岗位 | 53:17 | [link](https://www.bilibili.com/video/BV1VAUKBxEFT) |
| 562 | - | - | 从零开始学Ai-Infra—冲击26年秋招SSP | 44:12 | [link](https://www.bilibili.com/video/BV1gw2WBAE6t) |
| 563 | - | - | AI-Infra规划课—2025年秋招没有offer，怎么准备春招？ | 49:22 | [link](https://www.bilibili.com/video/BV1Ynm9BsEYm) |
| 564 | - | - | AI-Infra规划课—怎么学习算子开发？ | 50:03 | [link](https://www.bilibili.com/video/BV1wXmqBbE8U) |
| 565 | - | - | AI-Infra规划课—怎么关联实习和目标岗位？ | 41:41 | [link](https://www.bilibili.com/video/BV1uiqzBQEd5) |
| 566 | - | - | AI-Infra规划课—选实习offer | 46:48 | [link](https://www.bilibili.com/video/BV13rB4B9ETN) |
| 567 | - | - | AI-Infra规划课—怎么学习大模型推理框架 | 61:15 | [link](https://www.bilibili.com/video/BV1QBv6BHEGZ) |
| 568 | - | - | AI-Infra规划课—acm经历对ai-infra有帮助吗？ | 33:08 | [link](https://www.bilibili.com/video/BV1QLiwB2Emj) |
| 569 | - | - | AI-Infra规划课—芯片/互联网的实习通用吗？ | 79:44 | [link](https://www.bilibili.com/video/BV1XY6UBxELM) |
| 570 | - | - | AI-Infra规划课—怎么从后端转方向和端侧AI部署 | 88:44 | [link](https://www.bilibili.com/video/BV1sprQB9EFb) |
| 571 | - | - | AI-Infra规划课—2026年的SSP被预定了一个 | 10:08 | [link](https://www.bilibili.com/video/BV1ncz1BoEqE) |
| 572 | - | - | AI-Infra规划课—有实力的选手是怎么规划实习的？ | 40:13 | [link](https://www.bilibili.com/video/BV1gT6nB6EPA) |
| 573 | - | - | AI-Infra规划课—实习，比赛，论文和项目全优的一位同学 | 54:24 | [link](https://www.bilibili.com/video/BV1fBFxzpEH3) |
| 574 | - | - | AI-Infra规划课—怎么寻找自己简历中的亮点？ | 61:44 | [link](https://www.bilibili.com/video/BV1Z3ZJBfEyX) |
| 575 | - | - | AI-Infra规划课—留学生Infra岗简历实习研讨 | 31:34 | [link](https://www.bilibili.com/video/BV1HSNczqErh) |
| 576 | - | - | AI-Infra规划课—算子大佬是怎么炼成的 | 45:28 | [link](https://www.bilibili.com/video/BV18dw4z2ENV) |
| 577 | - | - | AI-Infra规划课—当算子实习生比社招同学更优秀的时候 | 62:40 | [link](https://www.bilibili.com/video/BV1LKAAzoEUy) |
| 578 | - | - | AI-Infra规划课—社招转infra岗位改简历 | 56:45 | [link](https://www.bilibili.com/video/BV1iNXjBBEZj) |
| 579 | - | - | AI-Infra规划课—26年4月3日春招规划实录 | 38:19 | [link](https://www.bilibili.com/video/BV1vt9gBpEzD) |
| 580 | - | - | AI-Infra规划课和模拟面—26年4月11日实录 | 86:17 | [link](https://www.bilibili.com/video/BV146DyBhELD) |
| 581 | - | - | AI-Infra规划课和模拟面—vLLM大模型推理优化岗我会怎么面？ | 45:57 | [link](https://www.bilibili.com/video/BV1UndWBHE8G) |
| 582 | - | - | AI-Infra规划课和模拟面—26年4月26日场—算子优化五步法 | 72:52 | [link](https://www.bilibili.com/video/BV1uaofBREJE) |
| 583 | - | - | AI-Infra规划课和模拟面—为vllm omni+vllm贡献者大佬修改简历-2026年5月1日场 | 59:10 | [link](https://www.bilibili.com/video/BV1h1R3BXEsf) |
| 584 | - | - | AI-Infra规划课和模拟面—一位写过高性能算子库的同学——2026年5月9日场 | 20:32 | [link](https://www.bilibili.com/video/BV1cNRdBfEE6) |
| 585 | - | - | AI-Infra规划课和模拟面—博士也愁找工作 | 25:04 | [link](https://www.bilibili.com/video/BV1yqG66pEmt) |
| 586 | - | - | AI-Infra规划课和模拟面—nano-vllm怎么学有竞争力？ | 11:53 | [link](https://www.bilibili.com/video/BV1UbG66ZE86) |
| 587 | - | - | AI-Infra规划课和模拟面—2026年5月30日职业规划实录 | 59:15 | [link](https://www.bilibili.com/video/BV1wTVj6SEhk) |
| 588 | - | - | AI-Infra规划课和模拟面—2026年6月6日-怎么给vLLM提交pr | 71:22 | [link](https://www.bilibili.com/video/BV1zKEp6GEzo) |
| 589 | - | - | AI-Infra规划课和模拟面—2026年6月13日—帮学员简历查漏补缺 | 65:27 | [link](https://www.bilibili.com/video/BV15SJs6yEGq) |
| 590 | - | - | AI-Infra规划课和模拟面—2026年6月20日—帮一位芯片全栈的同学简历突出重点 | 26:55 | [link](https://www.bilibili.com/video/BV1EujH6eExe) |
| 591 | - | - | AI-Infra规划课和模拟面—2026年6月20日—大模型推理端到端是必须掌握的 | 24:18 | [link](https://www.bilibili.com/video/BV1L5jH6cEYo) |
| 592 | - | - | AI-Infra规划课和模拟面—2026年6月27日—秋招推理框架、算子开发与项目打磨指导 | 104:13 | [link](https://www.bilibili.com/video/BV1eu7W6KEda) |
| 593 | - | - | AI-Infra规划课和模拟面—2026年7月4日—研一找到两份实习offer的女生 | 16:47 | [link](https://www.bilibili.com/video/BV1PzMP6rEQH) |
| 594 | - | - | AI-Infra规划课和模拟面—2026年7月11日—大二找到infra实习的同学 | 22:17 | [link](https://www.bilibili.com/video/BV1PVNA6fEAs) |
| 595 | - | - | AI-Infra规划课和模拟面—2026年7月11日—帮学员看简历 | 21:40 | [link](https://www.bilibili.com/video/BV1nBNw6XE47) |
| 596 | - | - | ai infra职业规划-2026年7月18日-学历和实习都顶级拉满的一位同学 | 25:16 | [link](https://www.bilibili.com/video/BV18VKB6zE51) |
| 597 | - | - | ai infra职业规划-2026年7月25日-精通推理优化的一位同学今年秋招 | 34:03 | [link](https://www.bilibili.com/video/BV15q3G6dESU) |
| 598 | - | - | ai infra职业规划-2026年8月2日-保研后的学习规划 | 7:38 | [link](https://www.bilibili.com/video/BV1kN3m6eEpR) |
| 599 | - | - | ai infra职业规划-2026年8月2日-在工作中发现推理加速的需求 | 20:52 | [link](https://www.bilibili.com/video/BV1kT3m6AEWh) |
| 600 | - | - | ai infra职业规划-2026年8月6日-拷打芯片行业的算子岗 | 34:34 | [link](https://www.bilibili.com/video/BV1XpuH6uEjL) |
| 601 | - | - | ai infra职业规划-2026年8月6日-大二去字节实习 | 22:09 | [link](https://www.bilibili.com/video/BV1x2ux6gE5x) |
| 602 | - | - | AI Infra-职业规划：参加2026秋招前大厂同学的职业规划 | 84:22 | [link](https://www.bilibili.com/video/BV1sNu56BEpH) |
| 603 | - | - | ai-infra规划-8月16日-28届实习阶段怎么学习vllm | 28:06 | [link](https://www.bilibili.com/video/BV1QebS6PEie) |
| 604 | - | - | ai-infra规划-8月16日-27届秋招前大家水平怎么样了？ | 35:30 | [link](https://www.bilibili.com/video/BV1XabS6vEnd) |
| 605 | - | - | ai-infra规划-8月22日-27/28届的有实力选手 | 98:44 | [link](https://www.bilibili.com/video/BV1RL8S6gEDT) |
| 606 | - | - | ai-infra规划-8月23日-学员经验-校招半年从infra小白到infra互联网大厂 | 29:07 | [link](https://www.bilibili.com/video/BV1ru8h6aE3e) |
| 607 | - | - | ai-infra规划-8月31日-秋招的算子开发、推理框架与芯片适配，简历项目怎么改？ | 59:30 | [link](https://www.bilibili.com/video/BV1FAtW6qEV3) |
| 608 | - | - | ai-infra规划-9月3日-给vLLM提了几次PR，能靠它冲大模型框架岗吗？ | 45:21 | [link](https://www.bilibili.com/video/BV1YptD6qEyn) |
| 609 | - | - | ai-infra规划-8月22日-做国产gpu适配的同学简历 | 31:45 | [link](https://www.bilibili.com/video/BV1y5to6TEFM) |
| 610 | - | - | ai-infra规划-9月5日-本2硕9-vLLM大模型推理框架简历应该这么改！ | 16:31 | [link](https://www.bilibili.com/video/BV1Fstm6zEyb) |
| 611 | - | - | ai-infra职业规划，2026年9月5日，如何改造自己的kv cache项目 | 20:42 | [link](https://www.bilibili.com/video/BV1cbbW6kEwh) |
| 612 | - | - | ai-infra职业规划，双硕士-hpc科研经历-如何从事cuda算子开发？ | 30:09 | [link](https://www.bilibili.com/video/BV1gSbG6bEh3) |
| 613 | - | - | ai-infra职业规划，从万卡集群调度走向ai-infra大模型推理加速 | 26:11 | [link](https://www.bilibili.com/video/BV15kbG6PEhV) |
| 614 | - | - | ai-infra职业规划，具身智能和互联网怎么选？ | 12:28 | [link](https://www.bilibili.com/video/BV1Vmb56BExL) |
| 615 | - | - | ai-infra职业规划，从集群推理优化科研到大模型推理：如何拿下AI Infra实习？ | 15:27 | [link](https://www.bilibili.com/video/BV1RWbV6NETb) |
| 616 | - | - | ai-infra职业规划，秋招北邮硕士做算子实习，如何转向大模型推理优化？ | 30:04 | [link](https://www.bilibili.com/video/BV1ZBY86eED9) |
| 617 | - | - | ai-infra职业规划，从零开始学习拿到大模型独角兽实习 | 30:19 | [link](https://www.bilibili.com/video/BV1XrY26iEwT) |
| 618 | - | - | ai-infra职业规划，算法转AI-Infra实习规划和Cuda学习 | 15:49 | [link](https://www.bilibili.com/video/BV1tme86HEhK) |
| 619 | - | - | ai-infra职业规划，从CUDA算子到推理框架：两份 AI Infra 简历的项目分析与改进建议 | 40:57 | [link](https://www.bilibili.com/video/BV15Th66UEec) |
| 620 | - | - | ai-infra职业规划：大厂的infra实习生怎么在准备秋招面试？ | 21:39 | [link](https://www.bilibili.com/video/BV1Zaho6iEtc) |
| 621 | - | - | ai-infra职业规划：大三在字节实习的同学又更新了他的简历 | 16:50 | [link](https://www.bilibili.com/video/BV1Dfax66EY1) |
| 622 | - | - | ai-infra职业规划：在顶流芯片公司的实习为什么不被互联网认可？ | 20:41 | [link](https://www.bilibili.com/video/BV1hZax63Eru) |
| 623 | - | - | ai-infra 27届学员秋招分享，今年我是如何拿到10个offer意向的？ | 66:15 | [link](https://www.bilibili.com/video/BV1kjaL6bENg) |
| 624 | - | - | ai-infra职业规划：约面十几家公司，推理岗仍卡项目深度，15天如何冲刺 AI Infra | 25:20 | [link](https://www.bilibili.com/video/BV1EjHi69EvZ) |
| 625 | - | - | ai-infra职业规划：土木老哥一转智驾再转Infra的求职之路 | 21:10 | [link](https://www.bilibili.com/video/BV15uHj6oE44) |
| 626 | - | - | ai-infra职业规划：怎么规划和修改自己的nano-vllm简历让它更出众？ | 28:36 | [link](https://www.bilibili.com/video/BV1FJpG6tE2N) |
| 627 | - | - | vLLM大模型推理框架-分块显存管理 | 15:45 | [link](https://www.bilibili.com/video/BV1WFnzzEEGD) |
| 628 | - | - | vLLM大模型推理框架-kv cache的初始化流程 | 18:32 | [link](https://www.bilibili.com/video/BV1hYHKz6EtE) |
| 629 | - | - | vLLM大模型推理框架-请求和显存块的映射 | 12:47 | [link](https://www.bilibili.com/video/BV1BY4VzHE4Z) |
| 630 | - | - | vLLM源码全流程分析—vLLM引擎架构与流式推理 | 67:39 | [link](https://www.bilibili.com/video/BV14zsozJE5B) |
| 631 | - | - | vLLM源码全流程分析—vLLM Worker和Executor组件的协作 | 39:01 | [link](https://www.bilibili.com/video/BV1db1LBmEpL) |
| 632 | - | - | vLLM 显存分块管理—PageAttention 的基石 | 33:23 | [link](https://www.bilibili.com/video/BV1n9rEBWEFK) |
| 633 | - | - | vLLM技术分享以及大模型推理框架学习、工作答疑 | 166:03 | [link](https://www.bilibili.com/video/BV1FCLV6LEsu) |
| 634 | - | - | SGLang 与 vLLM 深度对比：从 KV Cache 到调度架构 | 68:18 | [link](https://www.bilibili.com/video/BV1QxYB6yE2D) |
| 635 | - | - | sglang大模型推理框架-cuda graph从piecewise到breakable | 48:59 | [link](https://www.bilibili.com/video/BV1WzaT6rEGi) |
| 636 | - | - | sglang大模型推理框架-sglang中的triton编译技术 | 47:34 | [link](https://www.bilibili.com/video/BV1Zmat6dEeX) |
| 637 | - | - | sglang大模型推理框架-一个请求的端到端流程和生命周期 | 19:41 | [link](https://www.bilibili.com/video/BV1wraz6hEG3) |
| 638 | - | - | 从零自制深度学习推理框架：第一讲 项目预览和环境配置 | 34:17 | [link](https://www.bilibili.com/video/BV13UaczHEwf) |
| 639 | - | - | 从零自制深度学习推理框架：第二讲 张量(Tensor)的设计与实现 | 62:05 | [link](https://www.bilibili.com/video/BV1hUaczHE4e) |
| 640 | - | - | 从零自制深度学习推理框架：第三讲 计算图的定义 | 54:50 | [link](https://www.bilibili.com/video/BV1mdacz2EHq) |
| 641 | - | - | 从零自制深度学习推理框架：第四讲 构建计算图关系和执行顺序 | 51:23 | [link](https://www.bilibili.com/video/BV1DUacznEmu) |
| 642 | - | - | 从零自制深度学习推理框架：第五讲 KuiperInfer中的算⼦和注册⼯⼚ | 55:26 | [link](https://www.bilibili.com/video/BV1DUacznEL7) |
| 643 | - | - | 从零自制深度学习推理框架：第六讲 卷积和池化算子的实现 | 71:10 | [link](https://www.bilibili.com/video/BV1DUacznEsS) |
| 644 | - | - | 从零自制深度学习推理框架：第七讲 表达式层中词法分析和语法分析以及算子的实现 | 46:50 | [link](https://www.bilibili.com/video/BV1DUacznEbX) |
| 645 | - | - | 从零自制深度学习推理框架：第八讲 动手支持Resnet网络的推理 | 31:22 | [link](https://www.bilibili.com/video/BV1hUaczHEV6) |
| 646 | - | - | 从零自制深度学习推理框架：第九讲 自制一个支持yolov5的推理框架 | 41:22 | [link](https://www.bilibili.com/video/BV1hUaczHE4i) |
| 647 | - | - | AI-Infra必备Cuda入门课程-Transpose优化和Bank冲突处理 | 20:59 | [link](https://www.bilibili.com/video/BV1wtbjzgEBB) |
| 648 | - | - | AI-Infra必备Cuda入门课程-Matmul优化初步 | 54:47 | [link](https://www.bilibili.com/video/BV1ZithzTE5x) |
| 649 | - | - | AI-Infra必备Cuda入门课程-Softmax的实现与优化 | 68:38 | [link](https://www.bilibili.com/video/BV11Q8DzyE21) |
| 650 | - | - | AI-Infra必备Cuda入门课程-Reduce算子的实现 | 43:09 | [link](https://www.bilibili.com/video/BV13baszpESw) |
| 651 | - | - | Triton自制多模态大模型推理框架-用Triton写FlashAttention | 49:35 | [link](https://www.bilibili.com/video/BV1j59tY1EFt) |
| 652 | - | - | Triton自制多模态大模型推理框架-用Triton写出高性能的matmul | 31:39 | [link](https://www.bilibili.com/video/BV1SfAmeUECV) |
| 653 | - | - | Triton自制多模态大模型推理框架-Triton介绍和逐级编译流程 | 51:01 | [link](https://www.bilibili.com/video/BV1HCAMe4E5Y) |
| 654 | - | - | 限时试看-使用OpenAI Triton实现Softmax算子 | 13:15 | [link](https://www.bilibili.com/video/BV1KKZBYiEDj) |
| 655 | - | - | Triton自制大模型推理框架—大模型推理优化综述 | 154:38 | [link](https://www.bilibili.com/video/BV11oRWYWEmW) |
| 656 | - | - | AI Infra入门-使用OpenAI Triton实现Reduce算子 | 26:22 | [link](https://www.bilibili.com/video/BV1kaRzYdEsr) |
| 657 | - | - | 零基础入门ai infra的救星，自制深度学习推理框架出书了 | 1:18 | [link](https://www.bilibili.com/video/BV1MAZBYBELQ) |
| 658 | - | - | AI Infra秋招项目-OpenAI Triton自制深度学习推理框架发布了 | 13:40 | [link](https://www.bilibili.com/video/BV17QNhz2ESk) |
| 659 | - | - | 秋招巅峰项目：OpenAI Triton自制多模态推理框架，FlashAttention原理与实战 | 24:05 | [link](https://www.bilibili.com/video/BV1Jy3wznESs) |
| 660 | - | - | Cuda从零学-秋招转行拿高薪-从零自制大模型推理框架 | 20:05 | [link](https://www.bilibili.com/video/BV1hT421Y7mi) |
| 661 | - | - | 自制大模型推理框架-使用Nsight compute对Cuda算子调优 | 35:24 | [link](https://www.bilibili.com/video/BV1WS411w7g7) |
| 662 | - | - | 秋招项目-从零自制大模型推理框架-张量类的设计 | 8:01 | [link](https://www.bilibili.com/video/BV1dH4y1F735) |
| 663 | - | - | 秋招项目-从零自制大模型推理框架-算子类的设计 | 5:01 | [link](https://www.bilibili.com/video/BV18y411q71J) |
| 664 | - | - | 试看马上删-从零自制大模型推理框架，内存和显存资源是怎么被管理的。 | 5:01 | [link](https://www.bilibili.com/video/BV1is421T7Vq) |
| 665 | - | - | 从零自制大模型推理框架，一个靠谱的C++程序员是怎么练成的。 | 8:35 | [link](https://www.bilibili.com/video/BV1ji421e7MN) |
| 666 | - | - | 自制Cuda大模型推理框架-讲解一个从零手写的Qwen2.5推理 | 47:30 | [link](https://www.bilibili.com/video/BV1q2mTYrEqM) |
| 667 | - | - | 秋招看过来！自制大模型推理框架项目-sofmax算子的cuda实现 | 22:13 | [link](https://www.bilibili.com/video/BV1vZsyeuEz1) |
| 668 | - | - | 秋招看过来！自制大模型推理框架项目-动手实现LLama模型中的多头注意力机制 | 27:19 | [link](https://www.bilibili.com/video/BV17d4fe9Ep6) |
| 669 | - | - | 秋招看过来！自制大模型推理框架-怎么用Cuda实现LLama模型中的MLP层 | 26:09 | [link](https://www.bilibili.com/video/BV1uRnRe7EFQ) |
| 670 | - | - | 自制大模型推理框架-KVCache动手实现-原理篇 | 37:16 | [link](https://www.bilibili.com/video/BV1GmpZeiEB7) |
| 671 | - | - | 秋招好项目-《动手自制大模型推理框架》-算子的创建和权重的载入 | 14:27 | [link](https://www.bilibili.com/video/BV1bRveeoEPW) |
| 672 | - | - | 秋招、转行必备-动手自制大模型推理框架-CUDA显存管理 | 15:04 | [link](https://www.bilibili.com/video/BV142421Z7r3) |
| 673 | - | - | 自制大模型推理框架-Cuda算子再优化和NVCompute分析性能 | 25:21 | [link](https://www.bilibili.com/video/BV1Qx4y1t7jF) |
| 674 | - | - | 自制大模型推理框架-支持大模型int8分组量化 | 26:02 | [link](https://www.bilibili.com/video/BV1RM4m117Bj) |
| 675 | - | - | 自制Cuda大模型推理框架-算子类的实现 | 26:55 | [link](https://www.bilibili.com/video/BV1jXDTYEEEP) |
| 676 | - | - | 自制Cuda大模型推理框架-张量的实现和显存的管理 | 15:23 | [link](https://www.bilibili.com/video/BV1hsU7Y8EhP) |
| 677 | - | - | 自制Cuda大模型推理框架-RMSNorm的Cuda实现 | 18:42 | [link](https://www.bilibili.com/video/BV198znYnE7X) |
| 678 | - | - | 《自制深度学习推理框架》gemv算子的量化实现 | 18:09 | [link](https://www.bilibili.com/video/BV1FK6aYhEhB) |
| 679 | - | - | 《自制深度学习推理框架》新书预告！从理论到实践，打造你的AI推理引擎 | 10:23 | [link](https://www.bilibili.com/video/BV1ZPkhYfEt2) |
| 680 | - | - | 自制Cuda大模型推理框架-int8量化的实现 | 29:07 | [link](https://www.bilibili.com/video/BV1HdqJYoEj6) |
| 681 | - | - | 秋招巅峰项目：手写工业级LLM推理系统-CUDA加速Qwen-3全流程实现 | 12:37 | [link](https://www.bilibili.com/video/BV1zzNmzfEnF) |
| 682 | - | - | 《自制深度学习推理框架》配套视频-第一章环境的安装 | 27:40 | [link](https://www.bilibili.com/video/BV1oycGesEpj) |
| 683 | - | - | 《自制深度学习推理框架》-第二章张量的设计 | 41:00 | [link](https://www.bilibili.com/video/BV1T7wNe9EpK) |
| 684 | - | - | 《自制深度学习推理框架》-第三章-计算图的设计 | 37:36 | [link](https://www.bilibili.com/video/BV1sPfhYmEmx) |
| 685 | - | - | 《自制深度学习推理框架》-第四章-构建计算图 | 27:29 | [link](https://www.bilibili.com/video/BV1HKAYefEoQ) |
| 686 | - | - | 《自制深度学习推理框架》-第5章算子注册器的实现 | 31:19 | [link](https://www.bilibili.com/video/BV1w6RaYMEWh) |
| 687 | - | - | 从KuiperInfer出发谈一些工程开发经验 | 56:12 | [link](https://www.bilibili.com/video/BV1Ga4y1V7gF) |
| 688 | - | - | 自制深度学习推理框架-最终章-用自制的推理框架支持Yolov5模型的推理 | 48:53 | [link](https://www.bilibili.com/video/BV1xs4y1J7t2) |
| 689 | - | - | 自制深度学习推理框架-第13课-用我们自制的推理框架完成ResNet网络的推理和图片的分类 | 45:16 | [link](https://www.bilibili.com/video/BV1jD4y1M772) |
| 690 | - | - | 自制深度学习推理框架-第十二节-算子的执行流程 | 38:29 | [link](https://www.bilibili.com/video/BV1wY411C7Kv) |
| 691 | - | - | 自制深度学习推理框架-第十一节-再探Tensor类，构建计算图的图关系以及对算子的输入输出预分配 | 46:08 | [link](https://www.bilibili.com/video/BV1M54y1K7AG) |
| 692 | - | - | 自制深度学习推理框架-第10节-卷积算子的实现和im2col加速计算的原理 | 43:32 | [link](https://www.bilibili.com/video/BV1F841137Ct) |
| 693 | - | - | 自制深度学习推理框架-对计算图知识的补充 | 19:51 | [link](https://www.bilibili.com/video/BV18d4y1H7Tf) |
| 694 | - | - | 自制深度学习推理框架-第8.2节-计算图中的表达式下 | 20:48 | [link](https://www.bilibili.com/video/BV1cT411f7pJ) |
| 695 | - | - | 自制深度学习推理框架-第8.1节-计算图中的表达式上 | 38:25 | [link](https://www.bilibili.com/video/BV1HY4y1Z7S3) |
| 696 | - | - | 自制深度学习推理框架-第七课-构建自己的计算图 | 65:47 | [link](https://www.bilibili.com/video/BV1VW4y1V7vp) |
| 697 | - | - | Milestone里程碑，记录我们的自制框架KuiperInfer完美支持Yolov5n推理的一刻 | 6:00 | [link](https://www.bilibili.com/video/BV1t24y1i7cu) |
| 698 | - | - | 自制深度学习推理框架-第六课-MaxPooling算子的实现 | 32:18 | [link](https://www.bilibili.com/video/BV1m3411S7yy) |
| 699 | - | - | 自制深度学习推理框架-第五课-起飞！框架中的算子注册机制 | 30:35 | [link](https://www.bilibili.com/video/BV1Q24y1m7jR) |
| 700 | - | - | 自制深度学习推理框架-起飞！实现我们的第一个算子Relu-第四课 | 27:14 | [link](https://www.bilibili.com/video/BV1bG4y1J7sQ) |
| 701 | - | - | 自制深度学习推理框架-从CSV文件初始化Tensor张量-第三课 | 17:25 | [link](https://www.bilibili.com/video/BV1Pg411J7V5) |
| 702 | - | - | 自制深度学习推理框架-张量类Tensor的实现-第二课 | 32:21 | [link](https://www.bilibili.com/video/BV1Ed4y1v7Gb) |
| 703 | - | - | 自制深度学习推理框架-前言-第一课 | 27:28 | [link](https://www.bilibili.com/video/BV1HV4y1A7H8) |
| 704 | - | - | 比大模型快193倍、便宜444倍，TypeSafe Jev到底怎么做到的?｜ AI大模型｜AI Agent｜智能体 | 22:21 | [link](https://www.bilibili.com/video/BV1umah6WEqj) |
| 705 | - | - | AI 说“90% 有把握”，你敢让 Agent 自动执行吗？｜Jev：概率校准与 Agent 决策 | 13:50 | [link](https://www.bilibili.com/video/BV134ph6vEmV) |
| 706 | - | - | 《Agent Loop》给AI Agent的一首嘻哈主题曲｜AI工程师跨界做说唱，连动画MV都配齐了【AI MV大赛】 | 4:00 | [link](https://www.bilibili.com/video/BV1QLpw6JE6c) |
| 707 | - | - | AI Agent 的底层其实就是一个 while 循环？Agent Loop 核心机制完整讲解 | 10:39 | [link](https://www.bilibili.com/video/BV1SGTv6iEmZ) |
| 708 | - | - | AI Agent 为什么会“失忆”？因为上下文才是第一约束｜Agent 工程｜大模型Agent｜Agent Loop | 10:31 | [link](https://www.bilibili.com/video/BV1DsTn6wEB6) |
| 709 | - | - | AI Agent 为什么停不下来？从 ReAct 到 Copilot，看懂 Agent Loop 终止机制｜AI Agent 的终止机制详解 | 9:35 | [link](https://www.bilibili.com/video/BV14mTb6EEQz) |
| 710 | - | - | Loop Engineering：从 Prompt 到 Agent 循环的范式迁移｜AI Agent 的下一层能力，不是写提示词，而是设计循环 | 11:16 | [link](https://www.bilibili.com/video/BV1rmT16pEfj) |
| 711 | - | - | Agent Loop 即 RL Rollout？从产品循环到强化学习轨迹：理解 Agent RL 的关键入口，AI Agent 训练数据生成机制详解 | 10:39 | [link](https://www.bilibili.com/video/BV1DUTd6aEyv) |
| 712 | - | - | AI会做奥数，却端不稳一杯水：具身智能到底难在哪？ | 8:35 | [link](https://www.bilibili.com/video/BV1nRtn6PEwk) |
| 713 | - | - | 会后空翻的机器人，到底是怎么练出来的？你必须了解的从经典控制到强化学习｜AI Agent｜AI 智能体｜大模型强化学习 | 8:47 | [link](https://www.bilibili.com/video/BV1eQtG6PEqm) |
| 714 | - | - | 机器人到底怎么学会干活？从模仿学习到具身智能的数据瓶颈 | 8:53 | [link](https://www.bilibili.com/video/BV1bDYt6mEDz) |
| 715 | - | - | 一双灵巧手，为什么能卡住整台人形机器人？｜具身智能｜世界模型｜机器人 | 9:05 | [link](https://www.bilibili.com/video/BV12naW6ZENU) |
| 716 | - | - | 机器人的 GPT 时刻到了？VLA 大模型离真正好用还有多远｜具身智能｜AI Agent｜强化学习｜大模型 | 12:30 | [link](https://www.bilibili.com/video/BV1UqHL6UEQr) |
| 717 | - | - | DeepSeek V4.1：40层注意力，为什么只存4份KV？｜KV Cache优化详解｜Agent长上下文优化 | 14:46 | [link](https://www.bilibili.com/video/BV1Z5e56ZEmq) |
| 718 | - | - | DeepSeek V4.1：CED架构与KV Cache优化详解 | 12:03 | [link](https://www.bilibili.com/video/BV1xLe36hE65) |
| 719 | - | - | DeepSeek Harness：连 Agent Loop 本身都是插件，凭什么？揭秘智能体Runtime设计 | 12:29 | [link](https://www.bilibili.com/video/BV1cJb96cEg2) |
| 720 | - | - | 硬核解读 DeepSeek DSpark： 大模型推理快 60%-85%，投机解码的新天花板 | 14:15 | [link](https://www.bilibili.com/video/BV14fTc6TEj7) |
| 721 | - | - | DeepSeek多模态凭什么把GPT 5.4拉开：4000万样本+三层奖励+OPD蒸馏，把"框和点"喂进推理链的完整训练秘方 | 13:56 | [link](https://www.bilibili.com/video/BV1YXLp6FE8V) |
| 722 | - | - | 多模态模型的真正瓶颈不是"看不清"，而是"指不准"？｜DeepSeek 视觉原语论文从架构到 7056× 压缩链路全解析 | 11:14 | [link](https://www.bilibili.com/video/BV15j5u6WE5C) |
| 723 | - | - | DeepSeek V4 硬核全面拆解｜1.6万亿参数+百万级上下文+33万亿token同时不崩，CSA、mHC、Muon、OPD四大核心模块逐条拆解 | 17:09 | [link](https://www.bilibili.com/video/BV153oRBXEsG) |
| 724 | - | - | DeepSeek Engram：用"查字典"打败Transformer，推理能力反而涨了5分？ | 11:32 | [link](https://www.bilibili.com/video/BV1hLwMzwEVx) |
| 725 | - | - | DeepSeek-OCR项目导学 | 2:04 | [link](https://www.bilibili.com/video/BV1YLrZBXEMA) |
| 726 | - | - | DeepSeek系统工程优化导学 | 4:39 | [link](https://www.bilibili.com/video/BV1GLrZBXEmo) |
| 727 | - | - | DeepSeek与大模型技术演进 | 12:25 | [link](https://www.bilibili.com/video/BV1QErZBDEHa) |
| 728 | - | - | DeepSeek架构革新 MLA多头潜在注意力 | 2:15 | [link](https://www.bilibili.com/video/BV1hErZBDEzH) |
| 729 | - | - | 我开源了一个本地 AI 阅读器：EPUB/PDF 翻译、摘要、问答，Docker 一键部署｜FolioPaw 阅读猫 | 7:03 | [link](https://www.bilibili.com/video/BV1ZH8Z6MERd) |
| 730 | - | - | 99美元、24小时预售260万美元：这只“小黄鸭”为什么重要？ | 1:20 | [link](https://www.bilibili.com/video/BV1pktD69E9P) |
| 731 | - | - | MIT最新发现：Agent 泛化能力不在模型，而在 Harness！RLM重新定义大模型后训练 | 13:06 | [link](https://www.bilibili.com/video/BV1EGuZ6XEQC) |
| 732 | - | - | 让AI学会“存档”！Kimi K3的5122万个Agent沙箱揭秘：Agent强化学习基础设施到底有多复杂？ | 10:40 | [link](https://www.bilibili.com/video/BV1iXuH6UEd5) |
| 733 | - | - | Agent 的"世界模型"到底是什么? 从第一性原理，讲透它为什么总在同一个坑里栽倒｜AI Agent 深度解析 | 15:38 | [link](https://www.bilibili.com/video/BV1AmNH6EENf) |
| 734 | - | - | Agent 的真正瓶颈不是模型，而是这层 Agent Harness / HarnessX 全景解读 | 18:09 | [link](https://www.bilibili.com/video/BV1Lxj86RECd) |
| 735 | - | - | 刚发布几天就被美国政府紧急叫停:Claude 最强模型 Fable 5 / Mythos 到底强在哪? | 19:20 | [link](https://www.bilibili.com/video/BV1yyjN6vEZz) |
| 736 | - | - | 大模型强化学习一次讲透：RLHF、DPO、GRPO、RLVR 到底怎么选？ | 15:16 | [link](https://www.bilibili.com/video/BV1g2E26AEPD) |
| 737 | - | - | 同样100万Token，为什么有的模型贵30倍？大模型 API 到底在卖什么？一口气讲透 Token 成本、KV Cache 和缓存机制 | 18:45 | [link](https://www.bilibili.com/video/BV1e17y6wEy5) |
| 738 | - | - | 大模型到底是怎么思考的？是在读文字，还是在算向量？一期讲透 Token Space 和 Latent Space | 20:42 | [link](https://www.bilibili.com/video/BV1ABRyBqEoR) |
| 739 | - | - | RAG vs GraphRAG vs LLM Wiki 一次讲透：Karpathy引爆的LLM Wiki，是知识工程的下一次革命，还是又一个被高估的"自我进化" | 20:25 | [link](https://www.bilibili.com/video/BV1NG9xBUEju) |
| 740 | - | - | Claude Code源码曝光 底层技术硬核拆解：1884个文件背后，Anthropic如何构建Agent Runtime？ | 17:23 | [link](https://www.bilibili.com/video/BV1zR9JBREua) |
| 741 | - | - | 为什么你的Agent总翻车？Harness Engineering全拆解：Anthropic、OpenAI、DeepMind都在押注的Agent Runtime | 22:36 | [link](https://www.bilibili.com/video/BV1VBX9BrEon) |
| 742 | - | - | 0基础看懂多模态AI：架构三件套、数据工程、思维链到RAG，一期讲透 | 16:59 | [link](https://www.bilibili.com/video/BV1ywXsBkEDS) |
| 743 | - | - | 2026 AI Agent框架终极指南：从入门到生产部署的选型地图，10大框架五大范式，一期全讲透 | 17:14 | [link](https://www.bilibili.com/video/BV1SqAVzLEci) |
| 744 | - | - | 从RAG到Deep Research：单轮检索vs自主研究Agent，GRPO训练、混合检索、记忆管理怎么选？10篇论文带你看清RAG之后的下一代检索架构 | 13:47 | [link](https://www.bilibili.com/video/BV1GAwmzCEB4) |
| 745 | - | - | AI Agent终于能边用边学了？MemRL这篇论文太有工程价值了！MemRL给出新解法，提出无参数化Runtime Learning | 6:14 | [link](https://www.bilibili.com/video/BV18twWzuELh) |
| 746 | - | - | 多模态推理模型不一定要堆规模，微软Phi-4-reasoning-vision-15B的另一条路 | 8:49 | [link](https://www.bilibili.com/video/BV1X4PQz8EW8) |
| 747 | - | - | RNN不再“金鱼记忆”！一篇论文讲透Memory Caching，Mamba长上下文终于能打了 | 8:59 | [link](https://www.bilibili.com/video/BV1GHP4zZESk) |
| 748 | - | - | Agent 总犯同样的错？SKILLRL技能增强强化学习：把失败轨迹蒸馏成技能库，胜率硬拉 12%+！冷启动微调 + 验证驱动进化 | 9:00 | [link](https://www.bilibili.com/video/BV1kHPqzqEJh) |
| 749 | - | - | ARLArena：4B小模型用SAMPO训练，Agent任务成功率碾压GPT-5.2 | 8:12 | [link](https://www.bilibili.com/video/BV1vcPEzuERE) |
| 750 | - | - | Qwen 3.5 为何爆火？ 从架构到应用：MoE、混合注意力、Agent 工作流一次讲透 | 15:52 | [link](https://www.bilibili.com/video/BV1BCZBBSEJj) |
| 751 | - | - | 多模态大模型视频理解加速｜VideoAuto-R1：GRPO 强化学习 + 置信度，实现动态推理与Early Exit｜让视频推理又快又准 | 35:11 | [link](https://www.bilibili.com/video/BV1h7zFBEEFA) |
| 752 | - | - | 多模态视频理解怎么落地？学完这期，你就能独立部署一个多模态视频大模型服务：VideoAuto-R1 部署实战，把多模态视频大模型真正“上线”！ | 14:04 | [link](https://www.bilibili.com/video/BV1Pez1BNEqA) |
| 753 | - | - | 智谱GLM-TTS本地部署全流程：模型下载 + 推理跑通 + 多GPU批量生成 含音素控制｜命令行/批量推理/Gradio可视化｜语音克隆 | 25:48 | [link](https://www.bilibili.com/video/BV1wjqaBpESg) |
| 754 | - | - | 【ThinkMorph 论文精讲】多模态交错思维链的三大涌现能力！跨模态推理的未来方向 Interleaved CoT 详解｜AI大模型｜多模态大模型 | 24:33 | [link](https://www.bilibili.com/video/BV1SFCqBFEfC) |
| 755 | - | - | KIMI K2 Thinking 深度解析：从万亿MoE到智能体时代的架构革命｜超越DeepSeek的思考模型｜MoonshotAI｜AI Agent | 26:36 | [link](https://www.bilibili.com/video/BV1sJCnBGESj) |
| 756 | - | - | 从CoT到Soft Thinking LLM推理效率优化实战｜多路径推理+早停机制+参数配置全流程 / 大模型推理｜AI大模型教程｜CoT思维链 / 实战案例 | 18:53 | [link](https://www.bilibili.com/video/BV1TBT4zoE1b) |
| 757 | - | - | LLM推理新范式 Soft Thinking理论原理 离散Token局限+连续概念空间+Cold Stop机制解析｜AI大模型教程｜AI前沿技术｜大模型推理 | 21:22 | [link](https://www.bilibili.com/video/BV1UvjzzSEKU) |
| 758 | - | - | 多模态大模型Phi-4 微软首个多模态语言模型 将语音、视觉、文本处理集成到一个统一架构 模型详解｜模型架构｜模型训练Pipeline | 12:18 | [link](https://www.bilibili.com/video/BV1dY9BYVECo) |
| 759 | - | - | 微软Phi4多模态模型本地推理 8个demo案例演示 文本生成｜图像理解｜音频理解｜多轮对话｜Phi4多模态大模型案例实战 | 21:35 | [link](https://www.bilibili.com/video/BV1DDRNY1EeN) |
| 760 | - | - | 月之暗面发布面向大模型的MoBA（混合块注意力）架构 结合MoE和稀疏注意力 算法原理详解 / Transformer / Attention / LLM | 18:56 | [link](https://www.bilibili.com/video/BV1gkPieREDw) |
| 761 | - | - | 英伟达发布MM-Embed：融合文本和图像的跨模态信息检索新模型 | 28:50 | [link](https://www.bilibili.com/video/BV163mfY4Ecg) |
| 762 | - | - | 北大发布多模态大模型LLaVA-o1（已更名为LLaVA-CoT）推理计算Scaling新思路 | 21:55 | [link](https://www.bilibili.com/video/BV1TfUpYkEQg) |
| 763 | - | - | Google发表最新推理Scaling研究，从DRAG到IterDRAG，大模型RAG性能更上一层楼 | 33:31 | [link](https://www.bilibili.com/video/BV1gFBtYwEMG) |
| 764 | - | - | 探索OpenAI o1模型系列：推理能力的全新进展 | 33:39 | [link](https://www.bilibili.com/video/BV1GYbFepEhQ) |
| 765 | - | - | Agent为什么难落地？企业级AI Agent落地的5大核心挑战与解决方案｜腾讯、阿里、百度企业级实践深度拆解 | 19:24 | [link](https://www.bilibili.com/video/BV1P3gs6uEbJ) |
| 766 | - | - | 你的 Agent 为什么一上线就翻车？模型不是瓶颈，Harness 才是关键！深入理解 Model + Harness 工程架构 | 9:43 | [link](https://www.bilibili.com/video/BV1te8J62ETV) |
| 767 | - | - | 企业级 Agent 落地方法论：模型太慢、调用太贵、动作太险，高频业务里的Agent该怎么用？ | 9:56 | [link](https://www.bilibili.com/video/BV12u8z6eEax) |
| 768 | - | - | AI Agent 安全核心：如何给大模型分级授权？三层权限体系详解：分级授权、凭证隔离、签名许可｜企业级 Agent 落地方法论 | 9:37 | [link](https://www.bilibili.com/video/BV1kf8t6hEH8) |
| 769 | - | - | AI Agent会“作弊”？测试全通过，也可能根本没完成任务｜企业级 Agent 落地方法论｜AI Agent｜智能体教程 | 11:04 | [link](https://www.bilibili.com/video/BV1kch56oERd) |
| 770 | - | - | 模型再强也救不了 Agent：语义和记忆才是真正的瓶颈｜AI Agent｜AI 大模型｜Agent 记忆 | 11:24 | [link](https://www.bilibili.com/video/BV1ueta67Efx) |
| 771 | - | - | Claude Code 为什么不会撑爆上下文？深入解析 Agent 上下文压缩与会话恢复机制｜上下文投影、压缩、缓存与会话恢复全过程 | 14:35 | [link](https://www.bilibili.com/video/BV1nJ396JEmC) |
| 772 | - | - | Hermes Agent 记忆架构详解｜四层记忆系统如何持久化？长期事实、完整历史、外部recall，一次讲透 | 22:51 | [link](https://www.bilibili.com/video/BV17KoFBBEqM) |
| 773 | - | - | Agent记忆框架怎么选？5大Agent Memory项目工程级横向对比，哪一种才是未来Agent记忆的标准答案 | 15:11 | [link](https://www.bilibili.com/video/BV1p2DyB4Ee3) |
| 774 | - | - | Agent记忆系统深度拆解（下）｜MemOS / OpenViking / Hindsight / Second Me / MetaMem 五大开源架构全景对比 | 24:57 | [link](https://www.bilibili.com/video/BV1orQJB2Edt) |
| 775 | - | - | Claude Code 的记忆机制到底强在哪？六维记忆体系深度解析，一节视频讲透指令记忆、长期记忆、Session Memory 与 AutoDream | 24:31 | [link](https://www.bilibili.com/video/BV1z6SXBzEYh) |
| 776 | - | - | Agent 持续学习到底是什么？为什么它用一百次，还像第一次？ | 9:05 | [link](https://www.bilibili.com/video/BV13kKV6CEC7) |
| 777 | - | - | Agent记忆越多越聪明？恰恰相反：真正关键的是这4个动作｜写入、巩固、检索、遗忘的第一性原理｜Agent Continual Learning｜智能体持续学习 | 9:02 | [link](https://www.bilibili.com/video/BV1opKr6FEBC) |
| 778 | - | - | 为什么 Agent 不能照搬过去的经验？七要素定义一个合格 Agent Skill｜Agent Continual Learning 系列课程 | 7:52 | [link](https://www.bilibili.com/video/BV1CYKY6nEok) |
| 779 | - | - | Agent 如何持续学习？什么时候必须改模型权重？深入理解 AI Agent 的记忆、Skill 与模型参数更新机制｜Agent 持续学习的四层路由法则 | 8:15 | [link](https://www.bilibili.com/video/BV1ebg16jELx) |
| 780 | - | - | 给 Agent 加 Memory 真的会变聪明吗？深入解析 AI 持续学习系统设计｜Agent Continual Learning｜AI Agent｜智能体 | 8:24 | [link](https://www.bilibili.com/video/BV1kvgx66EZi) |
| 781 | - | - | OpenClaw 开源生态全景解读：14 个 AI Agent 项目，从 56 万行到 888KB | 12:29 | [link](https://www.bilibili.com/video/BV1KpNPzQEZs) |
| 782 | - | - | OpenClaw生态16个开源项目深度拆解： AI Agent之间怎么组队协作？从Agent协作到5美元芯片（第二期） | 29:18 | [link](https://www.bilibili.com/video/BV1o8QoBSEFF) |
| 783 | - | - | OpenClaw 任务调度系统是怎么设计的？如何编排 Agent 的定时任务？ | 9:49 | [link](https://www.bilibili.com/video/BV1UZcCzxEM5) |
| 784 | - | - | 拆解 OpenClaw Agent Runtime：工业级 AI Agent 执行引擎到底怎么跑起来的？ | 6:58 | [link](https://www.bilibili.com/video/BV1NWPTzRE7w) |
| 785 | - | - | OpenClaw Gateway如何让 AI Agent 稳定运转，AI助手同时接入多个平台，消息怎么调度？ | 5:04 | [link](https://www.bilibili.com/video/BV1GDA2z1Eh5) |
| 786 | - | - | 让AI拥有记忆：拆解OpenClaw开源记忆系统的架构设计｜BM25+向量混合搜索、时间衰减、降级容错 | 5:58 | [link](https://www.bilibili.com/video/BV1C5fiBREUu) |
| 787 | - | - | Agent为什么能用强化学习训练？5分钟讲清马尔可夫决策过程MDP｜强化学习基础 | 8:15 | [link](https://www.bilibili.com/video/BV16wAEzyEi5) |
| 788 | - | - | AI Agent进入强化学习时代！微软Agent Lightning到底解决了什么问题？ | 10:56 | [link](https://www.bilibili.com/video/BV1GzwezrEXg) |
| 789 | - | - | GAIA最强Agent实战：从0到1做可落地Agent｜AWorld+MCP架构全拆解｜多模态工具链+自动评测+WebUI/CLI一套跑通｜智能体｜AI大模型 | 19:22 | [link](https://www.bilibili.com/video/BV1k2fDBFExy) |
| 790 | - | - | 【DeepSeek系列】DeepSeek R1 + Ollama + OpenWebUI 本地化部署 交互页面展示｜DeepSeek教程 | 1:17 | [link](https://www.bilibili.com/video/BV1LiEjzBE64) |
| 791 | - | - | 【DeepSeek系列】DeepSeek R1 本地化部署流程：模型显卡需求｜Ollama安装｜运行DeepSeek R1模型的3种方式｜Docker部署 | 2:08 | [link](https://www.bilibili.com/video/BV1iEEJz2EeA) |
| 792 | - | - | 【DeepSeek系列】通过3种方式访问DeepSeek模型服务: 通过CLI运行推理｜通过API访问服务｜通过Python访问服务｜DeepSeek教程 | 5:28 | [link](https://www.bilibili.com/video/BV1RHEJzyEmk) |
| 793 | - | - | 【AI新趋势】什么是Agentic RAG？颠覆传统RAG的智能升级！大模型LLM+Agent智能体+检索增强生成RAG 系列课程更新中 | 1:26 | [link](https://www.bilibili.com/video/BV17J7fzxEL7) |
| 794 | - | - | 为什么大模型总是答非所问？LLM面临的四大挑战，核心问题一次搞懂 | 2:06 | [link](https://www.bilibili.com/video/BV1hQ7ZzyE7D) |
| 795 | - | - | 本地部署DeepSeek大模型，只需3步！Ollama + Docker 快速运行 API 服务 | 3:54 | [link](https://www.bilibili.com/video/BV1cBEezcEau) |
| 796 | - | - | DeepSeek大模型上线Web可视化界面！OpenWebUI + Ollama 部署全流程实战 | 4:13 | [link](https://www.bilibili.com/video/BV1QREezEERt) |
| 797 | - | - | 1分钟了解一个高效AI项目技术栈：Ollama + Playwright + MLFlow 搭建LLM服务我选这3个工具，非常高效！ | 0:50 | [link](https://www.bilibili.com/video/BV1juEizZEL7) |
| 798 | - | - | 教你如何不用OpenAI API Key 不花一分钱 即可跑通OpenAI Agents SDK全流程！ | 1:12 | [link](https://www.bilibili.com/video/BV1m4EizLEEh) |
| 799 | - | - | 搞懂RAG三大核心机制！LLM如何靠检索增强提升上下文理解力？ | 1:25 | [link](https://www.bilibili.com/video/BV1LpEkzVE38) |
| 800 | - | - | 【AI基础知识】LLM与RAG有何区别？一张图带你全面理解！ | 3:17 | [link](https://www.bilibili.com/video/BV1QoEpz7EAL) |
| 801 | - | - | 【AI Agent入门】3分钟了解LLM驱动的智能体核心原理 | 3:47 | [link](https://www.bilibili.com/video/BV1aPEDztESh) |
| 802 | - | - | 【RAG系统架构】一张图看懂检索增强生成流程！ | 2:06 | [link](https://www.bilibili.com/video/BV1ABEfzTEp9) |
| 803 | - | - | 【Agentic RAG框架详解】大模型+智能体的检索增强新范式 | 2:25 | [link](https://www.bilibili.com/video/BV1mpJ6ztEL3) |
| 804 | - | - | AI Agent 五大工作模式详解｜图解LLM智能体执行流程 | 4:13 | [link](https://www.bilibili.com/video/BV13RJ7zMEkD) |
| 805 | - | - | AI Agent核心能力全解析｜LLM、记忆、规划与工具是如何协作的？ | 2:37 | [link](https://www.bilibili.com/video/BV1QtJxzZEH7) |
| 806 | - | - | Qwen3本地RAG项目全流程 / Agentic RAG智能问答系统 项目结构 + UI功能介绍 | 2:37 | [link](https://www.bilibili.com/video/BV1TRj4zJECR) |
| 807 | - | - | 【AI知识库索引构建方法】多模型支持 Transformer/Sentence-Transformer/BM25多方法 实现高效索引 | 5:40 | [link](https://www.bilibili.com/video/BV1TWjgzvEmY) |
| 808 | - | - | 【LoRA微调核心问题】为什么LoRA权重初始化用正态分布，而不是零矩阵？ | 3:08 | [link](https://www.bilibili.com/video/BV1Fyj2zoEwv) |
| 809 | - | - | AI Agents + RAG 智能体驱动的检索增强新范式｜Agentic RAG的核心理念 | 1:34 | [link](https://www.bilibili.com/video/BV1uNjizCEai) |
| 810 | - | - | 【DeepSeek系列】RAG智能问答系统项目全览｜DeepSeek R1+Ollama+FAISS+Gradio实现流程｜PDF上传智能问答 | 2:29 | [link](https://www.bilibili.com/video/BV1Y67HzjEdC) |
| 811 | - | - | 【多智能体Agents应用实践】本地浏览器搜索Agent 多代理协作系统完整实现方案 / 支持Ollama大模型 / 自动规划搜索策略+并发任务+结构化研究报告 | 5:21 | [link](https://www.bilibili.com/video/BV1Rj7azkELc) |
| 812 | - | - | 【工具调用-高德天气API集成】手把手教你集成高德天气API｜完整演示高德API Key申请流程 | 5:19 | [link](https://www.bilibili.com/video/BV1n6TuzaEQZ) |
| 813 | - | - | 【AI Agent 实战】从0到1构建天气查询Agent 基于Ollama+Qwen本地模型 高德API全流程实战 | 8:22 | [link](https://www.bilibili.com/video/BV1eLTCz2EK2) |
| 814 | - | - | 【保姆级教程】原创案例 从零到一手把手教你 DeepSeek-R1 蒸馏版大模型微调 / 基于PyTorch QLoRA PEFT vLLM | 14:33 | [link](https://www.bilibili.com/video/BV1KfMuzVEKN) |
| 815 | - | - | MCP智能助手实战 / 手把手打造AI待办事项系统，支持Claude Desktop集成！ | 5:58 | [link](https://www.bilibili.com/video/BV1NdNnzPEbq) |
| 816 | - | - | 入门级教程 含源码解析｜DeepSeek-R1 + LangChain构建智能问答助手，支持RAG检索、多轮对话、文档解析｜大模型RAG实战教程 | 7:45 | [link](https://www.bilibili.com/video/BV1hb3MzRE9G) |
| 817 | - | - | 【含源码解析】多智能体协同案例：从大纲生成到科幻故事全流程AI创作｜Ollama本地大模型+AI Agent智能体协作｜Agent开发｜大模型Agent实战 | 11:07 | [link](https://www.bilibili.com/video/BV18Z3RzHEkB) |
| 818 | - | - | AI Agent开发调试利器！MCP协议实战Anthropic开源的MCP Inspector，可视化测试你的大模型工具！ | 9:47 | [link](https://www.bilibili.com/video/BV1ojGAzHEUa) |
| 819 | - | - | 【硬核科普】3分钟看懂AI搜索核心：文本嵌入与重排序！ | 2:59 | [link](https://www.bilibili.com/video/BV1kp8FzaEzZ) |
| 820 | - | - | Qwen3 Embedding模型论文3大创新点详解：刷新MTEB榜单！ | 3:21 | [link](https://www.bilibili.com/video/BV1mH8Bz2Es2) |
| 821 | - | - | DeepSeek R1 大模型微调实战项目 从数据到发布HuggingFace 全流程保姆级教程 基于unsloth+LoRA高效微调DeepSeek R1 | 3:21 | [link](https://www.bilibili.com/video/BV1RH82zUEDJ) |
| 822 | - | - | 【RLT强化学习项目实战】基于教师-学生范式训练数学大模型，全面提升推理能力！用GRPO训练Qwen3模型｜SFT+RL两阶段训练全流程 | 4:23 | [link](https://www.bilibili.com/video/BV1BohnzXErY) |
| 823 | - | - | vLLM部署实战：DeepSeek-R1蒸馏模型高性能上线全流程！ | 6:22 | [link](https://www.bilibili.com/video/BV1RWtpzVEQN) |
| 824 | - | - | 【Qwen3实战】5分钟带你看懂Qwen3双阶段检索｜Embedding+Reranker精准提升搜索&推荐效果！ | 5:44 | [link](https://www.bilibili.com/video/BV1vaeFzcEhf) |
| 825 | - | - | RAG(检索增强生成)到底是怎么运作的？从数据索引到搜索生成，带你掌握构建智能问答系统的关键技术，让大模型生成更精准答案！ | 3:29 | [link](https://www.bilibili.com/video/BV1u4YQzaEkb) |
| 826 | - | - | 【智能体必修课】如何让AI学会任务分工与接力？智能体常用代理模式之一：交接与路由模式 Ollama多语言代理 案例演示｜大模型实战教程｜Agent智能体 | 4:19 | [link](https://www.bilibili.com/video/BV1W7adzcERx) |
| 827 | - | - | 【源码级拆解】Agent驱动的Python代码执行器｜智能体决策+工具调用+消息处理｜智能体教程｜AI Agent｜大模型实战 | 26:40 | [link](https://www.bilibili.com/video/BV17NHCzsEiP) |
| 828 | - | - | 学完就能用！从0到1搭建Agentic RAG问答系统：Qwen3大模型+FAISS+Streamlit｜完整环境配置+实战部署教学｜RAG知识库搭建 | 8:55 | [link](https://www.bilibili.com/video/BV1KCHQzhETL) |
| 829 | - | - | 【FlashRAG实战入门】环境配置 + Pipeline实现 + Web端交互｜大模型RAG项目实战｜RAG检索增强生成 | 12:43 | [link](https://www.bilibili.com/video/BV1ewp3zcEvG) |
| 830 | - | - | 从0搭建VRAG多模态RAG：视觉检索+裁剪bbox+多轮对话，一键跑通Qwen2.5-VL实战 | 17:20 | [link](https://www.bilibili.com/video/BV1CUSKBmEVS) |
| 831 | - | - | 别再只做向量检索了！企业知识库检索必备：两阶段检索Embedding粗排 + Reranker精排 项目Demo全流程 含源码讲解 | 17:56 | [link](https://www.bilibili.com/video/BV1TcmjBCE6J) |
| 832 | - | - | 5分钟搞懂：Agent Skill 与 Prompt/Tool/MCP关系与区别！ | 5:30 | [link](https://www.bilibili.com/video/BV1fgftBxEdY) |
| 833 | - | - | 企业级RAG为什么选ElasticSearch？“搜索引擎+向量检索”融合方案｜Docker一键部署ElasticSearch+Kibana｜RAG向量检索 | 17:01 | [link](https://www.bilibili.com/video/BV1DY6qBdEk9) |
| 834 | - | - | Agent 工程化必看：一节讲透 Skill/Prompt/Tool/MCP区别！Skill体系+按需加载，让 Agent 不再“跑偏 | 18:34 | [link](https://www.bilibili.com/video/BV1NWcnzHEwZ) |
| 835 | - | - | Agent Skills 实战教程：如何让 Agent 按需加载知识？渐进式披露完整流程｜Agno Skills工作流全链路解析｜AI大模型｜智能体 | 14:48 | [link](https://www.bilibili.com/video/BV1yUfnBjEu2) |
| 836 | - | - | Agno框架Agent实战：智能写作Skill实现指南，Agent与Skill打造高效AI写作助手｜AI智能体｜大模型应用 | 7:40 | [link](https://www.bilibili.com/video/BV1sYfABeEoQ) |
| 837 | - | - | 一节搞懂Agent Skill工作流，手把手实现一个数据分析Skill：脚本执行+参考文档编排，用Skill把能力模块化｜智能体应用｜大模型实战｜AIAgent | 9:32 | [link](https://www.bilibili.com/video/BV1eqfBBmE2j) |
| 838 | - | - | Skill+MCP协同：智能电商客服Agent项目实战，多Skill动态选择 + 知识驱动工具调用，退款/咨询/故障+查单跨域协作（Skill + MCP） | 25:23 | [link](https://www.bilibili.com/video/BV1yJfSBfEVp) |
| 839 | - | - | DeepSeek 证明 LLM 才是更好的视觉编码器！DeepSeek OCR 2.0 架构拆解：基于Causal Queries的视觉Token重排序与压缩 | 4:59 | [link](https://www.bilibili.com/video/BV1uqz9BNEQw) |
| 840 | - | - | DeepSeek OCR 模型架构全解析｜从视觉编码到文本理解的核心机制详解｜AI大模型｜多模态大模型｜LLM | 28:20 | [link](https://www.bilibili.com/video/BV1GNsWzeEYc) |
| 841 | - | - | DeepSeek-OCR模型部署与推理全流程｜多模态OCR实战：从环境配置到API服务上线｜多模态大模型｜AI大模型实战 | 22:24 | [link](https://www.bilibili.com/video/BV1RtyaBbEC4) |
| 842 | - | - | 【大模型部署必学第一课】DeepSeek R1 实战 Ollama+OpenWebUI 本地RAG系统实战教程 全流程演示｜大模型教程｜RAG知识库搭建 | 17:02 | [link](https://www.bilibili.com/video/BV18pP2eEEPk) |
| 843 | - | - | DeepSeek R1 项目实战 基于Langchain+Faiss+Ollama+Gradio+Docker 从0到1实现RAG私有化部署 简易版实现 | 10:05 | [link](https://www.bilibili.com/video/BV1LMN8emEbD) |
| 844 | - | - | DeepSeek R1 深入浅出RAG技术实战：整合大模型、Ollama、FAISS、Gradio 和 Docker 搭建智能问答系统 | 18:00 | [link](https://www.bilibili.com/video/BV1i8NheHEab) |
| 845 | - | - | DeepSeek R1 大模型微调 基于unsloth微调框架与LoRA以及CoT问答数据集 wandb可视化训练日志 大模型微调与推理全流程实战 | 20:18 | [link](https://www.bilibili.com/video/BV1J8NGezENE) |
| 846 | - | - | DeepSeek R1 原创项目 基于PyTorch QLoRA PEFT vLLM 实现R1蒸馏版大模型微调与部署 单卡/多卡两种方法 | 17:25 | [link](https://www.bilibili.com/video/BV1HPwfeAEhz) |
| 847 | - | - | DeepSeek R1 原创项目 核心源码讲解 AI大模型 deepseek蒸馏版大模型微调与部署实战教程 基于PyTorch QLoRA PEFT vLLM | 23:57 | [link](https://www.bilibili.com/video/BV1yXAzeDELm) |
| 848 | - | - | 《DeepSeek系统实战：架构·算法·工程·应用》课程简介 | 8:05 | [link](https://www.bilibili.com/video/BV1WfrPB9Ewk) |
| 849 | - | - | 阿里AgentEvolver：Agent如何“自提问-自导航-自归因”实现高效自进化？大模型Agent强化学习提效思路 | 9:30 | [link](https://www.bilibili.com/video/BV1wgqDBuE4b) |
| 850 | - | - | AgentEvolver 强化学习+LLM Agent：Self-Questioning 让智能体自己造训练集｜多智能体/工具调用都能用 逆向任务生成 | 21:39 | [link](https://www.bilibili.com/video/BV1mTBKBxEYw) |
| 851 | - | - | Agent强化学习训练提效：Self-Navigating 经验驱动探索与隐式经验学习｜AgentEvolver 自进化Agent系统｜大模型Agent｜智能体 | 15:11 | [link](https://www.bilibili.com/video/BV1jcB2BXE1Z) |
| 852 | - | - | 长程任务RL的“信用分配”怎么破？从“结果奖励”到“过程奖励” Self-Attributing把稀疏奖励变密集｜AgentEvolver深度解读 | 18:09 | [link](https://www.bilibili.com/video/BV1HHBQBCELa) |
| 853 | - | - | AgentEvolver实战：AppWorld 环境 + GRPO 跑通「Agent自进化训练」全流程（安装/启动/配置）AI Agent｜强化学习 | 23:49 | [link](https://www.bilibili.com/video/BV1nNibBuEGs) |
| 854 | - | - | AWorld 企业级 Multi-Agent 框架深度解析：多智能体协作 + MCP工具 + 强化学习训练｜AI Agent｜智能体教程｜AI大模型 | 23:36 | [link](https://www.bilibili.com/video/BV1LaWiz6ESN) |
| 855 | - | - | AWorld 框架快速入门：环境搭建到第一个AI助理实例｜多智能体｜AI Agent教程｜智能体开发 | 5:46 | [link](https://www.bilibili.com/video/BV17HWCzhEAo) |
| 856 | - | - | 【AI Agent实战】一节掌握4大智能体：搜索+分析+工具+协作全流程 含源码解析｜AWorld框架深度解析｜大模型应用｜AI Agent｜多智能体 | 28:25 | [link](https://www.bilibili.com/video/BV1JYsZzVEq8) |
| 857 | - | - | GAIA项目实战：用 MCP 工具生态打造 Production-Ready 多模态 Agent（AWorld 架构拆解） | 13:55 | [link](https://www.bilibili.com/video/BV177S4B8EPH) |
| 858 | - | - | GAIA项目实战：从0跑通 AWorld！环境搭建 + WebUI/CLI 双模式联调（含Playwright/E2B）Agent智能体教程｜MCP协议｜多模态 | 15:19 | [link](https://www.bilibili.com/video/BV18P2xBzEBc) |
| 859 | - | - | 微软强化学习框架 Agent Lightning 核心方法论深度解读：零代码RL优化AI Agent｜从MDP理论到分层RL算法，无缝接入现有Agent框架 | 34:33 | [link](https://www.bilibili.com/video/BV13qbYzMEpM) |
| 860 | - | - | 深度拆解Agent Lightning系统架构设计｜分布式训练+核心模块全流程解析｜强化学习｜大模型推理｜智能体教程 | 7:18 | [link](https://www.bilibili.com/video/BV11DYqzUEhn) |
| 861 | - | - | 【SQL Agent实战】Agent Lightning 项目：LangChain + LangGraph + 强化学习｜智能体教程｜AI大模型实战 | 35:11 | [link](https://www.bilibili.com/video/BV1W2YyzvEz4) |
| 862 | - | - | 【Agent Lightning实战】智能计算Agent项目概述｜AutoGen + MCP + 强化学习 + Qwen大模型｜智能体教程｜强化学习实战 | 6:58 | [link](https://www.bilibili.com/video/BV1SPeoz1ELg) |
| 863 | - | - | 【Agent Lightning实战全流程】手把手教你搭建智能计算Agent｜从环境配置到模型推理一步到位｜强化学习算法+全流程实操 | 21:34 | [link](https://www.bilibili.com/video/BV166h2z8ERc) |
| 864 | - | - | RAG Agent RL实战指南（上）：数据准备、模型下载与知识库构建｜搭建智能检索增强系统｜强化学习｜RAG｜Agent智能体 | 16:08 | [link](https://www.bilibili.com/video/BV17xahzUEiG) |
| 865 | - | - | RAG Agent RL实战指南（下）：从0到1部署检索服务，启动分布式强化学习训练！Agent Lightning 智能体强化学习框架应用 | 20:39 | [link](https://www.bilibili.com/video/BV19BpEzUEcs) |
| 866 | - | - | RAG Agent RL源码深度解析｜从数据到推理的源码级拆解与实现｜检索增强生成核心机制全流程｜大模型RAG实战｜RAG + 强化学习｜Agent智能体 | 29:15 | [link](https://www.bilibili.com/video/BV19enPzMEWg) |
| 867 | - | - | 【APO实战】Agent-Lightning 提示词自动优化：智能会议室预订Agent（LLM Judge / Beam Search / 无需微调） | 43:54 | [link](https://www.bilibili.com/video/BV1Kr1sBhEe6) |
| 868 | - | - | 【APO算法 Debug讲解】Agent-Lightning 会议室预订Agent案例 核心源码讲解：数据流、Beam Search、LLM Judge | 18:57 | [link](https://www.bilibili.com/video/BV1Up23BFEJG) |
| 869 | - | - | Dify大模型应用平台深度解析 全面拆解架构、核心原理与功能机制｜大模型Agent开发｜RAG Agent 与多模型管理｜AI应用开发 | 26:33 | [link](https://www.bilibili.com/video/BV1wK4AzcEPF) |
| 870 | - | - | Dify本地部署全流程｜Docker安装+源码构建两种方式实战教学｜AI应用框架必学｜大模型Agent应用｜智能体开发 | 16:06 | [link](https://www.bilibili.com/video/BV1Ac42zWEMX) |
| 871 | - | - | 【UltraRAG 2.0 深度剖析】科研级RAG系统新范式：MCP 架构+YAML声明式编程｜Agentic RAG / 检索增强生成｜多模态大模型｜智能体 | 13:37 | [link](https://www.bilibili.com/video/BV1ZBpozAEqB) |
| 872 | - | - | 【UltraRAG快速入门实战】从环境搭建到完整RAG Pipeline / 本地LLM+MCP架构+YAML编程｜大模型RAG项目实战｜Agentic RAG | 22:37 | [link](https://www.bilibili.com/video/BV1FtJ1zhEHL) |
| 873 | - | - | 原创案例 Agentic RAG智能学术助手完整流程拆解 包含核心代码讲解 基于清华UtralRAG MCP架构+YAML声明式编程｜大模型RAG｜Agent | 31:15 | [link](https://www.bilibili.com/video/BV1tTn7zPEdx) |
| 874 | - | - | 【原创实战】VisionRAG Pro：构建智能多模态视觉分析系统｜UltraRAG 2.0 + Qwen2.5-VL 全流程讲解｜MCP架构｜YAML编程 | 28:39 | [link](https://www.bilibili.com/video/BV1Qr43zME4V) |
| 875 | - | - | 【阿里最新多模态RL框架解析】VRAG-RL研究背景详解：为什么RAG在图文理解上失效？ | 7:15 | [link](https://www.bilibili.com/video/BV1RZ8gzEEQo) |
| 876 | - | - | 【阿里最新多模态RAG+Agent】VRAG-RL方法论全拆解：多专家采样 × 细粒度奖励，刷新多模态RAG新高度！ | 24:23 | [link](https://www.bilibili.com/video/BV1ct8ozxEXx) |
| 877 | - | - | 【多模态RAG实战】VRAG项目全流程解析：构建视觉增强问答系统（Agent+RAG+Qwen2.5） / 支持图文检索+多轮对话｜智能体搭建｜检索增强生成 | 19:00 | [link](https://www.bilibili.com/video/BV135t5z7EDU) |
| 878 | - | - | 从零构建自定义多模态VRAG Agent助手｜ColQwen2 嵌入+FastAPI 部署+Streamlit 可视化 全流程实战 | 16:33 | [link](https://www.bilibili.com/video/BV1D3b8ztEX5) |
| 879 | - | - | 【实战教程】本地知识库+开源框架(Ollama/Qwen/LlamaIndex)｜多模态RAG检索增强生成 训练数据集构建全流程 | 23:15 | [link](https://www.bilibili.com/video/BV1dRYQzGEXy) |
| 880 | - | - | 【强化学习实战】VRAG-RL全流程：基于Qwen2.5-VL和GRPO实现强化学习在多模态RAG中的应用｜多模态大模型｜多模态RAG｜AI大模型实战 | 10:48 | [link](https://www.bilibili.com/video/BV11wYyzvEPj) |
| 881 | - | - | 【VRAG项目架构全解析】多模态RAG与强化学习智能体的系统设计与实现｜强化学习｜多模态大模型｜检索增强生成RAG｜Agent智能体｜AI大模型教程 | 10:08 | [link](https://www.bilibili.com/video/BV1iYewzMESg) |
| 882 | - | - | VRAG-RL核心源码精讲｜多模态检索增强生成与多步推理实现原理｜从0到1构建多模态视觉RAG Agent系统 (LlamaIndex/Ollama) | 43:38 | [link](https://www.bilibili.com/video/BV1YtezzTEC3) |
| 883 | - | - | RL强化学习新范式！RLT教师强化学习模型算法全解析｜SFT+RL两阶段训练全流程详解｜AI大模型微调｜大模型Agent｜Agent智能体｜Sakana AI | 17:36 | [link](https://www.bilibili.com/video/BV1ywG5zhE6k) |
| 884 | - | - | 【RLT强化学习算法原理】稠密奖励函数详解，训练更稳定、收敛更快的关键｜基于学生模型对数似然与KL散度的稠密奖励机制深度分析｜强化学习的数学原理｜AIAgent | 17:49 | [link](https://www.bilibili.com/video/BV1orubzJEPq) |
| 885 | - | - | 强化大模型的最后一环！RLT教师强化学习项目实战：奖励模型+偏好优化全流程解析（SFT+GRPO） | 20:40 | [link](https://www.bilibili.com/video/BV1VHg3zPEfN) |
| 886 | - | - | Qwen3 Embedding 模型详解：文本嵌入与重排序性能全面超越SOTA 重新定义文本嵌入 RAG必备神器｜检索增强生成｜大模型RAG｜通义千问 | 22:20 | [link](https://www.bilibili.com/video/BV1xHM3zjEr6) |
| 887 | - | - | Qwen3 Embedding+Reranker黄金组合 本地推理与部署实战 (附核心代码讲解) ｜RAG核心组件｜检索增强生成｜大模型rag教程 | 23:03 | [link](https://www.bilibili.com/video/BV1kVMAzSEHC) |
| 888 | - | - | 【实战】Qwen3 Embedding高效知识库检索系统Demo｜Embedding+Reranker两阶段精准召回｜检索增强生成｜大模型RAG实战 | 15:25 | [link](https://www.bilibili.com/video/BV1GYM2zdEbR) |
| 889 | - | - | Qwen3 Embedding模型微调教程（含LoRA与全参训练）｜支持MS-Swift框架｜AI大模型教程｜大模型微调实战 | 11:43 | [link](https://www.bilibili.com/video/BV1dZNdzUEUG) |
| 890 | - | - | Qwen3 Reranker (重排模型) 大模型微调实战教学｜LoRA高效微调+DeepSpeed训练加速｜RAG检索增强生成｜大模型LLM教程 | 7:01 | [link](https://www.bilibili.com/video/BV1T9KbzhE6j) |
| 891 | - | - | Agentic RAG 大模型+智能体+检索增强生成RAG 全流程实战｜大模型教程｜AI智能体｜检索增强rag / Agenticrag | 7:58 | [link](https://www.bilibili.com/video/BV1ZiEEzLE3X) |
| 892 | - | - | 【RAG原理详解】如何用检索增强生成技术提升大模型问答能力｜原理+挑战+解决方案全解析 | 9:27 | [link](https://www.bilibili.com/video/BV12pEFzGEyQ) |
| 893 | - | - | 【深度解析】Agentic RAG原理详解：智能体驱动的检索增强新范式｜大模型+智能体融合应用讲解｜大模型教程｜Agent智能体｜检索增强生成技术 | 6:37 | [link](https://www.bilibili.com/video/BV1NdEqzLEG5) |
| 894 | - | - | Agent核心架构全解：四大设计模式＋五类工作流机制｜含图解与主流框架实战分析｜Agentic RAG｜大模型Agent教程 ｜检索增强生成RAG | 9:38 | [link](https://www.bilibili.com/video/BV13uE8zeEVz) |
| 895 | - | - | Agentic RAG架构全解析：7种典型系统设计与实战应用 层级、多Agent、自适应、纠错型一次讲透｜大模型RAG进阶｜智能体Agent｜大模型RAG教程 | 11:27 | [link](https://www.bilibili.com/video/BV1e4E9zuEGh) |
| 896 | - | - | 【原创案例】Agentic RAG 基于Qwen3+langchain+ollama+Faiss+agno搭建完整RAG系统｜AI大模型教程｜大模型RAG | 24:26 | [link](https://www.bilibili.com/video/BV17PJhzSEBy) |
| 897 | - | - | 【源码解析】原创案例 Agentic RAG 本地化智能问答系统 项目实现思路及核心源码讲解 ｜Agent智能体工作流教程｜源码分析｜大模型智能体 | 21:18 | [link](https://www.bilibili.com/video/BV1VqJnz7ELU) |
| 898 | - | - | OpenAI Agents SDK 轻量级多智能体框架 基于大模型构建多智能体工作流 Agent智能体 Workflow 多轮对话 智能问答 对话助手 | 17:21 | [link](https://www.bilibili.com/video/BV1ajXkY2Edx) |
| 899 | - | - | 大模型Agent实战 原创案例 高德天气查询助手Agent 多智能体开发框架OpenAI Agents 智能体搭建 agent智能体工作流 智能体开发教程 | 15:52 | [link](https://www.bilibili.com/video/BV1VCoBY7ErL) |
| 900 | - | - | OpenAI Agents 多智能体开发框架 常用代理模式 确定性模式案例：写作助手Agent 大模型Agent实战 AI大模型教程 智能体工作流 | 12:08 | [link](https://www.bilibili.com/video/BV1ANotYYEFL) |
| 901 | - | - | OpenAI Agents 多智能体开发框架 常用代理模式 交接与路由模式 Agent智能体搭建 大模型Agent实战 智能体开发 agent智能体工作流教程 | 14:18 | [link](https://www.bilibili.com/video/BV1TAZKYEEzh) |
| 902 | - | - | OpenAI Agents SDK 多智能体开发框架 常用代理模式 代理作为工具 大模型Agent实战 AI Agent 智能体搭建 agent智能体工作流教程 | 10:48 | [link](https://www.bilibili.com/video/BV1iJZVYSEtv) |
| 903 | - | - | OpenAI Agents SDK 多智能体开发框架 常用代理模式 LLM大模型作为评判者 Agent智能体 AI大模型实战教程 写作助手Agent案例演示 | 11:43 | [link](https://www.bilibili.com/video/BV1qpZSYWEzf) |
| 904 | - | - | OpenAI Agents SDK 多智能体开发框架 常用代理模式 并行模式 大模型Agent教程 AI大模型 智能体Agent | 6:24 | [link](https://www.bilibili.com/video/BV1BeRqY2E51) |
| 905 | - | - | OpenAI Agents SDK 原创案例 大模型Agent实战 本地浏览器自动化检索（类似 Manus 效果）AI 智能体搭建 Agent开发教程 | 33:18 | [link](https://www.bilibili.com/video/BV1GSdpYPEMB) |
| 906 | - | - | 【MCP模型上下文协议实战指南】 AI Agent多场景应用实战 AI大模型应用实战教程 多智能体｜LLM｜DeepSeek｜MCP协议｜MCP入门 | 48:13 | [link](https://www.bilibili.com/video/BV1XwZHYPExh) |
| 907 | - | - | MCP模型上下文协议 基于Claude和Cline进行MCP服务器配置 大模型MCP案例实战 MCP Server开发 MCP客户端构建 ai大模型教程 | 16:20 | [link](https://www.bilibili.com/video/BV1cvZUY4Ec9) |
| 908 | - | - | MCP模型上下文协议 MCP Inspector调试MCP Servers的使用方法 AI大模型｜AI Agent｜智能体Agent｜mcp教程 | 10:17 | [link](https://www.bilibili.com/video/BV1DgZZYeE4Y) |
| 909 | - | - | MCP Server开发与应用 原创案例 待办事项助手 基于MCP Inspector可视化调试MCP Server AI大模型实战教程｜智能体Agent | 18:52 | [link](https://www.bilibili.com/video/BV1fgRfYkEfk) |
| 910 | - | - | AI Agent全景解析 + Lagent框架简介｜从智能体核心组件到开源项目｜大模型Agent教程｜AI前沿技术分享｜AI智能体 | 21:29 | [link](https://www.bilibili.com/video/BV1c8wNe1EL6) |
| 911 | - | - | AI Agent实战入门｜环境配置 + 基础对话模型调用｜大模型Agent实战｜智能体开发框架｜Agent智能体教程 | 32:15 | [link](https://www.bilibili.com/video/BV1PdwWe6Ei3) |
| 912 | - | - | 大模型Agent实战 LLM智能体轻量级开发框架 lagent 项目实战 案例二 fewshot 示例增强 | 19:19 | [link](https://www.bilibili.com/video/BV1ucwYeuEfd) |
| 913 | - | - | 大模型Agent实战 LLM智能体轻量级开发框架 lagent 项目实战 案例三 Agent驱动的Python代码执行器 | 26:53 | [link](https://www.bilibili.com/video/BV1fLfhYgE3C) |
| 914 | - | - | 大模型Agent实战 LLM智能体轻量级开发框架 lagent 项目 案例四 高德 天气API集成 | 26:49 | [link](https://www.bilibili.com/video/BV1c3fkYkEJE) |
| 915 | - | - | 大模型Agent实战 LLM智能体轻量级开发框架 lagent 项目 案例五 高德位置搜索和导航 | 15:29 | [link](https://www.bilibili.com/video/BV1qsPoeoE1X) |
| 916 | - | - | FlashRAG 大模型RAG研究一站式解决方案 项目简介 | 8:01 | [link](https://www.bilibili.com/video/BV1Tuk3YREML) |
| 917 | - | - | FlashRAG 大模型LLM与RAG研究利器 核心组件原理精讲 | 15:57 | [link](https://www.bilibili.com/video/BV1x3k3YWEeC) |
| 918 | - | - | FlashRAG 大模型LLM与RAG研究高效工具包 案例实践 快速入门Demo | 22:12 | [link](https://www.bilibili.com/video/BV1Q4kAYgEPm) |
| 919 | - | - | FlashRAG 大模型LLM与RAG研究利器 核心模块参数详细解析 | 19:31 | [link](https://www.bilibili.com/video/BV1V2kBY5EJo) |
| 920 | - | - | FlashRAG 项目实战 基于Transformers和BM25构建密集索引和稀疏索引 | 18:25 | [link](https://www.bilibili.com/video/BV1NHkSYcEoS) |
| 921 | - | - | FlashRAG 项目实战 大模型LLM与RAG研究利器 论文实验流程复现 | 33:45 | [link](https://www.bilibili.com/video/BV1BWkRYPEQM) |
| 922 | - | - | FlashRAG 大模型LLM与RAG研究利器 案例实战 核心源码Debug深度剖析 | 41:05 | [link](https://www.bilibili.com/video/BV1nECBY4E8g) |
| 923 | - | - | Meta重磅发布Llama 3.2：开放可定制的大模型深度解析 轻量级AI大模型和多模态模型 模型架构｜大模型教程｜AI前沿技术 | 17:58 | [link](https://www.bilibili.com/video/BV1d5xEeiEp5) |
| 924 | - | - | Llama3模型深入解析 核心功能 模型架构详解 大模型基础知识 llama3教程｜AI大模型教程｜AI前沿技术 | 11:09 | [link](https://www.bilibili.com/video/BV1pu4m1F7Ax) |
| 925 | - | - | 【系列课程】Llama3模型部署环境配置 基于vLLM推理 大模型实战 | 17:09 | [link](https://www.bilibili.com/video/BV1yt421P7ML) |
| 926 | - | - | 【系列课程】深度探索Llama 3 Torchrun分布式推理与特殊标记应用 大模型llama系列课程 | 9:56 | [link](https://www.bilibili.com/video/BV1ex4y187bx) |
| 927 | - | - | 【实操干货】Llama3模型量化与部署 基于llama.cpp进行大模型本地推理与部署 Llama3部署教程 | 16:32 | [link](https://www.bilibili.com/video/BV1Sw4m127ye) |
| 928 | - | - | 【项目实战】Llama 3模型Docker实战 利用开源项目llama.cpp进行Llama3模型的量化 并部署API服务 大模型实战教程 | 17:15 | [link](https://www.bilibili.com/video/BV1jF4m1A7jA) |
| 929 | - | - | 【Llama3 微调】基于llama-factory和自定义数据集进行大模型微调 Llama3教程 AI大模型实战课程 | 22:25 | [link](https://www.bilibili.com/video/BV1bp421S7Db) |
| 930 | - | - | 【Llama3 部署】基于TensorRT-LLM和Triton进行Llama3模型部署 AI大模型实战教程 | 40:14 | [link](https://www.bilibili.com/video/BV1Ap421D7GA) |
| 931 | - | - | llama-2-模型推理 | 12:40 | [link](https://www.bilibili.com/video/BV17h4y157x4) |
| 932 | - | - | 1-01 实战 泰坦尼克号沉船人员获救案例 数据清洗 | 38:50 | [link](https://www.bilibili.com/video/BV18k4y117Lf) |
| 933 | - | - | 1-02 实战 泰坦尼克号沉船人员获救案例 特征构建 (一) | 34:27 | [link](https://www.bilibili.com/video/BV1nK4y1Y7gD) |
| 934 | - | - | 1-03 实战 泰坦尼克号沉船人员获救案例 特征构建 (二) | 8:40 | [link](https://www.bilibili.com/video/BV1fA411Y7NH) |
| 935 | - | - | 1-04 实战 泰坦尼克号沉船人员获救案例 训练集和测试集 | 19:17 | [link](https://www.bilibili.com/video/BV1Yf4y197L1) |
| 936 | - | - | 1-05 实战 泰坦尼克号沉船人员获救案例 随机森林算法实现 | 26:37 | [link](https://www.bilibili.com/video/BV1mD4y1U7Uf) |
| 937 | - | - | 2 机器学习实战 纽约出租车车费预测 | 46:35 | [link](https://www.bilibili.com/video/BV1nz4y1f74G) |
| 938 | - | - | 3-01 实战 RNN LSTM 原理 | 17:01 | [link](https://www.bilibili.com/video/BV1kz4y1f7u7) |
| 939 | - | - | 3-02 LSTM 文本生成（字符级） | 31:05 | [link](https://www.bilibili.com/video/BV1v5411h79S) |
| 940 | - | - | 3-03 LSTM IBM股价预测 第一节 | 12:07 | [link](https://www.bilibili.com/video/BV1xD4y1m7CC) |
| 941 | - | - | 3-04 LSTM IBM股价预测 第二节 | 14:52 | [link](https://www.bilibili.com/video/BV1fa4y177Jf) |
| 942 | - | - | 3-05 LSTM IBM股价预测 第三节 | 7:55 | [link](https://www.bilibili.com/video/BV19T4y1L7GQ) |
| 943 | - | - | 3-06 LSTM IBM股价预测 第四节 | 14:53 | [link](https://www.bilibili.com/video/BV1jZ4y1T72j) |
| 944 | - | - | 3-07 LSTM IBM股价预测 第五节 | 9:42 | [link](https://www.bilibili.com/video/BV1Rp4y1Y7Rn) |
| 945 | - | - | 4-01 决策树 随机森林算法 案例实战 原理部分（上） | 18:23 | [link](https://www.bilibili.com/video/BV14a4y1j7QA) |
| 946 | - | - | 4-02 决策树 随机森林算法案例实战 用户流失预测（下） | 28:44 | [link](https://www.bilibili.com/video/BV1U5411b7a8) |
| 947 | - | - | 5-01 聚类算法kmeans和MeanShift原理 + 零售案例实战（上） | 32:40 | [link](https://www.bilibili.com/video/BV13a4y1j7uJ) |
| 948 | - | - | 5-02 聚类算法kmeans和MeanShift实战 消费者画像分析 | 35:27 | [link](https://www.bilibili.com/video/BV1Yp4y1e7A3) |
| 949 | - | - | 6-01 信用卡交易欺诈数据检测 (一) | 32:42 | [link](https://www.bilibili.com/video/BV1Sz4y1d7SB) |
| 950 | - | - | 6-02 信用卡交易欺诈数据检测 (二) | 24:58 | [link](https://www.bilibili.com/video/BV12t4y1v7sC) |
| 951 | - | - | 6-03 信用卡交易欺诈数据检测 方法2 (三) | 22:12 | [link](https://www.bilibili.com/video/BV1ia411A7fd) |
| 952 | - | - | 6-04 信用卡交易欺诈数据检测 方法2 (四) | 27:09 | [link](https://www.bilibili.com/video/BV1rK4y177E8) |
| 953 | - | - | 6-05 信用卡交易欺诈数据检测 方法3 基于PyTorch实现 (五) | 20:32 | [link](https://www.bilibili.com/video/BV135411L7AD) |
| 954 | - | - | 7-01 最牛算法之一_lightGBM算法_理论部分 | 22:51 | [link](https://www.bilibili.com/video/BV1JK4y1L7ow) |
| 955 | - | - | 7-02 最牛算法之一_lightGBM算法_交易欺诈检测实战【上集】 | 22:33 | [link](https://www.bilibili.com/video/BV1ZZ4y1g7T6) |
| 956 | - | - | 7-03 最牛算法之一_lightGBM算法_交易欺诈检测实战【下集】 | 32:28 | [link](https://www.bilibili.com/video/BV19T4y1M7ve) |
| 957 | - | - | 8_01 房屋价格预测【回归案例】 | 21:53 | [link](https://www.bilibili.com/video/BV1b54y1p7WG) |
| 958 | - | - | 8_02 房屋价格预测【回归案例】 | 17:15 | [link](https://www.bilibili.com/video/BV18y4y117Tp) |
| 959 | - | - | 8_03 房屋价格预测【回归案例】 | 19:09 | [link](https://www.bilibili.com/video/BV1DN411d7N7) |
| 960 | - | - | 09-1 进阶版 房屋价格预测案例 线性回归 理论部分 | 13:57 | [link](https://www.bilibili.com/video/BV1Nz421D7hn) |
| 961 | - | - | 09-2 进阶版 房屋价格预测 案例实战 数据预处理 | 7:23 | [link](https://www.bilibili.com/video/BV1ob421h74v) |
| 962 | - | - | 9-3 进阶版 房屋价格预测 案例实战 数据探索与分析（上） | 27:22 | [link](https://www.bilibili.com/video/BV1aM4m1o7u1) |
| 963 | - | - | 9-4 进阶版 房屋价格预测 案例实战 数据探索与分析（下） | 37:39 | [link](https://www.bilibili.com/video/BV1Wt421c7iU) |
| 964 | - | - | 9-5 进阶版 房屋价格预测 案例实战 特征工程 | 16:21 | [link](https://www.bilibili.com/video/BV1Pr421g7MD) |
| 965 | - | - | 9-6 进阶版 房屋价格预测 案例实战 模型训练和预测 | 15:36 | [link](https://www.bilibili.com/video/BV1Vb421a78U) |
| 966 | - | - | lightGBM-01 机器学习算法简介 | 9:47 | [link](https://www.bilibili.com/video/BV1K142197Yb) |
| 967 | - | - | LightGBM-02 算法大纲 | 2:28 | [link](https://www.bilibili.com/video/BV1dT421C72B) |
| 968 | - | - | LightGBM-03 基于Histogram的决策树算法 | 6:15 | [link](https://www.bilibili.com/video/BV1wt421w7GR) |
| 969 | - | - | LightGBM-04 单边梯度采样与互斥特征绑定 | 6:20 | [link](https://www.bilibili.com/video/BV1kZ42177oj) |
| 970 | - | - | LightGBM-05 多线程优化 | 9:33 | [link](https://www.bilibili.com/video/BV17T421y7ha) |
| 971 | - | - | LightGBM-06 核心超参数讲解 | 3:21 | [link](https://www.bilibili.com/video/BV1cm421p764) |
| 972 | - | - | LightGBM-07 论文解读 | 17:46 | [link](https://www.bilibili.com/video/BV1pD421P7ma) |
| 973 | - | - | LightGBM-08 入门案例 | 6:59 | [link](https://www.bilibili.com/video/BV1xm421H7MC) |
| 974 | - | - | LightGBM-09 医疗分类案例 | 15:32 | [link](https://www.bilibili.com/video/BV1FJ4m1J7Ho) |
| 975 | - | - | LightGBM-10 餐厅营收预测回归案例-上集 | 23:41 | [link](https://www.bilibili.com/video/BV1nM4m1d7K7) |
| 976 | - | - | LightGBM-11 餐厅营收预测回归案例-下集 | 19:31 | [link](https://www.bilibili.com/video/BV1gT42197xw) |
| 977 | - | - | 01 决策树算法简介 | 2:08 | [link](https://www.bilibili.com/video/BV1QT421a75u) |
| 978 | - | - | 02 决策树算法原理（一） | 7:07 | [link](https://www.bilibili.com/video/BV1Rm421V7r1) |
| 979 | - | - | 03 决策树算法原理（二） | 5:05 | [link](https://www.bilibili.com/video/BV1BE421N7xE) |
| 980 | - | - | 04 决策树算法原理（三） | 11:14 | [link](https://www.bilibili.com/video/BV1Jm421G7oc) |
| 981 | - | - | 05 决策树算法原理（四） | 9:19 | [link](https://www.bilibili.com/video/BV1mH4y1F7bq) |
| 982 | - | - | 06 决策树算法原理（五） | 1:47 | [link](https://www.bilibili.com/video/BV1UJ4m1T7bS) |
| 983 | - | - | 07 决策树 医疗分类案例 | 13:05 | [link](https://www.bilibili.com/video/BV1XS421X7Ki) |
| 984 | - | - | 08 决策树算法Python底层实现（一） | 9:59 | [link](https://www.bilibili.com/video/BV1nS42197rY) |
| 985 | - | - | 09 决策树算法Python底层实现（二） | 7:46 | [link](https://www.bilibili.com/video/BV1fy411e7zj) |
| 986 | - | - | 10 决策树算法Python底层实现（三） | 10:29 | [link](https://www.bilibili.com/video/BV1tS421X79P) |
| 987 | - | - | 11 决策树算法Python底层实现（四） | 11:40 | [link](https://www.bilibili.com/video/BV1xE421w7Az) |
| 988 | - | - | 12 决策树算法Python底层实现（五） | 11:30 | [link](https://www.bilibili.com/video/BV1kr421M7iu) |
| 989 | - | - | 13_编码知识点补充 | 7:53 | [link](https://www.bilibili.com/video/BV1YH4y1c7RV) |
| 990 | - | - | 14_编码知识点补充 | 4:33 | [link](https://www.bilibili.com/video/BV19y411i73L) |
| 991 | - | - | 15_收入预测分类案例(一) | 10:49 | [link](https://www.bilibili.com/video/BV1kr421M7C5) |
| 992 | - | - | 16_收入预测分类案例(二) | 10:24 | [link](https://www.bilibili.com/video/BV1k4421Z7ZJ) |
| 993 | - | - | 17 收入预测分类案例（三） | 11:25 | [link](https://www.bilibili.com/video/BV1YUp2eTEaM) |
| 994 | - | - | 18 收入预测分类案例（四） | 15:44 | [link](https://www.bilibili.com/video/BV1i6p2erEJC) |
| 995 | - | - | 01_多模态_MiniCPM-V_项目简介 | 8:08 | [link](https://www.bilibili.com/video/BV1T4421Q7Ei) |
| 996 | - | - | 02_多模态_基于Gradio和Streamlit实现Web端问答交互 | 17:12 | [link](https://www.bilibili.com/video/BV1E1421C7V2) |
| 997 | - | - | 03_多模态_基于llama.cpp进行模型量化和推理 | 18:20 | [link](https://www.bilibili.com/video/BV1Bw4m1v7A2) |
| 998 | - | - | 04_多模态_基于vLLM进行模型推理与源码讲解 | 25:04 | [link](https://www.bilibili.com/video/BV1jb42177ML) |
| 999 | - | - | 05_多模态_基于MiniCPM-V进行全参微调和lora微调 | 18:15 | [link](https://www.bilibili.com/video/BV1RE4m1R7ci) |
| 1000 | - | - | LoRA_01_算法原理深入解析-上集 | 21:25 | [link](https://www.bilibili.com/video/BV1cM4m1r7Fe) |
| 1001 | - | - | LoRA_02_算法原理深入解析-下集 | 15:35 | [link](https://www.bilibili.com/video/BV1FU411o7cF) |
| 1002 | - | - | LoRA_03_案例演示 LoRA的核心逻辑 | 10:08 | [link](https://www.bilibili.com/video/BV1sm421T7Xg) |
| 1003 | - | - | LoRA_04_基于PEFT进行llama3模型微调实战 | 18:31 | [link](https://www.bilibili.com/video/BV1gJ4m1A7UT) |
| 1004 | - | - | LoRA_05_01_基于GPT-2进行LoRA微调实战 | 14:08 | [link](https://www.bilibili.com/video/BV1zz421a7LN) |
| 1005 | - | - | LoRA_05_02_基于GPT-2进行LoRA微调实战 | 10:43 | [link](https://www.bilibili.com/video/BV1KD421G7Sm) |
| 1006 | - | - | LoRA_06_LoRA核心算法实现 | 14:50 | [link](https://www.bilibili.com/video/BV1HU411o7S1) |
| 1007 | - | - | LoRA_07_在VS Code中debug LoRA微调细节 | 15:14 | [link](https://www.bilibili.com/video/BV1zx4y1E7FR) |
| 1008 | - | - | 01 轻松学 PyTorch 简介和安装 | 31:58 | [link](https://www.bilibili.com/video/BV1tk4y1q7Jv) |
| 1009 | - | - | 02 轻松学 PyTorch 初识Tensor | 31:03 | [link](https://www.bilibili.com/video/BV1dp4y1U7mD) |
| 1010 | - | - | 03-1 轻松学 PyTorch 手写字体识别 MNIST (理论) | 13:47 | [link](https://www.bilibili.com/video/BV12i4y1G7ko) |
| 1011 | - | - | 03-2 轻松学 PyTorch 手写字体识别 MNIST ( 实战 - 上 ) | 54:36 | [link](https://www.bilibili.com/video/BV1WT4y177SA) |
| 1012 | - | - | 03-3 轻松学 PyTorch 手写字体识别 MNIST (实战 - 下) | 35:49 | [link](https://www.bilibili.com/video/BV1HK4y1s7j3) |
| 1013 | - | - | 04-1 轻松学PyTorch 肺部感染识别 简介 | 7:29 | [link](https://www.bilibili.com/video/BV1wk4y1B77W) |
| 1014 | - | - | 04-2 轻松学 PyTorch 显示数据集中的图片（2） | 38:09 | [link](https://www.bilibili.com/video/BV1xA411e7oX) |
| 1015 | - | - | 04-3 轻松学 PyTorch 迁移学习，模型微调 | 18:49 | [link](https://www.bilibili.com/video/BV1aZ4y1T7xd) |
| 1016 | - | - | 04-4 轻松学 PyTorch 定义训练函数 | 9:09 | [link](https://www.bilibili.com/video/BV1f5411h7Yj) |
| 1017 | - | - | 04-5 轻松学 PyTorch 定义测试函数 | 9:12 | [link](https://www.bilibili.com/video/BV1si4y137CD) |
| 1018 | - | - | 04-6 轻松学PyTorch 肺部识别案例实现 | 9:47 | [link](https://www.bilibili.com/video/BV1Kf4y197x9) |
| 1019 | - | - | 05-1 Pytorch RNN LSTM MNIST实战案例 | 20:16 | [link](https://www.bilibili.com/video/BV1n54y117KK) |
| 1020 | - | - | 05-2 Pytorch RNN LSTM MNIST实战案例 | 14:39 | [link](https://www.bilibili.com/video/BV19a4y1j77Y) |
| 1021 | - | - | 05-3 Pytorch RNN LSTM MNIST实战案例 | 20:12 | [link](https://www.bilibili.com/video/BV14K411P7u1) |
| 1022 | - | - | 05-4 Pytorch RNN LSTM MNIST实战案例 | 4:32 | [link](https://www.bilibili.com/video/BV1iV411m76r) |
| 1023 | - | - | 05-5 Pytorch RNN LSTM MNIST实战案例 | 6:27 | [link](https://www.bilibili.com/video/BV1Jt4y1q76b) |
| 1024 | - | - | 06-01 PyTorch 基础知识复习-1 | 22:08 | [link](https://www.bilibili.com/video/BV1FV41117gt) |
| 1025 | - | - | 06-02 PyTorch 基础知识复习-2 | 23:17 | [link](https://www.bilibili.com/video/BV11r4y1w7XM) |
| 1026 | - | - | 07-01 经典案例 CIFAR10 图形识别【PyTorch 官网实现】 | 35:59 | [link](https://www.bilibili.com/video/BV1Ta411w78P) |
| 1027 | - | - | 07-02 经典案例 CIFAR10 图像识别【个人实现】 | 33:30 | [link](https://www.bilibili.com/video/BV1Qa411c7JL) |
| 1028 | - | - | 08-01 肺部感染图像识别  -（上集） | 33:23 | [link](https://www.bilibili.com/video/BV1pp4y1r7uB) |
| 1029 | - | - | 08-02 肺部感染图像识别 -（中集） | 19:16 | [link](https://www.bilibili.com/video/BV13A411x7wK) |
| 1030 | - | - | 08-03 肺部感染图像识别 -（下集） | 23:48 | [link](https://www.bilibili.com/video/BV1nK4y1j7sX) |
| 1031 | - | - | 08-04 肺部感染图像识别 -（结果展示） | 2:53 | [link](https://www.bilibili.com/video/BV12t4y1a7LC) |
| 1032 | - | - | 09 迁移学习【图像识别]】基于Flask实现 | 45:54 | [link](https://www.bilibili.com/video/BV1Q54y1z7Ek) |
| 1033 | - | - | 10_PyTorch_情感分类_LSTM实现【上篇】 | 46:37 | [link](https://www.bilibili.com/video/BV1Bi4y157xD) |
| 1034 | - | - | 10 情感分类_Tensorflow_LSTM实现 - 01集 | 27:06 | [link](https://www.bilibili.com/video/BV1UK411u7Jx) |
| 1035 | - | - | 10 情感分类_Tensorflow_LSTM实现 - 02集 | 32:06 | [link](https://www.bilibili.com/video/BV1op4y1z7HK) |
| 1036 | - | - | 11_01_交通指示牌识别_迁移学习 | 21:37 | [link](https://www.bilibili.com/video/BV1tZ4y137mh) |
| 1037 | - | - | 11_02_交通指示牌识别_迁移学习 | 20:34 | [link](https://www.bilibili.com/video/BV1sa4y1p7KQ) |
| 1038 | - | - | 11_03_交通指示牌识别_迁移学习 | 34:36 | [link](https://www.bilibili.com/video/BV1No4y1Z7j1) |
| 1039 | - | - | 11_04_交通指示牌识别_案例优化_识别43个类别 | 48:41 | [link](https://www.bilibili.com/video/BV1sy4y1U7We) |
| 1040 | - | - | 12_01 LSTM 文本生成_字符级 | 11:19 | [link](https://www.bilibili.com/video/BV1Dv411W78n) |
| 1041 | - | - | 12_02 LSTM 文本生成_字符级 | 25:19 | [link](https://www.bilibili.com/video/BV1qv411W7fu) |
| 1042 | - | - | 12_03 LSTM 文本生成_字符级 | 18:31 | [link](https://www.bilibili.com/video/BV11r4y1T73S) |
| 1043 | - | - | 12_04 LSTM 文本生成_字符级 | 27:03 | [link](https://www.bilibili.com/video/BV1bK411u7ba) |
| 1044 | - | - | 13_01 PyTorch LSTM 情感分类【下篇】 | 31:18 | [link](https://www.bilibili.com/video/BV16U4y147dv) |
| 1045 | - | - | 13_02 PyTorch LSTM 情感分类【下篇】 | 22:05 | [link](https://www.bilibili.com/video/BV1Ay4y117yX) |
| 1046 | - | - | 13_03 PyTorch LSTM 情感分类【下篇】 | 36:47 | [link](https://www.bilibili.com/video/BV1wA411u73p) |
| 1047 | - | - | 精讲版-01 线性回归基础知识 | 13:09 | [link](https://www.bilibili.com/video/BV1QJ4m1E7SC) |
| 1048 | - | - | 精讲版-02 生成虚拟样本数据 | 7:38 | [link](https://www.bilibili.com/video/BV1vH4y1V7Gx) |
| 1049 | - | - | 精讲版-03 tensor的基本概念和应用 | 9:17 | [link](https://www.bilibili.com/video/BV1sH4y1g7bU) |
| 1050 | - | - | 精讲版-04 梯度下降法原理讲解 | 16:28 | [link](https://www.bilibili.com/video/BV1FJ4m1T7TN) |
| 1051 | - | - | 精讲版-05 自动梯度计算backward | 5:55 | [link](https://www.bilibili.com/video/BV1XC411E7ap) |
| 1052 | - | - | 精讲版-06 优化器optimizer和损失函数MSELoss | 7:50 | [link](https://www.bilibili.com/video/BV1wr42177ns) |
| 1053 | - | - | 精讲版-07 定义模型类 进行前向传播计算 | 8:07 | [link](https://www.bilibili.com/video/BV1Hz421m7Ag) |
| 1054 | - | - | 精讲版-08 序列模型 Sequential Model | 3:49 | [link](https://www.bilibili.com/video/BV1Jr42177Sa) |
| 1055 | - | - | 精讲版-09 Dataset和DataLoader封装原理和应用 | 10:53 | [link](https://www.bilibili.com/video/BV1Gm421g7Bb) |
| 1056 | - | - | 精讲版-10 模型验证 代码升级 | 6:28 | [link](https://www.bilibili.com/video/BV1nr421j7uw) |
| 1057 | - | - | 精讲版-11 天气预测实战-数据预处理 | 11:38 | [link](https://www.bilibili.com/video/BV1kU411o7Vw) |
| 1058 | - | - | 精讲版-12 天气预测实战-模型搭建 | 8:00 | [link](https://www.bilibili.com/video/BV17z421e77L) |
| 1059 | - | - | 精讲版-13 天气预测实战-模型训练和验证 | 8:15 | [link](https://www.bilibili.com/video/BV1WD421V7U1) |
| 1060 | - | - | 精讲版-14 天气预测实战-模型评估 混淆矩阵 | 6:09 | [link](https://www.bilibili.com/video/BV1JZ421s7sL) |
| 1061 | - | - | DeepSpeed分布式训练框架 DeepSpeed-Chat Step-1-01 简介 | 15:05 | [link](https://www.bilibili.com/video/BV1KV41137tS) |
| 1062 | - | - | DeepSpeed分布式训练框架 DeepSpeed-Chat Step-1-02 actor 模型微调 | 13:12 | [link](https://www.bilibili.com/video/BV1d14y1i7gU) |
| 1063 | - | - | DeepSpeed分布式训练框架 DeepSpeed-Chat Step-1-03 actor 模型评估 | 6:59 | [link](https://www.bilibili.com/video/BV1V8411R77B) |
| 1064 | - | - | DeepSpeed分布式训练框架 DeepSpeed-Chat Step-1-04 actor 模型推理 | 7:06 | [link](https://www.bilibili.com/video/BV1n8411R7gZ) |
| 1065 | - | - | DeepSpeed Chat 05 Step 1 源代码解读之参数配置 | 10:21 | [link](https://www.bilibili.com/video/BV1pN41187ex) |
| 1066 | - | - | DeepSpeed Chat 06 Step 1 源码解读之分布式环境配置 | 11:08 | [link](https://www.bilibili.com/video/BV1oj411z7Vd) |
| 1067 | - | - | DeepSpeed-Chat-07-step1_源码解读_创建 tokenizer 和 model | 11:51 | [link](https://www.bilibili.com/video/BV1br4y1o7jh) |
| 1068 | - | - | DeepSpeed-Chat-08-step1_源码解读_创建LoRA层 | 11:50 | [link](https://www.bilibili.com/video/BV1Vz4y1g7CX) |
| 1069 | - | - | DeepSpeed-Chat-09-step1_源码解读_创建数据集-第1节.mov | 10:03 | [link](https://www.bilibili.com/video/BV13X4y1x7VG) |
| 1070 | - | - | DeepSpeed-Chat-10-step1_源码解读_创建数据集-第2节 | 24:05 | [link](https://www.bilibili.com/video/BV1Hu4y1d7BL) |
| 1071 | - | - | DeepSpeed-Chat-11-step1_源码解读_创建数据集-第3节 | 8:21 | [link](https://www.bilibili.com/video/BV1KP411s7se) |
| 1072 | - | - | DeepSpeed-Chat-12-step1_源码解读_创建数据集-第4节 | 9:55 | [link](https://www.bilibili.com/video/BV1Sh4y1Q7jr) |
| 1073 | - | - | DeepSpeed-Chat-13-step1_源码解读_创建数据集-第5节 | 13:53 | [link](https://www.bilibili.com/video/BV1X94y1k7UF) |
| 1074 | - | - | DeepSpeed-Chat-14-step1_源码解读_创建数据集-第6节 | 4:21 | [link](https://www.bilibili.com/video/BV1Mp4y137xT) |
| 1075 | - | - | DeepSpeed-Chat-15-step1_源码解读_创建优化器和调度器 | 11:06 | [link](https://www.bilibili.com/video/BV1Z44y1c7eE) |
| 1076 | - | - | DeepSpeed-Chat-16-step1_源码解读_deepspeed初始化 | 7:41 | [link](https://www.bilibili.com/video/BV1PN41167xq) |
| 1077 | - | - | DeepSpeed-Chat-17-step1_源码解读_模型训练和验证 | 8:38 | [link](https://www.bilibili.com/video/BV1tr4y1d7GL) |
| 1078 | - | - | DeepSpeed-Chat-18-step1_源码解读_模型保存-第1节 | 12:03 | [link](https://www.bilibili.com/video/BV1AF41117HY) |
| 1079 | - | - | DeepSpeed-Chat-19-step1_源码解读_模型保存-第2节 | 3:31 | [link](https://www.bilibili.com/video/BV1Eh4y1S79Z) |
| 1080 | - | - | DeepSpeed-Chat-20-step1_源码解读_模型保存-第3节 | 9:08 | [link](https://www.bilibili.com/video/BV18h4y1S7Rn) |
| 1081 | - | - | DeepSpeed-Chat-21-step1_源码解读_模型评估 | 18:03 | [link](https://www.bilibili.com/video/BV1fZ421E7o9) |
| 1082 | - | - | DeepSpeed-Chat-22-step1_源码解读_模型推理-第1节 | 6:04 | [link](https://www.bilibili.com/video/BV1bm421p7GE) |
| 1083 | - | - | DeepSpeed-Chat-23-step1_源码解读_模型推理-第2节 | 5:46 | [link](https://www.bilibili.com/video/BV1yb421h7PB) |
| 1084 | - | - | DeepSpeed-Chat-24-step1_源码解读_模型推理-第3节 | 11:53 | [link](https://www.bilibili.com/video/BV1Xb421Y7ga) |
| 1085 | - | - | DeepSpeed-Chat-25 Step-2-01 简介 | 8:17 | [link](https://www.bilibili.com/video/BV1Dh4y1S7rG) |
| 1086 | - | - | DeepSpeed-Chat-26 Step-2 Reward模型微调和评估 | 9:52 | [link](https://www.bilibili.com/video/BV1z14y1i7hv) |
| 1087 | - | - | Chat-27-step2-源码解读-参数配置和初始化 | 12:28 | [link](https://www.bilibili.com/video/BV1y84y1m7VX) |
| 1088 | - | - | Chat-28-step2-源码解读-创建Reward模型 | 10:59 | [link](https://www.bilibili.com/video/BV1hN411t7pk) |
| 1089 | - | - | Chat-29-step2-源码解读-创建数据集 | 10:46 | [link](https://www.bilibili.com/video/BV14C4y1V7L4) |
| 1090 | - | - | Chat-30-step2-源码解读-参数分组_创建学习率调度器 | 5:51 | [link](https://www.bilibili.com/video/BV1P34y137FB) |
| 1091 | - | - | Chat-31-step2-源码解读-deepspeed初始化 | 2:45 | [link](https://www.bilibili.com/video/BV1Pm4y1G7yf) |
| 1092 | - | - | Chat-32-step2-源码解读-模型评估定义 | 7:57 | [link](https://www.bilibili.com/video/BV1P94y1a7T1) |
| 1093 | - | - | Chat-33-step2-源码解读-Reward模型训练 | 7:02 | [link](https://www.bilibili.com/video/BV1P8411y7EA) |
| 1094 | - | - | Chat-34-step2-源码解读-Reward模型保存 | 4:18 | [link](https://www.bilibili.com/video/BV1FV411c7Cf) |
| 1095 | - | - | Chat-35-step2-源码解读-Reward模型评估 | 11:22 | [link](https://www.bilibili.com/video/BV11H4y1f7X6) |
| 1096 | - | - | Chat-36-step2-源码解读-forward算法-第1节 | 11:58 | [link](https://www.bilibili.com/video/BV1v34y1V7jV) |
| 1097 | - | - | Chat-37-step2-源码解读-forward算法-第2节 | 13:32 | [link](https://www.bilibili.com/video/BV14H4y1f7EB) |
| 1098 | - | - | Chat-38-step2-源码解读-forward算法-第3节 | 5:59 | [link](https://www.bilibili.com/video/BV13m4y1G7mq) |
| 1099 | - | - | Chat-39-step2-源码解读-forward算法-第4节 | 9:47 | [link](https://www.bilibili.com/video/BV1RH4y1f7Dn) |
| 1100 | - | - | 方案1-CIFAR10-01-数据加载和预处理 | 11:45 | [link](https://www.bilibili.com/video/BV1wx4y1r7nn) |
| 1101 | - | - | 方案1-CIFAR10-02-模型定义与超参数创建 | 9:58 | [link](https://www.bilibili.com/video/BV1iC411n79w) |
| 1102 | - | - | 方案1-CIFAR10-03-模型训练和本地保存 | 6:45 | [link](https://www.bilibili.com/video/BV1Jp421Q7Ar) |
| 1103 | - | - | 方案1-CIFAR10-04-模型性能验证 | 16:35 | [link](https://www.bilibili.com/video/BV17z421r7nb) |
| 1104 | - | - | 方案1-CIFAR10-05-基于FastAPI实现推理服务 | 14:22 | [link](https://www.bilibili.com/video/BV12z42167Qd) |
| 1105 | - | - | 方案2-CIFAR10-DeepSpeed-01-超参数定义 | 15:37 | [link](https://www.bilibili.com/video/BV1Mt421A7Lj) |
| 1106 | - | - | 方案2-CIFAR10-DeepSpeed-02-模型结构定义 | 15:35 | [link](https://www.bilibili.com/video/BV19w4m1275e) |
| 1107 | - | - | 方案2-CIFAR10-DeepSpeed-03-模型分布式训练 | 7:13 | [link](https://www.bilibili.com/video/BV1u1421R78i) |
| 1108 | - | - | 方案2-CIFAR10-DeepSpeed-04-模型性能验证 | 9:03 | [link](https://www.bilibili.com/video/BV1DH4y1A785) |
| 1109 | - | - | 方案2-CIFAR10-DeepSpeed-05-配置文件参数讲解 | 8:54 | [link](https://www.bilibili.com/video/BV1dF4m1w7WQ) |
| 1110 | - | - | 方案2-CIFAR10-DeepSpeed-06-模型分布式训练 | 12:17 | [link](https://www.bilibili.com/video/BV1tt421A7Pd) |
| 1111 | - | - | OpenAI assistant API 学习指南-简介 | 22:55 | [link](https://www.bilibili.com/video/BV1Wj411j7mn) |
| 1112 | - | - | OpenAI assistant API 学习指南-assistant运行原理 | 22:17 | [link](https://www.bilibili.com/video/BV1oN411777P) |
| 1113 | - | - | LangChain 实战案例-01 基于上传的PDF文档进行QA问答 第1节 项目简介 | 9:55 | [link](https://www.bilibili.com/video/BV1fp4y137US) |
| 1114 | - | - | LangChain 实战案例-01 基于上传PDF文档进行QA问答 第2节 案例实现 | 22:33 | [link](https://www.bilibili.com/video/BV1rk4y1g7Gd) |
| 1115 | - | - | LangChain 教程 实战案例-01 基于上传PDF文档进行QA问答 第3节 向量数据库 | 15:13 | [link](https://www.bilibili.com/video/BV1294y1C7Cd) |
| 1116 | - | - | LangChain 实战案例-01 基于上传PDF文档进行QA问答 第4节 基于Gradio实现QA交互 | 32:09 | [link](https://www.bilibili.com/video/BV1rN41187Q9) |
| 1117 | - | - | Chinese LLaMA Alpaca 案例实战-01-项目概览 | 7:34 | [link](https://www.bilibili.com/video/BV1Mh4y187ir) |
| 1118 | - | - | Chinese- LLaMA- Alpaca 案例实战-02-指令数据生成 | 10:58 | [link](https://www.bilibili.com/video/BV1ns4y1g717) |
| 1119 | - | - | 案例实战-03-Chinese-LLaMA-AIpaca模型本地部署 | 12:39 | [link](https://www.bilibili.com/video/BV1xz4y18749) |
| 1120 | - | - | 案例实战-04-基于webUI进行交互 | 9:43 | [link](https://www.bilibili.com/video/BV1im4y1h7wo) |
| 1121 | - | - | 案例实战-05-基于LLaMA和LoRA模型进行预训练 | 20:30 | [link](https://www.bilibili.com/video/BV1f8411o73g) |
| 1122 | - | - | 案例实战-06-上集—基于LLaMA和LoRA模型进行指令精调 | 16:50 | [link](https://www.bilibili.com/video/BV1eX4y187nN) |
| 1123 | - | - | 案例实战-07-下集-基于LLaMA和LoRA模型进行指令精调 | 13:49 | [link](https://www.bilibili.com/video/BV1mP411D7bm) |
| 1124 | - | - | 案例实战-08-LLaMA与LangChain进行集成 | 19:33 | [link](https://www.bilibili.com/video/BV1Ph4y137JW) |
| 1125 | - | - | 案例实战-09-剧透-使用 FastAPI 实现 LLaMA API服务 | 10:50 | [link](https://www.bilibili.com/video/BV1vh4y1X7D6) |
| 1126 | - | - | 案例实战-10-LLaMA tokenizer模型与中文tokenizer模型合并操作 | 5:51 | [link](https://www.bilibili.com/video/BV1hh4y1M7YE) |
| 1127 | - | - | 案例实战-11-单个LoRA权重与LLaMA合并 | 25:00 | [link](https://www.bilibili.com/video/BV15h4y1M7MU) |
| 1128 | - | - | 案例实战-12-多个LoRA权重与LLaMA合并 | 8:55 | [link](https://www.bilibili.com/video/BV1KV4y117ci) |
| 1129 | - | - | 案例实战-13-指令精调手把手教程-升级版 | 16:32 | [link](https://www.bilibili.com/video/BV1Qu411t7ML) |
| 1130 | - | - | 案例实战-14-基于llama.cpp量化模型部署 | 13:53 | [link](https://www.bilibili.com/video/BV1Y14y1d75g) |
| 1131 | - | - | 案例实战-15-使用 privateGPT 进行多文档问答 | 14:07 | [link](https://www.bilibili.com/video/BV1Wm4y1Y7G3) |
| 1132 | - | - | 案例实战-16-llama.cpp量化模型GPU加速推理 | 14:40 | [link](https://www.bilibili.com/video/BV1314y1o7dS) |
| 1133 | - | - | 案例实战-17-llama.cpp量化模型API服务部署 | 13:58 | [link](https://www.bilibili.com/video/BV1kz4y1E7ha) |
| 1134 | - | - | 源码讲解-01-中文词汇表扩充 | 9:33 | [link](https://www.bilibili.com/video/BV1Es4y1g7uu) |
| 1135 | - | - | 源码讲解-02-llama与lora模型合并 | 14:35 | [link](https://www.bilibili.com/video/BV1rX4y187Wb) |
| 1136 | - | - | 源码讲解-03-基于llama模型进行推理 | 13:31 | [link](https://www.bilibili.com/video/BV1a24y1K79a) |
| 1137 | - | - | 源码讲解-04-上集-模型预训练代码逐行剖析 | 22:30 | [link](https://www.bilibili.com/video/BV18X4y187ss) |
| 1138 | - | - | 源码讲解-05-中集-模型预训练代码逐行剖析 | 20:46 | [link](https://www.bilibili.com/video/BV1wo4y1g7DF) |
| 1139 | - | - | 源码讲解-06-下集-模型预训练代码逐行剖析 | 24:41 | [link](https://www.bilibili.com/video/BV1S8411o78y) |
| 1140 | - | - | 源码讲解-07-上集-API服务server代码讲解 | 21:58 | [link](https://www.bilibili.com/video/BV1N14y1D7eT) |
| 1141 | - | - | 源码讲解-08-下集-API服务server代码讲解 | 17:41 | [link](https://www.bilibili.com/video/BV13k4y1H7Ck) |
| 1142 | - | - | 01_模型推理与部署专题简介 | 1:12 | [link](https://www.bilibili.com/video/BV1HY411r7fc) |
| 1143 | - | - | 02_TensorRT与Triton容器部署 | 15:35 | [link](https://www.bilibili.com/video/BV1h24y1n7ws) |
| 1144 | - | - | 03_TensorFlow模型转换TensorRT引擎推理 | 13:30 | [link](https://www.bilibili.com/video/BV1124y1b7Le) |
| 1145 | - | - | 04_Pytorch模型转换为TensorRT引擎推理 | 9:10 | [link](https://www.bilibili.com/video/BV1yg4y1t71M) |
| 1146 | - | - | 05_tensorflow_serving_模型部署与推理_mnist分类案例 | 13:58 | [link](https://www.bilibili.com/video/BV1iT411a7GU) |
| 1147 | - | - | 06_tensorflow_serving_单个模型部署与推理_线性回归 | 11:56 | [link](https://www.bilibili.com/video/BV1WY411B7Yh) |
| 1148 | - | - | 07_tensorflow_serving_多个模型部署与推理_模型迭代 | 14:36 | [link](https://www.bilibili.com/video/BV1x54y1M7Es) |
| 1149 | - | - | 08_torch_serving_docker环境部署 | 6:38 | [link](https://www.bilibili.com/video/BV19N411N73R) |
| 1150 | - | - | 09_torch_serving_案例1-序列分类 | 9:15 | [link](https://www.bilibili.com/video/BV18g4y1W7BD) |
| 1151 | - | - | 10_torch_serving_案例2-QA问答 | 12:33 | [link](https://www.bilibili.com/video/BV1vN411K7Bf) |
| 1152 | - | - | 轻松学·Streamlit_01_专题简介 | 8:41 | [link](https://www.bilibili.com/video/BV1EY4y1Z7No) |
| 1153 | - | - | 轻松学·Streamlit_02_基础功能探索 | 18:23 | [link](https://www.bilibili.com/video/BV1Q3411Z76n) |
| 1154 | - | - | 轻松学·Streamlit_03_基础功能探索 | 10:28 | [link](https://www.bilibili.com/video/BV1624y1h78E) |
| 1155 | - | - | 轻松学·Streamlit_04_基础功能探索 | 14:23 | [link](https://www.bilibili.com/video/BV1jv4y117zn) |
| 1156 | - | - | 轻松学·Streamlit_05_基础功能探索 | 8:07 | [link](https://www.bilibili.com/video/BV16G4y1w7td) |
| 1157 | - | - | 轻松学·Streamlit_06_基础功能探索 | 14:56 | [link](https://www.bilibili.com/video/BV1s3411d7QA) |
| 1158 | - | - | 轻松学·Streamlit_07_动物图片识别 APP | 13:37 | [link](https://www.bilibili.com/video/BV1Cx4y137xK) |
| 1159 | - | - | 轻松学·Streamlit_08_音频转文本 APP | 13:28 | [link](https://www.bilibili.com/video/BV1z14y1M7J1) |
| 1160 | - | - | 轻松学·Streamlit_09_ML分类案例 APP | 26:28 | [link](https://www.bilibili.com/video/BV1g24y1h7FK) |
| 1161 | - | - | 01_ES 概念、核心理论部分 | 8:39 | [link](https://www.bilibili.com/video/BV1Ta411q73R) |
| 1162 | - | - | 02_ES 基础操作快速入门 | 17:57 | [link](https://www.bilibili.com/video/BV1S5411U754) |
| 1163 | - | - | 03_ES python API基础操作入门 | 22:16 | [link](https://www.bilibili.com/video/BV1hY411E7iA) |
| 1164 | - | - | 04_ES 文本相似性计算 | 15:14 | [link](https://www.bilibili.com/video/BV1uZ4y127Lv) |
| 1165 | - | - | 进阶学·ES-02-01 理论知识 | 11:49 | [link](https://www.bilibili.com/video/BV1Dd4y1i7qW) |
| 1166 | - | - | 进阶学·ES-02-02 理论知识 | 9:56 | [link](https://www.bilibili.com/video/BV1de4y1U7JZ) |
| 1167 | - | - | 进阶学·ES-03-01 索引操作 | 14:04 | [link](https://www.bilibili.com/video/BV1J14y177sH) |
| 1168 | - | - | 进阶学·ES-03-02 映射操作-1 | 14:01 | [link](https://www.bilibili.com/video/BV1dt4y1c7Be) |
| 1169 | - | - | 进阶学·ES-03-02 映射操作-2 | 21:47 | [link](https://www.bilibili.com/video/BV19D4y1k7uw) |
| 1170 | - | - | 进阶学·ES-03-02 映射操作-3 | 16:11 | [link](https://www.bilibili.com/video/BV1Ee4y1q7oT) |
| 1171 | - | - | 进阶学·ES-03-02 映射操作-4 | 14:15 | [link](https://www.bilibili.com/video/BV1Y8411W7o2) |
| 1172 | - | - | 进阶学·ES-03-03 文档操作 | 18:50 | [link](https://www.bilibili.com/video/BV1J8411W7f6) |
| 1173 | - | - | 进阶学ES 03-04 ES基于python API实践-1 | 15:32 | [link](https://www.bilibili.com/video/BV1Ce4y1q7Ne) |
| 1174 | - | - | 进阶学ES 03-04 ES基于python API实践-2 | 18:37 | [link](https://www.bilibili.com/video/BV12d4y1i7QU) |
| 1175 | - | - | 进阶学·ES-04-01 analyzer简介 | 13:02 | [link](https://www.bilibili.com/video/BV1SV4y1L77u) |
| 1176 | - | - | 进阶学·ES-04-02 analyzer应用 | 13:20 | [link](https://www.bilibili.com/video/BV1g84y1z7SM) |
| 1177 | - | - | 进阶学·ES-04-03 analyzer IK分词器-自定义词典 | 13:31 | [link](https://www.bilibili.com/video/BV16N4y1c7VW) |
| 1178 | - | - | 进阶学·ES-04-04 analyzer IK分词器-同义词-上集 | 13:23 | [link](https://www.bilibili.com/video/BV1qe411L7SJ) |
| 1179 | - | - | 进阶学·ES-04-05 analyzer IK分词器-同义词-下集 | 8:24 | [link](https://www.bilibili.com/video/BV1mG4y1p75R) |
| 1180 | - | - | 进阶学·ES-04-06 analyzer IK分词器-停用词 | 17:39 | [link](https://www.bilibili.com/video/BV1i14y177tV) |
| 1181 | - | - | 进阶学·ES-04-07 analyzer IK分词器-拼音搜索 | 5:16 | [link](https://www.bilibili.com/video/BV1BK411Q7YP) |
| 1182 | - | - | 进阶学·ES-04-08 ES辅助功能 | 23:00 | [link](https://www.bilibili.com/video/BV1Ee4y1i77Q) |
| 1183 | - | - | 进阶学·ES-04-09 ES布尔查询 | 10:11 | [link](https://www.bilibili.com/video/BV1ZW4y1J77a) |
| 1184 | - | - | 进阶学·ES-04-10 ES全文搜索 | 13:18 | [link](https://www.bilibili.com/video/BV17e411V7ec) |
| 1185 | - | - | 进阶学·ES-04-11 ES搜索排序 | 14:29 | [link](https://www.bilibili.com/video/BV19V4y1V7ge) |
| 1186 | - | - | mysql_01_课程简介 | 2:59 | [link](https://www.bilibili.com/video/BV1e14y187iC) |
| 1187 | - | - | mysql_02_基本操作 | 8:07 | [link](https://www.bilibili.com/video/BV13t4y1A7HN) |
| 1188 | - | - | mysql_03_数据表的增删改 | 5:57 | [link](https://www.bilibili.com/video/BV1TV4y1K7S6) |
| 1189 | - | - | mysql_04_01_数据查询 | 13:18 | [link](https://www.bilibili.com/video/BV15T411P7rC) |
| 1190 | - | - | mysql_04_02_数据查询 | 13:43 | [link](https://www.bilibili.com/video/BV13e411j7M6) |
| 1191 | - | - | mysql_05_01_存储过程 | 12:18 | [link](https://www.bilibili.com/video/BV1eG4y1W7H5) |
| 1192 | - | - | mysql_05_02_存储过程 | 8:34 | [link](https://www.bilibili.com/video/BV1Te4y1z78C) |
| 1193 | - | - | mysql_06_01_索引 | 6:25 | [link](https://www.bilibili.com/video/BV1NN4y1N7Mc) |
| 1194 | - | - | mysql_06_02 索引 | 7:02 | [link](https://www.bilibili.com/video/BV1fV4y1N7eV) |
| 1195 | - | - | mysql_07_python与mysql教程 | 27:59 | [link](https://www.bilibili.com/video/BV17G411n7q6) |
| 1196 | - | - | mysql_08_pandas与mysql教程 | 9:24 | [link](https://www.bilibili.com/video/BV1kG4y1W7J7) |
| 1197 | - | - | 自然语言处理快速入门 01-BERT及其变种的原理 | 18:16 | [link](https://www.bilibili.com/video/BV1RP4y1t7sc) |
| 1198 | - | - | 02-BERT及其变种的原理 | 8:17 | [link](https://www.bilibili.com/video/BV1d44y1x7tP) |
| 1199 | - | - | 03-BERT及其变种的原理 | 3:59 | [link](https://www.bilibili.com/video/BV12r4y1y7PS) |
| 1200 | - | - | 04-BERT及其变种的原理 | 3:43 | [link](https://www.bilibili.com/video/BV19F411Y7ER) |
| 1201 | - | - | 05-BERT及其变种的原理 | 4:36 | [link](https://www.bilibili.com/video/BV1zr4y1y72v) |
| 1202 | - | - | 06-BERT入门二分类案例 自然语言处理快速入门 | 35:18 | [link](https://www.bilibili.com/video/BV1SP4y137Pp) |
| 1203 | - | - | 07-基于RoBERTa训练一个MLM掩码语言模型 | 29:18 | [link](https://www.bilibili.com/video/BV1gF411z78D) |
| 1204 | - | - | 08_一_基于BiLSTM和BERT实现分类任务 | 15:23 | [link](https://www.bilibili.com/video/BV1wb4y1i7hU) |
| 1205 | - | - | 09_二_基于BiLSTM和BERT实现分类任务 | 17:40 | [link](https://www.bilibili.com/video/BV1uR4y137JG) |
| 1206 | - | - | 10_三_基于BiLSTM和BERT实现分类任务 | 12:42 | [link](https://www.bilibili.com/video/BV1UP4y1J7yr) |
| 1207 | - | - | 11_四_基于BiLSTM和BERT实现分类任务 | 21:14 | [link](https://www.bilibili.com/video/BV17q4y117YB) |
| 1208 | - | - | 01_TensorFlow 2.0 分类案例【银行客户流失预测】官网+个人实现 | 40:56 | [link](https://www.bilibili.com/video/BV1f44y1z7XF) |
| 1209 | - | - | 02_TensorFlow 2.0 鲜花分类 官网案例详解 + 优化 | 32:03 | [link](https://www.bilibili.com/video/BV1cf4y187PE) |
| 1210 | - | - | 03_TensorFlow 2.0 迁移学习_案例1_基于预训练模型进行目标分类 | 22:16 | [link](https://www.bilibili.com/video/BV1oB4y1T7qL) |
| 1211 | - | - | 04-1_TensorFlow 2.0 迁移学习_案例2_上集_宠物狗品种识别 | 28:35 | [link](https://www.bilibili.com/video/BV1b44y167ca) |
| 1212 | - | - | 04-2_TensorFlow 2.0 迁移学习_案例2_下集_宠物狗品种识别 | 39:04 | [link](https://www.bilibili.com/video/BV19B4y1T7eP) |
| 1213 | - | - | 05_TensorFlow 2.0 回归案例 葡萄酒品质预测 | 38:12 | [link](https://www.bilibili.com/video/BV1F64y1r7Ub) |
| 1214 | - | - | 06_TensorFlow 2.0 基于LSTM进行文本生成（字符级） | 41:53 | [link](https://www.bilibili.com/video/BV1ko4y1k7Lo) |
| 1215 | - | - | 07_TensorFlow 2.0 基于LSTM单变量预测_电力消耗案例 | 51:01 | [link](https://www.bilibili.com/video/BV1f5411K7qD) |
| 1216 | - | - | 08_TensorFlow 2.0 基于LSTM多变量_共享单车使用量预测 | 48:39 | [link](https://www.bilibili.com/video/BV1y5411K7NR) |
| 1217 | - | - | 09_基于Embedding进行IMDB情感文本分类（上集） | 20:17 | [link](https://www.bilibili.com/video/BV19y4y1M7p5) |
| 1218 | - | - | 09_基于Embedding进行IMDB情感文本分类（下集） | 31:16 | [link](https://www.bilibili.com/video/BV1X64y197KS) |
| 1219 | - | - | 10-01 OCR入门案例_手写字体识别 | 11:28 | [link](https://www.bilibili.com/video/BV1tX4y1w751) |
| 1220 | - | - | 10-02 OCR入门案例_手写字体识别 | 44:06 | [link](https://www.bilibili.com/video/BV1EB4y1N7oz) |
| 1221 | - | - | 10-03 OCR入门案例_手写字体识别 | 16:25 | [link](https://www.bilibili.com/video/BV1oh411h7oy) |
| 1222 | - | - | 11_01 OCR 图片去噪 | 12:29 | [link](https://www.bilibili.com/video/BV1H54y1E7yv) |
| 1223 | - | - | 11_02 OCR 图片去噪 | 2:28 | [link](https://www.bilibili.com/video/BV1TX4y1A7fN) |
| 1224 | - | - | 11_03 OCR 图片去噪 | 16:14 | [link](https://www.bilibili.com/video/BV1Tf4y1j7PU) |
| 1225 | - | - | 11_04 OCR 图片去噪 | 5:48 | [link](https://www.bilibili.com/video/BV1L64y1z7yV) |
| 1226 | - | - | 11_05 OCR 图片去噪 | 10:51 | [link](https://www.bilibili.com/video/BV1bb4y1k75f) |
| 1227 | - | - | 12_TensorFlow 2.0 多分类案例 CIFAR10【官网 + 个人实现】 | 37:24 | [link](https://www.bilibili.com/video/BV1UK4y1X7dM) |
| 1228 | - | - | 01_轻松学Python_python语言简介和工具安装 | 14:13 | [link](https://www.bilibili.com/video/BV1Pg4y1q7BZ) |
| 1229 | - | - | 02 轻松学python 变量 | 16:19 | [link](https://www.bilibili.com/video/BV1Qi4y1s7EW) |
| 1230 | - | - | 03 轻松学python 数字类型 | 4:35 | [link](https://www.bilibili.com/video/BV1CT4y1E7fE) |
| 1231 | - | - | 04 轻松学python 运算符 | 9:52 | [link](https://www.bilibili.com/video/BV1854y1Q7ai) |
| 1232 | - | - | 05 轻松学python 字符串 | 39:30 | [link](https://www.bilibili.com/video/BV1vz411i726) |
| 1233 | - | - | 06 轻松学python 列表 | 27:46 | [link](https://www.bilibili.com/video/BV1vz4y197hL) |
| 1234 | - | - | 07 轻松学python 元组 | 18:43 | [link](https://www.bilibili.com/video/BV1xV411r7Gu) |
| 1235 | - | - | 08 轻松学python 字典 | 25:54 | [link](https://www.bilibili.com/video/BV1ki4y1s7TG) |
| 1236 | - | - | 09 轻松学python 集合 | 13:48 | [link](https://www.bilibili.com/video/BV1Lv41167zH) |
| 1237 | - | - | 10 轻松学python if条件判断语句 | 17:17 | [link](https://www.bilibili.com/video/BV16z411i7iY) |
| 1238 | - | - | 11 轻松学python while循环语句 | 22:27 | [link](https://www.bilibili.com/video/BV1RK4y1x7CQ) |
| 1239 | - | - | 12 轻松学python for循环语句 | 19:07 | [link](https://www.bilibili.com/video/BV1ET4y1J7GV) |
| 1240 | - | - | 13 轻松学python 迭代器 | 19:17 | [link](https://www.bilibili.com/video/BV11Z4y1H7zU) |
| 1241 | - | - | 14 轻松学 python range zip enumerate 内置函数 | 24:27 | [link](https://www.bilibili.com/video/BV1NK411W72q) |
| 1242 | - | - | 15 轻松学 python 列表推导 | 10:45 | [link](https://www.bilibili.com/video/BV1zz4y1Q7zo) |
| 1243 | - | - | 16-1 轻松学 Python 类 ( 第一节 ) | 17:32 | [link](https://www.bilibili.com/video/BV1qK4y1478J) |
| 1244 | - | - | 16-2 轻松学 Python 类 继承 多态 ( 第二节 ) | 33:10 | [link](https://www.bilibili.com/video/BV1Tz4y1X72S) |
| 1245 | - | - | 16-3 轻松学 Python 类 运算符重载 ( 第三节 ) | 38:52 | [link](https://www.bilibili.com/video/BV1wf4y1R7tw) |
| 1246 | - | - | 01_轻松学OpenCV_简介 | 15:40 | [link](https://www.bilibili.com/video/BV1Ji4y1x7vJ) |
| 1247 | - | - | 02_轻松学OpenCV_图像基础 | 31:58 | [link](https://www.bilibili.com/video/BV1eg4y1i7P6) |
| 1248 | - | - | 03 轻松学 OpenCV argparse模块 | 15:41 | [link](https://www.bilibili.com/video/BV1fK411H7bf) |
| 1249 | - | - | 04 轻松学 OpenCV 读取图片 | 20:02 | [link](https://www.bilibili.com/video/BV1uT4y1J7iV) |
| 1250 | - | - | 05 轻松学 OpenCV 读取_处理_保存图片 | 14:51 | [link](https://www.bilibili.com/video/BV1St4y1X7Lq) |
| 1251 | - | - | 06 轻松学 OpenCV 从摄像头读取视频 | 22:14 | [link](https://www.bilibili.com/video/BV1gg4y1v7jt) |
| 1252 | - | - | 07 轻松学 OpenCV 从视频文件读取内容 | 12:01 | [link](https://www.bilibili.com/video/BV19Z4y1H7GH) |
| 1253 | - | - | 08 轻松学OpenCV 保存摄像头读取到的视频内容 | 28:17 | [link](https://www.bilibili.com/video/BV1EV411k78q) |
| 1254 | - | - | 09 轻松学OpenCV 图像的8种变换 | 53:37 | [link](https://www.bilibili.com/video/BV1oK4y1x7PH) |
| 1255 | - | - | 10 轻松学 OpenCV 灰度直方图 | 41:48 | [link](https://www.bilibili.com/video/BV14i4y1x797) |
| 1256 | - | - | 11 轻松学 OpenCV 灰度直方图 ( 补充知识点 ) | 17:07 | [link](https://www.bilibili.com/video/BV1dK411p7cu) |
| 1257 | - | - | 12 轻松学 OpenCV mask | 24:33 | [link](https://www.bilibili.com/video/BV1EZ4y1H7bB) |
| 1258 | - | - | 13 轻松学 OpenCV 彩色直方图 | 25:12 | [link](https://www.bilibili.com/video/BV17k4y1z7L3) |
| 1259 | - | - | 14 轻松学 OpenCV 画出基本图形 | 24:58 | [link](https://www.bilibili.com/video/BV1xK4y147Mk) |
| 1260 | - | - | 15 轻松学 OpenCV 图片上显示文本 | 12:12 | [link](https://www.bilibili.com/video/BV1DD4y1D7Hw) |
| 1261 | - | - | 16 轻松学 OpenCV 人脸检测基于Haar级联 | 47:11 | [link](https://www.bilibili.com/video/BV18z411e7VJ) |
| 1262 | - | - | 17-1 轻松学 OpenCV 基于dlib在图片上进行人脸检测 | 22:37 | [link](https://www.bilibili.com/video/BV1PK411W7pF) |
| 1263 | - | - | 17-2 轻松学 OpenCV 基于dlib通过摄像头进行实时人脸检测 | 14:38 | [link](https://www.bilibili.com/video/BV11Z4y1H7aS) |
| 1264 | - | - | 18-1 轻松学 OpenCV  基于dlib进行人脸关键点检测( 图片 ) | 26:07 | [link](https://www.bilibili.com/video/BV1Bk4y1z7rE) |
| 1265 | - | - | 18-2 轻松学OpenCV 基于dlib进行人脸关键点检测 (摄像头) | 16:48 | [link](https://www.bilibili.com/video/BV19A411v7QS) |
| 1266 | - | - | 18-3 轻松学OpenCV 基于face_recognition进行人脸关键点检测 | 29:58 | [link](https://www.bilibili.com/video/BV1ez4y1Q7sD) |
| 1267 | - | - | 19-1 轻松学OpenCV 基于dlib进行人脸跟踪 | 19:18 | [link](https://www.bilibili.com/video/BV1pK4y147Fj) |
| 1268 | - | - | 19-2 轻松学OpenCV 基于dlib进行人脸跟踪(补充) | 15:29 | [link](https://www.bilibili.com/video/BV1Pz4y1R7iB) |
| 1269 | - | - | 19-3 轻松学OpenCV 基于dlib进行目标跟踪 | 38:44 | [link](https://www.bilibili.com/video/BV1cv411B7yN) |
| 1270 | - | - | 20-1 轻松学OpenCV 基于dlib进行人脸识别( 图片检测 ） | 61:17 | [link](https://www.bilibili.com/video/BV1DZ4y1H7RM) |
| 1271 | - | - | 20-2 轻松学OpenCV 基于face_recognition进行人脸识别 ( 摄像头 ) | 43:51 | [link](https://www.bilibili.com/video/BV1h5411Y7d8) |
| 1272 | - | - | 【极速入门】DeepSeek Harness上手实战指南！架构原理、项目实操、插件开发全栈精讲！赠全套知识库、Skills、桌面端应用与插件管理器！ | 135:02 | [link](https://www.bilibili.com/video/BV1tTbk6zE4C) |
| 1273 | - | - | 从零手搓工业级知识库！DeepSeek Harness智能体开发实战！Skills+插件+Agent预设全栈精讲，Agent设计、开发、部署、优化全流程实操！ | 141:14 | [link](https://www.bilibili.com/video/BV1Hf8A6sEbN) |
| 1274 | - | - | 用好插件，性能暴涨！多Agent系统+永久记忆+提示优化+OpenDesign+TUI等，10大必装插件助你的DeepSeek Harness如虎添翼！ | 12:17 | [link](https://www.bilibili.com/video/BV1eU836PEkF) |
| 1275 | - | - | 桌面端+插件商店+视觉增强，DeepSeek Harness Studio开源上线！一键选配管理插件，原生视觉能力增强，自动版本更新，0代码彻底掌控DSH！ | 3:26 | [link](https://www.bilibili.com/video/BV19Hb16dExu) |
| 1276 | - | - | DeepSeek Harness上手流程+入门导读！国产版Codex&Claude Code重磅开源！ | 8:43 | [link](https://www.bilibili.com/video/BV1P9gs6zEpz) |
| 1277 | - | - | 保姆级DeepSeek Harness部署与上手指南！DeepSeek版Codex&Claude Code，DSH完整部署&使用&调用&开发流程详解！ | 4:59 | [link](https://www.bilibili.com/video/BV1hfgW6jEVr) |
| 1278 | - | - | 架构解读+部署上手+插件使用，DeepSeek Harness全方位深度解析！基座性能持平Codex，高度灵活插件系统定义下一代Agent开发范式！ | 9:23 | [link](https://www.bilibili.com/video/BV1Lyuf6SETd) |
| 1279 | - | - | 效率翻倍，效果追平！DeepSeek Harness VS Codex，Agent性能全方位深度对比评测！ | 6:19 | [link](https://www.bilibili.com/video/BV1gduf6GEbZ) |
| 1280 | - | - | 0代码+配视觉！DeepSeek Harness桌面版安装使用，自带视觉增强与背景切换，保姆级上手使用流程详解！ | 46:22 | [link](https://www.bilibili.com/video/BV1aPgK6cEgj) |
| 1281 | - | - | 顶级体验！DeepSeek V4 Vision多模态模型介绍与效果实测！DeepSeek V4-Flash-Vision-Exp重磅发布！ | 6:15 | [link](https://www.bilibili.com/video/BV1sh8i6XE49) |
| 1282 | - | - | Token自由！单卡5090部署满血DeepSeek V4 Flash！32G显存运行Opus 4.8级大模型，FreeToken项目CPU+GPU混合推实战！ | 7:19 | [link](https://www.bilibili.com/video/BV1BuhG6CEjD) |
| 1283 | - | - | DeepSeek-V4-Pro正式版深度评测！11项工业场景全方位测评，Agentic Coding、前端审美、物理理解、Agent开发全面追平Fable 5！ | 5:15 | [link](https://www.bilibili.com/video/BV1Q2g76cENE) |
| 1284 | - | - | DeepSeek-V4-Pro正式版接Codex配视觉能力！0代码0网络门槛，Codex App、CLI双端环境实现，多隔离环境切换与配置管理，FF-Codex | 6:17 | [link](https://www.bilibili.com/video/BV1vegL6hEtA) |
| 1285 | - | - | 性能评测+上手解读！DeepSeek-V4-Pro开源新王，Agentic coding&推理&长程工具调用全面硬刚Fable 5！ | 4:34 | [link](https://www.bilibili.com/video/BV1bSgL6nEwR) |
| 1286 | - | - | DeepSeek Harness工作流分享！精美前端开发、AI PPT&视频制作实用工作流实践，Agent预设Preset上手进阶实战！ | 7:34 | [link](https://www.bilibili.com/video/BV1b68d6EEhG) |
| 1287 | - | - | 【面试八股】大模型微调与RAG该如何选？面试满分回答模板+底层原理精讲，直接背！秋招求职必备！ | 6:17 | [link](https://www.bilibili.com/video/BV12bYszLEY5) |
| 1288 | - | - | 【面试八股】如何估算大模型微调所需硬件？一个公式搞定！附面试满分答案模板 / MOE架构模型 / 微调预算有限如何分配资源 | 6:47 | [link](https://www.bilibili.com/video/BV19WeAzAEPJ) |
| 1289 | - | - | 【面试八股】PPO与GRPO算法原理对比分析，大模型强化学习微调必考，2步做出满分答卷，拿下高薪offer！ / 强化学习算法原理 / 高效微调算法原理 | 7:48 | [link](https://www.bilibili.com/video/BV1MGeVzHEB4) |
| 1290 | - | - | 【面试八股】如何进行多机多卡大模型微调？分布式训练满分答卷，让你的offer率提升80%！ / DeepSpeed / PyTorch Distributed | 6:22 | [link](https://www.bilibili.com/video/BV1xCY9zbE6b) |
| 1291 | - | - | 【面试八股】如何进行大模型多模态微调？10+算法工程经验分享，你也能写出满分答案！ / LoRA / QLoRA / 高效微调 | 4:30 | [link](https://www.bilibili.com/video/BV1hdebzTE3g) |
| 1292 | - | - | 【面试八股】专业领域微调数据集如何准备？11步工程化构建环节，适配面试 & 企业项目落地！/ 数据预处理 / 微调效果评估 | 6:45 | [link](https://www.bilibili.com/video/BV1RmebzkEyV) |
| 1293 | - | - | 【面试八股】如何评估大模型微调效果？人工+自动化评估，面试官听完点头的企业级评估方案！ / 构建模型评估数据集 / EvalScope自动构建数据集 | 5:25 | [link](https://www.bilibili.com/video/BV1h5ebzKEbA) |
| 1294 | - | - | 【面试八股】Qwen3的GSPO算法原理是什么？国产T0大模型核心技术精讲，0基础也能手撕前沿算法 / GRPO VS GSPO / PPO长度归一化 | 7:35 | [link](https://www.bilibili.com/video/BV1tNh1zvEnX) |
| 1295 | - | - | 【面试八股】如何通过微调提升Agent性能？Claude Code也在用的技术思路，自动化生成最优工具调用策略 / 指令微调 / 强化学习 / 奖励函数设计 | 5:18 | [link](https://www.bilibili.com/video/BV1ChhyzZEDv) |
| 1296 | - | - | 真神还是造假？GPT-5 VS Claude 4.1编程性能对比评测！全网首发GPT-5工业级实战性能评测，代码能力&Agent性能全方位深度测评！ | 10:28 | [link](https://www.bilibili.com/video/BV1kLtmzREMr) |
| 1297 | - | - | GPT-5深度解读与性能评测！编程&Agent性能全面超越Claude 4.1？实测&揭秘地表最强大模型核心功能特性！ | 10:51 | [link](https://www.bilibili.com/video/BV18YtCzoEue) |
| 1298 | - | - | GPT-5发布会4分钟速览！定价、性能…一次看完！GPT-5你需要知道的都在这了 | 6:35 | [link](https://www.bilibili.com/video/BV1ggtkz9EKs) |
| 1299 | - | - | LangGraph&LangChain智能体开发极速入门！前端对话+NL2SQL+Python代码解释器，前后端分离部署+运行状态实时追踪全流程实战！ | 11:52 | [link](https://www.bilibili.com/video/BV1Nx38zMEyi) |
| 1300 | - | - | 工业级智能体开发实践，LangChain从零入门与智能体开发实战！RAG知识库检索、MCP智能体开发、数据分析智能体搭建全领域实战！从零学会LangChain！ | 325:10 | [link](https://www.bilibili.com/video/BV1pYKgzAE5C) |
| 1301 | - | - | 超越LangChain！LangGraph快速入门与智能体开发实战！工业级智能体开发、部署、运维、前端对话全流程实践，NL2SQL、Python代码解释器开发！ | 275:01 | [link](https://www.bilibili.com/video/BV1Kx3CzyE6Q) |
| 1302 | - | - | 最热门智能体开发技术栈，最低零代码开发企业级Agent！LangChain&LangGraph+MCP技术实战，双向MCP接入与封装双向开发实践！ | 142:37 | [link](https://www.bilibili.com/video/BV1bzMdzkERM) |
| 1303 | - | - | MCP技术开发入门实战！DeepSeek、ollama、vLLM接入MCP，从零手撕代码搭建MCP Client与Server！MCP完整技术实战！ | 115:15 | [link](https://www.bilibili.com/video/BV1NLXCYTEbj) |
| 1304 | - | - | MCP企业级智能体开发实战！知识库问答系统+AI数据分析智能体项目实战！独家提供MCP常用工作流+通用开发模版+外部工具调用优化函数 | 132:56 | [link](https://www.bilibili.com/video/BV1n1ZuYjEzf) |
| 1305 | - | - | 零门槛接入MCP！Cursor、阿里云百炼、Open-WebUI、Cherry Studio接入10大最热门MCP工具实战流程！零门槛搭建专属智能体应用！ | 123:09 | [link](https://www.bilibili.com/video/BV1dCo7YdEgK) |
| 1306 | - | - | DeepSeek v3本地部署与调用实战｜vLLM、SGLang、LMDeploy+DeepSeek v3部署调用实战 | 33:40 | [link](https://www.bilibili.com/video/BV1jjwVe4EKn) |
| 1307 | - | - | DeepSeek-v3调用指南与Function calling技术实战｜DeepSeek v3模型参数详解与Tool Use功能实战 | 97:25 | [link](https://www.bilibili.com/video/BV1JuwVewELc) |
| 1308 | - | - | 【全网独家】手动复现DeepSeek v3！从零训练Mini DeepSeek v3！模型预训练+全量指令微调+DPO强化学习微调全流程实战 | 120:14 | [link](https://www.bilibili.com/video/BV1KtwueYE54) |
| 1309 | - | - | DeepSeek v3搭建Multi-Agent技术入门实战｜DeepSeek v3+OpenAI Swarm技术实战 | 60:04 | [link](https://www.bilibili.com/video/BV1T8czeSEf1) |
| 1310 | - | - | DeepSeek v3+GraphRAG技术实战｜DeepSeek v3知识图谱检索增强技术实战 | 44:01 | [link](https://www.bilibili.com/video/BV1Xwc6eoEW5) |
| 1311 | - | - | 【保姆级】DeepSeek R1本地部署与调用指南｜transformer、Ollama、vLLM、LMDeploy、SGLang部署与调用R1与蒸馏模型组 | 54:58 | [link](https://www.bilibili.com/video/BV19kFoe6Ef7) |
| 1312 | - | - | DeepSeek R1 API调用实战！DeepSeek R1模型参数详解与模型功能介绍｜自动编程、自动机器学习项目入门实战 | 23:52 | [link](https://www.bilibili.com/video/BV1UyfGYqE28) |
| 1313 | - | - | 借助DeepSeek R1进行模型蒸馏，模型蒸馏入门实战！从零训练DeepSeek R1 Distill模型｜模型蒸馏技术实战 | 79:22 | [link](https://www.bilibili.com/video/BV1X1FoeBEgW) |
| 1314 | - | - | 【最佳方案】DeepSeek R1搭建本地知识库问答系统｜DeepSeek+Ollama+RAG本地知识库问答实战｜AnythingLLM快速部署与应用实战 | 47:16 | [link](https://www.bilibili.com/video/BV12qF2ePEDa) |
| 1315 | - | - | 新年巨献！DeepSeek Janus Pro重磅开源！文生图+图像识别，统一多模态大模型奠基之作！超越DALL-E 3、SD3 Medium | 25:10 | [link](https://www.bilibili.com/video/BV15kFseHEQ5) |
| 1316 | - | - | DeepSeek新年巨献！Janus Pro本地部署与调用实战！图像识别+文生图统一多模态大模型本地部署与调用流程详解！ | 34:13 | [link](https://www.bilibili.com/video/BV1ZqFse9Egc) |
| 1317 | - | - | 【全网独家】训练定制化DeepSeek R1！零基础DeepSeek R1高效微调实战｜知识灌注+对话风格微调，推理模型+Cot数据集微调实战！ | 111:26 | [link](https://www.bilibili.com/video/BV1YjN8eGE1H) |
| 1318 | - | - | 【全网最强】DeepSeek R1论文逐段精读与训练流程代码复现｜R1强化学习训练流程详解、模型蒸馏方法介绍｜GRPO原理介绍与代码复现 | 162:26 | [link](https://www.bilibili.com/video/BV1n9NfezErB) |
| 1319 | - | - | 联网+本地知识问答+外部工具调用+代码解释器+多用户并发+多模型切换，DeepSeek+Open-WebUI终极部署指南！ | 109:52 | [link](https://www.bilibili.com/video/BV1qU9AYLEe3) |
| 1320 | - | - | 最低0显存，独家Unsloth动态量化部署满血DeepSeek｜纯CPU推理、CPU+GPU混合推理、纯GPU推理方案详解｜企业级最佳部署方案 | 103:00 | [link](https://www.bilibili.com/video/BV1oePLezEZD) |
| 1321 | - | - | 【全网独家】训练定制化DeepSeek R1！零基础DeepSeek R1高效微调实战｜知识灌注+对话风格微调，推理模型+Cot数据集微调实战！ | 110:46 | [link](https://www.bilibili.com/video/BV1f8Are5Enz) |
| 1322 | - | - | 独家KTransformers技术实战，手把手跑通4090运行DeepSeek满血版，独家FastAPI脚本编写&Open-WebUI结合方案深度讲解 | 113:14 | [link](https://www.bilibili.com/video/BV1kyAke9EBA) |
| 1323 | - | - | DeepSeek正式发布DualPipe，梁文峰亲自带队研发神级双向管道并行算加速，毫秒级榨干GPU性能！ | 6:28 | [link](https://www.bilibili.com/video/BV1Gj9AYMEki) |
| 1324 | - | - | DeepSeek重磅开源DeepGEMM矩阵加速库，全球唯一FP8超级矩阵加速器！2.7倍提升矩阵乘法计算效率！ | 4:43 | [link](https://www.bilibili.com/video/BV1KJP7eZE2F) |
| 1325 | - | - | DeepSeek重磅开源DeepEP，大模型训练&推理效率暴涨！粉碎算力垄断，重塑MoE模型训练新范式！ | 4:53 | [link](https://www.bilibili.com/video/BV1LXPYeHEwB) |
| 1326 | - | - | 不负众望，Deepseek又开源封神！FlashMLA推理速度怒飙3倍！工业级加速库改写vLLM、SGLang技术规范 | 4:11 | [link](https://www.bilibili.com/video/BV1jdPxeKEPV) |
| 1327 | - | - | DeepSeek开源周压轴发布3FS，全球唯一大模型分布式文件管理系统，6TiB/s巨量吞吐性能，开辟训练新篇章！ | 5:54 | [link](https://www.bilibili.com/video/BV1Xh93YfEV1) |
| 1328 | - | - | 比肩o1！DeepSeek R1全面解析！价格比OpenAI o1便宜50倍！ / 1.5B小模型代码能力赶超GPT4o / 小尺寸推理模型企业可本地部署 | 6:52 | [link](https://www.bilibili.com/video/BV1UBwbe4E1D) |
| 1329 | - | - | 【深度】DeepSeek v3性能评测与技术解析｜DeepSeek v3为何是技术人首选模型｜颠覆当前大模型技术格局 | 11:17 | [link](https://www.bilibili.com/video/BV18Ccie5Esy) |
| 1330 | - | - | 2025大模型最强求职指南！整理全网2万份JD，一手数据信息揭秘求职真相！ | 12:47 | [link](https://www.bilibili.com/video/BV18JreYpE5Q) |
| 1331 | - | - | 【深度】2024大模型年度总结与2025技术展望！Agent智能体迎来全面爆发，大模型技术“黄金十年”即将到来！ | 20:29 | [link](https://www.bilibili.com/video/BV1Xn6nYnEnr) |
| 1332 | - | - | 不止会解数学题！OpenAI o3即将开启AGI新时代！详解o3的现实应用与深远影响 | 10:50 | [link](https://www.bilibili.com/video/BV1abCaYxEpp) |
| 1333 | - | - | OpenAI发布会总结与深度解读：AGI之路天堑变通途！ | 11:08 | [link](https://www.bilibili.com/video/BV1YZCNYDEzt) |
| 1334 | - | - | AI视频生成终极之战！谷歌Veo 2正面硬刚OpenAI Sora！ | 5:48 | [link](https://www.bilibili.com/video/BV1YVkMYsEq5) |
| 1335 | - | - | 万元服务器运行满血DeepSeek！全网最全低成本部署方案+硬件采购避坑指南！KTransformers方案+Unsloth动态量化方案详解！ | 13:36 | [link](https://www.bilibili.com/video/BV1K7ACewEfM) |
| 1336 | - | - | 零基础揭秘DeepSeek R1训练流程｜全网首发万字拆解R1复现流程｜多阶段GRPO强化学习训练、模型蒸馏技术揭秘！ | 15:48 | [link](https://www.bilibili.com/video/BV1ESAMepE4K) |
| 1337 | - | - | OpenAI年度发布会Day 1解读：o1满血版、o1 pro mode与ChatGPT Pro新品解读！ | 7:51 | [link](https://www.bilibili.com/video/BV1ufiYYuEpT) |
| 1338 | - | - | OpenAI年度发布会Day 1完整回放与实时解读！｜o1、o1Pro、ChatGPT Pro重磅发布！｜三位UP深夜团建解读发布会 | 21:56 | [link](https://www.bilibili.com/video/BV1GXiYYVEGa) |
| 1339 | - | - | OpenAI年度发布会前瞻解读，GPT5、Sora、Agent工具会发布么？ | 18:09 | [link](https://www.bilibili.com/video/BV1PuieYaEjT) |
| 1340 | - | - | OpenAI年度发布会Day2解读：强化学习微调与定制化o1模型震撼登场！开启Agent开发新时代！奥特曼：今年最大惊喜！ | 11:45 | [link](https://www.bilibili.com/video/BV1joirYkEB8) |
| 1341 | - | - | OpenAI发布会Day 2发布会完整回放与深度解读｜强化学习API震撼登场，定制化o1模型人人可得，Agent开发一夜变天！Sam：今年最大惊喜！ | 80:46 | [link](https://www.bilibili.com/video/BV1yfi6YHEQ4) |
| 1342 | - | - | OpenAI年度发布会一阶段汇总：o1 Pro、ChatGPT Pro、强化学习API新品解读【合集】 | 19:35 | [link](https://www.bilibili.com/video/BV1GAq5YZEeA) |
| 1343 | - | - | Sora来了！今日最新宣传片《合成青春》速览与解读！｜百人热舞+实体一致+物理遵循+专业运镜，Sora王者归来！ | 5:40 | [link](https://www.bilibili.com/video/BV1AjqHYAESa) |
| 1344 | - | - | OpenAI年度重磅！o1大模型快速入门与开发实战！｜o1 API调用流程、推理与上下文管理、自动编程与实体识别开发实战！ | 46:33 | [link](https://www.bilibili.com/video/BV1zWqHY4EjE) |
| 1345 | - | - | Sora重磅发布！无限时长一致+任意帧修改+物理遵循！OpenAI发布会Day 3深度解读！ | 6:17 | [link](https://www.bilibili.com/video/BV18EquYGEfo) |
| 1346 | - | - | Sora今日重磅上线！发布会完整解读、Sora演示与功能详解！ | 56:22 | [link](https://www.bilibili.com/video/BV1shquYPEds) |
| 1347 | - | - | Sora功能及价格全解！Sora今日重磅发布，再次颠覆多模态领域，不负期待！ | 14:14 | [link](https://www.bilibili.com/video/BV1rRqMYZERK) |
| 1348 | - | - | 在线Cursor来了！新版Canvas功能深度解读！ChatGPT在线文本&代码智能编辑器现已上线！ | 14:53 | [link](https://www.bilibili.com/video/BV1dYqyYUEVT) |
| 1349 | - | - | OpenAI Day 4发布会实况回放与深度解读！在线Cursor来了，新版Canvas重磅上线！ | 24:04 | [link](https://www.bilibili.com/video/BV1FpqyY4Eew) |
| 1350 | - | - | ChatGPT Canvas智能编程与智能文本编辑完整功能演示！OpenAI发布会Day 4，新版ChatGPT Canvas重磅上线！ | 17:47 | [link](https://www.bilibili.com/video/BV1B1qCYQEcK) |
| 1351 | - | - | OpenAI Day 7深度解读，ChatGPT Projects功能来袭，文本&代码生产力迎来重大突破！ | 10:08 | [link](https://www.bilibili.com/video/BV1TfB3Y2EUS) |
| 1352 | - | - | OpenAI发布会Day 7发布会回放与解读：ChatGPT Projects功能重磅上线！新一代ChatBot生产力标杆！ | 29:14 | [link](https://www.bilibili.com/video/BV1pbB3YTE33) |
| 1353 | - | - | ChatGPT操控APP效果演示：一键操控Cursor及其他文本与代码编辑器！ | 31:25 | [link](https://www.bilibili.com/video/BV1e3kkY9E49) |
| 1354 | - | - | OpenAI Day 11：ChatGPT操控指定APP功能上线！发布会实况与深度解读～ | 49:41 | [link](https://www.bilibili.com/video/BV1eVkkYpEAu) |
| 1355 | - | - | ChatGPT APP协作功能介绍与解读！一键配对APP完成操控！Computer use雏形功能上线 | 13:00 | [link](https://www.bilibili.com/video/BV1pikkYqEbU) |
| 1356 | - | - | OpenAI Day 10：打电话、发短信找ChatGPT聊天｜OpenAI发布会Day 10回放与解读 | 18:46 | [link](https://www.bilibili.com/video/BV13DkPYCEHb) |
| 1357 | - | - | ChatGPT创意功能上线！打电话、发短信找ChatGPT聊天～ | 5:21 | [link](https://www.bilibili.com/video/BV1oHkNYHETB) |
| 1358 | - | - | ChatGPT Search发布会完整解读与实况回放｜ChatGPT完整体正式发布，发布会实况解读 | 18:16 | [link](https://www.bilibili.com/video/BV1zSkGYjEWA) |
| 1359 | - | - | ChatGPT完整体来袭，新版互联网Search功能重磅上线，免费可用！｜OpenAI发布会Day 8深度解读 | 9:47 | [link](https://www.bilibili.com/video/BV1nmkGYmEcf) |
| 1360 | - | - | o3推理大模型王炸登场 Agent将获最强大脑！数学编程能力大幅提升、推理新时代来临 ｜ OpenAI发布会Day12 | 7:37 | [link](https://www.bilibili.com/video/BV17wkQYQEaU) |
| 1361 | - | - | 全程高能！o3大模型发布会实况与深度解读！OpenAI Day12完整录像与技术解说 | 77:07 | [link](https://www.bilibili.com/video/BV1hikDYzELp) |
| 1362 | - | - | Agent智能体概念详解与2025大模型岗位技能要求分析｜2025Agent最热门开发方向分析 | 25:31 | [link](https://www.bilibili.com/video/BV1TjBnYTETX) |
| 1363 | - | - | 零基础Agent智能体开发基础理论详解！记忆、工具、规划、执行四大功能模块设计原理保姆级介绍！ | 24:47 | [link](https://www.bilibili.com/video/BV1CcBJYtEne) |
| 1364 | - | - | 12项Agent智能体开发框架入门与选型！｜Coze、Dify、LangChain、LangGraph、AutoGen等工具对比分析与选型建议！ | 23:10 | [link](https://www.bilibili.com/video/BV16NBJYRE3s) |
| 1365 | - | - | 当前主流各类GPU分类命名及适用场景介绍｜RTX系列、A系列、H系列、中国区特供版GPU分类命名规则及性能介绍 | 6:55 | [link](https://www.bilibili.com/video/BV1HpBEYsEzW) |
| 1366 | - | - | 大模型GPU性能与性价比天梯图详解！各类GPU的大模型训练与推理性能对比，以及主流GPU性价比分析！ | 9:33 | [link](https://www.bilibili.com/video/BV1daBEY7ESw) |
| 1367 | - | - | 各类大模型运行GPU配置推荐！各尺寸大模型训练、微调、推理所需GPU配置推荐！ | 7:26 | [link](https://www.bilibili.com/video/BV1GZB7YrE2Y) |
| 1368 | - | - | 个人、实验室、企业大模型项目GPU服务器推荐配置及报价！各类大模型项目GPU完整配置清单详解 | 6:29 | [link](https://www.bilibili.com/video/BV15oB7YGEjG) |
| 1369 | - | - | GLM4实战教程（1）：GLM系列在线大模型生态入门介绍 | 34:37 | [link](https://www.bilibili.com/video/BV1gK4y1B7oq) |
| 1370 | - | - | GLM4实战教程（2）：GLM4 API-KEY获取与本地调用 | 32:58 | [link](https://www.bilibili.com/video/BV1ja4y1y7Aj) |
| 1371 | - | - | GLM4实战教程（3）：GLM模型全参数讲解 | 59:18 | [link](https://www.bilibili.com/video/BV1he411n7nS) |
| 1372 | - | - | GLM4实战教程（4）：GLM模型Message队列设置方法与模型身份设置 | 21:23 | [link](https://www.bilibili.com/video/BV1oN4y1n7QG) |
| 1373 | - | - | 大模型最大风口Agent是什么？详解Agent在医疗、教育、生产力、个人助理、娱乐、电商领域应用现状 | 14:54 | [link](https://www.bilibili.com/video/BV1LN4y1a7gB) |
| 1374 | - | - | 团队自研Agent：MateGen重磅上线！定制知识库+本地代码解释器+联网+追踪debug！伴你高效学习&工作 | 17:16 | [link](https://www.bilibili.com/video/BV1WN41157QT) |
| 1375 | - | - | 开源大模型 VS GPT，哪个最适合做Agent？零基础入门Agent开发学习路线推荐！ | 16:17 | [link](https://www.bilibili.com/video/BV11u4y1M73s) |
| 1376 | - | - | 全球最前沿GPT系Agent开发都需要哪些技能？详解GPT系Agent开发必备技能学习路线！ | 8:22 | [link](https://www.bilibili.com/video/BV1mi4y1e7kd) |
| 1377 | - | - | 国内商用Agent开发，要学习哪些开源大模型？详解开源大模型开发Agent入门学习路径！ | 13:31 | [link](https://www.bilibili.com/video/BV1ij411W7fp) |
| 1378 | - | - | Agent概念详解！为什么Agent才是大模型的未来？数据分析&机器学习Agent到底长啥样？ | 32:13 | [link](https://www.bilibili.com/video/BV1w94y177et) |
| 1379 | - | - | Agent开发必备技能详解！零基础入门Agent开发学习路线精讲！｜在线大模型&开源大模型技术学习路线 | 38:09 | [link](https://www.bilibili.com/video/BV1MN4y1a7iz) |
| 1380 | - | - | 零基础迅速掌握Agent开发流程！Agent通用开发范式详解！｜Agent模块化开发流程精讲 | 23:22 | [link](https://www.bilibili.com/video/BV1MN41157gh) |
| 1381 | - | - | AI Agent开发新范式，GPTs功能详解！｜打造个人专属ChatGPT | 28:19 | [link](https://www.bilibili.com/video/BV1az4y1w7nH) |
| 1382 | - | - | 手把手创建一个专属GPTs！打造全自动数据分析Agent！｜以对话的方式高效开发AI Agent | 31:08 | [link](https://www.bilibili.com/video/BV1XG411S7Df) |
| 1383 | - | - | GPTs进阶功能Actions使用方法详解！将外部工具API接入GPTs，打造功能专属ChatGPT | 39:32 | [link](https://www.bilibili.com/video/BV1qC4y127js) |
| 1384 | - | - | 全自动数据分析报表GPTs功能测试！｜专属GPTs发布与功能测试 | 12:15 | [link](https://www.bilibili.com/video/BV1qw411N7qf) |
| 1385 | - | - | ChatGLM3零基础安装部署流程（上）｜ChatGLM3零基础代码调用流程｜ChatGLM3 Web应用调用方法 | 28:59 | [link](https://www.bilibili.com/video/BV1gN4y1r7RX) |
| 1386 | - | - | ChatGLM3零基础安装部署流程（下）｜ChatGLM3零基础代码调用流程｜ChatGLM3 Web应用调用方法 | 27:05 | [link](https://www.bilibili.com/video/BV18M411Q7Pp) |
| 1387 | - | - | ChatGLM3快速入门，全新API调用方法详解｜Messages参数功能介绍 | 28:21 | [link](https://www.bilibili.com/video/BV18c411d7Hd) |
| 1388 | - | - | ChatGLM3推理性能快速评测｜ChatGLM3 VS GPT系模型性能对比 | 25:57 | [link](https://www.bilibili.com/video/BV1BG411X7Hk) |
| 1389 | - | - | ChatGLM3工具调用function calling功能详解｜如何让ChatGLM3接入外部工具｜ChatGLM3 Agent开发入门 | 24:46 | [link](https://www.bilibili.com/video/BV1V84y1971r) |
| 1390 | - | - | ChatGLM3 Agent开发入门｜Function calling全自动实现｜AI Agent开发入门 | 26:00 | [link](https://www.bilibili.com/video/BV1Wy4y1c7oA) |
| 1391 | - | - | 进步显著！ChatGLM3重磅上线！深度详解新模型性能与新功能 | 34:48 | [link](https://www.bilibili.com/video/BV14N4y1674J) |
| 1392 | - | - | ChatGLM3全新消息队列功能介绍！接入先进多角色对话功能！ | 15:09 | [link](https://www.bilibili.com/video/BV1fg4y197xM) |
| 1393 | - | - | ChatGLM3全新Function calling功能详解！开启AI Agent之路的最核心功能！ | 22:21 | [link](https://www.bilibili.com/video/BV1K94y157gd) |
| 1394 | - | - | 如何借助大模型冲击Kaggle金牌？ | 26:48 | [link](https://www.bilibili.com/video/BV1i84y127sB) |
| 1395 | - | - | 自动机器学习建模AI Agent功能架构详解 | 29:07 | [link](https://www.bilibili.com/video/BV1MN411t79i) |
| 1396 | - | - | 自动机器学习建模 AI Agent入门实操 | 26:25 | [link](https://www.bilibili.com/video/BV1oG41117oq) |
| 1397 | - | - | 特征衍生全技术路径精讲 / 机器学习 / 特征工程 | 17:21 | [link](https://www.bilibili.com/video/BV1aC4y1d7GD) |
| 1398 | - | - | 特征筛选全技术路径精讲 | 10:59 | [link](https://www.bilibili.com/video/BV1Kw411k7XT) |
| 1399 | - | - | 模型融合全技术地图讲解 | 16:26 | [link](https://www.bilibili.com/video/BV19B4y1Z7dK) |
| 1400 | - | - | GPT系AI应用开发实战01: GPT模型Function calling功能入门介绍 | 27:18 | [link](https://www.bilibili.com/video/BV1XF411f7qF) |
| 1401 | - | - | GPT系AI应用开发实战02: Function calling相关参数详解 | 30:32 | [link](https://www.bilibili.com/video/BV16X4y1L7H2) |
| 1402 | - | - | GPT系AI应用开发实战03: Function calling开发流程详解 | 26:02 | [link](https://www.bilibili.com/video/BV1f8411d73j) |
| 1403 | - | - | GPT系AI应用开发实战04: GPT模型调用外部工具API方法介绍 | 29:17 | [link](https://www.bilibili.com/video/BV1w14y1q7yr) |
| 1404 | - | - | GPT系AI应用开发实战05: 基于GPT模型的天气查询应用开发实战 | 16:34 | [link](https://www.bilibili.com/video/BV1Nu4y1z7ku) |
| 1405 | - | - | GPT系AI应用开发实战06: AI应用开发入门: 谷歌云与API库入门介绍 | 22:07 | [link](https://www.bilibili.com/video/BV1hH4y1D7qF) |
| 1406 | - | - | GPT系AI应用开发实战07: AI应用开发入门: 谷歌云 Auth2.0 授权方法 | 28:30 | [link](https://www.bilibili.com/video/BV17p4y1j75v) |
| 1407 | - | - | GPT系AI应用开发实战08: 基于Gmail API的AI邮件系统开发实战1 | 15:04 | [link](https://www.bilibili.com/video/BV1rj411C7G4) |
| 1408 | - | - | GPT系AI应用开发实战09: 基于Gmail API的AI邮件系统开发实战2 | 27:26 | [link](https://www.bilibili.com/video/BV1gH4y1Q7iy) |
| 1409 | - | - | GPT系AI应用开发实战10: 热门AI应用开发方向解读 | 26:24 | [link](https://www.bilibili.com/video/BV1Dz4y1j7vH) |
| 1410 | - | - | GPT系AI应用开发实战11: 智能搜索问答机器人项目介绍与开发思路 | 29:52 | [link](https://www.bilibili.com/video/BV1Qp4y1A7X9) |
| 1411 | - | - | GPT系AI应用开发实战12: 谷歌搜索API获取与使用方法 / 将谷歌搜索接入GPT大模型 | 28:53 | [link](https://www.bilibili.com/video/BV16u411c7Nd) |
| 1412 | - | - | GPT系AI应用开发实战13: 构建基于GitHub的搜索问答机器人 | 30:32 | [link](https://www.bilibili.com/video/BV1jy4y1F7QW) |
| 1413 | - | - | GPT大模型技术实战教程01: OpenAI官网使用指南与API-Key获取 | 29:15 | [link](https://www.bilibili.com/video/BV1YM4y1x76K) |
| 1414 | - | - | GPT大模型技术实战教程02: GPT大模型API-Key使用方法&Jupyter本地调用 | 16:09 | [link](https://www.bilibili.com/video/BV1RV411T754) |
| 1415 | - | - | GPT大模型技术实战教程03: Completion模型与Chat模型入门介绍 | 16:04 | [link](https://www.bilibili.com/video/BV1M8411Q7Kv) |
| 1416 | - | - | GPT大模型技术实战教程04: Completion模型API使用方法详解 | 25:29 | [link](https://www.bilibili.com/video/BV1fP411k7vv) |
| 1417 | - | - | GPT大模型技术实战教程05:  Completion模型调参实践 | 14:46 | [link](https://www.bilibili.com/video/BV1zz4y147FZ) |
| 1418 | - | - | GPT大模型技术实战教程06: 基于Completion手动创建可自定义聊天风格的对话机器人 | 14:25 | [link](https://www.bilibili.com/video/BV1U14y197hp) |
| 1419 | - | - | GPT大模型技术实战教程07: GPT最新Chat类模型入门介绍 | 23:09 | [link](https://www.bilibili.com/video/BV1Vk4y1V76h) |
| 1420 | - | - | GPT大模型技术实战教程08：Chat模型功能介绍与发展现状 | 19:35 | [link](https://www.bilibili.com/video/BV1LN411Y7hW) |
| 1421 | - | - | GPT大模型技术实战教程09: GPT-4 API使用方法&Chat模型API详解 | 36:15 | [link](https://www.bilibili.com/video/BV1f14y1z7HS) |
| 1422 | - | - | GPT大模型技术实战教程10: GPT-4 API核心参数Message使用方法详解 | 25:32 | [link](https://www.bilibili.com/video/BV1vc411F7vi) |
| 1423 | - | - | 【入门】OpenAI在线大模型生态介绍｜大模型技术入门课程｜GPT&DALL·E&Codex&Embedding模型介绍 | 27:15 | [link](https://www.bilibili.com/video/BV15P411z7pU) |
| 1424 | - | - | 【入门】开源大模型生态与ChatGLM-6B大模型介绍｜最强中文大模型GLM介绍｜LLM开源大模型概览 | 33:35 | [link](https://www.bilibili.com/video/BV1Xg4y1N7kM) |
| 1425 | - | - | 【入门】大语言模型常用微调框架介绍｜LoRA&Prefix-Tuning&Prompt-Tuning&P-Tuning v2&RLHF微调原理简介 | 33:33 | [link](https://www.bilibili.com/video/BV1Yc411g78a) |
| 1426 | - | - | 【入门】AI应用开发范式LangChain零基础入门介绍｜LangChain六大功能模块解释｜基于LLM的AI开发流程与开发工具 | 25:38 | [link](https://www.bilibili.com/video/BV1gz4y1e7im) |
| 1427 | - | - | 机器学习面试热点问题精讲·Part 1.机器学习基础篇｜2023冲刺春招算法岗｜面试必考机器学习热点问题｜全原理讲解&附赠标准问答模版 | 45:49 | [link](https://www.bilibili.com/video/BV1oo4y167CV) |
| 1428 | - | - | 机器学习面试热点问题精讲·Part 2.经典机器学习篇｜2023冲刺春招算法岗｜面试必考机器学习热点问题｜全原理讲解&附赠标准问答模版 | 15:10 | [link](https://www.bilibili.com/video/BV1XT411v7WK) |
| 1429 | - | - | 机器学习面试热点问题精讲·Part 3.集成学习篇｜2023冲刺春招算法岗｜面试必考机器学习热点问题｜全原理讲解&附赠标准问答模版 | 24:22 | [link](https://www.bilibili.com/video/BV17j411g7PX) |
| 1430 | - | - | 机器学习面试热点问题精讲·Part 4.特征工程篇｜2023冲刺春招算法岗｜面试必考机器学习热点问题｜全原理讲解&附赠标准问答模版 | 35:13 | [link](https://www.bilibili.com/video/BV1pT411v7gD) |
| 1431 | - | - | 机器学习面试热点问题精讲·Part 5.模型融合篇｜2023冲刺春招算法岗｜面试必考机器学习热点问题｜全原理讲解&附赠标准问答模版 | 41:57 | [link](https://www.bilibili.com/video/BV1c54y1u7DU) |

## Per entry

- **RNN模型与NLP应用(1/9)：数据处理基础**
  - [B station](https://www.bilibili.com/video/BV1w54y1L7xK)
  - links: https://github.com/wangshusen/DeepLearning
- **RNN模型与NLP应用(2/9)：文本处理与词嵌入**
  - [B station](https://www.bilibili.com/video/BV1fp4y147Lc)
  - links: https://github.com/wangshusen/DeepLearning
- **RNN模型与NLP应用(3/9)：Simple RNN模型**
  - [B station](https://www.bilibili.com/video/BV1dq4y1f7ep)
  - links: https://github.com/wangshusen/DeepLearning
- **RNN模型与NLP应用(4/9)：LSTM模型**
  - [B station](https://www.bilibili.com/video/BV1UK4y1d7xa)
  - links: https://github.com/wangshusen/DeepLearning
- **RNN模型与NLP应用(5/9)：多层RNN、双向RNN、预训练**
  - [B station](https://www.bilibili.com/video/BV1Ab4y1f73K)
  - links: https://github.com/wangshusen/DeepLearning
- **RNN模型与NLP应用(6/9)：Text Generation (自动文本生成)**
  - [B station](https://www.bilibili.com/video/BV1Xh411e7ZR)
  - links: https://github.com/wangshusen/DeepLearning
- **RNN模型与NLP应用(7/9)：机器翻译与Seq2Seq模型**
  - [B station](https://www.bilibili.com/video/BV1964y127Vz)
  - links: https://github.com/wangshusen/DeepLearning
- **RNN模型与NLP应用(8/9)：Attention (注意力机制)**
  - [B station](https://www.bilibili.com/video/BV1YA411G7Ep)
  - links: https://github.com/wangshusen/DeepLearning
- **RNN模型与NLP应用(9/9)：Self-Attention (自注意力机制)**
  - [B station](https://www.bilibili.com/video/BV17B4y1F7oy)
  - links: https://github.com/wangshusen/DeepLearning
- **Transformer模型(1/2): 剥离RNN，保留Attention**
  - [B station](https://www.bilibili.com/video/BV1SK4y1d7Qh)
  - links: https://github.com/wangshusen/DeepLearning
- **Transformer模型(2/2): 从Attention层到Transformer网络**
  - [B station](https://www.bilibili.com/video/BV1N54y1L7N5)
  - links: https://github.com/wangshusen/DeepLearning
- **BERT (预训练Transformer模型)**
  - [B station](https://www.bilibili.com/video/BV1y64y127bF)
  - links: https://github.com/wangshusen/DeepLearning
- **Vision Transformer (ViT) 用于图片分类**
  - [B station](https://www.bilibili.com/video/BV18Q4y1o7NY)
  - links: https://github.com/wangshusen/DeepLearning.git
- **10-1: 图的基本概念和数据结构 Graph Basics and Data Structures**
  - [B station](https://www.bilibili.com/video/BV1k44y1z7g6)
  - links: https://github.com/wangshusen/AdvancedAlgorithms.git
- **11-1: 图中的路径和最短路 Shortest Path**
  - [B station](https://www.bilibili.com/video/BV1WB4y1g7tW)
  - links: https://github.com/wangshusen/AdvancedAlgorithms.git
- **11-2: 无权图的最短路算法 Finding Shortest Path in Unweighted Graphs**
  - [B station](https://www.bilibili.com/video/BV1CK4y1X7BT)
  - links: https://github.com/wangshusen/AdvancedAlgorithms.git
- **11-3: Dijkstra 算法 寻找有权图中最短路 Finding Shortest Path in Weighted Graphs**
  - [B station](https://www.bilibili.com/video/BV19K4y1g75e)
- **12-3: Kruskal算法 寻找最小生成树 Kruskal's Algorithm for Minimum Spanning Trees**
  - [B station](https://www.bilibili.com/video/BV1Sv411V781)
- **12-2: Prim算法 寻找最小生成树 Prim's Algorithm for Minimum Spanning Trees**
  - [B station](https://www.bilibili.com/video/BV1A5411M7zc)
  - links: https://github.com/wangshusen/AdvancedAlgorithms.git
- **12-1: 最小生成树 Minimum Spanning Trees**
  - [B station](https://www.bilibili.com/video/BV145411M7xL)
  - links: https://github.com/wangshusen/AdvancedAlgorithms.git
- **13-1: 网络流问题基础 Network Flow Problems**
  - [B station](https://www.bilibili.com/video/BV1K64y1C7Do)
  - links: https://github.com/wangshusen/AdvancedAlgorithms.git
- **13-2: Ford-Fulkerson Algorithm 寻找网络最大流**
  - [B station](https://www.bilibili.com/video/BV1Pv41157xh)
  - links: https://github.com/wangshusen/AdvancedAlgorithms.git
- **13-3: Edmonds-Karp Algorithm 寻找网络最大流**
  - [B station](https://www.bilibili.com/video/BV1uQ4y197Le)
  - links: https://github.com/wangshusen/AdvancedAlgorithms.git
- **13-4: Dinic's Algorithm 寻找网络最大流**
  - [B station](https://www.bilibili.com/video/BV1j64y1R7yK)
  - links: https://github.com/wangshusen/AdvancedAlgorithms.git
- **13-5: 最小割 Min-Cut**
  - [B station](https://www.bilibili.com/video/BV1T64y1R7ZK)
  - links: https://github.com/wangshusen/AdvancedAlgorithms.git
- **14-1: 二部图及其判定算法 Bipartite Graphs**
  - [B station](https://www.bilibili.com/video/BV14q4y1j776)
  - links: https://youtu.be/cndaoZ6XTxA
- **14-2: 无权二部图中的最大匹配 Maximum-Cardinality Bipartite Matching (MCBM)**
  - [B station](https://www.bilibili.com/video/BV1G54y157HA)
  - links: https://github.com/wangshusen/AdvancedAlgorithms.git
- **14-3: 有权二部图中的最大匹配 Maximum-Weight Bipartite Matching**
  - [B station](https://www.bilibili.com/video/BV1MB4y1g7Fx)
  - links: https://github.com/wangshusen/AdvancedAlgorithms.git
- **14-4: 匈牙利算法 Hungarian Algorithm**
  - [B station](https://www.bilibili.com/video/BV16K4y1X7Ph)
  - links: https://github.com/wangshusen/AdvancedAlgorithms.git
- **14-5: 稳定婚配问题 Stable Marriage Problem**
  - [B station](https://www.bilibili.com/video/BV1V44y167n3)
- **14-6: Gale-Shapley 算法 寻找稳定婚配**
  - [B station](https://www.bilibili.com/video/BV1uq4y177Hc)
  - links: https://github.com/wangshusen/AdvancedAlgorithms.git
- **概要01：推荐系统的基本概念**
  - [B station](https://www.bilibili.com/video/BV1PS4y1A7za)
  - links: https://github.com/wangshusen/RecommenderSystem
- **概要02：推荐系统的链路**
  - [B station](https://www.bilibili.com/video/BV1hF411M7b5)
  - links: https://github.com/wangshusen/RecommenderSystem
- **概要03：推荐系统的AB测试**
  - [B station](https://www.bilibili.com/video/BV1J44y1o7gf)
  - links: https://github.com/wangshusen/RecommenderSystem
- **召回01：基于物品的协同过滤（ItemCF）**
  - [B station](https://www.bilibili.com/video/BV1mA4y1Q7RN)
  - links: https://github.com/wangshusen/RecommenderSystem
- **召回02：Swing 模型**
  - [B station](https://www.bilibili.com/video/BV1DA4y1Q7rB)
  - links: https://github.com/wangshusen/RecommenderSystem
- **召回03：基于用户的协同过滤（UserCF）**
  - [B station](https://www.bilibili.com/video/BV1HY4y1Y7P1)
  - links: https://github.com/wangshusen/RecommenderSystem
- **召回04：离散特征处理**
  - [B station](https://www.bilibili.com/video/BV1pS4y1a7QT)
  - links: https://github.com/wangshusen/RecommenderSystem
- **召回05：矩阵补充、最近邻查找**
  - [B station](https://www.bilibili.com/video/BV1b34y1e7En)
  - links: https://github.com/wangshusen/RecommenderSystem
- **召回06：双塔模型——模型结构、训练方法**
  - [B station](https://www.bilibili.com/video/BV1YA4y1D75Q)
  - links: https://github.com/wangshusen/RecommenderSystem
- **召回07：双塔模型——正负样本**
  - [B station](https://www.bilibili.com/video/BV133411T7ue)
  - links: https://github.com/wangshusen/RecommenderSystem
- **召回08：双塔模型——线上服务、模型更新**
  - [B station](https://www.bilibili.com/video/BV1KY4y1h73Y)
  - links: https://github.com/wangshusen/RecommenderSystem
- **召回09：双塔模型+自监督学习**
  - [B station](https://www.bilibili.com/video/BV1v24y1B7JH)
  - links: https://github.com/wangshusen/RecommenderSystem
- **召回10：Deep Retrieval 召回**
  - [B station](https://www.bilibili.com/video/BV1Fu4y1b7PL)
  - links: https://github.com/wangshusen/RecommenderSystem
- **召回11：地理位置召回、作者召回、缓存召回**
  - [B station](https://www.bilibili.com/video/BV1m5411R7nd)
  - links: https://github.com/wangshusen/RecommenderSystem
- **召回12：曝光过滤 & Bloom Filter**
  - [B station](https://www.bilibili.com/video/BV1sa4y137LF)
- **排序01：多目标模型**
  - [B station](https://www.bilibili.com/video/BV19t4y1p7UM)
  - links: https://github.com/wangshusen/RecommenderSystem
- **排序02：Multi-gate Mixture-of-Experts (MMoE)**
  - [B station](https://www.bilibili.com/video/BV14Y411M74v)
  - links: https://github.com/wangshusen/RecommenderSystem
- **排序03：预估分数融合**
  - [B station](https://www.bilibili.com/video/BV1YT411578u)
  - links: https://github.com/wangshusen/RecommenderSystem
- **排序04：视频播放建模**
  - [B station](https://www.bilibili.com/video/BV1394y1277M)
  - links: https://github.com/wangshusen/RecommenderSystem
- **排序05：排序模型的特征**
  - [B station](https://www.bilibili.com/video/BV1gN4y157TM)
  - links: https://github.com/wangshusen/RecommenderSystem
- **排序06：粗排模型**
  - [B station](https://www.bilibili.com/video/BV1Dd4y1m7KT)
  - links: https://github.com/wangshusen/RecommenderSystem
- **特征交叉01：Factorized Machine (FM) 因式分解机**
  - [B station](https://www.bilibili.com/video/BV15V4y1x7Ht)
  - links: https://github.com/wangshusen/RecommenderSystem
- **特征交叉02：DCN 深度交叉网络**
  - [B station](https://www.bilibili.com/video/BV1LP411L7Z2)
  - links: https://github.com/wangshusen/RecommenderSystem
- **特征交叉03：LHUC (PPNet)**
  - [B station](https://www.bilibili.com/video/BV1jU4y1z7Tc)
  - links: https://ai.51cto.com/art/202102/644214.html https://github.com/wangshusen/RecommenderSystem
- **特征交叉04：SENet 和 Bilinear 交叉**
  - [B station](https://www.bilibili.com/video/BV1SY4y1M7bD)
  - links: https://github.com/wangshusen/RecommenderSystem
- **行为序列01：用户历史行为序列建模**
  - [B station](https://www.bilibili.com/video/BV1GG4y1B7Yh)
  - links: https://github.com/wangshusen/RecommenderSystem
- **行为序列02：DIN模型（注意力机制）**
  - [B station](https://www.bilibili.com/video/BV1bT411T7u4)
  - links: https://github.com/wangshusen/RecommenderSystem
- **行为序列03：SIM模型（长序列建模）**
  - [B station](https://www.bilibili.com/video/BV1Ze4y1B7JL)
  - links: https://github.com/wangshusen/RecommenderSystem
- **重排01：物品相似性的度量、提升多样性的方法**
  - [B station](https://www.bilibili.com/video/BV1ne4y1v7mC)
  - links: https://github.com/wangshusen/RecommenderSystem
- **重排02：MMR 多样性算法（Maximal Marginal Relevance）**
  - [B station](https://www.bilibili.com/video/BV1dV4y1V7Kg)
  - links: https://github.com/wangshusen/RecommenderSystem
- **重排03：业务规则约束下的多样性算法**
  - [B station](https://www.bilibili.com/video/BV1om4y1F7y5)
  - links: https://github.com/wangshusen/RecommenderSystem
- **重排04：DPP 多样性算法（上）**
  - [B station](https://www.bilibili.com/video/BV1re411F7cp)
  - links: https://github.com/wangshusen/RecommenderSystem
- **重排05：DPP 多样性算法（下）**
  - [B station](https://www.bilibili.com/video/BV1Md4y1c7uB)
  - links: https://github.com/wangshusen/RecommenderSystem
- **物品冷启01：优化目标 & 评价指标**
  - [B station](https://www.bilibili.com/video/BV1eZ4y1a7tG)
  - links: https://github.com/wangshusen/RecommenderSystem
- **物品冷启02：简单的召回通道**
  - [B station](https://www.bilibili.com/video/BV1HY4y157Ri)
- **物品冷启03：聚类召回**
  - [B station](https://www.bilibili.com/video/BV1YT4y1q7zC)
  - links: https://github.com/wangshusen/RecommenderSystem
- **物品冷启04：Look-Alike 召回**
  - [B station](https://www.bilibili.com/video/BV1U5411X7ud)
  - links: https://github.com/wangshusen/RecommenderSystem/tree/main/Slides
- **物品冷启05：流量调控**
  - [B station](https://www.bilibili.com/video/BV1vS4y1z7sC)
  - links: https://github.com/wangshusen/RecommenderSystem
- **物品冷启06：冷启的AB测试**
  - [B station](https://www.bilibili.com/video/BV12341137Cq)
- **推荐系统涨指标的方法01：概述**
  - [B station](https://www.bilibili.com/video/BV1fc41167jK)
  - links: https://github.com/wangshusen/RecommenderSystem https://arxiv.org/abs/2308.01204
- **推荐系统涨指标的方法02：召回**
  - [B station](https://www.bilibili.com/video/BV13H4y127Tt)
  - links: https://github.com/wangshusen/RecommenderSystem https://arxiv.org/abs/2308.01204
- **推荐系统涨指标的方法03：排序模型**
  - [B station](https://www.bilibili.com/video/BV1fQ4y1G72F)
  - links: https://github.com/wangshusen/RecommenderSystem https://arxiv.org/abs/2308.01204
- **推荐系统涨指标的方法04：多样性**
  - [B station](https://www.bilibili.com/video/BV1eN4y1z7vs)
  - links: https://github.com/wangshusen/RecommenderSystem https://arxiv.org/abs/2308.01204
- **推荐系统涨指标的方法05：特殊用户人群**
  - [B station](https://www.bilibili.com/video/BV15g4y1m7P4)
  - links: https://github.com/wangshusen/RecommenderSystem https://arxiv.org/abs/2308.01204
- **推荐系统涨指标的方法06：交互行为（关注、转发、评论）**
  - [B station](https://www.bilibili.com/video/BV1tg4y127rS)
  - links: https://github.com/wangshusen/RecommenderSystem https://arxiv.org/abs/2308.01204
- **神经网络结构搜索 (1/3): 基本概念和随机搜索   Neural Architecture Search: Basics & Random Search**
  - [B station](https://www.bilibili.com/video/BV14q4y177gQ)
  - links: https://github.com/wangshusen/DeepLearning.git
- **神经网络结构搜索 (2/3): RNN + RL   Neural Architecture Search: RNN + RL**
  - [B station](https://www.bilibili.com/video/BV15K4y1A7hq)
  - links: https://github.com/wangshusen/DeepLearning.git
- **神经网络结构搜索 (3/3): 可微方法   Differentiable Neural Architecture Search**
  - [B station](https://www.bilibili.com/video/BV1C64y127Fv)
  - links: https://github.com/wangshusen/DeepLearning.git
- **概要01：搜索引擎的基本概念**
  - [B station](https://www.bilibili.com/video/BV1Wr421b7uP)
  - links: https://github.com/wangshusen/SearchEngine
- **概要02：相关性、内容质量、时效性、个性化（决定搜索满意度的因素）**
  - [B station](https://www.bilibili.com/video/BV1Lm421J7Xz)
  - links: https://github.com/wangshusen/SearchEngine
- **概要03：搜索引擎的评价指标**
  - [B station](https://www.bilibili.com/video/BV1BT421m7UQ)
  - links: https://github.com/wangshusen/SearchEngine
- **概要04：搜索引擎的链路（查询词处理、召回、排序）**
  - [B station](https://www.bilibili.com/video/BV1UM4m1D7L3)
  - links: https://github.com/wangshusen/SearchEngine
- **相关性01：搜索相关性的定义与分档**
  - [B station](https://www.bilibili.com/video/BV1Xp421S7Kb)
  - links: https://github.com/wangshusen/SearchEngine
- **相关性02：评价指标（AUC、正逆序比、DCG）**
  - [B station](https://www.bilibili.com/video/BV1VD421N7K7)
  - links: https://github.com/wangshusen/SearchEngine
- **相关性03：文本匹配（TF-IDF、BM25、词距）**
  - [B station](https://www.bilibili.com/video/BV1XT421Q7fw)
  - links: https://github.com/wangshusen/SearchEngine
- **相关性04：BERT模型 (Part 1) - 模型结构、线上推理**
  - [B station](https://www.bilibili.com/video/BV17T421D72u)
  - links: https://github.com/wangshusen/SearchEngine
- **相关性05：BERT模型 (Part 2) - 模型训练**
  - [B station](https://www.bilibili.com/video/BV1pz421e7GS)
  - links: https://github.com/wangshusen/SearchEngine
- **Few-Shot Learning (1/3): 基本概念**
  - [B station](https://www.bilibili.com/video/BV1V44y1r7cx)
- **Few-Shot Learning (2/3): Siamese Network (孪生网络)**
  - [B station](https://www.bilibili.com/video/BV1vQ4y1R7dr)
  - links: https://github.com/wangshusen/DeepLearning
- **Few-Shot Learning (3/3)：Pretraining + Fine Tuning**
  - [B station](https://www.bilibili.com/video/BV1B44y1r75K)
  - links: https://github.com/wangshusen/DeepLearning
- **语义分割前言**
  - [B station](https://www.bilibili.com/video/BV1ev411P7dR)
- **转置卷积（transposed convolution）**
  - [B station](https://www.bilibili.com/video/BV1mh411J7U4)
- **FCN网络结构详解(语义分割)**
  - [B station](https://www.bilibili.com/video/BV1J3411C7zd)
- **膨胀卷积(Dilated convolution)详解**
  - [B station](https://www.bilibili.com/video/BV1Bf4y1g7j8)
- **Pytorch官方实现的FCN网络结构**
  - [B station](https://www.bilibili.com/video/BV1ev411u7TX)
- **DeepLabV1网络简介(语义分割)**
  - [B station](https://www.bilibili.com/video/BV1SU4y1N7Ao)
- **DeepLabV2网络简介(语义分割)**
  - [B station](https://www.bilibili.com/video/BV1gP4y1G7TC)
- **DeepLabV3网络简介(语义分割)**
  - [B station](https://www.bilibili.com/video/BV1Jb4y1q7j7)
- **LR-ASPP模型简介(语义分割)**
  - [B station](https://www.bilibili.com/video/BV1LS4y1M76E)
- **LR-ASPP源码讲解(Pytorch)**
  - [B station](https://www.bilibili.com/video/BV13D4y1F7ML)
- **U-Net网络结构讲解(语义分割)**
  - [B station](https://www.bilibili.com/video/BV1Vq4y127fB)
- **U2Net网络结构讲解**
  - [B station](https://www.bilibili.com/video/BV1yB4y1z7mj)
  - links: https://arxiv.org/abs/2005.09007 https://github.com/xuebinqin/U-2-Net https://github.com/WZMIAOMIAO/deep-learning-for-image-processing/tree/master/pytorch_segmentation/u2net
- **验证时Batch Size要设置成1？**
  - [B station](https://www.bilibili.com/video/BV1AP4y1m7qt)
- **网络训练前需要热身？**
  - [B station](https://www.bilibili.com/video/BV1sd4y1b72w)
- **为啥我保存的权重文件那么大？**
  - [B station](https://www.bilibili.com/video/BV13P41137uM)
- **如何精确统计模型推理时间**
  - [B station](https://www.bilibili.com/video/BV1km4SeuEim)
- **1.1 卷积神经网络基础**
  - [B station](https://www.bilibili.com/video/BV1b7411T7DA)
- **1.2 卷积神经网络基础补充**
  - [B station](https://www.bilibili.com/video/BV1M7411M7D2)
- **2.1 pytorch官方demo(Lenet)**
  - [B station](https://www.bilibili.com/video/BV187411T7Ye)
- **2.2 tensorflow2官方demo**
  - [B station](https://www.bilibili.com/video/BV1n7411T7o6)
- **3.1 AlexNet网络结构详解与花分类数据集下载**
  - [B station](https://www.bilibili.com/video/BV1p7411T7Pc)
- **3.2 使用pytorch搭建AlexNet并训练花分类数据集**
  - [B station](https://www.bilibili.com/video/BV1W7411T7qc)
- **3.3 使用tensorflow2搭建Alexnet**
  - [B station](https://www.bilibili.com/video/BV1s7411T7vs)
- **4.1 VGG网络详解及感受野的计算**
  - [B station](https://www.bilibili.com/video/BV1q7411T7Y6)
- **4.2 使用pytorch搭建VGG网络**
  - [B station](https://www.bilibili.com/video/BV1i7411T7ZN)
- **4.3 使用tensorflow搭建VGG网络**
  - [B station](https://www.bilibili.com/video/BV1q7411T76b)
- **5.1 GoogLeNet网络详解**
  - [B station](https://www.bilibili.com/video/BV1z7411T7ie)
- **5.2 使用pytorch搭建GoogLeNet网络**
  - [B station](https://www.bilibili.com/video/BV1r7411T7M5)
- **5.3 使用tensorflow搭建GoogLeNet网络**
  - [B station](https://www.bilibili.com/video/BV1a7411T7Ht)
- **6.1 ResNet网络结构，BN以及迁移学习详解**
  - [B station](https://www.bilibili.com/video/BV1T7411T7wa)
- **6.1.2 ResNeXt网络结构**
  - [B station](https://www.bilibili.com/video/BV1Ap4y1p71v)
- **6.2 使用pytorch搭建ResNet并基于迁移学习训练**
  - [B station](https://www.bilibili.com/video/BV14E411H7Uw)
- **6.2.2 使用pytorch搭建ResNeXt并基于迁移学习训练**
  - [B station](https://www.bilibili.com/video/BV1rX4y1N7tE)
- **6.3 使用tensorflow搭建ResNet网络并基于迁移学习的方法进行训练**
  - [B station](https://www.bilibili.com/video/BV1WE41177Ya)
- **7.1 MobileNet网络详解**
  - [B station](https://www.bilibili.com/video/BV1yE411p7L7)
- **7.1.2 MobileNetv3网络详解**
  - [B station](https://www.bilibili.com/video/BV1GK4y1p7uE)
- **7.2 使用pytorch搭建MobileNetV2并基于迁移学习训练**
  - [B station](https://www.bilibili.com/video/BV1qE411T7qZ)
- **7.2.2 使用Pytorch搭建MobileNetV3并基于迁移学习训练**
  - [B station](https://www.bilibili.com/video/BV1zT4y1P7pd)
- **7.3 使用tensorflow搭建MobileNetV2模型并基于迁移学习训练**
  - [B station](https://www.bilibili.com/video/BV1NE411K7tX)
- **7.3.2 使用Tensorflow2搭建MobileNetV3并基于迁移学习训练**
  - [B station](https://www.bilibili.com/video/BV1KA411g7wX)
- **8.1 ShuffleNet v1 v2理论讲解**
  - [B station](https://www.bilibili.com/video/BV15y4y1Y7SY)
- **8.2 使用Pytorch搭建ShuffleNetv2**
  - [B station](https://www.bilibili.com/video/BV1dh411r76X)
- **8.3 使用Tensorflow2搭建ShuffleNetv2**
  - [B station](https://www.bilibili.com/video/BV1kr4y1N7bh)
- **9.1 EfficientNet网络详解**
  - [B station](https://www.bilibili.com/video/BV1XK4y1U7PX)
- **9.2使用Pytorch搭建EfficientNet网络**
  - [B station](https://www.bilibili.com/video/BV19z4y1179h)
- **9.3 使用Tensorflow2搭建EfficientNet网络**
  - [B station](https://www.bilibili.com/video/BV1PK4y1S7Jf)
- **10.1 EfficientNetV2网络详解**
  - [B station](https://www.bilibili.com/video/BV19v41157AU)
- **10.2 使用Pytorch搭建EfficientNetV2网络**
  - [B station](https://www.bilibili.com/video/BV1Xy4y1g74u)
- **10.3 使用tensorflow搭建EfficientNetV2并基于迁移学习训练**
  - [B station](https://www.bilibili.com/video/BV19K4y1g7m4)
- **Transformer中Self-Attention以及Multi-Head Attention详解**
  - [B station](https://www.bilibili.com/video/BV15v411W78M)
- **11.1 Vision Transformer(vit)网络详解**
  - [B station](https://www.bilibili.com/video/BV1Jh411Y7WQ)
- **11.2 使用pytorch搭建Vision Transformer(vit)模型**
  - [B station](https://www.bilibili.com/video/BV1AL411W7dT)
- **11.3 使用tensorflow2搭建vision transformer(ViT)模型，并基于迁移学习训练**
  - [B station](https://www.bilibili.com/video/BV1q64y1X7GY)
- **12.1 Swin-Transformer网络结构详解**
  - [B station](https://www.bilibili.com/video/BV1pL4y1v7jC)
- **12.2 使用Pytorch搭建Swin-Transformer网络**
  - [B station](https://www.bilibili.com/video/BV1yg411K7Yc)
- **12.3 使用tensorflow2搭建Swin-Transformer网络**
  - [B station](https://www.bilibili.com/video/BV1bR4y1t7qT)
- **13.1 ConvNeXt网络讲解**
  - [B station](https://www.bilibili.com/video/BV1SS4y157fu)
- **13.2 使用Pytorch搭建ConvNeXt网络**
  - [B station](https://www.bilibili.com/video/BV14S4y1L791)
- **13.3 使用Tensorflow2搭建ConvNeXt网络**
  - [B station](https://www.bilibili.com/video/BV1TS4y1V7Gz)
- **14.1 RepVGG网络讲解**
  - [B station](https://www.bilibili.com/video/BV15f4y1o7QR)
- **15.1 MobileViT网络讲解**
  - [B station](https://www.bilibili.com/video/BV1TG41137sb)
- **15.2 MobileViT源码解析(Pytorch)**
  - [B station](https://www.bilibili.com/video/BV1ae411L7Ki)
- **大雁顶vlog**
  - [B station](https://www.bilibili.com/video/BV1NVsCenE2h)
- **告别2024-穿越东西涌（冲）**
  - [B station](https://www.bilibili.com/video/BV1bJrwYAE9M)
- **路过万达看到有人唱歌，头脑一热也上去唱了一首（有好几处没唱好，见谅）**
  - [B station](https://www.bilibili.com/video/BV1eHRfYNEpp)
- **图像生成开篇**
  - [B station](https://www.bilibili.com/video/BV1617T6iEGb)
- **DDPM介绍与公式推导**
  - [B station](https://www.bilibili.com/video/BV15ZN66WERR)
- **Latent Diffusion Model**
  - [B station](https://www.bilibili.com/video/BV15DY36CE5p)
- **Scalable Diffusion Model with Transformers (DiTs)**
  - [B station](https://www.bilibili.com/video/BV1wLha63EHz)
- **2021级寒假导学·2021.12.29直播回放——寒假导学**
  - [B station](https://www.bilibili.com/video/BV1Pm4y1Q7zG)
- **2021级寒假导学·2021.01.06直播回放——如何准备竞赛**
  - [B station](https://www.bilibili.com/video/BV1s44y1j76u)
- **2021级寒假导学·2021.01.11直播回放——数字电路**
  - [B station](https://www.bilibili.com/video/BV1QZ4y1S77q)
- **2021级寒假导学·2021.01.13直播回放——整数类型**
  - [B station](https://www.bilibili.com/video/BV1SP4y1j7EG)
- **2021级寒假导学·2021.01.17直播回放——浮点数与类型转换**
  - [B station](https://www.bilibili.com/video/BV1v34y1B7UG)
- **2021级寒假导学·2021.01.19直播回放——IO与行业历史八卦**
  - [B station](https://www.bilibili.com/video/BV1h44y1L7V8)
- **2021级寒假导学·2021.01.20直播回放——IO与缓冲机制**
  - [B station](https://www.bilibili.com/video/BV11L411c7Q3)
- **2021级寒假导学·2021.02.03直播回放——物理空间到信息空间（数学建模和数组）**
  - [B station](https://www.bilibili.com/video/BV1cr4y1h7kZ)
- **2021级寒假导学·2021.02.05直播回放——项目与调试**
  - [B station](https://www.bilibili.com/video/BV1h34y1y7Dq)
- **2021级寒假导学·2021.02.08直播回放——指针与内存**
  - [B station](https://www.bilibili.com/video/BV16m4y1Z78E)
- **2021级寒假导学·2021.02.09直播回放——指针、IO与内存对齐**
  - [B station](https://www.bilibili.com/video/BV13i4y1f7hY)
- **从“卷积”、到“图像卷积操作”、再到“卷积神经网络”，“卷积”意义的3次改变**
  - [B station](https://www.bilibili.com/video/BV1VV411478E)
- **卷积神经网络的底层是傅里叶变换，傅里叶变换的底层是希尔伯特空间坐标变换**
  - [B station](https://www.bilibili.com/video/BV1ce4y1p7jF)
- **“L1和L2正则化”直观理解(之一)，从拉格朗日乘数法角度进行理解**
  - [B station](https://www.bilibili.com/video/BV1Z44y147xA)
- **“L1和L2正则化”直观理解(之二)，为什么又叫权重衰减？到底哪里衰减了？**
  - [B station](https://www.bilibili.com/video/BV1gf4y1c7Gg)
- **贝叶斯解释“L1和L2正则化”，本质上是最大后验估计。如何深入理解贝叶斯公式？**
  - [B station](https://www.bilibili.com/video/BV1fR4y177jP)
- **用VC维度理解SVM的结构风险最小化 & VC维是理解正则化的第4个角度**
  - [B station](https://www.bilibili.com/video/BV1ML41177qc)
- **1. 非计算机专业学编程难在哪？**
  - [B station](https://www.bilibili.com/video/BV123411p7rf)
- **2. 为什么所有编程语言都是数据+指令？**
  - [B station](https://www.bilibili.com/video/BV1Za411t7c6)
- **3. 编程是如何用数学解决现实问题的？**
  - [B station](https://www.bilibili.com/video/BV1gr4y1W7As)
- **4. 用“λ演算法”去理解，为什么函数式编程会有更少的bug**
  - [B station](https://www.bilibili.com/video/BV1d34y1v7xr)
- **5. 深度学习和元胞自动机有什么关系？会给编程带来什么样的颠覆性改变？**
  - [B station](https://www.bilibili.com/video/BV1BF411T7wh)
- **6. 软件工程背后的思想是如何影响编程的**
  - [B station](https://www.bilibili.com/video/BV1h3411G741)
- **7. 程序员的性格为什么那么轴，那都是有原因的**
  - [B station](https://www.bilibili.com/video/BV1gK411D7zc)
- **从头开始，把概率论、统计、信息论中零散的知识统一起来**
  - [B station](https://www.bilibili.com/video/BV1vv4y1B714)
- **如何用概率论解决真实问题？用随机变量去建模，最大的难题是相关关系**
  - [B station](https://www.bilibili.com/video/BV1Xs4y1z72n)
- **直观理解概率论里的“依概率收敛” “几乎处处收敛”“以分布收敛”**
  - [B station](https://www.bilibili.com/video/BV1Lm4y1q7pQ)
- **概率论里的特征函数，如何用卷积定理去理解**
  - [B station](https://www.bilibili.com/video/BV1Fj411X7nP)
- **真随机存在吗？量子力学如何超越概率论？经典概率和量子概率的联系与区别**
  - [B station](https://www.bilibili.com/video/BV1r14y1q761)
- **从编解码和词嵌入开始，一步一步理解Transformer，注意力机制(Attention)的本质是卷积神经网络(CNN)**
  - [B station](https://www.bilibili.com/video/BV1XH4y1T76e)
- **学习分享一年，对神经网络的理解全都在这40分钟里了**
  - [B station](https://www.bilibili.com/video/BV1FP411j7oW)
- **什么是SVM，如何理解软间隔？什么是合叶损失函数、铰链损失函数？SVM与感知机横向对比，挖掘机器学习本质**
  - [B station](https://www.bilibili.com/video/BV1zq4y1g74J)
- **“交叉熵”如何做损失函数？打包理解“信息量”、“比特”、“熵”、“KL散度”、“交叉熵”**
  - [B station](https://www.bilibili.com/video/BV15V411W7VB)
- **“损失函数”是如何设计出来的？直观理解“最小二乘法”和“极大似然估计法”**
  - [B station](https://www.bilibili.com/video/BV1Y64y1Q7hi)
- **softmax是为了解决归一问题凑出来的吗？和最大熵是什么关系？最大熵对机器学习为什么非常重要？**
  - [B station](https://www.bilibili.com/video/BV1cP4y1t7cP)
- **如何理解“梯度下降法”？什么是“反向传播”？通过一个视频，一步一步全部搞明白**
  - [B station](https://www.bilibili.com/video/BV1Zg411T71b)
- **“随机梯度下降、牛顿法、动量法、Nesterov、AdaGrad、RMSprop、Adam”，打包理解对梯度下降法的优化**
  - [B station](https://www.bilibili.com/video/BV1r64y1s7fU)
- **如果大数定律失效，机器学习还能学吗？幂律分布可以告诉你答案**
  - [B station](https://www.bilibili.com/video/BV1QR4y1W7eK)
- **VC维是如何推导出来的？为什么说它是机器学习理论最重要的发明？**
  - [B station](https://www.bilibili.com/video/BV1Nr4y1i7or)
- **直观解释：为什么噪声不是过拟合的原因?又什么只要没有过拟合就一定有噪声?**
  - [B station](https://www.bilibili.com/video/BV1a44y1M7qx)
- **Pytorch 搭建自己的Ghostnet-YoloV4目标检测平台（Bubbliiiing）-Ghostnet网络介绍与构建**
  - [B station](https://www.bilibili.com/video/BV1KS4y1g7yz)
  - links: https://github.com/bubbliiiing/mobilenet-yolov4-pytorch https://blog.csdn.net/weixin_44791964/article/details/120884617
- **Pytorch 搭建自己的Ghostnet-YoloV4目标检测平台（Bubbliiiing）-将Ghostnet添加到YoloV4当中**
  - [B station](https://www.bilibili.com/video/BV1q34y1t7rJ)
  - links: https://github.com/bubbliiiing/mobilenet-yolov4-pytorch https://blog.csdn.net/weixin_44791964/article/details/120884617
- **Pytorch 搭建自己的Ghostnet-YoloV4目标检测平台（Bubbliiiing）-训练与预测**
  - [B station](https://www.bilibili.com/video/BV1cF411x7aa)
  - links: https://github.com/bubbliiiing/mobilenet-yolov4-pytorch https://blog.csdn.net/weixin_44791964/article/details/120884617
- **如何下载与打开一个Github深度学习库**
  - [B station](https://www.bilibili.com/video/BV1GY4y1t7Cc)
  - links: https://blog.csdn.net/weixin_44791964/article/details/123440488
- **如何使用一个Github深度学习库**
  - [B station](https://www.bilibili.com/video/BV1nY411w7tr)
  - links: https://blog.csdn.net/weixin_44791964/article/details/123441983
- **如何分解与学习一个深度学习库**
  - [B station](https://www.bilibili.com/video/BV1UB4y197pQ)
  - links: https://blog.csdn.net/weixin_44791964/article/details/123443267
- **如何修改一个深度学习库**
  - [B station](https://www.bilibili.com/video/BV1FF411j7BP)
  - links: https://blog.csdn.net/weixin_44791964/article/details/123475899
- **Pytorch 搭建自己的YoloV5目标检测平台（Bubbliiiing 源码详解 训练 预测）-YoloV5整体结构介绍**
  - [B station](https://www.bilibili.com/video/BV1FZ4y1m777)
  - links: https://blog.csdn.net/weixin_44791964/article/details/121626848 https://github.com/bubbliiiing/yolov5-pytorch
- **Pytorch 搭建自己的YoloV5目标检测平台（Bubbliiiing 源码详解 训练 预测）-主干网络介绍**
  - [B station](https://www.bilibili.com/video/BV1FL4y1L7t1)
  - links: https://blog.csdn.net/weixin_44791964/article/details/121626848 https://github.com/bubbliiiing/yolov5-pytorch
- **Pytorch 搭建自己的YoloV5目标检测平台（Bubbliiiing 源码详解 训练 预测）-加强特征提取网络介绍**
  - [B station](https://www.bilibili.com/video/BV1cS4y1A7Wi)
  - links: https://blog.csdn.net/weixin_44791964/article/details/121626848 https://github.com/bubbliiiing/yolov5-pytorch
- **Pytorch 搭建自己的YoloV5目标检测平台（Bubbliiiing 源码详解 训练 预测）-先验框原理介绍**
  - [B station](https://www.bilibili.com/video/BV1AB4y1U7qX)
  - links: https://blog.csdn.net/weixin_44791964/article/details/121626848 https://github.com/bubbliiiing/yolov5-pytorch
- **Pytorch 搭建自己的YoloV5目标检测平台（Bubbliiiing 源码详解 训练 预测）-Yolo Head介绍**
  - [B station](https://www.bilibili.com/video/BV14Y4y1e7XC)
  - links: https://blog.csdn.net/weixin_44791964/article/details/121626848 https://github.com/bubbliiiing/yolov5-pytorch
- **Pytorch 搭建自己的YoloV5目标检测平台（Bubbliiiing 源码详解 训练 预测）-预测过程介绍**
  - [B station](https://www.bilibili.com/video/BV1R94y1d7yf)
  - links: https://blog.csdn.net/weixin_44791964/article/details/121626848 https://github.com/bubbliiiing/yolov5-pytorch
- **Pytorch 搭建自己的YoloV5目标检测平台（Bubbliiiing 源码详解 训练 预测）-数据集格式介绍**
  - [B station](https://www.bilibili.com/video/BV1kT4y1h7Jp)
  - links: https://blog.csdn.net/weixin_44791964/article/details/121626848 https://github.com/bubbliiiing/yolov5-pytorch
- **Pytorch 搭建自己的YoloV5目标检测平台（Bubbliiiing 源码详解 训练 预测）-YoloV5训练参数解析**
  - [B station](https://www.bilibili.com/video/BV1VY4y1p7yR)
  - links: https://blog.csdn.net/weixin_44791964/article/details/121626848 https://github.com/bubbliiiing/yolov5-pytorch
- **Pytorch 搭建自己的YoloV5目标检测平台（Bubbliiiing 源码详解 训练 预测）-训练VOC数据集**
  - [B station](https://www.bilibili.com/video/BV1iu411C7qa)
  - links: https://blog.csdn.net/weixin_44791964/article/details/121626848 https://github.com/bubbliiiing/yolov5-pytorch
- **Pytorch 搭建自己的YoloV5目标检测平台（Bubbliiiing 源码详解 训练 预测）-训练自己的数据集**
  - [B station](https://www.bilibili.com/video/BV1vS4y1w75r)
  - links: https://blog.csdn.net/weixin_44791964/article/details/121626848 https://github.com/bubbliiiing/yolov5-pytorch
- **Pytorch 搭建自己的YoloV5目标检测平台（Bubbliiiing 源码详解 训练 预测）-模型预测**
  - [B station](https://www.bilibili.com/video/BV1m94y1d7ja)
  - links: https://blog.csdn.net/weixin_44791964/article/details/121626848 https://github.com/bubbliiiing/yolov5-pytorch
- **Pytorch 搭建自己的YoloV5目标检测平台（Bubbliiiing 源码详解 训练 预测）-模型训练前的数据预处理**
  - [B station](https://www.bilibili.com/video/BV1i541127QC)
  - links: https://blog.csdn.net/weixin_44791964/article/details/121626848 https://github.com/bubbliiiing/yolov5-pytorch
- **Pytorch 搭建自己的YoloV5目标检测平台（Bubbliiiing 源码详解 训练 预测）-模型的损失构建**
  - [B station](https://www.bilibili.com/video/BV1nB4y1U7zY)
  - links: https://blog.csdn.net/weixin_44791964/article/details/121626848 https://github.com/bubbliiiing/yolov5-pytorch
- **AI写真现在这么卷了吗？不仅可以单人SOLO，还可以有闺蜜照和漫画风？**
  - [B station](https://www.bilibili.com/video/BV1c34y1K7by)
  - links: https://github.com/aigc-apps/sd-webui-EasyPhoto https://blog.csdn.net/weixin_44791964/article/details/132646955
- **EasyPhoto双人写真实现-闺蜜照？兄弟照？指不定还能团体照！**
  - [B station](https://www.bilibili.com/video/BV1bh4y1v7Vx)
  - links: https://github.com/aigc-apps/sd-webui-EasyPhoto https://blog.csdn.net/weixin_44791964/article/details/132646955
- **深入浅出Self-Attention自注意力机制与Transformer模块-自注意力机制详解**
  - [B station](https://www.bilibili.com/video/BV1Rm411S7ML)
  - links: https://github.com/bubbliiiing/blip-pytorch https://blog.csdn.net/weixin_44791964/article/details/135423390
- **Keras 搭建自己的Ghostnet-YoloV4目标检测平台（Bubbliiiing）-Ghostnet网络介绍与构建**
  - [B station](https://www.bilibili.com/video/BV19q4y1t7fJ)
  - links: https://github.com/bubbliiiing/mobilenet-yolov4-keras https://blog.csdn.net/weixin_44791964/article/details/109994880
- **Keras 搭建自己的Ghostnet-YoloV4目标检测平台（Bubbliiiing）-将Ghostnet添加到YoloV4当中**
  - [B station](https://www.bilibili.com/video/BV1Ku411X7JY)
  - links: https://github.com/bubbliiiing/mobilenet-yolov4-keras https://blog.csdn.net/weixin_44791964/article/details/109994880
- **Keras 搭建自己的Ghostnet-YoloV4目标检测平台（Bubbliiiing）-训练与预测**
  - [B station](https://www.bilibili.com/video/BV15S4y1F7aM)
  - links: https://github.com/bubbliiiing/mobilenet-yolov4-keras https://blog.csdn.net/weixin_44791964/article/details/109994880
- **整理了几个100%会踩的Python细节坑，提前防止脑血栓**
  - [B station](https://www.bilibili.com/video/BV1Vd4y1g7gX)
- **整理了十个100%提高效率的Python编程技巧，再上一层楼**
  - [B station](https://www.bilibili.com/video/BV1NT411M7DM)
  - links: https://blog.csdn.net/zzh516451964zzh/article/details/127038827
- **这些包括我在内都有的Python编程陋习，趁早改掉**
  - [B station](https://www.bilibili.com/video/BV1nG411w7qw)
- **列表推导式，Python最好的特性？可读性？**
  - [B station](https://www.bilibili.com/video/BV13d4y1b7md)
- **元组啊，不就是不可变的列表吗**
  - [B station](https://www.bilibili.com/video/BV1yt4y1N7kh)
- **Python可变类型的坑，不要再踩了**
  - [B station](https://www.bilibili.com/video/BV1rG4y1d7SV)
- **科研第一课，流程与工具全梳理**
  - [B station](https://www.bilibili.com/video/BV11VSwY1EkP)
- **十年投稿经验，一小时拿去**
  - [B station](https://www.bilibili.com/video/BV1qRmiYZE2d)
- **科研论文写作实操，哪些是重点？哪些要规避？**
  - [B station](https://www.bilibili.com/video/BV19TBsYfEsm)
- **科研论文各模块到底咋写？摘要|引言|方法|实验|总结**
  - [B station](https://www.bilibili.com/video/BV1KUBjYfEwQ)
- **科研论文写作实操-如何魔改、命名|图表排版与美观|实验占比与工作饱和度**
  - [B station](https://www.bilibili.com/video/BV1QJkYY4EEo)
- **论文Rebuttal真的有用！**
  - [B station](https://www.bilibili.com/video/BV1gw6hY5ENm)
- **论文投稿后务必知晓的注意事项！**
  - [B station](https://www.bilibili.com/video/BV1WerPYhEoy)
- **别让审稿人费劲！硕博毕业大论文从盲审到答辩的写作3大核心**
  - [B station](https://www.bilibili.com/video/BV128c4z6Ec3)
- **巧取SCI/CCF论文！审稿人亲述顶会写作投稿致命问题及解决方案**
  - [B station](https://www.bilibili.com/video/BV1SGAYzPE8f)
- **如何提高毕业大论文通过率？全流程解析从格式规范到盲审与答辩的实用技巧**
  - [B station](https://www.bilibili.com/video/BV1pWQSBrE7E)
- **论文写作避坑！大模型效率优化论文速成指南——AI辅助提效+中稿技巧**
  - [B station](https://www.bilibili.com/video/BV1xo9DBRE91)
- **3h精通Opencv-Python**
  - [B station](https://www.bilibili.com/video/BV16K411W7x9)
  - links: https://github.com/murtazahassan/Learn-OpenCV-in-3-hours
- **4h上手C++版Opencv**
  - [B station](https://www.bilibili.com/video/BV11A411T7rL)
  - links: https://www.murtazahassan.com/courses/opencv-cpp-course/
- **做了个一键转换与编辑图像标注文件软件，极大提高效率**
  - [B station](https://www.bilibili.com/video/BV1aP4y1Z7f3)
  - links: https://github.com/Fafa-DL/LabelConvert
- **图片数据不够？我做了一个免费的图像增强软件**
  - [B station](https://www.bilibili.com/video/BV1kR4y1T766)
  - links: https://github.com/Fafa-DL/Image-Augmentation
- **图像增强软件V2.0，适用于|目标检测|图像分割|图像分类|**
  - [B station](https://www.bilibili.com/video/BV1gZ4y1C7Ex)
  - links: https://github.com/Fafa-DL/Image-Augmentation
- **图像增强软件V3.0，我不允许你的数据比别人少**
  - [B station](https://www.bilibili.com/video/BV1Sv4y1S7yb)
  - links: https://github.com/Fafa-DL/Image-Augmentation
- **【Pytorch 与神经网络】pytorch 环境安装和基础操作，由浅及深彻底掌握Pytorch**
  - [B station](https://www.bilibili.com/video/BV1Vj421R7HD)
- **【Pytorch 与神经网络】一节课搞定数据集处理｜模型训练+分布式训练**
  - [B station](https://www.bilibili.com/video/BV1hr421x7qH)
- **【Pytorch 与神经网络】机器视觉概念+代码实战教程**
  - [B station](https://www.bilibili.com/video/BV1dz421k7AG)
- **【Pytorch 与神经网络】机器视觉任务介绍+代码实战教程**
  - [B station](https://www.bilibili.com/video/BV1sK421a7Rm)
- **【Pytorch 与神经网络】nlp模型介绍+代码实战教程**
  - [B station](https://www.bilibili.com/video/BV1xE421T7xb)
- **【Pytorch 与神经网络】nlp任务介绍+代码复现**
  - [B station](https://www.bilibili.com/video/BV1GT421U742)
- **【Pytorch 与神经网络】生成式模型介绍，附：代码实战教程**
  - [B station](https://www.bilibili.com/video/BV1km411B7cj)
- **Pytorch与神经网络 | 模型训练/学习方式**
  - [B station](https://www.bilibili.com/video/BV15s421K76x)
- **1.入门知识与子词分词器实现-从零到一搭建Transformer项目**
  - [B station](https://www.bilibili.com/video/BV17UwyzLE9y)
- **2.多头注意力与位置编码-从零到一搭建Transformer项目**
  - [B station](https://www.bilibili.com/video/BV1EUwyzLEG1)
- **3.构建Transformer模型-从零到一搭建Transformer项目**
  - [B station](https://www.bilibili.com/video/BV129AJzZE3M)
- **具身智能——LLM for robotics**
  - [B station](https://www.bilibili.com/video/BV1CH4y1G7wx)
- **具身智能——LLM for robotics(2)**
  - [B station](https://www.bilibili.com/video/BV16x4y1v7EU)
- **一节课搞定YOLO-World项目实战与轻量化部署**
  - [B station](https://www.bilibili.com/video/BV1eK3uz8E43)
- **一节课搞定自动驾驶点云目标检测**
  - [B station](https://www.bilibili.com/video/BV1JL39zwEXZ)
- **一节课搞定YOLOv9详解|代码实战|轻量部署**
  - [B station](https://www.bilibili.com/video/BV1rnGnzkEws)
- **一节课搞定YOLOv10原理&代码实战**
  - [B station](https://www.bilibili.com/video/BV1FPGgzyE5w)
- **一节课搞定YOLOv8项目实战**
  - [B station](https://www.bilibili.com/video/BV1FHuFzrEWg)
- **一节课看尽深度学习目标检测这十年！**
  - [B station](https://www.bilibili.com/video/BV1Cju1zrEAD)
- **一节课搞懂机器人中的多模态及代码实战**
  - [B station](https://www.bilibili.com/video/BV1NcgwzoESp)
- **超越YOLO！一节课搞懂新生代目标检测器Grounding DINO**
  - [B station](https://www.bilibili.com/video/BV1rjgBzHEBW)
- **一节课搞定YOLOv8多目标实例分割与跟踪详解+实战**
  - [B station](https://www.bilibili.com/video/BV15n8czXEBu)
- **一节课搞懂医学分割终结者模型MedSAM**
  - [B station](https://www.bilibili.com/video/BV1GP8ezCEa2)
- **一节课搞懂基于mamba的自动驾驶感知**
  - [B station](https://www.bilibili.com/video/BV1318RzKEeT)
- **自动驾驶大一统新作，一节课搞懂DriveTransformer**
  - [B station](https://www.bilibili.com/video/BV1WthHzaEa8)
- **超越所有OCC视觉方案，一节课搞懂CVT-OCC算法**
  - [B station](https://www.bilibili.com/video/BV14RtJzsENU)
- **分割一切医学图像，一节课搞懂超级模块MedSAM**
  - [B station](https://www.bilibili.com/video/BV1dTtqznECo)
- **实现自动驾驶实时协同感知，一节课速通Mamba高阶魔改**
  - [B station](https://www.bilibili.com/video/BV1JLtoz2EKs)
- **迈向3D全景分割大一统，一节课速通PanoOcc算法**
  - [B station](https://www.bilibili.com/video/BV1XqbWzjEzW)
- **多模态大模型高效微调方法，视觉语言融合SOTA**
  - [B station](https://www.bilibili.com/video/BV1aae8zkEja)
- **车企人眼中的3D占用预测网络，一节课速通CVT-OCC**
  - [B station](https://www.bilibili.com/video/BV1zrvNzpEW6)
- **多模态大模型+具身智能，一节课解锁RoboBrain顶会创新**
  - [B station](https://www.bilibili.com/video/BV1rEptzWEqT)
- **顶会论文写作与实例分享，用对方法篇篇都是SCI！**
  - [B station](https://www.bilibili.com/video/BV1zHW3z3EMw)
- **一节课掌握多模态大模型统一分割框架： OMG-LLaVA**
  - [B station](https://www.bilibili.com/video/BV1e8nwzAEPh)
- **大模型微调效率巅峰，一节课速通顶会微调思路VB-LoRA**
  - [B station](https://www.bilibili.com/video/BV1GMngznEVi)
- **基于transformer的跨模态3D目标检测SOTA！易复现！**
  - [B station](https://www.bilibili.com/video/BV1LRsnzYEaf)
- **2025新拐点！一节课概览端到端自动驾驶，直击技术最前沿**
  - [B station](https://www.bilibili.com/video/BV1qR1CBeEeu)
- **自动驾驶OCC感知算法大爆！全方位解读Flash-OCC**
  - [B station](https://www.bilibili.com/video/BV1bP2ABgEQU)
- **自动驾驶感知是否已接近极限？一节课全面盘点技术前沿！**
  - [B station](https://www.bilibili.com/video/BV1PXkkBKEej)
- **一节课搞定自动驾驶视觉感知算法-BEVFormer**
  - [B station](https://www.bilibili.com/video/BV1FCyGBmEf6)
- **实现高级别自动驾驶的关键：一节课搞定多传感器融合**
  - [B station](https://www.bilibili.com/video/BV1E1ycB2Ehp)
- **老兵不死！百度开源BEVWorld：BEV潜在空间构建多模态世界模型，全面理解自动驾驶~**
  - [B station](https://www.bilibili.com/video/BV1g2UQBXEy2)
- **自动驾驶绕不开的前沿技术，一节课聊聊点云深度学习的二三事**
  - [B station](https://www.bilibili.com/video/BV1vwStBbEap)
- **一节课搞定自动驾驶之规控与预测，研梦非凡自动驾驶必学系列**
  - [B station](https://www.bilibili.com/video/BV1nQmxB8E1y)
- **一节课搞定毫米波雷达必知必学15个知识点，研梦非凡自动驾驶必学系列**
  - [B station](https://www.bilibili.com/video/BV1smq8BpERr)
- **一节课认知基于分层强化学习的规控算法，研梦非凡自动驾驶必学系列**
  - [B station](https://www.bilibili.com/video/BV1UPBKBtEz5)
- **自动驾驶热门方向：一节课掌握基于提示学习的VLM蒸馏新方法！**
  - [B station](https://www.bilibili.com/video/BV1zavWBHEnz)
- **大语言模型对时间序列预测有用吗？带你详拆一篇ICLR佳作**
  - [B station](https://www.bilibili.com/video/BV1x6i9BHEE1)
- **吊打一切卷积方法！审稿人带你看摸透Transformer+语义分割**
  - [B station](https://www.bilibili.com/video/BV1ESkFBME7F)
- **重温魔改Mamba核心：超车Transformer，备战今年CV各大顶会！**
  - [B station](https://www.bilibili.com/video/BV1th6gBVEJc)
- **一节课看懂分割一切视觉大模型，FastSAM论文/代码以及在工业场景中的应用**
  - [B station](https://www.bilibili.com/video/BV1mRcEzHEr9)
- **一节课看懂分割一切视觉大模型，FastSAM论文/代码以及在工业场景中的应用**
  - [B station](https://www.bilibili.com/video/BV1PpfbBTEUJ)
- **VoxFormer算法解析：自驾感知算法革命，英伟达技术力拉满！**
  - [B station](https://www.bilibili.com/video/BV1Sxwcz3EZa)
- **VoxFormer深度剖析：自驾感知算法革命，英伟达技术力拉满！**
  - [B station](https://www.bilibili.com/video/BV1Sxwcz3EqZ)
- **大模型加速算法：FlashAttention-V1原理篇，不会CUDA也能轻松看懂！**
  - [B station](https://www.bilibili.com/video/BV1VVDLB4Ecw)
- **大模型加速算法：FlashAttention-V2原理篇，不会CUDA也能轻松看懂！**
  - [B station](https://www.bilibili.com/video/BV1SnD4BnEJ8)
- **大模型加速算法：FlashAttention-V3原理篇，不会CUDA也能轻松看懂！**
  - [B station](https://www.bilibili.com/video/BV1p7QwBgETM)
- **大模型加速算法：FlashAttention论文解读，不会CUDA也能轻松看懂！**
  - [B station](https://www.bilibili.com/video/BV1KFQEBoEo9)
- **YOLOE：实时通用目标检测的感知一切，开放词汇系列顶会文献精读**
  - [B station](https://www.bilibili.com/video/BV1h7d5BYEee)
- **|AI学习路线分享|做完这些，你已经成为机器学习方面的专家**
  - [B station](https://www.bilibili.com/video/BV16341177c1)
- **非科班上岸算法工程师，我的心得分享**
  - [B station](https://www.bilibili.com/video/BV1M34y117gp)
- **『帮帮TA』导师佛系无实习无成果无项目，救救孩子**
  - [B station](https://www.bilibili.com/video/BV1ri4y127YT)
- **『帮帮TA』导师的首届学生|组会频繁|非科班|基础差**
  - [B station](https://www.bilibili.com/video/BV1Pa411878V)
- **关于裁员，我对读研期间所见所闻进行了复盘**
  - [B station](https://www.bilibili.com/video/BV12S4y1N7nG)
- **这份实用校招指南，请查收**
  - [B station](https://www.bilibili.com/video/BV17Z4y1e7zk)
  - links: https://www.wondercv.com/ https://www.nowcoder.com/ https://www.bilibili.com/read/cv15472202
- **【一个月吃透深度学习】零基础都能看懂，人工智能基础入门必看！**
  - [B station](https://www.bilibili.com/video/BV1u5411i7K7)
- **【一个月吃透深度学习】长短期记忆网络教程，零基础人工智能入门必备！**
  - [B station](https://www.bilibili.com/video/BV1Tg4y1U7Lp)
- **【一个月吃透深度学习】循环网络与一维卷积的应用，零基础都能看懂，人工智能入门必看！**
  - [B station](https://www.bilibili.com/video/BV1qK4y1z7AN)
- **【一个月吃透深度学习】项目实战【数据数值化（张量化）覆写torch下的Dataset类】，零基础人工智能入门必备！**
  - [B station](https://www.bilibili.com/video/BV1DB421z7E8)
- **【一个月吃透深度学习】项目实战（Pytorch实现卷积网络的文本分类），零基础人工智能入门必备！**
  - [B station](https://www.bilibili.com/video/BV1xB421z7HU)
- **【一个月吃透深度学习】项目实战（Pytorch实现神经网络的文本分类），零基础人工智能入门必备！**
  - [B station](https://www.bilibili.com/video/BV1zb4y1N72M)
- **【一个月吃透深度学习】Pytorch实现文本分类｜IMDB电影评论分析项目实战，零基础入门必备！**
  - [B station](https://www.bilibili.com/video/BV1j642137J4)
- **吃透《统计学习方法》**
  - [B station](https://www.bilibili.com/video/BV1tZ4y1U7ot)
- **《统计学习方法》第一章课后习题解答**
  - [B station](https://www.bilibili.com/video/BV1pP411M7DX)
- **《统计学习方法》第二章：感知机**
  - [B station](https://www.bilibili.com/video/BV1C44y1P7tA)
- **《统计学习方法》第三章：K近邻**
  - [B station](https://www.bilibili.com/video/BV1pi4y1D7Y3)
- **《统计学习方法》第四章：朴素贝叶斯**
  - [B station](https://www.bilibili.com/video/BV1sS4y1Y7mN)
- **《统计学习方法》第五章：决策树**
  - [B station](https://www.bilibili.com/video/BV19B4y127Nv)
- **《统计学习方法》第六章：逻辑回归**
  - [B station](https://www.bilibili.com/video/BV1aa411a7P8)
- **《统计学习方法》第七章：最大熵模型**
  - [B station](https://www.bilibili.com/video/BV1jY4y1t7Jt)
- **《统计学习方法》第八章：支持向量机**
  - [B station](https://www.bilibili.com/video/BV1ct4y157B1)
- **《统计学习方法》第九章：提升方法**
  - [B station](https://www.bilibili.com/video/BV1iP41177MY)
- **《统计学习方法》第十章：EM算法**
  - [B station](https://www.bilibili.com/video/BV12P411N7sj)
- **《统计学习方法》第十一章：隐马尔可夫模型**
  - [B station](https://www.bilibili.com/video/BV1HN411x736)
- **《统计学习方法》第十二章：条件随机场**
  - [B station](https://www.bilibili.com/video/BV11b4y1K7tN)
- **《统计学习方法》第十三章：无监督学习**
  - [B station](https://www.bilibili.com/video/BV1cxdaYrE2J)
- **《统计学习方法》第十四章：聚类**
  - [B station](https://www.bilibili.com/video/BV1Swj3zBEM2)
- **YOLOV8详解与轻量部署--YOLO基础篇**
  - [B station](https://www.bilibili.com/video/BV1b6cwe7ETq)
- **YOLOV8详解与轻量部署--YOLOv5、YOLOv8解析**
  - [B station](https://www.bilibili.com/video/BV1bAcBeJEfT)
- **YOLOV8详解与轻量部署--代码实战**
  - [B station](https://www.bilibili.com/video/BV1aJwweREvx)
- **YOLOV8详解与轻量部署--推理部署**
  - [B station](https://www.bilibili.com/video/BV16GfhYGELa)
- **论文泛读-如何快速了解一篇文章（大模型方向为例）**
  - [B station](https://www.bilibili.com/video/BV18SNWexEdk)
- **论文泛读-题目|作者|单位|摘要|结论怎么看？**
  - [B station](https://www.bilibili.com/video/BV1sKNSeDEA9)
- **论文泛读-图、表、公式、实验很重要**
  - [B station](https://www.bilibili.com/video/BV1VNAVeZEG4)
- **我将维护一个集成各主干网络的图像分类项目**
  - [B station](https://www.bilibili.com/video/BV1SY411P7Nd)
  - links: https://github.com/Fafa-DL/Awesome-Backbones
- **最新Windows配置VSCode与Anaconda环境**
  - [B station](https://www.bilibili.com/video/BV1QD4y147ek)
- **『图像分类』从零环境搭建&快速开始**
  - [B station](https://www.bilibili.com/video/BV1fe4y1s77Q)
  - links: https://github.com/Fafa-DL/Awesome-Backbones
- **『图像分类』模型如何搭建|文件如何调用**
  - [B station](https://www.bilibili.com/video/BV12a411772h)
  - links: https://github.com/Fafa-DL/Awesome-Backbones https://blog.csdn.net/zzh516451964zzh/article/details/124864793
- **『图像分类』数据预处理|数据增强**
  - [B station](https://www.bilibili.com/video/BV1zY4y167Ju)
  - links: https://github.com/Fafa-DL/Awesome-Backbones
- **『图像分类』学习率更新策略|优化器**
  - [B station](https://www.bilibili.com/video/BV1WT4y1q7qN)
  - links: https://github.com/Fafa-DL/Awesome-Backbones https://blog.csdn.net/zzh516451964zzh/article/details/124879584
- **『图像分类』配置文件补充说明**
  - [B station](https://www.bilibili.com/video/BV1bt4y1W7mm)
  - links: https://github.com/Fafa-DL/Awesome-Backbones
- **【一个月吃透机器学习】李航《统计学习方法》，零基础同学必学课程！！！**
  - [B station](https://www.bilibili.com/video/BV14j421U7oW)
- **【一个月吃透机器学习】K近邻，感知机，手把手代码实战教程！！！**
  - [B station](https://www.bilibili.com/video/BV1zC411p7N6)
- **【一个月吃透机器学习】朴素贝叶斯原理，及手把手代码实战教程！！！**
  - [B station](https://www.bilibili.com/video/BV17W421A73j)
- **【一个月吃透机器学习】朴素贝叶斯知识点讲解，手把手代码实战教程！**
  - [B station](https://www.bilibili.com/video/BV1ax421C7oH)
- **【一个月吃透机器学习】朴素贝叶斯代码实战，手把手教你写代码**
  - [B station](https://www.bilibili.com/video/BV1LZ421t7oS)
- **【一个月吃透机器学习】PageRank算法前沿理论详解＋代码实战教程**
  - [B station](https://www.bilibili.com/video/BV1sf421f7iq)
- **【一个月吃透机器学习】支持向量机SVM前沿理论详解＋实现代码复现详程**
  - [B station](https://www.bilibili.com/video/BV19K421a7Xy)
- **AI对程序员的冲击**
  - [B station](https://www.bilibili.com/video/BV1tDRCBzEzj)
- **你真的需要和大模型聊一下人生**
  - [B station](https://www.bilibili.com/video/BV1t35g62E2v)
- **AGI来了，人类最大的危机不是失业**
  - [B station](https://www.bilibili.com/video/BV1hiMM6FEFT)
- **美国政府为什么要持股OpenAI？ 答案比你想的更可怕**
  - [B station](https://www.bilibili.com/video/BV17ET16VErB)
- **调用大模型到底是英文好还是中文好？**
  - [B station](https://www.bilibili.com/video/BV1hjMa6cEvB)
- **Anthropic最新论文：大模型也会口是心非**
  - [B station](https://www.bilibili.com/video/BV1FCNL6oEta)
- **什么是HarnessEngineering？驾驭工程**
  - [B station](https://www.bilibili.com/video/BV13uojB6Eyh)
- **HarnessEngineering 如何进行任务拆分**
  - [B station](https://www.bilibili.com/video/BV1iwojBLEN5)
- **HarnessEngineering 如何引入外部知识 RAG，PageIndex，知识图谱，百科**
  - [B station](https://www.bilibili.com/video/BV118RMBNE6j)
- **Harness 记忆 如何给智能体增加记忆**
  - [B station](https://www.bilibili.com/video/BV1545m6cEqu)
- **Function Calling、MCP、CLI 到底差在哪？AI Agent 工具调用一次讲清**
  - [B station](https://www.bilibili.com/video/BV1SsE368ELz)
- **AI Agent 沙箱技术演进史 容器 虚拟机 E2B**
  - [B station](https://www.bilibili.com/video/BV1jKj66JE8W)
- **什么是强化学习《RethinFun强化学习》1.1**
  - [B station](https://www.bilibili.com/video/BV14swKz7Ego)
- **马尔科夫决策过程《RethinFun强化学习》1.2**
  - [B station](https://www.bilibili.com/video/BV1rXwNzuEmJ)
- **价值函数《RethinFun强化学习》1.3**
  - [B station](https://www.bilibili.com/video/BV1kDwNz6EgY)
- **贝尔曼方程《RethinFun强化学习》1.4**
  - [B station](https://www.bilibili.com/video/BV1kDwNz6EZd)
- **动态规划《RethinFun强化学习》2.1**
  - [B station](https://www.bilibili.com/video/BV1ECAAzaECF)
- **无模型方法MC、TD、SARSA、Q-Learning《RethinFun强化学习》2.2**
  - [B station](https://www.bilibili.com/video/BV1riAAzKEkJ)
- **动手实现悬崖漫步 SARSA、Q-Learning《RethinFun强化学习》2.3**
  - [B station](https://www.bilibili.com/video/BV1wiAAzTEun)
- **DQN原理及核心机制：经验回放|目标网络《RethinFun强化学习》3.1**
  - [B station](https://www.bilibili.com/video/BV1rkQcBPE8q)
- **DQN的进阶技巧：Double DQN | DuelingDQN《RethinFun强化学习》3.2**
  - [B station](https://www.bilibili.com/video/BV1w6QcBiEHy)
- **DQN动手实现“登月舱”：Lunar Lander《RethinFun强化学习》3.3**
  - [B station](https://www.bilibili.com/video/BV1w6QcBiEqf)
- **强化学习策略网络Policy Network**
  - [B station](https://www.bilibili.com/video/BV1nz5t6nEYX)
- **强化学习策略梯度算法原理**
  - [B station](https://www.bilibili.com/video/BV1nz5t6nEyE)
- **强化学习REINFORCE算法**
  - [B station](https://www.bilibili.com/video/BV1fC5t6mEjf)
- **强化学习增加Baseline**
  - [B station](https://www.bilibili.com/video/BV1EC5t6mES8)
- **Actor-Critic算法 A2C**
  - [B station](https://www.bilibili.com/video/BV1TBVN6fEuG)
- **GAE广义优势估计**
  - [B station](https://www.bilibili.com/video/BV1EdVN67E5h)
- **PPO近端策略优化**
  - [B station](https://www.bilibili.com/video/BV1zdVN67EVD)
- **PPO的Loss函数Entropy Loss**
  - [B station](https://www.bilibili.com/video/BV1f9VN6mEJm)
- **PPO的代码实现**
  - [B station](https://www.bilibili.com/video/BV1f9VN6mE2p)
- **生成算法数学基础（凸函数，Jensen不等式，KL散度）**
  - [B station](https://www.bilibili.com/video/BV1gexMzpEc7)
- **VAE算法讲解 （变分自编码器 Variational Auto-Encoder）**
  - [B station](https://www.bilibili.com/video/BV1xFxMz1EMS)
  - links: https://www.kaggle.com/datasets/jessicali9530/celeba-dataset https://pan.baidu.com/s/1hT-FUWm_fuVJQiGT5-HvrA?pwd=5rpm https://github.com/RethinkFun/VAE/blob/main/vae.py
- **图像生成 扩散模型 DDPM算法讲解（一）：直观理解**
  - [B station](https://www.bilibili.com/video/BV16ZsPz4ECF)
- **图像生成 扩散模型 DDPM算法讲解（二）：数学推导和代码实现**
  - [B station](https://www.bilibili.com/video/BV11KsPzwE2m)
  - links: https://www.kaggle.com/datasets/jessicali9530/celeba-dataset https://pan.baidu.com/s/1hT-FUWm_fuVJQiGT5-HvrA?pwd=5rpm https://github.com/RethinkFun/DDPM/blob/main/ddpm.py
- **FlowMatching的直观理解**
  - [B station](https://www.bilibili.com/video/BV142C2BSEbm)
- **FlowMatching的公式推导和源码实现**
  - [B station](https://www.bilibili.com/video/BV1K2C2BSEZB)
  - links: https://github.com/RethinkFun/FLowMatching/blob/main/flowmatching.py https://www.kaggle.com/datasets/jessicali9530/celeba-dataset https://pan.baidu.com/s/1hT-FUWm_fuVJQiGT5-HvrA?pwd=5rpm
- **Score Based Model 直观理解**
  - [B station](https://www.bilibili.com/video/BV19cBMBMEzp)
  - links: https://arxiv.org/abs/1907.05600 https://github.com/ermongroup/ncsn
- **Score Based Model公式推导及源码实现**
  - [B station](https://www.bilibili.com/video/BV1GNBMBiEch)
  - links: https://arxiv.org/abs/1907.05600 https://github.com/ermongroup/ncsn
- **扩散模型：SDE，统一Score模型和DDPM**
  - [B station](https://www.bilibili.com/video/BV1PervBGEeY)
- **条件和引导生成，conditional generation，Classifier Guidance，Classifier-Free Guidance，CFG**
  - [B station](https://www.bilibili.com/video/BV1EWBfBxENc)
- **DeepSeek-MOE原理讲解**
  - [B station](https://www.bilibili.com/video/BV1uUPieDEK1)
- **DeepSeek-v2 MLA 原理讲解**
  - [B station](https://www.bilibili.com/video/BV1BYXRYWEMj)
- **DeepSeek-v3原理讲解多token预测 MTP**
  - [B station](https://www.bilibili.com/video/BV1jA9HYfEAC)
- **DeepSeek-GRPO**
  - [B station](https://www.bilibili.com/video/BV1enQLYKEA5)
- **DeepSeekMathv2模型讲解|迈向自我验证的数学推理**
  - [B station](https://www.bilibili.com/video/BV1C2S4BzECy)
- **DINO v1 算法讲解**
  - [B station](https://www.bilibili.com/video/BV18AULBjED6)
- **DINO v2 算法讲解**
  - [B station](https://www.bilibili.com/video/BV19nUDBDEd8)
- **DINO v3 算法讲解**
  - [B station](https://www.bilibili.com/video/BV1ExUfBnEts)
- **PCA 主成分分析算法讲解(Principal Component Analysis)**
  - [B station](https://www.bilibili.com/video/BV1sty6BaE5J)
- **《RethinkFun深度学习教程》：前言**
  - [B station](https://www.bilibili.com/video/BV1do3LzUE6q)
  - links: https://github.com/RethinkFun/DeepLearning https://pan.baidu.com/s/1uDek4amMrPYDeu-R93CXrQ?pwd=etup
- **《RethinkFun深度学习教程》：1.1什么是深度学习**
  - [B station](https://www.bilibili.com/video/BV1do3LzUEzr)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：1.2如何学习深度学习**
  - [B station](https://www.bilibili.com/video/BV1oo3LzUETV)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：第二章 线性代数 2.1什么是向量**
  - [B station](https://www.bilibili.com/video/BV1oo3LzUE83)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：2.2向量的基**
  - [B station](https://www.bilibili.com/video/BV1jo3LzSE4b)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：2.3线性变换和矩阵**
  - [B station](https://www.bilibili.com/video/BV1oo3LzUEsU)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：2.4向量的点乘**
  - [B station](https://www.bilibili.com/video/BV1io3LzSEqC)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：2.5向量的叉乘**
  - [B station](https://www.bilibili.com/video/BV1oo3LzUE3r)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：3.1函数的极限**
  - [B station](https://www.bilibili.com/video/BV1nu3SzSE8f)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：3.2导数的定义**
  - [B station](https://www.bilibili.com/video/BV1pN3SzpE1z)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：3.3常用求导公式**
  - [B station](https://www.bilibili.com/video/BV1jA3XzHEY1)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：3.4导数运算法则**
  - [B station](https://www.bilibili.com/video/BV1erGFzBEx5)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：3.5一元函数微分**
  - [B station](https://www.bilibili.com/video/BV1EU3iz1Eit)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：3.6偏导数**
  - [B station](https://www.bilibili.com/video/BV1883BziECP)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：3.7全微分**
  - [B station](https://www.bilibili.com/video/BV19k3qzBELC)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：3.8方向导数与梯度**
  - [B station](https://www.bilibili.com/video/BV1Ae3CzuE9M)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：3.9定积分**
  - [B station](https://www.bilibili.com/video/BV1Yh3kzHEdu)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：第四章：深度学习里的概率与统计**
  - [B station](https://www.bilibili.com/video/BV14U3yzmEFz)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：4.2 概率里的基本运算**
  - [B station](https://www.bilibili.com/video/BV16J3yzqEWw)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：4.3随机变量及其分布**
  - [B station](https://www.bilibili.com/video/BV1yHGpzSEKR)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：4.4数学期望与方差**
  - [B station](https://www.bilibili.com/video/BV1FUGHzVE14)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：4.5大数定律**
  - [B station](https://www.bilibili.com/video/BV1AkGHz7EiQ)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：4.6 条件概率**
  - [B station](https://www.bilibili.com/video/BV1JSGHzkEku)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：4.7中心极限定理和正态分布**
  - [B station](https://www.bilibili.com/video/BV14XGnzDEkn)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：4.8极大似然估计**
  - [B station](https://www.bilibili.com/video/BV1kPGHzVEup)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：第五章 线性回归 5.1 一元线性回归**
  - [B station](https://www.bilibili.com/video/BV1hDuPzTED5)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：5.2 给线性回归增加偏置**
  - [B station](https://www.bilibili.com/video/BV1ocu6zjEUq)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》5.3 梯度下降算法**
  - [B station](https://www.bilibili.com/video/BV1wguzzpE4Z)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》5.4 多元线性回归**
  - [B station](https://www.bilibili.com/video/BV1J5uzzUEhW)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：5.5动手实现多元线性回归**
  - [B station](https://www.bilibili.com/video/BV1J5uzzUE7F)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：5.6线性回归只能拟合直线吗？**
  - [B station](https://www.bilibili.com/video/BV1J5uzzUEWX)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：第六章 线性回归 6.1 PyTorch简介**
  - [B station](https://www.bilibili.com/video/BV1eVuHzxEyq)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：6.2 CPU环境下的PyTorch安装**
  - [B station](https://www.bilibili.com/video/BV1V9uJznENq)
  - links: https://github.com/RethinkFun/DeepLearning
- **一次搞定Anaconda，PyTorch，CUDA，VS Code的安装**
  - [B station](https://www.bilibili.com/video/BV131upzWETr)
  - links: https://github.com/RethinkFun/DeepLearning
- **一次学懂PyTorch里的Tensor**
  - [B station](https://www.bilibili.com/video/BV1G1umz8EKH)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：6.5 计算图与自动求梯度**
  - [B station](https://www.bilibili.com/video/BV1KZumzHEZS)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：6.6 用PyTorch实现线性回归**
  - [B station](https://www.bilibili.com/video/BV1ppumzLEdG)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：6.7 优美的Loss曲线**
  - [B station](https://www.bilibili.com/video/BV1ALuRzPEmS)
  - links: https://github.com/RethinkFun/DeepLearning
- **为什么深度学习需要做Normalization？**
  - [B station](https://www.bilibili.com/video/BV1kJuozTE14)
  - links: https://github.com/RethinkFun/DeepLearning
- **逻辑回归和线性回归有什么关系？**
  - [B station](https://www.bilibili.com/video/BV1q3udzREu4)
  - links: https://github.com/RethinkFun/DeepLearning
- **逻辑回归的loss为什么不用MSE**
  - [B station](https://www.bilibili.com/video/BV1KGgbzPEcD)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：7.3多元逻辑回归**
  - [B station](https://www.bilibili.com/video/BV1NLgbzwE6X)
  - links: https://github.com/RethinkFun/DeepLearning
- **为什么要区分训练集和验证集？**
  - [B station](https://www.bilibili.com/video/BV1ejg8zJE9a)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：7.5 欠拟合和过拟合**
  - [B station](https://www.bilibili.com/video/BV1sig8ziEBa)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：7.6 二分类模型的评价指标**
  - [B station](https://www.bilibili.com/video/BV1XCghzSEKu)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：7.7 梯度下降算法的改进**
  - [B station](https://www.bilibili.com/video/BV1ZngezAEFn)
  - links: https://github.com/RethinkFun/DeepLearning
- **PyTorch+逻辑回归进行Titanic生存预测**
  - [B station](https://www.bilibili.com/video/BV1dUg5zGERE)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：7.9 PyTorch里的Dataset和DataLoader**
  - [B station](https://www.bilibili.com/video/BV1vUg5zGEEX)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：7.10 利用PyTorch定义逻辑回归模型**
  - [B station](https://www.bilibili.com/video/BV1i2g5zCEqG)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：7.11 用逻辑回归对Titanic数据进行训练**
  - [B station](https://www.bilibili.com/video/BV1i2g5zCEMw)
  - links: https://github.com/RethinkFun/DeepLearning
- **换个角度理解神经网络：从逻辑回归到神经网络**
  - [B station](https://www.bilibili.com/video/BV13XgWzhE4q)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：8.2 大脑与神经网络**
  - [B station](https://www.bilibili.com/video/BV1RTgWzwEbv)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：8.3 神经网络与矩阵计算**
  - [B station](https://www.bilibili.com/video/BV1xWgWznEQK)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：8.4 激活函数**
  - [B station](https://www.bilibili.com/video/BV1y1gpzjEAB)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：8.5 神经网络的多分类**
  - [B station](https://www.bilibili.com/video/BV1RWgpzhEM2)
  - links: https://github.com/RethinkFun/DeepLearning
- **不用PyTorch，自己动手实现神经网络训练**
  - [B station](https://www.bilibili.com/video/BV1kRbkz2Eyr)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：8.7 梯度消失梯度爆炸**
  - [B station](https://www.bilibili.com/video/BV1kRbkz2ECU)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：8.8 手动实现多分类神经网络**
  - [B station](https://www.bilibili.com/video/BV1xab1zFERW)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：8.9 用PyTorch实现多分类神经网络**
  - [B station](https://www.bilibili.com/video/BV14Yb1zbEwZ)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：8.10 为什么神经网络可以拟合任意函数**
  - [B station](https://www.bilibili.com/video/BV1E2b1zSECH)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：9.1 L1和L2正则化**
  - [B station](https://www.bilibili.com/video/BV198bQzRE4q)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：9.2 指数加权平均**
  - [B station](https://www.bilibili.com/video/BV1XUbDzXEUJ)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：9.3 动量梯度下降**
  - [B station](https://www.bilibili.com/video/BV1yTbQz6EtT)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：9.4 RMSProp**
  - [B station](https://www.bilibili.com/video/BV1AgbQzzEtE)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：9.5 Adam优化器**
  - [B station](https://www.bilibili.com/video/BV142b9zQE2X)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：9.6 权重衰减**
  - [B station](https://www.bilibili.com/video/BV186b9zdEXR)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：9.7 Dropout**
  - [B station](https://www.bilibili.com/video/BV1Yvb9zFEUD)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：9.8 批量归一化**
  - [B station](https://www.bilibili.com/video/BV1Yvb9zFEet)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：10.1 计算机视觉问题的特点**
  - [B station](https://www.bilibili.com/video/BV1EU8bzME3z)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：10.2 卷积操作**
  - [B station](https://www.bilibili.com/video/BV1T88bznEbf)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：10.3 卷积的进阶操作**
  - [B station](https://www.bilibili.com/video/BV1ik8ez2Euv)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：10.4 池化层**
  - [B station](https://www.bilibili.com/video/BV1Uj8ezvERH)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：10.5 一个完整的卷积神经网络**
  - [B station](https://www.bilibili.com/video/BV1QV8iz5En2)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：10.6 1乘1卷积和全局平均池化层**
  - [B station](https://www.bilibili.com/video/BV18V83zMEMN)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：10.7 用PyTorch实现卷积神经网络**
  - [B station](https://www.bilibili.com/video/BV1cT8gzWE5E)
  - links: https://www.kaggle.com/datasets/shaunthesheep/microsoft-catsvsdogs-dataset https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：10.8 图像增强**
  - [B station](https://www.bilibili.com/video/BV1yj8EzJEf2)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：11.1 LeNet**
  - [B station](https://www.bilibili.com/video/BV11F8HzoEKx)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：11.2 AlexNet**
  - [B station](https://www.bilibili.com/video/BV1638HzJEM6)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：11.3 GoogLeNet**
  - [B station](https://www.bilibili.com/video/BV1cM8HzpEen)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：11.4 VGGNet**
  - [B station](https://www.bilibili.com/video/BV1oi8nzVE7b)
  - links: https://github.com/RethinkFun/DeepLearning
- **ResNet原理及实现**
  - [B station](https://www.bilibili.com/video/BV13ChwzDEwU)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：11.6 ResNet实现**
  - [B station](https://www.bilibili.com/video/BV1UUhwzjE4W)
  - links: https://github.com/RethinkFun/DeepLearning
- **什么是迁移学习？**
  - [B station](https://www.bilibili.com/video/BV1UUhwzjEFR)
  - links: https://github.com/RethinkFun/DeepLearning
- **快速了解什么是目标检测**
  - [B station](https://www.bilibili.com/video/BV1b2hwzmEGh)
  - links: https://github.com/RethinkFun/DeepLearning
- **什么是语义分割？**
  - [B station](https://www.bilibili.com/video/BV1Sn8Bz7ER4)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：11.10 其他应用**
  - [B station](https://www.bilibili.com/video/BV1DE8BzUE1N)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：12.1 自然语言处理的发展**
  - [B station](https://www.bilibili.com/video/BV15h8qzQEgd)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：12.2 NLP的常见任务**
  - [B station](https://www.bilibili.com/video/BV1Sf8izCEx5)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：12.3词典生成**
  - [B station](https://www.bilibili.com/video/BV14J81zwE6c)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：12.4 Token编码**
  - [B station](https://www.bilibili.com/video/BV1sW81zbENS)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：12.5 语言模型采样**
  - [B station](https://www.bilibili.com/video/BV1NM8UzTEfV)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：13.1 RNN**
  - [B station](https://www.bilibili.com/video/BV1FJ8UzfEJX)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：13.2 RNN的不同类型**
  - [B station](https://www.bilibili.com/video/BV1wL8UzaEKg)
  - links: https://github.com/RethinkFun/DeepLearning
- **一次学懂LSTM 长短期记忆网络**
  - [B station](https://www.bilibili.com/video/BV1CahHzfEcD)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：13.4 GRU**
  - [B station](https://www.bilibili.com/video/BV1a5hHz3EAU)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：13.5 双向循环神经网络**
  - [B station](https://www.bilibili.com/video/BV1RuhHzyEM5)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：13.6 深度循环神经网络**
  - [B station](https://www.bilibili.com/video/BV1TkhnzPEkV)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：13.7 注意力机制**
  - [B station](https://www.bilibili.com/video/BV112hnz8E7F)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：14.1 数据准备**
  - [B station](https://www.bilibili.com/video/BV11dhPzJEUD)
  - links: https://pan.baidu.com/s/1v2K4Awr03mXUUPJbpyMfpw?pwd=4ak4 https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：14.2 BLEU评价指标**
  - [B station](https://www.bilibili.com/video/BV1XThMzBEQ2)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：14.3 模型定义**
  - [B station](https://www.bilibili.com/video/BV1b2hVz7EyR)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：14.4 模型评估**
  - [B station](https://www.bilibili.com/video/BV1yhhGzBEoH)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：15.1 动机与影响**
  - [B station](https://www.bilibili.com/video/BV1WXtVzaE4g)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：15.2 注意力机制**
  - [B station](https://www.bilibili.com/video/BV1wZtVzFEhc)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：15.3 层归一化**
  - [B station](https://www.bilibili.com/video/BV1E5tnzrEtP)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：15.4 位置编码**
  - [B station](https://www.bilibili.com/video/BV1iztJzvEKZ)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：15.5 把这一切组装起来**
  - [B station](https://www.bilibili.com/video/BV1VktJzaE35)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：15.6 利用Transformer实现模型翻译**
  - [B station](https://www.bilibili.com/video/BV1R74dzaE4b)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：16.1 GPT1**
  - [B station](https://www.bilibili.com/video/BV1R74dzaELB)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：16.2 BERT**
  - [B station](https://www.bilibili.com/video/BV1cP4dzGEyf)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：16.3 GPT2**
  - [B station](https://www.bilibili.com/video/BV1cP4dzGEoh)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：16.4 GPT3和GPT4**
  - [B station](https://www.bilibili.com/video/BV1cP4dzGEX5)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：17.1 Llama1**
  - [B station](https://www.bilibili.com/video/BV1BrtczHEYw)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：17.2 旋转位置编码**
  - [B station](https://www.bilibili.com/video/BV17rtczHEDc)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：17.3 Llama2**
  - [B station](https://www.bilibili.com/video/BV17rtczHESw)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：17.4 Llama3**
  - [B station](https://www.bilibili.com/video/BV17rtczHEk2)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：18.1 MOE**
  - [B station](https://www.bilibili.com/video/BV1i1tczUEgr)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：18.2 DeepSeekMOE**
  - [B station](https://www.bilibili.com/video/BV1v1tczUEUE)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：18.3 DeepSeekV2**
  - [B station](https://www.bilibili.com/video/BV1j1tczUEMF)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》：18.4 DeepSeekV3**
  - [B station](https://www.bilibili.com/video/BV1i1tczUEao)
  - links: https://github.com/RethinkFun/DeepLearning
- **《RethinkFun深度学习教程》完结！**
  - [B station](https://www.bilibili.com/video/BV13ftAzmEM2)
- **VIT （Vision Transformer）深度讲解**
  - [B station](https://www.bilibili.com/video/BV15RDtYqE4r)
- **多模态模型CLIP深度讲解**
  - [B station](https://www.bilibili.com/video/BV1pYmDYgEDW)
- **一次学懂对比学习：MOCO**
  - [B station](https://www.bilibili.com/video/BV1dtSuY7Evj)
- **一次学懂多模态算法：ALBEF模型**
  - [B station](https://www.bilibili.com/video/BV1uMUDYnEKu)
- **一次学懂BLIP多模态算法**
  - [B station](https://www.bilibili.com/video/BV1g7BmYHEJn)
- **一次学懂多模态算法：flamingo**
  - [B station](https://www.bilibili.com/video/BV1QszNYzE1r)
- **一次学懂多模态算法：BLIP2   BLIP-2**
  - [B station](https://www.bilibili.com/video/BV1bVBRYTEpL)
- **看傻眼！LLaVA多模态模型最简单的模型，最强的效果！LLaVA LLaVA-1.5 LLaVA-NeXT**
  - [B station](https://www.bilibili.com/video/BV12PznYuExg)
- **LLama 3.2 Vision 多模态大模型原理讲解**
  - [B station](https://www.bilibili.com/video/BV1QrBEY3Eax)
- **大模型预训练看这个视频就够了**
  - [B station](https://www.bilibili.com/video/BV1xhYtewEum)
  - links: https://github.com/RethinkFun/LLM
- **大模型微调看这个视频就够了 SFT NEFTune**
  - [B station](https://www.bilibili.com/video/BV1gmWDeLEMZ)
  - links: https://github.com/RethinkFun/sft/tree/main
- **零基础学习强化学习算法：ppo**
  - [B station](https://www.bilibili.com/video/BV1iz421h7gb)
- **代码实现大模型强化学习(PPO)，看这个视频就够了。**
  - [B station](https://www.bilibili.com/video/BV1rixye7ET6)
  - links: https://github.com/RethinkFun/trian_ppo/tree/main/train_ppo
- **模型量化一：量化基础 对称量化 非对称量化 极大值量化 零点量化**
  - [B station](https://www.bilibili.com/video/BV1EE42157Ms)
- **模型量化二：训练后动态量化 PTQ PTDQ，pytorch里进行模型训练后动态量化**
  - [B station](https://www.bilibili.com/video/BV1pZ421J7ga)
- **模型量化三：训练后静态量化 PTQ PTSQ pytorch里进行模型训练后静态量化**
  - [B station](https://www.bilibili.com/video/BV17m411C77i)
- **模型量化四：量化感知训练 QAT pytorch里进行量化感知训练**
  - [B station](https://www.bilibili.com/video/BV1pt421w7u4)
- **模型量化五：LLM.int8() Bitsandbytes HuggingFace 默认大模型量化方法**
  - [B station](https://www.bilibili.com/video/BV1mm421p7GD)
- **模型量化六：QLoRA 4bit 量化 NormalFloat4 量化**
  - [B station](https://www.bilibili.com/video/BV15y411a7so)
- **大模型修炼之道(一): Transformer Attention is all you need**
  - [B station](https://www.bilibili.com/video/BV1FH4y157ZC)
  - links: https://github.com/hkproj/pytorch-transformer/blob/main/model.py
- **大模型修炼之道(二): GPT系列GPT1，GPT2，GPT3，GPT4**
  - [B station](https://www.bilibili.com/video/BV1ZJ4m1K73s)
- **大模型修炼之道(三): Llama系列讲解 Llama1，Llama2, Llama3**
  - [B station](https://www.bilibili.com/video/BV1Ds421c7JP)
- **Pytorch里的register_parameter和register_buffer是干什么的？**
  - [B station](https://www.bilibili.com/video/BV1cr421J7Su)
- **MOE的实现-从Top-K到专家路由和Token Dispatch/Combine**
  - [B station](https://www.bilibili.com/video/BV1Ehpj6iEnE)
- **ai infra购课平台上线了～**
  - [B station](https://www.bilibili.com/video/BV13kvKzrEa9)
- **8月13日-学员会议-从零开始的AI Infra学习规划**
  - [B station](https://www.bilibili.com/video/BV1WSYyzYEiY)
  - links: https://tvle9mq8jh.feishu.cn/docx/BnqMdyaJ9oyXb1xwktgc7esMn4c
- **一次对ai-infra新学员的规划课**
  - [B station](https://www.bilibili.com/video/BV1TuYqzmEhh)
  - links: https://tvle9mq8jh.feishu.cn/docx/BnqMdyaJ9oyXb1xwktgc7esMn4c
- **AI Infra 2025年秋招经验分享**
  - [B station](https://www.bilibili.com/video/BV17tEvzdE4x)
- **大模型推理加速-AI Infra的简历应该怎么写？**
  - [B station](https://www.bilibili.com/video/BV1S6EyzBEZX)
- **AI Infra 2025年暑期实习经验分享**
  - [B station](https://www.bilibili.com/video/BV1pCL6zgEhw)
- **AI Infra秋招项目-用CUDA写一个支持qwen3的大模型推理框架**
  - [B station](https://www.bilibili.com/video/BV1jvNnzmEik)
- **如何写一份合格的AI-Infra岗位秋招简历**
  - [B station](https://www.bilibili.com/video/BV1iEpgz8EUE)
  - links: https://tvle9mq8jh.feishu.cn/docx/AsbMdFifqom06axLBcFcSZNmnud?from=from_copylink
- **Ai-Infra面试实录—大模型推理框架开发实习岗位**
  - [B station](https://www.bilibili.com/video/BV1VAUKBxEFT)
- **从零开始学Ai-Infra—冲击26年秋招SSP**
  - [B station](https://www.bilibili.com/video/BV1gw2WBAE6t)
- **AI-Infra规划课—2025年秋招没有offer，怎么准备春招？**
  - [B station](https://www.bilibili.com/video/BV1Ynm9BsEYm)
- **AI-Infra规划课—怎么学习算子开发？**
  - [B station](https://www.bilibili.com/video/BV1wXmqBbE8U)
- **AI-Infra规划课—怎么关联实习和目标岗位？**
  - [B station](https://www.bilibili.com/video/BV1uiqzBQEd5)
- **AI-Infra规划课—选实习offer**
  - [B station](https://www.bilibili.com/video/BV13rB4B9ETN)
- **AI-Infra规划课—怎么学习大模型推理框架**
  - [B station](https://www.bilibili.com/video/BV1QBv6BHEGZ)
- **AI-Infra规划课—acm经历对ai-infra有帮助吗？**
  - [B station](https://www.bilibili.com/video/BV1QLiwB2Emj)
- **AI-Infra规划课—芯片/互联网的实习通用吗？**
  - [B station](https://www.bilibili.com/video/BV1XY6UBxELM)
- **AI-Infra规划课—怎么从后端转方向和端侧AI部署**
  - [B station](https://www.bilibili.com/video/BV1sprQB9EFb)
- **AI-Infra规划课—2026年的SSP被预定了一个**
  - [B station](https://www.bilibili.com/video/BV1ncz1BoEqE)
- **AI-Infra规划课—有实力的选手是怎么规划实习的？**
  - [B station](https://www.bilibili.com/video/BV1gT6nB6EPA)
- **AI-Infra规划课—实习，比赛，论文和项目全优的一位同学**
  - [B station](https://www.bilibili.com/video/BV1fBFxzpEH3)
- **AI-Infra规划课—怎么寻找自己简历中的亮点？**
  - [B station](https://www.bilibili.com/video/BV1Z3ZJBfEyX)
- **AI-Infra规划课—留学生Infra岗简历实习研讨**
  - [B station](https://www.bilibili.com/video/BV1HSNczqErh)
- **AI-Infra规划课—算子大佬是怎么炼成的**
  - [B station](https://www.bilibili.com/video/BV18dw4z2ENV)
- **AI-Infra规划课—当算子实习生比社招同学更优秀的时候**
  - [B station](https://www.bilibili.com/video/BV1LKAAzoEUy)
- **AI-Infra规划课—社招转infra岗位改简历**
  - [B station](https://www.bilibili.com/video/BV1iNXjBBEZj)
- **AI-Infra规划课—26年4月3日春招规划实录**
  - [B station](https://www.bilibili.com/video/BV1vt9gBpEzD)
- **AI-Infra规划课和模拟面—26年4月11日实录**
  - [B station](https://www.bilibili.com/video/BV146DyBhELD)
- **AI-Infra规划课和模拟面—vLLM大模型推理优化岗我会怎么面？**
  - [B station](https://www.bilibili.com/video/BV1UndWBHE8G)
- **AI-Infra规划课和模拟面—26年4月26日场—算子优化五步法**
  - [B station](https://www.bilibili.com/video/BV1uaofBREJE)
- **AI-Infra规划课和模拟面—为vllm omni+vllm贡献者大佬修改简历-2026年5月1日场**
  - [B station](https://www.bilibili.com/video/BV1h1R3BXEsf)
- **AI-Infra规划课和模拟面—一位写过高性能算子库的同学——2026年5月9日场**
  - [B station](https://www.bilibili.com/video/BV1cNRdBfEE6)
- **AI-Infra规划课和模拟面—博士也愁找工作**
  - [B station](https://www.bilibili.com/video/BV1yqG66pEmt)
- **AI-Infra规划课和模拟面—nano-vllm怎么学有竞争力？**
  - [B station](https://www.bilibili.com/video/BV1UbG66ZE86)
- **AI-Infra规划课和模拟面—2026年5月30日职业规划实录**
  - [B station](https://www.bilibili.com/video/BV1wTVj6SEhk)
- **AI-Infra规划课和模拟面—2026年6月6日-怎么给vLLM提交pr**
  - [B station](https://www.bilibili.com/video/BV1zKEp6GEzo)
- **AI-Infra规划课和模拟面—2026年6月13日—帮学员简历查漏补缺**
  - [B station](https://www.bilibili.com/video/BV15SJs6yEGq)
- **AI-Infra规划课和模拟面—2026年6月20日—帮一位芯片全栈的同学简历突出重点**
  - [B station](https://www.bilibili.com/video/BV1EujH6eExe)
- **AI-Infra规划课和模拟面—2026年6月20日—大模型推理端到端是必须掌握的**
  - [B station](https://www.bilibili.com/video/BV1L5jH6cEYo)
- **AI-Infra规划课和模拟面—2026年6月27日—秋招推理框架、算子开发与项目打磨指导**
  - [B station](https://www.bilibili.com/video/BV1eu7W6KEda)
- **AI-Infra规划课和模拟面—2026年7月4日—研一找到两份实习offer的女生**
  - [B station](https://www.bilibili.com/video/BV1PzMP6rEQH)
- **AI-Infra规划课和模拟面—2026年7月11日—大二找到infra实习的同学**
  - [B station](https://www.bilibili.com/video/BV1PVNA6fEAs)
- **AI-Infra规划课和模拟面—2026年7月11日—帮学员看简历**
  - [B station](https://www.bilibili.com/video/BV1nBNw6XE47)
- **ai infra职业规划-2026年7月18日-学历和实习都顶级拉满的一位同学**
  - [B station](https://www.bilibili.com/video/BV18VKB6zE51)
- **ai infra职业规划-2026年7月25日-精通推理优化的一位同学今年秋招**
  - [B station](https://www.bilibili.com/video/BV15q3G6dESU)
- **ai infra职业规划-2026年8月2日-保研后的学习规划**
  - [B station](https://www.bilibili.com/video/BV1kN3m6eEpR)
- **ai infra职业规划-2026年8月2日-在工作中发现推理加速的需求**
  - [B station](https://www.bilibili.com/video/BV1kT3m6AEWh)
- **ai infra职业规划-2026年8月6日-拷打芯片行业的算子岗**
  - [B station](https://www.bilibili.com/video/BV1XpuH6uEjL)
- **ai infra职业规划-2026年8月6日-大二去字节实习**
  - [B station](https://www.bilibili.com/video/BV1x2ux6gE5x)
- **AI Infra-职业规划：参加2026秋招前大厂同学的职业规划**
  - [B station](https://www.bilibili.com/video/BV1sNu56BEpH)
- **ai-infra规划-8月16日-28届实习阶段怎么学习vllm**
  - [B station](https://www.bilibili.com/video/BV1QebS6PEie)
- **ai-infra规划-8月16日-27届秋招前大家水平怎么样了？**
  - [B station](https://www.bilibili.com/video/BV1XabS6vEnd)
- **ai-infra规划-8月22日-27/28届的有实力选手**
  - [B station](https://www.bilibili.com/video/BV1RL8S6gEDT)
- **ai-infra规划-8月23日-学员经验-校招半年从infra小白到infra互联网大厂**
  - [B station](https://www.bilibili.com/video/BV1ru8h6aE3e)
- **ai-infra规划-8月31日-秋招的算子开发、推理框架与芯片适配，简历项目怎么改？**
  - [B station](https://www.bilibili.com/video/BV1FAtW6qEV3)
- **ai-infra规划-9月3日-给vLLM提了几次PR，能靠它冲大模型框架岗吗？**
  - [B station](https://www.bilibili.com/video/BV1YptD6qEyn)
- **ai-infra规划-8月22日-做国产gpu适配的同学简历**
  - [B station](https://www.bilibili.com/video/BV1y5to6TEFM)
- **ai-infra规划-9月5日-本2硕9-vLLM大模型推理框架简历应该这么改！**
  - [B station](https://www.bilibili.com/video/BV1Fstm6zEyb)
- **ai-infra职业规划，2026年9月5日，如何改造自己的kv cache项目**
  - [B station](https://www.bilibili.com/video/BV1cbbW6kEwh)
- **ai-infra职业规划，双硕士-hpc科研经历-如何从事cuda算子开发？**
  - [B station](https://www.bilibili.com/video/BV1gSbG6bEh3)
- **ai-infra职业规划，从万卡集群调度走向ai-infra大模型推理加速**
  - [B station](https://www.bilibili.com/video/BV15kbG6PEhV)
- **ai-infra职业规划，具身智能和互联网怎么选？**
  - [B station](https://www.bilibili.com/video/BV1Vmb56BExL)
- **ai-infra职业规划，从集群推理优化科研到大模型推理：如何拿下AI Infra实习？**
  - [B station](https://www.bilibili.com/video/BV1RWbV6NETb)
- **ai-infra职业规划，秋招北邮硕士做算子实习，如何转向大模型推理优化？**
  - [B station](https://www.bilibili.com/video/BV1ZBY86eED9)
- **ai-infra职业规划，从零开始学习拿到大模型独角兽实习**
  - [B station](https://www.bilibili.com/video/BV1XrY26iEwT)
- **ai-infra职业规划，算法转AI-Infra实习规划和Cuda学习**
  - [B station](https://www.bilibili.com/video/BV1tme86HEhK)
- **ai-infra职业规划，从CUDA算子到推理框架：两份 AI Infra 简历的项目分析与改进建议**
  - [B station](https://www.bilibili.com/video/BV15Th66UEec)
- **ai-infra职业规划：大厂的infra实习生怎么在准备秋招面试？**
  - [B station](https://www.bilibili.com/video/BV1Zaho6iEtc)
- **ai-infra职业规划：大三在字节实习的同学又更新了他的简历**
  - [B station](https://www.bilibili.com/video/BV1Dfax66EY1)
- **ai-infra职业规划：在顶流芯片公司的实习为什么不被互联网认可？**
  - [B station](https://www.bilibili.com/video/BV1hZax63Eru)
- **ai-infra 27届学员秋招分享，今年我是如何拿到10个offer意向的？**
  - [B station](https://www.bilibili.com/video/BV1kjaL6bENg)
- **ai-infra职业规划：约面十几家公司，推理岗仍卡项目深度，15天如何冲刺 AI Infra**
  - [B station](https://www.bilibili.com/video/BV1EjHi69EvZ)
- **ai-infra职业规划：土木老哥一转智驾再转Infra的求职之路**
  - [B station](https://www.bilibili.com/video/BV15uHj6oE44)
- **ai-infra职业规划：怎么规划和修改自己的nano-vllm简历让它更出众？**
  - [B station](https://www.bilibili.com/video/BV1FJpG6tE2N)
- **vLLM大模型推理框架-分块显存管理**
  - [B station](https://www.bilibili.com/video/BV1WFnzzEEGD)
  - links: https://tvle9mq8jh.feishu.cn/docx/XBivdpOBBo5IdpxkIKBc83panXb?from=from_copylink
- **vLLM大模型推理框架-kv cache的初始化流程**
  - [B station](https://www.bilibili.com/video/BV1hYHKz6EtE)
  - links: https://tvle9mq8jh.feishu.cn/docx/XBivdpOBBo5IdpxkIKBc83panXb?from=from_copylink
- **vLLM大模型推理框架-请求和显存块的映射**
  - [B station](https://www.bilibili.com/video/BV1BY4VzHE4Z)
  - links: https://tvle9mq8jh.feishu.cn/docx/PqvYd6r9YoSsWLxJTuhcf823nOo
- **vLLM源码全流程分析—vLLM引擎架构与流式推理**
  - [B station](https://www.bilibili.com/video/BV14zsozJE5B)
  - links: https://l0kzvikuq0w.feishu.cn/docx/YcEidA4C2oumbZxOa4CceB0bnod?from=from_copylink‌‍‍‌‌‍‬‍‍﻿‌‌‬‍‬
- **vLLM源码全流程分析—vLLM Worker和Executor组件的协作**
  - [B station](https://www.bilibili.com/video/BV1db1LBmEpL)
  - links: https://l0kzvikuq0w.feishu.cn/docx/YcEidA4C2oumbZxOa4CceB0bnod?from=from_copylink‌‍‍‌‌‍‬‍‍﻿‌‌‬‍‬
- **vLLM 显存分块管理—PageAttention 的基石**
  - [B station](https://www.bilibili.com/video/BV1n9rEBWEFK)
- **vLLM技术分享以及大模型推理框架学习、工作答疑**
  - [B station](https://www.bilibili.com/video/BV1FCLV6LEsu)
- **SGLang 与 vLLM 深度对比：从 KV Cache 到调度架构**
  - [B station](https://www.bilibili.com/video/BV1QxYB6yE2D)
- **sglang大模型推理框架-cuda graph从piecewise到breakable**
  - [B station](https://www.bilibili.com/video/BV1WzaT6rEGi)
- **sglang大模型推理框架-sglang中的triton编译技术**
  - [B station](https://www.bilibili.com/video/BV1Zmat6dEeX)
- **sglang大模型推理框架-一个请求的端到端流程和生命周期**
  - [B station](https://www.bilibili.com/video/BV1wraz6hEG3)
- **从零自制深度学习推理框架：第一讲 项目预览和环境配置**
  - [B station](https://www.bilibili.com/video/BV13UaczHEwf)
- **从零自制深度学习推理框架：第二讲 张量(Tensor)的设计与实现**
  - [B station](https://www.bilibili.com/video/BV1hUaczHE4e)
- **从零自制深度学习推理框架：第三讲 计算图的定义**
  - [B station](https://www.bilibili.com/video/BV1mdacz2EHq)
- **从零自制深度学习推理框架：第四讲 构建计算图关系和执行顺序**
  - [B station](https://www.bilibili.com/video/BV1DUacznEmu)
- **从零自制深度学习推理框架：第五讲 KuiperInfer中的算⼦和注册⼯⼚**
  - [B station](https://www.bilibili.com/video/BV1DUacznEL7)
- **从零自制深度学习推理框架：第六讲 卷积和池化算子的实现**
  - [B station](https://www.bilibili.com/video/BV1DUacznEsS)
- **从零自制深度学习推理框架：第七讲 表达式层中词法分析和语法分析以及算子的实现**
  - [B station](https://www.bilibili.com/video/BV1DUacznEbX)
- **从零自制深度学习推理框架：第八讲 动手支持Resnet网络的推理**
  - [B station](https://www.bilibili.com/video/BV1hUaczHEV6)
- **从零自制深度学习推理框架：第九讲 自制一个支持yolov5的推理框架**
  - [B station](https://www.bilibili.com/video/BV1hUaczHE4i)
- **AI-Infra必备Cuda入门课程-Transpose优化和Bank冲突处理**
  - [B station](https://www.bilibili.com/video/BV1wtbjzgEBB)
  - links: https://tvle9mq8jh.feishu.cn/docx/BnqMdyaJ9oyXb1xwktgc7esMn4c
- **AI-Infra必备Cuda入门课程-Matmul优化初步**
  - [B station](https://www.bilibili.com/video/BV1ZithzTE5x)
  - links: https://tvle9mq8jh.feishu.cn/docx/BnqMdyaJ9oyXb1xwktgc7esMn4c
- **AI-Infra必备Cuda入门课程-Softmax的实现与优化**
  - [B station](https://www.bilibili.com/video/BV11Q8DzyE21)
  - links: https://tvle9mq8jh.feishu.cn/docx/BnqMdyaJ9oyXb1xwktgc7esMn4c
- **AI-Infra必备Cuda入门课程-Reduce算子的实现**
  - [B station](https://www.bilibili.com/video/BV13baszpESw)
  - links: https://tvle9mq8jh.feishu.cn/docx/BnqMdyaJ9oyXb1xwktgc7esMn4c
- **Triton自制多模态大模型推理框架-用Triton写FlashAttention**
  - [B station](https://www.bilibili.com/video/BV1j59tY1EFt)
- **Triton自制多模态大模型推理框架-用Triton写出高性能的matmul**
  - [B station](https://www.bilibili.com/video/BV1SfAmeUECV)
- **Triton自制多模态大模型推理框架-Triton介绍和逐级编译流程**
  - [B station](https://www.bilibili.com/video/BV1HCAMe4E5Y)
- **限时试看-使用OpenAI Triton实现Softmax算子**
  - [B station](https://www.bilibili.com/video/BV1KKZBYiEDj)
- **Triton自制大模型推理框架—大模型推理优化综述**
  - [B station](https://www.bilibili.com/video/BV11oRWYWEmW)
- **AI Infra入门-使用OpenAI Triton实现Reduce算子**
  - [B station](https://www.bilibili.com/video/BV1kaRzYdEsr)
- **零基础入门ai infra的救星，自制深度学习推理框架出书了**
  - [B station](https://www.bilibili.com/video/BV1MAZBYBELQ)
- **AI Infra秋招项目-OpenAI Triton自制深度学习推理框架发布了**
  - [B station](https://www.bilibili.com/video/BV17QNhz2ESk)
- **秋招巅峰项目：OpenAI Triton自制多模态推理框架，FlashAttention原理与实战**
  - [B station](https://www.bilibili.com/video/BV1Jy3wznESs)
  - links: https://l0kzvikuq0w.feishu.cn/docx/MjuAdl7kpob8rSxQiITcuMbLn9e?from=from_copylink
- **Cuda从零学-秋招转行拿高薪-从零自制大模型推理框架**
  - [B station](https://www.bilibili.com/video/BV1hT421Y7mi)
- **自制大模型推理框架-使用Nsight compute对Cuda算子调优**
  - [B station](https://www.bilibili.com/video/BV1WS411w7g7)
- **秋招项目-从零自制大模型推理框架-张量类的设计**
  - [B station](https://www.bilibili.com/video/BV1dH4y1F735)
- **秋招项目-从零自制大模型推理框架-算子类的设计**
  - [B station](https://www.bilibili.com/video/BV18y411q71J)
- **试看马上删-从零自制大模型推理框架，内存和显存资源是怎么被管理的。**
  - [B station](https://www.bilibili.com/video/BV1is421T7Vq)
- **从零自制大模型推理框架，一个靠谱的C++程序员是怎么练成的。**
  - [B station](https://www.bilibili.com/video/BV1ji421e7MN)
- **自制Cuda大模型推理框架-讲解一个从零手写的Qwen2.5推理**
  - [B station](https://www.bilibili.com/video/BV1q2mTYrEqM)
  - links: https://l0kzvikuq0w.feishu.cn/docx/ZF2hd0xfAoaXqaxcpn2c5oHAnBc
- **秋招看过来！自制大模型推理框架项目-sofmax算子的cuda实现**
  - [B station](https://www.bilibili.com/video/BV1vZsyeuEz1)
- **秋招看过来！自制大模型推理框架项目-动手实现LLama模型中的多头注意力机制**
  - [B station](https://www.bilibili.com/video/BV17d4fe9Ep6)
- **秋招看过来！自制大模型推理框架-怎么用Cuda实现LLama模型中的MLP层**
  - [B station](https://www.bilibili.com/video/BV1uRnRe7EFQ)
- **自制大模型推理框架-KVCache动手实现-原理篇**
  - [B station](https://www.bilibili.com/video/BV1GmpZeiEB7)
- **秋招好项目-《动手自制大模型推理框架》-算子的创建和权重的载入**
  - [B station](https://www.bilibili.com/video/BV1bRveeoEPW)
- **秋招、转行必备-动手自制大模型推理框架-CUDA显存管理**
  - [B station](https://www.bilibili.com/video/BV142421Z7r3)
- **自制大模型推理框架-Cuda算子再优化和NVCompute分析性能**
  - [B station](https://www.bilibili.com/video/BV1Qx4y1t7jF)
- **自制大模型推理框架-支持大模型int8分组量化**
  - [B station](https://www.bilibili.com/video/BV1RM4m117Bj)
- **自制Cuda大模型推理框架-算子类的实现**
  - [B station](https://www.bilibili.com/video/BV1jXDTYEEEP)
  - links: https://l0kzvikuq0w.feishu.cn/docx/ZF2hd0xfAoaXqaxcpn2c5oHAnBc
- **自制Cuda大模型推理框架-张量的实现和显存的管理**
  - [B station](https://www.bilibili.com/video/BV1hsU7Y8EhP)
  - links: https://l0kzvikuq0w.feishu.cn/docx/ZF2hd0xfAoaXqaxcpn2c5oHAnBc
- **自制Cuda大模型推理框架-RMSNorm的Cuda实现**
  - [B station](https://www.bilibili.com/video/BV198znYnE7X)
  - links: https://l0kzvikuq0w.feishu.cn/docx/ZF2hd0xfAoaXqaxcpn2c5oHAnBc
- **《自制深度学习推理框架》gemv算子的量化实现**
  - [B station](https://www.bilibili.com/video/BV1FK6aYhEhB)
  - links: https://l0kzvikuq0w.feishu.cn/docx/ZF2hd0xfAoaXqaxcpn2c5oHAnBc
- **《自制深度学习推理框架》新书预告！从理论到实践，打造你的AI推理引擎**
  - [B station](https://www.bilibili.com/video/BV1ZPkhYfEt2)
  - links: https://l0kzvikuq0w.feishu.cn/docx/ZF2hd0xfAoaXqaxcpn2c5oHAnBc
- **自制Cuda大模型推理框架-int8量化的实现**
  - [B station](https://www.bilibili.com/video/BV1HdqJYoEj6)
  - links: https://l0kzvikuq0w.feishu.cn/docx/ZF2hd0xfAoaXqaxcpn2c5oHAnBc
- **秋招巅峰项目：手写工业级LLM推理系统-CUDA加速Qwen-3全流程实现**
  - [B station](https://www.bilibili.com/video/BV1zzNmzfEnF)
- **《自制深度学习推理框架》配套视频-第一章环境的安装**
  - [B station](https://www.bilibili.com/video/BV1oycGesEpj)
  - links: https://l0kzvikuq0w.feishu.cn/docx/IBtod4PIDoAerHxjkZwcp4wDn9d https://l0kzvikuq0w.feishu.cn/docx/ZF2hd0xfAoaXqaxcpn2c5oHAnBc
- **《自制深度学习推理框架》-第二章张量的设计**
  - [B station](https://www.bilibili.com/video/BV1T7wNe9EpK)
  - links: https://l0kzvikuq0w.feishu.cn/docx/E4F0djDTqoyjRzxmH8kcHM9rnIc https://l0kzvikuq0w.feishu.cn/docx/ZF2hd0xfA
- **《自制深度学习推理框架》-第三章-计算图的设计**
  - [B station](https://www.bilibili.com/video/BV1sPfhYmEmx)
- **《自制深度学习推理框架》-第四章-构建计算图**
  - [B station](https://www.bilibili.com/video/BV1HKAYefEoQ)
- **《自制深度学习推理框架》-第5章算子注册器的实现**
  - [B station](https://www.bilibili.com/video/BV1w6RaYMEWh)
  - links: https://l0kzvikuq0w.feishu.cn/docx/TjLOdI46BoyIv7xCuAHcWpXRnth?from=from_copylink https://l0kzvikuq0w.feishu.cn/docx/ZF2hd0xf
- **从KuiperInfer出发谈一些工程开发经验**
  - [B station](https://www.bilibili.com/video/BV1Ga4y1V7gF)
  - links: https://zhuanlan.zhihu.com/p/623860716 https://github.com/zjhellofss/kuiper_project_practice/tree/main
- **自制深度学习推理框架-最终章-用自制的推理框架支持Yolov5模型的推理**
  - [B station](https://www.bilibili.com/video/BV1xs4y1J7t2)
  - links: https://github.com/zjhellofss/KuiperCourse https://gitee.com/fssssss/KuiperCourse/ https://blog.csdn.net/qq_32901731/article/details/129710271
- **自制深度学习推理框架-第13课-用我们自制的推理框架完成ResNet网络的推理和图片的分类**
  - [B station](https://www.bilibili.com/video/BV1jD4y1M772)
  - links: https://github.com/zjhellofss/KuiperCourse https://gitee.com/fssssss/KuiperCourse/ https://zhuanlan.zhihu.com/p/611158341
- **自制深度学习推理框架-第十二节-算子的执行流程**
  - [B station](https://www.bilibili.com/video/BV1wY411C7Kv)
  - links: https://github.com/zjhellofss/KuiperCourse https://zhuanlan.zhihu.com/p/607993700
- **自制深度学习推理框架-第十一节-再探Tensor类，构建计算图的图关系以及对算子的输入输出预分配**
  - [B station](https://www.bilibili.com/video/BV1M54y1K7AG)
  - links: https://github.com/zjhellofss/KuiperCourse https://gitee.com/fssssss/KuiperCourse/ https://blog.csdn.net/qq_32901731/article/details/128926136
- **自制深度学习推理框架-第10节-卷积算子的实现和im2col加速计算的原理**
  - [B station](https://www.bilibili.com/video/BV1F841137Ct)
  - links: https://github.com/zjhellofss/KuiperCourse https://gitee.com/fssssss/KuiperCourse/ https://blog.csdn.net/qq_32901731/article/details/128822803
- **自制深度学习推理框架-对计算图知识的补充**
  - [B station](https://www.bilibili.com/video/BV18d4y1H7Tf)
  - links: https://github.com/zjhellofss/KuiperCourse https://gitee.com/fssssss/KuiperCourse/ https://blog.csdn.net/qq_32901731/article/details/128732685
- **自制深度学习推理框架-第8.2节-计算图中的表达式下**
  - [B station](https://www.bilibili.com/video/BV1cT411f7pJ)
  - links: https://zhuanlan.zhihu.com/p/600505293
- **自制深度学习推理框架-第8.1节-计算图中的表达式上**
  - [B station](https://www.bilibili.com/video/BV1HY4y1Z7S3)
  - links: https://github.com/zjhellofss/KuiperCourse https://gitee.com/fssssss/KuiperCourse/ https://zhuanlan.zhihu.com/p/599301356
- **自制深度学习推理框架-第七课-构建自己的计算图**
  - [B station](https://www.bilibili.com/video/BV1VW4y1V7vp)
  - links: https://zhuanlan.zhihu.com/p/597240175 https://github.com/zjhellofss/kuiperinfer https://gitee.com/fssssss/KuiperCourse/
- **Milestone里程碑，记录我们的自制框架KuiperInfer完美支持Yolov5n推理的一刻**
  - [B station](https://www.bilibili.com/video/BV1t24y1i7cu)
  - links: https://space.bilibili.com/1822828582 https://github.com/zjhellofss/KuiperInfer
- **自制深度学习推理框架-第六课-MaxPooling算子的实现**
  - [B station](https://www.bilibili.com/video/BV1m3411S7yy)
  - links: https://zhuanlan.zhihu.com/p/595973185 https://github.com/zjhellofss/kuiperinfer https://gitee.com/fssssss/KuiperCourse/
- **自制深度学习推理框架-第五课-起飞！框架中的算子注册机制**
  - [B station](https://www.bilibili.com/video/BV1Q24y1m7jR)
  - links: https://zhuanlan.zhihu.com/p/594087648
- **自制深度学习推理框架-起飞！实现我们的第一个算子Relu-第四课**
  - [B station](https://www.bilibili.com/video/BV1bG4y1J7sQ)
  - links: https://zhuanlan.zhihu.com/p/593215728
- **自制深度学习推理框架-从CSV文件初始化Tensor张量-第三课**
  - [B station](https://www.bilibili.com/video/BV1Pg411J7V5)
  - links: https://github.com/zjhellofss/kuiperinfer https://cowtransfer.com/s/8233d31a70394c
- **自制深度学习推理框架-张量类Tensor的实现-第二课**
  - [B station](https://www.bilibili.com/video/BV1Ed4y1v7Gb)
  - links: https://cowtransfer.com/s/92602ff08d544b
- **自制深度学习推理框架-前言-第一课**
  - [B station](https://www.bilibili.com/video/BV1HV4y1A7H8)
  - links: https://cowtransfer.com/s/eec6da6f7dee4c
- **比大模型快193倍、便宜444倍，TypeSafe Jev到底怎么做到的?｜ AI大模型｜AI Agent｜智能体**
  - [B station](https://www.bilibili.com/video/BV1umah6WEqj)
- **AI 说“90% 有把握”，你敢让 Agent 自动执行吗？｜Jev：概率校准与 Agent 决策**
  - [B station](https://www.bilibili.com/video/BV134ph6vEmV)
- **《Agent Loop》给AI Agent的一首嘻哈主题曲｜AI工程师跨界做说唱，连动画MV都配齐了【AI MV大赛】**
  - [B station](https://www.bilibili.com/video/BV1QLpw6JE6c)
- **AI Agent 的底层其实就是一个 while 循环？Agent Loop 核心机制完整讲解**
  - [B station](https://www.bilibili.com/video/BV1SGTv6iEmZ)
- **AI Agent 为什么会“失忆”？因为上下文才是第一约束｜Agent 工程｜大模型Agent｜Agent Loop**
  - [B station](https://www.bilibili.com/video/BV1DsTn6wEB6)
- **AI Agent 为什么停不下来？从 ReAct 到 Copilot，看懂 Agent Loop 终止机制｜AI Agent 的终止机制详解**
  - [B station](https://www.bilibili.com/video/BV14mTb6EEQz)
- **Loop Engineering：从 Prompt 到 Agent 循环的范式迁移｜AI Agent 的下一层能力，不是写提示词，而是设计循环**
  - [B station](https://www.bilibili.com/video/BV1rmT16pEfj)
- **Agent Loop 即 RL Rollout？从产品循环到强化学习轨迹：理解 Agent RL 的关键入口，AI Agent 训练数据生成机制详解**
  - [B station](https://www.bilibili.com/video/BV1DUTd6aEyv)
- **AI会做奥数，却端不稳一杯水：具身智能到底难在哪？**
  - [B station](https://www.bilibili.com/video/BV1nRtn6PEwk)
- **会后空翻的机器人，到底是怎么练出来的？你必须了解的从经典控制到强化学习｜AI Agent｜AI 智能体｜大模型强化学习**
  - [B station](https://www.bilibili.com/video/BV1eQtG6PEqm)
- **机器人到底怎么学会干活？从模仿学习到具身智能的数据瓶颈**
  - [B station](https://www.bilibili.com/video/BV1bDYt6mEDz)
- **一双灵巧手，为什么能卡住整台人形机器人？｜具身智能｜世界模型｜机器人**
  - [B station](https://www.bilibili.com/video/BV12naW6ZENU)
- **机器人的 GPT 时刻到了？VLA 大模型离真正好用还有多远｜具身智能｜AI Agent｜强化学习｜大模型**
  - [B station](https://www.bilibili.com/video/BV1UqHL6UEQr)
- **DeepSeek V4.1：40层注意力，为什么只存4份KV？｜KV Cache优化详解｜Agent长上下文优化**
  - [B station](https://www.bilibili.com/video/BV1Z5e56ZEmq)
- **DeepSeek V4.1：CED架构与KV Cache优化详解**
  - [B station](https://www.bilibili.com/video/BV1xLe36hE65)
- **DeepSeek Harness：连 Agent Loop 本身都是插件，凭什么？揭秘智能体Runtime设计**
  - [B station](https://www.bilibili.com/video/BV1cJb96cEg2)
- **硬核解读 DeepSeek DSpark： 大模型推理快 60%-85%，投机解码的新天花板**
  - [B station](https://www.bilibili.com/video/BV14fTc6TEj7)
- **DeepSeek多模态凭什么把GPT 5.4拉开：4000万样本+三层奖励+OPD蒸馏，把"框和点"喂进推理链的完整训练秘方**
  - [B station](https://www.bilibili.com/video/BV1YXLp6FE8V)
- **多模态模型的真正瓶颈不是"看不清"，而是"指不准"？｜DeepSeek 视觉原语论文从架构到 7056× 压缩链路全解析**
  - [B station](https://www.bilibili.com/video/BV15j5u6WE5C)
- **DeepSeek V4 硬核全面拆解｜1.6万亿参数+百万级上下文+33万亿token同时不崩，CSA、mHC、Muon、OPD四大核心模块逐条拆解**
  - [B station](https://www.bilibili.com/video/BV153oRBXEsG)
- **DeepSeek Engram：用"查字典"打败Transformer，推理能力反而涨了5分？**
  - [B station](https://www.bilibili.com/video/BV1hLwMzwEVx)
- **DeepSeek-OCR项目导学**
  - [B station](https://www.bilibili.com/video/BV1YLrZBXEMA)
- **DeepSeek系统工程优化导学**
  - [B station](https://www.bilibili.com/video/BV1GLrZBXEmo)
- **DeepSeek与大模型技术演进**
  - [B station](https://www.bilibili.com/video/BV1QErZBDEHa)
- **DeepSeek架构革新 MLA多头潜在注意力**
  - [B station](https://www.bilibili.com/video/BV1hErZBDEzH)
- **我开源了一个本地 AI 阅读器：EPUB/PDF 翻译、摘要、问答，Docker 一键部署｜FolioPaw 阅读猫**
  - [B station](https://www.bilibili.com/video/BV1ZH8Z6MERd)
- **99美元、24小时预售260万美元：这只“小黄鸭”为什么重要？**
  - [B station](https://www.bilibili.com/video/BV1pktD69E9P)
- **MIT最新发现：Agent 泛化能力不在模型，而在 Harness！RLM重新定义大模型后训练**
  - [B station](https://www.bilibili.com/video/BV1EGuZ6XEQC)
- **让AI学会“存档”！Kimi K3的5122万个Agent沙箱揭秘：Agent强化学习基础设施到底有多复杂？**
  - [B station](https://www.bilibili.com/video/BV1iXuH6UEd5)
- **Agent 的"世界模型"到底是什么? 从第一性原理，讲透它为什么总在同一个坑里栽倒｜AI Agent 深度解析**
  - [B station](https://www.bilibili.com/video/BV1AmNH6EENf)
- **Agent 的真正瓶颈不是模型，而是这层 Agent Harness | HarnessX 全景解读**
  - [B station](https://www.bilibili.com/video/BV1Lxj86RECd)
- **刚发布几天就被美国政府紧急叫停:Claude 最强模型 Fable 5 / Mythos 到底强在哪?**
  - [B station](https://www.bilibili.com/video/BV1yyjN6vEZz)
- **大模型强化学习一次讲透：RLHF、DPO、GRPO、RLVR 到底怎么选？**
  - [B station](https://www.bilibili.com/video/BV1g2E26AEPD)
- **同样100万Token，为什么有的模型贵30倍？大模型 API 到底在卖什么？一口气讲透 Token 成本、KV Cache 和缓存机制**
  - [B station](https://www.bilibili.com/video/BV1e17y6wEy5)
- **大模型到底是怎么思考的？是在读文字，还是在算向量？一期讲透 Token Space 和 Latent Space**
  - [B station](https://www.bilibili.com/video/BV1ABRyBqEoR)
- **RAG vs GraphRAG vs LLM Wiki 一次讲透：Karpathy引爆的LLM Wiki，是知识工程的下一次革命，还是又一个被高估的"自我进化"**
  - [B station](https://www.bilibili.com/video/BV1NG9xBUEju)
- **Claude Code源码曝光 底层技术硬核拆解：1884个文件背后，Anthropic如何构建Agent Runtime？**
  - [B station](https://www.bilibili.com/video/BV1zR9JBREua)
- **为什么你的Agent总翻车？Harness Engineering全拆解：Anthropic、OpenAI、DeepMind都在押注的Agent Runtime**
  - [B station](https://www.bilibili.com/video/BV1VBX9BrEon)
- **0基础看懂多模态AI：架构三件套、数据工程、思维链到RAG，一期讲透**
  - [B station](https://www.bilibili.com/video/BV1ywXsBkEDS)
- **2026 AI Agent框架终极指南：从入门到生产部署的选型地图，10大框架五大范式，一期全讲透**
  - [B station](https://www.bilibili.com/video/BV1SqAVzLEci)
- **从RAG到Deep Research：单轮检索vs自主研究Agent，GRPO训练、混合检索、记忆管理怎么选？10篇论文带你看清RAG之后的下一代检索架构**
  - [B station](https://www.bilibili.com/video/BV1GAwmzCEB4)
- **AI Agent终于能边用边学了？MemRL这篇论文太有工程价值了！MemRL给出新解法，提出无参数化Runtime Learning**
  - [B station](https://www.bilibili.com/video/BV18twWzuELh)
- **多模态推理模型不一定要堆规模，微软Phi-4-reasoning-vision-15B的另一条路**
  - [B station](https://www.bilibili.com/video/BV1X4PQz8EW8)
- **RNN不再“金鱼记忆”！一篇论文讲透Memory Caching，Mamba长上下文终于能打了**
  - [B station](https://www.bilibili.com/video/BV1GHP4zZESk)
- **Agent 总犯同样的错？SKILLRL技能增强强化学习：把失败轨迹蒸馏成技能库，胜率硬拉 12%+！冷启动微调 + 验证驱动进化**
  - [B station](https://www.bilibili.com/video/BV1kHPqzqEJh)
- **ARLArena：4B小模型用SAMPO训练，Agent任务成功率碾压GPT-5.2**
  - [B station](https://www.bilibili.com/video/BV1vcPEzuERE)
- **Qwen 3.5 为何爆火？ 从架构到应用：MoE、混合注意力、Agent 工作流一次讲透**
  - [B station](https://www.bilibili.com/video/BV1BCZBBSEJj)
- **多模态大模型视频理解加速｜VideoAuto-R1：GRPO 强化学习 + 置信度，实现动态推理与Early Exit｜让视频推理又快又准**
  - [B station](https://www.bilibili.com/video/BV1h7zFBEEFA)
- **多模态视频理解怎么落地？学完这期，你就能独立部署一个多模态视频大模型服务：VideoAuto-R1 部署实战，把多模态视频大模型真正“上线”！**
  - [B station](https://www.bilibili.com/video/BV1Pez1BNEqA)
- **智谱GLM-TTS本地部署全流程：模型下载 + 推理跑通 + 多GPU批量生成 含音素控制｜命令行/批量推理/Gradio可视化｜语音克隆**
  - [B station](https://www.bilibili.com/video/BV1wjqaBpESg)
- **【ThinkMorph 论文精讲】多模态交错思维链的三大涌现能力！跨模态推理的未来方向 Interleaved CoT 详解｜AI大模型｜多模态大模型**
  - [B station](https://www.bilibili.com/video/BV1SFCqBFEfC)
- **KIMI K2 Thinking 深度解析：从万亿MoE到智能体时代的架构革命｜超越DeepSeek的思考模型｜MoonshotAI｜AI Agent**
  - [B station](https://www.bilibili.com/video/BV1sJCnBGESj)
- **从CoT到Soft Thinking LLM推理效率优化实战｜多路径推理+早停机制+参数配置全流程 | 大模型推理｜AI大模型教程｜CoT思维链 | 实战案例**
  - [B station](https://www.bilibili.com/video/BV1TBT4zoE1b)
- **LLM推理新范式 Soft Thinking理论原理 离散Token局限+连续概念空间+Cold Stop机制解析｜AI大模型教程｜AI前沿技术｜大模型推理**
  - [B station](https://www.bilibili.com/video/BV1UvjzzSEKU)
- **多模态大模型Phi-4 微软首个多模态语言模型 将语音、视觉、文本处理集成到一个统一架构 模型详解｜模型架构｜模型训练Pipeline**
  - [B station](https://www.bilibili.com/video/BV1dY9BYVECo)
- **微软Phi4多模态模型本地推理 8个demo案例演示 文本生成｜图像理解｜音频理解｜多轮对话｜Phi4多模态大模型案例实战**
  - [B station](https://www.bilibili.com/video/BV1DDRNY1EeN)
- **月之暗面发布面向大模型的MoBA（混合块注意力）架构 结合MoE和稀疏注意力 算法原理详解 | Transformer | Attention | LLM**
  - [B station](https://www.bilibili.com/video/BV1gkPieREDw)
- **英伟达发布MM-Embed：融合文本和图像的跨模态信息检索新模型**
  - [B station](https://www.bilibili.com/video/BV163mfY4Ecg)
- **北大发布多模态大模型LLaVA-o1（已更名为LLaVA-CoT）推理计算Scaling新思路**
  - [B station](https://www.bilibili.com/video/BV1TfUpYkEQg)
- **Google发表最新推理Scaling研究，从DRAG到IterDRAG，大模型RAG性能更上一层楼**
  - [B station](https://www.bilibili.com/video/BV1gFBtYwEMG)
- **探索OpenAI o1模型系列：推理能力的全新进展**
  - [B station](https://www.bilibili.com/video/BV1GYbFepEhQ)
- **Agent为什么难落地？企业级AI Agent落地的5大核心挑战与解决方案｜腾讯、阿里、百度企业级实践深度拆解**
  - [B station](https://www.bilibili.com/video/BV1P3gs6uEbJ)
- **你的 Agent 为什么一上线就翻车？模型不是瓶颈，Harness 才是关键！深入理解 Model + Harness 工程架构**
  - [B station](https://www.bilibili.com/video/BV1te8J62ETV)
- **企业级 Agent 落地方法论：模型太慢、调用太贵、动作太险，高频业务里的Agent该怎么用？**
  - [B station](https://www.bilibili.com/video/BV12u8z6eEax)
- **AI Agent 安全核心：如何给大模型分级授权？三层权限体系详解：分级授权、凭证隔离、签名许可｜企业级 Agent 落地方法论**
  - [B station](https://www.bilibili.com/video/BV1kf8t6hEH8)
- **AI Agent会“作弊”？测试全通过，也可能根本没完成任务｜企业级 Agent 落地方法论｜AI Agent｜智能体教程**
  - [B station](https://www.bilibili.com/video/BV1kch56oERd)
- **模型再强也救不了 Agent：语义和记忆才是真正的瓶颈｜AI Agent｜AI 大模型｜Agent 记忆**
  - [B station](https://www.bilibili.com/video/BV1ueta67Efx)
- **Claude Code 为什么不会撑爆上下文？深入解析 Agent 上下文压缩与会话恢复机制｜上下文投影、压缩、缓存与会话恢复全过程**
  - [B station](https://www.bilibili.com/video/BV1nJ396JEmC)
- **Hermes Agent 记忆架构详解｜四层记忆系统如何持久化？长期事实、完整历史、外部recall，一次讲透**
  - [B station](https://www.bilibili.com/video/BV17KoFBBEqM)
- **Agent记忆框架怎么选？5大Agent Memory项目工程级横向对比，哪一种才是未来Agent记忆的标准答案**
  - [B station](https://www.bilibili.com/video/BV1p2DyB4Ee3)
- **Agent记忆系统深度拆解（下）｜MemOS / OpenViking / Hindsight / Second Me / MetaMem 五大开源架构全景对比**
  - [B station](https://www.bilibili.com/video/BV1orQJB2Edt)
- **Claude Code 的记忆机制到底强在哪？六维记忆体系深度解析，一节视频讲透指令记忆、长期记忆、Session Memory 与 AutoDream**
  - [B station](https://www.bilibili.com/video/BV1z6SXBzEYh)
- **Agent 持续学习到底是什么？为什么它用一百次，还像第一次？**
  - [B station](https://www.bilibili.com/video/BV13kKV6CEC7)
- **Agent记忆越多越聪明？恰恰相反：真正关键的是这4个动作｜写入、巩固、检索、遗忘的第一性原理｜Agent Continual Learning｜智能体持续学习**
  - [B station](https://www.bilibili.com/video/BV1opKr6FEBC)
- **为什么 Agent 不能照搬过去的经验？七要素定义一个合格 Agent Skill｜Agent Continual Learning 系列课程**
  - [B station](https://www.bilibili.com/video/BV1CYKY6nEok)
- **Agent 如何持续学习？什么时候必须改模型权重？深入理解 AI Agent 的记忆、Skill 与模型参数更新机制｜Agent 持续学习的四层路由法则**
  - [B station](https://www.bilibili.com/video/BV1ebg16jELx)
- **给 Agent 加 Memory 真的会变聪明吗？深入解析 AI 持续学习系统设计｜Agent Continual Learning｜AI Agent｜智能体**
  - [B station](https://www.bilibili.com/video/BV1kvgx66EZi)
- **OpenClaw 开源生态全景解读：14 个 AI Agent 项目，从 56 万行到 888KB**
  - [B station](https://www.bilibili.com/video/BV1KpNPzQEZs)
- **OpenClaw生态16个开源项目深度拆解： AI Agent之间怎么组队协作？从Agent协作到5美元芯片（第二期）**
  - [B station](https://www.bilibili.com/video/BV1o8QoBSEFF)
- **OpenClaw 任务调度系统是怎么设计的？如何编排 Agent 的定时任务？**
  - [B station](https://www.bilibili.com/video/BV1UZcCzxEM5)
- **拆解 OpenClaw Agent Runtime：工业级 AI Agent 执行引擎到底怎么跑起来的？**
  - [B station](https://www.bilibili.com/video/BV1NWPTzRE7w)
- **OpenClaw Gateway如何让 AI Agent 稳定运转，AI助手同时接入多个平台，消息怎么调度？**
  - [B station](https://www.bilibili.com/video/BV1GDA2z1Eh5)
- **让AI拥有记忆：拆解OpenClaw开源记忆系统的架构设计｜BM25+向量混合搜索、时间衰减、降级容错**
  - [B station](https://www.bilibili.com/video/BV1C5fiBREUu)
- **Agent为什么能用强化学习训练？5分钟讲清马尔可夫决策过程MDP｜强化学习基础**
  - [B station](https://www.bilibili.com/video/BV16wAEzyEi5)
- **AI Agent进入强化学习时代！微软Agent Lightning到底解决了什么问题？**
  - [B station](https://www.bilibili.com/video/BV1GzwezrEXg)
- **GAIA最强Agent实战：从0到1做可落地Agent｜AWorld+MCP架构全拆解｜多模态工具链+自动评测+WebUI/CLI一套跑通｜智能体｜AI大模型**
  - [B station](https://www.bilibili.com/video/BV1k2fDBFExy)
- **【DeepSeek系列】DeepSeek R1 + Ollama + OpenWebUI 本地化部署 交互页面展示｜DeepSeek教程**
  - [B station](https://www.bilibili.com/video/BV1LiEjzBE64)
- **【DeepSeek系列】DeepSeek R1 本地化部署流程：模型显卡需求｜Ollama安装｜运行DeepSeek R1模型的3种方式｜Docker部署**
  - [B station](https://www.bilibili.com/video/BV1iEEJz2EeA)
- **【DeepSeek系列】通过3种方式访问DeepSeek模型服务: 通过CLI运行推理｜通过API访问服务｜通过Python访问服务｜DeepSeek教程**
  - [B station](https://www.bilibili.com/video/BV1RHEJzyEmk)
- **【AI新趋势】什么是Agentic RAG？颠覆传统RAG的智能升级！大模型LLM+Agent智能体+检索增强生成RAG 系列课程更新中**
  - [B station](https://www.bilibili.com/video/BV17J7fzxEL7)
- **为什么大模型总是答非所问？LLM面临的四大挑战，核心问题一次搞懂**
  - [B station](https://www.bilibili.com/video/BV1hQ7ZzyE7D)
- **本地部署DeepSeek大模型，只需3步！Ollama + Docker 快速运行 API 服务**
  - [B station](https://www.bilibili.com/video/BV1cBEezcEau)
- **DeepSeek大模型上线Web可视化界面！OpenWebUI + Ollama 部署全流程实战**
  - [B station](https://www.bilibili.com/video/BV1QREezEERt)
- **1分钟了解一个高效AI项目技术栈：Ollama + Playwright + MLFlow 搭建LLM服务我选这3个工具，非常高效！**
  - [B station](https://www.bilibili.com/video/BV1juEizZEL7)
- **教你如何不用OpenAI API Key 不花一分钱 即可跑通OpenAI Agents SDK全流程！**
  - [B station](https://www.bilibili.com/video/BV1m4EizLEEh)
- **搞懂RAG三大核心机制！LLM如何靠检索增强提升上下文理解力？**
  - [B station](https://www.bilibili.com/video/BV1LpEkzVE38)
- **【AI基础知识】LLM与RAG有何区别？一张图带你全面理解！**
  - [B station](https://www.bilibili.com/video/BV1QoEpz7EAL)
- **【AI Agent入门】3分钟了解LLM驱动的智能体核心原理**
  - [B station](https://www.bilibili.com/video/BV1aPEDztESh)
- **【RAG系统架构】一张图看懂检索增强生成流程！**
  - [B station](https://www.bilibili.com/video/BV1ABEfzTEp9)
- **【Agentic RAG框架详解】大模型+智能体的检索增强新范式**
  - [B station](https://www.bilibili.com/video/BV1mpJ6ztEL3)
- **AI Agent 五大工作模式详解｜图解LLM智能体执行流程**
  - [B station](https://www.bilibili.com/video/BV13RJ7zMEkD)
- **AI Agent核心能力全解析｜LLM、记忆、规划与工具是如何协作的？**
  - [B station](https://www.bilibili.com/video/BV1QtJxzZEH7)
- **Qwen3本地RAG项目全流程 | Agentic RAG智能问答系统 项目结构 + UI功能介绍**
  - [B station](https://www.bilibili.com/video/BV1TRj4zJECR)
- **【AI知识库索引构建方法】多模型支持 Transformer/Sentence-Transformer/BM25多方法 实现高效索引**
  - [B station](https://www.bilibili.com/video/BV1TWjgzvEmY)
- **【LoRA微调核心问题】为什么LoRA权重初始化用正态分布，而不是零矩阵？**
  - [B station](https://www.bilibili.com/video/BV1Fyj2zoEwv)
- **AI Agents + RAG 智能体驱动的检索增强新范式｜Agentic RAG的核心理念**
  - [B station](https://www.bilibili.com/video/BV1uNjizCEai)
- **【DeepSeek系列】RAG智能问答系统项目全览｜DeepSeek R1+Ollama+FAISS+Gradio实现流程｜PDF上传智能问答**
  - [B station](https://www.bilibili.com/video/BV1Y67HzjEdC)
- **【多智能体Agents应用实践】本地浏览器搜索Agent 多代理协作系统完整实现方案 | 支持Ollama大模型 | 自动规划搜索策略+并发任务+结构化研究报告**
  - [B station](https://www.bilibili.com/video/BV1Rj7azkELc)
- **【工具调用-高德天气API集成】手把手教你集成高德天气API｜完整演示高德API Key申请流程**
  - [B station](https://www.bilibili.com/video/BV1n6TuzaEQZ)
- **【AI Agent 实战】从0到1构建天气查询Agent 基于Ollama+Qwen本地模型 高德API全流程实战**
  - [B station](https://www.bilibili.com/video/BV1eLTCz2EK2)
- **【保姆级教程】原创案例 从零到一手把手教你 DeepSeek-R1 蒸馏版大模型微调 | 基于PyTorch QLoRA PEFT vLLM**
  - [B station](https://www.bilibili.com/video/BV1KfMuzVEKN)
- **MCP智能助手实战 | 手把手打造AI待办事项系统，支持Claude Desktop集成！**
  - [B station](https://www.bilibili.com/video/BV1NdNnzPEbq)
- **入门级教程 含源码解析｜DeepSeek-R1 + LangChain构建智能问答助手，支持RAG检索、多轮对话、文档解析｜大模型RAG实战教程**
  - [B station](https://www.bilibili.com/video/BV1hb3MzRE9G)
- **【含源码解析】多智能体协同案例：从大纲生成到科幻故事全流程AI创作｜Ollama本地大模型+AI Agent智能体协作｜Agent开发｜大模型Agent实战**
  - [B station](https://www.bilibili.com/video/BV18Z3RzHEkB)
- **AI Agent开发调试利器！MCP协议实战Anthropic开源的MCP Inspector，可视化测试你的大模型工具！**
  - [B station](https://www.bilibili.com/video/BV1ojGAzHEUa)
- **【硬核科普】3分钟看懂AI搜索核心：文本嵌入与重排序！**
  - [B station](https://www.bilibili.com/video/BV1kp8FzaEzZ)
- **Qwen3 Embedding模型论文3大创新点详解：刷新MTEB榜单！**
  - [B station](https://www.bilibili.com/video/BV1mH8Bz2Es2)
- **DeepSeek R1 大模型微调实战项目 从数据到发布HuggingFace 全流程保姆级教程 基于unsloth+LoRA高效微调DeepSeek R1**
  - [B station](https://www.bilibili.com/video/BV1RH82zUEDJ)
- **【RLT强化学习项目实战】基于教师-学生范式训练数学大模型，全面提升推理能力！用GRPO训练Qwen3模型｜SFT+RL两阶段训练全流程**
  - [B station](https://www.bilibili.com/video/BV1BohnzXErY)
- **vLLM部署实战：DeepSeek-R1蒸馏模型高性能上线全流程！**
  - [B station](https://www.bilibili.com/video/BV1RWtpzVEQN)
- **【Qwen3实战】5分钟带你看懂Qwen3双阶段检索｜Embedding+Reranker精准提升搜索&推荐效果！**
  - [B station](https://www.bilibili.com/video/BV1vaeFzcEhf)
- **RAG(检索增强生成)到底是怎么运作的？从数据索引到搜索生成，带你掌握构建智能问答系统的关键技术，让大模型生成更精准答案！**
  - [B station](https://www.bilibili.com/video/BV1u4YQzaEkb)
- **【智能体必修课】如何让AI学会任务分工与接力？智能体常用代理模式之一：交接与路由模式 Ollama多语言代理 案例演示｜大模型实战教程｜Agent智能体**
  - [B station](https://www.bilibili.com/video/BV1W7adzcERx)
- **【源码级拆解】Agent驱动的Python代码执行器｜智能体决策+工具调用+消息处理｜智能体教程｜AI Agent｜大模型实战**
  - [B station](https://www.bilibili.com/video/BV17NHCzsEiP)
- **学完就能用！从0到1搭建Agentic RAG问答系统：Qwen3大模型+FAISS+Streamlit｜完整环境配置+实战部署教学｜RAG知识库搭建**
  - [B station](https://www.bilibili.com/video/BV1KCHQzhETL)
- **【FlashRAG实战入门】环境配置 + Pipeline实现 + Web端交互｜大模型RAG项目实战｜RAG检索增强生成**
  - [B station](https://www.bilibili.com/video/BV1ewp3zcEvG)
- **从0搭建VRAG多模态RAG：视觉检索+裁剪bbox+多轮对话，一键跑通Qwen2.5-VL实战**
  - [B station](https://www.bilibili.com/video/BV1CUSKBmEVS)
- **别再只做向量检索了！企业知识库检索必备：两阶段检索Embedding粗排 + Reranker精排 项目Demo全流程 含源码讲解**
  - [B station](https://www.bilibili.com/video/BV1TcmjBCE6J)
- **5分钟搞懂：Agent Skill 与 Prompt/Tool/MCP关系与区别！**
  - [B station](https://www.bilibili.com/video/BV1fgftBxEdY)
- **企业级RAG为什么选ElasticSearch？“搜索引擎+向量检索”融合方案｜Docker一键部署ElasticSearch+Kibana｜RAG向量检索**
  - [B station](https://www.bilibili.com/video/BV1DY6qBdEk9)
- **Agent 工程化必看：一节讲透 Skill/Prompt/Tool/MCP区别！Skill体系+按需加载，让 Agent 不再“跑偏**
  - [B station](https://www.bilibili.com/video/BV1NWcnzHEwZ)
- **Agent Skills 实战教程：如何让 Agent 按需加载知识？渐进式披露完整流程｜Agno Skills工作流全链路解析｜AI大模型｜智能体**
  - [B station](https://www.bilibili.com/video/BV1yUfnBjEu2)
- **Agno框架Agent实战：智能写作Skill实现指南，Agent与Skill打造高效AI写作助手｜AI智能体｜大模型应用**
  - [B station](https://www.bilibili.com/video/BV1sYfABeEoQ)
- **一节搞懂Agent Skill工作流，手把手实现一个数据分析Skill：脚本执行+参考文档编排，用Skill把能力模块化｜智能体应用｜大模型实战｜AIAgent**
  - [B station](https://www.bilibili.com/video/BV1eqfBBmE2j)
- **Skill+MCP协同：智能电商客服Agent项目实战，多Skill动态选择 + 知识驱动工具调用，退款/咨询/故障+查单跨域协作（Skill + MCP）**
  - [B station](https://www.bilibili.com/video/BV1yJfSBfEVp)
- **DeepSeek 证明 LLM 才是更好的视觉编码器！DeepSeek OCR 2.0 架构拆解：基于Causal Queries的视觉Token重排序与压缩**
  - [B station](https://www.bilibili.com/video/BV1uqz9BNEQw)
- **DeepSeek OCR 模型架构全解析｜从视觉编码到文本理解的核心机制详解｜AI大模型｜多模态大模型｜LLM**
  - [B station](https://www.bilibili.com/video/BV1GNsWzeEYc)
- **DeepSeek-OCR模型部署与推理全流程｜多模态OCR实战：从环境配置到API服务上线｜多模态大模型｜AI大模型实战**
  - [B station](https://www.bilibili.com/video/BV1RtyaBbEC4)
- **【大模型部署必学第一课】DeepSeek R1 实战 Ollama+OpenWebUI 本地RAG系统实战教程 全流程演示｜大模型教程｜RAG知识库搭建**
  - [B station](https://www.bilibili.com/video/BV18pP2eEEPk)
- **DeepSeek R1 项目实战 基于Langchain+Faiss+Ollama+Gradio+Docker 从0到1实现RAG私有化部署 简易版实现**
  - [B station](https://www.bilibili.com/video/BV1LMN8emEbD)
- **DeepSeek R1 深入浅出RAG技术实战：整合大模型、Ollama、FAISS、Gradio 和 Docker 搭建智能问答系统**
  - [B station](https://www.bilibili.com/video/BV1i8NheHEab)
- **DeepSeek R1 大模型微调 基于unsloth微调框架与LoRA以及CoT问答数据集 wandb可视化训练日志 大模型微调与推理全流程实战**
  - [B station](https://www.bilibili.com/video/BV1J8NGezENE)
- **DeepSeek R1 原创项目 基于PyTorch QLoRA PEFT vLLM 实现R1蒸馏版大模型微调与部署 单卡/多卡两种方法**
  - [B station](https://www.bilibili.com/video/BV1HPwfeAEhz)
- **DeepSeek R1 原创项目 核心源码讲解 AI大模型 deepseek蒸馏版大模型微调与部署实战教程 基于PyTorch QLoRA PEFT vLLM**
  - [B station](https://www.bilibili.com/video/BV1yXAzeDELm)
- **《DeepSeek系统实战：架构·算法·工程·应用》课程简介**
  - [B station](https://www.bilibili.com/video/BV1WfrPB9Ewk)
- **阿里AgentEvolver：Agent如何“自提问-自导航-自归因”实现高效自进化？大模型Agent强化学习提效思路**
  - [B station](https://www.bilibili.com/video/BV1wgqDBuE4b)
- **AgentEvolver 强化学习+LLM Agent：Self-Questioning 让智能体自己造训练集｜多智能体/工具调用都能用 逆向任务生成**
  - [B station](https://www.bilibili.com/video/BV1mTBKBxEYw)
- **Agent强化学习训练提效：Self-Navigating 经验驱动探索与隐式经验学习｜AgentEvolver 自进化Agent系统｜大模型Agent｜智能体**
  - [B station](https://www.bilibili.com/video/BV1jcB2BXE1Z)
- **长程任务RL的“信用分配”怎么破？从“结果奖励”到“过程奖励” Self-Attributing把稀疏奖励变密集｜AgentEvolver深度解读**
  - [B station](https://www.bilibili.com/video/BV1HHBQBCELa)
- **AgentEvolver实战：AppWorld 环境 + GRPO 跑通「Agent自进化训练」全流程（安装/启动/配置）AI Agent｜强化学习**
  - [B station](https://www.bilibili.com/video/BV1nNibBuEGs)
- **AWorld 企业级 Multi-Agent 框架深度解析：多智能体协作 + MCP工具 + 强化学习训练｜AI Agent｜智能体教程｜AI大模型**
  - [B station](https://www.bilibili.com/video/BV1LaWiz6ESN)
- **AWorld 框架快速入门：环境搭建到第一个AI助理实例｜多智能体｜AI Agent教程｜智能体开发**
  - [B station](https://www.bilibili.com/video/BV17HWCzhEAo)
- **【AI Agent实战】一节掌握4大智能体：搜索+分析+工具+协作全流程 含源码解析｜AWorld框架深度解析｜大模型应用｜AI Agent｜多智能体**
  - [B station](https://www.bilibili.com/video/BV1JYsZzVEq8)
- **GAIA项目实战：用 MCP 工具生态打造 Production-Ready 多模态 Agent（AWorld 架构拆解）**
  - [B station](https://www.bilibili.com/video/BV177S4B8EPH)
- **GAIA项目实战：从0跑通 AWorld！环境搭建 + WebUI/CLI 双模式联调（含Playwright/E2B）Agent智能体教程｜MCP协议｜多模态**
  - [B station](https://www.bilibili.com/video/BV18P2xBzEBc)
- **微软强化学习框架 Agent Lightning 核心方法论深度解读：零代码RL优化AI Agent｜从MDP理论到分层RL算法，无缝接入现有Agent框架**
  - [B station](https://www.bilibili.com/video/BV13qbYzMEpM)
- **深度拆解Agent Lightning系统架构设计｜分布式训练+核心模块全流程解析｜强化学习｜大模型推理｜智能体教程**
  - [B station](https://www.bilibili.com/video/BV11DYqzUEhn)
- **【SQL Agent实战】Agent Lightning 项目：LangChain + LangGraph + 强化学习｜智能体教程｜AI大模型实战**
  - [B station](https://www.bilibili.com/video/BV1W2YyzvEz4)
- **【Agent Lightning实战】智能计算Agent项目概述｜AutoGen + MCP + 强化学习 + Qwen大模型｜智能体教程｜强化学习实战**
  - [B station](https://www.bilibili.com/video/BV1SPeoz1ELg)
- **【Agent Lightning实战全流程】手把手教你搭建智能计算Agent｜从环境配置到模型推理一步到位｜强化学习算法+全流程实操**
  - [B station](https://www.bilibili.com/video/BV166h2z8ERc)
- **RAG Agent RL实战指南（上）：数据准备、模型下载与知识库构建｜搭建智能检索增强系统｜强化学习｜RAG｜Agent智能体**
  - [B station](https://www.bilibili.com/video/BV17xahzUEiG)
- **RAG Agent RL实战指南（下）：从0到1部署检索服务，启动分布式强化学习训练！Agent Lightning 智能体强化学习框架应用**
  - [B station](https://www.bilibili.com/video/BV19BpEzUEcs)
- **RAG Agent RL源码深度解析｜从数据到推理的源码级拆解与实现｜检索增强生成核心机制全流程｜大模型RAG实战｜RAG + 强化学习｜Agent智能体**
  - [B station](https://www.bilibili.com/video/BV19enPzMEWg)
- **【APO实战】Agent-Lightning 提示词自动优化：智能会议室预订Agent（LLM Judge / Beam Search / 无需微调）**
  - [B station](https://www.bilibili.com/video/BV1Kr1sBhEe6)
- **【APO算法 Debug讲解】Agent-Lightning 会议室预订Agent案例 核心源码讲解：数据流、Beam Search、LLM Judge**
  - [B station](https://www.bilibili.com/video/BV1Up23BFEJG)
- **Dify大模型应用平台深度解析 全面拆解架构、核心原理与功能机制｜大模型Agent开发｜RAG Agent 与多模型管理｜AI应用开发**
  - [B station](https://www.bilibili.com/video/BV1wK4AzcEPF)
- **Dify本地部署全流程｜Docker安装+源码构建两种方式实战教学｜AI应用框架必学｜大模型Agent应用｜智能体开发**
  - [B station](https://www.bilibili.com/video/BV1Ac42zWEMX)
- **【UltraRAG 2.0 深度剖析】科研级RAG系统新范式：MCP 架构+YAML声明式编程｜Agentic RAG | 检索增强生成｜多模态大模型｜智能体**
  - [B station](https://www.bilibili.com/video/BV1ZBpozAEqB)
- **【UltraRAG快速入门实战】从环境搭建到完整RAG Pipeline | 本地LLM+MCP架构+YAML编程｜大模型RAG项目实战｜Agentic RAG**
  - [B station](https://www.bilibili.com/video/BV1FtJ1zhEHL)
- **原创案例 Agentic RAG智能学术助手完整流程拆解 包含核心代码讲解 基于清华UtralRAG MCP架构+YAML声明式编程｜大模型RAG｜Agent**
  - [B station](https://www.bilibili.com/video/BV1tTn7zPEdx)
- **【原创实战】VisionRAG Pro：构建智能多模态视觉分析系统｜UltraRAG 2.0 + Qwen2.5-VL 全流程讲解｜MCP架构｜YAML编程**
  - [B station](https://www.bilibili.com/video/BV1Qr43zME4V)
- **【阿里最新多模态RL框架解析】VRAG-RL研究背景详解：为什么RAG在图文理解上失效？**
  - [B station](https://www.bilibili.com/video/BV1RZ8gzEEQo)
- **【阿里最新多模态RAG+Agent】VRAG-RL方法论全拆解：多专家采样 × 细粒度奖励，刷新多模态RAG新高度！**
  - [B station](https://www.bilibili.com/video/BV1ct8ozxEXx)
- **【多模态RAG实战】VRAG项目全流程解析：构建视觉增强问答系统（Agent+RAG+Qwen2.5） | 支持图文检索+多轮对话｜智能体搭建｜检索增强生成**
  - [B station](https://www.bilibili.com/video/BV135t5z7EDU)
- **从零构建自定义多模态VRAG Agent助手｜ColQwen2 嵌入+FastAPI 部署+Streamlit 可视化 全流程实战**
  - [B station](https://www.bilibili.com/video/BV1D3b8ztEX5)
- **【实战教程】本地知识库+开源框架(Ollama/Qwen/LlamaIndex)｜多模态RAG检索增强生成 训练数据集构建全流程**
  - [B station](https://www.bilibili.com/video/BV1dRYQzGEXy)
- **【强化学习实战】VRAG-RL全流程：基于Qwen2.5-VL和GRPO实现强化学习在多模态RAG中的应用｜多模态大模型｜多模态RAG｜AI大模型实战**
  - [B station](https://www.bilibili.com/video/BV11wYyzvEPj)
- **【VRAG项目架构全解析】多模态RAG与强化学习智能体的系统设计与实现｜强化学习｜多模态大模型｜检索增强生成RAG｜Agent智能体｜AI大模型教程**
  - [B station](https://www.bilibili.com/video/BV1iYewzMESg)
- **VRAG-RL核心源码精讲｜多模态检索增强生成与多步推理实现原理｜从0到1构建多模态视觉RAG Agent系统 (LlamaIndex/Ollama)**
  - [B station](https://www.bilibili.com/video/BV1YtezzTEC3)
- **RL强化学习新范式！RLT教师强化学习模型算法全解析｜SFT+RL两阶段训练全流程详解｜AI大模型微调｜大模型Agent｜Agent智能体｜Sakana AI**
  - [B station](https://www.bilibili.com/video/BV1ywG5zhE6k)
- **【RLT强化学习算法原理】稠密奖励函数详解，训练更稳定、收敛更快的关键｜基于学生模型对数似然与KL散度的稠密奖励机制深度分析｜强化学习的数学原理｜AIAgent**
  - [B station](https://www.bilibili.com/video/BV1orubzJEPq)
- **强化大模型的最后一环！RLT教师强化学习项目实战：奖励模型+偏好优化全流程解析（SFT+GRPO）**
  - [B station](https://www.bilibili.com/video/BV1VHg3zPEfN)
- **Qwen3 Embedding 模型详解：文本嵌入与重排序性能全面超越SOTA 重新定义文本嵌入 RAG必备神器｜检索增强生成｜大模型RAG｜通义千问**
  - [B station](https://www.bilibili.com/video/BV1xHM3zjEr6)
- **Qwen3 Embedding+Reranker黄金组合 本地推理与部署实战 (附核心代码讲解) ｜RAG核心组件｜检索增强生成｜大模型rag教程**
  - [B station](https://www.bilibili.com/video/BV1kVMAzSEHC)
- **【实战】Qwen3 Embedding高效知识库检索系统Demo｜Embedding+Reranker两阶段精准召回｜检索增强生成｜大模型RAG实战**
  - [B station](https://www.bilibili.com/video/BV1GYM2zdEbR)
- **Qwen3 Embedding模型微调教程（含LoRA与全参训练）｜支持MS-Swift框架｜AI大模型教程｜大模型微调实战**
  - [B station](https://www.bilibili.com/video/BV1dZNdzUEUG)
- **Qwen3 Reranker (重排模型) 大模型微调实战教学｜LoRA高效微调+DeepSpeed训练加速｜RAG检索增强生成｜大模型LLM教程**
  - [B station](https://www.bilibili.com/video/BV1T9KbzhE6j)
- **Agentic RAG 大模型+智能体+检索增强生成RAG 全流程实战｜大模型教程｜AI智能体｜检索增强rag | Agenticrag**
  - [B station](https://www.bilibili.com/video/BV1ZiEEzLE3X)
- **【RAG原理详解】如何用检索增强生成技术提升大模型问答能力｜原理+挑战+解决方案全解析**
  - [B station](https://www.bilibili.com/video/BV12pEFzGEyQ)
- **【深度解析】Agentic RAG原理详解：智能体驱动的检索增强新范式｜大模型+智能体融合应用讲解｜大模型教程｜Agent智能体｜检索增强生成技术**
  - [B station](https://www.bilibili.com/video/BV1NdEqzLEG5)
- **Agent核心架构全解：四大设计模式＋五类工作流机制｜含图解与主流框架实战分析｜Agentic RAG｜大模型Agent教程 ｜检索增强生成RAG**
  - [B station](https://www.bilibili.com/video/BV13uE8zeEVz)
- **Agentic RAG架构全解析：7种典型系统设计与实战应用 层级、多Agent、自适应、纠错型一次讲透｜大模型RAG进阶｜智能体Agent｜大模型RAG教程**
  - [B station](https://www.bilibili.com/video/BV1e4E9zuEGh)
- **【原创案例】Agentic RAG 基于Qwen3+langchain+ollama+Faiss+agno搭建完整RAG系统｜AI大模型教程｜大模型RAG**
  - [B station](https://www.bilibili.com/video/BV17PJhzSEBy)
- **【源码解析】原创案例 Agentic RAG 本地化智能问答系统 项目实现思路及核心源码讲解 ｜Agent智能体工作流教程｜源码分析｜大模型智能体**
  - [B station](https://www.bilibili.com/video/BV1VqJnz7ELU)
- **OpenAI Agents SDK 轻量级多智能体框架 基于大模型构建多智能体工作流 Agent智能体 Workflow 多轮对话 智能问答 对话助手**
  - [B station](https://www.bilibili.com/video/BV1ajXkY2Edx)
- **大模型Agent实战 原创案例 高德天气查询助手Agent 多智能体开发框架OpenAI Agents 智能体搭建 agent智能体工作流 智能体开发教程**
  - [B station](https://www.bilibili.com/video/BV1VCoBY7ErL)
- **OpenAI Agents 多智能体开发框架 常用代理模式 确定性模式案例：写作助手Agent 大模型Agent实战 AI大模型教程 智能体工作流**
  - [B station](https://www.bilibili.com/video/BV1ANotYYEFL)
- **OpenAI Agents 多智能体开发框架 常用代理模式 交接与路由模式 Agent智能体搭建 大模型Agent实战 智能体开发 agent智能体工作流教程**
  - [B station](https://www.bilibili.com/video/BV1TAZKYEEzh)
- **OpenAI Agents SDK 多智能体开发框架 常用代理模式 代理作为工具 大模型Agent实战 AI Agent 智能体搭建 agent智能体工作流教程**
  - [B station](https://www.bilibili.com/video/BV1iJZVYSEtv)
- **OpenAI Agents SDK 多智能体开发框架 常用代理模式 LLM大模型作为评判者 Agent智能体 AI大模型实战教程 写作助手Agent案例演示**
  - [B station](https://www.bilibili.com/video/BV1qpZSYWEzf)
- **OpenAI Agents SDK 多智能体开发框架 常用代理模式 并行模式 大模型Agent教程 AI大模型 智能体Agent**
  - [B station](https://www.bilibili.com/video/BV1BeRqY2E51)
- **OpenAI Agents SDK 原创案例 大模型Agent实战 本地浏览器自动化检索（类似 Manus 效果）AI 智能体搭建 Agent开发教程**
  - [B station](https://www.bilibili.com/video/BV1GSdpYPEMB)
- **【MCP模型上下文协议实战指南】 AI Agent多场景应用实战 AI大模型应用实战教程 多智能体｜LLM｜DeepSeek｜MCP协议｜MCP入门**
  - [B station](https://www.bilibili.com/video/BV1XwZHYPExh)
- **MCP模型上下文协议 基于Claude和Cline进行MCP服务器配置 大模型MCP案例实战 MCP Server开发 MCP客户端构建 ai大模型教程**
  - [B station](https://www.bilibili.com/video/BV1cvZUY4Ec9)
- **MCP模型上下文协议 MCP Inspector调试MCP Servers的使用方法 AI大模型｜AI Agent｜智能体Agent｜mcp教程**
  - [B station](https://www.bilibili.com/video/BV1DgZZYeE4Y)
- **MCP Server开发与应用 原创案例 待办事项助手 基于MCP Inspector可视化调试MCP Server AI大模型实战教程｜智能体Agent**
  - [B station](https://www.bilibili.com/video/BV1fgRfYkEfk)
- **AI Agent全景解析 + Lagent框架简介｜从智能体核心组件到开源项目｜大模型Agent教程｜AI前沿技术分享｜AI智能体**
  - [B station](https://www.bilibili.com/video/BV1c8wNe1EL6)
- **AI Agent实战入门｜环境配置 + 基础对话模型调用｜大模型Agent实战｜智能体开发框架｜Agent智能体教程**
  - [B station](https://www.bilibili.com/video/BV1PdwWe6Ei3)
- **大模型Agent实战 LLM智能体轻量级开发框架 lagent 项目实战 案例二 fewshot 示例增强**
  - [B station](https://www.bilibili.com/video/BV1ucwYeuEfd)
- **大模型Agent实战 LLM智能体轻量级开发框架 lagent 项目实战 案例三 Agent驱动的Python代码执行器**
  - [B station](https://www.bilibili.com/video/BV1fLfhYgE3C)
- **大模型Agent实战 LLM智能体轻量级开发框架 lagent 项目 案例四 高德 天气API集成**
  - [B station](https://www.bilibili.com/video/BV1c3fkYkEJE)
- **大模型Agent实战 LLM智能体轻量级开发框架 lagent 项目 案例五 高德位置搜索和导航**
  - [B station](https://www.bilibili.com/video/BV1qsPoeoE1X)
- **FlashRAG 大模型RAG研究一站式解决方案 项目简介**
  - [B station](https://www.bilibili.com/video/BV1Tuk3YREML)
- **FlashRAG 大模型LLM与RAG研究利器 核心组件原理精讲**
  - [B station](https://www.bilibili.com/video/BV1x3k3YWEeC)
- **FlashRAG 大模型LLM与RAG研究高效工具包 案例实践 快速入门Demo**
  - [B station](https://www.bilibili.com/video/BV1Q4kAYgEPm)
- **FlashRAG 大模型LLM与RAG研究利器 核心模块参数详细解析**
  - [B station](https://www.bilibili.com/video/BV1V2kBY5EJo)
- **FlashRAG 项目实战 基于Transformers和BM25构建密集索引和稀疏索引**
  - [B station](https://www.bilibili.com/video/BV1NHkSYcEoS)
- **FlashRAG 项目实战 大模型LLM与RAG研究利器 论文实验流程复现**
  - [B station](https://www.bilibili.com/video/BV1BWkRYPEQM)
- **FlashRAG 大模型LLM与RAG研究利器 案例实战 核心源码Debug深度剖析**
  - [B station](https://www.bilibili.com/video/BV1nECBY4E8g)
- **Meta重磅发布Llama 3.2：开放可定制的大模型深度解析 轻量级AI大模型和多模态模型 模型架构｜大模型教程｜AI前沿技术**
  - [B station](https://www.bilibili.com/video/BV1d5xEeiEp5)
- **Llama3模型深入解析 核心功能 模型架构详解 大模型基础知识 llama3教程｜AI大模型教程｜AI前沿技术**
  - [B station](https://www.bilibili.com/video/BV1pu4m1F7Ax)
- **【系列课程】Llama3模型部署环境配置 基于vLLM推理 大模型实战**
  - [B station](https://www.bilibili.com/video/BV1yt421P7ML)
- **【系列课程】深度探索Llama 3 Torchrun分布式推理与特殊标记应用 大模型llama系列课程**
  - [B station](https://www.bilibili.com/video/BV1ex4y187bx)
- **【实操干货】Llama3模型量化与部署 基于llama.cpp进行大模型本地推理与部署 Llama3部署教程**
  - [B station](https://www.bilibili.com/video/BV1Sw4m127ye)
- **【项目实战】Llama 3模型Docker实战 利用开源项目llama.cpp进行Llama3模型的量化 并部署API服务 大模型实战教程**
  - [B station](https://www.bilibili.com/video/BV1jF4m1A7jA)
- **【Llama3 微调】基于llama-factory和自定义数据集进行大模型微调 Llama3教程 AI大模型实战课程**
  - [B station](https://www.bilibili.com/video/BV1bp421S7Db)
- **【Llama3 部署】基于TensorRT-LLM和Triton进行Llama3模型部署 AI大模型实战教程**
  - [B station](https://www.bilibili.com/video/BV1Ap421D7GA)
- **llama-2-模型推理**
  - [B station](https://www.bilibili.com/video/BV17h4y157x4)
- **1-01 实战 泰坦尼克号沉船人员获救案例 数据清洗**
  - [B station](https://www.bilibili.com/video/BV18k4y117Lf)
- **1-02 实战 泰坦尼克号沉船人员获救案例 特征构建 (一)**
  - [B station](https://www.bilibili.com/video/BV1nK4y1Y7gD)
- **1-03 实战 泰坦尼克号沉船人员获救案例 特征构建 (二)**
  - [B station](https://www.bilibili.com/video/BV1fA411Y7NH)
- **1-04 实战 泰坦尼克号沉船人员获救案例 训练集和测试集**
  - [B station](https://www.bilibili.com/video/BV1Yf4y197L1)
- **1-05 实战 泰坦尼克号沉船人员获救案例 随机森林算法实现**
  - [B station](https://www.bilibili.com/video/BV1mD4y1U7Uf)
- **2 机器学习实战 纽约出租车车费预测**
  - [B station](https://www.bilibili.com/video/BV1nz4y1f74G)
- **3-01 实战 RNN LSTM 原理**
  - [B station](https://www.bilibili.com/video/BV1kz4y1f7u7)
- **3-02 LSTM 文本生成（字符级）**
  - [B station](https://www.bilibili.com/video/BV1v5411h79S)
- **3-03 LSTM IBM股价预测 第一节**
  - [B station](https://www.bilibili.com/video/BV1xD4y1m7CC)
- **3-04 LSTM IBM股价预测 第二节**
  - [B station](https://www.bilibili.com/video/BV1fa4y177Jf)
- **3-05 LSTM IBM股价预测 第三节**
  - [B station](https://www.bilibili.com/video/BV19T4y1L7GQ)
- **3-06 LSTM IBM股价预测 第四节**
  - [B station](https://www.bilibili.com/video/BV1jZ4y1T72j)
- **3-07 LSTM IBM股价预测 第五节**
  - [B station](https://www.bilibili.com/video/BV1Rp4y1Y7Rn)
- **4-01 决策树 随机森林算法 案例实战 原理部分（上）**
  - [B station](https://www.bilibili.com/video/BV14a4y1j7QA)
- **4-02 决策树 随机森林算法案例实战 用户流失预测（下）**
  - [B station](https://www.bilibili.com/video/BV1U5411b7a8)
- **5-01 聚类算法kmeans和MeanShift原理 + 零售案例实战（上）**
  - [B station](https://www.bilibili.com/video/BV13a4y1j7uJ)
- **5-02 聚类算法kmeans和MeanShift实战 消费者画像分析**
  - [B station](https://www.bilibili.com/video/BV1Yp4y1e7A3)
- **6-01 信用卡交易欺诈数据检测 (一)**
  - [B station](https://www.bilibili.com/video/BV1Sz4y1d7SB)
- **6-02 信用卡交易欺诈数据检测 (二)**
  - [B station](https://www.bilibili.com/video/BV12t4y1v7sC)
- **6-03 信用卡交易欺诈数据检测 方法2 (三)**
  - [B station](https://www.bilibili.com/video/BV1ia411A7fd)
- **6-04 信用卡交易欺诈数据检测 方法2 (四)**
  - [B station](https://www.bilibili.com/video/BV1rK4y177E8)
- **6-05 信用卡交易欺诈数据检测 方法3 基于PyTorch实现 (五)**
  - [B station](https://www.bilibili.com/video/BV135411L7AD)
- **7-01 最牛算法之一_lightGBM算法_理论部分**
  - [B station](https://www.bilibili.com/video/BV1JK4y1L7ow)
- **7-02 最牛算法之一_lightGBM算法_交易欺诈检测实战【上集】**
  - [B station](https://www.bilibili.com/video/BV1ZZ4y1g7T6)
- **7-03 最牛算法之一_lightGBM算法_交易欺诈检测实战【下集】**
  - [B station](https://www.bilibili.com/video/BV19T4y1M7ve)
- **8_01 房屋价格预测【回归案例】**
  - [B station](https://www.bilibili.com/video/BV1b54y1p7WG)
- **8_02 房屋价格预测【回归案例】**
  - [B station](https://www.bilibili.com/video/BV18y4y117Tp)
- **8_03 房屋价格预测【回归案例】**
  - [B station](https://www.bilibili.com/video/BV1DN411d7N7)
- **09-1 进阶版 房屋价格预测案例 线性回归 理论部分**
  - [B station](https://www.bilibili.com/video/BV1Nz421D7hn)
- **09-2 进阶版 房屋价格预测 案例实战 数据预处理**
  - [B station](https://www.bilibili.com/video/BV1ob421h74v)
- **9-3 进阶版 房屋价格预测 案例实战 数据探索与分析（上）**
  - [B station](https://www.bilibili.com/video/BV1aM4m1o7u1)
- **9-4 进阶版 房屋价格预测 案例实战 数据探索与分析（下）**
  - [B station](https://www.bilibili.com/video/BV1Wt421c7iU)
- **9-5 进阶版 房屋价格预测 案例实战 特征工程**
  - [B station](https://www.bilibili.com/video/BV1Pr421g7MD)
- **9-6 进阶版 房屋价格预测 案例实战 模型训练和预测**
  - [B station](https://www.bilibili.com/video/BV1Vb421a78U)
- **lightGBM-01 机器学习算法简介**
  - [B station](https://www.bilibili.com/video/BV1K142197Yb)
- **LightGBM-02 算法大纲**
  - [B station](https://www.bilibili.com/video/BV1dT421C72B)
- **LightGBM-03 基于Histogram的决策树算法**
  - [B station](https://www.bilibili.com/video/BV1wt421w7GR)
- **LightGBM-04 单边梯度采样与互斥特征绑定**
  - [B station](https://www.bilibili.com/video/BV1kZ42177oj)
- **LightGBM-05 多线程优化**
  - [B station](https://www.bilibili.com/video/BV17T421y7ha)
- **LightGBM-06 核心超参数讲解**
  - [B station](https://www.bilibili.com/video/BV1cm421p764)
- **LightGBM-07 论文解读**
  - [B station](https://www.bilibili.com/video/BV1pD421P7ma)
- **LightGBM-08 入门案例**
  - [B station](https://www.bilibili.com/video/BV1xm421H7MC)
- **LightGBM-09 医疗分类案例**
  - [B station](https://www.bilibili.com/video/BV1FJ4m1J7Ho)
- **LightGBM-10 餐厅营收预测回归案例-上集**
  - [B station](https://www.bilibili.com/video/BV1nM4m1d7K7)
- **LightGBM-11 餐厅营收预测回归案例-下集**
  - [B station](https://www.bilibili.com/video/BV1gT42197xw)
- **01 决策树算法简介**
  - [B station](https://www.bilibili.com/video/BV1QT421a75u)
- **02 决策树算法原理（一）**
  - [B station](https://www.bilibili.com/video/BV1Rm421V7r1)
- **03 决策树算法原理（二）**
  - [B station](https://www.bilibili.com/video/BV1BE421N7xE)
- **04 决策树算法原理（三）**
  - [B station](https://www.bilibili.com/video/BV1Jm421G7oc)
- **05 决策树算法原理（四）**
  - [B station](https://www.bilibili.com/video/BV1mH4y1F7bq)
- **06 决策树算法原理（五）**
  - [B station](https://www.bilibili.com/video/BV1UJ4m1T7bS)
- **07 决策树 医疗分类案例**
  - [B station](https://www.bilibili.com/video/BV1XS421X7Ki)
- **08 决策树算法Python底层实现（一）**
  - [B station](https://www.bilibili.com/video/BV1nS42197rY)
- **09 决策树算法Python底层实现（二）**
  - [B station](https://www.bilibili.com/video/BV1fy411e7zj)
- **10 决策树算法Python底层实现（三）**
  - [B station](https://www.bilibili.com/video/BV1tS421X79P)
- **11 决策树算法Python底层实现（四）**
  - [B station](https://www.bilibili.com/video/BV1xE421w7Az)
- **12 决策树算法Python底层实现（五）**
  - [B station](https://www.bilibili.com/video/BV1kr421M7iu)
- **13_编码知识点补充**
  - [B station](https://www.bilibili.com/video/BV1YH4y1c7RV)
- **14_编码知识点补充**
  - [B station](https://www.bilibili.com/video/BV19y411i73L)
- **15_收入预测分类案例(一)**
  - [B station](https://www.bilibili.com/video/BV1kr421M7C5)
- **16_收入预测分类案例(二)**
  - [B station](https://www.bilibili.com/video/BV1k4421Z7ZJ)
- **17 收入预测分类案例（三）**
  - [B station](https://www.bilibili.com/video/BV1YUp2eTEaM)
- **18 收入预测分类案例（四）**
  - [B station](https://www.bilibili.com/video/BV1i6p2erEJC)
- **01_多模态_MiniCPM-V_项目简介**
  - [B station](https://www.bilibili.com/video/BV1T4421Q7Ei)
- **02_多模态_基于Gradio和Streamlit实现Web端问答交互**
  - [B station](https://www.bilibili.com/video/BV1E1421C7V2)
- **03_多模态_基于llama.cpp进行模型量化和推理**
  - [B station](https://www.bilibili.com/video/BV1Bw4m1v7A2)
- **04_多模态_基于vLLM进行模型推理与源码讲解**
  - [B station](https://www.bilibili.com/video/BV1jb42177ML)
- **05_多模态_基于MiniCPM-V进行全参微调和lora微调**
  - [B station](https://www.bilibili.com/video/BV1RE4m1R7ci)
- **LoRA_01_算法原理深入解析-上集**
  - [B station](https://www.bilibili.com/video/BV1cM4m1r7Fe)
- **LoRA_02_算法原理深入解析-下集**
  - [B station](https://www.bilibili.com/video/BV1FU411o7cF)
- **LoRA_03_案例演示 LoRA的核心逻辑**
  - [B station](https://www.bilibili.com/video/BV1sm421T7Xg)
- **LoRA_04_基于PEFT进行llama3模型微调实战**
  - [B station](https://www.bilibili.com/video/BV1gJ4m1A7UT)
- **LoRA_05_01_基于GPT-2进行LoRA微调实战**
  - [B station](https://www.bilibili.com/video/BV1zz421a7LN)
- **LoRA_05_02_基于GPT-2进行LoRA微调实战**
  - [B station](https://www.bilibili.com/video/BV1KD421G7Sm)
- **LoRA_06_LoRA核心算法实现**
  - [B station](https://www.bilibili.com/video/BV1HU411o7S1)
- **LoRA_07_在VS Code中debug LoRA微调细节**
  - [B station](https://www.bilibili.com/video/BV1zx4y1E7FR)
- **01 轻松学 PyTorch 简介和安装**
  - [B station](https://www.bilibili.com/video/BV1tk4y1q7Jv)
- **02 轻松学 PyTorch 初识Tensor**
  - [B station](https://www.bilibili.com/video/BV1dp4y1U7mD)
- **03-1 轻松学 PyTorch 手写字体识别 MNIST (理论)**
  - [B station](https://www.bilibili.com/video/BV12i4y1G7ko)
- **03-2 轻松学 PyTorch 手写字体识别 MNIST ( 实战 - 上 )**
  - [B station](https://www.bilibili.com/video/BV1WT4y177SA)
- **03-3 轻松学 PyTorch 手写字体识别 MNIST (实战 - 下)**
  - [B station](https://www.bilibili.com/video/BV1HK4y1s7j3)
- **04-1 轻松学PyTorch 肺部感染识别 简介**
  - [B station](https://www.bilibili.com/video/BV1wk4y1B77W)
- **04-2 轻松学 PyTorch 显示数据集中的图片（2）**
  - [B station](https://www.bilibili.com/video/BV1xA411e7oX)
- **04-3 轻松学 PyTorch 迁移学习，模型微调**
  - [B station](https://www.bilibili.com/video/BV1aZ4y1T7xd)
- **04-4 轻松学 PyTorch 定义训练函数**
  - [B station](https://www.bilibili.com/video/BV1f5411h7Yj)
- **04-5 轻松学 PyTorch 定义测试函数**
  - [B station](https://www.bilibili.com/video/BV1si4y137CD)
- **04-6 轻松学PyTorch 肺部识别案例实现**
  - [B station](https://www.bilibili.com/video/BV1Kf4y197x9)
- **05-1 Pytorch RNN LSTM MNIST实战案例**
  - [B station](https://www.bilibili.com/video/BV1n54y117KK)
- **05-2 Pytorch RNN LSTM MNIST实战案例**
  - [B station](https://www.bilibili.com/video/BV19a4y1j77Y)
- **05-3 Pytorch RNN LSTM MNIST实战案例**
  - [B station](https://www.bilibili.com/video/BV14K411P7u1)
- **05-4 Pytorch RNN LSTM MNIST实战案例**
  - [B station](https://www.bilibili.com/video/BV1iV411m76r)
- **05-5 Pytorch RNN LSTM MNIST实战案例**
  - [B station](https://www.bilibili.com/video/BV1Jt4y1q76b)
- **06-01 PyTorch 基础知识复习-1**
  - [B station](https://www.bilibili.com/video/BV1FV41117gt)
- **06-02 PyTorch 基础知识复习-2**
  - [B station](https://www.bilibili.com/video/BV11r4y1w7XM)
- **07-01 经典案例 CIFAR10 图形识别【PyTorch 官网实现】**
  - [B station](https://www.bilibili.com/video/BV1Ta411w78P)
- **07-02 经典案例 CIFAR10 图像识别【个人实现】**
  - [B station](https://www.bilibili.com/video/BV1Qa411c7JL)
- **08-01 肺部感染图像识别  -（上集）**
  - [B station](https://www.bilibili.com/video/BV1pp4y1r7uB)
- **08-02 肺部感染图像识别 -（中集）**
  - [B station](https://www.bilibili.com/video/BV13A411x7wK)
- **08-03 肺部感染图像识别 -（下集）**
  - [B station](https://www.bilibili.com/video/BV1nK4y1j7sX)
- **08-04 肺部感染图像识别 -（结果展示）**
  - [B station](https://www.bilibili.com/video/BV12t4y1a7LC)
- **09 迁移学习【图像识别]】基于Flask实现**
  - [B station](https://www.bilibili.com/video/BV1Q54y1z7Ek)
- **10_PyTorch_情感分类_LSTM实现【上篇】**
  - [B station](https://www.bilibili.com/video/BV1Bi4y157xD)
- **10 情感分类_Tensorflow_LSTM实现 - 01集**
  - [B station](https://www.bilibili.com/video/BV1UK411u7Jx)
- **10 情感分类_Tensorflow_LSTM实现 - 02集**
  - [B station](https://www.bilibili.com/video/BV1op4y1z7HK)
- **11_01_交通指示牌识别_迁移学习**
  - [B station](https://www.bilibili.com/video/BV1tZ4y137mh)
- **11_02_交通指示牌识别_迁移学习**
  - [B station](https://www.bilibili.com/video/BV1sa4y1p7KQ)
- **11_03_交通指示牌识别_迁移学习**
  - [B station](https://www.bilibili.com/video/BV1No4y1Z7j1)
- **11_04_交通指示牌识别_案例优化_识别43个类别**
  - [B station](https://www.bilibili.com/video/BV1sy4y1U7We)
- **12_01 LSTM 文本生成_字符级**
  - [B station](https://www.bilibili.com/video/BV1Dv411W78n)
- **12_02 LSTM 文本生成_字符级**
  - [B station](https://www.bilibili.com/video/BV1qv411W7fu)
- **12_03 LSTM 文本生成_字符级**
  - [B station](https://www.bilibili.com/video/BV11r4y1T73S)
- **12_04 LSTM 文本生成_字符级**
  - [B station](https://www.bilibili.com/video/BV1bK411u7ba)
- **13_01 PyTorch LSTM 情感分类【下篇】**
  - [B station](https://www.bilibili.com/video/BV16U4y147dv)
- **13_02 PyTorch LSTM 情感分类【下篇】**
  - [B station](https://www.bilibili.com/video/BV1Ay4y117yX)
- **13_03 PyTorch LSTM 情感分类【下篇】**
  - [B station](https://www.bilibili.com/video/BV1wA411u73p)
- **精讲版-01 线性回归基础知识**
  - [B station](https://www.bilibili.com/video/BV1QJ4m1E7SC)
- **精讲版-02 生成虚拟样本数据**
  - [B station](https://www.bilibili.com/video/BV1vH4y1V7Gx)
- **精讲版-03 tensor的基本概念和应用**
  - [B station](https://www.bilibili.com/video/BV1sH4y1g7bU)
- **精讲版-04 梯度下降法原理讲解**
  - [B station](https://www.bilibili.com/video/BV1FJ4m1T7TN)
- **精讲版-05 自动梯度计算backward**
  - [B station](https://www.bilibili.com/video/BV1XC411E7ap)
- **精讲版-06 优化器optimizer和损失函数MSELoss**
  - [B station](https://www.bilibili.com/video/BV1wr42177ns)
- **精讲版-07 定义模型类 进行前向传播计算**
  - [B station](https://www.bilibili.com/video/BV1Hz421m7Ag)
- **精讲版-08 序列模型 Sequential Model**
  - [B station](https://www.bilibili.com/video/BV1Jr42177Sa)
- **精讲版-09 Dataset和DataLoader封装原理和应用**
  - [B station](https://www.bilibili.com/video/BV1Gm421g7Bb)
- **精讲版-10 模型验证 代码升级**
  - [B station](https://www.bilibili.com/video/BV1nr421j7uw)
- **精讲版-11 天气预测实战-数据预处理**
  - [B station](https://www.bilibili.com/video/BV1kU411o7Vw)
- **精讲版-12 天气预测实战-模型搭建**
  - [B station](https://www.bilibili.com/video/BV17z421e77L)
- **精讲版-13 天气预测实战-模型训练和验证**
  - [B station](https://www.bilibili.com/video/BV1WD421V7U1)
- **精讲版-14 天气预测实战-模型评估 混淆矩阵**
  - [B station](https://www.bilibili.com/video/BV1JZ421s7sL)
- **DeepSpeed分布式训练框架 DeepSpeed-Chat Step-1-01 简介**
  - [B station](https://www.bilibili.com/video/BV1KV41137tS)
- **DeepSpeed分布式训练框架 DeepSpeed-Chat Step-1-02 actor 模型微调**
  - [B station](https://www.bilibili.com/video/BV1d14y1i7gU)
- **DeepSpeed分布式训练框架 DeepSpeed-Chat Step-1-03 actor 模型评估**
  - [B station](https://www.bilibili.com/video/BV1V8411R77B)
- **DeepSpeed分布式训练框架 DeepSpeed-Chat Step-1-04 actor 模型推理**
  - [B station](https://www.bilibili.com/video/BV1n8411R7gZ)
- **DeepSpeed Chat 05 Step 1 源代码解读之参数配置**
  - [B station](https://www.bilibili.com/video/BV1pN41187ex)
- **DeepSpeed Chat 06 Step 1 源码解读之分布式环境配置**
  - [B station](https://www.bilibili.com/video/BV1oj411z7Vd)
- **DeepSpeed-Chat-07-step1_源码解读_创建 tokenizer 和 model**
  - [B station](https://www.bilibili.com/video/BV1br4y1o7jh)
- **DeepSpeed-Chat-08-step1_源码解读_创建LoRA层**
  - [B station](https://www.bilibili.com/video/BV1Vz4y1g7CX)
- **DeepSpeed-Chat-09-step1_源码解读_创建数据集-第1节.mov**
  - [B station](https://www.bilibili.com/video/BV13X4y1x7VG)
- **DeepSpeed-Chat-10-step1_源码解读_创建数据集-第2节**
  - [B station](https://www.bilibili.com/video/BV1Hu4y1d7BL)
- **DeepSpeed-Chat-11-step1_源码解读_创建数据集-第3节**
  - [B station](https://www.bilibili.com/video/BV1KP411s7se)
- **DeepSpeed-Chat-12-step1_源码解读_创建数据集-第4节**
  - [B station](https://www.bilibili.com/video/BV1Sh4y1Q7jr)
- **DeepSpeed-Chat-13-step1_源码解读_创建数据集-第5节**
  - [B station](https://www.bilibili.com/video/BV1X94y1k7UF)
- **DeepSpeed-Chat-14-step1_源码解读_创建数据集-第6节**
  - [B station](https://www.bilibili.com/video/BV1Mp4y137xT)
- **DeepSpeed-Chat-15-step1_源码解读_创建优化器和调度器**
  - [B station](https://www.bilibili.com/video/BV1Z44y1c7eE)
- **DeepSpeed-Chat-16-step1_源码解读_deepspeed初始化**
  - [B station](https://www.bilibili.com/video/BV1PN41167xq)
- **DeepSpeed-Chat-17-step1_源码解读_模型训练和验证**
  - [B station](https://www.bilibili.com/video/BV1tr4y1d7GL)
- **DeepSpeed-Chat-18-step1_源码解读_模型保存-第1节**
  - [B station](https://www.bilibili.com/video/BV1AF41117HY)
- **DeepSpeed-Chat-19-step1_源码解读_模型保存-第2节**
  - [B station](https://www.bilibili.com/video/BV1Eh4y1S79Z)
- **DeepSpeed-Chat-20-step1_源码解读_模型保存-第3节**
  - [B station](https://www.bilibili.com/video/BV18h4y1S7Rn)
- **DeepSpeed-Chat-21-step1_源码解读_模型评估**
  - [B station](https://www.bilibili.com/video/BV1fZ421E7o9)
- **DeepSpeed-Chat-22-step1_源码解读_模型推理-第1节**
  - [B station](https://www.bilibili.com/video/BV1bm421p7GE)
- **DeepSpeed-Chat-23-step1_源码解读_模型推理-第2节**
  - [B station](https://www.bilibili.com/video/BV1yb421h7PB)
- **DeepSpeed-Chat-24-step1_源码解读_模型推理-第3节**
  - [B station](https://www.bilibili.com/video/BV1Xb421Y7ga)
- **DeepSpeed-Chat-25 Step-2-01 简介**
  - [B station](https://www.bilibili.com/video/BV1Dh4y1S7rG)
- **DeepSpeed-Chat-26 Step-2 Reward模型微调和评估**
  - [B station](https://www.bilibili.com/video/BV1z14y1i7hv)
- **Chat-27-step2-源码解读-参数配置和初始化**
  - [B station](https://www.bilibili.com/video/BV1y84y1m7VX)
- **Chat-28-step2-源码解读-创建Reward模型**
  - [B station](https://www.bilibili.com/video/BV1hN411t7pk)
- **Chat-29-step2-源码解读-创建数据集**
  - [B station](https://www.bilibili.com/video/BV14C4y1V7L4)
- **Chat-30-step2-源码解读-参数分组_创建学习率调度器**
  - [B station](https://www.bilibili.com/video/BV1P34y137FB)
- **Chat-31-step2-源码解读-deepspeed初始化**
  - [B station](https://www.bilibili.com/video/BV1Pm4y1G7yf)
- **Chat-32-step2-源码解读-模型评估定义**
  - [B station](https://www.bilibili.com/video/BV1P94y1a7T1)
- **Chat-33-step2-源码解读-Reward模型训练**
  - [B station](https://www.bilibili.com/video/BV1P8411y7EA)
- **Chat-34-step2-源码解读-Reward模型保存**
  - [B station](https://www.bilibili.com/video/BV1FV411c7Cf)
- **Chat-35-step2-源码解读-Reward模型评估**
  - [B station](https://www.bilibili.com/video/BV11H4y1f7X6)
- **Chat-36-step2-源码解读-forward算法-第1节**
  - [B station](https://www.bilibili.com/video/BV1v34y1V7jV)
- **Chat-37-step2-源码解读-forward算法-第2节**
  - [B station](https://www.bilibili.com/video/BV14H4y1f7EB)
- **Chat-38-step2-源码解读-forward算法-第3节**
  - [B station](https://www.bilibili.com/video/BV13m4y1G7mq)
- **Chat-39-step2-源码解读-forward算法-第4节**
  - [B station](https://www.bilibili.com/video/BV1RH4y1f7Dn)
- **方案1-CIFAR10-01-数据加载和预处理**
  - [B station](https://www.bilibili.com/video/BV1wx4y1r7nn)
- **方案1-CIFAR10-02-模型定义与超参数创建**
  - [B station](https://www.bilibili.com/video/BV1iC411n79w)
- **方案1-CIFAR10-03-模型训练和本地保存**
  - [B station](https://www.bilibili.com/video/BV1Jp421Q7Ar)
- **方案1-CIFAR10-04-模型性能验证**
  - [B station](https://www.bilibili.com/video/BV17z421r7nb)
- **方案1-CIFAR10-05-基于FastAPI实现推理服务**
  - [B station](https://www.bilibili.com/video/BV12z42167Qd)
- **方案2-CIFAR10-DeepSpeed-01-超参数定义**
  - [B station](https://www.bilibili.com/video/BV1Mt421A7Lj)
- **方案2-CIFAR10-DeepSpeed-02-模型结构定义**
  - [B station](https://www.bilibili.com/video/BV19w4m1275e)
- **方案2-CIFAR10-DeepSpeed-03-模型分布式训练**
  - [B station](https://www.bilibili.com/video/BV1u1421R78i)
- **方案2-CIFAR10-DeepSpeed-04-模型性能验证**
  - [B station](https://www.bilibili.com/video/BV1DH4y1A785)
- **方案2-CIFAR10-DeepSpeed-05-配置文件参数讲解**
  - [B station](https://www.bilibili.com/video/BV1dF4m1w7WQ)
- **方案2-CIFAR10-DeepSpeed-06-模型分布式训练**
  - [B station](https://www.bilibili.com/video/BV1tt421A7Pd)
- **OpenAI assistant API 学习指南-简介**
  - [B station](https://www.bilibili.com/video/BV1Wj411j7mn)
- **OpenAI assistant API 学习指南-assistant运行原理**
  - [B station](https://www.bilibili.com/video/BV1oN411777P)
- **LangChain 实战案例-01 基于上传的PDF文档进行QA问答 第1节 项目简介**
  - [B station](https://www.bilibili.com/video/BV1fp4y137US)
- **LangChain 实战案例-01 基于上传PDF文档进行QA问答 第2节 案例实现**
  - [B station](https://www.bilibili.com/video/BV1rk4y1g7Gd)
- **LangChain 教程 实战案例-01 基于上传PDF文档进行QA问答 第3节 向量数据库**
  - [B station](https://www.bilibili.com/video/BV1294y1C7Cd)
- **LangChain 实战案例-01 基于上传PDF文档进行QA问答 第4节 基于Gradio实现QA交互**
  - [B station](https://www.bilibili.com/video/BV1rN41187Q9)
- **Chinese LLaMA Alpaca 案例实战-01-项目概览**
  - [B station](https://www.bilibili.com/video/BV1Mh4y187ir)
- **Chinese- LLaMA- Alpaca 案例实战-02-指令数据生成**
  - [B station](https://www.bilibili.com/video/BV1ns4y1g717)
- **案例实战-03-Chinese-LLaMA-AIpaca模型本地部署**
  - [B station](https://www.bilibili.com/video/BV1xz4y18749)
- **案例实战-04-基于webUI进行交互**
  - [B station](https://www.bilibili.com/video/BV1im4y1h7wo)
- **案例实战-05-基于LLaMA和LoRA模型进行预训练**
  - [B station](https://www.bilibili.com/video/BV1f8411o73g)
- **案例实战-06-上集—基于LLaMA和LoRA模型进行指令精调**
  - [B station](https://www.bilibili.com/video/BV1eX4y187nN)
- **案例实战-07-下集-基于LLaMA和LoRA模型进行指令精调**
  - [B station](https://www.bilibili.com/video/BV1mP411D7bm)
- **案例实战-08-LLaMA与LangChain进行集成**
  - [B station](https://www.bilibili.com/video/BV1Ph4y137JW)
- **案例实战-09-剧透-使用 FastAPI 实现 LLaMA API服务**
  - [B station](https://www.bilibili.com/video/BV1vh4y1X7D6)
- **案例实战-10-LLaMA tokenizer模型与中文tokenizer模型合并操作**
  - [B station](https://www.bilibili.com/video/BV1hh4y1M7YE)
- **案例实战-11-单个LoRA权重与LLaMA合并**
  - [B station](https://www.bilibili.com/video/BV15h4y1M7MU)
- **案例实战-12-多个LoRA权重与LLaMA合并**
  - [B station](https://www.bilibili.com/video/BV1KV4y117ci)
- **案例实战-13-指令精调手把手教程-升级版**
  - [B station](https://www.bilibili.com/video/BV1Qu411t7ML)
- **案例实战-14-基于llama.cpp量化模型部署**
  - [B station](https://www.bilibili.com/video/BV1Y14y1d75g)
- **案例实战-15-使用 privateGPT 进行多文档问答**
  - [B station](https://www.bilibili.com/video/BV1Wm4y1Y7G3)
- **案例实战-16-llama.cpp量化模型GPU加速推理**
  - [B station](https://www.bilibili.com/video/BV1314y1o7dS)
- **案例实战-17-llama.cpp量化模型API服务部署**
  - [B station](https://www.bilibili.com/video/BV1kz4y1E7ha)
- **源码讲解-01-中文词汇表扩充**
  - [B station](https://www.bilibili.com/video/BV1Es4y1g7uu)
- **源码讲解-02-llama与lora模型合并**
  - [B station](https://www.bilibili.com/video/BV1rX4y187Wb)
- **源码讲解-03-基于llama模型进行推理**
  - [B station](https://www.bilibili.com/video/BV1a24y1K79a)
- **源码讲解-04-上集-模型预训练代码逐行剖析**
  - [B station](https://www.bilibili.com/video/BV18X4y187ss)
- **源码讲解-05-中集-模型预训练代码逐行剖析**
  - [B station](https://www.bilibili.com/video/BV1wo4y1g7DF)
- **源码讲解-06-下集-模型预训练代码逐行剖析**
  - [B station](https://www.bilibili.com/video/BV1S8411o78y)
- **源码讲解-07-上集-API服务server代码讲解**
  - [B station](https://www.bilibili.com/video/BV1N14y1D7eT)
- **源码讲解-08-下集-API服务server代码讲解**
  - [B station](https://www.bilibili.com/video/BV13k4y1H7Ck)
- **01_模型推理与部署专题简介**
  - [B station](https://www.bilibili.com/video/BV1HY411r7fc)
- **02_TensorRT与Triton容器部署**
  - [B station](https://www.bilibili.com/video/BV1h24y1n7ws)
- **03_TensorFlow模型转换TensorRT引擎推理**
  - [B station](https://www.bilibili.com/video/BV1124y1b7Le)
- **04_Pytorch模型转换为TensorRT引擎推理**
  - [B station](https://www.bilibili.com/video/BV1yg4y1t71M)
- **05_tensorflow_serving_模型部署与推理_mnist分类案例**
  - [B station](https://www.bilibili.com/video/BV1iT411a7GU)
- **06_tensorflow_serving_单个模型部署与推理_线性回归**
  - [B station](https://www.bilibili.com/video/BV1WY411B7Yh)
- **07_tensorflow_serving_多个模型部署与推理_模型迭代**
  - [B station](https://www.bilibili.com/video/BV1x54y1M7Es)
- **08_torch_serving_docker环境部署**
  - [B station](https://www.bilibili.com/video/BV19N411N73R)
- **09_torch_serving_案例1-序列分类**
  - [B station](https://www.bilibili.com/video/BV18g4y1W7BD)
- **10_torch_serving_案例2-QA问答**
  - [B station](https://www.bilibili.com/video/BV1vN411K7Bf)
- **轻松学·Streamlit_01_专题简介**
  - [B station](https://www.bilibili.com/video/BV1EY4y1Z7No)
- **轻松学·Streamlit_02_基础功能探索**
  - [B station](https://www.bilibili.com/video/BV1Q3411Z76n)
- **轻松学·Streamlit_03_基础功能探索**
  - [B station](https://www.bilibili.com/video/BV1624y1h78E)
- **轻松学·Streamlit_04_基础功能探索**
  - [B station](https://www.bilibili.com/video/BV1jv4y117zn)
- **轻松学·Streamlit_05_基础功能探索**
  - [B station](https://www.bilibili.com/video/BV16G4y1w7td)
- **轻松学·Streamlit_06_基础功能探索**
  - [B station](https://www.bilibili.com/video/BV1s3411d7QA)
- **轻松学·Streamlit_07_动物图片识别 APP**
  - [B station](https://www.bilibili.com/video/BV1Cx4y137xK)
- **轻松学·Streamlit_08_音频转文本 APP**
  - [B station](https://www.bilibili.com/video/BV1z14y1M7J1)
- **轻松学·Streamlit_09_ML分类案例 APP**
  - [B station](https://www.bilibili.com/video/BV1g24y1h7FK)
- **01_ES 概念、核心理论部分**
  - [B station](https://www.bilibili.com/video/BV1Ta411q73R)
- **02_ES 基础操作快速入门**
  - [B station](https://www.bilibili.com/video/BV1S5411U754)
- **03_ES python API基础操作入门**
  - [B station](https://www.bilibili.com/video/BV1hY411E7iA)
- **04_ES 文本相似性计算**
  - [B station](https://www.bilibili.com/video/BV1uZ4y127Lv)
- **进阶学·ES-02-01 理论知识**
  - [B station](https://www.bilibili.com/video/BV1Dd4y1i7qW)
- **进阶学·ES-02-02 理论知识**
  - [B station](https://www.bilibili.com/video/BV1de4y1U7JZ)
- **进阶学·ES-03-01 索引操作**
  - [B station](https://www.bilibili.com/video/BV1J14y177sH)
- **进阶学·ES-03-02 映射操作-1**
  - [B station](https://www.bilibili.com/video/BV1dt4y1c7Be)
- **进阶学·ES-03-02 映射操作-2**
  - [B station](https://www.bilibili.com/video/BV19D4y1k7uw)
- **进阶学·ES-03-02 映射操作-3**
  - [B station](https://www.bilibili.com/video/BV1Ee4y1q7oT)
- **进阶学·ES-03-02 映射操作-4**
  - [B station](https://www.bilibili.com/video/BV1Y8411W7o2)
- **进阶学·ES-03-03 文档操作**
  - [B station](https://www.bilibili.com/video/BV1J8411W7f6)
- **进阶学ES 03-04 ES基于python API实践-1**
  - [B station](https://www.bilibili.com/video/BV1Ce4y1q7Ne)
- **进阶学ES 03-04 ES基于python API实践-2**
  - [B station](https://www.bilibili.com/video/BV12d4y1i7QU)
- **进阶学·ES-04-01 analyzer简介**
  - [B station](https://www.bilibili.com/video/BV1SV4y1L77u)
- **进阶学·ES-04-02 analyzer应用**
  - [B station](https://www.bilibili.com/video/BV1g84y1z7SM)
- **进阶学·ES-04-03 analyzer IK分词器-自定义词典**
  - [B station](https://www.bilibili.com/video/BV16N4y1c7VW)
- **进阶学·ES-04-04 analyzer IK分词器-同义词-上集**
  - [B station](https://www.bilibili.com/video/BV1qe411L7SJ)
- **进阶学·ES-04-05 analyzer IK分词器-同义词-下集**
  - [B station](https://www.bilibili.com/video/BV1mG4y1p75R)
- **进阶学·ES-04-06 analyzer IK分词器-停用词**
  - [B station](https://www.bilibili.com/video/BV1i14y177tV)
- **进阶学·ES-04-07 analyzer IK分词器-拼音搜索**
  - [B station](https://www.bilibili.com/video/BV1BK411Q7YP)
- **进阶学·ES-04-08 ES辅助功能**
  - [B station](https://www.bilibili.com/video/BV1Ee4y1i77Q)
- **进阶学·ES-04-09 ES布尔查询**
  - [B station](https://www.bilibili.com/video/BV1ZW4y1J77a)
- **进阶学·ES-04-10 ES全文搜索**
  - [B station](https://www.bilibili.com/video/BV17e411V7ec)
- **进阶学·ES-04-11 ES搜索排序**
  - [B station](https://www.bilibili.com/video/BV19V4y1V7ge)
- **mysql_01_课程简介**
  - [B station](https://www.bilibili.com/video/BV1e14y187iC)
- **mysql_02_基本操作**
  - [B station](https://www.bilibili.com/video/BV13t4y1A7HN)
- **mysql_03_数据表的增删改**
  - [B station](https://www.bilibili.com/video/BV1TV4y1K7S6)
- **mysql_04_01_数据查询**
  - [B station](https://www.bilibili.com/video/BV15T411P7rC)
- **mysql_04_02_数据查询**
  - [B station](https://www.bilibili.com/video/BV13e411j7M6)
- **mysql_05_01_存储过程**
  - [B station](https://www.bilibili.com/video/BV1eG4y1W7H5)
- **mysql_05_02_存储过程**
  - [B station](https://www.bilibili.com/video/BV1Te4y1z78C)
- **mysql_06_01_索引**
  - [B station](https://www.bilibili.com/video/BV1NN4y1N7Mc)
- **mysql_06_02 索引**
  - [B station](https://www.bilibili.com/video/BV1fV4y1N7eV)
- **mysql_07_python与mysql教程**
  - [B station](https://www.bilibili.com/video/BV17G411n7q6)
- **mysql_08_pandas与mysql教程**
  - [B station](https://www.bilibili.com/video/BV1kG4y1W7J7)
- **自然语言处理快速入门 01-BERT及其变种的原理**
  - [B station](https://www.bilibili.com/video/BV1RP4y1t7sc)
- **02-BERT及其变种的原理**
  - [B station](https://www.bilibili.com/video/BV1d44y1x7tP)
- **03-BERT及其变种的原理**
  - [B station](https://www.bilibili.com/video/BV12r4y1y7PS)
- **04-BERT及其变种的原理**
  - [B station](https://www.bilibili.com/video/BV19F411Y7ER)
- **05-BERT及其变种的原理**
  - [B station](https://www.bilibili.com/video/BV1zr4y1y72v)
- **06-BERT入门二分类案例 自然语言处理快速入门**
  - [B station](https://www.bilibili.com/video/BV1SP4y137Pp)
- **07-基于RoBERTa训练一个MLM掩码语言模型**
  - [B station](https://www.bilibili.com/video/BV1gF411z78D)
- **08_一_基于BiLSTM和BERT实现分类任务**
  - [B station](https://www.bilibili.com/video/BV1wb4y1i7hU)
- **09_二_基于BiLSTM和BERT实现分类任务**
  - [B station](https://www.bilibili.com/video/BV1uR4y137JG)
- **10_三_基于BiLSTM和BERT实现分类任务**
  - [B station](https://www.bilibili.com/video/BV1UP4y1J7yr)
- **11_四_基于BiLSTM和BERT实现分类任务**
  - [B station](https://www.bilibili.com/video/BV17q4y117YB)
- **01_TensorFlow 2.0 分类案例【银行客户流失预测】官网+个人实现**
  - [B station](https://www.bilibili.com/video/BV1f44y1z7XF)
- **02_TensorFlow 2.0 鲜花分类 官网案例详解 + 优化**
  - [B station](https://www.bilibili.com/video/BV1cf4y187PE)
- **03_TensorFlow 2.0 迁移学习_案例1_基于预训练模型进行目标分类**
  - [B station](https://www.bilibili.com/video/BV1oB4y1T7qL)
- **04-1_TensorFlow 2.0 迁移学习_案例2_上集_宠物狗品种识别**
  - [B station](https://www.bilibili.com/video/BV1b44y167ca)
- **04-2_TensorFlow 2.0 迁移学习_案例2_下集_宠物狗品种识别**
  - [B station](https://www.bilibili.com/video/BV19B4y1T7eP)
- **05_TensorFlow 2.0 回归案例 葡萄酒品质预测**
  - [B station](https://www.bilibili.com/video/BV1F64y1r7Ub)
- **06_TensorFlow 2.0 基于LSTM进行文本生成（字符级）**
  - [B station](https://www.bilibili.com/video/BV1ko4y1k7Lo)
- **07_TensorFlow 2.0 基于LSTM单变量预测_电力消耗案例**
  - [B station](https://www.bilibili.com/video/BV1f5411K7qD)
- **08_TensorFlow 2.0 基于LSTM多变量_共享单车使用量预测**
  - [B station](https://www.bilibili.com/video/BV1y5411K7NR)
- **09_基于Embedding进行IMDB情感文本分类（上集）**
  - [B station](https://www.bilibili.com/video/BV19y4y1M7p5)
- **09_基于Embedding进行IMDB情感文本分类（下集）**
  - [B station](https://www.bilibili.com/video/BV1X64y197KS)
- **10-01 OCR入门案例_手写字体识别**
  - [B station](https://www.bilibili.com/video/BV1tX4y1w751)
- **10-02 OCR入门案例_手写字体识别**
  - [B station](https://www.bilibili.com/video/BV1EB4y1N7oz)
- **10-03 OCR入门案例_手写字体识别**
  - [B station](https://www.bilibili.com/video/BV1oh411h7oy)
- **11_01 OCR 图片去噪**
  - [B station](https://www.bilibili.com/video/BV1H54y1E7yv)
- **11_02 OCR 图片去噪**
  - [B station](https://www.bilibili.com/video/BV1TX4y1A7fN)
- **11_03 OCR 图片去噪**
  - [B station](https://www.bilibili.com/video/BV1Tf4y1j7PU)
- **11_04 OCR 图片去噪**
  - [B station](https://www.bilibili.com/video/BV1L64y1z7yV)
- **11_05 OCR 图片去噪**
  - [B station](https://www.bilibili.com/video/BV1bb4y1k75f)
- **12_TensorFlow 2.0 多分类案例 CIFAR10【官网 + 个人实现】**
  - [B station](https://www.bilibili.com/video/BV1UK4y1X7dM)
- **01_轻松学Python_python语言简介和工具安装**
  - [B station](https://www.bilibili.com/video/BV1Pg4y1q7BZ)
- **02 轻松学python 变量**
  - [B station](https://www.bilibili.com/video/BV1Qi4y1s7EW)
- **03 轻松学python 数字类型**
  - [B station](https://www.bilibili.com/video/BV1CT4y1E7fE)
- **04 轻松学python 运算符**
  - [B station](https://www.bilibili.com/video/BV1854y1Q7ai)
- **05 轻松学python 字符串**
  - [B station](https://www.bilibili.com/video/BV1vz411i726)
- **06 轻松学python 列表**
  - [B station](https://www.bilibili.com/video/BV1vz4y197hL)
- **07 轻松学python 元组**
  - [B station](https://www.bilibili.com/video/BV1xV411r7Gu)
- **08 轻松学python 字典**
  - [B station](https://www.bilibili.com/video/BV1ki4y1s7TG)
- **09 轻松学python 集合**
  - [B station](https://www.bilibili.com/video/BV1Lv41167zH)
- **10 轻松学python if条件判断语句**
  - [B station](https://www.bilibili.com/video/BV16z411i7iY)
- **11 轻松学python while循环语句**
  - [B station](https://www.bilibili.com/video/BV1RK4y1x7CQ)
- **12 轻松学python for循环语句**
  - [B station](https://www.bilibili.com/video/BV1ET4y1J7GV)
- **13 轻松学python 迭代器**
  - [B station](https://www.bilibili.com/video/BV11Z4y1H7zU)
- **14 轻松学 python range zip enumerate 内置函数**
  - [B station](https://www.bilibili.com/video/BV1NK411W72q)
- **15 轻松学 python 列表推导**
  - [B station](https://www.bilibili.com/video/BV1zz4y1Q7zo)
- **16-1 轻松学 Python 类 ( 第一节 )**
  - [B station](https://www.bilibili.com/video/BV1qK4y1478J)
- **16-2 轻松学 Python 类 继承 多态 ( 第二节 )**
  - [B station](https://www.bilibili.com/video/BV1Tz4y1X72S)
- **16-3 轻松学 Python 类 运算符重载 ( 第三节 )**
  - [B station](https://www.bilibili.com/video/BV1wf4y1R7tw)
- **01_轻松学OpenCV_简介**
  - [B station](https://www.bilibili.com/video/BV1Ji4y1x7vJ)
- **02_轻松学OpenCV_图像基础**
  - [B station](https://www.bilibili.com/video/BV1eg4y1i7P6)
- **03 轻松学 OpenCV argparse模块**
  - [B station](https://www.bilibili.com/video/BV1fK411H7bf)
- **04 轻松学 OpenCV 读取图片**
  - [B station](https://www.bilibili.com/video/BV1uT4y1J7iV)
- **05 轻松学 OpenCV 读取_处理_保存图片**
  - [B station](https://www.bilibili.com/video/BV1St4y1X7Lq)
- **06 轻松学 OpenCV 从摄像头读取视频**
  - [B station](https://www.bilibili.com/video/BV1gg4y1v7jt)
- **07 轻松学 OpenCV 从视频文件读取内容**
  - [B station](https://www.bilibili.com/video/BV19Z4y1H7GH)
- **08 轻松学OpenCV 保存摄像头读取到的视频内容**
  - [B station](https://www.bilibili.com/video/BV1EV411k78q)
- **09 轻松学OpenCV 图像的8种变换**
  - [B station](https://www.bilibili.com/video/BV1oK4y1x7PH)
- **10 轻松学 OpenCV 灰度直方图**
  - [B station](https://www.bilibili.com/video/BV14i4y1x797)
- **11 轻松学 OpenCV 灰度直方图 ( 补充知识点 )**
  - [B station](https://www.bilibili.com/video/BV1dK411p7cu)
- **12 轻松学 OpenCV mask**
  - [B station](https://www.bilibili.com/video/BV1EZ4y1H7bB)
- **13 轻松学 OpenCV 彩色直方图**
  - [B station](https://www.bilibili.com/video/BV17k4y1z7L3)
- **14 轻松学 OpenCV 画出基本图形**
  - [B station](https://www.bilibili.com/video/BV1xK4y147Mk)
- **15 轻松学 OpenCV 图片上显示文本**
  - [B station](https://www.bilibili.com/video/BV1DD4y1D7Hw)
- **16 轻松学 OpenCV 人脸检测基于Haar级联**
  - [B station](https://www.bilibili.com/video/BV18z411e7VJ)
- **17-1 轻松学 OpenCV 基于dlib在图片上进行人脸检测**
  - [B station](https://www.bilibili.com/video/BV1PK411W7pF)
- **17-2 轻松学 OpenCV 基于dlib通过摄像头进行实时人脸检测**
  - [B station](https://www.bilibili.com/video/BV11Z4y1H7aS)
- **18-1 轻松学 OpenCV  基于dlib进行人脸关键点检测( 图片 )**
  - [B station](https://www.bilibili.com/video/BV1Bk4y1z7rE)
- **18-2 轻松学OpenCV 基于dlib进行人脸关键点检测 (摄像头)**
  - [B station](https://www.bilibili.com/video/BV19A411v7QS)
- **18-3 轻松学OpenCV 基于face_recognition进行人脸关键点检测**
  - [B station](https://www.bilibili.com/video/BV1ez4y1Q7sD)
- **19-1 轻松学OpenCV 基于dlib进行人脸跟踪**
  - [B station](https://www.bilibili.com/video/BV1pK4y147Fj)
- **19-2 轻松学OpenCV 基于dlib进行人脸跟踪(补充)**
  - [B station](https://www.bilibili.com/video/BV1Pz4y1R7iB)
- **19-3 轻松学OpenCV 基于dlib进行目标跟踪**
  - [B station](https://www.bilibili.com/video/BV1cv411B7yN)
- **20-1 轻松学OpenCV 基于dlib进行人脸识别( 图片检测 ）**
  - [B station](https://www.bilibili.com/video/BV1DZ4y1H7RM)
- **20-2 轻松学OpenCV 基于face_recognition进行人脸识别 ( 摄像头 )**
  - [B station](https://www.bilibili.com/video/BV1h5411Y7d8)
- **【极速入门】DeepSeek Harness上手实战指南！架构原理、项目实操、插件开发全栈精讲！赠全套知识库、Skills、桌面端应用与插件管理器！**
  - [B station](https://www.bilibili.com/video/BV1tTbk6zE4C)
- **从零手搓工业级知识库！DeepSeek Harness智能体开发实战！Skills+插件+Agent预设全栈精讲，Agent设计、开发、部署、优化全流程实操！**
  - [B station](https://www.bilibili.com/video/BV1Hf8A6sEbN)
- **用好插件，性能暴涨！多Agent系统+永久记忆+提示优化+OpenDesign+TUI等，10大必装插件助你的DeepSeek Harness如虎添翼！**
  - [B station](https://www.bilibili.com/video/BV1eU836PEkF)
- **桌面端+插件商店+视觉增强，DeepSeek Harness Studio开源上线！一键选配管理插件，原生视觉能力增强，自动版本更新，0代码彻底掌控DSH！**
  - [B station](https://www.bilibili.com/video/BV19Hb16dExu)
- **DeepSeek Harness上手流程+入门导读！国产版Codex&Claude Code重磅开源！**
  - [B station](https://www.bilibili.com/video/BV1P9gs6zEpz)
- **保姆级DeepSeek Harness部署与上手指南！DeepSeek版Codex&Claude Code，DSH完整部署&使用&调用&开发流程详解！**
  - [B station](https://www.bilibili.com/video/BV1hfgW6jEVr)
- **架构解读+部署上手+插件使用，DeepSeek Harness全方位深度解析！基座性能持平Codex，高度灵活插件系统定义下一代Agent开发范式！**
  - [B station](https://www.bilibili.com/video/BV1Lyuf6SETd)
- **效率翻倍，效果追平！DeepSeek Harness VS Codex，Agent性能全方位深度对比评测！**
  - [B station](https://www.bilibili.com/video/BV1gduf6GEbZ)
- **0代码+配视觉！DeepSeek Harness桌面版安装使用，自带视觉增强与背景切换，保姆级上手使用流程详解！**
  - [B station](https://www.bilibili.com/video/BV1aPgK6cEgj)
- **顶级体验！DeepSeek V4 Vision多模态模型介绍与效果实测！DeepSeek V4-Flash-Vision-Exp重磅发布！**
  - [B station](https://www.bilibili.com/video/BV1sh8i6XE49)
- **Token自由！单卡5090部署满血DeepSeek V4 Flash！32G显存运行Opus 4.8级大模型，FreeToken项目CPU+GPU混合推实战！**
  - [B station](https://www.bilibili.com/video/BV1BuhG6CEjD)
- **DeepSeek-V4-Pro正式版深度评测！11项工业场景全方位测评，Agentic Coding、前端审美、物理理解、Agent开发全面追平Fable 5！**
  - [B station](https://www.bilibili.com/video/BV1Q2g76cENE)
- **DeepSeek-V4-Pro正式版接Codex配视觉能力！0代码0网络门槛，Codex App、CLI双端环境实现，多隔离环境切换与配置管理，FF-Codex**
  - [B station](https://www.bilibili.com/video/BV1vegL6hEtA)
- **性能评测+上手解读！DeepSeek-V4-Pro开源新王，Agentic coding&推理&长程工具调用全面硬刚Fable 5！**
  - [B station](https://www.bilibili.com/video/BV1bSgL6nEwR)
- **DeepSeek Harness工作流分享！精美前端开发、AI PPT&视频制作实用工作流实践，Agent预设Preset上手进阶实战！**
  - [B station](https://www.bilibili.com/video/BV1b68d6EEhG)
- **【面试八股】大模型微调与RAG该如何选？面试满分回答模板+底层原理精讲，直接背！秋招求职必备！**
  - [B station](https://www.bilibili.com/video/BV12bYszLEY5)
- **【面试八股】如何估算大模型微调所需硬件？一个公式搞定！附面试满分答案模板 | MOE架构模型 | 微调预算有限如何分配资源**
  - [B station](https://www.bilibili.com/video/BV19WeAzAEPJ)
- **【面试八股】PPO与GRPO算法原理对比分析，大模型强化学习微调必考，2步做出满分答卷，拿下高薪offer！ | 强化学习算法原理 | 高效微调算法原理**
  - [B station](https://www.bilibili.com/video/BV1MGeVzHEB4)
- **【面试八股】如何进行多机多卡大模型微调？分布式训练满分答卷，让你的offer率提升80%！ | DeepSpeed | PyTorch Distributed**
  - [B station](https://www.bilibili.com/video/BV1xCY9zbE6b)
- **【面试八股】如何进行大模型多模态微调？10+算法工程经验分享，你也能写出满分答案！ | LoRA | QLoRA | 高效微调**
  - [B station](https://www.bilibili.com/video/BV1hdebzTE3g)
- **【面试八股】专业领域微调数据集如何准备？11步工程化构建环节，适配面试 & 企业项目落地！| 数据预处理 | 微调效果评估**
  - [B station](https://www.bilibili.com/video/BV1RmebzkEyV)
- **【面试八股】如何评估大模型微调效果？人工+自动化评估，面试官听完点头的企业级评估方案！ | 构建模型评估数据集 | EvalScope自动构建数据集**
  - [B station](https://www.bilibili.com/video/BV1h5ebzKEbA)
- **【面试八股】Qwen3的GSPO算法原理是什么？国产T0大模型核心技术精讲，0基础也能手撕前沿算法 | GRPO VS GSPO | PPO长度归一化**
  - [B station](https://www.bilibili.com/video/BV1tNh1zvEnX)
- **【面试八股】如何通过微调提升Agent性能？Claude Code也在用的技术思路，自动化生成最优工具调用策略 | 指令微调 | 强化学习 | 奖励函数设计**
  - [B station](https://www.bilibili.com/video/BV1ChhyzZEDv)
- **真神还是造假？GPT-5 VS Claude 4.1编程性能对比评测！全网首发GPT-5工业级实战性能评测，代码能力&Agent性能全方位深度测评！**
  - [B station](https://www.bilibili.com/video/BV1kLtmzREMr)
- **GPT-5深度解读与性能评测！编程&Agent性能全面超越Claude 4.1？实测&揭秘地表最强大模型核心功能特性！**
  - [B station](https://www.bilibili.com/video/BV18YtCzoEue)
- **GPT-5发布会4分钟速览！定价、性能…一次看完！GPT-5你需要知道的都在这了**
  - [B station](https://www.bilibili.com/video/BV1ggtkz9EKs)
- **LangGraph&LangChain智能体开发极速入门！前端对话+NL2SQL+Python代码解释器，前后端分离部署+运行状态实时追踪全流程实战！**
  - [B station](https://www.bilibili.com/video/BV1Nx38zMEyi)
- **工业级智能体开发实践，LangChain从零入门与智能体开发实战！RAG知识库检索、MCP智能体开发、数据分析智能体搭建全领域实战！从零学会LangChain！**
  - [B station](https://www.bilibili.com/video/BV1pYKgzAE5C)
- **超越LangChain！LangGraph快速入门与智能体开发实战！工业级智能体开发、部署、运维、前端对话全流程实践，NL2SQL、Python代码解释器开发！**
  - [B station](https://www.bilibili.com/video/BV1Kx3CzyE6Q)
- **最热门智能体开发技术栈，最低零代码开发企业级Agent！LangChain&LangGraph+MCP技术实战，双向MCP接入与封装双向开发实践！**
  - [B station](https://www.bilibili.com/video/BV1bzMdzkERM)
- **MCP技术开发入门实战！DeepSeek、ollama、vLLM接入MCP，从零手撕代码搭建MCP Client与Server！MCP完整技术实战！**
  - [B station](https://www.bilibili.com/video/BV1NLXCYTEbj)
- **MCP企业级智能体开发实战！知识库问答系统+AI数据分析智能体项目实战！独家提供MCP常用工作流+通用开发模版+外部工具调用优化函数**
  - [B station](https://www.bilibili.com/video/BV1n1ZuYjEzf)
- **零门槛接入MCP！Cursor、阿里云百炼、Open-WebUI、Cherry Studio接入10大最热门MCP工具实战流程！零门槛搭建专属智能体应用！**
  - [B station](https://www.bilibili.com/video/BV1dCo7YdEgK)
- **DeepSeek v3本地部署与调用实战｜vLLM、SGLang、LMDeploy+DeepSeek v3部署调用实战**
  - [B station](https://www.bilibili.com/video/BV1jjwVe4EKn)
- **DeepSeek-v3调用指南与Function calling技术实战｜DeepSeek v3模型参数详解与Tool Use功能实战**
  - [B station](https://www.bilibili.com/video/BV1JuwVewELc)
- **【全网独家】手动复现DeepSeek v3！从零训练Mini DeepSeek v3！模型预训练+全量指令微调+DPO强化学习微调全流程实战**
  - [B station](https://www.bilibili.com/video/BV1KtwueYE54)
- **DeepSeek v3搭建Multi-Agent技术入门实战｜DeepSeek v3+OpenAI Swarm技术实战**
  - [B station](https://www.bilibili.com/video/BV1T8czeSEf1)
- **DeepSeek v3+GraphRAG技术实战｜DeepSeek v3知识图谱检索增强技术实战**
  - [B station](https://www.bilibili.com/video/BV1Xwc6eoEW5)
- **【保姆级】DeepSeek R1本地部署与调用指南｜transformer、Ollama、vLLM、LMDeploy、SGLang部署与调用R1与蒸馏模型组**
  - [B station](https://www.bilibili.com/video/BV19kFoe6Ef7)
- **DeepSeek R1 API调用实战！DeepSeek R1模型参数详解与模型功能介绍｜自动编程、自动机器学习项目入门实战**
  - [B station](https://www.bilibili.com/video/BV1UyfGYqE28)
- **借助DeepSeek R1进行模型蒸馏，模型蒸馏入门实战！从零训练DeepSeek R1 Distill模型｜模型蒸馏技术实战**
  - [B station](https://www.bilibili.com/video/BV1X1FoeBEgW)
- **【最佳方案】DeepSeek R1搭建本地知识库问答系统｜DeepSeek+Ollama+RAG本地知识库问答实战｜AnythingLLM快速部署与应用实战**
  - [B station](https://www.bilibili.com/video/BV12qF2ePEDa)
- **新年巨献！DeepSeek Janus Pro重磅开源！文生图+图像识别，统一多模态大模型奠基之作！超越DALL-E 3、SD3 Medium**
  - [B station](https://www.bilibili.com/video/BV15kFseHEQ5)
- **DeepSeek新年巨献！Janus Pro本地部署与调用实战！图像识别+文生图统一多模态大模型本地部署与调用流程详解！**
  - [B station](https://www.bilibili.com/video/BV1ZqFse9Egc)
- **【全网独家】训练定制化DeepSeek R1！零基础DeepSeek R1高效微调实战｜知识灌注+对话风格微调，推理模型+Cot数据集微调实战！**
  - [B station](https://www.bilibili.com/video/BV1YjN8eGE1H)
- **【全网最强】DeepSeek R1论文逐段精读与训练流程代码复现｜R1强化学习训练流程详解、模型蒸馏方法介绍｜GRPO原理介绍与代码复现**
  - [B station](https://www.bilibili.com/video/BV1n9NfezErB)
- **联网+本地知识问答+外部工具调用+代码解释器+多用户并发+多模型切换，DeepSeek+Open-WebUI终极部署指南！**
  - [B station](https://www.bilibili.com/video/BV1qU9AYLEe3)
- **最低0显存，独家Unsloth动态量化部署满血DeepSeek｜纯CPU推理、CPU+GPU混合推理、纯GPU推理方案详解｜企业级最佳部署方案**
  - [B station](https://www.bilibili.com/video/BV1oePLezEZD)
- **【全网独家】训练定制化DeepSeek R1！零基础DeepSeek R1高效微调实战｜知识灌注+对话风格微调，推理模型+Cot数据集微调实战！**
  - [B station](https://www.bilibili.com/video/BV1f8Are5Enz)
- **独家KTransformers技术实战，手把手跑通4090运行DeepSeek满血版，独家FastAPI脚本编写&Open-WebUI结合方案深度讲解**
  - [B station](https://www.bilibili.com/video/BV1kyAke9EBA)
- **DeepSeek正式发布DualPipe，梁文峰亲自带队研发神级双向管道并行算加速，毫秒级榨干GPU性能！**
  - [B station](https://www.bilibili.com/video/BV1Gj9AYMEki)
- **DeepSeek重磅开源DeepGEMM矩阵加速库，全球唯一FP8超级矩阵加速器！2.7倍提升矩阵乘法计算效率！**
  - [B station](https://www.bilibili.com/video/BV1KJP7eZE2F)
- **DeepSeek重磅开源DeepEP，大模型训练&推理效率暴涨！粉碎算力垄断，重塑MoE模型训练新范式！**
  - [B station](https://www.bilibili.com/video/BV1LXPYeHEwB)
- **不负众望，Deepseek又开源封神！FlashMLA推理速度怒飙3倍！工业级加速库改写vLLM、SGLang技术规范**
  - [B station](https://www.bilibili.com/video/BV1jdPxeKEPV)
- **DeepSeek开源周压轴发布3FS，全球唯一大模型分布式文件管理系统，6TiB/s巨量吞吐性能，开辟训练新篇章！**
  - [B station](https://www.bilibili.com/video/BV1Xh93YfEV1)
- **比肩o1！DeepSeek R1全面解析！价格比OpenAI o1便宜50倍！ | 1.5B小模型代码能力赶超GPT4o | 小尺寸推理模型企业可本地部署**
  - [B station](https://www.bilibili.com/video/BV1UBwbe4E1D)
- **【深度】DeepSeek v3性能评测与技术解析｜DeepSeek v3为何是技术人首选模型｜颠覆当前大模型技术格局**
  - [B station](https://www.bilibili.com/video/BV18Ccie5Esy)
- **2025大模型最强求职指南！整理全网2万份JD，一手数据信息揭秘求职真相！**
  - [B station](https://www.bilibili.com/video/BV18JreYpE5Q)
- **【深度】2024大模型年度总结与2025技术展望！Agent智能体迎来全面爆发，大模型技术“黄金十年”即将到来！**
  - [B station](https://www.bilibili.com/video/BV1Xn6nYnEnr)
- **不止会解数学题！OpenAI o3即将开启AGI新时代！详解o3的现实应用与深远影响**
  - [B station](https://www.bilibili.com/video/BV1abCaYxEpp)
- **OpenAI发布会总结与深度解读：AGI之路天堑变通途！**
  - [B station](https://www.bilibili.com/video/BV1YZCNYDEzt)
- **AI视频生成终极之战！谷歌Veo 2正面硬刚OpenAI Sora！**
  - [B station](https://www.bilibili.com/video/BV1YVkMYsEq5)
- **万元服务器运行满血DeepSeek！全网最全低成本部署方案+硬件采购避坑指南！KTransformers方案+Unsloth动态量化方案详解！**
  - [B station](https://www.bilibili.com/video/BV1K7ACewEfM)
- **零基础揭秘DeepSeek R1训练流程｜全网首发万字拆解R1复现流程｜多阶段GRPO强化学习训练、模型蒸馏技术揭秘！**
  - [B station](https://www.bilibili.com/video/BV1ESAMepE4K)
- **OpenAI年度发布会Day 1解读：o1满血版、o1 pro mode与ChatGPT Pro新品解读！**
  - [B station](https://www.bilibili.com/video/BV1ufiYYuEpT)
- **OpenAI年度发布会Day 1完整回放与实时解读！｜o1、o1Pro、ChatGPT Pro重磅发布！｜三位UP深夜团建解读发布会**
  - [B station](https://www.bilibili.com/video/BV1GXiYYVEGa)
- **OpenAI年度发布会前瞻解读，GPT5、Sora、Agent工具会发布么？**
  - [B station](https://www.bilibili.com/video/BV1PuieYaEjT)
- **OpenAI年度发布会Day2解读：强化学习微调与定制化o1模型震撼登场！开启Agent开发新时代！奥特曼：今年最大惊喜！**
  - [B station](https://www.bilibili.com/video/BV1joirYkEB8)
- **OpenAI发布会Day 2发布会完整回放与深度解读｜强化学习API震撼登场，定制化o1模型人人可得，Agent开发一夜变天！Sam：今年最大惊喜！**
  - [B station](https://www.bilibili.com/video/BV1yfi6YHEQ4)
- **OpenAI年度发布会一阶段汇总：o1 Pro、ChatGPT Pro、强化学习API新品解读【合集】**
  - [B station](https://www.bilibili.com/video/BV1GAq5YZEeA)
- **Sora来了！今日最新宣传片《合成青春》速览与解读！｜百人热舞+实体一致+物理遵循+专业运镜，Sora王者归来！**
  - [B station](https://www.bilibili.com/video/BV1AjqHYAESa)
- **OpenAI年度重磅！o1大模型快速入门与开发实战！｜o1 API调用流程、推理与上下文管理、自动编程与实体识别开发实战！**
  - [B station](https://www.bilibili.com/video/BV1zWqHY4EjE)
- **Sora重磅发布！无限时长一致+任意帧修改+物理遵循！OpenAI发布会Day 3深度解读！**
  - [B station](https://www.bilibili.com/video/BV18EquYGEfo)
- **Sora今日重磅上线！发布会完整解读、Sora演示与功能详解！**
  - [B station](https://www.bilibili.com/video/BV1shquYPEds)
- **Sora功能及价格全解！Sora今日重磅发布，再次颠覆多模态领域，不负期待！**
  - [B station](https://www.bilibili.com/video/BV1rRqMYZERK)
- **在线Cursor来了！新版Canvas功能深度解读！ChatGPT在线文本&代码智能编辑器现已上线！**
  - [B station](https://www.bilibili.com/video/BV1dYqyYUEVT)
- **OpenAI Day 4发布会实况回放与深度解读！在线Cursor来了，新版Canvas重磅上线！**
  - [B station](https://www.bilibili.com/video/BV1FpqyY4Eew)
- **ChatGPT Canvas智能编程与智能文本编辑完整功能演示！OpenAI发布会Day 4，新版ChatGPT Canvas重磅上线！**
  - [B station](https://www.bilibili.com/video/BV1B1qCYQEcK)
- **OpenAI Day 7深度解读，ChatGPT Projects功能来袭，文本&代码生产力迎来重大突破！**
  - [B station](https://www.bilibili.com/video/BV1TfB3Y2EUS)
- **OpenAI发布会Day 7发布会回放与解读：ChatGPT Projects功能重磅上线！新一代ChatBot生产力标杆！**
  - [B station](https://www.bilibili.com/video/BV1pbB3YTE33)
- **ChatGPT操控APP效果演示：一键操控Cursor及其他文本与代码编辑器！**
  - [B station](https://www.bilibili.com/video/BV1e3kkY9E49)
- **OpenAI Day 11：ChatGPT操控指定APP功能上线！发布会实况与深度解读～**
  - [B station](https://www.bilibili.com/video/BV1eVkkYpEAu)
- **ChatGPT APP协作功能介绍与解读！一键配对APP完成操控！Computer use雏形功能上线**
  - [B station](https://www.bilibili.com/video/BV1pikkYqEbU)
- **OpenAI Day 10：打电话、发短信找ChatGPT聊天｜OpenAI发布会Day 10回放与解读**
  - [B station](https://www.bilibili.com/video/BV13DkPYCEHb)
- **ChatGPT创意功能上线！打电话、发短信找ChatGPT聊天～**
  - [B station](https://www.bilibili.com/video/BV1oHkNYHETB)
- **ChatGPT Search发布会完整解读与实况回放｜ChatGPT完整体正式发布，发布会实况解读**
  - [B station](https://www.bilibili.com/video/BV1zSkGYjEWA)
- **ChatGPT完整体来袭，新版互联网Search功能重磅上线，免费可用！｜OpenAI发布会Day 8深度解读**
  - [B station](https://www.bilibili.com/video/BV1nmkGYmEcf)
- **o3推理大模型王炸登场 Agent将获最强大脑！数学编程能力大幅提升、推理新时代来临 ｜ OpenAI发布会Day12**
  - [B station](https://www.bilibili.com/video/BV17wkQYQEaU)
- **全程高能！o3大模型发布会实况与深度解读！OpenAI Day12完整录像与技术解说**
  - [B station](https://www.bilibili.com/video/BV1hikDYzELp)
- **Agent智能体概念详解与2025大模型岗位技能要求分析｜2025Agent最热门开发方向分析**
  - [B station](https://www.bilibili.com/video/BV1TjBnYTETX)
- **零基础Agent智能体开发基础理论详解！记忆、工具、规划、执行四大功能模块设计原理保姆级介绍！**
  - [B station](https://www.bilibili.com/video/BV1CcBJYtEne)
- **12项Agent智能体开发框架入门与选型！｜Coze、Dify、LangChain、LangGraph、AutoGen等工具对比分析与选型建议！**
  - [B station](https://www.bilibili.com/video/BV16NBJYRE3s)
- **当前主流各类GPU分类命名及适用场景介绍｜RTX系列、A系列、H系列、中国区特供版GPU分类命名规则及性能介绍**
  - [B station](https://www.bilibili.com/video/BV1HpBEYsEzW)
- **大模型GPU性能与性价比天梯图详解！各类GPU的大模型训练与推理性能对比，以及主流GPU性价比分析！**
  - [B station](https://www.bilibili.com/video/BV1daBEY7ESw)
- **各类大模型运行GPU配置推荐！各尺寸大模型训练、微调、推理所需GPU配置推荐！**
  - [B station](https://www.bilibili.com/video/BV1GZB7YrE2Y)
- **个人、实验室、企业大模型项目GPU服务器推荐配置及报价！各类大模型项目GPU完整配置清单详解**
  - [B station](https://www.bilibili.com/video/BV15oB7YGEjG)
- **GLM4实战教程（1）：GLM系列在线大模型生态入门介绍**
  - [B station](https://www.bilibili.com/video/BV1gK4y1B7oq)
- **GLM4实战教程（2）：GLM4 API-KEY获取与本地调用**
  - [B station](https://www.bilibili.com/video/BV1ja4y1y7Aj)
- **GLM4实战教程（3）：GLM模型全参数讲解**
  - [B station](https://www.bilibili.com/video/BV1he411n7nS)
- **GLM4实战教程（4）：GLM模型Message队列设置方法与模型身份设置**
  - [B station](https://www.bilibili.com/video/BV1oN4y1n7QG)
- **大模型最大风口Agent是什么？详解Agent在医疗、教育、生产力、个人助理、娱乐、电商领域应用现状**
  - [B station](https://www.bilibili.com/video/BV1LN4y1a7gB)
- **团队自研Agent：MateGen重磅上线！定制知识库+本地代码解释器+联网+追踪debug！伴你高效学习&工作**
  - [B station](https://www.bilibili.com/video/BV1WN41157QT)
- **开源大模型 VS GPT，哪个最适合做Agent？零基础入门Agent开发学习路线推荐！**
  - [B station](https://www.bilibili.com/video/BV11u4y1M73s)
- **全球最前沿GPT系Agent开发都需要哪些技能？详解GPT系Agent开发必备技能学习路线！**
  - [B station](https://www.bilibili.com/video/BV1mi4y1e7kd)
- **国内商用Agent开发，要学习哪些开源大模型？详解开源大模型开发Agent入门学习路径！**
  - [B station](https://www.bilibili.com/video/BV1ij411W7fp)
- **Agent概念详解！为什么Agent才是大模型的未来？数据分析&机器学习Agent到底长啥样？**
  - [B station](https://www.bilibili.com/video/BV1w94y177et)
- **Agent开发必备技能详解！零基础入门Agent开发学习路线精讲！｜在线大模型&开源大模型技术学习路线**
  - [B station](https://www.bilibili.com/video/BV1MN4y1a7iz)
- **零基础迅速掌握Agent开发流程！Agent通用开发范式详解！｜Agent模块化开发流程精讲**
  - [B station](https://www.bilibili.com/video/BV1MN41157gh)
- **AI Agent开发新范式，GPTs功能详解！｜打造个人专属ChatGPT**
  - [B station](https://www.bilibili.com/video/BV1az4y1w7nH)
- **手把手创建一个专属GPTs！打造全自动数据分析Agent！｜以对话的方式高效开发AI Agent**
  - [B station](https://www.bilibili.com/video/BV1XG411S7Df)
- **GPTs进阶功能Actions使用方法详解！将外部工具API接入GPTs，打造功能专属ChatGPT**
  - [B station](https://www.bilibili.com/video/BV1qC4y127js)
- **全自动数据分析报表GPTs功能测试！｜专属GPTs发布与功能测试**
  - [B station](https://www.bilibili.com/video/BV1qw411N7qf)
- **ChatGLM3零基础安装部署流程（上）｜ChatGLM3零基础代码调用流程｜ChatGLM3 Web应用调用方法**
  - [B station](https://www.bilibili.com/video/BV1gN4y1r7RX)
- **ChatGLM3零基础安装部署流程（下）｜ChatGLM3零基础代码调用流程｜ChatGLM3 Web应用调用方法**
  - [B station](https://www.bilibili.com/video/BV18M411Q7Pp)
- **ChatGLM3快速入门，全新API调用方法详解｜Messages参数功能介绍**
  - [B station](https://www.bilibili.com/video/BV18c411d7Hd)
- **ChatGLM3推理性能快速评测｜ChatGLM3 VS GPT系模型性能对比**
  - [B station](https://www.bilibili.com/video/BV1BG411X7Hk)
- **ChatGLM3工具调用function calling功能详解｜如何让ChatGLM3接入外部工具｜ChatGLM3 Agent开发入门**
  - [B station](https://www.bilibili.com/video/BV1V84y1971r)
- **ChatGLM3 Agent开发入门｜Function calling全自动实现｜AI Agent开发入门**
  - [B station](https://www.bilibili.com/video/BV1Wy4y1c7oA)
- **进步显著！ChatGLM3重磅上线！深度详解新模型性能与新功能**
  - [B station](https://www.bilibili.com/video/BV14N4y1674J)
- **ChatGLM3全新消息队列功能介绍！接入先进多角色对话功能！**
  - [B station](https://www.bilibili.com/video/BV1fg4y197xM)
- **ChatGLM3全新Function calling功能详解！开启AI Agent之路的最核心功能！**
  - [B station](https://www.bilibili.com/video/BV1K94y157gd)
- **如何借助大模型冲击Kaggle金牌？**
  - [B station](https://www.bilibili.com/video/BV1i84y127sB)
- **自动机器学习建模AI Agent功能架构详解**
  - [B station](https://www.bilibili.com/video/BV1MN411t79i)
- **自动机器学习建模 AI Agent入门实操**
  - [B station](https://www.bilibili.com/video/BV1oG41117oq)
- **特征衍生全技术路径精讲 | 机器学习 | 特征工程**
  - [B station](https://www.bilibili.com/video/BV1aC4y1d7GD)
- **特征筛选全技术路径精讲**
  - [B station](https://www.bilibili.com/video/BV1Kw411k7XT)
- **模型融合全技术地图讲解**
  - [B station](https://www.bilibili.com/video/BV19B4y1Z7dK)
- **GPT系AI应用开发实战01: GPT模型Function calling功能入门介绍**
  - [B station](https://www.bilibili.com/video/BV1XF411f7qF)
- **GPT系AI应用开发实战02: Function calling相关参数详解**
  - [B station](https://www.bilibili.com/video/BV16X4y1L7H2)
- **GPT系AI应用开发实战03: Function calling开发流程详解**
  - [B station](https://www.bilibili.com/video/BV1f8411d73j)
- **GPT系AI应用开发实战04: GPT模型调用外部工具API方法介绍**
  - [B station](https://www.bilibili.com/video/BV1w14y1q7yr)
- **GPT系AI应用开发实战05: 基于GPT模型的天气查询应用开发实战**
  - [B station](https://www.bilibili.com/video/BV1Nu4y1z7ku)
- **GPT系AI应用开发实战06: AI应用开发入门: 谷歌云与API库入门介绍**
  - [B station](https://www.bilibili.com/video/BV1hH4y1D7qF)
- **GPT系AI应用开发实战07: AI应用开发入门: 谷歌云 Auth2.0 授权方法**
  - [B station](https://www.bilibili.com/video/BV17p4y1j75v)
- **GPT系AI应用开发实战08: 基于Gmail API的AI邮件系统开发实战1**
  - [B station](https://www.bilibili.com/video/BV1rj411C7G4)
- **GPT系AI应用开发实战09: 基于Gmail API的AI邮件系统开发实战2**
  - [B station](https://www.bilibili.com/video/BV1gH4y1Q7iy)
- **GPT系AI应用开发实战10: 热门AI应用开发方向解读**
  - [B station](https://www.bilibili.com/video/BV1Dz4y1j7vH)
- **GPT系AI应用开发实战11: 智能搜索问答机器人项目介绍与开发思路**
  - [B station](https://www.bilibili.com/video/BV1Qp4y1A7X9)
- **GPT系AI应用开发实战12: 谷歌搜索API获取与使用方法 | 将谷歌搜索接入GPT大模型**
  - [B station](https://www.bilibili.com/video/BV16u411c7Nd)
- **GPT系AI应用开发实战13: 构建基于GitHub的搜索问答机器人**
  - [B station](https://www.bilibili.com/video/BV1jy4y1F7QW)
- **GPT大模型技术实战教程01: OpenAI官网使用指南与API-Key获取**
  - [B station](https://www.bilibili.com/video/BV1YM4y1x76K)
- **GPT大模型技术实战教程02: GPT大模型API-Key使用方法&Jupyter本地调用**
  - [B station](https://www.bilibili.com/video/BV1RV411T754)
- **GPT大模型技术实战教程03: Completion模型与Chat模型入门介绍**
  - [B station](https://www.bilibili.com/video/BV1M8411Q7Kv)
- **GPT大模型技术实战教程04: Completion模型API使用方法详解**
  - [B station](https://www.bilibili.com/video/BV1fP411k7vv)
- **GPT大模型技术实战教程05:  Completion模型调参实践**
  - [B station](https://www.bilibili.com/video/BV1zz4y147FZ)
- **GPT大模型技术实战教程06: 基于Completion手动创建可自定义聊天风格的对话机器人**
  - [B station](https://www.bilibili.com/video/BV1U14y197hp)
- **GPT大模型技术实战教程07: GPT最新Chat类模型入门介绍**
  - [B station](https://www.bilibili.com/video/BV1Vk4y1V76h)
- **GPT大模型技术实战教程08：Chat模型功能介绍与发展现状**
  - [B station](https://www.bilibili.com/video/BV1LN411Y7hW)
- **GPT大模型技术实战教程09: GPT-4 API使用方法&Chat模型API详解**
  - [B station](https://www.bilibili.com/video/BV1f14y1z7HS)
- **GPT大模型技术实战教程10: GPT-4 API核心参数Message使用方法详解**
  - [B station](https://www.bilibili.com/video/BV1vc411F7vi)
- **【入门】OpenAI在线大模型生态介绍｜大模型技术入门课程｜GPT&DALL·E&Codex&Embedding模型介绍**
  - [B station](https://www.bilibili.com/video/BV15P411z7pU)
- **【入门】开源大模型生态与ChatGLM-6B大模型介绍｜最强中文大模型GLM介绍｜LLM开源大模型概览**
  - [B station](https://www.bilibili.com/video/BV1Xg4y1N7kM)
- **【入门】大语言模型常用微调框架介绍｜LoRA&Prefix-Tuning&Prompt-Tuning&P-Tuning v2&RLHF微调原理简介**
  - [B station](https://www.bilibili.com/video/BV1Yc411g78a)
- **【入门】AI应用开发范式LangChain零基础入门介绍｜LangChain六大功能模块解释｜基于LLM的AI开发流程与开发工具**
  - [B station](https://www.bilibili.com/video/BV1gz4y1e7im)
- **机器学习面试热点问题精讲·Part 1.机器学习基础篇｜2023冲刺春招算法岗｜面试必考机器学习热点问题｜全原理讲解&附赠标准问答模版**
  - [B station](https://www.bilibili.com/video/BV1oo4y167CV)
- **机器学习面试热点问题精讲·Part 2.经典机器学习篇｜2023冲刺春招算法岗｜面试必考机器学习热点问题｜全原理讲解&附赠标准问答模版**
  - [B station](https://www.bilibili.com/video/BV1XT411v7WK)
- **机器学习面试热点问题精讲·Part 3.集成学习篇｜2023冲刺春招算法岗｜面试必考机器学习热点问题｜全原理讲解&附赠标准问答模版**
  - [B station](https://www.bilibili.com/video/BV17j411g7PX)
- **机器学习面试热点问题精讲·Part 4.特征工程篇｜2023冲刺春招算法岗｜面试必考机器学习热点问题｜全原理讲解&附赠标准问答模版**
  - [B station](https://www.bilibili.com/video/BV1pT411v7gD)
- **机器学习面试热点问题精讲·Part 5.模型融合篇｜2023冲刺春招算法岗｜面试必考机器学习热点问题｜全原理讲解&附赠标准问答模版**
  - [B station](https://www.bilibili.com/video/BV1c54y1u7DU)