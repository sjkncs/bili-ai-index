# 弹幕讨论 · 3.7 循环神经网络【斯坦福21秋季：实用机器学习中文版】

> 视频：[BV1pq4y1r7zo](https://www.bilibili.com/video/BV1pq4y1r7zo)　时长 0:20:57　弹幕总数 **135**　有实质内容 **70** 条　重点标记 **70** 条
>
> 来源：B 站 **跟李沐学AI** 的该集弹幕　快照：**2026-10-13**

## 口径说明（务必先读）

**这些内容全部是观众在视频上发的弹幕，不是经过核实的结论。**

- 其中有价值的：概念解释、类比、勘误、学习方法、延伸阅读线索。
- **也可能有错误的**：弹幕是个人理解，未经作者或权威确认。
  **本页不为其正确性背书，请勿直接引用为事实。**
- 每条带时间戳，点击可跳回视频对应位置自行核对。
- 筛选口径：保留长度 ≥ 10 字符、且不含纯感叹/打卡类噪声的弹幕，共 70 条（占该集弹幕 135 条的 51.9%）；同一句话被多人发送只保留一条并标注发送次数。
- 「重点」标记由关键词打分得出（技术词 + 解释性措辞 + 长度 + 多人重复），共 70 条；**它是启发式排序，不代表正确性，也不代表其余条目无价值。**

## 重点条目

| 时间 | 弹幕 | 发送次数 |
|---|---|---:|
| [0:00:05](https://www.bilibili.com/video/BV1pq4y1r7zo?t=5) | Dense layer是全连接层（Fully Connected Layer） | 1 |
| [0:01:00](https://www.bilibili.com/video/BV1pq4y1r7zo?t=60) | 这里是给词用独热编码还是给w用独热编码 | 1 |
| [0:01:28](https://www.bilibili.com/video/BV1pq4y1r7zo?t=88) | 衣服可加logo带货了 | 1 |
| [0:02:26](https://www.bilibili.com/video/BV1pq4y1r7zo?t=146) | 输入维度固定的意思吗 | 1 |
| [0:02:32](https://www.bilibili.com/video/BV1pq4y1r7zo?t=152) | 看怎麽說，作爲mlp一定是一個有意義的做法，但是不如rnn | 1 |
| [0:02:33](https://www.bilibili.com/video/BV1pq4y1r7zo?t=153) | 叠加应该是可以叠加的，只是需要的时间较长 | 1 |
| [0:02:37](https://www.bilibili.com/video/BV1pq4y1r7zo?t=157) | 以上各位，你们忽略了重要的东西：叠加是没有时序信息的！RNN是逐词编码的！有顺序！ | 1 |
| [0:02:49](https://www.bilibili.com/video/BV1pq4y1r7zo?t=169) | 叠加就变成了多个样本 | 1 |
| [0:03:05](https://www.bilibili.com/video/BV1pq4y1r7zo?t=185) | 有个疑问，ARX模型里面可以设置u(t-nb)啊，这样时间见序列不就进来了么 | 1 |
| [0:03:17](https://www.bilibili.com/video/BV1pq4y1r7zo?t=197) | 多样本就没有前后关系了把 | 1 |
| [0:03:24](https://www.bilibili.com/video/BV1pq4y1r7zo?t=204) | 如果这里加上权重的思想，感觉就可以直接跳到注意力机制了 | 1 |
| [0:03:26](https://www.bilibili.com/video/BV1pq4y1r7zo?t=206) | 也可以再加上位置编码啊？模仿transformer | 1 |
| [0:03:29](https://www.bilibili.com/video/BV1pq4y1r7zo?t=209) | MLP自己就有权重，注意力的重点是“自适应权重”，上面的理解不够啊 | 1 |
| [0:03:41](https://www.bilibili.com/video/BV1pq4y1r7zo?t=221) | 都transformer了还用RNN干嘛呢。。 | 1 |
| [0:03:47](https://www.bilibili.com/video/BV1pq4y1r7zo?t=227) | 说不用学RNN的同学，你不是做研究的。我请问，Trans是凭空出来的吗？ | 1 |
| [0:04:06](https://www.bilibili.com/video/BV1pq4y1r7zo?t=246) | 为什么是concat？ | 1 |
| [0:04:09](https://www.bilibili.com/video/BV1pq4y1r7zo?t=249) | 之前提到softmax就是变成概率的一个操作吗 | 1 |
| [0:04:16](https://www.bilibili.com/video/BV1pq4y1r7zo?t=256) | 请问大佬，现在有tansformer了，还有哪在用RNN吗？ | 1 |
| [0:04:27](https://www.bilibili.com/video/BV1pq4y1r7zo?t=267) | 上一节讲MLP代码里的H | 1 |
| [0:04:36](https://www.bilibili.com/video/BV1pq4y1r7zo?t=276) | 短序列，小数据集还可以用RNN啊，transformer模型都很大，很吃数据，数据集小的话效果不一定好 | 1 |
| [0:04:50](https://www.bilibili.com/video/BV1pq4y1r7zo?t=290) | 这里是 kv_cache 吗？ | 1 |
| [0:05:12](https://www.bilibili.com/video/BV1pq4y1r7zo?t=312) | Concat 什么操作啊？是指隐藏层数据相加吗，那不就失去时序特性了吗？ | 1 |
| [0:05:14](https://www.bilibili.com/video/BV1pq4y1r7zo?t=314) | 相当于用隐层把不同长度统一成相同长度？ | 1 |
| [0:05:21](https://www.bilibili.com/video/BV1pq4y1r7zo?t=321) | 前面的，是的！但逐个单词合并就是为了编码词的顺序！ | 1 |
| [0:05:33](https://www.bilibili.com/video/BV1pq4y1r7zo?t=333) | 可逆就可以肯定信息无损 | 1 |
| [0:05:46](https://www.bilibili.com/video/BV1pq4y1r7zo?t=346) | 肯定是不可逆，就像哈希值能回推原文么？ | 1 |
| [0:05:49](https://www.bilibili.com/video/BV1pq4y1r7zo?t=349) | 如果文本太长的话可能会导致网络的隐藏参数不够用，会忘掉最开始的内容 | 1 |
| [0:07:19](https://www.bilibili.com/video/BV1pq4y1r7zo?t=439) | 这个h是RNN中隐藏层的输出，不是最终输出 | 1 |
| [0:07:47](https://www.bilibili.com/video/BV1pq4y1r7zo?t=467) | rnn缺点就是不能并行 | 1 |
| [0:07:52](https://www.bilibili.com/video/BV1pq4y1r7zo?t=472) | 这样不是线性和了吗，还是concat吗 | 1 |
| [0:07:52](https://www.bilibili.com/video/BV1pq4y1r7zo?t=472) | 能并行就没transformer什么事情了 | 1 |
| [0:09:05](https://www.bilibili.com/video/BV1pq4y1r7zo?t=545) | 播放1.5万，点赞只有1000多？ | 1 |
| [0:09:17](https://www.bilibili.com/video/BV1pq4y1r7zo?t=557) | 都在认真学习，忘了点赞了 | 1 |
| [0:09:18](https://www.bilibili.com/video/BV1pq4y1r7zo?t=558) | 一部分是重复学习的吧 | 1 |
| [0:09:23](https://www.bilibili.com/video/BV1pq4y1r7zo?t=563) | 会不会只是感觉前面的Ht-1有更多的信息，而Xt只是相对于前面的信息少一点 | 1 |
| [0:09:43](https://www.bilibili.com/video/BV1pq4y1r7zo?t=583) | 12人正在观看。。。。 | 1 |
| [0:10:52](https://www.bilibili.com/video/BV1pq4y1r7zo?t=652) | why no mxnet | 1 |
| [0:11:07](https://www.bilibili.com/video/BV1pq4y1r7zo?t=667) | 这个不是隐藏层的数量吗？不是输出吧 | 1 |
| [0:11:41](https://www.bilibili.com/video/BV1pq4y1r7zo?t=701) | 为什么一个用randn，一个用rand呢 | 1 |
| [0:11:45](https://www.bilibili.com/video/BV1pq4y1r7zo?t=705) | 應該是筆誤吧，我覺得應該都是randn | 1 |
| [0:12:03](https://www.bilibili.com/video/BV1pq4y1r7zo?t=723) | B 和 C H W 对于图片 | 1 |
| [0:12:13](https://www.bilibili.com/video/BV1pq4y1r7zo?t=733) | 发繁体字的都是什么成分 | 1 |
| [0:12:16](https://www.bilibili.com/video/BV1pq4y1r7zo?t=736) | num_steps=10代表前面10个词预测下一个词，batch_size怎么理解呢 | 1 |
| [0:13:22](https://www.bilibili.com/video/BV1pq4y1r7zo?t=802) | 终于明白hidden_state怎么来的了 | 1 |
| [0:13:31](https://www.bilibili.com/video/BV1pq4y1r7zo?t=811) | 输入输出都是一样个数？ | 1 |
| [0:14:03](https://www.bilibili.com/video/BV1pq4y1r7zo?t=843) | 卧槽，一直以为一个step就有一个小单元 | 1 |
| [0:14:15](https://www.bilibili.com/video/BV1pq4y1r7zo?t=855) | 如果w_hh是一个东西的话，是不是每次得到的H向量的长度是一样的 | 1 |
| [0:14:15](https://www.bilibili.com/video/BV1pq4y1r7zo?t=855) | Loss怎么计算？反向传播？ | 1 |
| [0:15:23](https://www.bilibili.com/video/BV1pq4y1r7zo?t=923) | 这边H应该还要接一个softmax吧，感觉是不是要softmax之后得到y呢 | 1 |
| [0:15:24](https://www.bilibili.com/video/BV1pq4y1r7zo?t=924) | 方向是语序方向吧，和书写方向有关系吗？ | 1 |
| [0:15:26](https://www.bilibili.com/video/BV1pq4y1r7zo?t=926) | 举个例子有啥可杠的啊…… | 1 |
| [0:15:29](https://www.bilibili.com/video/BV1pq4y1r7zo?t=929) | 计算机读取只会从左往右，管你语序是从哪到哪 | 1 |
| [0:15:32](https://www.bilibili.com/video/BV1pq4y1r7zo?t=932) | 双向主要是害怕把最前面的忘了 | 1 |
| [0:15:35](https://www.bilibili.com/video/BV1pq4y1r7zo?t=935) | 没关系，大神就是可爱了一下 | 1 |
| [0:15:40](https://www.bilibili.com/video/BV1pq4y1r7zo?t=940) | 反着写难道你还正看吗 | 1 |
| [0:15:46](https://www.bilibili.com/video/BV1pq4y1r7zo?t=946) | 这个yt是yhat吗 | 1 |
| [0:15:46](https://www.bilibili.com/video/BV1pq4y1r7zo?t=946) | 在做一些multi-languange的任务的时候，采集到的数据可能有从左往右读的，也有从右往左读的，人工一个一个分辨太浪费时间了，直接双向多好 | 1 |
| [0:15:50](https://www.bilibili.com/video/BV1pq4y1r7zo?t=950) | 两个方向是求和得最终输出吗 | 1 |
| [0:15:55](https://www.bilibili.com/video/BV1pq4y1r7zo?t=955) | 语义有时候也需要结合上下文 | 1 |
| [0:16:07](https://www.bilibili.com/video/BV1pq4y1r7zo?t=967) | 主要是为了获得语法特征吧 | 1 |
| [0:16:10](https://www.bilibili.com/video/BV1pq4y1r7zo?t=970) | 确实例子有点不恰当，可以用高考语文古诗填空的思想理解 | 1 |
| [0:16:21](https://www.bilibili.com/video/BV1pq4y1r7zo?t=981) | 双向是为了更好的获取上下文的语义特征 | 1 |
| [0:16:38](https://www.bilibili.com/video/BV1pq4y1r7zo?t=998) | 完形填空好巧妙的形容 | 1 |
| [0:17:09](https://www.bilibili.com/video/BV1pq4y1r7zo?t=1029) | 这个多层 是横着的RNN数量吧 竖着只有双向两层 | 1 |
| [0:17:45](https://www.bilibili.com/video/BV1pq4y1r7zo?t=1065) | 这里speech是语音吧 | 1 |
| [0:17:46](https://www.bilibili.com/video/BV1pq4y1r7zo?t=1066) | RNN 还有对周期类数据，比如天气预报是有用的 | 1 |
| [0:18:16](https://www.bilibili.com/video/BV1pq4y1r7zo?t=1096) | speech为啥是语音？ | 1 |
| [0:18:27](https://www.bilibili.com/video/BV1pq4y1r7zo?t=1107) | speech偏向实时，audio偏向是文件 | 1 |
| [0:18:57](https://www.bilibili.com/video/BV1pq4y1r7zo?t=1137) | swin-transformer | 1 |
| [0:19:15](https://www.bilibili.com/video/BV1pq4y1r7zo?t=1155) | transformers是不是不用标注？ | 1 |

## 全部有实质内容的弹幕（按时间排序，共 70 条）

- `0:00:05`**Dense layer是全连接层（Fully Connected Layer）**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=5)
- `0:01:00`**这里是给词用独热编码还是给w用独热编码**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=60)
- `0:01:28`**衣服可加logo带货了**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=88)
- `0:02:26`**输入维度固定的意思吗**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=146)
- `0:02:32`**看怎麽說，作爲mlp一定是一個有意義的做法，但是不如rnn**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=152)
- `0:02:33`**叠加应该是可以叠加的，只是需要的时间较长**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=153)
- `0:02:37`**以上各位，你们忽略了重要的东西：叠加是没有时序信息的！RNN是逐词编码的！有顺序！**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=157)
- `0:02:49`**叠加就变成了多个样本**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=169)
- `0:03:05`**有个疑问，ARX模型里面可以设置u(t-nb)啊，这样时间见序列不就进来了么**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=185)
- `0:03:17`**多样本就没有前后关系了把**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=197)
- `0:03:24`**如果这里加上权重的思想，感觉就可以直接跳到注意力机制了**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=204)
- `0:03:26`**也可以再加上位置编码啊？模仿transformer**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=206)
- `0:03:29`**MLP自己就有权重，注意力的重点是“自适应权重”，上面的理解不够啊**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=209)
- `0:03:41`**都transformer了还用RNN干嘛呢。。**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=221)
- `0:03:47`**说不用学RNN的同学，你不是做研究的。我请问，Trans是凭空出来的吗？**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=227)
- `0:04:06`**为什么是concat？**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=246)
- `0:04:09`**之前提到softmax就是变成概率的一个操作吗**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=249)
- `0:04:16`**请问大佬，现在有tansformer了，还有哪在用RNN吗？**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=256)
- `0:04:27`**上一节讲MLP代码里的H**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=267)
- `0:04:36`**短序列，小数据集还可以用RNN啊，transformer模型都很大，很吃数据，数据集小的话效果不一定好**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=276)
- `0:04:50`**这里是 kv_cache 吗？**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=290)
- `0:05:12`**Concat 什么操作啊？是指隐藏层数据相加吗，那不就失去时序特性了吗？**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=312)
- `0:05:14`**相当于用隐层把不同长度统一成相同长度？**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=314)
- `0:05:21`**前面的，是的！但逐个单词合并就是为了编码词的顺序！**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=321)
- `0:05:33`**可逆就可以肯定信息无损**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=333)
- `0:05:46`**肯定是不可逆，就像哈希值能回推原文么？**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=346)
- `0:05:49`**如果文本太长的话可能会导致网络的隐藏参数不够用，会忘掉最开始的内容**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=349)
- `0:07:19`**这个h是RNN中隐藏层的输出，不是最终输出**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=439)
- `0:07:47`**rnn缺点就是不能并行**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=467)
- `0:07:52`**这样不是线性和了吗，还是concat吗**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=472)
- `0:07:52`**能并行就没transformer什么事情了**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=472)
- `0:09:05`**播放1.5万，点赞只有1000多？**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=545)
- `0:09:17`**都在认真学习，忘了点赞了**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=557)
- `0:09:18`**一部分是重复学习的吧**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=558)
- `0:09:23`**会不会只是感觉前面的Ht-1有更多的信息，而Xt只是相对于前面的信息少一点**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=563)
- `0:09:43`**12人正在观看。。。。**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=583)
- `0:10:52`**why no mxnet**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=652)
- `0:11:07`**这个不是隐藏层的数量吗？不是输出吧**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=667)
- `0:11:41`**为什么一个用randn，一个用rand呢**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=701)
- `0:11:45`**應該是筆誤吧，我覺得應該都是randn**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=705)
- `0:12:03`**B 和 C H W 对于图片**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=723)
- `0:12:13`**发繁体字的都是什么成分**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=733)
- `0:12:16`**num_steps=10代表前面10个词预测下一个词，batch_size怎么理解呢**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=736)
- `0:13:22`**终于明白hidden_state怎么来的了**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=802)
- `0:13:31`**输入输出都是一样个数？**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=811)
- `0:14:03`**卧槽，一直以为一个step就有一个小单元**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=843)
- `0:14:15`**如果w_hh是一个东西的话，是不是每次得到的H向量的长度是一样的**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=855)
- `0:14:15`**Loss怎么计算？反向传播？**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=855)
- `0:15:23`**这边H应该还要接一个softmax吧，感觉是不是要softmax之后得到y呢**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=923)
- `0:15:24`**方向是语序方向吧，和书写方向有关系吗？**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=924)
- `0:15:26`**举个例子有啥可杠的啊……**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=926)
- `0:15:29`**计算机读取只会从左往右，管你语序是从哪到哪**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=929)
- `0:15:32`**双向主要是害怕把最前面的忘了**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=932)
- `0:15:35`**没关系，大神就是可爱了一下**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=935)
- `0:15:40`**反着写难道你还正看吗**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=940)
- `0:15:46`**这个yt是yhat吗**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=946)
- `0:15:46`**在做一些multi-languange的任务的时候，采集到的数据可能有从左往右读的，也有从右往左读的，人工一个一个分辨太浪费时间了，直接双向多好**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=946)
- `0:15:50`**两个方向是求和得最终输出吗**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=950)
- `0:15:55`**语义有时候也需要结合上下文**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=955)
- `0:16:07`**主要是为了获得语法特征吧**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=967)
- `0:16:10`**确实例子有点不恰当，可以用高考语文古诗填空的思想理解**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=970)
- `0:16:21`**双向是为了更好的获取上下文的语义特征**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=981)
- `0:16:38`**完形填空好巧妙的形容**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=998)
- `0:17:09`**这个多层 是横着的RNN数量吧 竖着只有双向两层**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=1029)
- `0:17:45`**这里speech是语音吧**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=1065)
- `0:17:46`**RNN 还有对周期类数据，比如天气预报是有用的**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=1066)
- `0:18:16`**speech为啥是语音？**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=1096)
- `0:18:27`**speech偏向实时，audio偏向是文件**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=1107)
- `0:18:57`**swin-transformer**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=1137)
- `0:19:15`**transformers是不是不用标注？**　[↗](https://www.bilibili.com/video/BV1pq4y1r7zo?t=1155)
