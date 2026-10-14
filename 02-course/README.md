# AI 课程与教程

> Source: **ShusenWang, 霹雳吧啦Wz, 刘二大人, 王木头学科学, Bubbliiiing, 啥都会一点的研究生, RethinkFun, 我是傅傅猪, 唐国梁Tommy, 九天Hector, shuhuai008, 王树尧SJTU, 张伟楠SJTU, 良睦路程序员, Beyond_April, Enzo_Mi, 鱼香ROS机器人, 古希腊掌管代码的神, Nenly同学, 淅沥f80, 破夜萤火虫, 杜子源源** - Snapshot: **2026-10-14** - **3165** episodes.
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

## All 3165 episodes

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
| 1080 | - | - | DeepSpeed-Chat-23-step1_源码解读_模型推理-第2节 | 5:46 | [link](https://www.bilibili.com/video/BV1yb421h7PB) |
| 1081 | - | - | DeepSpeed-Chat-24-step1_源码解读_模型推理-第3节 | 11:53 | [link](https://www.bilibili.com/video/BV1Xb421Y7ga) |
| 1082 | - | - | DeepSpeed-Chat-26 Step-2 Reward模型微调和评估 | 9:52 | [link](https://www.bilibili.com/video/BV1z14y1i7hv) |
| 1083 | - | - | Chat-27-step2-源码解读-参数配置和初始化 | 12:28 | [link](https://www.bilibili.com/video/BV1y84y1m7VX) |
| 1084 | - | - | Chat-28-step2-源码解读-创建Reward模型 | 10:59 | [link](https://www.bilibili.com/video/BV1hN411t7pk) |
| 1085 | - | - | Chat-29-step2-源码解读-创建数据集 | 10:46 | [link](https://www.bilibili.com/video/BV14C4y1V7L4) |
| 1086 | - | - | Chat-30-step2-源码解读-参数分组_创建学习率调度器 | 5:51 | [link](https://www.bilibili.com/video/BV1P34y137FB) |
| 1087 | - | - | Chat-31-step2-源码解读-deepspeed初始化 | 2:45 | [link](https://www.bilibili.com/video/BV1Pm4y1G7yf) |
| 1088 | - | - | Chat-32-step2-源码解读-模型评估定义 | 7:57 | [link](https://www.bilibili.com/video/BV1P94y1a7T1) |
| 1089 | - | - | Chat-33-step2-源码解读-Reward模型训练 | 7:02 | [link](https://www.bilibili.com/video/BV1P8411y7EA) |
| 1090 | - | - | Chat-34-step2-源码解读-Reward模型保存 | 4:18 | [link](https://www.bilibili.com/video/BV1FV411c7Cf) |
| 1091 | - | - | Chat-35-step2-源码解读-Reward模型评估 | 11:22 | [link](https://www.bilibili.com/video/BV11H4y1f7X6) |
| 1092 | - | - | Chat-36-step2-源码解读-forward算法-第1节 | 11:58 | [link](https://www.bilibili.com/video/BV1v34y1V7jV) |
| 1093 | - | - | Chat-37-step2-源码解读-forward算法-第2节 | 13:32 | [link](https://www.bilibili.com/video/BV14H4y1f7EB) |
| 1094 | - | - | Chat-38-step2-源码解读-forward算法-第3节 | 5:59 | [link](https://www.bilibili.com/video/BV13m4y1G7mq) |
| 1095 | - | - | Chat-39-step2-源码解读-forward算法-第4节 | 9:47 | [link](https://www.bilibili.com/video/BV1RH4y1f7Dn) |
| 1096 | - | - | 方案1-CIFAR10-01-数据加载和预处理 | 11:45 | [link](https://www.bilibili.com/video/BV1wx4y1r7nn) |
| 1097 | - | - | 方案1-CIFAR10-02-模型定义与超参数创建 | 9:58 | [link](https://www.bilibili.com/video/BV1iC411n79w) |
| 1098 | - | - | 方案1-CIFAR10-03-模型训练和本地保存 | 6:45 | [link](https://www.bilibili.com/video/BV1Jp421Q7Ar) |
| 1099 | - | - | 方案1-CIFAR10-04-模型性能验证 | 16:35 | [link](https://www.bilibili.com/video/BV17z421r7nb) |
| 1100 | - | - | 方案1-CIFAR10-05-基于FastAPI实现推理服务 | 14:22 | [link](https://www.bilibili.com/video/BV12z42167Qd) |
| 1101 | - | - | 方案2-CIFAR10-DeepSpeed-01-超参数定义 | 15:37 | [link](https://www.bilibili.com/video/BV1Mt421A7Lj) |
| 1102 | - | - | 方案2-CIFAR10-DeepSpeed-02-模型结构定义 | 15:35 | [link](https://www.bilibili.com/video/BV19w4m1275e) |
| 1103 | - | - | 方案2-CIFAR10-DeepSpeed-03-模型分布式训练 | 7:13 | [link](https://www.bilibili.com/video/BV1u1421R78i) |
| 1104 | - | - | 方案2-CIFAR10-DeepSpeed-04-模型性能验证 | 9:03 | [link](https://www.bilibili.com/video/BV1DH4y1A785) |
| 1105 | - | - | 方案2-CIFAR10-DeepSpeed-05-配置文件参数讲解 | 8:54 | [link](https://www.bilibili.com/video/BV1dF4m1w7WQ) |
| 1106 | - | - | 方案2-CIFAR10-DeepSpeed-06-模型分布式训练 | 12:17 | [link](https://www.bilibili.com/video/BV1tt421A7Pd) |
| 1107 | - | - | OpenAI assistant API 学习指南-简介 | 22:55 | [link](https://www.bilibili.com/video/BV1Wj411j7mn) |
| 1108 | - | - | OpenAI assistant API 学习指南-assistant运行原理 | 22:17 | [link](https://www.bilibili.com/video/BV1oN411777P) |
| 1109 | - | - | LangChain 实战案例-01 基于上传的PDF文档进行QA问答 第1节 项目简介 | 9:55 | [link](https://www.bilibili.com/video/BV1fp4y137US) |
| 1110 | - | - | LangChain 实战案例-01 基于上传PDF文档进行QA问答 第2节 案例实现 | 22:33 | [link](https://www.bilibili.com/video/BV1rk4y1g7Gd) |
| 1111 | - | - | LangChain 教程 实战案例-01 基于上传PDF文档进行QA问答 第3节 向量数据库 | 15:13 | [link](https://www.bilibili.com/video/BV1294y1C7Cd) |
| 1112 | - | - | LangChain 实战案例-01 基于上传PDF文档进行QA问答 第4节 基于Gradio实现QA交互 | 32:09 | [link](https://www.bilibili.com/video/BV1rN41187Q9) |
| 1113 | - | - | Chinese LLaMA Alpaca 案例实战-01-项目概览 | 7:34 | [link](https://www.bilibili.com/video/BV1Mh4y187ir) |
| 1114 | - | - | Chinese- LLaMA- Alpaca 案例实战-02-指令数据生成 | 10:58 | [link](https://www.bilibili.com/video/BV1ns4y1g717) |
| 1115 | - | - | 案例实战-03-Chinese-LLaMA-AIpaca模型本地部署 | 12:39 | [link](https://www.bilibili.com/video/BV1xz4y18749) |
| 1116 | - | - | 案例实战-04-基于webUI进行交互 | 9:43 | [link](https://www.bilibili.com/video/BV1im4y1h7wo) |
| 1117 | - | - | 案例实战-05-基于LLaMA和LoRA模型进行预训练 | 20:30 | [link](https://www.bilibili.com/video/BV1f8411o73g) |
| 1118 | - | - | 案例实战-06-上集—基于LLaMA和LoRA模型进行指令精调 | 16:50 | [link](https://www.bilibili.com/video/BV1eX4y187nN) |
| 1119 | - | - | 案例实战-07-下集-基于LLaMA和LoRA模型进行指令精调 | 13:49 | [link](https://www.bilibili.com/video/BV1mP411D7bm) |
| 1120 | - | - | 案例实战-08-LLaMA与LangChain进行集成 | 19:33 | [link](https://www.bilibili.com/video/BV1Ph4y137JW) |
| 1121 | - | - | 案例实战-09-剧透-使用 FastAPI 实现 LLaMA API服务 | 10:50 | [link](https://www.bilibili.com/video/BV1vh4y1X7D6) |
| 1122 | - | - | 案例实战-10-LLaMA tokenizer模型与中文tokenizer模型合并操作 | 5:51 | [link](https://www.bilibili.com/video/BV1hh4y1M7YE) |
| 1123 | - | - | 案例实战-11-单个LoRA权重与LLaMA合并 | 25:00 | [link](https://www.bilibili.com/video/BV15h4y1M7MU) |
| 1124 | - | - | 案例实战-12-多个LoRA权重与LLaMA合并 | 8:55 | [link](https://www.bilibili.com/video/BV1KV4y117ci) |
| 1125 | - | - | 案例实战-13-指令精调手把手教程-升级版 | 16:32 | [link](https://www.bilibili.com/video/BV1Qu411t7ML) |
| 1126 | - | - | 案例实战-14-基于llama.cpp量化模型部署 | 13:53 | [link](https://www.bilibili.com/video/BV1Y14y1d75g) |
| 1127 | - | - | 案例实战-15-使用 privateGPT 进行多文档问答 | 14:07 | [link](https://www.bilibili.com/video/BV1Wm4y1Y7G3) |
| 1128 | - | - | 案例实战-16-llama.cpp量化模型GPU加速推理 | 14:40 | [link](https://www.bilibili.com/video/BV1314y1o7dS) |
| 1129 | - | - | 案例实战-17-llama.cpp量化模型API服务部署 | 13:58 | [link](https://www.bilibili.com/video/BV1kz4y1E7ha) |
| 1130 | - | - | 源码讲解-01-中文词汇表扩充 | 9:33 | [link](https://www.bilibili.com/video/BV1Es4y1g7uu) |
| 1131 | - | - | 源码讲解-02-llama与lora模型合并 | 14:35 | [link](https://www.bilibili.com/video/BV1rX4y187Wb) |
| 1132 | - | - | 源码讲解-03-基于llama模型进行推理 | 13:31 | [link](https://www.bilibili.com/video/BV1a24y1K79a) |
| 1133 | - | - | 源码讲解-04-上集-模型预训练代码逐行剖析 | 22:30 | [link](https://www.bilibili.com/video/BV18X4y187ss) |
| 1134 | - | - | 源码讲解-05-中集-模型预训练代码逐行剖析 | 20:46 | [link](https://www.bilibili.com/video/BV1wo4y1g7DF) |
| 1135 | - | - | 源码讲解-06-下集-模型预训练代码逐行剖析 | 24:41 | [link](https://www.bilibili.com/video/BV1S8411o78y) |
| 1136 | - | - | 源码讲解-07-上集-API服务server代码讲解 | 21:58 | [link](https://www.bilibili.com/video/BV1N14y1D7eT) |
| 1137 | - | - | 源码讲解-08-下集-API服务server代码讲解 | 17:41 | [link](https://www.bilibili.com/video/BV13k4y1H7Ck) |
| 1138 | - | - | 01_模型推理与部署专题简介 | 1:12 | [link](https://www.bilibili.com/video/BV1HY411r7fc) |
| 1139 | - | - | 02_TensorRT与Triton容器部署 | 15:35 | [link](https://www.bilibili.com/video/BV1h24y1n7ws) |
| 1140 | - | - | 03_TensorFlow模型转换TensorRT引擎推理 | 13:30 | [link](https://www.bilibili.com/video/BV1124y1b7Le) |
| 1141 | - | - | 04_Pytorch模型转换为TensorRT引擎推理 | 9:10 | [link](https://www.bilibili.com/video/BV1yg4y1t71M) |
| 1142 | - | - | 05_tensorflow_serving_模型部署与推理_mnist分类案例 | 13:58 | [link](https://www.bilibili.com/video/BV1iT411a7GU) |
| 1143 | - | - | 06_tensorflow_serving_单个模型部署与推理_线性回归 | 11:56 | [link](https://www.bilibili.com/video/BV1WY411B7Yh) |
| 1144 | - | - | 07_tensorflow_serving_多个模型部署与推理_模型迭代 | 14:36 | [link](https://www.bilibili.com/video/BV1x54y1M7Es) |
| 1145 | - | - | 08_torch_serving_docker环境部署 | 6:38 | [link](https://www.bilibili.com/video/BV19N411N73R) |
| 1146 | - | - | 09_torch_serving_案例1-序列分类 | 9:15 | [link](https://www.bilibili.com/video/BV18g4y1W7BD) |
| 1147 | - | - | 10_torch_serving_案例2-QA问答 | 12:33 | [link](https://www.bilibili.com/video/BV1vN411K7Bf) |
| 1148 | - | - | 轻松学·Streamlit_01_专题简介 | 8:41 | [link](https://www.bilibili.com/video/BV1EY4y1Z7No) |
| 1149 | - | - | 轻松学·Streamlit_02_基础功能探索 | 18:23 | [link](https://www.bilibili.com/video/BV1Q3411Z76n) |
| 1150 | - | - | 轻松学·Streamlit_03_基础功能探索 | 10:28 | [link](https://www.bilibili.com/video/BV1624y1h78E) |
| 1151 | - | - | 轻松学·Streamlit_04_基础功能探索 | 14:23 | [link](https://www.bilibili.com/video/BV1jv4y117zn) |
| 1152 | - | - | 轻松学·Streamlit_05_基础功能探索 | 8:07 | [link](https://www.bilibili.com/video/BV16G4y1w7td) |
| 1153 | - | - | 轻松学·Streamlit_06_基础功能探索 | 14:56 | [link](https://www.bilibili.com/video/BV1s3411d7QA) |
| 1154 | - | - | 轻松学·Streamlit_07_动物图片识别 APP | 13:37 | [link](https://www.bilibili.com/video/BV1Cx4y137xK) |
| 1155 | - | - | 轻松学·Streamlit_08_音频转文本 APP | 13:28 | [link](https://www.bilibili.com/video/BV1z14y1M7J1) |
| 1156 | - | - | 轻松学·Streamlit_09_ML分类案例 APP | 26:28 | [link](https://www.bilibili.com/video/BV1g24y1h7FK) |
| 1157 | - | - | 01_ES 概念、核心理论部分 | 8:39 | [link](https://www.bilibili.com/video/BV1Ta411q73R) |
| 1158 | - | - | DeepSpeed-Chat-20-step1_源码解读_模型保存-第3节 | 9:08 | [link](https://www.bilibili.com/video/BV18h4y1S7Rn) |
| 1159 | - | - | DeepSpeed-Chat-21-step1_源码解读_模型评估 | 18:03 | [link](https://www.bilibili.com/video/BV1fZ421E7o9) |
| 1160 | - | - | DeepSpeed-Chat-22-step1_源码解读_模型推理-第1节 | 6:04 | [link](https://www.bilibili.com/video/BV1bm421p7GE) |
| 1161 | - | - | DeepSpeed-Chat-25 Step-2-01 简介 | 8:17 | [link](https://www.bilibili.com/video/BV1Dh4y1S7rG) |
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
| 1174 | - | - | 进阶学·ES-04-01 analyzer简介 | 13:02 | [link](https://www.bilibili.com/video/BV1SV4y1L77u) |
| 1175 | - | - | 进阶学·ES-04-02 analyzer应用 | 13:20 | [link](https://www.bilibili.com/video/BV1g84y1z7SM) |
| 1176 | - | - | 进阶学·ES-04-03 analyzer IK分词器-自定义词典 | 13:31 | [link](https://www.bilibili.com/video/BV16N4y1c7VW) |
| 1177 | - | - | 进阶学·ES-04-04 analyzer IK分词器-同义词-上集 | 13:23 | [link](https://www.bilibili.com/video/BV1qe411L7SJ) |
| 1178 | - | - | 进阶学·ES-04-05 analyzer IK分词器-同义词-下集 | 8:24 | [link](https://www.bilibili.com/video/BV1mG4y1p75R) |
| 1179 | - | - | 进阶学·ES-04-06 analyzer IK分词器-停用词 | 17:39 | [link](https://www.bilibili.com/video/BV1i14y177tV) |
| 1180 | - | - | 进阶学·ES-04-07 analyzer IK分词器-拼音搜索 | 5:16 | [link](https://www.bilibili.com/video/BV1BK411Q7YP) |
| 1181 | - | - | 进阶学·ES-04-08 ES辅助功能 | 23:00 | [link](https://www.bilibili.com/video/BV1Ee4y1i77Q) |
| 1182 | - | - | 进阶学·ES-04-09 ES布尔查询 | 10:11 | [link](https://www.bilibili.com/video/BV1ZW4y1J77a) |
| 1183 | - | - | 进阶学·ES-04-10 ES全文搜索 | 13:18 | [link](https://www.bilibili.com/video/BV17e411V7ec) |
| 1184 | - | - | 进阶学·ES-04-11 ES搜索排序 | 14:29 | [link](https://www.bilibili.com/video/BV19V4y1V7ge) |
| 1185 | - | - | mysql_01_课程简介 | 2:59 | [link](https://www.bilibili.com/video/BV1e14y187iC) |
| 1186 | - | - | mysql_02_基本操作 | 8:07 | [link](https://www.bilibili.com/video/BV13t4y1A7HN) |
| 1187 | - | - | mysql_03_数据表的增删改 | 5:57 | [link](https://www.bilibili.com/video/BV1TV4y1K7S6) |
| 1188 | - | - | mysql_04_01_数据查询 | 13:18 | [link](https://www.bilibili.com/video/BV15T411P7rC) |
| 1189 | - | - | mysql_04_02_数据查询 | 13:43 | [link](https://www.bilibili.com/video/BV13e411j7M6) |
| 1190 | - | - | mysql_05_01_存储过程 | 12:18 | [link](https://www.bilibili.com/video/BV1eG4y1W7H5) |
| 1191 | - | - | mysql_05_02_存储过程 | 8:34 | [link](https://www.bilibili.com/video/BV1Te4y1z78C) |
| 1192 | - | - | mysql_06_01_索引 | 6:25 | [link](https://www.bilibili.com/video/BV1NN4y1N7Mc) |
| 1193 | - | - | mysql_06_02 索引 | 7:02 | [link](https://www.bilibili.com/video/BV1fV4y1N7eV) |
| 1194 | - | - | mysql_07_python与mysql教程 | 27:59 | [link](https://www.bilibili.com/video/BV17G411n7q6) |
| 1195 | - | - | mysql_08_pandas与mysql教程 | 9:24 | [link](https://www.bilibili.com/video/BV1kG4y1W7J7) |
| 1196 | - | - | 自然语言处理快速入门 01-BERT及其变种的原理 | 18:16 | [link](https://www.bilibili.com/video/BV1RP4y1t7sc) |
| 1197 | - | - | 02-BERT及其变种的原理 | 8:17 | [link](https://www.bilibili.com/video/BV1d44y1x7tP) |
| 1198 | - | - | 03-BERT及其变种的原理 | 3:59 | [link](https://www.bilibili.com/video/BV12r4y1y7PS) |
| 1199 | - | - | 04-BERT及其变种的原理 | 3:43 | [link](https://www.bilibili.com/video/BV19F411Y7ER) |
| 1200 | - | - | 05-BERT及其变种的原理 | 4:36 | [link](https://www.bilibili.com/video/BV1zr4y1y72v) |
| 1201 | - | - | 06-BERT入门二分类案例 自然语言处理快速入门 | 35:18 | [link](https://www.bilibili.com/video/BV1SP4y137Pp) |
| 1202 | - | - | 07-基于RoBERTa训练一个MLM掩码语言模型 | 29:18 | [link](https://www.bilibili.com/video/BV1gF411z78D) |
| 1203 | - | - | 08_一_基于BiLSTM和BERT实现分类任务 | 15:23 | [link](https://www.bilibili.com/video/BV1wb4y1i7hU) |
| 1204 | - | - | 09_二_基于BiLSTM和BERT实现分类任务 | 17:40 | [link](https://www.bilibili.com/video/BV1uR4y137JG) |
| 1205 | - | - | 10_三_基于BiLSTM和BERT实现分类任务 | 12:42 | [link](https://www.bilibili.com/video/BV1UP4y1J7yr) |
| 1206 | - | - | 11_四_基于BiLSTM和BERT实现分类任务 | 21:14 | [link](https://www.bilibili.com/video/BV17q4y117YB) |
| 1207 | - | - | 01_TensorFlow 2.0 分类案例【银行客户流失预测】官网+个人实现 | 40:56 | [link](https://www.bilibili.com/video/BV1f44y1z7XF) |
| 1208 | - | - | 02_TensorFlow 2.0 鲜花分类 官网案例详解 + 优化 | 32:03 | [link](https://www.bilibili.com/video/BV1cf4y187PE) |
| 1209 | - | - | 03_TensorFlow 2.0 迁移学习_案例1_基于预训练模型进行目标分类 | 22:16 | [link](https://www.bilibili.com/video/BV1oB4y1T7qL) |
| 1210 | - | - | 04-1_TensorFlow 2.0 迁移学习_案例2_上集_宠物狗品种识别 | 28:35 | [link](https://www.bilibili.com/video/BV1b44y167ca) |
| 1211 | - | - | 04-2_TensorFlow 2.0 迁移学习_案例2_下集_宠物狗品种识别 | 39:04 | [link](https://www.bilibili.com/video/BV19B4y1T7eP) |
| 1212 | - | - | 05_TensorFlow 2.0 回归案例 葡萄酒品质预测 | 38:12 | [link](https://www.bilibili.com/video/BV1F64y1r7Ub) |
| 1213 | - | - | 06_TensorFlow 2.0 基于LSTM进行文本生成（字符级） | 41:53 | [link](https://www.bilibili.com/video/BV1ko4y1k7Lo) |
| 1214 | - | - | 07_TensorFlow 2.0 基于LSTM单变量预测_电力消耗案例 | 51:01 | [link](https://www.bilibili.com/video/BV1f5411K7qD) |
| 1215 | - | - | 08_TensorFlow 2.0 基于LSTM多变量_共享单车使用量预测 | 48:39 | [link](https://www.bilibili.com/video/BV1y5411K7NR) |
| 1216 | - | - | 09_基于Embedding进行IMDB情感文本分类（上集） | 20:17 | [link](https://www.bilibili.com/video/BV19y4y1M7p5) |
| 1217 | - | - | 09_基于Embedding进行IMDB情感文本分类（下集） | 31:16 | [link](https://www.bilibili.com/video/BV1X64y197KS) |
| 1218 | - | - | 10-01 OCR入门案例_手写字体识别 | 11:28 | [link](https://www.bilibili.com/video/BV1tX4y1w751) |
| 1219 | - | - | 10-02 OCR入门案例_手写字体识别 | 44:06 | [link](https://www.bilibili.com/video/BV1EB4y1N7oz) |
| 1220 | - | - | 10-03 OCR入门案例_手写字体识别 | 16:25 | [link](https://www.bilibili.com/video/BV1oh411h7oy) |
| 1221 | - | - | 11_01 OCR 图片去噪 | 12:29 | [link](https://www.bilibili.com/video/BV1H54y1E7yv) |
| 1222 | - | - | 11_02 OCR 图片去噪 | 2:28 | [link](https://www.bilibili.com/video/BV1TX4y1A7fN) |
| 1223 | - | - | 11_03 OCR 图片去噪 | 16:14 | [link](https://www.bilibili.com/video/BV1Tf4y1j7PU) |
| 1224 | - | - | 11_04 OCR 图片去噪 | 5:48 | [link](https://www.bilibili.com/video/BV1L64y1z7yV) |
| 1225 | - | - | 11_05 OCR 图片去噪 | 10:51 | [link](https://www.bilibili.com/video/BV1bb4y1k75f) |
| 1226 | - | - | 12_TensorFlow 2.0 多分类案例 CIFAR10【官网 + 个人实现】 | 37:24 | [link](https://www.bilibili.com/video/BV1UK4y1X7dM) |
| 1227 | - | - | 01_轻松学Python_python语言简介和工具安装 | 14:13 | [link](https://www.bilibili.com/video/BV1Pg4y1q7BZ) |
| 1228 | - | - | 02 轻松学python 变量 | 16:19 | [link](https://www.bilibili.com/video/BV1Qi4y1s7EW) |
| 1229 | - | - | 03 轻松学python 数字类型 | 4:35 | [link](https://www.bilibili.com/video/BV1CT4y1E7fE) |
| 1230 | - | - | 04 轻松学python 运算符 | 9:52 | [link](https://www.bilibili.com/video/BV1854y1Q7ai) |
| 1231 | - | - | 05 轻松学python 字符串 | 39:30 | [link](https://www.bilibili.com/video/BV1vz411i726) |
| 1232 | - | - | 06 轻松学python 列表 | 27:46 | [link](https://www.bilibili.com/video/BV1vz4y197hL) |
| 1233 | - | - | 07 轻松学python 元组 | 18:43 | [link](https://www.bilibili.com/video/BV1xV411r7Gu) |
| 1234 | - | - | 08 轻松学python 字典 | 25:54 | [link](https://www.bilibili.com/video/BV1ki4y1s7TG) |
| 1235 | - | - | 09 轻松学python 集合 | 13:48 | [link](https://www.bilibili.com/video/BV1Lv41167zH) |
| 1236 | - | - | 10 轻松学python if条件判断语句 | 17:17 | [link](https://www.bilibili.com/video/BV16z411i7iY) |
| 1237 | - | - | 11 轻松学python while循环语句 | 22:27 | [link](https://www.bilibili.com/video/BV1RK4y1x7CQ) |
| 1238 | - | - | 12 轻松学python for循环语句 | 19:07 | [link](https://www.bilibili.com/video/BV1ET4y1J7GV) |
| 1239 | - | - | 13 轻松学python 迭代器 | 19:17 | [link](https://www.bilibili.com/video/BV11Z4y1H7zU) |
| 1240 | - | - | 14 轻松学 python range zip enumerate 内置函数 | 24:27 | [link](https://www.bilibili.com/video/BV1NK411W72q) |
| 1241 | - | - | 15 轻松学 python 列表推导 | 10:45 | [link](https://www.bilibili.com/video/BV1zz4y1Q7zo) |
| 1242 | - | - | 16-1 轻松学 Python 类 ( 第一节 ) | 17:32 | [link](https://www.bilibili.com/video/BV1qK4y1478J) |
| 1243 | - | - | 16-2 轻松学 Python 类 继承 多态 ( 第二节 ) | 33:10 | [link](https://www.bilibili.com/video/BV1Tz4y1X72S) |
| 1244 | - | - | 16-3 轻松学 Python 类 运算符重载 ( 第三节 ) | 38:52 | [link](https://www.bilibili.com/video/BV1wf4y1R7tw) |
| 1245 | - | - | 01_轻松学OpenCV_简介 | 15:40 | [link](https://www.bilibili.com/video/BV1Ji4y1x7vJ) |
| 1246 | - | - | 02_轻松学OpenCV_图像基础 | 31:58 | [link](https://www.bilibili.com/video/BV1eg4y1i7P6) |
| 1247 | - | - | 03 轻松学 OpenCV argparse模块 | 15:41 | [link](https://www.bilibili.com/video/BV1fK411H7bf) |
| 1248 | - | - | 04 轻松学 OpenCV 读取图片 | 20:02 | [link](https://www.bilibili.com/video/BV1uT4y1J7iV) |
| 1249 | - | - | 05 轻松学 OpenCV 读取_处理_保存图片 | 14:51 | [link](https://www.bilibili.com/video/BV1St4y1X7Lq) |
| 1250 | - | - | 06 轻松学 OpenCV 从摄像头读取视频 | 22:14 | [link](https://www.bilibili.com/video/BV1gg4y1v7jt) |
| 1251 | - | - | 07 轻松学 OpenCV 从视频文件读取内容 | 12:01 | [link](https://www.bilibili.com/video/BV19Z4y1H7GH) |
| 1252 | - | - | 08 轻松学OpenCV 保存摄像头读取到的视频内容 | 28:17 | [link](https://www.bilibili.com/video/BV1EV411k78q) |
| 1253 | - | - | 09 轻松学OpenCV 图像的8种变换 | 53:37 | [link](https://www.bilibili.com/video/BV1oK4y1x7PH) |
| 1254 | - | - | 10 轻松学 OpenCV 灰度直方图 | 41:48 | [link](https://www.bilibili.com/video/BV14i4y1x797) |
| 1255 | - | - | 11 轻松学 OpenCV 灰度直方图 ( 补充知识点 ) | 17:07 | [link](https://www.bilibili.com/video/BV1dK411p7cu) |
| 1256 | - | - | 12 轻松学 OpenCV mask | 24:33 | [link](https://www.bilibili.com/video/BV1EZ4y1H7bB) |
| 1257 | - | - | 13 轻松学 OpenCV 彩色直方图 | 25:12 | [link](https://www.bilibili.com/video/BV17k4y1z7L3) |
| 1258 | - | - | 14 轻松学 OpenCV 画出基本图形 | 24:58 | [link](https://www.bilibili.com/video/BV1xK4y147Mk) |
| 1259 | - | - | 15 轻松学 OpenCV 图片上显示文本 | 12:12 | [link](https://www.bilibili.com/video/BV1DD4y1D7Hw) |
| 1260 | - | - | 16 轻松学 OpenCV 人脸检测基于Haar级联 | 47:11 | [link](https://www.bilibili.com/video/BV18z411e7VJ) |
| 1261 | - | - | 17-1 轻松学 OpenCV 基于dlib在图片上进行人脸检测 | 22:37 | [link](https://www.bilibili.com/video/BV1PK411W7pF) |
| 1262 | - | - | 17-2 轻松学 OpenCV 基于dlib通过摄像头进行实时人脸检测 | 14:38 | [link](https://www.bilibili.com/video/BV11Z4y1H7aS) |
| 1263 | - | - | 18-1 轻松学 OpenCV  基于dlib进行人脸关键点检测( 图片 ) | 26:07 | [link](https://www.bilibili.com/video/BV1Bk4y1z7rE) |
| 1264 | - | - | 18-2 轻松学OpenCV 基于dlib进行人脸关键点检测 (摄像头) | 16:48 | [link](https://www.bilibili.com/video/BV19A411v7QS) |
| 1265 | - | - | 18-3 轻松学OpenCV 基于face_recognition进行人脸关键点检测 | 29:58 | [link](https://www.bilibili.com/video/BV1ez4y1Q7sD) |
| 1266 | - | - | 19-1 轻松学OpenCV 基于dlib进行人脸跟踪 | 19:18 | [link](https://www.bilibili.com/video/BV1pK4y147Fj) |
| 1267 | - | - | 19-2 轻松学OpenCV 基于dlib进行人脸跟踪(补充) | 15:29 | [link](https://www.bilibili.com/video/BV1Pz4y1R7iB) |
| 1268 | - | - | 19-3 轻松学OpenCV 基于dlib进行目标跟踪 | 38:44 | [link](https://www.bilibili.com/video/BV1cv411B7yN) |
| 1269 | - | - | 20-1 轻松学OpenCV 基于dlib进行人脸识别( 图片检测 ） | 61:17 | [link](https://www.bilibili.com/video/BV1DZ4y1H7RM) |
| 1270 | - | - | 20-2 轻松学OpenCV 基于face_recognition进行人脸识别 ( 摄像头 ) | 43:51 | [link](https://www.bilibili.com/video/BV1h5411Y7d8) |
| 1271 | - | - | 【极速入门】DeepSeek Harness上手实战指南！架构原理、项目实操、插件开发全栈精讲！赠全套知识库、Skills、桌面端应用与插件管理器！ | 135:02 | [link](https://www.bilibili.com/video/BV1tTbk6zE4C) |
| 1272 | - | - | 从零手搓工业级知识库！DeepSeek Harness智能体开发实战！Skills+插件+Agent预设全栈精讲，Agent设计、开发、部署、优化全流程实操！ | 141:14 | [link](https://www.bilibili.com/video/BV1Hf8A6sEbN) |
| 1273 | - | - | 用好插件，性能暴涨！多Agent系统+永久记忆+提示优化+OpenDesign+TUI等，10大必装插件助你的DeepSeek Harness如虎添翼！ | 12:17 | [link](https://www.bilibili.com/video/BV1eU836PEkF) |
| 1274 | - | - | 桌面端+插件商店+视觉增强，DeepSeek Harness Studio开源上线！一键选配管理插件，原生视觉能力增强，自动版本更新，0代码彻底掌控DSH！ | 3:26 | [link](https://www.bilibili.com/video/BV19Hb16dExu) |
| 1275 | - | - | DeepSeek Harness上手流程+入门导读！国产版Codex&Claude Code重磅开源！ | 8:43 | [link](https://www.bilibili.com/video/BV1P9gs6zEpz) |
| 1276 | - | - | 保姆级DeepSeek Harness部署与上手指南！DeepSeek版Codex&Claude Code，DSH完整部署&使用&调用&开发流程详解！ | 4:59 | [link](https://www.bilibili.com/video/BV1hfgW6jEVr) |
| 1277 | - | - | 架构解读+部署上手+插件使用，DeepSeek Harness全方位深度解析！基座性能持平Codex，高度灵活插件系统定义下一代Agent开发范式！ | 9:23 | [link](https://www.bilibili.com/video/BV1Lyuf6SETd) |
| 1278 | - | - | 效率翻倍，效果追平！DeepSeek Harness VS Codex，Agent性能全方位深度对比评测！ | 6:19 | [link](https://www.bilibili.com/video/BV1gduf6GEbZ) |
| 1279 | - | - | 0代码+配视觉！DeepSeek Harness桌面版安装使用，自带视觉增强与背景切换，保姆级上手使用流程详解！ | 46:22 | [link](https://www.bilibili.com/video/BV1aPgK6cEgj) |
| 1280 | - | - | 顶级体验！DeepSeek V4 Vision多模态模型介绍与效果实测！DeepSeek V4-Flash-Vision-Exp重磅发布！ | 6:15 | [link](https://www.bilibili.com/video/BV1sh8i6XE49) |
| 1281 | - | - | Token自由！单卡5090部署满血DeepSeek V4 Flash！32G显存运行Opus 4.8级大模型，FreeToken项目CPU+GPU混合推实战！ | 7:19 | [link](https://www.bilibili.com/video/BV1BuhG6CEjD) |
| 1282 | - | - | DeepSeek-V4-Pro正式版深度评测！11项工业场景全方位测评，Agentic Coding、前端审美、物理理解、Agent开发全面追平Fable 5！ | 5:15 | [link](https://www.bilibili.com/video/BV1Q2g76cENE) |
| 1283 | - | - | DeepSeek-V4-Pro正式版接Codex配视觉能力！0代码0网络门槛，Codex App、CLI双端环境实现，多隔离环境切换与配置管理，FF-Codex | 6:17 | [link](https://www.bilibili.com/video/BV1vegL6hEtA) |
| 1284 | - | - | 性能评测+上手解读！DeepSeek-V4-Pro开源新王，Agentic coding&推理&长程工具调用全面硬刚Fable 5！ | 4:34 | [link](https://www.bilibili.com/video/BV1bSgL6nEwR) |
| 1285 | - | - | DeepSeek Harness工作流分享！精美前端开发、AI PPT&视频制作实用工作流实践，Agent预设Preset上手进阶实战！ | 7:34 | [link](https://www.bilibili.com/video/BV1b68d6EEhG) |
| 1286 | - | - | 【面试八股】大模型微调与RAG该如何选？面试满分回答模板+底层原理精讲，直接背！秋招求职必备！ | 6:17 | [link](https://www.bilibili.com/video/BV12bYszLEY5) |
| 1287 | - | - | 【面试八股】如何估算大模型微调所需硬件？一个公式搞定！附面试满分答案模板 / MOE架构模型 / 微调预算有限如何分配资源 | 6:47 | [link](https://www.bilibili.com/video/BV19WeAzAEPJ) |
| 1288 | - | - | 【面试八股】PPO与GRPO算法原理对比分析，大模型强化学习微调必考，2步做出满分答卷，拿下高薪offer！ / 强化学习算法原理 / 高效微调算法原理 | 7:48 | [link](https://www.bilibili.com/video/BV1MGeVzHEB4) |
| 1289 | - | - | 【面试八股】如何进行多机多卡大模型微调？分布式训练满分答卷，让你的offer率提升80%！ / DeepSpeed / PyTorch Distributed | 6:22 | [link](https://www.bilibili.com/video/BV1xCY9zbE6b) |
| 1290 | - | - | 【面试八股】如何进行大模型多模态微调？10+算法工程经验分享，你也能写出满分答案！ / LoRA / QLoRA / 高效微调 | 4:30 | [link](https://www.bilibili.com/video/BV1hdebzTE3g) |
| 1291 | - | - | 【面试八股】专业领域微调数据集如何准备？11步工程化构建环节，适配面试 & 企业项目落地！/ 数据预处理 / 微调效果评估 | 6:45 | [link](https://www.bilibili.com/video/BV1RmebzkEyV) |
| 1292 | - | - | 【面试八股】如何评估大模型微调效果？人工+自动化评估，面试官听完点头的企业级评估方案！ / 构建模型评估数据集 / EvalScope自动构建数据集 | 5:25 | [link](https://www.bilibili.com/video/BV1h5ebzKEbA) |
| 1293 | - | - | 【面试八股】Qwen3的GSPO算法原理是什么？国产T0大模型核心技术精讲，0基础也能手撕前沿算法 / GRPO VS GSPO / PPO长度归一化 | 7:35 | [link](https://www.bilibili.com/video/BV1tNh1zvEnX) |
| 1294 | - | - | 【面试八股】如何通过微调提升Agent性能？Claude Code也在用的技术思路，自动化生成最优工具调用策略 / 指令微调 / 强化学习 / 奖励函数设计 | 5:18 | [link](https://www.bilibili.com/video/BV1ChhyzZEDv) |
| 1295 | - | - | 真神还是造假？GPT-5 VS Claude 4.1编程性能对比评测！全网首发GPT-5工业级实战性能评测，代码能力&Agent性能全方位深度测评！ | 10:28 | [link](https://www.bilibili.com/video/BV1kLtmzREMr) |
| 1296 | - | - | GPT-5深度解读与性能评测！编程&Agent性能全面超越Claude 4.1？实测&揭秘地表最强大模型核心功能特性！ | 10:51 | [link](https://www.bilibili.com/video/BV18YtCzoEue) |
| 1297 | - | - | GPT-5发布会4分钟速览！定价、性能…一次看完！GPT-5你需要知道的都在这了 | 6:35 | [link](https://www.bilibili.com/video/BV1ggtkz9EKs) |
| 1298 | - | - | LangGraph&LangChain智能体开发极速入门！前端对话+NL2SQL+Python代码解释器，前后端分离部署+运行状态实时追踪全流程实战！ | 11:52 | [link](https://www.bilibili.com/video/BV1Nx38zMEyi) |
| 1299 | - | - | 工业级智能体开发实践，LangChain从零入门与智能体开发实战！RAG知识库检索、MCP智能体开发、数据分析智能体搭建全领域实战！从零学会LangChain！ | 325:10 | [link](https://www.bilibili.com/video/BV1pYKgzAE5C) |
| 1300 | - | - | 超越LangChain！LangGraph快速入门与智能体开发实战！工业级智能体开发、部署、运维、前端对话全流程实践，NL2SQL、Python代码解释器开发！ | 275:01 | [link](https://www.bilibili.com/video/BV1Kx3CzyE6Q) |
| 1301 | - | - | 最热门智能体开发技术栈，最低零代码开发企业级Agent！LangChain&LangGraph+MCP技术实战，双向MCP接入与封装双向开发实践！ | 142:37 | [link](https://www.bilibili.com/video/BV1bzMdzkERM) |
| 1302 | - | - | MCP技术开发入门实战！DeepSeek、ollama、vLLM接入MCP，从零手撕代码搭建MCP Client与Server！MCP完整技术实战！ | 115:15 | [link](https://www.bilibili.com/video/BV1NLXCYTEbj) |
| 1303 | - | - | MCP企业级智能体开发实战！知识库问答系统+AI数据分析智能体项目实战！独家提供MCP常用工作流+通用开发模版+外部工具调用优化函数 | 132:56 | [link](https://www.bilibili.com/video/BV1n1ZuYjEzf) |
| 1304 | - | - | 零门槛接入MCP！Cursor、阿里云百炼、Open-WebUI、Cherry Studio接入10大最热门MCP工具实战流程！零门槛搭建专属智能体应用！ | 123:09 | [link](https://www.bilibili.com/video/BV1dCo7YdEgK) |
| 1305 | - | - | DeepSeek v3本地部署与调用实战｜vLLM、SGLang、LMDeploy+DeepSeek v3部署调用实战 | 33:40 | [link](https://www.bilibili.com/video/BV1jjwVe4EKn) |
| 1306 | - | - | DeepSeek-v3调用指南与Function calling技术实战｜DeepSeek v3模型参数详解与Tool Use功能实战 | 97:25 | [link](https://www.bilibili.com/video/BV1JuwVewELc) |
| 1307 | - | - | 【全网独家】手动复现DeepSeek v3！从零训练Mini DeepSeek v3！模型预训练+全量指令微调+DPO强化学习微调全流程实战 | 120:14 | [link](https://www.bilibili.com/video/BV1KtwueYE54) |
| 1308 | - | - | DeepSeek v3搭建Multi-Agent技术入门实战｜DeepSeek v3+OpenAI Swarm技术实战 | 60:04 | [link](https://www.bilibili.com/video/BV1T8czeSEf1) |
| 1309 | - | - | DeepSeek v3+GraphRAG技术实战｜DeepSeek v3知识图谱检索增强技术实战 | 44:01 | [link](https://www.bilibili.com/video/BV1Xwc6eoEW5) |
| 1310 | - | - | 【保姆级】DeepSeek R1本地部署与调用指南｜transformer、Ollama、vLLM、LMDeploy、SGLang部署与调用R1与蒸馏模型组 | 54:58 | [link](https://www.bilibili.com/video/BV19kFoe6Ef7) |
| 1311 | - | - | DeepSeek R1 API调用实战！DeepSeek R1模型参数详解与模型功能介绍｜自动编程、自动机器学习项目入门实战 | 23:52 | [link](https://www.bilibili.com/video/BV1UyfGYqE28) |
| 1312 | - | - | 借助DeepSeek R1进行模型蒸馏，模型蒸馏入门实战！从零训练DeepSeek R1 Distill模型｜模型蒸馏技术实战 | 79:22 | [link](https://www.bilibili.com/video/BV1X1FoeBEgW) |
| 1313 | - | - | 【最佳方案】DeepSeek R1搭建本地知识库问答系统｜DeepSeek+Ollama+RAG本地知识库问答实战｜AnythingLLM快速部署与应用实战 | 47:16 | [link](https://www.bilibili.com/video/BV12qF2ePEDa) |
| 1314 | - | - | 新年巨献！DeepSeek Janus Pro重磅开源！文生图+图像识别，统一多模态大模型奠基之作！超越DALL-E 3、SD3 Medium | 25:10 | [link](https://www.bilibili.com/video/BV15kFseHEQ5) |
| 1315 | - | - | DeepSeek新年巨献！Janus Pro本地部署与调用实战！图像识别+文生图统一多模态大模型本地部署与调用流程详解！ | 34:13 | [link](https://www.bilibili.com/video/BV1ZqFse9Egc) |
| 1316 | - | - | 【全网独家】训练定制化DeepSeek R1！零基础DeepSeek R1高效微调实战｜知识灌注+对话风格微调，推理模型+Cot数据集微调实战！ | 111:26 | [link](https://www.bilibili.com/video/BV1YjN8eGE1H) |
| 1317 | - | - | 【全网最强】DeepSeek R1论文逐段精读与训练流程代码复现｜R1强化学习训练流程详解、模型蒸馏方法介绍｜GRPO原理介绍与代码复现 | 162:26 | [link](https://www.bilibili.com/video/BV1n9NfezErB) |
| 1318 | - | - | 联网+本地知识问答+外部工具调用+代码解释器+多用户并发+多模型切换，DeepSeek+Open-WebUI终极部署指南！ | 109:52 | [link](https://www.bilibili.com/video/BV1qU9AYLEe3) |
| 1319 | - | - | 最低0显存，独家Unsloth动态量化部署满血DeepSeek｜纯CPU推理、CPU+GPU混合推理、纯GPU推理方案详解｜企业级最佳部署方案 | 103:00 | [link](https://www.bilibili.com/video/BV1oePLezEZD) |
| 1320 | - | - | 【全网独家】训练定制化DeepSeek R1！零基础DeepSeek R1高效微调实战｜知识灌注+对话风格微调，推理模型+Cot数据集微调实战！ | 110:46 | [link](https://www.bilibili.com/video/BV1f8Are5Enz) |
| 1321 | - | - | 独家KTransformers技术实战，手把手跑通4090运行DeepSeek满血版，独家FastAPI脚本编写&Open-WebUI结合方案深度讲解 | 113:14 | [link](https://www.bilibili.com/video/BV1kyAke9EBA) |
| 1322 | - | - | DeepSeek正式发布DualPipe，梁文峰亲自带队研发神级双向管道并行算加速，毫秒级榨干GPU性能！ | 6:28 | [link](https://www.bilibili.com/video/BV1Gj9AYMEki) |
| 1323 | - | - | DeepSeek重磅开源DeepGEMM矩阵加速库，全球唯一FP8超级矩阵加速器！2.7倍提升矩阵乘法计算效率！ | 4:43 | [link](https://www.bilibili.com/video/BV1KJP7eZE2F) |
| 1324 | - | - | DeepSeek重磅开源DeepEP，大模型训练&推理效率暴涨！粉碎算力垄断，重塑MoE模型训练新范式！ | 4:53 | [link](https://www.bilibili.com/video/BV1LXPYeHEwB) |
| 1325 | - | - | 不负众望，Deepseek又开源封神！FlashMLA推理速度怒飙3倍！工业级加速库改写vLLM、SGLang技术规范 | 4:11 | [link](https://www.bilibili.com/video/BV1jdPxeKEPV) |
| 1326 | - | - | DeepSeek开源周压轴发布3FS，全球唯一大模型分布式文件管理系统，6TiB/s巨量吞吐性能，开辟训练新篇章！ | 5:54 | [link](https://www.bilibili.com/video/BV1Xh93YfEV1) |
| 1327 | - | - | 比肩o1！DeepSeek R1全面解析！价格比OpenAI o1便宜50倍！ / 1.5B小模型代码能力赶超GPT4o / 小尺寸推理模型企业可本地部署 | 6:52 | [link](https://www.bilibili.com/video/BV1UBwbe4E1D) |
| 1328 | - | - | 【深度】DeepSeek v3性能评测与技术解析｜DeepSeek v3为何是技术人首选模型｜颠覆当前大模型技术格局 | 11:17 | [link](https://www.bilibili.com/video/BV18Ccie5Esy) |
| 1329 | - | - | 2025大模型最强求职指南！整理全网2万份JD，一手数据信息揭秘求职真相！ | 12:47 | [link](https://www.bilibili.com/video/BV18JreYpE5Q) |
| 1330 | - | - | 【深度】2024大模型年度总结与2025技术展望！Agent智能体迎来全面爆发，大模型技术“黄金十年”即将到来！ | 20:29 | [link](https://www.bilibili.com/video/BV1Xn6nYnEnr) |
| 1331 | - | - | 不止会解数学题！OpenAI o3即将开启AGI新时代！详解o3的现实应用与深远影响 | 10:50 | [link](https://www.bilibili.com/video/BV1abCaYxEpp) |
| 1332 | - | - | OpenAI发布会总结与深度解读：AGI之路天堑变通途！ | 11:08 | [link](https://www.bilibili.com/video/BV1YZCNYDEzt) |
| 1333 | - | - | AI视频生成终极之战！谷歌Veo 2正面硬刚OpenAI Sora！ | 5:48 | [link](https://www.bilibili.com/video/BV1YVkMYsEq5) |
| 1334 | - | - | 万元服务器运行满血DeepSeek！全网最全低成本部署方案+硬件采购避坑指南！KTransformers方案+Unsloth动态量化方案详解！ | 13:36 | [link](https://www.bilibili.com/video/BV1K7ACewEfM) |
| 1335 | - | - | 零基础揭秘DeepSeek R1训练流程｜全网首发万字拆解R1复现流程｜多阶段GRPO强化学习训练、模型蒸馏技术揭秘！ | 15:48 | [link](https://www.bilibili.com/video/BV1ESAMepE4K) |
| 1336 | - | - | OpenAI年度发布会Day 1解读：o1满血版、o1 pro mode与ChatGPT Pro新品解读！ | 7:51 | [link](https://www.bilibili.com/video/BV1ufiYYuEpT) |
| 1337 | - | - | OpenAI年度发布会Day 1完整回放与实时解读！｜o1、o1Pro、ChatGPT Pro重磅发布！｜三位UP深夜团建解读发布会 | 21:56 | [link](https://www.bilibili.com/video/BV1GXiYYVEGa) |
| 1338 | - | - | OpenAI年度发布会前瞻解读，GPT5、Sora、Agent工具会发布么？ | 18:09 | [link](https://www.bilibili.com/video/BV1PuieYaEjT) |
| 1339 | - | - | OpenAI年度发布会Day2解读：强化学习微调与定制化o1模型震撼登场！开启Agent开发新时代！奥特曼：今年最大惊喜！ | 11:45 | [link](https://www.bilibili.com/video/BV1joirYkEB8) |
| 1340 | - | - | OpenAI发布会Day 2发布会完整回放与深度解读｜强化学习API震撼登场，定制化o1模型人人可得，Agent开发一夜变天！Sam：今年最大惊喜！ | 80:46 | [link](https://www.bilibili.com/video/BV1yfi6YHEQ4) |
| 1341 | - | - | OpenAI年度发布会一阶段汇总：o1 Pro、ChatGPT Pro、强化学习API新品解读【合集】 | 19:35 | [link](https://www.bilibili.com/video/BV1GAq5YZEeA) |
| 1342 | - | - | Sora来了！今日最新宣传片《合成青春》速览与解读！｜百人热舞+实体一致+物理遵循+专业运镜，Sora王者归来！ | 5:40 | [link](https://www.bilibili.com/video/BV1AjqHYAESa) |
| 1343 | - | - | OpenAI年度重磅！o1大模型快速入门与开发实战！｜o1 API调用流程、推理与上下文管理、自动编程与实体识别开发实战！ | 46:33 | [link](https://www.bilibili.com/video/BV1zWqHY4EjE) |
| 1344 | - | - | Sora重磅发布！无限时长一致+任意帧修改+物理遵循！OpenAI发布会Day 3深度解读！ | 6:17 | [link](https://www.bilibili.com/video/BV18EquYGEfo) |
| 1345 | - | - | Sora今日重磅上线！发布会完整解读、Sora演示与功能详解！ | 56:22 | [link](https://www.bilibili.com/video/BV1shquYPEds) |
| 1346 | - | - | Sora功能及价格全解！Sora今日重磅发布，再次颠覆多模态领域，不负期待！ | 14:14 | [link](https://www.bilibili.com/video/BV1rRqMYZERK) |
| 1347 | - | - | 在线Cursor来了！新版Canvas功能深度解读！ChatGPT在线文本&代码智能编辑器现已上线！ | 14:53 | [link](https://www.bilibili.com/video/BV1dYqyYUEVT) |
| 1348 | - | - | OpenAI Day 4发布会实况回放与深度解读！在线Cursor来了，新版Canvas重磅上线！ | 24:04 | [link](https://www.bilibili.com/video/BV1FpqyY4Eew) |
| 1349 | - | - | ChatGPT Canvas智能编程与智能文本编辑完整功能演示！OpenAI发布会Day 4，新版ChatGPT Canvas重磅上线！ | 17:47 | [link](https://www.bilibili.com/video/BV1B1qCYQEcK) |
| 1350 | - | - | OpenAI Day 7深度解读，ChatGPT Projects功能来袭，文本&代码生产力迎来重大突破！ | 10:08 | [link](https://www.bilibili.com/video/BV1TfB3Y2EUS) |
| 1351 | - | - | OpenAI发布会Day 7发布会回放与解读：ChatGPT Projects功能重磅上线！新一代ChatBot生产力标杆！ | 29:14 | [link](https://www.bilibili.com/video/BV1pbB3YTE33) |
| 1352 | - | - | ChatGPT操控APP效果演示：一键操控Cursor及其他文本与代码编辑器！ | 31:25 | [link](https://www.bilibili.com/video/BV1e3kkY9E49) |
| 1353 | - | - | OpenAI Day 11：ChatGPT操控指定APP功能上线！发布会实况与深度解读～ | 49:41 | [link](https://www.bilibili.com/video/BV1eVkkYpEAu) |
| 1354 | - | - | ChatGPT APP协作功能介绍与解读！一键配对APP完成操控！Computer use雏形功能上线 | 13:00 | [link](https://www.bilibili.com/video/BV1pikkYqEbU) |
| 1355 | - | - | OpenAI Day 10：打电话、发短信找ChatGPT聊天｜OpenAI发布会Day 10回放与解读 | 18:46 | [link](https://www.bilibili.com/video/BV13DkPYCEHb) |
| 1356 | - | - | ChatGPT创意功能上线！打电话、发短信找ChatGPT聊天～ | 5:21 | [link](https://www.bilibili.com/video/BV1oHkNYHETB) |
| 1357 | - | - | ChatGPT Search发布会完整解读与实况回放｜ChatGPT完整体正式发布，发布会实况解读 | 18:16 | [link](https://www.bilibili.com/video/BV1zSkGYjEWA) |
| 1358 | - | - | ChatGPT完整体来袭，新版互联网Search功能重磅上线，免费可用！｜OpenAI发布会Day 8深度解读 | 9:47 | [link](https://www.bilibili.com/video/BV1nmkGYmEcf) |
| 1359 | - | - | o3推理大模型王炸登场 Agent将获最强大脑！数学编程能力大幅提升、推理新时代来临 ｜ OpenAI发布会Day12 | 7:37 | [link](https://www.bilibili.com/video/BV17wkQYQEaU) |
| 1360 | - | - | 全程高能！o3大模型发布会实况与深度解读！OpenAI Day12完整录像与技术解说 | 77:07 | [link](https://www.bilibili.com/video/BV1hikDYzELp) |
| 1361 | - | - | Agent智能体概念详解与2025大模型岗位技能要求分析｜2025Agent最热门开发方向分析 | 25:31 | [link](https://www.bilibili.com/video/BV1TjBnYTETX) |
| 1362 | - | - | 零基础Agent智能体开发基础理论详解！记忆、工具、规划、执行四大功能模块设计原理保姆级介绍！ | 24:47 | [link](https://www.bilibili.com/video/BV1CcBJYtEne) |
| 1363 | - | - | 12项Agent智能体开发框架入门与选型！｜Coze、Dify、LangChain、LangGraph、AutoGen等工具对比分析与选型建议！ | 23:10 | [link](https://www.bilibili.com/video/BV16NBJYRE3s) |
| 1364 | - | - | 当前主流各类GPU分类命名及适用场景介绍｜RTX系列、A系列、H系列、中国区特供版GPU分类命名规则及性能介绍 | 6:55 | [link](https://www.bilibili.com/video/BV1HpBEYsEzW) |
| 1365 | - | - | 大模型GPU性能与性价比天梯图详解！各类GPU的大模型训练与推理性能对比，以及主流GPU性价比分析！ | 9:33 | [link](https://www.bilibili.com/video/BV1daBEY7ESw) |
| 1366 | - | - | 各类大模型运行GPU配置推荐！各尺寸大模型训练、微调、推理所需GPU配置推荐！ | 7:26 | [link](https://www.bilibili.com/video/BV1GZB7YrE2Y) |
| 1367 | - | - | 个人、实验室、企业大模型项目GPU服务器推荐配置及报价！各类大模型项目GPU完整配置清单详解 | 6:29 | [link](https://www.bilibili.com/video/BV15oB7YGEjG) |
| 1368 | - | - | GLM4实战教程（1）：GLM系列在线大模型生态入门介绍 | 34:37 | [link](https://www.bilibili.com/video/BV1gK4y1B7oq) |
| 1369 | - | - | GLM4实战教程（2）：GLM4 API-KEY获取与本地调用 | 32:58 | [link](https://www.bilibili.com/video/BV1ja4y1y7Aj) |
| 1370 | - | - | GLM4实战教程（3）：GLM模型全参数讲解 | 59:18 | [link](https://www.bilibili.com/video/BV1he411n7nS) |
| 1371 | - | - | GLM4实战教程（4）：GLM模型Message队列设置方法与模型身份设置 | 21:23 | [link](https://www.bilibili.com/video/BV1oN4y1n7QG) |
| 1372 | - | - | 大模型最大风口Agent是什么？详解Agent在医疗、教育、生产力、个人助理、娱乐、电商领域应用现状 | 14:54 | [link](https://www.bilibili.com/video/BV1LN4y1a7gB) |
| 1373 | - | - | 团队自研Agent：MateGen重磅上线！定制知识库+本地代码解释器+联网+追踪debug！伴你高效学习&工作 | 17:16 | [link](https://www.bilibili.com/video/BV1WN41157QT) |
| 1374 | - | - | 开源大模型 VS GPT，哪个最适合做Agent？零基础入门Agent开发学习路线推荐！ | 16:17 | [link](https://www.bilibili.com/video/BV11u4y1M73s) |
| 1375 | - | - | 全球最前沿GPT系Agent开发都需要哪些技能？详解GPT系Agent开发必备技能学习路线！ | 8:22 | [link](https://www.bilibili.com/video/BV1mi4y1e7kd) |
| 1376 | - | - | 国内商用Agent开发，要学习哪些开源大模型？详解开源大模型开发Agent入门学习路径！ | 13:31 | [link](https://www.bilibili.com/video/BV1ij411W7fp) |
| 1377 | - | - | Agent概念详解！为什么Agent才是大模型的未来？数据分析&机器学习Agent到底长啥样？ | 32:13 | [link](https://www.bilibili.com/video/BV1w94y177et) |
| 1378 | - | - | Agent开发必备技能详解！零基础入门Agent开发学习路线精讲！｜在线大模型&开源大模型技术学习路线 | 38:09 | [link](https://www.bilibili.com/video/BV1MN4y1a7iz) |
| 1379 | - | - | 零基础迅速掌握Agent开发流程！Agent通用开发范式详解！｜Agent模块化开发流程精讲 | 23:22 | [link](https://www.bilibili.com/video/BV1MN41157gh) |
| 1380 | - | - | AI Agent开发新范式，GPTs功能详解！｜打造个人专属ChatGPT | 28:19 | [link](https://www.bilibili.com/video/BV1az4y1w7nH) |
| 1381 | - | - | 手把手创建一个专属GPTs！打造全自动数据分析Agent！｜以对话的方式高效开发AI Agent | 31:08 | [link](https://www.bilibili.com/video/BV1XG411S7Df) |
| 1382 | - | - | GPTs进阶功能Actions使用方法详解！将外部工具API接入GPTs，打造功能专属ChatGPT | 39:32 | [link](https://www.bilibili.com/video/BV1qC4y127js) |
| 1383 | - | - | 全自动数据分析报表GPTs功能测试！｜专属GPTs发布与功能测试 | 12:15 | [link](https://www.bilibili.com/video/BV1qw411N7qf) |
| 1384 | - | - | ChatGLM3零基础安装部署流程（上）｜ChatGLM3零基础代码调用流程｜ChatGLM3 Web应用调用方法 | 28:59 | [link](https://www.bilibili.com/video/BV1gN4y1r7RX) |
| 1385 | - | - | ChatGLM3零基础安装部署流程（下）｜ChatGLM3零基础代码调用流程｜ChatGLM3 Web应用调用方法 | 27:05 | [link](https://www.bilibili.com/video/BV18M411Q7Pp) |
| 1386 | - | - | ChatGLM3快速入门，全新API调用方法详解｜Messages参数功能介绍 | 28:21 | [link](https://www.bilibili.com/video/BV18c411d7Hd) |
| 1387 | - | - | ChatGLM3推理性能快速评测｜ChatGLM3 VS GPT系模型性能对比 | 25:57 | [link](https://www.bilibili.com/video/BV1BG411X7Hk) |
| 1388 | - | - | ChatGLM3工具调用function calling功能详解｜如何让ChatGLM3接入外部工具｜ChatGLM3 Agent开发入门 | 24:46 | [link](https://www.bilibili.com/video/BV1V84y1971r) |
| 1389 | - | - | ChatGLM3 Agent开发入门｜Function calling全自动实现｜AI Agent开发入门 | 26:00 | [link](https://www.bilibili.com/video/BV1Wy4y1c7oA) |
| 1390 | - | - | 进步显著！ChatGLM3重磅上线！深度详解新模型性能与新功能 | 34:48 | [link](https://www.bilibili.com/video/BV14N4y1674J) |
| 1391 | - | - | ChatGLM3全新消息队列功能介绍！接入先进多角色对话功能！ | 15:09 | [link](https://www.bilibili.com/video/BV1fg4y197xM) |
| 1392 | - | - | ChatGLM3全新Function calling功能详解！开启AI Agent之路的最核心功能！ | 22:21 | [link](https://www.bilibili.com/video/BV1K94y157gd) |
| 1393 | - | - | 如何借助大模型冲击Kaggle金牌？ | 26:48 | [link](https://www.bilibili.com/video/BV1i84y127sB) |
| 1394 | - | - | 自动机器学习建模AI Agent功能架构详解 | 29:07 | [link](https://www.bilibili.com/video/BV1MN411t79i) |
| 1395 | - | - | 自动机器学习建模 AI Agent入门实操 | 26:25 | [link](https://www.bilibili.com/video/BV1oG41117oq) |
| 1396 | - | - | 特征衍生全技术路径精讲 / 机器学习 / 特征工程 | 17:21 | [link](https://www.bilibili.com/video/BV1aC4y1d7GD) |
| 1397 | - | - | 特征筛选全技术路径精讲 | 10:59 | [link](https://www.bilibili.com/video/BV1Kw411k7XT) |
| 1398 | - | - | 模型融合全技术地图讲解 | 16:26 | [link](https://www.bilibili.com/video/BV19B4y1Z7dK) |
| 1399 | - | - | GPT系AI应用开发实战01: GPT模型Function calling功能入门介绍 | 27:18 | [link](https://www.bilibili.com/video/BV1XF411f7qF) |
| 1400 | - | - | GPT系AI应用开发实战02: Function calling相关参数详解 | 30:32 | [link](https://www.bilibili.com/video/BV16X4y1L7H2) |
| 1401 | - | - | GPT系AI应用开发实战03: Function calling开发流程详解 | 26:02 | [link](https://www.bilibili.com/video/BV1f8411d73j) |
| 1402 | - | - | GPT系AI应用开发实战04: GPT模型调用外部工具API方法介绍 | 29:17 | [link](https://www.bilibili.com/video/BV1w14y1q7yr) |
| 1403 | - | - | GPT系AI应用开发实战05: 基于GPT模型的天气查询应用开发实战 | 16:34 | [link](https://www.bilibili.com/video/BV1Nu4y1z7ku) |
| 1404 | - | - | GPT系AI应用开发实战06: AI应用开发入门: 谷歌云与API库入门介绍 | 22:07 | [link](https://www.bilibili.com/video/BV1hH4y1D7qF) |
| 1405 | - | - | GPT系AI应用开发实战07: AI应用开发入门: 谷歌云 Auth2.0 授权方法 | 28:30 | [link](https://www.bilibili.com/video/BV17p4y1j75v) |
| 1406 | - | - | GPT系AI应用开发实战08: 基于Gmail API的AI邮件系统开发实战1 | 15:04 | [link](https://www.bilibili.com/video/BV1rj411C7G4) |
| 1407 | - | - | GPT系AI应用开发实战09: 基于Gmail API的AI邮件系统开发实战2 | 27:26 | [link](https://www.bilibili.com/video/BV1gH4y1Q7iy) |
| 1408 | - | - | GPT系AI应用开发实战10: 热门AI应用开发方向解读 | 26:24 | [link](https://www.bilibili.com/video/BV1Dz4y1j7vH) |
| 1409 | - | - | GPT系AI应用开发实战11: 智能搜索问答机器人项目介绍与开发思路 | 29:52 | [link](https://www.bilibili.com/video/BV1Qp4y1A7X9) |
| 1410 | - | - | GPT系AI应用开发实战12: 谷歌搜索API获取与使用方法 / 将谷歌搜索接入GPT大模型 | 28:53 | [link](https://www.bilibili.com/video/BV16u411c7Nd) |
| 1411 | - | - | GPT系AI应用开发实战13: 构建基于GitHub的搜索问答机器人 | 30:32 | [link](https://www.bilibili.com/video/BV1jy4y1F7QW) |
| 1412 | - | - | GPT大模型技术实战教程01: OpenAI官网使用指南与API-Key获取 | 29:15 | [link](https://www.bilibili.com/video/BV1YM4y1x76K) |
| 1413 | - | - | GPT大模型技术实战教程02: GPT大模型API-Key使用方法&Jupyter本地调用 | 16:09 | [link](https://www.bilibili.com/video/BV1RV411T754) |
| 1414 | - | - | GPT大模型技术实战教程03: Completion模型与Chat模型入门介绍 | 16:04 | [link](https://www.bilibili.com/video/BV1M8411Q7Kv) |
| 1415 | - | - | GPT大模型技术实战教程04: Completion模型API使用方法详解 | 25:29 | [link](https://www.bilibili.com/video/BV1fP411k7vv) |
| 1416 | - | - | GPT大模型技术实战教程05:  Completion模型调参实践 | 14:46 | [link](https://www.bilibili.com/video/BV1zz4y147FZ) |
| 1417 | - | - | GPT大模型技术实战教程06: 基于Completion手动创建可自定义聊天风格的对话机器人 | 14:25 | [link](https://www.bilibili.com/video/BV1U14y197hp) |
| 1418 | - | - | GPT大模型技术实战教程07: GPT最新Chat类模型入门介绍 | 23:09 | [link](https://www.bilibili.com/video/BV1Vk4y1V76h) |
| 1419 | - | - | GPT大模型技术实战教程08：Chat模型功能介绍与发展现状 | 19:35 | [link](https://www.bilibili.com/video/BV1LN411Y7hW) |
| 1420 | - | - | GPT大模型技术实战教程09: GPT-4 API使用方法&Chat模型API详解 | 36:15 | [link](https://www.bilibili.com/video/BV1f14y1z7HS) |
| 1421 | - | - | GPT大模型技术实战教程10: GPT-4 API核心参数Message使用方法详解 | 25:32 | [link](https://www.bilibili.com/video/BV1vc411F7vi) |
| 1422 | - | - | 【入门】OpenAI在线大模型生态介绍｜大模型技术入门课程｜GPT&DALL·E&Codex&Embedding模型介绍 | 27:15 | [link](https://www.bilibili.com/video/BV15P411z7pU) |
| 1423 | - | - | 【入门】开源大模型生态与ChatGLM-6B大模型介绍｜最强中文大模型GLM介绍｜LLM开源大模型概览 | 33:35 | [link](https://www.bilibili.com/video/BV1Xg4y1N7kM) |
| 1424 | - | - | 【入门】大语言模型常用微调框架介绍｜LoRA&Prefix-Tuning&Prompt-Tuning&P-Tuning v2&RLHF微调原理简介 | 33:33 | [link](https://www.bilibili.com/video/BV1Yc411g78a) |
| 1425 | - | - | 【入门】AI应用开发范式LangChain零基础入门介绍｜LangChain六大功能模块解释｜基于LLM的AI开发流程与开发工具 | 25:38 | [link](https://www.bilibili.com/video/BV1gz4y1e7im) |
| 1426 | - | - | 机器学习面试热点问题精讲·Part 1.机器学习基础篇｜2023冲刺春招算法岗｜面试必考机器学习热点问题｜全原理讲解&附赠标准问答模版 | 45:49 | [link](https://www.bilibili.com/video/BV1oo4y167CV) |
| 1427 | - | - | 机器学习面试热点问题精讲·Part 2.经典机器学习篇｜2023冲刺春招算法岗｜面试必考机器学习热点问题｜全原理讲解&附赠标准问答模版 | 15:10 | [link](https://www.bilibili.com/video/BV1XT411v7WK) |
| 1428 | - | - | 机器学习面试热点问题精讲·Part 3.集成学习篇｜2023冲刺春招算法岗｜面试必考机器学习热点问题｜全原理讲解&附赠标准问答模版 | 24:22 | [link](https://www.bilibili.com/video/BV17j411g7PX) |
| 1429 | - | - | 机器学习面试热点问题精讲·Part 4.特征工程篇｜2023冲刺春招算法岗｜面试必考机器学习热点问题｜全原理讲解&附赠标准问答模版 | 35:13 | [link](https://www.bilibili.com/video/BV1pT411v7gD) |
| 1430 | - | - | 机器学习面试热点问题精讲·Part 5.模型融合篇｜2023冲刺春招算法岗｜面试必考机器学习热点问题｜全原理讲解&附赠标准问答模版 | 41:57 | [link](https://www.bilibili.com/video/BV1c54y1u7DU) |
| 1431 | - | - | 【优化算法】无约束优化-概述 | 24:04 | [link](https://www.bilibili.com/video/BV1mP411C7ed) |
| 1432 | - | - | 【优化算法】线搜索方法-方向 | 22:15 | [link](https://www.bilibili.com/video/BV1iX4y1H7Ef) |
| 1433 | - | - | 【优化算法】线搜索方法-步长-精确搜索 | 13:36 | [link](https://www.bilibili.com/video/BV1H14y1R7Yo) |
| 1434 | - | - | 【优化算法】线搜索方法-步长-非确定性搜索 | 14:22 | [link](https://www.bilibili.com/video/BV1Gh411P7uw) |
| 1435 | - | - | 【优化算法】线搜索方法-步长-Armijo Condition | 10:36 | [link](https://www.bilibili.com/video/BV11N411m75b) |
| 1436 | - | - | 【优化算法】线搜索方法-步长-Glodstein Condition | 10:07 | [link](https://www.bilibili.com/video/BV1UF411X7Dh) |
| 1437 | - | - | 【优化算法】线搜索方法-步长-Wolfe Condition | 15:30 | [link](https://www.bilibili.com/video/BV1Nz4y1J7Wt) |
| 1438 | - | - | 【优化算法】线搜索方法-收敛性证明 | 30:13 | [link](https://www.bilibili.com/video/BV1Mh411P7VY) |
| 1439 | - | - | 【优化算法】收敛速度简介 | 14:15 | [link](https://www.bilibili.com/video/BV1FP411y7kx) |
| 1440 | - | - | 【优化算法】梯度下降法-总体介绍 | 18:32 | [link](https://www.bilibili.com/video/BV14h4y1E71v) |
| 1441 | - | - | 【优化算法】梯度下降法-基础补充-凸函数vs强凸函数vs严格凸函数（上） | 23:39 | [link](https://www.bilibili.com/video/BV1vs4y167rA) |
| 1442 | - | - | 【优化算法】梯度下降法-基础补充-凸函数vs强凸函数vs严格凸函数（下） | 12:33 | [link](https://www.bilibili.com/video/BV1Uj411o7XT) |
| 1443 | - | - | 【优化算法】梯度下降法-二次上界 | 26:02 | [link](https://www.bilibili.com/video/BV1Ek4y1P72N) |
| 1444 | - | - | 【优化算法】梯度下降法-凸函数的收敛性 | 30:28 | [link](https://www.bilibili.com/video/BV15m4y1n72Q) |
| 1445 | - | - | 【优化算法】梯度下降法-白老爹定理（上） | 18:20 | [link](https://www.bilibili.com/video/BV1Tg4y1w7jx) |
| 1446 | - | - | 【优化算法】梯度下降法-白老爹定理（下） | 32:31 | [link](https://www.bilibili.com/video/BV1MV4y1h7Va) |
| 1447 | - | - | 【优化算法】梯度下降法-强凸函数的收敛性分析（上） | 37:48 | [link](https://www.bilibili.com/video/BV1WW4y1o7aG) |
| 1448 | - | - | 【优化算法】梯度下降法-强凸函数的收敛性分析（下） | 17:50 | [link](https://www.bilibili.com/video/BV1mj411Z7br) |
| 1449 | - | - | 【优化算法】经典牛顿法-总体介绍 | 18:48 | [link](https://www.bilibili.com/video/BV1fX4y1J7jE) |
| 1450 | - | - | 【优化算法】经典牛顿法-收敛性分析 | 41:08 | [link](https://www.bilibili.com/video/BV1794y1q7Hz) |
| 1451 | - | - | 【强化学习】规划与学习-Dyna Architecture | 39:44 | [link](https://www.bilibili.com/video/BV1yT4y1U78Z) |
| 1452 | - | - | 【强化学习】规划与学习-算力聚焦 | 27:14 | [link](https://www.bilibili.com/video/BV1ar4y1p7ES) |
| 1453 | - | - | 【强化学习】规划与学习-决策时规划 | 33:35 | [link](https://www.bilibili.com/video/BV1cY4y1i785) |
| 1454 | - | - | 【强化学习】规划与学习-蒙特卡洛树搜索 MCTS | 30:14 | [link](https://www.bilibili.com/video/BV1s5411D7JT) |
| 1455 | - | - | 【强化学习】策略梯度方法-策略近似 | 25:10 | [link](https://www.bilibili.com/video/BV1MS4y1r7ta) |
| 1456 | - | - | 【强化学习】策略梯度方法-策略梯度定理 | 27:50 | [link](https://www.bilibili.com/video/BV18u411Q76q) |
| 1457 | - | - | 【强化学习】策略梯度方法-REINFORCE | 9:26 | [link](https://www.bilibili.com/video/BV1xb4y1W7Ye) |
| 1458 | - | - | 【强化学习】策略梯度方法-REINFORCE with Baseline & Actor-Critic | 10:21 | [link](https://www.bilibili.com/video/BV1RF411x7oS) |
| 1459 | - | - | 【强化学习】 时序差分-策略评估 | 10:56 | [link](https://www.bilibili.com/video/BV1wS4y1F7zn) |
| 1460 | - | - | 【强化学习】(SARSA) 时序差分-同轨策略TD控制 | 9:27 | [link](https://www.bilibili.com/video/BV1BS4y1r7cm) |
| 1461 | - | - | 【强化学习】(Q-Learning) 时序差分-离轨策略TD控制 | 7:26 | [link](https://www.bilibili.com/video/BV1cZ4y1C7Ma) |
| 1462 | - | - | 【强化学习】时序差分-期望SARSA | 13:40 | [link](https://www.bilibili.com/video/BV15L411T7LM) |
| 1463 | - | - | 【强化学习】蒙特卡洛方法-前情回顾 | 15:02 | [link](https://www.bilibili.com/video/BV1rF411J7Mw) |
| 1464 | - | - | 【强化学习】蒙特卡洛方法-策略评估 | 8:23 | [link](https://www.bilibili.com/video/BV1vm4y1Z7Ce) |
| 1465 | - | - | 【强化学习】蒙特卡洛方法-基于试探性出发假设的MC控制 | 9:05 | [link](https://www.bilibili.com/video/BV1N5411o7QD) |
| 1466 | - | - | 【强化学习】蒙特卡洛方法-同轨VS离轨 | 8:09 | [link](https://www.bilibili.com/video/BV1bS4y1C75M) |
| 1467 | - | - | 【强化学习】 蒙特卡洛方法-同轨策略MC控制 | 21:19 | [link](https://www.bilibili.com/video/BV1Ju4119794) |
| 1468 | - | - | 【强化学习】蒙特卡洛方法-离轨策略MC策略评估 | 18:41 | [link](https://www.bilibili.com/video/BV1EZ4y1R7r4) |
| 1469 | - | - | 【强化学习】 蒙特卡洛方法-离轨策略评估与控制 | 15:12 | [link](https://www.bilibili.com/video/BV1sS4y1C7tR) |
| 1470 | - | - | 序言 | 25:52 | [link](https://www.bilibili.com/video/BV1yk28YUEfs) |
| 1471 | - | - | 2012逻辑选择 | 116:07 | [link](https://www.bilibili.com/video/BV1sk28YSEXV) |
| 1472 | - | - | 2012论证有效性分析 | 12:01 | [link](https://www.bilibili.com/video/BV1Nk28YSEY4) |
| 1473 | - | - | 2012论说文 | 17:40 | [link](https://www.bilibili.com/video/BV1Nk28YSEtg) |
| 1474 | - | - | 2016逻辑选择 | 135:51 | [link](https://www.bilibili.com/video/BV1demgYjEVD) |
| 1475 | - | - | 2016-26 | 3:18 | [link](https://www.bilibili.com/video/BV1a4mVYUENE) |
| 1476 | - | - | 2016-27 | 3:04 | [link](https://www.bilibili.com/video/BV18amVYLEKG) |
| 1477 | - | - | 2016-28 | 1:52 | [link](https://www.bilibili.com/video/BV1uamVYjERx) |
| 1478 | - | - | 2016-29 | 3:37 | [link](https://www.bilibili.com/video/BV1bamVYLEoz) |
| 1479 | - | - | 2016-30 | 2:33 | [link](https://www.bilibili.com/video/BV18amVYLEKx) |
| 1480 | - | - | 2016-31 | 2:33 | [link](https://www.bilibili.com/video/BV18amVYLEwL) |
| 1481 | - | - | 2016-32 | 5:52 | [link](https://www.bilibili.com/video/BV18amVYLENz) |
| 1482 | - | - | 2016-33 | 1:27 | [link](https://www.bilibili.com/video/BV1KZmGYzEsj) |
| 1483 | - | - | 2016-34 | 1:14 | [link](https://www.bilibili.com/video/BV1bamVYLEoc) |
| 1484 | - | - | 2016-35 | 9:20 | [link](https://www.bilibili.com/video/BV1bamVYLEoM) |
| 1485 | - | - | 2016-36 | 3:40 | [link](https://www.bilibili.com/video/BV18amVYLEcz) |
| 1486 | - | - | 2016-37 | 2:49 | [link](https://www.bilibili.com/video/BV1SamVYLExM) |
| 1487 | - | - | 2016-38 | 6:47 | [link](https://www.bilibili.com/video/BV18amVYLEwo) |
| 1488 | - | - | 2016-39 | 4:36 | [link](https://www.bilibili.com/video/BV1SamVYLEiW) |
| 1489 | - | - | 2016-40 | 2:31 | [link](https://www.bilibili.com/video/BV1bamVYLEZi) |
| 1490 | - | - | 2016-41 | 4:00 | [link](https://www.bilibili.com/video/BV1bamVYLEZk) |
| 1491 | - | - | 2016-42 | 1:04 | [link](https://www.bilibili.com/video/BV18amVYLEA5) |
| 1492 | - | - | 2016-43、44 | 7:32 | [link](https://www.bilibili.com/video/BV18amVYLEPF) |
| 1493 | - | - | 2016-45 | 2:26 | [link](https://www.bilibili.com/video/BV1bamVYLEfa) |
| 1494 | - | - | 2016-46 | 4:33 | [link](https://www.bilibili.com/video/BV1gamVYjEwA) |
| 1495 | - | - | 2016-47 | 1:58 | [link](https://www.bilibili.com/video/BV18amVYLEMk) |
| 1496 | - | - | 2016-48 | 5:10 | [link](https://www.bilibili.com/video/BV18amVYjEvq) |
| 1497 | - | - | 2016-49 | 5:57 | [link](https://www.bilibili.com/video/BV1bamVYLEfZ) |
| 1498 | - | - | 2016-50 | 3:52 | [link](https://www.bilibili.com/video/BV18amVYLEAs) |
| 1499 | - | - | 2016-51 | 2:33 | [link](https://www.bilibili.com/video/BV1SamVYLEiR) |
| 1500 | - | - | 2016-52、53 | 6:33 | [link](https://www.bilibili.com/video/BV1SamVYLEtx) |
| 1501 | - | - | 2016-54、55 | 5:24 | [link](https://www.bilibili.com/video/BV1Q4mVYUEBB) |
| 1502 | - | - | 2016论证有效性分析 | 10:37 | [link](https://www.bilibili.com/video/BV1mB28YpE6F) |
| 1503 | - | - | 2016论说文 | 14:34 | [link](https://www.bilibili.com/video/BV1xk28YSEc1) |
| 1504 | - | - | 2019逻辑选择 | 134:57 | [link](https://www.bilibili.com/video/BV1Nk28YSExk) |
| 1505 | - | - | 2019-26 | 2:50 | [link](https://www.bilibili.com/video/BV14czXYhEx5) |
| 1506 | - | - | 2019-27 | 3:59 | [link](https://www.bilibili.com/video/BV12czXYhEDz) |
| 1507 | - | - | 2019-28 | 3:27 | [link](https://www.bilibili.com/video/BV1KczXYhEQV) |
| 1508 | - | - | 2019-29 | 2:06 | [link](https://www.bilibili.com/video/BV1xczXYhEXv) |
| 1509 | - | - | 2019-30&31 | 5:09 | [link](https://www.bilibili.com/video/BV11czXYbEtr) |
| 1510 | - | - | 2019-32 | 3:17 | [link](https://www.bilibili.com/video/BV1KczXYhEdo) |
| 1511 | - | - | 2019-33 | 3:21 | [link](https://www.bilibili.com/video/BV1KczXYhEdX) |
| 1512 | - | - | 2019-34 | 5:42 | [link](https://www.bilibili.com/video/BV1KczXYhEDF) |
| 1513 | - | - | 2019-35 | 2:32 | [link](https://www.bilibili.com/video/BV1KczXYhEWV) |
| 1514 | - | - | 2019-36 | 5:47 | [link](https://www.bilibili.com/video/BV1KczXYhERR) |
| 1515 | - | - | 2019-37 | 7:04 | [link](https://www.bilibili.com/video/BV1TFzXYwEid) |
| 1516 | - | - | 2019-38 | 7:28 | [link](https://www.bilibili.com/video/BV1TFzXYwEkA) |
| 1517 | - | - | 2019-39 | 11:16 | [link](https://www.bilibili.com/video/BV14FzXYwEq8) |
| 1518 | - | - | 2019-40 | 4:05 | [link](https://www.bilibili.com/video/BV14FzXYwEqM) |
| 1519 | - | - | 2019-41 | 5:30 | [link](https://www.bilibili.com/video/BV14FzXYwEqz) |
| 1520 | - | - | 2019-42 | 1:33 | [link](https://www.bilibili.com/video/BV1TFzXYwEzG) |
| 1521 | - | - | 2019-43 | 5:03 | [link](https://www.bilibili.com/video/BV1tFzXYwEAs) |
| 1522 | - | - | 2019-44 | 4:04 | [link](https://www.bilibili.com/video/BV1TFzXYwEvn) |
| 1523 | - | - | 2019-45 | 2:10 | [link](https://www.bilibili.com/video/BV1tFzXYwEAd) |
| 1524 | - | - | 2019-46 | 5:13 | [link](https://www.bilibili.com/video/BV14FzXYwEvw) |
| 1525 | - | - | 2019-47 | 3:00 | [link](https://www.bilibili.com/video/BV14FzXYwEv1) |
| 1526 | - | - | 2019-48 | 3:34 | [link](https://www.bilibili.com/video/BV1mFzXYwEP4) |
| 1527 | - | - | 2019-49&50 | 9:31 | [link](https://www.bilibili.com/video/BV1NPzXYbEtG) |
| 1528 | - | - | 2019-51 | 3:06 | [link](https://www.bilibili.com/video/BV1NPzXYbE4D) |
| 1529 | - | - | 2019-52 | 3:46 | [link](https://www.bilibili.com/video/BV11PzXYbEsz) |
| 1530 | - | - | 2019-53 | 6:32 | [link](https://www.bilibili.com/video/BV1xPzXYbEcm) |
| 1531 | - | - | 2019-54&55 | 12:18 | [link](https://www.bilibili.com/video/BV1PPzXYbEfV) |
| 1532 | - | - | 2019论证有效性分析 | 17:00 | [link](https://www.bilibili.com/video/BV1yk28YUEoN) |
| 1533 | - | - | 2019论说文 | 15:06 | [link](https://www.bilibili.com/video/BV1Nk28YSE8v) |
| 1534 | - | - | 2021逻辑选择 | 123:29 | [link](https://www.bilibili.com/video/BV1yk28YUERZ) |
| 1535 | - | - | 2021-26 | 1:08 | [link](https://www.bilibili.com/video/BV1YYzFYZE2e) |
| 1536 | - | - | 2021-27 | 4:19 | [link](https://www.bilibili.com/video/BV1EszFYNEKF) |
| 1537 | - | - | 2021-28 | 2:55 | [link](https://www.bilibili.com/video/BV1ZszFYPErU) |
| 1538 | - | - | 2021-29 | 4:44 | [link](https://www.bilibili.com/video/BV1ZszFYPEaT) |
| 1539 | - | - | 2021-30 | 1:11 | [link](https://www.bilibili.com/video/BV1BszFYNE8g) |
| 1540 | - | - | 2021-31 | 3:57 | [link](https://www.bilibili.com/video/BV1BszFYPEuj) |
| 1541 | - | - | 2021-32 | 1:30 | [link](https://www.bilibili.com/video/BV1EszFYNEwm) |
| 1542 | - | - | 2021-33 | 10:22 | [link](https://www.bilibili.com/video/BV1BszFYPEMa) |
| 1543 | - | - | 2021-34 | 1:57 | [link](https://www.bilibili.com/video/BV1ZszFYPEkn) |
| 1544 | - | - | 2021-35 | 6:18 | [link](https://www.bilibili.com/video/BV15azFY8EYc) |
| 1545 | - | - | 2021-36 | 4:05 | [link](https://www.bilibili.com/video/BV1eazFYbEbd) |
| 1546 | - | - | 2021-37 | 8:46 | [link](https://www.bilibili.com/video/BV15azFY8Ea8) |
| 1547 | - | - | 2021-38 | 3:28 | [link](https://www.bilibili.com/video/BV1eazFYbEhi) |
| 1548 | - | - | 2021-39 | 2:39 | [link](https://www.bilibili.com/video/BV1RazFYbENG) |
| 1549 | - | - | 2021-40&41 | 4:10 | [link](https://www.bilibili.com/video/BV15azFY8EtQ) |
| 1550 | - | - | 2021-42 | 3:46 | [link](https://www.bilibili.com/video/BV1eazFYbEv1) |
| 1551 | - | - | 2021-43 | 1:20 | [link](https://www.bilibili.com/video/BV1eazFYbEvQ) |
| 1552 | - | - | 2021-44 | 2:48 | [link](https://www.bilibili.com/video/BV19azFYbEot) |
| 1553 | - | - | 2021-45 | 6:02 | [link](https://www.bilibili.com/video/BV1eazFYbEan) |
| 1554 | - | - | 2021-46 | 2:24 | [link](https://www.bilibili.com/video/BV1RazFYbEN1) |
| 1555 | - | - | 2021-47&48 | 9:14 | [link](https://www.bilibili.com/video/BV1eazFY8EdM) |
| 1556 | - | - | 2021-49 | 3:55 | [link](https://www.bilibili.com/video/BV1eazFYbEBa) |
| 1557 | - | - | 2021-50 | 3:17 | [link](https://www.bilibili.com/video/BV1eazFYbEqC) |
| 1558 | - | - | 2021-51 | 7:04 | [link](https://www.bilibili.com/video/BV19azFYbEo9) |
| 1559 | - | - | 2021-52 | 1:07 | [link](https://www.bilibili.com/video/BV1eazFY8EdN) |
| 1560 | - | - | 2021-53 | 2:09 | [link](https://www.bilibili.com/video/BV19YzFYZELZ) |
| 1561 | - | - | 2021-54、55 | 17:59 | [link](https://www.bilibili.com/video/BV1eYzFYfEu6) |
| 1562 | - | - | 2021论证有效性分析 | 17:15 | [link](https://www.bilibili.com/video/BV1Nk28YSEbp) |
| 1563 | - | - | 2021论说文 | 10:55 | [link](https://www.bilibili.com/video/BV1sk28YSER7) |
| 1564 | - | - | 2024逻辑选择 | 151:45 | [link](https://www.bilibili.com/video/BV11k28YUEFo) |
| 1565 | - | - | 2024-26 | 3:32 | [link](https://www.bilibili.com/video/BV1W9zFY5EHW) |
| 1566 | - | - | 2024-27 | 4:04 | [link](https://www.bilibili.com/video/BV1xUzFYmEh6) |
| 1567 | - | - | 2024-28 | 4:19 | [link](https://www.bilibili.com/video/BV12UzFYmEgy) |
| 1568 | - | - | 2024-28 | 7:22 | [link](https://www.bilibili.com/video/BV12UzFYmEAM) |
| 1569 | - | - | 2024-29 | 4:11 | [link](https://www.bilibili.com/video/BV1KUzFYUEhy) |
| 1570 | - | - | 2024-30 | 4:52 | [link](https://www.bilibili.com/video/BV1xUzFYmEvn) |
| 1571 | - | - | 2024-32 | 12:06 | [link](https://www.bilibili.com/video/BV1xUzFYmEzG) |
| 1572 | - | - | 2024-33 | 4:10 | [link](https://www.bilibili.com/video/BV12UzFYmEAf) |
| 1573 | - | - | 2024-34 | 3:23 | [link](https://www.bilibili.com/video/BV1wozFYVE9k) |
| 1574 | - | - | 2024-35&36 | 7:00 | [link](https://www.bilibili.com/video/BV1pozFYGEFv) |
| 1575 | - | - | 2024-37 | 4:54 | [link](https://www.bilibili.com/video/BV1HozFYGEoX) |
| 1576 | - | - | 2024-38 | 4:17 | [link](https://www.bilibili.com/video/BV1pozFYGEwv) |
| 1577 | - | - | 2024-39 | 4:38 | [link](https://www.bilibili.com/video/BV1pozFYGEKP) |
| 1578 | - | - | 2024-40 | 5:37 | [link](https://www.bilibili.com/video/BV1kozFYGExb) |
| 1579 | - | - | 2024-41 | 3:11 | [link](https://www.bilibili.com/video/BV1kozFYGEir) |
| 1580 | - | - | 2024-42 | 1:39 | [link](https://www.bilibili.com/video/BV1HozFYGEfV) |
| 1581 | - | - | 2024-43 | 2:47 | [link](https://www.bilibili.com/video/BV1pozFYGETp) |
| 1582 | - | - | 2024-44 | 3:11 | [link](https://www.bilibili.com/video/BV1yQzFY1Evo) |
| 1583 | - | - | 2024-45 | 3:49 | [link](https://www.bilibili.com/video/BV1yQzFY1ECd) |
| 1584 | - | - | 2024-46 | 2:27 | [link](https://www.bilibili.com/video/BV1kozFYGEBw) |
| 1585 | - | - | 2024-47 | 7:26 | [link](https://www.bilibili.com/video/BV1kozFYGEqx) |
| 1586 | - | - | 2024-48 | 4:17 | [link](https://www.bilibili.com/video/BV1HZzFYrE7n) |
| 1587 | - | - | 2024-49 | 3:55 | [link](https://www.bilibili.com/video/BV1HZzFYrEpN) |
| 1588 | - | - | 2024-50 | 6:40 | [link](https://www.bilibili.com/video/BV1rZzFYrE12) |
| 1589 | - | - | 2024-51 | 2:19 | [link](https://www.bilibili.com/video/BV1rZzFYrE2N) |
| 1590 | - | - | 2024-52 | 5:43 | [link](https://www.bilibili.com/video/BV1HZzFYrEE8) |
| 1591 | - | - | 2024-53 | 4:12 | [link](https://www.bilibili.com/video/BV1HZzFYrEp7) |
| 1592 | - | - | 2024-54、55 | 10:38 | [link](https://www.bilibili.com/video/BV1W9zFY5E46) |
| 1593 | - | - | 2024论证有效性分析 | 11:55 | [link](https://www.bilibili.com/video/BV1xk28YSEA5) |
| 1594 | - | - | 2024论说文 | 12:08 | [link](https://www.bilibili.com/video/BV1Nk28YSEe8) |
| 1595 | - | - | 0.1三国志曹操传（序章）——何去何从 | 1:02 | [link](https://www.bilibili.com/video/BV1ym4y1g7r5) |
| 1596 | - | - | 0.2三国志曹操传（序章）——颖川之战 | 8:58 | [link](https://www.bilibili.com/video/BV1aj411t7ao) |
| 1597 | - | - | 0.3三国志曹操传（序章）——壮志雄心 | 1:15 | [link](https://www.bilibili.com/video/BV1km4y1g7g1) |
| 1598 | - | - | 1.1三国志曹操传（第一章 霸王诞生）——董卓专权，首倡义兵 | 8:46 | [link](https://www.bilibili.com/video/BV1Jy4y1N7Lo) |
| 1599 | - | - | 1.2三国志曹操传（第一章 霸王诞生）——汜水关之战 | 13:42 | [link](https://www.bilibili.com/video/BV1PC4y157fE) |
| 1600 | - | - | 1.3三国志曹操传（第一章 霸王诞生）——军合力不齐，踌躇而雁行 | 2:12 | [link](https://www.bilibili.com/video/BV12G411m7zu) |
| 1601 | - | - | 1.4三国志曹操传（第一章 霸王诞生）——虎牢关之战 | 13:29 | [link](https://www.bilibili.com/video/BV1EC4y1577b) |
| 1602 | - | - | 1.5三国志曹操传（第一章 霸王诞生）——播越西迁移，号泣而且行 | 2:37 | [link](https://www.bilibili.com/video/BV1kw411r7hy) |
| 1603 | - | - | 1.6三国志曹操传（第一章 霸王诞生）——董卓追击战 | 21:30 | [link](https://www.bilibili.com/video/BV1hh4y1z7s3) |
| 1604 | - | - | 1.7三国志曹操传（第一章 霸王诞生）——盗贼如蚁聚，群雄皆鹰扬 | 7:28 | [link](https://www.bilibili.com/video/BV1WN4y1y7bE) |
| 1605 | - | - | 1.8三国志曹操传（第一章 霸王诞生）——青州黄巾讨伐战 | 15:27 | [link](https://www.bilibili.com/video/BV1Rj411s7ST) |
| 1606 | - | - | 1.9三国志曹操传（第一章 霸王诞生）——征讨陶谦，吕布偷袭 | 3:17 | [link](https://www.bilibili.com/video/BV1wG411U7gs) |
| 1607 | - | - | 1.10三国志曹操传（第一章 霸王诞生）——徐州复仇战 | 12:44 | [link](https://www.bilibili.com/video/BV1ew411A7rA) |
| 1608 | - | - | 1.11三国志曹操传（第一章 霸王诞生）——放弃进攻，回救濮阳 | 0:47 | [link](https://www.bilibili.com/video/BV1894y187aY) |
| 1609 | - | - | 1.12三国志曹操传（第一章 霸王诞生）——濮阳之战壹 | 25:38 | [link](https://www.bilibili.com/video/BV118411k719) |
| 1610 | - | - | 1.13三国志曹操传（第一章 霸王诞生）——似有内应，再战濮阳 | 1:30 | [link](https://www.bilibili.com/video/BV1ow411k7jm) |
| 1611 | - | - | 1.14三国志曹操传（第一章 霸王诞生）——濮阳之战贰 | 17:32 | [link](https://www.bilibili.com/video/BV1VG411U7ao) |
| 1612 | - | - | 1.15三国志曹操传（第一章 霸王诞生）——全力以赴，夺回濮阳 | 3:20 | [link](https://www.bilibili.com/video/BV1w8411C798) |
| 1613 | - | - | 1.16三国志曹操传（第一章 霸王诞生）——濮阳之战叁 | 18:38 | [link](https://www.bilibili.com/video/BV1ew411A7Sr) |
| 1614 | - | - | 1.17三国志曹操传（第一章 霸王诞生）——奉天子以令不臣 | 3:32 | [link](https://www.bilibili.com/video/BV1N84y127vB) |
| 1615 | - | - | 1.18三国志曹操传（第一章 霸王诞生）——献帝救出战 | 11:13 | [link](https://www.bilibili.com/video/BV1384y127E8) |
| 1616 | - | - | 1.19三国志曹操传（第一章 霸王诞生）——一征张绣，得意忘形 | 9:30 | [link](https://www.bilibili.com/video/BV1Wj411v7zm) |
| 1617 | - | - | 1.20三国志曹操传（第一章 霸王诞生）——张绣讨伐战壹（典韦殒命） | 6:15 | [link](https://www.bilibili.com/video/BV1nN4y1C7Fj) |
| 1618 | - | - | 1.21三国志曹操传（第一章 霸王诞生）——张绣讨伐战壹（典韦存活） | 11:46 | [link](https://www.bilibili.com/video/BV1gw411X74g) |
| 1619 | - | - | 1.22三国志曹操传（第一章 霸王诞生）——淮南弟称号 | 1:12 | [link](https://www.bilibili.com/video/BV15H4y1d7eH) |
| 1620 | - | - | 1.23三国志曹操传（第一章 霸王诞生）——袁术讨伐战 | 13:29 | [link](https://www.bilibili.com/video/BV1Sh4y1q7P4) |
| 1621 | - | - | 1.24三国志曹操传（第一章 霸王诞生）——卷土重来，二征张绣 | 1:54 | [link](https://www.bilibili.com/video/BV1Jy4y1K7Hh) |
| 1622 | - | - | 1.25三国志曹操传（第一章 霸王诞生）——张绣讨伐战贰 | 14:58 | [link](https://www.bilibili.com/video/BV1rh4y1q7JF) |
| 1623 | - | - | 1.26三国志曹操传（第一章 霸王诞生）——救援刘备，消灭吕布 | 2:30 | [link](https://www.bilibili.com/video/BV1Hy4y1K7mT) |
| 1624 | - | - | 1.27三国志曹操传（第一章 霸王诞生）——徐州救援战 | 15:44 | [link](https://www.bilibili.com/video/BV1ZC4y1G7F1) |
| 1625 | - | - | 1.28三国志曹操传（第一章 霸王诞生）——天寒地冻，围攻下邳 | 1:28 | [link](https://www.bilibili.com/video/BV1A94y1b7NV) |
| 1626 | - | - | 1.29三国志曹操传（第一章 霸王诞生）——吕布包围战 | 14:38 | [link](https://www.bilibili.com/video/BV19C4y1G7cC) |
| 1627 | - | - | 1.30三国志曹操传（第一章 霸王诞生）——吕布授首，中原统一 | 2:20 | [link](https://www.bilibili.com/video/BV1Nh4y1B78f) |
| 1628 | - | - | 2.1三国志曹操传（第二章 河北之争）——放虎归山，张绣来降 | 5:10 | [link](https://www.bilibili.com/video/BV1Sj411a7J4) |
| 1629 | - | - | 2.2三国志曹操传（第二章 河北之争）——徐州入侵战 | 12:17 | [link](https://www.bilibili.com/video/BV1LC4y1H7Ye) |
| 1630 | - | - | 2.3三国志曹操传（第二章 河北之争）——身在曹营心在刘 | 6:00 | [link](https://www.bilibili.com/video/BV1P94y1L7Lh) |
| 1631 | - | - | 2.4三国志曹操传（第二章 河北之争）——白马之战 | 11:07 | [link](https://www.bilibili.com/video/BV1DN4y167DT) |
| 1632 | - | - | 2.5三国志曹操传（第二章 河北之争）——已斩颜良，待诛文丑 | 1:17 | [link](https://www.bilibili.com/video/BV1du4y1j7gG) |
| 1633 | - | - | 2.6三国志曹操传（第二章 河北之争）——延津之战 | 12:42 | [link](https://www.bilibili.com/video/BV11z4y1N7hZ) |
| 1634 | - | - | 2.7三国志曹操传（第二章 河北之争）——送别关羽，直面生死 | 5:51 | [link](https://www.bilibili.com/video/BV19H4y1z73n) |
| 1635 | - | - | 2.8三国志曹操传（第二章 河北之争）——官渡之战 | 17:50 | [link](https://www.bilibili.com/video/BV1a94y1G7Pt) |
| 1636 | - | - | 2.9三国志曹操传（第二章 河北之争）——一战功成，袁氏溃败 | 4:11 | [link](https://www.bilibili.com/video/BV1JG411X7L9) |
| 1637 | - | - | 2.10三国志曹操传（第二章 河北之争）——宜将剩勇追穷寇 | 16:22 | [link](https://www.bilibili.com/video/BV1DC4y1E7Do) |
| 1638 | - | - | 2.11三国志曹操传（第二章 河北之争）——袁绍殒命，往事如烟 | 1:31 | [link](https://www.bilibili.com/video/BV1Aw411M7Zx) |
| 1639 | - | - | 2.12三国志曹操传（第二章 河北之争）——忙里偷闲，闪击刘备 | 0:18 | [link](https://www.bilibili.com/video/BV13Q4y1p7kS) |
| 1640 | - | - | 2.13三国志曹操传（第二章 河北之争）——穰山之战 | 13:12 | [link](https://www.bilibili.com/video/BV1Ke411R7si) |
| 1641 | - | - | 2.14三国志曹操传（第二章 河北之争）——刘备败逃，再击袁氏 | 2:29 | [link](https://www.bilibili.com/video/BV1Uu4y1h7CN) |
| 1642 | - | - | 2.15三国志曹操传（第二章 河北之争）——黎阳之战 | 10:38 | [link](https://www.bilibili.com/video/BV1v94y1G7D5) |
| 1643 | - | - | 2.16三国志曹操传（第二章 河北之争）——一鼓作气，拿下邺城 | 3:40 | [link](https://www.bilibili.com/video/BV12e411Q7Lm) |
| 1644 | - | - | 2.17三国志曹操传（第二章 河北之争）——邺城之战 | 19:08 | [link](https://www.bilibili.com/video/BV1TN4y1r7Mj) |
| 1645 | - | - | 2.18三国志曹操传（第二章 河北之争）——兄弟内讧，渔翁得利 | 2:44 | [link](https://www.bilibili.com/video/BV1uM411Q7Fm) |
| 1646 | - | - | 2.19三国志曹操传（第二章 河北之争）——南皮攻略战 | 13:53 | [link](https://www.bilibili.com/video/BV1cw411M7qy) |
| 1647 | - | - | 2.20三国志曹操传（第二章 河北之争）——出其不意，奔袭乌丸 | 1:04 | [link](https://www.bilibili.com/video/BV1n84y197MT) |
| 1648 | - | - | 2.21三国志曹操传（第二章 河北之争）——柳城平定战（郭嘉殒命） | 6:28 | [link](https://www.bilibili.com/video/BV1uu4y17732) |
| 1649 | - | - | 2.22三国志曹操传（第二章 河北之争）——柳城平定战（郭嘉存活） | 8:50 | [link](https://www.bilibili.com/video/BV1yH4y1z7Le) |
| 1650 | - | - | 2.23三国志曹操传（第二章 河北之争）——袁氏灭亡，北方统一 | 1:31 | [link](https://www.bilibili.com/video/BV1B94y1G7su) |
| 1651 | - | - | 3.1三国志曹操传（第三章 三国鼎立）——卧龙出山，国士无双 | 5:26 | [link](https://www.bilibili.com/video/BV1zG411S7h1) |
| 1652 | - | - | 3.2三国志曹操传（第三章 三国鼎立）——博望坡之战 | 10:22 | [link](https://www.bilibili.com/video/BV1Bv411F7vA) |
| 1653 | - | - | 3.3三国志曹操传（第三章 三国鼎立）——南下灭刘，鲸吞荆州 | 2:26 | [link](https://www.bilibili.com/video/BV1wC4y1j7Lj) |
| 1654 | - | - | 3.4三国志曹操传（第三章 三国鼎立）——长坂坡之战 | 16:30 | [link](https://www.bilibili.com/video/BV1Lu4y1b7Hv) |
| 1655 | - | - | 3.5三国志曹操传（第三章 三国鼎立）——孙刘联盟，南北对抗 | 4:25 | [link](https://www.bilibili.com/video/BV1wG411X7vq) |
| 1656 | - | - | 3.6三国志曹操传（第三章 三国鼎立）——赤壁之战（全灭敌军） | 20:41 | [link](https://www.bilibili.com/video/BV1cG411X7C3) |
| 1657 | - | - | 3.7三国志曹操传（第三章 三国鼎立）——赤壁之战（仓皇撤退） | 17:08 | [link](https://www.bilibili.com/video/BV17u4y1b7TK) |
| 1658 | - | - | 3.8三国志曹操传（第三章 三国鼎立）——败走华容 | 1:14 | [link](https://www.bilibili.com/video/BV1ma4y1S76v) |
| 1659 | - | - | 3.9三国志曹操传（第三章 三国鼎立）——赤壁突围战 | 7:18 | [link](https://www.bilibili.com/video/BV1Uv411F7hj) |
| 1660 | - | - | 3.10三国志曹操传（第三章 三国鼎立）——操撤兵北归，权兵临合肥 | 1:34 | [link](https://www.bilibili.com/video/BV1ru4y1A7Dy) |
| 1661 | - | - | 3.11三国志曹操传（第三章 三国鼎立）——合肥之战 | 9:50 | [link](https://www.bilibili.com/video/BV1yQ4y1t7GN) |
| 1662 | - | - | 3.12三国志曹操传（第三章 三国鼎立）——进军关中，消灭马超 | 3:43 | [link](https://www.bilibili.com/video/BV1dC4y127Ck) |
| 1663 | - | - | 3.13三国志曹操传（第三章 三国鼎立）——马超迎击战 | 9:41 | [link](https://www.bilibili.com/video/BV16G411S7bH) |
| 1664 | - | - | 3.14三国志曹操传（第三章 三国鼎立）——得寸进尺，剑指汉中 | 2:28 | [link](https://www.bilibili.com/video/BV19G411S7Di) |
| 1665 | - | - | 3.15三国志曹操传（第三章 三国鼎立）——张鲁讨伐战 | 10:12 | [link](https://www.bilibili.com/video/BV1bz4y1w7DJ) |
| 1666 | - | - | 3.16三国志曹操传（第三章 三国鼎立）——得陇不望蜀，孙刘再携手 | 2:31 | [link](https://www.bilibili.com/video/BV1iC4y1274c) |
| 1667 | - | - | 3.17三国志曹操传（第三章 三国鼎立）——逍遥津之战 | 10:45 | [link](https://www.bilibili.com/video/BV1v94y1n7TU) |
| 1668 | - | - | 3.18三国志曹操传（第三章 三国鼎立）——最后一次南征 | 1:30 | [link](https://www.bilibili.com/video/BV1Ua4y1m7Rt) |
| 1669 | - | - | 3.19三国志曹操传（第三章 三国鼎立）——濡须口之战 | 9:00 | [link](https://www.bilibili.com/video/BV1yN411M7wM) |
| 1670 | - | - | 3.20三国志曹操传（第三章 三国鼎立）——势均力敌，鼎足三分 | 1:06 | [link](https://www.bilibili.com/video/BV1Ug4y1Q7Ji) |
| 1671 | - | - | 4.1三国志曹操传（终章 天下统一）——天下英雄唯使君与操尔 | 1:18 | [link](https://www.bilibili.com/video/BV1Mz4y1A7bw) |
| 1672 | - | - | 4.2三国志曹操传（终章 天下统一）——定军山之战（全灭敌军） | 12:55 | [link](https://www.bilibili.com/video/BV1ej411E7kn) |
| 1673 | - | - | 4.3三国志曹操传（终章 天下统一）——定军山之战（夏侯渊殒命） | 18:37 | [link](https://www.bilibili.com/video/BV1qg4y1Q7Zo) |
| 1674 | - | - | 4.4三国志曹操传（终章 天下统一）——最后一次西征 | 0:45 | [link](https://www.bilibili.com/video/BV17e411Q76b) |
| 1675 | - | - | 4.5三国志曹操传（终章 天下统一）——汉水之战 | 10:59 | [link](https://www.bilibili.com/video/BV1Wu411F7FM) |
| 1676 | - | - | 4.6三国志曹操传（终章 天下统一）——一生的对手 | 0:11 | [link](https://www.bilibili.com/video/BV1Lw411N7U1) |
| 1677 | - | - | 4.7三国志曹操传（终章 天下统一）——斜谷之战 | 11:28 | [link](https://www.bilibili.com/video/BV16b4y1g7kT) |
| 1678 | - | - | 4.8三国志曹操传（终章 天下统一）——水淹七军，威震华夏 | 3:30 | [link](https://www.bilibili.com/video/BV1Sv411F7tk) |
| 1679 | - | - | 4.9三国志曹操传（终章 天下统一）——樊城救援战（庞德殒命） | 9:49 | [link](https://www.bilibili.com/video/BV16b4y1g7VL) |
| 1680 | - | - | 4.10三国志曹操传（终章 天下统一）——忠肝义胆，英雄相惜 | 1:24 | [link](https://www.bilibili.com/video/BV1eC4y1E7d5) |
| 1681 | - | - | 4.11三国志曹操传（终章 天下统一）——若天命在吾，吾为周文王矣 | 1:53 | [link](https://www.bilibili.com/video/BV1su4y1b76j) |
| 1682 | - | - | 5.1三国志曹操传（他不知道的事）——英雄的落幕 | 1:22 | [link](https://www.bilibili.com/video/BV1ZG411S7c6) |
| 1683 | - | - | 5.2三国志曹操传（心中永远的遗憾）——老骥伏枥，志在千里，烈士暮年，壮心不已。山不厌高，海不厌深，周公吐哺，天下归心。 | 131:17 | [link](https://www.bilibili.com/video/BV1qw411W7iP) |
| 1684 | - | - | 1.2024研究生入学考试数学冲刺阶段考点串讲——导学篇（独孤九剑总章） | 213:04 | [link](https://www.bilibili.com/video/BV1Gh4y1676V) |
| 1685 | - | - | 2.1.2024考研高等数学冲刺串讲——函数的有界性、奇偶性、单调性、周期性1 | 72:41 | [link](https://www.bilibili.com/video/BV1AC4y1Z7vV) |
| 1686 | - | - | 2.2.2024考研高等数学冲刺串讲——函数的有界性、奇偶性、单调性、周期性2（复合函数例题） | 42:59 | [link](https://www.bilibili.com/video/BV1Fz4y1F7Qi) |
| 1687 | - | - | 2.3.2024考研高等数学冲刺串讲——函数的有界性、奇偶性、单调性、周期性3（单调性、奇偶性例题） | 53:00 | [link](https://www.bilibili.com/video/BV1CC4y1L7mJ) |
| 1688 | - | - | 2.4.2024考研高等数学冲刺串讲——函数的有界性、奇偶性、单调性、周期性4（有界性例题） | 89:19 | [link](https://www.bilibili.com/video/BV11w411a7BK) |
| 1689 | - | - | 2.5.2024考研高等数学冲刺串讲——函数的有界性、奇偶性、单调性、周期性5（周期性例题） | 76:30 | [link](https://www.bilibili.com/video/BV1N94y1a78m) |
| 1690 | - | - | 2.6.2024考研高等数学冲刺串讲——常考函数、参数方程与极坐标方程 | 102:55 | [link](https://www.bilibili.com/video/BV1wH4y1o7Ds) |
| 1691 | - | - | 2.7.2024考研高等数学冲刺串讲——常考数列与不等式 | 85:19 | [link](https://www.bilibili.com/video/BV1J8411k79K) |
| 1692 | - | - | 2.8.2024考研高等数学冲刺串讲——常考数列与不等式（1.数学归纳法；2.柯西不等式） | 56:34 | [link](https://www.bilibili.com/video/BV178411k7cP) |
| 1693 | - | - | 2.8.2024考研高等数学冲刺串讲——常考数列与不等式（3.常用放缩公式；4.看起来不是不等式的不等式问题） | 78:35 | [link](https://www.bilibili.com/video/BV1rj41147ja) |
| 1694 | - | - | 2.8.2024考研高等数学冲刺串讲——常考数列与不等式（5.“经典名菜”品鉴） | 97:37 | [link](https://www.bilibili.com/video/BV1Nm4y1g7GJ) |
| 1695 | - | - | 3.1.2024考研高等数学冲刺串讲——极限与连续（考点梳理） | 113:18 | [link](https://www.bilibili.com/video/BV14Q4y1s7w7) |
| 1696 | - | - | 3.2.2024考研高等数学冲刺串讲——极限与连续（极限的计算） | 86:01 | [link](https://www.bilibili.com/video/BV19u4y1p7Ai) |
| 1697 | - | - | 3.3.2024考研高等数学冲刺串讲——极限与连续（有关极限定义的问题） | 84:27 | [link](https://www.bilibili.com/video/BV1bC4y137Bj) |
| 1698 | - | - | 3.4.2024考研高等数学冲刺串讲——极限与连续（夹逼定理与单调有界准则） | 84:39 | [link](https://www.bilibili.com/video/BV1HN411s7VY) |
| 1699 | - | - | 3.5.2024考研高等数学冲刺串讲——极限与连续（“经典名菜”品鉴） | 147:13 | [link](https://www.bilibili.com/video/BV1ce411X7Z8) |
| 1700 | - | - | 上海交大大模型智能体课程第1讲：初探大模型智能体 | 20:17 | [link](https://www.bilibili.com/video/BV1UgvYBtEaa) |
| 1701 | - | - | 上海交大大模型智能体课程第2讲：生成式大语言模型 | 16:45 | [link](https://www.bilibili.com/video/BV1bgvYBtEbk) |
| 1702 | - | - | 上海交大大模型智能体课程第3讲：提示工程 | 28:54 | [link](https://www.bilibili.com/video/BV1bgvYBtECs) |
| 1703 | - | - | 上海交大大模型智能体课程第4讲：智能体评估 | 26:16 | [link](https://www.bilibili.com/video/BV1YAvYBAETJ) |
| 1704 | - | - | 上海交大大模型智能体课程第5讲：智能体架构概览 | 35:52 | [link](https://www.bilibili.com/video/BV1YAvYBAEHH) |
| 1705 | - | - | 上海交大大模型智能体课程第6讲：记忆管理与检索增强 | 33:09 | [link](https://www.bilibili.com/video/BV1XAvYBAEXS) |
| 1706 | - | - | 上海交大大模型智能体课程第7讲：外部工具调用 | 29:50 | [link](https://www.bilibili.com/video/BV1VAvYBPEFW) |
| 1707 | - | - | 上海交大大模型智能体课程第8讲：推理、规划和树搜索增强 | 36:02 | [link](https://www.bilibili.com/video/BV1GAvYBPE9J) |
| 1708 | - | - | 上海交大大模型智能体课程第9讲：指令微调 | 26:16 | [link](https://www.bilibili.com/video/BV1YAvYBAEET) |
| 1709 | - | - | 上海交大大模型智能体课程第10讲：LoRA微调与模型量化 | 22:10 | [link](https://www.bilibili.com/video/BV1YAvYBAEcM) |
| 1710 | - | - | 上海交大大模型智能体课程第11讲：针对AI智能体的强化微调 | 34:51 | [link](https://www.bilibili.com/video/BV1YAvYBAEHU) |
| 1711 | - | - | 上海交大大模型智能体课程第12讲：多模态智能体 | 31:01 | [link](https://www.bilibili.com/video/BV1XAvYBAEaC) |
| 1712 | - | - | 上海交大大模型智能体课程第13讲：基于大语言模型的多智能体系统 | 28:33 | [link](https://www.bilibili.com/video/BV1XAvYBAEQw) |
| 1713 | - | - | 上海交大大模型智能体课程第14讲：智能体攻防 | 20:33 | [link](https://www.bilibili.com/video/BV19cvYBeEWt) |
| 1714 | - | - | 上海交大大模型智能体课程第15讲：智能体通信协议 | 37:09 | [link](https://www.bilibili.com/video/BV1YcvYBeEpE) |
| 1715 | - | - | HugWBC：让人形机器人蹦跶起来！ | 2:40 | [link](https://www.bilibili.com/video/BV13UNGe4Etn) |
| 1716 | - | - | OmniH2O：人形机器人全身控制遥操作学习框架 | 2:07 | [link](https://www.bilibili.com/video/BV1Y5KsewEdD) |
| 1717 | - | - | BeamDojo：人形机器人走梅花桩啦！ | 1:44 | [link](https://www.bilibili.com/video/BV1bAAtexEoB) |
| 1718 | - | - | RHINO：让人形机器人学会交互！ | 2:31 | [link](https://www.bilibili.com/video/BV18AAtexEpk) |
| 1719 | - | - | 跨具身人形运动：一脑多形 | 1:01 | [link](https://www.bilibili.com/video/BV11f8nztEia) |
| 1720 | - | - | 上海交大张伟楠机器学习课程第1讲：机器学习简介I | 25:38 | [link](https://www.bilibili.com/video/BV1L5S2Y9ESV) |
| 1721 | - | - | 上海交大张伟楠强化学习课程第1讲：机器学习简介II | 30:05 | [link](https://www.bilibili.com/video/BV16TS2YbE1q) |
| 1722 | - | - | 上海交大张伟楠机器学习课程第1讲：机器学习简介III | 32:01 | [link](https://www.bilibili.com/video/BV1cKS2YFEbC) |
| 1723 | - | - | 上海交大张伟楠机器学习课程第1讲：机器学习简介IV | 31:57 | [link](https://www.bilibili.com/video/BV1fgS2YxEEM) |
| 1724 | - | - | 上海交大张伟楠机器学习课程第1讲：机器学习简介V | 25:14 | [link](https://www.bilibili.com/video/BV1hcUNYtExa) |
| 1725 | - | - | 上海交大张伟楠机器学习课程第2讲：线性模型I | 30:37 | [link](https://www.bilibili.com/video/BV1A4UnYdEG6) |
| 1726 | - | - | 上海交大张伟楠机器学习课程第2讲：线性模型II | 29:58 | [link](https://www.bilibili.com/video/BV1p4UnYdEYN) |
| 1727 | - | - | 上海交大张伟楠机器学习课程第2讲：线性模型III | 30:05 | [link](https://www.bilibili.com/video/BV1A4UnYdE3b) |
| 1728 | - | - | 上海交大张伟楠机器学习课程第2讲：线性模型IV | 33:50 | [link](https://www.bilibili.com/video/BV1p4UnYdErP) |
| 1729 | - | - | 上海交大张伟楠机器学习课程第2讲：线性模型V | 22:04 | [link](https://www.bilibili.com/video/BV1A4UnYdET4) |
| 1730 | - | - | 上海交大张伟楠机器学习课程第3讲：K近邻算法与双线性模型I | 35:13 | [link](https://www.bilibili.com/video/BV1RiB8Y5Emz) |
| 1731 | - | - | 上海交大张伟楠机器学习课程第3讲：K近邻算法与双线性模型II | 35:42 | [link](https://www.bilibili.com/video/BV1ViB8YVERU) |
| 1732 | - | - | 上海交大张伟楠机器学习课程第3讲：K近邻算法与双线性模型III | 18:39 | [link](https://www.bilibili.com/video/BV1viB8YLESe) |
| 1733 | - | - | 上海交大张伟楠机器学习课程第4讲：人工神经网络I | 48:11 | [link](https://www.bilibili.com/video/BV1zuzxYgEAs) |
| 1734 | - | - | 上海交大张伟楠机器学习课程第4讲：人工神经网络II | 33:37 | [link](https://www.bilibili.com/video/BV1BuzxYgEho) |
| 1735 | - | - | 上海交大张伟楠机器学习课程第4讲：人工神经网络III | 35:51 | [link](https://www.bilibili.com/video/BV1EuzxY3EaY) |
| 1736 | - | - | 上海交大张伟楠机器学习课程第4讲：人工神经网络IV | 33:54 | [link](https://www.bilibili.com/video/BV1r5i1YoEuf) |
| 1737 | - | - | 上海交大张伟楠机器学习课程第4讲：人工神经网络V | 37:01 | [link](https://www.bilibili.com/video/BV165i1YoEQQ) |
| 1738 | - | - | 上海交大张伟楠机器学习课程第4讲：人工神经网络VI | 21:38 | [link](https://www.bilibili.com/video/BV165i1YoEmF) |
| 1739 | - | - | 上海交大张伟楠机器学习课程第5讲：支持向量机I | 44:26 | [link](https://www.bilibili.com/video/BV1QKBFYpE2A) |
| 1740 | - | - | 上海交大张伟楠机器学习课程第5讲：支持向量机II | 37:56 | [link](https://www.bilibili.com/video/BV1XKBFYpE2c) |
| 1741 | - | - | 上海交大张伟楠机器学习课程第5讲：支持向量机III | 42:13 | [link](https://www.bilibili.com/video/BV1XKBFYpEhM) |
| 1742 | - | - | 上海交大张伟楠机器学习课程第6讲：决策树I | 19:44 | [link](https://www.bilibili.com/video/BV1pUkUYXEiQ) |
| 1743 | - | - | 上海交大张伟楠机器学习课程第6讲：决策树II | 38:21 | [link](https://www.bilibili.com/video/BV1pUkUYXEHQ) |
| 1744 | - | - | 上海交大张伟楠机器学习课程第6讲：决策树III | 37:31 | [link](https://www.bilibili.com/video/BV1pUkUYXE4Q) |
| 1745 | - | - | 上海交大张伟楠机器学习课程第7讲：集成学习与森林模型I | 38:13 | [link](https://www.bilibili.com/video/BV17o6eYPEtB) |
| 1746 | - | - | 上海交大张伟楠机器学习课程第7讲：集成学习与森林模型II | 37:36 | [link](https://www.bilibili.com/video/BV17o6eYPEb3) |
| 1747 | - | - | 上海交大张伟楠机器学习课程第7讲：集成学习与森林模型III | 38:52 | [link](https://www.bilibili.com/video/BV1nU6eYzExT) |
| 1748 | - | - | 上海交大张伟楠机器学习课程第8讲：概率图模型I | 39:08 | [link](https://www.bilibili.com/video/BV1NNrgY1EWF) |
| 1749 | - | - | 上海交大张伟楠机器学习课程第8讲：概率图模型II | 22:26 | [link](https://www.bilibili.com/video/BV11NrgYyEGH) |
| 1750 | - | - | 上海交大张伟楠机器学习课程第8讲：概率图模型III | 38:02 | [link](https://www.bilibili.com/video/BV1yNrgYyEr3) |
| 1751 | - | - | 上海交大张伟楠机器学习课程第9讲：无监督学习I | 29:51 | [link](https://www.bilibili.com/video/BV1ancNeZEXt) |
| 1752 | - | - | 上海交大张伟楠机器学习课程第9讲：无监督学习II | 37:06 | [link](https://www.bilibili.com/video/BV1ancNeZE2Y) |
| 1753 | - | - | 上海交大张伟楠机器学习课程第9讲：无监督学习III | 37:36 | [link](https://www.bilibili.com/video/BV1GncNeZEpS) |
| 1754 | - | - | 上海交大张伟楠机器学习课程第9讲：无监督学习IV | 38:18 | [link](https://www.bilibili.com/video/BV1HowkeQEzS) |
| 1755 | - | - | 上海交大张伟楠机器学习课程第9讲：无监督学习V | 37:47 | [link](https://www.bilibili.com/video/BV1powkeQENk) |
| 1756 | - | - | 上海交大张伟楠机器学习课程第10讲：学习理论与模型选择I | 37:03 | [link](https://www.bilibili.com/video/BV1jpFNeYEdS) |
| 1757 | - | - | 上海交大张伟楠机器学习课程第10讲：学习理论与模型选择II | 38:28 | [link](https://www.bilibili.com/video/BV17pFNeYET2) |
| 1758 | - | - | 上海交大张伟楠机器学习课程第10讲：学习理论与模型选择III | 22:13 | [link](https://www.bilibili.com/video/BV17HFNePEzX) |
| 1759 | - | - | 上海交大张伟楠机器学习课程第11讲：迁移、多任务、元学习I | 48:57 | [link](https://www.bilibili.com/video/BV1sHfzYMETB) |
| 1760 | - | - | 上海交大张伟楠机器学习课程第11讲：迁移、多任务、元学习II | 36:20 | [link](https://www.bilibili.com/video/BV1sHfzYMEJH) |
| 1761 | - | - | 上海交大张伟楠机器学习课程第11讲：迁移、多任务、元学习III | 23:43 | [link](https://www.bilibili.com/video/BV1yHfzYMEya) |
| 1762 | - | - | 上海交大张伟楠机器学习课程第12讲：机器学习前沿话题漫谈 | 14:03 | [link](https://www.bilibili.com/video/BV1tVfzYCERh) |
| 1763 | - | - | RLChina 2024 / 3小时强化学习入门课程-上 | 58:07 | [link](https://www.bilibili.com/video/BV1yFm1Y4Evf) |
| 1764 | - | - | RLChina 2024 / 3小时强化学习入门课程-下 | 72:39 | [link](https://www.bilibili.com/video/BV1yFm1Y4Eiy) |
| 1765 | - | - | 上海交大张伟楠强化学习课程第1讲：强化学习简介I | 35:34 | [link](https://www.bilibili.com/video/BV1jUHdePEUZ) |
| 1766 | - | - | 上海交大张伟楠强化学习课程第1讲：强化学习简介II | 41:10 | [link](https://www.bilibili.com/video/BV1LSHdeYEQJ) |
| 1767 | - | - | 上海交大张伟楠强化学习课程第1讲：强化学习简介III | 11:52 | [link](https://www.bilibili.com/video/BV1LSHdeYEsv) |
| 1768 | - | - | 上海交大张伟楠强化学习课程第2讲：探索与利用 | 33:39 | [link](https://www.bilibili.com/video/BV1jaHfekE2U) |
| 1769 | - | - | 上海交大张伟楠强化学习课程第3讲：马尔可夫决策过程I | 21:33 | [link](https://www.bilibili.com/video/BV1ZaHfekEyL) |
| 1770 | - | - | 上海交大张伟楠强化学习课程第3讲：马尔可夫决策过程II | 24:34 | [link](https://www.bilibili.com/video/BV1D2HfewEmk) |
| 1771 | - | - | 上海交大张伟楠强化学习课程第4讲：动态规划 | 26:52 | [link](https://www.bilibili.com/video/BV1S2HfewEQa) |
| 1772 | - | - | 上海交大张伟楠强化学习课程第5讲：值函数估计I | 17:13 | [link](https://www.bilibili.com/video/BV13yHfeeEo2) |
| 1773 | - | - | 上海交大张伟楠强化学习课程第5讲：值函数估计II | 19:58 | [link](https://www.bilibili.com/video/BV1QyHfeYEPY) |
| 1774 | - | - | 上海交大张伟楠强化学习课程第6讲：无模型控制方法I | 39:41 | [link](https://www.bilibili.com/video/BV1USHfeFEZV) |
| 1775 | - | - | 上海交大张伟楠强化学习课程第6讲：无模型控制方法II | 26:49 | [link](https://www.bilibili.com/video/BV1SmHfehE3E) |
| 1776 | - | - | 上海交大张伟楠强化学习课程第7讲：规划与学习I | 34:01 | [link](https://www.bilibili.com/video/BV196HfeKEjm) |
| 1777 | - | - | 上海交大张伟楠强化学习课程第7讲：规划与学习II | 28:42 | [link](https://www.bilibili.com/video/BV196HfeKEBr) |
| 1778 | - | - | 上海交大张伟楠强化学习课程第8讲：参数化的值函数和策略I | 43:36 | [link](https://www.bilibili.com/video/BV1RBHfeqEHo) |
| 1779 | - | - | 上海交大张伟楠强化学习课程第8讲：参数化的值函数和策略II | 39:07 | [link](https://www.bilibili.com/video/BV1RBHfeqEWK) |
| 1780 | - | - | 上海交大张伟楠强化学习课程第9讲：深度强化学习价值方法I | 29:27 | [link](https://www.bilibili.com/video/BV1DtpeewESC) |
| 1781 | - | - | 上海交大张伟楠强化学习课程第9讲：深度强化学习价值方法II | 36:39 | [link](https://www.bilibili.com/video/BV1drpve3Eip) |
| 1782 | - | - | 上海交大张伟楠强化学习课程第10讲：深度强化学习策略方法I | 36:22 | [link](https://www.bilibili.com/video/BV199pzeUEMA) |
| 1783 | - | - | 上海交大张伟楠强化学习课程第10讲：深度强化学习策略方法II | 14:50 | [link](https://www.bilibili.com/video/BV199pzeUEgQ) |
| 1784 | - | - | 上海交大张伟楠强化学习课程第11讲：基于模型的深度强化学习I | 18:57 | [link](https://www.bilibili.com/video/BV199pzeUEg9) |
| 1785 | - | - | 上海交大张伟楠强化学习课程第11讲：基于模型的深度强化学习II | 35:09 | [link](https://www.bilibili.com/video/BV1DfpzeLEkB) |
| 1786 | - | - | 上海交大张伟楠强化学习课程第11讲：基于模型的深度强化学习III | 29:28 | [link](https://www.bilibili.com/video/BV1DfpzeLE5K) |
| 1787 | - | - | 上海交大张伟楠强化学习课程第12讲：模仿学习I | 32:10 | [link](https://www.bilibili.com/video/BV1DfpzeLEmC) |
| 1788 | - | - | 上海交大张伟楠强化学习课程第12讲：模仿学习II | 33:11 | [link](https://www.bilibili.com/video/BV1Qopze2Ee1) |
| 1789 | - | - | 上海交大张伟楠强化学习课程第13讲：离线强化学习 | 35:30 | [link](https://www.bilibili.com/video/BV1Qopze2EYU) |
| 1790 | - | - | 上海交大张伟楠强化学习课程第14讲：多智能体强化学习I | 33:03 | [link](https://www.bilibili.com/video/BV1Qopze2E1M) |
| 1791 | - | - | 上海交大张伟楠强化学习课程第14讲：多智能体强化学习II | 33:44 | [link](https://www.bilibili.com/video/BV1Qopze2Ep6) |
| 1792 | - | - | 上海交大张伟楠强化学习课程第14讲：多智能体强化学习III | 34:30 | [link](https://www.bilibili.com/video/BV1GopzemEF2) |
| 1793 | - | - | 上海交大张伟楠强化学习课程第14讲：多智能体强化学习IV | 32:58 | [link](https://www.bilibili.com/video/BV1TspzezEoo) |
| 1794 | - | - | 上海交大张伟楠强化学习课程第15讲：AI Agent与决策大模型I | 32:58 | [link](https://www.bilibili.com/video/BV1TspzezEbE) |
| 1795 | - | - | 上海交大张伟楠强化学习课程第15讲：AI Agent与决策大模型II | 31:18 | [link](https://www.bilibili.com/video/BV14spzezExv) |
| 1796 | - | - | 上海交大张伟楠强化学习课程第15讲：AI Agent与决策大模型III | 24:57 | [link](https://www.bilibili.com/video/BV14spzezE85) |
| 1797 | - | - | 上海交大张伟楠强化学习课程第16讲：基于扩散模型的强化学习 | 45:57 | [link](https://www.bilibili.com/video/BV12spzezE9Y) |
| 1798 | - | - | 面向python、算法工程师的agent开发教程 s1-介绍 | 9:15 | [link](https://www.bilibili.com/video/BV12AwDzgEwe) |
| 1799 | - | - | 面向python、算法工程师的agent开发教程 s2-图解+调试的方式查看agent数据流控制（查看agent是如何运行的） | 63:01 | [link](https://www.bilibili.com/video/BV1XADnBBEMy) |
| 1800 | - | - | 面向python、算法工程师的agent开发教程 s3-简单介绍一下agentscope的闪光点～ | 53:07 | [link](https://www.bilibili.com/video/BV1ksd9BcEx3) |
| 1801 | - | - | 【PaperTrail】把 DeepSeek 论文 Agent 蒸馏到 4B：数据采集、SFT 训练与本地部署｜源码分享 | 33:06 | [link](https://www.bilibili.com/video/BV12CY96EEFP) |
| 1802 | - | - | 【PaperTrail】Agent 技术拆解 S1：用 DeepSeek 和 AgentScope 搭建论文助手 | 12:43 | [link](https://www.bilibili.com/video/BV1Zkpp6HEuS) |
| 1803 | - | - | 【PaperTrail】Agent 技术拆解 S2：记录大模型交互轨迹，为 SFT 准备数据 | 9:01 | [link](https://www.bilibili.com/video/BV15Cpu65Esb) |
| 1804 | - | - | 图解deepseek的grpo原理、以debug形式阅读grpo的源码 | 43:09 | [link](https://www.bilibili.com/video/BV1wFNCehERn) |
| 1805 | - | - | deepseek-r1复现踩坑系列1: 多机多卡环境下GRPO训练32B大模型的框架对比 | 31:09 | [link](https://www.bilibili.com/video/BV1tGGezxEGg) |
| 1806 | - | - | deepseek-r1复现踩坑系列2: verl的二次开发-reward模块 | 51:43 | [link](https://www.bilibili.com/video/BV1TwV1zdEHw) |
| 1807 | - | - | 一个视频带你搞懂 verl里面的ray到底起什么作用？verl里面的worker怎么使用？——verl源码解读系列 | 53:53 | [link](https://www.bilibili.com/video/BV116gozmEdn) |
| 1808 | - | - | 由浅入深的了解 verl如何使用fsdp初始化model并且计算logits——verl源码解读系列 | 28:52 | [link](https://www.bilibili.com/video/BV1gjgqzYEJ3) |
| 1809 | - | - | 文本转向量教程s1——总体介绍 | 8:18 | [link](https://www.bilibili.com/video/BV1dw4m1o7X9) |
| 1810 | - | - | 文本转向量教程s2——认识文本转向量方法（sbert本质和推理加速） | 23:26 | [link](https://www.bilibili.com/video/BV1ex4y1S7u5) |
| 1811 | - | - | 文本转向量教程s3——Trainer二次开发（embedding为例） | 67:12 | [link](https://www.bilibili.com/video/BV1BC411L7tB) |
| 1812 | - | - | 为什么我的模型就没有办法使用ddp——基于bert做embedding任务 使用ddp进行训练 | 17:17 | [link](https://www.bilibili.com/video/BV1ii421e7V6) |
| 1813 | - | - | qwen3-embedidng、qwen3-reranker模型解读 使用ray进行部署 | 45:15 | [link](https://www.bilibili.com/video/BV18FThzuE4b) |
| 1814 | - | - | transformers源码阅读——入门（提高nlp工程师的工程能力） | 11:33 | [link](https://www.bilibili.com/video/BV1DN4y1X7av) |
| 1815 | - | - | transformers源码阅读——transformers包的文件框架介绍 | 12:45 | [link](https://www.bilibili.com/video/BV1Tm4y1M7nQ) |
| 1816 | - | - | transformers源码阅读——如何看懂模型代码（以llama为例） | 39:07 | [link](https://www.bilibili.com/video/BV1qj411y7kF) |
| 1817 | - | - | 图解llama架构 解读源码实现 | 30:31 | [link](https://www.bilibili.com/video/BV1nK4y1F7x7) |
| 1818 | - | - | transformers源码阅读——llama模型调试 | 43:36 | [link](https://www.bilibili.com/video/BV1Cw411y7gs) |
| 1819 | - | - | transfomers源码阅读——Trainer解读系列1_了解训练流程 | 31:58 | [link](https://www.bilibili.com/video/BV1b8411y7rR) |
| 1820 | - | - | transformers源码阅读——Trainer解读系列2_关键方法 | 25:08 | [link](https://www.bilibili.com/video/BV1GN411n7rS) |
| 1821 | - | - | transformers疑惑解答S1——transformers是怎么保存模型权重的？ | 9:33 | [link](https://www.bilibili.com/video/BV1nw411y7qL) |
| 1822 | - | - | longlora是怎么实现的——如何在transformers的模型上修改的 | 5:12 | [link](https://www.bilibili.com/video/BV1JN4y1f7JX) |
| 1823 | - | - | transformers二次开发——（定义自己的数据加载器 模型 训练器）bge模型微调流程 | 36:39 | [link](https://www.bilibili.com/video/BV1eu4y1x7ix) |
| 1824 | - | - | transformers二次开发——bge-reranker模型微调流程 | 19:17 | [link](https://www.bilibili.com/video/BV1sQ4y137Ft) |
| 1825 | - | - | 强化学习TRL包源码解读S1——reward_Trainer | 21:31 | [link](https://www.bilibili.com/video/BV1RG411y71U) |
| 1826 | - | - | 强化学习TRL包源码解读S2——PPO | 22:51 | [link](https://www.bilibili.com/video/BV1vy4y1P7GT) |
| 1827 | - | - | transformers源码阅读——neftune的工程实现 | 10:21 | [link](https://www.bilibili.com/video/BV1YQ4y1n7c6) |
| 1828 | - | - | transformers源码阅读——gradient_checkpointing详解 | 8:30 | [link](https://www.bilibili.com/video/BV1K84y1Q7hH) |
| 1829 | - | - | transformers源码阅读——投机采样原理和实现方法 | 25:20 | [link](https://www.bilibili.com/video/BV1ZC4y177Tw) |
| 1830 | - | - | 大模型量化是怎么实现的——transformers源码解读 | 11:51 | [link](https://www.bilibili.com/video/BV1Ga4y1D7ed) |
| 1831 | - | - | chatglm3源码阅读——吐槽角度 | 21:08 | [link](https://www.bilibili.com/video/BV1Rv411F7Mk) |
| 1832 | - | - | 国内的大模型结构和llama有多相似？ | 22:20 | [link](https://www.bilibili.com/video/BV15j411J7QP) |
| 1833 | - | - | transformers源码阅读——mixtral模型解读——MoE实现细节 | 35:13 | [link](https://www.bilibili.com/video/BV19N411G7J2) |
| 1834 | - | - | transformers源码阅读——图解mixtral模型——图解MoE细节 | 25:08 | [link](https://www.bilibili.com/video/BV1Xu4y1K7zn) |
| 1835 | - | - | transformers二次开发——百度轩辕70b大模型数据调度的实现 | 32:36 | [link](https://www.bilibili.com/video/BV1qT4y1H7G1) |
| 1836 | - | - | transformers二次开发——为什么要实现自己的sft代码 | 26:39 | [link](https://www.bilibili.com/video/BV1sK4y1z7LV) |
| 1837 | - | - | transformers二次开发——为什么要实现自己的sentence-embedding训练代码 | 19:47 | [link](https://www.bilibili.com/video/BV1bN4y1n7Ex) |
| 1838 | - | - | miniCPM系列S1——技术报告解读（吊打llama2-70b-chat模型？） | 30:51 | [link](https://www.bilibili.com/video/BV1cC411r7ZG) |
| 1839 | - | - | 手把手带你发现transformers的bug 并且修复它！ | 29:53 | [link](https://www.bilibili.com/video/BV16F4m1V7E1) |
| 1840 | - | - | 我的pr被transformers官方merge了&如何使用vscode和tensorboard查看训练日志 | 12:05 | [link](https://www.bilibili.com/video/BV1CZ421878s) |
| 1841 | - | - | 图解minicpm-v-2.6源码（debug的形式 一个视频看懂他的网络结构） | 53:09 | [link](https://www.bilibili.com/video/BV1SCYSeYET9) |
| 1842 | - | - | 一个视频让你对flash attention2下头（比较FA2和sdpa的效率） | 10:55 | [link](https://www.bilibili.com/video/BV18ceWeFEoP) |
| 1843 | - | - | transformers集成了Liger Kernel：在llm训练的时间更少、显存使用的更少 | 16:25 | [link](https://www.bilibili.com/video/BV1XCWzeJE7A) |
| 1844 | - | - | 如何优雅的修改transformers包的模型结构——面向nlp小白的开发教程 | 28:21 | [link](https://www.bilibili.com/video/BV1KhWmehEVz) |
| 1845 | - | - | transformers一个非常严重的bug——在使用梯度累计的时候 loss不等效 | 33:51 | [link](https://www.bilibili.com/video/BV1oY1aYzEVi) |
| 1846 | - | - | AutoModel的lazy加载方式原理解读 | 26:07 | [link](https://www.bilibili.com/video/BV1mhmeYiE3T) |
| 1847 | - | - | 图解大模型的KV Cache——图解+transformers源码阅读 | 60:55 | [link](https://www.bilibili.com/video/BV1U5CcYeEX8) |
| 1848 | - | - | vLLM源码阅读s1——源码介绍 | 18:16 | [link](https://www.bilibili.com/video/BV1Vp421S7zg) |
| 1849 | - | - | vLLM源码阅读s2——是如何进行离线推理的 | 43:45 | [link](https://www.bilibili.com/video/BV1qE42157Rn) |
| 1850 | - | - | vllm二次开发——自定义的新模型如何部署在vllm上S1 | 58:54 | [link](https://www.bilibili.com/video/BV1xbypYtEu2) |
| 1851 | - | - | 多模态大模型LLaVA模型讲解——transformers源码解读 | 40:13 | [link](https://www.bilibili.com/video/BV1nw4m1S7nZ) |
| 1852 | - | - | 自定义多模态大模型LLaVA——LLaVA系列 | 21:44 | [link](https://www.bilibili.com/video/BV1GS411P74b) |
| 1853 | - | - | 训练LLaVA模型（数据集构建、基于Trainer的训练框架搭建）——LLaVA系列 | 84:57 | [link](https://www.bilibili.com/video/BV1Si421v7j1) |
| 1854 | - | - | nlp开发利器——vscode如何debug transformers源码 | 10:15 | [link](https://www.bilibili.com/video/BV1Hh4y1i7Li) |
| 1855 | - | - | nlp开发利器——vscode如何debug transformers源码(torchrun形式） | 11:45 | [link](https://www.bilibili.com/video/BV1b84y1R75V) |
| 1856 | - | - | nlp开发利器——vscode如何debug transformers源码(deepspeed形式） | 7:07 | [link](https://www.bilibili.com/video/BV1xC4y1P7LH) |
| 1857 | - | - | nlp开发利器——vscode debug nlp大工程（最最最优雅的方式） | 13:31 | [link](https://www.bilibili.com/video/BV1wt421V718) |
| 1858 | - | - | 我的vscode主题配色 | 3:00 | [link](https://www.bilibili.com/video/BV1xv411c7ti) |
| 1859 | - | - | 使用vscode愉快的阅读transformers源码 | 8:11 | [link](https://www.bilibili.com/video/BV14b4y1G7bF) |
| 1860 | - | - | nlp开发利器——vscode愉快的写nlp代码 | 10:59 | [link](https://www.bilibili.com/video/BV1LH4y1H7jj) |
| 1861 | - | - | transformers更新了啥S2——在国庆的时候 更新了啥（闲聊） | 2:29 | [link](https://www.bilibili.com/video/BV1Lw411y7kD) |
| 1862 | - | - | transformers更新了啥S1——InternLM模型和llama模型竟然是差不多的 | 2:10 | [link](https://www.bilibili.com/video/BV1rz4y1G74d) |
| 1863 | - | - | transformers更新了啥S3——23-10-22日更新 | 10:27 | [link](https://www.bilibili.com/video/BV1Bj411v7PA) |
| 1864 | - | - | transformers更新了啥S3——23-11-05日更新 | 9:15 | [link](https://www.bilibili.com/video/BV1BC4y1J7Rs) |
| 1865 | - | - | transformers包新功能——一行代码将模型效率提高40% | 6:53 | [link](https://www.bilibili.com/video/BV1ap4y1d7MZ) |
| 1866 | - | - | [国内一小伙自制]地理坐标系的映射关系 | 0:41 | [link](https://www.bilibili.com/video/BV1uR4y1W7hZ) |
| 1867 | - | - | 3d视角查看中国各个省级地图(demo) | 0:52 | [link](https://www.bilibili.com/video/BV1JF41187Jf) |
| 1868 | - | - | python入门教程之写代码素质1【管理数据和代码】【中国人不骗中国人，这个绝对是最走心的教程】 | 13:15 | [link](https://www.bilibili.com/video/BV1Vg411T74D) |
| 1869 | - | - | 最走心的python学习分享【没有广告、没有焦虑、单纯的分享干货】 | 14:03 | [link](https://www.bilibili.com/video/BV1JP4y157uV) |
| 1870 | - | - | 我用技术成功追星啦 | 9:40 | [link](https://www.bilibili.com/video/BV1DT4y1R79v) |
| 1871 | - | - | 手写数值识别web应用 | 1:42 | [link](https://www.bilibili.com/video/BV15X4y1M7DT) |
| 1872 | - | - | python通关羊了个羊 | 1:35 | [link](https://www.bilibili.com/video/BV1HG4y1q7gi) |
| 1873 | - | - | vscode调试jupyter notebook | 0:47 | [link](https://www.bilibili.com/video/BV1KB4y1B78v) |
| 1874 | - | - | 细节怪27秋招面经八股合集：Day00 Multi-Agent 和 ReAct 和 Harness 有什么区别（不理解为什么会问这样的问题 | 6:39 | [link](https://www.bilibili.com/video/BV1k3YJ6GEek) |
| 1875 | - | - | 细节怪27秋招面经八股合集：ReAct 和 Plan-and-Excute 有什么区别 | 9:07 | [link](https://www.bilibili.com/video/BV1EEeA64ET3) |
| 1876 | - | - | 细节怪-2027秋招必学：如何拆解一个Agent （从loop到Harness,从openclaw 到Hermes ) | 21:35 | [link](https://www.bilibili.com/video/BV1GcKV6rEQq) |
| 1877 | - | - | 细节怪-27秋招必学：Claude Code 强大的Runtime到底是什么样的 | 34:00 | [link](https://www.bilibili.com/video/BV1VB3Y61EyE) |
| 1878 | - | - | 细节怪27秋招必学-Claude Code的上下文工程（听说最近删除了80%的System Prompt?!) | 21:52 | [link](https://www.bilibili.com/video/BV1Z33o6HEmG) |
| 1879 | - | - | 细节怪27秋招必学：Claude Code 的 Memory 是如何设计的（CLADE.md和Auto Memory) | 23:32 | [link](https://www.bilibili.com/video/BV1xr3f6zEcS) |
| 1880 | - | - | 细节怪-27秋招必学：Claude Code如何组织Skill,MCP,等tool(Action层） | 28:29 | [link](https://www.bilibili.com/video/BV1dou96KEGk) |
| 1881 | - | - | 细节怪27秋招必学：Herman Agent 惊艳一时的爱马仕究竟是如何完成自进化的？ | 13:38 | [link](https://www.bilibili.com/video/BV1wBbT6aEMY) |
| 1882 | - | - | 细节怪手撕LLM-混合专家模型MoE详解 | 18:08 | [link](https://www.bilibili.com/video/BV1iji7BwEqC) |
| 1883 | - | - | 细节怪-手撕LLM之如何训练一个大模型（大模型的能力，特点以及发展趋势）【本期为后续预告】 | 18:21 | [link](https://www.bilibili.com/video/BV1yZBbBSEUg) |
| 1884 | - | - | 细节怪-手撕LLM-LLaMA（激活函数SwiGLU, GQA…数学原理分析) | 22:58 | [link](https://www.bilibili.com/video/BV1damrBbErz) |
| 1885 | - | - | 细节怪-手撕LLM-Decoder-only之GLM（国内模型，创新点分析，架构设计） | 13:50 | [link](https://www.bilibili.com/video/BV1bZmiBKE4E) |
| 1886 | - | - | 细节怪-手撕LLM- GPT系列（细节设计分析，发展历程回顾） | 16:08 | [link](https://www.bilibili.com/video/BV11AmxBAEiR) |
| 1887 | - | - | 细节怪-手斯LLM- T5（Encoder-Decoder)创新点原理分析 | 17:43 | [link](https://www.bilibili.com/video/BV1W12QBiEoy) |
| 1888 | - | - | 细节怪-手撕LLM-Bert全景分析：ALBERT(Encoder-only) | 11:35 | [link](https://www.bilibili.com/video/BV1HU2SBoENv) |
| 1889 | - | - | 细节怪之手撕LLM-Bert 全景分析：RoBERTa（四大优化点剖析） | 11:49 | [link](https://www.bilibili.com/video/BV1aw25B3End) |
| 1890 | - | - | 细节怪之手撕LLM-Bert 全景分析（1）：Bert 细节分析和原理介绍（Encoder-only) | 17:27 | [link](https://www.bilibili.com/video/BV1eq25BLE5N) |
| 1891 | - | - | 细节怪-手撕LLM-旋转位置编码（3）：代码实现 | 6:12 | [link](https://www.bilibili.com/video/BV1K6UuBoEiY) |
| 1892 | - | - | 细节怪-手撕LLM-PE&RoPE: 为什么需要旋转位置编码（数学证明） | 9:55 | [link](https://www.bilibili.com/video/BV1MbycBbE4A) |
| 1893 | - | - | 细节怪-手撕LLM-PE&RoPE(1)：什么是旋转位置编码（原理分析） | 10:39 | [link](https://www.bilibili.com/video/BV19jycBiEBd) |
| 1894 | - | - | 细节怪-手撕Transformer: Add & Norm 残差连接和归一化的理论原理 | 10:24 | [link](https://www.bilibili.com/video/BV1agCeBdEdW) |
| 1895 | - | - | 细节怪-手撕Transformer: 位置编码（设计原理与示意图） | 7:10 | [link](https://www.bilibili.com/video/BV1DxyWBfEh1) |
| 1896 | - | - | 细节怪-手撕Transformer: 注意力机制之多头注意力（为什么需要多头注意力，为什么多头可以提取的多维信息，计算优化和纬度变化） | 9:57 | [link](https://www.bilibili.com/video/BV12jsyz2EeV) |
| 1897 | - | - | 细节怪-手撕Transformer: 注意力机制之掩码注意力（为什么需要掩码，如何构建掩码） | 5:42 | [link](https://www.bilibili.com/video/BV1WpsyzkEY3) |
| 1898 | - | - | 细节怪-手撕Transformer(2): 注意力机制原理分析与代码实践！（公式推导；自注意力） | 30:10 | [link](https://www.bilibili.com/video/BV1c9sizJEMv) |
| 1899 | - | - | 细节怪-手撕Transformer(1) : 整体架构（从数学原理到代码实践） | 4:49 | [link](https://www.bilibili.com/video/BV1DX4BzyEfC) |
| 1900 | - | - | 细节怪-手撕LLM之如何估算模型所需的显存（看完就会！算力选购必备~)【B站AI创作大赛-开放赛道】 | 6:54 | [link](https://www.bilibili.com/video/BV1Lj69BkEpi) |
| 1901 | - | - | 细节怪-手撕LLM之 LoRA 原理（大模型算法面试必考！）【2026开个好头】 | 13:23 | [link](https://www.bilibili.com/video/BV1wHkYBiEap) |
| 1902 | - | - | 细节怪-手撕 LLM 之 KV Cache 推理优化（1）实例分析（8分钟透彻理解） | 8:25 | [link](https://www.bilibili.com/video/BV1mDzcByEcv) |
| 1903 | - | - | 细节怪-手撕 LLM 之 vLLM 推理优化（2）最流行的大模型部署方式（一学就会！） | 12:43 | [link](https://www.bilibili.com/video/BV1wvzuBfEgD) |
| 1904 | - | - | 细节怪-手撕 LLM 之 Flash Attention 训练与推理优化（4）超清晰的讲解和手动推导，零基础也能听懂！ | 16:28 | [link](https://www.bilibili.com/video/BV1PazCBZEAK) |
| 1905 | - | - | 细节怪-手撕 LLM 之 TensorRT-LLM 推理优化（3）静态计算图，深度算子融合，超详细解读（一学就会！） | 18:25 | [link](https://www.bilibili.com/video/BV1mkz6BWEF4) |
| 1906 | - | - | 细节怪-手撕 LLM 系列：DeepSpeed 详解（ ZeRO 三阶段和底层通信原理，值得细细品味！) | 26:26 | [link](https://www.bilibili.com/video/BV1yP6GBzE7V) |
| 1907 | - | - | 细节怪-手撕 LLM 之 RLHF 概念详解与PPO算法详解（1）（近期高频八股，系统搞定！） | 19:10 | [link](https://www.bilibili.com/video/BV1LB6nBJECs) |
| 1908 | - | - | 细节怪-手撕 LLM 之大模型常用的几种精度（FP32，FP16，BF16，NF8，实例分析，一步到位，小知识点扫盲） | 19:17 | [link](https://www.bilibili.com/video/BV1SDZXB3Ewe) |
| 1909 | - | - | 细节怪-手撕 LLM 系列之 QLoRA 详解（什么是双重量化） | 7:56 | [link](https://www.bilibili.com/video/BV1BqZeBMEvZ) |
| 1910 | - | - | 细节怪手撕 LLM 之 DeepSeek-V4 注意力机制（CSA，HCA，Sliding Window, 从架构到原理 | 21:42 | [link](https://www.bilibili.com/video/BV1vsd3BcE97) |
| 1911 | - | - | 细节怪-手撕Transformer: KL散度公式推导（从信息量到交叉熵） | 6:33 | [link](https://www.bilibili.com/video/BV1Pxui6eErQ) |
| 1912 | - | - | 细节怪-手撕Transformer: RL中的KL散度，与DPO替代奖励函数的解析解 | 6:50 | [link](https://www.bilibili.com/video/BV1nQuv6oEKW) |
| 1913 | - | - | 手撕 LLM - 沉浸式实战跟练：手撕 MHA（多头注意力）大模型算法工程师必备技能！ | 15:33 | [link](https://www.bilibili.com/video/BV1TqkVB9EPL) |
| 1914 | - | - | 沉浸式手撕 LLM 系列 —— 手撕 GQA （大模型算法工程师入门必学）十分钟搞定！ | 11:30 | [link](https://www.bilibili.com/video/BV12ozABEEEG) |
| 1915 | - | - | 沉浸式手撕 LLM ：RoPE (旋转位置编码）细节只有手撕了才知道！大模型算法工程师入门必学～ | 9:54 | [link](https://www.bilibili.com/video/BV1soz2BMEmY) |
| 1916 | - | - | 沉浸式手撕 LLM 系列：Softmax (面试题目，新鲜出炉，做了一点拓展，后面的还得撕一下online softmax) | 5:02 | [link](https://www.bilibili.com/video/BV1yH6FBzE6t) |
| 1917 | - | - | 手撕 LLM 之沉浸式实战 plus : SFT-loss 原理分析公式推导 | 7:35 | [link](https://www.bilibili.com/video/BV1QoGf6HEqU) |
| 1918 | - | - | 沉浸式手撕实战：SFT-loss （numpy) 面试必会手撕跟练! | 4:44 | [link](https://www.bilibili.com/video/BV1EUEF6LEb9) |
| 1919 | - | - | LLM 应用开发原理-Agent 入门介绍（2）（Function calling 底层原理，如何选择合适的范式） | 13:21 | [link](https://www.bilibili.com/video/BV1nCcPzYExP) |
| 1920 | - | - | LLM 应用开发原理：Agent 开发框架介绍（1）低代码开发平台（dify, Coze, n8n, CrewAI) | 13:28 | [link](https://www.bilibili.com/video/BV1dNFUzVEhk) |
| 1921 | - | - | LLM 应用开发实战篇 ：从零构建一个 Agent Skill (小白友好，有手就会）第一期 | 11:22 | [link](https://www.bilibili.com/video/BV1MRf7B1EZW) |
| 1922 | - | - | LLM 应用开发原理实战篇：从零手搓一个skill (包含自己手搓和使用 skill-creator 来构建）小白友好，有手就行 | 16:07 | [link](https://www.bilibili.com/video/BV1naf7BhE8J) |
| 1923 | - | - | LLM 应用开发原理实战篇：安装一些好用的 skill (手把手教学，有手就行） | 5:45 | [link](https://www.bilibili.com/video/BV1uffJBDEGD) |
| 1924 | - | - | LLM 应用开发原理—拆解现象级 Agent 产品 OpenClaw 大虾（源码加原理） | 10:00 | [link](https://www.bilibili.com/video/BV15NQQBaE93) |
| 1925 | - | - | 多模态 之 CLIP ｜ 1、CLIP 网络结构精讲 | 24:33 | [link](https://www.bilibili.com/video/BV1BeZFBGEhe) |
| 1926 | - | - | 多模态 之 CLIP / 2、官方不开源训练代码？给你推荐个社区版开源复现 -- OpenCLIP | 19:57 | [link](https://www.bilibili.com/video/BV1YP5v6tEop) |
| 1927 | - | - | 多模态 之 ViLT ｜ 1、ViLT 的 Single Stream 结构 | 10:50 | [link](https://www.bilibili.com/video/BV1YUVJ6EERN) |
| 1928 | - | - | 多模态 之 ViLT ｜2、模型结构详解、三类任务、模型权重初始化方案 | 20:00 | [link](https://www.bilibili.com/video/BV1pwVU6VEjS) |
| 1929 | - | - | MLM｜Masked Language Model 详解 & Whole Word Masking | 14:36 | [link](https://www.bilibili.com/video/BV1QB7S63Ed2) |
| 1930 | - | - | 多模态 之 BLIP｜  一个模型 可以支持 3种工作模式（图文对比、图文匹配、配文生成） | 24:41 | [link](https://www.bilibili.com/video/BV1YwTk6tEPj) |
| 1931 | - | - | 多模态 之 BLIP｜ CapFilt ：自举式训练（Bootstrapped），用模型反哺数据 | 15:27 | [link](https://www.bilibili.com/video/BV1UMMN6DEvs) |
| 1932 | - | - | 3）BeamSearch 与 NucleusSampling | 7:05 | [link](https://www.bilibili.com/video/BV1Mr3Q64E8o) |
| 1933 | - | - | 多模态 之 YOLO-World ｜ 1、整体网络结构 | 13:57 | [link](https://www.bilibili.com/video/BV1S78w6eEAK) |
| 1934 | - | - | 多模态 之 YOLO-World ｜2、训练数据集 以及 Grounding 数据集的标注格式要求 （基于 Ultralytics） | 14:54 | [link](https://www.bilibili.com/video/BV1Nm826QEc4) |
| 1935 | - | - | 3）online/offline vocabulary | 13:32 | [link](https://www.bilibili.com/video/BV1R7tN6VE5T) |
| 1936 | - | - | 4）CLIP Text Encoder 处理文本流程 | 9:31 | [link](https://www.bilibili.com/video/BV19LtN6yEoH) |
| 1937 | - | - | 5）T-CSP Layer | 11:55 | [link](https://www.bilibili.com/video/BV1RLtN6yE1M) |
| 1938 | - | - | 6）Max-Sigmoid Attention | 14:40 | [link](https://www.bilibili.com/video/BV1Znt36vEc1) |
| 1939 | - | - | 7）Image-pooling Attention | 10:17 | [link](https://www.bilibili.com/video/BV1BTbF6zEQh) |
| 1940 | - | - | 8）World Head / Contrastive Head | 18:33 | [link](https://www.bilibili.com/video/BV1Wcbw6HEVY) |
| 1941 | - | - | 9）Region-Text Contrastive Loss | 7:36 | [link](https://www.bilibili.com/video/BV1webT6NEdk) |
| 1942 | - | - | 多模态 之 YOLOE ｜ 1、YOLOE 的三种模式 & 三阶段训练 & 模型整体网络结构 | 13:09 | [link](https://www.bilibili.com/video/BV1dMY16gEJP) |
| 1943 | - | - | 2）Text Embedding 与 RepRTA  网络结构 | 14:08 | [link](https://www.bilibili.com/video/BV1wzeh62Eg1) |
| 1944 | - | - | 3）YOLO-World 与 YOLOE 对比 | 8:50 | [link](https://www.bilibili.com/video/BV1fXev6pE8L) |
| 1945 | - | - | 4）BNContrastiveHead | 12:17 | [link](https://www.bilibili.com/video/BV1FEha6uESV) |
| 1946 | - | - | 5）RepRTA 结构重参数化 推导 & 代码讲解 | 14:06 | [link](https://www.bilibili.com/video/BV1hLaN6JE9Z) |
| 1947 | - | - | 6）第二阶段训练 参数冻结 | 9:53 | [link](https://www.bilibili.com/video/BV1ozaW61Eyx) |
| 1948 | - | - | 7）第二阶段整体训练框架 & 视觉提示 mask 预处理 | 10:18 | [link](https://www.bilibili.com/video/BV1LLYP6sEMk) |
| 1949 | - | - | 8）SAVPE 网络结构 & 分组加权聚合 | 20:59 | [link](https://www.bilibili.com/video/BV15Vp46ZE6j) |
| 1950 | - | - | Tokenizer｜1、基础知识准备 ：Unicode、UTF-8、ASCII | 10:50 | [link](https://www.bilibili.com/video/BV116daB6EC5) |
| 1951 | - | - | Tokenizer｜2、三大分词方法 ：Word / Character / Subword | 22:05 | [link](https://www.bilibili.com/video/BV1NtdZB1Eai) |
| 1952 | - | - | Tokenizer｜3、BPE 与 BBPE Tokenizer 详解 | 14:02 | [link](https://www.bilibili.com/video/BV1YYdmBhErJ) |
| 1953 | - | - | Tokenizer｜4、词边界符 | 10:06 | [link](https://www.bilibili.com/video/BV1cE9xByEXx) |
| 1954 | - | - | 5）WordPiece Tokenizer | 24:59 | [link](https://www.bilibili.com/video/BV14k3Q6REHR) |
| 1955 | - | - | 1）Flickr8k | 8:59 | [link](https://www.bilibili.com/video/BV1Z6Gs6NEaJ) |
| 1956 | - | - | 多模态 常用数据集｜ Flickr30k & Entities （Grounding 任务常用） | 11:51 | [link](https://www.bilibili.com/video/BV1kPpJ6DEhk) |
| 1957 | - | - | Conda 环境管理工具 | 56:09 | [link](https://www.bilibili.com/video/BV1bqKE6pEmD) |
| 1958 | - | - | Enzo 深度学习  入门篇 （更新中） | 258:20 | [link](https://www.bilibili.com/video/BV1tLuw6VEJd) |
| 1959 | - | - | 反向传播 ：计算图、叶子节点/非叶子节点/根节点、requires_grad、grad | 19:38 | [link](https://www.bilibili.com/video/BV12Q4X6aEjt) |
| 1960 | - | - | 模型压缩神技：结构重参数化 ： 训练时多分支，推理时单卷积！ | 26:40 | [link](https://www.bilibili.com/video/BV1uhN96JEzF) |
| 1961 | - | - | 环境配置 依赖包安装 常见问题 【50系显卡 Blackwell架构】 | 15:03 | [link](https://www.bilibili.com/video/BV1RLtU6eE7f) |
| 1962 | - | - | 【即插即用 卷积模块】蛇形卷积 DSConv ：Dynamic Snake Convolution | 21:19 | [link](https://www.bilibili.com/video/BV18SYt6EE64) |
| 1963 | - | - | 【即插即用 卷积模块】中国结卷积 CKConv ：Chinese Knot Convolution | 9:42 | [link](https://www.bilibili.com/video/BV1i9eH6LEkq) |
| 1964 | - | - | 【即插即用 卷积模块】方向引导的边缘门控卷积 DEGConv ：Direction-guided Edge Gated Convolution | 27:08 | [link](https://www.bilibili.com/video/BV1xRhs6hEXr) |
| 1965 | - | - | 【即插即用 注意力模块】LA：Linear Attention | 14:33 | [link](https://www.bilibili.com/video/BV1N8at6uEpi) |
| 1966 | - | - | 【即插即用 卷积模块】风车卷积 PConv ：Pinwheel-shaped Convolution | 9:27 | [link](https://www.bilibili.com/video/BV1UUpt6XEJZ) |
| 1967 | - | - | self-Attention｜自注意力机制 ｜位置编码 ｜ 理论 + 代码 | 19:00 | [link](https://www.bilibili.com/video/BV1qo4y1F7Ep) |
| 1968 | - | - | Multi-Head Attention / 算法 + 代码 | 7:42 | [link](https://www.bilibili.com/video/BV1gV4y167rS) |
| 1969 | - | - | ViT｜ Vision Transformer ｜理论 + 代码 | 25:28 | [link](https://www.bilibili.com/video/BV1xm4y1b7Pw) |
| 1970 | - | - | Positional Encoding ｜ 位置编码 | 11:47 | [link](https://www.bilibili.com/video/BV1z84y1R7t8) |
| 1971 | - | - | Swin Transformer ｜ Abstract | 14:53 | [link](https://www.bilibili.com/video/BV1Nz4y177aW) |
| 1972 | - | - | Swin Transformer （上） | 28:27 | [link](https://www.bilibili.com/video/BV1xF41197E4) |
| 1973 | - | - | Swin Transformer （下） | 18:21 | [link](https://www.bilibili.com/video/BV1qX4y1Y7mj) |
| 1974 | - | - | DETR ｜ 1、算法概述 | 7:13 | [link](https://www.bilibili.com/video/BV1Zo4y1A7FB) |
| 1975 | - | - | DETR ｜2、模型结构讲解 | 17:25 | [link](https://www.bilibili.com/video/BV1Gh4y127eZ) |
| 1976 | - | - | DETR ｜3、损失函数讲解 | 23:24 | [link](https://www.bilibili.com/video/BV1qu411V7ud) |
| 1977 | - | - | Attention Map ｜ 复现 DETR 论文中 encoder layer 的 attention map | 10:19 | [link](https://www.bilibili.com/video/BV1jC411W7sC) |
| 1978 | - | - | Deformable Convolution ｜可变形卷积 | 12:04 | [link](https://www.bilibili.com/video/BV1Sh4y1y75i) |
| 1979 | - | - | Deformable DETR / 1、Abstract  算法概述 | 11:24 | [link](https://www.bilibili.com/video/BV1rh4y1F7fG) |
| 1980 | - | - | Deformable DETR ｜ 2、backbone 、MultiHeadAttention 公式讲解 | 15:19 | [link](https://www.bilibili.com/video/BV1vr4y1o73B) |
| 1981 | - | - | Deformable DETR｜ 3、Deformable Attention、MSDeformAttention、流程讲解 | 15:02 | [link](https://www.bilibili.com/video/BV1Uj411z7QU) |
| 1982 | - | - | torchvision.models.resnet50() 可以使用哪些参数 ？ 这些参数有什么用 ？ 学习 DETR 必读 ！ | 14:00 | [link](https://www.bilibili.com/video/BV1Ya4y1o7HP) |
| 1983 | - | - | RT-DETR ｜1、abstract 算法概述 | 10:20 | [link](https://www.bilibili.com/video/BV1Nb4y1F7k9) |
| 1984 | - | - | RT-DETR  ｜ 2、backbone | 5:15 | [link](https://www.bilibili.com/video/BV1Ac411k7Sg) |
| 1985 | - | - | RT-DETR  ｜ 3、AIFI | 9:10 | [link](https://www.bilibili.com/video/BV1be411S74w) |
| 1986 | - | - | RT- DETR ｜ 4、CCFM | 7:52 | [link](https://www.bilibili.com/video/BV1DG411z71m) |
| 1987 | - | - | 5）CCFM 收尾工作 | 7:11 | [link](https://www.bilibili.com/video/BV1bUR3BDEWC) |
| 1988 | - | - | 6）decoder 整体网络结构 | 5:22 | [link](https://www.bilibili.com/video/BV1njt36uEk6) |
| 1989 | - | - | 7）denoising 理论讲解 | 18:05 | [link](https://www.bilibili.com/video/BV1Fjt36uEKD) |
| 1990 | - | - | 8）denoising 代码讲解 | 13:22 | [link](https://www.bilibili.com/video/BV1fJt36KEw9) |
| 1991 | - | - | 9）IoU-aware query selection | 6:43 | [link](https://www.bilibili.com/video/BV1fJt36KEuA) |
| 1992 | - | - | 10）IoU-aware query selection | 11:23 | [link](https://www.bilibili.com/video/BV1PMt36yEUR) |
| 1993 | - | - | 11）decoder MSDeformableAttention | 17:02 | [link](https://www.bilibili.com/video/BV1A3t36kEnm) |
| 1994 | - | - | 12）损失函数 | 31:11 | [link](https://www.bilibili.com/video/BV1L4t36aErd) |
| 1995 | - | - | 13）RT-DETR 快速跑通 | 15:14 | [link](https://www.bilibili.com/video/BV1v4t36aEyb) |
| 1996 | - | - | 14）Pycharm远程连接 + 配置 + 全流程跑通 | 10:50 | [link](https://www.bilibili.com/video/BV1Xht36ZE48) |
| 1997 | - | - | RT-DETR v1 ｜快速跑通 + AutoDL | 15:14 | [link](https://www.bilibili.com/video/BV1UWmMBREJ7) |
| 1998 | - | - | RT-DETR / Pycharm 远程连接 (AutoDL) + 配置 + 全流程跑通 | 10:50 | [link](https://www.bilibili.com/video/BV1egm7BxE4T) |
| 1999 | - | - | RT-DETR v2 相较于 v1 的 4个优化点 | 14:47 | [link](https://www.bilibili.com/video/BV1ePwzehEEy) |
| 2000 | - | - | RT-DETRv4 ｜ RT-DETR + DINOv3 | 28:26 | [link](https://www.bilibili.com/video/BV1zbE56sEmG) |
| 2001 | - | - | D-Fine ｜1、FDR ： Fine-grained Distribution Refinement | 27:24 | [link](https://www.bilibili.com/video/BV1JHopYjEV7) |
| 2002 | - | - | D-Fine｜2、损失函数细节精讲 之  FGL 数据准备 | 11:19 | [link](https://www.bilibili.com/video/BV1jHJNzGEDC) |
| 2003 | - | - | D-Fine｜3、损失函数  FGL :  Fine-Grained Localization Loss | 30:23 | [link](https://www.bilibili.com/video/BV1eDJ6zuErg) |
| 2004 | - | - | D-Fine / 4、GO-LDS 全局优化定位自蒸馏、DDFLoss | 16:13 | [link](https://www.bilibili.com/video/BV1kgjXz5EjJ) |
| 2005 | - | - | DEIM / 为什么 DEIM 能让 DETR 收敛提速一倍？？ | 19:39 | [link](https://www.bilibili.com/video/BV1saKAzSEHg) |
| 2006 | - | - | RoPE 旋转位置编码 | 22:46 | [link](https://www.bilibili.com/video/BV1ReLq6BE8i) |
| 2007 | - | - | Vibe Researching / Codex 介绍与安装 | 9:31 | [link](https://www.bilibili.com/video/BV1ZoJG6nEi9) |
| 2008 | - | - | Vibe Researching / Codex 基础使用 | 10:41 | [link](https://www.bilibili.com/video/BV1wSL96YENx) |
| 2009 | - | - | Vibe Researching / Codex - SKILL 基础介绍 | 16:05 | [link](https://www.bilibili.com/video/BV1Qjjh6SEYm) |
| 2010 | - | - | Vibe Researching / Codex - SKILL 实践 ： 创建一个用于收集论文基本信息的 SKILL | 15:17 | [link](https://www.bilibili.com/video/BV1e17g6PEEk) |
| 2011 | - | - | 解放生产力！我整了一个自动整理即插即用模块的 Codex Skill | 4:52 | [link](https://www.bilibili.com/video/BV1rwjd6TE7w) |
| 2012 | - | - | DINO v1 /  自监督学习、无标签的自蒸馏  self-distillation with no labels | 29:54 | [link](https://www.bilibili.com/video/BV1Q74HzeEBY) |
| 2013 | - | - | DINO v2 ｜ 5大改进点概述、整体训练框架解读 | 19:29 | [link](https://www.bilibili.com/video/BV1BoUnByEWr) |
| 2014 | - | - | DINO v3 ｜3阶段训练 +  扩大数据集（LVD-1689M）+ 扩大模型（ ViT-7B/16 ） | 9:49 | [link](https://www.bilibili.com/video/BV1vTvDBWEgG) |
| 2015 | - | - | DINOv3｜多模态｜DINOv3 +  CLIP 图文对齐 方案解析 | 9:14 | [link](https://www.bilibili.com/video/BV1JRd3B6EwN) |
| 2016 | - | - | 1、Dino v1 整体介绍 | 29:54 | [link](https://www.bilibili.com/video/BV1AKDdBsEib) |
| 2017 | - | - | 2、Multi-crop | 17:46 | [link](https://www.bilibili.com/video/BV1kKDdBWEZC) |
| 2018 | - | - | 3、教师网络与学生网络 | 19:33 | [link](https://www.bilibili.com/video/BV1pKDdBWEsp) |
| 2019 | - | - | 4、损失函数 | 16:52 | [link](https://www.bilibili.com/video/BV1HKDdBWEXb) |
| 2020 | - | - | 5、实验｜centering 与 sharpening | 11:57 | [link](https://www.bilibili.com/video/BV1kKDdBWE9E) |
| 2021 | - | - | 6、教师网络参数的更新 | 7:12 | [link](https://www.bilibili.com/video/BV1pKDdBWEbm) |
| 2022 | - | - | 7、实验｜教师网络构建方法的选择 | 3:53 | [link](https://www.bilibili.com/video/BV1AKDdBsE1E) |
| 2023 | - | - | 8、优化器、调度器、各组件重要性分析 | 13:12 | [link](https://www.bilibili.com/video/BV1pKDdBWEJZ) |
| 2024 | - | - | 0、前言 | 3:37 | [link](https://www.bilibili.com/video/BV1scDdBoEoy) |
| 2025 | - | - | 1、数据集构建_LVD142M | 11:20 | [link](https://www.bilibili.com/video/BV1scDdBoEzN) |
| 2026 | - | - | 2、改进点概述 | 19:29 | [link](https://www.bilibili.com/video/BV1scDdBoEzP) |
| 2027 | - | - | 3、patch-level objective | 23:16 | [link](https://www.bilibili.com/video/BV1xcDdBoEKe) |
| 2028 | - | - | 4、Sepeated Head | 4:08 | [link](https://www.bilibili.com/video/BV1ycDdBoEfg) |
| 2029 | - | - | 5、Sinkhorn-Knopp | 15:08 | [link](https://www.bilibili.com/video/BV1scDdBoE85) |
| 2030 | - | - | 6、KoLeo Regularizer | 25:03 | [link](https://www.bilibili.com/video/BV1scDdBoEm9) |
| 2031 | - | - | 1、DINOv3 | 9:49 | [link](https://www.bilibili.com/video/BV1qEDdBLEMk) |
| 2032 | - | - | 2、LVD1689M数据集的构建 | 12:30 | [link](https://www.bilibili.com/video/BV1qEDdBLE6i) |
| 2033 | - | - | 3、第一阶段训练 | 13:18 | [link](https://www.bilibili.com/video/BV1oEDdBLENy) |
| 2034 | - | - | 4、第二阶段训练 ： Gram Anchoring | 32:17 | [link](https://www.bilibili.com/video/BV1ZEDdBLEua) |
| 2035 | - | - | 5、第三阶段训练 High Resolution Adaptat | 3:45 | [link](https://www.bilibili.com/video/BV1jEDdBLEz2) |
| 2036 | - | - | 6、多学生模型并行蒸馏 | 21:49 | [link](https://www.bilibili.com/video/BV1jEDdBLE9c) |
| 2037 | - | - | 7、图文对齐（DINOv3 - CLIP） | 9:14 | [link](https://www.bilibili.com/video/BV1ZHRDBkEjf) |
| 2038 | - | - | 9、2D RoPE | 23:13 | [link](https://www.bilibili.com/video/BV1yfGE6fE3R) |
| 2039 | - | - | 1、自蒸馏训练 环境配置 + 运行 | 35:25 | [link](https://www.bilibili.com/video/BV1utQxBDEtY) |
| 2040 | - | - | 2、多学生模型并行蒸馏 环境配置+运行 | 26:58 | [link](https://www.bilibili.com/video/BV1jEDdBLEy3) |
| 2041 | - | - | yolov1 算法精讲（上） | 14:55 | [link](https://www.bilibili.com/video/BV1ec411T7Rh) |
| 2042 | - | - | yolov1 算法精讲（下） | 22:22 | [link](https://www.bilibili.com/video/BV1ks4y137oU) |
| 2043 | - | - | yolov5 ｜ 手把手代码精读 ｜数据增强 之 仿射变换(Affine)、透视变换(Perspective) | 17:51 | [link](https://www.bilibili.com/video/BV1Vr421h7wF) |
| 2044 | - | - | yolov5 ｜ 手把手代码精读 ｜数据增强 之 仿射变换(Affine)、透视变换(Perspective) / opencv 相关使用 | 9:21 | [link](https://www.bilibili.com/video/BV1sp42117Ti) |
| 2045 | - | - | yolov5 网络结构｜yaml 文件解读 | 11:53 | [link](https://www.bilibili.com/video/BV1tH4y1n7MT) |
| 2046 | - | - | yolov5 网络搭建 代码精讲 | 19:31 | [link](https://www.bilibili.com/video/BV1YZ421e7zH) |
| 2047 | - | - | yolov5 ｜损失函数 ｜ 正样本匹配 | 15:44 | [link](https://www.bilibili.com/video/BV1iH4y1G7hV) |
| 2048 | - | - | yolov5 ｜损失函数 ｜ 正样本匹配  代码精讲 | 15:48 | [link](https://www.bilibili.com/video/BV1nr421j7X5) |
| 2049 | - | - | 番外 ｜ anchor-based 与 anchor-free 、anchor 与 anchor-point、grid cell | 11:42 | [link](https://www.bilibili.com/video/BV1W1421b7uF) |
| 2050 | - | - | yolov8  /  损失函数 之  1、数据预处理 代码精读 | 18:31 | [link](https://www.bilibili.com/video/BV1Rb421n7fr) |
| 2051 | - | - | yolov8  /  损失函数 之  2、正样本匹配 理论讲解 | 7:58 | [link](https://www.bilibili.com/video/BV1p142187Sv) |
| 2052 | - | - | yolov8  /  损失函数 之  3、正样本匹配 代码精讲（上） | 22:01 | [link](https://www.bilibili.com/video/BV1HM4m1276w) |
| 2053 | - | - | yolov8  /  损失函数 之  4、正样本匹配 代码精讲（下） | 12:39 | [link](https://www.bilibili.com/video/BV1b1421t7rY) |
| 2054 | - | - | yolov8  /  损失函数 之  5、类别损失 | 7:08 | [link](https://www.bilibili.com/video/BV1ti421h77Z) |
| 2055 | - | - | yolov8  /  损失函数 之  6、定位损失 CIoU + DFL | 15:34 | [link](https://www.bilibili.com/video/BV1Zy411i75C) |
| 2056 | - | - | yolov5 ｜ 手把手代码精读 ｜数据增强 之 mosaic | 12:05 | [link](https://www.bilibili.com/video/BV1ax4y1U7Ym) |
| 2057 | - | - | yolo v11 网络结构的改动有哪些 ？ | 2:15 | [link](https://www.bilibili.com/video/BV1q7DpYtEWL) |
| 2058 | - | - | yolo v11 ｜  C3k2 模块结构详解 | 11:32 | [link](https://www.bilibili.com/video/BV1uUyUY6ETc) |
| 2059 | - | - | yolo v11 ｜ C2PSA 模块详解 | 10:50 | [link](https://www.bilibili.com/video/BV1ko18YLEir) |
| 2060 | - | - | yolo v11 ｜ Detect Head  检测头 | 4:27 | [link](https://www.bilibili.com/video/BV1vHDpYREFR) |
| 2061 | - | - | 怎么盘项目新版本的改动点 ？ yolo v11 的图像增强 和 损失函数 有改动嘛 ？ | 5:07 | [link](https://www.bilibili.com/video/BV1xErrYTEb1) |
| 2062 | - | - | yolo 实例分割 ｜ Segmentation Head 结构 与 推理阶段后处理流程 | 13:28 | [link](https://www.bilibili.com/video/BV1TpgqzbEu2) |
| 2063 | - | - | YOLO26 ｜ SPPF、C3K2、Detect Head 的模块改动 | 22:52 | [link](https://www.bilibili.com/video/BV1ULF5zBEnz) |
| 2064 | - | - | YOLO26 ｜ 整体训练流程，以及 STAL 与 ProgLoss 处理节点 | 13:38 | [link](https://www.bilibili.com/video/BV1o2FzzsENp) |
| 2065 | - | - | YOLO26 / DFL Removal 需要做哪些配合调整 ？ | 6:02 | [link](https://www.bilibili.com/video/BV1N8cwzvEum) |
| 2066 | - | - | YOLO26 / NMS-Free 的后处理是怎么做的 ？End-to-End NMS-Free Inference | 9:11 | [link](https://www.bilibili.com/video/BV13QcuzYEKj) |
| 2067 | - | - | YOLO26 / ProgLoss & STAL ， STAL 解决的是什么问题 ？ 具体解决方案是什么 ？ | 14:10 | [link](https://www.bilibili.com/video/BV1nJcxzbEA2) |
| 2068 | - | - | 9）YOLO26 ｜ MuSGD 知识准备 ：奇异值分解 | 17:29 | [link](https://www.bilibili.com/video/BV1UPPvz3EfN) |
| 2069 | - | - | 10）YOLO26 ｜ MuSGD 知识准备 ：牛顿法 | 7:48 | [link](https://www.bilibili.com/video/BV1mNPvz6EfV) |
| 2070 | - | - | 8）YOLO26 ｜MuSGD | 31:04 | [link](https://www.bilibili.com/video/BV1SNPvz6EFZ) |
| 2071 | - | - | Ultralytics 使用指南  / 下载哪个发布版本的 Ultralytics 项目 ？ 如何下载指定版本的 ？ | 6:35 | [link](https://www.bilibili.com/video/BV1f1PezWEKN) |
| 2072 | - | - | YOLO26 / AutoDL + Ultralytics 环境配置，全程复制粘贴命令，懒人必备 ！ | 8:47 | [link](https://www.bilibili.com/video/BV1q5ftBXE48) |
| 2073 | - | - | 小白必看 ！ 训练效率优化，需要观察哪些指标，如何查看，有哪些参数会影响 训练效率 ？ | 21:36 | [link](https://www.bilibili.com/video/BV1HuA3zoEAB) |
| 2074 | - | - | 训练小技巧 ｜ ultralytics 项目如此庞大且复杂，如何快速定位网络搭建入口/训练入口/损失函数入口/数据增强入口 ？ 怎么找到那条执行的任务主线 ？ | 11:55 | [link](https://www.bilibili.com/video/BV1VqJnz7EjB) |
| 2075 | - | - | pycharm 使用小技巧｜断点的灵活使用，如何断点在逻辑重叠的代码行，以及断点的统一管理 | 9:12 | [link](https://www.bilibili.com/video/BV1K3h4zUEif) |
| 2076 | - | - | 深度学习 pycharm 使用 ｜ 命令行完全解析：从 CLI 命令 到 PyCharm 配置 | 28:19 | [link](https://www.bilibili.com/video/BV11CZWBWE7N) |
| 2077 | - | - | 深度学习炼丹必修！AutoDL 租 GPU 全流程教学，跑通深度学习项目 | 29:07 | [link](https://www.bilibili.com/video/BV1s2YdzNESZ) |
| 2078 | - | - | AutoDL 实例迁移 / 在其他实例中复用环境 与 数据集、项目代码 | 19:17 | [link](https://www.bilibili.com/video/BV1PN1VB4Etx) |
| 2079 | - | - | 远程训练必备！再也不担心 断网 / 断电 / 关机，screen 一招搞定 | 10:01 | [link](https://www.bilibili.com/video/BV1eRwYzrEGq) |
| 2080 | - | - | 23.2、tmux | 14:53 | [link](https://www.bilibili.com/video/BV19ZAEzTE9A) |
| 2081 | - | - | 免费 GPU / TPU ｜ kaggle 项目部署 | 13:08 | [link](https://www.bilibili.com/video/BV1qM41137SY) |
| 2082 | - | - | kaggle 上白嫖 GPU 资源 训练 ViT 网络 | 16:48 | [link](https://www.bilibili.com/video/BV1zLSKBgE4S) |
| 2083 | - | - | 深度学习基础 ｜ argparse 模块 ｜ 命令行参数解析 | 22:25 | [link](https://www.bilibili.com/video/BV1jM4m1176F) |
| 2084 | - | - | tensor基础知识 1 -  pytorch 之 tensor 内部存储结构 | 10:18 | [link](https://www.bilibili.com/video/BV1NH4y177VL) |
| 2085 | - | - | Dataset 与 DataLoader | 5:42 | [link](https://www.bilibili.com/video/BV1sRtresEbB) |
| 2086 | - | - | Batch Normalization | 17:46 | [link](https://www.bilibili.com/video/BV11s4y1c7pg) |
| 2087 | - | - | 优化器 ｜SGD ｜Momentum ｜Adagrad ｜RMSProp ｜Adam | 23:48 | [link](https://www.bilibili.com/video/BV1jh4y1q7ua) |
| 2088 | - | - | 优化器 optimizer｜ 权重衰减、weight decay、L2 正则化惩罚 | 17:25 | [link](https://www.bilibili.com/video/BV1LghvzHEKn) |
| 2089 | - | - | 信息量 ｜熵 ｜ 交叉熵 ｜KL散度 （相对熵）｜交叉熵损失函数 | 18:19 | [link](https://www.bilibili.com/video/BV1L8411X7ZZ) |
| 2090 | - | - | 深度学习基础 ｜目标检测 评价指标 ：AP、mAP | 22:36 | [link](https://www.bilibili.com/video/BV1XHTwzhE1V) |
| 2091 | - | - | Mamba 超超超详细解说 ｜ 1、对 SSM 的透彻理解 | 15:08 | [link](https://www.bilibili.com/video/BV1n7421d7xG) |
| 2092 | - | - | Mamba 超超超详细解说 ｜ 2、SSM 的离散化推导 + 代码示例 | 9:46 | [link](https://www.bilibili.com/video/BV1GT421Y7vN) |
| 2093 | - | - | Mamba 超超超详细解说 ｜3、S4 ：Structured State Spaces for Sequences | 13:14 | [link](https://www.bilibili.com/video/BV1wR67YhE18) |
| 2094 | - | - | Mamba 超超超详细解说 ｜4、Mamba | 21:44 | [link](https://www.bilibili.com/video/BV16862YgEFK) |
| 2095 | - | - | VMamba / Mamba 如何应用于2维图像 ？ SS2D ！ 前 2D-Cross-Scan，后 2D-Cross-Merge | 12:26 | [link](https://www.bilibili.com/video/BV1FVbQzqEis) |
| 2096 | - | - | 基础知识准备 之 Triton（上） | 9:13 | [link](https://www.bilibili.com/video/BV1CjtbzGERE) |
| 2097 | - | - | 基础知识准备 之 Triton（下） | 11:39 | [link](https://www.bilibili.com/video/BV1rntbzzEUX) |
| 2098 | - | - | 4.1、VMamba 整体网络结构 | 12:26 | [link](https://www.bilibili.com/video/BV1uRhJzKEyG) |
| 2099 | - | - | 4.2、SS2D | 15:18 | [link](https://www.bilibili.com/video/BV1TfhJzYExF) |
| 2100 | - | - | 4.3、CrossScan 的 Triton 并行实现 | 29:30 | [link](https://www.bilibili.com/video/BV1CshJzdEyh) |
| 2101 | - | - | CUDA 编程快速上手 ｜ 1、grid、block、thread | 12:41 | [link](https://www.bilibili.com/video/BV1vpPXekEdC) |
| 2102 | - | - | CUDA 编程快速上手 ｜ 2、global memory、shared memory、register | 25:22 | [link](https://www.bilibili.com/video/BV16ZPCeoETD) |
| 2103 | - | - | 不会写 cuda / c++ ？ 用平替的 triton 呀 ! | 10:47 | [link](https://www.bilibili.com/video/BV1uvVFziE2k) |
| 2104 | - | - | triton 基础使用 第2课 ｜通过 一个简单的【向量加法并行计算】，带你入门 Triton 基础使用 ！ | 11:40 | [link](https://www.bilibili.com/video/BV1oLVrz8EVW) |
| 2105 | - | - | triton 基础使用 第3课 ｜LayerNorm 的并行实现 | 14:03 | [link](https://www.bilibili.com/video/BV1cU5PzTE2b) |
| 2106 | - | - | triton 基础使用 第4课 ｜LayerNorm 的并行实现 | 11:09 | [link](https://www.bilibili.com/video/BV17qEuz9EQ9) |
| 2107 | - | - | Diffusion ｜ DDPM ｜ 1 - 概述 | 17:44 | [link](https://www.bilibili.com/video/BV1Xu4y147ov) |
| 2108 | - | - | Diffusion ｜ DDPM ｜2 - 基础知识准备 | 21:53 | [link](https://www.bilibili.com/video/BV1UN411E7hz) |
| 2109 | - | - | Diffusion / DDPM ｜ 3 - 前向扩散过程 | 9:55 | [link](https://www.bilibili.com/video/BV1vw41117r1) |
| 2110 | - | - | Diffusion / DDPM / 4 - 反向去噪过程、图像概率分布的理解 | 7:44 | [link](https://www.bilibili.com/video/BV13N411J7zK) |
| 2111 | - | - | Diffusion ｜ DDPM ｜ 5 - 损失函数 | 12:58 | [link](https://www.bilibili.com/video/BV1ju4y1x7L4) |
| 2112 | - | - | 《ROS 2机器人开发从入门到实践》课程介绍 | 6:48 | [link](https://www.bilibili.com/video/BV1GW42197Ck) |
| 2113 | - | - | 《ROS 2机器人开发从入门到实践》1.1 ROS部落的自我介绍 | 19:51 | [link](https://www.bilibili.com/video/BV1tE4m1d7Ug) |
| 2114 | - | - | 《ROS 2机器人开发从入门到实践》1.2.1~1.2.3 ROS2开发环境搭建之安装虚拟机和Ubuntu | 31:41 | [link](https://www.bilibili.com/video/BV14M4m117LJ) |
| 2115 | - | - | 《ROS 2机器人开发从入门到实践》1.2.3.1使用Windows子系统WSL安装ROS2运行小海龟 | 13:10 | [link](https://www.bilibili.com/video/BV1QarYYsEnE) |
| 2116 | - | - | 《ROS 2机器人开发从入门到实践》1.2.4 在Ubuntu中安装ROS2 | 22:16 | [link](https://www.bilibili.com/video/BV1Jz421B7Ey) |
| 2117 | - | - | 《ROS 2机器人开发从入门到实践》1.3 运行你的第一个机器人 | 10:02 | [link](https://www.bilibili.com/video/BV1iE421w7d5) |
| 2118 | - | - | 《ROS 2机器人开发从入门到实践》 1.4.5 Linux基础之环境变量 | 26:00 | [link](https://www.bilibili.com/video/BV1pm42137bR) |
| 2119 | - | - | 《ROS 2机器人开发从入门到实践》 2.1.1编写你的第一个节点(Python示例) | 35:09 | [link](https://www.bilibili.com/video/BV1iy411i727) |
| 2120 | - | - | 《ROS 2机器人开发从入门到实践》 2.1.2编写你的第一个节点( C++ 示例) | 32:28 | [link](https://www.bilibili.com/video/BV1FH4y1c7Px) |
| 2121 | - | - | 《ROS 2机器人开发从入门到实践》 2.2 使用功能包组织Python节点 | 33:26 | [link](https://www.bilibili.com/video/BV1ky411e7hp) |
| 2122 | - | - | 《ROS 2机器人开发从入门到实践》 2.3 使用功能包组织C++节点 | 22:12 | [link](https://www.bilibili.com/video/BV1Pb42177BJ) |
| 2123 | - | - | 《ROS 2机器人开发从入门到实践》 2.4 多功能包的最佳实践WorkSpace | 9:26 | [link](https://www.bilibili.com/video/BV1Hx4y147gW) |
| 2124 | - | - | 《ROS 2机器人开发从入门到实践》2.5.1ROS2基础之编程:面向对象编程Python示例 | 34:10 | [link](https://www.bilibili.com/video/BV1xU411U7yR) |
| 2125 | - | - | 《ROS 2机器人开发从入门到实践》2.5.1ROS2基础之编程:面向对象编程C++示例 | 20:56 | [link](https://www.bilibili.com/video/BV191p2eMErj) |
| 2126 | - | - | 《ROS 2机器人开发从入门到实践》2.5.2用得到的C++新特性 | 39:09 | [link](https://www.bilibili.com/video/BV1CRWWeoEso) |
| 2127 | - | - | 《ROS 2机器人开发从入门到实践》2.5.3.1多线程与回调函数Python示例 | 19:10 | [link](https://www.bilibili.com/video/BV1DvWYehEWz) |
| 2128 | - | - | 《ROS 2机器人开发从入门到实践》2.5.3.2多线程与回调函数C++示例 | 23:31 | [link](https://www.bilibili.com/video/BV18mWjeEEXS) |
| 2129 | - | - | 《ROS 2机器人开发从入门到实践》3.1话题通信介绍 | 17:24 | [link](https://www.bilibili.com/video/BV1D3WXeSELP) |
| 2130 | - | - | 《ROS 2机器人开发从入门到实践》3.2.1通过话题发布小说 | 38:58 | [link](https://www.bilibili.com/video/BV1g1sFezEpx) |
| 2131 | - | - | 《ROS 2机器人开发从入门到实践》3.2.2订阅小说并合成语音 | 19:32 | [link](https://www.bilibili.com/video/BV18GWreJEVo) |
| 2132 | - | - | 《ROS 2机器人开发从入门到实践》3.3.1发布速度控制海龟画圆 | 26:30 | [link](https://www.bilibili.com/video/BV1pas7eGEkk) |
| 2133 | - | - | 《ROS 2机器人开发从入门到实践》3.3.2订阅pose实现闭环控制 | 27:26 | [link](https://www.bilibili.com/video/BV1mLsseKEiN) |
| 2134 | - | - | 《ROS 2机器人开发从入门到实践》3.4.1完成工程架构设计 | 4:01 | [link](https://www.bilibili.com/video/BV118sMeQExX) |
| 2135 | - | - | 《ROS 2机器人开发从入门到实践》3.4.2自定义通信接口 | 17:29 | [link](https://www.bilibili.com/video/BV1dTHgeeEPm) |
| 2136 | - | - | 《ROS 2机器人开发从入门到实践》3.4.3系统信息获取与发布 | 19:46 | [link](https://www.bilibili.com/video/BV1GnH5eGEC3) |
| 2137 | - | - | 《ROS 2机器人开发从入门到实践》3.4.4在功能包中使用QT | 13:08 | [link](https://www.bilibili.com/video/BV1W4noe5Ezr) |
| 2138 | - | - | 《ROS 2机器人开发从入门到实践》3.4.5订阅数据并用Qt显示 | 23:48 | [link](https://www.bilibili.com/video/BV1MxHvebEdL) |
| 2139 | - | - | 《ROS 2机器人开发从入门到实践》3.5ROS2基础之Git入门 | 14:57 | [link](https://www.bilibili.com/video/BV1FoHreaEMc) |
| 2140 | - | - | 《ROS 2机器人开发从入门到实践》4.1.1服务通信介绍 | 9:14 | [link](https://www.bilibili.com/video/BV1kAHxepEcf) |
| 2141 | - | - | 《ROS 2机器人开发从入门到实践》4.1.2基于服务的参数通信 | 8:34 | [link](https://www.bilibili.com/video/BV1pGHaerErL) |
| 2142 | - | - | 《ROS 2机器人开发从入门到实践》4.2.1自定义服务接口 | 9:57 | [link](https://www.bilibili.com/video/BV18rpKeUETp) |
| 2143 | - | - | 《ROS 2机器人开发从入门到实践》4.2.2人脸检测 | 19:19 | [link](https://www.bilibili.com/video/BV14HHQeKEPm) |
| 2144 | - | - | 《ROS 2机器人开发从入门到实践》4.2.3人脸检测服务实现 | 18:40 | [link](https://www.bilibili.com/video/BV13zpbeJEG2) |
| 2145 | - | - | 《ROS 2机器人开发从入门到实践》4.2.4人脸检测客户端的实现 | 21:12 | [link](https://www.bilibili.com/video/BV1yMpBehEWW) |
| 2146 | - | - | 《ROS 2机器人开发从入门到实践》4.3.1自定义服务接口 | 7:33 | [link](https://www.bilibili.com/video/BV123pJe2EgX) |
| 2147 | - | - | 《ROS 2机器人开发从入门到实践》4.3.2服务端代码实现 | 15:18 | [link](https://www.bilibili.com/video/BV1ncpEevE4N) |
| 2148 | - | - | 《ROS 2机器人开发从入门到实践》4.3.3客户端代码实现 | 20:03 | [link](https://www.bilibili.com/video/BV1mj4zeUELx) |
| 2149 | - | - | 《ROS 2机器人开发从入门到实践》4.4.1参数声明设置 | 5:50 | [link](https://www.bilibili.com/video/BV1G54neuEiH) |
| 2150 | - | - | 《ROS 2机器人开发从入门到实践》4.4.2订阅参数更新 | 9:12 | [link](https://www.bilibili.com/video/BV16T4fe4EpX) |
| 2151 | - | - | 《ROS 2机器人开发从入门到实践》4.4.3客户端代码实现 | 17:17 | [link](https://www.bilibili.com/video/BV1xatKeWEFT) |
| 2152 | - | - | 《ROS 2机器人开发从入门到实践》4.5.1参数声明与设置 | 4:40 | [link](https://www.bilibili.com/video/BV19k4UeXEvZ) |
| 2153 | - | - | 《ROS 2机器人开发从入门到实践》4.5.2接收参数事件 | 12:20 | [link](https://www.bilibili.com/video/BV1sutteUEry) |
| 2154 | - | - | 《ROS 2机器人开发从入门到实践》4.5.3修改其他节点的参数 | 21:09 | [link](https://www.bilibili.com/video/BV1dAtieREYf) |
| 2155 | - | - | 《ROS 2机器人开发从入门到实践》4.6.1使用Launch启动多个节点 | 12:18 | [link](https://www.bilibili.com/video/BV1hdtLeZE9y) |
| 2156 | - | - | 《ROS 2机器人开发从入门到实践》4.6.2使用launch传递参数 | 11:01 | [link](https://www.bilibili.com/video/BV18MtRePEdY) |
| 2157 | - | - | 《ROS 2机器人开发从入门到实践》4.6.3 launch使用进阶 | 19:12 | [link](https://www.bilibili.com/video/BV1BMbAeKEY8) |
| 2158 | - | - | 《ROS 2机器人开发从入门到实践》5.1.1通过命令行使用TF | 12:36 | [link](https://www.bilibili.com/video/BV1ietCe2E9F) |
| 2159 | - | - | 《ROS 2机器人开发从入门到实践》5.1.2对TF原理的简单探究 | 4:33 | [link](https://www.bilibili.com/video/BV1wnsCe1EgM) |
| 2160 | - | - | 《ROS 2机器人开发从入门到实践》5.2Python中的手眼坐标变换 | 21:50 | [link](https://www.bilibili.com/video/BV1YesXeoEGd) |
| 2161 | - | - | 《ROS 2机器人开发从入门到实践》5.2.2 通过Python发布动态TF | 6:04 | [link](https://www.bilibili.com/video/BV1mxsheXEpc) |
| 2162 | - | - | 《ROS 2机器人开发从入门到实践》5.2.3通过Python查询TF关系 | 11:45 | [link](https://www.bilibili.com/video/BV1CSszeuEH3) |
| 2163 | - | - | 《ROS 2机器人开发从入门到实践》5.3.1 通过C++发布静态TF | 18:36 | [link](https://www.bilibili.com/video/BV1h8xnePEMe) |
| 2164 | - | - | 《ROS 2机器人开发从入门到实践》5.3.2通过C++发布动态TF | 6:26 | [link](https://www.bilibili.com/video/BV12RsoefEyV) |
| 2165 | - | - | 《ROS 2机器人开发从入门到实践》5.3.3通过C++查询TF关系 | 17:33 | [link](https://www.bilibili.com/video/BV1CexqevEAw) |
| 2166 | - | - | 《ROS 2机器人开发从入门到实践》5.4.1常用可视化工具rqt | 5:10 | [link](https://www.bilibili.com/video/BV1dtxmeJEbG) |
| 2167 | - | - | 《ROS 2机器人开发从入门到实践》5.4.2 数据化可视工具Rviz | 6:42 | [link](https://www.bilibili.com/video/BV1NQx4e5EoJ) |
| 2168 | - | - | 《ROS 2机器人开发从入门到实践》5.5 数据记录工具ros2 bag | 6:07 | [link](https://www.bilibili.com/video/BV1KyxeewEuY) |
| 2169 | - | - | 《ROS 2机器人开发从入门到实践》5.6 ROS 2基础之Git进阶 | 3:26 | [link](https://www.bilibili.com/video/BV1qs4geDEzC) |
| 2170 | - | - | 《ROS 2机器人开发从入门到实践》5.6.2 Git进阶之学会撤销代码 | 3:31 | [link](https://www.bilibili.com/video/BV1ejxDesExB) |
| 2171 | - | - | 《ROS 2机器人开发从入门到实践》5.6.3 Git进阶之分支 | 6:42 | [link](https://www.bilibili.com/video/BV1tbxDejE9n) |
| 2172 | - | - | 《ROS 2机器人开发从入门到实践》6.1 机器人建模与仿真概述 | 5:26 | [link](https://www.bilibili.com/video/BV1CB19Y1Ew8) |
| 2173 | - | - | 《ROS 2机器人开发从入门到实践》6.2 使用URDF创建机器人 | 16:12 | [link](https://www.bilibili.com/video/BV1RT1BYQEAk) |
| 2174 | - | - | 《ROS 2机器人开发从入门到实践》6.2.2 在RViz中显示机器人 | 27:35 | [link](https://www.bilibili.com/video/BV1Vq2LYoECn) |
| 2175 | - | - | 《ROS 2机器人开发从入门到实践》6.2.3使用Xacro简化URDF | 13:58 | [link](https://www.bilibili.com/video/BV1WY2WYaEwc) |
| 2176 | - | - | 《ROS 2机器人开发从入门到实践》6.2.4创建机器人及传感器部件 | 17:10 | [link](https://www.bilibili.com/video/BV12a2NYJE7L) |
| 2177 | - | - | 《ROS 2机器人开发从入门到实践》6.2.5完善机器人执行器部件 | 12:47 | [link](https://www.bilibili.com/video/BV1s92VYTEc7) |
| 2178 | - | - | 《ROS 2机器人开发从入门到实践》6.2.6贴合地面，添加虚拟部件 | 3:47 | [link](https://www.bilibili.com/video/BV1xU2mYBE9u) |
| 2179 | - | - | 《ROS 2机器人开发从入门到实践》6.3.1为机器人部件添加碰撞属性 | 4:05 | [link](https://www.bilibili.com/video/BV11J29YQESi) |
| 2180 | - | - | 《ROS 2机器人开发从入门到实践》6.3.2为机器人部件添加质量与惯性 | 14:50 | [link](https://www.bilibili.com/video/BV1wJ2BYqER6) |
| 2181 | - | - | 《ROS 2机器人开发从入门到实践》6.4.1安装与使用Gazebo构建世界 | 9:53 | [link](https://www.bilibili.com/video/BV1oamGYxEty) |
| 2182 | - | - | 《ROS 2机器人开发从入门到实践》6.4.2在Gazebo中加载机器人模型 | 15:52 | [link](https://www.bilibili.com/video/BV1ho2dYNE6T) |
| 2183 | - | - | 《ROS 2机器人开发从入门到实践》6.4.3 使用Gazebo标签扩展URDF | 6:17 | [link](https://www.bilibili.com/video/BV1k8mNYyEjW) |
| 2184 | - | - | 《ROS 2机器人开发从入门到实践》6.4.4 使用两轮差速插件控制机器人 | 16:55 | [link](https://www.bilibili.com/video/BV1wyyPYvEPy) |
| 2185 | - | - | 《ROS 2机器人开发从入门到实践》6.4.5 激光雷达传感器仿真 | 8:08 | [link](https://www.bilibili.com/video/BV1vTCUYyEcX) |
| 2186 | - | - | 《ROS 2机器人开发从入门到实践》6.4.6惯性测量传感器仿真 | 4:45 | [link](https://www.bilibili.com/video/BV1qLCRYYEMa) |
| 2187 | - | - | 《ROS 2机器人开发从入门到实践》6.4.7深度相机传感器仿真 | 9:46 | [link](https://www.bilibili.com/video/BV1SVy8YQEzu) |
| 2188 | - | - | 《ROS 2机器人开发从入门到实践》6.5.1ros2_control介绍与安装 | 7:01 | [link](https://www.bilibili.com/video/BV1f1yVYREG6) |
| 2189 | - | - | 《ROS 2机器人开发从入门到实践》6.5.2使用 Gazebo 接入 ros2_control | 14:02 | [link](https://www.bilibili.com/video/BV1VayHYqEUe) |
| 2190 | - | - | 《ROS 2机器人开发从入门到实践》6.5.3使用关节状态发布控制器 | 14:32 | [link](https://www.bilibili.com/video/BV1kfyZY9EaA) |
| 2191 | - | - | 《ROS 2机器人开发从入门到实践》6.5.4使用力控制器控制轮子 | 4:58 | [link](https://www.bilibili.com/video/BV18QyzY2ExG) |
| 2192 | - | - | 《ROS 2机器人开发从入门到实践》6.5.5使用两轮差速控制器控制机器人 | 9:33 | [link](https://www.bilibili.com/video/BV13SyDYmEPx) |
| 2193 | - | - | 《ROS 2机器人开发从入门到实践》7 自主导航 让机器人自己动起来 | 1:15 | [link](https://www.bilibili.com/video/BV1fA1bYYE5q) |
| 2194 | - | - | 《ROS 2机器人开发从入门到实践》7.1 机器人导航介绍 | 9:05 | [link](https://www.bilibili.com/video/BV1gf1KYoEMf) |
| 2195 | - | - | 《ROS 2机器人开发从入门到实践》7.2.1构建第一章导航地图 | 9:06 | [link](https://www.bilibili.com/video/BV1Ff1jYqEyU) |
| 2196 | - | - | 《ROS 2机器人开发从入门到实践》7.2.2将地图保存为文件 | 5:36 | [link](https://www.bilibili.com/video/BV1kB1JYmEvR) |
| 2197 | - | - | 《ROS 2机器人开发从入门到实践》7.3.1Navigation2介绍与安装 | 6:15 | [link](https://www.bilibili.com/video/BV1ezSiYdEJG) |
| 2198 | - | - | 《ROS 2机器人开发从入门到实践》7.3.2编写launch并启动导航 | 4:59 | [link](https://www.bilibili.com/video/BV1kiSHYaEh8) |
| 2199 | - | - | 《ROS 2机器人开发从入门到实践》7.3.3编写launch并启动导航 | 13:06 | [link](https://www.bilibili.com/video/BV1bNSoY6EVj) |
| 2200 | - | - | 《ROS 2机器人开发从入门到实践》7.3.4进行单点与路点导航 | 3:10 | [link](https://www.bilibili.com/video/BV1bPSoY3E9D) |
| 2201 | - | - | 《ROS 2机器人开发从入门到实践》7.3.5导航过程中进行动态避障 | 1:06 | [link](https://www.bilibili.com/video/BV1VdSdY2EzK) |
| 2202 | - | - | 《ROS 2机器人开发从入门到实践》7.3.6优化导航速度和膨胀半径 | 5:41 | [link](https://www.bilibili.com/video/BV15CDWYbEnG) |
| 2203 | - | - | 《ROS 2机器人开发从入门到实践》7.3.7 优化机器人到点精度 | 3:54 | [link](https://www.bilibili.com/video/BV1iaDMYDEHW) |
| 2204 | - | - | 《ROS 2机器人开发从入门到实践》7.4.1使用话题初始化机器人位姿 | 11:50 | [link](https://www.bilibili.com/video/BV11bDDYXEsC) |
| 2205 | - | - | 《ROS 2机器人开发从入门到实践》7.4.2使用TF获取机器人实时位置 | 8:00 | [link](https://www.bilibili.com/video/BV1i5DaYnE31) |
| 2206 | - | - | 《ROS 2机器人开发从入门到实践》7.4.3调用接口进行单点导航 | 19:33 | [link](https://www.bilibili.com/video/BV1ALD6YXENf) |
| 2207 | - | - | 《ROS 2机器人开发从入门到实践》7.4.4使用接口完成路点导航 | 6:55 | [link](https://www.bilibili.com/video/BV1NumkY9E8H) |
| 2208 | - | - | 《ROS 2机器人开发从入门到实践》7.5.1完成机器人系统架构设计 | 2:37 | [link](https://www.bilibili.com/video/BV1eZm1YmEhm) |
| 2209 | - | - | 《ROS 2机器人开发从入门到实践》7.5.2编写巡检控制节点 | 34:27 | [link](https://www.bilibili.com/video/BV17WmhYyEZi) |
| 2210 | - | - | 《ROS 2机器人开发从入门到实践》7.5.3.1添加语音播报功能（上） | 4:57 | [link](https://www.bilibili.com/video/BV1yQU5Y5EVu) |
| 2211 | - | - | 《ROS 2机器人开发从入门到实践》7.5.3.2添加语音播报功能（中） | 7:33 | [link](https://www.bilibili.com/video/BV1PnmZYaEox) |
| 2212 | - | - | 《ROS 2机器人开发从入门到实践》7.5.3.3添加语音播报功能（下） | 14:13 | [link](https://www.bilibili.com/video/BV1oAUiY4EUY) |
| 2213 | - | - | 《ROS 2机器人开发从入门到实践》7.5.4订阅图像并记录 | 13:24 | [link](https://www.bilibili.com/video/BV1s7UrYpE1Z) |
| 2214 | - | - | 《ROS 2机器人开发从入门到实践》7.6.1添加自描述文件 | 11:57 | [link](https://www.bilibili.com/video/BV19HUkYBEYV) |
| 2215 | - | - | 《ROS 2机器人开发从入门到实践》7.6.2将代码托管在Gitee | 5:33 | [link](https://www.bilibili.com/video/BV1pAUkYQE6J) |
| 2216 | - | - | 《ROS 2机器人开发从入门到实践》7.6.3将代码托管在GitHub | 5:44 | [link](https://www.bilibili.com/video/BV1mbU7YoE6t) |
| 2217 | - | - | 《ROS 2机器人开发从入门到实践》8.1.1pluginlib介绍与安装 | 4:41 | [link](https://www.bilibili.com/video/BV1tbUQYREiY) |
| 2218 | - | - | 《ROS 2机器人开发从入门到实践》8.1.2定义插件抽象类 | 6:44 | [link](https://www.bilibili.com/video/BV1HVBqYVECK) |
| 2219 | - | - | 《ROS 2机器人开发从入门到实践》8.1.3编写并生成第一个插件 | 14:11 | [link](https://www.bilibili.com/video/BV1DYB2YnEYz) |
| 2220 | - | - | 《ROS 2机器人开发从入门到实践》8.1.4编写插件测试程序 | 8:36 | [link](https://www.bilibili.com/video/BV1hjB4YhELs) |
| 2221 | - | - | 《ROS 2机器人开发从入门到实践》8.2.1自定义规划器介绍 | 7:13 | [link](https://www.bilibili.com/video/BV1fSzNYHEza) |
| 2222 | - | - | 【面试必考】交叉熵 vs KL散度到底是什么？从惊讶度讲到损失函数，一次说清它俩的关系 | 5:53 | [link](https://www.bilibili.com/video/BV13tMK6oEAA) |
| 2223 | - | - | 【面试高频】熵、交叉熵、KL 散度什么关系？一枚硬币讲透 交叉熵 = 熵 + KL | 3:17 | [link](https://www.bilibili.com/video/BV1BJMh6uEGj) |
| 2224 | - | - | 【手撕代码】交叉熵到底在惩罚什么？BCE 与多分类 CE 一次讲透 | 3:19 | [link](https://www.bilibili.com/video/BV1vmM36EEmH) |
| 2225 | - | - | 【面试高频】InfoNCE Loss 和 Cross Entropy Loss 有什么区别？对比学习核心损失全解析 | 3:35 | [link](https://www.bilibili.com/video/BV1VQMp6LEvg) |
| 2226 | - | - | 【面试高频】什么是语言模型：从 N-gram、数据稀疏到神经语言模型与大模型 | 3:32 | [link](https://www.bilibili.com/video/BV1h9No6cE6x) |
| 2227 | - | - | 【强化学习】Q-Learning 到 DQN：TD 更新、经验回放、target 网络，为什么能玩 Atari | 3:02 | [link](https://www.bilibili.com/video/BV1FUKW6JE3P) |
| 2228 | - | - | 【强化学习最小模型】多臂老虎机：探索利用、ε-greedy、UCB、汤普森采样 | 4:03 | [link](https://www.bilibili.com/video/BV1ZYKs6EEGQ) |
| 2229 | - | - | 【强化学习】Actor-Critic / A2C / A3C：优势函数 A=Q−V、多 worker 并行为什么更稳 | 3:15 | [link](https://www.bilibili.com/video/BV13bKt6UELM) |
| 2230 | - | - | 【强化学习】Actor-Critic / A2C / A3C：优势函数 A=Q−V、多 worker 并行为什么更稳 | 3:15 | [link](https://www.bilibili.com/video/BV15fKx6nEDN) |
| 2231 | - | - | 【手撕代码】寻找质数：为什么只需试除到 √n？从暴力到埃氏筛 | 3:18 | [link](https://www.bilibili.com/video/BV1TYKx6MEBZ) |
| 2232 | - | - | 【机器学习】决策树三兄弟 ID3 / C4.5 / CART：划分标准、结构差异、工程选用 | 4:39 | [link](https://www.bilibili.com/video/BV1J5gR6mEuu) |
| 2233 | - | - | 【机器学习】K-means 聚类讲透：两步迭代 + 肘部法则 + EM 视角 | 3:39 | [link](https://www.bilibili.com/video/BV1E5gR6mEdn) |
| 2234 | - | - | 【机器学习】L1 vs L2 正则化：为什么 L1 产生稀疏解？几何/梯度/贝叶斯三视角 | 4:01 | [link](https://www.bilibili.com/video/BV1nVgR6EExs) |
| 2235 | - | - | 【机器学习】逻辑回归：名字叫回归 本质是分类——Sigmoid / 决策边界 / 交叉熵 一次讲透 | 4:23 | [link](https://www.bilibili.com/video/BV177gR61EJX) |
| 2236 | - | - | 【强化学习】SARSA vs Q-learning：一个绕悬崖一个贴悬崖，On/Off-Policy 本质 | 3:37 | [link](https://www.bilibili.com/video/BV18vgR6PEbf) |
| 2237 | - | - | 【强化学习基石】TD 时序差分：MC 采样 + DP bootstrap，SARSA / Q-learning / Actor-Critic 全是它的实例 | 3:35 | [link](https://www.bilibili.com/video/BV1uvgR6PEin) |
| 2238 | - | - | 【手撕面试】AUC 0.8 到底是什么意思：正样本排在负样本前面的概率，三行代码手撕 | 0:59 | [link](https://www.bilibili.com/video/BV1ampE6YEkX) |
| 2239 | - | - | 【从 Transformer 到大模型现代架构 01/20】大模型到底在算什么：下一词预测 | 4:01 | [link](https://www.bilibili.com/video/BV1SSpE6cECv) |
| 2240 | - | - | 【RL 入门到 GRPO 01】强化学习到底在学什么？监督学习给答案，RL 只给一个分数 | 1:00 | [link](https://www.bilibili.com/video/BV1HAhU6WEod) |
| 2241 | - | - | 【RL 入门到 GRPO 02】折扣因子 γ 到底在决定什么？为什么大模型里直接取 1 | 0:59 | [link](https://www.bilibili.com/video/BV1HThU6DEJi) |
| 2242 | - | - | 【RL 入门到 GRPO 03】V、Q 和 Advantage 分别在算什么？贝尔曼方程与 PPO 的 Critic | 0:59 | [link](https://www.bilibili.com/video/BV16ThU6DEk9) |
| 2243 | - | - | 【RL 入门到 GRPO 04】蒙特卡洛和 TD 差在哪？偏差方差的取舍与 TD 误差 δ | 0:59 | [link](https://www.bilibili.com/video/BV1nKhU6HEva) |
| 2244 | - | - | 【RL 入门到 GRPO 05】策略梯度是怎么推出来的？REINFORCE 与 DeepSeekMath 的统一形式 | 1:00 | [link](https://www.bilibili.com/video/BV14Zhm6oE5i) |
| 2245 | - | - | 【RL 入门到 GRPO 06】baseline 为什么不引入偏差？减 V 得到优势，GRPO 减的是组平均 | 0:57 | [link](https://www.bilibili.com/video/BV14Zhm6oEPG) |
| 2246 | - | - | 【RL 入门到 GRPO 07】Actor-Critic 为什么要两个网络？Critic 的作业与它在大模型上的代价 | 0:59 | [link](https://www.bilibili.com/video/BV1Tohm6bE1K) |
| 2247 | - | - | 【RL 入门到 GRPO 08】GAE 的 λ 到底在调什么？λ 为什么可以比 γ 小得多 | 1:00 | [link](https://www.bilibili.com/video/BV1Tohm6bEe4) |
| 2248 | - | - | 【RL 入门到 GRPO 09】重要性采样是什么？旧策略采的数据为什么还能用、能用到什么程度 | 0:56 | [link](https://www.bilibili.com/video/BV1schU6REqP) |
| 2249 | - | - | 【RL 入门到 GRPO 10】从 TRPO 到 PPO：KL 围栏与 clip 剪刀，ε 为什么是 0.2 | 0:59 | [link](https://www.bilibili.com/video/BV1WFhU6xED8) |
| 2250 | - | - | 【RL 入门到 GRPO 11】PPO 完整训练流程：三步一轮、三项损失，以及大模型版的参数 | 0:58 | [link](https://www.bilibili.com/video/BV1WFhU6xEmR) |
| 2251 | - | - | 【RL 入门到 GRPO 12】大模型怎么变成策略？单步老虎机与 token 级 MDP 的两种看法 | 0:56 | [link](https://www.bilibili.com/video/BV1LjhU6yEy1) |
| 2252 | - | - | 【RL 入门到 GRPO 13】RLHF 三阶段是怎么串起来的？InstructGPT 的三个数与对齐税 | 1:00 | [link](https://www.bilibili.com/video/BV17LhU6LEDs) |
| 2253 | - | - | 【RL 入门到 GRPO 14】Reward Model 是怎么训出来的？Bradley-Terry 与 batch 的反直觉细节 | 0:55 | [link](https://www.bilibili.com/video/BV1LJhU6kEkp) |
| 2254 | - | - | 【RL 入门到 GRPO 15】KL 惩罚在拴住谁？β 的取值、k3 估计，以及放奖励还是放损失 | 1:00 | [link](https://www.bilibili.com/video/BV1iEhU6VEm5) |
| 2255 | - | - | 【RL 入门到 GRPO 16】PPO 的四个模型：谁在学、谁在看，以及显存为什么是它的死穴 | 0:57 | [link](https://www.bilibili.com/video/BV1vEhU6VE81) |
| 2256 | - | - | 【RL 入门到 GRPO 17】DPO 是怎么推出来的？闭式解、配分函数与「你的语言模型其实是个 Reward Model」 | 1:00 | [link](https://www.bilibili.com/video/BV1fghU6UEUB) |
| 2257 | - | - | 【RL 入门到 GRPO 18】GRPO 到底改了 PPO 什么？去掉 Critic、换成组内基线、KL 进损失 | 0:58 | [link](https://www.bilibili.com/video/BV1e6hm6uEYW) |
| 2258 | - | - | 【RL 入门到 GRPO 19】GRPO 的两个偏差藏在哪？Dr. GRPO 删两个分母、DAPO 放宽 clip 治熵坍塌 | 0:59 | [link](https://www.bilibili.com/video/BV1EVhU62Ein) |
| 2259 | - | - | 【RL 入门到 GRPO 20】DeepSeek-R1 做对了什么？规则奖励、顿悟时刻与四阶段配方 | 0:59 | [link](https://www.bilibili.com/video/BV17VhU62EwM) |
| 2260 | - | - | 【面试高频】SFT 为什么要 Mask 掉 User 的部分？只学 Assistant，label 设 -100 | 3:43 | [link](https://www.bilibili.com/video/BV1KyNH6nEPk) |
| 2261 | - | - | 【面试高频】指令微调 Instruction Tuning：多任务、统一格式、零样本泛化，和 RLHF 别搞混 | 3:45 | [link](https://www.bilibili.com/video/BV1qLKj6ZE8D) |
| 2262 | - | - | 【面试高频】PEFT 参数高效微调五种方法：Adapter/Prefix/P-Tuning/Prompt Tuning/LoRA 对比 | 4:03 | [link](https://www.bilibili.com/video/BV1VUNo6vE1H) |
| 2263 | - | - | 【微调排障】chat template 不一致：不报错但效果暴降的 silent error | 2:42 | [link](https://www.bilibili.com/video/BV1t68264Eyx) |
| 2264 | - | - | 【微调实操】LoRA 超参调优：rank、alpha、target modules 与学习率怎么设 | 2:30 | [link](https://www.bilibili.com/video/BV1VY826wEd2) |
| 2265 | - | - | 【微调必修】LoRA 显存悖论：只训 1% 参数，为什么显存没等比例下降 | 2:51 | [link](https://www.bilibili.com/video/BV1aq826bExU) |
| 2266 | - | - | 【立项必答】SFT 到底需要多少条数据？从 LIMA 与 Alpaca 的对比讲透质量与数量 | 3:12 | [link](https://www.bilibili.com/video/BV1Rg8s6qEyy) |
| 2267 | - | - | 【微调排障】SFT 后的三种退化：重复、啰嗦、幻觉加剧各自的根因与修复 | 1:05 | [link](https://www.bilibili.com/video/BV1YL8s6PENV) |
| 2268 | - | - | 【SFT 排障】第二个 epoch loss 断崖暴跌：三大根因、判断方法与五个避免手段 | 3:15 | [link](https://www.bilibili.com/video/BV1hL8s6PE3u) |
| 2269 | - | - | 【大模型基础】SFT 和预训练的区别在哪里？损失掩码机制详解 | 2:37 | [link](https://www.bilibili.com/video/BV19V8s6vEKY) |
| 2270 | - | - | 【DeepSeek R1】冷启动 SFT 详解：千条数据为什么能解决 R1-Zero 的可读性问题 | 3:04 | [link](https://www.bilibili.com/video/BV14V8t6AELz) |
| 2271 | - | - | 【SFT 进阶】多轮对话训练详解：上下文拼接、loss mask 与长对话截断 | 2:59 | [link](https://www.bilibili.com/video/BV1wgbL6XE3k) |
| 2272 | - | - | 【推理提升】RFT 拒绝采样微调详解：性价比最高的推理能力提升方法 | 2:57 | [link](https://www.bilibili.com/video/BV1kdb76fEAX) |
| 2273 | - | - | 【SFT 调参】学习率实操指南：十分之一法则、经验值与两侧症状 | 2:24 | [link](https://www.bilibili.com/video/BV1TAb76KEap) |
| 2274 | - | - | 【SFT 数据】GRAPE：用目标模型概率挑回答，三分之一数据为什么能超过 Tulu3-SFT | 2:54 | [link](https://www.bilibili.com/video/BV1VneY6qEhN) |
| 2275 | - | - | 【Qwen3 技术报告】思考与非思考模式怎么训进一个模型？空 think 块、/no_think 标记与涌现的思考预算 | 3:48 | [link](https://www.bilibili.com/video/BV18mea6FEt1) |
| 2276 | - | - | 【训练排障】LoRA 开梯度检查点后 loss 纹丝不动，根因是什么？enable_input_require_grads 与 use_reentrant | 3:20 | [link](https://www.bilibili.com/video/BV1ezea6vE4D) |
| 2277 | - | - | 【SFT 面试】为什么用 SFT 教模型新知识，反而会让它更爱编？未知样本学得慢、学会后幻觉线性上升 | 2:59 | [link](https://www.bilibili.com/video/BV1Yrea6PEJH) |
| 2278 | - | - | 【SFT 评测】SFT 之后模型对提示词措辞更鲁棒了吗？1.7B/4B 降 54%~71%，8B 几乎为零 | 2:55 | [link](https://www.bilibili.com/video/BV1Wfea6QEWG) |
| 2279 | - | - | 【SFT 进阶】SFT 里每个 token 都该学吗？Rho-1 超额损失选 token 与 ProFit 屏蔽低概率措辞 | 3:41 | [link](https://www.bilibili.com/video/BV1Wfea6QEJ9) |
| 2280 | - | - | 【SFT 调参】六个决定一次讲透：为什么按验证 loss 早停会停错？LoRA lr 1e-3、过 2 轮 IFEval 退化、Muon | 3:19 | [link](https://www.bilibili.com/video/BV1knea6mErC) |
| 2281 | - | - | 【SFT 面试】为 RL 准备的 SFT 为什么不该追求最低 loss？TailSFT、SWE-Prime 与数据选择的容量边界 | 4:51 | [link](https://www.bilibili.com/video/BV16xea65ExR) |
| 2282 | - | - | 【SFT 面试】SFT 一定要 mask 掉 prompt 吗？指令长 5 倍、样本少于 1 万时给 prompt 算 loss 反而涨点 | 4:06 | [link](https://www.bilibili.com/video/BV1UTea64E3a) |
| 2283 | - | - | 【面试高频】梯度裁剪原理：按范数裁剪 vs 按值裁剪，阈值怎么设，为什么必开 | 3:03 | [link](https://www.bilibili.com/video/BV14ZNa6HEru) |
| 2284 | - | - | 【面试高频】大模型训练为何突然 NaN？QK-Norm 两行代码治好注意力 logit 爆炸 | 3:11 | [link](https://www.bilibili.com/video/BV1UUua6wEVU) |
| 2285 | - | - | 【微调实操】灾难性遗忘的五种缓解方法：从 LoRA rank 到任务向量加法 | 1:05 | [link](https://www.bilibili.com/video/BV1PD826SEFs) |
| 2286 | - | - | 【训练稳定性】梯度裁剪详解：静态全局范数裁剪与 AdaGC 自适应裁剪 | 0:58 | [link](https://www.bilibili.com/video/BV1EH826zEU7) |
| 2287 | - | - | 【RLHF 排障】三大崩溃现象诊断：reward 崩塌、KL 爆炸、输出发散 | 1:08 | [link](https://www.bilibili.com/video/BV1Bu8S6LEJU) |
| 2288 | - | - | 【训练排障】loss 突然变 NaN 怎么办？脏数据、梯度爆炸、精度溢出三路排查 | 2:57 | [link](https://www.bilibili.com/video/BV13f846kEU1) |
| 2289 | - | - | 【训练排障】训练不收敛的系统排查清单：学习率、数据、初始化、精度四步走 | 2:54 | [link](https://www.bilibili.com/video/BV1LQ8467E4e) |
| 2290 | - | - | 【持续学习】数据回放详解：配比、选样与遗忘监控 | 2:09 | [link](https://www.bilibili.com/video/BV1MT8t6TEaB) |
| 2291 | - | - | 【训练踩坑】token level mean vs sequence level sum：一个除法决定训练稳定还是崩溃 | 2:37 | [link](https://www.bilibili.com/video/BV1qNbE6XEfw) |
| 2292 | - | - | 【训练调试】可复现性详解：cuDNN、DataLoader 与分布式浮点误差三大随机源 | 2:55 | [link](https://www.bilibili.com/video/BV1iMbE6DEbj) |
| 2293 | - | - | 【训练诊断】train vs val loss：过拟合、欠拟合的判断标准与量化指标 | 2:41 | [link](https://www.bilibili.com/video/BV1RTbE6HEkW) |
| 2294 | - | - | 【训练监控】除了 loss 还必须看的五个指标：grad norm、PPL、MFU、学习率、吞吐量 | 3:12 | [link](https://www.bilibili.com/video/BV1zwbE6REWX) |
| 2295 | - | - | 【持续学习】三种技术路线：经验回放、EWC 与渐进式网络（LoRA adapter） | 1:59 | [link](https://www.bilibili.com/video/BV17pb76pEuR) |
| 2296 | - | - | 【训练监控】梯度范数多大算正常？基线建立与三种预警阈值设法 | 2:38 | [link](https://www.bilibili.com/video/BV1Urb76uETw) |
| 2297 | - | - | 【训练监控】WandB 与 TensorBoard 选型 + 必须记录的六大指标 | 2:45 | [link](https://www.bilibili.com/video/BV1gobj6gE67) |
| 2298 | - | - | 【训练排障】变长 SFT 开梯度累积，loss 为什么会系统性偏高？HF Trainer 存在两年的归一化 bug | 3:28 | [link](https://www.bilibili.com/video/BV1LReh6iES9) |
| 2299 | - | - | 【后训练面试】为什么 RL 比 SFT 更不容易遗忘？陈丹琦组消融：关键是 on-policy 数据而不是 KL | 3:35 | [link](https://www.bilibili.com/video/BV1oUeh6zEr8) |
| 2300 | - | - | 【训练排障】训练末期 grad norm 为什么反而上升？weight decay 与 LR 衰减的耦合，AdamC 一行修正 | 3:58 | [link](https://www.bilibili.com/video/BV1mMea6dEtA) |
| 2301 | - | - | 强化学习中的熵坍塌 | 2:46 | [link](https://www.bilibili.com/video/BV1qY9NBCEo2) |
| 2302 | - | - | 【面试高频】什么是熵坍塌和 Reward Hacking？它们的关系与解决办法 | 3:13 | [link](https://www.bilibili.com/video/BV1j1M36UEP1) |
| 2303 | - | - | 【面试高频】什么是 Rollout？RL 训练的经验采样，四步流程 + 为什么是头号瓶颈 | 3:11 | [link](https://www.bilibili.com/video/BV14rNH6pEvw) |
| 2304 | - | - | 【面试进阶】熵坍塌为什么发生？又如何解决？从协方差机制到 Clip-Higher | 3:20 | [link](https://www.bilibili.com/video/BV1rKKx6dEjc) |
| 2305 | - | - | 【RLHF】KL 惩罚系数 β 怎么调？太小 Reward Hacking，太大学不动 | 4:07 | [link](https://www.bilibili.com/video/BV1ck3R6pE2G) |
| 2306 | - | - | 【RL 工程】RLEP 经验回放：把高质量 rollout 存进 buffer 反复利用 | 1:03 | [link](https://www.bilibili.com/video/BV1fK8S6jE8G) |
| 2307 | - | - | 【RLHF 调参】PPO 三大超参详解：clip range、KL coefficient、GAE lambda | 3:13 | [link](https://www.bilibili.com/video/BV1w9b76wE6Z) |
| 2308 | - | - | 【RL 工程】batch 组织策略：难度分布、类型平衡与 rollout 数量 | 1:50 | [link](https://www.bilibili.com/video/BV1Kmb76KEqu) |
| 2309 | - | - | 【RL 调参】entropy bonus 详解：系数怎么设、衰减调度怎么做、熵坍缩怎么救 | 3:16 | [link](https://www.bilibili.com/video/BV1Tmb76KEFh) |
| 2310 | - | - | 【RL 工程】rollout 是 RL 训练的瓶颈：vLLM 加速与异步训练详解 | 3:14 | [link](https://www.bilibili.com/video/BV1N1b76qEif) |
| 2311 | - | - | 【RLHF 监控】target KL 设置与 KL 曲线诊断 | 2:01 | [link](https://www.bilibili.com/video/BV12yb76TEzJ) |
| 2312 | - | - | 【RL 基础】探索与利用的平衡：epsilon-greedy、UCB、entropy bonus 与好奇心驱动 | 1:48 | [link](https://www.bilibili.com/video/BV1UBb763E1D) |
| 2313 | - | - | 【RL 调参】rollout 采样温度：让 group 内有区分度才有训练信号 | 2:35 | [link](https://www.bilibili.com/video/BV1DBb763EHZ) |
| 2314 | - | - | 【RL 加速】用投机解码给 rollout 提速：draft 模型选择与命中率优化 | 1:47 | [link](https://www.bilibili.com/video/BV1KTb76YELi) |
| 2315 | - | - | 【异步 RL】PPO-EWMA：通过参数滑动平均改进 old logits 缺失问题，重要性比为什么要拆成两项 | 3:39 | [link](https://www.bilibili.com/video/BV1BVeY6GEwD) |
| 2316 | - | - | 【推理 Infra】Batch 不变内核：通过固定归约顺序消除大模型推理的不确定性，RL 训推 KL 归零 | 3:27 | [link](https://www.bilibili.com/video/BV173eY6CESH) |
| 2317 | - | - | 【Agentic RL 复盘】GPT-OSS 做 RL 为什么 KL 一开训就爆炸？MoE 路由、attention sink 与显存三个坑 | 3:37 | [link](https://www.bilibili.com/video/BV1VpeY6KEtn) |
| 2318 | - | - | 【MoE × RL】R3：通过重放推理时的专家路由，改进 MoE 做 RL 时训推路由不一致导致的崩溃 #大会员10周年 | 4:32 | [link](https://www.bilibili.com/video/BV1UTea64E41) |
| 2319 | - | - | 【RL 训练稳定性】训推不一致为什么是优化问题而不是精度问题？按回答长度激增触发学习率减半 | 3:51 | [link](https://www.bilibili.com/video/BV1h1ea6hEhW) |
| 2320 | - | - | 【RL 长训练】ProRL：通过验证停滞时重置参考策略，改进 RL 训几百步就停滞的问题 | 3:20 | [link](https://www.bilibili.com/video/BV1akea6YEjg) |
| 2321 | - | - | 【RL 训练】RL 的 batch 越大训练越快吗？√B 学习率缩放与「吞吐增益 > 样本惩罚」决策不等式 | 3:17 | [link](https://www.bilibili.com/video/BV1HceY6nEUr) |
| 2322 | - | - | 【RL 数据准备】RL 训练数据的难度怎么定？待训模型跑 8 次筛题、镜像 J 形分布、通过率拉回 50% | 3:41 | [link](https://www.bilibili.com/video/BV1rWea61Erm) |
| 2323 | - | - | 【RL 排障】RL 后期熵为什么会突然暴涨？正负样本不对称与 token 级熵流失衡，常规旋钮为何无效 | 3:04 | [link](https://www.bilibili.com/video/BV1ppea67Eni) |
| 2324 | - | - | 【RLVR 多样性】Uniqueness-Aware RL：通过按解题策略聚类加权优势，改进 RLVR 解题策略单一化的坍缩问题 | 2:58 | [link](https://www.bilibili.com/video/BV1rpea6jELJ) |
| 2325 | - | - | 【长 CoT RL】max response length 该分阶段放开还是一步到位？DeepScaleR、Skywork-OR1 与 Polaris 反例 | 3:35 | [link](https://www.bilibili.com/video/BV12Vea6pEBV) |
| 2326 | - | - | 【RL 前沿】BroRL：通过把每题 rollout 从 16 加到 512 改进 RL 训练饱和的问题（NVIDIA） | 4:25 | [link](https://www.bilibili.com/video/BV1f4ea6CETH) |
| 2327 | - | - | 【RL 训练动力学】GRPO 的训练曲线能预测吗？用阻尼振子解释动量、陈旧度与 group size | 4:39 | [link](https://www.bilibili.com/video/BV1RZeh6YETk) |
| 2328 | - | - | 【RL 系统】APRIL：通过 partial rollout 改进同步 RL 的长尾等待，多发一倍、够了就停、没写完续写 | 3:57 | [link](https://www.bilibili.com/video/BV1jDeh6uEYy) |
| 2329 | - | - | 【RL 省显存】QeRL：4-bit 量化噪声为什么让 RL 探索更好？32B 模型单卡 H100 跑 GRPO | 4:23 | [link](https://www.bilibili.com/video/BV1ZUeh6zECH) |
| 2330 | - | - | 【RL 超参】RL 的学习率为什么比 SFT 小 10 倍？1e-5 断崖式崩溃、JustRL 恒定 1e-6 与 LoRA 例外 | 4:38 | [link](https://www.bilibili.com/video/BV1R9eh6KEMN) |
| 2331 | - | - | 【RLVR 多样性】多样性坍塌发生在哪？集中在开头几个 token，只插值第 20 到 28 层就能找回 37% 覆盖 | 5:04 | [link](https://www.bilibili.com/video/BV1LQeh6BE1J) |
| 2332 | - | - | 【RL 训练】LLMZero：通过 Agent 逐 checkpoint 诊断与树搜索改进 RL 超参的固定日程问题 | 3:25 | [link](https://www.bilibili.com/video/BV1dQeh6qEJJ) |
| 2333 | - | - | 【面试高频】BLEU 与 ROUGE 讲透：精确率 vs 召回率、简短惩罚与最长公共子序列 | 3:25 | [link](https://www.bilibili.com/video/BV1X9No6cEVf) |
| 2334 | - | - | 【评测原理】pass@k 怎么推导计算：无偏估计公式 1−C(n−c,k)/C(n,k)，有偏 vs 无偏 | 3:13 | [link](https://www.bilibili.com/video/BV1DMK46VEAW) |
| 2335 | - | - | 【跑分黑箱】GSM8K 数据污染：benchmark 过拟合、n-gram 重叠检测、记忆探测 | 3:12 | [link](https://www.bilibili.com/video/BV1PzKx6PEo3) |
| 2336 | - | - | 【大模型评估】Elo 评分与 Bradley-Terry：Chatbot Arena 排名系统讲透 | 4:22 | [link](https://www.bilibili.com/video/BV17U3R6EENL) |
| 2337 | - | - | 【MT-Bench 实测】LLM-as-Judge 的四大偏差：位置/冗长/自我偏好/风格 | 4:10 | [link](https://www.bilibili.com/video/BV1f13R6JEfP) |
| 2338 | - | - | 【大模型评估】MMLU 分数有水分？57 个学科的评估细节、三大坑与改进版 | 4:13 | [link](https://www.bilibili.com/video/BV1e8826PEiP) |
| 2339 | - | - | 【上线必修】压力测试六维度：超长、空输入、特殊字符、多语言、对抗与重复 | 2:09 | [link](https://www.bilibili.com/video/BV1PUb76vEkx) |
| 2340 | - | - | 【训练工程】评测频率怎么定？proxy 高频看趋势、完整低频做决策，兼谈数据污染 | 2:56 | [link](https://www.bilibili.com/video/BV1FZb76bEW8) |
| 2341 | - | - | 【评测陷阱】benchmark 分数为什么会骗你？数据泄露与过拟合的检测方法 | 2:08 | [link](https://www.bilibili.com/video/BV1eab76jEkY) |
| 2342 | - | - | 【评测可信度】数据污染的检测与清洗：n-gram、embedding 与 PPL 三重检测 | 2:04 | [link](https://www.bilibili.com/video/BV1mrb76uEDc) |
| 2343 | - | - | 【RL 面试】RL 涨分是真学会还是在背题？Qwen 数学基准污染、记忆锚点电路与模型任务对齐度 | 5:11 | [link](https://www.bilibili.com/video/BV1R9eh6KEhk) |
| 2344 | - | - | 【RLHF】RM 分数涨人类却摇头？Goodhart 定律与 Reward Overoptimization 讲透 | 3:56 | [link](https://www.bilibili.com/video/BV1RX3R6yEh3) |
| 2345 | - | - | 【RLHF】为什么 ChatGPT 越训话越多？Length Bias 的来龙去脉 | 4:36 | [link](https://www.bilibili.com/video/BV1J23R6SE52) |
| 2346 | - | - | 【RLHF】Reward Model Ensemble：一个 RM 易被骗，K 个 RM 投票才公正 | 4:15 | [link](https://www.bilibili.com/video/BV15R3R65E2J) |
| 2347 | - | - | 【大模型对齐】Self-Rewarding LM：不要 Reward Model，让 LLM 自己当裁判 | 4:19 | [link](https://www.bilibili.com/video/BV1XZ3R63EYU) |
| 2348 | - | - | 【面试高频】PRM vs ORM：过程奖励为什么碾压结果奖励？一次讲透 | 3:24 | [link](https://www.bilibili.com/video/BV1UUua6wE44) |
| 2349 | - | - | 【对齐前沿】检测到模型作弊，为什么不该丢弃整条 rollout？GLM-5.2 在线守卫详解 | 2:51 | [link](https://www.bilibili.com/video/BV1A9826mEDt) |
| 2350 | - | - | 【推理 RL】奖励稀疏问题详解：奖励塑形、课程学习、好奇心驱动与 PRM | 2:53 | [link](https://www.bilibili.com/video/BV1Lg8S6yE84) |
| 2351 | - | - | 【面试高频】规则奖励 vs 奖励模型：两种奖励来源的优劣与选择策略 | 1:54 | [link](https://www.bilibili.com/video/BV1Sx8S6YESV) |
| 2352 | - | - | 【Yuan3.0】RIRM + RAPO：用负奖励改进推理模型答对后仍继续反思的浪费 | 2:47 | [link](https://www.bilibili.com/video/BV1LX8462E9d) |
| 2353 | - | - | 【Reasoning RL】RLVR 数据准备全流程：格式、冷启动、反思 token 与课程学习 | 3:02 | [link](https://www.bilibili.com/video/BV1uob56aEMT) |
| 2354 | - | - | 【对齐必修】reward hacking 详解：Goodhart 定律与五种实用防御手段 | 3:15 | [link](https://www.bilibili.com/video/BV16Rb768EZo) |
| 2355 | - | - | 【RL 工程】reward 归一化详解：running mean-std、batch 归一化与三个常见坑 | 2:14 | [link](https://www.bilibili.com/video/BV1CDb76AEk8) |
| 2356 | - | - | 【推理 RL】Cliff：通过标注第一处出错改进 GRPO 结果奖励过粗的问题，λ 为什么必须设 0 | 3:24 | [link](https://www.bilibili.com/video/BV1nPeY6EEQq) |
| 2357 | - | - | 【RL 奖励设计】RLVR 该不该给格式奖励？FrameThinker 消融与 Open-Reasoner-Zero 无格式分实践 | 4:04 | [link](https://www.bilibili.com/video/BV1V7eY6zEeZ) |
| 2358 | - | - | 【RL 奖励】探针裁判：从 1.7B 小模型隐藏层读 rubric 判断，为什么能超过 8B 生成式裁判 | 3:27 | [link](https://www.bilibili.com/video/BV15JeY6MEnz) |
| 2359 | - | - | 【RLVR 数据】RLVE：通过程序化生成、难度自适应的可验证环境，改进 RL 静态题库的信号衰减问题 | 3:11 | [link](https://www.bilibili.com/video/BV1Yrea6PE1R) |
| 2360 | - | - | 【Agent 安全】为什么 RL 后训练的 Agent 更爱作弊？同基座作弊率 23 倍，环境加固砍掉 87.7% | 4:30 | [link](https://www.bilibili.com/video/BV1sdea69ELG) |
| 2361 | - | - | 【RL 奖励】没有标准答案的任务怎么做 RL？给裁判一份参考回答，比 SFT 蒸馏高 20 分 | 3:07 | [link](https://www.bilibili.com/video/BV1tSea6ZEQm) |
| 2362 | - | - | 【RL 前沿】VerIF：用代码校验硬约束、推理模型判软约束，改进指令遵循 RL 的验证难题，IFEval 68.4→84.5 | 3:27 | [link](https://www.bilibili.com/video/BV1vYea6zEDe) |
| 2363 | - | - | 【RLVR 工程】训练前为什么要先 fuzz 你的 verifier？93% 判卷失败来自空格标点、版本间半数判法相反 | 3:04 | [link](https://www.bilibili.com/video/BV1qaea6gE6K) |
| 2364 | - | - | 【AI 安全】为什么不能把思维链监控写进 RL 奖励？混淆式作弊、反馈外溢与可监控性税 | 4:34 | [link](https://www.bilibili.com/video/BV1B4ea6CES3) |
| 2365 | - | - | 【RLVR 面试】奖励随机错 40% 为什么 RL 还能训？看训练奖励饱和速度判断模型在学还是在背 | 4:50 | [link](https://www.bilibili.com/video/BV1Xoeh6PEzc) |
| 2366 | - | - | 【RL 奖励】LLM 裁判为什么会被一个 token 骗过？万能钥匙攻击、Master-RM 与 rubric dropout | 5:09 | [link](https://www.bilibili.com/video/BV15Zeh6eEBg) |
| 2367 | - | - | 【大模型训练】Scaling Law 到底是什么原理？从幂律直线到 Chinchilla 黄金配比全解析 | 3:36 | [link](https://www.bilibili.com/video/BV1ECTj6YEyT) |
| 2368 | - | - | 【面试必考】大模型为什么很少用Dropout？从过拟合讲到单epoch时代，config考古实锤 | 3:56 | [link](https://www.bilibili.com/video/BV1YhT46HEhM) |
| 2369 | - | - | 【面试高频】训练算力 6ND 公式详解：前向 2N / 反向 4N 怎么来的？MoE 激活参数与 Chinchilla 一并讲透 | 3:28 | [link](https://www.bilibili.com/video/BV1jzNa6eEom) |
| 2370 | - | - | 【面试高频】训练算力 6ND 公式详解：前向 2N / 反向 4N 怎么来的？MoE 激活参数与 Chinchilla 一并讲透 | 3:28 | [link](https://www.bilibili.com/video/BV1eTKM6wEx6) |
| 2371 | - | - | 【大模型基础】预训练为什么只做「预测下一个词」就能学到知识？兼谈曝光偏差 | 3:33 | [link](https://www.bilibili.com/video/BV1RL8S6gEDV) |
| 2372 | - | - | 【训练常识】大模型预训练为什么只跑 1 个 epoch？三个原因与什么时候可以多跑 | 2:44 | [link](https://www.bilibili.com/video/BV1vR846LEHM) |
| 2373 | - | - | 【垂域实操】继续预训练的数据配比与遗忘防御：D-CPT Law 与三招工程手段 | 3:16 | [link](https://www.bilibili.com/video/BV1T38t6eEtb) |
| 2374 | - | - | 【训练技巧】大模型预训练为什么不用 Dropout？三个副作用与替代的正则化机制 | 2:48 | [link](https://www.bilibili.com/video/BV1xY8468Evd) |
| 2375 | - | - | 【训练技巧】Label Smoothing 在大模型上为什么基本不用？ | 1:52 | [link](https://www.bilibili.com/video/BV1cVbL6DEHz) |
| 2376 | - | - | 【训练技巧】早停配置详解：patience、验证集选择与预训练为何不用早停 | 1:45 | [link](https://www.bilibili.com/video/BV17Wb76QEma) |
| 2377 | - | - | 【训练配置】序列长度怎么选？O(n²) 成本、主流演进与分阶段扩展 | 2:33 | [link](https://www.bilibili.com/video/BV1Sib76kEZk) |
| 2378 | - | - | 【预训练面试】大模型真的不该用 Dropout 吗？层级 Dropout 配 1/ρ 缩放，8.2B 少用 25% 训练算力（Cerebras） | 4:19 | [link](https://www.bilibili.com/video/BV1y7ea6SEe6) |
| 2379 | - | - | 【ICML 2025】CPT Scaling Law：用分布偏移项与退火面积预测继续预训练的 loss 曲线 | 4:24 | [link](https://www.bilibili.com/video/BV1Rvea6MEhE) |
| 2380 | - | - | 【预训练前沿】专用预训练 SPT：领域数据混进预训练，为什么 1B 能打赢微调的 3B | 4:17 | [link](https://www.bilibili.com/video/BV1Zbea6GEq7) |
| 2381 | - | - | 【ICLR 2026】数据重复训练，决定过拟合的是次数还是间隔？记忆窗口与 190 个 epoch | 4:10 | [link](https://www.bilibili.com/video/BV1XFea6wEqq) |
| 2382 | - | - | 【推理 RL】OctoThinker：通过中段训练补推理语料，改进 Llama 做 RL 时长度失控、不涨分的问题 | 3:51 | [link](https://www.bilibili.com/video/BV19Fea6wEg4) |
| 2383 | - | - | 【面试高频】什么是 Checkpoint？梯度/激活检查点：大模型省显存的救命技巧 | 4:23 | [link](https://www.bilibili.com/video/BV1dmM36EESX) |
| 2384 | - | - | 【面试进阶】张量并行为什么先列切再行切？MLP 的切分秘密全在 GELU | 3:22 | [link](https://www.bilibili.com/video/BV1nCKW6XEji) |
| 2385 | - | - | 【面试高频】大模型训练所需显存怎么计算？三大件 + RLHF 讲透 | 2:42 | [link](https://www.bilibili.com/video/BV1R7gD6FEF5) |
| 2386 | - | - | 【面试高频】一层 Decoder 张量并行需要几次通信？答案 4 次 All-Reduce | 2:34 | [link](https://www.bilibili.com/video/BV1ZXKx6WEnK) |
| 2387 | - | - | 【面试高频】Scatter/Gather/Reduce/AllReduce 分别是什么？5 个通信原语一张图讲透 | 2:52 | [link](https://www.bilibili.com/video/BV1wCKx6hEoy) |
| 2388 | - | - | 【面试高频】DeepSpeed 的 3 个 Stage 是什么？ZeRO 逐级切分省显存讲透 | 3:15 | [link](https://www.bilibili.com/video/BV1BuKx69EDn) |
| 2389 | - | - | 【ZeRO 显存优化】70 亿参数训练要 110G？三刀砍掉 100G 冗余 | 4:04 | [link](https://www.bilibili.com/video/BV13tgX6cEYZ) |
| 2390 | - | - | 【分布式训练收官】序列并行 × 专家并行：百万 token 与上千专家的解法 | 3:44 | [link](https://www.bilibili.com/video/BV1VxgX6aEz8) |
| 2391 | - | - | 【Megatron 张量并行】一层都装不下？把权重矩阵劈开算 —— 4 次 AllReduce 讲透 | 3:54 | [link](https://www.bilibili.com/video/BV1GxgX6aELP) |
| 2392 | - | - | 【Ring AllReduce】打破参数服务器瓶颈：PyTorch DDP 的底层核心 | 4:14 | [link](https://www.bilibili.com/video/BV1Qggd6uE9u) |
| 2393 | - | - | 【流水线并行】显卡摸鱼的元凶：GPipe 挤气泡 vs PipeDream 1F1B | 4:11 | [link](https://www.bilibili.com/video/BV15WgR6rEfr) |
| 2394 | - | - | 【训练工程】断点续训详解：为什么恢复权重远远不够 | 0:53 | [link](https://www.bilibili.com/video/BV1UB826dEuV) |
| 2395 | - | - | 【分布式训练】通信瓶颈详解：为什么多节点训练卡在网络而不是算力 | 1:03 | [link](https://www.bilibili.com/video/BV1FF8m6CEdp) |
| 2396 | - | - | 【训练工程】大规模训练容错：Flash Checkpoint、DLRover 与 checkpoint 频率权衡 | 1:02 | [link](https://www.bilibili.com/video/BV1H58265EA1) |
| 2397 | - | - | 【训练效率】MFU 和 GPU 利用率的区别在哪里？兼谈 MFU 与 HFU | 3:13 | [link](https://www.bilibili.com/video/BV1Vh826YExp) |
| 2398 | - | - | 【RLHF 工程】PPO 训练显存爆炸怎么办？四模型驻留、offload 与稳定性调参 | 1:58 | [link](https://www.bilibili.com/video/BV15V8S6kEkq) |
| 2399 | - | - | 【显存必修】训练显存花在哪？缩 batch、梯度检查点、ZeRO、LoRA 四级省显存阶梯 | 3:13 | [link](https://www.bilibili.com/video/BV15Q8467EdP) |
| 2400 | - | - | 【显存优化】激活检查点选层策略：Uniform、Selective 与根号 n 法则 | 1:51 | [link](https://www.bilibili.com/video/BV1xg8t6NEQW) |
| 2401 | - | - | 【混合精度】BF16 / FP16 / FP8 选型决策树：尾数指数位数决定一切 | 2:19 | [link](https://www.bilibili.com/video/BV1NV8t6AEpU) |
| 2402 | - | - | 【训练加速】FP8 训练实操：E4M3/E5M2 选型、分层策略与 Transformer Engine 配置 | 2:02 | [link](https://www.bilibili.com/video/BV1D9b56eEv4) |
| 2403 | - | - | 【训练工程】GPU 利用率周期性归零：IO 瓶颈的定位与优化 | 3:14 | [link](https://www.bilibili.com/video/BV1xfb56cEdo) |
| 2404 | - | - | 【混合精度】Loss Scaling 与 GradScaler 详解：FP16 下溢怎么救，BF16 为何不用 | 2:58 | [link](https://www.bilibili.com/video/BV1JjbL6UEEe) |
| 2405 | - | - | 【DeepSpeed 配置】ZeRO Stage 怎么选、offload 怎么开：config.json 手把手 | 2:15 | [link](https://www.bilibili.com/video/BV1WTbL6REnE) |
| 2406 | - | - | 【分布式必修】并行策略选型决策树：DDP、ZeRO、张量并行、流水线并行 | 3:05 | [link](https://www.bilibili.com/video/BV1w9b76wE1c) |
| 2407 | - | - | 【性能分析】给训练做体检：PyTorch Profiler 与 nsys 的用法与瓶颈定位 | 2:55 | [link](https://www.bilibili.com/video/BV1eMbE6DEWh) |
| 2408 | - | - | 【训练效率】长度分桶策略：padding 浪费 98% 是怎么发生的 | 2:06 | [link](https://www.bilibili.com/video/BV1dxb76JEjP) |
| 2409 | - | - | 【分布式训练】同步 vs 异步梯度更新：staleness 与 99% 选同步的理由 | 1:45 | [link](https://www.bilibili.com/video/BV1Uzb766EtP) |
| 2410 | - | - | 【训练效率】序列 Packing 实现详解：装箱算法、cu_seqlens 与 block diagonal mask | 2:10 | [link](https://www.bilibili.com/video/BV1KPb76vEWq) |
| 2411 | - | - | 【训练效率】varlen attention 配置详解：cu_seqlens、position_ids 与 packing 的配套关系 | 1:55 | [link](https://www.bilibili.com/video/BV1MZbj6zEeK) |
| 2412 | - | - | 【混合精度面试】纯 bf16 训练为什么会停滞？相对更新小于 0.39% 就被舍入吞掉 | 4:30 | [link](https://www.bilibili.com/video/BV1viea6qEhh) |
| 2413 | - | - | 【训练显存】大词表训练时 logits 为什么吃掉 89% 显存？Cut Cross-Entropy 与 Liger Kernel 讲透 | 4:12 | [link](https://www.bilibili.com/video/BV19Reh6vEk5) |
| 2414 | - | - | 【面试必考】大模型Agent的Function Calling怎么设计更稳定？约束解码/工具检索/校验重试三层拆解 | 4:23 | [link](https://www.bilibili.com/video/BV14aMP6jEj3) |
| 2415 | - | - | 【面试前沿】大模型Agentic RL最新方向到底是什么？从GLM/Qwen看RL的下半场 | 5:57 | [link](https://www.bilibili.com/video/BV1HcMP6qEfQ) |
| 2416 | - | - | 【面试前沿】Agentic RL 中的行为崩塌到底是什么？从 Search-R1 复现看行为相变 | 5:00 | [link](https://www.bilibili.com/video/BV1vNMu6gEkG) |
| 2417 | - | - | 【Agent 工程】工具调用失败时，怎么保证 Agent 不死循环或乱回答？ | 5:42 | [link](https://www.bilibili.com/video/BV1oZT161Ez4) |
| 2418 | - | - | 【论文精读】35B 打平万亿参数？该 Scale 的是轨迹不是参数 | 4:26 | [link](https://www.bilibili.com/video/BV1GrMx6SE63) |
| 2419 | - | - | 【论文精读】Agent 最缺的能力是收手？28000 任务实测｜Agentic Abstention | 3:31 | [link](https://www.bilibili.com/video/BV1cHMx6YEXj) |
| 2420 | - | - | 【面试高频】MCP 与 Skills 有什么区别？连接协议 vs 行为规范，附协同关系与省 token 原理 | 3:16 | [link](https://www.bilibili.com/video/BV14zNH69EYY) |
| 2421 | - | - | 【Agent 设计模式】Reflexion：语言化反思+记忆，不改参数从失败中迭代改进 | 3:22 | [link](https://www.bilibili.com/video/BV1SMKs6vEwe) |
| 2422 | - | - | 【强化学习第一课】MDP 与贝尔曼方程：五要素、回报、价值函数、价值迭代 | 3:31 | [link](https://www.bilibili.com/video/BV1SqKT6QERp) |
| 2423 | - | - | 【Agent 范式】Plan-and-Execute vs ReAct：先规划再执行，长任务为什么要先拆 | 3:25 | [link](https://www.bilibili.com/video/BV1NqKW6oEEQ) |
| 2424 | - | - | 【LLM Agent】LATS：把蒙特卡洛树搜索搬进 Agent，比 ReAct 强 20-30% | 4:41 | [link](https://www.bilibili.com/video/BV1wk3R6pEKs) |
| 2425 | - | - | 【LLM 工具使用】Toolformer 讲透：让模型自监督学会"何时调工具"，零人工标注 | 4:55 | [link](https://www.bilibili.com/video/BV1e63Z6nECL) |
| 2426 | - | - | 【Agent 工程化】约四成 Agent 项目失败：五道鸿沟与系统工程化四板斧 | 2:51 | [link](https://www.bilibili.com/video/BV1NS826nEDS) |
| 2427 | - | - | 【Agent 前沿】Agent-Omit：通过省略思考与观察改进多轮 Agent 的上下文膨胀问题 | 3:01 | [link](https://www.bilibili.com/video/BV1JMeY61EcG) |
| 2428 | - | - | 【Agentic RL】River：通过过滤劣质合成环境改进终端 Agent RL 的奖励质量，不到 30% 的环境增益翻倍 | 2:59 | [link](https://www.bilibili.com/video/BV1rNeY6mE54) |
| 2429 | - | - | 【Agent RL】OTC-PO：把工具生产率写进奖励，为什么能让工具调用减 68.3% 而正确率不变 | 3:03 | [link](https://www.bilibili.com/video/BV1bUea6bE1M) |
| 2430 | - | - | 【Agent RL】长程工具 Agent 的 RL 配方怎么定？1K 条 4:3:3 数据、按模型大小配奖励、工具故障率压到 5% 以下 | 3:23 | [link](https://www.bilibili.com/video/BV1tQea64E5C) |
| 2431 | - | - | 【Agent RL】CompactionRL：通过把写摘要纳入 RL 训练，改进长程 Agent 的上下文压缩问题 | 4:24 | [link](https://www.bilibili.com/video/BV1y5ea6QEnz) |
| 2432 | - | - | 【Agent 训练】DART-SD：多轮工具调用是菱形不是链，只在第一个断点之后算 loss，BFCL 多轮 57.38 对 48.81 | 4:43 | [link](https://www.bilibili.com/video/BV115ea6QEuR) |
| 2433 | - | - | 【Agent RL】EnvHarness：通过围绕策略弱点改写环境动态，改进 Agent RL 的环境饱和问题（HF 518 赞） | 4:28 | [link](https://www.bilibili.com/video/BV1Cjea6nEUc) |
| 2434 | - | - | 【Agent RL】harness 原生 RL：在模型 API 边界记 token，训练与部署用同一套脚手架 | 4:33 | [link](https://www.bilibili.com/video/BV11jea6nEaK) |
| 2435 | - | - | 【Agent RL】多轮交互 RL 为什么学到的是裁判偏好？ARC 按策略分组 τ-airline +12.67，FACA 用户反应奖励 +10.22 | 4:52 | [link](https://www.bilibili.com/video/BV1rxea65EFj) |
| 2436 | - | - | 【Agent RL 面试】多轮 Agent RL 里工具返回的 token 为什么要 mask？loss、KL、重要性比三处都要排 | 3:59 | [link](https://www.bilibili.com/video/BV1B8ea6rEc7) |
| 2437 | - | - | 【RL 前沿】不用反向传播能训大模型 Agent 吗？进化策略与 GRPO 的方差、显存与 pass@k 对比 | 4:38 | [link](https://www.bilibili.com/video/BV1zbea6GEF9) |
| 2438 | - | - | 【大模型训练】同策略蒸馏 On-Policy Distillation：AIME 74.4 反超 RL，算力只要 1/10 | 3:30 | [link](https://www.bilibili.com/video/BV16tTk6zE7N) |
| 2439 | - | - | 【面试前沿】OPD 的 reward 设计合理吗？从 log 无界到 PowerOPD 幂变换 | 6:09 | [link](https://www.bilibili.com/video/BV1DtTC6tEy4) |
| 2440 | - | - | 【论文精读】蒸馏也会学出假实力？DOPD 揭穿特权错觉｜OPD 系列 | 4:30 | [link](https://www.bilibili.com/video/BV1AHMx6YEwW) |
| 2441 | - | - | 【后训练前沿】什么是 On-Policy Distillation？取 SFT 与 RL 之长（reverse KL 详解） | 3:58 | [link](https://www.bilibili.com/video/BV1BnMh6BEMz) |
| 2442 | - | - | 【模型压缩经典】知识蒸馏 KD：软标签、暗知识、温度、KL+CE 双损失 | 3:12 | [link](https://www.bilibili.com/video/BV1VcKs63Eo5) |
| 2443 | - | - | 【蒸馏细节】温度系数讲人话：T 在软化什么、为什么蒸馏 loss 要乘 T² 补偿 | 2:58 | [link](https://www.bilibili.com/video/BV1dXKW61EpT) |
| 2444 | - | - | 【反直觉】集成、蒸馏、自蒸馏三个秘密：多视角假设，为什么自蒸馏也能涨点 | 3:28 | [link](https://www.bilibili.com/video/BV1UgKs6PE4p) |
| 2445 | - | - | 【Alignment Tax】RLHF 让模型变乖，也让它变笨 — PPO-ptx 解法详解 | 3:52 | [link](https://www.bilibili.com/video/BV1cH3d6dETE) |
| 2446 | - | - | 【大模型对齐】1952 年的公式撑起 ChatGPT：Bradley-Terry 模型讲透 | 3:45 | [link](https://www.bilibili.com/video/BV1iS3R6mEdV) |
| 2447 | - | - | 【LLaMA 3 对齐】Iterative DPO：让模型自我改进，PPO 效果的 1/10 成本 | 3:48 | [link](https://www.bilibili.com/video/BV1JC3R6QE5N) |
| 2448 | - | - | 【LLaMA 3 的选择】Online RLHF vs Offline RLHF：在线交互与静态数据的取舍 | 4:56 | [link](https://www.bilibili.com/video/BV1Gc3d6gEDo) |
| 2449 | - | - | 【RLHF】RM 损失函数为什么用 sigmoid 差值?Pairwise Ranking 讲透 | 4:35 | [link](https://www.bilibili.com/video/BV1UN3d6iErs) |
| 2450 | - | - | 【LLM 对齐】RLHF 三阶段：SFT → RM → PPO 是怎么串起来的？ | 4:33 | [link](https://www.bilibili.com/video/BV1Qf3R66E8c) |
| 2451 | - | - | 【RLHF】Reward Model Calibration：RM 分数到底能不能信？0.2 差距的真实含义 | 4:54 | [link](https://www.bilibili.com/video/BV1GZ3R6GEmJ) |
| 2452 | - | - | 【面试高频】一次讲透宪法AI与RLAIF：大模型如何用AI反馈替代人类标注 | 4:03 | [link](https://www.bilibili.com/video/BV1iLuY6CESB) |
| 2453 | - | - | 【面试高频】DPO 变体全家桶：SimPO/KTO/ORPO/IPO 各改了什么、怎么选？ | 3:18 | [link](https://www.bilibili.com/video/BV1zKuY6SEhi) |
| 2454 | - | - | 【面试高频】生成式奖励模型GRM全解：会思考的考官，让奖励不再黑箱 | 3:36 | [link](https://www.bilibili.com/video/BV1zKuY6SEqJ) |
| 2455 | - | - | 【面试高频】不用成对偏好数据怎么做对齐？KTO 把前景理论塞进训练目标，损失厌恶一战封神 | 3:41 | [link](https://www.bilibili.com/video/BV1zMuY6EEZD) |
| 2456 | - | - | 【面试高频】SimPO vs DPO：扔掉参考模型，显存省一半还更强？ | 3:22 | [link](https://www.bilibili.com/video/BV196ua6qELh) |
| 2457 | - | - | 【对齐踩坑】DPO 的 loss 一直降，模型为什么反而变差？隐式奖励的作弊通道 | 2:52 | [link](https://www.bilibili.com/video/BV1AX826EEgv) |
| 2458 | - | - | 【DPO 实操】偏好数据怎么构造？三种生产方式、四个质量陷阱与完整流程 | 3:11 | [link](https://www.bilibili.com/video/BV1PD826SEAJ) |
| 2459 | - | - | 【RLHF 基础】奖励模型是怎么训练出来的？用排序代替打分的成对比较损失 | 2:36 | [link](https://www.bilibili.com/video/BV17T8S62EnA) |
| 2460 | - | - | 【DPO 原理】reference model 为什么不能丢？KL 约束的数学体现 | 2:48 | [link](https://www.bilibili.com/video/BV1uN8t6zEwx) |
| 2461 | - | - | 【蒸馏实操】推理能力蒸馏三法：CoT 数据、on-policy 与 SFT + RLVR | 1:59 | [link](https://www.bilibili.com/video/BV1cob76FERQ) |
| 2462 | - | - | 【DPO 调参】beta 参数详解：物理意义、两侧失效表现与经验值 | 2:41 | [link](https://www.bilibili.com/video/BV1dxb76JEVc) |
| 2463 | - | - | 【OPD 系列 05】Distilled RL：通过让老师重分配学生梯度，改进 OPD 的师生差距两难 | 3:57 | [link](https://www.bilibili.com/video/BV1CweY6SENu) |
| 2464 | - | - | 【OPD 系列】MOPD：用多教师在线蒸馏改进多域 RL 能力融合的跷跷板问题，Open-MOPD 从 35.6% 修到 83.4% | 3:29 | [link](https://www.bilibili.com/video/BV1hyea6wELy) |
| 2465 | - | - | 【OPD 系列】在线蒸馏需要多少数据？为什么 8 道难题就能追平 1.7 万条，驱动收益的是思维链长度 | 3:13 | [link](https://www.bilibili.com/video/BV1yZea6pEVy) |
| 2466 | - | - | 【在线蒸馏】OPSA：通过压低学生自身低概率 token 改进 OPD 的老师噪声问题，不要老师 AIME24 +35 | 3:56 | [link](https://www.bilibili.com/video/BV1rWea61EUz) |
| 2467 | - | - | 【对齐面试】Likelihood Displacement：为什么 DPO 越训 chosen 的概率越低？安全 DPO 拒答率反降 55% | 3:34 | [link](https://www.bilibili.com/video/BV1ivea6MEGr) |
| 2468 | - | - | 【面试高频】权重初始化 0.02 的由来：Xavier/He、残差流与小初始化，为什么不是随便设的 | 3:57 | [link](https://www.bilibili.com/video/BV17BNa6NEDc) |
| 2469 | - | - | 【面试高频】学习率 Warmup 为什么重要：损失面陡峭 + Adam 二阶矩不准，不加会怎样 | 3:19 | [link](https://www.bilibili.com/video/BV1F5Kj68Ecy) |
| 2470 | - | - | 【面试高频】学习率 Warmup 为什么重要：损失面陡峭 + Adam 二阶矩不准，不加会怎样 | 3:19 | [link](https://www.bilibili.com/video/BV1qcKM6KEDe) |
| 2471 | - | - | 【面试进阶】Muon 优化器凭什么取代 AdamW？只存动量、显存减半，还收敛更快 | 3:44 | [link](https://www.bilibili.com/video/BV1LLKx6SEkQ) |
| 2472 | - | - | 【大模型优化器】Adam 统治 10 年，三个新挑战者正在分庭抗礼——Lion/Sophia/Adafactor 讲透 | 3:54 | [link](https://www.bilibili.com/video/BV1F13R6nEAV) |
| 2473 | - | - | 【面试进阶】μTransfer原理详解：小模型调超参如何零样本迁移到大模型 | 3:49 | [link](https://www.bilibili.com/video/BV1ftua61Ezc) |
| 2474 | - | - | 【面试高频】WSD 学习率调度凭什么能随时停？三段式拆解+省算力套路 | 3:41 | [link](https://www.bilibili.com/video/BV1P5ua6xErX) |
| 2475 | - | - | 【训练技巧】梯度累积 vs 真大 batch：三个不等价的地方与实操建议 | 1:01 | [link](https://www.bilibili.com/video/BV1w9826mEYd) |
| 2476 | - | - | 【训练必修】大模型学习率怎么选？LR Range Test、warmup 与 cosine decay 实操 | 2:25 | [link](https://www.bilibili.com/video/BV13i826FEjB) |
| 2477 | - | - | 【优化器】Spike-Aware Adam：loss 尖峰之后动量 buffer 的残留问题 | 0:58 | [link](https://www.bilibili.com/video/BV15Z846VE3Y) |
| 2478 | - | - | 【训练调参】Batch size 怎么选？Critical Batch Size 与线性缩放规则详解 | 3:07 | [link](https://www.bilibili.com/video/BV1TM8t6iEFL) |
| 2479 | - | - | 【训练技巧】学习率衰减策略对比：cosine、linear 与 WSD 的适用场景 | 2:09 | [link](https://www.bilibili.com/video/BV1uP8t6uEud) |
| 2480 | - | - | 【科学调参】梯度噪声尺度：用一百步小实验算出最优 batch size | 2:03 | [link](https://www.bilibili.com/video/BV1bfb56cENP) |
| 2481 | - | - | 【调参工具】LR Finder 详解：怎么画、怎么读、怎么和 warmup 配合 | 2:58 | [link](https://www.bilibili.com/video/BV1fLbL6EEFL) |
| 2482 | - | - | 【多任务训练】loss 权重平衡三法：手动调权、不确定性加权与 GradNorm | 1:49 | [link](https://www.bilibili.com/video/BV1cgbL6XEYc) |
| 2483 | - | - | 【调参细节】warmup 步数详解：比例怎么定、做错了会怎样、怎么监控 | 2:26 | [link](https://www.bilibili.com/video/BV1qcbE6xEoL) |
| 2484 | - | - | 【优化器】Weight Decay 详解：系数怎么选、为什么 AdamW 的解耦这么关键 | 2:02 | [link](https://www.bilibili.com/video/BV1ebb76EEYc) |
| 2485 | - | - | 【训练细节】初始化标准差 0.02 的由来：从方差不变推导到实践修正 | 2:39 | [link](https://www.bilibili.com/video/BV1dbb767EV5) |
| 2486 | - | - | 【优化器面试】大模型 Adam 的 β₂ 为什么是 0.95 而不是 0.999？记忆 20 步 vs 1000 步 | 4:12 | [link](https://www.bilibili.com/video/BV1Zaea6gE8C) |
| 2487 | - | - | 【面试高频】大模型的 badcase 如何解决？从便宜到贵的解决顺序 | 2:44 | [link](https://www.bilibili.com/video/BV1YsKx6CEJq) |
| 2488 | - | - | 【面试高频】模型合并 TIES 与 DARE 原理全拆解：任务向量加减法如何缝合大模型 | 3:54 | [link](https://www.bilibili.com/video/BV1Z8ua65E9h) |
| 2489 | - | - | 【DeepSeek R1】R1 是怎么训练出来的？四阶段配方：RL 涌现、冷启动、拒绝采样、蒸馏 | 3:25 | [link](https://www.bilibili.com/video/BV1RL8S6gECS) |
| 2490 | - | - | 【全景图】大模型训练 pipeline 设计：PT、SFT、偏好对齐与 PAFT 并行范式 | 3:18 | [link](https://www.bilibili.com/video/BV1zwbE6REjt) |
| 2491 | - | - | 【零成本提升】Model Soup 详解：权重平均为什么有效、三种炖法怎么选 | 1:55 | [link](https://www.bilibili.com/video/BV1Qvb76VEQi) |
| 2492 | - | - | 【后训练工程】BCIT：通过绑定来源上下文与小预算试跑，改进后训练配方跨基座复用的有害迁移问题 | 3:48 | [link](https://www.bilibili.com/video/BV1ijeY6gELo) |
| 2493 | - | - | 【企业后训练】线上流量怎么变成后训练？T-Tech 三个 GRPO 专家各撞一种作弊与两段 SLERP 合并，32B 超过 235B | 3:49 | [link](https://www.bilibili.com/video/BV1eBea6KEWE) |
| 2494 | - | - | 【后训练】Self-Routing：通过按对错与置信度把样本分到四条路，改进后训练用单一算法的浪费 | 3:29 | [link](https://www.bilibili.com/video/BV14Xea6dE8q) |
| 2495 | - | - | 【后训练方法论】训练的中间阶段该怎么评估？RL 前分最低的 Mixed SFT，RL 后打败 next-chunk RL | 4:22 | [link](https://www.bilibili.com/video/BV1iYea6zEvS) |
| 2496 | - | - | 【数据工程刚需】预训练数据清洗全流程：抽正文、质量过滤、去重、数据配比 | 4:04 | [link](https://www.bilibili.com/video/BV1QNK46LEea) |
| 2497 | - | - | 【数据工程硬核】数据去重 MinHash / SimHash：Jaccard、LSH 分桶、汉明距离 | 3:47 | [link](https://www.bilibili.com/video/BV1EdKx6pEuH) |
| 2498 | - | - | 【数据为王】FineWeb：15T token 数据集怎么筛出来的，消融驱动、FineWeb-Edu | 3:32 | [link](https://www.bilibili.com/video/BV127K46TEyc) |
| 2499 | - | - | 【RLHF】Anthropic HH 数据集：Helpful 和 Harmless 是怎么标注的？ | 4:00 | [link](https://www.bilibili.com/video/BV1oQ3R6LEgz) |
| 2500 | - | - | 【数据工程】Phi-2：Textbooks Are All You Need——2.7B 打赢 70B，质量胜过规模 | 3:35 | [link](https://www.bilibili.com/video/BV1SP3d6TE81) |
| 2501 | - | - | 【训练技巧】课程学习工程实现：难度评估、课程设计与 pacing 控制 | 2:08 | [link](https://www.bilibili.com/video/BV1uw8t66Eo2) |
| 2502 | - | - | 【数据工程】文本数据增强三法：回译、改写与 GPT-4 生成的适用场景 | 1:55 | [link](https://www.bilibili.com/video/BV1MT8t6TEwW) |
| 2503 | - | - | 【IFT 数据】Self-Instruct 与 Evol-Instruct：指令微调数据的构造与三层过滤 | 2:02 | [link](https://www.bilibili.com/video/BV1fVbL6SECM) |
| 2504 | - | - | 【数据工程】合成数据完整 pipeline：Self-Instruct、Evol-Instruct 与四步质量控制 | 1:52 | [link](https://www.bilibili.com/video/BV1qNbE6XEU2) |
| 2505 | - | - | 【数据工程】标注质量控制：流程、Cohen Kappa 一致性检验与五个质控手段 | 2:10 | [link](https://www.bilibili.com/video/BV1L4b76SEAd) |
| 2506 | - | - | 【数据配比】代码与数学数据加多少？20%~40% 最优区间与梯度实验结论 | 2:51 | [link](https://www.bilibili.com/video/BV198b762Euk) |
| 2507 | - | - | 【数据工程】数据去重实操：MinHash、LSH 分桶与亿级数据并行处理 | 2:07 | [link](https://www.bilibili.com/video/BV1Zpb76HEeu) |
| 2508 | - | - | 【数据工程】数据不均衡详解：五步诊断、三种解法与主流模型配比 | 2:09 | [link](https://www.bilibili.com/video/BV1onb76XEqP) |
| 2509 | - | - | 【中文大模型】中英数据配比：1T 纯中文 vs 2T 混合的实验结论与跨语言迁移 | 2:43 | [link](https://www.bilibili.com/video/BV1QYb76yEBu) |
| 2510 | - | - | 【数据质量】SFT 数据自动筛选：GPT-4 打分、PPL 检测与 embedding 聚类 | 1:47 | [link](https://www.bilibili.com/video/BV1xPb76vEzd) |
| 2511 | - | - | 【数据工程】预训练数据配比：主流模型参考、DoReMi 与消融实验 | 1:53 | [link](https://www.bilibili.com/video/BV1TKb76PEcu) |
| 2512 | - | - | 【RL 数据配比】数学、代码、表格混训 RL，哪些域能跨域迁移、哪些必须专训？Guru 六域实验与 CARE-RL、TAC | 3:45 | [link](https://www.bilibili.com/video/BV1yVea6pE2L) |
| 2513 | - | - | QwenVL到Qwen3.5技术改进 | 3:36 | [link](https://www.bilibili.com/video/BV1GpXaBGEoE) |
| 2514 | - | - | 【文生图地基】DDPM 扩散模型原理：前向加噪、反向去噪，为什么 loss 化简成预测噪声 | 3:36 | [link](https://www.bilibili.com/video/BV1qyNo6TEN1) |
| 2515 | - | - | 【扩散加速】DDIM 采样原理：非马尔可夫、确定性采样，50 步媲美 1000 步不用重训 | 1:07 | [link](https://www.bilibili.com/video/BV1ikNo6BEkC) |
| 2516 | - | - | 【扩散进阶】Score/SDE 统一视角：分数场、Langevin 采样，DDPM 与分数匹配的统一 | 3:42 | [link](https://www.bilibili.com/video/BV1ikNo6BE9h) |
| 2517 | - | - | 【文生图必调】Classifier-Free Guidance 原理：一个系数如何权衡真实感与多样性 | 3:21 | [link](https://www.bilibili.com/video/BV1qkNo6BEzF) |
| 2518 | - | - | 【多模态第一课】CLIP 原理：图文对比预训练、InfoNCE、zero-shot 分类 | 3:29 | [link](https://www.bilibili.com/video/BV1YGKM6ZEuh) |
| 2519 | - | - | 【多模态】BLIP-2 的 Q-Former：可学习 query、cross-attention，桥接冻结视觉与 LLM | 3:24 | [link](https://www.bilibili.com/video/BV1Y3KM6bEjj) |
| 2520 | - | - | 【多模态】LLaVA 视觉对齐：CLIP ViT、Projector 投影层、两阶段训练 | 3:32 | [link](https://www.bilibili.com/video/BV1SzKT6nEPj) |
| 2521 | - | - | 【多模态】视觉编码器盘点：Patch、ViT、Projector，各家 VLM 视觉塔对比 | 3:39 | [link](https://www.bilibili.com/video/BV1MzKT6HESr) |
| 2522 | - | - | 【语音合成】VITS 端到端 TTS：变分推断、归一化流、对抗训练，一步合成语音 | 3:33 | [link](https://www.bilibili.com/video/BV1QwKs6zEhi) |
| 2523 | - | - | 【语音大模型地基】音频 Tokenizer：VQ-VAE、RVQ 残差量化，语音怎么离散化成 token | 3:50 | [link](https://www.bilibili.com/video/BV1jdKW6yEgH) |
| 2524 | - | - | 【文生图全流程】Stable Diffusion 原理：潜空间扩散、CLIP、U-Net、cross-attention | 3:35 | [link](https://www.bilibili.com/video/BV123Ks6YEfb) |
| 2525 | - | - | 【Sora 同款骨干】DiT 原理：patchify、adaLN-Zero，Transformer 取代 U-Net | 3:09 | [link](https://www.bilibili.com/video/BV1uTKs6TE4B) |
| 2526 | - | - | 【文生图最新范式】Flow Matching / Rectified Flow：向量场、拉直路径，SD3/FLUX 同款 | 3:40 | [link](https://www.bilibili.com/video/BV1mYKW68Esk) |
| 2527 | - | - | 【语音大模型入门】Whisper 原理：弱监督 68 万小时、encoder-decoder、特殊 token 多任务 | 3:00 | [link](https://www.bilibili.com/video/BV1qYKs6EEBj) |
| 2528 | - | - | 【生成基石】VAE 变分自编码器：ELBO 推导、重参数化、KL 正则的作用 | 3:58 | [link](https://www.bilibili.com/video/BV1U5K46uEJN) |
| 2529 | - | - | 【扩散进阶】扩散的数学=分层 VAE：x₀/噪声/分数 三种预测目标为什么等价 | 3:42 | [link](https://www.bilibili.com/video/BV1nPKW6JEJy) |
| 2530 | - | - | 【面试高频】多模态早融合 vs 后融合：Chameleon 凭什么把图文从头一起训 | 3:29 | [link](https://www.bilibili.com/video/BV1iLuY6CEX1) |
| 2531 | - | - | 【面试高频】NaViT 原生任意分辨率 + Patch n' Pack：视觉大模型为什么不再把图片压成方块？ | 3:14 | [link](https://www.bilibili.com/video/BV1oYua6GERd) |
| 2532 | - | - | 【面试高频】多模态大模型又慢又贵？视觉Token压缩 ToMe / FastV 两招讲透 | 3:37 | [link](https://www.bilibili.com/video/BV1Kuua6fEf3) |
| 2533 | - | - | 【AIGC 加速】一致性模型为什么能一步出图？从去噪轨迹讲到 LCM-LoRA | 2:34 | [link](https://www.bilibili.com/video/BV1mC826sEre) |
| 2534 | - | - | 【前沿架构】扩散语言模型为什么能一次并行吐出一整句？离散扩散原理详解 | 2:20 | [link](https://www.bilibili.com/video/BV1fF8m6kEiA) |
| 2535 | - | - | 【多模态】Google 用 sigmoid 替代 softmax——SigLIP vs CLIP 讲透 | 4:23 | [link](https://www.bilibili.com/video/BV1GZ846VETv) |
| 2536 | - | - | 【多模态基石】ViT 视觉 Transformer：把图像切成 patch，Transformer 也能做视觉 | 4:48 | [link](https://www.bilibili.com/video/BV1VR846LEY6) |
| 2537 | - | - | 【多模态面试】VLM 微调要不要解冻视觉编码器？只训 ViT 感知涨分、MMMU 可能下降，按任务来定 | 3:18 | [link](https://www.bilibili.com/video/BV1CJea6EEXs) |
| 2538 | - | - | 【大模型训练】GLM-5.2 为什么放弃 GRPO 换回 critic-based PPO？三个隐性假设崩塌全解析 | 4:06 | [link](https://www.bilibili.com/video/BV1qSTr6vEys) |
| 2539 | - | - | 【大模型训练】从概率模型看 SFT 和 RL 的区别：正向 KL vs 反向 KL 完整推导 | 3:21 | [link](https://www.bilibili.com/video/BV1rKTn65E9V) |
| 2540 | - | - | 【面试必考】GRPO、DAPO、GSPO三代强化学习算法，到底改了什么？从PPO讲起 | 5:04 | [link](https://www.bilibili.com/video/BV1oRMP6hE7f) |
| 2541 | - | - | 【面试高频】RLHF 优化算法进化史：PPO / DPO / GRPO / DAPO / GSPO 一次串清楚 | 3:15 | [link](https://www.bilibili.com/video/BV1qnMh6BEoZ) |
| 2542 | - | - | 【面试必考】PPO 到底在裁剪什么？从策略梯度的坑到那条安全带｜强化学习零基础 | 3:28 | [link](https://www.bilibili.com/video/BV1qnMh6BEx1) |
| 2543 | - | - | 【面试高频】KL 散度计算的三种近似方法？K1/K2/K3 一次讲透 | 2:39 | [link](https://www.bilibili.com/video/BV11jMt6yED7) |
| 2544 | - | - | 【RLHF 面试高频】GRPO 比 PPO 做了什么改进？一刀砍掉 Critic 省显存 | 2:46 | [link](https://www.bilibili.com/video/BV1iJMh6uERR) |
| 2545 | - | - | 【强化学习面试高频】GRPO 的损失为什么开始时是 0？两部分同时归零 | 2:45 | [link](https://www.bilibili.com/video/BV1imM36EEqD) |
| 2546 | - | - | 【面试进阶】GRPO 用旧策略数据，为什么还叫 on-policy？一个打篮球的例子讲透 | 3:09 | [link](https://www.bilibili.com/video/BV1fJNA69EFy) |
| 2547 | - | - | 【面试进阶】什么是重要性采样？为什么 token 级的损失难以收敛？「猫喜欢鱼」讲透 | 3:30 | [link](https://www.bilibili.com/video/BV1HENA6xEpB) |
| 2548 | - | - | 【强化学习】策略梯度定理：log-derivative 技巧、REINFORCE，怎么对随机采样求梯度 | 3:47 | [link](https://www.bilibili.com/video/BV1LVKW6VEEy) |
| 2549 | - | - | 【面试陷阱】GRPO 里被 clip 的 token 反向有没有梯度？用 torch.clamp 一跑就懂 | 2:46 | [link](https://www.bilibili.com/video/BV1HmKx6ZEyX) |
| 2550 | - | - | 【面试高频】ReMax：PPO 的轻量替代，砍 Critic 用 greedy 解码当 baseline | 3:26 | [link](https://www.bilibili.com/video/BV1gYgR6vEt4) |
| 2551 | - | - | 【RLOO 讲透】REINFORCE Leave-One-Out：不要 Critic、不要 greedy 假想敌，同组 response 互卷就够了 | 4:04 | [link](https://www.bilibili.com/video/BV13agR6KEDw) |
| 2552 | - | - | 【PPO 工程】π_θ/π_θ_old 是怎么算的？token-level log prob 的 3 个工程坑 | 4:40 | [link](https://www.bilibili.com/video/BV1Dw3d6BEYP) |
| 2553 | - | - | 【PPO 工程精华】importance sampling ratio + clip：同一 batch 训 4 epoch 的秘密 | 4:36 | [link](https://www.bilibili.com/video/BV1DP3d6TED7) |
| 2554 | - | - | 【RLHF】Reference Model 是干嘛的？为什么 PPO 离不开这个"躺平"的模型 | 4:28 | [link](https://www.bilibili.com/video/BV1Xd3R6kEdU) |
| 2555 | - | - | 【概率视角】SFT 和 RLHF 竟是同一枚硬币的两面：正向 KL vs 反向 KL | 4:26 | [link](https://www.bilibili.com/video/BV1er3Z6SEcf) |
| 2556 | - | - | 【RLHF 理论基础】Token-level MDP：LLM 的 state 和 action 到底是什么？ | 4:08 | [link](https://www.bilibili.com/video/BV1R63Z6nEeD) |
| 2557 | - | - | 【2025 RL 前沿】ASPO：通过重要性比率翻转改进 GRPO 的熵崩塌问题 | 3:23 | [link](https://www.bilibili.com/video/BV1WS826nEh5) |
| 2558 | - | - | 【RL 进阶】DAPO 动态采样：通过过滤全对全错组改进 GRPO 的零梯度浪费 | 2:47 | [link](https://www.bilibili.com/video/BV1rf8265Eg4) |
| 2559 | - | - | 【RL 进阶】DAPO：通过 token 级归一化改进 GRPO 长答案被稀释的问题 | 2:31 | [link](https://www.bilibili.com/video/BV1Ff8265E3j) |
| 2560 | - | - | 【RL 进阶】GSPO：通过序列级重要性比率改进 PPO/GRPO 的逐 token 方差问题 | 2:41 | [link](https://www.bilibili.com/video/BV1Bn826gEWs) |
| 2561 | - | - | 【RLHF 基础】PPO 的 clip 为什么只在一半情况下才生效？不对称四象限详解 | 3:21 | [link](https://www.bilibili.com/video/BV1RG8S6GEhk) |
| 2562 | - | - | 【RLHF 基础】PPO 的奖励为什么只在最后一个 token 才发？逐 token 算账拆解 | 2:41 | [link](https://www.bilibili.com/video/BV1RG8S6GEoq) |
| 2563 | - | - | 【RLHF 基础】PPO 为什么需要四个模型？演员、评论家、奖励、参考各自的作用 | 2:59 | [link](https://www.bilibili.com/video/BV1og8S6CE26) |
| 2564 | - | - | 【RLHF 深入】critic value function 详解：为什么难训准、GAE 怎么补、GRPO 怎么砍 | 3:08 | [link](https://www.bilibili.com/video/BV1uP8t6uE9J) |
| 2565 | - | - | 【RL 原理】credit assignment 与 GRPO 的 advantage 分配机制 | 1:42 | [link](https://www.bilibili.com/video/BV1PTb76YEVw) |
| 2566 | - | - | 【RL 前沿】SIGNBALANCE：通过保号与全局尺度改进 GRPO 给蒙对答案发高奖励的问题，附 DA3PO 难题错误放大 | 4:26 | [link](https://www.bilibili.com/video/BV1nNeY6mEGC) |
| 2567 | - | - | 【RL 面试新题】k3 估计器是无偏的，为什么 KL 项的梯度却是有偏的？放奖励与放 loss 的区别 | 3:27 | [link](https://www.bilibili.com/video/BV1GxeY6PEVi) |
| 2568 | - | - | 【RL 前沿】μ-GRPO：放宽 clip 加负优势否决，GRPO 用 250 倍陈旧的数据为什么不崩 | 3:51 | [link](https://www.bilibili.com/video/BV1aWeY6vEpH) |
| 2569 | - | - | 【GRPO 进阶】OraRL：通过解耦策略基线与标准答案增益，改进 GRPO 塞入标准答案时的优势反转问题 | 4:21 | [link](https://www.bilibili.com/video/BV1hyea6wEyV) |
| 2570 | - | - | 【RL 前沿】VAPO：通过 value 预训练与解耦 GAE 改进长思维链上 critic 训不准的问题（字节 Seed） | 3:30 | [link](https://www.bilibili.com/video/BV1rnea6mE4y) |
| 2571 | - | - | 【面试高频】大模型能过律考却算不对六位数乘法：分词错位+进位是未来信息+概率≠确定+调工具 | 3:17 | [link](https://www.bilibili.com/video/BV1azNU6BEpK) |
| 2572 | - | - | 【面试高频】In-Context Learning 机理：贝叶斯任务定位，为什么乱标签也能 work | 3:24 | [link](https://www.bilibili.com/video/BV1F5Kj68EPG) |
| 2573 | - | - | 【面试高频】涌现能力之争：是真的突现，还是度量假象？精确匹配 vs 平滑指标 | 4:05 | [link](https://www.bilibili.com/video/BV1B5Kj6bEGF) |
| 2574 | - | - | 【可解释性】激活导向详解：不改一个权重，用一个方向向量控制模型性格 | 2:48 | [link](https://www.bilibili.com/video/BV1ty8269ExR) |
| 2575 | - | - | 【范式反思】自回归的三个根本局限：滚雪球错误、无法全局规划、曝光偏差 | 2:55 | [link](https://www.bilibili.com/video/BV1g68264E7h) |
| 2576 | - | - | 【反直觉现象】Grokking 延迟泛化：模型"背完答案"后突然"开窍"，挑战早停智慧 | 3:34 | [link](https://www.bilibili.com/video/BV1Jn826gEKr) |
| 2577 | - | - | 【认知盲区】大模型为什么算不对多位数乘法？三重根因与逆序输入解法 | 2:52 | [link](https://www.bilibili.com/video/BV1rE826rEF6) |
| 2578 | - | - | 【AI 安全】大模型水印是怎么做的？绿名单方案详解：γ 切名单、δ 加分数、z 做检验 | 3:31 | [link](https://www.bilibili.com/video/BV1J7826GEU2) |
| 2579 | - | - | 【可解释性】Logit Lens 详解：把每一层的残差解码成词，看答案如何逐层结晶 | 2:17 | [link](https://www.bilibili.com/video/BV1Ye826hEBW) |
| 2580 | - | - | 【AI 安全】机器遗忘详解：梯度上升、RMU、NPO 三种让大模型选择性失忆的方法 | 2:05 | [link](https://www.bilibili.com/video/BV15t826vEUA) |
| 2581 | - | - | 【可解释性】SAE 稀疏自编码器详解：用 L1 约束把多义神经元拆成单义特征 | 2:58 | [link](https://www.bilibili.com/video/BV1ux8S6eEc4) |
| 2582 | - | - | 【认知盲区】大模型数不清 strawberry 的 r、算不对乘法，根因都在 tokenizer | 3:52 | [link](https://www.bilibili.com/video/BV1hc8t63EKR) |
| 2583 | - | - | 【训练诊断】用 Logit Lens 看训练到底改善了什么：中间层表示 vs 输出映射 | 2:26 | [link](https://www.bilibili.com/video/BV1cGbL6HEzH) |
| 2584 | - | - | 【AI 安全】红队测试实操：四种攻击手法、安全分类器与 RLHF 安全对齐 | 1:54 | [link](https://www.bilibili.com/video/BV1CDb76AEB8) |
| 2585 | - | - | 【RL 面试】RL 微调的幻觉税：为什么 RFT 之后模型对无解题不再拒答？混 10% 无解题 SUM 就能修回来 | 3:15 | [link](https://www.bilibili.com/video/BV1xXea6dECx) |
| 2586 | - | - | 【面试高频】如何理解 MoE 网络？Router 怎么实现？ | 2:38 | [link](https://www.bilibili.com/video/BV15XMp6yEzV) |
| 2587 | - | - | 【面试高频】MoE 架构相比 Dense 有什么好处？一个最小例子把计算量算清楚 | 3:35 | [link](https://www.bilibili.com/video/BV1TTMW6NEqk) |
| 2588 | - | - | 【手撕代码】MoE 设备受限路由怎么写？一招锁死跨卡通信（华为面试真题 / DeepSeek-V2） | 3:09 | [link](https://www.bilibili.com/video/BV1AkKx6wEXL) |
| 2589 | - | - | 【面试进阶】如何计算 sequence 粒度的负载均衡损失？MoE 专家忙闲不均怎么纠偏 | 3:30 | [link](https://www.bilibili.com/video/BV157gD6FE3J) |
| 2590 | - | - | 【MoE 架构】DeepseekMoE 细粒度 + 共享专家：凭什么比标准 MoE 强 10-15%？ | 4:14 | [link](https://www.bilibili.com/video/BV1oS3R62ESL) |
| 2591 | - | - | 【面试高频】DeepSeek 删掉辅助损失，MoE 反而更均衡？无辅助损失负载均衡一次讲透 | 3:15 | [link](https://www.bilibili.com/video/BV11dua64ECo) |
| 2592 | - | - | 【面试高频】Mixture-of-Depths：让 token 学会跳层，Transformer 算力省一半还不掉点 | 3:17 | [link](https://www.bilibili.com/video/BV19qua6zExA) |
| 2593 | - | - | 【Kimi K3】Stable LatentMoE：用三件套改进万亿 MoE 的训练崩溃 | 2:48 | [link](https://www.bilibili.com/video/BV1kL826CETq) |
| 2594 | - | - | 【架构】Mixture of Depths 详解：深度方向的稀疏，与 MoE 有何不同 | 2:17 | [link](https://www.bilibili.com/video/BV1WTbL6REiT) |
| 2595 | - | - | 【MoE 训练】专家忙闲不均怎么治？aux loss 调参与 DeepSeek-V3 动态偏置 | 3:14 | [link](https://www.bilibili.com/video/BV1kKbL6xEm1) |
| 2596 | - | - | 【MoE 训练】从零训练完整流程：专家初始化、router 设置与训练 schedule | 1:48 | [link](https://www.bilibili.com/video/BV1Qvb76VE4D) |
| 2597 | - | - | 【面试前沿】大模型深度思考的自主切换是怎么实现的？不确定性 / 决策器 / 多阶段 RL | 3:15 | [link](https://www.bilibili.com/video/BV1bGMt67E7J) |
| 2598 | - | - | 【面试高频】Zero/One/Few-shot 与 In-Context Learning：GPT-3 为什么是 few-shot learner | 3:36 | [link](https://www.bilibili.com/video/BV1FVKj6cEz6) |
| 2599 | - | - | 【面试高频】思维草稿Chain-of-Draft：一句提示词让大模型少写80%token，正确率几乎不掉 | 3:19 | [link](https://www.bilibili.com/video/BV1q3uY6jEYg) |
| 2600 | - | - | 【面试高频】思维图GoT讲透：链→树→图演进+聚合/回环+三大思维变换，质量涨六成还更省钱 | 3:14 | [link](https://www.bilibili.com/video/BV1nNuY6HEF4) |
| 2601 | - | - | 【面试高频】推理模型的显式思考真的必要吗？NoThinking 跳过思考反而更省更快 | 3:20 | [link](https://www.bilibili.com/video/BV1dYua6GEBn) |
| 2602 | - | - | 【面试高频】推理模型越想越歪？ParaThinker并行思考，打破长思维链的隧道视野 | 3:41 | [link](https://www.bilibili.com/video/BV1dhua6CEmV) |
| 2603 | - | - | 【面试高频】Quiet-STaR 原理拆解：每个 token 前先默想，推理能力自己长出来 | 3:18 | [link](https://www.bilibili.com/video/BV1U2ua6YEr4) |
| 2604 | - | - | 【面试高频】一张图讲透推理型大模型：推理时计算/PRM/搜索/自我进化 四根支柱 | 3:34 | [link](https://www.bilibili.com/video/BV1mQua6FEf9) |
| 2605 | - | - | 【面试高频】7B小模型自进化超o1？rStar-Math三件套(代码CoT+MCTS+过程偏好模型)一次讲透 | 3:31 | [link](https://www.bilibili.com/video/BV1tSua6aEHu) |
| 2606 | - | - | 【面试高频】大模型自我精炼Self-Refine：同一个模型自己批评自己，零训练提升输出质量 | 3:39 | [link](https://www.bilibili.com/video/BV1Gkua6TEHE) |
| 2607 | - | - | 【面试高频】测试时算力 Test-Time Compute：为什么 o1 多想一会儿就变强？四招讲透 | 3:33 | [link](https://www.bilibili.com/video/BV1QCua6vEv2) |
| 2608 | - | - | 【面试高频】思维链一条道走到黑？思维树ToT让大模型学会回溯，正确率从4%飙到74% | 3:11 | [link](https://www.bilibili.com/video/BV1T3ua6tEjt) |
| 2609 | - | - | 【推理增强】自洽性采样详解：为什么多想几遍取多数票能涨点 | 1:50 | [link](https://www.bilibili.com/video/BV1gs8S6NEtr) |
| 2610 | - | - | 【推理增强】Best-of-N 采样详解：四种挑选方法与 RFT 的衔接 | 2:17 | [link](https://www.bilibili.com/video/BV1Qab76LEvu) |
| 2611 | - | - | 大模型面试：为什么现在的大模型都是Decoder-Only架构？ | 3:41 | [link](https://www.bilibili.com/video/BV1uiXmBUEfp) |
| 2612 | - | - | 【面试必考】LayerNorm为什么被RMSNorm全面取代？从0讲透归一化+手撕LLaMA同款代码 | 4:29 | [link](https://www.bilibili.com/video/BV1owTx6pEqM) |
| 2613 | - | - | 【面试高频】请介绍 BERT 的流程：五大部件 + 预训练全讲透 | 2:45 | [link](https://www.bilibili.com/video/BV1SGMt67EEq) |
| 2614 | - | - | 【面试高频】Qwen 从 1 到 3 每个版本改了什么？一条线讲透六代改进点 | 3:20 | [link](https://www.bilibili.com/video/BV1KjMt6yE6h) |
| 2615 | - | - | 【面试高频】BERT 与 LSTM 有什么不同？结构 / 并行 / 双向 / 预训练四维度对比 | 3:11 | [link](https://www.bilibili.com/video/BV1KMMW6eEnp) |
| 2616 | - | - | 【面试高频】Encoder-Only 和 Decoder-Only 建模有何区别？BERT 与 GPT 的分水岭 | 2:41 | [link](https://www.bilibili.com/video/BV1HLNA6tEX9) |
| 2617 | - | - | 【面试高频】Engram 以存储换算力：确定性哈希查表的先天记忆，O(1) 取语义，NIAH 84→97 | 4:15 | [link](https://www.bilibili.com/video/BV17MNS6UEhc) |
| 2618 | - | - | 【面试高频】Kimi AttnRes：把残差升级成对历史层的注意力，伪查询+块级检索，N≈8 延迟<2% | 4:13 | [link](https://www.bilibili.com/video/BV1LVNS6LEHX) |
| 2619 | - | - | 【面试高频】SwiGLU 激活函数：GLU 门控 × Swish，为何取代 ReLU/GELU 成大模型 FFN 标配 | 4:17 | [link](https://www.bilibili.com/video/BV1i3NS62E68) |
| 2620 | - | - | 【面试高频】weight tying 详解：输入输出 Embedding 为什么共享？转置关系 / 省参数 / GPT-2 与 LLaMA 的取舍 | 3:44 | [link](https://www.bilibili.com/video/BV151Na68EcR) |
| 2621 | - | - | 【面试高频】BPE 分词详解：中文为什么比英文更费 Token？子词 / 字节级 / WordPiece / Unigram 全讲透 | 3:25 | [link](https://www.bilibili.com/video/BV1uUN86SEHs) |
| 2622 | - | - | 【面试高频】Word2Vec 词向量详解：CBOW / Skip-gram / 负采样，为什么它是 Embedding 的祖师爷 | 3:49 | [link](https://www.bilibili.com/video/BV1hmN86nEVC) |
| 2623 | - | - | 【面试高频】Transformer FFN 详解：为什么先升维 4 倍再降回？升维 / 降维 / 残差 / SwiGLU 2.67 倍全讲透 | 3:23 | [link](https://www.bilibili.com/video/BV14LN86GEG1) |
| 2624 | - | - | 【面试高频】7B 参数量怎么手算？12Ld²+Vd 公式详解，词嵌入 / 注意力 / FFN 逐块拆解 | 3:17 | [link](https://www.bilibili.com/video/BV1jiNa6iECe) |
| 2625 | - | - | 【面试高频】残差连接为什么重要：退化问题、梯度高速路，与 Transformer 的残差流 | 3:22 | [link](https://www.bilibili.com/video/BV1SXNa6RE4J) |
| 2626 | - | - | 【面试高频】RNN vs CNN vs Transformer：并行能力与长程依赖两把尺子讲透 | 3:37 | [link](https://www.bilibili.com/video/BV1q7Kj64EcD) |
| 2627 | - | - | 【面试高频】Embedding 到底是什么、为什么乘 √d_model：查找表、位置编码与数值量级 | 3:42 | [link](https://www.bilibili.com/video/BV1qyNo6TESa) |
| 2628 | - | - | 【面试高频】7B 参数量怎么手算？12Ld²+Vd 公式详解，词嵌入 / 注意力 / FFN 逐块拆解 | 3:17 | [link](https://www.bilibili.com/video/BV1BwKM6vEGs) |
| 2629 | - | - | 【面试高频】weight tying 详解：输入输出 Embedding 为什么共享？转置关系 / 省参数 / GPT-2 与 LLaMA 的取舍 | 3:44 | [link](https://www.bilibili.com/video/BV1BZKT6MEmC) |
| 2630 | - | - | 【面试高频】BatchNorm 与 LayerNorm 的区别：为什么 Transformer 只用 LayerNorm？ | 3:00 | [link](https://www.bilibili.com/video/BV1j7gD6cE75) |
| 2631 | - | - | 【大模型架构】RetNet 讲透：微软的 Transformer 杀手，训练并行 + 推理 O(1) | 3:54 | [link](https://www.bilibili.com/video/BV1RR3R6VEn7) |
| 2632 | - | - | 【面试高频】扔掉分词器！Byte Latent Transformer 用字节熵动态切 patch 全解析 | 4:03 | [link](https://www.bilibili.com/video/BV1oGuY61EFH) |
| 2633 | - | - | 【面试高频】Mamba+注意力+MoE三合一，Jamba如何把25万字塞进单张显卡？混合架构原理拆解 | 3:18 | [link](https://www.bilibili.com/video/BV1zuuY6mEqQ) |
| 2634 | - | - | 【面试高频】Titans：让大模型在推理时学会长期记忆，注意力+神经记忆到底怎么融合？ | 3:23 | [link](https://www.bilibili.com/video/BV1DCua6vEpr) |
| 2635 | - | - | 【面试进阶】大模型新结构TTT层：处理一条序列=训练一个小模型，线性复杂度+恒定内存扛长文本 | 3:36 | [link](https://www.bilibili.com/video/BV1Muua6fEpa) |
| 2636 | - | - | 【Kimi 新架构】Attention Residuals：用深度方向 softmax 改进残差连接的等权相加问题 | 3:51 | [link](https://www.bilibili.com/video/BV1Nm826QELP) |
| 2637 | - | - | 【面试高频】SwiGLU 的中间层维度为什么是 8/3·d？从参数量守恒一步步推导 | 2:41 | [link](https://www.bilibili.com/video/BV1Qc8t63EsP) |
| 2638 | - | - | 【架构辩论】Transformer 会被取代吗？三个致命伤，取代派/改良派/共存派三种解法 | 3:54 | [link](https://www.bilibili.com/video/BV1jS846SETu) |
| 2639 | - | - | 【训练第一步】tokenizer 词表设计：vocab size、中英混合与 Byte-level BPE | 3:18 | [link](https://www.bilibili.com/video/BV1BPbE6WELv) |
| 2640 | - | - | 【模型压缩】模型剪枝原理：结构化 vs 非结构化、按幅度剪、剪枝+微调 | 3:37 | [link](https://www.bilibili.com/video/BV14eKW6fENJ) |
| 2641 | - | - | 【顶会最佳论文】彩票假设：稀疏子网、重置回初始化，为什么小子网能单独达标 | 3:37 | [link](https://www.bilibili.com/video/BV1w6KW6RENb) |
| 2642 | - | - | 【LLM 剪枝】SparseGPT / Wanda：一次性剪枝不重训，按权重×激活选，公式讲透 | 3:39 | [link](https://www.bilibili.com/video/BV1qgKW6LEDW) |
| 2643 | - | - | 【面试高频】BitNet b1.58 全解：权重只用-1/0/1，乘法变加法，省电71倍还不掉点 | 3:37 | [link](https://www.bilibili.com/video/BV1iGuY61EDX) |
| 2644 | - | - | 【面试高频】大模型四位量化为什么总崩？旋转量化一招治激活离群点 | 3:41 | [link](https://www.bilibili.com/video/BV1mQua6FEAN) |
| 2645 | - | - | 【量化必修】离群激活详解：为什么清零 99% 的激活模型还活着，动几个大的就崩 | 1:59 | [link](https://www.bilibili.com/video/BV1vt826vEKv) |
| 2646 | - | - | 【量化部署】QAT vs PTQ：fake quantization、直通估计器与选型标准 | 2:35 | [link](https://www.bilibili.com/video/BV1pQb76YE6q) |
| 2647 | - | - | 大模型KV Cache原理详解 | 1:51 | [link](https://www.bilibili.com/video/BV12fXyBKEor) |
| 2648 | - | - | 图解大模型缓存 KV Cache的原理 | 3:27 | [link](https://www.bilibili.com/video/BV1yy5o6zELy) |
| 2649 | - | - | 【大模型加速】推测解码 Speculative Decoding 原理详解：从草稿验证到拒绝采样 | 3:31 | [link](https://www.bilibili.com/video/BV1CsTv6tEDU) |
| 2650 | - | - | 【大模型推理】内存墙 Memory-Bound 到底是什么？H100 算力利用率不足 1% 的真相 | 3:28 | [link](https://www.bilibili.com/video/BV1euTj6dEqX) |
| 2651 | - | - | 【推理优化】PagedAttention：显存浪费 60-80% 怎么救｜vLLM 核心技术 | 4:16 | [link](https://www.bilibili.com/video/BV1AHMx6YEAm) |
| 2652 | - | - | 【面试高频】温度·Top-K·Top-P 到底动了什么？解码采样一次讲透 | 3:34 | [link](https://www.bilibili.com/video/BV1cHMx6YE8i) |
| 2653 | - | - | 【面试高频】推理过程中的 KV Cache 怎么估算？从原理到 Qwen/DeepSeek 实算 | 4:55 | [link](https://www.bilibili.com/video/BV1KTMW6NE9t) |
| 2654 | - | - | 【面试高频】大模型推理占用的显存怎么计算？一个公式秒算 | 2:44 | [link](https://www.bilibili.com/video/BV1VsNH6PECF) |
| 2655 | - | - | 【面试高频】现在大模型为什么都用 left padding？一句话讲透 | 2:33 | [link](https://www.bilibili.com/video/BV1CyNH6nEXF) |
| 2656 | - | - | 【面试高频】MTP 多 Token 预测：一次预测多个未来字 + 投机解码，步数砍半提速 1.8× | 3:43 | [link](https://www.bilibili.com/video/BV1EoNg6kERe) |
| 2657 | - | - | 【面试高频】解码策略详解：贪心 / Beam Search / 采样怎么选？束宽、Top-K、Top-P 核采样全讲透 | 3:15 | [link](https://www.bilibili.com/video/BV1LyNa6cELQ) |
| 2658 | - | - | 【面试高频】解码策略详解：贪心 / Beam Search / 采样怎么选？束宽、Top-K、Top-P 核采样全讲透 | 3:15 | [link](https://www.bilibili.com/video/BV1FdKT66EAS) |
| 2659 | - | - | 【推理优化】Chunked Prefill：8000 token prompt 一进，Decode 集体卡 1 秒？ | 4:27 | [link](https://www.bilibili.com/video/BV1jWgR6rEK9) |
| 2660 | - | - | 【大模型推理】Continuous Batching：同样 8 张卡，凭啥 vLLM 比 HF 快 24 倍？ | 4:22 | [link](https://www.bilibili.com/video/BV1jpgR6GEM1) |
| 2661 | - | - | 【大模型推理】Continuous Batching：同样 8 张卡，凭啥 vLLM 比 HF 快 24 倍？ | 4:22 | [link](https://www.bilibili.com/video/BV1ipgR6GE1K) |
| 2662 | - | - | 【LLM 推理】PD 分离部署：Mooncake / DistServe / Splitwise 三家方案讲透 | 3:27 | [link](https://www.bilibili.com/video/BV1J7gR61EgA) |
| 2663 | - | - | 【LLM 推理】Prefill vs Decode：一个拼算力一个拼带宽，推理框架的灵魂 | 4:03 | [link](https://www.bilibili.com/video/BV1JjgR6jEgH) |
| 2664 | - | - | 【LLM 推理优化】RadixAttention：SGLang 的招牌技术，一棵 Radix Tree 让吞吐提升 2-5× | 4:40 | [link](https://www.bilibili.com/video/BV1gYgR6vEas) |
| 2665 | - | - | 【推理优化】7B 在 H100 上理论极限 TPS 是多少？从 HBM 带宽推公式 | 4:47 | [link](https://www.bilibili.com/video/BV1e4gR6zEfR) |
| 2666 | - | - | 【LLM 推理】TTFT vs ITL：推理体验的两个 SLO，优化路径完全不同 | 4:55 | [link](https://www.bilibili.com/video/BV1VxgR6gEmj) |
| 2667 | - | - | 【面试高频】KV缓存驱逐：H2O与SnapKV，95%的KV都在陪跑 | 3:26 | [link](https://www.bilibili.com/video/BV1Liua63EZG) |
| 2668 | - | - | 【面试进阶】Lookahead Decoding：把大模型解码看成解方程，雅可比并行无损加速 | 3:31 | [link](https://www.bilibili.com/video/BV1Reua6rEkb) |
| 2669 | - | - | 【面试高频】美杜莎解码：多解码头+树注意力，一次前向验证一整棵候选树 | 3:10 | [link](https://www.bilibili.com/video/BV1Vzua6uEKE) |
| 2670 | - | - | 【面试高频】DeepSeek V3 招牌 MTP 多 token 预测全解：训练当辅助任务、推理当投机解码加速器 | 3:38 | [link](https://www.bilibili.com/video/BV1o8ua65EdB) |
| 2671 | - | - | 【面试高频】自投机解码：不加显存，大模型推理怎么白捡两倍加速？ | 3:18 | [link](https://www.bilibili.com/video/BV1V6ua6BEnX) |
| 2672 | - | - | 【Agent 必修】约束解码怎么保证模型只吐合法 JSON？FSM/PDA 与 logit 屏蔽详解 | 2:40 | [link](https://www.bilibili.com/video/BV1bC826sEMX) |
| 2673 | - | - | 【推理必修】温度、Top-K、Top-P 的区别在哪里？兼谈贪心与束搜索 | 3:08 | [link](https://www.bilibili.com/video/BV1co8261ERi) |
| 2674 | - | - | 【推理调参】温度、Top-P、Top-K 该按什么顺序调？为什么不能同时拉满 | 3:51 | [link](https://www.bilibili.com/video/BV1Ew8m6GEeG) |
| 2675 | - | - | 【推理优化】KV Cache 为什么只缓存 K 和 V，从不缓存 Q？注意力的根本不对称 | 3:44 | [link](https://www.bilibili.com/video/BV1JL826CEQK) |
| 2676 | - | - | 【推理加速】Medusa 多解码头讲透：一次预测 k 个 token，无需草稿模型的内嵌方案 | 4:03 | [link](https://www.bilibili.com/video/BV1j4826KEUb) |
| 2677 | - | - | 【推理调参】存在惩罚和频率惩罚的区别在哪里？两个治复读旋钮讲透 | 3:37 | [link](https://www.bilibili.com/video/BV1e8826PEYT) |
| 2678 | - | - | 【推理架构】Prefill 与 Decode 为什么差 140 倍？PD 分离架构的由来 | 3:37 | [link](https://www.bilibili.com/video/BV1Xj8S6zEe1) |
| 2679 | - | - | 【推理踩坑】训练 right padding、推理 left padding：搞混就是 silent bug | 1:51 | [link](https://www.bilibili.com/video/BV1cubL6WEQi) |
| 2680 | - | - | 【面试必考】RoPE位置编码到底是什么？从0手撕Qwen3源码，代码和公式竟然对不上!? | 4:26 | [link](https://www.bilibili.com/video/BV1gLTx6CEHx) |
| 2681 | - | - | 【手撕代码】Multi-Head Attention 多头注意力怎么写（接上期自注意力） | 3:46 | [link](https://www.bilibili.com/video/BV1imM36EETx) |
| 2682 | - | - | 【面试高频】Softmax 前为什么要除以根号 d？含完整数学推导 | 2:39 | [link](https://www.bilibili.com/video/BV1cJNA6REKc) |
| 2683 | - | - | 【面试高频】Encoder 和 Decoder 中的 Mask 有什么不同？两层掩码一次讲透 | 2:57 | [link](https://www.bilibili.com/video/BV1cENA6xEtb) |
| 2684 | - | - | 【面试高频】DeepSeek NSA 原生稀疏注意力：压缩+选择+滑窗，长文本解码快 11 倍还反超全注意力 | 3:58 | [link](https://www.bilibili.com/video/BV1YKN36iEBs) |
| 2685 | - | - | 【面试高频】YaRN 长度外推：RoPE 高频外推低频内插 + 注意力温度，4k→128k 几乎零成本 | 3:42 | [link](https://www.bilibili.com/video/BV1RNN36TEva) |
| 2686 | - | - | 【面试高频】DCA 双块注意力：块内/块间/相邻块 + 位置重映射封顶，零训练扩到百万上下文 | 3:29 | [link](https://www.bilibili.com/video/BV1zdNg6VEsk) |
| 2687 | - | - | 【面试高频】DeepSeek DSA 稀疏注意力：闪电索引器选 top-2048，真正省的是访存而非 FLOPs | 3:37 | [link](https://www.bilibili.com/video/BV1LFN366ER5) |
| 2688 | - | - | 【面试高频】门控注意力：SDPA 输出后加 Sigmoid 门，强稀疏+破低秩+去 attention-sink，只多 1% 参数 | 3:58 | [link](https://www.bilibili.com/video/BV1jgNS67EsS) |
| 2689 | - | - | 【面试高频】注意力为什么是 O(n²)？n×n 矩阵、显存爆炸与上下文长度的真相 | 3:25 | [link](https://www.bilibili.com/video/BV16VKj6FEA8) |
| 2690 | - | - | 【手撕代码】softmax / safe softmax / online softmax：从会溢出到一遍算完（FlashAttention 核心） | 3:40 | [link](https://www.bilibili.com/video/BV1ETKW67EXG) |
| 2691 | - | - | 【RoPE 之后必问】长度外推：训短推长为什么崩，ALiBi/PI/NTK/YaRN 方法全景 | 3:13 | [link](https://www.bilibili.com/video/BV13pKW6TECw) |
| 2692 | - | - | 【长文本扩展】位置插值 PI → NTK-aware → YaRN：怎么把 32K 免训练扩到 128K | 3:47 | [link](https://www.bilibili.com/video/BV1uxKW6NE7B) |
| 2693 | - | - | 【面试综述题】高效 Transformer 四大流派：稀疏、低秩、核化、可逆，一张图看懂 | 3:26 | [link](https://www.bilibili.com/video/BV15jKW63E8e) |
| 2694 | - | - | 【线性注意力】Linformer & Performer：低秩投影、核化+结合律，O(n²) 降到 O(n) | 3:21 | [link](https://www.bilibili.com/video/BV1GJKW6uEEH) |
| 2695 | - | - | 【稀疏注意力】Longformer & BigBird：滑动窗口、全局、随机注意力，O(n²) 降到 O(n) | 3:31 | [link](https://www.bilibili.com/video/BV19wK467EJE) |
| 2696 | - | - | 【手撕代码】self-attention 自注意力：一个公式讲透 Transformer 的心脏 | 3:24 | [link](https://www.bilibili.com/video/BV1d7gD6FEUe) |
| 2697 | - | - | 【面试高频】MQA 和 GQA：把 KV 头砍到 8 组为什么效果不掉？｜注意力演化 MHA→MQA→GQA→MLA | 3:22 | [link](https://www.bilibili.com/video/BV1tiKx6KE8v) |
| 2698 | - | - | 【手撕代码】RoPE 旋转位置编码：为什么点积只看相对距离？一个视频讲透 | 3:22 | [link](https://www.bilibili.com/video/BV1gigR6YEiz) |
| 2699 | - | - | 【大模型数值稳定性】Safe Softmax：一行 exp(100) 让模型崩溃，FlashAttention 的数学基石 | 4:14 | [link](https://www.bilibili.com/video/BV1bigR6YEpq) |
| 2700 | - | - | 【位置编码】ALiBi 注意力线性偏置：不存位置向量，反而比 RoPE 外推更好？ | 4:05 | [link](https://www.bilibili.com/video/BV1zW3d6WE9z) |
| 2701 | - | - | 【面试高频】删掉开头几个 token 大模型当场崩盘？一图看透 Attention Sink 与 StreamingLLM | 2:55 | [link](https://www.bilibili.com/video/BV1youa6dEug) |
| 2702 | - | - | 【面试高频】M-RoPE 多模态位置编码全解：一套 RoPE 如何通吃文字图片视频 | 4:11 | [link](https://www.bilibili.com/video/BV1Xzua6MEe2) |
| 2703 | - | - | 【面试高频】滑动窗口注意力一次讲透：平方级降到线性，小窗口为何能看穿13万token | 3:36 | [link](https://www.bilibili.com/video/BV1D1ua6PErD) |
| 2704 | - | - | 【NeurIPS 2025 最佳论文】Gated Attention：用 head 级 sigmoid 门改进注意力的线性聚合与 attention sink | 2:56 | [link](https://www.bilibili.com/video/BV1cd826jEGT) |
| 2705 | - | - | 【线性注意力】Linear Attention 讲透：核函数替代 softmax，O(n²) 降到 O(n) | 4:57 | [link](https://www.bilibili.com/video/BV1JE826rEVe) |
| 2706 | - | - | 【长文本】LongRoPE 讲透：把 4K 上下文扩到 2048K，非均匀插值 vs 均匀插值 | 4:23 | [link](https://www.bilibili.com/video/BV13e826hE9X) |
| 2707 | - | - | 【长上下文】Lost in the Middle 详解：答案放中间为什么就找不到了？兼谈 RAG 重排 | 3:28 | [link](https://www.bilibili.com/video/BV1hi826FEwT) |
| 2708 | - | - | 【大模型推理】StreamingLLM 讲透：保留 4 个 sink token 让模型记住无限长对话 | 3:31 | [link](https://www.bilibili.com/video/BV1Rd846yETR) |
| 2709 | - | - | 【长文本】attention sink 详解：成因、后果与 StreamingLLM 的解法 | 2:19 | [link](https://www.bilibili.com/video/BV1Tg8t6NE6U) |
| 2710 | - | - | 【长文本】4K 扩到 128K：PI、NTK-aware、YaRN 三种外推方法与分阶段训练 | 3:04 | [link](https://www.bilibili.com/video/BV1JjbL6UEPF) |
| 2711 | - | - | 【面试高频】BM25 相比 TF-IDF 做了什么改进？非线性饱和 + 长度归一化全解析 | 3:09 | [link](https://www.bilibili.com/video/BV1uGMt67Eig) |
| 2712 | - | - | 【RAG 地基】向量数据库索引 HNSW / IVF-PQ：多层图导航、聚类分桶、乘积量化 | 4:05 | [link](https://www.bilibili.com/video/BV1EQKW67EgT) |
| 2713 | - | - | 【RAG】HyDE 讲透：先让 LLM"瞎编"答案，再用它去检索真实文档 | 3:43 | [link](https://www.bilibili.com/video/BV1vQ3R6jEds) |
| 2714 | - | - | 【面试高频】CRAG 纠错式检索增强：给 RAG 加一道质检，三档纠错让大模型不再胡说 | 3:29 | [link](https://www.bilibili.com/video/BV1v5uY65EXS) |
| 2715 | - | - | 【面试高频】GraphRAG 原理拆解：先建图谱再分社区，RAG 终于能答全局问题了 | 3:16 | [link](https://www.bilibili.com/video/BV1zuuY6mEyK) |
| 2716 | - | - | 【面试高频】Late Chunking：调换切块和编码顺序，RAG检索质量的零成本提升 | 3:23 | [link](https://www.bilibili.com/video/BV1Liua63ER5) |
| 2717 | - | - | 【面试高频】Self-RAG 四种反思 token 全拆解：按需检索 + 批判资料 + 拦截幻觉 | 3:18 | [link](https://www.bilibili.com/video/BV1MSua6aEi6) |
| 2718 | - | - | 【RAG 必修】余弦相似度的维度灾难：为什么检索结果全挤在 0.9 附近 | 3:22 | [link](https://www.bilibili.com/video/BV1Sr826dExM) |
| 2719 | - | - | 【RAG 实操】检索器与生成器的微调 pipeline：对比学习、上下文利用与联合训练 | 1:45 | [link](https://www.bilibili.com/video/BV1ZT8S61E3b) |
| 2720 | - | - | 【RAG 实操】embedding 模型微调：对比学习、InfoNCE 与难负样本挖掘 | 2:05 | [link](https://www.bilibili.com/video/BV1WY8468EbL) |
| 2721 | - | - | 我Vibe Coding做的游戏，上架Steam了【B站AI创造公开赛】 | 11:34 | [link](https://www.bilibili.com/video/BV1MPMd64EiD) |
| 2722 | - | - | 《群侠传：幸存者》47分钟完整实机演示+开发者全程解说【B站AI创造公开赛】 | 47:55 | [link](https://www.bilibili.com/video/BV1S9uw6jE12) |
| 2723 | - | - | 《群侠传：幸存者》开场CG：幸而存生，何处是江湖？ | 1:44 | [link](https://www.bilibili.com/video/BV1j1uB6bEYZ) |
| 2724 | - | - | 上架三周，好评如潮，谢谢你玩我用AI做的游戏。 | 7:02 | [link](https://www.bilibili.com/video/BV1eCbA6rEZV) |
| 2725 | - | - | 【2025最新版】B站第一套系统的AI绘画课！零基础学会Stable Diffusion，这绝对是你看过的最容易上手的AI绘画教程 / SD WebUI系列课 | 18:15 | [link](https://www.bilibili.com/video/BV1VXYszZEvD) |
| 2726 | - | - | 从零开始认识SD模型体系：版本、功能、风格和获取渠道——如何选择合适的AI绘图模型？｜AI绘画+SD WebUI零基础入门系列教程（2025最新版） | 22:45 | [link](https://www.bilibili.com/video/BV1YdYszoEcj) |
| 2727 | - | - | Stable Diffusion提示词全方位解析：两大书写逻辑+两个绝妙技巧，小白也能快速学会写Prompt！｜AI绘画+SD WebUI零基础入门系列教程 | 24:07 | [link](https://www.bilibili.com/video/BV15RYszbEWd) |
| 2728 | - | - | 一个视频，理清Stable Diffusion所有参数的调节方式，自由掌控出图效果！｜AI绘画+SD WebUI零基础入门系列教程（2025最新版） | 15:57 | [link](https://www.bilibili.com/video/BV1B1YszeEaW) |
| 2729 | - | - | 一键“复刻”世界名画！Stable Diffusion图生图技巧详细解析｜AI绘画+SD WebUI零基础入门系列教程（2025最新版） | 10:04 | [link](https://www.bilibili.com/video/BV1qUYszaEKd) |
| 2730 | - | - | 拒绝低质量出图！提高AI绘画分辨率，就靠高分辨率修复了！/ SD WebUI高清修复优化细节无损放大教程 · AI绘图零基础入门系列教程（2025最新版） | 13:35 | [link](https://www.bilibili.com/video/BV1T7eLzdETo) |
| 2731 | - | - | 低显存也能跑高清大图！Stable Diffusion放大脚本+附加功能算法放大教程，轻松输出2K级分辨率！ AI绘画零基础入门系列教程（2025最新版） | 12:16 | [link](https://www.bilibili.com/video/BV1MweEzeEa4) |
| 2732 | - | - | AI绘画的救星！定向修改画面，手把手教你玩转SD局部重绘！ Stable Diffusion WebUI重绘功能详解 · AI绘画零基础入门系列教程（2025最 | 18:32 | [link](https://www.bilibili.com/video/BV1CGeEzdEP3) |
| 2733 | - | - | 一个视频，讲明白AI绘画里的2种附加网络模型！LoRA、Embedding分别是什么？怎么用？Stable Diffusion WebUI零基础入门系列教程 | 10:17 | [link](https://www.bilibili.com/video/BV1gnaEzeEiU) |
| 2734 | - | - | Embedding模型的5种用法，懂了才是真高手！Stable Diffusion附加网络模型解析 · AI绘画零基础入门系列教程 | 12:39 | [link](https://www.bilibili.com/video/BV1mxaEzFEWp) |
| 2735 | - | - | LoRA模型的4大分类与实用姿势，一次性讲明白！Stable Diffusion附加网络模型解析 · AI绘画零基础入门系列教程 | 19:08 | [link](https://www.bilibili.com/video/BV1UMaHzuEmy) |
| 2736 | - | - | 一个视频搞定10大Stable Diffusion插件：提示词翻译反推+放大修复+抠图重绘！SD WebUI扩展插件专题 · AI绘画零基础入门教程 | 57:44 | [link](https://www.bilibili.com/video/BV1D2pEzVENY) |
| 2737 | - | - | 一口气了解10种ControlNet！原理+应用，全方位解析Stable Diffusion控制网！SD WebUI扩展插件专题 · AI绘画零基础入门教程 | 50:18 | [link](https://www.bilibili.com/video/BV1pwpJzAEr8) |
| 2738 | - | - | ComfyUI全球爆红，AI绘画进入“工作流时代”？做最好懂的Comfy UI入门教程：Stable Diffusion专业节点式界面新手教学 | 23:36 | [link](https://www.bilibili.com/video/BV1D7421N7xN) |
| 2739 | - | - | 史诗级更新！ComfyUI“改头换面”，晚一秒更新都是浪费！全新界面、功能与海量体验优化，10分钟带你速览新版本所有操作技巧！（附整合包下载地址） | 11:44 | [link](https://www.bilibili.com/video/BV1X8xFeCERn) |
| 2740 | - | - | 让Comfy UI“无所不能”的秘密——自定义节点！ComfyUI零基础入门教程系列：自定义节点的安装与使用，用ComfyUI Manager一键安装缺失工作流 | 18:49 | [link](https://www.bilibili.com/video/BV1pZ421b7t7) |
| 2741 | - | - | ComfyUI“不好用”？这期视频，帮你找到最正确的入门姿势！全面掌握高清修复+重绘+LoRA+ControlNet，无缝丝滑上手SD Comfy UI教程 | 37:09 | [link](https://www.bilibili.com/video/BV1ab42187er) |
| 2742 | - | - | 小白也能听懂的ComfyUI工作流搭建教程！节点连线整理技巧+复杂工作流解构 / AI绘画和SD应用落地的最佳载体！从思路到实操，一口气讲明白！ | 38:03 | [link](https://www.bilibili.com/video/BV19f421q7EU) |
| 2743 | - | - | 太爽了！AI绘画全面进化：懂中文、会做中文设计，还开源免费！Qwen Image+Edit模型零基础教程，一个视频讲清楚全部应用 / 附Comfy UI工作流 | 8:34 | [link](https://www.bilibili.com/video/BV11SabzWEUZ) |
| 2744 | - | - | 一口气了解FLUX.1：AI生图的“新王”，凭什么震惊世界？FLUX模型使用教程，基本用法到进阶应用，一网打尽！（含SD Forge与ComfyUI整合包） | 20:45 | [link](https://www.bilibili.com/video/BV1UytNexEUk) |
| 2745 | - | - | 取代PS，颠覆AI绘画的新神器？FLUX Kontext零基础上手教程：一句话搞定图像编辑！无缝修图、改文字、换背景 / 含ComfyUI工作流 | 19:27 | [link](https://www.bilibili.com/video/BV1vYKVzfEYB) |
| 2746 | - | - | 开源+免费！这个AI彻底改变了美工和设计！FLUX Kontext Dev本地安装与使用教程：最强一致性图像编辑模型！ / 含模型下载与ComfyUI工作流 | 10:11 | [link](https://www.bilibili.com/video/BV1P8KyzAEQ6) |
| 2747 | - | - | 关于Stable Diffusion 3.5，这个视频有你需要知道的一切：免费可商用，和Flux比谁强？ / SD3.5使用教程，含ComfyUI工作流与整合包 | 18:44 | [link](https://www.bilibili.com/video/BV1XCmyYME4c) |
| 2748 | - | - | 8倍加速，低配福音！笔记本跑出“4090级”速度？AI绘图门槛大幅降低，ComfyUI Nunchaku节点详解，四位量化的FLUX模型究竟有多快？/ 含工作流 | 12:37 | [link](https://www.bilibili.com/video/BV16WKwzTExU) |
| 2749 | - | - | 一句话修出创意大片，摄影界的“ChatGPT”有多强？零基础小白也能玩的AI摄影生成器，超能画布入门教程，AI绘画应用实践 | 13:11 | [link](https://www.bilibili.com/video/BV1xC411H7NH) |
| 2750 | - | - | 重磅黑科技！让照片“开口说话”，这项AI技术终于可以用了！阿里EMO正式开放，一键同步音频表情、眼神、嘴型，还能唱歌、RAP？新一代AI“数字人”使用教程 | 3:04 | [link](https://www.bilibili.com/video/BV1AF4m1A7kX) |
| 2751 | - | - | 可能是全世界最会做设计的AI！3秒一张海报，文案全自动排版，还能做Logo和UI！Ideogram2.0使用教程：最强平面设计大模型，连FLUX都“甘拜下风”！ | 17:23 | [link](https://www.bilibili.com/video/BV1De2uYeEtK) |
| 2752 | - | - | 如何将ComfyUI工作流变成月入$1000的AI图像“App”（零代码）/ ShellAgent入门教程 · AI Agent Bot手把手搭建教学 | 22:54 | [link](https://www.bilibili.com/video/BV16qQRYoE1r) |
| 2753 | - | - | 用嘴改图的AI神器！效率秒杀Photoshop，“开源版”GPT4o来了？ICEdit实测与教程：通过FLUX Fill实现定向编辑 / 含ComfyUI工作流 | 8:55 | [link](https://www.bilibili.com/video/BV1bNEvzrEn1) |
| 2754 | - | - | 二次元角色“穿越”现实世界，5种整活玩法，这个AI太强了！Vidu Q1参考生视频教程：AI动画/视频生成如何保证人物角色一致性？ | 5:02 | [link](https://www.bilibili.com/video/BV1vv32zNERc) |
| 2755 | - | - | 一句话搞定全套海报+Logo全案+电商合成图！星流Agent全方位使用教程 / Lovart“中文版”开放使用！无需邀请码！ | 19:33 | [link](https://www.bilibili.com/video/BV1Eb8XzuEqC) |
| 2756 | - | - | 0代码开发AI应用，一句话生成完整App！ShellAgent 2.0使用教程：全球首个“Text 2 App”工具，靠自然语言做完全套开发工作？ | 5:51 | [link](https://www.bilibili.com/video/BV1yNt3zdEHu) |
| 2757 | - | - | 0 基础 22 分钟速通大模型应用：无痛学会DeepSeek+ChatGPT+一切AI对话软件，我为你总结了这四大“必备场景”—— | 22:31 | [link](https://www.bilibili.com/video/BV1J5TfzYEuk) |
| 2758 | - | - | 拳打PS Beta，SD Web UI最强“替代品”，Invoke AI竟然这么好用！开源免费可商用，内附安装教程与基本操作指南！/ AI绘画入门教程 | 16:22 | [link](https://www.bilibili.com/video/BV1xc411M7hp) |
| 2759 | - | - | 超详细云端部署Stable Diffusion教程！100%还原本地操作，免费试用3个月，自由切换模型、扩展，阿里云的函数计算太香了！/ 在线安装Web UI | 19:19 | [link](https://www.bilibili.com/video/BV19u411x7Bk) |
| 2760 | - | - | 一口气实测SD+FLUX+DeepSeek，RTX 50系显卡AI绘图/视频/LLM性能全方位测试！—— 5070Ti&70&80&5090D AIGC速度测评 | 15:00 | [link](https://www.bilibili.com/video/BV1av9oY9Ez2) |
| 2761 | - | - | 1秒6张图，比4090快1.5倍？5090 D & 5080 AI画图速度测评 /  RTX 50系显卡上手体验 / Stable Diffusion/FLUX | 10:35 | [link](https://www.bilibili.com/video/BV1vCFLefE94) |
| 2762 | - | - | 首个40系SUPER显卡“AI评测”：速度提升50%？生成视频也很快！Stable Diffusion 绘画 & SVD动画性能实测 70S/70TiS/80S | 10:51 | [link](https://www.bilibili.com/video/BV1Yx4y1Z7xk) |
| 2763 | - | - | AI绘画的“显存杀手”？5块全新40系显卡怒测“最强开源大模型”——Stable Diffusion XL效率测试&使用技巧，SDXL低显存Web UI优化指南 | 14:57 | [link](https://www.bilibili.com/video/BV1MG411R7XQ) |
| 2764 | - | - | 显卡速度翻3倍，AI绘画进入“秒速时代”？Stable Diffusion究极加速插件，NVIDIA TensorRT扩展安装与使用全方位教程 | 16:11 | [link](https://www.bilibili.com/video/BV1Lv411F7Rr) |
| 2765 | - | - | 国产显卡到底能不能跑AI？摩尔线程MTT S4000 GPU“云”实测，ComfyUI / SD / 混元3D都能用！ | 7:55 | [link](https://www.bilibili.com/video/BV11buJzqEm9) |
| 2766 | - | - | 大概是站内第一个SORA系统实操教程：SORA全功能讲解+分析！【OpenAI发布全新视频生成模型】 | 14:15 | [link](https://www.bilibili.com/video/BV1HZqkYREmx) |
| 2767 | - | - | 一口气入门AI视频：3大主流路径与30个热门工具，全面分析AI做视频的各种技巧！/  AI视频生成入门教程&软件盘点：图生视频、转绘、二创拥抱整活、数字人 … | 12:58 | [link](https://www.bilibili.com/video/BV1mJyTYEEPT) |
| 2768 | - | - | 一线艺术家的AI短片工作流揭秘：“大佬”们这样用AI做视频！如何制作一个“商业级”的AI生成品牌宣传片？/ 七彩虹iGame Ultra Family主机 | 14:15 | [link](https://www.bilibili.com/video/BV1F8zBYLEKp) |
| 2769 | - | - | 最强免费AI视频模型，颠覆后期剪辑素材行业！一张图生成视频空镜，Stable Video Diffusion（SVD）零基础上手使用教学 ComfyUI工作流 | 16:14 | [link](https://www.bilibili.com/video/BV1iZ421t7Ax) |
| 2770 | - | - | AI视频时代的“开源先驱”：Sora来之前，你可以先掌握这些——AnimateDiff动画插件全方位教学，制作丝滑流畅动图！Stable Diffusion应用 | 18:11 | [link](https://www.bilibili.com/video/BV1zS421A7PG) |
| 2771 | - | - | Deforum AI视频生成入门教程：打造过亿播放的爆款短视频，20分钟学会Stable Diffusion“瞬息全宇宙”！AI空间运镜无限穿越动画生成 | 19:51 | [link](https://www.bilibili.com/video/BV1Fy421v7SB) |
| 2772 | - | - | 15分钟入门AI动画！Mov2Mov零基础教学，用Stable Diffusion生成酷炫逐帧重绘动画短视频，开启低成本动画时代 / 扩展插件教程 | 16:48 | [link](https://www.bilibili.com/video/BV1Su411b7Nm) |
| 2773 | - | - | 10倍效率，打造无闪烁丝滑AI动画！EbSynth插件全流程操作解析与原理分析，超智能的“补帧”动画制作揭秘！/ Stable Diffusion扩展插件教程 | 18:35 | [link](https://www.bilibili.com/video/BV1uX4y1H7U3) |
| 2774 | - | - | 可能是目前最适合小白的AI视频工具：免费、不限次数，一键扩写脚本，还能自动“配音”？阿里通义万相模型测评 / AI做视频的软件工具入门教程 | 6:38 | [link](https://www.bilibili.com/video/BV1M9tnevEBh) |
| 2775 | - | - | 2天用AI做完一个“商业级"广告？5090D首发宣传片“AI版”工作流分享！ / AIGC短片幕后分享 & AI生成视频教程 / 华硕RTX 5090D显卡 | 10:24 | [link](https://www.bilibili.com/video/BV1RkfEYAEyj) |
| 2776 | - | - | 全站首个【教程】工作流分享！百万播放的系列课是如何诞生的？策划剪辑视频后期全流程揭秘，学AI绘画一定看过这套Stable Diffusion入门课—— | 15:33 | [link](https://www.bilibili.com/video/BV14X4y1p7A9) |
| 2777 | - | - | 8年设计师，聊聊AI是怎么把我“取代”的：创意工作者如何面对AI浪潮？经历分享与职业建议 / ProArt创艺国度校园行分享记录 | 10:43 | [link](https://www.bilibili.com/video/BV1TR1aYxEYM) |
| 2778 | - | - | 我一臭打游戏的，AI革命和我有啥关系？ | 13:42 | [link](https://www.bilibili.com/video/BV1Ai421a7ns) |
| 2779 | - | - | 全 世 界 都 在 学 A I 绘 画 —— | 5:57 | [link](https://www.bilibili.com/video/BV16u411j7u3) |
| 2780 | - | - | 我在WAIC见到了马斯克和Stable Diffusion的创始人！聊大模型、AI应用的未来、AI焦虑？探秘2023世界人工智能大会—— | 7:17 | [link](https://www.bilibili.com/video/BV1rh4y1f7XJ) |
| 2781 | - | - | B站第一套系统的AI绘画课！零基础学会Stable Diffusion，这绝对是你看过的最容易上手的AI绘画教程 / SD WebUI 保姆级攻略 | 17:53 | [link](https://www.bilibili.com/video/BV1As4y127HW) |
| 2782 | - | - | 20分钟搞懂Prompt与参数设置，你的AI绘画“咒语”学明白了吗？ / 零基础入门Stable Diffusion·保姆级新手教程 / Prompt关键词教学 | 19:02 | [link](https://www.bilibili.com/video/BV12X4y1r7QB) |
| 2783 | - | - | 打破次元壁！用AI“重绘”照片和CG，效果惊艳到我了—— / Stable Diffusion图生图零基础入门·保姆级新手教程 / AI漫画特效&赛博Coser | 11:53 | [link](https://www.bilibili.com/video/BV1Lh411u7vs) |
| 2784 | - | - | AI绘画模型新手包！“画风”自由切换，有哪些你不知道的模型使用技巧？ / 零基础入门Stable Diffusion的保姆级新手教程 / SD模型下载方式与推荐 | 17:06 | [link](https://www.bilibili.com/video/BV1Us4y117Rg) |
| 2785 | - | - | 拒绝低质量出图！3种快速提高AI绘画分辨率的方式，十分钟讲完！/ StableDiffusion WebUI 保姆级攻略·高清修复优化细节无损放大教程 | 11:57 | [link](https://www.bilibili.com/video/BV11m4y12727) |
| 2786 | - | - | Embeddings是啥？怎么用？三大AI绘画高级模型概念解析，懂了才是真高手！/ StableDiffusion保姆级教程·模型原理解析及应用 | 13:50 | [link](https://www.bilibili.com/video/BV1th4y1p7fH) |
| 2787 | - | - | AI绘画的救星！定向修手修脸，手把手教你玩转局部重绘！/ StableDiffusion WebUI 保姆级教程·inPainting功能详解·含PS操作 | 15:23 | [link](https://www.bilibili.com/video/BV1uL411e7Uk) |
| 2788 | - | - | 新手入门：如何在SD里安装扩展插件？ / StableDiffusion教程 拓展（Extensions）的安装与应用 | 3:37 | [link](https://www.bilibili.com/video/BV1hz4y1a76M) |
| 2789 | - | - | LoRA从原理到实践，零基础打造赛博Coser、一键更换服饰，无所不能！5大应用方向剖析 & 保姆级讲解！Stable Diffusion AI绘画 | 24:28 | [link](https://www.bilibili.com/video/BV1nL411B7XT) |
| 2790 | - | - | 30分钟零基础掌握ControlNet！绝对是你看过最好懂的控制网原理分析 / 基本操作、插件安装与5大模型应用 · Stable Diffusion教程 | 30:01 | [link](https://www.bilibili.com/video/BV1Ds4y1e7ZB) |
| 2791 | - | - | Multi Diffusion + Tiled VAE + ControlNet Tile模型，低显存打造AI绘画超高清6K分辨率体验！SD扩展插件教程 | 16:21 | [link](https://www.bilibili.com/video/BV1Su4y1d7Dp) |
| 2792 | - | - | “牛逼”的教程来了！一次学会AI二维码+艺术字+光影光效+创意Logo生成，绝对是B站最详细的Stable Diffusion特效设计流程教学！AI绘画进阶应用 | 16:56 | [link](https://www.bilibili.com/video/BV1gX4y1J7ei) |
| 2793 | - | - | AI打开新世界大门！立绘一键“真人化”，还能换皮肤！ControlNet LineArt 线稿上色+换装换背景，Stable Diffusion系统教程 | 15:41 | [link](https://www.bilibili.com/video/BV1oB4y1R7Ms) |
| 2794 | - | - | AI再进化，这次竟然学会摄影了！一秒生成胶片风、拍立得，还能智能“修脸”！Stable Diffusion AI绘画真实系人像模型+LoRA推荐 | 12:42 | [link](https://www.bilibili.com/video/BV1DP41167bZ) |
| 2795 | - | - | 我用AI修复了50年前的亚运会老照片！Stable Diffusion智能上色+高清修复教程！StableSR + ControlNetTile&Recolor | 20:30 | [link](https://www.bilibili.com/video/BV1mm4y1575y) |
| 2796 | - | - | 一秒打通PS+SD！AI功能免费“平替”，还支持ControlNet？Auto Stable Diffusion Photoshop插件教程，释放轻薄本AI潜力 | 16:50 | [link](https://www.bilibili.com/video/BV1Zj411h7od) |
| 2797 | - | - | AI一键调光布景，这个开源神器改变了摄影和设计！IC-Light教程，全自动融图调色，附一键包+ComfyUI工作流+SD Forge插件 / 华硕天选Air | 14:32 | [link](https://www.bilibili.com/video/BV1Yy411e7y1) |
| 2798 | - | - | 5秒生成一张分图层AI素材，“抠图”已成过去式？设计师的免费PNG“素材库”！ControlNet作者新作，Layer Diffusion生成免抠AI绘图素材！ | 15:56 | [link](https://www.bilibili.com/video/BV1Xq421F7Ny) |
| 2799 | - | - | 8张照片训练个人LoRA，一分钱不花打造“AI写真”？Stable Diffusion EasyPhoto扩展插件教程，轻松训练AI绘画人脸模型 | 18:49 | [link](https://www.bilibili.com/video/BV1b8411k7fb) |
| 2800 | - | - | 靠AI开一家服装店？超详细AI衣服款式设计+“AI模特”换装教程 / Stable Diffusion商业落地实践&男女装电商应用，一秒生成“摄影级”产品图 | 21:00 | [link](https://www.bilibili.com/video/BV1994y1W7Tg) |
| 2801 | - | - | 一流模型！10个高手都在用的二次元插画绘画风大模型推荐，内附模型下载渠道与出图参数提示词关键词模版 / AI绘画 · StableDiffusion | 13:13 | [link](https://www.bilibili.com/video/BV1Us4y1M7x4) |
| 2802 | - | - | 关于SDXL 1.0，这个视频里有你想知道的全部 / 15分钟全面解读，AI绘画即将迎来“新时代”？Stable Diffusion XL大模型安装及使用教程 | 15:06 | [link](https://www.bilibili.com/video/BV1TM4y1p7RJ) |
| 2803 | - | - | 手稿变动画，AI生成3D贴图，艺术家手里的Stable Diffusion把我惊呆了！SD进阶工作流分享，强势辅助插画线稿上色+Blender建模！ | 11:58 | [link](https://www.bilibili.com/video/BV1ma4y1z7Cs) |
| 2804 | - | - | B站第一套系统的AI绘画模型训练课程！零基础入门“炼丹”，制作属于你的SD模型！模型微调（Dreambooth、LoRA、Embedding）原理分析教学 | 23:19 | [link](https://www.bilibili.com/video/BV1TK411v7Jw) |
| 2805 | - | - | 60分钟速通LORA训练！绝对是你看过最好懂的AI绘画模型训练教程！StableDiffusion超详细训练原理讲解+实操教学，LORA参数详解与训练集处理技巧 | 62:28 | [link](https://www.bilibili.com/video/BV16e411e7Zx) |
| 2806 | - | - | 照片发光了！超详细的PS光感设计教程：一个“发光”小技巧，让你的设计不再普通 / PS视觉合成教程，照片修图后期讲解！ | 16:47 | [link](https://www.bilibili.com/video/BV1tq4y1P7Nk) |
| 2807 | - | - | 无需3D建模，用PS制作一个梦幻宇宙星球，简单几步就能搞定 / Photoshop视觉合成教程系列 | 19:14 | [link](https://www.bilibili.com/video/BV1JL4y1W7At) |
| 2808 | - | - | 视觉效果拉满！这个PS教程，教你轻松设计“赛博朋克”的科幻光环效果！（适合海报设计/摄影后期修图）/ Photoshop视觉合成系列设计课 | 18:57 | [link](https://www.bilibili.com/video/BV1844y1a7ty) |
| 2809 | - | - | 用AI制作一个酷炫的三维文字环绕效果（科幻感光环合成补充教程） /  PS视觉合成系列 For 平面设计 & 摄影后期修图 By Nenly | 8:58 | [link](https://www.bilibili.com/video/BV1LR4y1W7Zm) |
| 2810 | - | - | 使用Photoshop，为你的照片添加闪亮的夜景光斑效果 / PS设计课：视觉合成系列教程（适用于海报设计、摄影后期修图等） | 10:25 | [link](https://www.bilibili.com/video/BV1hg411w7k3) |
| 2811 | - | - | 用PS设计梦幻的后期夜景光照效果（补充教程）/ PS设计课：视觉合成系列教程（适用于海报设计、摄影后期修图等） | 11:14 | [link](https://www.bilibili.com/video/BV1nq4y127LN) |
| 2812 | - | - | PS合成技巧：在高速公路上划船的“秘笈”！巧妙融合马路与水面—— / Photoshop视觉合成系列 | 3:13 | [link](https://www.bilibili.com/video/BV1Yr4y1J7MR) |
| 2813 | - | - | 如何利用PS制作漫画风人像手绘效果？ / 3分钟PS小技巧 | 3:17 | [link](https://www.bilibili.com/video/BV11V411n75u) |
| 2814 | - | - | 文字消失术！如何用PS制作酷炫的文字粒子消散效果？/ 设计案例教程 Daily Poster 海报设计第2期 | 15:20 | [link](https://www.bilibili.com/video/BV1wA411A7uN) |
| 2815 | - | - | 三步，用PS制作一个立体金属文字，十分钟一定能让你学会 / Photoshop文字设计教程 | 13:23 | [link](https://www.bilibili.com/video/BV113411i76R) |
| 2816 | - | - | 这么甜的文字设计，是我能用PS做出来的吗？不用怀疑，三步搞定一个“果冻文字”，你上你也行 / 字体效果设计系列，Photoshop教程，设计公开课 | 15:49 | [link](https://www.bilibili.com/video/BV1934y1S75B) |
| 2817 | - | - | 太酷炫了！用PS打造一个霓虹灯文字效果，这个教程15分钟一定能教会你 / Photoshop技巧教学，字效设计系列 & 视觉设计 | 17:23 | [link](https://www.bilibili.com/video/BV1bq4y1K79B) |
| 2818 | - | - | 全自动操作，三步实现“故障风”的PS文字效果，你能做到吗？（内附Photoshop源文件，可一键替换文字内容） | 17:21 | [link](https://www.bilibili.com/video/BV1n44y1t768) |
| 2819 | - | - | PS教程：制作一个可口又可爱的“曲奇饼干”文字效果，简单清晰，你也能学会 / Photoshop字效设计系列，平面海报设计 | 16:47 | [link](https://www.bilibili.com/video/BV1wq4y157zm) |
| 2820 | - | - | 用PS一键生成3D透视立体文字，十分钟教程，五分钟操作 / Photoshop字体效果设计系列 | 11:56 | [link](https://www.bilibili.com/video/BV1bR4y1t7Yn) |
| 2821 | - | - | 用PS制作一个炫彩油漆笔刷字，这是为你准备的详细教程—— / Photoshop字体效果设计系列 | 16:37 | [link](https://www.bilibili.com/video/BV1Aq4y1r7qb) |
| 2822 | - | - | PS教程：我的文字设计是用雪“堆”起来的，你的呢？这个“冰雪文字”，超适合你的圣诞海报设计 —— Photoshop字体效果设计课 | 15:05 | [link](https://www.bilibili.com/video/BV1iY411p75L) |
| 2823 | - | - | PS教程来了！超酷炫的迷幻流体渐变文字，10分钟教你学会搞定！潮到爆炸的“酸性”风，少不了这个设计—— / PS字体效果系列免费教程 | 12:01 | [link](https://www.bilibili.com/video/BV1GF411i77d) |
| 2824 | - | - | PS教程：三步打造潮到爆炸的酸性镀铬文字效果设计！适用于酷炫的海报、视觉设计 / Photoshop字体效果设计系列 By Nenly | 9:47 | [link](https://www.bilibili.com/video/BV1Yr4y1B7AP) |
| 2825 | - | - | 酸性热成像风格文字设计，用PS三步搞定 / Photoshop字体设计系列课 / 酸性潮流设计 / 适用于海报、视觉设计 | 4:49 | [link](https://www.bilibili.com/video/BV1k541127TE) |
| 2826 | - | - | 游戏秒变“8-Bit”像素风？这两个方法，你该学起来了！一期复古像素风PS视觉设计效果教程（适用于插画、摄影、后期） / Photoshop视觉设计课 | 12:41 | [link](https://www.bilibili.com/video/BV1Ve4y1X7CL) |
| 2827 | - | - | PS教程：设计三步变“燃”，从图层样式和混合模式开始 —— Photoshop字体效果设计系列课 / 适用于海报设计、特效制作 | 8:00 | [link](https://www.bilibili.com/video/BV19a411Y7pq) |
| 2828 | - | - | 【PS教程】你要的小清新，靠植物的神奇“穿插”来实现—— / Photoshop视觉设计系列 / 文艺风海报标题设计 | 7:43 | [link](https://www.bilibili.com/video/BV1B94y11764) |
| 2829 | - | - | 酷炫、高级的魔法烟雾效果，用PS两步轻松搞定 / Photoshop视觉设计系列 / 适用于海报主视觉 & 字体设计等 | 7:05 | [link](https://www.bilibili.com/video/BV1nN4y1j7QJ) |
| 2830 | - | - | 设计怎么“找素材”？适合新手的素材搜索“2步法”，高效收获对口的设计素材——（素材搜索教程，内附各类型素材网站推荐） | 5:59 | [link](https://www.bilibili.com/video/BV1Qq4y1h7YH) |
| 2831 | - | - | 第1课：新手上路，如何挑选适合自己的PS软件版本？ / Photoshop百科全书 · PS教程系列公开课 · 零基础入门学设计 | 3:46 | [link](https://www.bilibili.com/video/BV1xT4y1S7CK) |
| 2832 | - | - | 第2课：新手必看！如何获取最新版本的PS软件资源？（内附2022版安装包地址）/ Photoshop百科全书 · PS教程系列公开课 · 零基础入门学设计 | 2:35 | [link](https://www.bilibili.com/video/BV11q4y1479F) |
| 2833 | - | - | 一秒修复照片！移除人像、修补裂痕、去除污渍，PS自带的这四大“黑科技”工具，99%的人都没打开用过—— / Photoshop百科全书 · PS教程系列公开课 | 5:23 | [link](https://www.bilibili.com/video/BV1Xr4y1B7J6) |
| 2834 | - | - | 用PS，在云端与超级月亮共舞  /  Photoshop视觉合成流程拆解 · 第001期（三连过百出教程） | 2:25 | [link](https://www.bilibili.com/video/BV1sS4y1e78q) |
| 2835 | - | - | PS深度映射，打造酷炫的星空螺旋视觉效果 / Photoshop教程，设计过程快放 & 作品展示 | 0:43 | [link](https://www.bilibili.com/video/BV1ev411Y7dA) |
| 2836 | - | - | 如何用PS设计一个“饼干字”标题？展示一下操作流程 / Photoshop教学设计流程快放 | 1:01 | [link](https://www.bilibili.com/video/BV14A411K7ox) |
| 2837 | - | - | PS视觉合成效果教程：如何设计一只瓶中的鲸鱼？设计全过程展示—— | 1:02 | [link](https://www.bilibili.com/video/BV1ZX4y1G7D7) |
| 2838 | - | - | 用PS设计一张“月球表面”质感的海报，没有素材，自己动手做 / PS设计过程快放 & 作品展示 | 4:49 | [link](https://www.bilibili.com/video/BV1Mf4y167GS) |
| 2839 | - | - | PS置换滤镜设计人脸文字海报，超级有艺术感的设计手法！（全流程展示） | 0:54 | [link](https://www.bilibili.com/video/BV1Hy4y1a7eb) |
| 2840 | - | - | 如何用PS制作一个创意“传送门”？设计全过程来了 / Photoshop视觉合成教程 | 9:04 | [link](https://www.bilibili.com/video/BV1qA411M7Yi) |
| 2841 | - | - | 如何用PS制作一张酷炫的渐变Photoshop人像海报？模仿练习——视觉与版式设计 / Daily Poster | 10:00 | [link](https://www.bilibili.com/video/BV183411q7hp) |
| 2842 | - | - | 1986卫报广告：《视角》The Guardian's 1986 'Points of view' advert | 0:30 | [link](https://www.bilibili.com/video/BV1Er421L7ac) |
| 2843 | - | - | 判断英语权重的正确逻辑 | 5:49 | [link](https://www.bilibili.com/video/BV1MBao6xE3Q) |
| 2844 | - | - | 晶格玻尔兹曼方法LBM01-宏观，微观，介观 | 14:52 | [link](https://www.bilibili.com/video/BV192SDBoEnu) |
| 2845 | - | - | 晶格玻尔兹曼方法LBM02-连续介质流体力学复习 | 27:17 | [link](https://www.bilibili.com/video/BV1U9dJBVE3s) |
| 2846 | - | - | 晶格玻尔兹曼方法LBM03-玻尔兹曼方程 | 25:36 | [link](https://www.bilibili.com/video/BV1sGocBpEZJ) |
| 2847 | - | - | 晶格玻尔兹曼方法LBM04-分布函数的矩 | 16:08 | [link](https://www.bilibili.com/video/BV1DwRCBGE4H) |
| 2848 | - | - | 晶格玻尔兹曼方法LBM05-从玻尔兹曼方程推导宏观方程 | 30:17 | [link](https://www.bilibili.com/video/BV1HhR4BEETQ) |
| 2849 | - | - | 晶格玻尔兹曼方法LBM06-BGK近似，局部平衡分布函数 | 25:22 | [link](https://www.bilibili.com/video/BV1qsVF6AEbr) |
| 2850 | - | - | 晶格玻尔兹曼方法LBM07-局部平衡分布函数的矩 | 46:07 | [link](https://www.bilibili.com/video/BV1PFJH6pEmZ) |
| 2851 | - | - | 晶格玻尔兹曼方法08-从BE恢复NSE | 38:27 | [link](https://www.bilibili.com/video/BV1iP756mEdR) |
| 2852 | - | - | 特征值与特征向量01-基本知识复习 | 10:49 | [link](https://www.bilibili.com/video/BV1mKNTzFEmY) |
| 2853 | - | - | 行列式01-行列式计算1 | 14:20 | [link](https://www.bilibili.com/video/BV1W9c5ziERw) |
| 2854 | - | - | 线性映射01-基本知识复习与简单练习 | 12:11 | [link](https://www.bilibili.com/video/BV1Pui2B8EhV) |
| 2855 | - | - | 行空间01-寻找子空间的基1 | 18:16 | [link](https://www.bilibili.com/video/BV15kiuBGEas) |
| 2856 | - | - | 向量空间的基01-基本知识复习与简单练习 | 15:11 | [link](https://www.bilibili.com/video/BV1RQBUBxEMn) |
| 2857 | - | - | 向量空间01-基本知识复习 | 8:49 | [link](https://www.bilibili.com/video/BV1SPUSBCErf) |
| 2858 | - | - | 初等矩阵与可逆矩阵01-基本知识复习与简单练习 | 14:14 | [link](https://www.bilibili.com/video/BV14F1sBbEh4) |
| 2859 | - | - | 线性方程组01-基本知识复习 | 11:38 | [link](https://www.bilibili.com/video/BV1N7ymBpENU) |
| 2860 | - | - | 矩阵01-对称与反对称 | 17:05 | [link](https://www.bilibili.com/video/BV12JsqzhER1) |
| 2861 | - | - | 复数与多项式01-基本运算性质 | 21:21 | [link](https://www.bilibili.com/video/BV1TZ4BzGEQk) |
| 2862 | - | - | 域01-判断域1 | 36:18 | [link](https://www.bilibili.com/video/BV1e94JzwEgM) |
| 2863 | - | - | 【淅沥橙基础数学精品】线性代数A（已完结） | 1750:32 | [link](https://www.bilibili.com/video/BV1HB4gzHE9o) |
| 2864 | - | - | 数学分析一第1课-基本概念和简介 | 131:53 | [link](https://www.bilibili.com/video/BV1doPPzeEY5) |
| 2865 | - | - | 数学分析一第2课-数列的极限性质 | 119:55 | [link](https://www.bilibili.com/video/BV1qRwAzFEdm) |
| 2866 | - | - | 数学分析一第3课-数列审敛 | 175:28 | [link](https://www.bilibili.com/video/BV1BbA7zME5F) |
| 2867 | - | - | 数学分析一第4课-子数列 | 174:39 | [link](https://www.bilibili.com/video/BV1NaX8BtEgL) |
| 2868 | - | - | 数学分析一第5课-拓扑学简介，函数简介 | 180:55 | [link](https://www.bilibili.com/video/BV1CGS9BmEXD) |
| 2869 | - | - | 数学分析一第6课-函数的极限 | 175:19 | [link](https://www.bilibili.com/video/BV1sf5y6rEmM) |
| 2870 | - | - | 数学分析一第7课-连续函数 | 158:28 | [link](https://www.bilibili.com/video/BV1yhLw69Ese) |
| 2871 | - | - | 数学分析一第8课-导数 | 145:05 | [link](https://www.bilibili.com/video/BV1ZuEm6jEDR) |
| 2872 | - | - | 常微分方程ODE新版（一）：一阶方程 | 302:14 | [link](https://www.bilibili.com/video/BV1tCPpe2E7E) |
| 2873 | - | - | 常微分方程ODE练习一：一阶方程 | 216:13 | [link](https://www.bilibili.com/video/BV12qotY6E55) |
| 2874 | - | - | 常微分方程ODE02：n阶线性齐次方程的基本性质 | 101:54 | [link](https://www.bilibili.com/video/BV1hMRUYPEqA) |
| 2875 | - | - | 常微分方程ODE03: 降阶法 | 41:02 | [link](https://www.bilibili.com/video/BV11hdSYcEjF) |
| 2876 | - | - | 常微分方程ODE04：n阶线性常系数齐次方程 | 67:57 | [link](https://www.bilibili.com/video/BV1ni5EzrE7T) |
| 2877 | - | - | 常微分方程ODE05: n阶线性常系数非齐次方程的待定系数法 | 104:42 | [link](https://www.bilibili.com/video/BV1nrGkzBEmm) |
| 2878 | - | - | 常微分方程ODE06: 振子与共振 | 96:45 | [link](https://www.bilibili.com/video/BV1vqJez9Ehf) |
| 2879 | - | - | 常微分方程ODE07: Euler方程 | 53:43 | [link](https://www.bilibili.com/video/BV1hZj9zcEAy) |
| 2880 | - | - | 常微分方程ODE08: n阶线性非齐次方程：常数变易法 | 74:17 | [link](https://www.bilibili.com/video/BV1m6NxzUEMi) |
| 2881 | - | - | 常微分方程ODE09: 一阶线性方程组简介 | 71:11 | [link](https://www.bilibili.com/video/BV132gHzoEPx) |
| 2882 | - | - | 常微分方程ODE10: 求解一阶线性常系数方程组 | 129:01 | [link](https://www.bilibili.com/video/BV1MshAzQEBB) |
| 2883 | - | - | ODE11-求解一阶线性常系数方程组练习 | 57:35 | [link](https://www.bilibili.com/video/BV1fehhzEEZ6) |
| 2884 | - | - | ODE12-线性非齐次方程组 | 36:45 | [link](https://www.bilibili.com/video/BV1qyHnzbE6S) |
| 2885 | - | - | 傅里叶级数和积分变换（一）：傅里叶级数 | 519:50 | [link](https://www.bilibili.com/video/BV1Nm4y1F7eW) |
| 2886 | - | - | 傅里叶级数和积分变换（二）：傅里叶变换和拉普拉斯变换基础 | 482:26 | [link](https://www.bilibili.com/video/BV1bAqgYGENQ) |
| 2887 | - | - | 复变函数新编集版（已完结） | 939:53 | [link](https://www.bilibili.com/video/BV1P44y1873i) |
| 2888 | - | - | 多相流01-多相流简介和离散相基本性质 | 60:35 | [link](https://www.bilibili.com/video/BV1BS4y1A7Ej) |
| 2889 | - | - | 多相流02-相间耦合 | 53:08 | [link](https://www.bilibili.com/video/BV16r4y1J74N) |
| 2890 | - | - | 多相流03-相间耦合续 | 60:00 | [link](https://www.bilibili.com/video/BV1fB4y127xe) |
| 2891 | - | - | 多相流04-单颗粒方程 | 72:11 | [link](https://www.bilibili.com/video/BV1eY411w7R3) |
| 2892 | - | - | 多相流05-单颗粒能量守恒 | 46:00 | [link](https://www.bilibili.com/video/BV1fB4y1172k) |
| 2893 | - | - | 多相流06-质量耦合 | 49:02 | [link](https://www.bilibili.com/video/BV1ER4y1N7fK) |
| 2894 | - | - | 多相流07-曳力 | 73:33 | [link](https://www.bilibili.com/video/BV1WA4y1Q7A5) |
| 2895 | - | - | 多相流08-曳力影响因素 | 69:25 | [link](https://www.bilibili.com/video/BV1r3411N7KM) |
| 2896 | - | - | 多相流09-颗粒其他受力 | 75:37 | [link](https://www.bilibili.com/video/BV1ou411r7d2) |
| 2897 | - | - | 气液界面流01-表面张力1 | 18:52 | [link](https://www.bilibili.com/video/BV13B4y1W7gM) |
| 2898 | - | - | 气液界面流02-表面张力2 | 23:43 | [link](https://www.bilibili.com/video/BV1zr4y1M73A) |
| 2899 | - | - | 气液界面流03-界面描述1 | 25:35 | [link](https://www.bilibili.com/video/BV1nY4y1J7ba) |
| 2900 | - | - | 气液界面流04-界面描述2 | 35:56 | [link](https://www.bilibili.com/video/BV1CN41127Hy) |
| 2901 | - | - | 气液界面流05-流动方程1 | 18:03 | [link](https://www.bilibili.com/video/BV1Ax4y1Z7qP) |
| 2902 | - | - | 气液界面流06-流动方程2 | 21:41 | [link](https://www.bilibili.com/video/BV1NV41157G2) |
| 2903 | - | - | 多分散多相流1-简介，NDF | 56:20 | [link](https://www.bilibili.com/video/BV1vT4y1y7dj) |
| 2904 | - | - | 多分散多相流2-细颗粒的PBE | 40:15 | [link](https://www.bilibili.com/video/BV1GS4y157xy) |
| 2905 | - | - | 多分散多相流3-细颗粒的PBE（续），气固流的KE | 56:14 | [link](https://www.bilibili.com/video/BV1s34y1y7yj) |
| 2906 | - | - | 动力学01-向量 | 43:43 | [link](https://www.bilibili.com/video/BV1JZ4y1q7Ki) |
| 2907 | - | - | 动力学02-运动学基础，切法坐标 | 54:43 | [link](https://www.bilibili.com/video/BV1234y157mF) |
| 2908 | - | - | 动力学03-极坐标 | 52:32 | [link](https://www.bilibili.com/video/BV1qW4y1J7WC) |
| 2909 | - | - | 动力学04-移动旋转坐标系 | 42:16 | [link](https://www.bilibili.com/video/BV1Ch4y1M71j) |
| 2910 | - | - | 第二门计算机课-正课（完） | 748:34 | [link](https://www.bilibili.com/video/BV1RD4y1z7dy) |
| 2911 | - | - | 第二门计算机课之UNIX | 114:15 | [link](https://www.bilibili.com/video/BV15N411F7T4) |
| 2912 | - | - | 第二门计算机课之C语言（上） | 104:43 | [link](https://www.bilibili.com/video/BV1Mk4y1t7BD) |
| 2913 | - | - | 第二门计算机课之C语言（下） | 138:40 | [link](https://www.bilibili.com/video/BV1a84y13728) |
| 2914 | - | - | C++（1）：类 | 174:16 | [link](https://www.bilibili.com/video/BV1Mh4y1d7FN) |
| 2915 | - | - | C++（2）：异常 | 62:41 | [link](https://www.bilibili.com/video/BV1Qu411p7tM) |
| 2916 | - | - | C++（3）：OOP | 174:11 | [link](https://www.bilibili.com/video/BV12P411v7QM) |
| 2917 | - | - | Python（上）：基础 | 123:13 | [link](https://www.bilibili.com/video/BV1eN41167dt) |
| 2918 | - | - | Python（下）：OOP | 71:31 | [link](https://www.bilibili.com/video/BV1Ch411N7Cx) |
| 2919 | - | - | 工程数学之格林函数解常微分方程 | 84:38 | [link](https://www.bilibili.com/video/BV1NM411B7PN) |
| 2920 | - | - | 工程数学之渐进分析/摄动理论基础 | 159:05 | [link](https://www.bilibili.com/video/BV1EG4y1c735) |
| 2921 | - | - | 湍流/紊流01-湍流基本性质，流体方程1 | 65:14 | [link](https://www.bilibili.com/video/BV1JL411A7cE) |
| 2922 | - | - | 湍流/紊流02-流体方程2 | 53:09 | [link](https://www.bilibili.com/video/BV1gZ4y187JR) |
| 2923 | - | - | 湍流/紊流03-统计描述1 | 41:41 | [link](https://www.bilibili.com/video/BV1WB4y1y7Ub) |
| 2924 | - | - | 湍流/紊流04-统计描述2 | 27:18 | [link](https://www.bilibili.com/video/BV1RA4y1f7jp) |
| 2925 | - | - | 湍流/紊流05-统计描述3 | 52:20 | [link](https://www.bilibili.com/video/BV1j3411P7h8) |
| 2926 | - | - | 湍流/紊流06-统计描述4，湍流方程1 | 51:04 | [link](https://www.bilibili.com/video/BV12t4y1x7o7) |
| 2927 | - | - | 湍流/紊流07-湍流方程2 | 40:55 | [link](https://www.bilibili.com/video/BV1Zr4y1x7cV) |
| 2928 | - | - | 湍流/紊流08-湍流方程3，湍流尺度1 | 41:36 | [link](https://www.bilibili.com/video/BV1cY411c7Cd) |
| 2929 | - | - | 湍流/紊流09-湍流尺度2 | 47:38 | [link](https://www.bilibili.com/video/BV1wF411V74G) |
| 2930 | - | - | 湍流/紊流10-湍流尺度3 | 48:48 | [link](https://www.bilibili.com/video/BV1kY4y1x7zc) |
| 2931 | - | - | 湍流/紊流11-湍流尺度4 | 42:21 | [link](https://www.bilibili.com/video/BV1Fd4y1o7At) |
| 2932 | - | - | 湍流/紊流12-湍流尺度5 | 31:16 | [link](https://www.bilibili.com/video/BV1US4y1s7Bg) |
| 2933 | - | - | 湍流/紊流13-湍流尺度6 | 52:11 | [link](https://www.bilibili.com/video/BV1bB4y157nB) |
| 2934 | - | - | 拉普拉斯变换基础1 | 64:18 | [link](https://www.bilibili.com/video/BV1rZ4y1o7j4) |
| 2935 | - | - | 拉普拉斯变换基础2 | 58:26 | [link](https://www.bilibili.com/video/BV1Zr4y1b73G) |
| 2936 | - | - | 拉普拉斯变换基础3 | 51:16 | [link](https://www.bilibili.com/video/BV1RW4y127C5) |
| 2937 | - | - | 拉普拉斯变换基础4 | 54:13 | [link](https://www.bilibili.com/video/BV1Lr4y177ga) |
| 2938 | - | - | 【东方钢琴easy练习】永遠の巫女 | 1:42 | [link](https://www.bilibili.com/video/BV1vK411p7X9) |
| 2939 | - | - | 【东方钢琴easy练习】遠野の森 | 1:16 | [link](https://www.bilibili.com/video/BV1tA411i7u3) |
| 2940 | - | - | 【东方钢琴easy练习】妖々夢　～ Snow or Cherry Petal | 1:20 | [link](https://www.bilibili.com/video/BV1nv411q7Td) |
| 2941 | - | - | 【东方钢琴练习】春色小径 ～ Colorful Path（节选） | 1:28 | [link](https://www.bilibili.com/video/BV1Pq4y1g7Qr) |
| 2942 | - | - | 【东方钢琴easy练习】神は恵みの雨を降らす ～ Sylphid Dream | 1:43 | [link](https://www.bilibili.com/video/BV1FQ4y1P7ts) |
| 2943 | - | - | 英文非小说评鉴：《公正》 | 12:41 | [link](https://www.bilibili.com/video/BV17K411V749) |
| 2944 | - | - | 英文非小说评鉴：《心流》 | 8:55 | [link](https://www.bilibili.com/video/BV1G54y1r7b3) |
| 2945 | - | - | 多项式1：余式定理，因式定理 | 9:12 | [link](https://www.bilibili.com/video/BV1VZ4y1u75m) |
| 2946 | - | - | 多项式2：多项式求根 | 15:23 | [link](https://www.bilibili.com/video/BV1e54y1q72f) |
| 2947 | - | - | 多项式3：多项式求根，韦达定理 | 13:43 | [link](https://www.bilibili.com/video/BV15f4y1R7qE) |
| 2948 | - | - | 愉快学习的5条建议 | 9:21 | [link](https://www.bilibili.com/video/BV1Pt4y197ua) |
| 2949 | - | - | 如何在word中打公式？ | 14:15 | [link](https://www.bilibili.com/video/BV1C4411q7LS) |
| 2950 | - | - | The Willpower Instinct(《自控力》)精读-前言 | 98:54 | [link](https://www.bilibili.com/video/BV1tb41127KK) |
| 2951 | - | - | The Willpower Instinct(《自控力》)精读-第一章：什么是自控力 | 207:03 | [link](https://www.bilibili.com/video/BV1pb411h7vY) |
| 2952 | - | - | The Willpower Instinct(《自控力》)精读-第二章：自控力本能 | 259:59 | [link](https://www.bilibili.com/video/BV1xb411v7tm) |
| 2953 | - | - | The Willpower Instinct(《自控力》)精读-第三章：自控力好似肌肉 | 204:11 | [link](https://www.bilibili.com/video/BV1wb411t7d3) |
| 2954 | - | - | The Willpower Instinct(《自控力》)精读-第四章：“罪恶许可证” | 210:41 | [link](https://www.bilibili.com/video/BV1jb411L7TY) |
| 2955 | - | - | The Willpower Instinct（《自控力》）精读第五章：欲望还是幸福？ | 192:58 | [link](https://www.bilibili.com/video/BV114411Y7r7) |
| 2956 | - | - | The Willpower Instinct（自控力）第六章：What the Hell效应 | 156:18 | [link](https://www.bilibili.com/video/BV16J411A7Z4) |
| 2957 | - | - | The Willpower Instinct（《自控力》）精读-第七章：卖未来 | 181:44 | [link](https://www.bilibili.com/video/BV1EE411B7Cg) |
| 2958 | - | - | The Willpower Instinct（《自控力》）精读-第八章：自控力的感染性 | 151:22 | [link](https://www.bilibili.com/video/BV1zJ411Q7UM) |
| 2959 | - | - | The Willpower Instinct（《自控力》）精读-第9、10章：“不要做”的局限性，结束语 | 156:51 | [link](https://www.bilibili.com/video/BV1YJ411q7k1) |
| 2960 | - | - | 1_老奶奶学算法---两数之和 | 5:07 | [link](https://www.bilibili.com/video/BV1QeaP6EEiy) |
| 2961 | - | - | 2_老奶奶学算法---字母异位词分组 | 6:52 | [link](https://www.bilibili.com/video/BV1oHhX6REKo) |
| 2962 | - | - | 3_老奶奶学算法---最长连续序列 | 7:21 | [link](https://www.bilibili.com/video/BV1MBam6YE1E) |
| 2963 | - | - | 4_老奶奶学算法---哈希表大总结 | 7:12 | [link](https://www.bilibili.com/video/BV1tram6aEFB) |
| 2964 | - | - | 1_老奶奶学python---认知新帮手 | 2:24 | [link](https://www.bilibili.com/video/BV1m8uH6eEjE) |
| 2965 | - | - | 2_老奶奶学python---会装东西的纸箱 | 3:44 | [link](https://www.bilibili.com/video/BV1dbu86TEpC) |
| 2966 | - | - | 3_老奶奶学python---会开口问的帮手 | 3:16 | [link](https://www.bilibili.com/video/BV122u86REkY) |
| 2967 | - | - | 4_老奶奶学python---会拿主意的帮手 | 3:42 | [link](https://www.bilibili.com/video/BV1WVu86EE7Q) |
| 2968 | - | - | 5_老奶奶学python---数一遍与干到收工 | 1:41 | [link](https://www.bilibili.com/video/BV1AVu86EEzE) |
| 2969 | - | - | 6_老奶奶学python---货架装货 | 1:42 | [link](https://www.bilibili.com/video/BV1AVu86EEX3) |
| 2970 | - | - | 7_老奶奶学python---纸条的更多招式 | 1:42 | [link](https://www.bilibili.com/video/BV1AVu86EEBV) |
| 2971 | - | - | 8_老奶奶学python---小本本管货 | 2:01 | [link](https://www.bilibili.com/video/BV1AVu86EEbZ) |
| 2972 | - | - | 9_老奶奶学python---总结课(一)：会装会想 | 1:44 | [link](https://www.bilibili.com/video/BV1WVu86EEc8) |
| 2973 | - | - | 10_老奶奶学python---菜谱干货 | 1:54 | [link](https://www.bilibili.com/video/BV1K3uu6FEYy) |
| 2974 | - | - | 11_老奶奶学python---模具做货 | 2:17 | [link](https://www.bilibili.com/video/BV1x3uu6FEUd) |
| 2975 | - | - | 12_老奶奶学python---帮手摔倒也不慌 | 2:34 | [link](https://www.bilibili.com/video/BV1x3uu6FEeK) |
| 2976 | - | - | 13_老奶奶学python---借领居家工具箱 | 2:32 | [link](https://www.bilibili.com/video/BV11guu6fEiq) |
| 2977 | - | - | 14_老奶奶学python---记账本存档 | 2:36 | [link](https://www.bilibili.com/video/BV11Xtm6JEq9) |
| 2978 | - | - | 15_老奶奶学python---大总结课：小帮手全能上岗 | 2:40 | [link](https://www.bilibili.com/video/BV1CLuu6xEZ4) |
| 2979 | - | - | 最优化进阶---线性规划概述 | 61:35 | [link](https://www.bilibili.com/video/BV1o5UEBvENP) |
| 2980 | - | - | 老奶奶学最优化---线性规划基础 | 7:20 | [link](https://www.bilibili.com/video/BV1Cgg16bEPo) |
| 2981 | - | - | 老奶奶学最优化---单纯形法 | 6:26 | [link](https://www.bilibili.com/video/BV1Rxge6UE9E) |
| 2982 | - | - | 老奶奶学最优化---对偶 | 6:09 | [link](https://www.bilibili.com/video/BV19G3u6LEuW) |
| 2983 | - | - | 老奶奶学最优化---非单纯形法 | 4:55 | [link](https://www.bilibili.com/video/BV1T33G6CETZ) |
| 2984 | - | - | 老奶奶学最优化---整数规划 | 4:57 | [link](https://www.bilibili.com/video/BV1WT376QEwK) |
| 2985 | - | - | 写专利的周末 | 1:21 | [link](https://www.bilibili.com/video/BV1kZZ6YBExR) |
| 2986 | - | - | 循环 | 0:20 | [link](https://www.bilibili.com/video/BV19TVczCESR) |
| 2987 | - | - | 陈默的一天 | 0:26 | [link](https://www.bilibili.com/video/BV1yAo7BYEK7) |
| 2988 | - | - | 最近工作 | 1:05 | [link](https://www.bilibili.com/video/BV1BmLP6DEoX) |
| 2989 | - | - | 视觉主动跟随 | 0:38 | [link](https://www.bilibili.com/video/BV1aKLT6jEgp) |
| 2990 | - | - | 轮臂视觉主动跟随（注意看机器人头） | 1:21 | [link](https://www.bilibili.com/video/BV1GPLT6mEw4) |
| 2991 | - | - | 移动星厨 | 2:30 | [link](https://www.bilibili.com/video/BV1guLT65Etu) |
| 2992 | - | - | 手臂驱动 | 0:28 | [link](https://www.bilibili.com/video/BV1gTLT61Ezi) |
| 2993 | - | - | 星厨一代 | 2:50 | [link](https://www.bilibili.com/video/BV1VFLT6nEZf) |
| 2994 | - | - | 全部功能集成 | 1:22 | [link](https://www.bilibili.com/video/BV15ZLK6QErr) |
| 2995 | - | - | 日常 | 1:21 | [link](https://www.bilibili.com/video/BV1KgEc6cEC4) |
| 2996 | - | - | 每次付完款就弹出，利用人手抖、消费习惯，消费心理学开通，然后关闭又贼费劲。 | 0:12 | [link](https://www.bilibili.com/video/BV1rWJu6jEZz) |
| 2997 | - | - | vla 抓取和放置 | 0:53 | [link](https://www.bilibili.com/video/BV1we7x6oE8S) |
| 2998 | - | - | 劝学 | 0:06 | [link](https://www.bilibili.com/video/BV1EuNJ6iEQF) |
| 2999 | - | - | 自主作业 | 3:35 | [link](https://www.bilibili.com/video/BV1ubN96DEdj) |
| 3000 | - | - | 《富爸爸穷爸爸》：财务状态分析图 | 4:16 | [link](https://www.bilibili.com/video/BV14WrGBSEDM) |
| 3001 | - | - | 最优化基础---基本概念：凸优化、梯度、Jacobi矩阵、Hessian矩阵 | 68:53 | [link](https://www.bilibili.com/video/BV19M4y1n7M3) |
| 3002 | - | - | 最优化基础---一维搜索(1)：暴力搜索法、区间消去法、黄金分割法和斐波那契法 | 87:17 | [link](https://www.bilibili.com/video/BV1ku411b7iZ) |
| 3003 | - | - | 最优化基础---一维搜索(2)：二分法，牛顿法和割线法 | 30:49 | [link](https://www.bilibili.com/video/BV1Vh4y1E77d) |
| 3004 | - | - | 最优化基础---一维搜索(3)：三点二次插值法 | 42:50 | [link](https://www.bilibili.com/video/BV16M4y1x7B8) |
| 3005 | - | - | 最优化基础---非精确一维搜索：Armijo、Goldstein、Wolfe和强Wolfe条件；回溯法、内插公式和外插公式 | 65:01 | [link](https://www.bilibili.com/video/BV11X4y1E7yd) |
| 3006 | - | - | 最优化基础---多维无约束优化方法(1)：方向导数和梯度、梯度下降法、最速下降法 | 58:31 | [link](https://www.bilibili.com/video/BV1gu41177ZZ) |
| 3007 | - | - | 最优化基础---多维无约束优化方法(2)：牛顿法、Levenberg-Marquardt修正和高斯-牛顿法 | 52:35 | [link](https://www.bilibili.com/video/BV1mN4y1X7cP) |
| 3008 | - | - | 最优化基础---多维无约束优化方法(3)：共轭向量及其性质、共轭方向法的基本原理、扩张子空间定理、共轭梯度法以及非二次型问题中的共轭梯度法 | 87:05 | [link](https://www.bilibili.com/video/BV1xu411T7XW) |
| 3009 | - | - | 最优化基础---多维无约束优化方法(4)：拟牛顿法的引入、Hesse逆矩阵的近似、秩1修正公式、DFP算法和BFGS算法 | 62:31 | [link](https://www.bilibili.com/video/BV1ki421S7GH) |
| 3010 | - | - | 非精确一维搜索octave代码实现 | 20:09 | [link](https://www.bilibili.com/video/BV1Di421v7Qq) |
| 3011 | - | - | 最优化基础---求解线性方程组：概论、最小二乘法 | 14:19 | [link](https://www.bilibili.com/video/BV1ow4m1e7QC) |
| 3012 | - | - | 最优化基础---求解线性方程组：递推最小二乘法 | 13:21 | [link](https://www.bilibili.com/video/BV1tz42187hd) |
| 3013 | - | - | 最优化基础---求解线性方程组：最小范数解 | 20:41 | [link](https://www.bilibili.com/video/BV1ff421q7v5) |
| 3014 | - | - | 最优化基础---求解线性方程组：Kaczmarz算法 | 29:52 | [link](https://www.bilibili.com/video/BV1RmyXYoEF2) |
| 3015 | - | - | 最优化基础---求解线性方程组：一般意义下的方程组求解 | 22:24 | [link](https://www.bilibili.com/video/BV1zS6pYuEHR) |
| 3016 | - | - | 一点点说明，2023年10月22日 | 11:21 | [link](https://www.bilibili.com/video/BV1u34y1u7yU) |
| 3017 | - | - | 导数、梯度、雅可比矩阵、黑塞矩阵 | 1:10 | [link](https://www.bilibili.com/video/BV1iF41117ek) |
| 3018 | - | - | 二分法、牛顿法、割线法 | 0:49 | [link](https://www.bilibili.com/video/BV1T841167Gn) |
| 3019 | - | - | 暴力搜索法、区间消去法、黄金分割法、斐波拉契法 | 0:57 | [link](https://www.bilibili.com/video/BV1g94y1z7zu) |
| 3020 | - | - | 三点二次插值法 | 1:11 | [link](https://www.bilibili.com/video/BV1np4y1L7RM) |
| 3021 | - | - | Armijo条件、Goldstein条件、Wolfe和强Wolfe条件 | 1:18 | [link](https://www.bilibili.com/video/BV1AP411h7sY) |
| 3022 | - | - | 方向导数和梯度 | 1:35 | [link](https://www.bilibili.com/video/BV1zj41147Ei) |
| 3023 | - | - | 牛顿法、LM修正和高斯牛顿法 | 1:13 | [link](https://www.bilibili.com/video/BV1rw4m1S7bN) |
| 3024 | - | - | 共轭向量、扩张子空间定理和共轭梯度法 | 1:14 | [link](https://www.bilibili.com/video/BV1m7421R7RA) |
| 3025 | - | - | 拟牛顿法、黑塞矩阵逆矩阵近似、秩1、DFP和BFGS算法 | 1:23 | [link](https://www.bilibili.com/video/BV1Yy411z7Ei) |
| 3026 | - | - | 【01】AI Infra最详细Profile教程—vllm 实现及优化 | 21:41 | [link](https://www.bilibili.com/video/BV16w316ZEyS) |
| 3027 | - | - | 【02】vLLM实战项目代码，可秋招可实习用 | 5:04 | [link](https://www.bilibili.com/video/BV1keGP6UED9) |
| 3028 | - | - | 【03】vllm系列之torch.profiler与compile详解 | 29:12 | [link](https://www.bilibili.com/video/BV1XhM96FEjH) |
| 3029 | - | - | 手撕vLLM系列[4]：从自回归一路讲到多卡并行，全程附带性能分析与理论讲解 | 15:18 | [link](https://www.bilibili.com/video/BV1W2tn6zEjU) |
| 3030 | - | - | 手撕vLLM系列[5]: V0版本自回归推理概述 | 8:12 | [link](https://www.bilibili.com/video/BV1kvtW6yEt8) |
| 3031 | - | - | 手撕vLLM系列【6】：手把手教你vLLM环境搭建 | 8:52 | [link](https://www.bilibili.com/video/BV1Ebe36QEr3) |
| 3032 | - | - | 手撕vLLM系列【7】：RMSNorm代码实现 | 12:58 | [link](https://www.bilibili.com/video/BV1QEek6fEeq) |
| 3033 | - | - | 手撕vLLM系列【8】：Rotary 公式详解 | 6:08 | [link](https://www.bilibili.com/video/BV1She26TEeJ) |
| 3034 | - | - | 手撕vLLM系列【9】：RoPE 50行代码极简实现！ | 19:55 | [link](https://www.bilibili.com/video/BV1eFe16zEBi) |
| 3035 | - | - | 手撕vLLM系列【10】：Activation激活函数完整实现 | 5:54 | [link](https://www.bilibili.com/video/BV145e16FEBP) |
| 3036 | - | - | 手撕vLLM系列【11】：Attention 50行代码高效实现 | 14:14 | [link](https://www.bilibili.com/video/BV16qeB6cEJn) |
| 3037 | - | - | 从零到一：像刷力扣一样手撕100个AI Infra的Kernel算子（CUDA+Triton+Pytorch） | 4:41 | [link](https://www.bilibili.com/video/BV1qhDXBzEbA) |
| 3038 | - | - | AI Infra的招聘要求以及学习路线 | 5:03 | [link](https://www.bilibili.com/video/BV1qKQGBtEDE) |
| 3039 | - | - | 手撕AI Infra算子系列3：极速环境配置，20分钟学会！包你完全0报错！ | 20:54 | [link](https://www.bilibili.com/video/BV1VvQ3BSELZ) |
| 3040 | - | - | 手撕AI Infra算子系列4：CUDA、Triton、Pytorch的前世今生 | 17:45 | [link](https://www.bilibili.com/video/BV147dYBLEi4) |
| 3041 | - | - | 手撕AI Infra算子系列5：element wise算子详解（CUDA、Triton、Pytorch） | 20:27 | [link](https://www.bilibili.com/video/BV1L6oNBSEGc) |
| 3042 | - | - | 手撕AI Infra算子系列6：工业级Element Wise是如何实现的？Oneflow详解 | 9:04 | [link](https://www.bilibili.com/video/BV1npovBCE1r) |
| 3043 | - | - | 手撕AI Infra算子系列7：Matrix Addition详解。 | 11:26 | [link](https://www.bilibili.com/video/BV1PvoeB2E2h) |
| 3044 | - | - | 手撕AI Infra算子系列8：颜色反转；详解View与Offset | 18:18 | [link](https://www.bilibili.com/video/BV1ono6BJEnt) |
| 3045 | - | - | 手撕AI Infra算子系列9:Reduce的七种优化方法 | 23:21 | [link](https://www.bilibili.com/video/BV1cJdPBHEK2) |
| 3046 | - | - | 手撕AI Infra算子系列10：英伟达官方reduce实现详解 | 18:51 | [link](https://www.bilibili.com/video/BV1wc5n6PEhQ) |
| 3047 | - | - | 手撕AI Infra算子系列11：LeetGPU中的Reduce和Dot Product的代码实现 | 6:53 | [link](https://www.bilibili.com/video/BV1FS536zELn) |
| 3048 | - | - | 手撕AI Infra算子系列12：Softmax详解+原理+论文+N种优化方法 | 17:39 | [link](https://www.bilibili.com/video/BV1tq5i69Epg) |
| 3049 | - | - | 手撕AI Infra算子系列13：Scan算子详解+原理+代码+论文 | 12:39 | [link](https://www.bilibili.com/video/BV1K2Gq6SEvQ) |
| 3050 | - | - | 手撕AI Infra算子系列14：BatchNorm/LayerNorm/RMSNorm理论解析 | 18:43 | [link](https://www.bilibili.com/video/BV1BKG76LEPM) |
| 3051 | - | - | 手撕AI Infra算子系列15：Norm代码实现 | 24:50 | [link](https://www.bilibili.com/video/BV1fP7j6xEtN) |
| 3052 | - | - | 手撕AI Infra算子系列16：矩阵乘法 | 26:30 | [link](https://www.bilibili.com/video/BV1c77L6ZE5b) |
| 3053 | - | - | 手撕AI Infra算子系列18：别再背八股了！Transformer真的是一夜爆火吗？一文带你读懂Transformer的历史脉络！ALL才是论文的核心精华 | 26:11 | [link](https://www.bilibili.com/video/BV195Y16KEcg) |
| 3054 | - | - | 北邮矩阵论期末复习——复习前的吐槽 | 1:37 | [link](https://www.bilibili.com/video/BV1v8qaBkEy7) |
| 3055 | - | - | 范数理论 | 19:06 | [link](https://www.bilibili.com/video/BV1R8qaBkERy) |
| 3056 | - | - | 范数习题 | 16:11 | [link](https://www.bilibili.com/video/BV1v8qaBkEUe) |
| 3057 | - | - | 线性空间习题 | 17:26 | [link](https://www.bilibili.com/video/BV1njqrBVECz) |
| 3058 | - | - | 线性空间习题 | 8:17 | [link](https://www.bilibili.com/video/BV1njqrBVE7C) |
| 3059 | - | - | 北邮矩阵论对角化和Jordan | 14:31 | [link](https://www.bilibili.com/video/BV1Z8BMBEEoW) |
| 3060 | - | - | 北邮矩阵论线性变换一 | 24:53 | [link](https://www.bilibili.com/video/BV1B8BMBEEbV) |
| 3061 | - | - | 矩阵分析 | 10:09 | [link](https://www.bilibili.com/video/BV1QivQBpEWe) |
| 3062 | - | - | 矩阵函数课后习题全讲 | 22:50 | [link](https://www.bilibili.com/video/BV113v9B7EWj) |
| 3063 | - | - | LDU分解 | 4:42 | [link](https://www.bilibili.com/video/BV1SAv9BXEWE) |
| 3064 | - | - | LU的Crout分解 | 6:02 | [link](https://www.bilibili.com/video/BV1UAv9BXEfs) |
| 3065 | - | - | QR分解——施密特法 | 2:29 | [link](https://www.bilibili.com/video/BV1mKv9BDErD) |
| 3066 | - | - | QR——Given变换 | 7:36 | [link](https://www.bilibili.com/video/BV1rnv9B3Evg) |
| 3067 | - | - | QR分解——H分解 | 3:39 | [link](https://www.bilibili.com/video/BV13YicBjEYt) |
| 3068 | - | - | 满秩分解 | 0:41 | [link](https://www.bilibili.com/video/BV1GhicBmEs1) |
| 3069 | - | - | SVD分解 | 5:38 | [link](https://www.bilibili.com/video/BV1TCicBzEJm) |
| 3070 | - | - | 广义逆1——投影变换 | 16:55 | [link](https://www.bilibili.com/video/BV1MWifBBEJN) |
| 3071 | - | - | 广义逆矩阵求解 | 6:23 | [link](https://www.bilibili.com/video/BV1tyiZBNEnd) |
| 3072 | - | - | 广义逆课后题 | 9:32 | [link](https://www.bilibili.com/video/BV18ziZBBEbm) |
| 3073 | - | - | 欧式空间 | 6:27 | [link](https://www.bilibili.com/video/BV1VbqTBTEQg) |
| 3074 | - | - | 欧式空间习题 | 5:38 | [link](https://www.bilibili.com/video/BV1bdqKBfEsC) |
| 3075 | - | - | 考后碎碎念 | 1:10 | [link](https://www.bilibili.com/video/BV1X8iyBTEw6) |
| 3076 | - | - | 重生之我学Rust | 20:37 | [link](https://www.bilibili.com/video/BV1ziDWYPEFQ) |
| 3077 | - | - | 进阶学ES 03-04 ES基于python API实践-2 | 18:37 | [link](https://www.bilibili.com/video/BV12d4y1i7QU) |
| 3078 | - | - | 《ROS 2机器人开发从入门到实践》 1.4.1 Linux终端基础操作 | 14:20 | [link](https://www.bilibili.com/video/BV1NE421w72J) |
| 3079 | - | - | 《ROS 2机器人开发从入门到实践》 1.4.2 在Linux中安装软件 | 12:11 | [link](https://www.bilibili.com/video/BV1yr421M7ya) |
| 3080 | - | - | 《ROS 2机器人开发从入门到实践》 1.4.3 在Linux中编写Python代码 | 14:37 | [link](https://www.bilibili.com/video/BV1vb421J7XZ) |
| 3081 | - | - | 《ROS 2机器人开发从入门到实践》 1.4.4 在Linux中编写C++代码 | 15:19 | [link](https://www.bilibili.com/video/BV174421S73i) |
| 3082 | - | - | 《ROS 2机器人开发从入门到实践》8.2.2搭建规划器插件框架（上） | 9:53 | [link](https://www.bilibili.com/video/BV1AdzVYnErk) |
| 3083 | - | - | 《ROS 2机器人开发从入门到实践》8.2.2搭建规划器插件框架（下） | 8:59 | [link](https://www.bilibili.com/video/BV1EUB9YWERp) |
| 3084 | - | - | 《ROS 2机器人开发从入门到实践》8.2.3实现自定义规划算法 | 8:27 | [link](https://www.bilibili.com/video/BV1jAzYYtEEH) |
| 3085 | - | - | 《ROS 2机器人开发从入门到实践》8.2.4配置导航参数并测试 | 5:56 | [link](https://www.bilibili.com/video/BV1EHzpYvEQk) |
| 3086 | - | - | 《ROS 2机器人开发从入门到实践》8.3.1自定义控制介绍 | 3:29 | [link](https://www.bilibili.com/video/BV1tb6FYsErH) |
| 3087 | - | - | 《ROS 2机器人开发从入门到实践》8.3.2搭建控制器插件框架 | 12:52 | [link](https://www.bilibili.com/video/BV1HF6uYKEEH) |
| 3088 | - | - | 《ROS 2机器人开发从入门到实践》8.3.3实现自定义控制算法 | 13:13 | [link](https://www.bilibili.com/video/BV1E8q5YgEo6) |
| 3089 | - | - | 《ROS 2机器人开发从入门到实践》8.3.4配置导航参数并测试 | 9:38 | [link](https://www.bilibili.com/video/BV1qPqCYSEge) |
| 3090 | - | - | 《ROS 2机器人开发从入门到实践》第九章 搭建一个实体移动机器人 | 6:17 | [link](https://www.bilibili.com/video/BV13AqZYmEs2) |
| 3091 | - | - | 《ROS 2机器人开发从入门到实践》9.0.1FishBot两轮差速机器人组装教程 | 14:30 | [link](https://www.bilibili.com/video/BV17KkHYqEcZ) |
| 3092 | - | - | 《ROS 2机器人开发从入门到实践》9.0.2 FishBot配置助手介绍与安装 | 11:16 | [link](https://www.bilibili.com/video/BV1MQkwYNEi4) |
| 3093 | - | - | 《ROS 2机器人开发从入门到实践》9.0.3. 主控板固件烧录与配置 | 16:25 | [link](https://www.bilibili.com/video/BV1oAC5YJEdT) |
| 3094 | - | - | 《ROS 2机器人开发从入门到实践》9.0.4使用ROS2键盘控制FishBot | 9:27 | [link](https://www.bilibili.com/video/BV1PqkdY5Ew8) |
| 3095 | - | - | 《ROS 2机器人开发从入门到实践》9.0.5 雷达固件烧录及配置 | 11:26 | [link](https://www.bilibili.com/video/BV1GH63YfEq2) |
| 3096 | - | - | 《ROS 2机器人开发从入门到实践》9.0.6雷达驱动及建图测试 | 8:19 | [link](https://www.bilibili.com/video/BV1HH6HYzErB) |
| 3097 | - | - | 《ROS 2机器人开发从入门到实践》9.0.7 FishBot-Nav2导航测试 | 5:44 | [link](https://www.bilibili.com/video/BV1ePrFYvEvQ) |
| 3098 | - | - | 《ROS 2机器人开发从入门到实践》9.1移动机器人系统设计 | 5:00 | [link](https://www.bilibili.com/video/BV1NyFNeEEAh) |
| 3099 | - | - | 《ROS 2机器人开发从入门到实践》9.2.1开发平台介绍与安装 | 8:18 | [link](https://www.bilibili.com/video/BV1pLf2YxEzv) |
| 3100 | - | - | 《ROS 2机器人开发从入门到实践》9.2.2 第一个HelloWorld工程 | 8:30 | [link](https://www.bilibili.com/video/BV11cPXeoEfg) |
| 3101 | - | - | 《ROS 2机器人开发从入门到实践》9.2.3 使用代码点亮LED灯 | 6:03 | [link](https://www.bilibili.com/video/BV1FTNpeKEbG) |
| 3102 | - | - | 《ROS 2机器人开发从入门到实践》9.2.4 使用超声波测量距离 | 8:46 | [link](https://www.bilibili.com/video/BV18FNbeNEE5) |
| 3103 | - | - | 《ROS 2机器人开发从入门到实践》9.2.5 使用开源库驱动IMU | 9:47 | [link](https://www.bilibili.com/video/BV1LgN8ejEHG) |
| 3104 | - | - | 《ROS 2机器人开发从入门到实践》9.3.1 使用开源库驱动多路电机 | 10:03 | [link](https://www.bilibili.com/video/BV1UiNmeHEe1) |
| 3105 | - | - | 《ROS 2机器人开发从入门到实践》9.3.2 电动机速度测量与转换 | 16:33 | [link](https://www.bilibili.com/video/BV11ZNdeuEge) |
| 3106 | - | - | 《ROS 2机器人开发从入门到实践》9.3.3 使用PID控制轮子转速 | 29:24 | [link](https://www.bilibili.com/video/BV137KPezEaH) |
| 3107 | - | - | 《ROS 2机器人开发从入门到实践》9.3.4 运动学正逆解的实现 | 26:55 | [link](https://www.bilibili.com/video/BV1XwKTejE6V) |
| 3108 | - | - | 《ROS 2机器人开发从入门到实践》9.3.5 机器人里程计计算 | 15:23 | [link](https://www.bilibili.com/video/BV1BJA5eTE9t) |
| 3109 | - | - | 《ROS 2机器人开发从入门到实践》9.4.1 第一个节点 | 21:54 | [link](https://www.bilibili.com/video/BV1kQAqeCEE9) |
| 3110 | - | - | 《ROS 2机器人开发从入门到实践》9.4.2 订阅话题控制机器人 | 13:07 | [link](https://www.bilibili.com/video/BV12rPue6EoY) |
| 3111 | - | - | 《ROS 2机器人开发从入门到实践》9.4.3  发布机器人里程计话题 | 23:01 | [link](https://www.bilibili.com/video/BV15LPxeYEVp) |
| 3112 | - | - | 《ROS 2机器人开发从入门到实践》9.5.1  驱动并显示雷达点云 | 10:30 | [link](https://www.bilibili.com/video/BV1JnPeewEQ5) |
| 3113 | - | - | 《ROS 2机器人开发从入门到实践》9.5.2 移动机器人的坐标系框架介绍 | 4:41 | [link](https://www.bilibili.com/video/BV1QmP7eBEz2) |
| 3114 | - | - | 《ROS 2机器人开发从入门到实践》9.5.3 准备机器人URDF | 8:17 | [link](https://www.bilibili.com/video/BV1Fk9AYnEg2) |
| 3115 | - | - | 《ROS 2机器人开发从入门到实践》9.5.4 发布里程计TF | 4:56 | [link](https://www.bilibili.com/video/BV1Uq93YRE5T) |
| 3116 | - | - | 《ROS 2机器人开发从入门到实践》9.5.5 完成机器人建图并保存地图 | 9:00 | [link](https://www.bilibili.com/video/BV1yVXXYbETt) |
| 3117 | - | - | 《ROS 2机器人开发从入门到实践》9.5.6 完成机器人导航 | 7:27 | [link](https://www.bilibili.com/video/BV12L9hYrEkp) |
| 3118 | - | - | 《ROS 2机器人开发从入门到实践》10.1.1 QoS策略介绍 | 9:04 | [link](https://www.bilibili.com/video/BV1EK9zYDE1s) |
| 3119 | - | - | 《ROS 2机器人开发从入门到实践》10.1.2 QoS的兼容性 | 2:24 | [link](https://www.bilibili.com/video/BV1UH9ZYpEs6) |
| 3120 | - | - | 《ROS 2机器人开发从入门到实践》10.1.3 Python QoS兼容性测试 | 8:13 | [link](https://www.bilibili.com/video/BV17ERKY4E5U) |
| 3121 | - | - | 《ROS 2机器人开发从入门到实践》10.1.4 C++ QoS兼容性测试 | 6:10 | [link](https://www.bilibili.com/video/BV12m9mY9E8f) |
| 3122 | - | - | 《ROS 2机器人开发从入门到实践》10.2.1 执行器与回调组介绍 | 6:01 | [link](https://www.bilibili.com/video/BV1ViRHYcEhj) |
| 3123 | - | - | 《ROS 2机器人开发从入门到实践》10.2.2 在Python中使用回调组 | 9:33 | [link](https://www.bilibili.com/video/BV1sRRYY2Ecc) |
| 3124 | - | - | 《ROS 2机器人开发从入门到实践》10.2.3 在C++中使用回调组 | 8:33 | [link](https://www.bilibili.com/video/BV17aR5YSE9G) |
| 3125 | - | - | 《ROS 2机器人开发从入门到实践》10.3.1 生命周期节点介绍 | 9:15 | [link](https://www.bilibili.com/video/BV1pdQGYyEm5) |
| 3126 | - | - | 《ROS 2机器人开发从入门到实践》10.3.2 在Python中编写生命周期节点 | 9:42 | [link](https://www.bilibili.com/video/BV1R1QnYWEB3) |
| 3127 | - | - | 《ROS 2机器人开发从入门到实践》10.3.3  在C++中编写生命周期节点 | 6:42 | [link](https://www.bilibili.com/video/BV1CAQ6Y9EvF) |
| 3128 | - | - | 《ROS 2机器人开发从入门到实践》10.4.1 使用执行器组织多个节点 | 11:37 | [link](https://www.bilibili.com/video/BV11SXTYTEtu) |
| 3129 | - | - | 《ROS 2机器人开发从入门到实践》10.4.2 使用组件运行组合节点 | 5:54 | [link](https://www.bilibili.com/video/BV153QoYWEpn) |
| 3130 | - | - | 《ROS 2机器人开发从入门到实践》10.4.3 编写自己的组件 | 6:52 | [link](https://www.bilibili.com/video/BV1BCX6YnEKL) |
| 3131 | - | - | 《ROS 2机器人开发从入门到实践》10.5.1 消息过滤器介绍 | 1:39 | [link](https://www.bilibili.com/video/BV1bso2YaEDD) |
| 3132 | - | - | 《ROS 2机器人开发从入门到实践》10.5.2 在Python中同步传感器数据 | 5:36 | [link](https://www.bilibili.com/video/BV12UoeY4EuQ) |
| 3133 | - | - | 《ROS 2机器人开发从入门到实践》10.5.3 在 C++中同步传感器数据 | 6:44 | [link](https://www.bilibili.com/video/BV1nfoRY3E3t) |
| 3134 | - | - | 《ROS 2机器人开发从入门到实践》10.6.1 使用不同的DDS进行通信 | 4:55 | [link](https://www.bilibili.com/video/BV1UXZHYFExy) |
| 3135 | - | - | 《ROS 2机器人开发从入门到实践》10.6.2 配置局域网通信 | 2:29 | [link](https://www.bilibili.com/video/BV1BhfNYPEML) |
| 3136 | - | - | 《ROS 2机器人开发从入门到实践》10.6.3调整DDS配置 | 3:35 | [link](https://www.bilibili.com/video/BV1bMR2YxExi) |
| 3137 | - | - | 《ROS 2机器人开发从入门到实践》10.6.4 使用DDS共享内存 | 6:43 | [link](https://www.bilibili.com/video/BV1k5dNYPEdo) |
| 3138 | - | - | 【鱼香ROS】动手学ROS2/ROS2基础入门到实践教程/小鱼带你手把手学习ROS2 | 595:42 | [link](https://www.bilibili.com/video/BV1gr4y1Q7j5) |
| 3139 | - | - | 【ROS2硬件控制】1.课程及开发平台介绍 | 4:56 | [link](https://www.bilibili.com/video/BV1po4y1676Q) |
| 3140 | - | - | 【ROS2硬件控制】2.嵌入式开发从点灯开始 | 5:18 | [link](https://www.bilibili.com/video/BV1UD4y1M745) |
| 3141 | - | - | 【ROS2硬件控制】3. 什么是单片机MCU，和CPU什么区别 | 7:07 | [link](https://www.bilibili.com/video/BV1hg4y1t7af) |
| 3142 | - | - | 【ROS2硬件控制】4.细数-微处理器开发平台 | 10:58 | [link](https://www.bilibili.com/video/BV1354y1M7HM) |
| 3143 | - | - | 【ROS2硬件控制】5. 搭建PlateFormIO开发环境 | 12:51 | [link](https://www.bilibili.com/video/BV1mX4y1U762) |
| 3144 | - | - | 【ROS2硬件控制】6.PIO工程结构&构建方式 | 10:09 | [link](https://www.bilibili.com/video/BV1QY411B71V) |
| 3145 | - | - | 【ROS2硬件控制】7.串口输出HelloWorld（上） | 10:35 | [link](https://www.bilibili.com/video/BV1nv4y1L7QJ) |
| 3146 | - | - | 【ROS2硬件控制】7.串口输出HelloWorld（下） | 8:33 | [link](https://www.bilibili.com/video/BV1yM4y1z73M) |
| 3147 | - | - | 【ROS2硬件控制】13B.6串口通信-接收实验 | 10:52 | [link](https://www.bilibili.com/video/BV1xk4y1874q) |
| 3148 | - | - | 【ROS2硬件控制】13G.1 点灯基础-看懂LED驱动电路 | 5:27 | [link](https://www.bilibili.com/video/BV1nv4y1L7G9) |
| 3149 | - | - | 【ROS2硬件控制】13G.2 完成点灯-GPIO控制 | 17:01 | [link](https://www.bilibili.com/video/BV16m4y1k7xK) |
| 3150 | - | - | 【ROS2硬件控制】13G.3.学会使用按键-GPIO输入 | 13:19 | [link](https://www.bilibili.com/video/BV11m4y167GK) |
| 3151 | - | - | 【ROS2硬件控制】13G.4.电池电压测量-学会使用ADC | 19:55 | [link](https://www.bilibili.com/video/BV1fm4y1B7Ur) |
| 3152 | - | - | 【ROS2硬件控制】13A.1.学会安装第三方开源库 | 8:49 | [link](https://www.bilibili.com/video/BV17k4y1i7Dj) |
| 3153 | - | - | 【ROS2硬件控制】13A.2.使用开源库驱动IMU | 8:18 | [link](https://www.bilibili.com/video/BV1BL411S7vu) |
| 3154 | - | - | 【ROS2硬件控制】13A.3.学会面向对象编程-封装IMU驱动（上） | 22:15 | [link](https://www.bilibili.com/video/BV1Tc411W7jT) |
| 3155 | - | - | 【ROS2硬件控制】13A.3.学会面向对象编程-封装IMU驱动（下） | 17:03 | [link](https://www.bilibili.com/video/BV1mg4y1g7n6) |
| 3156 | - | - | 【ROS2硬件控制】13A.4.使用开源库驱动OLED | 17:04 | [link](https://www.bilibili.com/video/BV1FN411P7md) |
| 3157 | - | - | 【ROS2硬件控制】13A.5.通讯协议小课堂-I2C通信 | 13:21 | [link](https://www.bilibili.com/video/BV1ov4y1p799) |
| 3158 | - | - | 【ROS2硬件控制】13A.6.I2C通信实验-点亮OLEDU | 6:00 | [link](https://www.bilibili.com/video/BV11j411w7W8) |
| 3159 | - | - | 【ROS2硬件控制】14.MicroROS入门与实践 | 2:52 | [link](https://www.bilibili.com/video/BV15M4y1m7Rq) |
| 3160 | - | - | 【ROS2硬件控制】14B.1.Micro-ROS介绍与服务安装 | 5:48 | [link](https://www.bilibili.com/video/BV16m4y1q7zC) |
| 3161 | - | - | 【ROS2硬件控制】14B.2.在单片机上编写ROS2节点 | 25:19 | [link](https://www.bilibili.com/video/BV1gh411E7jU) |
| 3162 | - | - | 【ROS2硬件控制】14G.1.MicroROS话题订阅-控制LED | 21:29 | [link](https://www.bilibili.com/video/BV1sL411Y7NE) |
| 3163 | - | - | 【ROS2硬件控制】14G.2.ESP32上实现ROS-话题发布 | 16:46 | [link](https://www.bilibili.com/video/BV1No4y1t7x3) |
| 3164 | - | - | 14G.3.ESP32上实现ROS-服务通信 | 16:19 | [link](https://www.bilibili.com/video/BV17T411t7Ph) |
| 3165 | - | - | 14A.1.ESP32上实现ROS2自定义服务接口（上） | 12:54 | [link](https://www.bilibili.com/video/BV1nk4y1L7pz) |

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
  - links: https://www.tgltommy.com/p/agent-rl（ https://www.bilibili.com/cheese/play/ss842375604 https://synergyfuture.feishu.cn/wiki/LQKNwhbZDidLj4kTTRWcH7utnic
- **AI 说“90% 有把握”，你敢让 Agent 自动执行吗？｜Jev：概率校准与 Agent 决策**
  - [B station](https://www.bilibili.com/video/BV134ph6vEmV)
  - links: https://www.tgltommy.com/p/agent-rl（ https://www.bilibili.com/cheese/play/ss842375604 https://synergyfuture.feishu.cn/wiki/LQKNwhbZDidLj4kTTRWcH7utnic
- **《Agent Loop》给AI Agent的一首嘻哈主题曲｜AI工程师跨界做说唱，连动画MV都配齐了【AI MV大赛】**
  - [B station](https://www.bilibili.com/video/BV1QLpw6JE6c)
  - links: https://synergyfuture.feishu.cn/wiki/LQKNwhbZDidLj4kTTRWcH7utnic
- **AI Agent 的底层其实就是一个 while 循环？Agent Loop 核心机制完整讲解**
  - [B station](https://www.bilibili.com/video/BV1SGTv6iEmZ)
  - links: https://www.tgltommy.com/p/agent-rl（ https://www.bilibili.com/cheese/play/ss842375604
- **AI Agent 为什么会“失忆”？因为上下文才是第一约束｜Agent 工程｜大模型Agent｜Agent Loop**
  - [B station](https://www.bilibili.com/video/BV1DsTn6wEB6)
  - links: https://www.tgltommy.com/p/agent-rl（ https://www.bilibili.com/cheese/play/ss842375604
- **AI Agent 为什么停不下来？从 ReAct 到 Copilot，看懂 Agent Loop 终止机制｜AI Agent 的终止机制详解**
  - [B station](https://www.bilibili.com/video/BV14mTb6EEQz)
  - links: https://www.tgltommy.com/p/agent-rl（ https://www.bilibili.com/cheese/play/ss842375604
- **Loop Engineering：从 Prompt 到 Agent 循环的范式迁移｜AI Agent 的下一层能力，不是写提示词，而是设计循环**
  - [B station](https://www.bilibili.com/video/BV1rmT16pEfj)
  - links: https://www.tgltommy.com/p/agent-rl（ https://www.bilibili.com/cheese/play/ss842375604
- **Agent Loop 即 RL Rollout？从产品循环到强化学习轨迹：理解 Agent RL 的关键入口，AI Agent 训练数据生成机制详解**
  - [B station](https://www.bilibili.com/video/BV1DUTd6aEyv)
  - links: https://www.tgltommy.com/p/agent-rl（ https://www.bilibili.com/cheese/play/ss842375604
- **AI会做奥数，却端不稳一杯水：具身智能到底难在哪？**
  - [B station](https://www.bilibili.com/video/BV1nRtn6PEwk)
  - links: https://www.tgltommy.com/p/agent-rl（ https://www.bilibili.com/cheese/play/ss842375604 https://synergyfuture.feishu.cn/wiki/LQKNwhbZDidLj4kTTRWcH7utnic
- **会后空翻的机器人，到底是怎么练出来的？你必须了解的从经典控制到强化学习｜AI Agent｜AI 智能体｜大模型强化学习**
  - [B station](https://www.bilibili.com/video/BV1eQtG6PEqm)
  - links: https://www.tgltommy.com/p/agent-rl（ https://www.bilibili.com/cheese/play/ss842375604 https://synergyfuture.feishu.cn/wiki/LQKNwhbZDidLj4kTTRWcH7utnic
- **机器人到底怎么学会干活？从模仿学习到具身智能的数据瓶颈**
  - [B station](https://www.bilibili.com/video/BV1bDYt6mEDz)
  - links: https://www.tgltommy.com/p/agent-rl（ https://www.bilibili.com/cheese/play/ss842375604 https://synergyfuture.feishu.cn/wiki/LQKNwhbZDidLj4kTTRWcH7utnic
- **一双灵巧手，为什么能卡住整台人形机器人？｜具身智能｜世界模型｜机器人**
  - [B station](https://www.bilibili.com/video/BV12naW6ZENU)
  - links: https://www.tgltommy.com/p/agent-rl（ https://www.bilibili.com/cheese/play/ss842375604 https://synergyfuture.feishu.cn/wiki/LQKNwhbZDidLj4kTTRWcH7utnic
- **机器人的 GPT 时刻到了？VLA 大模型离真正好用还有多远｜具身智能｜AI Agent｜强化学习｜大模型**
  - [B station](https://www.bilibili.com/video/BV1UqHL6UEQr)
  - links: https://www.tgltommy.com/p/agent-rl（ https://www.bilibili.com/cheese/play/ss842375604 https://synergyfuture.feishu.cn/wiki/LQKNwhbZDidLj4kTTRWcH7utnic
- **DeepSeek V4.1：40层注意力，为什么只存4份KV？｜KV Cache优化详解｜Agent长上下文优化**
  - [B station](https://www.bilibili.com/video/BV1Z5e56ZEmq)
  - links: https://www.tgltommy.com/p/agent-rl（ https://www.bilibili.com/cheese/play/ss842375604 https://synergyfuture.feishu.cn/wiki/LQKNwhbZDidLj4kTTRWcH7utnic
- **DeepSeek V4.1：CED架构与KV Cache优化详解**
  - [B station](https://www.bilibili.com/video/BV1xLe36hE65)
  - links: https://www.bilibili.com/cheese/play/ss556613313 https://synergyfuture.feishu.cn/wiki/LQKNwhbZDidLj4kTTRWcH7utnic
- **DeepSeek Harness：连 Agent Loop 本身都是插件，凭什么？揭秘智能体Runtime设计**
  - [B station](https://www.bilibili.com/video/BV1cJb96cEg2)
  - links: https://www.tgltommy.com/p/agent-rl（ https://www.bilibili.com/cheese/play/ss842375604
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
  - links: https://github.com/TGLTommy/FolioPaw https://synergyfuture.feishu.cn/wiki/LQKNwhbZDidLj4kTTRWcH7utnic
- **99美元、24小时预售260万美元：这只“小黄鸭”为什么重要？**
  - [B station](https://www.bilibili.com/video/BV1pktD69E9P)
  - links: https://synergyfuture.feishu.cn/wiki/LQKNwhbZDidLj4kTTRWcH7utnic
- **MIT最新发现：Agent 泛化能力不在模型，而在 Harness！RLM重新定义大模型后训练**
  - [B station](https://www.bilibili.com/video/BV1EGuZ6XEQC)
  - links: https://www.tgltommy.com/p/agent-rl（ https://www.bilibili.com/cheese/play/ss842375604
- **让AI学会“存档”！Kimi K3的5122万个Agent沙箱揭秘：Agent强化学习基础设施到底有多复杂？**
  - [B station](https://www.bilibili.com/video/BV1iXuH6UEd5)
  - links: https://www.tgltommy.com/p/agent-rl（ https://www.bilibili.com/cheese/play/ss842375604
- **Agent 的"世界模型"到底是什么? 从第一性原理，讲透它为什么总在同一个坑里栽倒｜AI Agent 深度解析**
  - [B station](https://www.bilibili.com/video/BV1AmNH6EENf)
  - links: https://www.tgltommy.com/p/agent-rl（ https://www.bilibili.com/cheese/play/ss842375604
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
  - links: https://www.tgltommy.com/p/agent-rl（ https://www.bilibili.com/cheese/play/ss842375604
- **你的 Agent 为什么一上线就翻车？模型不是瓶颈，Harness 才是关键！深入理解 Model + Harness 工程架构**
  - [B station](https://www.bilibili.com/video/BV1te8J62ETV)
  - links: https://www.tgltommy.com/p/agent-rl（ https://www.bilibili.com/cheese/play/ss842375604
- **企业级 Agent 落地方法论：模型太慢、调用太贵、动作太险，高频业务里的Agent该怎么用？**
  - [B station](https://www.bilibili.com/video/BV12u8z6eEax)
  - links: https://www.tgltommy.com/p/agent-rl（ https://www.bilibili.com/cheese/play/ss842375604 https://synergyfuture.feishu.cn/wiki/LQKNwhbZDidLj4kTTRWcH7utnic
- **AI Agent 安全核心：如何给大模型分级授权？三层权限体系详解：分级授权、凭证隔离、签名许可｜企业级 Agent 落地方法论**
  - [B station](https://www.bilibili.com/video/BV1kf8t6hEH8)
  - links: https://www.tgltommy.com/p/agent-rl（ https://www.bilibili.com/cheese/play/ss842375604 https://synergyfuture.feishu.cn/wiki/LQKNwhbZDidLj4kTTRWcH7utnic
- **AI Agent会“作弊”？测试全通过，也可能根本没完成任务｜企业级 Agent 落地方法论｜AI Agent｜智能体教程**
  - [B station](https://www.bilibili.com/video/BV1kch56oERd)
  - links: https://www.tgltommy.com/p/agent-rl（ https://www.bilibili.com/cheese/play/ss842375604 https://synergyfuture.feishu.cn/wiki/LQKNwhbZDidLj4kTTRWcH7utnic
- **模型再强也救不了 Agent：语义和记忆才是真正的瓶颈｜AI Agent｜AI 大模型｜Agent 记忆**
  - [B station](https://www.bilibili.com/video/BV1ueta67Efx)
  - links: https://www.tgltommy.com/p/agent-rl（ https://www.bilibili.com/cheese/play/ss842375604 https://synergyfuture.feishu.cn/wiki/LQKNwhbZDidLj4kTTRWcH7utnic
- **Claude Code 为什么不会撑爆上下文？深入解析 Agent 上下文压缩与会话恢复机制｜上下文投影、压缩、缓存与会话恢复全过程**
  - [B station](https://www.bilibili.com/video/BV1nJ396JEmC)
  - links: https://www.tgltommy.com/p/agent-rl（ https://www.bilibili.com/cheese/play/ss842375604
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
  - links: https://www.tgltommy.com/p/agent-rl（ https://www.bilibili.com/cheese/play/ss842375604
- **Agent记忆越多越聪明？恰恰相反：真正关键的是这4个动作｜写入、巩固、检索、遗忘的第一性原理｜Agent Continual Learning｜智能体持续学习**
  - [B station](https://www.bilibili.com/video/BV1opKr6FEBC)
  - links: https://www.tgltommy.com/p/agent-rl（ https://www.bilibili.com/cheese/play/ss842375604
- **为什么 Agent 不能照搬过去的经验？七要素定义一个合格 Agent Skill｜Agent Continual Learning 系列课程**
  - [B station](https://www.bilibili.com/video/BV1CYKY6nEok)
  - links: https://www.tgltommy.com/p/agent-rl（ https://www.bilibili.com/cheese/play/ss842375604
- **Agent 如何持续学习？什么时候必须改模型权重？深入理解 AI Agent 的记忆、Skill 与模型参数更新机制｜Agent 持续学习的四层路由法则**
  - [B station](https://www.bilibili.com/video/BV1ebg16jELx)
  - links: https://www.tgltommy.com/p/agent-rl（ https://www.bilibili.com/cheese/play/ss842375604
- **给 Agent 加 Memory 真的会变聪明吗？深入解析 AI 持续学习系统设计｜Agent Continual Learning｜AI Agent｜智能体**
  - [B station](https://www.bilibili.com/video/BV1kvgx66EZi)
  - links: https://www.tgltommy.com/p/agent-rl（ https://www.bilibili.com/cheese/play/ss842375604
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
  - links: https://github.com/modelcontextprotocol/inspector https://github.com/modelcontextprotocol/servers https://www.firecrawl.dev/
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
  - links: https://www.bilibili.com/cheese/play/ss556613313?csource=private_space_class_null&spm_id_from=333.1387.0.0 https://www.tgltommy.com/p/deepseek
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
  - links: http://localhost:8000
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
  - links: https://arxiv.org/abs/2505.22019 https://github.com/Alibaba-NLP/VRAG
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
- **DeepSpeed-Chat-23-step1_源码解读_模型推理-第2节**
  - [B station](https://www.bilibili.com/video/BV1yb421h7PB)
- **DeepSpeed-Chat-24-step1_源码解读_模型推理-第3节**
  - [B station](https://www.bilibili.com/video/BV1Xb421Y7ga)
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
- **DeepSpeed-Chat-20-step1_源码解读_模型保存-第3节**
  - [B station](https://www.bilibili.com/video/BV18h4y1S7Rn)
- **DeepSpeed-Chat-21-step1_源码解读_模型评估**
  - [B station](https://www.bilibili.com/video/BV1fZ421E7o9)
- **DeepSpeed-Chat-22-step1_源码解读_模型推理-第1节**
  - [B station](https://www.bilibili.com/video/BV1bm421p7GE)
- **DeepSpeed-Chat-25 Step-2-01 简介**
  - [B station](https://www.bilibili.com/video/BV1Dh4y1S7rG)
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
  - links: https://www.bilibili.com/video/BV14N4y1674J
- **ChatGLM3全新Function calling功能详解！开启AI Agent之路的最核心功能！**
  - [B station](https://www.bilibili.com/video/BV1K94y157gd)
  - links: https://www.bilibili.com/video/BV14N4y1674J
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
- **【优化算法】无约束优化-概述**
  - [B station](https://www.bilibili.com/video/BV1mP411C7ed)
- **【优化算法】线搜索方法-方向**
  - [B station](https://www.bilibili.com/video/BV1iX4y1H7Ef)
- **【优化算法】线搜索方法-步长-精确搜索**
  - [B station](https://www.bilibili.com/video/BV1H14y1R7Yo)
- **【优化算法】线搜索方法-步长-非确定性搜索**
  - [B station](https://www.bilibili.com/video/BV1Gh411P7uw)
- **【优化算法】线搜索方法-步长-Armijo Condition**
  - [B station](https://www.bilibili.com/video/BV11N411m75b)
- **【优化算法】线搜索方法-步长-Glodstein Condition**
  - [B station](https://www.bilibili.com/video/BV1UF411X7Dh)
- **【优化算法】线搜索方法-步长-Wolfe Condition**
  - [B station](https://www.bilibili.com/video/BV1Nz4y1J7Wt)
- **【优化算法】线搜索方法-收敛性证明**
  - [B station](https://www.bilibili.com/video/BV1Mh411P7VY)
- **【优化算法】收敛速度简介**
  - [B station](https://www.bilibili.com/video/BV1FP411y7kx)
- **【优化算法】梯度下降法-总体介绍**
  - [B station](https://www.bilibili.com/video/BV14h4y1E71v)
- **【优化算法】梯度下降法-基础补充-凸函数vs强凸函数vs严格凸函数（上）**
  - [B station](https://www.bilibili.com/video/BV1vs4y167rA)
- **【优化算法】梯度下降法-基础补充-凸函数vs强凸函数vs严格凸函数（下）**
  - [B station](https://www.bilibili.com/video/BV1Uj411o7XT)
- **【优化算法】梯度下降法-二次上界**
  - [B station](https://www.bilibili.com/video/BV1Ek4y1P72N)
- **【优化算法】梯度下降法-凸函数的收敛性**
  - [B station](https://www.bilibili.com/video/BV15m4y1n72Q)
- **【优化算法】梯度下降法-白老爹定理（上）**
  - [B station](https://www.bilibili.com/video/BV1Tg4y1w7jx)
- **【优化算法】梯度下降法-白老爹定理（下）**
  - [B station](https://www.bilibili.com/video/BV1MV4y1h7Va)
- **【优化算法】梯度下降法-强凸函数的收敛性分析（上）**
  - [B station](https://www.bilibili.com/video/BV1WW4y1o7aG)
- **【优化算法】梯度下降法-强凸函数的收敛性分析（下）**
  - [B station](https://www.bilibili.com/video/BV1mj411Z7br)
- **【优化算法】经典牛顿法-总体介绍**
  - [B station](https://www.bilibili.com/video/BV1fX4y1J7jE)
- **【优化算法】经典牛顿法-收敛性分析**
  - [B station](https://www.bilibili.com/video/BV1794y1q7Hz)
- **【强化学习】规划与学习-Dyna Architecture**
  - [B station](https://www.bilibili.com/video/BV1yT4y1U78Z)
  - links: https://pan.baidu.com/s/1K9wWHT0ajxBRUY0iaDVccA http://www.incompleteideas.net/book/RLbook2020.pdf
- **【强化学习】规划与学习-算力聚焦**
  - [B station](https://www.bilibili.com/video/BV1ar4y1p7ES)
  - links: https://pan.baidu.com/s/1K9wWHT0ajxBRUY0iaDVccA http://www.incompleteideas.net/book/RLbook2020.pdf-
- **【强化学习】规划与学习-决策时规划**
  - [B station](https://www.bilibili.com/video/BV1cY4y1i785)
  - links: https://pan.baidu.com/s/1K9wWHT0ajxBRUY0iaDVccA http://www.incompleteideas.net/book/RLbook2020.pdf
- **【强化学习】规划与学习-蒙特卡洛树搜索 MCTS**
  - [B station](https://www.bilibili.com/video/BV1s5411D7JT)
- **【强化学习】策略梯度方法-策略近似**
  - [B station](https://www.bilibili.com/video/BV1MS4y1r7ta)
  - links: https://pan.baidu.com/s/1K9wWHT0ajxBRUY0iaDVccA http://www.incompleteideas.net/book/RLbook2020.pdf
- **【强化学习】策略梯度方法-策略梯度定理**
  - [B station](https://www.bilibili.com/video/BV18u411Q76q)
  - links: https://pan.baidu.com/s/1K9wWHT0ajxBRUY0iaDVccA http://www.incompleteideas.net/book/RLbook2020.pdf
- **【强化学习】策略梯度方法-REINFORCE**
  - [B station](https://www.bilibili.com/video/BV1xb4y1W7Ye)
  - links: https://pan.baidu.com/s/1K9wWHT0ajxBRUY0iaDVccA http://www.incompleteideas.net/book/RLbook2020.pdf
- **【强化学习】策略梯度方法-REINFORCE with Baseline & Actor-Critic**
  - [B station](https://www.bilibili.com/video/BV1RF411x7oS)
  - links: https://pan.baidu.com/s/1K9wWHT0ajxBRUY0iaDVccA http://www.incompleteideas.net/book/RLbook2020.pdf
- **【强化学习】 时序差分-策略评估**
  - [B station](https://www.bilibili.com/video/BV1wS4y1F7zn)
  - links: https://pan.baidu.com/s/1K9wWHT0ajxBRUY0iaDVccA http://www.incompleteideas.net/book/RLbook2020.pdf
- **【强化学习】(SARSA) 时序差分-同轨策略TD控制**
  - [B station](https://www.bilibili.com/video/BV1BS4y1r7cm)
  - links: https://pan.baidu.com/s/1K9wWHT0ajxBRUY0iaDVccA http://www.incompleteideas.net/book/RLbook2020.pdf
- **【强化学习】(Q-Learning) 时序差分-离轨策略TD控制**
  - [B station](https://www.bilibili.com/video/BV1cZ4y1C7Ma)
  - links: https://pan.baidu.com/s/1K9wWHT0ajxBRUY0iaDVccA http://www.incompleteideas.net/book/RLbook2020.pdf
- **【强化学习】时序差分-期望SARSA**
  - [B station](https://www.bilibili.com/video/BV15L411T7LM)
  - links: https://pan.baidu.com/s/1K9wWHT0ajxBRUY0iaDVccA http://www.incompleteideas.net/book/RLbook2020.pdf
- **【强化学习】蒙特卡洛方法-前情回顾**
  - [B station](https://www.bilibili.com/video/BV1rF411J7Mw)
  - links: https://pan.baidu.com/s/1K9wWHT0ajxBRUY0iaDVccA http://www.incompleteideas.net/book/RLbook2020.pdf
- **【强化学习】蒙特卡洛方法-策略评估**
  - [B station](https://www.bilibili.com/video/BV1vm4y1Z7Ce)
  - links: https://pan.baidu.com/s/1K9wWHT0ajxBRUY0iaDVccA http://www.incompleteideas.net/book/RLbook2020.pdf
- **【强化学习】蒙特卡洛方法-基于试探性出发假设的MC控制**
  - [B station](https://www.bilibili.com/video/BV1N5411o7QD)
  - links: https://pan.baidu.com/s/1K9wWHT0ajxBRUY0iaDVccA http://www.incompleteideas.net/book/RLbook2020.pdf
- **【强化学习】蒙特卡洛方法-同轨VS离轨**
  - [B station](https://www.bilibili.com/video/BV1bS4y1C75M)
  - links: https://pan.baidu.com/s/1K9wWHT0ajxBRUY0iaDVccA http://www.incompleteideas.net/book/RLbook2020.pdf
- **【强化学习】 蒙特卡洛方法-同轨策略MC控制**
  - [B station](https://www.bilibili.com/video/BV1Ju4119794)
  - links: https://pan.baidu.com/s/1K9wWHT0ajxBRUY0iaDVccA http://www.incompleteideas.net/book/RLbook2020.pdf
- **【强化学习】蒙特卡洛方法-离轨策略MC策略评估**
  - [B station](https://www.bilibili.com/video/BV1EZ4y1R7r4)
  - links: https://pan.baidu.com/s/1K9wWHT0ajxBRUY0iaDVccA http://www.incompleteideas.net/book/RLbook2020.pdf
- **【强化学习】 蒙特卡洛方法-离轨策略评估与控制**
  - [B station](https://www.bilibili.com/video/BV1sS4y1C7tR)
  - links: https://pan.baidu.com/s/1K9wWHT0ajxBRUY0iaDVccA http://www.incompleteideas.net/book/RLbook2020.pdf
- **序言**
  - [B station](https://www.bilibili.com/video/BV1yk28YUEfs)
- **2012逻辑选择**
  - [B station](https://www.bilibili.com/video/BV1sk28YSEXV)
- **2012论证有效性分析**
  - [B station](https://www.bilibili.com/video/BV1Nk28YSEY4)
- **2012论说文**
  - [B station](https://www.bilibili.com/video/BV1Nk28YSEtg)
- **2016逻辑选择**
  - [B station](https://www.bilibili.com/video/BV1demgYjEVD)
- **2016-26**
  - [B station](https://www.bilibili.com/video/BV1a4mVYUENE)
- **2016-27**
  - [B station](https://www.bilibili.com/video/BV18amVYLEKG)
- **2016-28**
  - [B station](https://www.bilibili.com/video/BV1uamVYjERx)
- **2016-29**
  - [B station](https://www.bilibili.com/video/BV1bamVYLEoz)
- **2016-30**
  - [B station](https://www.bilibili.com/video/BV18amVYLEKx)
- **2016-31**
  - [B station](https://www.bilibili.com/video/BV18amVYLEwL)
- **2016-32**
  - [B station](https://www.bilibili.com/video/BV18amVYLENz)
- **2016-33**
  - [B station](https://www.bilibili.com/video/BV1KZmGYzEsj)
- **2016-34**
  - [B station](https://www.bilibili.com/video/BV1bamVYLEoc)
- **2016-35**
  - [B station](https://www.bilibili.com/video/BV1bamVYLEoM)
- **2016-36**
  - [B station](https://www.bilibili.com/video/BV18amVYLEcz)
- **2016-37**
  - [B station](https://www.bilibili.com/video/BV1SamVYLExM)
- **2016-38**
  - [B station](https://www.bilibili.com/video/BV18amVYLEwo)
- **2016-39**
  - [B station](https://www.bilibili.com/video/BV1SamVYLEiW)
- **2016-40**
  - [B station](https://www.bilibili.com/video/BV1bamVYLEZi)
- **2016-41**
  - [B station](https://www.bilibili.com/video/BV1bamVYLEZk)
- **2016-42**
  - [B station](https://www.bilibili.com/video/BV18amVYLEA5)
- **2016-43、44**
  - [B station](https://www.bilibili.com/video/BV18amVYLEPF)
- **2016-45**
  - [B station](https://www.bilibili.com/video/BV1bamVYLEfa)
- **2016-46**
  - [B station](https://www.bilibili.com/video/BV1gamVYjEwA)
- **2016-47**
  - [B station](https://www.bilibili.com/video/BV18amVYLEMk)
- **2016-48**
  - [B station](https://www.bilibili.com/video/BV18amVYjEvq)
- **2016-49**
  - [B station](https://www.bilibili.com/video/BV1bamVYLEfZ)
- **2016-50**
  - [B station](https://www.bilibili.com/video/BV18amVYLEAs)
- **2016-51**
  - [B station](https://www.bilibili.com/video/BV1SamVYLEiR)
- **2016-52、53**
  - [B station](https://www.bilibili.com/video/BV1SamVYLEtx)
- **2016-54、55**
  - [B station](https://www.bilibili.com/video/BV1Q4mVYUEBB)
- **2016论证有效性分析**
  - [B station](https://www.bilibili.com/video/BV1mB28YpE6F)
- **2016论说文**
  - [B station](https://www.bilibili.com/video/BV1xk28YSEc1)
- **2019逻辑选择**
  - [B station](https://www.bilibili.com/video/BV1Nk28YSExk)
- **2019-26**
  - [B station](https://www.bilibili.com/video/BV14czXYhEx5)
- **2019-27**
  - [B station](https://www.bilibili.com/video/BV12czXYhEDz)
- **2019-28**
  - [B station](https://www.bilibili.com/video/BV1KczXYhEQV)
- **2019-29**
  - [B station](https://www.bilibili.com/video/BV1xczXYhEXv)
- **2019-30&31**
  - [B station](https://www.bilibili.com/video/BV11czXYbEtr)
- **2019-32**
  - [B station](https://www.bilibili.com/video/BV1KczXYhEdo)
- **2019-33**
  - [B station](https://www.bilibili.com/video/BV1KczXYhEdX)
- **2019-34**
  - [B station](https://www.bilibili.com/video/BV1KczXYhEDF)
- **2019-35**
  - [B station](https://www.bilibili.com/video/BV1KczXYhEWV)
- **2019-36**
  - [B station](https://www.bilibili.com/video/BV1KczXYhERR)
- **2019-37**
  - [B station](https://www.bilibili.com/video/BV1TFzXYwEid)
- **2019-38**
  - [B station](https://www.bilibili.com/video/BV1TFzXYwEkA)
- **2019-39**
  - [B station](https://www.bilibili.com/video/BV14FzXYwEq8)
- **2019-40**
  - [B station](https://www.bilibili.com/video/BV14FzXYwEqM)
- **2019-41**
  - [B station](https://www.bilibili.com/video/BV14FzXYwEqz)
- **2019-42**
  - [B station](https://www.bilibili.com/video/BV1TFzXYwEzG)
- **2019-43**
  - [B station](https://www.bilibili.com/video/BV1tFzXYwEAs)
- **2019-44**
  - [B station](https://www.bilibili.com/video/BV1TFzXYwEvn)
- **2019-45**
  - [B station](https://www.bilibili.com/video/BV1tFzXYwEAd)
- **2019-46**
  - [B station](https://www.bilibili.com/video/BV14FzXYwEvw)
- **2019-47**
  - [B station](https://www.bilibili.com/video/BV14FzXYwEv1)
- **2019-48**
  - [B station](https://www.bilibili.com/video/BV1mFzXYwEP4)
- **2019-49&50**
  - [B station](https://www.bilibili.com/video/BV1NPzXYbEtG)
- **2019-51**
  - [B station](https://www.bilibili.com/video/BV1NPzXYbE4D)
- **2019-52**
  - [B station](https://www.bilibili.com/video/BV11PzXYbEsz)
- **2019-53**
  - [B station](https://www.bilibili.com/video/BV1xPzXYbEcm)
- **2019-54&55**
  - [B station](https://www.bilibili.com/video/BV1PPzXYbEfV)
- **2019论证有效性分析**
  - [B station](https://www.bilibili.com/video/BV1yk28YUEoN)
- **2019论说文**
  - [B station](https://www.bilibili.com/video/BV1Nk28YSE8v)
- **2021逻辑选择**
  - [B station](https://www.bilibili.com/video/BV1yk28YUERZ)
- **2021-26**
  - [B station](https://www.bilibili.com/video/BV1YYzFYZE2e)
- **2021-27**
  - [B station](https://www.bilibili.com/video/BV1EszFYNEKF)
- **2021-28**
  - [B station](https://www.bilibili.com/video/BV1ZszFYPErU)
- **2021-29**
  - [B station](https://www.bilibili.com/video/BV1ZszFYPEaT)
- **2021-30**
  - [B station](https://www.bilibili.com/video/BV1BszFYNE8g)
- **2021-31**
  - [B station](https://www.bilibili.com/video/BV1BszFYPEuj)
- **2021-32**
  - [B station](https://www.bilibili.com/video/BV1EszFYNEwm)
- **2021-33**
  - [B station](https://www.bilibili.com/video/BV1BszFYPEMa)
- **2021-34**
  - [B station](https://www.bilibili.com/video/BV1ZszFYPEkn)
- **2021-35**
  - [B station](https://www.bilibili.com/video/BV15azFY8EYc)
- **2021-36**
  - [B station](https://www.bilibili.com/video/BV1eazFYbEbd)
- **2021-37**
  - [B station](https://www.bilibili.com/video/BV15azFY8Ea8)
- **2021-38**
  - [B station](https://www.bilibili.com/video/BV1eazFYbEhi)
- **2021-39**
  - [B station](https://www.bilibili.com/video/BV1RazFYbENG)
- **2021-40&41**
  - [B station](https://www.bilibili.com/video/BV15azFY8EtQ)
- **2021-42**
  - [B station](https://www.bilibili.com/video/BV1eazFYbEv1)
- **2021-43**
  - [B station](https://www.bilibili.com/video/BV1eazFYbEvQ)
- **2021-44**
  - [B station](https://www.bilibili.com/video/BV19azFYbEot)
- **2021-45**
  - [B station](https://www.bilibili.com/video/BV1eazFYbEan)
- **2021-46**
  - [B station](https://www.bilibili.com/video/BV1RazFYbEN1)
- **2021-47&48**
  - [B station](https://www.bilibili.com/video/BV1eazFY8EdM)
- **2021-49**
  - [B station](https://www.bilibili.com/video/BV1eazFYbEBa)
- **2021-50**
  - [B station](https://www.bilibili.com/video/BV1eazFYbEqC)
- **2021-51**
  - [B station](https://www.bilibili.com/video/BV19azFYbEo9)
- **2021-52**
  - [B station](https://www.bilibili.com/video/BV1eazFY8EdN)
- **2021-53**
  - [B station](https://www.bilibili.com/video/BV19YzFYZELZ)
- **2021-54、55**
  - [B station](https://www.bilibili.com/video/BV1eYzFYfEu6)
- **2021论证有效性分析**
  - [B station](https://www.bilibili.com/video/BV1Nk28YSEbp)
- **2021论说文**
  - [B station](https://www.bilibili.com/video/BV1sk28YSER7)
- **2024逻辑选择**
  - [B station](https://www.bilibili.com/video/BV11k28YUEFo)
- **2024-26**
  - [B station](https://www.bilibili.com/video/BV1W9zFY5EHW)
- **2024-27**
  - [B station](https://www.bilibili.com/video/BV1xUzFYmEh6)
- **2024-28**
  - [B station](https://www.bilibili.com/video/BV12UzFYmEgy)
- **2024-28**
  - [B station](https://www.bilibili.com/video/BV12UzFYmEAM)
- **2024-29**
  - [B station](https://www.bilibili.com/video/BV1KUzFYUEhy)
- **2024-30**
  - [B station](https://www.bilibili.com/video/BV1xUzFYmEvn)
- **2024-32**
  - [B station](https://www.bilibili.com/video/BV1xUzFYmEzG)
- **2024-33**
  - [B station](https://www.bilibili.com/video/BV12UzFYmEAf)
- **2024-34**
  - [B station](https://www.bilibili.com/video/BV1wozFYVE9k)
- **2024-35&36**
  - [B station](https://www.bilibili.com/video/BV1pozFYGEFv)
- **2024-37**
  - [B station](https://www.bilibili.com/video/BV1HozFYGEoX)
- **2024-38**
  - [B station](https://www.bilibili.com/video/BV1pozFYGEwv)
- **2024-39**
  - [B station](https://www.bilibili.com/video/BV1pozFYGEKP)
- **2024-40**
  - [B station](https://www.bilibili.com/video/BV1kozFYGExb)
- **2024-41**
  - [B station](https://www.bilibili.com/video/BV1kozFYGEir)
- **2024-42**
  - [B station](https://www.bilibili.com/video/BV1HozFYGEfV)
- **2024-43**
  - [B station](https://www.bilibili.com/video/BV1pozFYGETp)
- **2024-44**
  - [B station](https://www.bilibili.com/video/BV1yQzFY1Evo)
- **2024-45**
  - [B station](https://www.bilibili.com/video/BV1yQzFY1ECd)
- **2024-46**
  - [B station](https://www.bilibili.com/video/BV1kozFYGEBw)
- **2024-47**
  - [B station](https://www.bilibili.com/video/BV1kozFYGEqx)
- **2024-48**
  - [B station](https://www.bilibili.com/video/BV1HZzFYrE7n)
- **2024-49**
  - [B station](https://www.bilibili.com/video/BV1HZzFYrEpN)
- **2024-50**
  - [B station](https://www.bilibili.com/video/BV1rZzFYrE12)
- **2024-51**
  - [B station](https://www.bilibili.com/video/BV1rZzFYrE2N)
- **2024-52**
  - [B station](https://www.bilibili.com/video/BV1HZzFYrEE8)
- **2024-53**
  - [B station](https://www.bilibili.com/video/BV1HZzFYrEp7)
- **2024-54、55**
  - [B station](https://www.bilibili.com/video/BV1W9zFY5E46)
- **2024论证有效性分析**
  - [B station](https://www.bilibili.com/video/BV1xk28YSEA5)
- **2024论说文**
  - [B station](https://www.bilibili.com/video/BV1Nk28YSEe8)
- **0.1三国志曹操传（序章）——何去何从**
  - [B station](https://www.bilibili.com/video/BV1ym4y1g7r5)
- **0.2三国志曹操传（序章）——颖川之战**
  - [B station](https://www.bilibili.com/video/BV1aj411t7ao)
- **0.3三国志曹操传（序章）——壮志雄心**
  - [B station](https://www.bilibili.com/video/BV1km4y1g7g1)
- **1.1三国志曹操传（第一章 霸王诞生）——董卓专权，首倡义兵**
  - [B station](https://www.bilibili.com/video/BV1Jy4y1N7Lo)
- **1.2三国志曹操传（第一章 霸王诞生）——汜水关之战**
  - [B station](https://www.bilibili.com/video/BV1PC4y157fE)
- **1.3三国志曹操传（第一章 霸王诞生）——军合力不齐，踌躇而雁行**
  - [B station](https://www.bilibili.com/video/BV12G411m7zu)
- **1.4三国志曹操传（第一章 霸王诞生）——虎牢关之战**
  - [B station](https://www.bilibili.com/video/BV1EC4y1577b)
- **1.5三国志曹操传（第一章 霸王诞生）——播越西迁移，号泣而且行**
  - [B station](https://www.bilibili.com/video/BV1kw411r7hy)
- **1.6三国志曹操传（第一章 霸王诞生）——董卓追击战**
  - [B station](https://www.bilibili.com/video/BV1hh4y1z7s3)
- **1.7三国志曹操传（第一章 霸王诞生）——盗贼如蚁聚，群雄皆鹰扬**
  - [B station](https://www.bilibili.com/video/BV1WN4y1y7bE)
- **1.8三国志曹操传（第一章 霸王诞生）——青州黄巾讨伐战**
  - [B station](https://www.bilibili.com/video/BV1Rj411s7ST)
- **1.9三国志曹操传（第一章 霸王诞生）——征讨陶谦，吕布偷袭**
  - [B station](https://www.bilibili.com/video/BV1wG411U7gs)
- **1.10三国志曹操传（第一章 霸王诞生）——徐州复仇战**
  - [B station](https://www.bilibili.com/video/BV1ew411A7rA)
- **1.11三国志曹操传（第一章 霸王诞生）——放弃进攻，回救濮阳**
  - [B station](https://www.bilibili.com/video/BV1894y187aY)
- **1.12三国志曹操传（第一章 霸王诞生）——濮阳之战壹**
  - [B station](https://www.bilibili.com/video/BV118411k719)
- **1.13三国志曹操传（第一章 霸王诞生）——似有内应，再战濮阳**
  - [B station](https://www.bilibili.com/video/BV1ow411k7jm)
- **1.14三国志曹操传（第一章 霸王诞生）——濮阳之战贰**
  - [B station](https://www.bilibili.com/video/BV1VG411U7ao)
- **1.15三国志曹操传（第一章 霸王诞生）——全力以赴，夺回濮阳**
  - [B station](https://www.bilibili.com/video/BV1w8411C798)
- **1.16三国志曹操传（第一章 霸王诞生）——濮阳之战叁**
  - [B station](https://www.bilibili.com/video/BV1ew411A7Sr)
- **1.17三国志曹操传（第一章 霸王诞生）——奉天子以令不臣**
  - [B station](https://www.bilibili.com/video/BV1N84y127vB)
- **1.18三国志曹操传（第一章 霸王诞生）——献帝救出战**
  - [B station](https://www.bilibili.com/video/BV1384y127E8)
- **1.19三国志曹操传（第一章 霸王诞生）——一征张绣，得意忘形**
  - [B station](https://www.bilibili.com/video/BV1Wj411v7zm)
- **1.20三国志曹操传（第一章 霸王诞生）——张绣讨伐战壹（典韦殒命）**
  - [B station](https://www.bilibili.com/video/BV1nN4y1C7Fj)
- **1.21三国志曹操传（第一章 霸王诞生）——张绣讨伐战壹（典韦存活）**
  - [B station](https://www.bilibili.com/video/BV1gw411X74g)
- **1.22三国志曹操传（第一章 霸王诞生）——淮南弟称号**
  - [B station](https://www.bilibili.com/video/BV15H4y1d7eH)
- **1.23三国志曹操传（第一章 霸王诞生）——袁术讨伐战**
  - [B station](https://www.bilibili.com/video/BV1Sh4y1q7P4)
- **1.24三国志曹操传（第一章 霸王诞生）——卷土重来，二征张绣**
  - [B station](https://www.bilibili.com/video/BV1Jy4y1K7Hh)
- **1.25三国志曹操传（第一章 霸王诞生）——张绣讨伐战贰**
  - [B station](https://www.bilibili.com/video/BV1rh4y1q7JF)
- **1.26三国志曹操传（第一章 霸王诞生）——救援刘备，消灭吕布**
  - [B station](https://www.bilibili.com/video/BV1Hy4y1K7mT)
- **1.27三国志曹操传（第一章 霸王诞生）——徐州救援战**
  - [B station](https://www.bilibili.com/video/BV1ZC4y1G7F1)
- **1.28三国志曹操传（第一章 霸王诞生）——天寒地冻，围攻下邳**
  - [B station](https://www.bilibili.com/video/BV1A94y1b7NV)
- **1.29三国志曹操传（第一章 霸王诞生）——吕布包围战**
  - [B station](https://www.bilibili.com/video/BV19C4y1G7cC)
- **1.30三国志曹操传（第一章 霸王诞生）——吕布授首，中原统一**
  - [B station](https://www.bilibili.com/video/BV1Nh4y1B78f)
- **2.1三国志曹操传（第二章 河北之争）——放虎归山，张绣来降**
  - [B station](https://www.bilibili.com/video/BV1Sj411a7J4)
- **2.2三国志曹操传（第二章 河北之争）——徐州入侵战**
  - [B station](https://www.bilibili.com/video/BV1LC4y1H7Ye)
- **2.3三国志曹操传（第二章 河北之争）——身在曹营心在刘**
  - [B station](https://www.bilibili.com/video/BV1P94y1L7Lh)
- **2.4三国志曹操传（第二章 河北之争）——白马之战**
  - [B station](https://www.bilibili.com/video/BV1DN4y167DT)
- **2.5三国志曹操传（第二章 河北之争）——已斩颜良，待诛文丑**
  - [B station](https://www.bilibili.com/video/BV1du4y1j7gG)
- **2.6三国志曹操传（第二章 河北之争）——延津之战**
  - [B station](https://www.bilibili.com/video/BV11z4y1N7hZ)
- **2.7三国志曹操传（第二章 河北之争）——送别关羽，直面生死**
  - [B station](https://www.bilibili.com/video/BV19H4y1z73n)
- **2.8三国志曹操传（第二章 河北之争）——官渡之战**
  - [B station](https://www.bilibili.com/video/BV1a94y1G7Pt)
- **2.9三国志曹操传（第二章 河北之争）——一战功成，袁氏溃败**
  - [B station](https://www.bilibili.com/video/BV1JG411X7L9)
- **2.10三国志曹操传（第二章 河北之争）——宜将剩勇追穷寇**
  - [B station](https://www.bilibili.com/video/BV1DC4y1E7Do)
- **2.11三国志曹操传（第二章 河北之争）——袁绍殒命，往事如烟**
  - [B station](https://www.bilibili.com/video/BV1Aw411M7Zx)
- **2.12三国志曹操传（第二章 河北之争）——忙里偷闲，闪击刘备**
  - [B station](https://www.bilibili.com/video/BV13Q4y1p7kS)
- **2.13三国志曹操传（第二章 河北之争）——穰山之战**
  - [B station](https://www.bilibili.com/video/BV1Ke411R7si)
- **2.14三国志曹操传（第二章 河北之争）——刘备败逃，再击袁氏**
  - [B station](https://www.bilibili.com/video/BV1Uu4y1h7CN)
- **2.15三国志曹操传（第二章 河北之争）——黎阳之战**
  - [B station](https://www.bilibili.com/video/BV1v94y1G7D5)
- **2.16三国志曹操传（第二章 河北之争）——一鼓作气，拿下邺城**
  - [B station](https://www.bilibili.com/video/BV12e411Q7Lm)
- **2.17三国志曹操传（第二章 河北之争）——邺城之战**
  - [B station](https://www.bilibili.com/video/BV1TN4y1r7Mj)
- **2.18三国志曹操传（第二章 河北之争）——兄弟内讧，渔翁得利**
  - [B station](https://www.bilibili.com/video/BV1uM411Q7Fm)
- **2.19三国志曹操传（第二章 河北之争）——南皮攻略战**
  - [B station](https://www.bilibili.com/video/BV1cw411M7qy)
- **2.20三国志曹操传（第二章 河北之争）——出其不意，奔袭乌丸**
  - [B station](https://www.bilibili.com/video/BV1n84y197MT)
- **2.21三国志曹操传（第二章 河北之争）——柳城平定战（郭嘉殒命）**
  - [B station](https://www.bilibili.com/video/BV1uu4y17732)
- **2.22三国志曹操传（第二章 河北之争）——柳城平定战（郭嘉存活）**
  - [B station](https://www.bilibili.com/video/BV1yH4y1z7Le)
- **2.23三国志曹操传（第二章 河北之争）——袁氏灭亡，北方统一**
  - [B station](https://www.bilibili.com/video/BV1B94y1G7su)
- **3.1三国志曹操传（第三章 三国鼎立）——卧龙出山，国士无双**
  - [B station](https://www.bilibili.com/video/BV1zG411S7h1)
- **3.2三国志曹操传（第三章 三国鼎立）——博望坡之战**
  - [B station](https://www.bilibili.com/video/BV1Bv411F7vA)
- **3.3三国志曹操传（第三章 三国鼎立）——南下灭刘，鲸吞荆州**
  - [B station](https://www.bilibili.com/video/BV1wC4y1j7Lj)
- **3.4三国志曹操传（第三章 三国鼎立）——长坂坡之战**
  - [B station](https://www.bilibili.com/video/BV1Lu4y1b7Hv)
- **3.5三国志曹操传（第三章 三国鼎立）——孙刘联盟，南北对抗**
  - [B station](https://www.bilibili.com/video/BV1wG411X7vq)
- **3.6三国志曹操传（第三章 三国鼎立）——赤壁之战（全灭敌军）**
  - [B station](https://www.bilibili.com/video/BV1cG411X7C3)
- **3.7三国志曹操传（第三章 三国鼎立）——赤壁之战（仓皇撤退）**
  - [B station](https://www.bilibili.com/video/BV17u4y1b7TK)
- **3.8三国志曹操传（第三章 三国鼎立）——败走华容**
  - [B station](https://www.bilibili.com/video/BV1ma4y1S76v)
- **3.9三国志曹操传（第三章 三国鼎立）——赤壁突围战**
  - [B station](https://www.bilibili.com/video/BV1Uv411F7hj)
- **3.10三国志曹操传（第三章 三国鼎立）——操撤兵北归，权兵临合肥**
  - [B station](https://www.bilibili.com/video/BV1ru4y1A7Dy)
- **3.11三国志曹操传（第三章 三国鼎立）——合肥之战**
  - [B station](https://www.bilibili.com/video/BV1yQ4y1t7GN)
- **3.12三国志曹操传（第三章 三国鼎立）——进军关中，消灭马超**
  - [B station](https://www.bilibili.com/video/BV1dC4y127Ck)
- **3.13三国志曹操传（第三章 三国鼎立）——马超迎击战**
  - [B station](https://www.bilibili.com/video/BV16G411S7bH)
- **3.14三国志曹操传（第三章 三国鼎立）——得寸进尺，剑指汉中**
  - [B station](https://www.bilibili.com/video/BV19G411S7Di)
- **3.15三国志曹操传（第三章 三国鼎立）——张鲁讨伐战**
  - [B station](https://www.bilibili.com/video/BV1bz4y1w7DJ)
- **3.16三国志曹操传（第三章 三国鼎立）——得陇不望蜀，孙刘再携手**
  - [B station](https://www.bilibili.com/video/BV1iC4y1274c)
- **3.17三国志曹操传（第三章 三国鼎立）——逍遥津之战**
  - [B station](https://www.bilibili.com/video/BV1v94y1n7TU)
- **3.18三国志曹操传（第三章 三国鼎立）——最后一次南征**
  - [B station](https://www.bilibili.com/video/BV1Ua4y1m7Rt)
- **3.19三国志曹操传（第三章 三国鼎立）——濡须口之战**
  - [B station](https://www.bilibili.com/video/BV1yN411M7wM)
- **3.20三国志曹操传（第三章 三国鼎立）——势均力敌，鼎足三分**
  - [B station](https://www.bilibili.com/video/BV1Ug4y1Q7Ji)
- **4.1三国志曹操传（终章 天下统一）——天下英雄唯使君与操尔**
  - [B station](https://www.bilibili.com/video/BV1Mz4y1A7bw)
- **4.2三国志曹操传（终章 天下统一）——定军山之战（全灭敌军）**
  - [B station](https://www.bilibili.com/video/BV1ej411E7kn)
- **4.3三国志曹操传（终章 天下统一）——定军山之战（夏侯渊殒命）**
  - [B station](https://www.bilibili.com/video/BV1qg4y1Q7Zo)
- **4.4三国志曹操传（终章 天下统一）——最后一次西征**
  - [B station](https://www.bilibili.com/video/BV17e411Q76b)
- **4.5三国志曹操传（终章 天下统一）——汉水之战**
  - [B station](https://www.bilibili.com/video/BV1Wu411F7FM)
- **4.6三国志曹操传（终章 天下统一）——一生的对手**
  - [B station](https://www.bilibili.com/video/BV1Lw411N7U1)
- **4.7三国志曹操传（终章 天下统一）——斜谷之战**
  - [B station](https://www.bilibili.com/video/BV16b4y1g7kT)
- **4.8三国志曹操传（终章 天下统一）——水淹七军，威震华夏**
  - [B station](https://www.bilibili.com/video/BV1Sv411F7tk)
- **4.9三国志曹操传（终章 天下统一）——樊城救援战（庞德殒命）**
  - [B station](https://www.bilibili.com/video/BV16b4y1g7VL)
- **4.10三国志曹操传（终章 天下统一）——忠肝义胆，英雄相惜**
  - [B station](https://www.bilibili.com/video/BV1eC4y1E7d5)
- **4.11三国志曹操传（终章 天下统一）——若天命在吾，吾为周文王矣**
  - [B station](https://www.bilibili.com/video/BV1su4y1b76j)
- **5.1三国志曹操传（他不知道的事）——英雄的落幕**
  - [B station](https://www.bilibili.com/video/BV1ZG411S7c6)
- **5.2三国志曹操传（心中永远的遗憾）——老骥伏枥，志在千里，烈士暮年，壮心不已。山不厌高，海不厌深，周公吐哺，天下归心。**
  - [B station](https://www.bilibili.com/video/BV1qw411W7iP)
- **1.2024研究生入学考试数学冲刺阶段考点串讲——导学篇（独孤九剑总章）**
  - [B station](https://www.bilibili.com/video/BV1Gh4y1676V)
- **2.1.2024考研高等数学冲刺串讲——函数的有界性、奇偶性、单调性、周期性1**
  - [B station](https://www.bilibili.com/video/BV1AC4y1Z7vV)
- **2.2.2024考研高等数学冲刺串讲——函数的有界性、奇偶性、单调性、周期性2（复合函数例题）**
  - [B station](https://www.bilibili.com/video/BV1Fz4y1F7Qi)
- **2.3.2024考研高等数学冲刺串讲——函数的有界性、奇偶性、单调性、周期性3（单调性、奇偶性例题）**
  - [B station](https://www.bilibili.com/video/BV1CC4y1L7mJ)
- **2.4.2024考研高等数学冲刺串讲——函数的有界性、奇偶性、单调性、周期性4（有界性例题）**
  - [B station](https://www.bilibili.com/video/BV11w411a7BK)
- **2.5.2024考研高等数学冲刺串讲——函数的有界性、奇偶性、单调性、周期性5（周期性例题）**
  - [B station](https://www.bilibili.com/video/BV1N94y1a78m)
- **2.6.2024考研高等数学冲刺串讲——常考函数、参数方程与极坐标方程**
  - [B station](https://www.bilibili.com/video/BV1wH4y1o7Ds)
- **2.7.2024考研高等数学冲刺串讲——常考数列与不等式**
  - [B station](https://www.bilibili.com/video/BV1J8411k79K)
- **2.8.2024考研高等数学冲刺串讲——常考数列与不等式（1.数学归纳法；2.柯西不等式）**
  - [B station](https://www.bilibili.com/video/BV178411k7cP)
- **2.8.2024考研高等数学冲刺串讲——常考数列与不等式（3.常用放缩公式；4.看起来不是不等式的不等式问题）**
  - [B station](https://www.bilibili.com/video/BV1rj41147ja)
- **2.8.2024考研高等数学冲刺串讲——常考数列与不等式（5.“经典名菜”品鉴）**
  - [B station](https://www.bilibili.com/video/BV1Nm4y1g7GJ)
- **3.1.2024考研高等数学冲刺串讲——极限与连续（考点梳理）**
  - [B station](https://www.bilibili.com/video/BV14Q4y1s7w7)
- **3.2.2024考研高等数学冲刺串讲——极限与连续（极限的计算）**
  - [B station](https://www.bilibili.com/video/BV19u4y1p7Ai)
- **3.3.2024考研高等数学冲刺串讲——极限与连续（有关极限定义的问题）**
  - [B station](https://www.bilibili.com/video/BV1bC4y137Bj)
- **3.4.2024考研高等数学冲刺串讲——极限与连续（夹逼定理与单调有界准则）**
  - [B station](https://www.bilibili.com/video/BV1HN411s7VY)
- **3.5.2024考研高等数学冲刺串讲——极限与连续（“经典名菜”品鉴）**
  - [B station](https://www.bilibili.com/video/BV1ce411X7Z8)
- **上海交大大模型智能体课程第1讲：初探大模型智能体**
  - [B station](https://www.bilibili.com/video/BV1UgvYBtEaa)
- **上海交大大模型智能体课程第2讲：生成式大语言模型**
  - [B station](https://www.bilibili.com/video/BV1bgvYBtEbk)
- **上海交大大模型智能体课程第3讲：提示工程**
  - [B station](https://www.bilibili.com/video/BV1bgvYBtECs)
- **上海交大大模型智能体课程第4讲：智能体评估**
  - [B station](https://www.bilibili.com/video/BV1YAvYBAETJ)
- **上海交大大模型智能体课程第5讲：智能体架构概览**
  - [B station](https://www.bilibili.com/video/BV1YAvYBAEHH)
- **上海交大大模型智能体课程第6讲：记忆管理与检索增强**
  - [B station](https://www.bilibili.com/video/BV1XAvYBAEXS)
- **上海交大大模型智能体课程第7讲：外部工具调用**
  - [B station](https://www.bilibili.com/video/BV1VAvYBPEFW)
- **上海交大大模型智能体课程第8讲：推理、规划和树搜索增强**
  - [B station](https://www.bilibili.com/video/BV1GAvYBPE9J)
- **上海交大大模型智能体课程第9讲：指令微调**
  - [B station](https://www.bilibili.com/video/BV1YAvYBAEET)
- **上海交大大模型智能体课程第10讲：LoRA微调与模型量化**
  - [B station](https://www.bilibili.com/video/BV1YAvYBAEcM)
- **上海交大大模型智能体课程第11讲：针对AI智能体的强化微调**
  - [B station](https://www.bilibili.com/video/BV1YAvYBAEHU)
- **上海交大大模型智能体课程第12讲：多模态智能体**
  - [B station](https://www.bilibili.com/video/BV1XAvYBAEaC)
- **上海交大大模型智能体课程第13讲：基于大语言模型的多智能体系统**
  - [B station](https://www.bilibili.com/video/BV1XAvYBAEQw)
- **上海交大大模型智能体课程第14讲：智能体攻防**
  - [B station](https://www.bilibili.com/video/BV19cvYBeEWt)
- **上海交大大模型智能体课程第15讲：智能体通信协议**
  - [B station](https://www.bilibili.com/video/BV1YcvYBeEpE)
- **HugWBC：让人形机器人蹦跶起来！**
  - [B station](https://www.bilibili.com/video/BV13UNGe4Etn)
  - links: https://hugwbc.github.io/ https://arxiv.org/abs/2502.03206
- **OmniH2O：人形机器人全身控制遥操作学习框架**
  - [B station](https://www.bilibili.com/video/BV1Y5KsewEdD)
  - links: https://omni.human2humanoid.com/ https://arxiv.org/abs/2406.08858
- **BeamDojo：人形机器人走梅花桩啦！**
  - [B station](https://www.bilibili.com/video/BV1bAAtexEoB)
  - links: https://arxiv.org/abs/2502.10363 https://why618188.github.io/beamdojo/
- **RHINO：让人形机器人学会交互！**
  - [B station](https://www.bilibili.com/video/BV18AAtexEpk)
  - links: https://arxiv.org/abs/2502.13134
- **跨具身人形运动：一脑多形**
  - [B station](https://www.bilibili.com/video/BV11f8nztEia)
- **上海交大张伟楠机器学习课程第1讲：机器学习简介I**
  - [B station](https://www.bilibili.com/video/BV1L5S2Y9ESV)
  - links: https://wnzhang.net/teaching/sjtu-ml-2024/index.html https://wnzhang.net/teaching/sjtu-ml-2024/slides/1-ml-intro.pdf
- **上海交大张伟楠强化学习课程第1讲：机器学习简介II**
  - [B station](https://www.bilibili.com/video/BV16TS2YbE1q)
  - links: https://wnzhang.net/teaching/sjtu-ml-2024/index.html https://wnzhang.net/teaching/sjtu-ml-2024/slides/1-ml-intro.pdf
- **上海交大张伟楠机器学习课程第1讲：机器学习简介III**
  - [B station](https://www.bilibili.com/video/BV1cKS2YFEbC)
  - links: https://wnzhang.net/teaching/sjtu-ml-2024/index.html https://wnzhang.net/teaching/sjtu-ml-2024/slides/1-ml-intro.pdf
- **上海交大张伟楠机器学习课程第1讲：机器学习简介IV**
  - [B station](https://www.bilibili.com/video/BV1fgS2YxEEM)
  - links: https://wnzhang.net/teaching/sjtu-ml-2024/index.html https://wnzhang.net/teaching/sjtu-ml-2024/slides/1-ml-intro.pdf
- **上海交大张伟楠机器学习课程第1讲：机器学习简介V**
  - [B station](https://www.bilibili.com/video/BV1hcUNYtExa)
  - links: https://wnzhang.net/teaching/sjtu-ml-2024/index.html https://wnzhang.net/teaching/sjtu-ml-2024/slides/1-ml-intro.pdf
- **上海交大张伟楠机器学习课程第2讲：线性模型I**
  - [B station](https://www.bilibili.com/video/BV1A4UnYdEG6)
  - links: https://wnzhang.net/teaching/sjtu-ml-2024/index.html https://wnzhang.net/teaching/sjtu-ml-2024/slides/2-linear-models.pdf
- **上海交大张伟楠机器学习课程第2讲：线性模型II**
  - [B station](https://www.bilibili.com/video/BV1p4UnYdEYN)
  - links: https://wnzhang.net/teaching/sjtu-ml-2024/index.html https://wnzhang.net/teaching/sjtu-ml-2024/slides/2-linear-models.pdf
- **上海交大张伟楠机器学习课程第2讲：线性模型III**
  - [B station](https://www.bilibili.com/video/BV1A4UnYdE3b)
  - links: https://wnzhang.net/teaching/sjtu-ml-2024/index.html https://wnzhang.net/teaching/sjtu-ml-2024/slides/2-linear-models.pdf
- **上海交大张伟楠机器学习课程第2讲：线性模型IV**
  - [B station](https://www.bilibili.com/video/BV1p4UnYdErP)
  - links: https://wnzhang.net/teaching/sjtu-ml-2024/index.html https://wnzhang.net/teaching/sjtu-ml-2024/slides/2-linear-models.pdf
- **上海交大张伟楠机器学习课程第2讲：线性模型V**
  - [B station](https://www.bilibili.com/video/BV1A4UnYdET4)
  - links: https://wnzhang.net/teaching/sjtu-ml-2024/index.html https://wnzhang.net/teaching/sjtu-ml-2024/slides/2-linear-models.pdf
- **上海交大张伟楠机器学习课程第3讲：K近邻算法与双线性模型I**
  - [B station](https://www.bilibili.com/video/BV1RiB8Y5Emz)
  - links: https://wnzhang.net/teaching/sjtu-ml-2024/index.html https://wnzhang.net/teaching/sjtu-ml-2024/slides/3-knn-bilinear.pdf
- **上海交大张伟楠机器学习课程第3讲：K近邻算法与双线性模型II**
  - [B station](https://www.bilibili.com/video/BV1ViB8YVERU)
  - links: https://wnzhang.net/teaching/sjtu-ml-2024/index.html https://wnzhang.net/teaching/sjtu-ml-2024/slides/3-knn-bilinear.pdf
- **上海交大张伟楠机器学习课程第3讲：K近邻算法与双线性模型III**
  - [B station](https://www.bilibili.com/video/BV1viB8YLESe)
  - links: https://wnzhang.net/teaching/sjtu-ml-2024/index.html https://wnzhang.net/teaching/sjtu-ml-2024/slides/3-knn-bilinear.pdf
- **上海交大张伟楠机器学习课程第4讲：人工神经网络I**
  - [B station](https://www.bilibili.com/video/BV1zuzxYgEAs)
  - links: https://wnzhang.net/teaching/sjtu-ml-2024/index.html https://wnzhang.net/teaching/sjtu-ml-2024/slides/4-ann.pdf
- **上海交大张伟楠机器学习课程第4讲：人工神经网络II**
  - [B station](https://www.bilibili.com/video/BV1BuzxYgEho)
  - links: https://wnzhang.net/teaching/sjtu-ml-2024/index.html https://wnzhang.net/teaching/sjtu-ml-2024/slides/4-ann.pdf
- **上海交大张伟楠机器学习课程第4讲：人工神经网络III**
  - [B station](https://www.bilibili.com/video/BV1EuzxY3EaY)
  - links: https://wnzhang.net/teaching/sjtu-ml-2024/index.html https://wnzhang.net/teaching/sjtu-ml-2024/slides/4-ann.pdf
- **上海交大张伟楠机器学习课程第4讲：人工神经网络IV**
  - [B station](https://www.bilibili.com/video/BV1r5i1YoEuf)
  - links: https://wnzhang.net/teaching/sjtu-ml-2024/index.html https://wnzhang.net/teaching/sjtu-ml-2024/slides/4-ann.pdf
- **上海交大张伟楠机器学习课程第4讲：人工神经网络V**
  - [B station](https://www.bilibili.com/video/BV165i1YoEQQ)
  - links: https://wnzhang.net/teaching/sjtu-ml-2024/index.html https://wnzhang.net/teaching/sjtu-ml-2024/slides/4-ann.pdf
- **上海交大张伟楠机器学习课程第4讲：人工神经网络VI**
  - [B station](https://www.bilibili.com/video/BV165i1YoEmF)
  - links: https://wnzhang.net/teaching/sjtu-ml-2024/index.html https://wnzhang.net/teaching/sjtu-ml-2024/slides/4-ann.pdf
- **上海交大张伟楠机器学习课程第5讲：支持向量机I**
  - [B station](https://www.bilibili.com/video/BV1QKBFYpE2A)
  - links: https://wnzhang.net/teaching/sjtu-ml-2024/index.html https://wnzhang.net/teaching/sjtu-ml-2024/slides/5-svm.pdf
- **上海交大张伟楠机器学习课程第5讲：支持向量机II**
  - [B station](https://www.bilibili.com/video/BV1XKBFYpE2c)
  - links: https://wnzhang.net/teaching/sjtu-ml-2024/index.html https://wnzhang.net/teaching/sjtu-ml-2024/slides/5-svm.pdf
- **上海交大张伟楠机器学习课程第5讲：支持向量机III**
  - [B station](https://www.bilibili.com/video/BV1XKBFYpEhM)
  - links: https://wnzhang.net/teaching/sjtu-ml-2024/index.html https://wnzhang.net/teaching/sjtu-ml-2024/slides/5-svm.pdf
- **上海交大张伟楠机器学习课程第6讲：决策树I**
  - [B station](https://www.bilibili.com/video/BV1pUkUYXEiQ)
  - links: https://wnzhang.net/teaching/sjtu-ml-2024/index.html https://wnzhang.net/teaching/sjtu-ml-2024/slides/6-tree-models.pdf
- **上海交大张伟楠机器学习课程第6讲：决策树II**
  - [B station](https://www.bilibili.com/video/BV1pUkUYXEHQ)
  - links: https://wnzhang.net/teaching/sjtu-ml-2024/index.html https://wnzhang.net/teaching/sjtu-ml-2024/slides/6-tree-models.pdf
- **上海交大张伟楠机器学习课程第6讲：决策树III**
  - [B station](https://www.bilibili.com/video/BV1pUkUYXE4Q)
  - links: https://wnzhang.net/teaching/sjtu-ml-2024/index.html https://wnzhang.net/teaching/sjtu-ml-2024/slides/6-tree-models.pdf
- **上海交大张伟楠机器学习课程第7讲：集成学习与森林模型I**
  - [B station](https://www.bilibili.com/video/BV17o6eYPEtB)
  - links: https://wnzhang.net/teaching/sjtu-ml-2024/index.html https://wnzhang.net/teaching/sjtu-ml-2024/slides/7-ensemble.pdf
- **上海交大张伟楠机器学习课程第7讲：集成学习与森林模型II**
  - [B station](https://www.bilibili.com/video/BV17o6eYPEb3)
  - links: https://wnzhang.net/teaching/sjtu-ml-2024/index.html https://wnzhang.net/teaching/sjtu-ml-2024/slides/7-ensemble.pdf
- **上海交大张伟楠机器学习课程第7讲：集成学习与森林模型III**
  - [B station](https://www.bilibili.com/video/BV1nU6eYzExT)
  - links: https://wnzhang.net/teaching/sjtu-ml-2024/index.html https://wnzhang.net/teaching/sjtu-ml-2024/slides/7-ensemble.pdf
- **上海交大张伟楠机器学习课程第8讲：概率图模型I**
  - [B station](https://www.bilibili.com/video/BV1NNrgY1EWF)
  - links: https://wnzhang.net/teaching/sjtu-ml-2024/index.html https://wnzhang.net/teaching/sjtu-ml-2024/slides/8-pgm.pdf
- **上海交大张伟楠机器学习课程第8讲：概率图模型II**
  - [B station](https://www.bilibili.com/video/BV11NrgYyEGH)
  - links: https://wnzhang.net/teaching/sjtu-ml-2024/index.html https://wnzhang.net/teaching/sjtu-ml-2024/slides/8-pgm.pdf
- **上海交大张伟楠机器学习课程第8讲：概率图模型III**
  - [B station](https://www.bilibili.com/video/BV1yNrgYyEr3)
  - links: https://wnzhang.net/teaching/sjtu-ml-2024/index.html https://wnzhang.net/teaching/sjtu-ml-2024/slides/8-pgm.pdf
- **上海交大张伟楠机器学习课程第9讲：无监督学习I**
  - [B station](https://www.bilibili.com/video/BV1ancNeZEXt)
  - links: https://wnzhang.net/teaching/sjtu-ml-2024/index.html https://wnzhang.net/teaching/sjtu-ml-2024/slides/9-unsupervised.pdf
- **上海交大张伟楠机器学习课程第9讲：无监督学习II**
  - [B station](https://www.bilibili.com/video/BV1ancNeZE2Y)
  - links: https://wnzhang.net/teaching/sjtu-ml-2024/index.html https://wnzhang.net/teaching/sjtu-ml-2024/slides/9-unsupervised.pdf
- **上海交大张伟楠机器学习课程第9讲：无监督学习III**
  - [B station](https://www.bilibili.com/video/BV1GncNeZEpS)
  - links: https://wnzhang.net/teaching/sjtu-ml-2024/index.html https://wnzhang.net/teaching/sjtu-ml-2024/slides/9-unsupervised.pdf
- **上海交大张伟楠机器学习课程第9讲：无监督学习IV**
  - [B station](https://www.bilibili.com/video/BV1HowkeQEzS)
  - links: https://wnzhang.net/teaching/sjtu-ml-2024/index.html https://wnzhang.net/teaching/sjtu-ml-2024/slides/9-unsupervised.pdf
- **上海交大张伟楠机器学习课程第9讲：无监督学习V**
  - [B station](https://www.bilibili.com/video/BV1powkeQENk)
  - links: https://wnzhang.net/teaching/sjtu-ml-2024/index.html https://wnzhang.net/teaching/sjtu-ml-2024/slides/9-unsupervised.pdf
- **上海交大张伟楠机器学习课程第10讲：学习理论与模型选择I**
  - [B station](https://www.bilibili.com/video/BV1jpFNeYEdS)
  - links: https://wnzhang.net/teaching/sjtu-ml-2024/index.html https://wnzhang.net/teaching/sjtu-ml-2024/slides/10-ltms.pdf
- **上海交大张伟楠机器学习课程第10讲：学习理论与模型选择II**
  - [B station](https://www.bilibili.com/video/BV17pFNeYET2)
  - links: https://wnzhang.net/teaching/sjtu-ml-2024/index.html https://wnzhang.net/teaching/sjtu-ml-2024/slides/10-ltms.pdf
- **上海交大张伟楠机器学习课程第10讲：学习理论与模型选择III**
  - [B station](https://www.bilibili.com/video/BV17HFNePEzX)
  - links: https://wnzhang.net/teaching/sjtu-ml-2024/index.html https://wnzhang.net/teaching/sjtu-ml-2024/slides/10-ltms.pdf
- **上海交大张伟楠机器学习课程第11讲：迁移、多任务、元学习I**
  - [B station](https://www.bilibili.com/video/BV1sHfzYMETB)
  - links: https://wnzhang.net/teaching/sjtu-ml-2024/index.html https://wnzhang.net/teaching/sjtu-ml-2024/slides/11-multitask-meta.pdf
- **上海交大张伟楠机器学习课程第11讲：迁移、多任务、元学习II**
  - [B station](https://www.bilibili.com/video/BV1sHfzYMEJH)
  - links: https://wnzhang.net/teaching/sjtu-ml-2024/index.html https://wnzhang.net/teaching/sjtu-ml-2024/slides/11-multitask-meta.pdf
- **上海交大张伟楠机器学习课程第11讲：迁移、多任务、元学习III**
  - [B station](https://www.bilibili.com/video/BV1yHfzYMEya)
  - links: https://wnzhang.net/teaching/sjtu-ml-2024/index.html https://wnzhang.net/teaching/sjtu-ml-2024/slides/11-multitask-meta.pdf
- **上海交大张伟楠机器学习课程第12讲：机器学习前沿话题漫谈**
  - [B station](https://www.bilibili.com/video/BV1tVfzYCERh)
  - links: https://wnzhang.net/teaching/sjtu-ml-2024/index.html https://wnzhang.net/teaching/sjtu-ml-2024/slides/11-multitask-meta.pdf
- **RLChina 2024 | 3小时强化学习入门课程-上**
  - [B station](https://www.bilibili.com/video/BV1yFm1Y4Evf)
  - links: https://wnzhang.net/teaching/sjtu-rl-2024/slides/rl-turorial-3h-rlchina2024.pdf
- **RLChina 2024 | 3小时强化学习入门课程-下**
  - [B station](https://www.bilibili.com/video/BV1yFm1Y4Eiy)
  - links: https://wnzhang.net/teaching/sjtu-rl-2024/slides/rl-turorial-3h-rlchina2024.pdf
- **上海交大张伟楠强化学习课程第1讲：强化学习简介I**
  - [B station](https://www.bilibili.com/video/BV1jUHdePEUZ)
  - links: https://wnzhang.net/teaching/sjtu-rl-2024/index.html https://wnzhang.net/teaching/sjtu-rl-2024/slides/1-rl-intro.pdf
- **上海交大张伟楠强化学习课程第1讲：强化学习简介II**
  - [B station](https://www.bilibili.com/video/BV1LSHdeYEQJ)
  - links: https://wnzhang.net/teaching/sjtu-rl-2024/index.html https://wnzhang.net/teaching/sjtu-rl-2024/slides/1-rl-intro.pdf
- **上海交大张伟楠强化学习课程第1讲：强化学习简介III**
  - [B station](https://www.bilibili.com/video/BV1LSHdeYEsv)
  - links: https://wnzhang.net/teaching/sjtu-rl-2024/index.html https://wnzhang.net/teaching/sjtu-rl-2024/slides/1-rl-intro.pdf
- **上海交大张伟楠强化学习课程第2讲：探索与利用**
  - [B station](https://www.bilibili.com/video/BV1jaHfekE2U)
  - links: https://wnzhang.net/teaching/sjtu-rl-2024/index.html https://wnzhang.net/teaching/sjtu-rl-2024/slides/1-rl-intro.pdf
- **上海交大张伟楠强化学习课程第3讲：马尔可夫决策过程I**
  - [B station](https://www.bilibili.com/video/BV1ZaHfekEyL)
  - links: https://wnzhang.net/teaching/sjtu-rl-2024/index.html https://wnzhang.net/teaching/sjtu-rl-2024/slides/2-mdp-dp.pdf
- **上海交大张伟楠强化学习课程第3讲：马尔可夫决策过程II**
  - [B station](https://www.bilibili.com/video/BV1D2HfewEmk)
  - links: https://wnzhang.net/teaching/sjtu-rl-2024/index.html https://wnzhang.net/teaching/sjtu-rl-2024/slides/2-mdp-dp.pdf
- **上海交大张伟楠强化学习课程第4讲：动态规划**
  - [B station](https://www.bilibili.com/video/BV1S2HfewEQa)
  - links: https://wnzhang.net/teaching/sjtu-rl-2024/index.html https://wnzhang.net/teaching/sjtu-rl-2024/slides/2-mdp-dp.pdf
- **上海交大张伟楠强化学习课程第5讲：值函数估计I**
  - [B station](https://www.bilibili.com/video/BV13yHfeeEo2)
  - links: https://wnzhang.net/teaching/sjtu-rl-2024/index.html https://wnzhang.net/tutorials/sjtu-rl-2024/slides/3-value-est.pdf
- **上海交大张伟楠强化学习课程第5讲：值函数估计II**
  - [B station](https://www.bilibili.com/video/BV1QyHfeYEPY)
  - links: https://wnzhang.net/teaching/sjtu-rl-2024/index.html https://wnzhang.net/teaching/sjtu-rl-2024/slides/3-value-est.pdf
- **上海交大张伟楠强化学习课程第6讲：无模型控制方法I**
  - [B station](https://www.bilibili.com/video/BV1USHfeFEZV)
  - links: https://wnzhang.net/teaching/sjtu-rl-2024/index.html https://wnzhang.net/teaching/sjtu-rl-2024/slides/4-model-free-control.pdf
- **上海交大张伟楠强化学习课程第6讲：无模型控制方法II**
  - [B station](https://www.bilibili.com/video/BV1SmHfehE3E)
  - links: https://wnzhang.net/teaching/sjtu-rl-2024/index.html https://wnzhang.net/teaching/sjtu-rl-2024/slides/4-model-free-control.pdf
- **上海交大张伟楠强化学习课程第7讲：规划与学习I**
  - [B station](https://www.bilibili.com/video/BV196HfeKEjm)
  - links: https://wnzhang.net/teaching/sjtu-rl-2024/index.html https://wnzhang.net/teaching/sjtu-rl-2024/slides/5-planning-learning.pdf
- **上海交大张伟楠强化学习课程第7讲：规划与学习II**
  - [B station](https://www.bilibili.com/video/BV196HfeKEBr)
  - links: https://wnzhang.net/teaching/sjtu-rl-2024/index.html https://wnzhang.net/teaching/sjtu-rl-2024/slides/5-planning-learning.pdf
- **上海交大张伟楠强化学习课程第8讲：参数化的值函数和策略I**
  - [B station](https://www.bilibili.com/video/BV1RBHfeqEHo)
  - links: https://wnzhang.net/teaching/sjtu-rl-2024/index.html https://wnzhang.net/teaching/sjtu-rl-2024/slides/6-approx-methods.pdf
- **上海交大张伟楠强化学习课程第8讲：参数化的值函数和策略II**
  - [B station](https://www.bilibili.com/video/BV1RBHfeqEWK)
  - links: https://wnzhang.net/teaching/sjtu-rl-2024/index.html https://wnzhang.net/tutorials/sjtu-rl-2024/slides/6-approx-methods.pdf
- **上海交大张伟楠强化学习课程第9讲：深度强化学习价值方法I**
  - [B station](https://www.bilibili.com/video/BV1DtpeewESC)
  - links: https://wnzhang.net/teaching/sjtu-rl-2024/index.html https://wnzhang.net/teaching/sjtu-rl-2024/slides/7-drl-value.pdf
- **上海交大张伟楠强化学习课程第9讲：深度强化学习价值方法II**
  - [B station](https://www.bilibili.com/video/BV1drpve3Eip)
  - links: https://wnzhang.net/teaching/sjtu-rl-2024/index.html https://wnzhang.net/teaching/sjtu-rl-2024/slides/7-drl-value.pdf
- **上海交大张伟楠强化学习课程第10讲：深度强化学习策略方法I**
  - [B station](https://www.bilibili.com/video/BV199pzeUEMA)
  - links: https://wnzhang.net/teaching/sjtu-rl-2024/index.html https://wnzhang.net/teaching/sjtu-rl-2024/slides/8-drl-policy.pdf
- **上海交大张伟楠强化学习课程第10讲：深度强化学习策略方法II**
  - [B station](https://www.bilibili.com/video/BV199pzeUEgQ)
  - links: https://wnzhang.net/teaching/sjtu-rl-2024/index.html https://wnzhang.net/teaching/sjtu-rl-2024/slides/8-drl-policy.pdf
- **上海交大张伟楠强化学习课程第11讲：基于模型的深度强化学习I**
  - [B station](https://www.bilibili.com/video/BV199pzeUEg9)
  - links: https://wnzhang.net/teaching/sjtu-rl-2024/index.html https://wnzhang.net/teaching/sjtu-rl-2024/slides/9-model-based-rl.pdf
- **上海交大张伟楠强化学习课程第11讲：基于模型的深度强化学习II**
  - [B station](https://www.bilibili.com/video/BV1DfpzeLEkB)
  - links: https://wnzhang.net/teaching/sjtu-rl-2024/index.html https://wnzhang.net/teaching/sjtu-rl-2024/slides/9-model-based-rl.pdf
- **上海交大张伟楠强化学习课程第11讲：基于模型的深度强化学习III**
  - [B station](https://www.bilibili.com/video/BV1DfpzeLE5K)
  - links: https://wnzhang.net/teaching/sjtu-rl-2024/index.html https://wnzhang.net/teaching/sjtu-rl-2024/slides/9-model-based-rl.pdf
- **上海交大张伟楠强化学习课程第12讲：模仿学习I**
  - [B station](https://www.bilibili.com/video/BV1DfpzeLEmC)
  - links: https://wnzhang.net/teaching/sjtu-rl-2024/index.html https://wnzhang.net/teaching/sjtu-rl-2024/slides/10-imitation.pdf
- **上海交大张伟楠强化学习课程第12讲：模仿学习II**
  - [B station](https://www.bilibili.com/video/BV1Qopze2Ee1)
  - links: https://wnzhang.net/teaching/sjtu-rl-2024/index.html https://wnzhang.net/teaching/sjtu-rl-2024/slides/10-imitation.pdf
- **上海交大张伟楠强化学习课程第13讲：离线强化学习**
  - [B station](https://www.bilibili.com/video/BV1Qopze2EYU)
  - links: https://wnzhang.net/teaching/sjtu-rl-2024/index.html https://wnzhang.net/teaching/sjtu-rl-2024/slides/11-offline-rl.pdf
- **上海交大张伟楠强化学习课程第14讲：多智能体强化学习I**
  - [B station](https://www.bilibili.com/video/BV1Qopze2E1M)
  - links: https://wnzhang.net/teaching/sjtu-rl-2024/index.html https://wnzhang.net/teaching/sjtu-rl-2024/slides/12-13-marl.pdf
- **上海交大张伟楠强化学习课程第14讲：多智能体强化学习II**
  - [B station](https://www.bilibili.com/video/BV1Qopze2Ep6)
  - links: https://wnzhang.net/teaching/sjtu-rl-2024/index.html https://wnzhang.net/teaching/sjtu-rl-2024/slides/12-13-marl.pdf
- **上海交大张伟楠强化学习课程第14讲：多智能体强化学习III**
  - [B station](https://www.bilibili.com/video/BV1GopzemEF2)
  - links: https://wnzhang.net/teaching/sjtu-rl-2024/index.html https://wnzhang.net/teaching/sjtu-rl-2024/slides/12-13-marl.pdf
- **上海交大张伟楠强化学习课程第14讲：多智能体强化学习IV**
  - [B station](https://www.bilibili.com/video/BV1TspzezEoo)
  - links: https://wnzhang.net/teaching/sjtu-rl-2024/index.html https://wnzhang.net/teaching/sjtu-rl-2024/slides/12-13-marl.pdf
- **上海交大张伟楠强化学习课程第15讲：AI Agent与决策大模型I**
  - [B station](https://www.bilibili.com/video/BV1TspzezEbE)
  - links: https://wnzhang.net/teaching/sjtu-rl-2024/index.html https://wnzhang.net/teaching/sjtu-rl-2024/slides/14-llm-agents-ldm.pdf
- **上海交大张伟楠强化学习课程第15讲：AI Agent与决策大模型II**
  - [B station](https://www.bilibili.com/video/BV14spzezExv)
  - links: https://wnzhang.net/teaching/sjtu-rl-2024/index.html https://wnzhang.net/teaching/sjtu-rl-2024/slides/14-llm-agents-ldm.pdf
- **上海交大张伟楠强化学习课程第15讲：AI Agent与决策大模型III**
  - [B station](https://www.bilibili.com/video/BV14spzezE85)
  - links: https://wnzhang.net/teaching/sjtu-rl-2024/index.html https://wnzhang.net/teaching/sjtu-rl-2024/slides/14-llm-agents-ldm.pdf
- **上海交大张伟楠强化学习课程第16讲：基于扩散模型的强化学习**
  - [B station](https://www.bilibili.com/video/BV12spzezE9Y)
  - links: https://wnzhang.net/teaching/sjtu-rl-2024/index.html https://wnzhang.net/teaching/sjtu-rl-2024/slides/15-diffusion-rl.pdf
- **面向python、算法工程师的agent开发教程 s1-介绍**
  - [B station](https://www.bilibili.com/video/BV12AwDzgEwe)
  - links: https://github.com/yuanzhoulvpi2017/zero_agent
- **面向python、算法工程师的agent开发教程 s2-图解+调试的方式查看agent数据流控制（查看agent是如何运行的）**
  - [B station](https://www.bilibili.com/video/BV1XADnBBEMy)
  - links: https://github.com/yuanzhoulvpi2017/zero_agent
- **面向python、算法工程师的agent开发教程 s3-简单介绍一下agentscope的闪光点～**
  - [B station](https://www.bilibili.com/video/BV1ksd9BcEx3)
  - links: https://github.com/yuanzhoulvpi2017/zero_agent
- **【PaperTrail】把 DeepSeek 论文 Agent 蒸馏到 4B：数据采集、SFT 训练与本地部署｜源码分享**
  - [B station](https://www.bilibili.com/video/BV12CY96EEFP)
  - links: https://github.com/yuanzhoulvpi2017/zero_agent
- **【PaperTrail】Agent 技术拆解 S1：用 DeepSeek 和 AgentScope 搭建论文助手**
  - [B station](https://www.bilibili.com/video/BV1Zkpp6HEuS)
  - links: https://github.com/yuanzhoulvpi2017/zero_agent
- **【PaperTrail】Agent 技术拆解 S2：记录大模型交互轨迹，为 SFT 准备数据**
  - [B station](https://www.bilibili.com/video/BV15Cpu65Esb)
  - links: https://github.com/yuanzhoulvpi2017/zero_agent
- **图解deepseek的grpo原理、以debug形式阅读grpo的源码**
  - [B station](https://www.bilibili.com/video/BV1wFNCehERn)
  - links: https://github.com/yuanzhoulvpi2017/zero_nlp/tree/main/rl_grpo
- **deepseek-r1复现踩坑系列1: 多机多卡环境下GRPO训练32B大模型的框架对比**
  - [B station](https://www.bilibili.com/video/BV1tGGezxEGg)
  - links: https://github.com/yuanzhoulvpi2017/nano_rl
- **deepseek-r1复现踩坑系列2: verl的二次开发-reward模块**
  - [B station](https://www.bilibili.com/video/BV1TwV1zdEHw)
  - links: https://github.com/yuanzhoulvpi2017/nano_rl
- **一个视频带你搞懂 verl里面的ray到底起什么作用？verl里面的worker怎么使用？——verl源码解读系列**
  - [B station](https://www.bilibili.com/video/BV116gozmEdn)
- **由浅入深的了解 verl如何使用fsdp初始化model并且计算logits——verl源码解读系列**
  - [B station](https://www.bilibili.com/video/BV1gjgqzYEJ3)
  - links: https://github.com/yuanzhoulvpi2017/zero_nlp/tree/main/verl_base
- **文本转向量教程s1——总体介绍**
  - [B station](https://www.bilibili.com/video/BV1dw4m1o7X9)
  - links: https://huggingface.co/docs/optimum/index
- **文本转向量教程s2——认识文本转向量方法（sbert本质和推理加速）**
  - [B station](https://www.bilibili.com/video/BV1ex4y1S7u5)
  - links: https://huggingface.co/docs/optimum/index
- **文本转向量教程s3——Trainer二次开发（embedding为例）**
  - [B station](https://www.bilibili.com/video/BV1BC411L7tB)
  - links: https://huggingface.co/docs/optimum/index
- **为什么我的模型就没有办法使用ddp——基于bert做embedding任务 使用ddp进行训练**
  - [B station](https://www.bilibili.com/video/BV1ii421e7V6)
  - links: https://github.com/yuanzhoulvpi2017/SentenceEmbedding/tree/parallel_train
- **qwen3-embedidng、qwen3-reranker模型解读 使用ray进行部署**
  - [B station](https://www.bilibili.com/video/BV18FThzuE4b)
- **transformers源码阅读——入门（提高nlp工程师的工程能力）**
  - [B station](https://www.bilibili.com/video/BV1DN4y1X7av)
- **transformers源码阅读——transformers包的文件框架介绍**
  - [B station](https://www.bilibili.com/video/BV1Tm4y1M7nQ)
- **transformers源码阅读——如何看懂模型代码（以llama为例）**
  - [B station](https://www.bilibili.com/video/BV1qj411y7kF)
- **图解llama架构 解读源码实现**
  - [B station](https://www.bilibili.com/video/BV1nK4y1F7x7)
- **transformers源码阅读——llama模型调试**
  - [B station](https://www.bilibili.com/video/BV1Cw411y7gs)
- **transfomers源码阅读——Trainer解读系列1_了解训练流程**
  - [B station](https://www.bilibili.com/video/BV1b8411y7rR)
- **transformers源码阅读——Trainer解读系列2_关键方法**
  - [B station](https://www.bilibili.com/video/BV1GN411n7rS)
- **transformers疑惑解答S1——transformers是怎么保存模型权重的？**
  - [B station](https://www.bilibili.com/video/BV1nw411y7qL)
  - links: https://www.zhihu.com/question/620641385/answer/3230090109 https://huggingface.co/blog/accelerate-large-models https://github.com/huggingface/transformers/blob/03af4c42a624ea44b3325ff78151f499392dd617/src/transformers/trainer.py#L2965
- **longlora是怎么实现的——如何在transformers的模型上修改的**
  - [B station](https://www.bilibili.com/video/BV1JN4y1f7JX)
- **transformers二次开发——（定义自己的数据加载器 模型 训练器）bge模型微调流程**
  - [B station](https://www.bilibili.com/video/BV1eu4y1x7ix)
- **transformers二次开发——bge-reranker模型微调流程**
  - [B station](https://www.bilibili.com/video/BV1sQ4y137Ft)
- **强化学习TRL包源码解读S1——reward_Trainer**
  - [B station](https://www.bilibili.com/video/BV1RG411y71U)
- **强化学习TRL包源码解读S2——PPO**
  - [B station](https://www.bilibili.com/video/BV1vy4y1P7GT)
- **transformers源码阅读——neftune的工程实现**
  - [B station](https://www.bilibili.com/video/BV1YQ4y1n7c6)
- **transformers源码阅读——gradient_checkpointing详解**
  - [B station](https://www.bilibili.com/video/BV1K84y1Q7hH)
- **transformers源码阅读——投机采样原理和实现方法**
  - [B station](https://www.bilibili.com/video/BV1ZC4y177Tw)
  - links: https://zhuanlan.zhihu.com/p/653935025
- **大模型量化是怎么实现的——transformers源码解读**
  - [B station](https://www.bilibili.com/video/BV1Ga4y1D7ed)
  - links: https://github.com/huggingface/transformers/blob/9b25c164bdb2754002e118065bc5045436b72773/src/transformers/modeling_utils.py#L3291 https://github.com/huggingface/transformers/blob/4b796978656e461177a83d58ec3c2b06152c63db/src/transformers/integrations/bitsandbytes.py#L184
- **chatglm3源码阅读——吐槽角度**
  - [B station](https://www.bilibili.com/video/BV1Rv411F7Mk)
- **国内的大模型结构和llama有多相似？**
  - [B station](https://www.bilibili.com/video/BV15j411J7QP)
- **transformers源码阅读——mixtral模型解读——MoE实现细节**
  - [B station](https://www.bilibili.com/video/BV19N411G7J2)
- **transformers源码阅读——图解mixtral模型——图解MoE细节**
  - [B station](https://www.bilibili.com/video/BV1Xu4y1K7zn)
- **transformers二次开发——百度轩辕70b大模型数据调度的实现**
  - [B station](https://www.bilibili.com/video/BV1qT4y1H7G1)
- **transformers二次开发——为什么要实现自己的sft代码**
  - [B station](https://www.bilibili.com/video/BV1sK4y1z7LV)
  - links: https://github.com/yuanzhoulvpi2017/zero_nlp/tree/main/internlm-sft
- **transformers二次开发——为什么要实现自己的sentence-embedding训练代码**
  - [B station](https://www.bilibili.com/video/BV1bN4y1n7Ex)
  - links: https://github.com/yuanzhoulvpi2017/SentenceEmbedding
- **miniCPM系列S1——技术报告解读（吊打llama2-70b-chat模型？）**
  - [B station](https://www.bilibili.com/video/BV1cC411r7ZG)
- **手把手带你发现transformers的bug 并且修复它！**
  - [B station](https://www.bilibili.com/video/BV16F4m1V7E1)
- **我的pr被transformers官方merge了&如何使用vscode和tensorboard查看训练日志**
  - [B station](https://www.bilibili.com/video/BV1CZ421878s)
  - links: https://github.com/huggingface/transformers/pull/29568
- **图解minicpm-v-2.6源码（debug的形式 一个视频看懂他的网络结构）**
  - [B station](https://www.bilibili.com/video/BV1SCYSeYET9)
- **一个视频让你对flash attention2下头（比较FA2和sdpa的效率）**
  - [B station](https://www.bilibili.com/video/BV18ceWeFEoP)
  - links: https://github.com/huggingface/transformers/commit/1c37e8c1a6274e6e87b45c6319eb190757214c2a https://github.com/huggingface/transformers/pull/31940 https://gist.github.com/qubvel/ac691a54e54f9fae8144275f866a7ff8
- **transformers集成了Liger Kernel：在llm训练的时间更少、显存使用的更少**
  - [B station](https://www.bilibili.com/video/BV1XCWzeJE7A)
  - links: https://github.com/huggingface/transformers/pull/32860 https://github.com/huggingface/transformers/issues/32861 https://github.com/linkedin/Liger-Kernel
- **如何优雅的修改transformers包的模型结构——面向nlp小白的开发教程**
  - [B station](https://www.bilibili.com/video/BV1KhWmehEVz)
- **transformers一个非常严重的bug——在使用梯度累计的时候 loss不等效**
  - [B station](https://www.bilibili.com/video/BV1oY1aYzEVi)
  - links: https://unsloth.ai/blog/gradient https://github.com/huggingface/transformers/commit/d9f733625c43158f3fa52377f2f8bf49350160f3 https://github.com/huggingface/transformers/pull/34283
- **AutoModel的lazy加载方式原理解读**
  - [B station](https://www.bilibili.com/video/BV1mhmeYiE3T)
- **图解大模型的KV Cache——图解+transformers源码阅读**
  - [B station](https://www.bilibili.com/video/BV1U5CcYeEX8)
- **vLLM源码阅读s1——源码介绍**
  - [B station](https://www.bilibili.com/video/BV1Vp421S7zg)
- **vLLM源码阅读s2——是如何进行离线推理的**
  - [B station](https://www.bilibili.com/video/BV1qE42157Rn)
- **vllm二次开发——自定义的新模型如何部署在vllm上S1**
  - [B station](https://www.bilibili.com/video/BV1xbypYtEu2)
  - links: https://docs.vllm.ai/en/latest/index.html https://github.com/vllm-project/vllm/pull/8896/files https://github.com/vllm-project/vllm
- **多模态大模型LLaVA模型讲解——transformers源码解读**
  - [B station](https://www.bilibili.com/video/BV1nw4m1S7nZ)
- **自定义多模态大模型LLaVA——LLaVA系列**
  - [B station](https://www.bilibili.com/video/BV1GS411P74b)
- **训练LLaVA模型（数据集构建、基于Trainer的训练框架搭建）——LLaVA系列**
  - [B station](https://www.bilibili.com/video/BV1Si421v7j1)
- **nlp开发利器——vscode如何debug transformers源码**
  - [B station](https://www.bilibili.com/video/BV1Hh4y1i7Li)
- **nlp开发利器——vscode如何debug transformers源码(torchrun形式）**
  - [B station](https://www.bilibili.com/video/BV1b84y1R75V)
- **nlp开发利器——vscode如何debug transformers源码(deepspeed形式）**
  - [B station](https://www.bilibili.com/video/BV1xC4y1P7LH)
- **nlp开发利器——vscode debug nlp大工程（最最最优雅的方式）**
  - [B station](https://www.bilibili.com/video/BV1wt421V718)
  - links: https://github.com/yuanzhoulvpi2017/vscode_debug_transformers
- **我的vscode主题配色**
  - [B station](https://www.bilibili.com/video/BV1xv411c7ti)
  - links: https://blog.csdn.net/adley_app/article/details/108821464
- **使用vscode愉快的阅读transformers源码**
  - [B station](https://www.bilibili.com/video/BV14b4y1G7bF)
- **nlp开发利器——vscode愉快的写nlp代码**
  - [B station](https://www.bilibili.com/video/BV1LH4y1H7jj)
- **transformers更新了啥S2——在国庆的时候 更新了啥（闲聊）**
  - [B station](https://www.bilibili.com/video/BV1Lw411y7kD)
- **transformers更新了啥S1——InternLM模型和llama模型竟然是差不多的**
  - [B station](https://www.bilibili.com/video/BV1rz4y1G74d)
- **transformers更新了啥S3——23-10-22日更新**
  - [B station](https://www.bilibili.com/video/BV1Bj411v7PA)
- **transformers更新了啥S3——23-11-05日更新**
  - [B station](https://www.bilibili.com/video/BV1BC4y1J7Rs)
- **transformers包新功能——一行代码将模型效率提高40%**
  - [B station](https://www.bilibili.com/video/BV1ap4y1d7MZ)
- **[国内一小伙自制]地理坐标系的映射关系**
  - [B station](https://www.bilibili.com/video/BV1uR4y1W7hZ)
- **3d视角查看中国各个省级地图(demo)**
  - [B station](https://www.bilibili.com/video/BV1JF41187Jf)
- **python入门教程之写代码素质1【管理数据和代码】【中国人不骗中国人，这个绝对是最走心的教程】**
  - [B station](https://www.bilibili.com/video/BV1Vg411T74D)
- **最走心的python学习分享【没有广告、没有焦虑、单纯的分享干货】**
  - [B station](https://www.bilibili.com/video/BV1JP4y157uV)
- **我用技术成功追星啦**
  - [B station](https://www.bilibili.com/video/BV1DT4y1R79v)
- **手写数值识别web应用**
  - [B station](https://www.bilibili.com/video/BV15X4y1M7DT)
  - links: https://github.com/yuanzhoulvpi2017/classdigits_inter
- **python通关羊了个羊**
  - [B station](https://www.bilibili.com/video/BV1HG4y1q7gi)
- **vscode调试jupyter notebook**
  - [B station](https://www.bilibili.com/video/BV1KB4y1B78v)
- **细节怪27秋招面经八股合集：Day00 Multi-Agent 和 ReAct 和 Harness 有什么区别（不理解为什么会问这样的问题**
  - [B station](https://www.bilibili.com/video/BV1k3YJ6GEek)
- **细节怪27秋招面经八股合集：ReAct 和 Plan-and-Excute 有什么区别**
  - [B station](https://www.bilibili.com/video/BV1EEeA64ET3)
- **细节怪-2027秋招必学：如何拆解一个Agent （从loop到Harness,从openclaw 到Hermes )**
  - [B station](https://www.bilibili.com/video/BV1GcKV6rEQq)
- **细节怪-27秋招必学：Claude Code 强大的Runtime到底是什么样的**
  - [B station](https://www.bilibili.com/video/BV1VB3Y61EyE)
- **细节怪27秋招必学-Claude Code的上下文工程（听说最近删除了80%的System Prompt?!)**
  - [B station](https://www.bilibili.com/video/BV1Z33o6HEmG)
- **细节怪27秋招必学：Claude Code 的 Memory 是如何设计的（CLADE.md和Auto Memory)**
  - [B station](https://www.bilibili.com/video/BV1xr3f6zEcS)
- **细节怪-27秋招必学：Claude Code如何组织Skill,MCP,等tool(Action层）**
  - [B station](https://www.bilibili.com/video/BV1dou96KEGk)
- **细节怪27秋招必学：Herman Agent 惊艳一时的爱马仕究竟是如何完成自进化的？**
  - [B station](https://www.bilibili.com/video/BV1wBbT6aEMY)
- **细节怪手撕LLM-混合专家模型MoE详解**
  - [B station](https://www.bilibili.com/video/BV1iji7BwEqC)
- **细节怪-手撕LLM之如何训练一个大模型（大模型的能力，特点以及发展趋势）【本期为后续预告】**
  - [B station](https://www.bilibili.com/video/BV1yZBbBSEUg)
- **细节怪-手撕LLM-LLaMA（激活函数SwiGLU, GQA…数学原理分析)**
  - [B station](https://www.bilibili.com/video/BV1damrBbErz)
- **细节怪-手撕LLM-Decoder-only之GLM（国内模型，创新点分析，架构设计）**
  - [B station](https://www.bilibili.com/video/BV1bZmiBKE4E)
- **细节怪-手撕LLM- GPT系列（细节设计分析，发展历程回顾）**
  - [B station](https://www.bilibili.com/video/BV11AmxBAEiR)
- **细节怪-手斯LLM- T5（Encoder-Decoder)创新点原理分析**
  - [B station](https://www.bilibili.com/video/BV1W12QBiEoy)
- **细节怪-手撕LLM-Bert全景分析：ALBERT(Encoder-only)**
  - [B station](https://www.bilibili.com/video/BV1HU2SBoENv)
- **细节怪之手撕LLM-Bert 全景分析：RoBERTa（四大优化点剖析）**
  - [B station](https://www.bilibili.com/video/BV1aw25B3End)
- **细节怪之手撕LLM-Bert 全景分析（1）：Bert 细节分析和原理介绍（Encoder-only)**
  - [B station](https://www.bilibili.com/video/BV1eq25BLE5N)
- **细节怪-手撕LLM-旋转位置编码（3）：代码实现**
  - [B station](https://www.bilibili.com/video/BV1K6UuBoEiY)
- **细节怪-手撕LLM-PE&RoPE: 为什么需要旋转位置编码（数学证明）**
  - [B station](https://www.bilibili.com/video/BV1MbycBbE4A)
- **细节怪-手撕LLM-PE&RoPE(1)：什么是旋转位置编码（原理分析）**
  - [B station](https://www.bilibili.com/video/BV19jycBiEBd)
  - links: https://www.bilibili.com/video/BV1c9sizJEMv/ https://www.bilibili.com/video/BV1DxyWBfEh1/
- **细节怪-手撕Transformer: Add & Norm 残差连接和归一化的理论原理**
  - [B station](https://www.bilibili.com/video/BV1agCeBdEdW)
- **细节怪-手撕Transformer: 位置编码（设计原理与示意图）**
  - [B station](https://www.bilibili.com/video/BV1DxyWBfEh1)
- **细节怪-手撕Transformer: 注意力机制之多头注意力（为什么需要多头注意力，为什么多头可以提取的多维信息，计算优化和纬度变化）**
  - [B station](https://www.bilibili.com/video/BV12jsyz2EeV)
- **细节怪-手撕Transformer: 注意力机制之掩码注意力（为什么需要掩码，如何构建掩码）**
  - [B station](https://www.bilibili.com/video/BV1WpsyzkEY3)
- **细节怪-手撕Transformer(2): 注意力机制原理分析与代码实践！（公式推导；自注意力）**
  - [B station](https://www.bilibili.com/video/BV1c9sizJEMv)
- **细节怪-手撕Transformer(1) : 整体架构（从数学原理到代码实践）**
  - [B station](https://www.bilibili.com/video/BV1DX4BzyEfC)
- **细节怪-手撕LLM之如何估算模型所需的显存（看完就会！算力选购必备~)【B站AI创作大赛-开放赛道】**
  - [B station](https://www.bilibili.com/video/BV1Lj69BkEpi)
- **细节怪-手撕LLM之 LoRA 原理（大模型算法面试必考！）【2026开个好头】**
  - [B station](https://www.bilibili.com/video/BV1wHkYBiEap)
- **细节怪-手撕 LLM 之 KV Cache 推理优化（1）实例分析（8分钟透彻理解）**
  - [B station](https://www.bilibili.com/video/BV1mDzcByEcv)
- **细节怪-手撕 LLM 之 vLLM 推理优化（2）最流行的大模型部署方式（一学就会！）**
  - [B station](https://www.bilibili.com/video/BV1wvzuBfEgD)
- **细节怪-手撕 LLM 之 Flash Attention 训练与推理优化（4）超清晰的讲解和手动推导，零基础也能听懂！**
  - [B station](https://www.bilibili.com/video/BV1PazCBZEAK)
- **细节怪-手撕 LLM 之 TensorRT-LLM 推理优化（3）静态计算图，深度算子融合，超详细解读（一学就会！）**
  - [B station](https://www.bilibili.com/video/BV1mkz6BWEF4)
- **细节怪-手撕 LLM 系列：DeepSpeed 详解（ ZeRO 三阶段和底层通信原理，值得细细品味！)**
  - [B station](https://www.bilibili.com/video/BV1yP6GBzE7V)
- **细节怪-手撕 LLM 之 RLHF 概念详解与PPO算法详解（1）（近期高频八股，系统搞定！）**
  - [B station](https://www.bilibili.com/video/BV1LB6nBJECs)
- **细节怪-手撕 LLM 之大模型常用的几种精度（FP32，FP16，BF16，NF8，实例分析，一步到位，小知识点扫盲）**
  - [B station](https://www.bilibili.com/video/BV1SDZXB3Ewe)
- **细节怪-手撕 LLM 系列之 QLoRA 详解（什么是双重量化）**
  - [B station](https://www.bilibili.com/video/BV1BqZeBMEvZ)
- **细节怪手撕 LLM 之 DeepSeek-V4 注意力机制（CSA，HCA，Sliding Window, 从架构到原理**
  - [B station](https://www.bilibili.com/video/BV1vsd3BcE97)
- **细节怪-手撕Transformer: KL散度公式推导（从信息量到交叉熵）**
  - [B station](https://www.bilibili.com/video/BV1Pxui6eErQ)
- **细节怪-手撕Transformer: RL中的KL散度，与DPO替代奖励函数的解析解**
  - [B station](https://www.bilibili.com/video/BV1nQuv6oEKW)
- **手撕 LLM - 沉浸式实战跟练：手撕 MHA（多头注意力）大模型算法工程师必备技能！**
  - [B station](https://www.bilibili.com/video/BV1TqkVB9EPL)
- **沉浸式手撕 LLM 系列 —— 手撕 GQA （大模型算法工程师入门必学）十分钟搞定！**
  - [B station](https://www.bilibili.com/video/BV12ozABEEEG)
- **沉浸式手撕 LLM ：RoPE (旋转位置编码）细节只有手撕了才知道！大模型算法工程师入门必学～**
  - [B station](https://www.bilibili.com/video/BV1soz2BMEmY)
- **沉浸式手撕 LLM 系列：Softmax (面试题目，新鲜出炉，做了一点拓展，后面的还得撕一下online softmax)**
  - [B station](https://www.bilibili.com/video/BV1yH6FBzE6t)
- **手撕 LLM 之沉浸式实战 plus : SFT-loss 原理分析公式推导**
  - [B station](https://www.bilibili.com/video/BV1QoGf6HEqU)
- **沉浸式手撕实战：SFT-loss （numpy) 面试必会手撕跟练!**
  - [B station](https://www.bilibili.com/video/BV1EUEF6LEb9)
- **LLM 应用开发原理-Agent 入门介绍（2）（Function calling 底层原理，如何选择合适的范式）**
  - [B station](https://www.bilibili.com/video/BV1nCcPzYExP)
- **LLM 应用开发原理：Agent 开发框架介绍（1）低代码开发平台（dify, Coze, n8n, CrewAI)**
  - [B station](https://www.bilibili.com/video/BV1dNFUzVEhk)
- **LLM 应用开发实战篇 ：从零构建一个 Agent Skill (小白友好，有手就会）第一期**
  - [B station](https://www.bilibili.com/video/BV1MRf7B1EZW)
- **LLM 应用开发原理实战篇：从零手搓一个skill (包含自己手搓和使用 skill-creator 来构建）小白友好，有手就行**
  - [B station](https://www.bilibili.com/video/BV1naf7BhE8J)
- **LLM 应用开发原理实战篇：安装一些好用的 skill (手把手教学，有手就行）**
  - [B station](https://www.bilibili.com/video/BV1uffJBDEGD)
- **LLM 应用开发原理—拆解现象级 Agent 产品 OpenClaw 大虾（源码加原理）**
  - [B station](https://www.bilibili.com/video/BV15NQQBaE93)
- **多模态 之 CLIP ｜ 1、CLIP 网络结构精讲**
  - [B station](https://www.bilibili.com/video/BV1BeZFBGEhe)
- **多模态 之 CLIP | 2、官方不开源训练代码？给你推荐个社区版开源复现 -- OpenCLIP**
  - [B station](https://www.bilibili.com/video/BV1YP5v6tEop)
- **多模态 之 ViLT ｜ 1、ViLT 的 Single Stream 结构**
  - [B station](https://www.bilibili.com/video/BV1YUVJ6EERN)
- **多模态 之 ViLT ｜2、模型结构详解、三类任务、模型权重初始化方案**
  - [B station](https://www.bilibili.com/video/BV1pwVU6VEjS)
- **MLM｜Masked Language Model 详解 & Whole Word Masking**
  - [B station](https://www.bilibili.com/video/BV1QB7S63Ed2)
- **多模态 之 BLIP｜  一个模型 可以支持 3种工作模式（图文对比、图文匹配、配文生成）**
  - [B station](https://www.bilibili.com/video/BV1YwTk6tEPj)
- **多模态 之 BLIP｜ CapFilt ：自举式训练（Bootstrapped），用模型反哺数据**
  - [B station](https://www.bilibili.com/video/BV1UMMN6DEvs)
- **3）BeamSearch 与 NucleusSampling**
  - [B station](https://www.bilibili.com/video/BV1Mr3Q64E8o)
- **多模态 之 YOLO-World ｜ 1、整体网络结构**
  - [B station](https://www.bilibili.com/video/BV1S78w6eEAK)
- **多模态 之 YOLO-World ｜2、训练数据集 以及 Grounding 数据集的标注格式要求 （基于 Ultralytics）**
  - [B station](https://www.bilibili.com/video/BV1Nm826QEc4)
- **3）online/offline vocabulary**
  - [B station](https://www.bilibili.com/video/BV1R7tN6VE5T)
- **4）CLIP Text Encoder 处理文本流程**
  - [B station](https://www.bilibili.com/video/BV19LtN6yEoH)
- **5）T-CSP Layer**
  - [B station](https://www.bilibili.com/video/BV1RLtN6yE1M)
- **6）Max-Sigmoid Attention**
  - [B station](https://www.bilibili.com/video/BV1Znt36vEc1)
- **7）Image-pooling Attention**
  - [B station](https://www.bilibili.com/video/BV1BTbF6zEQh)
- **8）World Head / Contrastive Head**
  - [B station](https://www.bilibili.com/video/BV1Wcbw6HEVY)
- **9）Region-Text Contrastive Loss**
  - [B station](https://www.bilibili.com/video/BV1webT6NEdk)
- **多模态 之 YOLOE ｜ 1、YOLOE 的三种模式 & 三阶段训练 & 模型整体网络结构**
  - [B station](https://www.bilibili.com/video/BV1dMY16gEJP)
- **2）Text Embedding 与 RepRTA  网络结构**
  - [B station](https://www.bilibili.com/video/BV1wzeh62Eg1)
- **3）YOLO-World 与 YOLOE 对比**
  - [B station](https://www.bilibili.com/video/BV1fXev6pE8L)
- **4）BNContrastiveHead**
  - [B station](https://www.bilibili.com/video/BV1FEha6uESV)
- **5）RepRTA 结构重参数化 推导 & 代码讲解**
  - [B station](https://www.bilibili.com/video/BV1hLaN6JE9Z)
- **6）第二阶段训练 参数冻结**
  - [B station](https://www.bilibili.com/video/BV1ozaW61Eyx)
- **7）第二阶段整体训练框架 & 视觉提示 mask 预处理**
  - [B station](https://www.bilibili.com/video/BV1LLYP6sEMk)
- **8）SAVPE 网络结构 & 分组加权聚合**
  - [B station](https://www.bilibili.com/video/BV15Vp46ZE6j)
- **Tokenizer｜1、基础知识准备 ：Unicode、UTF-8、ASCII**
  - [B station](https://www.bilibili.com/video/BV116daB6EC5)
- **Tokenizer｜2、三大分词方法 ：Word / Character / Subword**
  - [B station](https://www.bilibili.com/video/BV1NtdZB1Eai)
- **Tokenizer｜3、BPE 与 BBPE Tokenizer 详解**
  - [B station](https://www.bilibili.com/video/BV1YYdmBhErJ)
- **Tokenizer｜4、词边界符**
  - [B station](https://www.bilibili.com/video/BV1cE9xByEXx)
- **5）WordPiece Tokenizer**
  - [B station](https://www.bilibili.com/video/BV14k3Q6REHR)
- **1）Flickr8k**
  - [B station](https://www.bilibili.com/video/BV1Z6Gs6NEaJ)
- **多模态 常用数据集｜ Flickr30k & Entities （Grounding 任务常用）**
  - [B station](https://www.bilibili.com/video/BV1kPpJ6DEhk)
- **Conda 环境管理工具**
  - [B station](https://www.bilibili.com/video/BV1bqKE6pEmD)
- **Enzo 深度学习  入门篇 （更新中）**
  - [B station](https://www.bilibili.com/video/BV1tLuw6VEJd)
- **反向传播 ：计算图、叶子节点/非叶子节点/根节点、requires_grad、grad**
  - [B station](https://www.bilibili.com/video/BV12Q4X6aEjt)
- **模型压缩神技：结构重参数化 ： 训练时多分支，推理时单卷积！**
  - [B station](https://www.bilibili.com/video/BV1uhN96JEzF)
- **环境配置 依赖包安装 常见问题 【50系显卡 Blackwell架构】**
  - [B station](https://www.bilibili.com/video/BV1RLtU6eE7f)
- **【即插即用 卷积模块】蛇形卷积 DSConv ：Dynamic Snake Convolution**
  - [B station](https://www.bilibili.com/video/BV18SYt6EE64)
- **【即插即用 卷积模块】中国结卷积 CKConv ：Chinese Knot Convolution**
  - [B station](https://www.bilibili.com/video/BV1i9eH6LEkq)
- **【即插即用 卷积模块】方向引导的边缘门控卷积 DEGConv ：Direction-guided Edge Gated Convolution**
  - [B station](https://www.bilibili.com/video/BV1xRhs6hEXr)
- **【即插即用 注意力模块】LA：Linear Attention**
  - [B station](https://www.bilibili.com/video/BV1N8at6uEpi)
- **【即插即用 卷积模块】风车卷积 PConv ：Pinwheel-shaped Convolution**
  - [B station](https://www.bilibili.com/video/BV1UUpt6XEJZ)
- **self-Attention｜自注意力机制 ｜位置编码 ｜ 理论 + 代码**
  - [B station](https://www.bilibili.com/video/BV1qo4y1F7Ep)
- **Multi-Head Attention | 算法 + 代码**
  - [B station](https://www.bilibili.com/video/BV1gV4y167rS)
- **ViT｜ Vision Transformer ｜理论 + 代码**
  - [B station](https://www.bilibili.com/video/BV1xm4y1b7Pw)
  - links: https://65d8gk.axshare.com
- **Positional Encoding ｜ 位置编码**
  - [B station](https://www.bilibili.com/video/BV1z84y1R7t8)
- **Swin Transformer ｜ Abstract**
  - [B station](https://www.bilibili.com/video/BV1Nz4y177aW)
- **Swin Transformer （上）**
  - [B station](https://www.bilibili.com/video/BV1xF41197E4)
- **Swin Transformer （下）**
  - [B station](https://www.bilibili.com/video/BV1qX4y1Y7mj)
- **DETR ｜ 1、算法概述**
  - [B station](https://www.bilibili.com/video/BV1Zo4y1A7FB)
- **DETR ｜2、模型结构讲解**
  - [B station](https://www.bilibili.com/video/BV1Gh4y127eZ)
- **DETR ｜3、损失函数讲解**
  - [B station](https://www.bilibili.com/video/BV1qu411V7ud)
- **Attention Map ｜ 复现 DETR 论文中 encoder layer 的 attention map**
  - [B station](https://www.bilibili.com/video/BV1jC411W7sC)
- **Deformable Convolution ｜可变形卷积**
  - [B station](https://www.bilibili.com/video/BV1Sh4y1y75i)
- **Deformable DETR | 1、Abstract  算法概述**
  - [B station](https://www.bilibili.com/video/BV1rh4y1F7fG)
- **Deformable DETR ｜ 2、backbone 、MultiHeadAttention 公式讲解**
  - [B station](https://www.bilibili.com/video/BV1vr4y1o73B)
- **Deformable DETR｜ 3、Deformable Attention、MSDeformAttention、流程讲解**
  - [B station](https://www.bilibili.com/video/BV1Uj411z7QU)
- **torchvision.models.resnet50() 可以使用哪些参数 ？ 这些参数有什么用 ？ 学习 DETR 必读 ！**
  - [B station](https://www.bilibili.com/video/BV1Ya4y1o7HP)
- **RT-DETR ｜1、abstract 算法概述**
  - [B station](https://www.bilibili.com/video/BV1Nb4y1F7k9)
- **RT-DETR  ｜ 2、backbone**
  - [B station](https://www.bilibili.com/video/BV1Ac411k7Sg)
- **RT-DETR  ｜ 3、AIFI**
  - [B station](https://www.bilibili.com/video/BV1be411S74w)
- **RT- DETR ｜ 4、CCFM**
  - [B station](https://www.bilibili.com/video/BV1DG411z71m)
- **5）CCFM 收尾工作**
  - [B station](https://www.bilibili.com/video/BV1bUR3BDEWC)
- **6）decoder 整体网络结构**
  - [B station](https://www.bilibili.com/video/BV1njt36uEk6)
- **7）denoising 理论讲解**
  - [B station](https://www.bilibili.com/video/BV1Fjt36uEKD)
- **8）denoising 代码讲解**
  - [B station](https://www.bilibili.com/video/BV1fJt36KEw9)
- **9）IoU-aware query selection**
  - [B station](https://www.bilibili.com/video/BV1fJt36KEuA)
- **10）IoU-aware query selection**
  - [B station](https://www.bilibili.com/video/BV1PMt36yEUR)
- **11）decoder MSDeformableAttention**
  - [B station](https://www.bilibili.com/video/BV1A3t36kEnm)
- **12）损失函数**
  - [B station](https://www.bilibili.com/video/BV1L4t36aErd)
- **13）RT-DETR 快速跑通**
  - [B station](https://www.bilibili.com/video/BV1v4t36aEyb)
- **14）Pycharm远程连接 + 配置 + 全流程跑通**
  - [B station](https://www.bilibili.com/video/BV1Xht36ZE48)
- **RT-DETR v1 ｜快速跑通 + AutoDL**
  - [B station](https://www.bilibili.com/video/BV1UWmMBREJ7)
- **RT-DETR | Pycharm 远程连接 (AutoDL) + 配置 + 全流程跑通**
  - [B station](https://www.bilibili.com/video/BV1egm7BxE4T)
- **RT-DETR v2 相较于 v1 的 4个优化点**
  - [B station](https://www.bilibili.com/video/BV1ePwzehEEy)
- **RT-DETRv4 ｜ RT-DETR + DINOv3**
  - [B station](https://www.bilibili.com/video/BV1zbE56sEmG)
- **D-Fine ｜1、FDR ： Fine-grained Distribution Refinement**
  - [B station](https://www.bilibili.com/video/BV1JHopYjEV7)
- **D-Fine｜2、损失函数细节精讲 之  FGL 数据准备**
  - [B station](https://www.bilibili.com/video/BV1jHJNzGEDC)
- **D-Fine｜3、损失函数  FGL :  Fine-Grained Localization Loss**
  - [B station](https://www.bilibili.com/video/BV1eDJ6zuErg)
- **D-Fine | 4、GO-LDS 全局优化定位自蒸馏、DDFLoss**
  - [B station](https://www.bilibili.com/video/BV1kgjXz5EjJ)
- **DEIM | 为什么 DEIM 能让 DETR 收敛提速一倍？？**
  - [B station](https://www.bilibili.com/video/BV1saKAzSEHg)
- **RoPE 旋转位置编码**
  - [B station](https://www.bilibili.com/video/BV1ReLq6BE8i)
- **Vibe Researching | Codex 介绍与安装**
  - [B station](https://www.bilibili.com/video/BV1ZoJG6nEi9)
- **Vibe Researching | Codex 基础使用**
  - [B station](https://www.bilibili.com/video/BV1wSL96YENx)
- **Vibe Researching | Codex - SKILL 基础介绍**
  - [B station](https://www.bilibili.com/video/BV1Qjjh6SEYm)
- **Vibe Researching | Codex - SKILL 实践 ： 创建一个用于收集论文基本信息的 SKILL**
  - [B station](https://www.bilibili.com/video/BV1e17g6PEEk)
- **解放生产力！我整了一个自动整理即插即用模块的 Codex Skill**
  - [B station](https://www.bilibili.com/video/BV1rwjd6TE7w)
- **DINO v1 |  自监督学习、无标签的自蒸馏  self-distillation with no labels**
  - [B station](https://www.bilibili.com/video/BV1Q74HzeEBY)
- **DINO v2 ｜ 5大改进点概述、整体训练框架解读**
  - [B station](https://www.bilibili.com/video/BV1BoUnByEWr)
- **DINO v3 ｜3阶段训练 +  扩大数据集（LVD-1689M）+ 扩大模型（ ViT-7B/16 ）**
  - [B station](https://www.bilibili.com/video/BV1vTvDBWEgG)
- **DINOv3｜多模态｜DINOv3 +  CLIP 图文对齐 方案解析**
  - [B station](https://www.bilibili.com/video/BV1JRd3B6EwN)
- **1、Dino v1 整体介绍**
  - [B station](https://www.bilibili.com/video/BV1AKDdBsEib)
- **2、Multi-crop**
  - [B station](https://www.bilibili.com/video/BV1kKDdBWEZC)
- **3、教师网络与学生网络**
  - [B station](https://www.bilibili.com/video/BV1pKDdBWEsp)
- **4、损失函数**
  - [B station](https://www.bilibili.com/video/BV1HKDdBWEXb)
- **5、实验｜centering 与 sharpening**
  - [B station](https://www.bilibili.com/video/BV1kKDdBWE9E)
- **6、教师网络参数的更新**
  - [B station](https://www.bilibili.com/video/BV1pKDdBWEbm)
- **7、实验｜教师网络构建方法的选择**
  - [B station](https://www.bilibili.com/video/BV1AKDdBsE1E)
- **8、优化器、调度器、各组件重要性分析**
  - [B station](https://www.bilibili.com/video/BV1pKDdBWEJZ)
- **0、前言**
  - [B station](https://www.bilibili.com/video/BV1scDdBoEoy)
- **1、数据集构建_LVD142M**
  - [B station](https://www.bilibili.com/video/BV1scDdBoEzN)
- **2、改进点概述**
  - [B station](https://www.bilibili.com/video/BV1scDdBoEzP)
- **3、patch-level objective**
  - [B station](https://www.bilibili.com/video/BV1xcDdBoEKe)
- **4、Sepeated Head**
  - [B station](https://www.bilibili.com/video/BV1ycDdBoEfg)
- **5、Sinkhorn-Knopp**
  - [B station](https://www.bilibili.com/video/BV1scDdBoE85)
- **6、KoLeo Regularizer**
  - [B station](https://www.bilibili.com/video/BV1scDdBoEm9)
- **1、DINOv3**
  - [B station](https://www.bilibili.com/video/BV1qEDdBLEMk)
- **2、LVD1689M数据集的构建**
  - [B station](https://www.bilibili.com/video/BV1qEDdBLE6i)
- **3、第一阶段训练**
  - [B station](https://www.bilibili.com/video/BV1oEDdBLENy)
- **4、第二阶段训练 ： Gram Anchoring**
  - [B station](https://www.bilibili.com/video/BV1ZEDdBLEua)
- **5、第三阶段训练 High Resolution Adaptat**
  - [B station](https://www.bilibili.com/video/BV1jEDdBLEz2)
- **6、多学生模型并行蒸馏**
  - [B station](https://www.bilibili.com/video/BV1jEDdBLE9c)
- **7、图文对齐（DINOv3 - CLIP）**
  - [B station](https://www.bilibili.com/video/BV1ZHRDBkEjf)
- **9、2D RoPE**
  - [B station](https://www.bilibili.com/video/BV1yfGE6fE3R)
- **1、自蒸馏训练 环境配置 + 运行**
  - [B station](https://www.bilibili.com/video/BV1utQxBDEtY)
- **2、多学生模型并行蒸馏 环境配置+运行**
  - [B station](https://www.bilibili.com/video/BV1jEDdBLEy3)
- **yolov1 算法精讲（上）**
  - [B station](https://www.bilibili.com/video/BV1ec411T7Rh)
- **yolov1 算法精讲（下）**
  - [B station](https://www.bilibili.com/video/BV1ks4y137oU)
- **yolov5 ｜ 手把手代码精读 ｜数据增强 之 仿射变换(Affine)、透视变换(Perspective)**
  - [B station](https://www.bilibili.com/video/BV1Vr421h7wF)
- **yolov5 ｜ 手把手代码精读 ｜数据增强 之 仿射变换(Affine)、透视变换(Perspective) | opencv 相关使用**
  - [B station](https://www.bilibili.com/video/BV1sp42117Ti)
- **yolov5 网络结构｜yaml 文件解读**
  - [B station](https://www.bilibili.com/video/BV1tH4y1n7MT)
- **yolov5 网络搭建 代码精讲**
  - [B station](https://www.bilibili.com/video/BV1YZ421e7zH)
- **yolov5 ｜损失函数 ｜ 正样本匹配**
  - [B station](https://www.bilibili.com/video/BV1iH4y1G7hV)
- **yolov5 ｜损失函数 ｜ 正样本匹配  代码精讲**
  - [B station](https://www.bilibili.com/video/BV1nr421j7X5)
- **番外 ｜ anchor-based 与 anchor-free 、anchor 与 anchor-point、grid cell**
  - [B station](https://www.bilibili.com/video/BV1W1421b7uF)
- **yolov8  |  损失函数 之  1、数据预处理 代码精读**
  - [B station](https://www.bilibili.com/video/BV1Rb421n7fr)
- **yolov8  |  损失函数 之  2、正样本匹配 理论讲解**
  - [B station](https://www.bilibili.com/video/BV1p142187Sv)
- **yolov8  |  损失函数 之  3、正样本匹配 代码精讲（上）**
  - [B station](https://www.bilibili.com/video/BV1HM4m1276w)
- **yolov8  |  损失函数 之  4、正样本匹配 代码精讲（下）**
  - [B station](https://www.bilibili.com/video/BV1b1421t7rY)
- **yolov8  |  损失函数 之  5、类别损失**
  - [B station](https://www.bilibili.com/video/BV1ti421h77Z)
- **yolov8  |  损失函数 之  6、定位损失 CIoU + DFL**
  - [B station](https://www.bilibili.com/video/BV1Zy411i75C)
- **yolov5 ｜ 手把手代码精读 ｜数据增强 之 mosaic**
  - [B station](https://www.bilibili.com/video/BV1ax4y1U7Ym)
- **yolo v11 网络结构的改动有哪些 ？**
  - [B station](https://www.bilibili.com/video/BV1q7DpYtEWL)
- **yolo v11 ｜  C3k2 模块结构详解**
  - [B station](https://www.bilibili.com/video/BV1uUyUY6ETc)
- **yolo v11 ｜ C2PSA 模块详解**
  - [B station](https://www.bilibili.com/video/BV1ko18YLEir)
- **yolo v11 ｜ Detect Head  检测头**
  - [B station](https://www.bilibili.com/video/BV1vHDpYREFR)
- **怎么盘项目新版本的改动点 ？ yolo v11 的图像增强 和 损失函数 有改动嘛 ？**
  - [B station](https://www.bilibili.com/video/BV1xErrYTEb1)
- **yolo 实例分割 ｜ Segmentation Head 结构 与 推理阶段后处理流程**
  - [B station](https://www.bilibili.com/video/BV1TpgqzbEu2)
- **YOLO26 ｜ SPPF、C3K2、Detect Head 的模块改动**
  - [B station](https://www.bilibili.com/video/BV1ULF5zBEnz)
- **YOLO26 ｜ 整体训练流程，以及 STAL 与 ProgLoss 处理节点**
  - [B station](https://www.bilibili.com/video/BV1o2FzzsENp)
- **YOLO26 | DFL Removal 需要做哪些配合调整 ？**
  - [B station](https://www.bilibili.com/video/BV1N8cwzvEum)
- **YOLO26 | NMS-Free 的后处理是怎么做的 ？End-to-End NMS-Free Inference**
  - [B station](https://www.bilibili.com/video/BV13QcuzYEKj)
- **YOLO26 | ProgLoss & STAL ， STAL 解决的是什么问题 ？ 具体解决方案是什么 ？**
  - [B station](https://www.bilibili.com/video/BV1nJcxzbEA2)
- **9）YOLO26 ｜ MuSGD 知识准备 ：奇异值分解**
  - [B station](https://www.bilibili.com/video/BV1UPPvz3EfN)
- **10）YOLO26 ｜ MuSGD 知识准备 ：牛顿法**
  - [B station](https://www.bilibili.com/video/BV1mNPvz6EfV)
- **8）YOLO26 ｜MuSGD**
  - [B station](https://www.bilibili.com/video/BV1SNPvz6EFZ)
- **Ultralytics 使用指南  | 下载哪个发布版本的 Ultralytics 项目 ？ 如何下载指定版本的 ？**
  - [B station](https://www.bilibili.com/video/BV1f1PezWEKN)
- **YOLO26 | AutoDL + Ultralytics 环境配置，全程复制粘贴命令，懒人必备 ！**
  - [B station](https://www.bilibili.com/video/BV1q5ftBXE48)
- **小白必看 ！ 训练效率优化，需要观察哪些指标，如何查看，有哪些参数会影响 训练效率 ？**
  - [B station](https://www.bilibili.com/video/BV1HuA3zoEAB)
- **训练小技巧 ｜ ultralytics 项目如此庞大且复杂，如何快速定位网络搭建入口/训练入口/损失函数入口/数据增强入口 ？ 怎么找到那条执行的任务主线 ？**
  - [B station](https://www.bilibili.com/video/BV1VqJnz7EjB)
- **pycharm 使用小技巧｜断点的灵活使用，如何断点在逻辑重叠的代码行，以及断点的统一管理**
  - [B station](https://www.bilibili.com/video/BV1K3h4zUEif)
- **深度学习 pycharm 使用 ｜ 命令行完全解析：从 CLI 命令 到 PyCharm 配置**
  - [B station](https://www.bilibili.com/video/BV11CZWBWE7N)
- **深度学习炼丹必修！AutoDL 租 GPU 全流程教学，跑通深度学习项目**
  - [B station](https://www.bilibili.com/video/BV1s2YdzNESZ)
- **AutoDL 实例迁移 | 在其他实例中复用环境 与 数据集、项目代码**
  - [B station](https://www.bilibili.com/video/BV1PN1VB4Etx)
- **远程训练必备！再也不担心 断网 / 断电 / 关机，screen 一招搞定**
  - [B station](https://www.bilibili.com/video/BV1eRwYzrEGq)
- **23.2、tmux**
  - [B station](https://www.bilibili.com/video/BV19ZAEzTE9A)
- **免费 GPU / TPU ｜ kaggle 项目部署**
  - [B station](https://www.bilibili.com/video/BV1qM41137SY)
- **kaggle 上白嫖 GPU 资源 训练 ViT 网络**
  - [B station](https://www.bilibili.com/video/BV1zLSKBgE4S)
- **深度学习基础 ｜ argparse 模块 ｜ 命令行参数解析**
  - [B station](https://www.bilibili.com/video/BV1jM4m1176F)
- **tensor基础知识 1 -  pytorch 之 tensor 内部存储结构**
  - [B station](https://www.bilibili.com/video/BV1NH4y177VL)
- **Dataset 与 DataLoader**
  - [B station](https://www.bilibili.com/video/BV1sRtresEbB)
- **Batch Normalization**
  - [B station](https://www.bilibili.com/video/BV11s4y1c7pg)
- **优化器 ｜SGD ｜Momentum ｜Adagrad ｜RMSProp ｜Adam**
  - [B station](https://www.bilibili.com/video/BV1jh4y1q7ua)
- **优化器 optimizer｜ 权重衰减、weight decay、L2 正则化惩罚**
  - [B station](https://www.bilibili.com/video/BV1LghvzHEKn)
- **信息量 ｜熵 ｜ 交叉熵 ｜KL散度 （相对熵）｜交叉熵损失函数**
  - [B station](https://www.bilibili.com/video/BV1L8411X7ZZ)
- **深度学习基础 ｜目标检测 评价指标 ：AP、mAP**
  - [B station](https://www.bilibili.com/video/BV1XHTwzhE1V)
- **Mamba 超超超详细解说 ｜ 1、对 SSM 的透彻理解**
  - [B station](https://www.bilibili.com/video/BV1n7421d7xG)
- **Mamba 超超超详细解说 ｜ 2、SSM 的离散化推导 + 代码示例**
  - [B station](https://www.bilibili.com/video/BV1GT421Y7vN)
- **Mamba 超超超详细解说 ｜3、S4 ：Structured State Spaces for Sequences**
  - [B station](https://www.bilibili.com/video/BV1wR67YhE18)
- **Mamba 超超超详细解说 ｜4、Mamba**
  - [B station](https://www.bilibili.com/video/BV16862YgEFK)
- **VMamba | Mamba 如何应用于2维图像 ？ SS2D ！ 前 2D-Cross-Scan，后 2D-Cross-Merge**
  - [B station](https://www.bilibili.com/video/BV1FVbQzqEis)
- **基础知识准备 之 Triton（上）**
  - [B station](https://www.bilibili.com/video/BV1CjtbzGERE)
- **基础知识准备 之 Triton（下）**
  - [B station](https://www.bilibili.com/video/BV1rntbzzEUX)
- **4.1、VMamba 整体网络结构**
  - [B station](https://www.bilibili.com/video/BV1uRhJzKEyG)
- **4.2、SS2D**
  - [B station](https://www.bilibili.com/video/BV1TfhJzYExF)
- **4.3、CrossScan 的 Triton 并行实现**
  - [B station](https://www.bilibili.com/video/BV1CshJzdEyh)
- **CUDA 编程快速上手 ｜ 1、grid、block、thread**
  - [B station](https://www.bilibili.com/video/BV1vpPXekEdC)
- **CUDA 编程快速上手 ｜ 2、global memory、shared memory、register**
  - [B station](https://www.bilibili.com/video/BV16ZPCeoETD)
- **不会写 cuda / c++ ？ 用平替的 triton 呀 !**
  - [B station](https://www.bilibili.com/video/BV1uvVFziE2k)
- **triton 基础使用 第2课 ｜通过 一个简单的【向量加法并行计算】，带你入门 Triton 基础使用 ！**
  - [B station](https://www.bilibili.com/video/BV1oLVrz8EVW)
- **triton 基础使用 第3课 ｜LayerNorm 的并行实现**
  - [B station](https://www.bilibili.com/video/BV1cU5PzTE2b)
- **triton 基础使用 第4课 ｜LayerNorm 的并行实现**
  - [B station](https://www.bilibili.com/video/BV17qEuz9EQ9)
- **Diffusion ｜ DDPM ｜ 1 - 概述**
  - [B station](https://www.bilibili.com/video/BV1Xu4y147ov)
  - links: https://www.bilibili.com/video/BV1xc411X7wx
- **Diffusion ｜ DDPM ｜2 - 基础知识准备**
  - [B station](https://www.bilibili.com/video/BV1UN411E7hz)
  - links: https://www.bilibili.com/video/BV1xc411X7wx
- **Diffusion | DDPM ｜ 3 - 前向扩散过程**
  - [B station](https://www.bilibili.com/video/BV1vw41117r1)
  - links: https://www.bilibili.com/video/BV1xc411X7wx
- **Diffusion | DDPM | 4 - 反向去噪过程、图像概率分布的理解**
  - [B station](https://www.bilibili.com/video/BV13N411J7zK)
  - links: https://www.bilibili.com/video/BV1xc411X7wx
- **Diffusion ｜ DDPM ｜ 5 - 损失函数**
  - [B station](https://www.bilibili.com/video/BV1ju4y1x7L4)
  - links: https://www.bilibili.com/video/BV1xc411X7wx
- **《ROS 2机器人开发从入门到实践》课程介绍**
  - [B station](https://www.bilibili.com/video/BV1GW42197Ck)
- **《ROS 2机器人开发从入门到实践》1.1 ROS部落的自我介绍**
  - [B station](https://www.bilibili.com/video/BV1tE4m1d7Ug)
- **《ROS 2机器人开发从入门到实践》1.2.1~1.2.3 ROS2开发环境搭建之安装虚拟机和Ubuntu**
  - [B station](https://www.bilibili.com/video/BV14M4m117LJ)
- **《ROS 2机器人开发从入门到实践》1.2.3.1使用Windows子系统WSL安装ROS2运行小海龟**
  - [B station](https://www.bilibili.com/video/BV1QarYYsEnE)
- **《ROS 2机器人开发从入门到实践》1.2.4 在Ubuntu中安装ROS2**
  - [B station](https://www.bilibili.com/video/BV1Jz421B7Ey)
- **《ROS 2机器人开发从入门到实践》1.3 运行你的第一个机器人**
  - [B station](https://www.bilibili.com/video/BV1iE421w7d5)
- **《ROS 2机器人开发从入门到实践》 1.4.5 Linux基础之环境变量**
  - [B station](https://www.bilibili.com/video/BV1pm42137bR)
- **《ROS 2机器人开发从入门到实践》 2.1.1编写你的第一个节点(Python示例)**
  - [B station](https://www.bilibili.com/video/BV1iy411i727)
- **《ROS 2机器人开发从入门到实践》 2.1.2编写你的第一个节点( C++ 示例)**
  - [B station](https://www.bilibili.com/video/BV1FH4y1c7Px)
- **《ROS 2机器人开发从入门到实践》 2.2 使用功能包组织Python节点**
  - [B station](https://www.bilibili.com/video/BV1ky411e7hp)
- **《ROS 2机器人开发从入门到实践》 2.3 使用功能包组织C++节点**
  - [B station](https://www.bilibili.com/video/BV1Pb42177BJ)
- **《ROS 2机器人开发从入门到实践》 2.4 多功能包的最佳实践WorkSpace**
  - [B station](https://www.bilibili.com/video/BV1Hx4y147gW)
- **《ROS 2机器人开发从入门到实践》2.5.1ROS2基础之编程:面向对象编程Python示例**
  - [B station](https://www.bilibili.com/video/BV1xU411U7yR)
- **《ROS 2机器人开发从入门到实践》2.5.1ROS2基础之编程:面向对象编程C++示例**
  - [B station](https://www.bilibili.com/video/BV191p2eMErj)
- **《ROS 2机器人开发从入门到实践》2.5.2用得到的C++新特性**
  - [B station](https://www.bilibili.com/video/BV1CRWWeoEso)
- **《ROS 2机器人开发从入门到实践》2.5.3.1多线程与回调函数Python示例**
  - [B station](https://www.bilibili.com/video/BV1DvWYehEWz)
- **《ROS 2机器人开发从入门到实践》2.5.3.2多线程与回调函数C++示例**
  - [B station](https://www.bilibili.com/video/BV18mWjeEEXS)
- **《ROS 2机器人开发从入门到实践》3.1话题通信介绍**
  - [B station](https://www.bilibili.com/video/BV1D3WXeSELP)
- **《ROS 2机器人开发从入门到实践》3.2.1通过话题发布小说**
  - [B station](https://www.bilibili.com/video/BV1g1sFezEpx)
- **《ROS 2机器人开发从入门到实践》3.2.2订阅小说并合成语音**
  - [B station](https://www.bilibili.com/video/BV18GWreJEVo)
- **《ROS 2机器人开发从入门到实践》3.3.1发布速度控制海龟画圆**
  - [B station](https://www.bilibili.com/video/BV1pas7eGEkk)
- **《ROS 2机器人开发从入门到实践》3.3.2订阅pose实现闭环控制**
  - [B station](https://www.bilibili.com/video/BV1mLsseKEiN)
- **《ROS 2机器人开发从入门到实践》3.4.1完成工程架构设计**
  - [B station](https://www.bilibili.com/video/BV118sMeQExX)
- **《ROS 2机器人开发从入门到实践》3.4.2自定义通信接口**
  - [B station](https://www.bilibili.com/video/BV1dTHgeeEPm)
- **《ROS 2机器人开发从入门到实践》3.4.3系统信息获取与发布**
  - [B station](https://www.bilibili.com/video/BV1GnH5eGEC3)
- **《ROS 2机器人开发从入门到实践》3.4.4在功能包中使用QT**
  - [B station](https://www.bilibili.com/video/BV1W4noe5Ezr)
- **《ROS 2机器人开发从入门到实践》3.4.5订阅数据并用Qt显示**
  - [B station](https://www.bilibili.com/video/BV1MxHvebEdL)
- **《ROS 2机器人开发从入门到实践》3.5ROS2基础之Git入门**
  - [B station](https://www.bilibili.com/video/BV1FoHreaEMc)
- **《ROS 2机器人开发从入门到实践》4.1.1服务通信介绍**
  - [B station](https://www.bilibili.com/video/BV1kAHxepEcf)
- **《ROS 2机器人开发从入门到实践》4.1.2基于服务的参数通信**
  - [B station](https://www.bilibili.com/video/BV1pGHaerErL)
- **《ROS 2机器人开发从入门到实践》4.2.1自定义服务接口**
  - [B station](https://www.bilibili.com/video/BV18rpKeUETp)
- **《ROS 2机器人开发从入门到实践》4.2.2人脸检测**
  - [B station](https://www.bilibili.com/video/BV14HHQeKEPm)
- **《ROS 2机器人开发从入门到实践》4.2.3人脸检测服务实现**
  - [B station](https://www.bilibili.com/video/BV13zpbeJEG2)
- **《ROS 2机器人开发从入门到实践》4.2.4人脸检测客户端的实现**
  - [B station](https://www.bilibili.com/video/BV1yMpBehEWW)
- **《ROS 2机器人开发从入门到实践》4.3.1自定义服务接口**
  - [B station](https://www.bilibili.com/video/BV123pJe2EgX)
- **《ROS 2机器人开发从入门到实践》4.3.2服务端代码实现**
  - [B station](https://www.bilibili.com/video/BV1ncpEevE4N)
- **《ROS 2机器人开发从入门到实践》4.3.3客户端代码实现**
  - [B station](https://www.bilibili.com/video/BV1mj4zeUELx)
- **《ROS 2机器人开发从入门到实践》4.4.1参数声明设置**
  - [B station](https://www.bilibili.com/video/BV1G54neuEiH)
- **《ROS 2机器人开发从入门到实践》4.4.2订阅参数更新**
  - [B station](https://www.bilibili.com/video/BV16T4fe4EpX)
- **《ROS 2机器人开发从入门到实践》4.4.3客户端代码实现**
  - [B station](https://www.bilibili.com/video/BV1xatKeWEFT)
- **《ROS 2机器人开发从入门到实践》4.5.1参数声明与设置**
  - [B station](https://www.bilibili.com/video/BV19k4UeXEvZ)
- **《ROS 2机器人开发从入门到实践》4.5.2接收参数事件**
  - [B station](https://www.bilibili.com/video/BV1sutteUEry)
- **《ROS 2机器人开发从入门到实践》4.5.3修改其他节点的参数**
  - [B station](https://www.bilibili.com/video/BV1dAtieREYf)
- **《ROS 2机器人开发从入门到实践》4.6.1使用Launch启动多个节点**
  - [B station](https://www.bilibili.com/video/BV1hdtLeZE9y)
- **《ROS 2机器人开发从入门到实践》4.6.2使用launch传递参数**
  - [B station](https://www.bilibili.com/video/BV18MtRePEdY)
- **《ROS 2机器人开发从入门到实践》4.6.3 launch使用进阶**
  - [B station](https://www.bilibili.com/video/BV1BMbAeKEY8)
- **《ROS 2机器人开发从入门到实践》5.1.1通过命令行使用TF**
  - [B station](https://www.bilibili.com/video/BV1ietCe2E9F)
- **《ROS 2机器人开发从入门到实践》5.1.2对TF原理的简单探究**
  - [B station](https://www.bilibili.com/video/BV1wnsCe1EgM)
- **《ROS 2机器人开发从入门到实践》5.2Python中的手眼坐标变换**
  - [B station](https://www.bilibili.com/video/BV1YesXeoEGd)
- **《ROS 2机器人开发从入门到实践》5.2.2 通过Python发布动态TF**
  - [B station](https://www.bilibili.com/video/BV1mxsheXEpc)
- **《ROS 2机器人开发从入门到实践》5.2.3通过Python查询TF关系**
  - [B station](https://www.bilibili.com/video/BV1CSszeuEH3)
- **《ROS 2机器人开发从入门到实践》5.3.1 通过C++发布静态TF**
  - [B station](https://www.bilibili.com/video/BV1h8xnePEMe)
- **《ROS 2机器人开发从入门到实践》5.3.2通过C++发布动态TF**
  - [B station](https://www.bilibili.com/video/BV12RsoefEyV)
- **《ROS 2机器人开发从入门到实践》5.3.3通过C++查询TF关系**
  - [B station](https://www.bilibili.com/video/BV1CexqevEAw)
- **《ROS 2机器人开发从入门到实践》5.4.1常用可视化工具rqt**
  - [B station](https://www.bilibili.com/video/BV1dtxmeJEbG)
- **《ROS 2机器人开发从入门到实践》5.4.2 数据化可视工具Rviz**
  - [B station](https://www.bilibili.com/video/BV1NQx4e5EoJ)
- **《ROS 2机器人开发从入门到实践》5.5 数据记录工具ros2 bag**
  - [B station](https://www.bilibili.com/video/BV1KyxeewEuY)
- **《ROS 2机器人开发从入门到实践》5.6 ROS 2基础之Git进阶**
  - [B station](https://www.bilibili.com/video/BV1qs4geDEzC)
- **《ROS 2机器人开发从入门到实践》5.6.2 Git进阶之学会撤销代码**
  - [B station](https://www.bilibili.com/video/BV1ejxDesExB)
- **《ROS 2机器人开发从入门到实践》5.6.3 Git进阶之分支**
  - [B station](https://www.bilibili.com/video/BV1tbxDejE9n)
- **《ROS 2机器人开发从入门到实践》6.1 机器人建模与仿真概述**
  - [B station](https://www.bilibili.com/video/BV1CB19Y1Ew8)
- **《ROS 2机器人开发从入门到实践》6.2 使用URDF创建机器人**
  - [B station](https://www.bilibili.com/video/BV1RT1BYQEAk)
- **《ROS 2机器人开发从入门到实践》6.2.2 在RViz中显示机器人**
  - [B station](https://www.bilibili.com/video/BV1Vq2LYoECn)
- **《ROS 2机器人开发从入门到实践》6.2.3使用Xacro简化URDF**
  - [B station](https://www.bilibili.com/video/BV1WY2WYaEwc)
- **《ROS 2机器人开发从入门到实践》6.2.4创建机器人及传感器部件**
  - [B station](https://www.bilibili.com/video/BV12a2NYJE7L)
- **《ROS 2机器人开发从入门到实践》6.2.5完善机器人执行器部件**
  - [B station](https://www.bilibili.com/video/BV1s92VYTEc7)
- **《ROS 2机器人开发从入门到实践》6.2.6贴合地面，添加虚拟部件**
  - [B station](https://www.bilibili.com/video/BV1xU2mYBE9u)
- **《ROS 2机器人开发从入门到实践》6.3.1为机器人部件添加碰撞属性**
  - [B station](https://www.bilibili.com/video/BV11J29YQESi)
- **《ROS 2机器人开发从入门到实践》6.3.2为机器人部件添加质量与惯性**
  - [B station](https://www.bilibili.com/video/BV1wJ2BYqER6)
- **《ROS 2机器人开发从入门到实践》6.4.1安装与使用Gazebo构建世界**
  - [B station](https://www.bilibili.com/video/BV1oamGYxEty)
- **《ROS 2机器人开发从入门到实践》6.4.2在Gazebo中加载机器人模型**
  - [B station](https://www.bilibili.com/video/BV1ho2dYNE6T)
- **《ROS 2机器人开发从入门到实践》6.4.3 使用Gazebo标签扩展URDF**
  - [B station](https://www.bilibili.com/video/BV1k8mNYyEjW)
- **《ROS 2机器人开发从入门到实践》6.4.4 使用两轮差速插件控制机器人**
  - [B station](https://www.bilibili.com/video/BV1wyyPYvEPy)
- **《ROS 2机器人开发从入门到实践》6.4.5 激光雷达传感器仿真**
  - [B station](https://www.bilibili.com/video/BV1vTCUYyEcX)
- **《ROS 2机器人开发从入门到实践》6.4.6惯性测量传感器仿真**
  - [B station](https://www.bilibili.com/video/BV1qLCRYYEMa)
- **《ROS 2机器人开发从入门到实践》6.4.7深度相机传感器仿真**
  - [B station](https://www.bilibili.com/video/BV1SVy8YQEzu)
- **《ROS 2机器人开发从入门到实践》6.5.1ros2_control介绍与安装**
  - [B station](https://www.bilibili.com/video/BV1f1yVYREG6)
- **《ROS 2机器人开发从入门到实践》6.5.2使用 Gazebo 接入 ros2_control**
  - [B station](https://www.bilibili.com/video/BV1VayHYqEUe)
- **《ROS 2机器人开发从入门到实践》6.5.3使用关节状态发布控制器**
  - [B station](https://www.bilibili.com/video/BV1kfyZY9EaA)
- **《ROS 2机器人开发从入门到实践》6.5.4使用力控制器控制轮子**
  - [B station](https://www.bilibili.com/video/BV18QyzY2ExG)
- **《ROS 2机器人开发从入门到实践》6.5.5使用两轮差速控制器控制机器人**
  - [B station](https://www.bilibili.com/video/BV13SyDYmEPx)
- **《ROS 2机器人开发从入门到实践》7 自主导航 让机器人自己动起来**
  - [B station](https://www.bilibili.com/video/BV1fA1bYYE5q)
- **《ROS 2机器人开发从入门到实践》7.1 机器人导航介绍**
  - [B station](https://www.bilibili.com/video/BV1gf1KYoEMf)
- **《ROS 2机器人开发从入门到实践》7.2.1构建第一章导航地图**
  - [B station](https://www.bilibili.com/video/BV1Ff1jYqEyU)
- **《ROS 2机器人开发从入门到实践》7.2.2将地图保存为文件**
  - [B station](https://www.bilibili.com/video/BV1kB1JYmEvR)
- **《ROS 2机器人开发从入门到实践》7.3.1Navigation2介绍与安装**
  - [B station](https://www.bilibili.com/video/BV1ezSiYdEJG)
- **《ROS 2机器人开发从入门到实践》7.3.2编写launch并启动导航**
  - [B station](https://www.bilibili.com/video/BV1kiSHYaEh8)
- **《ROS 2机器人开发从入门到实践》7.3.3编写launch并启动导航**
  - [B station](https://www.bilibili.com/video/BV1bNSoY6EVj)
- **《ROS 2机器人开发从入门到实践》7.3.4进行单点与路点导航**
  - [B station](https://www.bilibili.com/video/BV1bPSoY3E9D)
- **《ROS 2机器人开发从入门到实践》7.3.5导航过程中进行动态避障**
  - [B station](https://www.bilibili.com/video/BV1VdSdY2EzK)
- **《ROS 2机器人开发从入门到实践》7.3.6优化导航速度和膨胀半径**
  - [B station](https://www.bilibili.com/video/BV15CDWYbEnG)
- **《ROS 2机器人开发从入门到实践》7.3.7 优化机器人到点精度**
  - [B station](https://www.bilibili.com/video/BV1iaDMYDEHW)
- **《ROS 2机器人开发从入门到实践》7.4.1使用话题初始化机器人位姿**
  - [B station](https://www.bilibili.com/video/BV11bDDYXEsC)
- **《ROS 2机器人开发从入门到实践》7.4.2使用TF获取机器人实时位置**
  - [B station](https://www.bilibili.com/video/BV1i5DaYnE31)
- **《ROS 2机器人开发从入门到实践》7.4.3调用接口进行单点导航**
  - [B station](https://www.bilibili.com/video/BV1ALD6YXENf)
- **《ROS 2机器人开发从入门到实践》7.4.4使用接口完成路点导航**
  - [B station](https://www.bilibili.com/video/BV1NumkY9E8H)
- **《ROS 2机器人开发从入门到实践》7.5.1完成机器人系统架构设计**
  - [B station](https://www.bilibili.com/video/BV1eZm1YmEhm)
- **《ROS 2机器人开发从入门到实践》7.5.2编写巡检控制节点**
  - [B station](https://www.bilibili.com/video/BV17WmhYyEZi)
- **《ROS 2机器人开发从入门到实践》7.5.3.1添加语音播报功能（上）**
  - [B station](https://www.bilibili.com/video/BV1yQU5Y5EVu)
- **《ROS 2机器人开发从入门到实践》7.5.3.2添加语音播报功能（中）**
  - [B station](https://www.bilibili.com/video/BV1PnmZYaEox)
- **《ROS 2机器人开发从入门到实践》7.5.3.3添加语音播报功能（下）**
  - [B station](https://www.bilibili.com/video/BV1oAUiY4EUY)
- **《ROS 2机器人开发从入门到实践》7.5.4订阅图像并记录**
  - [B station](https://www.bilibili.com/video/BV1s7UrYpE1Z)
- **《ROS 2机器人开发从入门到实践》7.6.1添加自描述文件**
  - [B station](https://www.bilibili.com/video/BV19HUkYBEYV)
- **《ROS 2机器人开发从入门到实践》7.6.2将代码托管在Gitee**
  - [B station](https://www.bilibili.com/video/BV1pAUkYQE6J)
- **《ROS 2机器人开发从入门到实践》7.6.3将代码托管在GitHub**
  - [B station](https://www.bilibili.com/video/BV1mbU7YoE6t)
- **《ROS 2机器人开发从入门到实践》8.1.1pluginlib介绍与安装**
  - [B station](https://www.bilibili.com/video/BV1tbUQYREiY)
- **《ROS 2机器人开发从入门到实践》8.1.2定义插件抽象类**
  - [B station](https://www.bilibili.com/video/BV1HVBqYVECK)
- **《ROS 2机器人开发从入门到实践》8.1.3编写并生成第一个插件**
  - [B station](https://www.bilibili.com/video/BV1DYB2YnEYz)
- **《ROS 2机器人开发从入门到实践》8.1.4编写插件测试程序**
  - [B station](https://www.bilibili.com/video/BV1hjB4YhELs)
- **《ROS 2机器人开发从入门到实践》8.2.1自定义规划器介绍**
  - [B station](https://www.bilibili.com/video/BV1fSzNYHEza)
- **【面试必考】交叉熵 vs KL散度到底是什么？从惊讶度讲到损失函数，一次说清它俩的关系**
  - [B station](https://www.bilibili.com/video/BV13tMK6oEAA)
- **【面试高频】熵、交叉熵、KL 散度什么关系？一枚硬币讲透 交叉熵 = 熵 + KL**
  - [B station](https://www.bilibili.com/video/BV1BJMh6uEGj)
- **【手撕代码】交叉熵到底在惩罚什么？BCE 与多分类 CE 一次讲透**
  - [B station](https://www.bilibili.com/video/BV1vmM36EEmH)
- **【面试高频】InfoNCE Loss 和 Cross Entropy Loss 有什么区别？对比学习核心损失全解析**
  - [B station](https://www.bilibili.com/video/BV1VQMp6LEvg)
- **【面试高频】什么是语言模型：从 N-gram、数据稀疏到神经语言模型与大模型**
  - [B station](https://www.bilibili.com/video/BV1h9No6cE6x)
- **【强化学习】Q-Learning 到 DQN：TD 更新、经验回放、target 网络，为什么能玩 Atari**
  - [B station](https://www.bilibili.com/video/BV1FUKW6JE3P)
- **【强化学习最小模型】多臂老虎机：探索利用、ε-greedy、UCB、汤普森采样**
  - [B station](https://www.bilibili.com/video/BV1ZYKs6EEGQ)
- **【强化学习】Actor-Critic / A2C / A3C：优势函数 A=Q−V、多 worker 并行为什么更稳**
  - [B station](https://www.bilibili.com/video/BV13bKt6UELM)
- **【强化学习】Actor-Critic / A2C / A3C：优势函数 A=Q−V、多 worker 并行为什么更稳**
  - [B station](https://www.bilibili.com/video/BV15fKx6nEDN)
- **【手撕代码】寻找质数：为什么只需试除到 √n？从暴力到埃氏筛**
  - [B station](https://www.bilibili.com/video/BV1TYKx6MEBZ)
- **【机器学习】决策树三兄弟 ID3 / C4.5 / CART：划分标准、结构差异、工程选用**
  - [B station](https://www.bilibili.com/video/BV1J5gR6mEuu)
- **【机器学习】K-means 聚类讲透：两步迭代 + 肘部法则 + EM 视角**
  - [B station](https://www.bilibili.com/video/BV1E5gR6mEdn)
- **【机器学习】L1 vs L2 正则化：为什么 L1 产生稀疏解？几何/梯度/贝叶斯三视角**
  - [B station](https://www.bilibili.com/video/BV1nVgR6EExs)
- **【机器学习】逻辑回归：名字叫回归 本质是分类——Sigmoid / 决策边界 / 交叉熵 一次讲透**
  - [B station](https://www.bilibili.com/video/BV177gR61EJX)
- **【强化学习】SARSA vs Q-learning：一个绕悬崖一个贴悬崖，On/Off-Policy 本质**
  - [B station](https://www.bilibili.com/video/BV18vgR6PEbf)
- **【强化学习基石】TD 时序差分：MC 采样 + DP bootstrap，SARSA / Q-learning / Actor-Critic 全是它的实例**
  - [B station](https://www.bilibili.com/video/BV1uvgR6PEin)
- **【手撕面试】AUC 0.8 到底是什么意思：正样本排在负样本前面的概率，三行代码手撕**
  - [B station](https://www.bilibili.com/video/BV1ampE6YEkX)
- **【从 Transformer 到大模型现代架构 01/20】大模型到底在算什么：下一词预测**
  - [B station](https://www.bilibili.com/video/BV1SSpE6cECv)
- **【RL 入门到 GRPO 01】强化学习到底在学什么？监督学习给答案，RL 只给一个分数**
  - [B station](https://www.bilibili.com/video/BV1HAhU6WEod)
- **【RL 入门到 GRPO 02】折扣因子 γ 到底在决定什么？为什么大模型里直接取 1**
  - [B station](https://www.bilibili.com/video/BV1HThU6DEJi)
- **【RL 入门到 GRPO 03】V、Q 和 Advantage 分别在算什么？贝尔曼方程与 PPO 的 Critic**
  - [B station](https://www.bilibili.com/video/BV16ThU6DEk9)
- **【RL 入门到 GRPO 04】蒙特卡洛和 TD 差在哪？偏差方差的取舍与 TD 误差 δ**
  - [B station](https://www.bilibili.com/video/BV1nKhU6HEva)
- **【RL 入门到 GRPO 05】策略梯度是怎么推出来的？REINFORCE 与 DeepSeekMath 的统一形式**
  - [B station](https://www.bilibili.com/video/BV14Zhm6oE5i)
- **【RL 入门到 GRPO 06】baseline 为什么不引入偏差？减 V 得到优势，GRPO 减的是组平均**
  - [B station](https://www.bilibili.com/video/BV14Zhm6oEPG)
- **【RL 入门到 GRPO 07】Actor-Critic 为什么要两个网络？Critic 的作业与它在大模型上的代价**
  - [B station](https://www.bilibili.com/video/BV1Tohm6bE1K)
- **【RL 入门到 GRPO 08】GAE 的 λ 到底在调什么？λ 为什么可以比 γ 小得多**
  - [B station](https://www.bilibili.com/video/BV1Tohm6bEe4)
- **【RL 入门到 GRPO 09】重要性采样是什么？旧策略采的数据为什么还能用、能用到什么程度**
  - [B station](https://www.bilibili.com/video/BV1schU6REqP)
- **【RL 入门到 GRPO 10】从 TRPO 到 PPO：KL 围栏与 clip 剪刀，ε 为什么是 0.2**
  - [B station](https://www.bilibili.com/video/BV1WFhU6xED8)
- **【RL 入门到 GRPO 11】PPO 完整训练流程：三步一轮、三项损失，以及大模型版的参数**
  - [B station](https://www.bilibili.com/video/BV1WFhU6xEmR)
- **【RL 入门到 GRPO 12】大模型怎么变成策略？单步老虎机与 token 级 MDP 的两种看法**
  - [B station](https://www.bilibili.com/video/BV1LjhU6yEy1)
- **【RL 入门到 GRPO 13】RLHF 三阶段是怎么串起来的？InstructGPT 的三个数与对齐税**
  - [B station](https://www.bilibili.com/video/BV17LhU6LEDs)
- **【RL 入门到 GRPO 14】Reward Model 是怎么训出来的？Bradley-Terry 与 batch 的反直觉细节**
  - [B station](https://www.bilibili.com/video/BV1LJhU6kEkp)
- **【RL 入门到 GRPO 15】KL 惩罚在拴住谁？β 的取值、k3 估计，以及放奖励还是放损失**
  - [B station](https://www.bilibili.com/video/BV1iEhU6VEm5)
- **【RL 入门到 GRPO 16】PPO 的四个模型：谁在学、谁在看，以及显存为什么是它的死穴**
  - [B station](https://www.bilibili.com/video/BV1vEhU6VE81)
- **【RL 入门到 GRPO 17】DPO 是怎么推出来的？闭式解、配分函数与「你的语言模型其实是个 Reward Model」**
  - [B station](https://www.bilibili.com/video/BV1fghU6UEUB)
- **【RL 入门到 GRPO 18】GRPO 到底改了 PPO 什么？去掉 Critic、换成组内基线、KL 进损失**
  - [B station](https://www.bilibili.com/video/BV1e6hm6uEYW)
- **【RL 入门到 GRPO 19】GRPO 的两个偏差藏在哪？Dr. GRPO 删两个分母、DAPO 放宽 clip 治熵坍塌**
  - [B station](https://www.bilibili.com/video/BV1EVhU62Ein)
- **【RL 入门到 GRPO 20】DeepSeek-R1 做对了什么？规则奖励、顿悟时刻与四阶段配方**
  - [B station](https://www.bilibili.com/video/BV17VhU62EwM)
- **【面试高频】SFT 为什么要 Mask 掉 User 的部分？只学 Assistant，label 设 -100**
  - [B station](https://www.bilibili.com/video/BV1KyNH6nEPk)
- **【面试高频】指令微调 Instruction Tuning：多任务、统一格式、零样本泛化，和 RLHF 别搞混**
  - [B station](https://www.bilibili.com/video/BV1qLKj6ZE8D)
- **【面试高频】PEFT 参数高效微调五种方法：Adapter/Prefix/P-Tuning/Prompt Tuning/LoRA 对比**
  - [B station](https://www.bilibili.com/video/BV1VUNo6vE1H)
- **【微调排障】chat template 不一致：不报错但效果暴降的 silent error**
  - [B station](https://www.bilibili.com/video/BV1t68264Eyx)
- **【微调实操】LoRA 超参调优：rank、alpha、target modules 与学习率怎么设**
  - [B station](https://www.bilibili.com/video/BV1VY826wEd2)
- **【微调必修】LoRA 显存悖论：只训 1% 参数，为什么显存没等比例下降**
  - [B station](https://www.bilibili.com/video/BV1aq826bExU)
- **【立项必答】SFT 到底需要多少条数据？从 LIMA 与 Alpaca 的对比讲透质量与数量**
  - [B station](https://www.bilibili.com/video/BV1Rg8s6qEyy)
- **【微调排障】SFT 后的三种退化：重复、啰嗦、幻觉加剧各自的根因与修复**
  - [B station](https://www.bilibili.com/video/BV1YL8s6PENV)
- **【SFT 排障】第二个 epoch loss 断崖暴跌：三大根因、判断方法与五个避免手段**
  - [B station](https://www.bilibili.com/video/BV1hL8s6PE3u)
- **【大模型基础】SFT 和预训练的区别在哪里？损失掩码机制详解**
  - [B station](https://www.bilibili.com/video/BV19V8s6vEKY)
- **【DeepSeek R1】冷启动 SFT 详解：千条数据为什么能解决 R1-Zero 的可读性问题**
  - [B station](https://www.bilibili.com/video/BV14V8t6AELz)
- **【SFT 进阶】多轮对话训练详解：上下文拼接、loss mask 与长对话截断**
  - [B station](https://www.bilibili.com/video/BV1wgbL6XE3k)
- **【推理提升】RFT 拒绝采样微调详解：性价比最高的推理能力提升方法**
  - [B station](https://www.bilibili.com/video/BV1kdb76fEAX)
- **【SFT 调参】学习率实操指南：十分之一法则、经验值与两侧症状**
  - [B station](https://www.bilibili.com/video/BV1TAb76KEap)
- **【SFT 数据】GRAPE：用目标模型概率挑回答，三分之一数据为什么能超过 Tulu3-SFT**
  - [B station](https://www.bilibili.com/video/BV1VneY6qEhN)
- **【Qwen3 技术报告】思考与非思考模式怎么训进一个模型？空 think 块、/no_think 标记与涌现的思考预算**
  - [B station](https://www.bilibili.com/video/BV18mea6FEt1)
- **【训练排障】LoRA 开梯度检查点后 loss 纹丝不动，根因是什么？enable_input_require_grads 与 use_reentrant**
  - [B station](https://www.bilibili.com/video/BV1ezea6vE4D)
- **【SFT 面试】为什么用 SFT 教模型新知识，反而会让它更爱编？未知样本学得慢、学会后幻觉线性上升**
  - [B station](https://www.bilibili.com/video/BV1Yrea6PEJH)
- **【SFT 评测】SFT 之后模型对提示词措辞更鲁棒了吗？1.7B/4B 降 54%~71%，8B 几乎为零**
  - [B station](https://www.bilibili.com/video/BV1Wfea6QEWG)
- **【SFT 进阶】SFT 里每个 token 都该学吗？Rho-1 超额损失选 token 与 ProFit 屏蔽低概率措辞**
  - [B station](https://www.bilibili.com/video/BV1Wfea6QEJ9)
- **【SFT 调参】六个决定一次讲透：为什么按验证 loss 早停会停错？LoRA lr 1e-3、过 2 轮 IFEval 退化、Muon**
  - [B station](https://www.bilibili.com/video/BV1knea6mErC)
- **【SFT 面试】为 RL 准备的 SFT 为什么不该追求最低 loss？TailSFT、SWE-Prime 与数据选择的容量边界**
  - [B station](https://www.bilibili.com/video/BV16xea65ExR)
- **【SFT 面试】SFT 一定要 mask 掉 prompt 吗？指令长 5 倍、样本少于 1 万时给 prompt 算 loss 反而涨点**
  - [B station](https://www.bilibili.com/video/BV1UTea64E3a)
- **【面试高频】梯度裁剪原理：按范数裁剪 vs 按值裁剪，阈值怎么设，为什么必开**
  - [B station](https://www.bilibili.com/video/BV14ZNa6HEru)
- **【面试高频】大模型训练为何突然 NaN？QK-Norm 两行代码治好注意力 logit 爆炸**
  - [B station](https://www.bilibili.com/video/BV1UUua6wEVU)
- **【微调实操】灾难性遗忘的五种缓解方法：从 LoRA rank 到任务向量加法**
  - [B station](https://www.bilibili.com/video/BV1PD826SEFs)
- **【训练稳定性】梯度裁剪详解：静态全局范数裁剪与 AdaGC 自适应裁剪**
  - [B station](https://www.bilibili.com/video/BV1EH826zEU7)
- **【RLHF 排障】三大崩溃现象诊断：reward 崩塌、KL 爆炸、输出发散**
  - [B station](https://www.bilibili.com/video/BV1Bu8S6LEJU)
- **【训练排障】loss 突然变 NaN 怎么办？脏数据、梯度爆炸、精度溢出三路排查**
  - [B station](https://www.bilibili.com/video/BV13f846kEU1)
- **【训练排障】训练不收敛的系统排查清单：学习率、数据、初始化、精度四步走**
  - [B station](https://www.bilibili.com/video/BV1LQ8467E4e)
- **【持续学习】数据回放详解：配比、选样与遗忘监控**
  - [B station](https://www.bilibili.com/video/BV1MT8t6TEaB)
- **【训练踩坑】token level mean vs sequence level sum：一个除法决定训练稳定还是崩溃**
  - [B station](https://www.bilibili.com/video/BV1qNbE6XEfw)
- **【训练调试】可复现性详解：cuDNN、DataLoader 与分布式浮点误差三大随机源**
  - [B station](https://www.bilibili.com/video/BV1iMbE6DEbj)
- **【训练诊断】train vs val loss：过拟合、欠拟合的判断标准与量化指标**
  - [B station](https://www.bilibili.com/video/BV1RTbE6HEkW)
- **【训练监控】除了 loss 还必须看的五个指标：grad norm、PPL、MFU、学习率、吞吐量**
  - [B station](https://www.bilibili.com/video/BV1zwbE6REWX)
- **【持续学习】三种技术路线：经验回放、EWC 与渐进式网络（LoRA adapter）**
  - [B station](https://www.bilibili.com/video/BV17pb76pEuR)
- **【训练监控】梯度范数多大算正常？基线建立与三种预警阈值设法**
  - [B station](https://www.bilibili.com/video/BV1Urb76uETw)
- **【训练监控】WandB 与 TensorBoard 选型 + 必须记录的六大指标**
  - [B station](https://www.bilibili.com/video/BV1gobj6gE67)
- **【训练排障】变长 SFT 开梯度累积，loss 为什么会系统性偏高？HF Trainer 存在两年的归一化 bug**
  - [B station](https://www.bilibili.com/video/BV1LReh6iES9)
- **【后训练面试】为什么 RL 比 SFT 更不容易遗忘？陈丹琦组消融：关键是 on-policy 数据而不是 KL**
  - [B station](https://www.bilibili.com/video/BV1oUeh6zEr8)
- **【训练排障】训练末期 grad norm 为什么反而上升？weight decay 与 LR 衰减的耦合，AdamC 一行修正**
  - [B station](https://www.bilibili.com/video/BV1mMea6dEtA)
- **强化学习中的熵坍塌**
  - [B station](https://www.bilibili.com/video/BV1qY9NBCEo2)
- **【面试高频】什么是熵坍塌和 Reward Hacking？它们的关系与解决办法**
  - [B station](https://www.bilibili.com/video/BV1j1M36UEP1)
- **【面试高频】什么是 Rollout？RL 训练的经验采样，四步流程 + 为什么是头号瓶颈**
  - [B station](https://www.bilibili.com/video/BV14rNH6pEvw)
- **【面试进阶】熵坍塌为什么发生？又如何解决？从协方差机制到 Clip-Higher**
  - [B station](https://www.bilibili.com/video/BV1rKKx6dEjc)
- **【RLHF】KL 惩罚系数 β 怎么调？太小 Reward Hacking，太大学不动**
  - [B station](https://www.bilibili.com/video/BV1ck3R6pE2G)
  - links: https://arxiv.org/abs/2203.02155 https://arxiv.org/abs/2307.09288
- **【RL 工程】RLEP 经验回放：把高质量 rollout 存进 buffer 反复利用**
  - [B station](https://www.bilibili.com/video/BV1fK8S6jE8G)
- **【RLHF 调参】PPO 三大超参详解：clip range、KL coefficient、GAE lambda**
  - [B station](https://www.bilibili.com/video/BV1w9b76wE6Z)
- **【RL 工程】batch 组织策略：难度分布、类型平衡与 rollout 数量**
  - [B station](https://www.bilibili.com/video/BV1Kmb76KEqu)
- **【RL 调参】entropy bonus 详解：系数怎么设、衰减调度怎么做、熵坍缩怎么救**
  - [B station](https://www.bilibili.com/video/BV1Tmb76KEFh)
- **【RL 工程】rollout 是 RL 训练的瓶颈：vLLM 加速与异步训练详解**
  - [B station](https://www.bilibili.com/video/BV1N1b76qEif)
- **【RLHF 监控】target KL 设置与 KL 曲线诊断**
  - [B station](https://www.bilibili.com/video/BV12yb76TEzJ)
- **【RL 基础】探索与利用的平衡：epsilon-greedy、UCB、entropy bonus 与好奇心驱动**
  - [B station](https://www.bilibili.com/video/BV1UBb763E1D)
- **【RL 调参】rollout 采样温度：让 group 内有区分度才有训练信号**
  - [B station](https://www.bilibili.com/video/BV1DBb763EHZ)
- **【RL 加速】用投机解码给 rollout 提速：draft 模型选择与命中率优化**
  - [B station](https://www.bilibili.com/video/BV1KTb76YELi)
- **【异步 RL】PPO-EWMA：通过参数滑动平均改进 old logits 缺失问题，重要性比为什么要拆成两项**
  - [B station](https://www.bilibili.com/video/BV1BVeY6GEwD)
- **【推理 Infra】Batch 不变内核：通过固定归约顺序消除大模型推理的不确定性，RL 训推 KL 归零**
  - [B station](https://www.bilibili.com/video/BV173eY6CESH)
- **【Agentic RL 复盘】GPT-OSS 做 RL 为什么 KL 一开训就爆炸？MoE 路由、attention sink 与显存三个坑**
  - [B station](https://www.bilibili.com/video/BV1VpeY6KEtn)
- **【MoE × RL】R3：通过重放推理时的专家路由，改进 MoE 做 RL 时训推路由不一致导致的崩溃 #大会员10周年**
  - [B station](https://www.bilibili.com/video/BV1UTea64E41)
- **【RL 训练稳定性】训推不一致为什么是优化问题而不是精度问题？按回答长度激增触发学习率减半**
  - [B station](https://www.bilibili.com/video/BV1h1ea6hEhW)
- **【RL 长训练】ProRL：通过验证停滞时重置参考策略，改进 RL 训几百步就停滞的问题**
  - [B station](https://www.bilibili.com/video/BV1akea6YEjg)
- **【RL 训练】RL 的 batch 越大训练越快吗？√B 学习率缩放与「吞吐增益 > 样本惩罚」决策不等式**
  - [B station](https://www.bilibili.com/video/BV1HceY6nEUr)
- **【RL 数据准备】RL 训练数据的难度怎么定？待训模型跑 8 次筛题、镜像 J 形分布、通过率拉回 50%**
  - [B station](https://www.bilibili.com/video/BV1rWea61Erm)
- **【RL 排障】RL 后期熵为什么会突然暴涨？正负样本不对称与 token 级熵流失衡，常规旋钮为何无效**
  - [B station](https://www.bilibili.com/video/BV1ppea67Eni)
- **【RLVR 多样性】Uniqueness-Aware RL：通过按解题策略聚类加权优势，改进 RLVR 解题策略单一化的坍缩问题**
  - [B station](https://www.bilibili.com/video/BV1rpea6jELJ)
- **【长 CoT RL】max response length 该分阶段放开还是一步到位？DeepScaleR、Skywork-OR1 与 Polaris 反例**
  - [B station](https://www.bilibili.com/video/BV12Vea6pEBV)
- **【RL 前沿】BroRL：通过把每题 rollout 从 16 加到 512 改进 RL 训练饱和的问题（NVIDIA）**
  - [B station](https://www.bilibili.com/video/BV1f4ea6CETH)
- **【RL 训练动力学】GRPO 的训练曲线能预测吗？用阻尼振子解释动量、陈旧度与 group size**
  - [B station](https://www.bilibili.com/video/BV1RZeh6YETk)
- **【RL 系统】APRIL：通过 partial rollout 改进同步 RL 的长尾等待，多发一倍、够了就停、没写完续写**
  - [B station](https://www.bilibili.com/video/BV1jDeh6uEYy)
- **【RL 省显存】QeRL：4-bit 量化噪声为什么让 RL 探索更好？32B 模型单卡 H100 跑 GRPO**
  - [B station](https://www.bilibili.com/video/BV1ZUeh6zECH)
- **【RL 超参】RL 的学习率为什么比 SFT 小 10 倍？1e-5 断崖式崩溃、JustRL 恒定 1e-6 与 LoRA 例外**
  - [B station](https://www.bilibili.com/video/BV1R9eh6KEMN)
- **【RLVR 多样性】多样性坍塌发生在哪？集中在开头几个 token，只插值第 20 到 28 层就能找回 37% 覆盖**
  - [B station](https://www.bilibili.com/video/BV1LQeh6BE1J)
- **【RL 训练】LLMZero：通过 Agent 逐 checkpoint 诊断与树搜索改进 RL 超参的固定日程问题**
  - [B station](https://www.bilibili.com/video/BV1dQeh6qEJJ)
- **【面试高频】BLEU 与 ROUGE 讲透：精确率 vs 召回率、简短惩罚与最长公共子序列**
  - [B station](https://www.bilibili.com/video/BV1X9No6cEVf)
- **【评测原理】pass@k 怎么推导计算：无偏估计公式 1−C(n−c,k)/C(n,k)，有偏 vs 无偏**
  - [B station](https://www.bilibili.com/video/BV1DMK46VEAW)
- **【跑分黑箱】GSM8K 数据污染：benchmark 过拟合、n-gram 重叠检测、记忆探测**
  - [B station](https://www.bilibili.com/video/BV1PzKx6PEo3)
- **【大模型评估】Elo 评分与 Bradley-Terry：Chatbot Arena 排名系统讲透**
  - [B station](https://www.bilibili.com/video/BV17U3R6EENL)
- **【MT-Bench 实测】LLM-as-Judge 的四大偏差：位置/冗长/自我偏好/风格**
  - [B station](https://www.bilibili.com/video/BV1f13R6JEfP)
- **【大模型评估】MMLU 分数有水分？57 个学科的评估细节、三大坑与改进版**
  - [B station](https://www.bilibili.com/video/BV1e8826PEiP)
- **【上线必修】压力测试六维度：超长、空输入、特殊字符、多语言、对抗与重复**
  - [B station](https://www.bilibili.com/video/BV1PUb76vEkx)
- **【训练工程】评测频率怎么定？proxy 高频看趋势、完整低频做决策，兼谈数据污染**
  - [B station](https://www.bilibili.com/video/BV1FZb76bEW8)
- **【评测陷阱】benchmark 分数为什么会骗你？数据泄露与过拟合的检测方法**
  - [B station](https://www.bilibili.com/video/BV1eab76jEkY)
- **【评测可信度】数据污染的检测与清洗：n-gram、embedding 与 PPL 三重检测**
  - [B station](https://www.bilibili.com/video/BV1mrb76uEDc)
- **【RL 面试】RL 涨分是真学会还是在背题？Qwen 数学基准污染、记忆锚点电路与模型任务对齐度**
  - [B station](https://www.bilibili.com/video/BV1R9eh6KEhk)
- **【RLHF】RM 分数涨人类却摇头？Goodhart 定律与 Reward Overoptimization 讲透**
  - [B station](https://www.bilibili.com/video/BV1RX3R6yEh3)
- **【RLHF】为什么 ChatGPT 越训话越多？Length Bias 的来龙去脉**
  - [B station](https://www.bilibili.com/video/BV1J23R6SE52)
- **【RLHF】Reward Model Ensemble：一个 RM 易被骗，K 个 RM 投票才公正**
  - [B station](https://www.bilibili.com/video/BV15R3R65E2J)
- **【大模型对齐】Self-Rewarding LM：不要 Reward Model，让 LLM 自己当裁判**
  - [B station](https://www.bilibili.com/video/BV1XZ3R63EYU)
- **【面试高频】PRM vs ORM：过程奖励为什么碾压结果奖励？一次讲透**
  - [B station](https://www.bilibili.com/video/BV1UUua6wE44)
- **【对齐前沿】检测到模型作弊，为什么不该丢弃整条 rollout？GLM-5.2 在线守卫详解**
  - [B station](https://www.bilibili.com/video/BV1A9826mEDt)
- **【推理 RL】奖励稀疏问题详解：奖励塑形、课程学习、好奇心驱动与 PRM**
  - [B station](https://www.bilibili.com/video/BV1Lg8S6yE84)
- **【面试高频】规则奖励 vs 奖励模型：两种奖励来源的优劣与选择策略**
  - [B station](https://www.bilibili.com/video/BV1Sx8S6YESV)
- **【Yuan3.0】RIRM + RAPO：用负奖励改进推理模型答对后仍继续反思的浪费**
  - [B station](https://www.bilibili.com/video/BV1LX8462E9d)
- **【Reasoning RL】RLVR 数据准备全流程：格式、冷启动、反思 token 与课程学习**
  - [B station](https://www.bilibili.com/video/BV1uob56aEMT)
- **【对齐必修】reward hacking 详解：Goodhart 定律与五种实用防御手段**
  - [B station](https://www.bilibili.com/video/BV16Rb768EZo)
- **【RL 工程】reward 归一化详解：running mean-std、batch 归一化与三个常见坑**
  - [B station](https://www.bilibili.com/video/BV1CDb76AEk8)
- **【推理 RL】Cliff：通过标注第一处出错改进 GRPO 结果奖励过粗的问题，λ 为什么必须设 0**
  - [B station](https://www.bilibili.com/video/BV1nPeY6EEQq)
- **【RL 奖励设计】RLVR 该不该给格式奖励？FrameThinker 消融与 Open-Reasoner-Zero 无格式分实践**
  - [B station](https://www.bilibili.com/video/BV1V7eY6zEeZ)
- **【RL 奖励】探针裁判：从 1.7B 小模型隐藏层读 rubric 判断，为什么能超过 8B 生成式裁判**
  - [B station](https://www.bilibili.com/video/BV15JeY6MEnz)
- **【RLVR 数据】RLVE：通过程序化生成、难度自适应的可验证环境，改进 RL 静态题库的信号衰减问题**
  - [B station](https://www.bilibili.com/video/BV1Yrea6PE1R)
- **【Agent 安全】为什么 RL 后训练的 Agent 更爱作弊？同基座作弊率 23 倍，环境加固砍掉 87.7%**
  - [B station](https://www.bilibili.com/video/BV1sdea69ELG)
- **【RL 奖励】没有标准答案的任务怎么做 RL？给裁判一份参考回答，比 SFT 蒸馏高 20 分**
  - [B station](https://www.bilibili.com/video/BV1tSea6ZEQm)
- **【RL 前沿】VerIF：用代码校验硬约束、推理模型判软约束，改进指令遵循 RL 的验证难题，IFEval 68.4→84.5**
  - [B station](https://www.bilibili.com/video/BV1vYea6zEDe)
- **【RLVR 工程】训练前为什么要先 fuzz 你的 verifier？93% 判卷失败来自空格标点、版本间半数判法相反**
  - [B station](https://www.bilibili.com/video/BV1qaea6gE6K)
- **【AI 安全】为什么不能把思维链监控写进 RL 奖励？混淆式作弊、反馈外溢与可监控性税**
  - [B station](https://www.bilibili.com/video/BV1B4ea6CES3)
- **【RLVR 面试】奖励随机错 40% 为什么 RL 还能训？看训练奖励饱和速度判断模型在学还是在背**
  - [B station](https://www.bilibili.com/video/BV1Xoeh6PEzc)
- **【RL 奖励】LLM 裁判为什么会被一个 token 骗过？万能钥匙攻击、Master-RM 与 rubric dropout**
  - [B station](https://www.bilibili.com/video/BV15Zeh6eEBg)
- **【大模型训练】Scaling Law 到底是什么原理？从幂律直线到 Chinchilla 黄金配比全解析**
  - [B station](https://www.bilibili.com/video/BV1ECTj6YEyT)
- **【面试必考】大模型为什么很少用Dropout？从过拟合讲到单epoch时代，config考古实锤**
  - [B station](https://www.bilibili.com/video/BV1YhT46HEhM)
- **【面试高频】训练算力 6ND 公式详解：前向 2N / 反向 4N 怎么来的？MoE 激活参数与 Chinchilla 一并讲透**
  - [B station](https://www.bilibili.com/video/BV1jzNa6eEom)
- **【面试高频】训练算力 6ND 公式详解：前向 2N / 反向 4N 怎么来的？MoE 激活参数与 Chinchilla 一并讲透**
  - [B station](https://www.bilibili.com/video/BV1eTKM6wEx6)
- **【大模型基础】预训练为什么只做「预测下一个词」就能学到知识？兼谈曝光偏差**
  - [B station](https://www.bilibili.com/video/BV1RL8S6gEDV)
- **【训练常识】大模型预训练为什么只跑 1 个 epoch？三个原因与什么时候可以多跑**
  - [B station](https://www.bilibili.com/video/BV1vR846LEHM)
- **【垂域实操】继续预训练的数据配比与遗忘防御：D-CPT Law 与三招工程手段**
  - [B station](https://www.bilibili.com/video/BV1T38t6eEtb)
- **【训练技巧】大模型预训练为什么不用 Dropout？三个副作用与替代的正则化机制**
  - [B station](https://www.bilibili.com/video/BV1xY8468Evd)
- **【训练技巧】Label Smoothing 在大模型上为什么基本不用？**
  - [B station](https://www.bilibili.com/video/BV1cVbL6DEHz)
- **【训练技巧】早停配置详解：patience、验证集选择与预训练为何不用早停**
  - [B station](https://www.bilibili.com/video/BV17Wb76QEma)
- **【训练配置】序列长度怎么选？O(n²) 成本、主流演进与分阶段扩展**
  - [B station](https://www.bilibili.com/video/BV1Sib76kEZk)
- **【预训练面试】大模型真的不该用 Dropout 吗？层级 Dropout 配 1/ρ 缩放，8.2B 少用 25% 训练算力（Cerebras）**
  - [B station](https://www.bilibili.com/video/BV1y7ea6SEe6)
- **【ICML 2025】CPT Scaling Law：用分布偏移项与退火面积预测继续预训练的 loss 曲线**
  - [B station](https://www.bilibili.com/video/BV1Rvea6MEhE)
- **【预训练前沿】专用预训练 SPT：领域数据混进预训练，为什么 1B 能打赢微调的 3B**
  - [B station](https://www.bilibili.com/video/BV1Zbea6GEq7)
- **【ICLR 2026】数据重复训练，决定过拟合的是次数还是间隔？记忆窗口与 190 个 epoch**
  - [B station](https://www.bilibili.com/video/BV1XFea6wEqq)
- **【推理 RL】OctoThinker：通过中段训练补推理语料，改进 Llama 做 RL 时长度失控、不涨分的问题**
  - [B station](https://www.bilibili.com/video/BV19Fea6wEg4)
- **【面试高频】什么是 Checkpoint？梯度/激活检查点：大模型省显存的救命技巧**
  - [B station](https://www.bilibili.com/video/BV1dmM36EESX)
- **【面试进阶】张量并行为什么先列切再行切？MLP 的切分秘密全在 GELU**
  - [B station](https://www.bilibili.com/video/BV1nCKW6XEji)
- **【面试高频】大模型训练所需显存怎么计算？三大件 + RLHF 讲透**
  - [B station](https://www.bilibili.com/video/BV1R7gD6FEF5)
- **【面试高频】一层 Decoder 张量并行需要几次通信？答案 4 次 All-Reduce**
  - [B station](https://www.bilibili.com/video/BV1ZXKx6WEnK)
- **【面试高频】Scatter/Gather/Reduce/AllReduce 分别是什么？5 个通信原语一张图讲透**
  - [B station](https://www.bilibili.com/video/BV1wCKx6hEoy)
- **【面试高频】DeepSpeed 的 3 个 Stage 是什么？ZeRO 逐级切分省显存讲透**
  - [B station](https://www.bilibili.com/video/BV1BuKx69EDn)
- **【ZeRO 显存优化】70 亿参数训练要 110G？三刀砍掉 100G 冗余**
  - [B station](https://www.bilibili.com/video/BV13tgX6cEYZ)
- **【分布式训练收官】序列并行 × 专家并行：百万 token 与上千专家的解法**
  - [B station](https://www.bilibili.com/video/BV1VxgX6aEz8)
- **【Megatron 张量并行】一层都装不下？把权重矩阵劈开算 —— 4 次 AllReduce 讲透**
  - [B station](https://www.bilibili.com/video/BV1GxgX6aELP)
- **【Ring AllReduce】打破参数服务器瓶颈：PyTorch DDP 的底层核心**
  - [B station](https://www.bilibili.com/video/BV1Qggd6uE9u)
- **【流水线并行】显卡摸鱼的元凶：GPipe 挤气泡 vs PipeDream 1F1B**
  - [B station](https://www.bilibili.com/video/BV15WgR6rEfr)
- **【训练工程】断点续训详解：为什么恢复权重远远不够**
  - [B station](https://www.bilibili.com/video/BV1UB826dEuV)
- **【分布式训练】通信瓶颈详解：为什么多节点训练卡在网络而不是算力**
  - [B station](https://www.bilibili.com/video/BV1FF8m6CEdp)
- **【训练工程】大规模训练容错：Flash Checkpoint、DLRover 与 checkpoint 频率权衡**
  - [B station](https://www.bilibili.com/video/BV1H58265EA1)
- **【训练效率】MFU 和 GPU 利用率的区别在哪里？兼谈 MFU 与 HFU**
  - [B station](https://www.bilibili.com/video/BV1Vh826YExp)
- **【RLHF 工程】PPO 训练显存爆炸怎么办？四模型驻留、offload 与稳定性调参**
  - [B station](https://www.bilibili.com/video/BV15V8S6kEkq)
- **【显存必修】训练显存花在哪？缩 batch、梯度检查点、ZeRO、LoRA 四级省显存阶梯**
  - [B station](https://www.bilibili.com/video/BV15Q8467EdP)
- **【显存优化】激活检查点选层策略：Uniform、Selective 与根号 n 法则**
  - [B station](https://www.bilibili.com/video/BV1xg8t6NEQW)
- **【混合精度】BF16 / FP16 / FP8 选型决策树：尾数指数位数决定一切**
  - [B station](https://www.bilibili.com/video/BV1NV8t6AEpU)
- **【训练加速】FP8 训练实操：E4M3/E5M2 选型、分层策略与 Transformer Engine 配置**
  - [B station](https://www.bilibili.com/video/BV1D9b56eEv4)
- **【训练工程】GPU 利用率周期性归零：IO 瓶颈的定位与优化**
  - [B station](https://www.bilibili.com/video/BV1xfb56cEdo)
- **【混合精度】Loss Scaling 与 GradScaler 详解：FP16 下溢怎么救，BF16 为何不用**
  - [B station](https://www.bilibili.com/video/BV1JjbL6UEEe)
- **【DeepSpeed 配置】ZeRO Stage 怎么选、offload 怎么开：config.json 手把手**
  - [B station](https://www.bilibili.com/video/BV1WTbL6REnE)
- **【分布式必修】并行策略选型决策树：DDP、ZeRO、张量并行、流水线并行**
  - [B station](https://www.bilibili.com/video/BV1w9b76wE1c)
- **【性能分析】给训练做体检：PyTorch Profiler 与 nsys 的用法与瓶颈定位**
  - [B station](https://www.bilibili.com/video/BV1eMbE6DEWh)
- **【训练效率】长度分桶策略：padding 浪费 98% 是怎么发生的**
  - [B station](https://www.bilibili.com/video/BV1dxb76JEjP)
- **【分布式训练】同步 vs 异步梯度更新：staleness 与 99% 选同步的理由**
  - [B station](https://www.bilibili.com/video/BV1Uzb766EtP)
- **【训练效率】序列 Packing 实现详解：装箱算法、cu_seqlens 与 block diagonal mask**
  - [B station](https://www.bilibili.com/video/BV1KPb76vEWq)
- **【训练效率】varlen attention 配置详解：cu_seqlens、position_ids 与 packing 的配套关系**
  - [B station](https://www.bilibili.com/video/BV1MZbj6zEeK)
- **【混合精度面试】纯 bf16 训练为什么会停滞？相对更新小于 0.39% 就被舍入吞掉**
  - [B station](https://www.bilibili.com/video/BV1viea6qEhh)
- **【训练显存】大词表训练时 logits 为什么吃掉 89% 显存？Cut Cross-Entropy 与 Liger Kernel 讲透**
  - [B station](https://www.bilibili.com/video/BV19Reh6vEk5)
- **【面试必考】大模型Agent的Function Calling怎么设计更稳定？约束解码/工具检索/校验重试三层拆解**
  - [B station](https://www.bilibili.com/video/BV14aMP6jEj3)
- **【面试前沿】大模型Agentic RL最新方向到底是什么？从GLM/Qwen看RL的下半场**
  - [B station](https://www.bilibili.com/video/BV1HcMP6qEfQ)
- **【面试前沿】Agentic RL 中的行为崩塌到底是什么？从 Search-R1 复现看行为相变**
  - [B station](https://www.bilibili.com/video/BV1vNMu6gEkG)
- **【Agent 工程】工具调用失败时，怎么保证 Agent 不死循环或乱回答？**
  - [B station](https://www.bilibili.com/video/BV1oZT161Ez4)
- **【论文精读】35B 打平万亿参数？该 Scale 的是轨迹不是参数**
  - [B station](https://www.bilibili.com/video/BV1GrMx6SE63)
- **【论文精读】Agent 最缺的能力是收手？28000 任务实测｜Agentic Abstention**
  - [B station](https://www.bilibili.com/video/BV1cHMx6YEXj)
- **【面试高频】MCP 与 Skills 有什么区别？连接协议 vs 行为规范，附协同关系与省 token 原理**
  - [B station](https://www.bilibili.com/video/BV14zNH69EYY)
- **【Agent 设计模式】Reflexion：语言化反思+记忆，不改参数从失败中迭代改进**
  - [B station](https://www.bilibili.com/video/BV1SMKs6vEwe)
- **【强化学习第一课】MDP 与贝尔曼方程：五要素、回报、价值函数、价值迭代**
  - [B station](https://www.bilibili.com/video/BV1SqKT6QERp)
- **【Agent 范式】Plan-and-Execute vs ReAct：先规划再执行，长任务为什么要先拆**
  - [B station](https://www.bilibili.com/video/BV1NqKW6oEEQ)
- **【LLM Agent】LATS：把蒙特卡洛树搜索搬进 Agent，比 ReAct 强 20-30%**
  - [B station](https://www.bilibili.com/video/BV1wk3R6pEKs)
- **【LLM 工具使用】Toolformer 讲透：让模型自监督学会"何时调工具"，零人工标注**
  - [B station](https://www.bilibili.com/video/BV1e63Z6nECL)
- **【Agent 工程化】约四成 Agent 项目失败：五道鸿沟与系统工程化四板斧**
  - [B station](https://www.bilibili.com/video/BV1NS826nEDS)
- **【Agent 前沿】Agent-Omit：通过省略思考与观察改进多轮 Agent 的上下文膨胀问题**
  - [B station](https://www.bilibili.com/video/BV1JMeY61EcG)
- **【Agentic RL】River：通过过滤劣质合成环境改进终端 Agent RL 的奖励质量，不到 30% 的环境增益翻倍**
  - [B station](https://www.bilibili.com/video/BV1rNeY6mE54)
- **【Agent RL】OTC-PO：把工具生产率写进奖励，为什么能让工具调用减 68.3% 而正确率不变**
  - [B station](https://www.bilibili.com/video/BV1bUea6bE1M)
- **【Agent RL】长程工具 Agent 的 RL 配方怎么定？1K 条 4:3:3 数据、按模型大小配奖励、工具故障率压到 5% 以下**
  - [B station](https://www.bilibili.com/video/BV1tQea64E5C)
- **【Agent RL】CompactionRL：通过把写摘要纳入 RL 训练，改进长程 Agent 的上下文压缩问题**
  - [B station](https://www.bilibili.com/video/BV1y5ea6QEnz)
- **【Agent 训练】DART-SD：多轮工具调用是菱形不是链，只在第一个断点之后算 loss，BFCL 多轮 57.38 对 48.81**
  - [B station](https://www.bilibili.com/video/BV115ea6QEuR)
- **【Agent RL】EnvHarness：通过围绕策略弱点改写环境动态，改进 Agent RL 的环境饱和问题（HF 518 赞）**
  - [B station](https://www.bilibili.com/video/BV1Cjea6nEUc)
- **【Agent RL】harness 原生 RL：在模型 API 边界记 token，训练与部署用同一套脚手架**
  - [B station](https://www.bilibili.com/video/BV11jea6nEaK)
- **【Agent RL】多轮交互 RL 为什么学到的是裁判偏好？ARC 按策略分组 τ-airline +12.67，FACA 用户反应奖励 +10.22**
  - [B station](https://www.bilibili.com/video/BV1rxea65EFj)
- **【Agent RL 面试】多轮 Agent RL 里工具返回的 token 为什么要 mask？loss、KL、重要性比三处都要排**
  - [B station](https://www.bilibili.com/video/BV1B8ea6rEc7)
- **【RL 前沿】不用反向传播能训大模型 Agent 吗？进化策略与 GRPO 的方差、显存与 pass@k 对比**
  - [B station](https://www.bilibili.com/video/BV1zbea6GEF9)
- **【大模型训练】同策略蒸馏 On-Policy Distillation：AIME 74.4 反超 RL，算力只要 1/10**
  - [B station](https://www.bilibili.com/video/BV16tTk6zE7N)
- **【面试前沿】OPD 的 reward 设计合理吗？从 log 无界到 PowerOPD 幂变换**
  - [B station](https://www.bilibili.com/video/BV1DtTC6tEy4)
- **【论文精读】蒸馏也会学出假实力？DOPD 揭穿特权错觉｜OPD 系列**
  - [B station](https://www.bilibili.com/video/BV1AHMx6YEwW)
- **【后训练前沿】什么是 On-Policy Distillation？取 SFT 与 RL 之长（reverse KL 详解）**
  - [B station](https://www.bilibili.com/video/BV1BnMh6BEMz)
- **【模型压缩经典】知识蒸馏 KD：软标签、暗知识、温度、KL+CE 双损失**
  - [B station](https://www.bilibili.com/video/BV1VcKs63Eo5)
- **【蒸馏细节】温度系数讲人话：T 在软化什么、为什么蒸馏 loss 要乘 T² 补偿**
  - [B station](https://www.bilibili.com/video/BV1dXKW61EpT)
- **【反直觉】集成、蒸馏、自蒸馏三个秘密：多视角假设，为什么自蒸馏也能涨点**
  - [B station](https://www.bilibili.com/video/BV1UgKs6PE4p)
- **【Alignment Tax】RLHF 让模型变乖，也让它变笨 — PPO-ptx 解法详解**
  - [B station](https://www.bilibili.com/video/BV1cH3d6dETE)
- **【大模型对齐】1952 年的公式撑起 ChatGPT：Bradley-Terry 模型讲透**
  - [B station](https://www.bilibili.com/video/BV1iS3R6mEdV)
- **【LLaMA 3 对齐】Iterative DPO：让模型自我改进，PPO 效果的 1/10 成本**
  - [B station](https://www.bilibili.com/video/BV1JC3R6QE5N)
- **【LLaMA 3 的选择】Online RLHF vs Offline RLHF：在线交互与静态数据的取舍**
  - [B station](https://www.bilibili.com/video/BV1Gc3d6gEDo)
- **【RLHF】RM 损失函数为什么用 sigmoid 差值?Pairwise Ranking 讲透**
  - [B station](https://www.bilibili.com/video/BV1UN3d6iErs)
- **【LLM 对齐】RLHF 三阶段：SFT → RM → PPO 是怎么串起来的？**
  - [B station](https://www.bilibili.com/video/BV1Qf3R66E8c)
- **【RLHF】Reward Model Calibration：RM 分数到底能不能信？0.2 差距的真实含义**
  - [B station](https://www.bilibili.com/video/BV1GZ3R6GEmJ)
- **【面试高频】一次讲透宪法AI与RLAIF：大模型如何用AI反馈替代人类标注**
  - [B station](https://www.bilibili.com/video/BV1iLuY6CESB)
- **【面试高频】DPO 变体全家桶：SimPO/KTO/ORPO/IPO 各改了什么、怎么选？**
  - [B station](https://www.bilibili.com/video/BV1zKuY6SEhi)
- **【面试高频】生成式奖励模型GRM全解：会思考的考官，让奖励不再黑箱**
  - [B station](https://www.bilibili.com/video/BV1zKuY6SEqJ)
- **【面试高频】不用成对偏好数据怎么做对齐？KTO 把前景理论塞进训练目标，损失厌恶一战封神**
  - [B station](https://www.bilibili.com/video/BV1zMuY6EEZD)
- **【面试高频】SimPO vs DPO：扔掉参考模型，显存省一半还更强？**
  - [B station](https://www.bilibili.com/video/BV196ua6qELh)
- **【对齐踩坑】DPO 的 loss 一直降，模型为什么反而变差？隐式奖励的作弊通道**
  - [B station](https://www.bilibili.com/video/BV1AX826EEgv)
- **【DPO 实操】偏好数据怎么构造？三种生产方式、四个质量陷阱与完整流程**
  - [B station](https://www.bilibili.com/video/BV1PD826SEAJ)
- **【RLHF 基础】奖励模型是怎么训练出来的？用排序代替打分的成对比较损失**
  - [B station](https://www.bilibili.com/video/BV17T8S62EnA)
- **【DPO 原理】reference model 为什么不能丢？KL 约束的数学体现**
  - [B station](https://www.bilibili.com/video/BV1uN8t6zEwx)
- **【蒸馏实操】推理能力蒸馏三法：CoT 数据、on-policy 与 SFT + RLVR**
  - [B station](https://www.bilibili.com/video/BV1cob76FERQ)
- **【DPO 调参】beta 参数详解：物理意义、两侧失效表现与经验值**
  - [B station](https://www.bilibili.com/video/BV1dxb76JEVc)
- **【OPD 系列 05】Distilled RL：通过让老师重分配学生梯度，改进 OPD 的师生差距两难**
  - [B station](https://www.bilibili.com/video/BV1CweY6SENu)
- **【OPD 系列】MOPD：用多教师在线蒸馏改进多域 RL 能力融合的跷跷板问题，Open-MOPD 从 35.6% 修到 83.4%**
  - [B station](https://www.bilibili.com/video/BV1hyea6wELy)
- **【OPD 系列】在线蒸馏需要多少数据？为什么 8 道难题就能追平 1.7 万条，驱动收益的是思维链长度**
  - [B station](https://www.bilibili.com/video/BV1yZea6pEVy)
- **【在线蒸馏】OPSA：通过压低学生自身低概率 token 改进 OPD 的老师噪声问题，不要老师 AIME24 +35**
  - [B station](https://www.bilibili.com/video/BV1rWea61EUz)
- **【对齐面试】Likelihood Displacement：为什么 DPO 越训 chosen 的概率越低？安全 DPO 拒答率反降 55%**
  - [B station](https://www.bilibili.com/video/BV1ivea6MEGr)
- **【面试高频】权重初始化 0.02 的由来：Xavier/He、残差流与小初始化，为什么不是随便设的**
  - [B station](https://www.bilibili.com/video/BV17BNa6NEDc)
- **【面试高频】学习率 Warmup 为什么重要：损失面陡峭 + Adam 二阶矩不准，不加会怎样**
  - [B station](https://www.bilibili.com/video/BV1F5Kj68Ecy)
- **【面试高频】学习率 Warmup 为什么重要：损失面陡峭 + Adam 二阶矩不准，不加会怎样**
  - [B station](https://www.bilibili.com/video/BV1qcKM6KEDe)
- **【面试进阶】Muon 优化器凭什么取代 AdamW？只存动量、显存减半，还收敛更快**
  - [B station](https://www.bilibili.com/video/BV1LLKx6SEkQ)
- **【大模型优化器】Adam 统治 10 年，三个新挑战者正在分庭抗礼——Lion/Sophia/Adafactor 讲透**
  - [B station](https://www.bilibili.com/video/BV1F13R6nEAV)
- **【面试进阶】μTransfer原理详解：小模型调超参如何零样本迁移到大模型**
  - [B station](https://www.bilibili.com/video/BV1ftua61Ezc)
- **【面试高频】WSD 学习率调度凭什么能随时停？三段式拆解+省算力套路**
  - [B station](https://www.bilibili.com/video/BV1P5ua6xErX)
- **【训练技巧】梯度累积 vs 真大 batch：三个不等价的地方与实操建议**
  - [B station](https://www.bilibili.com/video/BV1w9826mEYd)
- **【训练必修】大模型学习率怎么选？LR Range Test、warmup 与 cosine decay 实操**
  - [B station](https://www.bilibili.com/video/BV13i826FEjB)
- **【优化器】Spike-Aware Adam：loss 尖峰之后动量 buffer 的残留问题**
  - [B station](https://www.bilibili.com/video/BV15Z846VE3Y)
- **【训练调参】Batch size 怎么选？Critical Batch Size 与线性缩放规则详解**
  - [B station](https://www.bilibili.com/video/BV1TM8t6iEFL)
- **【训练技巧】学习率衰减策略对比：cosine、linear 与 WSD 的适用场景**
  - [B station](https://www.bilibili.com/video/BV1uP8t6uEud)
- **【科学调参】梯度噪声尺度：用一百步小实验算出最优 batch size**
  - [B station](https://www.bilibili.com/video/BV1bfb56cENP)
- **【调参工具】LR Finder 详解：怎么画、怎么读、怎么和 warmup 配合**
  - [B station](https://www.bilibili.com/video/BV1fLbL6EEFL)
- **【多任务训练】loss 权重平衡三法：手动调权、不确定性加权与 GradNorm**
  - [B station](https://www.bilibili.com/video/BV1cgbL6XEYc)
- **【调参细节】warmup 步数详解：比例怎么定、做错了会怎样、怎么监控**
  - [B station](https://www.bilibili.com/video/BV1qcbE6xEoL)
- **【优化器】Weight Decay 详解：系数怎么选、为什么 AdamW 的解耦这么关键**
  - [B station](https://www.bilibili.com/video/BV1ebb76EEYc)
- **【训练细节】初始化标准差 0.02 的由来：从方差不变推导到实践修正**
  - [B station](https://www.bilibili.com/video/BV1dbb767EV5)
- **【优化器面试】大模型 Adam 的 β₂ 为什么是 0.95 而不是 0.999？记忆 20 步 vs 1000 步**
  - [B station](https://www.bilibili.com/video/BV1Zaea6gE8C)
- **【面试高频】大模型的 badcase 如何解决？从便宜到贵的解决顺序**
  - [B station](https://www.bilibili.com/video/BV1YsKx6CEJq)
- **【面试高频】模型合并 TIES 与 DARE 原理全拆解：任务向量加减法如何缝合大模型**
  - [B station](https://www.bilibili.com/video/BV1Z8ua65E9h)
- **【DeepSeek R1】R1 是怎么训练出来的？四阶段配方：RL 涌现、冷启动、拒绝采样、蒸馏**
  - [B station](https://www.bilibili.com/video/BV1RL8S6gECS)
- **【全景图】大模型训练 pipeline 设计：PT、SFT、偏好对齐与 PAFT 并行范式**
  - [B station](https://www.bilibili.com/video/BV1zwbE6REjt)
- **【零成本提升】Model Soup 详解：权重平均为什么有效、三种炖法怎么选**
  - [B station](https://www.bilibili.com/video/BV1Qvb76VEQi)
- **【后训练工程】BCIT：通过绑定来源上下文与小预算试跑，改进后训练配方跨基座复用的有害迁移问题**
  - [B station](https://www.bilibili.com/video/BV1ijeY6gELo)
- **【企业后训练】线上流量怎么变成后训练？T-Tech 三个 GRPO 专家各撞一种作弊与两段 SLERP 合并，32B 超过 235B**
  - [B station](https://www.bilibili.com/video/BV1eBea6KEWE)
- **【后训练】Self-Routing：通过按对错与置信度把样本分到四条路，改进后训练用单一算法的浪费**
  - [B station](https://www.bilibili.com/video/BV14Xea6dE8q)
- **【后训练方法论】训练的中间阶段该怎么评估？RL 前分最低的 Mixed SFT，RL 后打败 next-chunk RL**
  - [B station](https://www.bilibili.com/video/BV1iYea6zEvS)
- **【数据工程刚需】预训练数据清洗全流程：抽正文、质量过滤、去重、数据配比**
  - [B station](https://www.bilibili.com/video/BV1QNK46LEea)
- **【数据工程硬核】数据去重 MinHash / SimHash：Jaccard、LSH 分桶、汉明距离**
  - [B station](https://www.bilibili.com/video/BV1EdKx6pEuH)
- **【数据为王】FineWeb：15T token 数据集怎么筛出来的，消融驱动、FineWeb-Edu**
  - [B station](https://www.bilibili.com/video/BV127K46TEyc)
- **【RLHF】Anthropic HH 数据集：Helpful 和 Harmless 是怎么标注的？**
  - [B station](https://www.bilibili.com/video/BV1oQ3R6LEgz)
- **【数据工程】Phi-2：Textbooks Are All You Need——2.7B 打赢 70B，质量胜过规模**
  - [B station](https://www.bilibili.com/video/BV1SP3d6TE81)
- **【训练技巧】课程学习工程实现：难度评估、课程设计与 pacing 控制**
  - [B station](https://www.bilibili.com/video/BV1uw8t66Eo2)
- **【数据工程】文本数据增强三法：回译、改写与 GPT-4 生成的适用场景**
  - [B station](https://www.bilibili.com/video/BV1MT8t6TEwW)
- **【IFT 数据】Self-Instruct 与 Evol-Instruct：指令微调数据的构造与三层过滤**
  - [B station](https://www.bilibili.com/video/BV1fVbL6SECM)
- **【数据工程】合成数据完整 pipeline：Self-Instruct、Evol-Instruct 与四步质量控制**
  - [B station](https://www.bilibili.com/video/BV1qNbE6XEU2)
- **【数据工程】标注质量控制：流程、Cohen Kappa 一致性检验与五个质控手段**
  - [B station](https://www.bilibili.com/video/BV1L4b76SEAd)
- **【数据配比】代码与数学数据加多少？20%~40% 最优区间与梯度实验结论**
  - [B station](https://www.bilibili.com/video/BV198b762Euk)
- **【数据工程】数据去重实操：MinHash、LSH 分桶与亿级数据并行处理**
  - [B station](https://www.bilibili.com/video/BV1Zpb76HEeu)
- **【数据工程】数据不均衡详解：五步诊断、三种解法与主流模型配比**
  - [B station](https://www.bilibili.com/video/BV1onb76XEqP)
- **【中文大模型】中英数据配比：1T 纯中文 vs 2T 混合的实验结论与跨语言迁移**
  - [B station](https://www.bilibili.com/video/BV1QYb76yEBu)
- **【数据质量】SFT 数据自动筛选：GPT-4 打分、PPL 检测与 embedding 聚类**
  - [B station](https://www.bilibili.com/video/BV1xPb76vEzd)
- **【数据工程】预训练数据配比：主流模型参考、DoReMi 与消融实验**
  - [B station](https://www.bilibili.com/video/BV1TKb76PEcu)
- **【RL 数据配比】数学、代码、表格混训 RL，哪些域能跨域迁移、哪些必须专训？Guru 六域实验与 CARE-RL、TAC**
  - [B station](https://www.bilibili.com/video/BV1yVea6pE2L)
- **QwenVL到Qwen3.5技术改进**
  - [B station](https://www.bilibili.com/video/BV1GpXaBGEoE)
- **【文生图地基】DDPM 扩散模型原理：前向加噪、反向去噪，为什么 loss 化简成预测噪声**
  - [B station](https://www.bilibili.com/video/BV1qyNo6TEN1)
- **【扩散加速】DDIM 采样原理：非马尔可夫、确定性采样，50 步媲美 1000 步不用重训**
  - [B station](https://www.bilibili.com/video/BV1ikNo6BEkC)
- **【扩散进阶】Score/SDE 统一视角：分数场、Langevin 采样，DDPM 与分数匹配的统一**
  - [B station](https://www.bilibili.com/video/BV1ikNo6BE9h)
- **【文生图必调】Classifier-Free Guidance 原理：一个系数如何权衡真实感与多样性**
  - [B station](https://www.bilibili.com/video/BV1qkNo6BEzF)
- **【多模态第一课】CLIP 原理：图文对比预训练、InfoNCE、zero-shot 分类**
  - [B station](https://www.bilibili.com/video/BV1YGKM6ZEuh)
- **【多模态】BLIP-2 的 Q-Former：可学习 query、cross-attention，桥接冻结视觉与 LLM**
  - [B station](https://www.bilibili.com/video/BV1Y3KM6bEjj)
- **【多模态】LLaVA 视觉对齐：CLIP ViT、Projector 投影层、两阶段训练**
  - [B station](https://www.bilibili.com/video/BV1SzKT6nEPj)
- **【多模态】视觉编码器盘点：Patch、ViT、Projector，各家 VLM 视觉塔对比**
  - [B station](https://www.bilibili.com/video/BV1MzKT6HESr)
- **【语音合成】VITS 端到端 TTS：变分推断、归一化流、对抗训练，一步合成语音**
  - [B station](https://www.bilibili.com/video/BV1QwKs6zEhi)
- **【语音大模型地基】音频 Tokenizer：VQ-VAE、RVQ 残差量化，语音怎么离散化成 token**
  - [B station](https://www.bilibili.com/video/BV1jdKW6yEgH)
- **【文生图全流程】Stable Diffusion 原理：潜空间扩散、CLIP、U-Net、cross-attention**
  - [B station](https://www.bilibili.com/video/BV123Ks6YEfb)
- **【Sora 同款骨干】DiT 原理：patchify、adaLN-Zero，Transformer 取代 U-Net**
  - [B station](https://www.bilibili.com/video/BV1uTKs6TE4B)
- **【文生图最新范式】Flow Matching / Rectified Flow：向量场、拉直路径，SD3/FLUX 同款**
  - [B station](https://www.bilibili.com/video/BV1mYKW68Esk)
- **【语音大模型入门】Whisper 原理：弱监督 68 万小时、encoder-decoder、特殊 token 多任务**
  - [B station](https://www.bilibili.com/video/BV1qYKs6EEBj)
- **【生成基石】VAE 变分自编码器：ELBO 推导、重参数化、KL 正则的作用**
  - [B station](https://www.bilibili.com/video/BV1U5K46uEJN)
- **【扩散进阶】扩散的数学=分层 VAE：x₀/噪声/分数 三种预测目标为什么等价**
  - [B station](https://www.bilibili.com/video/BV1nPKW6JEJy)
- **【面试高频】多模态早融合 vs 后融合：Chameleon 凭什么把图文从头一起训**
  - [B station](https://www.bilibili.com/video/BV1iLuY6CEX1)
- **【面试高频】NaViT 原生任意分辨率 + Patch n' Pack：视觉大模型为什么不再把图片压成方块？**
  - [B station](https://www.bilibili.com/video/BV1oYua6GERd)
- **【面试高频】多模态大模型又慢又贵？视觉Token压缩 ToMe / FastV 两招讲透**
  - [B station](https://www.bilibili.com/video/BV1Kuua6fEf3)
- **【AIGC 加速】一致性模型为什么能一步出图？从去噪轨迹讲到 LCM-LoRA**
  - [B station](https://www.bilibili.com/video/BV1mC826sEre)
- **【前沿架构】扩散语言模型为什么能一次并行吐出一整句？离散扩散原理详解**
  - [B station](https://www.bilibili.com/video/BV1fF8m6kEiA)
- **【多模态】Google 用 sigmoid 替代 softmax——SigLIP vs CLIP 讲透**
  - [B station](https://www.bilibili.com/video/BV1GZ846VETv)
- **【多模态基石】ViT 视觉 Transformer：把图像切成 patch，Transformer 也能做视觉**
  - [B station](https://www.bilibili.com/video/BV1VR846LEY6)
  - links: https://arxiv.org/abs/2010.11929
- **【多模态面试】VLM 微调要不要解冻视觉编码器？只训 ViT 感知涨分、MMMU 可能下降，按任务来定**
  - [B station](https://www.bilibili.com/video/BV1CJea6EEXs)
- **【大模型训练】GLM-5.2 为什么放弃 GRPO 换回 critic-based PPO？三个隐性假设崩塌全解析**
  - [B station](https://www.bilibili.com/video/BV1qSTr6vEys)
- **【大模型训练】从概率模型看 SFT 和 RL 的区别：正向 KL vs 反向 KL 完整推导**
  - [B station](https://www.bilibili.com/video/BV1rKTn65E9V)
- **【面试必考】GRPO、DAPO、GSPO三代强化学习算法，到底改了什么？从PPO讲起**
  - [B station](https://www.bilibili.com/video/BV1oRMP6hE7f)
- **【面试高频】RLHF 优化算法进化史：PPO / DPO / GRPO / DAPO / GSPO 一次串清楚**
  - [B station](https://www.bilibili.com/video/BV1qnMh6BEoZ)
- **【面试必考】PPO 到底在裁剪什么？从策略梯度的坑到那条安全带｜强化学习零基础**
  - [B station](https://www.bilibili.com/video/BV1qnMh6BEx1)
- **【面试高频】KL 散度计算的三种近似方法？K1/K2/K3 一次讲透**
  - [B station](https://www.bilibili.com/video/BV11jMt6yED7)
- **【RLHF 面试高频】GRPO 比 PPO 做了什么改进？一刀砍掉 Critic 省显存**
  - [B station](https://www.bilibili.com/video/BV1iJMh6uERR)
- **【强化学习面试高频】GRPO 的损失为什么开始时是 0？两部分同时归零**
  - [B station](https://www.bilibili.com/video/BV1imM36EEqD)
- **【面试进阶】GRPO 用旧策略数据，为什么还叫 on-policy？一个打篮球的例子讲透**
  - [B station](https://www.bilibili.com/video/BV1fJNA69EFy)
- **【面试进阶】什么是重要性采样？为什么 token 级的损失难以收敛？「猫喜欢鱼」讲透**
  - [B station](https://www.bilibili.com/video/BV1HENA6xEpB)
- **【强化学习】策略梯度定理：log-derivative 技巧、REINFORCE，怎么对随机采样求梯度**
  - [B station](https://www.bilibili.com/video/BV1LVKW6VEEy)
- **【面试陷阱】GRPO 里被 clip 的 token 反向有没有梯度？用 torch.clamp 一跑就懂**
  - [B station](https://www.bilibili.com/video/BV1HmKx6ZEyX)
- **【面试高频】ReMax：PPO 的轻量替代，砍 Critic 用 greedy 解码当 baseline**
  - [B station](https://www.bilibili.com/video/BV1gYgR6vEt4)
- **【RLOO 讲透】REINFORCE Leave-One-Out：不要 Critic、不要 greedy 假想敌，同组 response 互卷就够了**
  - [B station](https://www.bilibili.com/video/BV13agR6KEDw)
- **【PPO 工程】π_θ/π_θ_old 是怎么算的？token-level log prob 的 3 个工程坑**
  - [B station](https://www.bilibili.com/video/BV1Dw3d6BEYP)
- **【PPO 工程精华】importance sampling ratio + clip：同一 batch 训 4 epoch 的秘密**
  - [B station](https://www.bilibili.com/video/BV1DP3d6TED7)
- **【RLHF】Reference Model 是干嘛的？为什么 PPO 离不开这个"躺平"的模型**
  - [B station](https://www.bilibili.com/video/BV1Xd3R6kEdU)
- **【概率视角】SFT 和 RLHF 竟是同一枚硬币的两面：正向 KL vs 反向 KL**
  - [B station](https://www.bilibili.com/video/BV1er3Z6SEcf)
- **【RLHF 理论基础】Token-level MDP：LLM 的 state 和 action 到底是什么？**
  - [B station](https://www.bilibili.com/video/BV1R63Z6nEeD)
- **【2025 RL 前沿】ASPO：通过重要性比率翻转改进 GRPO 的熵崩塌问题**
  - [B station](https://www.bilibili.com/video/BV1WS826nEh5)
- **【RL 进阶】DAPO 动态采样：通过过滤全对全错组改进 GRPO 的零梯度浪费**
  - [B station](https://www.bilibili.com/video/BV1rf8265Eg4)
- **【RL 进阶】DAPO：通过 token 级归一化改进 GRPO 长答案被稀释的问题**
  - [B station](https://www.bilibili.com/video/BV1Ff8265E3j)
- **【RL 进阶】GSPO：通过序列级重要性比率改进 PPO/GRPO 的逐 token 方差问题**
  - [B station](https://www.bilibili.com/video/BV1Bn826gEWs)
- **【RLHF 基础】PPO 的 clip 为什么只在一半情况下才生效？不对称四象限详解**
  - [B station](https://www.bilibili.com/video/BV1RG8S6GEhk)
- **【RLHF 基础】PPO 的奖励为什么只在最后一个 token 才发？逐 token 算账拆解**
  - [B station](https://www.bilibili.com/video/BV1RG8S6GEoq)
- **【RLHF 基础】PPO 为什么需要四个模型？演员、评论家、奖励、参考各自的作用**
  - [B station](https://www.bilibili.com/video/BV1og8S6CE26)
- **【RLHF 深入】critic value function 详解：为什么难训准、GAE 怎么补、GRPO 怎么砍**
  - [B station](https://www.bilibili.com/video/BV1uP8t6uE9J)
- **【RL 原理】credit assignment 与 GRPO 的 advantage 分配机制**
  - [B station](https://www.bilibili.com/video/BV1PTb76YEVw)
- **【RL 前沿】SIGNBALANCE：通过保号与全局尺度改进 GRPO 给蒙对答案发高奖励的问题，附 DA3PO 难题错误放大**
  - [B station](https://www.bilibili.com/video/BV1nNeY6mEGC)
- **【RL 面试新题】k3 估计器是无偏的，为什么 KL 项的梯度却是有偏的？放奖励与放 loss 的区别**
  - [B station](https://www.bilibili.com/video/BV1GxeY6PEVi)
- **【RL 前沿】μ-GRPO：放宽 clip 加负优势否决，GRPO 用 250 倍陈旧的数据为什么不崩**
  - [B station](https://www.bilibili.com/video/BV1aWeY6vEpH)
- **【GRPO 进阶】OraRL：通过解耦策略基线与标准答案增益，改进 GRPO 塞入标准答案时的优势反转问题**
  - [B station](https://www.bilibili.com/video/BV1hyea6wEyV)
- **【RL 前沿】VAPO：通过 value 预训练与解耦 GAE 改进长思维链上 critic 训不准的问题（字节 Seed）**
  - [B station](https://www.bilibili.com/video/BV1rnea6mE4y)
- **【面试高频】大模型能过律考却算不对六位数乘法：分词错位+进位是未来信息+概率≠确定+调工具**
  - [B station](https://www.bilibili.com/video/BV1azNU6BEpK)
- **【面试高频】In-Context Learning 机理：贝叶斯任务定位，为什么乱标签也能 work**
  - [B station](https://www.bilibili.com/video/BV1F5Kj68EPG)
- **【面试高频】涌现能力之争：是真的突现，还是度量假象？精确匹配 vs 平滑指标**
  - [B station](https://www.bilibili.com/video/BV1B5Kj6bEGF)
- **【可解释性】激活导向详解：不改一个权重，用一个方向向量控制模型性格**
  - [B station](https://www.bilibili.com/video/BV1ty8269ExR)
- **【范式反思】自回归的三个根本局限：滚雪球错误、无法全局规划、曝光偏差**
  - [B station](https://www.bilibili.com/video/BV1g68264E7h)
- **【反直觉现象】Grokking 延迟泛化：模型"背完答案"后突然"开窍"，挑战早停智慧**
  - [B station](https://www.bilibili.com/video/BV1Jn826gEKr)
- **【认知盲区】大模型为什么算不对多位数乘法？三重根因与逆序输入解法**
  - [B station](https://www.bilibili.com/video/BV1rE826rEF6)
- **【AI 安全】大模型水印是怎么做的？绿名单方案详解：γ 切名单、δ 加分数、z 做检验**
  - [B station](https://www.bilibili.com/video/BV1J7826GEU2)
- **【可解释性】Logit Lens 详解：把每一层的残差解码成词，看答案如何逐层结晶**
  - [B station](https://www.bilibili.com/video/BV1Ye826hEBW)
- **【AI 安全】机器遗忘详解：梯度上升、RMU、NPO 三种让大模型选择性失忆的方法**
  - [B station](https://www.bilibili.com/video/BV15t826vEUA)
- **【可解释性】SAE 稀疏自编码器详解：用 L1 约束把多义神经元拆成单义特征**
  - [B station](https://www.bilibili.com/video/BV1ux8S6eEc4)
- **【认知盲区】大模型数不清 strawberry 的 r、算不对乘法，根因都在 tokenizer**
  - [B station](https://www.bilibili.com/video/BV1hc8t63EKR)
- **【训练诊断】用 Logit Lens 看训练到底改善了什么：中间层表示 vs 输出映射**
  - [B station](https://www.bilibili.com/video/BV1cGbL6HEzH)
- **【AI 安全】红队测试实操：四种攻击手法、安全分类器与 RLHF 安全对齐**
  - [B station](https://www.bilibili.com/video/BV1CDb76AEB8)
- **【RL 面试】RL 微调的幻觉税：为什么 RFT 之后模型对无解题不再拒答？混 10% 无解题 SUM 就能修回来**
  - [B station](https://www.bilibili.com/video/BV1xXea6dECx)
- **【面试高频】如何理解 MoE 网络？Router 怎么实现？**
  - [B station](https://www.bilibili.com/video/BV15XMp6yEzV)
- **【面试高频】MoE 架构相比 Dense 有什么好处？一个最小例子把计算量算清楚**
  - [B station](https://www.bilibili.com/video/BV1TTMW6NEqk)
- **【手撕代码】MoE 设备受限路由怎么写？一招锁死跨卡通信（华为面试真题 / DeepSeek-V2）**
  - [B station](https://www.bilibili.com/video/BV1AkKx6wEXL)
- **【面试进阶】如何计算 sequence 粒度的负载均衡损失？MoE 专家忙闲不均怎么纠偏**
  - [B station](https://www.bilibili.com/video/BV157gD6FE3J)
- **【MoE 架构】DeepseekMoE 细粒度 + 共享专家：凭什么比标准 MoE 强 10-15%？**
  - [B station](https://www.bilibili.com/video/BV1oS3R62ESL)
- **【面试高频】DeepSeek 删掉辅助损失，MoE 反而更均衡？无辅助损失负载均衡一次讲透**
  - [B station](https://www.bilibili.com/video/BV11dua64ECo)
- **【面试高频】Mixture-of-Depths：让 token 学会跳层，Transformer 算力省一半还不掉点**
  - [B station](https://www.bilibili.com/video/BV19qua6zExA)
- **【Kimi K3】Stable LatentMoE：用三件套改进万亿 MoE 的训练崩溃**
  - [B station](https://www.bilibili.com/video/BV1kL826CETq)
- **【架构】Mixture of Depths 详解：深度方向的稀疏，与 MoE 有何不同**
  - [B station](https://www.bilibili.com/video/BV1WTbL6REiT)
- **【MoE 训练】专家忙闲不均怎么治？aux loss 调参与 DeepSeek-V3 动态偏置**
  - [B station](https://www.bilibili.com/video/BV1kKbL6xEm1)
- **【MoE 训练】从零训练完整流程：专家初始化、router 设置与训练 schedule**
  - [B station](https://www.bilibili.com/video/BV1Qvb76VE4D)
- **【面试前沿】大模型深度思考的自主切换是怎么实现的？不确定性 / 决策器 / 多阶段 RL**
  - [B station](https://www.bilibili.com/video/BV1bGMt67E7J)
- **【面试高频】Zero/One/Few-shot 与 In-Context Learning：GPT-3 为什么是 few-shot learner**
  - [B station](https://www.bilibili.com/video/BV1FVKj6cEz6)
- **【面试高频】思维草稿Chain-of-Draft：一句提示词让大模型少写80%token，正确率几乎不掉**
  - [B station](https://www.bilibili.com/video/BV1q3uY6jEYg)
- **【面试高频】思维图GoT讲透：链→树→图演进+聚合/回环+三大思维变换，质量涨六成还更省钱**
  - [B station](https://www.bilibili.com/video/BV1nNuY6HEF4)
- **【面试高频】推理模型的显式思考真的必要吗？NoThinking 跳过思考反而更省更快**
  - [B station](https://www.bilibili.com/video/BV1dYua6GEBn)
- **【面试高频】推理模型越想越歪？ParaThinker并行思考，打破长思维链的隧道视野**
  - [B station](https://www.bilibili.com/video/BV1dhua6CEmV)
- **【面试高频】Quiet-STaR 原理拆解：每个 token 前先默想，推理能力自己长出来**
  - [B station](https://www.bilibili.com/video/BV1U2ua6YEr4)
- **【面试高频】一张图讲透推理型大模型：推理时计算/PRM/搜索/自我进化 四根支柱**
  - [B station](https://www.bilibili.com/video/BV1mQua6FEf9)
- **【面试高频】7B小模型自进化超o1？rStar-Math三件套(代码CoT+MCTS+过程偏好模型)一次讲透**
  - [B station](https://www.bilibili.com/video/BV1tSua6aEHu)
- **【面试高频】大模型自我精炼Self-Refine：同一个模型自己批评自己，零训练提升输出质量**
  - [B station](https://www.bilibili.com/video/BV1Gkua6TEHE)
- **【面试高频】测试时算力 Test-Time Compute：为什么 o1 多想一会儿就变强？四招讲透**
  - [B station](https://www.bilibili.com/video/BV1QCua6vEv2)
- **【面试高频】思维链一条道走到黑？思维树ToT让大模型学会回溯，正确率从4%飙到74%**
  - [B station](https://www.bilibili.com/video/BV1T3ua6tEjt)
- **【推理增强】自洽性采样详解：为什么多想几遍取多数票能涨点**
  - [B station](https://www.bilibili.com/video/BV1gs8S6NEtr)
- **【推理增强】Best-of-N 采样详解：四种挑选方法与 RFT 的衔接**
  - [B station](https://www.bilibili.com/video/BV1Qab76LEvu)
- **大模型面试：为什么现在的大模型都是Decoder-Only架构？**
  - [B station](https://www.bilibili.com/video/BV1uiXmBUEfp)
- **【面试必考】LayerNorm为什么被RMSNorm全面取代？从0讲透归一化+手撕LLaMA同款代码**
  - [B station](https://www.bilibili.com/video/BV1owTx6pEqM)
- **【面试高频】请介绍 BERT 的流程：五大部件 + 预训练全讲透**
  - [B station](https://www.bilibili.com/video/BV1SGMt67EEq)
- **【面试高频】Qwen 从 1 到 3 每个版本改了什么？一条线讲透六代改进点**
  - [B station](https://www.bilibili.com/video/BV1KjMt6yE6h)
- **【面试高频】BERT 与 LSTM 有什么不同？结构 / 并行 / 双向 / 预训练四维度对比**
  - [B station](https://www.bilibili.com/video/BV1KMMW6eEnp)
- **【面试高频】Encoder-Only 和 Decoder-Only 建模有何区别？BERT 与 GPT 的分水岭**
  - [B station](https://www.bilibili.com/video/BV1HLNA6tEX9)
- **【面试高频】Engram 以存储换算力：确定性哈希查表的先天记忆，O(1) 取语义，NIAH 84→97**
  - [B station](https://www.bilibili.com/video/BV17MNS6UEhc)
- **【面试高频】Kimi AttnRes：把残差升级成对历史层的注意力，伪查询+块级检索，N≈8 延迟<2%**
  - [B station](https://www.bilibili.com/video/BV1LVNS6LEHX)
- **【面试高频】SwiGLU 激活函数：GLU 门控 × Swish，为何取代 ReLU/GELU 成大模型 FFN 标配**
  - [B station](https://www.bilibili.com/video/BV1i3NS62E68)
- **【面试高频】weight tying 详解：输入输出 Embedding 为什么共享？转置关系 / 省参数 / GPT-2 与 LLaMA 的取舍**
  - [B station](https://www.bilibili.com/video/BV151Na68EcR)
- **【面试高频】BPE 分词详解：中文为什么比英文更费 Token？子词 / 字节级 / WordPiece / Unigram 全讲透**
  - [B station](https://www.bilibili.com/video/BV1uUN86SEHs)
- **【面试高频】Word2Vec 词向量详解：CBOW / Skip-gram / 负采样，为什么它是 Embedding 的祖师爷**
  - [B station](https://www.bilibili.com/video/BV1hmN86nEVC)
- **【面试高频】Transformer FFN 详解：为什么先升维 4 倍再降回？升维 / 降维 / 残差 / SwiGLU 2.67 倍全讲透**
  - [B station](https://www.bilibili.com/video/BV14LN86GEG1)
- **【面试高频】7B 参数量怎么手算？12Ld²+Vd 公式详解，词嵌入 / 注意力 / FFN 逐块拆解**
  - [B station](https://www.bilibili.com/video/BV1jiNa6iECe)
- **【面试高频】残差连接为什么重要：退化问题、梯度高速路，与 Transformer 的残差流**
  - [B station](https://www.bilibili.com/video/BV1SXNa6RE4J)
- **【面试高频】RNN vs CNN vs Transformer：并行能力与长程依赖两把尺子讲透**
  - [B station](https://www.bilibili.com/video/BV1q7Kj64EcD)
- **【面试高频】Embedding 到底是什么、为什么乘 √d_model：查找表、位置编码与数值量级**
  - [B station](https://www.bilibili.com/video/BV1qyNo6TESa)
- **【面试高频】7B 参数量怎么手算？12Ld²+Vd 公式详解，词嵌入 / 注意力 / FFN 逐块拆解**
  - [B station](https://www.bilibili.com/video/BV1BwKM6vEGs)
- **【面试高频】weight tying 详解：输入输出 Embedding 为什么共享？转置关系 / 省参数 / GPT-2 与 LLaMA 的取舍**
  - [B station](https://www.bilibili.com/video/BV1BZKT6MEmC)
- **【面试高频】BatchNorm 与 LayerNorm 的区别：为什么 Transformer 只用 LayerNorm？**
  - [B station](https://www.bilibili.com/video/BV1j7gD6cE75)
- **【大模型架构】RetNet 讲透：微软的 Transformer 杀手，训练并行 + 推理 O(1)**
  - [B station](https://www.bilibili.com/video/BV1RR3R6VEn7)
- **【面试高频】扔掉分词器！Byte Latent Transformer 用字节熵动态切 patch 全解析**
  - [B station](https://www.bilibili.com/video/BV1oGuY61EFH)
- **【面试高频】Mamba+注意力+MoE三合一，Jamba如何把25万字塞进单张显卡？混合架构原理拆解**
  - [B station](https://www.bilibili.com/video/BV1zuuY6mEqQ)
- **【面试高频】Titans：让大模型在推理时学会长期记忆，注意力+神经记忆到底怎么融合？**
  - [B station](https://www.bilibili.com/video/BV1DCua6vEpr)
- **【面试进阶】大模型新结构TTT层：处理一条序列=训练一个小模型，线性复杂度+恒定内存扛长文本**
  - [B station](https://www.bilibili.com/video/BV1Muua6fEpa)
- **【Kimi 新架构】Attention Residuals：用深度方向 softmax 改进残差连接的等权相加问题**
  - [B station](https://www.bilibili.com/video/BV1Nm826QELP)
- **【面试高频】SwiGLU 的中间层维度为什么是 8/3·d？从参数量守恒一步步推导**
  - [B station](https://www.bilibili.com/video/BV1Qc8t63EsP)
- **【架构辩论】Transformer 会被取代吗？三个致命伤，取代派/改良派/共存派三种解法**
  - [B station](https://www.bilibili.com/video/BV1jS846SETu)
- **【训练第一步】tokenizer 词表设计：vocab size、中英混合与 Byte-level BPE**
  - [B station](https://www.bilibili.com/video/BV1BPbE6WELv)
- **【模型压缩】模型剪枝原理：结构化 vs 非结构化、按幅度剪、剪枝+微调**
  - [B station](https://www.bilibili.com/video/BV14eKW6fENJ)
- **【顶会最佳论文】彩票假设：稀疏子网、重置回初始化，为什么小子网能单独达标**
  - [B station](https://www.bilibili.com/video/BV1w6KW6RENb)
- **【LLM 剪枝】SparseGPT / Wanda：一次性剪枝不重训，按权重×激活选，公式讲透**
  - [B station](https://www.bilibili.com/video/BV1qgKW6LEDW)
- **【面试高频】BitNet b1.58 全解：权重只用-1/0/1，乘法变加法，省电71倍还不掉点**
  - [B station](https://www.bilibili.com/video/BV1iGuY61EDX)
- **【面试高频】大模型四位量化为什么总崩？旋转量化一招治激活离群点**
  - [B station](https://www.bilibili.com/video/BV1mQua6FEAN)
- **【量化必修】离群激活详解：为什么清零 99% 的激活模型还活着，动几个大的就崩**
  - [B station](https://www.bilibili.com/video/BV1vt826vEKv)
- **【量化部署】QAT vs PTQ：fake quantization、直通估计器与选型标准**
  - [B station](https://www.bilibili.com/video/BV1pQb76YE6q)
- **大模型KV Cache原理详解**
  - [B station](https://www.bilibili.com/video/BV12fXyBKEor)
- **图解大模型缓存 KV Cache的原理**
  - [B station](https://www.bilibili.com/video/BV1yy5o6zELy)
- **【大模型加速】推测解码 Speculative Decoding 原理详解：从草稿验证到拒绝采样**
  - [B station](https://www.bilibili.com/video/BV1CsTv6tEDU)
- **【大模型推理】内存墙 Memory-Bound 到底是什么？H100 算力利用率不足 1% 的真相**
  - [B station](https://www.bilibili.com/video/BV1euTj6dEqX)
- **【推理优化】PagedAttention：显存浪费 60-80% 怎么救｜vLLM 核心技术**
  - [B station](https://www.bilibili.com/video/BV1AHMx6YEAm)
- **【面试高频】温度·Top-K·Top-P 到底动了什么？解码采样一次讲透**
  - [B station](https://www.bilibili.com/video/BV1cHMx6YE8i)
- **【面试高频】推理过程中的 KV Cache 怎么估算？从原理到 Qwen/DeepSeek 实算**
  - [B station](https://www.bilibili.com/video/BV1KTMW6NE9t)
- **【面试高频】大模型推理占用的显存怎么计算？一个公式秒算**
  - [B station](https://www.bilibili.com/video/BV1VsNH6PECF)
- **【面试高频】现在大模型为什么都用 left padding？一句话讲透**
  - [B station](https://www.bilibili.com/video/BV1CyNH6nEXF)
- **【面试高频】MTP 多 Token 预测：一次预测多个未来字 + 投机解码，步数砍半提速 1.8×**
  - [B station](https://www.bilibili.com/video/BV1EoNg6kERe)
- **【面试高频】解码策略详解：贪心 / Beam Search / 采样怎么选？束宽、Top-K、Top-P 核采样全讲透**
  - [B station](https://www.bilibili.com/video/BV1LyNa6cELQ)
- **【面试高频】解码策略详解：贪心 / Beam Search / 采样怎么选？束宽、Top-K、Top-P 核采样全讲透**
  - [B station](https://www.bilibili.com/video/BV1FdKT66EAS)
- **【推理优化】Chunked Prefill：8000 token prompt 一进，Decode 集体卡 1 秒？**
  - [B station](https://www.bilibili.com/video/BV1jWgR6rEK9)
- **【大模型推理】Continuous Batching：同样 8 张卡，凭啥 vLLM 比 HF 快 24 倍？**
  - [B station](https://www.bilibili.com/video/BV1jpgR6GEM1)
- **【大模型推理】Continuous Batching：同样 8 张卡，凭啥 vLLM 比 HF 快 24 倍？**
  - [B station](https://www.bilibili.com/video/BV1ipgR6GE1K)
- **【LLM 推理】PD 分离部署：Mooncake / DistServe / Splitwise 三家方案讲透**
  - [B station](https://www.bilibili.com/video/BV1J7gR61EgA)
- **【LLM 推理】Prefill vs Decode：一个拼算力一个拼带宽，推理框架的灵魂**
  - [B station](https://www.bilibili.com/video/BV1JjgR6jEgH)
- **【LLM 推理优化】RadixAttention：SGLang 的招牌技术，一棵 Radix Tree 让吞吐提升 2-5×**
  - [B station](https://www.bilibili.com/video/BV1gYgR6vEas)
- **【推理优化】7B 在 H100 上理论极限 TPS 是多少？从 HBM 带宽推公式**
  - [B station](https://www.bilibili.com/video/BV1e4gR6zEfR)
- **【LLM 推理】TTFT vs ITL：推理体验的两个 SLO，优化路径完全不同**
  - [B station](https://www.bilibili.com/video/BV1VxgR6gEmj)
- **【面试高频】KV缓存驱逐：H2O与SnapKV，95%的KV都在陪跑**
  - [B station](https://www.bilibili.com/video/BV1Liua63EZG)
- **【面试进阶】Lookahead Decoding：把大模型解码看成解方程，雅可比并行无损加速**
  - [B station](https://www.bilibili.com/video/BV1Reua6rEkb)
- **【面试高频】美杜莎解码：多解码头+树注意力，一次前向验证一整棵候选树**
  - [B station](https://www.bilibili.com/video/BV1Vzua6uEKE)
- **【面试高频】DeepSeek V3 招牌 MTP 多 token 预测全解：训练当辅助任务、推理当投机解码加速器**
  - [B station](https://www.bilibili.com/video/BV1o8ua65EdB)
- **【面试高频】自投机解码：不加显存，大模型推理怎么白捡两倍加速？**
  - [B station](https://www.bilibili.com/video/BV1V6ua6BEnX)
- **【Agent 必修】约束解码怎么保证模型只吐合法 JSON？FSM/PDA 与 logit 屏蔽详解**
  - [B station](https://www.bilibili.com/video/BV1bC826sEMX)
- **【推理必修】温度、Top-K、Top-P 的区别在哪里？兼谈贪心与束搜索**
  - [B station](https://www.bilibili.com/video/BV1co8261ERi)
- **【推理调参】温度、Top-P、Top-K 该按什么顺序调？为什么不能同时拉满**
  - [B station](https://www.bilibili.com/video/BV1Ew8m6GEeG)
- **【推理优化】KV Cache 为什么只缓存 K 和 V，从不缓存 Q？注意力的根本不对称**
  - [B station](https://www.bilibili.com/video/BV1JL826CEQK)
- **【推理加速】Medusa 多解码头讲透：一次预测 k 个 token，无需草稿模型的内嵌方案**
  - [B station](https://www.bilibili.com/video/BV1j4826KEUb)
- **【推理调参】存在惩罚和频率惩罚的区别在哪里？两个治复读旋钮讲透**
  - [B station](https://www.bilibili.com/video/BV1e8826PEYT)
- **【推理架构】Prefill 与 Decode 为什么差 140 倍？PD 分离架构的由来**
  - [B station](https://www.bilibili.com/video/BV1Xj8S6zEe1)
- **【推理踩坑】训练 right padding、推理 left padding：搞混就是 silent bug**
  - [B station](https://www.bilibili.com/video/BV1cubL6WEQi)
- **【面试必考】RoPE位置编码到底是什么？从0手撕Qwen3源码，代码和公式竟然对不上!?**
  - [B station](https://www.bilibili.com/video/BV1gLTx6CEHx)
- **【手撕代码】Multi-Head Attention 多头注意力怎么写（接上期自注意力）**
  - [B station](https://www.bilibili.com/video/BV1imM36EETx)
- **【面试高频】Softmax 前为什么要除以根号 d？含完整数学推导**
  - [B station](https://www.bilibili.com/video/BV1cJNA6REKc)
- **【面试高频】Encoder 和 Decoder 中的 Mask 有什么不同？两层掩码一次讲透**
  - [B station](https://www.bilibili.com/video/BV1cENA6xEtb)
- **【面试高频】DeepSeek NSA 原生稀疏注意力：压缩+选择+滑窗，长文本解码快 11 倍还反超全注意力**
  - [B station](https://www.bilibili.com/video/BV1YKN36iEBs)
- **【面试高频】YaRN 长度外推：RoPE 高频外推低频内插 + 注意力温度，4k→128k 几乎零成本**
  - [B station](https://www.bilibili.com/video/BV1RNN36TEva)
- **【面试高频】DCA 双块注意力：块内/块间/相邻块 + 位置重映射封顶，零训练扩到百万上下文**
  - [B station](https://www.bilibili.com/video/BV1zdNg6VEsk)
- **【面试高频】DeepSeek DSA 稀疏注意力：闪电索引器选 top-2048，真正省的是访存而非 FLOPs**
  - [B station](https://www.bilibili.com/video/BV1LFN366ER5)
- **【面试高频】门控注意力：SDPA 输出后加 Sigmoid 门，强稀疏+破低秩+去 attention-sink，只多 1% 参数**
  - [B station](https://www.bilibili.com/video/BV1jgNS67EsS)
- **【面试高频】注意力为什么是 O(n²)？n×n 矩阵、显存爆炸与上下文长度的真相**
  - [B station](https://www.bilibili.com/video/BV16VKj6FEA8)
- **【手撕代码】softmax / safe softmax / online softmax：从会溢出到一遍算完（FlashAttention 核心）**
  - [B station](https://www.bilibili.com/video/BV1ETKW67EXG)
- **【RoPE 之后必问】长度外推：训短推长为什么崩，ALiBi/PI/NTK/YaRN 方法全景**
  - [B station](https://www.bilibili.com/video/BV13pKW6TECw)
- **【长文本扩展】位置插值 PI → NTK-aware → YaRN：怎么把 32K 免训练扩到 128K**
  - [B station](https://www.bilibili.com/video/BV1uxKW6NE7B)
- **【面试综述题】高效 Transformer 四大流派：稀疏、低秩、核化、可逆，一张图看懂**
  - [B station](https://www.bilibili.com/video/BV15jKW63E8e)
- **【线性注意力】Linformer & Performer：低秩投影、核化+结合律，O(n²) 降到 O(n)**
  - [B station](https://www.bilibili.com/video/BV1GJKW6uEEH)
- **【稀疏注意力】Longformer & BigBird：滑动窗口、全局、随机注意力，O(n²) 降到 O(n)**
  - [B station](https://www.bilibili.com/video/BV19wK467EJE)
- **【手撕代码】self-attention 自注意力：一个公式讲透 Transformer 的心脏**
  - [B station](https://www.bilibili.com/video/BV1d7gD6FEUe)
- **【面试高频】MQA 和 GQA：把 KV 头砍到 8 组为什么效果不掉？｜注意力演化 MHA→MQA→GQA→MLA**
  - [B station](https://www.bilibili.com/video/BV1tiKx6KE8v)
- **【手撕代码】RoPE 旋转位置编码：为什么点积只看相对距离？一个视频讲透**
  - [B station](https://www.bilibili.com/video/BV1gigR6YEiz)
- **【大模型数值稳定性】Safe Softmax：一行 exp(100) 让模型崩溃，FlashAttention 的数学基石**
  - [B station](https://www.bilibili.com/video/BV1bigR6YEpq)
- **【位置编码】ALiBi 注意力线性偏置：不存位置向量，反而比 RoPE 外推更好？**
  - [B station](https://www.bilibili.com/video/BV1zW3d6WE9z)
- **【面试高频】删掉开头几个 token 大模型当场崩盘？一图看透 Attention Sink 与 StreamingLLM**
  - [B station](https://www.bilibili.com/video/BV1youa6dEug)
- **【面试高频】M-RoPE 多模态位置编码全解：一套 RoPE 如何通吃文字图片视频**
  - [B station](https://www.bilibili.com/video/BV1Xzua6MEe2)
- **【面试高频】滑动窗口注意力一次讲透：平方级降到线性，小窗口为何能看穿13万token**
  - [B station](https://www.bilibili.com/video/BV1D1ua6PErD)
- **【NeurIPS 2025 最佳论文】Gated Attention：用 head 级 sigmoid 门改进注意力的线性聚合与 attention sink**
  - [B station](https://www.bilibili.com/video/BV1cd826jEGT)
- **【线性注意力】Linear Attention 讲透：核函数替代 softmax，O(n²) 降到 O(n)**
  - [B station](https://www.bilibili.com/video/BV1JE826rEVe)
- **【长文本】LongRoPE 讲透：把 4K 上下文扩到 2048K，非均匀插值 vs 均匀插值**
  - [B station](https://www.bilibili.com/video/BV13e826hE9X)
- **【长上下文】Lost in the Middle 详解：答案放中间为什么就找不到了？兼谈 RAG 重排**
  - [B station](https://www.bilibili.com/video/BV1hi826FEwT)
- **【大模型推理】StreamingLLM 讲透：保留 4 个 sink token 让模型记住无限长对话**
  - [B station](https://www.bilibili.com/video/BV1Rd846yETR)
- **【长文本】attention sink 详解：成因、后果与 StreamingLLM 的解法**
  - [B station](https://www.bilibili.com/video/BV1Tg8t6NE6U)
- **【长文本】4K 扩到 128K：PI、NTK-aware、YaRN 三种外推方法与分阶段训练**
  - [B station](https://www.bilibili.com/video/BV1JjbL6UEPF)
- **【面试高频】BM25 相比 TF-IDF 做了什么改进？非线性饱和 + 长度归一化全解析**
  - [B station](https://www.bilibili.com/video/BV1uGMt67Eig)
- **【RAG 地基】向量数据库索引 HNSW / IVF-PQ：多层图导航、聚类分桶、乘积量化**
  - [B station](https://www.bilibili.com/video/BV1EQKW67EgT)
- **【RAG】HyDE 讲透：先让 LLM"瞎编"答案，再用它去检索真实文档**
  - [B station](https://www.bilibili.com/video/BV1vQ3R6jEds)
- **【面试高频】CRAG 纠错式检索增强：给 RAG 加一道质检，三档纠错让大模型不再胡说**
  - [B station](https://www.bilibili.com/video/BV1v5uY65EXS)
- **【面试高频】GraphRAG 原理拆解：先建图谱再分社区，RAG 终于能答全局问题了**
  - [B station](https://www.bilibili.com/video/BV1zuuY6mEyK)
- **【面试高频】Late Chunking：调换切块和编码顺序，RAG检索质量的零成本提升**
  - [B station](https://www.bilibili.com/video/BV1Liua63ER5)
- **【面试高频】Self-RAG 四种反思 token 全拆解：按需检索 + 批判资料 + 拦截幻觉**
  - [B station](https://www.bilibili.com/video/BV1MSua6aEi6)
- **【RAG 必修】余弦相似度的维度灾难：为什么检索结果全挤在 0.9 附近**
  - [B station](https://www.bilibili.com/video/BV1Sr826dExM)
- **【RAG 实操】检索器与生成器的微调 pipeline：对比学习、上下文利用与联合训练**
  - [B station](https://www.bilibili.com/video/BV1ZT8S61E3b)
- **【RAG 实操】embedding 模型微调：对比学习、InfoNCE 与难负样本挖掘**
  - [B station](https://www.bilibili.com/video/BV1WY8468EbL)
- **我Vibe Coding做的游戏，上架Steam了【B站AI创造公开赛】**
  - [B station](https://www.bilibili.com/video/BV1MPMd64EiD)
- **《群侠传：幸存者》47分钟完整实机演示+开发者全程解说【B站AI创造公开赛】**
  - [B station](https://www.bilibili.com/video/BV1S9uw6jE12)
- **《群侠传：幸存者》开场CG：幸而存生，何处是江湖？**
  - [B station](https://www.bilibili.com/video/BV1j1uB6bEYZ)
- **上架三周，好评如潮，谢谢你玩我用AI做的游戏。**
  - [B station](https://www.bilibili.com/video/BV1eCbA6rEZV)
- **【2025最新版】B站第一套系统的AI绘画课！零基础学会Stable Diffusion，这绝对是你看过的最容易上手的AI绘画教程 | SD WebUI系列课**
  - [B station](https://www.bilibili.com/video/BV1VXYszZEvD)
  - links: https://gf66fxi6ji.feishu.cn/wiki/EmUcwsUoQiwDSqkyZk1cmXyonGe
- **从零开始认识SD模型体系：版本、功能、风格和获取渠道——如何选择合适的AI绘图模型？｜AI绘画+SD WebUI零基础入门系列教程（2025最新版）**
  - [B station](https://www.bilibili.com/video/BV1YdYszoEcj)
  - links: https://gf66fxi6ji.feishu.cn/wiki/EmUcwsUoQiwDSqkyZk1cmXyonGe
- **Stable Diffusion提示词全方位解析：两大书写逻辑+两个绝妙技巧，小白也能快速学会写Prompt！｜AI绘画+SD WebUI零基础入门系列教程**
  - [B station](https://www.bilibili.com/video/BV15RYszbEWd)
  - links: https://gf66fxi6ji.feishu.cn/wiki/EmUcwsUoQiwDSqkyZk1cmXyonGe
- **一个视频，理清Stable Diffusion所有参数的调节方式，自由掌控出图效果！｜AI绘画+SD WebUI零基础入门系列教程（2025最新版）**
  - [B station](https://www.bilibili.com/video/BV1B1YszeEaW)
  - links: https://gf66fxi6ji.feishu.cn/wiki/EmUcwsUoQiwDSqkyZk1cmXyonGe
- **一键“复刻”世界名画！Stable Diffusion图生图技巧详细解析｜AI绘画+SD WebUI零基础入门系列教程（2025最新版）**
  - [B station](https://www.bilibili.com/video/BV1qUYszaEKd)
  - links: https://gf66fxi6ji.feishu.cn/wiki/EmUcwsUoQiwDSqkyZk1cmXyonGe
- **拒绝低质量出图！提高AI绘画分辨率，就靠高分辨率修复了！| SD WebUI高清修复优化细节无损放大教程 · AI绘图零基础入门系列教程（2025最新版）**
  - [B station](https://www.bilibili.com/video/BV1T7eLzdETo)
  - links: https://gf66fxi6ji.feishu.cn/wiki/EmUcwsUoQiwDSqkyZk1cmXyonGe
- **低显存也能跑高清大图！Stable Diffusion放大脚本+附加功能算法放大教程，轻松输出2K级分辨率！ AI绘画零基础入门系列教程（2025最新版）**
  - [B station](https://www.bilibili.com/video/BV1MweEzeEa4)
  - links: https://gf66fxi6ji.feishu.cn/wiki/EmUcwsUoQiwDSqkyZk1cmXyonGe
- **AI绘画的救星！定向修改画面，手把手教你玩转SD局部重绘！ Stable Diffusion WebUI重绘功能详解 · AI绘画零基础入门系列教程（2025最**
  - [B station](https://www.bilibili.com/video/BV1CGeEzdEP3)
  - links: https://gf66fxi6ji.feishu.cn/wiki/EmUcwsUoQiwDSqkyZk1cmXyonGe
- **一个视频，讲明白AI绘画里的2种附加网络模型！LoRA、Embedding分别是什么？怎么用？Stable Diffusion WebUI零基础入门系列教程**
  - [B station](https://www.bilibili.com/video/BV1gnaEzeEiU)
  - links: https://gf66fxi6ji.feishu.cn/wiki/EmUcwsUoQiwDSqkyZk1cmXyonGe
- **Embedding模型的5种用法，懂了才是真高手！Stable Diffusion附加网络模型解析 · AI绘画零基础入门系列教程**
  - [B station](https://www.bilibili.com/video/BV1mxaEzFEWp)
  - links: https://gf66fxi6ji.feishu.cn/wiki/EmUcwsUoQiwDSqkyZk1cmXyonGe
- **LoRA模型的4大分类与实用姿势，一次性讲明白！Stable Diffusion附加网络模型解析 · AI绘画零基础入门系列教程**
  - [B station](https://www.bilibili.com/video/BV1UMaHzuEmy)
  - links: https://gf66fxi6ji.feishu.cn/wiki/EmUcwsUoQiwDSqkyZk1cmXyonGe
- **一个视频搞定10大Stable Diffusion插件：提示词翻译反推+放大修复+抠图重绘！SD WebUI扩展插件专题 · AI绘画零基础入门教程**
  - [B station](https://www.bilibili.com/video/BV1D2pEzVENY)
  - links: https://gf66fxi6ji.feishu.cn/wiki/EmUcwsUoQiwDSqkyZk1cmXyonGe
- **一口气了解10种ControlNet！原理+应用，全方位解析Stable Diffusion控制网！SD WebUI扩展插件专题 · AI绘画零基础入门教程**
  - [B station](https://www.bilibili.com/video/BV1pwpJzAEr8)
  - links: https://gf66fxi6ji.feishu.cn/wiki/EmUcwsUoQiwDSqkyZk1cmXyonGe
- **ComfyUI全球爆红，AI绘画进入“工作流时代”？做最好懂的Comfy UI入门教程：Stable Diffusion专业节点式界面新手教学**
  - [B station](https://www.bilibili.com/video/BV1D7421N7xN)
  - links: https://www.esheep.com/?channel=zz&from=19
- **史诗级更新！ComfyUI“改头换面”，晚一秒更新都是浪费！全新界面、功能与海量体验优化，10分钟带你速览新版本所有操作技巧！（附整合包下载地址）**
  - [B station](https://www.bilibili.com/video/BV1X8xFeCERn)
- **让Comfy UI“无所不能”的秘密——自定义节点！ComfyUI零基础入门教程系列：自定义节点的安装与使用，用ComfyUI Manager一键安装缺失工作流**
  - [B station](https://www.bilibili.com/video/BV1pZ421b7t7)
- **ComfyUI“不好用”？这期视频，帮你找到最正确的入门姿势！全面掌握高清修复+重绘+LoRA+ControlNet，无缝丝滑上手SD Comfy UI教程**
  - [B station](https://www.bilibili.com/video/BV1ab42187er)
- **小白也能听懂的ComfyUI工作流搭建教程！节点连线整理技巧+复杂工作流解构 | AI绘画和SD应用落地的最佳载体！从思路到实操，一口气讲明白！**
  - [B station](https://www.bilibili.com/video/BV19f421q7EU)
  - links: https://www.bilibili.com/opus/982835353717047312
- **太爽了！AI绘画全面进化：懂中文、会做中文设计，还开源免费！Qwen Image+Edit模型零基础教程，一个视频讲清楚全部应用 | 附Comfy UI工作流**
  - [B station](https://www.bilibili.com/video/BV11SabzWEUZ)
  - links: https://pan.baidu.com/s/1kjPwnc4-Ww3NEjrW8-8Z8Q?pwd=y9fk https://pan.quark.cn/s/6cbe46a3f0d1 https://wuying.com/
- **一口气了解FLUX.1：AI生图的“新王”，凭什么震惊世界？FLUX模型使用教程，基本用法到进阶应用，一网打尽！（含SD Forge与ComfyUI整合包）**
  - [B station](https://www.bilibili.com/video/BV1UytNexEUk)
- **取代PS，颠覆AI绘画的新神器？FLUX Kontext零基础上手教程：一句话搞定图像编辑！无缝修图、改文字、换背景 | 含ComfyUI工作流**
  - [B station](https://www.bilibili.com/video/BV1vYKVzfEYB)
- **开源+免费！这个AI彻底改变了美工和设计！FLUX Kontext Dev本地安装与使用教程：最强一致性图像编辑模型！ | 含模型下载与ComfyUI工作流**
  - [B station](https://www.bilibili.com/video/BV1P8KyzAEQ6)
- **关于Stable Diffusion 3.5，这个视频有你需要知道的一切：免费可商用，和Flux比谁强？ | SD3.5使用教程，含ComfyUI工作流与整合包**
  - [B station](https://www.bilibili.com/video/BV1XCmyYME4c)
  - links: https://serverless.datastone.cn/sprite/app/register?marketing_invite_code=2155128
- **8倍加速，低配福音！笔记本跑出“4090级”速度？AI绘图门槛大幅降低，ComfyUI Nunchaku节点详解，四位量化的FLUX模型究竟有多快？| 含工作流**
  - [B station](https://www.bilibili.com/video/BV16WKwzTExU)
  - links: https://github.com/mit-han-lab/ComfyUI-nunchaku/ https://github.com/mit-han-lab/nunchaku/releases https://huggingface.co/mit-han-lab/nunchaku/tree/main
- **一句话修出创意大片，摄影界的“ChatGPT”有多强？零基础小白也能玩的AI摄影生成器，超能画布入门教程，AI绘画应用实践**
  - [B station](https://www.bilibili.com/video/BV1xC411H7NH)
  - links: https://photo.baidu.com/photasy/home】
- **重磅黑科技！让照片“开口说话”，这项AI技术终于可以用了！阿里EMO正式开放，一键同步音频表情、眼神、嘴型，还能唱歌、RAP？新一代AI“数字人”使用教程**
  - [B station](https://www.bilibili.com/video/BV1AF4m1A7kX)
- **可能是全世界最会做设计的AI！3秒一张海报，文案全自动排版，还能做Logo和UI！Ideogram2.0使用教程：最强平面设计大模型，连FLUX都“甘拜下风”！**
  - [B station](https://www.bilibili.com/video/BV1De2uYeEtK)
- **如何将ComfyUI工作流变成月入$1000的AI图像“App”（零代码）| ShellAgent入门教程 · AI Agent Bot手把手搭建教学**
  - [B station](https://www.bilibili.com/video/BV16qQRYoE1r)
- **用嘴改图的AI神器！效率秒杀Photoshop，“开源版”GPT4o来了？ICEdit实测与教程：通过FLUX Fill实现定向编辑 | 含ComfyUI工作流**
  - [B station](https://www.bilibili.com/video/BV1bNEvzrEn1)
- **二次元角色“穿越”现实世界，5种整活玩法，这个AI太强了！Vidu Q1参考生视频教程：AI动画/视频生成如何保证人物角色一致性？**
  - [B station](https://www.bilibili.com/video/BV1vv32zNERc)
- **一句话搞定全套海报+Logo全案+电商合成图！星流Agent全方位使用教程 | Lovart“中文版”开放使用！无需邀请码！**
  - [B station](https://www.bilibili.com/video/BV1Eb8XzuEqC)
  - links: https://www.xingliu.art/
- **0代码开发AI应用，一句话生成完整App！ShellAgent 2.0使用教程：全球首个“Text 2 App”工具，靠自然语言做完全套开发工作？**
  - [B station](https://www.bilibili.com/video/BV1yNt3zdEHu)
- **0 基础 22 分钟速通大模型应用：无痛学会DeepSeek+ChatGPT+一切AI对话软件，我为你总结了这四大“必备场景”——**
  - [B station](https://www.bilibili.com/video/BV1J5TfzYEuk)
  - links: https://gf66fxi6ji.feishu.cn/wiki/AooDweIrNiVOSmkMkmvcpHGtnmd
- **拳打PS Beta，SD Web UI最强“替代品”，Invoke AI竟然这么好用！开源免费可商用，内附安装教程与基本操作指南！| AI绘画入门教程**
  - [B station](https://www.bilibili.com/video/BV1xc411M7hp)
  - links: https://github.com/invoke-ai/InvokeAI（ https://pan.quark.cn/s/98b88f75cc5f（ https://www.amazonaws.cn/free/
- **超详细云端部署Stable Diffusion教程！100%还原本地操作，免费试用3个月，自由切换模型、扩展，阿里云的函数计算太香了！| 在线安装Web UI**
  - [B station](https://www.bilibili.com/video/BV19u411x7Bk)
  - links: https://free.aliyun.com/?productCategory=%E5%87%BD%E6%95%B0%E8%AE%A1%E7%AE%97%20FC&scm=20140722.M_9489742._.V_1?spm=a1z389.11499242.0.0.65452413jgv5bn&utm_content=g_1000372611 https://www.aliyun.com/product/fc?spm=5176.devs https://free.aliyun.com/?product=9657388
- **一口气实测SD+FLUX+DeepSeek，RTX 50系显卡AI绘图/视频/LLM性能全方位测试！—— 5070Ti&70&80&5090D AIGC速度测评**
  - [B station](https://www.bilibili.com/video/BV1av9oY9Ez2)
- **1秒6张图，比4090快1.5倍？5090 D & 5080 AI画图速度测评 |  RTX 50系显卡上手体验 | Stable Diffusion/FLUX**
  - [B station](https://www.bilibili.com/video/BV1vCFLefE94)
- **首个40系SUPER显卡“AI评测”：速度提升50%？生成视频也很快！Stable Diffusion 绘画 & SVD动画性能实测 70S/70TiS/80S**
  - [B station](https://www.bilibili.com/video/BV1Yx4y1Z7xk)
- **AI绘画的“显存杀手”？5块全新40系显卡怒测“最强开源大模型”——Stable Diffusion XL效率测试&使用技巧，SDXL低显存Web UI优化指南**
  - [B station](https://www.bilibili.com/video/BV1MG411R7XQ)
  - links: https://www.notion.so/nenly/1-732d811aff564e8387924f4ff5a106bd?pvs=4（
- **显卡速度翻3倍，AI绘画进入“秒速时代”？Stable Diffusion究极加速插件，NVIDIA TensorRT扩展安装与使用全方位教程**
  - [B station](https://www.bilibili.com/video/BV1Lv411F7Rr)
  - links: https://github.com/NVIDIA/Stable-Diffusion-WebUI-TensorRT https://www.nvidia.cn/geforce/drivers/ https://www.nvidia.cn/geforce/geforce-experience/
- **国产显卡到底能不能跑AI？摩尔线程MTT S4000 GPU“云”实测，ComfyUI / SD / 混元3D都能用！**
  - [B station](https://www.bilibili.com/video/BV11buJzqEm9)
  - links: https://www.autodl.com/market/list https://academy.mthreads.com/ https://maliang.mthreads.com/
- **大概是站内第一个SORA系统实操教程：SORA全功能讲解+分析！【OpenAI发布全新视频生成模型】**
  - [B station](https://www.bilibili.com/video/BV1HZqkYREmx)
- **一口气入门AI视频：3大主流路径与30个热门工具，全面分析AI做视频的各种技巧！|  AI视频生成入门教程&软件盘点：图生视频、转绘、二创拥抱整活、数字人 …**
  - [B station](https://www.bilibili.com/video/BV1mJyTYEEPT)
- **一线艺术家的AI短片工作流揭秘：“大佬”们这样用AI做视频！如何制作一个“商业级”的AI生成品牌宣传片？| 七彩虹iGame Ultra Family主机**
  - [B station](https://www.bilibili.com/video/BV1F8zBYLEKp)
- **最强免费AI视频模型，颠覆后期剪辑素材行业！一张图生成视频空镜，Stable Video Diffusion（SVD）零基础上手使用教学 ComfyUI工作流**
  - [B station](https://www.bilibili.com/video/BV1iZ421t7Ax)
  - links: https://www.bilibili.com/read/cv33109228/ https://www.bilibili.com/read/cv33251369
- **AI视频时代的“开源先驱”：Sora来之前，你可以先掌握这些——AnimateDiff动画插件全方位教学，制作丝滑流畅动图！Stable Diffusion应用**
  - [B station](https://www.bilibili.com/video/BV1zS421A7PG)
- **Deforum AI视频生成入门教程：打造过亿播放的爆款短视频，20分钟学会Stable Diffusion“瞬息全宇宙”！AI空间运镜无限穿越动画生成**
  - [B station](https://www.bilibili.com/video/BV1Fy421v7SB)
- **15分钟入门AI动画！Mov2Mov零基础教学，用Stable Diffusion生成酷炫逐帧重绘动画短视频，开启低成本动画时代 | 扩展插件教程**
  - [B station](https://www.bilibili.com/video/BV1Su411b7Nm)
  - links: https://pan.quark.cn/s/98b88f75cc5f https://pan.baidu.com/s/10rzgzIjzad7AKmj-w8zO_w?pwd=nely
- **10倍效率，打造无闪烁丝滑AI动画！EbSynth插件全流程操作解析与原理分析，超智能的“补帧”动画制作揭秘！| Stable Diffusion扩展插件教程**
  - [B station](https://www.bilibili.com/video/BV1uX4y1H7U3)
- **可能是目前最适合小白的AI视频工具：免费、不限次数，一键扩写脚本，还能自动“配音”？阿里通义万相模型测评 | AI做视频的软件工具入门教程**
  - [B station](https://www.bilibili.com/video/BV1M9tnevEBh)
  - links: https://tongyi.aliyun.com/wanxiang/videoCreation
- **2天用AI做完一个“商业级"广告？5090D首发宣传片“AI版”工作流分享！ | AIGC短片幕后分享 & AI生成视频教程 | 华硕RTX 5090D显卡**
  - [B station](https://www.bilibili.com/video/BV1RkfEYAEyj)
- **全站首个【教程】工作流分享！百万播放的系列课是如何诞生的？策划剪辑视频后期全流程揭秘，学AI绘画一定看过这套Stable Diffusion入门课——**
  - [B station](https://www.bilibili.com/video/BV14X4y1p7A9)
- **8年设计师，聊聊AI是怎么把我“取代”的：创意工作者如何面对AI浪潮？经历分享与职业建议 | ProArt创艺国度校园行分享记录**
  - [B station](https://www.bilibili.com/video/BV1TR1aYxEYM)
- **我一臭打游戏的，AI革命和我有啥关系？**
  - [B station](https://www.bilibili.com/video/BV1Ai421a7ns)
- **全 世 界 都 在 学 A I 绘 画 ——**
  - [B station](https://www.bilibili.com/video/BV16u411j7u3)
- **我在WAIC见到了马斯克和Stable Diffusion的创始人！聊大模型、AI应用的未来、AI焦虑？探秘2023世界人工智能大会——**
  - [B station](https://www.bilibili.com/video/BV1rh4y1f7XJ)
- **B站第一套系统的AI绘画课！零基础学会Stable Diffusion，这绝对是你看过的最容易上手的AI绘画教程 | SD WebUI 保姆级攻略**
  - [B station](https://www.bilibili.com/video/BV1As4y127HW)
  - links: https://nenly.notion.site/017c3341c8b84a7ebb4c2cb16f36e28f https://pan.quark.cn/s/98b88f75cc5f https://pan.baidu.com/s/10rzgzIjzad7AKmj-w8zO_w?pwd=nely
- **20分钟搞懂Prompt与参数设置，你的AI绘画“咒语”学明白了吗？ | 零基础入门Stable Diffusion·保姆级新手教程 | Prompt关键词教学**
  - [B station](https://www.bilibili.com/video/BV12X4y1r7QB)
  - links: https://nenly.notion.site/017c3341c8b84a7ebb4c2cb16f36e28f https://pan.quark.cn/s/98b88f75cc5f https://pan.baidu.com/s/10rzgzIjzad7AKmj-w8zO_w?pwd=nely
- **打破次元壁！用AI“重绘”照片和CG，效果惊艳到我了—— | Stable Diffusion图生图零基础入门·保姆级新手教程 | AI漫画特效&赛博Coser**
  - [B station](https://www.bilibili.com/video/BV1Lh411u7vs)
  - links: https://nenly.notion.site/017c3341c8b84a7ebb4c2cb16f36e28f https://pan.quark.cn/s/98b88f75cc5f https://pan.baidu.com/s/10rzgzIjzad7AKmj-w8zO_w?pwd=nely
- **AI绘画模型新手包！“画风”自由切换，有哪些你不知道的模型使用技巧？ | 零基础入门Stable Diffusion的保姆级新手教程 | SD模型下载方式与推荐**
  - [B station](https://www.bilibili.com/video/BV1Us4y117Rg)
  - links: https://nenly.notion.site/017c3341c8b84a7ebb4c2cb16f36e28f https://pan.quark.cn/s/98b88f75cc5f https://pan.baidu.com/s/10rzgzIjzad7AKmj-w8zO_w?pwd=nely
- **拒绝低质量出图！3种快速提高AI绘画分辨率的方式，十分钟讲完！| StableDiffusion WebUI 保姆级攻略·高清修复优化细节无损放大教程**
  - [B station](https://www.bilibili.com/video/BV11m4y12727)
  - links: https://nenly.notion.site/017c3341c8b84a7ebb4c2cb16f36e28f https://pan.quark.cn/s/98b88f75cc5f https://pan.baidu.com/s/10rzgzIjzad7AKmj-w8zO_w?pwd=nely
- **Embeddings是啥？怎么用？三大AI绘画高级模型概念解析，懂了才是真高手！| StableDiffusion保姆级教程·模型原理解析及应用**
  - [B station](https://www.bilibili.com/video/BV1th4y1p7fH)
  - links: https://nenly.notion.site/017c3341c8b84a7ebb4c2cb16f36e28f https://pan.quark.cn/s/98b88f75cc5f https://pan.baidu.com/s/10rzgzIjzad7AKmj-w8zO_w?pwd=nely
- **AI绘画的救星！定向修手修脸，手把手教你玩转局部重绘！| StableDiffusion WebUI 保姆级教程·inPainting功能详解·含PS操作**
  - [B station](https://www.bilibili.com/video/BV1uL411e7Uk)
  - links: https://nenly.notion.site/017c3341c8b84a7ebb4c2cb16f36e28f https://pan.quark.cn/s/98b88f75cc5f https://pan.baidu.com/s/10rzgzIjzad7AKmj-w8zO_w?pwd=nely
- **新手入门：如何在SD里安装扩展插件？ | StableDiffusion教程 拓展（Extensions）的安装与应用**
  - [B station](https://www.bilibili.com/video/BV1hz4y1a76M)
  - links: https://nenly.notion.site/017c3341c8b84a7ebb4c2cb16f36e28f https://pan.quark.cn/s/98b88f75cc5f https://pan.baidu.com/s/10rzgzIjzad7AKmj-w8zO_w?pwd=nely
- **LoRA从原理到实践，零基础打造赛博Coser、一键更换服饰，无所不能！5大应用方向剖析 & 保姆级讲解！Stable Diffusion AI绘画**
  - [B station](https://www.bilibili.com/video/BV1nL411B7XT)
  - links: https://nenly.notion.site/017c3341c8b84a7ebb4c2cb16f36e28f https://pan.quark.cn/s/98b88f75cc5f https://pan.baidu.com/s/10rzgzIjzad7AKmj-w8zO_w?pwd=nely
- **30分钟零基础掌握ControlNet！绝对是你看过最好懂的控制网原理分析 | 基本操作、插件安装与5大模型应用 · Stable Diffusion教程**
  - [B station](https://www.bilibili.com/video/BV1Ds4y1e7ZB)
  - links: https://pan.quark.cn/s/98b88f75cc5f https://pan.baidu.com/s/10rzgzIjzad7AKmj-w8zO_w?pwd=nely https://nenly.notion.site/017c3341c8b84a7ebb4c2cb16f36e28f
- **Multi Diffusion + Tiled VAE + ControlNet Tile模型，低显存打造AI绘画超高清6K分辨率体验！SD扩展插件教程**
  - [B station](https://www.bilibili.com/video/BV1Su4y1d7Dp)
- **“牛逼”的教程来了！一次学会AI二维码+艺术字+光影光效+创意Logo生成，绝对是B站最详细的Stable Diffusion特效设计流程教学！AI绘画进阶应用**
  - [B station](https://www.bilibili.com/video/BV1gX4y1J7ei)
- **AI打开新世界大门！立绘一键“真人化”，还能换皮肤！ControlNet LineArt 线稿上色+换装换背景，Stable Diffusion系统教程**
  - [B station](https://www.bilibili.com/video/BV1oB4y1R7Ms)
  - links: https://nenly.notion.site/AI-f93575fc3b63418bbb98faf9a02fb854?pvs=4
- **AI再进化，这次竟然学会摄影了！一秒生成胶片风、拍立得，还能智能“修脸”！Stable Diffusion AI绘画真实系人像模型+LoRA推荐**
  - [B station](https://www.bilibili.com/video/BV1DP41167bZ)
- **我用AI修复了50年前的亚运会老照片！Stable Diffusion智能上色+高清修复教程！StableSR + ControlNetTile&Recolor**
  - [B station](https://www.bilibili.com/video/BV1mm4y1575y)
  - links: https://click.aliyun.com/m/1000380882/ https://nenly.notion.site/73af68ee048e4f9ab0dba7956c515229?pvs=4
- **一秒打通PS+SD！AI功能免费“平替”，还支持ControlNet？Auto Stable Diffusion Photoshop插件教程，释放轻薄本AI潜力**
  - [B station](https://www.bilibili.com/video/BV1Zj411h7od)
  - links: https://github.com/AbdullahAlfaraj/Auto-Photoshop-StableDiffusion-Plugin https://pan.quark.cn/s/98b88f75cc5f https://pan.baidu.com/s/10rzgzIjzad7AKmj-w8zO_w?pwd=nely
- **AI一键调光布景，这个开源神器改变了摄影和设计！IC-Light教程，全自动融图调色，附一键包+ComfyUI工作流+SD Forge插件 | 华硕天选Air**
  - [B station](https://www.bilibili.com/video/BV1Yy411e7y1)
- **5秒生成一张分图层AI素材，“抠图”已成过去式？设计师的免费PNG“素材库”！ControlNet作者新作，Layer Diffusion生成免抠AI绘图素材！**
  - [B station](https://www.bilibili.com/video/BV1Xq421F7Ny)
- **8张照片训练个人LoRA，一分钱不花打造“AI写真”？Stable Diffusion EasyPhoto扩展插件教程，轻松训练AI绘画人脸模型**
  - [B station](https://www.bilibili.com/video/BV1b8411k7fb)
  - links: https://github.com/aigc-apps/sd-webui-EasyPhoto https://www.bilibili.com/video/BV1mm4y1575y?t=809.2 https://nenly.notion.site/EasyPhoto-AI-b8cfabb1b82a4a30b49d8d0a37dd4581?pvs=4
- **靠AI开一家服装店？超详细AI衣服款式设计+“AI模特”换装教程 | Stable Diffusion商业落地实践&男女装电商应用，一秒生成“摄影级”产品图**
  - [B station](https://www.bilibili.com/video/BV1994y1W7Tg)
  - links: https://nenly.notion.site/AI-5653d05481264235b9871d17403727cf https://developer.aliyun.com/adc/series/activity/aigc_design https://click.aliyun.com/m/1000379966/
- **一流模型！10个高手都在用的二次元插画绘画风大模型推荐，内附模型下载渠道与出图参数提示词关键词模版 | AI绘画 · StableDiffusion**
  - [B station](https://www.bilibili.com/video/BV1Us4y1M7x4)
  - links: https://www.liblibai.com/#/】
- **关于SDXL 1.0，这个视频里有你想知道的全部 | 15分钟全面解读，AI绘画即将迎来“新时代”？Stable Diffusion XL大模型安装及使用教程**
  - [B station](https://www.bilibili.com/video/BV1TM4y1p7RJ)
- **手稿变动画，AI生成3D贴图，艺术家手里的Stable Diffusion把我惊呆了！SD进阶工作流分享，强势辅助插画线稿上色+Blender建模！**
  - [B station](https://www.bilibili.com/video/BV1ma4y1z7Cs)
  - links: https://nenly.notion.site/9e920bfe34b34326bffece505789d63d?pvs=74 https://huggingface.co/stabilityai/stable-video-diffusion-img2vid/tree/main https://www.youtube.com/watch?v=teIKjugRFlo
- **B站第一套系统的AI绘画模型训练课程！零基础入门“炼丹”，制作属于你的SD模型！模型微调（Dreambooth、LoRA、Embedding）原理分析教学**
  - [B station](https://www.bilibili.com/video/BV1TK411v7Jw)
  - links: https://gf66fxi6ji.feishu.cn/wiki/CEQgw0Bfdi1HBRktnIxcNg7CnRf（ https://pan.baidu.com/s/1W4ha-dMcoaCqF4ltyDNf7A?pwd=nely https://pan.quark.cn/s/8bcb33aa5c89
- **60分钟速通LORA训练！绝对是你看过最好懂的AI绘画模型训练教程！StableDiffusion超详细训练原理讲解+实操教学，LORA参数详解与训练集处理技巧**
  - [B station](https://www.bilibili.com/video/BV16e411e7Zx)
  - links: https://space.bilibili.com/507303431 https://space.bilibili.com/219296
- **照片发光了！超详细的PS光感设计教程：一个“发光”小技巧，让你的设计不再普通 | PS视觉合成教程，照片修图后期讲解！**
  - [B station](https://www.bilibili.com/video/BV1tq4y1P7Nk)
- **无需3D建模，用PS制作一个梦幻宇宙星球，简单几步就能搞定 | Photoshop视觉合成教程系列**
  - [B station](https://www.bilibili.com/video/BV1JL4y1W7At)
- **视觉效果拉满！这个PS教程，教你轻松设计“赛博朋克”的科幻光环效果！（适合海报设计/摄影后期修图）| Photoshop视觉合成系列设计课**
  - [B station](https://www.bilibili.com/video/BV1844y1a7ty)
- **用AI制作一个酷炫的三维文字环绕效果（科幻感光环合成补充教程） |  PS视觉合成系列 For 平面设计 & 摄影后期修图 By Nenly**
  - [B station](https://www.bilibili.com/video/BV1LR4y1W7Zm)
- **使用Photoshop，为你的照片添加闪亮的夜景光斑效果 | PS设计课：视觉合成系列教程（适用于海报设计、摄影后期修图等）**
  - [B station](https://www.bilibili.com/video/BV1hg411w7k3)
- **用PS设计梦幻的后期夜景光照效果（补充教程）| PS设计课：视觉合成系列教程（适用于海报设计、摄影后期修图等）**
  - [B station](https://www.bilibili.com/video/BV1nq4y127LN)
- **PS合成技巧：在高速公路上划船的“秘笈”！巧妙融合马路与水面—— | Photoshop视觉合成系列**
  - [B station](https://www.bilibili.com/video/BV1Yr4y1J7MR)
- **如何利用PS制作漫画风人像手绘效果？ | 3分钟PS小技巧**
  - [B station](https://www.bilibili.com/video/BV11V411n75u)
- **文字消失术！如何用PS制作酷炫的文字粒子消散效果？| 设计案例教程 Daily Poster 海报设计第2期**
  - [B station](https://www.bilibili.com/video/BV1wA411A7uN)
- **三步，用PS制作一个立体金属文字，十分钟一定能让你学会 | Photoshop文字设计教程**
  - [B station](https://www.bilibili.com/video/BV113411i76R)
- **这么甜的文字设计，是我能用PS做出来的吗？不用怀疑，三步搞定一个“果冻文字”，你上你也行 | 字体效果设计系列，Photoshop教程，设计公开课**
  - [B station](https://www.bilibili.com/video/BV1934y1S75B)
- **太酷炫了！用PS打造一个霓虹灯文字效果，这个教程15分钟一定能教会你 | Photoshop技巧教学，字效设计系列 & 视觉设计**
  - [B station](https://www.bilibili.com/video/BV1bq4y1K79B)
- **全自动操作，三步实现“故障风”的PS文字效果，你能做到吗？（内附Photoshop源文件，可一键替换文字内容）**
  - [B station](https://www.bilibili.com/video/BV1n44y1t768)
- **PS教程：制作一个可口又可爱的“曲奇饼干”文字效果，简单清晰，你也能学会 | Photoshop字效设计系列，平面海报设计**
  - [B station](https://www.bilibili.com/video/BV1wq4y157zm)
- **用PS一键生成3D透视立体文字，十分钟教程，五分钟操作 | Photoshop字体效果设计系列**
  - [B station](https://www.bilibili.com/video/BV1bR4y1t7Yn)
- **用PS制作一个炫彩油漆笔刷字，这是为你准备的详细教程—— | Photoshop字体效果设计系列**
  - [B station](https://www.bilibili.com/video/BV1Aq4y1r7qb)
- **PS教程：我的文字设计是用雪“堆”起来的，你的呢？这个“冰雪文字”，超适合你的圣诞海报设计 —— Photoshop字体效果设计课**
  - [B station](https://www.bilibili.com/video/BV1iY411p75L)
- **PS教程来了！超酷炫的迷幻流体渐变文字，10分钟教你学会搞定！潮到爆炸的“酸性”风，少不了这个设计—— | PS字体效果系列免费教程**
  - [B station](https://www.bilibili.com/video/BV1GF411i77d)
- **PS教程：三步打造潮到爆炸的酸性镀铬文字效果设计！适用于酷炫的海报、视觉设计 | Photoshop字体效果设计系列 By Nenly**
  - [B station](https://www.bilibili.com/video/BV1Yr4y1B7AP)
- **酸性热成像风格文字设计，用PS三步搞定 | Photoshop字体设计系列课 | 酸性潮流设计 | 适用于海报、视觉设计**
  - [B station](https://www.bilibili.com/video/BV1k541127TE)
- **游戏秒变“8-Bit”像素风？这两个方法，你该学起来了！一期复古像素风PS视觉设计效果教程（适用于插画、摄影、后期） | Photoshop视觉设计课**
  - [B station](https://www.bilibili.com/video/BV1Ve4y1X7CL)
- **PS教程：设计三步变“燃”，从图层样式和混合模式开始 —— Photoshop字体效果设计系列课 | 适用于海报设计、特效制作**
  - [B station](https://www.bilibili.com/video/BV19a411Y7pq)
- **【PS教程】你要的小清新，靠植物的神奇“穿插”来实现—— | Photoshop视觉设计系列 | 文艺风海报标题设计**
  - [B station](https://www.bilibili.com/video/BV1B94y11764)
- **酷炫、高级的魔法烟雾效果，用PS两步轻松搞定 | Photoshop视觉设计系列 | 适用于海报主视觉 & 字体设计等**
  - [B station](https://www.bilibili.com/video/BV1nN4y1j7QJ)
- **设计怎么“找素材”？适合新手的素材搜索“2步法”，高效收获对口的设计素材——（素材搜索教程，内附各类型素材网站推荐）**
  - [B station](https://www.bilibili.com/video/BV1Qq4y1h7YH)
  - links: https://js.design/］
- **第1课：新手上路，如何挑选适合自己的PS软件版本？ | Photoshop百科全书 · PS教程系列公开课 · 零基础入门学设计**
  - [B station](https://www.bilibili.com/video/BV1xT4y1S7CK)
- **第2课：新手必看！如何获取最新版本的PS软件资源？（内附2022版安装包地址）| Photoshop百科全书 · PS教程系列公开课 · 零基础入门学设计**
  - [B station](https://www.bilibili.com/video/BV11q4y1479F)
- **一秒修复照片！移除人像、修补裂痕、去除污渍，PS自带的这四大“黑科技”工具，99%的人都没打开用过—— | Photoshop百科全书 · PS教程系列公开课**
  - [B station](https://www.bilibili.com/video/BV1Xr4y1B7J6)
- **用PS，在云端与超级月亮共舞  |  Photoshop视觉合成流程拆解 · 第001期（三连过百出教程）**
  - [B station](https://www.bilibili.com/video/BV1sS4y1e78q)
- **PS深度映射，打造酷炫的星空螺旋视觉效果 | Photoshop教程，设计过程快放 & 作品展示**
  - [B station](https://www.bilibili.com/video/BV1ev411Y7dA)
- **如何用PS设计一个“饼干字”标题？展示一下操作流程 | Photoshop教学设计流程快放**
  - [B station](https://www.bilibili.com/video/BV14A411K7ox)
- **PS视觉合成效果教程：如何设计一只瓶中的鲸鱼？设计全过程展示——**
  - [B station](https://www.bilibili.com/video/BV1ZX4y1G7D7)
- **用PS设计一张“月球表面”质感的海报，没有素材，自己动手做 | PS设计过程快放 & 作品展示**
  - [B station](https://www.bilibili.com/video/BV1Mf4y167GS)
- **PS置换滤镜设计人脸文字海报，超级有艺术感的设计手法！（全流程展示）**
  - [B station](https://www.bilibili.com/video/BV1Hy4y1a7eb)
- **如何用PS制作一个创意“传送门”？设计全过程来了 | Photoshop视觉合成教程**
  - [B station](https://www.bilibili.com/video/BV1qA411M7Yi)
- **如何用PS制作一张酷炫的渐变Photoshop人像海报？模仿练习——视觉与版式设计 | Daily Poster**
  - [B station](https://www.bilibili.com/video/BV183411q7hp)
- **1986卫报广告：《视角》The Guardian's 1986 'Points of view' advert**
  - [B station](https://www.bilibili.com/video/BV1Er421L7ac)
  - links: https://www.youtube.com/watch?v=_SsccRkLLzU&ab_channel=TheGuardian
- **判断英语权重的正确逻辑**
  - [B station](https://www.bilibili.com/video/BV1MBao6xE3Q)
- **晶格玻尔兹曼方法LBM01-宏观，微观，介观**
  - [B station](https://www.bilibili.com/video/BV192SDBoEnu)
- **晶格玻尔兹曼方法LBM02-连续介质流体力学复习**
  - [B station](https://www.bilibili.com/video/BV1U9dJBVE3s)
- **晶格玻尔兹曼方法LBM03-玻尔兹曼方程**
  - [B station](https://www.bilibili.com/video/BV1sGocBpEZJ)
- **晶格玻尔兹曼方法LBM04-分布函数的矩**
  - [B station](https://www.bilibili.com/video/BV1DwRCBGE4H)
- **晶格玻尔兹曼方法LBM05-从玻尔兹曼方程推导宏观方程**
  - [B station](https://www.bilibili.com/video/BV1HhR4BEETQ)
- **晶格玻尔兹曼方法LBM06-BGK近似，局部平衡分布函数**
  - [B station](https://www.bilibili.com/video/BV1qsVF6AEbr)
- **晶格玻尔兹曼方法LBM07-局部平衡分布函数的矩**
  - [B station](https://www.bilibili.com/video/BV1PFJH6pEmZ)
- **晶格玻尔兹曼方法08-从BE恢复NSE**
  - [B station](https://www.bilibili.com/video/BV1iP756mEdR)
- **特征值与特征向量01-基本知识复习**
  - [B station](https://www.bilibili.com/video/BV1mKNTzFEmY)
- **行列式01-行列式计算1**
  - [B station](https://www.bilibili.com/video/BV1W9c5ziERw)
- **线性映射01-基本知识复习与简单练习**
  - [B station](https://www.bilibili.com/video/BV1Pui2B8EhV)
- **行空间01-寻找子空间的基1**
  - [B station](https://www.bilibili.com/video/BV15kiuBGEas)
- **向量空间的基01-基本知识复习与简单练习**
  - [B station](https://www.bilibili.com/video/BV1RQBUBxEMn)
- **向量空间01-基本知识复习**
  - [B station](https://www.bilibili.com/video/BV1SPUSBCErf)
- **初等矩阵与可逆矩阵01-基本知识复习与简单练习**
  - [B station](https://www.bilibili.com/video/BV14F1sBbEh4)
- **线性方程组01-基本知识复习**
  - [B station](https://www.bilibili.com/video/BV1N7ymBpENU)
- **矩阵01-对称与反对称**
  - [B station](https://www.bilibili.com/video/BV12JsqzhER1)
- **复数与多项式01-基本运算性质**
  - [B station](https://www.bilibili.com/video/BV1TZ4BzGEQk)
- **域01-判断域1**
  - [B station](https://www.bilibili.com/video/BV1e94JzwEgM)
- **【淅沥橙基础数学精品】线性代数A（已完结）**
  - [B station](https://www.bilibili.com/video/BV1HB4gzHE9o)
- **数学分析一第1课-基本概念和简介**
  - [B station](https://www.bilibili.com/video/BV1doPPzeEY5)
- **数学分析一第2课-数列的极限性质**
  - [B station](https://www.bilibili.com/video/BV1qRwAzFEdm)
- **数学分析一第3课-数列审敛**
  - [B station](https://www.bilibili.com/video/BV1BbA7zME5F)
- **数学分析一第4课-子数列**
  - [B station](https://www.bilibili.com/video/BV1NaX8BtEgL)
- **数学分析一第5课-拓扑学简介，函数简介**
  - [B station](https://www.bilibili.com/video/BV1CGS9BmEXD)
- **数学分析一第6课-函数的极限**
  - [B station](https://www.bilibili.com/video/BV1sf5y6rEmM)
- **数学分析一第7课-连续函数**
  - [B station](https://www.bilibili.com/video/BV1yhLw69Ese)
- **数学分析一第8课-导数**
  - [B station](https://www.bilibili.com/video/BV1ZuEm6jEDR)
- **常微分方程ODE新版（一）：一阶方程**
  - [B station](https://www.bilibili.com/video/BV1tCPpe2E7E)
  - links: https://pan.baidu.com/s/13MC3nNCIOpWtL7rbfdbSXQ
- **常微分方程ODE练习一：一阶方程**
  - [B station](https://www.bilibili.com/video/BV12qotY6E55)
- **常微分方程ODE02：n阶线性齐次方程的基本性质**
  - [B station](https://www.bilibili.com/video/BV1hMRUYPEqA)
- **常微分方程ODE03: 降阶法**
  - [B station](https://www.bilibili.com/video/BV11hdSYcEjF)
- **常微分方程ODE04：n阶线性常系数齐次方程**
  - [B station](https://www.bilibili.com/video/BV1ni5EzrE7T)
- **常微分方程ODE05: n阶线性常系数非齐次方程的待定系数法**
  - [B station](https://www.bilibili.com/video/BV1nrGkzBEmm)
- **常微分方程ODE06: 振子与共振**
  - [B station](https://www.bilibili.com/video/BV1vqJez9Ehf)
- **常微分方程ODE07: Euler方程**
  - [B station](https://www.bilibili.com/video/BV1hZj9zcEAy)
- **常微分方程ODE08: n阶线性非齐次方程：常数变易法**
  - [B station](https://www.bilibili.com/video/BV1m6NxzUEMi)
- **常微分方程ODE09: 一阶线性方程组简介**
  - [B station](https://www.bilibili.com/video/BV132gHzoEPx)
- **常微分方程ODE10: 求解一阶线性常系数方程组**
  - [B station](https://www.bilibili.com/video/BV1MshAzQEBB)
- **ODE11-求解一阶线性常系数方程组练习**
  - [B station](https://www.bilibili.com/video/BV1fehhzEEZ6)
- **ODE12-线性非齐次方程组**
  - [B station](https://www.bilibili.com/video/BV1qyHnzbE6S)
- **傅里叶级数和积分变换（一）：傅里叶级数**
  - [B station](https://www.bilibili.com/video/BV1Nm4y1F7eW)
  - links: https://pan.baidu.com/s/1At23_1dTJQeSuGMNcAoaKA
- **傅里叶级数和积分变换（二）：傅里叶变换和拉普拉斯变换基础**
  - [B station](https://www.bilibili.com/video/BV1bAqgYGENQ)
  - links: https://www.bilibili.com/video/BV1Nm4y1F7eW/?vd_source=2e0ba5ab2ea18243a228cb0ffc59bf75 https://pan.baidu.com/s/1BigPT1cQ7qrz1TsMmeC1Tg
- **复变函数新编集版（已完结）**
  - [B station](https://www.bilibili.com/video/BV1P44y1873i)
- **多相流01-多相流简介和离散相基本性质**
  - [B station](https://www.bilibili.com/video/BV1BS4y1A7Ej)
- **多相流02-相间耦合**
  - [B station](https://www.bilibili.com/video/BV16r4y1J74N)
- **多相流03-相间耦合续**
  - [B station](https://www.bilibili.com/video/BV1fB4y127xe)
- **多相流04-单颗粒方程**
  - [B station](https://www.bilibili.com/video/BV1eY411w7R3)
- **多相流05-单颗粒能量守恒**
  - [B station](https://www.bilibili.com/video/BV1fB4y1172k)
- **多相流06-质量耦合**
  - [B station](https://www.bilibili.com/video/BV1ER4y1N7fK)
- **多相流07-曳力**
  - [B station](https://www.bilibili.com/video/BV1WA4y1Q7A5)
- **多相流08-曳力影响因素**
  - [B station](https://www.bilibili.com/video/BV1r3411N7KM)
- **多相流09-颗粒其他受力**
  - [B station](https://www.bilibili.com/video/BV1ou411r7d2)
- **气液界面流01-表面张力1**
  - [B station](https://www.bilibili.com/video/BV13B4y1W7gM)
- **气液界面流02-表面张力2**
  - [B station](https://www.bilibili.com/video/BV1zr4y1M73A)
- **气液界面流03-界面描述1**
  - [B station](https://www.bilibili.com/video/BV1nY4y1J7ba)
- **气液界面流04-界面描述2**
  - [B station](https://www.bilibili.com/video/BV1CN41127Hy)
- **气液界面流05-流动方程1**
  - [B station](https://www.bilibili.com/video/BV1Ax4y1Z7qP)
- **气液界面流06-流动方程2**
  - [B station](https://www.bilibili.com/video/BV1NV41157G2)
- **多分散多相流1-简介，NDF**
  - [B station](https://www.bilibili.com/video/BV1vT4y1y7dj)
- **多分散多相流2-细颗粒的PBE**
  - [B station](https://www.bilibili.com/video/BV1GS4y157xy)
- **多分散多相流3-细颗粒的PBE（续），气固流的KE**
  - [B station](https://www.bilibili.com/video/BV1s34y1y7yj)
- **动力学01-向量**
  - [B station](https://www.bilibili.com/video/BV1JZ4y1q7Ki)
- **动力学02-运动学基础，切法坐标**
  - [B station](https://www.bilibili.com/video/BV1234y157mF)
- **动力学03-极坐标**
  - [B station](https://www.bilibili.com/video/BV1qW4y1J7WC)
- **动力学04-移动旋转坐标系**
  - [B station](https://www.bilibili.com/video/BV1Ch4y1M71j)
- **第二门计算机课-正课（完）**
  - [B station](https://www.bilibili.com/video/BV1RD4y1z7dy)
- **第二门计算机课之UNIX**
  - [B station](https://www.bilibili.com/video/BV15N411F7T4)
  - links: https://www.bilibili.com/video/BV1Q44y1x7Q4/ https://www.bilibili.com/video/BV1RD4y1z7dy/
- **第二门计算机课之C语言（上）**
  - [B station](https://www.bilibili.com/video/BV1Mk4y1t7BD)
  - links: https://www.bilibili.com/video/BV1Q44y1x7Q4/ https://www.bilibili.com/video/BV1RD4y1z7dy/ https://www.bilibili.com/video/BV15N411F7T4/
- **第二门计算机课之C语言（下）**
  - [B station](https://www.bilibili.com/video/BV1a84y13728)
- **C++（1）：类**
  - [B station](https://www.bilibili.com/video/BV1Mh4y1d7FN)
- **C++（2）：异常**
  - [B station](https://www.bilibili.com/video/BV1Qu411p7tM)
- **C++（3）：OOP**
  - [B station](https://www.bilibili.com/video/BV12P411v7QM)
- **Python（上）：基础**
  - [B station](https://www.bilibili.com/video/BV1eN41167dt)
- **Python（下）：OOP**
  - [B station](https://www.bilibili.com/video/BV1Ch411N7Cx)
- **工程数学之格林函数解常微分方程**
  - [B station](https://www.bilibili.com/video/BV1NM411B7PN)
- **工程数学之渐进分析/摄动理论基础**
  - [B station](https://www.bilibili.com/video/BV1EG4y1c735)
- **湍流/紊流01-湍流基本性质，流体方程1**
  - [B station](https://www.bilibili.com/video/BV1JL411A7cE)
- **湍流/紊流02-流体方程2**
  - [B station](https://www.bilibili.com/video/BV1gZ4y187JR)
- **湍流/紊流03-统计描述1**
  - [B station](https://www.bilibili.com/video/BV1WB4y1y7Ub)
- **湍流/紊流04-统计描述2**
  - [B station](https://www.bilibili.com/video/BV1RA4y1f7jp)
- **湍流/紊流05-统计描述3**
  - [B station](https://www.bilibili.com/video/BV1j3411P7h8)
- **湍流/紊流06-统计描述4，湍流方程1**
  - [B station](https://www.bilibili.com/video/BV12t4y1x7o7)
- **湍流/紊流07-湍流方程2**
  - [B station](https://www.bilibili.com/video/BV1Zr4y1x7cV)
- **湍流/紊流08-湍流方程3，湍流尺度1**
  - [B station](https://www.bilibili.com/video/BV1cY411c7Cd)
- **湍流/紊流09-湍流尺度2**
  - [B station](https://www.bilibili.com/video/BV1wF411V74G)
- **湍流/紊流10-湍流尺度3**
  - [B station](https://www.bilibili.com/video/BV1kY4y1x7zc)
- **湍流/紊流11-湍流尺度4**
  - [B station](https://www.bilibili.com/video/BV1Fd4y1o7At)
- **湍流/紊流12-湍流尺度5**
  - [B station](https://www.bilibili.com/video/BV1US4y1s7Bg)
- **湍流/紊流13-湍流尺度6**
  - [B station](https://www.bilibili.com/video/BV1bB4y157nB)
- **拉普拉斯变换基础1**
  - [B station](https://www.bilibili.com/video/BV1rZ4y1o7j4)
- **拉普拉斯变换基础2**
  - [B station](https://www.bilibili.com/video/BV1Zr4y1b73G)
- **拉普拉斯变换基础3**
  - [B station](https://www.bilibili.com/video/BV1RW4y127C5)
- **拉普拉斯变换基础4**
  - [B station](https://www.bilibili.com/video/BV1Lr4y177ga)
- **【东方钢琴easy练习】永遠の巫女**
  - [B station](https://www.bilibili.com/video/BV1vK411p7X9)
- **【东方钢琴easy练习】遠野の森**
  - [B station](https://www.bilibili.com/video/BV1tA411i7u3)
- **【东方钢琴easy练习】妖々夢　～ Snow or Cherry Petal**
  - [B station](https://www.bilibili.com/video/BV1nv411q7Td)
- **【东方钢琴练习】春色小径 ～ Colorful Path（节选）**
  - [B station](https://www.bilibili.com/video/BV1Pq4y1g7Qr)
- **【东方钢琴easy练习】神は恵みの雨を降らす ～ Sylphid Dream**
  - [B station](https://www.bilibili.com/video/BV1FQ4y1P7ts)
- **英文非小说评鉴：《公正》**
  - [B station](https://www.bilibili.com/video/BV17K411V749)
- **英文非小说评鉴：《心流》**
  - [B station](https://www.bilibili.com/video/BV1G54y1r7b3)
- **多项式1：余式定理，因式定理**
  - [B station](https://www.bilibili.com/video/BV1VZ4y1u75m)
- **多项式2：多项式求根**
  - [B station](https://www.bilibili.com/video/BV1e54y1q72f)
- **多项式3：多项式求根，韦达定理**
  - [B station](https://www.bilibili.com/video/BV15f4y1R7qE)
- **愉快学习的5条建议**
  - [B station](https://www.bilibili.com/video/BV1Pt4y197ua)
- **如何在word中打公式？**
  - [B station](https://www.bilibili.com/video/BV1C4411q7LS)
- **The Willpower Instinct(《自控力》)精读-前言**
  - [B station](https://www.bilibili.com/video/BV1tb41127KK)
  - links: https://space.bilibili.com/14767534/channel/seriesdetail?sid=3063738 https://pan.baidu.com/s/1WH_hVXZ8IXNRfWvfsWZLpg
- **The Willpower Instinct(《自控力》)精读-第一章：什么是自控力**
  - [B station](https://www.bilibili.com/video/BV1pb411h7vY)
  - links: https://space.bilibili.com/14767534/channel/seriesdetail?sid=3063738 https://pan.baidu.com/s/1WH_hVXZ8IXNRfWvfsWZLpg
- **The Willpower Instinct(《自控力》)精读-第二章：自控力本能**
  - [B station](https://www.bilibili.com/video/BV1xb411v7tm)
  - links: https://space.bilibili.com/14767534/channel/seriesdetail?sid=3063738 https://pan.baidu.com/s/1WH_hVXZ8IXNRfWvfsWZLpg
- **The Willpower Instinct(《自控力》)精读-第三章：自控力好似肌肉**
  - [B station](https://www.bilibili.com/video/BV1wb411t7d3)
  - links: https://space.bilibili.com/14767534/channel/seriesdetail?sid=3063738 https://pan.baidu.com/s/1WH_hVXZ8IXNRfWvfsWZLpg
- **The Willpower Instinct(《自控力》)精读-第四章：“罪恶许可证”**
  - [B station](https://www.bilibili.com/video/BV1jb411L7TY)
  - links: https://space.bilibili.com/14767534/channel/seriesdetail?sid=3063738 https://pan.baidu.com/s/1WH_hVXZ8IXNRfWvfsWZLpg
- **The Willpower Instinct（《自控力》）精读第五章：欲望还是幸福？**
  - [B station](https://www.bilibili.com/video/BV114411Y7r7)
  - links: https://space.bilibili.com/14767534/channel/seriesdetail?sid=3063738 https://pan.baidu.com/s/1WH_hVXZ8IXNRfWvfsWZLpg
- **The Willpower Instinct（自控力）第六章：What the Hell效应**
  - [B station](https://www.bilibili.com/video/BV16J411A7Z4)
  - links: https://space.bilibili.com/14767534/channel/seriesdetail?sid=3063738 https://pan.baidu.com/s/1WH_hVXZ8IXNRfWvfsWZLpg
- **The Willpower Instinct（《自控力》）精读-第七章：卖未来**
  - [B station](https://www.bilibili.com/video/BV1EE411B7Cg)
  - links: https://space.bilibili.com/14767534/channel/detail?cid=66140
- **The Willpower Instinct（《自控力》）精读-第八章：自控力的感染性**
  - [B station](https://www.bilibili.com/video/BV1zJ411Q7UM)
  - links: https://space.bilibili.com/14767534/channel/detail?cid=66140
- **The Willpower Instinct（《自控力》）精读-第9、10章：“不要做”的局限性，结束语**
  - [B station](https://www.bilibili.com/video/BV1YJ411q7k1)
  - links: https://space.bilibili.com/14767534/channel/detail?cid=66140
- **1_老奶奶学算法---两数之和**
  - [B station](https://www.bilibili.com/video/BV1QeaP6EEiy)
- **2_老奶奶学算法---字母异位词分组**
  - [B station](https://www.bilibili.com/video/BV1oHhX6REKo)
- **3_老奶奶学算法---最长连续序列**
  - [B station](https://www.bilibili.com/video/BV1MBam6YE1E)
- **4_老奶奶学算法---哈希表大总结**
  - [B station](https://www.bilibili.com/video/BV1tram6aEFB)
- **1_老奶奶学python---认知新帮手**
  - [B station](https://www.bilibili.com/video/BV1m8uH6eEjE)
- **2_老奶奶学python---会装东西的纸箱**
  - [B station](https://www.bilibili.com/video/BV1dbu86TEpC)
- **3_老奶奶学python---会开口问的帮手**
  - [B station](https://www.bilibili.com/video/BV122u86REkY)
- **4_老奶奶学python---会拿主意的帮手**
  - [B station](https://www.bilibili.com/video/BV1WVu86EE7Q)
- **5_老奶奶学python---数一遍与干到收工**
  - [B station](https://www.bilibili.com/video/BV1AVu86EEzE)
- **6_老奶奶学python---货架装货**
  - [B station](https://www.bilibili.com/video/BV1AVu86EEX3)
- **7_老奶奶学python---纸条的更多招式**
  - [B station](https://www.bilibili.com/video/BV1AVu86EEBV)
- **8_老奶奶学python---小本本管货**
  - [B station](https://www.bilibili.com/video/BV1AVu86EEbZ)
- **9_老奶奶学python---总结课(一)：会装会想**
  - [B station](https://www.bilibili.com/video/BV1WVu86EEc8)
- **10_老奶奶学python---菜谱干货**
  - [B station](https://www.bilibili.com/video/BV1K3uu6FEYy)
- **11_老奶奶学python---模具做货**
  - [B station](https://www.bilibili.com/video/BV1x3uu6FEUd)
- **12_老奶奶学python---帮手摔倒也不慌**
  - [B station](https://www.bilibili.com/video/BV1x3uu6FEeK)
- **13_老奶奶学python---借领居家工具箱**
  - [B station](https://www.bilibili.com/video/BV11guu6fEiq)
- **14_老奶奶学python---记账本存档**
  - [B station](https://www.bilibili.com/video/BV11Xtm6JEq9)
- **15_老奶奶学python---大总结课：小帮手全能上岗**
  - [B station](https://www.bilibili.com/video/BV1CLuu6xEZ4)
- **最优化进阶---线性规划概述**
  - [B station](https://www.bilibili.com/video/BV1o5UEBvENP)
- **老奶奶学最优化---线性规划基础**
  - [B station](https://www.bilibili.com/video/BV1Cgg16bEPo)
- **老奶奶学最优化---单纯形法**
  - [B station](https://www.bilibili.com/video/BV1Rxge6UE9E)
- **老奶奶学最优化---对偶**
  - [B station](https://www.bilibili.com/video/BV19G3u6LEuW)
- **老奶奶学最优化---非单纯形法**
  - [B station](https://www.bilibili.com/video/BV1T33G6CETZ)
- **老奶奶学最优化---整数规划**
  - [B station](https://www.bilibili.com/video/BV1WT376QEwK)
- **写专利的周末**
  - [B station](https://www.bilibili.com/video/BV1kZZ6YBExR)
- **循环**
  - [B station](https://www.bilibili.com/video/BV19TVczCESR)
- **陈默的一天**
  - [B station](https://www.bilibili.com/video/BV1yAo7BYEK7)
- **最近工作**
  - [B station](https://www.bilibili.com/video/BV1BmLP6DEoX)
- **视觉主动跟随**
  - [B station](https://www.bilibili.com/video/BV1aKLT6jEgp)
- **轮臂视觉主动跟随（注意看机器人头）**
  - [B station](https://www.bilibili.com/video/BV1GPLT6mEw4)
- **移动星厨**
  - [B station](https://www.bilibili.com/video/BV1guLT65Etu)
- **手臂驱动**
  - [B station](https://www.bilibili.com/video/BV1gTLT61Ezi)
- **星厨一代**
  - [B station](https://www.bilibili.com/video/BV1VFLT6nEZf)
- **全部功能集成**
  - [B station](https://www.bilibili.com/video/BV15ZLK6QErr)
- **日常**
  - [B station](https://www.bilibili.com/video/BV1KgEc6cEC4)
- **每次付完款就弹出，利用人手抖、消费习惯，消费心理学开通，然后关闭又贼费劲。**
  - [B station](https://www.bilibili.com/video/BV1rWJu6jEZz)
- **vla 抓取和放置**
  - [B station](https://www.bilibili.com/video/BV1we7x6oE8S)
- **劝学**
  - [B station](https://www.bilibili.com/video/BV1EuNJ6iEQF)
- **自主作业**
  - [B station](https://www.bilibili.com/video/BV1ubN96DEdj)
- **《富爸爸穷爸爸》：财务状态分析图**
  - [B station](https://www.bilibili.com/video/BV14WrGBSEDM)
- **最优化基础---基本概念：凸优化、梯度、Jacobi矩阵、Hessian矩阵**
  - [B station](https://www.bilibili.com/video/BV19M4y1n7M3)
- **最优化基础---一维搜索(1)：暴力搜索法、区间消去法、黄金分割法和斐波那契法**
  - [B station](https://www.bilibili.com/video/BV1ku411b7iZ)
- **最优化基础---一维搜索(2)：二分法，牛顿法和割线法**
  - [B station](https://www.bilibili.com/video/BV1Vh4y1E77d)
- **最优化基础---一维搜索(3)：三点二次插值法**
  - [B station](https://www.bilibili.com/video/BV16M4y1x7B8)
- **最优化基础---非精确一维搜索：Armijo、Goldstein、Wolfe和强Wolfe条件；回溯法、内插公式和外插公式**
  - [B station](https://www.bilibili.com/video/BV11X4y1E7yd)
- **最优化基础---多维无约束优化方法(1)：方向导数和梯度、梯度下降法、最速下降法**
  - [B station](https://www.bilibili.com/video/BV1gu41177ZZ)
- **最优化基础---多维无约束优化方法(2)：牛顿法、Levenberg-Marquardt修正和高斯-牛顿法**
  - [B station](https://www.bilibili.com/video/BV1mN4y1X7cP)
- **最优化基础---多维无约束优化方法(3)：共轭向量及其性质、共轭方向法的基本原理、扩张子空间定理、共轭梯度法以及非二次型问题中的共轭梯度法**
  - [B station](https://www.bilibili.com/video/BV1xu411T7XW)
- **最优化基础---多维无约束优化方法(4)：拟牛顿法的引入、Hesse逆矩阵的近似、秩1修正公式、DFP算法和BFGS算法**
  - [B station](https://www.bilibili.com/video/BV1ki421S7GH)
- **非精确一维搜索octave代码实现**
  - [B station](https://www.bilibili.com/video/BV1Di421v7Qq)
- **最优化基础---求解线性方程组：概论、最小二乘法**
  - [B station](https://www.bilibili.com/video/BV1ow4m1e7QC)
- **最优化基础---求解线性方程组：递推最小二乘法**
  - [B station](https://www.bilibili.com/video/BV1tz42187hd)
- **最优化基础---求解线性方程组：最小范数解**
  - [B station](https://www.bilibili.com/video/BV1ff421q7v5)
- **最优化基础---求解线性方程组：Kaczmarz算法**
  - [B station](https://www.bilibili.com/video/BV1RmyXYoEF2)
- **最优化基础---求解线性方程组：一般意义下的方程组求解**
  - [B station](https://www.bilibili.com/video/BV1zS6pYuEHR)
- **一点点说明，2023年10月22日**
  - [B station](https://www.bilibili.com/video/BV1u34y1u7yU)
- **导数、梯度、雅可比矩阵、黑塞矩阵**
  - [B station](https://www.bilibili.com/video/BV1iF41117ek)
- **二分法、牛顿法、割线法**
  - [B station](https://www.bilibili.com/video/BV1T841167Gn)
- **暴力搜索法、区间消去法、黄金分割法、斐波拉契法**
  - [B station](https://www.bilibili.com/video/BV1g94y1z7zu)
- **三点二次插值法**
  - [B station](https://www.bilibili.com/video/BV1np4y1L7RM)
- **Armijo条件、Goldstein条件、Wolfe和强Wolfe条件**
  - [B station](https://www.bilibili.com/video/BV1AP411h7sY)
- **方向导数和梯度**
  - [B station](https://www.bilibili.com/video/BV1zj41147Ei)
- **牛顿法、LM修正和高斯牛顿法**
  - [B station](https://www.bilibili.com/video/BV1rw4m1S7bN)
- **共轭向量、扩张子空间定理和共轭梯度法**
  - [B station](https://www.bilibili.com/video/BV1m7421R7RA)
- **拟牛顿法、黑塞矩阵逆矩阵近似、秩1、DFP和BFGS算法**
  - [B station](https://www.bilibili.com/video/BV1Yy411z7Ei)
- **【01】AI Infra最详细Profile教程—vllm 实现及优化**
  - [B station](https://www.bilibili.com/video/BV16w316ZEyS)
- **【02】vLLM实战项目代码，可秋招可实习用**
  - [B station](https://www.bilibili.com/video/BV1keGP6UED9)
- **【03】vllm系列之torch.profiler与compile详解**
  - [B station](https://www.bilibili.com/video/BV1XhM96FEjH)
- **手撕vLLM系列[4]：从自回归一路讲到多卡并行，全程附带性能分析与理论讲解**
  - [B station](https://www.bilibili.com/video/BV1W2tn6zEjU)
- **手撕vLLM系列[5]: V0版本自回归推理概述**
  - [B station](https://www.bilibili.com/video/BV1kvtW6yEt8)
- **手撕vLLM系列【6】：手把手教你vLLM环境搭建**
  - [B station](https://www.bilibili.com/video/BV1Ebe36QEr3)
- **手撕vLLM系列【7】：RMSNorm代码实现**
  - [B station](https://www.bilibili.com/video/BV1QEek6fEeq)
- **手撕vLLM系列【8】：Rotary 公式详解**
  - [B station](https://www.bilibili.com/video/BV1She26TEeJ)
- **手撕vLLM系列【9】：RoPE 50行代码极简实现！**
  - [B station](https://www.bilibili.com/video/BV1eFe16zEBi)
- **手撕vLLM系列【10】：Activation激活函数完整实现**
  - [B station](https://www.bilibili.com/video/BV145e16FEBP)
- **手撕vLLM系列【11】：Attention 50行代码高效实现**
  - [B station](https://www.bilibili.com/video/BV16qeB6cEJn)
- **从零到一：像刷力扣一样手撕100个AI Infra的Kernel算子（CUDA+Triton+Pytorch）**
  - [B station](https://www.bilibili.com/video/BV1qhDXBzEbA)
  - links: https://dlog.com.cn https://leetgpu.com/challenges
- **AI Infra的招聘要求以及学习路线**
  - [B station](https://www.bilibili.com/video/BV1qKQGBtEDE)
- **手撕AI Infra算子系列3：极速环境配置，20分钟学会！包你完全0报错！**
  - [B station](https://www.bilibili.com/video/BV1VvQ3BSELZ)
  - links: https://dlog.com.cn
- **手撕AI Infra算子系列4：CUDA、Triton、Pytorch的前世今生**
  - [B station](https://www.bilibili.com/video/BV147dYBLEi4)
  - links: https://dlog.com.cn
- **手撕AI Infra算子系列5：element wise算子详解（CUDA、Triton、Pytorch）**
  - [B station](https://www.bilibili.com/video/BV1L6oNBSEGc)
  - links: https://dlog.com.cn
- **手撕AI Infra算子系列6：工业级Element Wise是如何实现的？Oneflow详解**
  - [B station](https://www.bilibili.com/video/BV1npovBCE1r)
  - links: https://dlog.com.cn https://github.com/xlite-dev/LeetCUDA https://github.com/Oneflow-Inc/oneflow
- **手撕AI Infra算子系列7：Matrix Addition详解。**
  - [B station](https://www.bilibili.com/video/BV1PvoeB2E2h)
  - links: https://dlog.com.cn
- **手撕AI Infra算子系列8：颜色反转；详解View与Offset**
  - [B station](https://www.bilibili.com/video/BV1ono6BJEnt)
- **手撕AI Infra算子系列9:Reduce的七种优化方法**
  - [B station](https://www.bilibili.com/video/BV1cJdPBHEK2)
  - links: https://dlog.com.cn
- **手撕AI Infra算子系列10：英伟达官方reduce实现详解**
  - [B station](https://www.bilibili.com/video/BV1wc5n6PEhQ)
  - links: https://dlog.com.cn
- **手撕AI Infra算子系列11：LeetGPU中的Reduce和Dot Product的代码实现**
  - [B station](https://www.bilibili.com/video/BV1FS536zELn)
  - links: https://dlog.com.cn
- **手撕AI Infra算子系列12：Softmax详解+原理+论文+N种优化方法**
  - [B station](https://www.bilibili.com/video/BV1tq5i69Epg)
  - links: https://www.dlog.com.cn
- **手撕AI Infra算子系列13：Scan算子详解+原理+代码+论文**
  - [B station](https://www.bilibili.com/video/BV1K2Gq6SEvQ)
  - links: https://dlog.com.cn
- **手撕AI Infra算子系列14：BatchNorm/LayerNorm/RMSNorm理论解析**
  - [B station](https://www.bilibili.com/video/BV1BKG76LEPM)
  - links: https://dlog.com.cn
- **手撕AI Infra算子系列15：Norm代码实现**
  - [B station](https://www.bilibili.com/video/BV1fP7j6xEtN)
  - links: https://github.com/ZiyuanDu/Awesome_AI_Infra_Learning/tree/main https://www.dlog.com.cn
- **手撕AI Infra算子系列16：矩阵乘法**
  - [B station](https://www.bilibili.com/video/BV1c77L6ZE5b)
  - links: https://github.com/ZiyuanDu/Awesome_AI_Infra_Learning/tree/main https://www.dlog.com.cn
- **手撕AI Infra算子系列18：别再背八股了！Transformer真的是一夜爆火吗？一文带你读懂Transformer的历史脉络！ALL才是论文的核心精华**
  - [B station](https://www.bilibili.com/video/BV195Y16KEcg)
- **北邮矩阵论期末复习——复习前的吐槽**
  - [B station](https://www.bilibili.com/video/BV1v8qaBkEy7)
  - links: https://pan.baidu.com/s/1Co61DdFqmlC51Z8GKWdlOw?pwd=vqmu
- **范数理论**
  - [B station](https://www.bilibili.com/video/BV1R8qaBkERy)
- **范数习题**
  - [B station](https://www.bilibili.com/video/BV1v8qaBkEUe)
- **线性空间习题**
  - [B station](https://www.bilibili.com/video/BV1njqrBVECz)
- **线性空间习题**
  - [B station](https://www.bilibili.com/video/BV1njqrBVE7C)
- **北邮矩阵论对角化和Jordan**
  - [B station](https://www.bilibili.com/video/BV1Z8BMBEEoW)
- **北邮矩阵论线性变换一**
  - [B station](https://www.bilibili.com/video/BV1B8BMBEEbV)
- **矩阵分析**
  - [B station](https://www.bilibili.com/video/BV1QivQBpEWe)
- **矩阵函数课后习题全讲**
  - [B station](https://www.bilibili.com/video/BV113v9B7EWj)
- **LDU分解**
  - [B station](https://www.bilibili.com/video/BV1SAv9BXEWE)
- **LU的Crout分解**
  - [B station](https://www.bilibili.com/video/BV1UAv9BXEfs)
- **QR分解——施密特法**
  - [B station](https://www.bilibili.com/video/BV1mKv9BDErD)
- **QR——Given变换**
  - [B station](https://www.bilibili.com/video/BV1rnv9B3Evg)
- **QR分解——H分解**
  - [B station](https://www.bilibili.com/video/BV13YicBjEYt)
- **满秩分解**
  - [B station](https://www.bilibili.com/video/BV1GhicBmEs1)
- **SVD分解**
  - [B station](https://www.bilibili.com/video/BV1TCicBzEJm)
- **广义逆1——投影变换**
  - [B station](https://www.bilibili.com/video/BV1MWifBBEJN)
- **广义逆矩阵求解**
  - [B station](https://www.bilibili.com/video/BV1tyiZBNEnd)
- **广义逆课后题**
  - [B station](https://www.bilibili.com/video/BV18ziZBBEbm)
- **欧式空间**
  - [B station](https://www.bilibili.com/video/BV1VbqTBTEQg)
- **欧式空间习题**
  - [B station](https://www.bilibili.com/video/BV1bdqKBfEsC)
- **考后碎碎念**
  - [B station](https://www.bilibili.com/video/BV1X8iyBTEw6)
- **重生之我学Rust**
  - [B station](https://www.bilibili.com/video/BV1ziDWYPEFQ)
  - links: https://github.com/doublesevenshop/RUST_DEMOs/tree/main/
- **进阶学ES 03-04 ES基于python API实践-2**
  - [B station](https://www.bilibili.com/video/BV12d4y1i7QU)
- **《ROS 2机器人开发从入门到实践》 1.4.1 Linux终端基础操作**
  - [B station](https://www.bilibili.com/video/BV1NE421w72J)
- **《ROS 2机器人开发从入门到实践》 1.4.2 在Linux中安装软件**
  - [B station](https://www.bilibili.com/video/BV1yr421M7ya)
- **《ROS 2机器人开发从入门到实践》 1.4.3 在Linux中编写Python代码**
  - [B station](https://www.bilibili.com/video/BV1vb421J7XZ)
- **《ROS 2机器人开发从入门到实践》 1.4.4 在Linux中编写C++代码**
  - [B station](https://www.bilibili.com/video/BV174421S73i)
- **《ROS 2机器人开发从入门到实践》8.2.2搭建规划器插件框架（上）**
  - [B station](https://www.bilibili.com/video/BV1AdzVYnErk)
- **《ROS 2机器人开发从入门到实践》8.2.2搭建规划器插件框架（下）**
  - [B station](https://www.bilibili.com/video/BV1EUB9YWERp)
- **《ROS 2机器人开发从入门到实践》8.2.3实现自定义规划算法**
  - [B station](https://www.bilibili.com/video/BV1jAzYYtEEH)
- **《ROS 2机器人开发从入门到实践》8.2.4配置导航参数并测试**
  - [B station](https://www.bilibili.com/video/BV1EHzpYvEQk)
- **《ROS 2机器人开发从入门到实践》8.3.1自定义控制介绍**
  - [B station](https://www.bilibili.com/video/BV1tb6FYsErH)
- **《ROS 2机器人开发从入门到实践》8.3.2搭建控制器插件框架**
  - [B station](https://www.bilibili.com/video/BV1HF6uYKEEH)
- **《ROS 2机器人开发从入门到实践》8.3.3实现自定义控制算法**
  - [B station](https://www.bilibili.com/video/BV1E8q5YgEo6)
- **《ROS 2机器人开发从入门到实践》8.3.4配置导航参数并测试**
  - [B station](https://www.bilibili.com/video/BV1qPqCYSEge)
- **《ROS 2机器人开发从入门到实践》第九章 搭建一个实体移动机器人**
  - [B station](https://www.bilibili.com/video/BV13AqZYmEs2)
- **《ROS 2机器人开发从入门到实践》9.0.1FishBot两轮差速机器人组装教程**
  - [B station](https://www.bilibili.com/video/BV17KkHYqEcZ)
- **《ROS 2机器人开发从入门到实践》9.0.2 FishBot配置助手介绍与安装**
  - [B station](https://www.bilibili.com/video/BV1MQkwYNEi4)
- **《ROS 2机器人开发从入门到实践》9.0.3. 主控板固件烧录与配置**
  - [B station](https://www.bilibili.com/video/BV1oAC5YJEdT)
- **《ROS 2机器人开发从入门到实践》9.0.4使用ROS2键盘控制FishBot**
  - [B station](https://www.bilibili.com/video/BV1PqkdY5Ew8)
- **《ROS 2机器人开发从入门到实践》9.0.5 雷达固件烧录及配置**
  - [B station](https://www.bilibili.com/video/BV1GH63YfEq2)
- **《ROS 2机器人开发从入门到实践》9.0.6雷达驱动及建图测试**
  - [B station](https://www.bilibili.com/video/BV1HH6HYzErB)
- **《ROS 2机器人开发从入门到实践》9.0.7 FishBot-Nav2导航测试**
  - [B station](https://www.bilibili.com/video/BV1ePrFYvEvQ)
- **《ROS 2机器人开发从入门到实践》9.1移动机器人系统设计**
  - [B station](https://www.bilibili.com/video/BV1NyFNeEEAh)
- **《ROS 2机器人开发从入门到实践》9.2.1开发平台介绍与安装**
  - [B station](https://www.bilibili.com/video/BV1pLf2YxEzv)
- **《ROS 2机器人开发从入门到实践》9.2.2 第一个HelloWorld工程**
  - [B station](https://www.bilibili.com/video/BV11cPXeoEfg)
- **《ROS 2机器人开发从入门到实践》9.2.3 使用代码点亮LED灯**
  - [B station](https://www.bilibili.com/video/BV1FTNpeKEbG)
- **《ROS 2机器人开发从入门到实践》9.2.4 使用超声波测量距离**
  - [B station](https://www.bilibili.com/video/BV18FNbeNEE5)
- **《ROS 2机器人开发从入门到实践》9.2.5 使用开源库驱动IMU**
  - [B station](https://www.bilibili.com/video/BV1LgN8ejEHG)
- **《ROS 2机器人开发从入门到实践》9.3.1 使用开源库驱动多路电机**
  - [B station](https://www.bilibili.com/video/BV1UiNmeHEe1)
- **《ROS 2机器人开发从入门到实践》9.3.2 电动机速度测量与转换**
  - [B station](https://www.bilibili.com/video/BV11ZNdeuEge)
- **《ROS 2机器人开发从入门到实践》9.3.3 使用PID控制轮子转速**
  - [B station](https://www.bilibili.com/video/BV137KPezEaH)
- **《ROS 2机器人开发从入门到实践》9.3.4 运动学正逆解的实现**
  - [B station](https://www.bilibili.com/video/BV1XwKTejE6V)
- **《ROS 2机器人开发从入门到实践》9.3.5 机器人里程计计算**
  - [B station](https://www.bilibili.com/video/BV1BJA5eTE9t)
- **《ROS 2机器人开发从入门到实践》9.4.1 第一个节点**
  - [B station](https://www.bilibili.com/video/BV1kQAqeCEE9)
- **《ROS 2机器人开发从入门到实践》9.4.2 订阅话题控制机器人**
  - [B station](https://www.bilibili.com/video/BV12rPue6EoY)
- **《ROS 2机器人开发从入门到实践》9.4.3  发布机器人里程计话题**
  - [B station](https://www.bilibili.com/video/BV15LPxeYEVp)
- **《ROS 2机器人开发从入门到实践》9.5.1  驱动并显示雷达点云**
  - [B station](https://www.bilibili.com/video/BV1JnPeewEQ5)
- **《ROS 2机器人开发从入门到实践》9.5.2 移动机器人的坐标系框架介绍**
  - [B station](https://www.bilibili.com/video/BV1QmP7eBEz2)
- **《ROS 2机器人开发从入门到实践》9.5.3 准备机器人URDF**
  - [B station](https://www.bilibili.com/video/BV1Fk9AYnEg2)
- **《ROS 2机器人开发从入门到实践》9.5.4 发布里程计TF**
  - [B station](https://www.bilibili.com/video/BV1Uq93YRE5T)
- **《ROS 2机器人开发从入门到实践》9.5.5 完成机器人建图并保存地图**
  - [B station](https://www.bilibili.com/video/BV1yVXXYbETt)
- **《ROS 2机器人开发从入门到实践》9.5.6 完成机器人导航**
  - [B station](https://www.bilibili.com/video/BV12L9hYrEkp)
- **《ROS 2机器人开发从入门到实践》10.1.1 QoS策略介绍**
  - [B station](https://www.bilibili.com/video/BV1EK9zYDE1s)
- **《ROS 2机器人开发从入门到实践》10.1.2 QoS的兼容性**
  - [B station](https://www.bilibili.com/video/BV1UH9ZYpEs6)
- **《ROS 2机器人开发从入门到实践》10.1.3 Python QoS兼容性测试**
  - [B station](https://www.bilibili.com/video/BV17ERKY4E5U)
- **《ROS 2机器人开发从入门到实践》10.1.4 C++ QoS兼容性测试**
  - [B station](https://www.bilibili.com/video/BV12m9mY9E8f)
- **《ROS 2机器人开发从入门到实践》10.2.1 执行器与回调组介绍**
  - [B station](https://www.bilibili.com/video/BV1ViRHYcEhj)
- **《ROS 2机器人开发从入门到实践》10.2.2 在Python中使用回调组**
  - [B station](https://www.bilibili.com/video/BV1sRRYY2Ecc)
- **《ROS 2机器人开发从入门到实践》10.2.3 在C++中使用回调组**
  - [B station](https://www.bilibili.com/video/BV17aR5YSE9G)
- **《ROS 2机器人开发从入门到实践》10.3.1 生命周期节点介绍**
  - [B station](https://www.bilibili.com/video/BV1pdQGYyEm5)
- **《ROS 2机器人开发从入门到实践》10.3.2 在Python中编写生命周期节点**
  - [B station](https://www.bilibili.com/video/BV1R1QnYWEB3)
- **《ROS 2机器人开发从入门到实践》10.3.3  在C++中编写生命周期节点**
  - [B station](https://www.bilibili.com/video/BV1CAQ6Y9EvF)
- **《ROS 2机器人开发从入门到实践》10.4.1 使用执行器组织多个节点**
  - [B station](https://www.bilibili.com/video/BV11SXTYTEtu)
- **《ROS 2机器人开发从入门到实践》10.4.2 使用组件运行组合节点**
  - [B station](https://www.bilibili.com/video/BV153QoYWEpn)
- **《ROS 2机器人开发从入门到实践》10.4.3 编写自己的组件**
  - [B station](https://www.bilibili.com/video/BV1BCX6YnEKL)
- **《ROS 2机器人开发从入门到实践》10.5.1 消息过滤器介绍**
  - [B station](https://www.bilibili.com/video/BV1bso2YaEDD)
- **《ROS 2机器人开发从入门到实践》10.5.2 在Python中同步传感器数据**
  - [B station](https://www.bilibili.com/video/BV12UoeY4EuQ)
- **《ROS 2机器人开发从入门到实践》10.5.3 在 C++中同步传感器数据**
  - [B station](https://www.bilibili.com/video/BV1nfoRY3E3t)
- **《ROS 2机器人开发从入门到实践》10.6.1 使用不同的DDS进行通信**
  - [B station](https://www.bilibili.com/video/BV1UXZHYFExy)
- **《ROS 2机器人开发从入门到实践》10.6.2 配置局域网通信**
  - [B station](https://www.bilibili.com/video/BV1BhfNYPEML)
- **《ROS 2机器人开发从入门到实践》10.6.3调整DDS配置**
  - [B station](https://www.bilibili.com/video/BV1bMR2YxExi)
- **《ROS 2机器人开发从入门到实践》10.6.4 使用DDS共享内存**
  - [B station](https://www.bilibili.com/video/BV1k5dNYPEdo)
- **【鱼香ROS】动手学ROS2|ROS2基础入门到实践教程|小鱼带你手把手学习ROS2**
  - [B station](https://www.bilibili.com/video/BV1gr4y1Q7j5)
- **【ROS2硬件控制】1.课程及开发平台介绍**
  - [B station](https://www.bilibili.com/video/BV1po4y1676Q)
- **【ROS2硬件控制】2.嵌入式开发从点灯开始**
  - [B station](https://www.bilibili.com/video/BV1UD4y1M745)
- **【ROS2硬件控制】3. 什么是单片机MCU，和CPU什么区别**
  - [B station](https://www.bilibili.com/video/BV1hg4y1t7af)
- **【ROS2硬件控制】4.细数-微处理器开发平台**
  - [B station](https://www.bilibili.com/video/BV1354y1M7HM)
- **【ROS2硬件控制】5. 搭建PlateFormIO开发环境**
  - [B station](https://www.bilibili.com/video/BV1mX4y1U762)
- **【ROS2硬件控制】6.PIO工程结构&构建方式**
  - [B station](https://www.bilibili.com/video/BV1QY411B71V)
- **【ROS2硬件控制】7.串口输出HelloWorld（上）**
  - [B station](https://www.bilibili.com/video/BV1nv4y1L7QJ)
- **【ROS2硬件控制】7.串口输出HelloWorld（下）**
  - [B station](https://www.bilibili.com/video/BV1yM4y1z73M)
- **【ROS2硬件控制】13B.6串口通信-接收实验**
  - [B station](https://www.bilibili.com/video/BV1xk4y1874q)
- **【ROS2硬件控制】13G.1 点灯基础-看懂LED驱动电路**
  - [B station](https://www.bilibili.com/video/BV1nv4y1L7G9)
- **【ROS2硬件控制】13G.2 完成点灯-GPIO控制**
  - [B station](https://www.bilibili.com/video/BV16m4y1k7xK)
- **【ROS2硬件控制】13G.3.学会使用按键-GPIO输入**
  - [B station](https://www.bilibili.com/video/BV11m4y167GK)
- **【ROS2硬件控制】13G.4.电池电压测量-学会使用ADC**
  - [B station](https://www.bilibili.com/video/BV1fm4y1B7Ur)
- **【ROS2硬件控制】13A.1.学会安装第三方开源库**
  - [B station](https://www.bilibili.com/video/BV17k4y1i7Dj)
- **【ROS2硬件控制】13A.2.使用开源库驱动IMU**
  - [B station](https://www.bilibili.com/video/BV1BL411S7vu)
- **【ROS2硬件控制】13A.3.学会面向对象编程-封装IMU驱动（上）**
  - [B station](https://www.bilibili.com/video/BV1Tc411W7jT)
- **【ROS2硬件控制】13A.3.学会面向对象编程-封装IMU驱动（下）**
  - [B station](https://www.bilibili.com/video/BV1mg4y1g7n6)
- **【ROS2硬件控制】13A.4.使用开源库驱动OLED**
  - [B station](https://www.bilibili.com/video/BV1FN411P7md)
- **【ROS2硬件控制】13A.5.通讯协议小课堂-I2C通信**
  - [B station](https://www.bilibili.com/video/BV1ov4y1p799)
- **【ROS2硬件控制】13A.6.I2C通信实验-点亮OLEDU**
  - [B station](https://www.bilibili.com/video/BV11j411w7W8)
- **【ROS2硬件控制】14.MicroROS入门与实践**
  - [B station](https://www.bilibili.com/video/BV15M4y1m7Rq)
- **【ROS2硬件控制】14B.1.Micro-ROS介绍与服务安装**
  - [B station](https://www.bilibili.com/video/BV16m4y1q7zC)
- **【ROS2硬件控制】14B.2.在单片机上编写ROS2节点**
  - [B station](https://www.bilibili.com/video/BV1gh411E7jU)
- **【ROS2硬件控制】14G.1.MicroROS话题订阅-控制LED**
  - [B station](https://www.bilibili.com/video/BV1sL411Y7NE)
- **【ROS2硬件控制】14G.2.ESP32上实现ROS-话题发布**
  - [B station](https://www.bilibili.com/video/BV1No4y1t7x3)
- **14G.3.ESP32上实现ROS-服务通信**
  - [B station](https://www.bilibili.com/video/BV17T411t7Ph)
- **14A.1.ESP32上实现ROS2自定义服务接口（上）**
  - [B station](https://www.bilibili.com/video/BV1nk4y1L7pz)