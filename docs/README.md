# seo — docs

Search engine optimization, one engine and one market at a time.
Published at <https://x-cmd.com/seo>.

The library is grouped into four chapters. Chapter 1 is the shared
vocabulary, chapter 2 the engines that compete worldwide, chapter 3 the
Chinese-language engines, and chapter 4 the markets where the local
engine beats the global one.

Every article below exists in five languages — English, 中文,
Deutsch, Español, 日本語 (`en.md`, `cn.md`, `de.md`, `es.md`, `ja.md`,
the set used by x-cmd/dbnomics) — and carries a language-neutral
`llms.md` summary and a bilingual `faq.yml`. Articles not yet at five
languages are being extended from en+cn.

## 1 · Fundamentals

| page | what it covers |
|---|---|
| [SEO Basics](1-fundamentals/1-seo-basics/en.md) | what SEO is, the crawl → index → rank pipeline, and how a small site gets indexed |
| [DA / DR](1-fundamentals/2-da/en.md) | Moz Domain Authority vs Ahrefs Domain Rating — where the numbers come from, why they disagree |
| [Search engines at a glance](1-fundamentals/3-search-engines/en.md) | every engine in one table — index, share, users, SEO relevance, how to get in |

## 2 · Global engines

| page | engine | good for |
|---|---|---|
| [Google SEO](2-global-engines/1-google-seo/en.md) | Google | the engine that matters most, plus Search Console |
| [Bing + IndexNow](2-global-engines/2-bing-indexnow/en.md) | Bing | Webmaster Tools and the instant-submission protocol |
| [DuckDuckGo](2-global-engines/3-duckduckgo/en.md) | DuckDuckGo | privacy search, and the fact that it runs on other people's index |
| [Yahoo Search](2-global-engines/4-yahoo/en.md) | Yahoo | a separate product on top of Bing's index |
| [Yandex](2-global-engines/5-yandex/en.md) | Yandex | the Russian-language search giant |

## 3 · Chinese engines

| page | engine | good for |
|---|---|---|
| [Baidu](3-china-engines/1-baidu/en.md) | 百度 | the Chinese-language search giant, ICP 备案, 搜索资源平台 |
| [Shenma](3-china-engines/2-shenma/en.md) | 神马 | the mobile-first engine behind UC Browser |
| [Sogou](3-china-engines/3-sogou/en.md) | 搜狗 | Tencent's engine, and the WeChat / QQ ecosystem |

## 4 · Regional markets

Where the default engine is not Google. Each page covers one market:
who the local engines are, how big they actually are, how that market
searches, and what an optimizer has to do differently there.

| page | market | the local angle |
|---|---|---|
| [Regional search engines](4-regional-markets/1-overview/en.md) | overview | three shapes of local engine, and how to pick what to optimize for |
| [Korea](4-regional-markets/2-korea/en.md) | 韩国 | Naver's vertical search, and Daum inside KakaoTalk |
| [Japan](4-regional-markets/3-japan/en.md) | 日本 | Yahoo! JAPAN's own product on Google's index |
| [Taiwan](4-regional-markets/4-taiwan/en.md) | 台湾 | Google's default and Yahoo! Taiwan's second place |
| [Vietnam](4-regional-markets/5-vietnam/en.md) | 越南 | Cốc Cốc, an independent index built in Vietnam |
| [Southeast Asia](4-regional-markets/6-southeast-asia/en.md) | 东南亚 | Android defaults and in-app search eating Google queries |
| [Czech Republic](4-regional-markets/7-czech/en.md) | 捷克 | Seznam — a real independent index, not a wrapper |
| [Western Europe](4-regional-markets/8-western-europe/en.md) | 西欧 | Ecosia, MetaGer, Qwant, Startpage, and Google's slide |
| [Russia](4-regional-markets/9-russia/en.md) | 俄罗斯 | Yandex's home turf after 2022 |
| [India](4-regional-markets/10-india/en.md) | 印度 | Google's near-monopoly and the AI-search wobble |
| [Brazil](4-regional-markets/11-brazil/en.md) | 巴西 | where Bing and Yahoo still out-weigh their global average |

## Layout

```
docs/
├── README.md              # this file
├── _sidebar.yml           # chapter → page navigation
├── 1-fundamentals/
│   ├── 1-seo-basics/      # cn.md, en.md, llms.md, faq.yml
│   ├── 2-da/
│   └── 3-search-engines/
├── 2-global-engines/
│   ├── 1-google-seo/
│   ├── 2-bing-indexnow/
│   ├── 3-duckduckgo/
│   ├── 4-yahoo/
│   └── 5-yandex/
├── 3-china-engines/
│   ├── 1-baidu/
│   ├── 2-shenma/
│   └── 3-sogou/
└── 4-regional-markets/
    ├── 1-overview/
    ├── 2-korea/
    └── … (3-japan … 11-brazil)
```

One article = one folder. The `<n>-` prefix on a leaf folder fixes the
reading order; the site strips it when publishing, so the URL slug is
the name after the prefix — `2-korea/` serves at `x-cmd.com/seo/korea/`.
