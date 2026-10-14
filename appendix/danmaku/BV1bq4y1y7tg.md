# 弹幕讨论 · 11.2 NLP中的微调【斯坦福21秋季：实用机器学习中文版】

> 视频：[BV1bq4y1y7tg](https://www.bilibili.com/video/BV1bq4y1y7tg)　时长 0:21:25　弹幕总数 **75**　有实质内容 **32** 条　重点标记 **32** 条
>
> 来源：B 站 **跟李沐学AI** 的该集弹幕　快照：**2026-10-14**

## 口径说明（务必先读）

**这些内容全部是观众在视频上发的弹幕，不是经过核实的结论。**

- 其中有价值的：概念解释、类比、勘误、学习方法、延伸阅读线索。
- **也可能有错误的**：弹幕是个人理解，未经作者或权威确认。
  **本页不为其正确性背书，请勿直接引用为事实。**
- 每条带时间戳，点击可跳回视频对应位置自行核对。
- 筛选口径：保留长度 ≥ 10 字符、且不含纯感叹/打卡类噪声的弹幕，共 32 条（占该集弹幕 75 条的 42.7%）；同一句话被多人发送只保留一条并标注发送次数。
- 「重点」标记由关键词打分得出（技术词 + 解释性措辞 + 长度 + 多人重复），共 32 条；**它是启发式排序，不代表正确性，也不代表其余条目无价值。**

## 重点条目

| 时间 | 弹幕 | 发送次数 |
|---|---|---:|
| [0:00:02](https://www.bilibili.com/video/BV1bq4y1y7tg?t=2) | 斯坦福cs329p实用机器学习系列怎么不跟新了？ | 1 |
| [0:00:14](https://www.bilibili.com/video/BV1bq4y1y7tg?t=14) | 我猜有一些是放在论文精读了 | 1 |
| [0:00:17](https://www.bilibili.com/video/BV1bq4y1y7tg?t=17) | 完结撒花咯 大家工作面试顺利！ | 1 |
| [0:00:29](https://www.bilibili.com/video/BV1bq4y1y7tg?t=29) | cv 有图片分类的数据集 | 1 |
| [0:02:14](https://www.bilibili.com/video/BV1bq4y1y7tg?t=134) | 通过自己自监督训练，得到预训练的模型 | 1 |
| [0:02:16](https://www.bilibili.com/video/BV1bq4y1y7tg?t=136) | 这样应该有，在某个训练集，自监督训练好的模型吧？ | 1 |
| [0:02:24](https://www.bilibili.com/video/BV1bq4y1y7tg?t=144) | 万一预测的green | 1 |
| [0:02:34](https://www.bilibili.com/video/BV1bq4y1y7tg?t=154) | your -&gt;green | 1 |
| [0:02:37](https://www.bilibili.com/video/BV1bq4y1y7tg?t=157) | green是有什么病呢，在这抖机灵 | 1 |
| [0:03:02](https://www.bilibili.com/video/BV1bq4y1y7tg?t=182) | 词嵌入 就是一个词  用两个向量表示 | 1 |
| [0:03:27](https://www.bilibili.com/video/BV1bq4y1y7tg?t=207) | 这就是word2vec | 1 |
| [0:04:09](https://www.bilibili.com/video/BV1bq4y1y7tg?t=249) | 左右两边的每个的字的词向量加起来得到一个向量 | 1 |
| [0:04:42](https://www.bilibili.com/video/BV1bq4y1y7tg?t=282) | 周围的词的 v 怎么来了？ | 1 |
| [0:05:18](https://www.bilibili.com/video/BV1bq4y1y7tg?t=318) | 最初这些v和w是怎么来的?这里只说怎么预测？ | 1 |
| [0:05:27](https://www.bilibili.com/video/BV1bq4y1y7tg?t=327) | 这个负样本怎么做的？ | 1 |
| [0:05:47](https://www.bilibili.com/video/BV1bq4y1y7tg?t=347) | 又复习了一遍word2vec | 1 |
| [0:08:30](https://www.bilibili.com/video/BV1bq4y1y7tg?t=510) | 不难，直接用也挺有效，就是大了点训练代价大 | 1 |
| [0:08:56](https://www.bilibili.com/video/BV1bq4y1y7tg?t=536) | 记得代码是每句后面都有&lt;sep&gt; | 1 |
| [0:09:23](https://www.bilibili.com/video/BV1bq4y1y7tg?t=563) | 和CV很像，也就是计算机视觉 | 1 |
| [0:11:26](https://www.bilibili.com/video/BV1bq4y1y7tg?t=686) | 问答，和阅读理解是一回事吗 | 1 |
| [0:13:40](https://www.bilibili.com/video/BV1bq4y1y7tg?t=820) | 确实，AdamW在微调的时候，收敛效果很多时候都比Adam好一点 | 1 |
| [0:15:03](https://www.bilibili.com/video/BV1bq4y1y7tg?t=903) | 只要训练结果好，参数随便改好吧 | 1 |
| [0:15:13](https://www.bilibili.com/video/BV1bq4y1y7tg?t=913) | 这样需要全部数据集嘛 | 1 |
| [0:16:09](https://www.bilibili.com/video/BV1bq4y1y7tg?t=969) | 真的搞笑，东抄抄西抄抄 | 1 |
| [0:16:28](https://www.bilibili.com/video/BV1bq4y1y7tg?t=988) | 词元哪里来？word2vec？ | 1 |
| [0:18:44](https://www.bilibili.com/video/BV1bq4y1y7tg?t=1124) | 那sentence，就是一串字符串吗，把所有东西串起来 | 1 |
| [0:19:37](https://www.bilibili.com/video/BV1bq4y1y7tg?t=1177) | 为什么是编码器架构？ | 1 |
| [0:20:10](https://www.bilibili.com/video/BV1bq4y1y7tg?t=1210) | T5现在都不咋用了好像 | 1 |
| [0:20:15](https://www.bilibili.com/video/BV1bq4y1y7tg?t=1215) | 没有GPT-3的few-shot 讲解吗？ | 1 |
| [0:20:16](https://www.bilibili.com/video/BV1bq4y1y7tg?t=1216) | qa机器人石乐志，哈哈 | 1 |
| [0:20:18](https://www.bilibili.com/video/BV1bq4y1y7tg?t=1218) | 现在有GLM可以博采众长 | 1 |
| [0:21:24](https://www.bilibili.com/video/BV1bq4y1y7tg?t=1284) | 受益匪浅，继续等待下一个NLP更新 | 1 |

## 全部有实质内容的弹幕（按时间排序，共 32 条）

- `0:00:02`**斯坦福cs329p实用机器学习系列怎么不跟新了？**　[↗](https://www.bilibili.com/video/BV1bq4y1y7tg?t=2)
- `0:00:14`**我猜有一些是放在论文精读了**　[↗](https://www.bilibili.com/video/BV1bq4y1y7tg?t=14)
- `0:00:17`**完结撒花咯 大家工作面试顺利！**　[↗](https://www.bilibili.com/video/BV1bq4y1y7tg?t=17)
- `0:00:29`**cv 有图片分类的数据集**　[↗](https://www.bilibili.com/video/BV1bq4y1y7tg?t=29)
- `0:02:14`**通过自己自监督训练，得到预训练的模型**　[↗](https://www.bilibili.com/video/BV1bq4y1y7tg?t=134)
- `0:02:16`**这样应该有，在某个训练集，自监督训练好的模型吧？**　[↗](https://www.bilibili.com/video/BV1bq4y1y7tg?t=136)
- `0:02:24`**万一预测的green**　[↗](https://www.bilibili.com/video/BV1bq4y1y7tg?t=144)
- `0:02:34`**your -&gt;green**　[↗](https://www.bilibili.com/video/BV1bq4y1y7tg?t=154)
- `0:02:37`**green是有什么病呢，在这抖机灵**　[↗](https://www.bilibili.com/video/BV1bq4y1y7tg?t=157)
- `0:03:02`**词嵌入 就是一个词  用两个向量表示**　[↗](https://www.bilibili.com/video/BV1bq4y1y7tg?t=182)
- `0:03:27`**这就是word2vec**　[↗](https://www.bilibili.com/video/BV1bq4y1y7tg?t=207)
- `0:04:09`**左右两边的每个的字的词向量加起来得到一个向量**　[↗](https://www.bilibili.com/video/BV1bq4y1y7tg?t=249)
- `0:04:42`**周围的词的 v 怎么来了？**　[↗](https://www.bilibili.com/video/BV1bq4y1y7tg?t=282)
- `0:05:18`**最初这些v和w是怎么来的?这里只说怎么预测？**　[↗](https://www.bilibili.com/video/BV1bq4y1y7tg?t=318)
- `0:05:27`**这个负样本怎么做的？**　[↗](https://www.bilibili.com/video/BV1bq4y1y7tg?t=327)
- `0:05:47`**又复习了一遍word2vec**　[↗](https://www.bilibili.com/video/BV1bq4y1y7tg?t=347)
- `0:08:30`**不难，直接用也挺有效，就是大了点训练代价大**　[↗](https://www.bilibili.com/video/BV1bq4y1y7tg?t=510)
- `0:08:56`**记得代码是每句后面都有&lt;sep&gt;**　[↗](https://www.bilibili.com/video/BV1bq4y1y7tg?t=536)
- `0:09:23`**和CV很像，也就是计算机视觉**　[↗](https://www.bilibili.com/video/BV1bq4y1y7tg?t=563)
- `0:11:26`**问答，和阅读理解是一回事吗**　[↗](https://www.bilibili.com/video/BV1bq4y1y7tg?t=686)
- `0:13:40`**确实，AdamW在微调的时候，收敛效果很多时候都比Adam好一点**　[↗](https://www.bilibili.com/video/BV1bq4y1y7tg?t=820)
- `0:15:03`**只要训练结果好，参数随便改好吧**　[↗](https://www.bilibili.com/video/BV1bq4y1y7tg?t=903)
- `0:15:13`**这样需要全部数据集嘛**　[↗](https://www.bilibili.com/video/BV1bq4y1y7tg?t=913)
- `0:16:09`**真的搞笑，东抄抄西抄抄**　[↗](https://www.bilibili.com/video/BV1bq4y1y7tg?t=969)
- `0:16:28`**词元哪里来？word2vec？**　[↗](https://www.bilibili.com/video/BV1bq4y1y7tg?t=988)
- `0:18:44`**那sentence，就是一串字符串吗，把所有东西串起来**　[↗](https://www.bilibili.com/video/BV1bq4y1y7tg?t=1124)
- `0:19:37`**为什么是编码器架构？**　[↗](https://www.bilibili.com/video/BV1bq4y1y7tg?t=1177)
- `0:20:10`**T5现在都不咋用了好像**　[↗](https://www.bilibili.com/video/BV1bq4y1y7tg?t=1210)
- `0:20:15`**没有GPT-3的few-shot 讲解吗？**　[↗](https://www.bilibili.com/video/BV1bq4y1y7tg?t=1215)
- `0:20:16`**qa机器人石乐志，哈哈**　[↗](https://www.bilibili.com/video/BV1bq4y1y7tg?t=1216)
- `0:20:18`**现在有GLM可以博采众长**　[↗](https://www.bilibili.com/video/BV1bq4y1y7tg?t=1218)
- `0:21:24`**受益匪浅，继续等待下一个NLP更新**　[↗](https://www.bilibili.com/video/BV1bq4y1y7tg?t=1284)
