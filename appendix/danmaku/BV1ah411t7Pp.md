# 弹幕讨论 · 4.2 过拟合和欠拟合【斯坦福21秋季：实用机器学习中文版】

> 视频：[BV1ah411t7Pp](https://www.bilibili.com/video/BV1ah411t7Pp)　时长 0:29:37　弹幕总数 **133**　有实质内容 **47** 条　重点标记 **47** 条
>
> 来源：B 站 **跟李沐学AI** 的该集弹幕　快照：**2026-10-12**

## 口径说明（务必先读）

**这些内容全部是观众在视频上发的弹幕，不是经过核实的结论。**

- 其中有价值的：概念解释、类比、勘误、学习方法、延伸阅读线索。
- **也可能有错误的**：弹幕是个人理解，未经作者或权威确认。
  **本页不为其正确性背书，请勿直接引用为事实。**
- 每条带时间戳，点击可跳回视频对应位置自行核对。
- 筛选口径：保留长度 ≥ 10 字符、且不含纯感叹/打卡类噪声的弹幕，共 47 条（占该集弹幕 133 条的 35.3%）；同一句话被多人发送只保留一条并标注发送次数。
- 「重点」标记由关键词打分得出（技术词 + 解释性措辞 + 长度 + 多人重复），共 47 条；**它是启发式排序，不代表正确性，也不代表其余条目无价值。**

## 重点条目

| 时间 | 弹幕 | 发送次数 |
|---|---|---:|
| [0:00:42](https://www.bilibili.com/video/BV1ah411t7Pp?t=42) | 经典kaggle竞赛 | 1 |
| [0:01:00](https://www.bilibili.com/video/BV1ah411t7Pp?t=60) | 数据相关性不一定事件因果性？ | 1 |
| [0:01:29](https://www.bilibili.com/video/BV1ah411t7Pp?t=89) | 藍色可能是詐騙團夥doge | 1 |
| [0:01:32](https://www.bilibili.com/video/BV1ah411t7Pp?t=92) | 这五个人刚好都是左脚先走进门口并且使用右手签名 | 1 |
| [0:01:32](https://www.bilibili.com/video/BV1ah411t7Pp?t=92) | 数据里应该不会有这个特征吧囧 | 1 |
| [0:01:39](https://www.bilibili.com/video/BV1ah411t7Pp?t=99) | 在做模型的时候一般不会把申请者的穿着给放进模型吧 | 1 |
| [0:01:45](https://www.bilibili.com/video/BV1ah411t7Pp?t=105) | 以CNN为例，它的一个作用就是省去特征提取，把信息一股脑丢给计算机 | 1 |
| [0:01:58](https://www.bilibili.com/video/BV1ah411t7Pp?t=118) | 举个例子，说明学得太过也不好，相当于死脑筋 | 1 |
| [0:02:12](https://www.bilibili.com/video/BV1ah411t7Pp?t=132) | generaliztion | 1 |
| [0:03:38](https://www.bilibili.com/video/BV1ah411t7Pp?t=218) | 这个比喻太厉害，一下就明白了 | 1 |
| [0:04:10](https://www.bilibili.com/video/BV1ah411t7Pp?t=250) | 对应训练集、验证集、测试集 | 1 |
| [0:04:31](https://www.bilibili.com/video/BV1ah411t7Pp?t=271) | 国内大学很多都这么考试 | 1 |
| [0:04:45](https://www.bilibili.com/video/BV1ah411t7Pp?t=285) | 所以考试 是 考泛化性吗... | 1 |
| [0:04:55](https://www.bilibili.com/video/BV1ah411t7Pp?t=295) | 所以是说学霸是在学习上的泛化性很强吗？ | 1 |
| [0:04:57](https://www.bilibili.com/video/BV1ah411t7Pp?t=297) | 信息纬度的降低，特征提取 | 1 |
| [0:04:59](https://www.bilibili.com/video/BV1ah411t7Pp?t=299) | 正常人不可能一点泛化没有，也不能记得住所有题 | 1 |
| [0:05:00](https://www.bilibili.com/video/BV1ah411t7Pp?t=300) | 就是解题思路的举一反三啊 | 1 |
| [0:05:13](https://www.bilibili.com/video/BV1ah411t7Pp?t=313) | 高中生应该不至于看这个吧 | 1 |
| [0:05:49](https://www.bilibili.com/video/BV1ah411t7Pp?t=349) | 两短一长选一长，泛化误差怎样呢？ | 1 |
| [0:05:53](https://www.bilibili.com/video/BV1ah411t7Pp?t=353) | bug 哈哈哈哈哈哈 | 1 |
| [0:05:55](https://www.bilibili.com/video/BV1ah411t7Pp?t=355) | 我都很低，但训练的相对更低，怎么说 | 1 |
| [0:06:05](https://www.bilibili.com/video/BV1ah411t7Pp?t=365) | 属于瞎猫碰上死耗子了 | 1 |
| [0:06:34](https://www.bilibili.com/video/BV1ah411t7Pp?t=394) | 当年小学二年级的时候，老师考试时候拿错了高年级的卷子，满教室人几乎都不会做 | 1 |
| [0:06:58](https://www.bilibili.com/video/BV1ah411t7Pp?t=418) | 做难例挖掘会不会出现这种情况？ | 1 |
| [0:07:34](https://www.bilibili.com/video/BV1ah411t7Pp?t=454) | 之前一直理解是训练误差高就是欠拟合，因为训练的不好，也不会去做泛化预测，感觉根据沐神的提醒可以去看下这类情况 | 1 |
| [0:07:45](https://www.bilibili.com/video/BV1ah411t7Pp?t=465) | 我发现我就是欠拟合…… | 1 |
| [0:10:07](https://www.bilibili.com/video/BV1ah411t7Pp?t=607) | 没声儿了 但我能理解老师在讲啥hhhh | 1 |
| [0:10:30](https://www.bilibili.com/video/BV1ah411t7Pp?t=630) | ][];';';/jjjjjjju,n、、、、、、、、、、、、、、、、、、、、、、、、 | 1 |
| [0:13:25](https://www.bilibili.com/video/BV1ah411t7Pp?t=805) | 2022/5/4 加油青年！ | 1 |
| [0:13:32](https://www.bilibili.com/video/BV1ah411t7Pp?t=812) | 2089/10/5 这个世界是我们AI的  跟你们人类没什么关系了 | 1 |
| [0:13:38](https://www.bilibili.com/video/BV1ah411t7Pp?t=818) | 2024年12月28日 zy | 1 |
| [0:15:29](https://www.bilibili.com/video/BV1ah411t7Pp?t=929) | 那怎么保存住中间那个点的参数 | 1 |
| [0:17:55](https://www.bilibili.com/video/BV1ah411t7Pp?t=1075) | 这个曲线图是为了找到适合数据的模型规模吗？ | 1 |
| [0:18:41](https://www.bilibili.com/video/BV1ah411t7Pp?t=1121) | 那是17:50写上去的 | 1 |
| [0:21:34](https://www.bilibili.com/video/BV1ah411t7Pp?t=1294) | 这里应该说的是复杂度吧 | 4 |
| [0:21:35](https://www.bilibili.com/video/BV1ah411t7Pp?t=1295) | SVD?  什么特怔？ | 1 |
| [0:21:42](https://www.bilibili.com/video/BV1ah411t7Pp?t=1302) | 或者说可以理解成在一组数据集上面可以提取出来的feature的多少吗 | 1 |
| [0:22:40](https://www.bilibili.com/video/BV1ah411t7Pp?t=1360) | 这里的数据复杂度，说的应该是训练的数据样本 | 1 |
| [0:22:54](https://www.bilibili.com/video/BV1ah411t7Pp?t=1374) | 不是从欠拟合变成过拟合吗？ | 1 |
| [0:23:03](https://www.bilibili.com/video/BV1ah411t7Pp?t=1383) | 就是过拟合到欠拟合 模型一开始是简单的 数据一开始也是简单的 一开始可能会过拟合 数据越来越复杂会导致模型不能很好的拟合 慢慢变的欠拟合 | 1 |
| [0:23:17](https://www.bilibili.com/video/BV1ah411t7Pp?t=1397) | 简单模型模拟不了太复杂的数据，数据量小先过拟合再增加数据量到欠拟合 | 1 |
| [0:23:38](https://www.bilibili.com/video/BV1ah411t7Pp?t=1418) | 数据规模与质量决定上限，模型只是逼近这个上限~ | 1 |
| [0:23:53](https://www.bilibili.com/video/BV1ah411t7Pp?t=1433) | 脑子不够用了，做再多的题也记不住 | 1 |
| [0:24:26](https://www.bilibili.com/video/BV1ah411t7Pp?t=1466) | 这个能论证transformer用更多的数据能打赢cnn吗? | 1 |
| [0:24:49](https://www.bilibili.com/video/BV1ah411t7Pp?t=1489) | 深度网络参数复杂度更大，对于更大数据集，泛化误差更小 | 1 |
| [0:25:01](https://www.bilibili.com/video/BV1ah411t7Pp?t=1501) | 右下角，不仅聪明，还好学 | 1 |
| [0:28:48](https://www.bilibili.com/video/BV1ah411t7Pp?t=1728) | 太棒了，在实践中经常分不清什么是过拟合，什么是欠拟合 | 1 |

## 全部有实质内容的弹幕（按时间排序，共 47 条）

- `0:00:42`**经典kaggle竞赛**　[↗](https://www.bilibili.com/video/BV1ah411t7Pp?t=42)
- `0:01:00`**数据相关性不一定事件因果性？**　[↗](https://www.bilibili.com/video/BV1ah411t7Pp?t=60)
- `0:01:29`**藍色可能是詐騙團夥doge**　[↗](https://www.bilibili.com/video/BV1ah411t7Pp?t=89)
- `0:01:32`**这五个人刚好都是左脚先走进门口并且使用右手签名**　[↗](https://www.bilibili.com/video/BV1ah411t7Pp?t=92)
- `0:01:32`**数据里应该不会有这个特征吧囧**　[↗](https://www.bilibili.com/video/BV1ah411t7Pp?t=92)
- `0:01:39`**在做模型的时候一般不会把申请者的穿着给放进模型吧**　[↗](https://www.bilibili.com/video/BV1ah411t7Pp?t=99)
- `0:01:45`**以CNN为例，它的一个作用就是省去特征提取，把信息一股脑丢给计算机**　[↗](https://www.bilibili.com/video/BV1ah411t7Pp?t=105)
- `0:01:58`**举个例子，说明学得太过也不好，相当于死脑筋**　[↗](https://www.bilibili.com/video/BV1ah411t7Pp?t=118)
- `0:02:12`**generaliztion**　[↗](https://www.bilibili.com/video/BV1ah411t7Pp?t=132)
- `0:03:38`**这个比喻太厉害，一下就明白了**　[↗](https://www.bilibili.com/video/BV1ah411t7Pp?t=218)
- `0:04:10`**对应训练集、验证集、测试集**　[↗](https://www.bilibili.com/video/BV1ah411t7Pp?t=250)
- `0:04:31`**国内大学很多都这么考试**　[↗](https://www.bilibili.com/video/BV1ah411t7Pp?t=271)
- `0:04:45`**所以考试 是 考泛化性吗...**　[↗](https://www.bilibili.com/video/BV1ah411t7Pp?t=285)
- `0:04:55`**所以是说学霸是在学习上的泛化性很强吗？**　[↗](https://www.bilibili.com/video/BV1ah411t7Pp?t=295)
- `0:04:57`**信息纬度的降低，特征提取**　[↗](https://www.bilibili.com/video/BV1ah411t7Pp?t=297)
- `0:04:59`**正常人不可能一点泛化没有，也不能记得住所有题**　[↗](https://www.bilibili.com/video/BV1ah411t7Pp?t=299)
- `0:05:00`**就是解题思路的举一反三啊**　[↗](https://www.bilibili.com/video/BV1ah411t7Pp?t=300)
- `0:05:13`**高中生应该不至于看这个吧**　[↗](https://www.bilibili.com/video/BV1ah411t7Pp?t=313)
- `0:05:49`**两短一长选一长，泛化误差怎样呢？**　[↗](https://www.bilibili.com/video/BV1ah411t7Pp?t=349)
- `0:05:53`**bug 哈哈哈哈哈哈**　[↗](https://www.bilibili.com/video/BV1ah411t7Pp?t=353)
- `0:05:55`**我都很低，但训练的相对更低，怎么说**　[↗](https://www.bilibili.com/video/BV1ah411t7Pp?t=355)
- `0:06:05`**属于瞎猫碰上死耗子了**　[↗](https://www.bilibili.com/video/BV1ah411t7Pp?t=365)
- `0:06:34`**当年小学二年级的时候，老师考试时候拿错了高年级的卷子，满教室人几乎都不会做**　[↗](https://www.bilibili.com/video/BV1ah411t7Pp?t=394)
- `0:06:58`**做难例挖掘会不会出现这种情况？**　[↗](https://www.bilibili.com/video/BV1ah411t7Pp?t=418)
- `0:07:34`**之前一直理解是训练误差高就是欠拟合，因为训练的不好，也不会去做泛化预测，感觉根据沐神的提醒可以去看下这类情况**　[↗](https://www.bilibili.com/video/BV1ah411t7Pp?t=454)
- `0:07:45`**我发现我就是欠拟合……**　[↗](https://www.bilibili.com/video/BV1ah411t7Pp?t=465)
- `0:10:07`**没声儿了 但我能理解老师在讲啥hhhh**　[↗](https://www.bilibili.com/video/BV1ah411t7Pp?t=607)
- `0:10:30`**][];';';/jjjjjjju,n、、、、、、、、、、、、、、、、、、、、、、、、**　[↗](https://www.bilibili.com/video/BV1ah411t7Pp?t=630)
- `0:13:25`**2022/5/4 加油青年！**　[↗](https://www.bilibili.com/video/BV1ah411t7Pp?t=805)
- `0:13:32`**2089/10/5 这个世界是我们AI的  跟你们人类没什么关系了**　[↗](https://www.bilibili.com/video/BV1ah411t7Pp?t=812)
- `0:13:38`**2024年12月28日 zy**　[↗](https://www.bilibili.com/video/BV1ah411t7Pp?t=818)
- `0:15:29`**那怎么保存住中间那个点的参数**　[↗](https://www.bilibili.com/video/BV1ah411t7Pp?t=929)
- `0:17:55`**这个曲线图是为了找到适合数据的模型规模吗？**　[↗](https://www.bilibili.com/video/BV1ah411t7Pp?t=1075)
- `0:18:41`**那是17:50写上去的**　[↗](https://www.bilibili.com/video/BV1ah411t7Pp?t=1121)
- `0:21:34`**这里应该说的是复杂度吧**（×4）　[↗](https://www.bilibili.com/video/BV1ah411t7Pp?t=1294)
- `0:21:35`**SVD?  什么特怔？**　[↗](https://www.bilibili.com/video/BV1ah411t7Pp?t=1295)
- `0:21:42`**或者说可以理解成在一组数据集上面可以提取出来的feature的多少吗**　[↗](https://www.bilibili.com/video/BV1ah411t7Pp?t=1302)
- `0:22:40`**这里的数据复杂度，说的应该是训练的数据样本**　[↗](https://www.bilibili.com/video/BV1ah411t7Pp?t=1360)
- `0:22:54`**不是从欠拟合变成过拟合吗？**　[↗](https://www.bilibili.com/video/BV1ah411t7Pp?t=1374)
- `0:23:03`**就是过拟合到欠拟合 模型一开始是简单的 数据一开始也是简单的 一开始可能会过拟合 数据越来越复杂会导致模型不能很好的拟合 慢慢变的欠拟合**　[↗](https://www.bilibili.com/video/BV1ah411t7Pp?t=1383)
- `0:23:17`**简单模型模拟不了太复杂的数据，数据量小先过拟合再增加数据量到欠拟合**　[↗](https://www.bilibili.com/video/BV1ah411t7Pp?t=1397)
- `0:23:38`**数据规模与质量决定上限，模型只是逼近这个上限~**　[↗](https://www.bilibili.com/video/BV1ah411t7Pp?t=1418)
- `0:23:53`**脑子不够用了，做再多的题也记不住**　[↗](https://www.bilibili.com/video/BV1ah411t7Pp?t=1433)
- `0:24:26`**这个能论证transformer用更多的数据能打赢cnn吗?**　[↗](https://www.bilibili.com/video/BV1ah411t7Pp?t=1466)
- `0:24:49`**深度网络参数复杂度更大，对于更大数据集，泛化误差更小**　[↗](https://www.bilibili.com/video/BV1ah411t7Pp?t=1489)
- `0:25:01`**右下角，不仅聪明，还好学**　[↗](https://www.bilibili.com/video/BV1ah411t7Pp?t=1501)
- `0:28:48`**太棒了，在实践中经常分不清什么是过拟合，什么是欠拟合**　[↗](https://www.bilibili.com/video/BV1ah411t7Pp?t=1728)
