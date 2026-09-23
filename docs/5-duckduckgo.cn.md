---
x-title: DuckDuckGo — 注重隐私的搜索引擎，Bing 提供索引，带 DuckAssist 与 AI Chat
x-desc: >-
  DuckDuckGo 是注重隐私的搜索引擎，2026 年占据全球约 0.7% 市场份额。主要由
  Bing 提供索引，对部分垂类（Apple Maps、Wikipedia）有自己的爬虫。如何优化
  DuckDuckGo。
x-sidebar: DuckDuckGo SEO
x-keywords: duckduckgo, duckduckgo seo, ddg, 隐私搜索, duckassist, ai chat
x-json-ld:
  '@context': https://schema.org
  '@graph':
    - '@type': TechArticle
      headline: 'DuckDuckGo SEO'
      inLanguage: 'cn'
      about: 'DuckDuckGo 搜索引擎优化'
---

# DuckDuckGo — 注重隐私的搜索引擎，Bing 提供索引，带 DuckAssist 与 AI Chat

**DuckDuckGo（DDG）** 是由 Gabriel Weinberg 于 2008 年创立的注重隐私
的搜索引擎。2026 年占据全球搜索市场约 **0.7%**——份额小，但在注重
隐私的用户、Linux / 开源用户、开发者中影响不成比例。

DuckDuckGo 主要由 **Bing 的索引**支撑（100+ 源，包括 Bing、Yahoo、
Apple 的 Maps、Wolfram Alpha、以及 Wikipedia 的即时答案）。它也运行
自己的爬虫（**DuckDuckBot**）覆盖部分垂类，并运营自己的 AI 功能
（**DuckAssist、AI Chat**）。

> **TL;DR。** DuckDuckGo SEO = Bing SEO。同样的内容能排名。差异：
> 没有 `referer` 头泄漏；AI 答案引用来源；隐私默认浏览器把 DDG
> 设为默认。无自家站长工具——用 Bing Webmaster Tools。

## 为什么 DuckDuckGo？

- **全球搜索市场约 0.7%**（StatCounter 2026 Q2）。
- **在注重隐私的市场更高**（德国、荷兰、美国隐私细分）。
- **许多浏览器的默认搜索：**
  - **Tor Browser** —— 默认。
  - **Brave Browser** —— 隐私窗口默认。
  - **Vivaldi** —— 可选默认。
  - **DuckDuckGo Privacy Essentials** 浏览器扩展。
- **跳出率低** —— 注重隐私的用户点击更慎重。
- **AI 功能** —— DuckAssist（AI Overview 对应物）、AI Chat。

## DuckDuckGo 如何工作

DuckDuckGo 聚合 **100+ 垂类**：

- **网页** —— 主要 Bing 索引。
- **图片** —— Bing + 一些直接源。
- **视频** —— Bing。
- **新闻** —— Bing News + 部分源。
- **地图** —— Apple Maps（DDG 自己的协议）。
- **即时答案** —— Wikipedia、Wolfram Alpha、WikiData。
- **AI** —— DuckAssist + AI Chat。

DuckDuckGo 运行自己的爬虫 **DuckDuckBot**，覆盖部分垂类（主要是
Wikipedia + 开源数据集）。通用网页搜索结果源自 Bing。

### 隐私角度

- **没有 `referer` 头。** 用户点击结果时，目标站看到的是
  DuckDuckGo 重定向，不带搜索词。
- **不存储搜索历史。** DDG 不记录查询。
- **没有个人数据。** 没有 cookie，不记录 IP。
- **没有过滤气泡。** 同一查询所有人得到相同结果（与 Google
  个性化相反）。
- **一次访问一页面原则。** 一次查询 = 一次页面加载；不无限滚动。

对 SEO 的影响：

- **DDG 的 CTR 难以测量。** `referer` 不传关键词；你看到 DDG
  流量是"搜索"但没有关键词。
- **没有个性化偏见。** 排名基于查询而非用户历史——更接近"中立"
  排名。
- **AI 引用重要。** DuckAssist 像 Google AI Overviews 一样引用来源。

## 如何为 DuckDuckGo 优化

### 95% 规则

DuckDuckGo 网页搜索用 Bing 索引。排名共享。

为 Bing 优化（见 `3-bing-indexnow.en.md`），你就在 DuckDuckGo 上
排名。同样的内容质量 + E-E-A-T 类信号，同样的反向链接，同样的技术
健康，同样的结构化数据。

### DuckDuckGo 专属 5%

差异之处：

- **Wikipedia 存在。** 如果你的话题有 Wikipedia 文章，DDG 更可能
  通过即时答案推荐它。
- **开源 / 注重隐私的站。** DDG 的受众注重隐私；注重隐私的内容
  （开源工具、透明度报告、清晰的数据政策）获得微弱互动提升。
- **DuckAssist 引用。** 像 Google AI Overviews 一样，DuckAssist 引用
  来源。长篇一手内容胜出。
- **Apple Maps** —— DuckDuckGo 地图的本地 SEO，你需要为 Apple
  Maps（Apple Business Connect）优化，而非 Google Business Profile。
- **DuckDuckBot 爬虫** —— 足迹小；主要爬 Wikipedia 与开源数据集。
  不要期待 DDG 独立于 Bing 爬你的通用站。

### AI 功能

DuckDuckGo 的 AI 功能：

- **DuckAssist** —— AI 生成的答案摘要出现在搜索结果顶部，引用
  来源。
- **AI Chat** —— 聊天界面让用户提问后续问题。由 OpenAI、Anthropic、
  Mistral 等驱动。
- **注重隐私** —— DDG 声明 AI 查询不用于模型训练。

引用机制类似 Google AI Overviews：引用高质量来源，长篇一手内容
胜出。

## 追踪 DuckDuckGo 流量

DuckDuckGo 在分析中难以识别：

- **没有 `referer` 关键词** —— 你看到 DDG 流量是"搜索"但没有关键词
  串。
- **没有 UA 片段** —— DDG 的 UA 就是浏览器的 UA（Chrome on macOS、
  Firefox 等）。
- **HTTPS 重定向** —— 点击通过 `duckduckgo.com/l/` 然后重定向到
  目标。

估计 DuckDuckGo 流量的方法：

1. **按来源 / 媒介分析。** 看 `Source = duckduckgo.com`（如果你的
   分析工具能捕获）。
2. **服务器日志。** 把传入 IP / UA 与已知 DDG 爬虫 IP 对比。
3. **直接问用户。** 调查"你怎么找到我们的？"

实际上 DDG 流量小但质量高。

## DuckDuckGo 与 Bing 的关系

- **2014** —— DuckDuckGo 公开切换到用 Bing 索引做网页结果。
- **2016** —— DuckDuckGo Maps 的 Apple Maps 协议。
- **2018** —— DuckDuckGo Privacy Essentials 浏览器扩展上线。
- **2022** —— DuckAssist 正式推出。

DDG 与 Bing 没有合作关系；它为 Bing 的数据付费。

## DuckDuckGo 的爬虫

DuckDuckGo 的爬虫是 **DuckDuckBot**。主要跑：

- Wikipedia 更新。
- 开源数据源（OpenStreetMap、Wikidata）。
- 一些链接验证。

用户代理：

```
Mozilla/5.0 (compatible; DuckDuckBot-Https/1.1; https://duckduckgo.com/duckduckbot.html)
```

在 `robots.txt` 允许：

```txt
User-agent: DuckDuckBot
Allow: /
```

DuckDuckGo 大部分网页结果来自 Bingbot 的爬取，不是 DuckDuckBot。

## 注重隐私的 SEO 实践

如果你的受众与 DuckDuckGo 用户重叠，你可能也想做一个注重隐私的站：

- **隐私政策** —— 清晰、全面。
- **Cookie 同意横幅** —— 符合 GDPR / CCPA。
- **不追踪** —— 没有未经同意的 Google Analytics，没有 Facebook
  Pixel，没有第三方追踪器。
- **HTTPS** —— 必需。
- **不抓取邮件** —— 可见的邮件可能被爬。
- **透明的数据实践** —— 你收集什么数据、为什么、保留多久。

这些不直接提升 DDG 排名，但提升注重隐私用户的互动，间接有帮助。

## DuckDuckGo 速查清单

- [ ] 为 Bing 优化（BWT + IndexNow + Bing 排名因素）。DDG 网页跟随。
- [ ] 允许 DuckDuckBot 在 `robots.txt`。
- [ ] 如果你有 Wikipedia 存在，重复确认。
- [ ] DuckDuckGo Maps（移动）：为 Apple Maps / Apple Business Connect
  优化。
- [ ] 注重隐私（HTTPS、清晰隐私政策、无侵入式追踪）。

## DuckDuckGo vs Bing vs Google — 概览

| 维度 | DuckDuckGo | Bing | Google |
| --- | --- | --- | --- |
| 索引 | Bing + 100+ 源 | Bing | Google |
| 爬虫 | DuckDuckBot（小） | Bingbot | Googlebot |
| 隐私 | 一流 | 标准 | 标准 |
| AI 功能 | DuckAssist + AI Chat | Copilot | AI Overviews |
| 地图 | Apple Maps | Bing Maps | Google Maps |
| 站长工具 | 无 | Bing Webmaster Tools | Google Search Console |
| IndexNow | ✅（经 Bing） | ✅ | ❌ |
| 市场份额（2026 Q2） | 约 0.7% | 约 3.5% | 约 91% |

## 下一步？

- **6-baidu** — 百度 SEO（中文）。
- **7-shenma** — 神马 SEO（移动端，中文）。

## 源码与官方资源

- **DuckDuckGo：** <https://duckduckgo.com/>
- **DuckDuckBot：** <https://duckduckgo.com/duckduckbot>
- **DuckDuckGo 帮助：** <https://duckduckgo.com/duckduckgo-help-pages>
- **DuckDuckGo 隐私政策：** <https://duckduckgo.com/privacy>
- **Bing Webmaster Tools（用于 DDG 网页）：** <https://www.bing.com/webmasters>