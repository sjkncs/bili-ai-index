# AI 论文精读

> Source: **VALSE_Webinar, deep_thoughts, 读论文的麦小哲, 秋刀鱼的炼丹工坊, 同济子豪兄, 先进编译实验室, OpenMMLab, 五道口纳什, ZOMI酱, 海安雨** - Snapshot: **2026-10-13** - **2584** episodes.
> Data: [`items.json`](items.json)

## Data source / method / limits

**Data source**: `seasons_archives_list` for the episode list; `x/web-interface/view`
per video for its **`desc`** field.

**Method**: descriptions follow `[paper share] <full title> (<venue>) - <cn summary>`;
venue parsing is nesting-aware (handles `SE(3)` and nested conference parentheses).

**Limits**: the `paper` column comes from the **description**, because Bilibili
truncates video **titles** at 80 chars; missing venue/arXiv stays empty; index only.

## All 2584 episodes

| # | paper | venue | category | arXiv | resources | length | B station |
|---:|---|---|---|---|---|---:|---|
| 1 | 【VALSE2025】0606 顾实《APR：脑启发与认知计算》 | - | AI 论文精读 | - | - | 15:29 | [link](https://www.bilibili.com/video/BV1SGu4zaEeb) |
| 2 | 【VALSE2025】0606 叶茫《APR：大模型安全与伦理》 | - | AI 论文精读 | - | - | 15:36 | [link](https://www.bilibili.com/video/BV18Gu4zaEqp) |
| 3 | 【VALSE2025】0606 谢伟迪《APR：医疗通用大模型》 | - | AI 论文精读 | - | - | 17:10 | [link](https://www.bilibili.com/video/BV18Gu4zaEcj) |
| 4 | 【VALSE2025】0606 张兆翔《APR：世界模型理论与框架》 | - | AI 论文精读 | - | - | 17:47 | [link](https://www.bilibili.com/video/BV1YnuWzbEQi) |
| 5 | 【VALSE2025】0606 袁粒《APR：视频生成基础模型》 | - | AI 论文精读 | - | - | 16:20 | [link](https://www.bilibili.com/video/BV16NuWzzEJP) |
| 6 | 【VALSE2025】0606 俞扬《大会主旨报告：大模型背景下的强化学习》 | - | AI 论文精读 | - | - | 32:05 | [link](https://www.bilibili.com/video/BV1u2ptzNEHf) |
| 7 | 【VALSE2025】0606 白翔《大会主旨报告：迈向通用文字识别：文档智能模型的进展与趋势》 | - | AI 论文精读 | - | - | 32:09 | [link](https://www.bilibili.com/video/BV1PUpWz7EDh) |
| 8 | 【VALSE2025】0606 程明明《大会主旨报告：高效视觉感知与个性化生成》 | - | AI 论文精读 | - | - | 23:24 | [link](https://www.bilibili.com/video/BV1fZpWzgEQz) |
| 9 | 【VALSE2025】0608 马月昕《Workshop5：大场景多对象的重建与生成》 | - | AI 论文精读 | - | - | 32:31 | [link](https://www.bilibili.com/video/BV1ha4qzgEsh) |
| 10 | 【VALSE2025】0608 王程《Workshop5：大场景多对象的重建与生成》 | - | AI 论文精读 | - | - | 23:25 | [link](https://www.bilibili.com/video/BV18a4qzgEQg) |
| 11 | 【VALSE2025】0608 窦志扬《Workshop20：优秀学生论坛》 | - | AI 论文精读 | - | - | 12:38 | [link](https://www.bilibili.com/video/BV1ab4qzGEZf) |
| 12 | 【VALSE2025】0608 黄文柯《Workshop20：优秀学生论坛》 | - | AI 论文精读 | - | - | 9:13 | [link](https://www.bilibili.com/video/BV1Xb4qzGE4Z) |
| 13 | 【VALSE2025】0608 卫雅珂《Workshop20：优秀学生论坛》 | - | AI 论文精读 | - | - | 6:48 | [link](https://www.bilibili.com/video/BV16V4qzpEL7) |
| 14 | 【VALSE2025】0608 倪旻恒《Workshop20：优秀学生论坛》 | - | AI 论文精读 | - | - | 8:34 | [link](https://www.bilibili.com/video/BV16V4qzpEJF) |
| 15 | 【VALSE2025】0608 王健伊《Workshop20：优秀学生论坛》 | - | AI 论文精读 | - | - | 9:13 | [link](https://www.bilibili.com/video/BV1FV4qzWEed) |
| 16 | 【VALSE2025】0608 刘世隆《Workshop20：优秀学生论坛》 | - | AI 论文精读 | - | - | 4:50 | [link](https://www.bilibili.com/video/BV1FV4qzWECs) |
| 17 | 【VALSE2025】0608 刘欣鹏《Workshop20：优秀学生论坛》 | - | AI 论文精读 | - | - | 9:01 | [link](https://www.bilibili.com/video/BV1FV4qzWESa) |
| 18 | 【VALSE2025】0608 陈科研《Workshop20：优秀学生论坛》 | - | AI 论文精读 | - | - | 4:35 | [link](https://www.bilibili.com/video/BV1nV4qzWEju) |
| 19 | 【VALSE2025】0608 姚江超《Tutorial 4：可信机器学习》 | - | AI 论文精读 | - | - | 60:48 | [link](https://www.bilibili.com/video/BV12E4mzfEpb) |
| 20 | 【VALSE2025】0608 张杰《Tutorial 4：可信机器学习》 | - | AI 论文精读 | - | - | 66:58 | [link](https://www.bilibili.com/video/BV1KJ4mzFECJ) |
| 21 | 【VALSE2025】0608 韩波《Tutorial 4：可信机器学习》 | - | AI 论文精读 | - | - | 69:48 | [link](https://www.bilibili.com/video/BV1RP4mzgE3d) |
| 22 | 【VALSE2025】0608 张严浩《Workshop6：视觉通用模型》 | - | AI 论文精读 | - | - | 14:02 | [link](https://www.bilibili.com/video/BV1tsn2zLEch) |
| 23 | 【VALSE2025】0608 王栋《Workshop6：视觉通用模型》 | - | AI 论文精读 | - | - | 22:26 | [link](https://www.bilibili.com/video/BV1Txn2zyEPb) |
| 24 | 【VALSE2025】0608 王兴刚《Workshop6：视觉通用模型》 | - | AI 论文精读 | - | - | 35:50 | [link](https://www.bilibili.com/video/BV1dun2zsEKg) |
| 25 | 【VALSE2025】0608 代季峰《Workshop6：视觉通用模型》 | - | AI 论文精读 | - | - | 24:27 | [link](https://www.bilibili.com/video/BV1QLn2znEth) |
| 26 | 【VALSE2025】0608 陈隆《Workshop6：视觉通用模型》 | - | AI 论文精读 | - | - | 34:01 | [link](https://www.bilibili.com/video/BV1YRn2z9EYY) |
| 27 | 【VALSE2025】0607 谢琦《Tutorial3：深度学习网络架构设计》 | - | AI 论文精读 | - | - | 106:32 | [link](https://www.bilibili.com/video/BV1yMn1zTEej) |
| 28 | 【VALSE2025】0607 黄高《Tutorial3：深度学习网络架构设计》 | - | AI 论文精读 | - | - | 104:51 | [link](https://www.bilibili.com/video/BV1n7n1zcEhi) |
| 29 | 【VALSE2025】0607 董胤蓬《Workshop17：人工智能大模型安全》 | - | AI 论文精读 | - | - | 22:28 | [link](https://www.bilibili.com/video/BV1ENnqzTEeG) |
| 30 | 【VALSE2025】0607 周文柏《Workshop17：人工智能大模型安全》 | - | AI 论文精读 | - | - | 40:35 | [link](https://www.bilibili.com/video/BV1sDniz2EZs) |
| 31 | 【VALSE2025】0607 郭青《Workshop17：人工智能大模型安全》 | - | AI 论文精读 | - | - | 25:09 | [link](https://www.bilibili.com/video/BV1xDniz2Eem) |
| 32 | 【VALSE2025】0607 韦星星《Workshop17：人工智能大模型安全》 | - | AI 论文精读 | - | - | 24:09 | [link](https://www.bilibili.com/video/BV1N7Hcz7EHJ) |
| 33 | 【VALSE2025】0607 蔺琛皓《Workshop17：人工智能大模型安全》 | - | AI 论文精读 | - | - | 30:14 | [link](https://www.bilibili.com/video/BV1P7HczjEWZ) |
| 34 | 【VALSE2025】0607 王珂尧《Workshop17：人工智能大模型安全》 | - | AI 论文精读 | - | - | 8:08 | [link](https://www.bilibili.com/video/BV1N5HczEEaq) |
| 35 | 【VALSE2025】0607 朱翔昱《Workshop9：生物特征识别遇上AI+Science》 | - | AI 论文精读 | - | - | 50:07 | [link](https://www.bilibili.com/video/BV1gXn9zuEvZ) |
| 36 | 【VALSE2025】0607 刘宁《Workshop9：生物特征识别遇上AI+Science》 | - | AI 论文精读 | - | - | 32:38 | [link](https://www.bilibili.com/video/BV1nhn9zWEbT) |
| 37 | 【VALSE2025】0607 李晓白《Workshop9：生物特征识别遇上AI+Science》 | - | AI 论文精读 | - | - | 78:26 | [link](https://www.bilibili.com/video/BV1Hhn9zWEtV) |
| 38 | 【VALSE2025】0607 常乐《Workshop9：生物特征识别遇上AI+Science》 | - | AI 论文精读 | - | - | 34:10 | [link](https://www.bilibili.com/video/BV1Hbn9zREMC) |
| 39 | 【VALSE2025】0607 郑钰辉《Workshop1：多模态遥感通用模型》 | - | AI 论文精读 | - | - | 25:37 | [link](https://www.bilibili.com/video/BV15tnRzLE5o) |
| 40 | 【VALSE2025】0607 王正《Workshop7：多模态认知计算》 | - | AI 论文精读 | - | - | 36:46 | [link](https://www.bilibili.com/video/BV1vHnXzrE75) |
| 41 | 【VALSE2025】0607 沈为《Workshop7：多模态认知计算》 | - | AI 论文精读 | - | - | 29:02 | [link](https://www.bilibili.com/video/BV1RHnXz6EgJ) |
| 42 | 【VALSE2025】0607 魏云超《Workshop7：多模态认知计算》 | - | AI 论文精读 | - | - | 31:51 | [link](https://www.bilibili.com/video/BV1RHnXz6EGG) |
| 43 | 【VALSE2025】0607 张勇《Workshop7：多模态认知计算》 | - | AI 论文精读 | - | - | 10:21 | [link](https://www.bilibili.com/video/BV1LHnXzrEMP) |
| 44 | 【VALSE2025】0607 梁小丹《Workshop7：多模态认知计算》谢洪涛 | - | AI 论文精读 | - | - | 34:25 | [link](https://www.bilibili.com/video/BV1RHnXz6EFn) |
| 45 | 【VALSE2025】0607 梁小丹《Workshop7：多模态认知计算》 | - | AI 论文精读 | - | - | 26:38 | [link](https://www.bilibili.com/video/BV1eWnXzgEjc) |
| 46 | 【VALSE2025】0607 徐文超《Workshop7：多模态认知计算》 | - | AI 论文精读 | - | - | 25:31 | [link](https://www.bilibili.com/video/BV1ZonXz2EJU) |
| 47 | 【VALSE2025】0607 孙浩《Tutorial2：科学智能（AI for Science）》 | - | AI 论文精读 | - | - | 93:04 | [link](https://www.bilibili.com/video/BV1yKn3z6EQX) |
| 48 | 【VALSE2025】0607 陈键飞《Tutorial1：大模型基础理论结构与微调》 | - | AI 论文精读 | - | - | 116:36 | [link](https://www.bilibili.com/video/BV1q8n4zgECU) |
| 49 | 【VALSE2025】0607 岳翔宇《Workshop12：AI4Science，诺贝尔奖后的思考》 | - | AI 论文精读 | - | - | 31:35 | [link](https://www.bilibili.com/video/BV178n4zgE6U) |
| 50 | 【VALSE2025】0607 王笑楠《Workshop12：AI4Science，诺贝尔奖后的思考》 | - | AI 论文精读 | - | - | 29:51 | [link](https://www.bilibili.com/video/BV1Ndn4zpE8v) |
| 51 | 【VALSE2025】0607 王立威《Tutorial1：大模型基础理论结构与微调》 | - | AI 论文精读 | - | - | 69:59 | [link](https://www.bilibili.com/video/BV11dn4zHExR) |
| 52 | 【VALSE2025】0607 朱霖潮《Workshop12：AI4Science，诺贝尔奖后的思考》 | - | AI 论文精读 | - | - | 27:18 | [link](https://www.bilibili.com/video/BV1cNntzjEGy) |
| 53 | 【VALSE2025】0607 邵斌《Workshop12：AI4Science，诺贝尔奖后的思考》 | - | AI 论文精读 | - | - | 32:15 | [link](https://www.bilibili.com/video/BV1S2n4ztErt) |
| 54 | 【VALSE2025】0607 吴保东《Workshop12：AI4Science，诺贝尔奖后的思考》 | - | AI 论文精读 | - | - | 9:31 | [link](https://www.bilibili.com/video/BV1mSn4zxEbo) |
| 55 | 【VALSE2025】0607 张奇《Workshop13：大模型基础理论-从理论视角看待大模型技术发展》 | - | AI 论文精读 | - | - | 33:13 | [link](https://www.bilibili.com/video/BV1hNJRzTEcK) |
| 56 | 【VALSE2025】0607 方聪《Workshop13：大模型基础理论-从理论视角看待大模型技术发展》 | - | AI 论文精读 | - | - | 39:14 | [link](https://www.bilibili.com/video/BV18KJRziEL8) |
| 57 | 【VALSE2025】0607 黄维然《Workshop13：大模型基础理论-从理论视角看待大模型技术发展》 | - | AI 论文精读 | - | - | 36:34 | [link](https://www.bilibili.com/video/BV1uKJRziE1b) |
| 58 | 【VALSE2025】0607 龚铁梁《Workshop13：大模型基础理论-从理论视角看待大模型技术发展》 | - | AI 论文精读 | - | - | 28:04 | [link](https://www.bilibili.com/video/BV1hKJRziEPp) |
| 59 | 【VALSE2025】0607 蒋宁《Workshop13：大模型基础理论-从理论视角看待大模型技术发展》 | - | AI 论文精读 | - | - | 10:23 | [link](https://www.bilibili.com/video/BV1uKJRziEd5) |
| 60 | 【VALSE2025】0607 车万翔《Workshop13：大模型基础理论-从理论视角看待大模型技术发展》 | - | AI 论文精读 | - | - | 35:33 | [link](https://www.bilibili.com/video/BV1uKJRziEUa) |
| 61 | 【VALSE2025】0607 石野《Workshop10：基于生成式AI驱动的具身智能》 | - | AI 论文精读 | - | - | 41:03 | [link](https://www.bilibili.com/video/BV14XJCzvESS) |
| 62 | 【VALSE2025】0607 穆尧《Workshop10：基于生成式AI驱动的具身智能》 | - | AI 论文精读 | - | - | 36:10 | [link](https://www.bilibili.com/video/BV14XJCzvERJ) |
| 63 | 【VALSE2025】0607 盛律《Workshop10：基于生成式AI驱动的具身智能》 | - | AI 论文精读 | - | - | 33:24 | [link](https://www.bilibili.com/video/BV1h2JCzzEGd) |
| 64 | 【VALSE2025】0607 张直政《Workshop10：基于生成式AI驱动的具身智能》 | - | AI 论文精读 | - | - | 40:35 | [link](https://www.bilibili.com/video/BV182JCzzE4V) |
| 65 | 【VALSE2023】0610 高文《特征编码与数字视网膜》 | - | AI 论文精读 | - | - | 39:11 | [link](https://www.bilibili.com/video/BV1iV411579w) |
| 66 | 【VALSE2023】0610 陈熙霖 《计算机视觉-从孤立到系统性方法》 | - | AI 论文精读 | - | - | 27:26 | [link](https://www.bilibili.com/video/BV1n14y1B7x6) |
| 67 | 【VALSE2023】0610 吴建鑫《神经网络模型轻量化设计》 | - | AI 论文精读 | - | - | 15:03 | [link](https://www.bilibili.com/video/BV1Fu4y1174x) |
| 68 | 【VALSE2023】0610 刘烨斌《基于NeRF的三维视觉年度进展报告》 | - | AI 论文精读 | - | - | 13:54 | [link](https://www.bilibili.com/video/BV16x4y1X7WG) |
| 69 | 【VALSE2023】0610 张兆翔《类脑智能》 | - | AI 论文精读 | - | - | 15:41 | [link](https://www.bilibili.com/video/BV1Pk4y1G7zj) |
| 70 | 【VALSE2023】0610 夏勇《医学影像智能分析年度进展》 | - | AI 论文精读 | - | - | 15:19 | [link](https://www.bilibili.com/video/BV1Bj411r7Ex) |
| 71 | 【VALSE2023】0610 朱军《扩散概率模型的前沿进展》 | - | AI 论文精读 | - | - | 28:31 | [link](https://www.bilibili.com/video/BV1Rh4y1C7T7) |
| 72 | 【VALSE2023】0610 章国锋《基于隐式神经表示的三维重建、渲染与定位》 | - | AI 论文精读 | - | - | 25:10 | [link](https://www.bilibili.com/video/BV1H94y1C7mL) |
| 73 | 【VALSE2023】0610 刘偲《开放视觉感知》 | - | AI 论文精读 | - | - | 24:19 | [link](https://www.bilibili.com/video/BV1pM4y1p75v) |
| 74 | 【VALSE2023】0610 侯淇彬《开放域目标检测与识别年度进展》 | - | AI 论文精读 | - | - | 14:12 | [link](https://www.bilibili.com/video/BV1Yz4y1s7wC) |
| 75 | 【VALSE2023】0610 王利民《视频动作分析与识别》 | - | AI 论文精读 | - | - | 14:28 | [link](https://www.bilibili.com/video/BV1Uz4y1s76K) |
| 76 | 【VALSE2023】0610 胡瀚《视觉自监督学习年度进展评述》 | - | AI 论文精读 | - | - | 14:46 | [link](https://www.bilibili.com/video/BV1J44y1w79r) |
| 77 | 【VALSE2023】0610 程塨《遥感目标检测》 | - | AI 论文精读 | - | - | 12:44 | [link](https://www.bilibili.com/video/BV1D14y1i7wW) |
| 78 | 【VALSE2023】0610 邓伟洪《人脸感知计算年度进展报告》 | - | AI 论文精读 | - | - | 13:54 | [link](https://www.bilibili.com/video/BV12z4y1p7cr) |
| 79 | 【VALSE2023】0610 邓成/杨二昆《多模态融合感知年度进展综述》 | - | AI 论文精读 | - | - | 15:11 | [link](https://www.bilibili.com/video/BV1YP411t73r) |
| 80 | 【VALSE2023】0610 魏哲巍《图表示学习》 | - | AI 论文精读 | - | - | 13:04 | [link](https://www.bilibili.com/video/BV1244y1w7YT) |
| 81 | 【VALSE2023】0610 刘成林《文档智能：最新进展与趋势》 | - | AI 论文精读 | - | - | 15:14 | [link](https://www.bilibili.com/video/BV1FV4y1v7W6) |
| 82 | 【VALSE2023】0611 吴思《Tutorial ：计算神经科学-上》 | - | AI 论文精读 | - | - | 77:36 | [link](https://www.bilibili.com/video/BV1dj411r73d) |
| 83 | 【VALSE2023】0611 吴思《Tutorial ：计算神经科学-下》 | - | AI 论文精读 | - | - | 96:12 | [link](https://www.bilibili.com/video/BV1fu411J7jb) |
| 84 | 【VALSE2023】0611《Workshop：目标检测与分割-上》 | - | AI 论文精读 | - | - | 52:17 | [link](https://www.bilibili.com/video/BV1N8411o72f) |
| 85 | 【VALSE2023】0611《Workshop：目标检测与分割-下》 | - | AI 论文精读 | - | - | 115:20 | [link](https://www.bilibili.com/video/BV1fX4y177r8) |
| 86 | 【VALSE2023】0611《Workshop ：视觉知识和多重知识表达》 | - | AI 论文精读 | - | - | 106:37 | [link](https://www.bilibili.com/video/BV1dh4y1r7nX) |
| 87 | 【VALSE2023】0611《Workshop ：围绕手机的计算影像学》 | - | AI 论文精读 | - | - | 164:59 | [link](https://www.bilibili.com/video/BV1j94y1y76C) |
| 88 | 【VALSE2023】0611《Workshop ：机器人具身智能》 | - | AI 论文精读 | - | - | 115:38 | [link](https://www.bilibili.com/video/BV1L8411R7f7) |
| 89 | 【VALSE2023】0611《Tutorial：从Transformer到GPT》 | - | AI 论文精读 | - | - | 204:49 | [link](https://www.bilibili.com/video/BV1AV4y1v7xw) |
| 90 | 【VALSE2023】0611《Workshop：混合现实中的视觉与学习技术》 | - | AI 论文精读 | - | - | 169:57 | [link](https://www.bilibili.com/video/BV1Du4y1B7zE) |
| 91 | 【VALSE2023】0611《Workshop：物联网与工业应用》 | - | AI 论文精读 | - | - | 161:56 | [link](https://www.bilibili.com/video/BV16u4y1R7aJ) |
| 92 | 【VALSE2023】0611《Workshop ：女性研究者论坛》 | - | AI 论文精读 | - | - | 183:12 | [link](https://www.bilibili.com/video/BV1o14y1i7hs) |
| 93 | 【VALSE2023】0612《Workshop：多模态大模型与提示学习》 | - | AI 论文精读 | - | - | 152:49 | [link](https://www.bilibili.com/video/BV1WV41137is) |
| 94 | 【VALSE2023】0612《Workshop：三维视觉技术前沿》 | - | AI 论文精读 | - | - | 191:46 | [link](https://www.bilibili.com/video/BV1j44y1c7Yd) |
| 95 | 【VALSE2023】0612《Workshop：大模型背景下的自动驾驶与车路协同》 | - | AI 论文精读 | - | - | 170:22 | [link](https://www.bilibili.com/video/BV1nN41187mk) |
| 96 | 【VALSE2023】0612《Workshop：人工智能与科学计算》 | - | AI 论文精读 | - | - | 154:35 | [link](https://www.bilibili.com/video/BV1gF411Z7v2) |
| 97 | 【VALSE2023】0612《Workshop：语言文字识别与理解》 | - | AI 论文精读 | - | - | 194:34 | [link](https://www.bilibili.com/video/BV1LX4y1j7HM) |
| 98 | 【VALSE2023】0612《Workshop：自监督视觉表征学习》 | - | AI 论文精读 | - | - | 182:24 | [link](https://www.bilibili.com/video/BV1gm4y1p7yW) |
| 99 | 【VALSE2023】0612《Workshop：遥感影像解译》 | - | AI 论文精读 | - | - | 192:28 | [link](https://www.bilibili.com/video/BV1yu4y1R7f6) |
| 100 | 【VALSE2023】0612《Workshop：优秀学生论坛》 | - | AI 论文精读 | - | - | 109:21 | [link](https://www.bilibili.com/video/BV1pN41187Xf) |
| 101 | 【VALSE2023】0612《Workshop：多模态认知计算》 | - | AI 论文精读 | - | - | 208:59 | [link](https://www.bilibili.com/video/BV1bj411z7nD) |
| 102 | 【VALSE2023】0611《Workshop ：ChatGPT 与计算机视觉》 | - | AI 论文精读 | - | - | 104:06 | [link](https://www.bilibili.com/video/BV1m14y1v74v) |
| 103 | 【VALSE2023】0611《Workshop ：大模型对 CV/PR 的挑战与机会》 | - | AI 论文精读 | - | - | 127:40 | [link](https://www.bilibili.com/video/BV1C14y1v7CP) |
| 104 | 【VALSE2024】0507《Workshop ：多模态感知与对话》 | - | AI 论文精读 | - | - | 65:56 | [link](https://www.bilibili.com/video/BV1CU411o77f) |
| 105 | 【VALSE2024】0507《Workshop ：遥感图像智能解译论坛》 | - | AI 论文精读 | - | - | 205:09 | [link](https://www.bilibili.com/video/BV1D7421f7kx) |
| 106 | 【VALSE2024】0507《Workshop ：端到端自动驾驶》 | - | AI 论文精读 | - | - | 31:46 | [link](https://www.bilibili.com/video/BV13b421q7Vx) |
| 107 | 【VALSE2024】0507《Workshop ：多模态大模型》 | - | AI 论文精读 | - | - | 94:09 | [link](https://www.bilibili.com/video/BV11M4m1k7ba) |
| 108 | 【VALSE2024】0507《Workshop ：脑启发的视觉与学习》 | - | AI 论文精读 | - | - | 146:16 | [link](https://www.bilibili.com/video/BV1gb421q7hM) |
| 109 | 【VALSE2024】0507《Workshop ：优秀学生论坛》 | - | AI 论文精读 | - | - | 202:02 | [link](https://www.bilibili.com/video/BV1Cf421R7xc) |
| 110 | 【VALSE2024】0506《Tutorial：开放词汇视觉感知论坛》 | - | AI 论文精读 | - | - | 207:10 | [link](https://www.bilibili.com/video/BV1uf421d7Vk) |
| 111 | 【VALSE2024】0506《Workshop ：面向移动端的AI图像增强》 | - | AI 论文精读 | - | - | 218:48 | [link](https://www.bilibili.com/video/BV1gZ421x7fG) |
| 112 | 【VALSE2024】0506《Workshop ：三维重建与生成》 | - | AI 论文精读 | - | - | 204:51 | [link](https://www.bilibili.com/video/BV1DD421G7ws) |
| 113 | 【VALSE2024】0506《Workshop ：大模型赋能智慧医疗》 | - | AI 论文精读 | - | - | 235:16 | [link](https://www.bilibili.com/video/BV14r42157TN) |
| 114 | 【VALSE2024】0506《Workshop ：具身智能的视觉与学习》 | - | AI 论文精读 | - | - | 231:06 | [link](https://www.bilibili.com/video/BV1Bw4m1U7du) |
| 115 | 【VALSE2024】0506《Workshop ：大模型理论与机理》 | - | AI 论文精读 | - | - | 136:01 | [link](https://www.bilibili.com/video/BV19f421R7we) |
| 116 | 【VALSE2024】0506《Workshop ：视觉大模型高效迁移》 | - | AI 论文精读 | - | - | 141:27 | [link](https://www.bilibili.com/video/BV1EM4m1k7w6) |
| 117 | 【VALSE2024】0505 李鸿升《特邀报告：图像生成和视频生成若干前沿技术探索》 | - | AI 论文精读 | - | - | 26:21 | [link](https://www.bilibili.com/video/BV161421i7QW) |
| 118 | 【VALSE2024】0505 严骏驰《APR：世界模型增强的自动驾驶》 | - | AI 论文精读 | - | - | 16:35 | [link](https://www.bilibili.com/video/BV1FD421V7A1) |
| 119 | 【VALSE2024】0505 吴小俊《特邀报告：多模态视觉融合方法：是否存在性能极限？》 | - | AI 论文精读 | - | - | 31:57 | [link](https://www.bilibili.com/video/BV1Ft421T74U) |
| 120 | 【VALSE2024】0505 杨易《特邀报告：混合模型驱动的内容生成与具身智能》 | - | AI 论文精读 | - | - | 31:07 | [link](https://www.bilibili.com/video/BV1ss421w7eq) |
| 121 | 【VALSE2024】0505 施柏鑫《APR：神经形态相机视觉计算》 | - | AI 论文精读 | - | - | 18:10 | [link](https://www.bilibili.com/video/BV1Js42137CA) |
| 122 | 【VALSE2024】0505 杨耀东《APR：从偏好对齐到价值对齐与超对齐》 | - | AI 论文精读 | - | - | 21:06 | [link](https://www.bilibili.com/video/BV1Qi421U7yb) |
| 123 | 【VALSE2024】0505 王兴刚《APR：面向大模型的新型高效率网络架构》 | - | AI 论文精读 | - | - | 16:17 | [link](https://www.bilibili.com/video/BV1Gt421T7Z4) |
| 124 | 【VALSE2024】0505 俞扬《APR：世界模型与具身决策》 | - | AI 论文精读 | - | - | 16:40 | [link](https://www.bilibili.com/video/BV1aT421S7T5) |
| 125 | 【VALSE2024】0505 马月昕《特邀报告：三维场景理解的前世、今生与未来》 | - | AI 论文精读 | - | - | 31:22 | [link](https://www.bilibili.com/video/BV1Ff421d7n4) |
| 126 | 【VALSE2024】0505 卢志武《APR：视频生成》 | - | AI 论文精读 | - | - | 16:11 | [link](https://www.bilibili.com/video/BV1eZ421s794) |
| 127 | 【VALSE2024】0505 赵恒爽《APR：视觉基础大模型》 | - | AI 论文精读 | - | - | 21:23 | [link](https://www.bilibili.com/video/BV1Rf421R715) |
| 128 | 【VALSE2024】0505 林倞《APR：面向具身智能的多模态感知与交互》 | - | AI 论文精读 | - | - | 17:00 | [link](https://www.bilibili.com/video/BV1BZ421s7LD) |
| 129 | 【VALSE2024】0505 高林《APR：三维高斯泼溅（3D Gaussian Splatting）》 | - | AI 论文精读 | - | - | 18:21 | [link](https://www.bilibili.com/video/BV11r421j7tV) |
| 130 | 【VALSE2024】0505 谢凌曦《APR：视觉通用人工智能》 | - | AI 论文精读 | - | - | 16:54 | [link](https://www.bilibili.com/video/BV1mD421G7zJ) |
| 131 | 【VALSE2024】0505 代季峰《APR：智能体视觉》 | - | AI 论文精读 | - | - | 14:44 | [link](https://www.bilibili.com/video/BV1eM4m1k7jY) |
| 132 | 【VALSE2024】0505 陈华钧《APR：符号知识和大模型》 | - | AI 论文精读 | - | - | 16:05 | [link](https://www.bilibili.com/video/BV1Hz421Y7LG) |
| 133 | 【VALSE2024】0505《2023-2024年度CV与ML领域重要学术进展》 | - | AI 论文精读 | - | - | 15:27 | [link](https://www.bilibili.com/video/BV1ex4y1H7gC) |
| 134 | 【VALSE2024】0507《Workshop ：异构联邦学习》 | - | AI 论文精读 | - | - | 52:34 | [link](https://www.bilibili.com/video/BV1rD421G76t) |
| 135 | 1、PyTorch介绍与张量的创建 | - | AI 论文精读 | - | - | 42:00 | [link](https://www.bilibili.com/video/BV1ov411M7xL) |
| 136 | 2、PyTorch张量的运算API（上） | - | AI 论文精读 | - | - | 32:06 | [link](https://www.bilibili.com/video/BV1wQ4y1q7Bm) |
| 137 | 3、PyTorch张量的运算API（下） | - | AI 论文精读 | - | - | 48:16 | [link](https://www.bilibili.com/video/BV1Hq4y1R7dM) |
| 138 | 4、PyTorch的Dataset与DataLoader详细使用教程 | - | AI 论文精读 | - | - | 35:30 | [link](https://www.bilibili.com/video/BV1yP4y1L7cC) |
| 139 | 5、深入剖析PyTorch DataLoader源码 | - | AI 论文精读 | - | - | 42:30 | [link](https://www.bilibili.com/video/BV1kq4y1G75V) |
| 140 | 6、PyTorch中搭建分类网络实例 | - | AI 论文精读 | - | - | 43:50 | [link](https://www.bilibili.com/video/BV1VF411a7oz) |
| 141 | 7、深入剖析PyTorch nn.Module源码 | - | AI 论文精读 | - | - | 73:10 | [link](https://www.bilibili.com/video/BV1ch411b7yP) |
| 142 | 8、深入剖析PyTorch的state_dict、parameters、modules源码 | - | AI 论文精读 | - | - | 49:53 | [link](https://www.bilibili.com/video/BV12g411K7oq) |
| 143 | 9、深入剖析PyTorch的nn.Sequential及ModuleList源码 | - | AI 论文精读 | - | - | 46:14 | [link](https://www.bilibili.com/video/BV1Cb4y187H1) |
| 144 | 10、PyTorch autograd使用教程 | - | AI 论文精读 | - | - | 31:05 | [link](https://www.bilibili.com/video/BV1vL411u7bL) |
| 145 | 11、PyTorch中如何进行向量微分、矩阵微分与计算雅克比行列式 | - | AI 论文精读 | - | - | 33:12 | [link](https://www.bilibili.com/video/BV1Xr4y1r7wa) |
| 146 | 12、如何在PyTorch中训练模型 | - | AI 论文精读 | - | - | 37:33 | [link](https://www.bilibili.com/video/BV1wL411g7rv) |
| 147 | 13、详细推导自动微分Forward与Reverse模式 | - | AI 论文精读 | - | - | 54:08 | [link](https://www.bilibili.com/video/BV1PF411h7Ew) |
| 148 | 14、保存与加载PyTorch训练的模型和超参数 | - | AI 论文精读 | - | - | 37:50 | [link](https://www.bilibili.com/video/BV1U341187TM) |
| 149 | 15、Dropout原理以及其TF/Torch/Numpy源码实现 | - | AI 论文精读 | - | - | 45:45 | [link](https://www.bilibili.com/video/BV1gL4y1p7ww) |
| 150 | 16、PyTorch中进行卷积残差模块算子融合 | - | AI 论文精读 | - | - | 74:04 | [link](https://www.bilibili.com/video/BV1sU4y1u7TM) |
| 151 | 17、ConvMixer模型原理及其PyTorch逐行实现 | - | AI 论文精读 | - | - | 44:43 | [link](https://www.bilibili.com/video/BV1K34y1o74P) |
| 152 | 18、深入剖析PyTorch中的Transformer API源码 | - | AI 论文精读 | - | - | 67:40 | [link](https://www.bilibili.com/video/BV1o44y1Y7cp) |
| 153 | 19、Transformer模型Encoder原理精讲及其PyTorch逐行实现 | - | AI 论文精读 | - | - | 110:37 | [link](https://www.bilibili.com/video/BV1cP4y1V7GF) |
| 154 | 20、Transformer模型Decoder原理精讲及其PyTorch逐行实现 | - | AI 论文精读 | - | - | 59:13 | [link](https://www.bilibili.com/video/BV1Qg411N74v) |
| 155 | 21、Transformer Masked loss原理精讲及其PyTorch逐行实现 | - | AI 论文精读 | - | - | 45:54 | [link](https://www.bilibili.com/video/BV1dh411s7FW) |
| 156 | 22、PyTorch nn.Conv2d卷积网络使用教程 | - | AI 论文精读 | - | - | 33:34 | [link](https://www.bilibili.com/video/BV1644y1h7LN) |
| 157 | 23、手写并验证滑动相乘实现PyTorch二维卷积 | - | AI 论文精读 | - | - | 52:44 | [link](https://www.bilibili.com/video/BV1dP4y137er) |
| 158 | 24、手写并验证向量内积实现PyTorch二维卷积 | - | AI 论文精读 | - | - | 58:21 | [link](https://www.bilibili.com/video/BV1Qb4y1i7n5) |
| 159 | 25、手写实现nn.TransposedConv转置卷积 | - | AI 论文精读 | - | - | 52:18 | [link](https://www.bilibili.com/video/BV1fM4y1F7j5) |
| 160 | 26、手写卷积与转置卷积的代码总结 | - | AI 论文精读 | - | - | 41:48 | [link](https://www.bilibili.com/video/BV13U4y1K7op) |
| 161 | 27、手写实现PyTorch的DilatedConv和GroupConv | - | AI 论文精读 | - | - | 59:41 | [link](https://www.bilibili.com/video/BV1UY411W7W8) |
| 162 | 28、Vision Transformer(ViT)模型原理及PyTorch逐行实现 | - | AI 论文精读 | - | - | 67:26 | [link](https://www.bilibili.com/video/BV1cS4y1M7wo) |
| 163 | 29、PyTorch RNN的原理及其手写复现 | - | AI 论文精读 | - | - | 90:48 | [link](https://www.bilibili.com/video/BV13i4y1R7jB) |
| 164 | 30、PyTorch LSTM和LSTMP的原理及其手写复现 | - | AI 论文精读 | - | - | 76:29 | [link](https://www.bilibili.com/video/BV1zq4y1m7aH) |
| 165 | 31、PyTorch GRU的原理及其手写复现 | - | AI 论文精读 | - | - | 39:18 | [link](https://www.bilibili.com/video/BV1jm4y1Q7uh) |
| 166 | 32、基于PyTorch的文本分类项目模型与训练代码讲解 | - | AI 论文精读 | - | - | 55:10 | [link](https://www.bilibili.com/video/BV1eD4y1F7o4) |
| 167 | 33、完整讲解PyTorch多GPU分布式训练代码编写 | - | AI 论文精读 | - | - | 74:56 | [link](https://www.bilibili.com/video/BV1xZ4y1S7dG) |
| 168 | 34、Swin Transformer论文精讲及其PyTorch逐行复现 | - | AI 论文精读 | - | - | 98:20 | [link](https://www.bilibili.com/video/BV1kF411v7vg) |
| 169 | 35、基于PyTorch手写Attention-based Seq2Seq模型 | - | AI 论文精读 | - | - | 37:41 | [link](https://www.bilibili.com/video/BV1ML411w7k7) |
| 170 | 36、PyTorch训练加速技巧与爱因斯坦标示法 | - | AI 论文精读 | - | - | 65:52 | [link](https://www.bilibili.com/video/BV1ZY411b78A) |
| 171 | 37、Word Embedding原理精讲及其PyTorch API教程讲解 | - | AI 论文精读 | - | - | 49:54 | [link](https://www.bilibili.com/video/BV1wm4y1o7o5) |
| 172 | 38、ConvNeXt论文导读与模型精讲 | - | AI 论文精读 | - | - | 49:22 | [link](https://www.bilibili.com/video/BV1iP4y1M7nk) |
| 173 | 39、ConvNeXt模型代码逐行讲解 | - | AI 论文精读 | - | - | 33:12 | [link](https://www.bilibili.com/video/BV11Y41137VA) |
| 174 | 40、ConvNeXt分布式训练代码逐行讲解 | - | AI 论文精读 | - | - | 40:37 | [link](https://www.bilibili.com/video/BV1uP4y1u7qd) |
| 175 | 41、ResNet模型精讲以及PyTorch复现逐行讲解 | - | AI 论文精读 | - | - | 61:32 | [link](https://www.bilibili.com/video/BV1K3411p764) |
| 176 | 42、Masked AutoEncoder(MAE)论文导读与模型详细介绍 | - | AI 论文精读 | - | - | 62:41 | [link](https://www.bilibili.com/video/BV1u94y1f7NH) |
| 177 | 43、逐行讲解Masked AutoEncoder(MAE)的PyTorch代码 | - | AI 论文精读 | - | - | 110:32 | [link](https://www.bilibili.com/video/BV1JS4y1N7XE) |
| 178 | 44、Layer Normalization论文导读与原理精讲 | - | AI 论文精读 | - | - | 72:06 | [link](https://www.bilibili.com/video/BV1Ma411i76P) |
| 179 | 45、五种归一化的原理与PyTorch逐行手写实现讲解(BatchNorm/LayerNorm/InsNorm/GroupNorm/WeightNorm) | - | AI 论文精读 | - | - | 71:29 | [link](https://www.bilibili.com/video/BV1Pq4y1a7pH) |
| 180 | 46、四种Position Embedding的原理与PyTorch手写逐行实现（Transformer/ViT/Swin-T/MAE） | - | AI 论文精读 | - | - | 63:49 | [link](https://www.bilibili.com/video/BV1DF411u7ST) |
| 181 | 47、GAN原理讲解与PyTorch手写逐行讲解 | - | AI 论文精读 | - | - | 93:31 | [link](https://www.bilibili.com/video/BV1VT4y1e796) |
| 182 | 48、快速复现PyTorch的Weight Normalization | - | AI 论文精读 | - | - | 19:07 | [link](https://www.bilibili.com/video/BV1NZ4y117VT) |
| 183 | 49、cGAN及LSGAN的原理与PyTorch手写逐行讲解 | - | AI 论文精读 | - | - | 49:07 | [link](https://www.bilibili.com/video/BV1444y1G7y2) |
| 184 | 50、NormalizingFlow(标准化流)论文导读与原理精讲 | - | AI 论文精读 | - | - | 65:16 | [link](https://www.bilibili.com/video/BV1dS4y1c7xB) |
| 185 | 51、基于PyTorch ResNet18的果蔬分类逐行代码讲解 | - | AI 论文精读 | - | - | 68:13 | [link](https://www.bilibili.com/video/BV1vZ4y1h7X9) |
| 186 | 52、Excel/Csv文件数据转成PyTorch张量导入模型代码逐行讲解 | - | AI 论文精读 | - | - | 26:29 | [link](https://www.bilibili.com/video/BV1nR4y1N7Vj) |
| 187 | 53、NormalizingFlow(标准化流)的PyTorch代码逐行讲解 | - | AI 论文精读 | - | - | 81:49 | [link](https://www.bilibili.com/video/BV1QF411j7ee) |
| 188 | 54、Probabilistic Diffusion Model概率扩散模型理论与完整PyTorch代码详细解读 | - | AI 论文精读 | - | - | 96:09 | [link](https://www.bilibili.com/video/BV1b541197HX) |
| 189 | 55、PyTorch的交叉熵、信息熵、二分类交叉熵、负对数似然、KL散度、余弦相似度的原理与代码讲解 | - | AI 论文精读 | - | - | 78:46 | [link](https://www.bilibili.com/video/BV1Sv4y1A7dz) |
| 190 | 56、U-Net用于图像分割以及人声伴奏分离原理代码讲解 | - | AI 论文精读 | - | - | 43:46 | [link](https://www.bilibili.com/video/BV1C54y1o77i) |
| 191 | 57、Autoregressive Diffusion Model自回归扩散模型用于序列预测论文讲解 | - | AI 论文精读 | - | - | 48:50 | [link](https://www.bilibili.com/video/BV1pZ4y1t7dc) |
| 192 | 58、Improved Diffusion的PyTorch代码逐行深入讲解 | - | AI 论文精读 | - | - | 146:58 | [link](https://www.bilibili.com/video/BV1sG411s7vV) |
| 193 | 59、基于CLIP/ViT模型搭建相似图像检索系统 | - | AI 论文精读 | - | - | 41:17 | [link](https://www.bilibili.com/video/BV1BB4y1a76V) |
| 194 | 60、基于cVAE+Flow+GAN的效果最好语音合成VITS模型论文精讲 | - | AI 论文精读 | - | - | 94:31 | [link](https://www.bilibili.com/video/BV1wU4y1q7po) |
| 195 | 61、基于cVAE+Flow+GAN的效果最好语音合成VITS模型代码逐行讲解 | - | AI 论文精读 | - | - | 195:46 | [link](https://www.bilibili.com/video/BV1VG411h75N) |
| 196 | 62、Score Diffusion Model分数扩散模型理论与完整PyTorch代码详细解读 | - | AI 论文精读 | - | - | 144:42 | [link](https://www.bilibili.com/video/BV1Dd4y1A7oz) |
| 197 | 63、必看！概率扩散模型(DDPM)与分数扩散模型(SMLD)的联系与区别 | - | AI 论文精读 | - | - | 46:36 | [link](https://www.bilibili.com/video/BV1QG4y1674Q) |
| 198 | 64、扩散模型加速采样算法DDIM论文精讲与PyTorch源码逐行解读 | - | AI 论文精读 | - | - | 129:54 | [link](https://www.bilibili.com/video/BV1JY4y1N7dn) |
| 199 | 65、【特别视频】AI教程评论区在线答疑之2022-10-25 | - | AI 论文精读 | - | - | 35:55 | [link](https://www.bilibili.com/video/BV1Wt4y1T7Nu) |
| 200 | 66、Classifier Guided Diffusion条件扩散模型论文与PyTorch代码详细解读 | - | AI 论文精读 | - | - | 90:27 | [link](https://www.bilibili.com/video/BV1m84y1e7hP) |
| 201 | 67、DiffusionLM 基于扩散模型的语言模型论文原理精讲 | - | AI 论文精读 | - | - | 56:30 | [link](https://www.bilibili.com/video/BV1zt4y1P7HN) |
| 202 | 68、VQVAE预训练模型的论文原理及PyTorch代码逐行讲解 | - | AI 论文精读 | - | - | 80:21 | [link](https://www.bilibili.com/video/BV14Y4y1X7wb) |
| 203 | 69、VQGAN+Transformer自回归建模图像生成的论文原理细致讲解 | - | AI 论文精读 | - | - | 66:53 | [link](https://www.bilibili.com/video/BV1mh411g7r5) |
| 204 | 70、VQGAN+GPT1自回归建模+采样部分的代码讲解 | - | AI 论文精读 | - | - | 51:16 | [link](https://www.bilibili.com/video/BV1uu4y1R7LV) |
| 205 | 71、VQGAN模型+VQ离散化模块的代码讲解 | - | AI 论文精读 | - | - | 50:34 | [link](https://www.bilibili.com/video/BV1cM411R7dY) |
| 206 | 72、爆火的GPT-2论文讲解 | - | AI 论文精读 | - | - | 50:32 | [link](https://www.bilibili.com/video/BV1Ma4y1R72i) |
| 207 | 73、爆火必看的nano-GPT2 Pytorch经典代码逐行讲解 | - | AI 论文精读 | - | - | 82:01 | [link](https://www.bilibili.com/video/BV11N4y1479K) |
| 208 | 74、GPT-3论文原理讲解 | - | AI 论文精读 | - | - | 53:18 | [link](https://www.bilibili.com/video/BV1CT4y1s7dx) |
| 209 | 75、Llama源码讲解之RoPE旋转位置编码 | - | AI 论文精读 | - | - | 26:05 | [link](https://www.bilibili.com/video/BV1Zr421c76A) |
| 210 | 76、Llama源码讲解之RMS-Norm | - | AI 论文精读 | - | - | 13:43 | [link](https://www.bilibili.com/video/BV1u1421k7rH) |
| 211 | 77、Llama源码讲解之GroupQueryAttention和KV-cache | - | AI 论文精读 | - | - | 21:14 | [link](https://www.bilibili.com/video/BV186421f7RL) |
| 212 | 78、Llama源码讲解之Transformer | - | AI 论文精读 | - | - | 17:48 | [link](https://www.bilibili.com/video/BV1mT421k7gB) |
| 213 | 79、Llama源码讲解之自回归采样生成算法 | - | AI 论文精读 | - | - | 21:02 | [link](https://www.bilibili.com/video/BV1Bi421Y7Lo) |
| 214 | 80、Byte Pair Encoding 源码逐行讲解 | - | AI 论文精读 | - | - | 47:45 | [link](https://www.bilibili.com/video/BV12x4y1t75q) |
| 215 | 81、LLaMA-1 论文导读 | - | AI 论文精读 | - | - | 36:34 | [link](https://www.bilibili.com/video/BV1Pb42177gr) |
| 216 | 82、LLaMA-2 论文导读 | - | AI 论文精读 | - | - | 55:27 | [link](https://www.bilibili.com/video/BV1Q4421Z7Zw) |
| 217 | 83、如何计算GPT模型的FLOPs及参数量 | - | AI 论文精读 | - | - | 39:59 | [link](https://www.bilibili.com/video/BV1iQsYeCEoe) |
| 218 | 84、GPT-4o/Moshi实时语音对话多模态算法讲解 | - | AI 论文精读 | - | - | 140:42 | [link](https://www.bilibili.com/video/BV1VQCUYyE6a) |
| 219 | 85、Differential Transformer 论文原理逐段讲解 | - | AI 论文精读 | - | - | 54:58 | [link](https://www.bilibili.com/video/BV1Jq1PYPEYG) |
| 220 | 【读评论】博士up主竟被粉丝要求女装？/ 10w粉丝成就奖牌开箱 | - | AI 论文精读 | - | - | 5:21 | [link](https://www.bilibili.com/video/BV1gF411G7tB) |
| 221 | 【十万粉丝福利】厦大博士一家三口齐跳”小鸡恰恰舞“ | - | AI 论文精读 | - | - | 1:01 | [link](https://www.bilibili.com/video/BV1tr4y1W7hq) |
| 222 | 【疫情下的厦大】中秋节傍晚的全员核酸检测 | - | AI 论文精读 | - | - | 2:14 | [link](https://www.bilibili.com/video/BV1TL4y187c5) |
| 223 | 博士必备发型？聊聊我从茂密的秀发到强者发型的华丽蜕变 | - | AI 论文精读 | - | - | 5:48 | [link](https://www.bilibili.com/video/BV1wL4y1878e) |
| 224 | 导师怒斥研究生【延毕警告】 | - | AI 论文精读 | - | - | 3:31 | [link](https://www.bilibili.com/video/BV17o4y1U7bF) |
| 225 | 读 研 冰 城 | - | AI 论文精读 | - | - | 1:19 | [link](https://www.bilibili.com/video/BV1Jq4y1s7dc) |
| 226 | 【万粉福利】博士夫妻羞耻挑战女团舞只为讨好粉丝？/ 你最最最重要 | - | AI 论文精读 | - | - | 1:28 | [link](https://www.bilibili.com/video/BV1HK411H73d) |
| 227 | 【我们领证啦】将故事写成我们，走过八年的校园爱情，终于在春暖花开的厦门，修成正果啦！ | - | AI 论文精读 | - | - | 6:32 | [link](https://www.bilibili.com/video/BV1ip4y1Q7c7) |
| 228 | 【厦大vlog】开学在即，博士学长带你逛厦大 / 中国最美大学 / 春暖花开的厦门大学 | - | AI 论文精读 | - | - | 4:43 | [link](https://www.bilibili.com/video/BV1MQ4y1N7Pb) |
| 229 | 【婚纱照Vlog】走过了八年的爱情，在春暖花开的厦门，我们拍婚纱照啦！！！！！ | - | AI 论文精读 | - | - | 4:41 | [link](https://www.bilibili.com/video/BV1ke411x7xj) |
| 230 | 【从两个少年到三口之家】你陪我长大，我陪你慢慢变老！ | - | AI 论文精读 | - | - | 4:25 | [link](https://www.bilibili.com/video/BV1fA4y1S7Re) |
| 231 | 【SPSS+AMOS实战教程-01】论文结构&模型构建&问卷设计 / 快速学会实证论文 / 保姆级教程 / 数据来源问卷网 | - | AI 论文精读 | - | - | 11:47 | [link](https://www.bilibili.com/video/BV1ED4y1m7B4) |
| 232 | 【SPSS+AMOS实战教程-02】信度&效度检验 / 快速学会实证论文 / 保姆级教程 / 数据来源问卷网 | - | AI 论文精读 | - | - | 12:57 | [link](https://www.bilibili.com/video/BV1eK411K7tD) |
| 233 | 【SPSS+AMOS实战教程-03】AMOS基本操作 / 快速学会实证论文 / 保姆级教程 / 数据来源问卷网 | - | AI 论文精读 | - | - | 10:12 | [link](https://www.bilibili.com/video/BV1ja4y1j7Th) |
| 234 | 【SPSS+AMOS实战教程-04】Amos拟合优度与假设检验 / 快速学会实证论文 / 保姆级教程 / 数据来源问卷网 | - | AI 论文精读 | - | - | 10:57 | [link](https://www.bilibili.com/video/BV18D4y197K3) |
| 235 | 【SPSS+AMOS实战教程-05】中介效应检验与AMOS操作 / 快速学会实证论文 / 保姆级教程 / 数据来源问卷网 | - | AI 论文精读 | - | - | 7:35 | [link](https://www.bilibili.com/video/BV1Wi4y177SC) |
| 236 | 【SPSS+AMOS实战教程-06】调节效应检验与AMOS操作 / 快速学会实证论文 / 保姆级教程 | - | AI 论文精读 | - | - | 13:26 | [link](https://www.bilibili.com/video/BV1Qp4y1t7pb) |
| 237 | 【5分钟学会SPSS】描述性统计与相关性分析 / 史上最易上手 / 快速学会实证论文 / 保姆级教程 | - | AI 论文精读 | - | - | 5:05 | [link](https://www.bilibili.com/video/BV1xL411x7AU) |
| 238 | 【5分钟学会SPSS】验证性因子分析与探索性因子分析 / 史上最易上手 / 快速学会实证论文 / 保姆级教程 | - | AI 论文精读 | - | - | 4:32 | [link](https://www.bilibili.com/video/BV1wf4y1w7zV) |
| 239 | 【5分钟学会SPSS】独立样本t检验和方差分析 / 史上最易上手 / 快速学会实证论文 / 保姆级教程 | - | AI 论文精读 | - | - | 5:07 | [link](https://www.bilibili.com/video/BV1GU4y1A76Z) |
| 240 | 【5分钟学会SPSS】多元线性回归分析 / 史上最易上手 / 快速学会实证论文 / 保姆级教程 | - | AI 论文精读 | - | - | 3:28 | [link](https://www.bilibili.com/video/BV1La411v7Ny) |
| 241 | 【读研必看】导师选的好，研究生毕业早！博士学长吐血分享 | - | AI 论文精读 | - | - | 8:35 | [link](https://www.bilibili.com/video/BV1hB4y1J7gv) |
| 242 | 【论文降重】希望每一个毕业季的同学都能刷到这个视频！ | - | AI 论文精读 | - | - | 7:05 | [link](https://www.bilibili.com/video/BV1t44y1G7BW) |
| 243 | 请大数据推给想要读博或正在读博的同学 | - | AI 论文精读 | - | - | 5:05 | [link](https://www.bilibili.com/video/BV1PL4y1L78q) |
| 244 | 学长实测论文查重工具，源文鉴真的有那么香吗？ | - | AI 论文精读 | - | - | 5:04 | [link](https://www.bilibili.com/video/BV1dq4y1a7Me) |
| 245 | 十个博士九个有退学的冲动？学长是如何熬过四年读博之路的… | - | AI 论文精读 | - | - | 6:55 | [link](https://www.bilibili.com/video/BV16L4y177Jf) |
| 246 | 学长实测不同价位论文查重工具，结果竟让我大呼离谱？ | - | AI 论文精读 | - | - | 7:06 | [link](https://www.bilibili.com/video/BV1j34y147TL) |
| 247 | 【毕业论文格式排版】本科研究生必看：章节标题样式/页眉页码设置/生成自定义目录/图表格式/参考文献交叉引用 | - | AI 论文精读 | - | - | 17:49 | [link](https://www.bilibili.com/video/BV1744y1N7ts) |
| 248 | 【研究生必备】选对了期刊，发表SCI/核心期刊不是梦！ | - | AI 论文精读 | - | - | 7:27 | [link](https://www.bilibili.com/video/BV11Q4y1B79Z) |
| 249 | 取消博士生发表论文要求？以后博士真的可以轻松毕业了么？ | - | AI 论文精读 | - | - | 5:53 | [link](https://www.bilibili.com/video/BV1k341117L3) |
| 250 | 【安利向】学长亲测最好用的论文写作工具 / 功能强大，高效实现文献阅读、笔记管理、文献引用 / 科研效率提高十倍 | - | AI 论文精读 | - | - | 5:54 | [link](https://www.bilibili.com/video/BV1Bv41137PG) |
| 251 | 【考博】联系导师如何写邮件？导师的回复什么含义？厦大博士学长的经验分享！ | - | AI 论文精读 | - | - | 7:10 | [link](https://www.bilibili.com/video/BV1wb4y1m7n4) |
| 252 | 【研究生必看】学生干部经历重要么？研究生要不要加入学生会、做班委？ | - | AI 论文精读 | - | - | 4:17 | [link](https://www.bilibili.com/video/BV18f4y1J7Tp) |
| 253 | 【干货】三步带你快速高效阅读学术文献 / 博士学长千篇阅读经验总结 / 保姆级教程 / 建议收藏 | - | AI 论文精读 | - | - | 6:24 | [link](https://www.bilibili.com/video/BV1qo4y1U7eh) |
| 254 | 【准研究生必看】做好这些准备，顺利完成从本科生到研究生的华丽蜕变！ | - | AI 论文精读 | - | - | 4:01 | [link](https://www.bilibili.com/video/BV1Fq4y1D73u) |
| 255 | 【干货】论文写作中的文献引用格式 / 如何引用文献 / 毕业论文写作必备 / 保姆级教程 / 建议收藏 | - | AI 论文精读 | - | - | 4:12 | [link](https://www.bilibili.com/video/BV1XU4y177pe) |
| 256 | 【研究生必备】史上最强文献检索攻略 / 三步带你查找下载到想要的最新文献 / 保姆级教程 一看就会 / 建议收藏 | - | AI 论文精读 | - | - | 6:25 | [link](https://www.bilibili.com/video/BV1mq4y1Q73y) |
| 257 | 【论文小白100问】引言和绪论的区别有哪些？该如何选择？ | - | AI 论文精读 | - | - | 4:13 | [link](https://www.bilibili.com/video/BV1Af4y1Y7FV) |
| 258 | 【从本科双非到985博士】这三个习惯，后悔没在大学就养成！/ 本科生、研究生必看 | - | AI 论文精读 | - | - | 11:54 | [link](https://www.bilibili.com/video/BV1av411j7Ek) |
| 259 | 【毕业答辩2】博士学长教你轻松应对答辩现场的老师提问！ / 答辩流程详解 / 汇报PPT / 现场提问回答策略 | - | AI 论文精读 | - | - | 7:35 | [link](https://www.bilibili.com/video/BV1X84y1F7f4) |
| 260 | 【毕业答辩】做好这些准备，毕业论文答辩轻松通过！/ 博士学长倾囊相授 / 答辩PPT制作 / 答辩必备问题 / 着装&物品准备 | - | AI 论文精读 | - | - | 8:34 | [link](https://www.bilibili.com/video/BV1mV411J7ov) |
| 261 | 【论文降重】巨实用！毕业论文降重方法 / 三大招式助力学术小白顺利毕业/ 保姆级教程 / 博士学长手把手带你毕业 | - | AI 论文精读 | - | - | 8:27 | [link](https://www.bilibili.com/video/BV1Py4y1s7h1) |
| 262 | 【研究生必看】论文投稿最强攻略 / 期刊审稿流程 / 论文投稿方式 | - | AI 论文精读 | - | - | 9:54 | [link](https://www.bilibili.com/video/BV1cv411E7dF) |
| 263 | 【干货】文献汇报这样做就对了！/ 导师满意同学爱听 / 研究生组会汇报 / 保姆级教程 / 建议收藏 | - | AI 论文精读 | - | - | 9:26 | [link](https://www.bilibili.com/video/BV1qB4y1w7q7) |
| 264 | 【研究生必看】英文不好如何写作SCI/SSCI英文论文 / 博士学长手把手带你写英文论文 / 保姆级教学 / 经验分享 / 建议收藏 | - | AI 论文精读 | - | - | 6:53 | [link](https://www.bilibili.com/video/BV16y4y1B7fU) |
| 265 | 考 博 必 看 指 南 ！博士如何考？如何准备？申请考核制是什么？直博和硕博连读？ | - | AI 论文精读 | - | - | 7:40 | [link](https://www.bilibili.com/video/BV1gy4y187qn) |
| 266 | 你真的适合读博士么？厦大博士学长经验分享适合读博的4大条件，快看看你都符合么？ | - | AI 论文精读 | - | - | 6:46 | [link](https://www.bilibili.com/video/BV1eK411J7cr) |
| 267 | 【超干货】建议收藏！论文选题怎么选？博士学长带你五分钟学会论文选题！！！ | - | AI 论文精读 | - | - | 4:45 | [link](https://www.bilibili.com/video/BV1ra4y1a78B) |
| 268 | 【干货】建议收藏 / 学术文献读什么？怎么读？/ 博士学长吐血分享/ 研究生必看 / 科研 / 论文心得 | - | AI 论文精读 | - | - | 6:35 | [link](https://www.bilibili.com/video/BV1xD4y1S7Wp) |
| 269 | 【选导师】被逼跳楼？被变态导师性侵？博士学长经验分享研究生导师一定要这样选！！！ | - | AI 论文精读 | - | - | 10:30 | [link](https://www.bilibili.com/video/BV12V411C7Tf) |
| 270 | 【论文拯救指南】干货！五分钟学会Endnote神器自动生成毕业论文参考文献引用格式，本科毕设和研究生小白进 | - | AI 论文精读 | - | [pan.baidu.com](https://pan.baidu.com/s/1hkz_Gj6hTIIFwoYhYwcQ7A) | 6:11 | [link](https://www.bilibili.com/video/BV1Qa4y1i7pA) |
| 271 | 【论文拯救指南】干货！厦大博士学长手把手带你写毕业论文开题报告，本科毕设和研究生小白进 | - | AI 论文精读 | - | - | 9:11 | [link](https://www.bilibili.com/video/BV1Tz4y1d7iZ) |
| 272 | 【论文拯救指南】厦大博士学长带你4句话搞定论文摘要，本科毕设和研究生小白进 | - | AI 论文精读 | - | - | 5:12 | [link](https://www.bilibili.com/video/BV1kz4y1R7ut) |
| 273 | 【论文拯救指南】干货！厦大博士学长手把手带你写文献综述，本科毕设和研究生小白进 | - | AI 论文精读 | - | - | 10:15 | [link](https://www.bilibili.com/video/BV1j64y1M76u) |
| 274 | 【干货】毕业论文云答辩？厦大博士学长分享线上答辩通关秘籍！大四、研三必看 | - | AI 论文精读 | - | - | 8:07 | [link](https://www.bilibili.com/video/BV1Bk4y1R7KJ) |
| 275 | 【论文拯救指南】干货！厦大博士学长手把手带你写论文引言，本科毕设和研究生小白进 | - | AI 论文精读 | - | - | 7:01 | [link](https://www.bilibili.com/video/BV1Z54y1X7wr) |
| 276 | 【干货推荐】这样学习Stata事半功倍，绝不会“一学就废”！ | - | AI 论文精读 | - | - | 3:26 | [link](https://www.bilibili.com/video/BV1pB4y117fn) |
| 277 | 【干货】搞懂论文逻辑结构，读文献思路清晰，写论文下笔如神！ | - | AI 论文精读 | - | - | 5:19 | [link](https://www.bilibili.com/video/BV1sB4y1j71x) |
| 278 | 【研究生学英语】听说读写，这样学英语就对了！ | - | AI 论文精读 | - | - | 8:47 | [link](https://www.bilibili.com/video/BV1AK411d7cD) |
| 279 | 【安利】能随意编辑文字和图片的PDF神器，你见过吗？ | - | AI 论文精读 | - | - | 3:19 | [link](https://www.bilibili.com/video/BV1X8411A7sn) |
| 280 | 学姐亲测火遍全网的ChatGPT能帮论文党做什么？/ 文献阅读 /文献查找/ 搭建提纲/ 论文撰写/ 技术支持 | - | AI 论文精读 | - | - | 3:35 | [link](https://www.bilibili.com/video/BV1QD4y1A7sZ) |
| 281 | 用ChatGPT写了篇本科论文，查重率竟然达到？！ | - | AI 论文精读 | - | - | 2:43 | [link](https://www.bilibili.com/video/BV15M4y1S7ah) |
| 282 | 【毕业论文】第一集：论文选题，好的开始是成功的一半 | - | AI 论文精读 | - | - | 4:39 | [link](https://www.bilibili.com/video/BV1X24y1b7RL) |
| 283 | 【麦小哲】开题报告实用攻略，毕业论文必备，手把手带你完成开题报告撰写 | - | AI 论文精读 | - | - | 7:32 | [link](https://www.bilibili.com/video/BV1Fz4y1w7Tq) |
| 284 | 【麦小哲】科研小白如何快速高效阅读文献？宝藏方法推荐，建议收藏 | - | AI 论文精读 | - | [updf.cn](https://www.updf.cn/pdf-edu/) | 5:26 | [link](https://www.bilibili.com/video/BV1kw411n7DL) |
| 285 | [论文简析]VAE: Auto-encoding Variational Bayes[1312.6114] | - | AI 论文精读 | [1312.6114](https://arxiv.org/abs/1312.6114) | - | 20:06 | [link](https://www.bilibili.com/video/BV1q64y1y7J2) |
| 286 | [论文简析]ViT: Vision Transformer[2010.11929] | - | AI 论文精读 | [2010.11929](https://arxiv.org/abs/2010.11929) | [github.com](https://github.com/google-research/vision_transformer) | 15:22 | [link](https://www.bilibili.com/video/BV1di4y1N7pc) |
| 287 | [论文简析]How Do Vision Transformers Work?[2202.06709] | - | AI 论文精读 | [2202.06709](https://arxiv.org/abs/2202.06709) | [github.com](https://github.com/xxxnell/how-do-vits-work) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 47:24 | [link](https://www.bilibili.com/video/BV1UF41147AG) |
| 288 | [论文简析]Swin Transformer: Hierarchical ViT using Shifted Windows[2103.14030] | - | AI 论文精读 | [2103.14030](https://arxiv.org/abs/2103.14030) | [github.com](https://github.com/microsoft/Swin-Transformer) | 9:09 | [link](https://www.bilibili.com/video/BV1e84y1F7Sc) |
| 289 | [论文简析]DETR: End-to-End Object Detection with Transfromers[2005.12872] | - | AI 论文精读 | [2005.12872](https://arxiv.org/abs/2005.12872) | [github.com](https://github.com/facebookresearch/detr) | 14:30 | [link](https://www.bilibili.com/video/BV1T64y1D7NY) |
| 290 | [论文简析]NeRF: Representing Scenes as Neural Radiance Fields...[2003.08934] | - | AI 论文精读 | [2003.08934](https://arxiv.org/abs/2003.08934) | [github.com](https://github.com/bmild/nerf) [youtube.com](https://www.youtube.com/watch?v=dPWLybp4LL0) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 16:07 | [link](https://www.bilibili.com/video/BV1mV4y1M7TB) |
| 291 | [论文简析]Deep Unsupervised Learning using Nonequilibrium Thermodynamics[1503.03585] | - | AI 论文精读 | [1503.03585](https://arxiv.org/abs/1503.03585) | [github.com](https://github.com/Sohl-Dickstein/Diffusion-Probabilistic-Models) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 47:02 | [link](https://www.bilibili.com/video/BV19v4y1C7De) |
| 292 | [论文速览]LoRA: Low-Rank Adaptation of Large Language Models[2106.09685] | - | AI 论文精读 | [2106.09685](https://arxiv.org/abs/2106.09685) | [github.com](https://github.com/microsoft/LoRA) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 5:17 | [link](https://www.bilibili.com/video/BV1wX4y1s7an) |
| 293 | [论文速览]Flamingo: a Visual Language Model for Few-Shot Learning[2204.14198] | - | AI 论文精读 | [2204.14198](https://arxiv.org/abs/2204.14198) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 7:47 | [link](https://www.bilibili.com/video/BV1pu411G7ce) |
| 294 | [论文简析]A Generalist Agent / Gato[2205.06175] | - | AI 论文精读 | [2205.06175](https://arxiv.org/abs/2205.06175) | [github.com](https://github.com/OrigamiDream/gato) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 31:00 | [link](https://www.bilibili.com/video/BV1EK421k7Sy) |
| 295 | [论文简析]Does SSL Really Improve RL from Pixels?[2206.05266] | - | AI 论文精读 | [2206.05266](https://arxiv.org/abs/2206.05266) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 28:58 | [link](https://www.bilibili.com/video/BV1gM411r7wq) |
| 296 | [论文简析]Dreamer V2[2010.02193] | - | AI 论文精读 | - | [danijar.com](https://danijar.com/project/dreamerv2/) [ai.googleblog.com](https://ai.googleblog.com/2021/02/mastering-atari-with-discrete-world.html) | 23:20 | [link](https://www.bilibili.com/video/BV15o4y1R7kT) |
| 297 | [论文简析]World Models[1803.10122] | - | AI 论文精读 | [1803.10122](https://arxiv.org/abs/1803.10122) | [worldmodels.github.io](https://worldmodels.github.io/) [youtube.com](https://www.youtube.com/watch?v=HzA8LRqhujk) | 13:40 | [link](https://www.bilibili.com/video/BV1oz4y117qk) |
| 298 | [论文简析]Transformers are Sample Efficient World Models[2209.00588] | - | AI 论文精读 | [2209.00588](https://arxiv.org/abs/2209.00588) | [github.com](https://github.com/eloialonso/iris) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 10:34 | [link](https://www.bilibili.com/video/BV1i24y1Z78Q) |
| 299 | [论文简析]Reinforcement Learning with Augmented Data: RAD[2004.14990] | - | AI 论文精读 | [2004.14990](https://arxiv.org/abs/2004.14990) | [github.com](https://www.github.com/MishaLaskin/rad) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 4:54 | [link](https://www.bilibili.com/video/BV1ZS4y1h77B) |
| 300 | [论文简析]CURL[2004.04136] | - | AI 论文精读 | - | [github.com](https://github.com/MishaLaskin/curl) | 11:15 | [link](https://www.bilibili.com/video/BV14v411h7sq) |
| 301 | [论文简析]SPR: Data-Efficient RL with Self-Predictive Representations[2007.05929] | - | AI 论文精读 | [2007.05929](https://arxiv.org/abs/2007.05929) | [github.com](https://github.com/mila-iqia/spr) | 8:15 | [link](https://www.bilibili.com/video/BV1bN411Q7Hz) |
| 302 | [论文简析]DrQ: Data regularized Q[2004.13649] | - | AI 论文精读 | [2004.13649](https://arxiv.org/abs/2004.13649) | [sites.google.com](https://sites.google.com/view/data-regularized-q) | 10:44 | [link](https://www.bilibili.com/video/BV15p4y1h7Xu) |
| 303 | [论文简析]The Dormant Neuron Phenomenon in Deep Reinforcement Learning[2302.12902] | - | AI 论文精读 | [2302.12902](https://arxiv.org/abs/2302.12902) | [github.com](https://github.com/google/dopamine/tree/master/dopamine/labs/redo) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 13:34 | [link](https://www.bilibili.com/video/BV1r94y1w7tE) |
| 304 | [论文简析]XSkill: Cross Embodiment Skill Discovery[2307.09955] | - | AI 论文精读 | [2307.09955](https://arxiv.org/abs/2307.09955) | [xskill.cs.columbia.edu](https://xskill.cs.columbia.edu/) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 18:50 | [link](https://www.bilibili.com/video/BV1bj411L7yK) |
| 305 | [论文简析]Video Prediction Policy: A Generalist Robot Policy...[2412.14803] | - | AI 论文精读 | [2412.14803](https://arxiv.org/abs/2412.14803) | [video-prediction-policy.github.io](https://video-prediction-policy.github.io/) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 10:25 | [link](https://www.bilibili.com/video/BV1hZugzdE4F) |
| 306 | [论文速览]Efficient Action Tokenization for Vision-Language-Action Model[2501.09747] | - | AI 论文精读 | [2501.09747](https://arxiv.org/abs/2501.09747) | [pi.website](https://www.pi.website/research/fast) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 14:40 | [link](https://www.bilibili.com/video/BV1TuFpeKEXQ) |
| 307 | [论文简析]Rainbow:Combining Improvements in Deep Reinforcement Learning[1710.02298] | - | AI 论文精读 | [1710.02298](https://arxiv.org/abs/1710.02298) | [github.com](https://github.com/Kaixhin/Rainbow) | 27:38 | [link](https://www.bilibili.com/video/BV1W64y1x7MF) |
| 308 | [论文简析]PPG: Phasic Policy Gradient[2009.04416] | - | AI 论文精读 | [2009.04416](https://arxiv.org/abs/2009.04416) | [github.com](https://github.com/openai/phasic-policy-gradient) | 7:47 | [link](https://www.bilibili.com/video/BV1uB4y1A7Ec) |
| 309 | [论文简析]SAC: Soft Actor-Critic Part 1[1801.01290] | - | AI 论文精读 | [1801.01290](https://arxiv.org/abs/1801.01290) | - | 42:28 | [link](https://www.bilibili.com/video/BV1YK4y1T7b6) |
| 310 | [论文简析]SAC: Soft Actor-Critic Part 2[1812.05905] | - | AI 论文精读 | [1812.05905](https://arxiv.org/abs/1812.05905) | - | 10:53 | [link](https://www.bilibili.com/video/BV13V411e7Qb) |
| 311 | [论文简析]C-Learning: Learning to .. via Recursive Classification[2011.08909] | - | AI 论文精读 | [2011.08909](https://arxiv.org/abs/2011.08909) | [ben-eysenbach.github.io](https://ben-eysenbach.github.io/c_learning/) | 24:27 | [link](https://www.bilibili.com/video/BV1J64y1S7ZA) |
| 312 | [论文简析]Time-Contrastive Networks:Self-Supervised Learning from Video[1704.06888] | - | AI 论文精读 | [1704.06888](https://arxiv.org/abs/1704.06888) | [sermanet.github.io](https://sermanet.github.io/imitate/) | 13:03 | [link](https://www.bilibili.com/video/BV1Sr4y1A7bp) |
| 313 | [论文速览]Diffusion Policy: Visuomotor Policy Learning via Action Diff.[2303.04137] | - | AI 论文精读 | [2303.04137](https://arxiv.org/abs/2303.04137) | [diffusion-policy.cs.columbia.edu](https://diffusion-policy.cs.columbia.edu/) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 5:50 | [link](https://www.bilibili.com/video/BV1Cu411Y7d7) |
| 314 | [论文速览]Decision Transformer: RL via Sequence Modeling[2106.01345] | - | AI 论文精读 | [2106.01345](https://arxiv.org/abs/2106.01345) | [sites.google.com](https://sites.google.com/berkeley.edu/decision-transformer) | 5:11 | [link](https://www.bilibili.com/video/BV1zf4y1t7ka) |
| 315 | [论文简析]Visionary: Vision architecture discovery for robot learning[2103.14633] | - | AI 论文精读 | [2103.14633](https://arxiv.org/abs/2103.14633) | - | 10:31 | [link](https://www.bilibili.com/video/BV1oo4y1k7Jo) |
| 316 | [论文简析]Neuroevolution of Self-interpretable Agents[2003.08165] | - | AI 论文精读 | [2003.08165](https://arxiv.org/abs/2003.08165) | [attentionagent.github.io](https://attentionagent.github.io/) [youtube.com](https://www.youtube.com/watch?v=DTgeEWK_Wm0) | 13:32 | [link](https://www.bilibili.com/video/BV17Z4y1w7sX) |
| 317 | [论文简析]QT-Opt: Scalable Deep RL for Vision-Based Robotic Manipulation[1806.10293] | - | AI 论文精读 | [1806.10293](https://arxiv.org/abs/1806.10293) | [sites.google.com](https://sites.google.com/view/qtopt) | 13:35 | [link](https://www.bilibili.com/video/BV1Ey4y187bi) |
| 318 | [论文速览]DDPG&TD3[1509.02971][1802.09477] | - | AI 论文精读 | - | - | 17:30 | [link](https://www.bilibili.com/video/BV1nU4y1u7h1) |
| 319 | [论文简析]SEER: Stored Embeddings for Efficient RL[2103.02886] | - | AI 论文精读 | [2103.02886](https://arxiv.org/abs/2103.02886) | [github.com](https://github.com/lili-chen/SEER) | 7:48 | [link](https://www.bilibili.com/video/BV1rv411h7iS) |
| 320 | [论文简析]BCO: Behavioral Cloning from Observation[1805.01954] | - | AI 论文精读 | [1805.01954](https://arxiv.org/abs/1805.01954) | - | 16:14 | [link](https://www.bilibili.com/video/BV1aN411X7YT) |
| 321 | [论文简析]A Framework for Efficient Robotic Manipulation[2012.07975] | - | AI 论文精读 | [2012.07975](https://arxiv.org/abs/2012.07975) | [sites.google.com](https://sites.google.com/view/efficient-robotic-manipulation) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 5:33 | [link](https://www.bilibili.com/video/BV1pL4y1u7KG) |
| 322 | [论文速览]VRL3: A Data-Driven Framework for Visual Deep Reinforcement L.[2202.10324] | - | AI 论文精读 | [2202.10324](https://arxiv.org/abs/2202.10324) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 6:03 | [link](https://www.bilibili.com/video/BV1R841157aG) |
| 323 | [论文速览]Mask-based Latent Reconstruction for Reinforcement Learning[2201.12096] | - | AI 论文精读 | [2201.12096](https://arxiv.org/abs/2201.12096) | [github.com](https://github.com/microsoft/Mask-based-Latent-Reconstruction) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 5:10 | [link](https://www.bilibili.com/video/BV12v4y1z7BM) |
| 324 | [论文简析]Learning Invariant Representations for RL without Reconstructi[2006.10742] | - | AI 论文精读 | [2006.10742](https://arxiv.org/abs/2006.10742) | [sites.google.com](https://sites.google.com/view/deepbisim4control) | 15:29 | [link](https://www.bilibili.com/video/BV1EK4y1K7EL) |
| 325 | [论文简析]Stabilizing transformers for reinforcement learning[1910.06764] | - | AI 论文精读 | [1910.06764](https://arxiv.org/abs/1910.06764) | - | 13:57 | [link](https://www.bilibili.com/video/BV1Jf4y1s7ac) |
| 326 | [论文简析]Efficient Transformers in RL using Actor-Learner Distillation[2104.01655] | - | AI 论文精读 | [2104.01655](https://arxiv.org/abs/2104.01655) | - | 7:09 | [link](https://www.bilibili.com/video/BV1wZ4y1w7wP) |
| 327 | [论文速览]NeRF-RL: Reinforcement Learning with Neural Radiance Fields[2206.01634] | - | AI 论文精读 | [2206.01634](https://arxiv.org/abs/2206.01634) | [dannydriess.github.io](https://dannydriess.github.io/nerf-rl) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 10:13 | [link](https://www.bilibili.com/video/BV1tG4y1V7hn) |
| 328 | [论文简析]DADS: Dynamics-Aware Unsupervised Discovery of Skills[1907.01657] | - | AI 论文精读 | [1907.01657](https://arxiv.org/abs/1907.01657) | [sites.google.com](https://sites.google.com/view/dads-skill) | 21:09 | [link](https://www.bilibili.com/video/BV165411w71J) |
| 329 | [论文简析]Off-DADS: Emergent Real-World Robotic Skills via off policy RL[2004.12974] | - | AI 论文精读 | [2004.12974](https://arxiv.org/abs/2004.12974) | [sites.google.com](https://sites.google.com/view/dads-skill) | 10:16 | [link](https://www.bilibili.com/video/BV18y4y1h7P9) |
| 330 | [论文速览]Stabilizing Deep Q-Learning with ConvNets and ViT...[2107.00644] | - | AI 论文精读 | [2107.00644](https://arxiv.org/abs/2107.00644) | [nicklashansen.github.io](https://nicklashansen.github.io/SVEA) | 3:56 | [link](https://www.bilibili.com/video/BV12w411f74a) |
| 331 | [论文简析]Behavior From the Void: Unsupervised Active Pre-Training[2103.04551] | - | AI 论文精读 | [2103.04551](https://arxiv.org/abs/2103.04551) | - | 9:18 | [link](https://www.bilibili.com/video/BV1By4y1t7aK) |
| 332 | [论文速览]Self-Supervised Policy Adaptation during Deployment[2007.04309] | - | AI 论文精读 | [2007.04309](https://arxiv.org/abs/2007.04309) | [nicklashansen.github.io](https://nicklashansen.github.io/PAD/) | 3:43 | [link](https://www.bilibili.com/video/BV1t54y1J7pd) |
| 333 | [论文简析]RL-CycleGAN: Reinforcement Learning Aware Simulation-To-Real[2006.09001] | - | AI 论文精读 | [2006.09001](https://arxiv.org/abs/2006.09001) | - | 13:58 | [link](https://www.bilibili.com/video/BV1L54y1n7d3) |
| 334 | [论文速览]Synthetic Experience Replay[2303.06614] | - | AI 论文精读 | [2303.06614](https://arxiv.org/abs/2303.06614) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 2:32 | [link](https://www.bilibili.com/video/BV1wx4y1P7hD) |
| 335 | [论文简析]Contrastive Language, Action, and State Pre-training...[2304.10782] | - | AI 论文精读 | [2304.10782](https://arxiv.org/abs/2304.10782) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 6:16 | [link](https://www.bilibili.com/video/BV1UF411U7zk) |
| 336 | [论文速览]Implicit Behavioral Cloning / IBC[2109.00137] | - | AI 论文精读 | [2109.00137](https://arxiv.org/abs/2109.00137) | [implicitbc.github.io](https://implicitbc.github.io/) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 6:57 | [link](https://www.bilibili.com/video/BV18N411J7FD) |
| 337 | [论文夕拾]Diffusion Models for Robotics | - | AI 论文精读 | [2302.00111](https://arxiv.org/abs/2302.00111) | [universal-policy.github.io](https://universal-policy.github.io/unipi/) [diffusion-rosie.github.io](https://diffusion-rosie.github.io/) [github.com](https://github.com/conglu1997/SynthER) | 7:41 | [link](https://www.bilibili.com/video/BV1mV411c7na) |
| 338 | [论文简析]Crossway Diffusion: Improving Diffusion-based ... via SSL[2307.01849] | - | AI 论文精读 | [2307.01849](https://arxiv.org/abs/2307.01849) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 9:41 | [link](https://www.bilibili.com/video/BV1Yp4y1F7nv) |
| 339 | [论文速览]A Self-Improving Generalist Agent for Robotic Manipulation[2306.11706] | - | AI 论文精读 | [2306.11706](https://arxiv.org/abs/2306.11706) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 12:12 | [link](https://www.bilibili.com/video/BV1cx4y1y7PZ) |
| 340 | [论文速览]OpenVLA: An Open-Source Vision-Language-Action Model[2406.09246] | - | AI 论文精读 | [2406.09246](https://arxiv.org/abs/2406.09246) | [openvla.github.io](https://openvla.github.io/) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 5:31 | [link](https://www.bilibili.com/video/BV1m1421C7m7) |
| 341 | [论文速览]LLaRA: Supercharging Robot Learning Data for VLM Policy[2406.20095] | - | AI 论文精读 | [2406.20095](https://arxiv.org/abs/2406.20095) | [github.com](https://github.com/LostXine/LLaRA) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 15:02 | [link](https://www.bilibili.com/video/BV174421D7tW) |
| 342 | [论文速览]GENIMA: Generative Image as Action Models[2407.07875] | - | AI 论文精读 | [2407.07875](https://arxiv.org/abs/2407.07875) | [github.com](https://github.com/MohitShridhar/genima) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 6:20 | [link](https://www.bilibili.com/video/BV17S421971u) |
| 343 | [论文夕拾]Robot Manipulation in a Language Model Era | - | AI 论文精读 | - | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 12:03 | [link](https://www.bilibili.com/video/BV1BdCFYmEpa) |
| 344 | [论文速览]Latent Action Pretraining from Videos[2410.11758] | - | AI 论文精读 | [2410.11758](https://arxiv.org/abs/2410.11758) | [latentactionpretraining.github.io](https://latentactionpretraining.github.io/) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 6:41 | [link](https://www.bilibili.com/video/BV144KPeYE9v) |
| 345 | [论文速览]π_0: A Vision-Language-Action Flow Model for General Robot...[2410.24164] | - | AI 论文精读 | [2410.24164](https://arxiv.org/abs/2410.24164) | [github.com](https://github.com/Physical-Intelligence/openpi) [physicalintelligence.company](https://www.physicalintelligence.company/download/pi0.pdf) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 25:11 | [link](https://www.bilibili.com/video/BV142uFzWEdY) |
| 346 | [论文简析]DreamVLA: A Vision-Language-Action Model Dreamed...[2507.04447] | - | AI 论文精读 | [2507.04447](https://arxiv.org/abs/2507.04447) | [github.com](https://github.com/Zhangwenyao1/DreamVLA) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 9:12 | [link](https://www.bilibili.com/video/BV116utzwEZs) |
| 347 | [论文简析]Representation Learning with Contrastive Predictive Coding[1807.03748] | - | AI 论文精读 | [1807.03748](https://arxiv.org/abs/1807.03748) | - | 17:05 | [link](https://www.bilibili.com/video/BV1fK4y1o7A1) |
| 348 | [论文速览]Data-Efficient Image Recog with Contrastive Predictive Coding[1905.09272] | - | AI 论文精读 | [1905.09272](https://arxiv.org/abs/1905.09272) | - | 6:16 | [link](https://www.bilibili.com/video/BV1GU4y1H7b6) |
| 349 | [论文简析]SimCLR: A simple framework for contrastive learning[2002.05709] | - | AI 论文精读 | [2002.05709](https://arxiv.org/abs/2002.05709) | - | 3:12 | [link](https://www.bilibili.com/video/BV1Cp4y1b7ex) |
| 350 | [论文简析]SwAV: Swapping Assignments between multiple Views[2006.09882] | - | AI 论文精读 | [2006.09882](https://arxiv.org/abs/2006.09882) | [github.com](https://github.com/facebookresearch/swav) | 16:59 | [link](https://www.bilibili.com/video/BV1754y187Ki) |
| 351 | [论文简析]MoCo: Momentum Contrast Learning[1911.05722/2003.04297] | - | AI 论文精读 | - | - | 10:00 | [link](https://www.bilibili.com/video/BV1av411874e) |
| 352 | [论文简析]BYOL: Bootstrap Your Own Latent[2006.07733] | - | AI 论文精读 | [2006.07733](https://arxiv.org/abs/2006.07733) | [github.com](https://github.com/deepmind/deepmind-research/tree/master/byol) | 16:23 | [link](https://www.bilibili.com/video/BV1ki4y1T7X4) |
| 353 | [论文简析]DINO Emerging Properties in SelfSupervised Vision Transformers[2104.14294] | - | AI 论文精读 | [2104.14294](https://arxiv.org/abs/2104.14294) | [github.com](https://github.com/facebookresearch/dino) | 9:56 | [link](https://www.bilibili.com/video/BV1H54y157kj) |
| 354 | [论文简析]SimSiam: Exploring Simple Siamese Representation Learning[2011.10566] | - | AI 论文精读 | [2011.10566](https://arxiv.org/abs/2011.10566) | [github.com](https://github.com/PatrickHua/SimSiam) | 9:16 | [link](https://www.bilibili.com/video/BV1Ah411Q7Lb) |
| 355 | [论文简析]Barlow Twins:Self-Supervised Learning via Redundancy Reduction[2103.03230] | - | AI 论文精读 | [2103.03230](https://arxiv.org/abs/2103.03230) | [github.com](https://github.com/facebookresearch/barlowtwins) | 5:47 | [link](https://www.bilibili.com/video/BV1gZ4y1P7U1) |
| 356 | [论文速览]iBOT: Image BERT Pre-Training with Online Tokenizer[2111.07832] | - | AI 论文精读 | [2111.07832](https://arxiv.org/abs/2111.07832) | [github.com](https://github.com/bytedance/ibot) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 7:15 | [link](https://www.bilibili.com/video/BV1uM4y1q7Pa) |
| 357 | [论文简析]Evolving Losses for Unsupervised Video Representation Learning[2002.12177] | - | AI 论文精读 | [2002.12177](https://arxiv.org/abs/2002.12177) | - | 18:33 | [link](https://www.bilibili.com/video/BV1Pp4y1h7Ke) |
| 358 | [论文简析]Broaden Your Views for Self-Supervised Video Learning[2103.16559] | - | AI 论文精读 | [2103.16559](https://arxiv.org/abs/2103.16559) | - | 8:00 | [link](https://www.bilibili.com/video/BV1LQ4y1i7Zv) |
| 359 | [论文速览]Self-supervised Video Transformer[2112.01514] | - | AI 论文精读 | [2112.01514](https://arxiv.org/abs/2112.01514) | [github.com](https://github.com/kahnchana/svt) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 7:09 | [link](https://www.bilibili.com/video/BV17Y4y1g7Jw) |
| 360 | [论文简析]Extreme Masking for Learning Instance and Distributed Visual..[2206.04667] | - | AI 论文精读 | [2206.04667](https://arxiv.org/abs/2206.04667) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 5:22 | [link](https://www.bilibili.com/video/BV1sY4y1G7St) |
| 361 | [论文简析]Learning by Aligning Videos in Time[2103.17260] | - | AI 论文精读 | [2103.17260](https://arxiv.org/abs/2103.17260) | - | 11:13 | [link](https://www.bilibili.com/video/BV13f4y1b7Nt) |
| 362 | [论文简析]Probabilistic Representations for Video Contrastive Learning[2204.03946] | - | AI 论文精读 | [2204.03946](https://arxiv.org/abs/2204.03946) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 14:47 | [link](https://www.bilibili.com/video/BV1RT4y1Y73n) |
| 363 | [论文简析]Propagate Yourself: Exploring Pixel-Level Consistency...[2011.10043] | - | AI 论文精读 | [2011.10043](https://arxiv.org/abs/2011.10043) | [github.com](https://github.com/zdaxie/PixPro) | 7:37 | [link](https://www.bilibili.com/video/BV1hV411x7wL) |
| 364 | [论文简析]Location-Aware Self-Supervised Transformers for Semantic Seg.[2212.02400] | - | AI 论文精读 | [2212.02400](https://arxiv.org/abs/2212.02400) | [github.com](https://github.com/google-research/scenic/tree/main/scenic/projects/) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 12:03 | [link](https://www.bilibili.com/video/BV1wk4y1i7eH) |
| 365 | [论文简析]Rethinking Pre-training and Self-training[2006.06882] | - | AI 论文精读 | [2006.06882](https://arxiv.org/abs/2006.06882) | [github.com](https://github.com/tensorflow/tpu/tree/master/models/official/detection/projects/self_training) | 8:21 | [link](https://www.bilibili.com/video/BV1pK4y1U7ts) |
| 366 | [论文简析]Energy-Inspired Self-Supervised Pretraining for Vision Models[2302.01384] | - | AI 论文精读 | [2302.01384](https://arxiv.org/abs/2302.01384) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 11:08 | [link](https://www.bilibili.com/video/BV1hg4y1H7Gj) |
| 367 | [论文简析]Humble Teachers Teach Better Students for Semi-Supervised Object Detection | - | AI 论文精读 | - | [github.com](https://github.com/lryta/HumbleTeacher) | 12:45 | [link](https://www.bilibili.com/video/BV1SK4y1u7ix) |
| 368 | [论文简析]Towards Better Understanding of Self-Supervised Representation[2203.01881] | - | AI 论文精读 | [2203.01881](https://arxiv.org/abs/2203.01881) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 7:46 | [link](https://www.bilibili.com/video/BV1fG411n7EC) |
| 369 | [论文简析]TransRank: SS Video...Ranking-based Transformation Recognition[2205.02028] | - | AI 论文精读 | [2205.02028](https://arxiv.org/abs/2205.02028) | [github.com](https://github.com/kennymckormick/TransRank) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 14:28 | [link](https://www.bilibili.com/video/BV1zS4y1e7uY) |
| 370 | [论文速览]Object Discovery and Representation Networks[2203.08777] | - | AI 论文精读 | [2203.08777](https://arxiv.org/abs/2203.08777) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 5:52 | [link](https://www.bilibili.com/video/BV1n34y1b7Uo) |
| 371 | [论文速览]Efficient Visual Pretraining with Contrastive Detection[2103.10957] | - | AI 论文精读 | [2103.10957](https://arxiv.org/abs/2103.10957) | [github.com](https://github.com/deepmind/detcon) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 4:18 | [link](https://www.bilibili.com/video/BV1bY411n7BP) |
| 372 | [论文简析]Directional SSL for Heavy Image Augmentations[2110.13555] | - | AI 论文精读 | [2110.13555](https://arxiv.org/abs/2110.13555) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 6:31 | [link](https://www.bilibili.com/video/BV19U4y1o7SQ) |
| 373 | [论文速览]Invariant Information Clustering for Unsupervised Image...[1807.06653] | - | AI 论文精读 | [1807.06653](https://arxiv.org/abs/1807.06653) | [github.com](https://github.com/xu-ji/IIC) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 10:24 | [link](https://www.bilibili.com/video/BV1t34y1t72d) |
| 374 | [论文速览]Video Rep. Learning by Recognizing Temporal Transformations[2007.10730] | - | AI 论文精读 | [2007.10730](https://arxiv.org/abs/2007.10730) | [github.com](https://github.com/sjenni/temporal-ssl) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 6:34 | [link](https://www.bilibili.com/video/BV1qU4y1X7cg) |
| 375 | [论文简析]β-VAE Learning basic visual concepts with a constrained variational... | - | AI 论文精读 | - | [openreview.net](https://openreview.net/forum?id=Sy2fzU9gl) | 12:50 | [link](https://www.bilibili.com/video/BV1644y1q7Aj) |
| 376 | [论文简析]DCLGAN/SimDCL: Dual Contrastive Learning[2104.07689] | - | AI 论文精读 | [2104.07689](https://arxiv.org/abs/2104.07689) | [github.com](https://github.com/JunlinHan/DCLGAN) | 6:01 | [link](https://www.bilibili.com/video/BV15v411j7N7) |
| 377 | [论文简析]Generative Scene Inference and Sampling...[1907.13052] | - | AI 论文精读 | [1907.13052](https://arxiv.org/abs/1907.13052) | [github.com](https://github.com/applied-ai-lab/genesis) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 14:14 | [link](https://www.bilibili.com/video/BV1aZ4y1R7Ne) |
| 378 | [论文简析]An Empirical Study of Training Self-Supervised ViT[2104.02057] | - | AI 论文精读 | [2104.02057](https://arxiv.org/abs/2104.02057) | - | 8:58 | [link](https://www.bilibili.com/video/BV1UX4y1g7Dn) |
| 379 | [论文速览]Multi-Object ... with Iterative Variational Inference[1903.00450] | - | AI 论文精读 | [1903.00450](https://arxiv.org/abs/1903.00450) | [github.com](https://github.com/zhixuan-lin/IODINE) | 15:29 | [link](https://www.bilibili.com/video/BV15a41127C9) |
| 380 | [论文简析]MONet: Unsupervised Scene Decomposition and Representation[1901.11390] | - | AI 论文精读 | [1901.11390](https://arxiv.org/abs/1901.11390) | [github.com](https://github.com/baudm/MONet-pytorch) | 13:43 | [link](https://www.bilibili.com/video/BV1CT4y1y7Hc) |
| 381 | [论文简析]Leveraging BG AUG to encourage semantic focus in SSCL[2103.12719] | - | AI 论文精读 | [2103.12719](https://arxiv.org/abs/2103.12719) | - | 4:34 | [link](https://www.bilibili.com/video/BV1xX4y1G7Pe) |
| 382 | [论文简析]Object-Centric Learning with Slot Attention[2006.15055] | - | AI 论文精读 | [2006.15055](https://arxiv.org/abs/2006.15055) | [github.com](https://github.com/google-research/google-research/tree/master/slot_attention) | 9:18 | [link](https://www.bilibili.com/video/BV1QL4y1s7NK) |
| 383 | [论文简析]Equivariant Contrastive Learning[2111.00899] | - | AI 论文精读 | [2111.00899](https://arxiv.org/abs/2111.00899) | - | 10:02 | [link](https://www.bilibili.com/video/BV1jS4y1Z7Py) |
| 384 | [论文简析]Big Self-Supervised Models are Strong Semi-Supervised Learners[2006.10029] | - | AI 论文精读 | [2006.10029](https://arxiv.org/abs/2006.10029) | [github.com](https://github.com/google-research/simclr) | 7:04 | [link](https://www.bilibili.com/video/BV1Ey4y1t7zK) |
| 385 | [论文简析]Keeping Your Eye on the Ball: Trajectory Attention...[2106.05392] | - | AI 论文精读 | [2106.05392](https://arxiv.org/abs/2106.05392) | [github.com](https://github.com/facebookresearch/Motionformer) | 19:43 | [link](https://www.bilibili.com/video/BV1j3411i7jU) |
| 386 | [论文简析]Wasserstein Contrastive Representation Distillation: WCoRD[2012.08674] | - | AI 论文精读 | [2012.08674](https://arxiv.org/abs/2012.08674) | - | 19:41 | [link](https://www.bilibili.com/video/BV1vw41197wC) |
| 387 | [论文速览]Masked Feature Prediction .Self-Supervised Visual Pre-Training[2112.09133] | - | AI 论文精读 | [2112.09133](https://arxiv.org/abs/2112.09133) | [github.com](https://github.com/facebookresearch/pytorchvideo) | 5:17 | [link](https://www.bilibili.com/video/BV1YS4y1Q7Qj) |
| 388 | [论文速览]AugSelf: Improving Transferability...Augmentation-Aware..[2111.09613] | - | AI 论文精读 | [2111.09613](https://arxiv.org/abs/2111.09613) | [github.com](https://github.com/hankook/AugSelf) | 4:09 | [link](https://www.bilibili.com/video/BV1Ei4y1Z7Ld) |
| 389 | [论文速览]Nearest-Neighbor Contrastive Learning of Visual Representations[2104.14548 | - | AI 论文精读 | [2104.14548](https://arxiv.org/abs/2104.14548) | - | 5:34 | [link](https://www.bilibili.com/video/BV12f4y1M7Qq) |
| 390 | [论文速览]Solving Inefficiency of Self-supervised Representation Learning[2104.0876] | - | AI 论文精读 | [2104.08760](https://arxiv.org/abs/2104.08760) | [github.com](https://github.com/wanggrun/triplet) | 6:17 | [link](https://www.bilibili.com/video/BV1FL4y1z7jq) |
| 391 | [论文简析]VideoMoCo: ...Temporally Adversarial Examples[2103.05905] | - | AI 论文精读 | [2103.05905](https://arxiv.org/abs/2103.05905) | [github.com](https://github.com/tinapan-pt/VideoMoCo) | 6:43 | [link](https://www.bilibili.com/video/BV13f4y137Wc) |
| 392 | [论文速览]Theia: Distilling Diverse Vision Foundation Models for Robot..[2407.20179] | - | AI 论文精读 | [2407.20179](https://arxiv.org/abs/2407.20179) | [github.com](https://github.com/bdaiinstitute/theia) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 8:04 | [link](https://www.bilibili.com/video/BV18W42197So) |
| 393 | [论文速览]Long Short View Feature Decomposition via Contrastive Video...[2109.11593] | - | AI 论文精读 | [2109.11593](https://arxiv.org/abs/2109.11593) | - | 6:09 | [link](https://www.bilibili.com/video/BV1pQ4y1Q74S) |
| 394 | [论文简析]Vi2CLR: Video and Image for Visual Contrastive Learning of Representation | - | AI 论文精读 | - | - | 9:12 | [link](https://www.bilibili.com/video/BV1ZQ4y1i7Wa) |
| 395 | [论文速览]Generative Modeling by Estimating Gradients of the Data Dist[1907.05600] | - | AI 论文精读 | [1907.05600](https://arxiv.org/abs/1907.05600) | [github.com](https://github.com/ermongroup/ncsn) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 17:52 | [link](https://www.bilibili.com/video/BV1WY4y1Q7fy) |
| 396 | [论文简析]Unsupervised Learning of Object Keypoints for Perception..[1906.11883] | - | AI 论文精读 | [1906.11883](https://arxiv.org/abs/1906.11883) | [github.com](https://github.com/deepmind/deepmind-research/tree/master/transporter) | 11:17 | [link](https://www.bilibili.com/video/BV15w411R7rB) |
| 397 | [论文简析]Progressive Stage-wise Learning for Unsupervised Feature.. [2106.05554] | - | AI 论文精读 | [2106.05554](https://arxiv.org/abs/2106.05554) | - | 7:39 | [link](https://www.bilibili.com/video/BV1Fq4y1p7Ai) |
| 398 | [论文简析]Transf. Meta-learners for Implicit Neural Representations[2208.02801] | - | AI 论文精读 | [2208.02801](https://arxiv.org/abs/2208.02801) | [yinboc.github.io](https://yinboc.github.io/trans-inr) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 9:59 | [link](https://www.bilibili.com/video/BV1QV4y167S7) |
| 399 | [论文速览]Jigsaw Clustering for Unsupervised Visual Representation Learn[2104.00323] | - | AI 论文精读 | [2104.00323](https://arxiv.org/abs/2104.00323) | [github.com](https://github.com/dvlab-research/JigsawClustering) | 5:32 | [link](https://www.bilibili.com/video/BV1Jg41177uE) |
| 400 | [论文速览]SS Video Representation Learning by Context&Motion Decoupling[2104.00862] | - | AI 论文精读 | [2104.00862](https://arxiv.org/abs/2104.00862) | - | 8:28 | [link](https://www.bilibili.com/video/BV1qf4y157DW) |
| 401 | [论文简析]MixMAE & Mixed AE[2205.13137][2303.17152] | - | AI 论文精读 | [2205.13137](https://arxiv.org/abs/2205.13137) | [github.com](https://github.com/Sense-X/MixMIM) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 14:16 | [link](https://www.bilibili.com/video/BV1cF411d77x) |
| 402 | [论文速览]Finite Scalar Quantization: VQ-VAE Made Simple[2309.15505] | - | AI 论文精读 | [2309.15505](https://arxiv.org/abs/2309.15505) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 5:26 | [link](https://www.bilibili.com/video/BV1N84y1S779) |
| 403 | [论文简析]DropPos: Pre-Training ViTs by Reconstructing Dropped Positions[2309.03576] | - | AI 论文精读 | [2309.03576](https://arxiv.org/abs/2309.03576) | [github.com](https://github.com/Haochen-Wang409/DropPos) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 6:22 | [link](https://www.bilibili.com/video/BV1fu411u77K) |
| 404 | [论文速览]SODA: Bottleneck Diffusion Models for Representation Learning[2311.17901] | - | AI 论文精读 | [2311.17901](https://arxiv.org/abs/2311.17901) | [soda-diffusion.github.io](https://soda-diffusion.github.io/) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 13:59 | [link](https://www.bilibili.com/video/BV1jw411t7Kq) |
| 405 | [论文简析]Deconstructing Denoising Diffusion Models for SSL[2401.14404] | - | AI 论文精读 | [2401.14404](https://arxiv.org/abs/2401.14404) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 30:00 | [link](https://www.bilibili.com/video/BV1bv421r7Sv) |
| 406 | [论文速览]Socratic Models: Zero-Shot Multimodal Reasoning[2204.00598] | - | AI 论文精读 | [2204.00598](https://arxiv.org/abs/2204.00598) | [github.com](https://github.com/google-research/google-research/tree/master/socraticmodels) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 11:32 | [link](https://www.bilibili.com/video/BV1cS4y1n7yn) |
| 407 | [论文简析]Large Language Models as General Pattern Machines[2307.04721] | - | AI 论文精读 | [2307.04721](https://arxiv.org/abs/2307.04721) | [general-pattern-machines.github.io](https://general-pattern-machines.github.io/) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 15:46 | [link](https://www.bilibili.com/video/BV1EM4y1W7w1) |
| 408 | [论文速览]LaFTer: Label-Free Tuning of Zero-shot Classifier...[2305.18287] | - | AI 论文精读 | [2305.18287](https://arxiv.org/abs/2305.18287) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 6:52 | [link](https://www.bilibili.com/video/BV1Rm4y1p72G) |
| 409 | [论文速览]OWL-ViT: Simple Open-Vocabulary Object Detection with ViT[2205.06230] | - | AI 论文精读 | [2205.06230](https://arxiv.org/abs/2205.06230) | [github.com](https://github.com/google-research/scenic/tree/main/scenic/projects/owl_vit) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 7:45 | [link](https://www.bilibili.com/video/BV1x8411S7eZ) |
| 410 | [论文简析]GroupViT: Semantic Segmentation Emerges from Text Supervision[2202.11094] | - | AI 论文精读 | [2202.11094](https://arxiv.org/abs/2202.11094) | [jerryxu.net](https://jerryxu.net/GroupViT/) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 11:09 | [link](https://www.bilibili.com/video/BV1Bv4y127gH) |
| 411 | [论文简析]VATT: Video-Audio-Text Transformer[2104.11178] | - | AI 论文精读 | [2104.11178](https://arxiv.org/abs/2104.11178) | - | 11:59 | [link](https://www.bilibili.com/video/BV1554y1j71k) |
| 412 | [论文简析]End-to-End Video-Language Transformers..Masked Visual-token..[2111.12681] | - | AI 论文精读 | [2111.12681](https://arxiv.org/abs/2111.12681) | [github.com](https://github.com/tsujuifu/) | 9:09 | [link](https://www.bilibili.com/video/BV1UM4y1c7fh) |
| 413 | [论文简析]TAN: Temporal Alignment Networks for Long-term Video[2204.02968] | - | AI 论文精读 | [2204.02968](https://arxiv.org/abs/2204.02968) | [github.com](https://github.com/TengdaHan/TemporalAlignNet) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 16:21 | [link](https://www.bilibili.com/video/BV1194y1y7mF) |
| 414 | [论文简析]Improving fine-grained understanding in image-text pre-training[2401.0986] | - | AI 论文精读 | [2401.09865](https://arxiv.org/abs/2401.09865) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 17:36 | [link](https://www.bilibili.com/video/BV15A4m1G7zj) |
| 415 | [论文简析]End-to-End Learning... from Uncurated Instructional Videos[1912.06430] | - | AI 论文精读 | [1912.06430](https://arxiv.org/abs/1912.06430) | [di.ens.fr](https://www.di.ens.fr/willow/research/mil-nce/) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 8:59 | [link](https://www.bilibili.com/video/BV173411u7JE) |
| 416 | [论文简析]Region-Aware Pretraining for Open-Vocab. Object Det. w/ ViT[2305.07011] | - | AI 论文精读 | [2305.07011](https://arxiv.org/abs/2305.07011) | [github.com](https://github.com/google-research/google-research/tree/master/fvlm/rovit) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 8:11 | [link](https://www.bilibili.com/video/BV1D14y1C7m8) |
| 417 | [论文简析]Toolformer: Language Models Can Teach Themselves to Use Tools[2302.04761] | - | AI 论文精读 | [2302.04761](https://arxiv.org/abs/2302.04761) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 13:09 | [link](https://www.bilibili.com/video/BV1BV4y1a7iU) |
| 418 | [论文速览]ViperGPT: Visual Inference via Python Execution for Reasoning[2303.08128] | - | AI 论文精读 | [2303.08128](https://arxiv.org/abs/2303.08128) | [viper.cs.columbia.edu](https://viper.cs.columbia.edu/) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 5:59 | [link](https://www.bilibili.com/video/BV1BV4y1879K) |
| 419 | [论文简析]VoxPoser: Composable 3D Value Maps for Robotic...[2307.05973] | - | AI 论文精读 | [2307.05973](https://arxiv.org/abs/2307.05973) | [voxposer.github.io](https://voxposer.github.io/) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 13:04 | [link](https://www.bilibili.com/video/BV11h4y1j7D2) |
| 420 | [论文速览]LLaMA-Adapter: Efficient Fine-tuning..Zero-init Attention[2303.16199] | - | AI 论文精读 | [2303.16199](https://arxiv.org/abs/2303.16199) | [github.com](https://github.com/OpenGVLab/LLaMA-Adapter) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 4:22 | [link](https://www.bilibili.com/video/BV1Kp4y1L7ya) |
| 421 | [论文速览]Open-vocabulary Object Segmentation with Diffusion Models[2301.05221] | - | AI 论文精读 | [2301.05221](https://arxiv.org/abs/2301.05221) | [lipurple.github.io](https://lipurple.github.io/Grounded_Diffusion/) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 9:20 | [link](https://www.bilibili.com/video/BV1VV4y1e78c) |
| 422 | [论文速览]Open Vocab. Semantic Seg.  with Patch Aligned Contrastive...[2212.04994] | - | AI 论文精读 | [2212.04994](https://arxiv.org/abs/2212.04994) | [github.com](https://github.com/kahnchana/clippy) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 4:32 | [link](https://www.bilibili.com/video/BV1w94y1z7ey) |
| 423 | [论文简析]Representation Learning via Global Temporal Alignment and ...[2105.05217] | - | AI 论文精读 | [2105.05217](https://arxiv.org/abs/2105.05217) | [github.com](https://github.com/hadjisma/VideoAlignment) | 14:30 | [link](https://www.bilibili.com/video/BV1CM4y1T7nj) |
| 424 | [论文速览]LLaVA: Visual Instruction Tuning[2304.08485] | - | AI 论文精读 | [2304.08485](https://arxiv.org/abs/2304.08485) | [llava-vl.github.io](https://llava-vl.github.io/) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 9:33 | [link](https://www.bilibili.com/video/BV1n14y1k7B9) |
| 425 | [论文速览]LongLoRA: Efficient Fine-tuning of Long-Context LLMs[2309.12307] | - | AI 论文精读 | [2309.12307](https://arxiv.org/abs/2309.12307) | [github.com](https://github.com/dvlab-research/LongLoRA) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 5:04 | [link](https://www.bilibili.com/video/BV1PN411n7KX) |
| 426 | [论文简析]CLIP Dense Inference Yields Open-Vocab ... For-Free[2309.14289] | - | AI 论文精读 | [2309.14289](https://arxiv.org/abs/2309.14289) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 5:51 | [link](https://www.bilibili.com/video/BV1Jj41187We) |
| 427 | [论文速览]Ferret: Refer and Ground Anything Anywhere at Any Granularity[2310.07704] | - | AI 论文精读 | [2310.07704](https://arxiv.org/abs/2310.07704) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 9:43 | [link](https://www.bilibili.com/video/BV11h4y1z7mn) |
| 428 | [论文速览]VLMs are Zero-Shot Reward Models for RL[2310.12921] | - | AI 论文精读 | [2310.12921](https://arxiv.org/abs/2310.12921) | [sites.google.com](https://sites.google.com/view/vlm-rm) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 4:42 | [link](https://www.bilibili.com/video/BV1ne411R74d) |
| 429 | [论文速览]CRG: Improving Grounding in VLM w/o training[2403.02325] | - | AI 论文精读 | [2403.02325](https://arxiv.org/abs/2403.02325) | [contrastive-region-guidance.github.io](https://contrastive-region-guidance.github.io/) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 5:24 | [link](https://www.bilibili.com/video/BV1y2421T7R3) |
| 430 | [论文速览]A Simple LLM Framework for Long-Range Video Question-Answering[2312.17235] | - | AI 论文精读 | [2312.17235](https://arxiv.org/abs/2312.17235) | [github.com](https://github.com/CeeZh/LLoVi) [lilianweng.github.io](https://lilianweng.github.io/posts/2023-06-23-agent/) [github.com](https://github.com/L1Xu4n/Awesome-ChatGPT-prompts-ZH_CN) | 12:22 | [link](https://www.bilibili.com/video/BV1d2421N7VA) |
| 431 | [论文速览]Align before Fuse / ALBEF: ...[2107.07651] | - | AI 论文精读 | [2107.07651](https://arxiv.org/abs/2107.07651) | [github.com](https://github.com/salesforce/ALBEF/) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 13:16 | [link](https://www.bilibili.com/video/BV1fx4y1U7ui) |
| 432 | [论文速览]Bootstrapping Language-Image Pre-training...[2201.12086] | - | AI 论文精读 | [2201.12086](https://arxiv.org/abs/2201.12086) | [github.com](https://github.com/salesforce/BLIP) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 11:26 | [link](https://www.bilibili.com/video/BV1H1421Q7Ft) |
| 433 | [论文速览]BLIP-2 ...with Frozen Image Encoders and Large Language Models[2301.12597] | - | AI 论文精读 | [2301.12597](https://arxiv.org/abs/2301.12597) | [github.com](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 13:43 | [link](https://www.bilibili.com/video/BV1Ci42197ab) |
| 434 | [论文速览]Ferret-v2: An Improved...for Referring and Grounding with LLMs[2404.07973] | - | AI 论文精读 | [2404.07973](https://arxiv.org/abs/2404.07973) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 9:30 | [link](https://www.bilibili.com/video/BV12F4m1N7Mc) |
| 435 | [论文速览]Token Turing Machines[2211.09119] | - | AI 论文精读 | [2211.09119](https://arxiv.org/abs/2211.09119) | [michaelryoo.com](http://michaelryoo.com/) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 5:08 | [link](https://www.bilibili.com/video/BV1dV4y1f7J4) |
| 436 | [论文简析]NeRF in the Wild: NeRF for Unconstrained Photo Collections[2008.02268] | - | AI 论文精读 | [2008.02268](https://arxiv.org/abs/2008.02268) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 17:07 | [link](https://www.bilibili.com/video/BV1iD4y1e7K9) |
| 437 | [论文简析]Exploring Self-attention for Image Recognition[2004.13621] | - | AI 论文精读 | [2004.13621](https://arxiv.org/abs/2004.13621) | [github.com](https://github.com/hszhao/SAN) [youtube.com](https://www.youtube.com/watch?v=GuAsn4E3fP8) | 16:31 | [link](https://www.bilibili.com/video/BV1nA411K7Z6) |
| 438 | [论文简析]FlowNet3D: Learning Scene Flow in 3D Point Clouds[1806.01411] | - | AI 论文精读 | [1806.01411](https://arxiv.org/abs/1806.01411) | [github.com](https://github.com/xingyul/flownet3d) | 13:05 | [link](https://www.bilibili.com/video/BV1U3411j7Fg) |
| 439 | [论文简析]NeRV: Neural Representations for Videos[2110.13903] | - | AI 论文精读 | [2110.13903](https://arxiv.org/abs/2110.13903) | [github.com](https://github.com/haochen-rye/NeRV) | 8:34 | [link](https://www.bilibili.com/video/BV1Nf4y1K7j5) |
| 440 | [论文简析]TokenLearner: What Can 8 Learned Tokens Do for Images and vids[2106.11297] | - | AI 论文精读 | [2106.11297](https://arxiv.org/abs/2106.11297) | - | 11:15 | [link](https://www.bilibili.com/video/BV1of4y1t77m) |
| 441 | [论文简析]BiFormer: Vision Transformer with Bi-Level Routing Attention[2303.08810] | - | AI 论文精读 | [2303.08810](https://arxiv.org/abs/2303.08810) | [github.com](https://github.com/rayleizhu/BiFormer) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 6:47 | [link](https://www.bilibili.com/video/BV1tF4111774) |
| 442 | [论文简析]When Shift Operation Meets Vision Transformer[2201.10801] | - | AI 论文精读 | [2201.10801](https://arxiv.org/abs/2201.10801) | - | 5:59 | [link](https://www.bilibili.com/video/BV1CF411n7at) |
| 443 | [论文简析]DeepLab V3/V3+[1706.05587/1802.02611] | - | AI 论文精读 | - | - | 10:36 | [link](https://www.bilibili.com/video/BV1by4y1g76s) |
| 444 | [论文速览]Deformable Convolutional Networks; DCN[1703.06211] | - | AI 论文精读 | [1703.06211](https://arxiv.org/abs/1703.06211) | [github.com](https://github.com/msracver/Deformable-ConvNets) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 9:53 | [link](https://www.bilibili.com/video/BV1C94y1272t) |
| 445 | [论文简析]DeepLab: Semantic Image Segmentation with DCN..[1606.00915] | - | AI 论文精读 | [1606.00915](https://arxiv.org/abs/1606.00915) | - | 16:28 | [link](https://www.bilibili.com/video/BV1jf4y1Y7uM) |
| 446 | [论文简析]DAT: Vision Transformer with Deformable Attention[2201.00520] | - | AI 论文精读 | [2201.00520](https://arxiv.org/abs/2201.00520) | [github.com](https://github.com/LeapLabTHU/DAT) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 7:00 | [link](https://www.bilibili.com/video/BV1ir4y137BG) |
| 447 | [论文速览]Aggregating Nested Transformers[2105.12723] | - | AI 论文精读 | [2105.12723](https://arxiv.org/abs/2105.12723) | [github.com](https://github.com/google-research/nested-transformer) | 7:41 | [link](https://www.bilibili.com/video/BV1yq4y1H7mT) |
| 448 | [论文简析]X3D: Expanding Architectures for Efficient Video Recognition[2004.04730] | - | AI 论文精读 | [2004.04730](https://arxiv.org/abs/2004.04730) | [github.com](https://github.com/facebookresearch/SlowFast) | 4:07 | [link](https://www.bilibili.com/video/BV1qZ4y1F7Kf) |
| 449 | [论文简析]CeiT: Incorporating Convolution Designs into Visual Tr[2103.11816] | - | AI 论文精读 | [2103.11816](https://arxiv.org/abs/2103.11816) | [github.com](https://github.com/rishikksh20/CeiT-pytorch) | 5:57 | [link](https://www.bilibili.com/video/BV19L4y1B7Ad) |
| 450 | [论文速览]iFormer: Inception Transformer[2205.12956] | - | AI 论文精读 | [2205.12956](https://arxiv.org/abs/2205.12956) | [github.com](https://github.com/sail-sg/iFormer) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 6:25 | [link](https://www.bilibili.com/video/BV19L4y1P7ri) |
| 451 | [论文速览]Bottleneck Transformers for Visual Recognition[2101.11605] | - | AI 论文精读 | [2101.11605](https://arxiv.org/abs/2101.11605) | - | 2:10 | [link](https://www.bilibili.com/video/BV1i64y1t7WN) |
| 452 | [论文简析]NAT: Neighborhood Attention Transformer[2204.07143] | - | AI 论文精读 | [2204.07143](https://arxiv.org/abs/2204.07143) | [github.com](https://github.com/SHI-) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 5:14 | [link](https://www.bilibili.com/video/BV1xF411g7LK) |
| 453 | [论文简析]XCiT: Cross-Covariance Image Transformers[2106.09681] | - | AI 论文精读 | [2106.09681](https://arxiv.org/abs/2106.09681) | [github.com](https://github.com/facebookresearch/xcit) | 10:17 | [link](https://www.bilibili.com/video/BV1n64y1Q7RX) |
| 454 | [论文简析]DeiT: Data-efficient Image Transformers[2012.12877] | - | AI 论文精读 | - | [github.com](https://github.com/facebookresearch/deit) | 9:49 | [link](https://www.bilibili.com/video/BV1L5411P7rV) |
| 455 | [论文简析]TNT: Transformer in Transformer[2103.00112] | - | AI 论文精读 | [2103.00112](https://arxiv.org/abs/2103.00112) | [github.com](https://github.com/lucidrains/transformer-in-transformer) | 7:17 | [link](https://www.bilibili.com/video/BV1KK4y1U7Uq) |
| 456 | [论文简析]Tokens-to-Token ViT: Training ViT from Scratch on ImageNet[2101.11986] | - | AI 论文精读 | [2101.11986](https://arxiv.org/abs/2101.11986) | [github.com](https://github.com/yitu-opensource/T2T-ViT) | 4:16 | [link](https://www.bilibili.com/video/BV1yv411L7xN) |
| 457 | [论文简析]Dynamic Vision Transformers with Adaptive Sequence Length[2105.15075] | - | AI 论文精读 | [2105.15075](https://arxiv.org/abs/2105.15075) | [github.com](https://github.com/blackfeather-wang/Dynamic-Vision-Transformer) | 12:21 | [link](https://www.bilibili.com/video/BV1s54y1H7Wb) |
| 458 | [论文简析]SlowFast Networks for Video Recognition[1812.03982] | - | AI 论文精读 | [1812.03982](https://arxiv.org/abs/1812.03982) | [github.com](https://github.com/facebookresearch/SlowFast) | 9:35 | [link](https://www.bilibili.com/video/BV1DV411J7gS) |
| 459 | [论文简析]MViT: Multiscale Vision Transformers[2104.11227] | - | AI 论文精读 | [2104.11227](https://arxiv.org/abs/2104.11227) | [github.com](https://github.com/facebookresearch/SlowFast) | 12:31 | [link](https://www.bilibili.com/video/BV1np4y1b7QY) |
| 460 | [论文简析]BEVT: BERT Pretraining of Video Transformers[2112.01529] | - | AI 论文精读 | [2112.01529](https://arxiv.org/abs/2112.01529) | - | 10:23 | [link](https://www.bilibili.com/video/BV1R44y1h7CR) |
| 461 | [论文简析]Unified Transformer for Efficient Spatiotemporal...[2201.04676] | - | AI 论文精读 | [2201.04676](https://arxiv.org/abs/2201.04676) | [github.com](https://github.com/Sense-X/UniFormer) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 6:28 | [link](https://www.bilibili.com/video/BV1CT4y1i7Fa) |
| 462 | [论文简析]MLP-Mixer: An all-MLP Architecture for Vision[2105.01601] | - | AI 论文精读 | [2105.01601](https://arxiv.org/abs/2105.01601) | [github.com](https://github.com/google-research/vision_transformer/tree/linen) | 9:25 | [link](https://www.bilibili.com/video/BV1xK4y197qL) |
| 463 | [论文速览]EViT: Expediting Vision Transformers via Token Reorganizations[2202.07800] | - | AI 论文精读 | [2202.07800](https://arxiv.org/abs/2202.07800) | [github.com](https://github.com/youweiliang/evit) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 4:24 | [link](https://www.bilibili.com/video/BV1HS4y1F7nU) |
| 464 | [论文简析]Is Space-Time Attention All You Need for Video Understanding?[2102.05095] | - | AI 论文精读 | [2102.05095](https://arxiv.org/abs/2102.05095) | [github.com](https://github.com/facebookresearch/TimeSformer) | 4:34 | [link](https://www.bilibili.com/video/BV1dA411371w) |
| 465 | [论文简析]A Laplacian Pyramid Translation Network[2105.09188] | - | AI 论文精读 | [2105.09188](https://arxiv.org/abs/2105.09188) | [github.com](https://github.com/csjliang/LPTN) | 16:12 | [link](https://www.bilibili.com/video/BV1V64y1h7nv) |
| 466 | [论文简析]Per-Pixel Classification is Not All You Need for Semantic Seg[2107.06278] | - | AI 论文精读 | [2107.06278](https://arxiv.org/abs/2107.06278) | [bowenc0221.github.io](https://bowenc0221.github.io/maskformer/) | 10:29 | [link](https://www.bilibili.com/video/BV17f4y1A7XR) |
| 467 | [论文速览]Masked-attention Mask Tr. for Universal Image Segmentation[2112.01527] | - | AI 论文精读 | - | [bowenc0221.github.io](https://bowenc0221.github.io/mask2former/) | 8:02 | [link](https://www.bilibili.com/video/BV1ob4y1B7hp) |
| 468 | [论文简析]MobileNets: Efficient CNN for Mobile Vision Applications[1704.04861] | - | AI 论文精读 | [1704.04861](https://arxiv.org/abs/1704.04861) | - | 6:03 | [link](https://www.bilibili.com/video/BV1LB4y1c7Ap) |
| 469 | [论文简析]MobileNet V2: Inverted Residuals and Linear Bottlenecks[1801.04381] | - | AI 论文精读 | [1801.04381](https://arxiv.org/abs/1801.04381) | - | 10:30 | [link](https://www.bilibili.com/video/BV1Fq4y1n7Mq) |
| 470 | [论文简析]Searching for MobileNet V3[1905.02244] | - | AI 论文精读 | [1905.02244](https://arxiv.org/abs/1905.02244) | - | 8:04 | [link](https://www.bilibili.com/video/BV1vN411f7pY) |
| 471 | [论文简析]MnasNet: Platform-Aware Neural Architecture Search for Mobile[1807.11626] | - | AI 论文精读 | [1807.11626](https://arxiv.org/abs/1807.11626) | [github.com](https://github.com/tensorflow/tpu/tree/master/models/official/mnasnet) | 7:55 | [link](https://www.bilibili.com/video/BV1Wo4y127NM) |
| 472 | [论文简析]EfficientNet V1/V2[1905.11946/2104.00298] | - | AI 论文精读 | [1905.11946](https://arxiv.org/abs/1905.11946) | - | 13:29 | [link](https://www.bilibili.com/video/BV1MV411E7Pq) |
| 473 | [论文简析]Mobile-Former: Bridging MobileNet and Transformer[2108.05895] | - | AI 论文精读 | [2108.05895](https://arxiv.org/abs/2108.05895) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 13:49 | [link](https://www.bilibili.com/video/BV1CL4y1g76U) |
| 474 | [论文简析]Point Transformer[2012.09164] | - | AI 论文精读 | [2012.09164](https://arxiv.org/abs/2012.09164) | - | 11:54 | [link](https://www.bilibili.com/video/BV1PA41157su) |
| 475 | [论文简析]Point Transformer V2[2210.05666] | - | AI 论文精读 | [2210.05666](https://arxiv.org/abs/2210.05666) | [github.com](https://github.com/Gofinge/PointTransformerV2) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 10:36 | [link](https://www.bilibili.com/video/BV1de4y157hR) |
| 476 | [论文速览]RetNet: A Successor to Transformer for Large Language Models[2307.08621] | - | AI 论文精读 | [2307.08621](https://arxiv.org/abs/2307.08621) | [github.com](https://github.com/microsoft/torchscale) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 24:49 | [link](https://www.bilibili.com/video/BV1134y1G7uQ) |
| 477 | [论文简析]Vision Transformers Need Registers[2309.16588] | - | AI 论文精读 | [2309.16588](https://arxiv.org/abs/2309.16588) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 6:57 | [link](https://www.bilibili.com/video/BV1up4y1c7JU) |
| 478 | [论文简析]Contrastive Learning for Unpaired Image-to-Image Translation[2007.15651] | - | AI 论文精读 | [2007.15651](https://arxiv.org/abs/2007.15651) | [github.com](https://github.com/taesungp/contrastive-unpaired-translation) | 17:20 | [link](https://www.bilibili.com/video/BV14y4y1s7tS) |
| 479 | [论文简析]Multimodal Unsupervised Image-to-Image Translation[1804.04732] | - | AI 论文精读 | [1804.04732](https://arxiv.org/abs/1804.04732) | [github.com](https://github.com/nvlabs/MUNIT) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 12:51 | [link](https://www.bilibili.com/video/BV1Pb4y1p78y) |
| 480 | [论文速览]Rethinking the Truly Unsupervised Image-to-Image Translation[2006.06500] | - | AI 论文精读 | [2006.06500](https://arxiv.org/abs/2006.06500) | [github.com](https://github.com/clovaai/tunit) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 10:09 | [link](https://www.bilibili.com/video/BV1qZ4y1z77v) |
| 481 | [论文简析]Unsupervised Image-to-Image Translation Networks[1703.00848] | - | AI 论文精读 | [1703.00848](https://arxiv.org/abs/1703.00848) | [github.com](https://github.com/mingyuliutw/unit) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 9:43 | [link](https://www.bilibili.com/video/BV1c34y187BW) |
| 482 | [论文简析]RetinaGAN: An Object-aware Approach to Sim-to-Real Transfer[2011.03148] | - | AI 论文精读 | [2011.03148](https://arxiv.org/abs/2011.03148) | - | 11:29 | [link](https://www.bilibili.com/video/BV17o4y1X7Mk) |
| 483 | [论文简析]MoCoGAN-HD: A Good Image Generator Is What You Need...[2104.15069] | - | AI 论文精读 | [2104.15069](https://arxiv.org/abs/2104.15069) | [github.com](https://github.com/snap-research/MoCoGAN-HD) | 14:06 | [link](https://www.bilibili.com/video/BV1gv411L7Dy) |
| 484 | [论文简析]VQ-VAE:Neural discrete representation learning[1711.00937] | - | AI 论文精读 | [1711.00937](https://arxiv.org/abs/1711.00937) | - | 16:54 | [link](https://www.bilibili.com/video/BV1bb4y1i7j6) |
| 485 | [论文速览]Autoregressive Image Generation using Residual Quantization[2203.01941] | - | AI 论文精读 | [2203.01941](https://arxiv.org/abs/2203.01941) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 21:26 | [link](https://www.bilibili.com/video/BV1gY411E7ge) |
| 486 | [论文速览]Personalizing Text2Img Generation using Textual Inversion[2208.01618] | - | AI 论文精读 | [2208.01618](https://arxiv.org/abs/2208.01618) | [textual-inversion.github.io](https://textual-inversion.github.io/) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 4:39 | [link](https://www.bilibili.com/video/BV1oH4y1k7RW) |
| 487 | [论文速览]Taming Transformers for High-Resolution Image Synthesis[2012.09841] | - | AI 论文精读 | [2012.09841](https://arxiv.org/abs/2012.09841) | [git.io](https://git.io/JnyvK) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 6:14 | [link](https://www.bilibili.com/video/BV1ym4y1d7iP) |
| 488 | [论文简析]MaskGIT: Masked Generative Image Transformer[2202.04200] | - | AI 论文精读 | [2202.04200](https://arxiv.org/abs/2202.04200) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 9:00 | [link](https://www.bilibili.com/video/BV1qS4y1r7p1) |
| 489 | [论文简析]Regularized Vector Quantization for Tokenized Image Synthesis[2303.06424] | - | AI 论文精读 | [2303.06424](https://arxiv.org/abs/2303.06424) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 9:28 | [link](https://www.bilibili.com/video/BV1rG411o7pp) |
| 490 | [论文速览]Denoising Diffusion Probabilistic Models / DDPM[2006.11239] | - | AI 论文精读 | [2006.11239](https://arxiv.org/abs/2006.11239) | [github.com](https://github.com/hojonathanho/diffusion) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 31:44 | [link](https://www.bilibili.com/video/BV1yA41167Dg) |
| 491 | [论文速览]Denoising Diffusion Implicit Models / DDIM[2010.02502] | - | AI 论文精读 | [2010.02502](https://arxiv.org/abs/2010.02502) | [github.com](https://github.com/ermongroup/ddim) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 8:51 | [link](https://www.bilibili.com/video/BV1ic41157Vf) |
| 492 | [论文速览]Structured Denoising Diffusion Models in Discrete State-Spaces[2107.03006] | - | AI 论文精读 | [2107.03006](https://arxiv.org/abs/2107.03006) | [github.com](https://github.com/google-research/google-research/tree/master/d3pm) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 19:17 | [link](https://www.bilibili.com/video/BV1R84y1H7k1) |
| 493 | [论文速览]Drag Your GAN: Interactive Point-based Manipulation...[2305.10973] | - | AI 论文精读 | [2305.10973](https://arxiv.org/abs/2305.10973) | [vcai.mpi-inf.mpg.de](https://vcai.mpi-inf.mpg.de/projects/DragGAN/) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 10:30 | [link](https://www.bilibili.com/video/BV1Ju41177k3) |
| 494 | [论文简析]DreamBooth: Fine Tuning Text-to-Image Diffusion Models...[2208.12242] | - | AI 论文精读 | [2208.12242](https://arxiv.org/abs/2208.12242) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 7:55 | [link](https://www.bilibili.com/video/BV18m4y1H7fs) |
| 495 | [论文速览]FreeU: Free Lunch in Diffusion U-Net[2309.11497] | - | AI 论文精读 | [2309.11497](https://arxiv.org/abs/2309.11497) | [chenyangsi.top](https://chenyangsi.top/FreeU/) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 4:53 | [link](https://www.bilibili.com/video/BV1dk4y1F7dg) |
| 496 | [论文简析]Visual Autoregressive Modeling: ...via Next-Scale Prediction[2404.02905] | - | AI 论文精读 | [2404.02905](https://arxiv.org/abs/2404.02905) | [github.com](https://github.com/FoundationVision/VAR) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 28:12 | [link](https://www.bilibili.com/video/BV1pq421P7D4) |
| 497 | [论文速览]MixUp: Beyond Empirical Risk Minimization[1710.09412] | - | AI 论文精读 | [1710.09412](https://arxiv.org/abs/1710.09412) | [github.com](https://github.com/facebookresearch/mixup-cifar10) | 6:57 | [link](https://www.bilibili.com/video/BV12q4y167SV) |
| 498 | [论文速览]RegMixup: Mixup as a Regularizer Can Surprisingly Improve...[2206.14502] | - | AI 论文精读 | [2206.14502](https://arxiv.org/abs/2206.14502) | [github.com](https://github.com/FrancescoPinto/RegMixup) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 9:40 | [link](https://www.bilibili.com/video/BV1jB4y1i7iw) |
| 499 | [论文夕拾]Mixed Sample Data Augmentations, Part 1 | - | AI 论文精读 | [2106.07085](https://arxiv.org/abs/2106.07085) | [openaccess.thecvf.com](https://openaccess.thecvf.com/content_CVPRW_2020/papers/w45/Lee_SmoothMix_A_Simple_Yet_Effective_Data_Augmentation_to_Train_Robust_CVPRW_2020_paper.pdf) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 17:51 | [link](https://www.bilibili.com/video/BV1rr4y1V7Dx) |
| 500 | [论文夕拾]Mixed Sample Data Augmentations, Part 2 | - | AI 论文精读 | [2106.07085](https://arxiv.org/abs/2106.07085) | [github.com](https://github.com/JunlinHan/CropMix) [github.com](https://github.com/SaliencyMix/SaliencyMix) [github.com](https://github.com/snu-mllab/PuzzleMix) | 6:20 | [link](https://www.bilibili.com/video/BV1qt4y1h7kM) |
| 501 | [论文简析]Robust and Generalizable Visual ... via Random Convolutions[2007.13003] | - | AI 论文精读 | [2007.13003](https://arxiv.org/abs/2007.13003) | [github.com](https://github.com/wildphoton/RandConv) | 3:57 | [link](https://www.bilibili.com/video/BV1Kq4y1E7j3) |
| 502 | [论文速览]Simple Copy-Paste is a Strong Data Aug. for Instance Seg.[2012.07177] | - | AI 论文精读 | [2012.07177](https://arxiv.org/abs/2012.07177) | - | 3:11 | [link](https://www.bilibili.com/video/BV1Hq4y1s7wB) |
| 503 | [论文速览]Visual Prompt Tuning / VPT[2203.12119] | - | AI 论文精读 | [2203.12119](https://arxiv.org/abs/2203.12119) | [github.com](https://github.com/kmnp/vpt) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 3:00 | [link](https://www.bilibili.com/video/BV18h4y127GG) |
| 504 | [论文简析]Red Circle: Visual Prompt Engineering for VLMs[2304.06712] | - | AI 论文精读 | [2304.06712](https://arxiv.org/abs/2304.06712) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 10:33 | [link](https://www.bilibili.com/video/BV1wk4y1V7wo) |
| 505 | [论文简析]Finding an Unsupervised Image Segmenter in .. Generative Model[2105.08127] | - | AI 论文精读 | [2105.08127](https://arxiv.org/abs/2105.08127) | - | 10:38 | [link](https://www.bilibili.com/video/BV1Dy4y1W7uM) |
| 506 | [论文简析]PolyFormer: Referring Image Seg. as Sequential Polygon Gen [2302.07387] | - | AI 论文精读 | [2302.07387](https://arxiv.org/abs/2302.07387) | [polyformer.github.io](https://polyformer.github.io/) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 10:54 | [link](https://www.bilibili.com/video/BV1wr4y1o7V5) |
| 507 | [论文简析]DiffSeg: Unsupervised Zero-Shot Seg. using Stable Diffusion[2308.12469] | - | AI 论文精读 | [2308.12469](https://arxiv.org/abs/2308.12469) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 13:20 | [link](https://www.bilibili.com/video/BV1Sm4y1T74R) |
| 508 | [论文简析]Patching Open-Vocabulary Models by Interpolating Weights[2208.05592] | - | AI 论文精读 | [2208.05592](https://arxiv.org/abs/2208.05592) | [github.com](https://github.com/mlfoundations/patching) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 12:55 | [link](https://www.bilibili.com/video/BV1tV411P73W) |
| 509 | [论文速览]Scalable Video Object Segmentation with Simplified Framework[2308.09903] | - | AI 论文精读 | [2308.09903](https://arxiv.org/abs/2308.09903) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 8:07 | [link](https://www.bilibili.com/video/BV1Vu411g7Gm) |
| 510 | [论文速览]Learning to Learn with Generative Models of NN Checkpoints[2209.12892] | - | AI 论文精读 | [2209.12892](https://arxiv.org/abs/2209.12892) | [wpeebles.com](https://www.wpeebles.com/Gpt.html) [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | 8:21 | [link](https://www.bilibili.com/video/BV13H4y1j7Zd) |
| 511 | 给女朋友做的AR元宇宙增强现实生日贺卡 | - | AI 论文精读 | - | [sketchfab.com](https://sketchfab.com/3d-models/princess-peach-8122299e7adb434c8c7990be3f427561) [sketchfab.com](https://sketchfab.com/3d-models/gaming-guy-room-f6943c83d7af4bd598d1859b326578cf) [sketchfab.com](https://sketchfab.com/3d-models/legend-of-zelda-botw-heart-container-4cbca52ae7fc4654ae2d71438b7eb3f6) | 1:19 | [link](https://www.bilibili.com/video/BV17Y4y1z73F) |
| 512 | MATLAB竟然还能做增强现实AR元宇宙？ | - | AI 论文精读 | - | [github.com](https://github.com/TommyZihao/MATLAB_AR_Tutorials) | 16:30 | [link](https://www.bilibili.com/video/BV1wG41137oJ) |
| 513 | 构建自己的图像分类数据集【两天搞定AI毕设】 | - | AI 论文精读 | - | [github.com](https://github.com/TommyZihao/Train_Custom_Dataset) [featurize.cn](https://featurize.cn/?s=d7ce99f842414bfcaea5662a97581bd1) | 35:07 | [link](https://www.bilibili.com/video/BV1Jd4y1T7rw) |
| 514 | Pytorch预训练图像分类模型识别预测【两天搞定AI毕设】 | - | AI 论文精读 | - | [github.com](https://github.com/TommyZihao/Train_Custom_Dataset) [featurize.cn](https://featurize.cn/?s=d7ce99f842414bfcaea5662a97581bd1) [github.com](https://github.com/open-mmlab/mmclassification) | 37:55 | [link](https://www.bilibili.com/video/BV1qe4y1D7zD) |
| 515 | Pytorch迁移学习训练自己的图像分类模型【两天搞定AI毕设】 | - | AI 论文精读 | - | [github.com](https://github.com/TommyZihao/Train_Custom_Dataset) [featurize.cn](https://featurize.cn/?s=d7ce99f842414bfcaea5662a97581bd1) | 51:15 | [link](https://www.bilibili.com/video/BV1Ng411C7WY) |
| 516 | 用训练得到的pytorch图像分类模型，识别图像、视频、摄像头画面【两天搞定AI毕设】 | - | AI 论文精读 | - | [github.com](https://github.com/TommyZihao/Train_Custom_Dataset) [featurize.cn](https://featurize.cn/?s=d7ce99f842414bfcaea5662a97581bd1) | 16:46 | [link](https://www.bilibili.com/video/BV12d4y1P7xz) |
| 517 | 测试集上评估Pytorch训练得到的图像分类模型【两天搞定AI毕业设计】 | - | AI 论文精读 | - | [github.com](https://github.com/TommyZihao/Train_Custom_Dataset) [featurize.cn](https://featurize.cn/?s=d7ce99f842414bfcaea5662a97581bd1) | 24:49 | [link](https://www.bilibili.com/video/BV1bP411j7NK) |
| 518 | 图像分类测试集语义特征降维可视化 | - | AI 论文精读 | - | [github.com](https://github.com/TommyZihao/Train_Custom_Dataset) [featurize.cn](https://featurize.cn/?s=d7ce99f842414bfcaea5662a97581bd1) | 30:20 | [link](https://www.bilibili.com/video/BV1VB4y1z7xN) |
| 519 | 图像分类可解释性分析实战-CAM热力图系列算法 | - | AI 论文精读 | - | [github.com](https://github.com/TommyZihao/Train_Custom_Dataset) | 46:34 | [link](https://www.bilibili.com/video/BV1JG4y1s74x) |
| 520 | 图像分类可解释性分析实战-Deep Feature Factorization | - | AI 论文精读 | - | [jacobgil.github.io](https://jacobgil.github.io/pytorch-gradcam-book/Deep%20Feature%20Factorizations.html) [github.com](https://github.com/TommyZihao/Train_Custom_Dataset) | 10:50 | [link](https://www.bilibili.com/video/BV1Re4y1n73v) |
| 521 | 图像分类可解释性分析实战-Captum工具包 | - | AI 论文精读 | - | [github.com](https://github.com/TommyZihao/Train_Custom_Dataset) | 13:12 | [link](https://www.bilibili.com/video/BV1DN4y1N7fc) |
| 522 | 图像分类可解释性分析实战-shap工具包 | - | AI 论文精读 | - | [github.com](https://github.com/TommyZihao/Train_Custom_Dataset) | 49:01 | [link](https://www.bilibili.com/video/BV1vP4y1S7Xu) |
| 523 | 图像分类可解释性分析实战-lime工具包 | - | AI 论文精读 | - | [github.com](https://github.com/TommyZihao/zihao_course/blob/main/XAI) [github.com](https://github.com/TommyZihao/Train_Custom_Dataset) | 14:58 | [link](https://www.bilibili.com/video/BV1a84y1i7Tz) |
| 524 | 图像分类模型部署-Pytorch转ONNX | - | AI 论文精读 | - | [github.com](https://github.com/TommyZihao/Train_Custom_Dataset) | 16:41 | [link](https://www.bilibili.com/video/BV1cM4y187Xc) |
| 525 | Pytorch图像分类模型部署-ONNX Runtime本地终端推理 | - | AI 论文精读 | - | [github.com](https://github.com/TommyZihao/Train_Custom_Dataset) | 23:01 | [link](https://www.bilibili.com/video/BV1AM4y187yR) |
| 526 | Pytorch图像分类部署-ONNX Runtime安卓手机APP | - | AI 论文精读 | - | [github.com](https://github.com/TommyZihao/Train_Custom_Dataset) [github.com](https://github.com/microsoft/onnxruntime-inference-examples) [developer.android.com](https://developer.android.com/studio) | 16:33 | [link](https://www.bilibili.com/video/BV1cs4y1Q7nu) |
| 527 | Pytorch图像分类部署-ONNX Runtime浏览器Web前端 | - | AI 论文精读 | - | [github.com](https://github.com/TommyZihao/Train_Custom_Dataset) [onnx.coderai.cn](https://onnx.coderai.cn) [microsoft.github.io](https://microsoft.github.io/onnxruntime-web-demo) | 6:04 | [link](https://www.bilibili.com/video/BV1Ja4y137fZ) |
| 528 | AidLux图像分类部署-安卓鸿蒙高通ARM | - | AI 论文精读 | - | [aimo.aidlux.com](http://aimo.aidlux.com) [github.com](https://github.com/TommyZihao/aidlux_tutorial) [github.com](https://github.com/TommyZihao/Train_Custom_Dataset) | 34:14 | [link](https://www.bilibili.com/video/BV1oN411h7p1) |
| 529 | 文本识别OCR神器 MMOCR【OpenMMLab】 | - | AI 论文精读 | - | [github.com](https://github.com/open-mmlab/mmocr) [openmmlab.com](https://openmmlab.com/) | 15:43 | [link](https://www.bilibili.com/video/BV1Ua411x7dB) |
| 530 | MMOCR代码实战（上）安装配置、预训练OCR模型预测 | - | AI 论文精读 | - | [github.com](https://github.com/open-mmlab/mmocr) [openmmlab.com](https://openmmlab.com/) | 14:02 | [link](https://www.bilibili.com/video/BV1hP4y1M7Zc) |
| 531 | MMOCR代码实战（中）AI给文字区域打马赛克 | - | AI 论文精读 | - | [github.com](https://github.com/open-mmlab/mmocr) [openmmlab.com](https://openmmlab.com/) | 10:50 | [link](https://www.bilibili.com/video/BV1nZ4y1z77X) |
| 532 | MMOCR代码实战（下）Kaggle验证码文本识别 | - | AI 论文精读 | - | [github.com](https://github.com/open-mmlab/mmocr) [openmmlab.com](https://openmmlab.com/) | 10:32 | [link](https://www.bilibili.com/video/BV1tL411A7bj) |
| 533 | Github高赞开源项目速览-AIGC与大语言模型-20230707 | - | AI 论文精读 | - | [github.com](https://github.com/TommyZihao/Awesome) | 22:41 | [link](https://www.bilibili.com/video/BV1eW4y1f72L) |
| 534 | Github高赞开源项目速览-AIGC的N种玩法-20230808 | - | AI 论文精读 | - | [github.com](https://github.com/TommyZihao/Awesome) | 32:27 | [link](https://www.bilibili.com/video/BV1cV411V7LU) |
| 535 | 中医+人工智能黑科技：耳朵穴位经络图像识别 | - | AI 论文精读 | - | [github.com](https://github.com/TommyZihao/PointWise_Body) | 1:24 | [link](https://www.bilibili.com/video/BV168411Z7Lt) |
| 536 | 标注关键点检测数据集 | - | AI 论文精读 | - | - | 46:14 | [link](https://www.bilibili.com/video/BV19g4y1777q) |
| 537 | 关键点检测数据集-Labelme格式转YOLO格式 | - | AI 论文精读 | - | - | 19:54 | [link](https://www.bilibili.com/video/BV1QX4y1B7eF) |
| 538 | 关键点检测数据集-Labelme格式转MS COCO格式 | - | AI 论文精读 | - | - | 25:28 | [link](https://www.bilibili.com/video/BV1vc411J7GC) |
| 539 | YOLOV8关键点检测-预训练模型预测 | - | AI 论文精读 | - | [github.com](https://github.com/TommyZihao/Train_Custom_Dataset) | 36:04 | [link](https://www.bilibili.com/video/BV1yg4y177ef) |
| 540 | YOLOV8关键点检测-训练自己的关键点检测模型 | - | AI 论文精读 | - | [github.com](https://github.com/TommyZihao/Train_Custom_Dataset) | 50:36 | [link](https://www.bilibili.com/video/BV13a4y157HE) |
| 541 | YOLOV8关键点检测-用训练得到的模型预测图像、视频、摄像头画面 | - | AI 论文精读 | - | [github.com](https://github.com/TommyZihao/Train_Custom_Dataset) | 34:15 | [link](https://www.bilibili.com/video/BV1Lo4y1t76s) |
| 542 | YOLOV8关键点检测-预测源码解读 | - | AI 论文精读 | - | [github.com](https://github.com/TommyZihao/Train_Custom_Dataset) | 18:07 | [link](https://www.bilibili.com/video/BV1Yu411t7XF) |
| 543 | YOLOV8关键点检测-ONNX Runtime部署 | - | AI 论文精读 | - | [github.com](https://github.com/TommyZihao/Train_Custom_Dataset) | 21:24 | [link](https://www.bilibili.com/video/BV18L411B7Mv) |
| 544 | 玩转MMPose人体姿态估计关键点检测 | - | AI 论文精读 | - | [github.com](https://github.com/open-mmlab/mmpose) [openmmlab.com](https://openmmlab.com) | 1:01 | [link](https://www.bilibili.com/video/BV16B4y1h7JS) |
| 545 | 开源姿态估计算法库MMPose | - | AI 论文精读 | - | [github.com](https://github.com/open-mmlab/mmpose) [openmmlab.com](https://openmmlab.com) | 33:02 | [link](https://www.bilibili.com/video/BV15B4y1p7Kj) |
| 546 | RTMPose关键点检测-安装MMDetection和MMPose | - | AI 论文精读 | - | - | 15:42 | [link](https://www.bilibili.com/video/BV1Pa4y1g7N7) |
| 547 | RTMPose关键点检测-MMDetection三角板目标检测 | - | AI 论文精读 | - | - | 19:43 | [link](https://www.bilibili.com/video/BV1Lm4y1879K) |
| 548 | RTMPose关键点检测-训练、评估、推理预测 | - | AI 论文精读 | - | - | 17:52 | [link](https://www.bilibili.com/video/BV12a4y1u7sd) |
| 549 | AI画《三体》名场面 | - | AI 论文精读 | - | [github.com](https://github.com/TommyZihao/zihao_AIGC) [midjourney.com](https://www.midjourney.com) [yige.baidu.com](https://yige.baidu.com) | 2:12 | [link](https://www.bilibili.com/video/BV1b14y1W7iq) |
| 550 | AI画我的三体之章北海传 | - | AI 论文精读 | - | [github.com](https://github.com/TommyZihao/zihao_AIGC) | 2:47 | [link](https://www.bilibili.com/video/BV1Ux4y1F7zA) |
| 551 | 如果AI来画清华美院艺考题 | - | AI 论文精读 | - | [decoder.modelscope.cn](https://decoder.modelscope.cn) [modelscope.cn](https://www.modelscope.cn) | 2:12 | [link](https://www.bilibili.com/video/BV1d24y1f7Gi) |
| 552 | 三分钟部署AIGC神器DragGAN | - | AI 论文精读 | - | [growthdata.virtaicloud.com](https://growthdata.virtaicloud.com/t/ea) | 7:39 | [link](https://www.bilibili.com/video/BV1Xw411e7ev) |
| 553 | 斥资500元，我用AI打造的三体科幻微电影《云天明的童话》 | - | AI 论文精读 | - | - | 2:13 | [link](https://www.bilibili.com/video/BV1Xu4y1b7ny) |
| 554 | 石趣绘本园：基于Amazon Bedrock的AIGC交互式童话绘本 | - | AI 论文精读 | - | [aws.amazon.com](https://aws.amazon.com/cn/bedrock/?trk=920b209d-e1e2-4570-b186-008ab8db379e&sc_channel=psm) [github.com](https://github.com/TommyZihao/StoryBook_Bedrock) | 6:16 | [link](https://www.bilibili.com/video/BV1n64y1N7Vz) |
| 555 | 【拜年神器】一键部署阿里开源AI写真 | - | AI 论文精读 | [2308.14256](https://arxiv.org/abs/2308.14256) | [github.com](https://github.com/modelscope/facechain) [modelscope.cn](https://modelscope.cn/studios/CVstudio/cv_human_portrait) [tongyi.aliyun.com](https://tongyi.aliyun.com/wanxiang) | 7:34 | [link](https://www.bilibili.com/video/BV1DZ421B7J9) |
| 556 | 【精读AI论文】知识蒸馏 | - | AI 论文精读 | - | [readpaper.com](https://readpaper.com/paper/1821462560) [openmmlab.com](https://openmmlab.com/) [github.com](https://github.com/open-mmlab/MMRazor) | 64:22 | [link](https://www.bilibili.com/video/BV1gS4y1k7vj) |
| 557 | 知识蒸馏开山之作论文精读：Distilling the knowledge in a neural network | - | AI 论文精读 | - | [readpaper.com](https://readpaper.com/paper/1821462560) | 124:13 | [link](https://www.bilibili.com/video/BV1N44y1n7mU) |
| 558 | 知识蒸馏Pytorch代码实战 | - | AI 论文精读 | - | - | 8:34 | [link](https://www.bilibili.com/video/BV1zP4y1F7g4) |
| 559 | python交互式地图数据可视化神器folium | - | AI 论文精读 | - | [github.com](https://github.com/TommyZihao/folium_tutorials) | 29:05 | [link](https://www.bilibili.com/video/BV1t3411A7Z8) |
| 560 | folium实战-拍照地点分布地图可视化 | - | AI 论文精读 | - | [github.com](https://github.com/TommyZihao/folium_tutorials) | 5:11 | [link](https://www.bilibili.com/video/BV1m3411A786) |
| 561 | folium实战-全球地震与板块运动分布 | - | AI 论文精读 | - | [github.com](https://github.com/TommyZihao/folium_tutorials) | 21:24 | [link](https://www.bilibili.com/video/BV1gZ4y18772) |
| 562 | folium实战-波士顿犯罪地点、新冠疫情小区、纽约全天公交车可视化 | - | AI 论文精读 | - | [github.com](https://github.com/TommyZihao/folium_tutorials) | 11:04 | [link](https://www.bilibili.com/video/BV18T4y1B7PA) |
| 563 | folium实战-轨道交通数据可视化 | - | AI 论文精读 | - | [github.com](https://github.com/TommyZihao/folium_tutorials) | 21:36 | [link](https://www.bilibili.com/video/BV113411N7TL) |
| 564 | 玩转MMTracking视频感知与追踪算法库 | - | AI 论文精读 | - | [github.com](https://github.com/open-mmlab/mmtracking) | 0:49 | [link](https://www.bilibili.com/video/BV1za411Y7Zm) |
| 565 | MMTracking单目标追踪+轨迹绘制代码实战 | - | AI 论文精读 | - | [github.com](https://github.com/open-mmlab/mmtracking) | 23:06 | [link](https://www.bilibili.com/video/BV1s44y1g75J) |
| 566 | AI人流量计数+足迹追踪 | - | AI 论文精读 | - | [github.com](https://github.com/open-mmlab/mmtracking) | 42:06 | [link](https://www.bilibili.com/video/BV1J3411M7KQ) |
| 567 | 训练Deepsort多目标追踪算法 | - | AI 论文精读 | - | [github.com](https://github.com/open-mmlab/mmtracking) | 10:17 | [link](https://www.bilibili.com/video/BV1e5411m7Qh) |
| 568 | 【开箱遛遛】宇树机器狗Go2 | - | AI 论文精读 | - | - | 0:36 | [link](https://www.bilibili.com/video/BV1hG411Y74j) |
| 569 | 斯坦福CS224W图机器学习、图神经网络、知识图谱【同济子豪兄】 | - | AI 论文精读 | - | [web.stanford.edu](https://web.stanford.edu/class/cs224w) [github.com](https://github.com/TommyZihao/zihao_course/tree/main/CS224W) | 69:54 | [link](https://www.bilibili.com/video/BV1pR4y1S7GA) |
| 570 | 图的基本表示【斯坦福CS224W图机器学习】 | - | AI 论文精读 | - | [github.com](https://github.com/TommyZihao/zihao_course/tree/main/CS224W) [web.stanford.edu](https://web.stanford.edu/class/cs224w) | 30:17 | [link](https://www.bilibili.com/video/BV1n84y1e7SF) |
| 571 | 传统图机器学习的特征工程-节点【斯坦福CS224W】 | - | AI 论文精读 | - | [github.com](https://github.com/TommyZihao/zihao_course/tree/main/CS224W) [web.stanford.edu](https://web.stanford.edu/class/cs224w) | 38:58 | [link](https://www.bilibili.com/video/BV1HK411175s) |
| 572 | 传统图机器学习的特征工程-连接【斯坦福CS224W】 | - | AI 论文精读 | - | [github.com](https://github.com/TommyZihao/zihao_course/tree/main/CS224W) [web.stanford.edu](https://web.stanford.edu/class/cs224w) | 13:27 | [link](https://www.bilibili.com/video/BV1r3411m7sD) |
| 573 | 传统图机器学习的特征工程-全图【斯坦福CS224W】 | - | AI 论文精读 | - | [github.com](https://github.com/TommyZihao/zihao_course/tree/main/CS224W) [web.stanford.edu](https://web.stanford.edu/class/cs224w) | 17:41 | [link](https://www.bilibili.com/video/BV14W4y1V7gg) |
| 574 | 图机器学习NetworkX代码实战-创建图和可视化 | - | AI 论文精读 | - | [github.com](https://github.com/TommyZihao/zihao_course/tree/main/CS224W) [featurize.cn](https://featurize.cn?s=d7ce99f842414bfcaea5662a97581bd1) | 29:09 | [link](https://www.bilibili.com/video/BV1kM41147zV) |
| 575 | 图机器学习NetworkX代码实战-上海地铁站点图数据挖掘 | - | AI 论文精读 | - | [github.com](https://github.com/TommyZihao/zihao_course/tree/main/CS224W) [featurize.cn](https://featurize.cn?s=d7ce99f842414bfcaea5662a97581bd1) | 23:25 | [link](https://www.bilibili.com/video/BV1LY411R7HJ) |
| 576 | 随机游走的艺术-图嵌入表示学习【斯坦福CS224W图机器学习】 | - | AI 论文精读 | - | [github.com](https://github.com/TommyZihao/zihao_course/tree/main/CS224W) | 67:19 | [link](https://www.bilibili.com/video/BV1AP4y1r7Pz) |
| 577 | DeepWalk【图神经网络论文精读】 | - | AI 论文精读 | - | - | 46:51 | [link](https://www.bilibili.com/video/BV1o94y197vf) |
| 578 | DeepWalk论文逐句精读 | - | AI 论文精读 | - | - | 85:57 | [link](https://www.bilibili.com/video/BV1pW4y1z7pb) |
| 579 | DeepWalk代码实战-维基百科词条图嵌入可视化 | - | AI 论文精读 | - | - | 16:54 | [link](https://www.bilibili.com/video/BV1et4y187Gd) |
| 580 | Node2Vec【图神经网络论文精读】 | - | AI 论文精读 | - | - | 45:01 | [link](https://www.bilibili.com/video/BV1BS4y1E7tf) |
| 581 | Node2Vec论文逐句精读 | - | AI 论文精读 | - | - | 83:09 | [link](https://www.bilibili.com/video/BV1vU4y1i77T) |
| 582 | Node2Vec代码实战-《悲惨世界》小说人物图嵌入、Alias Sampling复现 | - | AI 论文精读 | - | - | 20:22 | [link](https://www.bilibili.com/video/BV1VS4y1E7Me) |
| 583 | 改变世界的谷歌PageRank算法 | - | AI 论文精读 | - | - | 77:18 | [link](https://www.bilibili.com/video/BV1uP411K7yN) |
| 584 | PageRank代码实战-西游记人物重要度 | - | AI 论文精读 | - | - | 6:04 | [link](https://www.bilibili.com/video/BV1Wg411H7Ep) |
| 585 | 半监督节点分类：标签传播和消息传递【斯坦福CS224W图机器学习】 | - | AI 论文精读 | - | [github.com](https://github.com/TommyZihao/zihao_course/tree/main/CS224W) | 74:06 | [link](https://www.bilibili.com/video/BV1184y1G7pA) |
| 586 | 深度学习基础【斯坦福CS224W图神经网络】 | - | AI 论文精读 | - | [github.com](https://github.com/TommyZihao/zihao_course/tree/main/CS224W) | 40:58 | [link](https://www.bilibili.com/video/BV13g4y1n7b4) |
| 587 | 图神经网络综述和学习路径【斯坦福CS224W图机器学习】 | - | AI 论文精读 | - | [github.com](https://github.com/TommyZihao/zihao_course/tree/main/CS224W) | 52:40 | [link](https://www.bilibili.com/video/BV16v4y1b7x7) |
| 588 | 图卷积神经网络GCN | - | AI 论文精读 | - | [github.com](https://github.com/TommyZihao/zihao_course/tree/main/CS224W) | 63:03 | [link](https://www.bilibili.com/video/BV1Hs4y157Ls) |
| 589 | 图神经网络GNN的表达能力 | - | AI 论文精读 | - | [github.com](https://github.com/TommyZihao/zihao_course/tree/main/CS224W) | 45:24 | [link](https://www.bilibili.com/video/BV1MT411Y7da) |
| 590 | 玩转Neo4j知识图谱和图数据挖掘 | - | AI 论文精读 | - | - | 28:54 | [link](https://www.bilibili.com/video/BV1Mr4y1i7CX) |
| 591 | Neo4j医疗知识图谱智能问答机器人 | - | AI 论文精读 | - | [liuhuanyong.github.io](https://liuhuanyong.github.io) [github.com](https://github.com/TommyZihao/QASystemOnMedicalKG/tree/master/notebook_tutorials) | 19:57 | [link](https://www.bilibili.com/video/BV1uY41167Ha) |
| 592 | 【精读AI论文】旷视轻量化网络ShuffleNet V2-算法精讲 | - | AI 论文精读 | - | - | 70:34 | [link](https://www.bilibili.com/video/BV1d3411Y7Ms) |
| 593 | 【精读AI论文】旷视轻量化网络ShuffleNet V2-论文精读 | - | AI 论文精读 | - | - | 93:36 | [link](https://www.bilibili.com/video/BV17u411U7Ag) |
| 594 | 生成对抗网络GAN交互式可视化 | - | AI 论文精读 | - | [poloclub.github.io](https://poloclub.github.io/ganlab/) [github.com](https://github.com/open-mmlab/mmgeneration) | 19:26 | [link](https://www.bilibili.com/video/BV1R44y1377T) |
| 595 | 生成对抗网络GAN开山之作论文精读 | - | AI 论文精读 | - | [github.com](https://github.com/open-mmlab/mmgeneration) | 100:15 | [link](https://www.bilibili.com/video/BV1oi4y1m7np) |
| 596 | 精读CycleGAN论文-拍案叫绝的非配对图像风格迁移 | - | AI 论文精读 | - | [junyanz.github.io](https://junyanz.github.io/CycleGAN) [github.com](https://github.com/open-mmlab/mmgeneration) | 105:07 | [link](https://www.bilibili.com/video/BV1Ya411a78P) |
| 597 | CycleGAN照片转梵高莫奈油画 | - | AI 论文精读 | - | [github.com](https://github.com/open-mmlab/mmgeneration) | 29:59 | [link](https://www.bilibili.com/video/BV1wv4y1T71F) |
| 598 | MMGeneration开源图像生成算法库【OpenMMLab】 | - | AI 论文精读 | - | [github.com](https://github.com/open-mmlab/mmgeneration（) [openmmlab.com](https://openmmlab.com/) | 44:07 | [link](https://www.bilibili.com/video/BV1bY4y147kz) |
| 599 | 【精读AI论文】pix2pix-简笔画猫转真猫 | - | AI 论文精读 | - | [phillipi.github.io](https://phillipi.github.io/pix2pix/) [affinelayer.com](https://affinelayer.com/pixsrv/) | 95:10 | [link](https://www.bilibili.com/video/BV1wY4y1k7Tc) |
| 600 | 人像自拍秒变爆款动漫画风【OpenMMLab】 | - | AI 论文精读 | - | [app.openmmlab.com](https://app.openmmlab.com/facestylor/) [colab.research.google.com](https://colab.research.google.com/drive/1hovHLKr0Vfa332LN-bBPAwyBe5WIc583?usp=sharing) | 28:04 | [link](https://www.bilibili.com/video/BV1XL4y1g7in) |
| 601 | 两天搞定语义分割毕业设计 | - | AI 论文精读 | - | [github.com](https://github.com/TommyZihao/MMSegmentation_Tutorials) | 0:12 | [link](https://www.bilibili.com/video/BV1Wr4y1d7Tr) |
| 602 | 语义分割与MMSegmentation | - | AI 论文精读 | - | [github.com](https://github.com/TommyZihao/MMSegmentation_Tutorials) | 41:52 | [link](https://www.bilibili.com/video/BV1qN411z7hz) |
| 603 | 标注自己的语义分割数据集 | - | AI 论文精读 | - | [github.com](https://github.com/TommyZihao/MMSegmentation_Tutorials) [github.com](https://github.com/wkentaro/labelme) [github.com](https://github.com/TommyZihao/Label2Everything/tree/main/labelme2mask) | 33:09 | [link](https://www.bilibili.com/video/BV1uu4y1Q7Rt) |
| 604 | 安装配置MMSegmentation+预训练语义分割推理预测 | - | AI 论文精读 | - | [github.com](https://github.com/TommyZihao/MMSegmentation_Tutorials) | 26:37 | [link](https://www.bilibili.com/video/BV1du4y1q7o5) |
| 605 | 准备西瓜语义分割数据集 | - | AI 论文精读 | - | [github.com](https://github.com/TommyZihao/MMSegmentation_Tutorials) | 14:20 | [link](https://www.bilibili.com/video/BV1C8411X7p9) |
| 606 | 准备MMSeg语义分割config配置文件 | - | AI 论文精读 | - | [github.com](https://github.com/TommyZihao/MMSegmentation_Tutorials) | 23:26 | [link](https://www.bilibili.com/video/BV1w44y1F73N) |
| 607 | MMSegmentation训练语义分割深度学习算法 | - | AI 论文精读 | - | [github.com](https://github.com/TommyZihao/MMSegmentation_Tutorials) | 23:54 | [link](https://www.bilibili.com/video/BV1Ch4y1S7cX) |
| 608 | MMSeg语义分割推理预测 | - | AI 论文精读 | - | [github.com](https://github.com/TommyZihao/MMSegmentation_Tutorials) | 24:52 | [link](https://www.bilibili.com/video/BV1vp4y1K7Tj) |
| 609 | 语义分割部署-MMDeploy模型转换 | - | AI 论文精读 | - | [github.com](https://github.com/TommyZihao/MMSegmentation_Tutorials) | 17:41 | [link](https://www.bilibili.com/video/BV1Ep4y1n7wo) |
| 610 | 语义分割部署-ONNX Runtime实时推理 | - | AI 论文精读 | - | [github.com](https://github.com/TommyZihao/MMSegmentation_Tutorials) | 6:33 | [link](https://www.bilibili.com/video/BV1aN411B7Dq) |
| 611 | AidLux语义分割部署-安卓鸿蒙高通ARM | - | AI 论文精读 | - | [aimo.aidlux.com](http://aimo.aidlux.com) [github.com](https://github.com/TommyZihao/aidlux_tutorial) [github.com](https://github.com/TommyZihao/MMSegmentation_Tutorials) | 28:59 | [link](https://www.bilibili.com/video/BV1k8411y7c2) |
| 612 | 可解释机器学习公开课 | - | AI 论文精读 | - | [github.com](https://github.com/TommyZihao/zihao_course/blob/main/XAI) [mp.weixin.qq.com](https://mp.weixin.qq.com/s/jxKVMpcqcunNSXxiyCtx0Q) | 61:06 | [link](https://www.bilibili.com/video/BV1Se4y1T7dG) |
| 613 | CAM可解释性分析-算法讲解 | - | AI 论文精读 | - | [readpaper.com](https://readpaper.com/user/collect/638623946528292864) | 36:49 | [link](https://www.bilibili.com/video/BV1Ke411g7gm) |
| 614 | CAM可解释性论文精读：Learning Deep Features for Discriminative Localization | - | AI 论文精读 | - | [readpaper.com](https://readpaper.com/user/collect/638623946528292864) | 50:15 | [link](https://www.bilibili.com/video/BV1fe4y1C7mN) |
| 615 | GradCAM深度学习可解释性分析 | - | AI 论文精读 | - | [github.com](https://github.com/TommyZihao/Train_Custom_Dataset) | 48:04 | [link](https://www.bilibili.com/video/BV1PD4y1B77q) |
| 616 | 【精读AI论文】GradCAM可解释性分析 | - | AI 论文精读 | - | [github.com](https://github.com/TommyZihao/Train_Custom_Dataset) | 53:08 | [link](https://www.bilibili.com/video/BV1id4y167FF) |
| 617 | LIME机器学习可解释性分析 | - | AI 论文精读 | - | [github.com](https://github.com/TommyZihao/zihao_course/blob/main/XAI) [github.com](https://github.com/TommyZihao/Train_Custom_Dataset) | 52:13 | [link](https://www.bilibili.com/video/BV12V4y1G7KF) |
| 618 | 【精读AI论文】LIME机器学习可解释性分析 | - | AI 论文精读 | - | [github.com](https://github.com/TommyZihao/zihao_course/blob/main/XAI) [github.com](https://github.com/TommyZihao/Train_Custom_Dataset) | 73:31 | [link](https://www.bilibili.com/video/BV1wV4y1V7rD) |
| 619 | MATLAB玩转深度学习可解释性分析 | - | AI 论文精读 | - | [github.com](https://github.com/TommyZihao/MATLAB_CAM_Tutorials) [github.com](https://github.com/TommyZihao/zihao_course/blob/main/XAI) | 19:11 | [link](https://www.bilibili.com/video/BV1Qd4y1b7Mr) |
| 620 | 11款神经网络科研绘图可视化工具 | - | AI 论文精读 | - | [github.com](https://github.com/TommyZihao/zihao_course/blob/main/XAI) | 20:55 | [link](https://www.bilibili.com/video/BV1TV4y1P7AP) |
| 621 | 论文分享ICML 2026：RAG场景下的不确定性量化研究 | - | AI 论文精读 | - | - | 18:36 | [link](https://www.bilibili.com/video/BV1NPNY67EH4) |
| 622 | 论文分享OMAC：多智能体协作的整体优化框架 | - | AI 论文精读 | [2505.11765](https://arxiv.org/abs/2505.11765) | [github.com](https://github.com/xiwenchao/OMAC) | 21:03 | [link](https://www.bilibili.com/video/BV1JUK26mEcb) |
| 623 | 论文分享HetRL：异构环境下的大模型强化学习调度框架 | - | AI 论文精读 | [2607.12345](https://arxiv.org/abs/2607.12345) | [github.com](https://github.com/hetrl-project/HetRL) | 9:34 | [link](https://www.bilibili.com/video/BV1APMS6AEYR) |
| 624 | 论文分享SONAR：去中心化学习不是“连得越多越好” | - | AI 论文精读 | - | [mlsys.org](https://mlsys.org/virtual/2026/oral/3857) [github.com](https://github.com/aidecentralized/sonar) | 11:31 | [link](https://www.bilibili.com/video/BV1DHuQ6HEch) |
| 625 | 论文分享BOOST：让低秩大模型在多GPU上真正跑快 | - | AI 论文精读 | [2512.12131](https://arxiv.org/abs/2512.12131) | [github.com](https://github.com/Arcana-2236/BOOST) | 13:00 | [link](https://www.bilibili.com/video/BV1A4gJ6XEYs) |
| 626 | 论文分享OSWorld-Human：电脑使用智能体离“高效”还有多远 | - | AI 论文精读 | [2506.16042](https://arxiv.org/abs/2506.16042) | [github.com](https://github.com/WukLab/osworld-human) | 18:35 | [link](https://www.bilibili.com/video/BV14bgA6jEqk) |
| 627 | 论文分享 Cocoon：相关噪声提升差分隐私训练精度，为什么系统成本却会暴涨 | - | AI 论文精读 | - | [usenix.org](https://www.usenix.org/conference/osdi26/presentation/kim-donghwan) [github.com](https://github.com/psu-paws/Cocoon) | 21:28 | [link](https://www.bilibili.com/video/BV1dVhc63EzM) |
| 628 | 论文分享 CSLE：强化学习安全策略如何从模拟器走向真实网络系统 | - | AI 论文精读 | - | [proceedings.mlsys.org](https://proceedings.mlsys.org/paper_files/paper/2026/hash/87eaaa8605a1a472d9a9756e7500517b-Abstract-Conference.html]) [github.com](https://github.com/Kim-Hammar/csle]) | 23:34 | [link](https://www.bilibili.com/video/BV13Rt96VEnk) |
| 629 | 论文分享 FLoRIST：联邦 LoRA 如何兼顾精度、通信与异构客户端 | - | AI 论文精读 | [2506.09199](https://arxiv.org/abs/2506.09199) | [github.com](https://github.com/DASS-Lab-Group/FLoRIST) | 30:44 | [link](https://www.bilibili.com/video/BV1pwY46aExv) |
| 630 | 视频理解和图像理解有什么区别？时序信息怎么建模？ | - | AI 论文精读 | - | - | 1:35 | [link](https://www.bilibili.com/video/BV1MddhBrEn8) |
| 631 | CLIP 的训练目标是什么？为什么要做图文匹配？ | - | AI 论文精读 | - | - | 1:31 | [link](https://www.bilibili.com/video/BV1spdhBPEEk) |
| 632 | CLIP 的视觉编码器用 ViT 还是 ResNet？各有什么优缺点？ | - | AI 论文精读 | - | - | 1:37 | [link](https://www.bilibili.com/video/BV1v7dzB6E8X) |
| 633 | 多模态模型的对齐（Alignment）是什么意思？怎么让图文语义对应？ | - | AI 论文精读 | - | - | 1:30 | [link](https://www.bilibili.com/video/BV19zdBBiE3c) |
| 634 | 图文相似度怎么计算？余弦相似度够用吗？ | - | AI 论文精读 | - | - | 1:26 | [link](https://www.bilibili.com/video/BV1HtoNBZEfS) |
| 635 | U-Net 在扩散模型里是怎么用的？时间步嵌入（Time Embedding）是什么？ | - | AI 论文精读 | - | - | 1:28 | [link](https://www.bilibili.com/video/BV1g7d2BXEDD) |
| 636 | CogVLM 的视觉专家模块是怎么设计的？ | - | AI 论文精读 | - | - | 1:26 | [link](https://www.bilibili.com/video/BV1g7d2BXEv5) |
| 637 | 文本生成 3D（Text-to-3D）怎么做？DreamFusion 的原理是什么？ | - | AI 论文精读 | - | - | 1:32 | [link](https://www.bilibili.com/video/BV13jd2BWETV) |
| 638 | 视频分类 (Video Classification) 怎么做？怎么从视频里提取全局特征？ | - | AI 论文精读 | - | - | 2:07 | [link](https://www.bilibili.com/video/BV1e3d2BoEqg) |
| 639 | 三维目标检测（3D Object Detection）怎么做？和 2D 检测有什么区别？ | - | AI 论文精读 | - | - | 2:02 | [link](https://www.bilibili.com/video/BV1XdonB9E4f) |
| 640 | GPT-4V（GPT-4 Vision）的多模态能力有多强？能做什么？ | - | AI 论文精读 | - | - | 1:38 | [link](https://www.bilibili.com/video/BV1fgoVBGEBi) |
| 641 | 多视图几何（Multi-View Geometry）是什么？SfM 和 SLAM 有什么区别？ | - | AI 论文精读 | - | - | 1:47 | [link](https://www.bilibili.com/video/BV134oVBaEN2) |
| 642 | IP-Adapter 是什么？怎么用图像作为 Prompt？ | - | AI 论文精读 | - | - | 1:37 | [link](https://www.bilibili.com/video/BV1bqoSB8Ec9) |
| 643 | 视频多模态大模型怎么做？长视频理解的难点是什么？ | - | AI 论文精读 | - | - | 1:55 | [link](https://www.bilibili.com/video/BV121o6BAEYN) |
| 644 | 跨模态检索（Cross-modal Retrieval）怎么做？图搜文、文搜图的原理是什么？ | - | AI 论文精读 | - | - | 1:38 | [link](https://www.bilibili.com/video/BV1G3R4BAEnv) |
| 645 | 视频超分辨率（Video Super-Resolution）是什么？怎么提升视频清晰度？ | - | AI 论文精读 | - | - | 1:53 | [link](https://www.bilibili.com/video/BV1SRdgBQE2m) |
| 646 | ViT 和 CNN 有什么区别？为什么多模态模型更喜欢用 ViT？ | - | AI 论文精读 | - | - | 1:40 | [link](https://www.bilibili.com/video/BV1DX5v69EmL) |
| 647 | 多模态大模型的幻觉问题更严重吗？视觉幻觉怎么缓解？ | - | AI 论文精读 | - | - | 1:49 | [link](https://www.bilibili.com/video/BV1BcLF6iEHb) |
| 648 | ViT（Vision Transformer）是怎么处理图像的？Patch Embedding 是什么？ | - | AI 论文精读 | - | - | 1:33 | [link](https://www.bilibili.com/video/BV1QfL16WE5q) |
| 649 | 【AI编译篇】AI  Infra 简历点评 | - | AI 论文精读 | - | - | 19:04 | [link](https://www.bilibili.com/video/BV1WE3c6uEYH) |
| 650 | 【AI应用篇】AI Infra简历点评 | - | AI 论文精读 | - | - | 27:54 | [link](https://www.bilibili.com/video/BV1oJ3B6AEBn) |
| 651 | 【AI推理篇】AI Infra简历点评 | - | AI 论文精读 | - | - | 37:04 | [link](https://www.bilibili.com/video/BV1poMy6HEws) |
| 652 | TileLang 分享：TileLang 简介 | - | AI 论文精读 | - | [github.com](https://github.com/tile-ai/tilelang) | 2:13 | [link](https://www.bilibili.com/video/BV1jHyjBEEFd) |
| 653 | TileLang 分享：TileLang 特性介绍 | - | AI 论文精读 | - | [github.com](https://github.com/tile-ai/tilelang) | 12:53 | [link](https://www.bilibili.com/video/BV1jJyjBSEzQ) |
| 654 | TileLang 分享：TileLang API 及算子实例 | - | AI 论文精读 | - | [github.com](https://github.com/tile-ai/tilelang) | 9:13 | [link](https://www.bilibili.com/video/BV1LpyjBmEGz) |
| 655 | TileLang 分享：TileLang 调优和 Debug | - | AI 论文精读 | - | [github.com](https://github.com/tile-ai/tilelang) | 4:54 | [link](https://www.bilibili.com/video/BV15pyjBmED5) |
| 656 | 自编教材实操课程分享：第五章—编译器前端 | - | AI 论文精读 | - | - | 8:19 | [link](https://www.bilibili.com/video/BV1NC411Y7A8) |
| 657 | 自编教材实操课程分享：第五章—编译器中端 | - | AI 论文精读 | - | - | 8:03 | [link](https://www.bilibili.com/video/BV1Xr421H7t3) |
| 658 | 自编教材实操课程分享：第五章—编译器后端 | - | AI 论文精读 | - | - | 8:53 | [link](https://www.bilibili.com/video/BV1gi421d7Hc) |
| 659 | 自编教材实操课程分享：第五章—编译选项 | - | AI 论文精读 | - | - | 5:42 | [link](https://www.bilibili.com/video/BV1Nr421n7Pd) |
| 660 | 自编教材实操课程分享：第五章—过程间优化 | - | AI 论文精读 | - | - | 6:05 | [link](https://www.bilibili.com/video/BV15m411d7gH) |
| 661 | 自编教材实操课程分享：第五章—循环展开 | - | AI 论文精读 | - | - | 9:36 | [link](https://www.bilibili.com/video/BV13f421f7ip) |
| 662 | 自编教材实操课程分享：第五章—循环分布 | - | AI 论文精读 | - | - | 9:40 | [link](https://www.bilibili.com/video/BV1pj421d793) |
| 663 | 自编教材实操课程分享：第五章—循环剥离 | - | AI 论文精读 | - | - | 6:10 | [link](https://www.bilibili.com/video/BV1AD421W7A1) |
| 664 | 自编教材实操课程分享：第五章—循环级向量化 | - | AI 论文精读 | - | - | 11:23 | [link](https://www.bilibili.com/video/BV19M4m1X7PU) |
| 665 | 自编教材实操课程分享：第五章—基本块级向量化 | - | AI 论文精读 | - | - | 7:59 | [link](https://www.bilibili.com/video/BV1wp421y7k2) |
| 666 | 自编教材实操课程分享：第五章—数据预取优化 | - | AI 论文精读 | - | - | 6:31 | [link](https://www.bilibili.com/video/BV1Dz421k72n) |
| 667 | 自编教材实操课程分享：第五章—浮点优化 | - | AI 论文精读 | - | - | 7:34 | [link](https://www.bilibili.com/video/BV1BZ421e7t6) |
| 668 | 自编教材实操课程分享：第五章—反馈优化 | - | AI 论文精读 | - | - | 3:34 | [link](https://www.bilibili.com/video/BV1xx421S74X) |
| 669 | 自编教材实操课程分享：第五章—链接时优化 | - | AI 论文精读 | - | - | 4:32 | [link](https://www.bilibili.com/video/BV1ZD421p7Gy) |
| 670 | 自编教材实操课程分享：第五章—编译指示 | - | AI 论文精读 | - | - | 19:35 | [link](https://www.bilibili.com/video/BV1jZ421v791) |
| 671 | 自编教材实操课程分享：第五章—数学库优化 | - | AI 论文精读 | - | - | 12:19 | [link](https://www.bilibili.com/video/BV12D421p79o) |
| 672 | 自编教材实操课程分享：第五章—运行时优化 | - | AI 论文精读 | - | - | 7:43 | [link](https://www.bilibili.com/video/BV1ax4y167hV) |
| 673 | 自编教材实操课程分享：第六章—算法优化 | - | AI 论文精读 | - | - | 16:37 | [link](https://www.bilibili.com/video/BV1C142197zL) |
| 674 | 自编教材实操课程分享：第六章—典型数据结构的性能分析 | - | AI 论文精读 | - | - | 3:59 | [link](https://www.bilibili.com/video/BV1ew4m127sJ) |
| 675 | 自编教材实操课程分享：第六章—选择合适的数据类型 | - | AI 论文精读 | - | - | 5:40 | [link](https://www.bilibili.com/video/BV11t421c7N1) |
| 676 | 自编教材实操课程分享：第六章—选择合适的数据结构（二） | - | AI 论文精读 | - | - | 7:08 | [link](https://www.bilibili.com/video/BV1vi421C7mB) |
| 677 | 自编教材实操课程分享：第六章—别名消除 | - | AI 论文精读 | - | - | 4:02 | [link](https://www.bilibili.com/video/BV1tx4y1B75k) |
| 678 | 自编教材实操课程分享：第六章—常数传播 | - | AI 论文精读 | - | - | 4:01 | [link](https://www.bilibili.com/video/BV1Cw4m1C7t3) |
| 679 | 自编教材实操课程分享：第六章—传参优化 | - | AI 论文精读 | - | - | 4:14 | [link](https://www.bilibili.com/video/BV1NM4m1o7oH) |
| 680 | 自编教材实操课程分享：第六章—内联替换 | - | AI 论文精读 | - | - | 3:58 | [link](https://www.bilibili.com/video/BV1CC411j7Zz) |
| 681 | 自编教材实操课程分享：第六章—过程克隆 | - | AI 论文精读 | - | - | 4:36 | [link](https://www.bilibili.com/video/BV17y411Y7Wo) |
| 682 | 自编教材实操课程分享：第六章—全局变量优化 | - | AI 论文精读 | - | - | 3:22 | [link](https://www.bilibili.com/video/BV1vf421m7RY) |
| 683 | 自编教材实操课程分享：第六章—循环不变量外提 | - | AI 论文精读 | - | - | 11:06 | [link](https://www.bilibili.com/video/BV1nw4m1D7np) |
| 684 | 自编教材实操课程分享：第六章—循环合并 | - | AI 论文精读 | - | - | 12:30 | [link](https://www.bilibili.com/video/BV1k7421f77W) |
| 685 | 自编教材实操课程分享：第六章—循环分段 | - | AI 论文精读 | - | - | 6:46 | [link](https://www.bilibili.com/video/BV18z421Y7eR) |
| 686 | 自编教材实操课程分享：第六章—循环展开和压紧 | - | AI 论文精读 | - | - | 13:03 | [link](https://www.bilibili.com/video/BV1mx4y1H7ch) |
| 687 | 自编教材实操课程分享：第六章-循环分块 | - | AI 论文精读 | - | - | 9:19 | [link](https://www.bilibili.com/video/BV1sJ4m137o2) |
| 688 | 自编教材实操课程分享：第六章—循环交换 | - | AI 论文精读 | - | - | 17:54 | [link](https://www.bilibili.com/video/BV1zx4y1n7fe) |
| 689 | 自编教材实操课程分享：第六章—循环分裂 | - | AI 论文精读 | - | - | 8:29 | [link](https://www.bilibili.com/video/BV1Et421N7E5) |
| 690 | 自编教材实操课程分享：第六章—循环倾斜 | - | AI 论文精读 | - | - | 7:58 | [link](https://www.bilibili.com/video/BV1J4421X7Zm) |
| 691 | 自编教材实操课程分享：第六章—循环分布 | - | AI 论文精读 | - | - | 12:38 | [link](https://www.bilibili.com/video/BV16S411K7Zv) |
| 692 | 自编教材实操课程分享：第六章—删除冗余语句 | - | AI 论文精读 | - | - | 9:39 | [link](https://www.bilibili.com/video/BV1Bx4y1J7Uq) |
| 693 | 自编教材实操课程分享：第六章—代数变换 | - | AI 论文精读 | - | - | 11:04 | [link](https://www.bilibili.com/video/BV1G7421d7FB) |
| 694 | 自编教材实操课程分享：第六章—公共子表达式优化 | - | AI 论文精读 | - | - | 4:42 | [link](https://www.bilibili.com/video/BV1Nr421w7DW) |
| 695 | 自编教材实操课程分享：第六章—合并判断条件 | - | AI 论文精读 | - | - | 4:42 | [link](https://www.bilibili.com/video/BV1n4421Q7H8) |
| 696 | 自编教材实操课程分享：第六章—生成选择指令 | - | AI 论文精读 | - | - | 4:41 | [link](https://www.bilibili.com/video/BV1px4y1J7mR) |
| 697 | 自编教材实操课程分享：第七章—指令流水 | - | AI 论文精读 | - | - | 10:30 | [link](https://www.bilibili.com/video/BV1dx4y147fD) |
| 698 | 自编教材实操课程分享：第七章—超长指令字 | - | AI 论文精读 | - | - | 4:34 | [link](https://www.bilibili.com/video/BV1Nf421z7Yy) |
| 699 | 自编教材实操课程分享：第七章—函数的向量化 | - | AI 论文精读 | - | - | 3:56 | [link](https://www.bilibili.com/video/BV1Uw4m1e7PE) |
| 700 | 自编教材实操课程分享：第七章—基本块的向量化 | - | AI 论文精读 | - | - | 6:07 | [link](https://www.bilibili.com/video/BV1A4421X7ov) |
| 701 | 自编教材实操课程分享：第七章—循环的向量化 | - | AI 论文精读 | - | - | 11:04 | [link](https://www.bilibili.com/video/BV1gZ421M7UP) |
| 702 | 自编教材实操课程分享：第六章—分支语句优化之运用条件编译 | - | AI 论文精读 | - | - | 5:47 | [link](https://www.bilibili.com/video/BV18Z421T7Tx) |
| 703 | 自编教材实操课程分享：第六章—分支语句优化之移除分支语句 | - | AI 论文精读 | - | - | 4:37 | [link](https://www.bilibili.com/video/BV1Bb421E7yE) |
| 704 | 自编教材实操课程分享：第七章—分支向量化 | - | AI 论文精读 | - | - | 9:54 | [link](https://www.bilibili.com/video/BV1ES421R7BC) |
| 705 | 自编教材实操课程分享：第七章—归约向量化 | - | AI 论文精读 | - | - | 4:26 | [link](https://www.bilibili.com/video/BV1Q4421U7UR) |
| 706 | 自编教材实操课程分享：第七章—不对齐访存 | - | AI 论文精读 | - | - | 11:36 | [link](https://www.bilibili.com/video/BV1cZ421u7oX) |
| 707 | 自编教材实操课程分享：第七章—不连续访存 | - | AI 论文精读 | - | - | 12:28 | [link](https://www.bilibili.com/video/BV1yS411c7nC) |
| 708 | 自编教材实操课程分享：第七章—向量运算融合 | - | AI 论文精读 | - | - | 4:09 | [link](https://www.bilibili.com/video/BV1gy411i7cL) |
| 709 | 自编教材实操课程分享：第七章—向量重用 | - | AI 论文精读 | - | - | 7:49 | [link](https://www.bilibili.com/video/BV1Pw4m1Y7nH) |
| 710 | 自编教材实操课程分享：第七章—循环完全展开 | - | AI 论文精读 | - | - | 3:46 | [link](https://www.bilibili.com/video/BV12H4y1w7cK) |
| 711 | 自编教材实操课程分享：第八章—寄存器分配 | - | AI 论文精读 | - | - | 16:12 | [link](https://www.bilibili.com/video/BV1kr421M7mc) |
| 712 | 自编教材实操课程分享：第八章—寄存器重用 | - | AI 论文精读 | - | - | 8:23 | [link](https://www.bilibili.com/video/BV1p142187Vu) |
| 713 | 自编教材实操课程分享：第八章—缓存分块 | - | AI 论文精读 | - | - | 15:43 | [link](https://www.bilibili.com/video/BV1o4421Z7Ld) |
| 714 | 自编教材实操课程分享：第八章—减少伪共享 | - | AI 论文精读 | - | - | 7:46 | [link](https://www.bilibili.com/video/BV1cZ421K7fz) |
| 715 | 自编教材实操课程分享：第八章—数据预取 | - | AI 论文精读 | - | - | 8:11 | [link](https://www.bilibili.com/video/BV1Jb421J7Fx) |
| 716 | 自编教材实操课程分享：第八章—减少内存读写 | - | AI 论文精读 | - | - | 7:45 | [link](https://www.bilibili.com/video/BV1amW8edE7Q) |
| 717 | 自编教材实操课程分享：第八章—数据对齐 | - | AI 论文精读 | - | - | 12:57 | [link](https://www.bilibili.com/video/BV1KCste1EQN) |
| 718 | 自编教材实操课程分享：第八章—多线程操作 | - | AI 论文精读 | - | - | 8:26 | [link](https://www.bilibili.com/video/BV1TksteLErP) |
| 719 | 自编教材实操课程分享：第八章—数组重组 | - | AI 论文精读 | - | - | 6:06 | [link](https://www.bilibili.com/video/BV1TksteLErM) |
| 720 | 自编教材实操课程分享：第八章—数组转置 | - | AI 论文精读 | - | - | 7:21 | [link](https://www.bilibili.com/video/BV18BHaeXECN) |
| 721 | 自编教材实操课程分享：第八章—结构属性域调整 | - | AI 论文精读 | - | - | 6:47 | [link](https://www.bilibili.com/video/BV1hqHaeWETX) |
| 722 | 自编教材实操课程分享：第八章—结构体拆分 | - | AI 论文精读 | - | - | 7:01 | [link](https://www.bilibili.com/video/BV18qHaeWEkd) |
| 723 | 自编教材实操课程分享：第八章—结构体数组转换 | - | AI 论文精读 | - | - | 6:33 | [link](https://www.bilibili.com/video/BV1wG4henEyc) |
| 724 | 自编教材实操课程分享：第九章—OpenMP程序编写 | - | AI 论文精读 | - | - | 8:23 | [link](https://www.bilibili.com/video/BV19ntJeMEpD) |
| 725 | 自编教材实操课程分享：第九章—OpenMP版矩阵乘 | - | AI 论文精读 | - | - | 7:39 | [link](https://www.bilibili.com/video/BV1hstJeeEpc) |
| 726 | 自编教材实操课程分享：第九章—并行区扩张 | - | AI 论文精读 | - | - | 14:59 | [link](https://www.bilibili.com/video/BV1its8eYEQh) |
| 727 | 自编教材实操课程分享：第九章—并行区合并 | - | AI 论文精读 | - | - | 14:09 | [link](https://www.bilibili.com/video/BV1qts8eYEiH) |
| 728 | 自编教材实操课程分享：第九章—数据填充避免伪共享 | - | AI 论文精读 | - | - | 10:12 | [link](https://www.bilibili.com/video/BV1Z4s8eAEp9) |
| 729 | 自编教材实操课程分享：第九章—循环向量化 | - | AI 论文精读 | - | - | 9:37 | [link](https://www.bilibili.com/video/BV1hjxWe6EDy) |
| 730 | 自编教材实操课程分享：第九章—循环嵌套合并调度 | - | AI 论文精读 | - | - | 15:13 | [link](https://www.bilibili.com/video/BV13jxWe6EAP) |
| 731 | 自编教材实操课程分享：第九章—线程调度配置策略 | - | AI 论文精读 | - | - | 15:50 | [link](https://www.bilibili.com/video/BV1bh2tYJEq3) |
| 732 | 自编教材实操课程分享：第九章—串并行切换 | - | AI 论文精读 | - | - | 10:41 | [link](https://www.bilibili.com/video/BV1ub2tYDEXm) |
| 733 | 自编教材实操课程分享：第九章—线程数设置优化 | - | AI 论文精读 | - | - | 14:26 | [link](https://www.bilibili.com/video/BV1qM2ZY2EwV) |
| 734 | 自编教材实操课程分享：第九章—分析隐式同步 | - | AI 论文精读 | - | - | 6:58 | [link](https://www.bilibili.com/video/BV1K9yGYaEAs) |
| 735 | 自编教材实操课程分享：第九章—消除隐式同步 | - | AI 论文精读 | - | - | 12:41 | [link](https://www.bilibili.com/video/BV1N9yGYhEea) |
| 736 | 自编教材实操课程分享：第九章—流水并行示例 | - | AI 论文精读 | - | - | 9:42 | [link](https://www.bilibili.com/video/BV1sUS8YxEJ3) |
| 737 | 自编教材实操课程分享：第九章—流水并行粒度 | - | AI 论文精读 | - | - | 15:38 | [link](https://www.bilibili.com/video/BV1qNShYyE4f) |
| 738 | 自编教材实操课程分享：第十章—CUDA程序编写 | - | AI 论文精读 | - | - | 6:52 | [link](https://www.bilibili.com/video/BV1j8DSYPEpp) |
| 739 | 自编教材实操课程分享：第十章—线程结构优化 | - | AI 论文精读 | - | - | 8:08 | [link](https://www.bilibili.com/video/BV1aoDUYoEoq) |
| 740 | 自编教材实操课程分享：第十章—分支优化 | - | AI 论文精读 | - | - | 6:42 | [link](https://www.bilibili.com/video/BV1unmDYEELs) |
| 741 | 自编教材实操课程分享：第十章—访存优化(1) | - | AI 论文精读 | - | - | 6:34 | [link](https://www.bilibili.com/video/BV1unmDYEEMA) |
| 742 | 自编教材实操课程分享：第十章—访存优化(2) | - | AI 论文精读 | - | - | 6:21 | [link](https://www.bilibili.com/video/BV1AGBxYLEjh) |
| 743 | 自编教材实操课程分享：第十章—数据预取 | - | AI 论文精读 | - | - | 5:06 | [link](https://www.bilibili.com/video/BV11PBxYSEot) |
| 744 | 自编教材实操课程分享：第十章—循环展开 | - | AI 论文精读 | - | - | 3:44 | [link](https://www.bilibili.com/video/BV1mABxYHEim) |
| 745 | 人工智能编译器MLIR-官方入门教程讲解 | - | AI 论文精读 | - | - | 60:39 | [link](https://www.bilibili.com/video/BV1Hd4y1U7mb) |
| 746 | 深度学习编译发展概述 | - | AI 论文精读 | - | [mindspore.cn](https://www.mindspore.cn/) | 16:31 | [link](https://www.bilibili.com/video/BV1zd4y1K7MQ) |
| 747 | 深度学习编译系统概述 | - | AI 论文精读 | - | - | 34:37 | [link](https://www.bilibili.com/video/BV1kS4y1t7JH) |
| 748 | 深度学习框架发展（一） | - | AI 论文精读 | - | - | 15:12 | [link](https://www.bilibili.com/video/BV1iD4y117td) |
| 749 | 深度学习框架发展（二） | - | AI 论文精读 | - | - | 13:00 | [link](https://www.bilibili.com/video/BV1dt4y1F7Cn) |
| 750 | 深度学习框架发展（三） | - | AI 论文精读 | - | - | 14:20 | [link](https://www.bilibili.com/video/BV1Qe4y1z78o) |
| 751 | 深度学习硬件平台 | - | AI 论文精读 | - | - | 13:05 | [link](https://www.bilibili.com/video/BV1JY411Q72M) |
| 752 | 深度学习自动微分：什么是自动微分 | - | AI 论文精读 | - | - | 10:55 | [link](https://www.bilibili.com/video/BV1fs4y197km) |
| 753 | HIP代码自动生成工具C2HIPC | - | AI 论文精读 | - | - | 9:53 | [link](https://www.bilibili.com/video/BV1Jg411Q7z6) |
| 754 | 循环优化（一）：循环展开和压紧 | - | AI 论文精读 | - | - | 12:54 | [link](https://www.bilibili.com/video/BV1HB4y1x7zv) |
| 755 | 循环优化（二）：循环合并 | - | AI 论文精读 | - | - | 11:16 | [link](https://www.bilibili.com/video/BV1CD4y1B7H2) |
| 756 | 循环优化（三）：循环分布 | - | AI 论文精读 | - | [zhuanlan.zhihu.com](https://zhuanlan.zhihu.com/p/568326883) | 9:29 | [link](https://www.bilibili.com/video/BV1Z8411t7dC) |
| 757 | 循环优化（四）：循环交换 | - | AI 论文精读 | - | - | 9:13 | [link](https://www.bilibili.com/video/BV13d4y1C7ca) |
| 758 | 循环优化（五）：循环不变量外提 | - | AI 论文精读 | - | - | 14:23 | [link](https://www.bilibili.com/video/BV1Ud4y1b7Zc) |
| 759 | 循环优化（六）：循环分段 | - | AI 论文精读 | - | - | 5:55 | [link](https://www.bilibili.com/video/BV1Zs4y1s7zn) |
| 760 | 循环优化（七）：循环分块 | - | AI 论文精读 | - | - | 11:23 | [link](https://www.bilibili.com/video/BV1gv4y1Y7ed) |
| 761 | 循环优化（八）：循环分裂 | - | AI 论文精读 | - | - | 6:29 | [link](https://www.bilibili.com/video/BV1mb411f7wK) |
| 762 | 循环优化（九）：循环倾斜 | - | AI 论文精读 | - | - | 13:30 | [link](https://www.bilibili.com/video/BV1uV4y1f7cJ) |
| 763 | 你知道吗，C语言最初被称为New B语言？ | - | AI 论文精读 | - | - | 8:57 | [link](https://www.bilibili.com/video/BV1Rp4y1c7k3) |
| 764 | 推理出企鹅会飞的编程语言——Prolog | - | AI 论文精读 | - | - | 8:16 | [link](https://www.bilibili.com/video/BV1BF411S7Sy) |
| 765 | 雷军：我写的代码像诗一样。Ruby：用我可以像写散文一样快乐写代码！ | - | AI 论文精读 | - | - | 10:39 | [link](https://www.bilibili.com/video/BV1Cp4y1w7a6) |
| 766 | LISP从括号出发，曲线救国的编程之路 | - | AI 论文精读 | - | - | 6:19 | [link](https://www.bilibili.com/video/BV1x84y1U7eD) |
| 767 | go，一门丑到无法形容的语言 | - | AI 论文精读 | - | - | 7:53 | [link](https://www.bilibili.com/video/BV1nu41137NZ) |
| 768 | Forth:一门不同于其他任何语言的编程语言 | - | AI 论文精读 | - | - | 6:52 | [link](https://www.bilibili.com/video/BV1m84y1D7bm) |
| 769 | 汇编语言：在我面前，所有高级编程语言都是小弟 | - | AI 论文精读 | - | - | 7:43 | [link](https://www.bilibili.com/video/BV1tu411376J) |
| 770 | COBOL：编程界的上古语言 | - | AI 论文精读 | - | - | 6:42 | [link](https://www.bilibili.com/video/BV158411C7zX) |
| 771 | ALGOL60:编程领域的带头大哥 | - | AI 论文精读 | - | - | 7:25 | [link](https://www.bilibili.com/video/BV1qh4y1h7UW) |
| 772 | 图算融合论文分享：Apollo | - | AI 论文精读 | - | - | 9:33 | [link](https://www.bilibili.com/video/BV1Do4y1L7Xd) |
| 773 | 算子调度优化论文分享：Rammer | - | AI 论文精读 | - | - | 10:35 | [link](https://www.bilibili.com/video/BV1LM411u7nE) |
| 774 | 动态shape深度学习算子自动调优论文分享：DietCode | - | AI 论文精读 | - | - | 14:45 | [link](https://www.bilibili.com/video/BV1RP4y167P4) |
| 775 | 动态shape深度学习编译器论文分享：DISC | - | AI 论文精读 | - | - | 14:26 | [link](https://www.bilibili.com/video/BV16R4y1U7J5) |
| 776 | Astitch：机器学习访存密集计算编译优化框架 | - | AI 论文精读 | - | - | 10:28 | [link](https://www.bilibili.com/video/BV1Ev4y1Q7L4) |
| 777 | 深度学习编译接口FreeTensor | - | AI 论文精读 | - | - | 15:53 | [link](https://www.bilibili.com/video/BV1uV4y1M7dQ) |
| 778 | 基于MLIR的GPU代码生成论文分享 | - | AI 论文精读 | - | - | 32:28 | [link](https://www.bilibili.com/video/BV1ga411N736) |
| 779 | 论文分享：计算图优化Welder | - | AI 论文精读 | - | - | 10:30 | [link](https://www.bilibili.com/video/BV1Tu4y1y7hN) |
| 780 | 论文分享：动态控制流编译优化Cocktailer | - | AI 论文精读 | - | - | 13:11 | [link](https://www.bilibili.com/video/BV1Kh4y1P7Rg) |
| 781 | 论文分享：动态神经网络编译优化BrainStorm | - | AI 论文精读 | - | - | 7:25 | [link](https://www.bilibili.com/video/BV1FC4y1R7pu) |
| 782 | 论文分享：计算密集型算子融合Chimera | - | AI 论文精读 | - | - | 10:05 | [link](https://www.bilibili.com/video/BV1Y6421G7kL) |
| 783 | 代码加速黑科技：GraalNN如何让程序性能飞跃 | - | AI 论文精读 | - | - | 9:32 | [link](https://www.bilibili.com/video/BV1m7JizLEC3) |
| 784 | CoServe：解锁 CoE 模型有限内存推理新路径 | - | AI 论文精读 | - | - | 8:33 | [link](https://www.bilibili.com/video/BV17kJLzBEF2) |
| 785 | PAPI：从静态到动态，异构PIM如何解锁LLM解码的“智能调度”新纪元 | - | AI 论文精读 | - | - | 11:29 | [link](https://www.bilibili.com/video/BV1d2Tjz6EtD) |
| 786 | CIM-MLC：从芯片到行级，解锁存算一体的编译新范式 | - | AI 论文精读 | - | - | 20:30 | [link](https://www.bilibili.com/video/BV1aKTvzDEdd) |
| 787 | 论文分享QiMeng-Xpiler：神经符号融合的异构深度学习系统张量程序跨平台转编译方案 | - | AI 论文精读 | - | - | 9:51 | [link](https://www.bilibili.com/video/BV1PopNzFEuH) |
| 788 | 论文分享UniNDP：面向Near DRAM处理架构的统一编译与仿真工具 | - | AI 论文精读 | - | [nicsefc.ee.tsinghua.edu.cn](https://nicsefc.ee.tsinghua.edu.cn/nics_file/pdf/d356f1fd-6204-4b21-8849-a9c3b2e15065.pdf) | 6:48 | [link](https://www.bilibili.com/video/BV1kfpNzoEjX) |
| 789 | 编译器自动调优论文分享：破解编译优化组合爆炸，协同搜索助力快速寻优 | - | AI 论文精读 | - | [dl.acm.org](https://dl.acm.org/doi/epdf/10.1145/3696443.3708961) | 7:13 | [link](https://www.bilibili.com/video/BV1y9pNzcEiL) |
| 790 | 论文分享ANT-ACE：实现神经网络推理自动化的全同态加密编译器框架 | - | AI 论文精读 | - | - | 8:02 | [link](https://www.bilibili.com/video/BV1A5nwz5EwS) |
| 791 | 论文分享HALO：面向全同态加密的循环感知自举管理 | - | AI 论文精读 | - | - | 9:38 | [link](https://www.bilibili.com/video/BV1vhnwzaENX) |
| 792 | 论文分享Gated Attention：用极小代价换来大模型性能飞升 | - | AI 论文精读 | - | - | 10:24 | [link](https://www.bilibili.com/video/BV1nGFVzQEAh) |
| 793 | 论文分享TempSamp-R1：用混合采样强化视频大模型时序定位 | - | AI 论文精读 | [2509.18056](https://arxiv.org/abs/2509.18056) | [github.com](https://github.com/HVision-NKU/TempSamp-R1) | 10:18 | [link](https://www.bilibili.com/video/BV1QVKb6mEFm) |
| 794 | 论文分享 FlashInfer：面向大模型推理服务的高效 Attention 引擎 | - | AI 论文精读 | [2501.01005](https://arxiv.org/abs/2501.01005) | [github.com](https://github.com/flashinfer-ai/flashinfer) | 9:36 | [link](https://www.bilibili.com/video/BV1QKgQ6xEgh) |
| 795 | 论文分享 CAKE：面向长上下文大模型的自适应 KV Cache 淘汰框架 | - | AI 论文精读 | [2503.12491](https://arxiv.org/abs/2503.12491) | [github.com](https://github.com/antgroup/cakekv) | 21:21 | [link](https://www.bilibili.com/video/BV16w3a6HEfe) |
| 796 | 01 课程介绍 | - | AI 论文精读 | - | - | 1:57 | [link](https://www.bilibili.com/video/BV16BGbzAEq2) |
| 797 | 01 神经网络基础 | - | AI 论文精读 | - | - | 12:59 | [link](https://www.bilibili.com/video/BV1cBGbzPE3T) |
| 798 | 02 深度学习的进化 | - | AI 论文精读 | - | - | 12:01 | [link](https://www.bilibili.com/video/BV1cBGbzPEKk) |
| 799 | 03 大语言模型 | - | AI 论文精读 | - | - | 8:26 | [link](https://www.bilibili.com/video/BV1cBGbzPEb2) |
| 800 | 01 faster-RCNN算法原理 | - | AI 论文精读 | - | - | 8:52 | [link](https://www.bilibili.com/video/BV1rBGbzAEFS) |
| 801 | 02 fasterRCNN实战 | - | AI 论文精读 | - | - | 12:41 | [link](https://www.bilibili.com/video/BV16BGbzAEtd) |
| 802 | 03 YOLOv11实战 | - | AI 论文精读 | - | - | 5:47 | [link](https://www.bilibili.com/video/BV1cBGbzPEb1) |
| 803 | 01 文本情感分类实战_1 | - | AI 论文精读 | - | - | 9:24 | [link](https://www.bilibili.com/video/BV1rBGbzAE5P) |
| 804 | 02 文本情感分类实战_2 | - | AI 论文精读 | - | - | 16:55 | [link](https://www.bilibili.com/video/BV1FBGbzPEoQ) |
| 805 | 01 大模型预训练基础_1 | - | AI 论文精读 | - | - | 7:39 | [link](https://www.bilibili.com/video/BV16BGbzAEbA) |
| 806 | 02 大模型预训练基础_2 | - | AI 论文精读 | - | - | 9:39 | [link](https://www.bilibili.com/video/BV1aRGbzHEmA) |
| 807 | 01 数据准备_1 | - | AI 论文精读 | - | - | 9:43 | [link](https://www.bilibili.com/video/BV1XRGbzHECt) |
| 808 | 02 数据准备_2 | - | AI 论文精读 | - | - | 11:16 | [link](https://www.bilibili.com/video/BV1YRGbzHEgK) |
| 809 | 03 模型结构_1 | - | AI 论文精读 | - | - | 13:19 | [link](https://www.bilibili.com/video/BV1GRGbzpEyR) |
| 810 | 04 模型结构_2 | - | AI 论文精读 | - | - | 14:58 | [link](https://www.bilibili.com/video/BV1YRGbzHE5h) |
| 811 | 01 预训练任务实现 | - | AI 论文精读 | - | - | 9:10 | [link](https://www.bilibili.com/video/BV1XRGbzHEXj) |
| 812 | 02 训练优化_1 | - | AI 论文精读 | - | - | 10:48 | [link](https://www.bilibili.com/video/BV1YRGbzHEWn) |
| 813 | 03 训练优化_2 | - | AI 论文精读 | - | - | 11:25 | [link](https://www.bilibili.com/video/BV1aRGbzHEBG) |
| 814 | 01 性能评估 | - | AI 论文精读 | - | - | 15:31 | [link](https://www.bilibili.com/video/BV1YRGbzHEcL) |
| 815 | 01 课程介绍 | - | AI 论文精读 | - | - | 1:02 | [link](https://www.bilibili.com/video/BV1gMjBzJE1B) |
| 816 | 01 大模型微调概述 | - | AI 论文精读 | - | - | 10:23 | [link](https://www.bilibili.com/video/BV1gMjBzJEDw) |
| 817 | 01 模型数据收集与处理 | - | AI 论文精读 | - | - | 14:32 | [link](https://www.bilibili.com/video/BV1gMjBzJEP9) |
| 818 | 01 数据预处理理论 | - | AI 论文精读 | - | - | 10:54 | [link](https://www.bilibili.com/video/BV1gMjBzJEap) |
| 819 | 02 启发式规则 | - | AI 论文精读 | - | - | 15:31 | [link](https://www.bilibili.com/video/BV1gMjBzJEEM) |
| 820 | 03 评估模型过滤(1) | - | AI 论文精读 | - | - | 13:30 | [link](https://www.bilibili.com/video/BV1DMjBzJEm9) |
| 821 | 04 评估模型过滤(2) | - | AI 论文精读 | - | - | 9:46 | [link](https://www.bilibili.com/video/BV1gMjBzJEPy) |
| 822 | 05 完全匹配去重 | - | AI 论文精读 | - | - | 18:28 | [link](https://www.bilibili.com/video/BV1hMjBzJENe) |
| 823 | 06 近似匹配去重(1) | - | AI 论文精读 | - | - | 11:18 | [link](https://www.bilibili.com/video/BV18MjBzJEY6) |
| 824 | 07 近似匹配去重(2) | - | AI 论文精读 | - | - | 10:22 | [link](https://www.bilibili.com/video/BV1gMjBzJESX) |
| 825 | 01 大模型微调工具与主流框架介绍 | - | AI 论文精读 | - | - | 19:17 | [link](https://www.bilibili.com/video/BV1c4jBzTEto) |
| 826 | 02 微调框架实战(1) | - | AI 论文精读 | - | - | 11:40 | [link](https://www.bilibili.com/video/BV1c4jBzTEpJ) |
| 827 | 03 微调框架实战(2) | - | AI 论文精读 | - | - | 15:23 | [link](https://www.bilibili.com/video/BV1wsjBzBE9p) |
| 828 | 01 微调方法(1) | - | AI 论文精读 | - | - | 10:04 | [link](https://www.bilibili.com/video/BV1wsjBzBEGW) |
| 829 | 02 微调方法(2) | - | AI 论文精读 | - | - | 12:48 | [link](https://www.bilibili.com/video/BV1wsjBzBEKA) |
| 830 | 01 人类对齐 | - | AI 论文精读 | - | - | 9:08 | [link](https://www.bilibili.com/video/BV1x7jBzVEbX) |
| 831 | 01 大模型评估与问题解决(1) | - | AI 论文精读 | - | - | 11:09 | [link](https://www.bilibili.com/video/BV1K7jBzVEFv) |
| 832 | 02 大模型评估与问题解决(2) | - | AI 论文精读 | - | - | 11:28 | [link](https://www.bilibili.com/video/BV1mLjBzyEAc) |
| 833 | 01 法律大模型强化学习实战 | - | AI 论文精读 | - | - | 17:38 | [link](https://www.bilibili.com/video/BV1WnjBz3Eip) |
| 834 | 02 法律大模型评估实战(1) | - | AI 论文精读 | - | - | 12:09 | [link](https://www.bilibili.com/video/BV1NnjBz3ETP) |
| 835 | 03 法律大模型评估实战(2) | - | AI 论文精读 | - | - | 10:36 | [link](https://www.bilibili.com/video/BV1PnjBz3ELn) |
| 836 | 课程介绍 | - | AI 论文精读 | - | - | 1:42 | [link](https://www.bilibili.com/video/BV1SkLtzHEkT) |
| 837 | 01 大模型推理挑战 | - | AI 论文精读 | - | - | 4:14 | [link](https://www.bilibili.com/video/BV1SkLtzHEdH) |
| 838 | 02 主流推理引擎对比 | - | AI 论文精读 | - | - | 6:08 | [link](https://www.bilibili.com/video/BV1gkLtzpEBa) |
| 839 | 03 大模型推理瓶颈分析 | - | AI 论文精读 | - | - | 17:46 | [link](https://www.bilibili.com/video/BV1DkLtzHEpD) |
| 840 | 01 vLLM环境搭建 | - | AI 论文精读 | - | - | 5:02 | [link](https://www.bilibili.com/video/BV1SkLtzHEDo) |
| 841 | 02 vLLM使用入门 | - | AI 论文精读 | - | - | 11:16 | [link](https://www.bilibili.com/video/BV1SkLtzHE2h) |
| 842 | 03 vLLM推理分析 | - | AI 论文精读 | - | - | 3:33 | [link](https://www.bilibili.com/video/BV1DkLtzHEF1) |
| 843 | 01 LoRA模型部署及实操 | - | AI 论文精读 | - | - | 18:10 | [link](https://www.bilibili.com/video/BV1gkLtzpEL4) |
| 844 | 02 多模态模型部署及实操 | - | AI 论文精读 | - | - | 13:43 | [link](https://www.bilibili.com/video/BV1gkLtzpEkd) |
| 845 | 01 vLLM量化模型支持 | - | AI 论文精读 | - | - | 3:44 | [link](https://www.bilibili.com/video/BV18kLtzpEZq) |
| 846 | 02 模型量化 | - | AI 论文精读 | - | - | 19:06 | [link](https://www.bilibili.com/video/BV1U1LtzJEWP) |
| 847 | 03 KV Cache量化 | - | AI 论文精读 | - | - | 9:04 | [link](https://www.bilibili.com/video/BV1U1LtzJEaX) |
| 848 | 01 性能测试指标(1) | - | AI 论文精读 | - | - | 15:43 | [link](https://www.bilibili.com/video/BV1U1LtzJEEB) |
| 849 | 02 性能测试指标(2) | - | AI 论文精读 | - | - | 13:16 | [link](https://www.bilibili.com/video/BV1U1LtzJE5V) |
| 850 | 03 性能测试工具 | - | AI 论文精读 | - | - | 4:55 | [link](https://www.bilibili.com/video/BV1M1LtznEme) |
| 851 | 04 性能分析 | - | AI 论文精读 | - | - | 8:52 | [link](https://www.bilibili.com/video/BV1S1LtznEM8) |
| 852 | 01 算子优化 | - | AI 论文精读 | - | - | 11:42 | [link](https://www.bilibili.com/video/BV1t1LtzEE1f) |
| 853 | 01 LLM引擎参数(1) | - | AI 论文精读 | - | - | 13:41 | [link](https://www.bilibili.com/video/BV1GjL7z8EZo) |
| 854 | 02 LLM引擎参数(2) | - | AI 论文精读 | - | - | 11:11 | [link](https://www.bilibili.com/video/BV19jL7zbEV7) |
| 855 | 03 推测解码与PD分离 | - | AI 论文精读 | - | - | 8:55 | [link](https://www.bilibili.com/video/BV1XjL7zbE4o) |
| 856 | 01 DeepSeek可视化部署(1) | - | AI 论文精读 | - | - | 13:25 | [link](https://www.bilibili.com/video/BV1wmjjzVEFC) |
| 857 | 02 DeepSeek可视化部署(2) | - | AI 论文精读 | - | - | 13:00 | [link](https://www.bilibili.com/video/BV1wmjjzVEFf) |
| 858 | 01 RAG本地部署(1) | - | AI 论文精读 | - | - | 16:47 | [link](https://www.bilibili.com/video/BV1A1jjzyELv) |
| 859 | 02 RAG本地部署(2) | - | AI 论文精读 | - | - | 20:33 | [link](https://www.bilibili.com/video/BV1w1jjzyEsX) |
| 860 | 01 vLLM+Dify构建Agent应用(1) | - | AI 论文精读 | - | - | 17:42 | [link](https://www.bilibili.com/video/BV1p1jjzyEhT) |
| 861 | 02 vLLM+Dify构建Agent应用(2) | - | AI 论文精读 | - | - | 13:29 | [link](https://www.bilibili.com/video/BV1C1jjzyEFA) |
| 862 | 03 vLLM+Dify构建Agent应用(3) | - | AI 论文精读 | - | - | 16:11 | [link](https://www.bilibili.com/video/BV1H1jjzyE9U) |
| 863 | 【AI实操 · 优化篇】01 Triton在PyTorch中的角色 | - | AI 论文精读 | - | - | 32:21 | [link](https://www.bilibili.com/video/BV1ZoRPYQE2K) |
| 864 | 【AI实操 · 优化篇】02 内核性能分析工具 | - | AI 论文精读 | - | - | 54:50 | [link](https://www.bilibili.com/video/BV1ZUQ1YtEwP) |
| 865 | 【AI实操 · 优化篇】03 Triton编译器及Pass管理器 | - | AI 论文精读 | - | - | 27:35 | [link](https://www.bilibili.com/video/BV1VYQdYJEBb) |
| 866 | 【AI实操 · 优化篇】04 Triton算子关键参数优化 | - | AI 论文精读 | - | - | 34:33 | [link](https://www.bilibili.com/video/BV1miotY3E2D) |
| 867 | 【AI实操 · 优化篇】05 Triton算子开发 | - | AI 论文精读 | - | - | 53:42 | [link](https://www.bilibili.com/video/BV193fFYkE7P) |
| 868 | 【AI实操 · 优化篇】06 Triton访存合并解析 | - | AI 论文精读 | - | - | 33:56 | [link](https://www.bilibili.com/video/BV1j6dRY8Erc) |
| 869 | 【AI实操 · 优化篇】07 Triton布局介绍 | - | AI 论文精读 | - | - | 43:48 | [link](https://www.bilibili.com/video/BV1F45HzLEHo) |
| 870 | 【AI实操 · 优化篇】08 Triton访存合并优化 | - | AI 论文精读 | - | - | 21:52 | [link](https://www.bilibili.com/video/BV1gzL2zTEq7) |
| 871 | 【AI实操 · 优化篇】09 编译优化实践(一)：代数变换 | - | AI 论文精读 | - | - | 23:21 | [link](https://www.bilibili.com/video/BV1UQEjz4EzX) |
| 872 | 【AI实操 · 优化篇】10 编译优化实践(二)：冗余去除 | - | AI 论文精读 | - | - | 16:41 | [link](https://www.bilibili.com/video/BV14TEczGE4i) |
| 873 | 【AI实操 · 优化篇】11 Triton归约操作解析 | - | AI 论文精读 | - | - | 50:01 | [link](https://www.bilibili.com/video/BV16fj8zGEjD) |
| 874 | 【AI实操 · 优化篇】12 Triton MMA操作解析：Tensor Core & MMA指令 | - | AI 论文精读 | - | - | 33:06 | [link](https://www.bilibili.com/video/BV1LnTszhEdY) |
| 875 | 【AI实操 · 优化篇】13 Triton MMA操作解析：Pipeline & Prefetch | - | AI 论文精读 | - | - | 35:15 | [link](https://www.bilibili.com/video/BV1vyN1zmEVG) |
| 876 | 深度学习模型压缩概述 | - | AI 论文精读 | - | - | 14:25 | [link](https://www.bilibili.com/video/BV1ht4y1P73i) |
| 877 | 无数据模型量化论文分享：ZeroQ | - | AI 论文精读 | - | - | 10:23 | [link](https://www.bilibili.com/video/BV1614y1T7FS) |
| 878 | 深度学习模型压缩方法（一）：模型蒸馏 | - | AI 论文精读 | - | - | 12:30 | [link](https://www.bilibili.com/video/BV1eb411971p) |
| 879 | 深度学习模型压缩方法（二）：剪枝 | - | AI 论文精读 | - | - | 11:21 | [link](https://www.bilibili.com/video/BV1pg4y1J73p) |
| 880 | 深度学习模型压缩方法（三）：量化 | - | AI 论文精读 | - | - | 11:14 | [link](https://www.bilibili.com/video/BV1bL411U747) |
| 881 | LLVM编译器入门（一）：LLVM整体设计 | - | AI 论文精读 | - | - | 13:40 | [link](https://www.bilibili.com/video/BV18j411B7TF) |
| 882 | LLVM编译器入门（二）：Clang前端 | - | AI 论文精读 | - | - | 12:35 | [link](https://www.bilibili.com/video/BV11j411B7XZ) |
| 883 | LLVM编译器入门（三）：IR优化 | - | AI 论文精读 | - | - | 14:53 | [link](https://www.bilibili.com/video/BV1fX4y1x79Y) |
| 884 | LLVM编译器入门（四）：代码生成 上 | - | AI 论文精读 | - | - | 15:33 | [link](https://www.bilibili.com/video/BV1tN411B71r) |
| 885 | LLVM编译器入门（五）：代码生成 下 | - | AI 论文精读 | - | - | 10:08 | [link](https://www.bilibili.com/video/BV1YG411o7AQ) |
| 886 | 基础篇：大语言模型推理发展 | - | AI 论文精读 | - | - | 5:42 | [link](https://www.bilibili.com/video/BV1v718BpEsV) |
| 887 | 核心篇：vLLM整体架构与请求预处理模块 | - | AI 论文精读 | - | - | 20:04 | [link](https://www.bilibili.com/video/BV1YcywBiEJ1) |
| 888 | 核心篇：vLLM 调度器模块 | - | AI 论文精读 | - | - | 19:08 | [link](https://www.bilibili.com/video/BV18tB8BFE1L) |
| 889 | 核心篇：vLLM 键值缓存管理器 | - | AI 论文精读 | - | - | 22:26 | [link](https://www.bilibili.com/video/BV1NhFjzTEKe) |
| 890 | 【AI论文救星】01 规划论文选题与结构 | - | AI 论文精读 | - | - | 2:29 | [link](https://www.bilibili.com/video/BV1NddtYvEb4) |
| 891 | 【AI论文救星】02 高效搜集整理文献 | - | AI 论文精读 | - | - | 2:11 | [link](https://www.bilibili.com/video/BV1FNdbYbE4b) |
| 892 | 【AI论文救星】03 可视化数据图表制作 | - | AI 论文精读 | - | - | 2:27 | [link](https://www.bilibili.com/video/BV1n3dgYrEcf) |
| 893 | 【AI论文救星】04 辅助写作与论文润色 | - | AI 论文精读 | - | - | 4:36 | [link](https://www.bilibili.com/video/BV1fKdbYoEm4) |
| 894 | 【AI论文救星】05 自动排版与文献格式规范 | - | AI 论文精读 | - | - | 1:40 | [link](https://www.bilibili.com/video/BV1PZdtYPEER) |
| 895 | 【AI论文救星】06 答辩PPT与讲稿生成 | - | AI 论文精读 | - | - | 3:30 | [link](https://www.bilibili.com/video/BV1kcdbYcEb6) |
| 896 | 【AI论文救星】07 毕业答辩问答模拟 | - | AI 论文精读 | - | - | 2:20 | [link](https://www.bilibili.com/video/BV1g6dAYzEiq) |
| 897 | 拥抱AI Agent~全网最详细的OpenManus本地部署教程 | - | AI 论文精读 | - | - | 7:45 | [link](https://www.bilibili.com/video/BV1w4XVY7Eou) |
| 898 | 突破常规！Julius 借 “交互式分析”，革新 AI 数据 | - | AI 论文精读 | - | - | 4:13 | [link](https://www.bilibili.com/video/BV1c7DfYPEgi) |
| 899 | 小白1分钟搞定！全网最详细的Deepseek的神仙级用法 | - | AI 论文精读 | - | - | 4:48 | [link](https://www.bilibili.com/video/BV1jb9iYMEBu) |
| 900 | 什么？？？马上开组会了~ PPT 还没做！ | - | AI 论文精读 | - | - | 3:13 | [link](https://www.bilibili.com/video/BV19aDfYXETT) |
| 901 | Deepseek+word打造会思考的智能文档 | - | AI 论文精读 | - | - | 5:26 | [link](https://www.bilibili.com/video/BV1ALQvY3E9a) |
| 902 | AI+Excel：如何让工作效率原地飞起 | - | AI 论文精读 | - | - | 5:32 | [link](https://www.bilibili.com/video/BV1JCQeYAEw8) |
| 903 | TVM简介 | - | AI 论文精读 | - | - | 14:59 | [link](https://www.bilibili.com/video/BV14N4y1c7zq) |
| 904 | TVM自动调度算法AutoTVM | - | AI 论文精读 | - | - | 14:46 | [link](https://www.bilibili.com/video/BV1114y1e7FK) |
| 905 | ANSOR：为深度学习生成高性能张量程序 | - | AI 论文精读 | - | - | 13:10 | [link](https://www.bilibili.com/video/BV1m14y1Y7LN) |
| 906 | TVM 编译流程与中间表示分析（一） | - | AI 论文精读 | - | - | 15:36 | [link](https://www.bilibili.com/video/BV1v3411U7fM) |
| 907 | TVM 编译流程与中间表示分析（二） | - | AI 论文精读 | - | - | 12:55 | [link](https://www.bilibili.com/video/BV1624y1v7wx) |
| 908 | ANSOR 优化算子代码解读（一） | - | AI 论文精读 | - | - | 12:51 | [link](https://www.bilibili.com/video/BV1ih4y127fX) |
| 909 | ANSOR优化算子代码解读（二） | - | AI 论文精读 | - | - | 6:56 | [link](https://www.bilibili.com/video/BV1C44y1c7WL) |
| 910 | ANSOR优化算子代码解读（三） | - | AI 论文精读 | - | - | 9:24 | [link](https://www.bilibili.com/video/BV1e94y167Qy) |
| 911 | ANSOR优化算子代码解读（四） | - | AI 论文精读 | - | - | 9:16 | [link](https://www.bilibili.com/video/BV1C8411X7BS) |
| 912 | TVM的量化框架（一） | - | AI 论文精读 | - | - | 10:37 | [link](https://www.bilibili.com/video/BV1ph4y1U7Dy) |
| 913 | TVM的量化框架（二） | - | AI 论文精读 | - | - | 5:44 | [link](https://www.bilibili.com/video/BV1aN4y1R7MY) |
| 914 | TVM的量化框架（三） | - | AI 论文精读 | - | - | 7:28 | [link](https://www.bilibili.com/video/BV1ur4y197zj) |
| 915 | TVM的量化框架（四） | - | AI 论文精读 | - | - | 10:52 | [link](https://www.bilibili.com/video/BV18w411S7Mh) |
| 916 | 自动并行论文分享：FlexFlow | - | AI 论文精读 | - | - | 15:52 | [link](https://www.bilibili.com/video/BV1wg411H78v) |
| 917 | 自动并行论文分享：CoCoNet | - | AI 论文精读 | - | - | 18:01 | [link](https://www.bilibili.com/video/BV1Nv4y1j78t) |
| 918 | 论文分享：新型注意力算法FlashAttention | - | AI 论文精读 | - | - | 7:24 | [link](https://www.bilibili.com/video/BV1zs4y1J7tb) |
| 919 | 自动并行—并行划分 | - | AI 论文精读 | - | - | 8:59 | [link](https://www.bilibili.com/video/BV1wo4y1L7WJ) |
| 920 | 数据并行通信优化论文分享：MG-WFBP | - | AI 论文精读 | - | - | 10:50 | [link](https://www.bilibili.com/video/BV1hj411Z7SS) |
| 921 | 自动并行论文分享：Merak | - | AI 论文精读 | - | [github.com](https://github.com/HPDL-Group/Merak) [ieeexplore.ieee.org](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10163912) | 8:58 | [link](https://www.bilibili.com/video/BV1T94y1C7i4) |
| 922 | 论文分享：并行程序自动转换 | - | AI 论文精读 | - | - | 13:10 | [link](https://www.bilibili.com/video/BV1sa4y1C7p7) |
| 923 | 论文分享：自动并行AvgPipe | - | AI 论文精读 | - | - | 15:21 | [link](https://www.bilibili.com/video/BV1rw41137QG) |
| 924 | 论文分享：自动并行AlpaServe | - | AI 论文精读 | - | - | 17:28 | [link](https://www.bilibili.com/video/BV1wc411m7ki) |
| 925 | 论文分享：自动并行Alpa | - | AI 论文精读 | - | - | 15:25 | [link](https://www.bilibili.com/video/BV11j41177TQ) |
| 926 | 论文分享：高性能计算领域大语言模型HPC-Coder | - | AI 论文精读 | - | - | 12:46 | [link](https://www.bilibili.com/video/BV1e4421c7Gk) |
| 927 | 自编教材分享：第一章—程序性能优化的意义（一） | - | AI 论文精读 | - | - | 9:08 | [link](https://www.bilibili.com/video/BV1LL411B7uW) |
| 928 | 自编教材分享：第一章—程序性能优化的意义（二） | - | AI 论文精读 | - | - | 6:53 | [link](https://www.bilibili.com/video/BV15g4y1F7QQ) |
| 929 | 自编教材分享：第二章—程序性能的度量指标及优化流程（一） | - | AI 论文精读 | - | - | 12:03 | [link](https://www.bilibili.com/video/BV1vu411s7Xw) |
| 930 | 自编教材分享：第三章—程序性能的分析和测量（一） | - | AI 论文精读 | - | - | 13:36 | [link](https://www.bilibili.com/video/BV1ZV4y1U7wr) |
| 931 | 自编教材分享：第三章—程序性能的分析和测量（二） | - | AI 论文精读 | - | - | 15:50 | [link](https://www.bilibili.com/video/BV11k4y1p7Bw) |
| 932 | 自编教材分享：第三章—程序性能的分析和测量（三） | - | AI 论文精读 | - | - | 15:14 | [link](https://www.bilibili.com/video/BV1Wm4y1v7yZ) |
| 933 | 自编教材分享：第四章—系统配置优化（一） | - | AI 论文精读 | - | - | 11:31 | [link](https://www.bilibili.com/video/BV1go4y1K72Y) |
| 934 | 自编教材分享：第四章—系统配置优化（二） | - | AI 论文精读 | - | - | 9:39 | [link](https://www.bilibili.com/video/BV12o4y1P7kW) |
| 935 | 自编教材分享：第五章—编译与运行优化 | - | AI 论文精读 | - | - | 54:05 | [link](https://www.bilibili.com/video/BV1KN4y1L7XT) |
| 936 | 自编教材分享：第六章—程序编写优化（一） | - | AI 论文精读 | - | - | 10:11 | [link](https://www.bilibili.com/video/BV1gX4y1q7Ms) |
| 937 | 自编教材分享：第六章—程序编写优化（二） | - | AI 论文精读 | - | - | 9:01 | [link](https://www.bilibili.com/video/BV1Aj411S7kJ) |
| 938 | 自编教材分享：第六章—程序编写优化（三） | - | AI 论文精读 | - | - | 6:04 | [link](https://www.bilibili.com/video/BV1sg4y1N763) |
| 939 | 自编教材分享：第六章—程序编写优化（四） | - | AI 论文精读 | - | - | 9:29 | [link](https://www.bilibili.com/video/BV1rh411A79q) |
| 940 | 自编教材分享：第六章—程序编写优化（五） | - | AI 论文精读 | - | - | 8:11 | [link](https://www.bilibili.com/video/BV1mz4y1E7rb) |
| 941 | 自编教材分享：第七章—指令级并行（一） | - | AI 论文精读 | - | - | 9:03 | [link](https://www.bilibili.com/video/BV1iV4y1h7wm) |
| 942 | 自编教材分享：第七章—指令级并行（二） | - | AI 论文精读 | - | - | 8:14 | [link](https://www.bilibili.com/video/BV1ym4y1E783) |
| 943 | 自编教材分享：第七章—数据级并行（一） | - | AI 论文精读 | - | - | 13:28 | [link](https://www.bilibili.com/video/BV1M94y1q7B4) |
| 944 | 自编教材分享：第七章—数据级并行（二） | - | AI 论文精读 | - | - | 11:26 | [link](https://www.bilibili.com/video/BV1Wj411R74A) |
| 945 | 自编教材分享：第七章—数据级并行（三） | - | AI 论文精读 | - | - | 15:23 | [link](https://www.bilibili.com/video/BV1Kk4y1G77z) |
| 946 | 自编教材分享：第八章—访存优化（一） | - | AI 论文精读 | - | - | 7:21 | [link](https://www.bilibili.com/video/BV1yz4y1s7qp) |
| 947 | 自编教材分享：第八章—访存优化（二） | - | AI 论文精读 | - | - | 11:08 | [link](https://www.bilibili.com/video/BV1fM4y1H7Ba) |
| 948 | 自编教材分享：第八章—访存优化（三） | - | AI 论文精读 | - | - | 10:10 | [link](https://www.bilibili.com/video/BV18m4y1W7fH) |
| 949 | 自编教材分享：第八章—访存优化（四） | - | AI 论文精读 | - | - | 8:51 | [link](https://www.bilibili.com/video/BV1Np4y1776Z) |
| 950 | 自编教材分享：第八章—访存优化（五） | - | AI 论文精读 | - | - | 6:29 | [link](https://www.bilibili.com/video/BV1gw411D7Bw) |
| 951 | 自编教材分享：第八章—访存优化（六） | - | AI 论文精读 | - | - | 8:03 | [link](https://www.bilibili.com/video/BV1cp4y1j7ga) |
| 952 | 自编教材分享：第九章—OpenMP编程简介 | - | AI 论文精读 | - | - | 10:55 | [link](https://www.bilibili.com/video/BV1Zw411U7a8) |
| 953 | 自编教材分享：第九章—并行区重构 | - | AI 论文精读 | - | - | 9:04 | [link](https://www.bilibili.com/video/BV1eu411A79T) |
| 954 | 自编教材分享：第九章—向量化指导命令 | - | AI 论文精读 | - | - | 4:47 | [link](https://www.bilibili.com/video/BV12h4y1Y7vH) |
| 955 | 自编教材分享：第九章—避免伪共享 | - | AI 论文精读 | - | - | 7:04 | [link](https://www.bilibili.com/video/BV1Gw411i7rS) |
| 956 | 自编教材分享：第九章—负载均衡优化 | - | AI 论文精读 | - | - | 9:45 | [link](https://www.bilibili.com/video/BV1XN4y1o7NQ) |
| 957 | 自编教材分享：第九章—避免隐式同步 | - | AI 论文精读 | - | - | 6:34 | [link](https://www.bilibili.com/video/BV19u4y1x7CS) |
| 958 | 自编教材分享：第九章—流水并行优化 | - | AI 论文精读 | - | - | 13:24 | [link](https://www.bilibili.com/video/BV1LB4y1Z74v) |
| 959 | 自编教材分享：第十章—CUDA程序优化（一） | - | AI 论文精读 | - | - | 12:57 | [link](https://www.bilibili.com/video/BV1pB4y1f7Md) |
| 960 | 自编教材分享：第十章—CUDA程序优化（二） | - | AI 论文精读 | - | - | 13:50 | [link](https://www.bilibili.com/video/BV1C94y187iq) |
| 961 | 自编教材分享：第十章—CUDA程序优化（三） | - | AI 论文精读 | - | - | 14:50 | [link](https://www.bilibili.com/video/BV1Kw411z7Wd) |
| 962 | 自编教材分享：第十章—CUDA程序优化（四） | - | AI 论文精读 | - | - | 9:10 | [link](https://www.bilibili.com/video/BV1G84y1R7Ak) |
| 963 | 自编教材分享：第十一章—MPI程序简介 | - | AI 论文精读 | - | - | 7:17 | [link](https://www.bilibili.com/video/BV1cj411a7Sb) |
| 964 | 自编教材分享：第十一章—MPI程序简介（二） | - | AI 论文精读 | - | - | 7:08 | [link](https://www.bilibili.com/video/BV1ra4y1m7JP) |
| 965 | 自编教材分享：第十一章—数据划分优化 | - | AI 论文精读 | - | - | 12:15 | [link](https://www.bilibili.com/video/BV1Lc411b7Fw) |
| 966 | 深度学习的产生与发展 | - | AI 论文精读 | - | - | 13:35 | [link](https://www.bilibili.com/video/BV1AM411P7JG) |
| 967 | 深度神经网络的结构 | - | AI 论文精读 | - | - | 10:35 | [link](https://www.bilibili.com/video/BV1bD4y1G7oV) |
| 968 | 神经网络的运行机制 | - | AI 论文精读 | - | - | 10:59 | [link](https://www.bilibili.com/video/BV1xs4y1b7nt) |
| 969 | CNN-卷积神经网络（一） | - | AI 论文精读 | - | - | 12:51 | [link](https://www.bilibili.com/video/BV1iL411o7iz) |
| 970 | CNN-卷积神经网络（二） | - | AI 论文精读 | - | - | 10:54 | [link](https://www.bilibili.com/video/BV1bL411o74W) |
| 971 | 【直播回放】FlagOS开源社区“高性能计算实训营” 2025年08月16日09点场 | - | AI 论文精读 | - | - | 271:31 | [link](https://www.bilibili.com/video/BV18XYnzVEWa) |
| 972 | 【直播回放】FlagOS开源社区“高性能计算实训营” 2025年08月16日14点场 | - | AI 论文精读 | - | - | 206:54 | [link](https://www.bilibili.com/video/BV1bXYnzVEQV) |
| 973 | 【直播回放】FlagOS开源社区“高性能计算实训营” 2025年08月17日08点场 | - | AI 论文精读 | - | - | 234:06 | [link](https://www.bilibili.com/video/BV18XYnzVEJv) |
| 974 | 【直播回放】FlagOS开源社区“高性能计算实训营” 2025年08月17日13点场 | - | AI 论文精读 | - | - | 323:22 | [link](https://www.bilibili.com/video/BV1wQYWzrEBz) |
| 975 | OpenAI triton分享：Triton概述 | - | AI 论文精读 | - | - | 5:24 | [link](https://www.bilibili.com/video/BV1Kr421M7rt) |
| 976 | OpenAI triton分享：Triton安装教程 | - | AI 论文精读 | - | - | 5:44 | [link](https://www.bilibili.com/video/BV1b9W8eQEW3) |
| 977 | OpenAI triton分享：triton程序编写 | - | AI 论文精读 | - | - | 7:15 | [link](https://www.bilibili.com/video/BV154421S7TE) |
| 978 | OpenAI triton分享：triton源码结构 | - | AI 论文精读 | - | - | 8:17 | [link](https://www.bilibili.com/video/BV1SHxWeTEMe) |
| 979 | OpenAI triton分享：triton编译流程 | - | AI 论文精读 | - | - | 12:19 | [link](https://www.bilibili.com/video/BV1Di2CYcEba) |
| 980 | OpenAI triton分享：triton调试方法及工具（上） | - | AI 论文精读 | - | - | 8:27 | [link](https://www.bilibili.com/video/BV1aY2CYAEhy) |
| 981 | OpenAI triton分享：triton调试方法及工具（下） | - | AI 论文精读 | - | - | 6:40 | [link](https://www.bilibili.com/video/BV1m6C1YsEn1) |
| 982 | OpenAI triton分享：triton IR 剖析（上） | - | AI 论文精读 | - | - | 12:06 | [link](https://www.bilibili.com/video/BV1EwzyYZELz) |
| 983 | OpenAI triton分享：triton IR 剖析（下） | - | AI 论文精读 | - | - | 11:01 | [link](https://www.bilibili.com/video/BV1AHCJYkESY) |
| 984 | 计算机视觉与OpenMMLab 开源算法体系 | - | AI 论文精读 | - | - | 47:38 | [link](https://www.bilibili.com/video/BV1WG41177DP) |
| 985 | 深度学习算法基础 | - | AI 论文精读 | - | - | 65:34 | [link](https://www.bilibili.com/video/BV1gP411N7yA) |
| 986 | 上海交大学生创新中心人工智能实训平台介绍 | - | AI 论文精读 | - | - | 14:47 | [link](https://www.bilibili.com/video/BV1CV4y1V7SQ) |
| 987 | 图像分类 | - | AI 论文精读 | - | - | 68:54 | [link](https://www.bilibili.com/video/BV11G4y1n7gC) |
| 988 | MMClassification 介绍与代码实践 | - | AI 论文精读 | - | - | 51:53 | [link](https://www.bilibili.com/video/BV1LP411N7G4) |
| 989 | MMClassification 实践 2 | - | AI 论文精读 | - | - | 33:50 | [link](https://www.bilibili.com/video/BV1be4y1e7uS) |
| 990 | 目标检测 | - | AI 论文精读 | - | - | 56:52 | [link](https://www.bilibili.com/video/BV1BG4y1n7pn) |
| 991 | MMDetection 介绍与代码实践 | - | AI 论文精读 | - | - | 37:02 | [link](https://www.bilibili.com/video/BV1o8411Y7Td) |
| 992 | 数据集采集与标注、LabelBee工具介绍 | - | AI 论文精读 | - | - | 80:29 | [link](https://www.bilibili.com/video/BV16W4y1E74Z) |
| 993 | 模型部署与 MMDeploy 实践 | - | AI 论文精读 | - | - | 29:14 | [link](https://www.bilibili.com/video/BV1Ne411G7RX) |
| 994 | 语义分割与 MMSegmentation 实践 | - | AI 论文精读 | - | - | 32:49 | [link](https://www.bilibili.com/video/BV1fP411A74D) |
| 995 | 文字字符识别与 MMOCR 实践 | - | AI 论文精读 | - | - | 16:31 | [link](https://www.bilibili.com/video/BV1Qe4y1e7fH) |
| 996 | 人体姿态估计与 MMPose 实践 | - | AI 论文精读 | - | - | 56:20 | [link](https://www.bilibili.com/video/BV1Hg411z7Qk) |
| 997 | 视频目标追踪与 MMTracking 实践 | - | AI 论文精读 | - | - | 23:51 | [link](https://www.bilibili.com/video/BV14t4y1T7rd) |
| 998 | 生成模型 GAN 与 MMGeneration 实践 | - | AI 论文精读 | - | - | 43:33 | [link](https://www.bilibili.com/video/BV1SK411D7uS) |
| 999 | 强化学习RL是否可以提升模型性能上限？亦或只是将模型的Pass@N向Pass@1收敛？ | - | AI 论文精读 | - | - | 10:09 | [link](https://www.bilibili.com/video/BV1saNbzQEwT) |
| 1000 | RLVR对推理能力的提升是否可以/如何才能泛化到通用能力？ | - | AI 论文精读 | - | - | 4:21 | [link](https://www.bilibili.com/video/BV1Q1Nez7E2t) |
| 1001 | 过去的PPO算法依赖于四个神经网络来进行稳定训练，近期以DAPO为代表的算法只需要一个policy model，是什么带来了模型训练稳定性的提升？ | - | AI 论文精读 | - | - | 9:27 | [link](https://www.bilibili.com/video/BV1THNBznEkF) |
| 1002 | 近期一些工作针对RL提出了一系列反直觉的结论，例如random reward也能提升性能，如何看待这些结论？ | - | AI 论文精读 | - | - | 5:29 | [link](https://www.bilibili.com/video/BV1SjNLzsEjq) |
| 1003 | 当前多模态领域的RL算法往往是纯语言领域RL算法的“应用”迁移，除了引入图像condition以外没有太多改进，如何针对多模态引入算法改进？ | - | AI 论文精读 | - | - | 8:56 | [link](https://www.bilibili.com/video/BV1TzN5zDE5V) |
| 1004 | 如何看待预训练数据/性能对RL效果的影响？ | - | AI 论文精读 | - | - | 7:55 | [link](https://www.bilibili.com/video/BV1oNN7z6Ecq) |
| 1005 | 零人工数据强化学习推理模型主题分享 | - | AI 论文精读 | - | - | 31:30 | [link](https://www.bilibili.com/video/BV1irNszFEtt) |
| 1006 | 小米 MiMo-VL 预训练及后训练技术分享 | - | AI 论文精读 | - | - | 30:41 | [link](https://www.bilibili.com/video/BV1xuKwz2Ejp) |
| 1007 | 强化学习范式 OREAL：超越蒸馏，推动轻中量级模型突破推理“三重门”困局 | - | AI 论文精读 | - | - | 21:31 | [link](https://www.bilibili.com/video/BV1BCKczeEJa) |
| 1008 | CPRet：面向编程竞赛检索的基准数据集和模型 | - | AI 论文精读 | - | - | 22:38 | [link](https://www.bilibili.com/video/BV1kFGgzjEtu) |
| 1009 | DyCodeEval: 数据污染下的代码模型的动态测评 | - | AI 论文精读 | - | - | 22:04 | [link](https://www.bilibili.com/video/BV1QrGuzbEPH) |
| 1010 | OSS-Bench：告别静态数据集！从真实开源项目中“活捉”高难度编程任务 | - | AI 论文精读 | - | - | 17:37 | [link](https://www.bilibili.com/video/BV1GauuzREiY) |
| 1011 | UTBoost：修复“漏风”的 SWE-Bench，揪出 345 个“假通过”补丁 | - | AI 论文精读 | - | - | 21:19 | [link](https://www.bilibili.com/video/BV1qtu3zKEq9) |
| 1012 | 上海人工智能实验室 大模型中心负责人 陈恺 深度解读 Intern-S1——科学多模态大模型 | - | AI 论文精读 | - | [chat.intern-ai.org.cn](https://chat.intern-ai.org.cn/) [huggingface.co](https://huggingface.co/InternLM) [modelscope.cn](https://modelscope.cn/organization/Shanghai_AI_Laboratory) | 14:48 | [link](https://www.bilibili.com/video/BV1K3agzBE9i) |
| 1013 | MiniCPM-V：迈向高效端侧多模态大模型 | - | AI 论文精读 | - | [huggingface.co](https://huggingface.co/openbmb) [modelscope.cn](https://modelscope.cn/organization/OpenBMB) | 13:33 | [link](https://www.bilibili.com/video/BV1VZaCzLEJr) |
| 1014 | GLM-V：迈向通用推理的多模态大模型 | - | AI 论文精读 | - | [huggingface.co](https://huggingface.co/zai-org) [modelscope.cn](https://modelscope.cn/organization/ZhipuAI) | 14:44 | [link](https://www.bilibili.com/video/BV1C9ahzbEmG) |
| 1015 | Ovis多模态大模型：结构对齐下的视觉语言融合 | - | AI 论文精读 | - | [huggingface.co](https://huggingface.co/AIDC-AI) [modelscope.cn](https://modelscope.cn/organization/AIDC-AI) | 14:26 | [link](https://www.bilibili.com/video/BV168HUzkEEZ) |
| 1016 | 阶跃星辰在多模态方向上的探索 | - | AI 论文精读 | - | [huggingface.co](https://huggingface.co/stepfun-ai) [modelscope.cn](https://modelscope.cn/organization/stepfun-ai) | 15:46 | [link](https://www.bilibili.com/video/BV1jAHXzmEao) |
| 1017 | 多模态模型哪些能力已逐渐饱和，还存在哪些不足和短板，未来有哪些值得关注的应用方向? | - | AI 论文精读 | - | - | 6:27 | [link](https://www.bilibili.com/video/BV1Y3HazDE2m) |
| 1018 | 多模态模型的推理相比于语言模型，有哪些不一样的技术挑战和发展思路？ | - | AI 论文精读 | - | - | 6:27 | [link](https://www.bilibili.com/video/BV1s1pWzJEGJ) |
| 1019 | 理解生成一体化是近期多模态大模型的热门探索方向，技术方案有什么样的演进趋势，未来是否有可能实现理解和生成任务的互相促进? | - | AI 论文精读 | - | - | 13:39 | [link](https://www.bilibili.com/video/BV1zCJkzQEmp) |
| 1020 | 多模态模型的突破是否被语言模型的研究进展所限制？模型架构和训练范式上有哪些创新路径？ | - | AI 论文精读 | - | - | 4:00 | [link](https://www.bilibili.com/video/BV1VFpCzQEG6) |
| 1021 | LongCat-Flash-Omni：美团全模态大模型探索 | - | AI 论文精读 | - | [huggingface.co](https://huggingface.co/meituan-longcat/LongCat-Flash-Omni) [modelscope.cn](https://modelscope.cn/models/meituan-longcat/LongCat-Flash-Omni) | 24:34 | [link](https://www.bilibili.com/video/BV16jyuBBEZ8) |
| 1022 | OmniVinci：全模态大模型的架构和数据探索 | - | AI 论文精读 | - | [huggingface.co](https://huggingface.co/nvidia/omnivinci) | 14:57 | [link](https://www.bilibili.com/video/BV1FFU5B8E9x) |
| 1023 | Ming-Omni：百灵多模态的实践与探索 | - | AI 论文精读 | - | [huggingface.co](https://huggingface.co/inclusionAI/Ming-flash-omni-Preview) [modelscope.cn](https://modelscope.cn/models/inclusionAI/Ming-flash-omni-Preview) | 43:18 | [link](https://www.bilibili.com/video/BV1oeUbBaEGt) |
| 1024 | Omni 全模态模型在训练数据和策略上面临哪些挑战？如何构建和利用涵盖图像、视 频、音频、文本的海量数据集，并采用何种训练策略技巧来有效融合多模态信息的？ | - | AI 论文精读 | - | - | 9:56 | [link](https://www.bilibili.com/video/BV1ZPSaBCEXH) |
| 1025 | 在多模态统一模型中，模态不均衡或者模态偏置问题如何解决？ | - | AI 论文精读 | - | - | 6:25 | [link](https://www.bilibili.com/video/BV1to28BUEdg) |
| 1026 | 在长上下文建模方面，模型如何真正利用极长序列？例如视频长达上万帧，或多轮对话跨越很长距离，模型如何保留和利用这些信息？ | - | AI 论文精读 | - | - | 6:38 | [link](https://www.bilibili.com/video/BV1Q625B5Eyp) |
| 1027 | 如何看待通用模态 tokenization 未来面临的挑战？所有模态用统一“词表”表示是否现实？ | - | AI 论文精读 | - | - | 7:13 | [link](https://www.bilibili.com/video/BV1cG2kBMEQ9) |
| 1028 | 在一个模型中同时学习理解任务和生成任务会不会互相促进？可以从哪些技术路线去突破？ | - | AI 论文精读 | - | - | 5:02 | [link](https://www.bilibili.com/video/BV1dNmKBFExt) |
| 1029 | Omni 全模态模型的发展趋势是什么，可能会朝哪些新方向拓展？还有哪些关键技术要突破？ | - | AI 论文精读 | - | - | 3:59 | [link](https://www.bilibili.com/video/BV12VmCBJEK7) |
| 1030 | HunyuanOCR：混元原生多模态端到端 OCR 专家 | - | AI 论文精读 | - | [huggingface.co](https://huggingface.co/spaces/tencent/HunyuanOCR) [modelscope.cn](https://modelscope.cn/models/Tencent-Hunyuan/HunyuanOCR) | 28:06 | [link](https://www.bilibili.com/video/BV1SBBVBEEMp) |
| 1031 | PaddleOCR-VL：支持 109 种语言的轻量化多模态文档解析方案 | - | AI 论文精读 | - | [huggingface.co](https://huggingface.co/PaddlePaddle/PaddleOCR-VL) [modelscope.cn](https://modelscope.cn/models/PaddlePaddle/PaddleOCR-VL) | 24:03 | [link](https://www.bilibili.com/video/BV16CBDBzEHJ) |
| 1032 | MinerU：高效精准的文档解析技术攻坚 | - | AI 论文精读 | - | [huggingface.co](https://huggingface.co/opendatalab/MinerU2.5-2509-1.2B) [modelscope.cn](https://modelscope.cn/models/OpenDataLab/MinerU2.5-2509-1.2B) [github.com](https://github.com/opendatalab/MinerU) | 23:21 | [link](https://www.bilibili.com/video/BV1epBaB3EPA) |
| 1033 | 极致端侧推理、结构还原与语义泛化三者之间存在天然的张力，在设计模型架构或训练策略时，如何权衡这三者之间的 trade-off 的？ | - | AI 论文精读 | - | - | 9:51 | [link](https://www.bilibili.com/video/BV1WZqFBPEjU) |
| 1034 | OCR 模型是否还有必要加入推理能力吗？主要会用于什么样的场景，会用怎样的形式出现？ | - | AI 论文精读 | - | - | 4:48 | [link](https://www.bilibili.com/video/BV1ZhqwB8EEr) |
| 1035 | OCR 系统在工程落地过程中，常见的性能瓶颈或优化难点有哪些？能否分享一些踩坑经验，尤其是在部署、推理效率或模型压缩方面的教训？ | - | AI 论文精读 | - | - | 2:57 | [link](https://www.bilibili.com/video/BV1MCquBvEfK) |
| 1036 | 如果从头搭建一个面向真实商业场景的文档解析系统（如合同、发票、报表等），有哪些关键建议可以给到开发者？ | - | AI 论文精读 | - | - | 2:52 | [link](https://www.bilibili.com/video/BV1RCiCBzERG) |
| 1037 | 从开源视角看，当前 OCR 工业级工具链或范式还有哪些关键缺失？如果不考虑商业化,最想推动或实现的 OCR 方向是什么？ | - | AI 论文精读 | - | - | 3:34 | [link](https://www.bilibili.com/video/BV1B8iDBaEgF) |
| 1038 | 能否分享最近关注、但本次尚未提及的 OCR 前沿工作？对于希望参与贡献开源项目的开发者，有哪些建议？ | - | AI 论文精读 | - | - | 8:36 | [link](https://www.bilibili.com/video/BV1NUrwBXEDj) |
| 1039 | 下一代多模态大模型能力演进的度量分析 | - | AI 论文精读 | - | - | 32:49 | [link](https://www.bilibili.com/video/BV1XUrhBLEsK) |
| 1040 | 基于多模态大模型的图像评价及应用探索 | - | AI 论文精读 | - | - | 12:51 | [link](https://www.bilibili.com/video/BV1pWr6BWEGv) |
| 1041 | 探索大模型的通用科学能力边界 | - | AI 论文精读 | - | - | 40:45 | [link](https://www.bilibili.com/video/BV1CLrLBXEoo) |
| 1042 | NewtonBench：在“平行宇宙”中评估大模型科学发现能力 | - | AI 论文精读 | - | - | 20:36 | [link](https://www.bilibili.com/video/BV1oVrzB3E2y) |
| 1043 | ScienceBoard: 从数字智能体到 AI 科学家 | - | AI 论文精读 | - | - | 29:39 | [link](https://www.bilibili.com/video/BV1FJhwzTEQH) |
| 1044 | AutoMind: 知识增强智能体解锁数据科学潜力 | - | AI 论文精读 | - | - | 28:15 | [link](https://www.bilibili.com/video/BV1oNhczoEM9) |
| 1045 | Scientists’ First Exam，科学认知能力的“开场哨声” | - | AI 论文精读 | - | - | 26:58 | [link](https://www.bilibili.com/video/BV1pWh7zUEMb) |
| 1046 | 圆桌讨论——科学智能的边界与突破 | - | AI 论文精读 | - | - | 49:13 | [link](https://www.bilibili.com/video/BV1X1tgzzEBH) |
| 1047 | 大模型评测基准发展趋势探讨 | - | AI 论文精读 | - | - | 24:08 | [link](https://www.bilibili.com/video/BV1AbrHBME4n) |
| 1048 | 技术写作系列课程第一课：技术写作的内容风格与选题 | - | AI 论文精读 | - | [mp.weixin.qq.com](https://mp.weixin.qq.com/s?__biz=MzI4MDcxNTY2MQ==&mid=2247510508&idx=1&sn=3072808c7889d1b6dacaf032c8e9dc19&chksm=ebb6a10edcc128186649d95af2132fa88ec1ac30d004c00fb52291ec5e2019b75042bb4b66f1&token=238828277&lang=zh_CN#rd) | 36:27 | [link](https://www.bilibili.com/video/BV1YX4y1B7mH) |
| 1049 | 技术写作系列课程第二课：如何起一个吸引人的标题 | - | AI 论文精读 | - | [mp.weixin.qq.com](https://mp.weixin.qq.com/s?__biz=MzI4MDcxNTY2MQ==&mid=2247510508&idx=1&sn=3072808c7889d1b6dacaf032c8e9dc19&chksm=ebb6a10edcc128186649d95af2132fa88ec1ac30d004c00fb52291ec5e2019b75042bb4b66f1&token=238828277&lang=zh_CN#rd) | 19:47 | [link](https://www.bilibili.com/video/BV1qs4y1d7jm) |
| 1050 | 技术写作系列课程第三课：如何搭建文章结构 | - | AI 论文精读 | - | [mp.weixin.qq.com](https://mp.weixin.qq.com/s?__biz=MzI4MDcxNTY2MQ==&mid=2247510508&idx=1&sn=3072808c7889d1b6dacaf032c8e9dc19&chksm=ebb6a10edcc128186649d95af2132fa88ec1ac30d004c00fb52291ec5e2019b75042bb4b66f1&token=238828277&lang=zh_CN#rd) | 32:48 | [link](https://www.bilibili.com/video/BV1oc411E7nD) |
| 1051 | 技术写作系列课程第四课：技术写作必备的利器工具 | - | AI 论文精读 | - | [mp.weixin.qq.com](https://mp.weixin.qq.com/s?__biz=MzI4MDcxNTY2MQ==&mid=2247510508&idx=1&sn=3072808c7889d1b6dacaf032c8e9dc19&chksm=ebb6a10edcc128186649d95af2132fa88ec1ac30d004c00fb52291ec5e2019b75042bb4b66f1&token=238828277&lang=zh_CN#rd) | 44:11 | [link](https://www.bilibili.com/video/BV1Tg4y1777V) |
| 1052 | Label Studio x Segment Anything Model 半自动化标注 | - | AI 论文精读 | - | [github.com](https://github.com/open-mmlab/playground/blob/main/label_anything/readme_zh.md) [cdn.vansin.top](https://cdn.vansin.top/open-mmlab/pg.jpg) | 0:22 | [link](https://www.bilibili.com/video/BV1uv4y1J7yM) |
| 1053 | Label-Studio X Segment Anything Model 半自动化标注（2）：Windows CPU 环境配置 | - | AI 论文精读 | - | [github.com](https://github.com/open-mmlab/playground/blob/main/label_anything/readme_zh.md) [cdn.vansin.top](https://cdn.vansin.top/open-mmlab/pg.jpg) | 2:43 | [link](https://www.bilibili.com/video/BV1hh411F7uR) |
| 1054 | Label-Studio X Segment Anything Model 半自动化标注（3）：开启前后端并标注 | - | AI 论文精读 | - | [github.com](https://github.com/open-mmlab/playground/blob/main/label_anything/readme_zh.md) [cdn.vansin.top](https://cdn.vansin.top/open-mmlab/pg.jpg) | 5:56 | [link](https://www.bilibili.com/video/BV1Fo4y1V77n) |
| 1055 | Label-Studio X Segment Anything Model 半自动化标注（4）：数据集可视化及模型训练和测试 | - | AI 论文精读 | - | [github.com](https://github.com/open-mmlab/playground/blob/main/label_anything/readme_zh.md) [cdn.vansin.top](https://cdn.vansin.top/open-mmlab/pg.jpg) | 7:21 | [link](https://www.bilibili.com/video/BV1Lh4y1o7qN) |
| 1056 | 以最新数学博资考题为例，书生-S2可以围绕一道复杂问题进行数小时的持续探索 | - | AI 论文精读 | - | [chat.intern-ai.org.cn](https://chat.intern-ai.org.cn/intern-s1-math-research/CCQRPo7AqQJjn5hXHaO4VopPQh1Z89ONciSGUKmgFFA=/9) [chat.intern-ai.org.cn](https://chat.intern-ai.org.cn/) [github.com](https://github.com/InternLM/Intern-S1) | 7:54 | [link](https://www.bilibili.com/video/BV1L8eE6NEk3) |
| 1057 | 书生-S2 实现结合疾病靶标的蛋白药物的自主设计 | - | AI 论文精读 | - | [chat.intern-ai.org.cn](https://chat.intern-ai.org.cn/case/Intern-S2/protein-design) [chat.intern-ai.org.cn](https://chat.intern-ai.org.cn/) [github.com](https://github.com/InternLM/Intern-S1) | 0:28 | [link](https://www.bilibili.com/video/BV1fHeE6zESc) |
| 1058 | 基于给定的化学式，书生-S2 实现物理可行的晶体构建 | - | AI 论文精读 | - | [chat.intern-ai.org.cn](https://chat.intern-ai.org.cn/case/Intern-S2/crystal-structure-construction) [chat.intern-ai.org.cn](https://chat.intern-ai.org.cn/) [github.com](https://github.com/InternLM/Intern-S1) | 0:29 | [link](https://www.bilibili.com/video/BV1JneE63EUa) |
| 1059 | “书生-S2，帮我构建一个长征7火箭的3D CAD模型” | - | AI 论文精读 | - | [chat.intern-ai.org.cn](https://chat.intern-ai.org.cn/) [github.com](https://github.com/InternLM/Intern-S1) [internlm.intern-ai.org.cn](https://internlm.intern-ai.org.cn/api/strategy) | 1:08 | [link](https://www.bilibili.com/video/BV1RQe76cEAg) |
| 1060 | Linux 前置基础知识 | - | AI 论文精读 | - | [github.com](https://github.com/InternLM/Tutorial/tree/camp3/docs/L0/Linux) [wjx.cn](https://www.wjx.cn/vm/PvefmG2.aspx?sojumpparm=openmmlabbz) [github.com](https://github.com/InternLM/Tutorial) | 15:01 | [link](https://www.bilibili.com/video/BV1FS421d7yg) |
| 1061 | Python 前置基础知识 | - | AI 论文精读 | - | [github.com](https://github.com/InternLM/Tutorial/tree/camp3/docs/L0/Python) [wjx.cn](https://www.wjx.cn/vm/PvefmG2.aspx?sojumpparm=openmmlabbz) [github.com](https://github.com/InternLM/Tutorial) | 13:49 | [link](https://www.bilibili.com/video/BV1mS421X7h4) |
| 1062 | Git 前置基础知识 | - | AI 论文精读 | - | [github.com](https://github.com/InternLM/Tutorial/tree/camp3/docs/L0/Git) [wjx.cn](https://www.wjx.cn/vm/PvefmG2.aspx?sojumpparm=openmmlabbz) [github.com](https://github.com/InternLM/Tutorial) | 6:06 | [link](https://www.bilibili.com/video/BV1Pz421i7bw) |
| 1063 | 书生·浦语大模型全链路开源开放体系 | - | AI 论文精读 | - | [wjx.cn](https://www.wjx.cn/vm/PvefmG2.aspx?sojumpparm=openmmlabbz) [github.com](https://github.com/InternLM/Tutorial) | 29:02 | [link](https://www.bilibili.com/video/BV18142187g5) |
| 1064 | 8G 显存玩转书生大模型 Demo | - | AI 论文精读 | - | [github.com](https://github.com/InternLM/Tutorial/blob/camp3/docs/L1/Demo/readme.md) [wjx.cn](https://www.wjx.cn/vm/PvefmG2.aspx?sojumpparm=openmmlabbz) [github.com](https://github.com/InternLM/Tutorial) | 8:08 | [link](https://www.bilibili.com/video/BV18x4y147SU) |
| 1065 | 浦语提示词工程实践 | - | AI 论文精读 | - | [github.com](https://github.com/InternLM/Tutorial/tree/camp3/docs/L1/Prompt) [wjx.cn](https://www.wjx.cn/vm/PvefmG2.aspx?sojumpparm=openmmlabbz) [github.com](https://github.com/InternLM/Tutorial) | 55:17 | [link](https://www.bilibili.com/video/BV1cU411S7iV) |
| 1066 | InternLM+LlamaIndex RAG 实践 | - | AI 论文精读 | - | [github.com](https://github.com/InternLM/Tutorial/tree/camp3/docs/L1/LlamaIndex) [github.com](https://github.com/InternLM/Tutorial/blob/camp3/docs/L1/LlamaIndex/task.md) [wjx.cn](https://www.wjx.cn/vm/PvefmG2.aspx?sojumpparm=openmmlabbz) | 55:20 | [link](https://www.bilibili.com/video/BV19E4m1X79q) |
| 1067 | XTuner 微调大模型个人小助手认知 | - | AI 论文精读 | - | [github.com](https://github.com/InternLM/Tutorial/tree/camp3/docs/L1/XTuner) [wjx.cn](https://www.wjx.cn/vm/PvefmG2.aspx?sojumpparm=openmmlabbz) [github.com](https://github.com/InternLM/Tutorial) | 23:59 | [link](https://www.bilibili.com/video/BV1tz421B72y) |
| 1068 | OpenCompass 评测 InternLM-1.8B 实践 | - | AI 论文精读 | - | [github.com](https://github.com/InternLM/Tutorial/blob/camp3/docs/L1/OpenCompass/readme.md) [wjx.cn](https://www.wjx.cn/vm/PvefmG2.aspx?sojumpparm=openmmlabbz) [github.com](https://github.com/InternLM/Tutorial) | 21:15 | [link](https://www.bilibili.com/video/BV1RM4m1279j) |
| 1069 | Lagent 自定义你的 Agent 智能体 | - | AI 论文精读 | - | [github.com](https://github.com/InternLM/Tutorial/blob/camp3/docs/L2/Lagent/readme.md) [wjx.cn](https://www.wjx.cn/vm/PvefmG2.aspx?sojumpparm=openmmlabbz) [github.com](https://github.com/InternLM/Tutorial) | 7:13 | [link](https://www.bilibili.com/video/BV18M4m1y7sm) |
| 1070 | LMDeploy 量化部署进阶实践 | - | AI 论文精读 | - | [github.com](https://github.com/InternLM/Tutorial/blob/camp3/docs/L2/LMDeploy/readme.md) [wjx.cn](https://www.wjx.cn/vm/PvefmG2.aspx?sojumpparm=openmmlabbz) [github.com](https://github.com/InternLM/Tutorial) | 89:57 | [link](https://www.bilibili.com/video/BV1df421q7cR) |
| 1071 | InternVL（冷笑话大师）部署微调实践 | - | AI 论文精读 | - | [github.com](https://github.com/InternLM/Tutorial/blob/camp3/docs/L2/InternVL/joke_readme.md) [wjx.cn](https://www.wjx.cn/vm/PvefmG2.aspx?sojumpparm=openmmlabbz) [github.com](https://github.com/InternLM/Tutorial) | 18:47 | [link](https://www.bilibili.com/video/BV1N6p1eXETX) |
| 1072 | 茴香豆：企业级知识库问答工具 | - | AI 论文精读 | - | [github.com](https://github.com/InternLM/Tutorial/tree/camp3/docs/L2/Huixiangdou) [wjx.cn](https://www.wjx.cn/vm/PvefmG2.aspx?sojumpparm=openmmlabbz) [github.com](https://github.com/InternLM/Tutorial) | 51:40 | [link](https://www.bilibili.com/video/BV1C5W2epEYP) |
| 1073 | 销冠——卖货主播大模型 | - | AI 论文精读 | - | [github.com](https://github.com/InternLM/Tutorial/tree/camp3/docs/EasterEgg/StreamerSales) | 23:46 | [link](https://www.bilibili.com/video/BV1f1421b7Du) |
| 1074 | InternLM-1.8B 模型安卓端侧部署实践 | - | AI 论文精读 | - | [github.com](https://github.com/InternLM/Tutorial/tree/camp3/docs/EasterEgg/Android) [wjx.cn](https://www.wjx.cn/vm/PvefmG2.aspx?sojumpparm=openmmlabbz) [github.com](https://github.com/InternLM/Tutorial) | 4:20 | [link](https://www.bilibili.com/video/BV1Ai421a7R6) |
| 1075 | 手把手带你使用 InternLM 实现谁是卧底游戏 | - | AI 论文精读 | - | [github.com](https://github.com/InternLM/Tutorial/tree/camp3/docs/EasterEgg/Game) [wjx.cn](https://www.wjx.cn/vm/PvefmG2.aspx?sojumpparm=openmmlabbz) [github.com](https://github.com/InternLM/Tutorial) | 16:39 | [link](https://www.bilibili.com/video/BV1uhp1efEeE) |
| 1076 | 旋转~跳跃~检测王者 MMDetection 的好兄弟来啦！ | - | AI 论文精读 | - | [github.com](https://github.com/open-mmlab/mmrotate) | 0:16 | [link](https://www.bilibili.com/video/BV1Hr4y1r73p) |
| 1077 | 墩墩生成器来啦！三步穿上墩墩服变身冰墩墩，做今年冬天最靓崽！ | - | AI 论文精读 | - | [github.com](https://github.com/open-mmlab/mmpose/tree/master/tools/webcam/configs) | 1:11 | [link](https://www.bilibili.com/video/BV1Tq4y1t77C) |
| 1078 | 千行百业智能化落地，MMDeploy 助你一“部”到位！ | - | AI 论文精读 | - | [github.com](https://github.com/open-mmlab/mmdeploy) | 1:14 | [link](https://www.bilibili.com/video/BV1g34y1z7EW) |
| 1079 | 操作顺滑，一秒上手，LabelBee 让人工标注更智能! | - | AI 论文精读 | - | - | 1:12 | [link](https://www.bilibili.com/video/BV1pr4y1X7VM) |
| 1080 | 画形亦画骨，知面也知心，与 MMHuman3D 一道探索人体参数化模型！ | - | AI 论文精读 | - | [github.com](https://github.com/open-mmlab/mmhuman3d) | 0:43 | [link](https://www.bilibili.com/video/BV1Ch411s7mS) |
| 1081 | MMFlow:帧与帧之间的追光者 | - | AI 论文精读 | - | [github.com](https://github.com/open-mmlab/mmflow！) | 0:44 | [link](https://www.bilibili.com/video/BV1Zr4y1r72H) |
| 1082 | 【MMTracking】单目标跟踪！持续跟踪！ | - | AI 论文精读 | - | [github.com](https://github.com/open-mmlab/mmtracking) | 0:29 | [link](https://www.bilibili.com/video/BV1Ev411376o) |
| 1083 | 【MMTracking】国庆快乐！多目标跟踪走丢也不怕！ | - | AI 论文精读 | - | [github.com](https://github.com/open-mmlab/mmtracking) [zhuanlan.zhihu.com](https://zhuanlan.zhihu.com/p/414625166) | 0:29 | [link](https://www.bilibili.com/video/BV1tU4y1c7mj) |
| 1084 | 【MMtracking】实时追踪！套马杆的汉子的马 | - | AI 论文精读 | - | [github.com](https://github.com/open-mmlab/mmtracking) [zhuanlan.zhihu.com](https://zhuanlan.zhihu.com/p/412817354) | 0:17 | [link](https://www.bilibili.com/video/BV1xL41147n5) |
| 1085 | 【MMDetection】七夕没对象？用我检测一下！ | - | AI 论文精读 | - | [github.com](https://github.com/open-mmlab/mmdetection) | 0:21 | [link](https://www.bilibili.com/video/BV1QU4y177oZ) |
| 1086 | 【MMPose】火柴人出击！ | - | AI 论文精读 | - | [github.com](https://github.com/open-mmlab/mmpose) | 0:29 | [link](https://www.bilibili.com/video/BV1YU4y1H7Dq) |
| 1087 | 【MMPose】 demo webcam | - | AI 论文精读 | - | [github.com](https://github.com/open-mmlab/mmpose) | 0:18 | [link](https://www.bilibili.com/video/BV1pw411R7iD) |
| 1088 | 【MMPose】3D Human Pose | - | AI 论文精读 | - | [github.com](https://github.com/open-mmlab/mmpose) | 0:21 | [link](https://www.bilibili.com/video/BV1B3411672x) |
| 1089 | 【MMPose】Animal Pose | - | AI 论文精读 | - | [github.com](https://github.com/open-mmlab/mmpose) | 0:17 | [link](https://www.bilibili.com/video/BV1t341167V7) |
| 1090 | 【MMPose】2D Human Pose | - | AI 论文精读 | - | [github.com](https://github.com/open-mmlab/mmpose) | 0:24 | [link](https://www.bilibili.com/video/BV1Zf4y157PF) |
| 1091 | AI 生成视频不闪了！社区大佬又整新活啦！ | - | AI 论文精读 | - | [github.com](https://github.com/open-mmlab/mmagic) | 0:11 | [link](https://www.bilibili.com/video/BV19o4y1b7RZ) |
| 1092 | Segment Anything Model+ MMagic = Generate Anything！ | - | AI 论文精读 | - | [github.com](https://github.com/open-mmlab/playground/tree/main/mmagic_sam) [github.com](https://github.com/open-mmlab/mmagic) | 0:11 | [link](https://www.bilibili.com/video/BV1ws4y1R7aB) |
| 1093 | DragGAN 应用来啦，无需部署，在线体验！ | - | AI 论文精读 | - | [github.com](https://github.com/XingangPan/DragGAN) [openxlab.org.cn](https://openxlab.org.cn/apps/detail/XingangPan/DragGAN) | 1:06 | [link](https://www.bilibili.com/video/BV1Rh4y1y7LK) |
| 1094 | 还在排队 SearchGPT？快来试试开源的 AI 搜索引擎框架 MindSearch！ | - | AI 论文精读 | - | [github.com](https://github.com/InternLM/mindsearch) | 1:55 | [link](https://www.bilibili.com/video/BV1Kx4y1s7SS) |
| 1095 | 人工智能时代的创业新范式 | - | AI 论文精读 | - | - | 44:13 | [link](https://www.bilibili.com/video/BV1gAmnBZEuK) |
| 1096 | 从初心到商业化：以快速迭代创造用户真价值 | - | AI 论文精读 | - | - | 23:23 | [link](https://www.bilibili.com/video/BV1hwmnBbE7d) |
| 1097 | 医疗领域大模型微调实践 | - | AI 论文精读 | - | [colearn.intern-ai.org.cn](https://colearn.intern-ai.org.cn/c6?s=bili) | 9:56 | [link](https://www.bilibili.com/video/BV1gfqJBNEmT) |
| 1098 | MMSelfSup 代码库介绍 | - | AI 论文精读 | - | [github.com](https://github.com/open-mmlab/mmselfsup) | 12:04 | [link](https://www.bilibili.com/video/BV1hg411r7iK) |
| 1099 | MMSelfSup 代码教程【1】模型自监督预训练 之 SimCLR | - | AI 论文精读 | - | [github.com](https://github.com/open-mmlab/mmselfsup) | 18:28 | [link](https://www.bilibili.com/video/BV1Ht4y1n7jy) |
| 1100 | MMSelfSup 代码教程【2】图片向量可视化 t-SNE | - | AI 论文精读 | - | [github.com](https://github.com/open-mmlab/mmselfsup) | 20:52 | [link](https://www.bilibili.com/video/BV1yS4y1W7B6) |
| 1101 | MMSelfSup 代码教程【3】自监督预训练模型的评估：“分类” 下游任务 之 线性评估 | - | AI 论文精读 | - | [github.com](https://github.com/open-mmlab/mmselfsup) | 13:22 | [link](https://www.bilibili.com/video/BV1LP41157uA) |
| 1102 | MMSelfSup 代码教程【4】自监督预训练模型的评估：“分类” 下游任务 之 SVM 评估 | - | AI 论文精读 | - | [github.com](https://github.com/open-mmlab/mmselfsup) | 18:17 | [link](https://www.bilibili.com/video/BV1Ga411G73i) |
| 1103 | MMSelfSup 代码教程【5】自监督预训练模型的评估：“检测”下游任务 | - | AI 论文精读 | - | [github.com](https://github.com/open-mmlab/mmselfsup) | 11:10 | [link](https://www.bilibili.com/video/BV1EP41157BL) |
| 1104 | MMSelfSup 代码教程【6】在 MMDetection 中使用自监督预训练模型 | - | AI 论文精读 | - | [github.com](https://github.com/open-mmlab/mmselfsup) | 10:20 | [link](https://www.bilibili.com/video/BV1Fe4y1Z7Wh) |
| 1105 | MMSelfSup 代码教程【7】模型自监督预训练 之 MAE | - | AI 论文精读 | - | [github.com](https://github.com/open-mmlab/mmselfsup) | 17:28 | [link](https://www.bilibili.com/video/BV1EY4y1u7Px) |
| 1106 | 10 分钟带你上手 MMEval（一）：MMEval 介绍 | - | AI 论文精读 | - | [github.com](https://github.com/open-mmlab/mmeval) | 6:34 | [link](https://www.bilibili.com/video/BV1m24y127Db) |
| 1107 | 10 分钟带你上手 MMEval（二）：MMEval 使用介绍 | - | AI 论文精读 | - | [github.com](https://github.com/open-mmlab/mmeval) | 8:41 | [link](https://www.bilibili.com/video/BV1HP4y117pA) |
| 1108 | 10 分钟带你上手 MMEval（三）：如何给 MMEval 添加新的评测指标 | - | AI 论文精读 | - | [github.com](https://github.com/open-mmlab/mmeval) | 10:12 | [link](https://www.bilibili.com/video/BV1Ev4y1d7nK) |
| 1109 | 大语言模型复杂医疗推理评测基准MedAgentsBench | - | AI 论文精读 | - | [hub.opencompass.org.cn](https://hub.opencompass.org.cn/dataset-detail/MedAgents-Bench) | 34:53 | [link](https://www.bilibili.com/video/BV1J5oXYYEYH) |
| 1110 | 通用写作评测基准 WritingBench | - | AI 论文精读 | - | [hub.opencompass.org.cn](https://hub.opencompass.org.cn/dataset-detail/WritingBench) | 34:39 | [link](https://www.bilibili.com/video/BV1dFdpYqELh) |
| 1111 | 首个视频时空推理评估基准 V-STaR | - | AI 论文精读 | - | [hub.opencompass.org.cn](https://hub.opencompass.org.cn/dataset-detail/V-STaR) | 38:35 | [link](https://www.bilibili.com/video/BV1DbdHYZEbq) |
| 1112 | ViLBench：多模态过程奖励（Process Reward）建模组件 | - | AI 论文精读 | - | [hub.opencompass.org.cn](https://hub.opencompass.org.cn/dataset-detail/ViLBench) | 45:00 | [link](https://www.bilibili.com/video/BV1cZ5kzyECC) |
| 1113 | CMU团队打造考公逻辑谜题 VisualPuzzles | - | AI 论文精读 | - | [hub.opencompass.org.cn](https://hub.opencompass.org.cn/dataset-detail/VisualPuzzles) | 41:03 | [link](https://www.bilibili.com/video/BV16kL7zrEdq) |
| 1114 | ToolHop：查询驱动的多跳工具使用评测集 | - | AI 论文精读 | - | [hub.opencompass.org.cn](https://hub.opencompass.org.cn/dataset-detail/ToolHop) | 46:43 | [link](https://www.bilibili.com/video/BV1CjExzGE7s) |
| 1115 | 1. MMDetection3D 介绍及安装配置 | - | AI 论文精读 | - | - | 5:37 | [link](https://www.bilibili.com/video/BV1aG4y197is) |
| 1116 | 2. 使用 MMDet3D 预训练模型在点云和数据图像上推理 | - | AI 论文精读 | - | - | 15:49 | [link](https://www.bilibili.com/video/BV1E44y1Q7qi) |
| 1117 | 3. KITTI 数据集介绍及 MMDet3D 坐标系规范 | - | AI 论文精读 | - | - | 26:19 | [link](https://www.bilibili.com/video/BV1vv4y1d7br) |
| 1118 | 4. 使用 MMDetection3D 训练 | - | AI 论文精读 | - | - | 15:06 | [link](https://www.bilibili.com/video/BV11G4y157ux) |
| 1119 | 5. PointPillars 和 KittiDataset 的配置文件解读 | - | AI 论文精读 | - | - | 16:02 | [link](https://www.bilibili.com/video/BV14M41167Ct) |
| 1120 | 6. PointPillars 和 KittiDataset 的代码解读 | - | AI 论文精读 | - | - | 32:37 | [link](https://www.bilibili.com/video/BV1Xe4y1g7Xv) |
| 1121 | 大语言模型原理与书生大模型提示词工程实践 | - | AI 论文精读 | - | [aicarrier.feishu.cn](https://aicarrier.feishu.cn/wiki/SEfTwYCgAiDEkskx7yocvzuhnph) [aicarrier.feishu.cn](https://aicarrier.feishu.cn/wiki/DK9Wwf1DRiidwgk1FPDcvj6Bnxq) [colearn.intern-ai.org.cn](https://colearn.intern-ai.org.cn/set?s=bz) | 39:46 | [link](https://www.bilibili.com/video/BV1vUjYz2Eys) |
| 1122 | 玩转书生大模型 API 之 Browse Use实践 | - | AI 论文精读 | - | [aicarrier.feishu.cn](https://aicarrier.feishu.cn/wiki/XhoNw2qzPir8qmkVNYyc5YAunrc) [colearn.intern-ai.org.cn](https://colearn.intern-ai.org.cn/set?s=bz) | 1:29 | [link](https://www.bilibili.com/video/BV1SPGnzWEN4) |
| 1123 | InternLM 微调论文分类实践 | - | AI 论文精读 | - | [aicarrier.feishu.cn](https://aicarrier.feishu.cn/wiki/QdhEwaIINietCak3Y1dcdbLJn3e) [colearn.intern-ai.org.cn](https://colearn.intern-ai.org.cn/set?s=bz) | 15:10 | [link](https://www.bilibili.com/video/BV1DyGuz4Ewp) |
| 1124 | GraphGen 训练数据合成框架 | - | AI 论文精读 | - | [colearn.intern-ai.org.cn](https://colearn.intern-ai.org.cn/set) | 4:49 | [link](https://www.bilibili.com/video/BV1EA31zMEQk) |
| 1125 | CAMEL 书生多智能体系统实践 | - | AI 论文精读 | - | - | 41:23 | [link](https://www.bilibili.com/video/BV15A3EzWEPv) |
| 1126 | 国产开源、免费的 AI 图像与视频创作平台MagicMaker，新手教程来啦！ | - | AI 论文精读 | - | [magicmaker.openxlab.org.cn](https://magicmaker.openxlab.org.cn/) | 2:05 | [link](https://www.bilibili.com/video/BV1w2421A7YP) |
| 1127 | “龙在城隍庙吃小笼包”MagicMaker亮相东方卫视春晚特别直播节目，科技魔法点亮传统舞台 | - | AI 论文精读 | - | [magicmaker.openxlab.org.cn](https://magicmaker.openxlab.org.cn/home) | 0:45 | [link](https://www.bilibili.com/video/BV1TS421A7UR) |
| 1128 | “一个小男生和一个小女生在黄河路‘偷心’”MagicMaker亮相东方卫视春晚特别直播节目，科技魔法点亮传统舞台 | - | AI 论文精读 | - | [magicmaker.openxlab.org.cn](https://magicmaker.openxlab.org.cn/home) | 1:36 | [link](https://www.bilibili.com/video/BV18z421X7ci) |
| 1129 | “龙在东方明珠上盘旋”MagicMaker亮相东方卫视春晚特别直播节目，科技魔法点亮传统舞台 | - | AI 论文精读 | - | [magicmaker.openxlab.org.cn](https://magicmaker.openxlab.org.cn/home) | 1:17 | [link](https://www.bilibili.com/video/BV1VC411s7Fv) |
| 1130 | 社区开放麦#1｜基于关键点的动作识别 | - | AI 论文精读 | - | - | 46:41 | [link](https://www.bilibili.com/video/BV1Yu411k7Be) |
| 1131 | 社区开放麦#2｜CVPR前沿姿态估计论文精讲 | - | AI 论文精读 | - | - | 60:13 | [link](https://www.bilibili.com/video/BV1dS4y187sj) |
| 1132 | 社区开放麦#3｜PyTorch 分布式训练解读 | - | AI 论文精读 | - | - | 66:51 | [link](https://www.bilibili.com/video/BV1Jv4y1K7fv) |
| 1133 | 社区开放麦#4｜手把手带你复现最新自监督算法 | - | AI 论文精读 | - | - | 61:09 | [link](https://www.bilibili.com/video/BV1xt4y1x7sp) |
| 1134 | 社区开放麦#5｜带你探寻可见光之外的世界 | - | AI 论文精读 | - | - | 36:01 | [link](https://www.bilibili.com/video/BV1Ka411n7nP) |
| 1135 | 社区开放麦#6｜带你了解车速估计技术在自动驾驶领域的应用 | - | AI 论文精读 | - | - | 50:40 | [link](https://www.bilibili.com/video/BV1sY4y1L7Au) |
| 1136 | 社区开放麦#7  MMPose 姿态估计创意 demo 大赛 | - | AI 论文精读 | - | - | 59:49 | [link](https://www.bilibili.com/video/BV1J34y1j7AP) |
| 1137 | 社区开放麦#8 / 迈向真实世界的感知：3D 目标检测 | - | AI 论文精读 | - | - | 69:23 | [link](https://www.bilibili.com/video/BV1hg41197HX) |
| 1138 | 社区开放麦#9 / OpenMMLab 模块化设计背后的功臣 | - | AI 论文精读 | - | - | 59:46 | [link](https://www.bilibili.com/video/BV19Z4y1q7Q5) |
| 1139 | 社区开放麦#10 / MMDeploy ncnn 部署实战 | - | AI 论文精读 | - | - | 47:44 | [link](https://www.bilibili.com/video/BV1gS4y1p7gm) |
| 1140 | 社区开放麦#11 / BEV感知：下一代自动驾驶感知算法新范式 | - | AI 论文精读 | - | - | 57:01 | [link](https://www.bilibili.com/video/BV12t4y1t7Lq) |
| 1141 | 社区开放麦#12 / 视觉有向目标的高精度检测 | - | AI 论文精读 | - | - | 63:46 | [link](https://www.bilibili.com/video/BV1Wr4y1E7Qr) |
| 1142 | 社区开放麦#13 / 手势识别算法综述与正确打开方式 | - | AI 论文精读 | - | - | 57:48 | [link](https://www.bilibili.com/video/BV1ar4y1j7aN) |
| 1143 | 社区开放麦#14 / 从时间序列角度破解姿态估计中的两大问题 | - | AI 论文精读 | - | - | 94:16 | [link](https://www.bilibili.com/video/BV1aB4y1k7Ph) |
| 1144 | 社区开放麦#15/  突破纯视觉 3D 检测深度估计瓶颈 | - | AI 论文精读 | - | - | 59:31 | [link](https://www.bilibili.com/video/BV1dg41117ba) |
| 1145 | 社区开放麦#16 / 稀疏卷积的高性能部署 | - | AI 论文精读 | - | - | 58:07 | [link](https://www.bilibili.com/video/BV1gV4y177F6) |
| 1146 | 社区开放麦#17 / 像素级别的多目标跟踪方案 | - | AI 论文精读 | - | - | 32:41 | [link](https://www.bilibili.com/video/BV1814y1b7Za) |
| 1147 | 社区开放麦#18 / 半监督学习在 3D 目标检测的最新进展 | - | AI 论文精读 | - | - | 45:01 | [link](https://www.bilibili.com/video/BV1mT411c7kB) |
| 1148 | 社区开放麦#19 / 对 AI 炼丹师友好的模型部署探索 | - | AI 论文精读 | - | - | 84:31 | [link](https://www.bilibili.com/video/BV12V4y1H7XQ) |
| 1149 | 社区开放麦#20 / 简单有效的目标跟踪方案 | - | AI 论文精读 | - | - | 50:46 | [link](https://www.bilibili.com/video/BV1wd4y1X7j5) |
| 1150 | 社区开放麦#21 / 当钩子编程遇到深度学习：Runner & Hook | - | AI 论文精读 | - | - | 59:58 | [link](https://www.bilibili.com/video/BV1pe4y1C7n1) |
| 1151 | 社区开放麦#22 /  姿态估计领域的前沿进展 | - | AI 论文精读 | - | - | 77:13 | [link](https://www.bilibili.com/video/BV1HV4y1M7dG) |
| 1152 | 社区开放麦#23 / MMYOLO 圆桌会 | - | AI 论文精读 | - | - | 51:38 | [link](https://www.bilibili.com/video/BV1r24y1R7D1) |
| 1153 | 社区开放麦#24 / 释放数据潜力，打造 AI 加速引擎 | - | AI 论文精读 | - | - | 53:51 | [link](https://www.bilibili.com/video/BV1p8411s7W6) |
| 1154 | AI奇妙夜第一期 | - | AI 论文精读 | - | - | 76:09 | [link](https://www.bilibili.com/video/BV1P8411e7Cb) |
| 1155 | 社区开放麦#27 / 部署神器Halide, 实现高性能算法 | - | AI 论文精读 | - | - | 46:06 | [link](https://www.bilibili.com/video/BV1Tg411B7ch) |
| 1156 | AI 奇妙夜#2 / 子豪兄分享人工智能学习心法 | - | AI 论文精读 | - | - | 82:07 | [link](https://www.bilibili.com/video/BV1WG4y1f7yX) |
| 1157 | 社区开放麦#29 / ECCV Oral / 用于场景文本检测识别的弱监督视觉语言预训练方法 | - | AI 论文精读 | - | - | 53:31 | [link](https://www.bilibili.com/video/BV16G4y1x7es) |
| 1158 | 社区开放麦#30 / 入门剪枝利器 MMRazor，迈出模型压缩第一步 | - | AI 论文精读 | - | - | 53:24 | [link](https://www.bilibili.com/video/BV1wG411u7SP) |
| 1159 | 社区开放麦#31 / 异构检测器间知识蒸馏算法 PKD / NeurIPS22 | - | AI 论文精读 | - | - | 55:56 | [link](https://www.bilibili.com/video/BV1z24y1k7iu) |
| 1160 | 社区开放麦#32 / ONNX 新特性和最佳实践介绍 | - | AI 论文精读 | - | - | 66:28 | [link](https://www.bilibili.com/video/BV1LG411K7ah) |
| 1161 | 社区开放麦#33 / 详解 ACCV22 大规模细粒度图像分类夺冠方案 | - | AI 论文精读 | - | [github.com](https://github.com/open-mmlab/mmselfsup/tree/dev-1.x/projects/fgia_accv2022_1st) [github.com](https://github.com/open-mmlab/mmclassification/tree/dev-1.x/projects/fgia_accv2022_1st) | 36:03 | [link](https://www.bilibili.com/video/BV13M411S7b5) |
| 1162 | 社区开放麦#34 / 突破 AI 推理性能瓶颈，神经网络量化的方法与实践 | - | AI 论文精读 | - | - | 64:09 | [link](https://www.bilibili.com/video/BV128411n7yN) |
| 1163 | AI 奇妙夜#3 / 大规模多模态预训练最新研究进展 | - | AI 论文精读 | - | - | 53:10 | [link](https://www.bilibili.com/video/BV1J14y1A7SE) |
| 1164 | 社区开放麦#36 多模态场景下的高性能 Embedding 计算服务 | - | AI 论文精读 | - | - | 52:10 | [link](https://www.bilibili.com/video/BV1ET411m7gu) |
| 1165 | 社区开放麦#37 / 牛津大学vgg组博士：提高遮挡检测下的目标检测效果 | - | AI 论文精读 | - | - | 55:18 | [link](https://www.bilibili.com/video/BV1NA41167kN) |
| 1166 | 社区开放麦#38 目标检测新范式！DETR 系列算法解读 | - | AI 论文精读 | - | - | 123:27 | [link](https://www.bilibili.com/video/BV17x4y1w7ZK) |
| 1167 | 弱监督有向目标检测 / 杨学 | - | AI 论文精读 | - | - | 64:14 | [link](https://www.bilibili.com/video/BV1GD4y1g7s8) |
| 1168 | 社区开放麦#41 / 视觉大模型设计新范式 | - | AI 论文精读 | - | - | 66:15 | [link](https://www.bilibili.com/video/BV1zs4y15754) |
| 1169 | AI 奇妙夜#4 / 文字识别：从数据趋动到模型自监督 | - | AI 论文精读 | - | [github.com](https://github.com/open-mmlab/mmocr) | 66:35 | [link](https://www.bilibili.com/video/BV1Zb41197V4) |
| 1170 | 社区开放麦#42 / 面向自动驾驶场景的纯视觉三维语义占有预测 | - | AI 论文精读 | - | - | 70:13 | [link](https://www.bilibili.com/video/BV1P54y1T7vS) |
| 1171 | 社区开放麦#43 / 高精度实例分割 PatchDCT | - | AI 论文精读 | - | - | 22:03 | [link](https://www.bilibili.com/video/BV1Sx4y1w7JK) |
| 1172 | AI奇妙夜#5 / “视觉与语言”跨模态智能及应用 | - | AI 论文精读 | - | - | 60:59 | [link](https://www.bilibili.com/video/BV1Y84y1g7nP) |
| 1173 | CVPR 2023 有向目标检测角度预测新方法 — 相移编码 / 社区开放麦#45 | - | AI 论文精读 | - | - | 41:41 | [link](https://www.bilibili.com/video/BV1Cv4y1n72h) |
| 1174 | 业界可用的高性能的姿态估计模型能有多快？ / 社区开放麦#46 | - | AI 论文精读 | - | - | 87:37 | [link](https://www.bilibili.com/video/BV1Wc411p7HT) |
| 1175 | CVPR2023 首个大规模全场景人体数据集 Human-Art / 社区开放麦#47 | - | AI 论文精读 | - | - | 59:00 | [link](https://www.bilibili.com/video/BV1Hs4y1d7bJ) |
| 1176 | MOSS：如何打造对话式语言模型 / 社区开放麦#48 | - | AI 论文精读 | - | - | 65:19 | [link](https://www.bilibili.com/video/BV1fa4y1V7xG) |
| 1177 | 超大规模视觉通用感知模型-代季峰教授 / AI奇妙夜#6 | - | AI 论文精读 | - | - | 50:12 | [link](https://www.bilibili.com/video/BV1dM411g7Jn) |
| 1178 | 视频理解基础模型及下游应用-王利民教授 / AI奇妙夜#7 | - | AI 论文精读 | - | - | 60:43 | [link](https://www.bilibili.com/video/BV1rz4y1t7b7) |
| 1179 | ICLR Spotlight / 在卷积网络上做BERT式预训练 | - | AI 论文精读 | - | - | 56:44 | [link](https://www.bilibili.com/video/BV11s4y1M7qL) |
| 1180 | HumanBench：迈向以人为中心的通才模型 | - | AI 论文精读 | - | - | 45:54 | [link](https://www.bilibili.com/video/BV1Q24y1N72o) |
| 1181 | 低成本微调垂直领域专属 ChatGPT | - | AI 论文精读 | - | - | 67:12 | [link](https://www.bilibili.com/video/BV1Pz4y1q7yA) |
| 1182 | 自动驾驶场景中的半监督点云分割 | - | AI 论文精读 | - | - | 63:23 | [link](https://www.bilibili.com/video/BV11u4y1d7S2) |
| 1183 | 基于 Visual Transformer 的分割模型综述 | - | AI 论文精读 | - | - | 62:06 | [link](https://www.bilibili.com/video/BV1tc411M7DC) |
| 1184 | AI 2.0：突破性技术推动智能制造的应用创新 | - | AI 论文精读 | - | - | 55:11 | [link](https://www.bilibili.com/video/BV1ch4y1M7Re) |
| 1185 | 基于 SAM 大模型的实例分割研究 —— RSPrompter | - | AI 论文精读 | - | - | 52:55 | [link](https://www.bilibili.com/video/BV1J94y1i7bB) |
| 1186 | 开放检测视觉场景理解 / 社区开放麦 | - | AI 论文精读 | - | - | 67:01 | [link](https://www.bilibili.com/video/BV1u14y1R7mn) |
| 1187 | 运用 SAM 模型分割任意点云 | - | AI 论文精读 | - | - | 76:19 | [link](https://www.bilibili.com/video/BV1gm4y1j7M2) |
| 1188 | MMBench：基于ChatGPT的全方位多模能力评测体系 | - | AI 论文精读 | - | [opencompass.org.cn](https://opencompass.org.cn/MMBench) [opencompass.org.cn](https://opencompass.org.cn/omni-rank) | 42:30 | [link](https://www.bilibili.com/video/BV16z4y1x7qG) |
| 1189 | 迈向更强的端到端多人姿态估计 | - | AI 论文精读 | - | - | 65:30 | [link](https://www.bilibili.com/video/BV1fj41197R9) |
| 1190 | SAM 时代，图像/视频分割将何去何从？ | - | AI 论文精读 | - | [openxlab.org.cn](https://openxlab.org.cn/apps/detail/keleiwhu/sam-hq) | 67:34 | [link](https://www.bilibili.com/video/BV1ZP41147xQ) |
| 1191 | MFF：简单高效的多级特征融合自监督方法 / ICCV 2023 | - | AI 论文精读 | - | [github.com](https://github.com/open-mmlab/mmpretrain/tree/dev) [readpaper.com](https://readpaper.com/paper/4784261971549618177?channel=OpenMMlab) | 39:03 | [link](https://www.bilibili.com/video/BV1q94y1z7Xe) |
| 1192 | 更好的人体姿态，更好的生成图像 | - | AI 论文精读 | [2307.15880](https://arxiv.org/abs/2307.15880) | [yzd-v.github.io](https://yzd-v.github.io/page/) [github.com](https://github.com/IDEA-Research/DWPose) [openxlab.org.cn](https://openxlab.org.cn/apps/detail/mmpose/RTMPose) | 33:05 | [link](https://www.bilibili.com/video/BV1rw411Q7t6) |
| 1193 | 基于大规模多模态扩散模型的文本到视频生成 | - | AI 论文精读 | [2212.09478](https://arxiv.org/abs/2212.09478) | [github.com](https://github.com/researchmm/MM-Diffusion) [github.com](https://github.com/daooshee/HD-VG-130M) | 70:46 | [link](https://www.bilibili.com/video/BV1BP411h7oQ) |
| 1194 | 多模态任务终结者：Meta-Transformer | - | AI 论文精读 | - | [readpaper.com](https://readpaper.com/paper/1880723763752826112?channel=OpenMMLab) | 59:30 | [link](https://www.bilibili.com/video/BV1Bu4y1y714) |
| 1195 | 迈向更强的开集目标检测-From Detection to Grounding | - | AI 论文精读 | - | [readpaper.com](https://readpaper.com/paper/4731752776334327809?channel=OpenMMlab) | 57:19 | [link](https://www.bilibili.com/video/BV1Mk4y1F7cp) |
| 1196 | 如何基于大模型构建智能体？多机构百页综述从交互角度详解 AI Agent！ | - | AI 论文精读 | - | - | 70:51 | [link](https://www.bilibili.com/video/BV1884y1U7CR) |
| 1197 | 你的3D感知模型够鲁棒吗？Robo3D告诉你答案！ | - | AI 论文精读 | [2303.17597](https://arxiv.org/abs/2303.17597) | - | 69:08 | [link](https://www.bilibili.com/video/BV1nu411u7W6) |
| 1198 | 如何高效微调大模型？技术原理与最佳实践揭秘！ | - | AI 论文精读 | - | [github.com](https://github.com/liguodongiot/llm-action/tree/main/train/peft) | 86:20 | [link](https://www.bilibili.com/video/BV1qw411c7Hd) |
| 1199 | 大模型时代通用检测趋势解读及MMDetection未来展望 | - | AI 论文精读 | - | - | 82:24 | [link](https://www.bilibili.com/video/BV1o94y1L7fg) |
| 1200 | CVPR23 / 3D Occupancy 预测冠军方案：FB-OCC | - | AI 论文精读 | - | - | 52:45 | [link](https://www.bilibili.com/video/BV1PX4y1e7zz) |
| 1201 | 多模态 Agents：用大模型语言模型串联多模态专家 | - | AI 论文精读 | - | - | 39:48 | [link](https://www.bilibili.com/video/BV1mM411X7Zn) |
| 1202 | 探索未知：LLM Agent 应用开发的全新时代 | - | AI 论文精读 | - | [zhuanlan.zhihu.com](https://zhuanlan.zhihu.com/p/622947810) [zhuanlan.zhihu.com](https://zhuanlan.zhihu.com/p/629589593) [zhuanlan.zhihu.com](https://zhuanlan.zhihu.com/p/633033220) | 67:39 | [link](https://www.bilibili.com/video/BV1W84y197qq) |
| 1203 | AI时代数据应用的全链路工厂- Chat2DB | - | AI 论文精读 | - | [sqlgpt.cn](https://sqlgpt.cn/zh) [github.com](https://github.com/chat2db/Chat2DB/) | 35:53 | [link](https://www.bilibili.com/video/BV1re411m7p3) |
| 1204 | 语音与音频生成 Amphion揭秘霉霉如何演唱《稻香》 | - | AI 论文精读 | [2312.09911](https://arxiv.org/abs/2312.09911) | [github.com](https://github.com/open-mmlab/Amphion) | 59:55 | [link](https://www.bilibili.com/video/BV1AV411R7SS) |
| 1205 | RTMPose 家族史诗级更新！多人、全身一网打尽 | - | AI 论文精读 | [2312.07526](https://arxiv.org/abs/2312.07526) | [github.com](https://github.com/open-mmlab/mmpose/tree/main/projects/rtmo) | 80:21 | [link](https://www.bilibili.com/video/BV1P5411v7tz) |
| 1206 | 清华提出首个面向无监督和半监督新意图发现的文本聚类框架USNID | - | AI 论文精读 | [2304.07699](https://arxiv.org/abs/2304.07699) | [ieeexplore.ieee.org](https://ieeexplore.ieee.org/document/10349963) [github.com](https://github.com/thuiar/TEXTOIR) | 69:12 | [link](https://www.bilibili.com/video/BV1464y1w73f) |
| 1207 | Beyond Segmentation Anything，超越SAM | - | AI 论文精读 | [2312.06660](https://arxiv.org/abs/2312.06660) | [github.com](https://github.com/chongzhou96/EdgeSAM) [huggingface.co](https://huggingface.co/spaces/chongzhou/EdgeSAM) [github.com](https://github.com/HarborYuan/ovsam) | 68:50 | [link](https://www.bilibili.com/video/BV1xC411r7qq) |
| 1208 | Sora 夜谈之 Video Diffusion 综述 | - | AI 论文精读 | - | [github.com](https://github.com/ChenHsing/Awesome-Video-Diffusion-Models) | 90:09 | [link](https://www.bilibili.com/video/BV1cJ4m1e7sQ) |
| 1209 | 新一代换脸神器 InstantID：高保真人像秒级生成 | - | AI 论文精读 | [2401.07519](https://arxiv.org/abs/2401.07519) | [github.com](https://github.com/InstantID/InstantID) [instantid.github.io](https://instantid.github.io/) [openxlab.org.cn](https://openxlab.org.cn/apps/detail/InstantX/InstantID) | 76:56 | [link](https://www.bilibili.com/video/BV1HH4y177T5) |
| 1210 | CVPR 2024 - 具身智能中的多模态三维感知思考 | - | AI 论文精读 | [2312.16170](https://arxiv.org/abs/2312.16170) | [tai-wang.github.io](http://tai-wang.github.io/embodiedscan) [github.com](https://github.com/OpenRobotLab/EmbodiedScan) [opendrivelab.com](https://opendrivelab.com/challenge2024/#multiview_3d_visual_grounding) | 51:26 | [link](https://www.bilibili.com/video/BV1nt421V7UY) |
| 1211 | PK 周杰伦，全能音乐创作大模型 SongComposer 作词作曲令人惊叹 | - | AI 论文精读 | [2402.17645](https://arxiv.org/abs/2402.17645) | [pjlab-songcomposer.github.io](https://pjlab-songcomposer.github.io/) | 66:09 | [link](https://www.bilibili.com/video/BV1bw4m1d7dK) |
| 1212 | Stable Diffusion 3 论文技术解析，架构细节大揭秘！ | - | AI 论文精读 | - | [stabilityai-public-packages.s3.us-west-2.amazonaws.com](https://stabilityai-public-packages.s3.us-west-2.amazonaws.com/Stable+Diffusion+3+Paper.pdf) | 58:15 | [link](https://www.bilibili.com/video/BV1Ni421d7ud) |
| 1213 | 无需训练的 Stable Diffusion 视频编辑方法 | - | AI 论文精读 | [2306.07954](https://arxiv.org/abs/2306.07954) | [github.com](https://github.com/williamyang1991/Rerender_A_Video) | 56:49 | [link](https://www.bilibili.com/video/BV12w4m1R75t) |
| 1214 | Latte 专场: 深度解读视频生成与训练技术 | - | AI 论文精读 | - | [github.com](https://github.com/Vchitect) [wyhsirius.github.io](https://wyhsirius.github.io/) [github.com](https://github.com/InternLM/xtuner) | 120:08 | [link](https://www.bilibili.com/video/BV14F4m1K7Wz) |
| 1215 | 微软研究院谭旭带来零样本 TTS 模型 NaturalSpeech 3 | - | AI 论文精读 | - | [speechresearch.github.io](https://speechresearch.github.io/naturalspeech3/) [huggingface.co](https://huggingface.co/spaces/amphion/naturalspeech3_facodec) | 62:41 | [link](https://www.bilibili.com/video/BV1tm421s7B6) |
| 1216 | 零样本语音生成大模型与Amphion实践 | - | AI 论文精读 | [2312.09911](https://arxiv.org/abs/2312.09911) | [github.com](https://github.com/open-mmlab/Amphion) | 67:19 | [link](https://www.bilibili.com/video/BV18C41177JA) |
| 1217 | 多模态大模型的技术实践与思考 | - | AI 论文精读 | - | - | 65:53 | [link](https://www.bilibili.com/video/BV17n4y1d7wp) |
| 1218 | 当大模型遇上心理咨询：基于心理咨询报告的对话重构和评测框架CPsyCoun | - | AI 论文精读 | - | - | 54:02 | [link](https://www.bilibili.com/video/BV1vJ4m1g7G4) |
| 1219 | ACL 24 论文分享（东北大学信息检索小组场） | - | AI 论文精读 | - | - | 73:27 | [link](https://www.bilibili.com/video/BV144421Q7ir) |
| 1220 | SD-Eval新基准，让语音交互大模型情智兼备 | - | AI 论文精读 | - | - | 47:56 | [link](https://www.bilibili.com/video/BV16E421A7wU) |
| 1221 | 魔搭社区-浦语模型和工具实战 | - | AI 论文精读 | - | [modelscope.cn](https://www.modelscope.cn/studios/Shanghai_AI_Laboratory/MindSearch) [modelscope.cn](https://modelscope.cn/studios/opencompass/CompassArena) | 70:26 | [link](https://www.bilibili.com/video/BV1zy411i7yp) |
| 1222 | 开源工具MinerU助力复杂PDF高效解析提取 | - | AI 论文精读 | - | - | 67:06 | [link](https://www.bilibili.com/video/BV15rHSeyEk2) |
| 1223 | MindSearch：AI 时代的“思考型”智能搜索引擎 | - | AI 论文精读 | - | - | 58:35 | [link](https://www.bilibili.com/video/BV1UHy3YYEHz) |
| 1224 | MaskGCT：基于掩码生成模型的大规模零样本 TTS 模型 | - | AI 论文精读 | - | - | 82:28 | [link](https://www.bilibili.com/video/BV1LJD1YsEd4) |
| 1225 | 玩转 MMYOLO 之工具篇（一）：特征图可视化 | - | AI 论文精读 | - | [github.com](https://github.com/open-mmlab/mmyolo) [github.com](https://github.com/open-mmlab/mmyolo/issues/136) | 17:48 | [link](https://www.bilibili.com/video/BV188411s7o8) |
| 1226 | 玩转 MMYOLO 之基础篇（一）：配置文件全解读 | - | AI 论文精读 | - | [github.com](https://github.com/open-mmlab/mmyolo) [github.com](https://github.com/open-mmlab/mmyolo/issues/136) [github.com](https://github.com/open-mmlab/OpenMMLabCourse) | 18:33 | [link](https://www.bilibili.com/video/BV1214y157ck) |
| 1227 | 【MMYOLO】超酷炫 RTMDet 特征图可视化 demo | - | AI 论文精读 | - | - | 0:33 | [link](https://www.bilibili.com/video/BV1je4y1478R) |
| 1228 | 玩转 MMYOLO 之实用篇（一）: 源码阅读和调试「必备」技巧 | - | AI 论文精读 | - | [github.com](https://github.com/open-mmlab/mmyolo) [github.com](https://github.com/open-mmlab/mmyolo/issues/136) [github.com](https://github.com/open-mmlab/OpenMMLabCourse) | 43:02 | [link](https://www.bilibili.com/video/BV1N14y1V7mB) |
| 1229 | MMYOLO 社区贡献者经验分享会 | - | AI 论文精读 | - | [github.com](https://github.com/open-mmlab/mmyolo) [github.com](https://github.com/open-mmlab/mmyolo/issues/136) [github.com](https://github.com/open-mmlab/OpenMMLabCourse) | 82:05 | [link](https://www.bilibili.com/video/BV12d4y1r7Nd) |
| 1230 | 玩转 MMYOLO 之基础篇（二）： 工程文件结构简析 | - | AI 论文精读 | - | [github.com](https://github.com/open-mmlab/mmyolo) [github.com](https://github.com/open-mmlab/mmyolo/issues/136) [github.com](https://github.com/open-mmlab/OpenMMLabCourse) | 12:06 | [link](https://www.bilibili.com/video/BV1LP4y117jS) |
| 1231 | 玩转 MMYOLO 之实用篇（二）: 10分钟带你换遍主干网络 | - | AI 论文精读 | - | [github.com](https://github.com/open-mmlab/mmyolo) [github.com](https://github.com/open-mmlab/mmyolo/issues/136) [github.com](https://github.com/open-mmlab/OpenMMLabCourse) | 9:07 | [link](https://www.bilibili.com/video/BV1JG4y1d7GC) |
| 1232 | 玩转 MMYOLO 之工具篇（二）：十分钟轻松掌握大图推理 | - | AI 论文精读 | - | [github.com](https://github.com/open-mmlab/mmyolo) [github.com](https://github.com/open-mmlab/mmyolo/issues/136) [github.com](https://github.com/open-mmlab/OpenMMLabCourse) | 11:34 | [link](https://www.bilibili.com/video/BV1EK411R7Ws) |
| 1233 | 玩转 MMYOLO 之实用篇（三）：自定义数据集从标注到部署保姆级教程 | - | AI 论文精读 | - | [github.com](https://github.com/open-mmlab/mmyolo) [github.com](https://github.com/open-mmlab/mmyolo/issues/136) [github.com](https://github.com/open-mmlab/OpenMMLabCourse) | 49:30 | [link](https://www.bilibili.com/video/BV1RG4y137i5) |
| 1234 | 玩转 MMYOLO 之实用篇（四）：顶会第一步 · 模块自定义 | - | AI 论文精读 | - | [github.com](https://github.com/open-mmlab/mmyolo) [github.com](https://github.com/open-mmlab/mmyolo/issues/136) [github.com](https://github.com/open-mmlab/OpenMMLabCourse) | 8:15 | [link](https://www.bilibili.com/video/BV1yd4y1j7VD) |
| 1235 | 玩转 MMYOLO 之实用篇（五）：训练和测试技巧合集 | - | AI 论文精读 | - | [github.com](https://github.com/open-mmlab/mmyolo) [github.com](https://github.com/open-mmlab/mmyolo/issues/136) [github.com](https://github.com/open-mmlab/OpenMMLabCourse) | 24:29 | [link](https://www.bilibili.com/video/BV1GM4y1U77z) |
| 1236 | 清华大学导师亲授！3D目标检测超硬核课程新鲜出炉~ | - | AI 论文精读 | - | - | 100:24 | [link](https://www.bilibili.com/video/BV1Sc411K7L1) |
| 1237 | 人体关键点检测与MMPose | - | AI 论文精读 | - | - | 50:23 | [link](https://www.bilibili.com/video/BV1kk4y1L7Xb) |
| 1238 | 1. PyTorch 模型部署基础知识 | - | AI 论文精读 | - | - | 41:49 | [link](https://www.bilibili.com/video/BV1Tx4y1F768) |
| 1239 | 2. 安装配置 MMDeploy 环境 | - | AI 论文精读 | - | - | 10:03 | [link](https://www.bilibili.com/video/BV1yX4y1X7jp) |
| 1240 | 3. 部署 MMClassification 图像分类模型 | - | AI 论文精读 | - | - | 5:45 | [link](https://www.bilibili.com/video/BV1V84y1J7MT) |
| 1241 | 4. 部署 MMDetection 目标检测模型 | - | AI 论文精读 | - | - | 2:55 | [link](https://www.bilibili.com/video/BV11R4y1v7L2) |
| 1242 | 自监督学习与 MMSelfSup | - | AI 论文精读 | - | - | 66:02 | [link](https://www.bilibili.com/video/BV1iu4y1e7tV) |
| 1243 | Linux 前置基础（基本命令、SSH及端口映射） | - | AI 论文精读 | - | [github.com](https://github.com/InternLM/Tutorial/tree/camp4/docs/L0/linux) [github.com](https://github.com/InternLM/Tutorial/tree/camp4/docs/L0/linux/task.md) [colearn.intern-ai.org.cn](https://colearn.intern-ai.org.cn/set?s=bz4) | 15:01 | [link](https://www.bilibili.com/video/BV13U1VYmEUr) |
| 1244 | Python 前置基础（熟悉断点调试、依赖指定路径安装） | - | AI 论文精读 | - | [github.com](https://github.com/InternLM/Tutorial/blob/camp4/docs/L0/Python) [github.com](https://github.com/InternLM/Tutorial/blob/camp4/docs/L0/Python/task.md) [colearn.intern-ai.org.cn](https://colearn.intern-ai.org.cn/set?s=bzl0python) | 10:34 | [link](https://www.bilibili.com/video/BV1u61jYSExg) |
| 1245 | Git 前置基础（熟悉常见 Git 命令及GitHub 平台） | - | AI 论文精读 | - | [github.com](https://github.com/InternLM/Tutorial/blob/camp4/docs/L0/git) [github.com](https://github.com/InternLM/Tutorial/blob/camp4/docs/L0/git/task.md) [colearn.intern-ai.org.cn](https://colearn.intern-ai.org.cn/set?s=bz_git) | 14:40 | [link](https://www.bilibili.com/video/BV15MShYkEgg) |
| 1246 | 玩转Hugging Face/魔搭/魔乐平台(熟悉模型下载上传及应用上传) | - | AI 论文精读 | - | [github.com](https://github.com/InternLM/Tutorial/blob/camp4/docs/L0/maas) [github.com](https://github.com/InternLM/Tutorial/blob/camp4/docs/L0/maas/task.md) [colearn.intern-ai.org.cn](https://colearn.intern-ai.org.cn/set?s=bzl0maas) | 11:04 | [link](https://www.bilibili.com/video/BV1XxStYYEH1) |
| 1247 | 书生·浦语大模型开源开放体系 | - | AI 论文精读 | - | [github.com](https://github.com/InternLM/Tutorial/tree/camp4/docs/L1/ToolChain) [colearn.intern-ai.org.cn](https://colearn.intern-ai.org.cn/set?s=bz_toolchain) [studio.intern-ai.org.cn](https://studio.intern-ai.org.cn/) | 29:01 | [link](https://www.bilibili.com/video/BV1CkSUYGE1v) |
| 1248 | 玩转书生「多模态对话」与「AI 搜索」产品 | - | AI 论文精读 | - | [internlm.intern-ai.org.cn](https://internlm.intern-ai.org.cn/) [github.com](https://github.com/InternLM/Tutorial/blob/camp4/docs/L1/InternIntro) [github.com](https://github.com/InternLM/Tutorial/blob/camp4/docs/L1/InternIntro/tasks.md) | 4:49 | [link](https://www.bilibili.com/video/BV1ExDQYyEAA) |
| 1249 | 浦语提示词工程实践 | - | AI 论文精读 | - | [github.com](https://github.com/InternLM/Tutorial/blob/camp4/docs/L1/Prompt) [github.com](https://github.com/InternLM/Tutorial/blob/camp4/docs/L1/Prompt/tasks.md) [colearn.intern-ai.org.cn](https://colearn.intern-ai.org.cn/set?s=bzprompt) | 70:53 | [link](https://www.bilibili.com/video/BV1tjS7YfEWJ) |
| 1250 | 浦语+LlamaIndex 外挂知识库 RAG 实践 | - | AI 论文精读 | - | [github.com](https://github.com/InternLM/Tutorial/blob/camp4/docs/L1/LlamaIndex/readme_api.md) [github.com](https://github.com/InternLM/Tutorial/blob/camp4/docs/L1/LlamaIndex/task.md) [colearn.intern-ai.org.cn](https://colearn.intern-ai.org.cn/set?s=bzxtuner) | 55:19 | [link](https://www.bilibili.com/video/BV1YzDJY1E2i) |
| 1251 | XTuner 微调 InternLM 个人小助手认知实践 | - | AI 论文精读 | - | [github.com](https://github.com/InternLM/Tutorial/blob/camp4/docs/L1/XTuner) [github.com](https://github.com/InternLM/Tutorial/blob/camp4/docs/L1/XTuner/task.md) [colearn.intern-ai.org.cn](https://colearn.intern-ai.org.cn/set?s=bzxtuner) | 23:47 | [link](https://www.bilibili.com/video/BV1G9SJYGEtD) |
| 1252 | OpenCompass 评测书生大模型实践 | - | AI 论文精读 | - | [github.com](https://github.com/InternLM/Tutorial/blob/camp4/docs/L1/Evaluation) [github.com](https://github.com/InternLM/Tutorial/blob/camp4/docs/L1/Evaluation/task.md) [colearn.intern-ai.org.cn](https://colearn.intern-ai.org.cn/set?s=bzoc) | 23:42 | [link](https://www.bilibili.com/video/BV1dtD4YKENj) |
| 1253 | Lagent 从零搭建你的 Multi-Agent (书生·浦语 API 版) | - | AI 论文精读 | - | [github.com](https://github.com/InternLM/Tutorial/blob/camp4/docs/L2/Agent) [github.com](https://github.com/InternLM/Tutorial/blob/camp4/docs/L2/Agent/task.md) [colearn.intern-ai.org.cn](https://colearn.intern-ai.org.cn/set?s=bzlagent) | 22:29 | [link](https://www.bilibili.com/video/BV19RzcYaEFy) |
| 1254 | LMDeploy 量化部署进阶实践 | - | AI 论文精读 | - | [github.com](https://github.com/InternLM/Tutorial/blob/camp4/docs/L2/LMDeploy) [github.com](https://github.com/InternLM/Tutorial/blob/camp4/docs/L2/LMDeploy/task.md) [colearn.intern-ai.org.cn](https://colearn.intern-ai.org.cn/set?s=bz_lmdeploy) | 89:57 | [link](https://www.bilibili.com/video/BV18aUHY3EEG) |
| 1255 | 多模态大模型发展简述及其微调部署实践(InternVL2为例) | - | AI 论文精读 | - | [github.com](https://github.com/InternLM/Tutorial/blob/camp4/docs/L2/InternVL) [github.com](https://github.com/InternLM/Tutorial/blob/camp4/docs/L2/InternVL/task.md) [colearn.intern-ai.org.cn](https://colearn.intern-ai.org.cn/set?s=bzinternvl) | 23:10 | [link](https://www.bilibili.com/video/BV1nESCYWEnN) |
| 1256 | InternLM+WasmEdge 部署智能体实践 | - | AI 论文精读 | - | - | 13:52 | [link](https://www.bilibili.com/video/BV1K2rAYeEXG) |
| 1257 | EgoExolearn跨视角技能学习数据集 | - | AI 论文精读 | - | - | 25:11 | [link](https://www.bilibili.com/video/BV1pT42167pQ) |
| 1258 | 单阶段多维度模型搜索范式 | - | AI 论文精读 | - | - | 34:25 | [link](https://www.bilibili.com/video/BV1Yb421J7wA) |
| 1259 | MVBench 多模态视频评测体系 | - | AI 论文精读 | - | - | 28:53 | [link](https://www.bilibili.com/video/BV1ZE4m1R7Tc) |
| 1260 | 人机协作的视觉生成 | - | AI 论文精读 | - | - | 29:13 | [link](https://www.bilibili.com/video/BV1fZ421N7re) |
| 1261 | 个性化图像动画生成器，利用文本提示将图像变为奇妙的动画 | - | AI 论文精读 | [2312.13964](https://arxiv.org/abs/2312.13964) | [github.com](https://github.com/open-mmlab/PIA) [openxlab.org.cn](https://openxlab.org.cn/apps/detail/zhangyiming/PiaPia/) | 28:27 | [link](https://www.bilibili.com/video/BV1PE4m197ZM) |
| 1262 | 基于像素点的拖拽式图像编辑分享 | - | AI 论文精读 | - | [github.com](https://github.com/LPengYang/FreeDrag) [openxlab.org.cn](https://openxlab.org.cn/apps/detail/LPengYang/FreeDrag) | 38:13 | [link](https://www.bilibili.com/video/BV1XH4y1c78r) |
| 1263 | GenNBV：面向主动三维重建的可泛化最佳视角探索策略 | - | AI 论文精读 | [2402.16174](https://arxiv.org/abs/2402.16174) | [github.com](https://github.com/zjwzcx/GenNBV) | 37:23 | [link](https://www.bilibili.com/video/BV1yy411i7jh) |
| 1264 | 多模态大模型幻觉成因解释以及基于惩罚回退策略的幻觉缓解方法 | - | AI 论文精读 | [2311.17911](https://arxiv.org/abs/2311.17911) | [github.com](https://github.com/shikiw/OPERA) | 25:13 | [link](https://www.bilibili.com/video/BV1QH4y1c7p3) |
| 1265 | 中文常识推理基准-CHARM | - | AI 论文精读 | [2403.14112](https://arxiv.org/abs/2403.14112) | [github.com](https://github.com/opendatalab/CHARM) [hub.opencompass.org.cn](https://hub.opencompass.org.cn/dataset-detail/CHARM) | 12:23 | [link](https://www.bilibili.com/video/BV1QcmdYiExz) |
| 1266 | 分享 SALAD-BENCH 数据集与评估方法 | - | AI 论文精读 | - | [github.com](https://github.com/OpenSafetyLab/SALAD-BENCH) [hub.opencompass.org.cn](https://hub.opencompass.org.cn/dataset-detail/SALAD-Bench) | 28:19 | [link](https://www.bilibili.com/video/BV1KimoYaExY) |
| 1267 | 评估大语言模型多轮对话能力的细粒度评测集 | - | AI 论文精读 | - | [aclanthology.org](https://aclanthology.org/2024.acl-long.401/) [github.com](https://github.com/mtbench101) [hub.opencompass.org.cn](https://hub.opencompass.org.cn/dataset-detail/MT-Bench-101) | 23:11 | [link](https://www.bilibili.com/video/BV1mvmoYAEAv) |
| 1268 | ConvBench：多轮视觉对话评测基准与能力解耦评测方式 | - | AI 论文精读 | [2406.11833](https://arxiv.org/abs/2406.11833) | [github.com](https://github.com/Liuziyu77/MMDU) [hub.opencompass.org.cn](https://hub.opencompass.org.cn/dataset-detail/MMDU) | 17:00 | [link](https://www.bilibili.com/video/BV1QbcRevE61) |
| 1269 | GTA：大模型复杂任务工具调用能力评测 | - | AI 论文精读 | [2407.08713](https://arxiv.org/abs/2407.08713) | [open-compass.github.io](https://open-compass.github.io/GTA) [hub.opencompass.org.cn](https://hub.opencompass.org.cn/dataset-detail/GTA) | 17:17 | [link](https://www.bilibili.com/video/BV1cucReJETD) |
| 1270 | MMDU：高质量多图多轮对话数据集 | - | AI 论文精读 | [2406.11833](https://arxiv.org/abs/2406.11833) | [github.com](https://github.com/Liuziyu77/MMDU) [hub.opencompass.org.cn](https://hub.opencompass.org.cn/dataset-detail/MMDU) | 15:36 | [link](https://www.bilibili.com/video/BV1HTcReDEhX) |
| 1271 | MMLongBench-Doc：使用可视化对长上下文文档理解进行基准测试 | - | AI 论文精读 | [2407.01523](https://arxiv.org/abs/2407.01523) | [github.com](https://github.com/mayubo2333/MMLongBench-Doc) [hub.opencompass.org.cn](https://hub.opencompass.org.cn/dataset-detail/MMLongBench-Doc) | 25:00 | [link](https://www.bilibili.com/video/BV19scReMEdS) |
| 1272 | 多模态推理的评测以及后训练 | - | AI 论文精读 | - | [hub.opencompass.org.cn](https://hub.opencompass.org.cn/dataset-detail/MMIU) | 17:44 | [link](https://www.bilibili.com/video/BV1C9XrYaEyz) |
| 1273 | 多模态动态评测（Oral） | - | AI 论文精读 | - | - | 20:41 | [link](https://www.bilibili.com/video/BV1P9XrYYEje) |
| 1274 | LOKI：基于多模态大模型的合成数据检测基准 | - | AI 论文精读 | - | [hub.opencompass.org.cn](https://hub.opencompass.org.cn/dataset-detail/LOKI) | 37:35 | [link](https://www.bilibili.com/video/BV1JJXrYdEXi) |
| 1275 | Sim-CoT 驱动高效隐式思考 | - | AI 论文精读 | - | [github.com](https://github.com/InternLM/SIM-CoT) | 28:03 | [link](https://www.bilibili.com/video/BV1VGEC6fErh) |
| 1276 | 数据分布解读 RL 如何“学新不忘旧” | - | AI 论文精读 | - | - | 24:25 | [link](https://www.bilibili.com/video/BV1afE16NEXf) |
| 1277 | 数据驱动的大模型长度泛化推理新范式 | - | AI 论文精读 | [2507.13332](https://arxiv.org/abs/2507.13332) | - | 14:15 | [link](https://www.bilibili.com/video/BV1H2TF64Ek9) |
| 1278 | 利用智能体解锁地球观测的完整图景 | - | AI 论文精读 | [2509.23141](https://arxiv.org/abs/2509.23141) | [opendatalab.github.io](https://opendatalab.github.io/Earth-Agent/) | 13:43 | [link](https://www.bilibili.com/video/BV1LUTj6FE9N) |
| 1279 | 冗余性解耦的高效长文本偏好优化 | - | AI 论文精读 | - | [openreview.net](https://openreview.net/pdf?id=iiBjaiikJG) [github.com](https://github.com/shs910/SoLoPO) | 30:48 | [link](https://www.bilibili.com/video/BV12uTQ6CEHz) |
| 1280 | AI科研加速营第1课｜用AI快速看懂一个研究方向 | - | AI 论文精读 | - | [sensorsdata.intern-ai.org.cn](https://sensorsdata.intern-ai.org.cn/t/ca) | 17:37 | [link](https://www.bilibili.com/video/BV1jMY163EWE) |
| 1281 | AI科研加速营第2课｜AI论文工作流：检索、精读与核验 | - | AI 论文精读 | - | [sensorsdata.intern-ai.org.cn](https://sensorsdata.intern-ai.org.cn/t/ca) | 12:32 | [link](https://www.bilibili.com/video/BV1tTen6ZEmy) |
| 1282 | AI科研加速营第3课｜建立可持续更新的研究上下文 | - | AI 论文精读 | - | [sensorsdata.intern-ai.org.cn](https://sensorsdata.intern-ai.org.cn/t/ca) | 18:30 | [link](https://www.bilibili.com/video/BV11zec6NE3k) |
| 1283 | AI科研加速营第4课｜AI辅助实验设计：科学数据与计算一体化实践 | - | AI 论文精读 | - | [sensorsdata.intern-ai.org.cn](https://sensorsdata.intern-ai.org.cn/t/ca) | 41:38 | [link](https://www.bilibili.com/video/BV1FTeG6dEQ4) |
| 1284 | AI科研加速营第5课｜AI辅助论文与课题申请书写作 | - | AI 论文精读 | - | [sensorsdata.intern-ai.org.cn](https://sensorsdata.intern-ai.org.cn/t/ca) | 20:59 | [link](https://www.bilibili.com/video/BV1xLe16bE2p) |
| 1285 | AI科研加速营第6课｜把科研方法沉淀为可复用的Agent Skill | - | AI 论文精读 | - | [sensorsdata.intern-ai.org.cn](https://sensorsdata.intern-ai.org.cn/t/ca) | 17:55 | [link](https://www.bilibili.com/video/BV1TZem6BEQP) |
| 1286 | AI科研加速营第7课｜通往可扩展、统一的蛋白基础模型之路 | - | AI 论文精读 | - | [sensorsdata.intern-ai.org.cn](https://sensorsdata.intern-ai.org.cn/t/ca) | 33:54 | [link](https://www.bilibili.com/video/BV1sHem6AEXD) |
| 1287 | AI科研加速营第8课｜大模型时代的物质科学研究 | - | AI 论文精读 | - | [sensorsdata.intern-ai.org.cn](https://sensorsdata.intern-ai.org.cn/t/ca) | 18:23 | [link](https://www.bilibili.com/video/BV1Vfhv6BEXx) |
| 1288 | AI科研加速营第9课｜地球科学中的科学智能：从工具的革命到革命的工具 | - | AI 论文精读 | - | [sensorsdata.intern-ai.org.cn](https://sensorsdata.intern-ai.org.cn/t/ca) | 24:30 | [link](https://www.bilibili.com/video/BV16RhE6TEmM) |
| 1289 | OpenMMLab 环境配置 （一） Windows 11 CPU | - | AI 论文精读 | - | [mmsig.openmmlab.com](https://mmsig.openmmlab.com/general/env/win11) | 18:43 | [link](https://www.bilibili.com/video/BV1Bh41157gL) |
| 1290 | 通用、统一且灵活的开源算法平台 OpenMMLab 2.0 / CVPR 2023 （全英分享） | - | AI 论文精读 | - | [github.com](https://github.com/open-mmlab) | 17:28 | [link](https://www.bilibili.com/video/BV1Zg4y1P7LB) |
| 1291 | 视觉基础模型的探索：MMPreTrain / CVPR 2023 (全英分享) | - | AI 论文精读 | - | [github.com](https://github.com/open-mmlab/mmpretrain) | 31:56 | [link](https://www.bilibili.com/video/BV11s4y1C7S9) |
| 1292 | 通用目标检测工具 MMDetection3.0 / CVPR 2023 （全英分享） | - | AI 论文精读 | - | [github.com](https://github.com/open-mmlab/mmdetection) | 30:47 | [link](https://www.bilibili.com/video/BV1214y1274j) |
| 1293 | 图像与视频生成、编辑和增强工具 MMagic / CVPR 2023 （全英分享） | - | AI 论文精读 | - | [github.com](https://github.com/open-mmlab/mmagic) | 26:08 | [link](https://www.bilibili.com/video/BV1nX4y1q7DF) |
| 1294 | 面向人工智能的开放数据平台：OpenDataLab / CVPR 2023 （全英分享） | - | AI 论文精读 | - | - | 12:09 | [link](https://www.bilibili.com/video/BV1Hm4y1a7Xa) |
| 1295 | 【CVPR-2022】/ Kai Chen -- Overview of OpenMMLab and Recent Updates | - | AI 论文精读 | - | - | 38:09 | [link](https://www.bilibili.com/video/BV1H84y1z7Ce) |
| 1296 | 【CVPR-2022】/ Chen Change Loy -- Improving Video Super-Resolution | - | AI 论文精读 | - | - | 32:03 | [link](https://www.bilibili.com/video/BV1mP411P7za) |
| 1297 | 【CVPR-2022】/ Han Hu -- Convergence of Architectures and Learning Methods | - | AI 论文精读 | - | - | 33:38 | [link](https://www.bilibili.com/video/BV1vG411j79R) |
| 1298 | 【CVPR-2022】/ Hang Zhao -- Vision-centric 3D Perception | - | AI 论文精读 | - | - | 32:42 | [link](https://www.bilibili.com/video/BV1y44y1f72z) |
| 1299 | 【CVPR-2022】/ Haodong Duan -- Action Understanding in A Human-centric View | - | AI 论文精读 | - | - | 24:33 | [link](https://www.bilibili.com/video/BV1iG4y1p78W) |
| 1300 | Wenwei Zhang / General Detection with MMDetection | - | AI 论文精读 | - | - | 34:02 | [link](https://www.bilibili.com/video/BV1A8411F7Ti) |
| 1301 | OpenMMLab：视觉、语言与生成式人工智能开源平台 | - | AI 论文精读 | - | - | 21:25 | [link](https://www.bilibili.com/video/BV1z94y18767) |
| 1302 | OpenMMLab基础模型研究进展 | - | AI 论文精读 | - | - | 28:52 | [link](https://www.bilibili.com/video/BV1tC4y157hc) |
| 1303 | OpenDataLab —— 一个面向人工智能的开放数据平台 | - | AI 论文精读 | - | - | 14:37 | [link](https://www.bilibili.com/video/BV1334y1G7RA) |
| 1304 | MMagic —— 图像与视频生成、编辑及增强工具库 | - | AI 论文精读 | - | - | 21:40 | [link](https://www.bilibili.com/video/BV1P94y187HE) |
| 1305 | MMDetection：从通用目标检测迈向多模态智能体 | - | AI 论文精读 | - | - | 33:54 | [link](https://www.bilibili.com/video/BV1134y1u7dq) |
| 1306 | 书生·浦语大模型全链路开源体系 | - | AI 论文精读 | - | [github.com](https://github.com/InternLM/InternLM/) [wjx.cn](https://www.wjx.cn/vm/tUX8dEV.aspx?udsid=240962) | 36:24 | [link](https://www.bilibili.com/video/BV1Vx421X72D) |
| 1307 | 轻松玩转书生·浦语大模型趣味 Demo | - | AI 论文精读 | - | [github.com](https://github.com/InternLM/Tutorial/blob/camp2/helloworld/hello_world.md) [wjx.cn](https://www.wjx.cn/vm/tUX8dEV.aspx?udsid=240962) [github.com](https://github.com/InternLM/InternLM) | 21:15 | [link](https://www.bilibili.com/video/BV1AH4y1H78d) |
| 1308 | 茴香豆：搭建你的 RAG 智能助理 | - | AI 论文精读 | - | [github.com](https://github.com/InternLM/Tutorial/blob/camp2/huixiangdou/readme.md) [wjx.cn](https://www.wjx.cn/vm/tUX8dEV.aspx?udsid=240962) [github.com](https://github.com/InternLM/HuixiangDou) | 42:26 | [link](https://www.bilibili.com/video/BV1QA4m1F7t4) |
| 1309 | XTuner 微调 LLM：1.8B、多模态、Agent | - | AI 论文精读 | - | [github.com](https://github.com/InternLM/Tutorial/blob/camp2/xtuner/readme.md) [github.com](https://github.com/InternLM/Tutorial/blob/camp2/xtuner/homework.md) [github.com](https://github.com/InternLM/XTuner) | 72:29 | [link](https://www.bilibili.com/video/BV15m421j78d) |
| 1310 | LMDeploy 量化部署 LLM-VLM 实践 | - | AI 论文精读 | - | [github.com](https://github.com/InternLM/Tutorial/blob/camp2/lmdeploy/README.md) [github.com](https://github.com/InternLM/Tutorial/blob/camp2/lmdeploy/homework.md) [github.com](https://github.com/InternLM/LMDeploy) | 52:30 | [link](https://www.bilibili.com/video/BV1tr421x75B) |
| 1311 | Lagent & AgentLego 智能体应用搭建 | - | AI 论文精读 | - | [github.com](https://github.com/InternLM/Tutorial/tree/camp2/agent) [github.com](https://github.com/InternLM/Tutorial/blob/camp2/agent/homework.md) [github.com](https://github.com/InternLM/Lagent) | 35:40 | [link](https://www.bilibili.com/video/BV1Xt4217728) |
| 1312 | OpenCompass 大模型评测实战 | - | AI 论文精读 | - | [github.com](https://github.com/InternLM/Tutorial/blob/camp2/opencompass/readme.md) [github.com](https://github.com/InternLM/Tutorial/blob/camp2/opencompass/homework.md) [github.com](https://github.com/open-compass/opencompass) | 45:36 | [link](https://www.bilibili.com/video/BV1Pm41127jU) |
| 1313 | 大模型微调数据构造（补充课程） | - | AI 论文精读 | - | - | 38:14 | [link](https://www.bilibili.com/video/BV1Dx4y1z7Ju) |
| 1314 | 多模态简述 | - | AI 论文精读 | - | - | 46:34 | [link](https://www.bilibili.com/video/BV12E421A76T) |
| 1315 | LMDeploy 量化部署 InternVL 浦语灵笔实践 | - | AI 论文精读 | - | [github.com](https://github.com/InternLM/Tutorial/tree/camp2/lmdeploy_vlm) | 7:19 | [link](https://www.bilibili.com/video/BV11m421373q) |
| 1316 | XTuner 微调 LLaVA 实践 | - | AI 论文精读 | - | [github.com](https://github.com/InternLM/Tutorial/blob/camp2/xtuner/llava/xtuner_llava.md) | 28:28 | [link](https://www.bilibili.com/video/BV1vZ421M7ig) |
| 1317 | AI实战营第二期 开营仪式 | - | AI 论文精读 | - | - | 66:24 | [link](https://www.bilibili.com/video/BV1sc411V74M) |
| 1318 | Github八万star，开源计算机视觉神器OpenMMLab | - | AI 论文精读 | - | [openmmlab.com](https://openmmlab.com) [github.com](https://github.com/open-mmlab) | 27:02 | [link](https://www.bilibili.com/video/BV1js4y1i72P) |
| 1319 | 深度学习预训练与MMPretrain | - | AI 论文精读 | - | - | 38:07 | [link](https://www.bilibili.com/video/BV1PN411y7C1) |
| 1320 | 目标检测与MMDetection | - | AI 论文精读 | - | - | 89:59 | [link](https://www.bilibili.com/video/BV1Ak4y1p7W9) |
| 1321 | MMDetection代码课 | - | AI 论文精读 | - | - | 46:49 | [link](https://www.bilibili.com/video/BV1Tm4y1q7fy) |
| 1322 | 语义分割与MMSegmentation | - | AI 论文精读 | - | [github.com](https://github.com/open-mmlab/mmsegmentation) [github.com](https://github.com/TommyZihao/MMSegmentation_Tutorials) | 37:05 | [link](https://www.bilibili.com/video/BV1gV4y1m74P) |
| 1323 | 玩转AIGC神器MMagic | - | AI 论文精读 | - | [github.com](https://github.com/open-mmlab/mmagic) [github.com](https://github.com/TommyZihao/MMagic_Tutorials) | 31:24 | [link](https://www.bilibili.com/video/BV1gM4y1n7vP) |
| 1324 | 【OpenMMLab 2.0 系列直播】OpenMMLab 2.0 整体介绍 | - | AI 论文精读 | - | - | 22:15 | [link](https://www.bilibili.com/video/BV1Yd4y1z7bo) |
| 1325 | 【OpenMMLab 2.0 系列直播】MMEngine & MMCV 介绍 | - | AI 论文精读 | - | - | 82:27 | [link](https://www.bilibili.com/video/BV15B4y1779M) |
| 1326 | 【OpenMMLab 2.0 系列直播】MMClassification 介绍 | - | AI 论文精读 | - | - | 28:11 | [link](https://www.bilibili.com/video/BV1x24y1R7mD) |
| 1327 | 【OpenMMLab 2.0 系列直播】MMSelfsup 介绍 | - | AI 论文精读 | - | - | 15:53 | [link](https://www.bilibili.com/video/BV1214y1h7CJ) |
| 1328 | 【OpenMMLab 2.0 系列直播】MMDetection 介绍 | - | AI 论文精读 | - | - | 31:26 | [link](https://www.bilibili.com/video/BV19G411g7w9) |
| 1329 | 【OpenMMLab 2.0 系列直播】MMDetection3D 介绍 | - | AI 论文精读 | - | - | 17:32 | [link](https://www.bilibili.com/video/BV1YD4y117w6) |
| 1330 | 【OpenMMLab 2.0 系列直播】OpenMMLab 社区荣誉体系介绍 | - | AI 论文精读 | - | - | 16:50 | [link](https://www.bilibili.com/video/BV1kB4y1J7u9) |
| 1331 | 【OpenMMLab 2.0 系列直播】MMSegmentation 介绍 | - | AI 论文精读 | - | - | 42:06 | [link](https://www.bilibili.com/video/BV1F841147JZ) |
| 1332 | 【OpenMMLab 2.0 系列直播】 MMAction2 介绍 | - | AI 论文精读 | - | - | 18:03 | [link](https://www.bilibili.com/video/BV1V841147Jp) |
| 1333 | 【OpenMMLab 2.0 系列直播】MMPose 介绍 | - | AI 论文精读 | - | - | 33:39 | [link](https://www.bilibili.com/video/BV11B4y1J7oD) |
| 1334 | 【OpenMMLab 2.0 系列直播】 MMEditing & MMGeneration 介绍 | - | AI 论文精读 | - | - | 34:12 | [link](https://www.bilibili.com/video/BV1Xd4y1M7zE) |
| 1335 | 【OpenMMLab 2.0 系列直播】MMOCR 介绍 | - | AI 论文精读 | - | - | 43:42 | [link](https://www.bilibili.com/video/BV1wY4y1K7DZ) |
| 1336 | 【OpenMMLab 2.0 系列直播】MMRazor 介绍 | - | AI 论文精读 | - | - | 51:11 | [link](https://www.bilibili.com/video/BV1ug411e7Jp) |
| 1337 | 【OpenMMLab 2.0 系列直播】MMYOLO 介绍 | - | AI 论文精读 | - | - | 26:03 | [link](https://www.bilibili.com/video/BV19e4y1674D) |
| 1338 | 【OpenMMLab 2.0 系列直播】RTMDet | - | AI 论文精读 | - | - | 36:58 | [link](https://www.bilibili.com/video/BV1e841147GD) |
| 1339 | 大模型时代下视觉网络的创新设计与拓展 / 热门研究 云际会#1 | - | AI 论文精读 | - | - | 136:51 | [link](https://www.bilibili.com/video/BV18L411m7jU) |
| 1340 | 多模态大模型的前奏：迈向真实世界的通用感知 / 热门研究云际会#2 | - | AI 论文精读 | - | - | 118:53 | [link](https://www.bilibili.com/video/BV1W24y1c7mB) |
| 1341 | 探索之路：OCR 领域在大模型浪潮中的创新契机 / 热门研究云际会#3 | - | AI 论文精读 | - | - | 119:15 | [link](https://www.bilibili.com/video/BV1Lh411E787) |
| 1342 | 多模态扩散模型的革新应用 / 热门研究云际会#4 | - | AI 论文精读 | - | - | 123:44 | [link](https://www.bilibili.com/video/BV1pP411273K) |
| 1343 | 基于 SiliconCloud 平台使用 MindSearch | - | AI 论文精读 | - | [github.com](https://github.com/InternLM/mindsearch) [mindsearch.netlify.app](https://mindsearch.netlify.app/) [cloud.siliconflow.cn](https://cloud.siliconflow.cn/playground/chat) | 18:13 | [link](https://www.bilibili.com/video/BV163sxeZEPi) |
| 1344 | AI 实战营开营仪式 | - | AI 论文精读 | - | - | 48:06 | [link](https://www.bilibili.com/video/BV1o3411X7MB) |
| 1345 | 1 计算机视觉算法基础与OpenMMLab介绍 | - | AI 论文精读 | - | - | 114:53 | [link](https://www.bilibili.com/video/BV1Ty4y1X7X1) |
| 1346 | 2 计算机视觉之图像分类算法基础 | - | AI 论文精读 | - | - | 91:03 | [link](https://www.bilibili.com/video/BV1js4y1W7CN) |
| 1347 | 3 图像分类代码实战与超算平台介绍 | - | AI 论文精读 | - | - | 117:34 | [link](https://www.bilibili.com/video/BV1MA411k7NT) |
| 1348 | 4 目标检测算法基础 | - | AI 论文精读 | - | - | 75:28 | [link](https://www.bilibili.com/video/BV1Ay4y1Q7mC) |
| 1349 | 5 MMDetection 代码教学 | - | AI 论文精读 | - | - | 134:41 | [link](https://www.bilibili.com/video/BV1Av4y1475i) |
| 1350 | 6 语义分割算法基础 | - | AI 论文精读 | - | - | 61:09 | [link](https://www.bilibili.com/video/BV1s24y1W7Xa) |
| 1351 | 7 MMSegmentation 代码教学 | - | AI 论文精读 | - | - | 79:20 | [link](https://www.bilibili.com/video/BV1eT411R7Jq) |
| 1352 | AI实战营 结营仪式 | - | AI 论文精读 | - | - | 17:33 | [link](https://www.bilibili.com/video/BV1ge4y1c7tY) |
| 1353 | 书生·浦语大模型全链路开源体系 | - | AI 论文精读 | - | [github.com](https://github.com/internLM/tutorial) | 42:00 | [link](https://www.bilibili.com/video/BV1Rc411b7ns) |
| 1354 | 轻松玩转书生·浦语大模型趣味Demo | - | AI 论文精读 | - | [github.com](https://github.com/InternLM/tutorial/blob/main/helloworld/hello_world.md) | 45:49 | [link](https://www.bilibili.com/video/BV1Ci4y1z72H) |
| 1355 | 基于 InternLM 和 LangChain 搭建你的知识库 | - | AI 论文精读 | - | [github.com](https://github.com/InternLM/tutorial/tree/main/langchain) | 39:17 | [link](https://www.bilibili.com/video/BV1sT4y1p71V) |
| 1356 | XTuner 大模型单卡低成本微调实战 | - | AI 论文精读 | - | [github.com](https://github.com/InternLM/tutorial/blob/main/xtuner/README.md) [github.com](https://github.com/internLM/xtuner) | 94:01 | [link](https://www.bilibili.com/video/BV1yK4y1B75J) |
| 1357 | XTuner 大模型低成本微调作业讲解——个人小助手认知微调实践 | - | AI 论文精读 | - | [github.com](https://github.com/InternLM/tutorial/blob/main/xtuner/self.md) | 15:58 | [link](https://www.bilibili.com/video/BV13t4y1o75X) |
| 1358 | LMDeploy 大模型量化部署实践 | - | AI 论文精读 | - | [github.com](https://github.com/InternLM/tutorial/blob/main/lmdeploy/lmdeploy.md) [github.com](https://github.com/internLM/lmdeploy) | 91:12 | [link](https://www.bilibili.com/video/BV1iW4y1A77P) |
| 1359 | OpenCompass 大模型评测 | - | AI 论文精读 | - | [github.com](https://github.com/InternLM/tutorial/blob/main/opencompass/opencompass_tutorial.md) [github.com](https://github.com/open-compass/opencompass) | 51:31 | [link](https://www.bilibili.com/video/BV1Gg4y1U7uc) |
| 1360 | [数学基础与PyTorch] 01 从变分推断到 FKL/RKL 的讨论，到 ELBO/VAE，以及知识蒸馏（FKL） | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/math/calculus/variational_inferenc_rkl_vae.ipynb) | 17:37 | [link](https://www.bilibili.com/video/BV1MZkxBZEPv) |
| 1361 | [数学基础与PyTorch] 02 梯度的视角回顾 Pretrain 和 SFT 的 Cross Entropy Loss，LLM如何更新 token emb | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/math/pytorch/cross-entropy-loss-gradient-descent.ipynb) | 20:29 | [link](https://www.bilibili.com/video/BV1YN5d67ETR) |
| 1362 | [数学基础与PyTorch] 03 回顾策略梯度，score function trick，蒙特卡洛采样，pytorch 优化与重要性采样 | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/math/pytorch/pg-score-function.ipynb) [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/math/pytorch/score-reparameterization.ipynb) | 9:32 | [link](https://www.bilibili.com/video/BV1VFVV6ZENF) |
| 1363 | [数学基础与PyTorch] 04 策略梯度score function trick 与 VAE 重参数化 trick | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/math/pytorch/score-reparameterization.ipynb) [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/math/pytorch/pg-score-function.ipynb) | 18:30 | [link](https://www.bilibili.com/video/BV1CCVU65EqD) |
| 1364 | [数学基础与PyTorch] 05 OPD-01 RKL/FKL, TopK, 为什么可以复用RL infra，seq level KL，verl/slime | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agentic_rl/distillation/opd-01.ipynb) | 32:02 | [link](https://www.bilibili.com/video/BV1WpGu6aEKo) |
| 1365 | [数学基础与PyTorch] 06 理解高维Tensor，手撕 MHA 为什么先 reshape 再 permute？view/stride/contiguou | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/math/pytorch/basics/tensor-shape-axis-processing.ipynb) [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/math/pytorch/basics/vit-attention.ipynb) | 38:26 | [link](https://www.bilibili.com/video/BV1RphN6DEeQ) |
| 1366 | [数学基础与PyTorch] 07 MHA 的 QKVO 四重投影，为什么少不了 W_O？concat 再乘 ≡ 逐 head 求和 / OV 电路 rank | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/llms/%E6%9E%B6%E6%9E%84/kimi/attentions.ipynb) | 26:59 | [link](https://www.bilibili.com/video/BV1ZktH6cESE) |
| 1367 | [数学基础与PyTorch] 08 Jev 决策模型与概率校准，ECE 计算，RL之后LLM过度自信 | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/llms/%E6%9E%B6%E6%9E%84/jev/calibration.ipynb) [aclanthology.org](https://aclanthology.org/2023.emnlp-main.330.pdf) | 25:39 | [link](https://www.bilibili.com/video/BV1y1pJ6XEc5) |
| 1368 | [A100 Training] 01 熟悉一台A100 SXM GPU计算节点，必要基础配置，SXM/PCIe/HGX，CPU与GPU带宽及内存带宽测试 | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agentic_rl/training_projs/%E5%BD%93%E6%8B%BF%E5%88%B0%E4%B8%80%E4%B8%AAA100%E7%9A%84%E8%8A%82%E7%82%B9.ipynb) [github.com](https://github.com/wdkns/modern_genai_bilibili/tree/main/agentic_rl/training_projs/scripts) | 32:24 | [link](https://www.bilibili.com/video/BV1CGN26EEeT) |
| 1369 | [A100 Training] 02 verl/slime 框架及训练任务介绍，插拔式设计，Qwen3.5全家桶，InfiGUI，thinking mode | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/modern_genai_bilibili/tree/main/agentic_rl/training_projs) | 26:28 | [link](https://www.bilibili.com/video/BV1xJKB6vEzh) |
| 1370 | [A100 Training] 03 verl/slime 一些实际的训练经验，踩过的坑，wandb，GDN，remove pad，精度，clip_ratio | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/modern_genai_bilibili/tree/main/agentic_rl/training_projs) | 29:38 | [link](https://www.bilibili.com/video/BV1MTKp6bEn4) |
| 1371 | [A100 Training] 04 verl/slime Docker 容器 debug，断点调试，源码细读，ray 分布式 debug | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/modern_genai_bilibili/tree/main/agentic_rl/training_projs) | 15:17 | [link](https://www.bilibili.com/video/BV19Qgy6rE32) |
| 1372 | [Pro6000 Training] 05 8卡Pro 6000 硬件概览，感知硬件，理解拓扑，NUMA / 一切都关乎通信带宽 | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/slides/pro6000-%E7%A1%AC%E4%BB%B6%E5%85%A8%E8%A7%A3-%E5%85%AC%E5%BC%80%E7%89%88.pdf) | 29:09 | [link](https://www.bilibili.com/video/BV1EjeA6ZEi9) |
| 1373 | [Pro 6000 Training] 06 8卡 RTX PRO 6000 原生 FP4 装下 GLM-5.3：NVFP4、E2M1、KV cache 与并发 | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agentic_rl/training_projs/pro6000/platform-2-supp.ipynb) [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/slides/pro6000-%E7%A1%AC%E4%BB%B6%E5%85%A8%E8%A7%A3-%E5%85%AC%E5%BC%80%E7%89%88.pdf) | 23:02 | [link](https://www.bilibili.com/video/BV1vfHC6MEk3) |
| 1374 | [LLM Architect] 01 MoE 初步，参数量计算，Qwen3-30B-A3B，GQA 与 Sparse MoE | - | AI 论文精读 | - | - | 15:30 | [link](https://www.bilibili.com/video/BV1P5nfz6Eto) |
| 1375 | [LLM Architect] 02 Qwen3 Dense vs. MoE，MoE 等效宽度，attention vs. ffn，RMSNorm | - | AI 论文精读 | - | - | 19:03 | [link](https://www.bilibili.com/video/BV1ty4TzSEpg) |
| 1376 | [Reasoning Model] K2 Thinking，理解 Interleaved thinking 交错推理，定义和处理 Turn | - | AI 论文精读 | - | - | 14:53 | [link](https://www.bilibili.com/video/BV1AMCdBqEe1) |
| 1377 | [kimi] muon optimizer 基本原理，梯度白化（正交化），zeropower，newtonschulz5，，svd，范数 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_rl/blob/main/tutorials/k2/muon_basics.ipynb) | 21:48 | [link](https://www.bilibili.com/video/BV18sgtzKEVQ) |
| 1378 | [LLM Architect] 04 RoPE 理解的几何视角，Qwen3 RoPE 计算细节，与 Interleaved 版本的对比 | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/llms/%E6%9E%B6%E6%9E%84/pe/RoPE-geometric.ipynb) | 18:23 | [link](https://www.bilibili.com/video/BV1cv2XBAEsA) |
| 1379 | [LLM Architect] 05 RoPE Attention 远程衰减理解与推导，如何同时编码短距离和长距离，Base 与 Context Window | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/llms/%E6%9E%B6%E6%9E%84/pe/RoPE%20%E8%A1%A5%E5%85%85.ipynb) | 16:52 | [link](https://www.bilibili.com/video/BV1qVmYBzE2d) |
| 1380 | [LLM Architect] 06 Attention Head 典型模式识别与分析，Attention Sink、PTH、Induction Head | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/llms/%E6%9E%B6%E6%9E%84/attention/attention_pattern.ipynb) | 19:04 | [link](https://www.bilibili.com/video/BV16xB6B3EVi) |
| 1381 | [LLM Architect] 07 VLM 多模态模型架构设计，对比 Gemini Qwen3-VL 与 Kimi K2.5，如何理解原生多模态 | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/llms/%E5%A4%9A%E6%A8%A1%E6%80%81/%E5%8E%9F%E7%94%9F%E5%A4%9A%E6%A8%A1%E6%80%81.ipynb) | 17:25 | [link](https://www.bilibili.com/video/BV1jJfDBUEcR) |
| 1382 | [LLM Architect] 08 Dive into K2.5，Kimi K2.5 论文串讲与导读，原生多模态，Agent Swarm，国产之光 | - | AI 论文精读 | [2602.02276](https://arxiv.org/abs/2602.02276) | - | 58:20 | [link](https://www.bilibili.com/video/BV1nvcuz5Ewj) |
| 1383 | [LLM Architect] 09 深入理解和对比 prefill与decode / kv-cache / 并行-串行 / GEMM-GEMV / 算力-带宽 | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/llms/%E6%9E%B6%E6%9E%84/prefill-decode.ipynb) | 34:01 | [link](https://www.bilibili.com/video/BV1APAuzpEHY) |
| 1384 | [LLM Architect] 10 为什么LLM无法理解输出马嘉祺，深入理解Glitch（故障）Token，词嵌入漂移、SFT/RL、gradient 视角 | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/llms/%E6%9E%B6%E6%9E%84/tokenizers/special_Glitch_tokens.ipynb) | 24:47 | [link](https://www.bilibili.com/video/BV1qZRZBcEiH) |
| 1385 | [LLM Architect] 11 探测解码分布一致性推导，MTP 拓扑结构，训练与self speculative decoding | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agentic_rl/infra/%E6%8E%A2%E6%B5%8B%E8%A7%A3%E7%A0%81-MTP.ipynb) | 25:09 | [link](https://www.bilibili.com/video/BV1naJp6EEey) |
| 1386 | [LLM Architect] 12 Kimi K3 架构初步，张量计算视角，KDA，MLA，Latent MoE，MoonViT 与残差注意力 | - | AI 论文精读 | [2607.24653](https://arxiv.org/abs/2607.24653) | [github.com](https://github.com/wdkns/wdkns-skills/tree/main/demos/kimi-k3-tensor) [github.com](https://github.com/wdkns/wdkns-skills/tree/main/skills/tensor-formula-viz) | 32:40 | [link](https://www.bilibili.com/video/BV1VpMB6nEvH) |
| 1387 | [LLM Architect] 13 Kimi K3 门控机制，门控注意力，Gated MLA，KDA的门控分支，MoE 中的SiTU-GLU，SwiGLU | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/llms/%E6%9E%B6%E6%9E%84/kimi/activations.ipynb) | 16:46 | [link](https://www.bilibili.com/video/BV1UNur6pEkZ) |
| 1388 | [LLM Architect] 14 DeepSeek V4.1 Causal Encoder Decoder， yoco 对比与 kvcache | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/llms/%E6%9E%B6%E6%9E%84/dpsk/v4.1/ced.ipynb) [github.com](https://github.com/wdkns/modern_genai_bilibili/tree/main/slides) | 25:10 | [link](https://www.bilibili.com/video/BV1ceYX6iE4P) |
| 1389 | [LLM Architect] 15 Jev 架构推测，Tree Mask 隔离复用与并行计算，概率与confidence，RLCD/RLCR | - | AI 论文精读 | - | [archerhume.com](https://archerhume.com/posts/jevs-architecture-unmasked/) [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/slides/jev_architecture-v2.pdf) | 22:09 | [link](https://www.bilibili.com/video/BV1Mihq6AEbc) |
| 1390 | [Agentic Infra] [Ray] 01 ray task与ray actor基础（Ray remote），分布式任务调度，并发控制，多进程多线程与协程 | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agentic_rl/verl/ray/ray_remote_get.ipynb) | 22:51 | [link](https://www.bilibili.com/video/BV1HuZcBEEyy) |
| 1391 | [Agentic Infra]  02 RL post-training 训练框架，训练流程参数分析与指标监控，显存分配与性能调优 | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agentic_rl/verl/verl-algos-metrics.ipynb) | 34:47 | [link](https://www.bilibili.com/video/BV1z6Mu6LE7i) |
| 1392 | [Agentic Infra] 03 算力密度与Roofline model，对比 5090/M5 max/DGX spark，Qwen3-8B 算力与访存 | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agentic_rl/infra/%E6%98%BE%E5%AD%98-%E7%AE%97%E5%8A%9B-M%E8%8A%AF%E7%89%87.ipynb) | 28:31 | [link](https://www.bilibili.com/video/BV1rRYM65ENj) |
| 1393 | [Modern Agent] 01 Survey of LLM Agent Reasoning & Planning, PDDL，一些 know how | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/modern_genai_bilibili/blob/main/agents/Modern%20Agents.pptx) | 32:11 | [link](https://www.bilibili.com/video/BV1wjY5zyEki) |
| 1394 | [Modern Agent] 02 langchain/langgraph 在实现 ReAct 的差异，langsmith 监控的小 tips | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agents/langchain-graph/react_langchain_langgraph.ipynb) | 17:09 | [link](https://www.bilibili.com/video/BV1n4n7znEDN) |
| 1395 | [Modern Agent] 03 Planning Agent，Plan-Execute-RePlan 一个泛化性强的实用 Agentic Workflow | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agents/Modern%20Agents.pptx) [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agents/langchain-graph/plan-and-execute/plan-and-execute.ipynb) | 14:29 | [link](https://www.bilibili.com/video/BV1qa43z5EBJ) |
| 1396 | [AI Agent] llama_index RAG 原理及源码分析 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/rag/llama_index_basics.ipynb) | 21:58 | [link](https://www.bilibili.com/video/BV1Vm42157PL) |
| 1397 | [LangGraph] 实现 Building Effective Agents，各种 workflows 及 Agent | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/agents/langchain/advanced/building_effective_agents.ipynb) | 28:43 | [link](https://www.bilibili.com/video/BV1ZsM2zcEFa) |
| 1398 | [Agent Works] Gemini 2.5 Pro + Agent = IMO 金牌，actor-critic，生成 -> 验证 -> 修正 迭代循环 | - | AI 论文精读 | - | [github.com](https://github.com/lyang36/IMO25.git) [github.com](https://github.com/chunhuizhang/prompts_for_academic/blob/main/math/scripts/imo-gemini-sdk.py) | 24:14 | [link](https://www.bilibili.com/video/BV1Aq8bz1Emj) |
| 1399 | [Modern Agent] 04 结构化输出与工具调用，langchain / openai api / http 抓包分析 | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agents/langchain-graph/utils-features/structured_output.ipynb) [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agents/langchain-graph/utils-features/scripts/test_structure_outputs.py) | 9:30 | [link](https://www.bilibili.com/video/BV1uiUnBFED4) |
| 1400 | [Modern Agent] 05 LightRAG 知识图谱 based 的双层检索 与 LangFuse（API 监控 prompt 输入输出） | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agents/rag/lightrag/lightrag.ipynb) [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agents/tools/langfuse.ipynb) [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agents/rag/lightrag/scripts/lightrag_demo.py) | 19:50 | [link](https://www.bilibili.com/video/BV1TkmqBKEid) |
| 1401 | [Modern Agent] 07 SAM3 与 VLM，检测/识别/分割，Gemini 原生分割能力，Visual Prompting/Grounding | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/llms/%E5%A4%9A%E6%A8%A1%E6%80%81/cv/sam3-gemini.ipynb) [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/llms/%E5%A4%9A%E6%A8%A1%E6%80%81/cv/scripts/sam_agent.py) [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/llms/%E5%A4%9A%E6%A8%A1%E6%80%81/cv/seg_utils.py) | 16:50 | [link](https://www.bilibili.com/video/BV1yyqqBBEqB) |
| 1402 | [Modern Agent] 08 LightRAG 进阶，why KG-based RAG，文档 graph 如何合并，可视化 KG，Hybrid、Mix检索 | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agents/rag/lightrag/lightrag-advanced.ipynb) [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agents/rag/lightrag/scripts/lightrag_complex_demo.py) [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agents/rag/lightrag/scripts/viz_graph.py) | 11:56 | [link](https://www.bilibili.com/video/BV1Fuq2BWELU) |
| 1403 | [Modern Agent] 09 Gemini Agentic Vision，如何理解模型基础能力与 Post-Training，Gemini 3 Flash | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agents/apis/gemini/gemini-vision.ipynb) | 15:44 | [link](https://www.bilibili.com/video/BV1nU6yBfEqE) |
| 1404 | [Modern Agent] 10 多模态VLM Visual Prompting，SAM 1/2/3, Grounding DINO, Set of Mark | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agents/multi-modality/visual-prompting.ipynb) | 18:54 | [link](https://www.bilibili.com/video/BV1ebPhzBEdc) |
| 1405 | [Modern Agent] 11  Codex 初步，系统提示词注入，会话历史管理，Context Engineering，Skills / MCP 位置 | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agents/context-engineering/context-engineering-codex.ipynb) | 8:05 | [link](https://www.bilibili.com/video/BV1fyNKz5Egb) |
| 1406 | [Modern Agent] 12 Codex 中的 Skills 与 Tools 加载，Context Engineering，agent runtime | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agents/context-engineering/tool-schema-codex.ipynb) | 10:52 | [link](https://www.bilibili.com/video/BV1bSwpzNEWE) |
| 1407 | [Modern Agent] 13 Superpowers Skills，Vibe Coding 时代的软件开发圣经 | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agents/mcp-skills/skills/superpowers.ipynb) | 33:39 | [link](https://www.bilibili.com/video/BV1xswKz7EDh) |
| 1408 | [Modern Agent] 14 Codex 中的上下文压缩 compact 与 handoff / openai compact 接口提示词破解 | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agents/context-engineering/compact/compact-codex.ipynb) [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agents/context-engineering/compact/script.py) [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agents/context-engineering/compact/results.txt) | 7:48 | [link](https://www.bilibili.com/video/BV1eMAGzjEhg) |
| 1409 | [Modern Agent] 15 Codex 通用工具设计，subagents，apply_patch，exec_command，agentic vision | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agents/context-engineering/general_tool_design.ipynb) [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agents/context-engineering/files/test_response_create_6335.json) | 23:11 | [link](https://www.bilibili.com/video/BV1QUXGBXER9) |
| 1410 | [Modern Agent] 16 Claude Code 记忆（Memory）系统设计，记忆语义分类，记忆召回，记忆写入、更新与维护 | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agents/context-engineering/memory-claude-code.ipynb) | 21:38 | [link](https://www.bilibili.com/video/BV1ZA93BtEKW) |
| 1411 | [Modern Agent] 17 Codex 中的 Plan Mode 与 update_plan，plan dynamics：创建、状态更新与replan | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agents/context-engineering/plan-codex.ipynb) [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agents/context-engineering/files/test_query_wire_request_6160.json) | 14:49 | [link](https://www.bilibili.com/video/BV1NdDtBjEg7) |
| 1412 | [Modern Agent] 18 何时如何保持思维链 CoT，interleaved thinking，kvcache 利用，Qwen3.6 | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agents/apis/retain-cot.ipynb) | 21:35 | [link](https://www.bilibili.com/video/BV1Ztb969ERR) |
| 1413 | [智能的边界] gemini 2.5 deep think 初体验, parallel thinking 与 AlphaGeometry2 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/prompts_for_academic/blob/main/benchmark/0803_gemini_dp_test.ipynb) | 26:08 | [link](https://www.bilibili.com/video/BV1uyhVzUEyT) |
| 1414 | [实用的AI] paper-reading (system prompt) + gemini 2.5 pro + canvas + GEM | - | AI 论文精读 | - | - | 9:08 | [link](https://www.bilibili.com/video/BV1FqebznEWU) |
| 1415 | [实用的 AI] 科研绘图（teaser/poster），nano banana vs. GPT，nature/science 美学风格 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/prompts_for_academic/blob/main/leverage/%E7%A7%91%E7%A0%94%E7%BB%98%E5%9B%BE.ipynb) | 29:07 | [link](https://www.bilibili.com/video/BV12dHvz7Eb8) |
| 1416 | [实用 AI] Gemini 2.5 原生多模态能力，视频理解，tokens计算，youtube 视频整理成 blog | - | AI 论文精读 | - | [ai.google.dev](https://ai.google.dev/gemini-api/docs/video-understanding?hl=zh-cn) [github.com](https://github.com/chunhuizhang/prompts_for_academic/blob/main/leverage/youtube.ipynb) | 10:41 | [link](https://www.bilibili.com/video/BV1NoWszREy5) |
| 1417 | [实用 AI] GPT/Gemini 全流程参与 idea 生成，实验设计，Paper writing / AI scientist / NotebookLM | - | AI 论文精读 | - | - | 33:36 | [link](https://www.bilibili.com/video/BV1vPsZzAEbe) |
| 1418 | [实用 AI] 基于 Nano 🍌 Pro + NotebookLM 做任意资源的视觉化呈现和理解，（漫画风格）PPT 与 信息图 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/prompts_for_academic/blob/main/leverage/nano-banana-gemini3.ipynb) | 14:42 | [link](https://www.bilibili.com/video/BV1HUUTBCEnf) |
| 1419 | [智能的边界] 性能-价格帕累托前沿上的 Gemini 模型家族，断层领先的 Gemini 3 flash，以及一些绘图技巧 | - | AI 论文精读 | - | [blog.google](https://blog.google/products/gemini/gemini-3-flash/) | 6:51 | [link](https://www.bilibili.com/video/BV1SnqQBnEcM) |
| 1420 | [探索智能的边界] 喜迎 GPT Image 2，多图一致性，agentic search，thinking and generating | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agents/app/gpt-image2.ipynb) [zhuanlan.zhihu.com](https://zhuanlan.zhihu.com/p/1975730596534830124) | 11:44 | [link](https://www.bilibili.com/video/BV12NoMB3Esi) |
| 1421 | [智能的边界] 深入 GPT Pro，通用工具设计（搜索与cli），沙盒系统硬件，skills，Python环境，UV，下载限制与 tex pdf 等 | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/wdkns-skills/blob/main/skills/youtube-render-pdf/assets/notes-template.tex) [github.com](https://github.com/martinbjeldbak/ultimate-beamer-theme-list) | 19:58 | [link](https://www.bilibili.com/video/BV14xEn6DEz8) |
| 1422 | [M芯片与AI计算] 01 硬件视角下的 M5 内存带宽概念与计算，mactop，实际代码测试（MPS、Stream），魔改48GB版本4090 | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/dev/environment/m5-max-benchmark/m5-max.ipynb) [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/dev/environment/m5-max-benchmark/scripts/mps-v1.py) | 23:25 | [link](https://www.bilibili.com/video/BV1UUDDBJEn4) |
| 1423 | [M芯片与AI计算] 02 Coding Agent 时代的 MacOS 装机配置与心流体验的获得，实用 CLI 工具，rg、yazi、fzf、uv | - | AI 论文精读 | - | [yanxingliu.github.io](https://yanxingliu.github.io/posts/2026/04/useful-cli-tools/) [github.com](https://github.com/XuehaiPan/Dev-Setup) | 30:02 | [link](https://www.bilibili.com/video/BV1SrLG6oEax) |
| 1424 | [Agentic RL] 01 PG loss components，dual-clip，entropy，kl，如何自定义 pg loss | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agentic_rl/verl/objectives_loss.ipynb) | 21:59 | [link](https://www.bilibili.com/video/BV1KFpczQEkA) |
| 1425 | [Agentic RL] 02 策略梯度基础，从 PG 到 TRPO 到 PPO-Clip 核心公式简单推导 | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agentic_rl/deep_RL/pg/from_pg_to_ppo-clip.ipynb) | 15:14 | [link](https://www.bilibili.com/video/BV12NHJzTEoP) |
| 1426 | [Agentic RL] 03 策略梯度补充，GRPO loss 分析，优势标准化，On Policy | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agentic_rl/deep_RL/pg/policy_gradient.ipynb) | 23:07 | [link](https://www.bilibili.com/video/BV18hsFzbEKJ) |
| 1427 | [Agentic RL] 04 REINFORCE 4 LLM，设计 reward，如何维护和计算 PG/KL loss，KL loss 计算细节 | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agentic_rl/deep_RL/align/align_demo.ipynb) [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agentic_rl/deep_RL/scripts/reinforce_align.py) | 15:06 | [link](https://www.bilibili.com/video/BV1Ya1LB1EDM) |
| 1428 | [Agentic RL] [Inference] 05 vllm 参数配置、显存分析与性能调优 max_num_batched_tokens | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agentic_rl/inference/vllm_sglang.ipynb) [verl.readthedocs.io](https://verl.readthedocs.io/en/latest/perf/perf_tuning.html#rollout-generation-tuning) | 22:22 | [link](https://www.bilibili.com/video/BV1QnSFBkEZU) |
| 1429 | [Agentic RL] [RM] 06 DeepSeekMath-v2, 自我验证, verifier & meta verifier，验证&微调迭代 | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agentic_rl/reasoning/math/deepseekmath-v2.ipynb) | 14:28 | [link](https://www.bilibili.com/video/BV1AaSTBEEeS) |
| 1430 | [Agentic RL] 07 limits of RLVR，base vs. RL, pass@k, ppl 基于 vLLM 计算细节以及采样效率 | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agentic_rl/reasoning/rlvr.ipynb) | 24:13 | [link](https://www.bilibili.com/video/BV1pWSvBtEAk) |
| 1431 | [veRL] 从原理层面理解训练参数，PPO & GRPO，batch size，kl & entropy | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_rl/blob/main/tutorials/infra/verl/verl_config_perf.ipynb) | 25:16 | [link](https://www.bilibili.com/video/BV1DZL1zNEN2) |
| 1432 | [veRL] 核心强化学习算法，GRPO、RLOO、REINFORCE++、REINFORCE++ baseline | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_rl/blob/main/tutorials/objectives_adv/core_algo_adv.ipynb) | 21:36 | [link](https://www.bilibili.com/video/BV1d4Yvz4EXA) |
| 1433 | [veRL] FSDP SFT trainer，SFT vs. RL，交叉熵损失 / loss mask / learning rate scheduler | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_rl/blob/main/tutorials/infra/verl/verl_sft.ipynb) | 23:14 | [link](https://www.bilibili.com/video/BV1CkJgzAEAG) |
| 1434 | [veRL] fsdp sft trainer 补充，teacher forcing、shift labels shift logits、loss mask | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_rl/blob/main/tutorials/infra/verl/verl_sft_supp.ipynb) | 19:00 | [link](https://www.bilibili.com/video/BV1eWjtzbEdP) |
| 1435 | [Agentic RL] [VeRL] 08 MultiTurn Tool Use, Coding Agent SFT 训练，Cold Start for RL | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agentic_rl/verl/retool/ReTool-sft.ipynb) | 25:25 | [link](https://www.bilibili.com/video/BV19PmwB5ERd) |
| 1436 | [veRL] tokenizer 编解码的非对称性，RL 训练崩溃到 Agent loop 中的 token in token out | - | AI 论文精读 | - | - | 11:27 | [link](https://www.bilibili.com/video/BV1b2pDzYEY2) |
| 1437 | [Agentic RL] [RM] 09 Reward Model insights，理解概率建模（Bradley-Terry）、MLE、深度学习的关系 | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agentic_rl/reward_model/Bradley-Terry-RM.ipynb) | 15:04 | [link](https://www.bilibili.com/video/BV1z4vkBBEgD) |
| 1438 | [Agentic RL] 10 分布的视角理解 LLM 的 SFT 训练和 RL 训练，Forward/Reverse KL，分布与奖励 | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agentic_rl/sft_rl_fkl_rkl.ipynb) | 16:24 | [link](https://www.bilibili.com/video/BV1WvrGBGEbf) |
| 1439 | [Agentic RL] 11 重新理解 DPO，带 KL 正则的 RL 目标函数推导，隐式的奖励模型，DPO 可能的缺陷与不足 | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agentic_rl/reward_model/dpo.ipynb) | 13:52 | [link](https://www.bilibili.com/video/BV1N16ZBuERA) |
| 1440 | [Agentic RL] 12 verl infra AgentLoop 基本概念及流程，AgentLoopManager，hybrid训练与推理 | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agentic_rl/verl/agent/agent_loop_arch.ipynb) | 24:33 | [link](https://www.bilibili.com/video/BV135zrBaEEU) |
| 1441 | [Agentic RL] 13 verl infra AgentLoop 代码串讲，multi-turn 推理与 ray trainer | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agentic_rl/verl/agent/agent_loop_code.ipynb) | 16:43 | [link](https://www.bilibili.com/video/BV1MizSBJEbi) |
| 1442 | [Agentic RL] 14 verl AgentLoop 全流程与计算细节，async rollout 实现，状态机，tool / interaction | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agentic_rl/verl/agent/agent_loop_details.ipynb) | 22:04 | [link](https://www.bilibili.com/video/BV18d6sBpEZq) |
| 1443 | [Agentic RL] 15 基于 Docker 容器安装和开发 VeRL，Cursor/VSCode 远程连接 verl 容器，如同本地开发 | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/dev/docker/%E6%8C%81%E4%B9%85%E5%8C%96%E5%BC%80%E5%8F%91-verl.ipynb) | 17:12 | [link](https://www.bilibili.com/video/BV19jAzzREgW) |
| 1444 | [Agentic RL] [Env] 16 Docker容器沙盒，Jupyter Kernel 创建有状态的 CI（代码解释器）环境，实现 SWE-Vision | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agentic_rl/sandbox-env/swe-vision/swe-vision.ipynb) [unipat.ai](https://unipat.ai/blog/SWE-Vision) | 22:01 | [link](https://www.bilibili.com/video/BV15JdEBmEh9) |
| 1445 | 说说心里话 - 2024版（关于学习动力与方法，关于正反馈，关于 ai 协作） | - | AI 论文精读 | - | - | 34:16 | [link](https://www.bilibili.com/video/BV1BFrFYMEsg) |
| 1446 | [说说心里话] modern AI 入门 roadmap，RL4LLM | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/modern_ai_for_beginners) | 21:14 | [link](https://www.bilibili.com/video/BV1PrQSYSExG) |
| 1447 | [说说心里话] [2026-春] 人机协作的视角，AI 时代的学习指南与焦虑缓解 | - | AI 论文精读 | - | - | 18:24 | [link](https://www.bilibili.com/video/BV12nw4z6Eoa) |
| 1448 | [小白向-深度学习装机指南] 01 双4090 涡轮版开箱启动 vlog（gpu burn，cpu burn） | - | AI 论文精读 | - | - | 10:56 | [link](https://www.bilibili.com/video/BV1A54y1F7kN) |
| 1449 | [装机指南] 02 双卡4090 gpu-burn，cpu-burn，cuda-samples 性能测试 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/deeplearning-envs/blob/main/01_gpuburn_cpuburn_cuda_samples.ipynb) | 22:09 | [link](https://www.bilibili.com/video/BV1Kg4y1u7rZ) |
| 1450 | [性能测试] 03 单 4090 BERT、GPT2、T5 TFLOPS 测试及对比 3090TI | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/deeplearning-envs/blob/main/02_single_4090_transformers.ipynb) | 28:13 | [link](https://www.bilibili.com/video/BV1Mh41157Mc) |
| 1451 | [性能测试] 04 双4090 BERT、GPT性能测试（megatron-lm、apex、deepspeed） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/deeplearning-envs/blob/main/03_multi_4090s_transformers.ipynb) | 29:34 | [link](https://www.bilibili.com/video/BV1u24y1K7jS) |
| 1452 | [显卡环境] CUDA_VISIBLE_DEVICES 控制显卡可见性 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/deeplearning-envs/blob/main/cuda_visible_devices.ipynb) | 3:22 | [link](https://www.bilibili.com/video/BV17z4y1s7eG) |
| 1453 | [linux tools] tmux 分屏（终端复用器） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/deeplearning-envs/blob/main/tmux.ipynb) | 6:18 | [link](https://www.bilibili.com/video/BV1mu4y1B7Mp) |
| 1454 | [显卡驱动] lspci 显卡是否在槽位，显卡基本信息 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/deeplearning-envs/blob/main/%E6%98%BE%E5%8D%A1%E5%AE%89%E8%A3%85%E4%B8%8E%E9%A9%B1%E5%8A%A8%E9%97%AE%E9%A2%98.ipynb) | 5:59 | [link](https://www.bilibili.com/video/BV19Q4y1c7ia) |
| 1455 | [A100 01] A100 服务器开箱，超微平台，gpu、cpu、内存、硬盘等信息查看 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/deeplearning-envs/blob/main/A100/A100_%E5%BC%80%E7%AE%B1.ipynb) | 22:18 | [link](https://www.bilibili.com/video/BV1Yt42187NM) |
| 1456 | [A100 02] GPU 服务器压力测试，gpu burn，cpu burn，cuda samples | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/deeplearning-envs/blob/main/A100/gpuburn_cpuburn_cuda_samples.ipynb) | 15:43 | [link](https://www.bilibili.com/video/BV1wu4m1N7ET) |
| 1457 | [工具使用] tmux 会话管理及会话持久性 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/deeplearning-envs/blob/main/tmux.ipynb) | 4:23 | [link](https://www.bilibili.com/video/BV1AqHdekETT) |
| 1458 | [AI硬件科普] 内存/显存带宽，从 NVIDIA 到苹果 M4 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/deeplearning-envs/blob/main/%E7%A1%AC%E4%BB%B6/%E5%86%85%E5%AD%98.ipynb) | 8:29 | [link](https://www.bilibili.com/video/BV1Y9DAYwEvg) |
| 1459 | [内网穿透] 穿透内网gpu服务器（jupyter lab 服务），namesilo、cloudflare 托管 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/full_stack/blob/main/tutorials/%E6%9C%8D%E5%8A%A1%E5%99%A8/%E5%9F%9F%E5%90%8D-%E5%85%AC%E7%BD%91ip-cloudflare.ipynb) | 11:54 | [link](https://www.bilibili.com/video/BV1PYfpYdEPx) |
| 1460 | [硬件扫盲] GPU 核心参数及对比，4090/5090/A100/H100 M4 Max 芯片，显存带宽、算力、卡间通信 | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/dev/environment/%E7%A1%AC%E4%BB%B6%E6%8C%87%E5%8D%97/%E6%98%BE%E5%8D%A1%E6%A0%B8%E5%BF%83%E5%8F%82%E6%95%B0.ipynb) [my.feishu.cn](https://my.feishu.cn/wiki/WgaPwKSczi8P6jkRmBncEXL7nBf?from=from_copylink) | 14:28 | [link](https://www.bilibili.com/video/BV16Fr2BPEdo) |
| 1461 | [硬件扫盲] GPU 核心参数及对比，为什么显存带宽决定了LLM推理，Pro 6000 及 PPT 算力 | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/dev/environment/%E7%A1%AC%E4%BB%B6%E6%8C%87%E5%8D%97/%E6%98%BE%E5%8D%A1%E6%A0%B8%E5%BF%83%E5%8F%82%E6%95%B0.ipynb) [my.feishu.cn](https://my.feishu.cn/wiki/WgaPwKSczi8P6jkRmBncEXL7nBf?from=from_copylink) | 10:56 | [link](https://www.bilibili.com/video/BV1thrUBDEKE) |
| 1462 | [硬件扫盲] 苹果 M5 pro/max 芯片，对比 Nvidia GPU，内存带宽，统一内存，tensor core，融合架构 | - | AI 论文精读 | - | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/dev/environment/%E7%A1%AC%E4%BB%B6%E6%8C%87%E5%8D%97/apple-%E8%8A%AF%E7%89%87.ipynb) | 23:24 | [link](https://www.bilibili.com/video/BV1ZKP1zSEDB) |
| 1463 | [实用科研] 01 LLM-as-a-Judge, single 评分 vs. pair 对比，gemini 2.5 pro 原生 pdf 科研阅读 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/prompts_for_academic/blob/main/llm_as_a_judge/llm_as_a_judge.ipynb) | 20:22 | [link](https://www.bilibili.com/video/BV1TYNkzbEy7) |
| 1464 | [实用科研] 02 DeepConf，Deep Think with Confidence，如何评估一个推理过程的好坏 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_rl/blob/main/tutorials/reasoning/DeepConf.ipynb) | 16:37 | [link](https://www.bilibili.com/video/BV1yMeEzbEGd) |
| 1465 | [LLM & AIGC] 01 openai api 的简单介绍（文本生成/指令，图像生成） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/llm/tutorials/01_openai_api.ipynb) [openai.com](https://openai.com/api/) [openai.com](https://openai.com/api/pricing/) | 13:58 | [link](https://www.bilibili.com/video/BV1v24y1n7Xt) |
| 1466 | [LLM & AIGC] 02 ChatGPT api 的简单介绍（system, user, assistant）与多轮对话 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/llm/tutorials/02_chatgpt_api.ipynb) [platform.openai.com](https://platform.openai.com/docs/guides/chat/introduction?utm_medium=email&_hsmi=248356722&_hsenc=p2ANqtz---D39JbXpjnArtTGpAjkiyPnZK66ca4OF0vwyatKYqXnGNTJx5cH1yA8yeHp5CUO2hvaLXvCoLq3ATF9bjCyr9MzpSYQ&utm_content=248356722&utm_source=hs_email) | 11:56 | [link](https://www.bilibili.com/video/BV1kN411F76F) |
| 1467 | [LLM & AIGC] 03 openai  embedding （text-embedding-ada-002）基于 embedding 的文本语义匹配 | - | AI 论文精读 | - | [platform.openai.com](https://platform.openai.com/docs/guides/embeddings/what-are-embeddings) [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/llm/tutorials/03_embedding_search.ipynb) | 12:53 | [link](https://www.bilibili.com/video/BV1s84y1A73s) |
| 1468 | [LLM && AIGC] visual chatgpt 01 认识 image captioning 及 blip model | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/llm/tutorials/04_visual_chatgpt_01_image_caption.ipynb) [github.com](https://github.com/microsoft/visual-chatgpt) [kaggle.com](https://www.kaggle.com/datasets/kunalgupta2616/flickr-8k-images-with-captions) | 11:33 | [link](https://www.bilibili.com/video/BV1Jb411Z7f2) |
| 1469 | [LLM && AIGC] 04 深入理解 openai tokenizer 及 api 中的 logit_bias 与 logprobs | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/llm/tutorials/05_openai_tokenizer_logit_bias_logprobs.ipynb) [help.openai.com](https://help.openai.com/en/articles/4936856-what-are-tokens-and-how-to-count-them) | 23:24 | [link](https://www.bilibili.com/video/BV1vT411z7BB) |
| 1470 | [LLM && AIGC] 05 OpenAI 长文本（long text，超出 max_tokens）处理及 summary，划分 chunk 处理 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/llm/tutorials/06_long_text_summarize_vanilla.ipynb) [platform.openai.com](https://platform.openai.com/docs/models/gpt-3) | 15:46 | [link](https://www.bilibili.com/video/BV1WT411z7FY) |
| 1471 | [LLM && AIGC] 06 OpenAI whisper 命令行及脚本的使用（生成视频的音频） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/llm/tutorials/07_whisper.ipynb) | 15:43 | [link](https://www.bilibili.com/video/BV13h4y1W7CS) |
| 1472 | [LLM && AIGC] visual chatgpt 02 认识 Text2Image 及 stable-diffusion-v1-5 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/02_text2img.ipynb) | 10:49 | [link](https://www.bilibili.com/video/BV1M24y1c7Qp) |
| 1473 | [prompt engineering] 从 CoT 到 ToT（Tree of Thoughts） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/prompt_engineering/tot_tree_of_thought.ipynb) | 21:09 | [link](https://www.bilibili.com/video/BV1DW421c7tq) |
| 1474 | [AI Agent] Agentic Reasoning & workflow工作流，及translation-agent 一个具体的 agent 项目 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/agents/applications/translation-agent-demo.ipynb) | 18:17 | [link](https://www.bilibili.com/video/BV1rZ421K7PG) |
| 1475 | [AI Agent] function calling & tool uses 与 argument generation | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/agents/oai_function_call_rag.ipynb) | 22:38 | [link](https://www.bilibili.com/video/BV1cH4y1c7Xj) |
| 1476 | [LangChain] 01 基础入门，LCEL 、Tool Use、RAG 以及 LangSmith | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/agents/langchain/langchain_agents.ipynb) | 26:09 | [link](https://www.bilibili.com/video/BV1ax4y1s7Sk) |
| 1477 | [LangChain] 02 conversational agents，ReAct、agent_scratchpad 历史过程信息维护 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/agents/langchain/conversational_agents.ipynb) | 29:10 | [link](https://www.bilibili.com/video/BV13E421A7j6) |
| 1478 | [LangChain] 03 LangGraph 基本概念（AgentState、StateGraph，nodes，edges） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/agents/langchain/LangGraph_basics.ipynb) | 24:31 | [link](https://www.bilibili.com/video/BV1Py411q7mQ) |
| 1479 | [LangChain] 04 LangGraph 构建复杂 RAG workflow（Self-corrective） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/agents/langchain/LangGraph-rag.ipynb) | 24:22 | [link](https://www.bilibili.com/video/BV1XnsceyEit) |
| 1480 | [LangChain] 05 LangChain、LangGraph 结构化输出（Structured output），gpt-4o-2024-08-06 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/agents/langchain/structured_output.ipynb) [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/agents/langchain/output_parser.ipynb) | 23:41 | [link](https://www.bilibili.com/video/BV1sAxaeHECc) |
| 1481 | [LangChain] 06 基于LangGraph 实现 Reflexion Agent（generator vs. critic） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/agents/langchain/examples/reflexion_agent.ipynb) | 23:34 | [link](https://www.bilibili.com/video/BV1XRBBYPERJ) |
| 1482 | [OpenAI API] logprobs 与 top_logprobs 模型输出的置信度（confidence）与困惑度（PPL） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/oai/logP.ipynb) | 18:56 | [link](https://www.bilibili.com/video/BV18hqLYtE8W) |
| 1483 | [LangGraph] gemini 开源全栈 deep research 及 Anthropic multi-agent research system 导读 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/prompts_for_academic/blob/main/deepresearch/multi-agent%20research%20system.ipynb) [github.com](https://github.com/chunhuizhang/prompts_for_academic/blob/main/deepresearch/gemini_deepresearch.ipynb) | 28:06 | [link](https://www.bilibili.com/video/BV1DnKWzmEJg) |
| 1484 | [MCP] 以 sequencial thinking 为例，MCP 原理，修改源码，本地部署 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/mcp/about_mcp.ipynb) | 17:19 | [link](https://www.bilibili.com/video/BV1jLuAzGEzx) |
| 1485 | [Agentic] 一个具体的 demo 展示所谓的 Agentic Intelligence，Kimi K2，openai agent | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_rl/blob/main/tutorials/k2/agentic.ipynb) [github.com](https://github.com/chunhuizhang/llm_rl/blob/main/tutorials/k2/scripts/main.py) | 12:13 | [link](https://www.bilibili.com/video/BV1iuu9zEE6A) |
| 1486 | [LLM + MCTS] 基于 LangGraph 实现 Language Agent Tree Search （LATS） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/agents/langchain/planning/lats.ipynb) | 28:20 | [link](https://www.bilibili.com/video/BV1tohbzdEWC) |
| 1487 | [动手写bert系列] 01 huggingface tokenizer （vocab，encode，decode）原理及细节 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/tree/master/hugface) | 28:45 | [link](https://www.bilibili.com/video/BV1W34y157tA) |
| 1488 | [动手写 bert 系列] 02 tokenizer encode_plus, token_type_ids（mlm，nsp） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/tree/master/hugface) | 15:05 | [link](https://www.bilibili.com/video/BV1dZ4y1v7U3) |
| 1489 | [动手写 bert 系列] bert model architecture 模型架构初探（embedding + encoder + pooler） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/tree/master/fine_tune/bert/tutorials) | 19:01 | [link](https://www.bilibili.com/video/BV1xT411V7Ng) |
| 1490 | [动手写 bert 系列] torch.no_grad() vs. param.requires_grad == False | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/tree/master/fine_tune/bert/tutorials) [stackoverflow.com](https://stackoverflow.com/questions/63785319/pytorch-torch-no-grad-versus-requires-grad-false) | 7:54 | [link](https://www.bilibili.com/video/BV1HT41137Zw) |
| 1491 | [动手写 bert 系列] bert embedding 源码解析，word_embedding/position_embedding/token_type | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/tree/master/fine_tune/bert/tutorials) | 19:42 | [link](https://www.bilibili.com/video/BV1X94y1R7La) |
| 1492 | [动手写 bert 系列] BertTokenizer subword，wordpiece 如何处理海量数字等长尾单词 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/fine_tune/bert/tutorials/04_subword_wordpiece_tokenizer.ipynb) | 11:34 | [link](https://www.bilibili.com/video/BV1sv4y1M7aw) |
| 1493 | [动手写 bert 系列] 解析 bertmodel 的output(last_hidden_state，pooler_output，hidden_state) | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/fine_tune/bert/tutorials/05_model_outputs.ipynb) [huggingface.co](https://huggingface.co/docs/transformers/model_doc/bert#transformers.BertModel) | 13:34 | [link](https://www.bilibili.com/video/BV1Qa411D7vZ) |
| 1494 | [动手写Bert系列] bertencoder self attention 计算细节及计算过程 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/fine_tune/bert/tutorials/06_attn_01.ipynb) | 23:35 | [link](https://www.bilibili.com/video/BV14B4y1x79R) |
| 1495 | [动手写bert系列] BertSelfLayer 多头注意力机制（multi head attention）的分块矩阵实现 | - | AI 论文精读 | - | - | 13:26 | [link](https://www.bilibili.com/video/BV1pe411g7NX) |
| 1496 | [动手写 bert 系列] Bert 中的（add & norm）残差连接与残差模块（residual connections/residual blocks） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/fine_tune/bert/tutorials/07_add_norm_residual_conn.ipynb) | 12:08 | [link](https://www.bilibili.com/video/BV1VW4y1b79x) |
| 1497 | [动手写bert] bert pooler output 与 bert head | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/fine_tune/bert/tutorials/08_bert_head_pooler_output.ipynb) | 13:09 | [link](https://www.bilibili.com/video/BV1AG4y1H7wq) |
| 1498 | [动手写 bert] masking 机制、bert head 与 BertForMaskedLM | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/fine_tune/bert/tutorials/09_masked_lm.ipynb) | 24:55 | [link](https://www.bilibili.com/video/BV1Je4y1e7uF) |
| 1499 | [bert、t5、gpt] 01 fine tune transformers 文本分类/情感分析 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bert_t5_gpt/blob/main/tutorials/01_fine_tune_transformers_on_classification.ipynb) | 42:42 | [link](https://www.bilibili.com/video/BV1tM411L7HE) |
| 1500 | [[bert、t5、gpt] 02 transformer 架构 scaled dot product self attention（qkv） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bert_t5_gpt/blob/main/tutorials/02_transformer_architecture_self_attention.ipynb) | 36:24 | [link](https://www.bilibili.com/video/BV14s4y127kk) |
| 1501 | [[bert、t5、gpt] 03 AttentionHead 与 MultiHeadAttention | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bert_t5_gpt/blob/main/tutorials/03_transformer_architecture_multi_head_attention.ipynb) | 17:10 | [link](https://www.bilibili.com/video/BV14V4y1f7L2) |
| 1502 | [bert、t5、gpt] 04 构建 TransformerEncoderLayer（FFN 与 Layer Norm、skip connection） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bert_t5_gpt/blob/main/tutorials/04_ffn_layer_norm_skip_conn.ipynb) | 17:18 | [link](https://www.bilibili.com/video/BV1XX4y1B71n) |
| 1503 | [bert、t5、gpt] 05 构建 TransformerDecoderLayer（FFN 与 Masked MultiHeadAttention） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bert_t5_gpt/blob/main/tutorials/05_transformer_decoder_layer.ipynb) | 19:45 | [link](https://www.bilibili.com/video/BV1Ch4y1n7jZ) |
| 1504 | [bert、t5、gpt] 06 GPT2 整体介绍（tokenizer，model forward） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bert_t5_gpt/blob/main/tutorials/06_gpt2_overall.ipynb) | 31:25 | [link](https://www.bilibili.com/video/BV1hL41187Pw) |
| 1505 | [bert、t5、gpt] 07 GPT2 decoding （greedy search, beam search） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bert_t5_gpt/blob/main/tutorials/07_gpt2_decoding(generation) | 29:44 | [link](https://www.bilibili.com/video/BV1aa4y1G7p9) |
| 1506 | [bert、t5、gpt] 08 GPT2 sampling （top-k，top-p （nucleus sampling）） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bert_t5_gpt/blob/main/tutorials/08_gpt2_decoding_sampling.ipynb) | 21:37 | [link](https://www.bilibili.com/video/BV1Ho4y1x76q) |
| 1507 | [bert、t5、gpt] 09 T5 整体介绍（t5-11b，T5ForConditionalGeneration） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bert_t5_gpt/blob/main/tutorials/09_t5_overall.ipynb) | 20:29 | [link](https://www.bilibili.com/video/BV1Lh4y1b74i) |
| 1508 | [bert、t5、gpt] 10 知识蒸馏（knowledge distill）初步，模型结构及损失函数设计 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bert_t5_gpt/blob/main/tutorials/11_knowledge_distillation_basics.ipynb) | 11:45 | [link](https://www.bilibili.com/video/BV1Do4y1A7EN) |
| 1509 | [bert、t5、gpt] 11 知识蒸馏（knowledge distill）huggingface trainer pipeline | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bert_t5_gpt/blob/main/tutorials/13_kd_pipeline.ipynb) | 15:15 | [link](https://www.bilibili.com/video/BV16V4y18733) |
| 1510 | [BERT 番外] Sin Position Encoding 的简洁实现（RoPE 基础） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bert_t5_gpt/blob/main/tutorials/sin_position_encoding.ipynb) | 6:13 | [link](https://www.bilibili.com/video/BV1KN411p73o) |
| 1511 | [GPT 番外] tied/share tensors wte与lm_head（GPT2LMHeadModel） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bert_t5_gpt/blob/main/tutorials/tied_shared_tensors_lm_head_token_embedding.ipynb) | 8:09 | [link](https://www.bilibili.com/video/BV1ec411971a) |
| 1512 | [sbert 01] sentence-transformers pipeline | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bert_t5_gpt/blob/main/tutorials/sbert-tutorials/sentence-transformers-pipeline.ipynb) | 24:01 | [link](https://www.bilibili.com/video/BV1sK421C7oG) |
| 1513 | [sbert 02] sbert 前向及损失函数pooling method计算细节 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bert_t5_gpt/blob/main/tutorials/sbert-tutorials/sbert_%E6%BA%90%E7%A0%81%E5%88%86%E6%9E%90.ipynb) | 15:05 | [link](https://www.bilibili.com/video/BV1S6421u7jA) |
| 1514 | [LLM 番外] 自回归语言模型cross entropy loss，及 PPL 评估 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bert_t5_gpt/blob/main/tutorials/ar_lm_loss_PPL-perplexity.ipynb) | 9:18 | [link](https://www.bilibili.com/video/BV1ZA4m1w7D5) |
| 1515 | [gpt2 番外] training vs. inference（generate），PPL 计算，交叉熵损失与 ignore_index | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bert_t5_gpt/blob/main/tutorials/gpt2_training_inference_ppl.ipynb) | 17:49 | [link](https://www.bilibili.com/video/BV1ox4y147o1) |
| 1516 | [LLM 原理] 高效推理 Speculative Decoding 投机探测采样 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_rl/blob/main/tutorials/infra/flashinfer/speculative_decoding.ipynb) | 7:39 | [link](https://www.bilibili.com/video/BV1Vt3QzLEQ1) |
| 1517 | [LLM+RL] 合成数据与model collapse，nature 正刊封面 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_rl/blob/main/tutorials/garbage_out.ipynb) | 16:11 | [link](https://www.bilibili.com/video/BV18JyaYxEGi) |
| 1518 | [LLM+RL] 基于开源 LLM 实现 O1-like step by step 慢思考（slow thinking），ollama，streamlit | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_rl/blob/main/tutorials/reasoning/ollama_reasoning.ipynb) | 12:33 | [link](https://www.bilibili.com/video/BV1ZsBjY5EBb) |
| 1519 | [LLM+RL] model.generate 之 beam search decoding strategy | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_rl/blob/main/tutorials/search-learn/llm_beam_search.ipynb) | 11:47 | [link](https://www.bilibili.com/video/BV1SbrKYkETg) |
| 1520 | [LLM + RL] kimi 1.5 论文导读与 highlights | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_rl/blob/main/tutorials/r1-k1.5/k1.5.ipynb) | 42:54 | [link](https://www.bilibili.com/video/BV1RXNDeMEin) |
| 1521 | [LLM+RL] R1 论文导读，SFT vs. RL，RL 基础以及 GRPO 细节，以及一系列复现工作讨论 | - | AI 论文精读 | - | - | 57:59 | [link](https://www.bilibili.com/video/BV15yA3eWE5b) |
| 1522 | [LLM+RL] 理解 GRPO 公式原理及 TRL GrpoTrainer 代码实现（advantage 与 loss 计算） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_rl/blob/main/tutorials/r1-k1.5/trl_grpo.ipynb) | 48:42 | [link](https://www.bilibili.com/video/BV1pXA5eyEEg) |
| 1523 | [LLM+RL] GRPO 中的 KL div（散度），reverse vs. forward，以及无偏估计（Schulman） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_rl/blob/main/tutorials/r1-k1.5/grpo_kl.ipynb) | 12:06 | [link](https://www.bilibili.com/video/BV1rsAXe7EZs) |
| 1524 | [RL4LLM] 理解 reasoning model Tokenizer 的 chat template，vllm inference | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_rl/blob/main/tutorials/r1-k1.5/reasoning_model_chat_template_and_inference.ipynb) | 23:44 | [link](https://www.bilibili.com/video/BV1LKXSYqE3T) |
| 1525 | [RL4LLM] PPO workflow 及 OpenRLHF、veRL 初步介绍，ray distributed debugger | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_rl/blob/main/tutorials/r1-k1.5/infra/overall_basics.ipynb) | 24:13 | [link](https://www.bilibili.com/video/BV1Pz9tYbEeZ) |
| 1526 | [RL4LLM] 深入 PPO-clip 目标函数细节（及重要性采样） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_rl/blob/main/tutorials/basics_insights_of_RL/importance_sampling.ipynb) [github.com](https://github.com/chunhuizhang/llm_rl/blob/main/tutorials/basics_insights_of_RL/PPO_clip.ipynb) | 24:23 | [link](https://www.bilibili.com/video/BV1y1R4YbE1E) |
| 1527 | [RL4LLM] GRPO loss/objective 分析 及可能的 biases 分析（DAPO，Dr. GRPO) | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_rl/blob/main/tutorials/r1-k1.5/grpo_loss.ipynb) | 19:05 | [link](https://www.bilibili.com/video/BV1LgXbY5EFD) |
| 1528 | [RL4LLM] deepseek v3 工具调用的 bug 以及理解 chat_template 的 function calling | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_rl/blob/main/tutorials/tokenizer/v3.ipynb) | 14:17 | [link](https://www.bilibili.com/video/BV1dsdWYuEXw) |
| 1529 | [veRL] 性能优化 use_remove_padding （flash attn varlen）变长序列处理 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_rl/blob/main/tutorials/infra/verl/verl_packing.ipynb) [verl.readthedocs.io](https://verl.readthedocs.io/en/latest/perf/perf_tuning.html) | 24:00 | [link](https://www.bilibili.com/video/BV1ZqdaYAEzA) |
| 1530 | [veRL] log probs from logits 与 entropy from logits 的高效计算 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_rl/blob/main/tutorials/infra/verl/log_probs_from_logits.ipynb) | 10:18 | [link](https://www.bilibili.com/video/BV1iedzYEEV4) |
| 1531 | [RL4LLM] base vs. instruct model，个性化（custom）chat template（make prefix） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_rl/blob/main/tutorials/tokenizer/base_instruct.ipynb) [github.com](https://github.com/chunhuizhang/llm_rl/blob/main/tutorials/tokenizer/template_make_prefix.ipynb) | 21:38 | [link](https://www.bilibili.com/video/BV1JZLcz4EUC) |
| 1532 | [RL insights] 深入理解 Policy Gradient 算法（REINFORCE, Actor-Critic, A2C），打开强化学习算法的总钥匙 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/modern_ai_for_beginners/blob/main/books_reading_notes/RL/%E5%BC%BA%E5%8C%96%E5%AD%A6%E4%B9%A0%E7%9A%84%E6%95%B0%E5%AD%A6%E5%8E%9F%E7%90%86.ipynb) | 35:15 | [link](https://www.bilibili.com/video/BV1i8TQzuEKs) |
| 1533 | [RL insights] 推导和理解 Policy Gradient 算法，PG vs. MLE/SFT，采样及训练过程 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_rl/blob/main/tutorials/basics_insights_of_RL/pg.ipynb) | 17:21 | [link](https://www.bilibili.com/video/BV1UzgozEEFA) |
| 1534 | [五分钟系列] 01 gensim embedding vectors 距离及可视化分析 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bert_t5_gpt/blob/main/tutorials/embedding_visualize_analysis.ipynb) | 6:59 | [link](https://www.bilibili.com/video/BV1Zs4y1r7mg) |
| 1535 | [工具的使用] 从 jupyter notebook 到 jupyter lab（网页版 vscode？） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/full_stack/blob/main/tutorials/%E7%8E%AF%E5%A2%83%E5%8F%8A%E4%BE%9D%E8%B5%96/pip_jupyter.ipynb) | 8:03 | [link](https://www.bilibili.com/video/BV1Qt421G74s) |
| 1536 | [五分钟快谈] GPT Canvas 从 notebook 到 python 文件 | - | AI 论文精读 | - | - | 3:57 | [link](https://www.bilibili.com/video/BV1whqDYLETt) |
| 1537 | [实用 AI 工具] gemini-cli 尝鲜，命令行中的Agent，（mcp servers） | - | AI 论文精读 | - | - | 6:47 | [link](https://www.bilibili.com/video/BV13LKyzkEhu) |
| 1538 | [pytorch distributed] 01 nn.DataParallel 数据并行初步 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/pytorch_distribute_tutorials/blob/main/tutorials/01_multi_gpus_data_parallelism.ipynb) | 15:34 | [link](https://www.bilibili.com/video/BV1jm4y187tM) |
| 1539 | [pytorch distributed] 02 DDP 基本概念（Ring AllReduce，node，world，rank，参数服务器） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/pytorch_distribute_tutorials/blob/main/tutorials/02_ddp_basics.ipynb) | 15:28 | [link](https://www.bilibili.com/video/BV1Uo4y1K7wM) |
| 1540 | [pytorch distributed] 03 DDP 初步应用（Trainer，torchrun） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/pytorch_distribute_tutorials/blob/main/tutorials/03_ddp_toy_example.ipynb) [github.com](https://github.com/chunhuizhang/pytorch_distribute_tutorials/blob/main/tutorials/ddp_gpus.py) [github.com](https://github.com/chunhuizhang/pytorch_distribute_tutorials/blob/main/tutorials/ddp_gpus_torchrun.py) | 18:41 | [link](https://www.bilibili.com/video/BV13L411i7Ls) |
| 1541 | [pytorch distributed] 04 模型并行（model parallel）on ResNet50 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/pytorch_distribute_tutorials/blob/main/tutorials/04_model_parallel_resnet50.ipynb) | 21:01 | [link](https://www.bilibili.com/video/BV15h4y1V7xe) |
| 1542 | [pytorch distributed] 05 张量并行（tensor parallel），分块矩阵的角度，作用在 FFN 以及 Attention 上 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/pytorch_distribute_tutorials/blob/main/tutorials/tensor_parallel.ipynb) | 18:38 | [link](https://www.bilibili.com/video/BV1Jy4y1A76p) |
| 1543 | [pytorch distributed] torch 分布式基础（process group），点对点通信，集合通信 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/pytorch_distribute_tutorials/blob/main/tutorials/torch_distributed_basics.ipynb) [github.com](https://github.com/chunhuizhang/pytorch_distribute_tutorials/blob/main/tutorials/torch_dist.py) | 15:51 | [link](https://www.bilibili.com/video/BV1t2421F7zY) |
| 1544 | [pytorch distributed] nccl 集合通信（collective communication） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/pytorch_distribute_tutorials/blob/main/tutorials/torch_nccl_collective_communication.ipynb) [github.com](https://github.com/chunhuizhang/pytorch_distribute_tutorials/blob/main/tutorials/torch_nccl_test.py) | 15:24 | [link](https://www.bilibili.com/video/BV1zK42187Kv) |
| 1545 | [pytorch distributed] amp 原理，automatic mixed precision 自动混合精度 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/pytorch_distribute_tutorials/blob/main/tutorials/amp_autocast_mixed_precision_training.ipynb) | 17:49 | [link](https://www.bilibili.com/video/BV1eW421w7NJ) |
| 1546 | [pytorch distributed] deepspeed 基本概念、原理（os+g+p） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/pytorch_distribute_tutorials/blob/main/tutorials/deepspeed_accelerate/deepspeed_basics.ipynb) | 20:47 | [link](https://www.bilibili.com/video/BV1rZ42187PA) |
| 1547 | [pytorch distributed] accelerate 基本用法（config，launch）数据并行 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/pytorch_distribute_tutorials/blob/main/tutorials/deepspeed_accelerate/accelerate_config.ipynb) | 14:12 | [link](https://www.bilibili.com/video/BV1jS411K72E) |
| 1548 | [QKV attention] kv-cache、decoder only vs. BERT, 单向注意力 vs. 双向注意力 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/pytorch_distribute_tutorials/blob/main/tutorials/kv-cache.ipynb) | 14:58 | [link](https://www.bilibili.com/video/BV1sw4m1v7sa) |
| 1549 | [pytorch distributed] 从 DDP、模型并行、流水线并行到 FSDP（NCCL，deepspeed 与 Accelerate） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/pytorch_distribute_tutorials/blob/main/tutorials/FSDP.ipynb) | 30:28 | [link](https://www.bilibili.com/video/BV1Kx4y187Te) |
| 1550 | [QKV attention] flash attention（Tiling与重计算），operation fused，HBM vs. SRAM | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bert_t5_gpt/blob/main/tutorials/attention/flash_attn.ipynb) | 33:59 | [link](https://www.bilibili.com/video/BV1DW421R7CA) |
| 1551 | [pytorch distributed] 张量并行与 megtron-lm 及 accelerate 配置 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/pytorch_distribute_tutorials/blob/main/tutorials/deepspeed_accelerate/megtron_lm.ipynb) | 20:14 | [link](https://www.bilibili.com/video/BV1TsWoe4E22) |
| 1552 | [pytorch 加速] CPU传输 & GPU计算的并行（pin_memory，non_blocking） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/nn_basics/performance_optimization/pytorch_optimization.ipynb) | 8:54 | [link](https://www.bilibili.com/video/BV15Xxve1EtZ) |
| 1553 | [Pytorch 分布式] ring-allreduce 算法（scatter-reduce、allgather）以及 FSDP | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/pytorch_distribute_tutorials/blob/main/tutorials/3D-parallel/ring-allreduce.ipynb) | 20:10 | [link](https://www.bilibili.com/video/BV1biLHzAEzv) |
| 1554 | [Pytorch 分布式] DeepSpeed Ulysses 分布式序列并行算法，尤利西斯，Ring attention | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/pytorch_distribute_tutorials/blob/main/tutorials/3D-parallel/SP-%E5%BA%8F%E5%88%97%E5%B9%B6%E8%A1%8C.ipynb) | 16:01 | [link](https://www.bilibili.com/video/BV1tsVZzbEXh) |
| 1555 | [LLMs inference] quantization 量化整体介绍（bitsandbytes、GPTQ、GGUF、AWQ） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_inference_serving/blob/main/tutorials/quantization/qlora_gptq_gguf_awq.ipynb) [github.com](https://github.com/chunhuizhang/llm_inference_serving/blob/main/tutorials/quantization/basics.ipynb) | 23:12 | [link](https://www.bilibili.com/video/BV1FH4y1c73W) |
| 1556 | [LLMs inference] hf transformers 中的 KV cache | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_inference_serving/blob/main/tutorials/cache/use_cache_past_key_values.ipynb) | 14:05 | [link](https://www.bilibili.com/video/BV1VpU6YcEuS) |
| 1557 | [LLMs serving] openrouter & vllm host LLM 推理服务，openai api 兼容 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/ai_app/openrouter.ipynb) [github.com](https://github.com/chunhuizhang/llm_inference_serving/blob/main/tutorials/vllm/hosting_OpenAI-Compatible%20Server.ipynb) | 13:22 | [link](https://www.bilibili.com/video/BV17FccedE8s) |
| 1558 | [LLMs inference] vllm & sglang offline inference，tensor parallel vs. data parall | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_rl/tree/main/tutorials/infra/inference/scripts) | 26:53 | [link](https://www.bilibili.com/video/BV1jGXHYfEdx) |
| 1559 | [stable diffusion] 01 本地安装及环境配置（diffusers, StableDiffusionPipeline, text2image） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/diffusion/tutorials/01_tut.ipynb) | 15:10 | [link](https://www.bilibili.com/video/BV1BV4y137bA) |
| 1560 | [diffusion] 生成模型基础 VAE 原理及实现 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/diffusion_models_tutorials/blob/main/tutorials/Variational_Autoencoders.ipynb) | 27:30 | [link](https://www.bilibili.com/video/BV1QC4y1A7Gs) |
| 1561 | [generative models] 概率建模视角下的现代生成模型（生成式 vs. 判别式，采样与密度估计） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/generative_models_tutorials/blob/main/tutorials/%E6%A6%82%E7%8E%87%E5%BB%BA%E6%A8%A1%E8%A7%86%E8%A7%92%E4%B8%8B%E7%9A%84%E7%94%9F%E6%88%90%E6%A8%A1%E5%9E%8B_cdf_sampling_kde.ipynb) | 18:38 | [link](https://www.bilibili.com/video/BV1bi421v75t) |
| 1562 | [VAE] VAE 核心concepts、概率建模思维及 latent space 可视化 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/diffusion_models_tutorials/blob/main/tutorials/vae/vae_latent_space.ipynb) | 19:37 | [link](https://www.bilibili.com/video/BV1r3w6eyEys) |
| 1563 | [纳什荐书][生成式AI] 01 《GPT图解》导读 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/modern_ai_for_beginners/tree/main/books_reading_notes) [github.com](https://github.com/chunhuizhang/modern_ai_for_beginners) | 11:18 | [link](https://www.bilibili.com/video/BV1BT421S7rb) |
| 1564 | [纳什荐书][强化学习] chap2 MDP（马尔可夫决策过程），最优策略与最优状态价值 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/modern_ai_for_beginners/blob/main/books_reading_notes/%E6%B7%B1%E5%BA%A6%E5%AD%A6%E4%B9%A0%E5%85%A5%E9%97%A8/%E5%BC%BA%E5%8C%96%E5%AD%A6%E4%B9%A0/chap2_mdp.ipynb) | 27:21 | [link](https://www.bilibili.com/video/BV1Hb6WYkEHd) |
| 1565 | [动手写神经网络] 如何设计卷积核（conv kernel）实现降2采样，以及初探vggnet/resnet 卷积设计思路（不断降空间尺度，升channel） | - | AI 论文精读 | - | [pytorch.org](https://pytorch.org/docs/stable/generated/torch.nn.Conv2d.html) [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/learn_torch/utils/vgg_hook.py) | 7:23 | [link](https://www.bilibili.com/video/BV1dF411P7Fk) |
| 1566 | [动手写神经网络] 如何对数据集归一化（transforms.Normalize）以 mnist 数据集为例（mean=0.1307, std=0.3081） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/dl/normalize/mnist_demo.py) [stackoverflow.com](https://stackoverflow.com/questions/63746182/correct-way-of-normalizing-and-scaling-the-mnist-dataset) | 9:29 | [link](https://www.bilibili.com/video/BV12K411f76T) |
| 1567 | [动手写神经网络] 如何对数据集（ImageNet） denormalize（inverse normalize）还原为原来的均值和标准差（mean/std） | - | AI 论文精读 | - | - | 5:10 | [link](https://www.bilibili.com/video/BV1og411m7cc) |
| 1568 | [动手写神经网络] 01 认识 pytorch 中的 dataset、dataloader（mnist、fashionmnist、cifar10） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/dl/tutorials/01_torch_dataset_dataloader.ipynb) | 24:09 | [link](https://www.bilibili.com/video/BV18y4y1Q7Jy) |
| 1569 | 【深度学习环境搭建】01 本机、GPU服务器端深度学习环境搭建（代码、数据共享） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/dl/tutorials/03_rnn_on_images.py) | 9:03 | [link](https://www.bilibili.com/video/BV1G14y1c7Sw) |
| 1570 | 【深度学习环境搭建】02 gpu 服务器端部署 jupyter notebook server | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/dl/tutorials/test_jupyter_notebook.ipynb) | 8:13 | [link](https://www.bilibili.com/video/BV1Ye4y1P7bw) |
| 1571 | [动手写神经网络] 02 逐行写代码 CNN pipeline 图像分类（模型结构、训练、评估） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/dl/tutorials/02_cnn_on_mnist.ipynb) | 31:37 | [link](https://www.bilibili.com/video/BV1954y1N7bh) |
| 1572 | [动手写神经网络] 03 自定义 CNN 模型适配新的数据集 CIFAR10（适配+简单调参） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/dl/tutorials/03_cnn_on_cifar10.ipynb) | 13:23 | [link](https://www.bilibili.com/video/BV1js4y1a77W) |
| 1573 | [动手写神经网络] 04 使用预训练 vgg 提升 cifar10 分类准确率 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/dl/tutorials/04_vgg_on_cifar10.ipynb) | 18:55 | [link](https://www.bilibili.com/video/BV1Z54y1F77T) |
| 1574 | [动手写神经网络] 05 使用预训练 resnet18 提升 cifar10 分类准确率及误分类图像可视化分析 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/dl/tutorials/05_resnet_on_cifar10.ipynb) | 25:34 | [link](https://www.bilibili.com/video/BV1xj411g796) |
| 1575 | [动手写神经网络] 06 自定义（kaggle）数据集（custom dataset）、Dataloader，及 train test valid 数据集拆分 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/dl/tutorials/06_custom_dataset_train_valid_test.ipynb) | 22:56 | [link](https://www.bilibili.com/video/BV1z84y1P79Q) |
| 1576 | [动手写神经网络] 07 预训练 resnet 解决 kaggle weather dataset（validation dataset）的使用 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/dl/tutorials/07_resnet_on_weather_validation_data.ipynb) | 18:32 | [link](https://www.bilibili.com/video/BV1Cs4y1578z) |
| 1577 | [动手写神经网络] 08 WandB（weights & biases）深度学习调参利器 | - | AI 论文精读 | - | [wandb.ai](https://wandb.ai/site/articles/intro-to-pytorch-with-wandb) [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/nn_basics/01_pytorch_wandb.ipynb) | 19:34 | [link](https://www.bilibili.com/video/BV1qs4y1A7qq) |
| 1578 | [动手写神经网络] 可微才可学，深度学习框架自动微分计算图（DAG） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/nn_basics/grad/%E5%8F%AF%E5%BE%AE%E6%89%8D%E5%8F%AF%E5%AD%A6.ipynb) | 17:34 | [link](https://www.bilibili.com/video/BV1gMC9YJEiX) |
| 1579 | [动手写神经网络] 手动实现 Transformer Encoder | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bert_t5_gpt/blob/main/tutorials/encoder-decoder/transformer-encoder-decoder.ipynb) | 21:24 | [link](https://www.bilibili.com/video/BV1cZ1xYFEFx) |
| 1580 | [动手写 Transformer] 从 RNN 到 Transformer，为什么需要位置编码（position encoding） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bert_t5_gpt/blob/main/tutorials/encoder-decoder/bow_wo_pe.ipynb) | 10:59 | [link](https://www.bilibili.com/video/BV1zRSqYvEjC) |
| 1581 | [动手写神经网络] pytorch 高维张量 Tensor 维度操作与处理，einops | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bert_t5_gpt/blob/main/tutorials/encoder-decoder/reshape_permute_einsum.ipynb) | 23:03 | [link](https://www.bilibili.com/video/BV173DrY5EAL) |
| 1582 | [动手写 Transformer] 手动实现 Transformer Decoder（交叉注意力，encoder-decoder cross attentio） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bert_t5_gpt/blob/main/tutorials/encoder-decoder/transformer-encoder-decoder.ipynb) | 14:43 | [link](https://www.bilibili.com/video/BV1ZqUaYmEkq) |
| 1583 | [动手写神经网络] kSparse AutoEncoder 稀疏性激活的显示实现（SAE on LLM） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/dnn/ae/ksparse-ae.py) [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/dnn/ae/ksparse-ae.ipynb) | 16:22 | [link](https://www.bilibili.com/video/BV15JCrYWEDQ) |
| 1584 | [蒙特卡洛方法] 01 从黎曼和式积分（Reimann Sum）到蒙特卡洛估计（monte carlo estimation）求积分求期望 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/rl/montecarlo/01_monte_carlo_estimation.ipynb) [en.wikipedia.org](https://en.wikipedia.org/wiki/Monte_Carlo_integration) | 15:22 | [link](https://www.bilibili.com/video/BV1Hm4y1z7bP) |
| 1585 | [蒙特卡洛方法] 02 重要性采样（importance sampling）及 python 实现 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/deeplearning_math/blob/main/tutorials/montecarlo/importance_sampling.ipynb) | 9:04 | [link](https://www.bilibili.com/video/BV1SV4y1i7bW) |
| 1586 | [蒙特卡洛方法] 03 接受/拒绝采样（accept/reject samping）初步 cases 分析 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/deeplearning_math/blob/main/tutorials/montecarlo/rejection_sampling_01_cases.ipynb) | 10:50 | [link](https://www.bilibili.com/video/BV1Tm4y1N7hU) |
| 1587 | [蒙特卡洛方法] 04 重要性采样补充，数学性质及 On-policy vs. Off-policy | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/deeplearning_math/blob/main/tutorials/montecarlo/importance_sampling_2.ipynb) | 14:01 | [link](https://www.bilibili.com/video/BV1Vr421u7Qz) |
| 1588 | [蒙特卡洛方法] 05 接受拒绝采样框架、原理推导与分析（MCMC 基础） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/deeplearning_math/blob/main/tutorials/montecarlo/accept-reject/formulate.ipynb) [github.com](https://github.com/chunhuizhang/deeplearning_math/blob/main/tutorials/montecarlo/accept-reject/practices.ipynb) | 11:00 | [link](https://www.bilibili.com/video/BV1RKkbYSEoS) |
| 1589 | [蒙特卡洛方法] 06 马尔可夫链（Markov Chain）与稳态分布和细致平稳条件（detailed balance） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/deeplearning_math/blob/main/tutorials/montecarlo/mcmc/Markov-Chain.ipynb) | 14:39 | [link](https://www.bilibili.com/video/BV1SYkqYPE1s) |
| 1590 | [手推公式] sigmoid 及其导数 softmax 及其导数性质（从 logits 到 probabilities） | - | AI 论文精读 | - | - | 10:25 | [link](https://www.bilibili.com/video/BV14v4y137Sv) |
| 1591 | 【手推公式】从 logodds 到 sigmoid 概率化输出，用于 LR、XGBoost 的分类任务 | - | AI 论文精读 | - | - | 4:37 | [link](https://www.bilibili.com/video/BV1fA411v7xj) |
| 1592 | 【手推公式】odds（几率）与对数几率（logodds）在logistics regression及xgboost classification中的应用 | - | AI 论文精读 | - | - | 21:00 | [link](https://www.bilibili.com/video/BV1rp4y1D74F) |
| 1593 | 【手推公式】指数族分布（exponential family distribution），伯努利分布及高斯分布的推导 | - | AI 论文精读 | - | - | 10:13 | [link](https://www.bilibili.com/video/BV1Cg4y1q7jW) |
| 1594 | 【手推公式】从二分类（二项分布）到多分类（多项分布），最大似然估计与交叉熵损失的等价 | - | AI 论文精读 | - | - | 12:59 | [link](https://www.bilibili.com/video/BV1a5411W7Dn) |
| 1595 | 【机器学习】【手推公式】从Hinge loss（合页损失）到 SVM（hard margin/soft margin） | - | AI 论文精读 | - | - | 9:47 | [link](https://www.bilibili.com/video/BV1ai4y1x7LN) |
| 1596 | 【手推公式】xgboost自定义损失函数（cross entropy/squared log loss）及其一阶导数gradient二阶导数hessian | - | AI 论文精读 | - | - | 10:12 | [link](https://www.bilibili.com/video/BV12i4y1s7nj) |
| 1597 | 【手推公式】multi-classification多分类评估（precision/recall，micro averaging与macro averaging | - | AI 论文精读 | - | - | 16:20 | [link](https://www.bilibili.com/video/BV1Ji4y147F9) |
| 1598 | 【手推公式】【销量预测】【回归分析】MAE与MSE在回归分析时的区别，为什么MSE倾向于回归均值，MAE倾向于回归中位数 | - | AI 论文精读 | - | - | 6:40 | [link](https://www.bilibili.com/video/BV13z4y1d7CA) |
| 1599 | 【手推公式】【目标检测】【Fast RCNN】RoIPooling 的作用及计算 | - | AI 论文精读 | - | - | 12:55 | [link](https://www.bilibili.com/video/BV1sz4y1R7go) |
| 1600 | 【数学分析】泰勒级数（Taylor series）展开的本质（多项式逼近）多项式系数的推导 | - | AI 论文精读 | - | - | 10:23 | [link](https://www.bilibili.com/video/BV1Fr4y1A7ei) |
| 1601 | [AI 核心概念及计算] 优化 01 梯度下降（gradient descent）与梯度上升（gradient ascent）细节及可视化分析 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/ml_core/tutorials/01_grad_descent_details_visualization.ipynb) [realpython.com](https://realpython.com/gradient-descent-algorithm-python/#momentum-in-stochastic-gradient-descent) | 16:17 | [link](https://www.bilibili.com/video/BV1sc41157fk) |
| 1602 | [AI 核心概念及计算] 概率计算 01 pytorch 最大似然估计（MLE）伯努利分布的参数 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/ml_core/tutorials/02_pytorch_mle_for_bernoulli.ipynb) | 12:35 | [link](https://www.bilibili.com/video/BV15s4y1S7aZ) |
| 1603 | 【矩阵分析】从特征值特征向量到矩阵SVD奇异值分解（np.linalg.svd） | - | AI 论文精读 | - | - | 12:03 | [link](https://www.bilibili.com/video/BV1u54y12766) |
| 1604 | [矩阵分析] LoRA 矩阵分析基础之 SVD low rank approximation（低秩逼近） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/supplement_01_svd.ipynb) | 11:09 | [link](https://www.bilibili.com/video/BV1Jg4y1c7dh) |
| 1605 | [数学！数学] 最大似然估计（MLE）与最小化交叉熵损失（cross entropy loss）的等价性 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/deeplearning_math/blob/main/tutorials/01_cross_entropy_mle.ipynb) | 11:38 | [link](https://www.bilibili.com/video/BV19k4y1M7cJ) |
| 1606 | [pytorch optim] 优化器相关 - learning rate scheduler | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/nn_basics/optimizer/lr_scheduler.ipynb) | 13:25 | [link](https://www.bilibili.com/video/BV1oP411z7bv) |
| 1607 | [矩阵分析] 从向量范数到矩阵范数、torch spectral norm（矩阵的谱范数） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/deeplearning_math/blob/main/tutorials/matrix/Lp_norm_matrix_norm.ipynb) [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/nn_basics/spectral_norm.ipynb) | 10:07 | [link](https://www.bilibili.com/video/BV1JN411h7qU) |
| 1608 | [pytorch optim] 优化器相关 AdaGrad（adaptive gradient） 与 RMSprop，自适应梯度 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/nn_basics/optimizer/adagrad_rmsprop.ipynb) | 15:36 | [link](https://www.bilibili.com/video/BV1294y1C7S4) |
| 1609 | 【矩阵分析】二维旋转矩阵的推导（极坐标/基变换） | - | AI 论文精读 | - | [scipython.com](https://scipython.com/book/chapter-6-numpy/examples/creating-a-rotation-matrix-in-numpy/) | 10:10 | [link](https://www.bilibili.com/video/BV17Y4y1Y7Ss) |
| 1610 | [矩阵分析] 旋转矩阵的计算机与应用（复平面，RoPE） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/deeplearning_math/blob/main/tutorials/matrix/%E6%97%8B%E8%BD%AC%E7%9F%A9%E9%98%B5%EF%BC%88rotation%20matrix%EF%BC%89.ipynb) | 9:09 | [link](https://www.bilibili.com/video/BV1pw411D7nP) |
| 1611 | [概率 & 统计] kl div kl散度的计算及应用（pytorch） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/deeplearning_math/blob/main/tutorials/prob_stats/kl_div_basics.ipynb) [github.com](https://github.com/chunhuizhang/deeplearning_math/blob/main/tutorials/prob_stats/pytorch_kl_div_examples.ipynb) | 11:59 | [link](https://www.bilibili.com/video/BV1JG411o7GV) |
| 1612 | [多元变量微分] 方向导数与梯度下降方法（directional derivatives） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/deeplearning_math/blob/main/tutorials/calculus/derivative_partial_directional.ipynb) | 9:03 | [link](https://www.bilibili.com/video/BV1n94y1G7Jx) |
| 1613 | [凸函数] convex 性质与简森不等式（jensen's inequality）与 ELBO、投资组合理论（Porfolio） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/deeplearning_math/blob/main/tutorials/calculus/convex_function_jensen_inequality.ipynb) | 9:25 | [link](https://www.bilibili.com/video/BV1Lu4y1P7e5) |
| 1614 | [统计] python 假设检验基础（T-Test，ANOVA，chi2） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/deeplearning_math/blob/main/tutorials/prob_stats/stats/%E5%81%87%E8%AE%BE%E6%A3%80%E9%AA%8C.ipynb) | 12:40 | [link](https://www.bilibili.com/video/BV1NQ4y1t79i) |
| 1615 | [机器学习理论] 霍夫丁不等式（hoeffding's inequality）到 UCB | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/deeplearning_math/blob/main/tutorials/prob_stats/hoeffding's_inequality.ipynb) | 7:51 | [link](https://www.bilibili.com/video/BV1xe411k7V1) |
| 1616 | [概率 & 统计] Thompson Sampling（随机贝叶斯后验采样）与多臂老虎机 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/deeplearning_math/blob/main/tutorials/prob_stats/multi_armed_bandits_thompson_sampling.ipynb) | 11:36 | [link](https://www.bilibili.com/video/BV18p4y1Z7Xd) |
| 1617 | [矩阵分析] 分块矩阵的角度理解矩阵运算（独热向量与对角矩阵） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/deeplearning_math/blob/main/tutorials/matrix/%E5%88%86%E5%9D%97%E7%9F%A9%E9%98%B5%E7%9A%84%E5%A4%84%E7%90%86%E4%B8%8E%E7%90%86%E8%A7%A3.ipynb) | 5:55 | [link](https://www.bilibili.com/video/BV11T4y1b714) |
| 1618 | [pytorch optim] Adam 与 AdamW，L2 reg 与 weight decay，deepseed | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/nn_basics/optimizer/adadelta_adam.ipynb) [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/nn_basics/optimizer/l2_reg_weight_decay_adaw.ipynb) | 10:53 | [link](https://www.bilibili.com/video/BV1Wt421b7uA) |
| 1619 | [pytorch optim] pytorch 作为一个通用优化问题求解器（目标函数、决策变量） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/nn_basics/optimizer/pytorch_as_a_general_optimizer.ipynb) | 8:55 | [link](https://www.bilibili.com/video/BV1kt421V7Y4) |
| 1620 | [lora 番外] LoRA merge 与 SVD（矩阵奇异值分解） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/peft/lora_svd_basics.ipynb) | 6:45 | [link](https://www.bilibili.com/video/BV1XK421a75H) |
| 1621 | [矩阵微分] 标量/矢量关于矢量/矩阵的矩阵微分，深度学习框架反向传播 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/deeplearning_math/blob/main/tutorials/matrix/matrix_calculus.ipynb) | 20:44 | [link](https://www.bilibili.com/video/BV1R4421Z79L) |
| 1622 | [损失函数设计] 为什么多分类问题损失函数用交叉熵损失，而不是 MSE | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/nn_basics/loss/mse_crossentropy.ipynb) | 8:29 | [link](https://www.bilibili.com/video/BV13NHfewE3o) |
| 1623 | [数学基础] 概率（probability） vs. 似然（likelihood），及其在LLM中小小的实践 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/deeplearning_math/blob/main/tutorials/prob_stats/LM%E4%B8%AD%E7%9A%84%E6%A6%82%E7%8E%87%E4%B8%8E%E4%BC%BC%E7%84%B6.ipynb) | 10:46 | [link](https://www.bilibili.com/video/BV1JpBtYjE5C) |
| 1624 | [LLMs 实践] 01 llama、alpaca、vicuna 整体介绍及 llama 推理过程 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/01_llama_intro.ipynb) | 20:24 | [link](https://www.bilibili.com/video/BV1jk4y1L75w) |
| 1625 | [LLMs 实践] 02 LoRA（Low Rank Adaption）基本原理与基本概念，fine-tune 大语言模型 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/02_lora_baics.ipynb) | 17:27 | [link](https://www.bilibili.com/video/BV15T411477N) |
| 1626 | [LLMs 实践] 03 LoRA fine-tune 大语言模型（peft、bloom 7b） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/03_lora_practice.ipynb) | 27:25 | [link](https://www.bilibili.com/video/BV1qz4y1B7LB) |
| 1627 | [LLMs 实践] 04 PEFT/LoRA 源码分析 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/04_PEFT_lora.ipynb) | 13:21 | [link](https://www.bilibili.com/video/BV1sV4y1z7uS) |
| 1628 | [番外] float16 与 bf16 表示和计算细节 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/05_float16_bf16.ipynb) | 13:27 | [link](https://www.bilibili.com/video/BV1no4y1u7og) |
| 1629 | [LLMs 实践] 06 LLaMA，Alpaca LoRA 7B 推理 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/06_alpaca_llama_7b_lora.ipynb) | 14:13 | [link](https://www.bilibili.com/video/BV1Po4y1T7Bn) |
| 1630 | [LLMs 实践] 07 fp16 与自动混合精度训练（amp）显著提升 batch size | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/07_fp16_mixed_precision_training.ipynb) | 11:55 | [link](https://www.bilibili.com/video/BV1Uj411D7Xm) |
| 1631 | [LLMs 实践] 08 LLM.int8 量化细节 （load_in_8bit）以及 bitsandbytes 库 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/LLM.int8.ipynb) | 18:12 | [link](https://www.bilibili.com/video/BV1bX4y1e7a5) |
| 1632 | [LLMs 实践] 09 BPE gpt2 tokenizer 与 train tokenizer | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/tokenizer_basics.ipynb) [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/gpt2_train_tokenizer.ipynb) | 21:30 | [link](https://www.bilibili.com/video/BV1Sk4y1P7LK) |
| 1633 | [LLMs 实践] 10 预训练语料，mapping & streaming（load_dataset） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/pretrain_corpus_%E5%A4%A7%E6%A8%A1%E5%9E%8B%E9%A2%84%E8%AE%AD%E7%BB%83%E8%AF%AD%E6%96%99.ipynb) [github.com](https://github.com/chunhuizhang/bert_t5_gpt/blob/main/tutorials/dataset_dataloader.ipynb) | 15:05 | [link](https://www.bilibili.com/video/BV1LF411Q7fh) |
| 1634 | [LLMs 实践] 11 gradient accumulation 显存优化 trick | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/gradient_accumulation.ipynb) | 8:22 | [link](https://www.bilibili.com/video/BV1tz4y1773d) |
| 1635 | [LLMs 实践] 12 LLM SFT training （trl SFTTrainer、alpaca dataset） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/llm_training_sft.ipynb) | 10:34 | [link](https://www.bilibili.com/video/BV1jh4y1c713) |
| 1636 | [LLMs 实践] 13 gradient checkpointing 显存优化 trick | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/gradient_checkpointing.ipynb) | 13:38 | [link](https://www.bilibili.com/video/BV1QM4y1H7nH) |
| 1637 | [LLMs 实践] 14 llama2 introduction 及 fine tune llama2（guanaco dataset） | - | AI 论文精读 | - | [huggingface.co](https://huggingface.co/blog/llama2) [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/llama2_introduction.ipynb) | 17:20 | [link](https://www.bilibili.com/video/BV1xP411x7TL) |
| 1638 | [LLMs 实践] 15 llama2 源码初步（text completion & chat completion） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/llama2_src_01.ipynb) | 22:34 | [link](https://www.bilibili.com/video/BV1Zu4y1B7gM) |
| 1639 | [personal chatgpt] trl 基础介绍：reward model，ppotrainer | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/trl_basics.ipynb) | 16:51 | [link](https://www.bilibili.com/video/BV1zm4y1H79x) |
| 1640 | [LLMs 实践] 17 llama2 源码分析（RMSNorm 与 SwiGLU） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/llama2_src_02_RMSNorm_SwiGLU.ipynb) | 10:26 | [link](https://www.bilibili.com/video/BV1e14y1C7G8) |
| 1641 | [LLMs 实践] 18 llama2 源码分析 RoPE 相对位置编码的复数形式 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/llama2_src_03_RoPE_01_complex_position_encoding.ipynb) | 12:05 | [link](https://www.bilibili.com/video/BV1Dh4y1P7KY) |
| 1642 | [LLMs 实践] 19 llama2 源码分析 RoPE apply_rotary_emb 从绝对位置编码到相对位置编码 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/llama2_src_03_RoPE_apply_rotary_emb.ipynb) | 15:27 | [link](https://www.bilibili.com/video/BV18u411M7j1) |
| 1643 | [LLMs 实践] 20 llama2 源码分析 cache KV（keys、values cache）加速推理 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/llama2_src_cache_kv.ipynb) | 14:10 | [link](https://www.bilibili.com/video/BV1FB4y1Z79y) |
| 1644 | [LLMs 实践] 21 llama2 源码分析 GQA：Grouped Query Attention | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/llama2_src_grouped_query_attention.ipynb) | 7:34 | [link](https://www.bilibili.com/video/BV1vc411o7fa) |
| 1645 | [LLMs 实践] 221 llama2 源码分析 generate 的完整过程 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/llama2_src_generate.ipynb) | 26:55 | [link](https://www.bilibili.com/video/BV1Ea4y1d7wx) |
| 1646 | [personal chatgpt] trl reward model 与 RewardTrainer（奖励模型，分类模型） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/reward_model/trl_reward_trainer.ipynb) | 18:36 | [link](https://www.bilibili.com/video/BV1GZ421t7oU) |
| 1647 | [personal chatgpt] peft LoRA merge pipeline（lora inject，svd） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/peft/lora_inject.ipynb) [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/peft/lora_merge.ipynb) [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/peft/lora_svd_basics.ipynb) | 20:44 | [link](https://www.bilibili.com/video/BV13A4m1w7i6) |
| 1648 | [personal chatgpt] LLAMA 3 整体介绍（与 LLama 2 的不同？） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/llama/llama3_0419.ipynb) | 19:54 | [link](https://www.bilibili.com/video/BV15z42167yB) |
| 1649 | [personal chatgpt] gpt-4o tokenizer 及特殊中文tokens（压缩词表），o200k_base | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/tokenizer/tokenizer_gpt4o.ipynb) | 10:00 | [link](https://www.bilibili.com/video/BV1bw4m1Q7KC) |
| 1650 | [personal chatgpt] trl rlhf PPOTrainer，原理分析与代码走读（OpenRLHF framework） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/trl_hf/trl_ppotrainer_helloworld.ipynb) | 26:46 | [link](https://www.bilibili.com/video/BV1ss421G7Nj) |
| 1651 | [personal chatgpt] 从 RoPE 到 CoPE（绝对位置编码，相对位置编码，Contextual Position Encoding） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/position_encoding/rope_cope.ipynb) | 26:33 | [link](https://www.bilibili.com/video/BV1XS411P7Lc) |
| 1652 | [personal chatgpt] Llama2 7B vs. Llama3 8B （词表、attention 及 mlp） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/llama/llama2_7b_llama3_8b.ipynb) | 19:10 | [link](https://www.bilibili.com/video/BV18E421A7TQ) |
| 1653 | [personal chatgpt] instructGPT 中的 reward modeling，概率建模与损失函数性质 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/reward_model/reward_model_Bradley_Terry_model.ipynb) | 22:47 | [link](https://www.bilibili.com/video/BV1GJDzYcEns) |
| 1654 | [python 多进程、多线程以及协程] 01 关于进程（multiprocessing，pid、ppid） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/threads/about_process.py) | 6:28 | [link](https://www.bilibili.com/video/BV1dD4y1a7NS) |
| 1655 | [python 多进程、多线程、协程] 02 用 python 多线程实现生产者消费者流程 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/threads/prod_cons.py) | 10:01 | [link](https://www.bilibili.com/video/BV1YP411M7eN) |
| 1656 | [python 多进程、多线程] 03 GIL、threading、多进程，concurrent.futures | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/full_stack/blob/main/tutorials/python/%E5%A4%9A%E8%BF%9B%E7%A8%8B_%E5%A4%9A%E7%BA%BF%E7%A8%8B/GIL_mt_mp.ipynb) | 17:47 | [link](https://www.bilibili.com/video/BV1pE4depEtq) |
| 1657 | [模型拓扑接口] 经典 RNN 模型（一）模型参数及训练参数的介绍 | - | AI 论文精读 | - | [pytorch.org](https://pytorch.org/docs/stable/generated/torch.nn.RNN.html) | 19:42 | [link](https://www.bilibili.com/video/BV13v4y1P7Cd) |
| 1658 | [模型拓扑结构] pytorch 注册钩子函数（register_forward_hook）实现对各个层（layer）输入输出 shape 的查看 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/tree/master/learn_torch/utils) | 8:35 | [link](https://www.bilibili.com/video/BV1YL4y1A7oY) |
| 1659 | 【计算机视觉】cnn/maxpool 输入输出 shape 的变化与kernel size、pool size、stride size，padding=same | - | AI 论文精读 | - | - | 12:31 | [link](https://www.bilibili.com/video/BV1oJ411d73Q) |
| 1660 | [pytorch 网络拓扑结构] 深度理解 nn.BatchNorm1d | - | AI 论文精读 | - | [pytorch.org](https://pytorch.org/docs/stable/generated/torch.nn.BatchNorm1d.html) | 9:17 | [link](https://www.bilibili.com/video/BV19B4y1q743) |
| 1661 | [pytorch 网络模型结构] 深入理解 nn.BatchNorm1d/2d 计算过程 | - | AI 论文精读 | - | [pytorch.org](https://pytorch.org/docs/stable/generated/torch.nn.BatchNorm2d.html) | 9:35 | [link](https://www.bilibili.com/video/BV1dv4y1M79T) |
| 1662 | [pytorch 模型拓扑结构] 深入理解 nn.BatchNorm2d/3d | - | AI 论文精读 | - | [pytorch.org](https://pytorch.org/docs/stable/generated/torch.nn.BatchNorm2d.html) | 3:46 | [link](https://www.bilibili.com/video/BV1vY411N7gb) |
| 1663 | [pytorch 网络拓扑结构] 深入理解 nn.LayerNorm 的计算过程 | - | AI 论文精读 | - | - | 14:12 | [link](https://www.bilibili.com/video/BV1Fa411p7W3) |
| 1664 | [pytorch 模型拓扑结构] 深入理解 nn.CrossEntropyLoss 计算过程（nn.NLLLoss(nn.LogSoftmax)) | - | AI 论文精读 | - | [pytorch.org](https://pytorch.org/docs/stable/generated/torch.nn.CrossEntropyLoss.html) [pytorch.org](https://pytorch.org/docs/stable/generated/torch.nn.NLLLoss.html) | 10:32 | [link](https://www.bilibili.com/video/BV1NY4y1E76o) |
| 1665 | [pytorch 模型拓扑结构] pytorch 矩阵乘法大全（torch.dot, mm, bmm, @, *, matmul） | - | AI 论文精读 | - | - | 8:26 | [link](https://www.bilibili.com/video/BV1za411S7sA) |
| 1666 | [pytorch 神经网络拓扑结构] pad_sequence/pack_padded_sequence 时序模型如何处理不定长输入 | - | AI 论文精读 | - | [pytorch.org](https://pytorch.org/docs/stable/generated/torch.nn.utils.rnn.pad_sequence.html) [pytorch.org](https://pytorch.org/docs/stable/generated/torch.nn.utils.rnn.pad_packed_sequence.html) | 14:04 | [link](https://www.bilibili.com/video/BV1A94y1D76b) |
| 1667 | [pytorch模型拓扑结构] nn.MultiheadAttention, init/forward, 及 query，key，value 的计算细节 | - | AI 论文精读 | - | - | 17:20 | [link](https://www.bilibili.com/video/BV1Za411G782) |
| 1668 | [pytorch 网络模型结构] batchnorm train 及 eval 模式的差异及（running_mean, running_var）的计算细节 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/tree/master/learn_torch/tutorials) | 11:49 | [link](https://www.bilibili.com/video/BV1n14y1v7ap) |
| 1669 | [pytorch] [求导练习] 01 sigmoid 函数自动求导练习（autograd，单变量，多变量 multivariables 形式） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/learn_torch/grad/01_sigmoid.ipynb) | 11:31 | [link](https://www.bilibili.com/video/BV1rW4y1N7ZU) |
| 1670 | [pytorch] [求导练习] 02 softmax 函数自动求导练习（autograd，Jacobian matrix） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/learn_torch/grad/02_softmax.ipynb) | 16:46 | [link](https://www.bilibili.com/video/BV1gW4y1K7Du) |
| 1671 | [pytorch] [求导练习] 03 计算图（computation graph）及链式法则（chain rule）反向传播过程 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/learn_torch/grad/03_computation_graph.ipynb) | 13:56 | [link](https://www.bilibili.com/video/BV1hv4y1B7pE) |
| 1672 | [pytorch] [求导练习] 04 前向计算与反向传播与梯度更新（forward，loss.backward(), optimizer.step） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/learn_torch/grad/04_backward_step.ipynb) | 15:07 | [link](https://www.bilibili.com/video/BV13G4y1m7MC) |
| 1673 | [pytorch 模型拓扑结构] 深入理解 nn.BCELoss 计算过程及 backward 及其与 CrossEntropyLoss 的区别与联系 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/learn_torch/loss/01_BCELoss_binary_cross_entropy.ipynb) | 15:33 | [link](https://www.bilibili.com/video/BV1H24y1e7oV) |
| 1674 | [pytorch] [求导练习] 05 计算图（computation graph）构建细节之 inplace operation（data与detach） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/learn_torch/grad/05_torch_variables_grad_inplace_operation.ipynb) [zhuanlan.zhihu.com](https://zhuanlan.zhihu.com/p/38475183) | 23:30 | [link](https://www.bilibili.com/video/BV1YL411Z7Rj) |
| 1675 | [pytorch] [求导练习] 06 计算图（computation graph）细节之 retain graph（multi output/backwar） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/learn_torch/grad/06_retain_graph.ipynb) | 11:06 | [link](https://www.bilibili.com/video/BV1o24y1b7tk) |
| 1676 | [pytorch] 深入理解 torch.gather 及 dim 与 index 的关系 | - | AI 论文精读 | - | [zhuanlan.zhihu.com](https://zhuanlan.zhihu.com/p/352877584) [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/learn_torch/basics/torch.gather.ipynb) | 12:45 | [link](https://www.bilibili.com/video/BV1YY4y1Q72M) |
| 1677 | [pytorch] 深入理解 nn.KLDivLoss（kl 散度） 与 nn.CrossEntropyLoss（交叉熵） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/learn_torch/loss/02_kl_divergence_cross_entropy.ipynb) [pytorch.org](https://pytorch.org/docs/stable/generated/torch.nn.KLDivLoss.html) [pytorch.org](https://pytorch.org/docs/stable/generated/torch.nn.CrossEntropyLoss.html) | 21:54 | [link](https://www.bilibili.com/video/BV1Nx4y1N7qb) |
| 1678 | [pytorch] 激活函数（梯度消失）sigmoid，clamp，relu（sparse representation，dying relu） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/learn_torch/basics/activate_fn_gradient_sigmoid_relu_clamp.ipynb) | 15:10 | [link](https://www.bilibili.com/video/BV1qh411u7Ab) |
| 1679 | [pytorch] 激活函数，从 ReLU、LeakyRELU 到 GELU 及其梯度（gradient）（BertLayer，FFN，GELU） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/nn_basics/02_gelu_grad.ipynb) [paperswithcode.com](https://paperswithcode.com/method/gelu) | 9:30 | [link](https://www.bilibili.com/video/BV1Wg4y177py) |
| 1680 | [pytorch] nn.Embedding 前向查表索引过程与 one hot 关系及 max_norm 的作用 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/nn_basics/04_embedding_details.ipynb) | 13:25 | [link](https://www.bilibili.com/video/BV1wm4y187Cr) |
| 1681 | [pytorch] torch.einsum 到索引到矩阵运算（index、shape、dimension、axis） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/nn_basics/einsum_numpy_torch.ipynb) | 13:28 | [link](https://www.bilibili.com/video/BV1Fx4y1X72e) |
| 1682 | [pytorch] Tensor shape 变化 view 与 reshape（contiguous 的理解） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/nn_basics/shape_modified.ipynb) | 11:36 | [link](https://www.bilibili.com/video/BV1Zw411y7Ks) |
| 1683 | [pytorch] Tensor 轴（axis）交换，transpose（转置）、swapaxes、permute | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/nn_basics/axis_dim_processing.ipynb) | 14:42 | [link](https://www.bilibili.com/video/BV1pN4y117rD) |
| 1684 | [pytorch] 多项式分布及采样（torch.multinomial, torch distribution Categorical） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/nn_basics/multinomail_categorical.ipynb) | 10:46 | [link](https://www.bilibili.com/video/BV1Vu4y1p7dv) |
| 1685 | [pytorch] torch.nn.Bilinear 计算过程与 einsum（爱因斯坦求和约定） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/nn_basics/einsum_bilinear.ipynb) | 11:37 | [link](https://www.bilibili.com/video/BV1De411X7ei) |
| 1686 | [pytorch 番外] Tensorboard 与计算图初步（算子与 ATen） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/nn_basics/tensorboard_graph.ipynb) | 12:14 | [link](https://www.bilibili.com/video/BV1Vv411F7tG) |
| 1687 | [pytorch] F.binary_cross_entropy（二分类） 与 F.cross_entropy（多分类） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/nn_basics/bce_loss_cross_entropy.ipynb) | 7:00 | [link](https://www.bilibili.com/video/BV1AN41177Jo) |
| 1688 | [einops 01] einsum 补充与 einops 初步（实现 ViT 的图像分块） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/nn_basics/einsum_supp_einops_%E5%88%9D%E6%AD%A5.ipynb) | 12:21 | [link](https://www.bilibili.com/video/BV11J4m1s7AU) |
| 1689 | [PyTorch] Dropout 基本原理（前向计算与自动求导） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/nn_basics/torch_dropout.ipynb) | 7:07 | [link](https://www.bilibili.com/video/BV1Xz421r7L1) |
| 1690 | [pytorch 计算图] retain_graph 获取非叶子节点的 grad | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/nn_basics/grad/retain_grad_retatin_graph.ipynb) | 8:32 | [link](https://www.bilibili.com/video/BV1DH4y1N7it) |
| 1691 | k-Sparse AutorEncoder 与大语言模型可解释性研究（openai、claude），top-K 求导 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/nn_basics/grad/sae_topK.ipynb) | 13:06 | [link](https://www.bilibili.com/video/BV1sx4y1J76b) |
| 1692 | [pytorch] BN、LN、RMSNorm 及 pre LN vs. post LN 对比，标准化 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/nn_basics/normalization.ipynb) | 23:23 | [link](https://www.bilibili.com/video/BV13q49eaERj) |
| 1693 | [LLMs tuning] 01 trl SFTTrainer 中的 formatting_func 与 DataCollatorForCompletion | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llms_tuning/blob/main/tutorials/finetune/trl/collate_fn_formatting_func.ipynb) | 15:13 | [link](https://www.bilibili.com/video/BV1bn4y1f7wF) |
| 1694 | [LLMs tuning] 02 accelerate ddp 与 trl SFTTrainer | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llms_tuning/blob/main/tutorials/accelerate_ds_fsdp/accelerate_ddp.ipynb) | 9:44 | [link](https://www.bilibili.com/video/BV1V4421S75Q) |
| 1695 | [LLMs tuning] 03 llama3-8B instruct SFT on Financial RAG | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llms_tuning/blob/main/tutorials/finetune/examples/finetune_llama3_for_RAG.ipynb) | 26:03 | [link](https://www.bilibili.com/video/BV1Yx4y147t4) |
| 1696 | [LLMs tuning] 04 optimizer Trainer 优化细节（AdamW，grad clip、Grad Norm）等 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llms_tuning/blob/main/tutorials/optimization_details.ipynb) | 12:33 | [link](https://www.bilibili.com/video/BV1Ri421h7qV) |
| 1697 | [LLMs tuning] 05 StackLlama、SFT+DPO（代码组织、数据处理，pipeline） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llms_tuning/blob/main/tutorials/finetune/trl-examples/llama_stackexchange.ipynb) | 25:54 | [link](https://www.bilibili.com/video/BV1gE421A7Pm) |
| 1698 | [LLMs tuning] 06 多轮对话 qlora SFT（Multi-turn Conversation） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/llms_tuning/blob/main/tutorials/chat/chat_sft_mistral.ipynb) | 16:46 | [link](https://www.bilibili.com/video/BV1ygHFeQEE5) |
| 1699 | [pytorch 强化学习] 01 认识环境（environment，gym.Env）以及 CartPole-v0/v1 环境 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/rl/tutorials/01_env.ipynb) [gymlibrary.dev](https://www.gymlibrary.dev/environments/classic_control/cart_pole/) | 18:04 | [link](https://www.bilibili.com/video/BV1tP411M7dT) |
| 1700 | [pytorch 强化学习] 02 将 env rendering 保存为 mp4/gif（以 CartPole 为例，mode='rgb_array'） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/tree/master/rl/tutorials) | 16:25 | [link](https://www.bilibili.com/video/BV1JW4y1g7AH) |
| 1701 | [pytorch 强化学习] 03 动手写迷宫环境（maze env）状态及动作策略初步（及动画保存） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/rl/tutorials/03_maze.ipynb) | 26:29 | [link](https://www.bilibili.com/video/BV1Ye411P7Sw) |
| 1702 | [pytorch 强化学习] 04 迷宫环境（maze environment）封装 MazeEnv、Agent 类 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/rl/tutorials/03_MazeEnv_Agent.ipynb) | 15:47 | [link](https://www.bilibili.com/video/BV1pD4y1a7Am) |
| 1703 | [pytorch 强化学习] 05 迷宫环境（maze environment）策略梯度（Policy Gradient）求解 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/rl/tutorials/04_maze_env_policy_gradient.ipynb) | 25:23 | [link](https://www.bilibili.com/video/BV1es4y1a7Q2) |
| 1704 | [pytorch 强化学习] 06 迷宫环境（maze environment）SARSA（Q-table，value iteration）求解 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/rl/tutorials/05_value_iteration_sarsa.ipynb) | 31:45 | [link](https://www.bilibili.com/video/BV1Us4y1h7TZ) |
| 1705 | [pytorch 强化学习] 07 迷宫环境（maze environment）Q Learning（value iteration）求解（策略关闭 off） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/rl/tutorials/06_value_iteration_q_learning.ipynb) | 6:08 | [link](https://www.bilibili.com/video/BV1LY4y127XV) |
| 1706 | [pytorch 强化学习] 08 CartPole Q learning 连续状态离散化（digitize 分桶）及 display_frame_as_gif | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/rl/tutorials/07_cart_pole_digitize_space.ipynb) [gymlibrary.dev](https://www.gymlibrary.dev/environments/classic_control/cart_pole/) | 18:31 | [link](https://www.bilibili.com/video/BV1Lo4y1k7Mz) |
| 1707 | [pytorch 强化学习] 09 （逐行写代码）CartPole Q learning 基于连续状态离散化（digitize 分桶） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/rl/tutorials/08_cart_pole_q_learning.ipynb) | 25:53 | [link](https://www.bilibili.com/video/BV1Yv4y187jP) |
| 1708 | [pytorch 强化学习] 10 从 Q Learning 到 DQN（experience replay 与 huber loss / smooth L1） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/rl/tutorials/09_dqn_cart_pole_outline.ipynb) [pytorch.org](https://pytorch.org/tutorials/intermediate/reinforcement_q_learning.html) | 13:26 | [link](https://www.bilibili.com/video/BV1Fs4y1p75P) |
| 1709 | [pytorch 强化学习] 11 逐行写代码实现 DQN（ReplayMemory，Transition，DQN as Q function） | - | AI 论文精读 | - | [pytorch.org](https://pytorch.org/tutorials/intermediate/reinforcement_q_learning.html) [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/rl/tutorials/10_dqn_cart_pole.ipynb) | 35:51 | [link](https://www.bilibili.com/video/BV1XP411Z7N4) |
| 1710 | [pytorch 强化学习] 12 逐行写代码实现 DQN 完全体 | - | AI 论文精读 | - | [pytorch.org](https://pytorch.org/tutorials/intermediate/reinforcement_q_learning.html) [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/rl/tutorials/10_dqn_cart_pole.ipynb) | 20:42 | [link](https://www.bilibili.com/video/BV1t84y1w7BC) |
| 1711 | [pytorch 强化学习] 13 基于 pytorch 神经网络实现 policy gradient（REINFORCE）求解 CartPole | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/rl/tutorials/11_deep_policy_gradient_on_cartpole.ipynb) [cs.toronto.edu](http://www.cs.toronto.edu/~tingwuwang/REINFORCE.pdf) [lilianweng.github.io](https://lilianweng.github.io/posts/2018-04-08-policy-gradient/) | 25:46 | [link](https://www.bilibili.com/video/BV1eg4y1s7TN) |
| 1712 | [强化学习基础 01] MDP 基础（概率转移，与POMDP、I-POMDP） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/drl/mdp_basics.ipynb) | 19:52 | [link](https://www.bilibili.com/video/BV1V94y1E7Pi) |
| 1713 | [强化学习基础 02] MDP价值迭代算法（value iteration，V(s), Q(s,a), pi(s)） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/drl/mdps_value_iteration.ipynb) | 21:48 | [link](https://www.bilibili.com/video/BV1ow41147Nv) |
| 1714 | [强化学习基础 03] 多臂老虎机（Multi-Armed Bandit）与 UCB | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/drl/multi_armed_bandits.ipynb) | 22:30 | [link](https://www.bilibili.com/video/BV1Ga4y167ux) |
| 1715 | [mcts] 01 mcts 基本概念基本原理（UCB）及两个示例 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/drl/mcts/mcts_01_intro_bascis.ipynb) | 22:44 | [link](https://www.bilibili.com/video/BV1zC411h7B8) |
| 1716 | [mcts] 02 mcts from scartch（UCTNode，uct_search, pUCT，树的可视化） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/drl/mcts/mcts_02_from_scartch.ipynb) | 13:22 | [link](https://www.bilibili.com/video/BV1ZA4m1P7RV) |
| 1717 | [DRL] 从策略梯度到 TRPO（Lagrange Duality，拉格朗日对偶性） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/drl/policy_based/pg_trpo_ppo.ipynb) | 14:58 | [link](https://www.bilibili.com/video/BV1hD421K7gG) |
| 1718 | [DRL] 从 TRPO 到 PPO（PPO-penalty，PPO-clip） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/drl/policy_based/pg_trpo_ppo.ipynb) | 12:32 | [link](https://www.bilibili.com/video/BV11J4m137fY) |
| 1719 | [RLHF] 从 PPO rlhf 到 DPO，公式推导与原理分析 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/trl_hf/trl_dpo.ipynb) [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/trl_hf/dpo_math.ipynb) | 16:01 | [link](https://www.bilibili.com/video/BV1pM4m1U75K) |
| 1720 | 【运筹】运筹决策系统的搭建，从决策变量、中间变量到约束及目标，从求解到无解时约束的放松 | - | AI 论文精读 | - | - | 6:15 | [link](https://www.bilibili.com/video/BV18L4y1B7HM) |
| 1721 | 【ortools】【cpmodel】八皇后问题的约束规划求解（leetcode 51/52 n-queens） | - | AI 论文精读 | - | [developers.google.cn](https://developers.google.cn/optimization/cp/queens?hl=zh-cn) | 22:06 | [link](https://www.bilibili.com/video/BV1Si4y1L7gD) |
| 1722 | 【python 运筹优化】scipy.optimize.minimize 接口介绍（method、jacobian、hessian）/ 有约束非线性优化 | - | AI 论文精读 | - | [docs.scipy.org](https://docs.scipy.org/doc/scipy/reference/generated/scipy.optimize.minimize.html) [scipy-lectures.org](https://scipy-lectures.org/advanced/mathematical_optimization/) | 19:56 | [link](https://www.bilibili.com/video/BV1nA4y197mu) |
| 1723 | 【python 运筹优化】scipy.optimize.minimize 使用 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/nlp/demo.py) [docs.scipy.org](https://docs.scipy.org/doc/scipy/reference/generated/scipy.optimize.minimize.html) | 15:49 | [link](https://www.bilibili.com/video/BV1nL4y157iQ) |
| 1724 | 【python 运筹】混合整数规划 / MIP / ortools / SCIP / CBC | - | AI 论文精读 | - | - | 12:09 | [link](https://www.bilibili.com/video/BV1jq4y1z7Rf) |
| 1725 | 【Python 运筹实战】Python实战 /指派问题assignment problem/ 匈牙利算法（Hungarian algorithm） | - | AI 论文精读 | - | - | 7:47 | [link](https://www.bilibili.com/video/BV1dR4y1t756) |
| 1726 | 【Python 运筹实战】指派问题assignment problem/ 匈牙利算法（Hungarian algorithm）/ scipy.optimize | - | AI 论文精读 | - | - | 5:27 | [link](https://www.bilibili.com/video/BV1KS4y1R7eY) |
| 1727 | 【运筹】0/1二值逻辑整数规划约束的描述与表达，conditional/multiple choices以及互斥约束建模 | - | AI 论文精读 | - | - | 21:16 | [link](https://www.bilibili.com/video/BV1Et4y167rm) |
| 1728 | 【运筹】【整数规划】outer approximation 求解 MINLP及示例 | - | AI 论文精读 | - | [optimization.mccormick.northwestern.edu](https://optimization.mccormick.northwestern.edu/index.php/Outer-approximation_(OA) [science.osti.gov](https://science.osti.gov/-/media/ascr/pdf/workshops-conferences/mathtalks/Leyffer.pdf) | 28:23 | [link](https://www.bilibili.com/video/BV1mZ4y157To) |
| 1729 | [python 运筹优化] 系统性介绍 scipy 中的非线性最小二乘（NNLS, curve_fit, least_squares） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/ortools_tutorials/blob/main/tutorials/scipy.optimize/least_square_curve_fit.ipynb) | 19:41 | [link](https://www.bilibili.com/video/BV1GQ4y1H78A) |
| 1730 | [优化算法] 梯度下降、共轭梯度、牛顿法、逆牛顿法（BFGS） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/ortools_tutorials/blob/main/tutorials/scipy.optimize/Quasi-Newton.ipynb) | 13:04 | [link](https://www.bilibili.com/video/BV1CD421n73k) |
| 1731 | [全栈算法工程师系列] python deepcopy（深拷贝，clone，克隆）性能优化（浅拷贝+递归） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/basics/opt/copy_test.ipynb) [cloud.tencent.com](https://cloud.tencent.com/developer/article/1008984) [xie.infoq.cn](https://xie.infoq.cn/article/71e69c4296f307132cac4d367) | 6:12 | [link](https://www.bilibili.com/video/BV1T14y1b7ve) |
| 1732 | [全栈算法工程师] 如何把github当做个人笔记记录站点，git与github（本地与远端，local/remote(origin)） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/deep_learning_notes) | 12:59 | [link](https://www.bilibili.com/video/BV1uG4y1a7gz) |
| 1733 | [全栈算法工程师] 用 subprocess.Popen 执行 linux 命令 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/basics/python/linux_shell.py) | 7:52 | [link](https://www.bilibili.com/video/BV1nd4y1o7Xk) |
| 1734 | 【Python番外】可变对象（mutable）vs.不可变对象（immuable），可hash对象（hashable）vs.不可hash对象（unhashab） | - | AI 论文精读 | - | - | 14:35 | [link](https://www.bilibili.com/video/BV1C7411R72h) |
| 1735 | 【python番外】python函数式编程与闭包与yield关键字 | - | AI 论文精读 | - | - | 25:53 | [link](https://www.bilibili.com/video/BV1mJ411q7no) |
| 1736 | 【python app 开发】01 使用 tkinter 及 pyinstaller 制作一个简单的日期管理软件 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/app/date_demo2.py) | 12:44 | [link](https://www.bilibili.com/video/BV1DP4y127Uh) |
| 1737 | 【python app 开发】02 使用 tkinter 及 PIL (pillow) 制作图像九宫格 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/app/learn/splits.py) | 12:30 | [link](https://www.bilibili.com/video/BV1HW4y1W7KV) |
| 1738 | [全栈深度学习] 02 vscode remote（远程）gpus 服务器开发调试 debugger（以 nanoGPT 为例） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/full_stack/blob/main/tutorials/02_vscode_remote_server_development.ipynb) | 17:08 | [link](https://www.bilibili.com/video/BV1xs4y1Q7bs) |
| 1739 | [全栈深度学习] 01 docker 工具的基本使用及 nvidia cuda pytorch 镜像 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/full_stack/blob/main/tutorials/01_docker.ipynb) | 17:56 | [link](https://www.bilibili.com/video/BV19s4y1X7Zx) |
| 1740 | [工具的使用] python jupyter 环境安装配置拓展（nbextension）（ExcecuteTime：执行时间，Table of Content） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/fun_tools/jupyter_extentisons.md) [towardsdatascience.com](https://towardsdatascience.com/jupyter-notebook-extensions-517fa69d2231) | 10:24 | [link](https://www.bilibili.com/video/BV1u24y147bo) |
| 1741 | [python 全栈] python 装饰器（decorator）及 functools.cache | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/full_stack/blob/main/tutorials/python/decorator_basics_functools.ipynb) | 16:27 | [link](https://www.bilibili.com/video/BV1v8411R7tf) |
| 1742 | [全栈算法] docker nvidia pytorch gpu 环境及容器操作，端口号映射 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/full_stack/blob/main/tutorials/docker_gpu_torch_%E6%B7%B1%E5%BA%A6%E5%AD%A6%E4%B9%A0%E7%8E%AF%E5%A2%83.ipynb) | 15:05 | [link](https://www.bilibili.com/video/BV1Su4y1e7fc) |
| 1743 | [python 全栈] 正则表达式初步与指南 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/full_stack/blob/main/tutorials/%E6%AD%A3%E5%88%99_re_regex.ipynb) | 22:53 | [link](https://www.bilibili.com/video/BV1kg4y1d768) |
| 1744 | [全栈 docker] 03 docker 容器开发（start，exec）及 commit、save、load 持久化，docker vscode | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/full_stack/blob/main/tutorials/docker/docker_modify_save_load.ipynb) | 15:36 | [link](https://www.bilibili.com/video/BV1AF4m1w7Fo) |
| 1745 | [leetcode reviews] 01 计算思维与刷题方法 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/leetcode_reviews/blob/main/introduction.ipynb) [github.com](https://github.com/chunhuizhang/leetcode_reviews/blob/main/dp%E5%8A%A8%E6%80%81%E8%A7%84%E5%88%92/62.%20Unique%20Paths.ipynb) | 15:36 | [link](https://www.bilibili.com/video/BV1rP411s7T5) |
| 1746 | [leetcode reviews] 62 unique paths, dfs + cache, O(m), O(n) | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/leetcode_reviews/blob/main/%E9%80%92%E5%BD%92%E4%B8%8E%E5%9B%9E%E6%BA%AF/62.%20Unique%20Paths.ipynb) [github.com](https://github.com/chunhuizhang/leetcode_reviews/blob/main/dp%E5%8A%A8%E6%80%81%E8%A7%84%E5%88%92/62.%20Unique%20Paths.ipynb) | 9:20 | [link](https://www.bilibili.com/video/BV1hG411Z7Sf) |
| 1747 | [leetcode reviews] 207. Course Schedule（图算法，拓扑排序，DAG 环检测） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/leetcode_reviews/blob/main/%E6%95%B0%E6%8D%AE%E7%BB%93%E6%9E%84/%E5%9B%BE%EF%BC%88graph%EF%BC%89/topological_sort.ipynb) | 8:45 | [link](https://www.bilibili.com/video/BV1vN4y1Q7Q4) |
| 1748 | [leetcode reviews] FSM 有限状态机导论（交通灯，考拉兹猜想 Collatz conjecture） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/leetcode_reviews/blob/main/%E5%85%B6%E4%BB%96/FSM_%E6%9C%89%E9%99%90%E7%8A%B6%E6%80%81%E6%9C%BA.ipynb) | 12:30 | [link](https://www.bilibili.com/video/BV1Nu411M7za) |
| 1749 | [leetcode reviews] list of list 矩阵转置与旋转（transpose & rotate） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/leetcode_reviews/blob/main/%E6%95%B0%E6%8D%AE%E7%BB%93%E6%9E%84/grid_world/48.%20Rotate%20Image.ipynb) | 14:30 | [link](https://www.bilibili.com/video/BV13C4y137pJ) |
| 1750 | 【程序员说会计】breakeven / 盈亏平衡点 / 总营收（total revenue）/ 总成本（total cost）/ 边际贡献 | - | AI 论文精读 | - | - | 14:58 | [link](https://www.bilibili.com/video/BV1m34y1X7Wb) |
| 1751 | 【会计】个人所得税速算扣除数的计算及推导 | - | AI 论文精读 | - | - | 7:19 | [link](https://www.bilibili.com/video/BV13y4y177N1) |
| 1752 | 【Python 金融】72法则 / 本金翻倍 / 每年复利 1 次 / 每年复利多次 / 连续复利 / 泰勒级数 / 麦克劳林公式 | - | AI 论文精读 | - | - | 14:47 | [link](https://www.bilibili.com/video/BV1pZ4y197vZ) |
| 1753 | 【金融数学】中央银行法定准备金率与货币乘数/等比数列 | - | AI 论文精读 | - | - | 8:52 | [link](https://www.bilibili.com/video/BV1iq4y1R7Ez) |
| 1754 | [程序员说金融] 等额本金概念及计算（月供还款分析：月供本金，月供利息） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/finance/equal_principal.py) [cmbchina.com](https://www.cmbchina.com/CmbWebPubInfo/Cal_Loan_Per.aspx?chnl=dkjsq) [zhuanlan.zhihu.com](https://zhuanlan.zhihu.com/p/37403083) | 8:24 | [link](https://www.bilibili.com/video/BV1SY4y1w7XN) |
| 1755 | [程序员说金融] 等额本息概念及计算（月供还款分析：月供本金，月供利息） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/finance/equal_principal_interest.py) [baike.baidu.com](https://baike.baidu.com/item/) [cmbchina.com](https://www.cmbchina.com/CmbWebPubInfo/Cal_Loan_Per.aspx?chnl=dkjsq) | 6:36 | [link](https://www.bilibili.com/video/BV1CB4y1r7Lr) |
| 1756 | 【excel】计算白条花呗借呗分期付款的真实IRR（Internal Rate of Return） | - | AI 论文精读 | - | [iyiou.com](https://www.iyiou.com/p/85347.html) | 8:55 | [link](https://www.bilibili.com/video/BV17D4y197ET) |
| 1757 | [程序员说金融] 跨期投资项目的比较，NPV 与 IRR 的概念及计算（excel 函数） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/deep_learning_notes/blob/main/misc/) | 13:26 | [link](https://www.bilibili.com/video/BV1wg411k7ie) |
| 1758 | [程序员说金融] 对数回报率（收益率）及其性质（可加性，负对称性，及泰勒展开下的近似相等） | - | AI 论文精读 | - | - | 6:39 | [link](https://www.bilibili.com/video/BV11B4y1V7Bj) |
| 1759 | [程序员说金融] LPR（基准利率）概念（数据获取），你的房贷利率降了吗 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/financial_programming/blob/main/LPR(Loan-Prime-Rate) | 14:47 | [link](https://www.bilibili.com/video/BV1934y137ya) |
| 1760 | 【数值计算】newton's method 牛顿法求极值点，求函数的零点（求根），图解法 | - | AI 论文精读 | - | - | 7:16 | [link](https://www.bilibili.com/video/BV1yD4y1o7Po) |
| 1761 | 【数值计算】牛顿迭代法（Newton's method，Newton-Raphson method，牛顿-拉夫逊（拉弗森））计算二次方根（sqrt）三次方根 | - | AI 论文精读 | - | - | 5:19 | [link](https://www.bilibili.com/video/BV16t4y117Me) |
| 1762 | [数值计算] 一阶泰勒展开快速计算一个数的平方根 | - | AI 论文精读 | - | - | 5:24 | [link](https://www.bilibili.com/video/BV1V24y1676f) |
| 1763 | [数值计算] 快速计算、妙算对数，之对数表（logarithm table）的使用，如何将任意一个数转换为10-99，或0-0.99之间的可查表形式 | - | AI 论文精读 | - | [icap.org.pk](https://icap.org.pk/files/per/students/exam/notices/log-table.pdf) | 8:45 | [link](https://www.bilibili.com/video/BV1M341197gj) |
| 1764 | [数值计算] 快速计算、秒算大数乘除运算，对数变换将乘除变为加减，再通过查表（logarithm table）获得10-99之间的对数值 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/numerical/pdfs/log-table.pdf) | 9:23 | [link](https://www.bilibili.com/video/BV1Wd4y1H7oW) |
| 1765 | [animation & rendering] matplotlib funcanimation 多重动画绘制（multiple lines plot） | - | AI 论文精读 | - | [matplotlib.org](https://matplotlib.org/stable/api/animation_api.html) [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/vis/animation/line_plot_ani.py) [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/vis/animation/multi_line_plot_ani.py) | 21:30 | [link](https://www.bilibili.com/video/BV1pD4y1b7c2) |
| 1766 | [pygame Astar寻路算法可视化] 01 pygame 初始化及 grid world 创建 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/path_finding/tutorials/01_init_grid_world.py) | 11:52 | [link](https://www.bilibili.com/video/BV1984y1e7Yn) |
| 1767 | [pygame Astar寻路算法可视化] 02 鼠标事件响应（前台事件与后台处理） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/path_finding/tutorials/02_event_frontend_backend.py) | 13:53 | [link](https://www.bilibili.com/video/BV1bG4y1878o) |
| 1768 | [pygame Astar寻路算法可视化] 03 A star算法初始化及有效邻域的计算 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/path_finding/tutorials/03_astar.py) | 21:35 | [link](https://www.bilibili.com/video/BV13Y411f7VC) |
| 1769 | [pygame Astar寻路算法可视化] 04 A star 算法优先级队列，f = g + h | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/path_finding/tutorials/03_astar.py) | 16:24 | [link](https://www.bilibili.com/video/BV1TG4y1b7FA) |
| 1770 | [数据可视化] 绘制 z=f(x, y) （三维空间中的 surface） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/vis/animation/tutorials/01_z%3Df(x%2Cy) | 3:42 | [link](https://www.bilibili.com/video/BV1tY411y7N9) |
| 1771 | [数据可视化] 绘制交互式 3d plot（interactive 3d plot, Axes3d） z=f(x, y) （三维空间中的 surface） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/vis/animation/tutorials/02_interactive_3d_plot.ipynb) | 5:32 | [link](https://www.bilibili.com/video/BV1KR4y1a7Xe) |
| 1772 | 【搜索算法】【search】01 python-astar 图上搜索（graph search）f(n)=g(n)+h(n) | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/search/atar_demo.py) | 9:34 | [link](https://www.bilibili.com/video/BV1b44y197Jd) |
| 1773 | 【搜索算法】【search】02 爬山算法（hill climbing）二维离散空间上的邻域搜索 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/search/02_hill_climbing_discrete_space.ipynb) | 13:06 | [link](https://www.bilibili.com/video/BV1p8411N7BX) |
| 1774 | [python nlp] 01 词频分析与 Zipf law 齐夫定律（log-log plot） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/nlp/tutorials/01_word_freq_prob_zipf_law.ipynb) [norvig.com](http://norvig.com/ngrams/) [norvig.com](http://norvig.com/big.txt) | 16:31 | [link](https://www.bilibili.com/video/BV1EM411h75p) |
| 1775 | [概率统计] 将对数几率（logodds）引入到贝叶斯公式（bayes），后验对数几率=先验对数几率+似然对数几率 | - | AI 论文精读 | - | - | 7:21 | [link](https://www.bilibili.com/video/BV1DN4y1T7et) |
| 1776 | 【手推公式】logistic regression 及其与 linear regression 的区别，对数线性与对数几率 | - | AI 论文精读 | - | - | 10:18 | [link](https://www.bilibili.com/video/BV1zz4y1R7nr) |
| 1777 | 【统计】箱线图（boxplot）进行异常点检测（outlier detection），为什么定义为 1.5倍的 IQR | - | AI 论文精读 | - | [towardsdatascience.com](https://towardsdatascience.com/why-1-5-in-iqr-method-of-outlier-detection-5d07fdc82097) | 17:18 | [link](https://www.bilibili.com/video/BV1WR4y1g7Yp) |
| 1778 | 【数据处理】数据变换的三种形式，（几率）对数线性（log linear）、线性对数（linear log）、双对数log-log | - | AI 论文精读 | - | [journals.physiology.org](https://journals.physiology.org/doi/full/10.1152/advan.00018.2018) [medium.com](https://medium.com/@kyawsawhtoon/log-transformation-purpose-and-interpretation-9444b4b049c9) | 10:20 | [link](https://www.bilibili.com/video/BV1LZ4y1N78x) |
| 1779 | 【数据变换】【可视化】xscale('log') , yscale('log'), log-log plot 非线性转换为线性 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/data_science/tutorials/01_log_scale.ipynb) | 5:56 | [link](https://www.bilibili.com/video/BV1XK411y7YR) |
| 1780 | 【python 信号与系统】01 np.convolve 一维离散卷积（三种mode：full、valid、same） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/tree/master/signal_system) | 13:01 | [link](https://www.bilibili.com/video/BV1y44y1Q7MB) |
| 1781 | 【信号与系统】数值乘法与序列卷积，级数乘法与Cauchy 乘法 | - | AI 论文精读 | - | [zhuanlan.zhihu.com](https://zhuanlan.zhihu.com/p/30986744) | 13:05 | [link](https://www.bilibili.com/video/BV1Wh411f7C5) |
| 1782 | 【python 信号与系统】02 scipy.signal.convolve2d 二维（图像）卷积及其与 CNN 的区别 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/tree/master/signal_system) | 10:47 | [link](https://www.bilibili.com/video/BV1NW4y1W7zw) |
| 1783 | 【python 信号与系统】1维卷积实现滑动求和/滑动平均（moving sum，moving average） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/tree/master/signal_system) | 7:20 | [link](https://www.bilibili.com/video/BV15M411k7Wg) |
| 1784 | 【flask web 核心】01 认识 request，response 以及 cookie | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/web/flask_proj/tut01/app.py) | 14:01 | [link](https://www.bilibili.com/video/BV1t84y1r7Zg) |
| 1785 | [调包侠] 使用深度学习模型（paddlehub - humanseg）进行人物提取（前景提取、抠图） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/cv/seg/human_seg_0521.ipynb) | 17:51 | [link](https://www.bilibili.com/video/BV1sr4y14745) |
| 1786 | [调包侠] 使用 PyTorch Swin Transformer 完成图像分类 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/tree/master/pretrained/swin) | 18:20 | [link](https://www.bilibili.com/video/BV1na41177B2) |
| 1787 | [调包侠] tencent ailab 中文语料 embedding vector（word2vec） | - | AI 论文精读 | - | [ai.tencent.com](https://ai.tencent.com/ailab/nlp/zh/embedding.html) [ai.tencent.com](https://ai.tencent.com/ailab/nlp/zh/download.html) | 10:32 | [link](https://www.bilibili.com/video/BV1dr4y1u76M) |
| 1788 | [调包侠] 04 使用预训练模型进行图像特征向量提取（image feature extractor，img2vec）并进行相似性计算 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/tree/master/cv/img2vec) | 13:38 | [link](https://www.bilibili.com/video/BV1WY411N7fR) |
| 1789 | [调包侠] 使用 gensim 完成 word2vec 的计算，及 model.most_similar 的计算过程（positive，negative） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/nlp/gensim_demo/w2c.py) | 13:33 | [link](https://www.bilibili.com/video/BV1WF411A7Ah) |
| 1790 | 【数据可视化】【excel】漏斗分析-漏斗图（funnel）与金字塔图（pyramid）的区别和联系 | - | AI 论文精读 | - | - | 5:53 | [link](https://www.bilibili.com/video/BV1qE411g7h9) |
| 1791 | [不务正业] 科研的起点 - 修改 Python 三方库/包源码 | - | AI 论文精读 | - | [github.com](https://github.com/dexplo/bar_chart_race) | 8:26 | [link](https://www.bilibili.com/video/BV1xB4y1Y7BB) |
| 1792 | [面向 cv 的 ffmpeg] （1）ffmpeg.probe 获取视频基本信息 | - | AI 论文精读 | - | [github.com](https://github.com/kkroening/ffmpeg-python) [github.com](https://github.com/kkroening/ffmpeg-python/tree/master/examples) [github.com](https://github.com/chunhuizhang/bilibili_vlogs/tree/master/py_ffmpeg) | 4:52 | [link](https://www.bilibili.com/video/BV18a411n7hX) |
| 1793 | [面向 cv 的 ffmpeg] （2）将视频转换为 4D numpy.ndarray | - | AI 论文精读 | - | [github.com](https://github.com/kkroening/ffmpeg-python) [github.com](https://github.com/kkroening/ffmpeg-python/tree/master/examples) [github.com](https://github.com/chunhuizhang/bilibili_vlogs/tree/master/py_ffmpeg) | 4:11 | [link](https://www.bilibili.com/video/BV1pW4y1S7Sb) |
| 1794 | [深度学习面试系列] L2-L1正则的 MLE/MAP 概率解释 | - | AI 论文精读 | - | [bjlkeng.github.io](https://bjlkeng.github.io/posts/probabilistic-interpretation-of-regularization/#id12) | 15:45 | [link](https://www.bilibili.com/video/BV1ZW4y1C7wq) |
| 1795 | [计算几何] 从几何到代数 / 投影长度的计算（law of cosine 与 projection formula） | - | AI 论文精读 | - | - | 8:54 | [link](https://www.bilibili.com/video/BV1pY4y157KW) |
| 1796 | 【约束满足问题】AIMA / Chap 6 / CSP / AC-3 / Arc Consistency | - | AI 论文精读 | - | [en.wikipedia.org](https://en.wikipedia.org/wiki/AC-3_algorithm) | 14:13 | [link](https://www.bilibili.com/video/BV1Ku41167bs) |
| 1797 | 【约束规划】ortools / cpmodel / model.AddBoolOr / model.AddImplication / 实现逻辑表达式及逻辑约束 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/cp/binary_encodings.py) [google.github.io](https://google.github.io/or-tools/java/classcom_1_1google_1_1ortools_1_1sat_1_1CpModel.html) | 10:07 | [link](https://www.bilibili.com/video/BV1g34y1v747) |
| 1798 | 【运筹优化】CP-SAT / cpmodel / CSP / boolean logic / channeling / 分段函数 | - | AI 论文精读 | - | [github.com](https://github.com/google/or-tools/blob/stable/ortools/sat/doc/channeling.md) | 9:13 | [link](https://www.bilibili.com/video/BV1Nm4y1f7PH) |
| 1799 | 【运筹优化】CP-SAT / CP-model / 求解 CryptArithmetic | - | AI 论文精读 | - | [developers.google.com](https://developers.google.com/optimization/cp/cryptarithmetic) [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/ordemo/send_more_money.py) | 7:39 | [link](https://www.bilibili.com/video/BV13L411F7dC) |
| 1800 | 【运筹优化】CSP（约束满足最优化）/ CP-SAT / domain reduction / constraint propagation | - | AI 论文精读 | - | [ibm.com](https://www.ibm.com/docs/en/icos/20.1.0?topic=optimizer-constraint-propagation) | 7:19 | [link](https://www.bilibili.com/video/BV1gT4y1173C) |
| 1801 | 【python 运筹】约束满足规划问题 / CP-SAT solver / ortools / 自定义打印所有可行解的回调函数 | - | AI 论文精读 | - | [developers.google.com](https://developers.google.com/optimization/cp/cp_solver) [youtube.com](https://www.youtube.com/watch?v=4cCS8rrYT14) | 8:43 | [link](https://www.bilibili.com/video/BV1Bq4y1g7JJ) |
| 1802 | 【python 运筹】constraint satisfaction problems / 约束满足问题 / ortools.sat / cp_model | - | AI 论文精读 | - | [youtube.com](https://www.youtube.com/watch?v=1FJy-ubE7UE) [youtube.com](https://www.youtube.com/watch?v=4cCS8rrYT14) | 11:56 | [link](https://www.bilibili.com/video/BV1AF411a7ir) |
| 1803 | 【运筹】ortools / cp-sat / 鸡兔同笼 demo | - | AI 论文精读 | - | [github.com](https://github.com/google/or-tools) [github.com](https://github.com/google/or-tools/tree/stable/ortools/sat) [github.com](https://github.com/google/or-tools/tree/stable/ortools/sat/doc) | 7:03 | [link](https://www.bilibili.com/video/BV11v411T7o8) |
| 1804 | 【约束规划】从 binary encoding 到 logical expression 到 logical constraints 以及 CpModel | - | AI 论文精读 | - | [cis.upenn.edu](https://www.cis.upenn.edu/~cis189/) [ibmdecisionoptimization.github.io](https://ibmdecisionoptimization.github.io/docplex-doc/mp_vs_cp.html) | 11:31 | [link](https://www.bilibili.com/video/BV1ti4y1U77F) |
| 1805 | [Python 机器学习] 深入理解 numpy（ndarray）的 axis（轴/维度） | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/basics/np_basics/np_axis_demo.ipynb) | 14:20 | [link](https://www.bilibili.com/video/BV1vr4y187GQ) |
| 1806 | 【机器学习中的数学】【无穷级数】1/n^p（p-series）收敛性的证明 | - | AI 论文精读 | - | [animated-mathematics.net](https://animated-mathematics.net/integral-test-p-series.html) | 7:46 | [link](https://www.bilibili.com/video/BV1tN41197vH) |
| 1807 | 【机器学习中的数学】【概率论】正态分布的导数与拐点（inflection points） | - | AI 论文精读 | - | - | 7:40 | [link](https://www.bilibili.com/video/BV1Lp4y1H7tS) |
| 1808 | 【矩阵计算】从 im2col 到 GEMM，矩阵与核的卷积到矩阵乘法 | - | AI 论文精读 | - | [mathworks.com](https://www.mathworks.com/help/images/ref/im2col.html) [cnblogs.com](https://www.cnblogs.com/shine-lee/p/10775831.html) | 13:04 | [link](https://www.bilibili.com/video/BV13v411t76n) |
| 1809 | 【推荐系统】【缺失值处理】【矩阵分析】基于低秩矩阵补全（low rank matrix completing，矩阵分解 matrix factorizatio） | - | AI 论文精读 | - | - | 19:26 | [link](https://www.bilibili.com/video/BV1P5411572h) |
| 1810 | 【sklearn machin learning】linear model（lr/lasso/ridge）预测回归2020年双11总成交额（GMV） | - | AI 论文精读 | - | - | 16:20 | [link](https://www.bilibili.com/video/BV1Ea4y1s7uz) |
| 1811 | 【机器学习】线性回归（linear regression）逻辑回归（logistics regression）特征重要性与 odds ratio | - | AI 论文精读 | - | - | 12:50 | [link](https://www.bilibili.com/video/BV1CZ4y1T7k7) |
| 1812 | 【手推公式】可导损失函数（loss function）的梯度下降（GD）、随机梯度下降（SGD）以及mini-batch gd梯度优化策略 | - | AI 论文精读 | - | - | 8:59 | [link](https://www.bilibili.com/video/BV1Ct4y197ch) |
| 1813 | 【计算机科学】蒙特卡洛方法计算“一棍砍两刀”构成三角形的概率 | - | AI 论文精读 | - | [github.com](https://github.com/chunhuizhang/bilibili_vlogs) | 12:34 | [link](https://www.bilibili.com/video/BV1sE411v7se) |
| 1814 | 【贝叶斯分析】三门问题的贝叶斯解释及其对于人生的启发（路径依赖+沉没成本，为什么说选择大于努力，方向大于坚持，何时调整人生的方向） | - | AI 论文精读 | - | - | 7:22 | [link](https://www.bilibili.com/video/BV1ka4y1x78q) |
| 1815 | 【贝叶斯分析】三门问题（蒙提霍尔悖论，Monty Hall problem）的三个解释及其 python 仿真验证 | - | AI 论文精读 | - | - | 15:15 | [link](https://www.bilibili.com/video/BV1WK411L7vD) |
| 1816 | 大模型遇到Agent智能体：简介 #大模型 #AI系统 #智能体 | - | AI 论文精读 | - | - | 13:03 | [link](https://www.bilibili.com/video/BV11w411p7dW) |
| 1817 | AI Agent智能体具体组成 #大模型 #AI系统 #智能体 | - | AI 论文精读 | - | - | 10:59 | [link](https://www.bilibili.com/video/BV11u4y1P73P) |
| 1818 | Agent智能体的规划与提示词的关系 #大模型 #AI系统 #智能体 | - | AI 论文精读 | - | - | 15:09 | [link](https://www.bilibili.com/video/BV1kM411f7Gb) |
| 1819 | AI Agent智能体应用原理剖析：AutoGPT、HuggingFPT等 #大模型 #AI系统 #智能体 | - | AI 论文精读 | - | - | 14:49 | [link](https://www.bilibili.com/video/BV1KC4y1S7ZG) |
| 1820 | Agent智能体的问题与未来思考 #大模型 #AI系统 #智能体 | - | AI 论文精读 | - | - | 9:19 | [link](https://www.bilibili.com/video/BV1zM411f7n2) |
| 1821 | 什么是Harness？不就是Agent的Infra嘛 | - | AI 论文精读 | - | - | 14:09 | [link](https://www.bilibili.com/video/BV1nyQGBaEKW) |
| 1822 | DeepSeek Harnees全网深度解读！ | - | AI 论文精读 | - | - | 20:01 | [link](https://www.bilibili.com/video/BV1f98M6AEeg) |
| 1823 | 打破 Transformer 结构垄断的新方式！#大模型 #Transformer | - | AI 论文精读 | - | - | 8:22 | [link](https://www.bilibili.com/video/BV12EtRe4Ech) |
| 1824 | Linear Attention 打破 Transformer 大模型结构垄断！#大模型 #Transformer | - | AI 论文精读 | - | - | 23:28 | [link](https://www.bilibili.com/video/BV1V7s9etEmQ) |
| 1825 | 深度解读 KIMI K3 | - | AI 论文精读 | - | - | 18:41 | [link](https://www.bilibili.com/video/BV1rJKa63Eic) |
| 1826 | 万卡集群组网的网络基本知识！多层、单层、收敛比、拓扑什么关系？ | - | AI 论文精读 | - | - | 16:17 | [link](https://www.bilibili.com/video/BV1CQeEzFEiN) |
| 1827 | 又来万卡集群网络基本知识！框式vs盒式？单轨vs多轨？ | - | AI 论文精读 | - | - | 14:25 | [link](https://www.bilibili.com/video/BV18wHYz2EZ3) |
| 1828 | 了解AI组网，先看HPC超算组网洞察！世界最先进的组网都有哪些方案？ | - | AI 论文精读 | - | - | 16:22 | [link](https://www.bilibili.com/video/BV1sLWwzWEix) |
| 1829 | 国外万卡AI集群网络洞察！看国外Google、Mate 大厂是如何搭建万卡AI集群！ | - | AI 论文精读 | - | - | 20:57 | [link](https://www.bilibili.com/video/BV1tpnGzUELC) |
| 1830 | 国内大厂万卡AI集群网络洞察！看国内阿里、字节、腾讯是如何搭建万卡AI集群！ | - | AI 论文精读 | - | - | 22:14 | [link](https://www.bilibili.com/video/BV1FXnEzpEPZ) |
| 1831 | AI万卡集群建设挑战！太难啦建10万卡集群，哭死 | - | AI 论文精读 | - | - | 25:50 | [link](https://www.bilibili.com/video/BV1QTbxzyETx) |
| 1832 | AI万卡集群整体交付流程！太详细！ | - | AI 论文精读 | - | - | 22:04 | [link](https://www.bilibili.com/video/BV1JMYbzjE1b) |
| 1833 | GPU万卡集群交付的测试步骤有哪些？应该怎么交付？ | - | AI 论文精读 | - | - | 9:36 | [link](https://www.bilibili.com/video/BV1jneqzPEsn) |
| 1834 | GPU万卡集群如何进行测试！线性度、模型性能、通信带宽意味什么？！ | - | AI 论文精读 | - | - | 14:25 | [link](https://www.bilibili.com/video/BV116eqzJE8a) |
| 1835 | GPU万卡集群交付实践总结！全是精华！ | - | AI 论文精读 | - | - | 10:01 | [link](https://www.bilibili.com/video/BV1Uveqz9EGw) |
| 1836 | 【AI 集群】英伟达 Blackwell 产品演进分析 | - | AI 论文精读 | - | - | 19:42 | [link](https://www.bilibili.com/video/BV1iT6TYXE25) |
| 1837 | 【AI 集群】英伟达 Blackwell 深度解读 | - | AI 论文精读 | - | - | 21:01 | [link](https://www.bilibili.com/video/BV1EczyYbEfE) |
| 1838 | 【AI 集群】英伟达 GB200 网络演进深度解读 | - | AI 论文精读 | - | - | 18:37 | [link](https://www.bilibili.com/video/BV1Vgi2YJEk7) |
| 1839 | 【AI 集群】英伟达 GB200 集群互联方案 | - | AI 论文精读 | - | - | 32:03 | [link](https://www.bilibili.com/video/BV1uaiXYbE5h) |
| 1840 | 【AI 集群】xAI世界最大10万卡GPU集群解读 | - | AI 论文精读 | - | - | 14:05 | [link](https://www.bilibili.com/video/BV1Mui6YdE6s) |
| 1841 | 【AI 集群】建设对十万卡 AI 集群深度思考与反思！ | - | AI 论文精读 | - | - | 17:49 | [link](https://www.bilibili.com/video/BV16MqsYNExP) |
| 1842 | AI 服务器爆炸图鉴！了解 AI 服务器/GPU服务器长什么样子！ | - | AI 论文精读 | - | - | 24:47 | [link](https://www.bilibili.com/video/BV1DktBzLEvb) |
| 1843 | 为什么GPU和 AI 服务器风冷仍然是主流？ | - | AI 论文精读 | - | - | 21:24 | [link](https://www.bilibili.com/video/BV1mftyzZEB9) |
| 1844 | AI时代为什么需要液冷？液冷技术发展剖析 | - | AI 论文精读 | - | - | 24:41 | [link](https://www.bilibili.com/video/BV1EvtYz1EXF) |
| 1845 | AI集群液冷实践与思考！带你走进液冷的核心知识区！ | - | AI 论文精读 | - | - | 20:09 | [link](https://www.bilibili.com/video/BV1FjbMz1E7u) |
| 1846 | AI机柜、服务器机柜爆炸图鉴！ | - | AI 论文精读 | - | - | 12:21 | [link](https://www.bilibili.com/video/BV1DwtSzGE7Q) |
| 1847 | AI集群GPU集群供电和配电系统！ | - | AI 论文精读 | - | - | 20:29 | [link](https://www.bilibili.com/video/BV1UHtZzhEYJ) |
| 1848 | 新专题！什么是集群计算？超算、AI智能、数据中心的区别是什么？ | - | AI 论文精读 | - | - | 21:40 | [link](https://www.bilibili.com/video/BV1s5KfzzEbo) |
| 1849 | 通过超算硬件发展趋势看AIInfra基础设施的未来！ | - | AI 论文精读 | - | - | 32:24 | [link](https://www.bilibili.com/video/BV16A3wzEELU) |
| 1850 | 深度剖析HPC基础软件和应用的发展趋势！窥探AIInfra基础软件！ | - | AI 论文精读 | - | - | 23:19 | [link](https://www.bilibili.com/video/BV1Sr3YzXEQa) |
| 1851 | 集群计算HPC历史发展历程！回顾大型机到微型机时代！ | - | AI 论文精读 | - | - | 19:42 | [link](https://www.bilibili.com/video/BV1vugAzgEMK) |
| 1852 | 集群计算的发展历程（下集）！从云到 AI 智算中心！ | - | AI 论文精读 | - | - | 23:18 | [link](https://www.bilibili.com/video/BV14kgizdEmc) |
| 1853 | AIInfra分层介绍！了解AIInfra怎么分层就看这个视频！ | - | AI 论文精读 | - | - | 36:16 | [link](https://www.bilibili.com/video/BV1C28dzWErf) |
| 1854 | 通过AI集群建设，看AI Infra的5层系统架构！学AI Infra就看这里！ | - | AI 论文精读 | - | - | 20:03 | [link](https://www.bilibili.com/video/BV1KD8zz2EeP) |
| 1855 | 为什么大模型都用Transformer结构？ #AIInfra #大模型 #Transformer | - | AI 论文精读 | - | - | 25:48 | [link](https://www.bilibili.com/video/BV1rt421476q) |
| 1856 | 大模型输入长什么样子？大模型Tokenizer核心算法原理全解析！ | - | AI 论文精读 | - | - | 30:17 | [link](https://www.bilibili.com/video/BV16pTJz9EV4) |
| 1857 | 大模型Embedding整明白了！RoPE位置编码真简单！ | - | AI 论文精读 | - | - | 18:21 | [link](https://www.bilibili.com/video/BV1SSTgzLEzf) |
| 1858 | Attention注意力才是大模型核心，一文讲明白Transformer本质！ | - | AI 论文精读 | - | - | 25:19 | [link](https://www.bilibili.com/video/BV11AMHzuEet) |
| 1859 | Attention变种GQA、MLA、MQA都有什么区别？终于清晰啦 | - | AI 论文精读 | - | - | 25:50 | [link](https://www.bilibili.com/video/BV1GzMUz8Eav) |
| 1860 | Transformer长序列新架构介绍！NSA\MOBA\LongTransfer\TransformerXL都来了！ | - | AI 论文精读 | - | - | 20:28 | [link](https://www.bilibili.com/video/BV16PN6z6ELg) |
| 1861 | 大模型参数应该怎么设置？一个视频搞清楚！系列最核心！ | - | AI 论文精读 | - | - | 25:09 | [link](https://www.bilibili.com/video/BV1nTNkzjE3J) |
| 1862 | 大模型整体架构、大模型全流程介绍 #大模型 #AI系统 | - | AI 论文精读 | - | - | 17:00 | [link](https://www.bilibili.com/video/BV1a34y137zi) |
| 1863 | 大模型整体架构、大模型全流程介绍 #大模型 #AI系统 | - | AI 论文精读 | - | - | 18:15 | [link](https://www.bilibili.com/video/BV1F34y1G7Fz) |
| 1864 | 大模型AI集群训练时间 & 训练效率如何计算？ #大模型 #AI系统 | - | AI 论文精读 | - | - | 15:44 | [link](https://www.bilibili.com/video/BV1YN4y1Z7RU) |
| 1865 | 大模型AI集群如何组成？AI集群需要哪些硬件？ #大模型 #AI系统 | - | AI 论文精读 | - | - | 14:58 | [link](https://www.bilibili.com/video/BV1dC4y1d7hd) |
| 1866 | 大模型在AI集群分布式架构：参数服务器 or 集合通信架构？ #大模型 #AI系统 | - | AI 论文精读 | - | - | 11:48 | [link](https://www.bilibili.com/video/BV1384y127iP) |
| 1867 | 大模型训练需要多少GPU？大模型显存怎么算？ #大模型 #AI系统 | - | AI 论文精读 | - | - | 19:20 | [link](https://www.bilibili.com/video/BV15Q4y147Uo) |
| 1868 | 大模型推理需要多大的显存？ #大模型 #AI系统 #推理 #显存 | - | AI 论文精读 | - | - | 18:25 | [link](https://www.bilibili.com/video/BV1Rc411S7jj) |
| 1869 | NPU与GPU间为什么会有精度误差？！ | - | AI 论文精读 | - | - | 19:11 | [link](https://www.bilibili.com/video/BV1wGE9zSE1C) |
| 1870 | 一个视频就讲清楚 MCP 是什么！ | - | AI 论文精读 | - | - | 26:11 | [link](https://www.bilibili.com/video/BV1c97ozsEt9) |
| 1871 | 看MCP Server代码，了解大模型跟MCP如何协同！ | - | AI 论文精读 | - | - | 28:31 | [link](https://www.bilibili.com/video/BV11MEHzwEp6) |
| 1872 | DeepSeek MoE把价格打下来核心原因？看MoE架构剖析！ | - | AI 论文精读 | - | - | 28:41 | [link](https://www.bilibili.com/video/BV17PNtekE3Y) |
| 1873 | MoE架构的前世今生，MoE经典论文串烧和MoE可视化！ | - | AI 论文精读 | - | - | 30:39 | [link](https://www.bilibili.com/video/BV1y7wZeeE96) |
| 1874 | MOE奠基论文走读，Adaptive Mixtures of Local Experts！ | - | AI 论文精读 | - | - | 10:22 | [link](https://www.bilibili.com/video/BV1MiAYeuETj) |
| 1875 | MOE初遇RNN论文走读，Outrageously Large Neural Networks！ | - | AI 论文精读 | - | - | 23:49 | [link](https://www.bilibili.com/video/BV1RYAjeKE3o) |
| 1876 | MOE经典论文GShard解读，MoE 迎来Transformer时代！ | - | AI 论文精读 | - | - | 25:57 | [link](https://www.bilibili.com/video/BV1r8ApeaEyW) |
| 1877 | Switch Transformer经典论文解读！ | - | AI 论文精读 | - | - | 21:28 | [link](https://www.bilibili.com/video/BV1UsPceJEEQ) |
| 1878 | MOE经典论文ST-MOE和GLaM，如何解决MOE训练稳定性问题！ | - | AI 论文精读 | - | - | 21:16 | [link](https://www.bilibili.com/video/BV1L59qYqEVw) |
| 1879 | DeepSeekMOE论文走读，DeepSeek开山之作，共享专家原理！ | - | AI 论文精读 | - | - | 15:08 | [link](https://www.bilibili.com/video/BV1tE9HYUEdz) |
| 1880 | MOE终于迎来可视化解读！傻瓜都能看懂MoE核心原理！ | - | AI 论文精读 | - | - | 30:16 | [link](https://www.bilibili.com/video/BV1Gj9ZYdE4N) |
| 1881 | MoE遇到大模型，到底选大参数少专家还是？小参数多专家呢？ | - | AI 论文精读 | - | - | 20:22 | [link](https://www.bilibili.com/video/BV1UERNYqEwU) |
| 1882 | 使用昇腾NPU手撕MoE单机版代码！没想到如此简单！ | - | AI 论文精读 | - | - | 19:39 | [link](https://www.bilibili.com/video/BV1UTRYYUE5o) |
| 1883 | 使用昇腾NPU实现单机8卡MoE通信！手把手教你写代码！ | - | AI 论文精读 | - | - | 27:51 | [link](https://www.bilibili.com/video/BV1JaR5YSEMN) |
| 1884 | 视觉也用MoE？一起分析 V-MoE 和 Soft-MoE！ | - | AI 论文精读 | - | - | 15:19 | [link](https://www.bilibili.com/video/BV1JNQVYBEq7) |
| 1885 | DeepSeek V3深度解读，炸开美国资本市场，10/1算力训练大模型！ | - | AI 论文精读 | - | - | 26:52 | [link](https://www.bilibili.com/video/BV1hRcGemErK) |
| 1886 | DeepSeek-R1深度解读，大模型+强化学习重挫英伟达！ | - | AI 论文精读 | - | - | 29:50 | [link](https://www.bilibili.com/video/BV1dHw4e8E3e) |
| 1887 | DeepSeek春节核弹解读，多模态大模型JanusPro到底如何？ | - | AI 论文精读 | - | - | 26:19 | [link](https://www.bilibili.com/video/BV1d8P1e9EtC) |
| 1888 | DeepSeek开源 Day1：FlashMLA深度解读，分块MLA利用Flash显存！ | - | AI 论文精读 | - | - | 38:20 | [link](https://www.bilibili.com/video/BV1P9PeezEkx) |
| 1889 | DeepSeek开源Day2：DeepEP 原理，NVSHMEM实现All2All通信！ | - | AI 论文精读 | - | - | 22:27 | [link](https://www.bilibili.com/video/BV1bN9PYeEak) |
| 1890 | DeepSeek开源Day2：DeepEP代码走读！ | - | AI 论文精读 | - | - | 35:18 | [link](https://www.bilibili.com/video/BV1EwXSYgEMx) |
| 1891 | DeepSeek开源一周大串烧，对行业和大模型带来哪些变化和冲击？ | - | AI 论文精读 | - | - | 23:23 | [link](https://www.bilibili.com/video/BV11W9hYKEGj) |
| 1892 | 全网最详细：SORA视频生成大模型原理剖析 #大模型 #OpenAI #SORA | - | AI 论文精读 | - | - | 38:12 | [link](https://www.bilibili.com/video/BV1Bx4y1k7BQ) |
| 1893 | 全网最详细：OpenAI GPT-4o多模态大模型深度解读 #大模型 #OpenAI #GPT-4o | - | AI 论文精读 | - | - | 35:44 | [link](https://www.bilibili.com/video/BV1Uy411Y76z) |
| 1894 | OpenAI o1大模型炸了，数学逻辑推导能力堪比博士！ #大模型 #OpenAI | - | AI 论文精读 | - | - | 29:00 | [link](https://www.bilibili.com/video/BV1QetAesERe) |
| 1895 | 从谷歌最新大模型GEMMA看24年大模型发展趋势 #AIInfra #大模型 #Transformer | - | AI 论文精读 | - | - | 13:58 | [link](https://www.bilibili.com/video/BV1kC411H7cz) |
| 1896 | 绷不住了，大模型居然都免费了！ 对产业带来什么影响？ #大模型 #GPT4 | - | AI 论文精读 | - | - | 29:07 | [link](https://www.bilibili.com/video/BV1zM4m1m7Qa) |
| 1897 | 开源 vs 闭源大模型之争，LLAMA3.1 开源引起的血案！#大模型 #LLAMA3 #开源 | - | AI 论文精读 | - | - | 21:18 | [link](https://www.bilibili.com/video/BV1ZZ421N7Af) |
| 1898 | LLAMA3.1 全球最大开源大模型 405B 详细解读！#大模型 #llama | - | AI 论文精读 | - | - | 25:43 | [link](https://www.bilibili.com/video/BV1Xf421v7Go) |
| 1899 | 从KIMI 200万中文长序列看24年大模型发展趋势 #AIInfra #大模型 #KIMI | - | AI 论文精读 | - | - | 21:25 | [link](https://www.bilibili.com/video/BV1Fx421D7Je) |
| 1900 | KIMI K1.5深度解读，DeepSeek R1国内竞品到底如何？ | - | AI 论文精读 | - | - | 36:24 | [link](https://www.bilibili.com/video/BV1goNAecE5W) |
| 1901 | KIMI Loooooooong超长序列核心技术MoBA，掌握核心大模型原理？ | - | AI 论文精读 | - | - | 30:29 | [link](https://www.bilibili.com/video/BV1J1PGevEPb) |
| 1902 | 回顾AI历史10年：从AlexNet到大模型爆发，算法、芯片、AI创业变化！ | - | AI 论文精读 | - | - | 16:25 | [link](https://www.bilibili.com/video/BV1pDNferEEW) |
| 1903 | 时光倒流2024：多模态觉醒，幻方独占鳌头！ | - | AI 论文精读 | - | - | 13:39 | [link](https://www.bilibili.com/video/BV11KFtekE5X) |
| 1904 | 时光倒流2023：大模型元年，全球百模大战！ | - | AI 论文精读 | - | - | 12:20 | [link](https://www.bilibili.com/video/BV1kGFteBE2z) |
| 1905 | 时光倒流2022：ChatGPT发布，低迷AI迎来春天！ | - | AI 论文精读 | - | - | 11:55 | [link](https://www.bilibili.com/video/BV1jUFQewEze) |
| 1906 | 时光倒流2021：AI4SCI登顶 Science，大模型爆发前夕！ | - | AI 论文精读 | - | - | 10:50 | [link](https://www.bilibili.com/video/BV1cKFde7Ez9) |
| 1907 | 时光倒流2020：OpenAI GPT3发布，MuZero登顶Science封面！ | - | AI 论文精读 | - | - | 9:44 | [link](https://www.bilibili.com/video/BV193F6eoEaS) |
| 1908 | 时光倒流2019：BERT发布迎来NLP最大突破，GPT当年竞品！ | - | AI 论文精读 | - | - | 13:48 | [link](https://www.bilibili.com/video/BV1YvPReGEcj) |
| 1909 | 时光倒流2018：AI芯片遍地开花，英伟达硬件狂飙！ | - | AI 论文精读 | - | - | 12:29 | [link](https://www.bilibili.com/video/BV1mzNVeHEHy) |
| 1910 | 时光倒流2017：Transformer架构提出，大模型一切基础！ | - | AI 论文精读 | - | - | 10:40 | [link](https://www.bilibili.com/video/BV1iNNUeaENt) |
| 1911 | 时光倒流2016：深度强化学习AlphaGo战胜围棋大师！ | - | AI 论文精读 | - | - | 6:02 | [link](https://www.bilibili.com/video/BV1L5NaeHEv1) |
| 1912 | 时光倒流2015：ResNet提出&OpenAI创立，AI爆发前夕！ | - | AI 论文精读 | - | - | 6:30 | [link](https://www.bilibili.com/video/BV12MN6etEvp) |
| 1913 | 时光倒流2014：12年到14年AlexNet与ImageNet引起AI爆发！ | - | AI 论文精读 | - | - | 9:08 | [link](https://www.bilibili.com/video/BV18gKEe6ECd) |
| 1914 | WWDC2024 深度解读苹果 AI 技术! #WWDC #苹果 #大模型 | - | AI 论文精读 | - | - | 28:28 | [link](https://www.bilibili.com/video/BV1YH4y1w7WQ) |
| 1915 | NVIDIA CES 2025洞察，大型芯片发布和DIGITS小型机太香了！ | - | AI 论文精读 | - | - | 22:05 | [link](https://www.bilibili.com/video/BV1vjczebESC) |
| 1916 | NVIDIA COSMOS世界模型深度剖析，跟SORA什么区别？ | - | AI 论文精读 | - | - | 35:20 | [link](https://www.bilibili.com/video/BV18hwLeREUK) |
| 1917 | 英伟达NVIDIA创业20年坎坷之路，差点公司都丢掉 | - | AI 论文精读 | - | - | 7:38 | [link](https://www.bilibili.com/video/BV1FN411r7BW) |
| 1918 | 大模型时代需要AI安全吗？APPLE推出Swith HE同态加密有什么用？ | - | AI 论文精读 | - | - | 13:14 | [link](https://www.bilibili.com/video/BV1gmBuYjEhD) |
| 1919 | AI 需要安全吗？AI 安全有哪些技术？对隐私计算技术全分析！ | - | AI 论文精读 | - | - | 25:11 | [link](https://www.bilibili.com/video/BV1AecAe3Err) |
| 1920 | 【大模型推理】大模型推理整体知识，大模型推理必看指南 | - | AI 论文精读 | - | - | 6:48 | [link](https://www.bilibili.com/video/BV1dyqDYvEv2) |
| 1921 | 【大模型推理】大模型推理 Prefill 和 Decoder 阶段详解 | - | AI 论文精读 | - | - | 18:37 | [link](https://www.bilibili.com/video/BV1nHqgYFEcq) |
| 1922 | 【大模型推理】大模型业界常用推理框架怎么选？ | - | AI 论文精读 | - | - | 20:58 | [link](https://www.bilibili.com/video/BV16yqeYhELh) |
| 1923 | 三贱客，瞎聊什么是多模态大模型！ | - | AI 论文精读 | - | - | 5:52 | [link](https://www.bilibili.com/video/BV1DSxQeDETh) |
| 1924 | 有人能告诉我具身智能是什么吗？ #大模型 #具身智能 #机器人 | - | AI 论文精读 | - | - | 18:07 | [link](https://www.bilibili.com/video/BV1Yk4ZeyE1B) |
| 1925 | 具身智能技术路线详细讲解！大白话具身智能！ #大模型 #具身智能 #机器人 | - | AI 论文精读 | - | - | 22:45 | [link](https://www.bilibili.com/video/BV1F8taeDEFP) |
| 1926 | 具身智能的信息平权！聊聊具身产业观点！ #大模型 #具身智能 #机器人 | - | AI 论文精读 | - | - | 19:40 | [link](https://www.bilibili.com/video/BV1M2tje9EG4) |
| 1927 | NCCL/HCCL 的基础 MPI 通信介绍！#大模型 #集合通信 #MPI | - | AI 论文精读 | - | - | 13:29 | [link](https://www.bilibili.com/video/BV1Di421h7u2) |
| 1928 | 业界集合通信库XCCL大串烧(基本介绍)上篇 #大模型 #集合通信 #NCCL | - | AI 论文精读 | - | - | 11:11 | [link](https://www.bilibili.com/video/BV1o4421U7mo) |
| 1929 | 业界集合通信库XCCL大串烧(基本介绍)下篇 #大模型 #集合通信 #NCCL | - | AI 论文精读 | - | - | 10:44 | [link](https://www.bilibili.com/video/BV1bS421X7uN) |
| 1930 | 了解英伟达NCCL通信库一个视频就够 #大模型 #集合通信 #NCCL | - | AI 论文精读 | - | - | 19:01 | [link](https://www.bilibili.com/video/BV1SWpXe2Epa) |
| 1931 | 英伟达NCCL通信库到底怎么用！ #大模型 #集合通信 #NCCL | - | AI 论文精读 | - | - | 14:37 | [link](https://www.bilibili.com/video/BV1BnpPesE5B) |
| 1932 | 终于搞清楚通信算法与网络拓扑啥关系了！#大模型 #集合通信 #NCCL | - | AI 论文精读 | - | - | 11:58 | [link](https://www.bilibili.com/video/BV1DaHDezEcs) |
| 1933 | 万卡集群通信优化算法双二叉树！ #大模型 #集合通信 #NCCL | - | AI 论文精读 | - | - | 16:13 | [link](https://www.bilibili.com/video/BV1zSpnezEB8) |
| 1934 | 华为HCCL 集合通信库开源(放)啦！难得呀！ #大模型 #集合通信 #NCCL | - | AI 论文精读 | - | - | 21:17 | [link](https://www.bilibili.com/video/BV1wB4aeHEGM) |
| 1935 | XCCL网络建模了解对大模型通信的影响 #大模型 #集合通信 #NCCL | - | AI 论文精读 | - | - | 11:50 | [link](https://www.bilibili.com/video/BV1JkptetEJh) |
| 1936 | 推荐技术迎来 E2E 大变革时代！#大模型 #生成式推荐 #推荐系统 | - | AI 论文精读 | - | - | 27:07 | [link](https://www.bilibili.com/video/BV1BHpBeQEmR) |
| 1937 | 萝卜快跑技术解读！端到端自动驾驶？ #萝卜快跑 #自动驾驶 #端到端 | - | AI 论文精读 | - | - | 17:03 | [link](https://www.bilibili.com/video/BV1G4421S7Qa) |
| 1938 | 端到端自动驾驶算法综述 #特斯拉 #自动驾驶 #端到端 | - | AI 论文精读 | - | - | 18:40 | [link](https://www.bilibili.com/video/BV1xi421a7er) |
| 1939 | 大模型的集合通信内容介绍 #大模型 #通信 #集合通信 | - | AI 论文精读 | - | - | 8:30 | [link](https://www.bilibili.com/video/BV1jz421h7CA) |
| 1940 | 为什么需要集合通信？NCCL的架构是什么样？ #大模型 #通信 #集合通信 | - | AI 论文精读 | - | - | 16:00 | [link](https://www.bilibili.com/video/BV18J4m1G7UU) |
| 1941 | 集合通信的操作/原语/算子是什么？ #大模型 #通信 #集合通信 | - | AI 论文精读 | - | - | 17:28 | [link](https://www.bilibili.com/video/BV1gS411K7k5) |
| 1942 | AI 对集合通信算法的诉求有什么？集合通信算法是啥？ #大模型 #通信 #集合通信 | - | AI 论文精读 | - | - | 18:17 | [link](https://www.bilibili.com/video/BV1g7421d7bN) |
| 1943 | 大模型并行的集合通信算法具体实现细节纰漏！#大模型 #集合通信 | - | AI 论文精读 | - | - | 22:08 | [link](https://www.bilibili.com/video/BV1fm421G7KK) |
| 1944 | 通信域是什么概念？PyTorch 如何实现集合通信？#大模型 #集合通信 | - | AI 论文精读 | - | - | 17:04 | [link](https://www.bilibili.com/video/BV1VZ421g7jY) |
| 1945 | 研究大模型在 AI 集群的通信，还要了解芯片内互联技术？Yes！#大模型 #集合通信 | - | AI 论文精读 | - | - | 14:07 | [link](https://www.bilibili.com/video/BV1jy411z7tg) |
| 1946 | 终于到了大模型集群互联，看昇腾Atlas 900集群细节！#大模型 #集合通信 | - | AI 论文精读 | - | - | 22:18 | [link](https://www.bilibili.com/video/BV1Wz421q7SV) |
| 1947 | 壁仞BR100是全球最强算力？反正我不信【AI芯片】国产厂商 | - | AI 论文精读 | - | - | 17:12 | [link](https://www.bilibili.com/video/BV1QW4y1S75Y) |
| 1948 | 壁仞BR100全球最强算力？架构解读来啦【AI芯片】国产厂商 | - | AI 论文精读 | - | - | 17:54 | [link](https://www.bilibili.com/video/BV1G14y1275T) |
| 1949 | 燧原科技搞AI芯片怎么样？邃思2.0芯片【AI芯片】国产厂商03 | - | AI 论文精读 | - | - | 13:36 | [link](https://www.bilibili.com/video/BV15W4y1Z7Hj) |
| 1950 | 寒武纪:AI芯片第一股,能否支撑千亿市值?【AI系统】国产AI芯片 | - | AI 论文精读 | - | - | 18:14 | [link](https://www.bilibili.com/video/BV1Y8411m7Cd) |
| 1951 | 寒武纪AI芯片第一股，芯片架构解读【AI系统】国产AI芯片 | - | AI 论文精读 | - | - | 8:18 | [link](https://www.bilibili.com/video/BV1op4y157Qf) |
| 1952 | 寒武纪AI芯片第一股，芯片架构解读【AI系统】国产AI芯片 | - | AI 论文精读 | - | - | 11:49 | [link](https://www.bilibili.com/video/BV1TV411j7Yx) |
| 1953 | 再不了解昇腾 AI服务器就要被公关掉了，随时删库跑路！ #大模型 #昇腾 #AI芯片 | - | AI 论文精读 | - | - | 20:13 | [link](https://www.bilibili.com/video/BV1yb421J7Jk) |
| 1954 | 你居然？敢说昇腾310/910 SOC处理器架构！#昇腾 #AI芯片 | - | AI 论文精读 | - | - | 17:39 | [link](https://www.bilibili.com/video/BV1Ls421M7t1) |
| 1955 | 昇腾的达芬奇内核架构，终于有人说明白了！#昇腾 #AI芯片 | - | AI 论文精读 | - | - | 23:28 | [link](https://www.bilibili.com/video/BV1HM4m1U76m) |
| 1956 | 昇腾AICore快速计算矩阵的秘密被打开了！#昇腾 #AI芯片 | - | AI 论文精读 | - | - | 17:07 | [link](https://www.bilibili.com/video/BV1v6421Z78u) |
| 1957 | 大模型是怎么训起来的？分布式并行框架介绍 #大模型 #分布式并行 #训练 | - | AI 论文精读 | - | - | 12:43 | [link](https://www.bilibili.com/video/BV1op421C7wp) |
| 1958 | 分布式并行框架DeepSpeed介绍 #大模型 #分布式并行 #训练 | - | AI 论文精读 | - | - | 15:06 | [link](https://www.bilibili.com/video/BV1tH4y1J7bm) |
| 1959 | DeepSpeed优化器并行ZeRO1/2/3原理 #大模型 #分布式并行 #训练 | - | AI 论文精读 | - | - | 20:42 | [link](https://www.bilibili.com/video/BV1fb421t7KN) |
| 1960 | 分布式训练框架Megatron-LM代码概览 #大模型 #分布式并行 #训练 | - | AI 论文精读 | - | - | 20:04 | [link](https://www.bilibili.com/video/BV12J4m1K78y) |
| 1961 | 分布式PTD多维并行与GPU集群关系 #大模型 #分布式并行 #分布式训练 | - | AI 论文精读 | - | - | 15:22 | [link](https://www.bilibili.com/video/BV1NH4y1g7w4) |
| 1962 | 大模型PTD并行后如何配置在GPU集群？ #大模型 #分布式并行 #分布式训练 | - | AI 论文精读 | - | - | 14:50 | [link](https://www.bilibili.com/video/BV1ji421C7jH) |
| 1963 | Megatron-LM张量并行的行切分和列切分核心原理 #大模型 #分布式并行 #分布式训练 | - | AI 论文精读 | - | - | 19:39 | [link](https://www.bilibili.com/video/BV1yw4m1S71Y) |
| 1964 | Megatron-LM 张量并行 TP 代码剖析 #大模型 #分布式并行 #分布式训练 | - | AI 论文精读 | - | - | 22:06 | [link](https://www.bilibili.com/video/BV1cy411Y7B9) |
| 1965 | Megatron-LM 序列并行 SP 代码剖析 #大模型 #分布式并行 #分布式训练 | - | AI 论文精读 | - | - | 22:14 | [link](https://www.bilibili.com/video/BV1EM4m1r7tm) |
| 1966 | 流水并行 PP 基本原理(Gpipe原理) #大模型 #分布式并行 #分布式训练 | - | AI 论文精读 | - | - | 12:30 | [link](https://www.bilibili.com/video/BV18f42197Sx) |
| 1967 | 流水并行 PP 基本原理(1F1B、1F1B Interleaved原理) #大模型 #分布式并行 #分布式训练 | - | AI 论文精读 | - | - | 16:58 | [link](https://www.bilibili.com/video/BV1aD421g7yZ) |
| 1968 | Megatron-LM 流水并行PP代码解析 #大模型 #分布式并行 #分布式训练 | - | AI 论文精读 | - | - | 19:33 | [link](https://www.bilibili.com/video/BV1hs421g7vN) |
| 1969 | Yann Lecun主推JEPA世界模型详细解读 #大模型 #世界模型 #sora | - | AI 论文精读 | - | - | 14:10 | [link](https://www.bilibili.com/video/BV1v1421Q73e) |
| 1970 | 谷歌世界模型Genie详细解读 #大模型 #世界模型 #SORA #Geine | - | AI 论文精读 | - | - | 15:33 | [link](https://www.bilibili.com/video/BV1b6421F7Tq) |
| 1971 | SORA真的是世界模型？什么是世界模型？ #大模型 #世界模型 #SORA | - | AI 论文精读 | - | - | 14:22 | [link](https://www.bilibili.com/video/BV1GZ421t7jr) |
| 1972 | SORA如何引爆世界模型之争？ #大模型 #世界模型 #SORA | - | AI 论文精读 | - | - | 9:32 | [link](https://www.bilibili.com/video/BV1dH4y1p7zt) |
| 1973 | 特斯拉Tesla DOJO芯片架构【AI芯片】NPU详解01 | - | AI 论文精读 | - | - | 14:28 | [link](https://www.bilibili.com/video/BV1Ro4y1M7n8) |
| 1974 | 特斯拉Tesla DOJO Core(存算一体架构)核心介绍【AI芯片】NPU详解02 | - | AI 论文精读 | - | - | 16:35 | [link](https://www.bilibili.com/video/BV17o4y1N7Yn) |
| 1975 | 特斯拉DOJO存算系统是怎么工作的？【AI芯片】NPU详解03 | - | AI 论文精读 | - | - | 16:36 | [link](https://www.bilibili.com/video/BV1Ez4y1e7zo) |
| 1976 | Google TPU芯片系列概览和历史发展【AI芯片】TPU系列01 | - | AI 论文精读 | - | - | 16:37 | [link](https://www.bilibili.com/video/BV1Dp4y1V7PF) |
| 1977 | Google TPUV1 脉动阵列原理【AI芯片】TPU系列02 | - | AI 论文精读 | - | - | 18:05 | [link](https://www.bilibili.com/video/BV12P411W7YC) |
| 1978 | 世界第一块AI训练芯片(Google TPUv2)的原理【AI芯片】TPU系列03 | - | AI 论文精读 | - | - | 15:36 | [link](https://www.bilibili.com/video/BV1x84y1f7Ex) |
| 1979 | 超级计算节点TPU POD介绍 #AI芯片 #TPU系列 #超算中心 | - | AI 论文精读 | - | - | 15:19 | [link](https://www.bilibili.com/video/BV1Pm4y1g7MG) |
| 1980 | AI集群超级互联Google TPUv4 #AI芯片 #TPU系列 #AI集群 | - | AI 论文精读 | - | - | 13:23 | [link](https://www.bilibili.com/video/BV1QH4y1X77U) |
| 1981 | AI集群超级互联Google TPUv4 光交换机 #AI芯片 #TPU系列 #AI集群 | - | AI 论文精读 | - | - | 16:45 | [link](https://www.bilibili.com/video/BV1yc411o7cQ) |
| 1982 | 地表最强推理芯片Groq原理剖析&洞察 #大模型 #Groq #推理 | - | AI 论文精读 | - | - | 40:15 | [link](https://www.bilibili.com/video/BV1jx421C7mG) |
| 1983 | 向量数据库介绍，Vector和Embedding关系 #大模型 #向量数据库 | - | AI 论文精读 | - | - | 10:58 | [link](https://www.bilibili.com/video/BV1JF4m177Wd) |
| 1984 | 向量数据库的功能、特性、发展和基本原理 #大模型 #向量数据库 | - | AI 论文精读 | - | - | 11:35 | [link](https://www.bilibili.com/video/BV1mv421C7uW) |
| 1985 | 向量数据库的技术与混合搜索系统 #大模型 #向量数据库 | - | AI 论文精读 | - | - | 8:19 | [link](https://www.bilibili.com/video/BV1pj421X7TH) |
| 1986 | RAG技术详解、向量数据库对大模型的作用 #大模型 #向量数据库 | - | AI 论文精读 | - | - | 16:38 | [link](https://www.bilibili.com/video/BV1yu4m1P7UA) |
| 1987 | 向量数据库核心：相似性搜索 #大模型 #向量数据库 | - | AI 论文精读 | - | - | 14:48 | [link](https://www.bilibili.com/video/BV1UH4y1h79F) |
| 1988 | 向量数据库相似性搜索算法：ANN、IVF、HNSW #大模型 #向量数据库 | - | AI 论文精读 | - | - | 13:38 | [link](https://www.bilibili.com/video/BV1ap421d7Hf) |
| 1989 | 向量数据库相似性搜索算法：LSH、PQ、ISV-PQ #大模型 #向量数据库 | - | AI 论文精读 | - | - | 9:57 | [link](https://www.bilibili.com/video/BV1c6421g7Xr) |
| 1990 | 向量数据库之相似度度量和过滤的方法 #大模型 #向量数据库 | - | AI 论文精读 | - | - | 9:39 | [link](https://www.bilibili.com/video/BV1pH4y1j7XD) |
| 1991 | 大模型之数据工程概述 #大模型 #数据工程 #AIInfra | - | AI 论文精读 | - | - | 6:15 | [link](https://www.bilibili.com/video/BV1dC41147er) |
| 1992 | 大模型为什么需要微调？有哪些微调方式？#大模型 #微调 | - | AI 论文精读 | - | - | 13:46 | [link](https://www.bilibili.com/video/BV1fc411m7Yt) |
| 1993 | 大模型的训练流程是什么？详解大模型预训练和微调间区别 #大模型 #微调 | - | AI 论文精读 | - | - | 11:28 | [link](https://www.bilibili.com/video/BV1994y1A7mC) |
| 1994 | AI芯片除硬件本身外，还要关注什么？【AI芯片】黄金十年 | - | AI 论文精读 | - | - | 11:18 | [link](https://www.bilibili.com/video/BV13u4y197Lw) |
| 1995 | CUDA编程好不好用，看SIMD和SIMT？#AI芯片 #SIMT #AI编程 | - | AI 论文精读 | - | - | 18:34 | [link](https://www.bilibili.com/video/BV1Kr4y1d7eW) |
| 1996 | CUDA、SIMD、SIMT、DSA什么关系？好乱呀！#GPU #CUDA #英伟达 #SIMT | - | AI 论文精读 | - | - | 13:40 | [link](https://www.bilibili.com/video/BV1WC4y1w79T) |
| 1997 | CUDA跟SIMT的硬件架构什么关系？#GPU #CUDA #英伟达 #SIMT | - | AI 论文精读 | - | - | 11:42 | [link](https://www.bilibili.com/video/BV16c41117vp) |
| 1998 | AI芯片从CUDA和NVIDIA中有哪些值得借鉴？#GPU #CUDA #英伟达 #SIMT #AI芯片 | - | AI 论文精读 | - | - | 17:48 | [link](https://www.bilibili.com/video/BV1j94y1N7qh) |
| 1999 | 关于AI芯片演进的8个思考 #GPU #CUDA #AI芯片 #英伟达 #SIMT | - | AI 论文精读 | - | - | 13:33 | [link](https://www.bilibili.com/video/BV1te411y7UC) |
| 2000 | 存储遇到大模型会有什么新架构和技术点？ #大模型 #AI系统 #数据存储 #AI集群 | - | AI 论文精读 | - | - | 8:08 | [link](https://www.bilibili.com/video/BV1H94y1J7wq) |
| 2001 | 数据存储硬件组成（RAM/Flash/Cache/HBM/SSD） #大模型 #AI系统 #数据存储 #AI集群 | - | AI 论文精读 | - | - | 11:37 | [link](https://www.bilibili.com/video/BV1fw411P7FY) |
| 2002 | 数据存储集群连接方式（DAS/SAN/NAS） #大模型 #AI系统 #数据存储 #AI集群 | - | AI 论文精读 | - | - | 8:23 | [link](https://www.bilibili.com/video/BV1SQ4y147b3) |
| 2003 | 数据的存储类型和方式(块存储/文件存储/对象存储) #大模型 #AI系统 #数据存储 #AI集群 | - | AI 论文精读 | - | - | 10:48 | [link](https://www.bilibili.com/video/BV1fa4y1Z76n) |
| 2004 | 存储遇到大模型会有哪些挑战？#大模型 #AI系统 #数据存储 #AI集群 | - | AI 论文精读 | - | - | 20:00 | [link](https://www.bilibili.com/video/BV1UG411i7SM) |
| 2005 | 大模型训练的存储优化方案(上) #大模型 #AI系统 #数据存储 #AI集群 | - | AI 论文精读 | - | - | 10:45 | [link](https://www.bilibili.com/video/BV1uw411h7B7) |
| 2006 | 大模型训练的存储优化方案(下) #大模型 #AI系统 #数据存储 #AI集群 | - | AI 论文精读 | - | - | 11:34 | [link](https://www.bilibili.com/video/BV11u4y1c7Pu) |
| 2007 | 大模型 Checkpoint 优化手段！ #大模型 #AI系统 #数据存储 #AI集群 | - | AI 论文精读 | - | - | 15:02 | [link](https://www.bilibili.com/video/BV1wM411d7cc) |
| 2008 | 存算架构的思考 #大模型 #AI系统 #数据存储 #AI集群 | - | AI 论文精读 | - | - | 5:54 | [link](https://www.bilibili.com/video/BV1kw411h74p) |
| 2009 | NVIDIA英伟达Tensor Core基本原理(上)【AI芯片】GPU架构04 | - | AI 论文精读 | - | - | 10:52 | [link](https://www.bilibili.com/video/BV1aL411a71w) |
| 2010 | NVIDIA英伟达Tensor Core架构发展(中)【AI芯片】GPU架构05 | - | AI 论文精读 | - | - | 17:27 | [link](https://www.bilibili.com/video/BV1pL41187FH) |
| 2011 | NVIDIA英伟达Tensor Core深度剖析(下)【AI芯片】GPU架构06 | - | AI 论文精读 | - | - | 14:30 | [link](https://www.bilibili.com/video/BV1oh4y1J7B4) |
| 2012 | 分布式训练和NVLink&NVSwitch关系【AI芯片】GPU详解04 | - | AI 论文精读 | - | - | 14:25 | [link](https://www.bilibili.com/video/BV1cV4y1r7Rz) |
| 2013 | 深入NVLink原理：内部结构与组网拓扑【AI芯片】GPU详解05 | - | AI 论文精读 | - | - | 15:30 | [link](https://www.bilibili.com/video/BV1uP411X7Dr) |
| 2014 | 从NVLink到NVSwitch，英伟达最黑科技【AI芯片】GPU详解06 | - | AI 论文精读 | - | - | 15:59 | [link](https://www.bilibili.com/video/BV1uM4y1n7qd) |
| 2015 | 深入GPU原理：线程和缓存关系【AI芯片】GPU原理01 | - | AI 论文精读 | - | - | 16:57 | [link](https://www.bilibili.com/video/BV1bm4y1m7Ki) |
| 2016 | 为什么AI训练使用GPU而不是CPU？【AI芯片】GPU原理02 | - | AI 论文精读 | - | - | 17:34 | [link](https://www.bilibili.com/video/BV1Ms4y1N7RL) |
| 2017 | GPU硬件架构与CUDA如何对应？【AI芯片】GPU架构01 | - | AI 论文精读 | - | - | 17:48 | [link](https://www.bilibili.com/video/BV1Kk4y1Y7op) |
| 2018 | NVIDIA十代GPU架构回顾(从Fermi费米到Volta伏特)【AI芯片】GPU架构02 | - | AI 论文精读 | - | - | 13:40 | [link](https://www.bilibili.com/video/BV1x24y1F7kY) |
| 2019 | NVIDIA十代GPU架构回顾(从Turning图灵到Hopper赫柏)【AI芯片】GPU架构03 | - | AI 论文精读 | - | - | 17:06 | [link](https://www.bilibili.com/video/BV1mm4y1C7fg) |
| 2020 | 从CPU发展和组成看并行架构！【AI芯片】芯片基础01 | - | AI 论文精读 | - | - | 13:52 | [link](https://www.bilibili.com/video/BV1tv4y1V72f) |
| 2021 | CPU的ISA指令集架构看CISC和RISC之争！【AI芯片】芯片基础02 | - | AI 论文精读 | - | - | 13:45 | [link](https://www.bilibili.com/video/BV1ro4y1W7xN) |
| 2022 | CPU计算本质：数据如何传输【AI芯片】芯片基础03 | - | AI 论文精读 | - | - | 11:57 | [link](https://www.bilibili.com/video/BV17X4y1k7eF) |
| 2023 | CPU计算时延【AI芯片】芯片基础04 | - | AI 论文精读 | - | - | 9:16 | [link](https://www.bilibili.com/video/BV1Qk4y1i7GT) |
| 2024 | 从GPU架构发展看AI【AI芯片】芯片基础05 | - | AI 论文精读 | - | - | 13:44 | [link](https://www.bilibili.com/video/BV1sM411T72Q) |
| 2025 | AI芯片技术基础【AI芯片】芯片基础06 | - | AI 论文精读 | - | - | 14:23 | [link](https://www.bilibili.com/video/BV1Rk4y1e77n) |
| 2026 | 超异构体系思考，计算体系架构变革10年【AI芯片】芯片基础07 | - | AI 论文精读 | - | - | 16:56 | [link](https://www.bilibili.com/video/BV1YM4y117VK) |
| 2027 | AI芯片涉及哪些知识？【AI芯片】内容简介 | - | AI 论文精读 | - | - | 7:56 | [link](https://www.bilibili.com/video/BV1DX4y1D7PC) |
| 2028 | 深度学习计算模式是什么？【AI芯片】AI计算体系02 | - | AI 论文精读 | - | - | 14:21 | [link](https://www.bilibili.com/video/BV17x4y1T7Cn) |
| 2029 | 轻量化和大模型的计算模式怎么理解？【AI芯片】AI计算体系03 | - | AI 论文精读 | - | - | 13:47 | [link](https://www.bilibili.com/video/BV1754y1M78X) |
| 2030 | 设计AI芯片需要关注什么指标？【AI芯片】AI计算体系04 | - | AI 论文精读 | - | - | 17:12 | [link](https://www.bilibili.com/video/BV1qL411o7S9) |
| 2031 | AI芯片主要计算方式：矩阵运算【AI芯片】AI计算体系05 | - | AI 论文精读 | - | - | 9:53 | [link](https://www.bilibili.com/video/BV1ak4y1h7mp) |
| 2032 | int8/fp16/bf16/tf32在AI芯片中什么作用？【AI芯片】AI计算体系06 | - | AI 论文精读 | - | - | 12:43 | [link](https://www.bilibili.com/video/BV1WT411k724) |
| 2033 | AI 计算体系到底是什么？【AI芯片】AI计算体系07 | - | AI 论文精读 | - | - | 8:14 | [link](https://www.bilibili.com/video/BV1j54y1T7ii) |
| 2034 | Kernel优化架构介绍！【推理引擎】Kernel优化第01篇 | - | AI 论文精读 | - | - | 5:59 | [link](https://www.bilibili.com/video/BV1Ze4y1c7Bb) |
| 2035 | 卷积优化：卷积操作基础原理！【推理引擎】Kernel优化第02篇 | - | AI 论文精读 | - | - | 13:48 | [link](https://www.bilibili.com/video/BV1No4y1e7KX) |
| 2036 | 卷积优化：Im2Col算法和组合优化算法【推理引擎】Kernel优化第03篇 | - | AI 论文精读 | - | - | 15:56 | [link](https://www.bilibili.com/video/BV1Ys4y1o7XW) |
| 2037 | 卷积优化：Winograd算法【推理引擎】Kernel优化第04篇 | - | AI 论文精读 | - | - | 14:32 | [link](https://www.bilibili.com/video/BV1vv4y1Y7sc) |
| 2038 | QNNPack之间接优化算法【推理引擎】Kernel优化第05篇 | - | AI 论文精读 | - | - | 11:53 | [link](https://www.bilibili.com/video/BV1ms4y1o7ki) |
| 2039 | 推理引擎内存布局方式【推理引擎】Kernel优化第06篇 | - | AI 论文精读 | - | - | 12:52 | [link](https://www.bilibili.com/video/BV1eX4y1X7mL) |
| 2040 | ChatGPT狂飙：GPT家族详解！【ChatGPT原理】第01篇 | - | AI 论文精读 | - | - | 15:20 | [link](https://www.bilibili.com/video/BV1kv4y1s7V7) |
| 2041 | ChatGPT狂飙：强化学习RLHF与PPO！【ChatGPT】原理第02篇 | - | AI 论文精读 | - | - | 13:43 | [link](https://www.bilibili.com/video/BV1eT411S7Yx) |
| 2042 | ChatGPT狂飙：InstructGPT解析！【ChatGPT】原理第03篇 | - | AI 论文精读 | - | - | 13:56 | [link](https://www.bilibili.com/video/BV1e24y1s7k8) |
| 2043 | 离线转换模块架构与流程！【推理引擎】离线转换系列第01篇 | - | AI 论文精读 | - | - | 14:41 | [link](https://www.bilibili.com/video/BV1724y1z7ep) |
| 2044 | 模型序列化和反序列化原理！【推理引擎】离线转换系列第02篇 | - | AI 论文精读 | - | - | 15:07 | [link](https://www.bilibili.com/video/BV13P4y167sr) |
| 2045 | 如何自定义计算图IR？【推理引擎】离线转换系列第03篇 | - | AI 论文精读 | - | - | 12:47 | [link](https://www.bilibili.com/video/BV1rx4y177R9) |
| 2046 | 模型转换技术细节！【推理引擎】离线转换系列第04篇 | - | AI 论文精读 | - | - | 5:53 | [link](https://www.bilibili.com/video/BV13341197zU) |
| 2047 | 计算图优化策略！【推理引擎】离线优化系列第01篇 | - | AI 论文精读 | - | - | 9:33 | [link](https://www.bilibili.com/video/BV1g84y1L7tF) |
| 2048 | 常量折叠与冗余节点消除优化！计算图优化Details！【推理引擎】离线优化第02篇 | - | AI 论文精读 | - | - | 13:25 | [link](https://www.bilibili.com/video/BV1fA411r7hr) |
| 2049 | 算子融合/算子替换/算子前移优化！【推理引擎】离线优化第03篇 | - | AI 论文精读 | - | - | 9:44 | [link](https://www.bilibili.com/video/BV1Qj411T7Ef) |
| 2050 | Flash Attention原理！数据布局转换与内存优化！【推理引擎】离线优化第04篇 | - | AI 论文精读 | - | - | 10:03 | [link](https://www.bilibili.com/video/BV1Ae4y1N7u7) |
| 2051 | 模型压缩架构和流程介绍！量化/剪枝/蒸馏/二值化4件套！【推理系统】模型压缩第01篇 | - | AI 论文精读 | - | - | 4:17 | [link](https://www.bilibili.com/video/BV1384y187tL) |
| 2052 | 低比特量化基本原理！【推理引擎】模型压缩系列第02篇 | - | AI 论文精读 | - | - | 13:48 | [link](https://www.bilibili.com/video/BV1VD4y1n7AR) |
| 2053 | 感知量化训练QAT原理！伪量化节点计算方式！【推理引擎】模型压缩系列第03篇 | - | AI 论文精读 | - | - | 12:08 | [link](https://www.bilibili.com/video/BV1s8411w7b9) |
| 2054 | 训练后量化PTQ深度解读！与量化部署核心原理！【推理引擎】模型压缩系列第04篇 | - | AI 论文精读 | - | - | 14:16 | [link](https://www.bilibili.com/video/BV1HD4y1n7E1) |
| 2055 | 模型剪枝核心原理！模型剪枝算法和流程介绍！Model Pruning深度解析【推理引擎】模型压缩系列第05篇 | - | AI 论文精读 | - | - | 14:22 | [link](https://www.bilibili.com/video/BV1y34y1Z7KQ) |
| 2056 | 知识蒸馏原理介绍！知识从哪里来怎么蒸馏？【推理引擎】模型压缩系列第06篇(上) | - | AI 论文精读 | - | - | 9:32 | [link](https://www.bilibili.com/video/BV1My4y197Tf) |
| 2057 | 知识蒸馏SOTA算法解读！【推理引擎】模型压缩系列第06篇(下) | - | AI 论文精读 | - | - | 13:58 | [link](https://www.bilibili.com/video/BV1vA411d7MF) |
| 2058 | 如何计算模型参数量？什么是FLOPS和MACC？【推理系统】模型小型化第01篇 | - | AI 论文精读 | - | - | 8:45 | [link](https://www.bilibili.com/video/BV1KW4y1G75J) |
| 2059 | CNN模型小型化原理！SqueezeNet/ShuffleNet/MobileNet系列介绍！【推理系统】模型小型化第02篇 | - | AI 论文精读 | - | - | 12:58 | [link](https://www.bilibili.com/video/BV1Y84y1b7xj) |
| 2060 | CNN模型小型化算法总结！ESPnet/GhostNet系列介绍！【推理系统】模型小型化第03篇 | - | AI 论文精读 | - | - | 8:36 | [link](https://www.bilibili.com/video/BV1DK411k7qt) |
| 2061 | Transformer轻量化SOTA模型原理！【推理系统】模型小型化第04篇 | - | AI 论文精读 | - | - | 17:10 | [link](https://www.bilibili.com/video/BV19d4y1V7ou) |
| 2062 | AI编译器前端"图层优化"内容概览！！【AI编译器】系列之前端优化第01篇 | - | AI 论文精读 | - | - | 3:46 | [link](https://www.bilibili.com/video/BV1ne411w7n2) |
| 2063 | 图层IR(Graph IR)是什么？AI编译器如何接收图层IR进行优化呢？【AI编译器】系列之前端优化第02篇 | - | AI 论文精读 | - | - | 11:11 | [link](https://www.bilibili.com/video/BV1kV4y1w72W) |
| 2064 | 算子融合了解下！AI编译器如何实现算子融合的？【AI编译器】系列之前端优化第03篇 | - | AI 论文精读 | - | - | 17:48 | [link](https://www.bilibili.com/video/BV1P24y1D7RV) |
| 2065 | 编译器为什么要对数据布局转换呢 Layout Transformations？【AI编译器】系列之前端优化第04篇(上) | - | AI 论文精读 | - | - | 16:29 | [link](https://www.bilibili.com/video/BV1xK411z7Uw) |
| 2066 | [概率 & 统计] KL 散度（KL div）forward vs. reverse | - | AI 论文精读 | - | - | 11:03 | [link](https://www.bilibili.com/video/BV1cT42127wg) |
| 2067 | 详解AI编译器数据布局转换方法！华为昇腾处理器的数据布局格式！【AI编译器】系列之前端优化第04篇(下) | - | AI 论文精读 | - | - | 13:54 | [link](https://www.bilibili.com/video/BV1gd4y1Y7dc) |
| 2068 | AI编译器内存优化算法！动态内存和静态内存区别！【AI编译器】前端优化第05篇 | - | AI 论文精读 | - | - | 17:09 | [link](https://www.bilibili.com/video/BV1nM411879s) |
| 2069 | 常量折叠原理！AI编译器常量折叠跟传统编译器什么关系？计算图也需要常量折叠！【AI编译器】系列之前端优化第06篇 | - | AI 论文精读 | - | - | 11:06 | [link](https://www.bilibili.com/video/BV1P8411W7dY) |
| 2070 | 编译器公共子表达式消除的方法！AI编译器消除公共子表达式【AI编译器】系列之前端优化第07篇 | - | AI 论文精读 | - | - | 8:30 | [link](https://www.bilibili.com/video/BV1rv4y1Q7tp) |
| 2071 | 编译器死代码消除的原理！AI编译器死代码消除【AI编译器】系列之前端优化第08篇 | - | AI 论文精读 | - | - | 6:24 | [link](https://www.bilibili.com/video/BV1hD4y1h7nh) |
| 2072 | 编译器的代数化简原理！AI编译器的代数化简来啦！【AI编译器】系列之前端优化第09篇 | - | AI 论文精读 | - | - | 9:30 | [link](https://www.bilibili.com/video/BV1g24y1Q7qC) |
| 2073 | AI编译器的前端优化/图优化Pass的顺序怎么排？【AI编译器】系列之前端优化第10篇 | - | AI 论文精读 | - | - | 4:58 | [link](https://www.bilibili.com/video/BV1L14y1P7ku) |
| 2074 | PyTorch 2.0新特性开撸！图模式打开了潘多拉！【AI编译器之PyTorch】系列01篇 | - | AI 论文精读 | - | - | 13:30 | [link](https://www.bilibili.com/video/BV1p84y1675B) |
| 2075 | TorchScript 解读！图模式的第一次尝试！静态图+JIT编译器！【AI编译器之PyTorch】系列02篇 | - | AI 论文精读 | - | - | 8:30 | [link](https://www.bilibili.com/video/BV1JV4y1P7gB) |
| 2076 | PyTorch静态图的TorchFX和Lazy Tensor特性解读！【AI编译器之PyTorch】系列03篇 | - | AI 论文精读 | - | - | 13:41 | [link](https://www.bilibili.com/video/BV1944y1m7fU) |
| 2077 | TorchDynamo原理来啦！PyTorch2.0编译新特性哦！【AI编译器之PyTorch】系列04篇 | - | AI 论文精读 | - | - | 14:45 | [link](https://www.bilibili.com/video/BV1jD4y1a7hx) |
| 2078 | AOTAutograd原理解读！如何获取静态反向图？【AI编译器之PyTorch】系列05篇 | - | AI 论文精读 | - | - | 10:42 | [link](https://www.bilibili.com/video/BV1Me4y1V7Ke) |
| 2079 | PyTorch Dispatcher原理！PyTorch算子注册！【AI编译器之PyTorch】系列06篇 | - | AI 论文精读 | - | - | 15:49 | [link](https://www.bilibili.com/video/BV1L3411d7SM) |
| 2080 | 什么是推理系统？推理有哪些应用？【推理系统】系列01篇 | - | AI 论文精读 | - | - | 8:23 | [link](https://www.bilibili.com/video/BV1J8411K7pj) |
| 2081 | 推理系统和推理引擎的不同之处在哪？【推理系统】系列02篇 | - | AI 论文精读 | - | - | 17:03 | [link](https://www.bilibili.com/video/BV1nY4y1f7G5) |
| 2082 | 云侧和端侧推理方式的特点和区别！【推理系统】系列03篇 | - | AI 论文精读 | - | - | 12:55 | [link](https://www.bilibili.com/video/BV1M24y1v7rK) |
| 2083 | 推理系统架构和Trition架构介绍！【推理系统】系列04篇 | - | AI 论文精读 | - | - | 14:25 | [link](https://www.bilibili.com/video/BV1Gv4y1i7Tw) |
| 2084 | 推理引擎架构介绍！MNN、TF Lite、TensorRT介绍！【推理系统】系列05篇(上) | - | AI 论文精读 | - | - | 12:47 | [link](https://www.bilibili.com/video/BV1Mx4y137Er) |
| 2085 | 推理引擎架构！MNN、TensorRT架构介绍！【推理系统】系列05篇(下) | - | AI 论文精读 | - | - | 14:15 | [link](https://www.bilibili.com/video/BV1FG4y1C7Mn) |
| 2086 | AI编译器后端优化来啦！AI编译器后端架构！【AI编译器】后端优化01篇 | - | AI 论文精读 | - | - | 13:12 | [link](https://www.bilibili.com/video/BV17D4y177bP) |
| 2087 | 如何对算子IR表示？算子是如何分开计算和调度两部分？【AI编译器】后端优化02篇 | - | AI 论文精读 | - | - | 10:19 | [link](https://www.bilibili.com/video/BV1K84y1x7Be) |
| 2088 | AI编译器后端算子优化来啦！算子优化手工方式！【AI编译器】后端优化03篇 | - | AI 论文精读 | - | - | 8:24 | [link](https://www.bilibili.com/video/BV1ZA411X7WZ) |
| 2089 | 后端算子循环优化！Loop Optimization常见方法！【AI编译器】后端优化04篇 | - | AI 论文精读 | - | - | 12:07 | [link](https://www.bilibili.com/video/BV1r14y1w7hG) |
| 2090 | 算子优化的指令和存储优化！【AI编译器】后端优化05篇 | - | AI 论文精读 | - | - | 12:59 | [link](https://www.bilibili.com/video/BV11d4y1a7J6) |
| 2091 | Auto Tuning原理！TVM的AutoTVM实现方式详解！【AI编译器】后端优化06篇 | - | AI 论文精读 | - | - | 11:55 | [link](https://www.bilibili.com/video/BV1uA411D7JF) |
| 2092 | 分布式并行策略基础介绍！【分布式并行】系列第01篇 | - | AI 论文精读 | - | - | 3:31 | [link](https://www.bilibili.com/video/BV1ve411w7DL) |
| 2093 | PyTorch数据并行怎么实现？DP、DDP、FSDP数据并行原理？【分布式并行】系列第02篇 | - | AI 论文精读 | - | - | 13:50 | [link](https://www.bilibili.com/video/BV1JK411S7gL) |
| 2094 | 什么是张量并行？张量并行的数学原理是什么？【分布式并行】系列第03篇 | - | AI 论文精读 | - | - | 16:19 | [link](https://www.bilibili.com/video/BV1vt4y1K7wT) |
| 2095 | 张量还能自动并行？MindSpore张量自动并行啥原理？【大模型与分布式训练】系列04篇 | - | AI 论文精读 | - | - | 6:12 | [link](https://www.bilibili.com/video/BV1C8411h7Q6) |
| 2096 | 模型并行的流水线并行来啦！了解下GPipe和PipeDream？【分布式并行】系列第05篇 | - | AI 论文精读 | - | - | 15:28 | [link](https://www.bilibili.com/video/BV1WD4y1t7Ba) |
| 2097 | 混合并行？多维并行？有多维度混合在一起并行吗？【分布式并行】系列第06篇 | - | AI 论文精读 | - | - | 15:33 | [link](https://www.bilibili.com/video/BV1gD4y1t7Ut) |
| 2098 | 分布式训练总结！【大模型与分布式训练】系列第07篇 | - | AI 论文精读 | - | - | 13:07 | [link](https://www.bilibili.com/video/BV1av4y1S7DQ) |
| 2099 | 为什么需要AI编译器？跟传统编译器啥关系吗？【AI编译器】系列第一篇 | - | AI 论文精读 | - | - | 10:44 | [link](https://www.bilibili.com/video/BV1pM41167KP) |
| 2100 | AI编译器架构发展！三个阶段出现的AI编译器有啥区别？【AI编译器】系列第二篇 | - | AI 论文精读 | - | - | 17:30 | [link](https://www.bilibili.com/video/BV1QK411R7iy) |
| 2101 | AI编译器啥架构来着？有多少模块？【AI编译器】系列第三篇 | - | AI 论文精读 | - | - | 8:42 | [link](https://www.bilibili.com/video/BV1qD4y1Y73e) |
| 2102 | AI编译器的挑战与未来？【AI编译器】系列第四篇 | - | AI 论文精读 | - | - | 14:31 | [link](https://www.bilibili.com/video/BV1Hv4y1R7uc) |
| 2103 | 计算图有哪些内容知识？【计算图】系列第一篇 | - | AI 论文精读 | - | - | 1:55 | [link](https://www.bilibili.com/video/BV1cG411E7gV) |
| 2104 | 为什么AI框架都用计算图？什么是计算图？到底计算图有什么用？【计算图】系列第二篇 | - | AI 论文精读 | - | - | 10:37 | [link](https://www.bilibili.com/video/BV1rR4y197HM) |
| 2105 | 计算图跟微分什么关系？怎么用计算图表示自动微分？AI框架自动微分如何通过计算图来实现？【计算图】系列第三篇 | - | AI 论文精读 | - | - | 16:45 | [link](https://www.bilibili.com/video/BV1S24y197FU) |
| 2106 | 对计算图进行优化与执行调度！计算图优化跟AI编译器啥关系？一起了解下计算图的调度执行吧！【计算图】第四篇 | - | AI 论文精读 | - | - | 10:31 | [link](https://www.bilibili.com/video/BV1hD4y1k7Ty) |
| 2107 | AI框架都是怎么表示控制流的？PyTorch和TF对计算图中控制语句如何处理？【计算图】第五篇 | - | AI 论文精读 | - | - | 15:22 | [link](https://www.bilibili.com/video/BV17P41177Pk) |
| 2108 | AI框架如何实现动静统一？PyTorch和MindSpore动静统一做得如何了？【计算图】第六篇 | - | AI 论文精读 | - | - | 7:08 | [link](https://www.bilibili.com/video/BV11M41167yX) |
| 2109 | 计算图未来将会走向何方？【计算图】第七篇 | - | AI 论文精读 | - | - | 6:50 | [link](https://www.bilibili.com/video/BV1hm4y1A7Nv) |
| 2110 | 编译器和解释器啥区别？AOT和JIT啥区别？Pass和IR又是什么？【AI编译器】系列01篇 | - | AI 论文精读 | - | - | 15:17 | [link](https://www.bilibili.com/video/BV1D84y1y73v) |
| 2111 | GCC和LLVM发家历史？两大开源编译器的爱恨情仇【AI编译器】系列第二篇 | - | AI 论文精读 | - | - | 10:41 | [link](https://www.bilibili.com/video/BV1sM411C7Vr) |
| 2112 | GCC编译过程！优缺点是啥？手把手用GCC编译一个小程序【AI编译器】系列第三篇 | - | AI 论文精读 | - | - | 9:49 | [link](https://www.bilibili.com/video/BV1LR4y1f7et) |
| 2113 | LLVM架构了解下？为什么LLVM这么火？一起初体验实操LLVM【AI编译器】系列第四篇 | - | AI 论文精读 | - | - | 15:13 | [link](https://www.bilibili.com/video/BV1CG4y1V7Dn) |
| 2114 | LLVM IR详解！LLVM编译器的核心理念来啦！【AI编译器】系列第五篇(上) | - | AI 论文精读 | - | - | 11:13 | [link](https://www.bilibili.com/video/BV1PP411u7NR) |
| 2115 | LLVM编译器前端和优化层了解下？词法语法分析、Pass优化都在这！【AI编译器】系列第五篇(中) | - | AI 论文精读 | - | - | 11:48 | [link](https://www.bilibili.com/video/BV1vd4y1t7vS) |
| 2116 | LLVM后端代码生成！了解下基于LLVM的项目！【AI编译器】系列第五篇(下) | - | AI 论文精读 | - | - | 14:26 | [link](https://www.bilibili.com/video/BV1cd4y1b7ho) |
| 2117 | 分布式训练、分布式集群的基础介绍！【分布式集群】第01篇 | - | AI 论文精读 | - | - | 7:39 | [link](https://www.bilibili.com/video/BV1ge411L7mi) |
| 2118 | AI集群用什么服务器架构？Ring All Reduce算法跟物理网络啥关系？【分布式集群】系列第02篇 | - | AI 论文精读 | - | - | 13:14 | [link](https://www.bilibili.com/video/BV1fg41187rc) |
| 2119 | AI集群的软硬件通信：从硬件PCIE、NVLINK、RDMA原理到通信NCCL、MPI原理！【分布式集群】系列第03篇 | - | AI 论文精读 | - | - | 12:15 | [link](https://www.bilibili.com/video/BV14P4y1S7u4) |
| 2120 | AI集群机器间是怎么通信？通信原语是个什么玩意？【分布式集群】系列第04篇 | - | AI 论文精读 | - | - | 9:38 | [link](https://www.bilibili.com/video/BV1te4y1e7vz) |
| 2121 | AI框架如何实现分布式训练？SISD和SIMT又是什么？【分布式集群】系列第05篇 | - | AI 论文精读 | - | - | 16:13 | [link](https://www.bilibili.com/video/BV1Y14y1576A) |
| 2122 | 大模型是什么？大模型有什么用？训练大模型会遇到哪些挑战？【分布式算法】第01篇 | - | AI 论文精读 | - | - | 13:45 | [link](https://www.bilibili.com/video/BV1n8411s7f3) |
| 2123 | 大模型算法有哪种结构？怎么样才算大模型呢？从Transformer和MOE结构看大模型发展！【分布式算法】系列第02篇 | - | AI 论文精读 | - | - | 16:06 | [link](https://www.bilibili.com/video/BV1Mt4y1M7SE) |
| 2124 | 从十亿到万亿规模SOTA大模型有哪些？BERT、GPT3、Switch算法来啦！【分布式算法】系列第03篇 | - | AI 论文精读 | - | - | 15:35 | [link](https://www.bilibili.com/video/BV1em4y1F7ay) |
| 2125 | AI框架内容介绍：AI框架基础、AI框架之争、AI编程范式！【AI框架基础】系列第一篇 | - | AI 论文精读 | - | - | 4:21 | [link](https://www.bilibili.com/video/BV1he4y1z7oD) |
| 2126 | AI框架有什么用？没有AI框架写算法又会怎么样？【AI框架基础】系列第二篇 | - | AI 论文精读 | - | - | 13:11 | [link](https://www.bilibili.com/video/BV1fd4y1q7qk) |
| 2127 | AI框架之争！都2022年，应该怎么选择AI框架？【AI框架基础】系列第三篇 | - | AI 论文精读 | - | - | 16:16 | [link](https://www.bilibili.com/video/BV1C8411x7Kn) |
| 2128 | 函数式编程和声明式编程啥区别？AI到底应该用什么编程范式？【AI框架基础】系列第四篇 | - | AI 论文精读 | - | - | 13:16 | [link](https://www.bilibili.com/video/BV1gR4y1o7WT) |
| 2129 | 想了解自动微分吗？自动微分内容介绍！【自动微分】系列第一篇！ | - | AI 论文精读 | - | - | 4:39 | [link](https://www.bilibili.com/video/BV1FV4y1T7zp) |
| 2130 | 符号微分/数值微分/自动微分区别是什么？【自动微分】系列第二篇 | - | AI 论文精读 | - | - | 10:56 | [link](https://www.bilibili.com/video/BV1Ld4y1M7GJ) |
| 2131 | 前向微分和正向微分怎么理解？微分方式跟反向传播算法啥关系？【自动微分】系列第三篇 | - | AI 论文精读 | - | - | 13:27 | [link](https://www.bilibili.com/video/BV1zD4y117bL) |
| 2132 | 自动微分是怎么实现的？Lib Base、操作符重载、源码转换不懂得快来！【自动微分】系列第四篇！ | - | AI 论文精读 | - | - | 11:51 | [link](https://www.bilibili.com/video/BV1BN4y1P76t) |
| 2133 | 亲自撸一个正向自动微分的AI框架！【自动微分】系列第五篇 | - | AI 论文精读 | - | - | 10:29 | [link](https://www.bilibili.com/video/BV1Ne4y1p7WU) |
| 2134 | 手把手实现一个PyTorch！实现PyTorch核心自动微分！【自动微分】系列第六篇 | - | AI 论文精读 | - | - | 19:53 | [link](https://www.bilibili.com/video/BV1ae4y1z7E6) |
| 2135 | 自动微分挑战和未来！自动微分易用性和性能应该如何兼容？可微编程是否未来？【自动微分】系列第七篇 | - | AI 论文精读 | - | - | 13:01 | [link](https://www.bilibili.com/video/BV17e4y1z73W) |
| 2136 | [2] 读上月新鲜出炉的综述：大模型写算子【每周一个宝藏论文】 | - | AI 论文精读 | - | - | 11:07 | [link](https://www.bilibili.com/video/BV1XcfBBGEUw) |
| 2137 | [4] 大模型写算子：一篇综述+2个数据集【每周一个宝藏论文】 | - | AI 论文精读 | - | - | 15:52 | [link](https://www.bilibili.com/video/BV1pJA6zkEH4) |
| 2138 | [6] Agent写算子：读三个Agent写算子的论文【每周一个宝藏论文】 | - | AI 论文精读 | - | - | 14:05 | [link](https://www.bilibili.com/video/BV1HVPkzEEx9) |
| 2139 | [8] 读三个强化学习写算子的论文【每周一个宝藏论文】 | - | AI 论文精读 | - | - | 16:25 | [link](https://www.bilibili.com/video/BV1fVckzqE1S) |
| 2140 | ［10］大模型写算子：读两个KernelBench的改进工作【每周一个宝藏论文】 | - | AI 论文精读 | - | - | 13:43 | [link](https://www.bilibili.com/video/BV1M8QUBUESz) |
| 2141 | ［12］读2个多Agent共享KV Cache的论文【每周一个宝藏论文】 | - | AI 论文精读 | - | - | 13:50 | [link](https://www.bilibili.com/video/BV1B997BmEGr) |
| 2142 | [14] AWQ：大语言模型量化论文解读 【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 11:29 | [link](https://www.bilibili.com/video/BV1RuoFBvEm8) |
| 2143 | [16] LLM.int8()：大模型量化论文解读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 11:58 | [link](https://www.bilibili.com/video/BV1BeoNB9EQP) |
| 2144 | [18] SmoothQuant：大模型量化论文解读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 14:17 | [link](https://www.bilibili.com/video/BV1CkoPBbEyB) |
| 2145 | [28] 模型剪枝OB家族论文一口气看完：OBD、OBS、OBC【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 21:51 | [link](https://www.bilibili.com/video/BV1bJd2BHEeb) |
| 2146 | [29] GPTQ：大模型量化论文解读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 11:48 | [link](https://www.bilibili.com/video/BV1Y3d2BoELh) |
| 2147 | [31]. OSDI 2025 LLM方向论文串讲：DecDEC、WLB_LLM、Straggler【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 26:50 | [link](https://www.bilibili.com/video/BV129ReB1EiW) |
| 2148 | [44]. AutoRound：大模型量化论文解读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 11:06 | [link](https://www.bilibili.com/video/BV1t1RrBNEEt) |
| 2149 | [107]. 微软的1.58bit量化：论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 6:19 | [link](https://www.bilibili.com/video/BV1rtME6LEfy) |
| 2150 | [163]. Deep Compression：韩松的剪枝+量化经典，论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 8:18 | [link](https://www.bilibili.com/video/BV16ath6fEA4) |
| 2151 | [178]. QuaRot：旋转矩阵消除异常值，4 比特无损推理，论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 15:28 | [link](https://www.bilibili.com/video/BV1jvep67Eoa) |
| 2152 | [180]. PyramidKV：金字塔式 KV 压缩，省显存保性能，论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 12:53 | [link](https://www.bilibili.com/video/BV1TdhB6MEm7) |
| 2153 | [15] PagedAttention：vLLM论文解读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 8:45 | [link](https://www.bilibili.com/video/BV1xJoNBPEqe) |
| 2154 | [17] FlashAttention-1论文解读 【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 16:32 | [link](https://www.bilibili.com/video/BV1XPoNB5EQy) |
| 2155 | [24] SGLang：大模型推理引擎论文解读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 12:06 | [link](https://www.bilibili.com/video/BV18Ud6BME78) |
| 2156 | [20] 投机采样：大模型推理加速论文解读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 5:49 | [link](https://www.bilibili.com/video/BV1V6d6BCEzJ) |
| 2157 | [21] 在线softmax：论文解读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 6:21 | [link](https://www.bilibili.com/video/BV1Qkd6B3EUe) |
| 2158 | [22] FlashAttention-V2：论文解读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 11:09 | [link](https://www.bilibili.com/video/BV1yfd6B8E37) |
| 2159 | [23] flash-attention-v3：论文解读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 10:45 | [link](https://www.bilibili.com/video/BV1yZd6BcE3b) |
| 2160 | [26] GQA：分组查询注意力论文解读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 5:53 | [link](https://www.bilibili.com/video/BV1Bcd2BeEVv) |
| 2161 | [27] SlimAttention：一种和FlashAttention分块策略不同的注意力【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 7:29 | [link](https://www.bilibili.com/video/BV1hjd2BWEGS) |
| 2162 | [43]. MQA：论文解读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 6:26 | [link](https://www.bilibili.com/video/BV1m1RrBNEmy) |
| 2163 | [79]. FlashAttention-4：论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 10:50 | [link](https://www.bilibili.com/video/BV1q6Js6DEwE) |
| 2164 | [99]. Medusa：投机解码和树形注意力论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 10:11 | [link](https://www.bilibili.com/video/BV1NsKQ6zENp) |
| 2165 | [98]. TurboQuant：KV Cache量化论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 10:50 | [link](https://www.bilibili.com/video/BV11sKQ6zEFj) |
| 2166 | [101]. H2O：KV缓存压缩论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 10:05 | [link](https://www.bilibili.com/video/BV1ktTc6tEce) |
| 2167 | [100]. FlashDecoding的改进：FlashDecoding++论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 8:53 | [link](https://www.bilibili.com/video/BV1rtTc6tEen) |
| 2168 | [110]. EAGLE：投机解码论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 7:37 | [link](https://www.bilibili.com/video/BV1BZMJ6CEa6) |
| 2169 | [116] Deepseek的DSpark：投机解码论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 8:32 | [link](https://www.bilibili.com/video/BV1SCK36PEGX) |
| 2170 | [179]. Orca：迭代级调度开创者，LLM 服务系统鼻祖，论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 15:40 | [link](https://www.bilibili.com/video/BV1GueP6pE7P) |
| 2171 | [25] QLora：大模型量化微调论文解读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 11:05 | [link](https://www.bilibili.com/video/BV1CFdrBfE2D) |
| 2172 | [152]. Distilling the Knowledge：知识蒸馏奠基之作，论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 7:46 | [link](https://www.bilibili.com/video/BV1cK8h6vEVW) |
| 2173 | [19] DeepSeek-V4逐图、逐公式解读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 29:02 | [link](https://www.bilibili.com/video/BV1Mgo5BwEST) |
| 2174 | [30] Deepseek-MLA、MTP解读 【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 12:01 | [link](https://www.bilibili.com/video/BV1Vgd2BtEKe) |
| 2175 | [32]. Hyper Connections：残差连接的改进【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 10:54 | [link](https://www.bilibili.com/video/BV142RrBeEa3) |
| 2176 | [33]. mHC：流形约束超连接【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 10:51 | [link](https://www.bilibili.com/video/BV1m2RrBeEFS) |
| 2177 | [35]. Deepseek-Engram：论文解读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 14:18 | [link](https://www.bilibili.com/video/BV122RrBeEfs) |
| 2178 | [37]. Adam：论文解读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 9:27 | [link](https://www.bilibili.com/video/BV142RrBeEjQ) |
| 2179 | [40]. Transformer：论文解读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 9:32 | [link](https://www.bilibili.com/video/BV1t1RrBNEwi) |
| 2180 | [46]. Muon is Scalable：Muon优化器论文解读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 11:45 | [link](https://www.bilibili.com/video/BV14N5b6YEbf) |
| 2181 | [51]. BERT：论文解读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 7:30 | [link](https://www.bilibili.com/video/BV1fXLJ6aEZ1) |
| 2182 | [52]. GPT2：论文解读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 11:58 | [link](https://www.bilibili.com/video/BV1FXLJ6YECS) |
| 2183 | [53]. GPT3：论文解读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 8:06 | [link](https://www.bilibili.com/video/BV1FXLJ6YEh4) |
| 2184 | [56]. 旋转位置编码RoPE：论文解读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 6:58 | [link](https://www.bilibili.com/video/BV1cQLJ6PEAs) |
| 2185 | [59]. MoE：论文解读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 10:49 | [link](https://www.bilibili.com/video/BV17zLC68Emq) |
| 2186 | [65]. Mamba：论文解读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 10:58 | [link](https://www.bilibili.com/video/BV1uGVK6iEh2) |
| 2187 | [67]. Dropout：论文解读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 5:08 | [link](https://www.bilibili.com/video/BV1dsG26dETn) |
| 2188 | [72]. Word2Vec：论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 5:52 | [link](https://www.bilibili.com/video/BV1Ag7m6XERk) |
| 2189 | [82]. 思维链：论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 7:27 | [link](https://www.bilibili.com/video/BV1q6Js6DEaQ) |
| 2190 | [83]. 思维树：论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 9:37 | [link](https://www.bilibili.com/video/BV176Js6DEsq) |
| 2191 | [92]. TVM：论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 12:44 | [link](https://www.bilibili.com/video/BV1kv7q6REVg) |
| 2192 | [93]. PyTorch_2：论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 7:49 | [link](https://www.bilibili.com/video/BV1kv7q6RE7a) |
| 2193 | [94]. BPE：论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 6:39 | [link](https://www.bilibili.com/video/BV1kv7q6REeS) |
| 2194 | [96]. Mamba_2：论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 7:14 | [link](https://www.bilibili.com/video/BV1Av7q6dEpF) |
| 2195 | [104]. kimi的注意力残差：论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 9:31 | [link](https://www.bilibili.com/video/BV1MRME6oEhx) |
| 2196 | [105]. TTT，一种序列模型：论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 9:39 | [link](https://www.bilibili.com/video/BV1MRME6oE3a) |
| 2197 | [106]. RWKV，一种序列模型：论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 8:01 | [link](https://www.bilibili.com/video/BV1MRME6oE2V) |
| 2198 | [108]. deepseek的NSA：论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 10:25 | [link](https://www.bilibili.com/video/BV1HtME6LEWp) |
| 2199 | [109]. AdamW：论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 7:19 | [link](https://www.bilibili.com/video/BV1eKMn6MEMr) |
| 2200 | [113]. GRU：论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 9:24 | [link](https://www.bilibili.com/video/BV1LwN36uEbV) |
| 2201 | [117]. Kimi 的混合线性注意力：论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 10:07 | [link](https://www.bilibili.com/video/BV1TUKp6hEi6) |
| 2202 | [119]. LookAhead：投机解码论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 11:11 | [link](https://www.bilibili.com/video/BV1hrKp6NEp3) |
| 2203 | [120]. Performer，线性注意力：论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 9:33 | [link](https://www.bilibili.com/video/BV1hzKp6iE1b) |
| 2204 | [115] Kimi K3 技术报告：论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 11:19 | [link](https://www.bilibili.com/video/BV1uyK36eEcT) |
| 2205 | [127]. LSTM：经典重温，论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 5:55 | [link](https://www.bilibili.com/video/BV1Qr3y6VEt4) |
| 2206 | [129]. Muon 优化器：原始技术博客，论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 5:43 | [link](https://www.bilibili.com/video/BV1hr3y6VEd6) |
| 2207 | [139]. RNN：循环神经网络经典重温，论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 7:23 | [link](https://www.bilibili.com/video/BV1KiuG6zE44) |
| 2208 | [133]. FlashDecoding：原始技术博客，论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 5:03 | [link](https://www.bilibili.com/video/BV1xBuG6MEB3) |
| 2209 | [142]. LoRA：大模型微调经典重温，论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 9:02 | [link](https://www.bilibili.com/video/BV1zxbY6vE5n) |
| 2210 | [144]. Megatron LM：大模型并行训练重要工作，论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 8:12 | [link](https://www.bilibili.com/video/BV1BxbY6vE9J) |
| 2211 | [146]. Universal_Approximators：神经网络的万能近似定理，论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 6:37 | [link](https://www.bilibili.com/video/BV1CEbY6gEHM) |
| 2212 | [148]. Diffusion LM：扩散语言模型开山之作，论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 7:45 | [link](https://www.bilibili.com/video/BV1AEbY63ETH) |
| 2213 | [150]. Seq2Seq：序列到序列经典论文，论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 8:46 | [link](https://www.bilibili.com/video/BV1Rf8J6bEDU) |
| 2214 | [151]. Switch Transformer：稀疏专家模型，论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 14:32 | [link](https://www.bilibili.com/video/BV16K8h6eE2v) |
| 2215 | [153]. Bahdanau Attention：首次将注意力用于Seq2Seq，论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 6:28 | [link](https://www.bilibili.com/video/BV1rK8h6eEGT) |
| 2216 | [154]. ZeRO：DeepSpeed 大模型显存优化，论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 10:16 | [link](https://www.bilibili.com/video/BV1B38h6cEQP) |
| 2217 | [158]. Gated Attention：NeurIPS 2025 最佳论文，给注意力加个门，论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 9:32 | [link](https://www.bilibili.com/video/BV1ULth66EHH) |
| 2218 | [159]. MoBA：Kimi 的稀疏注意力，NSA 姊妹篇，论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 9:04 | [link](https://www.bilibili.com/video/BV1ULth66EJ8) |
| 2219 | [160]. EAGLE-3：投机解码 EAGLE 的最新改进，论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 10:23 | [link](https://www.bilibili.com/video/BV1xnth6KEFB) |
| 2220 | [165]. Mooncake：Kimi 的推理架构，FAST 2025 最佳论文，KV Cache 中心的存算分离，论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 19:12 | [link](https://www.bilibili.com/video/BV1cqYe6QEZW) |
| 2221 | [166]. FlashInfer：MLSys 2025 最佳论文，vLLM、SGLang 都在用的注意力引擎，论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 17:58 | [link](https://www.bilibili.com/video/BV1cqYe6QEZC) |
| 2222 | [167]. 投机解码：性能还是幻觉？MLSys 2026 在 vLLM 上的首次系统实测，论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 17:18 | [link](https://www.bilibili.com/video/BV1riYe6HEX2) |
| 2223 | [168]. Fast_dLLM：给扩散大模型加 KV Cache，免训练提速 27 倍，论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 16:05 | [link](https://www.bilibili.com/video/BV1kiYe6HEFq) |
| 2224 | [169]. NVFP4_Pretraining：英伟达用 4bit 预训练 12B 模型，10 万亿 token 不掉点，论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 20:03 | [link](https://www.bilibili.com/video/BV1riYe6HEfk) |
| 2225 | [170]. SOAP_Muon_and_Beyond：英伟达实测，万亿 token 上超越 AdamW 的优化器，论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 17:18 | [link](https://www.bilibili.com/video/BV1piYe6pEcF) |
| 2226 | [171]. MegaScale_MoE：字节 1440 卡训 352B MoE，比 Megatron 快 1.88 倍，论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 17:14 | [link](https://www.bilibili.com/video/BV1F6Ye6SEAe) |
| 2227 | [172]. DualKV：GRPO 里被复制 32 遍的 prompt，终于不重复算了，论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 18:54 | [link](https://www.bilibili.com/video/BV1F6Ye6SEx6) |
| 2228 | [173]. Kimi_K2：万亿 MoE 开源 Agent 模型，MuonClip 稳训练，论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 15:37 | [link](https://www.bilibili.com/video/BV1fwY165EtL) |
| 2229 | [174]. DeepSeek_V3_2：DSA 稀疏注意力，长上下文大幅提速，论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 14:13 | [link](https://www.bilibili.com/video/BV1fwY165ES8) |
| 2230 | [175]. Qwen3：快慢思考混合推理，多尺寸模型全家桶，论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 10:35 | [link](https://www.bilibili.com/video/BV1BwY165E6E) |
| 2231 | [176]. Llama_3：Meta 405B 模型群，训练全细节公开，论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 12:57 | [link](https://www.bilibili.com/video/BV1fwY165EyC) |
| 2232 | [177]. MiniMax_M1：Lightning Attention 撑起百万上下文推理，论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 14:22 | [link](https://www.bilibili.com/video/BV1KFe56uEqn) |
| 2233 | [181]. GLM 5：智谱新一代旗舰，DSA 稀疏注意力 + 异步 RL 做 Agent 工程，论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 10:52 | [link](https://www.bilibili.com/video/BV15rHv6mEMH) |
| 2234 | [182]. Qwen3.5 Omni：混合注意力 MoE 全模态，ARIA 让语音合成更自然，论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 12:41 | [link](https://www.bilibili.com/video/BV15rHv6mEjH) |
| 2235 | [183]. Complex KDA：把 Kimi Delta Attention 升级到复数域，表达能力大幅增强，论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 19:41 | [link](https://www.bilibili.com/video/BV15rHv6mEXm) |
| 2236 | [184]. DeepSeek V4.1 Flash：KV Cache 压到 890 字节每 token，论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 15:31 | [link](https://www.bilibili.com/video/BV13KHv66EtS) |
| 2237 | [185]. DeepSeek DSec：为 Agent 强化学习打造的沙箱基础设施，论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 20:10 | [link](https://www.bilibili.com/video/BV1hKHv6rEme) |
| 2238 | [186]. GLM OCR：0.9B 小模型 + 多 token 预测，OCR 解码不再逐字蹦，论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 15:10 | [link](https://www.bilibili.com/video/BV1QKHv6rEeg) |
| 2239 | [187]. Gemini 2.5：谷歌经典模型，长上下文 + 多模态撬动 Agent 工作流，论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 12:17 | [link](https://www.bilibili.com/video/BV183Hv6ME7a) |
| 2240 | [188]. Scaling SAE：OpenAI 的稀疏自编码器缩放定律，可解释性工作，论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 14:40 | [link](https://www.bilibili.com/video/BV1b3Hv6MEod) |
| 2241 | [189]. GLM 5.3：智谱基座没换，纯靠后训练 Scaling 编程暴涨，论文阅读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 6:26 | [link](https://www.bilibili.com/video/BV1YCpE6KEW1) |
| 2242 | [190]. 字节 Seed 逮到 DeepSeek「神鬼二象性」：分块 KV Cache 带来 4-Token 周期，论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 15:19 | [link](https://www.bilibili.com/video/BV1ZapE6kEUj) |
| 2243 | [34]. PPO：论文解读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 9:56 | [link](https://www.bilibili.com/video/BV1T2RrBvE25) |
| 2244 | [36]. DPO：论文解读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 8:45 | [link](https://www.bilibili.com/video/BV142RrBeE8E) |
| 2245 | [38]. AlphaGo：论文解读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 11:20 | [link](https://www.bilibili.com/video/BV1t1RrBNELs) |
| 2246 | [39]. 智能体强化学习论文串讲：WebRL、DigiRL、WebAgent-R1、AgentQ【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 43:40 | [link](https://www.bilibili.com/video/BV1f9RxBCEyN) |
| 2247 | [41]. DeepSeek_GRPO：论文解读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 7:17 | [link](https://www.bilibili.com/video/BV1m1RrBNEhp) |
| 2248 | [42]. DQN：论文解读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 9:26 | [link](https://www.bilibili.com/video/BV141RrBNEd1) |
| 2249 | [45]. AlphaZero：论文解读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 5:50 | [link](https://www.bilibili.com/video/BV1nERrB9E7d) |
| 2250 | [47]. QLearning：论文解读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 5:56 | [link](https://www.bilibili.com/video/BV14N5b6YEbS) |
| 2251 | [48]. DAPO：论文解读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 15:10 | [link](https://www.bilibili.com/video/BV1tN5b6YEjF) |
| 2252 | [131]. A3C：首次用异步 actor-critic 把深度 RL 做稳定，是 PPO的基石，论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 7:11 | [link](https://www.bilibili.com/video/BV1MYuG6rETy) |
| 2253 | [135]. TRPO：PPO的前身，论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 8:57 | [link](https://www.bilibili.com/video/BV1xBuG6MEYJ) |
| 2254 | [137]. MuZero：AlphaZero 之后关键的一步：直接学一个世界模型做 MCTS，论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 9:04 | [link](https://www.bilibili.com/video/BV1KBuG6MEwe) |
| 2255 | [141]. Rainbow：把 DQN 的六大改进一次拼完，论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 7:43 | [link](https://www.bilibili.com/video/BV1BtbY6PEfW) |
| 2256 | [156]. UCB1：多臂老虎机，论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 9:51 | [link](https://www.bilibili.com/video/BV17MhG65E2o) |
| 2257 | [157]. GSPO：GRPO 的改进，序列级重要性采样，论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 8:17 | [link](https://www.bilibili.com/video/BV1T7th6gELe) |
| 2258 | [164]. InstructGPT：RLHF 的开山之作，论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 9:07 | [link](https://www.bilibili.com/video/BV1j2tG6qE5e) |
| 2259 | [49]. ResNet：论文解读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 9:56 | [link](https://www.bilibili.com/video/BV1FXLJ6YE4U) |
| 2260 | [50]. MobileNet：论文解读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 8:19 | [link](https://www.bilibili.com/video/BV1FXLJ6YExi) |
| 2261 | [54]. ViT：论文解读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 8:46 | [link](https://www.bilibili.com/video/BV1JXLJ6YE1X) |
| 2262 | [57]. CLIP：论文解读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 9:20 | [link](https://www.bilibili.com/video/BV1cQLJ6PE78) |
| 2263 | [58]. MAE：论文解读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 10:21 | [link](https://www.bilibili.com/video/BV1zGLM6cEYG) |
| 2264 | [60]. SAM：论文解读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 9:02 | [link](https://www.bilibili.com/video/BV1ktGe6NE1c) |
| 2265 | [62]. FlowMatching：论文解读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 9:45 | [link](https://www.bilibili.com/video/BV1hiGx6oExa) |
| 2266 | [63]. DETR：论文解读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 6:08 | [link](https://www.bilibili.com/video/BV1DiGx6oE4S) |
| 2267 | [64]. YOLO：论文解读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 8:23 | [link](https://www.bilibili.com/video/BV18iGx6oEo1) |
| 2268 | [66]. DINO：论文解读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 11:09 | [link](https://www.bilibili.com/video/BV1bGVK6iEq7) |
| 2269 | [68]. EfficientNet：论文解读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 8:08 | [link](https://www.bilibili.com/video/BV1zRVE6sEmR) |
| 2270 | [69]. SwinTransformer：论文解读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 12:23 | [link](https://www.bilibili.com/video/BV1zRVE6sEU2) |
| 2271 | [70]. UNet：论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 7:53 | [link](https://www.bilibili.com/video/BV1zRVE6sEz1) |
| 2272 | [73]. FasterRCNN：论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 9:07 | [link](https://www.bilibili.com/video/BV1Wg7m6XEgG) |
| 2273 | [74]. VGG：论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 5:52 | [link](https://www.bilibili.com/video/BV1Ag7m6XEy4) |
| 2274 | [75]. GoogLeNet：论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 5:13 | [link](https://www.bilibili.com/video/BV1Pg7m6XEnq) |
| 2275 | [76]. VAE：论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 8:46 | [link](https://www.bilibili.com/video/BV1Ag7m6XEyN) |
| 2276 | [77]. DDPM：论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 8:39 | [link](https://www.bilibili.com/video/BV176Js6DEaM) |
| 2277 | [78]. CFG：论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 6:03 | [link](https://www.bilibili.com/video/BV176Js6DE5W) |
| 2278 | [81]. ProgressiveDistillation：论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 10:03 | [link](https://www.bilibili.com/video/BV1q6Js6DE2b) |
| 2279 | [80]. GAN：论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 7:34 | [link](https://www.bilibili.com/video/BV176Js6DEPp) |
| 2280 | [84]. WGAN：论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 7:08 | [link](https://www.bilibili.com/video/BV176Js6DELe) |
| 2281 | [85]. NCSN：论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 8:28 | [link](https://www.bilibili.com/video/BV1LXjg6vEhk) |
| 2282 | [86]. DDIM：论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 10:48 | [link](https://www.bilibili.com/video/BV1LXjg6vEPM) |
| 2283 | [95]. SAM_2：论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 8:34 | [link](https://www.bilibili.com/video/BV1kv7q6RELS) |
| 2284 | [91]. ConsistencyModels：论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 11:50 | [link](https://www.bilibili.com/video/BV1wv7q6dEtL) |
| 2285 | [90]. EDM：论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 12:01 | [link](https://www.bilibili.com/video/BV1kv7q6REvQ) |
| 2286 | [89]. LDM：论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 14:52 | [link](https://www.bilibili.com/video/BV1Av7q6dEKW) |
| 2287 | [88]. DiffusionBeatGANs：论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 13:05 | [link](https://www.bilibili.com/video/BV1kv7q6REEK) |
| 2288 | [87]. ScoreSDE：论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 9:59 | [link](https://www.bilibili.com/video/BV1kv7q6REtL) |
| 2289 | [111]. Stable Diffusion：论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 10:34 | [link](https://www.bilibili.com/video/BV19AN36iE8n) |
| 2290 | [112]. SAM 3：论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 10:34 | [link](https://www.bilibili.com/video/BV15wN36uEXx) |
| 2291 | [114]. DiT：论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 7:52 | [link](https://www.bilibili.com/video/BV1UyK36YED6) |
| 2292 | [118]. Rectified Flow：论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 7:25 | [link](https://www.bilibili.com/video/BV1hrKp6NEj5) |
| 2293 | [121]. CNN，卷积网络经典重温：论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 9:42 | [link](https://www.bilibili.com/video/BV1Mdgh6aE5u) |
| 2294 | [122]. MRP，借鉴MTP的思想用于扩散语言模型：论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 9:32 | [link](https://www.bilibili.com/video/BV12Fga6fEuk) |
| 2295 | [124]. DINO v2：论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 10:18 | [link](https://www.bilibili.com/video/BV1H4gh6HEdj) |
| 2296 | [125]. ControlNet：论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 8:53 | [link](https://www.bilibili.com/video/BV1nB3r6UEPf) |
| 2297 | [126]. DeepSeek OCR：论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 9:44 | [link](https://www.bilibili.com/video/BV1vY3y6UEaG) |
| 2298 | [128]. DINOv3：论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 12:19 | [link](https://www.bilibili.com/video/BV1Dr3y6GEDX) |
| 2299 | [132]. Conditional Flow Matching：条件流匹配，论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 7:51 | [link](https://www.bilibili.com/video/BV1TYuG6rEX1) |
| 2300 | [143]. NeRF：神经辐射场三维重建，论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 12:04 | [link](https://www.bilibili.com/video/BV1zxbY6vEy9) |
| 2301 | [145]. 3D Gaussian Splatting：3D高斯实时渲染，论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 8:59 | [link](https://www.bilibili.com/video/BV1zxbY6vEgk) |
| 2302 | [147]. AlexNet：深度学习名作经典重温，论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 8:00 | [link](https://www.bilibili.com/video/BV1kEbY6gEvA) |
| 2303 | [149]. Batch Norm：批量归一化经典重温，论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 7:03 | [link](https://www.bilibili.com/video/BV1ezbv6eEYm) |
| 2304 | [161]. Instant NGP：把 NeRF 加速到秒级的哈希编码，论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 7:15 | [link](https://www.bilibili.com/video/BV12nth6MEaj) |
| 2305 | [162]. 2D Gaussian Splatting：3D 高斯的改进，几何重建更准，论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 8:07 | [link](https://www.bilibili.com/video/BV12nth6TEAC) |
| 2306 | [55]. ScaNN：向量检索论文解读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 7:31 | [link](https://www.bilibili.com/video/BV1FQLJ6PESa) |
| 2307 | [61]. RaBitQ：向量检索论文解读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 9:13 | [link](https://www.bilibili.com/video/BV1AtGe6KEuV) |
| 2308 | [97]. RaBitQ的改进工作：论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 9:38 | [link](https://www.bilibili.com/video/BV18e7p6FEU6) |
| 2309 | [123]. 向量检索ANNS经典论文：PQ论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 9:31 | [link](https://www.bilibili.com/video/BV1Kfgh68ErF) |
| 2310 | [71]. Whisper：论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 10:36 | [link](https://www.bilibili.com/video/BV1Ag7m6XErq) |
| 2311 | [155]. CTC：语音识别的经典损失函数，论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 7:56 | [link](https://www.bilibili.com/video/BV1f38h6cEcs) |
| 2312 | [102]. ReAct：Agent经典论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 9:17 | [link](https://www.bilibili.com/video/BV1FRTi6oEz2) |
| 2313 | [103]. Reflexion：Agent经典论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 6:53 | [link](https://www.bilibili.com/video/BV1cJTb6BE3S) |
| 2314 | [130]. App Agent：大模型操作手机，GUI Agent论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 6:00 | [link](https://www.bilibili.com/video/BV1mvuG6gEHj) |
| 2315 | [134]. SWE-agent：Agent处理GitHub issue的经典论文，论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 8:48 | [link](https://www.bilibili.com/video/BV1xBuG6MEuX) |
| 2316 | [136]. Toolformer：大模型自发调用工具的开山之作，论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 8:45 | [link](https://www.bilibili.com/video/BV1NBuG6MEiP) |
| 2317 | [138]. Voyager：Agent玩我的世界，论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 10:12 | [link](https://www.bilibili.com/video/BV1KiuG6zECG) |
| 2318 | [140]. Mobile Agent：大模型操作手机，GUI Agent论文精读【每天一个宝藏论文】 | - | AI 论文精读 | - | - | 7:09 | [link](https://www.bilibili.com/video/BV1pPu26bEB6) |
| 2319 | 13. 旋转位置编码和复数欧拉公式有什么关系？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:44 | [link](https://www.bilibili.com/video/BV1qzFxzQES2) |
| 2320 | 14. 旋转位置编码和高中三角函数和差角公式有什么关系？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:07 | [link](https://www.bilibili.com/video/BV1uoFxzgEWz) |
| 2321 | 16. RoPE如何从2维推广到任意偶数维，奇数维咋办？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:04 | [link](https://www.bilibili.com/video/BV1FgcMzkE5h) |
| 2322 | 17. 为什么正余弦位置编码的注意力是和绝对位置相关的？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:17 | [link](https://www.bilibili.com/video/BV1mZcuztEw2) |
| 2323 | 19. 为什么RoPE中旋转矩阵R实际上不需要矩阵乘算子？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:26 | [link](https://www.bilibili.com/video/BV1XyFyzcEN6) |
| 2324 | 20. RoPE注意力的绝对位置无关性和欧拉公式有什么关系？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:16 | [link](https://www.bilibili.com/video/BV1fFFDzsEt6) |
| 2325 | 21. 为什么增大旋转位置编码中10000可提高模型外推能力【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:26 | [link](https://www.bilibili.com/video/BV1o5FozuEz2) |
| 2326 | 22. 为什么transformers.Llama的实现和RoPE原论文不一致？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:31 | [link](https://www.bilibili.com/video/BV1nUcbzTEGi) |
| 2327 | 23. Llama的旋转位置编码实现和RoPE原论文有何不同？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:38 | [link](https://www.bilibili.com/video/BV15EcbzoEY7) |
| 2328 | 120. 任意矩阵满足什么性质就能成为RoPE旋转矩阵？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:36 | [link](https://www.bilibili.com/video/BV1TN5b6YE5q) |
| 2329 | 134. 为什么RoPE中旋转矩阵R0是单位阵？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 1:18 | [link](https://www.bilibili.com/video/BV1UGVK6vEzn) |
| 2330 | 138. 如何可视化含RoPE的注意力分数矩阵【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:55 | [link](https://www.bilibili.com/video/BV1FRVE6xEap) |
| 2331 | 147. 如何直观理解RoPE的平移不变性【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 1:54 | [link](https://www.bilibili.com/video/BV18Aj36ZEZP) |
| 2332 | 25. 举例说明FlashAttention的分块矩阵乘法的正确性？【每天一个宝藏名词】 | - | AI 论文精读 | - | - | 2:32 | [link](https://www.bilibili.com/video/BV18pcLz2E3P) |
| 2333 | 28. 为什么在线Softmax比安全Softmax可以少一次循环？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:44 | [link](https://www.bilibili.com/video/BV1i6cnzzE2x) |
| 2334 | 30. 举例说明SlimAttention的分块矩阵乘法的正确性？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:31 | [link](https://www.bilibili.com/video/BV11KcWz8EZm) |
| 2335 | 31. FlashAttention v2版本如何省略掩码上三角矩阵计算？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:25 | [link](https://www.bilibili.com/video/BV16qZLBxEZt) |
| 2336 | 33. 用户改提示词为什么不会影响前面的KV Cache？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:38 | [link](https://www.bilibili.com/video/BV1dgZ7BQEHL) |
| 2337 | 34. BERT为什么没有KV Cache/KV Cache何以存在？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:43 | [link](https://www.bilibili.com/video/BV1qKZ7BsEs5) |
| 2338 | 36. 为什么推理时prefill是GEMM，而decode是（Batched）GEMV？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:38 | [link](https://www.bilibili.com/video/BV1UtZkBjEZP) |
| 2339 | 37. GQA中讲的共享指的是Token还是Head？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:30 | [link](https://www.bilibili.com/video/BV1cTZyBzEjv) |
| 2340 | 39. FlashAttention V2中为何要先循环Q后循环K？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:55 | [link](https://www.bilibili.com/video/BV1yiArzSEs1) |
| 2341 | 41 Flash Attention之前的那种N^2注意力不好在哪里？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:32 | [link](https://www.bilibili.com/video/BV1WzArzUEdr) |
| 2342 | 55. 为什么KV Cache也有LRU等缓存替换策略?【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:33 | [link](https://www.bilibili.com/video/BV1YdANzcESN) |
| 2343 | 56. 为什么多个Sub-Agent也可以共享前缀KV Cache？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 1:51 | [link](https://www.bilibili.com/video/BV1cPAuzpE6e) |
| 2344 | 68. prefill和decode时KV Cache是如何"堆积"的？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:58 | [link](https://www.bilibili.com/video/BV1AYQdBfEDS) |
| 2345 | 82. 在线Softmax和Flash Attention分别维护了多少个“动态规划量”？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:07 | [link](https://www.bilibili.com/video/BV1oA93BtETZ) |
| 2346 | 83. Flash Attention的线性显存比平方显存增长慢了多少？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 1:47 | [link](https://www.bilibili.com/video/BV1baNGzmEzn) |
| 2347 | 85. 为什么prefill和decode都可以跳过掩码上三角计算？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:45 | [link](https://www.bilibili.com/video/BV1ZEDvB9E6Y) |
| 2348 | 101. 如何用矩阵乘法链式法则速推Flash Attention梯度？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:23 | [link](https://www.bilibili.com/video/BV12CoMB5EDJ) |
| 2349 | 102. PagedAttention是如何减少内存浪费的？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:23 | [link](https://www.bilibili.com/video/BV1EwoRBfExe) |
| 2350 | 106. Flash Attention反向传播也做到线性显存了吗？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:20 | [link](https://www.bilibili.com/video/BV1a89kB3EVu) |
| 2351 | 111. 如何直观理解KV Cache的显存计算公式？以Llama2-7B为例。【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:38 | [link](https://www.bilibili.com/video/BV1Tf9XBwEzM) |
| 2352 | 117. 如何用动态规划理解在线softmax的循环与归约？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:48 | [link](https://www.bilibili.com/video/BV1SHR9BuEBH) |
| 2353 | 141. 多轮对话中Decode之后还要增量Prefill，那新的KV如何并入KV Cache？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:05 | [link](https://www.bilibili.com/video/BV1zCjg6rE9F) |
| 2354 | 143. 如何可视化SGLang中的KV Cache？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 1:10 | [link](https://www.bilibili.com/video/BV13Aj36ZEcC) |
| 2355 | 29. 以逐元素乘加为例，算子融合为什么能提高计算效率？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 1:51 | [link](https://www.bilibili.com/video/BV19PcnzPEQp) |
| 2356 | 45. SIMD是如何加速张量计算的(简单理解)【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 1:10 | [link](https://www.bilibili.com/video/BV1doArzKExB) |
| 2357 | 49. 双缓冲是如何加速张量计算的？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:30 | [link](https://www.bilibili.com/video/BV1bUP5zDER5) |
| 2358 | 53. 如何加速两个张量之和？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 1:17 | [link](https://www.bilibili.com/video/BV1SqPhzAErH) |
| 2359 | 57. 网格步进是如何加速张量计算的？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:08 | [link](https://www.bilibili.com/video/BV1SSNFz2EDK) |
| 2360 | 97. 张量广播的线性索引是如何对应的？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:47 | [link](https://www.bilibili.com/video/BV1KyoMByEdR) |
| 2361 | 103. 多个线程执行同一段算子代码时发生了什么？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:53 | [link](https://www.bilibili.com/video/BV1JcoRB8EGb) |
| 2362 | 108. 如何用前缀和理解稀疏矩阵的CSR格式？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:46 | [link](https://www.bilibili.com/video/BV1k7RuBPEsV) |
| 2363 | 140. 稀疏矩阵乘稠密向量SpMV是如何跳过0值计算的？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 1:58 | [link](https://www.bilibili.com/video/BV1AG7m6HEEW) |
| 2364 | 162. 如何可视化GEMM？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:51 | [link](https://www.bilibili.com/video/BV1tWTj6jEGU) |
| 2365 | 163. 张量并行中的列并行和行并行是如何切分W和X矩阵的？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:33 | [link](https://www.bilibili.com/video/BV1rJTb6qEYr) |
| 2366 | 164. 为什么环形All-Reduce 时，4卡和128卡单卡通信量差不多？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:38 | [link](https://www.bilibili.com/video/BV1AzMP6rE61) |
| 2367 | 166. 如何用双缓冲优化GEMM？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:52 | [link](https://www.bilibili.com/video/BV1WzMP6rEN6) |
| 2368 | 168. Megatron张量并行如何用列切分加行切分降低FFN层的通信？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:33 | [link](https://www.bilibili.com/video/BV1zTMP6YEqg) |
| 2369 | 172. 如何用外积优化GEMM？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:48 | [link](https://www.bilibili.com/video/BV1E9Mb6MEeq) |
| 2370 | 178. 如何在SRAM和寄存器两个层级同时使用双缓冲优化GEMM？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:49 | [link](https://www.bilibili.com/video/BV1XEKG6gERb) |
| 2371 | 195. 如何用Tensor Core加速GEMM？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:04 | [link](https://www.bilibili.com/video/BV1xT3k6ZEP8) |
| 2372 | 42. 聚类量化和线性量化有何不同？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:42 | [link](https://www.bilibili.com/video/BV1yBArzEEeE) |
| 2373 | 44. 为什么把权重置0就是在剪枝？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:21 | [link](https://www.bilibili.com/video/BV1B9ArzuEP3) |
| 2374 | 62．LLM.int8是如何利用向量外积进行量化的？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:08 | [link](https://www.bilibili.com/video/BV17pwEzMETL) |
| 2375 | 63. 举例说明SmoothQuant量化对角矩阵乘法的正确性？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:51 | [link](https://www.bilibili.com/video/BV1VTw7zbEzq) |
| 2376 | 64. SmoothQuant量化中有没有用到外积思想？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:31 | [link](https://www.bilibili.com/video/BV1DMwmzgEyV) |
| 2377 | 65. 从校准集说明为何SmoothQuant中的S无需矩阵乘算子【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:09 | [link](https://www.bilibili.com/video/BV12DwRz9E4j) |
| 2378 | 66. LLM.int8与SmoothQuant解决离群值的思路有何异同？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:04 | [link](https://www.bilibili.com/video/BV13rwCzwEKX) |
| 2379 | 67. 为何圆形山谷会让OBD剪枝退化为基于大小剪枝？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:28 | [link](https://www.bilibili.com/video/BV1qAA5ztELy) |
| 2380 | 71. OBD剪枝假设山谷是什么样的？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:37 | [link](https://www.bilibili.com/video/BV11RQfB3Eot) |
| 2381 | 73. OBS剪枝保留与修改了OBD剪枝的哪些假设？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:57 | [link](https://www.bilibili.com/video/BV1njXKBnEBg) |
| 2382 | 74. 为什么OBD剪枝是特殊的OBS剪枝？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:29 | [link](https://www.bilibili.com/video/BV1xTXKB4Ecn) |
| 2383 | 75. OBS剪枝是如何选择被剪枝的权重的？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:36 | [link](https://www.bilibili.com/video/BV1AwX1BPE1g) |
| 2384 | 76. 为什么OBS剪枝可看作特殊的OBQ量化？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:31 | [link](https://www.bilibili.com/video/BV1cKX1BhED8) |
| 2385 | 78. GPTQ量化的最小化目标如何写成类似OBS形式的？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:21 | [link](https://www.bilibili.com/video/BV1679cBME93) |
| 2386 | 79. 为什么基于权重大小剪枝是特殊的OBD、OBS、OBQ？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 1:45 | [link](https://www.bilibili.com/video/BV1fn9cBKEbt) |
| 2387 | 80. 剪枝后微调让被置零的权重不再为零怎么办？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:16 | [link](https://www.bilibili.com/video/BV16E9cBqEK8) |
| 2388 | 81. 量化后微调让聚在一起的权重分家了怎么办？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:58 | [link](https://www.bilibili.com/video/BV1zf9gBwEqd) |
| 2389 | 88. 量化后微调为什么要对聚类中心求和？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:48 | [link](https://www.bilibili.com/video/BV1fcD4BPEo7) |
| 2390 | 89. 量化感知训练是如何感知到量化的？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:59 | [link](https://www.bilibili.com/video/BV1d9QABeEdC) |
| 2391 | 90. OBQ如何将最小化剪枝损失推广到量化？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 1:54 | [link](https://www.bilibili.com/video/BV1kkDQBVE4y) |
| 2392 | 92. 为什么量化会让损失“山谷”变成“台阶”？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 1:55 | [link](https://www.bilibili.com/video/BV1eoQvBQEMF) |
| 2393 | 94. 量化感知训练中为什么要STE来处理round梯度？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:29 | [link](https://www.bilibili.com/video/BV12qdaBkERq) |
| 2394 | 110. 为什么激活值per channel量化比per token量化难加速得多？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:46 | [link](https://www.bilibili.com/video/BV1k7RuBPEqt) |
| 2395 | 123. 如何用CPU内存的残差修正量化误差？以DecDEC为例【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:15 | [link](https://www.bilibili.com/video/BV1FXLJ6YEEv) |
| 2396 | 160. 如何对注意力头剪枝？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:39 | [link](https://www.bilibili.com/video/BV1YCTY6qEMZ) |
| 2397 | 219. 为什么把权重置0就是在剪枝？(新版)【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:12 | [link](https://www.bilibili.com/video/BV1rG4U6kE2E) |
| 2398 | 47 CLIP比较人性化的可视化可能长什么样？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:19 | [link](https://www.bilibili.com/video/BV1k4PDzrE9X) |
| 2399 | 59. DeepSeek OCR比较人性化的可视化可能是什么样的？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:54 | [link](https://www.bilibili.com/video/BV13gcCzbE7y) |
| 2400 | 174. 为什么DDPM加噪相当于90°旋转插值？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:52 | [link](https://www.bilibili.com/video/BV1vAN36BEit) |
| 2401 | 181. 为什么 DDPM 加噪旋转角是不均匀的？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:30 | [link](https://www.bilibili.com/video/BV1YjKG6rEhy) |
| 2402 | 190. 为什么扩散模型采样高斯噪声相当于在球壳上选点？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:40 | [link](https://www.bilibili.com/video/BV16V3762ECA) |
| 2403 | 193. 为什么前向KL让生成模型倾向平均，反向KL倾向专精？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:26 | [link](https://www.bilibili.com/video/BV1vo3w6wE6J) |
| 2404 | 198. 为什么逐点卷积可以用 GEMM 实现？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:40 | [link](https://www.bilibili.com/video/BV1BB3t6gEtZ) |
| 2405 | 205. 如何可视化VIT？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:33 | [link](https://www.bilibili.com/video/BV1t3up6iE8b) |
| 2406 | 206. 为什么DDPM加噪图在椭圆上，而Flow Matching在直线上？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:41 | [link](https://www.bilibili.com/video/BV1x2uN6SEAt) |
| 2407 | 210. 为什么ViT展平像素这一步是用卷积实现的？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:04 | [link](https://www.bilibili.com/video/BV16M8h6AEY6) |
| 2408 | 212. 如何可视化UNet？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:15 | [link](https://www.bilibili.com/video/BV1quhG6CEtf) |
| 2409 | 32. 一种人性化的Transformer可视化可能是什么样的？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:53 | [link](https://www.bilibili.com/video/BV13FZEBEE6y) |
| 2410 | 35. Transformer暗含多少种分块矩阵乘法的理解方式？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:58 | [link](https://www.bilibili.com/video/BV1pRZtBaEYv) |
| 2411 | 40. Temperature、TopK/P退化为贪婪解码的三种条件是？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:27 | [link](https://www.bilibili.com/video/BV1AzArzUEh1) |
| 2412 | 77. 为什么训练时教师强制是只“感觉”不“生成”的？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:58 | [link](https://www.bilibili.com/video/BV14BXoBMEsk) |
| 2413 | 93. 为什么Transformer的核心公式是在做加权平均？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 1:53 | [link](https://www.bilibili.com/video/BV1CkQjBJE8K) |
| 2414 | 98. 为什么训练时上个词的概率预测不直接影响下个词？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:04 | [link](https://www.bilibili.com/video/BV1CSoMBgEUA) |
| 2415 | 99. MOE中先求Top K后Softmax，与先求Softmax后重归一化能一样？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 1:54 | [link](https://www.bilibili.com/video/BV1U6oMBjE1D) |
| 2416 | 104. 为什么训练时是同时预测token的？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:43 | [link](https://www.bilibili.com/video/BV1jNoRBoE9b) |
| 2417 | 107. DeepSeek V4如何使用Attention Sink忽略上下文？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:06 | [link](https://www.bilibili.com/video/BV1389kB3Ek4) |
| 2418 | 109. 最简单的Transformer可视化能有多简单？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 1:07 | [link](https://www.bilibili.com/video/BV1A7RuBNETS) |
| 2419 | 112. 如何可视化MOE？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:16 | [link](https://www.bilibili.com/video/BV1uGdgBnE65) |
| 2420 | 114. 为什么除以√dk是在给注意力升温？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:16 | [link](https://www.bilibili.com/video/BV1m5RmBSEkF) |
| 2421 | 118. 为什么Deepseek V3不用辅助损失也能做到MoE负载均衡？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:43 | [link](https://www.bilibili.com/video/BV1MyRXBvEG1) |
| 2422 | 119. 如何可视化多头注意力？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 0:53 | [link](https://www.bilibili.com/video/BV1235J6qENx) |
| 2423 | 121. 为什么GQA是MQA过渡到MHA的插值？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:01 | [link](https://www.bilibili.com/video/BV16XLJ6YEVP) |
| 2424 | 122. 为什么只有单个词嵌入就能构成二元语言模型？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:11 | [link](https://www.bilibili.com/video/BV1FXLJ6YEwC) |
| 2425 | 124. 训练时是如何恰好错开一个token的？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 1:39 | [link](https://www.bilibili.com/video/BV1FXLJ6YE1L) |
| 2426 | 125. 为什么Token数相同的批次未必是负载均衡的？以WLB LLM为例【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 1:48 | [link](https://www.bilibili.com/video/BV1FXLJ6YEiX) |
| 2427 | 126. 举例说明投机解码如何拒绝采样？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:52 | [link](https://www.bilibili.com/video/BV1EVLM6bEuU) |
| 2428 | 127. 为什么Adam优化器相当于在求19日EMA均线？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:30 | [link](https://www.bilibili.com/video/BV1FGLM6wEbm) |
| 2429 | 128. 为什么4D并行的四个任务划分维度是正交的？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 0:59 | [link](https://www.bilibili.com/video/BV1ZzLC6bEbU) |
| 2430 | 130. 如何从概率树理解投机解码是无损的？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:51 | [link](https://www.bilibili.com/video/BV1ktGe6NEtg) |
| 2431 | 132. 为什么只用柱状图就能证明投机解码是无损的？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:20 | [link](https://www.bilibili.com/video/BV1UHGB6REeL) |
| 2432 | 133. 如何可视化超连接？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:30 | [link](https://www.bilibili.com/video/BV1h1GE6BEMm) |
| 2433 | 135. 如何直观理解超连接中的残差流？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:27 | [link](https://www.bilibili.com/video/BV1bGVK6iE2B) |
| 2434 | 136. BERT和GPT的可视化有多像？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 1:18 | [link](https://www.bilibili.com/video/BV1LsG26dEuq) |
| 2435 | 137. HC=？会让超连接退化为preNorm传统残差连接？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:16 | [link](https://www.bilibili.com/video/BV1zRVE6sE2x) |
| 2436 | 139. 为什么传统残差连接是mhc残差流扩展率=1 的特例？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:53 | [link](https://www.bilibili.com/video/BV1zRVE6sExg) |
| 2437 | 142. 如何可视化前馈网络｜线性层的反向传播？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:49 | [link](https://www.bilibili.com/video/BV1gAj36ZELC) |
| 2438 | 144. 如何可视化Transformer的残差连接？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 0:42 | [link](https://www.bilibili.com/video/BV1DAj36ZE2E) |
| 2439 | 145. 从prefill和decode角度理解投机解码何以加速？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:18 | [link](https://www.bilibili.com/video/BV1hAj36ZE7E) |
| 2440 | 146. 能否有一种方法同时可视化注意力的前向和反向传播？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:14 | [link](https://www.bilibili.com/video/BV1gAj36ZEUA) |
| 2441 | 148. 超连接中的连边和感知机的连边有何异同？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:11 | [link](https://www.bilibili.com/video/BV1DAj36ZEZD) |
| 2442 | 149. 为什么投机解码最多可以比K个Token多生成一个Token？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:41 | [link](https://www.bilibili.com/video/BV1gAj36ZEY3) |
| 2443 | 150. 对比注意力池和注意力温度对注意力汇聚有什么影响？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:19 | [link](https://www.bilibili.com/video/BV1hAj36ZE8a) |
| 2444 | 151. 如何可视化MQA？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 1:28 | [link](https://www.bilibili.com/video/BV1gAj36ZEmj) |
| 2445 | 152. 为什么前向残差连接对应反向残差连接【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:02 | [link](https://www.bilibili.com/video/BV1bv7p6bEeG) |
| 2446 | 153. 从等比数列求和理解Adam优化器训练初期动量修正【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:35 | [link](https://www.bilibili.com/video/BV1he7p6FEp1) |
| 2447 | 154. 为什么投机解码确保每轮至少产出一个 token？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:32 | [link](https://www.bilibili.com/video/BV1De7p6FEL3) |
| 2448 | 156. 最简单的transformer反向传播可视化能有多简单？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:40 | [link](https://www.bilibili.com/video/BV18e7p6FE1J) |
| 2449 | 157. 为什么Adam除以√vt让稳定的梯度项归一化，振荡的梯度项归零化【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:37 | [link](https://www.bilibili.com/video/BV13e7p6cEF4) |
| 2450 | 158. 最简单的含RoPE的Transformer可视化有多简单？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:18 | [link](https://www.bilibili.com/video/BV18e7p6FEeD) |
| 2451 | 159. 如何可视化MTP？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:57 | [link](https://www.bilibili.com/video/BV1rtTc6tEqd) |
| 2452 | 161. MoE每个token都要选专家，那prefill要如何并行？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:45 | [link](https://www.bilibili.com/video/BV1foTi6sEyH) |
| 2453 | 165. 残差连接在Transformer反向传播中可视化出来是什么样的？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:06 | [link](https://www.bilibili.com/video/BV1AzMP6kE62) |
| 2454 | 169. MTP为什么能一次预测多个未来 token？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:18 | [link](https://www.bilibili.com/video/BV1aDMu6BEDb) |
| 2455 | 170. vLLM 投机解码首token合并 prefill 这个小技巧是怎么来的？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:01 | [link](https://www.bilibili.com/video/BV1hETD6mERB) |
| 2456 | 171. 如何可视化 DeepSeek MLA（简化版）？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:36 | [link](https://www.bilibili.com/video/BV1MRTd6bEbH) |
| 2457 | 173. 如何证明任意两句话的公共前缀都有相同的KV Cache？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:43 | [link](https://www.bilibili.com/video/BV1HNM76GEo8) |
| 2458 | 176. 如何可视化交叉注意力【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:42 | [link](https://www.bilibili.com/video/BV1RVKG6CEhW) |
| 2459 | 177. Megatron张量并行如何用列切分加行切分降低注意力层的通信？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:38 | [link](https://www.bilibili.com/video/BV1GEKG63EUT) |
| 2460 | 183. 为什么注意力要除以√dk而不是√d model【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:45 | [link](https://www.bilibili.com/video/BV1byK36eEUT) |
| 2461 | 185. 如何可视化kimi的注意力残差？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:51 | [link](https://www.bilibili.com/video/BV1qBKb6hEkq) |
| 2462 | 187. 为什么MLA无需显式解压Q和K？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:37 | [link](https://www.bilibili.com/video/BV19s3K6zEXQ) |
| 2463 | 188. 预训练和SFT产生的初始梯度有何不同？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:24 | [link](https://www.bilibili.com/video/BV1Qz3g61EAe) |
| 2464 | 192. 如何证明注意力右上角加-∞就看不到后面了？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:14 | [link](https://www.bilibili.com/video/BV1N8gZ6NEzg) |
| 2465 | 194. 为什么滑动窗口注意力在 decode 时要使用环形缓存？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:25 | [link](https://www.bilibili.com/video/BV1WP3B65Eh5) |
| 2466 | 196. 为什么自注意力矩阵是正方形，而交叉注意力矩阵是长方形？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:50 | [link](https://www.bilibili.com/video/BV17S316dExh) |
| 2467 | 199. FlashAttention如何加速滑动窗口注意力prefill？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:29 | [link](https://www.bilibili.com/video/BV1VKMX6bEo1) |
| 2468 | 201. 如何把RoPE算子融合到FlashAttention里？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:53 | [link](https://www.bilibili.com/video/BV1pmuA6gEN7) |
| 2469 | 202. 如何像之前可视化Transformer那样可视化RNN？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:33 | [link](https://www.bilibili.com/video/BV1njMy6UEzQ) |
| 2470 | 203. 推理时Q没有Cache，那训练时呢？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:29 | [link](https://www.bilibili.com/video/BV1njMy6UEmC) |
| 2471 | 204. 如何可视化 RWKV？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:20 | [link](https://www.bilibili.com/video/BV1s5un6dEKR) |
| 2472 | 207. 为什么MLA连V也不需要显式解压？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:27 | [link](https://www.bilibili.com/video/BV1pPu26bELp) |
| 2473 | 208. 如何证明Transformer本身不含位置信息？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:28 | [link](https://www.bilibili.com/video/BV1ezbv6eEC6) |
| 2474 | 209. 为什么同样是依赖上一隐藏状态，RWKV可以并行训练，而RNN不行？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:22 | [link](https://www.bilibili.com/video/BV1T8876rEaA) |
| 2475 | 214. 为什么MLA无需显式解压K和Q？(新版)【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:38 | [link](https://www.bilibili.com/video/BV1FE8Z63E5v) |
| 2476 | 215. 连续批处理如何把Prefill和Decode请求的FFN拼成一次矩阵乘？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:27 | [link](https://www.bilibili.com/video/BV1DrhF6PEtj) |
| 2477 | 216. 多轮对话中Decode之后还要增量Prefill，那新的KV如何并入KV Cache？(新版)【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:58 | [link](https://www.bilibili.com/video/BV1vYhF6zEud) |
| 2478 | 217. Chunked Prefill为什么要给长Prefill分块？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:40 | [link](https://www.bilibili.com/video/BV12Xhw6YE5X) |
| 2479 | 218. 大模型的训练、推理、SFT、强化学习究竟有什么区别？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:37 | [link](https://www.bilibili.com/video/BV1wk4k6fEsY) |
| 2480 | 222. 为什么传统位置编码只作用于词嵌入，而RoPE每层都作用？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:16 | [link](https://www.bilibili.com/video/BV16ath6fEMr) |
| 2481 | 223. 如何可视化MOE？(新版)【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:03 | [link](https://www.bilibili.com/video/BV1LUtG6KEkJ) |
| 2482 | 224. 如何证明因果掩码其实就已经内禀位置信息了？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:47 | [link](https://www.bilibili.com/video/BV1i2tG6qEZ8) |
| 2483 | 225. Deepseek的MLA是如何处理RoPE的？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:35 | [link](https://www.bilibili.com/video/BV1BWto6cEsD) |
| 2484 | 226. 最简单的transformer反向传播可视化能有多简单？(新版)【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:39 | [link](https://www.bilibili.com/video/BV1BHto6aE7P) |
| 2485 | 231. 从prefill和decode角度理解投机解码何以加速？(新版)【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:23 | [link](https://www.bilibili.com/video/BV1fwY165Eeq) |
| 2486 | 232. 为什么滑动窗口注意力在decode时要使用环形缓存？（新版）【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:26 | [link](https://www.bilibili.com/video/BV1sce56BEk1) |
| 2487 | 234. 为什么MLA连V也不需要显式解压？（新版）【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:28 | [link](https://www.bilibili.com/video/BV1YEeH6uECe) |
| 2488 | 236. 为什么自注意力矩阵是正方形，而交叉注意力矩阵是长方形？(新版)【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:49 | [link](https://www.bilibili.com/video/BV1cXeA6PEJR) |
| 2489 | 237. ViT如何使用RoPE？(1D简单版)【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:43 | [link](https://www.bilibili.com/video/BV1hheA6EEW2) |
| 2490 | 238. 扩散语言模型和自回归语言模型有何异同？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:31 | [link](https://www.bilibili.com/video/BV1mdhB6TEmr) |
| 2491 | 239. 如何可视化MTP？(新版)【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:48 | [link](https://www.bilibili.com/video/BV1mdhB6TEQE) |
| 2492 | 240. 为什么注意力要除以√dk而不是√d model？(新版)【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:38 | [link](https://www.bilibili.com/video/BV1MnhJ6JEKb) |
| 2493 | 241. 如何可视化GQA？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 1:36 | [link](https://www.bilibili.com/video/BV1e1ac6VEJF) |
| 2494 | 242. 交叉注意力输出的第i个向量代表什么？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:11 | [link](https://www.bilibili.com/video/BV1cFaT6uEky) |
| 2495 | 243. 为什么投机解码最多可以比K个Token多生成一个Token？(新版)【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:13 | [link](https://www.bilibili.com/video/BV11Vhm6oEZ4) |
| 2496 | 244. 为什么KV Cache相当于Agent的短期记忆？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 1:43 | [link](https://www.bilibili.com/video/BV1CEhm6WEX3) |
| 2497 | 245. 为什么投机解码确保每轮至少产出一个 token？(新版)【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:37 | [link](https://www.bilibili.com/video/BV1CEhm6WER6) |
| 2498 | 247. 交叉注意力需要做旋转位置编码吗？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:59 | [link](https://www.bilibili.com/video/BV1Ksh96yEyN) |
| 2499 | 249. 最近大火的Jev和传统的LLM有何异同？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:48 | [link](https://www.bilibili.com/video/BV1MKa66VEJ4) |
| 2500 | 250. prefill和decode相当于RNN中的什么操作？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:38 | [link](https://www.bilibili.com/video/BV1s6He68EcV) |
| 2501 | 251. Pyramid KV为什么用金字塔形KV Cache？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:44 | [link](https://www.bilibili.com/video/BV1zcHr6uE2N) |
| 2502 | 252. KV Cache相当于RNN中的什么东西？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:45 | [link](https://www.bilibili.com/video/BV1FcHr6gEDq) |
| 2503 | 253. 什么是树形掩码？它和因果掩码有何异同？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:32 | [link](https://www.bilibili.com/video/BV14UHJ6oE9E) |
| 2504 | 255. 树形注意力如何一次前向并行验证整棵草稿树？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:07 | [link](https://www.bilibili.com/video/BV1MRH26BE6z) |
| 2505 | 257. 一棵完美二叉树的树形注意力掩码是什么样的？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:49 | [link](https://www.bilibili.com/video/BV1mVHd64EGJ) |
| 2506 | 259. 如何证明任意两句话的公共前缀都有相同的KV Cache？(新版)【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:35 | [link](https://www.bilibili.com/video/BV1SGpn6NEfF) |
| 2507 | 58. 如何根据答案倒推合成思维链做SFT？以AscendKernelGen为例【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 1:55 | [link](https://www.bilibili.com/video/BV1DvcyzcEa4) |
| 2508 | 60. LoRA微调和向量外积为何长得很像？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:46 | [link](https://www.bilibili.com/video/BV1pKwjz3E1P) |
| 2509 | 84. LoRA要增加旁路，微调前后模型结构却可以不变，为什么？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:16 | [link](https://www.bilibili.com/video/BV1cQSSBvE8N) |
| 2510 | 96. LoRA微调中A、B都随机初始化或全零初始化分别会带来什么问题？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:19 | [link](https://www.bilibili.com/video/BV15GdjByEpy) |
| 2511 | 182. 如何可视化知识蒸馏？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:38 | [link](https://www.bilibili.com/video/BV1UyK36YE3Z) |
| 2512 | 191. 如何可视化LoRA？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 0:36 | [link](https://www.bilibili.com/video/BV1Zq3j63Eeu) |
| 2513 | 46. 矩阵乘法对激活的梯度是怎么来的？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:35 | [link](https://www.bilibili.com/video/BV1ioArzKEMB) |
| 2514 | 51 矩阵乘法对权重的梯度是怎么来的？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:24 | [link](https://www.bilibili.com/video/BV1TUPWzkE6U) |
| 2515 | 52 简单的梯度算子是如何定义的【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:13 | [link](https://www.bilibili.com/video/BV1TUPWzkEgW) |
| 2516 | 61. 含广播的偏置b的梯度如何计算？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:01 | [link](https://www.bilibili.com/video/BV1WWXWBzELJ) |
| 2517 | 87. 为什么前向广播对应着反向归约？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:23 | [link](https://www.bilibili.com/video/BV177DWBdEoV) |
| 2518 | 69. 深度学习中两种常用的矩阵微积分是怎么来的？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:34 | [link](https://www.bilibili.com/video/BV1a9XNBTERT) |
| 2519 | 70. 如何理解泰勒展开的多元函数扩展？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 1:53 | [link](https://www.bilibili.com/video/BV1HVXKBpE9p) |
| 2520 | 100. 为什么神经网络连接可以用矩阵乘法实现？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:54 | [link](https://www.bilibili.com/video/BV1SBoMBmEVB) |
| 2521 | 86. 为什么矩阵乘法可以看作标量乘法的拓展？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:35 | [link](https://www.bilibili.com/video/BV1WxDeBcExC) |
| 2522 | 72. 如何从几何视角理解拉格朗日乘子法？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:17 | [link](https://www.bilibili.com/video/BV1C3XKB9EHm) |
| 2523 | 95. 标量乘法的链式法则可以推广到矩阵吗？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:26 | [link](https://www.bilibili.com/video/BV1D8daB7En5) |
| 2524 | 105. K-Means聚类和中垂线有什么关系？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:17 | [link](https://www.bilibili.com/video/BV1Kk9kBAEnC) |
| 2525 | 113. 如何理解梯度下降的多元函数扩展？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:06 | [link](https://www.bilibili.com/video/BV1m5RmBSENE) |
| 2526 | 184. 一口气看完：正态分布，梯度下降、泰勒展开一元推广到多元【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 11:14 | [link](https://www.bilibili.com/video/BV1LvKw6UEuM) |
| 2527 | 115. 为什么梯度下降、泰勒展开、正态分布都有多元扩展？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:01 | [link](https://www.bilibili.com/video/BV1M5RmBDENg) |
| 2528 | 155. 为什么信息熵=最优码长，交叉熵=实际码长，KL散度=浪费码长【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:17 | [link](https://www.bilibili.com/video/BV18e7p6FEZ1) |
| 2529 | 167. 为什么KL散度非负和信息熵是最优码长这两件事是等价的？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:06 | [link](https://www.bilibili.com/video/BV1fTMP6YEtZ) |
| 2530 | 175. 如何理解正态分布的多元扩展？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:47 | [link](https://www.bilibili.com/video/BV1eVKG6CEZH) |
| 2531 | 179. 如何用高中导数证明 KL 散度非负？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:39 | [link](https://www.bilibili.com/video/BV1GEKG6uEgV) |
| 2532 | 180. 向量如何对向量求导？推广到矩阵、张量呢？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:19 | [link](https://www.bilibili.com/video/BV1VjKG6kEpR) |
| 2533 | 189. 为什么反向传播的本质是乘雅可比矩阵？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:28 | [link](https://www.bilibili.com/video/BV17Y356TEZu) |
| 2534 | 197. 为什么自动微分系统倾向于反向微分而非前向微分？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:18 | [link](https://www.bilibili.com/video/BV1ct3x6gEkq) |
| 2535 | 200. 为什么线性层反向传播也可以用GEMM实现？——为什么前向全连接对应反向全连接？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:06 | [link](https://www.bilibili.com/video/BV1t3uF6MEbd) |
| 2536 | 91. 游戏AI和LLM的πθ(a∣s)有何异同？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:22 | [link](https://www.bilibili.com/video/BV1TeD9B4EbF) |
| 2537 | 116. 如何从动态规划和记忆化搜索理解DQN？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:39 | [link](https://www.bilibili.com/video/BV1ygRXBZEQf) |
| 2538 | 129. 举例说明DPO论文里三行核心代码是啥意思？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:31 | [link](https://www.bilibili.com/video/BV1AtGe6KEbW) |
| 2539 | 131. 折扣因子γ是如何改变未来的奖励重要程度的？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:16 | [link](https://www.bilibili.com/video/BV1AtGe6KEuk) |
| 2540 | 186. 为什么交叉熵梯度相当于特殊的策略梯度？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:37 | [link](https://www.bilibili.com/video/BV1G2gh6BEg6) |
| 2541 | 211. 如何求PPO中每个token的梯度？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:56 | [link](https://www.bilibili.com/video/BV1juhG6CEmD) |
| 2542 | 213. 为什么GRPO可以扔掉价值网络？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:32 | [link](https://www.bilibili.com/video/BV1WC896BEPW) |
| 2543 | 220. PPO的损失计算和SFT有何异同？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:09 | [link](https://www.bilibili.com/video/BV14Ctp6JEp6) |
| 2544 | 221. 为什么很多强化学习框架要内置vLLM这样的推理引擎加速采样？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:03 | [link](https://www.bilibili.com/video/BV16ath6fEbM) |
| 2545 | 227. PPO中的优势A是怎么来的？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:03 | [link](https://www.bilibili.com/video/BV1mTtf6SEhx) |
| 2546 | 228. PPO的价值网络是如何根据写到一半的答案猜平均分的？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:22 | [link](https://www.bilibili.com/video/BV163b46DE6F) |
| 2547 | 229. 为什么PPO的优势A是每个token一个，而GRPO是整段回答一个？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:10 | [link](https://www.bilibili.com/video/BV151Yu6uERg) |
| 2548 | 230. PPO的GAE是如何计算的？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:28 | [link](https://www.bilibili.com/video/BV1weYR65EjZ) |
| 2549 | 233. 大模型强化学习的价值网络和围棋的价值网络有何异同？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:32 | [link](https://www.bilibili.com/video/BV1eEeH6uEiN) |
| 2550 | 235. 如何从PPO每个token的目标函数推导出梯度？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:36 | [link](https://www.bilibili.com/video/BV1cXeA6PEVh) |
| 2551 | 246. 为什么大模型RL里每一步的奖励几乎都是0？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 2:31 | [link](https://www.bilibili.com/video/BV1Tsh96yEAY) |
| 2552 | 254. PPO里面的KL约束到底在防什么？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:48 | [link](https://www.bilibili.com/video/BV1L5HC6uE4H) |
| 2553 | 256. 为什么PPO里的KL约束用的是反向KL而非前向KL？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:44 | [link](https://www.bilibili.com/video/BV163Hm6dECv) |
| 2554 | 258. 什么是OPD（On-Policy Distillation）？【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 3:12 | [link](https://www.bilibili.com/video/BV1oQHR6rEvQ) |
| 2555 | 248. 新加坡-2026-会议留影【每天一个宝藏问题】 | - | AI 论文精读 | - | - | 0:15 | [link](https://www.bilibili.com/video/BV1bsaz63EV5) |
| 2556 | [1]. 跑通TritonBench测试LLM的算子生成能力(ACL2025)【每周一个宝藏实验】 | - | AI 论文精读 | - | - | 13:03 | [link](https://www.bilibili.com/video/BV12xZBBwEKf) |
| 2557 | [3] 从采摘200片三叶草开始训练一个简易无条件DDPM 【每周一个宝藏实验】 | - | AI 论文精读 | - | - | 14:52 | [link](https://www.bilibili.com/video/BV1PcfEBrEBs) |
| 2558 | [5] 快速上手FuctionCall和React：极简易百词斩Agent【每周一个宝藏实验】 | - | AI 论文精读 | - | - | 15:39 | [link](https://www.bilibili.com/video/BV1nUAazDEma) |
| 2559 | [7] 跑KernelBench测试LLM将PyTorch转译为CUDA代码的能力（ICML2025）【每周一个宝藏实验】 | - | AI 论文精读 | - | - | 10:40 | [link](https://www.bilibili.com/video/BV1gzPyzuERu) |
| 2560 | [9] 跑CUDA-L2测试和cuBLAS相比效果如何？【每周一个宝藏实验】 | - | AI 论文精读 | - | - | 7:53 | [link](https://www.bilibili.com/video/BV1QPwszCE39) |
| 2561 | [11] 跑robust-kbench测试LLM写算子，附Agent提示词【每周一个宝藏实验】 | - | AI 论文精读 | - | - | 2:30 | [link](https://www.bilibili.com/video/BV1vxAszpE3P) |
| 2562 | [13] AutoDL上部署龙虾，它能帮忙测试算子性能吗？【每周一个宝藏实验】 | - | AI 论文精读 | - | - | 3:10 | [link](https://www.bilibili.com/video/BV1XMX5BZEGF) |
| 2563 | 1. BitNet 1.58b：微软开源的3值量化模型【每天一个宝藏名词】 | - | AI 论文精读 | - | - | 0:27 | [link](https://www.bilibili.com/video/BV1kG6jBSE3u) |
| 2564 | 2. AWQ：一种保护关键权重的LLM量化算法【每天一个宝藏名词】 | - | AI 论文精读 | - | - | 0:27 | [link](https://www.bilibili.com/video/BV16H6EBHEP5) |
| 2565 | 3. GPTQ：一种纯数学的LLM量化方法【每天一个宝藏名词】 | - | AI 论文精读 | - | - | 0:32 | [link](https://www.bilibili.com/video/BV1aXzXBNE4A) |
| 2566 | 4. SmoothQuant：一种转嫁压力的LLM量化方法【每天一个宝藏名词】 | - | AI 论文精读 | - | - | 0:25 | [link](https://www.bilibili.com/video/BV1RyzXB6Eyz) |
| 2567 | 7. SlimAttention：一种比FlashAttention更适合CPU的推理方案【每天一个宝藏名词】 | - | AI 论文精读 | - | - | 0:30 | [link](https://www.bilibili.com/video/BV1MUzZBVEtV) |
| 2568 | 8. PagedAttention：借鉴操作系统分页机制，内置于vLLM【每天一个宝藏名词】 | - | AI 论文精读 | - | - | 0:28 | [link](https://www.bilibili.com/video/BV1Ht6wBVEUX) |
| 2569 | 9. FlashAttention：将Attention的显存占用从平方级降到了线性级【每天一个宝藏名词】 | - | AI 论文精读 | - | - | 0:29 | [link](https://www.bilibili.com/video/BV1C66YBvECv) |
| 2570 | 10. NF4：QLoRA中的非均匀量化数据类型【每天一个宝藏名词】 | - | AI 论文精读 | - | - | 0:32 | [link](https://www.bilibili.com/video/BV1qA6BBKEck) |
| 2571 | 11. GQA：介于MHA和MQA之间，键值共享查询分组【每天一个宝藏名词】 | - | AI 论文精读 | - | - | 0:28 | [link](https://www.bilibili.com/video/BV19u6BBwEQ8) |
| 2572 | 12. RoPE：通过旋转矩阵让注意力只取决于相对位置【每天一个宝藏名词】 | - | AI 论文精读 | - | - | 0:28 | [link](https://www.bilibili.com/video/BV1gQ6iBREZw) |
| 2573 | 15. 投机解码：小模型草拟，大模型验证【每天一个宝藏名词】 | - | AI 论文精读 | - | - | 0:32 | [link](https://www.bilibili.com/video/BV1yS6zBXEVu) |
| 2574 | 27. 在线Softmax：通过修正比安全Softmax减少了一次循环【每天一个宝藏名词】 | - | AI 论文精读 | - | - | 0:32 | [link](https://www.bilibili.com/video/BV1c1c7zzEb4) |
| 2575 | 54. bf16：与FP32有相同的8位指数位，所以更适合模型训练【每天一个宝藏名词】 | - | AI 论文精读 | - | - | 0:47 | [link](https://www.bilibili.com/video/BV1DvPhzeE3R) |
| 2576 | 24. 思维树：大模型+DFS玩24点游戏成功率大增【每天一个宝藏名词】 | - | AI 论文精读 | - | - | 0:26 | [link](https://www.bilibili.com/video/BV1gtcbzDENr) |
| 2577 | 26. TinyML：MIT推出的大模型轻量化课，亲手量化一个本地llama模型【每天一个宝藏名词】 | - | AI 论文精读 | - | - | 0:30 | [link](https://www.bilibili.com/video/BV1CPcJzLELq) |
| 2578 | 5. CS336：斯坦福LLM神课，甚至包含洗数据和SFT【每天一个宝藏名词】 | - | AI 论文精读 | - | - | 0:30 | [link](https://www.bilibili.com/video/BV12pzXBREPY) |
| 2579 | 18. CCF-DDL：一个统计CCF分类和倒计时的宝藏网站【每天一个宝藏名词】 | - | AI 论文精读 | - | - | 0:32 | [link](https://www.bilibili.com/video/BV1Jif9BeEYE) |
| 2580 | 6. nano-vLLM：纯python实现的堪比vLLM的推理框架【每天一个宝藏名词】 | - | AI 论文精读 | - | - | 0:29 | [link](https://www.bilibili.com/video/BV1FTzfBcE3h) |
| 2581 | 38. miniSGLang：一个简化版SGLang，仅5000行python【每天一个宝藏名词】 | - | AI 论文精读 | - | - | 0:18 | [link](https://www.bilibili.com/video/BV1obA6zeEtE) |
| 2582 | 43. everything：比Windows默认文件搜索工具快很多，2MB的免费小工具【每天一个宝藏名词】 | - | AI 论文精读 | - | - | 0:26 | [link](https://www.bilibili.com/video/BV1iRArzqEvU) |
| 2583 | 48. NoteBookLM：Google的PPT制作神器，还有思维导图等一系列功能【每天一个宝藏名词】 | - | AI 论文精读 | - | - | 0:17 | [link](https://www.bilibili.com/video/BV1MUP5zDEmj) |
| 2584 | 50. 环境变量的工作原理：控制台启动时自动执行命令，让简写命令找到在哪执行【每天一个宝藏名词】 | - | AI 论文精读 | - | - | 1:06 | [link](https://www.bilibili.com/video/BV1zXP7zyEbD) |

## Per entry

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
- **1、PyTorch介绍与张量的创建** - [B station](https://www.bilibili.com/video/BV1ov411M7xL)
- **2、PyTorch张量的运算API（上）** - [B station](https://www.bilibili.com/video/BV1wQ4y1q7Bm)
- **3、PyTorch张量的运算API（下）** - [B station](https://www.bilibili.com/video/BV1Hq4y1R7dM)
- **4、PyTorch的Dataset与DataLoader详细使用教程** - [B station](https://www.bilibili.com/video/BV1yP4y1L7cC)
- **5、深入剖析PyTorch DataLoader源码** - [B station](https://www.bilibili.com/video/BV1kq4y1G75V)
- **6、PyTorch中搭建分类网络实例** - [B station](https://www.bilibili.com/video/BV1VF411a7oz)
- **7、深入剖析PyTorch nn.Module源码** - [B station](https://www.bilibili.com/video/BV1ch411b7yP)
- **8、深入剖析PyTorch的state_dict、parameters、modules源码** - [B station](https://www.bilibili.com/video/BV12g411K7oq)
- **9、深入剖析PyTorch的nn.Sequential及ModuleList源码** - [B station](https://www.bilibili.com/video/BV1Cb4y187H1)
- **10、PyTorch autograd使用教程** - [B station](https://www.bilibili.com/video/BV1vL411u7bL)
- **11、PyTorch中如何进行向量微分、矩阵微分与计算雅克比行列式** - [B station](https://www.bilibili.com/video/BV1Xr4y1r7wa)
- **12、如何在PyTorch中训练模型** - [B station](https://www.bilibili.com/video/BV1wL411g7rv)
- **13、详细推导自动微分Forward与Reverse模式** - [B station](https://www.bilibili.com/video/BV1PF411h7Ew)
- **14、保存与加载PyTorch训练的模型和超参数** - [B station](https://www.bilibili.com/video/BV1U341187TM)
- **15、Dropout原理以及其TF/Torch/Numpy源码实现** - [B station](https://www.bilibili.com/video/BV1gL4y1p7ww)
- **16、PyTorch中进行卷积残差模块算子融合** - [B station](https://www.bilibili.com/video/BV1sU4y1u7TM)
- **17、ConvMixer模型原理及其PyTorch逐行实现** - [B station](https://www.bilibili.com/video/BV1K34y1o74P)
- **18、深入剖析PyTorch中的Transformer API源码** - [B station](https://www.bilibili.com/video/BV1o44y1Y7cp)
- **19、Transformer模型Encoder原理精讲及其PyTorch逐行实现** - [B station](https://www.bilibili.com/video/BV1cP4y1V7GF)
- **20、Transformer模型Decoder原理精讲及其PyTorch逐行实现** - [B station](https://www.bilibili.com/video/BV1Qg411N74v)
- **21、Transformer Masked loss原理精讲及其PyTorch逐行实现** - [B station](https://www.bilibili.com/video/BV1dh411s7FW)
- **22、PyTorch nn.Conv2d卷积网络使用教程** - [B station](https://www.bilibili.com/video/BV1644y1h7LN)
- **23、手写并验证滑动相乘实现PyTorch二维卷积** - [B station](https://www.bilibili.com/video/BV1dP4y137er)
- **24、手写并验证向量内积实现PyTorch二维卷积** - [B station](https://www.bilibili.com/video/BV1Qb4y1i7n5)
- **25、手写实现nn.TransposedConv转置卷积** - [B station](https://www.bilibili.com/video/BV1fM4y1F7j5)
- **26、手写卷积与转置卷积的代码总结** - [B station](https://www.bilibili.com/video/BV13U4y1K7op)
- **27、手写实现PyTorch的DilatedConv和GroupConv** - [B station](https://www.bilibili.com/video/BV1UY411W7W8)
- **28、Vision Transformer(ViT)模型原理及PyTorch逐行实现** - [B station](https://www.bilibili.com/video/BV1cS4y1M7wo)
- **29、PyTorch RNN的原理及其手写复现** - [B station](https://www.bilibili.com/video/BV13i4y1R7jB)
- **30、PyTorch LSTM和LSTMP的原理及其手写复现** - [B station](https://www.bilibili.com/video/BV1zq4y1m7aH)
- **31、PyTorch GRU的原理及其手写复现** - [B station](https://www.bilibili.com/video/BV1jm4y1Q7uh)
- **32、基于PyTorch的文本分类项目模型与训练代码讲解** - [B station](https://www.bilibili.com/video/BV1eD4y1F7o4)
- **33、完整讲解PyTorch多GPU分布式训练代码编写** - [B station](https://www.bilibili.com/video/BV1xZ4y1S7dG)
- **34、Swin Transformer论文精讲及其PyTorch逐行复现** - [B station](https://www.bilibili.com/video/BV1kF411v7vg)
- **35、基于PyTorch手写Attention-based Seq2Seq模型** - [B station](https://www.bilibili.com/video/BV1ML411w7k7)
- **36、PyTorch训练加速技巧与爱因斯坦标示法** - [B station](https://www.bilibili.com/video/BV1ZY411b78A)
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
- **【论文拯救指南】干货！五分钟学会Endnote神器自动生成毕业论文参考文献引用格式，本科毕设和研究生小白进** - [pan.baidu.com](https://pan.baidu.com/s/1hkz_Gj6hTIIFwoYhYwcQ7A) | [B station](https://www.bilibili.com/video/BV1Qa4y1i7pA)
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
- **【麦小哲】科研小白如何快速高效阅读文献？宝藏方法推荐，建议收藏** - [updf.cn](https://www.updf.cn/pdf-edu/) | [B station](https://www.bilibili.com/video/BV1kw411n7DL)
- **[论文简析]VAE: Auto-encoding Variational Bayes[1312.6114]** - [arXiv:1312.6114](https://arxiv.org/abs/1312.6114) | [arxiv.org](https://arxiv.org/abs/1312.6114) | [B station](https://www.bilibili.com/video/BV1q64y1y7J2)
- **[论文简析]ViT: Vision Transformer[2010.11929]** - [arXiv:2010.11929](https://arxiv.org/abs/2010.11929) | [arxiv.org](https://arxiv.org/abs/2010.11929) | [github.com](https://github.com/google-research/vision_transformer) | [B station](https://www.bilibili.com/video/BV1di4y1N7pc)
- **[论文简析]How Do Vision Transformers Work?[2202.06709]** - [arXiv:2202.06709](https://arxiv.org/abs/2202.06709) | [arxiv.org](http://arxiv.org/abs/2202.06709) | [github.com](https://github.com/xxxnell/how-do-vits-work) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1UF41147AG)
- **[论文简析]Swin Transformer: Hierarchical ViT using Shifted Windows[2103.14030]** - [arXiv:2103.14030](https://arxiv.org/abs/2103.14030) | [arxiv.org](http://arxiv.org/abs/2103.14030) | [github.com](https://github.com/microsoft/Swin-Transformer) | [B station](https://www.bilibili.com/video/BV1e84y1F7Sc)
- **[论文简析]DETR: End-to-End Object Detection with Transfromers[2005.12872]** - [arXiv:2005.12872](https://arxiv.org/abs/2005.12872) | [arxiv.org](https://arxiv.org/abs/2005.12872) | [github.com](https://github.com/facebookresearch/detr) | [B station](https://www.bilibili.com/video/BV1T64y1D7NY)
- **[论文简析]NeRF: Representing Scenes as Neural Radiance Fields...[2003.08934]** - [arXiv:2003.08934](https://arxiv.org/abs/2003.08934) | [arxiv.org](http://arxiv.org/abs/2003.08934) | [github.com](https://github.com/bmild/nerf) | [youtube.com](https://www.youtube.com/watch?v=dPWLybp4LL0) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1mV4y1M7TB)
- **[论文简析]Deep Unsupervised Learning using Nonequilibrium Thermodynamics[1503.03585]** - [arXiv:1503.03585](https://arxiv.org/abs/1503.03585) | [arxiv.org](http://arxiv.org/abs/1503.03585) | [github.com](https://github.com/Sohl-Dickstein/Diffusion-Probabilistic-Models) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV19v4y1C7De)
- **[论文速览]LoRA: Low-Rank Adaptation of Large Language Models[2106.09685]** - [arXiv:2106.09685](https://arxiv.org/abs/2106.09685) | [arxiv.org](http://arxiv.org/abs/2106.09685) | [github.com](https://github.com/microsoft/LoRA) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1wX4y1s7an)
- **[论文速览]Flamingo: a Visual Language Model for Few-Shot Learning[2204.14198]** - [arXiv:2204.14198](https://arxiv.org/abs/2204.14198) | [arxiv.org](http://arxiv.org/abs/2204.14198) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1pu411G7ce)
- **[论文简析]A Generalist Agent / Gato[2205.06175]** - [arXiv:2205.06175](https://arxiv.org/abs/2205.06175) | [arxiv.org](https://arxiv.org/abs/2205.06175) | [github.com](https://github.com/OrigamiDream/gato) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1EK421k7Sy)
- **[论文简析]Does SSL Really Improve RL from Pixels?[2206.05266]** - [arXiv:2206.05266](https://arxiv.org/abs/2206.05266) | [arxiv.org](https://arxiv.org/abs/2206.05266) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1gM411r7wq)
- **[论文简析]Dreamer V2[2010.02193]** - [danijar.com](https://danijar.com/project/dreamerv2/) | [ai.googleblog.com](https://ai.googleblog.com/2021/02/mastering-atari-with-discrete-world.html) | [B station](https://www.bilibili.com/video/BV15o4y1R7kT)
- **[论文简析]World Models[1803.10122]** - [arXiv:1803.10122](https://arxiv.org/abs/1803.10122) | [arxiv.org](https://arxiv.org/abs/1803.10122) | [worldmodels.github.io](https://worldmodels.github.io/) | [youtube.com](https://www.youtube.com/watch?v=HzA8LRqhujk) | [B station](https://www.bilibili.com/video/BV1oz4y117qk)
- **[论文简析]Transformers are Sample Efficient World Models[2209.00588]** - [arXiv:2209.00588](https://arxiv.org/abs/2209.00588) | [arxiv.org](http://arxiv.org/abs/2209.00588) | [github.com](https://github.com/eloialonso/iris) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1i24y1Z78Q)
- **[论文简析]Reinforcement Learning with Augmented Data: RAD[2004.14990]** - [arXiv:2004.14990](https://arxiv.org/abs/2004.14990) | [arxiv.org](http://arxiv.org/abs/2004.14990) | [github.com](https://www.github.com/MishaLaskin/rad) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1ZS4y1h77B)
- **[论文简析]CURL[2004.04136]** - [github.com](https://github.com/MishaLaskin/curl) | [B station](https://www.bilibili.com/video/BV14v411h7sq)
- **[论文简析]SPR: Data-Efficient RL with Self-Predictive Representations[2007.05929]** - [arXiv:2007.05929](https://arxiv.org/abs/2007.05929) | [arxiv.org](http://arxiv.org/abs/2007.05929) | [github.com](https://github.com/mila-iqia/spr) | [B station](https://www.bilibili.com/video/BV1bN411Q7Hz)
- **[论文简析]DrQ: Data regularized Q[2004.13649]** - [arXiv:2004.13649](https://arxiv.org/abs/2004.13649) | [arxiv.org](http://arxiv.org/abs/2004.13649) | [sites.google.com](https://sites.google.com/view/data-regularized-q) | [B station](https://www.bilibili.com/video/BV15p4y1h7Xu)
- **[论文简析]The Dormant Neuron Phenomenon in Deep Reinforcement Learning[2302.12902]** - [arXiv:2302.12902](https://arxiv.org/abs/2302.12902) | [arxiv.org](https://arxiv.org/abs/2302.12902) | [github.com](https://github.com/google/dopamine/tree/master/dopamine/labs/redo) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1r94y1w7tE)
- **[论文简析]XSkill: Cross Embodiment Skill Discovery[2307.09955]** - [arXiv:2307.09955](https://arxiv.org/abs/2307.09955) | [arxiv.org](http://arxiv.org/abs/2307.09955) | [xskill.cs.columbia.edu](https://xskill.cs.columbia.edu/) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1bj411L7yK)
- **[论文简析]Video Prediction Policy: A Generalist Robot Policy...[2412.14803]** - [arXiv:2412.14803](https://arxiv.org/abs/2412.14803) | [arxiv.org](https://arxiv.org/abs/2412.14803) | [video-prediction-policy.github.io](https://video-prediction-policy.github.io/) | [arxiv.org](https://arxiv.org/abs/2403.16998) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1hZugzdE4F)
- **[论文速览]Efficient Action Tokenization for Vision-Language-Action Model[2501.09747]** - [arXiv:2501.09747](https://arxiv.org/abs/2501.09747) | [arxiv.org](https://arxiv.org/abs/2501.09747) | [pi.website](https://www.pi.website/research/fast) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1TuFpeKEXQ)
- **[论文简析]Rainbow:Combining Improvements in Deep Reinforcement Learning[1710.02298]** - [arXiv:1710.02298](https://arxiv.org/abs/1710.02298) | [arxiv.org](http://arxiv.org/abs/1710.02298) | [github.com](https://github.com/Kaixhin/Rainbow) | [B station](https://www.bilibili.com/video/BV1W64y1x7MF)
- **[论文简析]PPG: Phasic Policy Gradient[2009.04416]** - [arXiv:2009.04416](https://arxiv.org/abs/2009.04416) | [arxiv.org](http://arxiv.org/abs/2009.04416) | [github.com](https://github.com/openai/phasic-policy-gradient) | [B station](https://www.bilibili.com/video/BV1uB4y1A7Ec)
- **[论文简析]SAC: Soft Actor-Critic Part 1[1801.01290]** - [arXiv:1801.01290](https://arxiv.org/abs/1801.01290) | [arxiv.org](http://arxiv.org/abs/1801.01290) | [B station](https://www.bilibili.com/video/BV1YK4y1T7b6)
- **[论文简析]SAC: Soft Actor-Critic Part 2[1812.05905]** - [arXiv:1812.05905](https://arxiv.org/abs/1812.05905) | [arxiv.org](http://arxiv.org/abs/1812.05905) | [B station](https://www.bilibili.com/video/BV13V411e7Qb)
- **[论文简析]C-Learning: Learning to .. via Recursive Classification[2011.08909]** - [arXiv:2011.08909](https://arxiv.org/abs/2011.08909) | [arxiv.org](http://arxiv.org/abs/2011.08909) | [ben-eysenbach.github.io](https://ben-eysenbach.github.io/c_learning/) | [B station](https://www.bilibili.com/video/BV1J64y1S7ZA)
- **[论文简析]Time-Contrastive Networks:Self-Supervised Learning from Video[1704.06888]** - [arXiv:1704.06888](https://arxiv.org/abs/1704.06888) | [arxiv.org](https://arxiv.org/abs/1704.06888) | [sermanet.github.io](https://sermanet.github.io/imitate/) | [B station](https://www.bilibili.com/video/BV1Sr4y1A7bp)
- **[论文速览]Diffusion Policy: Visuomotor Policy Learning via Action Diff.[2303.04137]** - [arXiv:2303.04137](https://arxiv.org/abs/2303.04137) | [arxiv.org](http://arxiv.org/abs/2303.04137) | [diffusion-policy.cs.columbia.edu](https://diffusion-policy.cs.columbia.edu/) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1Cu411Y7d7)
- **[论文速览]Decision Transformer: RL via Sequence Modeling[2106.01345]** - [arXiv:2106.01345](https://arxiv.org/abs/2106.01345) | [arxiv.org](http://arxiv.org/abs/2106.01345) | [sites.google.com](https://sites.google.com/berkeley.edu/decision-transformer) | [B station](https://www.bilibili.com/video/BV1zf4y1t7ka)
- **[论文简析]Visionary: Vision architecture discovery for robot learning[2103.14633]** - [arXiv:2103.14633](https://arxiv.org/abs/2103.14633) | [arxiv.org](http://arxiv.org/abs/2103.14633) | [B station](https://www.bilibili.com/video/BV1oo4y1k7Jo)
- **[论文简析]Neuroevolution of Self-interpretable Agents[2003.08165]** - [arXiv:2003.08165](https://arxiv.org/abs/2003.08165) | [arxiv.org](https://arxiv.org/abs/2003.08165) | [attentionagent.github.io](https://attentionagent.github.io/) | [youtube.com](https://www.youtube.com/watch?v=DTgeEWK_Wm0) | [B station](https://www.bilibili.com/video/BV17Z4y1w7sX)
- **[论文简析]QT-Opt: Scalable Deep RL for Vision-Based Robotic Manipulation[1806.10293]** - [arXiv:1806.10293](https://arxiv.org/abs/1806.10293) | [arxiv.org](http://arxiv.org/abs/1806.10293) | [sites.google.com](https://sites.google.com/view/qtopt) | [B station](https://www.bilibili.com/video/BV1Ey4y187bi)
- **[论文速览]DDPG&TD3[1509.02971][1802.09477]** - [B station](https://www.bilibili.com/video/BV1nU4y1u7h1)
- **[论文简析]SEER: Stored Embeddings for Efficient RL[2103.02886]** - [arXiv:2103.02886](https://arxiv.org/abs/2103.02886) | [arxiv.org](https://arxiv.org/abs/2103.02886) | [github.com](https://github.com/lili-chen/SEER) | [B station](https://www.bilibili.com/video/BV1rv411h7iS)
- **[论文简析]BCO: Behavioral Cloning from Observation[1805.01954]** - [arXiv:1805.01954](https://arxiv.org/abs/1805.01954) | [arxiv.org](http://arxiv.org/abs/1805.01954) | [B station](https://www.bilibili.com/video/BV1aN411X7YT)
- **[论文简析]A Framework for Efficient Robotic Manipulation[2012.07975]** - [arXiv:2012.07975](https://arxiv.org/abs/2012.07975) | [arxiv.org](http://arxiv.org/abs/2012.07975) | [sites.google.com](https://sites.google.com/view/efficient-robotic-manipulation) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1pL4y1u7KG)
- **[论文速览]VRL3: A Data-Driven Framework for Visual Deep Reinforcement L.[2202.10324]** - [arXiv:2202.10324](https://arxiv.org/abs/2202.10324) | [arxiv.org](http://arxiv.org/abs/2202.10324) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1R841157aG)
- **[论文速览]Mask-based Latent Reconstruction for Reinforcement Learning[2201.12096]** - [arXiv:2201.12096](https://arxiv.org/abs/2201.12096) | [arxiv.org](http://arxiv.org/abs/2201.12096) | [github.com](https://github.com/microsoft/Mask-based-Latent-Reconstruction) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV12v4y1z7BM)
- **[论文简析]Learning Invariant Representations for RL without Reconstructi[2006.10742]** - [arXiv:2006.10742](https://arxiv.org/abs/2006.10742) | [arxiv.org](http://arxiv.org/abs/2006.10742) | [sites.google.com](https://sites.google.com/view/deepbisim4control) | [B station](https://www.bilibili.com/video/BV1EK4y1K7EL)
- **[论文简析]Stabilizing transformers for reinforcement learning[1910.06764]** - [arXiv:1910.06764](https://arxiv.org/abs/1910.06764) | [arxiv.org](http://arxiv.org/abs/1910.06764) | [arxiv.org](http://arxiv.org/abs/1901.02860) | [B station](https://www.bilibili.com/video/BV1Jf4y1s7ac)
- **[论文简析]Efficient Transformers in RL using Actor-Learner Distillation[2104.01655]** - [arXiv:2104.01655](https://arxiv.org/abs/2104.01655) | [arxiv.org](http://arxiv.org/abs/2104.01655) | [B station](https://www.bilibili.com/video/BV1wZ4y1w7wP)
- **[论文速览]NeRF-RL: Reinforcement Learning with Neural Radiance Fields[2206.01634]** - [arXiv:2206.01634](https://arxiv.org/abs/2206.01634) | [arxiv.org](https://arxiv.org/abs/2206.01634) | [dannydriess.github.io](https://dannydriess.github.io/nerf-rl) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1tG4y1V7hn)
- **[论文简析]DADS: Dynamics-Aware Unsupervised Discovery of Skills[1907.01657]** - [arXiv:1907.01657](https://arxiv.org/abs/1907.01657) | [arxiv.org](http://arxiv.org/abs/1907.01657) | [sites.google.com](https://sites.google.com/view/dads-skill) | [B station](https://www.bilibili.com/video/BV165411w71J)
- **[论文简析]Off-DADS: Emergent Real-World Robotic Skills via off policy RL[2004.12974]** - [arXiv:2004.12974](https://arxiv.org/abs/2004.12974) | [arxiv.org](http://arxiv.org/abs/2004.12974) | [sites.google.com](https://sites.google.com/view/dads-skill) | [B station](https://www.bilibili.com/video/BV18y4y1h7P9)
- **[论文速览]Stabilizing Deep Q-Learning with ConvNets and ViT...[2107.00644]** - [arXiv:2107.00644](https://arxiv.org/abs/2107.00644) | [arxiv.org](http://arxiv.org/abs/2107.00644) | [nicklashansen.github.io](https://nicklashansen.github.io/SVEA) | [B station](https://www.bilibili.com/video/BV12w411f74a)
- **[论文简析]Behavior From the Void: Unsupervised Active Pre-Training[2103.04551]** - [arXiv:2103.04551](https://arxiv.org/abs/2103.04551) | [arxiv.org](http://arxiv.org/abs/2103.04551) | [B station](https://www.bilibili.com/video/BV1By4y1t7aK)
- **[论文速览]Self-Supervised Policy Adaptation during Deployment[2007.04309]** - [arXiv:2007.04309](https://arxiv.org/abs/2007.04309) | [arxiv.org](http://arxiv.org/abs/2007.04309) | [nicklashansen.github.io](https://nicklashansen.github.io/PAD/) | [B station](https://www.bilibili.com/video/BV1t54y1J7pd)
- **[论文简析]RL-CycleGAN: Reinforcement Learning Aware Simulation-To-Real[2006.09001]** - [arXiv:2006.09001](https://arxiv.org/abs/2006.09001) | [arxiv.org](http://arxiv.org/abs/2006.09001) | [B station](https://www.bilibili.com/video/BV1L54y1n7d3)
- **[论文速览]Synthetic Experience Replay[2303.06614]** - [arXiv:2303.06614](https://arxiv.org/abs/2303.06614) | [arxiv.org](http://arxiv.org/abs/2303.06614) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1wx4y1P7hD)
- **[论文简析]Contrastive Language, Action, and State Pre-training...[2304.10782]** - [arXiv:2304.10782](https://arxiv.org/abs/2304.10782) | [arxiv.org](http://arxiv.org/abs/2304.10782) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1UF411U7zk)
- **[论文速览]Implicit Behavioral Cloning / IBC[2109.00137]** - [arXiv:2109.00137](https://arxiv.org/abs/2109.00137) | [arxiv.org](http://arxiv.org/abs/2109.00137) | [implicitbc.github.io](https://implicitbc.github.io/) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV18N411J7FD)
- **[论文夕拾]Diffusion Models for Robotics** - [arXiv:2302.00111](https://arxiv.org/abs/2302.00111) | [arxiv.org](https://arxiv.org/abs/2302.00111) | [universal-policy.github.io](https://universal-policy.github.io/unipi/) | [arxiv.org](https://arxiv.org/abs/2302.11550) | [diffusion-rosie.github.io](https://diffusion-rosie.github.io/) | [B station](https://www.bilibili.com/video/BV1mV411c7na)
- **[论文简析]Crossway Diffusion: Improving Diffusion-based ... via SSL[2307.01849]** - [arXiv:2307.01849](https://arxiv.org/abs/2307.01849) | [arxiv.org](https://arxiv.org/abs/2307.01849) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1Yp4y1F7nv)
- **[论文速览]A Self-Improving Generalist Agent for Robotic Manipulation[2306.11706]** - [arXiv:2306.11706](https://arxiv.org/abs/2306.11706) | [arxiv.org](https://arxiv.org/abs/2306.11706) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1cx4y1y7PZ)
- **[论文速览]OpenVLA: An Open-Source Vision-Language-Action Model[2406.09246]** - [arXiv:2406.09246](https://arxiv.org/abs/2406.09246) | [arxiv.org](https://arxiv.org/abs/2406.09246) | [openvla.github.io](https://openvla.github.io/) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1m1421C7m7)
- **[论文速览]LLaRA: Supercharging Robot Learning Data for VLM Policy[2406.20095]** - [arXiv:2406.20095](https://arxiv.org/abs/2406.20095) | [arxiv.org](https://arxiv.org/abs/2406.20095) | [github.com](https://github.com/LostXine/LLaRA) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV174421D7tW)
- **[论文速览]GENIMA: Generative Image as Action Models[2407.07875]** - [arXiv:2407.07875](https://arxiv.org/abs/2407.07875) | [arxiv.org](https://arxiv.org/abs/2407.07875) | [github.com](https://github.com/MohitShridhar/genima) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV17S421971u)
- **[论文夕拾]Robot Manipulation in a Language Model Era** - [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1BdCFYmEpa)
- **[论文速览]Latent Action Pretraining from Videos[2410.11758]** - [arXiv:2410.11758](https://arxiv.org/abs/2410.11758) | [arxiv.org](https://arxiv.org/abs/2410.11758) | [latentactionpretraining.github.io](https://latentactionpretraining.github.io/) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV144KPeYE9v)
- **[论文速览]π_0: A Vision-Language-Action Flow Model for General Robot...[2410.24164]** - [arXiv:2410.24164](https://arxiv.org/abs/2410.24164) | [arxiv.org](https://arxiv.org/abs/2410.24164) | [github.com](https://github.com/Physical-Intelligence/openpi) | [physicalintelligence.company](https://www.physicalintelligence.company/download/pi0.pdf) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV142uFzWEdY)
- **[论文简析]DreamVLA: A Vision-Language-Action Model Dreamed...[2507.04447]** - [arXiv:2507.04447](https://arxiv.org/abs/2507.04447) | [arxiv.org](https://arxiv.org/abs/2507.04447) | [github.com](https://github.com/Zhangwenyao1/DreamVLA) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV116utzwEZs)
- **[论文简析]Representation Learning with Contrastive Predictive Coding[1807.03748]** - [arXiv:1807.03748](https://arxiv.org/abs/1807.03748) | [arxiv.org](http://arxiv.org/abs/1807.03748) | [B station](https://www.bilibili.com/video/BV1fK4y1o7A1)
- **[论文速览]Data-Efficient Image Recog with Contrastive Predictive Coding[1905.09272]** - [arXiv:1905.09272](https://arxiv.org/abs/1905.09272) | [arxiv.org](http://arxiv.org/abs/1905.09272) | [B station](https://www.bilibili.com/video/BV1GU4y1H7b6)
- **[论文简析]SimCLR: A simple framework for contrastive learning[2002.05709]** - [arXiv:2002.05709](https://arxiv.org/abs/2002.05709) | [arxiv.org](http://arxiv.org/abs/2002.05709) | [B station](https://www.bilibili.com/video/BV1Cp4y1b7ex)
- **[论文简析]SwAV: Swapping Assignments between multiple Views[2006.09882]** - [arXiv:2006.09882](https://arxiv.org/abs/2006.09882) | [arxiv.org](http://arxiv.org/abs/2006.09882) | [github.com](https://github.com/facebookresearch/swav) | [B station](https://www.bilibili.com/video/BV1754y187Ki)
- **[论文简析]MoCo: Momentum Contrast Learning[1911.05722/2003.04297]** - [B station](https://www.bilibili.com/video/BV1av411874e)
- **[论文简析]BYOL: Bootstrap Your Own Latent[2006.07733]** - [arXiv:2006.07733](https://arxiv.org/abs/2006.07733) | [arxiv.org](https://arxiv.org/abs/2006.07733) | [github.com](https://github.com/deepmind/deepmind-research/tree/master/byol) | [B station](https://www.bilibili.com/video/BV1ki4y1T7X4)
- **[论文简析]DINO Emerging Properties in SelfSupervised Vision Transformers[2104.14294]** - [arXiv:2104.14294](https://arxiv.org/abs/2104.14294) | [arxiv.org](http://arxiv.org/abs/2104.14294) | [github.com](https://github.com/facebookresearch/dino) | [B station](https://www.bilibili.com/video/BV1H54y157kj)
- **[论文简析]SimSiam: Exploring Simple Siamese Representation Learning[2011.10566]** - [arXiv:2011.10566](https://arxiv.org/abs/2011.10566) | [arxiv.org](https://arxiv.org/abs/2011.10566) | [github.com](https://github.com/PatrickHua/SimSiam) | [B station](https://www.bilibili.com/video/BV1Ah411Q7Lb)
- **[论文简析]Barlow Twins:Self-Supervised Learning via Redundancy Reduction[2103.03230]** - [arXiv:2103.03230](https://arxiv.org/abs/2103.03230) | [arxiv.org](https://arxiv.org/abs/2103.03230) | [github.com](https://github.com/facebookresearch/barlowtwins) | [B station](https://www.bilibili.com/video/BV1gZ4y1P7U1)
- **[论文速览]iBOT: Image BERT Pre-Training with Online Tokenizer[2111.07832]** - [arXiv:2111.07832](https://arxiv.org/abs/2111.07832) | [arxiv.org](http://arxiv.org/abs/2111.07832) | [github.com](https://github.com/bytedance/ibot) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1uM4y1q7Pa)
- **[论文简析]Evolving Losses for Unsupervised Video Representation Learning[2002.12177]** - [arXiv:2002.12177](https://arxiv.org/abs/2002.12177) | [arxiv.org](https://arxiv.org/abs/2002.12177) | [B station](https://www.bilibili.com/video/BV1Pp4y1h7Ke)
- **[论文简析]Broaden Your Views for Self-Supervised Video Learning[2103.16559]** - [arXiv:2103.16559](https://arxiv.org/abs/2103.16559) | [arxiv.org](http://arxiv.org/abs/2103.16559) | [B station](https://www.bilibili.com/video/BV1LQ4y1i7Zv)
- **[论文速览]Self-supervised Video Transformer[2112.01514]** - [arXiv:2112.01514](https://arxiv.org/abs/2112.01514) | [arxiv.org](https://arxiv.org/abs/2112.01514) | [github.com](https://github.com/kahnchana/svt) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV17Y4y1g7Jw)
- **[论文简析]Extreme Masking for Learning Instance and Distributed Visual..[2206.04667]** - [arXiv:2206.04667](https://arxiv.org/abs/2206.04667) | [arxiv.org](http://arxiv.org/abs/2206.04667) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1sY4y1G7St)
- **[论文简析]Learning by Aligning Videos in Time[2103.17260]** - [arXiv:2103.17260](https://arxiv.org/abs/2103.17260) | [arxiv.org](http://arxiv.org/abs/2103.17260) | [B station](https://www.bilibili.com/video/BV13f4y1b7Nt)
- **[论文简析]Probabilistic Representations for Video Contrastive Learning[2204.03946]** - [arXiv:2204.03946](https://arxiv.org/abs/2204.03946) | [arxiv.org](http://arxiv.org/abs/2204.03946) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1RT4y1Y73n)
- **[论文简析]Propagate Yourself: Exploring Pixel-Level Consistency...[2011.10043]** - [arXiv:2011.10043](https://arxiv.org/abs/2011.10043) | [arxiv.org](http://arxiv.org/abs/2011.10043) | [github.com](https://github.com/zdaxie/PixPro) | [B station](https://www.bilibili.com/video/BV1hV411x7wL)
- **[论文简析]Location-Aware Self-Supervised Transformers for Semantic Seg.[2212.02400]** - [arXiv:2212.02400](https://arxiv.org/abs/2212.02400) | [arxiv.org](http://arxiv.org/abs/2212.02400) | [github.com](https://github.com/google-research/scenic/tree/main/scenic/projects/) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1wk4y1i7eH)
- **[论文简析]Rethinking Pre-training and Self-training[2006.06882]** - [arXiv:2006.06882](https://arxiv.org/abs/2006.06882) | [arxiv.org](http://arxiv.org/abs/2006.06882) | [github.com](https://github.com/tensorflow/tpu/tree/master/models/official/detection/projects/self_training) | [B station](https://www.bilibili.com/video/BV1pK4y1U7ts)
- **[论文简析]Energy-Inspired Self-Supervised Pretraining for Vision Models[2302.01384]** - [arXiv:2302.01384](https://arxiv.org/abs/2302.01384) | [arxiv.org](http://arxiv.org/abs/2302.01384) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1hg4y1H7Gj)
- **[论文简析]Humble Teachers Teach Better Students for Semi-Supervised Object Detection** - [github.com](https://github.com/lryta/HumbleTeacher) | [B station](https://www.bilibili.com/video/BV1SK4y1u7ix)
- **[论文简析]Towards Better Understanding of Self-Supervised Representation[2203.01881]** - [arXiv:2203.01881](https://arxiv.org/abs/2203.01881) | [arxiv.org](http://arxiv.org/abs/2203.01881) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1fG411n7EC)
- **[论文简析]TransRank: SS Video...Ranking-based Transformation Recognition[2205.02028]** - [arXiv:2205.02028](https://arxiv.org/abs/2205.02028) | [arxiv.org](http://arxiv.org/abs/2205.02028) | [github.com](https://github.com/kennymckormick/TransRank) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1zS4y1e7uY)
- **[论文速览]Object Discovery and Representation Networks[2203.08777]** - [arXiv:2203.08777](https://arxiv.org/abs/2203.08777) | [arxiv.org](http://arxiv.org/abs/2203.08777) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1n34y1b7Uo)
- **[论文速览]Efficient Visual Pretraining with Contrastive Detection[2103.10957]** - [arXiv:2103.10957](https://arxiv.org/abs/2103.10957) | [arxiv.org](http://arxiv.org/abs/2103.10957) | [github.com](https://github.com/deepmind/detcon) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1bY411n7BP)
- **[论文简析]Directional SSL for Heavy Image Augmentations[2110.13555]** - [arXiv:2110.13555](https://arxiv.org/abs/2110.13555) | [arxiv.org](http://arxiv.org/abs/2110.13555) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV19U4y1o7SQ)
- **[论文速览]Invariant Information Clustering for Unsupervised Image...[1807.06653]** - [arXiv:1807.06653](https://arxiv.org/abs/1807.06653) | [arxiv.org](http://arxiv.org/abs/1807.06653) | [github.com](https://github.com/xu-ji/IIC) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1t34y1t72d)
- **[论文速览]Video Rep. Learning by Recognizing Temporal Transformations[2007.10730]** - [arXiv:2007.10730](https://arxiv.org/abs/2007.10730) | [arxiv.org](http://arxiv.org/abs/2007.10730) | [github.com](https://github.com/sjenni/temporal-ssl) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1qU4y1X7cg)
- **[论文简析]β-VAE Learning basic visual concepts with a constrained variational...** - [openreview.net](https://openreview.net/forum?id=Sy2fzU9gl) | [B station](https://www.bilibili.com/video/BV1644y1q7Aj)
- **[论文简析]DCLGAN/SimDCL: Dual Contrastive Learning[2104.07689]** - [arXiv:2104.07689](https://arxiv.org/abs/2104.07689) | [arxiv.org](http://arxiv.org/abs/2104.07689) | [github.com](https://github.com/JunlinHan/DCLGAN) | [B station](https://www.bilibili.com/video/BV15v411j7N7)
- **[论文简析]Generative Scene Inference and Sampling...[1907.13052]** - [arXiv:1907.13052](https://arxiv.org/abs/1907.13052) | [arxiv.org](http://arxiv.org/abs/1907.13052) | [github.com](https://github.com/applied-ai-lab/genesis) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1aZ4y1R7Ne)
- **[论文简析]An Empirical Study of Training Self-Supervised ViT[2104.02057]** - [arXiv:2104.02057](https://arxiv.org/abs/2104.02057) | [arxiv.org](http://arxiv.org/abs/2104.02057) | [B station](https://www.bilibili.com/video/BV1UX4y1g7Dn)
- **[论文速览]Multi-Object ... with Iterative Variational Inference[1903.00450]** - [arXiv:1903.00450](https://arxiv.org/abs/1903.00450) | [arxiv.org](http://arxiv.org/abs/1903.00450) | [github.com](https://github.com/zhixuan-lin/IODINE) | [B station](https://www.bilibili.com/video/BV15a41127C9)
- **[论文简析]MONet: Unsupervised Scene Decomposition and Representation[1901.11390]** - [arXiv:1901.11390](https://arxiv.org/abs/1901.11390) | [arxiv.org](http://arxiv.org/abs/1901.11390) | [github.com](https://github.com/baudm/MONet-pytorch) | [B station](https://www.bilibili.com/video/BV1CT4y1y7Hc)
- **[论文简析]Leveraging BG AUG to encourage semantic focus in SSCL[2103.12719]** - [arXiv:2103.12719](https://arxiv.org/abs/2103.12719) | [arxiv.org](http://arxiv.org/abs/2103.12719) | [B station](https://www.bilibili.com/video/BV1xX4y1G7Pe)
- **[论文简析]Object-Centric Learning with Slot Attention[2006.15055]** - [arXiv:2006.15055](https://arxiv.org/abs/2006.15055) | [arxiv.org](http://arxiv.org/abs/2006.15055) | [github.com](https://github.com/google-research/google-research/tree/master/slot_attention) | [B station](https://www.bilibili.com/video/BV1QL4y1s7NK)
- **[论文简析]Equivariant Contrastive Learning[2111.00899]** - [arXiv:2111.00899](https://arxiv.org/abs/2111.00899) | [arxiv.org](http://arxiv.org/abs/2111.00899) | [B station](https://www.bilibili.com/video/BV1jS4y1Z7Py)
- **[论文简析]Big Self-Supervised Models are Strong Semi-Supervised Learners[2006.10029]** - [arXiv:2006.10029](https://arxiv.org/abs/2006.10029) | [arxiv.org](http://arxiv.org/abs/2006.10029) | [github.com](https://github.com/google-research/simclr) | [B station](https://www.bilibili.com/video/BV1Ey4y1t7zK)
- **[论文简析]Keeping Your Eye on the Ball: Trajectory Attention...[2106.05392]** - [arXiv:2106.05392](https://arxiv.org/abs/2106.05392) | [arxiv.org](http://arxiv.org/abs/2106.05392) | [github.com](https://github.com/facebookresearch/Motionformer) | [B station](https://www.bilibili.com/video/BV1j3411i7jU)
- **[论文简析]Wasserstein Contrastive Representation Distillation: WCoRD[2012.08674]** - [arXiv:2012.08674](https://arxiv.org/abs/2012.08674) | [arxiv.org](http://arxiv.org/abs/2012.08674) | [B station](https://www.bilibili.com/video/BV1vw41197wC)
- **[论文速览]Masked Feature Prediction .Self-Supervised Visual Pre-Training[2112.09133]** - [arXiv:2112.09133](https://arxiv.org/abs/2112.09133) | [arxiv.org](http://arxiv.org/abs/2112.09133) | [github.com](https://github.com/facebookresearch/pytorchvideo) | [B station](https://www.bilibili.com/video/BV1YS4y1Q7Qj)
- **[论文速览]AugSelf: Improving Transferability...Augmentation-Aware..[2111.09613]** - [arXiv:2111.09613](https://arxiv.org/abs/2111.09613) | [arxiv.org](http://arxiv.org/abs/2111.09613) | [github.com](https://github.com/hankook/AugSelf) | [B station](https://www.bilibili.com/video/BV1Ei4y1Z7Ld)
- **[论文速览]Nearest-Neighbor Contrastive Learning of Visual Representations[2104.14548** - [arXiv:2104.14548](https://arxiv.org/abs/2104.14548) | [arxiv.org](http://arxiv.org/abs/2104.14548) | [B station](https://www.bilibili.com/video/BV12f4y1M7Qq)
- **[论文速览]Solving Inefficiency of Self-supervised Representation Learning[2104.0876]** - [arXiv:2104.08760](https://arxiv.org/abs/2104.08760) | [arxiv.org](http://arxiv.org/abs/2104.08760) | [github.com](https://github.com/wanggrun/triplet) | [B station](https://www.bilibili.com/video/BV1FL4y1z7jq)
- **[论文简析]VideoMoCo: ...Temporally Adversarial Examples[2103.05905]** - [arXiv:2103.05905](https://arxiv.org/abs/2103.05905) | [arxiv.org](http://arxiv.org/abs/2103.05905) | [github.com](https://github.com/tinapan-pt/VideoMoCo) | [B station](https://www.bilibili.com/video/BV13f4y137Wc)
- **[论文速览]Theia: Distilling Diverse Vision Foundation Models for Robot..[2407.20179]** - [arXiv:2407.20179](https://arxiv.org/abs/2407.20179) | [arxiv.org](https://arxiv.org/abs/2407.20179) | [github.com](https://github.com/bdaiinstitute/theia) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV18W42197So)
- **[论文速览]Long Short View Feature Decomposition via Contrastive Video...[2109.11593]** - [arXiv:2109.11593](https://arxiv.org/abs/2109.11593) | [arxiv.org](http://arxiv.org/abs/2109.11593) | [B station](https://www.bilibili.com/video/BV1pQ4y1Q74S)
- **[论文简析]Vi2CLR: Video and Image for Visual Contrastive Learning of Representation** - [B station](https://www.bilibili.com/video/BV1ZQ4y1i7Wa)
- **[论文速览]Generative Modeling by Estimating Gradients of the Data Dist[1907.05600]** - [arXiv:1907.05600](https://arxiv.org/abs/1907.05600) | [arxiv.org](http://arxiv.org/abs/1907.05600) | [github.com](https://github.com/ermongroup/ncsn) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1WY4y1Q7fy)
- **[论文简析]Unsupervised Learning of Object Keypoints for Perception..[1906.11883]** - [arXiv:1906.11883](https://arxiv.org/abs/1906.11883) | [arxiv.org](http://arxiv.org/abs/1906.11883) | [github.com](https://github.com/deepmind/deepmind-research/tree/master/transporter) | [B station](https://www.bilibili.com/video/BV15w411R7rB)
- **[论文简析]Progressive Stage-wise Learning for Unsupervised Feature.. [2106.05554]** - [arXiv:2106.05554](https://arxiv.org/abs/2106.05554) | [arxiv.org](http://arxiv.org/abs/2106.05554) | [B station](https://www.bilibili.com/video/BV1Fq4y1p7Ai)
- **[论文简析]Transf. Meta-learners for Implicit Neural Representations[2208.02801]** - [arXiv:2208.02801](https://arxiv.org/abs/2208.02801) | [arxiv.org](http://arxiv.org/abs/2208.02801) | [yinboc.github.io](https://yinboc.github.io/trans-inr) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1QV4y167S7)
- **[论文速览]Jigsaw Clustering for Unsupervised Visual Representation Learn[2104.00323]** - [arXiv:2104.00323](https://arxiv.org/abs/2104.00323) | [arxiv.org](http://arxiv.org/abs/2104.00323) | [github.com](https://github.com/dvlab-research/JigsawClustering) | [B station](https://www.bilibili.com/video/BV1Jg41177uE)
- **[论文速览]SS Video Representation Learning by Context&Motion Decoupling[2104.00862]** - [arXiv:2104.00862](https://arxiv.org/abs/2104.00862) | [arxiv.org](http://arxiv.org/abs/2104.00862) | [B station](https://www.bilibili.com/video/BV1qf4y157DW)
- **[论文简析]MixMAE & Mixed AE[2205.13137][2303.17152]** - [arXiv:2205.13137](https://arxiv.org/abs/2205.13137) | [arxiv.org](http://arxiv.org/abs/2205.13137) | [github.com](https://github.com/Sense-X/MixMIM) | [arxiv.org](http://arxiv.org/abs/2303.17152) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1cF411d77x)
- **[论文速览]Finite Scalar Quantization: VQ-VAE Made Simple[2309.15505]** - [arXiv:2309.15505](https://arxiv.org/abs/2309.15505) | [arxiv.org](http://arxiv.org/abs/2309.15505) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1N84y1S779)
- **[论文简析]DropPos: Pre-Training ViTs by Reconstructing Dropped Positions[2309.03576]** - [arXiv:2309.03576](https://arxiv.org/abs/2309.03576) | [arxiv.org](http://arxiv.org/abs/2309.03576) | [github.com](https://github.com/Haochen-Wang409/DropPos) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1fu411u77K)
- **[论文速览]SODA: Bottleneck Diffusion Models for Representation Learning[2311.17901]** - [arXiv:2311.17901](https://arxiv.org/abs/2311.17901) | [arxiv.org](https://arxiv.org/abs/2311.17901) | [soda-diffusion.github.io](https://soda-diffusion.github.io/) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1jw411t7Kq)
- **[论文简析]Deconstructing Denoising Diffusion Models for SSL[2401.14404]** - [arXiv:2401.14404](https://arxiv.org/abs/2401.14404) | [arxiv.org](http://arxiv.org/abs/2401.14404) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1bv421r7Sv)
- **[论文速览]Socratic Models: Zero-Shot Multimodal Reasoning[2204.00598]** - [arXiv:2204.00598](https://arxiv.org/abs/2204.00598) | [arxiv.org](http://arxiv.org/abs/2204.00598) | [github.com](https://github.com/google-research/google-research/tree/master/socraticmodels) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1cS4y1n7yn)
- **[论文简析]Large Language Models as General Pattern Machines[2307.04721]** - [arXiv:2307.04721](https://arxiv.org/abs/2307.04721) | [arxiv.org](http://arxiv.org/abs/2307.04721) | [general-pattern-machines.github.io](https://general-pattern-machines.github.io/) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1EM4y1W7w1)
- **[论文速览]LaFTer: Label-Free Tuning of Zero-shot Classifier...[2305.18287]** - [arXiv:2305.18287](https://arxiv.org/abs/2305.18287) | [arxiv.org](http://arxiv.org/abs/2305.18287) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1Rm4y1p72G)
- **[论文速览]OWL-ViT: Simple Open-Vocabulary Object Detection with ViT[2205.06230]** - [arXiv:2205.06230](https://arxiv.org/abs/2205.06230) | [arxiv.org](http://arxiv.org/abs/2205.06230) | [github.com](https://github.com/google-research/scenic/tree/main/scenic/projects/owl_vit) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1x8411S7eZ)
- **[论文简析]GroupViT: Semantic Segmentation Emerges from Text Supervision[2202.11094]** - [arXiv:2202.11094](https://arxiv.org/abs/2202.11094) | [arxiv.org](http://arxiv.org/abs/2202.11094) | [jerryxu.net](https://jerryxu.net/GroupViT/) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1Bv4y127gH)
- **[论文简析]VATT: Video-Audio-Text Transformer[2104.11178]** - [arXiv:2104.11178](https://arxiv.org/abs/2104.11178) | [arxiv.org](http://arxiv.org/abs/2104.11178) | [B station](https://www.bilibili.com/video/BV1554y1j71k)
- **[论文简析]End-to-End Video-Language Transformers..Masked Visual-token..[2111.12681]** - [arXiv:2111.12681](https://arxiv.org/abs/2111.12681) | [arxiv.org](http://arxiv.org/abs/2111.12681) | [github.com](https://github.com/tsujuifu/) | [B station](https://www.bilibili.com/video/BV1UM4y1c7fh)
- **[论文简析]TAN: Temporal Alignment Networks for Long-term Video[2204.02968]** - [arXiv:2204.02968](https://arxiv.org/abs/2204.02968) | [arxiv.org](http://arxiv.org/abs/2204.02968) | [github.com](https://github.com/TengdaHan/TemporalAlignNet) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1194y1y7mF)
- **[论文简析]Improving fine-grained understanding in image-text pre-training[2401.0986]** - [arXiv:2401.09865](https://arxiv.org/abs/2401.09865) | [arxiv.org](http://arxiv.org/abs/2401.09865) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV15A4m1G7zj)
- **[论文简析]End-to-End Learning... from Uncurated Instructional Videos[1912.06430]** - [arXiv:1912.06430](https://arxiv.org/abs/1912.06430) | [arxiv.org](http://arxiv.org/abs/1912.06430) | [di.ens.fr](https://www.di.ens.fr/willow/research/mil-nce/) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV173411u7JE)
- **[论文简析]Region-Aware Pretraining for Open-Vocab. Object Det. w/ ViT[2305.07011]** - [arXiv:2305.07011](https://arxiv.org/abs/2305.07011) | [arxiv.org](http://arxiv.org/abs/2305.07011) | [github.com](https://github.com/google-research/google-research/tree/master/fvlm/rovit) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1D14y1C7m8)
- **[论文简析]Toolformer: Language Models Can Teach Themselves to Use Tools[2302.04761]** - [arXiv:2302.04761](https://arxiv.org/abs/2302.04761) | [arxiv.org](http://arxiv.org/abs/2302.04761) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1BV4y1a7iU)
- **[论文速览]ViperGPT: Visual Inference via Python Execution for Reasoning[2303.08128]** - [arXiv:2303.08128](https://arxiv.org/abs/2303.08128) | [arxiv.org](http://arxiv.org/abs/2303.08128) | [viper.cs.columbia.edu](https://viper.cs.columbia.edu/) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1BV4y1879K)
- **[论文简析]VoxPoser: Composable 3D Value Maps for Robotic...[2307.05973]** - [arXiv:2307.05973](https://arxiv.org/abs/2307.05973) | [arxiv.org](http://arxiv.org/abs/2307.05973) | [voxposer.github.io](https://voxposer.github.io/) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV11h4y1j7D2)
- **[论文速览]LLaMA-Adapter: Efficient Fine-tuning..Zero-init Attention[2303.16199]** - [arXiv:2303.16199](https://arxiv.org/abs/2303.16199) | [arxiv.org](http://arxiv.org/abs/2303.16199) | [github.com](https://github.com/OpenGVLab/LLaMA-Adapter) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1Kp4y1L7ya)
- **[论文速览]Open-vocabulary Object Segmentation with Diffusion Models[2301.05221]** - [arXiv:2301.05221](https://arxiv.org/abs/2301.05221) | [arxiv.org](http://arxiv.org/abs/2301.05221) | [lipurple.github.io](https://lipurple.github.io/Grounded_Diffusion/) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1VV4y1e78c)
- **[论文速览]Open Vocab. Semantic Seg.  with Patch Aligned Contrastive...[2212.04994]** - [arXiv:2212.04994](https://arxiv.org/abs/2212.04994) | [arxiv.org](http://arxiv.org/abs/2212.04994) | [arxiv.org](http://arxiv.org/abs/2210.09996) | [github.com](https://github.com/kahnchana/clippy) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1w94y1z7ey)
- **[论文简析]Representation Learning via Global Temporal Alignment and ...[2105.05217]** - [arXiv:2105.05217](https://arxiv.org/abs/2105.05217) | [arxiv.org](http://arxiv.org/abs/2105.05217) | [github.com](https://github.com/hadjisma/VideoAlignment) | [B station](https://www.bilibili.com/video/BV1CM4y1T7nj)
- **[论文速览]LLaVA: Visual Instruction Tuning[2304.08485]** - [arXiv:2304.08485](https://arxiv.org/abs/2304.08485) | [arxiv.org](http://arxiv.org/abs/2304.08485) | [llava-vl.github.io](https://llava-vl.github.io/) | [arxiv.org](https://arxiv.org/abs/2306.00890) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1n14y1k7B9)
- **[论文速览]LongLoRA: Efficient Fine-tuning of Long-Context LLMs[2309.12307]** - [arXiv:2309.12307](https://arxiv.org/abs/2309.12307) | [arxiv.org](http://arxiv.org/abs/2309.12307) | [github.com](https://github.com/dvlab-research/LongLoRA) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1PN411n7KX)
- **[论文简析]CLIP Dense Inference Yields Open-Vocab ... For-Free[2309.14289]** - [arXiv:2309.14289](https://arxiv.org/abs/2309.14289) | [arxiv.org](http://arxiv.org/abs/2309.14289) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1Jj41187We)
- **[论文速览]Ferret: Refer and Ground Anything Anywhere at Any Granularity[2310.07704]** - [arXiv:2310.07704](https://arxiv.org/abs/2310.07704) | [arxiv.org](https://arxiv.org/abs/2310.07704) | [arxiv.org](https://arxiv.org/abs/2307.05222) | [arxiv.org](https://arxiv.org/abs/2305.17216) | [arxiv.org](https://arxiv.org/abs/2307.15818) | [B station](https://www.bilibili.com/video/BV11h4y1z7mn)
- **[论文速览]VLMs are Zero-Shot Reward Models for RL[2310.12921]** - [arXiv:2310.12921](https://arxiv.org/abs/2310.12921) | [arxiv.org](https://arxiv.org/abs/2310.12921) | [sites.google.com](https://sites.google.com/view/vlm-rm) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1ne411R74d)
- **[论文速览]CRG: Improving Grounding in VLM w/o training[2403.02325]** - [arXiv:2403.02325](https://arxiv.org/abs/2403.02325) | [arxiv.org](https://arxiv.org/abs/2403.02325) | [contrastive-region-guidance.github.io](https://contrastive-region-guidance.github.io/) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1y2421T7R3)
- **[论文速览]A Simple LLM Framework for Long-Range Video Question-Answering[2312.17235]** - [arXiv:2312.17235](https://arxiv.org/abs/2312.17235) | [arxiv.org](http://arxiv.org/abs/2312.17235) | [github.com](https://github.com/CeeZh/LLoVi) | [lilianweng.github.io](https://lilianweng.github.io/posts/2023-06-23-agent/) | [github.com](https://github.com/L1Xu4n/Awesome-ChatGPT-prompts-ZH_CN) | [B station](https://www.bilibili.com/video/BV1d2421N7VA)
- **[论文速览]Align before Fuse / ALBEF: ...[2107.07651]** - [arXiv:2107.07651](https://arxiv.org/abs/2107.07651) | [arxiv.org](https://arxiv.org/abs/2107.07651) | [github.com](https://github.com/salesforce/ALBEF/) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1fx4y1U7ui)
- **[论文速览]Bootstrapping Language-Image Pre-training...[2201.12086]** - [arXiv:2201.12086](https://arxiv.org/abs/2201.12086) | [arxiv.org](http://arxiv.org/abs/2201.12086) | [github.com](https://github.com/salesforce/BLIP) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1H1421Q7Ft)
- **[论文速览]BLIP-2 ...with Frozen Image Encoders and Large Language Models[2301.12597]** - [arXiv:2301.12597](https://arxiv.org/abs/2301.12597) | [arxiv.org](http://arxiv.org/abs/2301.12597) | [github.com](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1Ci42197ab)
- **[论文速览]Ferret-v2: An Improved...for Referring and Grounding with LLMs[2404.07973]** - [arXiv:2404.07973](https://arxiv.org/abs/2404.07973) | [arxiv.org](https://arxiv.org/abs/2404.07973) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV12F4m1N7Mc)
- **[论文速览]Token Turing Machines[2211.09119]** - [arXiv:2211.09119](https://arxiv.org/abs/2211.09119) | [arxiv.org](http://arxiv.org/abs/2211.09119) | [michaelryoo.com](http://michaelryoo.com/) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1dV4y1f7J4)
- **[论文简析]NeRF in the Wild: NeRF for Unconstrained Photo Collections[2008.02268]** - [arXiv:2008.02268](https://arxiv.org/abs/2008.02268) | [arxiv.org](http://arxiv.org/abs/2008.02268) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1iD4y1e7K9)
- **[论文简析]Exploring Self-attention for Image Recognition[2004.13621]** - [arXiv:2004.13621](https://arxiv.org/abs/2004.13621) | [arxiv.org](https://arxiv.org/abs/2004.13621) | [github.com](https://github.com/hszhao/SAN) | [youtube.com](https://www.youtube.com/watch?v=GuAsn4E3fP8) | [B station](https://www.bilibili.com/video/BV1nA411K7Z6)
- **[论文简析]FlowNet3D: Learning Scene Flow in 3D Point Clouds[1806.01411]** - [arXiv:1806.01411](https://arxiv.org/abs/1806.01411) | [arxiv.org](http://arxiv.org/abs/1806.01411) | [github.com](https://github.com/xingyul/flownet3d) | [B station](https://www.bilibili.com/video/BV1U3411j7Fg)
- **[论文简析]NeRV: Neural Representations for Videos[2110.13903]** - [arXiv:2110.13903](https://arxiv.org/abs/2110.13903) | [arxiv.org](http://arxiv.org/abs/2110.13903) | [github.com](https://github.com/haochen-rye/NeRV) | [B station](https://www.bilibili.com/video/BV1Nf4y1K7j5)
- **[论文简析]TokenLearner: What Can 8 Learned Tokens Do for Images and vids[2106.11297]** - [arXiv:2106.11297](https://arxiv.org/abs/2106.11297) | [arxiv.org](http://arxiv.org/abs/2106.11297) | [B station](https://www.bilibili.com/video/BV1of4y1t77m)
- **[论文简析]BiFormer: Vision Transformer with Bi-Level Routing Attention[2303.08810]** - [arXiv:2303.08810](https://arxiv.org/abs/2303.08810) | [arxiv.org](http://arxiv.org/abs/2303.08810) | [github.com](https://github.com/rayleizhu/BiFormer) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1tF4111774)
- **[论文简析]When Shift Operation Meets Vision Transformer[2201.10801]** - [arXiv:2201.10801](https://arxiv.org/abs/2201.10801) | [arxiv.org](http://arxiv.org/abs/2201.10801) | [B station](https://www.bilibili.com/video/BV1CF411n7at)
- **[论文简析]DeepLab V3/V3+[1706.05587/1802.02611]** - [B station](https://www.bilibili.com/video/BV1by4y1g76s)
- **[论文速览]Deformable Convolutional Networks; DCN[1703.06211]** - [arXiv:1703.06211](https://arxiv.org/abs/1703.06211) | [arxiv.org](http://arxiv.org/abs/1703.06211) | [github.com](https://github.com/msracver/Deformable-ConvNets) | [arxiv.org](https://arxiv.org/abs/1811.11168) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1C94y1272t)
- **[论文简析]DeepLab: Semantic Image Segmentation with DCN..[1606.00915]** - [arXiv:1606.00915](https://arxiv.org/abs/1606.00915) | [arxiv.org](http://arxiv.org/abs/1606.00915) | [B station](https://www.bilibili.com/video/BV1jf4y1Y7uM)
- **[论文简析]DAT: Vision Transformer with Deformable Attention[2201.00520]** - [arXiv:2201.00520](https://arxiv.org/abs/2201.00520) | [arxiv.org](http://arxiv.org/abs/2201.00520) | [github.com](https://github.com/LeapLabTHU/DAT) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1ir4y137BG)
- **[论文速览]Aggregating Nested Transformers[2105.12723]** - [arXiv:2105.12723](https://arxiv.org/abs/2105.12723) | [arxiv.org](http://arxiv.org/abs/2105.12723) | [github.com](https://github.com/google-research/nested-transformer) | [B station](https://www.bilibili.com/video/BV1yq4y1H7mT)
- **[论文简析]X3D: Expanding Architectures for Efficient Video Recognition[2004.04730]** - [arXiv:2004.04730](https://arxiv.org/abs/2004.04730) | [arxiv.org](http://arxiv.org/abs/2004.04730) | [github.com](https://github.com/facebookresearch/SlowFast) | [B station](https://www.bilibili.com/video/BV1qZ4y1F7Kf)
- **[论文简析]CeiT: Incorporating Convolution Designs into Visual Tr[2103.11816]** - [arXiv:2103.11816](https://arxiv.org/abs/2103.11816) | [arxiv.org](http://arxiv.org/abs/2103.11816) | [github.com](https://github.com/rishikksh20/CeiT-pytorch) | [B station](https://www.bilibili.com/video/BV19L4y1B7Ad)
- **[论文速览]iFormer: Inception Transformer[2205.12956]** - [arXiv:2205.12956](https://arxiv.org/abs/2205.12956) | [arxiv.org](http://arxiv.org/abs/2205.12956) | [github.com](https://github.com/sail-sg/iFormer) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV19L4y1P7ri)
- **[论文速览]Bottleneck Transformers for Visual Recognition[2101.11605]** - [arXiv:2101.11605](https://arxiv.org/abs/2101.11605) | [arxiv.org](http://arxiv.org/abs/2101.11605) | [B station](https://www.bilibili.com/video/BV1i64y1t7WN)
- **[论文简析]NAT: Neighborhood Attention Transformer[2204.07143]** - [arXiv:2204.07143](https://arxiv.org/abs/2204.07143) | [arxiv.org](http://arxiv.org/abs/2204.07143) | [github.com](https://github.com/SHI-) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1xF411g7LK)
- **[论文简析]XCiT: Cross-Covariance Image Transformers[2106.09681]** - [arXiv:2106.09681](https://arxiv.org/abs/2106.09681) | [arxiv.org](http://arxiv.org/abs/2106.09681) | [github.com](https://github.com/facebookresearch/xcit) | [B station](https://www.bilibili.com/video/BV1n64y1Q7RX)
- **[论文简析]DeiT: Data-efficient Image Transformers[2012.12877]** - [arxiv.org](https://arxiv.org/pdf/2012.12877.pdf) | [github.com](https://github.com/facebookresearch/deit) | [B station](https://www.bilibili.com/video/BV1L5411P7rV)
- **[论文简析]TNT: Transformer in Transformer[2103.00112]** - [arXiv:2103.00112](https://arxiv.org/abs/2103.00112) | [arxiv.org](https://arxiv.org/abs/2103.00112) | [github.com](https://github.com/lucidrains/transformer-in-transformer) | [B station](https://www.bilibili.com/video/BV1KK4y1U7Uq)
- **[论文简析]Tokens-to-Token ViT: Training ViT from Scratch on ImageNet[2101.11986]** - [arXiv:2101.11986](https://arxiv.org/abs/2101.11986) | [arxiv.org](http://arxiv.org/abs/2101.11986) | [github.com](https://github.com/yitu-opensource/T2T-ViT) | [B station](https://www.bilibili.com/video/BV1yv411L7xN)
- **[论文简析]Dynamic Vision Transformers with Adaptive Sequence Length[2105.15075]** - [arXiv:2105.15075](https://arxiv.org/abs/2105.15075) | [arxiv.org](http://arxiv.org/abs/2105.15075) | [github.com](https://github.com/blackfeather-wang/Dynamic-Vision-Transformer) | [B station](https://www.bilibili.com/video/BV1s54y1H7Wb)
- **[论文简析]SlowFast Networks for Video Recognition[1812.03982]** - [arXiv:1812.03982](https://arxiv.org/abs/1812.03982) | [arxiv.org](http://arxiv.org/abs/1812.03982) | [github.com](https://github.com/facebookresearch/SlowFast) | [B station](https://www.bilibili.com/video/BV1DV411J7gS)
- **[论文简析]MViT: Multiscale Vision Transformers[2104.11227]** - [arXiv:2104.11227](https://arxiv.org/abs/2104.11227) | [arxiv.org](http://arxiv.org/abs/2104.11227) | [github.com](https://github.com/facebookresearch/SlowFast) | [B station](https://www.bilibili.com/video/BV1np4y1b7QY)
- **[论文简析]BEVT: BERT Pretraining of Video Transformers[2112.01529]** - [arXiv:2112.01529](https://arxiv.org/abs/2112.01529) | [arxiv.org](http://arxiv.org/abs/2112.01529) | [B station](https://www.bilibili.com/video/BV1R44y1h7CR)
- **[论文简析]Unified Transformer for Efficient Spatiotemporal...[2201.04676]** - [arXiv:2201.04676](https://arxiv.org/abs/2201.04676) | [arxiv.org](http://arxiv.org/abs/2201.04676) | [github.com](https://github.com/Sense-X/UniFormer) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1CT4y1i7Fa)
- **[论文简析]MLP-Mixer: An all-MLP Architecture for Vision[2105.01601]** - [arXiv:2105.01601](https://arxiv.org/abs/2105.01601) | [arxiv.org](http://arxiv.org/abs/2105.01601) | [github.com](https://github.com/google-research/vision_transformer/tree/linen) | [B station](https://www.bilibili.com/video/BV1xK4y197qL)
- **[论文速览]EViT: Expediting Vision Transformers via Token Reorganizations[2202.07800]** - [arXiv:2202.07800](https://arxiv.org/abs/2202.07800) | [arxiv.org](http://arxiv.org/abs/2202.07800) | [github.com](https://github.com/youweiliang/evit) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1HS4y1F7nU)
- **[论文简析]Is Space-Time Attention All You Need for Video Understanding?[2102.05095]** - [arXiv:2102.05095](https://arxiv.org/abs/2102.05095) | [arxiv.org](http://arxiv.org/abs/2102.05095) | [github.com](https://github.com/facebookresearch/TimeSformer) | [B station](https://www.bilibili.com/video/BV1dA411371w)
- **[论文简析]A Laplacian Pyramid Translation Network[2105.09188]** - [arXiv:2105.09188](https://arxiv.org/abs/2105.09188) | [arxiv.org](http://arxiv.org/abs/2105.09188) | [github.com](https://github.com/csjliang/LPTN) | [B station](https://www.bilibili.com/video/BV1V64y1h7nv)
- **[论文简析]Per-Pixel Classification is Not All You Need for Semantic Seg[2107.06278]** - [arXiv:2107.06278](https://arxiv.org/abs/2107.06278) | [arxiv.org](http://arxiv.org/abs/2107.06278) | [bowenc0221.github.io](https://bowenc0221.github.io/maskformer/) | [B station](https://www.bilibili.com/video/BV17f4y1A7XR)
- **[论文速览]Masked-attention Mask Tr. for Universal Image Segmentation[2112.01527]** - [bowenc0221.github.io](https://bowenc0221.github.io/mask2former/) | [B station](https://www.bilibili.com/video/BV1ob4y1B7hp)
- **[论文简析]MobileNets: Efficient CNN for Mobile Vision Applications[1704.04861]** - [arXiv:1704.04861](https://arxiv.org/abs/1704.04861) | [arxiv.org](http://arxiv.org/abs/1704.04861) | [B station](https://www.bilibili.com/video/BV1LB4y1c7Ap)
- **[论文简析]MobileNet V2: Inverted Residuals and Linear Bottlenecks[1801.04381]** - [arXiv:1801.04381](https://arxiv.org/abs/1801.04381) | [arxiv.org](http://arxiv.org/abs/1801.04381) | [B station](https://www.bilibili.com/video/BV1Fq4y1n7Mq)
- **[论文简析]Searching for MobileNet V3[1905.02244]** - [arXiv:1905.02244](https://arxiv.org/abs/1905.02244) | [arxiv.org](http://arxiv.org/abs/1905.02244) | [B station](https://www.bilibili.com/video/BV1vN411f7pY)
- **[论文简析]MnasNet: Platform-Aware Neural Architecture Search for Mobile[1807.11626]** - [arXiv:1807.11626](https://arxiv.org/abs/1807.11626) | [arxiv.org](http://arxiv.org/abs/1807.11626) | [github.com](https://github.com/tensorflow/tpu/tree/master/models/official/mnasnet) | [B station](https://www.bilibili.com/video/BV1Wo4y127NM)
- **[论文简析]EfficientNet V1/V2[1905.11946/2104.00298]** - [arXiv:1905.11946](https://arxiv.org/abs/1905.11946) | [arxiv.org](http://arxiv.org/abs/1905.11946) | [B station](https://www.bilibili.com/video/BV1MV411E7Pq)
- **[论文简析]Mobile-Former: Bridging MobileNet and Transformer[2108.05895]** - [arXiv:2108.05895](https://arxiv.org/abs/2108.05895) | [arxiv.org](http://arxiv.org/abs/2108.05895) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1CL4y1g76U)
- **[论文简析]Point Transformer[2012.09164]** - [arXiv:2012.09164](https://arxiv.org/abs/2012.09164) | [arxiv.org](http://arxiv.org/abs/2012.09164) | [B station](https://www.bilibili.com/video/BV1PA41157su)
- **[论文简析]Point Transformer V2[2210.05666]** - [arXiv:2210.05666](https://arxiv.org/abs/2210.05666) | [arxiv.org](http://arxiv.org/abs/2210.05666) | [github.com](https://github.com/Gofinge/PointTransformerV2) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1de4y157hR)
- **[论文速览]RetNet: A Successor to Transformer for Large Language Models[2307.08621]** - [arXiv:2307.08621](https://arxiv.org/abs/2307.08621) | [arxiv.org](http://arxiv.org/abs/2307.08621) | [github.com](https://github.com/microsoft/torchscale) | [arxiv.org](http://arxiv.org/abs/2212.10554) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1134y1G7uQ)
- **[论文简析]Vision Transformers Need Registers[2309.16588]** - [arXiv:2309.16588](https://arxiv.org/abs/2309.16588) | [arxiv.org](http://arxiv.org/abs/2309.16588) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1up4y1c7JU)
- **[论文简析]Contrastive Learning for Unpaired Image-to-Image Translation[2007.15651]** - [arXiv:2007.15651](https://arxiv.org/abs/2007.15651) | [arxiv.org](http://arxiv.org/abs/2007.15651) | [github.com](https://github.com/taesungp/contrastive-unpaired-translation) | [B station](https://www.bilibili.com/video/BV14y4y1s7tS)
- **[论文简析]Multimodal Unsupervised Image-to-Image Translation[1804.04732]** - [arXiv:1804.04732](https://arxiv.org/abs/1804.04732) | [arxiv.org](http://arxiv.org/abs/1804.04732) | [github.com](https://github.com/nvlabs/MUNIT) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1Pb4y1p78y)
- **[论文速览]Rethinking the Truly Unsupervised Image-to-Image Translation[2006.06500]** - [arXiv:2006.06500](https://arxiv.org/abs/2006.06500) | [arxiv.org](http://arxiv.org/abs/2006.06500) | [github.com](https://github.com/clovaai/tunit) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1qZ4y1z77v)
- **[论文简析]Unsupervised Image-to-Image Translation Networks[1703.00848]** - [arXiv:1703.00848](https://arxiv.org/abs/1703.00848) | [arxiv.org](http://arxiv.org/abs/1703.00848) | [github.com](https://github.com/mingyuliutw/unit) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1c34y187BW)
- **[论文简析]RetinaGAN: An Object-aware Approach to Sim-to-Real Transfer[2011.03148]** - [arXiv:2011.03148](https://arxiv.org/abs/2011.03148) | [arxiv.org](http://arxiv.org/abs/2011.03148) | [arxiv.org](http://arxiv.org/abs/1708.02002) | [B station](https://www.bilibili.com/video/BV17o4y1X7Mk)
- **[论文简析]MoCoGAN-HD: A Good Image Generator Is What You Need...[2104.15069]** - [arXiv:2104.15069](https://arxiv.org/abs/2104.15069) | [arxiv.org](http://arxiv.org/abs/2104.15069) | [github.com](https://github.com/snap-research/MoCoGAN-HD) | [B station](https://www.bilibili.com/video/BV1gv411L7Dy)
- **[论文简析]VQ-VAE:Neural discrete representation learning[1711.00937]** - [arXiv:1711.00937](https://arxiv.org/abs/1711.00937) | [arxiv.org](http://arxiv.org/abs/1711.00937) | [B station](https://www.bilibili.com/video/BV1bb4y1i7j6)
- **[论文速览]Autoregressive Image Generation using Residual Quantization[2203.01941]** - [arXiv:2203.01941](https://arxiv.org/abs/2203.01941) | [arxiv.org](http://arxiv.org/abs/2203.01941) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1gY411E7ge)
- **[论文速览]Personalizing Text2Img Generation using Textual Inversion[2208.01618]** - [arXiv:2208.01618](https://arxiv.org/abs/2208.01618) | [arxiv.org](https://arxiv.org/abs/2208.01618) | [textual-inversion.github.io](https://textual-inversion.github.io/) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1oH4y1k7RW)
- **[论文速览]Taming Transformers for High-Resolution Image Synthesis[2012.09841]** - [arXiv:2012.09841](https://arxiv.org/abs/2012.09841) | [arxiv.org](http://arxiv.org/abs/2012.09841) | [git.io](https://git.io/JnyvK) | [arxiv.org](https://arxiv.org/abs/2102.12092) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1ym4y1d7iP)
- **[论文简析]MaskGIT: Masked Generative Image Transformer[2202.04200]** - [arXiv:2202.04200](https://arxiv.org/abs/2202.04200) | [arxiv.org](http://arxiv.org/abs/2202.04200) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1qS4y1r7p1)
- **[论文简析]Regularized Vector Quantization for Tokenized Image Synthesis[2303.06424]** - [arXiv:2303.06424](https://arxiv.org/abs/2303.06424) | [arxiv.org](http://arxiv.org/abs/2303.06424) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1rG411o7pp)
- **[论文速览]Denoising Diffusion Probabilistic Models / DDPM[2006.11239]** - [arXiv:2006.11239](https://arxiv.org/abs/2006.11239) | [arxiv.org](http://arxiv.org/abs/2006.11239) | [github.com](https://github.com/hojonathanho/diffusion) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1yA41167Dg)
- **[论文速览]Denoising Diffusion Implicit Models / DDIM[2010.02502]** - [arXiv:2010.02502](https://arxiv.org/abs/2010.02502) | [arxiv.org](http://arxiv.org/abs/2010.02502) | [github.com](https://github.com/ermongroup/ddim) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1ic41157Vf)
- **[论文速览]Structured Denoising Diffusion Models in Discrete State-Spaces[2107.03006]** - [arXiv:2107.03006](https://arxiv.org/abs/2107.03006) | [arxiv.org](http://arxiv.org/abs/2107.03006) | [github.com](https://github.com/google-research/google-research/tree/master/d3pm) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1R84y1H7k1)
- **[论文速览]Drag Your GAN: Interactive Point-based Manipulation...[2305.10973]** - [arXiv:2305.10973](https://arxiv.org/abs/2305.10973) | [arxiv.org](http://arxiv.org/abs/2305.10973) | [vcai.mpi-inf.mpg.de](https://vcai.mpi-inf.mpg.de/projects/DragGAN/) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1Ju41177k3)
- **[论文简析]DreamBooth: Fine Tuning Text-to-Image Diffusion Models...[2208.12242]** - [arXiv:2208.12242](https://arxiv.org/abs/2208.12242) | [arxiv.org](http://arxiv.org/abs/2208.12242) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV18m4y1H7fs)
- **[论文速览]FreeU: Free Lunch in Diffusion U-Net[2309.11497]** - [arXiv:2309.11497](https://arxiv.org/abs/2309.11497) | [arxiv.org](http://arxiv.org/abs/2309.11497) | [chenyangsi.top](https://chenyangsi.top/FreeU/) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1dk4y1F7dg)
- **[论文简析]Visual Autoregressive Modeling: ...via Next-Scale Prediction[2404.02905]** - [arXiv:2404.02905](https://arxiv.org/abs/2404.02905) | [arxiv.org](https://arxiv.org/abs/2404.02905) | [github.com](https://github.com/FoundationVision/VAR) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1pq421P7D4)
- **[论文速览]MixUp: Beyond Empirical Risk Minimization[1710.09412]** - [arXiv:1710.09412](https://arxiv.org/abs/1710.09412) | [arxiv.org](http://arxiv.org/abs/1710.09412) | [github.com](https://github.com/facebookresearch/mixup-cifar10) | [B station](https://www.bilibili.com/video/BV12q4y167SV)
- **[论文速览]RegMixup: Mixup as a Regularizer Can Surprisingly Improve...[2206.14502]** - [arXiv:2206.14502](https://arxiv.org/abs/2206.14502) | [arxiv.org](https://arxiv.org/abs/2206.14502) | [github.com](https://github.com/FrancescoPinto/RegMixup) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1jB4y1i7iw)
- **[论文夕拾]Mixed Sample Data Augmentations, Part 1** - [arXiv:2106.07085](https://arxiv.org/abs/2106.07085) | [arxiv.org](https://arxiv.org/abs/2106.07085) | [arxiv.org](https://arxiv.org/abs/2001.04086) | [openaccess.thecvf.com](https://openaccess.thecvf.com/content_CVPRW_2020/papers/w45/Lee_SmoothMix_A_Simple_Yet_Effective_Data_Augmentation_to_Train_Robust_CVPRW_2020_paper.pdf) | [arxiv.org](https://arxiv.org/abs/2002.12047) | [B station](https://www.bilibili.com/video/BV1rr4y1V7Dx)
- **[论文夕拾]Mixed Sample Data Augmentations, Part 2** - [arXiv:2106.07085](https://arxiv.org/abs/2106.07085) | [arxiv.org](https://arxiv.org/abs/2106.07085) | [arxiv.org](http://arxiv.org/abs/2205.15955) | [github.com](https://github.com/JunlinHan/CropMix) | [arxiv.org](https://arxiv.org/abs/2011.11778) | [B station](https://www.bilibili.com/video/BV1qt4y1h7kM)
- **[论文简析]Robust and Generalizable Visual ... via Random Convolutions[2007.13003]** - [arXiv:2007.13003](https://arxiv.org/abs/2007.13003) | [arxiv.org](http://arxiv.org/abs/2007.13003) | [github.com](https://github.com/wildphoton/RandConv) | [B station](https://www.bilibili.com/video/BV1Kq4y1E7j3)
- **[论文速览]Simple Copy-Paste is a Strong Data Aug. for Instance Seg.[2012.07177]** - [arXiv:2012.07177](https://arxiv.org/abs/2012.07177) | [arxiv.org](http://arxiv.org/abs/2012.07177) | [B station](https://www.bilibili.com/video/BV1Hq4y1s7wB)
- **[论文速览]Visual Prompt Tuning / VPT[2203.12119]** - [arXiv:2203.12119](https://arxiv.org/abs/2203.12119) | [arxiv.org](http://arxiv.org/abs/2203.12119) | [github.com](https://github.com/kmnp/vpt) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV18h4y127GG)
- **[论文简析]Red Circle: Visual Prompt Engineering for VLMs[2304.06712]** - [arXiv:2304.06712](https://arxiv.org/abs/2304.06712) | [arxiv.org](http://arxiv.org/abs/2304.06712) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1wk4y1V7wo)
- **[论文简析]Finding an Unsupervised Image Segmenter in .. Generative Model[2105.08127]** - [arXiv:2105.08127](https://arxiv.org/abs/2105.08127) | [arxiv.org](http://arxiv.org/abs/2105.08127) | [B station](https://www.bilibili.com/video/BV1Dy4y1W7uM)
- **[论文简析]PolyFormer: Referring Image Seg. as Sequential Polygon Gen [2302.07387]** - [arXiv:2302.07387](https://arxiv.org/abs/2302.07387) | [arxiv.org](http://arxiv.org/abs/2302.07387) | [polyformer.github.io](https://polyformer.github.io/) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1wr4y1o7V5)
- **[论文简析]DiffSeg: Unsupervised Zero-Shot Seg. using Stable Diffusion[2308.12469]** - [arXiv:2308.12469](https://arxiv.org/abs/2308.12469) | [arxiv.org](http://arxiv.org/abs/2308.12469) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1Sm4y1T74R)
- **[论文简析]Patching Open-Vocabulary Models by Interpolating Weights[2208.05592]** - [arXiv:2208.05592](https://arxiv.org/abs/2208.05592) | [arxiv.org](http://arxiv.org/abs/2208.05592) | [github.com](https://github.com/mlfoundations/patching) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1tV411P73W)
- **[论文速览]Scalable Video Object Segmentation with Simplified Framework[2308.09903]** - [arXiv:2308.09903](https://arxiv.org/abs/2308.09903) | [arxiv.org](http://arxiv.org/abs/2308.09903) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV1Vu411g7Gm)
- **[论文速览]Learning to Learn with Generative Models of NN Checkpoints[2209.12892]** - [arXiv:2209.12892](https://arxiv.org/abs/2209.12892) | [arxiv.org](http://arxiv.org/abs/2209.12892) | [wpeebles.com](https://www.wpeebles.com/Gpt.html) | [docs.qq.com](https://docs.qq.com/sheet/DSUdOTG9xWUdydVB6) | [B station](https://www.bilibili.com/video/BV13H4y1j7Zd)
- **给女朋友做的AR元宇宙增强现实生日贺卡** - [sketchfab.com](https://sketchfab.com/3d-models/princess-peach-8122299e7adb434c8c7990be3f427561) | [sketchfab.com](https://sketchfab.com/3d-models/gaming-guy-room-f6943c83d7af4bd598d1859b326578cf) | [sketchfab.com](https://sketchfab.com/3d-models/legend-of-zelda-botw-heart-container-4cbca52ae7fc4654ae2d71438b7eb3f6) | [sketchfab.com](https://sketchfab.com/3d-models/majoras-mask-789e5fdafe554bb0814f26005e659161) | [B station](https://www.bilibili.com/video/BV17Y4y1z73F)
- **MATLAB竟然还能做增强现实AR元宇宙？** - [github.com](https://github.com/TommyZihao/MATLAB_AR_Tutorials) | [B station](https://www.bilibili.com/video/BV1wG41137oJ)
- **构建自己的图像分类数据集【两天搞定AI毕设】** - [github.com](https://github.com/TommyZihao/Train_Custom_Dataset) | [featurize.cn](https://featurize.cn/?s=d7ce99f842414bfcaea5662a97581bd1) | [B station](https://www.bilibili.com/video/BV1Jd4y1T7rw)
- **Pytorch预训练图像分类模型识别预测【两天搞定AI毕设】** - [github.com](https://github.com/TommyZihao/Train_Custom_Dataset) | [featurize.cn](https://featurize.cn/?s=d7ce99f842414bfcaea5662a97581bd1) | [github.com](https://github.com/open-mmlab/mmclassification) | [B station](https://www.bilibili.com/video/BV1qe4y1D7zD)
- **Pytorch迁移学习训练自己的图像分类模型【两天搞定AI毕设】** - [github.com](https://github.com/TommyZihao/Train_Custom_Dataset) | [featurize.cn](https://featurize.cn/?s=d7ce99f842414bfcaea5662a97581bd1) | [B station](https://www.bilibili.com/video/BV1Ng411C7WY)
- **用训练得到的pytorch图像分类模型，识别图像、视频、摄像头画面【两天搞定AI毕设】** - [github.com](https://github.com/TommyZihao/Train_Custom_Dataset) | [featurize.cn](https://featurize.cn/?s=d7ce99f842414bfcaea5662a97581bd1) | [B station](https://www.bilibili.com/video/BV12d4y1P7xz)
- **测试集上评估Pytorch训练得到的图像分类模型【两天搞定AI毕业设计】** - [github.com](https://github.com/TommyZihao/Train_Custom_Dataset) | [featurize.cn](https://featurize.cn/?s=d7ce99f842414bfcaea5662a97581bd1) | [B station](https://www.bilibili.com/video/BV1bP411j7NK)
- **图像分类测试集语义特征降维可视化** - [github.com](https://github.com/TommyZihao/Train_Custom_Dataset) | [featurize.cn](https://featurize.cn/?s=d7ce99f842414bfcaea5662a97581bd1) | [B station](https://www.bilibili.com/video/BV1VB4y1z7xN)
- **图像分类可解释性分析实战-CAM热力图系列算法** - [github.com](https://github.com/TommyZihao/Train_Custom_Dataset) | [B station](https://www.bilibili.com/video/BV1JG4y1s74x)
- **图像分类可解释性分析实战-Deep Feature Factorization** - [jacobgil.github.io](https://jacobgil.github.io/pytorch-gradcam-book/Deep%20Feature%20Factorizations.html) | [github.com](https://github.com/TommyZihao/Train_Custom_Dataset) | [B station](https://www.bilibili.com/video/BV1Re4y1n73v)
- **图像分类可解释性分析实战-Captum工具包** - [github.com](https://github.com/TommyZihao/Train_Custom_Dataset) | [B station](https://www.bilibili.com/video/BV1DN4y1N7fc)
- **图像分类可解释性分析实战-shap工具包** - [github.com](https://github.com/TommyZihao/Train_Custom_Dataset) | [B station](https://www.bilibili.com/video/BV1vP4y1S7Xu)
- **图像分类可解释性分析实战-lime工具包** - [github.com](https://github.com/TommyZihao/zihao_course/blob/main/XAI) | [github.com](https://github.com/TommyZihao/Train_Custom_Dataset) | [B station](https://www.bilibili.com/video/BV1a84y1i7Tz)
- **图像分类模型部署-Pytorch转ONNX** - [github.com](https://github.com/TommyZihao/Train_Custom_Dataset) | [B station](https://www.bilibili.com/video/BV1cM4y187Xc)
- **Pytorch图像分类模型部署-ONNX Runtime本地终端推理** - [github.com](https://github.com/TommyZihao/Train_Custom_Dataset) | [B station](https://www.bilibili.com/video/BV1AM4y187yR)
- **Pytorch图像分类部署-ONNX Runtime安卓手机APP** - [github.com](https://github.com/TommyZihao/Train_Custom_Dataset) | [github.com](https://github.com/microsoft/onnxruntime-inference-examples) | [developer.android.com](https://developer.android.com/studio) | [B station](https://www.bilibili.com/video/BV1cs4y1Q7nu)
- **Pytorch图像分类部署-ONNX Runtime浏览器Web前端** - [github.com](https://github.com/TommyZihao/Train_Custom_Dataset) | [onnx.coderai.cn](https://onnx.coderai.cn) | [microsoft.github.io](https://microsoft.github.io/onnxruntime-web-demo) | [github.com](https://github.com/microsoft/onnxruntime-web-demo) | [B station](https://www.bilibili.com/video/BV1Ja4y137fZ)
- **AidLux图像分类部署-安卓鸿蒙高通ARM** - [aimo.aidlux.com](http://aimo.aidlux.com) | [github.com](https://github.com/TommyZihao/aidlux_tutorial) | [github.com](https://github.com/TommyZihao/Train_Custom_Dataset) | [B station](https://www.bilibili.com/video/BV1oN411h7p1)
- **文本识别OCR神器 MMOCR【OpenMMLab】** - [github.com](https://github.com/open-mmlab/mmocr) | [openmmlab.com](https://openmmlab.com/) | [B station](https://www.bilibili.com/video/BV1Ua411x7dB)
- **MMOCR代码实战（上）安装配置、预训练OCR模型预测** - [github.com](https://github.com/open-mmlab/mmocr) | [openmmlab.com](https://openmmlab.com/) | [B station](https://www.bilibili.com/video/BV1hP4y1M7Zc)
- **MMOCR代码实战（中）AI给文字区域打马赛克** - [github.com](https://github.com/open-mmlab/mmocr) | [openmmlab.com](https://openmmlab.com/) | [B station](https://www.bilibili.com/video/BV1nZ4y1z77X)
- **MMOCR代码实战（下）Kaggle验证码文本识别** - [github.com](https://github.com/open-mmlab/mmocr) | [openmmlab.com](https://openmmlab.com/) | [B station](https://www.bilibili.com/video/BV1tL411A7bj)
- **Github高赞开源项目速览-AIGC与大语言模型-20230707** - [github.com](https://github.com/TommyZihao/Awesome) | [B station](https://www.bilibili.com/video/BV1eW4y1f72L)
- **Github高赞开源项目速览-AIGC的N种玩法-20230808** - [github.com](https://github.com/TommyZihao/Awesome) | [B station](https://www.bilibili.com/video/BV1cV411V7LU)
- **中医+人工智能黑科技：耳朵穴位经络图像识别** - [github.com](https://github.com/TommyZihao/PointWise_Body) | [B station](https://www.bilibili.com/video/BV168411Z7Lt)
- **标注关键点检测数据集** - [B station](https://www.bilibili.com/video/BV19g4y1777q)
- **关键点检测数据集-Labelme格式转YOLO格式** - [B station](https://www.bilibili.com/video/BV1QX4y1B7eF)
- **关键点检测数据集-Labelme格式转MS COCO格式** - [B station](https://www.bilibili.com/video/BV1vc411J7GC)
- **YOLOV8关键点检测-预训练模型预测** - [github.com](https://github.com/TommyZihao/Train_Custom_Dataset) | [B station](https://www.bilibili.com/video/BV1yg4y177ef)
- **YOLOV8关键点检测-训练自己的关键点检测模型** - [github.com](https://github.com/TommyZihao/Train_Custom_Dataset) | [B station](https://www.bilibili.com/video/BV13a4y157HE)
- **YOLOV8关键点检测-用训练得到的模型预测图像、视频、摄像头画面** - [github.com](https://github.com/TommyZihao/Train_Custom_Dataset) | [B station](https://www.bilibili.com/video/BV1Lo4y1t76s)
- **YOLOV8关键点检测-预测源码解读** - [github.com](https://github.com/TommyZihao/Train_Custom_Dataset) | [B station](https://www.bilibili.com/video/BV1Yu411t7XF)
- **YOLOV8关键点检测-ONNX Runtime部署** - [github.com](https://github.com/TommyZihao/Train_Custom_Dataset) | [B station](https://www.bilibili.com/video/BV18L411B7Mv)
- **玩转MMPose人体姿态估计关键点检测** - [github.com](https://github.com/open-mmlab/mmpose) | [openmmlab.com](https://openmmlab.com) | [B station](https://www.bilibili.com/video/BV16B4y1h7JS)
- **开源姿态估计算法库MMPose** - [github.com](https://github.com/open-mmlab/mmpose) | [openmmlab.com](https://openmmlab.com) | [B station](https://www.bilibili.com/video/BV15B4y1p7Kj)
- **RTMPose关键点检测-安装MMDetection和MMPose** - [B station](https://www.bilibili.com/video/BV1Pa4y1g7N7)
- **RTMPose关键点检测-MMDetection三角板目标检测** - [B station](https://www.bilibili.com/video/BV1Lm4y1879K)
- **RTMPose关键点检测-训练、评估、推理预测** - [B station](https://www.bilibili.com/video/BV12a4y1u7sd)
- **AI画《三体》名场面** - [github.com](https://github.com/TommyZihao/zihao_AIGC) | [midjourney.com](https://www.midjourney.com) | [yige.baidu.com](https://yige.baidu.com) | [wenxin.baidu.com](https://wenxin.baidu.com/moduleApi/ernieVilg) | [B station](https://www.bilibili.com/video/BV1b14y1W7iq)
- **AI画我的三体之章北海传** - [github.com](https://github.com/TommyZihao/zihao_AIGC) | [B station](https://www.bilibili.com/video/BV1Ux4y1F7zA)
- **如果AI来画清华美院艺考题** - [decoder.modelscope.cn](https://decoder.modelscope.cn) | [modelscope.cn](https://www.modelscope.cn) | [B station](https://www.bilibili.com/video/BV1d24y1f7Gi)
- **三分钟部署AIGC神器DragGAN** - [growthdata.virtaicloud.com](https://growthdata.virtaicloud.com/t/ea) | [B station](https://www.bilibili.com/video/BV1Xw411e7ev)
- **斥资500元，我用AI打造的三体科幻微电影《云天明的童话》** - [B station](https://www.bilibili.com/video/BV1Xu4y1b7ny)
- **石趣绘本园：基于Amazon Bedrock的AIGC交互式童话绘本** - [aws.amazon.com](https://aws.amazon.com/cn/bedrock/?trk=920b209d-e1e2-4570-b186-008ab8db379e&sc_channel=psm) | [github.com](https://github.com/TommyZihao/StoryBook_Bedrock) | [B station](https://www.bilibili.com/video/BV1n64y1N7Vz)
- **【拜年神器】一键部署阿里开源AI写真** - [arXiv:2308.14256](https://arxiv.org/abs/2308.14256) | [github.com](https://github.com/modelscope/facechain) | [arxiv.org](https://arxiv.org/abs/2308.14256) | [modelscope.cn](https://modelscope.cn/studios/CVstudio/cv_human_portrait) | [tongyi.aliyun.com](https://tongyi.aliyun.com/wanxiang) | [B station](https://www.bilibili.com/video/BV1DZ421B7J9)
- **【精读AI论文】知识蒸馏** - [readpaper.com](https://readpaper.com/paper/1821462560) | [openmmlab.com](https://openmmlab.com/) | [github.com](https://github.com/open-mmlab/MMRazor) | [github.com](https://github.com/open-mmlab/MMDeploy) | [B station](https://www.bilibili.com/video/BV1gS4y1k7vj)
- **知识蒸馏开山之作论文精读：Distilling the knowledge in a neural network** - [readpaper.com](https://readpaper.com/paper/1821462560) | [B station](https://www.bilibili.com/video/BV1N44y1n7mU)
- **知识蒸馏Pytorch代码实战** - [B station](https://www.bilibili.com/video/BV1zP4y1F7g4)
- **python交互式地图数据可视化神器folium** - [github.com](https://github.com/TommyZihao/folium_tutorials) | [B station](https://www.bilibili.com/video/BV1t3411A7Z8)
- **folium实战-拍照地点分布地图可视化** - [github.com](https://github.com/TommyZihao/folium_tutorials) | [B station](https://www.bilibili.com/video/BV1m3411A786)
- **folium实战-全球地震与板块运动分布** - [github.com](https://github.com/TommyZihao/folium_tutorials) | [B station](https://www.bilibili.com/video/BV1gZ4y18772)
- **folium实战-波士顿犯罪地点、新冠疫情小区、纽约全天公交车可视化** - [github.com](https://github.com/TommyZihao/folium_tutorials) | [B station](https://www.bilibili.com/video/BV18T4y1B7PA)
- **folium实战-轨道交通数据可视化** - [github.com](https://github.com/TommyZihao/folium_tutorials) | [B station](https://www.bilibili.com/video/BV113411N7TL)
- **玩转MMTracking视频感知与追踪算法库** - [github.com](https://github.com/open-mmlab/mmtracking) | [B station](https://www.bilibili.com/video/BV1za411Y7Zm)
- **MMTracking单目标追踪+轨迹绘制代码实战** - [github.com](https://github.com/open-mmlab/mmtracking) | [B station](https://www.bilibili.com/video/BV1s44y1g75J)
- **AI人流量计数+足迹追踪** - [github.com](https://github.com/open-mmlab/mmtracking) | [B station](https://www.bilibili.com/video/BV1J3411M7KQ)
- **训练Deepsort多目标追踪算法** - [github.com](https://github.com/open-mmlab/mmtracking) | [B station](https://www.bilibili.com/video/BV1e5411m7Qh)
- **【开箱遛遛】宇树机器狗Go2** - [B station](https://www.bilibili.com/video/BV1hG411Y74j)
- **斯坦福CS224W图机器学习、图神经网络、知识图谱【同济子豪兄】** - [web.stanford.edu](https://web.stanford.edu/class/cs224w) | [github.com](https://github.com/TommyZihao/zihao_course/tree/main/CS224W) | [B station](https://www.bilibili.com/video/BV1pR4y1S7GA)
- **图的基本表示【斯坦福CS224W图机器学习】** - [github.com](https://github.com/TommyZihao/zihao_course/tree/main/CS224W) | [web.stanford.edu](https://web.stanford.edu/class/cs224w) | [B station](https://www.bilibili.com/video/BV1n84y1e7SF)
- **传统图机器学习的特征工程-节点【斯坦福CS224W】** - [github.com](https://github.com/TommyZihao/zihao_course/tree/main/CS224W) | [web.stanford.edu](https://web.stanford.edu/class/cs224w) | [B station](https://www.bilibili.com/video/BV1HK411175s)
- **传统图机器学习的特征工程-连接【斯坦福CS224W】** - [github.com](https://github.com/TommyZihao/zihao_course/tree/main/CS224W) | [web.stanford.edu](https://web.stanford.edu/class/cs224w) | [B station](https://www.bilibili.com/video/BV1r3411m7sD)
- **传统图机器学习的特征工程-全图【斯坦福CS224W】** - [github.com](https://github.com/TommyZihao/zihao_course/tree/main/CS224W) | [web.stanford.edu](https://web.stanford.edu/class/cs224w) | [B station](https://www.bilibili.com/video/BV14W4y1V7gg)
- **图机器学习NetworkX代码实战-创建图和可视化** - [github.com](https://github.com/TommyZihao/zihao_course/tree/main/CS224W) | [featurize.cn](https://featurize.cn?s=d7ce99f842414bfcaea5662a97581bd1) | [B station](https://www.bilibili.com/video/BV1kM41147zV)
- **图机器学习NetworkX代码实战-上海地铁站点图数据挖掘** - [github.com](https://github.com/TommyZihao/zihao_course/tree/main/CS224W) | [featurize.cn](https://featurize.cn?s=d7ce99f842414bfcaea5662a97581bd1) | [B station](https://www.bilibili.com/video/BV1LY411R7HJ)
- **随机游走的艺术-图嵌入表示学习【斯坦福CS224W图机器学习】** - [github.com](https://github.com/TommyZihao/zihao_course/tree/main/CS224W) | [B station](https://www.bilibili.com/video/BV1AP4y1r7Pz)
- **DeepWalk【图神经网络论文精读】** - [B station](https://www.bilibili.com/video/BV1o94y197vf)
- **DeepWalk论文逐句精读** - [B station](https://www.bilibili.com/video/BV1pW4y1z7pb)
- **DeepWalk代码实战-维基百科词条图嵌入可视化** - [B station](https://www.bilibili.com/video/BV1et4y187Gd)
- **Node2Vec【图神经网络论文精读】** - [B station](https://www.bilibili.com/video/BV1BS4y1E7tf)
- **Node2Vec论文逐句精读** - [B station](https://www.bilibili.com/video/BV1vU4y1i77T)
- **Node2Vec代码实战-《悲惨世界》小说人物图嵌入、Alias Sampling复现** - [B station](https://www.bilibili.com/video/BV1VS4y1E7Me)
- **改变世界的谷歌PageRank算法** - [B station](https://www.bilibili.com/video/BV1uP411K7yN)
- **PageRank代码实战-西游记人物重要度** - [B station](https://www.bilibili.com/video/BV1Wg411H7Ep)
- **半监督节点分类：标签传播和消息传递【斯坦福CS224W图机器学习】** - [github.com](https://github.com/TommyZihao/zihao_course/tree/main/CS224W) | [B station](https://www.bilibili.com/video/BV1184y1G7pA)
- **深度学习基础【斯坦福CS224W图神经网络】** - [github.com](https://github.com/TommyZihao/zihao_course/tree/main/CS224W) | [B station](https://www.bilibili.com/video/BV13g4y1n7b4)
- **图神经网络综述和学习路径【斯坦福CS224W图机器学习】** - [github.com](https://github.com/TommyZihao/zihao_course/tree/main/CS224W) | [B station](https://www.bilibili.com/video/BV16v4y1b7x7)
- **图卷积神经网络GCN** - [github.com](https://github.com/TommyZihao/zihao_course/tree/main/CS224W) | [B station](https://www.bilibili.com/video/BV1Hs4y157Ls)
- **图神经网络GNN的表达能力** - [github.com](https://github.com/TommyZihao/zihao_course/tree/main/CS224W) | [B station](https://www.bilibili.com/video/BV1MT411Y7da)
- **玩转Neo4j知识图谱和图数据挖掘** - [B station](https://www.bilibili.com/video/BV1Mr4y1i7CX)
- **Neo4j医疗知识图谱智能问答机器人** - [liuhuanyong.github.io](https://liuhuanyong.github.io) | [github.com](https://github.com/TommyZihao/QASystemOnMedicalKG/tree/master/notebook_tutorials) | [B station](https://www.bilibili.com/video/BV1uY41167Ha)
- **【精读AI论文】旷视轻量化网络ShuffleNet V2-算法精讲** - [B station](https://www.bilibili.com/video/BV1d3411Y7Ms)
- **【精读AI论文】旷视轻量化网络ShuffleNet V2-论文精读** - [B station](https://www.bilibili.com/video/BV17u411U7Ag)
- **生成对抗网络GAN交互式可视化** - [poloclub.github.io](https://poloclub.github.io/ganlab/) | [github.com](https://github.com/open-mmlab/mmgeneration) | [B station](https://www.bilibili.com/video/BV1R44y1377T)
- **生成对抗网络GAN开山之作论文精读** - [github.com](https://github.com/open-mmlab/mmgeneration) | [B station](https://www.bilibili.com/video/BV1oi4y1m7np)
- **精读CycleGAN论文-拍案叫绝的非配对图像风格迁移** - [junyanz.github.io](https://junyanz.github.io/CycleGAN) | [arxiv.org](https://arxiv.org/pdf/1703.10593.pdf) | [github.com](https://github.com/open-mmlab/mmgeneration) | [B station](https://www.bilibili.com/video/BV1Ya411a78P)
- **CycleGAN照片转梵高莫奈油画** - [github.com](https://github.com/open-mmlab/mmgeneration) | [B station](https://www.bilibili.com/video/BV1wv4y1T71F)
- **MMGeneration开源图像生成算法库【OpenMMLab】** - [github.com](https://github.com/open-mmlab/mmgeneration（) | [openmmlab.com](https://openmmlab.com/) | [B station](https://www.bilibili.com/video/BV1bY4y147kz)
- **【精读AI论文】pix2pix-简笔画猫转真猫** - [phillipi.github.io](https://phillipi.github.io/pix2pix/) | [affinelayer.com](https://affinelayer.com/pixsrv/) | [B station](https://www.bilibili.com/video/BV1wY4y1k7Tc)
- **人像自拍秒变爆款动漫画风【OpenMMLab】** - [app.openmmlab.com](https://app.openmmlab.com/facestylor/) | [colab.research.google.com](https://colab.research.google.com/drive/1hovHLKr0Vfa332LN-bBPAwyBe5WIc583?usp=sharing) | [B station](https://www.bilibili.com/video/BV1XL4y1g7in)
- **两天搞定语义分割毕业设计** - [github.com](https://github.com/TommyZihao/MMSegmentation_Tutorials) | [B station](https://www.bilibili.com/video/BV1Wr4y1d7Tr)
- **语义分割与MMSegmentation** - [github.com](https://github.com/TommyZihao/MMSegmentation_Tutorials) | [B station](https://www.bilibili.com/video/BV1qN411z7hz)
- **标注自己的语义分割数据集** - [github.com](https://github.com/TommyZihao/MMSegmentation_Tutorials) | [github.com](https://github.com/wkentaro/labelme) | [github.com](https://github.com/TommyZihao/Label2Everything/tree/main/labelme2mask) | [github.com](https://github.com/TommyZihao/Train_Custom_Dataset/tree/main/%E8%AF%AD%E4%B9%89%E5%88%86%E5%89%B2) | [B station](https://www.bilibili.com/video/BV1uu4y1Q7Rt)
- **安装配置MMSegmentation+预训练语义分割推理预测** - [github.com](https://github.com/TommyZihao/MMSegmentation_Tutorials) | [B station](https://www.bilibili.com/video/BV1du4y1q7o5)
- **准备西瓜语义分割数据集** - [github.com](https://github.com/TommyZihao/MMSegmentation_Tutorials) | [B station](https://www.bilibili.com/video/BV1C8411X7p9)
- **准备MMSeg语义分割config配置文件** - [github.com](https://github.com/TommyZihao/MMSegmentation_Tutorials) | [B station](https://www.bilibili.com/video/BV1w44y1F73N)
- **MMSegmentation训练语义分割深度学习算法** - [github.com](https://github.com/TommyZihao/MMSegmentation_Tutorials) | [B station](https://www.bilibili.com/video/BV1Ch4y1S7cX)
- **MMSeg语义分割推理预测** - [github.com](https://github.com/TommyZihao/MMSegmentation_Tutorials) | [B station](https://www.bilibili.com/video/BV1vp4y1K7Tj)
- **语义分割部署-MMDeploy模型转换** - [github.com](https://github.com/TommyZihao/MMSegmentation_Tutorials) | [B station](https://www.bilibili.com/video/BV1Ep4y1n7wo)
- **语义分割部署-ONNX Runtime实时推理** - [github.com](https://github.com/TommyZihao/MMSegmentation_Tutorials) | [B station](https://www.bilibili.com/video/BV1aN411B7Dq)
- **AidLux语义分割部署-安卓鸿蒙高通ARM** - [aimo.aidlux.com](http://aimo.aidlux.com) | [github.com](https://github.com/TommyZihao/aidlux_tutorial) | [github.com](https://github.com/TommyZihao/MMSegmentation_Tutorials) | [B station](https://www.bilibili.com/video/BV1k8411y7c2)
- **可解释机器学习公开课** - [github.com](https://github.com/TommyZihao/zihao_course/blob/main/XAI) | [mp.weixin.qq.com](https://mp.weixin.qq.com/s/jxKVMpcqcunNSXxiyCtx0Q) | [B station](https://www.bilibili.com/video/BV1Se4y1T7dG)
- **CAM可解释性分析-算法讲解** - [readpaper.com](https://readpaper.com/user/collect/638623946528292864) | [B station](https://www.bilibili.com/video/BV1Ke411g7gm)
- **CAM可解释性论文精读：Learning Deep Features for Discriminative Localization** - [readpaper.com](https://readpaper.com/user/collect/638623946528292864) | [B station](https://www.bilibili.com/video/BV1fe4y1C7mN)
- **GradCAM深度学习可解释性分析** - [github.com](https://github.com/TommyZihao/Train_Custom_Dataset) | [B station](https://www.bilibili.com/video/BV1PD4y1B77q)
- **【精读AI论文】GradCAM可解释性分析** - [github.com](https://github.com/TommyZihao/Train_Custom_Dataset) | [B station](https://www.bilibili.com/video/BV1id4y167FF)
- **LIME机器学习可解释性分析** - [github.com](https://github.com/TommyZihao/zihao_course/blob/main/XAI) | [github.com](https://github.com/TommyZihao/Train_Custom_Dataset) | [B station](https://www.bilibili.com/video/BV12V4y1G7KF)
- **【精读AI论文】LIME机器学习可解释性分析** - [github.com](https://github.com/TommyZihao/zihao_course/blob/main/XAI) | [github.com](https://github.com/TommyZihao/Train_Custom_Dataset) | [B station](https://www.bilibili.com/video/BV1wV4y1V7rD)
- **MATLAB玩转深度学习可解释性分析** - [github.com](https://github.com/TommyZihao/MATLAB_CAM_Tutorials) | [github.com](https://github.com/TommyZihao/zihao_course/blob/main/XAI) | [B station](https://www.bilibili.com/video/BV1Qd4y1b7Mr)
- **11款神经网络科研绘图可视化工具** - [github.com](https://github.com/TommyZihao/zihao_course/blob/main/XAI) | [B station](https://www.bilibili.com/video/BV1TV4y1P7AP)
- **论文分享ICML 2026：RAG场景下的不确定性量化研究** - [B station](https://www.bilibili.com/video/BV1NPNY67EH4)
- **论文分享OMAC：多智能体协作的整体优化框架** - [arXiv:2505.11765](https://arxiv.org/abs/2505.11765) | [arxiv.org](https://arxiv.org/abs/2505.11765) | [github.com](https://github.com/xiwenchao/OMAC) | [B station](https://www.bilibili.com/video/BV1JUK26mEcb)
- **论文分享HetRL：异构环境下的大模型强化学习调度框架** - [arXiv:2607.12345](https://arxiv.org/abs/2607.12345) | [arxiv.org](https://arxiv.org/abs/2607.12345) | [github.com](https://github.com/hetrl-project/HetRL) | [B station](https://www.bilibili.com/video/BV1APMS6AEYR)
- **论文分享SONAR：去中心化学习不是“连得越多越好”** - [mlsys.org](https://mlsys.org/virtual/2026/oral/3857) | [github.com](https://github.com/aidecentralized/sonar) | [B station](https://www.bilibili.com/video/BV1DHuQ6HEch)
- **论文分享BOOST：让低秩大模型在多GPU上真正跑快** - [arXiv:2512.12131](https://arxiv.org/abs/2512.12131) | [arxiv.org](https://arxiv.org/abs/2512.12131) | [github.com](https://github.com/Arcana-2236/BOOST) | [B station](https://www.bilibili.com/video/BV1A4gJ6XEYs)
- **论文分享OSWorld-Human：电脑使用智能体离“高效”还有多远** - [arXiv:2506.16042](https://arxiv.org/abs/2506.16042) | [arxiv.org](https://arxiv.org/abs/2506.16042) | [github.com](https://github.com/WukLab/osworld-human) | [B station](https://www.bilibili.com/video/BV14bgA6jEqk)
- **论文分享 Cocoon：相关噪声提升差分隐私训练精度，为什么系统成本却会暴涨** - [usenix.org](https://www.usenix.org/conference/osdi26/presentation/kim-donghwan) | [github.com](https://github.com/psu-paws/Cocoon) | [B station](https://www.bilibili.com/video/BV1dVhc63EzM)
- **论文分享 CSLE：强化学习安全策略如何从模拟器走向真实网络系统** - [proceedings.mlsys.org](https://proceedings.mlsys.org/paper_files/paper/2026/hash/87eaaa8605a1a472d9a9756e7500517b-Abstract-Conference.html]) | [github.com](https://github.com/Kim-Hammar/csle]) | [B station](https://www.bilibili.com/video/BV13Rt96VEnk)
- **论文分享 FLoRIST：联邦 LoRA 如何兼顾精度、通信与异构客户端** - [arXiv:2506.09199](https://arxiv.org/abs/2506.09199) | [arxiv.org](https://arxiv.org/abs/2506.09199) | [github.com](https://github.com/DASS-Lab-Group/FLoRIST) | [B station](https://www.bilibili.com/video/BV1pwY46aExv)
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
- **TileLang 分享：TileLang 简介** - [github.com](https://github.com/tile-ai/tilelang) | [B station](https://www.bilibili.com/video/BV1jHyjBEEFd)
- **TileLang 分享：TileLang 特性介绍** - [github.com](https://github.com/tile-ai/tilelang) | [B station](https://www.bilibili.com/video/BV1jJyjBSEzQ)
- **TileLang 分享：TileLang API 及算子实例** - [github.com](https://github.com/tile-ai/tilelang) | [B station](https://www.bilibili.com/video/BV1LpyjBmEGz)
- **TileLang 分享：TileLang 调优和 Debug** - [github.com](https://github.com/tile-ai/tilelang) | [B station](https://www.bilibili.com/video/BV15pyjBmED5)
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
- **深度学习编译发展概述** - [mindspore.cn](https://www.mindspore.cn/) | [B station](https://www.bilibili.com/video/BV1zd4y1K7MQ)
- **深度学习编译系统概述** - [B station](https://www.bilibili.com/video/BV1kS4y1t7JH)
- **深度学习框架发展（一）** - [B station](https://www.bilibili.com/video/BV1iD4y117td)
- **深度学习框架发展（二）** - [B station](https://www.bilibili.com/video/BV1dt4y1F7Cn)
- **深度学习框架发展（三）** - [B station](https://www.bilibili.com/video/BV1Qe4y1z78o)
- **深度学习硬件平台** - [B station](https://www.bilibili.com/video/BV1JY411Q72M)
- **深度学习自动微分：什么是自动微分** - [B station](https://www.bilibili.com/video/BV1fs4y197km)
- **HIP代码自动生成工具C2HIPC** - [B station](https://www.bilibili.com/video/BV1Jg411Q7z6)
- **循环优化（一）：循环展开和压紧** - [B station](https://www.bilibili.com/video/BV1HB4y1x7zv)
- **循环优化（二）：循环合并** - [B station](https://www.bilibili.com/video/BV1CD4y1B7H2)
- **循环优化（三）：循环分布** - [zhuanlan.zhihu.com](https://zhuanlan.zhihu.com/p/568326883) | [B station](https://www.bilibili.com/video/BV1Z8411t7dC)
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
- **代码加速黑科技：GraalNN如何让程序性能飞跃** - [doi.org](https://doi.org/10.1145/3696443.3708958) | [B station](https://www.bilibili.com/video/BV1m7JizLEC3)
- **CoServe：解锁 CoE 模型有限内存推理新路径** - [doi.org](https://doi.org/10.1145/3676641.3715986) | [B station](https://www.bilibili.com/video/BV17kJLzBEF2)
- **PAPI：从静态到动态，异构PIM如何解锁LLM解码的“智能调度”新纪元** - [B station](https://www.bilibili.com/video/BV1d2Tjz6EtD)
- **CIM-MLC：从芯片到行级，解锁存算一体的编译新范式** - [B station](https://www.bilibili.com/video/BV1aKTvzDEdd)
- **论文分享QiMeng-Xpiler：神经符号融合的异构深度学习系统张量程序跨平台转编译方案** - [arxiv.org](https://arxiv.org/pdf/2505.02146) | [B station](https://www.bilibili.com/video/BV1PopNzFEuH)
- **论文分享UniNDP：面向Near DRAM处理架构的统一编译与仿真工具** - [nicsefc.ee.tsinghua.edu.cn](https://nicsefc.ee.tsinghua.edu.cn/nics_file/pdf/d356f1fd-6204-4b21-8849-a9c3b2e15065.pdf) | [B station](https://www.bilibili.com/video/BV1kfpNzoEjX)
- **编译器自动调优论文分享：破解编译优化组合爆炸，协同搜索助力快速寻优** - [dl.acm.org](https://dl.acm.org/doi/epdf/10.1145/3696443.3708961) | [B station](https://www.bilibili.com/video/BV1y9pNzcEiL)
- **论文分享ANT-ACE：实现神经网络推理自动化的全同态加密编译器框架** - [B station](https://www.bilibili.com/video/BV1A5nwz5EwS)
- **论文分享HALO：面向全同态加密的循环感知自举管理** - [B station](https://www.bilibili.com/video/BV1vhnwzaENX)
- **论文分享Gated Attention：用极小代价换来大模型性能飞升** - [B station](https://www.bilibili.com/video/BV1nGFVzQEAh)
- **论文分享TempSamp-R1：用混合采样强化视频大模型时序定位** - [arXiv:2509.18056](https://arxiv.org/abs/2509.18056) | [arxiv.org](https://arxiv.org/abs/2509.18056) | [github.com](https://github.com/HVision-NKU/TempSamp-R1) | [B station](https://www.bilibili.com/video/BV1QVKb6mEFm)
- **论文分享 FlashInfer：面向大模型推理服务的高效 Attention 引擎** - [arXiv:2501.01005](https://arxiv.org/abs/2501.01005) | [arxiv.org](https://arxiv.org/abs/2501.01005) | [github.com](https://github.com/flashinfer-ai/flashinfer) | [B station](https://www.bilibili.com/video/BV1QKgQ6xEgh)
- **论文分享 CAKE：面向长上下文大模型的自适应 KV Cache 淘汰框架** - [arXiv:2503.12491](https://arxiv.org/abs/2503.12491) | [arxiv.org](https://arxiv.org/abs/2503.12491) | [github.com](https://github.com/antgroup/cakekv) | [B station](https://www.bilibili.com/video/BV16w3a6HEfe)
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
- **自动并行论文分享：Merak** - [arxiv.org](https://arxiv.org/pdf/2206.04959.pdf) | [github.com](https://github.com/HPDL-Group/Merak) | [ieeexplore.ieee.org](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10163912) | [B station](https://www.bilibili.com/video/BV1T94y1C7i4)
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
- **上海人工智能实验室 大模型中心负责人 陈恺 深度解读 Intern-S1——科学多模态大模型** - [chat.intern-ai.org.cn](https://chat.intern-ai.org.cn/) | [huggingface.co](https://huggingface.co/InternLM) | [modelscope.cn](https://modelscope.cn/organization/Shanghai_AI_Laboratory) | [B station](https://www.bilibili.com/video/BV1K3agzBE9i)
- **MiniCPM-V：迈向高效端侧多模态大模型** - [huggingface.co](https://huggingface.co/openbmb) | [modelscope.cn](https://modelscope.cn/organization/OpenBMB) | [B station](https://www.bilibili.com/video/BV1VZaCzLEJr)
- **GLM-V：迈向通用推理的多模态大模型** - [huggingface.co](https://huggingface.co/zai-org) | [modelscope.cn](https://modelscope.cn/organization/ZhipuAI) | [B station](https://www.bilibili.com/video/BV1C9ahzbEmG)
- **Ovis多模态大模型：结构对齐下的视觉语言融合** - [huggingface.co](https://huggingface.co/AIDC-AI) | [modelscope.cn](https://modelscope.cn/organization/AIDC-AI) | [B station](https://www.bilibili.com/video/BV168HUzkEEZ)
- **阶跃星辰在多模态方向上的探索** - [huggingface.co](https://huggingface.co/stepfun-ai) | [modelscope.cn](https://modelscope.cn/organization/stepfun-ai) | [B station](https://www.bilibili.com/video/BV1jAHXzmEao)
- **多模态模型哪些能力已逐渐饱和，还存在哪些不足和短板，未来有哪些值得关注的应用方向?** - [B station](https://www.bilibili.com/video/BV1Y3HazDE2m)
- **多模态模型的推理相比于语言模型，有哪些不一样的技术挑战和发展思路？** - [B station](https://www.bilibili.com/video/BV1s1pWzJEGJ)
- **理解生成一体化是近期多模态大模型的热门探索方向，技术方案有什么样的演进趋势，未来是否有可能实现理解和生成任务的互相促进?** - [B station](https://www.bilibili.com/video/BV1zCJkzQEmp)
- **多模态模型的突破是否被语言模型的研究进展所限制？模型架构和训练范式上有哪些创新路径？** - [B station](https://www.bilibili.com/video/BV1VFpCzQEG6)
- **LongCat-Flash-Omni：美团全模态大模型探索** - [huggingface.co](https://huggingface.co/meituan-longcat/LongCat-Flash-Omni) | [modelscope.cn](https://modelscope.cn/models/meituan-longcat/LongCat-Flash-Omni) | [B station](https://www.bilibili.com/video/BV16jyuBBEZ8)
- **OmniVinci：全模态大模型的架构和数据探索** - [huggingface.co](https://huggingface.co/nvidia/omnivinci) | [B station](https://www.bilibili.com/video/BV1FFU5B8E9x)
- **Ming-Omni：百灵多模态的实践与探索** - [huggingface.co](https://huggingface.co/inclusionAI/Ming-flash-omni-Preview) | [modelscope.cn](https://modelscope.cn/models/inclusionAI/Ming-flash-omni-Preview) | [B station](https://www.bilibili.com/video/BV1oeUbBaEGt)
- **Omni 全模态模型在训练数据和策略上面临哪些挑战？如何构建和利用涵盖图像、视 频、音频、文本的海量数据集，并采用何种训练策略技巧来有效融合多模态信息的？** - [B station](https://www.bilibili.com/video/BV1ZPSaBCEXH)
- **在多模态统一模型中，模态不均衡或者模态偏置问题如何解决？** - [B station](https://www.bilibili.com/video/BV1to28BUEdg)
- **在长上下文建模方面，模型如何真正利用极长序列？例如视频长达上万帧，或多轮对话跨越很长距离，模型如何保留和利用这些信息？** - [B station](https://www.bilibili.com/video/BV1Q625B5Eyp)
- **如何看待通用模态 tokenization 未来面临的挑战？所有模态用统一“词表”表示是否现实？** - [B station](https://www.bilibili.com/video/BV1cG2kBMEQ9)
- **在一个模型中同时学习理解任务和生成任务会不会互相促进？可以从哪些技术路线去突破？** - [B station](https://www.bilibili.com/video/BV1dNmKBFExt)
- **Omni 全模态模型的发展趋势是什么，可能会朝哪些新方向拓展？还有哪些关键技术要突破？** - [B station](https://www.bilibili.com/video/BV12VmCBJEK7)
- **HunyuanOCR：混元原生多模态端到端 OCR 专家** - [huggingface.co](https://huggingface.co/spaces/tencent/HunyuanOCR) | [modelscope.cn](https://modelscope.cn/models/Tencent-Hunyuan/HunyuanOCR) | [B station](https://www.bilibili.com/video/BV1SBBVBEEMp)
- **PaddleOCR-VL：支持 109 种语言的轻量化多模态文档解析方案** - [huggingface.co](https://huggingface.co/PaddlePaddle/PaddleOCR-VL) | [modelscope.cn](https://modelscope.cn/models/PaddlePaddle/PaddleOCR-VL) | [B station](https://www.bilibili.com/video/BV16CBDBzEHJ)
- **MinerU：高效精准的文档解析技术攻坚** - [huggingface.co](https://huggingface.co/opendatalab/MinerU2.5-2509-1.2B) | [modelscope.cn](https://modelscope.cn/models/OpenDataLab/MinerU2.5-2509-1.2B) | [github.com](https://github.com/opendatalab/MinerU) | [B station](https://www.bilibili.com/video/BV1epBaB3EPA)
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
- **技术写作系列课程第一课：技术写作的内容风格与选题** - [mp.weixin.qq.com](https://mp.weixin.qq.com/s?__biz=MzI4MDcxNTY2MQ==&mid=2247510508&idx=1&sn=3072808c7889d1b6dacaf032c8e9dc19&chksm=ebb6a10edcc128186649d95af2132fa88ec1ac30d004c00fb52291ec5e2019b75042bb4b66f1&token=238828277&lang=zh_CN#rd) | [B station](https://www.bilibili.com/video/BV1YX4y1B7mH)
- **技术写作系列课程第二课：如何起一个吸引人的标题** - [mp.weixin.qq.com](https://mp.weixin.qq.com/s?__biz=MzI4MDcxNTY2MQ==&mid=2247510508&idx=1&sn=3072808c7889d1b6dacaf032c8e9dc19&chksm=ebb6a10edcc128186649d95af2132fa88ec1ac30d004c00fb52291ec5e2019b75042bb4b66f1&token=238828277&lang=zh_CN#rd) | [B station](https://www.bilibili.com/video/BV1qs4y1d7jm)
- **技术写作系列课程第三课：如何搭建文章结构** - [mp.weixin.qq.com](https://mp.weixin.qq.com/s?__biz=MzI4MDcxNTY2MQ==&mid=2247510508&idx=1&sn=3072808c7889d1b6dacaf032c8e9dc19&chksm=ebb6a10edcc128186649d95af2132fa88ec1ac30d004c00fb52291ec5e2019b75042bb4b66f1&token=238828277&lang=zh_CN#rd) | [B station](https://www.bilibili.com/video/BV1oc411E7nD)
- **技术写作系列课程第四课：技术写作必备的利器工具** - [mp.weixin.qq.com](https://mp.weixin.qq.com/s?__biz=MzI4MDcxNTY2MQ==&mid=2247510508&idx=1&sn=3072808c7889d1b6dacaf032c8e9dc19&chksm=ebb6a10edcc128186649d95af2132fa88ec1ac30d004c00fb52291ec5e2019b75042bb4b66f1&token=238828277&lang=zh_CN#rd) | [B station](https://www.bilibili.com/video/BV1Tg4y1777V)
- **Label Studio x Segment Anything Model 半自动化标注** - [github.com](https://github.com/open-mmlab/playground/blob/main/label_anything/readme_zh.md) | [cdn.vansin.top](https://cdn.vansin.top/open-mmlab/pg.jpg) | [B station](https://www.bilibili.com/video/BV1uv4y1J7yM)
- **Label-Studio X Segment Anything Model 半自动化标注（2）：Windows CPU 环境配置** - [github.com](https://github.com/open-mmlab/playground/blob/main/label_anything/readme_zh.md) | [cdn.vansin.top](https://cdn.vansin.top/open-mmlab/pg.jpg) | [B station](https://www.bilibili.com/video/BV1hh411F7uR)
- **Label-Studio X Segment Anything Model 半自动化标注（3）：开启前后端并标注** - [github.com](https://github.com/open-mmlab/playground/blob/main/label_anything/readme_zh.md) | [cdn.vansin.top](https://cdn.vansin.top/open-mmlab/pg.jpg) | [B station](https://www.bilibili.com/video/BV1Fo4y1V77n)
- **Label-Studio X Segment Anything Model 半自动化标注（4）：数据集可视化及模型训练和测试** - [github.com](https://github.com/open-mmlab/playground/blob/main/label_anything/readme_zh.md) | [cdn.vansin.top](https://cdn.vansin.top/open-mmlab/pg.jpg) | [B station](https://www.bilibili.com/video/BV1Lh4y1o7qN)
- **以最新数学博资考题为例，书生-S2可以围绕一道复杂问题进行数小时的持续探索** - [chat.intern-ai.org.cn](https://chat.intern-ai.org.cn/intern-s1-math-research/CCQRPo7AqQJjn5hXHaO4VopPQh1Z89ONciSGUKmgFFA=/9) | [chat.intern-ai.org.cn](https://chat.intern-ai.org.cn/) | [github.com](https://github.com/InternLM/Intern-S1) | [internlm.intern-ai.org.cn](https://internlm.intern-ai.org.cn/api/strategy) | [B station](https://www.bilibili.com/video/BV1L8eE6NEk3)
- **书生-S2 实现结合疾病靶标的蛋白药物的自主设计** - [chat.intern-ai.org.cn](https://chat.intern-ai.org.cn/case/Intern-S2/protein-design) | [chat.intern-ai.org.cn](https://chat.intern-ai.org.cn/) | [github.com](https://github.com/InternLM/Intern-S1) | [internlm.intern-ai.org.cn](https://internlm.intern-ai.org.cn/api/strategy) | [B station](https://www.bilibili.com/video/BV1fHeE6zESc)
- **基于给定的化学式，书生-S2 实现物理可行的晶体构建** - [chat.intern-ai.org.cn](https://chat.intern-ai.org.cn/case/Intern-S2/crystal-structure-construction) | [chat.intern-ai.org.cn](https://chat.intern-ai.org.cn/) | [github.com](https://github.com/InternLM/Intern-S1) | [internlm.intern-ai.org.cn](https://internlm.intern-ai.org.cn/api/strategy) | [B station](https://www.bilibili.com/video/BV1JneE63EUa)
- **“书生-S2，帮我构建一个长征7火箭的3D CAD模型”** - [chat.intern-ai.org.cn](https://chat.intern-ai.org.cn/) | [github.com](https://github.com/InternLM/Intern-S1) | [internlm.intern-ai.org.cn](https://internlm.intern-ai.org.cn/api/strategy) | [B station](https://www.bilibili.com/video/BV1RQe76cEAg)
- **Linux 前置基础知识** - [github.com](https://github.com/InternLM/Tutorial/tree/camp3/docs/L0/Linux) | [wjx.cn](https://www.wjx.cn/vm/PvefmG2.aspx?sojumpparm=openmmlabbz) | [github.com](https://github.com/InternLM/Tutorial) | [B station](https://www.bilibili.com/video/BV1FS421d7yg)
- **Python 前置基础知识** - [github.com](https://github.com/InternLM/Tutorial/tree/camp3/docs/L0/Python) | [wjx.cn](https://www.wjx.cn/vm/PvefmG2.aspx?sojumpparm=openmmlabbz) | [github.com](https://github.com/InternLM/Tutorial) | [B station](https://www.bilibili.com/video/BV1mS421X7h4)
- **Git 前置基础知识** - [github.com](https://github.com/InternLM/Tutorial/tree/camp3/docs/L0/Git) | [wjx.cn](https://www.wjx.cn/vm/PvefmG2.aspx?sojumpparm=openmmlabbz) | [github.com](https://github.com/InternLM/Tutorial) | [B station](https://www.bilibili.com/video/BV1Pz421i7bw)
- **书生·浦语大模型全链路开源开放体系** - [wjx.cn](https://www.wjx.cn/vm/PvefmG2.aspx?sojumpparm=openmmlabbz) | [github.com](https://github.com/InternLM/Tutorial) | [B station](https://www.bilibili.com/video/BV18142187g5)
- **8G 显存玩转书生大模型 Demo** - [github.com](https://github.com/InternLM/Tutorial/blob/camp3/docs/L1/Demo/readme.md) | [wjx.cn](https://www.wjx.cn/vm/PvefmG2.aspx?sojumpparm=openmmlabbz) | [github.com](https://github.com/InternLM/Tutorial) | [B station](https://www.bilibili.com/video/BV18x4y147SU)
- **浦语提示词工程实践** - [github.com](https://github.com/InternLM/Tutorial/tree/camp3/docs/L1/Prompt) | [wjx.cn](https://www.wjx.cn/vm/PvefmG2.aspx?sojumpparm=openmmlabbz) | [github.com](https://github.com/InternLM/Tutorial) | [B station](https://www.bilibili.com/video/BV1cU411S7iV)
- **InternLM+LlamaIndex RAG 实践** - [github.com](https://github.com/InternLM/Tutorial/tree/camp3/docs/L1/LlamaIndex) | [github.com](https://github.com/InternLM/Tutorial/blob/camp3/docs/L1/LlamaIndex/task.md) | [wjx.cn](https://www.wjx.cn/vm/PvefmG2.aspx?sojumpparm=openmmlabbz) | [github.com](https://github.com/InternLM/Tutorial) | [B station](https://www.bilibili.com/video/BV19E4m1X79q)
- **XTuner 微调大模型个人小助手认知** - [github.com](https://github.com/InternLM/Tutorial/tree/camp3/docs/L1/XTuner) | [wjx.cn](https://www.wjx.cn/vm/PvefmG2.aspx?sojumpparm=openmmlabbz) | [github.com](https://github.com/InternLM/Tutorial) | [B station](https://www.bilibili.com/video/BV1tz421B72y)
- **OpenCompass 评测 InternLM-1.8B 实践** - [github.com](https://github.com/InternLM/Tutorial/blob/camp3/docs/L1/OpenCompass/readme.md) | [wjx.cn](https://www.wjx.cn/vm/PvefmG2.aspx?sojumpparm=openmmlabbz) | [github.com](https://github.com/InternLM/Tutorial) | [B station](https://www.bilibili.com/video/BV1RM4m1279j)
- **Lagent 自定义你的 Agent 智能体** - [github.com](https://github.com/InternLM/Tutorial/blob/camp3/docs/L2/Lagent/readme.md) | [wjx.cn](https://www.wjx.cn/vm/PvefmG2.aspx?sojumpparm=openmmlabbz) | [github.com](https://github.com/InternLM/Tutorial) | [B station](https://www.bilibili.com/video/BV18M4m1y7sm)
- **LMDeploy 量化部署进阶实践** - [github.com](https://github.com/InternLM/Tutorial/blob/camp3/docs/L2/LMDeploy/readme.md) | [wjx.cn](https://www.wjx.cn/vm/PvefmG2.aspx?sojumpparm=openmmlabbz) | [github.com](https://github.com/InternLM/Tutorial) | [B station](https://www.bilibili.com/video/BV1df421q7cR)
- **InternVL（冷笑话大师）部署微调实践** - [github.com](https://github.com/InternLM/Tutorial/blob/camp3/docs/L2/InternVL/joke_readme.md) | [wjx.cn](https://www.wjx.cn/vm/PvefmG2.aspx?sojumpparm=openmmlabbz) | [github.com](https://github.com/InternLM/Tutorial) | [B station](https://www.bilibili.com/video/BV1N6p1eXETX)
- **茴香豆：企业级知识库问答工具** - [github.com](https://github.com/InternLM/Tutorial/tree/camp3/docs/L2/Huixiangdou) | [wjx.cn](https://www.wjx.cn/vm/PvefmG2.aspx?sojumpparm=openmmlabbz) | [github.com](https://github.com/InternLM/Tutorial) | [B station](https://www.bilibili.com/video/BV1C5W2epEYP)
- **销冠——卖货主播大模型** - [github.com](https://github.com/InternLM/Tutorial/tree/camp3/docs/EasterEgg/StreamerSales) | [B station](https://www.bilibili.com/video/BV1f1421b7Du)
- **InternLM-1.8B 模型安卓端侧部署实践** - [github.com](https://github.com/InternLM/Tutorial/tree/camp3/docs/EasterEgg/Android) | [wjx.cn](https://www.wjx.cn/vm/PvefmG2.aspx?sojumpparm=openmmlabbz) | [github.com](https://github.com/InternLM/Tutorial) | [B station](https://www.bilibili.com/video/BV1Ai421a7R6)
- **手把手带你使用 InternLM 实现谁是卧底游戏** - [github.com](https://github.com/InternLM/Tutorial/tree/camp3/docs/EasterEgg/Game) | [wjx.cn](https://www.wjx.cn/vm/PvefmG2.aspx?sojumpparm=openmmlabbz) | [github.com](https://github.com/InternLM/Tutorial) | [B station](https://www.bilibili.com/video/BV1uhp1efEeE)
- **旋转~跳跃~检测王者 MMDetection 的好兄弟来啦！** - [github.com](https://github.com/open-mmlab/mmrotate) | [B station](https://www.bilibili.com/video/BV1Hr4y1r73p)
- **墩墩生成器来啦！三步穿上墩墩服变身冰墩墩，做今年冬天最靓崽！** - [github.com](https://github.com/open-mmlab/mmpose/tree/master/tools/webcam/configs) | [B station](https://www.bilibili.com/video/BV1Tq4y1t77C)
- **千行百业智能化落地，MMDeploy 助你一“部”到位！** - [github.com](https://github.com/open-mmlab/mmdeploy) | [B station](https://www.bilibili.com/video/BV1g34y1z7EW)
- **操作顺滑，一秒上手，LabelBee 让人工标注更智能!** - [B station](https://www.bilibili.com/video/BV1pr4y1X7VM)
- **画形亦画骨，知面也知心，与 MMHuman3D 一道探索人体参数化模型！** - [github.com](https://github.com/open-mmlab/mmhuman3d) | [B station](https://www.bilibili.com/video/BV1Ch411s7mS)
- **MMFlow:帧与帧之间的追光者** - [github.com](https://github.com/open-mmlab/mmflow！) | [B station](https://www.bilibili.com/video/BV1Zr4y1r72H)
- **【MMTracking】单目标跟踪！持续跟踪！** - [github.com](https://github.com/open-mmlab/mmtracking) | [B station](https://www.bilibili.com/video/BV1Ev411376o)
- **【MMTracking】国庆快乐！多目标跟踪走丢也不怕！** - [github.com](https://github.com/open-mmlab/mmtracking) | [zhuanlan.zhihu.com](https://zhuanlan.zhihu.com/p/414625166) | [B station](https://www.bilibili.com/video/BV1tU4y1c7mj)
- **【MMtracking】实时追踪！套马杆的汉子的马** - [github.com](https://github.com/open-mmlab/mmtracking) | [zhuanlan.zhihu.com](https://zhuanlan.zhihu.com/p/412817354) | [B station](https://www.bilibili.com/video/BV1xL41147n5)
- **【MMDetection】七夕没对象？用我检测一下！** - [github.com](https://github.com/open-mmlab/mmdetection) | [B station](https://www.bilibili.com/video/BV1QU4y177oZ)
- **【MMPose】火柴人出击！** - [github.com](https://github.com/open-mmlab/mmpose) | [B station](https://www.bilibili.com/video/BV1YU4y1H7Dq)
- **【MMPose】 demo webcam** - [github.com](https://github.com/open-mmlab/mmpose) | [B station](https://www.bilibili.com/video/BV1pw411R7iD)
- **【MMPose】3D Human Pose** - [github.com](https://github.com/open-mmlab/mmpose) | [B station](https://www.bilibili.com/video/BV1B3411672x)
- **【MMPose】Animal Pose** - [github.com](https://github.com/open-mmlab/mmpose) | [B station](https://www.bilibili.com/video/BV1t341167V7)
- **【MMPose】2D Human Pose** - [github.com](https://github.com/open-mmlab/mmpose) | [B station](https://www.bilibili.com/video/BV1Zf4y157PF)
- **AI 生成视频不闪了！社区大佬又整新活啦！** - [github.com](https://github.com/open-mmlab/mmagic) | [B station](https://www.bilibili.com/video/BV19o4y1b7RZ)
- **Segment Anything Model+ MMagic = Generate Anything！** - [github.com](https://github.com/open-mmlab/playground/tree/main/mmagic_sam) | [github.com](https://github.com/open-mmlab/mmagic) | [B station](https://www.bilibili.com/video/BV1ws4y1R7aB)
- **DragGAN 应用来啦，无需部署，在线体验！** - [github.com](https://github.com/XingangPan/DragGAN) | [openxlab.org.cn](https://openxlab.org.cn/apps/detail/XingangPan/DragGAN) | [B station](https://www.bilibili.com/video/BV1Rh4y1y7LK)
- **还在排队 SearchGPT？快来试试开源的 AI 搜索引擎框架 MindSearch！** - [github.com](https://github.com/InternLM/mindsearch) | [B station](https://www.bilibili.com/video/BV1Kx4y1s7SS)
- **人工智能时代的创业新范式** - [B station](https://www.bilibili.com/video/BV1gAmnBZEuK)
- **从初心到商业化：以快速迭代创造用户真价值** - [B station](https://www.bilibili.com/video/BV1hwmnBbE7d)
- **医疗领域大模型微调实践** - [colearn.intern-ai.org.cn](https://colearn.intern-ai.org.cn/c6?s=bili) | [B station](https://www.bilibili.com/video/BV1gfqJBNEmT)
- **MMSelfSup 代码库介绍** - [github.com](https://github.com/open-mmlab/mmselfsup) | [B station](https://www.bilibili.com/video/BV1hg411r7iK)
- **MMSelfSup 代码教程【1】模型自监督预训练 之 SimCLR** - [github.com](https://github.com/open-mmlab/mmselfsup) | [B station](https://www.bilibili.com/video/BV1Ht4y1n7jy)
- **MMSelfSup 代码教程【2】图片向量可视化 t-SNE** - [github.com](https://github.com/open-mmlab/mmselfsup) | [B station](https://www.bilibili.com/video/BV1yS4y1W7B6)
- **MMSelfSup 代码教程【3】自监督预训练模型的评估：“分类” 下游任务 之 线性评估** - [github.com](https://github.com/open-mmlab/mmselfsup) | [B station](https://www.bilibili.com/video/BV1LP41157uA)
- **MMSelfSup 代码教程【4】自监督预训练模型的评估：“分类” 下游任务 之 SVM 评估** - [github.com](https://github.com/open-mmlab/mmselfsup) | [B station](https://www.bilibili.com/video/BV1Ga411G73i)
- **MMSelfSup 代码教程【5】自监督预训练模型的评估：“检测”下游任务** - [github.com](https://github.com/open-mmlab/mmselfsup) | [B station](https://www.bilibili.com/video/BV1EP41157BL)
- **MMSelfSup 代码教程【6】在 MMDetection 中使用自监督预训练模型** - [github.com](https://github.com/open-mmlab/mmselfsup) | [B station](https://www.bilibili.com/video/BV1Fe4y1Z7Wh)
- **MMSelfSup 代码教程【7】模型自监督预训练 之 MAE** - [github.com](https://github.com/open-mmlab/mmselfsup) | [B station](https://www.bilibili.com/video/BV1EY4y1u7Px)
- **10 分钟带你上手 MMEval（一）：MMEval 介绍** - [github.com](https://github.com/open-mmlab/mmeval) | [B station](https://www.bilibili.com/video/BV1m24y127Db)
- **10 分钟带你上手 MMEval（二）：MMEval 使用介绍** - [github.com](https://github.com/open-mmlab/mmeval) | [B station](https://www.bilibili.com/video/BV1HP4y117pA)
- **10 分钟带你上手 MMEval（三）：如何给 MMEval 添加新的评测指标** - [github.com](https://github.com/open-mmlab/mmeval) | [B station](https://www.bilibili.com/video/BV1Ev4y1d7nK)
- **大语言模型复杂医疗推理评测基准MedAgentsBench** - [hub.opencompass.org.cn](https://hub.opencompass.org.cn/dataset-detail/MedAgents-Bench) | [B station](https://www.bilibili.com/video/BV1J5oXYYEYH)
- **通用写作评测基准 WritingBench** - [hub.opencompass.org.cn](https://hub.opencompass.org.cn/dataset-detail/WritingBench) | [B station](https://www.bilibili.com/video/BV1dFdpYqELh)
- **首个视频时空推理评估基准 V-STaR** - [hub.opencompass.org.cn](https://hub.opencompass.org.cn/dataset-detail/V-STaR) | [B station](https://www.bilibili.com/video/BV1DbdHYZEbq)
- **ViLBench：多模态过程奖励（Process Reward）建模组件** - [hub.opencompass.org.cn](https://hub.opencompass.org.cn/dataset-detail/ViLBench) | [B station](https://www.bilibili.com/video/BV1cZ5kzyECC)
- **CMU团队打造考公逻辑谜题 VisualPuzzles** - [hub.opencompass.org.cn](https://hub.opencompass.org.cn/dataset-detail/VisualPuzzles) | [B station](https://www.bilibili.com/video/BV16kL7zrEdq)
- **ToolHop：查询驱动的多跳工具使用评测集** - [hub.opencompass.org.cn](https://hub.opencompass.org.cn/dataset-detail/ToolHop) | [B station](https://www.bilibili.com/video/BV1CjExzGE7s)
- **1. MMDetection3D 介绍及安装配置** - [B station](https://www.bilibili.com/video/BV1aG4y197is)
- **2. 使用 MMDet3D 预训练模型在点云和数据图像上推理** - [B station](https://www.bilibili.com/video/BV1E44y1Q7qi)
- **3. KITTI 数据集介绍及 MMDet3D 坐标系规范** - [B station](https://www.bilibili.com/video/BV1vv4y1d7br)
- **4. 使用 MMDetection3D 训练** - [B station](https://www.bilibili.com/video/BV11G4y157ux)
- **5. PointPillars 和 KittiDataset 的配置文件解读** - [B station](https://www.bilibili.com/video/BV14M41167Ct)
- **6. PointPillars 和 KittiDataset 的代码解读** - [B station](https://www.bilibili.com/video/BV1Xe4y1g7Xv)
- **大语言模型原理与书生大模型提示词工程实践** - [aicarrier.feishu.cn](https://aicarrier.feishu.cn/wiki/SEfTwYCgAiDEkskx7yocvzuhnph) | [aicarrier.feishu.cn](https://aicarrier.feishu.cn/wiki/DK9Wwf1DRiidwgk1FPDcvj6Bnxq) | [colearn.intern-ai.org.cn](https://colearn.intern-ai.org.cn/set?s=bz) | [aicarrier.feishu.cn](https://aicarrier.feishu.cn/wiki/QdhEwaIINietCak3Y1dcdbLJn3e) | [B station](https://www.bilibili.com/video/BV1vUjYz2Eys)
- **玩转书生大模型 API 之 Browse Use实践** - [aicarrier.feishu.cn](https://aicarrier.feishu.cn/wiki/XhoNw2qzPir8qmkVNYyc5YAunrc) | [colearn.intern-ai.org.cn](https://colearn.intern-ai.org.cn/set?s=bz) | [B station](https://www.bilibili.com/video/BV1SPGnzWEN4)
- **InternLM 微调论文分类实践** - [aicarrier.feishu.cn](https://aicarrier.feishu.cn/wiki/QdhEwaIINietCak3Y1dcdbLJn3e) | [colearn.intern-ai.org.cn](https://colearn.intern-ai.org.cn/set?s=bz) | [B station](https://www.bilibili.com/video/BV1DyGuz4Ewp)
- **GraphGen 训练数据合成框架** - [colearn.intern-ai.org.cn](https://colearn.intern-ai.org.cn/set) | [B station](https://www.bilibili.com/video/BV1EA31zMEQk)
- **CAMEL 书生多智能体系统实践** - [B station](https://www.bilibili.com/video/BV15A3EzWEPv)
- **国产开源、免费的 AI 图像与视频创作平台MagicMaker，新手教程来啦！** - [magicmaker.openxlab.org.cn](https://magicmaker.openxlab.org.cn/) | [B station](https://www.bilibili.com/video/BV1w2421A7YP)
- **“龙在城隍庙吃小笼包”MagicMaker亮相东方卫视春晚特别直播节目，科技魔法点亮传统舞台** - [magicmaker.openxlab.org.cn](https://magicmaker.openxlab.org.cn/home) | [B station](https://www.bilibili.com/video/BV1TS421A7UR)
- **“一个小男生和一个小女生在黄河路‘偷心’”MagicMaker亮相东方卫视春晚特别直播节目，科技魔法点亮传统舞台** - [magicmaker.openxlab.org.cn](https://magicmaker.openxlab.org.cn/home) | [B station](https://www.bilibili.com/video/BV18z421X7ci)
- **“龙在东方明珠上盘旋”MagicMaker亮相东方卫视春晚特别直播节目，科技魔法点亮传统舞台** - [magicmaker.openxlab.org.cn](https://magicmaker.openxlab.org.cn/home) | [B station](https://www.bilibili.com/video/BV1VC411s7Fv)
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
- **社区开放麦#33 | 详解 ACCV22 大规模细粒度图像分类夺冠方案** - [github.com](https://github.com/open-mmlab/mmselfsup/tree/dev-1.x/projects/fgia_accv2022_1st) | [github.com](https://github.com/open-mmlab/mmclassification/tree/dev-1.x/projects/fgia_accv2022_1st) | [B station](https://www.bilibili.com/video/BV13M411S7b5)
- **社区开放麦#34 | 突破 AI 推理性能瓶颈，神经网络量化的方法与实践** - [B station](https://www.bilibili.com/video/BV128411n7yN)
- **AI 奇妙夜#3 | 大规模多模态预训练最新研究进展** - [B station](https://www.bilibili.com/video/BV1J14y1A7SE)
- **社区开放麦#36 多模态场景下的高性能 Embedding 计算服务** - [B station](https://www.bilibili.com/video/BV1ET411m7gu)
- **社区开放麦#37 | 牛津大学vgg组博士：提高遮挡检测下的目标检测效果** - [B station](https://www.bilibili.com/video/BV1NA41167kN)
- **社区开放麦#38 目标检测新范式！DETR 系列算法解读** - [B station](https://www.bilibili.com/video/BV17x4y1w7ZK)
- **弱监督有向目标检测 | 杨学** - [B station](https://www.bilibili.com/video/BV1GD4y1g7s8)
- **社区开放麦#41 | 视觉大模型设计新范式** - [B station](https://www.bilibili.com/video/BV1zs4y15754)
- **AI 奇妙夜#4 | 文字识别：从数据趋动到模型自监督** - [github.com](https://github.com/open-mmlab/mmocr) | [B station](https://www.bilibili.com/video/BV1Zb41197V4)
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
- **MMBench：基于ChatGPT的全方位多模能力评测体系** - [opencompass.org.cn](https://opencompass.org.cn/MMBench) | [arxiv.org](https://arxiv.org/pdf/2307.06281.pdf) | [opencompass.org.cn](https://opencompass.org.cn/omni-rank) | [B station](https://www.bilibili.com/video/BV16z4y1x7qG)
- **迈向更强的端到端多人姿态估计** - [B station](https://www.bilibili.com/video/BV1fj41197R9)
- **SAM 时代，图像/视频分割将何去何从？** - [openxlab.org.cn](https://openxlab.org.cn/apps/detail/keleiwhu/sam-hq) | [B station](https://www.bilibili.com/video/BV1ZP41147xQ)
- **MFF：简单高效的多级特征融合自监督方法 | ICCV 2023** - [github.com](https://github.com/open-mmlab/mmpretrain/tree/dev) | [readpaper.com](https://readpaper.com/paper/4784261971549618177?channel=OpenMMlab) | [B station](https://www.bilibili.com/video/BV1q94y1z7Xe)
- **更好的人体姿态，更好的生成图像** - [arXiv:2307.15880](https://arxiv.org/abs/2307.15880) | [yzd-v.github.io](https://yzd-v.github.io/page/) | [arxiv.org](https://arxiv.org/abs/2307.15880) | [github.com](https://github.com/IDEA-Research/DWPose) | [openxlab.org.cn](https://openxlab.org.cn/apps/detail/mmpose/RTMPose) | [B station](https://www.bilibili.com/video/BV1rw411Q7t6)
- **基于大规模多模态扩散模型的文本到视频生成** - [arXiv:2212.09478](https://arxiv.org/abs/2212.09478) | [arxiv.org](https://arxiv.org/abs/2212.09478) | [arxiv.org](https://arxiv.org/abs/2305.10874) | [arxiv.org](https://arxiv.org/abs/2306.07257) | [arxiv.org](https://arxiv.org/abs/2307.16371) | [B station](https://www.bilibili.com/video/BV1BP411h7oQ)
- **多模态任务终结者：Meta-Transformer** - [readpaper.com](https://readpaper.com/paper/1880723763752826112?channel=OpenMMLab) | [B station](https://www.bilibili.com/video/BV1Bu4y1y714)
- **迈向更强的开集目标检测-From Detection to Grounding** - [readpaper.com](https://readpaper.com/paper/4731752776334327809?channel=OpenMMlab) | [B station](https://www.bilibili.com/video/BV1Mk4y1F7cp)
- **如何基于大模型构建智能体？多机构百页综述从交互角度详解 AI Agent！** - [arxiv.org](https://arxiv.org/pdf/2305.13246.pdf) | [B station](https://www.bilibili.com/video/BV1884y1U7CR)
- **你的3D感知模型够鲁棒吗？Robo3D告诉你答案！** - [arXiv:2303.17597](https://arxiv.org/abs/2303.17597) | [arxiv.org](https://arxiv.org/abs/2303.17597) | [arxiv.org](https://arxiv.org/abs/2304.06719) | [B station](https://www.bilibili.com/video/BV1nu411u7W6)
- **如何高效微调大模型？技术原理与最佳实践揭秘！** - [github.com](https://github.com/liguodongiot/llm-action/tree/main/train/peft) | [B station](https://www.bilibili.com/video/BV1qw411c7Hd)
- **大模型时代通用检测趋势解读及MMDetection未来展望** - [B station](https://www.bilibili.com/video/BV1o94y1L7fg)
- **CVPR23 | 3D Occupancy 预测冠军方案：FB-OCC** - [B station](https://www.bilibili.com/video/BV1PX4y1e7zz)
- **多模态 Agents：用大模型语言模型串联多模态专家** - [B station](https://www.bilibili.com/video/BV1mM411X7Zn)
- **探索未知：LLM Agent 应用开发的全新时代** - [zhuanlan.zhihu.com](https://zhuanlan.zhihu.com/p/622947810) | [zhuanlan.zhihu.com](https://zhuanlan.zhihu.com/p/629589593) | [zhuanlan.zhihu.com](https://zhuanlan.zhihu.com/p/633033220) | [zhuanlan.zhihu.com](https://zhuanlan.zhihu.com/p/642690763) | [B station](https://www.bilibili.com/video/BV1W84y197qq)
- **AI时代数据应用的全链路工厂- Chat2DB** - [sqlgpt.cn](https://sqlgpt.cn/zh) | [github.com](https://github.com/chat2db/Chat2DB/) | [B station](https://www.bilibili.com/video/BV1re411m7p3)
- **语音与音频生成 Amphion揭秘霉霉如何演唱《稻香》** - [arXiv:2312.09911](https://arxiv.org/abs/2312.09911) | [github.com](https://github.com/open-mmlab/Amphion) | [arxiv.org](https://arxiv.org/abs/2312.09911) | [arxiv.org](https://arxiv.org/abs/2310.11160) | [arxiv.org](https://arxiv.org/abs/2304.00830) | [B station](https://www.bilibili.com/video/BV1AV411R7SS)
- **RTMPose 家族史诗级更新！多人、全身一网打尽** - [arXiv:2312.07526](https://arxiv.org/abs/2312.07526) | [arxiv.org](https://arxiv.org/abs/2312.07526) | [github.com](https://github.com/open-mmlab/mmpose/tree/main/projects/rtmo) | [B station](https://www.bilibili.com/video/BV1P5411v7tz)
- **清华提出首个面向无监督和半监督新意图发现的文本聚类框架USNID** - [arXiv:2304.07699](https://arxiv.org/abs/2304.07699) | [ieeexplore.ieee.org](https://ieeexplore.ieee.org/document/10349963) | [arxiv.org](https://arxiv.org/abs/2304.07699) | [github.com](https://github.com/thuiar/TEXTOIR) | [B station](https://www.bilibili.com/video/BV1464y1w73f)
- **Beyond Segmentation Anything，超越SAM** - [arXiv:2312.06660](https://arxiv.org/abs/2312.06660) | [arxiv.org](https://arxiv.org/abs/2312.06660) | [github.com](https://github.com/chongzhou96/EdgeSAM) | [huggingface.co](https://huggingface.co/spaces/chongzhou/EdgeSAM) | [arxiv.org](https://arxiv.org/abs/2401.02955) | [B station](https://www.bilibili.com/video/BV1xC411r7qq)
- **Sora 夜谈之 Video Diffusion 综述** - [arxiv.org](https://arxiv.org/pdf/2310.10647.pdf) | [github.com](https://github.com/ChenHsing/Awesome-Video-Diffusion-Models) | [B station](https://www.bilibili.com/video/BV1cJ4m1e7sQ)
- **新一代换脸神器 InstantID：高保真人像秒级生成** - [arXiv:2401.07519](https://arxiv.org/abs/2401.07519) | [github.com](https://github.com/InstantID/InstantID) | [instantid.github.io](https://instantid.github.io/) | [arxiv.org](https://arxiv.org/abs/2401.07519) | [openxlab.org.cn](https://openxlab.org.cn/apps/detail/InstantX/InstantID) | [B station](https://www.bilibili.com/video/BV1HH4y177T5)
- **CVPR 2024 - 具身智能中的多模态三维感知思考** - [arXiv:2312.16170](https://arxiv.org/abs/2312.16170) | [arxiv.org](https://arxiv.org/abs/2312.16170) | [tai-wang.github.io](http://tai-wang.github.io/embodiedscan) | [github.com](https://github.com/OpenRobotLab/EmbodiedScan) | [opendrivelab.com](https://opendrivelab.com/challenge2024/#multiview_3d_visual_grounding) | [B station](https://www.bilibili.com/video/BV1nt421V7UY)
- **PK 周杰伦，全能音乐创作大模型 SongComposer 作词作曲令人惊叹** - [arXiv:2402.17645](https://arxiv.org/abs/2402.17645) | [arxiv.org](https://arxiv.org/abs/2402.17645) | [pjlab-songcomposer.github.io](https://pjlab-songcomposer.github.io/) | [B station](https://www.bilibili.com/video/BV1bw4m1d7dK)
- **Stable Diffusion 3 论文技术解析，架构细节大揭秘！** - [stabilityai-public-packages.s3.us-west-2.amazonaws.com](https://stabilityai-public-packages.s3.us-west-2.amazonaws.com/Stable+Diffusion+3+Paper.pdf) | [B station](https://www.bilibili.com/video/BV1Ni421d7ud)
- **无需训练的 Stable Diffusion 视频编辑方法** - [arXiv:2306.07954](https://arxiv.org/abs/2306.07954) | [arxiv.org](https://arxiv.org/abs/2306.07954) | [github.com](https://github.com/williamyang1991/Rerender_A_Video) | [B station](https://www.bilibili.com/video/BV12w4m1R75t)
- **Latte 专场: 深度解读视频生成与训练技术** - [github.com](https://github.com/Vchitect) | [wyhsirius.github.io](https://wyhsirius.github.io/) | [github.com](https://github.com/InternLM/xtuner) | [B station](https://www.bilibili.com/video/BV14F4m1K7Wz)
- **微软研究院谭旭带来零样本 TTS 模型 NaturalSpeech 3** - [arxiv.org](https://arxiv.org/pdf/2403.03100.pdf) | [speechresearch.github.io](https://speechresearch.github.io/naturalspeech3/) | [huggingface.co](https://huggingface.co/spaces/amphion/naturalspeech3_facodec) | [B station](https://www.bilibili.com/video/BV1tm421s7B6)
- **零样本语音生成大模型与Amphion实践** - [arXiv:2312.09911](https://arxiv.org/abs/2312.09911) | [arxiv.org](https://arxiv.org/abs/2312.09911) | [arxiv.org](https://arxiv.org/abs/2403.03100) | [github.com](https://github.com/open-mmlab/Amphion) | [B station](https://www.bilibili.com/video/BV18C41177JA)
- **多模态大模型的技术实践与思考** - [B station](https://www.bilibili.com/video/BV17n4y1d7wp)
- **当大模型遇上心理咨询：基于心理咨询报告的对话重构和评测框架CPsyCoun** - [B station](https://www.bilibili.com/video/BV1vJ4m1g7G4)
- **ACL 24 论文分享（东北大学信息检索小组场）** - [B station](https://www.bilibili.com/video/BV144421Q7ir)
- **SD-Eval新基准，让语音交互大模型情智兼备** - [B station](https://www.bilibili.com/video/BV16E421A7wU)
- **魔搭社区-浦语模型和工具实战** - [modelscope.cn](https://www.modelscope.cn/studios/Shanghai_AI_Laboratory/MindSearch) | [modelscope.cn](https://modelscope.cn/studios/opencompass/CompassArena) | [B station](https://www.bilibili.com/video/BV1zy411i7yp)
- **开源工具MinerU助力复杂PDF高效解析提取** - [B station](https://www.bilibili.com/video/BV15rHSeyEk2)
- **MindSearch：AI 时代的“思考型”智能搜索引擎** - [B station](https://www.bilibili.com/video/BV1UHy3YYEHz)
- **MaskGCT：基于掩码生成模型的大规模零样本 TTS 模型** - [B station](https://www.bilibili.com/video/BV1LJD1YsEd4)
- **玩转 MMYOLO 之工具篇（一）：特征图可视化** - [github.com](https://github.com/open-mmlab/mmyolo) | [github.com](https://github.com/open-mmlab/mmyolo/issues/136) | [B station](https://www.bilibili.com/video/BV188411s7o8)
- **玩转 MMYOLO 之基础篇（一）：配置文件全解读** - [github.com](https://github.com/open-mmlab/mmyolo) | [github.com](https://github.com/open-mmlab/mmyolo/issues/136) | [github.com](https://github.com/open-mmlab/OpenMMLabCourse) | [github.com](https://github.com/open-mmlab/OpenMMLabCourse/blob/main/mmyolo.md) | [B station](https://www.bilibili.com/video/BV1214y157ck)
- **【MMYOLO】超酷炫 RTMDet 特征图可视化 demo** - [B station](https://www.bilibili.com/video/BV1je4y1478R)
- **玩转 MMYOLO 之实用篇（一）: 源码阅读和调试「必备」技巧** - [github.com](https://github.com/open-mmlab/mmyolo) | [github.com](https://github.com/open-mmlab/mmyolo/issues/136) | [github.com](https://github.com/open-mmlab/OpenMMLabCourse) | [github.com](https://github.com/open-mmlab/OpenMMLabCourse/blob/main/mmyolo.md) | [B station](https://www.bilibili.com/video/BV1N14y1V7mB)
- **MMYOLO 社区贡献者经验分享会** - [github.com](https://github.com/open-mmlab/mmyolo) | [github.com](https://github.com/open-mmlab/mmyolo/issues/136) | [github.com](https://github.com/open-mmlab/OpenMMLabCourse) | [github.com](https://github.com/open-mmlab/OpenMMLabCourse/blob/main/mmyolo.md) | [B station](https://www.bilibili.com/video/BV12d4y1r7Nd)
- **玩转 MMYOLO 之基础篇（二）： 工程文件结构简析** - [github.com](https://github.com/open-mmlab/mmyolo) | [github.com](https://github.com/open-mmlab/mmyolo/issues/136) | [github.com](https://github.com/open-mmlab/OpenMMLabCourse) | [github.com](https://github.com/open-mmlab/OpenMMLabCourse/blob/main/mmyolo.md) | [B station](https://www.bilibili.com/video/BV1LP4y117jS)
- **玩转 MMYOLO 之实用篇（二）: 10分钟带你换遍主干网络** - [github.com](https://github.com/open-mmlab/mmyolo) | [github.com](https://github.com/open-mmlab/mmyolo/issues/136) | [github.com](https://github.com/open-mmlab/OpenMMLabCourse) | [github.com](https://github.com/open-mmlab/OpenMMLabCourse/blob/main/mmyolo.md) | [B station](https://www.bilibili.com/video/BV1JG4y1d7GC)
- **玩转 MMYOLO 之工具篇（二）：十分钟轻松掌握大图推理** - [github.com](https://github.com/open-mmlab/mmyolo) | [github.com](https://github.com/open-mmlab/mmyolo/issues/136) | [github.com](https://github.com/open-mmlab/OpenMMLabCourse) | [github.com](https://github.com/open-mmlab/OpenMMLabCourse/blob/main/mmyolo.md) | [B station](https://www.bilibili.com/video/BV1EK411R7Ws)
- **玩转 MMYOLO 之实用篇（三）：自定义数据集从标注到部署保姆级教程** - [github.com](https://github.com/open-mmlab/mmyolo) | [github.com](https://github.com/open-mmlab/mmyolo/issues/136) | [github.com](https://github.com/open-mmlab/OpenMMLabCourse) | [github.com](https://github.com/open-mmlab/OpenMMLabCourse/blob/main/mmyolo.md) | [B station](https://www.bilibili.com/video/BV1RG4y137i5)
- **玩转 MMYOLO 之实用篇（四）：顶会第一步 · 模块自定义** - [github.com](https://github.com/open-mmlab/mmyolo) | [github.com](https://github.com/open-mmlab/mmyolo/issues/136) | [github.com](https://github.com/open-mmlab/OpenMMLabCourse) | [github.com](https://github.com/open-mmlab/OpenMMLabCourse/blob/main/mmyolo.md) | [B station](https://www.bilibili.com/video/BV1yd4y1j7VD)
- **玩转 MMYOLO 之实用篇（五）：训练和测试技巧合集** - [github.com](https://github.com/open-mmlab/mmyolo) | [github.com](https://github.com/open-mmlab/mmyolo/issues/136) | [github.com](https://github.com/open-mmlab/OpenMMLabCourse) | [github.com](https://github.com/open-mmlab/OpenMMLabCourse/blob/main/mmyolo.md) | [B station](https://www.bilibili.com/video/BV1GM4y1U77z)
- **清华大学导师亲授！3D目标检测超硬核课程新鲜出炉~** - [B station](https://www.bilibili.com/video/BV1Sc411K7L1)
- **人体关键点检测与MMPose** - [B station](https://www.bilibili.com/video/BV1kk4y1L7Xb)
- **1. PyTorch 模型部署基础知识** - [B station](https://www.bilibili.com/video/BV1Tx4y1F768)
- **2. 安装配置 MMDeploy 环境** - [B station](https://www.bilibili.com/video/BV1yX4y1X7jp)
- **3. 部署 MMClassification 图像分类模型** - [B station](https://www.bilibili.com/video/BV1V84y1J7MT)
- **4. 部署 MMDetection 目标检测模型** - [B station](https://www.bilibili.com/video/BV11R4y1v7L2)
- **自监督学习与 MMSelfSup** - [B station](https://www.bilibili.com/video/BV1iu4y1e7tV)
- **Linux 前置基础（基本命令、SSH及端口映射）** - [github.com](https://github.com/InternLM/Tutorial/tree/camp4/docs/L0/linux) | [github.com](https://github.com/InternLM/Tutorial/tree/camp4/docs/L0/linux/task.md) | [colearn.intern-ai.org.cn](https://colearn.intern-ai.org.cn/set?s=bz4) | [studio.intern-ai.org.cn](https://studio.intern-ai.org.cn/) | [B station](https://www.bilibili.com/video/BV13U1VYmEUr)
- **Python 前置基础（熟悉断点调试、依赖指定路径安装）** - [github.com](https://github.com/InternLM/Tutorial/blob/camp4/docs/L0/Python) | [github.com](https://github.com/InternLM/Tutorial/blob/camp4/docs/L0/Python/task.md) | [colearn.intern-ai.org.cn](https://colearn.intern-ai.org.cn/set?s=bzl0python) | [studio.intern-ai.org.cn](https://studio.intern-ai.org.cn/) | [B station](https://www.bilibili.com/video/BV1u61jYSExg)
- **Git 前置基础（熟悉常见 Git 命令及GitHub 平台）** - [github.com](https://github.com/InternLM/Tutorial/blob/camp4/docs/L0/git) | [github.com](https://github.com/InternLM/Tutorial/blob/camp4/docs/L0/git/task.md) | [colearn.intern-ai.org.cn](https://colearn.intern-ai.org.cn/set?s=bz_git) | [studio.intern-ai.org.cn](https://studio.intern-ai.org.cn/) | [B station](https://www.bilibili.com/video/BV15MShYkEgg)
- **玩转Hugging Face/魔搭/魔乐平台(熟悉模型下载上传及应用上传)** - [github.com](https://github.com/InternLM/Tutorial/blob/camp4/docs/L0/maas) | [github.com](https://github.com/InternLM/Tutorial/blob/camp4/docs/L0/maas/task.md) | [colearn.intern-ai.org.cn](https://colearn.intern-ai.org.cn/set?s=bzl0maas) | [studio.intern-ai.org.cn](https://studio.intern-ai.org.cn/) | [B station](https://www.bilibili.com/video/BV1XxStYYEH1)
- **书生·浦语大模型开源开放体系** - [github.com](https://github.com/InternLM/Tutorial/tree/camp4/docs/L1/ToolChain) | [colearn.intern-ai.org.cn](https://colearn.intern-ai.org.cn/set?s=bz_toolchain) | [studio.intern-ai.org.cn](https://studio.intern-ai.org.cn/) | [B station](https://www.bilibili.com/video/BV1CkSUYGE1v)
- **玩转书生「多模态对话」与「AI 搜索」产品** - [internlm.intern-ai.org.cn](https://internlm.intern-ai.org.cn/) | [github.com](https://github.com/InternLM/Tutorial/blob/camp4/docs/L1/InternIntro) | [github.com](https://github.com/InternLM/Tutorial/blob/camp4/docs/L1/InternIntro/tasks.md) | [colearn.intern-ai.org.cn](https://colearn.intern-ai.org.cn/set?s=bzoc) | [B station](https://www.bilibili.com/video/BV1ExDQYyEAA)
- **浦语提示词工程实践** - [github.com](https://github.com/InternLM/Tutorial/blob/camp4/docs/L1/Prompt) | [github.com](https://github.com/InternLM/Tutorial/blob/camp4/docs/L1/Prompt/tasks.md) | [colearn.intern-ai.org.cn](https://colearn.intern-ai.org.cn/set?s=bzprompt) | [studio.intern-ai.org.cn](https://studio.intern-ai.org.cn/) | [B station](https://www.bilibili.com/video/BV1tjS7YfEWJ)
- **浦语+LlamaIndex 外挂知识库 RAG 实践** - [github.com](https://github.com/InternLM/Tutorial/blob/camp4/docs/L1/LlamaIndex/readme_api.md) | [github.com](https://github.com/InternLM/Tutorial/blob/camp4/docs/L1/LlamaIndex/task.md) | [colearn.intern-ai.org.cn](https://colearn.intern-ai.org.cn/set?s=bzxtuner) | [studio.intern-ai.org.cn](https://studio.intern-ai.org.cn/) | [B station](https://www.bilibili.com/video/BV1YzDJY1E2i)
- **XTuner 微调 InternLM 个人小助手认知实践** - [github.com](https://github.com/InternLM/Tutorial/blob/camp4/docs/L1/XTuner) | [github.com](https://github.com/InternLM/Tutorial/blob/camp4/docs/L1/XTuner/task.md) | [colearn.intern-ai.org.cn](https://colearn.intern-ai.org.cn/set?s=bzxtuner) | [studio.intern-ai.org.cn](https://studio.intern-ai.org.cn/) | [B station](https://www.bilibili.com/video/BV1G9SJYGEtD)
- **OpenCompass 评测书生大模型实践** - [github.com](https://github.com/InternLM/Tutorial/blob/camp4/docs/L1/Evaluation) | [github.com](https://github.com/InternLM/Tutorial/blob/camp4/docs/L1/Evaluation/task.md) | [colearn.intern-ai.org.cn](https://colearn.intern-ai.org.cn/set?s=bzoc) | [studio.intern-ai.org.cn](https://studio.intern-ai.org.cn/) | [B station](https://www.bilibili.com/video/BV1dtD4YKENj)
- **Lagent 从零搭建你的 Multi-Agent (书生·浦语 API 版)** - [github.com](https://github.com/InternLM/Tutorial/blob/camp4/docs/L2/Agent) | [github.com](https://github.com/InternLM/Tutorial/blob/camp4/docs/L2/Agent/task.md) | [colearn.intern-ai.org.cn](https://colearn.intern-ai.org.cn/set?s=bzlagent) | [studio.intern-ai.org.cn](https://studio.intern-ai.org.cn/) | [B station](https://www.bilibili.com/video/BV19RzcYaEFy)
- **LMDeploy 量化部署进阶实践** - [github.com](https://github.com/InternLM/Tutorial/blob/camp4/docs/L2/LMDeploy) | [github.com](https://github.com/InternLM/Tutorial/blob/camp4/docs/L2/LMDeploy/task.md) | [colearn.intern-ai.org.cn](https://colearn.intern-ai.org.cn/set?s=bz_lmdeploy) | [studio.intern-ai.org.cn](https://studio.intern-ai.org.cn/) | [B station](https://www.bilibili.com/video/BV18aUHY3EEG)
- **多模态大模型发展简述及其微调部署实践(InternVL2为例)** - [github.com](https://github.com/InternLM/Tutorial/blob/camp4/docs/L2/InternVL) | [github.com](https://github.com/InternLM/Tutorial/blob/camp4/docs/L2/InternVL/task.md) | [colearn.intern-ai.org.cn](https://colearn.intern-ai.org.cn/set?s=bzinternvl) | [studio.intern-ai.org.cn](https://studio.intern-ai.org.cn/) | [B station](https://www.bilibili.com/video/BV1nESCYWEnN)
- **InternLM+WasmEdge 部署智能体实践** - [B station](https://www.bilibili.com/video/BV1K2rAYeEXG)
- **EgoExolearn跨视角技能学习数据集** - [B station](https://www.bilibili.com/video/BV1pT42167pQ)
- **单阶段多维度模型搜索范式** - [B station](https://www.bilibili.com/video/BV1Yb421J7wA)
- **MVBench 多模态视频评测体系** - [B station](https://www.bilibili.com/video/BV1ZE4m1R7Tc)
- **人机协作的视觉生成** - [B station](https://www.bilibili.com/video/BV1fZ421N7re)
- **个性化图像动画生成器，利用文本提示将图像变为奇妙的动画** - [arXiv:2312.13964](https://arxiv.org/abs/2312.13964) | [arxiv.org](https://arxiv.org/abs/2312.13964) | [github.com](https://github.com/open-mmlab/PIA) | [openxlab.org.cn](https://openxlab.org.cn/apps/detail/zhangyiming/PiaPia/) | [B station](https://www.bilibili.com/video/BV1PE4m197ZM)
- **基于像素点的拖拽式图像编辑分享** - [arxiv.org](https://arxiv.org/html/2307.04684v3) | [github.com](https://github.com/LPengYang/FreeDrag) | [openxlab.org.cn](https://openxlab.org.cn/apps/detail/LPengYang/FreeDrag) | [B station](https://www.bilibili.com/video/BV1XH4y1c78r)
- **GenNBV：面向主动三维重建的可泛化最佳视角探索策略** - [arXiv:2402.16174](https://arxiv.org/abs/2402.16174) | [arxiv.org](https://arxiv.org/abs/2402.16174) | [github.com](https://github.com/zjwzcx/GenNBV) | [B station](https://www.bilibili.com/video/BV1yy411i7jh)
- **多模态大模型幻觉成因解释以及基于惩罚回退策略的幻觉缓解方法** - [arXiv:2311.17911](https://arxiv.org/abs/2311.17911) | [arxiv.org](https://arxiv.org/abs/2311.17911) | [github.com](https://github.com/shikiw/OPERA) | [B station](https://www.bilibili.com/video/BV1QH4y1c7p3)
- **中文常识推理基准-CHARM** - [arXiv:2403.14112](https://arxiv.org/abs/2403.14112) | [arxiv.org](https://arxiv.org/abs/2403.14112) | [github.com](https://github.com/opendatalab/CHARM) | [hub.opencompass.org.cn](https://hub.opencompass.org.cn/dataset-detail/CHARM) | [B station](https://www.bilibili.com/video/BV1QcmdYiExz)
- **分享 SALAD-BENCH 数据集与评估方法** - [arxiv.org](https://arxiv.org/pdf/2402.05044) | [github.com](https://github.com/OpenSafetyLab/SALAD-BENCH) | [hub.opencompass.org.cn](https://hub.opencompass.org.cn/dataset-detail/SALAD-Bench) | [B station](https://www.bilibili.com/video/BV1KimoYaExY)
- **评估大语言模型多轮对话能力的细粒度评测集** - [aclanthology.org](https://aclanthology.org/2024.acl-long.401/) | [github.com](https://github.com/mtbench101) | [hub.opencompass.org.cn](https://hub.opencompass.org.cn/dataset-detail/MT-Bench-101) | [B station](https://www.bilibili.com/video/BV1mvmoYAEAv)
- **ConvBench：多轮视觉对话评测基准与能力解耦评测方式** - [arXiv:2406.11833](https://arxiv.org/abs/2406.11833) | [arxiv.org](https://arxiv.org/abs/2406.11833) | [github.com](https://github.com/Liuziyu77/MMDU) | [hub.opencompass.org.cn](https://hub.opencompass.org.cn/dataset-detail/MMDU) | [B station](https://www.bilibili.com/video/BV1QbcRevE61)
- **GTA：大模型复杂任务工具调用能力评测** - [arXiv:2407.08713](https://arxiv.org/abs/2407.08713) | [arxiv.org](https://arxiv.org/abs/2407.08713) | [open-compass.github.io](https://open-compass.github.io/GTA) | [hub.opencompass.org.cn](https://hub.opencompass.org.cn/dataset-detail/GTA) | [B station](https://www.bilibili.com/video/BV1cucReJETD)
- **MMDU：高质量多图多轮对话数据集** - [arXiv:2406.11833](https://arxiv.org/abs/2406.11833) | [arxiv.org](https://arxiv.org/abs/2406.11833) | [github.com](https://github.com/Liuziyu77/MMDU) | [hub.opencompass.org.cn](https://hub.opencompass.org.cn/dataset-detail/MMDU) | [B station](https://www.bilibili.com/video/BV1HTcReDEhX)
- **MMLongBench-Doc：使用可视化对长上下文文档理解进行基准测试** - [arXiv:2407.01523](https://arxiv.org/abs/2407.01523) | [arxiv.org](https://arxiv.org/abs/2407.01523) | [github.com](https://github.com/mayubo2333/MMLongBench-Doc) | [hub.opencompass.org.cn](https://hub.opencompass.org.cn/dataset-detail/MMLongBench-Doc) | [B station](https://www.bilibili.com/video/BV19scReMEdS)
- **多模态推理的评测以及后训练** - [hub.opencompass.org.cn](https://hub.opencompass.org.cn/dataset-detail/MMIU) | [B station](https://www.bilibili.com/video/BV1C9XrYaEyz)
- **多模态动态评测（Oral）** - [B station](https://www.bilibili.com/video/BV1P9XrYYEje)
- **LOKI：基于多模态大模型的合成数据检测基准** - [hub.opencompass.org.cn](https://hub.opencompass.org.cn/dataset-detail/LOKI) | [B station](https://www.bilibili.com/video/BV1JJXrYdEXi)
- **Sim-CoT 驱动高效隐式思考** - [arxiv.org](https://arxiv.org/pdf/2509.20317) | [github.com](https://github.com/InternLM/SIM-CoT) | [B station](https://www.bilibili.com/video/BV1VGEC6fErh)
- **数据分布解读 RL 如何“学新不忘旧”** - [arxiv.org](https://arxiv.org/pdf/2506.23508) | [B station](https://www.bilibili.com/video/BV1afE16NEXf)
- **数据驱动的大模型长度泛化推理新范式** - [arXiv:2507.13332](https://arxiv.org/abs/2507.13332) | [arxiv.org](https://arxiv.org/abs/2507.13332) | [B station](https://www.bilibili.com/video/BV1H2TF64Ek9)
- **利用智能体解锁地球观测的完整图景** - [arXiv:2509.23141](https://arxiv.org/abs/2509.23141) | [arxiv.org](https://arxiv.org/abs/2509.23141) | [opendatalab.github.io](https://opendatalab.github.io/Earth-Agent/) | [B station](https://www.bilibili.com/video/BV1LUTj6FE9N)
- **冗余性解耦的高效长文本偏好优化** - [openreview.net](https://openreview.net/pdf?id=iiBjaiikJG) | [github.com](https://github.com/shs910/SoLoPO) | [B station](https://www.bilibili.com/video/BV12uTQ6CEHz)
- **AI科研加速营第1课｜用AI快速看懂一个研究方向** - [sensorsdata.intern-ai.org.cn](https://sensorsdata.intern-ai.org.cn/t/ca) | [B station](https://www.bilibili.com/video/BV1jMY163EWE)
- **AI科研加速营第2课｜AI论文工作流：检索、精读与核验** - [sensorsdata.intern-ai.org.cn](https://sensorsdata.intern-ai.org.cn/t/ca) | [B station](https://www.bilibili.com/video/BV1tTen6ZEmy)
- **AI科研加速营第3课｜建立可持续更新的研究上下文** - [sensorsdata.intern-ai.org.cn](https://sensorsdata.intern-ai.org.cn/t/ca) | [B station](https://www.bilibili.com/video/BV11zec6NE3k)
- **AI科研加速营第4课｜AI辅助实验设计：科学数据与计算一体化实践** - [sensorsdata.intern-ai.org.cn](https://sensorsdata.intern-ai.org.cn/t/ca) | [B station](https://www.bilibili.com/video/BV1FTeG6dEQ4)
- **AI科研加速营第5课｜AI辅助论文与课题申请书写作** - [sensorsdata.intern-ai.org.cn](https://sensorsdata.intern-ai.org.cn/t/ca) | [B station](https://www.bilibili.com/video/BV1xLe16bE2p)
- **AI科研加速营第6课｜把科研方法沉淀为可复用的Agent Skill** - [sensorsdata.intern-ai.org.cn](https://sensorsdata.intern-ai.org.cn/t/ca) | [B station](https://www.bilibili.com/video/BV1TZem6BEQP)
- **AI科研加速营第7课｜通往可扩展、统一的蛋白基础模型之路** - [sensorsdata.intern-ai.org.cn](https://sensorsdata.intern-ai.org.cn/t/ca) | [B station](https://www.bilibili.com/video/BV1sHem6AEXD)
- **AI科研加速营第8课｜大模型时代的物质科学研究** - [sensorsdata.intern-ai.org.cn](https://sensorsdata.intern-ai.org.cn/t/ca) | [B station](https://www.bilibili.com/video/BV1Vfhv6BEXx)
- **AI科研加速营第9课｜地球科学中的科学智能：从工具的革命到革命的工具** - [sensorsdata.intern-ai.org.cn](https://sensorsdata.intern-ai.org.cn/t/ca) | [B station](https://www.bilibili.com/video/BV16RhE6TEmM)
- **OpenMMLab 环境配置 （一） Windows 11 CPU** - [mmsig.openmmlab.com](https://mmsig.openmmlab.com/general/env/win11) | [B station](https://www.bilibili.com/video/BV1Bh41157gL)
- **通用、统一且灵活的开源算法平台 OpenMMLab 2.0 | CVPR 2023 （全英分享）** - [github.com](https://github.com/open-mmlab) | [B station](https://www.bilibili.com/video/BV1Zg4y1P7LB)
- **视觉基础模型的探索：MMPreTrain | CVPR 2023 (全英分享)** - [github.com](https://github.com/open-mmlab/mmpretrain) | [B station](https://www.bilibili.com/video/BV11s4y1C7S9)
- **通用目标检测工具 MMDetection3.0 | CVPR 2023 （全英分享）** - [github.com](https://github.com/open-mmlab/mmdetection) | [B station](https://www.bilibili.com/video/BV1214y1274j)
- **图像与视频生成、编辑和增强工具 MMagic | CVPR 2023 （全英分享）** - [github.com](https://github.com/open-mmlab/mmagic) | [B station](https://www.bilibili.com/video/BV1nX4y1q7DF)
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
- **书生·浦语大模型全链路开源体系** - [github.com](https://github.com/InternLM/InternLM/) | [wjx.cn](https://www.wjx.cn/vm/tUX8dEV.aspx?udsid=240962) | [B station](https://www.bilibili.com/video/BV1Vx421X72D)
- **轻松玩转书生·浦语大模型趣味 Demo** - [github.com](https://github.com/InternLM/Tutorial/blob/camp2/helloworld/hello_world.md) | [wjx.cn](https://www.wjx.cn/vm/tUX8dEV.aspx?udsid=240962) | [github.com](https://github.com/InternLM/InternLM) | [B station](https://www.bilibili.com/video/BV1AH4y1H78d)
- **茴香豆：搭建你的 RAG 智能助理** - [github.com](https://github.com/InternLM/Tutorial/blob/camp2/huixiangdou/readme.md) | [wjx.cn](https://www.wjx.cn/vm/tUX8dEV.aspx?udsid=240962) | [github.com](https://github.com/InternLM/HuixiangDou) | [B station](https://www.bilibili.com/video/BV1QA4m1F7t4)
- **XTuner 微调 LLM：1.8B、多模态、Agent** - [github.com](https://github.com/InternLM/Tutorial/blob/camp2/xtuner/readme.md) | [github.com](https://github.com/InternLM/Tutorial/blob/camp2/xtuner/homework.md) | [github.com](https://github.com/InternLM/XTuner) | [wjx.cn](https://www.wjx.cn/vm/tUX8dEV.aspx?udsid=240962) | [B station](https://www.bilibili.com/video/BV15m421j78d)
- **LMDeploy 量化部署 LLM-VLM 实践** - [github.com](https://github.com/InternLM/Tutorial/blob/camp2/lmdeploy/README.md) | [github.com](https://github.com/InternLM/Tutorial/blob/camp2/lmdeploy/homework.md) | [github.com](https://github.com/InternLM/LMDeploy) | [wjx.cn](https://www.wjx.cn/vm/tUX8dEV.aspx?udsid=240962) | [B station](https://www.bilibili.com/video/BV1tr421x75B)
- **Lagent & AgentLego 智能体应用搭建** - [github.com](https://github.com/InternLM/Tutorial/tree/camp2/agent) | [github.com](https://github.com/InternLM/Tutorial/blob/camp2/agent/homework.md) | [github.com](https://github.com/InternLM/Lagent) | [github.com](https://github.com/InternLM/AgentLego) | [B station](https://www.bilibili.com/video/BV1Xt4217728)
- **OpenCompass 大模型评测实战** - [github.com](https://github.com/InternLM/Tutorial/blob/camp2/opencompass/readme.md) | [github.com](https://github.com/InternLM/Tutorial/blob/camp2/opencompass/homework.md) | [github.com](https://github.com/open-compass/opencompass) | [wjx.cn](https://www.wjx.cn/vm/tUX8dEV.aspx?udsid=240962) | [B station](https://www.bilibili.com/video/BV1Pm41127jU)
- **大模型微调数据构造（补充课程）** - [B station](https://www.bilibili.com/video/BV1Dx4y1z7Ju)
- **多模态简述** - [B station](https://www.bilibili.com/video/BV12E421A76T)
- **LMDeploy 量化部署 InternVL 浦语灵笔实践** - [github.com](https://github.com/InternLM/Tutorial/tree/camp2/lmdeploy_vlm) | [B station](https://www.bilibili.com/video/BV11m421373q)
- **XTuner 微调 LLaVA 实践** - [github.com](https://github.com/InternLM/Tutorial/blob/camp2/xtuner/llava/xtuner_llava.md) | [B station](https://www.bilibili.com/video/BV1vZ421M7ig)
- **AI实战营第二期 开营仪式** - [B station](https://www.bilibili.com/video/BV1sc411V74M)
- **Github八万star，开源计算机视觉神器OpenMMLab** - [openmmlab.com](https://openmmlab.com) | [github.com](https://github.com/open-mmlab) | [B station](https://www.bilibili.com/video/BV1js4y1i72P)
- **深度学习预训练与MMPretrain** - [B station](https://www.bilibili.com/video/BV1PN411y7C1)
- **目标检测与MMDetection** - [B station](https://www.bilibili.com/video/BV1Ak4y1p7W9)
- **MMDetection代码课** - [B station](https://www.bilibili.com/video/BV1Tm4y1q7fy)
- **语义分割与MMSegmentation** - [github.com](https://github.com/open-mmlab/mmsegmentation) | [github.com](https://github.com/TommyZihao/MMSegmentation_Tutorials) | [B station](https://www.bilibili.com/video/BV1gV4y1m74P)
- **玩转AIGC神器MMagic** - [github.com](https://github.com/open-mmlab/mmagic) | [github.com](https://github.com/TommyZihao/MMagic_Tutorials) | [B station](https://www.bilibili.com/video/BV1gM4y1n7vP)
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
- **基于 SiliconCloud 平台使用 MindSearch** - [github.com](https://github.com/InternLM/mindsearch) | [mindsearch.netlify.app](https://mindsearch.netlify.app/) | [cloud.siliconflow.cn](https://cloud.siliconflow.cn/playground/chat) | [B station](https://www.bilibili.com/video/BV163sxeZEPi)
- **AI 实战营开营仪式** - [B station](https://www.bilibili.com/video/BV1o3411X7MB)
- **1 计算机视觉算法基础与OpenMMLab介绍** - [B station](https://www.bilibili.com/video/BV1Ty4y1X7X1)
- **2 计算机视觉之图像分类算法基础** - [B station](https://www.bilibili.com/video/BV1js4y1W7CN)
- **3 图像分类代码实战与超算平台介绍** - [B station](https://www.bilibili.com/video/BV1MA411k7NT)
- **4 目标检测算法基础** - [B station](https://www.bilibili.com/video/BV1Ay4y1Q7mC)
- **5 MMDetection 代码教学** - [B station](https://www.bilibili.com/video/BV1Av4y1475i)
- **6 语义分割算法基础** - [B station](https://www.bilibili.com/video/BV1s24y1W7Xa)
- **7 MMSegmentation 代码教学** - [B station](https://www.bilibili.com/video/BV1eT411R7Jq)
- **AI实战营 结营仪式** - [B station](https://www.bilibili.com/video/BV1ge4y1c7tY)
- **书生·浦语大模型全链路开源体系** - [github.com](https://github.com/internLM/tutorial) | [B station](https://www.bilibili.com/video/BV1Rc411b7ns)
- **轻松玩转书生·浦语大模型趣味Demo** - [github.com](https://github.com/InternLM/tutorial/blob/main/helloworld/hello_world.md) | [B station](https://www.bilibili.com/video/BV1Ci4y1z72H)
- **基于 InternLM 和 LangChain 搭建你的知识库** - [github.com](https://github.com/InternLM/tutorial/tree/main/langchain) | [B station](https://www.bilibili.com/video/BV1sT4y1p71V)
- **XTuner 大模型单卡低成本微调实战** - [github.com](https://github.com/InternLM/tutorial/blob/main/xtuner/README.md) | [github.com](https://github.com/internLM/xtuner) | [B station](https://www.bilibili.com/video/BV1yK4y1B75J)
- **XTuner 大模型低成本微调作业讲解——个人小助手认知微调实践** - [github.com](https://github.com/InternLM/tutorial/blob/main/xtuner/self.md) | [B station](https://www.bilibili.com/video/BV13t4y1o75X)
- **LMDeploy 大模型量化部署实践** - [github.com](https://github.com/InternLM/tutorial/blob/main/lmdeploy/lmdeploy.md) | [github.com](https://github.com/internLM/lmdeploy) | [B station](https://www.bilibili.com/video/BV1iW4y1A77P)
- **OpenCompass 大模型评测** - [github.com](https://github.com/InternLM/tutorial/blob/main/opencompass/opencompass_tutorial.md) | [github.com](https://github.com/open-compass/opencompass) | [B station](https://www.bilibili.com/video/BV1Gg4y1U7uc)
- **[数学基础与PyTorch] 01 从变分推断到 FKL/RKL 的讨论，到 ELBO/VAE，以及知识蒸馏（FKL）** - [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/math/calculus/variational_inferenc_rkl_vae.ipynb) | [B station](https://www.bilibili.com/video/BV1MZkxBZEPv)
- **[数学基础与PyTorch] 02 梯度的视角回顾 Pretrain 和 SFT 的 Cross Entropy Loss，LLM如何更新 token emb** - [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/math/pytorch/cross-entropy-loss-gradient-descent.ipynb) | [B station](https://www.bilibili.com/video/BV1YN5d67ETR)
- **[数学基础与PyTorch] 03 回顾策略梯度，score function trick，蒙特卡洛采样，pytorch 优化与重要性采样** - [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/math/pytorch/pg-score-function.ipynb) | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/math/pytorch/score-reparameterization.ipynb) | [B station](https://www.bilibili.com/video/BV1VFVV6ZENF)
- **[数学基础与PyTorch] 04 策略梯度score function trick 与 VAE 重参数化 trick** - [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/math/pytorch/score-reparameterization.ipynb) | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/math/pytorch/pg-score-function.ipynb) | [B station](https://www.bilibili.com/video/BV1CCVU65EqD)
- **[数学基础与PyTorch] 05 OPD-01 RKL/FKL, TopK, 为什么可以复用RL infra，seq level KL，verl/slime** - [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agentic_rl/distillation/opd-01.ipynb) | [B station](https://www.bilibili.com/video/BV1WpGu6aEKo)
- **[数学基础与PyTorch] 06 理解高维Tensor，手撕 MHA 为什么先 reshape 再 permute？view/stride/contiguou** - [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/math/pytorch/basics/tensor-shape-axis-processing.ipynb) | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/math/pytorch/basics/vit-attention.ipynb) | [B station](https://www.bilibili.com/video/BV1RphN6DEeQ)
- **[数学基础与PyTorch] 07 MHA 的 QKVO 四重投影，为什么少不了 W_O？concat 再乘 ≡ 逐 head 求和 | OV 电路 rank** - [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/llms/%E6%9E%B6%E6%9E%84/kimi/attentions.ipynb) | [B station](https://www.bilibili.com/video/BV1ZktH6cESE)
- **[数学基础与PyTorch] 08 Jev 决策模型与概率校准，ECE 计算，RL之后LLM过度自信** - [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/llms/%E6%9E%B6%E6%9E%84/jev/calibration.ipynb) | [aclanthology.org](https://aclanthology.org/2023.emnlp-main.330.pdf) | [arxiv.org](https://arxiv.org/pdf/2507.16806) | [arxiv.org](https://arxiv.org/pdf/2504.13837) | [B station](https://www.bilibili.com/video/BV1y1pJ6XEc5)
- **[A100 Training] 01 熟悉一台A100 SXM GPU计算节点，必要基础配置，SXM/PCIe/HGX，CPU与GPU带宽及内存带宽测试** - [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agentic_rl/training_projs/%E5%BD%93%E6%8B%BF%E5%88%B0%E4%B8%80%E4%B8%AAA100%E7%9A%84%E8%8A%82%E7%82%B9.ipynb) | [github.com](https://github.com/wdkns/modern_genai_bilibili/tree/main/agentic_rl/training_projs/scripts) | [B station](https://www.bilibili.com/video/BV1CGN26EEeT)
- **[A100 Training] 02 verl/slime 框架及训练任务介绍，插拔式设计，Qwen3.5全家桶，InfiGUI，thinking mode** - [github.com](https://github.com/wdkns/modern_genai_bilibili/tree/main/agentic_rl/training_projs) | [B station](https://www.bilibili.com/video/BV1xJKB6vEzh)
- **[A100 Training] 03 verl/slime 一些实际的训练经验，踩过的坑，wandb，GDN，remove pad，精度，clip_ratio** - [github.com](https://github.com/wdkns/modern_genai_bilibili/tree/main/agentic_rl/training_projs) | [B station](https://www.bilibili.com/video/BV1MTKp6bEn4)
- **[A100 Training] 04 verl/slime Docker 容器 debug，断点调试，源码细读，ray 分布式 debug** - [github.com](https://github.com/wdkns/modern_genai_bilibili/tree/main/agentic_rl/training_projs) | [B station](https://www.bilibili.com/video/BV19Qgy6rE32)
- **[Pro6000 Training] 05 8卡Pro 6000 硬件概览，感知硬件，理解拓扑，NUMA | 一切都关乎通信带宽** - [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/slides/pro6000-%E7%A1%AC%E4%BB%B6%E5%85%A8%E8%A7%A3-%E5%85%AC%E5%BC%80%E7%89%88.pdf) | [B station](https://www.bilibili.com/video/BV1EjeA6ZEi9)
- **[Pro 6000 Training] 06 8卡 RTX PRO 6000 原生 FP4 装下 GLM-5.3：NVFP4、E2M1、KV cache 与并发** - [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agentic_rl/training_projs/pro6000/platform-2-supp.ipynb) | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/slides/pro6000-%E7%A1%AC%E4%BB%B6%E5%85%A8%E8%A7%A3-%E5%85%AC%E5%BC%80%E7%89%88.pdf) | [B station](https://www.bilibili.com/video/BV1vfHC6MEk3)
- **[LLM Architect] 01 MoE 初步，参数量计算，Qwen3-30B-A3B，GQA 与 Sparse MoE** - [B station](https://www.bilibili.com/video/BV1P5nfz6Eto)
- **[LLM Architect] 02 Qwen3 Dense vs. MoE，MoE 等效宽度，attention vs. ffn，RMSNorm** - [B station](https://www.bilibili.com/video/BV1ty4TzSEpg)
- **[Reasoning Model] K2 Thinking，理解 Interleaved thinking 交错推理，定义和处理 Turn** - [B station](https://www.bilibili.com/video/BV1AMCdBqEe1)
- **[kimi] muon optimizer 基本原理，梯度白化（正交化），zeropower，newtonschulz5，，svd，范数** - [github.com](https://github.com/chunhuizhang/llm_rl/blob/main/tutorials/k2/muon_basics.ipynb) | [B station](https://www.bilibili.com/video/BV18sgtzKEVQ)
- **[LLM Architect] 04 RoPE 理解的几何视角，Qwen3 RoPE 计算细节，与 Interleaved 版本的对比** - [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/llms/%E6%9E%B6%E6%9E%84/pe/RoPE-geometric.ipynb) | [B station](https://www.bilibili.com/video/BV1cv2XBAEsA)
- **[LLM Architect] 05 RoPE Attention 远程衰减理解与推导，如何同时编码短距离和长距离，Base 与 Context Window** - [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/llms/%E6%9E%B6%E6%9E%84/pe/RoPE%20%E8%A1%A5%E5%85%85.ipynb) | [B station](https://www.bilibili.com/video/BV1qVmYBzE2d)
- **[LLM Architect] 06 Attention Head 典型模式识别与分析，Attention Sink、PTH、Induction Head** - [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/llms/%E6%9E%B6%E6%9E%84/attention/attention_pattern.ipynb) | [B station](https://www.bilibili.com/video/BV16xB6B3EVi)
- **[LLM Architect] 07 VLM 多模态模型架构设计，对比 Gemini Qwen3-VL 与 Kimi K2.5，如何理解原生多模态** - [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/llms/%E5%A4%9A%E6%A8%A1%E6%80%81/%E5%8E%9F%E7%94%9F%E5%A4%9A%E6%A8%A1%E6%80%81.ipynb) | [B station](https://www.bilibili.com/video/BV1jJfDBUEcR)
- **[LLM Architect] 08 Dive into K2.5，Kimi K2.5 论文串讲与导读，原生多模态，Agent Swarm，国产之光** - [arXiv:2602.02276](https://arxiv.org/abs/2602.02276) | [arxiv.org](https://arxiv.org/abs/2602.02276) | [B station](https://www.bilibili.com/video/BV1nvcuz5Ewj)
- **[LLM Architect] 09 深入理解和对比 prefill与decode | kv-cache | 并行-串行 | GEMM-GEMV | 算力-带宽** - [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/llms/%E6%9E%B6%E6%9E%84/prefill-decode.ipynb) | [B station](https://www.bilibili.com/video/BV1APAuzpEHY)
- **[LLM Architect] 10 为什么LLM无法理解输出马嘉祺，深入理解Glitch（故障）Token，词嵌入漂移、SFT/RL、gradient 视角** - [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/llms/%E6%9E%B6%E6%9E%84/tokenizers/special_Glitch_tokens.ipynb) | [B station](https://www.bilibili.com/video/BV1qZRZBcEiH)
- **[LLM Architect] 11 探测解码分布一致性推导，MTP 拓扑结构，训练与self speculative decoding** - [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agentic_rl/infra/%E6%8E%A2%E6%B5%8B%E8%A7%A3%E7%A0%81-MTP.ipynb) | [B station](https://www.bilibili.com/video/BV1naJp6EEey)
- **[LLM Architect] 12 Kimi K3 架构初步，张量计算视角，KDA，MLA，Latent MoE，MoonViT 与残差注意力** - [arXiv:2607.24653](https://arxiv.org/abs/2607.24653) | [arxiv.org](https://arxiv.org/abs/2607.24653) | [github.com](https://github.com/wdkns/wdkns-skills/tree/main/demos/kimi-k3-tensor) | [github.com](https://github.com/wdkns/wdkns-skills/tree/main/skills/tensor-formula-viz) | [B station](https://www.bilibili.com/video/BV1VpMB6nEvH)
- **[LLM Architect] 13 Kimi K3 门控机制，门控注意力，Gated MLA，KDA的门控分支，MoE 中的SiTU-GLU，SwiGLU** - [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/llms/%E6%9E%B6%E6%9E%84/kimi/activations.ipynb) | [B station](https://www.bilibili.com/video/BV1UNur6pEkZ)
- **[LLM Architect] 14 DeepSeek V4.1 Causal Encoder Decoder， yoco 对比与 kvcache** - [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/llms/%E6%9E%B6%E6%9E%84/dpsk/v4.1/ced.ipynb) | [github.com](https://github.com/wdkns/modern_genai_bilibili/tree/main/slides) | [B station](https://www.bilibili.com/video/BV1ceYX6iE4P)
- **[LLM Architect] 15 Jev 架构推测，Tree Mask 隔离复用与并行计算，概率与confidence，RLCD/RLCR** - [archerhume.com](https://archerhume.com/posts/jevs-architecture-unmasked/) | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/slides/jev_architecture-v2.pdf) | [B station](https://www.bilibili.com/video/BV1Mihq6AEbc)
- **[Agentic Infra] [Ray] 01 ray task与ray actor基础（Ray remote），分布式任务调度，并发控制，多进程多线程与协程** - [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agentic_rl/verl/ray/ray_remote_get.ipynb) | [B station](https://www.bilibili.com/video/BV1HuZcBEEyy)
- **[Agentic Infra]  02 RL post-training 训练框架，训练流程参数分析与指标监控，显存分配与性能调优** - [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agentic_rl/verl/verl-algos-metrics.ipynb) | [B station](https://www.bilibili.com/video/BV1z6Mu6LE7i)
- **[Agentic Infra] 03 算力密度与Roofline model，对比 5090/M5 max/DGX spark，Qwen3-8B 算力与访存** - [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agentic_rl/infra/%E6%98%BE%E5%AD%98-%E7%AE%97%E5%8A%9B-M%E8%8A%AF%E7%89%87.ipynb) | [B station](https://www.bilibili.com/video/BV1rRYM65ENj)
- **[Modern Agent] 01 Survey of LLM Agent Reasoning & Planning, PDDL，一些 know how** - [github.com](https://github.com/chunhuizhang/modern_genai_bilibili/blob/main/agents/Modern%20Agents.pptx) | [B station](https://www.bilibili.com/video/BV1wjY5zyEki)
- **[Modern Agent] 02 langchain/langgraph 在实现 ReAct 的差异，langsmith 监控的小 tips** - [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agents/langchain-graph/react_langchain_langgraph.ipynb) | [B station](https://www.bilibili.com/video/BV1n4n7znEDN)
- **[Modern Agent] 03 Planning Agent，Plan-Execute-RePlan 一个泛化性强的实用 Agentic Workflow** - [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agents/Modern%20Agents.pptx) | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agents/langchain-graph/plan-and-execute/plan-and-execute.ipynb) | [B station](https://www.bilibili.com/video/BV1qa43z5EBJ)
- **[AI Agent] llama_index RAG 原理及源码分析** - [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/rag/llama_index_basics.ipynb) | [B station](https://www.bilibili.com/video/BV1Vm42157PL)
- **[LangGraph] 实现 Building Effective Agents，各种 workflows 及 Agent** - [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/agents/langchain/advanced/building_effective_agents.ipynb) | [B station](https://www.bilibili.com/video/BV1ZsM2zcEFa)
- **[Agent Works] Gemini 2.5 Pro + Agent = IMO 金牌，actor-critic，生成 -> 验证 -> 修正 迭代循环** - [github.com](https://github.com/lyang36/IMO25.git) | [github.com](https://github.com/chunhuizhang/prompts_for_academic/blob/main/math/scripts/imo-gemini-sdk.py) | [B station](https://www.bilibili.com/video/BV1Aq8bz1Emj)
- **[Modern Agent] 04 结构化输出与工具调用，langchain | openai api | http 抓包分析** - [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agents/langchain-graph/utils-features/structured_output.ipynb) | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agents/langchain-graph/utils-features/scripts/test_structure_outputs.py) | [B station](https://www.bilibili.com/video/BV1uiUnBFED4)
- **[Modern Agent] 05 LightRAG 知识图谱 based 的双层检索 与 LangFuse（API 监控 prompt 输入输出）** - [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agents/rag/lightrag/lightrag.ipynb) | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agents/tools/langfuse.ipynb) | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agents/rag/lightrag/scripts/lightrag_demo.py) | [B station](https://www.bilibili.com/video/BV1TkmqBKEid)
- **[Modern Agent] 07 SAM3 与 VLM，检测/识别/分割，Gemini 原生分割能力，Visual Prompting/Grounding** - [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/llms/%E5%A4%9A%E6%A8%A1%E6%80%81/cv/sam3-gemini.ipynb) | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/llms/%E5%A4%9A%E6%A8%A1%E6%80%81/cv/scripts/sam_agent.py) | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/llms/%E5%A4%9A%E6%A8%A1%E6%80%81/cv/seg_utils.py) | [developers.googleblog.com](https://developers.googleblog.com/en/conversational-image-segmentation-gemini-2-5/) | [B station](https://www.bilibili.com/video/BV1yyqqBBEqB)
- **[Modern Agent] 08 LightRAG 进阶，why KG-based RAG，文档 graph 如何合并，可视化 KG，Hybrid、Mix检索** - [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agents/rag/lightrag/lightrag-advanced.ipynb) | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agents/rag/lightrag/scripts/lightrag_complex_demo.py) | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agents/rag/lightrag/scripts/viz_graph.py) | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agents/rag/lightrag/scripts/merge.py) | [B station](https://www.bilibili.com/video/BV1Fuq2BWELU)
- **[Modern Agent] 09 Gemini Agentic Vision，如何理解模型基础能力与 Post-Training，Gemini 3 Flash** - [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agents/apis/gemini/gemini-vision.ipynb) | [B station](https://www.bilibili.com/video/BV1nU6yBfEqE)
- **[Modern Agent] 10 多模态VLM Visual Prompting，SAM 1/2/3, Grounding DINO, Set of Mark** - [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agents/multi-modality/visual-prompting.ipynb) | [B station](https://www.bilibili.com/video/BV1ebPhzBEdc)
- **[Modern Agent] 11  Codex 初步，系统提示词注入，会话历史管理，Context Engineering，Skills / MCP 位置** - [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agents/context-engineering/context-engineering-codex.ipynb) | [B station](https://www.bilibili.com/video/BV1fyNKz5Egb)
- **[Modern Agent] 12 Codex 中的 Skills 与 Tools 加载，Context Engineering，agent runtime** - [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agents/context-engineering/tool-schema-codex.ipynb) | [B station](https://www.bilibili.com/video/BV1bSwpzNEWE)
- **[Modern Agent] 13 Superpowers Skills，Vibe Coding 时代的软件开发圣经** - [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agents/mcp-skills/skills/superpowers.ipynb) | [B station](https://www.bilibili.com/video/BV1xswKz7EDh)
- **[Modern Agent] 14 Codex 中的上下文压缩 compact 与 handoff | openai compact 接口提示词破解** - [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agents/context-engineering/compact/compact-codex.ipynb) | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agents/context-engineering/compact/script.py) | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agents/context-engineering/compact/results.txt) | [x.com](https://x.com/kangwook_lee/status/2028955292025962534?s=46) | [B station](https://www.bilibili.com/video/BV1eMAGzjEhg)
- **[Modern Agent] 15 Codex 通用工具设计，subagents，apply_patch，exec_command，agentic vision** - [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agents/context-engineering/general_tool_design.ipynb) | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agents/context-engineering/files/test_response_create_6335.json) | [B station](https://www.bilibili.com/video/BV1QUXGBXER9)
- **[Modern Agent] 16 Claude Code 记忆（Memory）系统设计，记忆语义分类，记忆召回，记忆写入、更新与维护** - [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agents/context-engineering/memory-claude-code.ipynb) | [B station](https://www.bilibili.com/video/BV1ZA93BtEKW)
- **[Modern Agent] 17 Codex 中的 Plan Mode 与 update_plan，plan dynamics：创建、状态更新与replan** - [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agents/context-engineering/plan-codex.ipynb) | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agents/context-engineering/files/test_query_wire_request_6160.json) | [B station](https://www.bilibili.com/video/BV1NdDtBjEg7)
- **[Modern Agent] 18 何时如何保持思维链 CoT，interleaved thinking，kvcache 利用，Qwen3.6** - [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agents/apis/retain-cot.ipynb) | [B station](https://www.bilibili.com/video/BV1Ztb969ERR)
- **[智能的边界] gemini 2.5 deep think 初体验, parallel thinking 与 AlphaGeometry2** - [github.com](https://github.com/chunhuizhang/prompts_for_academic/blob/main/benchmark/0803_gemini_dp_test.ipynb) | [B station](https://www.bilibili.com/video/BV1uyhVzUEyT)
- **[实用的AI] paper-reading (system prompt) + gemini 2.5 pro + canvas + GEM** - [B station](https://www.bilibili.com/video/BV1FqebznEWU)
- **[实用的 AI] 科研绘图（teaser/poster），nano banana vs. GPT，nature/science 美学风格** - [github.com](https://github.com/chunhuizhang/prompts_for_academic/blob/main/leverage/%E7%A7%91%E7%A0%94%E7%BB%98%E5%9B%BE.ipynb) | [B station](https://www.bilibili.com/video/BV12dHvz7Eb8)
- **[实用 AI] Gemini 2.5 原生多模态能力，视频理解，tokens计算，youtube 视频整理成 blog** - [ai.google.dev](https://ai.google.dev/gemini-api/docs/video-understanding?hl=zh-cn) | [github.com](https://github.com/chunhuizhang/prompts_for_academic/blob/main/leverage/youtube.ipynb) | [B station](https://www.bilibili.com/video/BV1NoWszREy5)
- **[实用 AI] GPT/Gemini 全流程参与 idea 生成，实验设计，Paper writing | AI scientist | NotebookLM** - [B station](https://www.bilibili.com/video/BV1vPsZzAEbe)
- **[实用 AI] 基于 Nano 🍌 Pro + NotebookLM 做任意资源的视觉化呈现和理解，（漫画风格）PPT 与 信息图** - [github.com](https://github.com/chunhuizhang/prompts_for_academic/blob/main/leverage/nano-banana-gemini3.ipynb) | [B station](https://www.bilibili.com/video/BV1HUUTBCEnf)
- **[智能的边界] 性能-价格帕累托前沿上的 Gemini 模型家族，断层领先的 Gemini 3 flash，以及一些绘图技巧** - [blog.google](https://blog.google/products/gemini/gemini-3-flash/) | [B station](https://www.bilibili.com/video/BV1SnqQBnEcM)
- **[探索智能的边界] 喜迎 GPT Image 2，多图一致性，agentic search，thinking and generating** - [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agents/app/gpt-image2.ipynb) | [zhuanlan.zhihu.com](https://zhuanlan.zhihu.com/p/1975730596534830124) | [B station](https://www.bilibili.com/video/BV12NoMB3Esi)
- **[智能的边界] 深入 GPT Pro，通用工具设计（搜索与cli），沙盒系统硬件，skills，Python环境，UV，下载限制与 tex pdf 等** - [github.com](https://github.com/wdkns/wdkns-skills/blob/main/skills/youtube-render-pdf/assets/notes-template.tex) | [github.com](https://github.com/martinbjeldbak/ultimate-beamer-theme-list) | [B station](https://www.bilibili.com/video/BV14xEn6DEz8)
- **[M芯片与AI计算] 01 硬件视角下的 M5 内存带宽概念与计算，mactop，实际代码测试（MPS、Stream），魔改48GB版本4090** - [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/dev/environment/m5-max-benchmark/m5-max.ipynb) | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/dev/environment/m5-max-benchmark/scripts/mps-v1.py) | [B station](https://www.bilibili.com/video/BV1UUDDBJEn4)
- **[M芯片与AI计算] 02 Coding Agent 时代的 MacOS 装机配置与心流体验的获得，实用 CLI 工具，rg、yazi、fzf、uv** - [yanxingliu.github.io](https://yanxingliu.github.io/posts/2026/04/useful-cli-tools/) | [github.com](https://github.com/XuehaiPan/Dev-Setup) | [B station](https://www.bilibili.com/video/BV1SrLG6oEax)
- **[Agentic RL] 01 PG loss components，dual-clip，entropy，kl，如何自定义 pg loss** - [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agentic_rl/verl/objectives_loss.ipynb) | [B station](https://www.bilibili.com/video/BV1KFpczQEkA)
- **[Agentic RL] 02 策略梯度基础，从 PG 到 TRPO 到 PPO-Clip 核心公式简单推导** - [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agentic_rl/deep_RL/pg/from_pg_to_ppo-clip.ipynb) | [B station](https://www.bilibili.com/video/BV12NHJzTEoP)
- **[Agentic RL] 03 策略梯度补充，GRPO loss 分析，优势标准化，On Policy** - [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agentic_rl/deep_RL/pg/policy_gradient.ipynb) | [B station](https://www.bilibili.com/video/BV18hsFzbEKJ)
- **[Agentic RL] 04 REINFORCE 4 LLM，设计 reward，如何维护和计算 PG/KL loss，KL loss 计算细节** - [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agentic_rl/deep_RL/align/align_demo.ipynb) | [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agentic_rl/deep_RL/scripts/reinforce_align.py) | [B station](https://www.bilibili.com/video/BV1Ya1LB1EDM)
- **[Agentic RL] [Inference] 05 vllm 参数配置、显存分析与性能调优 max_num_batched_tokens** - [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agentic_rl/inference/vllm_sglang.ipynb) | [verl.readthedocs.io](https://verl.readthedocs.io/en/latest/perf/perf_tuning.html#rollout-generation-tuning) | [B station](https://www.bilibili.com/video/BV1QnSFBkEZU)
- **[Agentic RL] [RM] 06 DeepSeekMath-v2, 自我验证, verifier & meta verifier，验证&微调迭代** - [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agentic_rl/reasoning/math/deepseekmath-v2.ipynb) | [B station](https://www.bilibili.com/video/BV1AaSTBEEeS)
- **[Agentic RL] 07 limits of RLVR，base vs. RL, pass@k, ppl 基于 vLLM 计算细节以及采样效率** - [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agentic_rl/reasoning/rlvr.ipynb) | [B station](https://www.bilibili.com/video/BV1pWSvBtEAk)
- **[veRL] 从原理层面理解训练参数，PPO & GRPO，batch size，kl & entropy** - [github.com](https://github.com/chunhuizhang/llm_rl/blob/main/tutorials/infra/verl/verl_config_perf.ipynb) | [B station](https://www.bilibili.com/video/BV1DZL1zNEN2)
- **[veRL] 核心强化学习算法，GRPO、RLOO、REINFORCE++、REINFORCE++ baseline** - [github.com](https://github.com/chunhuizhang/llm_rl/blob/main/tutorials/objectives_adv/core_algo_adv.ipynb) | [B station](https://www.bilibili.com/video/BV1d4Yvz4EXA)
- **[veRL] FSDP SFT trainer，SFT vs. RL，交叉熵损失 | loss mask | learning rate scheduler** - [github.com](https://github.com/chunhuizhang/llm_rl/blob/main/tutorials/infra/verl/verl_sft.ipynb) | [B station](https://www.bilibili.com/video/BV1CkJgzAEAG)
- **[veRL] fsdp sft trainer 补充，teacher forcing、shift labels shift logits、loss mask** - [github.com](https://github.com/chunhuizhang/llm_rl/blob/main/tutorials/infra/verl/verl_sft_supp.ipynb) | [B station](https://www.bilibili.com/video/BV1eWjtzbEdP)
- **[Agentic RL] [VeRL] 08 MultiTurn Tool Use, Coding Agent SFT 训练，Cold Start for RL** - [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agentic_rl/verl/retool/ReTool-sft.ipynb) | [B station](https://www.bilibili.com/video/BV19PmwB5ERd)
- **[veRL] tokenizer 编解码的非对称性，RL 训练崩溃到 Agent loop 中的 token in token out** - [B station](https://www.bilibili.com/video/BV1b2pDzYEY2)
- **[Agentic RL] [RM] 09 Reward Model insights，理解概率建模（Bradley-Terry）、MLE、深度学习的关系** - [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agentic_rl/reward_model/Bradley-Terry-RM.ipynb) | [B station](https://www.bilibili.com/video/BV1z4vkBBEgD)
- **[Agentic RL] 10 分布的视角理解 LLM 的 SFT 训练和 RL 训练，Forward/Reverse KL，分布与奖励** - [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agentic_rl/sft_rl_fkl_rkl.ipynb) | [B station](https://www.bilibili.com/video/BV1WvrGBGEbf)
- **[Agentic RL] 11 重新理解 DPO，带 KL 正则的 RL 目标函数推导，隐式的奖励模型，DPO 可能的缺陷与不足** - [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agentic_rl/reward_model/dpo.ipynb) | [B station](https://www.bilibili.com/video/BV1N16ZBuERA)
- **[Agentic RL] 12 verl infra AgentLoop 基本概念及流程，AgentLoopManager，hybrid训练与推理** - [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agentic_rl/verl/agent/agent_loop_arch.ipynb) | [B station](https://www.bilibili.com/video/BV135zrBaEEU)
- **[Agentic RL] 13 verl infra AgentLoop 代码串讲，multi-turn 推理与 ray trainer** - [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agentic_rl/verl/agent/agent_loop_code.ipynb) | [B station](https://www.bilibili.com/video/BV1MizSBJEbi)
- **[Agentic RL] 14 verl AgentLoop 全流程与计算细节，async rollout 实现，状态机，tool / interaction** - [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agentic_rl/verl/agent/agent_loop_details.ipynb) | [B station](https://www.bilibili.com/video/BV18d6sBpEZq)
- **[Agentic RL] 15 基于 Docker 容器安装和开发 VeRL，Cursor/VSCode 远程连接 verl 容器，如同本地开发** - [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/dev/docker/%E6%8C%81%E4%B9%85%E5%8C%96%E5%BC%80%E5%8F%91-verl.ipynb) | [B station](https://www.bilibili.com/video/BV19jAzzREgW)
- **[Agentic RL] [Env] 16 Docker容器沙盒，Jupyter Kernel 创建有状态的 CI（代码解释器）环境，实现 SWE-Vision** - [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/agentic_rl/sandbox-env/swe-vision/swe-vision.ipynb) | [unipat.ai](https://unipat.ai/blog/SWE-Vision) | [B station](https://www.bilibili.com/video/BV15JdEBmEh9)
- **说说心里话 - 2024版（关于学习动力与方法，关于正反馈，关于 ai 协作）** - [B station](https://www.bilibili.com/video/BV1BFrFYMEsg)
- **[说说心里话] modern AI 入门 roadmap，RL4LLM** - [github.com](https://github.com/chunhuizhang/modern_ai_for_beginners) | [B station](https://www.bilibili.com/video/BV1PrQSYSExG)
- **[说说心里话] [2026-春] 人机协作的视角，AI 时代的学习指南与焦虑缓解** - [B station](https://www.bilibili.com/video/BV12nw4z6Eoa)
- **[小白向-深度学习装机指南] 01 双4090 涡轮版开箱启动 vlog（gpu burn，cpu burn）** - [B station](https://www.bilibili.com/video/BV1A54y1F7kN)
- **[装机指南] 02 双卡4090 gpu-burn，cpu-burn，cuda-samples 性能测试** - [github.com](https://github.com/chunhuizhang/deeplearning-envs/blob/main/01_gpuburn_cpuburn_cuda_samples.ipynb) | [B station](https://www.bilibili.com/video/BV1Kg4y1u7rZ)
- **[性能测试] 03 单 4090 BERT、GPT2、T5 TFLOPS 测试及对比 3090TI** - [github.com](https://github.com/chunhuizhang/deeplearning-envs/blob/main/02_single_4090_transformers.ipynb) | [B station](https://www.bilibili.com/video/BV1Mh41157Mc)
- **[性能测试] 04 双4090 BERT、GPT性能测试（megatron-lm、apex、deepspeed）** - [github.com](https://github.com/chunhuizhang/deeplearning-envs/blob/main/03_multi_4090s_transformers.ipynb) | [B station](https://www.bilibili.com/video/BV1u24y1K7jS)
- **[显卡环境] CUDA_VISIBLE_DEVICES 控制显卡可见性** - [github.com](https://github.com/chunhuizhang/deeplearning-envs/blob/main/cuda_visible_devices.ipynb) | [B station](https://www.bilibili.com/video/BV17z4y1s7eG)
- **[linux tools] tmux 分屏（终端复用器）** - [github.com](https://github.com/chunhuizhang/deeplearning-envs/blob/main/tmux.ipynb) | [B station](https://www.bilibili.com/video/BV1mu4y1B7Mp)
- **[显卡驱动] lspci 显卡是否在槽位，显卡基本信息** - [github.com](https://github.com/chunhuizhang/deeplearning-envs/blob/main/%E6%98%BE%E5%8D%A1%E5%AE%89%E8%A3%85%E4%B8%8E%E9%A9%B1%E5%8A%A8%E9%97%AE%E9%A2%98.ipynb) | [B station](https://www.bilibili.com/video/BV19Q4y1c7ia)
- **[A100 01] A100 服务器开箱，超微平台，gpu、cpu、内存、硬盘等信息查看** - [github.com](https://github.com/chunhuizhang/deeplearning-envs/blob/main/A100/A100_%E5%BC%80%E7%AE%B1.ipynb) | [B station](https://www.bilibili.com/video/BV1Yt42187NM)
- **[A100 02] GPU 服务器压力测试，gpu burn，cpu burn，cuda samples** - [github.com](https://github.com/chunhuizhang/deeplearning-envs/blob/main/A100/gpuburn_cpuburn_cuda_samples.ipynb) | [B station](https://www.bilibili.com/video/BV1wu4m1N7ET)
- **[工具使用] tmux 会话管理及会话持久性** - [github.com](https://github.com/chunhuizhang/deeplearning-envs/blob/main/tmux.ipynb) | [B station](https://www.bilibili.com/video/BV1AqHdekETT)
- **[AI硬件科普] 内存/显存带宽，从 NVIDIA 到苹果 M4** - [github.com](https://github.com/chunhuizhang/deeplearning-envs/blob/main/%E7%A1%AC%E4%BB%B6/%E5%86%85%E5%AD%98.ipynb) | [B station](https://www.bilibili.com/video/BV1Y9DAYwEvg)
- **[内网穿透] 穿透内网gpu服务器（jupyter lab 服务），namesilo、cloudflare 托管** - [github.com](https://github.com/chunhuizhang/full_stack/blob/main/tutorials/%E6%9C%8D%E5%8A%A1%E5%99%A8/%E5%9F%9F%E5%90%8D-%E5%85%AC%E7%BD%91ip-cloudflare.ipynb) | [B station](https://www.bilibili.com/video/BV1PYfpYdEPx)
- **[硬件扫盲] GPU 核心参数及对比，4090/5090/A100/H100 M4 Max 芯片，显存带宽、算力、卡间通信** - [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/dev/environment/%E7%A1%AC%E4%BB%B6%E6%8C%87%E5%8D%97/%E6%98%BE%E5%8D%A1%E6%A0%B8%E5%BF%83%E5%8F%82%E6%95%B0.ipynb) | [my.feishu.cn](https://my.feishu.cn/wiki/WgaPwKSczi8P6jkRmBncEXL7nBf?from=from_copylink) | [B station](https://www.bilibili.com/video/BV16Fr2BPEdo)
- **[硬件扫盲] GPU 核心参数及对比，为什么显存带宽决定了LLM推理，Pro 6000 及 PPT 算力** - [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/dev/environment/%E7%A1%AC%E4%BB%B6%E6%8C%87%E5%8D%97/%E6%98%BE%E5%8D%A1%E6%A0%B8%E5%BF%83%E5%8F%82%E6%95%B0.ipynb) | [my.feishu.cn](https://my.feishu.cn/wiki/WgaPwKSczi8P6jkRmBncEXL7nBf?from=from_copylink) | [B station](https://www.bilibili.com/video/BV1thrUBDEKE)
- **[硬件扫盲] 苹果 M5 pro/max 芯片，对比 Nvidia GPU，内存带宽，统一内存，tensor core，融合架构** - [github.com](https://github.com/wdkns/modern_genai_bilibili/blob/main/dev/environment/%E7%A1%AC%E4%BB%B6%E6%8C%87%E5%8D%97/apple-%E8%8A%AF%E7%89%87.ipynb) | [B station](https://www.bilibili.com/video/BV1ZKP1zSEDB)
- **[实用科研] 01 LLM-as-a-Judge, single 评分 vs. pair 对比，gemini 2.5 pro 原生 pdf 科研阅读** - [github.com](https://github.com/chunhuizhang/prompts_for_academic/blob/main/llm_as_a_judge/llm_as_a_judge.ipynb) | [B station](https://www.bilibili.com/video/BV1TYNkzbEy7)
- **[实用科研] 02 DeepConf，Deep Think with Confidence，如何评估一个推理过程的好坏** - [github.com](https://github.com/chunhuizhang/llm_rl/blob/main/tutorials/reasoning/DeepConf.ipynb) | [B station](https://www.bilibili.com/video/BV1yMeEzbEGd)
- **[LLM & AIGC] 01 openai api 的简单介绍（文本生成/指令，图像生成）** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/llm/tutorials/01_openai_api.ipynb) | [openai.com](https://openai.com/api/) | [openai.com](https://openai.com/api/pricing/) | [platform.openai.com](https://platform.openai.com/account/usage) | [B station](https://www.bilibili.com/video/BV1v24y1n7Xt)
- **[LLM & AIGC] 02 ChatGPT api 的简单介绍（system, user, assistant）与多轮对话** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/llm/tutorials/02_chatgpt_api.ipynb) | [platform.openai.com](https://platform.openai.com/docs/guides/chat/introduction?utm_medium=email&_hsmi=248356722&_hsenc=p2ANqtz---D39JbXpjnArtTGpAjkiyPnZK66ca4OF0vwyatKYqXnGNTJx5cH1yA8yeHp5CUO2hvaLXvCoLq3ATF9bjCyr9MzpSYQ&utm_content=248356722&utm_source=hs_email) | [B station](https://www.bilibili.com/video/BV1kN411F76F)
- **[LLM & AIGC] 03 openai  embedding （text-embedding-ada-002）基于 embedding 的文本语义匹配** - [platform.openai.com](https://platform.openai.com/docs/guides/embeddings/what-are-embeddings) | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/llm/tutorials/03_embedding_search.ipynb) | [B station](https://www.bilibili.com/video/BV1s84y1A73s)
- **[LLM && AIGC] visual chatgpt 01 认识 image captioning 及 blip model** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/llm/tutorials/04_visual_chatgpt_01_image_caption.ipynb) | [github.com](https://github.com/microsoft/visual-chatgpt) | [kaggle.com](https://www.kaggle.com/datasets/kunalgupta2616/flickr-8k-images-with-captions) | [B station](https://www.bilibili.com/video/BV1Jb411Z7f2)
- **[LLM && AIGC] 04 深入理解 openai tokenizer 及 api 中的 logit_bias 与 logprobs** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/llm/tutorials/05_openai_tokenizer_logit_bias_logprobs.ipynb) | [help.openai.com](https://help.openai.com/en/articles/4936856-what-are-tokens-and-how-to-count-them) | [B station](https://www.bilibili.com/video/BV1vT411z7BB)
- **[LLM && AIGC] 05 OpenAI 长文本（long text，超出 max_tokens）处理及 summary，划分 chunk 处理** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/llm/tutorials/06_long_text_summarize_vanilla.ipynb) | [platform.openai.com](https://platform.openai.com/docs/models/gpt-3) | [B station](https://www.bilibili.com/video/BV1WT411z7FY)
- **[LLM && AIGC] 06 OpenAI whisper 命令行及脚本的使用（生成视频的音频）** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/llm/tutorials/07_whisper.ipynb) | [B station](https://www.bilibili.com/video/BV13h4y1W7CS)
- **[LLM && AIGC] visual chatgpt 02 认识 Text2Image 及 stable-diffusion-v1-5** - [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/02_text2img.ipynb) | [B station](https://www.bilibili.com/video/BV1M24y1c7Qp)
- **[prompt engineering] 从 CoT 到 ToT（Tree of Thoughts）** - [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/prompt_engineering/tot_tree_of_thought.ipynb) | [B station](https://www.bilibili.com/video/BV1DW421c7tq)
- **[AI Agent] Agentic Reasoning & workflow工作流，及translation-agent 一个具体的 agent 项目** - [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/agents/applications/translation-agent-demo.ipynb) | [B station](https://www.bilibili.com/video/BV1rZ421K7PG)
- **[AI Agent] function calling & tool uses 与 argument generation** - [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/agents/oai_function_call_rag.ipynb) | [B station](https://www.bilibili.com/video/BV1cH4y1c7Xj)
- **[LangChain] 01 基础入门，LCEL 、Tool Use、RAG 以及 LangSmith** - [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/agents/langchain/langchain_agents.ipynb) | [B station](https://www.bilibili.com/video/BV1ax4y1s7Sk)
- **[LangChain] 02 conversational agents，ReAct、agent_scratchpad 历史过程信息维护** - [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/agents/langchain/conversational_agents.ipynb) | [B station](https://www.bilibili.com/video/BV13E421A7j6)
- **[LangChain] 03 LangGraph 基本概念（AgentState、StateGraph，nodes，edges）** - [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/agents/langchain/LangGraph_basics.ipynb) | [B station](https://www.bilibili.com/video/BV1Py411q7mQ)
- **[LangChain] 04 LangGraph 构建复杂 RAG workflow（Self-corrective）** - [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/agents/langchain/LangGraph-rag.ipynb) | [B station](https://www.bilibili.com/video/BV1XnsceyEit)
- **[LangChain] 05 LangChain、LangGraph 结构化输出（Structured output），gpt-4o-2024-08-06** - [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/agents/langchain/structured_output.ipynb) | [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/agents/langchain/output_parser.ipynb) | [B station](https://www.bilibili.com/video/BV1sAxaeHECc)
- **[LangChain] 06 基于LangGraph 实现 Reflexion Agent（generator vs. critic）** - [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/agents/langchain/examples/reflexion_agent.ipynb) | [B station](https://www.bilibili.com/video/BV1XRBBYPERJ)
- **[OpenAI API] logprobs 与 top_logprobs 模型输出的置信度（confidence）与困惑度（PPL）** - [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/oai/logP.ipynb) | [B station](https://www.bilibili.com/video/BV18hqLYtE8W)
- **[LangGraph] gemini 开源全栈 deep research 及 Anthropic multi-agent research system 导读** - [github.com](https://github.com/chunhuizhang/prompts_for_academic/blob/main/deepresearch/multi-agent%20research%20system.ipynb) | [github.com](https://github.com/chunhuizhang/prompts_for_academic/blob/main/deepresearch/gemini_deepresearch.ipynb) | [B station](https://www.bilibili.com/video/BV1DnKWzmEJg)
- **[MCP] 以 sequencial thinking 为例，MCP 原理，修改源码，本地部署** - [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/mcp/about_mcp.ipynb) | [B station](https://www.bilibili.com/video/BV1jLuAzGEzx)
- **[Agentic] 一个具体的 demo 展示所谓的 Agentic Intelligence，Kimi K2，openai agent** - [github.com](https://github.com/chunhuizhang/llm_rl/blob/main/tutorials/k2/agentic.ipynb) | [github.com](https://github.com/chunhuizhang/llm_rl/blob/main/tutorials/k2/scripts/main.py) | [B station](https://www.bilibili.com/video/BV1iuu9zEE6A)
- **[LLM + MCTS] 基于 LangGraph 实现 Language Agent Tree Search （LATS）** - [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/agents/langchain/planning/lats.ipynb) | [B station](https://www.bilibili.com/video/BV1tohbzdEWC)
- **[动手写bert系列] 01 huggingface tokenizer （vocab，encode，decode）原理及细节** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/tree/master/hugface) | [B station](https://www.bilibili.com/video/BV1W34y157tA)
- **[动手写 bert 系列] 02 tokenizer encode_plus, token_type_ids（mlm，nsp）** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/tree/master/hugface) | [B station](https://www.bilibili.com/video/BV1dZ4y1v7U3)
- **[动手写 bert 系列] bert model architecture 模型架构初探（embedding + encoder + pooler）** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/tree/master/fine_tune/bert/tutorials) | [B station](https://www.bilibili.com/video/BV1xT411V7Ng)
- **[动手写 bert 系列] torch.no_grad() vs. param.requires_grad == False** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/tree/master/fine_tune/bert/tutorials) | [stackoverflow.com](https://stackoverflow.com/questions/63785319/pytorch-torch-no-grad-versus-requires-grad-false) | [B station](https://www.bilibili.com/video/BV1HT41137Zw)
- **[动手写 bert 系列] bert embedding 源码解析，word_embedding/position_embedding/token_type** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/tree/master/fine_tune/bert/tutorials) | [B station](https://www.bilibili.com/video/BV1X94y1R7La)
- **[动手写 bert 系列] BertTokenizer subword，wordpiece 如何处理海量数字等长尾单词** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/fine_tune/bert/tutorials/04_subword_wordpiece_tokenizer.ipynb) | [B station](https://www.bilibili.com/video/BV1sv4y1M7aw)
- **[动手写 bert 系列] 解析 bertmodel 的output(last_hidden_state，pooler_output，hidden_state)** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/fine_tune/bert/tutorials/05_model_outputs.ipynb) | [huggingface.co](https://huggingface.co/docs/transformers/model_doc/bert#transformers.BertModel) | [B station](https://www.bilibili.com/video/BV1Qa411D7vZ)
- **[动手写Bert系列] bertencoder self attention 计算细节及计算过程** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/fine_tune/bert/tutorials/06_attn_01.ipynb) | [B station](https://www.bilibili.com/video/BV14B4y1x79R)
- **[动手写bert系列] BertSelfLayer 多头注意力机制（multi head attention）的分块矩阵实现** - [B station](https://www.bilibili.com/video/BV1pe411g7NX)
- **[动手写 bert 系列] Bert 中的（add & norm）残差连接与残差模块（residual connections/residual blocks）** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/fine_tune/bert/tutorials/07_add_norm_residual_conn.ipynb) | [B station](https://www.bilibili.com/video/BV1VW4y1b79x)
- **[动手写bert] bert pooler output 与 bert head** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/fine_tune/bert/tutorials/08_bert_head_pooler_output.ipynb) | [B station](https://www.bilibili.com/video/BV1AG4y1H7wq)
- **[动手写 bert] masking 机制、bert head 与 BertForMaskedLM** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/fine_tune/bert/tutorials/09_masked_lm.ipynb) | [B station](https://www.bilibili.com/video/BV1Je4y1e7uF)
- **[bert、t5、gpt] 01 fine tune transformers 文本分类/情感分析** - [github.com](https://github.com/chunhuizhang/bert_t5_gpt/blob/main/tutorials/01_fine_tune_transformers_on_classification.ipynb) | [B station](https://www.bilibili.com/video/BV1tM411L7HE)
- **[[bert、t5、gpt] 02 transformer 架构 scaled dot product self attention（qkv）** - [github.com](https://github.com/chunhuizhang/bert_t5_gpt/blob/main/tutorials/02_transformer_architecture_self_attention.ipynb) | [B station](https://www.bilibili.com/video/BV14s4y127kk)
- **[[bert、t5、gpt] 03 AttentionHead 与 MultiHeadAttention** - [github.com](https://github.com/chunhuizhang/bert_t5_gpt/blob/main/tutorials/03_transformer_architecture_multi_head_attention.ipynb) | [B station](https://www.bilibili.com/video/BV14V4y1f7L2)
- **[bert、t5、gpt] 04 构建 TransformerEncoderLayer（FFN 与 Layer Norm、skip connection）** - [github.com](https://github.com/chunhuizhang/bert_t5_gpt/blob/main/tutorials/04_ffn_layer_norm_skip_conn.ipynb) | [B station](https://www.bilibili.com/video/BV1XX4y1B71n)
- **[bert、t5、gpt] 05 构建 TransformerDecoderLayer（FFN 与 Masked MultiHeadAttention）** - [github.com](https://github.com/chunhuizhang/bert_t5_gpt/blob/main/tutorials/05_transformer_decoder_layer.ipynb) | [B station](https://www.bilibili.com/video/BV1Ch4y1n7jZ)
- **[bert、t5、gpt] 06 GPT2 整体介绍（tokenizer，model forward）** - [github.com](https://github.com/chunhuizhang/bert_t5_gpt/blob/main/tutorials/06_gpt2_overall.ipynb) | [B station](https://www.bilibili.com/video/BV1hL41187Pw)
- **[bert、t5、gpt] 07 GPT2 decoding （greedy search, beam search）** - [github.com](https://github.com/chunhuizhang/bert_t5_gpt/blob/main/tutorials/07_gpt2_decoding(generation) | [B station](https://www.bilibili.com/video/BV1aa4y1G7p9)
- **[bert、t5、gpt] 08 GPT2 sampling （top-k，top-p （nucleus sampling））** - [github.com](https://github.com/chunhuizhang/bert_t5_gpt/blob/main/tutorials/08_gpt2_decoding_sampling.ipynb) | [B station](https://www.bilibili.com/video/BV1Ho4y1x76q)
- **[bert、t5、gpt] 09 T5 整体介绍（t5-11b，T5ForConditionalGeneration）** - [github.com](https://github.com/chunhuizhang/bert_t5_gpt/blob/main/tutorials/09_t5_overall.ipynb) | [B station](https://www.bilibili.com/video/BV1Lh4y1b74i)
- **[bert、t5、gpt] 10 知识蒸馏（knowledge distill）初步，模型结构及损失函数设计** - [github.com](https://github.com/chunhuizhang/bert_t5_gpt/blob/main/tutorials/11_knowledge_distillation_basics.ipynb) | [B station](https://www.bilibili.com/video/BV1Do4y1A7EN)
- **[bert、t5、gpt] 11 知识蒸馏（knowledge distill）huggingface trainer pipeline** - [github.com](https://github.com/chunhuizhang/bert_t5_gpt/blob/main/tutorials/13_kd_pipeline.ipynb) | [B station](https://www.bilibili.com/video/BV16V4y18733)
- **[BERT 番外] Sin Position Encoding 的简洁实现（RoPE 基础）** - [github.com](https://github.com/chunhuizhang/bert_t5_gpt/blob/main/tutorials/sin_position_encoding.ipynb) | [B station](https://www.bilibili.com/video/BV1KN411p73o)
- **[GPT 番外] tied/share tensors wte与lm_head（GPT2LMHeadModel）** - [github.com](https://github.com/chunhuizhang/bert_t5_gpt/blob/main/tutorials/tied_shared_tensors_lm_head_token_embedding.ipynb) | [B station](https://www.bilibili.com/video/BV1ec411971a)
- **[sbert 01] sentence-transformers pipeline** - [github.com](https://github.com/chunhuizhang/bert_t5_gpt/blob/main/tutorials/sbert-tutorials/sentence-transformers-pipeline.ipynb) | [B station](https://www.bilibili.com/video/BV1sK421C7oG)
- **[sbert 02] sbert 前向及损失函数pooling method计算细节** - [github.com](https://github.com/chunhuizhang/bert_t5_gpt/blob/main/tutorials/sbert-tutorials/sbert_%E6%BA%90%E7%A0%81%E5%88%86%E6%9E%90.ipynb) | [B station](https://www.bilibili.com/video/BV1S6421u7jA)
- **[LLM 番外] 自回归语言模型cross entropy loss，及 PPL 评估** - [github.com](https://github.com/chunhuizhang/bert_t5_gpt/blob/main/tutorials/ar_lm_loss_PPL-perplexity.ipynb) | [B station](https://www.bilibili.com/video/BV1ZA4m1w7D5)
- **[gpt2 番外] training vs. inference（generate），PPL 计算，交叉熵损失与 ignore_index** - [github.com](https://github.com/chunhuizhang/bert_t5_gpt/blob/main/tutorials/gpt2_training_inference_ppl.ipynb) | [B station](https://www.bilibili.com/video/BV1ox4y147o1)
- **[LLM 原理] 高效推理 Speculative Decoding 投机探测采样** - [github.com](https://github.com/chunhuizhang/llm_rl/blob/main/tutorials/infra/flashinfer/speculative_decoding.ipynb) | [B station](https://www.bilibili.com/video/BV1Vt3QzLEQ1)
- **[LLM+RL] 合成数据与model collapse，nature 正刊封面** - [github.com](https://github.com/chunhuizhang/llm_rl/blob/main/tutorials/garbage_out.ipynb) | [B station](https://www.bilibili.com/video/BV18JyaYxEGi)
- **[LLM+RL] 基于开源 LLM 实现 O1-like step by step 慢思考（slow thinking），ollama，streamlit** - [github.com](https://github.com/chunhuizhang/llm_rl/blob/main/tutorials/reasoning/ollama_reasoning.ipynb) | [B station](https://www.bilibili.com/video/BV1ZsBjY5EBb)
- **[LLM+RL] model.generate 之 beam search decoding strategy** - [github.com](https://github.com/chunhuizhang/llm_rl/blob/main/tutorials/search-learn/llm_beam_search.ipynb) | [B station](https://www.bilibili.com/video/BV1SbrKYkETg)
- **[LLM + RL] kimi 1.5 论文导读与 highlights** - [github.com](https://github.com/chunhuizhang/llm_rl/blob/main/tutorials/r1-k1.5/k1.5.ipynb) | [B station](https://www.bilibili.com/video/BV1RXNDeMEin)
- **[LLM+RL] R1 论文导读，SFT vs. RL，RL 基础以及 GRPO 细节，以及一系列复现工作讨论** - [B station](https://www.bilibili.com/video/BV15yA3eWE5b)
- **[LLM+RL] 理解 GRPO 公式原理及 TRL GrpoTrainer 代码实现（advantage 与 loss 计算）** - [github.com](https://github.com/chunhuizhang/llm_rl/blob/main/tutorials/r1-k1.5/trl_grpo.ipynb) | [B station](https://www.bilibili.com/video/BV1pXA5eyEEg)
- **[LLM+RL] GRPO 中的 KL div（散度），reverse vs. forward，以及无偏估计（Schulman）** - [github.com](https://github.com/chunhuizhang/llm_rl/blob/main/tutorials/r1-k1.5/grpo_kl.ipynb) | [B station](https://www.bilibili.com/video/BV1rsAXe7EZs)
- **[RL4LLM] 理解 reasoning model Tokenizer 的 chat template，vllm inference** - [github.com](https://github.com/chunhuizhang/llm_rl/blob/main/tutorials/r1-k1.5/reasoning_model_chat_template_and_inference.ipynb) | [B station](https://www.bilibili.com/video/BV1LKXSYqE3T)
- **[RL4LLM] PPO workflow 及 OpenRLHF、veRL 初步介绍，ray distributed debugger** - [github.com](https://github.com/chunhuizhang/llm_rl/blob/main/tutorials/r1-k1.5/infra/overall_basics.ipynb) | [B station](https://www.bilibili.com/video/BV1Pz9tYbEeZ)
- **[RL4LLM] 深入 PPO-clip 目标函数细节（及重要性采样）** - [github.com](https://github.com/chunhuizhang/llm_rl/blob/main/tutorials/basics_insights_of_RL/importance_sampling.ipynb) | [github.com](https://github.com/chunhuizhang/llm_rl/blob/main/tutorials/basics_insights_of_RL/PPO_clip.ipynb) | [B station](https://www.bilibili.com/video/BV1y1R4YbE1E)
- **[RL4LLM] GRPO loss/objective 分析 及可能的 biases 分析（DAPO，Dr. GRPO)** - [github.com](https://github.com/chunhuizhang/llm_rl/blob/main/tutorials/r1-k1.5/grpo_loss.ipynb) | [B station](https://www.bilibili.com/video/BV1LgXbY5EFD)
- **[RL4LLM] deepseek v3 工具调用的 bug 以及理解 chat_template 的 function calling** - [github.com](https://github.com/chunhuizhang/llm_rl/blob/main/tutorials/tokenizer/v3.ipynb) | [B station](https://www.bilibili.com/video/BV1dsdWYuEXw)
- **[veRL] 性能优化 use_remove_padding （flash attn varlen）变长序列处理** - [github.com](https://github.com/chunhuizhang/llm_rl/blob/main/tutorials/infra/verl/verl_packing.ipynb) | [verl.readthedocs.io](https://verl.readthedocs.io/en/latest/perf/perf_tuning.html) | [B station](https://www.bilibili.com/video/BV1ZqdaYAEzA)
- **[veRL] log probs from logits 与 entropy from logits 的高效计算** - [github.com](https://github.com/chunhuizhang/llm_rl/blob/main/tutorials/infra/verl/log_probs_from_logits.ipynb) | [B station](https://www.bilibili.com/video/BV1iedzYEEV4)
- **[RL4LLM] base vs. instruct model，个性化（custom）chat template（make prefix）** - [github.com](https://github.com/chunhuizhang/llm_rl/blob/main/tutorials/tokenizer/base_instruct.ipynb) | [github.com](https://github.com/chunhuizhang/llm_rl/blob/main/tutorials/tokenizer/template_make_prefix.ipynb) | [B station](https://www.bilibili.com/video/BV1JZLcz4EUC)
- **[RL insights] 深入理解 Policy Gradient 算法（REINFORCE, Actor-Critic, A2C），打开强化学习算法的总钥匙** - [github.com](https://github.com/chunhuizhang/modern_ai_for_beginners/blob/main/books_reading_notes/RL/%E5%BC%BA%E5%8C%96%E5%AD%A6%E4%B9%A0%E7%9A%84%E6%95%B0%E5%AD%A6%E5%8E%9F%E7%90%86.ipynb) | [B station](https://www.bilibili.com/video/BV1i8TQzuEKs)
- **[RL insights] 推导和理解 Policy Gradient 算法，PG vs. MLE/SFT，采样及训练过程** - [github.com](https://github.com/chunhuizhang/llm_rl/blob/main/tutorials/basics_insights_of_RL/pg.ipynb) | [B station](https://www.bilibili.com/video/BV1UzgozEEFA)
- **[五分钟系列] 01 gensim embedding vectors 距离及可视化分析** - [github.com](https://github.com/chunhuizhang/bert_t5_gpt/blob/main/tutorials/embedding_visualize_analysis.ipynb) | [B station](https://www.bilibili.com/video/BV1Zs4y1r7mg)
- **[工具的使用] 从 jupyter notebook 到 jupyter lab（网页版 vscode？）** - [github.com](https://github.com/chunhuizhang/full_stack/blob/main/tutorials/%E7%8E%AF%E5%A2%83%E5%8F%8A%E4%BE%9D%E8%B5%96/pip_jupyter.ipynb) | [B station](https://www.bilibili.com/video/BV1Qt421G74s)
- **[五分钟快谈] GPT Canvas 从 notebook 到 python 文件** - [B station](https://www.bilibili.com/video/BV1whqDYLETt)
- **[实用 AI 工具] gemini-cli 尝鲜，命令行中的Agent，（mcp servers）** - [B station](https://www.bilibili.com/video/BV13LKyzkEhu)
- **[pytorch distributed] 01 nn.DataParallel 数据并行初步** - [github.com](https://github.com/chunhuizhang/pytorch_distribute_tutorials/blob/main/tutorials/01_multi_gpus_data_parallelism.ipynb) | [B station](https://www.bilibili.com/video/BV1jm4y187tM)
- **[pytorch distributed] 02 DDP 基本概念（Ring AllReduce，node，world，rank，参数服务器）** - [github.com](https://github.com/chunhuizhang/pytorch_distribute_tutorials/blob/main/tutorials/02_ddp_basics.ipynb) | [B station](https://www.bilibili.com/video/BV1Uo4y1K7wM)
- **[pytorch distributed] 03 DDP 初步应用（Trainer，torchrun）** - [github.com](https://github.com/chunhuizhang/pytorch_distribute_tutorials/blob/main/tutorials/03_ddp_toy_example.ipynb) | [github.com](https://github.com/chunhuizhang/pytorch_distribute_tutorials/blob/main/tutorials/ddp_gpus.py) | [github.com](https://github.com/chunhuizhang/pytorch_distribute_tutorials/blob/main/tutorials/ddp_gpus_torchrun.py) | [B station](https://www.bilibili.com/video/BV13L411i7Ls)
- **[pytorch distributed] 04 模型并行（model parallel）on ResNet50** - [github.com](https://github.com/chunhuizhang/pytorch_distribute_tutorials/blob/main/tutorials/04_model_parallel_resnet50.ipynb) | [B station](https://www.bilibili.com/video/BV15h4y1V7xe)
- **[pytorch distributed] 05 张量并行（tensor parallel），分块矩阵的角度，作用在 FFN 以及 Attention 上** - [github.com](https://github.com/chunhuizhang/pytorch_distribute_tutorials/blob/main/tutorials/tensor_parallel.ipynb) | [B station](https://www.bilibili.com/video/BV1Jy4y1A76p)
- **[pytorch distributed] torch 分布式基础（process group），点对点通信，集合通信** - [github.com](https://github.com/chunhuizhang/pytorch_distribute_tutorials/blob/main/tutorials/torch_distributed_basics.ipynb) | [github.com](https://github.com/chunhuizhang/pytorch_distribute_tutorials/blob/main/tutorials/torch_dist.py) | [B station](https://www.bilibili.com/video/BV1t2421F7zY)
- **[pytorch distributed] nccl 集合通信（collective communication）** - [github.com](https://github.com/chunhuizhang/pytorch_distribute_tutorials/blob/main/tutorials/torch_nccl_collective_communication.ipynb) | [github.com](https://github.com/chunhuizhang/pytorch_distribute_tutorials/blob/main/tutorials/torch_nccl_test.py) | [B station](https://www.bilibili.com/video/BV1zK42187Kv)
- **[pytorch distributed] amp 原理，automatic mixed precision 自动混合精度** - [github.com](https://github.com/chunhuizhang/pytorch_distribute_tutorials/blob/main/tutorials/amp_autocast_mixed_precision_training.ipynb) | [B station](https://www.bilibili.com/video/BV1eW421w7NJ)
- **[pytorch distributed] deepspeed 基本概念、原理（os+g+p）** - [github.com](https://github.com/chunhuizhang/pytorch_distribute_tutorials/blob/main/tutorials/deepspeed_accelerate/deepspeed_basics.ipynb) | [B station](https://www.bilibili.com/video/BV1rZ42187PA)
- **[pytorch distributed] accelerate 基本用法（config，launch）数据并行** - [github.com](https://github.com/chunhuizhang/pytorch_distribute_tutorials/blob/main/tutorials/deepspeed_accelerate/accelerate_config.ipynb) | [B station](https://www.bilibili.com/video/BV1jS411K72E)
- **[QKV attention] kv-cache、decoder only vs. BERT, 单向注意力 vs. 双向注意力** - [github.com](https://github.com/chunhuizhang/pytorch_distribute_tutorials/blob/main/tutorials/kv-cache.ipynb) | [B station](https://www.bilibili.com/video/BV1sw4m1v7sa)
- **[pytorch distributed] 从 DDP、模型并行、流水线并行到 FSDP（NCCL，deepspeed 与 Accelerate）** - [github.com](https://github.com/chunhuizhang/pytorch_distribute_tutorials/blob/main/tutorials/FSDP.ipynb) | [B station](https://www.bilibili.com/video/BV1Kx4y187Te)
- **[QKV attention] flash attention（Tiling与重计算），operation fused，HBM vs. SRAM** - [github.com](https://github.com/chunhuizhang/bert_t5_gpt/blob/main/tutorials/attention/flash_attn.ipynb) | [B station](https://www.bilibili.com/video/BV1DW421R7CA)
- **[pytorch distributed] 张量并行与 megtron-lm 及 accelerate 配置** - [github.com](https://github.com/chunhuizhang/pytorch_distribute_tutorials/blob/main/tutorials/deepspeed_accelerate/megtron_lm.ipynb) | [B station](https://www.bilibili.com/video/BV1TsWoe4E22)
- **[pytorch 加速] CPU传输 & GPU计算的并行（pin_memory，non_blocking）** - [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/nn_basics/performance_optimization/pytorch_optimization.ipynb) | [B station](https://www.bilibili.com/video/BV15Xxve1EtZ)
- **[Pytorch 分布式] ring-allreduce 算法（scatter-reduce、allgather）以及 FSDP** - [github.com](https://github.com/chunhuizhang/pytorch_distribute_tutorials/blob/main/tutorials/3D-parallel/ring-allreduce.ipynb) | [B station](https://www.bilibili.com/video/BV1biLHzAEzv)
- **[Pytorch 分布式] DeepSpeed Ulysses 分布式序列并行算法，尤利西斯，Ring attention** - [github.com](https://github.com/chunhuizhang/pytorch_distribute_tutorials/blob/main/tutorials/3D-parallel/SP-%E5%BA%8F%E5%88%97%E5%B9%B6%E8%A1%8C.ipynb) | [B station](https://www.bilibili.com/video/BV1tsVZzbEXh)
- **[LLMs inference] quantization 量化整体介绍（bitsandbytes、GPTQ、GGUF、AWQ）** - [github.com](https://github.com/chunhuizhang/llm_inference_serving/blob/main/tutorials/quantization/qlora_gptq_gguf_awq.ipynb) | [github.com](https://github.com/chunhuizhang/llm_inference_serving/blob/main/tutorials/quantization/basics.ipynb) | [B station](https://www.bilibili.com/video/BV1FH4y1c73W)
- **[LLMs inference] hf transformers 中的 KV cache** - [github.com](https://github.com/chunhuizhang/llm_inference_serving/blob/main/tutorials/cache/use_cache_past_key_values.ipynb) | [B station](https://www.bilibili.com/video/BV1VpU6YcEuS)
- **[LLMs serving] openrouter & vllm host LLM 推理服务，openai api 兼容** - [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/ai_app/openrouter.ipynb) | [github.com](https://github.com/chunhuizhang/llm_inference_serving/blob/main/tutorials/vllm/hosting_OpenAI-Compatible%20Server.ipynb) | [B station](https://www.bilibili.com/video/BV17FccedE8s)
- **[LLMs inference] vllm & sglang offline inference，tensor parallel vs. data parall** - [github.com](https://github.com/chunhuizhang/llm_rl/tree/main/tutorials/infra/inference/scripts) | [B station](https://www.bilibili.com/video/BV1jGXHYfEdx)
- **[stable diffusion] 01 本地安装及环境配置（diffusers, StableDiffusionPipeline, text2image）** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/diffusion/tutorials/01_tut.ipynb) | [B station](https://www.bilibili.com/video/BV1BV4y137bA)
- **[diffusion] 生成模型基础 VAE 原理及实现** - [github.com](https://github.com/chunhuizhang/diffusion_models_tutorials/blob/main/tutorials/Variational_Autoencoders.ipynb) | [B station](https://www.bilibili.com/video/BV1QC4y1A7Gs)
- **[generative models] 概率建模视角下的现代生成模型（生成式 vs. 判别式，采样与密度估计）** - [github.com](https://github.com/chunhuizhang/generative_models_tutorials/blob/main/tutorials/%E6%A6%82%E7%8E%87%E5%BB%BA%E6%A8%A1%E8%A7%86%E8%A7%92%E4%B8%8B%E7%9A%84%E7%94%9F%E6%88%90%E6%A8%A1%E5%9E%8B_cdf_sampling_kde.ipynb) | [B station](https://www.bilibili.com/video/BV1bi421v75t)
- **[VAE] VAE 核心concepts、概率建模思维及 latent space 可视化** - [github.com](https://github.com/chunhuizhang/diffusion_models_tutorials/blob/main/tutorials/vae/vae_latent_space.ipynb) | [B station](https://www.bilibili.com/video/BV1r3w6eyEys)
- **[纳什荐书][生成式AI] 01 《GPT图解》导读** - [github.com](https://github.com/chunhuizhang/modern_ai_for_beginners/tree/main/books_reading_notes) | [github.com](https://github.com/chunhuizhang/modern_ai_for_beginners) | [B station](https://www.bilibili.com/video/BV1BT421S7rb)
- **[纳什荐书][强化学习] chap2 MDP（马尔可夫决策过程），最优策略与最优状态价值** - [github.com](https://github.com/chunhuizhang/modern_ai_for_beginners/blob/main/books_reading_notes/%E6%B7%B1%E5%BA%A6%E5%AD%A6%E4%B9%A0%E5%85%A5%E9%97%A8/%E5%BC%BA%E5%8C%96%E5%AD%A6%E4%B9%A0/chap2_mdp.ipynb) | [B station](https://www.bilibili.com/video/BV1Hb6WYkEHd)
- **[动手写神经网络] 如何设计卷积核（conv kernel）实现降2采样，以及初探vggnet/resnet 卷积设计思路（不断降空间尺度，升channel）** - [pytorch.org](https://pytorch.org/docs/stable/generated/torch.nn.Conv2d.html) | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/learn_torch/utils/vgg_hook.py) | [B station](https://www.bilibili.com/video/BV1dF411P7Fk)
- **[动手写神经网络] 如何对数据集归一化（transforms.Normalize）以 mnist 数据集为例（mean=0.1307, std=0.3081）** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/dl/normalize/mnist_demo.py) | [stackoverflow.com](https://stackoverflow.com/questions/63746182/correct-way-of-normalizing-and-scaling-the-mnist-dataset) | [B station](https://www.bilibili.com/video/BV12K411f76T)
- **[动手写神经网络] 如何对数据集（ImageNet） denormalize（inverse normalize）还原为原来的均值和标准差（mean/std）** - [B station](https://www.bilibili.com/video/BV1og411m7cc)
- **[动手写神经网络] 01 认识 pytorch 中的 dataset、dataloader（mnist、fashionmnist、cifar10）** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/dl/tutorials/01_torch_dataset_dataloader.ipynb) | [B station](https://www.bilibili.com/video/BV18y4y1Q7Jy)
- **【深度学习环境搭建】01 本机、GPU服务器端深度学习环境搭建（代码、数据共享）** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/dl/tutorials/03_rnn_on_images.py) | [B station](https://www.bilibili.com/video/BV1G14y1c7Sw)
- **【深度学习环境搭建】02 gpu 服务器端部署 jupyter notebook server** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/dl/tutorials/test_jupyter_notebook.ipynb) | [B station](https://www.bilibili.com/video/BV1Ye4y1P7bw)
- **[动手写神经网络] 02 逐行写代码 CNN pipeline 图像分类（模型结构、训练、评估）** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/dl/tutorials/02_cnn_on_mnist.ipynb) | [B station](https://www.bilibili.com/video/BV1954y1N7bh)
- **[动手写神经网络] 03 自定义 CNN 模型适配新的数据集 CIFAR10（适配+简单调参）** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/dl/tutorials/03_cnn_on_cifar10.ipynb) | [B station](https://www.bilibili.com/video/BV1js4y1a77W)
- **[动手写神经网络] 04 使用预训练 vgg 提升 cifar10 分类准确率** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/dl/tutorials/04_vgg_on_cifar10.ipynb) | [B station](https://www.bilibili.com/video/BV1Z54y1F77T)
- **[动手写神经网络] 05 使用预训练 resnet18 提升 cifar10 分类准确率及误分类图像可视化分析** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/dl/tutorials/05_resnet_on_cifar10.ipynb) | [B station](https://www.bilibili.com/video/BV1xj411g796)
- **[动手写神经网络] 06 自定义（kaggle）数据集（custom dataset）、Dataloader，及 train test valid 数据集拆分** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/dl/tutorials/06_custom_dataset_train_valid_test.ipynb) | [B station](https://www.bilibili.com/video/BV1z84y1P79Q)
- **[动手写神经网络] 07 预训练 resnet 解决 kaggle weather dataset（validation dataset）的使用** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/dl/tutorials/07_resnet_on_weather_validation_data.ipynb) | [B station](https://www.bilibili.com/video/BV1Cs4y1578z)
- **[动手写神经网络] 08 WandB（weights & biases）深度学习调参利器** - [wandb.ai](https://wandb.ai/site/articles/intro-to-pytorch-with-wandb) | [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/nn_basics/01_pytorch_wandb.ipynb) | [B station](https://www.bilibili.com/video/BV1qs4y1A7qq)
- **[动手写神经网络] 可微才可学，深度学习框架自动微分计算图（DAG）** - [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/nn_basics/grad/%E5%8F%AF%E5%BE%AE%E6%89%8D%E5%8F%AF%E5%AD%A6.ipynb) | [B station](https://www.bilibili.com/video/BV1gMC9YJEiX)
- **[动手写神经网络] 手动实现 Transformer Encoder** - [github.com](https://github.com/chunhuizhang/bert_t5_gpt/blob/main/tutorials/encoder-decoder/transformer-encoder-decoder.ipynb) | [B station](https://www.bilibili.com/video/BV1cZ1xYFEFx)
- **[动手写 Transformer] 从 RNN 到 Transformer，为什么需要位置编码（position encoding）** - [github.com](https://github.com/chunhuizhang/bert_t5_gpt/blob/main/tutorials/encoder-decoder/bow_wo_pe.ipynb) | [B station](https://www.bilibili.com/video/BV1zRSqYvEjC)
- **[动手写神经网络] pytorch 高维张量 Tensor 维度操作与处理，einops** - [github.com](https://github.com/chunhuizhang/bert_t5_gpt/blob/main/tutorials/encoder-decoder/reshape_permute_einsum.ipynb) | [B station](https://www.bilibili.com/video/BV173DrY5EAL)
- **[动手写 Transformer] 手动实现 Transformer Decoder（交叉注意力，encoder-decoder cross attentio）** - [github.com](https://github.com/chunhuizhang/bert_t5_gpt/blob/main/tutorials/encoder-decoder/transformer-encoder-decoder.ipynb) | [B station](https://www.bilibili.com/video/BV1ZqUaYmEkq)
- **[动手写神经网络] kSparse AutoEncoder 稀疏性激活的显示实现（SAE on LLM）** - [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/dnn/ae/ksparse-ae.py) | [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/dnn/ae/ksparse-ae.ipynb) | [B station](https://www.bilibili.com/video/BV15JCrYWEDQ)
- **[蒙特卡洛方法] 01 从黎曼和式积分（Reimann Sum）到蒙特卡洛估计（monte carlo estimation）求积分求期望** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/rl/montecarlo/01_monte_carlo_estimation.ipynb) | [en.wikipedia.org](https://en.wikipedia.org/wiki/Monte_Carlo_integration) | [B station](https://www.bilibili.com/video/BV1Hm4y1z7bP)
- **[蒙特卡洛方法] 02 重要性采样（importance sampling）及 python 实现** - [github.com](https://github.com/chunhuizhang/deeplearning_math/blob/main/tutorials/montecarlo/importance_sampling.ipynb) | [B station](https://www.bilibili.com/video/BV1SV4y1i7bW)
- **[蒙特卡洛方法] 03 接受/拒绝采样（accept/reject samping）初步 cases 分析** - [github.com](https://github.com/chunhuizhang/deeplearning_math/blob/main/tutorials/montecarlo/rejection_sampling_01_cases.ipynb) | [B station](https://www.bilibili.com/video/BV1Tm4y1N7hU)
- **[蒙特卡洛方法] 04 重要性采样补充，数学性质及 On-policy vs. Off-policy** - [github.com](https://github.com/chunhuizhang/deeplearning_math/blob/main/tutorials/montecarlo/importance_sampling_2.ipynb) | [B station](https://www.bilibili.com/video/BV1Vr421u7Qz)
- **[蒙特卡洛方法] 05 接受拒绝采样框架、原理推导与分析（MCMC 基础）** - [github.com](https://github.com/chunhuizhang/deeplearning_math/blob/main/tutorials/montecarlo/accept-reject/formulate.ipynb) | [github.com](https://github.com/chunhuizhang/deeplearning_math/blob/main/tutorials/montecarlo/accept-reject/practices.ipynb) | [B station](https://www.bilibili.com/video/BV1RKkbYSEoS)
- **[蒙特卡洛方法] 06 马尔可夫链（Markov Chain）与稳态分布和细致平稳条件（detailed balance）** - [github.com](https://github.com/chunhuizhang/deeplearning_math/blob/main/tutorials/montecarlo/mcmc/Markov-Chain.ipynb) | [B station](https://www.bilibili.com/video/BV1SYkqYPE1s)
- **[手推公式] sigmoid 及其导数 softmax 及其导数性质（从 logits 到 probabilities）** - [B station](https://www.bilibili.com/video/BV14v4y137Sv)
- **【手推公式】从 logodds 到 sigmoid 概率化输出，用于 LR、XGBoost 的分类任务** - [B station](https://www.bilibili.com/video/BV1fA411v7xj)
- **【手推公式】odds（几率）与对数几率（logodds）在logistics regression及xgboost classification中的应用** - [B station](https://www.bilibili.com/video/BV1rp4y1D74F)
- **【手推公式】指数族分布（exponential family distribution），伯努利分布及高斯分布的推导** - [B station](https://www.bilibili.com/video/BV1Cg4y1q7jW)
- **【手推公式】从二分类（二项分布）到多分类（多项分布），最大似然估计与交叉熵损失的等价** - [B station](https://www.bilibili.com/video/BV1a5411W7Dn)
- **【机器学习】【手推公式】从Hinge loss（合页损失）到 SVM（hard margin/soft margin）** - [B station](https://www.bilibili.com/video/BV1ai4y1x7LN)
- **【手推公式】xgboost自定义损失函数（cross entropy/squared log loss）及其一阶导数gradient二阶导数hessian** - [B station](https://www.bilibili.com/video/BV12i4y1s7nj)
- **【手推公式】multi-classification多分类评估（precision/recall，micro averaging与macro averaging** - [B station](https://www.bilibili.com/video/BV1Ji4y147F9)
- **【手推公式】【销量预测】【回归分析】MAE与MSE在回归分析时的区别，为什么MSE倾向于回归均值，MAE倾向于回归中位数** - [B station](https://www.bilibili.com/video/BV13z4y1d7CA)
- **【手推公式】【目标检测】【Fast RCNN】RoIPooling 的作用及计算** - [B station](https://www.bilibili.com/video/BV1sz4y1R7go)
- **【数学分析】泰勒级数（Taylor series）展开的本质（多项式逼近）多项式系数的推导** - [B station](https://www.bilibili.com/video/BV1Fr4y1A7ei)
- **[AI 核心概念及计算] 优化 01 梯度下降（gradient descent）与梯度上升（gradient ascent）细节及可视化分析** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/ml_core/tutorials/01_grad_descent_details_visualization.ipynb) | [realpython.com](https://realpython.com/gradient-descent-algorithm-python/#momentum-in-stochastic-gradient-descent) | [B station](https://www.bilibili.com/video/BV1sc41157fk)
- **[AI 核心概念及计算] 概率计算 01 pytorch 最大似然估计（MLE）伯努利分布的参数** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/ml_core/tutorials/02_pytorch_mle_for_bernoulli.ipynb) | [B station](https://www.bilibili.com/video/BV15s4y1S7aZ)
- **【矩阵分析】从特征值特征向量到矩阵SVD奇异值分解（np.linalg.svd）** - [B station](https://www.bilibili.com/video/BV1u54y12766)
- **[矩阵分析] LoRA 矩阵分析基础之 SVD low rank approximation（低秩逼近）** - [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/supplement_01_svd.ipynb) | [B station](https://www.bilibili.com/video/BV1Jg4y1c7dh)
- **[数学！数学] 最大似然估计（MLE）与最小化交叉熵损失（cross entropy loss）的等价性** - [github.com](https://github.com/chunhuizhang/deeplearning_math/blob/main/tutorials/01_cross_entropy_mle.ipynb) | [B station](https://www.bilibili.com/video/BV19k4y1M7cJ)
- **[pytorch optim] 优化器相关 - learning rate scheduler** - [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/nn_basics/optimizer/lr_scheduler.ipynb) | [B station](https://www.bilibili.com/video/BV1oP411z7bv)
- **[矩阵分析] 从向量范数到矩阵范数、torch spectral norm（矩阵的谱范数）** - [github.com](https://github.com/chunhuizhang/deeplearning_math/blob/main/tutorials/matrix/Lp_norm_matrix_norm.ipynb) | [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/nn_basics/spectral_norm.ipynb) | [B station](https://www.bilibili.com/video/BV1JN411h7qU)
- **[pytorch optim] 优化器相关 AdaGrad（adaptive gradient） 与 RMSprop，自适应梯度** - [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/nn_basics/optimizer/adagrad_rmsprop.ipynb) | [B station](https://www.bilibili.com/video/BV1294y1C7S4)
- **【矩阵分析】二维旋转矩阵的推导（极坐标/基变换）** - [scipython.com](https://scipython.com/book/chapter-6-numpy/examples/creating-a-rotation-matrix-in-numpy/) | [B station](https://www.bilibili.com/video/BV17Y4y1Y7Ss)
- **[矩阵分析] 旋转矩阵的计算机与应用（复平面，RoPE）** - [github.com](https://github.com/chunhuizhang/deeplearning_math/blob/main/tutorials/matrix/%E6%97%8B%E8%BD%AC%E7%9F%A9%E9%98%B5%EF%BC%88rotation%20matrix%EF%BC%89.ipynb) | [B station](https://www.bilibili.com/video/BV1pw411D7nP)
- **[概率 & 统计] kl div kl散度的计算及应用（pytorch）** - [github.com](https://github.com/chunhuizhang/deeplearning_math/blob/main/tutorials/prob_stats/kl_div_basics.ipynb) | [github.com](https://github.com/chunhuizhang/deeplearning_math/blob/main/tutorials/prob_stats/pytorch_kl_div_examples.ipynb) | [B station](https://www.bilibili.com/video/BV1JG411o7GV)
- **[多元变量微分] 方向导数与梯度下降方法（directional derivatives）** - [github.com](https://github.com/chunhuizhang/deeplearning_math/blob/main/tutorials/calculus/derivative_partial_directional.ipynb) | [B station](https://www.bilibili.com/video/BV1n94y1G7Jx)
- **[凸函数] convex 性质与简森不等式（jensen's inequality）与 ELBO、投资组合理论（Porfolio）** - [github.com](https://github.com/chunhuizhang/deeplearning_math/blob/main/tutorials/calculus/convex_function_jensen_inequality.ipynb) | [B station](https://www.bilibili.com/video/BV1Lu4y1P7e5)
- **[统计] python 假设检验基础（T-Test，ANOVA，chi2）** - [github.com](https://github.com/chunhuizhang/deeplearning_math/blob/main/tutorials/prob_stats/stats/%E5%81%87%E8%AE%BE%E6%A3%80%E9%AA%8C.ipynb) | [B station](https://www.bilibili.com/video/BV1NQ4y1t79i)
- **[机器学习理论] 霍夫丁不等式（hoeffding's inequality）到 UCB** - [github.com](https://github.com/chunhuizhang/deeplearning_math/blob/main/tutorials/prob_stats/hoeffding's_inequality.ipynb) | [B station](https://www.bilibili.com/video/BV1xe411k7V1)
- **[概率 & 统计] Thompson Sampling（随机贝叶斯后验采样）与多臂老虎机** - [github.com](https://github.com/chunhuizhang/deeplearning_math/blob/main/tutorials/prob_stats/multi_armed_bandits_thompson_sampling.ipynb) | [B station](https://www.bilibili.com/video/BV18p4y1Z7Xd)
- **[矩阵分析] 分块矩阵的角度理解矩阵运算（独热向量与对角矩阵）** - [github.com](https://github.com/chunhuizhang/deeplearning_math/blob/main/tutorials/matrix/%E5%88%86%E5%9D%97%E7%9F%A9%E9%98%B5%E7%9A%84%E5%A4%84%E7%90%86%E4%B8%8E%E7%90%86%E8%A7%A3.ipynb) | [B station](https://www.bilibili.com/video/BV11T4y1b714)
- **[pytorch optim] Adam 与 AdamW，L2 reg 与 weight decay，deepseed** - [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/nn_basics/optimizer/adadelta_adam.ipynb) | [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/nn_basics/optimizer/l2_reg_weight_decay_adaw.ipynb) | [B station](https://www.bilibili.com/video/BV1Wt421b7uA)
- **[pytorch optim] pytorch 作为一个通用优化问题求解器（目标函数、决策变量）** - [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/nn_basics/optimizer/pytorch_as_a_general_optimizer.ipynb) | [B station](https://www.bilibili.com/video/BV1kt421V7Y4)
- **[lora 番外] LoRA merge 与 SVD（矩阵奇异值分解）** - [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/peft/lora_svd_basics.ipynb) | [B station](https://www.bilibili.com/video/BV1XK421a75H)
- **[矩阵微分] 标量/矢量关于矢量/矩阵的矩阵微分，深度学习框架反向传播** - [github.com](https://github.com/chunhuizhang/deeplearning_math/blob/main/tutorials/matrix/matrix_calculus.ipynb) | [B station](https://www.bilibili.com/video/BV1R4421Z79L)
- **[损失函数设计] 为什么多分类问题损失函数用交叉熵损失，而不是 MSE** - [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/nn_basics/loss/mse_crossentropy.ipynb) | [B station](https://www.bilibili.com/video/BV13NHfewE3o)
- **[数学基础] 概率（probability） vs. 似然（likelihood），及其在LLM中小小的实践** - [github.com](https://github.com/chunhuizhang/deeplearning_math/blob/main/tutorials/prob_stats/LM%E4%B8%AD%E7%9A%84%E6%A6%82%E7%8E%87%E4%B8%8E%E4%BC%BC%E7%84%B6.ipynb) | [B station](https://www.bilibili.com/video/BV1JpBtYjE5C)
- **[LLMs 实践] 01 llama、alpaca、vicuna 整体介绍及 llama 推理过程** - [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/01_llama_intro.ipynb) | [B station](https://www.bilibili.com/video/BV1jk4y1L75w)
- **[LLMs 实践] 02 LoRA（Low Rank Adaption）基本原理与基本概念，fine-tune 大语言模型** - [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/02_lora_baics.ipynb) | [B station](https://www.bilibili.com/video/BV15T411477N)
- **[LLMs 实践] 03 LoRA fine-tune 大语言模型（peft、bloom 7b）** - [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/03_lora_practice.ipynb) | [B station](https://www.bilibili.com/video/BV1qz4y1B7LB)
- **[LLMs 实践] 04 PEFT/LoRA 源码分析** - [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/04_PEFT_lora.ipynb) | [B station](https://www.bilibili.com/video/BV1sV4y1z7uS)
- **[番外] float16 与 bf16 表示和计算细节** - [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/05_float16_bf16.ipynb) | [B station](https://www.bilibili.com/video/BV1no4y1u7og)
- **[LLMs 实践] 06 LLaMA，Alpaca LoRA 7B 推理** - [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/06_alpaca_llama_7b_lora.ipynb) | [B station](https://www.bilibili.com/video/BV1Po4y1T7Bn)
- **[LLMs 实践] 07 fp16 与自动混合精度训练（amp）显著提升 batch size** - [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/07_fp16_mixed_precision_training.ipynb) | [B station](https://www.bilibili.com/video/BV1Uj411D7Xm)
- **[LLMs 实践] 08 LLM.int8 量化细节 （load_in_8bit）以及 bitsandbytes 库** - [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/LLM.int8.ipynb) | [B station](https://www.bilibili.com/video/BV1bX4y1e7a5)
- **[LLMs 实践] 09 BPE gpt2 tokenizer 与 train tokenizer** - [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/tokenizer_basics.ipynb) | [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/gpt2_train_tokenizer.ipynb) | [B station](https://www.bilibili.com/video/BV1Sk4y1P7LK)
- **[LLMs 实践] 10 预训练语料，mapping & streaming（load_dataset）** - [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/pretrain_corpus_%E5%A4%A7%E6%A8%A1%E5%9E%8B%E9%A2%84%E8%AE%AD%E7%BB%83%E8%AF%AD%E6%96%99.ipynb) | [github.com](https://github.com/chunhuizhang/bert_t5_gpt/blob/main/tutorials/dataset_dataloader.ipynb) | [B station](https://www.bilibili.com/video/BV1LF411Q7fh)
- **[LLMs 实践] 11 gradient accumulation 显存优化 trick** - [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/gradient_accumulation.ipynb) | [B station](https://www.bilibili.com/video/BV1tz4y1773d)
- **[LLMs 实践] 12 LLM SFT training （trl SFTTrainer、alpaca dataset）** - [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/llm_training_sft.ipynb) | [B station](https://www.bilibili.com/video/BV1jh4y1c713)
- **[LLMs 实践] 13 gradient checkpointing 显存优化 trick** - [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/gradient_checkpointing.ipynb) | [B station](https://www.bilibili.com/video/BV1QM4y1H7nH)
- **[LLMs 实践] 14 llama2 introduction 及 fine tune llama2（guanaco dataset）** - [huggingface.co](https://huggingface.co/blog/llama2) | [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/llama2_introduction.ipynb) | [B station](https://www.bilibili.com/video/BV1xP411x7TL)
- **[LLMs 实践] 15 llama2 源码初步（text completion & chat completion）** - [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/llama2_src_01.ipynb) | [B station](https://www.bilibili.com/video/BV1Zu4y1B7gM)
- **[personal chatgpt] trl 基础介绍：reward model，ppotrainer** - [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/trl_basics.ipynb) | [B station](https://www.bilibili.com/video/BV1zm4y1H79x)
- **[LLMs 实践] 17 llama2 源码分析（RMSNorm 与 SwiGLU）** - [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/llama2_src_02_RMSNorm_SwiGLU.ipynb) | [B station](https://www.bilibili.com/video/BV1e14y1C7G8)
- **[LLMs 实践] 18 llama2 源码分析 RoPE 相对位置编码的复数形式** - [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/llama2_src_03_RoPE_01_complex_position_encoding.ipynb) | [B station](https://www.bilibili.com/video/BV1Dh4y1P7KY)
- **[LLMs 实践] 19 llama2 源码分析 RoPE apply_rotary_emb 从绝对位置编码到相对位置编码** - [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/llama2_src_03_RoPE_apply_rotary_emb.ipynb) | [B station](https://www.bilibili.com/video/BV18u411M7j1)
- **[LLMs 实践] 20 llama2 源码分析 cache KV（keys、values cache）加速推理** - [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/llama2_src_cache_kv.ipynb) | [B station](https://www.bilibili.com/video/BV1FB4y1Z79y)
- **[LLMs 实践] 21 llama2 源码分析 GQA：Grouped Query Attention** - [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/llama2_src_grouped_query_attention.ipynb) | [B station](https://www.bilibili.com/video/BV1vc411o7fa)
- **[LLMs 实践] 221 llama2 源码分析 generate 的完整过程** - [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/llama2_src_generate.ipynb) | [B station](https://www.bilibili.com/video/BV1Ea4y1d7wx)
- **[personal chatgpt] trl reward model 与 RewardTrainer（奖励模型，分类模型）** - [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/reward_model/trl_reward_trainer.ipynb) | [B station](https://www.bilibili.com/video/BV1GZ421t7oU)
- **[personal chatgpt] peft LoRA merge pipeline（lora inject，svd）** - [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/peft/lora_inject.ipynb) | [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/peft/lora_merge.ipynb) | [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/peft/lora_svd_basics.ipynb) | [B station](https://www.bilibili.com/video/BV13A4m1w7i6)
- **[personal chatgpt] LLAMA 3 整体介绍（与 LLama 2 的不同？）** - [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/llama/llama3_0419.ipynb) | [B station](https://www.bilibili.com/video/BV15z42167yB)
- **[personal chatgpt] gpt-4o tokenizer 及特殊中文tokens（压缩词表），o200k_base** - [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/tokenizer/tokenizer_gpt4o.ipynb) | [B station](https://www.bilibili.com/video/BV1bw4m1Q7KC)
- **[personal chatgpt] trl rlhf PPOTrainer，原理分析与代码走读（OpenRLHF framework）** - [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/trl_hf/trl_ppotrainer_helloworld.ipynb) | [B station](https://www.bilibili.com/video/BV1ss421G7Nj)
- **[personal chatgpt] 从 RoPE 到 CoPE（绝对位置编码，相对位置编码，Contextual Position Encoding）** - [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/position_encoding/rope_cope.ipynb) | [B station](https://www.bilibili.com/video/BV1XS411P7Lc)
- **[personal chatgpt] Llama2 7B vs. Llama3 8B （词表、attention 及 mlp）** - [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/llama/llama2_7b_llama3_8b.ipynb) | [B station](https://www.bilibili.com/video/BV18E421A7TQ)
- **[personal chatgpt] instructGPT 中的 reward modeling，概率建模与损失函数性质** - [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/reward_model/reward_model_Bradley_Terry_model.ipynb) | [B station](https://www.bilibili.com/video/BV1GJDzYcEns)
- **[python 多进程、多线程以及协程] 01 关于进程（multiprocessing，pid、ppid）** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/threads/about_process.py) | [B station](https://www.bilibili.com/video/BV1dD4y1a7NS)
- **[python 多进程、多线程、协程] 02 用 python 多线程实现生产者消费者流程** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/threads/prod_cons.py) | [B station](https://www.bilibili.com/video/BV1YP411M7eN)
- **[python 多进程、多线程] 03 GIL、threading、多进程，concurrent.futures** - [github.com](https://github.com/chunhuizhang/full_stack/blob/main/tutorials/python/%E5%A4%9A%E8%BF%9B%E7%A8%8B_%E5%A4%9A%E7%BA%BF%E7%A8%8B/GIL_mt_mp.ipynb) | [B station](https://www.bilibili.com/video/BV1pE4depEtq)
- **[模型拓扑接口] 经典 RNN 模型（一）模型参数及训练参数的介绍** - [pytorch.org](https://pytorch.org/docs/stable/generated/torch.nn.RNN.html) | [B station](https://www.bilibili.com/video/BV13v4y1P7Cd)
- **[模型拓扑结构] pytorch 注册钩子函数（register_forward_hook）实现对各个层（layer）输入输出 shape 的查看** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/tree/master/learn_torch/utils) | [B station](https://www.bilibili.com/video/BV1YL4y1A7oY)
- **【计算机视觉】cnn/maxpool 输入输出 shape 的变化与kernel size、pool size、stride size，padding=same** - [B station](https://www.bilibili.com/video/BV1oJ411d73Q)
- **[pytorch 网络拓扑结构] 深度理解 nn.BatchNorm1d** - [pytorch.org](https://pytorch.org/docs/stable/generated/torch.nn.BatchNorm1d.html) | [B station](https://www.bilibili.com/video/BV19B4y1q743)
- **[pytorch 网络模型结构] 深入理解 nn.BatchNorm1d/2d 计算过程** - [pytorch.org](https://pytorch.org/docs/stable/generated/torch.nn.BatchNorm2d.html) | [B station](https://www.bilibili.com/video/BV1dv4y1M79T)
- **[pytorch 模型拓扑结构] 深入理解 nn.BatchNorm2d/3d** - [pytorch.org](https://pytorch.org/docs/stable/generated/torch.nn.BatchNorm2d.html) | [B station](https://www.bilibili.com/video/BV1vY411N7gb)
- **[pytorch 网络拓扑结构] 深入理解 nn.LayerNorm 的计算过程** - [B station](https://www.bilibili.com/video/BV1Fa411p7W3)
- **[pytorch 模型拓扑结构] 深入理解 nn.CrossEntropyLoss 计算过程（nn.NLLLoss(nn.LogSoftmax))** - [pytorch.org](https://pytorch.org/docs/stable/generated/torch.nn.CrossEntropyLoss.html) | [pytorch.org](https://pytorch.org/docs/stable/generated/torch.nn.NLLLoss.html) | [B station](https://www.bilibili.com/video/BV1NY4y1E76o)
- **[pytorch 模型拓扑结构] pytorch 矩阵乘法大全（torch.dot, mm, bmm, @, *, matmul）** - [B station](https://www.bilibili.com/video/BV1za411S7sA)
- **[pytorch 神经网络拓扑结构] pad_sequence/pack_padded_sequence 时序模型如何处理不定长输入** - [pytorch.org](https://pytorch.org/docs/stable/generated/torch.nn.utils.rnn.pad_sequence.html) | [pytorch.org](https://pytorch.org/docs/stable/generated/torch.nn.utils.rnn.pad_packed_sequence.html) | [B station](https://www.bilibili.com/video/BV1A94y1D76b)
- **[pytorch模型拓扑结构] nn.MultiheadAttention, init/forward, 及 query，key，value 的计算细节** - [B station](https://www.bilibili.com/video/BV1Za411G782)
- **[pytorch 网络模型结构] batchnorm train 及 eval 模式的差异及（running_mean, running_var）的计算细节** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/tree/master/learn_torch/tutorials) | [B station](https://www.bilibili.com/video/BV1n14y1v7ap)
- **[pytorch] [求导练习] 01 sigmoid 函数自动求导练习（autograd，单变量，多变量 multivariables 形式）** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/learn_torch/grad/01_sigmoid.ipynb) | [B station](https://www.bilibili.com/video/BV1rW4y1N7ZU)
- **[pytorch] [求导练习] 02 softmax 函数自动求导练习（autograd，Jacobian matrix）** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/learn_torch/grad/02_softmax.ipynb) | [B station](https://www.bilibili.com/video/BV1gW4y1K7Du)
- **[pytorch] [求导练习] 03 计算图（computation graph）及链式法则（chain rule）反向传播过程** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/learn_torch/grad/03_computation_graph.ipynb) | [B station](https://www.bilibili.com/video/BV1hv4y1B7pE)
- **[pytorch] [求导练习] 04 前向计算与反向传播与梯度更新（forward，loss.backward(), optimizer.step）** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/learn_torch/grad/04_backward_step.ipynb) | [B station](https://www.bilibili.com/video/BV13G4y1m7MC)
- **[pytorch 模型拓扑结构] 深入理解 nn.BCELoss 计算过程及 backward 及其与 CrossEntropyLoss 的区别与联系** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/learn_torch/loss/01_BCELoss_binary_cross_entropy.ipynb) | [B station](https://www.bilibili.com/video/BV1H24y1e7oV)
- **[pytorch] [求导练习] 05 计算图（computation graph）构建细节之 inplace operation（data与detach）** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/learn_torch/grad/05_torch_variables_grad_inplace_operation.ipynb) | [zhuanlan.zhihu.com](https://zhuanlan.zhihu.com/p/38475183) | [B station](https://www.bilibili.com/video/BV1YL411Z7Rj)
- **[pytorch] [求导练习] 06 计算图（computation graph）细节之 retain graph（multi output/backwar）** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/learn_torch/grad/06_retain_graph.ipynb) | [B station](https://www.bilibili.com/video/BV1o24y1b7tk)
- **[pytorch] 深入理解 torch.gather 及 dim 与 index 的关系** - [zhuanlan.zhihu.com](https://zhuanlan.zhihu.com/p/352877584) | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/learn_torch/basics/torch.gather.ipynb) | [B station](https://www.bilibili.com/video/BV1YY4y1Q72M)
- **[pytorch] 深入理解 nn.KLDivLoss（kl 散度） 与 nn.CrossEntropyLoss（交叉熵）** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/learn_torch/loss/02_kl_divergence_cross_entropy.ipynb) | [pytorch.org](https://pytorch.org/docs/stable/generated/torch.nn.KLDivLoss.html) | [pytorch.org](https://pytorch.org/docs/stable/generated/torch.nn.CrossEntropyLoss.html) | [B station](https://www.bilibili.com/video/BV1Nx4y1N7qb)
- **[pytorch] 激活函数（梯度消失）sigmoid，clamp，relu（sparse representation，dying relu）** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/learn_torch/basics/activate_fn_gradient_sigmoid_relu_clamp.ipynb) | [B station](https://www.bilibili.com/video/BV1qh411u7Ab)
- **[pytorch] 激活函数，从 ReLU、LeakyRELU 到 GELU 及其梯度（gradient）（BertLayer，FFN，GELU）** - [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/nn_basics/02_gelu_grad.ipynb) | [paperswithcode.com](https://paperswithcode.com/method/gelu) | [B station](https://www.bilibili.com/video/BV1Wg4y177py)
- **[pytorch] nn.Embedding 前向查表索引过程与 one hot 关系及 max_norm 的作用** - [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/nn_basics/04_embedding_details.ipynb) | [B station](https://www.bilibili.com/video/BV1wm4y187Cr)
- **[pytorch] torch.einsum 到索引到矩阵运算（index、shape、dimension、axis）** - [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/nn_basics/einsum_numpy_torch.ipynb) | [B station](https://www.bilibili.com/video/BV1Fx4y1X72e)
- **[pytorch] Tensor shape 变化 view 与 reshape（contiguous 的理解）** - [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/nn_basics/shape_modified.ipynb) | [B station](https://www.bilibili.com/video/BV1Zw411y7Ks)
- **[pytorch] Tensor 轴（axis）交换，transpose（转置）、swapaxes、permute** - [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/nn_basics/axis_dim_processing.ipynb) | [B station](https://www.bilibili.com/video/BV1pN4y117rD)
- **[pytorch] 多项式分布及采样（torch.multinomial, torch distribution Categorical）** - [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/nn_basics/multinomail_categorical.ipynb) | [B station](https://www.bilibili.com/video/BV1Vu4y1p7dv)
- **[pytorch] torch.nn.Bilinear 计算过程与 einsum（爱因斯坦求和约定）** - [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/nn_basics/einsum_bilinear.ipynb) | [B station](https://www.bilibili.com/video/BV1De411X7ei)
- **[pytorch 番外] Tensorboard 与计算图初步（算子与 ATen）** - [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/nn_basics/tensorboard_graph.ipynb) | [B station](https://www.bilibili.com/video/BV1Vv411F7tG)
- **[pytorch] F.binary_cross_entropy（二分类） 与 F.cross_entropy（多分类）** - [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/nn_basics/bce_loss_cross_entropy.ipynb) | [B station](https://www.bilibili.com/video/BV1AN41177Jo)
- **[einops 01] einsum 补充与 einops 初步（实现 ViT 的图像分块）** - [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/nn_basics/einsum_supp_einops_%E5%88%9D%E6%AD%A5.ipynb) | [B station](https://www.bilibili.com/video/BV11J4m1s7AU)
- **[PyTorch] Dropout 基本原理（前向计算与自动求导）** - [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/nn_basics/torch_dropout.ipynb) | [B station](https://www.bilibili.com/video/BV1Xz421r7L1)
- **[pytorch 计算图] retain_graph 获取非叶子节点的 grad** - [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/nn_basics/grad/retain_grad_retatin_graph.ipynb) | [B station](https://www.bilibili.com/video/BV1DH4y1N7it)
- **k-Sparse AutorEncoder 与大语言模型可解释性研究（openai、claude），top-K 求导** - [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/nn_basics/grad/sae_topK.ipynb) | [B station](https://www.bilibili.com/video/BV1sx4y1J76b)
- **[pytorch] BN、LN、RMSNorm 及 pre LN vs. post LN 对比，标准化** - [github.com](https://github.com/chunhuizhang/llm_aigc/blob/main/tutorials/nn_basics/normalization.ipynb) | [B station](https://www.bilibili.com/video/BV13q49eaERj)
- **[LLMs tuning] 01 trl SFTTrainer 中的 formatting_func 与 DataCollatorForCompletion** - [github.com](https://github.com/chunhuizhang/llms_tuning/blob/main/tutorials/finetune/trl/collate_fn_formatting_func.ipynb) | [B station](https://www.bilibili.com/video/BV1bn4y1f7wF)
- **[LLMs tuning] 02 accelerate ddp 与 trl SFTTrainer** - [github.com](https://github.com/chunhuizhang/llms_tuning/blob/main/tutorials/accelerate_ds_fsdp/accelerate_ddp.ipynb) | [B station](https://www.bilibili.com/video/BV1V4421S75Q)
- **[LLMs tuning] 03 llama3-8B instruct SFT on Financial RAG** - [github.com](https://github.com/chunhuizhang/llms_tuning/blob/main/tutorials/finetune/examples/finetune_llama3_for_RAG.ipynb) | [B station](https://www.bilibili.com/video/BV1Yx4y147t4)
- **[LLMs tuning] 04 optimizer Trainer 优化细节（AdamW，grad clip、Grad Norm）等** - [github.com](https://github.com/chunhuizhang/llms_tuning/blob/main/tutorials/optimization_details.ipynb) | [B station](https://www.bilibili.com/video/BV1Ri421h7qV)
- **[LLMs tuning] 05 StackLlama、SFT+DPO（代码组织、数据处理，pipeline）** - [github.com](https://github.com/chunhuizhang/llms_tuning/blob/main/tutorials/finetune/trl-examples/llama_stackexchange.ipynb) | [B station](https://www.bilibili.com/video/BV1gE421A7Pm)
- **[LLMs tuning] 06 多轮对话 qlora SFT（Multi-turn Conversation）** - [github.com](https://github.com/chunhuizhang/llms_tuning/blob/main/tutorials/chat/chat_sft_mistral.ipynb) | [B station](https://www.bilibili.com/video/BV1ygHFeQEE5)
- **[pytorch 强化学习] 01 认识环境（environment，gym.Env）以及 CartPole-v0/v1 环境** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/rl/tutorials/01_env.ipynb) | [gymlibrary.dev](https://www.gymlibrary.dev/environments/classic_control/cart_pole/) | [B station](https://www.bilibili.com/video/BV1tP411M7dT)
- **[pytorch 强化学习] 02 将 env rendering 保存为 mp4/gif（以 CartPole 为例，mode='rgb_array'）** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/tree/master/rl/tutorials) | [B station](https://www.bilibili.com/video/BV1JW4y1g7AH)
- **[pytorch 强化学习] 03 动手写迷宫环境（maze env）状态及动作策略初步（及动画保存）** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/rl/tutorials/03_maze.ipynb) | [B station](https://www.bilibili.com/video/BV1Ye411P7Sw)
- **[pytorch 强化学习] 04 迷宫环境（maze environment）封装 MazeEnv、Agent 类** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/rl/tutorials/03_MazeEnv_Agent.ipynb) | [B station](https://www.bilibili.com/video/BV1pD4y1a7Am)
- **[pytorch 强化学习] 05 迷宫环境（maze environment）策略梯度（Policy Gradient）求解** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/rl/tutorials/04_maze_env_policy_gradient.ipynb) | [B station](https://www.bilibili.com/video/BV1es4y1a7Q2)
- **[pytorch 强化学习] 06 迷宫环境（maze environment）SARSA（Q-table，value iteration）求解** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/rl/tutorials/05_value_iteration_sarsa.ipynb) | [B station](https://www.bilibili.com/video/BV1Us4y1h7TZ)
- **[pytorch 强化学习] 07 迷宫环境（maze environment）Q Learning（value iteration）求解（策略关闭 off）** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/rl/tutorials/06_value_iteration_q_learning.ipynb) | [B station](https://www.bilibili.com/video/BV1LY4y127XV)
- **[pytorch 强化学习] 08 CartPole Q learning 连续状态离散化（digitize 分桶）及 display_frame_as_gif** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/rl/tutorials/07_cart_pole_digitize_space.ipynb) | [gymlibrary.dev](https://www.gymlibrary.dev/environments/classic_control/cart_pole/) | [B station](https://www.bilibili.com/video/BV1Lo4y1k7Mz)
- **[pytorch 强化学习] 09 （逐行写代码）CartPole Q learning 基于连续状态离散化（digitize 分桶）** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/rl/tutorials/08_cart_pole_q_learning.ipynb) | [B station](https://www.bilibili.com/video/BV1Yv4y187jP)
- **[pytorch 强化学习] 10 从 Q Learning 到 DQN（experience replay 与 huber loss / smooth L1）** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/rl/tutorials/09_dqn_cart_pole_outline.ipynb) | [pytorch.org](https://pytorch.org/tutorials/intermediate/reinforcement_q_learning.html) | [B station](https://www.bilibili.com/video/BV1Fs4y1p75P)
- **[pytorch 强化学习] 11 逐行写代码实现 DQN（ReplayMemory，Transition，DQN as Q function）** - [pytorch.org](https://pytorch.org/tutorials/intermediate/reinforcement_q_learning.html) | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/rl/tutorials/10_dqn_cart_pole.ipynb) | [B station](https://www.bilibili.com/video/BV1XP411Z7N4)
- **[pytorch 强化学习] 12 逐行写代码实现 DQN 完全体** - [pytorch.org](https://pytorch.org/tutorials/intermediate/reinforcement_q_learning.html) | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/rl/tutorials/10_dqn_cart_pole.ipynb) | [B station](https://www.bilibili.com/video/BV1t84y1w7BC)
- **[pytorch 强化学习] 13 基于 pytorch 神经网络实现 policy gradient（REINFORCE）求解 CartPole** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/rl/tutorials/11_deep_policy_gradient_on_cartpole.ipynb) | [cs.toronto.edu](http://www.cs.toronto.edu/~tingwuwang/REINFORCE.pdf) | [lilianweng.github.io](https://lilianweng.github.io/posts/2018-04-08-policy-gradient/) | [B station](https://www.bilibili.com/video/BV1eg4y1s7TN)
- **[强化学习基础 01] MDP 基础（概率转移，与POMDP、I-POMDP）** - [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/drl/mdp_basics.ipynb) | [B station](https://www.bilibili.com/video/BV1V94y1E7Pi)
- **[强化学习基础 02] MDP价值迭代算法（value iteration，V(s), Q(s,a), pi(s)）** - [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/drl/mdps_value_iteration.ipynb) | [B station](https://www.bilibili.com/video/BV1ow41147Nv)
- **[强化学习基础 03] 多臂老虎机（Multi-Armed Bandit）与 UCB** - [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/drl/multi_armed_bandits.ipynb) | [B station](https://www.bilibili.com/video/BV1Ga4y167ux)
- **[mcts] 01 mcts 基本概念基本原理（UCB）及两个示例** - [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/drl/mcts/mcts_01_intro_bascis.ipynb) | [B station](https://www.bilibili.com/video/BV1zC411h7B8)
- **[mcts] 02 mcts from scartch（UCTNode，uct_search, pUCT，树的可视化）** - [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/drl/mcts/mcts_02_from_scartch.ipynb) | [B station](https://www.bilibili.com/video/BV1ZA4m1P7RV)
- **[DRL] 从策略梯度到 TRPO（Lagrange Duality，拉格朗日对偶性）** - [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/drl/policy_based/pg_trpo_ppo.ipynb) | [B station](https://www.bilibili.com/video/BV1hD421K7gG)
- **[DRL] 从 TRPO 到 PPO（PPO-penalty，PPO-clip）** - [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/drl/policy_based/pg_trpo_ppo.ipynb) | [B station](https://www.bilibili.com/video/BV11J4m137fY)
- **[RLHF] 从 PPO rlhf 到 DPO，公式推导与原理分析** - [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/trl_hf/trl_dpo.ipynb) | [github.com](https://github.com/chunhuizhang/personal_chatgpt/blob/main/tutorials/trl_hf/dpo_math.ipynb) | [B station](https://www.bilibili.com/video/BV1pM4m1U75K)
- **【运筹】运筹决策系统的搭建，从决策变量、中间变量到约束及目标，从求解到无解时约束的放松** - [B station](https://www.bilibili.com/video/BV18L4y1B7HM)
- **【ortools】【cpmodel】八皇后问题的约束规划求解（leetcode 51/52 n-queens）** - [developers.google.cn](https://developers.google.cn/optimization/cp/queens?hl=zh-cn) | [B station](https://www.bilibili.com/video/BV1Si4y1L7gD)
- **【python 运筹优化】scipy.optimize.minimize 接口介绍（method、jacobian、hessian）| 有约束非线性优化** - [docs.scipy.org](https://docs.scipy.org/doc/scipy/reference/generated/scipy.optimize.minimize.html) | [scipy-lectures.org](https://scipy-lectures.org/advanced/mathematical_optimization/) | [B station](https://www.bilibili.com/video/BV1nA4y197mu)
- **【python 运筹优化】scipy.optimize.minimize 使用** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/nlp/demo.py) | [docs.scipy.org](https://docs.scipy.org/doc/scipy/reference/generated/scipy.optimize.minimize.html) | [B station](https://www.bilibili.com/video/BV1nL4y157iQ)
- **【python 运筹】混合整数规划 | MIP | ortools | SCIP | CBC** - [B station](https://www.bilibili.com/video/BV1jq4y1z7Rf)
- **【Python 运筹实战】Python实战 |指派问题assignment problem| 匈牙利算法（Hungarian algorithm）** - [B station](https://www.bilibili.com/video/BV1dR4y1t756)
- **【Python 运筹实战】指派问题assignment problem| 匈牙利算法（Hungarian algorithm）| scipy.optimize** - [B station](https://www.bilibili.com/video/BV1KS4y1R7eY)
- **【运筹】0/1二值逻辑整数规划约束的描述与表达，conditional/multiple choices以及互斥约束建模** - [B station](https://www.bilibili.com/video/BV1Et4y167rm)
- **【运筹】【整数规划】outer approximation 求解 MINLP及示例** - [optimization.mccormick.northwestern.edu](https://optimization.mccormick.northwestern.edu/index.php/Outer-approximation_(OA) | [science.osti.gov](https://science.osti.gov/-/media/ascr/pdf/workshops-conferences/mathtalks/Leyffer.pdf) | [B station](https://www.bilibili.com/video/BV1mZ4y157To)
- **[python 运筹优化] 系统性介绍 scipy 中的非线性最小二乘（NNLS, curve_fit, least_squares）** - [github.com](https://github.com/chunhuizhang/ortools_tutorials/blob/main/tutorials/scipy.optimize/least_square_curve_fit.ipynb) | [B station](https://www.bilibili.com/video/BV1GQ4y1H78A)
- **[优化算法] 梯度下降、共轭梯度、牛顿法、逆牛顿法（BFGS）** - [github.com](https://github.com/chunhuizhang/ortools_tutorials/blob/main/tutorials/scipy.optimize/Quasi-Newton.ipynb) | [B station](https://www.bilibili.com/video/BV1CD421n73k)
- **[全栈算法工程师系列] python deepcopy（深拷贝，clone，克隆）性能优化（浅拷贝+递归）** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/basics/opt/copy_test.ipynb) | [cloud.tencent.com](https://cloud.tencent.com/developer/article/1008984) | [xie.infoq.cn](https://xie.infoq.cn/article/71e69c4296f307132cac4d367) | [B station](https://www.bilibili.com/video/BV1T14y1b7ve)
- **[全栈算法工程师] 如何把github当做个人笔记记录站点，git与github（本地与远端，local/remote(origin)）** - [github.com](https://github.com/chunhuizhang/deep_learning_notes) | [B station](https://www.bilibili.com/video/BV1uG4y1a7gz)
- **[全栈算法工程师] 用 subprocess.Popen 执行 linux 命令** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/basics/python/linux_shell.py) | [B station](https://www.bilibili.com/video/BV1nd4y1o7Xk)
- **【Python番外】可变对象（mutable）vs.不可变对象（immuable），可hash对象（hashable）vs.不可hash对象（unhashab）** - [B station](https://www.bilibili.com/video/BV1C7411R72h)
- **【python番外】python函数式编程与闭包与yield关键字** - [B station](https://www.bilibili.com/video/BV1mJ411q7no)
- **【python app 开发】01 使用 tkinter 及 pyinstaller 制作一个简单的日期管理软件** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/app/date_demo2.py) | [B station](https://www.bilibili.com/video/BV1DP4y127Uh)
- **【python app 开发】02 使用 tkinter 及 PIL (pillow) 制作图像九宫格** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/app/learn/splits.py) | [B station](https://www.bilibili.com/video/BV1HW4y1W7KV)
- **[全栈深度学习] 02 vscode remote（远程）gpus 服务器开发调试 debugger（以 nanoGPT 为例）** - [github.com](https://github.com/chunhuizhang/full_stack/blob/main/tutorials/02_vscode_remote_server_development.ipynb) | [B station](https://www.bilibili.com/video/BV1xs4y1Q7bs)
- **[全栈深度学习] 01 docker 工具的基本使用及 nvidia cuda pytorch 镜像** - [github.com](https://github.com/chunhuizhang/full_stack/blob/main/tutorials/01_docker.ipynb) | [B station](https://www.bilibili.com/video/BV19s4y1X7Zx)
- **[工具的使用] python jupyter 环境安装配置拓展（nbextension）（ExcecuteTime：执行时间，Table of Content）** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/fun_tools/jupyter_extentisons.md) | [towardsdatascience.com](https://towardsdatascience.com/jupyter-notebook-extensions-517fa69d2231) | [B station](https://www.bilibili.com/video/BV1u24y147bo)
- **[python 全栈] python 装饰器（decorator）及 functools.cache** - [github.com](https://github.com/chunhuizhang/full_stack/blob/main/tutorials/python/decorator_basics_functools.ipynb) | [B station](https://www.bilibili.com/video/BV1v8411R7tf)
- **[全栈算法] docker nvidia pytorch gpu 环境及容器操作，端口号映射** - [github.com](https://github.com/chunhuizhang/full_stack/blob/main/tutorials/docker_gpu_torch_%E6%B7%B1%E5%BA%A6%E5%AD%A6%E4%B9%A0%E7%8E%AF%E5%A2%83.ipynb) | [B station](https://www.bilibili.com/video/BV1Su4y1e7fc)
- **[python 全栈] 正则表达式初步与指南** - [github.com](https://github.com/chunhuizhang/full_stack/blob/main/tutorials/%E6%AD%A3%E5%88%99_re_regex.ipynb) | [B station](https://www.bilibili.com/video/BV1kg4y1d768)
- **[全栈 docker] 03 docker 容器开发（start，exec）及 commit、save、load 持久化，docker vscode** - [github.com](https://github.com/chunhuizhang/full_stack/blob/main/tutorials/docker/docker_modify_save_load.ipynb) | [B station](https://www.bilibili.com/video/BV1AF4m1w7Fo)
- **[leetcode reviews] 01 计算思维与刷题方法** - [github.com](https://github.com/chunhuizhang/leetcode_reviews/blob/main/introduction.ipynb) | [github.com](https://github.com/chunhuizhang/leetcode_reviews/blob/main/dp%E5%8A%A8%E6%80%81%E8%A7%84%E5%88%92/62.%20Unique%20Paths.ipynb) | [B station](https://www.bilibili.com/video/BV1rP411s7T5)
- **[leetcode reviews] 62 unique paths, dfs + cache, O(m), O(n)** - [github.com](https://github.com/chunhuizhang/leetcode_reviews/blob/main/%E9%80%92%E5%BD%92%E4%B8%8E%E5%9B%9E%E6%BA%AF/62.%20Unique%20Paths.ipynb) | [github.com](https://github.com/chunhuizhang/leetcode_reviews/blob/main/dp%E5%8A%A8%E6%80%81%E8%A7%84%E5%88%92/62.%20Unique%20Paths.ipynb) | [B station](https://www.bilibili.com/video/BV1hG411Z7Sf)
- **[leetcode reviews] 207. Course Schedule（图算法，拓扑排序，DAG 环检测）** - [github.com](https://github.com/chunhuizhang/leetcode_reviews/blob/main/%E6%95%B0%E6%8D%AE%E7%BB%93%E6%9E%84/%E5%9B%BE%EF%BC%88graph%EF%BC%89/topological_sort.ipynb) | [B station](https://www.bilibili.com/video/BV1vN4y1Q7Q4)
- **[leetcode reviews] FSM 有限状态机导论（交通灯，考拉兹猜想 Collatz conjecture）** - [github.com](https://github.com/chunhuizhang/leetcode_reviews/blob/main/%E5%85%B6%E4%BB%96/FSM_%E6%9C%89%E9%99%90%E7%8A%B6%E6%80%81%E6%9C%BA.ipynb) | [B station](https://www.bilibili.com/video/BV1Nu411M7za)
- **[leetcode reviews] list of list 矩阵转置与旋转（transpose & rotate）** - [github.com](https://github.com/chunhuizhang/leetcode_reviews/blob/main/%E6%95%B0%E6%8D%AE%E7%BB%93%E6%9E%84/grid_world/48.%20Rotate%20Image.ipynb) | [B station](https://www.bilibili.com/video/BV13C4y137pJ)
- **【程序员说会计】breakeven | 盈亏平衡点 | 总营收（total revenue）| 总成本（total cost）| 边际贡献** - [B station](https://www.bilibili.com/video/BV1m34y1X7Wb)
- **【会计】个人所得税速算扣除数的计算及推导** - [B station](https://www.bilibili.com/video/BV13y4y177N1)
- **【Python 金融】72法则 | 本金翻倍 | 每年复利 1 次 | 每年复利多次 | 连续复利 | 泰勒级数 | 麦克劳林公式** - [B station](https://www.bilibili.com/video/BV1pZ4y197vZ)
- **【金融数学】中央银行法定准备金率与货币乘数|等比数列** - [B station](https://www.bilibili.com/video/BV1iq4y1R7Ez)
- **[程序员说金融] 等额本金概念及计算（月供还款分析：月供本金，月供利息）** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/finance/equal_principal.py) | [cmbchina.com](https://www.cmbchina.com/CmbWebPubInfo/Cal_Loan_Per.aspx?chnl=dkjsq) | [zhuanlan.zhihu.com](https://zhuanlan.zhihu.com/p/37403083) | [B station](https://www.bilibili.com/video/BV1SY4y1w7XN)
- **[程序员说金融] 等额本息概念及计算（月供还款分析：月供本金，月供利息）** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/finance/equal_principal_interest.py) | [baike.baidu.com](https://baike.baidu.com/item/) | [cmbchina.com](https://www.cmbchina.com/CmbWebPubInfo/Cal_Loan_Per.aspx?chnl=dkjsq) | [B station](https://www.bilibili.com/video/BV1CB4y1r7Lr)
- **【excel】计算白条花呗借呗分期付款的真实IRR（Internal Rate of Return）** - [iyiou.com](https://www.iyiou.com/p/85347.html) | [B station](https://www.bilibili.com/video/BV17D4y197ET)
- **[程序员说金融] 跨期投资项目的比较，NPV 与 IRR 的概念及计算（excel 函数）** - [github.com](https://github.com/chunhuizhang/deep_learning_notes/blob/main/misc/) | [B station](https://www.bilibili.com/video/BV1wg411k7ie)
- **[程序员说金融] 对数回报率（收益率）及其性质（可加性，负对称性，及泰勒展开下的近似相等）** - [B station](https://www.bilibili.com/video/BV11B4y1V7Bj)
- **[程序员说金融] LPR（基准利率）概念（数据获取），你的房贷利率降了吗** - [github.com](https://github.com/chunhuizhang/financial_programming/blob/main/LPR(Loan-Prime-Rate) | [B station](https://www.bilibili.com/video/BV1934y137ya)
- **【数值计算】newton's method 牛顿法求极值点，求函数的零点（求根），图解法** - [B station](https://www.bilibili.com/video/BV1yD4y1o7Po)
- **【数值计算】牛顿迭代法（Newton's method，Newton-Raphson method，牛顿-拉夫逊（拉弗森））计算二次方根（sqrt）三次方根** - [B station](https://www.bilibili.com/video/BV16t4y117Me)
- **[数值计算] 一阶泰勒展开快速计算一个数的平方根** - [B station](https://www.bilibili.com/video/BV1V24y1676f)
- **[数值计算] 快速计算、妙算对数，之对数表（logarithm table）的使用，如何将任意一个数转换为10-99，或0-0.99之间的可查表形式** - [icap.org.pk](https://icap.org.pk/files/per/students/exam/notices/log-table.pdf) | [B station](https://www.bilibili.com/video/BV1M341197gj)
- **[数值计算] 快速计算、秒算大数乘除运算，对数变换将乘除变为加减，再通过查表（logarithm table）获得10-99之间的对数值** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/numerical/pdfs/log-table.pdf) | [B station](https://www.bilibili.com/video/BV1Wd4y1H7oW)
- **[animation & rendering] matplotlib funcanimation 多重动画绘制（multiple lines plot）** - [matplotlib.org](https://matplotlib.org/stable/api/animation_api.html) | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/vis/animation/line_plot_ani.py) | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/vis/animation/multi_line_plot_ani.py) | [B station](https://www.bilibili.com/video/BV1pD4y1b7c2)
- **[pygame Astar寻路算法可视化] 01 pygame 初始化及 grid world 创建** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/path_finding/tutorials/01_init_grid_world.py) | [B station](https://www.bilibili.com/video/BV1984y1e7Yn)
- **[pygame Astar寻路算法可视化] 02 鼠标事件响应（前台事件与后台处理）** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/path_finding/tutorials/02_event_frontend_backend.py) | [B station](https://www.bilibili.com/video/BV1bG4y1878o)
- **[pygame Astar寻路算法可视化] 03 A star算法初始化及有效邻域的计算** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/path_finding/tutorials/03_astar.py) | [B station](https://www.bilibili.com/video/BV13Y411f7VC)
- **[pygame Astar寻路算法可视化] 04 A star 算法优先级队列，f = g + h** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/path_finding/tutorials/03_astar.py) | [B station](https://www.bilibili.com/video/BV1TG4y1b7FA)
- **[数据可视化] 绘制 z=f(x, y) （三维空间中的 surface）** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/vis/animation/tutorials/01_z%3Df(x%2Cy) | [B station](https://www.bilibili.com/video/BV1tY411y7N9)
- **[数据可视化] 绘制交互式 3d plot（interactive 3d plot, Axes3d） z=f(x, y) （三维空间中的 surface）** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/vis/animation/tutorials/02_interactive_3d_plot.ipynb) | [B station](https://www.bilibili.com/video/BV1KR4y1a7Xe)
- **【搜索算法】【search】01 python-astar 图上搜索（graph search）f(n)=g(n)+h(n)** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/search/atar_demo.py) | [B station](https://www.bilibili.com/video/BV1b44y197Jd)
- **【搜索算法】【search】02 爬山算法（hill climbing）二维离散空间上的邻域搜索** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/search/02_hill_climbing_discrete_space.ipynb) | [B station](https://www.bilibili.com/video/BV1p8411N7BX)
- **[python nlp] 01 词频分析与 Zipf law 齐夫定律（log-log plot）** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/nlp/tutorials/01_word_freq_prob_zipf_law.ipynb) | [norvig.com](http://norvig.com/ngrams/) | [norvig.com](http://norvig.com/big.txt) | [regexr.com](https://regexr.com/) | [B station](https://www.bilibili.com/video/BV1EM411h75p)
- **[概率统计] 将对数几率（logodds）引入到贝叶斯公式（bayes），后验对数几率=先验对数几率+似然对数几率** - [B station](https://www.bilibili.com/video/BV1DN4y1T7et)
- **【手推公式】logistic regression 及其与 linear regression 的区别，对数线性与对数几率** - [B station](https://www.bilibili.com/video/BV1zz4y1R7nr)
- **【统计】箱线图（boxplot）进行异常点检测（outlier detection），为什么定义为 1.5倍的 IQR** - [towardsdatascience.com](https://towardsdatascience.com/why-1-5-in-iqr-method-of-outlier-detection-5d07fdc82097) | [B station](https://www.bilibili.com/video/BV1WR4y1g7Yp)
- **【数据处理】数据变换的三种形式，（几率）对数线性（log linear）、线性对数（linear log）、双对数log-log** - [journals.physiology.org](https://journals.physiology.org/doi/full/10.1152/advan.00018.2018) | [medium.com](https://medium.com/@kyawsawhtoon/log-transformation-purpose-and-interpretation-9444b4b049c9) | [B station](https://www.bilibili.com/video/BV1LZ4y1N78x)
- **【数据变换】【可视化】xscale('log') , yscale('log'), log-log plot 非线性转换为线性** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/data_science/tutorials/01_log_scale.ipynb) | [B station](https://www.bilibili.com/video/BV1XK411y7YR)
- **【python 信号与系统】01 np.convolve 一维离散卷积（三种mode：full、valid、same）** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/tree/master/signal_system) | [B station](https://www.bilibili.com/video/BV1y44y1Q7MB)
- **【信号与系统】数值乘法与序列卷积，级数乘法与Cauchy 乘法** - [zhuanlan.zhihu.com](https://zhuanlan.zhihu.com/p/30986744) | [B station](https://www.bilibili.com/video/BV1Wh411f7C5)
- **【python 信号与系统】02 scipy.signal.convolve2d 二维（图像）卷积及其与 CNN 的区别** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/tree/master/signal_system) | [B station](https://www.bilibili.com/video/BV1NW4y1W7zw)
- **【python 信号与系统】1维卷积实现滑动求和/滑动平均（moving sum，moving average）** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/tree/master/signal_system) | [B station](https://www.bilibili.com/video/BV15M411k7Wg)
- **【flask web 核心】01 认识 request，response 以及 cookie** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/web/flask_proj/tut01/app.py) | [B station](https://www.bilibili.com/video/BV1t84y1r7Zg)
- **[调包侠] 使用深度学习模型（paddlehub - humanseg）进行人物提取（前景提取、抠图）** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/cv/seg/human_seg_0521.ipynb) | [B station](https://www.bilibili.com/video/BV1sr4y14745)
- **[调包侠] 使用 PyTorch Swin Transformer 完成图像分类** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/tree/master/pretrained/swin) | [B station](https://www.bilibili.com/video/BV1na41177B2)
- **[调包侠] tencent ailab 中文语料 embedding vector（word2vec）** - [ai.tencent.com](https://ai.tencent.com/ailab/nlp/zh/embedding.html) | [ai.tencent.com](https://ai.tencent.com/ailab/nlp/zh/download.html) | [B station](https://www.bilibili.com/video/BV1dr4y1u76M)
- **[调包侠] 04 使用预训练模型进行图像特征向量提取（image feature extractor，img2vec）并进行相似性计算** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/tree/master/cv/img2vec) | [B station](https://www.bilibili.com/video/BV1WY411N7fR)
- **[调包侠] 使用 gensim 完成 word2vec 的计算，及 model.most_similar 的计算过程（positive，negative）** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/nlp/gensim_demo/w2c.py) | [B station](https://www.bilibili.com/video/BV1WF411A7Ah)
- **【数据可视化】【excel】漏斗分析-漏斗图（funnel）与金字塔图（pyramid）的区别和联系** - [B station](https://www.bilibili.com/video/BV1qE411g7h9)
- **[不务正业] 科研的起点 - 修改 Python 三方库/包源码** - [github.com](https://github.com/dexplo/bar_chart_race) | [B station](https://www.bilibili.com/video/BV1xB4y1Y7BB)
- **[面向 cv 的 ffmpeg] （1）ffmpeg.probe 获取视频基本信息** - [github.com](https://github.com/kkroening/ffmpeg-python) | [github.com](https://github.com/kkroening/ffmpeg-python/tree/master/examples) | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/tree/master/py_ffmpeg) | [B station](https://www.bilibili.com/video/BV18a411n7hX)
- **[面向 cv 的 ffmpeg] （2）将视频转换为 4D numpy.ndarray** - [github.com](https://github.com/kkroening/ffmpeg-python) | [github.com](https://github.com/kkroening/ffmpeg-python/tree/master/examples) | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/tree/master/py_ffmpeg) | [B station](https://www.bilibili.com/video/BV1pW4y1S7Sb)
- **[深度学习面试系列] L2-L1正则的 MLE/MAP 概率解释** - [bjlkeng.github.io](https://bjlkeng.github.io/posts/probabilistic-interpretation-of-regularization/#id12) | [B station](https://www.bilibili.com/video/BV1ZW4y1C7wq)
- **[计算几何] 从几何到代数 | 投影长度的计算（law of cosine 与 projection formula）** - [B station](https://www.bilibili.com/video/BV1pY4y157KW)
- **【约束满足问题】AIMA | Chap 6 | CSP | AC-3 | Arc Consistency** - [en.wikipedia.org](https://en.wikipedia.org/wiki/AC-3_algorithm) | [B station](https://www.bilibili.com/video/BV1Ku41167bs)
- **【约束规划】ortools | cpmodel | model.AddBoolOr | model.AddImplication | 实现逻辑表达式及逻辑约束** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/cp/binary_encodings.py) | [google.github.io](https://google.github.io/or-tools/java/classcom_1_1google_1_1ortools_1_1sat_1_1CpModel.html) | [B station](https://www.bilibili.com/video/BV1g34y1v747)
- **【运筹优化】CP-SAT | cpmodel | CSP | boolean logic | channeling | 分段函数** - [github.com](https://github.com/google/or-tools/blob/stable/ortools/sat/doc/channeling.md) | [B station](https://www.bilibili.com/video/BV1Nm4y1f7PH)
- **【运筹优化】CP-SAT | CP-model | 求解 CryptArithmetic** - [developers.google.com](https://developers.google.com/optimization/cp/cryptarithmetic) | [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/ordemo/send_more_money.py) | [B station](https://www.bilibili.com/video/BV13L411F7dC)
- **【运筹优化】CSP（约束满足最优化）| CP-SAT | domain reduction | constraint propagation** - [ibm.com](https://www.ibm.com/docs/en/icos/20.1.0?topic=optimizer-constraint-propagation) | [B station](https://www.bilibili.com/video/BV1gT4y1173C)
- **【python 运筹】约束满足规划问题 | CP-SAT solver | ortools | 自定义打印所有可行解的回调函数** - [developers.google.com](https://developers.google.com/optimization/cp/cp_solver) | [youtube.com](https://www.youtube.com/watch?v=4cCS8rrYT14) | [B station](https://www.bilibili.com/video/BV1Bq4y1g7JJ)
- **【python 运筹】constraint satisfaction problems | 约束满足问题 | ortools.sat | cp_model** - [youtube.com](https://www.youtube.com/watch?v=1FJy-ubE7UE) | [youtube.com](https://www.youtube.com/watch?v=4cCS8rrYT14) | [B station](https://www.bilibili.com/video/BV1AF411a7ir)
- **【运筹】ortools | cp-sat | 鸡兔同笼 demo** - [github.com](https://github.com/google/or-tools) | [github.com](https://github.com/google/or-tools/tree/stable/ortools/sat) | [github.com](https://github.com/google/or-tools/tree/stable/ortools/sat/doc) | [github.com](https://github.com/google/or-tools/blob/stable/ortools/sat/doc/integer_arithmetic.md) | [B station](https://www.bilibili.com/video/BV11v411T7o8)
- **【约束规划】从 binary encoding 到 logical expression 到 logical constraints 以及 CpModel** - [cis.upenn.edu](https://www.cis.upenn.edu/~cis189/) | [ibmdecisionoptimization.github.io](https://ibmdecisionoptimization.github.io/docplex-doc/mp_vs_cp.html) | [B station](https://www.bilibili.com/video/BV1ti4y1U77F)
- **[Python 机器学习] 深入理解 numpy（ndarray）的 axis（轴/维度）** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs/blob/master/basics/np_basics/np_axis_demo.ipynb) | [B station](https://www.bilibili.com/video/BV1vr4y187GQ)
- **【机器学习中的数学】【无穷级数】1/n^p（p-series）收敛性的证明** - [animated-mathematics.net](https://animated-mathematics.net/integral-test-p-series.html) | [B station](https://www.bilibili.com/video/BV1tN41197vH)
- **【机器学习中的数学】【概率论】正态分布的导数与拐点（inflection points）** - [B station](https://www.bilibili.com/video/BV1Lp4y1H7tS)
- **【矩阵计算】从 im2col 到 GEMM，矩阵与核的卷积到矩阵乘法** - [mathworks.com](https://www.mathworks.com/help/images/ref/im2col.html) | [cnblogs.com](https://www.cnblogs.com/shine-lee/p/10775831.html) | [B station](https://www.bilibili.com/video/BV13v411t76n)
- **【推荐系统】【缺失值处理】【矩阵分析】基于低秩矩阵补全（low rank matrix completing，矩阵分解 matrix factorizatio）** - [B station](https://www.bilibili.com/video/BV1P5411572h)
- **【sklearn machin learning】linear model（lr/lasso/ridge）预测回归2020年双11总成交额（GMV）** - [B station](https://www.bilibili.com/video/BV1Ea4y1s7uz)
- **【机器学习】线性回归（linear regression）逻辑回归（logistics regression）特征重要性与 odds ratio** - [B station](https://www.bilibili.com/video/BV1CZ4y1T7k7)
- **【手推公式】可导损失函数（loss function）的梯度下降（GD）、随机梯度下降（SGD）以及mini-batch gd梯度优化策略** - [B station](https://www.bilibili.com/video/BV1Ct4y197ch)
- **【计算机科学】蒙特卡洛方法计算“一棍砍两刀”构成三角形的概率** - [github.com](https://github.com/chunhuizhang/bilibili_vlogs) | [B station](https://www.bilibili.com/video/BV1sE411v7se)
- **【贝叶斯分析】三门问题的贝叶斯解释及其对于人生的启发（路径依赖+沉没成本，为什么说选择大于努力，方向大于坚持，何时调整人生的方向）** - [B station](https://www.bilibili.com/video/BV1ka4y1x78q)
- **【贝叶斯分析】三门问题（蒙提霍尔悖论，Monty Hall problem）的三个解释及其 python 仿真验证** - [B station](https://www.bilibili.com/video/BV1WK411L7vD)
- **大模型遇到Agent智能体：简介 #大模型 #AI系统 #智能体** - [B station](https://www.bilibili.com/video/BV11w411p7dW)
- **AI Agent智能体具体组成 #大模型 #AI系统 #智能体** - [B station](https://www.bilibili.com/video/BV11u4y1P73P)
- **Agent智能体的规划与提示词的关系 #大模型 #AI系统 #智能体** - [B station](https://www.bilibili.com/video/BV1kM411f7Gb)
- **AI Agent智能体应用原理剖析：AutoGPT、HuggingFPT等 #大模型 #AI系统 #智能体** - [B station](https://www.bilibili.com/video/BV1KC4y1S7ZG)
- **Agent智能体的问题与未来思考 #大模型 #AI系统 #智能体** - [B station](https://www.bilibili.com/video/BV1zM411f7n2)
- **什么是Harness？不就是Agent的Infra嘛** - [B station](https://www.bilibili.com/video/BV1nyQGBaEKW)
- **DeepSeek Harnees全网深度解读！** - [B station](https://www.bilibili.com/video/BV1f98M6AEeg)
- **打破 Transformer 结构垄断的新方式！#大模型 #Transformer** - [B station](https://www.bilibili.com/video/BV12EtRe4Ech)
- **Linear Attention 打破 Transformer 大模型结构垄断！#大模型 #Transformer** - [B station](https://www.bilibili.com/video/BV1V7s9etEmQ)
- **深度解读 KIMI K3** - [B station](https://www.bilibili.com/video/BV1rJKa63Eic)
- **万卡集群组网的网络基本知识！多层、单层、收敛比、拓扑什么关系？** - [B station](https://www.bilibili.com/video/BV1CQeEzFEiN)
- **又来万卡集群网络基本知识！框式vs盒式？单轨vs多轨？** - [B station](https://www.bilibili.com/video/BV18wHYz2EZ3)
- **了解AI组网，先看HPC超算组网洞察！世界最先进的组网都有哪些方案？** - [B station](https://www.bilibili.com/video/BV1sLWwzWEix)
- **国外万卡AI集群网络洞察！看国外Google、Mate 大厂是如何搭建万卡AI集群！** - [B station](https://www.bilibili.com/video/BV1tpnGzUELC)
- **国内大厂万卡AI集群网络洞察！看国内阿里、字节、腾讯是如何搭建万卡AI集群！** - [B station](https://www.bilibili.com/video/BV1FXnEzpEPZ)
- **AI万卡集群建设挑战！太难啦建10万卡集群，哭死** - [B station](https://www.bilibili.com/video/BV1QTbxzyETx)
- **AI万卡集群整体交付流程！太详细！** - [B station](https://www.bilibili.com/video/BV1JMYbzjE1b)
- **GPU万卡集群交付的测试步骤有哪些？应该怎么交付？** - [B station](https://www.bilibili.com/video/BV1jneqzPEsn)
- **GPU万卡集群如何进行测试！线性度、模型性能、通信带宽意味什么？！** - [B station](https://www.bilibili.com/video/BV116eqzJE8a)
- **GPU万卡集群交付实践总结！全是精华！** - [B station](https://www.bilibili.com/video/BV1Uveqz9EGw)
- **【AI 集群】英伟达 Blackwell 产品演进分析** - [B station](https://www.bilibili.com/video/BV1iT6TYXE25)
- **【AI 集群】英伟达 Blackwell 深度解读** - [B station](https://www.bilibili.com/video/BV1EczyYbEfE)
- **【AI 集群】英伟达 GB200 网络演进深度解读** - [B station](https://www.bilibili.com/video/BV1Vgi2YJEk7)
- **【AI 集群】英伟达 GB200 集群互联方案** - [B station](https://www.bilibili.com/video/BV1uaiXYbE5h)
- **【AI 集群】xAI世界最大10万卡GPU集群解读** - [B station](https://www.bilibili.com/video/BV1Mui6YdE6s)
- **【AI 集群】建设对十万卡 AI 集群深度思考与反思！** - [B station](https://www.bilibili.com/video/BV16MqsYNExP)
- **AI 服务器爆炸图鉴！了解 AI 服务器/GPU服务器长什么样子！** - [B station](https://www.bilibili.com/video/BV1DktBzLEvb)
- **为什么GPU和 AI 服务器风冷仍然是主流？** - [B station](https://www.bilibili.com/video/BV1mftyzZEB9)
- **AI时代为什么需要液冷？液冷技术发展剖析** - [B station](https://www.bilibili.com/video/BV1EvtYz1EXF)
- **AI集群液冷实践与思考！带你走进液冷的核心知识区！** - [B station](https://www.bilibili.com/video/BV1FjbMz1E7u)
- **AI机柜、服务器机柜爆炸图鉴！** - [B station](https://www.bilibili.com/video/BV1DwtSzGE7Q)
- **AI集群GPU集群供电和配电系统！** - [B station](https://www.bilibili.com/video/BV1UHtZzhEYJ)
- **新专题！什么是集群计算？超算、AI智能、数据中心的区别是什么？** - [B station](https://www.bilibili.com/video/BV1s5KfzzEbo)
- **通过超算硬件发展趋势看AIInfra基础设施的未来！** - [B station](https://www.bilibili.com/video/BV16A3wzEELU)
- **深度剖析HPC基础软件和应用的发展趋势！窥探AIInfra基础软件！** - [B station](https://www.bilibili.com/video/BV1Sr3YzXEQa)
- **集群计算HPC历史发展历程！回顾大型机到微型机时代！** - [B station](https://www.bilibili.com/video/BV1vugAzgEMK)
- **集群计算的发展历程（下集）！从云到 AI 智算中心！** - [B station](https://www.bilibili.com/video/BV14kgizdEmc)
- **AIInfra分层介绍！了解AIInfra怎么分层就看这个视频！** - [B station](https://www.bilibili.com/video/BV1C28dzWErf)
- **通过AI集群建设，看AI Infra的5层系统架构！学AI Infra就看这里！** - [B station](https://www.bilibili.com/video/BV1KD8zz2EeP)
- **为什么大模型都用Transformer结构？ #AIInfra #大模型 #Transformer** - [B station](https://www.bilibili.com/video/BV1rt421476q)
- **大模型输入长什么样子？大模型Tokenizer核心算法原理全解析！** - [B station](https://www.bilibili.com/video/BV16pTJz9EV4)
- **大模型Embedding整明白了！RoPE位置编码真简单！** - [B station](https://www.bilibili.com/video/BV1SSTgzLEzf)
- **Attention注意力才是大模型核心，一文讲明白Transformer本质！** - [B station](https://www.bilibili.com/video/BV11AMHzuEet)
- **Attention变种GQA、MLA、MQA都有什么区别？终于清晰啦** - [B station](https://www.bilibili.com/video/BV1GzMUz8Eav)
- **Transformer长序列新架构介绍！NSA\MOBA\LongTransfer\TransformerXL都来了！** - [B station](https://www.bilibili.com/video/BV16PN6z6ELg)
- **大模型参数应该怎么设置？一个视频搞清楚！系列最核心！** - [B station](https://www.bilibili.com/video/BV1nTNkzjE3J)
- **大模型整体架构、大模型全流程介绍 #大模型 #AI系统** - [B station](https://www.bilibili.com/video/BV1a34y137zi)
- **大模型整体架构、大模型全流程介绍 #大模型 #AI系统** - [B station](https://www.bilibili.com/video/BV1F34y1G7Fz)
- **大模型AI集群训练时间 & 训练效率如何计算？ #大模型 #AI系统** - [B station](https://www.bilibili.com/video/BV1YN4y1Z7RU)
- **大模型AI集群如何组成？AI集群需要哪些硬件？ #大模型 #AI系统** - [B station](https://www.bilibili.com/video/BV1dC4y1d7hd)
- **大模型在AI集群分布式架构：参数服务器 or 集合通信架构？ #大模型 #AI系统** - [B station](https://www.bilibili.com/video/BV1384y127iP)
- **大模型训练需要多少GPU？大模型显存怎么算？ #大模型 #AI系统** - [B station](https://www.bilibili.com/video/BV15Q4y147Uo)
- **大模型推理需要多大的显存？ #大模型 #AI系统 #推理 #显存** - [B station](https://www.bilibili.com/video/BV1Rc411S7jj)
- **NPU与GPU间为什么会有精度误差？！** - [B station](https://www.bilibili.com/video/BV1wGE9zSE1C)
- **一个视频就讲清楚 MCP 是什么！** - [B station](https://www.bilibili.com/video/BV1c97ozsEt9)
- **看MCP Server代码，了解大模型跟MCP如何协同！** - [B station](https://www.bilibili.com/video/BV11MEHzwEp6)
- **DeepSeek MoE把价格打下来核心原因？看MoE架构剖析！** - [B station](https://www.bilibili.com/video/BV17PNtekE3Y)
- **MoE架构的前世今生，MoE经典论文串烧和MoE可视化！** - [B station](https://www.bilibili.com/video/BV1y7wZeeE96)
- **MOE奠基论文走读，Adaptive Mixtures of Local Experts！** - [B station](https://www.bilibili.com/video/BV1MiAYeuETj)
- **MOE初遇RNN论文走读，Outrageously Large Neural Networks！** - [B station](https://www.bilibili.com/video/BV1RYAjeKE3o)
- **MOE经典论文GShard解读，MoE 迎来Transformer时代！** - [B station](https://www.bilibili.com/video/BV1r8ApeaEyW)
- **Switch Transformer经典论文解读！** - [B station](https://www.bilibili.com/video/BV1UsPceJEEQ)
- **MOE经典论文ST-MOE和GLaM，如何解决MOE训练稳定性问题！** - [B station](https://www.bilibili.com/video/BV1L59qYqEVw)
- **DeepSeekMOE论文走读，DeepSeek开山之作，共享专家原理！** - [B station](https://www.bilibili.com/video/BV1tE9HYUEdz)
- **MOE终于迎来可视化解读！傻瓜都能看懂MoE核心原理！** - [B station](https://www.bilibili.com/video/BV1Gj9ZYdE4N)
- **MoE遇到大模型，到底选大参数少专家还是？小参数多专家呢？** - [B station](https://www.bilibili.com/video/BV1UERNYqEwU)
- **使用昇腾NPU手撕MoE单机版代码！没想到如此简单！** - [B station](https://www.bilibili.com/video/BV1UTRYYUE5o)
- **使用昇腾NPU实现单机8卡MoE通信！手把手教你写代码！** - [B station](https://www.bilibili.com/video/BV1JaR5YSEMN)
- **视觉也用MoE？一起分析 V-MoE 和 Soft-MoE！** - [B station](https://www.bilibili.com/video/BV1JNQVYBEq7)
- **DeepSeek V3深度解读，炸开美国资本市场，10/1算力训练大模型！** - [B station](https://www.bilibili.com/video/BV1hRcGemErK)
- **DeepSeek-R1深度解读，大模型+强化学习重挫英伟达！** - [B station](https://www.bilibili.com/video/BV1dHw4e8E3e)
- **DeepSeek春节核弹解读，多模态大模型JanusPro到底如何？** - [B station](https://www.bilibili.com/video/BV1d8P1e9EtC)
- **DeepSeek开源 Day1：FlashMLA深度解读，分块MLA利用Flash显存！** - [B station](https://www.bilibili.com/video/BV1P9PeezEkx)
- **DeepSeek开源Day2：DeepEP 原理，NVSHMEM实现All2All通信！** - [B station](https://www.bilibili.com/video/BV1bN9PYeEak)
- **DeepSeek开源Day2：DeepEP代码走读！** - [B station](https://www.bilibili.com/video/BV1EwXSYgEMx)
- **DeepSeek开源一周大串烧，对行业和大模型带来哪些变化和冲击？** - [B station](https://www.bilibili.com/video/BV11W9hYKEGj)
- **全网最详细：SORA视频生成大模型原理剖析 #大模型 #OpenAI #SORA** - [B station](https://www.bilibili.com/video/BV1Bx4y1k7BQ)
- **全网最详细：OpenAI GPT-4o多模态大模型深度解读 #大模型 #OpenAI #GPT-4o** - [B station](https://www.bilibili.com/video/BV1Uy411Y76z)
- **OpenAI o1大模型炸了，数学逻辑推导能力堪比博士！ #大模型 #OpenAI** - [B station](https://www.bilibili.com/video/BV1QetAesERe)
- **从谷歌最新大模型GEMMA看24年大模型发展趋势 #AIInfra #大模型 #Transformer** - [B station](https://www.bilibili.com/video/BV1kC411H7cz)
- **绷不住了，大模型居然都免费了！ 对产业带来什么影响？ #大模型 #GPT4** - [B station](https://www.bilibili.com/video/BV1zM4m1m7Qa)
- **开源 vs 闭源大模型之争，LLAMA3.1 开源引起的血案！#大模型 #LLAMA3 #开源** - [B station](https://www.bilibili.com/video/BV1ZZ421N7Af)
- **LLAMA3.1 全球最大开源大模型 405B 详细解读！#大模型 #llama** - [B station](https://www.bilibili.com/video/BV1Xf421v7Go)
- **从KIMI 200万中文长序列看24年大模型发展趋势 #AIInfra #大模型 #KIMI** - [B station](https://www.bilibili.com/video/BV1Fx421D7Je)
- **KIMI K1.5深度解读，DeepSeek R1国内竞品到底如何？** - [B station](https://www.bilibili.com/video/BV1goNAecE5W)
- **KIMI Loooooooong超长序列核心技术MoBA，掌握核心大模型原理？** - [B station](https://www.bilibili.com/video/BV1J1PGevEPb)
- **回顾AI历史10年：从AlexNet到大模型爆发，算法、芯片、AI创业变化！** - [B station](https://www.bilibili.com/video/BV1pDNferEEW)
- **时光倒流2024：多模态觉醒，幻方独占鳌头！** - [B station](https://www.bilibili.com/video/BV11KFtekE5X)
- **时光倒流2023：大模型元年，全球百模大战！** - [B station](https://www.bilibili.com/video/BV1kGFteBE2z)
- **时光倒流2022：ChatGPT发布，低迷AI迎来春天！** - [B station](https://www.bilibili.com/video/BV1jUFQewEze)
- **时光倒流2021：AI4SCI登顶 Science，大模型爆发前夕！** - [B station](https://www.bilibili.com/video/BV1cKFde7Ez9)
- **时光倒流2020：OpenAI GPT3发布，MuZero登顶Science封面！** - [B station](https://www.bilibili.com/video/BV193F6eoEaS)
- **时光倒流2019：BERT发布迎来NLP最大突破，GPT当年竞品！** - [B station](https://www.bilibili.com/video/BV1YvPReGEcj)
- **时光倒流2018：AI芯片遍地开花，英伟达硬件狂飙！** - [B station](https://www.bilibili.com/video/BV1mzNVeHEHy)
- **时光倒流2017：Transformer架构提出，大模型一切基础！** - [B station](https://www.bilibili.com/video/BV1iNNUeaENt)
- **时光倒流2016：深度强化学习AlphaGo战胜围棋大师！** - [B station](https://www.bilibili.com/video/BV1L5NaeHEv1)
- **时光倒流2015：ResNet提出&OpenAI创立，AI爆发前夕！** - [B station](https://www.bilibili.com/video/BV12MN6etEvp)
- **时光倒流2014：12年到14年AlexNet与ImageNet引起AI爆发！** - [B station](https://www.bilibili.com/video/BV18gKEe6ECd)
- **WWDC2024 深度解读苹果 AI 技术! #WWDC #苹果 #大模型** - [B station](https://www.bilibili.com/video/BV1YH4y1w7WQ)
- **NVIDIA CES 2025洞察，大型芯片发布和DIGITS小型机太香了！** - [B station](https://www.bilibili.com/video/BV1vjczebESC)
- **NVIDIA COSMOS世界模型深度剖析，跟SORA什么区别？** - [B station](https://www.bilibili.com/video/BV18hwLeREUK)
- **英伟达NVIDIA创业20年坎坷之路，差点公司都丢掉** - [B station](https://www.bilibili.com/video/BV1FN411r7BW)
- **大模型时代需要AI安全吗？APPLE推出Swith HE同态加密有什么用？** - [B station](https://www.bilibili.com/video/BV1gmBuYjEhD)
- **AI 需要安全吗？AI 安全有哪些技术？对隐私计算技术全分析！** - [B station](https://www.bilibili.com/video/BV1AecAe3Err)
- **【大模型推理】大模型推理整体知识，大模型推理必看指南** - [B station](https://www.bilibili.com/video/BV1dyqDYvEv2)
- **【大模型推理】大模型推理 Prefill 和 Decoder 阶段详解** - [B station](https://www.bilibili.com/video/BV1nHqgYFEcq)
- **【大模型推理】大模型业界常用推理框架怎么选？** - [B station](https://www.bilibili.com/video/BV16yqeYhELh)
- **三贱客，瞎聊什么是多模态大模型！** - [B station](https://www.bilibili.com/video/BV1DSxQeDETh)
- **有人能告诉我具身智能是什么吗？ #大模型 #具身智能 #机器人** - [B station](https://www.bilibili.com/video/BV1Yk4ZeyE1B)
- **具身智能技术路线详细讲解！大白话具身智能！ #大模型 #具身智能 #机器人** - [B station](https://www.bilibili.com/video/BV1F8taeDEFP)
- **具身智能的信息平权！聊聊具身产业观点！ #大模型 #具身智能 #机器人** - [B station](https://www.bilibili.com/video/BV1M2tje9EG4)
- **NCCL/HCCL 的基础 MPI 通信介绍！#大模型 #集合通信 #MPI** - [B station](https://www.bilibili.com/video/BV1Di421h7u2)
- **业界集合通信库XCCL大串烧(基本介绍)上篇 #大模型 #集合通信 #NCCL** - [B station](https://www.bilibili.com/video/BV1o4421U7mo)
- **业界集合通信库XCCL大串烧(基本介绍)下篇 #大模型 #集合通信 #NCCL** - [B station](https://www.bilibili.com/video/BV1bS421X7uN)
- **了解英伟达NCCL通信库一个视频就够 #大模型 #集合通信 #NCCL** - [B station](https://www.bilibili.com/video/BV1SWpXe2Epa)
- **英伟达NCCL通信库到底怎么用！ #大模型 #集合通信 #NCCL** - [B station](https://www.bilibili.com/video/BV1BnpPesE5B)
- **终于搞清楚通信算法与网络拓扑啥关系了！#大模型 #集合通信 #NCCL** - [B station](https://www.bilibili.com/video/BV1DaHDezEcs)
- **万卡集群通信优化算法双二叉树！ #大模型 #集合通信 #NCCL** - [B station](https://www.bilibili.com/video/BV1zSpnezEB8)
- **华为HCCL 集合通信库开源(放)啦！难得呀！ #大模型 #集合通信 #NCCL** - [B station](https://www.bilibili.com/video/BV1wB4aeHEGM)
- **XCCL网络建模了解对大模型通信的影响 #大模型 #集合通信 #NCCL** - [B station](https://www.bilibili.com/video/BV1JkptetEJh)
- **推荐技术迎来 E2E 大变革时代！#大模型 #生成式推荐 #推荐系统** - [B station](https://www.bilibili.com/video/BV1BHpBeQEmR)
- **萝卜快跑技术解读！端到端自动驾驶？ #萝卜快跑 #自动驾驶 #端到端** - [B station](https://www.bilibili.com/video/BV1G4421S7Qa)
- **端到端自动驾驶算法综述 #特斯拉 #自动驾驶 #端到端** - [B station](https://www.bilibili.com/video/BV1xi421a7er)
- **大模型的集合通信内容介绍 #大模型 #通信 #集合通信** - [B station](https://www.bilibili.com/video/BV1jz421h7CA)
- **为什么需要集合通信？NCCL的架构是什么样？ #大模型 #通信 #集合通信** - [B station](https://www.bilibili.com/video/BV18J4m1G7UU)
- **集合通信的操作/原语/算子是什么？ #大模型 #通信 #集合通信** - [B station](https://www.bilibili.com/video/BV1gS411K7k5)
- **AI 对集合通信算法的诉求有什么？集合通信算法是啥？ #大模型 #通信 #集合通信** - [B station](https://www.bilibili.com/video/BV1g7421d7bN)
- **大模型并行的集合通信算法具体实现细节纰漏！#大模型 #集合通信** - [B station](https://www.bilibili.com/video/BV1fm421G7KK)
- **通信域是什么概念？PyTorch 如何实现集合通信？#大模型 #集合通信** - [B station](https://www.bilibili.com/video/BV1VZ421g7jY)
- **研究大模型在 AI 集群的通信，还要了解芯片内互联技术？Yes！#大模型 #集合通信** - [B station](https://www.bilibili.com/video/BV1jy411z7tg)
- **终于到了大模型集群互联，看昇腾Atlas 900集群细节！#大模型 #集合通信** - [B station](https://www.bilibili.com/video/BV1Wz421q7SV)
- **壁仞BR100是全球最强算力？反正我不信【AI芯片】国产厂商** - [B station](https://www.bilibili.com/video/BV1QW4y1S75Y)
- **壁仞BR100全球最强算力？架构解读来啦【AI芯片】国产厂商** - [B station](https://www.bilibili.com/video/BV1G14y1275T)
- **燧原科技搞AI芯片怎么样？邃思2.0芯片【AI芯片】国产厂商03** - [B station](https://www.bilibili.com/video/BV15W4y1Z7Hj)
- **寒武纪:AI芯片第一股,能否支撑千亿市值?【AI系统】国产AI芯片** - [B station](https://www.bilibili.com/video/BV1Y8411m7Cd)
- **寒武纪AI芯片第一股，芯片架构解读【AI系统】国产AI芯片** - [B station](https://www.bilibili.com/video/BV1op4y157Qf)
- **寒武纪AI芯片第一股，芯片架构解读【AI系统】国产AI芯片** - [B station](https://www.bilibili.com/video/BV1TV411j7Yx)
- **再不了解昇腾 AI服务器就要被公关掉了，随时删库跑路！ #大模型 #昇腾 #AI芯片** - [B station](https://www.bilibili.com/video/BV1yb421J7Jk)
- **你居然？敢说昇腾310/910 SOC处理器架构！#昇腾 #AI芯片** - [B station](https://www.bilibili.com/video/BV1Ls421M7t1)
- **昇腾的达芬奇内核架构，终于有人说明白了！#昇腾 #AI芯片** - [B station](https://www.bilibili.com/video/BV1HM4m1U76m)
- **昇腾AICore快速计算矩阵的秘密被打开了！#昇腾 #AI芯片** - [B station](https://www.bilibili.com/video/BV1v6421Z78u)
- **大模型是怎么训起来的？分布式并行框架介绍 #大模型 #分布式并行 #训练** - [B station](https://www.bilibili.com/video/BV1op421C7wp)
- **分布式并行框架DeepSpeed介绍 #大模型 #分布式并行 #训练** - [B station](https://www.bilibili.com/video/BV1tH4y1J7bm)
- **DeepSpeed优化器并行ZeRO1/2/3原理 #大模型 #分布式并行 #训练** - [B station](https://www.bilibili.com/video/BV1fb421t7KN)
- **分布式训练框架Megatron-LM代码概览 #大模型 #分布式并行 #训练** - [B station](https://www.bilibili.com/video/BV12J4m1K78y)
- **分布式PTD多维并行与GPU集群关系 #大模型 #分布式并行 #分布式训练** - [B station](https://www.bilibili.com/video/BV1NH4y1g7w4)
- **大模型PTD并行后如何配置在GPU集群？ #大模型 #分布式并行 #分布式训练** - [B station](https://www.bilibili.com/video/BV1ji421C7jH)
- **Megatron-LM张量并行的行切分和列切分核心原理 #大模型 #分布式并行 #分布式训练** - [B station](https://www.bilibili.com/video/BV1yw4m1S71Y)
- **Megatron-LM 张量并行 TP 代码剖析 #大模型 #分布式并行 #分布式训练** - [B station](https://www.bilibili.com/video/BV1cy411Y7B9)
- **Megatron-LM 序列并行 SP 代码剖析 #大模型 #分布式并行 #分布式训练** - [B station](https://www.bilibili.com/video/BV1EM4m1r7tm)
- **流水并行 PP 基本原理(Gpipe原理) #大模型 #分布式并行 #分布式训练** - [B station](https://www.bilibili.com/video/BV18f42197Sx)
- **流水并行 PP 基本原理(1F1B、1F1B Interleaved原理) #大模型 #分布式并行 #分布式训练** - [B station](https://www.bilibili.com/video/BV1aD421g7yZ)
- **Megatron-LM 流水并行PP代码解析 #大模型 #分布式并行 #分布式训练** - [B station](https://www.bilibili.com/video/BV1hs421g7vN)
- **Yann Lecun主推JEPA世界模型详细解读 #大模型 #世界模型 #sora** - [B station](https://www.bilibili.com/video/BV1v1421Q73e)
- **谷歌世界模型Genie详细解读 #大模型 #世界模型 #SORA #Geine** - [B station](https://www.bilibili.com/video/BV1b6421F7Tq)
- **SORA真的是世界模型？什么是世界模型？ #大模型 #世界模型 #SORA** - [B station](https://www.bilibili.com/video/BV1GZ421t7jr)
- **SORA如何引爆世界模型之争？ #大模型 #世界模型 #SORA** - [B station](https://www.bilibili.com/video/BV1dH4y1p7zt)
- **特斯拉Tesla DOJO芯片架构【AI芯片】NPU详解01** - [B station](https://www.bilibili.com/video/BV1Ro4y1M7n8)
- **特斯拉Tesla DOJO Core(存算一体架构)核心介绍【AI芯片】NPU详解02** - [B station](https://www.bilibili.com/video/BV17o4y1N7Yn)
- **特斯拉DOJO存算系统是怎么工作的？【AI芯片】NPU详解03** - [B station](https://www.bilibili.com/video/BV1Ez4y1e7zo)
- **Google TPU芯片系列概览和历史发展【AI芯片】TPU系列01** - [B station](https://www.bilibili.com/video/BV1Dp4y1V7PF)
- **Google TPUV1 脉动阵列原理【AI芯片】TPU系列02** - [B station](https://www.bilibili.com/video/BV12P411W7YC)
- **世界第一块AI训练芯片(Google TPUv2)的原理【AI芯片】TPU系列03** - [B station](https://www.bilibili.com/video/BV1x84y1f7Ex)
- **超级计算节点TPU POD介绍 #AI芯片 #TPU系列 #超算中心** - [B station](https://www.bilibili.com/video/BV1Pm4y1g7MG)
- **AI集群超级互联Google TPUv4 #AI芯片 #TPU系列 #AI集群** - [B station](https://www.bilibili.com/video/BV1QH4y1X77U)
- **AI集群超级互联Google TPUv4 光交换机 #AI芯片 #TPU系列 #AI集群** - [B station](https://www.bilibili.com/video/BV1yc411o7cQ)
- **地表最强推理芯片Groq原理剖析&洞察 #大模型 #Groq #推理** - [B station](https://www.bilibili.com/video/BV1jx421C7mG)
- **向量数据库介绍，Vector和Embedding关系 #大模型 #向量数据库** - [B station](https://www.bilibili.com/video/BV1JF4m177Wd)
- **向量数据库的功能、特性、发展和基本原理 #大模型 #向量数据库** - [B station](https://www.bilibili.com/video/BV1mv421C7uW)
- **向量数据库的技术与混合搜索系统 #大模型 #向量数据库** - [B station](https://www.bilibili.com/video/BV1pj421X7TH)
- **RAG技术详解、向量数据库对大模型的作用 #大模型 #向量数据库** - [B station](https://www.bilibili.com/video/BV1yu4m1P7UA)
- **向量数据库核心：相似性搜索 #大模型 #向量数据库** - [B station](https://www.bilibili.com/video/BV1UH4y1h79F)
- **向量数据库相似性搜索算法：ANN、IVF、HNSW #大模型 #向量数据库** - [B station](https://www.bilibili.com/video/BV1ap421d7Hf)
- **向量数据库相似性搜索算法：LSH、PQ、ISV-PQ #大模型 #向量数据库** - [B station](https://www.bilibili.com/video/BV1c6421g7Xr)
- **向量数据库之相似度度量和过滤的方法 #大模型 #向量数据库** - [B station](https://www.bilibili.com/video/BV1pH4y1j7XD)
- **大模型之数据工程概述 #大模型 #数据工程 #AIInfra** - [B station](https://www.bilibili.com/video/BV1dC41147er)
- **大模型为什么需要微调？有哪些微调方式？#大模型 #微调** - [B station](https://www.bilibili.com/video/BV1fc411m7Yt)
- **大模型的训练流程是什么？详解大模型预训练和微调间区别 #大模型 #微调** - [B station](https://www.bilibili.com/video/BV1994y1A7mC)
- **AI芯片除硬件本身外，还要关注什么？【AI芯片】黄金十年** - [B station](https://www.bilibili.com/video/BV13u4y197Lw)
- **CUDA编程好不好用，看SIMD和SIMT？#AI芯片 #SIMT #AI编程** - [B station](https://www.bilibili.com/video/BV1Kr4y1d7eW)
- **CUDA、SIMD、SIMT、DSA什么关系？好乱呀！#GPU #CUDA #英伟达 #SIMT** - [B station](https://www.bilibili.com/video/BV1WC4y1w79T)
- **CUDA跟SIMT的硬件架构什么关系？#GPU #CUDA #英伟达 #SIMT** - [B station](https://www.bilibili.com/video/BV16c41117vp)
- **AI芯片从CUDA和NVIDIA中有哪些值得借鉴？#GPU #CUDA #英伟达 #SIMT #AI芯片** - [B station](https://www.bilibili.com/video/BV1j94y1N7qh)
- **关于AI芯片演进的8个思考 #GPU #CUDA #AI芯片 #英伟达 #SIMT** - [B station](https://www.bilibili.com/video/BV1te411y7UC)
- **存储遇到大模型会有什么新架构和技术点？ #大模型 #AI系统 #数据存储 #AI集群** - [B station](https://www.bilibili.com/video/BV1H94y1J7wq)
- **数据存储硬件组成（RAM/Flash/Cache/HBM/SSD） #大模型 #AI系统 #数据存储 #AI集群** - [B station](https://www.bilibili.com/video/BV1fw411P7FY)
- **数据存储集群连接方式（DAS/SAN/NAS） #大模型 #AI系统 #数据存储 #AI集群** - [B station](https://www.bilibili.com/video/BV1SQ4y147b3)
- **数据的存储类型和方式(块存储/文件存储/对象存储) #大模型 #AI系统 #数据存储 #AI集群** - [B station](https://www.bilibili.com/video/BV1fa4y1Z76n)
- **存储遇到大模型会有哪些挑战？#大模型 #AI系统 #数据存储 #AI集群** - [B station](https://www.bilibili.com/video/BV1UG411i7SM)
- **大模型训练的存储优化方案(上) #大模型 #AI系统 #数据存储 #AI集群** - [B station](https://www.bilibili.com/video/BV1uw411h7B7)
- **大模型训练的存储优化方案(下) #大模型 #AI系统 #数据存储 #AI集群** - [B station](https://www.bilibili.com/video/BV11u4y1c7Pu)
- **大模型 Checkpoint 优化手段！ #大模型 #AI系统 #数据存储 #AI集群** - [B station](https://www.bilibili.com/video/BV1wM411d7cc)
- **存算架构的思考 #大模型 #AI系统 #数据存储 #AI集群** - [B station](https://www.bilibili.com/video/BV1kw411h74p)
- **NVIDIA英伟达Tensor Core基本原理(上)【AI芯片】GPU架构04** - [B station](https://www.bilibili.com/video/BV1aL411a71w)
- **NVIDIA英伟达Tensor Core架构发展(中)【AI芯片】GPU架构05** - [B station](https://www.bilibili.com/video/BV1pL41187FH)
- **NVIDIA英伟达Tensor Core深度剖析(下)【AI芯片】GPU架构06** - [B station](https://www.bilibili.com/video/BV1oh4y1J7B4)
- **分布式训练和NVLink&NVSwitch关系【AI芯片】GPU详解04** - [B station](https://www.bilibili.com/video/BV1cV4y1r7Rz)
- **深入NVLink原理：内部结构与组网拓扑【AI芯片】GPU详解05** - [B station](https://www.bilibili.com/video/BV1uP411X7Dr)
- **从NVLink到NVSwitch，英伟达最黑科技【AI芯片】GPU详解06** - [B station](https://www.bilibili.com/video/BV1uM4y1n7qd)
- **深入GPU原理：线程和缓存关系【AI芯片】GPU原理01** - [B station](https://www.bilibili.com/video/BV1bm4y1m7Ki)
- **为什么AI训练使用GPU而不是CPU？【AI芯片】GPU原理02** - [B station](https://www.bilibili.com/video/BV1Ms4y1N7RL)
- **GPU硬件架构与CUDA如何对应？【AI芯片】GPU架构01** - [B station](https://www.bilibili.com/video/BV1Kk4y1Y7op)
- **NVIDIA十代GPU架构回顾(从Fermi费米到Volta伏特)【AI芯片】GPU架构02** - [B station](https://www.bilibili.com/video/BV1x24y1F7kY)
- **NVIDIA十代GPU架构回顾(从Turning图灵到Hopper赫柏)【AI芯片】GPU架构03** - [B station](https://www.bilibili.com/video/BV1mm4y1C7fg)
- **从CPU发展和组成看并行架构！【AI芯片】芯片基础01** - [B station](https://www.bilibili.com/video/BV1tv4y1V72f)
- **CPU的ISA指令集架构看CISC和RISC之争！【AI芯片】芯片基础02** - [B station](https://www.bilibili.com/video/BV1ro4y1W7xN)
- **CPU计算本质：数据如何传输【AI芯片】芯片基础03** - [B station](https://www.bilibili.com/video/BV17X4y1k7eF)
- **CPU计算时延【AI芯片】芯片基础04** - [B station](https://www.bilibili.com/video/BV1Qk4y1i7GT)
- **从GPU架构发展看AI【AI芯片】芯片基础05** - [B station](https://www.bilibili.com/video/BV1sM411T72Q)
- **AI芯片技术基础【AI芯片】芯片基础06** - [B station](https://www.bilibili.com/video/BV1Rk4y1e77n)
- **超异构体系思考，计算体系架构变革10年【AI芯片】芯片基础07** - [B station](https://www.bilibili.com/video/BV1YM4y117VK)
- **AI芯片涉及哪些知识？【AI芯片】内容简介** - [B station](https://www.bilibili.com/video/BV1DX4y1D7PC)
- **深度学习计算模式是什么？【AI芯片】AI计算体系02** - [B station](https://www.bilibili.com/video/BV17x4y1T7Cn)
- **轻量化和大模型的计算模式怎么理解？【AI芯片】AI计算体系03** - [B station](https://www.bilibili.com/video/BV1754y1M78X)
- **设计AI芯片需要关注什么指标？【AI芯片】AI计算体系04** - [B station](https://www.bilibili.com/video/BV1qL411o7S9)
- **AI芯片主要计算方式：矩阵运算【AI芯片】AI计算体系05** - [B station](https://www.bilibili.com/video/BV1ak4y1h7mp)
- **int8/fp16/bf16/tf32在AI芯片中什么作用？【AI芯片】AI计算体系06** - [B station](https://www.bilibili.com/video/BV1WT411k724)
- **AI 计算体系到底是什么？【AI芯片】AI计算体系07** - [B station](https://www.bilibili.com/video/BV1j54y1T7ii)
- **Kernel优化架构介绍！【推理引擎】Kernel优化第01篇** - [B station](https://www.bilibili.com/video/BV1Ze4y1c7Bb)
- **卷积优化：卷积操作基础原理！【推理引擎】Kernel优化第02篇** - [B station](https://www.bilibili.com/video/BV1No4y1e7KX)
- **卷积优化：Im2Col算法和组合优化算法【推理引擎】Kernel优化第03篇** - [B station](https://www.bilibili.com/video/BV1Ys4y1o7XW)
- **卷积优化：Winograd算法【推理引擎】Kernel优化第04篇** - [B station](https://www.bilibili.com/video/BV1vv4y1Y7sc)
- **QNNPack之间接优化算法【推理引擎】Kernel优化第05篇** - [B station](https://www.bilibili.com/video/BV1ms4y1o7ki)
- **推理引擎内存布局方式【推理引擎】Kernel优化第06篇** - [B station](https://www.bilibili.com/video/BV1eX4y1X7mL)
- **ChatGPT狂飙：GPT家族详解！【ChatGPT原理】第01篇** - [B station](https://www.bilibili.com/video/BV1kv4y1s7V7)
- **ChatGPT狂飙：强化学习RLHF与PPO！【ChatGPT】原理第02篇** - [B station](https://www.bilibili.com/video/BV1eT411S7Yx)
- **ChatGPT狂飙：InstructGPT解析！【ChatGPT】原理第03篇** - [B station](https://www.bilibili.com/video/BV1e24y1s7k8)
- **离线转换模块架构与流程！【推理引擎】离线转换系列第01篇** - [B station](https://www.bilibili.com/video/BV1724y1z7ep)
- **模型序列化和反序列化原理！【推理引擎】离线转换系列第02篇** - [B station](https://www.bilibili.com/video/BV13P4y167sr)
- **如何自定义计算图IR？【推理引擎】离线转换系列第03篇** - [B station](https://www.bilibili.com/video/BV1rx4y177R9)
- **模型转换技术细节！【推理引擎】离线转换系列第04篇** - [B station](https://www.bilibili.com/video/BV13341197zU)
- **计算图优化策略！【推理引擎】离线优化系列第01篇** - [B station](https://www.bilibili.com/video/BV1g84y1L7tF)
- **常量折叠与冗余节点消除优化！计算图优化Details！【推理引擎】离线优化第02篇** - [B station](https://www.bilibili.com/video/BV1fA411r7hr)
- **算子融合/算子替换/算子前移优化！【推理引擎】离线优化第03篇** - [B station](https://www.bilibili.com/video/BV1Qj411T7Ef)
- **Flash Attention原理！数据布局转换与内存优化！【推理引擎】离线优化第04篇** - [B station](https://www.bilibili.com/video/BV1Ae4y1N7u7)
- **模型压缩架构和流程介绍！量化/剪枝/蒸馏/二值化4件套！【推理系统】模型压缩第01篇** - [B station](https://www.bilibili.com/video/BV1384y187tL)
- **低比特量化基本原理！【推理引擎】模型压缩系列第02篇** - [B station](https://www.bilibili.com/video/BV1VD4y1n7AR)
- **感知量化训练QAT原理！伪量化节点计算方式！【推理引擎】模型压缩系列第03篇** - [B station](https://www.bilibili.com/video/BV1s8411w7b9)
- **训练后量化PTQ深度解读！与量化部署核心原理！【推理引擎】模型压缩系列第04篇** - [B station](https://www.bilibili.com/video/BV1HD4y1n7E1)
- **模型剪枝核心原理！模型剪枝算法和流程介绍！Model Pruning深度解析【推理引擎】模型压缩系列第05篇** - [B station](https://www.bilibili.com/video/BV1y34y1Z7KQ)
- **知识蒸馏原理介绍！知识从哪里来怎么蒸馏？【推理引擎】模型压缩系列第06篇(上)** - [B station](https://www.bilibili.com/video/BV1My4y197Tf)
- **知识蒸馏SOTA算法解读！【推理引擎】模型压缩系列第06篇(下)** - [B station](https://www.bilibili.com/video/BV1vA411d7MF)
- **如何计算模型参数量？什么是FLOPS和MACC？【推理系统】模型小型化第01篇** - [B station](https://www.bilibili.com/video/BV1KW4y1G75J)
- **CNN模型小型化原理！SqueezeNet/ShuffleNet/MobileNet系列介绍！【推理系统】模型小型化第02篇** - [B station](https://www.bilibili.com/video/BV1Y84y1b7xj)
- **CNN模型小型化算法总结！ESPnet/GhostNet系列介绍！【推理系统】模型小型化第03篇** - [B station](https://www.bilibili.com/video/BV1DK411k7qt)
- **Transformer轻量化SOTA模型原理！【推理系统】模型小型化第04篇** - [B station](https://www.bilibili.com/video/BV19d4y1V7ou)
- **AI编译器前端"图层优化"内容概览！！【AI编译器】系列之前端优化第01篇** - [B station](https://www.bilibili.com/video/BV1ne411w7n2)
- **图层IR(Graph IR)是什么？AI编译器如何接收图层IR进行优化呢？【AI编译器】系列之前端优化第02篇** - [B station](https://www.bilibili.com/video/BV1kV4y1w72W)
- **算子融合了解下！AI编译器如何实现算子融合的？【AI编译器】系列之前端优化第03篇** - [B station](https://www.bilibili.com/video/BV1P24y1D7RV)
- **编译器为什么要对数据布局转换呢 Layout Transformations？【AI编译器】系列之前端优化第04篇(上)** - [B station](https://www.bilibili.com/video/BV1xK411z7Uw)
- **[概率 & 统计] KL 散度（KL div）forward vs. reverse** - [B station](https://www.bilibili.com/video/BV1cT42127wg)
- **详解AI编译器数据布局转换方法！华为昇腾处理器的数据布局格式！【AI编译器】系列之前端优化第04篇(下)** - [B station](https://www.bilibili.com/video/BV1gd4y1Y7dc)
- **AI编译器内存优化算法！动态内存和静态内存区别！【AI编译器】前端优化第05篇** - [B station](https://www.bilibili.com/video/BV1nM411879s)
- **常量折叠原理！AI编译器常量折叠跟传统编译器什么关系？计算图也需要常量折叠！【AI编译器】系列之前端优化第06篇** - [B station](https://www.bilibili.com/video/BV1P8411W7dY)
- **编译器公共子表达式消除的方法！AI编译器消除公共子表达式【AI编译器】系列之前端优化第07篇** - [B station](https://www.bilibili.com/video/BV1rv4y1Q7tp)
- **编译器死代码消除的原理！AI编译器死代码消除【AI编译器】系列之前端优化第08篇** - [B station](https://www.bilibili.com/video/BV1hD4y1h7nh)
- **编译器的代数化简原理！AI编译器的代数化简来啦！【AI编译器】系列之前端优化第09篇** - [B station](https://www.bilibili.com/video/BV1g24y1Q7qC)
- **AI编译器的前端优化/图优化Pass的顺序怎么排？【AI编译器】系列之前端优化第10篇** - [B station](https://www.bilibili.com/video/BV1L14y1P7ku)
- **PyTorch 2.0新特性开撸！图模式打开了潘多拉！【AI编译器之PyTorch】系列01篇** - [B station](https://www.bilibili.com/video/BV1p84y1675B)
- **TorchScript 解读！图模式的第一次尝试！静态图+JIT编译器！【AI编译器之PyTorch】系列02篇** - [B station](https://www.bilibili.com/video/BV1JV4y1P7gB)
- **PyTorch静态图的TorchFX和Lazy Tensor特性解读！【AI编译器之PyTorch】系列03篇** - [B station](https://www.bilibili.com/video/BV1944y1m7fU)
- **TorchDynamo原理来啦！PyTorch2.0编译新特性哦！【AI编译器之PyTorch】系列04篇** - [B station](https://www.bilibili.com/video/BV1jD4y1a7hx)
- **AOTAutograd原理解读！如何获取静态反向图？【AI编译器之PyTorch】系列05篇** - [B station](https://www.bilibili.com/video/BV1Me4y1V7Ke)
- **PyTorch Dispatcher原理！PyTorch算子注册！【AI编译器之PyTorch】系列06篇** - [B station](https://www.bilibili.com/video/BV1L3411d7SM)
- **什么是推理系统？推理有哪些应用？【推理系统】系列01篇** - [B station](https://www.bilibili.com/video/BV1J8411K7pj)
- **推理系统和推理引擎的不同之处在哪？【推理系统】系列02篇** - [B station](https://www.bilibili.com/video/BV1nY4y1f7G5)
- **云侧和端侧推理方式的特点和区别！【推理系统】系列03篇** - [B station](https://www.bilibili.com/video/BV1M24y1v7rK)
- **推理系统架构和Trition架构介绍！【推理系统】系列04篇** - [B station](https://www.bilibili.com/video/BV1Gv4y1i7Tw)
- **推理引擎架构介绍！MNN、TF Lite、TensorRT介绍！【推理系统】系列05篇(上)** - [B station](https://www.bilibili.com/video/BV1Mx4y137Er)
- **推理引擎架构！MNN、TensorRT架构介绍！【推理系统】系列05篇(下)** - [B station](https://www.bilibili.com/video/BV1FG4y1C7Mn)
- **AI编译器后端优化来啦！AI编译器后端架构！【AI编译器】后端优化01篇** - [B station](https://www.bilibili.com/video/BV17D4y177bP)
- **如何对算子IR表示？算子是如何分开计算和调度两部分？【AI编译器】后端优化02篇** - [B station](https://www.bilibili.com/video/BV1K84y1x7Be)
- **AI编译器后端算子优化来啦！算子优化手工方式！【AI编译器】后端优化03篇** - [B station](https://www.bilibili.com/video/BV1ZA411X7WZ)
- **后端算子循环优化！Loop Optimization常见方法！【AI编译器】后端优化04篇** - [B station](https://www.bilibili.com/video/BV1r14y1w7hG)
- **算子优化的指令和存储优化！【AI编译器】后端优化05篇** - [B station](https://www.bilibili.com/video/BV11d4y1a7J6)
- **Auto Tuning原理！TVM的AutoTVM实现方式详解！【AI编译器】后端优化06篇** - [B station](https://www.bilibili.com/video/BV1uA411D7JF)
- **分布式并行策略基础介绍！【分布式并行】系列第01篇** - [B station](https://www.bilibili.com/video/BV1ve411w7DL)
- **PyTorch数据并行怎么实现？DP、DDP、FSDP数据并行原理？【分布式并行】系列第02篇** - [B station](https://www.bilibili.com/video/BV1JK411S7gL)
- **什么是张量并行？张量并行的数学原理是什么？【分布式并行】系列第03篇** - [B station](https://www.bilibili.com/video/BV1vt4y1K7wT)
- **张量还能自动并行？MindSpore张量自动并行啥原理？【大模型与分布式训练】系列04篇** - [B station](https://www.bilibili.com/video/BV1C8411h7Q6)
- **模型并行的流水线并行来啦！了解下GPipe和PipeDream？【分布式并行】系列第05篇** - [B station](https://www.bilibili.com/video/BV1WD4y1t7Ba)
- **混合并行？多维并行？有多维度混合在一起并行吗？【分布式并行】系列第06篇** - [B station](https://www.bilibili.com/video/BV1gD4y1t7Ut)
- **分布式训练总结！【大模型与分布式训练】系列第07篇** - [B station](https://www.bilibili.com/video/BV1av4y1S7DQ)
- **为什么需要AI编译器？跟传统编译器啥关系吗？【AI编译器】系列第一篇** - [B station](https://www.bilibili.com/video/BV1pM41167KP)
- **AI编译器架构发展！三个阶段出现的AI编译器有啥区别？【AI编译器】系列第二篇** - [B station](https://www.bilibili.com/video/BV1QK411R7iy)
- **AI编译器啥架构来着？有多少模块？【AI编译器】系列第三篇** - [B station](https://www.bilibili.com/video/BV1qD4y1Y73e)
- **AI编译器的挑战与未来？【AI编译器】系列第四篇** - [B station](https://www.bilibili.com/video/BV1Hv4y1R7uc)
- **计算图有哪些内容知识？【计算图】系列第一篇** - [B station](https://www.bilibili.com/video/BV1cG411E7gV)
- **为什么AI框架都用计算图？什么是计算图？到底计算图有什么用？【计算图】系列第二篇** - [B station](https://www.bilibili.com/video/BV1rR4y197HM)
- **计算图跟微分什么关系？怎么用计算图表示自动微分？AI框架自动微分如何通过计算图来实现？【计算图】系列第三篇** - [B station](https://www.bilibili.com/video/BV1S24y197FU)
- **对计算图进行优化与执行调度！计算图优化跟AI编译器啥关系？一起了解下计算图的调度执行吧！【计算图】第四篇** - [B station](https://www.bilibili.com/video/BV1hD4y1k7Ty)
- **AI框架都是怎么表示控制流的？PyTorch和TF对计算图中控制语句如何处理？【计算图】第五篇** - [B station](https://www.bilibili.com/video/BV17P41177Pk)
- **AI框架如何实现动静统一？PyTorch和MindSpore动静统一做得如何了？【计算图】第六篇** - [B station](https://www.bilibili.com/video/BV11M41167yX)
- **计算图未来将会走向何方？【计算图】第七篇** - [B station](https://www.bilibili.com/video/BV1hm4y1A7Nv)
- **编译器和解释器啥区别？AOT和JIT啥区别？Pass和IR又是什么？【AI编译器】系列01篇** - [B station](https://www.bilibili.com/video/BV1D84y1y73v)
- **GCC和LLVM发家历史？两大开源编译器的爱恨情仇【AI编译器】系列第二篇** - [B station](https://www.bilibili.com/video/BV1sM411C7Vr)
- **GCC编译过程！优缺点是啥？手把手用GCC编译一个小程序【AI编译器】系列第三篇** - [B station](https://www.bilibili.com/video/BV1LR4y1f7et)
- **LLVM架构了解下？为什么LLVM这么火？一起初体验实操LLVM【AI编译器】系列第四篇** - [B station](https://www.bilibili.com/video/BV1CG4y1V7Dn)
- **LLVM IR详解！LLVM编译器的核心理念来啦！【AI编译器】系列第五篇(上)** - [B station](https://www.bilibili.com/video/BV1PP411u7NR)
- **LLVM编译器前端和优化层了解下？词法语法分析、Pass优化都在这！【AI编译器】系列第五篇(中)** - [B station](https://www.bilibili.com/video/BV1vd4y1t7vS)
- **LLVM后端代码生成！了解下基于LLVM的项目！【AI编译器】系列第五篇(下)** - [B station](https://www.bilibili.com/video/BV1cd4y1b7ho)
- **分布式训练、分布式集群的基础介绍！【分布式集群】第01篇** - [B station](https://www.bilibili.com/video/BV1ge411L7mi)
- **AI集群用什么服务器架构？Ring All Reduce算法跟物理网络啥关系？【分布式集群】系列第02篇** - [B station](https://www.bilibili.com/video/BV1fg41187rc)
- **AI集群的软硬件通信：从硬件PCIE、NVLINK、RDMA原理到通信NCCL、MPI原理！【分布式集群】系列第03篇** - [B station](https://www.bilibili.com/video/BV14P4y1S7u4)
- **AI集群机器间是怎么通信？通信原语是个什么玩意？【分布式集群】系列第04篇** - [B station](https://www.bilibili.com/video/BV1te4y1e7vz)
- **AI框架如何实现分布式训练？SISD和SIMT又是什么？【分布式集群】系列第05篇** - [B station](https://www.bilibili.com/video/BV1Y14y1576A)
- **大模型是什么？大模型有什么用？训练大模型会遇到哪些挑战？【分布式算法】第01篇** - [B station](https://www.bilibili.com/video/BV1n8411s7f3)
- **大模型算法有哪种结构？怎么样才算大模型呢？从Transformer和MOE结构看大模型发展！【分布式算法】系列第02篇** - [B station](https://www.bilibili.com/video/BV1Mt4y1M7SE)
- **从十亿到万亿规模SOTA大模型有哪些？BERT、GPT3、Switch算法来啦！【分布式算法】系列第03篇** - [B station](https://www.bilibili.com/video/BV1em4y1F7ay)
- **AI框架内容介绍：AI框架基础、AI框架之争、AI编程范式！【AI框架基础】系列第一篇** - [B station](https://www.bilibili.com/video/BV1he4y1z7oD)
- **AI框架有什么用？没有AI框架写算法又会怎么样？【AI框架基础】系列第二篇** - [B station](https://www.bilibili.com/video/BV1fd4y1q7qk)
- **AI框架之争！都2022年，应该怎么选择AI框架？【AI框架基础】系列第三篇** - [B station](https://www.bilibili.com/video/BV1C8411x7Kn)
- **函数式编程和声明式编程啥区别？AI到底应该用什么编程范式？【AI框架基础】系列第四篇** - [B station](https://www.bilibili.com/video/BV1gR4y1o7WT)
- **想了解自动微分吗？自动微分内容介绍！【自动微分】系列第一篇！** - [B station](https://www.bilibili.com/video/BV1FV4y1T7zp)
- **符号微分/数值微分/自动微分区别是什么？【自动微分】系列第二篇** - [B station](https://www.bilibili.com/video/BV1Ld4y1M7GJ)
- **前向微分和正向微分怎么理解？微分方式跟反向传播算法啥关系？【自动微分】系列第三篇** - [B station](https://www.bilibili.com/video/BV1zD4y117bL)
- **自动微分是怎么实现的？Lib Base、操作符重载、源码转换不懂得快来！【自动微分】系列第四篇！** - [B station](https://www.bilibili.com/video/BV1BN4y1P76t)
- **亲自撸一个正向自动微分的AI框架！【自动微分】系列第五篇** - [B station](https://www.bilibili.com/video/BV1Ne4y1p7WU)
- **手把手实现一个PyTorch！实现PyTorch核心自动微分！【自动微分】系列第六篇** - [B station](https://www.bilibili.com/video/BV1ae4y1z7E6)
- **自动微分挑战和未来！自动微分易用性和性能应该如何兼容？可微编程是否未来？【自动微分】系列第七篇** - [B station](https://www.bilibili.com/video/BV17e4y1z73W)
- **[2] 读上月新鲜出炉的综述：大模型写算子【每周一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1XcfBBGEUw)
- **[4] 大模型写算子：一篇综述+2个数据集【每周一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1pJA6zkEH4)
- **[6] Agent写算子：读三个Agent写算子的论文【每周一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1HVPkzEEx9)
- **[8] 读三个强化学习写算子的论文【每周一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1fVckzqE1S)
- **［10］大模型写算子：读两个KernelBench的改进工作【每周一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1M8QUBUESz)
- **［12］读2个多Agent共享KV Cache的论文【每周一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1B997BmEGr)
- **[14] AWQ：大语言模型量化论文解读 【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1RuoFBvEm8)
- **[16] LLM.int8()：大模型量化论文解读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1BeoNB9EQP)
- **[18] SmoothQuant：大模型量化论文解读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1CkoPBbEyB)
- **[28] 模型剪枝OB家族论文一口气看完：OBD、OBS、OBC【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1bJd2BHEeb)
- **[29] GPTQ：大模型量化论文解读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1Y3d2BoELh)
- **[31]. OSDI 2025 LLM方向论文串讲：DecDEC、WLB_LLM、Straggler【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV129ReB1EiW)
- **[44]. AutoRound：大模型量化论文解读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1t1RrBNEEt)
- **[107]. 微软的1.58bit量化：论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1rtME6LEfy)
- **[163]. Deep Compression：韩松的剪枝+量化经典，论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV16ath6fEA4)
- **[178]. QuaRot：旋转矩阵消除异常值，4 比特无损推理，论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1jvep67Eoa)
- **[180]. PyramidKV：金字塔式 KV 压缩，省显存保性能，论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1TdhB6MEm7)
- **[15] PagedAttention：vLLM论文解读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1xJoNBPEqe)
- **[17] FlashAttention-1论文解读 【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1XPoNB5EQy)
- **[24] SGLang：大模型推理引擎论文解读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV18Ud6BME78)
- **[20] 投机采样：大模型推理加速论文解读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1V6d6BCEzJ)
- **[21] 在线softmax：论文解读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1Qkd6B3EUe)
- **[22] FlashAttention-V2：论文解读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1yfd6B8E37)
- **[23] flash-attention-v3：论文解读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1yZd6BcE3b)
- **[26] GQA：分组查询注意力论文解读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1Bcd2BeEVv)
- **[27] SlimAttention：一种和FlashAttention分块策略不同的注意力【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1hjd2BWEGS)
- **[43]. MQA：论文解读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1m1RrBNEmy)
- **[79]. FlashAttention-4：论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1q6Js6DEwE)
- **[99]. Medusa：投机解码和树形注意力论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1NsKQ6zENp)
- **[98]. TurboQuant：KV Cache量化论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV11sKQ6zEFj)
- **[101]. H2O：KV缓存压缩论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1ktTc6tEce)
- **[100]. FlashDecoding的改进：FlashDecoding++论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1rtTc6tEen)
- **[110]. EAGLE：投机解码论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1BZMJ6CEa6)
- **[116] Deepseek的DSpark：投机解码论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1SCK36PEGX)
- **[179]. Orca：迭代级调度开创者，LLM 服务系统鼻祖，论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1GueP6pE7P)
- **[25] QLora：大模型量化微调论文解读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1CFdrBfE2D)
- **[152]. Distilling the Knowledge：知识蒸馏奠基之作，论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1cK8h6vEVW)
- **[19] DeepSeek-V4逐图、逐公式解读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1Mgo5BwEST)
- **[30] Deepseek-MLA、MTP解读 【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1Vgd2BtEKe)
- **[32]. Hyper Connections：残差连接的改进【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV142RrBeEa3)
- **[33]. mHC：流形约束超连接【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1m2RrBeEFS)
- **[35]. Deepseek-Engram：论文解读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV122RrBeEfs)
- **[37]. Adam：论文解读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV142RrBeEjQ)
- **[40]. Transformer：论文解读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1t1RrBNEwi)
- **[46]. Muon is Scalable：Muon优化器论文解读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV14N5b6YEbf)
- **[51]. BERT：论文解读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1fXLJ6aEZ1)
- **[52]. GPT2：论文解读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1FXLJ6YECS)
- **[53]. GPT3：论文解读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1FXLJ6YEh4)
- **[56]. 旋转位置编码RoPE：论文解读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1cQLJ6PEAs)
- **[59]. MoE：论文解读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV17zLC68Emq)
- **[65]. Mamba：论文解读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1uGVK6iEh2)
- **[67]. Dropout：论文解读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1dsG26dETn)
- **[72]. Word2Vec：论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1Ag7m6XERk)
- **[82]. 思维链：论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1q6Js6DEaQ)
- **[83]. 思维树：论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV176Js6DEsq)
- **[92]. TVM：论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1kv7q6REVg)
- **[93]. PyTorch_2：论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1kv7q6RE7a)
- **[94]. BPE：论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1kv7q6REeS)
- **[96]. Mamba_2：论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1Av7q6dEpF)
- **[104]. kimi的注意力残差：论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1MRME6oEhx)
- **[105]. TTT，一种序列模型：论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1MRME6oE3a)
- **[106]. RWKV，一种序列模型：论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1MRME6oE2V)
- **[108]. deepseek的NSA：论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1HtME6LEWp)
- **[109]. AdamW：论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1eKMn6MEMr)
- **[113]. GRU：论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1LwN36uEbV)
- **[117]. Kimi 的混合线性注意力：论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1TUKp6hEi6)
- **[119]. LookAhead：投机解码论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1hrKp6NEp3)
- **[120]. Performer，线性注意力：论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1hzKp6iE1b)
- **[115] Kimi K3 技术报告：论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1uyK36eEcT)
- **[127]. LSTM：经典重温，论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1Qr3y6VEt4)
- **[129]. Muon 优化器：原始技术博客，论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1hr3y6VEd6)
- **[139]. RNN：循环神经网络经典重温，论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1KiuG6zE44)
- **[133]. FlashDecoding：原始技术博客，论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1xBuG6MEB3)
- **[142]. LoRA：大模型微调经典重温，论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1zxbY6vE5n)
- **[144]. Megatron LM：大模型并行训练重要工作，论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1BxbY6vE9J)
- **[146]. Universal_Approximators：神经网络的万能近似定理，论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1CEbY6gEHM)
- **[148]. Diffusion LM：扩散语言模型开山之作，论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1AEbY63ETH)
- **[150]. Seq2Seq：序列到序列经典论文，论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1Rf8J6bEDU)
- **[151]. Switch Transformer：稀疏专家模型，论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV16K8h6eE2v)
- **[153]. Bahdanau Attention：首次将注意力用于Seq2Seq，论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1rK8h6eEGT)
- **[154]. ZeRO：DeepSpeed 大模型显存优化，论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1B38h6cEQP)
- **[158]. Gated Attention：NeurIPS 2025 最佳论文，给注意力加个门，论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1ULth66EHH)
- **[159]. MoBA：Kimi 的稀疏注意力，NSA 姊妹篇，论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1ULth66EJ8)
- **[160]. EAGLE-3：投机解码 EAGLE 的最新改进，论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1xnth6KEFB)
- **[165]. Mooncake：Kimi 的推理架构，FAST 2025 最佳论文，KV Cache 中心的存算分离，论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1cqYe6QEZW)
- **[166]. FlashInfer：MLSys 2025 最佳论文，vLLM、SGLang 都在用的注意力引擎，论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1cqYe6QEZC)
- **[167]. 投机解码：性能还是幻觉？MLSys 2026 在 vLLM 上的首次系统实测，论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1riYe6HEX2)
- **[168]. Fast_dLLM：给扩散大模型加 KV Cache，免训练提速 27 倍，论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1kiYe6HEFq)
- **[169]. NVFP4_Pretraining：英伟达用 4bit 预训练 12B 模型，10 万亿 token 不掉点，论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1riYe6HEfk)
- **[170]. SOAP_Muon_and_Beyond：英伟达实测，万亿 token 上超越 AdamW 的优化器，论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1piYe6pEcF)
- **[171]. MegaScale_MoE：字节 1440 卡训 352B MoE，比 Megatron 快 1.88 倍，论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1F6Ye6SEAe)
- **[172]. DualKV：GRPO 里被复制 32 遍的 prompt，终于不重复算了，论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1F6Ye6SEx6)
- **[173]. Kimi_K2：万亿 MoE 开源 Agent 模型，MuonClip 稳训练，论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1fwY165EtL)
- **[174]. DeepSeek_V3_2：DSA 稀疏注意力，长上下文大幅提速，论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1fwY165ES8)
- **[175]. Qwen3：快慢思考混合推理，多尺寸模型全家桶，论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1BwY165E6E)
- **[176]. Llama_3：Meta 405B 模型群，训练全细节公开，论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1fwY165EyC)
- **[177]. MiniMax_M1：Lightning Attention 撑起百万上下文推理，论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1KFe56uEqn)
- **[181]. GLM 5：智谱新一代旗舰，DSA 稀疏注意力 + 异步 RL 做 Agent 工程，论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV15rHv6mEMH)
- **[182]. Qwen3.5 Omni：混合注意力 MoE 全模态，ARIA 让语音合成更自然，论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV15rHv6mEjH)
- **[183]. Complex KDA：把 Kimi Delta Attention 升级到复数域，表达能力大幅增强，论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV15rHv6mEXm)
- **[184]. DeepSeek V4.1 Flash：KV Cache 压到 890 字节每 token，论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV13KHv66EtS)
- **[185]. DeepSeek DSec：为 Agent 强化学习打造的沙箱基础设施，论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1hKHv6rEme)
- **[186]. GLM OCR：0.9B 小模型 + 多 token 预测，OCR 解码不再逐字蹦，论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1QKHv6rEeg)
- **[187]. Gemini 2.5：谷歌经典模型，长上下文 + 多模态撬动 Agent 工作流，论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV183Hv6ME7a)
- **[188]. Scaling SAE：OpenAI 的稀疏自编码器缩放定律，可解释性工作，论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1b3Hv6MEod)
- **[189]. GLM 5.3：智谱基座没换，纯靠后训练 Scaling 编程暴涨，论文阅读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1YCpE6KEW1)
- **[190]. 字节 Seed 逮到 DeepSeek「神鬼二象性」：分块 KV Cache 带来 4-Token 周期，论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1ZapE6kEUj)
- **[34]. PPO：论文解读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1T2RrBvE25)
- **[36]. DPO：论文解读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV142RrBeE8E)
- **[38]. AlphaGo：论文解读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1t1RrBNELs)
- **[39]. 智能体强化学习论文串讲：WebRL、DigiRL、WebAgent-R1、AgentQ【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1f9RxBCEyN)
- **[41]. DeepSeek_GRPO：论文解读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1m1RrBNEhp)
- **[42]. DQN：论文解读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV141RrBNEd1)
- **[45]. AlphaZero：论文解读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1nERrB9E7d)
- **[47]. QLearning：论文解读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV14N5b6YEbS)
- **[48]. DAPO：论文解读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1tN5b6YEjF)
- **[131]. A3C：首次用异步 actor-critic 把深度 RL 做稳定，是 PPO的基石，论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1MYuG6rETy)
- **[135]. TRPO：PPO的前身，论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1xBuG6MEYJ)
- **[137]. MuZero：AlphaZero 之后关键的一步：直接学一个世界模型做 MCTS，论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1KBuG6MEwe)
- **[141]. Rainbow：把 DQN 的六大改进一次拼完，论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1BtbY6PEfW)
- **[156]. UCB1：多臂老虎机，论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV17MhG65E2o)
- **[157]. GSPO：GRPO 的改进，序列级重要性采样，论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1T7th6gELe)
- **[164]. InstructGPT：RLHF 的开山之作，论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1j2tG6qE5e)
- **[49]. ResNet：论文解读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1FXLJ6YE4U)
- **[50]. MobileNet：论文解读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1FXLJ6YExi)
- **[54]. ViT：论文解读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1JXLJ6YE1X)
- **[57]. CLIP：论文解读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1cQLJ6PE78)
- **[58]. MAE：论文解读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1zGLM6cEYG)
- **[60]. SAM：论文解读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1ktGe6NE1c)
- **[62]. FlowMatching：论文解读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1hiGx6oExa)
- **[63]. DETR：论文解读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1DiGx6oE4S)
- **[64]. YOLO：论文解读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV18iGx6oEo1)
- **[66]. DINO：论文解读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1bGVK6iEq7)
- **[68]. EfficientNet：论文解读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1zRVE6sEmR)
- **[69]. SwinTransformer：论文解读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1zRVE6sEU2)
- **[70]. UNet：论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1zRVE6sEz1)
- **[73]. FasterRCNN：论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1Wg7m6XEgG)
- **[74]. VGG：论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1Ag7m6XEy4)
- **[75]. GoogLeNet：论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1Pg7m6XEnq)
- **[76]. VAE：论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1Ag7m6XEyN)
- **[77]. DDPM：论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV176Js6DEaM)
- **[78]. CFG：论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV176Js6DE5W)
- **[81]. ProgressiveDistillation：论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1q6Js6DE2b)
- **[80]. GAN：论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV176Js6DEPp)
- **[84]. WGAN：论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV176Js6DELe)
- **[85]. NCSN：论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1LXjg6vEhk)
- **[86]. DDIM：论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1LXjg6vEPM)
- **[95]. SAM_2：论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1kv7q6RELS)
- **[91]. ConsistencyModels：论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1wv7q6dEtL)
- **[90]. EDM：论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1kv7q6REvQ)
- **[89]. LDM：论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1Av7q6dEKW)
- **[88]. DiffusionBeatGANs：论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1kv7q6REEK)
- **[87]. ScoreSDE：论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1kv7q6REtL)
- **[111]. Stable Diffusion：论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV19AN36iE8n)
- **[112]. SAM 3：论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV15wN36uEXx)
- **[114]. DiT：论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1UyK36YED6)
- **[118]. Rectified Flow：论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1hrKp6NEj5)
- **[121]. CNN，卷积网络经典重温：论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1Mdgh6aE5u)
- **[122]. MRP，借鉴MTP的思想用于扩散语言模型：论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV12Fga6fEuk)
- **[124]. DINO v2：论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1H4gh6HEdj)
- **[125]. ControlNet：论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1nB3r6UEPf)
- **[126]. DeepSeek OCR：论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1vY3y6UEaG)
- **[128]. DINOv3：论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1Dr3y6GEDX)
- **[132]. Conditional Flow Matching：条件流匹配，论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1TYuG6rEX1)
- **[143]. NeRF：神经辐射场三维重建，论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1zxbY6vEy9)
- **[145]. 3D Gaussian Splatting：3D高斯实时渲染，论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1zxbY6vEgk)
- **[147]. AlexNet：深度学习名作经典重温，论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1kEbY6gEvA)
- **[149]. Batch Norm：批量归一化经典重温，论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1ezbv6eEYm)
- **[161]. Instant NGP：把 NeRF 加速到秒级的哈希编码，论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV12nth6MEaj)
- **[162]. 2D Gaussian Splatting：3D 高斯的改进，几何重建更准，论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV12nth6TEAC)
- **[55]. ScaNN：向量检索论文解读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1FQLJ6PESa)
- **[61]. RaBitQ：向量检索论文解读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1AtGe6KEuV)
- **[97]. RaBitQ的改进工作：论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV18e7p6FEU6)
- **[123]. 向量检索ANNS经典论文：PQ论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1Kfgh68ErF)
- **[71]. Whisper：论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1Ag7m6XErq)
- **[155]. CTC：语音识别的经典损失函数，论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1f38h6cEcs)
- **[102]. ReAct：Agent经典论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1FRTi6oEz2)
- **[103]. Reflexion：Agent经典论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1cJTb6BE3S)
- **[130]. App Agent：大模型操作手机，GUI Agent论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1mvuG6gEHj)
- **[134]. SWE-agent：Agent处理GitHub issue的经典论文，论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1xBuG6MEuX)
- **[136]. Toolformer：大模型自发调用工具的开山之作，论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1NBuG6MEiP)
- **[138]. Voyager：Agent玩我的世界，论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1KiuG6zECG)
- **[140]. Mobile Agent：大模型操作手机，GUI Agent论文精读【每天一个宝藏论文】** - [B station](https://www.bilibili.com/video/BV1pPu26bEB6)
- **13. 旋转位置编码和复数欧拉公式有什么关系？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1qzFxzQES2)
- **14. 旋转位置编码和高中三角函数和差角公式有什么关系？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1uoFxzgEWz)
- **16. RoPE如何从2维推广到任意偶数维，奇数维咋办？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1FgcMzkE5h)
- **17. 为什么正余弦位置编码的注意力是和绝对位置相关的？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1mZcuztEw2)
- **19. 为什么RoPE中旋转矩阵R实际上不需要矩阵乘算子？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1XyFyzcEN6)
- **20. RoPE注意力的绝对位置无关性和欧拉公式有什么关系？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1fFFDzsEt6)
- **21. 为什么增大旋转位置编码中10000可提高模型外推能力【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1o5FozuEz2)
- **22. 为什么transformers.Llama的实现和RoPE原论文不一致？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1nUcbzTEGi)
- **23. Llama的旋转位置编码实现和RoPE原论文有何不同？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV15EcbzoEY7)
- **120. 任意矩阵满足什么性质就能成为RoPE旋转矩阵？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1TN5b6YE5q)
- **134. 为什么RoPE中旋转矩阵R0是单位阵？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1UGVK6vEzn)
- **138. 如何可视化含RoPE的注意力分数矩阵【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1FRVE6xEap)
- **147. 如何直观理解RoPE的平移不变性【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV18Aj36ZEZP)
- **25. 举例说明FlashAttention的分块矩阵乘法的正确性？【每天一个宝藏名词】** - [B station](https://www.bilibili.com/video/BV18pcLz2E3P)
- **28. 为什么在线Softmax比安全Softmax可以少一次循环？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1i6cnzzE2x)
- **30. 举例说明SlimAttention的分块矩阵乘法的正确性？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV11KcWz8EZm)
- **31. FlashAttention v2版本如何省略掩码上三角矩阵计算？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV16qZLBxEZt)
- **33. 用户改提示词为什么不会影响前面的KV Cache？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1dgZ7BQEHL)
- **34. BERT为什么没有KV Cache/KV Cache何以存在？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1qKZ7BsEs5)
- **36. 为什么推理时prefill是GEMM，而decode是（Batched）GEMV？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1UtZkBjEZP)
- **37. GQA中讲的共享指的是Token还是Head？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1cTZyBzEjv)
- **39. FlashAttention V2中为何要先循环Q后循环K？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1yiArzSEs1)
- **41 Flash Attention之前的那种N^2注意力不好在哪里？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1WzArzUEdr)
- **55. 为什么KV Cache也有LRU等缓存替换策略?【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1YdANzcESN)
- **56. 为什么多个Sub-Agent也可以共享前缀KV Cache？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1cPAuzpE6e)
- **68. prefill和decode时KV Cache是如何"堆积"的？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1AYQdBfEDS)
- **82. 在线Softmax和Flash Attention分别维护了多少个“动态规划量”？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1oA93BtETZ)
- **83. Flash Attention的线性显存比平方显存增长慢了多少？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1baNGzmEzn)
- **85. 为什么prefill和decode都可以跳过掩码上三角计算？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1ZEDvB9E6Y)
- **101. 如何用矩阵乘法链式法则速推Flash Attention梯度？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV12CoMB5EDJ)
- **102. PagedAttention是如何减少内存浪费的？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1EwoRBfExe)
- **106. Flash Attention反向传播也做到线性显存了吗？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1a89kB3EVu)
- **111. 如何直观理解KV Cache的显存计算公式？以Llama2-7B为例。【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1Tf9XBwEzM)
- **117. 如何用动态规划理解在线softmax的循环与归约？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1SHR9BuEBH)
- **141. 多轮对话中Decode之后还要增量Prefill，那新的KV如何并入KV Cache？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1zCjg6rE9F)
- **143. 如何可视化SGLang中的KV Cache？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV13Aj36ZEcC)
- **29. 以逐元素乘加为例，算子融合为什么能提高计算效率？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV19PcnzPEQp)
- **45. SIMD是如何加速张量计算的(简单理解)【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1doArzKExB)
- **49. 双缓冲是如何加速张量计算的？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1bUP5zDER5)
- **53. 如何加速两个张量之和？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1SqPhzAErH)
- **57. 网格步进是如何加速张量计算的？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1SSNFz2EDK)
- **97. 张量广播的线性索引是如何对应的？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1KyoMByEdR)
- **103. 多个线程执行同一段算子代码时发生了什么？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1JcoRB8EGb)
- **108. 如何用前缀和理解稀疏矩阵的CSR格式？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1k7RuBPEsV)
- **140. 稀疏矩阵乘稠密向量SpMV是如何跳过0值计算的？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1AG7m6HEEW)
- **162. 如何可视化GEMM？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1tWTj6jEGU)
- **163. 张量并行中的列并行和行并行是如何切分W和X矩阵的？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1rJTb6qEYr)
- **164. 为什么环形All-Reduce 时，4卡和128卡单卡通信量差不多？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1AzMP6rE61)
- **166. 如何用双缓冲优化GEMM？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1WzMP6rEN6)
- **168. Megatron张量并行如何用列切分加行切分降低FFN层的通信？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1zTMP6YEqg)
- **172. 如何用外积优化GEMM？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1E9Mb6MEeq)
- **178. 如何在SRAM和寄存器两个层级同时使用双缓冲优化GEMM？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1XEKG6gERb)
- **195. 如何用Tensor Core加速GEMM？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1xT3k6ZEP8)
- **42. 聚类量化和线性量化有何不同？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1yBArzEEeE)
- **44. 为什么把权重置0就是在剪枝？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1B9ArzuEP3)
- **62．LLM.int8是如何利用向量外积进行量化的？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV17pwEzMETL)
- **63. 举例说明SmoothQuant量化对角矩阵乘法的正确性？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1VTw7zbEzq)
- **64. SmoothQuant量化中有没有用到外积思想？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1DMwmzgEyV)
- **65. 从校准集说明为何SmoothQuant中的S无需矩阵乘算子【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV12DwRz9E4j)
- **66. LLM.int8与SmoothQuant解决离群值的思路有何异同？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV13rwCzwEKX)
- **67. 为何圆形山谷会让OBD剪枝退化为基于大小剪枝？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1qAA5ztELy)
- **71. OBD剪枝假设山谷是什么样的？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV11RQfB3Eot)
- **73. OBS剪枝保留与修改了OBD剪枝的哪些假设？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1njXKBnEBg)
- **74. 为什么OBD剪枝是特殊的OBS剪枝？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1xTXKB4Ecn)
- **75. OBS剪枝是如何选择被剪枝的权重的？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1AwX1BPE1g)
- **76. 为什么OBS剪枝可看作特殊的OBQ量化？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1cKX1BhED8)
- **78. GPTQ量化的最小化目标如何写成类似OBS形式的？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1679cBME93)
- **79. 为什么基于权重大小剪枝是特殊的OBD、OBS、OBQ？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1fn9cBKEbt)
- **80. 剪枝后微调让被置零的权重不再为零怎么办？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV16E9cBqEK8)
- **81. 量化后微调让聚在一起的权重分家了怎么办？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1zf9gBwEqd)
- **88. 量化后微调为什么要对聚类中心求和？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1fcD4BPEo7)
- **89. 量化感知训练是如何感知到量化的？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1d9QABeEdC)
- **90. OBQ如何将最小化剪枝损失推广到量化？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1kkDQBVE4y)
- **92. 为什么量化会让损失“山谷”变成“台阶”？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1eoQvBQEMF)
- **94. 量化感知训练中为什么要STE来处理round梯度？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV12qdaBkERq)
- **110. 为什么激活值per channel量化比per token量化难加速得多？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1k7RuBPEqt)
- **123. 如何用CPU内存的残差修正量化误差？以DecDEC为例【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1FXLJ6YEEv)
- **160. 如何对注意力头剪枝？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1YCTY6qEMZ)
- **219. 为什么把权重置0就是在剪枝？(新版)【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1rG4U6kE2E)
- **47 CLIP比较人性化的可视化可能长什么样？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1k4PDzrE9X)
- **59. DeepSeek OCR比较人性化的可视化可能是什么样的？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV13gcCzbE7y)
- **174. 为什么DDPM加噪相当于90°旋转插值？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1vAN36BEit)
- **181. 为什么 DDPM 加噪旋转角是不均匀的？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1YjKG6rEhy)
- **190. 为什么扩散模型采样高斯噪声相当于在球壳上选点？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV16V3762ECA)
- **193. 为什么前向KL让生成模型倾向平均，反向KL倾向专精？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1vo3w6wE6J)
- **198. 为什么逐点卷积可以用 GEMM 实现？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1BB3t6gEtZ)
- **205. 如何可视化VIT？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1t3up6iE8b)
- **206. 为什么DDPM加噪图在椭圆上，而Flow Matching在直线上？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1x2uN6SEAt)
- **210. 为什么ViT展平像素这一步是用卷积实现的？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV16M8h6AEY6)
- **212. 如何可视化UNet？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1quhG6CEtf)
- **32. 一种人性化的Transformer可视化可能是什么样的？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV13FZEBEE6y)
- **35. Transformer暗含多少种分块矩阵乘法的理解方式？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1pRZtBaEYv)
- **40. Temperature、TopK/P退化为贪婪解码的三种条件是？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1AzArzUEh1)
- **77. 为什么训练时教师强制是只“感觉”不“生成”的？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV14BXoBMEsk)
- **93. 为什么Transformer的核心公式是在做加权平均？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1CkQjBJE8K)
- **98. 为什么训练时上个词的概率预测不直接影响下个词？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1CSoMBgEUA)
- **99. MOE中先求Top K后Softmax，与先求Softmax后重归一化能一样？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1U6oMBjE1D)
- **104. 为什么训练时是同时预测token的？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1jNoRBoE9b)
- **107. DeepSeek V4如何使用Attention Sink忽略上下文？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1389kB3Ek4)
- **109. 最简单的Transformer可视化能有多简单？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1A7RuBNETS)
- **112. 如何可视化MOE？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1uGdgBnE65)
- **114. 为什么除以√dk是在给注意力升温？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1m5RmBSEkF)
- **118. 为什么Deepseek V3不用辅助损失也能做到MoE负载均衡？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1MyRXBvEG1)
- **119. 如何可视化多头注意力？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1235J6qENx)
- **121. 为什么GQA是MQA过渡到MHA的插值？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV16XLJ6YEVP)
- **122. 为什么只有单个词嵌入就能构成二元语言模型？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1FXLJ6YEwC)
- **124. 训练时是如何恰好错开一个token的？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1FXLJ6YE1L)
- **125. 为什么Token数相同的批次未必是负载均衡的？以WLB LLM为例【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1FXLJ6YEiX)
- **126. 举例说明投机解码如何拒绝采样？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1EVLM6bEuU)
- **127. 为什么Adam优化器相当于在求19日EMA均线？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1FGLM6wEbm)
- **128. 为什么4D并行的四个任务划分维度是正交的？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1ZzLC6bEbU)
- **130. 如何从概率树理解投机解码是无损的？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1ktGe6NEtg)
- **132. 为什么只用柱状图就能证明投机解码是无损的？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1UHGB6REeL)
- **133. 如何可视化超连接？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1h1GE6BEMm)
- **135. 如何直观理解超连接中的残差流？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1bGVK6iE2B)
- **136. BERT和GPT的可视化有多像？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1LsG26dEuq)
- **137. HC=？会让超连接退化为preNorm传统残差连接？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1zRVE6sE2x)
- **139. 为什么传统残差连接是mhc残差流扩展率=1 的特例？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1zRVE6sExg)
- **142. 如何可视化前馈网络｜线性层的反向传播？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1gAj36ZELC)
- **144. 如何可视化Transformer的残差连接？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1DAj36ZE2E)
- **145. 从prefill和decode角度理解投机解码何以加速？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1hAj36ZE7E)
- **146. 能否有一种方法同时可视化注意力的前向和反向传播？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1gAj36ZEUA)
- **148. 超连接中的连边和感知机的连边有何异同？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1DAj36ZEZD)
- **149. 为什么投机解码最多可以比K个Token多生成一个Token？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1gAj36ZEY3)
- **150. 对比注意力池和注意力温度对注意力汇聚有什么影响？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1hAj36ZE8a)
- **151. 如何可视化MQA？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1gAj36ZEmj)
- **152. 为什么前向残差连接对应反向残差连接【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1bv7p6bEeG)
- **153. 从等比数列求和理解Adam优化器训练初期动量修正【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1he7p6FEp1)
- **154. 为什么投机解码确保每轮至少产出一个 token？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1De7p6FEL3)
- **156. 最简单的transformer反向传播可视化能有多简单？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV18e7p6FE1J)
- **157. 为什么Adam除以√vt让稳定的梯度项归一化，振荡的梯度项归零化【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV13e7p6cEF4)
- **158. 最简单的含RoPE的Transformer可视化有多简单？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV18e7p6FEeD)
- **159. 如何可视化MTP？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1rtTc6tEqd)
- **161. MoE每个token都要选专家，那prefill要如何并行？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1foTi6sEyH)
- **165. 残差连接在Transformer反向传播中可视化出来是什么样的？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1AzMP6kE62)
- **169. MTP为什么能一次预测多个未来 token？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1aDMu6BEDb)
- **170. vLLM 投机解码首token合并 prefill 这个小技巧是怎么来的？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1hETD6mERB)
- **171. 如何可视化 DeepSeek MLA（简化版）？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1MRTd6bEbH)
- **173. 如何证明任意两句话的公共前缀都有相同的KV Cache？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1HNM76GEo8)
- **176. 如何可视化交叉注意力【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1RVKG6CEhW)
- **177. Megatron张量并行如何用列切分加行切分降低注意力层的通信？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1GEKG63EUT)
- **183. 为什么注意力要除以√dk而不是√d model【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1byK36eEUT)
- **185. 如何可视化kimi的注意力残差？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1qBKb6hEkq)
- **187. 为什么MLA无需显式解压Q和K？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV19s3K6zEXQ)
- **188. 预训练和SFT产生的初始梯度有何不同？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1Qz3g61EAe)
- **192. 如何证明注意力右上角加-∞就看不到后面了？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1N8gZ6NEzg)
- **194. 为什么滑动窗口注意力在 decode 时要使用环形缓存？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1WP3B65Eh5)
- **196. 为什么自注意力矩阵是正方形，而交叉注意力矩阵是长方形？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV17S316dExh)
- **199. FlashAttention如何加速滑动窗口注意力prefill？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1VKMX6bEo1)
- **201. 如何把RoPE算子融合到FlashAttention里？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1pmuA6gEN7)
- **202. 如何像之前可视化Transformer那样可视化RNN？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1njMy6UEzQ)
- **203. 推理时Q没有Cache，那训练时呢？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1njMy6UEmC)
- **204. 如何可视化 RWKV？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1s5un6dEKR)
- **207. 为什么MLA连V也不需要显式解压？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1pPu26bELp)
- **208. 如何证明Transformer本身不含位置信息？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1ezbv6eEC6)
- **209. 为什么同样是依赖上一隐藏状态，RWKV可以并行训练，而RNN不行？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1T8876rEaA)
- **214. 为什么MLA无需显式解压K和Q？(新版)【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1FE8Z63E5v)
- **215. 连续批处理如何把Prefill和Decode请求的FFN拼成一次矩阵乘？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1DrhF6PEtj)
- **216. 多轮对话中Decode之后还要增量Prefill，那新的KV如何并入KV Cache？(新版)【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1vYhF6zEud)
- **217. Chunked Prefill为什么要给长Prefill分块？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV12Xhw6YE5X)
- **218. 大模型的训练、推理、SFT、强化学习究竟有什么区别？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1wk4k6fEsY)
- **222. 为什么传统位置编码只作用于词嵌入，而RoPE每层都作用？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV16ath6fEMr)
- **223. 如何可视化MOE？(新版)【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1LUtG6KEkJ)
- **224. 如何证明因果掩码其实就已经内禀位置信息了？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1i2tG6qEZ8)
- **225. Deepseek的MLA是如何处理RoPE的？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1BWto6cEsD)
- **226. 最简单的transformer反向传播可视化能有多简单？(新版)【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1BHto6aE7P)
- **231. 从prefill和decode角度理解投机解码何以加速？(新版)【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1fwY165Eeq)
- **232. 为什么滑动窗口注意力在decode时要使用环形缓存？（新版）【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1sce56BEk1)
- **234. 为什么MLA连V也不需要显式解压？（新版）【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1YEeH6uECe)
- **236. 为什么自注意力矩阵是正方形，而交叉注意力矩阵是长方形？(新版)【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1cXeA6PEJR)
- **237. ViT如何使用RoPE？(1D简单版)【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1hheA6EEW2)
- **238. 扩散语言模型和自回归语言模型有何异同？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1mdhB6TEmr)
- **239. 如何可视化MTP？(新版)【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1mdhB6TEQE)
- **240. 为什么注意力要除以√dk而不是√d model？(新版)【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1MnhJ6JEKb)
- **241. 如何可视化GQA？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1e1ac6VEJF)
- **242. 交叉注意力输出的第i个向量代表什么？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1cFaT6uEky)
- **243. 为什么投机解码最多可以比K个Token多生成一个Token？(新版)【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV11Vhm6oEZ4)
- **244. 为什么KV Cache相当于Agent的短期记忆？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1CEhm6WEX3)
- **245. 为什么投机解码确保每轮至少产出一个 token？(新版)【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1CEhm6WER6)
- **247. 交叉注意力需要做旋转位置编码吗？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1Ksh96yEyN)
- **249. 最近大火的Jev和传统的LLM有何异同？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1MKa66VEJ4)
- **250. prefill和decode相当于RNN中的什么操作？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1s6He68EcV)
- **251. Pyramid KV为什么用金字塔形KV Cache？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1zcHr6uE2N)
- **252. KV Cache相当于RNN中的什么东西？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1FcHr6gEDq)
- **253. 什么是树形掩码？它和因果掩码有何异同？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV14UHJ6oE9E)
- **255. 树形注意力如何一次前向并行验证整棵草稿树？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1MRH26BE6z)
- **257. 一棵完美二叉树的树形注意力掩码是什么样的？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1mVHd64EGJ)
- **259. 如何证明任意两句话的公共前缀都有相同的KV Cache？(新版)【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1SGpn6NEfF)
- **58. 如何根据答案倒推合成思维链做SFT？以AscendKernelGen为例【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1DvcyzcEa4)
- **60. LoRA微调和向量外积为何长得很像？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1pKwjz3E1P)
- **84. LoRA要增加旁路，微调前后模型结构却可以不变，为什么？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1cQSSBvE8N)
- **96. LoRA微调中A、B都随机初始化或全零初始化分别会带来什么问题？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV15GdjByEpy)
- **182. 如何可视化知识蒸馏？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1UyK36YE3Z)
- **191. 如何可视化LoRA？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1Zq3j63Eeu)
- **46. 矩阵乘法对激活的梯度是怎么来的？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1ioArzKEMB)
- **51 矩阵乘法对权重的梯度是怎么来的？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1TUPWzkE6U)
- **52 简单的梯度算子是如何定义的【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1TUPWzkEgW)
- **61. 含广播的偏置b的梯度如何计算？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1WWXWBzELJ)
- **87. 为什么前向广播对应着反向归约？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV177DWBdEoV)
- **69. 深度学习中两种常用的矩阵微积分是怎么来的？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1a9XNBTERT)
- **70. 如何理解泰勒展开的多元函数扩展？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1HVXKBpE9p)
- **100. 为什么神经网络连接可以用矩阵乘法实现？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1SBoMBmEVB)
- **86. 为什么矩阵乘法可以看作标量乘法的拓展？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1WxDeBcExC)
- **72. 如何从几何视角理解拉格朗日乘子法？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1C3XKB9EHm)
- **95. 标量乘法的链式法则可以推广到矩阵吗？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1D8daB7En5)
- **105. K-Means聚类和中垂线有什么关系？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1Kk9kBAEnC)
- **113. 如何理解梯度下降的多元函数扩展？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1m5RmBSENE)
- **184. 一口气看完：正态分布，梯度下降、泰勒展开一元推广到多元【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1LvKw6UEuM)
- **115. 为什么梯度下降、泰勒展开、正态分布都有多元扩展？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1M5RmBDENg)
- **155. 为什么信息熵=最优码长，交叉熵=实际码长，KL散度=浪费码长【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV18e7p6FEZ1)
- **167. 为什么KL散度非负和信息熵是最优码长这两件事是等价的？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1fTMP6YEtZ)
- **175. 如何理解正态分布的多元扩展？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1eVKG6CEZH)
- **179. 如何用高中导数证明 KL 散度非负？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1GEKG6uEgV)
- **180. 向量如何对向量求导？推广到矩阵、张量呢？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1VjKG6kEpR)
- **189. 为什么反向传播的本质是乘雅可比矩阵？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV17Y356TEZu)
- **197. 为什么自动微分系统倾向于反向微分而非前向微分？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1ct3x6gEkq)
- **200. 为什么线性层反向传播也可以用GEMM实现？——为什么前向全连接对应反向全连接？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1t3uF6MEbd)
- **91. 游戏AI和LLM的πθ(a∣s)有何异同？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1TeD9B4EbF)
- **116. 如何从动态规划和记忆化搜索理解DQN？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1ygRXBZEQf)
- **129. 举例说明DPO论文里三行核心代码是啥意思？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1AtGe6KEbW)
- **131. 折扣因子γ是如何改变未来的奖励重要程度的？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1AtGe6KEuk)
- **186. 为什么交叉熵梯度相当于特殊的策略梯度？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1G2gh6BEg6)
- **211. 如何求PPO中每个token的梯度？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1juhG6CEmD)
- **213. 为什么GRPO可以扔掉价值网络？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1WC896BEPW)
- **220. PPO的损失计算和SFT有何异同？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV14Ctp6JEp6)
- **221. 为什么很多强化学习框架要内置vLLM这样的推理引擎加速采样？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV16ath6fEbM)
- **227. PPO中的优势A是怎么来的？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1mTtf6SEhx)
- **228. PPO的价值网络是如何根据写到一半的答案猜平均分的？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV163b46DE6F)
- **229. 为什么PPO的优势A是每个token一个，而GRPO是整段回答一个？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV151Yu6uERg)
- **230. PPO的GAE是如何计算的？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1weYR65EjZ)
- **233. 大模型强化学习的价值网络和围棋的价值网络有何异同？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1eEeH6uEiN)
- **235. 如何从PPO每个token的目标函数推导出梯度？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1cXeA6PEVh)
- **246. 为什么大模型RL里每一步的奖励几乎都是0？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1Tsh96yEAY)
- **254. PPO里面的KL约束到底在防什么？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1L5HC6uE4H)
- **256. 为什么PPO里的KL约束用的是反向KL而非前向KL？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV163Hm6dECv)
- **258. 什么是OPD（On-Policy Distillation）？【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1oQHR6rEvQ)
- **248. 新加坡-2026-会议留影【每天一个宝藏问题】** - [B station](https://www.bilibili.com/video/BV1bsaz63EV5)
- **[1]. 跑通TritonBench测试LLM的算子生成能力(ACL2025)【每周一个宝藏实验】** - [B station](https://www.bilibili.com/video/BV12xZBBwEKf)
- **[3] 从采摘200片三叶草开始训练一个简易无条件DDPM 【每周一个宝藏实验】** - [B station](https://www.bilibili.com/video/BV1PcfEBrEBs)
- **[5] 快速上手FuctionCall和React：极简易百词斩Agent【每周一个宝藏实验】** - [B station](https://www.bilibili.com/video/BV1nUAazDEma)
- **[7] 跑KernelBench测试LLM将PyTorch转译为CUDA代码的能力（ICML2025）【每周一个宝藏实验】** - [B station](https://www.bilibili.com/video/BV1gzPyzuERu)
- **[9] 跑CUDA-L2测试和cuBLAS相比效果如何？【每周一个宝藏实验】** - [B station](https://www.bilibili.com/video/BV1QPwszCE39)
- **[11] 跑robust-kbench测试LLM写算子，附Agent提示词【每周一个宝藏实验】** - [B station](https://www.bilibili.com/video/BV1vxAszpE3P)
- **[13] AutoDL上部署龙虾，它能帮忙测试算子性能吗？【每周一个宝藏实验】** - [B station](https://www.bilibili.com/video/BV1XMX5BZEGF)
- **1. BitNet 1.58b：微软开源的3值量化模型【每天一个宝藏名词】** - [B station](https://www.bilibili.com/video/BV1kG6jBSE3u)
- **2. AWQ：一种保护关键权重的LLM量化算法【每天一个宝藏名词】** - [B station](https://www.bilibili.com/video/BV16H6EBHEP5)
- **3. GPTQ：一种纯数学的LLM量化方法【每天一个宝藏名词】** - [B station](https://www.bilibili.com/video/BV1aXzXBNE4A)
- **4. SmoothQuant：一种转嫁压力的LLM量化方法【每天一个宝藏名词】** - [B station](https://www.bilibili.com/video/BV1RyzXB6Eyz)
- **7. SlimAttention：一种比FlashAttention更适合CPU的推理方案【每天一个宝藏名词】** - [B station](https://www.bilibili.com/video/BV1MUzZBVEtV)
- **8. PagedAttention：借鉴操作系统分页机制，内置于vLLM【每天一个宝藏名词】** - [B station](https://www.bilibili.com/video/BV1Ht6wBVEUX)
- **9. FlashAttention：将Attention的显存占用从平方级降到了线性级【每天一个宝藏名词】** - [B station](https://www.bilibili.com/video/BV1C66YBvECv)
- **10. NF4：QLoRA中的非均匀量化数据类型【每天一个宝藏名词】** - [B station](https://www.bilibili.com/video/BV1qA6BBKEck)
- **11. GQA：介于MHA和MQA之间，键值共享查询分组【每天一个宝藏名词】** - [B station](https://www.bilibili.com/video/BV19u6BBwEQ8)
- **12. RoPE：通过旋转矩阵让注意力只取决于相对位置【每天一个宝藏名词】** - [B station](https://www.bilibili.com/video/BV1gQ6iBREZw)
- **15. 投机解码：小模型草拟，大模型验证【每天一个宝藏名词】** - [B station](https://www.bilibili.com/video/BV1yS6zBXEVu)
- **27. 在线Softmax：通过修正比安全Softmax减少了一次循环【每天一个宝藏名词】** - [B station](https://www.bilibili.com/video/BV1c1c7zzEb4)
- **54. bf16：与FP32有相同的8位指数位，所以更适合模型训练【每天一个宝藏名词】** - [B station](https://www.bilibili.com/video/BV1DvPhzeE3R)
- **24. 思维树：大模型+DFS玩24点游戏成功率大增【每天一个宝藏名词】** - [B station](https://www.bilibili.com/video/BV1gtcbzDENr)
- **26. TinyML：MIT推出的大模型轻量化课，亲手量化一个本地llama模型【每天一个宝藏名词】** - [B station](https://www.bilibili.com/video/BV1CPcJzLELq)
- **5. CS336：斯坦福LLM神课，甚至包含洗数据和SFT【每天一个宝藏名词】** - [B station](https://www.bilibili.com/video/BV12pzXBREPY)
- **18. CCF-DDL：一个统计CCF分类和倒计时的宝藏网站【每天一个宝藏名词】** - [B station](https://www.bilibili.com/video/BV1Jif9BeEYE)
- **6. nano-vLLM：纯python实现的堪比vLLM的推理框架【每天一个宝藏名词】** - [B station](https://www.bilibili.com/video/BV1FTzfBcE3h)
- **38. miniSGLang：一个简化版SGLang，仅5000行python【每天一个宝藏名词】** - [B station](https://www.bilibili.com/video/BV1obA6zeEtE)
- **43. everything：比Windows默认文件搜索工具快很多，2MB的免费小工具【每天一个宝藏名词】** - [B station](https://www.bilibili.com/video/BV1iRArzqEvU)
- **48. NoteBookLM：Google的PPT制作神器，还有思维导图等一系列功能【每天一个宝藏名词】** - [B station](https://www.bilibili.com/video/BV1MUP5zDEmj)
- **50. 环境变量的工作原理：控制台启动时自动执行命令，让简写命令找到在哪执行【每天一个宝藏名词】** - [B station](https://www.bilibili.com/video/BV1zXP7zyEbD)