---
x-title: 越南搜索引擎 —— Cốc Cốc、Google 与一个真正的本地索引
x-desc: >-
  2026 年越南搜索怎么运转 —— Google 的主导、Cốc Cốc 这个罕见的国家级自建索引样本、
  越南语的声调符号，以及在越南市场做优化要做什么。
x-sidebar: 越南搜索引擎
x-keywords: 越南搜索引擎, coccoc, cốc cốc 浏览器, 越南语 seo, 声调符号, coccocbot, google 越南
x-json-ld:
  '@context': https://schema.org
  '@graph':
    - '@type': TechArticle
      headline: '越南搜索引擎 —— Cốc Cốc 与一个真正的本地索引'
      inLanguage: 'cn'
      about: '越南搜索引擎市场份额与 Cốc Cốc SEO'
---

# 越南搜索引擎 —— Cốc Cốc、Google 与一个真正的本地索引

越南乍看是又一个「只有 Google」的市场——大体上也是。但它拥有全世界
仅存的几个真正独立的国家级搜索索引之一：**Cốc Cốc**，一家越南公司，
用自己的爬虫（`coccocbot`）爬越南网络、用自己的信号排序、装在自己
基于 Chromium 的浏览器里。如果你想理解 2026 年「本地搜索引擎」还能是
什么样子，这是少数还活着的样本。

> **TL;DR。** 2025 年引荐口径：Google 94.2%、Cốc Cốc 4.4%、Bing 0.7%、
> Yahoo! 0.5%。策略就是 Google。有趣的部分是 Cốc Cốc——一个独立的越南
> 索引，有自己的爬虫、自己的浏览器，而且份额在**涨**（2025 年秋从 3.9% 升到 5.3%–6.0%）。
> 对内容来说，实际的坑是越南语的声调符号：正文里要保留，也别指望英文
> 页面能被搜到。

## 市场到底是什么样？

下面是越南 2025 年的份额，全设备，来自
[StatCounter](https://gs.statcounter.com/search-engine-market-share/all/viet-nam)
的月度平均：

[![2025 年越南搜索份额](https://x-cmd.com/draw?type=hbar&t=opendata&unit=%25&title=2025%20%E5%B9%B4%E8%B6%8A%E5%8D%97%E6%90%9C%E7%B4%A2%E5%B8%82%E5%9C%BA%E4%BB%BD%E9%A2%9D&labels=Google,CocCoc,Bing,Yahoo!,DuckDuckGo&values=94.2,4.4,0.7,0.5,0.1)](https://x-cmd.com/draw/explore?type=hbar&t=opendata&unit=%25&title=2025%20%E5%B9%B4%E8%B6%8A%E5%8D%97%E6%90%9C%E7%B4%A2%E5%B8%82%E5%9C%BA%E4%BB%BD%E9%A2%9D&labels=Google,CocCoc,Bing,Yahoo!,DuckDuckGo&values=94.2,4.4,0.7,0.5,0.1)

Google 在 94% 以上，剩下的一切基本就是 Cốc Cốc。Bing 在这里反常地
**小**——0.7%，而全球平均约 4%——这本身就说明问题：离开了 Windows
默认设置，Bing 并不会自己走到哪儿都吃香。

## Cốc Cốc —— 独立索引现在长什么样

Cốc Cốc 是这个市场里有意思的对象，哪怕你从不为它做优化，也值得弄懂它。

这家公司从做越南语浏览器起家——**Cốc Cốc 浏览器**，一个为越南网络调校的
Chromium 分支——然后为它造了一个搜索引擎。这个引擎既不是套壳也不是
元搜索，它维护着**自己的越南网页索引**，由自己的爬虫
（`coccocbot` / `coccocbot-web`）抓取，排序信号专为越南语调校。

这个组合——国家级索引加上装载它的浏览器——已经近乎绝迹。目前还在
自爬自排、达到国家级规模的引擎名单很短：Google、Bing、Yandex、百度、
Naver、Seznam，再加一个 Cốc Cốc。其余的要么租索引，要么合并别人的结果。

Cốc Cốc 的份额也在动：2025 年 8 月还是 3.9%，10–12 月到了 5.3%–6.0%，
2026 年则在约 3.6%–6% 之间震荡——趋势向上，但月度波动不小。它强在那些「是越南人」真正加分的查询上——本地服务、
越南语电商，以及**不带声调符号的查询**——它对越南语拼写的容错比 Google
更宽容。

这个引擎公开的方向是基于自有越南语语料做 AI 优先的搜索，它的公开材料
强调：拥有国家级索引，正是它的 AI 答案立足于越南语来源的原因。这套
论证——独立索引是国家 AI 搜索产品的护城河——和 Seznam 在捷克、Naver
在韩国讲的是同一个故事。

## 越南语的声调符号 —— 实际的坑

越南语用拉丁字母加一层很重的符号书写：**tiếng Việt** 同时带声调标记和
元音标记，而带符号和不带符号往往是两个不同的词。

对搜索有两个后果：

**查询不带符号时，引擎得猜。** 越南用户经常敲 `nha hang` 而不是
`nhà hàng`，一部分原因是声调符号的键盘输入太慢。Google 处理得不错但
不完美；Cốc Cốc 则把「对不带符号越南语的容错」当作卖点。无论哪种情况：
一个只在关键词里写全符号的页面，可能匹配不上半数受众实际的敲法。

**URL 和内容里不要乱丢符号。** 内容应当带完整、正确的越南语符号。URL
的稳妥惯例是转写成 ASCII（`nha-hang-ha-noi`），并确保 CMS 一致地执行。
要避免的错误是编码不一致——同一个词一处带符号一处不带，URL 在版本间
变来变去。

对想覆盖越南的英文站：默认它不会被自然搜到。越南用户用越南语搜索，
页面里没有越南语，查询就没有可以匹配的东西。如果这个市场要紧，内容
就得是**写出来的**越南语，而不是逐词翻译。

## 这些事实意味着什么

1. **用越南语做 Google。** 常规动作——Search Console、sitemap、结构化
   数据、移动优先性能——配越南语关键词和越南语内容。越南流量大头在
   手机上，移动性能优先。
2. **内容保留完整声调符号。** 正确拼写（đúng chính tả）写进标题、描述、
   正文和 alt 文本。
3. **URL 一律转写成 ASCII**，由 CMS 一致处理。
4. **robots.txt 放行 `coccocbot`**，让它爬。没有类似 Search Console 的
   独立提交入口，进去的方式就是可被抓取。如果越南流量对你重要，Cốc Cốc
   那 4%–6% 是真实流量，成本只是 robots 文件里的一行。
5. **不要为越南专门投 Bing。** 那里的 0.7%，你为别的市场做的 Bing 工作
   顺手就覆盖了。
6. **本地链接与本地目录。** 越南的目录站和本地媒体是本地查询的 citation
   层。

## 接下来读什么

越南和[捷克](https://x-cmd.com/seo/czech)是一对——Seznam 是本章里另一个
活下来的国家级独立索引，对比着看就知道这种形态的引擎面对 Google 守得住
什么、守不住什么。本页每个数字背后的口径问题在
[区域市场总览](https://x-cmd.com/seo/overview)里，爬虫与索引的机制在
[SEO 基础](https://x-cmd.com/seo/seo-basics)里。

## 源码与官方资源

- **[StatCounter —— 越南搜索引擎市场份额](https://gs.statcounter.com/search-engine-market-share/all/viet-nam)** —— 引荐流量口径的数字。
- **[Cốc Cốc](https://coccoc.com)** —— 搜索引擎与浏览器。
- **[Cốc Cốc 广告](https://ads.coccoc.com)** —— 它的广告平台与商家工具。
- **[coccocbot —— 爬虫文档](https://bot.coccoc.com)** —— 爬虫的 UA 与 robots 处理。
- **[Google Search Console](https://search.google.com/search-console)** —— 最重要引擎的工具。
- **[Google 越南](https://www.google.com.vn)** —— 本地 Google 前端。
