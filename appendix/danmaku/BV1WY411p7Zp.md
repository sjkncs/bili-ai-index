# 弹幕讨论 · 10.1 深度神经网络架构【斯坦福21秋季：实用机器学习中文版】

> 视频：[BV1WY411p7Zp](https://www.bilibili.com/video/BV1WY411p7Zp)　时长 0:29:43　弹幕总数 **89**　有实质内容 **35** 条　重点标记 **35** 条
>
> 来源：B 站 **跟李沐学AI** 的该集弹幕　快照：**2026-10-12**

## 口径说明（务必先读）

**这些内容全部是观众在视频上发的弹幕，不是经过核实的结论。**

- 其中有价值的：概念解释、类比、勘误、学习方法、延伸阅读线索。
- **也可能有错误的**：弹幕是个人理解，未经作者或权威确认。
  **本页不为其正确性背书，请勿直接引用为事实。**
- 每条带时间戳，点击可跳回视频对应位置自行核对。
- 筛选口径：保留长度 ≥ 10 字符、且不含纯感叹/打卡类噪声的弹幕，共 35 条（占该集弹幕 89 条的 39.3%）；同一句话被多人发送只保留一条并标注发送次数。
- 「重点」标记由关键词打分得出（技术词 + 解释性措辞 + 长度 + 多人重复），共 35 条；**它是启发式排序，不代表正确性，也不代表其余条目无价值。**

## 重点条目

| 时间 | 弹幕 | 发送次数 |
|---|---|---:|
| [0:00:28](https://www.bilibili.com/video/BV1WY411p7Zp?t=28) | 而且今天是镜像，Amazon和美人尖报漏的 | 1 |
| [0:01:42](https://www.bilibili.com/video/BV1WY411p7Zp?t=102) | 大年除夕，居然还有一个小伙伴陪我在看，新年快乐哇 | 1 |
| [0:02:09](https://www.bilibili.com/video/BV1WY411p7Zp?t=129) | 防止某个权重影响太大 | 1 |
| [0:02:56](https://www.bilibili.com/video/BV1WY411p7Zp?t=176) | lipschitz连续 | 1 |
| [0:03:56](https://www.bilibili.com/video/BV1WY411p7Zp?t=236) | 端午节看了3天 觉得自己棒棒哒 | 1 |
| [0:04:30](https://www.bilibili.com/video/BV1WY411p7Zp?t=270) | 像人脑从认知x突然转向y，认知方向重要，认知水平也很重要 | 1 |
| [0:04:37](https://www.bilibili.com/video/BV1WY411p7Zp?t=277) | 贝塔和batchnorn有什么联系嘛 | 1 |
| [0:04:38](https://www.bilibili.com/video/BV1WY411p7Zp?t=278) | 为什么归一化可以实现这样？ | 1 |
| [0:05:07](https://www.bilibili.com/video/BV1WY411p7Zp?t=307) | 这门课从短袖讲到了长袖 | 1 |
| [0:07:45](https://www.bilibili.com/video/BV1WY411p7Zp?t=465) | 一般对图片来说是先高后宽吧 | 1 |
| [0:11:17](https://www.bilibili.com/video/BV1WY411p7Zp?t=677) | standard normal和normal的区别吗 | 1 |
| [0:11:17](https://www.bilibili.com/video/BV1WY411p7Zp?t=677) | 归一化是标准化的一个实现方式吧 | 1 |
| [0:13:57](https://www.bilibili.com/video/BV1WY411p7Zp?t=837) | 不是乘以2吧  **2是做平方 | 1 |
| [0:14:43](https://www.bilibili.com/video/BV1WY411p7Zp?t=883) | 应该是(1,c,1,1) | 1 |
| [0:14:49](https://www.bilibili.com/video/BV1WY411p7Zp?t=889) | 这里讲错了，应该是(1,c,1,1)，得到的是每个通道的均值，就可以沿通道维度做 Normalization | 1 |
| [0:14:51](https://www.bilibili.com/video/BV1WY411p7Zp?t=891) | (n,c,w,h) ==&gt; 0,2,3维求均值,keepdim --&gt; (1,c,1,1)   \|\|\|   dim=1，keepdim --&gt; (n,1,w,h) | 1 |
| [0:14:56](https://www.bilibili.com/video/BV1WY411p7Zp?t=896) | 确实应该是按照0，2，3维求均值然后第1维保留 | 1 |
| [0:15:03](https://www.bilibili.com/video/BV1WY411p7Zp?t=903) | (1, c, 1, 1) | 1 |
| [0:15:08](https://www.bilibili.com/video/BV1WY411p7Zp?t=908) | 应该是对0,2,3维取平均吧 | 1 |
| [0:15:08](https://www.bilibili.com/video/BV1WY411p7Zp?t=908) | 这里是不是不太对？感觉应该写成dim=1， keepdim=True | 1 |
| [0:15:20](https://www.bilibili.com/video/BV1WY411p7Zp?t=920) | 没错啊,是对每个样本的特征求均值 | 1 |
| [0:15:27](https://www.bilibili.com/video/BV1WY411p7Zp?t=927) | 不应该是对当前batch内的所有样本，求各列（特征）的均值吗？ | 1 |
| [0:17:40](https://www.bilibili.com/video/BV1WY411p7Zp?t=1060) | 原来实现有这么多细节 | 1 |
| [0:18:49](https://www.bilibili.com/video/BV1WY411p7Zp?t=1129) | convnext也用啦，开卷 | 1 |
| [0:21:41](https://www.bilibili.com/video/BV1WY411p7Zp?t=1301) | 就是一个样本的某层上所有特征图, 做标准化 | 1 |
| [0:22:40](https://www.bilibili.com/video/BV1WY411p7Zp?t=1360) | 这俩交错起来会是个啥... | 1 |
| [0:23:24](https://www.bilibili.com/video/BV1WY411p7Zp?t=1404) | 就是每个句子各自算均值和方差 | 1 |
| [0:24:00](https://www.bilibili.com/video/BV1WY411p7Zp?t=1440) | 不用保存，不用保存统计参数？ | 1 |
| [0:24:08](https://www.bilibili.com/video/BV1WY411p7Zp?t=1448) | 从和邻居比变成和自己比 | 1 |
| [0:26:06](https://www.bilibili.com/video/BV1WY411p7Zp?t=1566) | 多试试说不定就发现物理意义了 | 1 |
| [0:27:08](https://www.bilibili.com/video/BV1WY411p7Zp?t=1628) | 每个地方都搞一下。。。 | 1 |
| [0:27:38](https://www.bilibili.com/video/BV1WY411p7Zp?t=1658) | 究竟人脑是怎么运作的？ | 1 |
| [0:27:43](https://www.bilibili.com/video/BV1WY411p7Zp?t=1663) | BN一定要稳定！ 否则不要用！ | 1 |
| [0:27:46](https://www.bilibili.com/video/BV1WY411p7Zp?t=1666) | GAN貌似Instancenorm用的比较多 | 1 |
| [0:28:59](https://www.bilibili.com/video/BV1WY411p7Zp?t=1739) | 归一化或标准化感觉等同于人脑使用抽象逻辑认知不同事物的相通性 | 1 |

## 全部有实质内容的弹幕（按时间排序，共 35 条）

- `0:00:28`**而且今天是镜像，Amazon和美人尖报漏的**　[↗](https://www.bilibili.com/video/BV1WY411p7Zp?t=28)
- `0:01:42`**大年除夕，居然还有一个小伙伴陪我在看，新年快乐哇**　[↗](https://www.bilibili.com/video/BV1WY411p7Zp?t=102)
- `0:02:09`**防止某个权重影响太大**　[↗](https://www.bilibili.com/video/BV1WY411p7Zp?t=129)
- `0:02:56`**lipschitz连续**　[↗](https://www.bilibili.com/video/BV1WY411p7Zp?t=176)
- `0:03:56`**端午节看了3天 觉得自己棒棒哒**　[↗](https://www.bilibili.com/video/BV1WY411p7Zp?t=236)
- `0:04:30`**像人脑从认知x突然转向y，认知方向重要，认知水平也很重要**　[↗](https://www.bilibili.com/video/BV1WY411p7Zp?t=270)
- `0:04:37`**贝塔和batchnorn有什么联系嘛**　[↗](https://www.bilibili.com/video/BV1WY411p7Zp?t=277)
- `0:04:38`**为什么归一化可以实现这样？**　[↗](https://www.bilibili.com/video/BV1WY411p7Zp?t=278)
- `0:05:07`**这门课从短袖讲到了长袖**　[↗](https://www.bilibili.com/video/BV1WY411p7Zp?t=307)
- `0:07:45`**一般对图片来说是先高后宽吧**　[↗](https://www.bilibili.com/video/BV1WY411p7Zp?t=465)
- `0:11:17`**standard normal和normal的区别吗**　[↗](https://www.bilibili.com/video/BV1WY411p7Zp?t=677)
- `0:11:17`**归一化是标准化的一个实现方式吧**　[↗](https://www.bilibili.com/video/BV1WY411p7Zp?t=677)
- `0:13:57`**不是乘以2吧  **2是做平方**　[↗](https://www.bilibili.com/video/BV1WY411p7Zp?t=837)
- `0:14:43`**应该是(1,c,1,1)**　[↗](https://www.bilibili.com/video/BV1WY411p7Zp?t=883)
- `0:14:49`**这里讲错了，应该是(1,c,1,1)，得到的是每个通道的均值，就可以沿通道维度做 Normalization**　[↗](https://www.bilibili.com/video/BV1WY411p7Zp?t=889)
- `0:14:51`**(n,c,w,h) ==&gt; 0,2,3维求均值,keepdim --&gt; (1,c,1,1)   \|\|\|   dim=1，keepdim --&gt; (n,1,w,h)**　[↗](https://www.bilibili.com/video/BV1WY411p7Zp?t=891)
- `0:14:56`**确实应该是按照0，2，3维求均值然后第1维保留**　[↗](https://www.bilibili.com/video/BV1WY411p7Zp?t=896)
- `0:15:03`**(1, c, 1, 1)**　[↗](https://www.bilibili.com/video/BV1WY411p7Zp?t=903)
- `0:15:08`**应该是对0,2,3维取平均吧**　[↗](https://www.bilibili.com/video/BV1WY411p7Zp?t=908)
- `0:15:08`**这里是不是不太对？感觉应该写成dim=1， keepdim=True**　[↗](https://www.bilibili.com/video/BV1WY411p7Zp?t=908)
- `0:15:20`**没错啊,是对每个样本的特征求均值**　[↗](https://www.bilibili.com/video/BV1WY411p7Zp?t=920)
- `0:15:27`**不应该是对当前batch内的所有样本，求各列（特征）的均值吗？**　[↗](https://www.bilibili.com/video/BV1WY411p7Zp?t=927)
- `0:17:40`**原来实现有这么多细节**　[↗](https://www.bilibili.com/video/BV1WY411p7Zp?t=1060)
- `0:18:49`**convnext也用啦，开卷**　[↗](https://www.bilibili.com/video/BV1WY411p7Zp?t=1129)
- `0:21:41`**就是一个样本的某层上所有特征图, 做标准化**　[↗](https://www.bilibili.com/video/BV1WY411p7Zp?t=1301)
- `0:22:40`**这俩交错起来会是个啥...**　[↗](https://www.bilibili.com/video/BV1WY411p7Zp?t=1360)
- `0:23:24`**就是每个句子各自算均值和方差**　[↗](https://www.bilibili.com/video/BV1WY411p7Zp?t=1404)
- `0:24:00`**不用保存，不用保存统计参数？**　[↗](https://www.bilibili.com/video/BV1WY411p7Zp?t=1440)
- `0:24:08`**从和邻居比变成和自己比**　[↗](https://www.bilibili.com/video/BV1WY411p7Zp?t=1448)
- `0:26:06`**多试试说不定就发现物理意义了**　[↗](https://www.bilibili.com/video/BV1WY411p7Zp?t=1566)
- `0:27:08`**每个地方都搞一下。。。**　[↗](https://www.bilibili.com/video/BV1WY411p7Zp?t=1628)
- `0:27:38`**究竟人脑是怎么运作的？**　[↗](https://www.bilibili.com/video/BV1WY411p7Zp?t=1658)
- `0:27:43`**BN一定要稳定！ 否则不要用！**　[↗](https://www.bilibili.com/video/BV1WY411p7Zp?t=1663)
- `0:27:46`**GAN貌似Instancenorm用的比较多**　[↗](https://www.bilibili.com/video/BV1WY411p7Zp?t=1666)
- `0:28:59`**归一化或标准化感觉等同于人脑使用抽象逻辑认知不同事物的相通性**　[↗](https://www.bilibili.com/video/BV1WY411p7Zp?t=1739)
