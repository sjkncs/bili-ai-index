# AI 论文精读

> Source: **VALSE_Webinar, deep_thoughts, 读论文的麦小哲, 秋刀鱼的炼丹工坊, 同济子豪兄, 先进编译实验室, OpenMMLab** - Snapshot: **2026-10-12** - **60** episodes.
> Data: [`items.json`](items.json)

## Data source / method / limits

**Data source**: `seasons_archives_list` for the episode list; `x/web-interface/view`
per video for its **`desc`** field.

**Method**: descriptions follow `[paper share] <full title> (<venue>) - <cn summary>`;
venue parsing is nesting-aware (handles `SE(3)` and nested conference parentheses).

**Limits**: the `paper` column comes from the **description**, because Bilibili
truncates video **titles** at 80 chars; missing venue/arXiv stays empty; index only.

## All 60 episodes

| # | paper | venue | category | arXiv | length | B station |
|---:|---|---|---|---|---:|---|
| 1 | 39、ConvNeXt模型代码逐行讲解 | - | AI 论文精读 | - | 33:12 | [link](https://www.bilibili.com/video/BV11Y41137VA) |
| 2 | 8、深入剖析PyTorch的state_dict、parameters、modules源码 | - | AI 论文精读 | - | 49:53 | [link](https://www.bilibili.com/video/BV12g411K7oq) |
| 3 | 29、PyTorch RNN的原理及其手写复现 | - | AI 论文精读 | - | 90:48 | [link](https://www.bilibili.com/video/BV13i4y1R7jB) |
| 4 | 论文分享 CSLE：强化学习安全策略如何从模拟器走向真实网络系统 | - | AI 论文精读 | - | 23:34 | [link](https://www.bilibili.com/video/BV13Rt96VEnk) |
| 5 | 26、手写卷积与转置卷积的代码总结 | - | AI 论文精读 | - | 41:48 | [link](https://www.bilibili.com/video/BV13U4y1K7op) |
| 6 | 49、cGAN及LSGAN的原理与PyTorch手写逐行讲解 | - | AI 论文精读 | - | 49:07 | [link](https://www.bilibili.com/video/BV1444y1G7y2) |
| 7 | 论文分享OSWorld-Human：电脑使用智能体离“高效”还有多远 | - | AI 论文精读 | [2506.16042](https://arxiv.org/abs/2506.16042) | 18:35 | [link](https://www.bilibili.com/video/BV14bgA6jEqk) |
| 8 | 22、PyTorch nn.Conv2d卷积网络使用教程 | - | AI 论文精读 | - | 33:34 | [link](https://www.bilibili.com/video/BV1644y1h7LN) |
| 9 | 论文分享BOOST：让低秩大模型在多GPU上真正跑快 | - | AI 论文精读 | [2512.12131](https://arxiv.org/abs/2512.12131) | 13:00 | [link](https://www.bilibili.com/video/BV1A4gJ6XEYs) |
| 10 | 论文分享HetRL：异构环境下的大模型强化学习调度框架 | - | AI 论文精读 | [2607.12345](https://arxiv.org/abs/2607.12345) | 9:34 | [link](https://www.bilibili.com/video/BV1APMS6AEYR) |
| 11 | 9、深入剖析PyTorch的nn.Sequential及ModuleList源码 | - | AI 论文精读 | - | 46:14 | [link](https://www.bilibili.com/video/BV1Cb4y187H1) |
| 12 | 7、深入剖析PyTorch nn.Module源码 | - | AI 论文精读 | - | 73:10 | [link](https://www.bilibili.com/video/BV1ch411b7yP) |
| 13 | 19、Transformer模型Encoder原理精讲及其PyTorch逐行实现 | - | AI 论文精读 | - | 110:37 | [link](https://www.bilibili.com/video/BV1cP4y1V7GF) |
| 14 | 28、Vision Transformer(ViT)模型原理及PyTorch逐行实现 | - | AI 论文精读 | - | 67:26 | [link](https://www.bilibili.com/video/BV1cS4y1M7wo) |
| 15 | 46、四种Position Embedding的原理与PyTorch手写逐行实现（Transformer/ViT/Swin-T/MAE） | - | AI 论文精读 | - | 63:49 | [link](https://www.bilibili.com/video/BV1DF411u7ST) |
| 16 | 21、Transformer Masked loss原理精讲及其PyTorch逐行实现 | - | AI 论文精读 | - | 45:54 | [link](https://www.bilibili.com/video/BV1dh411s7FW) |
| 17 | 论文分享SONAR：去中心化学习不是“连得越多越好” | - | AI 论文精读 | - | 11:31 | [link](https://www.bilibili.com/video/BV1DHuQ6HEch) |
| 18 | 23、手写并验证滑动相乘实现PyTorch二维卷积 | - | AI 论文精读 | - | 52:44 | [link](https://www.bilibili.com/video/BV1dP4y137er) |
| 19 | 50、NormalizingFlow(标准化流)论文导读与原理精讲 | - | AI 论文精读 | - | 65:16 | [link](https://www.bilibili.com/video/BV1dS4y1c7xB) |
| 20 | 论文分享 Cocoon：相关噪声提升差分隐私训练精度，为什么系统成本却会暴涨 | - | AI 论文精读 | - | 21:28 | [link](https://www.bilibili.com/video/BV1dVhc63EzM) |
| 21 | 32、基于PyTorch的文本分类项目模型与训练代码讲解 | - | AI 论文精读 | - | 55:10 | [link](https://www.bilibili.com/video/BV1eD4y1F7o4) |
| 22 | 25、手写实现nn.TransposedConv转置卷积 | - | AI 论文精读 | - | 52:18 | [link](https://www.bilibili.com/video/BV1fM4y1F7j5) |
| 23 | 15、Dropout原理以及其TF/Torch/Numpy源码实现 | - | AI 论文精读 | - | 45:45 | [link](https://www.bilibili.com/video/BV1gL4y1p7ww) |
| 24 | 3、PyTorch张量的运算API（下） | - | AI 论文精读 | - | 48:16 | [link](https://www.bilibili.com/video/BV1Hq4y1R7dM) |
| 25 | 38、ConvNeXt论文导读与模型精讲 | - | AI 论文精读 | - | 49:22 | [link](https://www.bilibili.com/video/BV1iP4y1M7nk) |
| 26 | 31、PyTorch GRU的原理及其手写复现 | - | AI 论文精读 | - | 39:18 | [link](https://www.bilibili.com/video/BV1jm4y1Q7uh) |
| 27 | 43、逐行讲解Masked AutoEncoder(MAE)的PyTorch代码 | - | AI 论文精读 | - | 110:32 | [link](https://www.bilibili.com/video/BV1JS4y1N7XE) |
| 28 | 论文分享OMAC：多智能体协作的整体优化框架 | - | AI 论文精读 | [2505.11765](https://arxiv.org/abs/2505.11765) | 21:03 | [link](https://www.bilibili.com/video/BV1JUK26mEcb) |
| 29 | 41、ResNet模型精讲以及PyTorch复现逐行讲解 | - | AI 论文精读 | - | 61:32 | [link](https://www.bilibili.com/video/BV1K3411p764) |
| 30 | 17、ConvMixer模型原理及其PyTorch逐行实现 | - | AI 论文精读 | - | 44:43 | [link](https://www.bilibili.com/video/BV1K34y1o74P) |
| 31 | 34、Swin Transformer论文精讲及其PyTorch逐行复现 | - | AI 论文精读 | - | 98:20 | [link](https://www.bilibili.com/video/BV1kF411v7vg) |
| 32 | 5、深入剖析PyTorch DataLoader源码 | - | AI 论文精读 | - | 42:30 | [link](https://www.bilibili.com/video/BV1kq4y1G75V) |
| 33 | 44、Layer Normalization论文导读与原理精讲 | - | AI 论文精读 | - | 72:06 | [link](https://www.bilibili.com/video/BV1Ma411i76P) |
| 34 | 35、基于PyTorch手写Attention-based Seq2Seq模型 | - | AI 论文精读 | - | 37:41 | [link](https://www.bilibili.com/video/BV1ML411w7k7) |
| 35 | 论文分享ICML 2026：RAG场景下的不确定性量化研究 | - | AI 论文精读 | - | 18:36 | [link](https://www.bilibili.com/video/BV1NPNY67EH4) |
| 36 | 48、快速复现PyTorch的Weight Normalization | - | AI 论文精读 | - | 19:07 | [link](https://www.bilibili.com/video/BV1NZ4y117VT) |
| 37 | 18、深入剖析PyTorch中的Transformer API源码 | - | AI 论文精读 | - | 67:40 | [link](https://www.bilibili.com/video/BV1o44y1Y7cp) |
| 38 | 1、PyTorch介绍与张量的创建 | - | AI 论文精读 | - | 42:00 | [link](https://www.bilibili.com/video/BV1ov411M7xL) |
| 39 | 13、详细推导自动微分Forward与Reverse模式 | - | AI 论文精读 | - | 54:08 | [link](https://www.bilibili.com/video/BV1PF411h7Ew) |
| 40 | 45、五种归一化的原理与PyTorch逐行手写实现讲解(BatchNorm/LayerNorm/InsNorm/GroupNorm/WeightNorm) | - | AI 论文精读 | - | 71:29 | [link](https://www.bilibili.com/video/BV1Pq4y1a7pH) |
| 41 | 论文分享 FLoRIST：联邦 LoRA 如何兼顾精度、通信与异构客户端 | - | AI 论文精读 | [2506.09199](https://arxiv.org/abs/2506.09199) | 30:44 | [link](https://www.bilibili.com/video/BV1pwY46aExv) |
| 42 | 24、手写并验证向量内积实现PyTorch二维卷积 | - | AI 论文精读 | - | 58:21 | [link](https://www.bilibili.com/video/BV1Qb4y1i7n5) |
| 43 | 20、Transformer模型Decoder原理精讲及其PyTorch逐行实现 | - | AI 论文精读 | - | 59:13 | [link](https://www.bilibili.com/video/BV1Qg411N74v) |
| 44 | 16、PyTorch中进行卷积残差模块算子融合 | - | AI 论文精读 | - | 74:04 | [link](https://www.bilibili.com/video/BV1sU4y1u7TM) |
| 45 | 14、保存与加载PyTorch训练的模型和超参数 | - | AI 论文精读 | - | 37:50 | [link](https://www.bilibili.com/video/BV1U341187TM) |
| 46 | 42、Masked AutoEncoder(MAE)论文导读与模型详细介绍 | - | AI 论文精读 | - | 62:41 | [link](https://www.bilibili.com/video/BV1u94y1f7NH) |
| 47 | 40、ConvNeXt分布式训练代码逐行讲解 | - | AI 论文精读 | - | 40:37 | [link](https://www.bilibili.com/video/BV1uP4y1u7qd) |
| 48 | 27、手写实现PyTorch的DilatedConv和GroupConv | - | AI 论文精读 | - | 59:41 | [link](https://www.bilibili.com/video/BV1UY411W7W8) |
| 49 | 6、PyTorch中搭建分类网络实例 | - | AI 论文精读 | - | 43:50 | [link](https://www.bilibili.com/video/BV1VF411a7oz) |
| 50 | 10、PyTorch autograd使用教程 | - | AI 论文精读 | - | 31:05 | [link](https://www.bilibili.com/video/BV1vL411u7bL) |
| 51 | 47、GAN原理讲解与PyTorch手写逐行讲解 | - | AI 论文精读 | - | 93:31 | [link](https://www.bilibili.com/video/BV1VT4y1e796) |
| 52 | 51、基于PyTorch ResNet18的果蔬分类逐行代码讲解 | - | AI 论文精读 | - | 68:13 | [link](https://www.bilibili.com/video/BV1vZ4y1h7X9) |
| 53 | 12、如何在PyTorch中训练模型 | - | AI 论文精读 | - | 37:33 | [link](https://www.bilibili.com/video/BV1wL411g7rv) |
| 54 | 37、Word Embedding原理精讲及其PyTorch API教程讲解 | - | AI 论文精读 | - | 49:54 | [link](https://www.bilibili.com/video/BV1wm4y1o7o5) |
| 55 | 2、PyTorch张量的运算API（上） | - | AI 论文精读 | - | 32:06 | [link](https://www.bilibili.com/video/BV1wQ4y1q7Bm) |
| 56 | 11、PyTorch中如何进行向量微分、矩阵微分与计算雅克比行列式 | - | AI 论文精读 | - | 33:12 | [link](https://www.bilibili.com/video/BV1Xr4y1r7wa) |
| 57 | 33、完整讲解PyTorch多GPU分布式训练代码编写 | - | AI 论文精读 | - | 74:56 | [link](https://www.bilibili.com/video/BV1xZ4y1S7dG) |
| 58 | 4、PyTorch的Dataset与DataLoader详细使用教程 | - | AI 论文精读 | - | 35:30 | [link](https://www.bilibili.com/video/BV1yP4y1L7cC) |
| 59 | 30、PyTorch LSTM和LSTMP的原理及其手写复现 | - | AI 论文精读 | - | 76:29 | [link](https://www.bilibili.com/video/BV1zq4y1m7aH) |
| 60 | 36、PyTorch训练加速技巧与爱因斯坦标示法 | - | AI 论文精读 | - | 65:52 | [link](https://www.bilibili.com/video/BV1ZY411b78A) |

## Per entry

- **39、ConvNeXt模型代码逐行讲解** - [B station](https://www.bilibili.com/video/BV11Y41137VA)
- **8、深入剖析PyTorch的state_dict、parameters、modules源码** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV12g411K7oq)
- **29、PyTorch RNN的原理及其手写复现** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV13i4y1R7jB)
- **论文分享 CSLE：强化学习安全策略如何从模拟器走向真实网络系统** - [project](https://proceedings.mlsys.org/paper_files/paper/2026/hash/87eaaa8605a1a472d9a9756e7500517b-Abstract-Conference.html]) | [B station](https://www.bilibili.com/video/BV13Rt96VEnk)
- **26、手写卷积与转置卷积的代码总结** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV13U4y1K7op)
- **49、cGAN及LSGAN的原理与PyTorch手写逐行讲解** - [B station](https://www.bilibili.com/video/BV1444y1G7y2)
- **论文分享OSWorld-Human：电脑使用智能体离“高效”还有多远** - [arXiv:2506.16042](https://arxiv.org/abs/2506.16042) | [project](https://github.com/WukLab/osworld-human) | [B station](https://www.bilibili.com/video/BV14bgA6jEqk)
- **22、PyTorch nn.Conv2d卷积网络使用教程** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1644y1h7LN)
- **论文分享BOOST：让低秩大模型在多GPU上真正跑快** - [arXiv:2512.12131](https://arxiv.org/abs/2512.12131) | [project](https://github.com/Arcana-2236/BOOST) | [B station](https://www.bilibili.com/video/BV1A4gJ6XEYs)
- **论文分享HetRL：异构环境下的大模型强化学习调度框架** - [arXiv:2607.12345](https://arxiv.org/abs/2607.12345) | [project](https://github.com/hetrl-project/HetRL) | [B station](https://www.bilibili.com/video/BV1APMS6AEYR)
- **9、深入剖析PyTorch的nn.Sequential及ModuleList源码** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1Cb4y187H1)
- **7、深入剖析PyTorch nn.Module源码** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1ch411b7yP)
- **19、Transformer模型Encoder原理精讲及其PyTorch逐行实现** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1cP4y1V7GF)
- **28、Vision Transformer(ViT)模型原理及PyTorch逐行实现** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1cS4y1M7wo)
- **46、四种Position Embedding的原理与PyTorch手写逐行实现（Transformer/ViT/Swin-T/MAE）** - [B station](https://www.bilibili.com/video/BV1DF411u7ST)
- **21、Transformer Masked loss原理精讲及其PyTorch逐行实现** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1dh411s7FW)
- **论文分享SONAR：去中心化学习不是“连得越多越好”** - [project](https://mlsys.org/virtual/2026/oral/3857) | [B station](https://www.bilibili.com/video/BV1DHuQ6HEch)
- **23、手写并验证滑动相乘实现PyTorch二维卷积** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1dP4y137er)
- **50、NormalizingFlow(标准化流)论文导读与原理精讲** - [B station](https://www.bilibili.com/video/BV1dS4y1c7xB)
- **论文分享 Cocoon：相关噪声提升差分隐私训练精度，为什么系统成本却会暴涨** - [project](https://www.usenix.org/conference/osdi26/presentation/kim-donghwan) | [B station](https://www.bilibili.com/video/BV1dVhc63EzM)
- **32、基于PyTorch的文本分类项目模型与训练代码讲解** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1eD4y1F7o4)
- **25、手写实现nn.TransposedConv转置卷积** - [B station](https://www.bilibili.com/video/BV1fM4y1F7j5)
- **15、Dropout原理以及其TF/Torch/Numpy源码实现** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1gL4y1p7ww)
- **3、PyTorch张量的运算API（下）** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1Hq4y1R7dM)
- **38、ConvNeXt论文导读与模型精讲** - [B station](https://www.bilibili.com/video/BV1iP4y1M7nk)
- **31、PyTorch GRU的原理及其手写复现** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1jm4y1Q7uh)
- **43、逐行讲解Masked AutoEncoder(MAE)的PyTorch代码** - [B station](https://www.bilibili.com/video/BV1JS4y1N7XE)
- **论文分享OMAC：多智能体协作的整体优化框架** - [arXiv:2505.11765](https://arxiv.org/abs/2505.11765) | [project](https://github.com/xiwenchao/OMAC) | [B station](https://www.bilibili.com/video/BV1JUK26mEcb)
- **41、ResNet模型精讲以及PyTorch复现逐行讲解** - [B station](https://www.bilibili.com/video/BV1K3411p764)
- **17、ConvMixer模型原理及其PyTorch逐行实现** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1K34y1o74P)
- **34、Swin Transformer论文精讲及其PyTorch逐行复现** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1kF411v7vg)
- **5、深入剖析PyTorch DataLoader源码** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1kq4y1G75V)
- **44、Layer Normalization论文导读与原理精讲** - [B station](https://www.bilibili.com/video/BV1Ma411i76P)
- **35、基于PyTorch手写Attention-based Seq2Seq模型** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1ML411w7k7)
- **论文分享ICML 2026：RAG场景下的不确定性量化研究** - [B station](https://www.bilibili.com/video/BV1NPNY67EH4)
- **48、快速复现PyTorch的Weight Normalization** - [B station](https://www.bilibili.com/video/BV1NZ4y117VT)
- **18、深入剖析PyTorch中的Transformer API源码** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1o44y1Y7cp)
- **1、PyTorch介绍与张量的创建** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1ov411M7xL)
- **13、详细推导自动微分Forward与Reverse模式** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1PF411h7Ew)
- **45、五种归一化的原理与PyTorch逐行手写实现讲解(BatchNorm/LayerNorm/InsNorm/GroupNorm/WeightNorm)** - [B station](https://www.bilibili.com/video/BV1Pq4y1a7pH)
- **论文分享 FLoRIST：联邦 LoRA 如何兼顾精度、通信与异构客户端** - [arXiv:2506.09199](https://arxiv.org/abs/2506.09199) | [project](https://github.com/DASS-Lab-Group/FLoRIST) | [B station](https://www.bilibili.com/video/BV1pwY46aExv)
- **24、手写并验证向量内积实现PyTorch二维卷积** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1Qb4y1i7n5)
- **20、Transformer模型Decoder原理精讲及其PyTorch逐行实现** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1Qg411N74v)
- **16、PyTorch中进行卷积残差模块算子融合** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1sU4y1u7TM)
- **14、保存与加载PyTorch训练的模型和超参数** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1U341187TM)
- **42、Masked AutoEncoder(MAE)论文导读与模型详细介绍** - [B station](https://www.bilibili.com/video/BV1u94y1f7NH)
- **40、ConvNeXt分布式训练代码逐行讲解** - [B station](https://www.bilibili.com/video/BV1uP4y1u7qd)
- **27、手写实现PyTorch的DilatedConv和GroupConv** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1UY411W7W8)
- **6、PyTorch中搭建分类网络实例** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1VF411a7oz)
- **10、PyTorch autograd使用教程** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1vL411u7bL)
- **47、GAN原理讲解与PyTorch手写逐行讲解** - [B station](https://www.bilibili.com/video/BV1VT4y1e796)
- **51、基于PyTorch ResNet18的果蔬分类逐行代码讲解** - [B station](https://www.bilibili.com/video/BV1vZ4y1h7X9)
- **12、如何在PyTorch中训练模型** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1wL411g7rv)
- **37、Word Embedding原理精讲及其PyTorch API教程讲解** - [B station](https://www.bilibili.com/video/BV1wm4y1o7o5)
- **2、PyTorch张量的运算API（上）** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1wQ4y1q7Bm)
- **11、PyTorch中如何进行向量微分、矩阵微分与计算雅克比行列式** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1Xr4y1r7wa)
- **33、完整讲解PyTorch多GPU分布式训练代码编写** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1xZ4y1S7dG)
- **4、PyTorch的Dataset与DataLoader详细使用教程** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1yP4y1L7cC)
- **30、PyTorch LSTM和LSTMP的原理及其手写复现** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1zq4y1m7aH)
- **36、PyTorch训练加速技巧与爱因斯坦标示法** - [project](https://live.bilibili.com/14297368?spm_id_from=333.999.0.0) | [B station](https://www.bilibili.com/video/BV1ZY411b78A)