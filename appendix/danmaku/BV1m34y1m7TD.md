# 弹幕讨论 · 3.6 卷积神经网络【斯坦福21秋季：实用机器学习中文版】

> 视频：[BV1m34y1m7TD](https://www.bilibili.com/video/BV1m34y1m7TD)　时长 0:17:55　弹幕总数 **147**　有实质内容 **77** 条　重点标记 **77** 条
>
> 来源：B 站 **跟李沐学AI** 的该集弹幕　快照：**2026-10-12**

## 口径说明（务必先读）

**这些内容全部是观众在视频上发的弹幕，不是经过核实的结论。**

- 其中有价值的：概念解释、类比、勘误、学习方法、延伸阅读线索。
- **也可能有错误的**：弹幕是个人理解，未经作者或权威确认。
  **本页不为其正确性背书，请勿直接引用为事实。**
- 每条带时间戳，点击可跳回视频对应位置自行核对。
- 筛选口径：保留长度 ≥ 10 字符、且不含纯感叹/打卡类噪声的弹幕，共 77 条（占该集弹幕 147 条的 52.4%）；同一句话被多人发送只保留一条并标注发送次数。
- 「重点」标记由关键词打分得出（技术词 + 解释性措辞 + 长度 + 多人重复），共 77 条；**它是启发式排序，不代表正确性，也不代表其余条目无价值。**

## 重点条目

| 时间 | 弹幕 | 发送次数 |
|---|---|---:|
| [0:00:49](https://www.bilibili.com/video/BV1m34y1m7TD?t=49) | zy 2024年12月27日 | 1 |
| [0:00:53](https://www.bilibili.com/video/BV1m34y1m7TD?t=53) | 有的 就是听起来很吃力哈哈 | 1 |
| [0:00:57](https://www.bilibili.com/video/BV1m34y1m7TD?t=57) | 上一集的东西，Multiple Layer Perceptron | 1 |
| [0:01:19](https://www.bilibili.com/video/BV1m34y1m7TD?t=79) | 为什么90000个image就是90000个特征呢 | 1 |
| [0:01:22](https://www.bilibili.com/video/BV1m34y1m7TD?t=82) | 这个课程和动手深度学习应该怎么结合起来学习呢 | 1 |
| [0:01:22](https://www.bilibili.com/video/BV1m34y1m7TD?t=82) | 完全听不懂了   还要继续听吗？ | 1 |
| [0:01:25](https://www.bilibili.com/video/BV1m34y1m7TD?t=85) | 上来就隐藏层，全连接层？ | 1 |
| [0:01:29](https://www.bilibili.com/video/BV1m34y1m7TD?t=89) | 300 * 300.一个像素作为一个输入。那么有90000个输入，中间层是全连接，所以这里有90000 * 10000=9亿个参数 | 1 |
| [0:01:32](https://www.bilibili.com/video/BV1m34y1m7TD?t=92) | 十亿 ！感知每一个像素 | 1 |
| [0:01:34](https://www.bilibili.com/video/BV1m34y1m7TD?t=94) | 如果我没想错的话可以理解成把图片flatten到一维再输入，所以第一个层的w是90000*10000 | 1 |
| [0:01:36](https://www.bilibili.com/video/BV1m34y1m7TD?t=96) | 实在很好，顺利从MLP过渡到卷积 | 1 |
| [0:01:49](https://www.bilibili.com/video/BV1m34y1m7TD?t=109) | w和b都学不是应该20亿么 | 1 |
| [0:02:02](https://www.bilibili.com/video/BV1m34y1m7TD?t=122) | 人的位置在马路前段后段对识别人没影响 | 1 |
| [0:02:39](https://www.bilibili.com/video/BV1m34y1m7TD?t=159) | find waldo | 1 |
| [0:02:50](https://www.bilibili.com/video/BV1m34y1m7TD?t=170) | Find Waldo lol | 1 |
| [0:02:52](https://www.bilibili.com/video/BV1m34y1m7TD?t=172) | 生活大爆炸有一集有玩这个来着 | 1 |
| [0:04:18](https://www.bilibili.com/video/BV1m34y1m7TD?t=258) | 所以90000 x 10000 是把每个像素做为特征了，10000是超参数，选择的输出 | 1 |
| [0:04:28](https://www.bilibili.com/video/BV1m34y1m7TD?t=268) | 卷积网络只能用于图片问题吗 | 1 |
| [0:04:31](https://www.bilibili.com/video/BV1m34y1m7TD?t=271) | 反复看了几遍，终于懂了卷积层和全连接层的区别和演变过程 | 1 |
| [0:04:34](https://www.bilibili.com/video/BV1m34y1m7TD?t=274) | 4 by 4，不是440 | 1 |
| [0:05:50](https://www.bilibili.com/video/BV1m34y1m7TD?t=350) | 这里相当于Dense layer一个输出结果对应9万个参数，而卷积只对应4个参数 | 1 |
| [0:06:12](https://www.bilibili.com/video/BV1m34y1m7TD?t=372) | 没听这个课之前 以前学的卷积是学了个寂寞 | 1 |
| [0:06:22](https://www.bilibili.com/video/BV1m34y1m7TD?t=382) | 这里的卷积和统计学上的卷积不太一样 | 1 |
| [0:07:13](https://www.bilibili.com/video/BV1m34y1m7TD?t=433) | 识别一个模式 pattern | 1 |
| [0:07:17](https://www.bilibili.com/video/BV1m34y1m7TD?t=437) | pattern解释为图案会比较好理解一点吧 | 1 |
| [0:08:23](https://www.bilibili.com/video/BV1m34y1m7TD?t=503) | 求指路，之前的相关课程 | 1 |
| [0:08:27](https://www.bilibili.com/video/BV1m34y1m7TD?t=507) | 一定要转专业成功呀，在智科里面好好学习一番 | 1 |
| [0:08:51](https://www.bilibili.com/video/BV1m34y1m7TD?t=531) | 都已经找到这了，深度学习在哪学还能找不到吗 | 1 |
| [0:10:14](https://www.bilibili.com/video/BV1m34y1m7TD?t=614) | Python的语法糖 | 1 |
| [0:10:16](https://www.bilibili.com/video/BV1m34y1m7TD?t=616) | 是设定一个卷积核，然后用这个卷积核按一定步长滑过图像的所有像素，从而提取到图像的某一特征 | 1 |
| [0:10:25](https://www.bilibili.com/video/BV1m34y1m7TD?t=625) | 不包含+h和+w的那行和那列 | 1 |
| [0:10:26](https://www.bilibili.com/video/BV1m34y1m7TD?t=626) | 可以理解为每次算一个窗口大小的加权和 | 1 |
| [0:10:27](https://www.bilibili.com/video/BV1m34y1m7TD?t=627) | 这个代码习惯跟以前用的MATLAB太像了！ | 1 |
| [0:10:30](https://www.bilibili.com/video/BV1m34y1m7TD?t=630) | 就是对应位置相乘在相加，然后窗口滑动 | 1 |
| [0:10:57](https://www.bilibili.com/video/BV1m34y1m7TD?t=657) | 在这里为什么要反过来相乘呀 | 1 |
| [0:11:06](https://www.bilibili.com/video/BV1m34y1m7TD?t=666) | 那卷积这里卷命名的意义何在呢 | 1 |
| [0:11:09](https://www.bilibili.com/video/BV1m34y1m7TD?t=669) | 这里不是严格的意义卷积（没有翻转），只是英语单词相同，意译的话可以换一个更贴切的名字的 | 1 |
| [0:11:16](https://www.bilibili.com/video/BV1m34y1m7TD?t=676) | 是因为这里的过程和卷积一开始定义的滑动异曲同工所以这么叫 | 1 |
| [0:11:26](https://www.bilibili.com/video/BV1m34y1m7TD?t=686) | ？？？？？？？？？？？？？？？？？？？？？？》？》》》》》？》？》？》》？》》》？》？》》？》？》？》》？》》》？》？》？》？》？》？》？ | 1 |
| [0:12:23](https://www.bilibili.com/video/BV1m34y1m7TD?t=743) | aggregation | 1 |
| [0:12:28](https://www.bilibili.com/video/BV1m34y1m7TD?t=748) | 现在已经被stride参数代替了 | 1 |
| [0:12:28](https://www.bilibili.com/video/BV1m34y1m7TD?t=748) | 池化的这种解释好有意思 | 1 |
| [0:12:31](https://www.bilibili.com/video/BV1m34y1m7TD?t=751) | 平均池化层或最大池化层 | 1 |
| [0:12:38](https://www.bilibili.com/video/BV1m34y1m7TD?t=758) | mean和sum似乎没有本质的区别？ | 1 |
| [0:12:38](https://www.bilibili.com/video/BV1m34y1m7TD?t=758) | stride不就是步长吗···你搁这套娃呢 | 1 |
| [0:12:41](https://www.bilibili.com/video/BV1m34y1m7TD?t=761) | stride和这个有啥关系 | 1 |
| [0:12:46](https://www.bilibili.com/video/BV1m34y1m7TD?t=766) | 这里的stride默认就是1啊 up说的不是针对于image中噪声的补偿而采用pooling layer再次降维 从而robust吗 | 1 |
| [0:12:49](https://www.bilibili.com/video/BV1m34y1m7TD?t=769) | stride默认的不是步长和window大小相等吗 | 1 |
| [0:13:01](https://www.bilibili.com/video/BV1m34y1m7TD?t=781) | 终于明白卷积和池化的意义了，沐神讲的真清楚 | 1 |
| [0:13:02](https://www.bilibili.com/video/BV1m34y1m7TD?t=782) | 池化层降低精度，提高泛化性 | 1 |
| [0:13:31](https://www.bilibili.com/video/BV1m34y1m7TD?t=811) | 开始听不懂了，但记住结论是不是就行 | 1 |
| [0:13:46](https://www.bilibili.com/video/BV1m34y1m7TD?t=826) | 特征值在窗口内，不管在窗口的哪个位置，只要找最大的就是 | 1 |
| [0:13:48](https://www.bilibili.com/video/BV1m34y1m7TD?t=828) | 这里就是用汇聚层替代卷积核了吗？ | 1 |
| [0:13:50](https://www.bilibili.com/video/BV1m34y1m7TD?t=830) | 不是替代，是对卷积层的输出再做“卷积”，也就是pooling，这是两步走的事 | 1 |
| [0:13:59](https://www.bilibili.com/video/BV1m34y1m7TD?t=839) | 简单来说就是数据可能会有细微抖动 所以对一小块数据就行模糊处理 选一个值做他们的代表 一般是均值或者最大值 | 1 |
| [0:14:02](https://www.bilibili.com/video/BV1m34y1m7TD?t=842) | 跟空洞卷积还是有区别的 | 1 |
| [0:14:09](https://www.bilibili.com/video/BV1m34y1m7TD?t=849) | pooling的意思就是减少数据量 | 1 |
| [0:14:20](https://www.bilibili.com/video/BV1m34y1m7TD?t=860) | 池化就是选最大或者平均的卷积结果 | 1 |
| [0:14:20](https://www.bilibili.com/video/BV1m34y1m7TD?t=860) | 这个其实需要算法的知识，就是一个滑动窗口。你们可以了解一下 | 1 |
| [0:14:20](https://www.bilibili.com/video/BV1m34y1m7TD?t=860) | 这几节真好，把以前刷的3门课都解释的清清楚楚。居然能看懂代码了。。。 | 1 |
| [0:14:23](https://www.bilibili.com/video/BV1m34y1m7TD?t=863) | 相当于用同种算法把各个区域进行重映射 | 1 |
| [0:14:25](https://www.bilibili.com/video/BV1m34y1m7TD?t=865) | 这些代码可以直接在框架里面调用，一行代码就可解决，但是新手需要先了解基本原理 | 1 |
| [0:14:29](https://www.bilibili.com/video/BV1m34y1m7TD?t=869) | 这里默认的stride应该都是1把 | 1 |
| [0:14:40](https://www.bilibili.com/video/BV1m34y1m7TD?t=880) | 这部分老师讲的好抽象，看弹幕才对应上是哪部分知识，就是一个滑动窗口取值的方法 | 1 |
| [0:14:43](https://www.bilibili.com/video/BV1m34y1m7TD?t=883) | 像素平均周围点把图像模糊化，来降低模型的像素敏感度 | 1 |
| [0:14:45](https://www.bilibili.com/video/BV1m34y1m7TD?t=885) | 我想知道这个平移是什么概念 | 1 |
| [0:14:52](https://www.bilibili.com/video/BV1m34y1m7TD?t=892) | 平均池化相当于模糊了图片，马赛克 | 1 |
| [0:14:56](https://www.bilibili.com/video/BV1m34y1m7TD?t=896) | 把图片分成很多个小块，然后取这个小块的池化值，相当于采样，图片偏移不大时，相同采样方式得到的采样值是一样的 | 1 |
| [0:15:25](https://www.bilibili.com/video/BV1m34y1m7TD?t=925) | 除了能够减少维度，还可以增强鲁棒性，太清楚了 | 1 |
| [0:15:28](https://www.bilibili.com/video/BV1m34y1m7TD?t=928) | 需要满足位置不变性的特征，才能用小核卷积 | 1 |
| [0:16:42](https://www.bilibili.com/video/BV1m34y1m7TD?t=1002) | 卷积不是具有平移不变性吗 | 1 |
| [0:16:51](https://www.bilibili.com/video/BV1m34y1m7TD?t=1011) | 没有反，仔细看是函数里参数的一个顺序，是从上到下的。 | 1 |
| [0:16:53](https://www.bilibili.com/video/BV1m34y1m7TD?t=1013) | flatten应该是把二维展成一维的吧？（不懂就问 | 1 |
| [0:17:00](https://www.bilibili.com/video/BV1m34y1m7TD?t=1020) | 底下是输入，上面是输出，这里是说反了还是ppt写反了？ | 1 |
| [0:17:01](https://www.bilibili.com/video/BV1m34y1m7TD?t=1021) | 全连接层不是一位的列向量作为输入和输出吗，为什么这里又说是二维的 | 1 |
| [0:17:06](https://www.bilibili.com/video/BV1m34y1m7TD?t=1026) | 就是二维的矩阵，一维的是以分类为目标的输出 | 1 |
| [0:17:46](https://www.bilibili.com/video/BV1m34y1m7TD?t=1066) | VGG的特点是只用3x3卷称核 | 1 |

## 全部有实质内容的弹幕（按时间排序，共 77 条）

- `0:00:49`**zy 2024年12月27日**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=49)
- `0:00:53`**有的 就是听起来很吃力哈哈**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=53)
- `0:00:57`**上一集的东西，Multiple Layer Perceptron**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=57)
- `0:01:19`**为什么90000个image就是90000个特征呢**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=79)
- `0:01:22`**这个课程和动手深度学习应该怎么结合起来学习呢**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=82)
- `0:01:22`**完全听不懂了   还要继续听吗？**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=82)
- `0:01:25`**上来就隐藏层，全连接层？**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=85)
- `0:01:29`**300 * 300.一个像素作为一个输入。那么有90000个输入，中间层是全连接，所以这里有90000 * 10000=9亿个参数**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=89)
- `0:01:32`**十亿 ！感知每一个像素**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=92)
- `0:01:34`**如果我没想错的话可以理解成把图片flatten到一维再输入，所以第一个层的w是90000*10000**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=94)
- `0:01:36`**实在很好，顺利从MLP过渡到卷积**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=96)
- `0:01:49`**w和b都学不是应该20亿么**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=109)
- `0:02:02`**人的位置在马路前段后段对识别人没影响**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=122)
- `0:02:39`**find waldo**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=159)
- `0:02:50`**Find Waldo lol**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=170)
- `0:02:52`**生活大爆炸有一集有玩这个来着**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=172)
- `0:04:18`**所以90000 x 10000 是把每个像素做为特征了，10000是超参数，选择的输出**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=258)
- `0:04:28`**卷积网络只能用于图片问题吗**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=268)
- `0:04:31`**反复看了几遍，终于懂了卷积层和全连接层的区别和演变过程**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=271)
- `0:04:34`**4 by 4，不是440**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=274)
- `0:05:50`**这里相当于Dense layer一个输出结果对应9万个参数，而卷积只对应4个参数**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=350)
- `0:06:12`**没听这个课之前 以前学的卷积是学了个寂寞**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=372)
- `0:06:22`**这里的卷积和统计学上的卷积不太一样**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=382)
- `0:07:13`**识别一个模式 pattern**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=433)
- `0:07:17`**pattern解释为图案会比较好理解一点吧**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=437)
- `0:08:23`**求指路，之前的相关课程**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=503)
- `0:08:27`**一定要转专业成功呀，在智科里面好好学习一番**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=507)
- `0:08:51`**都已经找到这了，深度学习在哪学还能找不到吗**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=531)
- `0:10:14`**Python的语法糖**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=614)
- `0:10:16`**是设定一个卷积核，然后用这个卷积核按一定步长滑过图像的所有像素，从而提取到图像的某一特征**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=616)
- `0:10:25`**不包含+h和+w的那行和那列**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=625)
- `0:10:26`**可以理解为每次算一个窗口大小的加权和**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=626)
- `0:10:27`**这个代码习惯跟以前用的MATLAB太像了！**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=627)
- `0:10:30`**就是对应位置相乘在相加，然后窗口滑动**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=630)
- `0:10:57`**在这里为什么要反过来相乘呀**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=657)
- `0:11:06`**那卷积这里卷命名的意义何在呢**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=666)
- `0:11:09`**这里不是严格的意义卷积（没有翻转），只是英语单词相同，意译的话可以换一个更贴切的名字的**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=669)
- `0:11:16`**是因为这里的过程和卷积一开始定义的滑动异曲同工所以这么叫**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=676)
- `0:11:26`**？？？？？？？？？？？？？？？？？？？？？？》？》》》》》？》？》？》》？》》》？》？》》？》？》？》》？》》》？》？》？》？》？》？》？**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=686)
- `0:12:23`**aggregation**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=743)
- `0:12:28`**现在已经被stride参数代替了**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=748)
- `0:12:28`**池化的这种解释好有意思**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=748)
- `0:12:31`**平均池化层或最大池化层**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=751)
- `0:12:38`**mean和sum似乎没有本质的区别？**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=758)
- `0:12:38`**stride不就是步长吗···你搁这套娃呢**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=758)
- `0:12:41`**stride和这个有啥关系**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=761)
- `0:12:46`**这里的stride默认就是1啊 up说的不是针对于image中噪声的补偿而采用pooling layer再次降维 从而robust吗**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=766)
- `0:12:49`**stride默认的不是步长和window大小相等吗**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=769)
- `0:13:01`**终于明白卷积和池化的意义了，沐神讲的真清楚**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=781)
- `0:13:02`**池化层降低精度，提高泛化性**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=782)
- `0:13:31`**开始听不懂了，但记住结论是不是就行**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=811)
- `0:13:46`**特征值在窗口内，不管在窗口的哪个位置，只要找最大的就是**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=826)
- `0:13:48`**这里就是用汇聚层替代卷积核了吗？**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=828)
- `0:13:50`**不是替代，是对卷积层的输出再做“卷积”，也就是pooling，这是两步走的事**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=830)
- `0:13:59`**简单来说就是数据可能会有细微抖动 所以对一小块数据就行模糊处理 选一个值做他们的代表 一般是均值或者最大值**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=839)
- `0:14:02`**跟空洞卷积还是有区别的**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=842)
- `0:14:09`**pooling的意思就是减少数据量**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=849)
- `0:14:20`**池化就是选最大或者平均的卷积结果**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=860)
- `0:14:20`**这个其实需要算法的知识，就是一个滑动窗口。你们可以了解一下**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=860)
- `0:14:20`**这几节真好，把以前刷的3门课都解释的清清楚楚。居然能看懂代码了。。。**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=860)
- `0:14:23`**相当于用同种算法把各个区域进行重映射**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=863)
- `0:14:25`**这些代码可以直接在框架里面调用，一行代码就可解决，但是新手需要先了解基本原理**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=865)
- `0:14:29`**这里默认的stride应该都是1把**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=869)
- `0:14:40`**这部分老师讲的好抽象，看弹幕才对应上是哪部分知识，就是一个滑动窗口取值的方法**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=880)
- `0:14:43`**像素平均周围点把图像模糊化，来降低模型的像素敏感度**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=883)
- `0:14:45`**我想知道这个平移是什么概念**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=885)
- `0:14:52`**平均池化相当于模糊了图片，马赛克**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=892)
- `0:14:56`**把图片分成很多个小块，然后取这个小块的池化值，相当于采样，图片偏移不大时，相同采样方式得到的采样值是一样的**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=896)
- `0:15:25`**除了能够减少维度，还可以增强鲁棒性，太清楚了**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=925)
- `0:15:28`**需要满足位置不变性的特征，才能用小核卷积**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=928)
- `0:16:42`**卷积不是具有平移不变性吗**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=1002)
- `0:16:51`**没有反，仔细看是函数里参数的一个顺序，是从上到下的。**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=1011)
- `0:16:53`**flatten应该是把二维展成一维的吧？（不懂就问**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=1013)
- `0:17:00`**底下是输入，上面是输出，这里是说反了还是ppt写反了？**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=1020)
- `0:17:01`**全连接层不是一位的列向量作为输入和输出吗，为什么这里又说是二维的**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=1021)
- `0:17:06`**就是二维的矩阵，一维的是以分类为目标的输出**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=1026)
- `0:17:46`**VGG的特点是只用3x3卷称核**　[↗](https://www.bilibili.com/video/BV1m34y1m7TD?t=1066)
