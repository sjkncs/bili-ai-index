# 弹幕讨论 · Neural Corpus Indexer 文档检索【论文精读·47】

> 视频：[BV1Se411w7Sn](https://www.bilibili.com/video/BV1Se411w7Sn)　时长 0:55:47　弹幕总数 **199**　有实质内容 **76** 条　重点标记 **76** 条
>
> 来源：B 站 **跟李沐学AI** 的该集弹幕　快照：**2026-10-14**

## 口径说明（务必先读）

**这些内容全部是观众在视频上发的弹幕，不是经过核实的结论。**

- 其中有价值的：概念解释、类比、勘误、学习方法、延伸阅读线索。
- **也可能有错误的**：弹幕是个人理解，未经作者或权威确认。
  **本页不为其正确性背书，请勿直接引用为事实。**
- 每条带时间戳，点击可跳回视频对应位置自行核对。
- 筛选口径：保留长度 ≥ 10 字符、且不含纯感叹/打卡类噪声的弹幕，共 76 条（占该集弹幕 199 条的 38.2%）；同一句话被多人发送只保留一条并标注发送次数。
- 「重点」标记由关键词打分得出（技术词 + 解释性措辞 + 长度 + 多人重复），共 76 条；**它是启发式排序，不代表正确性，也不代表其余条目无价值。**

## 重点条目

| 时间 | 弹幕 | 发送次数 |
|---|---|---:|
| [0:00:36](https://www.bilibili.com/video/BV1Se411w7Sn?t=36) | 这个错误我曾经也犯过，被导师骂个半死 | 1 |
| [0:00:37](https://www.bilibili.com/video/BV1Se411w7Sn?t=37) | 搞混一點點的影響已經很大了 | 1 |
| [0:01:07](https://www.bilibili.com/video/BV1Se411w7Sn?t=67) | 不是纯纯纯八卦？？？？ | 1 |
| [0:01:27](https://www.bilibili.com/video/BV1Se411w7Sn?t=87) | 不是说bug啊，测试集数据混到训练里，不百分百故意的吗？请给一个不是故意的场景 | 1 |
| [0:01:43](https://www.bilibili.com/video/BV1Se411w7Sn?t=103) | 可惜现在知乎没有匿名了 | 1 |
| [0:01:52](https://www.bilibili.com/video/BV1Se411w7Sn?t=112) | 看到大佬也这么说我就放心了 | 1 |
| [0:02:33](https://www.bilibili.com/video/BV1Se411w7Sn?t=153) | wsdm一般发音按wisdom念 | 1 |
| [0:03:05](https://www.bilibili.com/video/BV1Se411w7Sn?t=185) | 如果我是审稿人遇到这种情况我就选择第二种 | 1 |
| [0:03:17](https://www.bilibili.com/video/BV1Se411w7Sn?t=197) | 所以你永远不会是审稿人 | 1 |
| [0:07:53](https://www.bilibili.com/video/BV1Se411w7Sn?t=473) | 话说第二版书出了没？ | 1 |
| [0:08:56](https://www.bilibili.com/video/BV1Se411w7Sn?t=536) | 从文档里检索词，变成根据词列出相关文档 | 1 |
| [0:09:43](https://www.bilibili.com/video/BV1Se411w7Sn?t=583) | 出现attention is all you need | 1 |
| [0:10:34](https://www.bilibili.com/video/BV1Se411w7Sn?t=634) | sentence transformers | 1 |
| [0:11:11](https://www.bilibili.com/video/BV1Se411w7Sn?t=671) | 一直有一个问题，cos最小值不是-1么？ | 1 |
| [0:11:20](https://www.bilibili.com/video/BV1Se411w7Sn?t=680) | Contrastive Loss | 1 |
| [0:12:09](https://www.bilibili.com/video/BV1Se411w7Sn?t=729) | milvus 的向量检索好像就是在同一个簇里检索 | 1 |
| [0:15:32](https://www.bilibili.com/video/BV1Se411w7Sn?t=932) | hhhh我写论文日常 | 1 |
| [0:19:21](https://www.bilibili.com/video/BV1Se411w7Sn?t=1161) | 每次增加文档的话岂不是要重新训练模型 | 1 |
| [0:19:56](https://www.bilibili.com/video/BV1Se411w7Sn?t=1196) | 没明白除了有个ID外，跟twin tower有啥本质区别 | 1 |
| [0:20:05](https://www.bilibili.com/video/BV1Se411w7Sn?t=1205) | 这个好像只有一个模型 | 1 |
| [0:20:11](https://www.bilibili.com/video/BV1Se411w7Sn?t=1211) | 为啥要放ID在里面，用ID有什么用 | 1 |
| [0:20:11](https://www.bilibili.com/video/BV1Se411w7Sn?t=1211) | two tower是要使用两个不同的神经网络，这里让NCI同时学习到了query和doc的文本信息，只用了一个神经网络 | 1 |
| [0:20:13](https://www.bilibili.com/video/BV1Se411w7Sn?t=1213) | 区别就是NCI只有一个输入，双塔有俩输入 | 1 |
| [0:20:16](https://www.bilibili.com/video/BV1Se411w7Sn?t=1216) | 实际上现在 embedding query 和 doc 也用的一个模型，不是 two tower | 1 |
| [0:20:17](https://www.bilibili.com/video/BV1Se411w7Sn?t=1217) | 这有decoding啊 | 1 |
| [0:20:22](https://www.bilibili.com/video/BV1Se411w7Sn?t=1222) | 这里不涉及Contrastive loss，不用双塔 | 1 |
| [0:21:10](https://www.bilibili.com/video/BV1Se411w7Sn?t=1270) | 因为本质一毛一样哈哈哈 | 1 |
| [0:21:40](https://www.bilibili.com/video/BV1Se411w7Sn?t=1300) | 用什么vector做聚类？ | 1 |
| [0:22:22](https://www.bilibili.com/video/BV1Se411w7Sn?t=1342) | 23333，作者一看就国人 | 1 |
| [0:22:40](https://www.bilibili.com/video/BV1Se411w7Sn?t=1360) | 这个图和讲解都很清晰 | 1 |
| [0:23:32](https://www.bilibili.com/video/BV1Se411w7Sn?t=1412) | word2vec预训练就有层次softmax | 1 |
| [0:23:33](https://www.bilibili.com/video/BV1Se411w7Sn?t=1413) | k-mean 需要能计算距离(相似度), 文档的距离怎么定义? | 1 |
| [0:23:49](https://www.bilibili.com/video/BV1Se411w7Sn?t=1429) | 海明距离、文本编辑距离 | 1 |
| [0:24:11](https://www.bilibili.com/video/BV1Se411w7Sn?t=1451) | docid 2越多的，抄袭、灌水越多 | 1 |
| [0:24:35](https://www.bilibili.com/video/BV1Se411w7Sn?t=1475) | 这个妙啊，可惜不是原创… | 1 |
| [0:24:59](https://www.bilibili.com/video/BV1Se411w7Sn?t=1499) | Seq2seq 来生成id 有点妙 | 1 |
| [0:25:04](https://www.bilibili.com/video/BV1Se411w7Sn?t=1504) | 和 HNSW 算法有点像啊 | 1 |
| [0:25:06](https://www.bilibili.com/video/BV1Se411w7Sn?t=1506) | 用seq2seq是想不到的 | 1 |
| [0:25:12](https://www.bilibili.com/video/BV1Se411w7Sn?t=1512) | 那怎么保证不会生成没有的docid，还是说还是去改变分类label | 1 |
| [0:26:47](https://www.bilibili.com/video/BV1Se411w7Sn?t=1607) | dosample=true | 1 |
| [0:27:10](https://www.bilibili.com/video/BV1Se411w7Sn?t=1630) | 求指路哪里讲的beam search | 1 |
| [0:27:14](https://www.bilibili.com/video/BV1Se411w7Sn?t=1634) | 在动手学习深度学习课程中讲过beam search | 1 |
| [0:27:56](https://www.bilibili.com/video/BV1Se411w7Sn?t=1676) | 这里的t5怎么训练的？ | 1 |
| [0:28:03](https://www.bilibili.com/video/BV1Se411w7Sn?t=1683) | t5你如果说的是那个transformer的话，他可以是直接拿现成的训练好的模型。也可以你自己找一些文档query数据集训练一个 | 1 |
| [0:28:05](https://www.bilibili.com/video/BV1Se411w7Sn?t=1685) | t5是预训练模型  跟bert那种训练好的一样 | 1 |
| [0:30:14](https://www.bilibili.com/video/BV1Se411w7Sn?t=1814) | 就是position embbeding concate进input了呗 | 1 |
| [0:30:28](https://www.bilibili.com/video/BV1Se411w7Sn?t=1828) | 我个人的理解是原来的每一步输出都是按照一个相同的矩阵来和当前步的h进行相乘然后取softmax，但是作者现在想换成按照每一步都有一个独立的矩阵相乘取softmax，不知道对不对 | 1 |
| [0:31:21](https://www.bilibili.com/video/BV1Se411w7Sn?t=1881) | 这个是原创，然而纯trick | 1 |
| [0:31:37](https://www.bilibili.com/video/BV1Se411w7Sn?t=1897) | 有种写专利硬凑的感觉。。 | 1 |
| [0:31:38](https://www.bilibili.com/video/BV1Se411w7Sn?t=1898) | 发现手里的论文的图，跟这个图不一样，手里的论文的hi是Ei? | 1 |
| [0:31:41](https://www.bilibili.com/video/BV1Se411w7Sn?t=1901) | 寫過類似的東西 有用 提升兩個點 | 1 |
| [0:31:49](https://www.bilibili.com/video/BV1Se411w7Sn?t=1909) | 这幅图说实话做的很糟糕，太容易产生歧义了。作者完全可以只展示做一次预测的过程 | 1 |
| [0:32:22](https://www.bilibili.com/video/BV1Se411w7Sn?t=1942) | r- dropout | 1 |
| [0:32:27](https://www.bilibili.com/video/BV1Se411w7Sn?t=1947) | 除了r drop，simcse也类似 | 1 |
| [0:32:34](https://www.bilibili.com/video/BV1Se411w7Sn?t=1954) | simcse也是这样的 | 1 |
| [0:32:43](https://www.bilibili.com/video/BV1Se411w7Sn?t=1963) | si m c l r | 1 |
| [0:36:37](https://www.bilibili.com/video/BV1Se411w7Sn?t=2197) | 改进基本纯trick，reg函数其实就是rdrop | 1 |
| [0:38:21](https://www.bilibili.com/video/BV1Se411w7Sn?t=2301) | QA对语义要求更高一些吧？ | 1 |
| [0:38:25](https://www.bilibili.com/video/BV1Se411w7Sn?t=2305) | 是的 QA不要求term精确匹配 | 1 |
| [0:40:18](https://www.bilibili.com/video/BV1Se411w7Sn?t=2418) | 这块生成器怎么训练的？ | 1 |
| [0:40:20](https://www.bilibili.com/video/BV1Se411w7Sn?t=2420) | 预训练的，前面说过了吧 | 1 |
| [0:40:26](https://www.bilibili.com/video/BV1Se411w7Sn?t=2426) | 这个实验居然在最新版已经去掉了。不显示这个Query生成的效果了 | 1 |
| [0:44:06](https://www.bilibili.com/video/BV1Se411w7Sn?t=2646) | 猜的没错，那个开源bm25实现确实非常烂… | 1 |
| [0:44:37](https://www.bilibili.com/video/BV1Se411w7Sn?t=2677) | 新来的文档重新训，太伤了 | 1 |
| [0:44:39](https://www.bilibili.com/video/BV1Se411w7Sn?t=2679) | 这个还不如twin tower呢 | 1 |
| [0:45:59](https://www.bilibili.com/video/BV1Se411w7Sn?t=2759) | DSI还不如BM25？ | 1 |
| [0:46:44](https://www.bilibili.com/video/BV1Se411w7Sn?t=2804) | 这里我也打开openrevirew网站了，搜到了这篇论文，为什么我看不到comments呀。 | 1 |
| [0:47:20](https://www.bilibili.com/video/BV1Se411w7Sn?t=2840) | 有点像prompt，或者COT？ | 1 |
| [0:48:23](https://www.bilibili.com/video/BV1Se411w7Sn?t=2903) | 直接加序号虽然提升了了性能，但是不是过拟合了，真实场景的序号不同吧？ | 1 |
| [0:48:59](https://www.bilibili.com/video/BV1Se411w7Sn?t=2939) | 最后做了分类相当于计算了query跟所有doc的距离，对性能破坏太大了，还得ann | 1 |
| [0:51:54](https://www.bilibili.com/video/BV1Se411w7Sn?t=3114) | 可见ms团队这个工作氛围略好大喜功 | 1 |
| [0:52:02](https://www.bilibili.com/video/BV1Se411w7Sn?t=3122) | 可能确实那时他们效果确实够好，也就想吹一吹 | 1 |
| [0:52:18](https://www.bilibili.com/video/BV1Se411w7Sn?t=3138) | 这样写可能是为了唬住审稿人 文章好中 | 1 |
| [0:52:36](https://www.bilibili.com/video/BV1Se411w7Sn?t=3156) | 有可能是和DSI时间差不多，但是DSI先挂Arxiv了 | 1 |
| [0:52:42](https://www.bilibili.com/video/BV1Se411w7Sn?t=3162) | 感觉这个论文像是比DSI挂ArXiv慢了一步，所以导致里面很多话都说的很满 | 1 |
| [0:53:05](https://www.bilibili.com/video/BV1Se411w7Sn?t=3185) | 怎么听解读感觉dsi更经典啊 | 1 |

## 全部有实质内容的弹幕（按时间排序，共 76 条）

- `0:00:36`**这个错误我曾经也犯过，被导师骂个半死**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=36)
- `0:00:37`**搞混一點點的影響已經很大了**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=37)
- `0:01:07`**不是纯纯纯八卦？？？？**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=67)
- `0:01:27`**不是说bug啊，测试集数据混到训练里，不百分百故意的吗？请给一个不是故意的场景**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=87)
- `0:01:43`**可惜现在知乎没有匿名了**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=103)
- `0:01:52`**看到大佬也这么说我就放心了**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=112)
- `0:02:33`**wsdm一般发音按wisdom念**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=153)
- `0:03:05`**如果我是审稿人遇到这种情况我就选择第二种**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=185)
- `0:03:17`**所以你永远不会是审稿人**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=197)
- `0:07:53`**话说第二版书出了没？**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=473)
- `0:08:56`**从文档里检索词，变成根据词列出相关文档**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=536)
- `0:09:43`**出现attention is all you need**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=583)
- `0:10:34`**sentence transformers**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=634)
- `0:11:11`**一直有一个问题，cos最小值不是-1么？**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=671)
- `0:11:20`**Contrastive Loss**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=680)
- `0:12:09`**milvus 的向量检索好像就是在同一个簇里检索**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=729)
- `0:15:32`**hhhh我写论文日常**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=932)
- `0:19:21`**每次增加文档的话岂不是要重新训练模型**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=1161)
- `0:19:56`**没明白除了有个ID外，跟twin tower有啥本质区别**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=1196)
- `0:20:05`**这个好像只有一个模型**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=1205)
- `0:20:11`**为啥要放ID在里面，用ID有什么用**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=1211)
- `0:20:11`**two tower是要使用两个不同的神经网络，这里让NCI同时学习到了query和doc的文本信息，只用了一个神经网络**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=1211)
- `0:20:13`**区别就是NCI只有一个输入，双塔有俩输入**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=1213)
- `0:20:16`**实际上现在 embedding query 和 doc 也用的一个模型，不是 two tower**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=1216)
- `0:20:17`**这有decoding啊**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=1217)
- `0:20:22`**这里不涉及Contrastive loss，不用双塔**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=1222)
- `0:21:10`**因为本质一毛一样哈哈哈**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=1270)
- `0:21:40`**用什么vector做聚类？**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=1300)
- `0:22:22`**23333，作者一看就国人**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=1342)
- `0:22:40`**这个图和讲解都很清晰**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=1360)
- `0:23:32`**word2vec预训练就有层次softmax**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=1412)
- `0:23:33`**k-mean 需要能计算距离(相似度), 文档的距离怎么定义?**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=1413)
- `0:23:49`**海明距离、文本编辑距离**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=1429)
- `0:24:11`**docid 2越多的，抄袭、灌水越多**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=1451)
- `0:24:35`**这个妙啊，可惜不是原创…**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=1475)
- `0:24:59`**Seq2seq 来生成id 有点妙**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=1499)
- `0:25:04`**和 HNSW 算法有点像啊**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=1504)
- `0:25:06`**用seq2seq是想不到的**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=1506)
- `0:25:12`**那怎么保证不会生成没有的docid，还是说还是去改变分类label**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=1512)
- `0:26:47`**dosample=true**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=1607)
- `0:27:10`**求指路哪里讲的beam search**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=1630)
- `0:27:14`**在动手学习深度学习课程中讲过beam search**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=1634)
- `0:27:56`**这里的t5怎么训练的？**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=1676)
- `0:28:03`**t5你如果说的是那个transformer的话，他可以是直接拿现成的训练好的模型。也可以你自己找一些文档query数据集训练一个**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=1683)
- `0:28:05`**t5是预训练模型  跟bert那种训练好的一样**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=1685)
- `0:30:14`**就是position embbeding concate进input了呗**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=1814)
- `0:30:28`**我个人的理解是原来的每一步输出都是按照一个相同的矩阵来和当前步的h进行相乘然后取softmax，但是作者现在想换成按照每一步都有一个独立的矩阵相乘取softmax，不知道对不对**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=1828)
- `0:31:21`**这个是原创，然而纯trick**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=1881)
- `0:31:37`**有种写专利硬凑的感觉。。**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=1897)
- `0:31:38`**发现手里的论文的图，跟这个图不一样，手里的论文的hi是Ei?**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=1898)
- `0:31:41`**寫過類似的東西 有用 提升兩個點**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=1901)
- `0:31:49`**这幅图说实话做的很糟糕，太容易产生歧义了。作者完全可以只展示做一次预测的过程**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=1909)
- `0:32:22`**r- dropout**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=1942)
- `0:32:27`**除了r drop，simcse也类似**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=1947)
- `0:32:34`**simcse也是这样的**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=1954)
- `0:32:43`**si m c l r**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=1963)
- `0:36:37`**改进基本纯trick，reg函数其实就是rdrop**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=2197)
- `0:38:21`**QA对语义要求更高一些吧？**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=2301)
- `0:38:25`**是的 QA不要求term精确匹配**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=2305)
- `0:40:18`**这块生成器怎么训练的？**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=2418)
- `0:40:20`**预训练的，前面说过了吧**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=2420)
- `0:40:26`**这个实验居然在最新版已经去掉了。不显示这个Query生成的效果了**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=2426)
- `0:44:06`**猜的没错，那个开源bm25实现确实非常烂…**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=2646)
- `0:44:37`**新来的文档重新训，太伤了**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=2677)
- `0:44:39`**这个还不如twin tower呢**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=2679)
- `0:45:59`**DSI还不如BM25？**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=2759)
- `0:46:44`**这里我也打开openrevirew网站了，搜到了这篇论文，为什么我看不到comments呀。**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=2804)
- `0:47:20`**有点像prompt，或者COT？**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=2840)
- `0:48:23`**直接加序号虽然提升了了性能，但是不是过拟合了，真实场景的序号不同吧？**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=2903)
- `0:48:59`**最后做了分类相当于计算了query跟所有doc的距离，对性能破坏太大了，还得ann**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=2939)
- `0:51:54`**可见ms团队这个工作氛围略好大喜功**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=3114)
- `0:52:02`**可能确实那时他们效果确实够好，也就想吹一吹**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=3122)
- `0:52:18`**这样写可能是为了唬住审稿人 文章好中**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=3138)
- `0:52:36`**有可能是和DSI时间差不多，但是DSI先挂Arxiv了**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=3156)
- `0:52:42`**感觉这个论文像是比DSI挂ArXiv慢了一步，所以导致里面很多话都说的很满**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=3162)
- `0:53:05`**怎么听解读感觉dsi更经典啊**　[↗](https://www.bilibili.com/video/BV1Se411w7Sn?t=3185)
