# 弹幕讨论 · 单卡、多卡 BERT、GPT2 训练性能【100亿模型计划】

> 视频：[BV1fG411G7eH](https://www.bilibili.com/video/BV1fG411G7eH)　时长 0:50:23　弹幕总数 **143**　有实质内容 **56** 条　重点标记 **56** 条
>
> 来源：B 站 **跟李沐学AI** 的该集弹幕　快照：**2026-10-12**

## 口径说明（务必先读）

**这些内容全部是观众在视频上发的弹幕，不是经过核实的结论。**

- 其中有价值的：概念解释、类比、勘误、学习方法、延伸阅读线索。
- **也可能有错误的**：弹幕是个人理解，未经作者或权威确认。
  **本页不为其正确性背书，请勿直接引用为事实。**
- 每条带时间戳，点击可跳回视频对应位置自行核对。
- 筛选口径：保留长度 ≥ 10 字符、且不含纯感叹/打卡类噪声的弹幕，共 56 条（占该集弹幕 143 条的 39.2%）；同一句话被多人发送只保留一条并标注发送次数。
- 「重点」标记由关键词打分得出（技术词 + 解释性措辞 + 长度 + 多人重复），共 56 条；**它是启发式排序，不代表正确性，也不代表其余条目无价值。**

## 重点条目

| 时间 | 弹幕 | 发送次数 |
|---|---|---:|
| [0:00:10](https://www.bilibili.com/video/BV1fG411G7eH?t=10) | 哥，你下次出镜前洗个头，显得你更帅一点 | 1 |
| [0:00:21](https://www.bilibili.com/video/BV1fG411G7eH?t=21) | 头发变多了，生发水哪买的？ | 1 |
| [0:00:24](https://www.bilibili.com/video/BV1fG411G7eH?t=24) | 好奇，这个我还真不清楚，感觉走pcie4.0应该够的 | 1 |
| [0:00:37](https://www.bilibili.com/video/BV1fG411G7eH?t=37) | 左下角北背景逼死强迫症 | 1 |
| [0:00:45](https://www.bilibili.com/video/BV1fG411G7eH?t=45) | 主要是40系漏的功耗太可怕了 | 1 |
| [0:01:09](https://www.bilibili.com/video/BV1fG411G7eH?t=69) | aws 首席科学家做数据分析还是用excel 哈哈哈哈哈哈哈哈或或 | 1 |
| [0:01:15](https://www.bilibili.com/video/BV1fG411G7eH?t=75) | 这不是excel，是google sheet | 1 |
| [0:01:35](https://www.bilibili.com/video/BV1fG411G7eH?t=95) | 更高的价格的倾向于显存容量而不是算力 | 1 |
| [0:01:51](https://www.bilibili.com/video/BV1fG411G7eH?t=111) | 这样看3080ti好像最划算 | 1 |
| [0:01:52](https://www.bilibili.com/video/BV1fG411G7eH?t=112) | 我的笔记本1060Ti | 1 |
| [0:01:56](https://www.bilibili.com/video/BV1fG411G7eH?t=116) | 3080是算力单价低，但是矿卡也最多 | 1 |
| [0:01:57](https://www.bilibili.com/video/BV1fG411G7eH?t=117) | 3080不是显存不够么 | 1 |
| [0:02:06](https://www.bilibili.com/video/BV1fG411G7eH?t=126) | 感觉3090性价比更高？ | 1 |
| [0:02:20](https://www.bilibili.com/video/BV1fG411G7eH?t=140) | 所以3080最划得来 | 1 |
| [0:02:20](https://www.bilibili.com/video/BV1fG411G7eH?t=140) | 谁自己买……都能报销，整最贵的就完事了 | 1 |
| [0:02:20](https://www.bilibili.com/video/BV1fG411G7eH?t=140) | 其实最不划算的是3080，最划算是90，这里图表有一定误导作用 | 1 |
| [0:02:20](https://www.bilibili.com/video/BV1fG411G7eH?t=140) | 不该说线性，应该是说斜率比较高 | 1 |
| [0:02:21](https://www.bilibili.com/video/BV1fG411G7eH?t=141) | 懂了，3080搞起来 | 1 |
| [0:02:36](https://www.bilibili.com/video/BV1fG411G7eH?t=156) | 为什么3060 的memory size 是 8 | 1 |
| [0:02:36](https://www.bilibili.com/video/BV1fG411G7eH?t=156) | 主要是之前的显卡降价太多 | 1 |
| [0:02:42](https://www.bilibili.com/video/BV1fG411G7eH?t=162) | 还是因为老黄怕amd yes | 1 |
| [0:02:42](https://www.bilibili.com/video/BV1fG411G7eH?t=162) | 3060不是12G？ | 1 |
| [0:02:43](https://www.bilibili.com/video/BV1fG411G7eH?t=163) | 我说怎么换大现存每个batch还是那么慢，原来卡在tflops上了 | 1 |
| [0:03:16](https://www.bilibili.com/video/BV1fG411G7eH?t=196) | 不值得，mini batch | 1 |
| [0:07:14](https://www.bilibili.com/video/BV1fG411G7eH?t=434) | adam是谁（doge） | 1 |
| [0:07:15](https://www.bilibili.com/video/BV1fG411G7eH?t=435) | 233确实错误，因为能找到不收敛的例子 | 1 |
| [0:07:19](https://www.bilibili.com/video/BV1fG411G7eH?t=439) | 可是现在大模型基本都是用这个adamw | 1 |
| [0:10:16](https://www.bilibili.com/video/BV1fG411G7eH?t=616) | 这段实验代码写的赏心悦目 | 1 |
| [0:10:25](https://www.bilibili.com/video/BV1fG411G7eH?t=625) | 格式化工具可以让代码好看很多 | 1 |
| [0:11:36](https://www.bilibili.com/video/BV1fG411G7eH?t=696) | 前面的总结：用python 跑测试做参数变量声明！！ | 1 |
| [0:15:19](https://www.bilibili.com/video/BV1fG411G7eH?t=919) | 主要是large模型太大了吧，占用显存比较多 | 1 |
| [0:17:23](https://www.bilibili.com/video/BV1fG411G7eH?t=1043) | 这是实验真的太优雅啊 | 1 |
| [0:17:48](https://www.bilibili.com/video/BV1fG411G7eH?t=1068) | 有趣的是在GitHub上的文档依然是有错的 | 1 |
| [0:17:48](https://www.bilibili.com/video/BV1fG411G7eH?t=1068) | 就在这一个剪切的画面， with 32-bit被修正成了with 16-bit | 1 |
| [0:17:53](https://www.bilibili.com/video/BV1fG411G7eH?t=1073) | 是的 混合精度的官方教程也写了这个 | 1 |
| [0:19:48](https://www.bilibili.com/video/BV1fG411G7eH?t=1188) | 暂停看解释就很清楚了 | 1 |
| [0:19:55](https://www.bilibili.com/video/BV1fG411G7eH?t=1195) | 记一下，值得细细研究 | 1 |
| [0:27:30](https://www.bilibili.com/video/BV1fG411G7eH?t=1650) | 真是手把手教你训大模型啊 | 1 |
| [0:31:29](https://www.bilibili.com/video/BV1fG411G7eH?t=1889) | 刚刚外面有人飙车是吗 | 1 |
| [0:31:35](https://www.bilibili.com/video/BV1fG411G7eH?t=1895) | 对于机械专业的我晕的一 | 1 |
| [0:31:59](https://www.bilibili.com/video/BV1fG411G7eH?t=1919) | 哈哈2024年才开始用fp8训练 | 1 |
| [0:34:05](https://www.bilibili.com/video/BV1fG411G7eH?t=2045) | 因为一个通道x16、一个通道x8，插了两张卡，就按照x8通信了 | 1 |
| [0:35:25](https://www.bilibili.com/video/BV1fG411G7eH?t=2125) | 实验室的8卡A100没有NVLink，多卡训练提升很少，感觉有点暴殄天物。。。 | 1 |
| [0:35:37](https://www.bilibili.com/video/BV1fG411G7eH?t=2137) | 这双卡与单卡比提升太小了 | 1 |
| [0:35:53](https://www.bilibili.com/video/BV1fG411G7eH?t=2153) | 感觉用deepspeed速度没降太多啊 | 1 |
| [0:37:26](https://www.bilibili.com/video/BV1fG411G7eH?t=2246) | 为什么3亿参数要发6亿梯度？ | 1 |
| [0:37:29](https://www.bilibili.com/video/BV1fG411G7eH?t=2249) | 因为有两张卡，每张发3e，总共6e | 1 |
| [0:37:29](https://www.bilibili.com/video/BV1fG411G7eH?t=2249) | 因为ring-all reduce 的通讯量近乎是2*模型参数 | 1 |
| [0:42:26](https://www.bilibili.com/video/BV1fG411G7eH?t=2546) | 梯度累加不增加内存吗 | 1 |
| [0:48:08](https://www.bilibili.com/video/BV1fG411G7eH?t=2888) | 这个作业成本有点高啊 | 1 |
| [0:48:59](https://www.bilibili.com/video/BV1fG411G7eH?t=2939) | 这练习是不是要两块3090才行？ | 1 |
| [0:49:12](https://www.bilibili.com/video/BV1fG411G7eH?t=2952) | 算了我笔记本的3060捉襟见肘 | 1 |
| [0:49:40](https://www.bilibili.com/video/BV1fG411G7eH?t=2980) | 马上用新买的5090试试 | 1 |
| [0:49:41](https://www.bilibili.com/video/BV1fG411G7eH?t=2981) | v100 是不是就告别bf16了？ | 1 |
| [0:49:47](https://www.bilibili.com/video/BV1fG411G7eH?t=2987) | 3060-12G  贫民窟首选 | 1 |
| [0:50:22](https://www.bilibili.com/video/BV1fG411G7eH?t=3022) | 做练习题去了，期待6卡机器哈哈哈 | 1 |

## 全部有实质内容的弹幕（按时间排序，共 56 条）

- `0:00:10`**哥，你下次出镜前洗个头，显得你更帅一点**　[↗](https://www.bilibili.com/video/BV1fG411G7eH?t=10)
- `0:00:21`**头发变多了，生发水哪买的？**　[↗](https://www.bilibili.com/video/BV1fG411G7eH?t=21)
- `0:00:24`**好奇，这个我还真不清楚，感觉走pcie4.0应该够的**　[↗](https://www.bilibili.com/video/BV1fG411G7eH?t=24)
- `0:00:37`**左下角北背景逼死强迫症**　[↗](https://www.bilibili.com/video/BV1fG411G7eH?t=37)
- `0:00:45`**主要是40系漏的功耗太可怕了**　[↗](https://www.bilibili.com/video/BV1fG411G7eH?t=45)
- `0:01:09`**aws 首席科学家做数据分析还是用excel 哈哈哈哈哈哈哈哈或或**　[↗](https://www.bilibili.com/video/BV1fG411G7eH?t=69)
- `0:01:15`**这不是excel，是google sheet**　[↗](https://www.bilibili.com/video/BV1fG411G7eH?t=75)
- `0:01:35`**更高的价格的倾向于显存容量而不是算力**　[↗](https://www.bilibili.com/video/BV1fG411G7eH?t=95)
- `0:01:51`**这样看3080ti好像最划算**　[↗](https://www.bilibili.com/video/BV1fG411G7eH?t=111)
- `0:01:52`**我的笔记本1060Ti**　[↗](https://www.bilibili.com/video/BV1fG411G7eH?t=112)
- `0:01:56`**3080是算力单价低，但是矿卡也最多**　[↗](https://www.bilibili.com/video/BV1fG411G7eH?t=116)
- `0:01:57`**3080不是显存不够么**　[↗](https://www.bilibili.com/video/BV1fG411G7eH?t=117)
- `0:02:06`**感觉3090性价比更高？**　[↗](https://www.bilibili.com/video/BV1fG411G7eH?t=126)
- `0:02:20`**所以3080最划得来**　[↗](https://www.bilibili.com/video/BV1fG411G7eH?t=140)
- `0:02:20`**谁自己买……都能报销，整最贵的就完事了**　[↗](https://www.bilibili.com/video/BV1fG411G7eH?t=140)
- `0:02:20`**其实最不划算的是3080，最划算是90，这里图表有一定误导作用**　[↗](https://www.bilibili.com/video/BV1fG411G7eH?t=140)
- `0:02:20`**不该说线性，应该是说斜率比较高**　[↗](https://www.bilibili.com/video/BV1fG411G7eH?t=140)
- `0:02:21`**懂了，3080搞起来**　[↗](https://www.bilibili.com/video/BV1fG411G7eH?t=141)
- `0:02:36`**为什么3060 的memory size 是 8**　[↗](https://www.bilibili.com/video/BV1fG411G7eH?t=156)
- `0:02:36`**主要是之前的显卡降价太多**　[↗](https://www.bilibili.com/video/BV1fG411G7eH?t=156)
- `0:02:42`**还是因为老黄怕amd yes**　[↗](https://www.bilibili.com/video/BV1fG411G7eH?t=162)
- `0:02:42`**3060不是12G？**　[↗](https://www.bilibili.com/video/BV1fG411G7eH?t=162)
- `0:02:43`**我说怎么换大现存每个batch还是那么慢，原来卡在tflops上了**　[↗](https://www.bilibili.com/video/BV1fG411G7eH?t=163)
- `0:03:16`**不值得，mini batch**　[↗](https://www.bilibili.com/video/BV1fG411G7eH?t=196)
- `0:07:14`**adam是谁（doge）**　[↗](https://www.bilibili.com/video/BV1fG411G7eH?t=434)
- `0:07:15`**233确实错误，因为能找到不收敛的例子**　[↗](https://www.bilibili.com/video/BV1fG411G7eH?t=435)
- `0:07:19`**可是现在大模型基本都是用这个adamw**　[↗](https://www.bilibili.com/video/BV1fG411G7eH?t=439)
- `0:10:16`**这段实验代码写的赏心悦目**　[↗](https://www.bilibili.com/video/BV1fG411G7eH?t=616)
- `0:10:25`**格式化工具可以让代码好看很多**　[↗](https://www.bilibili.com/video/BV1fG411G7eH?t=625)
- `0:11:36`**前面的总结：用python 跑测试做参数变量声明！！**　[↗](https://www.bilibili.com/video/BV1fG411G7eH?t=696)
- `0:15:19`**主要是large模型太大了吧，占用显存比较多**　[↗](https://www.bilibili.com/video/BV1fG411G7eH?t=919)
- `0:17:23`**这是实验真的太优雅啊**　[↗](https://www.bilibili.com/video/BV1fG411G7eH?t=1043)
- `0:17:48`**有趣的是在GitHub上的文档依然是有错的**　[↗](https://www.bilibili.com/video/BV1fG411G7eH?t=1068)
- `0:17:48`**就在这一个剪切的画面， with 32-bit被修正成了with 16-bit**　[↗](https://www.bilibili.com/video/BV1fG411G7eH?t=1068)
- `0:17:53`**是的 混合精度的官方教程也写了这个**　[↗](https://www.bilibili.com/video/BV1fG411G7eH?t=1073)
- `0:19:48`**暂停看解释就很清楚了**　[↗](https://www.bilibili.com/video/BV1fG411G7eH?t=1188)
- `0:19:55`**记一下，值得细细研究**　[↗](https://www.bilibili.com/video/BV1fG411G7eH?t=1195)
- `0:27:30`**真是手把手教你训大模型啊**　[↗](https://www.bilibili.com/video/BV1fG411G7eH?t=1650)
- `0:31:29`**刚刚外面有人飙车是吗**　[↗](https://www.bilibili.com/video/BV1fG411G7eH?t=1889)
- `0:31:35`**对于机械专业的我晕的一**　[↗](https://www.bilibili.com/video/BV1fG411G7eH?t=1895)
- `0:31:59`**哈哈2024年才开始用fp8训练**　[↗](https://www.bilibili.com/video/BV1fG411G7eH?t=1919)
- `0:34:05`**因为一个通道x16、一个通道x8，插了两张卡，就按照x8通信了**　[↗](https://www.bilibili.com/video/BV1fG411G7eH?t=2045)
- `0:35:25`**实验室的8卡A100没有NVLink，多卡训练提升很少，感觉有点暴殄天物。。。**　[↗](https://www.bilibili.com/video/BV1fG411G7eH?t=2125)
- `0:35:37`**这双卡与单卡比提升太小了**　[↗](https://www.bilibili.com/video/BV1fG411G7eH?t=2137)
- `0:35:53`**感觉用deepspeed速度没降太多啊**　[↗](https://www.bilibili.com/video/BV1fG411G7eH?t=2153)
- `0:37:26`**为什么3亿参数要发6亿梯度？**　[↗](https://www.bilibili.com/video/BV1fG411G7eH?t=2246)
- `0:37:29`**因为有两张卡，每张发3e，总共6e**　[↗](https://www.bilibili.com/video/BV1fG411G7eH?t=2249)
- `0:37:29`**因为ring-all reduce 的通讯量近乎是2*模型参数**　[↗](https://www.bilibili.com/video/BV1fG411G7eH?t=2249)
- `0:42:26`**梯度累加不增加内存吗**　[↗](https://www.bilibili.com/video/BV1fG411G7eH?t=2546)
- `0:48:08`**这个作业成本有点高啊**　[↗](https://www.bilibili.com/video/BV1fG411G7eH?t=2888)
- `0:48:59`**这练习是不是要两块3090才行？**　[↗](https://www.bilibili.com/video/BV1fG411G7eH?t=2939)
- `0:49:12`**算了我笔记本的3060捉襟见肘**　[↗](https://www.bilibili.com/video/BV1fG411G7eH?t=2952)
- `0:49:40`**马上用新买的5090试试**　[↗](https://www.bilibili.com/video/BV1fG411G7eH?t=2980)
- `0:49:41`**v100 是不是就告别bf16了？**　[↗](https://www.bilibili.com/video/BV1fG411G7eH?t=2981)
- `0:49:47`**3060-12G  贫民窟首选**　[↗](https://www.bilibili.com/video/BV1fG411G7eH?t=2987)
- `0:50:22`**做练习题去了，期待6卡机器哈哈哈**　[↗](https://www.bilibili.com/video/BV1fG411G7eH?t=3022)
