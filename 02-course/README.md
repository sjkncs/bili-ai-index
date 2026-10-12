# AI 课程与教程

> Source: **ShusenWang, 霹雳吧啦Wz, 刘二大人, 王木头学科学, Bubbliiiing, 啥都会一点的研究生** - Snapshot: **2026-10-12** - **357** episodes.
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

## All 357 episodes

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
- **最新Windows配置VSCode与Anaconda环境**
  - [B station](https://www.bilibili.com/video/BV1QD4y147ek)
- **『图像分类』从零环境搭建&快速开始**
  - [B station](https://www.bilibili.com/video/BV1fe4y1s77Q)
- **『图像分类』模型如何搭建|文件如何调用**
  - [B station](https://www.bilibili.com/video/BV12a411772h)
- **『图像分类』数据预处理|数据增强**
  - [B station](https://www.bilibili.com/video/BV1zY4y167Ju)
- **『图像分类』学习率更新策略|优化器**
  - [B station](https://www.bilibili.com/video/BV1WT4y1q7qN)
- **『图像分类』配置文件补充说明**
  - [B station](https://www.bilibili.com/video/BV1bt4y1W7mm)
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