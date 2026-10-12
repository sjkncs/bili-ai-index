# 弹幕讨论聚合 · 跟李沐学AI

> 快照：**2026-10-12**　覆盖 **106** 集　弹幕总数 **64,724** 条　有实质内容 **26,517** 条　重点标记 **10,545** 条

## 数据来源 · 计算方法 · 口径限制

**数据来源**：B 站弹幕接口 `comment.bilibili.com/<cid>.xml`（`cid` 来自 `x/web-interface/view` 的 `pages[0]`）。

**计算方法**
1. 抓取每集全部弹幕（`--compressed` 必需——该接口返回 deflate 压缩，不解压只能得到二进制）。
2. 保留长度 ≥ 10 字符且不含纯感叹/打卡类噪声的条目；同一句话被多人发送只保留一条，记录发送次数（重复次数本身反映观众共识度）。
3. 按关键词打分（技术词、解释性措辞、长度、重复次数）标记「重点」，但**不删除**其余条目——按 Top-N 截断会仅因排序更靠前的条目存在而丢掉实质内容，调整分数只能改变丢掉哪一条，不能解决这个问题。
4. 全部条目按**时间戳**排序，与视频进度对齐。

**口径限制（重要）**
- **弹幕是观众个人言论，未经核实，可能有错。本附录不为其正确性背书，不可直接作为事实引用。**
- 「重点」标记是**启发式排序**，不是质量或正确性的判定。
- 弹幕不是评论：B 站 **匿名评论接口每条视频只返回 3 条**（实测 4 个视频分别声明 216/279/1342 条，均只返回 3 条），完整评论需要登录 Cookie，本附录**不含评论区**。
- 弹幕存在时间显示漂移与重复发送，同一句话的实际出现次数可能高于记录值。
- 本附录只覆盖 **跟李沐学AI** 一个账号，其他账号尚未抓取。

## 各集一览（按弹幕数降序）

| # | 集 | 视频 | 弹幕总数 | 有实质内容 | 重点 |
|---:|---|---|---:|---:|---:|
| 1 | Transformer论文逐段精读【论文精读】 | [BV1pu411o7BE](danmaku/BV1pu411o7BE.md) | 6749 | 2968 | 150 |
| 2 | CLIP 论文逐段精读【论文精读】 | [BV1SL4y1s7LQ](danmaku/BV1SL4y1s7LQ.md) | 3122 | 1416 | 150 |
| 3 | 零基础多图详解图神经网络（GNN/GCN）【论文精读】 | [BV1iT4y1d7zP](danmaku/BV1iT4y1d7zP.md) | 2994 | 1238 | 150 |
| 4 | ViT论文逐段精读【论文精读】 | [BV15P4y137jb](danmaku/BV15P4y137jb.md) | 2896 | 1271 | 150 |
| 5 | 对比学习论文综述【论文精读】 | [BV19S4y1M7hm](danmaku/BV19S4y1M7hm.md) | 2167 | 817 | 150 |
| 6 | ResNet论文逐段精读【论文精读】 | [BV1P3411y7nn](danmaku/BV1P3411y7nn.md) | 2063 | 749 | 150 |
| 7 | AlexNet论文逐段精读【论文精读】 | [BV1hq4y157t1](danmaku/BV1hq4y157t1.md) | 2060 | 738 | 150 |
| 8 | GPT，GPT-2，GPT-3 论文精读【论文精读】 | [BV1AF411b7xQ](danmaku/BV1AF411b7xQ.md) | 2015 | 936 | 150 |
| 9 | GAN论文逐段精读【论文精读】 | [BV1rb4y187vD](danmaku/BV1rb4y187vD.md) | 1933 | 675 | 150 |
| 10 | MoCo 论文逐段精读【论文精读】 | [BV1C3411s7t9](danmaku/BV1C3411s7t9.md) | 1785 | 857 | 150 |
| 11 | Swin Transformer论文精读【论文精读】 | [BV13L4y1475U](danmaku/BV13L4y1475U.md) | 1764 | 853 | 150 |
| 12 | GPT-4论文精读【论文精读·53】 | [BV1vM4y1U7b5](danmaku/BV1vM4y1U7b5.md) | 1696 | 827 | 150 |
| 13 | DALL·E 2（内含扩散模型介绍）【论文精读】 | [BV17r4y1u77B](danmaku/BV17r4y1u77B.md) | 1480 | 636 | 150 |
| 14 | BERT 论文逐段精读【论文精读】 | [BV1PL411M7eQ](danmaku/BV1PL411M7eQ.md) | 1454 | 722 | 150 |
| 15 | InstructGPT 论文精读【论文精读·48】 | [BV1hd4y187CR](danmaku/BV1hd4y187CR.md) | 1314 | 596 | 150 |
| 16 | 斯坦福 2022 年 AI 指数报告精读【论文精读】 | [BV1s44y1N7eu](danmaku/BV1s44y1N7eu.md) | 1194 | 289 | 150 |
| 17 | 安静、高性价比双卡装机【100亿模型计划】 | [BV1NB4y1L7R8](danmaku/BV1NB4y1L7R8.md) | 1086 | 396 | 150 |
| 18 | MAE 论文逐段精读【论文精读】 | [BV1sq4y1q77t](danmaku/BV1sq4y1q77t.md) | 1055 | 478 | 150 |
| 19 | DETR 论文精读【论文精读】 | [BV1GB4y1X72R](danmaku/BV1GB4y1X72R.md) | 1027 | 468 | 150 |
| 20 | 1.1 课程介绍【斯坦福21秋季：实用机器学习中文版】 | [BV13U4y1N7Uo](danmaku/BV13U4y1N7Uo.md) | 993 | 224 | 150 |
| 21 | 参数服务器（Parameter Server）逐段精读【论文精读】 | [BV1YA4y197G8](danmaku/BV1YA4y197G8.md) | 967 | 310 | 150 |
| 22 | 9年后重读深度学习奠基作之一：AlexNet【论文精读·2】 | [BV1ih411J7Kz](danmaku/BV1ih411J7Kz.md) | 915 | 308 | 150 |
| 23 | AlphaFold 2 论文精读【论文精读】 | [BV1oR4y1K7Xr](danmaku/BV1oR4y1K7Xr.md) | 895 | 375 | 150 |
| 24 | Windows 下安装 CUDA 和 Pytorch 跑深度学习 - 动手学深度学习v2 | [BV18K411w7Vs](danmaku/BV18K411w7Vs.md) | 784 | 440 | 150 |
| 25 | 大模型时代下做科研的四个思路【论文精读·52】 | [BV1oX4y1d7X6](danmaku/BV1oX4y1d7X6.md) | 765 | 319 | 150 |
| 26 | 1.4 数据标注【斯坦福21秋季：实用机器学习中文版】 | [BV1HL41147aL](danmaku/BV1HL41147aL.md) | 637 | 244 | 150 |
| 27 | CLIP 改进工作串讲（上）【论文精读·42】 | [BV1FV4y1p7Lm](danmaku/BV1FV4y1p7Lm.md) | 608 | 315 | 150 |
| 28 | Llama 3.1论文精读 · 1. 导言【论文精读·54】 | [BV1WM4m1y7Uh](danmaku/BV1WM4m1y7Uh.md) | 607 | 179 | 150 |
| 29 | 肝了6个月的AudioLLM，开源了【100亿模型计划】 | [BV1LGbozkEDY](danmaku/BV1LGbozkEDY.md) | 584 | 211 | 150 |
| 30 | OpenAI Whisper 精读【论文精读·45】 | [BV1VG4y1t74x](danmaku/BV1VG4y1t74x.md) | 532 | 195 | 150 |
| 31 | 适合新手的 100TB 数据存储方案【100亿模型计划】 | [BV1Re4y1z7ce](danmaku/BV1Re4y1z7ce.md) | 526 | 225 | 150 |
| 32 | 如何读论文【论文精读·1】 | [BV1H44y1t75x](danmaku/BV1H44y1t75x.md) | 524 | 179 | 150 |
| 33 | 高性价比的 500TB 数据存储方案【100亿模型计划】 | [BV1ut4y1M7q5](danmaku/BV1ut4y1M7q5.md) | 505 | 210 | 150 |
| 34 | ViLT 论文精读【论文精读】 | [BV14r4y1j74y](danmaku/BV14r4y1j74y.md) | 505 | 212 | 150 |
| 35 | 跟读者建立联系【研究的艺术·一】 | [BV1hY411T7vy](danmaku/BV1hY411T7vy.md) | 493 | 111 | 111 |
| 36 | 多模态论文串讲·上【论文精读·46】 | [BV1Vd4y1v77v](danmaku/BV1Vd4y1v77v.md) | 476 | 222 | 150 |
| 37 | 2.1 探索性数据分析【斯坦福21秋季：实用机器学习中文版】 | [BV1Xh411p7M9](danmaku/BV1Xh411p7M9.md) | 471 | 204 | 150 |
| 38 | 1.3 网页数据抓取【斯坦福21秋季：实用机器学习中文版】 | [BV1JM4y137kK](danmaku/BV1JM4y137kK.md) | 453 | 148 | 148 |
| 39 | 多模态论文串讲·下【论文精读·49】 | [BV1fA411Z772](danmaku/BV1fA411Z772.md) | 431 | 195 | 150 |
| 40 | Anthropic LLM 论文精读【论文精读·51】 | [BV1XY411B7nM](danmaku/BV1XY411B7nM.md) | 423 | 156 | 150 |
| 41 | Deepmind用机器学习指导数学直觉论文逐段精读【论文精读】 | [BV1YZ4y1S72j](danmaku/BV1YZ4y1S72j.md) | 417 | 164 | 150 |
| 42 | 视频理解论文串讲（下）【论文精读】 | [BV11Y411P7ep](danmaku/BV11Y411P7ep.md) | 381 | 146 | 146 |
| 43 | OpenAI Codex 论文精读【论文精读】 | [BV1iY41137Zi](danmaku/BV1iY41137Zi.md) | 375 | 155 | 150 |
| 44 | 1.2 数据获取【斯坦福21秋季：实用机器学习中文版】 | [BV1Lf4y1n7LN](danmaku/BV1Lf4y1n7LN.md) | 375 | 108 | 108 |
| 45 | 撑起计算机视觉半边天的ResNet【论文精读】 | [BV1Fb4y1h73E](danmaku/BV1Fb4y1h73E.md) | 369 | 140 | 140 |
| 46 | CLIP 改进工作串讲（下）【论文精读·42】 | [BV1gg411U7n4](danmaku/BV1gg411U7n4.md) | 367 | 140 | 140 |
| 47 | Pathways 论文精读【论文精读】 | [BV1xB4y1m7Xi](danmaku/BV1xB4y1m7Xi.md) | 339 | 101 | 101 |
| 48 | 双流网络论文逐段精读【论文精读】 | [BV1mq4y1x7RU](danmaku/BV1mq4y1x7RU.md) | 334 | 145 | 145 |
| 49 | 你（被）吐槽过论文不够 novel 吗？【论文精读】 | [BV1ea41127Bq](danmaku/BV1ea41127Bq.md) | 331 | 126 | 126 |
| 50 | 给小朋友做的AI工具：把喜欢的书读出来 | [BV1xbkkYGEQq](danmaku/BV1xbkkYGEQq.md) | 319 | 118 | 118 |
| 51 | Chain of Thought论文、代码和资源【论文精读·43】 | [BV1t8411e7Ug](danmaku/BV1t8411e7Ug.md) | 282 | 136 | 136 |
| 52 | HELM 全面语言模型评测【论文精读·50】 | [BV1z24y1B7uX](danmaku/BV1z24y1B7uX.md) | 271 | 89 | 89 |
| 53 | I3D 论文精读【论文精读】 | [BV1tY4y1p7hq](danmaku/BV1tY4y1p7hq.md) | 269 | 109 | 109 |
| 54 | 环境安装，BERT、GPT、T5 性能测试，和横向对比【100亿模型计划】 | [BV1LT411F77M](danmaku/BV1LT411F77M.md) | 262 | 120 | 120 |
| 55 | 在讲 OpenAI Whisper 前先做了一个剪视频小工具【论文精读·44】 | [BV1Pe4y1t7de](danmaku/BV1Pe4y1t7de.md) | 260 | 78 | 78 |
| 56 | 如何判断（你自己的）研究工作的价值【论文精读】 | [BV1oL411c7Us](danmaku/BV1oL411c7Us.md) | 252 | 69 | 69 |
| 57 | 9.2 超参数优化【斯坦福21秋季：实用机器学习中文版】 | [BV1FM4y1c7yG](danmaku/BV1FM4y1c7yG.md) | 248 | 120 | 120 |
| 58 | Llama 3.1论文精读 · 2. 预训练数据【论文精读·54】 | [BV1u142187S5](danmaku/BV1u142187S5.md) | 243 | 82 | 82 |
| 59 | GPipe论文精读【论文精读】 | [BV1v34y1E7zu](danmaku/BV1v34y1E7zu.md) | 232 | 101 | 101 |
| 60 | 11.1 迁移学习【斯坦福21秋季：实用机器学习中文版】 | [BV1SL4y1t7ZL](danmaku/BV1SL4y1t7ZL.md) | 232 | 75 | 75 |
| 61 | 3.2 最简单也最常用的决策树【斯坦福21秋季：实用机器学习中文版】 | [BV17u411f7dt](danmaku/BV17u411f7dt.md) | 231 | 85 | 85 |
| 62 | Megatron LM 论文精读【论文精读】 | [BV1nB4y1R7Yz](danmaku/BV1nB4y1R7Yz.md) | 220 | 100 | 100 |
| 63 | 明白问题的重要性【研究的艺术·二】 | [BV11S4y1v7S2](danmaku/BV11S4y1v7S2.md) | 213 | 50 | 50 |
| 64 | 9.1 模型调参【斯坦福21秋季：实用机器学习中文版】 | [BV1vQ4y1e7LF](danmaku/BV1vQ4y1e7LF.md) | 208 | 83 | 83 |
| 65 | 视频理解论文串讲（上）【论文精读】 | [BV1fL4y157yA](danmaku/BV1fL4y157yA.md) | 203 | 74 | 74 |
| 66 | 2.3 数据变换【斯坦福21秋季：实用机器学习中文版】 | [BV1pQ4y167ej](danmaku/BV1pQ4y167ej.md) | 201 | 58 | 58 |
| 67 | Neural Corpus Indexer 文档检索【论文精读·47】 | [BV1Se411w7Sn](danmaku/BV1Se411w7Sn.md) | 199 | 76 | 76 |
| 68 | 5.4 Stacking【斯坦福21秋季：实用机器学习中文版】 | [BV1PZ4y197CX](danmaku/BV1PZ4y197CX.md) | 197 | 93 | 93 |
| 69 | 4.1 模型评估【斯坦福21秋季：实用机器学习中文版】 | [BV1tQ4y1S7Ty](danmaku/BV1tQ4y1S7Ty.md) | 195 | 91 | 91 |
| 70 | 2.4 特征工程【斯坦福21秋季：实用机器学习中文版】 | [BV1t44y1x7Hw](danmaku/BV1t44y1x7Hw.md) | 191 | 78 | 78 |
| 71 | 如何找研究想法 1【论文精读】 | [BV1qq4y1z7F2](danmaku/BV1qq4y1z7F2.md) | 185 | 81 | 81 |
| 72 | 视频生成·上【论文精读·55】 | [BV1VdcxesEAt](danmaku/BV1VdcxesEAt.md) | 184 | 65 | 65 |
| 73 | Zero 论文精读【论文精读】 | [BV1tY411g7ZT](danmaku/BV1tY411g7ZT.md) | 159 | 71 | 71 |
| 74 | 5.1 方差和偏差【斯坦福21秋季：实用机器学习中文版】 | [BV1H44y1v7Kf](danmaku/BV1H44y1v7Kf.md) | 155 | 75 | 75 |
| 75 | Llama 3.1论文精读 · 3. 模型【论文精读·54】 | [BV1Q4421Z7Tj](danmaku/BV1Q4421Z7Tj.md) | 154 | 85 | 85 |
| 76 | Llama 3.1论文精读 · 4. 训练infra【论文精读·54】 | [BV1b4421f7fa](danmaku/BV1b4421f7fa.md) | 149 | 55 | 55 |
| 77 | 3.6 卷积神经网络【斯坦福21秋季：实用机器学习中文版】 | [BV1m34y1m7TD](danmaku/BV1m34y1m7TD.md) | 147 | 77 | 77 |
| 78 | 单卡、多卡 BERT、GPT2 训练性能【100亿模型计划】 | [BV1fG411G7eH](danmaku/BV1fG411G7eH.md) | 143 | 56 | 56 |
| 79 | 3.3 最简单也同样最常用的线性模型【斯坦福21秋季：实用机器学习中文版】 | [BV1eh411b7ZW](danmaku/BV1eh411b7ZW.md) | 140 | 69 | 69 |
| 80 | 5.2 Bagging【斯坦福21秋季：实用机器学习中文版】 | [BV13g411N7xy](danmaku/BV13g411N7xy.md) | 139 | 63 | 63 |
| 81 | 4.3 模型验证【斯坦福21秋季：实用机器学习中文版】 | [BV1Dh411x7hZ](danmaku/BV1Dh411x7hZ.md) | 136 | 60 | 60 |
| 82 | 3.7 循环神经网络【斯坦福21秋季：实用机器学习中文版】 | [BV1pq4y1r7zo](danmaku/BV1pq4y1r7zo.md) | 135 | 70 | 70 |
| 83 | 4.2 过拟合和欠拟合【斯坦福21秋季：实用机器学习中文版】 | [BV1ah411t7Pp](danmaku/BV1ah411t7Pp.md) | 133 | 47 | 47 |
| 84 | 使用 AWS 最便宜的 GPU 实例 - 动手学深度学习v2 | [BV1MA411L78X](danmaku/BV1MA411L78X.md) | 133 | 64 | 64 |
| 85 | DeepMind AlphaCode 论文精读【论文精读】 | [BV1ab4y1s7rc](danmaku/BV1ab4y1s7rc.md) | 132 | 56 | 56 |
| 86 | 2.2 数据清理【斯坦福21秋季：实用机器学习中文版】 | [BV1kQ4y1Q7mx](danmaku/BV1kQ4y1Q7mx.md) | 117 | 43 | 43 |
| 87 | 3.4 随机梯度下降【斯坦福21秋季：实用机器学习中文版】 | [BV1234y1m75j](danmaku/BV1234y1m75j.md) | 110 | 55 | 55 |
| 88 | 3.5 多层感知机【斯坦福21秋季：实用机器学习中文版】 | [BV1ST4y1R7uC](danmaku/BV1ST4y1R7uC.md) | 98 | 44 | 44 |
| 89 | 5.3 Boosting【斯坦福21秋季：实用机器学习中文版】 | [BV1aM4y1P7z9](danmaku/BV1aM4y1P7z9.md) | 96 | 52 | 52 |
| 90 | 10.1 深度神经网络架构【斯坦福21秋季：实用机器学习中文版】 | [BV1WY411p7Zp](danmaku/BV1WY411p7Zp.md) | 89 | 35 | 35 |
| 91 | 讲好故事、论点【研究的艺术·三】 | [BV1WB4y1v7ST](danmaku/BV1WB4y1v7ST.md) | 81 | 26 | 26 |
| 92 | 理由、论据和担保【研究的艺术·四】 | [BV1SB4y1a75c](danmaku/BV1SB4y1a75c.md) | 77 | 17 | 17 |
| 93 | 10行代码战胜90%数据科学家？ | [BV1rh411m7Hb](danmaku/BV1rh411m7Hb.md) | 76 | 33 | 33 |
| 94 | 9.3 网络架构搜索【斯坦福21秋季：实用机器学习中文版】 | [BV1gP4y1H7Rd](danmaku/BV1gP4y1H7Rd.md) | 76 | 33 | 33 |
| 95 | 11.2 NLP中的微调【斯坦福21秋季：实用机器学习中文版】 | [BV1bq4y1y7tg](danmaku/BV1bq4y1y7tg.md) | 75 | 32 | 32 |
| 96 | 做了个实时数字人，水平吊打我自己 | [BV1pB586fEap](danmaku/BV1pB586fEap.md) | 70 | 14 | 14 |
| 97 | 3.1 8分钟机器学习介绍【斯坦福21秋季：实用机器学习中文版】 | [BV1Nv411u7bW](danmaku/BV1Nv411u7bW.md) | 60 | 26 | 26 |
| 98 | AutoGluon背后的技术 | [BV1F84y1F7Ps](danmaku/BV1F84y1F7Ps.md) | 58 | 19 | 19 |
| 99 | Llama 3.1论文精读 · 5. 模型训练过程【论文精读·54】 | [BV1c8HbeaEXi](danmaku/BV1c8HbeaEXi.md) | 50 | 17 | 17 |
| 100 | AlphaFold2论文精读预告【论文精读】 | [BV1Eu411U7Te](danmaku/BV1Eu411U7Te.md) | 46 | 14 | 14 |
| 101 | 视频生成·下：模型和训练【论文精读·55】 | [BV1U65SzuE4p](danmaku/BV1U65SzuE4p.md) | 43 | 14 | 14 |
| 102 | 2.5 数据科学家的日常【斯坦福21秋季：实用机器学习中文版】 | [BV1KL411G7BX](danmaku/BV1KL411G7BX.md) | 42 | 14 | 14 |
| 103 | 古法做视频里加一点点科技 | [BV1ScKR6QEQF](danmaku/BV1ScKR6QEQF.md) | 32 | 1 | 1 |
| 104 | 立个flag，续更【100亿模型计划】 | [BV1aCgMzHELG](danmaku/BV1aCgMzHELG.md) | 22 | 3 | 3 |
| 105 | Windows 上安装和使用 AutoGluon v0.4 | [BV1yL4y177hH](danmaku/BV1yL4y177hH.md) | 16 | 8 | 8 |
| 106 | 能跟你对话的TTS【开源】 | [BV1RfEw6LEfF](danmaku/BV1RfEw6LEfF.md) | 2 | 1 | 1 |

---
*2026-10-12 快照。弹幕版权归发送者所有，此处仅作学习索引与观点汇总。*