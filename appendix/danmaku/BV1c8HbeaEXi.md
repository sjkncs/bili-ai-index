# 弹幕讨论 · Llama 3.1论文精读 · 5. 模型训练过程【论文精读·54】

> 视频：[BV1c8HbeaEXi](https://www.bilibili.com/video/BV1c8HbeaEXi)　时长 0:10:42　弹幕总数 **50**　有实质内容 **17** 条　重点标记 **17** 条
>
> 来源：B 站 **跟李沐学AI** 的该集弹幕　快照：**2026-10-12**

## 口径说明（务必先读）

**这些内容全部是观众在视频上发的弹幕，不是经过核实的结论。**

- 其中有价值的：概念解释、类比、勘误、学习方法、延伸阅读线索。
- **也可能有错误的**：弹幕是个人理解，未经作者或权威确认。
  **本页不为其正确性背书，请勿直接引用为事实。**
- 每条带时间戳，点击可跳回视频对应位置自行核对。
- 筛选口径：保留长度 ≥ 10 字符、且不含纯感叹/打卡类噪声的弹幕，共 17 条（占该集弹幕 50 条的 34.0%）；同一句话被多人发送只保留一条并标注发送次数。
- 「重点」标记由关键词打分得出（技术词 + 解释性措辞 + 长度 + 多人重复），共 17 条；**它是启发式排序，不代表正确性，也不代表其余条目无价值。**

## 重点条目

| 时间 | 弹幕 | 发送次数 |
|---|---|---:|
| [0:00:14](https://www.bilibili.com/video/BV1c8HbeaEXi?t=14) | 导师又回来了，太开心了 | 1 |
| [0:00:33](https://www.bilibili.com/video/BV1c8HbeaEXi?t=33) | 对于修练者来说，丹方是最珍贵的 | 1 |
| [0:01:40](https://www.bilibili.com/video/BV1c8HbeaEXi?t=100) | 4000000的mini batch。。。 | 1 |
| [0:02:50](https://www.bilibili.com/video/BV1c8HbeaEXi?t=170) | 小bs不应该随机性更大吗 | 2 |
| [0:02:56](https://www.bilibili.com/video/BV1c8HbeaEXi?t=176) | 为什么不是大的batchsize的数据分布更均匀训练更稳定？ | 1 |
| [0:04:12](https://www.bilibili.com/video/BV1c8HbeaEXi?t=252) | 而在中国则是一成不变的 | 1 |
| [0:04:21](https://www.bilibili.com/video/BV1c8HbeaEXi?t=261) | 而在中国是永远不变的 | 1 |
| [0:04:48](https://www.bilibili.com/video/BV1c8HbeaEXi?t=288) | 数据那节有提过给数据质量评级 | 1 |
| [0:06:35](https://www.bilibili.com/video/BV1c8HbeaEXi?t=395) | 不做SFT就跑MMLU分数不会很低吗 | 1 |
| [0:06:46](https://www.bilibili.com/video/BV1c8HbeaEXi?t=406) | 所以在这篇报告在结果那个部分放置的都是5shot和COT的结果 | 1 |
| [0:06:54](https://www.bilibili.com/video/BV1c8HbeaEXi?t=414) | 感觉这里的收敛是看ppl而非acc吧 | 1 |
| [0:08:19](https://www.bilibili.com/video/BV1c8HbeaEXi?t=499) | 学习率降成零，什么用途？ | 1 |
| [0:08:25](https://www.bilibili.com/video/BV1c8HbeaEXi?t=505) | 学习率是慢慢降成零的，一直在调参 | 1 |
| [0:09:10](https://www.bilibili.com/video/BV1c8HbeaEXi?t=550) | 不是bagging，是直接参数层面平均 | 1 |
| [0:09:43](https://www.bilibili.com/video/BV1c8HbeaEXi?t=583) | 全是工程 没有一点理论保证 | 1 |
| [0:10:19](https://www.bilibili.com/video/BV1c8HbeaEXi?t=619) | 还算是简单？？？？？？ | 1 |
| [0:10:26](https://www.bilibili.com/video/BV1c8HbeaEXi?t=626) | 复杂主要还是因为他的模型大。这个流程确实已经很简单了。‘ | 1 |

## 全部有实质内容的弹幕（按时间排序，共 17 条）

- `0:00:14`**导师又回来了，太开心了**　[↗](https://www.bilibili.com/video/BV1c8HbeaEXi?t=14)
- `0:00:33`**对于修练者来说，丹方是最珍贵的**　[↗](https://www.bilibili.com/video/BV1c8HbeaEXi?t=33)
- `0:01:40`**4000000的mini batch。。。**　[↗](https://www.bilibili.com/video/BV1c8HbeaEXi?t=100)
- `0:02:50`**小bs不应该随机性更大吗**（×2）　[↗](https://www.bilibili.com/video/BV1c8HbeaEXi?t=170)
- `0:02:56`**为什么不是大的batchsize的数据分布更均匀训练更稳定？**　[↗](https://www.bilibili.com/video/BV1c8HbeaEXi?t=176)
- `0:04:12`**而在中国则是一成不变的**　[↗](https://www.bilibili.com/video/BV1c8HbeaEXi?t=252)
- `0:04:21`**而在中国是永远不变的**　[↗](https://www.bilibili.com/video/BV1c8HbeaEXi?t=261)
- `0:04:48`**数据那节有提过给数据质量评级**　[↗](https://www.bilibili.com/video/BV1c8HbeaEXi?t=288)
- `0:06:35`**不做SFT就跑MMLU分数不会很低吗**　[↗](https://www.bilibili.com/video/BV1c8HbeaEXi?t=395)
- `0:06:46`**所以在这篇报告在结果那个部分放置的都是5shot和COT的结果**　[↗](https://www.bilibili.com/video/BV1c8HbeaEXi?t=406)
- `0:06:54`**感觉这里的收敛是看ppl而非acc吧**　[↗](https://www.bilibili.com/video/BV1c8HbeaEXi?t=414)
- `0:08:19`**学习率降成零，什么用途？**　[↗](https://www.bilibili.com/video/BV1c8HbeaEXi?t=499)
- `0:08:25`**学习率是慢慢降成零的，一直在调参**　[↗](https://www.bilibili.com/video/BV1c8HbeaEXi?t=505)
- `0:09:10`**不是bagging，是直接参数层面平均**　[↗](https://www.bilibili.com/video/BV1c8HbeaEXi?t=550)
- `0:09:43`**全是工程 没有一点理论保证**　[↗](https://www.bilibili.com/video/BV1c8HbeaEXi?t=583)
- `0:10:19`**还算是简单？？？？？？**　[↗](https://www.bilibili.com/video/BV1c8HbeaEXi?t=619)
- `0:10:26`**复杂主要还是因为他的模型大。这个流程确实已经很简单了。‘**　[↗](https://www.bilibili.com/video/BV1c8HbeaEXi?t=626)
