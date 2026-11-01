---
x-title: 区域搜索引擎 —— 当 Google 不是默认选项
x-desc: >-
  各地区搜索引擎的实地指南 —— 本地引擎如何运作、市场份额数字为什么互相矛盾，
  以及在韩国、日本、越南、捷克、俄罗斯这些市场里到底该优化谁。
x-sidebar: 区域搜索引擎
x-keywords: 区域搜索引擎, 本地搜索引擎, naver, seznam, coccoc, 市场份额, 国际化 seo, 各国搜索引擎
x-json-ld:
  '@context': https://schema.org
  '@graph':
    - '@type': TechArticle
      headline: '区域搜索引擎 —— 当 Google 不是默认选项'
      inLanguage: 'cn'
      about: '各国搜索引擎市场份额与本地搜索引擎'
---

# 区域搜索引擎 —— 当 Google 不是默认选项

**先给结论：** 全球搜索里 Google 大约占 90%，「只做 Google」在多数
情况下是对的。但在大约十分之一的市场里，本地引擎真能拿到可观份额——
在俄罗斯接近 Google 的三倍，在韩国按查询量算比 Google 还多——而背后
的原因本身就值得弄明白。这一页讲清楚是哪些市场、本地引擎到底怎么运作、以及怎么读描述
它们的份额数字。

> **TL;DR。** 全球 Google 约 90%。例外集中在俄罗斯（Yandex 约 73%）、
> 韩国（Naver 约 46%–63%，取决于统计口径）、台湾（Yahoo! 约 13%）、
> 捷克（Seznam 约 12%）、日本（Yahoo! 约 9%）和越南（Cốc Cốc 约 4%）。
> 一个本地引擎值不值得投入，看三件事：它有没有**自己的索引**、
> 有没有**自己的站长工具**、当地用户**搜索方式是不是不一样**。
> 三条里有一条不成立，做 Google 就够了。

## 我真的需要优化第二个引擎吗？

先问自己一句话：*我的用户在哪里，他们是不是用当地的方式搜索？*

多数站点只卖一个国家。如果那个国家是美国、英国、德国、法国、印度、
巴西，或者东南亚大部分地方，那么 Google 加上一两个跟班引擎就是全部
故事。如果你的用户在俄罗斯、韩国、捷克、越南、日本或台湾，答案就
不一样了，这一页会具体讲清楚差在哪。

陷阱在于，「本地」不等于「值得优化」。一个本地引擎只有在**它的索引
你借不到**的时候，才需要你投入。如果它只是换个皮重新吐 Google 的
结果，那你已经在 Google 上做的事已经覆盖了它，第二个策略只会白费工。

## 那个到处都在引用的数字 —— 以及它掩盖了什么

这是 2025 年的全球搜索份额，按月取平均：

[![2025 年全球搜索份额](https://x-cmd.com/draw?type=pie&t=market-mono&unit=%25&title=Worldwide%20search%20share%202025&labels=Google,Bing,Yandex,Yahoo!,DuckDuckGo,Baidu,Naver,CocCoc,Ecosia,Other&values=89.9,4.0,2.2,1.4,0.8,0.7,0.3,0.2,0.1,0.4)](https://x-cmd.com/draw/explore?type=pie&t=market-mono&unit=%25&title=Worldwide%20search%20share%202025&labels=Google,Bing,Yandex,Yahoo!,DuckDuckGo,Baidu,Naver,CocCoc,Ecosia,Other&values=89.9,4.0,2.2,1.4,0.8,0.7,0.3,0.2,0.1,0.4)

把它当成一份「剩下的」清单来看。Google 拿走每十次查询里的九次，
其余全部加起来约十分之一。Bing 以 4% 排第二，原因不是用户喜爱，
而是 Bing 预装在 Windows 和 Edge 上，很多人从来不改。Yandex 以 2.2%
排第三，几乎完全是因为它拿下了俄罗斯市场。1% 以下的在全球尺度上
都是舍入误差——哪怕其中几个在自己国家是绝对主导。

这就是本章唯一一张图要说的全部：**全球份额不等于市场份额。** 全球
0.3% 的引擎，在某个国家可能是多数派。

## 本地引擎只有三种形态

在一个本地引擎真正重要的市场里，下一个问题是它属于哪种类型。形态
只有三种，而它们对你要做的工作影响完全不同。

### 1. 自建索引

引擎自己爬网、自己排序。Naver、Yandex、百度、Seznam、Cốc Cốc 都
是这一类。

这是唯一需要单独做一套 SEO 策略的形态。引擎有自己的爬虫、自己的排序
信号、自己的站长工具，那么只提交给 Google 然后干等是不够的——你也
必须按它的规矩被收录进去。

### 2. 授权套壳

引擎借用别人的索引，自己加一层界面、一批自己的垂类、有时还有一层
自己的排序逻辑。Yahoo! JAPAN 用的是 Google 的索引，Yahoo! 台湾同理；
Ecosia 跑在 Bing 索引上，同时叠了自己的环保数据。

这种形态便宜得多。Google 上的工作基本能带过去。带不过去的是**呈现**
层面：谁排第一、你能不能拿到富结果卡片、标题和描述怎么被截断，以及
这个引擎自己的那一大块垂类生态会不会整个挡在自然结果前面。

### 3. 元搜索

引擎把你的查询转发给别的引擎，再把结果合起来。Startpage、MetaGer、
Qwant 都在不同阶段做过这件事。

对站点来说不需要任何额外的工作。如果 Startpage 代理的是 Google，你的
Google 排名就是你的 Startpage 排名。没有额外的提交，也没有额外的
工具要学。

## 哪些市场真的有本地霸主

下面是本章覆盖的每个市场里，Google 最大的对手，2025 年平均：

[![2025 年各市场 Google 的最大对手](https://x-cmd.com/draw?type=hbar&t=opendata&unit=%25&title=Biggest%20rival%20to%20Google%20by%20market%202025&labels=Russia%20-%20Yandex,South%20Korea%20-%20Naver,Taiwan%20-%20Yahoo!,Czechia%20-%20Seznam,Japan%20-%20Yahoo!,Germany%20-%20Bing,France%20-%20Bing,Philippines%20-%20Bing,Netherlands%20-%20Bing,Brazil%20-%20Bing,Vietnam%20-%20CocCoc,Indonesia%20-%20Bing,Thailand%20-%20Bing,India%20-%20Bing&values=73.2,45.6,13.3,11.6,9.4,6.4,5.4,5.7,4.9,5.9,4.4,2.5,1.4,1.3)](https://x-cmd.com/draw/explore?type=hbar&t=opendata&unit=%25&title=Biggest%20rival%20to%20Google%20by%20market%202025&labels=Russia%20-%20Yandex,South%20Korea%20-%20Naver,Taiwan%20-%20Yahoo!,Czechia%20-%20Seznam,Japan%20-%20Yahoo!,Germany%20-%20Bing,France%20-%20Bing,Philippines%20-%20Bing,Netherlands%20-%20Bing,Brazil%20-%20Bing,Vietnam%20-%20CocCoc,Indonesia%20-%20Bing,Thailand%20-%20Bing,India%20-%20Bing&values=73.2,45.6,13.3,11.6,9.4,6.4,5.4,5.7,4.9,5.9,4.4,2.5,1.4,1.3)

两件事很显眼。第一，真正要紧的是前五根柱：俄罗斯、韩国、台湾、捷克
和日本。再往下，「本地」引擎其实只是 Bing 默认设置堆出来的尾巴，
Google 加 Bing 就能覆盖整个市场。

第二，看柱子上写的是**哪个**引擎。德国、法国、巴西、菲律宾、荷兰、
印度的柱子上写的是 Bing——意思是这部分工作只要做一次：一个 Bing
站长工具账号、一份 sitemap、[IndexNow](https://www.indexnow.org/)，
六个市场同时覆盖。而 Bing 的索引还供给 Yahoo Search、DuckDuckGo 和
Ecosia，所以一份 Bing 索引等于四个引擎。

下面是完整的表，加上决定一个市场值不值得你投入的形态与工具两列：

| 市场 | 最大对手 | 2025 份额 | 形态 | 有自己的站长工具？ |
| --- | --- | ---: | --- | --- |
| 俄罗斯 | Yandex | 73.2% | 自建索引 | 有 —— [Yandex.Webmaster](https://webmaster.yandex.com/) |
| 韩国 | Naver | 45.6% | 自建索引 | 有 —— [Naver Search Advisor](https://searchadvisor.naver.com/) |
| 台湾 | Yahoo! 台湾 | 13.3% | 授权套壳（Google 索引） | 无 —— 与 Google 同一索引 |
| 捷克 | Seznam | 11.6% | 自建索引 | 有 —— [Seznam 站长工具](https://reporter.seznam.cz/wm/) |
| 日本 | Yahoo! JAPAN | 9.4% | 授权套壳（Google 索引） | 无 —— 与 Google 同一索引 |
| 德国 | Bing | 6.4% | 自建索引（美国） | 有 —— [Bing 站长工具](https://www.bing.com/webmasters) |
| 巴西 | Bing | 5.9% | 自建索引（美国） | 有 —— Bing 站长工具 |
| 菲律宾 | Bing | 5.7% | 自建索引（美国） | 有 —— Bing 站长工具 |
| 法国 | Bing | 5.4% | 自建索引（美国） | 有 —— Bing 站长工具 |
| 荷兰 | Bing | 4.9% | 自建索引（美国） | 有 —— Bing 站长工具 |
| 越南 | Cốc Cốc | 4.4% | 自建索引 | 有 —— Cốc Cốc 广告 / 爬虫工具 |
| 印度尼西亚 | Bing | 2.5% | 自建索引（美国） | 有 —— Bing 站长工具 |
| 泰国 | Bing | 1.4% | 自建索引（美国） | 有 —— Bing 站长工具 |
| 印度 | Bing | 1.3% | 自建索引（美国） | 有 —— Bing 站长工具 |

份额取自 [StatCounter](https://gs.statcounter.com/search-engine-market-share/all/south-korea)
2025 全年平均，四舍五入到一位小数。韩国的 Naver 在「查询量」口径下
要高得多——下一节讲这个。

有一簇引擎值得单独提一句。德国、法国、荷兰、奥地利有一批小而声量
不小的隐私引擎：[Ecosia](https://www.ecosia.org/)（柏林，跑在 Bing
索引上，把广告收入捐给种树）、[Startpage](https://www.startpage.com/)（荷兰，
在欧盟服务器上代理 Google 结果）、[Qwant](https://www.qwant.com/)（法国，
欧盟部署，离开 Bing 之后有了自己的索引）、[MetaGer](https://metager.org/)（德国，
元搜索）。它们加起来在各自市场占 1%–2%——真实存在，上得了表格，但
小到不值得单独立一套策略。它们的意义在于标示那几个国家的隐私舆情，
另外其中两个跑在 Bing 索引上，等于跟着你本来就要做的 Bing 工作一起
生效。

## 数字为什么互相矛盾 —— 要看口径，不只看数字

查韩国的市场份额，你会找到至少三个不同的答案。它们都是真的，只是
量的不是同一件事。

**StatCounter** 数的是**引荐流量**——从搜索结果点出去、落到网站上的
那部分点击。**InternetTrend** 数的是**查询量**，包括那些在引擎自己的
页面上就被回答完、根本没产生外跳的查询。

韩国是差距最大的地方，因为 Naver 把很大一部分韩国问题直接答在 Naver
里面：知识 iN 的答案、博客结果、Cafe 帖子、Place 门店信息。一个韩国
用户可以完全不点进你的网站就得到完整答案——StatCounter 自然看不到这次
访问。

2025 年，两个来源是这样说的：

| 引擎 | InternetTrend（查询量） | StatCounter（引荐流量） |
| --- | ---: | ---: |
| Naver | 62.9% | 45.6% |
| Google | 29.6% | 45.8% |
| Bing | 3.1% | 5.0% |
| Daum | 2.9% | 1.2% |

同一个市场、同一年，差 17 个百分点。哪个「对」取决于你想量什么。
如果你问的是**我能赢下多少搜索**，用查询量；如果你问的是**我能拿到
多少访客**，用引荐量——或者更好，用你自己的分析工具。

同一个坑在每个市场都有。看到一个博客给出份额，先找方法，再决定要不要
照做。不带来源、不带日期、不带口径的数字通常是错的；同时和两个独立
统计源打架的数字通常也是错的。

## 进入本地市场后，真正变的是什么

通过「值不值得」这道关只是开始。本地引擎占优的市场，通常在四个
具体方面和你熟悉的不一样。

**语言不是翻译。** 韩国或捷克的搜索者敲的是本地人问本地问题的样子，
不是翻译过来的关键词。韩国查询经常是完整的自然语句；捷克查询带变音
符号，而粗心的 URL 设计会把它弄丢。机器翻译读起来就是机器翻译，对
用户和对引擎都是。

**结果页不是一列链接。** Naver 用自己的垂类拼出一个 **Smart Block**——
博客、Cafe、Place、购物、知识答案。页面顶部不是你的网站。在 Naver 上，
出现在**垂类生态内部**和在自然结果里排名一样重要。

**提交是另一份工作。** Google Search Console 对 Naver、Seznam、Yandex
一点用都没有。每一个都有自己的验证流程、自己的 sitemap 接口，有时
还有自己的索引协议。Seznam 和 Yandex 都接受
[IndexNow](https://www.indexnow.org/)，这让「快点被收录」从一件苦等
的事变成一个可解的问题。

**链接的含义也不同。** 在本地引擎排自己索引的市场里，来自本地目录
或本地新闻的一条链接，权重远高于同一条国际链接在 Google 里的效果。
捷克语网站、来自捷克网站的链接，才是硬通货。

## 怎么判断一个本地引擎重不重要

按顺序问六个问题，就能把「第二个引擎会改变什么」的市场和「什么都
不改变」的市场分开：

1. **这个市场占你多少流量？** 低于大约 5% 的会话，无论本地引擎在
   主场份额多大，都动不了你的数字。
2. **本地引擎有自己的索引吗？** 如果它只是重新吐 Google 或 Bing 的
   结果，Google 和 Bing 的工作已经到达它——没有需要单独做的事。
3. **它有自己的站长工具吗？** Naver、Seznam、Yandex、百度、Bing
   各自都有一个；没有工具的引擎，无一例外都在骑别人家的索引。
4. **它有自己的垂类生态吗？** Naver、Daum、Kakao、Cốc Cốc、Seznam
   都有一些产品，在那里被看见意味着「出现在产品里」，而不只是在
   网页结果里排名。
5. **查询语言不同吗？** 韩语、日语、捷克语、越南语的查询是当地语言
   的句子；机翻页面回答它们，答得很糟。
6. **几个引擎共享一次提交吗？** Bing 的索引供给 Yahoo、DuckDuckGo
   和 Ecosia；IndexNow 一次触达 Bing、Yandex 和 Seznam。

## 接下来读什么

下面每个市场都有单独一页，写了该地的本地引擎、带来源的份额数字、
当地实际怎么搜、以及提交流程。如果只读一页，读
[韩国](https://x-cmd.com/seo/korea)——它是本地引擎真能和全球引擎
掰手腕最清楚的例子，也是两种统计口径分歧最大的地方。

背景知识在 [全球引擎](https://x-cmd.com/seo/google-seo) 和
[中文引擎](https://x-cmd.com/seo/baidu) 那几页：爬虫是什么、索引是什么、
[IndexNow](https://www.indexnow.org/) 在整个链条里怎么摆。

## 源码与官方资源

- **[StatCounter 搜索引擎市场份额](https://gs.statcounter.com/search-engine-market-share/all/south-korea)** —— 本章所有图都基于它的引荐流量口径。
- **[Naver 在韩国搜索市场登顶 60%（韩联社）](https://en.yna.co.kr/view/AEN20260104002400320)** —— InternetTrend 的查询量口径。
- **[Naver Search Advisor](https://searchadvisor.naver.com/)** —— Naver 的站长工具。
- **[Seznam 站长工具](https://reporter.seznam.cz/wm/)** —— Seznam 的站长工具。
- **[Yandex.Webmaster](https://webmaster.yandex.com/)** —— Yandex 的站长工具。
- **[IndexNow](https://www.indexnow.org/)** —— 各引擎共用的即时提交协议。
- **[日本公平交易委员会 — 移动软件竞争法](https://www.jftc.go.jp/en/pressreleases/yearly-2025/March/250331.html)** —— 日本的智能手机搜索新规。
- **[x-cmd/draw](https://github.com/x-cmd/draw)** —— 本页图表所用的端点。
