---
x-title: 谷歌 SEO — 排名因素、Search Console 与工作流
x-desc: >-
  2026 年在 Google 上排名的实用指南 —— E-E-A-T、Core Web Vitals、结构化数据、
  有用内容、AI Overviews，以及 Google Search Console 日常工作流。
x-sidebar: 谷歌 SEO
x-keywords: 谷歌 seo, search console, eeat, core web vitals, 有用内容, ai overviews, sitemap
x-json-ld:
  '@context': https://schema.org
  '@graph':
    - '@type': TechArticle
      headline: '谷歌 SEO'
      inLanguage: 'cn'
      about: '谷歌搜索引擎优化'
---

# 谷歌 SEO — 排名因素、Search Console 与工作流

Google 在 2026 年占据全球搜索市场约 **91%**。如果你只为单个引擎
优化，那就优化 Google。本文覆盖谷歌专属 SEO：排名因素格局、
Search Console 日常工作流，以及 2026 年的具体情况（有用内容、
AI Overviews、结构化数据）。

> **TL;DR。** 谷歌 SEO = E-E-A-T + Core Web Vitals + 有用内容
> + 结构化数据。免费工具：Google Search Console。提交 sitemap，
> 监控覆盖 + 表现，修复问题。AI Overviews 下移点击；长篇一手内容
> 胜出。

## 为什么 Google？

- **全球搜索市场约 91%**（StatCounter 2026 Q2）。
- **移动搜索市场约 88%**。
- **美国桌面搜索市场约 85%**。

替代品（Bing、DuckDuckGo、百度）也有关系——见后续文章——但 Google
是默认。在 Google 上排名好的站通常在 Bing 上也排名好（排名因素
类似）。

## Google Search Console — 免费工具

**Google Search Console（GSC）**是每个做谷歌 SEO 的人都需要的免费
工具。验证你的域名，然后每天用它。

### 设置

1. 访问 <https://search.google.com/search-console>。
2. 添加资源——**URL 前缀**（通过 HTML 文件、DNS 记录或 Google
   Analytics 验证）或**域名**（通过 DNS TXT 记录验证）。
3. 验证后，GSC 在 24-72 小时内开始收集数据。

### 每日 / 每周工作流

1. **效果** → 查看热门查询与页面。找高曝光但低 CTR 的页面——
   它们需要更好的标题与描述。
2. **覆盖** → 查看**已排除**标签。错误是没收录的页面；警告是有
   问题的页面。
3. **URL 检查** → 粘贴 URL 看 Google 如何渲染，是否收录，有哪些
   问题。
4. **Sitemap** → 提交新 sitemap；检查现有 sitemap 状态。
5. **增强功能** → 如果有结构化数据，看按类型的报告（文章、FAQ、
   商品等）。
6. **链接** → 看哪些外部站点链接到你。
7. **人工操作** → 红色横幅表示 Google 处罚过你的站。仔细读每条
   并修复。

### 读取"效果"报告

"效果"报告展示：

- **总点击** —— 你的页面在 Google 搜索中被点击的总次数。
- **总曝光** —— 你的页面在 Google 搜索中出现的总次数。
- **平均 CTR** —— 点击 / 曝光。基准：
  - 第 1 位：约 30% CTR
  - 第 2-3 位：约 15%
  - 第 4-10 位：约 5%
  - 第 11 位以下：< 2%
- **平均排名** —— 你的平均排名。

按这些过滤：

- **查询** —— 用户搜索了什么。
- **页面** —— 你的哪些页面有排名。
- **国家** —— 地理。
- **设备** —— 桌面 / 移动 / 平板。
- **日期** —— 最近 7 / 28 / 90 天 / 16 个月。

## 2026 年谷歌排名因素

谷歌算法有数百个信号。主要类别：

### 内容质量 — E-E-A-T

**E-E-A-T**（经验、专业性、权威性、可信度）是 Google 评估内容
质量的框架。

| 信号 | 含义 |
| --- | --- |
| **经验** | 对话题的一手经验。你做过吗？ |
| **专业性** | 领域知识。你合格吗？ |
| **权威性** | 行业 / 网络认可。其他来源引用你吗？ |
| **可信度** | 准确性、透明性、安全性。用户能信任你吗？ |

对 YMYL（Your Money or Your Life）话题——健康、金融、法律、安全
——E-E-A-T 执行得更严。一篇由未验证作者写的医学文章可能排名差，
即便事实正确。

### 有用内容（Helpful Content）

Google 的**Helpful Content Update（HCU）**于 2022 年上线，此后
迭代多次。它针对"为搜索引擎写而非为人写"的内容——这些内容：

- 聚合其他来源但不增值。
- 针对很多关键词但每个都不深入。
- 没有清晰的观点。
- 没有展示一手经验。

修复：为人先写内容。把 SEO 当指引而非目标。

### Core Web Vitals

Google 的用户体验信号：

- **LCP（Largest Contentful Paint，最大内容绘制）**——"良好" <
  2.5s。
- **INP（Interaction to Next Paint，交互到下一次绘制）**—— <
  200ms。
- **CLS（Cumulative Layout Shift，累计布局偏移）**—— < 0.1。

测量方式：

- **Lighthouse**（Chrome DevTools → Lighthouse 标签）。
- **PageSpeed Insights**（<https://pagespeed.web.dev/>）。
- **Chrome User Experience Report（CrUX）**——真实用户数据，
  集成在 GSC 的"体验"下。

### 结构化数据（Schema.org / JSON-LD）

Google 用结构化数据启用富结果。没有结构化数据，你的页面就是
蓝链。有了：

| 类型 | 富结果 |
| --- | --- |
| `Article` | 头条轮播、文章卡片。 |
| `FAQPage` | 可展开的 FAQ 手风琴。 |
| `HowTo` | 分步卡片。 |
| `Product` | 价格、库存、评分。 |
| `Recipe` | 图像、评分、烹饪时间。 |
| `BreadcrumbList` | SERP 中的面包屑。 |
| `Organization` | 知识面板。 |
| `LocalBusiness` | 地图 + 营业时间 + 评论。 |

用 <https://search.google.com/test/rich-results> 验证。

### 移动优先

自 2018 年起，Google 索引页面的**移动版本**。如果移动版坏
了，桌面无关紧要。

检查移动友好性：

- **GSC → 体验 → 移动可用性**——Google 在这里通知移动问题。
- **Lighthouse** 带移动模拟。
- **Chrome DevTools** 移动模拟器。

### HTTPS

自 2014 年起必需。通过 Let's Encrypt 免费获取证书。混合内容
（HTTPS 页面加载 HTTP 子资源）会伤排名。

### 页面速度

Core Web Vitals 是一部分。其他速度信号：

- **TTFB（Time to First Byte）**——"良好" < 800ms。
- **FCP（First Contentful Paint）**—— < 1.8s。
- **TBT（Total Blocking Time）**—— < 200ms。

### 页内 SEO

- **标题标签**——`<title>`——50-60 字符，含主关键词。
- **Meta 描述**——150-160 字符，带行动召唤。
- **H1**——每页一个，含主关键词。
- **URL**——简短、描述性、kebab-case。
- **内链**——每个页面至少被站内一个其他页面链。
- **图像 alt 文本**——描述性，自然含关键词。

### 反向链接

#1 页外因素。质量比数量重要。一个顶级来源（NYT、Wikipedia、
业内前三站）的单链胜过 10,000 个低质量链。

## AI Overviews（前身为 SGE）

2025 年 5 月，Google 把 **Search Generative Experience（SGE）**
重命名为 **AI Overviews**。AI 生成的摘要现在出现在许多搜索结果
顶部，带引用。

对 SEO 的影响：

- **点击下移。** 用户从 AI Overviews 得到答案，可能不点进你的页面。
- **引用仍可见。** 在 AI Overview 中被引用能带来品牌曝光与点击
  （CTR 低但质量高）。
- **长篇一手内容胜出。** AI Overviews 引用有原创研究、专家评论或
  独特数据的内容。

修复：写 AI Overviews 想引用的内容——有第一手经验、原创数据、
清晰专业性的内容。

## 本地 SEO

本地业务：

- **Google Business Profile**——在 <https://business.google.com/>
  认领。
- **NAP 一致性**——所有网络列表上 Name、Address、Phone 一致。
- **评论**——数量 + 时效 + 回复。
- **本地反向链接**——本地媒体、本地目录、赞助。

## Google 处罚

Google 可以手动或算法处罚你的站。

| 类型 | 如何检测 | 如何修复 |
| --- | --- | --- |
| **人工操作** | GSC → 人工操作 | 读描述，修复，申请复议。 |
| **有用内容降权** | 全站流量无明显原因下滑 | 审计内容的一手经验与价值。 |
| **链接作弊** | GSC → 人工操作 → 非自然链接 | 拒绝坏链接；申请删除。 |
| **伪装 / 隐蔽重定向** | GSC → 人工操作 | 移除伪装；对爬虫和用户返回相同内容。 |
| **薄内容** | 覆盖 → "已抓取，当前未收录" | 增值或删除。 |

## 谷歌 SEO 速查清单

小站 1 小时清单：

- [ ] 域名已在 Google Search Console 验证。
- [ ] Sitemap 已提交；状态 OK。
- [ ] 所有页面返回 200，无 404。
- [ ] 每个页面有唯一的 `<title>` 与 `<meta name="description">`。
- [ ] 强制 HTTPS（HTTP → 301 到 HTTPS）。
- [ ] 移动 + 桌面 Core Web Vitals 全部"良好"。
- [ ] 主页至少有一块 `Organization` JSON-LD。
- [ ] 文章页有 `Article` JSON-LD。
- [ ] 内链：每个页面 ≥ 1 个内链。
- [ ] GSC 移动可用性 OK。
- [ ] 无人为操作。
- [ ] 来自外部来源的 3+ 质量反向链接。

## 下一步？

- **3-bing-indexnow** — Bing Webmaster Tools + IndexNow 协议。
- **4-yahoo** — Yahoo Search。
- **5-duckduckgo** — DuckDuckGo SEO。
- **6-baidu** — 百度 SEO。
- **7-shenma** — 神马（移动端）。

## 源码与官方资源

- **Google Search Central：** <https://developers.google.com/search>
- **Search Console：** <https://search.google.com/search-console>
- **富结果测试：** <https://search.google.com/test/rich-results>
- **PageSpeed Insights：** <https://pagespeed.web.dev/>
- **Lighthouse：** <https://developer.chrome.com/docs/lighthouse/overview>
- **Schema.org：** <https://schema.org/>