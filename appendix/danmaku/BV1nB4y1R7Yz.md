# 弹幕讨论 · Megatron LM 论文精读【论文精读】

> 视频：[BV1nB4y1R7Yz](https://www.bilibili.com/video/BV1nB4y1R7Yz)　时长 0:56:08　弹幕总数 **220**　有实质内容 **100** 条　重点标记 **100** 条
>
> 来源：B 站 **跟李沐学AI** 的该集弹幕　快照：**2026-10-13**

## 口径说明（务必先读）

**这些内容全部是观众在视频上发的弹幕，不是经过核实的结论。**

- 其中有价值的：概念解释、类比、勘误、学习方法、延伸阅读线索。
- **也可能有错误的**：弹幕是个人理解，未经作者或权威确认。
  **本页不为其正确性背书，请勿直接引用为事实。**
- 每条带时间戳，点击可跳回视频对应位置自行核对。
- 筛选口径：保留长度 ≥ 10 字符、且不含纯感叹/打卡类噪声的弹幕，共 100 条（占该集弹幕 220 条的 45.5%）；同一句话被多人发送只保留一条并标注发送次数。
- 「重点」标记由关键词打分得出（技术词 + 解释性措辞 + 长度 + 多人重复），共 100 条；**它是启发式排序，不代表正确性，也不代表其余条目无价值。**

## 重点条目

| 时间 | 弹幕 | 发送次数 |
|---|---|---:|
| [0:00:11](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=11) | aws的箭头好像被当幕布剪掉了 | 1 |
| [0:00:14](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=14) | 我小时候听到的翻译版本是麦加登 | 1 |
| [0:00:51](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=51) | 威震天（Megatron） | 1 |
| [0:00:55](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=55) | Megatron威震天，老大 | 1 |
| [0:00:59](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=59) | 这是几十亿啊 doge | 1 |
| [0:00:59](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=59) | 变形金刚（transformers） | 1 |
| [0:01:02](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=62) | 和Transformer对应吗（ | 1 |
| [0:01:56](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=116) | 木神在亚马逊工作么！？ | 1 |
| [0:02:30](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=150) | 为啥我的注意力一直在沐神胸口的可透视图标上 | 1 |
| [0:02:58](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=178) | 你这条弹幕成功让我分心了 | 1 |
| [0:04:16](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=256) | 2026年考古，现在SOTA模型都是TB级别，8.3B确实和玩具差不多 | 1 |
| [0:04:32](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=272) | 虽然效果好，但模型太简单，， | 1 |
| [0:04:38](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=278) | 512个GPU，估计大部分学校都没有这个条件。。。 | 1 |
| [0:04:46](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=286) | 英伟达自己的团队肯定有 | 1 |
| [0:06:06](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=366) | 端午都有100多人看，卷啊 | 1 |
| [0:07:47](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=467) | 是不是没有GPU都没办法从事这个方向？？ | 1 |
| [0:08:05](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=485) | 前面，是的没有GPU基本上GPT3以后的模型你就都不用参与了，目前的ASIC性能基本达不到 | 1 |
| [0:09:38](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=578) | 后面改成deepnorm了.... | 1 |
| [0:12:55](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=775) | at what cost? | 1 |
| [0:12:58](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=778) | 然而非常不简单，非常难用 | 1 |
| [0:13:43](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=823) | 醍醐灌顶，一下就串起来了 | 1 |
| [0:13:52](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=832) | blvblv的意思是 当前位置 每个词都有词表上的预测分数，所以是v | 1 |
| [0:13:57](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=837) | 太精辟了，大佬就是大佬 | 1 |
| [0:15:21](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=921) | 这里为什么说是隐藏层的大小呢，不应该是单词的维度吗 | 1 |
| [0:15:28](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=928) | 这里说的应该是hidden_size等于token embedding_size的情况 | 1 |
| [0:15:29](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=929) | 隐藏层的维度就等于token张量的维度 | 1 |
| [0:15:37](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=937) | batch_size*sequence_length*token_size | 1 |
| [0:16:31](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=991) | 这里没画太好，gelu过0，0点的 | 1 |
| [0:20:44](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1244) | 然后做一次allgather | 1 |
| [0:20:46](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1246) | 感觉跟Swin-Transformer做shift之后的attention计算原理是一样的 | 1 |
| [0:20:47](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1247) | 怎么有点MapReduce的感觉 | 1 |
| [0:21:40](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1300) | 但是只需要在计算完结果的时候通讯了 计算中途都是并行的 | 1 |
| [0:21:42](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1302) | 这样做的好处就是节省了一次allgather的通信 | 1 |
| [0:21:44](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1304) | K' 比 K大四倍，新的方案只用1/4的通讯开销 | 1 |
| [0:21:58](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1318) | 意思是相比数据并行，通信开销降低为之前的1/4，在K撇是4K大小的情况下 | 1 |
| [0:22:12](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1332) | 张量并行那么就不需要把梯度合起来了，因为参数张量拆分了 | 1 |
| [0:22:20](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1340) | 你自己在草稿纸上推导一下就知道了 | 1 |
| [0:22:20](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1340) | 这两种方式一起使用吧 | 1 |
| [0:22:30](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1350) | 这样也节省不了多少内存啊 | 1 |
| [0:22:42](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1362) | 第二个方法主要好在节省通讯次数 | 1 |
| [0:22:59](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1379) | 这不就是mlp并行么 | 1 |
| [0:23:47](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1427) | multi-head天然支持这套张量并行 | 1 |
| [0:23:59](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1439) | mlp层的拆分机制做的是数据并行？ | 1 |
| [0:24:53](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1493) | 应该是和V做点积才对吧？ | 1 |
| [0:24:57](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1497) | 对，我也想说这点，按照缩放点积那里的代码就是点积 | 1 |
| [0:24:59](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1499) | 这里应该是相乘吧, y=(q*k^T)/\sqrt{d_k}*t | 1 |
| [0:25:23](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1523) | 一个头的时候和V相加也可以？我记得好像是相乘的 | 1 |
| [0:25:27](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1527) | 是相乘，口误了，理解就行 | 1 |
| [0:25:45](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1545) | 相乘，口误了吧，问题不大 | 1 |
| [0:25:51](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1551) | 也就是多头是并行算的 | 1 |
| [0:26:42](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1602) | GPU个数大于注意力的头数的时候是如何处理的？ | 1 |
| [0:27:03](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1623) | 这个并不是concat操作吧，这里只是对于一个单层的MHA来说的，拆分的QKV三个矩阵 | 1 |
| [0:27:13](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1633) | 做个ALL REDUCE | 1 |
| [0:27:43](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1663) | 老师 头别动 我截个图 | 1 |
| [0:29:15](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1755) | 注意这里是training部分而非inference部分 | 1 |
| [0:29:41](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1781) | v是词表大小，k是隐藏层大小，和上面attn的那个k相同 | 1 |
| [0:29:44](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1784) | 这块的切法好像跟论文里面讲的不一样 | 1 |
| [0:30:08](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1808) | 在另外一块能找到为什么变成0 | 1 |
| [0:30:15](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1815) | 0的意思是找不到的写0，那么和找到的那个加起来就行 | 1 |
| [0:30:22](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1822) | 做成0是为了后面2个GPU做allreduce方便 | 1 |
| [0:30:28](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1828) | b乘以l相当于是token数量 | 1 |
| [0:30:36](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1836) | 在没找到的GPU上给0 | 1 |
| [0:30:38](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1838) | 输出层不就是做了一个linear么 | 1 |
| [0:30:46](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1846) | 不是linear，比如机器翻译得到token，在输出层要映射回文本，就是一个嵌入层查字典 | 1 |
| [0:31:01](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1861) | 为啥是V呢？不应该还是K么 | 1 |
| [0:31:05](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1865) | 前面的，因为v是词表长度。你最后要算某个位置上，每一个词的概率，取最大那个 | 1 |
| [0:31:14](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1874) | softmax也可以并行吧 | 1 |
| [0:31:19](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1879) | 因为需要计算词典中每个 token 对应的概率，所以是 V。 | 1 |
| [0:31:20](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1880) | 输出层的目的是更新词表 | 1 |
| [0:31:22](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1882) | 这个b*l就是token数量，就是b句有l个词的数据中单词的个数，v是对每一个单词输出的预测值的长度，也就是有v个和为1的百分数 | 1 |
| [0:31:22](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1882) | flashattention | 1 |
| [0:31:37](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1897) | 我不理解，为什么输入说出要共享embedding，参数矩阵都形状都是不一样 | 1 |
| [0:31:38](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1898) | v是每个词的logits吧 | 1 |
| [0:31:44](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1904) | b就是batch，指的是句子总数，l是每个句子中的单词数 | 1 |
| [0:31:44](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1904) | v是vocab size | 1 |
| [0:31:45](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1905) | 输出embedding 矩阵式是输入embedding矩阵的转置 共享权重 所以可以通用 计算的时transpose一下就行了 | 1 |
| [0:31:52](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1912) | 输出不应该是每个句子下一个 token 所以是 b*v 吗 | 1 |
| [0:32:11](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1931) | 局部最大之最大为全局最大，局部和之和为全局和之和 | 1 |
| [0:32:16](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1936) | tansformer那张图的输出层是linear啊，为什么不写明embedding | 1 |
| [0:32:27](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1947) | 就是列求和，然后传输，最后行求softmax | 1 |
| [0:32:37](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1957) | 这里是针对softmax分母求和做的优化 | 1 |
| [0:32:51](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1971) | 这里画列，主要指求和完每一行就变量一个标量，所以 all-reduce 交互的只有一列求和的向量 | 1 |
| [0:33:20](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=2000) | 回头还是再看下transformer的论文吧。 | 1 |
| [0:33:31](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=2011) | 第一个按列，第二个按行 | 1 |
| [0:36:12](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=2172) | 这里是什么意思？听不懂 | 1 |
| [0:36:36](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=2196) | k^2指的是把权重给all-reduce   b l k 指的是把中间结果进行all-reduce   n | 1 |
| [0:37:33](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=2253) | 1W不是10的四次方吗 | 1 |
| [0:38:31](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=2311) | 这里为啥不需要啊？不用等权重在主节点更新以后再重新发送权重吗？ | 1 |
| [0:40:23](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=2423) | money is all you need | 1 |
| [0:40:33](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=2433) | 这论文真不是谁都能发的，小公司、小实验室、穷老师、穷学生就不要想了。。 | 1 |
| [0:40:33](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=2433) | nv自己论文想怎么弄就怎么弄 | 1 |
| [0:40:42](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=2442) | wwwwwwwwwww | 1 |
| [0:40:59](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=2459) | 自家卖GPU的，随便用 | 1 |
| [0:41:08](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=2468) | 一个infiniband 100Gbps | 1 |
| [0:41:29](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=2489) | NV 硬广了，属于是 | 1 |
| [0:43:59](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=2639) | PCIE 总线不够用了。。 | 1 |
| [0:49:22](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=2962) | AllReduce的数据并行是同步的吧？ | 1 |
| [0:49:57](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=2997) | 两个都是preNorm 区别时shortcut那条路是否有LayerNorm | 1 |
| [0:50:01](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=3001) | LayerNorm实际上是有affine参数的，可能x+f（x）的时候，我猜可能是affine引起了原始x的偏移导致崩了 | 1 |
| [0:50:24](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=3024) | b属于pre-LN吧 | 1 |

## 全部有实质内容的弹幕（按时间排序，共 100 条）

- `0:00:11`**aws的箭头好像被当幕布剪掉了**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=11)
- `0:00:14`**我小时候听到的翻译版本是麦加登**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=14)
- `0:00:51`**威震天（Megatron）**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=51)
- `0:00:55`**Megatron威震天，老大**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=55)
- `0:00:59`**这是几十亿啊 doge**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=59)
- `0:00:59`**变形金刚（transformers）**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=59)
- `0:01:02`**和Transformer对应吗（**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=62)
- `0:01:56`**木神在亚马逊工作么！？**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=116)
- `0:02:30`**为啥我的注意力一直在沐神胸口的可透视图标上**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=150)
- `0:02:58`**你这条弹幕成功让我分心了**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=178)
- `0:04:16`**2026年考古，现在SOTA模型都是TB级别，8.3B确实和玩具差不多**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=256)
- `0:04:32`**虽然效果好，但模型太简单，，**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=272)
- `0:04:38`**512个GPU，估计大部分学校都没有这个条件。。。**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=278)
- `0:04:46`**英伟达自己的团队肯定有**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=286)
- `0:06:06`**端午都有100多人看，卷啊**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=366)
- `0:07:47`**是不是没有GPU都没办法从事这个方向？？**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=467)
- `0:08:05`**前面，是的没有GPU基本上GPT3以后的模型你就都不用参与了，目前的ASIC性能基本达不到**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=485)
- `0:09:38`**后面改成deepnorm了....**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=578)
- `0:12:55`**at what cost?**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=775)
- `0:12:58`**然而非常不简单，非常难用**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=778)
- `0:13:43`**醍醐灌顶，一下就串起来了**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=823)
- `0:13:52`**blvblv的意思是 当前位置 每个词都有词表上的预测分数，所以是v**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=832)
- `0:13:57`**太精辟了，大佬就是大佬**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=837)
- `0:15:21`**这里为什么说是隐藏层的大小呢，不应该是单词的维度吗**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=921)
- `0:15:28`**这里说的应该是hidden_size等于token embedding_size的情况**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=928)
- `0:15:29`**隐藏层的维度就等于token张量的维度**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=929)
- `0:15:37`**batch_size*sequence_length*token_size**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=937)
- `0:16:31`**这里没画太好，gelu过0，0点的**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=991)
- `0:20:44`**然后做一次allgather**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1244)
- `0:20:46`**感觉跟Swin-Transformer做shift之后的attention计算原理是一样的**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1246)
- `0:20:47`**怎么有点MapReduce的感觉**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1247)
- `0:21:40`**但是只需要在计算完结果的时候通讯了 计算中途都是并行的**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1300)
- `0:21:42`**这样做的好处就是节省了一次allgather的通信**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1302)
- `0:21:44`**K' 比 K大四倍，新的方案只用1/4的通讯开销**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1304)
- `0:21:58`**意思是相比数据并行，通信开销降低为之前的1/4，在K撇是4K大小的情况下**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1318)
- `0:22:12`**张量并行那么就不需要把梯度合起来了，因为参数张量拆分了**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1332)
- `0:22:20`**你自己在草稿纸上推导一下就知道了**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1340)
- `0:22:20`**这两种方式一起使用吧**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1340)
- `0:22:30`**这样也节省不了多少内存啊**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1350)
- `0:22:42`**第二个方法主要好在节省通讯次数**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1362)
- `0:22:59`**这不就是mlp并行么**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1379)
- `0:23:47`**multi-head天然支持这套张量并行**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1427)
- `0:23:59`**mlp层的拆分机制做的是数据并行？**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1439)
- `0:24:53`**应该是和V做点积才对吧？**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1493)
- `0:24:57`**对，我也想说这点，按照缩放点积那里的代码就是点积**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1497)
- `0:24:59`**这里应该是相乘吧, y=(q*k^T)/\sqrt{d_k}*t**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1499)
- `0:25:23`**一个头的时候和V相加也可以？我记得好像是相乘的**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1523)
- `0:25:27`**是相乘，口误了，理解就行**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1527)
- `0:25:45`**相乘，口误了吧，问题不大**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1545)
- `0:25:51`**也就是多头是并行算的**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1551)
- `0:26:42`**GPU个数大于注意力的头数的时候是如何处理的？**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1602)
- `0:27:03`**这个并不是concat操作吧，这里只是对于一个单层的MHA来说的，拆分的QKV三个矩阵**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1623)
- `0:27:13`**做个ALL REDUCE**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1633)
- `0:27:43`**老师 头别动 我截个图**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1663)
- `0:29:15`**注意这里是training部分而非inference部分**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1755)
- `0:29:41`**v是词表大小，k是隐藏层大小，和上面attn的那个k相同**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1781)
- `0:29:44`**这块的切法好像跟论文里面讲的不一样**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1784)
- `0:30:08`**在另外一块能找到为什么变成0**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1808)
- `0:30:15`**0的意思是找不到的写0，那么和找到的那个加起来就行**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1815)
- `0:30:22`**做成0是为了后面2个GPU做allreduce方便**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1822)
- `0:30:28`**b乘以l相当于是token数量**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1828)
- `0:30:36`**在没找到的GPU上给0**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1836)
- `0:30:38`**输出层不就是做了一个linear么**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1838)
- `0:30:46`**不是linear，比如机器翻译得到token，在输出层要映射回文本，就是一个嵌入层查字典**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1846)
- `0:31:01`**为啥是V呢？不应该还是K么**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1861)
- `0:31:05`**前面的，因为v是词表长度。你最后要算某个位置上，每一个词的概率，取最大那个**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1865)
- `0:31:14`**softmax也可以并行吧**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1874)
- `0:31:19`**因为需要计算词典中每个 token 对应的概率，所以是 V。**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1879)
- `0:31:20`**输出层的目的是更新词表**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1880)
- `0:31:22`**这个b*l就是token数量，就是b句有l个词的数据中单词的个数，v是对每一个单词输出的预测值的长度，也就是有v个和为1的百分数**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1882)
- `0:31:22`**flashattention**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1882)
- `0:31:37`**我不理解，为什么输入说出要共享embedding，参数矩阵都形状都是不一样**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1897)
- `0:31:38`**v是每个词的logits吧**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1898)
- `0:31:44`**b就是batch，指的是句子总数，l是每个句子中的单词数**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1904)
- `0:31:44`**v是vocab size**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1904)
- `0:31:45`**输出embedding 矩阵式是输入embedding矩阵的转置 共享权重 所以可以通用 计算的时transpose一下就行了**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1905)
- `0:31:52`**输出不应该是每个句子下一个 token 所以是 b*v 吗**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1912)
- `0:32:11`**局部最大之最大为全局最大，局部和之和为全局和之和**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1931)
- `0:32:16`**tansformer那张图的输出层是linear啊，为什么不写明embedding**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1936)
- `0:32:27`**就是列求和，然后传输，最后行求softmax**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1947)
- `0:32:37`**这里是针对softmax分母求和做的优化**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1957)
- `0:32:51`**这里画列，主要指求和完每一行就变量一个标量，所以 all-reduce 交互的只有一列求和的向量**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=1971)
- `0:33:20`**回头还是再看下transformer的论文吧。**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=2000)
- `0:33:31`**第一个按列，第二个按行**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=2011)
- `0:36:12`**这里是什么意思？听不懂**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=2172)
- `0:36:36`**k^2指的是把权重给all-reduce   b l k 指的是把中间结果进行all-reduce   n**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=2196)
- `0:37:33`**1W不是10的四次方吗**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=2253)
- `0:38:31`**这里为啥不需要啊？不用等权重在主节点更新以后再重新发送权重吗？**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=2311)
- `0:40:23`**money is all you need**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=2423)
- `0:40:33`**这论文真不是谁都能发的，小公司、小实验室、穷老师、穷学生就不要想了。。**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=2433)
- `0:40:33`**nv自己论文想怎么弄就怎么弄**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=2433)
- `0:40:42`**wwwwwwwwwww**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=2442)
- `0:40:59`**自家卖GPU的，随便用**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=2459)
- `0:41:08`**一个infiniband 100Gbps**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=2468)
- `0:41:29`**NV 硬广了，属于是**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=2489)
- `0:43:59`**PCIE 总线不够用了。。**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=2639)
- `0:49:22`**AllReduce的数据并行是同步的吧？**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=2962)
- `0:49:57`**两个都是preNorm 区别时shortcut那条路是否有LayerNorm**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=2997)
- `0:50:01`**LayerNorm实际上是有affine参数的，可能x+f（x）的时候，我猜可能是affine引起了原始x的偏移导致崩了**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=3001)
- `0:50:24`**b属于pre-LN吧**　[↗](https://www.bilibili.com/video/BV1nB4y1R7Yz?t=3024)
