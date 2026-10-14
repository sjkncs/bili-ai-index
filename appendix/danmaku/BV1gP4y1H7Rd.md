# 弹幕讨论 · 9.3 网络架构搜索【斯坦福21秋季：实用机器学习中文版】

> 视频：[BV1gP4y1H7Rd](https://www.bilibili.com/video/BV1gP4y1H7Rd)　时长 0:24:02　弹幕总数 **76**　有实质内容 **33** 条　重点标记 **33** 条
>
> 来源：B 站 **跟李沐学AI** 的该集弹幕　快照：**2026-10-14**

## 口径说明（务必先读）

**这些内容全部是观众在视频上发的弹幕，不是经过核实的结论。**

- 其中有价值的：概念解释、类比、勘误、学习方法、延伸阅读线索。
- **也可能有错误的**：弹幕是个人理解，未经作者或权威确认。
  **本页不为其正确性背书，请勿直接引用为事实。**
- 每条带时间戳，点击可跳回视频对应位置自行核对。
- 筛选口径：保留长度 ≥ 10 字符、且不含纯感叹/打卡类噪声的弹幕，共 33 条（占该集弹幕 76 条的 43.4%）；同一句话被多人发送只保留一条并标注发送次数。
- 「重点」标记由关键词打分得出（技术词 + 解释性措辞 + 长度 + 多人重复），共 33 条；**它是启发式排序，不代表正确性，也不代表其余条目无价值。**

## 重点条目

| 时间 | 弹幕 | 发送次数 |
|---|---|---:|
| [0:01:46](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=106) | 为啥这几期声音这么小？ | 1 |
| [0:01:49](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=109) | 好好听课！别玩手机，就说你呢！注意听讲 | 1 |
| [0:02:50](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=170) | 启发式算法？ALNS？ | 1 |
| [0:03:06](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=186) | 架构搜索就是比如这一层到底是用普通CNN好还是transformer还是残差还是别的什么模块 | 1 |
| [0:03:20](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=200) | 感觉像是网络结构的网络 | 1 |
| [0:05:19](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=319) | GPU is all you need | 1 |
| [0:05:22](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=322) | 100个gpu20天 | 1 |
| [0:05:42](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=342) | 现在gpu资源太贵了 | 1 |
| [0:05:49](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=349) | 用我目前可以理解的思路，觉得NAS肯定很贵 | 1 |
| [0:06:28](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=388) | 大家散了吧，这节课学起来你根本用不起 | 1 |
| [0:08:46](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=526) | 层一和层二的C是不同的 | 1 |
| [0:09:07](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=547) | Inception? | 1 |
| [0:09:23](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=563) | 这不就是attention吗？ | 1 |
| [0:09:36](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=576) | 原来是要遍历所有路径，现在每一层求个局部最优，然后根据目前的最优路径继续往下拓展，不知道这么理解对不对 | 1 |
| [0:09:38](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=578) | 这不就是每个超参数  训练后  自动选择吗？ | 1 |
| [0:09:49](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=589) | 本质是把模块组合的每一个选择都从离散变成可微，从而可学。主要靠softmax | 1 |
| [0:09:52](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=592) | 是同时训练很多子模型，然后根据每层的子模型最优选取吗 | 1 |
| [0:10:17](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=617) | 应该不是每层最优吧 感觉整体最优才行？ | 1 |
| [0:10:43](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=643) | 类似于inceptionnet的操作是吧？ | 1 |
| [0:10:47](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=647) | 加权求积是指对这一层的超参数 | 1 |
| [0:10:55](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=655) | 这房的超参数加权组合成一个值 | 1 |
| [0:10:57](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=657) | 这层学的是三个output的权重 | 1 |
| [0:11:23](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=683) | 用什么作为训练的标注？ | 1 |
| [0:12:22](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=742) | 这个权重咋计算出来的？直接全连接层？ | 1 |
| [0:12:44](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=764) | 可微表现在，每个模型所加的权重需要被训练，也就存在了训练的方式 | 1 |
| [0:12:44](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=764) | 选模块是不可微的，但是每个模型的权重是可微的 | 1 |
| [0:18:45](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=1125) | metalearning 的感觉 | 1 |
| [0:22:24](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=1344) | 看完之后感觉，实验室不支持研究这个条件啊 | 1 |
| [0:22:42](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=1362) | metalearning | 1 |
| [0:23:40](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=1420) | 这里应该是one-shot吧 | 1 |
| [0:23:43](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=1423) | 不是，这里说的应该是可导架构搜索select里面的one-hot | 1 |
| [0:23:43](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=1423) | one-shot的吧 | 1 |
| [0:23:45](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=1425) | softM以入本身没有参数可以训练得到吧? | 1 |

## 全部有实质内容的弹幕（按时间排序，共 33 条）

- `0:01:46`**为啥这几期声音这么小？**　[↗](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=106)
- `0:01:49`**好好听课！别玩手机，就说你呢！注意听讲**　[↗](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=109)
- `0:02:50`**启发式算法？ALNS？**　[↗](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=170)
- `0:03:06`**架构搜索就是比如这一层到底是用普通CNN好还是transformer还是残差还是别的什么模块**　[↗](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=186)
- `0:03:20`**感觉像是网络结构的网络**　[↗](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=200)
- `0:05:19`**GPU is all you need**　[↗](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=319)
- `0:05:22`**100个gpu20天**　[↗](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=322)
- `0:05:42`**现在gpu资源太贵了**　[↗](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=342)
- `0:05:49`**用我目前可以理解的思路，觉得NAS肯定很贵**　[↗](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=349)
- `0:06:28`**大家散了吧，这节课学起来你根本用不起**　[↗](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=388)
- `0:08:46`**层一和层二的C是不同的**　[↗](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=526)
- `0:09:07`**Inception?**　[↗](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=547)
- `0:09:23`**这不就是attention吗？**　[↗](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=563)
- `0:09:36`**原来是要遍历所有路径，现在每一层求个局部最优，然后根据目前的最优路径继续往下拓展，不知道这么理解对不对**　[↗](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=576)
- `0:09:38`**这不就是每个超参数  训练后  自动选择吗？**　[↗](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=578)
- `0:09:49`**本质是把模块组合的每一个选择都从离散变成可微，从而可学。主要靠softmax**　[↗](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=589)
- `0:09:52`**是同时训练很多子模型，然后根据每层的子模型最优选取吗**　[↗](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=592)
- `0:10:17`**应该不是每层最优吧 感觉整体最优才行？**　[↗](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=617)
- `0:10:43`**类似于inceptionnet的操作是吧？**　[↗](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=643)
- `0:10:47`**加权求积是指对这一层的超参数**　[↗](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=647)
- `0:10:55`**这房的超参数加权组合成一个值**　[↗](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=655)
- `0:10:57`**这层学的是三个output的权重**　[↗](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=657)
- `0:11:23`**用什么作为训练的标注？**　[↗](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=683)
- `0:12:22`**这个权重咋计算出来的？直接全连接层？**　[↗](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=742)
- `0:12:44`**可微表现在，每个模型所加的权重需要被训练，也就存在了训练的方式**　[↗](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=764)
- `0:12:44`**选模块是不可微的，但是每个模型的权重是可微的**　[↗](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=764)
- `0:18:45`**metalearning 的感觉**　[↗](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=1125)
- `0:22:24`**看完之后感觉，实验室不支持研究这个条件啊**　[↗](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=1344)
- `0:22:42`**metalearning**　[↗](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=1362)
- `0:23:40`**这里应该是one-shot吧**　[↗](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=1420)
- `0:23:43`**不是，这里说的应该是可导架构搜索select里面的one-hot**　[↗](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=1423)
- `0:23:43`**one-shot的吧**　[↗](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=1423)
- `0:23:45`**softM以入本身没有参数可以训练得到吧?**　[↗](https://www.bilibili.com/video/BV1gP4y1H7Rd?t=1425)
