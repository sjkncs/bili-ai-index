# 弹幕讨论 · 5.4 Stacking【斯坦福21秋季：实用机器学习中文版】

> 视频：[BV1PZ4y197CX](https://www.bilibili.com/video/BV1PZ4y197CX)　时长 0:22:03　弹幕总数 **197**　有实质内容 **93** 条　重点标记 **93** 条
>
> 来源：B 站 **跟李沐学AI** 的该集弹幕　快照：**2026-10-14**

## 口径说明（务必先读）

**这些内容全部是观众在视频上发的弹幕，不是经过核实的结论。**

- 其中有价值的：概念解释、类比、勘误、学习方法、延伸阅读线索。
- **也可能有错误的**：弹幕是个人理解，未经作者或权威确认。
  **本页不为其正确性背书，请勿直接引用为事实。**
- 每条带时间戳，点击可跳回视频对应位置自行核对。
- 筛选口径：保留长度 ≥ 10 字符、且不含纯感叹/打卡类噪声的弹幕，共 93 条（占该集弹幕 197 条的 47.2%）；同一句话被多人发送只保留一条并标注发送次数。
- 「重点」标记由关键词打分得出（技术词 + 解释性措辞 + 长度 + 多人重复），共 93 条；**它是启发式排序，不代表正确性，也不代表其余条目无价值。**

## 重点条目

| 时间 | 弹幕 | 发送次数 |
|---|---|---:|
| [0:00:02](https://www.bilibili.com/video/BV1PZ4y197CX?t=2) | 5之后怎么断了？然后是9开始 | 1 |
| [0:00:35](https://www.bilibili.com/video/BV1PZ4y197CX?t=35) | wakanda forever | 1 |
| [0:00:40](https://www.bilibili.com/video/BV1PZ4y197CX?t=40) | stacking=bagging+boosting？ | 1 |
| [0:01:06](https://www.bilibili.com/video/BV1PZ4y197CX?t=66) | autogluon里面有个multi-layer-stacking | 1 |
| [0:01:15](https://www.bilibili.com/video/BV1PZ4y197CX?t=75) | 这个Loss怎么算？ | 1 |
| [0:01:31](https://www.bilibili.com/video/BV1PZ4y197CX?t=91) | ensemble还是stacking？ | 1 |
| [0:02:07](https://www.bilibili.com/video/BV1PZ4y197CX?t=127) | 是不是feature engineering里常用这种结构 | 1 |
| [0:02:09](https://www.bilibili.com/video/BV1PZ4y197CX?t=129) | Merry Christmas | 1 |
| [0:02:39](https://www.bilibili.com/video/BV1PZ4y197CX?t=159) | 相当于直接学习每个模型的权重 | 1 |
| [0:02:47](https://www.bilibili.com/video/BV1PZ4y197CX?t=167) | super learning？ | 1 |
| [0:02:54](https://www.bilibili.com/video/BV1PZ4y197CX?t=174) | 剪辑今天晚上鸡腿没了 | 1 |
| [0:03:10](https://www.bilibili.com/video/BV1PZ4y197CX?t=190) | 还故意留了NG的花絮 | 1 |
| [0:03:38](https://www.bilibili.com/video/BV1PZ4y197CX?t=218) | 不考虑速度的吗？用这么多模型 | 1 |
| [0:03:59](https://www.bilibili.com/video/BV1PZ4y197CX?t=239) | 怎么感觉和automl有点像啊 | 1 |
| [0:04:10](https://www.bilibili.com/video/BV1PZ4y197CX?t=250) | 就是加权投票，权重可学习 | 1 |
| [0:06:49](https://www.bilibili.com/video/BV1PZ4y197CX?t=409) | 最后这个模型的时间是全部相加吗 | 1 |
| [0:06:51](https://www.bilibili.com/video/BV1PZ4y197CX?t=411) | catboost很好啊，十分之一的时间 精度只比综合的少了0.01左右 | 1 |
| [0:07:06](https://www.bilibili.com/video/BV1PZ4y197CX?t=426) | 模型是可并行的，然后需要再加权处理 | 1 |
| [0:07:15](https://www.bilibili.com/video/BV1PZ4y197CX?t=435) | 最后效果好像好的并不多，每个模型付出的精力貌似多很多 | 1 |
| [0:08:01](https://www.bilibili.com/video/BV1PZ4y197CX?t=481) | 增加模型复杂度就降低了bias | 1 |
| [0:08:01](https://www.bilibili.com/video/BV1PZ4y197CX?t=481) | 这多个不同的基学习器，首先单独训练，然后stack，再finetune训练的方式么？ | 1 |
| [0:08:07](https://www.bilibili.com/video/BV1PZ4y197CX?t=487) | 看上去是的，模型复杂了很多，精度并没有提高多少 | 1 |
| [0:08:11](https://www.bilibili.com/video/BV1PZ4y197CX?t=491) | googlenet:有人模仿我的脸 | 1 |
| [0:08:52](https://www.bilibili.com/video/BV1PZ4y197CX?t=532) | 有点像resnet? | 1 |
| [0:08:57](https://www.bilibili.com/video/BV1PZ4y197CX?t=537) | resnet是吧（（（ | 1 |
| [0:09:00](https://www.bilibili.com/video/BV1PZ4y197CX?t=540) | 感觉和深度深林原理相同 | 1 |
| [0:09:01](https://www.bilibili.com/video/BV1PZ4y197CX?t=541) | concat就不是残差了 | 1 |
| [0:09:03](https://www.bilibili.com/video/BV1PZ4y197CX?t=543) | 有点resnet的味道了 | 1 |
| [0:09:08](https://www.bilibili.com/video/BV1PZ4y197CX?t=548) | 是concat不是+，densenet | 1 |
| [0:09:33](https://www.bilibili.com/video/BV1PZ4y197CX?t=573) | 没事，过拟合了再加宽（ | 1 |
| [0:09:44](https://www.bilibili.com/video/BV1PZ4y197CX?t=584) | 过拟合了对dense做bagging | 1 |
| [0:10:12](https://www.bilibili.com/video/BV1PZ4y197CX?t=612) | 第二层还用第一层的参数吗 | 1 |
| [0:10:20](https://www.bilibili.com/video/BV1PZ4y197CX?t=620) | 使用交叉验证就可以了吧 | 1 |
| [0:10:28](https://www.bilibili.com/video/BV1PZ4y197CX?t=628) | 类似GBDT的多层学习，容易过拟合 | 1 |
| [0:12:21](https://www.bilibili.com/video/BV1PZ4y197CX?t=741) | 不要放弃，这个k折验证用的很多的，效果很好 | 1 |
| [0:12:59](https://www.bilibili.com/video/BV1PZ4y197CX?t=779) | K折，每次都是n个模型拟合，留下一份没训练的样本预测，然后把K折的预测整合起来，变成全样本的新增变量，加上原来的再训练 | 1 |
| [0:13:00](https://www.bilibili.com/video/BV1PZ4y197CX?t=780) | k这个维度是为了把数据先分再合，目的是减轻过拟合 | 1 |
| [0:13:01](https://www.bilibili.com/video/BV1PZ4y197CX?t=781) | 这样不会导致误差变大吗 | 1 |
| [0:13:02](https://www.bilibili.com/video/BV1PZ4y197CX?t=782) | sa.1&lt;JLk  BHNJ                      mcjf  h ;lada | 1 |
| [0:13:04](https://www.bilibili.com/video/BV1PZ4y197CX?t=784) | 这不是训练成本爆炸了 | 1 |
| [0:13:23](https://www.bilibili.com/video/BV1PZ4y197CX?t=803) | 感觉这个复杂到没啥用了 | 1 |
| [0:13:25](https://www.bilibili.com/video/BV1PZ4y197CX?t=805) | 竟然还可以这样，涨知识了 | 1 |
| [0:13:34](https://www.bilibili.com/video/BV1PZ4y197CX?t=814) | 感觉做复杂之后越来越偏，真正有效的应该是大道至简 | 1 |
| [0:14:19](https://www.bilibili.com/video/BV1PZ4y197CX?t=859) | 取平均就类似bagging的做法 | 1 |
| [0:14:25](https://www.bilibili.com/video/BV1PZ4y197CX?t=865) | 感觉训练要花很多时间 | 1 |
| [0:14:31](https://www.bilibili.com/video/BV1PZ4y197CX?t=871) | 我不太理解，为什么我使用的时候这块会用redis。 | 1 |
| [0:16:09](https://www.bilibili.com/video/BV1PZ4y197CX?t=969) | 在有些时候这0.002可能是误差 | 1 |
| [0:16:32](https://www.bilibili.com/video/BV1PZ4y197CX?t=992) | 层与层之间参数不共享吧？ | 1 |
| [0:16:33](https://www.bilibili.com/video/BV1PZ4y197CX?t=993) | 0.2%在比赛就挺多 | 1 |
| [0:16:42](https://www.bilibili.com/video/BV1PZ4y197CX?t=1002) | 这个Error的进步真的太小了 | 1 |
| [0:17:14](https://www.bilibili.com/video/BV1PZ4y197CX?t=1034) | 感觉第二层已经很不错了都 | 1 |
| [0:17:16](https://www.bilibili.com/video/BV1PZ4y197CX?t=1036) | 那岂不是可以无限叠加？最后会收敛吧 | 1 |
| [0:17:20](https://www.bilibili.com/video/BV1PZ4y197CX?t=1040) | 无限叠加估计是过拟合了吧 | 1 |
| [0:17:20](https://www.bilibili.com/video/BV1PZ4y197CX?t=1040) | 成本控制啊，越堆叠效果越弱 | 1 |
| [0:17:46](https://www.bilibili.com/video/BV1PZ4y197CX?t=1066) | 叠加多了容易出现过拟合 | 1 |
| [0:18:30](https://www.bilibili.com/video/BV1PZ4y197CX?t=1110) | 并行解决方差，多层解决偏差，讲的是真的好 | 1 |
| [0:18:33](https://www.bilibili.com/video/BV1PZ4y197CX?t=1113) | 第二层使用第一层训练得到的参数作为初始参数吗 | 1 |
| [0:19:09](https://www.bilibili.com/video/BV1PZ4y197CX?t=1149) | 这里图错了吧，bagging应该是降低方差，boosting是降低偏差 | 1 |
| [0:19:15](https://www.bilibili.com/video/BV1PZ4y197CX?t=1155) | 是不是反了，bagging主要是降低方差吧 | 1 |
| [0:19:28](https://www.bilibili.com/video/BV1PZ4y197CX?t=1168) | 表格里的bias和variance, 应该写反了 | 1 |
| [0:19:29](https://www.bilibili.com/video/BV1PZ4y197CX?t=1169) | 偏差和方差是不是反了？ | 1 |
| [0:19:34](https://www.bilibili.com/video/BV1PZ4y197CX?t=1174) | 这是不是跟前面将的相反？ | 1 |
| [0:19:42](https://www.bilibili.com/video/BV1PZ4y197CX?t=1182) | bagging和boosting说反了 | 1 |
| [0:19:43](https://www.bilibili.com/video/BV1PZ4y197CX?t=1183) | 这个B和V好像都反了 | 1 |
| [0:19:47](https://www.bilibili.com/video/BV1PZ4y197CX?t=1187) | bagging的主要效果不是降低方差么？ | 1 |
| [0:19:49](https://www.bilibili.com/video/BV1PZ4y197CX?t=1189) | 这里有问题，Bagging是降低方差，Boosting是降低偏差 | 1 |
| [0:19:51](https://www.bilibili.com/video/BV1PZ4y197CX?t=1191) | 好像bagging和boosting反了？前者降低vars后者降低bias | 1 |
| [0:19:51](https://www.bilibili.com/video/BV1PZ4y197CX?t=1191) | Bias和Variance写反了。 | 1 |
| [0:19:53](https://www.bilibili.com/video/BV1PZ4y197CX?t=1193) | bagging不是降低方差吗？boosting降低偏差吧？这里写反了吗？ | 1 |
| [0:19:54](https://www.bilibili.com/video/BV1PZ4y197CX?t=1194) | bias 和 variance写反了 | 1 |
| [0:19:56](https://www.bilibili.com/video/BV1PZ4y197CX?t=1196) | 确实感觉 baggding和boosting反了，bagging应该是降低方差，boosting是降低偏差 | 1 |
| [0:19:59](https://www.bilibili.com/video/BV1PZ4y197CX?t=1199) | 我也觉得反了。但是我菜我不敢说。 | 1 |
| [0:20:03](https://www.bilibili.com/video/BV1PZ4y197CX?t=1203) | 图片里的bias和variance应该是写反了 | 1 |
| [0:20:07](https://www.bilibili.com/video/BV1PZ4y197CX?t=1207) | bagging 和boosting是不是写错了 | 1 |
| [0:20:07](https://www.bilibili.com/video/BV1PZ4y197CX?t=1207) | bagging boost stack的bias和var都反了吧 | 1 |
| [0:20:07](https://www.bilibili.com/video/BV1PZ4y197CX?t=1207) | bagging 和 boosting写反了吧 | 1 |
| [0:20:08](https://www.bilibili.com/video/BV1PZ4y197CX?t=1208) | 反了 bagging降低方差 boosting降低偏差 | 1 |
| [0:20:10](https://www.bilibili.com/video/BV1PZ4y197CX?t=1210) | 写错了的～ bagging 是 variance， bossting 是bias | 1 |
| [0:20:10](https://www.bilibili.com/video/BV1PZ4y197CX?t=1210) | boost降低偏差把 | 1 |
| [0:20:13](https://www.bilibili.com/video/BV1PZ4y197CX?t=1213) | 方差和偏差 列 写反了 | 1 |
| [0:20:14](https://www.bilibili.com/video/BV1PZ4y197CX?t=1214) | 多层stacking也是为了首先降低bias啊 | 1 |
| [0:20:17](https://www.bilibili.com/video/BV1PZ4y197CX?t=1217) | boosting和bagging是不是反了 | 1 |
| [0:20:20](https://www.bilibili.com/video/BV1PZ4y197CX?t=1220) | 这个图bagging和boosting的偏差方差是不是搞反了 | 1 |
| [0:20:24](https://www.bilibili.com/video/BV1PZ4y197CX?t=1224) | stacking也反了吧 | 1 |
| [0:20:29](https://www.bilibili.com/video/BV1PZ4y197CX?t=1229) | stacking不是可以防止过拟合吗？？？ | 1 |
| [0:20:32](https://www.bilibili.com/video/BV1PZ4y197CX?t=1232) | bagging 减少variance,boosting reduce bias | 1 |
| [0:20:39](https://www.bilibili.com/video/BV1PZ4y197CX?t=1239) | 我觉得是bias和variance这里写反了吧 | 1 |
| [0:20:45](https://www.bilibili.com/video/BV1PZ4y197CX?t=1245) | 可以简单理解成bias 和 variance 这两列写反了 | 1 |
| [0:20:51](https://www.bilibili.com/video/BV1PZ4y197CX?t=1251) | 官网 ppt 上是对的。大家可以按ppt的表格 | 1 |
| [0:20:55](https://www.bilibili.com/video/BV1PZ4y197CX?t=1255) | 不影响，大神肯定是故意写反考验我们的 | 1 |
| [0:21:06](https://www.bilibili.com/video/BV1PZ4y197CX?t=1266) | 考验大家有没有好好听课 | 1 |
| [0:21:18](https://www.bilibili.com/video/BV1PZ4y197CX?t=1278) | 全都要，就是贵，哈哈 | 1 |
| [0:21:27](https://www.bilibili.com/video/BV1PZ4y197CX?t=1287) | 恩，你们都看错了，快擦一下眼睛 | 1 |

## 全部有实质内容的弹幕（按时间排序，共 93 条）

- `0:00:02`**5之后怎么断了？然后是9开始**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=2)
- `0:00:35`**wakanda forever**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=35)
- `0:00:40`**stacking=bagging+boosting？**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=40)
- `0:01:06`**autogluon里面有个multi-layer-stacking**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=66)
- `0:01:15`**这个Loss怎么算？**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=75)
- `0:01:31`**ensemble还是stacking？**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=91)
- `0:02:07`**是不是feature engineering里常用这种结构**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=127)
- `0:02:09`**Merry Christmas**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=129)
- `0:02:39`**相当于直接学习每个模型的权重**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=159)
- `0:02:47`**super learning？**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=167)
- `0:02:54`**剪辑今天晚上鸡腿没了**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=174)
- `0:03:10`**还故意留了NG的花絮**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=190)
- `0:03:38`**不考虑速度的吗？用这么多模型**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=218)
- `0:03:59`**怎么感觉和automl有点像啊**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=239)
- `0:04:10`**就是加权投票，权重可学习**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=250)
- `0:06:49`**最后这个模型的时间是全部相加吗**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=409)
- `0:06:51`**catboost很好啊，十分之一的时间 精度只比综合的少了0.01左右**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=411)
- `0:07:06`**模型是可并行的，然后需要再加权处理**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=426)
- `0:07:15`**最后效果好像好的并不多，每个模型付出的精力貌似多很多**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=435)
- `0:08:01`**增加模型复杂度就降低了bias**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=481)
- `0:08:01`**这多个不同的基学习器，首先单独训练，然后stack，再finetune训练的方式么？**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=481)
- `0:08:07`**看上去是的，模型复杂了很多，精度并没有提高多少**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=487)
- `0:08:11`**googlenet:有人模仿我的脸**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=491)
- `0:08:52`**有点像resnet?**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=532)
- `0:08:57`**resnet是吧（（（**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=537)
- `0:09:00`**感觉和深度深林原理相同**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=540)
- `0:09:01`**concat就不是残差了**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=541)
- `0:09:03`**有点resnet的味道了**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=543)
- `0:09:08`**是concat不是+，densenet**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=548)
- `0:09:33`**没事，过拟合了再加宽（**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=573)
- `0:09:44`**过拟合了对dense做bagging**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=584)
- `0:10:12`**第二层还用第一层的参数吗**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=612)
- `0:10:20`**使用交叉验证就可以了吧**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=620)
- `0:10:28`**类似GBDT的多层学习，容易过拟合**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=628)
- `0:12:21`**不要放弃，这个k折验证用的很多的，效果很好**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=741)
- `0:12:59`**K折，每次都是n个模型拟合，留下一份没训练的样本预测，然后把K折的预测整合起来，变成全样本的新增变量，加上原来的再训练**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=779)
- `0:13:00`**k这个维度是为了把数据先分再合，目的是减轻过拟合**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=780)
- `0:13:01`**这样不会导致误差变大吗**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=781)
- `0:13:02`**sa.1&lt;JLk  BHNJ                      mcjf  h ;lada**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=782)
- `0:13:04`**这不是训练成本爆炸了**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=784)
- `0:13:23`**感觉这个复杂到没啥用了**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=803)
- `0:13:25`**竟然还可以这样，涨知识了**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=805)
- `0:13:34`**感觉做复杂之后越来越偏，真正有效的应该是大道至简**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=814)
- `0:14:19`**取平均就类似bagging的做法**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=859)
- `0:14:25`**感觉训练要花很多时间**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=865)
- `0:14:31`**我不太理解，为什么我使用的时候这块会用redis。**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=871)
- `0:16:09`**在有些时候这0.002可能是误差**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=969)
- `0:16:32`**层与层之间参数不共享吧？**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=992)
- `0:16:33`**0.2%在比赛就挺多**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=993)
- `0:16:42`**这个Error的进步真的太小了**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=1002)
- `0:17:14`**感觉第二层已经很不错了都**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=1034)
- `0:17:16`**那岂不是可以无限叠加？最后会收敛吧**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=1036)
- `0:17:20`**无限叠加估计是过拟合了吧**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=1040)
- `0:17:20`**成本控制啊，越堆叠效果越弱**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=1040)
- `0:17:46`**叠加多了容易出现过拟合**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=1066)
- `0:18:30`**并行解决方差，多层解决偏差，讲的是真的好**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=1110)
- `0:18:33`**第二层使用第一层训练得到的参数作为初始参数吗**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=1113)
- `0:19:09`**这里图错了吧，bagging应该是降低方差，boosting是降低偏差**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=1149)
- `0:19:15`**是不是反了，bagging主要是降低方差吧**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=1155)
- `0:19:28`**表格里的bias和variance, 应该写反了**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=1168)
- `0:19:29`**偏差和方差是不是反了？**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=1169)
- `0:19:34`**这是不是跟前面将的相反？**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=1174)
- `0:19:42`**bagging和boosting说反了**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=1182)
- `0:19:43`**这个B和V好像都反了**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=1183)
- `0:19:47`**bagging的主要效果不是降低方差么？**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=1187)
- `0:19:49`**这里有问题，Bagging是降低方差，Boosting是降低偏差**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=1189)
- `0:19:51`**好像bagging和boosting反了？前者降低vars后者降低bias**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=1191)
- `0:19:51`**Bias和Variance写反了。**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=1191)
- `0:19:53`**bagging不是降低方差吗？boosting降低偏差吧？这里写反了吗？**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=1193)
- `0:19:54`**bias 和 variance写反了**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=1194)
- `0:19:56`**确实感觉 baggding和boosting反了，bagging应该是降低方差，boosting是降低偏差**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=1196)
- `0:19:59`**我也觉得反了。但是我菜我不敢说。**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=1199)
- `0:20:03`**图片里的bias和variance应该是写反了**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=1203)
- `0:20:07`**bagging 和boosting是不是写错了**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=1207)
- `0:20:07`**bagging boost stack的bias和var都反了吧**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=1207)
- `0:20:07`**bagging 和 boosting写反了吧**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=1207)
- `0:20:08`**反了 bagging降低方差 boosting降低偏差**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=1208)
- `0:20:10`**写错了的～ bagging 是 variance， bossting 是bias**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=1210)
- `0:20:10`**boost降低偏差把**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=1210)
- `0:20:13`**方差和偏差 列 写反了**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=1213)
- `0:20:14`**多层stacking也是为了首先降低bias啊**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=1214)
- `0:20:17`**boosting和bagging是不是反了**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=1217)
- `0:20:20`**这个图bagging和boosting的偏差方差是不是搞反了**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=1220)
- `0:20:24`**stacking也反了吧**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=1224)
- `0:20:29`**stacking不是可以防止过拟合吗？？？**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=1229)
- `0:20:32`**bagging 减少variance,boosting reduce bias**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=1232)
- `0:20:39`**我觉得是bias和variance这里写反了吧**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=1239)
- `0:20:45`**可以简单理解成bias 和 variance 这两列写反了**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=1245)
- `0:20:51`**官网 ppt 上是对的。大家可以按ppt的表格**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=1251)
- `0:20:55`**不影响，大神肯定是故意写反考验我们的**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=1255)
- `0:21:06`**考验大家有没有好好听课**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=1266)
- `0:21:18`**全都要，就是贵，哈哈**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=1278)
- `0:21:27`**恩，你们都看错了，快擦一下眼睛**　[↗](https://www.bilibili.com/video/BV1PZ4y197CX?t=1287)
