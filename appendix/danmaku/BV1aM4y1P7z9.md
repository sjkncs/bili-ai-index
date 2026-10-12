# 弹幕讨论 · 5.3 Boosting【斯坦福21秋季：实用机器学习中文版】

> 视频：[BV1aM4y1P7z9](https://www.bilibili.com/video/BV1aM4y1P7z9)　时长 0:14:42　弹幕总数 **96**　有实质内容 **52** 条　重点标记 **52** 条
>
> 来源：B 站 **跟李沐学AI** 的该集弹幕　快照：**2026-10-13**

## 口径说明（务必先读）

**这些内容全部是观众在视频上发的弹幕，不是经过核实的结论。**

- 其中有价值的：概念解释、类比、勘误、学习方法、延伸阅读线索。
- **也可能有错误的**：弹幕是个人理解，未经作者或权威确认。
  **本页不为其正确性背书，请勿直接引用为事实。**
- 每条带时间戳，点击可跳回视频对应位置自行核对。
- 筛选口径：保留长度 ≥ 10 字符、且不含纯感叹/打卡类噪声的弹幕，共 52 条（占该集弹幕 96 条的 54.2%）；同一句话被多人发送只保留一条并标注发送次数。
- 「重点」标记由关键词打分得出（技术词 + 解释性措辞 + 长度 + 多人重复），共 52 条；**它是启发式排序，不代表正确性，也不代表其余条目无价值。**

## 重点条目

| 时间 | 弹幕 | 发送次数 |
|---|---|---:|
| [0:00:47](https://www.bilibili.com/video/BV1aM4y1P7z9?t=47) | 一个是方差、一个是偏差，醍醐灌顶 | 1 |
| [0:01:18](https://www.bilibili.com/video/BV1aM4y1P7z9?t=78) | 顺序的决策树？Resnet | 1 |
| [0:01:43](https://www.bilibili.com/video/BV1aM4y1P7z9?t=103) | 我记得有种方式是调整权重，对判断错误的样本增大权重，其他减小 | 1 |
| [0:01:55](https://www.bilibili.com/video/BV1aM4y1P7z9?t=115) | 调整样本权重的是Adaboost【刚接触的小白】 | 1 |
| [0:02:48](https://www.bilibili.com/video/BV1aM4y1P7z9?t=168) | “一直搞下去”，瞬间感觉老师萌萌的 | 1 |
| [0:02:51](https://www.bilibili.com/video/BV1aM4y1P7z9?t=171) | 不是时间h_t，应该是第t次 | 1 |
| [0:03:36](https://www.bilibili.com/video/BV1aM4y1P7z9?t=216) | 感觉和用aux  loss一个套路啊 | 1 |
| [0:03:38](https://www.bilibili.com/video/BV1aM4y1P7z9?t=218) | 第二个模型有点自监督？ | 1 |
| [0:04:14](https://www.bilibili.com/video/BV1aM4y1P7z9?t=254) | ht是第t个树模型还是第t+1个树模型 | 1 |
| [0:04:17](https://www.bilibili.com/video/BV1aM4y1P7z9?t=257) | 可不可以理解为，bagging类似并行，boosting类似串行 | 1 |
| [0:04:30](https://www.bilibili.com/video/BV1aM4y1P7z9?t=270) | 这里的f_t(x)是不是就是h_t(x)呀 | 1 |
| [0:04:38](https://www.bilibili.com/video/BV1aM4y1P7z9?t=278) | 这不就是魔改gradient descend? | 1 |
| [0:05:39](https://www.bilibili.com/video/BV1aM4y1P7z9?t=339) | f_t(x): 第i次训练的weak model | 1 |
| [0:06:18](https://www.bilibili.com/video/BV1aM4y1P7z9?t=378) | H是Ht还是Ht+1？ | 1 |
| [0:06:31](https://www.bilibili.com/video/BV1aM4y1P7z9?t=391) | 这里看frideman原文讲的清楚点 | 1 |
| [0:06:32](https://www.bilibili.com/video/BV1aM4y1P7z9?t=392) | 在学校学过，当时没完全懂，现在再看，懂了 | 1 |
| [0:06:35](https://www.bilibili.com/video/BV1aM4y1P7z9?t=395) | 大Ht(x)与小ht(x)啥关系了？ | 1 |
| [0:06:44](https://www.bilibili.com/video/BV1aM4y1P7z9?t=404) | 大H是無數小h綫性組合 | 1 |
| [0:07:03](https://www.bilibili.com/video/BV1aM4y1P7z9?t=423) | 为什么L/H可以等于ft | 1 |
| [0:07:06](https://www.bilibili.com/video/BV1aM4y1P7z9?t=426) | 也不是完全等吧，是成正比的，好像差2倍吧 | 1 |
| [0:07:15](https://www.bilibili.com/video/BV1aM4y1P7z9?t=435) | 把MSE作为损失函数，梯度等于残差 | 1 |
| [0:07:26](https://www.bilibili.com/video/BV1aM4y1P7z9?t=446) | 论文已经开题啦，用的是XGBoost ing | 1 |
| [0:07:29](https://www.bilibili.com/video/BV1aM4y1P7z9?t=449) | 如果loss是mse即L=(H(x)-y)^2,那么梯度dL/dH=y-H(x)即残差h(x)，所以用学校率n*h(x)修正Ht(x) | 1 |
| [0:07:40](https://www.bilibili.com/video/BV1aM4y1P7z9?t=460) | ;;;;;;;;;;;;;;;;;;;;;' | 1 |
| [0:08:20](https://www.bilibili.com/video/BV1aM4y1P7z9?t=500) | 原来大神也会被迫用copy! | 1 |
| [0:08:56](https://www.bilibili.com/video/BV1aM4y1P7z9?t=536) | y的形式不用深拷贝也行 | 1 |
| [0:09:11](https://www.bilibili.com/video/BV1aM4y1P7z9?t=551) | 公式代码很简单，原理可不简单 | 1 |
| [0:09:28](https://www.bilibili.com/video/BV1aM4y1P7z9?t=568) | predict的时候为什么要乘以学习率呢？这样在做residual的时候不是就乘以两次了吗 | 1 |
| [0:09:28](https://www.bilibili.com/video/BV1aM4y1P7z9?t=568) | 为什么求和后要乘学习率呀 | 1 |
| [0:09:31](https://www.bilibili.com/video/BV1aM4y1P7z9?t=571) | 这一步是为了累加各阶段h得到实际模型H，预测阶段和之前训练阶段的操作一致 | 1 |
| [0:09:31](https://www.bilibili.com/video/BV1aM4y1P7z9?t=571) | 两个predict不一样 | 1 |
| [0:09:31](https://www.bilibili.com/video/BV1aM4y1P7z9?t=571) | predict的时候乘以学习率是因为predict的是ht，而下一步residual要用的是Ht；最后一行乘学习率是为了加权每个弱学习器的结果 | 1 |
| [0:09:33](https://www.bilibili.com/video/BV1aM4y1P7z9?t=573) | 这里不清楚的话，可以看看左下角链接里更详细点的幻灯片(7-3) | 1 |
| [0:09:34](https://www.bilibili.com/video/BV1aM4y1P7z9?t=574) | 按原理是每个learner*学习率然后求和，学习率不变，可以提出来，相当于learner求和之后乘学习率 | 1 |
| [0:09:55](https://www.bilibili.com/video/BV1aM4y1P7z9?t=595) | Fire the ppt maker | 1 |
| [0:11:10](https://www.bilibili.com/video/BV1aM4y1P7z9?t=670) | 原来就是你小子叫GBDT啊 | 1 |
| [0:11:14](https://www.bilibili.com/video/BV1aM4y1P7z9?t=674) | 有人在看吗？28号录过 | 1 |
| [0:11:33](https://www.bilibili.com/video/BV1aM4y1P7z9?t=693) | 这里的nlearners指的是什么啊？ | 1 |
| [0:11:37](https://www.bilibili.com/video/BV1aM4y1P7z9?t=697) | boosting弱分类器的个数 | 1 |
| [0:12:36](https://www.bilibili.com/video/BV1aM4y1P7z9?t=756) | 往上翘，就是过拟合？ | 1 |
| [0:12:46](https://www.bilibili.com/video/BV1aM4y1P7z9?t=766) | 训练误差小于验证误差就是过拟合 | 1 |
| [0:12:48](https://www.bilibili.com/video/BV1aM4y1P7z9?t=768) | &lt;- 过拟合是 train error 很低然后 valid error 往上翘 | 1 |
| [0:12:50](https://www.bilibili.com/video/BV1aM4y1P7z9?t=770) | 说往上翘的别误导人了行吗？ | 1 |
| [0:12:53](https://www.bilibili.com/video/BV1aM4y1P7z9?t=773) | train error 和 valid error 之间的都是过拟合吧 | 1 |
| [0:12:58](https://www.bilibili.com/video/BV1aM4y1P7z9?t=778) | 说误导人的别误导人了行吗？ | 1 |
| [0:13:01](https://www.bilibili.com/video/BV1aM4y1P7z9?t=781) | 他问的没错。但实践中要的不是不过拟合，是测试准确率最高 | 1 |
| [0:13:07](https://www.bilibili.com/video/BV1aM4y1P7z9?t=787) | train error和test/valid error差距减小，bias减小，却不保证test/valid error减小。。。 | 1 |
| [0:13:27](https://www.bilibili.com/video/BV1aM4y1P7z9?t=807) | 这如何说明对减少偏差起作用？ | 1 |
| [0:13:31](https://www.bilibili.com/video/BV1aM4y1P7z9?t=811) | GameBOYMicro? | 1 |
| [0:14:14](https://www.bilibili.com/video/BV1aM4y1P7z9?t=854) | 有没有既bagging又boosting的模型啊 | 1 |
| [0:14:40](https://www.bilibili.com/video/BV1aM4y1P7z9?t=880) | bagging需要复杂的树，boosting需要简单的树，怎么既bagging又bossting？ | 1 |
| [0:14:40](https://www.bilibili.com/video/BV1aM4y1P7z9?t=880) | boosting后bagging | 1 |

## 全部有实质内容的弹幕（按时间排序，共 52 条）

- `0:00:47`**一个是方差、一个是偏差，醍醐灌顶**　[↗](https://www.bilibili.com/video/BV1aM4y1P7z9?t=47)
- `0:01:18`**顺序的决策树？Resnet**　[↗](https://www.bilibili.com/video/BV1aM4y1P7z9?t=78)
- `0:01:43`**我记得有种方式是调整权重，对判断错误的样本增大权重，其他减小**　[↗](https://www.bilibili.com/video/BV1aM4y1P7z9?t=103)
- `0:01:55`**调整样本权重的是Adaboost【刚接触的小白】**　[↗](https://www.bilibili.com/video/BV1aM4y1P7z9?t=115)
- `0:02:48`**“一直搞下去”，瞬间感觉老师萌萌的**　[↗](https://www.bilibili.com/video/BV1aM4y1P7z9?t=168)
- `0:02:51`**不是时间h_t，应该是第t次**　[↗](https://www.bilibili.com/video/BV1aM4y1P7z9?t=171)
- `0:03:36`**感觉和用aux  loss一个套路啊**　[↗](https://www.bilibili.com/video/BV1aM4y1P7z9?t=216)
- `0:03:38`**第二个模型有点自监督？**　[↗](https://www.bilibili.com/video/BV1aM4y1P7z9?t=218)
- `0:04:14`**ht是第t个树模型还是第t+1个树模型**　[↗](https://www.bilibili.com/video/BV1aM4y1P7z9?t=254)
- `0:04:17`**可不可以理解为，bagging类似并行，boosting类似串行**　[↗](https://www.bilibili.com/video/BV1aM4y1P7z9?t=257)
- `0:04:30`**这里的f_t(x)是不是就是h_t(x)呀**　[↗](https://www.bilibili.com/video/BV1aM4y1P7z9?t=270)
- `0:04:38`**这不就是魔改gradient descend?**　[↗](https://www.bilibili.com/video/BV1aM4y1P7z9?t=278)
- `0:05:39`**f_t(x): 第i次训练的weak model**　[↗](https://www.bilibili.com/video/BV1aM4y1P7z9?t=339)
- `0:06:18`**H是Ht还是Ht+1？**　[↗](https://www.bilibili.com/video/BV1aM4y1P7z9?t=378)
- `0:06:31`**这里看frideman原文讲的清楚点**　[↗](https://www.bilibili.com/video/BV1aM4y1P7z9?t=391)
- `0:06:32`**在学校学过，当时没完全懂，现在再看，懂了**　[↗](https://www.bilibili.com/video/BV1aM4y1P7z9?t=392)
- `0:06:35`**大Ht(x)与小ht(x)啥关系了？**　[↗](https://www.bilibili.com/video/BV1aM4y1P7z9?t=395)
- `0:06:44`**大H是無數小h綫性組合**　[↗](https://www.bilibili.com/video/BV1aM4y1P7z9?t=404)
- `0:07:03`**为什么L/H可以等于ft**　[↗](https://www.bilibili.com/video/BV1aM4y1P7z9?t=423)
- `0:07:06`**也不是完全等吧，是成正比的，好像差2倍吧**　[↗](https://www.bilibili.com/video/BV1aM4y1P7z9?t=426)
- `0:07:15`**把MSE作为损失函数，梯度等于残差**　[↗](https://www.bilibili.com/video/BV1aM4y1P7z9?t=435)
- `0:07:26`**论文已经开题啦，用的是XGBoost ing**　[↗](https://www.bilibili.com/video/BV1aM4y1P7z9?t=446)
- `0:07:29`**如果loss是mse即L=(H(x)-y)^2,那么梯度dL/dH=y-H(x)即残差h(x)，所以用学校率n*h(x)修正Ht(x)**　[↗](https://www.bilibili.com/video/BV1aM4y1P7z9?t=449)
- `0:07:40`**;;;;;;;;;;;;;;;;;;;;;'**　[↗](https://www.bilibili.com/video/BV1aM4y1P7z9?t=460)
- `0:08:20`**原来大神也会被迫用copy!**　[↗](https://www.bilibili.com/video/BV1aM4y1P7z9?t=500)
- `0:08:56`**y的形式不用深拷贝也行**　[↗](https://www.bilibili.com/video/BV1aM4y1P7z9?t=536)
- `0:09:11`**公式代码很简单，原理可不简单**　[↗](https://www.bilibili.com/video/BV1aM4y1P7z9?t=551)
- `0:09:28`**predict的时候为什么要乘以学习率呢？这样在做residual的时候不是就乘以两次了吗**　[↗](https://www.bilibili.com/video/BV1aM4y1P7z9?t=568)
- `0:09:28`**为什么求和后要乘学习率呀**　[↗](https://www.bilibili.com/video/BV1aM4y1P7z9?t=568)
- `0:09:31`**这一步是为了累加各阶段h得到实际模型H，预测阶段和之前训练阶段的操作一致**　[↗](https://www.bilibili.com/video/BV1aM4y1P7z9?t=571)
- `0:09:31`**两个predict不一样**　[↗](https://www.bilibili.com/video/BV1aM4y1P7z9?t=571)
- `0:09:31`**predict的时候乘以学习率是因为predict的是ht，而下一步residual要用的是Ht；最后一行乘学习率是为了加权每个弱学习器的结果**　[↗](https://www.bilibili.com/video/BV1aM4y1P7z9?t=571)
- `0:09:33`**这里不清楚的话，可以看看左下角链接里更详细点的幻灯片(7-3)**　[↗](https://www.bilibili.com/video/BV1aM4y1P7z9?t=573)
- `0:09:34`**按原理是每个learner*学习率然后求和，学习率不变，可以提出来，相当于learner求和之后乘学习率**　[↗](https://www.bilibili.com/video/BV1aM4y1P7z9?t=574)
- `0:09:55`**Fire the ppt maker**　[↗](https://www.bilibili.com/video/BV1aM4y1P7z9?t=595)
- `0:11:10`**原来就是你小子叫GBDT啊**　[↗](https://www.bilibili.com/video/BV1aM4y1P7z9?t=670)
- `0:11:14`**有人在看吗？28号录过**　[↗](https://www.bilibili.com/video/BV1aM4y1P7z9?t=674)
- `0:11:33`**这里的nlearners指的是什么啊？**　[↗](https://www.bilibili.com/video/BV1aM4y1P7z9?t=693)
- `0:11:37`**boosting弱分类器的个数**　[↗](https://www.bilibili.com/video/BV1aM4y1P7z9?t=697)
- `0:12:36`**往上翘，就是过拟合？**　[↗](https://www.bilibili.com/video/BV1aM4y1P7z9?t=756)
- `0:12:46`**训练误差小于验证误差就是过拟合**　[↗](https://www.bilibili.com/video/BV1aM4y1P7z9?t=766)
- `0:12:48`**&lt;- 过拟合是 train error 很低然后 valid error 往上翘**　[↗](https://www.bilibili.com/video/BV1aM4y1P7z9?t=768)
- `0:12:50`**说往上翘的别误导人了行吗？**　[↗](https://www.bilibili.com/video/BV1aM4y1P7z9?t=770)
- `0:12:53`**train error 和 valid error 之间的都是过拟合吧**　[↗](https://www.bilibili.com/video/BV1aM4y1P7z9?t=773)
- `0:12:58`**说误导人的别误导人了行吗？**　[↗](https://www.bilibili.com/video/BV1aM4y1P7z9?t=778)
- `0:13:01`**他问的没错。但实践中要的不是不过拟合，是测试准确率最高**　[↗](https://www.bilibili.com/video/BV1aM4y1P7z9?t=781)
- `0:13:07`**train error和test/valid error差距减小，bias减小，却不保证test/valid error减小。。。**　[↗](https://www.bilibili.com/video/BV1aM4y1P7z9?t=787)
- `0:13:27`**这如何说明对减少偏差起作用？**　[↗](https://www.bilibili.com/video/BV1aM4y1P7z9?t=807)
- `0:13:31`**GameBOYMicro?**　[↗](https://www.bilibili.com/video/BV1aM4y1P7z9?t=811)
- `0:14:14`**有没有既bagging又boosting的模型啊**　[↗](https://www.bilibili.com/video/BV1aM4y1P7z9?t=854)
- `0:14:40`**bagging需要复杂的树，boosting需要简单的树，怎么既bagging又bossting？**　[↗](https://www.bilibili.com/video/BV1aM4y1P7z9?t=880)
- `0:14:40`**boosting后bagging**　[↗](https://www.bilibili.com/video/BV1aM4y1P7z9?t=880)
