# 弹幕讨论 · Zero 论文精读【论文精读】

> 视频：[BV1tY411g7ZT](https://www.bilibili.com/video/BV1tY411g7ZT)　时长 0:52:21　弹幕总数 **159**　有实质内容 **71** 条　重点标记 **71** 条
>
> 来源：B 站 **跟李沐学AI** 的该集弹幕　快照：**2026-10-13**

## 口径说明（务必先读）

**这些内容全部是观众在视频上发的弹幕，不是经过核实的结论。**

- 其中有价值的：概念解释、类比、勘误、学习方法、延伸阅读线索。
- **也可能有错误的**：弹幕是个人理解，未经作者或权威确认。
  **本页不为其正确性背书，请勿直接引用为事实。**
- 每条带时间戳，点击可跳回视频对应位置自行核对。
- 筛选口径：保留长度 ≥ 10 字符、且不含纯感叹/打卡类噪声的弹幕，共 71 条（占该集弹幕 159 条的 44.7%）；同一句话被多人发送只保留一条并标注发送次数。
- 「重点」标记由关键词打分得出（技术词 + 解释性措辞 + 长度 + 多人重复），共 71 条；**它是启发式排序，不代表正确性，也不代表其余条目无价值。**

## 重点条目

| 时间 | 弹幕 | 发送次数 |
|---|---|---:|
| [0:01:16](https://www.bilibili.com/video/BV1tY411g7ZT?t=76) | 李沐：参数服务器正是我提出的 | 1 |
| [0:04:38](https://www.bilibili.com/video/BV1tY411g7ZT?t=278) | 那么要不要考虑出一个视频讲讲呢 | 1 |
| [0:05:00](https://www.bilibili.com/video/BV1tY411g7ZT?t=300) | 1.4B 32G 多少batchsize, 多长的输入文本 | 1 |
| [0:07:12](https://www.bilibili.com/video/BV1tY411g7ZT?t=432) | 一个公司的做一个项目也是这样大多数时间用在沟通上面了 | 1 |
| [0:08:56](https://www.bilibili.com/video/BV1tY411g7ZT?t=536) | 有没有小伙伴知道activation是在什么时候讲到的 | 1 |
| [0:09:14](https://www.bilibili.com/video/BV1tY411g7ZT?t=554) | gpipe里面讲需要两次前向传播的时候讲的 | 1 |
| [0:09:45](https://www.bilibili.com/video/BV1tY411g7ZT?t=585) | 这篇文章真的读起来很怪 | 1 |
| [0:09:56](https://www.bilibili.com/video/BV1tY411g7ZT?t=596) | 懂得都懂，不懂的我也不想解释，听懂掌声 | 1 |
| [0:10:34](https://www.bilibili.com/video/BV1tY411g7ZT?t=634) | 感觉这行文逻辑有点跳脱啊 | 1 |
| [0:11:30](https://www.bilibili.com/video/BV1tY411g7ZT?t=690) | 微软的这几篇zero的工作写的风格都是这样的，很难读 | 1 |
| [0:11:41](https://www.bilibili.com/video/BV1tY411g7ZT?t=701) | 看微软官方那个视频看一遍就懂了... | 1 |
| [0:12:56](https://www.bilibili.com/video/BV1tY411g7ZT?t=776) | Who is Adam | 1 |
| [0:13:47](https://www.bilibili.com/video/BV1tY411g7ZT?t=827) | 大部分的人其实用不到这些，到了公司才需要用到 | 1 |
| [0:13:52](https://www.bilibili.com/video/BV1tY411g7ZT?t=832) | 你只要有tesla的卡就用得到，不一定要在公司，而且哪怕是GeForce的卡，用半精度也可以省显存 | 1 |
| [0:14:14](https://www.bilibili.com/video/BV1tY411g7ZT?t=854) | 大核是 Tensor core吗 | 1 |
| [0:15:00](https://www.bilibili.com/video/BV1tY411g7ZT?t=900) | tensor core | 2 |
| [0:15:11](https://www.bilibili.com/video/BV1tY411g7ZT?t=911) | 实际体验，在训练bert-large和deberta-xlarge的时候，混合精度经常导致nan | 1 |
| [0:15:40](https://www.bilibili.com/video/BV1tY411g7ZT?t=940) | 其实这是\psi，不是\phi | 1 |
| [0:16:13](https://www.bilibili.com/video/BV1tY411g7ZT?t=973) | 为啥fp16的时候不是分开存，，fp32的时候就要分开存权重 | 1 |
| [0:16:16](https://www.bilibili.com/video/BV1tY411g7ZT?t=976) | 就是到adam的时候要转化之后存 | 1 |
| [0:16:28](https://www.bilibili.com/video/BV1tY411g7ZT?t=988) | 那fp16相比fp32所用显存不就变成一样的了吗 | 1 |
| [0:16:30](https://www.bilibili.com/video/BV1tY411g7ZT?t=990) | loss scale就不用存fp32了吧 | 1 |
| [0:17:43](https://www.bilibili.com/video/BV1tY411g7ZT?t=1063) | 27gb除以4差不多7GB，加上刚才的24GB是31GB | 1 |
| [0:17:46](https://www.bilibili.com/video/BV1tY411g7ZT?t=1066) | 还没算torch context | 1 |
| [0:18:20](https://www.bilibili.com/video/BV1tY411g7ZT?t=1100) | 字幕错了，是析构，不是虚构 | 1 |
| [0:18:21](https://www.bilibili.com/video/BV1tY411g7ZT?t=1101) | 是析构不是虚构哈，字幕错了 | 1 |
| [0:18:41](https://www.bilibili.com/video/BV1tY411g7ZT?t=1121) | tensorflow文档写好点，也不至于搞成今天这样 | 1 |
| [0:18:44](https://www.bilibili.com/video/BV1tY411g7ZT?t=1124) | vllm就是解决这个问题的吧 | 1 |
| [0:20:21](https://www.bilibili.com/video/BV1tY411g7ZT?t=1221) | 占显存吧，怎么会占带宽呢 | 1 |
| [0:20:26](https://www.bilibili.com/video/BV1tY411g7ZT?t=1226) | 我也觉得老师说错了 应该是显存 | 1 |
| [0:20:49](https://www.bilibili.com/video/BV1tY411g7ZT?t=1249) | 但是通信的带宽开销是不是就大了 | 1 |
| [0:20:54](https://www.bilibili.com/video/BV1tY411g7ZT?t=1254) | 这个参数通信层与层之间可以并行啊 | 1 |
| [0:20:55](https://www.bilibili.com/video/BV1tY411g7ZT?t=1255) | 带宽换显存呗，总得有牺牲的 | 1 |
| [0:21:00](https://www.bilibili.com/video/BV1tY411g7ZT?t=1260) | 感觉和megatron思想一样呀 | 1 |
| [0:25:43](https://www.bilibili.com/video/BV1tY411g7ZT?t=1543) | 这个想法有点类似ring all reduce | 1 |
| [0:25:55](https://www.bilibili.com/video/BV1tY411g7ZT?t=1555) | 有一个小问题其实，就是梯度并不是这样全发，只维护自己那一部分就可以 | 1 |
| [0:27:29](https://www.bilibili.com/video/BV1tY411g7ZT?t=1649) | 有个reduce scatter算子 | 1 |
| [0:29:23](https://www.bilibili.com/video/BV1tY411g7ZT?t=1763) | 为啥1024比64只少这么一点点 | 1 |
| [0:29:36](https://www.bilibili.com/video/BV1tY411g7ZT?t=1776) | 因为这个地方有一个基础的内存，就是fp16 存储的基础模型，其他fp32的参数以及梯度这些在256平均的时候数值已经比较小了，再进行/4也很小所以对总的影响比较小 | 1 |
| [0:29:38](https://www.bilibili.com/video/BV1tY411g7ZT?t=1778) | 因为只用了zero1，还有几个部分没切 | 1 |
| [0:32:15](https://www.bilibili.com/video/BV1tY411g7ZT?t=1935) | 补全这里的内存开销是属于哪个部分呢 | 1 |
| [0:32:22](https://www.bilibili.com/video/BV1tY411g7ZT?t=1942) | megatron 里的 sequence parallel | 1 |
| [0:32:26](https://www.bilibili.com/video/BV1tY411g7ZT?t=1946) | activations | 1 |
| [0:32:38](https://www.bilibili.com/video/BV1tY411g7ZT?t=1958) | 做一次scatter-reduce | 1 |
| [0:32:57](https://www.bilibili.com/video/BV1tY411g7ZT?t=1977) | 这个是不是叫 reduce scatter | 1 |
| [0:33:02](https://www.bilibili.com/video/BV1tY411g7ZT?t=1982) | 这不是all reduce操作，这是reduce-scatter操作 | 1 |
| [0:33:07](https://www.bilibili.com/video/BV1tY411g7ZT?t=1987) | 前向为什么会有梯度？ 应该是想说activation吧 | 1 |
| [0:33:14](https://www.bilibili.com/video/BV1tY411g7ZT?t=1994) | 是 reduce-scatter | 1 |
| [0:33:57](https://www.bilibili.com/video/BV1tY411g7ZT?t=2037) | 没有事先了解的话直接看这个视频还是有点抽象 | 1 |
| [0:33:57](https://www.bilibili.com/video/BV1tY411g7ZT?t=2037) | 可以看微软官方的视频，非常清楚 | 1 |
| [0:34:15](https://www.bilibili.com/video/BV1tY411g7ZT?t=2055) | 所以zero3的参数并行和megatron的区别是什么 | 1 |
| [0:34:20](https://www.bilibili.com/video/BV1tY411g7ZT?t=2060) | zero3 切 weight， 每张卡存一部分，但是整整计算的时候，还是会使用完整的 weight 计算，还是属于 数据并行。megater 中切weight 是张量并行 | 1 |
| [0:37:07](https://www.bilibili.com/video/BV1tY411g7ZT?t=2227) | 可以理解为buffer存在decay系数？ | 1 |
| [0:38:08](https://www.bilibili.com/video/BV1tY411g7ZT?t=2288) | python后端cPython有实现内存池 | 1 |
| [0:38:22](https://www.bilibili.com/video/BV1tY411g7ZT?t=2302) | 内存碎片化，nvidia-smi和torch allocated显示的内存也不一样 | 1 |
| [0:38:49](https://www.bilibili.com/video/BV1tY411g7ZT?t=2329) | 感觉跟jvm里面的内存管理思想相似，释放并整理内存 | 1 |
| [0:39:04](https://www.bilibili.com/video/BV1tY411g7ZT?t=2344) | python的内存池也是这么做的 | 1 |
| [0:40:35](https://www.bilibili.com/video/BV1tY411g7ZT?t=2435) | 也就1024块卡。。。。。。 | 1 |
| [0:41:38](https://www.bilibili.com/video/BV1tY411g7ZT?t=2498) | 是回扣，也可能是微软就是钱太多 | 1 |
| [0:46:01](https://www.bilibili.com/video/BV1tY411g7ZT?t=2761) | 大batch只是单卡计算量提上去了，实际训练速度可能会下降 | 1 |
| [0:46:21](https://www.bilibili.com/video/BV1tY411g7ZT?t=2781) | 这里的计算应该是反向传播的计算？ | 1 |
| [0:46:46](https://www.bilibili.com/video/BV1tY411g7ZT?t=2806) | 所以一般来说我只需要关注加速比就可以了是吗？ | 1 |
| [0:47:03](https://www.bilibili.com/video/BV1tY411g7ZT?t=2823) | 好多分布式论文不给收敛结果 | 1 |
| [0:47:32](https://www.bilibili.com/video/BV1tY411g7ZT?t=2852) | 训练一个100B的模型收敛不现实 | 1 |
| [0:48:26](https://www.bilibili.com/video/BV1tY411g7ZT?t=2906) | gpt-3: 勿 Cue，谢谢 | 1 |
| [0:48:47](https://www.bilibili.com/video/BV1tY411g7ZT?t=2927) | 沐神：还不是参数服务器那点小把戏 | 1 |
| [0:49:26](https://www.bilibili.com/video/BV1tY411g7ZT?t=2966) | 这为什么也能写论文··· | 1 |
| [0:50:41](https://www.bilibili.com/video/BV1tY411g7ZT?t=3041) | 跟我的参数服务器还差一些 | 1 |
| [0:50:59](https://www.bilibili.com/video/BV1tY411g7ZT?t=3059) | 我写论文很头疼的事情就是几句话就说完自己的想法了 | 1 |
| [0:51:02](https://www.bilibili.com/video/BV1tY411g7ZT?t=3062) | 不是谁都可以发顶会的 | 1 |
| [0:51:51](https://www.bilibili.com/video/BV1tY411g7ZT?t=3111) | GPT：勿cue。。 | 1 |

## 全部有实质内容的弹幕（按时间排序，共 71 条）

- `0:01:16`**李沐：参数服务器正是我提出的**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=76)
- `0:04:38`**那么要不要考虑出一个视频讲讲呢**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=278)
- `0:05:00`**1.4B 32G 多少batchsize, 多长的输入文本**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=300)
- `0:07:12`**一个公司的做一个项目也是这样大多数时间用在沟通上面了**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=432)
- `0:08:56`**有没有小伙伴知道activation是在什么时候讲到的**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=536)
- `0:09:14`**gpipe里面讲需要两次前向传播的时候讲的**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=554)
- `0:09:45`**这篇文章真的读起来很怪**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=585)
- `0:09:56`**懂得都懂，不懂的我也不想解释，听懂掌声**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=596)
- `0:10:34`**感觉这行文逻辑有点跳脱啊**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=634)
- `0:11:30`**微软的这几篇zero的工作写的风格都是这样的，很难读**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=690)
- `0:11:41`**看微软官方那个视频看一遍就懂了...**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=701)
- `0:12:56`**Who is Adam**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=776)
- `0:13:47`**大部分的人其实用不到这些，到了公司才需要用到**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=827)
- `0:13:52`**你只要有tesla的卡就用得到，不一定要在公司，而且哪怕是GeForce的卡，用半精度也可以省显存**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=832)
- `0:14:14`**大核是 Tensor core吗**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=854)
- `0:15:00`**tensor core**（×2）　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=900)
- `0:15:11`**实际体验，在训练bert-large和deberta-xlarge的时候，混合精度经常导致nan**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=911)
- `0:15:40`**其实这是\psi，不是\phi**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=940)
- `0:16:13`**为啥fp16的时候不是分开存，，fp32的时候就要分开存权重**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=973)
- `0:16:16`**就是到adam的时候要转化之后存**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=976)
- `0:16:28`**那fp16相比fp32所用显存不就变成一样的了吗**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=988)
- `0:16:30`**loss scale就不用存fp32了吧**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=990)
- `0:17:43`**27gb除以4差不多7GB，加上刚才的24GB是31GB**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=1063)
- `0:17:46`**还没算torch context**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=1066)
- `0:18:20`**字幕错了，是析构，不是虚构**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=1100)
- `0:18:21`**是析构不是虚构哈，字幕错了**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=1101)
- `0:18:41`**tensorflow文档写好点，也不至于搞成今天这样**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=1121)
- `0:18:44`**vllm就是解决这个问题的吧**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=1124)
- `0:20:21`**占显存吧，怎么会占带宽呢**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=1221)
- `0:20:26`**我也觉得老师说错了 应该是显存**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=1226)
- `0:20:49`**但是通信的带宽开销是不是就大了**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=1249)
- `0:20:54`**这个参数通信层与层之间可以并行啊**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=1254)
- `0:20:55`**带宽换显存呗，总得有牺牲的**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=1255)
- `0:21:00`**感觉和megatron思想一样呀**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=1260)
- `0:25:43`**这个想法有点类似ring all reduce**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=1543)
- `0:25:55`**有一个小问题其实，就是梯度并不是这样全发，只维护自己那一部分就可以**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=1555)
- `0:27:29`**有个reduce scatter算子**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=1649)
- `0:29:23`**为啥1024比64只少这么一点点**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=1763)
- `0:29:36`**因为这个地方有一个基础的内存，就是fp16 存储的基础模型，其他fp32的参数以及梯度这些在256平均的时候数值已经比较小了，再进行/4也很小所以对总的影响比较小**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=1776)
- `0:29:38`**因为只用了zero1，还有几个部分没切**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=1778)
- `0:32:15`**补全这里的内存开销是属于哪个部分呢**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=1935)
- `0:32:22`**megatron 里的 sequence parallel**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=1942)
- `0:32:26`**activations**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=1946)
- `0:32:38`**做一次scatter-reduce**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=1958)
- `0:32:57`**这个是不是叫 reduce scatter**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=1977)
- `0:33:02`**这不是all reduce操作，这是reduce-scatter操作**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=1982)
- `0:33:07`**前向为什么会有梯度？ 应该是想说activation吧**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=1987)
- `0:33:14`**是 reduce-scatter**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=1994)
- `0:33:57`**没有事先了解的话直接看这个视频还是有点抽象**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=2037)
- `0:33:57`**可以看微软官方的视频，非常清楚**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=2037)
- `0:34:15`**所以zero3的参数并行和megatron的区别是什么**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=2055)
- `0:34:20`**zero3 切 weight， 每张卡存一部分，但是整整计算的时候，还是会使用完整的 weight 计算，还是属于 数据并行。megater 中切weight 是张量并行**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=2060)
- `0:37:07`**可以理解为buffer存在decay系数？**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=2227)
- `0:38:08`**python后端cPython有实现内存池**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=2288)
- `0:38:22`**内存碎片化，nvidia-smi和torch allocated显示的内存也不一样**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=2302)
- `0:38:49`**感觉跟jvm里面的内存管理思想相似，释放并整理内存**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=2329)
- `0:39:04`**python的内存池也是这么做的**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=2344)
- `0:40:35`**也就1024块卡。。。。。。**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=2435)
- `0:41:38`**是回扣，也可能是微软就是钱太多**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=2498)
- `0:46:01`**大batch只是单卡计算量提上去了，实际训练速度可能会下降**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=2761)
- `0:46:21`**这里的计算应该是反向传播的计算？**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=2781)
- `0:46:46`**所以一般来说我只需要关注加速比就可以了是吗？**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=2806)
- `0:47:03`**好多分布式论文不给收敛结果**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=2823)
- `0:47:32`**训练一个100B的模型收敛不现实**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=2852)
- `0:48:26`**gpt-3: 勿 Cue，谢谢**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=2906)
- `0:48:47`**沐神：还不是参数服务器那点小把戏**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=2927)
- `0:49:26`**这为什么也能写论文···**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=2966)
- `0:50:41`**跟我的参数服务器还差一些**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=3041)
- `0:50:59`**我写论文很头疼的事情就是几句话就说完自己的想法了**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=3059)
- `0:51:02`**不是谁都可以发顶会的**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=3062)
- `0:51:51`**GPT：勿cue。。**　[↗](https://www.bilibili.com/video/BV1tY411g7ZT?t=3111)
