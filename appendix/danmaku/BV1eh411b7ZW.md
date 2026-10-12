# 弹幕讨论 · 3.3 最简单也同样最常用的线性模型【斯坦福21秋季：实用机器学习中文版】

> 视频：[BV1eh411b7ZW](https://www.bilibili.com/video/BV1eh411b7ZW)　时长 0:14:50　弹幕总数 **140**　有实质内容 **69** 条　重点标记 **69** 条
>
> 来源：B 站 **跟李沐学AI** 的该集弹幕　快照：**2026-10-13**

## 口径说明（务必先读）

**这些内容全部是观众在视频上发的弹幕，不是经过核实的结论。**

- 其中有价值的：概念解释、类比、勘误、学习方法、延伸阅读线索。
- **也可能有错误的**：弹幕是个人理解，未经作者或权威确认。
  **本页不为其正确性背书，请勿直接引用为事实。**
- 每条带时间戳，点击可跳回视频对应位置自行核对。
- 筛选口径：保留长度 ≥ 10 字符、且不含纯感叹/打卡类噪声的弹幕，共 69 条（占该集弹幕 140 条的 49.3%）；同一句话被多人发送只保留一条并标注发送次数。
- 「重点」标记由关键词打分得出（技术词 + 解释性措辞 + 长度 + 多人重复），共 69 条；**它是启发式排序，不代表正确性，也不代表其余条目无价值。**

## 重点条目

| 时间 | 弹幕 | 发送次数 |
|---|---|---:|
| [0:00:14](https://www.bilibili.com/video/BV1eh411b7ZW?t=14) | Merry Christmas | 1 |
| [0:00:14](https://www.bilibili.com/video/BV1eh411b7ZW?t=14) | 怎么这集声音突然小了 | 1 |
| [0:00:43](https://www.bilibili.com/video/BV1eh411b7ZW?t=43) | 还有现在看视频的啊，圣诞节快乐 | 1 |
| [0:00:53](https://www.bilibili.com/video/BV1eh411b7ZW?t=53) | 22年5.20 快乐！ | 1 |
| [0:01:04](https://www.bilibili.com/video/BV1eh411b7ZW?t=64) | 20260315，快乐！ | 1 |
| [0:01:14](https://www.bilibili.com/video/BV1eh411b7ZW?t=74) | Linear regression应用场景：股票价格预测，供应和销售量分析，医学诊断，计算时间序列相关性 | 1 |
| [0:01:52](https://www.bilibili.com/video/BV1eh411b7ZW?t=112) | 这不就是感知机？深度神经网络 | 1 |
| [0:02:30](https://www.bilibili.com/video/BV1eh411b7ZW?t=150) | X should be matrix (n, p) | 1 |
| [0:02:39](https://www.bilibili.com/video/BV1eh411b7ZW?t=159) | 其实直接向量乘法也可以 | 1 |
| [0:03:04](https://www.bilibili.com/video/BV1eh411b7ZW?t=184) | 刚开始是n*p，转置后才是p*n | 1 |
| [0:03:06](https://www.bilibili.com/video/BV1eh411b7ZW?t=186) | 这里说错了吧？长为P的向量？ | 1 |
| [0:03:11](https://www.bilibili.com/video/BV1eh411b7ZW?t=191) | 是的，p就是一个样本特征的个数 | 1 |
| [0:03:13](https://www.bilibili.com/video/BV1eh411b7ZW?t=193) | 就是长为n的向量，这里的是标签，只有一维，标签个数就是卖出去了所少个房子 | 1 |
| [0:03:20](https://www.bilibili.com/video/BV1eh411b7ZW?t=200) | n个长为P的向量有问题吗 | 1 |
| [0:03:24](https://www.bilibili.com/video/BV1eh411b7ZW?t=204) | 没说错。标号y表示的是房价，一共有n个，所以向量y是长为n的向量 | 1 |
| [0:03:43](https://www.bilibili.com/video/BV1eh411b7ZW?t=223) | 现在线性一般都是看r^2嘛？ | 1 |
| [0:04:07](https://www.bilibili.com/video/BV1eh411b7ZW?t=247) | 所有样本，不是用随机梯度下降 | 1 |
| [0:04:28](https://www.bilibili.com/video/BV1eh411b7ZW?t=268) | 那个是norm，这里是二范数 | 1 |
| [0:04:36](https://www.bilibili.com/video/BV1eh411b7ZW?t=276) | 真实值减估计值的期望 | 1 |
| [0:04:39](https://www.bilibili.com/video/BV1eh411b7ZW?t=279) | 好久没学过这些了，有人讲解看哭了 | 1 |
| [0:04:42](https://www.bilibili.com/video/BV1eh411b7ZW?t=282) | 那两根竖线就是绝对值符号 | 1 |
| [0:04:43](https://www.bilibili.com/video/BV1eh411b7ZW?t=283) | 这里取范数里面的不是一个值吗？ | 1 |
| [0:04:46](https://www.bilibili.com/video/BV1eh411b7ZW?t=286) | 如此清楚！感谢老师！ | 1 |
| [0:04:48](https://www.bilibili.com/video/BV1eh411b7ZW?t=288) | 说绝对值的，回去补补数学基础吧 | 1 |
| [0:04:53](https://www.bilibili.com/video/BV1eh411b7ZW?t=293) | 说绝对值的惊艳到我了。。。。。 | 1 |
| [0:05:19](https://www.bilibili.com/video/BV1eh411b7ZW?t=319) | 对于每个类来说，就是个线性回归任务？ | 1 |
| [0:05:39](https://www.bilibili.com/video/BV1eh411b7ZW?t=339) | 逻辑回归大哥让我醍醐灌顶！ | 1 |
| [0:06:08](https://www.bilibili.com/video/BV1eh411b7ZW?t=368) | 二分类问题，吴恩达老师讲过 | 1 |
| [0:06:37](https://www.bilibili.com/video/BV1eh411b7ZW?t=397) | softmax是多分类把，sigmoid才是逻辑回归的 | 1 |
| [0:06:51](https://www.bilibili.com/video/BV1eh411b7ZW?t=411) | 懂了懂了，想了好久。真是每句都是精髓。 | 1 |
| [0:06:56](https://www.bilibili.com/video/BV1eh411b7ZW?t=416) | 这不就是一层的神经网络吗，输出10个神经元 | 1 |
| [0:06:58](https://www.bilibili.com/video/BV1eh411b7ZW?t=418) | 看w和b的獲取方法吧，現在説是感知器還是神經網絡不好説，但不是向量機 | 1 |
| [0:06:59](https://www.bilibili.com/video/BV1eh411b7ZW?t=419) | 感觉就是个不加激活函数的单层（1层输入1层输出）神经网络 | 1 |
| [0:07:03](https://www.bilibili.com/video/BV1eh411b7ZW?t=423) | 和最近邻分类器有什么区别 | 1 |
| [0:07:10](https://www.bilibili.com/video/BV1eh411b7ZW?t=430) | 在每个位置列上还是转换为回归问题，只不过计算的是置信度 | 1 |
| [0:07:16](https://www.bilibili.com/video/BV1eh411b7ZW?t=436) | 这里不明白，wi bi为什么对应不同class有多个。 | 1 |
| [0:07:18](https://www.bilibili.com/video/BV1eh411b7ZW?t=438) | 你可以把所有带权重和偏置的全连接叫做感知机 | 1 |
| [0:07:22](https://www.bilibili.com/video/BV1eh411b7ZW?t=442) | one-hot encoding，独热编码。听到第二遍才反应过来 | 1 |
| [0:07:32](https://www.bilibili.com/video/BV1eh411b7ZW?t=452) | 真实标签一般用one-hot编码 | 1 |
| [0:07:58](https://www.bilibili.com/video/BV1eh411b7ZW?t=478) | 这是要学习n个linear regressions | 1 |
| [0:08:01](https://www.bilibili.com/video/BV1eh411b7ZW?t=481) | 有什么可听不懂的 都是基本数学问题 | 1 |
| [0:08:17](https://www.bilibili.com/video/BV1eh411b7ZW?t=497) | softmax的话可以用平滑标签 | 1 |
| [0:08:20](https://www.bilibili.com/video/BV1eh411b7ZW?t=500) | 还是谦虚一点好每个人都有不熟悉的地方 | 1 |
| [0:08:21](https://www.bilibili.com/video/BV1eh411b7ZW?t=501) | Loss 不考虑所有样本了嘛？ | 1 |
| [0:08:35](https://www.bilibili.com/video/BV1eh411b7ZW?t=515) | 所有的oi加起来等于1吗 | 1 |
| [0:09:34](https://www.bilibili.com/video/BV1eh411b7ZW?t=574) | focal loss | 1 |
| [0:10:09](https://www.bilibili.com/video/BV1eh411b7ZW?t=609) | 每个样本的各个类别的概率加起来为 1？ | 1 |
| [0:11:04](https://www.bilibili.com/video/BV1eh411b7ZW?t=664) | 概率化了 听懂这块对神经网络帮助特别大 | 1 |
| [0:11:06](https://www.bilibili.com/video/BV1eh411b7ZW?t=666) | 这是深度前馈神经网络里参数学习的过程吗 | 1 |
| [0:11:21](https://www.bilibili.com/video/BV1eh411b7ZW?t=681) | softmax——每一项的区间范围的(0,1)。 所有项相加的和为1。 | 1 |
| [0:11:34](https://www.bilibili.com/video/BV1eh411b7ZW?t=694) | 这不是ce loss的操作吗 | 1 |
| [0:11:49](https://www.bilibili.com/video/BV1eh411b7ZW?t=709) | 这个线性模型是怎么样定义的？ | 1 |
| [0:11:50](https://www.bilibili.com/video/BV1eh411b7ZW?t=710) | 3333333333333 | 1 |
| [0:12:00](https://www.bilibili.com/video/BV1eh411b7ZW?t=720) | 应该是因为exp取对数一系列操作之后和原来函数的趋势是一样并且一一对应的吧 | 1 |
| [0:12:12](https://www.bilibili.com/video/BV1eh411b7ZW?t=732) | 就是不同类别的分界线 | 1 |
| [0:12:33](https://www.bilibili.com/video/BV1eh411b7ZW?t=753) | 线性回归 多分类问题 用softmax | 1 |
| [0:13:10](https://www.bilibili.com/video/BV1eh411b7ZW?t=790) | 给字幕纠个错是交叉墒 | 1 |
| [0:13:11](https://www.bilibili.com/video/BV1eh411b7ZW?t=791) | 定量衡量两个概率模型是否一致 | 1 |
| [0:13:15](https://www.bilibili.com/video/BV1eh411b7ZW?t=795) | 纠正前面那个 是交叉熵 | 1 |
| [0:13:20](https://www.bilibili.com/video/BV1eh411b7ZW?t=800) | 二分类交叉熵损失函数 | 1 |
| [0:13:28](https://www.bilibili.com/video/BV1eh411b7ZW?t=808) | crossentropy | 1 |
| [0:13:42](https://www.bilibili.com/video/BV1eh411b7ZW?t=822) | “只关心正确类别，而不关心其他类别的概率”主要是交叉熵Loss起作用 | 1 |
| [0:13:43](https://www.bilibili.com/video/BV1eh411b7ZW?t=823) | 本来线性回归我是会的，可是真的没听懂。 | 1 |
| [0:13:51](https://www.bilibili.com/video/BV1eh411b7ZW?t=831) | 交叉熵损失只关心正确的那个类别的概率 | 1 |
| [0:14:00](https://www.bilibili.com/video/BV1eh411b7ZW?t=840) | 感觉像是说不需要强制让非目标以外的都趋向0 去拟合 | 1 |
| [0:14:28](https://www.bilibili.com/video/BV1eh411b7ZW?t=868) | 这样跟softmax没有关系呀 softmax会把相互间的差值拉得更大呀 | 1 |
| [0:14:43](https://www.bilibili.com/video/BV1eh411b7ZW?t=883) | 看到这个损失函数，为什么不把标签设置为一纬de？ | 1 |
| [0:14:43](https://www.bilibili.com/video/BV1eh411b7ZW?t=883) | Retinanet提出的focal loss | 1 |
| [0:14:44](https://www.bilibili.com/video/BV1eh411b7ZW?t=884) | 这里和最近邻分类器的损失函数好像 | 1 |

## 全部有实质内容的弹幕（按时间排序，共 69 条）

- `0:00:14`**Merry Christmas**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=14)
- `0:00:14`**怎么这集声音突然小了**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=14)
- `0:00:43`**还有现在看视频的啊，圣诞节快乐**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=43)
- `0:00:53`**22年5.20 快乐！**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=53)
- `0:01:04`**20260315，快乐！**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=64)
- `0:01:14`**Linear regression应用场景：股票价格预测，供应和销售量分析，医学诊断，计算时间序列相关性**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=74)
- `0:01:52`**这不就是感知机？深度神经网络**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=112)
- `0:02:30`**X should be matrix (n, p)**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=150)
- `0:02:39`**其实直接向量乘法也可以**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=159)
- `0:03:04`**刚开始是n*p，转置后才是p*n**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=184)
- `0:03:06`**这里说错了吧？长为P的向量？**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=186)
- `0:03:11`**是的，p就是一个样本特征的个数**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=191)
- `0:03:13`**就是长为n的向量，这里的是标签，只有一维，标签个数就是卖出去了所少个房子**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=193)
- `0:03:20`**n个长为P的向量有问题吗**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=200)
- `0:03:24`**没说错。标号y表示的是房价，一共有n个，所以向量y是长为n的向量**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=204)
- `0:03:43`**现在线性一般都是看r^2嘛？**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=223)
- `0:04:07`**所有样本，不是用随机梯度下降**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=247)
- `0:04:28`**那个是norm，这里是二范数**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=268)
- `0:04:36`**真实值减估计值的期望**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=276)
- `0:04:39`**好久没学过这些了，有人讲解看哭了**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=279)
- `0:04:42`**那两根竖线就是绝对值符号**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=282)
- `0:04:43`**这里取范数里面的不是一个值吗？**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=283)
- `0:04:46`**如此清楚！感谢老师！**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=286)
- `0:04:48`**说绝对值的，回去补补数学基础吧**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=288)
- `0:04:53`**说绝对值的惊艳到我了。。。。。**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=293)
- `0:05:19`**对于每个类来说，就是个线性回归任务？**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=319)
- `0:05:39`**逻辑回归大哥让我醍醐灌顶！**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=339)
- `0:06:08`**二分类问题，吴恩达老师讲过**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=368)
- `0:06:37`**softmax是多分类把，sigmoid才是逻辑回归的**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=397)
- `0:06:51`**懂了懂了，想了好久。真是每句都是精髓。**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=411)
- `0:06:56`**这不就是一层的神经网络吗，输出10个神经元**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=416)
- `0:06:58`**看w和b的獲取方法吧，現在説是感知器還是神經網絡不好説，但不是向量機**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=418)
- `0:06:59`**感觉就是个不加激活函数的单层（1层输入1层输出）神经网络**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=419)
- `0:07:03`**和最近邻分类器有什么区别**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=423)
- `0:07:10`**在每个位置列上还是转换为回归问题，只不过计算的是置信度**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=430)
- `0:07:16`**这里不明白，wi bi为什么对应不同class有多个。**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=436)
- `0:07:18`**你可以把所有带权重和偏置的全连接叫做感知机**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=438)
- `0:07:22`**one-hot encoding，独热编码。听到第二遍才反应过来**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=442)
- `0:07:32`**真实标签一般用one-hot编码**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=452)
- `0:07:58`**这是要学习n个linear regressions**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=478)
- `0:08:01`**有什么可听不懂的 都是基本数学问题**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=481)
- `0:08:17`**softmax的话可以用平滑标签**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=497)
- `0:08:20`**还是谦虚一点好每个人都有不熟悉的地方**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=500)
- `0:08:21`**Loss 不考虑所有样本了嘛？**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=501)
- `0:08:35`**所有的oi加起来等于1吗**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=515)
- `0:09:34`**focal loss**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=574)
- `0:10:09`**每个样本的各个类别的概率加起来为 1？**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=609)
- `0:11:04`**概率化了 听懂这块对神经网络帮助特别大**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=664)
- `0:11:06`**这是深度前馈神经网络里参数学习的过程吗**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=666)
- `0:11:21`**softmax——每一项的区间范围的(0,1)。 所有项相加的和为1。**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=681)
- `0:11:34`**这不是ce loss的操作吗**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=694)
- `0:11:49`**这个线性模型是怎么样定义的？**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=709)
- `0:11:50`**3333333333333**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=710)
- `0:12:00`**应该是因为exp取对数一系列操作之后和原来函数的趋势是一样并且一一对应的吧**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=720)
- `0:12:12`**就是不同类别的分界线**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=732)
- `0:12:33`**线性回归 多分类问题 用softmax**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=753)
- `0:13:10`**给字幕纠个错是交叉墒**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=790)
- `0:13:11`**定量衡量两个概率模型是否一致**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=791)
- `0:13:15`**纠正前面那个 是交叉熵**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=795)
- `0:13:20`**二分类交叉熵损失函数**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=800)
- `0:13:28`**crossentropy**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=808)
- `0:13:42`**“只关心正确类别，而不关心其他类别的概率”主要是交叉熵Loss起作用**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=822)
- `0:13:43`**本来线性回归我是会的，可是真的没听懂。**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=823)
- `0:13:51`**交叉熵损失只关心正确的那个类别的概率**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=831)
- `0:14:00`**感觉像是说不需要强制让非目标以外的都趋向0 去拟合**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=840)
- `0:14:28`**这样跟softmax没有关系呀 softmax会把相互间的差值拉得更大呀**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=868)
- `0:14:43`**看到这个损失函数，为什么不把标签设置为一纬de？**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=883)
- `0:14:43`**Retinanet提出的focal loss**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=883)
- `0:14:44`**这里和最近邻分类器的损失函数好像**　[↗](https://www.bilibili.com/video/BV1eh411b7ZW?t=884)
