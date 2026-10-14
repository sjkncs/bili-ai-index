# 弹幕讨论 · 3.5 多层感知机【斯坦福21秋季：实用机器学习中文版】

> 视频：[BV1ST4y1R7uC](https://www.bilibili.com/video/BV1ST4y1R7uC)　时长 0:11:44　弹幕总数 **98**　有实质内容 **44** 条　重点标记 **44** 条
>
> 来源：B 站 **跟李沐学AI** 的该集弹幕　快照：**2026-10-14**

## 口径说明（务必先读）

**这些内容全部是观众在视频上发的弹幕，不是经过核实的结论。**

- 其中有价值的：概念解释、类比、勘误、学习方法、延伸阅读线索。
- **也可能有错误的**：弹幕是个人理解，未经作者或权威确认。
  **本页不为其正确性背书，请勿直接引用为事实。**
- 每条带时间戳，点击可跳回视频对应位置自行核对。
- 筛选口径：保留长度 ≥ 10 字符、且不含纯感叹/打卡类噪声的弹幕，共 44 条（占该集弹幕 98 条的 44.9%）；同一句话被多人发送只保留一条并标注发送次数。
- 「重点」标记由关键词打分得出（技术词 + 解释性措辞 + 长度 + 多人重复），共 44 条；**它是启发式排序，不代表正确性，也不代表其余条目无价值。**

## 重点条目

| 时间 | 弹幕 | 发送次数 |
|---|---|---:|
| [0:00:31](https://www.bilibili.com/video/BV1ST4y1R7uC?t=31) | 可以报考斯坦福（不是 | 1 |
| [0:00:33](https://www.bilibili.com/video/BV1ST4y1R7uC?t=33) | 激发了对之前课程的兴趣 | 1 |
| [0:00:33](https://www.bilibili.com/video/BV1ST4y1R7uC?t=33) | 真的激发起我对动手学深度wan | 1 |
| [0:01:29](https://www.bilibili.com/video/BV1ST4y1R7uC?t=89) | 这句话真的是茅塞顿开了 | 1 |
| [0:01:43](https://www.bilibili.com/video/BV1ST4y1R7uC?t=103) | 神经网络更懂机器学习 | 1 |
| [0:01:51](https://www.bilibili.com/video/BV1ST4y1R7uC?t=111) | 这个吴恩达老师没讲，补充了 | 1 |
| [0:01:56](https://www.bilibili.com/video/BV1ST4y1R7uC?t=116) | 有字幕的呀，自己点开就行了呀 | 1 |
| [0:02:19](https://www.bilibili.com/video/BV1ST4y1R7uC?t=139) | 评论区有大佬写字幕了 | 1 |
| [0:02:33](https://www.bilibili.com/video/BV1ST4y1R7uC?t=153) | 大数量级的数据和计算 | 1 |
| [0:03:23](https://www.bilibili.com/video/BV1ST4y1R7uC?t=203) | 晚上好 正在一起看的其他9个朋友 | 1 |
| [0:03:39](https://www.bilibili.com/video/BV1ST4y1R7uC?t=219) | 晚上好，和我一起看的俩人 | 1 |
| [0:03:47](https://www.bilibili.com/video/BV1ST4y1R7uC?t=227) | fully connected layer | 1 |
| [0:04:35](https://www.bilibili.com/video/BV1ST4y1R7uC?t=275) | dense稠密层 全连接层 | 1 |
| [0:04:42](https://www.bilibili.com/video/BV1ST4y1R7uC?t=282) | 就相当于m是样本数，n是特征数 | 1 |
| [0:04:48](https://www.bilibili.com/video/BV1ST4y1R7uC?t=288) | m是样本数的理解是错误的 | 1 |
| [0:04:52](https://www.bilibili.com/video/BV1ST4y1R7uC?t=292) | 注意liner regression 的时候w是 特征数x 1，y_hat = x w +b 这里形式相似，但是意义完全不同 | 1 |
| [0:05:05](https://www.bilibili.com/video/BV1ST4y1R7uC?t=305) | 这里m是隐藏层的向量维度 | 1 |
| [0:05:13](https://www.bilibili.com/video/BV1ST4y1R7uC?t=313) | 那这里的m是分类的label数量么？ | 1 |
| [0:05:18](https://www.bilibili.com/video/BV1ST4y1R7uC?t=318) | m好像是你想要的特征维数 | 1 |
| [0:05:18](https://www.bilibili.com/video/BV1ST4y1R7uC?t=318) | 感觉如果是单层感知机的话那m就是label数，但如果是多层的话就不一定 | 1 |
| [0:05:21](https://www.bilibili.com/video/BV1ST4y1R7uC?t=321) | n是特征维数，m是类别数，这里没有提到label数量 | 1 |
| [0:05:30](https://www.bilibili.com/video/BV1ST4y1R7uC?t=330) | 单层感知机 就是前面的线性模型  就是稠密层线性层全全链接层 | 1 |
| [0:05:31](https://www.bilibili.com/video/BV1ST4y1R7uC?t=331) | m就是分类的个数，比如有猫狗未知三类，m就是3 | 1 |
| [0:06:37](https://www.bilibili.com/video/BV1ST4y1R7uC?t=397) | 用ReLU的神经网络计算比较高效，但如果学习率很大，更新后不一定能被激活，所以ReLU的变种也很常用 | 1 |
| [0:07:22](https://www.bilibili.com/video/BV1ST4y1R7uC?t=442) | 为什么relu是非线性的？ | 1 |
| [0:07:26](https://www.bilibili.com/video/BV1ST4y1R7uC?t=446) | ←即答：被掰了一下，不是一根线直到底，虽然它还是很直 | 1 |
| [0:07:27](https://www.bilibili.com/video/BV1ST4y1R7uC?t=447) | relu把直线变成射线， 多条射线组合出来救折线了 | 1 |
| [0:07:32](https://www.bilibili.com/video/BV1ST4y1R7uC?t=452) | 为什么relu是线性的？ | 1 |
| [0:07:35](https://www.bilibili.com/video/BV1ST4y1R7uC?t=455) | 刚不是才讲了吗 你耳朵被炮打了 | 1 |
| [0:07:36](https://www.bilibili.com/video/BV1ST4y1R7uC?t=456) | relu中间有不可微的点 | 1 |
| [0:07:46](https://www.bilibili.com/video/BV1ST4y1R7uC?t=466) | RELU在x=0时不可导 | 1 |
| [0:08:27](https://www.bilibili.com/video/BV1ST4y1R7uC?t=507) | 二维看，线性是过原点的直线 | 1 |
| [0:08:58](https://www.bilibili.com/video/BV1ST4y1R7uC?t=538) | 2021/10/28 | 1 |
| [0:09:06](https://www.bilibili.com/video/BV1ST4y1R7uC?t=546) | 输出层可以根据问题选恒等函数，softmax | 1 |
| [0:09:11](https://www.bilibili.com/video/BV1ST4y1R7uC?t=551) | 2022/01/01 | 1 |
| [0:10:31](https://www.bilibili.com/video/BV1ST4y1R7uC?t=631) | ---------- | 1 |
| [0:10:52](https://www.bilibili.com/video/BV1ST4y1R7uC?t=652) | num_inputs和num_hiddens我觉得写反了 | 1 |
| [0:11:02](https://www.bilibili.com/video/BV1ST4y1R7uC?t=662) | 说反的，是没有从数学角度转到编程角度 | 1 |
| [0:11:06](https://www.bilibili.com/video/BV1ST4y1R7uC?t=666) | sorry, why *0.01? | 1 |
| [0:11:23](https://www.bilibili.com/video/BV1ST4y1R7uC?t=683) | 因为激活函数存在的意义，就是将两个线性运算合并而失去多层的意义 | 1 |
| [0:11:23](https://www.bilibili.com/video/BV1ST4y1R7uC?t=683) | 为什么输出层不需要激活函数呢 | 1 |
| [0:11:25](https://www.bilibili.com/video/BV1ST4y1R7uC?t=685) | 应该是对的。和nn.Linear不一样；这里应该是直接的矩阵乘法 | 1 |
| [0:11:27](https://www.bilibili.com/video/BV1ST4y1R7uC?t=687) | 因为你这一层直接输出了，不用再激活去进入下一个隐藏层了 | 1 |
| [0:11:38](https://www.bilibili.com/video/BV1ST4y1R7uC?t=698) | 全体起立，respect！！！！ | 1 |

## 全部有实质内容的弹幕（按时间排序，共 44 条）

- `0:00:31`**可以报考斯坦福（不是**　[↗](https://www.bilibili.com/video/BV1ST4y1R7uC?t=31)
- `0:00:33`**激发了对之前课程的兴趣**　[↗](https://www.bilibili.com/video/BV1ST4y1R7uC?t=33)
- `0:00:33`**真的激发起我对动手学深度wan**　[↗](https://www.bilibili.com/video/BV1ST4y1R7uC?t=33)
- `0:01:29`**这句话真的是茅塞顿开了**　[↗](https://www.bilibili.com/video/BV1ST4y1R7uC?t=89)
- `0:01:43`**神经网络更懂机器学习**　[↗](https://www.bilibili.com/video/BV1ST4y1R7uC?t=103)
- `0:01:51`**这个吴恩达老师没讲，补充了**　[↗](https://www.bilibili.com/video/BV1ST4y1R7uC?t=111)
- `0:01:56`**有字幕的呀，自己点开就行了呀**　[↗](https://www.bilibili.com/video/BV1ST4y1R7uC?t=116)
- `0:02:19`**评论区有大佬写字幕了**　[↗](https://www.bilibili.com/video/BV1ST4y1R7uC?t=139)
- `0:02:33`**大数量级的数据和计算**　[↗](https://www.bilibili.com/video/BV1ST4y1R7uC?t=153)
- `0:03:23`**晚上好 正在一起看的其他9个朋友**　[↗](https://www.bilibili.com/video/BV1ST4y1R7uC?t=203)
- `0:03:39`**晚上好，和我一起看的俩人**　[↗](https://www.bilibili.com/video/BV1ST4y1R7uC?t=219)
- `0:03:47`**fully connected layer**　[↗](https://www.bilibili.com/video/BV1ST4y1R7uC?t=227)
- `0:04:35`**dense稠密层 全连接层**　[↗](https://www.bilibili.com/video/BV1ST4y1R7uC?t=275)
- `0:04:42`**就相当于m是样本数，n是特征数**　[↗](https://www.bilibili.com/video/BV1ST4y1R7uC?t=282)
- `0:04:48`**m是样本数的理解是错误的**　[↗](https://www.bilibili.com/video/BV1ST4y1R7uC?t=288)
- `0:04:52`**注意liner regression 的时候w是 特征数x 1，y_hat = x w +b 这里形式相似，但是意义完全不同**　[↗](https://www.bilibili.com/video/BV1ST4y1R7uC?t=292)
- `0:05:05`**这里m是隐藏层的向量维度**　[↗](https://www.bilibili.com/video/BV1ST4y1R7uC?t=305)
- `0:05:13`**那这里的m是分类的label数量么？**　[↗](https://www.bilibili.com/video/BV1ST4y1R7uC?t=313)
- `0:05:18`**m好像是你想要的特征维数**　[↗](https://www.bilibili.com/video/BV1ST4y1R7uC?t=318)
- `0:05:18`**感觉如果是单层感知机的话那m就是label数，但如果是多层的话就不一定**　[↗](https://www.bilibili.com/video/BV1ST4y1R7uC?t=318)
- `0:05:21`**n是特征维数，m是类别数，这里没有提到label数量**　[↗](https://www.bilibili.com/video/BV1ST4y1R7uC?t=321)
- `0:05:30`**单层感知机 就是前面的线性模型  就是稠密层线性层全全链接层**　[↗](https://www.bilibili.com/video/BV1ST4y1R7uC?t=330)
- `0:05:31`**m就是分类的个数，比如有猫狗未知三类，m就是3**　[↗](https://www.bilibili.com/video/BV1ST4y1R7uC?t=331)
- `0:06:37`**用ReLU的神经网络计算比较高效，但如果学习率很大，更新后不一定能被激活，所以ReLU的变种也很常用**　[↗](https://www.bilibili.com/video/BV1ST4y1R7uC?t=397)
- `0:07:22`**为什么relu是非线性的？**　[↗](https://www.bilibili.com/video/BV1ST4y1R7uC?t=442)
- `0:07:26`**←即答：被掰了一下，不是一根线直到底，虽然它还是很直**　[↗](https://www.bilibili.com/video/BV1ST4y1R7uC?t=446)
- `0:07:27`**relu把直线变成射线， 多条射线组合出来救折线了**　[↗](https://www.bilibili.com/video/BV1ST4y1R7uC?t=447)
- `0:07:32`**为什么relu是线性的？**　[↗](https://www.bilibili.com/video/BV1ST4y1R7uC?t=452)
- `0:07:35`**刚不是才讲了吗 你耳朵被炮打了**　[↗](https://www.bilibili.com/video/BV1ST4y1R7uC?t=455)
- `0:07:36`**relu中间有不可微的点**　[↗](https://www.bilibili.com/video/BV1ST4y1R7uC?t=456)
- `0:07:46`**RELU在x=0时不可导**　[↗](https://www.bilibili.com/video/BV1ST4y1R7uC?t=466)
- `0:08:27`**二维看，线性是过原点的直线**　[↗](https://www.bilibili.com/video/BV1ST4y1R7uC?t=507)
- `0:08:58`**2021/10/28**　[↗](https://www.bilibili.com/video/BV1ST4y1R7uC?t=538)
- `0:09:06`**输出层可以根据问题选恒等函数，softmax**　[↗](https://www.bilibili.com/video/BV1ST4y1R7uC?t=546)
- `0:09:11`**2022/01/01**　[↗](https://www.bilibili.com/video/BV1ST4y1R7uC?t=551)
- `0:10:31`**----------**　[↗](https://www.bilibili.com/video/BV1ST4y1R7uC?t=631)
- `0:10:52`**num_inputs和num_hiddens我觉得写反了**　[↗](https://www.bilibili.com/video/BV1ST4y1R7uC?t=652)
- `0:11:02`**说反的，是没有从数学角度转到编程角度**　[↗](https://www.bilibili.com/video/BV1ST4y1R7uC?t=662)
- `0:11:06`**sorry, why *0.01?**　[↗](https://www.bilibili.com/video/BV1ST4y1R7uC?t=666)
- `0:11:23`**因为激活函数存在的意义，就是将两个线性运算合并而失去多层的意义**　[↗](https://www.bilibili.com/video/BV1ST4y1R7uC?t=683)
- `0:11:23`**为什么输出层不需要激活函数呢**　[↗](https://www.bilibili.com/video/BV1ST4y1R7uC?t=683)
- `0:11:25`**应该是对的。和nn.Linear不一样；这里应该是直接的矩阵乘法**　[↗](https://www.bilibili.com/video/BV1ST4y1R7uC?t=685)
- `0:11:27`**因为你这一层直接输出了，不用再激活去进入下一个隐藏层了**　[↗](https://www.bilibili.com/video/BV1ST4y1R7uC?t=687)
- `0:11:38`**全体起立，respect！！！！**　[↗](https://www.bilibili.com/video/BV1ST4y1R7uC?t=698)
