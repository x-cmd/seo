---
x-title: 什么是 DA？—— Moz 域名权重 + Ahrefs DR，新手也能看懂
x-desc: >-
  DA（Domain Authority）是 Moz 给网站打的"信任"分，0–100。
  Ahrefs 的对应分数叫 DR（Domain Rating）。本文用大白话讲清
  这两个分数是什么、回答新手最常问的问题（"DA 是 Google 的
  分数吗？"），并带你一步步查任何一个网站。
x-sidebar: 什么是 DA？
x-keywords: da, domain authority, moz da, dr, domain rating, ahrefs dr, 域名权重, 第三方 seo 指标, 新手入门
x-json-ld:
  '@context': https://schema.org
  '@graph':
    - '@type': TechArticle
      headline: '什么是 DA —— Moz 域名权重与 Ahrefs DR 入门'
      inLanguage: 'cn'
      about: '域名权重与域名评分——一篇讲清'
---

# 什么是 DA？—— Moz 域名权重 + Ahrefs DR，新手也能看懂

先回答你大概率是从搜索框里敲出来、找过来的那个问题：

**"DA 是 Google 的分数吗？"**

答：**不是**。DA **不是** Google 的分数，也不是 Bing 的、
百度的、任何一个搜索引擎的分数。DA 是 [Moz](https://moz.com/)
这家公司打的分，从 2005 年左右就有了。另一家公司
[Ahrefs](https://ahrefs.com/) 打了个类似的东西，叫 DR。

如果你想问的是"Google 怎么看我网站的权威度"，那是另一回事——
**Google 根本不公布权威度分数**。（Google 当年公开过一个叫
[PageRank](https://en.wikipedia.org/wiki/PageRank) 的链接分数，
是所有这类分数的老祖宗；但 2016 年他们把公开的 PageRank
工具栏下线了。）Google 给你的最接近的东西是
**[Google Search Console](https://search.google.com/search-console)**——
它能告诉你 Google 怎么收录你的站、哪些查询给你带来流量、
有没有收到人工操作——但**它不给你一个"DA 数字"**。

所以当你听到有人讲"我的 DA 是 35"，说的是 **Moz** 给他们站的
打分，不是 Google 的。把这层关系记住，下面的内容就都顺了。

## 三秒钟版本

如果只看一段，看这段。

**DA（Domain Authority）和 DR（Domain Rating）是 SEO 工具公司
做的"第三方信任分"。** 都是 0–100，越高越好。适合在同一个工具
里对比两个网站，不是直接的排名因子——Google 决定页面排第几
的时候不会去查 DA 或 DR。它们只是根据每个站的反向链接档案
估算的"代理指标"。

就这些。下面一页一段慢慢讲。

## DA 到底是什么——用大白话讲

**DA** 是 **Domain Authority（域名权重）** 的缩写。
[Moz](https://moz.com/) 给它知道的每个网站打一个 0–100 的
分数。这个想法大概在 2005 年就有了，那时候公司还叫
"SEOmoz"。它是这一类链接权威度分数里最早的一个——后面
其他分数基本都是从它演变过来的。

Moz 算你 DA 的时候，主要看两件事：

- **有多少个不同的网站链接到你。** 来自 `cnn.com` 的一个
  链接和来自 `mycousinsblog.com` 的一个链接都算，但它们
  算**两个不同的"链接根域名"**，不是两个链接。所以
  从同一个站来 100 条链接，不如从 100 个不同的站来
  100 条链接。
- **链接你的那些站有多权威。** 如果链接你的站自己 DA
  很高，那这一票比来自低 DA 站的要重得多。来自 BBC
  的一个链接抵得上来自随机博客的一千个。

Moz 还会看几个次要信号——你的链接模式看起来是否自然、
有没有垃圾信号——但 DA 的大部分就是"有多少站链你，
它们好不好"。

大多数真实网站的 DA 在 10–70 之间。新站从 0 起步。
成熟的品牌站大多在 70–90。DA 100 留给 google.com、
facebook.com 这种——基本上整个互联网都已经链向它了。

## DR 是什么，跟 DA 怎么比

**DR** 是 **Domain Rating（域名评分）** 的缩写。
[Ahrefs](https://ahrefs.com/) 在 DA 之后几年推出了它。
大方向一样——一个 0–100 的分数，告诉你"这个站的反向链接
档案有多强"——但配方不一样。

最大的实际差别是 **DR 只算 dofollow 链接**。Dofollow 链接
是默认那种——一个站链另一个站，没加任何特殊标记，搜索引擎
就当作一票支持。**Nofollow** 是反过来——告诉搜索引擎
"这票别算"。DR 完全忽略 nofollow 链接；DA 给它们部分
信用。

DR 看的面也更窄——就看你有多少 dofollow 引用域名，以及
这些引用域名各自的 DR。不看流量、不看锚文本（链接里
那个可点击的文字）、不加任何别的信号。这让 DR 比 DA 更
"纯"，更接近一个纯链接图指标。

实际中两个分数一般落在大致相同的范围，但不会完全一致。
一个长期存在、被知名站点链接的站，两个工具给的分数都
会高。一个链接档案不太寻常的站——比如大部分是论坛签名
或者大部分是 nofollow 的新闻提及——两个工具给的分数
可能差得比较多。

## 0–100 的刻度是怎么一回事

DA 和 DR 都用**对数刻度**。"对数"听着像术语，但实际含义
很简单：**每往上一级都比上一级更难**。

如果你听说过地震的里氏震级，那你已经见过对数刻度了。
里氏 5 级地震不是里氏 1 级地震的 5 倍大——大概是
10 万倍大。每升一级，幅度就跳一大截。里氏震级就是对数
刻度。

DA 和 DR 的逻辑一样：

- DA 10 → 20：正常做反向链接几个月可达。
- DA 30 → 40：明显更难了。
- DA 50 → 60：再难一档。
- DA 70 → 80：很难。
- DA 80 → 90：精英级别，只有持续大规模被引用的站才能到。

所以听到有人说"我们半年把 DR 从 12 做到 35"，这是有分量的
进步——跨越了低中段一段距离。听到有人说"我们半年把 DR
从 78 做到 82"，虽然数字只涨了 4，其实是更大的成就。
刻度的顶部，每一级比底部跳得更大。

## 为什么两个分数对不上

同一个站用 Moz 和 Ahrefs 查，拿到的数字大概率不一样。
两个原因。

**它们看到的互联网不一样。** Moz 有自己的爬虫——数据库叫
Mozscape，爬虫本体叫 Rogerbot。Ahrefs 也有自己的爬虫，
叫 AhrefsBot。两套爬虫，两套理解。一套爬虫看到、另一套
没看到的站，就只在一个工具里出现。一套爬虫发现、另一套
没发现的链接，就只在一个工具里被算。

**它们用的公式不一样。** DA 在原始链接之外还混进了几个
信号——站点整体权威度、链接模式质量之类。DR 接近纯
链接计数。所以哪怕两边的爬虫看到完全一样的链接集，
得出来的分数也不会相等，因为算式不同。

实际一条就一条——**DA 和 DR 适合在同一工具内对比站，
不适合跨工具下结论。**"我的 DR 比竞品高"是有用的对比；
"我的 DA 是 35 他们是 50，所以我排名比他们低"——这个推论
不成立。

## 怎么查任何一个站的 DA 或 DR

这是实操部分。有四个工具值得知道，按上手难度排。

### Ahrefs 网站权重检查器——不登录，只人机验证

想不登录拿一个 DR 数字，最快的入口是
**[Ahrefs 网站权重检查器](https://ahrefs.com/zh/website-authority-checker/)**。
它只给 DR（Ahrefs 做 DR，不做 DA），但这是最快的查询，
不花钱。

步骤：

1. 浏览器打开 [ahrefs.com/zh/website-authority-checker](https://ahrefs.com/zh/website-authority-checker/)。
2. 页面会让人做个"人机验证"——常见那种"我不是机器人"
   勾选框。点过去。
3. 在输入框里输入一个域名，比如 `example.com`。
4. 回车。
5. 就能看到这个域名的 DR，外加几个相关指标——多少站链它、
   链接数量随时间的趋势、链它的主要国家等。

无需账号、无需信用卡、无需邮箱。URL 里的 `/zh/` 给中文界面，
中文用户用着更顺手；想要英文就把 `/zh/` 去掉。

这几乎是所有人推荐的第一站——一分钟出活。

### Moz Domain Analysis——需要登录，给 DA

发明 DA 的 Moz 公司没有完全免登录的查询入口。要看 DA，
得有个 Moz 账号。

入口是 **[Moz Domain Analysis](https://moz.com/domain-analysis)**。
免费 Moz 账号每月能查的次数不多（我们上次知道是大约
10 次/月）。付费 Moz Pro 账号不限次，能完整访问 Moz 的
反向链接数据库。

如果你已经有 Moz 账号——免费或付费——直接登录查。如果没有，
只是想看个数字，上面的 Ahrefs 检查器能给你 DR，且是免费的。
DA 和 DR 接近到这种程度，光看 DR 对大多数场景够用。

### Semrush Authority Score——需要登录，第三方参照

如果你已经在订阅 Semrush，他们的指标叫
**[Semrush Authority Score](https://www.semrush.com/analytics/overview/)**，
也是 0–100，反向链接加一些其他信号混合算出来的。Semrush
也没有匿名查询入口——得有免费试用或付费账号。如果已经在
用 Semrush，那 Authority Score 跟 Moz / Ahrefs 一起看，是个
不错的第二视角。

### Majestic Trust Flow 与 Citation Flow——部分免费

[Majestic](https://majestic.com/) 比 Moz 和 Ahrefs 都老。
他们打两个分——Trust Flow（链接质量）和 Citation Flow
（链接数量），各 0–100。年代比 DA 和 DR 都早。Majestic
有个 [免费的公开 Site Explorer](https://majestic.com/reports/site-explorer)，
但深度有限——完整查询要登录。

## 这个分数实际意味着什么（又不能意味着什么）

这是大多数教程跳过、但其实最重要的部分。

DA 和 DR 适合做**相对对比**，不是绝对判断。举几个有用和
没用的解读。

### 有用的解读

- "我的 DR 半年从 12 涨到 35。"——这意味着反向链接档案
  显著增长。好信号。
- "竞品 DR 65，我 DR 30。"——在链接图维度你有一个明显
  的差距要补。规划好节奏。
- "我的 DR 是 70。"——筛选外链市场的一个合理门槛——
  大多数"DR 50+"的外链卖家在卖的就是这一档的站。

### 没用的解读

- "我的 DA 是 35，所以我的页面会排得很高。"——错。DA 不
  告诉你页面是否回答了查询、加载多快、移不移动友好，
  也不告诉你 Google 是否觉得它可信。DA 只是众多输入之一。
- "我要买点便宜外链把 DR 顶上去。"——通常适得其反。
  Google 会惩罚明显的链接买卖。而且就算有用，作用也比
  你想的小——DR 给高 DR 链接的权重远大于低 DR 链接。
- "DA 30 + DR 50 等于 DA 50 + DR 30。"——不是。每个工具
  度量的是稍微不一样的东西，差距告诉你的是链接图的特征，
  不是排名。

## 常见的几个坑

几个会绊到新手的事情。不是大问题——知道就行。

**分数会自己动。** Moz 和 Ahrefs 都在滚动更新自己的链接索引。
一个站一周可能 ±2 到 5 分 DR 的波动，没人新建或丢失任何
链接。小波动不用慌。

**缓存的分数会骗人。** 有些站在首页嵌了个"DR / DA"的徽章，
但已经好几个月没更新了。看一眼底层分数的时间戳，或者
自己重新查一遍。

**Spam Score 是 Moz 的独立分数。** Moz 在 DA 旁边还报一个
[Spam Score](https://moz.com/learn/seo/spam-score)——独立的
0–100 分，估算一个域名看起来有多"垃圾"。高 DA + 高 Spam
Score 是个红旗——通常意味着 DA 是被低质量链接顶上去的。
判断域名时用它当过滤器，别事后才想起来。

**Nofollow vs dofollow 有影响。** DR 完全忽略 nofollow 链接；
DA 给它们部分信用。如果你的链接档案里大部分是 nofollow
（论坛 profile 之类），DR 看起来会很惨，DA 可能看着还行。
两种视角都有用。

**打的是根域名，不是子域名。** DA 和 DR 打的是根域名。
`blog.example.com` 上的强链接贡献给 `example.com` 的分数，
不是给 `blog.example.com` 自己。如果你有内容放在子域名上，
积分归父级。

**Moz 的索引不一定新。** Moz 的爬虫比 Ahrefs 慢。如果 Moz
最近没爬你的新链接，你的 DA 可能比真实情况落后几周。DR
（来自 Ahrefs）通常更新。

## 走一遍：查一个站

假设你想查 `wikipedia.org` 的 DR。实际操作步骤：

**第一步**：浏览器打开 [ahrefs.com/zh/website-authority-checker](https://ahrefs.com/zh/website-authority-checker/)。

**第二步**：勾一下"I am not a robot"过掉人机验证。一般一点
就过。

**第三步**：在输入框里打 `wikipedia.org`，回车。

**第四步**：你会看到 Wikipedia 的 DR——大概是 90 多，
因为 Wikipedia 是互联网上被链最多的站之一——加几个相关
数字：多少站链它、链接数随时间的趋势、链它的主要国家等。

**第五步**：这就是你的 DR。一分钟内搞定，不用注册账号。

如果你还想要 DA，再去 https://www.moz.com/domain-analysis
（[Moz Domain Analysis](https://moz.com/domain-analysis)），
登录 Moz 账号，输入同一个域名，看 Wikipedia 的 DA。Wikipedia
的 DA 也非常高（90 多），但大概率跟 DR 不一样——是上面讲过
的索引和公式差异。

这就是整个查询流程。多数场景只看 DR 就够了；DA 是
已经有 Moz 订阅时的补充。

## 一览表

| 工具 | 指标 | 分数范围 | 要登录？ | 查询入口 |
| --- | --- | --- | --- | --- |
| Moz | DA（Domain Authority） | 0–100 | 是——免费或付费账号 | [Moz Domain Analysis](https://moz.com/domain-analysis) |
| Ahrefs | DR（Domain Rating） | 0–100 | **否**——只人机验证 | [Ahrefs 网站权重检查器](https://ahrefs.com/zh/website-authority-checker/) |
| Semrush | Authority Score | 0–100 | 是——免费试用或付费 | [Semrush Analytics Overview](https://www.semrush.com/analytics/overview/) |
| Majestic | Trust Flow / Citation Flow | 各 0–100 | 部分——有限免费 | [Majestic Site Explorer](https://majestic.com/reports/site-explorer) |

## 下一步

DA 和 DR 是快速了解一个站权威度的有用指标，不是目标本身。
真正的排名工作在搜索引擎那一层。如果你在做 Google（迄今
最大的引擎），下一篇读 [3-google-seo](https://x-cmd.com/seo/google-seo)
即可。受众在哪里，再加读对应引擎。

想看官方定义，参考以下页面：

- [Moz 对 DA 的解释](https://moz.com/learn/seo/domain-authority)
- [Ahrefs 对 DR 的解释](https://ahrefs.com/blog/domain-rating/)
- [Moz 对 Spam Score 的解释](https://moz.com/learn/seo/spam-score)

[Wikipedia 的 PageRank 条目](https://en.wikipedia.org/wiki/PageRank)
也值得一读——PageRank 是 Google 1990 年代末的原始链接分数，
DA、DR、还有这一类所有分数，都是它的精神后裔。