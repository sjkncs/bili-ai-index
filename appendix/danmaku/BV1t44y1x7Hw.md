# 弹幕讨论 · 2.4 特征工程【斯坦福21秋季：实用机器学习中文版】

> 视频：[BV1t44y1x7Hw](https://www.bilibili.com/video/BV1t44y1x7Hw)　时长 0:19:59　弹幕总数 **191**　有实质内容 **78** 条　重点标记 **78** 条
>
> 来源：B 站 **跟李沐学AI** 的该集弹幕　快照：**2026-10-12**

## 口径说明（务必先读）

**这些内容全部是观众在视频上发的弹幕，不是经过核实的结论。**

- 其中有价值的：概念解释、类比、勘误、学习方法、延伸阅读线索。
- **也可能有错误的**：弹幕是个人理解，未经作者或权威确认。
  **本页不为其正确性背书，请勿直接引用为事实。**
- 每条带时间戳，点击可跳回视频对应位置自行核对。
- 筛选口径：保留长度 ≥ 10 字符、且不含纯感叹/打卡类噪声的弹幕，共 78 条（占该集弹幕 191 条的 40.8%）；同一句话被多人发送只保留一条并标注发送次数。
- 「重点」标记由关键词打分得出（技术词 + 解释性措辞 + 长度 + 多人重复），共 78 条；**它是启发式排序，不代表正确性，也不代表其余条目无价值。**

## 重点条目

| 时间 | 弹幕 | 发送次数 |
|---|---|---:|
| [0:00:04](https://www.bilibili.com/video/BV1t44y1x7Hw?t=4) | 333333333333333333333333333333333333333333333333333333333333333333333333333333333333333333333333 | 1 |
| [0:00:34](https://www.bilibili.com/video/BV1t44y1x7Hw?t=34) | 机器学习试图摆脱先验知识，但是就目前而已做不到 | 1 |
| [0:01:45](https://www.bilibili.com/video/BV1t44y1x7Hw?t=105) | 听李老师讲讲ML的历史和圈里的八卦也挺有趣的 | 1 |
| [0:02:26](https://www.bilibili.com/video/BV1t44y1x7Hw?t=146) | 2022年5月11日安徽安庆 | 1 |
| [0:02:54](https://www.bilibili.com/video/BV1t44y1x7Hw?t=174) | 2022。10。22 | 1 |
| [0:03:32](https://www.bilibili.com/video/BV1t44y1x7Hw?t=212) | 这里也产生了可解释性的问题，人工特征工程可解释，交给神经网络就难以解释了 | 1 |
| [0:03:47](https://www.bilibili.com/video/BV1t44y1x7Hw?t=227) | 那特征工程不也费人力资源吗 | 1 |
| [0:03:48](https://www.bilibili.com/video/BV1t44y1x7Hw?t=228) | 费数据是什么概念？有点不理解 | 1 |
| [0:03:49](https://www.bilibili.com/video/BV1t44y1x7Hw?t=229) | 前面的，费数据就是说神经网络需要大量的数据去训练啊 | 1 |
| [0:03:50](https://www.bilibili.com/video/BV1t44y1x7Hw?t=230) | 要学习特征需要很多数据吧 | 1 |
| [0:03:52](https://www.bilibili.com/video/BV1t44y1x7Hw?t=232) | 费数据就是需要的数据样本量很大，数万数百万甚至更多 | 1 |
| [0:03:53](https://www.bilibili.com/video/BV1t44y1x7Hw?t=233) | 费数据就是需要很大的数据集吧 | 1 |
| [0:04:01](https://www.bilibili.com/video/BV1t44y1x7Hw?t=241) | 大的数据集训练更深的模型得到更高的精度 | 1 |
| [0:04:12](https://www.bilibili.com/video/BV1t44y1x7Hw?t=252) | 意思就是需要大量数据 | 1 |
| [0:04:48](https://www.bilibili.com/video/BV1t44y1x7Hw?t=288) | 这里我有一个问题 使用one-hot表示这种带有次序关系的标记是不是不太合适 | 1 |
| [0:04:49](https://www.bilibili.com/video/BV1t44y1x7Hw?t=289) | one-hot encoding | 1 |
| [0:05:58](https://www.bilibili.com/video/BV1t44y1x7Hw?t=358) | 求解答：这里的一列指什么？如图是指[cat]、[dog]还是[[cat],[dog]]? | 1 |
| [0:05:59](https://www.bilibili.com/video/BV1t44y1x7Hw?t=359) | 我理解的是type有五类值，那么新建五个列，列名为type 的五类值，列值为0，1，type列对应的哪类，那么对应的那列就是1，其余为0 | 1 |
| [0:05:59](https://www.bilibili.com/video/BV1t44y1x7Hw?t=359) | 假如有一列特征，特征名叫动物，这一列有4个动物（猫，狗，鱼，鸟）。独热编码就是把这一列变成4列（动物-猫，动物-狗，动物-鱼，动物-鸟），原来那一列动物列中的猫就变为4列中的（1，0，0，0）以此类推 | 1 |
| [0:06:02](https://www.bilibili.com/video/BV1t44y1x7Hw?t=362) | 指[cat],[dog] | 1 |
| [0:06:52](https://www.bilibili.com/video/BV1t44y1x7Hw?t=412) | 不太能理解这里“那一列有很多东西则可能得到很多类”，有没有大佬能举个生动的例子 | 1 |
| [0:06:53](https://www.bilibili.com/video/BV1t44y1x7Hw?t=413) | 向量计算、线性代数：数学之美 | 1 |
| [0:06:56](https://www.bilibili.com/video/BV1t44y1x7Hw?t=416) | 就是类别型变量取值过多，独热编码后得到稀疏矩阵 | 1 |
| [0:06:58](https://www.bilibili.com/video/BV1t44y1x7Hw?t=418) | 可以把少量类归为一类，否则类太多，而且某些类数量分布少一般来说没什么信息 | 1 |
| [0:06:59](https://www.bilibili.com/video/BV1t44y1x7Hw?t=419) | 个人觉得，这里有点像独热编码。一列里面，有不同的属性。比如房子的单价，地段，大小 | 1 |
| [0:06:59](https://www.bilibili.com/video/BV1t44y1x7Hw?t=419) | 比如cat是列“c”为1，其他25列为0 | 1 |
| [0:06:59](https://www.bilibili.com/video/BV1t44y1x7Hw?t=419) | 一个英语单词，如果按照首字母分就会分出26列，对每一个单词都有：某一列为1其他列为0 | 1 |
| [0:07:01](https://www.bilibili.com/video/BV1t44y1x7Hw?t=421) | 把原来某个特征里的N个类别转换成N个列，哪个列的值为1就表示之前是哪个类别的数据 | 1 |
| [0:07:01](https://www.bilibili.com/video/BV1t44y1x7Hw?t=421) | 比如前面卖房子的有1800个类 | 1 |
| [0:07:03](https://www.bilibili.com/video/BV1t44y1x7Hw?t=423) | 这个想法在之前的视频里边讲有 | 1 |
| [0:07:03](https://www.bilibili.com/video/BV1t44y1x7Hw?t=423) | 前面的说的没有问题，将某个特征里的n个值转换为n个列，那么很明显该列只会有一个1，剩下的全为0. | 1 |
| [0:07:34](https://www.bilibili.com/video/BV1t44y1x7Hw?t=454) | 开集学习 Open Set | 1 |
| [0:07:35](https://www.bilibili.com/video/BV1t44y1x7Hw?t=455) | 不如叫other，更符合直觉一点 | 1 |
| [0:08:17](https://www.bilibili.com/video/BV1t44y1x7Hw?t=497) | 也可以计算时间值到观测时点的长度 | 1 |
| [0:08:20](https://www.bilibili.com/video/BV1t44y1x7Hw?t=500) | 应该是“一年里的第几天” | 1 |
| [0:08:28](https://www.bilibili.com/video/BV1t44y1x7Hw?t=508) | 这种time dummy以前都是econ里常用的，如今econ已经成为垃圾专业了。哎哎哎哎 | 1 |
| [0:09:36](https://www.bilibili.com/video/BV1t44y1x7Hw?t=576) | 我国节假日是拆东墙补西墙拼凑的 | 1 |
| [0:09:36](https://www.bilibili.com/video/BV1t44y1x7Hw?t=576) | 可以对日期多加几个特征，标记是否调休、节假日假期、节假日长度 | 1 |
| [0:09:41](https://www.bilibili.com/video/BV1t44y1x7Hw?t=581) | 有没有特征工程师  哈哈 | 1 |
| [0:09:42](https://www.bilibili.com/video/BV1t44y1x7Hw?t=582) | 可以添加特征，说明每年这个是长假或者短假 | 1 |
| [0:09:43](https://www.bilibili.com/video/BV1t44y1x7Hw?t=583) | 这些个特征对我国节假日还真不怎么好用，哈哈哈哈哈 | 1 |
| [0:10:02](https://www.bilibili.com/video/BV1t44y1x7Hw?t=602) | 为什么我这样标了，就一定有用，数学证明太难了 | 1 |
| [0:10:07](https://www.bilibili.com/video/BV1t44y1x7Hw?t=607) | Dummy Variable | 1 |
| [0:10:20](https://www.bilibili.com/video/BV1t44y1x7Hw?t=620) | 组合的话原来特征就没用了吧 | 1 |
| [0:10:23](https://www.bilibili.com/video/BV1t44y1x7Hw?t=623) | 学校推迟假期，说后面补的。这特么新学期都要开学了。还欠着 | 1 |
| [0:11:01](https://www.bilibili.com/video/BV1t44y1x7Hw?t=661) | female dog | 1 |
| [0:11:20](https://www.bilibili.com/video/BV1t44y1x7Hw?t=680) | 这么做意义何在啊，计算机不应该自动学习到2个特征之间的关系吗 | 1 |
| [0:11:36](https://www.bilibili.com/video/BV1t44y1x7Hw?t=696) | 笛卡儿积哈哈哈哈哈哈 | 1 |
| [0:11:47](https://www.bilibili.com/video/BV1t44y1x7Hw?t=707) | 笛卡尔为什么不叫卡笛尔 | 1 |
| [0:11:57](https://www.bilibili.com/video/BV1t44y1x7Hw?t=717) | Outer  join | 1 |
| [0:11:57](https://www.bilibili.com/video/BV1t44y1x7Hw?t=717) | 因为笛卡尔 是Descartes | 1 |
| [0:12:09](https://www.bilibili.com/video/BV1t44y1x7Hw?t=729) | 前面说的是深度学习的情况，深度学习才能自动抽取特征 | 1 |
| [0:12:25](https://www.bilibili.com/video/BV1t44y1x7Hw?t=745) | 线性代数的重要性体现出来了 | 1 |
| [0:12:48](https://www.bilibili.com/video/BV1t44y1x7Hw?t=768) | graph data怎么办？ | 1 |
| [0:12:57](https://www.bilibili.com/video/BV1t44y1x7Hw?t=777) | 拉普拉斯矩阵可以表示图 | 1 |
| [0:13:50](https://www.bilibili.com/video/BV1t44y1x7Hw?t=830) | dinosaur~哦~ | 1 |
| [0:14:36](https://www.bilibili.com/video/BV1t44y1x7Hw?t=876) | 这里才21年，居然就已经拿gpt3来举例了 | 1 |
| [0:14:40](https://www.bilibili.com/video/BV1t44y1x7Hw?t=880) | levinstein distance | 1 |
| [0:14:54](https://www.bilibili.com/video/BV1t44y1x7Hw?t=894) | 有两种模型，面试考过 | 1 |
| [0:15:32](https://www.bilibili.com/video/BV1t44y1x7Hw?t=932) | bert不也要先embedding和位置编码 | 1 |
| [0:15:54](https://www.bilibili.com/video/BV1t44y1x7Hw?t=954) | 那门课学了，但是对transformer确实还是不太懂。。。。。。 | 1 |
| [0:15:55](https://www.bilibili.com/video/BV1t44y1x7Hw?t=955) | GPT 返回词向量？ | 1 |
| [0:15:57](https://www.bilibili.com/video/BV1t44y1x7Hw?t=957) | swin-transfromer | 1 |
| [0:16:02](https://www.bilibili.com/video/BV1t44y1x7Hw?t=962) | 2023chatgpt占领地球啦 | 1 |
| [0:16:08](https://www.bilibili.com/video/BV1t44y1x7Hw?t=968) | 2023/11/21 奥特曼加入微软了 | 1 |
| [0:16:10](https://www.bilibili.com/video/BV1t44y1x7Hw?t=970) | 简单介绍一下 指精读八十分钟 | 1 |
| [0:16:24](https://www.bilibili.com/video/BV1t44y1x7Hw?t=984) | 2025deepseek打败openai | 1 |
| [0:16:57](https://www.bilibili.com/video/BV1t44y1x7Hw?t=1017) | 贵不是他的问题，是我的问题 | 1 |
| [0:17:03](https://www.bilibili.com/video/BV1t44y1x7Hw?t=1023) | SIFT当年被拒了很多次 | 1 |
| [0:17:31](https://www.bilibili.com/video/BV1t44y1x7Hw?t=1051) | 冻结深度神经网络，训练分类器 | 1 |
| [0:17:58](https://www.bilibili.com/video/BV1t44y1x7Hw?t=1078) | 预训练模型的features怎么来呢 | 1 |
| [0:18:00](https://www.bilibili.com/video/BV1t44y1x7Hw?t=1080) | 也就是说，现在的特征都是用神经网络来做啦 | 1 |
| [0:18:14](https://www.bilibili.com/video/BV1t44y1x7Hw?t=1094) | 神经网络训练特征向量 | 1 |
| [0:18:23](https://www.bilibili.com/video/BV1t44y1x7Hw?t=1103) | 预训练好的模型怎么找？比如我想找一个对鸟做预训练好的ResNet18 模型，从哪里找呢 | 1 |
| [0:18:42](https://www.bilibili.com/video/BV1t44y1x7Hw?t=1122) | 学术上都是用深度学习，但是现在企业还是用的大量的table数据，机器学习还是主流 | 1 |
| [0:18:49](https://www.bilibili.com/video/BV1t44y1x7Hw?t=1129) | 特征似乎既重要又没有固定套路 | 1 |
| [0:19:24](https://www.bilibili.com/video/BV1t44y1x7Hw?t=1164) | 自己从头训练？不依赖现有的？ | 1 |
| [0:19:44](https://www.bilibili.com/video/BV1t44y1x7Hw?t=1184) | 谢谢老师，大家加油！ | 2 |

## 全部有实质内容的弹幕（按时间排序，共 78 条）

- `0:00:04`**333333333333333333333333333333333333333333333333333333333333333333333333333333333333333333333333**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=4)
- `0:00:34`**机器学习试图摆脱先验知识，但是就目前而已做不到**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=34)
- `0:01:45`**听李老师讲讲ML的历史和圈里的八卦也挺有趣的**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=105)
- `0:02:26`**2022年5月11日安徽安庆**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=146)
- `0:02:54`**2022。10。22**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=174)
- `0:03:32`**这里也产生了可解释性的问题，人工特征工程可解释，交给神经网络就难以解释了**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=212)
- `0:03:47`**那特征工程不也费人力资源吗**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=227)
- `0:03:48`**费数据是什么概念？有点不理解**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=228)
- `0:03:49`**前面的，费数据就是说神经网络需要大量的数据去训练啊**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=229)
- `0:03:50`**要学习特征需要很多数据吧**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=230)
- `0:03:52`**费数据就是需要的数据样本量很大，数万数百万甚至更多**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=232)
- `0:03:53`**费数据就是需要很大的数据集吧**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=233)
- `0:04:01`**大的数据集训练更深的模型得到更高的精度**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=241)
- `0:04:12`**意思就是需要大量数据**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=252)
- `0:04:48`**这里我有一个问题 使用one-hot表示这种带有次序关系的标记是不是不太合适**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=288)
- `0:04:49`**one-hot encoding**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=289)
- `0:05:58`**求解答：这里的一列指什么？如图是指[cat]、[dog]还是[[cat],[dog]]?**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=358)
- `0:05:59`**我理解的是type有五类值，那么新建五个列，列名为type 的五类值，列值为0，1，type列对应的哪类，那么对应的那列就是1，其余为0**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=359)
- `0:05:59`**假如有一列特征，特征名叫动物，这一列有4个动物（猫，狗，鱼，鸟）。独热编码就是把这一列变成4列（动物-猫，动物-狗，动物-鱼，动物-鸟），原来那一列动物列中的猫就变为4列中的（1，0，0，0）以此类推**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=359)
- `0:06:02`**指[cat],[dog]**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=362)
- `0:06:52`**不太能理解这里“那一列有很多东西则可能得到很多类”，有没有大佬能举个生动的例子**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=412)
- `0:06:53`**向量计算、线性代数：数学之美**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=413)
- `0:06:56`**就是类别型变量取值过多，独热编码后得到稀疏矩阵**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=416)
- `0:06:58`**可以把少量类归为一类，否则类太多，而且某些类数量分布少一般来说没什么信息**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=418)
- `0:06:59`**个人觉得，这里有点像独热编码。一列里面，有不同的属性。比如房子的单价，地段，大小**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=419)
- `0:06:59`**比如cat是列“c”为1，其他25列为0**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=419)
- `0:06:59`**一个英语单词，如果按照首字母分就会分出26列，对每一个单词都有：某一列为1其他列为0**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=419)
- `0:07:01`**把原来某个特征里的N个类别转换成N个列，哪个列的值为1就表示之前是哪个类别的数据**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=421)
- `0:07:01`**比如前面卖房子的有1800个类**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=421)
- `0:07:03`**这个想法在之前的视频里边讲有**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=423)
- `0:07:03`**前面的说的没有问题，将某个特征里的n个值转换为n个列，那么很明显该列只会有一个1，剩下的全为0.**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=423)
- `0:07:34`**开集学习 Open Set**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=454)
- `0:07:35`**不如叫other，更符合直觉一点**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=455)
- `0:08:17`**也可以计算时间值到观测时点的长度**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=497)
- `0:08:20`**应该是“一年里的第几天”**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=500)
- `0:08:28`**这种time dummy以前都是econ里常用的，如今econ已经成为垃圾专业了。哎哎哎哎**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=508)
- `0:09:36`**我国节假日是拆东墙补西墙拼凑的**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=576)
- `0:09:36`**可以对日期多加几个特征，标记是否调休、节假日假期、节假日长度**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=576)
- `0:09:41`**有没有特征工程师  哈哈**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=581)
- `0:09:42`**可以添加特征，说明每年这个是长假或者短假**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=582)
- `0:09:43`**这些个特征对我国节假日还真不怎么好用，哈哈哈哈哈**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=583)
- `0:10:02`**为什么我这样标了，就一定有用，数学证明太难了**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=602)
- `0:10:07`**Dummy Variable**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=607)
- `0:10:20`**组合的话原来特征就没用了吧**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=620)
- `0:10:23`**学校推迟假期，说后面补的。这特么新学期都要开学了。还欠着**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=623)
- `0:11:01`**female dog**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=661)
- `0:11:20`**这么做意义何在啊，计算机不应该自动学习到2个特征之间的关系吗**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=680)
- `0:11:36`**笛卡儿积哈哈哈哈哈哈**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=696)
- `0:11:47`**笛卡尔为什么不叫卡笛尔**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=707)
- `0:11:57`**Outer  join**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=717)
- `0:11:57`**因为笛卡尔 是Descartes**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=717)
- `0:12:09`**前面说的是深度学习的情况，深度学习才能自动抽取特征**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=729)
- `0:12:25`**线性代数的重要性体现出来了**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=745)
- `0:12:48`**graph data怎么办？**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=768)
- `0:12:57`**拉普拉斯矩阵可以表示图**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=777)
- `0:13:50`**dinosaur~哦~**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=830)
- `0:14:36`**这里才21年，居然就已经拿gpt3来举例了**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=876)
- `0:14:40`**levinstein distance**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=880)
- `0:14:54`**有两种模型，面试考过**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=894)
- `0:15:32`**bert不也要先embedding和位置编码**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=932)
- `0:15:54`**那门课学了，但是对transformer确实还是不太懂。。。。。。**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=954)
- `0:15:55`**GPT 返回词向量？**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=955)
- `0:15:57`**swin-transfromer**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=957)
- `0:16:02`**2023chatgpt占领地球啦**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=962)
- `0:16:08`**2023/11/21 奥特曼加入微软了**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=968)
- `0:16:10`**简单介绍一下 指精读八十分钟**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=970)
- `0:16:24`**2025deepseek打败openai**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=984)
- `0:16:57`**贵不是他的问题，是我的问题**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=1017)
- `0:17:03`**SIFT当年被拒了很多次**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=1023)
- `0:17:31`**冻结深度神经网络，训练分类器**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=1051)
- `0:17:58`**预训练模型的features怎么来呢**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=1078)
- `0:18:00`**也就是说，现在的特征都是用神经网络来做啦**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=1080)
- `0:18:14`**神经网络训练特征向量**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=1094)
- `0:18:23`**预训练好的模型怎么找？比如我想找一个对鸟做预训练好的ResNet18 模型，从哪里找呢**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=1103)
- `0:18:42`**学术上都是用深度学习，但是现在企业还是用的大量的table数据，机器学习还是主流**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=1122)
- `0:18:49`**特征似乎既重要又没有固定套路**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=1129)
- `0:19:24`**自己从头训练？不依赖现有的？**　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=1164)
- `0:19:44`**谢谢老师，大家加油！**（×2）　[↗](https://www.bilibili.com/video/BV1t44y1x7Hw?t=1184)
