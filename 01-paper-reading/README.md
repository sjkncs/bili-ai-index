# AI 论文精读

> Source: **VALSE_Webinar, deep_thoughts, 读论文的麦小哲, 秋刀鱼的炼丹工坊, 同济子豪兄, 先进编译实验室, OpenMMLab** - Snapshot: **2026-10-12** - **1359** episodes.
> Data: [`items.json`](items.json)

## Data source / method / limits

**Data source**: `seasons_archives_list` for the episode list; `x/web-interface/view`
per video for its **`desc`** field.

**Method**: descriptions follow `[paper share] <full title> (<venue>) - <cn summary>`;
venue parsing is nesting-aware (handles `SE(3)` and nested conference parentheses).

**Limits**: the `paper` column comes from the **description**, because Bilibili
truncates video **titles** at 80 chars; missing venue/arXiv stays empty; index only.

## All 1359 episodes

| # | paper | venue | category | arXiv | length | B station |
|---:|---|---|---|---|---:|---|
| 1 | 1、PyTorch介绍与张量的创建 | - | AI 论文精读 | - | 42:00 | [link](https://www.bilibili.com/video/BV1ov411M7xL) |
| 2 | 2、PyTorch张量的运算API（上） | - | AI 论文精读 | - | 32:06 | [link](https://www.bilibili.com/video/BV1wQ4y1q7Bm) |
| 3 | 3、PyTorch张量的运算API（下） | - | AI 论文精读 | - | 48:16 | [link](https://www.bilibili.com/video/BV1Hq4y1R7dM) |
| 4 | 4、PyTorch的Dataset与DataLoader详细使用教程 | - | AI 论文精读 | - | 35:30 | [link](https://www.bilibili.com/video/BV1yP4y1L7cC) |
| 5 | 5、深入剖析PyTorch DataLoader源码 | - | AI 论文精读 | - | 42:30 | [link](https://www.bilibili.com/video/BV1kq4y1G75V) |
| 6 | 6、PyTorch中搭建分类网络实例 | - | AI 论文精读 | - | 43:50 | [link](https://www.bilibili.com/video/BV1VF411a7oz) |
| 7 | 7、深入剖析PyTorch nn.Module源码 | - | AI 论文精读 | - | 73:10 | [link](https://www.bilibili.com/video/BV1ch411b7yP) |
| 8 | 8、深入剖析PyTorch的state_dict、parameters、modules源码 | - | AI 论文精读 | - | 49:53 | [link](https://www.bilibili.com/video/BV12g411K7oq) |
| 9 | 9、深入剖析PyTorch的nn.Sequential及ModuleList源码 | - | AI 论文精读 | - | 46:14 | [link](https://www.bilibili.com/video/BV1Cb4y187H1) |
| 10 | 10、PyTorch autograd使用教程 | - | AI 论文精读 | - | 31:05 | [link](https://www.bilibili.com/video/BV1vL411u7bL) |
| 11 | 11、PyTorch中如何进行向量微分、矩阵微分与计算雅克比行列式 | - | AI 论文精读 | - | 33:12 | [link](https://www.bilibili.com/video/BV1Xr4y1r7wa) |
| 12 | 12、如何在PyTorch中训练模型 | - | AI 论文精读 | - | 37:33 | [link](https://www.bilibili.com/video/BV1wL411g7rv) |
| 13 | 13、详细推导自动微分Forward与Reverse模式 | - | AI 论文精读 | - | 54:08 | [link](https://www.bilibili.com/video/BV1PF411h7Ew) |
| 14 | 14、保存与加载PyTorch训练的模型和超参数 | - | AI 论文精读 | - | 37:50 | [link](https://www.bilibili.com/video/BV1U341187TM) |
| 15 | 15、Dropout原理以及其TF/Torch/Numpy源码实现 | - | AI 论文精读 | - | 45:45 | [link](https://www.bilibili.com/video/BV1gL4y1p7ww) |
| 16 | 16、PyTorch中进行卷积残差模块算子融合 | - | AI 论文精读 | - | 74:04 | [link](https://www.bilibili.com/video/BV1sU4y1u7TM) |
| 17 | 17、ConvMixer模型原理及其PyTorch逐行实现 | - | AI 论文精读 | - | 44:43 | [link](https://www.bilibili.com/video/BV1K34y1o74P) |
| 18 | 18、深入剖析PyTorch中的Transformer API源码 | - | AI 论文精读 | - | 67:40 | [link](https://www.bilibili.com/video/BV1o44y1Y7cp) |
| 19 | 19、Transformer模型Encoder原理精讲及其PyTorch逐行实现 | - | AI 论文精读 | - | 110:37 | [link](https://www.bilibili.com/video/BV1cP4y1V7GF) |
| 20 | 20、Transformer模型Decoder原理精讲及其PyTorch逐行实现 | - | AI 论文精读 | - | 59:13 | [link](https://www.bilibili.com/video/BV1Qg411N74v) |
| 21 | 21、Transformer Masked loss原理精讲及其PyTorch逐行实现 | - | AI 论文精读 | - | 45:54 | [link](https://www.bilibili.com/video/BV1dh411s7FW) |
| 22 | 22、PyTorch nn.Conv2d卷积网络使用教程 | - | AI 论文精读 | - | 33:34 | [link](https://www.bilibili.com/video/BV1644y1h7LN) |
| 23 | 23、手写并验证滑动相乘实现PyTorch二维卷积 | - | AI 论文精读 | - | 52:44 | [link](https://www.bilibili.com/video/BV1dP4y137er) |
| 24 | 24、手写并验证向量内积实现PyTorch二维卷积 | - | AI 论文精读 | - | 58:21 | [link](https://www.bilibili.com/video/BV1Qb4y1i7n5) |
| 25 | 25、手写实现nn.TransposedConv转置卷积 | - | AI 论文精读 | - | 52:18 | [link](https://www.bilibili.com/video/BV1fM4y1F7j5) |
| 26 | 26、手写卷积与转置卷积的代码总结 | - | AI 论文精读 | - | 41:48 | [link](https://www.bilibili.com/video/BV13U4y1K7op) |
| 27 | 27、手写实现PyTorch的DilatedConv和GroupConv | - | AI 论文精读 | - | 59:41 | [link](https://www.bilibili.com/video/BV1UY411W7W8) |
| 28 | 28、Vision Transformer(ViT)模型原理及PyTorch逐行实现 | - | AI 论文精读 | - | 67:26 | [link](https://www.bilibili.com/video/BV1cS4y1M7wo) |
| 29 | 29、PyTorch RNN的原理及其手写复现 | - | AI 论文精读 | - | 90:48 | [link](https://www.bilibili.com/video/BV13i4y1R7jB) |
| 30 | 30、PyTorch LSTM和LSTMP的原理及其手写复现 | - | AI 论文精读 | - | 76:29 | [link](https://www.bilibili.com/video/BV1zq4y1m7aH) |
| 31 | 31、PyTorch GRU的原理及其手写复现 | - | AI 论文精读 | - | 39:18 | [link](https://www.bilibili.com/video/BV1jm4y1Q7uh) |
| 32 | 32、基于PyTorch的文本分类项目模型与训练代码讲解 | - | AI 论文精读 | - | 55:10 | [link](https://www.bilibili.com/video/BV1eD4y1F7o4) |
| 33 | 33、完整讲解PyTorch多GPU分布式训练代码编写 | - | AI 论文精读 | - | 74:56 | [link](https://www.bilibili.com/video/BV1xZ4y1S7dG) |
| 34 | 34、Swin Transformer论文精讲及其PyTorch逐行复现 | - | AI 论文精读 | - | 98:20 | [link](https://www.bilibili.com/video/BV1kF411v7vg) |
| 35 | 35、基于PyTorch手写Attention-based Seq2Seq模型 | - | AI 论文精读 | - | 37:41 | [link](https://www.bilibili.com/video/BV1ML411w7k7) |
| 36 | 36、PyTorch训练加速技巧与爱因斯坦标示法 | - | AI 论文精读 | - | 65:52 | [link](https://www.bilibili.com/video/BV1ZY411b78A) |
| 37 | 37、Word Embedding原理精讲及其PyTorch API教程讲解 | - | AI 论文精读 | - | 49:54 | [link](https://www.bilibili.com/video/BV1wm4y1o7o5) |
| 38 | 38、ConvNeXt论文导读与模型精讲 | - | AI 论文精读 | - | 49:22 | [link](https://www.bilibili.com/video/BV1iP4y1M7nk) |
| 39 | 39、ConvNeXt模型代码逐行讲解 | - | AI 论文精读 | - | 33:12 | [link](https://www.bilibili.com/video/BV11Y41137VA) |
| 40 | 40、ConvNeXt分布式训练代码逐行讲解 | - | AI 论文精读 | - | 40:37 | [link](https://www.bilibili.com/video/BV1uP4y1u7qd) |
| 41 | 41、ResNet模型精讲以及PyTorch复现逐行讲解 | - | AI 论文精读 | - | 61:32 | [link](https://www.bilibili.com/video/BV1K3411p764) |
| 42 | 42、Masked AutoEncoder(MAE)论文导读与模型详细介绍 | - | AI 论文精读 | - | 62:41 | [link](https://www.bilibili.com/video/BV1u94y1f7NH) |
| 43 | 43、逐行讲解Masked AutoEncoder(MAE)的PyTorch代码 | - | AI 论文精读 | - | 110:32 | [link](https://www.bilibili.com/video/BV1JS4y1N7XE) |
| 44 | 44、Layer Normalization论文导读与原理精讲 | - | AI 论文精读 | - | 72:06 | [link](https://www.bilibili.com/video/BV1Ma411i76P) |
| 45 | 45、五种归一化的原理与PyTorch逐行手写实现讲解(BatchNorm/LayerNorm/InsNorm/GroupNorm/WeightNorm) | - | AI 论文精读 | - | 71:29 | [link](https://www.bilibili.com/video/BV1Pq4y1a7pH) |
| 46 | 46、四种Position Embedding的原理与PyTorch手写逐行实现（Transformer/ViT/Swin-T/MAE） | - | AI 论文精读 | - | 63:49 | [link](https://www.bilibili.com/video/BV1DF411u7ST) |
| 47 | 47、GAN原理讲解与PyTorch手写逐行讲解 | - | AI 论文精读 | - | 93:31 | [link](https://www.bilibili.com/video/BV1VT4y1e796) |
| 48 | 48、快速复现PyTorch的Weight Normalization | - | AI 论文精读 | - | 19:07 | [link](https://www.bilibili.com/video/BV1NZ4y117VT) |
| 49 | 49、cGAN及LSGAN的原理与PyTorch手写逐行讲解 | - | AI 论文精读 | - | 49:07 | [link](https://www.bilibili.com/video/BV1444y1G7y2) |
| 50 | 50、NormalizingFlow(标准化流)论文导读与原理精讲 | - | AI 论文精读 | - | 65:16 | [link](https://www.bilibili.com/video/BV1dS4y1c7xB) |
| 51 | 51、基于PyTorch ResNet18的果蔬分类逐行代码讲解 | - | AI 论文精读 | - | 68:13 | [link](https://www.bilibili.com/video/BV1vZ4y1h7X9) |
| 52 | 论文分享ICML 2026：RAG场景下的不确定性量化研究 | - | AI 论文精读 | - | 18:36 | [link](https://www.bilibili.com/video/BV1NPNY67EH4) |
| 53 | 论文分享OMAC：多智能体协作的整体优化框架 | - | AI 论文精读 | [2505.11765](https://arxiv.org/abs/2505.11765) | 21:03 | [link](https://www.bilibili.com/video/BV1JUK26mEcb) |
| 54 | 论文分享HetRL：异构环境下的大模型强化学习调度框架 | - | AI 论文精读 | [2607.12345](https://arxiv.org/abs/2607.12345) | 9:34 | [link](https://www.bilibili.com/video/BV1APMS6AEYR) |
| 55 | 论文分享SONAR：去中心化学习不是“连得越多越好” | - | AI 论文精读 | - | 11:31 | [link](https://www.bilibili.com/video/BV1DHuQ6HEch) |
| 56 | 论文分享BOOST：让低秩大模型在多GPU上真正跑快 | - | AI 论文精读 | [2512.12131](https://arxiv.org/abs/2512.12131) | 13:00 | [link](https://www.bilibili.com/video/BV1A4gJ6XEYs) |
| 57 | 论文分享OSWorld-Human：电脑使用智能体离“高效”还有多远 | - | AI 论文精读 | [2506.16042](https://arxiv.org/abs/2506.16042) | 18:35 | [link](https://www.bilibili.com/video/BV14bgA6jEqk) |
| 58 | 论文分享 Cocoon：相关噪声提升差分隐私训练精度，为什么系统成本却会暴涨 | - | AI 论文精读 | - | 21:28 | [link](https://www.bilibili.com/video/BV1dVhc63EzM) |
| 59 | 论文分享 CSLE：强化学习安全策略如何从模拟器走向真实网络系统 | - | AI 论文精读 | - | 23:34 | [link](https://www.bilibili.com/video/BV13Rt96VEnk) |
| 60 | 论文分享 FLoRIST：联邦 LoRA 如何兼顾精度、通信与异构客户端 | - | AI 论文精读 | [2506.09199](https://arxiv.org/abs/2506.09199) | 30:44 | [link](https://www.bilibili.com/video/BV1pwY46aExv) |
| 61 | 【VALSE2025】0606 顾实《APR：脑启发与认知计算》 | - | AI 论文精读 | - | 15:29 | [link](https://www.bilibili.com/video/BV1SGu4zaEeb) |
| 62 | 【VALSE2025】0606 叶茫《APR：大模型安全与伦理》 | - | AI 论文精读 | - | 15:36 | [link](https://www.bilibili.com/video/BV18Gu4zaEqp) |
| 63 | 【VALSE2025】0606 谢伟迪《APR：医疗通用大模型》 | - | AI 论文精读 | - | 17:10 | [link](https://www.bilibili.com/video/BV18Gu4zaEcj) |
| 64 | 【VALSE2025】0606 张兆翔《APR：世界模型理论与框架》 | - | AI 论文精读 | - | 17:47 | [link](https://www.bilibili.com/video/BV1YnuWzbEQi) |
| 65 | 【VALSE2025】0606 袁粒《APR：视频生成基础模型》 | - | AI 论文精读 | - | 16:20 | [link](https://www.bilibili.com/video/BV16NuWzzEJP) |
| 66 | 【VALSE2025】0606 俞扬《大会主旨报告：大模型背景下的强化学习》 | - | AI 论文精读 | - | 32:05 | [link](https://www.bilibili.com/video/BV1u2ptzNEHf) |
| 67 | 【VALSE2025】0606 白翔《大会主旨报告：迈向通用文字识别：文档智能模型的进展与趋势》 | - | AI 论文精读 | - | 32:09 | [link](https://www.bilibili.com/video/BV1PUpWz7EDh) |
| 68 | 【VALSE2025】0606 程明明《大会主旨报告：高效视觉感知与个性化生成》 | - | AI 论文精读 | - | 23:24 | [link](https://www.bilibili.com/video/BV1fZpWzgEQz) |
| 69 | 【VALSE2025】0608 马月昕《Workshop5：大场景多对象的重建与生成》 | - | AI 论文精读 | - | 32:31 | [link](https://www.bilibili.com/video/BV1ha4qzgEsh) |
| 70 | 【VALSE2025】0608 王程《Workshop5：大场景多对象的重建与生成》 | - | AI 论文精读 | - | 23:25 | [link](https://www.bilibili.com/video/BV18a4qzgEQg) |
| 71 | 【VALSE2025】0608 窦志扬《Workshop20：优秀学生论坛》 | - | AI 论文精读 | - | 12:38 | [link](https://www.bilibili.com/video/BV1ab4qzGEZf) |
| 72 | 【VALSE2025】0608 黄文柯《Workshop20：优秀学生论坛》 | - | AI 论文精读 | - | 9:13 | [link](https://www.bilibili.com/video/BV1Xb4qzGE4Z) |
| 73 | 【VALSE2025】0608 卫雅珂《Workshop20：优秀学生论坛》 | - | AI 论文精读 | - | 6:48 | [link](https://www.bilibili.com/video/BV16V4qzpEL7) |
| 74 | 【VALSE2025】0608 倪旻恒《Workshop20：优秀学生论坛》 | - | AI 论文精读 | - | 8:34 | [link](https://www.bilibili.com/video/BV16V4qzpEJF) |
| 75 | 【VALSE2025】0608 王健伊《Workshop20：优秀学生论坛》 | - | AI 论文精读 | - | 9:13 | [link](https://www.bilibili.com/video/BV1FV4qzWEed) |
| 76 | 【VALSE2025】0608 刘世隆《Workshop20：优秀学生论坛》 | - | AI 论文精读 | - | 4:50 | [link](https://www.bilibili.com/video/BV1FV4qzWECs) |
| 77 | 【VALSE2025】0608 刘欣鹏《Workshop20：优秀学生论坛》 | - | AI 论文精读 | - | 9:01 | [link](https://www.bilibili.com/video/BV1FV4qzWESa) |
| 78 | 【VALSE2025】0608 陈科研《Workshop20：优秀学生论坛》 | - | AI 论文精读 | - | 4:35 | [link](https://www.bilibili.com/video/BV1nV4qzWEju) |
| 79 | 【VALSE2025】0608 姚江超《Tutorial 4：可信机器学习》 | - | AI 论文精读 | - | 60:48 | [link](https://www.bilibili.com/video/BV12E4mzfEpb) |
| 80 | 【VALSE2025】0608 张杰《Tutorial 4：可信机器学习》 | - | AI 论文精读 | - | 66:58 | [link](https://www.bilibili.com/video/BV1KJ4mzFECJ) |
| 81 | 【VALSE2025】0608 韩波《Tutorial 4：可信机器学习》 | - | AI 论文精读 | - | 69:48 | [link](https://www.bilibili.com/video/BV1RP4mzgE3d) |
| 82 | 【VALSE2025】0608 张严浩《Workshop6：视觉通用模型》 | - | AI 论文精读 | - | 14:02 | [link](https://www.bilibili.com/video/BV1tsn2zLEch) |
| 83 | 【VALSE2025】0608 王栋《Workshop6：视觉通用模型》 | - | AI 论文精读 | - | 22:26 | [link](https://www.bilibili.com/video/BV1Txn2zyEPb) |
| 84 | 【VALSE2025】0608 王兴刚《Workshop6：视觉通用模型》 | - | AI 论文精读 | - | 35:50 | [link](https://www.bilibili.com/video/BV1dun2zsEKg) |
| 85 | 【VALSE2025】0608 代季峰《Workshop6：视觉通用模型》 | - | AI 论文精读 | - | 24:27 | [link](https://www.bilibili.com/video/BV1QLn2znEth) |
| 86 | 【VALSE2025】0608 陈隆《Workshop6：视觉通用模型》 | - | AI 论文精读 | - | 34:01 | [link](https://www.bilibili.com/video/BV1YRn2z9EYY) |
| 87 | 【VALSE2025】0607 谢琦《Tutorial3：深度学习网络架构设计》 | - | AI 论文精读 | - | 106:32 | [link](https://www.bilibili.com/video/BV1yMn1zTEej) |
| 88 | 【VALSE2025】0607 黄高《Tutorial3：深度学习网络架构设计》 | - | AI 论文精读 | - | 104:51 | [link](https://www.bilibili.com/video/BV1n7n1zcEhi) |
| 89 | 【VALSE2025】0607 董胤蓬《Workshop17：人工智能大模型安全》 | - | AI 论文精读 | - | 22:28 | [link](https://www.bilibili.com/video/BV1ENnqzTEeG) |
| 90 | 【VALSE2025】0607 周文柏《Workshop17：人工智能大模型安全》 | - | AI 论文精读 | - | 40:35 | [link](https://www.bilibili.com/video/BV1sDniz2EZs) |
| 91 | 【VALSE2025】0607 郭青《Workshop17：人工智能大模型安全》 | - | AI 论文精读 | - | 25:09 | [link](https://www.bilibili.com/video/BV1xDniz2Eem) |
| 92 | 【VALSE2025】0607 韦星星《Workshop17：人工智能大模型安全》 | - | AI 论文精读 | - | 24:09 | [link](https://www.bilibili.com/video/BV1N7Hcz7EHJ) |
| 93 | 【VALSE2025】0607 蔺琛皓《Workshop17：人工智能大模型安全》 | - | AI 论文精读 | - | 30:14 | [link](https://www.bilibili.com/video/BV1P7HczjEWZ) |
| 94 | 【VALSE2025】0607 王珂尧《Workshop17：人工智能大模型安全》 | - | AI 论文精读 | - | 8:08 | [link](https://www.bilibili.com/video/BV1N5HczEEaq) |
| 95 | 【VALSE2025】0607 朱翔昱《Workshop9：生物特征识别遇上AI+Science》 | - | AI 论文精读 | - | 50:07 | [link](https://www.bilibili.com/video/BV1gXn9zuEvZ) |
| 96 | 【VALSE2025】0607 刘宁《Workshop9：生物特征识别遇上AI+Science》 | - | AI 论文精读 | - | 32:38 | [link](https://www.bilibili.com/video/BV1nhn9zWEbT) |
| 97 | 【VALSE2025】0607 李晓白《Workshop9：生物特征识别遇上AI+Science》 | - | AI 论文精读 | - | 78:26 | [link](https://www.bilibili.com/video/BV1Hhn9zWEtV) |
| 98 | 【VALSE2025】0607 常乐《Workshop9：生物特征识别遇上AI+Science》 | - | AI 论文精读 | - | 34:10 | [link](https://www.bilibili.com/video/BV1Hbn9zREMC) |
| 99 | 【VALSE2025】0607 郑钰辉《Workshop1：多模态遥感通用模型》 | - | AI 论文精读 | - | 25:37 | [link](https://www.bilibili.com/video/BV15tnRzLE5o) |
| 100 | 【VALSE2025】0607 王正《Workshop7：多模态认知计算》 | - | AI 论文精读 | - | 36:46 | [link](https://www.bilibili.com/video/BV1vHnXzrE75) |
| 101 | 【VALSE2025】0607 沈为《Workshop7：多模态认知计算》 | - | AI 论文精读 | - | 29:02 | [link](https://www.bilibili.com/video/BV1RHnXz6EgJ) |
| 102 | 【VALSE2025】0607 魏云超《Workshop7：多模态认知计算》 | - | AI 论文精读 | - | 31:51 | [link](https://www.bilibili.com/video/BV1RHnXz6EGG) |
| 103 | 【VALSE2025】0607 张勇《Workshop7：多模态认知计算》 | - | AI 论文精读 | - | 10:21 | [link](https://www.bilibili.com/video/BV1LHnXzrEMP) |
| 104 | 【VALSE2025】0607 梁小丹《Workshop7：多模态认知计算》谢洪涛 | - | AI 论文精读 | - | 34:25 | [link](https://www.bilibili.com/video/BV1RHnXz6EFn) |
| 105 | 【VALSE2025】0607 梁小丹《Workshop7：多模态认知计算》 | - | AI 论文精读 | - | 26:38 | [link](https://www.bilibili.com/video/BV1eWnXzgEjc) |
| 106 | 【VALSE2025】0607 徐文超《Workshop7：多模态认知计算》 | - | AI 论文精读 | - | 25:31 | [link](https://www.bilibili.com/video/BV1ZonXz2EJU) |
| 107 | 【VALSE2025】0607 孙浩《Tutorial2：科学智能（AI for Science）》 | - | AI 论文精读 | - | 93:04 | [link](https://www.bilibili.com/video/BV1yKn3z6EQX) |
| 108 | 【VALSE2025】0607 陈键飞《Tutorial1：大模型基础理论结构与微调》 | - | AI 论文精读 | - | 116:36 | [link](https://www.bilibili.com/video/BV1q8n4zgECU) |
| 109 | 【VALSE2025】0607 岳翔宇《Workshop12：AI4Science，诺贝尔奖后的思考》 | - | AI 论文精读 | - | 31:35 | [link](https://www.bilibili.com/video/BV178n4zgE6U) |
| 110 | 【VALSE2025】0607 王笑楠《Workshop12：AI4Science，诺贝尔奖后的思考》 | - | AI 论文精读 | - | 29:51 | [link](https://www.bilibili.com/video/BV1Ndn4zpE8v) |
| 111 | 【VALSE2025】0607 王立威《Tutorial1：大模型基础理论结构与微调》 | - | AI 论文精读 | - | 69:59 | [link](https://www.bilibili.com/video/BV11dn4zHExR) |
| 112 | 【VALSE2025】0607 朱霖潮《Workshop12：AI4Science，诺贝尔奖后的思考》 | - | AI 论文精读 | - | 27:18 | [link](https://www.bilibili.com/video/BV1cNntzjEGy) |
| 113 | 【VALSE2025】0607 邵斌《Workshop12：AI4Science，诺贝尔奖后的思考》 | - | AI 论文精读 | - | 32:15 | [link](https://www.bilibili.com/video/BV1S2n4ztErt) |
| 114 | 【VALSE2025】0607 吴保东《Workshop12：AI4Science，诺贝尔奖后的思考》 | - | AI 论文精读 | - | 9:31 | [link](https://www.bilibili.com/video/BV1mSn4zxEbo) |
| 115 | 【VALSE2025】0607 张奇《Workshop13：大模型基础理论-从理论视角看待大模型技术发展》 | - | AI 论文精读 | - | 33:13 | [link](https://www.bilibili.com/video/BV1hNJRzTEcK) |
| 116 | 【VALSE2025】0607 方聪《Workshop13：大模型基础理论-从理论视角看待大模型技术发展》 | - | AI 论文精读 | - | 39:14 | [link](https://www.bilibili.com/video/BV18KJRziEL8) |
| 117 | 【VALSE2025】0607 黄维然《Workshop13：大模型基础理论-从理论视角看待大模型技术发展》 | - | AI 论文精读 | - | 36:34 | [link](https://www.bilibili.com/video/BV1uKJRziE1b) |
| 118 | 【VALSE2025】0607 龚铁梁《Workshop13：大模型基础理论-从理论视角看待大模型技术发展》 | - | AI 论文精读 | - | 28:04 | [link](https://www.bilibili.com/video/BV1hKJRziEPp) |
| 119 | 【VALSE2025】0607 蒋宁《Workshop13：大模型基础理论-从理论视角看待大模型技术发展》 | - | AI 论文精读 | - | 10:23 | [link](https://www.bilibili.com/video/BV1uKJRziEd5) |
| 120 | 【VALSE2025】0607 车万翔《Workshop13：大模型基础理论-从理论视角看待大模型技术发展》 | - | AI 论文精读 | - | 35:33 | [link](https://www.bilibili.com/video/BV1uKJRziEUa) |
| 121 | 【VALSE2025】0607 石野《Workshop10：基于生成式AI驱动的具身智能》 | - | AI 论文精读 | - | 41:03 | [link](https://www.bilibili.com/video/BV14XJCzvESS) |
| 122 | 【VALSE2025】0607 穆尧《Workshop10：基于生成式AI驱动的具身智能》 | - | AI 论文精读 | - | 36:10 | [link](https://www.bilibili.com/video/BV14XJCzvERJ) |
| 123 | 【VALSE2025】0607 盛律《Workshop10：基于生成式AI驱动的具身智能》 | - | AI 论文精读 | - | 33:24 | [link](https://www.bilibili.com/video/BV1h2JCzzEGd) |
| 124 | 【VALSE2025】0607 张直政《Workshop10：基于生成式AI驱动的具身智能》 | - | AI 论文精读 | - | 40:35 | [link](https://www.bilibili.com/video/BV182JCzzE4V) |
| 125 | 【VALSE2023】0610 高文《特征编码与数字视网膜》 | - | AI 论文精读 | - | 39:11 | [link](https://www.bilibili.com/video/BV1iV411579w) |
| 126 | 【VALSE2023】0610 陈熙霖 《计算机视觉-从孤立到系统性方法》 | - | AI 论文精读 | - | 27:26 | [link](https://www.bilibili.com/video/BV1n14y1B7x6) |
| 127 | 【VALSE2023】0610 吴建鑫《神经网络模型轻量化设计》 | - | AI 论文精读 | - | 15:03 | [link](https://www.bilibili.com/video/BV1Fu4y1174x) |
| 128 | 【VALSE2023】0610 刘烨斌《基于NeRF的三维视觉年度进展报告》 | - | AI 论文精读 | - | 13:54 | [link](https://www.bilibili.com/video/BV16x4y1X7WG) |
| 129 | 【VALSE2023】0610 张兆翔《类脑智能》 | - | AI 论文精读 | - | 15:41 | [link](https://www.bilibili.com/video/BV1Pk4y1G7zj) |
| 130 | 【VALSE2023】0610 夏勇《医学影像智能分析年度进展》 | - | AI 论文精读 | - | 15:19 | [link](https://www.bilibili.com/video/BV1Bj411r7Ex) |
| 131 | 【VALSE2023】0610 朱军《扩散概率模型的前沿进展》 | - | AI 论文精读 | - | 28:31 | [link](https://www.bilibili.com/video/BV1Rh4y1C7T7) |
| 132 | 【VALSE2023】0610 章国锋《基于隐式神经表示的三维重建、渲染与定位》 | - | AI 论文精读 | - | 25:10 | [link](https://www.bilibili.com/video/BV1H94y1C7mL) |
| 133 | 【VALSE2023】0610 刘偲《开放视觉感知》 | - | AI 论文精读 | - | 24:19 | [link](https://www.bilibili.com/video/BV1pM4y1p75v) |
| 134 | 【VALSE2023】0610 侯淇彬《开放域目标检测与识别年度进展》 | - | AI 论文精读 | - | 14:12 | [link](https://www.bilibili.com/video/BV1Yz4y1s7wC) |
| 135 | 【VALSE2023】0610 王利民《视频动作分析与识别》 | - | AI 论文精读 | - | 14:28 | [link](https://www.bilibili.com/video/BV1Uz4y1s76K) |
| 136 | 【VALSE2023】0610 胡瀚《视觉自监督学习年度进展评述》 | - | AI 论文精读 | - | 14:46 | [link](https://www.bilibili.com/video/BV1J44y1w79r) |
| 137 | 【VALSE2023】0610 程塨《遥感目标检测》 | - | AI 论文精读 | - | 12:44 | [link](https://www.bilibili.com/video/BV1D14y1i7wW) |
| 138 | 【VALSE2023】0610 邓伟洪《人脸感知计算年度进展报告》 | - | AI 论文精读 | - | 13:54 | [link](https://www.bilibili.com/video/BV12z4y1p7cr) |
| 139 | 【VALSE2023】0610 邓成/杨二昆《多模态融合感知年度进展综述》 | - | AI 论文精读 | - | 15:11 | [link](https://www.bilibili.com/video/BV1YP411t73r) |
| 140 | 【VALSE2023】0610 魏哲巍《图表示学习》 | - | AI 论文精读 | - | 13:04 | [link](https://www.bilibili.com/video/BV1244y1w7YT) |
| 141 | 【VALSE2023】0610 刘成林《文档智能：最新进展与趋势》 | - | AI 论文精读 | - | 15:14 | [link](https://www.bilibili.com/video/BV1FV4y1v7W6) |
| 142 | 【VALSE2023】0611 吴思《Tutorial ：计算神经科学-上》 | - | AI 论文精读 | - | 77:36 | [link](https://www.bilibili.com/video/BV1dj411r73d) |
| 143 | 【VALSE2023】0611 吴思《Tutorial ：计算神经科学-下》 | - | AI 论文精读 | - | 96:12 | [link](https://www.bilibili.com/video/BV1fu411J7jb) |
| 144 | 【VALSE2023】0611《Workshop：目标检测与分割-上》 | - | AI 论文精读 | - | 52:17 | [link](https://www.bilibili.com/video/BV1N8411o72f) |
| 145 | 【VALSE2023】0611《Workshop：目标检测与分割-下》 | - | AI 论文精读 | - | 115:20 | [link](https://www.bilibili.com/video/BV1fX4y177r8) |
| 146 | 【VALSE2023】0611《Workshop ：视觉知识和多重知识表达》 | - | AI 论文精读 | - | 106:37 | [link](https://www.bilibili.com/video/BV1dh4y1r7nX) |
| 147 | 【VALSE2023】0611《Workshop ：围绕手机的计算影像学》 | - | AI 论文精读 | - | 164:59 | [link](https://www.bilibili.com/video/BV1j94y1y76C) |
| 148 | 【VALSE2023】0611《Workshop ：机器人具身智能》 | - | AI 论文精读 | - | 115:38 | [link](https://www.bilibili.com/video/BV1L8411R7f7) |
| 149 | 【VALSE2023】0611《Tutorial：从Transformer到GPT》 | - | AI 论文精读 | - | 204:49 | [link](https://www.bilibili.com/video/BV1AV4y1v7xw) |
| 150 | 【VALSE2023】0611《Workshop：混合现实中的视觉与学习技术》 | - | AI 论文精读 | - | 169:57 | [link](https://www.bilibili.com/video/BV1Du4y1B7zE) |
| 151 | 【VALSE2023】0611《Workshop：物联网与工业应用》 | - | AI 论文精读 | - | 161:56 | [link](https://www.bilibili.com/video/BV16u4y1R7aJ) |
| 152 | 【VALSE2023】0611《Workshop ：女性研究者论坛》 | - | AI 论文精读 | - | 183:12 | [link](https://www.bilibili.com/video/BV1o14y1i7hs) |
| 153 | 【VALSE2023】0612《Workshop：多模态大模型与提示学习》 | - | AI 论文精读 | - | 152:49 | [link](https://www.bilibili.com/video/BV1WV41137is) |
| 154 | 【VALSE2023】0612《Workshop：三维视觉技术前沿》 | - | AI 论文精读 | - | 191:46 | [link](https://www.bilibili.com/video/BV1j44y1c7Yd) |
| 155 | 【VALSE2023】0612《Workshop：大模型背景下的自动驾驶与车路协同》 | - | AI 论文精读 | - | 170:22 | [link](https://www.bilibili.com/video/BV1nN41187mk) |
| 156 | 【VALSE2023】0612《Workshop：人工智能与科学计算》 | - | AI 论文精读 | - | 154:35 | [link](https://www.bilibili.com/video/BV1gF411Z7v2) |
| 157 | 【VALSE2023】0612《Workshop：语言文字识别与理解》 | - | AI 论文精读 | - | 194:34 | [link](https://www.bilibili.com/video/BV1LX4y1j7HM) |
| 158 | 【VALSE2023】0612《Workshop：自监督视觉表征学习》 | - | AI 论文精读 | - | 182:24 | [link](https://www.bilibili.com/video/BV1gm4y1p7yW) |
| 159 | 【VALSE2023】0612《Workshop：遥感影像解译》 | - | AI 论文精读 | - | 192:28 | [link](https://www.bilibili.com/video/BV1yu4y1R7f6) |
| 160 | 【VALSE2023】0612《Workshop：优秀学生论坛》 | - | AI 论文精读 | - | 109:21 | [link](https://www.bilibili.com/video/BV1pN41187Xf) |
| 161 | 【VALSE2023】0612《Workshop：多模态认知计算》 | - | AI 论文精读 | - | 208:59 | [link](https://www.bilibili.com/video/BV1bj411z7nD) |
| 162 | 【VALSE2023】0611《Workshop ：ChatGPT 与计算机视觉》 | - | AI 论文精读 | - | 104:06 | [link](https://www.bilibili.com/video/BV1m14y1v74v) |
| 163 | 【VALSE2023】0611《Workshop ：大模型对 CV/PR 的挑战与机会》 | - | AI 论文精读 | - | 127:40 | [link](https://www.bilibili.com/video/BV1C14y1v7CP) |
| 164 | 【VALSE2024】0507《Workshop ：多模态感知与对话》 | - | AI 论文精读 | - | 65:56 | [link](https://www.bilibili.com/video/BV1CU411o77f) |
| 165 | 【VALSE2024】0507《Workshop ：遥感图像智能解译论坛》 | - | AI 论文精读 | - | 205:09 | [link](https://www.bilibili.com/video/BV1D7421f7kx) |
| 166 | 【VALSE2024】0507《Workshop ：端到端自动驾驶》 | - | AI 论文精读 | - | 31:46 | [link](https://www.bilibili.com/video/BV13b421q7Vx) |
| 167 | 【VALSE2024】0507《Workshop ：多模态大模型》 | - | AI 论文精读 | - | 94:09 | [link](https://www.bilibili.com/video/BV11M4m1k7ba) |
| 168 | 【VALSE2024】0507《Workshop ：脑启发的视觉与学习》 | - | AI 论文精读 | - | 146:16 | [link](https://www.bilibili.com/video/BV1gb421q7hM) |
| 169 | 【VALSE2024】0507《Workshop ：优秀学生论坛》 | - | AI 论文精读 | - | 202:02 | [link](https://www.bilibili.com/video/BV1Cf421R7xc) |
| 170 | 【VALSE2024】0506《Tutorial：开放词汇视觉感知论坛》 | - | AI 论文精读 | - | 207:10 | [link](https://www.bilibili.com/video/BV1uf421d7Vk) |
| 171 | 【VALSE2024】0506《Workshop ：面向移动端的AI图像增强》 | - | AI 论文精读 | - | 218:48 | [link](https://www.bilibili.com/video/BV1gZ421x7fG) |
| 172 | 【VALSE2024】0506《Workshop ：三维重建与生成》 | - | AI 论文精读 | - | 204:51 | [link](https://www.bilibili.com/video/BV1DD421G7ws) |
| 173 | 【VALSE2024】0506《Workshop ：大模型赋能智慧医疗》 | - | AI 论文精读 | - | 235:16 | [link](https://www.bilibili.com/video/BV14r42157TN) |
| 174 | 【VALSE2024】0506《Workshop ：具身智能的视觉与学习》 | - | AI 论文精读 | - | 231:06 | [link](https://www.bilibili.com/video/BV1Bw4m1U7du) |
| 175 | 【VALSE2024】0506《Workshop ：大模型理论与机理》 | - | AI 论文精读 | - | 136:01 | [link](https://www.bilibili.com/video/BV19f421R7we) |
| 176 | 【VALSE2024】0506《Workshop ：视觉大模型高效迁移》 | - | AI 论文精读 | - | 141:27 | [link](https://www.bilibili.com/video/BV1EM4m1k7w6) |
| 177 | 【VALSE2024】0505 李鸿升《特邀报告：图像生成和视频生成若干前沿技术探索》 | - | AI 论文精读 | - | 26:21 | [link](https://www.bilibili.com/video/BV161421i7QW) |
| 178 | 【VALSE2024】0505 严骏驰《APR：世界模型增强的自动驾驶》 | - | AI 论文精读 | - | 16:35 | [link](https://www.bilibili.com/video/BV1FD421V7A1) |
| 179 | 【VALSE2024】0505 吴小俊《特邀报告：多模态视觉融合方法：是否存在性能极限？》 | - | AI 论文精读 | - | 31:57 | [link](https://www.bilibili.com/video/BV1Ft421T74U) |
| 180 | 【VALSE2024】0505 杨易《特邀报告：混合模型驱动的内容生成与具身智能》 | - | AI 论文精读 | - | 31:07 | [link](https://www.bilibili.com/video/BV1ss421w7eq) |
| 181 | 【VALSE2024】0505 施柏鑫《APR：神经形态相机视觉计算》 | - | AI 论文精读 | - | 18:10 | [link](https://www.bilibili.com/video/BV1Js42137CA) |
| 182 | 【VALSE2024】0505 杨耀东《APR：从偏好对齐到价值对齐与超对齐》 | - | AI 论文精读 | - | 21:06 | [link](https://www.bilibili.com/video/BV1Qi421U7yb) |
| 183 | 【VALSE2024】0505 王兴刚《APR：面向大模型的新型高效率网络架构》 | - | AI 论文精读 | - | 16:17 | [link](https://www.bilibili.com/video/BV1Gt421T7Z4) |
| 184 | 【VALSE2024】0505 俞扬《APR：世界模型与具身决策》 | - | AI 论文精读 | - | 16:40 | [link](https://www.bilibili.com/video/BV1aT421S7T5) |
| 185 | 【VALSE2024】0505 马月昕《特邀报告：三维场景理解的前世、今生与未来》 | - | AI 论文精读 | - | 31:22 | [link](https://www.bilibili.com/video/BV1Ff421d7n4) |
| 186 | 【VALSE2024】0505 卢志武《APR：视频生成》 | - | AI 论文精读 | - | 16:11 | [link](https://www.bilibili.com/video/BV1eZ421s794) |
| 187 | 【VALSE2024】0505 赵恒爽《APR：视觉基础大模型》 | - | AI 论文精读 | - | 21:23 | [link](https://www.bilibili.com/video/BV1Rf421R715) |
| 188 | 【VALSE2024】0505 林倞《APR：面向具身智能的多模态感知与交互》 | - | AI 论文精读 | - | 17:00 | [link](https://www.bilibili.com/video/BV1BZ421s7LD) |
| 189 | 【VALSE2024】0505 高林《APR：三维高斯泼溅（3D Gaussian Splatting）》 | - | AI 论文精读 | - | 18:21 | [link](https://www.bilibili.com/video/BV11r421j7tV) |
| 190 | 【VALSE2024】0505 谢凌曦《APR：视觉通用人工智能》 | - | AI 论文精读 | - | 16:54 | [link](https://www.bilibili.com/video/BV1mD421G7zJ) |
| 191 | 【VALSE2024】0505 代季峰《APR：智能体视觉》 | - | AI 论文精读 | - | 14:44 | [link](https://www.bilibili.com/video/BV1eM4m1k7jY) |
| 192 | 【VALSE2024】0505 陈华钧《APR：符号知识和大模型》 | - | AI 论文精读 | - | 16:05 | [link](https://www.bilibili.com/video/BV1Hz421Y7LG) |
| 193 | 【VALSE2024】0505《2023-2024年度CV与ML领域重要学术进展》 | - | AI 论文精读 | - | 15:27 | [link](https://www.bilibili.com/video/BV1ex4y1H7gC) |
| 194 | 【VALSE2024】0507《Workshop ：异构联邦学习》 | - | AI 论文精读 | - | 52:34 | [link](https://www.bilibili.com/video/BV1rD421G76t) |
| 195 | 52、Excel/Csv文件数据转成PyTorch张量导入模型代码逐行讲解 | - | AI 论文精读 | - | 26:29 | [link](https://www.bilibili.com/video/BV1nR4y1N7Vj) |
| 196 | 53、NormalizingFlow(标准化流)的PyTorch代码逐行讲解 | - | AI 论文精读 | - | 81:49 | [link](https://www.bilibili.com/video/BV1QF411j7ee) |
| 197 | 54、Probabilistic Diffusion Model概率扩散模型理论与完整PyTorch代码详细解读 | - | AI 论文精读 | - | 96:09 | [link](https://www.bilibili.com/video/BV1b541197HX) |
| 198 | 55、PyTorch的交叉熵、信息熵、二分类交叉熵、负对数似然、KL散度、余弦相似度的原理与代码讲解 | - | AI 论文精读 | - | 78:46 | [link](https://www.bilibili.com/video/BV1Sv4y1A7dz) |
| 199 | 56、U-Net用于图像分割以及人声伴奏分离原理代码讲解 | - | AI 论文精读 | - | 43:46 | [link](https://www.bilibili.com/video/BV1C54y1o77i) |
| 200 | 57、Autoregressive Diffusion Model自回归扩散模型用于序列预测论文讲解 | - | AI 论文精读 | - | 48:50 | [link](https://www.bilibili.com/video/BV1pZ4y1t7dc) |
| 201 | 58、Improved Diffusion的PyTorch代码逐行深入讲解 | - | AI 论文精读 | - | 146:58 | [link](https://www.bilibili.com/video/BV1sG411s7vV) |
| 202 | 59、基于CLIP/ViT模型搭建相似图像检索系统 | - | AI 论文精读 | - | 41:17 | [link](https://www.bilibili.com/video/BV1BB4y1a76V) |
| 203 | 60、基于cVAE+Flow+GAN的效果最好语音合成VITS模型论文精讲 | - | AI 论文精读 | - | 94:31 | [link](https://www.bilibili.com/video/BV1wU4y1q7po) |
| 204 | 61、基于cVAE+Flow+GAN的效果最好语音合成VITS模型代码逐行讲解 | - | AI 论文精读 | - | 195:46 | [link](https://www.bilibili.com/video/BV1VG411h75N) |
| 205 | 62、Score Diffusion Model分数扩散模型理论与完整PyTorch代码详细解读 | - | AI 论文精读 | - | 144:42 | [link](https://www.bilibili.com/video/BV1Dd4y1A7oz) |
| 206 | 63、必看！概率扩散模型(DDPM)与分数扩散模型(SMLD)的联系与区别 | - | AI 论文精读 | - | 46:36 | [link](https://www.bilibili.com/video/BV1QG4y1674Q) |
| 207 | 64、扩散模型加速采样算法DDIM论文精讲与PyTorch源码逐行解读 | - | AI 论文精读 | - | 129:54 | [link](https://www.bilibili.com/video/BV1JY4y1N7dn) |
| 208 | 65、【特别视频】AI教程评论区在线答疑之2022-10-25 | - | AI 论文精读 | - | 35:55 | [link](https://www.bilibili.com/video/BV1Wt4y1T7Nu) |
| 209 | 66、Classifier Guided Diffusion条件扩散模型论文与PyTorch代码详细解读 | - | AI 论文精读 | - | 90:27 | [link](https://www.bilibili.com/video/BV1m84y1e7hP) |
| 210 | 67、DiffusionLM 基于扩散模型的语言模型论文原理精讲 | - | AI 论文精读 | - | 56:30 | [link](https://www.bilibili.com/video/BV1zt4y1P7HN) |
| 211 | 68、VQVAE预训练模型的论文原理及PyTorch代码逐行讲解 | - | AI 论文精读 | - | 80:21 | [link](https://www.bilibili.com/video/BV14Y4y1X7wb) |
| 212 | 69、VQGAN+Transformer自回归建模图像生成的论文原理细致讲解 | - | AI 论文精读 | - | 66:53 | [link](https://www.bilibili.com/video/BV1mh411g7r5) |
| 213 | 70、VQGAN+GPT1自回归建模+采样部分的代码讲解 | - | AI 论文精读 | - | 51:16 | [link](https://www.bilibili.com/video/BV1uu4y1R7LV) |
| 214 | 71、VQGAN模型+VQ离散化模块的代码讲解 | - | AI 论文精读 | - | 50:34 | [link](https://www.bilibili.com/video/BV1cM411R7dY) |
| 215 | 72、爆火的GPT-2论文讲解 | - | AI 论文精读 | - | 50:32 | [link](https://www.bilibili.com/video/BV1Ma4y1R72i) |
| 216 | 73、爆火必看的nano-GPT2 Pytorch经典代码逐行讲解 | - | AI 论文精读 | - | 82:01 | [link](https://www.bilibili.com/video/BV11N4y1479K) |
| 217 | 74、GPT-3论文原理讲解 | - | AI 论文精读 | - | 53:18 | [link](https://www.bilibili.com/video/BV1CT4y1s7dx) |
| 218 | 75、Llama源码讲解之RoPE旋转位置编码 | - | AI 论文精读 | - | 26:05 | [link](https://www.bilibili.com/video/BV1Zr421c76A) |
| 219 | 76、Llama源码讲解之RMS-Norm | - | AI 论文精读 | - | 13:43 | [link](https://www.bilibili.com/video/BV1u1421k7rH) |
| 220 | 77、Llama源码讲解之GroupQueryAttention和KV-cache | - | AI 论文精读 | - | 21:14 | [link](https://www.bilibili.com/video/BV186421f7RL) |
| 221 | 78、Llama源码讲解之Transformer | - | AI 论文精读 | - | 17:48 | [link](https://www.bilibili.com/video/BV1mT421k7gB) |
| 222 | 79、Llama源码讲解之自回归采样生成算法 | - | AI 论文精读 | - | 21:02 | [link](https://www.bilibili.com/video/BV1Bi421Y7Lo) |
| 223 | 80、Byte Pair Encoding 源码逐行讲解 | - | AI 论文精读 | - | 47:45 | [link](https://www.bilibili.com/video/BV12x4y1t75q) |
| 224 | 81、LLaMA-1 论文导读 | - | AI 论文精读 | - | 36:34 | [link](https://www.bilibili.com/video/BV1Pb42177gr) |
| 225 | 82、LLaMA-2 论文导读 | - | AI 论文精读 | - | 55:27 | [link](https://www.bilibili.com/video/BV1Q4421Z7Zw) |
| 226 | 83、如何计算GPT模型的FLOPs及参数量 | - | AI 论文精读 | - | 39:59 | [link](https://www.bilibili.com/video/BV1iQsYeCEoe) |
| 227 | 84、GPT-4o/Moshi实时语音对话多模态算法讲解 | - | AI 论文精读 | - | 140:42 | [link](https://www.bilibili.com/video/BV1VQCUYyE6a) |
| 228 | 85、Differential Transformer 论文原理逐段讲解 | - | AI 论文精读 | - | 54:58 | [link](https://www.bilibili.com/video/BV1Jq1PYPEYG) |
| 229 | 【读评论】博士up主竟被粉丝要求女装？/ 10w粉丝成就奖牌开箱 | - | AI 论文精读 | - | 5:21 | [link](https://www.bilibili.com/video/BV1gF411G7tB) |
| 230 | 【十万粉丝福利】厦大博士一家三口齐跳”小鸡恰恰舞“ | - | AI 论文精读 | - | 1:01 | [link](https://www.bilibili.com/video/BV1tr4y1W7hq) |
| 231 | 【疫情下的厦大】中秋节傍晚的全员核酸检测 | - | AI 论文精读 | - | 2:14 | [link](https://www.bilibili.com/video/BV1TL4y187c5) |
| 232 | 博士必备发型？聊聊我从茂密的秀发到强者发型的华丽蜕变 | - | AI 论文精读 | - | 5:48 | [link](https://www.bilibili.com/video/BV1wL4y1878e) |
| 233 | 导师怒斥研究生【延毕警告】 | - | AI 论文精读 | - | 3:31 | [link](https://www.bilibili.com/video/BV17o4y1U7bF) |
| 234 | 读 研 冰 城 | - | AI 论文精读 | - | 1:19 | [link](https://www.bilibili.com/video/BV1Jq4y1s7dc) |
| 235 | 【万粉福利】博士夫妻羞耻挑战女团舞只为讨好粉丝？/ 你最最最重要 | - | AI 论文精读 | - | 1:28 | [link](https://www.bilibili.com/video/BV1HK411H73d) |
| 236 | 【我们领证啦】将故事写成我们，走过八年的校园爱情，终于在春暖花开的厦门，修成正果啦！ | - | AI 论文精读 | - | 6:32 | [link](https://www.bilibili.com/video/BV1ip4y1Q7c7) |
| 237 | 【厦大vlog】开学在即，博士学长带你逛厦大 / 中国最美大学 / 春暖花开的厦门大学 | - | AI 论文精读 | - | 4:43 | [link](https://www.bilibili.com/video/BV1MQ4y1N7Pb) |
| 238 | 【婚纱照Vlog】走过了八年的爱情，在春暖花开的厦门，我们拍婚纱照啦！！！！！ | - | AI 论文精读 | - | 4:41 | [link](https://www.bilibili.com/video/BV1ke411x7xj) |
| 239 | 【从两个少年到三口之家】你陪我长大，我陪你慢慢变老！ | - | AI 论文精读 | - | 4:25 | [link](https://www.bilibili.com/video/BV1fA4y1S7Re) |
| 240 | 【SPSS+AMOS实战教程-01】论文结构&模型构建&问卷设计 / 快速学会实证论文 / 保姆级教程 / 数据来源问卷网 | - | AI 论文精读 | - | 11:47 | [link](https://www.bilibili.com/video/BV1ED4y1m7B4) |
| 241 | 【SPSS+AMOS实战教程-02】信度&效度检验 / 快速学会实证论文 / 保姆级教程 / 数据来源问卷网 | - | AI 论文精读 | - | 12:57 | [link](https://www.bilibili.com/video/BV1eK411K7tD) |
| 242 | 【SPSS+AMOS实战教程-03】AMOS基本操作 / 快速学会实证论文 / 保姆级教程 / 数据来源问卷网 | - | AI 论文精读 | - | 10:12 | [link](https://www.bilibili.com/video/BV1ja4y1j7Th) |
| 243 | 【SPSS+AMOS实战教程-04】Amos拟合优度与假设检验 / 快速学会实证论文 / 保姆级教程 / 数据来源问卷网 | - | AI 论文精读 | - | 10:57 | [link](https://www.bilibili.com/video/BV18D4y197K3) |
| 244 | 【SPSS+AMOS实战教程-05】中介效应检验与AMOS操作 / 快速学会实证论文 / 保姆级教程 / 数据来源问卷网 | - | AI 论文精读 | - | 7:35 | [link](https://www.bilibili.com/video/BV1Wi4y177SC) |
| 245 | 【SPSS+AMOS实战教程-06】调节效应检验与AMOS操作 / 快速学会实证论文 / 保姆级教程 | - | AI 论文精读 | - | 13:26 | [link](https://www.bilibili.com/video/BV1Qp4y1t7pb) |
| 246 | 【5分钟学会SPSS】描述性统计与相关性分析 / 史上最易上手 / 快速学会实证论文 / 保姆级教程 | - | AI 论文精读 | - | 5:05 | [link](https://www.bilibili.com/video/BV1xL411x7AU) |
| 247 | 【5分钟学会SPSS】验证性因子分析与探索性因子分析 / 史上最易上手 / 快速学会实证论文 / 保姆级教程 | - | AI 论文精读 | - | 4:32 | [link](https://www.bilibili.com/video/BV1wf4y1w7zV) |
| 248 | 【5分钟学会SPSS】独立样本t检验和方差分析 / 史上最易上手 / 快速学会实证论文 / 保姆级教程 | - | AI 论文精读 | - | 5:07 | [link](https://www.bilibili.com/video/BV1GU4y1A76Z) |
| 249 | 【5分钟学会SPSS】多元线性回归分析 / 史上最易上手 / 快速学会实证论文 / 保姆级教程 | - | AI 论文精读 | - | 3:28 | [link](https://www.bilibili.com/video/BV1La411v7Ny) |
| 250 | 【读研必看】导师选的好，研究生毕业早！博士学长吐血分享 | - | AI 论文精读 | - | 8:35 | [link](https://www.bilibili.com/video/BV1hB4y1J7gv) |
| 251 | 【论文降重】希望每一个毕业季的同学都能刷到这个视频！ | - | AI 论文精读 | - | 7:05 | [link](https://www.bilibili.com/video/BV1t44y1G7BW) |
| 252 | 请大数据推给想要读博或正在读博的同学 | - | AI 论文精读 | - | 5:05 | [link](https://www.bilibili.com/video/BV1PL4y1L78q) |
| 253 | 学长实测论文查重工具，源文鉴真的有那么香吗？ | - | AI 论文精读 | - | 5:04 | [link](https://www.bilibili.com/video/BV1dq4y1a7Me) |
| 254 | 十个博士九个有退学的冲动？学长是如何熬过四年读博之路的… | - | AI 论文精读 | - | 6:55 | [link](https://www.bilibili.com/video/BV16L4y177Jf) |
| 255 | 学长实测不同价位论文查重工具，结果竟让我大呼离谱？ | - | AI 论文精读 | - | 7:06 | [link](https://www.bilibili.com/video/BV1j34y147TL) |
| 256 | 【毕业论文格式排版】本科研究生必看：章节标题样式/页眉页码设置/生成自定义目录/图表格式/参考文献交叉引用 | - | AI 论文精读 | - | 17:49 | [link](https://www.bilibili.com/video/BV1744y1N7ts) |
| 257 | 【研究生必备】选对了期刊，发表SCI/核心期刊不是梦！ | - | AI 论文精读 | - | 7:27 | [link](https://www.bilibili.com/video/BV11Q4y1B79Z) |
| 258 | 取消博士生发表论文要求？以后博士真的可以轻松毕业了么？ | - | AI 论文精读 | - | 5:53 | [link](https://www.bilibili.com/video/BV1k341117L3) |
| 259 | 【安利向】学长亲测最好用的论文写作工具 / 功能强大，高效实现文献阅读、笔记管理、文献引用 / 科研效率提高十倍 | - | AI 论文精读 | - | 5:54 | [link](https://www.bilibili.com/video/BV1Bv41137PG) |
| 260 | 【考博】联系导师如何写邮件？导师的回复什么含义？厦大博士学长的经验分享！ | - | AI 论文精读 | - | 7:10 | [link](https://www.bilibili.com/video/BV1wb4y1m7n4) |
| 261 | 【研究生必看】学生干部经历重要么？研究生要不要加入学生会、做班委？ | - | AI 论文精读 | - | 4:17 | [link](https://www.bilibili.com/video/BV18f4y1J7Tp) |
| 262 | 【干货】三步带你快速高效阅读学术文献 / 博士学长千篇阅读经验总结 / 保姆级教程 / 建议收藏 | - | AI 论文精读 | - | 6:24 | [link](https://www.bilibili.com/video/BV1qo4y1U7eh) |
| 263 | 【准研究生必看】做好这些准备，顺利完成从本科生到研究生的华丽蜕变！ | - | AI 论文精读 | - | 4:01 | [link](https://www.bilibili.com/video/BV1Fq4y1D73u) |
| 264 | 【干货】论文写作中的文献引用格式 / 如何引用文献 / 毕业论文写作必备 / 保姆级教程 / 建议收藏 | - | AI 论文精读 | - | 4:12 | [link](https://www.bilibili.com/video/BV1XU4y177pe) |
| 265 | 【研究生必备】史上最强文献检索攻略 / 三步带你查找下载到想要的最新文献 / 保姆级教程 一看就会 / 建议收藏 | - | AI 论文精读 | - | 6:25 | [link](https://www.bilibili.com/video/BV1mq4y1Q73y) |
| 266 | 【论文小白100问】引言和绪论的区别有哪些？该如何选择？ | - | AI 论文精读 | - | 4:13 | [link](https://www.bilibili.com/video/BV1Af4y1Y7FV) |
| 267 | 【从本科双非到985博士】这三个习惯，后悔没在大学就养成！/ 本科生、研究生必看 | - | AI 论文精读 | - | 11:54 | [link](https://www.bilibili.com/video/BV1av411j7Ek) |
| 268 | 【毕业答辩2】博士学长教你轻松应对答辩现场的老师提问！ / 答辩流程详解 / 汇报PPT / 现场提问回答策略 | - | AI 论文精读 | - | 7:35 | [link](https://www.bilibili.com/video/BV1X84y1F7f4) |
| 269 | 【毕业答辩】做好这些准备，毕业论文答辩轻松通过！/ 博士学长倾囊相授 / 答辩PPT制作 / 答辩必备问题 / 着装&物品准备 | - | AI 论文精读 | - | 8:34 | [link](https://www.bilibili.com/video/BV1mV411J7ov) |
| 270 | 【论文降重】巨实用！毕业论文降重方法 / 三大招式助力学术小白顺利毕业/ 保姆级教程 / 博士学长手把手带你毕业 | - | AI 论文精读 | - | 8:27 | [link](https://www.bilibili.com/video/BV1Py4y1s7h1) |
| 271 | 【研究生必看】论文投稿最强攻略 / 期刊审稿流程 / 论文投稿方式 | - | AI 论文精读 | - | 9:54 | [link](https://www.bilibili.com/video/BV1cv411E7dF) |
| 272 | 【干货】文献汇报这样做就对了！/ 导师满意同学爱听 / 研究生组会汇报 / 保姆级教程 / 建议收藏 | - | AI 论文精读 | - | 9:26 | [link](https://www.bilibili.com/video/BV1qB4y1w7q7) |
| 273 | 【研究生必看】英文不好如何写作SCI/SSCI英文论文 / 博士学长手把手带你写英文论文 / 保姆级教学 / 经验分享 / 建议收藏 | - | AI 论文精读 | - | 6:53 | [link](https://www.bilibili.com/video/BV16y4y1B7fU) |
| 274 | 考 博 必 看 指 南 ！博士如何考？如何准备？申请考核制是什么？直博和硕博连读？ | - | AI 论文精读 | - | 7:40 | [link](https://www.bilibili.com/video/BV1gy4y187qn) |
| 275 | 你真的适合读博士么？厦大博士学长经验分享适合读博的4大条件，快看看你都符合么？ | - | AI 论文精读 | - | 6:46 | [link](https://www.bilibili.com/video/BV1eK411J7cr) |
| 276 | 【超干货】建议收藏！论文选题怎么选？博士学长带你五分钟学会论文选题！！！ | - | AI 论文精读 | - | 4:45 | [link](https://www.bilibili.com/video/BV1ra4y1a78B) |
| 277 | 【干货】建议收藏 / 学术文献读什么？怎么读？/ 博士学长吐血分享/ 研究生必看 / 科研 / 论文心得 | - | AI 论文精读 | - | 6:35 | [link](https://www.bilibili.com/video/BV1xD4y1S7Wp) |
| 278 | 【选导师】被逼跳楼？被变态导师性侵？博士学长经验分享研究生导师一定要这样选！！！ | - | AI 论文精读 | - | 10:30 | [link](https://www.bilibili.com/video/BV12V411C7Tf) |
| 279 | 【论文拯救指南】干货！五分钟学会Endnote神器自动生成毕业论文参考文献引用格式，本科毕设和研究生小白进 | - | AI 论文精读 | - | 6:11 | [link](https://www.bilibili.com/video/BV1Qa4y1i7pA) |
| 280 | 【论文拯救指南】干货！厦大博士学长手把手带你写毕业论文开题报告，本科毕设和研究生小白进 | - | AI 论文精读 | - | 9:11 | [link](https://www.bilibili.com/video/BV1Tz4y1d7iZ) |
| 281 | 【论文拯救指南】厦大博士学长带你4句话搞定论文摘要，本科毕设和研究生小白进 | - | AI 论文精读 | - | 5:12 | [link](https://www.bilibili.com/video/BV1kz4y1R7ut) |
| 282 | 【论文拯救指南】干货！厦大博士学长手把手带你写文献综述，本科毕设和研究生小白进 | - | AI 论文精读 | - | 10:15 | [link](https://www.bilibili.com/video/BV1j64y1M76u) |
| 283 | 【干货】毕业论文云答辩？厦大博士学长分享线上答辩通关秘籍！大四、研三必看 | - | AI 论文精读 | - | 8:07 | [link](https://www.bilibili.com/video/BV1Bk4y1R7KJ) |
| 284 | 【论文拯救指南】干货！厦大博士学长手把手带你写论文引言，本科毕设和研究生小白进 | - | AI 论文精读 | - | 7:01 | [link](https://www.bilibili.com/video/BV1Z54y1X7wr) |
| 285 | 【干货推荐】这样学习Stata事半功倍，绝不会“一学就废”！ | - | AI 论文精读 | - | 3:26 | [link](https://www.bilibili.com/video/BV1pB4y117fn) |
| 286 | 【干货】搞懂论文逻辑结构，读文献思路清晰，写论文下笔如神！ | - | AI 论文精读 | - | 5:19 | [link](https://www.bilibili.com/video/BV1sB4y1j71x) |
| 287 | 【研究生学英语】听说读写，这样学英语就对了！ | - | AI 论文精读 | - | 8:47 | [link](https://www.bilibili.com/video/BV1AK411d7cD) |
| 288 | 【安利】能随意编辑文字和图片的PDF神器，你见过吗？ | - | AI 论文精读 | - | 3:19 | [link](https://www.bilibili.com/video/BV1X8411A7sn) |
| 289 | 学姐亲测火遍全网的ChatGPT能帮论文党做什么？/ 文献阅读 /文献查找/ 搭建提纲/ 论文撰写/ 技术支持 | - | AI 论文精读 | - | 3:35 | [link](https://www.bilibili.com/video/BV1QD4y1A7sZ) |
| 290 | 用ChatGPT写了篇本科论文，查重率竟然达到？！ | - | AI 论文精读 | - | 2:43 | [link](https://www.bilibili.com/video/BV15M4y1S7ah) |
| 291 | 【毕业论文】第一集：论文选题，好的开始是成功的一半 | - | AI 论文精读 | - | 4:39 | [link](https://www.bilibili.com/video/BV1X24y1b7RL) |
| 292 | 【麦小哲】开题报告实用攻略，毕业论文必备，手把手带你完成开题报告撰写 | - | AI 论文精读 | - | 7:32 | [link](https://www.bilibili.com/video/BV1Fz4y1w7Tq) |
| 293 | 【麦小哲】科研小白如何快速高效阅读文献？宝藏方法推荐，建议收藏 | - | AI 论文精读 | - | 5:26 | [link](https://www.bilibili.com/video/BV1kw411n7DL) |
| 294 | [论文简析]VAE: Auto-encoding Variational Bayes[1312.6114] | - | AI 论文精读 | - | 20:06 | [link](https://www.bilibili.com/video/BV1q64y1y7J2) |
| 295 | [论文简析]ViT: Vision Transformer[2010.11929] | - | AI 论文精读 | - | 15:22 | [link](https://www.bilibili.com/video/BV1di4y1N7pc) |
| 296 | [论文简析]How Do Vision Transformers Work?[2202.06709] | - | AI 论文精读 | - | 47:24 | [link](https://www.bilibili.com/video/BV1UF41147AG) |
| 297 | [论文简析]Swin Transformer: Hierarchical ViT using Shifted Windows[2103.14030] | - | AI 论文精读 | - | 9:09 | [link](https://www.bilibili.com/video/BV1e84y1F7Sc) |
| 298 | [论文简析]DETR: End-to-End Object Detection with Transfromers[2005.12872] | - | AI 论文精读 | - | 14:30 | [link](https://www.bilibili.com/video/BV1T64y1D7NY) |
| 299 | [论文简析]NeRF: Representing Scenes as Neural Radiance Fields...[2003.08934] | - | AI 论文精读 | - | 16:07 | [link](https://www.bilibili.com/video/BV1mV4y1M7TB) |
| 300 | [论文简析]Deep Unsupervised Learning using Nonequilibrium Thermodynamics[1503.03585] | - | AI 论文精读 | - | 47:02 | [link](https://www.bilibili.com/video/BV19v4y1C7De) |
| 301 | [论文速览]LoRA: Low-Rank Adaptation of Large Language Models[2106.09685] | - | AI 论文精读 | - | 5:17 | [link](https://www.bilibili.com/video/BV1wX4y1s7an) |
| 302 | [论文速览]Flamingo: a Visual Language Model for Few-Shot Learning[2204.14198] | - | AI 论文精读 | - | 7:47 | [link](https://www.bilibili.com/video/BV1pu411G7ce) |
| 303 | [论文简析]A Generalist Agent / Gato[2205.06175] | - | AI 论文精读 | - | 31:00 | [link](https://www.bilibili.com/video/BV1EK421k7Sy) |
| 304 | [论文简析]Does SSL Really Improve RL from Pixels?[2206.05266] | - | AI 论文精读 | - | 28:58 | [link](https://www.bilibili.com/video/BV1gM411r7wq) |
| 305 | [论文简析]Dreamer V2[2010.02193] | - | AI 论文精读 | - | 23:20 | [link](https://www.bilibili.com/video/BV15o4y1R7kT) |
| 306 | [论文简析]World Models[1803.10122] | - | AI 论文精读 | - | 13:40 | [link](https://www.bilibili.com/video/BV1oz4y117qk) |
| 307 | [论文简析]Transformers are Sample Efficient World Models[2209.00588] | - | AI 论文精读 | - | 10:34 | [link](https://www.bilibili.com/video/BV1i24y1Z78Q) |
| 308 | [论文简析]Reinforcement Learning with Augmented Data: RAD[2004.14990] | - | AI 论文精读 | - | 4:54 | [link](https://www.bilibili.com/video/BV1ZS4y1h77B) |
| 309 | [论文简析]CURL[2004.04136] | - | AI 论文精读 | - | 11:15 | [link](https://www.bilibili.com/video/BV14v411h7sq) |
| 310 | [论文简析]SPR: Data-Efficient RL with Self-Predictive Representations[2007.05929] | - | AI 论文精读 | - | 8:15 | [link](https://www.bilibili.com/video/BV1bN411Q7Hz) |
| 311 | [论文简析]DrQ: Data regularized Q[2004.13649] | - | AI 论文精读 | - | 10:44 | [link](https://www.bilibili.com/video/BV15p4y1h7Xu) |
| 312 | [论文简析]The Dormant Neuron Phenomenon in Deep Reinforcement Learning[2302.12902] | - | AI 论文精读 | - | 13:34 | [link](https://www.bilibili.com/video/BV1r94y1w7tE) |
| 313 | [论文简析]XSkill: Cross Embodiment Skill Discovery[2307.09955] | - | AI 论文精读 | - | 18:50 | [link](https://www.bilibili.com/video/BV1bj411L7yK) |
| 314 | [论文简析]Video Prediction Policy: A Generalist Robot Policy...[2412.14803] | - | AI 论文精读 | - | 10:25 | [link](https://www.bilibili.com/video/BV1hZugzdE4F) |
| 315 | [论文速览]Efficient Action Tokenization for Vision-Language-Action Model[2501.09747] | - | AI 论文精读 | - | 14:40 | [link](https://www.bilibili.com/video/BV1TuFpeKEXQ) |
| 316 | [论文简析]Rainbow:Combining Improvements in Deep Reinforcement Learning[1710.02298] | - | AI 论文精读 | - | 27:38 | [link](https://www.bilibili.com/video/BV1W64y1x7MF) |
| 317 | [论文简析]PPG: Phasic Policy Gradient[2009.04416] | - | AI 论文精读 | - | 7:47 | [link](https://www.bilibili.com/video/BV1uB4y1A7Ec) |
| 318 | [论文简析]SAC: Soft Actor-Critic Part 1[1801.01290] | - | AI 论文精读 | - | 42:28 | [link](https://www.bilibili.com/video/BV1YK4y1T7b6) |
| 319 | [论文简析]SAC: Soft Actor-Critic Part 2[1812.05905] | - | AI 论文精读 | - | 10:53 | [link](https://www.bilibili.com/video/BV13V411e7Qb) |
| 320 | [论文简析]C-Learning: Learning to .. via Recursive Classification[2011.08909] | - | AI 论文精读 | - | 24:27 | [link](https://www.bilibili.com/video/BV1J64y1S7ZA) |
| 321 | [论文简析]Time-Contrastive Networks:Self-Supervised Learning from Video[1704.06888] | - | AI 论文精读 | - | 13:03 | [link](https://www.bilibili.com/video/BV1Sr4y1A7bp) |
| 322 | [论文速览]Diffusion Policy: Visuomotor Policy Learning via Action Diff.[2303.04137] | - | AI 论文精读 | - | 5:50 | [link](https://www.bilibili.com/video/BV1Cu411Y7d7) |
| 323 | [论文速览]Decision Transformer: RL via Sequence Modeling[2106.01345] | - | AI 论文精读 | - | 5:11 | [link](https://www.bilibili.com/video/BV1zf4y1t7ka) |
| 324 | [论文简析]Visionary: Vision architecture discovery for robot learning[2103.14633] | - | AI 论文精读 | - | 10:31 | [link](https://www.bilibili.com/video/BV1oo4y1k7Jo) |
| 325 | [论文简析]Neuroevolution of Self-interpretable Agents[2003.08165] | - | AI 论文精读 | - | 13:32 | [link](https://www.bilibili.com/video/BV17Z4y1w7sX) |
| 326 | [论文简析]QT-Opt: Scalable Deep RL for Vision-Based Robotic Manipulation[1806.10293] | - | AI 论文精读 | - | 13:35 | [link](https://www.bilibili.com/video/BV1Ey4y187bi) |
| 327 | [论文速览]DDPG&TD3[1509.02971][1802.09477] | - | AI 论文精读 | - | 17:30 | [link](https://www.bilibili.com/video/BV1nU4y1u7h1) |
| 328 | [论文简析]SEER: Stored Embeddings for Efficient RL[2103.02886] | - | AI 论文精读 | - | 7:48 | [link](https://www.bilibili.com/video/BV1rv411h7iS) |
| 329 | [论文简析]BCO: Behavioral Cloning from Observation[1805.01954] | - | AI 论文精读 | - | 16:14 | [link](https://www.bilibili.com/video/BV1aN411X7YT) |
| 330 | [论文简析]A Framework for Efficient Robotic Manipulation[2012.07975] | - | AI 论文精读 | - | 5:33 | [link](https://www.bilibili.com/video/BV1pL4y1u7KG) |
| 331 | [论文速览]VRL3: A Data-Driven Framework for Visual Deep Reinforcement L.[2202.10324] | - | AI 论文精读 | - | 6:03 | [link](https://www.bilibili.com/video/BV1R841157aG) |
| 332 | [论文速览]Mask-based Latent Reconstruction for Reinforcement Learning[2201.12096] | - | AI 论文精读 | - | 5:10 | [link](https://www.bilibili.com/video/BV12v4y1z7BM) |
| 333 | [论文简析]Learning Invariant Representations for RL without Reconstructi[2006.10742] | - | AI 论文精读 | - | 15:29 | [link](https://www.bilibili.com/video/BV1EK4y1K7EL) |
| 334 | [论文简析]Stabilizing transformers for reinforcement learning[1910.06764] | - | AI 论文精读 | - | 13:57 | [link](https://www.bilibili.com/video/BV1Jf4y1s7ac) |
| 335 | [论文简析]Efficient Transformers in RL using Actor-Learner Distillation[2104.01655] | - | AI 论文精读 | - | 7:09 | [link](https://www.bilibili.com/video/BV1wZ4y1w7wP) |
| 336 | [论文速览]NeRF-RL: Reinforcement Learning with Neural Radiance Fields[2206.01634] | - | AI 论文精读 | - | 10:13 | [link](https://www.bilibili.com/video/BV1tG4y1V7hn) |
| 337 | [论文简析]DADS: Dynamics-Aware Unsupervised Discovery of Skills[1907.01657] | - | AI 论文精读 | - | 21:09 | [link](https://www.bilibili.com/video/BV165411w71J) |
| 338 | [论文简析]Off-DADS: Emergent Real-World Robotic Skills via off policy RL[2004.12974] | - | AI 论文精读 | - | 10:16 | [link](https://www.bilibili.com/video/BV18y4y1h7P9) |
| 339 | [论文速览]Stabilizing Deep Q-Learning with ConvNets and ViT...[2107.00644] | - | AI 论文精读 | - | 3:56 | [link](https://www.bilibili.com/video/BV12w411f74a) |
| 340 | [论文简析]Behavior From the Void: Unsupervised Active Pre-Training[2103.04551] | - | AI 论文精读 | - | 9:18 | [link](https://www.bilibili.com/video/BV1By4y1t7aK) |
| 341 | [论文速览]Self-Supervised Policy Adaptation during Deployment[2007.04309] | - | AI 论文精读 | - | 3:43 | [link](https://www.bilibili.com/video/BV1t54y1J7pd) |
| 342 | [论文简析]RL-CycleGAN: Reinforcement Learning Aware Simulation-To-Real[2006.09001] | - | AI 论文精读 | - | 13:58 | [link](https://www.bilibili.com/video/BV1L54y1n7d3) |
| 343 | [论文速览]Synthetic Experience Replay[2303.06614] | - | AI 论文精读 | - | 2:32 | [link](https://www.bilibili.com/video/BV1wx4y1P7hD) |
| 344 | [论文简析]Contrastive Language, Action, and State Pre-training...[2304.10782] | - | AI 论文精读 | - | 6:16 | [link](https://www.bilibili.com/video/BV1UF411U7zk) |
| 345 | [论文速览]Implicit Behavioral Cloning / IBC[2109.00137] | - | AI 论文精读 | - | 6:57 | [link](https://www.bilibili.com/video/BV18N411J7FD) |
| 346 | [论文夕拾]Diffusion Models for Robotics | - | AI 论文精读 | - | 7:41 | [link](https://www.bilibili.com/video/BV1mV411c7na) |
| 347 | [论文简析]Crossway Diffusion: Improving Diffusion-based ... via SSL[2307.01849] | - | AI 论文精读 | - | 9:41 | [link](https://www.bilibili.com/video/BV1Yp4y1F7nv) |
| 348 | [论文速览]A Self-Improving Generalist Agent for Robotic Manipulation[2306.11706] | - | AI 论文精读 | - | 12:12 | [link](https://www.bilibili.com/video/BV1cx4y1y7PZ) |
| 349 | [论文速览]OpenVLA: An Open-Source Vision-Language-Action Model[2406.09246] | - | AI 论文精读 | - | 5:31 | [link](https://www.bilibili.com/video/BV1m1421C7m7) |
| 350 | [论文速览]LLaRA: Supercharging Robot Learning Data for VLM Policy[2406.20095] | - | AI 论文精读 | - | 15:02 | [link](https://www.bilibili.com/video/BV174421D7tW) |
| 351 | [论文速览]GENIMA: Generative Image as Action Models[2407.07875] | - | AI 论文精读 | - | 6:20 | [link](https://www.bilibili.com/video/BV17S421971u) |
| 352 | [论文夕拾]Robot Manipulation in a Language Model Era | - | AI 论文精读 | - | 12:03 | [link](https://www.bilibili.com/video/BV1BdCFYmEpa) |
| 353 | [论文速览]Latent Action Pretraining from Videos[2410.11758] | - | AI 论文精读 | - | 6:41 | [link](https://www.bilibili.com/video/BV144KPeYE9v) |
| 354 | [论文速览]π_0: A Vision-Language-Action Flow Model for General Robot...[2410.24164] | - | AI 论文精读 | - | 25:11 | [link](https://www.bilibili.com/video/BV142uFzWEdY) |
| 355 | [论文简析]DreamVLA: A Vision-Language-Action Model Dreamed...[2507.04447] | - | AI 论文精读 | - | 9:12 | [link](https://www.bilibili.com/video/BV116utzwEZs) |
| 356 | [论文简析]Representation Learning with Contrastive Predictive Coding[1807.03748] | - | AI 论文精读 | - | 17:05 | [link](https://www.bilibili.com/video/BV1fK4y1o7A1) |
| 357 | [论文速览]Data-Efficient Image Recog with Contrastive Predictive Coding[1905.09272] | - | AI 论文精读 | - | 6:16 | [link](https://www.bilibili.com/video/BV1GU4y1H7b6) |
| 358 | [论文简析]SimCLR: A simple framework for contrastive learning[2002.05709] | - | AI 论文精读 | - | 3:12 | [link](https://www.bilibili.com/video/BV1Cp4y1b7ex) |
| 359 | [论文简析]SwAV: Swapping Assignments between multiple Views[2006.09882] | - | AI 论文精读 | - | 16:59 | [link](https://www.bilibili.com/video/BV1754y187Ki) |
| 360 | [论文简析]MoCo: Momentum Contrast Learning[1911.05722/2003.04297] | - | AI 论文精读 | - | 10:00 | [link](https://www.bilibili.com/video/BV1av411874e) |
| 361 | [论文简析]BYOL: Bootstrap Your Own Latent[2006.07733] | - | AI 论文精读 | - | 16:23 | [link](https://www.bilibili.com/video/BV1ki4y1T7X4) |
| 362 | [论文简析]DINO Emerging Properties in SelfSupervised Vision Transformers[2104.14294] | - | AI 论文精读 | - | 9:56 | [link](https://www.bilibili.com/video/BV1H54y157kj) |
| 363 | [论文简析]SimSiam: Exploring Simple Siamese Representation Learning[2011.10566] | - | AI 论文精读 | - | 9:16 | [link](https://www.bilibili.com/video/BV1Ah411Q7Lb) |
| 364 | [论文简析]Barlow Twins:Self-Supervised Learning via Redundancy Reduction[2103.03230] | - | AI 论文精读 | - | 5:47 | [link](https://www.bilibili.com/video/BV1gZ4y1P7U1) |
| 365 | [论文速览]iBOT: Image BERT Pre-Training with Online Tokenizer[2111.07832] | - | AI 论文精读 | - | 7:15 | [link](https://www.bilibili.com/video/BV1uM4y1q7Pa) |
| 366 | [论文简析]Evolving Losses for Unsupervised Video Representation Learning[2002.12177] | - | AI 论文精读 | - | 18:33 | [link](https://www.bilibili.com/video/BV1Pp4y1h7Ke) |
| 367 | [论文简析]Broaden Your Views for Self-Supervised Video Learning[2103.16559] | - | AI 论文精读 | - | 8:00 | [link](https://www.bilibili.com/video/BV1LQ4y1i7Zv) |
| 368 | [论文速览]Self-supervised Video Transformer[2112.01514] | - | AI 论文精读 | - | 7:09 | [link](https://www.bilibili.com/video/BV17Y4y1g7Jw) |
| 369 | [论文简析]Extreme Masking for Learning Instance and Distributed Visual..[2206.04667] | - | AI 论文精读 | - | 5:22 | [link](https://www.bilibili.com/video/BV1sY4y1G7St) |
| 370 | [论文简析]Learning by Aligning Videos in Time[2103.17260] | - | AI 论文精读 | - | 11:13 | [link](https://www.bilibili.com/video/BV13f4y1b7Nt) |
| 371 | [论文简析]Probabilistic Representations for Video Contrastive Learning[2204.03946] | - | AI 论文精读 | - | 14:47 | [link](https://www.bilibili.com/video/BV1RT4y1Y73n) |
| 372 | [论文简析]Propagate Yourself: Exploring Pixel-Level Consistency...[2011.10043] | - | AI 论文精读 | - | 7:37 | [link](https://www.bilibili.com/video/BV1hV411x7wL) |
| 373 | [论文简析]Location-Aware Self-Supervised Transformers for Semantic Seg.[2212.02400] | - | AI 论文精读 | - | 12:03 | [link](https://www.bilibili.com/video/BV1wk4y1i7eH) |
| 374 | [论文简析]Rethinking Pre-training and Self-training[2006.06882] | - | AI 论文精读 | - | 8:21 | [link](https://www.bilibili.com/video/BV1pK4y1U7ts) |
| 375 | [论文简析]Energy-Inspired Self-Supervised Pretraining for Vision Models[2302.01384] | - | AI 论文精读 | - | 11:08 | [link](https://www.bilibili.com/video/BV1hg4y1H7Gj) |
| 376 | [论文简析]Humble Teachers Teach Better Students for Semi-Supervised Object Detection | - | AI 论文精读 | - | 12:45 | [link](https://www.bilibili.com/video/BV1SK4y1u7ix) |
| 377 | [论文简析]Towards Better Understanding of Self-Supervised Representation[2203.01881] | - | AI 论文精读 | - | 7:46 | [link](https://www.bilibili.com/video/BV1fG411n7EC) |
| 378 | [论文简析]TransRank: SS Video...Ranking-based Transformation Recognition[2205.02028] | - | AI 论文精读 | - | 14:28 | [link](https://www.bilibili.com/video/BV1zS4y1e7uY) |
| 379 | [论文速览]Object Discovery and Representation Networks[2203.08777] | - | AI 论文精读 | - | 5:52 | [link](https://www.bilibili.com/video/BV1n34y1b7Uo) |
| 380 | [论文速览]Efficient Visual Pretraining with Contrastive Detection[2103.10957] | - | AI 论文精读 | - | 4:18 | [link](https://www.bilibili.com/video/BV1bY411n7BP) |
| 381 | [论文简析]Directional SSL for Heavy Image Augmentations[2110.13555] | - | AI 论文精读 | - | 6:31 | [link](https://www.bilibili.com/video/BV19U4y1o7SQ) |
| 382 | [论文速览]Invariant Information Clustering for Unsupervised Image...[1807.06653] | - | AI 论文精读 | - | 10:24 | [link](https://www.bilibili.com/video/BV1t34y1t72d) |
| 383 | [论文速览]Video Rep. Learning by Recognizing Temporal Transformations[2007.10730] | - | AI 论文精读 | - | 6:34 | [link](https://www.bilibili.com/video/BV1qU4y1X7cg) |
| 384 | [论文简析]β-VAE Learning basic visual concepts with a constrained variational... | - | AI 论文精读 | - | 12:50 | [link](https://www.bilibili.com/video/BV1644y1q7Aj) |
| 385 | [论文简析]DCLGAN/SimDCL: Dual Contrastive Learning[2104.07689] | - | AI 论文精读 | - | 6:01 | [link](https://www.bilibili.com/video/BV15v411j7N7) |
| 386 | [论文简析]Generative Scene Inference and Sampling...[1907.13052] | - | AI 论文精读 | - | 14:14 | [link](https://www.bilibili.com/video/BV1aZ4y1R7Ne) |
| 387 | [论文简析]An Empirical Study of Training Self-Supervised ViT[2104.02057] | - | AI 论文精读 | - | 8:58 | [link](https://www.bilibili.com/video/BV1UX4y1g7Dn) |
| 388 | [论文速览]Multi-Object ... with Iterative Variational Inference[1903.00450] | - | AI 论文精读 | - | 15:29 | [link](https://www.bilibili.com/video/BV15a41127C9) |
| 389 | [论文简析]MONet: Unsupervised Scene Decomposition and Representation[1901.11390] | - | AI 论文精读 | - | 13:43 | [link](https://www.bilibili.com/video/BV1CT4y1y7Hc) |
| 390 | [论文简析]Leveraging BG AUG to encourage semantic focus in SSCL[2103.12719] | - | AI 论文精读 | - | 4:34 | [link](https://www.bilibili.com/video/BV1xX4y1G7Pe) |
| 391 | [论文简析]Object-Centric Learning with Slot Attention[2006.15055] | - | AI 论文精读 | - | 9:18 | [link](https://www.bilibili.com/video/BV1QL4y1s7NK) |
| 392 | [论文简析]Equivariant Contrastive Learning[2111.00899] | - | AI 论文精读 | - | 10:02 | [link](https://www.bilibili.com/video/BV1jS4y1Z7Py) |
| 393 | [论文简析]Big Self-Supervised Models are Strong Semi-Supervised Learners[2006.10029] | - | AI 论文精读 | - | 7:04 | [link](https://www.bilibili.com/video/BV1Ey4y1t7zK) |
| 394 | [论文简析]Keeping Your Eye on the Ball: Trajectory Attention...[2106.05392] | - | AI 论文精读 | - | 19:43 | [link](https://www.bilibili.com/video/BV1j3411i7jU) |
| 395 | [论文简析]Wasserstein Contrastive Representation Distillation: WCoRD[2012.08674] | - | AI 论文精读 | - | 19:41 | [link](https://www.bilibili.com/video/BV1vw41197wC) |
| 396 | [论文速览]Masked Feature Prediction .Self-Supervised Visual Pre-Training[2112.09133] | - | AI 论文精读 | - | 5:17 | [link](https://www.bilibili.com/video/BV1YS4y1Q7Qj) |
| 397 | [论文速览]AugSelf: Improving Transferability...Augmentation-Aware..[2111.09613] | - | AI 论文精读 | - | 4:09 | [link](https://www.bilibili.com/video/BV1Ei4y1Z7Ld) |
| 398 | [论文速览]Nearest-Neighbor Contrastive Learning of Visual Representations[2104.14548 | - | AI 论文精读 | - | 5:34 | [link](https://www.bilibili.com/video/BV12f4y1M7Qq) |
| 399 | [论文速览]Solving Inefficiency of Self-supervised Representation Learning[2104.0876] | - | AI 论文精读 | - | 6:17 | [link](https://www.bilibili.com/video/BV1FL4y1z7jq) |
| 400 | [论文简析]VideoMoCo: ...Temporally Adversarial Examples[2103.05905] | - | AI 论文精读 | - | 6:43 | [link](https://www.bilibili.com/video/BV13f4y137Wc) |
| 401 | [论文速览]Theia: Distilling Diverse Vision Foundation Models for Robot..[2407.20179] | - | AI 论文精读 | - | 8:04 | [link](https://www.bilibili.com/video/BV18W42197So) |
| 402 | [论文速览]Long Short View Feature Decomposition via Contrastive Video...[2109.11593] | - | AI 论文精读 | - | 6:09 | [link](https://www.bilibili.com/video/BV1pQ4y1Q74S) |
| 403 | [论文简析]Vi2CLR: Video and Image for Visual Contrastive Learning of Representation | - | AI 论文精读 | - | 9:12 | [link](https://www.bilibili.com/video/BV1ZQ4y1i7Wa) |
| 404 | [论文速览]Generative Modeling by Estimating Gradients of the Data Dist[1907.05600] | - | AI 论文精读 | - | 17:52 | [link](https://www.bilibili.com/video/BV1WY4y1Q7fy) |
| 405 | [论文简析]Unsupervised Learning of Object Keypoints for Perception..[1906.11883] | - | AI 论文精读 | - | 11:17 | [link](https://www.bilibili.com/video/BV15w411R7rB) |
| 406 | [论文简析]Progressive Stage-wise Learning for Unsupervised Feature.. [2106.05554] | - | AI 论文精读 | - | 7:39 | [link](https://www.bilibili.com/video/BV1Fq4y1p7Ai) |
| 407 | [论文简析]Transf. Meta-learners for Implicit Neural Representations[2208.02801] | - | AI 论文精读 | - | 9:59 | [link](https://www.bilibili.com/video/BV1QV4y167S7) |
| 408 | [论文速览]Jigsaw Clustering for Unsupervised Visual Representation Learn[2104.00323] | - | AI 论文精读 | - | 5:32 | [link](https://www.bilibili.com/video/BV1Jg41177uE) |
| 409 | [论文速览]SS Video Representation Learning by Context&Motion Decoupling[2104.00862] | - | AI 论文精读 | - | 8:28 | [link](https://www.bilibili.com/video/BV1qf4y157DW) |
| 410 | [论文简析]MixMAE & Mixed AE[2205.13137][2303.17152] | - | AI 论文精读 | - | 14:16 | [link](https://www.bilibili.com/video/BV1cF411d77x) |
| 411 | [论文速览]Finite Scalar Quantization: VQ-VAE Made Simple[2309.15505] | - | AI 论文精读 | - | 5:26 | [link](https://www.bilibili.com/video/BV1N84y1S779) |
| 412 | [论文简析]DropPos: Pre-Training ViTs by Reconstructing Dropped Positions[2309.03576] | - | AI 论文精读 | - | 6:22 | [link](https://www.bilibili.com/video/BV1fu411u77K) |
| 413 | [论文速览]SODA: Bottleneck Diffusion Models for Representation Learning[2311.17901] | - | AI 论文精读 | - | 13:59 | [link](https://www.bilibili.com/video/BV1jw411t7Kq) |
| 414 | [论文简析]Deconstructing Denoising Diffusion Models for SSL[2401.14404] | - | AI 论文精读 | - | 30:00 | [link](https://www.bilibili.com/video/BV1bv421r7Sv) |
| 415 | [论文速览]Socratic Models: Zero-Shot Multimodal Reasoning[2204.00598] | - | AI 论文精读 | - | 11:32 | [link](https://www.bilibili.com/video/BV1cS4y1n7yn) |
| 416 | [论文简析]Large Language Models as General Pattern Machines[2307.04721] | - | AI 论文精读 | - | 15:46 | [link](https://www.bilibili.com/video/BV1EM4y1W7w1) |
| 417 | [论文速览]LaFTer: Label-Free Tuning of Zero-shot Classifier...[2305.18287] | - | AI 论文精读 | - | 6:52 | [link](https://www.bilibili.com/video/BV1Rm4y1p72G) |
| 418 | [论文速览]OWL-ViT: Simple Open-Vocabulary Object Detection with ViT[2205.06230] | - | AI 论文精读 | - | 7:45 | [link](https://www.bilibili.com/video/BV1x8411S7eZ) |
| 419 | [论文简析]GroupViT: Semantic Segmentation Emerges from Text Supervision[2202.11094] | - | AI 论文精读 | - | 11:09 | [link](https://www.bilibili.com/video/BV1Bv4y127gH) |
| 420 | [论文简析]VATT: Video-Audio-Text Transformer[2104.11178] | - | AI 论文精读 | - | 11:59 | [link](https://www.bilibili.com/video/BV1554y1j71k) |
| 421 | [论文简析]End-to-End Video-Language Transformers..Masked Visual-token..[2111.12681] | - | AI 论文精读 | - | 9:09 | [link](https://www.bilibili.com/video/BV1UM4y1c7fh) |
| 422 | [论文简析]TAN: Temporal Alignment Networks for Long-term Video[2204.02968] | - | AI 论文精读 | - | 16:21 | [link](https://www.bilibili.com/video/BV1194y1y7mF) |
| 423 | [论文简析]Improving fine-grained understanding in image-text pre-training[2401.0986] | - | AI 论文精读 | - | 17:36 | [link](https://www.bilibili.com/video/BV15A4m1G7zj) |
| 424 | [论文简析]End-to-End Learning... from Uncurated Instructional Videos[1912.06430] | - | AI 论文精读 | - | 8:59 | [link](https://www.bilibili.com/video/BV173411u7JE) |
| 425 | [论文简析]Region-Aware Pretraining for Open-Vocab. Object Det. w/ ViT[2305.07011] | - | AI 论文精读 | - | 8:11 | [link](https://www.bilibili.com/video/BV1D14y1C7m8) |
| 426 | [论文简析]Toolformer: Language Models Can Teach Themselves to Use Tools[2302.04761] | - | AI 论文精读 | - | 13:09 | [link](https://www.bilibili.com/video/BV1BV4y1a7iU) |
| 427 | [论文速览]ViperGPT: Visual Inference via Python Execution for Reasoning[2303.08128] | - | AI 论文精读 | - | 5:59 | [link](https://www.bilibili.com/video/BV1BV4y1879K) |
| 428 | [论文简析]VoxPoser: Composable 3D Value Maps for Robotic...[2307.05973] | - | AI 论文精读 | - | 13:04 | [link](https://www.bilibili.com/video/BV11h4y1j7D2) |
| 429 | [论文速览]LLaMA-Adapter: Efficient Fine-tuning..Zero-init Attention[2303.16199] | - | AI 论文精读 | - | 4:22 | [link](https://www.bilibili.com/video/BV1Kp4y1L7ya) |
| 430 | [论文速览]Open-vocabulary Object Segmentation with Diffusion Models[2301.05221] | - | AI 论文精读 | - | 9:20 | [link](https://www.bilibili.com/video/BV1VV4y1e78c) |
| 431 | [论文速览]Open Vocab. Semantic Seg.  with Patch Aligned Contrastive...[2212.04994] | - | AI 论文精读 | - | 4:32 | [link](https://www.bilibili.com/video/BV1w94y1z7ey) |
| 432 | [论文简析]Representation Learning via Global Temporal Alignment and ...[2105.05217] | - | AI 论文精读 | - | 14:30 | [link](https://www.bilibili.com/video/BV1CM4y1T7nj) |
| 433 | [论文速览]LLaVA: Visual Instruction Tuning[2304.08485] | - | AI 论文精读 | - | 9:33 | [link](https://www.bilibili.com/video/BV1n14y1k7B9) |
| 434 | [论文速览]LongLoRA: Efficient Fine-tuning of Long-Context LLMs[2309.12307] | - | AI 论文精读 | - | 5:04 | [link](https://www.bilibili.com/video/BV1PN411n7KX) |
| 435 | [论文简析]CLIP Dense Inference Yields Open-Vocab ... For-Free[2309.14289] | - | AI 论文精读 | - | 5:51 | [link](https://www.bilibili.com/video/BV1Jj41187We) |
| 436 | [论文速览]Ferret: Refer and Ground Anything Anywhere at Any Granularity[2310.07704] | - | AI 论文精读 | - | 9:43 | [link](https://www.bilibili.com/video/BV11h4y1z7mn) |
| 437 | [论文速览]VLMs are Zero-Shot Reward Models for RL[2310.12921] | - | AI 论文精读 | - | 4:42 | [link](https://www.bilibili.com/video/BV1ne411R74d) |
| 438 | [论文速览]CRG: Improving Grounding in VLM w/o training[2403.02325] | - | AI 论文精读 | - | 5:24 | [link](https://www.bilibili.com/video/BV1y2421T7R3) |
| 439 | [论文速览]A Simple LLM Framework for Long-Range Video Question-Answering[2312.17235] | - | AI 论文精读 | - | 12:22 | [link](https://www.bilibili.com/video/BV1d2421N7VA) |
| 440 | [论文速览]Align before Fuse / ALBEF: ...[2107.07651] | - | AI 论文精读 | - | 13:16 | [link](https://www.bilibili.com/video/BV1fx4y1U7ui) |
| 441 | [论文速览]Bootstrapping Language-Image Pre-training...[2201.12086] | - | AI 论文精读 | - | 11:26 | [link](https://www.bilibili.com/video/BV1H1421Q7Ft) |
| 442 | [论文速览]BLIP-2 ...with Frozen Image Encoders and Large Language Models[2301.12597] | - | AI 论文精读 | - | 13:43 | [link](https://www.bilibili.com/video/BV1Ci42197ab) |
| 443 | [论文速览]Ferret-v2: An Improved...for Referring and Grounding with LLMs[2404.07973] | - | AI 论文精读 | - | 9:30 | [link](https://www.bilibili.com/video/BV12F4m1N7Mc) |
| 444 | [论文速览]Token Turing Machines[2211.09119] | - | AI 论文精读 | - | 5:08 | [link](https://www.bilibili.com/video/BV1dV4y1f7J4) |
| 445 | [论文简析]NeRF in the Wild: NeRF for Unconstrained Photo Collections[2008.02268] | - | AI 论文精读 | - | 17:07 | [link](https://www.bilibili.com/video/BV1iD4y1e7K9) |
| 446 | [论文简析]Exploring Self-attention for Image Recognition[2004.13621] | - | AI 论文精读 | - | 16:31 | [link](https://www.bilibili.com/video/BV1nA411K7Z6) |
| 447 | [论文简析]FlowNet3D: Learning Scene Flow in 3D Point Clouds[1806.01411] | - | AI 论文精读 | - | 13:05 | [link](https://www.bilibili.com/video/BV1U3411j7Fg) |
| 448 | [论文简析]NeRV: Neural Representations for Videos[2110.13903] | - | AI 论文精读 | - | 8:34 | [link](https://www.bilibili.com/video/BV1Nf4y1K7j5) |
| 449 | [论文简析]TokenLearner: What Can 8 Learned Tokens Do for Images and vids[2106.11297] | - | AI 论文精读 | - | 11:15 | [link](https://www.bilibili.com/video/BV1of4y1t77m) |
| 450 | [论文简析]BiFormer: Vision Transformer with Bi-Level Routing Attention[2303.08810] | - | AI 论文精读 | - | 6:47 | [link](https://www.bilibili.com/video/BV1tF4111774) |
| 451 | [论文简析]When Shift Operation Meets Vision Transformer[2201.10801] | - | AI 论文精读 | - | 5:59 | [link](https://www.bilibili.com/video/BV1CF411n7at) |
| 452 | [论文简析]DeepLab V3/V3+[1706.05587/1802.02611] | - | AI 论文精读 | - | 10:36 | [link](https://www.bilibili.com/video/BV1by4y1g76s) |
| 453 | [论文速览]Deformable Convolutional Networks; DCN[1703.06211] | - | AI 论文精读 | - | 9:53 | [link](https://www.bilibili.com/video/BV1C94y1272t) |
| 454 | [论文简析]DeepLab: Semantic Image Segmentation with DCN..[1606.00915] | - | AI 论文精读 | - | 16:28 | [link](https://www.bilibili.com/video/BV1jf4y1Y7uM) |
| 455 | [论文简析]DAT: Vision Transformer with Deformable Attention[2201.00520] | - | AI 论文精读 | - | 7:00 | [link](https://www.bilibili.com/video/BV1ir4y137BG) |
| 456 | [论文速览]Aggregating Nested Transformers[2105.12723] | - | AI 论文精读 | - | 7:41 | [link](https://www.bilibili.com/video/BV1yq4y1H7mT) |
| 457 | [论文简析]X3D: Expanding Architectures for Efficient Video Recognition[2004.04730] | - | AI 论文精读 | - | 4:07 | [link](https://www.bilibili.com/video/BV1qZ4y1F7Kf) |
| 458 | [论文简析]CeiT: Incorporating Convolution Designs into Visual Tr[2103.11816] | - | AI 论文精读 | - | 5:57 | [link](https://www.bilibili.com/video/BV19L4y1B7Ad) |
| 459 | [论文速览]iFormer: Inception Transformer[2205.12956] | - | AI 论文精读 | - | 6:25 | [link](https://www.bilibili.com/video/BV19L4y1P7ri) |
| 460 | [论文速览]Bottleneck Transformers for Visual Recognition[2101.11605] | - | AI 论文精读 | - | 2:10 | [link](https://www.bilibili.com/video/BV1i64y1t7WN) |
| 461 | [论文简析]NAT: Neighborhood Attention Transformer[2204.07143] | - | AI 论文精读 | - | 5:14 | [link](https://www.bilibili.com/video/BV1xF411g7LK) |
| 462 | [论文简析]XCiT: Cross-Covariance Image Transformers[2106.09681] | - | AI 论文精读 | - | 10:17 | [link](https://www.bilibili.com/video/BV1n64y1Q7RX) |
| 463 | [论文简析]DeiT: Data-efficient Image Transformers[2012.12877] | - | AI 论文精读 | - | 9:49 | [link](https://www.bilibili.com/video/BV1L5411P7rV) |
| 464 | [论文简析]TNT: Transformer in Transformer[2103.00112] | - | AI 论文精读 | - | 7:17 | [link](https://www.bilibili.com/video/BV1KK4y1U7Uq) |
| 465 | [论文简析]Tokens-to-Token ViT: Training ViT from Scratch on ImageNet[2101.11986] | - | AI 论文精读 | - | 4:16 | [link](https://www.bilibili.com/video/BV1yv411L7xN) |
| 466 | [论文简析]Dynamic Vision Transformers with Adaptive Sequence Length[2105.15075] | - | AI 论文精读 | - | 12:21 | [link](https://www.bilibili.com/video/BV1s54y1H7Wb) |
| 467 | [论文简析]SlowFast Networks for Video Recognition[1812.03982] | - | AI 论文精读 | - | 9:35 | [link](https://www.bilibili.com/video/BV1DV411J7gS) |
| 468 | [论文简析]MViT: Multiscale Vision Transformers[2104.11227] | - | AI 论文精读 | - | 12:31 | [link](https://www.bilibili.com/video/BV1np4y1b7QY) |
| 469 | [论文简析]BEVT: BERT Pretraining of Video Transformers[2112.01529] | - | AI 论文精读 | - | 10:23 | [link](https://www.bilibili.com/video/BV1R44y1h7CR) |
| 470 | [论文简析]Unified Transformer for Efficient Spatiotemporal...[2201.04676] | - | AI 论文精读 | - | 6:28 | [link](https://www.bilibili.com/video/BV1CT4y1i7Fa) |
| 471 | [论文简析]MLP-Mixer: An all-MLP Architecture for Vision[2105.01601] | - | AI 论文精读 | - | 9:25 | [link](https://www.bilibili.com/video/BV1xK4y197qL) |
| 472 | [论文速览]EViT: Expediting Vision Transformers via Token Reorganizations[2202.07800] | - | AI 论文精读 | - | 4:24 | [link](https://www.bilibili.com/video/BV1HS4y1F7nU) |
| 473 | [论文简析]Is Space-Time Attention All You Need for Video Understanding?[2102.05095] | - | AI 论文精读 | - | 4:34 | [link](https://www.bilibili.com/video/BV1dA411371w) |
| 474 | [论文简析]A Laplacian Pyramid Translation Network[2105.09188] | - | AI 论文精读 | - | 16:12 | [link](https://www.bilibili.com/video/BV1V64y1h7nv) |
| 475 | [论文简析]Per-Pixel Classification is Not All You Need for Semantic Seg[2107.06278] | - | AI 论文精读 | - | 10:29 | [link](https://www.bilibili.com/video/BV17f4y1A7XR) |
| 476 | [论文速览]Masked-attention Mask Tr. for Universal Image Segmentation[2112.01527] | - | AI 论文精读 | - | 8:02 | [link](https://www.bilibili.com/video/BV1ob4y1B7hp) |
| 477 | [论文简析]MobileNets: Efficient CNN for Mobile Vision Applications[1704.04861] | - | AI 论文精读 | - | 6:03 | [link](https://www.bilibili.com/video/BV1LB4y1c7Ap) |
| 478 | [论文简析]MobileNet V2: Inverted Residuals and Linear Bottlenecks[1801.04381] | - | AI 论文精读 | - | 10:30 | [link](https://www.bilibili.com/video/BV1Fq4y1n7Mq) |
| 479 | [论文简析]Searching for MobileNet V3[1905.02244] | - | AI 论文精读 | - | 8:04 | [link](https://www.bilibili.com/video/BV1vN411f7pY) |
| 480 | [论文简析]MnasNet: Platform-Aware Neural Architecture Search for Mobile[1807.11626] | - | AI 论文精读 | - | 7:55 | [link](https://www.bilibili.com/video/BV1Wo4y127NM) |
| 481 | [论文简析]EfficientNet V1/V2[1905.11946/2104.00298] | - | AI 论文精读 | - | 13:29 | [link](https://www.bilibili.com/video/BV1MV411E7Pq) |
| 482 | [论文简析]Mobile-Former: Bridging MobileNet and Transformer[2108.05895] | - | AI 论文精读 | - | 13:49 | [link](https://www.bilibili.com/video/BV1CL4y1g76U) |
| 483 | [论文简析]Point Transformer[2012.09164] | - | AI 论文精读 | - | 11:54 | [link](https://www.bilibili.com/video/BV1PA41157su) |
| 484 | [论文简析]Point Transformer V2[2210.05666] | - | AI 论文精读 | - | 10:36 | [link](https://www.bilibili.com/video/BV1de4y157hR) |
| 485 | [论文速览]RetNet: A Successor to Transformer for Large Language Models[2307.08621] | - | AI 论文精读 | - | 24:49 | [link](https://www.bilibili.com/video/BV1134y1G7uQ) |
| 486 | [论文简析]Vision Transformers Need Registers[2309.16588] | - | AI 论文精读 | - | 6:57 | [link](https://www.bilibili.com/video/BV1up4y1c7JU) |
| 487 | [论文简析]Contrastive Learning for Unpaired Image-to-Image Translation[2007.15651] | - | AI 论文精读 | - | 17:20 | [link](https://www.bilibili.com/video/BV14y4y1s7tS) |
| 488 | [论文简析]Multimodal Unsupervised Image-to-Image Translation[1804.04732] | - | AI 论文精读 | - | 12:51 | [link](https://www.bilibili.com/video/BV1Pb4y1p78y) |
| 489 | [论文速览]Rethinking the Truly Unsupervised Image-to-Image Translation[2006.06500] | - | AI 论文精读 | - | 10:09 | [link](https://www.bilibili.com/video/BV1qZ4y1z77v) |
| 490 | [论文简析]Unsupervised Image-to-Image Translation Networks[1703.00848] | - | AI 论文精读 | - | 9:43 | [link](https://www.bilibili.com/video/BV1c34y187BW) |
| 491 | [论文简析]RetinaGAN: An Object-aware Approach to Sim-to-Real Transfer[2011.03148] | - | AI 论文精读 | - | 11:29 | [link](https://www.bilibili.com/video/BV17o4y1X7Mk) |
| 492 | [论文简析]MoCoGAN-HD: A Good Image Generator Is What You Need...[2104.15069] | - | AI 论文精读 | - | 14:06 | [link](https://www.bilibili.com/video/BV1gv411L7Dy) |
| 493 | [论文简析]VQ-VAE:Neural discrete representation learning[1711.00937] | - | AI 论文精读 | - | 16:54 | [link](https://www.bilibili.com/video/BV1bb4y1i7j6) |
| 494 | [论文速览]Autoregressive Image Generation using Residual Quantization[2203.01941] | - | AI 论文精读 | - | 21:26 | [link](https://www.bilibili.com/video/BV1gY411E7ge) |
| 495 | [论文速览]Personalizing Text2Img Generation using Textual Inversion[2208.01618] | - | AI 论文精读 | - | 4:39 | [link](https://www.bilibili.com/video/BV1oH4y1k7RW) |
| 496 | [论文速览]Taming Transformers for High-Resolution Image Synthesis[2012.09841] | - | AI 论文精读 | - | 6:14 | [link](https://www.bilibili.com/video/BV1ym4y1d7iP) |
| 497 | [论文简析]MaskGIT: Masked Generative Image Transformer[2202.04200] | - | AI 论文精读 | - | 9:00 | [link](https://www.bilibili.com/video/BV1qS4y1r7p1) |
| 498 | [论文简析]Regularized Vector Quantization for Tokenized Image Synthesis[2303.06424] | - | AI 论文精读 | - | 9:28 | [link](https://www.bilibili.com/video/BV1rG411o7pp) |
| 499 | [论文速览]Denoising Diffusion Probabilistic Models / DDPM[2006.11239] | - | AI 论文精读 | - | 31:44 | [link](https://www.bilibili.com/video/BV1yA41167Dg) |
| 500 | [论文速览]Denoising Diffusion Implicit Models / DDIM[2010.02502] | - | AI 论文精读 | - | 8:51 | [link](https://www.bilibili.com/video/BV1ic41157Vf) |
| 501 | [论文速览]Structured Denoising Diffusion Models in Discrete State-Spaces[2107.03006] | - | AI 论文精读 | - | 19:17 | [link](https://www.bilibili.com/video/BV1R84y1H7k1) |
| 502 | [论文速览]Drag Your GAN: Interactive Point-based Manipulation...[2305.10973] | - | AI 论文精读 | - | 10:30 | [link](https://www.bilibili.com/video/BV1Ju41177k3) |
| 503 | [论文简析]DreamBooth: Fine Tuning Text-to-Image Diffusion Models...[2208.12242] | - | AI 论文精读 | - | 7:55 | [link](https://www.bilibili.com/video/BV18m4y1H7fs) |
| 504 | [论文速览]FreeU: Free Lunch in Diffusion U-Net[2309.11497] | - | AI 论文精读 | - | 4:53 | [link](https://www.bilibili.com/video/BV1dk4y1F7dg) |
| 505 | [论文简析]Visual Autoregressive Modeling: ...via Next-Scale Prediction[2404.02905] | - | AI 论文精读 | - | 28:12 | [link](https://www.bilibili.com/video/BV1pq421P7D4) |
| 506 | [论文速览]MixUp: Beyond Empirical Risk Minimization[1710.09412] | - | AI 论文精读 | - | 6:57 | [link](https://www.bilibili.com/video/BV12q4y167SV) |
| 507 | [论文速览]RegMixup: Mixup as a Regularizer Can Surprisingly Improve...[2206.14502] | - | AI 论文精读 | - | 9:40 | [link](https://www.bilibili.com/video/BV1jB4y1i7iw) |
| 508 | [论文夕拾]Mixed Sample Data Augmentations, Part 1 | - | AI 论文精读 | - | 17:51 | [link](https://www.bilibili.com/video/BV1rr4y1V7Dx) |
| 509 | [论文夕拾]Mixed Sample Data Augmentations, Part 2 | - | AI 论文精读 | - | 6:20 | [link](https://www.bilibili.com/video/BV1qt4y1h7kM) |
| 510 | [论文简析]Robust and Generalizable Visual ... via Random Convolutions[2007.13003] | - | AI 论文精读 | - | 3:57 | [link](https://www.bilibili.com/video/BV1Kq4y1E7j3) |
| 511 | [论文速览]Simple Copy-Paste is a Strong Data Aug. for Instance Seg.[2012.07177] | - | AI 论文精读 | - | 3:11 | [link](https://www.bilibili.com/video/BV1Hq4y1s7wB) |
| 512 | [论文速览]Visual Prompt Tuning / VPT[2203.12119] | - | AI 论文精读 | - | 3:00 | [link](https://www.bilibili.com/video/BV18h4y127GG) |
| 513 | [论文简析]Red Circle: Visual Prompt Engineering for VLMs[2304.06712] | - | AI 论文精读 | - | 10:33 | [link](https://www.bilibili.com/video/BV1wk4y1V7wo) |
| 514 | [论文简析]Finding an Unsupervised Image Segmenter in .. Generative Model[2105.08127] | - | AI 论文精读 | - | 10:38 | [link](https://www.bilibili.com/video/BV1Dy4y1W7uM) |
| 515 | [论文简析]PolyFormer: Referring Image Seg. as Sequential Polygon Gen [2302.07387] | - | AI 论文精读 | - | 10:54 | [link](https://www.bilibili.com/video/BV1wr4y1o7V5) |
| 516 | [论文简析]DiffSeg: Unsupervised Zero-Shot Seg. using Stable Diffusion[2308.12469] | - | AI 论文精读 | - | 13:20 | [link](https://www.bilibili.com/video/BV1Sm4y1T74R) |
| 517 | [论文简析]Patching Open-Vocabulary Models by Interpolating Weights[2208.05592] | - | AI 论文精读 | - | 12:55 | [link](https://www.bilibili.com/video/BV1tV411P73W) |
| 518 | [论文速览]Scalable Video Object Segmentation with Simplified Framework[2308.09903] | - | AI 论文精读 | - | 8:07 | [link](https://www.bilibili.com/video/BV1Vu411g7Gm) |
| 519 | [论文速览]Learning to Learn with Generative Models of NN Checkpoints[2209.12892] | - | AI 论文精读 | - | 8:21 | [link](https://www.bilibili.com/video/BV13H4y1j7Zd) |
| 520 | 给女朋友做的AR元宇宙增强现实生日贺卡 | - | AI 论文精读 | - | 1:19 | [link](https://www.bilibili.com/video/BV17Y4y1z73F) |
| 521 | MATLAB竟然还能做增强现实AR元宇宙？ | - | AI 论文精读 | - | 16:30 | [link](https://www.bilibili.com/video/BV1wG41137oJ) |
| 522 | 构建自己的图像分类数据集【两天搞定AI毕设】 | - | AI 论文精读 | - | 35:07 | [link](https://www.bilibili.com/video/BV1Jd4y1T7rw) |
| 523 | Pytorch预训练图像分类模型识别预测【两天搞定AI毕设】 | - | AI 论文精读 | - | 37:55 | [link](https://www.bilibili.com/video/BV1qe4y1D7zD) |
| 524 | Pytorch迁移学习训练自己的图像分类模型【两天搞定AI毕设】 | - | AI 论文精读 | - | 51:15 | [link](https://www.bilibili.com/video/BV1Ng411C7WY) |
| 525 | 用训练得到的pytorch图像分类模型，识别图像、视频、摄像头画面【两天搞定AI毕设】 | - | AI 论文精读 | - | 16:46 | [link](https://www.bilibili.com/video/BV12d4y1P7xz) |
| 526 | 测试集上评估Pytorch训练得到的图像分类模型【两天搞定AI毕业设计】 | - | AI 论文精读 | - | 24:49 | [link](https://www.bilibili.com/video/BV1bP411j7NK) |
| 527 | 图像分类测试集语义特征降维可视化 | - | AI 论文精读 | - | 30:20 | [link](https://www.bilibili.com/video/BV1VB4y1z7xN) |
| 528 | 图像分类可解释性分析实战-CAM热力图系列算法 | - | AI 论文精读 | - | 46:34 | [link](https://www.bilibili.com/video/BV1JG4y1s74x) |
| 529 | 图像分类可解释性分析实战-Deep Feature Factorization | - | AI 论文精读 | - | 10:50 | [link](https://www.bilibili.com/video/BV1Re4y1n73v) |
| 530 | 图像分类可解释性分析实战-Captum工具包 | - | AI 论文精读 | - | 13:12 | [link](https://www.bilibili.com/video/BV1DN4y1N7fc) |
| 531 | 图像分类可解释性分析实战-shap工具包 | - | AI 论文精读 | - | 49:01 | [link](https://www.bilibili.com/video/BV1vP4y1S7Xu) |
| 532 | 图像分类可解释性分析实战-lime工具包 | - | AI 论文精读 | - | 14:58 | [link](https://www.bilibili.com/video/BV1a84y1i7Tz) |
| 533 | 图像分类模型部署-Pytorch转ONNX | - | AI 论文精读 | - | 16:41 | [link](https://www.bilibili.com/video/BV1cM4y187Xc) |
| 534 | Pytorch图像分类模型部署-ONNX Runtime本地终端推理 | - | AI 论文精读 | - | 23:01 | [link](https://www.bilibili.com/video/BV1AM4y187yR) |
| 535 | Pytorch图像分类部署-ONNX Runtime安卓手机APP | - | AI 论文精读 | - | 16:33 | [link](https://www.bilibili.com/video/BV1cs4y1Q7nu) |
| 536 | Pytorch图像分类部署-ONNX Runtime浏览器Web前端 | - | AI 论文精读 | - | 6:04 | [link](https://www.bilibili.com/video/BV1Ja4y137fZ) |
| 537 | AidLux图像分类部署-安卓鸿蒙高通ARM | - | AI 论文精读 | - | 34:14 | [link](https://www.bilibili.com/video/BV1oN411h7p1) |
| 538 | 文本识别OCR神器 MMOCR【OpenMMLab】 | - | AI 论文精读 | - | 15:43 | [link](https://www.bilibili.com/video/BV1Ua411x7dB) |
| 539 | MMOCR代码实战（上）安装配置、预训练OCR模型预测 | - | AI 论文精读 | - | 14:02 | [link](https://www.bilibili.com/video/BV1hP4y1M7Zc) |
| 540 | MMOCR代码实战（中）AI给文字区域打马赛克 | - | AI 论文精读 | - | 10:50 | [link](https://www.bilibili.com/video/BV1nZ4y1z77X) |
| 541 | MMOCR代码实战（下）Kaggle验证码文本识别 | - | AI 论文精读 | - | 10:32 | [link](https://www.bilibili.com/video/BV1tL411A7bj) |
| 542 | Github高赞开源项目速览-AIGC与大语言模型-20230707 | - | AI 论文精读 | - | 22:41 | [link](https://www.bilibili.com/video/BV1eW4y1f72L) |
| 543 | Github高赞开源项目速览-AIGC的N种玩法-20230808 | - | AI 论文精读 | - | 32:27 | [link](https://www.bilibili.com/video/BV1cV411V7LU) |
| 544 | 中医+人工智能黑科技：耳朵穴位经络图像识别 | - | AI 论文精读 | - | 1:24 | [link](https://www.bilibili.com/video/BV168411Z7Lt) |
| 545 | 标注关键点检测数据集 | - | AI 论文精读 | - | 46:14 | [link](https://www.bilibili.com/video/BV19g4y1777q) |
| 546 | 关键点检测数据集-Labelme格式转YOLO格式 | - | AI 论文精读 | - | 19:54 | [link](https://www.bilibili.com/video/BV1QX4y1B7eF) |
| 547 | 关键点检测数据集-Labelme格式转MS COCO格式 | - | AI 论文精读 | - | 25:28 | [link](https://www.bilibili.com/video/BV1vc411J7GC) |
| 548 | YOLOV8关键点检测-预训练模型预测 | - | AI 论文精读 | - | 36:04 | [link](https://www.bilibili.com/video/BV1yg4y177ef) |
| 549 | YOLOV8关键点检测-训练自己的关键点检测模型 | - | AI 论文精读 | - | 50:36 | [link](https://www.bilibili.com/video/BV13a4y157HE) |
| 550 | YOLOV8关键点检测-用训练得到的模型预测图像、视频、摄像头画面 | - | AI 论文精读 | - | 34:15 | [link](https://www.bilibili.com/video/BV1Lo4y1t76s) |
| 551 | YOLOV8关键点检测-预测源码解读 | - | AI 论文精读 | - | 18:07 | [link](https://www.bilibili.com/video/BV1Yu411t7XF) |
| 552 | YOLOV8关键点检测-ONNX Runtime部署 | - | AI 论文精读 | - | 21:24 | [link](https://www.bilibili.com/video/BV18L411B7Mv) |
| 553 | 玩转MMPose人体姿态估计关键点检测 | - | AI 论文精读 | - | 1:01 | [link](https://www.bilibili.com/video/BV16B4y1h7JS) |
| 554 | 开源姿态估计算法库MMPose | - | AI 论文精读 | - | 33:02 | [link](https://www.bilibili.com/video/BV15B4y1p7Kj) |
| 555 | RTMPose关键点检测-安装MMDetection和MMPose | - | AI 论文精读 | - | 15:42 | [link](https://www.bilibili.com/video/BV1Pa4y1g7N7) |
| 556 | RTMPose关键点检测-MMDetection三角板目标检测 | - | AI 论文精读 | - | 19:43 | [link](https://www.bilibili.com/video/BV1Lm4y1879K) |
| 557 | RTMPose关键点检测-训练、评估、推理预测 | - | AI 论文精读 | - | 17:52 | [link](https://www.bilibili.com/video/BV12a4y1u7sd) |
| 558 | AI画《三体》名场面 | - | AI 论文精读 | - | 2:12 | [link](https://www.bilibili.com/video/BV1b14y1W7iq) |
| 559 | AI画我的三体之章北海传 | - | AI 论文精读 | - | 2:47 | [link](https://www.bilibili.com/video/BV1Ux4y1F7zA) |
| 560 | 如果AI来画清华美院艺考题 | - | AI 论文精读 | - | 2:12 | [link](https://www.bilibili.com/video/BV1d24y1f7Gi) |
| 561 | 三分钟部署AIGC神器DragGAN | - | AI 论文精读 | - | 7:39 | [link](https://www.bilibili.com/video/BV1Xw411e7ev) |
| 562 | 斥资500元，我用AI打造的三体科幻微电影《云天明的童话》 | - | AI 论文精读 | - | 2:13 | [link](https://www.bilibili.com/video/BV1Xu4y1b7ny) |
| 563 | 石趣绘本园：基于Amazon Bedrock的AIGC交互式童话绘本 | - | AI 论文精读 | - | 6:16 | [link](https://www.bilibili.com/video/BV1n64y1N7Vz) |
| 564 | 【拜年神器】一键部署阿里开源AI写真 | - | AI 论文精读 | - | 7:34 | [link](https://www.bilibili.com/video/BV1DZ421B7J9) |
| 565 | 【精读AI论文】知识蒸馏 | - | AI 论文精读 | - | 64:22 | [link](https://www.bilibili.com/video/BV1gS4y1k7vj) |
| 566 | 知识蒸馏开山之作论文精读：Distilling the knowledge in a neural network | - | AI 论文精读 | - | 124:13 | [link](https://www.bilibili.com/video/BV1N44y1n7mU) |
| 567 | 知识蒸馏Pytorch代码实战 | - | AI 论文精读 | - | 8:34 | [link](https://www.bilibili.com/video/BV1zP4y1F7g4) |
| 568 | python交互式地图数据可视化神器folium | - | AI 论文精读 | - | 29:05 | [link](https://www.bilibili.com/video/BV1t3411A7Z8) |
| 569 | folium实战-拍照地点分布地图可视化 | - | AI 论文精读 | - | 5:11 | [link](https://www.bilibili.com/video/BV1m3411A786) |
| 570 | folium实战-全球地震与板块运动分布 | - | AI 论文精读 | - | 21:24 | [link](https://www.bilibili.com/video/BV1gZ4y18772) |
| 571 | folium实战-波士顿犯罪地点、新冠疫情小区、纽约全天公交车可视化 | - | AI 论文精读 | - | 11:04 | [link](https://www.bilibili.com/video/BV18T4y1B7PA) |
| 572 | folium实战-轨道交通数据可视化 | - | AI 论文精读 | - | 21:36 | [link](https://www.bilibili.com/video/BV113411N7TL) |
| 573 | 玩转MMTracking视频感知与追踪算法库 | - | AI 论文精读 | - | 0:49 | [link](https://www.bilibili.com/video/BV1za411Y7Zm) |
| 574 | MMTracking单目标追踪+轨迹绘制代码实战 | - | AI 论文精读 | - | 23:06 | [link](https://www.bilibili.com/video/BV1s44y1g75J) |
| 575 | AI人流量计数+足迹追踪 | - | AI 论文精读 | - | 42:06 | [link](https://www.bilibili.com/video/BV1J3411M7KQ) |
| 576 | 训练Deepsort多目标追踪算法 | - | AI 论文精读 | - | 10:17 | [link](https://www.bilibili.com/video/BV1e5411m7Qh) |
| 577 | 【开箱遛遛】宇树机器狗Go2 | - | AI 论文精读 | - | 0:36 | [link](https://www.bilibili.com/video/BV1hG411Y74j) |
| 578 | 斯坦福CS224W图机器学习、图神经网络、知识图谱【同济子豪兄】 | - | AI 论文精读 | - | 69:54 | [link](https://www.bilibili.com/video/BV1pR4y1S7GA) |
| 579 | 图的基本表示【斯坦福CS224W图机器学习】 | - | AI 论文精读 | - | 30:17 | [link](https://www.bilibili.com/video/BV1n84y1e7SF) |
| 580 | 传统图机器学习的特征工程-节点【斯坦福CS224W】 | - | AI 论文精读 | - | 38:58 | [link](https://www.bilibili.com/video/BV1HK411175s) |
| 581 | 传统图机器学习的特征工程-连接【斯坦福CS224W】 | - | AI 论文精读 | - | 13:27 | [link](https://www.bilibili.com/video/BV1r3411m7sD) |
| 582 | 传统图机器学习的特征工程-全图【斯坦福CS224W】 | - | AI 论文精读 | - | 17:41 | [link](https://www.bilibili.com/video/BV14W4y1V7gg) |
| 583 | 图机器学习NetworkX代码实战-创建图和可视化 | - | AI 论文精读 | - | 29:09 | [link](https://www.bilibili.com/video/BV1kM41147zV) |
| 584 | 图机器学习NetworkX代码实战-上海地铁站点图数据挖掘 | - | AI 论文精读 | - | 23:25 | [link](https://www.bilibili.com/video/BV1LY411R7HJ) |
| 585 | 随机游走的艺术-图嵌入表示学习【斯坦福CS224W图机器学习】 | - | AI 论文精读 | - | 67:19 | [link](https://www.bilibili.com/video/BV1AP4y1r7Pz) |
| 586 | DeepWalk【图神经网络论文精读】 | - | AI 论文精读 | - | 46:51 | [link](https://www.bilibili.com/video/BV1o94y197vf) |
| 587 | DeepWalk论文逐句精读 | - | AI 论文精读 | - | 85:57 | [link](https://www.bilibili.com/video/BV1pW4y1z7pb) |
| 588 | DeepWalk代码实战-维基百科词条图嵌入可视化 | - | AI 论文精读 | - | 16:54 | [link](https://www.bilibili.com/video/BV1et4y187Gd) |
| 589 | Node2Vec【图神经网络论文精读】 | - | AI 论文精读 | - | 45:01 | [link](https://www.bilibili.com/video/BV1BS4y1E7tf) |
| 590 | Node2Vec论文逐句精读 | - | AI 论文精读 | - | 83:09 | [link](https://www.bilibili.com/video/BV1vU4y1i77T) |
| 591 | Node2Vec代码实战-《悲惨世界》小说人物图嵌入、Alias Sampling复现 | - | AI 论文精读 | - | 20:22 | [link](https://www.bilibili.com/video/BV1VS4y1E7Me) |
| 592 | 改变世界的谷歌PageRank算法 | - | AI 论文精读 | - | 77:18 | [link](https://www.bilibili.com/video/BV1uP411K7yN) |
| 593 | PageRank代码实战-西游记人物重要度 | - | AI 论文精读 | - | 6:04 | [link](https://www.bilibili.com/video/BV1Wg411H7Ep) |
| 594 | 半监督节点分类：标签传播和消息传递【斯坦福CS224W图机器学习】 | - | AI 论文精读 | - | 74:06 | [link](https://www.bilibili.com/video/BV1184y1G7pA) |
| 595 | 深度学习基础【斯坦福CS224W图神经网络】 | - | AI 论文精读 | - | 40:58 | [link](https://www.bilibili.com/video/BV13g4y1n7b4) |
| 596 | 图神经网络综述和学习路径【斯坦福CS224W图机器学习】 | - | AI 论文精读 | - | 52:40 | [link](https://www.bilibili.com/video/BV16v4y1b7x7) |
| 597 | 图卷积神经网络GCN | - | AI 论文精读 | - | 63:03 | [link](https://www.bilibili.com/video/BV1Hs4y157Ls) |
| 598 | 图神经网络GNN的表达能力 | - | AI 论文精读 | - | 45:24 | [link](https://www.bilibili.com/video/BV1MT411Y7da) |
| 599 | 玩转Neo4j知识图谱和图数据挖掘 | - | AI 论文精读 | - | 28:54 | [link](https://www.bilibili.com/video/BV1Mr4y1i7CX) |
| 600 | Neo4j医疗知识图谱智能问答机器人 | - | AI 论文精读 | - | 19:57 | [link](https://www.bilibili.com/video/BV1uY41167Ha) |
| 601 | 【精读AI论文】旷视轻量化网络ShuffleNet V2-算法精讲 | - | AI 论文精读 | - | 70:34 | [link](https://www.bilibili.com/video/BV1d3411Y7Ms) |
| 602 | 【精读AI论文】旷视轻量化网络ShuffleNet V2-论文精读 | - | AI 论文精读 | - | 93:36 | [link](https://www.bilibili.com/video/BV17u411U7Ag) |
| 603 | 生成对抗网络GAN交互式可视化 | - | AI 论文精读 | - | 19:26 | [link](https://www.bilibili.com/video/BV1R44y1377T) |
| 604 | 生成对抗网络GAN开山之作论文精读 | - | AI 论文精读 | - | 100:15 | [link](https://www.bilibili.com/video/BV1oi4y1m7np) |
| 605 | 精读CycleGAN论文-拍案叫绝的非配对图像风格迁移 | - | AI 论文精读 | - | 105:07 | [link](https://www.bilibili.com/video/BV1Ya411a78P) |
| 606 | CycleGAN照片转梵高莫奈油画 | - | AI 论文精读 | - | 29:59 | [link](https://www.bilibili.com/video/BV1wv4y1T71F) |
| 607 | MMGeneration开源图像生成算法库【OpenMMLab】 | - | AI 论文精读 | - | 44:07 | [link](https://www.bilibili.com/video/BV1bY4y147kz) |
| 608 | 【精读AI论文】pix2pix-简笔画猫转真猫 | - | AI 论文精读 | - | 95:10 | [link](https://www.bilibili.com/video/BV1wY4y1k7Tc) |
| 609 | 人像自拍秒变爆款动漫画风【OpenMMLab】 | - | AI 论文精读 | - | 28:04 | [link](https://www.bilibili.com/video/BV1XL4y1g7in) |
| 610 | 两天搞定语义分割毕业设计 | - | AI 论文精读 | - | 0:12 | [link](https://www.bilibili.com/video/BV1Wr4y1d7Tr) |
| 611 | 语义分割与MMSegmentation | - | AI 论文精读 | - | 41:52 | [link](https://www.bilibili.com/video/BV1qN411z7hz) |
| 612 | 标注自己的语义分割数据集 | - | AI 论文精读 | - | 33:09 | [link](https://www.bilibili.com/video/BV1uu4y1Q7Rt) |
| 613 | 安装配置MMSegmentation+预训练语义分割推理预测 | - | AI 论文精读 | - | 26:37 | [link](https://www.bilibili.com/video/BV1du4y1q7o5) |
| 614 | 准备西瓜语义分割数据集 | - | AI 论文精读 | - | 14:20 | [link](https://www.bilibili.com/video/BV1C8411X7p9) |
| 615 | 准备MMSeg语义分割config配置文件 | - | AI 论文精读 | - | 23:26 | [link](https://www.bilibili.com/video/BV1w44y1F73N) |
| 616 | MMSegmentation训练语义分割深度学习算法 | - | AI 论文精读 | - | 23:54 | [link](https://www.bilibili.com/video/BV1Ch4y1S7cX) |
| 617 | MMSeg语义分割推理预测 | - | AI 论文精读 | - | 24:52 | [link](https://www.bilibili.com/video/BV1vp4y1K7Tj) |
| 618 | 语义分割部署-MMDeploy模型转换 | - | AI 论文精读 | - | 17:41 | [link](https://www.bilibili.com/video/BV1Ep4y1n7wo) |
| 619 | 语义分割部署-ONNX Runtime实时推理 | - | AI 论文精读 | - | 6:33 | [link](https://www.bilibili.com/video/BV1aN411B7Dq) |
| 620 | AidLux语义分割部署-安卓鸿蒙高通ARM | - | AI 论文精读 | - | 28:59 | [link](https://www.bilibili.com/video/BV1k8411y7c2) |
| 621 | 可解释机器学习公开课 | - | AI 论文精读 | - | 61:06 | [link](https://www.bilibili.com/video/BV1Se4y1T7dG) |
| 622 | CAM可解释性分析-算法讲解 | - | AI 论文精读 | - | 36:49 | [link](https://www.bilibili.com/video/BV1Ke411g7gm) |
| 623 | CAM可解释性论文精读：Learning Deep Features for Discriminative Localization | - | AI 论文精读 | - | 50:15 | [link](https://www.bilibili.com/video/BV1fe4y1C7mN) |
| 624 | GradCAM深度学习可解释性分析 | - | AI 论文精读 | - | 48:04 | [link](https://www.bilibili.com/video/BV1PD4y1B77q) |
| 625 | 【精读AI论文】GradCAM可解释性分析 | - | AI 论文精读 | - | 53:08 | [link](https://www.bilibili.com/video/BV1id4y167FF) |
| 626 | LIME机器学习可解释性分析 | - | AI 论文精读 | - | 52:13 | [link](https://www.bilibili.com/video/BV12V4y1G7KF) |
| 627 | 【精读AI论文】LIME机器学习可解释性分析 | - | AI 论文精读 | - | 73:31 | [link](https://www.bilibili.com/video/BV1wV4y1V7rD) |
| 628 | MATLAB玩转深度学习可解释性分析 | - | AI 论文精读 | - | 19:11 | [link](https://www.bilibili.com/video/BV1Qd4y1b7Mr) |
| 629 | 11款神经网络科研绘图可视化工具 | - | AI 论文精读 | - | 20:55 | [link](https://www.bilibili.com/video/BV1TV4y1P7AP) |
| 630 | 视频理解和图像理解有什么区别？时序信息怎么建模？ | - | AI 论文精读 | - | 1:35 | [link](https://www.bilibili.com/video/BV1MddhBrEn8) |
| 631 | CLIP 的训练目标是什么？为什么要做图文匹配？ | - | AI 论文精读 | - | 1:31 | [link](https://www.bilibili.com/video/BV1spdhBPEEk) |
| 632 | CLIP 的视觉编码器用 ViT 还是 ResNet？各有什么优缺点？ | - | AI 论文精读 | - | 1:37 | [link](https://www.bilibili.com/video/BV1v7dzB6E8X) |
| 633 | 多模态模型的对齐（Alignment）是什么意思？怎么让图文语义对应？ | - | AI 论文精读 | - | 1:30 | [link](https://www.bilibili.com/video/BV19zdBBiE3c) |
| 634 | 图文相似度怎么计算？余弦相似度够用吗？ | - | AI 论文精读 | - | 1:26 | [link](https://www.bilibili.com/video/BV1HtoNBZEfS) |
| 635 | U-Net 在扩散模型里是怎么用的？时间步嵌入（Time Embedding）是什么？ | - | AI 论文精读 | - | 1:28 | [link](https://www.bilibili.com/video/BV1g7d2BXEDD) |
| 636 | CogVLM 的视觉专家模块是怎么设计的？ | - | AI 论文精读 | - | 1:26 | [link](https://www.bilibili.com/video/BV1g7d2BXEv5) |
| 637 | 文本生成 3D（Text-to-3D）怎么做？DreamFusion 的原理是什么？ | - | AI 论文精读 | - | 1:32 | [link](https://www.bilibili.com/video/BV13jd2BWETV) |
| 638 | 视频分类 (Video Classification) 怎么做？怎么从视频里提取全局特征？ | - | AI 论文精读 | - | 2:07 | [link](https://www.bilibili.com/video/BV1e3d2BoEqg) |
| 639 | 三维目标检测（3D Object Detection）怎么做？和 2D 检测有什么区别？ | - | AI 论文精读 | - | 2:02 | [link](https://www.bilibili.com/video/BV1XdonB9E4f) |
| 640 | GPT-4V（GPT-4 Vision）的多模态能力有多强？能做什么？ | - | AI 论文精读 | - | 1:38 | [link](https://www.bilibili.com/video/BV1fgoVBGEBi) |
| 641 | 多视图几何（Multi-View Geometry）是什么？SfM 和 SLAM 有什么区别？ | - | AI 论文精读 | - | 1:47 | [link](https://www.bilibili.com/video/BV134oVBaEN2) |
| 642 | IP-Adapter 是什么？怎么用图像作为 Prompt？ | - | AI 论文精读 | - | 1:37 | [link](https://www.bilibili.com/video/BV1bqoSB8Ec9) |
| 643 | 视频多模态大模型怎么做？长视频理解的难点是什么？ | - | AI 论文精读 | - | 1:55 | [link](https://www.bilibili.com/video/BV121o6BAEYN) |
| 644 | 跨模态检索（Cross-modal Retrieval）怎么做？图搜文、文搜图的原理是什么？ | - | AI 论文精读 | - | 1:38 | [link](https://www.bilibili.com/video/BV1G3R4BAEnv) |
| 645 | 视频超分辨率（Video Super-Resolution）是什么？怎么提升视频清晰度？ | - | AI 论文精读 | - | 1:53 | [link](https://www.bilibili.com/video/BV1SRdgBQE2m) |
| 646 | ViT 和 CNN 有什么区别？为什么多模态模型更喜欢用 ViT？ | - | AI 论文精读 | - | 1:40 | [link](https://www.bilibili.com/video/BV1DX5v69EmL) |
| 647 | 多模态大模型的幻觉问题更严重吗？视觉幻觉怎么缓解？ | - | AI 论文精读 | - | 1:49 | [link](https://www.bilibili.com/video/BV1BcLF6iEHb) |
| 648 | ViT（Vision Transformer）是怎么处理图像的？Patch Embedding 是什么？ | - | AI 论文精读 | - | 1:33 | [link](https://www.bilibili.com/video/BV1QfL16WE5q) |
| 649 | 【AI编译篇】AI  Infra 简历点评 | - | AI 论文精读 | - | 19:04 | [link](https://www.bilibili.com/video/BV1WE3c6uEYH) |
| 650 | 【AI应用篇】AI Infra简历点评 | - | AI 论文精读 | - | 27:54 | [link](https://www.bilibili.com/video/BV1oJ3B6AEBn) |
| 651 | 【AI推理篇】AI Infra简历点评 | - | AI 论文精读 | - | 37:04 | [link](https://www.bilibili.com/video/BV1poMy6HEws) |
| 652 | TileLang 分享：TileLang 简介 | - | AI 论文精读 | - | 2:13 | [link](https://www.bilibili.com/video/BV1jHyjBEEFd) |
| 653 | TileLang 分享：TileLang 特性介绍 | - | AI 论文精读 | - | 12:53 | [link](https://www.bilibili.com/video/BV1jJyjBSEzQ) |
| 654 | TileLang 分享：TileLang API 及算子实例 | - | AI 论文精读 | - | 9:13 | [link](https://www.bilibili.com/video/BV1LpyjBmEGz) |
| 655 | TileLang 分享：TileLang 调优和 Debug | - | AI 论文精读 | - | 4:54 | [link](https://www.bilibili.com/video/BV15pyjBmED5) |
| 656 | 自编教材实操课程分享：第五章—编译器前端 | - | AI 论文精读 | - | 8:19 | [link](https://www.bilibili.com/video/BV1NC411Y7A8) |
| 657 | 自编教材实操课程分享：第五章—编译器中端 | - | AI 论文精读 | - | 8:03 | [link](https://www.bilibili.com/video/BV1Xr421H7t3) |
| 658 | 自编教材实操课程分享：第五章—编译器后端 | - | AI 论文精读 | - | 8:53 | [link](https://www.bilibili.com/video/BV1gi421d7Hc) |
| 659 | 自编教材实操课程分享：第五章—编译选项 | - | AI 论文精读 | - | 5:42 | [link](https://www.bilibili.com/video/BV1Nr421n7Pd) |
| 660 | 自编教材实操课程分享：第五章—过程间优化 | - | AI 论文精读 | - | 6:05 | [link](https://www.bilibili.com/video/BV15m411d7gH) |
| 661 | 自编教材实操课程分享：第五章—循环展开 | - | AI 论文精读 | - | 9:36 | [link](https://www.bilibili.com/video/BV13f421f7ip) |
| 662 | 自编教材实操课程分享：第五章—循环分布 | - | AI 论文精读 | - | 9:40 | [link](https://www.bilibili.com/video/BV1pj421d793) |
| 663 | 自编教材实操课程分享：第五章—循环剥离 | - | AI 论文精读 | - | 6:10 | [link](https://www.bilibili.com/video/BV1AD421W7A1) |
| 664 | 自编教材实操课程分享：第五章—循环级向量化 | - | AI 论文精读 | - | 11:23 | [link](https://www.bilibili.com/video/BV19M4m1X7PU) |
| 665 | 自编教材实操课程分享：第五章—基本块级向量化 | - | AI 论文精读 | - | 7:59 | [link](https://www.bilibili.com/video/BV1wp421y7k2) |
| 666 | 自编教材实操课程分享：第五章—数据预取优化 | - | AI 论文精读 | - | 6:31 | [link](https://www.bilibili.com/video/BV1Dz421k72n) |
| 667 | 自编教材实操课程分享：第五章—浮点优化 | - | AI 论文精读 | - | 7:34 | [link](https://www.bilibili.com/video/BV1BZ421e7t6) |
| 668 | 自编教材实操课程分享：第五章—反馈优化 | - | AI 论文精读 | - | 3:34 | [link](https://www.bilibili.com/video/BV1xx421S74X) |
| 669 | 自编教材实操课程分享：第五章—链接时优化 | - | AI 论文精读 | - | 4:32 | [link](https://www.bilibili.com/video/BV1ZD421p7Gy) |
| 670 | 自编教材实操课程分享：第五章—编译指示 | - | AI 论文精读 | - | 19:35 | [link](https://www.bilibili.com/video/BV1jZ421v791) |
| 671 | 自编教材实操课程分享：第五章—数学库优化 | - | AI 论文精读 | - | 12:19 | [link](https://www.bilibili.com/video/BV12D421p79o) |
| 672 | 自编教材实操课程分享：第五章—运行时优化 | - | AI 论文精读 | - | 7:43 | [link](https://www.bilibili.com/video/BV1ax4y167hV) |
| 673 | 自编教材实操课程分享：第六章—算法优化 | - | AI 论文精读 | - | 16:37 | [link](https://www.bilibili.com/video/BV1C142197zL) |
| 674 | 自编教材实操课程分享：第六章—典型数据结构的性能分析 | - | AI 论文精读 | - | 3:59 | [link](https://www.bilibili.com/video/BV1ew4m127sJ) |
| 675 | 自编教材实操课程分享：第六章—选择合适的数据类型 | - | AI 论文精读 | - | 5:40 | [link](https://www.bilibili.com/video/BV11t421c7N1) |
| 676 | 自编教材实操课程分享：第六章—选择合适的数据结构（二） | - | AI 论文精读 | - | 7:08 | [link](https://www.bilibili.com/video/BV1vi421C7mB) |
| 677 | 自编教材实操课程分享：第六章—别名消除 | - | AI 论文精读 | - | 4:02 | [link](https://www.bilibili.com/video/BV1tx4y1B75k) |
| 678 | 自编教材实操课程分享：第六章—常数传播 | - | AI 论文精读 | - | 4:01 | [link](https://www.bilibili.com/video/BV1Cw4m1C7t3) |
| 679 | 自编教材实操课程分享：第六章—传参优化 | - | AI 论文精读 | - | 4:14 | [link](https://www.bilibili.com/video/BV1NM4m1o7oH) |
| 680 | 自编教材实操课程分享：第六章—内联替换 | - | AI 论文精读 | - | 3:58 | [link](https://www.bilibili.com/video/BV1CC411j7Zz) |
| 681 | 自编教材实操课程分享：第六章—过程克隆 | - | AI 论文精读 | - | 4:36 | [link](https://www.bilibili.com/video/BV17y411Y7Wo) |
| 682 | 自编教材实操课程分享：第六章—全局变量优化 | - | AI 论文精读 | - | 3:22 | [link](https://www.bilibili.com/video/BV1vf421m7RY) |
| 683 | 自编教材实操课程分享：第六章—循环不变量外提 | - | AI 论文精读 | - | 11:06 | [link](https://www.bilibili.com/video/BV1nw4m1D7np) |
| 684 | 自编教材实操课程分享：第六章—循环合并 | - | AI 论文精读 | - | 12:30 | [link](https://www.bilibili.com/video/BV1k7421f77W) |
| 685 | 自编教材实操课程分享：第六章—循环分段 | - | AI 论文精读 | - | 6:46 | [link](https://www.bilibili.com/video/BV18z421Y7eR) |
| 686 | 自编教材实操课程分享：第六章—循环展开和压紧 | - | AI 论文精读 | - | 13:03 | [link](https://www.bilibili.com/video/BV1mx4y1H7ch) |
| 687 | 自编教材实操课程分享：第六章-循环分块 | - | AI 论文精读 | - | 9:19 | [link](https://www.bilibili.com/video/BV1sJ4m137o2) |
| 688 | 自编教材实操课程分享：第六章—循环交换 | - | AI 论文精读 | - | 17:54 | [link](https://www.bilibili.com/video/BV1zx4y1n7fe) |
| 689 | 自编教材实操课程分享：第六章—循环分裂 | - | AI 论文精读 | - | 8:29 | [link](https://www.bilibili.com/video/BV1Et421N7E5) |
| 690 | 自编教材实操课程分享：第六章—循环倾斜 | - | AI 论文精读 | - | 7:58 | [link](https://www.bilibili.com/video/BV1J4421X7Zm) |
| 691 | 自编教材实操课程分享：第六章—循环分布 | - | AI 论文精读 | - | 12:38 | [link](https://www.bilibili.com/video/BV16S411K7Zv) |
| 692 | 自编教材实操课程分享：第六章—删除冗余语句 | - | AI 论文精读 | - | 9:39 | [link](https://www.bilibili.com/video/BV1Bx4y1J7Uq) |
| 693 | 自编教材实操课程分享：第六章—代数变换 | - | AI 论文精读 | - | 11:04 | [link](https://www.bilibili.com/video/BV1G7421d7FB) |
| 694 | 自编教材实操课程分享：第六章—公共子表达式优化 | - | AI 论文精读 | - | 4:42 | [link](https://www.bilibili.com/video/BV1Nr421w7DW) |
| 695 | 自编教材实操课程分享：第六章—合并判断条件 | - | AI 论文精读 | - | 4:42 | [link](https://www.bilibili.com/video/BV1n4421Q7H8) |
| 696 | 自编教材实操课程分享：第六章—生成选择指令 | - | AI 论文精读 | - | 4:41 | [link](https://www.bilibili.com/video/BV1px4y1J7mR) |
| 697 | 自编教材实操课程分享：第七章—指令流水 | - | AI 论文精读 | - | 10:30 | [link](https://www.bilibili.com/video/BV1dx4y147fD) |
| 698 | 自编教材实操课程分享：第七章—超长指令字 | - | AI 论文精读 | - | 4:34 | [link](https://www.bilibili.com/video/BV1Nf421z7Yy) |
| 699 | 自编教材实操课程分享：第七章—函数的向量化 | - | AI 论文精读 | - | 3:56 | [link](https://www.bilibili.com/video/BV1Uw4m1e7PE) |
| 700 | 自编教材实操课程分享：第七章—基本块的向量化 | - | AI 论文精读 | - | 6:07 | [link](https://www.bilibili.com/video/BV1A4421X7ov) |
| 701 | 自编教材实操课程分享：第七章—循环的向量化 | - | AI 论文精读 | - | 11:04 | [link](https://www.bilibili.com/video/BV1gZ421M7UP) |
| 702 | 自编教材实操课程分享：第六章—分支语句优化之运用条件编译 | - | AI 论文精读 | - | 5:47 | [link](https://www.bilibili.com/video/BV18Z421T7Tx) |
| 703 | 自编教材实操课程分享：第六章—分支语句优化之移除分支语句 | - | AI 论文精读 | - | 4:37 | [link](https://www.bilibili.com/video/BV1Bb421E7yE) |
| 704 | 自编教材实操课程分享：第七章—分支向量化 | - | AI 论文精读 | - | 9:54 | [link](https://www.bilibili.com/video/BV1ES421R7BC) |
| 705 | 自编教材实操课程分享：第七章—归约向量化 | - | AI 论文精读 | - | 4:26 | [link](https://www.bilibili.com/video/BV1Q4421U7UR) |
| 706 | 自编教材实操课程分享：第七章—不对齐访存 | - | AI 论文精读 | - | 11:36 | [link](https://www.bilibili.com/video/BV1cZ421u7oX) |
| 707 | 自编教材实操课程分享：第七章—不连续访存 | - | AI 论文精读 | - | 12:28 | [link](https://www.bilibili.com/video/BV1yS411c7nC) |
| 708 | 自编教材实操课程分享：第七章—向量运算融合 | - | AI 论文精读 | - | 4:09 | [link](https://www.bilibili.com/video/BV1gy411i7cL) |
| 709 | 自编教材实操课程分享：第七章—向量重用 | - | AI 论文精读 | - | 7:49 | [link](https://www.bilibili.com/video/BV1Pw4m1Y7nH) |
| 710 | 自编教材实操课程分享：第七章—循环完全展开 | - | AI 论文精读 | - | 3:46 | [link](https://www.bilibili.com/video/BV12H4y1w7cK) |
| 711 | 自编教材实操课程分享：第八章—寄存器分配 | - | AI 论文精读 | - | 16:12 | [link](https://www.bilibili.com/video/BV1kr421M7mc) |
| 712 | 自编教材实操课程分享：第八章—寄存器重用 | - | AI 论文精读 | - | 8:23 | [link](https://www.bilibili.com/video/BV1p142187Vu) |
| 713 | 自编教材实操课程分享：第八章—缓存分块 | - | AI 论文精读 | - | 15:43 | [link](https://www.bilibili.com/video/BV1o4421Z7Ld) |
| 714 | 自编教材实操课程分享：第八章—减少伪共享 | - | AI 论文精读 | - | 7:46 | [link](https://www.bilibili.com/video/BV1cZ421K7fz) |
| 715 | 自编教材实操课程分享：第八章—数据预取 | - | AI 论文精读 | - | 8:11 | [link](https://www.bilibili.com/video/BV1Jb421J7Fx) |
| 716 | 自编教材实操课程分享：第八章—减少内存读写 | - | AI 论文精读 | - | 7:45 | [link](https://www.bilibili.com/video/BV1amW8edE7Q) |
| 717 | 自编教材实操课程分享：第八章—数据对齐 | - | AI 论文精读 | - | 12:57 | [link](https://www.bilibili.com/video/BV1KCste1EQN) |
| 718 | 自编教材实操课程分享：第八章—多线程操作 | - | AI 论文精读 | - | 8:26 | [link](https://www.bilibili.com/video/BV1TksteLErP) |
| 719 | 自编教材实操课程分享：第八章—数组重组 | - | AI 论文精读 | - | 6:06 | [link](https://www.bilibili.com/video/BV1TksteLErM) |
| 720 | 自编教材实操课程分享：第八章—数组转置 | - | AI 论文精读 | - | 7:21 | [link](https://www.bilibili.com/video/BV18BHaeXECN) |
| 721 | 自编教材实操课程分享：第八章—结构属性域调整 | - | AI 论文精读 | - | 6:47 | [link](https://www.bilibili.com/video/BV1hqHaeWETX) |
| 722 | 自编教材实操课程分享：第八章—结构体拆分 | - | AI 论文精读 | - | 7:01 | [link](https://www.bilibili.com/video/BV18qHaeWEkd) |
| 723 | 自编教材实操课程分享：第八章—结构体数组转换 | - | AI 论文精读 | - | 6:33 | [link](https://www.bilibili.com/video/BV1wG4henEyc) |
| 724 | 自编教材实操课程分享：第九章—OpenMP程序编写 | - | AI 论文精读 | - | 8:23 | [link](https://www.bilibili.com/video/BV19ntJeMEpD) |
| 725 | 自编教材实操课程分享：第九章—OpenMP版矩阵乘 | - | AI 论文精读 | - | 7:39 | [link](https://www.bilibili.com/video/BV1hstJeeEpc) |
| 726 | 自编教材实操课程分享：第九章—并行区扩张 | - | AI 论文精读 | - | 14:59 | [link](https://www.bilibili.com/video/BV1its8eYEQh) |
| 727 | 自编教材实操课程分享：第九章—并行区合并 | - | AI 论文精读 | - | 14:09 | [link](https://www.bilibili.com/video/BV1qts8eYEiH) |
| 728 | 自编教材实操课程分享：第九章—数据填充避免伪共享 | - | AI 论文精读 | - | 10:12 | [link](https://www.bilibili.com/video/BV1Z4s8eAEp9) |
| 729 | 自编教材实操课程分享：第九章—循环向量化 | - | AI 论文精读 | - | 9:37 | [link](https://www.bilibili.com/video/BV1hjxWe6EDy) |
| 730 | 自编教材实操课程分享：第九章—循环嵌套合并调度 | - | AI 论文精读 | - | 15:13 | [link](https://www.bilibili.com/video/BV13jxWe6EAP) |
| 731 | 自编教材实操课程分享：第九章—线程调度配置策略 | - | AI 论文精读 | - | 15:50 | [link](https://www.bilibili.com/video/BV1bh2tYJEq3) |
| 732 | 自编教材实操课程分享：第九章—串并行切换 | - | AI 论文精读 | - | 10:41 | [link](https://www.bilibili.com/video/BV1ub2tYDEXm) |
| 733 | 自编教材实操课程分享：第九章—线程数设置优化 | - | AI 论文精读 | - | 14:26 | [link](https://www.bilibili.com/video/BV1qM2ZY2EwV) |
| 734 | 自编教材实操课程分享：第九章—分析隐式同步 | - | AI 论文精读 | - | 6:58 | [link](https://www.bilibili.com/video/BV1K9yGYaEAs) |
| 735 | 自编教材实操课程分享：第九章—消除隐式同步 | - | AI 论文精读 | - | 12:41 | [link](https://www.bilibili.com/video/BV1N9yGYhEea) |
| 736 | 自编教材实操课程分享：第九章—流水并行示例 | - | AI 论文精读 | - | 9:42 | [link](https://www.bilibili.com/video/BV1sUS8YxEJ3) |
| 737 | 自编教材实操课程分享：第九章—流水并行粒度 | - | AI 论文精读 | - | 15:38 | [link](https://www.bilibili.com/video/BV1qNShYyE4f) |
| 738 | 自编教材实操课程分享：第十章—CUDA程序编写 | - | AI 论文精读 | - | 6:52 | [link](https://www.bilibili.com/video/BV1j8DSYPEpp) |
| 739 | 自编教材实操课程分享：第十章—线程结构优化 | - | AI 论文精读 | - | 8:08 | [link](https://www.bilibili.com/video/BV1aoDUYoEoq) |
| 740 | 自编教材实操课程分享：第十章—分支优化 | - | AI 论文精读 | - | 6:42 | [link](https://www.bilibili.com/video/BV1unmDYEELs) |
| 741 | 自编教材实操课程分享：第十章—访存优化(1) | - | AI 论文精读 | - | 6:34 | [link](https://www.bilibili.com/video/BV1unmDYEEMA) |
| 742 | 自编教材实操课程分享：第十章—访存优化(2) | - | AI 论文精读 | - | 6:21 | [link](https://www.bilibili.com/video/BV1AGBxYLEjh) |
| 743 | 自编教材实操课程分享：第十章—数据预取 | - | AI 论文精读 | - | 5:06 | [link](https://www.bilibili.com/video/BV11PBxYSEot) |
| 744 | 自编教材实操课程分享：第十章—循环展开 | - | AI 论文精读 | - | 3:44 | [link](https://www.bilibili.com/video/BV1mABxYHEim) |
| 745 | 人工智能编译器MLIR-官方入门教程讲解 | - | AI 论文精读 | - | 60:39 | [link](https://www.bilibili.com/video/BV1Hd4y1U7mb) |
| 746 | 深度学习编译发展概述 | - | AI 论文精读 | - | 16:31 | [link](https://www.bilibili.com/video/BV1zd4y1K7MQ) |
| 747 | 深度学习编译系统概述 | - | AI 论文精读 | - | 34:37 | [link](https://www.bilibili.com/video/BV1kS4y1t7JH) |
| 748 | 深度学习框架发展（一） | - | AI 论文精读 | - | 15:12 | [link](https://www.bilibili.com/video/BV1iD4y117td) |
| 749 | 深度学习框架发展（二） | - | AI 论文精读 | - | 13:00 | [link](https://www.bilibili.com/video/BV1dt4y1F7Cn) |
| 750 | 深度学习框架发展（三） | - | AI 论文精读 | - | 14:20 | [link](https://www.bilibili.com/video/BV1Qe4y1z78o) |
| 751 | 深度学习硬件平台 | - | AI 论文精读 | - | 13:05 | [link](https://www.bilibili.com/video/BV1JY411Q72M) |
| 752 | 深度学习自动微分：什么是自动微分 | - | AI 论文精读 | - | 10:55 | [link](https://www.bilibili.com/video/BV1fs4y197km) |
| 753 | HIP代码自动生成工具C2HIPC | - | AI 论文精读 | - | 9:53 | [link](https://www.bilibili.com/video/BV1Jg411Q7z6) |
| 754 | 循环优化（一）：循环展开和压紧 | - | AI 论文精读 | - | 12:54 | [link](https://www.bilibili.com/video/BV1HB4y1x7zv) |
| 755 | 循环优化（二）：循环合并 | - | AI 论文精读 | - | 11:16 | [link](https://www.bilibili.com/video/BV1CD4y1B7H2) |
| 756 | 循环优化（三）：循环分布 | - | AI 论文精读 | - | 9:29 | [link](https://www.bilibili.com/video/BV1Z8411t7dC) |
| 757 | 循环优化（四）：循环交换 | - | AI 论文精读 | - | 9:13 | [link](https://www.bilibili.com/video/BV13d4y1C7ca) |
| 758 | 循环优化（五）：循环不变量外提 | - | AI 论文精读 | - | 14:23 | [link](https://www.bilibili.com/video/BV1Ud4y1b7Zc) |
| 759 | 循环优化（六）：循环分段 | - | AI 论文精读 | - | 5:55 | [link](https://www.bilibili.com/video/BV1Zs4y1s7zn) |
| 760 | 循环优化（七）：循环分块 | - | AI 论文精读 | - | 11:23 | [link](https://www.bilibili.com/video/BV1gv4y1Y7ed) |
| 761 | 循环优化（八）：循环分裂 | - | AI 论文精读 | - | 6:29 | [link](https://www.bilibili.com/video/BV1mb411f7wK) |
| 762 | 循环优化（九）：循环倾斜 | - | AI 论文精读 | - | 13:30 | [link](https://www.bilibili.com/video/BV1uV4y1f7cJ) |
| 763 | 你知道吗，C语言最初被称为New B语言？ | - | AI 论文精读 | - | 8:57 | [link](https://www.bilibili.com/video/BV1Rp4y1c7k3) |
| 764 | 推理出企鹅会飞的编程语言——Prolog | - | AI 论文精读 | - | 8:16 | [link](https://www.bilibili.com/video/BV1BF411S7Sy) |
| 765 | 雷军：我写的代码像诗一样。Ruby：用我可以像写散文一样快乐写代码！ | - | AI 论文精读 | - | 10:39 | [link](https://www.bilibili.com/video/BV1Cp4y1w7a6) |
| 766 | LISP从括号出发，曲线救国的编程之路 | - | AI 论文精读 | - | 6:19 | [link](https://www.bilibili.com/video/BV1x84y1U7eD) |
| 767 | go，一门丑到无法形容的语言 | - | AI 论文精读 | - | 7:53 | [link](https://www.bilibili.com/video/BV1nu41137NZ) |
| 768 | Forth:一门不同于其他任何语言的编程语言 | - | AI 论文精读 | - | 6:52 | [link](https://www.bilibili.com/video/BV1m84y1D7bm) |
| 769 | 汇编语言：在我面前，所有高级编程语言都是小弟 | - | AI 论文精读 | - | 7:43 | [link](https://www.bilibili.com/video/BV1tu411376J) |
| 770 | COBOL：编程界的上古语言 | - | AI 论文精读 | - | 6:42 | [link](https://www.bilibili.com/video/BV158411C7zX) |
| 771 | ALGOL60:编程领域的带头大哥 | - | AI 论文精读 | - | 7:25 | [link](https://www.bilibili.com/video/BV1qh4y1h7UW) |
| 772 | 图算融合论文分享：Apollo | - | AI 论文精读 | - | 9:33 | [link](https://www.bilibili.com/video/BV1Do4y1L7Xd) |
| 773 | 算子调度优化论文分享：Rammer | - | AI 论文精读 | - | 10:35 | [link](https://www.bilibili.com/video/BV1LM411u7nE) |
| 774 | 动态shape深度学习算子自动调优论文分享：DietCode | - | AI 论文精读 | - | 14:45 | [link](https://www.bilibili.com/video/BV1RP4y167P4) |
| 775 | 动态shape深度学习编译器论文分享：DISC | - | AI 论文精读 | - | 14:26 | [link](https://www.bilibili.com/video/BV16R4y1U7J5) |
| 776 | Astitch：机器学习访存密集计算编译优化框架 | - | AI 论文精读 | - | 10:28 | [link](https://www.bilibili.com/video/BV1Ev4y1Q7L4) |
| 777 | 深度学习编译接口FreeTensor | - | AI 论文精读 | - | 15:53 | [link](https://www.bilibili.com/video/BV1uV4y1M7dQ) |
| 778 | 基于MLIR的GPU代码生成论文分享 | - | AI 论文精读 | - | 32:28 | [link](https://www.bilibili.com/video/BV1ga411N736) |
| 779 | 论文分享：计算图优化Welder | - | AI 论文精读 | - | 10:30 | [link](https://www.bilibili.com/video/BV1Tu4y1y7hN) |
| 780 | 论文分享：动态控制流编译优化Cocktailer | - | AI 论文精读 | - | 13:11 | [link](https://www.bilibili.com/video/BV1Kh4y1P7Rg) |
| 781 | 论文分享：动态神经网络编译优化BrainStorm | - | AI 论文精读 | - | 7:25 | [link](https://www.bilibili.com/video/BV1FC4y1R7pu) |
| 782 | 论文分享：计算密集型算子融合Chimera | - | AI 论文精读 | - | 10:05 | [link](https://www.bilibili.com/video/BV1Y6421G7kL) |
| 783 | 代码加速黑科技：GraalNN如何让程序性能飞跃 | - | AI 论文精读 | - | 9:32 | [link](https://www.bilibili.com/video/BV1m7JizLEC3) |
| 784 | CoServe：解锁 CoE 模型有限内存推理新路径 | - | AI 论文精读 | - | 8:33 | [link](https://www.bilibili.com/video/BV17kJLzBEF2) |
| 785 | PAPI：从静态到动态，异构PIM如何解锁LLM解码的“智能调度”新纪元 | - | AI 论文精读 | - | 11:29 | [link](https://www.bilibili.com/video/BV1d2Tjz6EtD) |
| 786 | CIM-MLC：从芯片到行级，解锁存算一体的编译新范式 | - | AI 论文精读 | - | 20:30 | [link](https://www.bilibili.com/video/BV1aKTvzDEdd) |
| 787 | 论文分享QiMeng-Xpiler：神经符号融合的异构深度学习系统张量程序跨平台转编译方案 | - | AI 论文精读 | - | 9:51 | [link](https://www.bilibili.com/video/BV1PopNzFEuH) |
| 788 | 论文分享UniNDP：面向Near DRAM处理架构的统一编译与仿真工具 | - | AI 论文精读 | - | 6:48 | [link](https://www.bilibili.com/video/BV1kfpNzoEjX) |
| 789 | 编译器自动调优论文分享：破解编译优化组合爆炸，协同搜索助力快速寻优 | - | AI 论文精读 | - | 7:13 | [link](https://www.bilibili.com/video/BV1y9pNzcEiL) |
| 790 | 论文分享ANT-ACE：实现神经网络推理自动化的全同态加密编译器框架 | - | AI 论文精读 | - | 8:02 | [link](https://www.bilibili.com/video/BV1A5nwz5EwS) |
| 791 | 论文分享HALO：面向全同态加密的循环感知自举管理 | - | AI 论文精读 | - | 9:38 | [link](https://www.bilibili.com/video/BV1vhnwzaENX) |
| 792 | 论文分享Gated Attention：用极小代价换来大模型性能飞升 | - | AI 论文精读 | - | 10:24 | [link](https://www.bilibili.com/video/BV1nGFVzQEAh) |
| 793 | 论文分享TempSamp-R1：用混合采样强化视频大模型时序定位 | - | AI 论文精读 | - | 10:18 | [link](https://www.bilibili.com/video/BV1QVKb6mEFm) |
| 794 | 论文分享 FlashInfer：面向大模型推理服务的高效 Attention 引擎 | - | AI 论文精读 | - | 9:36 | [link](https://www.bilibili.com/video/BV1QKgQ6xEgh) |
| 795 | 论文分享 CAKE：面向长上下文大模型的自适应 KV Cache 淘汰框架 | - | AI 论文精读 | - | 21:21 | [link](https://www.bilibili.com/video/BV16w3a6HEfe) |
| 796 | 01 课程介绍 | - | AI 论文精读 | - | 1:57 | [link](https://www.bilibili.com/video/BV16BGbzAEq2) |
| 797 | 01 神经网络基础 | - | AI 论文精读 | - | 12:59 | [link](https://www.bilibili.com/video/BV1cBGbzPE3T) |
| 798 | 02 深度学习的进化 | - | AI 论文精读 | - | 12:01 | [link](https://www.bilibili.com/video/BV1cBGbzPEKk) |
| 799 | 03 大语言模型 | - | AI 论文精读 | - | 8:26 | [link](https://www.bilibili.com/video/BV1cBGbzPEb2) |
| 800 | 01 faster-RCNN算法原理 | - | AI 论文精读 | - | 8:52 | [link](https://www.bilibili.com/video/BV1rBGbzAEFS) |
| 801 | 02 fasterRCNN实战 | - | AI 论文精读 | - | 12:41 | [link](https://www.bilibili.com/video/BV16BGbzAEtd) |
| 802 | 03 YOLOv11实战 | - | AI 论文精读 | - | 5:47 | [link](https://www.bilibili.com/video/BV1cBGbzPEb1) |
| 803 | 01 文本情感分类实战_1 | - | AI 论文精读 | - | 9:24 | [link](https://www.bilibili.com/video/BV1rBGbzAE5P) |
| 804 | 02 文本情感分类实战_2 | - | AI 论文精读 | - | 16:55 | [link](https://www.bilibili.com/video/BV1FBGbzPEoQ) |
| 805 | 01 大模型预训练基础_1 | - | AI 论文精读 | - | 7:39 | [link](https://www.bilibili.com/video/BV16BGbzAEbA) |
| 806 | 02 大模型预训练基础_2 | - | AI 论文精读 | - | 9:39 | [link](https://www.bilibili.com/video/BV1aRGbzHEmA) |
| 807 | 01 数据准备_1 | - | AI 论文精读 | - | 9:43 | [link](https://www.bilibili.com/video/BV1XRGbzHECt) |
| 808 | 02 数据准备_2 | - | AI 论文精读 | - | 11:16 | [link](https://www.bilibili.com/video/BV1YRGbzHEgK) |
| 809 | 03 模型结构_1 | - | AI 论文精读 | - | 13:19 | [link](https://www.bilibili.com/video/BV1GRGbzpEyR) |
| 810 | 04 模型结构_2 | - | AI 论文精读 | - | 14:58 | [link](https://www.bilibili.com/video/BV1YRGbzHE5h) |
| 811 | 01 预训练任务实现 | - | AI 论文精读 | - | 9:10 | [link](https://www.bilibili.com/video/BV1XRGbzHEXj) |
| 812 | 02 训练优化_1 | - | AI 论文精读 | - | 10:48 | [link](https://www.bilibili.com/video/BV1YRGbzHEWn) |
| 813 | 03 训练优化_2 | - | AI 论文精读 | - | 11:25 | [link](https://www.bilibili.com/video/BV1aRGbzHEBG) |
| 814 | 01 性能评估 | - | AI 论文精读 | - | 15:31 | [link](https://www.bilibili.com/video/BV1YRGbzHEcL) |
| 815 | 01 课程介绍 | - | AI 论文精读 | - | 1:02 | [link](https://www.bilibili.com/video/BV1gMjBzJE1B) |
| 816 | 01 大模型微调概述 | - | AI 论文精读 | - | 10:23 | [link](https://www.bilibili.com/video/BV1gMjBzJEDw) |
| 817 | 01 模型数据收集与处理 | - | AI 论文精读 | - | 14:32 | [link](https://www.bilibili.com/video/BV1gMjBzJEP9) |
| 818 | 01 数据预处理理论 | - | AI 论文精读 | - | 10:54 | [link](https://www.bilibili.com/video/BV1gMjBzJEap) |
| 819 | 02 启发式规则 | - | AI 论文精读 | - | 15:31 | [link](https://www.bilibili.com/video/BV1gMjBzJEEM) |
| 820 | 03 评估模型过滤(1) | - | AI 论文精读 | - | 13:30 | [link](https://www.bilibili.com/video/BV1DMjBzJEm9) |
| 821 | 04 评估模型过滤(2) | - | AI 论文精读 | - | 9:46 | [link](https://www.bilibili.com/video/BV1gMjBzJEPy) |
| 822 | 05 完全匹配去重 | - | AI 论文精读 | - | 18:28 | [link](https://www.bilibili.com/video/BV1hMjBzJENe) |
| 823 | 06 近似匹配去重(1) | - | AI 论文精读 | - | 11:18 | [link](https://www.bilibili.com/video/BV18MjBzJEY6) |
| 824 | 07 近似匹配去重(2) | - | AI 论文精读 | - | 10:22 | [link](https://www.bilibili.com/video/BV1gMjBzJESX) |
| 825 | 01 大模型微调工具与主流框架介绍 | - | AI 论文精读 | - | 19:17 | [link](https://www.bilibili.com/video/BV1c4jBzTEto) |
| 826 | 02 微调框架实战(1) | - | AI 论文精读 | - | 11:40 | [link](https://www.bilibili.com/video/BV1c4jBzTEpJ) |
| 827 | 03 微调框架实战(2) | - | AI 论文精读 | - | 15:23 | [link](https://www.bilibili.com/video/BV1wsjBzBE9p) |
| 828 | 01 微调方法(1) | - | AI 论文精读 | - | 10:04 | [link](https://www.bilibili.com/video/BV1wsjBzBEGW) |
| 829 | 02 微调方法(2) | - | AI 论文精读 | - | 12:48 | [link](https://www.bilibili.com/video/BV1wsjBzBEKA) |
| 830 | 01 人类对齐 | - | AI 论文精读 | - | 9:08 | [link](https://www.bilibili.com/video/BV1x7jBzVEbX) |
| 831 | 01 大模型评估与问题解决(1) | - | AI 论文精读 | - | 11:09 | [link](https://www.bilibili.com/video/BV1K7jBzVEFv) |
| 832 | 02 大模型评估与问题解决(2) | - | AI 论文精读 | - | 11:28 | [link](https://www.bilibili.com/video/BV1mLjBzyEAc) |
| 833 | 01 法律大模型强化学习实战 | - | AI 论文精读 | - | 17:38 | [link](https://www.bilibili.com/video/BV1WnjBz3Eip) |
| 834 | 02 法律大模型评估实战(1) | - | AI 论文精读 | - | 12:09 | [link](https://www.bilibili.com/video/BV1NnjBz3ETP) |
| 835 | 03 法律大模型评估实战(2) | - | AI 论文精读 | - | 10:36 | [link](https://www.bilibili.com/video/BV1PnjBz3ELn) |
| 836 | 课程介绍 | - | AI 论文精读 | - | 1:42 | [link](https://www.bilibili.com/video/BV1SkLtzHEkT) |
| 837 | 01 大模型推理挑战 | - | AI 论文精读 | - | 4:14 | [link](https://www.bilibili.com/video/BV1SkLtzHEdH) |
| 838 | 02 主流推理引擎对比 | - | AI 论文精读 | - | 6:08 | [link](https://www.bilibili.com/video/BV1gkLtzpEBa) |
| 839 | 03 大模型推理瓶颈分析 | - | AI 论文精读 | - | 17:46 | [link](https://www.bilibili.com/video/BV1DkLtzHEpD) |
| 840 | 01 vLLM环境搭建 | - | AI 论文精读 | - | 5:02 | [link](https://www.bilibili.com/video/BV1SkLtzHEDo) |
| 841 | 02 vLLM使用入门 | - | AI 论文精读 | - | 11:16 | [link](https://www.bilibili.com/video/BV1SkLtzHE2h) |
| 842 | 03 vLLM推理分析 | - | AI 论文精读 | - | 3:33 | [link](https://www.bilibili.com/video/BV1DkLtzHEF1) |
| 843 | 01 LoRA模型部署及实操 | - | AI 论文精读 | - | 18:10 | [link](https://www.bilibili.com/video/BV1gkLtzpEL4) |
| 844 | 02 多模态模型部署及实操 | - | AI 论文精读 | - | 13:43 | [link](https://www.bilibili.com/video/BV1gkLtzpEkd) |
| 845 | 01 vLLM量化模型支持 | - | AI 论文精读 | - | 3:44 | [link](https://www.bilibili.com/video/BV18kLtzpEZq) |
| 846 | 02 模型量化 | - | AI 论文精读 | - | 19:06 | [link](https://www.bilibili.com/video/BV1U1LtzJEWP) |
| 847 | 03 KV Cache量化 | - | AI 论文精读 | - | 9:04 | [link](https://www.bilibili.com/video/BV1U1LtzJEaX) |
| 848 | 01 性能测试指标(1) | - | AI 论文精读 | - | 15:43 | [link](https://www.bilibili.com/video/BV1U1LtzJEEB) |
| 849 | 02 性能测试指标(2) | - | AI 论文精读 | - | 13:16 | [link](https://www.bilibili.com/video/BV1U1LtzJE5V) |
| 850 | 03 性能测试工具 | - | AI 论文精读 | - | 4:55 | [link](https://www.bilibili.com/video/BV1M1LtznEme) |
| 851 | 04 性能分析 | - | AI 论文精读 | - | 8:52 | [link](https://www.bilibili.com/video/BV1S1LtznEM8) |
| 852 | 01 算子优化 | - | AI 论文精读 | - | 11:42 | [link](https://www.bilibili.com/video/BV1t1LtzEE1f) |
| 853 | 01 LLM引擎参数(1) | - | AI 论文精读 | - | 13:41 | [link](https://www.bilibili.com/video/BV1GjL7z8EZo) |
| 854 | 02 LLM引擎参数(2) | - | AI 论文精读 | - | 11:11 | [link](https://www.bilibili.com/video/BV19jL7zbEV7) |
| 855 | 03 推测解码与PD分离 | - | AI 论文精读 | - | 8:55 | [link](https://www.bilibili.com/video/BV1XjL7zbE4o) |
| 856 | 01 DeepSeek可视化部署(1) | - | AI 论文精读 | - | 13:25 | [link](https://www.bilibili.com/video/BV1wmjjzVEFC) |
| 857 | 02 DeepSeek可视化部署(2) | - | AI 论文精读 | - | 13:00 | [link](https://www.bilibili.com/video/BV1wmjjzVEFf) |
| 858 | 01 RAG本地部署(1) | - | AI 论文精读 | - | 16:47 | [link](https://www.bilibili.com/video/BV1A1jjzyELv) |
| 859 | 02 RAG本地部署(2) | - | AI 论文精读 | - | 20:33 | [link](https://www.bilibili.com/video/BV1w1jjzyEsX) |
| 860 | 01 vLLM+Dify构建Agent应用(1) | - | AI 论文精读 | - | 17:42 | [link](https://www.bilibili.com/video/BV1p1jjzyEhT) |
| 861 | 02 vLLM+Dify构建Agent应用(2) | - | AI 论文精读 | - | 13:29 | [link](https://www.bilibili.com/video/BV1C1jjzyEFA) |
| 862 | 03 vLLM+Dify构建Agent应用(3) | - | AI 论文精读 | - | 16:11 | [link](https://www.bilibili.com/video/BV1H1jjzyE9U) |
| 863 | 【AI实操 · 优化篇】01 Triton在PyTorch中的角色 | - | AI 论文精读 | - | 32:21 | [link](https://www.bilibili.com/video/BV1ZoRPYQE2K) |
| 864 | 【AI实操 · 优化篇】02 内核性能分析工具 | - | AI 论文精读 | - | 54:50 | [link](https://www.bilibili.com/video/BV1ZUQ1YtEwP) |
| 865 | 【AI实操 · 优化篇】03 Triton编译器及Pass管理器 | - | AI 论文精读 | - | 27:35 | [link](https://www.bilibili.com/video/BV1VYQdYJEBb) |
| 866 | 【AI实操 · 优化篇】04 Triton算子关键参数优化 | - | AI 论文精读 | - | 34:33 | [link](https://www.bilibili.com/video/BV1miotY3E2D) |
| 867 | 【AI实操 · 优化篇】05 Triton算子开发 | - | AI 论文精读 | - | 53:42 | [link](https://www.bilibili.com/video/BV193fFYkE7P) |
| 868 | 【AI实操 · 优化篇】06 Triton访存合并解析 | - | AI 论文精读 | - | 33:56 | [link](https://www.bilibili.com/video/BV1j6dRY8Erc) |
| 869 | 【AI实操 · 优化篇】07 Triton布局介绍 | - | AI 论文精读 | - | 43:48 | [link](https://www.bilibili.com/video/BV1F45HzLEHo) |
| 870 | 【AI实操 · 优化篇】08 Triton访存合并优化 | - | AI 论文精读 | - | 21:52 | [link](https://www.bilibili.com/video/BV1gzL2zTEq7) |
| 871 | 【AI实操 · 优化篇】09 编译优化实践(一)：代数变换 | - | AI 论文精读 | - | 23:21 | [link](https://www.bilibili.com/video/BV1UQEjz4EzX) |
| 872 | 【AI实操 · 优化篇】10 编译优化实践(二)：冗余去除 | - | AI 论文精读 | - | 16:41 | [link](https://www.bilibili.com/video/BV14TEczGE4i) |
| 873 | 【AI实操 · 优化篇】11 Triton归约操作解析 | - | AI 论文精读 | - | 50:01 | [link](https://www.bilibili.com/video/BV16fj8zGEjD) |
| 874 | 【AI实操 · 优化篇】12 Triton MMA操作解析：Tensor Core & MMA指令 | - | AI 论文精读 | - | 33:06 | [link](https://www.bilibili.com/video/BV1LnTszhEdY) |
| 875 | 【AI实操 · 优化篇】13 Triton MMA操作解析：Pipeline & Prefetch | - | AI 论文精读 | - | 35:15 | [link](https://www.bilibili.com/video/BV1vyN1zmEVG) |
| 876 | 深度学习模型压缩概述 | - | AI 论文精读 | - | 14:25 | [link](https://www.bilibili.com/video/BV1ht4y1P73i) |
| 877 | 无数据模型量化论文分享：ZeroQ | - | AI 论文精读 | - | 10:23 | [link](https://www.bilibili.com/video/BV1614y1T7FS) |
| 878 | 深度学习模型压缩方法（一）：模型蒸馏 | - | AI 论文精读 | - | 12:30 | [link](https://www.bilibili.com/video/BV1eb411971p) |
| 879 | 深度学习模型压缩方法（二）：剪枝 | - | AI 论文精读 | - | 11:21 | [link](https://www.bilibili.com/video/BV1pg4y1J73p) |
| 880 | 深度学习模型压缩方法（三）：量化 | - | AI 论文精读 | - | 11:14 | [link](https://www.bilibili.com/video/BV1bL411U747) |
| 881 | LLVM编译器入门（一）：LLVM整体设计 | - | AI 论文精读 | - | 13:40 | [link](https://www.bilibili.com/video/BV18j411B7TF) |
| 882 | LLVM编译器入门（二）：Clang前端 | - | AI 论文精读 | - | 12:35 | [link](https://www.bilibili.com/video/BV11j411B7XZ) |
| 883 | LLVM编译器入门（三）：IR优化 | - | AI 论文精读 | - | 14:53 | [link](https://www.bilibili.com/video/BV1fX4y1x79Y) |
| 884 | LLVM编译器入门（四）：代码生成 上 | - | AI 论文精读 | - | 15:33 | [link](https://www.bilibili.com/video/BV1tN411B71r) |
| 885 | LLVM编译器入门（五）：代码生成 下 | - | AI 论文精读 | - | 10:08 | [link](https://www.bilibili.com/video/BV1YG411o7AQ) |
| 886 | 基础篇：大语言模型推理发展 | - | AI 论文精读 | - | 5:42 | [link](https://www.bilibili.com/video/BV1v718BpEsV) |
| 887 | 核心篇：vLLM整体架构与请求预处理模块 | - | AI 论文精读 | - | 20:04 | [link](https://www.bilibili.com/video/BV1YcywBiEJ1) |
| 888 | 核心篇：vLLM 调度器模块 | - | AI 论文精读 | - | 19:08 | [link](https://www.bilibili.com/video/BV18tB8BFE1L) |
| 889 | 核心篇：vLLM 键值缓存管理器 | - | AI 论文精读 | - | 22:26 | [link](https://www.bilibili.com/video/BV1NhFjzTEKe) |
| 890 | 【AI论文救星】01 规划论文选题与结构 | - | AI 论文精读 | - | 2:29 | [link](https://www.bilibili.com/video/BV1NddtYvEb4) |
| 891 | 【AI论文救星】02 高效搜集整理文献 | - | AI 论文精读 | - | 2:11 | [link](https://www.bilibili.com/video/BV1FNdbYbE4b) |
| 892 | 【AI论文救星】03 可视化数据图表制作 | - | AI 论文精读 | - | 2:27 | [link](https://www.bilibili.com/video/BV1n3dgYrEcf) |
| 893 | 【AI论文救星】04 辅助写作与论文润色 | - | AI 论文精读 | - | 4:36 | [link](https://www.bilibili.com/video/BV1fKdbYoEm4) |
| 894 | 【AI论文救星】05 自动排版与文献格式规范 | - | AI 论文精读 | - | 1:40 | [link](https://www.bilibili.com/video/BV1PZdtYPEER) |
| 895 | 【AI论文救星】06 答辩PPT与讲稿生成 | - | AI 论文精读 | - | 3:30 | [link](https://www.bilibili.com/video/BV1kcdbYcEb6) |
| 896 | 【AI论文救星】07 毕业答辩问答模拟 | - | AI 论文精读 | - | 2:20 | [link](https://www.bilibili.com/video/BV1g6dAYzEiq) |
| 897 | 拥抱AI Agent~全网最详细的OpenManus本地部署教程 | - | AI 论文精读 | - | 7:45 | [link](https://www.bilibili.com/video/BV1w4XVY7Eou) |
| 898 | 突破常规！Julius 借 “交互式分析”，革新 AI 数据 | - | AI 论文精读 | - | 4:13 | [link](https://www.bilibili.com/video/BV1c7DfYPEgi) |
| 899 | 小白1分钟搞定！全网最详细的Deepseek的神仙级用法 | - | AI 论文精读 | - | 4:48 | [link](https://www.bilibili.com/video/BV1jb9iYMEBu) |
| 900 | 什么？？？马上开组会了~ PPT 还没做！ | - | AI 论文精读 | - | 3:13 | [link](https://www.bilibili.com/video/BV19aDfYXETT) |
| 901 | Deepseek+word打造会思考的智能文档 | - | AI 论文精读 | - | 5:26 | [link](https://www.bilibili.com/video/BV1ALQvY3E9a) |
| 902 | AI+Excel：如何让工作效率原地飞起 | - | AI 论文精读 | - | 5:32 | [link](https://www.bilibili.com/video/BV1JCQeYAEw8) |
| 903 | TVM简介 | - | AI 论文精读 | - | 14:59 | [link](https://www.bilibili.com/video/BV14N4y1c7zq) |
| 904 | TVM自动调度算法AutoTVM | - | AI 论文精读 | - | 14:46 | [link](https://www.bilibili.com/video/BV1114y1e7FK) |
| 905 | ANSOR：为深度学习生成高性能张量程序 | - | AI 论文精读 | - | 13:10 | [link](https://www.bilibili.com/video/BV1m14y1Y7LN) |
| 906 | TVM 编译流程与中间表示分析（一） | - | AI 论文精读 | - | 15:36 | [link](https://www.bilibili.com/video/BV1v3411U7fM) |
| 907 | TVM 编译流程与中间表示分析（二） | - | AI 论文精读 | - | 12:55 | [link](https://www.bilibili.com/video/BV1624y1v7wx) |
| 908 | ANSOR 优化算子代码解读（一） | - | AI 论文精读 | - | 12:51 | [link](https://www.bilibili.com/video/BV1ih4y127fX) |
| 909 | ANSOR优化算子代码解读（二） | - | AI 论文精读 | - | 6:56 | [link](https://www.bilibili.com/video/BV1C44y1c7WL) |
| 910 | ANSOR优化算子代码解读（三） | - | AI 论文精读 | - | 9:24 | [link](https://www.bilibili.com/video/BV1e94y167Qy) |
| 911 | ANSOR优化算子代码解读（四） | - | AI 论文精读 | - | 9:16 | [link](https://www.bilibili.com/video/BV1C8411X7BS) |
| 912 | TVM的量化框架（一） | - | AI 论文精读 | - | 10:37 | [link](https://www.bilibili.com/video/BV1ph4y1U7Dy) |
| 913 | TVM的量化框架（二） | - | AI 论文精读 | - | 5:44 | [link](https://www.bilibili.com/video/BV1aN4y1R7MY) |
| 914 | TVM的量化框架（三） | - | AI 论文精读 | - | 7:28 | [link](https://www.bilibili.com/video/BV1ur4y197zj) |
| 915 | TVM的量化框架（四） | - | AI 论文精读 | - | 10:52 | [link](https://www.bilibili.com/video/BV18w411S7Mh) |
| 916 | 自动并行论文分享：FlexFlow | - | AI 论文精读 | - | 15:52 | [link](https://www.bilibili.com/video/BV1wg411H78v) |
| 917 | 自动并行论文分享：CoCoNet | - | AI 论文精读 | - | 18:01 | [link](https://www.bilibili.com/video/BV1Nv4y1j78t) |
| 918 | 论文分享：新型注意力算法FlashAttention | - | AI 论文精读 | - | 7:24 | [link](https://www.bilibili.com/video/BV1zs4y1J7tb) |
| 919 | 自动并行—并行划分 | - | AI 论文精读 | - | 8:59 | [link](https://www.bilibili.com/video/BV1wo4y1L7WJ) |
| 920 | 数据并行通信优化论文分享：MG-WFBP | - | AI 论文精读 | - | 10:50 | [link](https://www.bilibili.com/video/BV1hj411Z7SS) |
| 921 | 自动并行论文分享：Merak | - | AI 论文精读 | - | 8:58 | [link](https://www.bilibili.com/video/BV1T94y1C7i4) |
| 922 | 论文分享：并行程序自动转换 | - | AI 论文精读 | - | 13:10 | [link](https://www.bilibili.com/video/BV1sa4y1C7p7) |
| 923 | 论文分享：自动并行AvgPipe | - | AI 论文精读 | - | 15:21 | [link](https://www.bilibili.com/video/BV1rw41137QG) |
| 924 | 论文分享：自动并行AlpaServe | - | AI 论文精读 | - | 17:28 | [link](https://www.bilibili.com/video/BV1wc411m7ki) |
| 925 | 论文分享：自动并行Alpa | - | AI 论文精读 | - | 15:25 | [link](https://www.bilibili.com/video/BV11j41177TQ) |
| 926 | 论文分享：高性能计算领域大语言模型HPC-Coder | - | AI 论文精读 | - | 12:46 | [link](https://www.bilibili.com/video/BV1e4421c7Gk) |
| 927 | 自编教材分享：第一章—程序性能优化的意义（一） | - | AI 论文精读 | - | 9:08 | [link](https://www.bilibili.com/video/BV1LL411B7uW) |
| 928 | 自编教材分享：第一章—程序性能优化的意义（二） | - | AI 论文精读 | - | 6:53 | [link](https://www.bilibili.com/video/BV15g4y1F7QQ) |
| 929 | 自编教材分享：第二章—程序性能的度量指标及优化流程（一） | - | AI 论文精读 | - | 12:03 | [link](https://www.bilibili.com/video/BV1vu411s7Xw) |
| 930 | 自编教材分享：第三章—程序性能的分析和测量（一） | - | AI 论文精读 | - | 13:36 | [link](https://www.bilibili.com/video/BV1ZV4y1U7wr) |
| 931 | 自编教材分享：第三章—程序性能的分析和测量（二） | - | AI 论文精读 | - | 15:50 | [link](https://www.bilibili.com/video/BV11k4y1p7Bw) |
| 932 | 自编教材分享：第三章—程序性能的分析和测量（三） | - | AI 论文精读 | - | 15:14 | [link](https://www.bilibili.com/video/BV1Wm4y1v7yZ) |
| 933 | 自编教材分享：第四章—系统配置优化（一） | - | AI 论文精读 | - | 11:31 | [link](https://www.bilibili.com/video/BV1go4y1K72Y) |
| 934 | 自编教材分享：第四章—系统配置优化（二） | - | AI 论文精读 | - | 9:39 | [link](https://www.bilibili.com/video/BV12o4y1P7kW) |
| 935 | 自编教材分享：第五章—编译与运行优化 | - | AI 论文精读 | - | 54:05 | [link](https://www.bilibili.com/video/BV1KN4y1L7XT) |
| 936 | 自编教材分享：第六章—程序编写优化（一） | - | AI 论文精读 | - | 10:11 | [link](https://www.bilibili.com/video/BV1gX4y1q7Ms) |
| 937 | 自编教材分享：第六章—程序编写优化（二） | - | AI 论文精读 | - | 9:01 | [link](https://www.bilibili.com/video/BV1Aj411S7kJ) |
| 938 | 自编教材分享：第六章—程序编写优化（三） | - | AI 论文精读 | - | 6:04 | [link](https://www.bilibili.com/video/BV1sg4y1N763) |
| 939 | 自编教材分享：第六章—程序编写优化（四） | - | AI 论文精读 | - | 9:29 | [link](https://www.bilibili.com/video/BV1rh411A79q) |
| 940 | 自编教材分享：第六章—程序编写优化（五） | - | AI 论文精读 | - | 8:11 | [link](https://www.bilibili.com/video/BV1mz4y1E7rb) |
| 941 | 自编教材分享：第七章—指令级并行（一） | - | AI 论文精读 | - | 9:03 | [link](https://www.bilibili.com/video/BV1iV4y1h7wm) |
| 942 | 自编教材分享：第七章—指令级并行（二） | - | AI 论文精读 | - | 8:14 | [link](https://www.bilibili.com/video/BV1ym4y1E783) |
| 943 | 自编教材分享：第七章—数据级并行（一） | - | AI 论文精读 | - | 13:28 | [link](https://www.bilibili.com/video/BV1M94y1q7B4) |
| 944 | 自编教材分享：第七章—数据级并行（二） | - | AI 论文精读 | - | 11:26 | [link](https://www.bilibili.com/video/BV1Wj411R74A) |
| 945 | 自编教材分享：第七章—数据级并行（三） | - | AI 论文精读 | - | 15:23 | [link](https://www.bilibili.com/video/BV1Kk4y1G77z) |
| 946 | 自编教材分享：第八章—访存优化（一） | - | AI 论文精读 | - | 7:21 | [link](https://www.bilibili.com/video/BV1yz4y1s7qp) |
| 947 | 自编教材分享：第八章—访存优化（二） | - | AI 论文精读 | - | 11:08 | [link](https://www.bilibili.com/video/BV1fM4y1H7Ba) |
| 948 | 自编教材分享：第八章—访存优化（三） | - | AI 论文精读 | - | 10:10 | [link](https://www.bilibili.com/video/BV18m4y1W7fH) |
| 949 | 自编教材分享：第八章—访存优化（四） | - | AI 论文精读 | - | 8:51 | [link](https://www.bilibili.com/video/BV1Np4y1776Z) |
| 950 | 自编教材分享：第八章—访存优化（五） | - | AI 论文精读 | - | 6:29 | [link](https://www.bilibili.com/video/BV1gw411D7Bw) |
| 951 | 自编教材分享：第八章—访存优化（六） | - | AI 论文精读 | - | 8:03 | [link](https://www.bilibili.com/video/BV1cp4y1j7ga) |
| 952 | 自编教材分享：第九章—OpenMP编程简介 | - | AI 论文精读 | - | 10:55 | [link](https://www.bilibili.com/video/BV1Zw411U7a8) |
| 953 | 自编教材分享：第九章—并行区重构 | - | AI 论文精读 | - | 9:04 | [link](https://www.bilibili.com/video/BV1eu411A79T) |
| 954 | 自编教材分享：第九章—向量化指导命令 | - | AI 论文精读 | - | 4:47 | [link](https://www.bilibili.com/video/BV12h4y1Y7vH) |
| 955 | 自编教材分享：第九章—避免伪共享 | - | AI 论文精读 | - | 7:04 | [link](https://www.bilibili.com/video/BV1Gw411i7rS) |
| 956 | 自编教材分享：第九章—负载均衡优化 | - | AI 论文精读 | - | 9:45 | [link](https://www.bilibili.com/video/BV1XN4y1o7NQ) |
| 957 | 自编教材分享：第九章—避免隐式同步 | - | AI 论文精读 | - | 6:34 | [link](https://www.bilibili.com/video/BV19u4y1x7CS) |
| 958 | 自编教材分享：第九章—流水并行优化 | - | AI 论文精读 | - | 13:24 | [link](https://www.bilibili.com/video/BV1LB4y1Z74v) |
| 959 | 自编教材分享：第十章—CUDA程序优化（一） | - | AI 论文精读 | - | 12:57 | [link](https://www.bilibili.com/video/BV1pB4y1f7Md) |
| 960 | 自编教材分享：第十章—CUDA程序优化（二） | - | AI 论文精读 | - | 13:50 | [link](https://www.bilibili.com/video/BV1C94y187iq) |
| 961 | 自编教材分享：第十章—CUDA程序优化（三） | - | AI 论文精读 | - | 14:50 | [link](https://www.bilibili.com/video/BV1Kw411z7Wd) |
| 962 | 自编教材分享：第十章—CUDA程序优化（四） | - | AI 论文精读 | - | 9:10 | [link](https://www.bilibili.com/video/BV1G84y1R7Ak) |
| 963 | 自编教材分享：第十一章—MPI程序简介 | - | AI 论文精读 | - | 7:17 | [link](https://www.bilibili.com/video/BV1cj411a7Sb) |
| 964 | 自编教材分享：第十一章—MPI程序简介（二） | - | AI 论文精读 | - | 7:08 | [link](https://www.bilibili.com/video/BV1ra4y1m7JP) |
| 965 | 自编教材分享：第十一章—数据划分优化 | - | AI 论文精读 | - | 12:15 | [link](https://www.bilibili.com/video/BV1Lc411b7Fw) |
| 966 | 深度学习的产生与发展 | - | AI 论文精读 | - | 13:35 | [link](https://www.bilibili.com/video/BV1AM411P7JG) |
| 967 | 深度神经网络的结构 | - | AI 论文精读 | - | 10:35 | [link](https://www.bilibili.com/video/BV1bD4y1G7oV) |
| 968 | 神经网络的运行机制 | - | AI 论文精读 | - | 10:59 | [link](https://www.bilibili.com/video/BV1xs4y1b7nt) |
| 969 | CNN-卷积神经网络（一） | - | AI 论文精读 | - | 12:51 | [link](https://www.bilibili.com/video/BV1iL411o7iz) |
| 970 | CNN-卷积神经网络（二） | - | AI 论文精读 | - | 10:54 | [link](https://www.bilibili.com/video/BV1bL411o74W) |
| 971 | 【直播回放】FlagOS开源社区“高性能计算实训营” 2025年08月16日09点场 | - | AI 论文精读 | - | 271:31 | [link](https://www.bilibili.com/video/BV18XYnzVEWa) |
| 972 | 【直播回放】FlagOS开源社区“高性能计算实训营” 2025年08月16日14点场 | - | AI 论文精读 | - | 206:54 | [link](https://www.bilibili.com/video/BV1bXYnzVEQV) |
| 973 | 【直播回放】FlagOS开源社区“高性能计算实训营” 2025年08月17日08点场 | - | AI 论文精读 | - | 234:06 | [link](https://www.bilibili.com/video/BV18XYnzVEJv) |
| 974 | 【直播回放】FlagOS开源社区“高性能计算实训营” 2025年08月17日13点场 | - | AI 论文精读 | - | 323:22 | [link](https://www.bilibili.com/video/BV1wQYWzrEBz) |
| 975 | OpenAI triton分享：Triton概述 | - | AI 论文精读 | - | 5:24 | [link](https://www.bilibili.com/video/BV1Kr421M7rt) |
| 976 | OpenAI triton分享：Triton安装教程 | - | AI 论文精读 | - | 5:44 | [link](https://www.bilibili.com/video/BV1b9W8eQEW3) |
| 977 | OpenAI triton分享：triton程序编写 | - | AI 论文精读 | - | 7:15 | [link](https://www.bilibili.com/video/BV154421S7TE) |
| 978 | OpenAI triton分享：triton源码结构 | - | AI 论文精读 | - | 8:17 | [link](https://www.bilibili.com/video/BV1SHxWeTEMe) |
| 979 | OpenAI triton分享：triton编译流程 | - | AI 论文精读 | - | 12:19 | [link](https://www.bilibili.com/video/BV1Di2CYcEba) |
| 980 | OpenAI triton分享：triton调试方法及工具（上） | - | AI 论文精读 | - | 8:27 | [link](https://www.bilibili.com/video/BV1aY2CYAEhy) |
| 981 | OpenAI triton分享：triton调试方法及工具（下） | - | AI 论文精读 | - | 6:40 | [link](https://www.bilibili.com/video/BV1m6C1YsEn1) |
| 982 | OpenAI triton分享：triton IR 剖析（上） | - | AI 论文精读 | - | 12:06 | [link](https://www.bilibili.com/video/BV1EwzyYZELz) |
| 983 | OpenAI triton分享：triton IR 剖析（下） | - | AI 论文精读 | - | 11:01 | [link](https://www.bilibili.com/video/BV1AHCJYkESY) |
| 984 | 计算机视觉与OpenMMLab 开源算法体系 | - | AI 论文精读 | - | 47:38 | [link](https://www.bilibili.com/video/BV1WG41177DP) |
| 985 | 深度学习算法基础 | - | AI 论文精读 | - | 65:34 | [link](https://www.bilibili.com/video/BV1gP411N7yA) |
| 986 | 上海交大学生创新中心人工智能实训平台介绍 | - | AI 论文精读 | - | 14:47 | [link](https://www.bilibili.com/video/BV1CV4y1V7SQ) |
| 987 | 图像分类 | - | AI 论文精读 | - | 68:54 | [link](https://www.bilibili.com/video/BV11G4y1n7gC) |
| 988 | MMClassification 介绍与代码实践 | - | AI 论文精读 | - | 51:53 | [link](https://www.bilibili.com/video/BV1LP411N7G4) |
| 989 | MMClassification 实践 2 | - | AI 论文精读 | - | 33:50 | [link](https://www.bilibili.com/video/BV1be4y1e7uS) |
| 990 | 目标检测 | - | AI 论文精读 | - | 56:52 | [link](https://www.bilibili.com/video/BV1BG4y1n7pn) |
| 991 | MMDetection 介绍与代码实践 | - | AI 论文精读 | - | 37:02 | [link](https://www.bilibili.com/video/BV1o8411Y7Td) |
| 992 | 数据集采集与标注、LabelBee工具介绍 | - | AI 论文精读 | - | 80:29 | [link](https://www.bilibili.com/video/BV16W4y1E74Z) |
| 993 | 模型部署与 MMDeploy 实践 | - | AI 论文精读 | - | 29:14 | [link](https://www.bilibili.com/video/BV1Ne411G7RX) |
| 994 | 语义分割与 MMSegmentation 实践 | - | AI 论文精读 | - | 32:49 | [link](https://www.bilibili.com/video/BV1fP411A74D) |
| 995 | 文字字符识别与 MMOCR 实践 | - | AI 论文精读 | - | 16:31 | [link](https://www.bilibili.com/video/BV1Qe4y1e7fH) |
| 996 | 人体姿态估计与 MMPose 实践 | - | AI 论文精读 | - | 56:20 | [link](https://www.bilibili.com/video/BV1Hg411z7Qk) |
| 997 | 视频目标追踪与 MMTracking 实践 | - | AI 论文精读 | - | 23:51 | [link](https://www.bilibili.com/video/BV14t4y1T7rd) |
| 998 | 生成模型 GAN 与 MMGeneration 实践 | - | AI 论文精读 | - | 43:33 | [link](https://www.bilibili.com/video/BV1SK411D7uS) |
| 999 | 强化学习RL是否可以提升模型性能上限？亦或只是将模型的Pass@N向Pass@1收敛？ | - | AI 论文精读 | - | 10:09 | [link](https://www.bilibili.com/video/BV1saNbzQEwT) |
| 1000 | RLVR对推理能力的提升是否可以/如何才能泛化到通用能力？ | - | AI 论文精读 | - | 4:21 | [link](https://www.bilibili.com/video/BV1Q1Nez7E2t) |
| 1001 | 过去的PPO算法依赖于四个神经网络来进行稳定训练，近期以DAPO为代表的算法只需要一个policy model，是什么带来了模型训练稳定性的提升？ | - | AI 论文精读 | - | 9:27 | [link](https://www.bilibili.com/video/BV1THNBznEkF) |
| 1002 | 近期一些工作针对RL提出了一系列反直觉的结论，例如random reward也能提升性能，如何看待这些结论？ | - | AI 论文精读 | - | 5:29 | [link](https://www.bilibili.com/video/BV1SjNLzsEjq) |
| 1003 | 当前多模态领域的RL算法往往是纯语言领域RL算法的“应用”迁移，除了引入图像condition以外没有太多改进，如何针对多模态引入算法改进？ | - | AI 论文精读 | - | 8:56 | [link](https://www.bilibili.com/video/BV1TzN5zDE5V) |
| 1004 | 如何看待预训练数据/性能对RL效果的影响？ | - | AI 论文精读 | - | 7:55 | [link](https://www.bilibili.com/video/BV1oNN7z6Ecq) |
| 1005 | 零人工数据强化学习推理模型主题分享 | - | AI 论文精读 | - | 31:30 | [link](https://www.bilibili.com/video/BV1irNszFEtt) |
| 1006 | 小米 MiMo-VL 预训练及后训练技术分享 | - | AI 论文精读 | - | 30:41 | [link](https://www.bilibili.com/video/BV1xuKwz2Ejp) |
| 1007 | 强化学习范式 OREAL：超越蒸馏，推动轻中量级模型突破推理“三重门”困局 | - | AI 论文精读 | - | 21:31 | [link](https://www.bilibili.com/video/BV1BCKczeEJa) |
| 1008 | CPRet：面向编程竞赛检索的基准数据集和模型 | - | AI 论文精读 | - | 22:38 | [link](https://www.bilibili.com/video/BV1kFGgzjEtu) |
| 1009 | DyCodeEval: 数据污染下的代码模型的动态测评 | - | AI 论文精读 | - | 22:04 | [link](https://www.bilibili.com/video/BV1QrGuzbEPH) |
| 1010 | OSS-Bench：告别静态数据集！从真实开源项目中“活捉”高难度编程任务 | - | AI 论文精读 | - | 17:37 | [link](https://www.bilibili.com/video/BV1GauuzREiY) |
| 1011 | UTBoost：修复“漏风”的 SWE-Bench，揪出 345 个“假通过”补丁 | - | AI 论文精读 | - | 21:19 | [link](https://www.bilibili.com/video/BV1qtu3zKEq9) |
| 1012 | 上海人工智能实验室 大模型中心负责人 陈恺 深度解读 Intern-S1——科学多模态大模型 | - | AI 论文精读 | - | 14:48 | [link](https://www.bilibili.com/video/BV1K3agzBE9i) |
| 1013 | MiniCPM-V：迈向高效端侧多模态大模型 | - | AI 论文精读 | - | 13:33 | [link](https://www.bilibili.com/video/BV1VZaCzLEJr) |
| 1014 | GLM-V：迈向通用推理的多模态大模型 | - | AI 论文精读 | - | 14:44 | [link](https://www.bilibili.com/video/BV1C9ahzbEmG) |
| 1015 | Ovis多模态大模型：结构对齐下的视觉语言融合 | - | AI 论文精读 | - | 14:26 | [link](https://www.bilibili.com/video/BV168HUzkEEZ) |
| 1016 | 阶跃星辰在多模态方向上的探索 | - | AI 论文精读 | - | 15:46 | [link](https://www.bilibili.com/video/BV1jAHXzmEao) |
| 1017 | 多模态模型哪些能力已逐渐饱和，还存在哪些不足和短板，未来有哪些值得关注的应用方向? | - | AI 论文精读 | - | 6:27 | [link](https://www.bilibili.com/video/BV1Y3HazDE2m) |
| 1018 | 多模态模型的推理相比于语言模型，有哪些不一样的技术挑战和发展思路？ | - | AI 论文精读 | - | 6:27 | [link](https://www.bilibili.com/video/BV1s1pWzJEGJ) |
| 1019 | 理解生成一体化是近期多模态大模型的热门探索方向，技术方案有什么样的演进趋势，未来是否有可能实现理解和生成任务的互相促进? | - | AI 论文精读 | - | 13:39 | [link](https://www.bilibili.com/video/BV1zCJkzQEmp) |
| 1020 | 多模态模型的突破是否被语言模型的研究进展所限制？模型架构和训练范式上有哪些创新路径？ | - | AI 论文精读 | - | 4:00 | [link](https://www.bilibili.com/video/BV1VFpCzQEG6) |
| 1021 | LongCat-Flash-Omni：美团全模态大模型探索 | - | AI 论文精读 | - | 24:34 | [link](https://www.bilibili.com/video/BV16jyuBBEZ8) |
| 1022 | OmniVinci：全模态大模型的架构和数据探索 | - | AI 论文精读 | - | 14:57 | [link](https://www.bilibili.com/video/BV1FFU5B8E9x) |
| 1023 | Ming-Omni：百灵多模态的实践与探索 | - | AI 论文精读 | - | 43:18 | [link](https://www.bilibili.com/video/BV1oeUbBaEGt) |
| 1024 | Omni 全模态模型在训练数据和策略上面临哪些挑战？如何构建和利用涵盖图像、视 频、音频、文本的海量数据集，并采用何种训练策略技巧来有效融合多模态信息的？ | - | AI 论文精读 | - | 9:56 | [link](https://www.bilibili.com/video/BV1ZPSaBCEXH) |
| 1025 | 在多模态统一模型中，模态不均衡或者模态偏置问题如何解决？ | - | AI 论文精读 | - | 6:25 | [link](https://www.bilibili.com/video/BV1to28BUEdg) |
| 1026 | 在长上下文建模方面，模型如何真正利用极长序列？例如视频长达上万帧，或多轮对话跨越很长距离，模型如何保留和利用这些信息？ | - | AI 论文精读 | - | 6:38 | [link](https://www.bilibili.com/video/BV1Q625B5Eyp) |
| 1027 | 如何看待通用模态 tokenization 未来面临的挑战？所有模态用统一“词表”表示是否现实？ | - | AI 论文精读 | - | 7:13 | [link](https://www.bilibili.com/video/BV1cG2kBMEQ9) |
| 1028 | 在一个模型中同时学习理解任务和生成任务会不会互相促进？可以从哪些技术路线去突破？ | - | AI 论文精读 | - | 5:02 | [link](https://www.bilibili.com/video/BV1dNmKBFExt) |
| 1029 | Omni 全模态模型的发展趋势是什么，可能会朝哪些新方向拓展？还有哪些关键技术要突破？ | - | AI 论文精读 | - | 3:59 | [link](https://www.bilibili.com/video/BV12VmCBJEK7) |
| 1030 | HunyuanOCR：混元原生多模态端到端 OCR 专家 | - | AI 论文精读 | - | 28:06 | [link](https://www.bilibili.com/video/BV1SBBVBEEMp) |
| 1031 | PaddleOCR-VL：支持 109 种语言的轻量化多模态文档解析方案 | - | AI 论文精读 | - | 24:03 | [link](https://www.bilibili.com/video/BV16CBDBzEHJ) |
| 1032 | MinerU：高效精准的文档解析技术攻坚 | - | AI 论文精读 | - | 23:21 | [link](https://www.bilibili.com/video/BV1epBaB3EPA) |
| 1033 | 极致端侧推理、结构还原与语义泛化三者之间存在天然的张力，在设计模型架构或训练策略时，如何权衡这三者之间的 trade-off 的？ | - | AI 论文精读 | - | 9:51 | [link](https://www.bilibili.com/video/BV1WZqFBPEjU) |
| 1034 | OCR 模型是否还有必要加入推理能力吗？主要会用于什么样的场景，会用怎样的形式出现？ | - | AI 论文精读 | - | 4:48 | [link](https://www.bilibili.com/video/BV1ZhqwB8EEr) |
| 1035 | OCR 系统在工程落地过程中，常见的性能瓶颈或优化难点有哪些？能否分享一些踩坑经验，尤其是在部署、推理效率或模型压缩方面的教训？ | - | AI 论文精读 | - | 2:57 | [link](https://www.bilibili.com/video/BV1MCquBvEfK) |
| 1036 | 如果从头搭建一个面向真实商业场景的文档解析系统（如合同、发票、报表等），有哪些关键建议可以给到开发者？ | - | AI 论文精读 | - | 2:52 | [link](https://www.bilibili.com/video/BV1RCiCBzERG) |
| 1037 | 从开源视角看，当前 OCR 工业级工具链或范式还有哪些关键缺失？如果不考虑商业化,最想推动或实现的 OCR 方向是什么？ | - | AI 论文精读 | - | 3:34 | [link](https://www.bilibili.com/video/BV1B8iDBaEgF) |
| 1038 | 能否分享最近关注、但本次尚未提及的 OCR 前沿工作？对于希望参与贡献开源项目的开发者，有哪些建议？ | - | AI 论文精读 | - | 8:36 | [link](https://www.bilibili.com/video/BV1NUrwBXEDj) |
| 1039 | 下一代多模态大模型能力演进的度量分析 | - | AI 论文精读 | - | 32:49 | [link](https://www.bilibili.com/video/BV1XUrhBLEsK) |
| 1040 | 基于多模态大模型的图像评价及应用探索 | - | AI 论文精读 | - | 12:51 | [link](https://www.bilibili.com/video/BV1pWr6BWEGv) |
| 1041 | 探索大模型的通用科学能力边界 | - | AI 论文精读 | - | 40:45 | [link](https://www.bilibili.com/video/BV1CLrLBXEoo) |
| 1042 | NewtonBench：在“平行宇宙”中评估大模型科学发现能力 | - | AI 论文精读 | - | 20:36 | [link](https://www.bilibili.com/video/BV1oVrzB3E2y) |
| 1043 | ScienceBoard: 从数字智能体到 AI 科学家 | - | AI 论文精读 | - | 29:39 | [link](https://www.bilibili.com/video/BV1FJhwzTEQH) |
| 1044 | AutoMind: 知识增强智能体解锁数据科学潜力 | - | AI 论文精读 | - | 28:15 | [link](https://www.bilibili.com/video/BV1oNhczoEM9) |
| 1045 | Scientists’ First Exam，科学认知能力的“开场哨声” | - | AI 论文精读 | - | 26:58 | [link](https://www.bilibili.com/video/BV1pWh7zUEMb) |
| 1046 | 圆桌讨论——科学智能的边界与突破 | - | AI 论文精读 | - | 49:13 | [link](https://www.bilibili.com/video/BV1X1tgzzEBH) |
| 1047 | 大模型评测基准发展趋势探讨 | - | AI 论文精读 | - | 24:08 | [link](https://www.bilibili.com/video/BV1AbrHBME4n) |
| 1048 | 技术写作系列课程第一课：技术写作的内容风格与选题 | - | AI 论文精读 | - | 36:27 | [link](https://www.bilibili.com/video/BV1YX4y1B7mH) |
| 1049 | 技术写作系列课程第二课：如何起一个吸引人的标题 | - | AI 论文精读 | - | 19:47 | [link](https://www.bilibili.com/video/BV1qs4y1d7jm) |
| 1050 | 技术写作系列课程第三课：如何搭建文章结构 | - | AI 论文精读 | - | 32:48 | [link](https://www.bilibili.com/video/BV1oc411E7nD) |
| 1051 | 技术写作系列课程第四课：技术写作必备的利器工具 | - | AI 论文精读 | - | 44:11 | [link](https://www.bilibili.com/video/BV1Tg4y1777V) |
| 1052 | Label Studio x Segment Anything Model 半自动化标注 | - | AI 论文精读 | - | 0:22 | [link](https://www.bilibili.com/video/BV1uv4y1J7yM) |
| 1053 | Label-Studio X Segment Anything Model 半自动化标注（2）：Windows CPU 环境配置 | - | AI 论文精读 | - | 2:43 | [link](https://www.bilibili.com/video/BV1hh411F7uR) |
| 1054 | Label-Studio X Segment Anything Model 半自动化标注（3）：开启前后端并标注 | - | AI 论文精读 | - | 5:56 | [link](https://www.bilibili.com/video/BV1Fo4y1V77n) |
| 1055 | Label-Studio X Segment Anything Model 半自动化标注（4）：数据集可视化及模型训练和测试 | - | AI 论文精读 | - | 7:21 | [link](https://www.bilibili.com/video/BV1Lh4y1o7qN) |
| 1056 | 以最新数学博资考题为例，书生-S2可以围绕一道复杂问题进行数小时的持续探索 | - | AI 论文精读 | - | 7:54 | [link](https://www.bilibili.com/video/BV1L8eE6NEk3) |
| 1057 | 书生-S2 实现结合疾病靶标的蛋白药物的自主设计 | - | AI 论文精读 | - | 0:28 | [link](https://www.bilibili.com/video/BV1fHeE6zESc) |
| 1058 | 基于给定的化学式，书生-S2 实现物理可行的晶体构建 | - | AI 论文精读 | - | 0:29 | [link](https://www.bilibili.com/video/BV1JneE63EUa) |
| 1059 | “书生-S2，帮我构建一个长征7火箭的3D CAD模型” | - | AI 论文精读 | - | 1:08 | [link](https://www.bilibili.com/video/BV1RQe76cEAg) |
| 1060 | Linux 前置基础知识 | - | AI 论文精读 | - | 15:01 | [link](https://www.bilibili.com/video/BV1FS421d7yg) |
| 1061 | Python 前置基础知识 | - | AI 论文精读 | - | 13:49 | [link](https://www.bilibili.com/video/BV1mS421X7h4) |
| 1062 | Git 前置基础知识 | - | AI 论文精读 | - | 6:06 | [link](https://www.bilibili.com/video/BV1Pz421i7bw) |
| 1063 | 书生·浦语大模型全链路开源开放体系 | - | AI 论文精读 | - | 29:02 | [link](https://www.bilibili.com/video/BV18142187g5) |
| 1064 | 8G 显存玩转书生大模型 Demo | - | AI 论文精读 | - | 8:08 | [link](https://www.bilibili.com/video/BV18x4y147SU) |
| 1065 | 浦语提示词工程实践 | - | AI 论文精读 | - | 55:17 | [link](https://www.bilibili.com/video/BV1cU411S7iV) |
| 1066 | InternLM+LlamaIndex RAG 实践 | - | AI 论文精读 | - | 55:20 | [link](https://www.bilibili.com/video/BV19E4m1X79q) |
| 1067 | XTuner 微调大模型个人小助手认知 | - | AI 论文精读 | - | 23:59 | [link](https://www.bilibili.com/video/BV1tz421B72y) |
| 1068 | OpenCompass 评测 InternLM-1.8B 实践 | - | AI 论文精读 | - | 21:15 | [link](https://www.bilibili.com/video/BV1RM4m1279j) |
| 1069 | Lagent 自定义你的 Agent 智能体 | - | AI 论文精读 | - | 7:13 | [link](https://www.bilibili.com/video/BV18M4m1y7sm) |
| 1070 | LMDeploy 量化部署进阶实践 | - | AI 论文精读 | - | 89:57 | [link](https://www.bilibili.com/video/BV1df421q7cR) |
| 1071 | InternVL（冷笑话大师）部署微调实践 | - | AI 论文精读 | - | 18:47 | [link](https://www.bilibili.com/video/BV1N6p1eXETX) |
| 1072 | 茴香豆：企业级知识库问答工具 | - | AI 论文精读 | - | 51:40 | [link](https://www.bilibili.com/video/BV1C5W2epEYP) |
| 1073 | 销冠——卖货主播大模型 | - | AI 论文精读 | - | 23:46 | [link](https://www.bilibili.com/video/BV1f1421b7Du) |
| 1074 | InternLM-1.8B 模型安卓端侧部署实践 | - | AI 论文精读 | - | 4:20 | [link](https://www.bilibili.com/video/BV1Ai421a7R6) |
| 1075 | 手把手带你使用 InternLM 实现谁是卧底游戏 | - | AI 论文精读 | - | 16:39 | [link](https://www.bilibili.com/video/BV1uhp1efEeE) |
| 1076 | 旋转~跳跃~检测王者 MMDetection 的好兄弟来啦！ | - | AI 论文精读 | - | 0:16 | [link](https://www.bilibili.com/video/BV1Hr4y1r73p) |
| 1077 | 墩墩生成器来啦！三步穿上墩墩服变身冰墩墩，做今年冬天最靓崽！ | - | AI 论文精读 | - | 1:11 | [link](https://www.bilibili.com/video/BV1Tq4y1t77C) |
| 1078 | 千行百业智能化落地，MMDeploy 助你一“部”到位！ | - | AI 论文精读 | - | 1:14 | [link](https://www.bilibili.com/video/BV1g34y1z7EW) |
| 1079 | 操作顺滑，一秒上手，LabelBee 让人工标注更智能! | - | AI 论文精读 | - | 1:12 | [link](https://www.bilibili.com/video/BV1pr4y1X7VM) |
| 1080 | 画形亦画骨，知面也知心，与 MMHuman3D 一道探索人体参数化模型！ | - | AI 论文精读 | - | 0:43 | [link](https://www.bilibili.com/video/BV1Ch411s7mS) |
| 1081 | MMFlow:帧与帧之间的追光者 | - | AI 论文精读 | - | 0:44 | [link](https://www.bilibili.com/video/BV1Zr4y1r72H) |
| 1082 | 【MMTracking】单目标跟踪！持续跟踪！ | - | AI 论文精读 | - | 0:29 | [link](https://www.bilibili.com/video/BV1Ev411376o) |
| 1083 | 【MMTracking】国庆快乐！多目标跟踪走丢也不怕！ | - | AI 论文精读 | - | 0:29 | [link](https://www.bilibili.com/video/BV1tU4y1c7mj) |
| 1084 | 【MMtracking】实时追踪！套马杆的汉子的马 | - | AI 论文精读 | - | 0:17 | [link](https://www.bilibili.com/video/BV1xL41147n5) |
| 1085 | 【MMDetection】七夕没对象？用我检测一下！ | - | AI 论文精读 | - | 0:21 | [link](https://www.bilibili.com/video/BV1QU4y177oZ) |
| 1086 | 【MMPose】火柴人出击！ | - | AI 论文精读 | - | 0:29 | [link](https://www.bilibili.com/video/BV1YU4y1H7Dq) |
| 1087 | 【MMPose】 demo webcam | - | AI 论文精读 | - | 0:18 | [link](https://www.bilibili.com/video/BV1pw411R7iD) |
| 1088 | 【MMPose】3D Human Pose | - | AI 论文精读 | - | 0:21 | [link](https://www.bilibili.com/video/BV1B3411672x) |
| 1089 | 【MMPose】Animal Pose | - | AI 论文精读 | - | 0:17 | [link](https://www.bilibili.com/video/BV1t341167V7) |
| 1090 | 【MMPose】2D Human Pose | - | AI 论文精读 | - | 0:24 | [link](https://www.bilibili.com/video/BV1Zf4y157PF) |
| 1091 | AI 生成视频不闪了！社区大佬又整新活啦！ | - | AI 论文精读 | - | 0:11 | [link](https://www.bilibili.com/video/BV19o4y1b7RZ) |
| 1092 | Segment Anything Model+ MMagic = Generate Anything！ | - | AI 论文精读 | - | 0:11 | [link](https://www.bilibili.com/video/BV1ws4y1R7aB) |
| 1093 | DragGAN 应用来啦，无需部署，在线体验！ | - | AI 论文精读 | - | 1:06 | [link](https://www.bilibili.com/video/BV1Rh4y1y7LK) |
| 1094 | 还在排队 SearchGPT？快来试试开源的 AI 搜索引擎框架 MindSearch！ | - | AI 论文精读 | - | 1:55 | [link](https://www.bilibili.com/video/BV1Kx4y1s7SS) |
| 1095 | 人工智能时代的创业新范式 | - | AI 论文精读 | - | 44:13 | [link](https://www.bilibili.com/video/BV1gAmnBZEuK) |
| 1096 | 从初心到商业化：以快速迭代创造用户真价值 | - | AI 论文精读 | - | 23:23 | [link](https://www.bilibili.com/video/BV1hwmnBbE7d) |
| 1097 | 医疗领域大模型微调实践 | - | AI 论文精读 | - | 9:56 | [link](https://www.bilibili.com/video/BV1gfqJBNEmT) |
| 1098 | MMSelfSup 代码库介绍 | - | AI 论文精读 | - | 12:04 | [link](https://www.bilibili.com/video/BV1hg411r7iK) |
| 1099 | MMSelfSup 代码教程【1】模型自监督预训练 之 SimCLR | - | AI 论文精读 | - | 18:28 | [link](https://www.bilibili.com/video/BV1Ht4y1n7jy) |
| 1100 | MMSelfSup 代码教程【2】图片向量可视化 t-SNE | - | AI 论文精读 | - | 20:52 | [link](https://www.bilibili.com/video/BV1yS4y1W7B6) |
| 1101 | MMSelfSup 代码教程【3】自监督预训练模型的评估：“分类” 下游任务 之 线性评估 | - | AI 论文精读 | - | 13:22 | [link](https://www.bilibili.com/video/BV1LP41157uA) |
| 1102 | MMSelfSup 代码教程【4】自监督预训练模型的评估：“分类” 下游任务 之 SVM 评估 | - | AI 论文精读 | - | 18:17 | [link](https://www.bilibili.com/video/BV1Ga411G73i) |
| 1103 | MMSelfSup 代码教程【5】自监督预训练模型的评估：“检测”下游任务 | - | AI 论文精读 | - | 11:10 | [link](https://www.bilibili.com/video/BV1EP41157BL) |
| 1104 | MMSelfSup 代码教程【6】在 MMDetection 中使用自监督预训练模型 | - | AI 论文精读 | - | 10:20 | [link](https://www.bilibili.com/video/BV1Fe4y1Z7Wh) |
| 1105 | MMSelfSup 代码教程【7】模型自监督预训练 之 MAE | - | AI 论文精读 | - | 17:28 | [link](https://www.bilibili.com/video/BV1EY4y1u7Px) |
| 1106 | 10 分钟带你上手 MMEval（一）：MMEval 介绍 | - | AI 论文精读 | - | 6:34 | [link](https://www.bilibili.com/video/BV1m24y127Db) |
| 1107 | 10 分钟带你上手 MMEval（二）：MMEval 使用介绍 | - | AI 论文精读 | - | 8:41 | [link](https://www.bilibili.com/video/BV1HP4y117pA) |
| 1108 | 10 分钟带你上手 MMEval（三）：如何给 MMEval 添加新的评测指标 | - | AI 论文精读 | - | 10:12 | [link](https://www.bilibili.com/video/BV1Ev4y1d7nK) |
| 1109 | 大语言模型复杂医疗推理评测基准MedAgentsBench | - | AI 论文精读 | - | 34:53 | [link](https://www.bilibili.com/video/BV1J5oXYYEYH) |
| 1110 | 通用写作评测基准 WritingBench | - | AI 论文精读 | - | 34:39 | [link](https://www.bilibili.com/video/BV1dFdpYqELh) |
| 1111 | 首个视频时空推理评估基准 V-STaR | - | AI 论文精读 | - | 38:35 | [link](https://www.bilibili.com/video/BV1DbdHYZEbq) |
| 1112 | ViLBench：多模态过程奖励（Process Reward）建模组件 | - | AI 论文精读 | - | 45:00 | [link](https://www.bilibili.com/video/BV1cZ5kzyECC) |
| 1113 | CMU团队打造考公逻辑谜题 VisualPuzzles | - | AI 论文精读 | - | 41:03 | [link](https://www.bilibili.com/video/BV16kL7zrEdq) |
| 1114 | ToolHop：查询驱动的多跳工具使用评测集 | - | AI 论文精读 | - | 46:43 | [link](https://www.bilibili.com/video/BV1CjExzGE7s) |
| 1115 | 1. MMDetection3D 介绍及安装配置 | - | AI 论文精读 | - | 5:37 | [link](https://www.bilibili.com/video/BV1aG4y197is) |
| 1116 | 2. 使用 MMDet3D 预训练模型在点云和数据图像上推理 | - | AI 论文精读 | - | 15:49 | [link](https://www.bilibili.com/video/BV1E44y1Q7qi) |
| 1117 | 3. KITTI 数据集介绍及 MMDet3D 坐标系规范 | - | AI 论文精读 | - | 26:19 | [link](https://www.bilibili.com/video/BV1vv4y1d7br) |
| 1118 | 4. 使用 MMDetection3D 训练 | - | AI 论文精读 | - | 15:06 | [link](https://www.bilibili.com/video/BV11G4y157ux) |
| 1119 | 5. PointPillars 和 KittiDataset 的配置文件解读 | - | AI 论文精读 | - | 16:02 | [link](https://www.bilibili.com/video/BV14M41167Ct) |
| 1120 | 6. PointPillars 和 KittiDataset 的代码解读 | - | AI 论文精读 | - | 32:37 | [link](https://www.bilibili.com/video/BV1Xe4y1g7Xv) |
| 1121 | 大语言模型原理与书生大模型提示词工程实践 | - | AI 论文精读 | - | 39:46 | [link](https://www.bilibili.com/video/BV1vUjYz2Eys) |
| 1122 | 玩转书生大模型 API 之 Browse Use实践 | - | AI 论文精读 | - | 1:29 | [link](https://www.bilibili.com/video/BV1SPGnzWEN4) |
| 1123 | InternLM 微调论文分类实践 | - | AI 论文精读 | - | 15:10 | [link](https://www.bilibili.com/video/BV1DyGuz4Ewp) |
| 1124 | GraphGen 训练数据合成框架 | - | AI 论文精读 | - | 4:49 | [link](https://www.bilibili.com/video/BV1EA31zMEQk) |
| 1125 | CAMEL 书生多智能体系统实践 | - | AI 论文精读 | - | 41:23 | [link](https://www.bilibili.com/video/BV15A3EzWEPv) |
| 1126 | 国产开源、免费的 AI 图像与视频创作平台MagicMaker，新手教程来啦！ | - | AI 论文精读 | - | 2:05 | [link](https://www.bilibili.com/video/BV1w2421A7YP) |
| 1127 | “龙在城隍庙吃小笼包”MagicMaker亮相东方卫视春晚特别直播节目，科技魔法点亮传统舞台 | - | AI 论文精读 | - | 0:45 | [link](https://www.bilibili.com/video/BV1TS421A7UR) |
| 1128 | “一个小男生和一个小女生在黄河路‘偷心’”MagicMaker亮相东方卫视春晚特别直播节目，科技魔法点亮传统舞台 | - | AI 论文精读 | - | 1:36 | [link](https://www.bilibili.com/video/BV18z421X7ci) |
| 1129 | “龙在东方明珠上盘旋”MagicMaker亮相东方卫视春晚特别直播节目，科技魔法点亮传统舞台 | - | AI 论文精读 | - | 1:17 | [link](https://www.bilibili.com/video/BV1VC411s7Fv) |
| 1130 | 社区开放麦#1｜基于关键点的动作识别 | - | AI 论文精读 | - | 46:41 | [link](https://www.bilibili.com/video/BV1Yu411k7Be) |
| 1131 | 社区开放麦#2｜CVPR前沿姿态估计论文精讲 | - | AI 论文精读 | - | 60:13 | [link](https://www.bilibili.com/video/BV1dS4y187sj) |
| 1132 | 社区开放麦#3｜PyTorch 分布式训练解读 | - | AI 论文精读 | - | 66:51 | [link](https://www.bilibili.com/video/BV1Jv4y1K7fv) |
| 1133 | 社区开放麦#4｜手把手带你复现最新自监督算法 | - | AI 论文精读 | - | 61:09 | [link](https://www.bilibili.com/video/BV1xt4y1x7sp) |
| 1134 | 社区开放麦#5｜带你探寻可见光之外的世界 | - | AI 论文精读 | - | 36:01 | [link](https://www.bilibili.com/video/BV1Ka411n7nP) |
| 1135 | 社区开放麦#6｜带你了解车速估计技术在自动驾驶领域的应用 | - | AI 论文精读 | - | 50:40 | [link](https://www.bilibili.com/video/BV1sY4y1L7Au) |
| 1136 | 社区开放麦#7  MMPose 姿态估计创意 demo 大赛 | - | AI 论文精读 | - | 59:49 | [link](https://www.bilibili.com/video/BV1J34y1j7AP) |
| 1137 | 社区开放麦#8 / 迈向真实世界的感知：3D 目标检测 | - | AI 论文精读 | - | 69:23 | [link](https://www.bilibili.com/video/BV1hg41197HX) |
| 1138 | 社区开放麦#9 / OpenMMLab 模块化设计背后的功臣 | - | AI 论文精读 | - | 59:46 | [link](https://www.bilibili.com/video/BV19Z4y1q7Q5) |
| 1139 | 社区开放麦#10 / MMDeploy ncnn 部署实战 | - | AI 论文精读 | - | 47:44 | [link](https://www.bilibili.com/video/BV1gS4y1p7gm) |
| 1140 | 社区开放麦#11 / BEV感知：下一代自动驾驶感知算法新范式 | - | AI 论文精读 | - | 57:01 | [link](https://www.bilibili.com/video/BV12t4y1t7Lq) |
| 1141 | 社区开放麦#12 / 视觉有向目标的高精度检测 | - | AI 论文精读 | - | 63:46 | [link](https://www.bilibili.com/video/BV1Wr4y1E7Qr) |
| 1142 | 社区开放麦#13 / 手势识别算法综述与正确打开方式 | - | AI 论文精读 | - | 57:48 | [link](https://www.bilibili.com/video/BV1ar4y1j7aN) |
| 1143 | 社区开放麦#14 / 从时间序列角度破解姿态估计中的两大问题 | - | AI 论文精读 | - | 94:16 | [link](https://www.bilibili.com/video/BV1aB4y1k7Ph) |
| 1144 | 社区开放麦#15/  突破纯视觉 3D 检测深度估计瓶颈 | - | AI 论文精读 | - | 59:31 | [link](https://www.bilibili.com/video/BV1dg41117ba) |
| 1145 | 社区开放麦#16 / 稀疏卷积的高性能部署 | - | AI 论文精读 | - | 58:07 | [link](https://www.bilibili.com/video/BV1gV4y177F6) |
| 1146 | 社区开放麦#17 / 像素级别的多目标跟踪方案 | - | AI 论文精读 | - | 32:41 | [link](https://www.bilibili.com/video/BV1814y1b7Za) |
| 1147 | 社区开放麦#18 / 半监督学习在 3D 目标检测的最新进展 | - | AI 论文精读 | - | 45:01 | [link](https://www.bilibili.com/video/BV1mT411c7kB) |
| 1148 | 社区开放麦#19 / 对 AI 炼丹师友好的模型部署探索 | - | AI 论文精读 | - | 84:31 | [link](https://www.bilibili.com/video/BV12V4y1H7XQ) |
| 1149 | 社区开放麦#20 / 简单有效的目标跟踪方案 | - | AI 论文精读 | - | 50:46 | [link](https://www.bilibili.com/video/BV1wd4y1X7j5) |
| 1150 | 社区开放麦#21 / 当钩子编程遇到深度学习：Runner & Hook | - | AI 论文精读 | - | 59:58 | [link](https://www.bilibili.com/video/BV1pe4y1C7n1) |
| 1151 | 社区开放麦#22 /  姿态估计领域的前沿进展 | - | AI 论文精读 | - | 77:13 | [link](https://www.bilibili.com/video/BV1HV4y1M7dG) |
| 1152 | 社区开放麦#23 / MMYOLO 圆桌会 | - | AI 论文精读 | - | 51:38 | [link](https://www.bilibili.com/video/BV1r24y1R7D1) |
| 1153 | 社区开放麦#24 / 释放数据潜力，打造 AI 加速引擎 | - | AI 论文精读 | - | 53:51 | [link](https://www.bilibili.com/video/BV1p8411s7W6) |
| 1154 | AI奇妙夜第一期 | - | AI 论文精读 | - | 76:09 | [link](https://www.bilibili.com/video/BV1P8411e7Cb) |
| 1155 | 社区开放麦#27 / 部署神器Halide, 实现高性能算法 | - | AI 论文精读 | - | 46:06 | [link](https://www.bilibili.com/video/BV1Tg411B7ch) |
| 1156 | AI 奇妙夜#2 / 子豪兄分享人工智能学习心法 | - | AI 论文精读 | - | 82:07 | [link](https://www.bilibili.com/video/BV1WG4y1f7yX) |
| 1157 | 社区开放麦#29 / ECCV Oral / 用于场景文本检测识别的弱监督视觉语言预训练方法 | - | AI 论文精读 | - | 53:31 | [link](https://www.bilibili.com/video/BV16G4y1x7es) |
| 1158 | 社区开放麦#30 / 入门剪枝利器 MMRazor，迈出模型压缩第一步 | - | AI 论文精读 | - | 53:24 | [link](https://www.bilibili.com/video/BV1wG411u7SP) |
| 1159 | 社区开放麦#31 / 异构检测器间知识蒸馏算法 PKD / NeurIPS22 | - | AI 论文精读 | - | 55:56 | [link](https://www.bilibili.com/video/BV1z24y1k7iu) |
| 1160 | 社区开放麦#32 / ONNX 新特性和最佳实践介绍 | - | AI 论文精读 | - | 66:28 | [link](https://www.bilibili.com/video/BV1LG411K7ah) |
| 1161 | 社区开放麦#33 / 详解 ACCV22 大规模细粒度图像分类夺冠方案 | - | AI 论文精读 | - | 36:03 | [link](https://www.bilibili.com/video/BV13M411S7b5) |
| 1162 | 社区开放麦#34 / 突破 AI 推理性能瓶颈，神经网络量化的方法与实践 | - | AI 论文精读 | - | 64:09 | [link](https://www.bilibili.com/video/BV128411n7yN) |
| 1163 | AI 奇妙夜#3 / 大规模多模态预训练最新研究进展 | - | AI 论文精读 | - | 53:10 | [link](https://www.bilibili.com/video/BV1J14y1A7SE) |
| 1164 | 社区开放麦#36 多模态场景下的高性能 Embedding 计算服务 | - | AI 论文精读 | - | 52:10 | [link](https://www.bilibili.com/video/BV1ET411m7gu) |
| 1165 | 社区开放麦#37 / 牛津大学vgg组博士：提高遮挡检测下的目标检测效果 | - | AI 论文精读 | - | 55:18 | [link](https://www.bilibili.com/video/BV1NA41167kN) |
| 1166 | 社区开放麦#38 目标检测新范式！DETR 系列算法解读 | - | AI 论文精读 | - | 123:27 | [link](https://www.bilibili.com/video/BV17x4y1w7ZK) |
| 1167 | 弱监督有向目标检测 / 杨学 | - | AI 论文精读 | - | 64:14 | [link](https://www.bilibili.com/video/BV1GD4y1g7s8) |
| 1168 | 社区开放麦#41 / 视觉大模型设计新范式 | - | AI 论文精读 | - | 66:15 | [link](https://www.bilibili.com/video/BV1zs4y15754) |
| 1169 | AI 奇妙夜#4 / 文字识别：从数据趋动到模型自监督 | - | AI 论文精读 | - | 66:35 | [link](https://www.bilibili.com/video/BV1Zb41197V4) |
| 1170 | 社区开放麦#42 / 面向自动驾驶场景的纯视觉三维语义占有预测 | - | AI 论文精读 | - | 70:13 | [link](https://www.bilibili.com/video/BV1P54y1T7vS) |
| 1171 | 社区开放麦#43 / 高精度实例分割 PatchDCT | - | AI 论文精读 | - | 22:03 | [link](https://www.bilibili.com/video/BV1Sx4y1w7JK) |
| 1172 | AI奇妙夜#5 / “视觉与语言”跨模态智能及应用 | - | AI 论文精读 | - | 60:59 | [link](https://www.bilibili.com/video/BV1Y84y1g7nP) |
| 1173 | CVPR 2023 有向目标检测角度预测新方法 — 相移编码 / 社区开放麦#45 | - | AI 论文精读 | - | 41:41 | [link](https://www.bilibili.com/video/BV1Cv4y1n72h) |
| 1174 | 业界可用的高性能的姿态估计模型能有多快？ / 社区开放麦#46 | - | AI 论文精读 | - | 87:37 | [link](https://www.bilibili.com/video/BV1Wc411p7HT) |
| 1175 | CVPR2023 首个大规模全场景人体数据集 Human-Art / 社区开放麦#47 | - | AI 论文精读 | - | 59:00 | [link](https://www.bilibili.com/video/BV1Hs4y1d7bJ) |
| 1176 | MOSS：如何打造对话式语言模型 / 社区开放麦#48 | - | AI 论文精读 | - | 65:19 | [link](https://www.bilibili.com/video/BV1fa4y1V7xG) |
| 1177 | 超大规模视觉通用感知模型-代季峰教授 / AI奇妙夜#6 | - | AI 论文精读 | - | 50:12 | [link](https://www.bilibili.com/video/BV1dM411g7Jn) |
| 1178 | 视频理解基础模型及下游应用-王利民教授 / AI奇妙夜#7 | - | AI 论文精读 | - | 60:43 | [link](https://www.bilibili.com/video/BV1rz4y1t7b7) |
| 1179 | ICLR Spotlight / 在卷积网络上做BERT式预训练 | - | AI 论文精读 | - | 56:44 | [link](https://www.bilibili.com/video/BV11s4y1M7qL) |
| 1180 | HumanBench：迈向以人为中心的通才模型 | - | AI 论文精读 | - | 45:54 | [link](https://www.bilibili.com/video/BV1Q24y1N72o) |
| 1181 | 低成本微调垂直领域专属 ChatGPT | - | AI 论文精读 | - | 67:12 | [link](https://www.bilibili.com/video/BV1Pz4y1q7yA) |
| 1182 | 自动驾驶场景中的半监督点云分割 | - | AI 论文精读 | - | 63:23 | [link](https://www.bilibili.com/video/BV11u4y1d7S2) |
| 1183 | 基于 Visual Transformer 的分割模型综述 | - | AI 论文精读 | - | 62:06 | [link](https://www.bilibili.com/video/BV1tc411M7DC) |
| 1184 | AI 2.0：突破性技术推动智能制造的应用创新 | - | AI 论文精读 | - | 55:11 | [link](https://www.bilibili.com/video/BV1ch4y1M7Re) |
| 1185 | 基于 SAM 大模型的实例分割研究 —— RSPrompter | - | AI 论文精读 | - | 52:55 | [link](https://www.bilibili.com/video/BV1J94y1i7bB) |
| 1186 | 开放检测视觉场景理解 / 社区开放麦 | - | AI 论文精读 | - | 67:01 | [link](https://www.bilibili.com/video/BV1u14y1R7mn) |
| 1187 | 运用 SAM 模型分割任意点云 | - | AI 论文精读 | - | 76:19 | [link](https://www.bilibili.com/video/BV1gm4y1j7M2) |
| 1188 | MMBench：基于ChatGPT的全方位多模能力评测体系 | - | AI 论文精读 | - | 42:30 | [link](https://www.bilibili.com/video/BV16z4y1x7qG) |
| 1189 | 迈向更强的端到端多人姿态估计 | - | AI 论文精读 | - | 65:30 | [link](https://www.bilibili.com/video/BV1fj41197R9) |
| 1190 | SAM 时代，图像/视频分割将何去何从？ | - | AI 论文精读 | - | 67:34 | [link](https://www.bilibili.com/video/BV1ZP41147xQ) |
| 1191 | MFF：简单高效的多级特征融合自监督方法 / ICCV 2023 | - | AI 论文精读 | - | 39:03 | [link](https://www.bilibili.com/video/BV1q94y1z7Xe) |
| 1192 | 更好的人体姿态，更好的生成图像 | - | AI 论文精读 | - | 33:05 | [link](https://www.bilibili.com/video/BV1rw411Q7t6) |
| 1193 | 基于大规模多模态扩散模型的文本到视频生成 | - | AI 论文精读 | - | 70:46 | [link](https://www.bilibili.com/video/BV1BP411h7oQ) |
| 1194 | 多模态任务终结者：Meta-Transformer | - | AI 论文精读 | - | 59:30 | [link](https://www.bilibili.com/video/BV1Bu4y1y714) |
| 1195 | 迈向更强的开集目标检测-From Detection to Grounding | - | AI 论文精读 | - | 57:19 | [link](https://www.bilibili.com/video/BV1Mk4y1F7cp) |
| 1196 | 如何基于大模型构建智能体？多机构百页综述从交互角度详解 AI Agent！ | - | AI 论文精读 | - | 70:51 | [link](https://www.bilibili.com/video/BV1884y1U7CR) |
| 1197 | 你的3D感知模型够鲁棒吗？Robo3D告诉你答案！ | - | AI 论文精读 | - | 69:08 | [link](https://www.bilibili.com/video/BV1nu411u7W6) |
| 1198 | 如何高效微调大模型？技术原理与最佳实践揭秘！ | - | AI 论文精读 | - | 86:20 | [link](https://www.bilibili.com/video/BV1qw411c7Hd) |
| 1199 | 大模型时代通用检测趋势解读及MMDetection未来展望 | - | AI 论文精读 | - | 82:24 | [link](https://www.bilibili.com/video/BV1o94y1L7fg) |
| 1200 | CVPR23 / 3D Occupancy 预测冠军方案：FB-OCC | - | AI 论文精读 | - | 52:45 | [link](https://www.bilibili.com/video/BV1PX4y1e7zz) |
| 1201 | 多模态 Agents：用大模型语言模型串联多模态专家 | - | AI 论文精读 | - | 39:48 | [link](https://www.bilibili.com/video/BV1mM411X7Zn) |
| 1202 | 探索未知：LLM Agent 应用开发的全新时代 | - | AI 论文精读 | - | 67:39 | [link](https://www.bilibili.com/video/BV1W84y197qq) |
| 1203 | AI时代数据应用的全链路工厂- Chat2DB | - | AI 论文精读 | - | 35:53 | [link](https://www.bilibili.com/video/BV1re411m7p3) |
| 1204 | 语音与音频生成 Amphion揭秘霉霉如何演唱《稻香》 | - | AI 论文精读 | - | 59:55 | [link](https://www.bilibili.com/video/BV1AV411R7SS) |
| 1205 | RTMPose 家族史诗级更新！多人、全身一网打尽 | - | AI 论文精读 | - | 80:21 | [link](https://www.bilibili.com/video/BV1P5411v7tz) |
| 1206 | 清华提出首个面向无监督和半监督新意图发现的文本聚类框架USNID | - | AI 论文精读 | - | 69:12 | [link](https://www.bilibili.com/video/BV1464y1w73f) |
| 1207 | Beyond Segmentation Anything，超越SAM | - | AI 论文精读 | - | 68:50 | [link](https://www.bilibili.com/video/BV1xC411r7qq) |
| 1208 | Sora 夜谈之 Video Diffusion 综述 | - | AI 论文精读 | - | 90:09 | [link](https://www.bilibili.com/video/BV1cJ4m1e7sQ) |
| 1209 | 新一代换脸神器 InstantID：高保真人像秒级生成 | - | AI 论文精读 | - | 76:56 | [link](https://www.bilibili.com/video/BV1HH4y177T5) |
| 1210 | CVPR 2024 - 具身智能中的多模态三维感知思考 | - | AI 论文精读 | - | 51:26 | [link](https://www.bilibili.com/video/BV1nt421V7UY) |
| 1211 | PK 周杰伦，全能音乐创作大模型 SongComposer 作词作曲令人惊叹 | - | AI 论文精读 | - | 66:09 | [link](https://www.bilibili.com/video/BV1bw4m1d7dK) |
| 1212 | Stable Diffusion 3 论文技术解析，架构细节大揭秘！ | - | AI 论文精读 | - | 58:15 | [link](https://www.bilibili.com/video/BV1Ni421d7ud) |
| 1213 | 无需训练的 Stable Diffusion 视频编辑方法 | - | AI 论文精读 | - | 56:49 | [link](https://www.bilibili.com/video/BV12w4m1R75t) |
| 1214 | Latte 专场: 深度解读视频生成与训练技术 | - | AI 论文精读 | - | 120:08 | [link](https://www.bilibili.com/video/BV14F4m1K7Wz) |
| 1215 | 微软研究院谭旭带来零样本 TTS 模型 NaturalSpeech 3 | - | AI 论文精读 | - | 62:41 | [link](https://www.bilibili.com/video/BV1tm421s7B6) |
| 1216 | 零样本语音生成大模型与Amphion实践 | - | AI 论文精读 | - | 67:19 | [link](https://www.bilibili.com/video/BV18C41177JA) |
| 1217 | 多模态大模型的技术实践与思考 | - | AI 论文精读 | - | 65:53 | [link](https://www.bilibili.com/video/BV17n4y1d7wp) |
| 1218 | 当大模型遇上心理咨询：基于心理咨询报告的对话重构和评测框架CPsyCoun | - | AI 论文精读 | - | 54:02 | [link](https://www.bilibili.com/video/BV1vJ4m1g7G4) |
| 1219 | ACL 24 论文分享（东北大学信息检索小组场） | - | AI 论文精读 | - | 73:27 | [link](https://www.bilibili.com/video/BV144421Q7ir) |
| 1220 | SD-Eval新基准，让语音交互大模型情智兼备 | - | AI 论文精读 | - | 47:56 | [link](https://www.bilibili.com/video/BV16E421A7wU) |
| 1221 | 魔搭社区-浦语模型和工具实战 | - | AI 论文精读 | - | 70:26 | [link](https://www.bilibili.com/video/BV1zy411i7yp) |
| 1222 | 开源工具MinerU助力复杂PDF高效解析提取 | - | AI 论文精读 | - | 67:06 | [link](https://www.bilibili.com/video/BV15rHSeyEk2) |
| 1223 | MindSearch：AI 时代的“思考型”智能搜索引擎 | - | AI 论文精读 | - | 58:35 | [link](https://www.bilibili.com/video/BV1UHy3YYEHz) |
| 1224 | MaskGCT：基于掩码生成模型的大规模零样本 TTS 模型 | - | AI 论文精读 | - | 82:28 | [link](https://www.bilibili.com/video/BV1LJD1YsEd4) |
| 1225 | 玩转 MMYOLO 之工具篇（一）：特征图可视化 | - | AI 论文精读 | - | 17:48 | [link](https://www.bilibili.com/video/BV188411s7o8) |
| 1226 | 玩转 MMYOLO 之基础篇（一）：配置文件全解读 | - | AI 论文精读 | - | 18:33 | [link](https://www.bilibili.com/video/BV1214y157ck) |
| 1227 | 【MMYOLO】超酷炫 RTMDet 特征图可视化 demo | - | AI 论文精读 | - | 0:33 | [link](https://www.bilibili.com/video/BV1je4y1478R) |
| 1228 | 玩转 MMYOLO 之实用篇（一）: 源码阅读和调试「必备」技巧 | - | AI 论文精读 | - | 43:02 | [link](https://www.bilibili.com/video/BV1N14y1V7mB) |
| 1229 | MMYOLO 社区贡献者经验分享会 | - | AI 论文精读 | - | 82:05 | [link](https://www.bilibili.com/video/BV12d4y1r7Nd) |
| 1230 | 玩转 MMYOLO 之基础篇（二）： 工程文件结构简析 | - | AI 论文精读 | - | 12:06 | [link](https://www.bilibili.com/video/BV1LP4y117jS) |
| 1231 | 玩转 MMYOLO 之实用篇（二）: 10分钟带你换遍主干网络 | - | AI 论文精读 | - | 9:07 | [link](https://www.bilibili.com/video/BV1JG4y1d7GC) |
| 1232 | 玩转 MMYOLO 之工具篇（二）：十分钟轻松掌握大图推理 | - | AI 论文精读 | - | 11:34 | [link](https://www.bilibili.com/video/BV1EK411R7Ws) |
| 1233 | 玩转 MMYOLO 之实用篇（三）：自定义数据集从标注到部署保姆级教程 | - | AI 论文精读 | - | 49:30 | [link](https://www.bilibili.com/video/BV1RG4y137i5) |
| 1234 | 玩转 MMYOLO 之实用篇（四）：顶会第一步 · 模块自定义 | - | AI 论文精读 | - | 8:15 | [link](https://www.bilibili.com/video/BV1yd4y1j7VD) |
| 1235 | 玩转 MMYOLO 之实用篇（五）：训练和测试技巧合集 | - | AI 论文精读 | - | 24:29 | [link](https://www.bilibili.com/video/BV1GM4y1U77z) |
| 1236 | 清华大学导师亲授！3D目标检测超硬核课程新鲜出炉~ | - | AI 论文精读 | - | 100:24 | [link](https://www.bilibili.com/video/BV1Sc411K7L1) |
| 1237 | 人体关键点检测与MMPose | - | AI 论文精读 | - | 50:23 | [link](https://www.bilibili.com/video/BV1kk4y1L7Xb) |
| 1238 | 1. PyTorch 模型部署基础知识 | - | AI 论文精读 | - | 41:49 | [link](https://www.bilibili.com/video/BV1Tx4y1F768) |
| 1239 | 2. 安装配置 MMDeploy 环境 | - | AI 论文精读 | - | 10:03 | [link](https://www.bilibili.com/video/BV1yX4y1X7jp) |
| 1240 | 3. 部署 MMClassification 图像分类模型 | - | AI 论文精读 | - | 5:45 | [link](https://www.bilibili.com/video/BV1V84y1J7MT) |
| 1241 | 4. 部署 MMDetection 目标检测模型 | - | AI 论文精读 | - | 2:55 | [link](https://www.bilibili.com/video/BV11R4y1v7L2) |
| 1242 | 自监督学习与 MMSelfSup | - | AI 论文精读 | - | 66:02 | [link](https://www.bilibili.com/video/BV1iu4y1e7tV) |
| 1243 | Linux 前置基础（基本命令、SSH及端口映射） | - | AI 论文精读 | - | 15:01 | [link](https://www.bilibili.com/video/BV13U1VYmEUr) |
| 1244 | Python 前置基础（熟悉断点调试、依赖指定路径安装） | - | AI 论文精读 | - | 10:34 | [link](https://www.bilibili.com/video/BV1u61jYSExg) |
| 1245 | Git 前置基础（熟悉常见 Git 命令及GitHub 平台） | - | AI 论文精读 | - | 14:40 | [link](https://www.bilibili.com/video/BV15MShYkEgg) |
| 1246 | 玩转Hugging Face/魔搭/魔乐平台(熟悉模型下载上传及应用上传) | - | AI 论文精读 | - | 11:04 | [link](https://www.bilibili.com/video/BV1XxStYYEH1) |
| 1247 | 书生·浦语大模型开源开放体系 | - | AI 论文精读 | - | 29:01 | [link](https://www.bilibili.com/video/BV1CkSUYGE1v) |
| 1248 | 玩转书生「多模态对话」与「AI 搜索」产品 | - | AI 论文精读 | - | 4:49 | [link](https://www.bilibili.com/video/BV1ExDQYyEAA) |
| 1249 | 浦语提示词工程实践 | - | AI 论文精读 | - | 70:53 | [link](https://www.bilibili.com/video/BV1tjS7YfEWJ) |
| 1250 | 浦语+LlamaIndex 外挂知识库 RAG 实践 | - | AI 论文精读 | - | 55:19 | [link](https://www.bilibili.com/video/BV1YzDJY1E2i) |
| 1251 | XTuner 微调 InternLM 个人小助手认知实践 | - | AI 论文精读 | - | 23:47 | [link](https://www.bilibili.com/video/BV1G9SJYGEtD) |
| 1252 | OpenCompass 评测书生大模型实践 | - | AI 论文精读 | - | 23:42 | [link](https://www.bilibili.com/video/BV1dtD4YKENj) |
| 1253 | Lagent 从零搭建你的 Multi-Agent (书生·浦语 API 版) | - | AI 论文精读 | - | 22:29 | [link](https://www.bilibili.com/video/BV19RzcYaEFy) |
| 1254 | LMDeploy 量化部署进阶实践 | - | AI 论文精读 | - | 89:57 | [link](https://www.bilibili.com/video/BV18aUHY3EEG) |
| 1255 | 多模态大模型发展简述及其微调部署实践(InternVL2为例) | - | AI 论文精读 | - | 23:10 | [link](https://www.bilibili.com/video/BV1nESCYWEnN) |
| 1256 | InternLM+WasmEdge 部署智能体实践 | - | AI 论文精读 | - | 13:52 | [link](https://www.bilibili.com/video/BV1K2rAYeEXG) |
| 1257 | EgoExolearn跨视角技能学习数据集 | - | AI 论文精读 | - | 25:11 | [link](https://www.bilibili.com/video/BV1pT42167pQ) |
| 1258 | 单阶段多维度模型搜索范式 | - | AI 论文精读 | - | 34:25 | [link](https://www.bilibili.com/video/BV1Yb421J7wA) |
| 1259 | MVBench 多模态视频评测体系 | - | AI 论文精读 | - | 28:53 | [link](https://www.bilibili.com/video/BV1ZE4m1R7Tc) |
| 1260 | 人机协作的视觉生成 | - | AI 论文精读 | - | 29:13 | [link](https://www.bilibili.com/video/BV1fZ421N7re) |
| 1261 | 个性化图像动画生成器，利用文本提示将图像变为奇妙的动画 | - | AI 论文精读 | - | 28:27 | [link](https://www.bilibili.com/video/BV1PE4m197ZM) |
| 1262 | 基于像素点的拖拽式图像编辑分享 | - | AI 论文精读 | - | 38:13 | [link](https://www.bilibili.com/video/BV1XH4y1c78r) |
| 1263 | GenNBV：面向主动三维重建的可泛化最佳视角探索策略 | - | AI 论文精读 | - | 37:23 | [link](https://www.bilibili.com/video/BV1yy411i7jh) |
| 1264 | 多模态大模型幻觉成因解释以及基于惩罚回退策略的幻觉缓解方法 | - | AI 论文精读 | - | 25:13 | [link](https://www.bilibili.com/video/BV1QH4y1c7p3) |
| 1265 | 中文常识推理基准-CHARM | - | AI 论文精读 | - | 12:23 | [link](https://www.bilibili.com/video/BV1QcmdYiExz) |
| 1266 | 分享 SALAD-BENCH 数据集与评估方法 | - | AI 论文精读 | - | 28:19 | [link](https://www.bilibili.com/video/BV1KimoYaExY) |
| 1267 | 评估大语言模型多轮对话能力的细粒度评测集 | - | AI 论文精读 | - | 23:11 | [link](https://www.bilibili.com/video/BV1mvmoYAEAv) |
| 1268 | ConvBench：多轮视觉对话评测基准与能力解耦评测方式 | - | AI 论文精读 | - | 17:00 | [link](https://www.bilibili.com/video/BV1QbcRevE61) |
| 1269 | GTA：大模型复杂任务工具调用能力评测 | - | AI 论文精读 | - | 17:17 | [link](https://www.bilibili.com/video/BV1cucReJETD) |
| 1270 | MMDU：高质量多图多轮对话数据集 | - | AI 论文精读 | - | 15:36 | [link](https://www.bilibili.com/video/BV1HTcReDEhX) |
| 1271 | MMLongBench-Doc：使用可视化对长上下文文档理解进行基准测试 | - | AI 论文精读 | - | 25:00 | [link](https://www.bilibili.com/video/BV19scReMEdS) |
| 1272 | 多模态推理的评测以及后训练 | - | AI 论文精读 | - | 17:44 | [link](https://www.bilibili.com/video/BV1C9XrYaEyz) |
| 1273 | 多模态动态评测（Oral） | - | AI 论文精读 | - | 20:41 | [link](https://www.bilibili.com/video/BV1P9XrYYEje) |
| 1274 | LOKI：基于多模态大模型的合成数据检测基准 | - | AI 论文精读 | - | 37:35 | [link](https://www.bilibili.com/video/BV1JJXrYdEXi) |
| 1275 | Sim-CoT 驱动高效隐式思考 | - | AI 论文精读 | - | 28:03 | [link](https://www.bilibili.com/video/BV1VGEC6fErh) |
| 1276 | 数据分布解读 RL 如何“学新不忘旧” | - | AI 论文精读 | - | 24:25 | [link](https://www.bilibili.com/video/BV1afE16NEXf) |
| 1277 | 数据驱动的大模型长度泛化推理新范式 | - | AI 论文精读 | - | 14:15 | [link](https://www.bilibili.com/video/BV1H2TF64Ek9) |
| 1278 | 利用智能体解锁地球观测的完整图景 | - | AI 论文精读 | - | 13:43 | [link](https://www.bilibili.com/video/BV1LUTj6FE9N) |
| 1279 | 冗余性解耦的高效长文本偏好优化 | - | AI 论文精读 | - | 30:48 | [link](https://www.bilibili.com/video/BV12uTQ6CEHz) |
| 1280 | AI科研加速营第1课｜用AI快速看懂一个研究方向 | - | AI 论文精读 | - | 17:37 | [link](https://www.bilibili.com/video/BV1jMY163EWE) |
| 1281 | AI科研加速营第2课｜AI论文工作流：检索、精读与核验 | - | AI 论文精读 | - | 12:32 | [link](https://www.bilibili.com/video/BV1tTen6ZEmy) |
| 1282 | AI科研加速营第3课｜建立可持续更新的研究上下文 | - | AI 论文精读 | - | 18:30 | [link](https://www.bilibili.com/video/BV11zec6NE3k) |
| 1283 | AI科研加速营第4课｜AI辅助实验设计：科学数据与计算一体化实践 | - | AI 论文精读 | - | 41:38 | [link](https://www.bilibili.com/video/BV1FTeG6dEQ4) |
| 1284 | AI科研加速营第5课｜AI辅助论文与课题申请书写作 | - | AI 论文精读 | - | 20:59 | [link](https://www.bilibili.com/video/BV1xLe16bE2p) |
| 1285 | AI科研加速营第6课｜把科研方法沉淀为可复用的Agent Skill | - | AI 论文精读 | - | 17:55 | [link](https://www.bilibili.com/video/BV1TZem6BEQP) |
| 1286 | AI科研加速营第7课｜通往可扩展、统一的蛋白基础模型之路 | - | AI 论文精读 | - | 33:54 | [link](https://www.bilibili.com/video/BV1sHem6AEXD) |
| 1287 | AI科研加速营第8课｜大模型时代的物质科学研究 | - | AI 论文精读 | - | 18:23 | [link](https://www.bilibili.com/video/BV1Vfhv6BEXx) |
| 1288 | AI科研加速营第9课｜地球科学中的科学智能：从工具的革命到革命的工具 | - | AI 论文精读 | - | 24:30 | [link](https://www.bilibili.com/video/BV16RhE6TEmM) |
| 1289 | OpenMMLab 环境配置 （一） Windows 11 CPU | - | AI 论文精读 | - | 18:43 | [link](https://www.bilibili.com/video/BV1Bh41157gL) |
| 1290 | 通用、统一且灵活的开源算法平台 OpenMMLab 2.0 / CVPR 2023 （全英分享） | - | AI 论文精读 | - | 17:28 | [link](https://www.bilibili.com/video/BV1Zg4y1P7LB) |
| 1291 | 视觉基础模型的探索：MMPreTrain / CVPR 2023 (全英分享) | - | AI 论文精读 | - | 31:56 | [link](https://www.bilibili.com/video/BV11s4y1C7S9) |
| 1292 | 通用目标检测工具 MMDetection3.0 / CVPR 2023 （全英分享） | - | AI 论文精读 | - | 30:47 | [link](https://www.bilibili.com/video/BV1214y1274j) |
| 1293 | 图像与视频生成、编辑和增强工具 MMagic / CVPR 2023 （全英分享） | - | AI 论文精读 | - | 26:08 | [link](https://www.bilibili.com/video/BV1nX4y1q7DF) |
| 1294 | 面向人工智能的开放数据平台：OpenDataLab / CVPR 2023 （全英分享） | - | AI 论文精读 | - | 12:09 | [link](https://www.bilibili.com/video/BV1Hm4y1a7Xa) |
| 1295 | 【CVPR-2022】/ Kai Chen -- Overview of OpenMMLab and Recent Updates | - | AI 论文精读 | - | 38:09 | [link](https://www.bilibili.com/video/BV1H84y1z7Ce) |
| 1296 | 【CVPR-2022】/ Chen Change Loy -- Improving Video Super-Resolution | - | AI 论文精读 | - | 32:03 | [link](https://www.bilibili.com/video/BV1mP411P7za) |
| 1297 | 【CVPR-2022】/ Han Hu -- Convergence of Architectures and Learning Methods | - | AI 论文精读 | - | 33:38 | [link](https://www.bilibili.com/video/BV1vG411j79R) |
| 1298 | 【CVPR-2022】/ Hang Zhao -- Vision-centric 3D Perception | - | AI 论文精读 | - | 32:42 | [link](https://www.bilibili.com/video/BV1y44y1f72z) |
| 1299 | 【CVPR-2022】/ Haodong Duan -- Action Understanding in A Human-centric View | - | AI 论文精读 | - | 24:33 | [link](https://www.bilibili.com/video/BV1iG4y1p78W) |
| 1300 | Wenwei Zhang / General Detection with MMDetection | - | AI 论文精读 | - | 34:02 | [link](https://www.bilibili.com/video/BV1A8411F7Ti) |
| 1301 | OpenMMLab：视觉、语言与生成式人工智能开源平台 | - | AI 论文精读 | - | 21:25 | [link](https://www.bilibili.com/video/BV1z94y18767) |
| 1302 | OpenMMLab基础模型研究进展 | - | AI 论文精读 | - | 28:52 | [link](https://www.bilibili.com/video/BV1tC4y157hc) |
| 1303 | OpenDataLab —— 一个面向人工智能的开放数据平台 | - | AI 论文精读 | - | 14:37 | [link](https://www.bilibili.com/video/BV1334y1G7RA) |
| 1304 | MMagic —— 图像与视频生成、编辑及增强工具库 | - | AI 论文精读 | - | 21:40 | [link](https://www.bilibili.com/video/BV1P94y187HE) |
| 1305 | MMDetection：从通用目标检测迈向多模态智能体 | - | AI 论文精读 | - | 33:54 | [link](https://www.bilibili.com/video/BV1134y1u7dq) |
| 1306 | 书生·浦语大模型全链路开源体系 | - | AI 论文精读 | - | 36:24 | [link](https://www.bilibili.com/video/BV1Vx421X72D) |
| 1307 | 轻松玩转书生·浦语大模型趣味 Demo | - | AI 论文精读 | - | 21:15 | [link](https://www.bilibili.com/video/BV1AH4y1H78d) |
| 1308 | 茴香豆：搭建你的 RAG 智能助理 | - | AI 论文精读 | - | 42:26 | [link](https://www.bilibili.com/video/BV1QA4m1F7t4) |
| 1309 | XTuner 微调 LLM：1.8B、多模态、Agent | - | AI 论文精读 | - | 72:29 | [link](https://www.bilibili.com/video/BV15m421j78d) |
| 1310 | LMDeploy 量化部署 LLM-VLM 实践 | - | AI 论文精读 | - | 52:30 | [link](https://www.bilibili.com/video/BV1tr421x75B) |
| 1311 | Lagent & AgentLego 智能体应用搭建 | - | AI 论文精读 | - | 35:40 | [link](https://www.bilibili.com/video/BV1Xt4217728) |
| 1312 | OpenCompass 大模型评测实战 | - | AI 论文精读 | - | 45:36 | [link](https://www.bilibili.com/video/BV1Pm41127jU) |
| 1313 | 大模型微调数据构造（补充课程） | - | AI 论文精读 | - | 38:14 | [link](https://www.bilibili.com/video/BV1Dx4y1z7Ju) |
| 1314 | 多模态简述 | - | AI 论文精读 | - | 46:34 | [link](https://www.bilibili.com/video/BV12E421A76T) |
| 1315 | LMDeploy 量化部署 InternVL 浦语灵笔实践 | - | AI 论文精读 | - | 7:19 | [link](https://www.bilibili.com/video/BV11m421373q) |
| 1316 | XTuner 微调 LLaVA 实践 | - | AI 论文精读 | - | 28:28 | [link](https://www.bilibili.com/video/BV1vZ421M7ig) |
| 1317 | AI实战营第二期 开营仪式 | - | AI 论文精读 | - | 66:24 | [link](https://www.bilibili.com/video/BV1sc411V74M) |
| 1318 | Github八万star，开源计算机视觉神器OpenMMLab | - | AI 论文精读 | - | 27:02 | [link](https://www.bilibili.com/video/BV1js4y1i72P) |
| 1319 | 深度学习预训练与MMPretrain | - | AI 论文精读 | - | 38:07 | [link](https://www.bilibili.com/video/BV1PN411y7C1) |
| 1320 | 目标检测与MMDetection | - | AI 论文精读 | - | 89:59 | [link](https://www.bilibili.com/video/BV1Ak4y1p7W9) |
| 1321 | MMDetection代码课 | - | AI 论文精读 | - | 46:49 | [link](https://www.bilibili.com/video/BV1Tm4y1q7fy) |
| 1322 | 语义分割与MMSegmentation | - | AI 论文精读 | - | 37:05 | [link](https://www.bilibili.com/video/BV1gV4y1m74P) |
| 1323 | 玩转AIGC神器MMagic | - | AI 论文精读 | - | 31:24 | [link](https://www.bilibili.com/video/BV1gM4y1n7vP) |
| 1324 | 【OpenMMLab 2.0 系列直播】OpenMMLab 2.0 整体介绍 | - | AI 论文精读 | - | 22:15 | [link](https://www.bilibili.com/video/BV1Yd4y1z7bo) |
| 1325 | 【OpenMMLab 2.0 系列直播】MMEngine & MMCV 介绍 | - | AI 论文精读 | - | 82:27 | [link](https://www.bilibili.com/video/BV15B4y1779M) |
| 1326 | 【OpenMMLab 2.0 系列直播】MMClassification 介绍 | - | AI 论文精读 | - | 28:11 | [link](https://www.bilibili.com/video/BV1x24y1R7mD) |
| 1327 | 【OpenMMLab 2.0 系列直播】MMSelfsup 介绍 | - | AI 论文精读 | - | 15:53 | [link](https://www.bilibili.com/video/BV1214y1h7CJ) |
| 1328 | 【OpenMMLab 2.0 系列直播】MMDetection 介绍 | - | AI 论文精读 | - | 31:26 | [link](https://www.bilibili.com/video/BV19G411g7w9) |
| 1329 | 【OpenMMLab 2.0 系列直播】MMDetection3D 介绍 | - | AI 论文精读 | - | 17:32 | [link](https://www.bilibili.com/video/BV1YD4y117w6) |
| 1330 | 【OpenMMLab 2.0 系列直播】OpenMMLab 社区荣誉体系介绍 | - | AI 论文精读 | - | 16:50 | [link](https://www.bilibili.com/video/BV1kB4y1J7u9) |
| 1331 | 【OpenMMLab 2.0 系列直播】MMSegmentation 介绍 | - | AI 论文精读 | - | 42:06 | [link](https://www.bilibili.com/video/BV1F841147JZ) |
| 1332 | 【OpenMMLab 2.0 系列直播】 MMAction2 介绍 | - | AI 论文精读 | - | 18:03 | [link](https://www.bilibili.com/video/BV1V841147Jp) |
| 1333 | 【OpenMMLab 2.0 系列直播】MMPose 介绍 | - | AI 论文精读 | - | 33:39 | [link](https://www.bilibili.com/video/BV11B4y1J7oD) |
| 1334 | 【OpenMMLab 2.0 系列直播】 MMEditing & MMGeneration 介绍 | - | AI 论文精读 | - | 34:12 | [link](https://www.bilibili.com/video/BV1Xd4y1M7zE) |
| 1335 | 【OpenMMLab 2.0 系列直播】MMOCR 介绍 | - | AI 论文精读 | - | 43:42 | [link](https://www.bilibili.com/video/BV1wY4y1K7DZ) |
| 1336 | 【OpenMMLab 2.0 系列直播】MMRazor 介绍 | - | AI 论文精读 | - | 51:11 | [link](https://www.bilibili.com/video/BV1ug411e7Jp) |
| 1337 | 【OpenMMLab 2.0 系列直播】MMYOLO 介绍 | - | AI 论文精读 | - | 26:03 | [link](https://www.bilibili.com/video/BV19e4y1674D) |
| 1338 | 【OpenMMLab 2.0 系列直播】RTMDet | - | AI 论文精读 | - | 36:58 | [link](https://www.bilibili.com/video/BV1e841147GD) |
| 1339 | 大模型时代下视觉网络的创新设计与拓展 / 热门研究 云际会#1 | - | AI 论文精读 | - | 136:51 | [link](https://www.bilibili.com/video/BV18L411m7jU) |
| 1340 | 多模态大模型的前奏：迈向真实世界的通用感知 / 热门研究云际会#2 | - | AI 论文精读 | - | 118:53 | [link](https://www.bilibili.com/video/BV1W24y1c7mB) |
| 1341 | 探索之路：OCR 领域在大模型浪潮中的创新契机 / 热门研究云际会#3 | - | AI 论文精读 | - | 119:15 | [link](https://www.bilibili.com/video/BV1Lh411E787) |
| 1342 | 多模态扩散模型的革新应用 / 热门研究云际会#4 | - | AI 论文精读 | - | 123:44 | [link](https://www.bilibili.com/video/BV1pP411273K) |
| 1343 | 基于 SiliconCloud 平台使用 MindSearch | - | AI 论文精读 | - | 18:13 | [link](https://www.bilibili.com/video/BV163sxeZEPi) |
| 1344 | AI 实战营开营仪式 | - | AI 论文精读 | - | 48:06 | [link](https://www.bilibili.com/video/BV1o3411X7MB) |
| 1345 | 1 计算机视觉算法基础与OpenMMLab介绍 | - | AI 论文精读 | - | 114:53 | [link](https://www.bilibili.com/video/BV1Ty4y1X7X1) |
| 1346 | 2 计算机视觉之图像分类算法基础 | - | AI 论文精读 | - | 91:03 | [link](https://www.bilibili.com/video/BV1js4y1W7CN) |
| 1347 | 3 图像分类代码实战与超算平台介绍 | - | AI 论文精读 | - | 117:34 | [link](https://www.bilibili.com/video/BV1MA411k7NT) |
| 1348 | 4 目标检测算法基础 | - | AI 论文精读 | - | 75:28 | [link](https://www.bilibili.com/video/BV1Ay4y1Q7mC) |
| 1349 | 5 MMDetection 代码教学 | - | AI 论文精读 | - | 134:41 | [link](https://www.bilibili.com/video/BV1Av4y1475i) |
| 1350 | 6 语义分割算法基础 | - | AI 论文精读 | - | 61:09 | [link](https://www.bilibili.com/video/BV1s24y1W7Xa) |
| 1351 | 7 MMSegmentation 代码教学 | - | AI 论文精读 | - | 79:20 | [link](https://www.bilibili.com/video/BV1eT411R7Jq) |
| 1352 | AI实战营 结营仪式 | - | AI 论文精读 | - | 17:33 | [link](https://www.bilibili.com/video/BV1ge4y1c7tY) |
| 1353 | 书生·浦语大模型全链路开源体系 | - | AI 论文精读 | - | 42:00 | [link](https://www.bilibili.com/video/BV1Rc411b7ns) |
| 1354 | 轻松玩转书生·浦语大模型趣味Demo | - | AI 论文精读 | - | 45:49 | [link](https://www.bilibili.com/video/BV1Ci4y1z72H) |
| 1355 | 基于 InternLM 和 LangChain 搭建你的知识库 | - | AI 论文精读 | - | 39:17 | [link](https://www.bilibili.com/video/BV1sT4y1p71V) |
| 1356 | XTuner 大模型单卡低成本微调实战 | - | AI 论文精读 | - | 94:01 | [link](https://www.bilibili.com/video/BV1yK4y1B75J) |
| 1357 | XTuner 大模型低成本微调作业讲解——个人小助手认知微调实践 | - | AI 论文精读 | - | 15:58 | [link](https://www.bilibili.com/video/BV13t4y1o75X) |
| 1358 | LMDeploy 大模型量化部署实践 | - | AI 论文精读 | - | 91:12 | [link](https://www.bilibili.com/video/BV1iW4y1A77P) |
| 1359 | OpenCompass 大模型评测 | - | AI 论文精读 | - | 51:31 | [link](https://www.bilibili.com/video/BV1Gg4y1U7uc) |

## Per entry

- **1、PyTorch介绍与张量的创建** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1ov411M7xL)
- **2、PyTorch张量的运算API（上）** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1wQ4y1q7Bm)
- **3、PyTorch张量的运算API（下）** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1Hq4y1R7dM)
- **4、PyTorch的Dataset与DataLoader详细使用教程** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1yP4y1L7cC)
- **5、深入剖析PyTorch DataLoader源码** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1kq4y1G75V)
- **6、PyTorch中搭建分类网络实例** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1VF411a7oz)
- **7、深入剖析PyTorch nn.Module源码** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1ch411b7yP)
- **8、深入剖析PyTorch的state_dict、parameters、modules源码** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV12g411K7oq)
- **9、深入剖析PyTorch的nn.Sequential及ModuleList源码** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1Cb4y187H1)
- **10、PyTorch autograd使用教程** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1vL411u7bL)
- **11、PyTorch中如何进行向量微分、矩阵微分与计算雅克比行列式** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1Xr4y1r7wa)
- **12、如何在PyTorch中训练模型** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1wL411g7rv)
- **13、详细推导自动微分Forward与Reverse模式** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1PF411h7Ew)
- **14、保存与加载PyTorch训练的模型和超参数** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1U341187TM)
- **15、Dropout原理以及其TF/Torch/Numpy源码实现** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1gL4y1p7ww)
- **16、PyTorch中进行卷积残差模块算子融合** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1sU4y1u7TM)
- **17、ConvMixer模型原理及其PyTorch逐行实现** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1K34y1o74P)
- **18、深入剖析PyTorch中的Transformer API源码** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1o44y1Y7cp)
- **19、Transformer模型Encoder原理精讲及其PyTorch逐行实现** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1cP4y1V7GF)
- **20、Transformer模型Decoder原理精讲及其PyTorch逐行实现** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1Qg411N74v)
- **21、Transformer Masked loss原理精讲及其PyTorch逐行实现** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1dh411s7FW)
- **22、PyTorch nn.Conv2d卷积网络使用教程** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1644y1h7LN)
- **23、手写并验证滑动相乘实现PyTorch二维卷积** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1dP4y137er)
- **24、手写并验证向量内积实现PyTorch二维卷积** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1Qb4y1i7n5)
- **25、手写实现nn.TransposedConv转置卷积** - [B station](https://www.bilibili.com/video/BV1fM4y1F7j5)
- **26、手写卷积与转置卷积的代码总结** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV13U4y1K7op)
- **27、手写实现PyTorch的DilatedConv和GroupConv** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1UY411W7W8)
- **28、Vision Transformer(ViT)模型原理及PyTorch逐行实现** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1cS4y1M7wo)
- **29、PyTorch RNN的原理及其手写复现** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV13i4y1R7jB)
- **30、PyTorch LSTM和LSTMP的原理及其手写复现** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1zq4y1m7aH)
- **31、PyTorch GRU的原理及其手写复现** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1jm4y1Q7uh)
- **32、基于PyTorch的文本分类项目模型与训练代码讲解** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1eD4y1F7o4)
- **33、完整讲解PyTorch多GPU分布式训练代码编写** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1xZ4y1S7dG)
- **34、Swin Transformer论文精讲及其PyTorch逐行复现** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1kF411v7vg)
- **35、基于PyTorch手写Attention-based Seq2Seq模型** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1ML411w7k7)
- **36、PyTorch训练加速技巧与爱因斯坦标示法** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1ZY411b78A)
- **37、Word Embedding原理精讲及其PyTorch API教程讲解** - [B station](https://www.bilibili.com/video/BV1wm4y1o7o5)
- **38、ConvNeXt论文导读与模型精讲** - [B station](https://www.bilibili.com/video/BV1iP4y1M7nk)
- **39、ConvNeXt模型代码逐行讲解** - [B station](https://www.bilibili.com/video/BV11Y41137VA)
- **40、ConvNeXt分布式训练代码逐行讲解** - [B station](https://www.bilibili.com/video/BV1uP4y1u7qd)
- **41、ResNet模型精讲以及PyTorch复现逐行讲解** - [B station](https://www.bilibili.com/video/BV1K3411p764)
- **42、Masked AutoEncoder(MAE)论文导读与模型详细介绍** - [B station](https://www.bilibili.com/video/BV1u94y1f7NH)
- **43、逐行讲解Masked AutoEncoder(MAE)的PyTorch代码** - [B station](https://www.bilibili.com/video/BV1JS4y1N7XE)
- **44、Layer Normalization论文导读与原理精讲** - [B station](https://www.bilibili.com/video/BV1Ma411i76P)
- **45、五种归一化的原理与PyTorch逐行手写实现讲解(BatchNorm/LayerNorm/InsNorm/GroupNorm/WeightNorm)** - [B station](https://www.bilibili.com/video/BV1Pq4y1a7pH)
- **46、四种Position Embedding的原理与PyTorch手写逐行实现（Transformer/ViT/Swin-T/MAE）** - [B station](https://www.bilibili.com/video/BV1DF411u7ST)
- **47、GAN原理讲解与PyTorch手写逐行讲解** - [B station](https://www.bilibili.com/video/BV1VT4y1e796)
- **48、快速复现PyTorch的Weight Normalization** - [B station](https://www.bilibili.com/video/BV1NZ4y117VT)
- **49、cGAN及LSGAN的原理与PyTorch手写逐行讲解** - [B station](https://www.bilibili.com/video/BV1444y1G7y2)
- **50、NormalizingFlow(标准化流)论文导读与原理精讲** - [B station](https://www.bilibili.com/video/BV1dS4y1c7xB)
- **51、基于PyTorch ResNet18的果蔬分类逐行代码讲解** - [B station](https://www.bilibili.com/video/BV1vZ4y1h7X9)
- **论文分享ICML 2026：RAG场景下的不确定性量化研究** - [B station](https://www.bilibili.com/video/BV1NPNY67EH4)
- **论文分享OMAC：多智能体协作的整体优化框架** - [arXiv:2505.11765](https://arxiv.org/abs/2505.11765) | [project](https://github.com/xiwenchao/OMAC) | [B station](https://www.bilibili.com/video/BV1JUK26mEcb)
- **论文分享HetRL：异构环境下的大模型强化学习调度框架** - [arXiv:2607.12345](https://arxiv.org/abs/2607.12345) | [project](https://github.com/hetrl-project/HetRL) | [B station](https://www.bilibili.com/video/BV1APMS6AEYR)
- **论文分享SONAR：去中心化学习不是“连得越多越好”** - [project](https://mlsys.org/virtual/2026/oral/3857) | [B station](https://www.bilibili.com/video/BV1DHuQ6HEch)
- **论文分享BOOST：让低秩大模型在多GPU上真正跑快** - [arXiv:2512.12131](https://arxiv.org/abs/2512.12131) | [project](https://github.com/Arcana-2236/BOOST) | [B station](https://www.bilibili.com/video/BV1A4gJ6XEYs)
- **论文分享OSWorld-Human：电脑使用智能体离“高效”还有多远** - [arXiv:2506.16042](https://arxiv.org/abs/2506.16042) | [project](https://github.com/WukLab/osworld-human) | [B station](https://www.bilibili.com/video/BV14bgA6jEqk)
- **论文分享 Cocoon：相关噪声提升差分隐私训练精度，为什么系统成本却会暴涨** - [project](https://www.usenix.org/conference/osdi26/presentation/kim-donghwan) | [B station](https://www.bilibili.com/video/BV1dVhc63EzM)
- **论文分享 CSLE：强化学习安全策略如何从模拟器走向真实网络系统** - [project](https://proceedings.mlsys.org/paper_files/paper/2026/hash/87eaaa8605a1a472d9a9756e7500517b-Abstract-Conference.html]) | [B station](https://www.bilibili.com/video/BV13Rt96VEnk)
- **论文分享 FLoRIST：联邦 LoRA 如何兼顾精度、通信与异构客户端** - [arXiv:2506.09199](https://arxiv.org/abs/2506.09199) | [project](https://github.com/DASS-Lab-Group/FLoRIST) | [B station](https://www.bilibili.com/video/BV1pwY46aExv)
- **【VALSE2025】0606 顾实《APR：脑启发与认知计算》** - [B station](https://www.bilibili.com/video/BV1SGu4zaEeb)
- **【VALSE2025】0606 叶茫《APR：大模型安全与伦理》** - [B station](https://www.bilibili.com/video/BV18Gu4zaEqp)
- **【VALSE2025】0606 谢伟迪《APR：医疗通用大模型》** - [B station](https://www.bilibili.com/video/BV18Gu4zaEcj)
- **【VALSE2025】0606 张兆翔《APR：世界模型理论与框架》** - [B station](https://www.bilibili.com/video/BV1YnuWzbEQi)
- **【VALSE2025】0606 袁粒《APR：视频生成基础模型》** - [B station](https://www.bilibili.com/video/BV16NuWzzEJP)
- **【VALSE2025】0606 俞扬《大会主旨报告：大模型背景下的强化学习》** - [B station](https://www.bilibili.com/video/BV1u2ptzNEHf)
- **【VALSE2025】0606 白翔《大会主旨报告：迈向通用文字识别：文档智能模型的进展与趋势》** - [B station](https://www.bilibili.com/video/BV1PUpWz7EDh)
- **【VALSE2025】0606 程明明《大会主旨报告：高效视觉感知与个性化生成》** - [B station](https://www.bilibili.com/video/BV1fZpWzgEQz)
- **【VALSE2025】0608 马月昕《Workshop5：大场景多对象的重建与生成》** - [B station](https://www.bilibili.com/video/BV1ha4qzgEsh)
- **【VALSE2025】0608 王程《Workshop5：大场景多对象的重建与生成》** - [B station](https://www.bilibili.com/video/BV18a4qzgEQg)
- **【VALSE2025】0608 窦志扬《Workshop20：优秀学生论坛》** - [B station](https://www.bilibili.com/video/BV1ab4qzGEZf)
- **【VALSE2025】0608 黄文柯《Workshop20：优秀学生论坛》** - [B station](https://www.bilibili.com/video/BV1Xb4qzGE4Z)
- **【VALSE2025】0608 卫雅珂《Workshop20：优秀学生论坛》** - [B station](https://www.bilibili.com/video/BV16V4qzpEL7)
- **【VALSE2025】0608 倪旻恒《Workshop20：优秀学生论坛》** - [B station](https://www.bilibili.com/video/BV16V4qzpEJF)
- **【VALSE2025】0608 王健伊《Workshop20：优秀学生论坛》** - [B station](https://www.bilibili.com/video/BV1FV4qzWEed)
- **【VALSE2025】0608 刘世隆《Workshop20：优秀学生论坛》** - [B station](https://www.bilibili.com/video/BV1FV4qzWECs)
- **【VALSE2025】0608 刘欣鹏《Workshop20：优秀学生论坛》** - [B station](https://www.bilibili.com/video/BV1FV4qzWESa)
- **【VALSE2025】0608 陈科研《Workshop20：优秀学生论坛》** - [B station](https://www.bilibili.com/video/BV1nV4qzWEju)
- **【VALSE2025】0608 姚江超《Tutorial 4：可信机器学习》** - [B station](https://www.bilibili.com/video/BV12E4mzfEpb)
- **【VALSE2025】0608 张杰《Tutorial 4：可信机器学习》** - [B station](https://www.bilibili.com/video/BV1KJ4mzFECJ)
- **【VALSE2025】0608 韩波《Tutorial 4：可信机器学习》** - [B station](https://www.bilibili.com/video/BV1RP4mzgE3d)
- **【VALSE2025】0608 张严浩《Workshop6：视觉通用模型》** - [B station](https://www.bilibili.com/video/BV1tsn2zLEch)
- **【VALSE2025】0608 王栋《Workshop6：视觉通用模型》** - [B station](https://www.bilibili.com/video/BV1Txn2zyEPb)
- **【VALSE2025】0608 王兴刚《Workshop6：视觉通用模型》** - [B station](https://www.bilibili.com/video/BV1dun2zsEKg)
- **【VALSE2025】0608 代季峰《Workshop6：视觉通用模型》** - [B station](https://www.bilibili.com/video/BV1QLn2znEth)
- **【VALSE2025】0608 陈隆《Workshop6：视觉通用模型》** - [B station](https://www.bilibili.com/video/BV1YRn2z9EYY)
- **【VALSE2025】0607 谢琦《Tutorial3：深度学习网络架构设计》** - [B station](https://www.bilibili.com/video/BV1yMn1zTEej)
- **【VALSE2025】0607 黄高《Tutorial3：深度学习网络架构设计》** - [B station](https://www.bilibili.com/video/BV1n7n1zcEhi)
- **【VALSE2025】0607 董胤蓬《Workshop17：人工智能大模型安全》** - [B station](https://www.bilibili.com/video/BV1ENnqzTEeG)
- **【VALSE2025】0607 周文柏《Workshop17：人工智能大模型安全》** - [B station](https://www.bilibili.com/video/BV1sDniz2EZs)
- **【VALSE2025】0607 郭青《Workshop17：人工智能大模型安全》** - [B station](https://www.bilibili.com/video/BV1xDniz2Eem)
- **【VALSE2025】0607 韦星星《Workshop17：人工智能大模型安全》** - [B station](https://www.bilibili.com/video/BV1N7Hcz7EHJ)
- **【VALSE2025】0607 蔺琛皓《Workshop17：人工智能大模型安全》** - [B station](https://www.bilibili.com/video/BV1P7HczjEWZ)
- **【VALSE2025】0607 王珂尧《Workshop17：人工智能大模型安全》** - [B station](https://www.bilibili.com/video/BV1N5HczEEaq)
- **【VALSE2025】0607 朱翔昱《Workshop9：生物特征识别遇上AI+Science》** - [B station](https://www.bilibili.com/video/BV1gXn9zuEvZ)
- **【VALSE2025】0607 刘宁《Workshop9：生物特征识别遇上AI+Science》** - [B station](https://www.bilibili.com/video/BV1nhn9zWEbT)
- **【VALSE2025】0607 李晓白《Workshop9：生物特征识别遇上AI+Science》** - [B station](https://www.bilibili.com/video/BV1Hhn9zWEtV)
- **【VALSE2025】0607 常乐《Workshop9：生物特征识别遇上AI+Science》** - [B station](https://www.bilibili.com/video/BV1Hbn9zREMC)
- **【VALSE2025】0607 郑钰辉《Workshop1：多模态遥感通用模型》** - [B station](https://www.bilibili.com/video/BV15tnRzLE5o)
- **【VALSE2025】0607 王正《Workshop7：多模态认知计算》** - [B station](https://www.bilibili.com/video/BV1vHnXzrE75)
- **【VALSE2025】0607 沈为《Workshop7：多模态认知计算》** - [B station](https://www.bilibili.com/video/BV1RHnXz6EgJ)
- **【VALSE2025】0607 魏云超《Workshop7：多模态认知计算》** - [B station](https://www.bilibili.com/video/BV1RHnXz6EGG)
- **【VALSE2025】0607 张勇《Workshop7：多模态认知计算》** - [B station](https://www.bilibili.com/video/BV1LHnXzrEMP)
- **【VALSE2025】0607 梁小丹《Workshop7：多模态认知计算》谢洪涛** - [B station](https://www.bilibili.com/video/BV1RHnXz6EFn)
- **【VALSE2025】0607 梁小丹《Workshop7：多模态认知计算》** - [B station](https://www.bilibili.com/video/BV1eWnXzgEjc)
- **【VALSE2025】0607 徐文超《Workshop7：多模态认知计算》** - [B station](https://www.bilibili.com/video/BV1ZonXz2EJU)
- **【VALSE2025】0607 孙浩《Tutorial2：科学智能（AI for Science）》** - [B station](https://www.bilibili.com/video/BV1yKn3z6EQX)
- **【VALSE2025】0607 陈键飞《Tutorial1：大模型基础理论结构与微调》** - [B station](https://www.bilibili.com/video/BV1q8n4zgECU)
- **【VALSE2025】0607 岳翔宇《Workshop12：AI4Science，诺贝尔奖后的思考》** - [B station](https://www.bilibili.com/video/BV178n4zgE6U)
- **【VALSE2025】0607 王笑楠《Workshop12：AI4Science，诺贝尔奖后的思考》** - [B station](https://www.bilibili.com/video/BV1Ndn4zpE8v)
- **【VALSE2025】0607 王立威《Tutorial1：大模型基础理论结构与微调》** - [B station](https://www.bilibili.com/video/BV11dn4zHExR)
- **【VALSE2025】0607 朱霖潮《Workshop12：AI4Science，诺贝尔奖后的思考》** - [B station](https://www.bilibili.com/video/BV1cNntzjEGy)
- **【VALSE2025】0607 邵斌《Workshop12：AI4Science，诺贝尔奖后的思考》** - [B station](https://www.bilibili.com/video/BV1S2n4ztErt)
- **【VALSE2025】0607 吴保东《Workshop12：AI4Science，诺贝尔奖后的思考》** - [B station](https://www.bilibili.com/video/BV1mSn4zxEbo)
- **【VALSE2025】0607 张奇《Workshop13：大模型基础理论-从理论视角看待大模型技术发展》** - [B station](https://www.bilibili.com/video/BV1hNJRzTEcK)
- **【VALSE2025】0607 方聪《Workshop13：大模型基础理论-从理论视角看待大模型技术发展》** - [B station](https://www.bilibili.com/video/BV18KJRziEL8)
- **【VALSE2025】0607 黄维然《Workshop13：大模型基础理论-从理论视角看待大模型技术发展》** - [B station](https://www.bilibili.com/video/BV1uKJRziE1b)
- **【VALSE2025】0607 龚铁梁《Workshop13：大模型基础理论-从理论视角看待大模型技术发展》** - [B station](https://www.bilibili.com/video/BV1hKJRziEPp)
- **【VALSE2025】0607 蒋宁《Workshop13：大模型基础理论-从理论视角看待大模型技术发展》** - [B station](https://www.bilibili.com/video/BV1uKJRziEd5)
- **【VALSE2025】0607 车万翔《Workshop13：大模型基础理论-从理论视角看待大模型技术发展》** - [B station](https://www.bilibili.com/video/BV1uKJRziEUa)
- **【VALSE2025】0607 石野《Workshop10：基于生成式AI驱动的具身智能》** - [B station](https://www.bilibili.com/video/BV14XJCzvESS)
- **【VALSE2025】0607 穆尧《Workshop10：基于生成式AI驱动的具身智能》** - [B station](https://www.bilibili.com/video/BV14XJCzvERJ)
- **【VALSE2025】0607 盛律《Workshop10：基于生成式AI驱动的具身智能》** - [B station](https://www.bilibili.com/video/BV1h2JCzzEGd)
- **【VALSE2025】0607 张直政《Workshop10：基于生成式AI驱动的具身智能》** - [B station](https://www.bilibili.com/video/BV182JCzzE4V)
- **【VALSE2023】0610 高文《特征编码与数字视网膜》** - [B station](https://www.bilibili.com/video/BV1iV411579w)
- **【VALSE2023】0610 陈熙霖 《计算机视觉-从孤立到系统性方法》** - [B station](https://www.bilibili.com/video/BV1n14y1B7x6)
- **【VALSE2023】0610 吴建鑫《神经网络模型轻量化设计》** - [B station](https://www.bilibili.com/video/BV1Fu4y1174x)
- **【VALSE2023】0610 刘烨斌《基于NeRF的三维视觉年度进展报告》** - [B station](https://www.bilibili.com/video/BV16x4y1X7WG)
- **【VALSE2023】0610 张兆翔《类脑智能》** - [B station](https://www.bilibili.com/video/BV1Pk4y1G7zj)
- **【VALSE2023】0610 夏勇《医学影像智能分析年度进展》** - [B station](https://www.bilibili.com/video/BV1Bj411r7Ex)
- **【VALSE2023】0610 朱军《扩散概率模型的前沿进展》** - [B station](https://www.bilibili.com/video/BV1Rh4y1C7T7)
- **【VALSE2023】0610 章国锋《基于隐式神经表示的三维重建、渲染与定位》** - [B station](https://www.bilibili.com/video/BV1H94y1C7mL)
- **【VALSE2023】0610 刘偲《开放视觉感知》** - [B station](https://www.bilibili.com/video/BV1pM4y1p75v)
- **【VALSE2023】0610 侯淇彬《开放域目标检测与识别年度进展》** - [B station](https://www.bilibili.com/video/BV1Yz4y1s7wC)
- **【VALSE2023】0610 王利民《视频动作分析与识别》** - [B station](https://www.bilibili.com/video/BV1Uz4y1s76K)
- **【VALSE2023】0610 胡瀚《视觉自监督学习年度进展评述》** - [B station](https://www.bilibili.com/video/BV1J44y1w79r)
- **【VALSE2023】0610 程塨《遥感目标检测》** - [B station](https://www.bilibili.com/video/BV1D14y1i7wW)
- **【VALSE2023】0610 邓伟洪《人脸感知计算年度进展报告》** - [B station](https://www.bilibili.com/video/BV12z4y1p7cr)
- **【VALSE2023】0610 邓成/杨二昆《多模态融合感知年度进展综述》** - [B station](https://www.bilibili.com/video/BV1YP411t73r)
- **【VALSE2023】0610 魏哲巍《图表示学习》** - [B station](https://www.bilibili.com/video/BV1244y1w7YT)
- **【VALSE2023】0610 刘成林《文档智能：最新进展与趋势》** - [B station](https://www.bilibili.com/video/BV1FV4y1v7W6)
- **【VALSE2023】0611 吴思《Tutorial ：计算神经科学-上》** - [B station](https://www.bilibili.com/video/BV1dj411r73d)
- **【VALSE2023】0611 吴思《Tutorial ：计算神经科学-下》** - [B station](https://www.bilibili.com/video/BV1fu411J7jb)
- **【VALSE2023】0611《Workshop：目标检测与分割-上》** - [B station](https://www.bilibili.com/video/BV1N8411o72f)
- **【VALSE2023】0611《Workshop：目标检测与分割-下》** - [B station](https://www.bilibili.com/video/BV1fX4y177r8)
- **【VALSE2023】0611《Workshop ：视觉知识和多重知识表达》** - [B station](https://www.bilibili.com/video/BV1dh4y1r7nX)
- **【VALSE2023】0611《Workshop ：围绕手机的计算影像学》** - [B station](https://www.bilibili.com/video/BV1j94y1y76C)
- **【VALSE2023】0611《Workshop ：机器人具身智能》** - [B station](https://www.bilibili.com/video/BV1L8411R7f7)
- **【VALSE2023】0611《Tutorial：从Transformer到GPT》** - [B station](https://www.bilibili.com/video/BV1AV4y1v7xw)
- **【VALSE2023】0611《Workshop：混合现实中的视觉与学习技术》** - [B station](https://www.bilibili.com/video/BV1Du4y1B7zE)
- **【VALSE2023】0611《Workshop：物联网与工业应用》** - [B station](https://www.bilibili.com/video/BV16u4y1R7aJ)
- **【VALSE2023】0611《Workshop ：女性研究者论坛》** - [B station](https://www.bilibili.com/video/BV1o14y1i7hs)
- **【VALSE2023】0612《Workshop：多模态大模型与提示学习》** - [B station](https://www.bilibili.com/video/BV1WV41137is)
- **【VALSE2023】0612《Workshop：三维视觉技术前沿》** - [B station](https://www.bilibili.com/video/BV1j44y1c7Yd)
- **【VALSE2023】0612《Workshop：大模型背景下的自动驾驶与车路协同》** - [B station](https://www.bilibili.com/video/BV1nN41187mk)
- **【VALSE2023】0612《Workshop：人工智能与科学计算》** - [B station](https://www.bilibili.com/video/BV1gF411Z7v2)
- **【VALSE2023】0612《Workshop：语言文字识别与理解》** - [B station](https://www.bilibili.com/video/BV1LX4y1j7HM)
- **【VALSE2023】0612《Workshop：自监督视觉表征学习》** - [B station](https://www.bilibili.com/video/BV1gm4y1p7yW)
- **【VALSE2023】0612《Workshop：遥感影像解译》** - [B station](https://www.bilibili.com/video/BV1yu4y1R7f6)
- **【VALSE2023】0612《Workshop：优秀学生论坛》** - [B station](https://www.bilibili.com/video/BV1pN41187Xf)
- **【VALSE2023】0612《Workshop：多模态认知计算》** - [B station](https://www.bilibili.com/video/BV1bj411z7nD)
- **【VALSE2023】0611《Workshop ：ChatGPT 与计算机视觉》** - [B station](https://www.bilibili.com/video/BV1m14y1v74v)
- **【VALSE2023】0611《Workshop ：大模型对 CV/PR 的挑战与机会》** - [B station](https://www.bilibili.com/video/BV1C14y1v7CP)
- **【VALSE2024】0507《Workshop ：多模态感知与对话》** - [B station](https://www.bilibili.com/video/BV1CU411o77f)
- **【VALSE2024】0507《Workshop ：遥感图像智能解译论坛》** - [B station](https://www.bilibili.com/video/BV1D7421f7kx)
- **【VALSE2024】0507《Workshop ：端到端自动驾驶》** - [B station](https://www.bilibili.com/video/BV13b421q7Vx)
- **【VALSE2024】0507《Workshop ：多模态大模型》** - [B station](https://www.bilibili.com/video/BV11M4m1k7ba)
- **【VALSE2024】0507《Workshop ：脑启发的视觉与学习》** - [B station](https://www.bilibili.com/video/BV1gb421q7hM)
- **【VALSE2024】0507《Workshop ：优秀学生论坛》** - [B station](https://www.bilibili.com/video/BV1Cf421R7xc)
- **【VALSE2024】0506《Tutorial：开放词汇视觉感知论坛》** - [B station](https://www.bilibili.com/video/BV1uf421d7Vk)
- **【VALSE2024】0506《Workshop ：面向移动端的AI图像增强》** - [B station](https://www.bilibili.com/video/BV1gZ421x7fG)
- **【VALSE2024】0506《Workshop ：三维重建与生成》** - [B station](https://www.bilibili.com/video/BV1DD421G7ws)
- **【VALSE2024】0506《Workshop ：大模型赋能智慧医疗》** - [B station](https://www.bilibili.com/video/BV14r42157TN)
- **【VALSE2024】0506《Workshop ：具身智能的视觉与学习》** - [B station](https://www.bilibili.com/video/BV1Bw4m1U7du)
- **【VALSE2024】0506《Workshop ：大模型理论与机理》** - [B station](https://www.bilibili.com/video/BV19f421R7we)
- **【VALSE2024】0506《Workshop ：视觉大模型高效迁移》** - [B station](https://www.bilibili.com/video/BV1EM4m1k7w6)
- **【VALSE2024】0505 李鸿升《特邀报告：图像生成和视频生成若干前沿技术探索》** - [B station](https://www.bilibili.com/video/BV161421i7QW)
- **【VALSE2024】0505 严骏驰《APR：世界模型增强的自动驾驶》** - [B station](https://www.bilibili.com/video/BV1FD421V7A1)
- **【VALSE2024】0505 吴小俊《特邀报告：多模态视觉融合方法：是否存在性能极限？》** - [B station](https://www.bilibili.com/video/BV1Ft421T74U)
- **【VALSE2024】0505 杨易《特邀报告：混合模型驱动的内容生成与具身智能》** - [B station](https://www.bilibili.com/video/BV1ss421w7eq)
- **【VALSE2024】0505 施柏鑫《APR：神经形态相机视觉计算》** - [B station](https://www.bilibili.com/video/BV1Js42137CA)
- **【VALSE2024】0505 杨耀东《APR：从偏好对齐到价值对齐与超对齐》** - [B station](https://www.bilibili.com/video/BV1Qi421U7yb)
- **【VALSE2024】0505 王兴刚《APR：面向大模型的新型高效率网络架构》** - [B station](https://www.bilibili.com/video/BV1Gt421T7Z4)
- **【VALSE2024】0505 俞扬《APR：世界模型与具身决策》** - [B station](https://www.bilibili.com/video/BV1aT421S7T5)
- **【VALSE2024】0505 马月昕《特邀报告：三维场景理解的前世、今生与未来》** - [B station](https://www.bilibili.com/video/BV1Ff421d7n4)
- **【VALSE2024】0505 卢志武《APR：视频生成》** - [B station](https://www.bilibili.com/video/BV1eZ421s794)
- **【VALSE2024】0505 赵恒爽《APR：视觉基础大模型》** - [B station](https://www.bilibili.com/video/BV1Rf421R715)
- **【VALSE2024】0505 林倞《APR：面向具身智能的多模态感知与交互》** - [B station](https://www.bilibili.com/video/BV1BZ421s7LD)
- **【VALSE2024】0505 高林《APR：三维高斯泼溅（3D Gaussian Splatting）》** - [B station](https://www.bilibili.com/video/BV11r421j7tV)
- **【VALSE2024】0505 谢凌曦《APR：视觉通用人工智能》** - [B station](https://www.bilibili.com/video/BV1mD421G7zJ)
- **【VALSE2024】0505 代季峰《APR：智能体视觉》** - [B station](https://www.bilibili.com/video/BV1eM4m1k7jY)
- **【VALSE2024】0505 陈华钧《APR：符号知识和大模型》** - [B station](https://www.bilibili.com/video/BV1Hz421Y7LG)
- **【VALSE2024】0505《2023-2024年度CV与ML领域重要学术进展》** - [B station](https://www.bilibili.com/video/BV1ex4y1H7gC)
- **【VALSE2024】0507《Workshop ：异构联邦学习》** - [B station](https://www.bilibili.com/video/BV1rD421G76t)
- **52、Excel/Csv文件数据转成PyTorch张量导入模型代码逐行讲解** - [B station](https://www.bilibili.com/video/BV1nR4y1N7Vj)
- **53、NormalizingFlow(标准化流)的PyTorch代码逐行讲解** - [B station](https://www.bilibili.com/video/BV1QF411j7ee)
- **54、Probabilistic Diffusion Model概率扩散模型理论与完整PyTorch代码详细解读** - [B station](https://www.bilibili.com/video/BV1b541197HX)
- **55、PyTorch的交叉熵、信息熵、二分类交叉熵、负对数似然、KL散度、余弦相似度的原理与代码讲解** - [B station](https://www.bilibili.com/video/BV1Sv4y1A7dz)
- **56、U-Net用于图像分割以及人声伴奏分离原理代码讲解** - [B station](https://www.bilibili.com/video/BV1C54y1o77i)
- **57、Autoregressive Diffusion Model自回归扩散模型用于序列预测论文讲解** - [B station](https://www.bilibili.com/video/BV1pZ4y1t7dc)
- **58、Improved Diffusion的PyTorch代码逐行深入讲解** - [B station](https://www.bilibili.com/video/BV1sG411s7vV)
- **59、基于CLIP/ViT模型搭建相似图像检索系统** - [B station](https://www.bilibili.com/video/BV1BB4y1a76V)
- **60、基于cVAE+Flow+GAN的效果最好语音合成VITS模型论文精讲** - [B station](https://www.bilibili.com/video/BV1wU4y1q7po)
- **61、基于cVAE+Flow+GAN的效果最好语音合成VITS模型代码逐行讲解** - [B station](https://www.bilibili.com/video/BV1VG411h75N)
- **62、Score Diffusion Model分数扩散模型理论与完整PyTorch代码详细解读** - [B station](https://www.bilibili.com/video/BV1Dd4y1A7oz)
- **63、必看！概率扩散模型(DDPM)与分数扩散模型(SMLD)的联系与区别** - [B station](https://www.bilibili.com/video/BV1QG4y1674Q)
- **64、扩散模型加速采样算法DDIM论文精讲与PyTorch源码逐行解读** - [B station](https://www.bilibili.com/video/BV1JY4y1N7dn)
- **65、【特别视频】AI教程评论区在线答疑之2022-10-25** - [B station](https://www.bilibili.com/video/BV1Wt4y1T7Nu)
- **66、Classifier Guided Diffusion条件扩散模型论文与PyTorch代码详细解读** - [B station](https://www.bilibili.com/video/BV1m84y1e7hP)
- **67、DiffusionLM 基于扩散模型的语言模型论文原理精讲** - [B station](https://www.bilibili.com/video/BV1zt4y1P7HN)
- **68、VQVAE预训练模型的论文原理及PyTorch代码逐行讲解** - [B station](https://www.bilibili.com/video/BV14Y4y1X7wb)
- **69、VQGAN+Transformer自回归建模图像生成的论文原理细致讲解** - [B station](https://www.bilibili.com/video/BV1mh411g7r5)
- **70、VQGAN+GPT1自回归建模+采样部分的代码讲解** - [B station](https://www.bilibili.com/video/BV1uu4y1R7LV)
- **71、VQGAN模型+VQ离散化模块的代码讲解** - [B station](https://www.bilibili.com/video/BV1cM411R7dY)
- **72、爆火的GPT-2论文讲解** - [B station](https://www.bilibili.com/video/BV1Ma4y1R72i)
- **73、爆火必看的nano-GPT2 Pytorch经典代码逐行讲解** - [B station](https://www.bilibili.com/video/BV11N4y1479K)
- **74、GPT-3论文原理讲解** - [B station](https://www.bilibili.com/video/BV1CT4y1s7dx)
- **75、Llama源码讲解之RoPE旋转位置编码** - [B station](https://www.bilibili.com/video/BV1Zr421c76A)
- **76、Llama源码讲解之RMS-Norm** - [B station](https://www.bilibili.com/video/BV1u1421k7rH)
- **77、Llama源码讲解之GroupQueryAttention和KV-cache** - [B station](https://www.bilibili.com/video/BV186421f7RL)
- **78、Llama源码讲解之Transformer** - [B station](https://www.bilibili.com/video/BV1mT421k7gB)
- **79、Llama源码讲解之自回归采样生成算法** - [B station](https://www.bilibili.com/video/BV1Bi421Y7Lo)
- **80、Byte Pair Encoding 源码逐行讲解** - [B station](https://www.bilibili.com/video/BV12x4y1t75q)
- **81、LLaMA-1 论文导读** - [B station](https://www.bilibili.com/video/BV1Pb42177gr)
- **82、LLaMA-2 论文导读** - [B station](https://www.bilibili.com/video/BV1Q4421Z7Zw)
- **83、如何计算GPT模型的FLOPs及参数量** - [B station](https://www.bilibili.com/video/BV1iQsYeCEoe)
- **84、GPT-4o/Moshi实时语音对话多模态算法讲解** - [B station](https://www.bilibili.com/video/BV1VQCUYyE6a)
- **85、Differential Transformer 论文原理逐段讲解** - [B station](https://www.bilibili.com/video/BV1Jq1PYPEYG)
- **【读评论】博士up主竟被粉丝要求女装？| 10w粉丝成就奖牌开箱** - [B station](https://www.bilibili.com/video/BV1gF411G7tB)
- **【十万粉丝福利】厦大博士一家三口齐跳”小鸡恰恰舞“** - [B station](https://www.bilibili.com/video/BV1tr4y1W7hq)
- **【疫情下的厦大】中秋节傍晚的全员核酸检测** - [B station](https://www.bilibili.com/video/BV1TL4y187c5)
- **博士必备发型？聊聊我从茂密的秀发到强者发型的华丽蜕变** - [B station](https://www.bilibili.com/video/BV1wL4y1878e)
- **导师怒斥研究生【延毕警告】** - [B station](https://www.bilibili.com/video/BV17o4y1U7bF)
- **读 研 冰 城** - [B station](https://www.bilibili.com/video/BV1Jq4y1s7dc)
- **【万粉福利】博士夫妻羞耻挑战女团舞只为讨好粉丝？| 你最最最重要** - [B station](https://www.bilibili.com/video/BV1HK411H73d)
- **【我们领证啦】将故事写成我们，走过八年的校园爱情，终于在春暖花开的厦门，修成正果啦！** - [B station](https://www.bilibili.com/video/BV1ip4y1Q7c7)
- **【厦大vlog】开学在即，博士学长带你逛厦大 | 中国最美大学 | 春暖花开的厦门大学** - [B station](https://www.bilibili.com/video/BV1MQ4y1N7Pb)
- **【婚纱照Vlog】走过了八年的爱情，在春暖花开的厦门，我们拍婚纱照啦！！！！！** - [B station](https://www.bilibili.com/video/BV1ke411x7xj)
- **【从两个少年到三口之家】你陪我长大，我陪你慢慢变老！** - [B station](https://www.bilibili.com/video/BV1fA4y1S7Re)
- **【SPSS+AMOS实战教程-01】论文结构&模型构建&问卷设计 | 快速学会实证论文 | 保姆级教程 | 数据来源问卷网** - [B station](https://www.bilibili.com/video/BV1ED4y1m7B4)
- **【SPSS+AMOS实战教程-02】信度&效度检验 | 快速学会实证论文 | 保姆级教程 | 数据来源问卷网** - [B station](https://www.bilibili.com/video/BV1eK411K7tD)
- **【SPSS+AMOS实战教程-03】AMOS基本操作 | 快速学会实证论文 | 保姆级教程 | 数据来源问卷网** - [B station](https://www.bilibili.com/video/BV1ja4y1j7Th)
- **【SPSS+AMOS实战教程-04】Amos拟合优度与假设检验 | 快速学会实证论文 | 保姆级教程 | 数据来源问卷网** - [B station](https://www.bilibili.com/video/BV18D4y197K3)
- **【SPSS+AMOS实战教程-05】中介效应检验与AMOS操作 | 快速学会实证论文 | 保姆级教程 | 数据来源问卷网** - [B station](https://www.bilibili.com/video/BV1Wi4y177SC)
- **【SPSS+AMOS实战教程-06】调节效应检验与AMOS操作 | 快速学会实证论文 | 保姆级教程** - [B station](https://www.bilibili.com/video/BV1Qp4y1t7pb)
- **【5分钟学会SPSS】描述性统计与相关性分析 | 史上最易上手 | 快速学会实证论文 | 保姆级教程** - [B station](https://www.bilibili.com/video/BV1xL411x7AU)
- **【5分钟学会SPSS】验证性因子分析与探索性因子分析 | 史上最易上手 | 快速学会实证论文 | 保姆级教程** - [B station](https://www.bilibili.com/video/BV1wf4y1w7zV)
- **【5分钟学会SPSS】独立样本t检验和方差分析 | 史上最易上手 | 快速学会实证论文 | 保姆级教程** - [B station](https://www.bilibili.com/video/BV1GU4y1A76Z)
- **【5分钟学会SPSS】多元线性回归分析 | 史上最易上手 | 快速学会实证论文 | 保姆级教程** - [B station](https://www.bilibili.com/video/BV1La411v7Ny)
- **【读研必看】导师选的好，研究生毕业早！博士学长吐血分享** - [B station](https://www.bilibili.com/video/BV1hB4y1J7gv)
- **【论文降重】希望每一个毕业季的同学都能刷到这个视频！** - [B station](https://www.bilibili.com/video/BV1t44y1G7BW)
- **请大数据推给想要读博或正在读博的同学** - [B station](https://www.bilibili.com/video/BV1PL4y1L78q)
- **学长实测论文查重工具，源文鉴真的有那么香吗？** - [B station](https://www.bilibili.com/video/BV1dq4y1a7Me)
- **十个博士九个有退学的冲动？学长是如何熬过四年读博之路的…** - [B station](https://www.bilibili.com/video/BV16L4y177Jf)
- **学长实测不同价位论文查重工具，结果竟让我大呼离谱？** - [B station](https://www.bilibili.com/video/BV1j34y147TL)
- **【毕业论文格式排版】本科研究生必看：章节标题样式/页眉页码设置/生成自定义目录/图表格式/参考文献交叉引用** - [B station](https://www.bilibili.com/video/BV1744y1N7ts)
- **【研究生必备】选对了期刊，发表SCI/核心期刊不是梦！** - [B station](https://www.bilibili.com/video/BV11Q4y1B79Z)
- **取消博士生发表论文要求？以后博士真的可以轻松毕业了么？** - [B station](https://www.bilibili.com/video/BV1k341117L3)
- **【安利向】学长亲测最好用的论文写作工具 | 功能强大，高效实现文献阅读、笔记管理、文献引用 | 科研效率提高十倍** - [B station](https://www.bilibili.com/video/BV1Bv41137PG)
- **【考博】联系导师如何写邮件？导师的回复什么含义？厦大博士学长的经验分享！** - [B station](https://www.bilibili.com/video/BV1wb4y1m7n4)
- **【研究生必看】学生干部经历重要么？研究生要不要加入学生会、做班委？** - [B station](https://www.bilibili.com/video/BV18f4y1J7Tp)
- **【干货】三步带你快速高效阅读学术文献 | 博士学长千篇阅读经验总结 | 保姆级教程 | 建议收藏** - [B station](https://www.bilibili.com/video/BV1qo4y1U7eh)
- **【准研究生必看】做好这些准备，顺利完成从本科生到研究生的华丽蜕变！** - [B station](https://www.bilibili.com/video/BV1Fq4y1D73u)
- **【干货】论文写作中的文献引用格式 | 如何引用文献 | 毕业论文写作必备 | 保姆级教程 | 建议收藏** - [B station](https://www.bilibili.com/video/BV1XU4y177pe)
- **【研究生必备】史上最强文献检索攻略 | 三步带你查找下载到想要的最新文献 | 保姆级教程 一看就会 | 建议收藏** - [B station](https://www.bilibili.com/video/BV1mq4y1Q73y)
- **【论文小白100问】引言和绪论的区别有哪些？该如何选择？** - [B station](https://www.bilibili.com/video/BV1Af4y1Y7FV)
- **【从本科双非到985博士】这三个习惯，后悔没在大学就养成！| 本科生、研究生必看** - [B station](https://www.bilibili.com/video/BV1av411j7Ek)
- **【毕业答辩2】博士学长教你轻松应对答辩现场的老师提问！ | 答辩流程详解 | 汇报PPT | 现场提问回答策略** - [B station](https://www.bilibili.com/video/BV1X84y1F7f4)
- **【毕业答辩】做好这些准备，毕业论文答辩轻松通过！| 博士学长倾囊相授 | 答辩PPT制作 | 答辩必备问题 | 着装&物品准备** - [B station](https://www.bilibili.com/video/BV1mV411J7ov)
- **【论文降重】巨实用！毕业论文降重方法 | 三大招式助力学术小白顺利毕业| 保姆级教程 | 博士学长手把手带你毕业** - [B station](https://www.bilibili.com/video/BV1Py4y1s7h1)
- **【研究生必看】论文投稿最强攻略 | 期刊审稿流程 | 论文投稿方式** - [B station](https://www.bilibili.com/video/BV1cv411E7dF)
- **【干货】文献汇报这样做就对了！| 导师满意同学爱听 | 研究生组会汇报 | 保姆级教程 | 建议收藏** - [B station](https://www.bilibili.com/video/BV1qB4y1w7q7)
- **【研究生必看】英文不好如何写作SCI/SSCI英文论文 | 博士学长手把手带你写英文论文 | 保姆级教学 | 经验分享 | 建议收藏** - [B station](https://www.bilibili.com/video/BV16y4y1B7fU)
- **考 博 必 看 指 南 ！博士如何考？如何准备？申请考核制是什么？直博和硕博连读？** - [B station](https://www.bilibili.com/video/BV1gy4y187qn)
- **你真的适合读博士么？厦大博士学长经验分享适合读博的4大条件，快看看你都符合么？** - [B station](https://www.bilibili.com/video/BV1eK411J7cr)
- **【超干货】建议收藏！论文选题怎么选？博士学长带你五分钟学会论文选题！！！** - [B station](https://www.bilibili.com/video/BV1ra4y1a78B)
- **【干货】建议收藏 | 学术文献读什么？怎么读？| 博士学长吐血分享| 研究生必看 | 科研 | 论文心得** - [B station](https://www.bilibili.com/video/BV1xD4y1S7Wp)
- **【选导师】被逼跳楼？被变态导师性侵？博士学长经验分享研究生导师一定要这样选！！！** - [B station](https://www.bilibili.com/video/BV12V411C7Tf)
- **【论文拯救指南】干货！五分钟学会Endnote神器自动生成毕业论文参考文献引用格式，本科毕设和研究生小白进** - [B station](https://www.bilibili.com/video/BV1Qa4y1i7pA)
- **【论文拯救指南】干货！厦大博士学长手把手带你写毕业论文开题报告，本科毕设和研究生小白进** - [B station](https://www.bilibili.com/video/BV1Tz4y1d7iZ)
- **【论文拯救指南】厦大博士学长带你4句话搞定论文摘要，本科毕设和研究生小白进** - [B station](https://www.bilibili.com/video/BV1kz4y1R7ut)
- **【论文拯救指南】干货！厦大博士学长手把手带你写文献综述，本科毕设和研究生小白进** - [B station](https://www.bilibili.com/video/BV1j64y1M76u)
- **【干货】毕业论文云答辩？厦大博士学长分享线上答辩通关秘籍！大四、研三必看** - [B station](https://www.bilibili.com/video/BV1Bk4y1R7KJ)
- **【论文拯救指南】干货！厦大博士学长手把手带你写论文引言，本科毕设和研究生小白进** - [B station](https://www.bilibili.com/video/BV1Z54y1X7wr)
- **【干货推荐】这样学习Stata事半功倍，绝不会“一学就废”！** - [B station](https://www.bilibili.com/video/BV1pB4y117fn)
- **【干货】搞懂论文逻辑结构，读文献思路清晰，写论文下笔如神！** - [B station](https://www.bilibili.com/video/BV1sB4y1j71x)
- **【研究生学英语】听说读写，这样学英语就对了！** - [B station](https://www.bilibili.com/video/BV1AK411d7cD)
- **【安利】能随意编辑文字和图片的PDF神器，你见过吗？** - [B station](https://www.bilibili.com/video/BV1X8411A7sn)
- **学姐亲测火遍全网的ChatGPT能帮论文党做什么？| 文献阅读 |文献查找| 搭建提纲| 论文撰写| 技术支持** - [B station](https://www.bilibili.com/video/BV1QD4y1A7sZ)
- **用ChatGPT写了篇本科论文，查重率竟然达到？！** - [B station](https://www.bilibili.com/video/BV15M4y1S7ah)
- **【毕业论文】第一集：论文选题，好的开始是成功的一半** - [B station](https://www.bilibili.com/video/BV1X24y1b7RL)
- **【麦小哲】开题报告实用攻略，毕业论文必备，手把手带你完成开题报告撰写** - [B station](https://www.bilibili.com/video/BV1Fz4y1w7Tq)
- **【麦小哲】科研小白如何快速高效阅读文献？宝藏方法推荐，建议收藏** - [B station](https://www.bilibili.com/video/BV1kw411n7DL)
- **[论文简析]VAE: Auto-encoding Variational Bayes[1312.6114]** - [B station](https://www.bilibili.com/video/BV1q64y1y7J2)
- **[论文简析]ViT: Vision Transformer[2010.11929]** - [B station](https://www.bilibili.com/video/BV1di4y1N7pc)
- **[论文简析]How Do Vision Transformers Work?[2202.06709]** - [B station](https://www.bilibili.com/video/BV1UF41147AG)
- **[论文简析]Swin Transformer: Hierarchical ViT using Shifted Windows[2103.14030]** - [B station](https://www.bilibili.com/video/BV1e84y1F7Sc)
- **[论文简析]DETR: End-to-End Object Detection with Transfromers[2005.12872]** - [B station](https://www.bilibili.com/video/BV1T64y1D7NY)
- **[论文简析]NeRF: Representing Scenes as Neural Radiance Fields...[2003.08934]** - [B station](https://www.bilibili.com/video/BV1mV4y1M7TB)
- **[论文简析]Deep Unsupervised Learning using Nonequilibrium Thermodynamics[1503.03585]** - [B station](https://www.bilibili.com/video/BV19v4y1C7De)
- **[论文速览]LoRA: Low-Rank Adaptation of Large Language Models[2106.09685]** - [B station](https://www.bilibili.com/video/BV1wX4y1s7an)
- **[论文速览]Flamingo: a Visual Language Model for Few-Shot Learning[2204.14198]** - [B station](https://www.bilibili.com/video/BV1pu411G7ce)
- **[论文简析]A Generalist Agent / Gato[2205.06175]** - [B station](https://www.bilibili.com/video/BV1EK421k7Sy)
- **[论文简析]Does SSL Really Improve RL from Pixels?[2206.05266]** - [B station](https://www.bilibili.com/video/BV1gM411r7wq)
- **[论文简析]Dreamer V2[2010.02193]** - [B station](https://www.bilibili.com/video/BV15o4y1R7kT)
- **[论文简析]World Models[1803.10122]** - [B station](https://www.bilibili.com/video/BV1oz4y117qk)
- **[论文简析]Transformers are Sample Efficient World Models[2209.00588]** - [B station](https://www.bilibili.com/video/BV1i24y1Z78Q)
- **[论文简析]Reinforcement Learning with Augmented Data: RAD[2004.14990]** - [B station](https://www.bilibili.com/video/BV1ZS4y1h77B)
- **[论文简析]CURL[2004.04136]** - [B station](https://www.bilibili.com/video/BV14v411h7sq)
- **[论文简析]SPR: Data-Efficient RL with Self-Predictive Representations[2007.05929]** - [B station](https://www.bilibili.com/video/BV1bN411Q7Hz)
- **[论文简析]DrQ: Data regularized Q[2004.13649]** - [B station](https://www.bilibili.com/video/BV15p4y1h7Xu)
- **[论文简析]The Dormant Neuron Phenomenon in Deep Reinforcement Learning[2302.12902]** - [B station](https://www.bilibili.com/video/BV1r94y1w7tE)
- **[论文简析]XSkill: Cross Embodiment Skill Discovery[2307.09955]** - [B station](https://www.bilibili.com/video/BV1bj411L7yK)
- **[论文简析]Video Prediction Policy: A Generalist Robot Policy...[2412.14803]** - [B station](https://www.bilibili.com/video/BV1hZugzdE4F)
- **[论文速览]Efficient Action Tokenization for Vision-Language-Action Model[2501.09747]** - [B station](https://www.bilibili.com/video/BV1TuFpeKEXQ)
- **[论文简析]Rainbow:Combining Improvements in Deep Reinforcement Learning[1710.02298]** - [B station](https://www.bilibili.com/video/BV1W64y1x7MF)
- **[论文简析]PPG: Phasic Policy Gradient[2009.04416]** - [B station](https://www.bilibili.com/video/BV1uB4y1A7Ec)
- **[论文简析]SAC: Soft Actor-Critic Part 1[1801.01290]** - [B station](https://www.bilibili.com/video/BV1YK4y1T7b6)
- **[论文简析]SAC: Soft Actor-Critic Part 2[1812.05905]** - [B station](https://www.bilibili.com/video/BV13V411e7Qb)
- **[论文简析]C-Learning: Learning to .. via Recursive Classification[2011.08909]** - [B station](https://www.bilibili.com/video/BV1J64y1S7ZA)
- **[论文简析]Time-Contrastive Networks:Self-Supervised Learning from Video[1704.06888]** - [B station](https://www.bilibili.com/video/BV1Sr4y1A7bp)
- **[论文速览]Diffusion Policy: Visuomotor Policy Learning via Action Diff.[2303.04137]** - [B station](https://www.bilibili.com/video/BV1Cu411Y7d7)
- **[论文速览]Decision Transformer: RL via Sequence Modeling[2106.01345]** - [B station](https://www.bilibili.com/video/BV1zf4y1t7ka)
- **[论文简析]Visionary: Vision architecture discovery for robot learning[2103.14633]** - [B station](https://www.bilibili.com/video/BV1oo4y1k7Jo)
- **[论文简析]Neuroevolution of Self-interpretable Agents[2003.08165]** - [B station](https://www.bilibili.com/video/BV17Z4y1w7sX)
- **[论文简析]QT-Opt: Scalable Deep RL for Vision-Based Robotic Manipulation[1806.10293]** - [B station](https://www.bilibili.com/video/BV1Ey4y187bi)
- **[论文速览]DDPG&TD3[1509.02971][1802.09477]** - [B station](https://www.bilibili.com/video/BV1nU4y1u7h1)
- **[论文简析]SEER: Stored Embeddings for Efficient RL[2103.02886]** - [B station](https://www.bilibili.com/video/BV1rv411h7iS)
- **[论文简析]BCO: Behavioral Cloning from Observation[1805.01954]** - [B station](https://www.bilibili.com/video/BV1aN411X7YT)
- **[论文简析]A Framework for Efficient Robotic Manipulation[2012.07975]** - [B station](https://www.bilibili.com/video/BV1pL4y1u7KG)
- **[论文速览]VRL3: A Data-Driven Framework for Visual Deep Reinforcement L.[2202.10324]** - [B station](https://www.bilibili.com/video/BV1R841157aG)
- **[论文速览]Mask-based Latent Reconstruction for Reinforcement Learning[2201.12096]** - [B station](https://www.bilibili.com/video/BV12v4y1z7BM)
- **[论文简析]Learning Invariant Representations for RL without Reconstructi[2006.10742]** - [B station](https://www.bilibili.com/video/BV1EK4y1K7EL)
- **[论文简析]Stabilizing transformers for reinforcement learning[1910.06764]** - [B station](https://www.bilibili.com/video/BV1Jf4y1s7ac)
- **[论文简析]Efficient Transformers in RL using Actor-Learner Distillation[2104.01655]** - [B station](https://www.bilibili.com/video/BV1wZ4y1w7wP)
- **[论文速览]NeRF-RL: Reinforcement Learning with Neural Radiance Fields[2206.01634]** - [B station](https://www.bilibili.com/video/BV1tG4y1V7hn)
- **[论文简析]DADS: Dynamics-Aware Unsupervised Discovery of Skills[1907.01657]** - [B station](https://www.bilibili.com/video/BV165411w71J)
- **[论文简析]Off-DADS: Emergent Real-World Robotic Skills via off policy RL[2004.12974]** - [B station](https://www.bilibili.com/video/BV18y4y1h7P9)
- **[论文速览]Stabilizing Deep Q-Learning with ConvNets and ViT...[2107.00644]** - [B station](https://www.bilibili.com/video/BV12w411f74a)
- **[论文简析]Behavior From the Void: Unsupervised Active Pre-Training[2103.04551]** - [B station](https://www.bilibili.com/video/BV1By4y1t7aK)
- **[论文速览]Self-Supervised Policy Adaptation during Deployment[2007.04309]** - [B station](https://www.bilibili.com/video/BV1t54y1J7pd)
- **[论文简析]RL-CycleGAN: Reinforcement Learning Aware Simulation-To-Real[2006.09001]** - [B station](https://www.bilibili.com/video/BV1L54y1n7d3)
- **[论文速览]Synthetic Experience Replay[2303.06614]** - [B station](https://www.bilibili.com/video/BV1wx4y1P7hD)
- **[论文简析]Contrastive Language, Action, and State Pre-training...[2304.10782]** - [B station](https://www.bilibili.com/video/BV1UF411U7zk)
- **[论文速览]Implicit Behavioral Cloning / IBC[2109.00137]** - [B station](https://www.bilibili.com/video/BV18N411J7FD)
- **[论文夕拾]Diffusion Models for Robotics** - [B station](https://www.bilibili.com/video/BV1mV411c7na)
- **[论文简析]Crossway Diffusion: Improving Diffusion-based ... via SSL[2307.01849]** - [B station](https://www.bilibili.com/video/BV1Yp4y1F7nv)
- **[论文速览]A Self-Improving Generalist Agent for Robotic Manipulation[2306.11706]** - [B station](https://www.bilibili.com/video/BV1cx4y1y7PZ)
- **[论文速览]OpenVLA: An Open-Source Vision-Language-Action Model[2406.09246]** - [B station](https://www.bilibili.com/video/BV1m1421C7m7)
- **[论文速览]LLaRA: Supercharging Robot Learning Data for VLM Policy[2406.20095]** - [B station](https://www.bilibili.com/video/BV174421D7tW)
- **[论文速览]GENIMA: Generative Image as Action Models[2407.07875]** - [B station](https://www.bilibili.com/video/BV17S421971u)
- **[论文夕拾]Robot Manipulation in a Language Model Era** - [B station](https://www.bilibili.com/video/BV1BdCFYmEpa)
- **[论文速览]Latent Action Pretraining from Videos[2410.11758]** - [B station](https://www.bilibili.com/video/BV144KPeYE9v)
- **[论文速览]π_0: A Vision-Language-Action Flow Model for General Robot...[2410.24164]** - [B station](https://www.bilibili.com/video/BV142uFzWEdY)
- **[论文简析]DreamVLA: A Vision-Language-Action Model Dreamed...[2507.04447]** - [B station](https://www.bilibili.com/video/BV116utzwEZs)
- **[论文简析]Representation Learning with Contrastive Predictive Coding[1807.03748]** - [B station](https://www.bilibili.com/video/BV1fK4y1o7A1)
- **[论文速览]Data-Efficient Image Recog with Contrastive Predictive Coding[1905.09272]** - [B station](https://www.bilibili.com/video/BV1GU4y1H7b6)
- **[论文简析]SimCLR: A simple framework for contrastive learning[2002.05709]** - [B station](https://www.bilibili.com/video/BV1Cp4y1b7ex)
- **[论文简析]SwAV: Swapping Assignments between multiple Views[2006.09882]** - [B station](https://www.bilibili.com/video/BV1754y187Ki)
- **[论文简析]MoCo: Momentum Contrast Learning[1911.05722/2003.04297]** - [B station](https://www.bilibili.com/video/BV1av411874e)
- **[论文简析]BYOL: Bootstrap Your Own Latent[2006.07733]** - [B station](https://www.bilibili.com/video/BV1ki4y1T7X4)
- **[论文简析]DINO Emerging Properties in SelfSupervised Vision Transformers[2104.14294]** - [B station](https://www.bilibili.com/video/BV1H54y157kj)
- **[论文简析]SimSiam: Exploring Simple Siamese Representation Learning[2011.10566]** - [B station](https://www.bilibili.com/video/BV1Ah411Q7Lb)
- **[论文简析]Barlow Twins:Self-Supervised Learning via Redundancy Reduction[2103.03230]** - [B station](https://www.bilibili.com/video/BV1gZ4y1P7U1)
- **[论文速览]iBOT: Image BERT Pre-Training with Online Tokenizer[2111.07832]** - [B station](https://www.bilibili.com/video/BV1uM4y1q7Pa)
- **[论文简析]Evolving Losses for Unsupervised Video Representation Learning[2002.12177]** - [B station](https://www.bilibili.com/video/BV1Pp4y1h7Ke)
- **[论文简析]Broaden Your Views for Self-Supervised Video Learning[2103.16559]** - [B station](https://www.bilibili.com/video/BV1LQ4y1i7Zv)
- **[论文速览]Self-supervised Video Transformer[2112.01514]** - [B station](https://www.bilibili.com/video/BV17Y4y1g7Jw)
- **[论文简析]Extreme Masking for Learning Instance and Distributed Visual..[2206.04667]** - [B station](https://www.bilibili.com/video/BV1sY4y1G7St)
- **[论文简析]Learning by Aligning Videos in Time[2103.17260]** - [B station](https://www.bilibili.com/video/BV13f4y1b7Nt)
- **[论文简析]Probabilistic Representations for Video Contrastive Learning[2204.03946]** - [B station](https://www.bilibili.com/video/BV1RT4y1Y73n)
- **[论文简析]Propagate Yourself: Exploring Pixel-Level Consistency...[2011.10043]** - [B station](https://www.bilibili.com/video/BV1hV411x7wL)
- **[论文简析]Location-Aware Self-Supervised Transformers for Semantic Seg.[2212.02400]** - [B station](https://www.bilibili.com/video/BV1wk4y1i7eH)
- **[论文简析]Rethinking Pre-training and Self-training[2006.06882]** - [B station](https://www.bilibili.com/video/BV1pK4y1U7ts)
- **[论文简析]Energy-Inspired Self-Supervised Pretraining for Vision Models[2302.01384]** - [B station](https://www.bilibili.com/video/BV1hg4y1H7Gj)
- **[论文简析]Humble Teachers Teach Better Students for Semi-Supervised Object Detection** - [B station](https://www.bilibili.com/video/BV1SK4y1u7ix)
- **[论文简析]Towards Better Understanding of Self-Supervised Representation[2203.01881]** - [B station](https://www.bilibili.com/video/BV1fG411n7EC)
- **[论文简析]TransRank: SS Video...Ranking-based Transformation Recognition[2205.02028]** - [B station](https://www.bilibili.com/video/BV1zS4y1e7uY)
- **[论文速览]Object Discovery and Representation Networks[2203.08777]** - [B station](https://www.bilibili.com/video/BV1n34y1b7Uo)
- **[论文速览]Efficient Visual Pretraining with Contrastive Detection[2103.10957]** - [B station](https://www.bilibili.com/video/BV1bY411n7BP)
- **[论文简析]Directional SSL for Heavy Image Augmentations[2110.13555]** - [B station](https://www.bilibili.com/video/BV19U4y1o7SQ)
- **[论文速览]Invariant Information Clustering for Unsupervised Image...[1807.06653]** - [B station](https://www.bilibili.com/video/BV1t34y1t72d)
- **[论文速览]Video Rep. Learning by Recognizing Temporal Transformations[2007.10730]** - [B station](https://www.bilibili.com/video/BV1qU4y1X7cg)
- **[论文简析]β-VAE Learning basic visual concepts with a constrained variational...** - [B station](https://www.bilibili.com/video/BV1644y1q7Aj)
- **[论文简析]DCLGAN/SimDCL: Dual Contrastive Learning[2104.07689]** - [B station](https://www.bilibili.com/video/BV15v411j7N7)
- **[论文简析]Generative Scene Inference and Sampling...[1907.13052]** - [B station](https://www.bilibili.com/video/BV1aZ4y1R7Ne)
- **[论文简析]An Empirical Study of Training Self-Supervised ViT[2104.02057]** - [B station](https://www.bilibili.com/video/BV1UX4y1g7Dn)
- **[论文速览]Multi-Object ... with Iterative Variational Inference[1903.00450]** - [B station](https://www.bilibili.com/video/BV15a41127C9)
- **[论文简析]MONet: Unsupervised Scene Decomposition and Representation[1901.11390]** - [B station](https://www.bilibili.com/video/BV1CT4y1y7Hc)
- **[论文简析]Leveraging BG AUG to encourage semantic focus in SSCL[2103.12719]** - [B station](https://www.bilibili.com/video/BV1xX4y1G7Pe)
- **[论文简析]Object-Centric Learning with Slot Attention[2006.15055]** - [B station](https://www.bilibili.com/video/BV1QL4y1s7NK)
- **[论文简析]Equivariant Contrastive Learning[2111.00899]** - [B station](https://www.bilibili.com/video/BV1jS4y1Z7Py)
- **[论文简析]Big Self-Supervised Models are Strong Semi-Supervised Learners[2006.10029]** - [B station](https://www.bilibili.com/video/BV1Ey4y1t7zK)
- **[论文简析]Keeping Your Eye on the Ball: Trajectory Attention...[2106.05392]** - [B station](https://www.bilibili.com/video/BV1j3411i7jU)
- **[论文简析]Wasserstein Contrastive Representation Distillation: WCoRD[2012.08674]** - [B station](https://www.bilibili.com/video/BV1vw41197wC)
- **[论文速览]Masked Feature Prediction .Self-Supervised Visual Pre-Training[2112.09133]** - [B station](https://www.bilibili.com/video/BV1YS4y1Q7Qj)
- **[论文速览]AugSelf: Improving Transferability...Augmentation-Aware..[2111.09613]** - [B station](https://www.bilibili.com/video/BV1Ei4y1Z7Ld)
- **[论文速览]Nearest-Neighbor Contrastive Learning of Visual Representations[2104.14548** - [B station](https://www.bilibili.com/video/BV12f4y1M7Qq)
- **[论文速览]Solving Inefficiency of Self-supervised Representation Learning[2104.0876]** - [B station](https://www.bilibili.com/video/BV1FL4y1z7jq)
- **[论文简析]VideoMoCo: ...Temporally Adversarial Examples[2103.05905]** - [B station](https://www.bilibili.com/video/BV13f4y137Wc)
- **[论文速览]Theia: Distilling Diverse Vision Foundation Models for Robot..[2407.20179]** - [B station](https://www.bilibili.com/video/BV18W42197So)
- **[论文速览]Long Short View Feature Decomposition via Contrastive Video...[2109.11593]** - [B station](https://www.bilibili.com/video/BV1pQ4y1Q74S)
- **[论文简析]Vi2CLR: Video and Image for Visual Contrastive Learning of Representation** - [B station](https://www.bilibili.com/video/BV1ZQ4y1i7Wa)
- **[论文速览]Generative Modeling by Estimating Gradients of the Data Dist[1907.05600]** - [B station](https://www.bilibili.com/video/BV1WY4y1Q7fy)
- **[论文简析]Unsupervised Learning of Object Keypoints for Perception..[1906.11883]** - [B station](https://www.bilibili.com/video/BV15w411R7rB)
- **[论文简析]Progressive Stage-wise Learning for Unsupervised Feature.. [2106.05554]** - [B station](https://www.bilibili.com/video/BV1Fq4y1p7Ai)
- **[论文简析]Transf. Meta-learners for Implicit Neural Representations[2208.02801]** - [B station](https://www.bilibili.com/video/BV1QV4y167S7)
- **[论文速览]Jigsaw Clustering for Unsupervised Visual Representation Learn[2104.00323]** - [B station](https://www.bilibili.com/video/BV1Jg41177uE)
- **[论文速览]SS Video Representation Learning by Context&Motion Decoupling[2104.00862]** - [B station](https://www.bilibili.com/video/BV1qf4y157DW)
- **[论文简析]MixMAE & Mixed AE[2205.13137][2303.17152]** - [B station](https://www.bilibili.com/video/BV1cF411d77x)
- **[论文速览]Finite Scalar Quantization: VQ-VAE Made Simple[2309.15505]** - [B station](https://www.bilibili.com/video/BV1N84y1S779)
- **[论文简析]DropPos: Pre-Training ViTs by Reconstructing Dropped Positions[2309.03576]** - [B station](https://www.bilibili.com/video/BV1fu411u77K)
- **[论文速览]SODA: Bottleneck Diffusion Models for Representation Learning[2311.17901]** - [B station](https://www.bilibili.com/video/BV1jw411t7Kq)
- **[论文简析]Deconstructing Denoising Diffusion Models for SSL[2401.14404]** - [B station](https://www.bilibili.com/video/BV1bv421r7Sv)
- **[论文速览]Socratic Models: Zero-Shot Multimodal Reasoning[2204.00598]** - [B station](https://www.bilibili.com/video/BV1cS4y1n7yn)
- **[论文简析]Large Language Models as General Pattern Machines[2307.04721]** - [B station](https://www.bilibili.com/video/BV1EM4y1W7w1)
- **[论文速览]LaFTer: Label-Free Tuning of Zero-shot Classifier...[2305.18287]** - [B station](https://www.bilibili.com/video/BV1Rm4y1p72G)
- **[论文速览]OWL-ViT: Simple Open-Vocabulary Object Detection with ViT[2205.06230]** - [B station](https://www.bilibili.com/video/BV1x8411S7eZ)
- **[论文简析]GroupViT: Semantic Segmentation Emerges from Text Supervision[2202.11094]** - [B station](https://www.bilibili.com/video/BV1Bv4y127gH)
- **[论文简析]VATT: Video-Audio-Text Transformer[2104.11178]** - [B station](https://www.bilibili.com/video/BV1554y1j71k)
- **[论文简析]End-to-End Video-Language Transformers..Masked Visual-token..[2111.12681]** - [B station](https://www.bilibili.com/video/BV1UM4y1c7fh)
- **[论文简析]TAN: Temporal Alignment Networks for Long-term Video[2204.02968]** - [B station](https://www.bilibili.com/video/BV1194y1y7mF)
- **[论文简析]Improving fine-grained understanding in image-text pre-training[2401.0986]** - [B station](https://www.bilibili.com/video/BV15A4m1G7zj)
- **[论文简析]End-to-End Learning... from Uncurated Instructional Videos[1912.06430]** - [B station](https://www.bilibili.com/video/BV173411u7JE)
- **[论文简析]Region-Aware Pretraining for Open-Vocab. Object Det. w/ ViT[2305.07011]** - [B station](https://www.bilibili.com/video/BV1D14y1C7m8)
- **[论文简析]Toolformer: Language Models Can Teach Themselves to Use Tools[2302.04761]** - [B station](https://www.bilibili.com/video/BV1BV4y1a7iU)
- **[论文速览]ViperGPT: Visual Inference via Python Execution for Reasoning[2303.08128]** - [B station](https://www.bilibili.com/video/BV1BV4y1879K)
- **[论文简析]VoxPoser: Composable 3D Value Maps for Robotic...[2307.05973]** - [B station](https://www.bilibili.com/video/BV11h4y1j7D2)
- **[论文速览]LLaMA-Adapter: Efficient Fine-tuning..Zero-init Attention[2303.16199]** - [B station](https://www.bilibili.com/video/BV1Kp4y1L7ya)
- **[论文速览]Open-vocabulary Object Segmentation with Diffusion Models[2301.05221]** - [B station](https://www.bilibili.com/video/BV1VV4y1e78c)
- **[论文速览]Open Vocab. Semantic Seg.  with Patch Aligned Contrastive...[2212.04994]** - [B station](https://www.bilibili.com/video/BV1w94y1z7ey)
- **[论文简析]Representation Learning via Global Temporal Alignment and ...[2105.05217]** - [B station](https://www.bilibili.com/video/BV1CM4y1T7nj)
- **[论文速览]LLaVA: Visual Instruction Tuning[2304.08485]** - [B station](https://www.bilibili.com/video/BV1n14y1k7B9)
- **[论文速览]LongLoRA: Efficient Fine-tuning of Long-Context LLMs[2309.12307]** - [B station](https://www.bilibili.com/video/BV1PN411n7KX)
- **[论文简析]CLIP Dense Inference Yields Open-Vocab ... For-Free[2309.14289]** - [B station](https://www.bilibili.com/video/BV1Jj41187We)
- **[论文速览]Ferret: Refer and Ground Anything Anywhere at Any Granularity[2310.07704]** - [B station](https://www.bilibili.com/video/BV11h4y1z7mn)
- **[论文速览]VLMs are Zero-Shot Reward Models for RL[2310.12921]** - [B station](https://www.bilibili.com/video/BV1ne411R74d)
- **[论文速览]CRG: Improving Grounding in VLM w/o training[2403.02325]** - [B station](https://www.bilibili.com/video/BV1y2421T7R3)
- **[论文速览]A Simple LLM Framework for Long-Range Video Question-Answering[2312.17235]** - [B station](https://www.bilibili.com/video/BV1d2421N7VA)
- **[论文速览]Align before Fuse / ALBEF: ...[2107.07651]** - [B station](https://www.bilibili.com/video/BV1fx4y1U7ui)
- **[论文速览]Bootstrapping Language-Image Pre-training...[2201.12086]** - [B station](https://www.bilibili.com/video/BV1H1421Q7Ft)
- **[论文速览]BLIP-2 ...with Frozen Image Encoders and Large Language Models[2301.12597]** - [B station](https://www.bilibili.com/video/BV1Ci42197ab)
- **[论文速览]Ferret-v2: An Improved...for Referring and Grounding with LLMs[2404.07973]** - [B station](https://www.bilibili.com/video/BV12F4m1N7Mc)
- **[论文速览]Token Turing Machines[2211.09119]** - [B station](https://www.bilibili.com/video/BV1dV4y1f7J4)
- **[论文简析]NeRF in the Wild: NeRF for Unconstrained Photo Collections[2008.02268]** - [B station](https://www.bilibili.com/video/BV1iD4y1e7K9)
- **[论文简析]Exploring Self-attention for Image Recognition[2004.13621]** - [B station](https://www.bilibili.com/video/BV1nA411K7Z6)
- **[论文简析]FlowNet3D: Learning Scene Flow in 3D Point Clouds[1806.01411]** - [B station](https://www.bilibili.com/video/BV1U3411j7Fg)
- **[论文简析]NeRV: Neural Representations for Videos[2110.13903]** - [B station](https://www.bilibili.com/video/BV1Nf4y1K7j5)
- **[论文简析]TokenLearner: What Can 8 Learned Tokens Do for Images and vids[2106.11297]** - [B station](https://www.bilibili.com/video/BV1of4y1t77m)
- **[论文简析]BiFormer: Vision Transformer with Bi-Level Routing Attention[2303.08810]** - [B station](https://www.bilibili.com/video/BV1tF4111774)
- **[论文简析]When Shift Operation Meets Vision Transformer[2201.10801]** - [B station](https://www.bilibili.com/video/BV1CF411n7at)
- **[论文简析]DeepLab V3/V3+[1706.05587/1802.02611]** - [B station](https://www.bilibili.com/video/BV1by4y1g76s)
- **[论文速览]Deformable Convolutional Networks; DCN[1703.06211]** - [B station](https://www.bilibili.com/video/BV1C94y1272t)
- **[论文简析]DeepLab: Semantic Image Segmentation with DCN..[1606.00915]** - [B station](https://www.bilibili.com/video/BV1jf4y1Y7uM)
- **[论文简析]DAT: Vision Transformer with Deformable Attention[2201.00520]** - [B station](https://www.bilibili.com/video/BV1ir4y137BG)
- **[论文速览]Aggregating Nested Transformers[2105.12723]** - [B station](https://www.bilibili.com/video/BV1yq4y1H7mT)
- **[论文简析]X3D: Expanding Architectures for Efficient Video Recognition[2004.04730]** - [B station](https://www.bilibili.com/video/BV1qZ4y1F7Kf)
- **[论文简析]CeiT: Incorporating Convolution Designs into Visual Tr[2103.11816]** - [B station](https://www.bilibili.com/video/BV19L4y1B7Ad)
- **[论文速览]iFormer: Inception Transformer[2205.12956]** - [B station](https://www.bilibili.com/video/BV19L4y1P7ri)
- **[论文速览]Bottleneck Transformers for Visual Recognition[2101.11605]** - [B station](https://www.bilibili.com/video/BV1i64y1t7WN)
- **[论文简析]NAT: Neighborhood Attention Transformer[2204.07143]** - [B station](https://www.bilibili.com/video/BV1xF411g7LK)
- **[论文简析]XCiT: Cross-Covariance Image Transformers[2106.09681]** - [B station](https://www.bilibili.com/video/BV1n64y1Q7RX)
- **[论文简析]DeiT: Data-efficient Image Transformers[2012.12877]** - [B station](https://www.bilibili.com/video/BV1L5411P7rV)
- **[论文简析]TNT: Transformer in Transformer[2103.00112]** - [B station](https://www.bilibili.com/video/BV1KK4y1U7Uq)
- **[论文简析]Tokens-to-Token ViT: Training ViT from Scratch on ImageNet[2101.11986]** - [B station](https://www.bilibili.com/video/BV1yv411L7xN)
- **[论文简析]Dynamic Vision Transformers with Adaptive Sequence Length[2105.15075]** - [B station](https://www.bilibili.com/video/BV1s54y1H7Wb)
- **[论文简析]SlowFast Networks for Video Recognition[1812.03982]** - [B station](https://www.bilibili.com/video/BV1DV411J7gS)
- **[论文简析]MViT: Multiscale Vision Transformers[2104.11227]** - [B station](https://www.bilibili.com/video/BV1np4y1b7QY)
- **[论文简析]BEVT: BERT Pretraining of Video Transformers[2112.01529]** - [B station](https://www.bilibili.com/video/BV1R44y1h7CR)
- **[论文简析]Unified Transformer for Efficient Spatiotemporal...[2201.04676]** - [B station](https://www.bilibili.com/video/BV1CT4y1i7Fa)
- **[论文简析]MLP-Mixer: An all-MLP Architecture for Vision[2105.01601]** - [B station](https://www.bilibili.com/video/BV1xK4y197qL)
- **[论文速览]EViT: Expediting Vision Transformers via Token Reorganizations[2202.07800]** - [B station](https://www.bilibili.com/video/BV1HS4y1F7nU)
- **[论文简析]Is Space-Time Attention All You Need for Video Understanding?[2102.05095]** - [B station](https://www.bilibili.com/video/BV1dA411371w)
- **[论文简析]A Laplacian Pyramid Translation Network[2105.09188]** - [B station](https://www.bilibili.com/video/BV1V64y1h7nv)
- **[论文简析]Per-Pixel Classification is Not All You Need for Semantic Seg[2107.06278]** - [B station](https://www.bilibili.com/video/BV17f4y1A7XR)
- **[论文速览]Masked-attention Mask Tr. for Universal Image Segmentation[2112.01527]** - [B station](https://www.bilibili.com/video/BV1ob4y1B7hp)
- **[论文简析]MobileNets: Efficient CNN for Mobile Vision Applications[1704.04861]** - [B station](https://www.bilibili.com/video/BV1LB4y1c7Ap)
- **[论文简析]MobileNet V2: Inverted Residuals and Linear Bottlenecks[1801.04381]** - [B station](https://www.bilibili.com/video/BV1Fq4y1n7Mq)
- **[论文简析]Searching for MobileNet V3[1905.02244]** - [B station](https://www.bilibili.com/video/BV1vN411f7pY)
- **[论文简析]MnasNet: Platform-Aware Neural Architecture Search for Mobile[1807.11626]** - [B station](https://www.bilibili.com/video/BV1Wo4y127NM)
- **[论文简析]EfficientNet V1/V2[1905.11946/2104.00298]** - [B station](https://www.bilibili.com/video/BV1MV411E7Pq)
- **[论文简析]Mobile-Former: Bridging MobileNet and Transformer[2108.05895]** - [B station](https://www.bilibili.com/video/BV1CL4y1g76U)
- **[论文简析]Point Transformer[2012.09164]** - [B station](https://www.bilibili.com/video/BV1PA41157su)
- **[论文简析]Point Transformer V2[2210.05666]** - [B station](https://www.bilibili.com/video/BV1de4y157hR)
- **[论文速览]RetNet: A Successor to Transformer for Large Language Models[2307.08621]** - [B station](https://www.bilibili.com/video/BV1134y1G7uQ)
- **[论文简析]Vision Transformers Need Registers[2309.16588]** - [B station](https://www.bilibili.com/video/BV1up4y1c7JU)
- **[论文简析]Contrastive Learning for Unpaired Image-to-Image Translation[2007.15651]** - [B station](https://www.bilibili.com/video/BV14y4y1s7tS)
- **[论文简析]Multimodal Unsupervised Image-to-Image Translation[1804.04732]** - [B station](https://www.bilibili.com/video/BV1Pb4y1p78y)
- **[论文速览]Rethinking the Truly Unsupervised Image-to-Image Translation[2006.06500]** - [B station](https://www.bilibili.com/video/BV1qZ4y1z77v)
- **[论文简析]Unsupervised Image-to-Image Translation Networks[1703.00848]** - [B station](https://www.bilibili.com/video/BV1c34y187BW)
- **[论文简析]RetinaGAN: An Object-aware Approach to Sim-to-Real Transfer[2011.03148]** - [B station](https://www.bilibili.com/video/BV17o4y1X7Mk)
- **[论文简析]MoCoGAN-HD: A Good Image Generator Is What You Need...[2104.15069]** - [B station](https://www.bilibili.com/video/BV1gv411L7Dy)
- **[论文简析]VQ-VAE:Neural discrete representation learning[1711.00937]** - [B station](https://www.bilibili.com/video/BV1bb4y1i7j6)
- **[论文速览]Autoregressive Image Generation using Residual Quantization[2203.01941]** - [B station](https://www.bilibili.com/video/BV1gY411E7ge)
- **[论文速览]Personalizing Text2Img Generation using Textual Inversion[2208.01618]** - [B station](https://www.bilibili.com/video/BV1oH4y1k7RW)
- **[论文速览]Taming Transformers for High-Resolution Image Synthesis[2012.09841]** - [B station](https://www.bilibili.com/video/BV1ym4y1d7iP)
- **[论文简析]MaskGIT: Masked Generative Image Transformer[2202.04200]** - [B station](https://www.bilibili.com/video/BV1qS4y1r7p1)
- **[论文简析]Regularized Vector Quantization for Tokenized Image Synthesis[2303.06424]** - [B station](https://www.bilibili.com/video/BV1rG411o7pp)
- **[论文速览]Denoising Diffusion Probabilistic Models / DDPM[2006.11239]** - [B station](https://www.bilibili.com/video/BV1yA41167Dg)
- **[论文速览]Denoising Diffusion Implicit Models / DDIM[2010.02502]** - [B station](https://www.bilibili.com/video/BV1ic41157Vf)
- **[论文速览]Structured Denoising Diffusion Models in Discrete State-Spaces[2107.03006]** - [B station](https://www.bilibili.com/video/BV1R84y1H7k1)
- **[论文速览]Drag Your GAN: Interactive Point-based Manipulation...[2305.10973]** - [B station](https://www.bilibili.com/video/BV1Ju41177k3)
- **[论文简析]DreamBooth: Fine Tuning Text-to-Image Diffusion Models...[2208.12242]** - [B station](https://www.bilibili.com/video/BV18m4y1H7fs)
- **[论文速览]FreeU: Free Lunch in Diffusion U-Net[2309.11497]** - [B station](https://www.bilibili.com/video/BV1dk4y1F7dg)
- **[论文简析]Visual Autoregressive Modeling: ...via Next-Scale Prediction[2404.02905]** - [B station](https://www.bilibili.com/video/BV1pq421P7D4)
- **[论文速览]MixUp: Beyond Empirical Risk Minimization[1710.09412]** - [B station](https://www.bilibili.com/video/BV12q4y167SV)
- **[论文速览]RegMixup: Mixup as a Regularizer Can Surprisingly Improve...[2206.14502]** - [B station](https://www.bilibili.com/video/BV1jB4y1i7iw)
- **[论文夕拾]Mixed Sample Data Augmentations, Part 1** - [B station](https://www.bilibili.com/video/BV1rr4y1V7Dx)
- **[论文夕拾]Mixed Sample Data Augmentations, Part 2** - [B station](https://www.bilibili.com/video/BV1qt4y1h7kM)
- **[论文简析]Robust and Generalizable Visual ... via Random Convolutions[2007.13003]** - [B station](https://www.bilibili.com/video/BV1Kq4y1E7j3)
- **[论文速览]Simple Copy-Paste is a Strong Data Aug. for Instance Seg.[2012.07177]** - [B station](https://www.bilibili.com/video/BV1Hq4y1s7wB)
- **[论文速览]Visual Prompt Tuning / VPT[2203.12119]** - [B station](https://www.bilibili.com/video/BV18h4y127GG)
- **[论文简析]Red Circle: Visual Prompt Engineering for VLMs[2304.06712]** - [B station](https://www.bilibili.com/video/BV1wk4y1V7wo)
- **[论文简析]Finding an Unsupervised Image Segmenter in .. Generative Model[2105.08127]** - [B station](https://www.bilibili.com/video/BV1Dy4y1W7uM)
- **[论文简析]PolyFormer: Referring Image Seg. as Sequential Polygon Gen [2302.07387]** - [B station](https://www.bilibili.com/video/BV1wr4y1o7V5)
- **[论文简析]DiffSeg: Unsupervised Zero-Shot Seg. using Stable Diffusion[2308.12469]** - [B station](https://www.bilibili.com/video/BV1Sm4y1T74R)
- **[论文简析]Patching Open-Vocabulary Models by Interpolating Weights[2208.05592]** - [B station](https://www.bilibili.com/video/BV1tV411P73W)
- **[论文速览]Scalable Video Object Segmentation with Simplified Framework[2308.09903]** - [B station](https://www.bilibili.com/video/BV1Vu411g7Gm)
- **[论文速览]Learning to Learn with Generative Models of NN Checkpoints[2209.12892]** - [B station](https://www.bilibili.com/video/BV13H4y1j7Zd)
- **给女朋友做的AR元宇宙增强现实生日贺卡** - [B station](https://www.bilibili.com/video/BV17Y4y1z73F)
- **MATLAB竟然还能做增强现实AR元宇宙？** - [B station](https://www.bilibili.com/video/BV1wG41137oJ)
- **构建自己的图像分类数据集【两天搞定AI毕设】** - [B station](https://www.bilibili.com/video/BV1Jd4y1T7rw)
- **Pytorch预训练图像分类模型识别预测【两天搞定AI毕设】** - [B station](https://www.bilibili.com/video/BV1qe4y1D7zD)
- **Pytorch迁移学习训练自己的图像分类模型【两天搞定AI毕设】** - [B station](https://www.bilibili.com/video/BV1Ng411C7WY)
- **用训练得到的pytorch图像分类模型，识别图像、视频、摄像头画面【两天搞定AI毕设】** - [B station](https://www.bilibili.com/video/BV12d4y1P7xz)
- **测试集上评估Pytorch训练得到的图像分类模型【两天搞定AI毕业设计】** - [B station](https://www.bilibili.com/video/BV1bP411j7NK)
- **图像分类测试集语义特征降维可视化** - [B station](https://www.bilibili.com/video/BV1VB4y1z7xN)
- **图像分类可解释性分析实战-CAM热力图系列算法** - [B station](https://www.bilibili.com/video/BV1JG4y1s74x)
- **图像分类可解释性分析实战-Deep Feature Factorization** - [B station](https://www.bilibili.com/video/BV1Re4y1n73v)
- **图像分类可解释性分析实战-Captum工具包** - [B station](https://www.bilibili.com/video/BV1DN4y1N7fc)
- **图像分类可解释性分析实战-shap工具包** - [B station](https://www.bilibili.com/video/BV1vP4y1S7Xu)
- **图像分类可解释性分析实战-lime工具包** - [B station](https://www.bilibili.com/video/BV1a84y1i7Tz)
- **图像分类模型部署-Pytorch转ONNX** - [B station](https://www.bilibili.com/video/BV1cM4y187Xc)
- **Pytorch图像分类模型部署-ONNX Runtime本地终端推理** - [B station](https://www.bilibili.com/video/BV1AM4y187yR)
- **Pytorch图像分类部署-ONNX Runtime安卓手机APP** - [B station](https://www.bilibili.com/video/BV1cs4y1Q7nu)
- **Pytorch图像分类部署-ONNX Runtime浏览器Web前端** - [B station](https://www.bilibili.com/video/BV1Ja4y137fZ)
- **AidLux图像分类部署-安卓鸿蒙高通ARM** - [B station](https://www.bilibili.com/video/BV1oN411h7p1)
- **文本识别OCR神器 MMOCR【OpenMMLab】** - [B station](https://www.bilibili.com/video/BV1Ua411x7dB)
- **MMOCR代码实战（上）安装配置、预训练OCR模型预测** - [B station](https://www.bilibili.com/video/BV1hP4y1M7Zc)
- **MMOCR代码实战（中）AI给文字区域打马赛克** - [B station](https://www.bilibili.com/video/BV1nZ4y1z77X)
- **MMOCR代码实战（下）Kaggle验证码文本识别** - [B station](https://www.bilibili.com/video/BV1tL411A7bj)
- **Github高赞开源项目速览-AIGC与大语言模型-20230707** - [B station](https://www.bilibili.com/video/BV1eW4y1f72L)
- **Github高赞开源项目速览-AIGC的N种玩法-20230808** - [B station](https://www.bilibili.com/video/BV1cV411V7LU)
- **中医+人工智能黑科技：耳朵穴位经络图像识别** - [B station](https://www.bilibili.com/video/BV168411Z7Lt)
- **标注关键点检测数据集** - [B station](https://www.bilibili.com/video/BV19g4y1777q)
- **关键点检测数据集-Labelme格式转YOLO格式** - [B station](https://www.bilibili.com/video/BV1QX4y1B7eF)
- **关键点检测数据集-Labelme格式转MS COCO格式** - [B station](https://www.bilibili.com/video/BV1vc411J7GC)
- **YOLOV8关键点检测-预训练模型预测** - [B station](https://www.bilibili.com/video/BV1yg4y177ef)
- **YOLOV8关键点检测-训练自己的关键点检测模型** - [B station](https://www.bilibili.com/video/BV13a4y157HE)
- **YOLOV8关键点检测-用训练得到的模型预测图像、视频、摄像头画面** - [B station](https://www.bilibili.com/video/BV1Lo4y1t76s)
- **YOLOV8关键点检测-预测源码解读** - [B station](https://www.bilibili.com/video/BV1Yu411t7XF)
- **YOLOV8关键点检测-ONNX Runtime部署** - [B station](https://www.bilibili.com/video/BV18L411B7Mv)
- **玩转MMPose人体姿态估计关键点检测** - [B station](https://www.bilibili.com/video/BV16B4y1h7JS)
- **开源姿态估计算法库MMPose** - [B station](https://www.bilibili.com/video/BV15B4y1p7Kj)
- **RTMPose关键点检测-安装MMDetection和MMPose** - [B station](https://www.bilibili.com/video/BV1Pa4y1g7N7)
- **RTMPose关键点检测-MMDetection三角板目标检测** - [B station](https://www.bilibili.com/video/BV1Lm4y1879K)
- **RTMPose关键点检测-训练、评估、推理预测** - [B station](https://www.bilibili.com/video/BV12a4y1u7sd)
- **AI画《三体》名场面** - [B station](https://www.bilibili.com/video/BV1b14y1W7iq)
- **AI画我的三体之章北海传** - [B station](https://www.bilibili.com/video/BV1Ux4y1F7zA)
- **如果AI来画清华美院艺考题** - [B station](https://www.bilibili.com/video/BV1d24y1f7Gi)
- **三分钟部署AIGC神器DragGAN** - [B station](https://www.bilibili.com/video/BV1Xw411e7ev)
- **斥资500元，我用AI打造的三体科幻微电影《云天明的童话》** - [B station](https://www.bilibili.com/video/BV1Xu4y1b7ny)
- **石趣绘本园：基于Amazon Bedrock的AIGC交互式童话绘本** - [B station](https://www.bilibili.com/video/BV1n64y1N7Vz)
- **【拜年神器】一键部署阿里开源AI写真** - [B station](https://www.bilibili.com/video/BV1DZ421B7J9)
- **【精读AI论文】知识蒸馏** - [B station](https://www.bilibili.com/video/BV1gS4y1k7vj)
- **知识蒸馏开山之作论文精读：Distilling the knowledge in a neural network** - [B station](https://www.bilibili.com/video/BV1N44y1n7mU)
- **知识蒸馏Pytorch代码实战** - [B station](https://www.bilibili.com/video/BV1zP4y1F7g4)
- **python交互式地图数据可视化神器folium** - [B station](https://www.bilibili.com/video/BV1t3411A7Z8)
- **folium实战-拍照地点分布地图可视化** - [B station](https://www.bilibili.com/video/BV1m3411A786)
- **folium实战-全球地震与板块运动分布** - [B station](https://www.bilibili.com/video/BV1gZ4y18772)
- **folium实战-波士顿犯罪地点、新冠疫情小区、纽约全天公交车可视化** - [B station](https://www.bilibili.com/video/BV18T4y1B7PA)
- **folium实战-轨道交通数据可视化** - [B station](https://www.bilibili.com/video/BV113411N7TL)
- **玩转MMTracking视频感知与追踪算法库** - [B station](https://www.bilibili.com/video/BV1za411Y7Zm)
- **MMTracking单目标追踪+轨迹绘制代码实战** - [B station](https://www.bilibili.com/video/BV1s44y1g75J)
- **AI人流量计数+足迹追踪** - [B station](https://www.bilibili.com/video/BV1J3411M7KQ)
- **训练Deepsort多目标追踪算法** - [B station](https://www.bilibili.com/video/BV1e5411m7Qh)
- **【开箱遛遛】宇树机器狗Go2** - [B station](https://www.bilibili.com/video/BV1hG411Y74j)
- **斯坦福CS224W图机器学习、图神经网络、知识图谱【同济子豪兄】** - [B station](https://www.bilibili.com/video/BV1pR4y1S7GA)
- **图的基本表示【斯坦福CS224W图机器学习】** - [B station](https://www.bilibili.com/video/BV1n84y1e7SF)
- **传统图机器学习的特征工程-节点【斯坦福CS224W】** - [B station](https://www.bilibili.com/video/BV1HK411175s)
- **传统图机器学习的特征工程-连接【斯坦福CS224W】** - [B station](https://www.bilibili.com/video/BV1r3411m7sD)
- **传统图机器学习的特征工程-全图【斯坦福CS224W】** - [B station](https://www.bilibili.com/video/BV14W4y1V7gg)
- **图机器学习NetworkX代码实战-创建图和可视化** - [B station](https://www.bilibili.com/video/BV1kM41147zV)
- **图机器学习NetworkX代码实战-上海地铁站点图数据挖掘** - [B station](https://www.bilibili.com/video/BV1LY411R7HJ)
- **随机游走的艺术-图嵌入表示学习【斯坦福CS224W图机器学习】** - [B station](https://www.bilibili.com/video/BV1AP4y1r7Pz)
- **DeepWalk【图神经网络论文精读】** - [B station](https://www.bilibili.com/video/BV1o94y197vf)
- **DeepWalk论文逐句精读** - [B station](https://www.bilibili.com/video/BV1pW4y1z7pb)
- **DeepWalk代码实战-维基百科词条图嵌入可视化** - [B station](https://www.bilibili.com/video/BV1et4y187Gd)
- **Node2Vec【图神经网络论文精读】** - [B station](https://www.bilibili.com/video/BV1BS4y1E7tf)
- **Node2Vec论文逐句精读** - [B station](https://www.bilibili.com/video/BV1vU4y1i77T)
- **Node2Vec代码实战-《悲惨世界》小说人物图嵌入、Alias Sampling复现** - [B station](https://www.bilibili.com/video/BV1VS4y1E7Me)
- **改变世界的谷歌PageRank算法** - [B station](https://www.bilibili.com/video/BV1uP411K7yN)
- **PageRank代码实战-西游记人物重要度** - [B station](https://www.bilibili.com/video/BV1Wg411H7Ep)
- **半监督节点分类：标签传播和消息传递【斯坦福CS224W图机器学习】** - [B station](https://www.bilibili.com/video/BV1184y1G7pA)
- **深度学习基础【斯坦福CS224W图神经网络】** - [B station](https://www.bilibili.com/video/BV13g4y1n7b4)
- **图神经网络综述和学习路径【斯坦福CS224W图机器学习】** - [B station](https://www.bilibili.com/video/BV16v4y1b7x7)
- **图卷积神经网络GCN** - [B station](https://www.bilibili.com/video/BV1Hs4y157Ls)
- **图神经网络GNN的表达能力** - [B station](https://www.bilibili.com/video/BV1MT411Y7da)
- **玩转Neo4j知识图谱和图数据挖掘** - [B station](https://www.bilibili.com/video/BV1Mr4y1i7CX)
- **Neo4j医疗知识图谱智能问答机器人** - [B station](https://www.bilibili.com/video/BV1uY41167Ha)
- **【精读AI论文】旷视轻量化网络ShuffleNet V2-算法精讲** - [B station](https://www.bilibili.com/video/BV1d3411Y7Ms)
- **【精读AI论文】旷视轻量化网络ShuffleNet V2-论文精读** - [B station](https://www.bilibili.com/video/BV17u411U7Ag)
- **生成对抗网络GAN交互式可视化** - [B station](https://www.bilibili.com/video/BV1R44y1377T)
- **生成对抗网络GAN开山之作论文精读** - [B station](https://www.bilibili.com/video/BV1oi4y1m7np)
- **精读CycleGAN论文-拍案叫绝的非配对图像风格迁移** - [B station](https://www.bilibili.com/video/BV1Ya411a78P)
- **CycleGAN照片转梵高莫奈油画** - [B station](https://www.bilibili.com/video/BV1wv4y1T71F)
- **MMGeneration开源图像生成算法库【OpenMMLab】** - [B station](https://www.bilibili.com/video/BV1bY4y147kz)
- **【精读AI论文】pix2pix-简笔画猫转真猫** - [B station](https://www.bilibili.com/video/BV1wY4y1k7Tc)
- **人像自拍秒变爆款动漫画风【OpenMMLab】** - [B station](https://www.bilibili.com/video/BV1XL4y1g7in)
- **两天搞定语义分割毕业设计** - [B station](https://www.bilibili.com/video/BV1Wr4y1d7Tr)
- **语义分割与MMSegmentation** - [B station](https://www.bilibili.com/video/BV1qN411z7hz)
- **标注自己的语义分割数据集** - [B station](https://www.bilibili.com/video/BV1uu4y1Q7Rt)
- **安装配置MMSegmentation+预训练语义分割推理预测** - [B station](https://www.bilibili.com/video/BV1du4y1q7o5)
- **准备西瓜语义分割数据集** - [B station](https://www.bilibili.com/video/BV1C8411X7p9)
- **准备MMSeg语义分割config配置文件** - [B station](https://www.bilibili.com/video/BV1w44y1F73N)
- **MMSegmentation训练语义分割深度学习算法** - [B station](https://www.bilibili.com/video/BV1Ch4y1S7cX)
- **MMSeg语义分割推理预测** - [B station](https://www.bilibili.com/video/BV1vp4y1K7Tj)
- **语义分割部署-MMDeploy模型转换** - [B station](https://www.bilibili.com/video/BV1Ep4y1n7wo)
- **语义分割部署-ONNX Runtime实时推理** - [B station](https://www.bilibili.com/video/BV1aN411B7Dq)
- **AidLux语义分割部署-安卓鸿蒙高通ARM** - [B station](https://www.bilibili.com/video/BV1k8411y7c2)
- **可解释机器学习公开课** - [B station](https://www.bilibili.com/video/BV1Se4y1T7dG)
- **CAM可解释性分析-算法讲解** - [B station](https://www.bilibili.com/video/BV1Ke411g7gm)
- **CAM可解释性论文精读：Learning Deep Features for Discriminative Localization** - [B station](https://www.bilibili.com/video/BV1fe4y1C7mN)
- **GradCAM深度学习可解释性分析** - [B station](https://www.bilibili.com/video/BV1PD4y1B77q)
- **【精读AI论文】GradCAM可解释性分析** - [B station](https://www.bilibili.com/video/BV1id4y167FF)
- **LIME机器学习可解释性分析** - [B station](https://www.bilibili.com/video/BV12V4y1G7KF)
- **【精读AI论文】LIME机器学习可解释性分析** - [B station](https://www.bilibili.com/video/BV1wV4y1V7rD)
- **MATLAB玩转深度学习可解释性分析** - [B station](https://www.bilibili.com/video/BV1Qd4y1b7Mr)
- **11款神经网络科研绘图可视化工具** - [B station](https://www.bilibili.com/video/BV1TV4y1P7AP)
- **视频理解和图像理解有什么区别？时序信息怎么建模？** - [B station](https://www.bilibili.com/video/BV1MddhBrEn8)
- **CLIP 的训练目标是什么？为什么要做图文匹配？** - [B station](https://www.bilibili.com/video/BV1spdhBPEEk)
- **CLIP 的视觉编码器用 ViT 还是 ResNet？各有什么优缺点？** - [B station](https://www.bilibili.com/video/BV1v7dzB6E8X)
- **多模态模型的对齐（Alignment）是什么意思？怎么让图文语义对应？** - [B station](https://www.bilibili.com/video/BV19zdBBiE3c)
- **图文相似度怎么计算？余弦相似度够用吗？** - [B station](https://www.bilibili.com/video/BV1HtoNBZEfS)
- **U-Net 在扩散模型里是怎么用的？时间步嵌入（Time Embedding）是什么？** - [B station](https://www.bilibili.com/video/BV1g7d2BXEDD)
- **CogVLM 的视觉专家模块是怎么设计的？** - [B station](https://www.bilibili.com/video/BV1g7d2BXEv5)
- **文本生成 3D（Text-to-3D）怎么做？DreamFusion 的原理是什么？** - [B station](https://www.bilibili.com/video/BV13jd2BWETV)
- **视频分类 (Video Classification) 怎么做？怎么从视频里提取全局特征？** - [B station](https://www.bilibili.com/video/BV1e3d2BoEqg)
- **三维目标检测（3D Object Detection）怎么做？和 2D 检测有什么区别？** - [B station](https://www.bilibili.com/video/BV1XdonB9E4f)
- **GPT-4V（GPT-4 Vision）的多模态能力有多强？能做什么？** - [B station](https://www.bilibili.com/video/BV1fgoVBGEBi)
- **多视图几何（Multi-View Geometry）是什么？SfM 和 SLAM 有什么区别？** - [B station](https://www.bilibili.com/video/BV134oVBaEN2)
- **IP-Adapter 是什么？怎么用图像作为 Prompt？** - [B station](https://www.bilibili.com/video/BV1bqoSB8Ec9)
- **视频多模态大模型怎么做？长视频理解的难点是什么？** - [B station](https://www.bilibili.com/video/BV121o6BAEYN)
- **跨模态检索（Cross-modal Retrieval）怎么做？图搜文、文搜图的原理是什么？** - [B station](https://www.bilibili.com/video/BV1G3R4BAEnv)
- **视频超分辨率（Video Super-Resolution）是什么？怎么提升视频清晰度？** - [B station](https://www.bilibili.com/video/BV1SRdgBQE2m)
- **ViT 和 CNN 有什么区别？为什么多模态模型更喜欢用 ViT？** - [B station](https://www.bilibili.com/video/BV1DX5v69EmL)
- **多模态大模型的幻觉问题更严重吗？视觉幻觉怎么缓解？** - [B station](https://www.bilibili.com/video/BV1BcLF6iEHb)
- **ViT（Vision Transformer）是怎么处理图像的？Patch Embedding 是什么？** - [B station](https://www.bilibili.com/video/BV1QfL16WE5q)
- **【AI编译篇】AI  Infra 简历点评** - [B station](https://www.bilibili.com/video/BV1WE3c6uEYH)
- **【AI应用篇】AI Infra简历点评** - [B station](https://www.bilibili.com/video/BV1oJ3B6AEBn)
- **【AI推理篇】AI Infra简历点评** - [B station](https://www.bilibili.com/video/BV1poMy6HEws)
- **TileLang 分享：TileLang 简介** - [B station](https://www.bilibili.com/video/BV1jHyjBEEFd)
- **TileLang 分享：TileLang 特性介绍** - [B station](https://www.bilibili.com/video/BV1jJyjBSEzQ)
- **TileLang 分享：TileLang API 及算子实例** - [B station](https://www.bilibili.com/video/BV1LpyjBmEGz)
- **TileLang 分享：TileLang 调优和 Debug** - [B station](https://www.bilibili.com/video/BV15pyjBmED5)
- **自编教材实操课程分享：第五章—编译器前端** - [B station](https://www.bilibili.com/video/BV1NC411Y7A8)
- **自编教材实操课程分享：第五章—编译器中端** - [B station](https://www.bilibili.com/video/BV1Xr421H7t3)
- **自编教材实操课程分享：第五章—编译器后端** - [B station](https://www.bilibili.com/video/BV1gi421d7Hc)
- **自编教材实操课程分享：第五章—编译选项** - [B station](https://www.bilibili.com/video/BV1Nr421n7Pd)
- **自编教材实操课程分享：第五章—过程间优化** - [B station](https://www.bilibili.com/video/BV15m411d7gH)
- **自编教材实操课程分享：第五章—循环展开** - [B station](https://www.bilibili.com/video/BV13f421f7ip)
- **自编教材实操课程分享：第五章—循环分布** - [B station](https://www.bilibili.com/video/BV1pj421d793)
- **自编教材实操课程分享：第五章—循环剥离** - [B station](https://www.bilibili.com/video/BV1AD421W7A1)
- **自编教材实操课程分享：第五章—循环级向量化** - [B station](https://www.bilibili.com/video/BV19M4m1X7PU)
- **自编教材实操课程分享：第五章—基本块级向量化** - [B station](https://www.bilibili.com/video/BV1wp421y7k2)
- **自编教材实操课程分享：第五章—数据预取优化** - [B station](https://www.bilibili.com/video/BV1Dz421k72n)
- **自编教材实操课程分享：第五章—浮点优化** - [B station](https://www.bilibili.com/video/BV1BZ421e7t6)
- **自编教材实操课程分享：第五章—反馈优化** - [B station](https://www.bilibili.com/video/BV1xx421S74X)
- **自编教材实操课程分享：第五章—链接时优化** - [B station](https://www.bilibili.com/video/BV1ZD421p7Gy)
- **自编教材实操课程分享：第五章—编译指示** - [B station](https://www.bilibili.com/video/BV1jZ421v791)
- **自编教材实操课程分享：第五章—数学库优化** - [B station](https://www.bilibili.com/video/BV12D421p79o)
- **自编教材实操课程分享：第五章—运行时优化** - [B station](https://www.bilibili.com/video/BV1ax4y167hV)
- **自编教材实操课程分享：第六章—算法优化** - [B station](https://www.bilibili.com/video/BV1C142197zL)
- **自编教材实操课程分享：第六章—典型数据结构的性能分析** - [B station](https://www.bilibili.com/video/BV1ew4m127sJ)
- **自编教材实操课程分享：第六章—选择合适的数据类型** - [B station](https://www.bilibili.com/video/BV11t421c7N1)
- **自编教材实操课程分享：第六章—选择合适的数据结构（二）** - [B station](https://www.bilibili.com/video/BV1vi421C7mB)
- **自编教材实操课程分享：第六章—别名消除** - [B station](https://www.bilibili.com/video/BV1tx4y1B75k)
- **自编教材实操课程分享：第六章—常数传播** - [B station](https://www.bilibili.com/video/BV1Cw4m1C7t3)
- **自编教材实操课程分享：第六章—传参优化** - [B station](https://www.bilibili.com/video/BV1NM4m1o7oH)
- **自编教材实操课程分享：第六章—内联替换** - [B station](https://www.bilibili.com/video/BV1CC411j7Zz)
- **自编教材实操课程分享：第六章—过程克隆** - [B station](https://www.bilibili.com/video/BV17y411Y7Wo)
- **自编教材实操课程分享：第六章—全局变量优化** - [B station](https://www.bilibili.com/video/BV1vf421m7RY)
- **自编教材实操课程分享：第六章—循环不变量外提** - [B station](https://www.bilibili.com/video/BV1nw4m1D7np)
- **自编教材实操课程分享：第六章—循环合并** - [B station](https://www.bilibili.com/video/BV1k7421f77W)
- **自编教材实操课程分享：第六章—循环分段** - [B station](https://www.bilibili.com/video/BV18z421Y7eR)
- **自编教材实操课程分享：第六章—循环展开和压紧** - [B station](https://www.bilibili.com/video/BV1mx4y1H7ch)
- **自编教材实操课程分享：第六章-循环分块** - [B station](https://www.bilibili.com/video/BV1sJ4m137o2)
- **自编教材实操课程分享：第六章—循环交换** - [B station](https://www.bilibili.com/video/BV1zx4y1n7fe)
- **自编教材实操课程分享：第六章—循环分裂** - [B station](https://www.bilibili.com/video/BV1Et421N7E5)
- **自编教材实操课程分享：第六章—循环倾斜** - [B station](https://www.bilibili.com/video/BV1J4421X7Zm)
- **自编教材实操课程分享：第六章—循环分布** - [B station](https://www.bilibili.com/video/BV16S411K7Zv)
- **自编教材实操课程分享：第六章—删除冗余语句** - [B station](https://www.bilibili.com/video/BV1Bx4y1J7Uq)
- **自编教材实操课程分享：第六章—代数变换** - [B station](https://www.bilibili.com/video/BV1G7421d7FB)
- **自编教材实操课程分享：第六章—公共子表达式优化** - [B station](https://www.bilibili.com/video/BV1Nr421w7DW)
- **自编教材实操课程分享：第六章—合并判断条件** - [B station](https://www.bilibili.com/video/BV1n4421Q7H8)
- **自编教材实操课程分享：第六章—生成选择指令** - [B station](https://www.bilibili.com/video/BV1px4y1J7mR)
- **自编教材实操课程分享：第七章—指令流水** - [B station](https://www.bilibili.com/video/BV1dx4y147fD)
- **自编教材实操课程分享：第七章—超长指令字** - [B station](https://www.bilibili.com/video/BV1Nf421z7Yy)
- **自编教材实操课程分享：第七章—函数的向量化** - [B station](https://www.bilibili.com/video/BV1Uw4m1e7PE)
- **自编教材实操课程分享：第七章—基本块的向量化** - [B station](https://www.bilibili.com/video/BV1A4421X7ov)
- **自编教材实操课程分享：第七章—循环的向量化** - [B station](https://www.bilibili.com/video/BV1gZ421M7UP)
- **自编教材实操课程分享：第六章—分支语句优化之运用条件编译** - [B station](https://www.bilibili.com/video/BV18Z421T7Tx)
- **自编教材实操课程分享：第六章—分支语句优化之移除分支语句** - [B station](https://www.bilibili.com/video/BV1Bb421E7yE)
- **自编教材实操课程分享：第七章—分支向量化** - [B station](https://www.bilibili.com/video/BV1ES421R7BC)
- **自编教材实操课程分享：第七章—归约向量化** - [B station](https://www.bilibili.com/video/BV1Q4421U7UR)
- **自编教材实操课程分享：第七章—不对齐访存** - [B station](https://www.bilibili.com/video/BV1cZ421u7oX)
- **自编教材实操课程分享：第七章—不连续访存** - [B station](https://www.bilibili.com/video/BV1yS411c7nC)
- **自编教材实操课程分享：第七章—向量运算融合** - [B station](https://www.bilibili.com/video/BV1gy411i7cL)
- **自编教材实操课程分享：第七章—向量重用** - [B station](https://www.bilibili.com/video/BV1Pw4m1Y7nH)
- **自编教材实操课程分享：第七章—循环完全展开** - [B station](https://www.bilibili.com/video/BV12H4y1w7cK)
- **自编教材实操课程分享：第八章—寄存器分配** - [B station](https://www.bilibili.com/video/BV1kr421M7mc)
- **自编教材实操课程分享：第八章—寄存器重用** - [B station](https://www.bilibili.com/video/BV1p142187Vu)
- **自编教材实操课程分享：第八章—缓存分块** - [B station](https://www.bilibili.com/video/BV1o4421Z7Ld)
- **自编教材实操课程分享：第八章—减少伪共享** - [B station](https://www.bilibili.com/video/BV1cZ421K7fz)
- **自编教材实操课程分享：第八章—数据预取** - [B station](https://www.bilibili.com/video/BV1Jb421J7Fx)
- **自编教材实操课程分享：第八章—减少内存读写** - [B station](https://www.bilibili.com/video/BV1amW8edE7Q)
- **自编教材实操课程分享：第八章—数据对齐** - [B station](https://www.bilibili.com/video/BV1KCste1EQN)
- **自编教材实操课程分享：第八章—多线程操作** - [B station](https://www.bilibili.com/video/BV1TksteLErP)
- **自编教材实操课程分享：第八章—数组重组** - [B station](https://www.bilibili.com/video/BV1TksteLErM)
- **自编教材实操课程分享：第八章—数组转置** - [B station](https://www.bilibili.com/video/BV18BHaeXECN)
- **自编教材实操课程分享：第八章—结构属性域调整** - [B station](https://www.bilibili.com/video/BV1hqHaeWETX)
- **自编教材实操课程分享：第八章—结构体拆分** - [B station](https://www.bilibili.com/video/BV18qHaeWEkd)
- **自编教材实操课程分享：第八章—结构体数组转换** - [B station](https://www.bilibili.com/video/BV1wG4henEyc)
- **自编教材实操课程分享：第九章—OpenMP程序编写** - [B station](https://www.bilibili.com/video/BV19ntJeMEpD)
- **自编教材实操课程分享：第九章—OpenMP版矩阵乘** - [B station](https://www.bilibili.com/video/BV1hstJeeEpc)
- **自编教材实操课程分享：第九章—并行区扩张** - [B station](https://www.bilibili.com/video/BV1its8eYEQh)
- **自编教材实操课程分享：第九章—并行区合并** - [B station](https://www.bilibili.com/video/BV1qts8eYEiH)
- **自编教材实操课程分享：第九章—数据填充避免伪共享** - [B station](https://www.bilibili.com/video/BV1Z4s8eAEp9)
- **自编教材实操课程分享：第九章—循环向量化** - [B station](https://www.bilibili.com/video/BV1hjxWe6EDy)
- **自编教材实操课程分享：第九章—循环嵌套合并调度** - [B station](https://www.bilibili.com/video/BV13jxWe6EAP)
- **自编教材实操课程分享：第九章—线程调度配置策略** - [B station](https://www.bilibili.com/video/BV1bh2tYJEq3)
- **自编教材实操课程分享：第九章—串并行切换** - [B station](https://www.bilibili.com/video/BV1ub2tYDEXm)
- **自编教材实操课程分享：第九章—线程数设置优化** - [B station](https://www.bilibili.com/video/BV1qM2ZY2EwV)
- **自编教材实操课程分享：第九章—分析隐式同步** - [B station](https://www.bilibili.com/video/BV1K9yGYaEAs)
- **自编教材实操课程分享：第九章—消除隐式同步** - [B station](https://www.bilibili.com/video/BV1N9yGYhEea)
- **自编教材实操课程分享：第九章—流水并行示例** - [B station](https://www.bilibili.com/video/BV1sUS8YxEJ3)
- **自编教材实操课程分享：第九章—流水并行粒度** - [B station](https://www.bilibili.com/video/BV1qNShYyE4f)
- **自编教材实操课程分享：第十章—CUDA程序编写** - [B station](https://www.bilibili.com/video/BV1j8DSYPEpp)
- **自编教材实操课程分享：第十章—线程结构优化** - [B station](https://www.bilibili.com/video/BV1aoDUYoEoq)
- **自编教材实操课程分享：第十章—分支优化** - [B station](https://www.bilibili.com/video/BV1unmDYEELs)
- **自编教材实操课程分享：第十章—访存优化(1)** - [B station](https://www.bilibili.com/video/BV1unmDYEEMA)
- **自编教材实操课程分享：第十章—访存优化(2)** - [B station](https://www.bilibili.com/video/BV1AGBxYLEjh)
- **自编教材实操课程分享：第十章—数据预取** - [B station](https://www.bilibili.com/video/BV11PBxYSEot)
- **自编教材实操课程分享：第十章—循环展开** - [B station](https://www.bilibili.com/video/BV1mABxYHEim)
- **人工智能编译器MLIR-官方入门教程讲解** - [B station](https://www.bilibili.com/video/BV1Hd4y1U7mb)
- **深度学习编译发展概述** - [B station](https://www.bilibili.com/video/BV1zd4y1K7MQ)
- **深度学习编译系统概述** - [B station](https://www.bilibili.com/video/BV1kS4y1t7JH)
- **深度学习框架发展（一）** - [B station](https://www.bilibili.com/video/BV1iD4y117td)
- **深度学习框架发展（二）** - [B station](https://www.bilibili.com/video/BV1dt4y1F7Cn)
- **深度学习框架发展（三）** - [B station](https://www.bilibili.com/video/BV1Qe4y1z78o)
- **深度学习硬件平台** - [B station](https://www.bilibili.com/video/BV1JY411Q72M)
- **深度学习自动微分：什么是自动微分** - [B station](https://www.bilibili.com/video/BV1fs4y197km)
- **HIP代码自动生成工具C2HIPC** - [B station](https://www.bilibili.com/video/BV1Jg411Q7z6)
- **循环优化（一）：循环展开和压紧** - [B station](https://www.bilibili.com/video/BV1HB4y1x7zv)
- **循环优化（二）：循环合并** - [B station](https://www.bilibili.com/video/BV1CD4y1B7H2)
- **循环优化（三）：循环分布** - [B station](https://www.bilibili.com/video/BV1Z8411t7dC)
- **循环优化（四）：循环交换** - [B station](https://www.bilibili.com/video/BV13d4y1C7ca)
- **循环优化（五）：循环不变量外提** - [B station](https://www.bilibili.com/video/BV1Ud4y1b7Zc)
- **循环优化（六）：循环分段** - [B station](https://www.bilibili.com/video/BV1Zs4y1s7zn)
- **循环优化（七）：循环分块** - [B station](https://www.bilibili.com/video/BV1gv4y1Y7ed)
- **循环优化（八）：循环分裂** - [B station](https://www.bilibili.com/video/BV1mb411f7wK)
- **循环优化（九）：循环倾斜** - [B station](https://www.bilibili.com/video/BV1uV4y1f7cJ)
- **你知道吗，C语言最初被称为New B语言？** - [B station](https://www.bilibili.com/video/BV1Rp4y1c7k3)
- **推理出企鹅会飞的编程语言——Prolog** - [B station](https://www.bilibili.com/video/BV1BF411S7Sy)
- **雷军：我写的代码像诗一样。Ruby：用我可以像写散文一样快乐写代码！** - [B station](https://www.bilibili.com/video/BV1Cp4y1w7a6)
- **LISP从括号出发，曲线救国的编程之路** - [B station](https://www.bilibili.com/video/BV1x84y1U7eD)
- **go，一门丑到无法形容的语言** - [B station](https://www.bilibili.com/video/BV1nu41137NZ)
- **Forth:一门不同于其他任何语言的编程语言** - [B station](https://www.bilibili.com/video/BV1m84y1D7bm)
- **汇编语言：在我面前，所有高级编程语言都是小弟** - [B station](https://www.bilibili.com/video/BV1tu411376J)
- **COBOL：编程界的上古语言** - [B station](https://www.bilibili.com/video/BV158411C7zX)
- **ALGOL60:编程领域的带头大哥** - [B station](https://www.bilibili.com/video/BV1qh4y1h7UW)
- **图算融合论文分享：Apollo** - [B station](https://www.bilibili.com/video/BV1Do4y1L7Xd)
- **算子调度优化论文分享：Rammer** - [B station](https://www.bilibili.com/video/BV1LM411u7nE)
- **动态shape深度学习算子自动调优论文分享：DietCode** - [B station](https://www.bilibili.com/video/BV1RP4y167P4)
- **动态shape深度学习编译器论文分享：DISC** - [B station](https://www.bilibili.com/video/BV16R4y1U7J5)
- **Astitch：机器学习访存密集计算编译优化框架** - [B station](https://www.bilibili.com/video/BV1Ev4y1Q7L4)
- **深度学习编译接口FreeTensor** - [B station](https://www.bilibili.com/video/BV1uV4y1M7dQ)
- **基于MLIR的GPU代码生成论文分享** - [B station](https://www.bilibili.com/video/BV1ga411N736)
- **论文分享：计算图优化Welder** - [B station](https://www.bilibili.com/video/BV1Tu4y1y7hN)
- **论文分享：动态控制流编译优化Cocktailer** - [B station](https://www.bilibili.com/video/BV1Kh4y1P7Rg)
- **论文分享：动态神经网络编译优化BrainStorm** - [B station](https://www.bilibili.com/video/BV1FC4y1R7pu)
- **论文分享：计算密集型算子融合Chimera** - [B station](https://www.bilibili.com/video/BV1Y6421G7kL)
- **代码加速黑科技：GraalNN如何让程序性能飞跃** - [B station](https://www.bilibili.com/video/BV1m7JizLEC3)
- **CoServe：解锁 CoE 模型有限内存推理新路径** - [B station](https://www.bilibili.com/video/BV17kJLzBEF2)
- **PAPI：从静态到动态，异构PIM如何解锁LLM解码的“智能调度”新纪元** - [B station](https://www.bilibili.com/video/BV1d2Tjz6EtD)
- **CIM-MLC：从芯片到行级，解锁存算一体的编译新范式** - [B station](https://www.bilibili.com/video/BV1aKTvzDEdd)
- **论文分享QiMeng-Xpiler：神经符号融合的异构深度学习系统张量程序跨平台转编译方案** - [B station](https://www.bilibili.com/video/BV1PopNzFEuH)
- **论文分享UniNDP：面向Near DRAM处理架构的统一编译与仿真工具** - [B station](https://www.bilibili.com/video/BV1kfpNzoEjX)
- **编译器自动调优论文分享：破解编译优化组合爆炸，协同搜索助力快速寻优** - [B station](https://www.bilibili.com/video/BV1y9pNzcEiL)
- **论文分享ANT-ACE：实现神经网络推理自动化的全同态加密编译器框架** - [B station](https://www.bilibili.com/video/BV1A5nwz5EwS)
- **论文分享HALO：面向全同态加密的循环感知自举管理** - [B station](https://www.bilibili.com/video/BV1vhnwzaENX)
- **论文分享Gated Attention：用极小代价换来大模型性能飞升** - [B station](https://www.bilibili.com/video/BV1nGFVzQEAh)
- **论文分享TempSamp-R1：用混合采样强化视频大模型时序定位** - [B station](https://www.bilibili.com/video/BV1QVKb6mEFm)
- **论文分享 FlashInfer：面向大模型推理服务的高效 Attention 引擎** - [B station](https://www.bilibili.com/video/BV1QKgQ6xEgh)
- **论文分享 CAKE：面向长上下文大模型的自适应 KV Cache 淘汰框架** - [B station](https://www.bilibili.com/video/BV16w3a6HEfe)
- **01 课程介绍** - [B station](https://www.bilibili.com/video/BV16BGbzAEq2)
- **01 神经网络基础** - [B station](https://www.bilibili.com/video/BV1cBGbzPE3T)
- **02 深度学习的进化** - [B station](https://www.bilibili.com/video/BV1cBGbzPEKk)
- **03 大语言模型** - [B station](https://www.bilibili.com/video/BV1cBGbzPEb2)
- **01 faster-RCNN算法原理** - [B station](https://www.bilibili.com/video/BV1rBGbzAEFS)
- **02 fasterRCNN实战** - [B station](https://www.bilibili.com/video/BV16BGbzAEtd)
- **03 YOLOv11实战** - [B station](https://www.bilibili.com/video/BV1cBGbzPEb1)
- **01 文本情感分类实战_1** - [B station](https://www.bilibili.com/video/BV1rBGbzAE5P)
- **02 文本情感分类实战_2** - [B station](https://www.bilibili.com/video/BV1FBGbzPEoQ)
- **01 大模型预训练基础_1** - [B station](https://www.bilibili.com/video/BV16BGbzAEbA)
- **02 大模型预训练基础_2** - [B station](https://www.bilibili.com/video/BV1aRGbzHEmA)
- **01 数据准备_1** - [B station](https://www.bilibili.com/video/BV1XRGbzHECt)
- **02 数据准备_2** - [B station](https://www.bilibili.com/video/BV1YRGbzHEgK)
- **03 模型结构_1** - [B station](https://www.bilibili.com/video/BV1GRGbzpEyR)
- **04 模型结构_2** - [B station](https://www.bilibili.com/video/BV1YRGbzHE5h)
- **01 预训练任务实现** - [B station](https://www.bilibili.com/video/BV1XRGbzHEXj)
- **02 训练优化_1** - [B station](https://www.bilibili.com/video/BV1YRGbzHEWn)
- **03 训练优化_2** - [B station](https://www.bilibili.com/video/BV1aRGbzHEBG)
- **01 性能评估** - [B station](https://www.bilibili.com/video/BV1YRGbzHEcL)
- **01 课程介绍** - [B station](https://www.bilibili.com/video/BV1gMjBzJE1B)
- **01 大模型微调概述** - [B station](https://www.bilibili.com/video/BV1gMjBzJEDw)
- **01 模型数据收集与处理** - [B station](https://www.bilibili.com/video/BV1gMjBzJEP9)
- **01 数据预处理理论** - [B station](https://www.bilibili.com/video/BV1gMjBzJEap)
- **02 启发式规则** - [B station](https://www.bilibili.com/video/BV1gMjBzJEEM)
- **03 评估模型过滤(1)** - [B station](https://www.bilibili.com/video/BV1DMjBzJEm9)
- **04 评估模型过滤(2)** - [B station](https://www.bilibili.com/video/BV1gMjBzJEPy)
- **05 完全匹配去重** - [B station](https://www.bilibili.com/video/BV1hMjBzJENe)
- **06 近似匹配去重(1)** - [B station](https://www.bilibili.com/video/BV18MjBzJEY6)
- **07 近似匹配去重(2)** - [B station](https://www.bilibili.com/video/BV1gMjBzJESX)
- **01 大模型微调工具与主流框架介绍** - [B station](https://www.bilibili.com/video/BV1c4jBzTEto)
- **02 微调框架实战(1)** - [B station](https://www.bilibili.com/video/BV1c4jBzTEpJ)
- **03 微调框架实战(2)** - [B station](https://www.bilibili.com/video/BV1wsjBzBE9p)
- **01 微调方法(1)** - [B station](https://www.bilibili.com/video/BV1wsjBzBEGW)
- **02 微调方法(2)** - [B station](https://www.bilibili.com/video/BV1wsjBzBEKA)
- **01 人类对齐** - [B station](https://www.bilibili.com/video/BV1x7jBzVEbX)
- **01 大模型评估与问题解决(1)** - [B station](https://www.bilibili.com/video/BV1K7jBzVEFv)
- **02 大模型评估与问题解决(2)** - [B station](https://www.bilibili.com/video/BV1mLjBzyEAc)
- **01 法律大模型强化学习实战** - [B station](https://www.bilibili.com/video/BV1WnjBz3Eip)
- **02 法律大模型评估实战(1)** - [B station](https://www.bilibili.com/video/BV1NnjBz3ETP)
- **03 法律大模型评估实战(2)** - [B station](https://www.bilibili.com/video/BV1PnjBz3ELn)
- **课程介绍** - [B station](https://www.bilibili.com/video/BV1SkLtzHEkT)
- **01 大模型推理挑战** - [B station](https://www.bilibili.com/video/BV1SkLtzHEdH)
- **02 主流推理引擎对比** - [B station](https://www.bilibili.com/video/BV1gkLtzpEBa)
- **03 大模型推理瓶颈分析** - [B station](https://www.bilibili.com/video/BV1DkLtzHEpD)
- **01 vLLM环境搭建** - [B station](https://www.bilibili.com/video/BV1SkLtzHEDo)
- **02 vLLM使用入门** - [B station](https://www.bilibili.com/video/BV1SkLtzHE2h)
- **03 vLLM推理分析** - [B station](https://www.bilibili.com/video/BV1DkLtzHEF1)
- **01 LoRA模型部署及实操** - [B station](https://www.bilibili.com/video/BV1gkLtzpEL4)
- **02 多模态模型部署及实操** - [B station](https://www.bilibili.com/video/BV1gkLtzpEkd)
- **01 vLLM量化模型支持** - [B station](https://www.bilibili.com/video/BV18kLtzpEZq)
- **02 模型量化** - [B station](https://www.bilibili.com/video/BV1U1LtzJEWP)
- **03 KV Cache量化** - [B station](https://www.bilibili.com/video/BV1U1LtzJEaX)
- **01 性能测试指标(1)** - [B station](https://www.bilibili.com/video/BV1U1LtzJEEB)
- **02 性能测试指标(2)** - [B station](https://www.bilibili.com/video/BV1U1LtzJE5V)
- **03 性能测试工具** - [B station](https://www.bilibili.com/video/BV1M1LtznEme)
- **04 性能分析** - [B station](https://www.bilibili.com/video/BV1S1LtznEM8)
- **01 算子优化** - [B station](https://www.bilibili.com/video/BV1t1LtzEE1f)
- **01 LLM引擎参数(1)** - [B station](https://www.bilibili.com/video/BV1GjL7z8EZo)
- **02 LLM引擎参数(2)** - [B station](https://www.bilibili.com/video/BV19jL7zbEV7)
- **03 推测解码与PD分离** - [B station](https://www.bilibili.com/video/BV1XjL7zbE4o)
- **01 DeepSeek可视化部署(1)** - [B station](https://www.bilibili.com/video/BV1wmjjzVEFC)
- **02 DeepSeek可视化部署(2)** - [B station](https://www.bilibili.com/video/BV1wmjjzVEFf)
- **01 RAG本地部署(1)** - [B station](https://www.bilibili.com/video/BV1A1jjzyELv)
- **02 RAG本地部署(2)** - [B station](https://www.bilibili.com/video/BV1w1jjzyEsX)
- **01 vLLM+Dify构建Agent应用(1)** - [B station](https://www.bilibili.com/video/BV1p1jjzyEhT)
- **02 vLLM+Dify构建Agent应用(2)** - [B station](https://www.bilibili.com/video/BV1C1jjzyEFA)
- **03 vLLM+Dify构建Agent应用(3)** - [B station](https://www.bilibili.com/video/BV1H1jjzyE9U)
- **【AI实操 · 优化篇】01 Triton在PyTorch中的角色** - [B station](https://www.bilibili.com/video/BV1ZoRPYQE2K)
- **【AI实操 · 优化篇】02 内核性能分析工具** - [B station](https://www.bilibili.com/video/BV1ZUQ1YtEwP)
- **【AI实操 · 优化篇】03 Triton编译器及Pass管理器** - [B station](https://www.bilibili.com/video/BV1VYQdYJEBb)
- **【AI实操 · 优化篇】04 Triton算子关键参数优化** - [B station](https://www.bilibili.com/video/BV1miotY3E2D)
- **【AI实操 · 优化篇】05 Triton算子开发** - [B station](https://www.bilibili.com/video/BV193fFYkE7P)
- **【AI实操 · 优化篇】06 Triton访存合并解析** - [B station](https://www.bilibili.com/video/BV1j6dRY8Erc)
- **【AI实操 · 优化篇】07 Triton布局介绍** - [B station](https://www.bilibili.com/video/BV1F45HzLEHo)
- **【AI实操 · 优化篇】08 Triton访存合并优化** - [B station](https://www.bilibili.com/video/BV1gzL2zTEq7)
- **【AI实操 · 优化篇】09 编译优化实践(一)：代数变换** - [B station](https://www.bilibili.com/video/BV1UQEjz4EzX)
- **【AI实操 · 优化篇】10 编译优化实践(二)：冗余去除** - [B station](https://www.bilibili.com/video/BV14TEczGE4i)
- **【AI实操 · 优化篇】11 Triton归约操作解析** - [B station](https://www.bilibili.com/video/BV16fj8zGEjD)
- **【AI实操 · 优化篇】12 Triton MMA操作解析：Tensor Core & MMA指令** - [B station](https://www.bilibili.com/video/BV1LnTszhEdY)
- **【AI实操 · 优化篇】13 Triton MMA操作解析：Pipeline & Prefetch** - [B station](https://www.bilibili.com/video/BV1vyN1zmEVG)
- **深度学习模型压缩概述** - [B station](https://www.bilibili.com/video/BV1ht4y1P73i)
- **无数据模型量化论文分享：ZeroQ** - [B station](https://www.bilibili.com/video/BV1614y1T7FS)
- **深度学习模型压缩方法（一）：模型蒸馏** - [B station](https://www.bilibili.com/video/BV1eb411971p)
- **深度学习模型压缩方法（二）：剪枝** - [B station](https://www.bilibili.com/video/BV1pg4y1J73p)
- **深度学习模型压缩方法（三）：量化** - [B station](https://www.bilibili.com/video/BV1bL411U747)
- **LLVM编译器入门（一）：LLVM整体设计** - [B station](https://www.bilibili.com/video/BV18j411B7TF)
- **LLVM编译器入门（二）：Clang前端** - [B station](https://www.bilibili.com/video/BV11j411B7XZ)
- **LLVM编译器入门（三）：IR优化** - [B station](https://www.bilibili.com/video/BV1fX4y1x79Y)
- **LLVM编译器入门（四）：代码生成 上** - [B station](https://www.bilibili.com/video/BV1tN411B71r)
- **LLVM编译器入门（五）：代码生成 下** - [B station](https://www.bilibili.com/video/BV1YG411o7AQ)
- **基础篇：大语言模型推理发展** - [B station](https://www.bilibili.com/video/BV1v718BpEsV)
- **核心篇：vLLM整体架构与请求预处理模块** - [B station](https://www.bilibili.com/video/BV1YcywBiEJ1)
- **核心篇：vLLM 调度器模块** - [B station](https://www.bilibili.com/video/BV18tB8BFE1L)
- **核心篇：vLLM 键值缓存管理器** - [B station](https://www.bilibili.com/video/BV1NhFjzTEKe)
- **【AI论文救星】01 规划论文选题与结构** - [B station](https://www.bilibili.com/video/BV1NddtYvEb4)
- **【AI论文救星】02 高效搜集整理文献** - [B station](https://www.bilibili.com/video/BV1FNdbYbE4b)
- **【AI论文救星】03 可视化数据图表制作** - [B station](https://www.bilibili.com/video/BV1n3dgYrEcf)
- **【AI论文救星】04 辅助写作与论文润色** - [B station](https://www.bilibili.com/video/BV1fKdbYoEm4)
- **【AI论文救星】05 自动排版与文献格式规范** - [B station](https://www.bilibili.com/video/BV1PZdtYPEER)
- **【AI论文救星】06 答辩PPT与讲稿生成** - [B station](https://www.bilibili.com/video/BV1kcdbYcEb6)
- **【AI论文救星】07 毕业答辩问答模拟** - [B station](https://www.bilibili.com/video/BV1g6dAYzEiq)
- **拥抱AI Agent~全网最详细的OpenManus本地部署教程** - [B station](https://www.bilibili.com/video/BV1w4XVY7Eou)
- **突破常规！Julius 借 “交互式分析”，革新 AI 数据** - [B station](https://www.bilibili.com/video/BV1c7DfYPEgi)
- **小白1分钟搞定！全网最详细的Deepseek的神仙级用法** - [B station](https://www.bilibili.com/video/BV1jb9iYMEBu)
- **什么？？？马上开组会了~ PPT 还没做！** - [B station](https://www.bilibili.com/video/BV19aDfYXETT)
- **Deepseek+word打造会思考的智能文档** - [B station](https://www.bilibili.com/video/BV1ALQvY3E9a)
- **AI+Excel：如何让工作效率原地飞起** - [B station](https://www.bilibili.com/video/BV1JCQeYAEw8)
- **TVM简介** - [B station](https://www.bilibili.com/video/BV14N4y1c7zq)
- **TVM自动调度算法AutoTVM** - [B station](https://www.bilibili.com/video/BV1114y1e7FK)
- **ANSOR：为深度学习生成高性能张量程序** - [B station](https://www.bilibili.com/video/BV1m14y1Y7LN)
- **TVM 编译流程与中间表示分析（一）** - [B station](https://www.bilibili.com/video/BV1v3411U7fM)
- **TVM 编译流程与中间表示分析（二）** - [B station](https://www.bilibili.com/video/BV1624y1v7wx)
- **ANSOR 优化算子代码解读（一）** - [B station](https://www.bilibili.com/video/BV1ih4y127fX)
- **ANSOR优化算子代码解读（二）** - [B station](https://www.bilibili.com/video/BV1C44y1c7WL)
- **ANSOR优化算子代码解读（三）** - [B station](https://www.bilibili.com/video/BV1e94y167Qy)
- **ANSOR优化算子代码解读（四）** - [B station](https://www.bilibili.com/video/BV1C8411X7BS)
- **TVM的量化框架（一）** - [B station](https://www.bilibili.com/video/BV1ph4y1U7Dy)
- **TVM的量化框架（二）** - [B station](https://www.bilibili.com/video/BV1aN4y1R7MY)
- **TVM的量化框架（三）** - [B station](https://www.bilibili.com/video/BV1ur4y197zj)
- **TVM的量化框架（四）** - [B station](https://www.bilibili.com/video/BV18w411S7Mh)
- **自动并行论文分享：FlexFlow** - [B station](https://www.bilibili.com/video/BV1wg411H78v)
- **自动并行论文分享：CoCoNet** - [B station](https://www.bilibili.com/video/BV1Nv4y1j78t)
- **论文分享：新型注意力算法FlashAttention** - [B station](https://www.bilibili.com/video/BV1zs4y1J7tb)
- **自动并行—并行划分** - [B station](https://www.bilibili.com/video/BV1wo4y1L7WJ)
- **数据并行通信优化论文分享：MG-WFBP** - [B station](https://www.bilibili.com/video/BV1hj411Z7SS)
- **自动并行论文分享：Merak** - [B station](https://www.bilibili.com/video/BV1T94y1C7i4)
- **论文分享：并行程序自动转换** - [B station](https://www.bilibili.com/video/BV1sa4y1C7p7)
- **论文分享：自动并行AvgPipe** - [B station](https://www.bilibili.com/video/BV1rw41137QG)
- **论文分享：自动并行AlpaServe** - [B station](https://www.bilibili.com/video/BV1wc411m7ki)
- **论文分享：自动并行Alpa** - [B station](https://www.bilibili.com/video/BV11j41177TQ)
- **论文分享：高性能计算领域大语言模型HPC-Coder** - [B station](https://www.bilibili.com/video/BV1e4421c7Gk)
- **自编教材分享：第一章—程序性能优化的意义（一）** - [B station](https://www.bilibili.com/video/BV1LL411B7uW)
- **自编教材分享：第一章—程序性能优化的意义（二）** - [B station](https://www.bilibili.com/video/BV15g4y1F7QQ)
- **自编教材分享：第二章—程序性能的度量指标及优化流程（一）** - [B station](https://www.bilibili.com/video/BV1vu411s7Xw)
- **自编教材分享：第三章—程序性能的分析和测量（一）** - [B station](https://www.bilibili.com/video/BV1ZV4y1U7wr)
- **自编教材分享：第三章—程序性能的分析和测量（二）** - [B station](https://www.bilibili.com/video/BV11k4y1p7Bw)
- **自编教材分享：第三章—程序性能的分析和测量（三）** - [B station](https://www.bilibili.com/video/BV1Wm4y1v7yZ)
- **自编教材分享：第四章—系统配置优化（一）** - [B station](https://www.bilibili.com/video/BV1go4y1K72Y)
- **自编教材分享：第四章—系统配置优化（二）** - [B station](https://www.bilibili.com/video/BV12o4y1P7kW)
- **自编教材分享：第五章—编译与运行优化** - [B station](https://www.bilibili.com/video/BV1KN4y1L7XT)
- **自编教材分享：第六章—程序编写优化（一）** - [B station](https://www.bilibili.com/video/BV1gX4y1q7Ms)
- **自编教材分享：第六章—程序编写优化（二）** - [B station](https://www.bilibili.com/video/BV1Aj411S7kJ)
- **自编教材分享：第六章—程序编写优化（三）** - [B station](https://www.bilibili.com/video/BV1sg4y1N763)
- **自编教材分享：第六章—程序编写优化（四）** - [B station](https://www.bilibili.com/video/BV1rh411A79q)
- **自编教材分享：第六章—程序编写优化（五）** - [B station](https://www.bilibili.com/video/BV1mz4y1E7rb)
- **自编教材分享：第七章—指令级并行（一）** - [B station](https://www.bilibili.com/video/BV1iV4y1h7wm)
- **自编教材分享：第七章—指令级并行（二）** - [B station](https://www.bilibili.com/video/BV1ym4y1E783)
- **自编教材分享：第七章—数据级并行（一）** - [B station](https://www.bilibili.com/video/BV1M94y1q7B4)
- **自编教材分享：第七章—数据级并行（二）** - [B station](https://www.bilibili.com/video/BV1Wj411R74A)
- **自编教材分享：第七章—数据级并行（三）** - [B station](https://www.bilibili.com/video/BV1Kk4y1G77z)
- **自编教材分享：第八章—访存优化（一）** - [B station](https://www.bilibili.com/video/BV1yz4y1s7qp)
- **自编教材分享：第八章—访存优化（二）** - [B station](https://www.bilibili.com/video/BV1fM4y1H7Ba)
- **自编教材分享：第八章—访存优化（三）** - [B station](https://www.bilibili.com/video/BV18m4y1W7fH)
- **自编教材分享：第八章—访存优化（四）** - [B station](https://www.bilibili.com/video/BV1Np4y1776Z)
- **自编教材分享：第八章—访存优化（五）** - [B station](https://www.bilibili.com/video/BV1gw411D7Bw)
- **自编教材分享：第八章—访存优化（六）** - [B station](https://www.bilibili.com/video/BV1cp4y1j7ga)
- **自编教材分享：第九章—OpenMP编程简介** - [B station](https://www.bilibili.com/video/BV1Zw411U7a8)
- **自编教材分享：第九章—并行区重构** - [B station](https://www.bilibili.com/video/BV1eu411A79T)
- **自编教材分享：第九章—向量化指导命令** - [B station](https://www.bilibili.com/video/BV12h4y1Y7vH)
- **自编教材分享：第九章—避免伪共享** - [B station](https://www.bilibili.com/video/BV1Gw411i7rS)
- **自编教材分享：第九章—负载均衡优化** - [B station](https://www.bilibili.com/video/BV1XN4y1o7NQ)
- **自编教材分享：第九章—避免隐式同步** - [B station](https://www.bilibili.com/video/BV19u4y1x7CS)
- **自编教材分享：第九章—流水并行优化** - [B station](https://www.bilibili.com/video/BV1LB4y1Z74v)
- **自编教材分享：第十章—CUDA程序优化（一）** - [B station](https://www.bilibili.com/video/BV1pB4y1f7Md)
- **自编教材分享：第十章—CUDA程序优化（二）** - [B station](https://www.bilibili.com/video/BV1C94y187iq)
- **自编教材分享：第十章—CUDA程序优化（三）** - [B station](https://www.bilibili.com/video/BV1Kw411z7Wd)
- **自编教材分享：第十章—CUDA程序优化（四）** - [B station](https://www.bilibili.com/video/BV1G84y1R7Ak)
- **自编教材分享：第十一章—MPI程序简介** - [B station](https://www.bilibili.com/video/BV1cj411a7Sb)
- **自编教材分享：第十一章—MPI程序简介（二）** - [B station](https://www.bilibili.com/video/BV1ra4y1m7JP)
- **自编教材分享：第十一章—数据划分优化** - [B station](https://www.bilibili.com/video/BV1Lc411b7Fw)
- **深度学习的产生与发展** - [B station](https://www.bilibili.com/video/BV1AM411P7JG)
- **深度神经网络的结构** - [B station](https://www.bilibili.com/video/BV1bD4y1G7oV)
- **神经网络的运行机制** - [B station](https://www.bilibili.com/video/BV1xs4y1b7nt)
- **CNN-卷积神经网络（一）** - [B station](https://www.bilibili.com/video/BV1iL411o7iz)
- **CNN-卷积神经网络（二）** - [B station](https://www.bilibili.com/video/BV1bL411o74W)
- **【直播回放】FlagOS开源社区“高性能计算实训营” 2025年08月16日09点场** - [B station](https://www.bilibili.com/video/BV18XYnzVEWa)
- **【直播回放】FlagOS开源社区“高性能计算实训营” 2025年08月16日14点场** - [B station](https://www.bilibili.com/video/BV1bXYnzVEQV)
- **【直播回放】FlagOS开源社区“高性能计算实训营” 2025年08月17日08点场** - [B station](https://www.bilibili.com/video/BV18XYnzVEJv)
- **【直播回放】FlagOS开源社区“高性能计算实训营” 2025年08月17日13点场** - [B station](https://www.bilibili.com/video/BV1wQYWzrEBz)
- **OpenAI triton分享：Triton概述** - [B station](https://www.bilibili.com/video/BV1Kr421M7rt)
- **OpenAI triton分享：Triton安装教程** - [B station](https://www.bilibili.com/video/BV1b9W8eQEW3)
- **OpenAI triton分享：triton程序编写** - [B station](https://www.bilibili.com/video/BV154421S7TE)
- **OpenAI triton分享：triton源码结构** - [B station](https://www.bilibili.com/video/BV1SHxWeTEMe)
- **OpenAI triton分享：triton编译流程** - [B station](https://www.bilibili.com/video/BV1Di2CYcEba)
- **OpenAI triton分享：triton调试方法及工具（上）** - [B station](https://www.bilibili.com/video/BV1aY2CYAEhy)
- **OpenAI triton分享：triton调试方法及工具（下）** - [B station](https://www.bilibili.com/video/BV1m6C1YsEn1)
- **OpenAI triton分享：triton IR 剖析（上）** - [B station](https://www.bilibili.com/video/BV1EwzyYZELz)
- **OpenAI triton分享：triton IR 剖析（下）** - [B station](https://www.bilibili.com/video/BV1AHCJYkESY)
- **计算机视觉与OpenMMLab 开源算法体系** - [B station](https://www.bilibili.com/video/BV1WG41177DP)
- **深度学习算法基础** - [B station](https://www.bilibili.com/video/BV1gP411N7yA)
- **上海交大学生创新中心人工智能实训平台介绍** - [B station](https://www.bilibili.com/video/BV1CV4y1V7SQ)
- **图像分类** - [B station](https://www.bilibili.com/video/BV11G4y1n7gC)
- **MMClassification 介绍与代码实践** - [B station](https://www.bilibili.com/video/BV1LP411N7G4)
- **MMClassification 实践 2** - [B station](https://www.bilibili.com/video/BV1be4y1e7uS)
- **目标检测** - [B station](https://www.bilibili.com/video/BV1BG4y1n7pn)
- **MMDetection 介绍与代码实践** - [B station](https://www.bilibili.com/video/BV1o8411Y7Td)
- **数据集采集与标注、LabelBee工具介绍** - [B station](https://www.bilibili.com/video/BV16W4y1E74Z)
- **模型部署与 MMDeploy 实践** - [B station](https://www.bilibili.com/video/BV1Ne411G7RX)
- **语义分割与 MMSegmentation 实践** - [B station](https://www.bilibili.com/video/BV1fP411A74D)
- **文字字符识别与 MMOCR 实践** - [B station](https://www.bilibili.com/video/BV1Qe4y1e7fH)
- **人体姿态估计与 MMPose 实践** - [B station](https://www.bilibili.com/video/BV1Hg411z7Qk)
- **视频目标追踪与 MMTracking 实践** - [B station](https://www.bilibili.com/video/BV14t4y1T7rd)
- **生成模型 GAN 与 MMGeneration 实践** - [B station](https://www.bilibili.com/video/BV1SK411D7uS)
- **强化学习RL是否可以提升模型性能上限？亦或只是将模型的Pass@N向Pass@1收敛？** - [B station](https://www.bilibili.com/video/BV1saNbzQEwT)
- **RLVR对推理能力的提升是否可以/如何才能泛化到通用能力？** - [B station](https://www.bilibili.com/video/BV1Q1Nez7E2t)
- **过去的PPO算法依赖于四个神经网络来进行稳定训练，近期以DAPO为代表的算法只需要一个policy model，是什么带来了模型训练稳定性的提升？** - [B station](https://www.bilibili.com/video/BV1THNBznEkF)
- **近期一些工作针对RL提出了一系列反直觉的结论，例如random reward也能提升性能，如何看待这些结论？** - [B station](https://www.bilibili.com/video/BV1SjNLzsEjq)
- **当前多模态领域的RL算法往往是纯语言领域RL算法的“应用”迁移，除了引入图像condition以外没有太多改进，如何针对多模态引入算法改进？** - [B station](https://www.bilibili.com/video/BV1TzN5zDE5V)
- **如何看待预训练数据/性能对RL效果的影响？** - [B station](https://www.bilibili.com/video/BV1oNN7z6Ecq)
- **零人工数据强化学习推理模型主题分享** - [B station](https://www.bilibili.com/video/BV1irNszFEtt)
- **小米 MiMo-VL 预训练及后训练技术分享** - [B station](https://www.bilibili.com/video/BV1xuKwz2Ejp)
- **强化学习范式 OREAL：超越蒸馏，推动轻中量级模型突破推理“三重门”困局** - [B station](https://www.bilibili.com/video/BV1BCKczeEJa)
- **CPRet：面向编程竞赛检索的基准数据集和模型** - [B station](https://www.bilibili.com/video/BV1kFGgzjEtu)
- **DyCodeEval: 数据污染下的代码模型的动态测评** - [B station](https://www.bilibili.com/video/BV1QrGuzbEPH)
- **OSS-Bench：告别静态数据集！从真实开源项目中“活捉”高难度编程任务** - [B station](https://www.bilibili.com/video/BV1GauuzREiY)
- **UTBoost：修复“漏风”的 SWE-Bench，揪出 345 个“假通过”补丁** - [B station](https://www.bilibili.com/video/BV1qtu3zKEq9)
- **上海人工智能实验室 大模型中心负责人 陈恺 深度解读 Intern-S1——科学多模态大模型** - [B station](https://www.bilibili.com/video/BV1K3agzBE9i)
- **MiniCPM-V：迈向高效端侧多模态大模型** - [B station](https://www.bilibili.com/video/BV1VZaCzLEJr)
- **GLM-V：迈向通用推理的多模态大模型** - [B station](https://www.bilibili.com/video/BV1C9ahzbEmG)
- **Ovis多模态大模型：结构对齐下的视觉语言融合** - [B station](https://www.bilibili.com/video/BV168HUzkEEZ)
- **阶跃星辰在多模态方向上的探索** - [B station](https://www.bilibili.com/video/BV1jAHXzmEao)
- **多模态模型哪些能力已逐渐饱和，还存在哪些不足和短板，未来有哪些值得关注的应用方向?** - [B station](https://www.bilibili.com/video/BV1Y3HazDE2m)
- **多模态模型的推理相比于语言模型，有哪些不一样的技术挑战和发展思路？** - [B station](https://www.bilibili.com/video/BV1s1pWzJEGJ)
- **理解生成一体化是近期多模态大模型的热门探索方向，技术方案有什么样的演进趋势，未来是否有可能实现理解和生成任务的互相促进?** - [B station](https://www.bilibili.com/video/BV1zCJkzQEmp)
- **多模态模型的突破是否被语言模型的研究进展所限制？模型架构和训练范式上有哪些创新路径？** - [B station](https://www.bilibili.com/video/BV1VFpCzQEG6)
- **LongCat-Flash-Omni：美团全模态大模型探索** - [B station](https://www.bilibili.com/video/BV16jyuBBEZ8)
- **OmniVinci：全模态大模型的架构和数据探索** - [B station](https://www.bilibili.com/video/BV1FFU5B8E9x)
- **Ming-Omni：百灵多模态的实践与探索** - [B station](https://www.bilibili.com/video/BV1oeUbBaEGt)
- **Omni 全模态模型在训练数据和策略上面临哪些挑战？如何构建和利用涵盖图像、视 频、音频、文本的海量数据集，并采用何种训练策略技巧来有效融合多模态信息的？** - [B station](https://www.bilibili.com/video/BV1ZPSaBCEXH)
- **在多模态统一模型中，模态不均衡或者模态偏置问题如何解决？** - [B station](https://www.bilibili.com/video/BV1to28BUEdg)
- **在长上下文建模方面，模型如何真正利用极长序列？例如视频长达上万帧，或多轮对话跨越很长距离，模型如何保留和利用这些信息？** - [B station](https://www.bilibili.com/video/BV1Q625B5Eyp)
- **如何看待通用模态 tokenization 未来面临的挑战？所有模态用统一“词表”表示是否现实？** - [B station](https://www.bilibili.com/video/BV1cG2kBMEQ9)
- **在一个模型中同时学习理解任务和生成任务会不会互相促进？可以从哪些技术路线去突破？** - [B station](https://www.bilibili.com/video/BV1dNmKBFExt)
- **Omni 全模态模型的发展趋势是什么，可能会朝哪些新方向拓展？还有哪些关键技术要突破？** - [B station](https://www.bilibili.com/video/BV12VmCBJEK7)
- **HunyuanOCR：混元原生多模态端到端 OCR 专家** - [B station](https://www.bilibili.com/video/BV1SBBVBEEMp)
- **PaddleOCR-VL：支持 109 种语言的轻量化多模态文档解析方案** - [B station](https://www.bilibili.com/video/BV16CBDBzEHJ)
- **MinerU：高效精准的文档解析技术攻坚** - [B station](https://www.bilibili.com/video/BV1epBaB3EPA)
- **极致端侧推理、结构还原与语义泛化三者之间存在天然的张力，在设计模型架构或训练策略时，如何权衡这三者之间的 trade-off 的？** - [B station](https://www.bilibili.com/video/BV1WZqFBPEjU)
- **OCR 模型是否还有必要加入推理能力吗？主要会用于什么样的场景，会用怎样的形式出现？** - [B station](https://www.bilibili.com/video/BV1ZhqwB8EEr)
- **OCR 系统在工程落地过程中，常见的性能瓶颈或优化难点有哪些？能否分享一些踩坑经验，尤其是在部署、推理效率或模型压缩方面的教训？** - [B station](https://www.bilibili.com/video/BV1MCquBvEfK)
- **如果从头搭建一个面向真实商业场景的文档解析系统（如合同、发票、报表等），有哪些关键建议可以给到开发者？** - [B station](https://www.bilibili.com/video/BV1RCiCBzERG)
- **从开源视角看，当前 OCR 工业级工具链或范式还有哪些关键缺失？如果不考虑商业化,最想推动或实现的 OCR 方向是什么？** - [B station](https://www.bilibili.com/video/BV1B8iDBaEgF)
- **能否分享最近关注、但本次尚未提及的 OCR 前沿工作？对于希望参与贡献开源项目的开发者，有哪些建议？** - [B station](https://www.bilibili.com/video/BV1NUrwBXEDj)
- **下一代多模态大模型能力演进的度量分析** - [B station](https://www.bilibili.com/video/BV1XUrhBLEsK)
- **基于多模态大模型的图像评价及应用探索** - [B station](https://www.bilibili.com/video/BV1pWr6BWEGv)
- **探索大模型的通用科学能力边界** - [B station](https://www.bilibili.com/video/BV1CLrLBXEoo)
- **NewtonBench：在“平行宇宙”中评估大模型科学发现能力** - [B station](https://www.bilibili.com/video/BV1oVrzB3E2y)
- **ScienceBoard: 从数字智能体到 AI 科学家** - [B station](https://www.bilibili.com/video/BV1FJhwzTEQH)
- **AutoMind: 知识增强智能体解锁数据科学潜力** - [B station](https://www.bilibili.com/video/BV1oNhczoEM9)
- **Scientists’ First Exam，科学认知能力的“开场哨声”** - [B station](https://www.bilibili.com/video/BV1pWh7zUEMb)
- **圆桌讨论——科学智能的边界与突破** - [B station](https://www.bilibili.com/video/BV1X1tgzzEBH)
- **大模型评测基准发展趋势探讨** - [B station](https://www.bilibili.com/video/BV1AbrHBME4n)
- **技术写作系列课程第一课：技术写作的内容风格与选题** - [B station](https://www.bilibili.com/video/BV1YX4y1B7mH)
- **技术写作系列课程第二课：如何起一个吸引人的标题** - [B station](https://www.bilibili.com/video/BV1qs4y1d7jm)
- **技术写作系列课程第三课：如何搭建文章结构** - [B station](https://www.bilibili.com/video/BV1oc411E7nD)
- **技术写作系列课程第四课：技术写作必备的利器工具** - [B station](https://www.bilibili.com/video/BV1Tg4y1777V)
- **Label Studio x Segment Anything Model 半自动化标注** - [B station](https://www.bilibili.com/video/BV1uv4y1J7yM)
- **Label-Studio X Segment Anything Model 半自动化标注（2）：Windows CPU 环境配置** - [B station](https://www.bilibili.com/video/BV1hh411F7uR)
- **Label-Studio X Segment Anything Model 半自动化标注（3）：开启前后端并标注** - [B station](https://www.bilibili.com/video/BV1Fo4y1V77n)
- **Label-Studio X Segment Anything Model 半自动化标注（4）：数据集可视化及模型训练和测试** - [B station](https://www.bilibili.com/video/BV1Lh4y1o7qN)
- **以最新数学博资考题为例，书生-S2可以围绕一道复杂问题进行数小时的持续探索** - [B station](https://www.bilibili.com/video/BV1L8eE6NEk3)
- **书生-S2 实现结合疾病靶标的蛋白药物的自主设计** - [B station](https://www.bilibili.com/video/BV1fHeE6zESc)
- **基于给定的化学式，书生-S2 实现物理可行的晶体构建** - [B station](https://www.bilibili.com/video/BV1JneE63EUa)
- **“书生-S2，帮我构建一个长征7火箭的3D CAD模型”** - [B station](https://www.bilibili.com/video/BV1RQe76cEAg)
- **Linux 前置基础知识** - [B station](https://www.bilibili.com/video/BV1FS421d7yg)
- **Python 前置基础知识** - [B station](https://www.bilibili.com/video/BV1mS421X7h4)
- **Git 前置基础知识** - [B station](https://www.bilibili.com/video/BV1Pz421i7bw)
- **书生·浦语大模型全链路开源开放体系** - [B station](https://www.bilibili.com/video/BV18142187g5)
- **8G 显存玩转书生大模型 Demo** - [B station](https://www.bilibili.com/video/BV18x4y147SU)
- **浦语提示词工程实践** - [B station](https://www.bilibili.com/video/BV1cU411S7iV)
- **InternLM+LlamaIndex RAG 实践** - [B station](https://www.bilibili.com/video/BV19E4m1X79q)
- **XTuner 微调大模型个人小助手认知** - [B station](https://www.bilibili.com/video/BV1tz421B72y)
- **OpenCompass 评测 InternLM-1.8B 实践** - [B station](https://www.bilibili.com/video/BV1RM4m1279j)
- **Lagent 自定义你的 Agent 智能体** - [B station](https://www.bilibili.com/video/BV18M4m1y7sm)
- **LMDeploy 量化部署进阶实践** - [B station](https://www.bilibili.com/video/BV1df421q7cR)
- **InternVL（冷笑话大师）部署微调实践** - [B station](https://www.bilibili.com/video/BV1N6p1eXETX)
- **茴香豆：企业级知识库问答工具** - [B station](https://www.bilibili.com/video/BV1C5W2epEYP)
- **销冠——卖货主播大模型** - [B station](https://www.bilibili.com/video/BV1f1421b7Du)
- **InternLM-1.8B 模型安卓端侧部署实践** - [B station](https://www.bilibili.com/video/BV1Ai421a7R6)
- **手把手带你使用 InternLM 实现谁是卧底游戏** - [B station](https://www.bilibili.com/video/BV1uhp1efEeE)
- **旋转~跳跃~检测王者 MMDetection 的好兄弟来啦！** - [B station](https://www.bilibili.com/video/BV1Hr4y1r73p)
- **墩墩生成器来啦！三步穿上墩墩服变身冰墩墩，做今年冬天最靓崽！** - [B station](https://www.bilibili.com/video/BV1Tq4y1t77C)
- **千行百业智能化落地，MMDeploy 助你一“部”到位！** - [B station](https://www.bilibili.com/video/BV1g34y1z7EW)
- **操作顺滑，一秒上手，LabelBee 让人工标注更智能!** - [B station](https://www.bilibili.com/video/BV1pr4y1X7VM)
- **画形亦画骨，知面也知心，与 MMHuman3D 一道探索人体参数化模型！** - [B station](https://www.bilibili.com/video/BV1Ch411s7mS)
- **MMFlow:帧与帧之间的追光者** - [B station](https://www.bilibili.com/video/BV1Zr4y1r72H)
- **【MMTracking】单目标跟踪！持续跟踪！** - [B station](https://www.bilibili.com/video/BV1Ev411376o)
- **【MMTracking】国庆快乐！多目标跟踪走丢也不怕！** - [B station](https://www.bilibili.com/video/BV1tU4y1c7mj)
- **【MMtracking】实时追踪！套马杆的汉子的马** - [B station](https://www.bilibili.com/video/BV1xL41147n5)
- **【MMDetection】七夕没对象？用我检测一下！** - [B station](https://www.bilibili.com/video/BV1QU4y177oZ)
- **【MMPose】火柴人出击！** - [B station](https://www.bilibili.com/video/BV1YU4y1H7Dq)
- **【MMPose】 demo webcam** - [B station](https://www.bilibili.com/video/BV1pw411R7iD)
- **【MMPose】3D Human Pose** - [B station](https://www.bilibili.com/video/BV1B3411672x)
- **【MMPose】Animal Pose** - [B station](https://www.bilibili.com/video/BV1t341167V7)
- **【MMPose】2D Human Pose** - [B station](https://www.bilibili.com/video/BV1Zf4y157PF)
- **AI 生成视频不闪了！社区大佬又整新活啦！** - [B station](https://www.bilibili.com/video/BV19o4y1b7RZ)
- **Segment Anything Model+ MMagic = Generate Anything！** - [B station](https://www.bilibili.com/video/BV1ws4y1R7aB)
- **DragGAN 应用来啦，无需部署，在线体验！** - [B station](https://www.bilibili.com/video/BV1Rh4y1y7LK)
- **还在排队 SearchGPT？快来试试开源的 AI 搜索引擎框架 MindSearch！** - [B station](https://www.bilibili.com/video/BV1Kx4y1s7SS)
- **人工智能时代的创业新范式** - [B station](https://www.bilibili.com/video/BV1gAmnBZEuK)
- **从初心到商业化：以快速迭代创造用户真价值** - [B station](https://www.bilibili.com/video/BV1hwmnBbE7d)
- **医疗领域大模型微调实践** - [B station](https://www.bilibili.com/video/BV1gfqJBNEmT)
- **MMSelfSup 代码库介绍** - [B station](https://www.bilibili.com/video/BV1hg411r7iK)
- **MMSelfSup 代码教程【1】模型自监督预训练 之 SimCLR** - [B station](https://www.bilibili.com/video/BV1Ht4y1n7jy)
- **MMSelfSup 代码教程【2】图片向量可视化 t-SNE** - [B station](https://www.bilibili.com/video/BV1yS4y1W7B6)
- **MMSelfSup 代码教程【3】自监督预训练模型的评估：“分类” 下游任务 之 线性评估** - [B station](https://www.bilibili.com/video/BV1LP41157uA)
- **MMSelfSup 代码教程【4】自监督预训练模型的评估：“分类” 下游任务 之 SVM 评估** - [B station](https://www.bilibili.com/video/BV1Ga411G73i)
- **MMSelfSup 代码教程【5】自监督预训练模型的评估：“检测”下游任务** - [B station](https://www.bilibili.com/video/BV1EP41157BL)
- **MMSelfSup 代码教程【6】在 MMDetection 中使用自监督预训练模型** - [B station](https://www.bilibili.com/video/BV1Fe4y1Z7Wh)
- **MMSelfSup 代码教程【7】模型自监督预训练 之 MAE** - [B station](https://www.bilibili.com/video/BV1EY4y1u7Px)
- **10 分钟带你上手 MMEval（一）：MMEval 介绍** - [B station](https://www.bilibili.com/video/BV1m24y127Db)
- **10 分钟带你上手 MMEval（二）：MMEval 使用介绍** - [B station](https://www.bilibili.com/video/BV1HP4y117pA)
- **10 分钟带你上手 MMEval（三）：如何给 MMEval 添加新的评测指标** - [B station](https://www.bilibili.com/video/BV1Ev4y1d7nK)
- **大语言模型复杂医疗推理评测基准MedAgentsBench** - [B station](https://www.bilibili.com/video/BV1J5oXYYEYH)
- **通用写作评测基准 WritingBench** - [B station](https://www.bilibili.com/video/BV1dFdpYqELh)
- **首个视频时空推理评估基准 V-STaR** - [B station](https://www.bilibili.com/video/BV1DbdHYZEbq)
- **ViLBench：多模态过程奖励（Process Reward）建模组件** - [B station](https://www.bilibili.com/video/BV1cZ5kzyECC)
- **CMU团队打造考公逻辑谜题 VisualPuzzles** - [B station](https://www.bilibili.com/video/BV16kL7zrEdq)
- **ToolHop：查询驱动的多跳工具使用评测集** - [B station](https://www.bilibili.com/video/BV1CjExzGE7s)
- **1. MMDetection3D 介绍及安装配置** - [B station](https://www.bilibili.com/video/BV1aG4y197is)
- **2. 使用 MMDet3D 预训练模型在点云和数据图像上推理** - [B station](https://www.bilibili.com/video/BV1E44y1Q7qi)
- **3. KITTI 数据集介绍及 MMDet3D 坐标系规范** - [B station](https://www.bilibili.com/video/BV1vv4y1d7br)
- **4. 使用 MMDetection3D 训练** - [B station](https://www.bilibili.com/video/BV11G4y157ux)
- **5. PointPillars 和 KittiDataset 的配置文件解读** - [B station](https://www.bilibili.com/video/BV14M41167Ct)
- **6. PointPillars 和 KittiDataset 的代码解读** - [B station](https://www.bilibili.com/video/BV1Xe4y1g7Xv)
- **大语言模型原理与书生大模型提示词工程实践** - [B station](https://www.bilibili.com/video/BV1vUjYz2Eys)
- **玩转书生大模型 API 之 Browse Use实践** - [B station](https://www.bilibili.com/video/BV1SPGnzWEN4)
- **InternLM 微调论文分类实践** - [B station](https://www.bilibili.com/video/BV1DyGuz4Ewp)
- **GraphGen 训练数据合成框架** - [B station](https://www.bilibili.com/video/BV1EA31zMEQk)
- **CAMEL 书生多智能体系统实践** - [B station](https://www.bilibili.com/video/BV15A3EzWEPv)
- **国产开源、免费的 AI 图像与视频创作平台MagicMaker，新手教程来啦！** - [B station](https://www.bilibili.com/video/BV1w2421A7YP)
- **“龙在城隍庙吃小笼包”MagicMaker亮相东方卫视春晚特别直播节目，科技魔法点亮传统舞台** - [B station](https://www.bilibili.com/video/BV1TS421A7UR)
- **“一个小男生和一个小女生在黄河路‘偷心’”MagicMaker亮相东方卫视春晚特别直播节目，科技魔法点亮传统舞台** - [B station](https://www.bilibili.com/video/BV18z421X7ci)
- **“龙在东方明珠上盘旋”MagicMaker亮相东方卫视春晚特别直播节目，科技魔法点亮传统舞台** - [B station](https://www.bilibili.com/video/BV1VC411s7Fv)
- **社区开放麦#1｜基于关键点的动作识别** - [B station](https://www.bilibili.com/video/BV1Yu411k7Be)
- **社区开放麦#2｜CVPR前沿姿态估计论文精讲** - [B station](https://www.bilibili.com/video/BV1dS4y187sj)
- **社区开放麦#3｜PyTorch 分布式训练解读** - [B station](https://www.bilibili.com/video/BV1Jv4y1K7fv)
- **社区开放麦#4｜手把手带你复现最新自监督算法** - [B station](https://www.bilibili.com/video/BV1xt4y1x7sp)
- **社区开放麦#5｜带你探寻可见光之外的世界** - [B station](https://www.bilibili.com/video/BV1Ka411n7nP)
- **社区开放麦#6｜带你了解车速估计技术在自动驾驶领域的应用** - [B station](https://www.bilibili.com/video/BV1sY4y1L7Au)
- **社区开放麦#7  MMPose 姿态估计创意 demo 大赛** - [B station](https://www.bilibili.com/video/BV1J34y1j7AP)
- **社区开放麦#8 | 迈向真实世界的感知：3D 目标检测** - [B station](https://www.bilibili.com/video/BV1hg41197HX)
- **社区开放麦#9 | OpenMMLab 模块化设计背后的功臣** - [B station](https://www.bilibili.com/video/BV19Z4y1q7Q5)
- **社区开放麦#10 | MMDeploy ncnn 部署实战** - [B station](https://www.bilibili.com/video/BV1gS4y1p7gm)
- **社区开放麦#11 | BEV感知：下一代自动驾驶感知算法新范式** - [B station](https://www.bilibili.com/video/BV12t4y1t7Lq)
- **社区开放麦#12 | 视觉有向目标的高精度检测** - [B station](https://www.bilibili.com/video/BV1Wr4y1E7Qr)
- **社区开放麦#13 | 手势识别算法综述与正确打开方式** - [B station](https://www.bilibili.com/video/BV1ar4y1j7aN)
- **社区开放麦#14 | 从时间序列角度破解姿态估计中的两大问题** - [B station](https://www.bilibili.com/video/BV1aB4y1k7Ph)
- **社区开放麦#15|  突破纯视觉 3D 检测深度估计瓶颈** - [B station](https://www.bilibili.com/video/BV1dg41117ba)
- **社区开放麦#16 | 稀疏卷积的高性能部署** - [B station](https://www.bilibili.com/video/BV1gV4y177F6)
- **社区开放麦#17 | 像素级别的多目标跟踪方案** - [B station](https://www.bilibili.com/video/BV1814y1b7Za)
- **社区开放麦#18 | 半监督学习在 3D 目标检测的最新进展** - [B station](https://www.bilibili.com/video/BV1mT411c7kB)
- **社区开放麦#19 | 对 AI 炼丹师友好的模型部署探索** - [B station](https://www.bilibili.com/video/BV12V4y1H7XQ)
- **社区开放麦#20 | 简单有效的目标跟踪方案** - [B station](https://www.bilibili.com/video/BV1wd4y1X7j5)
- **社区开放麦#21 | 当钩子编程遇到深度学习：Runner & Hook** - [B station](https://www.bilibili.com/video/BV1pe4y1C7n1)
- **社区开放麦#22 |  姿态估计领域的前沿进展** - [B station](https://www.bilibili.com/video/BV1HV4y1M7dG)
- **社区开放麦#23 | MMYOLO 圆桌会** - [B station](https://www.bilibili.com/video/BV1r24y1R7D1)
- **社区开放麦#24 | 释放数据潜力，打造 AI 加速引擎** - [B station](https://www.bilibili.com/video/BV1p8411s7W6)
- **AI奇妙夜第一期** - [B station](https://www.bilibili.com/video/BV1P8411e7Cb)
- **社区开放麦#27 | 部署神器Halide, 实现高性能算法** - [B station](https://www.bilibili.com/video/BV1Tg411B7ch)
- **AI 奇妙夜#2 | 子豪兄分享人工智能学习心法** - [B station](https://www.bilibili.com/video/BV1WG4y1f7yX)
- **社区开放麦#29 | ECCV Oral | 用于场景文本检测识别的弱监督视觉语言预训练方法** - [B station](https://www.bilibili.com/video/BV16G4y1x7es)
- **社区开放麦#30 | 入门剪枝利器 MMRazor，迈出模型压缩第一步** - [B station](https://www.bilibili.com/video/BV1wG411u7SP)
- **社区开放麦#31 | 异构检测器间知识蒸馏算法 PKD | NeurIPS22** - [B station](https://www.bilibili.com/video/BV1z24y1k7iu)
- **社区开放麦#32 | ONNX 新特性和最佳实践介绍** - [B station](https://www.bilibili.com/video/BV1LG411K7ah)
- **社区开放麦#33 | 详解 ACCV22 大规模细粒度图像分类夺冠方案** - [B station](https://www.bilibili.com/video/BV13M411S7b5)
- **社区开放麦#34 | 突破 AI 推理性能瓶颈，神经网络量化的方法与实践** - [B station](https://www.bilibili.com/video/BV128411n7yN)
- **AI 奇妙夜#3 | 大规模多模态预训练最新研究进展** - [B station](https://www.bilibili.com/video/BV1J14y1A7SE)
- **社区开放麦#36 多模态场景下的高性能 Embedding 计算服务** - [B station](https://www.bilibili.com/video/BV1ET411m7gu)
- **社区开放麦#37 | 牛津大学vgg组博士：提高遮挡检测下的目标检测效果** - [B station](https://www.bilibili.com/video/BV1NA41167kN)
- **社区开放麦#38 目标检测新范式！DETR 系列算法解读** - [B station](https://www.bilibili.com/video/BV17x4y1w7ZK)
- **弱监督有向目标检测 | 杨学** - [B station](https://www.bilibili.com/video/BV1GD4y1g7s8)
- **社区开放麦#41 | 视觉大模型设计新范式** - [B station](https://www.bilibili.com/video/BV1zs4y15754)
- **AI 奇妙夜#4 | 文字识别：从数据趋动到模型自监督** - [B station](https://www.bilibili.com/video/BV1Zb41197V4)
- **社区开放麦#42 | 面向自动驾驶场景的纯视觉三维语义占有预测** - [B station](https://www.bilibili.com/video/BV1P54y1T7vS)
- **社区开放麦#43 | 高精度实例分割 PatchDCT** - [B station](https://www.bilibili.com/video/BV1Sx4y1w7JK)
- **AI奇妙夜#5 | “视觉与语言”跨模态智能及应用** - [B station](https://www.bilibili.com/video/BV1Y84y1g7nP)
- **CVPR 2023 有向目标检测角度预测新方法 — 相移编码 | 社区开放麦#45** - [B station](https://www.bilibili.com/video/BV1Cv4y1n72h)
- **业界可用的高性能的姿态估计模型能有多快？ | 社区开放麦#46** - [B station](https://www.bilibili.com/video/BV1Wc411p7HT)
- **CVPR2023 首个大规模全场景人体数据集 Human-Art | 社区开放麦#47** - [B station](https://www.bilibili.com/video/BV1Hs4y1d7bJ)
- **MOSS：如何打造对话式语言模型 | 社区开放麦#48** - [B station](https://www.bilibili.com/video/BV1fa4y1V7xG)
- **超大规模视觉通用感知模型-代季峰教授 | AI奇妙夜#6** - [B station](https://www.bilibili.com/video/BV1dM411g7Jn)
- **视频理解基础模型及下游应用-王利民教授 | AI奇妙夜#7** - [B station](https://www.bilibili.com/video/BV1rz4y1t7b7)
- **ICLR Spotlight | 在卷积网络上做BERT式预训练** - [B station](https://www.bilibili.com/video/BV11s4y1M7qL)
- **HumanBench：迈向以人为中心的通才模型** - [B station](https://www.bilibili.com/video/BV1Q24y1N72o)
- **低成本微调垂直领域专属 ChatGPT** - [B station](https://www.bilibili.com/video/BV1Pz4y1q7yA)
- **自动驾驶场景中的半监督点云分割** - [B station](https://www.bilibili.com/video/BV11u4y1d7S2)
- **基于 Visual Transformer 的分割模型综述** - [B station](https://www.bilibili.com/video/BV1tc411M7DC)
- **AI 2.0：突破性技术推动智能制造的应用创新** - [B station](https://www.bilibili.com/video/BV1ch4y1M7Re)
- **基于 SAM 大模型的实例分割研究 —— RSPrompter** - [B station](https://www.bilibili.com/video/BV1J94y1i7bB)
- **开放检测视觉场景理解 | 社区开放麦** - [B station](https://www.bilibili.com/video/BV1u14y1R7mn)
- **运用 SAM 模型分割任意点云** - [B station](https://www.bilibili.com/video/BV1gm4y1j7M2)
- **MMBench：基于ChatGPT的全方位多模能力评测体系** - [B station](https://www.bilibili.com/video/BV16z4y1x7qG)
- **迈向更强的端到端多人姿态估计** - [B station](https://www.bilibili.com/video/BV1fj41197R9)
- **SAM 时代，图像/视频分割将何去何从？** - [B station](https://www.bilibili.com/video/BV1ZP41147xQ)
- **MFF：简单高效的多级特征融合自监督方法 | ICCV 2023** - [B station](https://www.bilibili.com/video/BV1q94y1z7Xe)
- **更好的人体姿态，更好的生成图像** - [B station](https://www.bilibili.com/video/BV1rw411Q7t6)
- **基于大规模多模态扩散模型的文本到视频生成** - [B station](https://www.bilibili.com/video/BV1BP411h7oQ)
- **多模态任务终结者：Meta-Transformer** - [B station](https://www.bilibili.com/video/BV1Bu4y1y714)
- **迈向更强的开集目标检测-From Detection to Grounding** - [B station](https://www.bilibili.com/video/BV1Mk4y1F7cp)
- **如何基于大模型构建智能体？多机构百页综述从交互角度详解 AI Agent！** - [B station](https://www.bilibili.com/video/BV1884y1U7CR)
- **你的3D感知模型够鲁棒吗？Robo3D告诉你答案！** - [B station](https://www.bilibili.com/video/BV1nu411u7W6)
- **如何高效微调大模型？技术原理与最佳实践揭秘！** - [B station](https://www.bilibili.com/video/BV1qw411c7Hd)
- **大模型时代通用检测趋势解读及MMDetection未来展望** - [B station](https://www.bilibili.com/video/BV1o94y1L7fg)
- **CVPR23 | 3D Occupancy 预测冠军方案：FB-OCC** - [B station](https://www.bilibili.com/video/BV1PX4y1e7zz)
- **多模态 Agents：用大模型语言模型串联多模态专家** - [B station](https://www.bilibili.com/video/BV1mM411X7Zn)
- **探索未知：LLM Agent 应用开发的全新时代** - [B station](https://www.bilibili.com/video/BV1W84y197qq)
- **AI时代数据应用的全链路工厂- Chat2DB** - [B station](https://www.bilibili.com/video/BV1re411m7p3)
- **语音与音频生成 Amphion揭秘霉霉如何演唱《稻香》** - [B station](https://www.bilibili.com/video/BV1AV411R7SS)
- **RTMPose 家族史诗级更新！多人、全身一网打尽** - [B station](https://www.bilibili.com/video/BV1P5411v7tz)
- **清华提出首个面向无监督和半监督新意图发现的文本聚类框架USNID** - [B station](https://www.bilibili.com/video/BV1464y1w73f)
- **Beyond Segmentation Anything，超越SAM** - [B station](https://www.bilibili.com/video/BV1xC411r7qq)
- **Sora 夜谈之 Video Diffusion 综述** - [B station](https://www.bilibili.com/video/BV1cJ4m1e7sQ)
- **新一代换脸神器 InstantID：高保真人像秒级生成** - [B station](https://www.bilibili.com/video/BV1HH4y177T5)
- **CVPR 2024 - 具身智能中的多模态三维感知思考** - [B station](https://www.bilibili.com/video/BV1nt421V7UY)
- **PK 周杰伦，全能音乐创作大模型 SongComposer 作词作曲令人惊叹** - [B station](https://www.bilibili.com/video/BV1bw4m1d7dK)
- **Stable Diffusion 3 论文技术解析，架构细节大揭秘！** - [B station](https://www.bilibili.com/video/BV1Ni421d7ud)
- **无需训练的 Stable Diffusion 视频编辑方法** - [B station](https://www.bilibili.com/video/BV12w4m1R75t)
- **Latte 专场: 深度解读视频生成与训练技术** - [B station](https://www.bilibili.com/video/BV14F4m1K7Wz)
- **微软研究院谭旭带来零样本 TTS 模型 NaturalSpeech 3** - [B station](https://www.bilibili.com/video/BV1tm421s7B6)
- **零样本语音生成大模型与Amphion实践** - [B station](https://www.bilibili.com/video/BV18C41177JA)
- **多模态大模型的技术实践与思考** - [B station](https://www.bilibili.com/video/BV17n4y1d7wp)
- **当大模型遇上心理咨询：基于心理咨询报告的对话重构和评测框架CPsyCoun** - [B station](https://www.bilibili.com/video/BV1vJ4m1g7G4)
- **ACL 24 论文分享（东北大学信息检索小组场）** - [B station](https://www.bilibili.com/video/BV144421Q7ir)
- **SD-Eval新基准，让语音交互大模型情智兼备** - [B station](https://www.bilibili.com/video/BV16E421A7wU)
- **魔搭社区-浦语模型和工具实战** - [B station](https://www.bilibili.com/video/BV1zy411i7yp)
- **开源工具MinerU助力复杂PDF高效解析提取** - [B station](https://www.bilibili.com/video/BV15rHSeyEk2)
- **MindSearch：AI 时代的“思考型”智能搜索引擎** - [B station](https://www.bilibili.com/video/BV1UHy3YYEHz)
- **MaskGCT：基于掩码生成模型的大规模零样本 TTS 模型** - [B station](https://www.bilibili.com/video/BV1LJD1YsEd4)
- **玩转 MMYOLO 之工具篇（一）：特征图可视化** - [B station](https://www.bilibili.com/video/BV188411s7o8)
- **玩转 MMYOLO 之基础篇（一）：配置文件全解读** - [B station](https://www.bilibili.com/video/BV1214y157ck)
- **【MMYOLO】超酷炫 RTMDet 特征图可视化 demo** - [B station](https://www.bilibili.com/video/BV1je4y1478R)
- **玩转 MMYOLO 之实用篇（一）: 源码阅读和调试「必备」技巧** - [B station](https://www.bilibili.com/video/BV1N14y1V7mB)
- **MMYOLO 社区贡献者经验分享会** - [B station](https://www.bilibili.com/video/BV12d4y1r7Nd)
- **玩转 MMYOLO 之基础篇（二）： 工程文件结构简析** - [B station](https://www.bilibili.com/video/BV1LP4y117jS)
- **玩转 MMYOLO 之实用篇（二）: 10分钟带你换遍主干网络** - [B station](https://www.bilibili.com/video/BV1JG4y1d7GC)
- **玩转 MMYOLO 之工具篇（二）：十分钟轻松掌握大图推理** - [B station](https://www.bilibili.com/video/BV1EK411R7Ws)
- **玩转 MMYOLO 之实用篇（三）：自定义数据集从标注到部署保姆级教程** - [B station](https://www.bilibili.com/video/BV1RG4y137i5)
- **玩转 MMYOLO 之实用篇（四）：顶会第一步 · 模块自定义** - [B station](https://www.bilibili.com/video/BV1yd4y1j7VD)
- **玩转 MMYOLO 之实用篇（五）：训练和测试技巧合集** - [B station](https://www.bilibili.com/video/BV1GM4y1U77z)
- **清华大学导师亲授！3D目标检测超硬核课程新鲜出炉~** - [B station](https://www.bilibili.com/video/BV1Sc411K7L1)
- **人体关键点检测与MMPose** - [B station](https://www.bilibili.com/video/BV1kk4y1L7Xb)
- **1. PyTorch 模型部署基础知识** - [B station](https://www.bilibili.com/video/BV1Tx4y1F768)
- **2. 安装配置 MMDeploy 环境** - [B station](https://www.bilibili.com/video/BV1yX4y1X7jp)
- **3. 部署 MMClassification 图像分类模型** - [B station](https://www.bilibili.com/video/BV1V84y1J7MT)
- **4. 部署 MMDetection 目标检测模型** - [B station](https://www.bilibili.com/video/BV11R4y1v7L2)
- **自监督学习与 MMSelfSup** - [B station](https://www.bilibili.com/video/BV1iu4y1e7tV)
- **Linux 前置基础（基本命令、SSH及端口映射）** - [B station](https://www.bilibili.com/video/BV13U1VYmEUr)
- **Python 前置基础（熟悉断点调试、依赖指定路径安装）** - [B station](https://www.bilibili.com/video/BV1u61jYSExg)
- **Git 前置基础（熟悉常见 Git 命令及GitHub 平台）** - [B station](https://www.bilibili.com/video/BV15MShYkEgg)
- **玩转Hugging Face/魔搭/魔乐平台(熟悉模型下载上传及应用上传)** - [B station](https://www.bilibili.com/video/BV1XxStYYEH1)
- **书生·浦语大模型开源开放体系** - [B station](https://www.bilibili.com/video/BV1CkSUYGE1v)
- **玩转书生「多模态对话」与「AI 搜索」产品** - [B station](https://www.bilibili.com/video/BV1ExDQYyEAA)
- **浦语提示词工程实践** - [B station](https://www.bilibili.com/video/BV1tjS7YfEWJ)
- **浦语+LlamaIndex 外挂知识库 RAG 实践** - [B station](https://www.bilibili.com/video/BV1YzDJY1E2i)
- **XTuner 微调 InternLM 个人小助手认知实践** - [B station](https://www.bilibili.com/video/BV1G9SJYGEtD)
- **OpenCompass 评测书生大模型实践** - [B station](https://www.bilibili.com/video/BV1dtD4YKENj)
- **Lagent 从零搭建你的 Multi-Agent (书生·浦语 API 版)** - [B station](https://www.bilibili.com/video/BV19RzcYaEFy)
- **LMDeploy 量化部署进阶实践** - [B station](https://www.bilibili.com/video/BV18aUHY3EEG)
- **多模态大模型发展简述及其微调部署实践(InternVL2为例)** - [B station](https://www.bilibili.com/video/BV1nESCYWEnN)
- **InternLM+WasmEdge 部署智能体实践** - [B station](https://www.bilibili.com/video/BV1K2rAYeEXG)
- **EgoExolearn跨视角技能学习数据集** - [B station](https://www.bilibili.com/video/BV1pT42167pQ)
- **单阶段多维度模型搜索范式** - [B station](https://www.bilibili.com/video/BV1Yb421J7wA)
- **MVBench 多模态视频评测体系** - [B station](https://www.bilibili.com/video/BV1ZE4m1R7Tc)
- **人机协作的视觉生成** - [B station](https://www.bilibili.com/video/BV1fZ421N7re)
- **个性化图像动画生成器，利用文本提示将图像变为奇妙的动画** - [B station](https://www.bilibili.com/video/BV1PE4m197ZM)
- **基于像素点的拖拽式图像编辑分享** - [B station](https://www.bilibili.com/video/BV1XH4y1c78r)
- **GenNBV：面向主动三维重建的可泛化最佳视角探索策略** - [B station](https://www.bilibili.com/video/BV1yy411i7jh)
- **多模态大模型幻觉成因解释以及基于惩罚回退策略的幻觉缓解方法** - [B station](https://www.bilibili.com/video/BV1QH4y1c7p3)
- **中文常识推理基准-CHARM** - [B station](https://www.bilibili.com/video/BV1QcmdYiExz)
- **分享 SALAD-BENCH 数据集与评估方法** - [B station](https://www.bilibili.com/video/BV1KimoYaExY)
- **评估大语言模型多轮对话能力的细粒度评测集** - [B station](https://www.bilibili.com/video/BV1mvmoYAEAv)
- **ConvBench：多轮视觉对话评测基准与能力解耦评测方式** - [B station](https://www.bilibili.com/video/BV1QbcRevE61)
- **GTA：大模型复杂任务工具调用能力评测** - [B station](https://www.bilibili.com/video/BV1cucReJETD)
- **MMDU：高质量多图多轮对话数据集** - [B station](https://www.bilibili.com/video/BV1HTcReDEhX)
- **MMLongBench-Doc：使用可视化对长上下文文档理解进行基准测试** - [B station](https://www.bilibili.com/video/BV19scReMEdS)
- **多模态推理的评测以及后训练** - [B station](https://www.bilibili.com/video/BV1C9XrYaEyz)
- **多模态动态评测（Oral）** - [B station](https://www.bilibili.com/video/BV1P9XrYYEje)
- **LOKI：基于多模态大模型的合成数据检测基准** - [B station](https://www.bilibili.com/video/BV1JJXrYdEXi)
- **Sim-CoT 驱动高效隐式思考** - [B station](https://www.bilibili.com/video/BV1VGEC6fErh)
- **数据分布解读 RL 如何“学新不忘旧”** - [B station](https://www.bilibili.com/video/BV1afE16NEXf)
- **数据驱动的大模型长度泛化推理新范式** - [B station](https://www.bilibili.com/video/BV1H2TF64Ek9)
- **利用智能体解锁地球观测的完整图景** - [B station](https://www.bilibili.com/video/BV1LUTj6FE9N)
- **冗余性解耦的高效长文本偏好优化** - [B station](https://www.bilibili.com/video/BV12uTQ6CEHz)
- **AI科研加速营第1课｜用AI快速看懂一个研究方向** - [B station](https://www.bilibili.com/video/BV1jMY163EWE)
- **AI科研加速营第2课｜AI论文工作流：检索、精读与核验** - [B station](https://www.bilibili.com/video/BV1tTen6ZEmy)
- **AI科研加速营第3课｜建立可持续更新的研究上下文** - [B station](https://www.bilibili.com/video/BV11zec6NE3k)
- **AI科研加速营第4课｜AI辅助实验设计：科学数据与计算一体化实践** - [B station](https://www.bilibili.com/video/BV1FTeG6dEQ4)
- **AI科研加速营第5课｜AI辅助论文与课题申请书写作** - [B station](https://www.bilibili.com/video/BV1xLe16bE2p)
- **AI科研加速营第6课｜把科研方法沉淀为可复用的Agent Skill** - [B station](https://www.bilibili.com/video/BV1TZem6BEQP)
- **AI科研加速营第7课｜通往可扩展、统一的蛋白基础模型之路** - [B station](https://www.bilibili.com/video/BV1sHem6AEXD)
- **AI科研加速营第8课｜大模型时代的物质科学研究** - [B station](https://www.bilibili.com/video/BV1Vfhv6BEXx)
- **AI科研加速营第9课｜地球科学中的科学智能：从工具的革命到革命的工具** - [B station](https://www.bilibili.com/video/BV16RhE6TEmM)
- **OpenMMLab 环境配置 （一） Windows 11 CPU** - [B station](https://www.bilibili.com/video/BV1Bh41157gL)
- **通用、统一且灵活的开源算法平台 OpenMMLab 2.0 | CVPR 2023 （全英分享）** - [B station](https://www.bilibili.com/video/BV1Zg4y1P7LB)
- **视觉基础模型的探索：MMPreTrain | CVPR 2023 (全英分享)** - [B station](https://www.bilibili.com/video/BV11s4y1C7S9)
- **通用目标检测工具 MMDetection3.0 | CVPR 2023 （全英分享）** - [B station](https://www.bilibili.com/video/BV1214y1274j)
- **图像与视频生成、编辑和增强工具 MMagic | CVPR 2023 （全英分享）** - [B station](https://www.bilibili.com/video/BV1nX4y1q7DF)
- **面向人工智能的开放数据平台：OpenDataLab | CVPR 2023 （全英分享）** - [B station](https://www.bilibili.com/video/BV1Hm4y1a7Xa)
- **【CVPR-2022】| Kai Chen -- Overview of OpenMMLab and Recent Updates** - [B station](https://www.bilibili.com/video/BV1H84y1z7Ce)
- **【CVPR-2022】| Chen Change Loy -- Improving Video Super-Resolution** - [B station](https://www.bilibili.com/video/BV1mP411P7za)
- **【CVPR-2022】| Han Hu -- Convergence of Architectures and Learning Methods** - [B station](https://www.bilibili.com/video/BV1vG411j79R)
- **【CVPR-2022】| Hang Zhao -- Vision-centric 3D Perception** - [B station](https://www.bilibili.com/video/BV1y44y1f72z)
- **【CVPR-2022】| Haodong Duan -- Action Understanding in A Human-centric View** - [B station](https://www.bilibili.com/video/BV1iG4y1p78W)
- **Wenwei Zhang | General Detection with MMDetection** - [B station](https://www.bilibili.com/video/BV1A8411F7Ti)
- **OpenMMLab：视觉、语言与生成式人工智能开源平台** - [B station](https://www.bilibili.com/video/BV1z94y18767)
- **OpenMMLab基础模型研究进展** - [B station](https://www.bilibili.com/video/BV1tC4y157hc)
- **OpenDataLab —— 一个面向人工智能的开放数据平台** - [B station](https://www.bilibili.com/video/BV1334y1G7RA)
- **MMagic —— 图像与视频生成、编辑及增强工具库** - [B station](https://www.bilibili.com/video/BV1P94y187HE)
- **MMDetection：从通用目标检测迈向多模态智能体** - [B station](https://www.bilibili.com/video/BV1134y1u7dq)
- **书生·浦语大模型全链路开源体系** - [B station](https://www.bilibili.com/video/BV1Vx421X72D)
- **轻松玩转书生·浦语大模型趣味 Demo** - [B station](https://www.bilibili.com/video/BV1AH4y1H78d)
- **茴香豆：搭建你的 RAG 智能助理** - [B station](https://www.bilibili.com/video/BV1QA4m1F7t4)
- **XTuner 微调 LLM：1.8B、多模态、Agent** - [B station](https://www.bilibili.com/video/BV15m421j78d)
- **LMDeploy 量化部署 LLM-VLM 实践** - [B station](https://www.bilibili.com/video/BV1tr421x75B)
- **Lagent & AgentLego 智能体应用搭建** - [B station](https://www.bilibili.com/video/BV1Xt4217728)
- **OpenCompass 大模型评测实战** - [B station](https://www.bilibili.com/video/BV1Pm41127jU)
- **大模型微调数据构造（补充课程）** - [B station](https://www.bilibili.com/video/BV1Dx4y1z7Ju)
- **多模态简述** - [B station](https://www.bilibili.com/video/BV12E421A76T)
- **LMDeploy 量化部署 InternVL 浦语灵笔实践** - [B station](https://www.bilibili.com/video/BV11m421373q)
- **XTuner 微调 LLaVA 实践** - [B station](https://www.bilibili.com/video/BV1vZ421M7ig)
- **AI实战营第二期 开营仪式** - [B station](https://www.bilibili.com/video/BV1sc411V74M)
- **Github八万star，开源计算机视觉神器OpenMMLab** - [B station](https://www.bilibili.com/video/BV1js4y1i72P)
- **深度学习预训练与MMPretrain** - [B station](https://www.bilibili.com/video/BV1PN411y7C1)
- **目标检测与MMDetection** - [B station](https://www.bilibili.com/video/BV1Ak4y1p7W9)
- **MMDetection代码课** - [B station](https://www.bilibili.com/video/BV1Tm4y1q7fy)
- **语义分割与MMSegmentation** - [B station](https://www.bilibili.com/video/BV1gV4y1m74P)
- **玩转AIGC神器MMagic** - [B station](https://www.bilibili.com/video/BV1gM4y1n7vP)
- **【OpenMMLab 2.0 系列直播】OpenMMLab 2.0 整体介绍** - [B station](https://www.bilibili.com/video/BV1Yd4y1z7bo)
- **【OpenMMLab 2.0 系列直播】MMEngine & MMCV 介绍** - [B station](https://www.bilibili.com/video/BV15B4y1779M)
- **【OpenMMLab 2.0 系列直播】MMClassification 介绍** - [B station](https://www.bilibili.com/video/BV1x24y1R7mD)
- **【OpenMMLab 2.0 系列直播】MMSelfsup 介绍** - [B station](https://www.bilibili.com/video/BV1214y1h7CJ)
- **【OpenMMLab 2.0 系列直播】MMDetection 介绍** - [B station](https://www.bilibili.com/video/BV19G411g7w9)
- **【OpenMMLab 2.0 系列直播】MMDetection3D 介绍** - [B station](https://www.bilibili.com/video/BV1YD4y117w6)
- **【OpenMMLab 2.0 系列直播】OpenMMLab 社区荣誉体系介绍** - [B station](https://www.bilibili.com/video/BV1kB4y1J7u9)
- **【OpenMMLab 2.0 系列直播】MMSegmentation 介绍** - [B station](https://www.bilibili.com/video/BV1F841147JZ)
- **【OpenMMLab 2.0 系列直播】 MMAction2 介绍** - [B station](https://www.bilibili.com/video/BV1V841147Jp)
- **【OpenMMLab 2.0 系列直播】MMPose 介绍** - [B station](https://www.bilibili.com/video/BV11B4y1J7oD)
- **【OpenMMLab 2.0 系列直播】 MMEditing & MMGeneration 介绍** - [B station](https://www.bilibili.com/video/BV1Xd4y1M7zE)
- **【OpenMMLab 2.0 系列直播】MMOCR 介绍** - [B station](https://www.bilibili.com/video/BV1wY4y1K7DZ)
- **【OpenMMLab 2.0 系列直播】MMRazor 介绍** - [B station](https://www.bilibili.com/video/BV1ug411e7Jp)
- **【OpenMMLab 2.0 系列直播】MMYOLO 介绍** - [B station](https://www.bilibili.com/video/BV19e4y1674D)
- **【OpenMMLab 2.0 系列直播】RTMDet** - [B station](https://www.bilibili.com/video/BV1e841147GD)
- **大模型时代下视觉网络的创新设计与拓展 | 热门研究 云际会#1** - [B station](https://www.bilibili.com/video/BV18L411m7jU)
- **多模态大模型的前奏：迈向真实世界的通用感知 | 热门研究云际会#2** - [B station](https://www.bilibili.com/video/BV1W24y1c7mB)
- **探索之路：OCR 领域在大模型浪潮中的创新契机 | 热门研究云际会#3** - [B station](https://www.bilibili.com/video/BV1Lh411E787)
- **多模态扩散模型的革新应用 | 热门研究云际会#4** - [B station](https://www.bilibili.com/video/BV1pP411273K)
- **基于 SiliconCloud 平台使用 MindSearch** - [B station](https://www.bilibili.com/video/BV163sxeZEPi)
- **AI 实战营开营仪式** - [B station](https://www.bilibili.com/video/BV1o3411X7MB)
- **1 计算机视觉算法基础与OpenMMLab介绍** - [B station](https://www.bilibili.com/video/BV1Ty4y1X7X1)
- **2 计算机视觉之图像分类算法基础** - [B station](https://www.bilibili.com/video/BV1js4y1W7CN)
- **3 图像分类代码实战与超算平台介绍** - [B station](https://www.bilibili.com/video/BV1MA411k7NT)
- **4 目标检测算法基础** - [B station](https://www.bilibili.com/video/BV1Ay4y1Q7mC)
- **5 MMDetection 代码教学** - [B station](https://www.bilibili.com/video/BV1Av4y1475i)
- **6 语义分割算法基础** - [B station](https://www.bilibili.com/video/BV1s24y1W7Xa)
- **7 MMSegmentation 代码教学** - [B station](https://www.bilibili.com/video/BV1eT411R7Jq)
- **AI实战营 结营仪式** - [B station](https://www.bilibili.com/video/BV1ge4y1c7tY)
- **书生·浦语大模型全链路开源体系** - [B station](https://www.bilibili.com/video/BV1Rc411b7ns)
- **轻松玩转书生·浦语大模型趣味Demo** - [B station](https://www.bilibili.com/video/BV1Ci4y1z72H)
- **基于 InternLM 和 LangChain 搭建你的知识库** - [B station](https://www.bilibili.com/video/BV1sT4y1p71V)
- **XTuner 大模型单卡低成本微调实战** - [B station](https://www.bilibili.com/video/BV1yK4y1B75J)
- **XTuner 大模型低成本微调作业讲解——个人小助手认知微调实践** - [B station](https://www.bilibili.com/video/BV13t4y1o75X)
- **LMDeploy 大模型量化部署实践** - [B station](https://www.bilibili.com/video/BV1iW4y1A77P)
- **OpenCompass 大模型评测** - [B station](https://www.bilibili.com/video/BV1Gg4y1U7uc)