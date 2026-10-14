# 弹幕讨论 · GPipe论文精读【论文精读】

> 视频：[BV1v34y1E7zu](https://www.bilibili.com/video/BV1v34y1E7zu)　时长 0:58:48　弹幕总数 **232**　有实质内容 **101** 条　重点标记 **101** 条
>
> 来源：B 站 **跟李沐学AI** 的该集弹幕　快照：**2026-10-14**

## 口径说明（务必先读）

**这些内容全部是观众在视频上发的弹幕，不是经过核实的结论。**

- 其中有价值的：概念解释、类比、勘误、学习方法、延伸阅读线索。
- **也可能有错误的**：弹幕是个人理解，未经作者或权威确认。
  **本页不为其正确性背书，请勿直接引用为事实。**
- 每条带时间戳，点击可跳回视频对应位置自行核对。
- 筛选口径：保留长度 ≥ 10 字符、且不含纯感叹/打卡类噪声的弹幕，共 101 条（占该集弹幕 232 条的 43.5%）；同一句话被多人发送只保留一条并标注发送次数。
- 「重点」标记由关键词打分得出（技术词 + 解释性措辞 + 长度 + 多人重复），共 101 条；**它是启发式排序，不代表正确性，也不代表其余条目无价值。**

## 重点条目

| 时间 | 弹幕 | 发送次数 |
|---|---|---:|
| [0:00:00](https://www.bilibili.com/video/BV1v34y1E7zu?t=0) | 流水线不应该很直观吗？为什么前人没做呢？是有什么特殊原因吗？ | 1 |
| [0:00:07](https://www.bilibili.com/video/BV1v34y1E7zu?t=7) | 读过诶，来深度学习一下 | 1 |
| [0:00:08](https://www.bilibili.com/video/BV1v34y1E7zu?t=8) | 不和孙雨杉交换人生史 | 1 |
| [0:00:39](https://www.bilibili.com/video/BV1v34y1E7zu?t=39) | CPU技术都弄来了是吧~ | 1 |
| [0:00:45](https://www.bilibili.com/video/BV1v34y1E7zu?t=45) | MEGATRON也要来了吧 | 1 |
| [0:00:47](https://www.bilibili.com/video/BV1v34y1E7zu?t=47) | 这里pipeline会不会和GPU里面的渲染用的pipeline很像 | 1 |
| [0:02:15](https://www.bilibili.com/video/BV1v34y1E7zu?t=135) | 刚投了一篇系统类的paper到neurips…… | 1 |
| [0:03:32](https://www.bilibili.com/video/BV1v34y1E7zu?t=212) | google不是鼓励内部不搞政治么，哈哈哈 | 1 |
| [0:06:02](https://www.bilibili.com/video/BV1v34y1E7zu?t=362) | 系统门槛那么高。。。 | 1 |
| [0:09:08](https://www.bilibili.com/video/BV1v34y1E7zu?t=548) | 现在还用的是64g的内存 | 1 |
| [0:09:16](https://www.bilibili.com/video/BV1v34y1E7zu?t=556) | 我现在用的还是24G | 1 |
| [0:11:01](https://www.bilibili.com/video/BV1v34y1E7zu?t=661) | 奇怪，Megatron-LM 不是发表在 Gpipe 之后吗 | 1 |
| [0:13:45](https://www.bilibili.com/video/BV1v34y1E7zu?t=825) | 3407 is all you need | 1 |
| [0:14:52](https://www.bilibili.com/video/BV1v34y1E7zu?t=892) | 现在国内的开源库，都是这么整的，可谓非常之方便了 | 1 |
| [0:15:13](https://www.bilibili.com/video/BV1v34y1E7zu?t=913) | 你为什么知道这个事情 | 1 |
| [0:15:16](https://www.bilibili.com/video/BV1v34y1E7zu?t=916) | 你为什么知道这个事情（恼） | 1 |
| [0:15:17](https://www.bilibili.com/video/BV1v34y1E7zu?t=917) | 那么你为什么知道这个事情呢 | 1 |
| [0:15:18](https://www.bilibili.com/video/BV1v34y1E7zu?t=918) | 所以你接受这个事情用了多久  狗头 | 1 |
| [0:18:27](https://www.bilibili.com/video/BV1v34y1E7zu?t=1107) | 是因为模型太大载入不进去一个GPU是吗 | 1 |
| [0:18:51](https://www.bilibili.com/video/BV1v34y1E7zu?t=1131) | 和 nvlink 没关系，pcie 通信也可以 | 1 |
| [0:19:48](https://www.bilibili.com/video/BV1v34y1E7zu?t=1188) | 数据并行是为了加速吗？ | 1 |
| [0:19:55](https://www.bilibili.com/video/BV1v34y1E7zu?t=1195) | 数据并行的前提是gpu可以放下整个模型 | 1 |
| [0:20:03](https://www.bilibili.com/video/BV1v34y1E7zu?t=1203) | 数据量太大的情况下用数据并行，模型参数太大的情况下用模型并行，两个都大的话单节点模型并行，多节点之间数据并行 | 1 |
| [0:20:14](https://www.bilibili.com/video/BV1v34y1E7zu?t=1214) | 一个是切明显，一个是切数据 | 1 |
| [0:20:20](https://www.bilibili.com/video/BV1v34y1E7zu?t=1220) | 数据并行解决数据量太大的问题 | 1 |
| [0:20:32](https://www.bilibili.com/video/BV1v34y1E7zu?t=1232) | 有点类似 联邦学习？ | 1 |
| [0:20:44](https://www.bilibili.com/video/BV1v34y1E7zu?t=1244) | 请问这里不用把loss先加起来再算梯度嘛？ | 1 |
| [0:20:49](https://www.bilibili.com/video/BV1v34y1E7zu?t=1249) | 梯度累加比loss加起来算梯度更高效吧，多个梯度相加可以看作多个方向矢量相加。 | 1 |
| [0:21:39](https://www.bilibili.com/video/BV1v34y1E7zu?t=1299) | 这里图(b)的几个F0和B0其实应该分别是F1,F2,F3和B3,B2,B1 | 1 |
| [0:22:02](https://www.bilibili.com/video/BV1v34y1E7zu?t=1322) | 我感觉和Zero3好像 | 1 |
| [0:22:34](https://www.bilibili.com/video/BV1v34y1E7zu?t=1354) | 空洞太多 所以优化就是怎么减少空洞 | 1 |
| [0:22:53](https://www.bilibili.com/video/BV1v34y1E7zu?t=1373) | b图怎么都是F0和B0？ | 1 |
| [0:24:55](https://www.bilibili.com/video/BV1v34y1E7zu?t=1495) | 感觉好像CSAPP里面的流水线 | 1 |
| [0:25:04](https://www.bilibili.com/video/BV1v34y1E7zu?t=1504) | 感觉还是有浪费，只不过是浪费的时间少了 | 1 |
| [0:25:21](https://www.bilibili.com/video/BV1v34y1E7zu?t=1521) | 计算机体系结构的五段流水线 | 1 |
| [0:26:04](https://www.bilibili.com/video/BV1v34y1E7zu?t=1564) | 只是空闲时间少了，不一定总的计算时间少了 | 1 |
| [0:26:05](https://www.bilibili.com/video/BV1v34y1E7zu?t=1565) | 感觉就是dp和mp的融合。 | 1 |
| [0:26:07](https://www.bilibili.com/video/BV1v34y1E7zu?t=1567) | 学过计算机组成理解起来就很容易 | 1 |
| [0:26:15](https://www.bilibili.com/video/BV1v34y1E7zu?t=1575) | 没学过计算机组成原理理解起来也很容易... | 1 |
| [0:26:28](https://www.bilibili.com/video/BV1v34y1E7zu?t=1588) | 但是这相当于要承担x模型切块数大小的额外内存 因为每个小批次都会有一队中间变量 | 1 |
| [0:26:45](https://www.bilibili.com/video/BV1v34y1E7zu?t=1605) | GPU：我不能休息一下吗 | 1 |
| [0:27:03](https://www.bilibili.com/video/BV1v34y1E7zu?t=1623) | 切得无限多bubble区就变成三角形？ | 1 |
| [0:27:10](https://www.bilibili.com/video/BV1v34y1E7zu?t=1630) | 这里微批量的size能超过卡数吗？ | 1 |
| [0:27:19](https://www.bilibili.com/video/BV1v34y1E7zu?t=1639) | 块多，但是通信也有瓶颈吧 | 1 |
| [0:28:12](https://www.bilibili.com/video/BV1v34y1E7zu?t=1692) | 那相比直接数据并行优势是什么呢 | 1 |
| [0:28:15](https://www.bilibili.com/video/BV1v34y1E7zu?t=1695) | 应该还是节省内存开销吧，前面说模型并行的优点就在于节约内存 | 1 |
| [0:28:29](https://www.bilibili.com/video/BV1v34y1E7zu?t=1709) | 纯粹的数据并行能跑起来的前提是一块GPU的显存能塞下整个模型参数+状态量，现在说的流水线并行的前提就是一个GPU塞不完 | 1 |
| [0:29:56](https://www.bilibili.com/video/BV1v34y1E7zu?t=1796) | 后面的微软的zero就是丢掉了一部分吧 | 1 |
| [0:30:16](https://www.bilibili.com/video/BV1v34y1E7zu?t=1816) | 不是算关于w的梯度吗？ | 1 |
| [0:30:36](https://www.bilibili.com/video/BV1v34y1E7zu?t=1836) | 没有说反，BP的核心是反向递推y对x的导数，每一步的结果乘以activation就是对W的偏导 | 1 |
| [0:30:47](https://www.bilibili.com/video/BV1v34y1E7zu?t=1847) | 怎么算雅可比积是另一个问题； 推公式不能直接这么写 | 1 |
| [0:31:39](https://www.bilibili.com/video/BV1v34y1E7zu?t=1899) | 重新算的话也不知道x 了啊 | 1 |
| [0:31:39](https://www.bilibili.com/video/BV1v34y1E7zu?t=1899) | 这里的activation指的应该是x和y吧？ | 1 |
| [0:31:52](https://www.bilibili.com/video/BV1v34y1E7zu?t=1912) | activation 就是激活函数，sigmoid relu这种 | 1 |
| [0:31:55](https://www.bilibili.com/video/BV1v34y1E7zu?t=1915) | 算W的时候也需要X吧 | 1 |
| [0:32:02](https://www.bilibili.com/video/BV1v34y1E7zu?t=1922) | 这里的意思是，x关于z的偏导=W | 1 |
| [0:32:02](https://www.bilibili.com/video/BV1v34y1E7zu?t=1922) | X是输入，肯定是有的 | 1 |
| [0:32:04](https://www.bilibili.com/video/BV1v34y1E7zu?t=1924) | 前面弹幕，W是权重啊，在这个过程中一直是不变量，算个啥呀。W只有最后一步update weights时才有“运算” | 1 |
| [0:32:30](https://www.bilibili.com/video/BV1v34y1E7zu?t=1950) | 可以了解下这篇论文Training Deep Nets with Sublinear Memory Cost，还有pytorch的Gradient Checkpointing | 1 |
| [0:33:06](https://www.bilibili.com/video/BV1v34y1E7zu?t=1986) | 中间变量叫做activation，可能会变得特别大 | 1 |
| [0:33:27](https://www.bilibili.com/video/BV1v34y1E7zu?t=2007) | gradient checkpoints 的思想 | 1 |
| [0:33:53](https://www.bilibili.com/video/BV1v34y1E7zu?t=2033) | 你反向传播的时候这个x 凭什么又还会在呢 | 1 |
| [0:34:38](https://www.bilibili.com/video/BV1v34y1E7zu?t=2078) | Activation Recomputation | 1 |
| [0:34:57](https://www.bilibili.com/video/BV1v34y1E7zu?t=2097) | 这个是不是陈天奇的文章？ | 1 |
| [0:36:05](https://www.bilibili.com/video/BV1v34y1E7zu?t=2165) | 没搞明白为什么不能丢 | 1 |
| [0:38:33](https://www.bilibili.com/video/BV1v34y1E7zu?t=2313) | (L*N)/(M*K) 可以也丢掉吗？ | 1 |
| [0:38:41](https://www.bilibili.com/video/BV1v34y1E7zu?t=2321) | 这里重新forward的性能开销和从CPU内存中取回GPU内存相比哪个开销更大 | 1 |
| [0:38:52](https://www.bilibili.com/video/BV1v34y1E7zu?t=2332) | ←不同硬件/模型不一样，要去取不同的并行配置试出最优解，一般多节点通信开销会远大于节点内的计算开销 | 1 |
| [0:38:56](https://www.bilibili.com/video/BV1v34y1E7zu?t=2336) | 重新计算的开销会小一些，特别是对于 transformer 模型 | 1 |
| [0:39:31](https://www.bilibili.com/video/BV1v34y1E7zu?t=2371) | 似乎这里模型前向的时间和批量大小相关？ | 1 |
| [0:39:52](https://www.bilibili.com/video/BV1v34y1E7zu?t=2392) | 因为很多穷人拿不到多机多卡的入场券，已经被淘汰了 | 1 |
| [0:39:59](https://www.bilibili.com/video/BV1v34y1E7zu?t=2399) | 感觉系统的就是没多少人看 | 1 |
| [0:40:33](https://www.bilibili.com/video/BV1v34y1E7zu?t=2433) | 我不想掌握1000张A100的训练技术吗？是我真的不想吗？ | 1 |
| [0:42:01](https://www.bilibili.com/video/BV1v34y1E7zu?t=2521) | 只跑inference吗 | 1 |
| [0:42:01](https://www.bilibili.com/video/BV1v34y1E7zu?t=2521) | 梯度和优化器的内存呢？ | 1 |
| [0:42:56](https://www.bilibili.com/video/BV1v34y1E7zu?t=2576) | 猜对了，真是陈天奇的... | 1 |
| [0:44:42](https://www.bilibili.com/video/BV1v34y1E7zu?t=2682) | 这个tot应该是总的显存占用 | 1 |
| [0:45:05](https://www.bilibili.com/video/BV1v34y1E7zu?t=2705) | 感觉11.7G和3.15G写反了 | 1 |
| [0:45:08](https://www.bilibili.com/video/BV1v34y1E7zu?t=2708) | 只加了层数，宽度没怎么变？ | 1 |
| [0:45:12](https://www.bilibili.com/video/BV1v34y1E7zu?t=2712) | 19年就训了84B模型吗？ | 1 |
| [0:45:59](https://www.bilibili.com/video/BV1v34y1E7zu?t=2759) | 这里应该是batch size变大了 | 1 |
| [0:47:37](https://www.bilibili.com/video/BV1v34y1E7zu?t=2857) | 就是走PCIE通道吧 | 1 |
| [0:47:39](https://www.bilibili.com/video/BV1v34y1E7zu?t=2859) | P100应该是有PCIE版本的，禁掉NVLINK反而不太容易 | 1 |
| [0:47:55](https://www.bilibili.com/video/BV1v34y1E7zu?t=2875) | 这里的硬件 nvlink 是可以通过设置关掉的，用 pcie 连接。 | 1 |
| [0:47:58](https://www.bilibili.com/video/BV1v34y1E7zu?t=2878) | 但是gpu玩模型并行不用nvlink那相当于故意让gpu自废武功5成 | 1 |
| [0:48:21](https://www.bilibili.com/video/BV1v34y1E7zu?t=2901) | CUDA disable P2P传输可以不走NVLink | 1 |
| [0:48:34](https://www.bilibili.com/video/BV1v34y1E7zu?t=2914) | 没错 GPU之间通过PCIE bridge可以实现P2P通信 | 1 |
| [0:48:43](https://www.bilibili.com/video/BV1v34y1E7zu?t=2923) | 这个没有和数据并行比吧，怎么证明这个呢？ | 1 |
| [0:48:46](https://www.bilibili.com/video/BV1v34y1E7zu?t=2926) | 是说传输的数据小所以通信对性能影响小吗？ | 1 |
| [0:49:58](https://www.bilibili.com/video/BV1v34y1E7zu?t=2998) | 外行看热闹内行看门道 | 1 |
| [0:50:23](https://www.bilibili.com/video/BV1v34y1E7zu?t=3023) | 因为BackProp需要同时计算weight和activation的梯度 | 1 |
| [0:50:37](https://www.bilibili.com/video/BV1v34y1E7zu?t=3037) | 反向传播计算梯度如果是用差分法，那就是要算两次矩阵乘法，所以是前向两倍？ | 1 |
| [0:50:39](https://www.bilibili.com/video/BV1v34y1E7zu?t=3039) | BUBBLE时间GPU的计算是空闲的嘛，那会可以做recompute | 1 |
| [0:51:06](https://www.bilibili.com/video/BV1v34y1E7zu?t=3066) | 这些数据都是怎么统计出来的hh | 1 |
| [0:54:55](https://www.bilibili.com/video/BV1v34y1E7zu?t=3295) | 怎么会相互引用？发表应该有先后顺序 | 1 |
| [0:55:13](https://www.bilibili.com/video/BV1v34y1E7zu?t=3313) | 相互引用是因为论文有v1 v2么？ | 1 |
| [0:56:18](https://www.bilibili.com/video/BV1v34y1E7zu?t=3378) | hhhhhh不如牧神 | 1 |
| [0:56:42](https://www.bilibili.com/video/BV1v34y1E7zu?t=3402) | 做简单的东西别人才会follow。但AF2是反例哈哈 | 1 |
| [0:57:51](https://www.bilibili.com/video/BV1v34y1E7zu?t=3471) | encoder-decoder架构是不是也没有纯decoder那么好切... | 1 |
| [0:58:37](https://www.bilibili.com/video/BV1v34y1E7zu?t=3517) | 。。。怎么理解都无法理解成局限性吧。。。 | 1 |
| [0:58:43](https://www.bilibili.com/video/BV1v34y1E7zu?t=3523) | 以后做同步我就这么说了，可靠性 | 1 |

## 全部有实质内容的弹幕（按时间排序，共 101 条）

- `0:00:00`**流水线不应该很直观吗？为什么前人没做呢？是有什么特殊原因吗？**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=0)
- `0:00:07`**读过诶，来深度学习一下**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=7)
- `0:00:08`**不和孙雨杉交换人生史**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=8)
- `0:00:39`**CPU技术都弄来了是吧~**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=39)
- `0:00:45`**MEGATRON也要来了吧**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=45)
- `0:00:47`**这里pipeline会不会和GPU里面的渲染用的pipeline很像**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=47)
- `0:02:15`**刚投了一篇系统类的paper到neurips……**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=135)
- `0:03:32`**google不是鼓励内部不搞政治么，哈哈哈**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=212)
- `0:06:02`**系统门槛那么高。。。**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=362)
- `0:09:08`**现在还用的是64g的内存**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=548)
- `0:09:16`**我现在用的还是24G**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=556)
- `0:11:01`**奇怪，Megatron-LM 不是发表在 Gpipe 之后吗**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=661)
- `0:13:45`**3407 is all you need**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=825)
- `0:14:52`**现在国内的开源库，都是这么整的，可谓非常之方便了**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=892)
- `0:15:13`**你为什么知道这个事情**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=913)
- `0:15:16`**你为什么知道这个事情（恼）**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=916)
- `0:15:17`**那么你为什么知道这个事情呢**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=917)
- `0:15:18`**所以你接受这个事情用了多久  狗头**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=918)
- `0:18:27`**是因为模型太大载入不进去一个GPU是吗**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=1107)
- `0:18:51`**和 nvlink 没关系，pcie 通信也可以**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=1131)
- `0:19:48`**数据并行是为了加速吗？**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=1188)
- `0:19:55`**数据并行的前提是gpu可以放下整个模型**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=1195)
- `0:20:03`**数据量太大的情况下用数据并行，模型参数太大的情况下用模型并行，两个都大的话单节点模型并行，多节点之间数据并行**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=1203)
- `0:20:14`**一个是切明显，一个是切数据**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=1214)
- `0:20:20`**数据并行解决数据量太大的问题**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=1220)
- `0:20:32`**有点类似 联邦学习？**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=1232)
- `0:20:44`**请问这里不用把loss先加起来再算梯度嘛？**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=1244)
- `0:20:49`**梯度累加比loss加起来算梯度更高效吧，多个梯度相加可以看作多个方向矢量相加。**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=1249)
- `0:21:39`**这里图(b)的几个F0和B0其实应该分别是F1,F2,F3和B3,B2,B1**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=1299)
- `0:22:02`**我感觉和Zero3好像**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=1322)
- `0:22:34`**空洞太多 所以优化就是怎么减少空洞**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=1354)
- `0:22:53`**b图怎么都是F0和B0？**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=1373)
- `0:24:55`**感觉好像CSAPP里面的流水线**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=1495)
- `0:25:04`**感觉还是有浪费，只不过是浪费的时间少了**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=1504)
- `0:25:21`**计算机体系结构的五段流水线**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=1521)
- `0:26:04`**只是空闲时间少了，不一定总的计算时间少了**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=1564)
- `0:26:05`**感觉就是dp和mp的融合。**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=1565)
- `0:26:07`**学过计算机组成理解起来就很容易**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=1567)
- `0:26:15`**没学过计算机组成原理理解起来也很容易...**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=1575)
- `0:26:28`**但是这相当于要承担x模型切块数大小的额外内存 因为每个小批次都会有一队中间变量**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=1588)
- `0:26:45`**GPU：我不能休息一下吗**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=1605)
- `0:27:03`**切得无限多bubble区就变成三角形？**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=1623)
- `0:27:10`**这里微批量的size能超过卡数吗？**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=1630)
- `0:27:19`**块多，但是通信也有瓶颈吧**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=1639)
- `0:28:12`**那相比直接数据并行优势是什么呢**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=1692)
- `0:28:15`**应该还是节省内存开销吧，前面说模型并行的优点就在于节约内存**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=1695)
- `0:28:29`**纯粹的数据并行能跑起来的前提是一块GPU的显存能塞下整个模型参数+状态量，现在说的流水线并行的前提就是一个GPU塞不完**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=1709)
- `0:29:56`**后面的微软的zero就是丢掉了一部分吧**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=1796)
- `0:30:16`**不是算关于w的梯度吗？**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=1816)
- `0:30:36`**没有说反，BP的核心是反向递推y对x的导数，每一步的结果乘以activation就是对W的偏导**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=1836)
- `0:30:47`**怎么算雅可比积是另一个问题； 推公式不能直接这么写**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=1847)
- `0:31:39`**重新算的话也不知道x 了啊**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=1899)
- `0:31:39`**这里的activation指的应该是x和y吧？**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=1899)
- `0:31:52`**activation 就是激活函数，sigmoid relu这种**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=1912)
- `0:31:55`**算W的时候也需要X吧**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=1915)
- `0:32:02`**这里的意思是，x关于z的偏导=W**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=1922)
- `0:32:02`**X是输入，肯定是有的**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=1922)
- `0:32:04`**前面弹幕，W是权重啊，在这个过程中一直是不变量，算个啥呀。W只有最后一步update weights时才有“运算”**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=1924)
- `0:32:30`**可以了解下这篇论文Training Deep Nets with Sublinear Memory Cost，还有pytorch的Gradient Checkpointing**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=1950)
- `0:33:06`**中间变量叫做activation，可能会变得特别大**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=1986)
- `0:33:27`**gradient checkpoints 的思想**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=2007)
- `0:33:53`**你反向传播的时候这个x 凭什么又还会在呢**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=2033)
- `0:34:38`**Activation Recomputation**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=2078)
- `0:34:57`**这个是不是陈天奇的文章？**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=2097)
- `0:36:05`**没搞明白为什么不能丢**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=2165)
- `0:38:33`**(L*N)/(M*K) 可以也丢掉吗？**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=2313)
- `0:38:41`**这里重新forward的性能开销和从CPU内存中取回GPU内存相比哪个开销更大**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=2321)
- `0:38:52`**←不同硬件/模型不一样，要去取不同的并行配置试出最优解，一般多节点通信开销会远大于节点内的计算开销**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=2332)
- `0:38:56`**重新计算的开销会小一些，特别是对于 transformer 模型**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=2336)
- `0:39:31`**似乎这里模型前向的时间和批量大小相关？**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=2371)
- `0:39:52`**因为很多穷人拿不到多机多卡的入场券，已经被淘汰了**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=2392)
- `0:39:59`**感觉系统的就是没多少人看**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=2399)
- `0:40:33`**我不想掌握1000张A100的训练技术吗？是我真的不想吗？**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=2433)
- `0:42:01`**只跑inference吗**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=2521)
- `0:42:01`**梯度和优化器的内存呢？**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=2521)
- `0:42:56`**猜对了，真是陈天奇的...**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=2576)
- `0:44:42`**这个tot应该是总的显存占用**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=2682)
- `0:45:05`**感觉11.7G和3.15G写反了**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=2705)
- `0:45:08`**只加了层数，宽度没怎么变？**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=2708)
- `0:45:12`**19年就训了84B模型吗？**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=2712)
- `0:45:59`**这里应该是batch size变大了**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=2759)
- `0:47:37`**就是走PCIE通道吧**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=2857)
- `0:47:39`**P100应该是有PCIE版本的，禁掉NVLINK反而不太容易**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=2859)
- `0:47:55`**这里的硬件 nvlink 是可以通过设置关掉的，用 pcie 连接。**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=2875)
- `0:47:58`**但是gpu玩模型并行不用nvlink那相当于故意让gpu自废武功5成**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=2878)
- `0:48:21`**CUDA disable P2P传输可以不走NVLink**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=2901)
- `0:48:34`**没错 GPU之间通过PCIE bridge可以实现P2P通信**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=2914)
- `0:48:43`**这个没有和数据并行比吧，怎么证明这个呢？**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=2923)
- `0:48:46`**是说传输的数据小所以通信对性能影响小吗？**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=2926)
- `0:49:58`**外行看热闹内行看门道**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=2998)
- `0:50:23`**因为BackProp需要同时计算weight和activation的梯度**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=3023)
- `0:50:37`**反向传播计算梯度如果是用差分法，那就是要算两次矩阵乘法，所以是前向两倍？**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=3037)
- `0:50:39`**BUBBLE时间GPU的计算是空闲的嘛，那会可以做recompute**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=3039)
- `0:51:06`**这些数据都是怎么统计出来的hh**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=3066)
- `0:54:55`**怎么会相互引用？发表应该有先后顺序**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=3295)
- `0:55:13`**相互引用是因为论文有v1 v2么？**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=3313)
- `0:56:18`**hhhhhh不如牧神**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=3378)
- `0:56:42`**做简单的东西别人才会follow。但AF2是反例哈哈**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=3402)
- `0:57:51`**encoder-decoder架构是不是也没有纯decoder那么好切...**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=3471)
- `0:58:37`**。。。怎么理解都无法理解成局限性吧。。。**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=3517)
- `0:58:43`**以后做同步我就这么说了，可靠性**　[↗](https://www.bilibili.com/video/BV1v34y1E7zu?t=3523)
