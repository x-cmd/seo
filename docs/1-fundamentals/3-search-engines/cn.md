---
x-title: 世界搜索引擎一览 —— 一张表看清
x-desc: >-
  本文库覆盖的每一个搜索引擎，汇于一处 —— 它的主场在哪、索引是不是自建的、
  在主场有多大、用户规模大约多少、对 SEO 何时重要、站点如何被收录。
  每一行链接到对应的深度文章。
x-sidebar: 搜索引擎一览
x-keywords: 搜索引擎列表, 所有搜索引擎, 各国搜索引擎, 自建索引, 市场份额, naver, yandex, seznam, coccoc, 百度, 搜索引擎对比
x-json-ld:
  '@context': https://schema.org
  '@graph':
    - '@type': TechArticle
      headline: '世界搜索引擎一览 —— 一张表看清'
      inLanguage: 'cn'
      about: '世界搜索引擎对比：索引归属、主场份额、用户估计、SEO 价值与收录方式'
---

# 世界搜索引擎一览 —— 一张表看清

这一页是整个文库的地图。有专门文章的每一个引擎在这里各占一行，配五件
解释「它是什么」的事实：主场在哪、索引是不是自建的、在主场有多大、
用户规模大约多少、一个站点要出现在它的结果里需要什么。每个引擎名链接
到它的完整文章。

先说两列怎么读，因为大多数误读都出在这里：

**「索引」是全表最有预测力的一列。** 自己爬网、自己排序的引擎——自建
索引——是一个真正独立的入口，需要单独提交、单独做排名工作。标着
*Bing* 或 *Google* 的引擎，是用自己的界面呈现别家公司的结果：到达
上游索引，就等于到达了它。*元搜索* 把查询转发给几家再合并答案。目前
国家级及以上规模的自建索引引擎只剩下大约七个，整张表的形状就是由
「它们是谁」决定的。

**「份额」和「用户」量的不是一回事。** 份额取自
[StatCounter](https://gs.statcounter.com/search-engine-market-share)
2025 年月度平均，是**外跳引荐**口径——它系统性低估那些在自己页面上
就把答案给完的引擎（Naver 最明显；查询量口径见
[韩国](https://x-cmd.com/seo/korea)）。用户数来自口径各异的公开来源
——App 月活、站点访问量、每日查询估计——只能当数量级参考，不能互比。
没有可靠公开数字的格子是「—」。

## 全球引擎

| 引擎 | 主场 | 索引 | 主场份额（2025） | 用户（估） | 何时重要 | 收录方式 |
| --- | --- | --- | --- | --- | --- | --- |
| [Google](https://x-cmd.com/seo/google-seo) | 美国 | 自建 | 全球约 89.9% | 每天数十亿次查询（第三方估计） | 几乎所有市场的第一入口 | [Search Console](https://search.google.com/search-console) + sitemap |
| [Bing](https://x-cmd.com/seo/bing-indexnow) | 美国 | 自建 | 全球约 4.0%；日本桌面 19.0%、德国桌面 15.8% | — | 办公桌面受众；一次提交喂饱一串卫星 | [Bing 站长工具](https://www.bing.com/webmasters) + [IndexNow](https://www.indexnow.org/) |
| [DuckDuckGo](https://x-cmd.com/seo/duckduckgo) | 美国 | 主要用 Bing | 全球约 0.8% | — | 隐私人群；没有可做的单独动作 | 随 Bing 覆盖 |
| [Yahoo! Search](https://x-cmd.com/seo/yahoo) | 美国 | 用 Bing | 全球约 1.4% | — | 门户时代的受众，偏年长，美国以外也有 | 随 Bing 覆盖 |
| [Ecosia](https://x-cmd.com/seo/western-europe) | 德国 | 用 Bing | 德国 1.1% | — | 隐私舆情的信号，不是目标 | 随 Bing 覆盖 |
| [Startpage](https://x-cmd.com/seo/western-europe) | 荷兰 | 代理 Google | 荷兰 <1% | — | 同上，只是代理的是 Google | 随 Google 覆盖 |
| [Qwant](https://x-cmd.com/seo/western-europe) | 法国 | 自建（小） | 法国 0.9% | — | 欧盟数据主权叙事 | 无大门户；靠爬虫自己发现 |
| [MetaGer](https://x-cmd.com/seo/western-europe) | 德国 | 元搜索 | 德国 <0.5% | — | 非营利的元搜索，这一簇里最老 | 无可提交——它实时查询别人 |

## 国家引擎

这些引擎在主场赢过、或认真挑战过全球引擎。「索引」列在这里开始真正
起作用。

| 引擎 | 主场 | 索引 | 主场份额（2025） | 用户（估） | 何时重要 | 收录方式 |
| --- | --- | --- | --- | --- | --- | --- |
| [Naver](https://x-cmd.com/seo/korea) | 韩国 | 自建 | 引荐 45.6%、查询量 62.9% | App 月活约 4685 万（2026-07，Mobile Index） | 韩语、本地、购物查询——韩国网络的主门 | [Naver Search Advisor](https://searchadvisor.naver.com/) + 自家垂类里出现 |
| [Daum](https://x-cmd.com/seo/korea)（Kakao 系） | 韩国 | 自建（萎缩） | 1.2% | Daum App 月活约 631 万（2026-07） | 以 KakaoTalk 内 `#` 搜索的形式存活 | KakaoTalk 生态，不是网页提交 |
| [Yahoo! JAPAN](https://x-cmd.com/seo/japan) | 日本 | 用 Google | 9.4%（移动 12.2%） | — | 两代日本手机用户的习惯；移动端最强 | 随 Google 覆盖——没有独立索引 |
| [Yahoo! 台湾](https://x-cmd.com/seo/taiwan) | 台湾 | 用 Google | 13.3%（桌面 17.1%） | — | 台湾桌面端长期的第二 | 随 Google 覆盖 |
| [Yandex](https://x-cmd.com/seo/russia) | 俄罗斯 | 自建 | 73.2% | — | 俄语市场的第一引擎 | [Yandex.Webmaster](https://webmaster.yandex.com/) + IndexNow |
| [Seznam](https://x-cmd.com/seo/czech) | 捷克 | 自建（2005 年起） | 11.6%（桌面 14.1%） | 月访问约 2.14 亿（SimilarWeb，2025-04） | 捷克语搜索；欧盟仅存的国家索引 | [Seznam 站长工具](https://reporter.seznam.cz/wm/) + IndexNow |
| [Cốc Cốc](https://x-cmd.com/seo/vietnam) | 越南 | 自建 | 4.4%（2025 年末 5.3–6.0%） | — | 越南语查询和它自带的浏览器 | robots.txt 放行 `coccocbot`——靠爬虫发现 |
| [百度](https://x-cmd.com/seo/baidu) | 中国 | 自建 | 中文搜索主导 | — | 中文网络的第一入口 | [百度搜索资源平台](https://ziyuan.baidu.com/)（常需 ICP 备案） |
| [神马](https://x-cmd.com/seo/shenma) | 中国 | 自建 | 移动优先，内嵌 UC 浏览器 | — | 移动端中文用户；UC 的装机量 | 百度生态 + UC 浏览器存在感 |
| [搜狗](https://x-cmd.com/seo/sogou) | 中国 | 自建 | 微信内容的搜索层 | — | 搜微信围墙内的内容 | [搜狗站长平台](https://zhanzhang.sogou.com/) + 微信存在感 |

## 不是引擎，但查询照样被它们接走

份额表数的是经过搜索引擎的搜索。在好几个市场，越来越大的一块「查东西」
根本不经过搜索引擎，少了它们这张地图就不完整：

| 入口 | 在哪 | 接走什么 | 规模（估） | 详见 |
| --- | --- | --- | --- | --- |
| TikTok 搜索 | 全球年轻用户；[东南亚](https://x-cmd.com/seo/southeast-asia)最强 | 吃、玩、买、「值不值」——用视频回答 | — | [东南亚](https://x-cmd.com/seo/southeast-asia) |
| Shopee / Lazada / Tokopedia | 东南亚 | 带购买意图的商品查询 | — | [东南亚](https://x-cmd.com/seo/southeast-asia) |
| Mercado Livre / Shopee 巴西 | 巴西 | 同上，葡萄牙语版 | — | [巴西](https://x-cmd.com/seo/brazil) |
| KakaoTalk `#` 搜索 | 韩国 | 聊天里敲的查询，Daum 来答 | KakaoTalk 覆盖约 90%+ 韩国用户 | [韩国](https://x-cmd.com/seo/korea) |
| LINE | 日本、台湾 | 服务、官方账号、本地意图 | — | [日本](https://x-cmd.com/seo/japan)、[台湾](https://x-cmd.com/seo/taiwan) |
| WhatsApp Business | 巴西、印度 | 搜索流量最终转化的地方 | 巴西网民渗透 90%+ | [巴西](https://x-cmd.com/seo/brazil) |

## 这张表藏着三件事

**自建索引引擎只剩大约七个**：Google、Bing、Yandex、百度、Naver、
Seznam、Cốc Cốc（Qwant 的算小但真实）。其余每一行都是建在它们之上的
产品——这就是为什么「收录方式」一列不断重复：前门一共只有七扇。

**套壳家族比看上去大。** Bing 的索引悄悄供给 DuckDuckGo、Yahoo! Search、
Ecosia 等；Google 的供给 Yahoo! JAPAN、Yahoo! 台湾和 Startpage。一个
份额 1% 的「小」引擎，可能只是某个大索引露在外面的一角。

**IndexNow 一次敲开七扇门里的三扇。** Bing、Yandex、Seznam 都接受它，
一个端点加一个 Google Search Console，就覆盖了七个自建索引里的四个
——经由它们，也覆盖了表里大多数套壳行。

## 接下来读什么

想了解本地市场为什么不同，从[区域市场总览](https://x-cmd.com/seo/overview)
开始；或者直接点上面匹配你受众的那一行。表格背后的机制——爬取、收录、
排序——在 [SEO 基础](https://x-cmd.com/seo/seo-basics)里；用来在这些
引擎之间比较站点权重的指标，在 [DA / DR](https://x-cmd.com/seo/da)里。

## 源码与官方资源

- **[StatCounter —— 搜索引擎市场份额](https://gs.statcounter.com/search-engine-market-share)** —— 份额列的 2025 年引荐平均。
- **[IndexNow](https://www.indexnow.org/)** —— 共享的即时提交协议（Bing、Yandex、Seznam）。
- **[Google Search Console](https://search.google.com/search-console)**、**[Bing 站长工具](https://www.bing.com/webmasters)**、**[Naver Search Advisor](https://searchadvisor.naver.com/)**、**[Yandex.Webmaster](https://webmaster.yandex.com/)**、**[Seznam 站长工具](https://reporter.seznam.cz/wm/)**、**[百度搜索资源平台](https://ziyuan.baidu.com/)**、**[搜狗站长平台](https://zhanzhang.sogou.com/)** —— 七扇前门。
