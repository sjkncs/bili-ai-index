# 弹幕讨论 · 2.2 数据清理【斯坦福21秋季：实用机器学习中文版】

> 视频：[BV1kQ4y1Q7mx](https://www.bilibili.com/video/BV1kQ4y1Q7mx)　时长 0:18:53　弹幕总数 **117**　有实质内容 **43** 条　重点标记 **43** 条
>
> 来源：B 站 **跟李沐学AI** 的该集弹幕　快照：**2026-10-13**

## 口径说明（务必先读）

**这些内容全部是观众在视频上发的弹幕，不是经过核实的结论。**

- 其中有价值的：概念解释、类比、勘误、学习方法、延伸阅读线索。
- **也可能有错误的**：弹幕是个人理解，未经作者或权威确认。
  **本页不为其正确性背书，请勿直接引用为事实。**
- 每条带时间戳，点击可跳回视频对应位置自行核对。
- 筛选口径：保留长度 ≥ 10 字符、且不含纯感叹/打卡类噪声的弹幕，共 43 条（占该集弹幕 117 条的 36.8%）；同一句话被多人发送只保留一条并标注发送次数。
- 「重点」标记由关键词打分得出（技术词 + 解释性措辞 + 长度 + 多人重复），共 43 条；**它是启发式排序，不代表正确性，也不代表其余条目无价值。**

## 重点条目

| 时间 | 弹幕 | 发送次数 |
|---|---|---:|
| [0:00:00](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=0) | 请问课程的作业会公开吗？想做一下。 | 1 |
| [0:02:08](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=128) | ·12345汉尼拔【】、 | 1 |
| [0:02:51](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=171) | 错误的数据不会把模型带偏嘛 | 1 |
| [0:03:08](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=188) | garbage in garbage out | 1 |
| [0:03:09](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=189) | 只要你的模型足够大，即使你数据都是乱标的，他都能给你训练一个精度还行的结果 | 1 |
| [0:03:22](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=202) | 几个错误不可能带偏很多 | 1 |
| [0:03:37](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=217) | 如果你的数据集大部分都是错的那就不行 | 1 |
| [0:04:33](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=273) | compounding error | 1 |
| [0:05:22](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=322) | 应该是说不能有NULL，AI字幕错了 | 1 |
| [0:05:31](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=331) | 就是not a number， NA数据 | 1 |
| [0:05:34](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=334) | 是nan不是null | 1 |
| [0:05:45](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=345) | null empty na 有差别的 | 1 |
| [0:05:55](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=355) | nan类型是float | 1 |
| [0:06:05](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=365) | 讲义在课程下面的链接里 | 1 |
| [0:06:09](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=369) | 这个跟数据标注说过一样？ | 1 |
| [0:08:47](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=527) | Interquartile range | 1 |
| [0:09:00](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=540) | IQR （ interquartile range缩写），中文译为“四分位差/间距” | 1 |
| [0:09:10](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=550) | 异常检测场景不能剔除离群值吧 | 1 |
| [0:09:15](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=555) | 这里是因为正态分布三倍标准差的原因吗 | 1 |
| [0:09:16](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=556) | 目的不同的话处理也不一样吧 | 1 |
| [0:09:20](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=560) | 具体问题具体分析的吧，如果预测的数据也有在outliers里面就需要保留给模型做参考 | 1 |
| [0:09:54](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=594) | 这样修数据 后面不会过拟合吗 | 1 |
| [0:09:58](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=598) | 去掉这些数据，反而不会过拟合啊 | 1 |
| [0:10:01](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=601) | 这个不算过拟合吧，这是针对特定问题筛选数据而已 | 1 |
| [0:10:01](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=601) | 异常检测具体问题具体分析~ | 1 |
| [0:10:01](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=601) | 这里的基本假设是，提出一个大多数人能用的房价预测模型。 | 1 |
| [0:10:01](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=601) | 这样做会不会把一些小场景数据过滤掉了， | 1 |
| [0:10:12](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=612) | 特殊场景特殊分析。不可能一个方法论套所有的场景的。 | 1 |
| [0:10:32](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=632) | 反而提高了泛化能力我觉得 | 1 |
| [0:10:57](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=657) | 函数依赖 database的概念 | 1 |
| [0:11:19](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=679) | 问题我咋知道是哪个错了呢 | 1 |
| [0:11:27](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=687) | 数据库中的  依赖关系吧 | 1 |
| [0:11:28](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=688) | 想知道哪个错了，就需要在process前做大量的background research 或者和client/stakeholders 进行沟通，彻底理解数据。 | 1 |
| [0:11:52](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=712) | 这里是数据的意义,如果某些数据明显脱离了在实际业务中的意义, 需要被删除, 这个也是与客户访谈的真正意义, 要理解数据的意义,也就知道每一个数据的范围,大小,合理的区间在哪里 | 1 |
| [0:13:36](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=816) | 能坚持到这里的老铁明显少了许多了，上难度了 | 1 |
| [0:13:52](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=832) | 这个是data brew, aws的服务 | 1 |
| [0:13:58](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=838) | 这里可以直接用map函数进行映射 | 1 |
| [0:16:02](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=962) | APP是Trifacta | 1 |
| [0:16:02](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=962) | Excel的查找 替换？ | 1 |
| [0:16:25](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=985) | 推荐 Tableau Prep，虽然界面不同于视频里的，不过功能感觉很接近 | 1 |
| [0:16:30](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=990) | 哈哈自家数据集就没有 | 1 |
| [0:17:22](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=1042) | 推荐powerbi的客户端可以直接查看这些 | 1 |
| [0:18:52](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=1132) | 有推荐的图形交互处理工具吗？ | 1 |

## 全部有实质内容的弹幕（按时间排序，共 43 条）

- `0:00:00`**请问课程的作业会公开吗？想做一下。**　[↗](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=0)
- `0:02:08`**·12345汉尼拔【】、**　[↗](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=128)
- `0:02:51`**错误的数据不会把模型带偏嘛**　[↗](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=171)
- `0:03:08`**garbage in garbage out**　[↗](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=188)
- `0:03:09`**只要你的模型足够大，即使你数据都是乱标的，他都能给你训练一个精度还行的结果**　[↗](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=189)
- `0:03:22`**几个错误不可能带偏很多**　[↗](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=202)
- `0:03:37`**如果你的数据集大部分都是错的那就不行**　[↗](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=217)
- `0:04:33`**compounding error**　[↗](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=273)
- `0:05:22`**应该是说不能有NULL，AI字幕错了**　[↗](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=322)
- `0:05:31`**就是not a number， NA数据**　[↗](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=331)
- `0:05:34`**是nan不是null**　[↗](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=334)
- `0:05:45`**null empty na 有差别的**　[↗](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=345)
- `0:05:55`**nan类型是float**　[↗](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=355)
- `0:06:05`**讲义在课程下面的链接里**　[↗](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=365)
- `0:06:09`**这个跟数据标注说过一样？**　[↗](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=369)
- `0:08:47`**Interquartile range**　[↗](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=527)
- `0:09:00`**IQR （ interquartile range缩写），中文译为“四分位差/间距”**　[↗](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=540)
- `0:09:10`**异常检测场景不能剔除离群值吧**　[↗](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=550)
- `0:09:15`**这里是因为正态分布三倍标准差的原因吗**　[↗](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=555)
- `0:09:16`**目的不同的话处理也不一样吧**　[↗](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=556)
- `0:09:20`**具体问题具体分析的吧，如果预测的数据也有在outliers里面就需要保留给模型做参考**　[↗](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=560)
- `0:09:54`**这样修数据 后面不会过拟合吗**　[↗](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=594)
- `0:09:58`**去掉这些数据，反而不会过拟合啊**　[↗](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=598)
- `0:10:01`**这个不算过拟合吧，这是针对特定问题筛选数据而已**　[↗](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=601)
- `0:10:01`**异常检测具体问题具体分析~**　[↗](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=601)
- `0:10:01`**这里的基本假设是，提出一个大多数人能用的房价预测模型。**　[↗](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=601)
- `0:10:01`**这样做会不会把一些小场景数据过滤掉了，**　[↗](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=601)
- `0:10:12`**特殊场景特殊分析。不可能一个方法论套所有的场景的。**　[↗](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=612)
- `0:10:32`**反而提高了泛化能力我觉得**　[↗](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=632)
- `0:10:57`**函数依赖 database的概念**　[↗](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=657)
- `0:11:19`**问题我咋知道是哪个错了呢**　[↗](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=679)
- `0:11:27`**数据库中的  依赖关系吧**　[↗](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=687)
- `0:11:28`**想知道哪个错了，就需要在process前做大量的background research 或者和client/stakeholders 进行沟通，彻底理解数据。**　[↗](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=688)
- `0:11:52`**这里是数据的意义,如果某些数据明显脱离了在实际业务中的意义, 需要被删除, 这个也是与客户访谈的真正意义, 要理解数据的意义,也就知道每一个数据的范围,大小,合理的区间在哪里**　[↗](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=712)
- `0:13:36`**能坚持到这里的老铁明显少了许多了，上难度了**　[↗](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=816)
- `0:13:52`**这个是data brew, aws的服务**　[↗](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=832)
- `0:13:58`**这里可以直接用map函数进行映射**　[↗](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=838)
- `0:16:02`**APP是Trifacta**　[↗](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=962)
- `0:16:02`**Excel的查找 替换？**　[↗](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=962)
- `0:16:25`**推荐 Tableau Prep，虽然界面不同于视频里的，不过功能感觉很接近**　[↗](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=985)
- `0:16:30`**哈哈自家数据集就没有**　[↗](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=990)
- `0:17:22`**推荐powerbi的客户端可以直接查看这些**　[↗](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=1042)
- `0:18:52`**有推荐的图形交互处理工具吗？**　[↗](https://www.bilibili.com/video/BV1kQ4y1Q7mx?t=1132)
