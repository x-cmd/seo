# x-cmd/seo — SEO 专题文库

搜索引擎优化的文章、横向对比与按引擎的深度介绍。在
<https://x-cmd.com/seo> 以专题文库形式发布。

> 🌐 **English version: [README.md](./README.md)** — same
> content, English front matter.

本仓库托管 x-cmd 官网「SEO」专题的英中双语文章。文章为内容导向，
事实优先，欢迎任何人提交**修改 PR** — 见
[`CONTRIBUTING.md`](./CONTRIBUTING.md)。

## 仓库结构

```
x-cmd/seo/
├── README.md                 # 本文件（英文）
├── README.cn.md              # 中文版
├── CONTRIBUTING.md           # 文章写作流程 + frontmatter 规范 + FAQ schema
├── SKILL.md                  # AI agent 配方
├── LICENSE                   # Apache-2.0
└── docs/
    ├── README.md             # 分章节索引
    ├── _sidebar.yml          # 章节 → 页面导航
    ├── 1-fundamentals/       # 公共词汇
    │   ├── 1-seo-basics/     # 什么是 SEO + 小站收录
    │   ├── 2-da/             # DA / DR — Moz 域名权重 + Ahrefs 域名评分
    │   └── 3-search-engines/ # 所有引擎一张表
    ├── 2-global-engines/     # 全球竞争的引擎
    │   ├── 1-google-seo/     # 谷歌 SEO + Search Console
    │   ├── 2-bing-indexnow/  # Bing Webmaster Tools + IndexNow
    │   ├── 3-duckduckgo/     # DuckDuckGo SEO
    │   ├── 4-yahoo/          # Yahoo Search（独立）
    │   └── 5-yandex/         # Yandex SEO（俄语搜索）
    ├── 3-china-engines/      # 中文引擎
    │   ├── 1-baidu/          # 百度 SEO
    │   ├── 2-shenma/         # 神马 SEO（移动端）
    │   └── 3-sogou/          # 搜狗 SEO（腾讯 / 微信）
    └── 4-regional-markets/   # 本地引擎赢过全球引擎的市场
        ├── 1-overview/       # 本地引擎有哪几种形态，该优化谁
        ├── 2-korea/          # Naver、Daum、Kakao
        ├── 3-japan/          # Yahoo! JAPAN、运营商引擎
        ├── 4-taiwan/         # Google + Yahoo 台湾
        ├── 5-vietnam/        # Cốc Cốc
        ├── 6-southeast-asia/ # 安卓默认位 + 应用内搜索
        ├── 7-czech/          # Seznam
        ├── 8-western-europe/  # Ecosia、MetaGer、Qwant、Startpage
        ├── 9-russia/         # Yandex 的主场
        ├── 10-india/         # 谷歌近乎垄断
        └── 11-brazil/        # Bing 与 Yahoo 份额高于全球均值
```

文章按**章节**分组。叶子目录名带 `<n>-` 序号前缀，用于固定阅读顺序；
站点发布时会剥掉序号，URL slug 取前缀之后的名字——`2-korea/` 发布为
`x-cmd.com/seo/korea/`。

每篇文章是四个同步的文件：`.en.md`、`.cn.md`、`.llms.md`、`.faq.yml`。

## 章节

### 1 · 基础

| 文章 | 用途 |
| --- | --- |
| [`seo-basics`](./docs/1-fundamentals/1-seo-basics/en.md) | 什么是 SEO + 小站如何提高收录——定义、核心概念、sitemap / robots.txt / 结构化数据 / 反向链接。 |
| [`da`](./docs/1-fundamentals/2-da/en.md) | DA / DR — Moz 域名权重 vs Ahrefs 域名评分——两个最常见的第三方链接权重指标；分数为何对不上；最快的无登录查询。 |
| [`search-engines`](./docs/1-fundamentals/3-search-engines/en.md) | 世界搜索引擎一张表——索引归属、2025 主场份额、用户估计、SEO 价值与收录方式，每行链接到对应文章。 |

### 2 · 全球引擎

| 文章 | 用途 |
| --- | --- |
| [`google-seo`](./docs/2-global-engines/1-google-seo/en.md) | 谷歌 SEO + Search Console——最大的搜索引擎；如何优化；如何用 Search Console。 |
| [`bing-indexnow`](./docs/2-global-engines/2-bing-indexnow/en.md) | Bing Webmaster Tools + IndexNow——即时提交协议。 |
| [`duckduckgo`](./docs/2-global-engines/3-duckduckgo/en.md) | DuckDuckGo SEO——注重隐私；Bing 衍生结果；市场份额较小但在增长。 |
| [`yahoo`](./docs/2-global-engines/4-yahoo/en.md) | Yahoo Search——Yahoo 作为独立搜索引擎（由 Bing 驱动，但有自己的产品）。 |
| [`yandex`](./docs/2-global-engines/5-yandex/en.md) | Yandex SEO——俄语搜索龙头；Yandex.Webmaster + Yandex.Metrica 生态。 |

### 3 · 中文引擎

| 文章 | 用途 |
| --- | --- |
| [`baidu`](./docs/3-china-engines/1-baidu/en.md) | 百度 SEO——中文搜索巨头；百度搜索资源平台。 |
| [`shenma`](./docs/3-china-engines/2-shenma/en.md) | 神马 SEO——UC 浏览器背后的移动端中文搜索引擎。 |
| [`sogou`](./docs/3-china-engines/3-sogou/en.md) | 搜狗 SEO——腾讯系中文搜索；与微信 / QQ 生态深度集成。 |

### 4 · 区域市场

谷歌几乎处处是默认引擎，但不是处处都是。这一章覆盖那些本地引擎
真能拿到份额的市场、当地人实际怎么搜、以及优化时需要改什么。

| 文章 | 用途 |
| --- | --- |
| [`overview`](./docs/4-regional-markets/1-overview/en.md) | 本地引擎的三种形态——独立索引、授权套壳、元搜索——以及怎么决定值不值得投。 |
| [`korea`](./docs/4-regional-markets/2-korea/en.md) | 韩国——Naver 的垂直搜索、KakaoTalk 里的 Daum，以及为什么韩语查询更像提问而非关键词。 |
| [`japan`](./docs/4-regional-markets/3-japan/en.md) | 日本——Yahoo! JAPAN 跑在 Google 索引上的独立产品，以及运营商引擎。 |
| [`taiwan`](./docs/4-regional-markets/4-taiwan/en.md) | 台湾——谷歌的默认位与 Yahoo 台湾长期的第二。 |
| [`vietnam`](./docs/4-regional-markets/5-vietnam/en.md) | 越南——Cốc Cốc，一套在越南自建自营的独立索引。 |
| [`southeast-asia`](./docs/4-regional-markets/6-southeast-asia/en.md) | 东南亚——安卓默认入口与应用内搜索正在从谷歌手里拿走查询。 |
| [`czech`](./docs/4-regional-markets/7-czech/en.md) | 捷克——Seznam，真正的独立索引而非套壳，有自己的站长工具。 |
| [`western-europe`](./docs/4-regional-markets/8-western-europe/en.md) | 德国、法国、荷兰——Ecosia、MetaGer、Qwant、Startpage，以及谷歌的下滑。 |
| [`russia`](./docs/4-regional-markets/9-russia/en.md) | 俄罗斯——2022 年后 Yandex 的主场，以及国家背书的替代品。 |
| [`india`](./docs/4-regional-markets/10-india/en.md) | 印度——谷歌近乎垄断，以及 AI 搜索带来的晃动。 |
| [`brazil`](./docs/4-regional-markets/11-brazil/en.md) | 巴西——Bing 与 Yahoo 份额高于全球均值的地方。 |

## 姊妹仓库

- [`x-cmd/cve`](https://github.com/x-cmd/cve) — 专题文库模式参考。
- [`x-cmd/gpg`](https://github.com/x-cmd/gpg) — 专题文库模式参考。
- [`x-cmd/terminal](https://github.com/x-cmd/terminal) — 终端专题文库。
- [`x-cmd/browser](https://github.com/x-cmd/browser) — 浏览器专题文库。
- [`x-cmd/ghclaw](https://github.com/x-cmd/ghclaw) — GitHub 事件 claw 设计。

## 许可

Apache License 2.0 — 见 [`LICENSE`](./LICENSE)。
