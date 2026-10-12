# 弹幕讨论 · 4.3 模型验证【斯坦福21秋季：实用机器学习中文版】

> 视频：[BV1Dh411x7hZ](https://www.bilibili.com/video/BV1Dh411x7hZ)　时长 0:23:07　弹幕总数 **136**　有实质内容 **60** 条　重点标记 **60** 条
>
> 来源：B 站 **跟李沐学AI** 的该集弹幕　快照：**2026-10-13**

## 口径说明（务必先读）

**这些内容全部是观众在视频上发的弹幕，不是经过核实的结论。**

- 其中有价值的：概念解释、类比、勘误、学习方法、延伸阅读线索。
- **也可能有错误的**：弹幕是个人理解，未经作者或权威确认。
  **本页不为其正确性背书，请勿直接引用为事实。**
- 每条带时间戳，点击可跳回视频对应位置自行核对。
- 筛选口径：保留长度 ≥ 10 字符、且不含纯感叹/打卡类噪声的弹幕，共 60 条（占该集弹幕 136 条的 44.1%）；同一句话被多人发送只保留一条并标注发送次数。
- 「重点」标记由关键词打分得出（技术词 + 解释性措辞 + 长度 + 多人重复），共 60 条；**它是启发式排序，不代表正确性，也不代表其余条目无价值。**

## 重点条目

| 时间 | 弹幕 | 发送次数 |
|---|---|---:|
| [0:02:14](https://www.bilibili.com/video/BV1Dh411x7hZ?t=134) | 其实333EGNNNNNNNNNNNNN/M | 1 |
| [0:02:40](https://www.bilibili.com/video/BV1Dh411x7hZ?t=160) | 测试数据集只能使用一次 | 1 |
| [0:02:41](https://www.bilibili.com/video/BV1Dh411x7hZ?t=161) | 吴恩达说：测试集可以反复用多次（如K折交叉验证），而验证集只能用一次，因为根据统计学理论，验证集是严格不参与训练的，与这里向左……唉，工程科学上的概念有时候确实没那么严谨…… | 1 |
| [0:02:54](https://www.bilibili.com/video/BV1Dh411x7hZ?t=174) | 前面把测试集、验证集说反了 | 1 |
| [0:02:57](https://www.bilibili.com/video/BV1Dh411x7hZ?t=177) | 这里跟西瓜书上是一样的 | 1 |
| [0:02:59](https://www.bilibili.com/video/BV1Dh411x7hZ?t=179) | 那是因为他说的是反的，要有点自己的判断力好不 | 1 |
| [0:03:00](https://www.bilibili.com/video/BV1Dh411x7hZ?t=180) | 验证集（验证的作用：用于在训练过程中评估模型的性能和调整超参数。在每个训练周期（epoch）结束时，模型会在验证集上进行评估，以判断模型是否过拟合、欠拟合，以及调整超参数） | 1 |
| [0:03:06](https://www.bilibili.com/video/BV1Dh411x7hZ?t=186) | 测试集  用于最终评估模型的泛化性能 | 1 |
| [0:03:14](https://www.bilibili.com/video/BV1Dh411x7hZ?t=194) | 相当于LC的hidden test cases？感觉 :) | 1 |
| [0:03:26](https://www.bilibili.com/video/BV1Dh411x7hZ?t=206) | 训练集、验证集、测试集，继续学习 | 1 |
| [0:03:41](https://www.bilibili.com/video/BV1Dh411x7hZ?t=221) | 为什么只能用一次？不用来训练不就可多次用了吗？ | 1 |
| [0:03:46](https://www.bilibili.com/video/BV1Dh411x7hZ?t=226) | 重点是不能根据模型在测试集的表现调整模型，然而不调整模型，每次运行的结果都是一样的了，运行多次也就没有任何意义。 | 1 |
| [0:04:17](https://www.bilibili.com/video/BV1Dh411x7hZ?t=257) | 数据集拆开成训练集和验证集 | 1 |
| [0:04:35](https://www.bilibili.com/video/BV1Dh411x7hZ?t=275) | test data  valid data  验证集 测试集  太不严谨了啪…… | 1 |
| [0:06:19](https://www.bilibili.com/video/BV1Dh411x7hZ?t=379) | 不是独立同分布下不能用随机抽样分嘛？ | 1 |
| [0:06:24](https://www.bilibili.com/video/BV1Dh411x7hZ?t=384) | Independent and identically distributed | 1 |
| [0:08:09](https://www.bilibili.com/video/BV1Dh411x7hZ?t=489) | scipy上就有专门的包来算插值，插值是什么意思呢？ | 1 |
| [0:08:17](https://www.bilibili.com/video/BV1Dh411x7hZ?t=497) | a2=(a1+a3)/2 | 1 |
| [0:08:17](https://www.bilibili.com/video/BV1Dh411x7hZ?t=497) | 差值详细原理请看数值分析 | 1 |
| [0:08:18](https://www.bilibili.com/video/BV1Dh411x7hZ?t=498) | 擦纸可以理解成给出两个已知的点和坐标去计算中间点的坐标值 | 1 |
| [0:08:20](https://www.bilibili.com/video/BV1Dh411x7hZ?t=500) | 就是字面意思，有部分值缺失了，通过某种方法在缺失部分填上值 | 1 |
| [0:08:41](https://www.bilibili.com/video/BV1Dh411x7hZ?t=521) | 字幕辛苦了，还有插入语 | 1 |
| [0:10:14](https://www.bilibili.com/video/BV1Dh411x7hZ?t=614) | 重点是怎么知道数据的分布情况 | 1 |
| [0:10:15](https://www.bilibili.com/video/BV1Dh411x7hZ?t=615) | 每种case的样本数怎么统计？ | 1 |
| [0:10:23](https://www.bilibili.com/video/BV1Dh411x7hZ?t=623) | 准备数据和特征工程的时候就应该知道了数据的分布。这个在前面讲到了 | 1 |
| [0:11:54](https://www.bilibili.com/video/BV1Dh411x7hZ?t=714) | 泛化误差两边都差不多？ | 1 |
| [0:11:59](https://www.bilibili.com/video/BV1Dh411x7hZ?t=719) | 因为随机取潜在的规律差一些？毕竟按顺序会有比较强的相关性 | 1 |
| [0:12:23](https://www.bilibili.com/video/BV1Dh411x7hZ?t=743) | 随机的验证集是取的同六个月里面的吧 | 1 |
| [0:12:32](https://www.bilibili.com/video/BV1Dh411x7hZ?t=752) | w2q1```aqsqAA@W～W%UW | 1 |
| [0:13:07](https://www.bilibili.com/video/BV1Dh411x7hZ?t=787) | Merry Christmas | 1 |
| [0:13:34](https://www.bilibili.com/video/BV1Dh411x7hZ?t=814) | 所以这里的结论是应该随机取样？但前面不是说房价预测不能随机取样吗 | 1 |
| [0:13:38](https://www.bilibili.com/video/BV1Dh411x7hZ?t=818) | 我觉得这里说的是线性回归本来就无法拟合这个模型，而随机分法显著低估了验证误差 | 1 |
| [0:13:51](https://www.bilibili.com/video/BV1Dh411x7hZ?t=831) | 所以我们应该随机采样? | 1 |
| [0:13:54](https://www.bilibili.com/video/BV1Dh411x7hZ?t=834) | 沐神意思是对于时序数据，随机采样和顺序采样会对模型产生不一样的效果，此时更应该使用顺序采样 | 1 |
| [0:14:00](https://www.bilibili.com/video/BV1Dh411x7hZ?t=840) | 肯定是顺序采样啊，这样才能提前发现模型过拟合了 | 1 |
| [0:14:10](https://www.bilibili.com/video/BV1Dh411x7hZ?t=850) | 顺序肯定合理但是模型难以训练，随机抽容易训练但模型训出来没啥用吧 | 1 |
| [0:14:21](https://www.bilibili.com/video/BV1Dh411x7hZ?t=861) | 总感觉看过是怎么回事儿？ | 1 |
| [0:14:28](https://www.bilibili.com/video/BV1Dh411x7hZ?t=868) | 动手学深度学习里讲过 | 1 |
| [0:14:38](https://www.bilibili.com/video/BV1Dh411x7hZ?t=878) | 三折叠，怎么折，都有面~ | 1 |
| [0:14:47](https://www.bilibili.com/video/BV1Dh411x7hZ?t=887) | 这个东西是个机器学习课都会讲，虽然将的方式不一样 | 1 |
| [0:14:50](https://www.bilibili.com/video/BV1Dh411x7hZ?t=890) | 那对于时序数据是不是不能用K折啊 | 1 |
| [0:15:45](https://www.bilibili.com/video/BV1Dh411x7hZ?t=945) | 那最后训练出的模型使用哪一个训练出来的参数呢？ | 1 |
| [0:15:48](https://www.bilibili.com/video/BV1Dh411x7hZ?t=948) | 是每个epoch更换一次？ | 1 |
| [0:16:01](https://www.bilibili.com/video/BV1Dh411x7hZ?t=961) | 相当于训练了K个模型，每个模型分别用某一fold的数据进行训练和验证。 | 1 |
| [0:16:15](https://www.bilibili.com/video/BV1Dh411x7hZ?t=975) | 不那么贵：指8张v100能跑通 | 1 |
| [0:16:17](https://www.bilibili.com/video/BV1Dh411x7hZ?t=977) | 这应该是同一参数，然后使用不同划分的训练集和测试集，综合评估在这一参数下模型的好坏 | 1 |
| [0:16:19](https://www.bilibili.com/video/BV1Dh411x7hZ?t=979) | 交叉验证后，只是为了做验证吗？该如是使用呢？ | 1 |
| [0:16:30](https://www.bilibili.com/video/BV1Dh411x7hZ?t=990) | 交叉验证完看完结果不错就直接测试集了呀，还不错就上线了 | 1 |
| [0:16:50](https://www.bilibili.com/video/BV1Dh411x7hZ?t=1010) | hahahahahahah | 1 |
| [0:16:57](https://www.bilibili.com/video/BV1Dh411x7hZ?t=1017) | 为什么这种污染，不能是有意的 | 1 |
| [0:16:58](https://www.bilibili.com/video/BV1Dh411x7hZ?t=1018) | 有没有可能我是天才呢 | 1 |
| [0:17:17](https://www.bilibili.com/video/BV1Dh411x7hZ?t=1037) | 我那个模型还真是这个原因 | 1 |
| [0:17:49](https://www.bilibili.com/video/BV1Dh411x7hZ?t=1069) | 有没有可能是故意的[狗头] | 1 |
| [0:18:51](https://www.bilibili.com/video/BV1Dh411x7hZ?t=1131) | 问题是某些搜索引擎也是用ImageNet给图片分类的啊 | 1 |
| [0:19:32](https://www.bilibili.com/video/BV1Dh411x7hZ?t=1172) | 自己拍图片hhh造数据集 | 1 |
| [0:20:14](https://www.bilibili.com/video/BV1Dh411x7hZ?t=1214) | 这感觉和第一条有点像 | 1 |
| [0:21:29](https://www.bilibili.com/video/BV1Dh411x7hZ?t=1289) | 理论看书，结合大神的视频，理解的更清楚 | 1 |
| [0:22:37](https://www.bilibili.com/video/BV1Dh411x7hZ?t=1357) | 懂了，这就去跟何凯明对线 | 1 |
| [0:22:55](https://www.bilibili.com/video/BV1Dh411x7hZ?t=1375) | 今天的烦恼就留给明天吧 | 1 |
| [0:22:58](https://www.bilibili.com/video/BV1Dh411x7hZ?t=1378) | 啊哈哈哈哈哈哈，呜呜呜呜呜呜，哭了。太真实了，但是当我开心过后，当晚通常是睡不着了。。。。 | 2 |

## 全部有实质内容的弹幕（按时间排序，共 60 条）

- `0:02:14`**其实333EGNNNNNNNNNNNNN/M**　[↗](https://www.bilibili.com/video/BV1Dh411x7hZ?t=134)
- `0:02:40`**测试数据集只能使用一次**　[↗](https://www.bilibili.com/video/BV1Dh411x7hZ?t=160)
- `0:02:41`**吴恩达说：测试集可以反复用多次（如K折交叉验证），而验证集只能用一次，因为根据统计学理论，验证集是严格不参与训练的，与这里向左……唉，工程科学上的概念有时候确实没那么严谨……**　[↗](https://www.bilibili.com/video/BV1Dh411x7hZ?t=161)
- `0:02:54`**前面把测试集、验证集说反了**　[↗](https://www.bilibili.com/video/BV1Dh411x7hZ?t=174)
- `0:02:57`**这里跟西瓜书上是一样的**　[↗](https://www.bilibili.com/video/BV1Dh411x7hZ?t=177)
- `0:02:59`**那是因为他说的是反的，要有点自己的判断力好不**　[↗](https://www.bilibili.com/video/BV1Dh411x7hZ?t=179)
- `0:03:00`**验证集（验证的作用：用于在训练过程中评估模型的性能和调整超参数。在每个训练周期（epoch）结束时，模型会在验证集上进行评估，以判断模型是否过拟合、欠拟合，以及调整超参数）**　[↗](https://www.bilibili.com/video/BV1Dh411x7hZ?t=180)
- `0:03:06`**测试集  用于最终评估模型的泛化性能**　[↗](https://www.bilibili.com/video/BV1Dh411x7hZ?t=186)
- `0:03:14`**相当于LC的hidden test cases？感觉 :)**　[↗](https://www.bilibili.com/video/BV1Dh411x7hZ?t=194)
- `0:03:26`**训练集、验证集、测试集，继续学习**　[↗](https://www.bilibili.com/video/BV1Dh411x7hZ?t=206)
- `0:03:41`**为什么只能用一次？不用来训练不就可多次用了吗？**　[↗](https://www.bilibili.com/video/BV1Dh411x7hZ?t=221)
- `0:03:46`**重点是不能根据模型在测试集的表现调整模型，然而不调整模型，每次运行的结果都是一样的了，运行多次也就没有任何意义。**　[↗](https://www.bilibili.com/video/BV1Dh411x7hZ?t=226)
- `0:04:17`**数据集拆开成训练集和验证集**　[↗](https://www.bilibili.com/video/BV1Dh411x7hZ?t=257)
- `0:04:35`**test data  valid data  验证集 测试集  太不严谨了啪……**　[↗](https://www.bilibili.com/video/BV1Dh411x7hZ?t=275)
- `0:06:19`**不是独立同分布下不能用随机抽样分嘛？**　[↗](https://www.bilibili.com/video/BV1Dh411x7hZ?t=379)
- `0:06:24`**Independent and identically distributed**　[↗](https://www.bilibili.com/video/BV1Dh411x7hZ?t=384)
- `0:08:09`**scipy上就有专门的包来算插值，插值是什么意思呢？**　[↗](https://www.bilibili.com/video/BV1Dh411x7hZ?t=489)
- `0:08:17`**a2=(a1+a3)/2**　[↗](https://www.bilibili.com/video/BV1Dh411x7hZ?t=497)
- `0:08:17`**差值详细原理请看数值分析**　[↗](https://www.bilibili.com/video/BV1Dh411x7hZ?t=497)
- `0:08:18`**擦纸可以理解成给出两个已知的点和坐标去计算中间点的坐标值**　[↗](https://www.bilibili.com/video/BV1Dh411x7hZ?t=498)
- `0:08:20`**就是字面意思，有部分值缺失了，通过某种方法在缺失部分填上值**　[↗](https://www.bilibili.com/video/BV1Dh411x7hZ?t=500)
- `0:08:41`**字幕辛苦了，还有插入语**　[↗](https://www.bilibili.com/video/BV1Dh411x7hZ?t=521)
- `0:10:14`**重点是怎么知道数据的分布情况**　[↗](https://www.bilibili.com/video/BV1Dh411x7hZ?t=614)
- `0:10:15`**每种case的样本数怎么统计？**　[↗](https://www.bilibili.com/video/BV1Dh411x7hZ?t=615)
- `0:10:23`**准备数据和特征工程的时候就应该知道了数据的分布。这个在前面讲到了**　[↗](https://www.bilibili.com/video/BV1Dh411x7hZ?t=623)
- `0:11:54`**泛化误差两边都差不多？**　[↗](https://www.bilibili.com/video/BV1Dh411x7hZ?t=714)
- `0:11:59`**因为随机取潜在的规律差一些？毕竟按顺序会有比较强的相关性**　[↗](https://www.bilibili.com/video/BV1Dh411x7hZ?t=719)
- `0:12:23`**随机的验证集是取的同六个月里面的吧**　[↗](https://www.bilibili.com/video/BV1Dh411x7hZ?t=743)
- `0:12:32`**w2q1```aqsqAA@W～W%UW**　[↗](https://www.bilibili.com/video/BV1Dh411x7hZ?t=752)
- `0:13:07`**Merry Christmas**　[↗](https://www.bilibili.com/video/BV1Dh411x7hZ?t=787)
- `0:13:34`**所以这里的结论是应该随机取样？但前面不是说房价预测不能随机取样吗**　[↗](https://www.bilibili.com/video/BV1Dh411x7hZ?t=814)
- `0:13:38`**我觉得这里说的是线性回归本来就无法拟合这个模型，而随机分法显著低估了验证误差**　[↗](https://www.bilibili.com/video/BV1Dh411x7hZ?t=818)
- `0:13:51`**所以我们应该随机采样?**　[↗](https://www.bilibili.com/video/BV1Dh411x7hZ?t=831)
- `0:13:54`**沐神意思是对于时序数据，随机采样和顺序采样会对模型产生不一样的效果，此时更应该使用顺序采样**　[↗](https://www.bilibili.com/video/BV1Dh411x7hZ?t=834)
- `0:14:00`**肯定是顺序采样啊，这样才能提前发现模型过拟合了**　[↗](https://www.bilibili.com/video/BV1Dh411x7hZ?t=840)
- `0:14:10`**顺序肯定合理但是模型难以训练，随机抽容易训练但模型训出来没啥用吧**　[↗](https://www.bilibili.com/video/BV1Dh411x7hZ?t=850)
- `0:14:21`**总感觉看过是怎么回事儿？**　[↗](https://www.bilibili.com/video/BV1Dh411x7hZ?t=861)
- `0:14:28`**动手学深度学习里讲过**　[↗](https://www.bilibili.com/video/BV1Dh411x7hZ?t=868)
- `0:14:38`**三折叠，怎么折，都有面~**　[↗](https://www.bilibili.com/video/BV1Dh411x7hZ?t=878)
- `0:14:47`**这个东西是个机器学习课都会讲，虽然将的方式不一样**　[↗](https://www.bilibili.com/video/BV1Dh411x7hZ?t=887)
- `0:14:50`**那对于时序数据是不是不能用K折啊**　[↗](https://www.bilibili.com/video/BV1Dh411x7hZ?t=890)
- `0:15:45`**那最后训练出的模型使用哪一个训练出来的参数呢？**　[↗](https://www.bilibili.com/video/BV1Dh411x7hZ?t=945)
- `0:15:48`**是每个epoch更换一次？**　[↗](https://www.bilibili.com/video/BV1Dh411x7hZ?t=948)
- `0:16:01`**相当于训练了K个模型，每个模型分别用某一fold的数据进行训练和验证。**　[↗](https://www.bilibili.com/video/BV1Dh411x7hZ?t=961)
- `0:16:15`**不那么贵：指8张v100能跑通**　[↗](https://www.bilibili.com/video/BV1Dh411x7hZ?t=975)
- `0:16:17`**这应该是同一参数，然后使用不同划分的训练集和测试集，综合评估在这一参数下模型的好坏**　[↗](https://www.bilibili.com/video/BV1Dh411x7hZ?t=977)
- `0:16:19`**交叉验证后，只是为了做验证吗？该如是使用呢？**　[↗](https://www.bilibili.com/video/BV1Dh411x7hZ?t=979)
- `0:16:30`**交叉验证完看完结果不错就直接测试集了呀，还不错就上线了**　[↗](https://www.bilibili.com/video/BV1Dh411x7hZ?t=990)
- `0:16:50`**hahahahahahah**　[↗](https://www.bilibili.com/video/BV1Dh411x7hZ?t=1010)
- `0:16:57`**为什么这种污染，不能是有意的**　[↗](https://www.bilibili.com/video/BV1Dh411x7hZ?t=1017)
- `0:16:58`**有没有可能我是天才呢**　[↗](https://www.bilibili.com/video/BV1Dh411x7hZ?t=1018)
- `0:17:17`**我那个模型还真是这个原因**　[↗](https://www.bilibili.com/video/BV1Dh411x7hZ?t=1037)
- `0:17:49`**有没有可能是故意的[狗头]**　[↗](https://www.bilibili.com/video/BV1Dh411x7hZ?t=1069)
- `0:18:51`**问题是某些搜索引擎也是用ImageNet给图片分类的啊**　[↗](https://www.bilibili.com/video/BV1Dh411x7hZ?t=1131)
- `0:19:32`**自己拍图片hhh造数据集**　[↗](https://www.bilibili.com/video/BV1Dh411x7hZ?t=1172)
- `0:20:14`**这感觉和第一条有点像**　[↗](https://www.bilibili.com/video/BV1Dh411x7hZ?t=1214)
- `0:21:29`**理论看书，结合大神的视频，理解的更清楚**　[↗](https://www.bilibili.com/video/BV1Dh411x7hZ?t=1289)
- `0:22:37`**懂了，这就去跟何凯明对线**　[↗](https://www.bilibili.com/video/BV1Dh411x7hZ?t=1357)
- `0:22:55`**今天的烦恼就留给明天吧**　[↗](https://www.bilibili.com/video/BV1Dh411x7hZ?t=1375)
- `0:22:58`**啊哈哈哈哈哈哈，呜呜呜呜呜呜，哭了。太真实了，但是当我开心过后，当晚通常是睡不着了。。。。**（×2）　[↗](https://www.bilibili.com/video/BV1Dh411x7hZ?t=1378)
