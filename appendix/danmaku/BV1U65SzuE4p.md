# 弹幕讨论 · 视频生成·下：模型和训练【论文精读·55】

> 视频：[BV1U65SzuE4p](https://www.bilibili.com/video/BV1U65SzuE4p)　时长 1:02:50　弹幕总数 **43**　有实质内容 **14** 条　重点标记 **14** 条
>
> 来源：B 站 **跟李沐学AI** 的该集弹幕　快照：**2026-10-14**

## 口径说明（务必先读）

**这些内容全部是观众在视频上发的弹幕，不是经过核实的结论。**

- 其中有价值的：概念解释、类比、勘误、学习方法、延伸阅读线索。
- **也可能有错误的**：弹幕是个人理解，未经作者或权威确认。
  **本页不为其正确性背书，请勿直接引用为事实。**
- 每条带时间戳，点击可跳回视频对应位置自行核对。
- 筛选口径：保留长度 ≥ 10 字符、且不含纯感叹/打卡类噪声的弹幕，共 14 条（占该集弹幕 43 条的 32.6%）；同一句话被多人发送只保留一条并标注发送次数。
- 「重点」标记由关键词打分得出（技术词 + 解释性措辞 + 长度 + 多人重复），共 14 条；**它是启发式排序，不代表正确性，也不代表其余条目无价值。**

## 重点条目

| 时间 | 弹幕 | 发送次数 |
|---|---|---:|
| [0:00:00](https://www.bilibili.com/video/BV1U65SzuE4p?t=0) | 早晨一到工位就上课！！ | 1 |
| [0:00:11](https://www.bilibili.com/video/BV1U65SzuE4p?t=11) | 真是每一个都是经典呀 | 1 |
| [0:01:08](https://www.bilibili.com/video/BV1U65SzuE4p?t=68) | 怎么感觉和上半部没接上 | 1 |
| [0:39:33](https://www.bilibili.com/video/BV1U65SzuE4p?t=2373) | “可能就是忘了吧，TPU那么多” | 1 |
| [0:40:59](https://www.bilibili.com/video/BV1U65SzuE4p?t=2459) | 早上八点就有十几个人了 | 1 |
| [0:43:41](https://www.bilibili.com/video/BV1U65SzuE4p?t=2621) | 这个flow matching的解释没看懂，似乎和ddpm没区别，还是用加噪 | 1 |
| [0:43:45](https://www.bilibili.com/video/BV1U65SzuE4p?t=2625) | 可以去看看代码，比公式好理解 | 1 |
| [0:43:54](https://www.bilibili.com/video/BV1U65SzuE4p?t=2634) | 我以为能给我讲明白到底为啥这俩是等价的，其实还是没有doge | 1 |
| [0:46:47](https://www.bilibili.com/video/BV1U65SzuE4p?t=2807) | 为什么速度vt和时间无关，模型预测得速度还要输入t作为参数 | 1 |
| [0:46:55](https://www.bilibili.com/video/BV1U65SzuE4p?t=2815) | 因为这training，inference需要aware到T | 1 |
| [0:46:56](https://www.bilibili.com/video/BV1U65SzuE4p?t=2816) | 因为你得知道现在分布变换到哪一步了，虽然OT是直线，但推理中由于存在交叉，实际预测的V并不是指向目标分布 | 1 |
| [0:48:26](https://www.bilibili.com/video/BV1U65SzuE4p?t=2906) | OT实际也不直，因为存在多条路径交叉的情况，否则直接一步采样就可以变换了，实际仍要多步采样 | 1 |
| [0:57:59](https://www.bilibili.com/video/BV1U65SzuE4p?t=3479) | 12月底录视频但是4月中发 | 1 |
| [1:02:33](https://www.bilibili.com/video/BV1U65SzuE4p?t=3753) | 完结待续:D_JYQ | 1 |

## 全部有实质内容的弹幕（按时间排序，共 14 条）

- `0:00:00`**早晨一到工位就上课！！**　[↗](https://www.bilibili.com/video/BV1U65SzuE4p?t=0)
- `0:00:11`**真是每一个都是经典呀**　[↗](https://www.bilibili.com/video/BV1U65SzuE4p?t=11)
- `0:01:08`**怎么感觉和上半部没接上**　[↗](https://www.bilibili.com/video/BV1U65SzuE4p?t=68)
- `0:39:33`**“可能就是忘了吧，TPU那么多”**　[↗](https://www.bilibili.com/video/BV1U65SzuE4p?t=2373)
- `0:40:59`**早上八点就有十几个人了**　[↗](https://www.bilibili.com/video/BV1U65SzuE4p?t=2459)
- `0:43:41`**这个flow matching的解释没看懂，似乎和ddpm没区别，还是用加噪**　[↗](https://www.bilibili.com/video/BV1U65SzuE4p?t=2621)
- `0:43:45`**可以去看看代码，比公式好理解**　[↗](https://www.bilibili.com/video/BV1U65SzuE4p?t=2625)
- `0:43:54`**我以为能给我讲明白到底为啥这俩是等价的，其实还是没有doge**　[↗](https://www.bilibili.com/video/BV1U65SzuE4p?t=2634)
- `0:46:47`**为什么速度vt和时间无关，模型预测得速度还要输入t作为参数**　[↗](https://www.bilibili.com/video/BV1U65SzuE4p?t=2807)
- `0:46:55`**因为这training，inference需要aware到T**　[↗](https://www.bilibili.com/video/BV1U65SzuE4p?t=2815)
- `0:46:56`**因为你得知道现在分布变换到哪一步了，虽然OT是直线，但推理中由于存在交叉，实际预测的V并不是指向目标分布**　[↗](https://www.bilibili.com/video/BV1U65SzuE4p?t=2816)
- `0:48:26`**OT实际也不直，因为存在多条路径交叉的情况，否则直接一步采样就可以变换了，实际仍要多步采样**　[↗](https://www.bilibili.com/video/BV1U65SzuE4p?t=2906)
- `0:57:59`**12月底录视频但是4月中发**　[↗](https://www.bilibili.com/video/BV1U65SzuE4p?t=3479)
- `1:02:33`**完结待续:D_JYQ**　[↗](https://www.bilibili.com/video/BV1U65SzuE4p?t=3753)
