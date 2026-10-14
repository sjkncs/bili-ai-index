# 弹幕讨论 · DeepMind AlphaCode 论文精读【论文精读】

> 视频：[BV1ab4y1s7rc](https://www.bilibili.com/video/BV1ab4y1s7rc)　时长 0:44:01　弹幕总数 **132**　有实质内容 **56** 条　重点标记 **56** 条
>
> 来源：B 站 **跟李沐学AI** 的该集弹幕　快照：**2026-10-14**

## 口径说明（务必先读）

**这些内容全部是观众在视频上发的弹幕，不是经过核实的结论。**

- 其中有价值的：概念解释、类比、勘误、学习方法、延伸阅读线索。
- **也可能有错误的**：弹幕是个人理解，未经作者或权威确认。
  **本页不为其正确性背书，请勿直接引用为事实。**
- 每条带时间戳，点击可跳回视频对应位置自行核对。
- 筛选口径：保留长度 ≥ 10 字符、且不含纯感叹/打卡类噪声的弹幕，共 56 条（占该集弹幕 132 条的 42.4%）；同一句话被多人发送只保留一条并标注发送次数。
- 「重点」标记由关键词打分得出（技术词 + 解释性措辞 + 长度 + 多人重复），共 56 条；**它是启发式排序，不代表正确性，也不代表其余条目无价值。**

## 重点条目

| 时间 | 弹幕 | 发送次数 |
|---|---|---:|
| [0:00:01](https://www.bilibili.com/video/BV1ab4y1s7rc?t=1) | 地主家也没有余粮啊[doge] | 1 |
| [0:00:26](https://www.bilibili.com/video/BV1ab4y1s7rc?t=26) | 正式版2022年12月发了Science | 1 |
| [0:00:29](https://www.bilibili.com/video/BV1ab4y1s7rc?t=29) | 2022年12月登上了science的封面文章 | 1 |
| [0:00:30](https://www.bilibili.com/video/BV1ab4y1s7rc?t=30) | 你打败了我，就这样打败了我 | 1 |
| [0:00:55](https://www.bilibili.com/video/BV1ab4y1s7rc?t=55) | 可以用这个打google code jam吗 | 1 |
| [0:01:32](https://www.bilibili.com/video/BV1ab4y1s7rc?t=92) | 要是我参加了这比例还能更高 | 1 |
| [0:01:34](https://www.bilibili.com/video/BV1ab4y1s7rc?t=94) | 沃日，我已经被打败了 | 1 |
| [0:01:36](https://www.bilibili.com/video/BV1ab4y1s7rc?t=96) | 5000 多个参数人员 | 1 |
| [0:01:51](https://www.bilibili.com/video/BV1ab4y1s7rc?t=111) | codeforces自动刷题 | 1 |
| [0:04:57](https://www.bilibili.com/video/BV1ab4y1s7rc?t=297) | 现在新号都是0分了。1238大概是会一些简单的算法的水平。 | 1 |
| [0:05:48](https://www.bilibili.com/video/BV1ab4y1s7rc?t=348) | o3已经单挑icpc总决赛金牌了 | 1 |
| [0:06:02](https://www.bilibili.com/video/BV1ab4y1s7rc?t=362) | 终于反应过来回退是删除2333 | 1 |
| [0:06:18](https://www.bilibili.com/video/BV1ab4y1s7rc?t=378) | 这用的什么软件看的pdf啊 | 1 |
| [0:06:27](https://www.bilibili.com/video/BV1ab4y1s7rc?t=387) | leetcode521题，最长特殊序列。。 | 1 |
| [0:07:49](https://www.bilibili.com/video/BV1ab4y1s7rc?t=469) | 这题真不难，比正常签到题难一点顶天了 | 1 |
| [0:07:52](https://www.bilibili.com/video/BV1ab4y1s7rc?t=472) | 类似的题Leetcode 844 | 1 |
| [0:07:55](https://www.bilibili.com/video/BV1ab4y1s7rc?t=475) | lc844范围才200，n方的DP就行。这题10w | 1 |
| [0:07:56](https://www.bilibili.com/video/BV1ab4y1s7rc?t=476) | 而且844都告诉你哪里回退了 | 1 |
| [0:08:20](https://www.bilibili.com/video/BV1ab4y1s7rc?t=500) | 分字符减少的数量是奇数和偶数2种情况吧 | 1 |
| [0:08:20](https://www.bilibili.com/video/BV1ab4y1s7rc?t=500) | 爆搜那保底分（doge） | 1 |
| [0:08:22](https://www.bilibili.com/video/BV1ab4y1s7rc?t=502) | 在s中找到所有子序列t，找到其中两两元素间隔为偶数的 | 1 |
| [0:08:23](https://www.bilibili.com/video/BV1ab4y1s7rc?t=503) | 随机输出yes no | 1 |
| [0:08:26](https://www.bilibili.com/video/BV1ab4y1s7rc?t=506) | cf的题哪来的保底分啊(doge | 1 |
| [0:08:30](https://www.bilibili.com/video/BV1ab4y1s7rc?t=510) | codeforce是ac制 | 1 |
| [0:08:36](https://www.bilibili.com/video/BV1ab4y1s7rc?t=516) | 一小时前刚才力扣上做过类似的。。。。 | 1 |
| [0:08:39](https://www.bilibili.com/video/BV1ab4y1s7rc?t=519) | 先不管输入输出，先判断in&amp;out的长度，以及是否有in中无的出现在out中，根据这个先删掉一部分No, 剩下的再判断。 | 1 |
| [0:10:00](https://www.bilibili.com/video/BV1ab4y1s7rc?t=600) | leetcode 罚时间（doge)） | 1 |
| [0:10:37](https://www.bilibili.com/video/BV1ab4y1s7rc?t=637) | tourist：直接倒开 | 1 |
| [0:10:55](https://www.bilibili.com/video/BV1ab4y1s7rc?t=655) | 一边听，一边写代码？？ | 1 |
| [0:10:59](https://www.bilibili.com/video/BV1ab4y1s7rc?t=659) | 这让我一下回想起了当年本科打比赛的时候 | 1 |
| [0:11:07](https://www.bilibili.com/video/BV1ab4y1s7rc?t=667) | 当年1小时读完全部题目，然后看队友表演就好了。 | 1 |
| [0:14:23](https://www.bilibili.com/video/BV1ab4y1s7rc?t=863) | C++哈哈哈哈哈，最低 | 1 |
| [0:14:58](https://www.bilibili.com/video/BV1ab4y1s7rc?t=898) | 假阳性，隔离14天。 | 1 |
| [0:15:02](https://www.bilibili.com/video/BV1ab4y1s7rc?t=902) | c++,java都忘了差不多了，就剩下python会点了 | 1 |
| [0:16:56](https://www.bilibili.com/video/BV1ab4y1s7rc?t=1016) | openAI 真的是 不遗余力推广GPT啊 | 1 |
| [0:18:06](https://www.bilibili.com/video/BV1ab4y1s7rc?t=1086) | 听上去还是像机器翻译 | 1 |
| [0:18:45](https://www.bilibili.com/video/BV1ab4y1s7rc?t=1125) | group attention | 1 |
| [0:19:29](https://www.bilibili.com/video/BV1ab4y1s7rc?t=1169) | 这个终于算是比较小批量了 | 1 |
| [0:22:08](https://www.bilibili.com/video/BV1ab4y1s7rc?t=1328) | 就是希望结果取更多概率高的结果 | 1 |
| [0:22:11](https://www.bilibili.com/video/BV1ab4y1s7rc?t=1331) | 大概可以将T理解为正态分布的标准差，所以T越小越尖锐（当然原理不同） | 1 |
| [0:26:54](https://www.bilibili.com/video/BV1ab4y1s7rc?t=1614) | 也没听懂这个测试样例是那个测试样例。 | 1 |
| [0:26:59](https://www.bilibili.com/video/BV1ab4y1s7rc?t=1619) | 说人话就是训练另一个生成式模型用来生成测试，然后根据测试生成的结果来对不同的program进行聚类。 | 1 |
| [0:27:20](https://www.bilibili.com/video/BV1ab4y1s7rc?t=1640) | 这里确实没讲这些新的测试样例怎么生成的 主要是用来聚类 | 1 |
| [0:27:42](https://www.bilibili.com/video/BV1ab4y1s7rc?t=1662) | 对同一个测试用例有相似的输出 → 聚为一类 → 选择代表代码（类别越大说明模型越倾向） | 1 |
| [0:28:35](https://www.bilibili.com/video/BV1ab4y1s7rc?t=1715) | 感觉就是换个数据集调一调，出个实验报告 | 1 |
| [0:28:50](https://www.bilibili.com/video/BV1ab4y1s7rc?t=1730) | 我觉得我能打败100%的选手（狗头 | 1 |
| [0:29:50](https://www.bilibili.com/video/BV1ab4y1s7rc?t=1790) | 还是故事讲得好，代码生成10次写得这么轻描淡写 | 1 |
| [0:33:54](https://www.bilibili.com/video/BV1ab4y1s7rc?t=2034) | 两个点之间有些为什么不是直线？ | 1 |
| [0:34:10](https://www.bilibili.com/video/BV1ab4y1s7rc?t=2050) | Ablation study | 1 |
| [0:36:24](https://www.bilibili.com/video/BV1ab4y1s7rc?t=2184) | 一大堆头文件 有可能 | 1 |
| [0:39:51](https://www.bilibili.com/video/BV1ab4y1s7rc?t=2391) | random tag是可以增加结果多样性吗？ | 1 |
| [0:39:55](https://www.bilibili.com/video/BV1ab4y1s7rc?t=2395) | 是的，论文里是这么说的 | 1 |
| [0:43:04](https://www.bilibili.com/video/BV1ab4y1s7rc?t=2584) | openai喜欢闷声发大财 | 1 |
| [0:43:21](https://www.bilibili.com/video/BV1ab4y1s7rc?t=2601) | 毕竟OpenAI 已经背离初心了 | 1 |
| [0:43:39](https://www.bilibili.com/video/BV1ab4y1s7rc?t=2619) | tourist或成下一个李世石 | 1 |
| [0:43:41](https://www.bilibili.com/video/BV1ab4y1s7rc?t=2621) | leader board terminator！ | 1 |

## 全部有实质内容的弹幕（按时间排序，共 56 条）

- `0:00:01`**地主家也没有余粮啊[doge]**　[↗](https://www.bilibili.com/video/BV1ab4y1s7rc?t=1)
- `0:00:26`**正式版2022年12月发了Science**　[↗](https://www.bilibili.com/video/BV1ab4y1s7rc?t=26)
- `0:00:29`**2022年12月登上了science的封面文章**　[↗](https://www.bilibili.com/video/BV1ab4y1s7rc?t=29)
- `0:00:30`**你打败了我，就这样打败了我**　[↗](https://www.bilibili.com/video/BV1ab4y1s7rc?t=30)
- `0:00:55`**可以用这个打google code jam吗**　[↗](https://www.bilibili.com/video/BV1ab4y1s7rc?t=55)
- `0:01:32`**要是我参加了这比例还能更高**　[↗](https://www.bilibili.com/video/BV1ab4y1s7rc?t=92)
- `0:01:34`**沃日，我已经被打败了**　[↗](https://www.bilibili.com/video/BV1ab4y1s7rc?t=94)
- `0:01:36`**5000 多个参数人员**　[↗](https://www.bilibili.com/video/BV1ab4y1s7rc?t=96)
- `0:01:51`**codeforces自动刷题**　[↗](https://www.bilibili.com/video/BV1ab4y1s7rc?t=111)
- `0:04:57`**现在新号都是0分了。1238大概是会一些简单的算法的水平。**　[↗](https://www.bilibili.com/video/BV1ab4y1s7rc?t=297)
- `0:05:48`**o3已经单挑icpc总决赛金牌了**　[↗](https://www.bilibili.com/video/BV1ab4y1s7rc?t=348)
- `0:06:02`**终于反应过来回退是删除2333**　[↗](https://www.bilibili.com/video/BV1ab4y1s7rc?t=362)
- `0:06:18`**这用的什么软件看的pdf啊**　[↗](https://www.bilibili.com/video/BV1ab4y1s7rc?t=378)
- `0:06:27`**leetcode521题，最长特殊序列。。**　[↗](https://www.bilibili.com/video/BV1ab4y1s7rc?t=387)
- `0:07:49`**这题真不难，比正常签到题难一点顶天了**　[↗](https://www.bilibili.com/video/BV1ab4y1s7rc?t=469)
- `0:07:52`**类似的题Leetcode 844**　[↗](https://www.bilibili.com/video/BV1ab4y1s7rc?t=472)
- `0:07:55`**lc844范围才200，n方的DP就行。这题10w**　[↗](https://www.bilibili.com/video/BV1ab4y1s7rc?t=475)
- `0:07:56`**而且844都告诉你哪里回退了**　[↗](https://www.bilibili.com/video/BV1ab4y1s7rc?t=476)
- `0:08:20`**分字符减少的数量是奇数和偶数2种情况吧**　[↗](https://www.bilibili.com/video/BV1ab4y1s7rc?t=500)
- `0:08:20`**爆搜那保底分（doge）**　[↗](https://www.bilibili.com/video/BV1ab4y1s7rc?t=500)
- `0:08:22`**在s中找到所有子序列t，找到其中两两元素间隔为偶数的**　[↗](https://www.bilibili.com/video/BV1ab4y1s7rc?t=502)
- `0:08:23`**随机输出yes no**　[↗](https://www.bilibili.com/video/BV1ab4y1s7rc?t=503)
- `0:08:26`**cf的题哪来的保底分啊(doge**　[↗](https://www.bilibili.com/video/BV1ab4y1s7rc?t=506)
- `0:08:30`**codeforce是ac制**　[↗](https://www.bilibili.com/video/BV1ab4y1s7rc?t=510)
- `0:08:36`**一小时前刚才力扣上做过类似的。。。。**　[↗](https://www.bilibili.com/video/BV1ab4y1s7rc?t=516)
- `0:08:39`**先不管输入输出，先判断in&amp;out的长度，以及是否有in中无的出现在out中，根据这个先删掉一部分No, 剩下的再判断。**　[↗](https://www.bilibili.com/video/BV1ab4y1s7rc?t=519)
- `0:10:00`**leetcode 罚时间（doge)）**　[↗](https://www.bilibili.com/video/BV1ab4y1s7rc?t=600)
- `0:10:37`**tourist：直接倒开**　[↗](https://www.bilibili.com/video/BV1ab4y1s7rc?t=637)
- `0:10:55`**一边听，一边写代码？？**　[↗](https://www.bilibili.com/video/BV1ab4y1s7rc?t=655)
- `0:10:59`**这让我一下回想起了当年本科打比赛的时候**　[↗](https://www.bilibili.com/video/BV1ab4y1s7rc?t=659)
- `0:11:07`**当年1小时读完全部题目，然后看队友表演就好了。**　[↗](https://www.bilibili.com/video/BV1ab4y1s7rc?t=667)
- `0:14:23`**C++哈哈哈哈哈，最低**　[↗](https://www.bilibili.com/video/BV1ab4y1s7rc?t=863)
- `0:14:58`**假阳性，隔离14天。**　[↗](https://www.bilibili.com/video/BV1ab4y1s7rc?t=898)
- `0:15:02`**c++,java都忘了差不多了，就剩下python会点了**　[↗](https://www.bilibili.com/video/BV1ab4y1s7rc?t=902)
- `0:16:56`**openAI 真的是 不遗余力推广GPT啊**　[↗](https://www.bilibili.com/video/BV1ab4y1s7rc?t=1016)
- `0:18:06`**听上去还是像机器翻译**　[↗](https://www.bilibili.com/video/BV1ab4y1s7rc?t=1086)
- `0:18:45`**group attention**　[↗](https://www.bilibili.com/video/BV1ab4y1s7rc?t=1125)
- `0:19:29`**这个终于算是比较小批量了**　[↗](https://www.bilibili.com/video/BV1ab4y1s7rc?t=1169)
- `0:22:08`**就是希望结果取更多概率高的结果**　[↗](https://www.bilibili.com/video/BV1ab4y1s7rc?t=1328)
- `0:22:11`**大概可以将T理解为正态分布的标准差，所以T越小越尖锐（当然原理不同）**　[↗](https://www.bilibili.com/video/BV1ab4y1s7rc?t=1331)
- `0:26:54`**也没听懂这个测试样例是那个测试样例。**　[↗](https://www.bilibili.com/video/BV1ab4y1s7rc?t=1614)
- `0:26:59`**说人话就是训练另一个生成式模型用来生成测试，然后根据测试生成的结果来对不同的program进行聚类。**　[↗](https://www.bilibili.com/video/BV1ab4y1s7rc?t=1619)
- `0:27:20`**这里确实没讲这些新的测试样例怎么生成的 主要是用来聚类**　[↗](https://www.bilibili.com/video/BV1ab4y1s7rc?t=1640)
- `0:27:42`**对同一个测试用例有相似的输出 → 聚为一类 → 选择代表代码（类别越大说明模型越倾向）**　[↗](https://www.bilibili.com/video/BV1ab4y1s7rc?t=1662)
- `0:28:35`**感觉就是换个数据集调一调，出个实验报告**　[↗](https://www.bilibili.com/video/BV1ab4y1s7rc?t=1715)
- `0:28:50`**我觉得我能打败100%的选手（狗头**　[↗](https://www.bilibili.com/video/BV1ab4y1s7rc?t=1730)
- `0:29:50`**还是故事讲得好，代码生成10次写得这么轻描淡写**　[↗](https://www.bilibili.com/video/BV1ab4y1s7rc?t=1790)
- `0:33:54`**两个点之间有些为什么不是直线？**　[↗](https://www.bilibili.com/video/BV1ab4y1s7rc?t=2034)
- `0:34:10`**Ablation study**　[↗](https://www.bilibili.com/video/BV1ab4y1s7rc?t=2050)
- `0:36:24`**一大堆头文件 有可能**　[↗](https://www.bilibili.com/video/BV1ab4y1s7rc?t=2184)
- `0:39:51`**random tag是可以增加结果多样性吗？**　[↗](https://www.bilibili.com/video/BV1ab4y1s7rc?t=2391)
- `0:39:55`**是的，论文里是这么说的**　[↗](https://www.bilibili.com/video/BV1ab4y1s7rc?t=2395)
- `0:43:04`**openai喜欢闷声发大财**　[↗](https://www.bilibili.com/video/BV1ab4y1s7rc?t=2584)
- `0:43:21`**毕竟OpenAI 已经背离初心了**　[↗](https://www.bilibili.com/video/BV1ab4y1s7rc?t=2601)
- `0:43:39`**tourist或成下一个李世石**　[↗](https://www.bilibili.com/video/BV1ab4y1s7rc?t=2619)
- `0:43:41`**leader board terminator！**　[↗](https://www.bilibili.com/video/BV1ab4y1s7rc?t=2621)
