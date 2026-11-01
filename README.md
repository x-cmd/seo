# x-cmd/seo — SEO topic library

Articles, comparisons, and per-engine deep dives on search
engine optimization. Published as a topic library at
<https://x-cmd.com/seo>.

> 🌐 **中文版：[README.cn.md](./README.cn.md)** — same content,
> Chinese front matter.

This repo holds the canonical English / Chinese articles that
back the **SEO** section of the x-cmd website. Articles are
content-only, factual, and open for **modification PRs** from
anyone — see [`CONTRIBUTING.md`](./CONTRIBUTING.md).

## What's in this repo

```
x-cmd/seo/
├── README.md                 # this file (English)
├── README.cn.md              # Chinese version
├── CONTRIBUTING.md           # article workflow + frontmatter spec + FAQ schema
├── SKILL.md                  # AI-agent recipe
├── LICENSE                   # Apache-2.0
└── docs/
    ├── README.md             # chapter-by-chapter index
    ├── _sidebar.yml          # chapter → page navigation
    ├── 1-fundamentals/       # the shared vocabulary
    │   ├── 1-seo-basics/     # what is SEO + small-site indexing
    │   ├── 2-da/             # DA / DR — Moz + Ahrefs link authority metrics
    │   └── 3-search-engines/ # every engine in one table
    ├── 2-global-engines/     # the engines that compete everywhere
    │   ├── 1-google-seo/     # Google SEO + Search Console
    │   ├── 2-bing-indexnow/  # Bing Webmaster Tools + IndexNow
    │   ├── 3-duckduckgo/     # DuckDuckGo SEO
    │   ├── 4-yahoo/          # Yahoo Search (independent)
    │   └── 5-yandex/         # Yandex SEO (Russian-language)
    ├── 3-china-engines/      # the Chinese-language engines
    │   ├── 1-baidu/          # Baidu SEO
    │   ├── 2-shenma/         # Shenma SEO (UC / mobile)
    │   └── 3-sogou/          # Sogou SEO (Tencent / WeChat)
    └── 4-regional-markets/   # where the local engine beats the global one
        ├── 1-overview/       # how local engines differ, and what to optimize
        ├── 2-korea/          # Naver, Daum, Kakao
        ├── 3-japan/          # Yahoo! JAPAN, carrier engines
        ├── 4-taiwan/         # Google + Yahoo! Taiwan
        ├── 5-vietnam/        # Cốc Cốc
        ├── 6-southeast-asia/ # Android defaults + in-app search
        ├── 7-czech/          # Seznam
        ├── 8-western-europe/  # Ecosia, MetaGer, Qwant, Startpage
        ├── 9-russia/         # Yandex's home turf
        ├── 10-india/         # Google's near-monopoly
        └── 11-brazil/        # where Bing and Yahoo still over-index
```

Articles are grouped into **chapters**. Leaf folder names carry a
`<n>-` prefix that fixes the reading order; the site strips the
number when publishing, so the URL slug is the name after the
prefix — `2-korea/` is published as `x-cmd.com/seo/korea/`.

Every article exists in five languages — `en.md`, `cn.md`, `de.md`,
`pt.md`, `ja.md` (the same set as [x-cmd/dbnomics](https://github.com/x-cmd/dbnomics)) —
plus a language-neutral `llms.md` summary and a bilingual `faq.yml`,
all kept in sync. Languages currently at en+cn are being extended to
the full five.

## Chapters

### 1 · Fundamentals

| Article | Purpose |
| --- | --- |
| [`seo-basics`](./docs/1-fundamentals/1-seo-basics/en.md) | What is SEO + how small sites improve indexing — definitions, core concepts, sitemap / robots.txt / structured data / backlinks. |
| [`da`](./docs/1-fundamentals/2-da/en.md) | DA / DR — Moz Domain Authority vs Ahrefs Domain Rating — the two leading third-party link-authority metrics, why they don't agree, and the fastest no-login lookup. |
| [`search-engines`](./docs/1-fundamentals/3-search-engines/en.md) | Search engines of the world in one table — index ownership, 2025 home share, user estimates, SEO relevance, and how to get indexed, each row linking to its article. |

### 2 · Global engines

| Article | Purpose |
| --- | --- |
| [`google-seo`](./docs/2-global-engines/1-google-seo/en.md) | Google SEO + Search Console — the biggest search engine; how to optimize for it; how to use Google Search Console. |
| [`bing-indexnow`](./docs/2-global-engines/2-bing-indexnow/en.md) | Bing Webmaster Tools + IndexNow — the instant-submission protocol. |
| [`duckduckgo`](./docs/2-global-engines/3-duckduckgo/en.md) | DuckDuckGo SEO — privacy-focused; Bing-derived; smaller market share but growing. |
| [`yahoo`](./docs/2-global-engines/4-yahoo/en.md) | Yahoo Search — Yahoo as a separate search engine (powered by Bing, but with its own products). |
| [`yandex`](./docs/2-global-engines/5-yandex/en.md) | Yandex SEO — the Russian-language search giant; Yandex.Webmaster + Yandex.Metrica ecosystem. |

### 3 · Chinese engines

| Article | Purpose |
| --- | --- |
| [`baidu`](./docs/3-china-engines/1-baidu/en.md) | Baidu SEO — the Chinese-language search giant; Baidu Search Resource Platform. |
| [`shenma`](./docs/3-china-engines/2-shenma/en.md) | Shenma SEO — the mobile-focused Chinese search engine by UC Browser. |
| [`sogou`](./docs/3-china-engines/3-sogou/en.md) | Sogou SEO — Tencent-backed Chinese search; deep WeChat / QQ ecosystem integration. |

### 4 · Regional markets

Google is the default almost everywhere. It is not the default
everywhere. These pages cover the markets where a local engine takes
a real share, how that market actually searches, and what an optimizer
has to change.

| Article | Purpose |
| --- | --- |
| [`overview`](./docs/4-regional-markets/1-overview/en.md) | The three shapes of local engine — independent index, licensed wrapper, meta-search — and how to decide what is worth optimizing. |
| [`korea`](./docs/4-regional-markets/2-korea/en.md) | Korea — Naver's vertical search, Daum inside KakaoTalk, and why a Korean query is a question rather than a keyword. |
| [`japan`](./docs/4-regional-markets/3-japan/en.md) | Japan — Yahoo! JAPAN as a distinct product on Google's index, plus the carrier engines. |
| [`taiwan`](./docs/4-regional-markets/4-taiwan/en.md) | Taiwan — Google's default and Yahoo! Taiwan's persistent second place. |
| [`vietnam`](./docs/4-regional-markets/5-vietnam/en.md) | Vietnam — Cốc Cốc, an independent index built and run in Vietnam. |
| [`southeast-asia`](./docs/4-regional-markets/6-southeast-asia/en.md) | Southeast Asia — Android default placements and in-app search taking queries away from Google. |
| [`czech`](./docs/4-regional-markets/7-czech/en.md) | Czech Republic — Seznam, a real independent index rather than a wrapper, with its own webmaster tools. |
| [`western-europe`](./docs/4-regional-markets/8-western-europe/en.md) | Germany, France, the Netherlands — Ecosia, MetaGer, Qwant, Startpage, and Google's slide. |
| [`russia`](./docs/4-regional-markets/9-russia/en.md) | Russia — Yandex's home turf after 2022, and the state-aligned alternatives. |
| [`india`](./docs/4-regional-markets/10-india/en.md) | India — Google's near-monopoly, and the wobble AI search is putting in it. |
| [`brazil`](./docs/4-regional-markets/11-brazil/en.md) | Brazil — where Bing and Yahoo still over-index against their global average. |

## Sister repos

- [`x-cmd/cve`](https://github.com/x-cmd/cve) — topic library pattern reference.
- [`x-cmd/gpg`](https://github.com/x-cmd/gpg) — topic library pattern reference.
- [`x-cmd/terminal](https://github.com/x-cmd/terminal) — terminal topic library.
- [`x-cmd/browser](https://github.com/x-cmd/browser) — browser topic library.
- [`x-cmd/ghclaw](https://github.com/x-cmd/ghclaw) — GitHub event claw design.

## License

Apache License 2.0 — see [`LICENSE`](./LICENSE).
