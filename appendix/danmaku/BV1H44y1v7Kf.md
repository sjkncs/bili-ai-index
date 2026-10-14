# 弹幕讨论 · 5.1 方差和偏差【斯坦福21秋季：实用机器学习中文版】

> 视频：[BV1H44y1v7Kf](https://www.bilibili.com/video/BV1H44y1v7Kf)　时长 0:17:00　弹幕总数 **155**　有实质内容 **75** 条　重点标记 **75** 条
>
> 来源：B 站 **跟李沐学AI** 的该集弹幕　快照：**2026-10-14**

## 口径说明（务必先读）

**这些内容全部是观众在视频上发的弹幕，不是经过核实的结论。**

- 其中有价值的：概念解释、类比、勘误、学习方法、延伸阅读线索。
- **也可能有错误的**：弹幕是个人理解，未经作者或权威确认。
  **本页不为其正确性背书，请勿直接引用为事实。**
- 每条带时间戳，点击可跳回视频对应位置自行核对。
- 筛选口径：保留长度 ≥ 10 字符、且不含纯感叹/打卡类噪声的弹幕，共 75 条（占该集弹幕 155 条的 48.4%）；同一句话被多人发送只保留一条并标注发送次数。
- 「重点」标记由关键词打分得出（技术词 + 解释性措辞 + 长度 + 多人重复），共 75 条；**它是启发式排序，不代表正确性，也不代表其余条目无价值。**

## 重点条目

| 时间 | 弹幕 | 发送次数 |
|---|---|---:|
| [0:00:04](https://www.bilibili.com/video/BV1H44y1v7Kf?t=4) | 好了，我上节课已经开心过了 | 1 |
| [0:00:07](https://www.bilibili.com/video/BV1H44y1v7Kf?t=7) | 瓦坎达forever！ | 1 |
| [0:00:32](https://www.bilibili.com/video/BV1H44y1v7Kf?t=32) | 真实的模型是什么？怎么来的？ | 1 |
| [0:00:45](https://www.bilibili.com/video/BV1H44y1v7Kf?t=45) | 这个中心点怎么来的？ | 1 |
| [0:00:52](https://www.bilibili.com/video/BV1H44y1v7Kf?t=52) | 不同的点时用不同的数据训练的到的模型，然后进行预测得到的值吧？ | 1 |
| [0:00:55](https://www.bilibili.com/video/BV1H44y1v7Kf?t=55) | 瓦坎达Forever！ | 1 |
| [0:01:00](https://www.bilibili.com/video/BV1H44y1v7Kf?t=60) | 相同数据集，相同的网络结构？ | 1 |
| [0:01:09](https://www.bilibili.com/video/BV1H44y1v7Kf?t=69) | 模型对数据分布的敏感性 | 1 |
| [0:01:16](https://www.bilibili.com/video/BV1H44y1v7Kf?t=76) | 这个图做的太好了，一下子就理解到了 | 1 |
| [0:02:37](https://www.bilibili.com/video/BV1H44y1v7Kf?t=157) | 偏差应该算是准确性，方差算是稳定性，我是这么理解的 | 1 |
| [0:02:39](https://www.bilibili.com/video/BV1H44y1v7Kf?t=159) | wakanda forever | 1 |
| [0:02:44](https://www.bilibili.com/video/BV1H44y1v7Kf?t=164) | 这个和过拟合和欠拟合有关系吧 | 1 |
| [0:02:49](https://www.bilibili.com/video/BV1H44y1v7Kf?t=169) | 关系不大，这个方差是多次训练的结果 | 1 |
| [0:02:53](https://www.bilibili.com/video/BV1H44y1v7Kf?t=173) | 在模型上如何调整呢？ | 1 |
| [0:02:54](https://www.bilibili.com/video/BV1H44y1v7Kf?t=174) | 偏差：瞄准精度，方差：弹道集中度 | 1 |
| [0:02:54](https://www.bilibili.com/video/BV1H44y1v7Kf?t=174) | 老师的衣服是瓦坎达么 | 1 |
| [0:02:56](https://www.bilibili.com/video/BV1H44y1v7Kf?t=176) | 偏差和期望什么区别？ | 1 |
| [0:03:28](https://www.bilibili.com/video/BV1H44y1v7Kf?t=208) | Merry Christmas | 1 |
| [0:03:29](https://www.bilibili.com/video/BV1H44y1v7Kf?t=209) | 才看到，大神穿的是黑豹啊 | 1 |
| [0:04:49](https://www.bilibili.com/video/BV1H44y1v7Kf?t=289) | D是不同的数据集的子集（采样） | 1 |
| [0:05:07](https://www.bilibili.com/video/BV1H44y1v7Kf?t=307) | 请问E()代表求期望吗？ | 1 |
| [0:05:25](https://www.bilibili.com/video/BV1H44y1v7Kf?t=325) | 补概率论吧，机器学习可以放一放了 | 1 |
| [0:05:27](https://www.bilibili.com/video/BV1H44y1v7Kf?t=327) | expectation | 1 |
| [0:06:12](https://www.bilibili.com/video/BV1H44y1v7Kf?t=372) | f是理想的模型？与训练集天关 | 1 |
| [0:06:23](https://www.bilibili.com/video/BV1H44y1v7Kf?t=383) | 这里举例 f是真实模型，数据就是用f生成的 | 1 |
| [0:06:33](https://www.bilibili.com/video/BV1H44y1v7Kf?t=393) | 机器学习学了三四遍了 | 1 |
| [0:07:03](https://www.bilibili.com/video/BV1H44y1v7Kf?t=423) | 为什么左边期望有下标D，等式右边没有啊 | 1 |
| [0:07:10](https://www.bilibili.com/video/BV1H44y1v7Kf?t=430) | 这个里的y=f+误差，指的是测量设备本身的误差+真正的结果，得到现在测量结果y | 1 |
| [0:07:19](https://www.bilibili.com/video/BV1H44y1v7Kf?t=439) | 三四遍的那个留下，我六七遍了 | 1 |
| [0:07:24](https://www.bilibili.com/video/BV1H44y1v7Kf?t=444) | 假设是独立的。实际上可能有交互作用。 | 1 |
| [0:07:28](https://www.bilibili.com/video/BV1H44y1v7Kf?t=448) | 我错了，并没有交叉效应。因为是泛化表现。 | 1 |
| [0:07:44](https://www.bilibili.com/video/BV1H44y1v7Kf?t=464) | 这里假设是同方差吧，如果数据分布是异方差就不能这么处理了嘛？ | 1 |
| [0:07:48](https://www.bilibili.com/video/BV1H44y1v7Kf?t=468) | 独立样本之间的联合概率密度等于分别概率的乘积 | 1 |
| [0:07:54](https://www.bilibili.com/video/BV1H44y1v7Kf?t=474) | 每次都是从入门到放弃 | 1 |
| [0:08:45](https://www.bilibili.com/video/BV1H44y1v7Kf?t=525) | 第一项是偏差的平方！ | 1 |
| [0:08:56](https://www.bilibili.com/video/BV1H44y1v7Kf?t=536) | 听君一席话胜读十年书 | 1 |
| [0:08:57](https://www.bilibili.com/video/BV1H44y1v7Kf?t=537) | 好清晰的思路一个式子2个概念都理清了 | 1 |
| [0:08:57](https://www.bilibili.com/video/BV1H44y1v7Kf?t=537) | 方差本身就包含平方了，所以不用再平方了！ | 1 |
| [0:09:07](https://www.bilibili.com/video/BV1H44y1v7Kf?t=547) | 这个偏差还不是跟真实的label | 1 |
| [0:09:18](https://www.bilibili.com/video/BV1H44y1v7Kf?t=558) | 我感觉老师讲的是对的啊 | 1 |
| [0:09:20](https://www.bilibili.com/video/BV1H44y1v7Kf?t=560) | 倒数第二排最后一项右端是不是多了一个小括号？ | 1 |
| [0:09:24](https://www.bilibili.com/video/BV1H44y1v7Kf?t=564) | 怎么看起来像是D是同一个数据集呢 | 1 |
| [0:09:26](https://www.bilibili.com/video/BV1H44y1v7Kf?t=566) | E（X^2）=D（X）+E（X）*E（X | 1 |
| [0:09:28](https://www.bilibili.com/video/BV1H44y1v7Kf?t=568) | f怎么来的？  f_hat是不同次训练的模型，f呢？ | 1 |
| [0:09:29](https://www.bilibili.com/video/BV1H44y1v7Kf?t=569) | 方差等于平方的期望减期望的平方 | 1 |
| [0:09:31](https://www.bilibili.com/video/BV1H44y1v7Kf?t=571) | 这不是sigma期望的平方，是平方的期望，所以不是0 | 1 |
| [0:09:47](https://www.bilibili.com/video/BV1H44y1v7Kf?t=587) | 最后一项是噪声的平方！ | 1 |
| [0:09:59](https://www.bilibili.com/video/BV1H44y1v7Kf?t=599) | 这个式子太清晰，白话：你的模型既要准也要稳定，真实标签的噪声不是你能掌握的 | 1 |
| [0:10:03](https://www.bilibili.com/video/BV1H44y1v7Kf?t=603) | 偏差不是跟真实值？而是跟f的偏差？ | 1 |
| [0:10:52](https://www.bilibili.com/video/BV1H44y1v7Kf?t=652) | 外面刚刚有直升机飞过 | 1 |
| [0:11:26](https://www.bilibili.com/video/BV1H44y1v7Kf?t=686) | 为啥从5点几跳到9点几了呢 | 1 |
| [0:11:36](https://www.bilibili.com/video/BV1H44y1v7Kf?t=696) | 好像增加模型随机性可以减少方差的吧 | 1 |
| [0:11:38](https://www.bilibili.com/video/BV1H44y1v7Kf?t=698) | 偏差是跟 训练模型的均值 做差，说明均值跟f 很近 | 1 |
| [0:11:47](https://www.bilibili.com/video/BV1H44y1v7Kf?t=707) | 交叉点就是泛化误差的最低点 | 1 |
| [0:12:29](https://www.bilibili.com/video/BV1H44y1v7Kf?t=749) | var变化这没讲清楚 是学习结果的多样性 | 1 |
| [0:12:29](https://www.bilibili.com/video/BV1H44y1v7Kf?t=749) | 大语言模型每次输出结果都不太一样，但是意思都差不多，就是偏差小方差大的体现！ | 1 |
| [0:12:31](https://www.bilibili.com/video/BV1H44y1v7Kf?t=751) | 也觉得没讲清楚var | 1 |
| [0:12:34](https://www.bilibili.com/video/BV1H44y1v7Kf?t=754) | 看不懂的直接去看bishop的模式识别 | 1 |
| [0:12:39](https://www.bilibili.com/video/BV1H44y1v7Kf?t=759) | 没懂的去看看概率论期望的公式 | 1 |
| [0:12:41](https://www.bilibili.com/video/BV1H44y1v7Kf?t=761) | 知道是评估指标并且会写代码就行了 | 1 |
| [0:13:19](https://www.bilibili.com/video/BV1H44y1v7Kf?t=799) | 如果模型复杂度高，拟合能力久更强，所以只要D符合真实分布，即使单次训练模型可能有偏差，多次训练得到的模型平均下来也会比简单模型更准确 | 1 |
| [0:13:19](https://www.bilibili.com/video/BV1H44y1v7Kf?t=799) | 前面的D是模型的训练数据，如果模型复杂程度高，D的变化会对模型造成的影响就更大，所以模型方差高（对D的采样结果更敏感） | 1 |
| [0:13:34](https://www.bilibili.com/video/BV1H44y1v7Kf?t=814) | 讲的真好，又深刻理解方差和偏差了 | 1 |
| [0:13:55](https://www.bilibili.com/video/BV1H44y1v7Kf?t=835) | 我理解得慢慢的，但老师其实都面面俱到地讲了， 所以回看几遍基本上都能懂，老师太厉害啦！ | 1 |
| [0:14:35](https://www.bilibili.com/video/BV1H44y1v7Kf?t=875) | 你们也是用2倍速播放吗？ | 1 |
| [0:14:43](https://www.bilibili.com/video/BV1H44y1v7Kf?t=883) | 减少偏差要复杂模型，减少方差要简化模型，不冲突吗？ | 1 |
| [0:15:39](https://www.bilibili.com/video/BV1H44y1v7Kf?t=939) | 怎么降呢？怎么知道哪些数据是噪声？ | 1 |
| [0:15:45](https://www.bilibili.com/video/BV1H44y1v7Kf?t=945) | ←这就涉及数据质量判断和提升问题了 | 1 |
| [0:16:00](https://www.bilibili.com/video/BV1H44y1v7Kf?t=960) | 老师ensemble是不是读错了 | 1 |
| [0:16:01](https://www.bilibili.com/video/BV1H44y1v7Kf?t=961) | 可能应该是 昂萨姆布 | 1 |
| [0:16:24](https://www.bilibili.com/video/BV1H44y1v7Kf?t=984) | 降偏差和方差都可以用stacking | 1 |
| [0:16:28](https://www.bilibili.com/video/BV1H44y1v7Kf?t=988) | 随机森林就是bagging | 1 |
| [0:16:35](https://www.bilibili.com/video/BV1H44y1v7Kf?t=995) | 随机森林是bagging的一个变种…… | 1 |
| [0:16:35](https://www.bilibili.com/video/BV1H44y1v7Kf?t=995) | 前边提到grediant boosting decision tree里面boosting是这个意思吗 | 1 |
| [0:16:46](https://www.bilibili.com/video/BV1H44y1v7Kf?t=1006) | 数据范围影响泛化的上限 | 1 |

## 全部有实质内容的弹幕（按时间排序，共 75 条）

- `0:00:04`**好了，我上节课已经开心过了**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=4)
- `0:00:07`**瓦坎达forever！**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=7)
- `0:00:32`**真实的模型是什么？怎么来的？**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=32)
- `0:00:45`**这个中心点怎么来的？**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=45)
- `0:00:52`**不同的点时用不同的数据训练的到的模型，然后进行预测得到的值吧？**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=52)
- `0:00:55`**瓦坎达Forever！**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=55)
- `0:01:00`**相同数据集，相同的网络结构？**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=60)
- `0:01:09`**模型对数据分布的敏感性**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=69)
- `0:01:16`**这个图做的太好了，一下子就理解到了**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=76)
- `0:02:37`**偏差应该算是准确性，方差算是稳定性，我是这么理解的**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=157)
- `0:02:39`**wakanda forever**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=159)
- `0:02:44`**这个和过拟合和欠拟合有关系吧**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=164)
- `0:02:49`**关系不大，这个方差是多次训练的结果**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=169)
- `0:02:53`**在模型上如何调整呢？**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=173)
- `0:02:54`**偏差：瞄准精度，方差：弹道集中度**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=174)
- `0:02:54`**老师的衣服是瓦坎达么**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=174)
- `0:02:56`**偏差和期望什么区别？**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=176)
- `0:03:28`**Merry Christmas**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=208)
- `0:03:29`**才看到，大神穿的是黑豹啊**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=209)
- `0:04:49`**D是不同的数据集的子集（采样）**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=289)
- `0:05:07`**请问E()代表求期望吗？**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=307)
- `0:05:25`**补概率论吧，机器学习可以放一放了**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=325)
- `0:05:27`**expectation**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=327)
- `0:06:12`**f是理想的模型？与训练集天关**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=372)
- `0:06:23`**这里举例 f是真实模型，数据就是用f生成的**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=383)
- `0:06:33`**机器学习学了三四遍了**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=393)
- `0:07:03`**为什么左边期望有下标D，等式右边没有啊**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=423)
- `0:07:10`**这个里的y=f+误差，指的是测量设备本身的误差+真正的结果，得到现在测量结果y**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=430)
- `0:07:19`**三四遍的那个留下，我六七遍了**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=439)
- `0:07:24`**假设是独立的。实际上可能有交互作用。**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=444)
- `0:07:28`**我错了，并没有交叉效应。因为是泛化表现。**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=448)
- `0:07:44`**这里假设是同方差吧，如果数据分布是异方差就不能这么处理了嘛？**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=464)
- `0:07:48`**独立样本之间的联合概率密度等于分别概率的乘积**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=468)
- `0:07:54`**每次都是从入门到放弃**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=474)
- `0:08:45`**第一项是偏差的平方！**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=525)
- `0:08:56`**听君一席话胜读十年书**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=536)
- `0:08:57`**好清晰的思路一个式子2个概念都理清了**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=537)
- `0:08:57`**方差本身就包含平方了，所以不用再平方了！**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=537)
- `0:09:07`**这个偏差还不是跟真实的label**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=547)
- `0:09:18`**我感觉老师讲的是对的啊**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=558)
- `0:09:20`**倒数第二排最后一项右端是不是多了一个小括号？**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=560)
- `0:09:24`**怎么看起来像是D是同一个数据集呢**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=564)
- `0:09:26`**E（X^2）=D（X）+E（X）*E（X**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=566)
- `0:09:28`**f怎么来的？  f_hat是不同次训练的模型，f呢？**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=568)
- `0:09:29`**方差等于平方的期望减期望的平方**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=569)
- `0:09:31`**这不是sigma期望的平方，是平方的期望，所以不是0**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=571)
- `0:09:47`**最后一项是噪声的平方！**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=587)
- `0:09:59`**这个式子太清晰，白话：你的模型既要准也要稳定，真实标签的噪声不是你能掌握的**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=599)
- `0:10:03`**偏差不是跟真实值？而是跟f的偏差？**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=603)
- `0:10:52`**外面刚刚有直升机飞过**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=652)
- `0:11:26`**为啥从5点几跳到9点几了呢**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=686)
- `0:11:36`**好像增加模型随机性可以减少方差的吧**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=696)
- `0:11:38`**偏差是跟 训练模型的均值 做差，说明均值跟f 很近**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=698)
- `0:11:47`**交叉点就是泛化误差的最低点**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=707)
- `0:12:29`**var变化这没讲清楚 是学习结果的多样性**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=749)
- `0:12:29`**大语言模型每次输出结果都不太一样，但是意思都差不多，就是偏差小方差大的体现！**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=749)
- `0:12:31`**也觉得没讲清楚var**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=751)
- `0:12:34`**看不懂的直接去看bishop的模式识别**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=754)
- `0:12:39`**没懂的去看看概率论期望的公式**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=759)
- `0:12:41`**知道是评估指标并且会写代码就行了**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=761)
- `0:13:19`**如果模型复杂度高，拟合能力久更强，所以只要D符合真实分布，即使单次训练模型可能有偏差，多次训练得到的模型平均下来也会比简单模型更准确**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=799)
- `0:13:19`**前面的D是模型的训练数据，如果模型复杂程度高，D的变化会对模型造成的影响就更大，所以模型方差高（对D的采样结果更敏感）**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=799)
- `0:13:34`**讲的真好，又深刻理解方差和偏差了**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=814)
- `0:13:55`**我理解得慢慢的，但老师其实都面面俱到地讲了， 所以回看几遍基本上都能懂，老师太厉害啦！**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=835)
- `0:14:35`**你们也是用2倍速播放吗？**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=875)
- `0:14:43`**减少偏差要复杂模型，减少方差要简化模型，不冲突吗？**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=883)
- `0:15:39`**怎么降呢？怎么知道哪些数据是噪声？**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=939)
- `0:15:45`**←这就涉及数据质量判断和提升问题了**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=945)
- `0:16:00`**老师ensemble是不是读错了**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=960)
- `0:16:01`**可能应该是 昂萨姆布**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=961)
- `0:16:24`**降偏差和方差都可以用stacking**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=984)
- `0:16:28`**随机森林就是bagging**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=988)
- `0:16:35`**随机森林是bagging的一个变种……**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=995)
- `0:16:35`**前边提到grediant boosting decision tree里面boosting是这个意思吗**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=995)
- `0:16:46`**数据范围影响泛化的上限**　[↗](https://www.bilibili.com/video/BV1H44y1v7Kf?t=1006)
