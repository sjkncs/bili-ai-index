# 弹幕讨论 · 3.1 8分钟机器学习介绍【斯坦福21秋季：实用机器学习中文版】

> 视频：[BV1Nv411u7bW](https://www.bilibili.com/video/BV1Nv411u7bW)　时长 0:08:43　弹幕总数 **60**　有实质内容 **26** 条　重点标记 **26** 条
>
> 来源：B 站 **跟李沐学AI** 的该集弹幕　快照：**2026-10-12**

## 口径说明（务必先读）

**这些内容全部是观众在视频上发的弹幕，不是经过核实的结论。**

- 其中有价值的：概念解释、类比、勘误、学习方法、延伸阅读线索。
- **也可能有错误的**：弹幕是个人理解，未经作者或权威确认。
  **本页不为其正确性背书，请勿直接引用为事实。**
- 每条带时间戳，点击可跳回视频对应位置自行核对。
- 筛选口径：保留长度 ≥ 10 字符、且不含纯感叹/打卡类噪声的弹幕，共 26 条（占该集弹幕 60 条的 43.3%）；同一句话被多人发送只保留一条并标注发送次数。
- 「重点」标记由关键词打分得出（技术词 + 解释性措辞 + 长度 + 多人重复），共 26 条；**它是启发式排序，不代表正确性，也不代表其余条目无价值。**

## 重点条目

| 时间 | 弹幕 | 发送次数 |
|---|---|---:|
| [0:00:38](https://www.bilibili.com/video/BV1Nv411u7bW?t=38) | 半监督的图标真的会被笑死 | 1 |
| [0:00:57](https://www.bilibili.com/video/BV1Nv411u7bW?t=57) | 自监督 跟监督学习有什么区别？不就是通过词向量生成标注？ | 1 |
| [0:00:57](https://www.bilibili.com/video/BV1Nv411u7bW?t=57) | 我以为自监督是无监督学习的一种 | 1 |
| [0:01:14](https://www.bilibili.com/video/BV1Nv411u7bW?t=74) | 标注通过深度学习模型生成的，就叫自监督？ | 1 |
| [0:01:17](https://www.bilibili.com/video/BV1Nv411u7bW?t=77) | 自监督可是有标号的，无监督没有标号 | 1 |
| [0:01:22](https://www.bilibili.com/video/BV1Nv411u7bW?t=82) | 自监督是可以理解成无监督的 | 1 |
| [0:01:26](https://www.bilibili.com/video/BV1Nv411u7bW?t=86) | 自监督可以理解为监督吧  只是经过一个模型得转换 | 1 |
| [0:01:34](https://www.bilibili.com/video/BV1Nv411u7bW?t=94) | 应该是无监督是自监督的一种 | 1 |
| [0:01:55](https://www.bilibili.com/video/BV1Nv411u7bW?t=115) | 每一种算法旁边的icon也是对应的，太用心了 | 1 |
| [0:02:10](https://www.bilibili.com/video/BV1Nv411u7bW?t=130) | 这样估计会使样本不均匀？ | 1 |
| [0:02:39](https://www.bilibili.com/video/BV1Nv411u7bW?t=159) | 期待老师再出一本机器学习的书， | 1 |
| [0:02:43](https://www.bilibili.com/video/BV1Nv411u7bW?t=163) | GAN 是生成概率密度分布？ | 1 |
| [0:05:41](https://www.bilibili.com/video/BV1Nv411u7bW?t=341) | 自己判断一下是不是口误呗 | 1 |
| [0:05:45](https://www.bilibili.com/video/BV1Nv411u7bW?t=345) | 平方的话就不会存在负数了 更好判断准确性如何 | 1 |
| [0:05:49](https://www.bilibili.com/video/BV1Nv411u7bW?t=349) | 一般前面还有个1/2，这样的好处是，求导的时候，和前面1/2消掉，计算方便 | 1 |
| [0:05:52](https://www.bilibili.com/video/BV1Nv411u7bW?t=352) | 他没说开根号 说以 是平方 谢谢大家 | 1 |
| [0:06:02](https://www.bilibili.com/video/BV1Nv411u7bW?t=362) | 说明损失值不关心正负，只关心绝对值的大小 | 1 |
| [0:06:08](https://www.bilibili.com/video/BV1Nv411u7bW?t=368) | 开平方后可以惩罚错的更多的结果 | 1 |
| [0:06:13](https://www.bilibili.com/video/BV1Nv411u7bW?t=373) | 这是求平方，不是开平方。 | 1 |
| [0:06:29](https://www.bilibili.com/video/BV1Nv411u7bW?t=389) | 这个就是方差，不难理解 | 1 |
| [0:06:38](https://www.bilibili.com/video/BV1Nv411u7bW?t=398) | 平方不是为了之后求导方便吗 | 1 |
| [0:06:41](https://www.bilibili.com/video/BV1Nv411u7bW?t=401) | obj + loss =  min(loss) | 1 |
| [0:06:42](https://www.bilibili.com/video/BV1Nv411u7bW?t=402) | 防止损失值有正有负，损失被抵消了 | 1 |
| [0:06:55](https://www.bilibili.com/video/BV1Nv411u7bW?t=415) | 用一个模型能监督另一个模型的训练结果并自动调整吗？ | 1 |
| [0:06:58](https://www.bilibili.com/video/BV1Nv411u7bW?t=418) | 实在是非常有收获，谢谢老师 | 5 |
| [0:07:25](https://www.bilibili.com/video/BV1Nv411u7bW?t=445) | 二次方可导，凸函数优化。 | 1 |

## 全部有实质内容的弹幕（按时间排序，共 26 条）

- `0:00:38`**半监督的图标真的会被笑死**　[↗](https://www.bilibili.com/video/BV1Nv411u7bW?t=38)
- `0:00:57`**自监督 跟监督学习有什么区别？不就是通过词向量生成标注？**　[↗](https://www.bilibili.com/video/BV1Nv411u7bW?t=57)
- `0:00:57`**我以为自监督是无监督学习的一种**　[↗](https://www.bilibili.com/video/BV1Nv411u7bW?t=57)
- `0:01:14`**标注通过深度学习模型生成的，就叫自监督？**　[↗](https://www.bilibili.com/video/BV1Nv411u7bW?t=74)
- `0:01:17`**自监督可是有标号的，无监督没有标号**　[↗](https://www.bilibili.com/video/BV1Nv411u7bW?t=77)
- `0:01:22`**自监督是可以理解成无监督的**　[↗](https://www.bilibili.com/video/BV1Nv411u7bW?t=82)
- `0:01:26`**自监督可以理解为监督吧  只是经过一个模型得转换**　[↗](https://www.bilibili.com/video/BV1Nv411u7bW?t=86)
- `0:01:34`**应该是无监督是自监督的一种**　[↗](https://www.bilibili.com/video/BV1Nv411u7bW?t=94)
- `0:01:55`**每一种算法旁边的icon也是对应的，太用心了**　[↗](https://www.bilibili.com/video/BV1Nv411u7bW?t=115)
- `0:02:10`**这样估计会使样本不均匀？**　[↗](https://www.bilibili.com/video/BV1Nv411u7bW?t=130)
- `0:02:39`**期待老师再出一本机器学习的书，**　[↗](https://www.bilibili.com/video/BV1Nv411u7bW?t=159)
- `0:02:43`**GAN 是生成概率密度分布？**　[↗](https://www.bilibili.com/video/BV1Nv411u7bW?t=163)
- `0:05:41`**自己判断一下是不是口误呗**　[↗](https://www.bilibili.com/video/BV1Nv411u7bW?t=341)
- `0:05:45`**平方的话就不会存在负数了 更好判断准确性如何**　[↗](https://www.bilibili.com/video/BV1Nv411u7bW?t=345)
- `0:05:49`**一般前面还有个1/2，这样的好处是，求导的时候，和前面1/2消掉，计算方便**　[↗](https://www.bilibili.com/video/BV1Nv411u7bW?t=349)
- `0:05:52`**他没说开根号 说以 是平方 谢谢大家**　[↗](https://www.bilibili.com/video/BV1Nv411u7bW?t=352)
- `0:06:02`**说明损失值不关心正负，只关心绝对值的大小**　[↗](https://www.bilibili.com/video/BV1Nv411u7bW?t=362)
- `0:06:08`**开平方后可以惩罚错的更多的结果**　[↗](https://www.bilibili.com/video/BV1Nv411u7bW?t=368)
- `0:06:13`**这是求平方，不是开平方。**　[↗](https://www.bilibili.com/video/BV1Nv411u7bW?t=373)
- `0:06:29`**这个就是方差，不难理解**　[↗](https://www.bilibili.com/video/BV1Nv411u7bW?t=389)
- `0:06:38`**平方不是为了之后求导方便吗**　[↗](https://www.bilibili.com/video/BV1Nv411u7bW?t=398)
- `0:06:41`**obj + loss =  min(loss)**　[↗](https://www.bilibili.com/video/BV1Nv411u7bW?t=401)
- `0:06:42`**防止损失值有正有负，损失被抵消了**　[↗](https://www.bilibili.com/video/BV1Nv411u7bW?t=402)
- `0:06:55`**用一个模型能监督另一个模型的训练结果并自动调整吗？**　[↗](https://www.bilibili.com/video/BV1Nv411u7bW?t=415)
- `0:06:58`**实在是非常有收获，谢谢老师**（×5）　[↗](https://www.bilibili.com/video/BV1Nv411u7bW?t=418)
- `0:07:25`**二次方可导，凸函数优化。**　[↗](https://www.bilibili.com/video/BV1Nv411u7bW?t=445)
