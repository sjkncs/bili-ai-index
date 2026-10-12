# 弹幕讨论 · 11.1 迁移学习【斯坦福21秋季：实用机器学习中文版】

> 视频：[BV1SL4y1t7ZL](https://www.bilibili.com/video/BV1SL4y1t7ZL)　时长 0:29:58　弹幕总数 **232**　有实质内容 **75** 条　重点标记 **75** 条
>
> 来源：B 站 **跟李沐学AI** 的该集弹幕　快照：**2026-10-12**

## 口径说明（务必先读）

**这些内容全部是观众在视频上发的弹幕，不是经过核实的结论。**

- 其中有价值的：概念解释、类比、勘误、学习方法、延伸阅读线索。
- **也可能有错误的**：弹幕是个人理解，未经作者或权威确认。
  **本页不为其正确性背书，请勿直接引用为事实。**
- 每条带时间戳，点击可跳回视频对应位置自行核对。
- 筛选口径：保留长度 ≥ 10 字符、且不含纯感叹/打卡类噪声的弹幕，共 75 条（占该集弹幕 232 条的 32.3%）；同一句话被多人发送只保留一条并标注发送次数。
- 「重点」标记由关键词打分得出（技术词 + 解释性措辞 + 长度 + 多人重复），共 75 条；**它是启发式排序，不代表正确性，也不代表其余条目无价值。**

## 重点条目

| 时间 | 弹幕 | 发送次数 |
|---|---|---:|
| [0:00:59](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=59) | 迁移学习等同于finetune吗 | 1 |
| [0:01:11](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=71) | fine tunning只是迁移学习的一种方法吧 | 1 |
| [0:01:36](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=96) | 迁移学习导论，你值得拥有 | 1 |
| [0:02:45](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=165) | 第二个，为什么不直接训练目标的模型，而训练相近的任务？ | 1 |
| [0:02:49](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=169) | 因为训练目标模型能用的数据量太小 | 1 |
| [0:02:49](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=169) | 因为目标任务没有足够的带标签的数据集拿来训练 | 1 |
| [0:03:04](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=184) | 迁移学习解决小样本问题的 | 1 |
| [0:03:24](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=204) | 这一段本身有点Transfer Learning的感觉 | 1 |
| [0:03:24](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=204) | 这刚开始就醍醐灌顶了哈哈哈哈哈 | 1 |
| [0:06:29](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=389) | 1.2M是1.2百万张？ | 1 |
| [0:06:41](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=401) | 1024x1024看成百万 | 1 |
| [0:08:12](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=492) | encoder-decoder | 1 |
| [0:08:31](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=511) | 会不会被分类成猪... | 1 |
| [0:08:38](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=518) | 所有的都看做编码器还挺有道理呢 | 1 |
| [0:09:14](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=554) | 线性可分的特征，是特证相互独立？ | 1 |
| [0:09:16](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=556) | 线性可分的特征就是类似感知机模型那种 | 1 |
| [0:09:17](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=557) | 现在10个人，你们好 | 1 |
| [0:09:24](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=564) | 怎么找预训练模型，以及它训练用的数据集？ | 1 |
| [0:09:30](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=570) | 现在16个人,你们好 | 1 |
| [0:09:30](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=570) | 泛化能力，可以理解为在我们在大的数据集中训练出来的模型，在别的问题上也是可以帮到忙的一种能力 | 1 |
| [0:09:47](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=587) | 2022-10-10 | 1 |
| [0:09:51](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=591) | 2023 3.15 十个同学你们好 | 1 |
| [0:09:57](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=597) | 2022-11-09 | 1 |
| [0:10:06](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=606) | 以前不知道，其实即便不同数据，只要使用同样网络如CNN，原来训练的模型参数还是可用的，最后几层微调就行。 | 1 |
| [0:10:28](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=628) | 图片的话，直接用Whisper这种的迁移不是更好？ | 1 |
| [0:10:28](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=628) | 22.5.14还在封控中 | 1 |
| [0:10:44](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=644) | 22.7.30  学习学习 | 1 |
| [0:11:07](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=667) | 基本上都是imagenet预训练好的吗？有没有其他大型的数据集 | 1 |
| [0:11:10](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=670) | 有的，office-home和visda | 1 |
| [0:11:15](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=675) | 图像转到语言结构有差异就不迁移了吧 | 1 |
| [0:13:28](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=808) | 老师嗓子有些哑，注意身体 | 1 |
| [0:14:08](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=848) | 微调的思想和残差网络有一点像 | 1 |
| [0:14:59](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=899) | 2022年4月22日晚，上海 | 1 |
| [0:15:03](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=903) | 请问迁移学习会改变假设空间吗 | 1 |
| [0:15:08](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=908) | 5.25 青岛，活在b站的研究僧 | 1 |
| [0:15:09](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=909) | 迁移学习用小的学习率和少量的epoch | 1 |
| [0:15:22](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=922) | 我觉得应该不会，假设空间还是不变，只是finetune把初始的f'设置得跟目标f比较近 | 1 |
| [0:15:49](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=949) | 正常不是0.001吗 | 1 |
| [0:15:58](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=958) | 是不是梯度下降的内容？ | 1 |
| [0:16:34](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=994) | 要冻结预训练层的吧，通常来讲 | 1 |
| [0:16:36](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=996) | batch_size | 1 |
| [0:16:57](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1017) | 限制是正则化防止过拟合吗 | 1 |
| [0:17:04](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1024) | 限制本身也是一种先验知识的正则化 | 1 |
| [0:17:29](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1049) | finetune的数据集小，模型比较大，容易过拟合 | 1 |
| [0:17:38](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1058) | 比较泛化能力有哪些指标呢 | 1 |
| [0:17:41](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1061) | overfitting | 1 |
| [0:17:49](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1069) | 泛化就看测试集表现吧 | 1 |
| [0:17:59](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1079) | 终于明白了为什么要微调 | 1 |
| [0:18:45](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1125) | 底层，具体是什么层？特征图分辨率比较小的图？ | 1 |
| [0:18:53](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1133) | 低是指提取的特征是微弱的 | 1 |
| [0:19:04](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1144) | 越靠近输入层，能提取到的信息越局部，越“小” | 1 |
| [0:19:12](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1152) | 但是其实不freeze，梯度也几乎影响不到bottom吧。。 | 1 |
| [0:19:28](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1168) | 前面的你没理解李沐的意思，他的意思是防止过拟合 | 1 |
| [0:20:29](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1229) | 底层是深度网络开始的那几层？ | 1 |
| [0:20:40](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1240) | 浅层才是深度网络开始的那几层 | 1 |
| [0:20:57](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1257) | 因为学习不管什么任务，都需要去理解局部的特征，比如“这是一个圆圈”，这是一个边等等 | 1 |
| [0:20:57](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1257) | 底层值指的是最开始的几层，是提取局部特征的，越靠近输出越靠近你的语义空间，越全局，所以最开始的几层可以考虑降低学习率 | 1 |
| [0:21:20](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1280) | 这种是不是就是冻结训练鸭 | 1 |
| [0:21:42](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1302) | 所以一般是固定多少层？ | 1 |
| [0:21:44](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1304) | 对于transformer这种模型应该固定哪些层 | 1 |
| [0:21:46](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1306) | 那要样本差不多才行吧 | 1 |
| [0:22:16](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1336) | 沐神，可以出一期图像识别实战的视频吗？从代码简单迁移训练，验证，到后面的测试。谢谢！ | 1 |
| [0:22:28](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1348) | Hugging face | 1 |
| [0:22:36](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1356) | huggingface？ | 1 |
| [0:23:00](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1380) | huggingface的库也不错 | 1 |
| [0:23:28](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1408) | 大佬觉得一般般hhhhhhhhhh | 1 |
| [0:23:45](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1425) | 用起来 比较好的收哦 | 1 |
| [0:23:58](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1438) | 这里的权重指的是什么权重呀 | 1 |
| [0:24:07](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1447) | 可以理解为决策函数的系数吧 | 1 |
| [0:24:16](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1456) | 现在是不是用 HF ? | 1 |
| [0:24:27](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1467) | pytorch 本身也可以做吧，timm 还有其他用处吗 | 1 |
| [0:25:04](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1504) | 某些层的学习率改成0是怎么实现的？ | 1 |
| [0:28:36](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1716) | 这个倒不是玄学，别整天到处刷 | 1 |
| [0:29:07](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1747) | 讲的很透彻 今天的组会到此结束 | 1 |
| [0:29:38](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1778) | Bert模型没有解码器 | 1 |

## 全部有实质内容的弹幕（按时间排序，共 75 条）

- `0:00:59`**迁移学习等同于finetune吗**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=59)
- `0:01:11`**fine tunning只是迁移学习的一种方法吧**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=71)
- `0:01:36`**迁移学习导论，你值得拥有**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=96)
- `0:02:45`**第二个，为什么不直接训练目标的模型，而训练相近的任务？**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=165)
- `0:02:49`**因为训练目标模型能用的数据量太小**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=169)
- `0:02:49`**因为目标任务没有足够的带标签的数据集拿来训练**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=169)
- `0:03:04`**迁移学习解决小样本问题的**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=184)
- `0:03:24`**这一段本身有点Transfer Learning的感觉**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=204)
- `0:03:24`**这刚开始就醍醐灌顶了哈哈哈哈哈**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=204)
- `0:06:29`**1.2M是1.2百万张？**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=389)
- `0:06:41`**1024x1024看成百万**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=401)
- `0:08:12`**encoder-decoder**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=492)
- `0:08:31`**会不会被分类成猪...**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=511)
- `0:08:38`**所有的都看做编码器还挺有道理呢**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=518)
- `0:09:14`**线性可分的特征，是特证相互独立？**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=554)
- `0:09:16`**线性可分的特征就是类似感知机模型那种**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=556)
- `0:09:17`**现在10个人，你们好**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=557)
- `0:09:24`**怎么找预训练模型，以及它训练用的数据集？**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=564)
- `0:09:30`**现在16个人,你们好**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=570)
- `0:09:30`**泛化能力，可以理解为在我们在大的数据集中训练出来的模型，在别的问题上也是可以帮到忙的一种能力**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=570)
- `0:09:47`**2022-10-10**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=587)
- `0:09:51`**2023 3.15 十个同学你们好**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=591)
- `0:09:57`**2022-11-09**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=597)
- `0:10:06`**以前不知道，其实即便不同数据，只要使用同样网络如CNN，原来训练的模型参数还是可用的，最后几层微调就行。**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=606)
- `0:10:28`**图片的话，直接用Whisper这种的迁移不是更好？**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=628)
- `0:10:28`**22.5.14还在封控中**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=628)
- `0:10:44`**22.7.30  学习学习**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=644)
- `0:11:07`**基本上都是imagenet预训练好的吗？有没有其他大型的数据集**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=667)
- `0:11:10`**有的，office-home和visda**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=670)
- `0:11:15`**图像转到语言结构有差异就不迁移了吧**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=675)
- `0:13:28`**老师嗓子有些哑，注意身体**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=808)
- `0:14:08`**微调的思想和残差网络有一点像**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=848)
- `0:14:59`**2022年4月22日晚，上海**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=899)
- `0:15:03`**请问迁移学习会改变假设空间吗**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=903)
- `0:15:08`**5.25 青岛，活在b站的研究僧**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=908)
- `0:15:09`**迁移学习用小的学习率和少量的epoch**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=909)
- `0:15:22`**我觉得应该不会，假设空间还是不变，只是finetune把初始的f'设置得跟目标f比较近**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=922)
- `0:15:49`**正常不是0.001吗**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=949)
- `0:15:58`**是不是梯度下降的内容？**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=958)
- `0:16:34`**要冻结预训练层的吧，通常来讲**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=994)
- `0:16:36`**batch_size**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=996)
- `0:16:57`**限制是正则化防止过拟合吗**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1017)
- `0:17:04`**限制本身也是一种先验知识的正则化**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1024)
- `0:17:29`**finetune的数据集小，模型比较大，容易过拟合**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1049)
- `0:17:38`**比较泛化能力有哪些指标呢**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1058)
- `0:17:41`**overfitting**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1061)
- `0:17:49`**泛化就看测试集表现吧**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1069)
- `0:17:59`**终于明白了为什么要微调**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1079)
- `0:18:45`**底层，具体是什么层？特征图分辨率比较小的图？**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1125)
- `0:18:53`**低是指提取的特征是微弱的**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1133)
- `0:19:04`**越靠近输入层，能提取到的信息越局部，越“小”**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1144)
- `0:19:12`**但是其实不freeze，梯度也几乎影响不到bottom吧。。**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1152)
- `0:19:28`**前面的你没理解李沐的意思，他的意思是防止过拟合**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1168)
- `0:20:29`**底层是深度网络开始的那几层？**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1229)
- `0:20:40`**浅层才是深度网络开始的那几层**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1240)
- `0:20:57`**因为学习不管什么任务，都需要去理解局部的特征，比如“这是一个圆圈”，这是一个边等等**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1257)
- `0:20:57`**底层值指的是最开始的几层，是提取局部特征的，越靠近输出越靠近你的语义空间，越全局，所以最开始的几层可以考虑降低学习率**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1257)
- `0:21:20`**这种是不是就是冻结训练鸭**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1280)
- `0:21:42`**所以一般是固定多少层？**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1302)
- `0:21:44`**对于transformer这种模型应该固定哪些层**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1304)
- `0:21:46`**那要样本差不多才行吧**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1306)
- `0:22:16`**沐神，可以出一期图像识别实战的视频吗？从代码简单迁移训练，验证，到后面的测试。谢谢！**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1336)
- `0:22:28`**Hugging face**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1348)
- `0:22:36`**huggingface？**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1356)
- `0:23:00`**huggingface的库也不错**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1380)
- `0:23:28`**大佬觉得一般般hhhhhhhhhh**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1408)
- `0:23:45`**用起来 比较好的收哦**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1425)
- `0:23:58`**这里的权重指的是什么权重呀**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1438)
- `0:24:07`**可以理解为决策函数的系数吧**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1447)
- `0:24:16`**现在是不是用 HF ?**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1456)
- `0:24:27`**pytorch 本身也可以做吧，timm 还有其他用处吗**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1467)
- `0:25:04`**某些层的学习率改成0是怎么实现的？**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1504)
- `0:28:36`**这个倒不是玄学，别整天到处刷**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1716)
- `0:29:07`**讲的很透彻 今天的组会到此结束**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1747)
- `0:29:38`**Bert模型没有解码器**　[↗](https://www.bilibili.com/video/BV1SL4y1t7ZL?t=1778)
