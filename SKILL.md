---
name: seo
description: SEO topic library — basics, DA / DR (Moz + Ahrefs), Google / Bing / DuckDuckGo / Yahoo / Yandex / Baidu / Shenma / Sogou, and regional search markets (Korea, Japan, Taiwan, Vietnam, Southeast Asia, Czech, German-speaking Europe, Russia, India, Brazil). Use when the user asks about "SEO", "search engine optimization", "Domain Authority", "DR", "Ahrefs", "Moz", "Google Search Console", "IndexNow", "Baidu SEO", "Shenma", "Sogou", "Naver", "search engine market share", or how to rank / get indexed.
metadata: type=topic-library, source=team-curated, schema=4-tuple-md, refresh=manual, license=apache-2.0, scope=seo
---

# x-cmd/seo — using the SEO topic library

## 1. Read on the website

The articles are published at [x-cmd.com/seo](https://x-cmd.com/seo).
Each article lives at `/seo/<slug>` (e.g. `/seo/google-seo`,
`/seo/bing-indexnow`, `/seo/korea`).

## 2. Use the raw files

Plain markdown + YAML, served over HTTPS from GitHub. Fetch
directly from `https://raw.githubusercontent.com/x-cmd/seo/main/...`
— do not route through any CDN or proxy.

```sh
# All four files for one slot
for ext in en.md cn.md llms.md faq.yml; do
  curl -fsSL "https://raw.githubusercontent.com/x-cmd/seo/main/docs/1-fundamentals/seo-basics/$ext"
done
```

## Article schema (per slot)

Each slot is four files, kept in sync:

| File | Shape | Purpose |
| --- | --- | --- |
| `<slug>/en.md` | Markdown with YAML frontmatter. | Canonical English article. |
| `<slug>/cn.md` | Same, in Chinese. | Chinese translation. |
| `<slug>/llms.md` | YAML frontmatter + flat structured sections. | LLM-friendly summary. |
| `<slug>/faq.yml` | Bilingual `question` + `answer`. | FAQ + JSON-LD. |

Articles live in **chapters**: `docs/<n>-<chapter>/<slug>/`. The
chapter directory is organization only — the leaf folder name is the
URL slug (`x-cmd.com/seo/<slug>/`).

## Chapters and slots

| Chapter | Slot | Article | Style |
| --- | --- | --- | --- |
| `1-fundamentals` | `seo-basics` | What is SEO + small-site indexing. | Definitions + practical tips. |
| `1-fundamentals` | `da` | DA / DR — Moz Domain Authority vs Ahrefs Domain Rating. | Cross-cutting — query tools + scoring caveats. |
| `2-global-engines` | `google-seo` | Google SEO + Search Console. | Google-specific. |
| `2-global-engines` | `bing-indexnow` | Bing + IndexNow protocol. | Bing-specific. |
| `2-global-engines` | `duckduckgo` | DuckDuckGo SEO. | DuckDuckGo-specific. |
| `2-global-engines` | `yahoo` | Yahoo Search (independent). | Yahoo-specific. |
| `2-global-engines` | `yandex` | Yandex SEO (Russian-language). | Yandex-specific (Russian). |
| `3-china-engines` | `baidu` | Baidu SEO. | Baidu-specific (Chinese). |
| `3-china-engines` | `shenma` | Shenma SEO (mobile). | Shenma-specific (Chinese). |
| `3-china-engines` | `sogou` | Sogou SEO (Tencent / WeChat). | Sogou-specific (Chinese). |
| `4-regional-markets` | `overview` | Local engines: three shapes, and how to pick. | Cross-cutting — market selection. |
| `4-regional-markets` | `korea` | Korea — Naver / Daum / Kakao. | Market-specific (Korean). |
| `4-regional-markets` | `japan` | Japan — Yahoo! JAPAN + carrier engines. | Market-specific (Japanese). |
| `4-regional-markets` | `taiwan` | Taiwan — Google + Yahoo! Taiwan. | Market-specific (Chinese). |
| `4-regional-markets` | `vietnam` | Vietnam — Cốc Cốc. | Market-specific (Vietnamese). |
| `4-regional-markets` | `southeast-asia` | Indonesia / Thailand / Philippines. | Market-specific (regional). |
| `4-regional-markets` | `czech` | Czech Republic — Seznam. | Market-specific (Czech). |
| `4-regional-markets` | `german-speaking-europe` | Germany / France / Netherlands. | Market-specific (regional). |
| `4-regional-markets` | `russia` | Russia — Yandex's home turf. | Market-specific (Russian). |
| `4-regional-markets` | `india` | India — Google's near-monopoly. | Market-specific (Indian). |
| `4-regional-markets` | `brazil` | Brazil — Bing / Yahoo over-index. | Market-specific (Brazilian). |

## Common agent queries

```sh
# "How do I get my site indexed on Google?" — read seo-basics, then google-seo.
# "What is DA / DR — how do I check a domain's authority?" — read da.
# "How do I submit URLs to Bing fast?" — read bing-indexnow.
# "How do I optimize for Baidu?" — read baidu.
# "Why doesn't my site appear on DuckDuckGo?" — read duckduckgo.
# "What's IndexNow?" — read bing-indexnow.
# "What does Search Console do?" — read google-seo.
# "How do I optimize for Yandex?" — read yandex.
# "How do I submit URLs to Sogou?" — read sogou.
# "Which search engine matters in Korea?" — read korea.
# "How do I reach Japanese users?" — read japan.
# "Do I need to optimize for a local engine outside the US?" — read overview.
```

When a question requires per-engine guidance, **always cross-
check** the relevant per-engine article — do not invent
guidance from memory. The articles are the source of truth.

## Sources

- [This repo](https://github.com/x-cmd/seo) — the source.
- [Published articles](https://x-cmd.com/seo) — the live library.
- [Google Search Central](https://developers.google.com/search) — Google's official SEO docs.
- [Bing Webmaster Tools](https://www.bing.com/webmasters) — Bing's official tool.
- [IndexNow](https://www.indexnow.org/) — the IndexNow protocol site.
- [Baidu Search Resource Platform](https://ziyuan.baidu.com/) — Baidu's official tool.