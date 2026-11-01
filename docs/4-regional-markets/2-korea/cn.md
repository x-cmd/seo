---
x-title: 韩国搜索引擎 —— Naver、Google、Daum 与 KakaoTalk
x-desc: >-
  2026 年韩国搜索到底怎么运转 —— Naver 的垂直搜索与 C-Rank、为什么 Naver 的份额
  在不同口径下是 46% 还是 63%、Daum 发生了什么，以及在韩国市场做优化要做什么。
x-sidebar: 韩国搜索引擎
x-keywords: 韩国搜索引擎, naver seo, daum, kakaotalk 搜索, naver search advisor, 지식iN, c-rank, 韩国市场
x-json-ld:
  '@context': https://schema.org
  '@graph':
    - '@type': TechArticle
      headline: '韩国搜索引擎 —— Naver、Google、Daum 与 KakaoTalk'
      inLanguage: 'cn'
      about: '韩国搜索引擎市场份额与 Naver SEO'
---

# 韩国搜索引擎 —— Naver、Google、Daum 与 KakaoTalk

韩国是唯一一个本地搜索引擎真正压过 Google 的市场，而原因并不是
韩国人不喜欢 Google。真正的原因是：Naver 回答问题的方式，和韩国人
提问的方式一致——整句整句的、关于本地的事、答案来自 Naver 自己的博客、
Cafe、地图和问答。如果你的站只为 Google 做优化，韩国大约三分之一的
搜索需求就直接够不着了。

> **TL;DR。** 2025 年查询量口径：Naver 62.9% / Google 29.6%。2025 年
> 外跳引荐口径：Google 45.8% / Naver 45.6%——几乎打平。两个数字都是真的，
> 它们量的不是同一件事。Naver 是**移动端**引擎（移动端占 60.8%），
> Google 是**桌面端**引擎（桌面端占 58.6%）。Naver 用自己的信号
> （C-Rank、D.I.A.）给自己的垂类排序，所以需要单独一套策略。Daum 已经
> 掉到 1%–3%，活在 KakaoTalk 里。Naver 自己的工具是
> [Naver Search Advisor](https://searchadvisor.naver.com/)。

## 市场到底是什么样？

下面是韩国 2025 年各引擎的份额，全设备，来自
[StatCounter](https://gs.statcounter.com/search-engine-market-share/all/south-korea)
的月度平均：

[![2025 年韩国搜索份额](https://x-cmd.com/draw?type=hbar&t=opendata&unit=%25&title=2025%20%E5%B9%B4%E9%9F%A9%E5%9B%BD%E6%90%9C%E7%B4%A2%E5%B8%82%E5%9C%BA%E4%BB%BD%E9%A2%9D&labels=Google,Naver,Bing,Daum,CocCoc,Yandex,Yahoo!&values=45.8,45.6,5.0,1.2,0.9,0.8,0.4)](https://x-cmd.com/draw/explore?type=hbar&t=opendata&unit=%25&title=2025%20%E5%B9%B4%E9%9F%A9%E5%9B%BD%E6%90%9C%E7%B4%A2%E5%B8%82%E5%9C%BA%E4%BB%BD%E9%A2%9D&labels=Google,Naver,Bing,Daum,CocCoc,Yandex,Yahoo!&values=45.8,45.6,5.0,1.2,0.9,0.8,0.4)

两个引擎拿走了几乎全部，第三名 Bing 的 5% 是因为它预装在 Windows 上，
而不是因为谁主动选了它。下面那些——Cốc Cốc、Yandex、Yahoo!——各自不到
1%，只有在别的原因让你必须关心时才值得管。

### 为什么你会查到两个不一样的答案

搜「韩国搜索引擎市场份额」，你会看到 52.4% / 38.2% 这样一对数字在
各种博客和聚合站上流传。这一对数字跟两家主要统计源都对不上——任何设备
口径下、任何方向上都对不上。把它当作未经证实的数字，直接略过。

你还会看到下面这个，而这才是真实情况：

[![韩国 —— 两种数法](https://x-cmd.com/draw?type=bar&unit=%25&title=%E9%9F%A9%E5%9B%BD%20%20%E4%B8%A4%E7%A7%8D%E7%AE%97%E6%B3%95&labels=Google,Naver,Bing,Daum&series=InternetTrend%20%28%E6%9F%A5%E8%AF%A2%E9%87%8F%29:29.6,62.9,3.1,2.9&series=StatCounter%20%28%E5%BC%95%E8%AF%81%E6%B5%81%E9%87%8F%29:45.8,45.6,5.0,1.2)](https://x-cmd.com/draw/explore?type=bar&unit=%25&title=%E9%9F%A9%E5%9B%BD%20%20%E4%B8%A4%E7%A7%8D%E7%AE%97%E6%B3%95&labels=Google,Naver,Bing,Daum&series=InternetTrend%20%28%E6%9F%A5%E8%AF%A2%E9%87%8F%29:29.6,62.9,3.1,2.9&series=StatCounter%20%28%E5%BC%95%E8%AF%81%E6%B5%81%E9%87%8F%29:45.8,45.6,5.0,1.2)

**InternetTrend** 数的是**查询量**——韩国人敲下去的每一次搜索。
**StatCounter** 数的是**引荐**——真正从引擎点出去、落到网站上的点击。

Naver 在前者是 62.9%，在后者是 45.6%。这 17 个百分点就是全部故事：
**韩国很大一部分搜索是在 Naver 内部被回答完的，用户一次都没点出来。**
Naver 自己的知识 iN 答案、博客结果、Cafe 帖子、Place 门店——韩国用户
可以在 Naver 上把事办完，全程没看到你的网站，于是没有任何引荐被记录。

那该用哪个数字？问「**我能赢下多少搜索**」就用查询量，那是机会的大小；
问「**我能拿到多少访客**」就用引荐量，或者更好——用你自己的分析工具。

这个差距同时也告诉你该往哪使劲。Naver 那些在站内就答完的问题，恰恰是
永远不产生点击的问题——这意味着 Naver 策略不是「在同一页排得更靠前」，
而是「进到能回答这类问题的那一个垂类里去」。

## Naver 是移动引擎，Google 是桌面引擎

这是原始数字告诉你的第二件事，很容易被忽略：

[![韩国 —— 移动端 vs 桌面端](https://x-cmd.com/draw?type=bar&unit=%25&title=%E9%9F%A9%E5%9B%BD%20%20%E7%A7%BB%E5%8A%A8%E7%AB%AF%20vs%20%E6%A1%8C%E9%9D%A2%E7%AB%AF&labels=Google,Naver,Bing,Daum&series=Mobile:35.9,60.8,0.4,0.0&series=Desktop:58.6,26.1,10.8,2.8)](https://x-cmd.com/draw/explore?type=bar&unit=%25&title=%E9%9F%A9%E5%9B%BD%20%20%E7%A7%BB%E5%8A%A8%E7%AB%AF%20vs%20%E6%A1%8C%E9%9D%A2%E7%AB%AF&labels=Google,Naver,Bing,Daum&series=Mobile:35.9,60.8,0.4,0.0&series=Desktop:58.6,26.1,10.8,2.8)

在手机上，Naver 拿走接近三分之二的搜索，Google 掉到三分之一左右；在
桌面上，Google 拿下接近六成，Naver 掉到四分之一左右。Daum 在移动端几乎
归零——它是一个靠老电脑用户习惯活下来的桌面门户。

实际解读是：**移动端需要 Naver，桌面端 Google 仍是更大的那块蛋糕。**
一个只优化 Google 的韩国上线方案，优化的是这个市场里较小的一半。

## Naver 到底怎么排序

Naver 不是一列蓝链。它是一个**集成搜索**门户，用自己的垂类拼出结果页，
每个垂类有自己的用户群和自己的信号。

| 垂类 | 是什么 | 为什么重要 |
| --- | --- | --- |
| **VIEW** | Naver **博客** + Naver **Cafe** 混合结果 | 内容营销的主要战场 |
| **知识 iN（지식iN）** | 问答平台，2002 年就上线 | 长尾问题里经常排在页面最上面 |
| **Naver 博客** | 用户博客——测评、长文、图文 | 承载 **C-Rank** 信号 |
| **Naver Cafe** | 社区论坛——公寓、爱好、育儿 | 常常压过品牌自己的商品页 |
| **Naver Place（플레이스）** | 本地商家信息，类似 Google 商家 | 有本地业务基本是必做项 |
| **Naver Shopping** | 商品结果与 Smart Store | 成交发生的地方 |
| **Naver News / TV / VIBE** | 聚合媒体与视频 | 漏斗上层 |

如果打算认真做，两个排序系统必须搞懂。**C-Rank** 给博客的权威度和话题
专注度打分；**D.I.A.** 给单篇内容打分——相关性、停留时间、评论、分享。
Naver 自己的团队把这个结果叫做 폐쇄형 생태계（封闭生态）：这里很大一部分
内容 Google 根本爬不到，所以在里面缺席不是排名惩罚，而是永久性损失。

对一条购物类查询，结果顺序大致是：达人测评 → 长文博客（Power Contents）
→ Naver Place → Cafe 帖子 → 知识 iN → 商品列表。一个品牌能同时出现在
其中三个板块里，做得会比只在一个板块里排第一的品牌好。

两个坑。**知识 iN 会严惩作弊**——自问自答、小号矩阵、批量操作都会被
标记，一旦被标记可能烧掉整片账号矩阵。它要的是可信度，不是流量farm。
**Cafe 里的付费发帖**违反韩国竞争法与 Cafe 服务条款；合规做法是从
现有客户那里引导真实的用户评价。

## Daum 与 KakaoTalk —— 第二个生态

Daum 是韩国的第一个门户，曾经是韩国最大的搜索引擎。现在是另一回事了。

Kakao 在 2014 年收购 Daum 并把它并进 KakaoTalk。Daum 的份额从并购前后
的 20%–30% 掉到今天的 1%–3%——2024 年 7 月被 Bing 反超。2025 年 12 月
Kakao 把 Daum 分拆为 AXZ；Upstage 于 2026 年 5 月 7 日完成收购，7 月
改名 Daum Corporation，并把它与 SOLAR 大模型结合。

活下来的不是搜索框，而是**在 KakaoTalk 里的位置**。在聊天窗口敲 `#`
会返回 Daum 结果，而 KakaoTalk 在韩国的渗透率约 90%–98%。Kakao 还在
聊天里测试一种 AI 生成答案的模式，取代基于 Daum 的 `#` 搜索，让用户
完全不离开 App。

所以 KakaoTalk 是一个分发渠道，不是需要优化的搜索引擎。如果你的用户
在韩国，一个 KakaoTalk 频道往往比再做一轮页面内 SEO 更划算。

## Google 在韩国还强在哪里

别转过头就过度倾斜。即便在美国以外最亲 Google 的市场，Google 在一些
具体且可预测的地方依然很强——开发者与技术类查询约 95%、英文与全球
内容约 88%、YouTube 式视频约 98%、学术搜索约 78%、B2B SaaS 评测类
约 70%。它在韩国本地购物上最弱，约 18%。

大致分法是：**英文、技术、学术、视频搜索仍属 Google；韩语、本地、
消费和购物搜索属 Naver。**

## AI 这一轮把两个数字都搅动了

2025 和 2026 年发生了两件事，让任何超过一年的份额数字都过时了。

**Naver 的 AI Briefing**（AI 摘要模块）在 2025 年陆续铺到健康、公共
部门和金融等垂类，取材于教学医院、学术团体等可信的韩国机构。到 2026 年
4 月，它出现在约 20% 的 Naver 查询上，月活超过 3000 万。这是对
「在页面里就把答案给完」这个行为的正面攻击——正是那个行为让 Naver 的
引荐率看起来偏低。

**Google 的韩国手机 App 在 2026 年 7 月首次超过 Naver**——月活 4702 万
对 Naver 的 4685 万。与此同时，ChatGPT 在韩国月活达到 1646 万，明显
甩开 Daum 的 631 万。2025 年一项政府调查发现，60% 的生成式 AI 用户
把至少一半的传统搜索活动转移到了 AI 平台。

趋势很清楚：搜索市场正在从「搜索结果页」往「AI 答案」迁移——而在那
个战场上赢的，未必是传统结果页上赢的那个。

## 到底该做什么

**如果你要在韩国上线**，按这个顺序走最有效。

1. **永远先做 Google。** 它仍占外跳搜索流量的近一半，桌面端更是近一半。
   把常规动作做完：Search Console、sitemap、结构化数据、Core Web Vitals。
2. **加上 Bing。** 5% 不是舍入误差，而 Bing 站长工具加
   [IndexNow](https://www.indexnow.org/) 的边际成本几乎为零。
3. **在 Naver Search Advisor 完成验证。** 它是韩国最接近 Google Search
   Console 的东西：站点验证、抓取与收录报告、URL 检查、重新索引请求。
   它只管外部网页这一层。
4. **然后进到 Naver 内部去做。** 博客拿 C-Rank 和内容触达，Place 做
   本地，Shopping 做电商，知识 iN 在你确实有专家能答的时候做。
5. **用韩国人问问题的方式写。** 韩国查询是句子。「서울 맛집」（首尔美食）
   是一个地点加一个类目，不是一串关键词。
6. **拿韩国站的外链。** 在 Naver 的排序里，一条韩国博客或韩国新闻的
   链接，价值远高于同等的国际链接。
7. **盯住 AI 界面。** Naver 的 AI Briefing 和 Google 的 AI Overviews
   都取材于观点清晰、一手、可引用的内容。被摘要引用一次，比多拿一条
   蓝链更值钱。

**如果你并不在韩国做市场**，这一页仍然值得读一遍，因为这个模式会重复
出现：本地引擎赢，靠的不是排序压过 Google，而是用另一种方式把问题
回答得更好。

## 接下来读什么

[韩国](https://x-cmd.com/seo/korea)是本章最深的一个案例。最接近的对照
是[日本](https://x-cmd.com/seo/japan)——一个跑在 Google 索引上的套壳
引擎拿到了相近的份额，却不需要单独一套策略；以及
[区域市场总览](https://x-cmd.com/seo/overview)，那里解释了本页每一个
数字背后的口径差异。爬虫和索引的机制在
[SEO 基础](https://x-cmd.com/seo/seo-basics)里。

## 源码与官方资源

- **[StatCounter —— 韩国搜索引擎市场份额](https://gs.statcounter.com/search-engine-market-share/all/south-korea)** —— 引荐流量口径的数字。
- **[Naver 在韩国搜索市场登顶 60%（韩联社）](https://en.yna.co.kr/view/AEN20260104002400320)** —— InternetTrend 查询量口径的数字。
- **[Naver Search Advisor](https://searchadvisor.naver.com/)** —— Naver 的站长工具：网页搜索顾问、站点检查、SEO 基础。
- **[Naver Blog — Corporate](https://navercorp.com/en/storyDetail?seq=32546)** —— Naver 自己对平台策略的描述。
- **[韩国先驱报 —— Kakao 分拆 Daum](https://m.koreaherald.com/article/10627173)** —— Daum 分拆始末。
- **[Kakao](https://www.kakao.com)** —— KakaoTalk 的频道与搜索入口。
- **[Bing Webmaster Tools](https://www.bing.com/webmasters)** —— 市场里的 Bing 一侧。
- **[IndexNow](https://www.indexnow.org/)** —— 向 Bing 等参与方即时提交。
