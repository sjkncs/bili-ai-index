# 弹幕讨论 · 9.2 超参数优化【斯坦福21秋季：实用机器学习中文版】

> 视频：[BV1FM4y1c7yG](https://www.bilibili.com/video/BV1FM4y1c7yG)　时长 0:40:41　弹幕总数 **248**　有实质内容 **120** 条　重点标记 **120** 条
>
> 来源：B 站 **跟李沐学AI** 的该集弹幕　快照：**2026-10-13**

## 口径说明（务必先读）

**这些内容全部是观众在视频上发的弹幕，不是经过核实的结论。**

- 其中有价值的：概念解释、类比、勘误、学习方法、延伸阅读线索。
- **也可能有错误的**：弹幕是个人理解，未经作者或权威确认。
  **本页不为其正确性背书，请勿直接引用为事实。**
- 每条带时间戳，点击可跳回视频对应位置自行核对。
- 筛选口径：保留长度 ≥ 10 字符、且不含纯感叹/打卡类噪声的弹幕，共 120 条（占该集弹幕 248 条的 48.4%）；同一句话被多人发送只保留一条并标注发送次数。
- 「重点」标记由关键词打分得出（技术词 + 解释性措辞 + 长度 + 多人重复），共 120 条；**它是启发式排序，不代表正确性，也不代表其余条目无价值。**

## 重点条目

| 时间 | 弹幕 | 发送次数 |
|---|---|---:|
| [0:00:12](https://www.bilibili.com/video/BV1FM4y1c7yG?t=12) | 不但不鸽，而且更到你跟不上 | 1 |
| [0:02:04](https://www.bilibili.com/video/BV1FM4y1c7yG?t=124) | 字幕好像错了，做log后-6到-1随机取，相当于去掉那个10的底数 | 1 |
| [0:03:43](https://www.bilibili.com/video/BV1FM4y1c7yG?t=223) | 3个朋友，你们晚上好 | 1 |
| [0:03:51](https://www.bilibili.com/video/BV1FM4y1c7yG?t=231) | weight decay 别设太大，模型直接欠拟合 | 1 |
| [0:03:56](https://www.bilibili.com/video/BV1FM4y1c7yG?t=236) | 感觉需要补一补前面的 | 1 |
| [0:03:59](https://www.bilibili.com/video/BV1FM4y1c7yG?t=239) | 么么哒拉，我是小白白啊 | 1 |
| [0:04:33](https://www.bilibili.com/video/BV1FM4y1c7yG?t=273) | 入个der，这课就不是用来入门的 | 1 |
| [0:04:35](https://www.bilibili.com/video/BV1FM4y1c7yG?t=275) | detecror换不同的 backbone? | 1 |
| [0:04:52](https://www.bilibili.com/video/BV1FM4y1c7yG?t=292) | 入门用深度学习解决实际问题 | 1 |
| [0:07:27](https://www.bilibili.com/video/BV1FM4y1c7yG?t=447) | 那评估这个超参数的好坏也是需要结果来评估的呀，请教 | 1 |
| [0:07:56](https://www.bilibili.com/video/BV1FM4y1c7yG?t=476) | 关键是超参数的好坏有时候跟数据集大小有关 | 1 |
| [0:08:27](https://www.bilibili.com/video/BV1FM4y1c7yG?t=507) | 那这两批方法都是需要的 | 1 |
| [0:08:31](https://www.bilibili.com/video/BV1FM4y1c7yG?t=511) | 本来可解释性就差，再加上这种无法证明的推演延申。。。。 | 1 |
| [0:10:29](https://www.bilibili.com/video/BV1FM4y1c7yG?t=629) | 想听模拟退火和遗传算法 | 1 |
| [0:10:36](https://www.bilibili.com/video/BV1FM4y1c7yG?t=636) | SA和GA这种启发式算法感觉有点扯 | 1 |
| [0:10:41](https://www.bilibili.com/video/BV1FM4y1c7yG?t=641) | 遗传算法不属于机器学习 | 1 |
| [0:10:43](https://www.bilibili.com/video/BV1FM4y1c7yG?t=643) | 。。。模拟退火和遗传算法去听数学建模的课更快吧 | 1 |
| [0:10:43](https://www.bilibili.com/video/BV1FM4y1c7yG?t=643) | 因为定义不具体, 讨论属不属意义不大 | 1 |
| [0:10:46](https://www.bilibili.com/video/BV1FM4y1c7yG?t=646) | 模拟退火的去看数模就行 | 1 |
| [0:10:46](https://www.bilibili.com/video/BV1FM4y1c7yG?t=646) | 都特简单，看看wiki就懂了 | 1 |
| [0:11:17](https://www.bilibili.com/video/BV1FM4y1c7yG?t=677) | random比grid要好一点 | 1 |
| [0:11:49](https://www.bilibili.com/video/BV1FM4y1c7yG?t=709) | 在下就这样把自己的3090干爆了 | 1 |
| [0:12:20](https://www.bilibili.com/video/BV1FM4y1c7yG?t=740) | 超参数是浮点数类型，范围就大了 | 1 |
| [0:12:23](https://www.bilibili.com/video/BV1FM4y1c7yG?t=743) | money is all u need | 1 |
| [0:12:43](https://www.bilibili.com/video/BV1FM4y1c7yG?t=763) | 原来老师还可以该位置 | 1 |
| [0:13:00](https://www.bilibili.com/video/BV1FM4y1c7yG?t=780) | 家里有卡不怕，让他搜 | 1 |
| [0:13:05](https://www.bilibili.com/video/BV1FM4y1c7yG?t=785) | stochastic | 1 |
| [0:13:39](https://www.bilibili.com/video/BV1FM4y1c7yG?t=819) | 本质上就是穷举和采样的区别 | 1 |
| [0:13:51](https://www.bilibili.com/video/BV1FM4y1c7yG?t=831) | 那n是不是也可以算是一个超参数了 | 1 |
| [0:13:59](https://www.bilibili.com/video/BV1FM4y1c7yG?t=839) | 那这个n也成了超参数了 | 1 |
| [0:14:08](https://www.bilibili.com/video/BV1FM4y1c7yG?t=848) | 这个n是不是要叫超超参数（ | 1 |
| [0:14:16](https://www.bilibili.com/video/BV1FM4y1c7yG?t=856) | 不放回的，重复训练一组参数那不是浪费时间吗 | 1 |
| [0:14:17](https://www.bilibili.com/video/BV1FM4y1c7yG?t=857) | 肯定不放回。择优不是为了鲁棒 | 1 |
| [0:14:49](https://www.bilibili.com/video/BV1FM4y1c7yG?t=889) | early stopping | 1 |
| [0:15:40](https://www.bilibili.com/video/BV1FM4y1c7yG?t=940) | 随机搜索怎么能保证是一直增长的？ | 1 |
| [0:15:42](https://www.bilibili.com/video/BV1FM4y1c7yG?t=942) | 对啊，随机搜索很难收敛把 | 1 |
| [0:15:44](https://www.bilibili.com/video/BV1FM4y1c7yG?t=944) | 因为这个图应该是目前最优结果的曲线，不是实时结果的曲线 | 1 |
| [0:15:47](https://www.bilibili.com/video/BV1FM4y1c7yG?t=947) | 这个曲线必定是单调增的，但是未必严格单调增 | 1 |
| [0:15:59](https://www.bilibili.com/video/BV1FM4y1c7yG?t=959) | 参考精英保留遗传算法，在随机的过程中，可以把最好的结果保存下来~ | 1 |
| [0:16:01](https://www.bilibili.com/video/BV1FM4y1c7yG?t=961) | 要是绿色的情况那就老倒霉蛋了 | 1 |
| [0:16:02](https://www.bilibili.com/video/BV1FM4y1c7yG?t=962) | 也就是说在以后的时间内产生的不好的结果不做统计，在遇到更好的结果前保持不变，如果一段时间内找不到更好的结果就可以停止了 | 1 |
| [0:16:18](https://www.bilibili.com/video/BV1FM4y1c7yG?t=978) | 是训练过程中吧？不是随机选参过程停止吧？ | 1 |
| [0:16:32](https://www.bilibili.com/video/BV1FM4y1c7yG?t=992) | 不是最优也是局部最优了，问题不大 | 1 |
| [0:16:56](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1016) | 在代码中写一个早停就好 | 1 |
| [0:16:58](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1018) | 这个显然不一定是单调增吧？最优的几个解就那么几个了？玄学啊 | 1 |
| [0:17:09](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1029) | 基于观察修改先验分布，产生置信度较高的后验 | 1 |
| [0:17:41](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1061) | 但是AutoML 很多用的BO | 1 |
| [0:18:02](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1082) | target = 他给的，学到了！！哈哈！！ | 1 |
| [0:18:11](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1091) | 诶？这里写的不就是map么 | 1 |
| [0:18:22](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1102) | 那你最早的prior是哪里来呢 | 1 |
| [0:18:38](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1118) | 这是太卷了还是开始套娃了。。 | 1 |
| [0:18:38](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1118) | Meta Model | 1 |
| [0:18:45](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1125) | 通过概率帮助做到比random稍好一点的结果 | 1 |
| [0:19:34](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1174) | 用魔法打败魔法，用玄学解决玄学 | 1 |
| [0:19:41](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1181) | 都是基于概率的模型啊 | 1 |
| [0:20:17](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1217) | 全是传统概率模型里的东西 | 1 |
| [0:20:45](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1245) | 置信区间还是置信度？ | 1 |
| [0:21:00](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1260) | 我也不知道这是置信区间还是置信带 | 1 |
| [0:21:03](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1263) | 置信区间吧，正负西格玛 | 1 |
| [0:21:21](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1281) | 正负一个西格玛，95%置信区间 不要纠结用词 | 1 |
| [0:21:46](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1306) | 那不就变成了网格调参 | 1 |
| [0:22:36](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1356) | 请问这里的不置信是指什么不置信？ | 1 |
| [0:22:42](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1362) | 不置信指的是model预测的这组超参数的validation accuracy的置信区间比较大（不确定性比较大） | 1 |
| [0:22:52](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1372) | 这个置信和不确定度、信息熵的概念有点像吧 | 1 |
| [0:22:52](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1372) | 有点类似主动学习的查询函数 | 1 |
| [0:23:04](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1384) | 目标函数是最小化，选目标函数对应的点，点坐标再选最不置信的超参数，去优化 | 1 |
| [0:23:14](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1394) | 弹幕呢？怎么没人说话了。 | 1 |
| [0:23:18](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1398) | 取最大值是因为我们想要最大值，比如准确度 | 1 |
| [0:23:33](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1413) | 专心听课，虽然听不懂 | 1 |
| [0:24:15](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1455) | 那为什么右边那个已采样点的获取函数不等于0呢 | 1 |
| [0:24:32](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1472) | 怎么嗅到了强化学习的味道 | 1 |
| [0:24:33](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1473) | 探索与利用的trade off | 1 |
| [0:24:38](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1478) | exploitate 开采.v | 1 |
| [0:24:42](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1482) | 能用强化学习做强化学习网络的超参数优化吗 | 1 |
| [0:24:43](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1483) | 人生就是一次退火算法 | 1 |
| [0:24:50](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1490) | 这个是贝叶斯统计嘛？ | 1 |
| [0:24:51](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1491) | 升华主题了哈哈哈哈哈哈 | 1 |
| [0:25:26](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1526) | 可以理解为启发式搜索吧 | 1 |
| [0:25:26](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1526) | prml那本书貌似有这个东西 | 1 |
| [0:26:14](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1574) | 我只喜欢Grid() | 1 |
| [0:26:50](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1610) | 不能并行采一堆点来初始化吗 | 1 |
| [0:26:51](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1611) | 老师我真的悟了，读万卷书不如来看下视频 | 1 |
| [0:26:58](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1618) | 先并行算几个点?作为拟合的点，然后再用BO算下一个超参数？ | 1 |
| [0:27:05](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1625) | 并行采集100个就不符合贝叶斯的那个公式了吧 | 1 |
| [0:27:44](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1664) | random yyds | 1 |
| [0:27:56](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1676) | 贝叶斯优化还需要继续发展才行 | 1 |
| [0:27:59](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1679) | 这么多年也没有明显的进步呀... | 1 |
| [0:28:41](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1721) | 不行，sh只代表snow halation | 1 |
| [0:30:54](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1854) | 扔掉的超参数设置什么值呢？随机？ | 1 |
| [0:30:58](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1858) | 计算机领域最喜欢的二分 | 1 |
| [0:31:13](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1873) | 多参数优化好像就有很多群算法和演化算法了 | 1 |
| [0:31:14](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1874) | 怎么看着绿色的是潜力股啊 | 1 |
| [0:31:26](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1886) | 这样不会错误的扔掉一些比较慢但是可能之后结果很好的吗 | 1 |
| [0:31:27](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1887) | 本质也是random。但是做了止损 | 1 |
| [0:31:41](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1901) | HPO就是玄学 没有百分百保证 | 1 |
| [0:31:53](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1913) | 如果一开始16个选的不好 岂不是会很惨 | 1 |
| [0:32:01](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1921) | 当然会错误地丢掉潜力股，但是你要明白这个过程本来就是黑盒的，物竞天择适者生存的本质是贪心！考虑了计算成本的话，我们无论如何是得不到最优的参数组合的 | 1 |
| [0:32:02](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1922) | 可以试试随机减半吗？ | 1 |
| [0:32:03](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1923) | 所以一开始就得选个好的超参区间 | 1 |
| [0:32:07](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1927) | 随机减半的话，还需要训练干嘛 | 1 |
| [0:32:24](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1944) | HPO真的只想接受GRID，但是没办法。。。没钱没算力 | 1 |
| [0:32:25](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1945) | m是模型特性决定的，对于一类模型，应该可以提前知道要训练几轮；再加上有限的训练budget，n就用除法得到 | 1 |
| [0:32:31](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1951) | 唉automl还是要超参数，但是减少了超参数的分析数量吧 | 1 |
| [0:33:19](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1999) | 一开始 比较便宜，可以选的广泛一点 | 1 |
| [0:34:59](https://www.bilibili.com/video/BV1FM4y1c7yG?t=2099) | 用什么来断定淘汰哪个超参数？ | 1 |
| [0:35:16](https://www.bilibili.com/video/BV1FM4y1c7yG?t=2116) | 这里用的是验证机准确度来判断的 | 1 |
| [0:35:26](https://www.bilibili.com/video/BV1FM4y1c7yG?t=2126) | 怎么看到最后精度还不如最开始那个 | 1 |
| [0:35:46](https://www.bilibili.com/video/BV1FM4y1c7yG?t=2146) | 好像这儿不太对，hyperband似乎不是训练前一次的前50%，而是从新采样超参数？ | 1 |
| [0:35:55](https://www.bilibili.com/video/BV1FM4y1c7yG?t=2155) | 那这样不是每一次找到topK以后就可以停止了吗 | 1 |
| [0:35:59](https://www.bilibili.com/video/BV1FM4y1c7yG?t=2159) | 最好的怎么有个那么差 | 1 |
| [0:36:03](https://www.bilibili.com/video/BV1FM4y1c7yG?t=2163) | 最后一个图好像对不上 | 1 |
| [0:36:26](https://www.bilibili.com/video/BV1FM4y1c7yG?t=2186) | 为啥右下图的top accuracy还不如左下图呢？ | 1 |
| [0:36:37](https://www.bilibili.com/video/BV1FM4y1c7yG?t=2197) | 对的吧？人家已经跑完的不用在跑一遍了 | 1 |
| [0:36:42](https://www.bilibili.com/video/BV1FM4y1c7yG?t=2202) | 所以为啥最后一个这么差 | 1 |
| [0:36:49](https://www.bilibili.com/video/BV1FM4y1c7yG?t=2209) | 这些都是工程的思维那 | 1 |
| [0:36:51](https://www.bilibili.com/video/BV1FM4y1c7yG?t=2211) | 就是帮你多次调整n和m的值 | 1 |
| [0:36:54](https://www.bilibili.com/video/BV1FM4y1c7yG?t=2214) | 实际情况就这样啊，本来就是试出来的 | 1 |
| [0:36:59](https://www.bilibili.com/video/BV1FM4y1c7yG?t=2219) | 不知道这个训练曲线的形状有没有什么先验知识，要是有的话就可以大致估计一条然后再选多训练哪些了 | 1 |
| [0:39:13](https://www.bilibili.com/video/BV1FM4y1c7yG?t=2353) | default值万岁 | 1 |
| [0:39:20](https://www.bilibili.com/video/BV1FM4y1c7yG?t=2360) | meta learning内容了 | 1 |

## 全部有实质内容的弹幕（按时间排序，共 120 条）

- `0:00:12`**不但不鸽，而且更到你跟不上**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=12)
- `0:02:04`**字幕好像错了，做log后-6到-1随机取，相当于去掉那个10的底数**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=124)
- `0:03:43`**3个朋友，你们晚上好**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=223)
- `0:03:51`**weight decay 别设太大，模型直接欠拟合**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=231)
- `0:03:56`**感觉需要补一补前面的**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=236)
- `0:03:59`**么么哒拉，我是小白白啊**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=239)
- `0:04:33`**入个der，这课就不是用来入门的**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=273)
- `0:04:35`**detecror换不同的 backbone?**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=275)
- `0:04:52`**入门用深度学习解决实际问题**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=292)
- `0:07:27`**那评估这个超参数的好坏也是需要结果来评估的呀，请教**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=447)
- `0:07:56`**关键是超参数的好坏有时候跟数据集大小有关**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=476)
- `0:08:27`**那这两批方法都是需要的**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=507)
- `0:08:31`**本来可解释性就差，再加上这种无法证明的推演延申。。。。**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=511)
- `0:10:29`**想听模拟退火和遗传算法**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=629)
- `0:10:36`**SA和GA这种启发式算法感觉有点扯**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=636)
- `0:10:41`**遗传算法不属于机器学习**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=641)
- `0:10:43`**。。。模拟退火和遗传算法去听数学建模的课更快吧**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=643)
- `0:10:43`**因为定义不具体, 讨论属不属意义不大**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=643)
- `0:10:46`**模拟退火的去看数模就行**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=646)
- `0:10:46`**都特简单，看看wiki就懂了**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=646)
- `0:11:17`**random比grid要好一点**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=677)
- `0:11:49`**在下就这样把自己的3090干爆了**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=709)
- `0:12:20`**超参数是浮点数类型，范围就大了**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=740)
- `0:12:23`**money is all u need**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=743)
- `0:12:43`**原来老师还可以该位置**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=763)
- `0:13:00`**家里有卡不怕，让他搜**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=780)
- `0:13:05`**stochastic**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=785)
- `0:13:39`**本质上就是穷举和采样的区别**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=819)
- `0:13:51`**那n是不是也可以算是一个超参数了**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=831)
- `0:13:59`**那这个n也成了超参数了**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=839)
- `0:14:08`**这个n是不是要叫超超参数（**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=848)
- `0:14:16`**不放回的，重复训练一组参数那不是浪费时间吗**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=856)
- `0:14:17`**肯定不放回。择优不是为了鲁棒**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=857)
- `0:14:49`**early stopping**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=889)
- `0:15:40`**随机搜索怎么能保证是一直增长的？**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=940)
- `0:15:42`**对啊，随机搜索很难收敛把**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=942)
- `0:15:44`**因为这个图应该是目前最优结果的曲线，不是实时结果的曲线**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=944)
- `0:15:47`**这个曲线必定是单调增的，但是未必严格单调增**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=947)
- `0:15:59`**参考精英保留遗传算法，在随机的过程中，可以把最好的结果保存下来~**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=959)
- `0:16:01`**要是绿色的情况那就老倒霉蛋了**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=961)
- `0:16:02`**也就是说在以后的时间内产生的不好的结果不做统计，在遇到更好的结果前保持不变，如果一段时间内找不到更好的结果就可以停止了**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=962)
- `0:16:18`**是训练过程中吧？不是随机选参过程停止吧？**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=978)
- `0:16:32`**不是最优也是局部最优了，问题不大**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=992)
- `0:16:56`**在代码中写一个早停就好**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1016)
- `0:16:58`**这个显然不一定是单调增吧？最优的几个解就那么几个了？玄学啊**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1018)
- `0:17:09`**基于观察修改先验分布，产生置信度较高的后验**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1029)
- `0:17:41`**但是AutoML 很多用的BO**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1061)
- `0:18:02`**target = 他给的，学到了！！哈哈！！**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1082)
- `0:18:11`**诶？这里写的不就是map么**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1091)
- `0:18:22`**那你最早的prior是哪里来呢**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1102)
- `0:18:38`**这是太卷了还是开始套娃了。。**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1118)
- `0:18:38`**Meta Model**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1118)
- `0:18:45`**通过概率帮助做到比random稍好一点的结果**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1125)
- `0:19:34`**用魔法打败魔法，用玄学解决玄学**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1174)
- `0:19:41`**都是基于概率的模型啊**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1181)
- `0:20:17`**全是传统概率模型里的东西**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1217)
- `0:20:45`**置信区间还是置信度？**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1245)
- `0:21:00`**我也不知道这是置信区间还是置信带**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1260)
- `0:21:03`**置信区间吧，正负西格玛**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1263)
- `0:21:21`**正负一个西格玛，95%置信区间 不要纠结用词**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1281)
- `0:21:46`**那不就变成了网格调参**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1306)
- `0:22:36`**请问这里的不置信是指什么不置信？**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1356)
- `0:22:42`**不置信指的是model预测的这组超参数的validation accuracy的置信区间比较大（不确定性比较大）**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1362)
- `0:22:52`**这个置信和不确定度、信息熵的概念有点像吧**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1372)
- `0:22:52`**有点类似主动学习的查询函数**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1372)
- `0:23:04`**目标函数是最小化，选目标函数对应的点，点坐标再选最不置信的超参数，去优化**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1384)
- `0:23:14`**弹幕呢？怎么没人说话了。**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1394)
- `0:23:18`**取最大值是因为我们想要最大值，比如准确度**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1398)
- `0:23:33`**专心听课，虽然听不懂**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1413)
- `0:24:15`**那为什么右边那个已采样点的获取函数不等于0呢**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1455)
- `0:24:32`**怎么嗅到了强化学习的味道**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1472)
- `0:24:33`**探索与利用的trade off**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1473)
- `0:24:38`**exploitate 开采.v**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1478)
- `0:24:42`**能用强化学习做强化学习网络的超参数优化吗**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1482)
- `0:24:43`**人生就是一次退火算法**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1483)
- `0:24:50`**这个是贝叶斯统计嘛？**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1490)
- `0:24:51`**升华主题了哈哈哈哈哈哈**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1491)
- `0:25:26`**可以理解为启发式搜索吧**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1526)
- `0:25:26`**prml那本书貌似有这个东西**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1526)
- `0:26:14`**我只喜欢Grid()**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1574)
- `0:26:50`**不能并行采一堆点来初始化吗**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1610)
- `0:26:51`**老师我真的悟了，读万卷书不如来看下视频**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1611)
- `0:26:58`**先并行算几个点?作为拟合的点，然后再用BO算下一个超参数？**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1618)
- `0:27:05`**并行采集100个就不符合贝叶斯的那个公式了吧**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1625)
- `0:27:44`**random yyds**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1664)
- `0:27:56`**贝叶斯优化还需要继续发展才行**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1676)
- `0:27:59`**这么多年也没有明显的进步呀...**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1679)
- `0:28:41`**不行，sh只代表snow halation**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1721)
- `0:30:54`**扔掉的超参数设置什么值呢？随机？**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1854)
- `0:30:58`**计算机领域最喜欢的二分**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1858)
- `0:31:13`**多参数优化好像就有很多群算法和演化算法了**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1873)
- `0:31:14`**怎么看着绿色的是潜力股啊**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1874)
- `0:31:26`**这样不会错误的扔掉一些比较慢但是可能之后结果很好的吗**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1886)
- `0:31:27`**本质也是random。但是做了止损**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1887)
- `0:31:41`**HPO就是玄学 没有百分百保证**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1901)
- `0:31:53`**如果一开始16个选的不好 岂不是会很惨**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1913)
- `0:32:01`**当然会错误地丢掉潜力股，但是你要明白这个过程本来就是黑盒的，物竞天择适者生存的本质是贪心！考虑了计算成本的话，我们无论如何是得不到最优的参数组合的**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1921)
- `0:32:02`**可以试试随机减半吗？**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1922)
- `0:32:03`**所以一开始就得选个好的超参区间**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1923)
- `0:32:07`**随机减半的话，还需要训练干嘛**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1927)
- `0:32:24`**HPO真的只想接受GRID，但是没办法。。。没钱没算力**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1944)
- `0:32:25`**m是模型特性决定的，对于一类模型，应该可以提前知道要训练几轮；再加上有限的训练budget，n就用除法得到**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1945)
- `0:32:31`**唉automl还是要超参数，但是减少了超参数的分析数量吧**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1951)
- `0:33:19`**一开始 比较便宜，可以选的广泛一点**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=1999)
- `0:34:59`**用什么来断定淘汰哪个超参数？**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=2099)
- `0:35:16`**这里用的是验证机准确度来判断的**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=2116)
- `0:35:26`**怎么看到最后精度还不如最开始那个**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=2126)
- `0:35:46`**好像这儿不太对，hyperband似乎不是训练前一次的前50%，而是从新采样超参数？**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=2146)
- `0:35:55`**那这样不是每一次找到topK以后就可以停止了吗**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=2155)
- `0:35:59`**最好的怎么有个那么差**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=2159)
- `0:36:03`**最后一个图好像对不上**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=2163)
- `0:36:26`**为啥右下图的top accuracy还不如左下图呢？**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=2186)
- `0:36:37`**对的吧？人家已经跑完的不用在跑一遍了**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=2197)
- `0:36:42`**所以为啥最后一个这么差**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=2202)
- `0:36:49`**这些都是工程的思维那**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=2209)
- `0:36:51`**就是帮你多次调整n和m的值**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=2211)
- `0:36:54`**实际情况就这样啊，本来就是试出来的**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=2214)
- `0:36:59`**不知道这个训练曲线的形状有没有什么先验知识，要是有的话就可以大致估计一条然后再选多训练哪些了**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=2219)
- `0:39:13`**default值万岁**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=2353)
- `0:39:20`**meta learning内容了**　[↗](https://www.bilibili.com/video/BV1FM4y1c7yG?t=2360)
