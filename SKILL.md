---
name: seo
description: SEO topic library — basics, Google / Bing / Yahoo / DuckDuckGo / Baidu / Shenma, and small-site indexing strategies. Use when the user asks about "SEO", "search engine optimization", "Google Search Console", "IndexNow", "Baidu SEO", "Shenma", or how to rank / get indexed.
metadata: type=topic-library, source=team-curated, schema=4-tuple-md, refresh=manual, license=apache-2.0, scope=seo
---

# x-cmd/seo — using the SEO topic library

## 1. Read on the website

The articles are published at <https://x-cmd.com/seo>. Each
per-engine article lives at `/seo/<slug>` (e.g.
`/seo/google-seo`, `/seo/bing-indexnow`).

## 2. Use the raw files

Plain markdown + YAML, served over HTTPS from GitHub. Fetch
directly from `https://raw.githubusercontent.com/x-cmd/seo/main/...`
— do not route through any CDN or proxy.

```sh
# All four files for one slot
for ext in en.md cn.md llms.md faq.yml; do
  curl -fsSL "https://raw.githubusercontent.com/x-cmd/seo/main/docs/1-seo-basics.$ext"
done
```

## Article schema (per slot)

Each slot is four files, kept in sync:

| File | Shape | Purpose |
| --- | --- | --- |
| `n-<slug>.en.md` | Markdown with YAML frontmatter. | Canonical English article. |
| `n-<slug>.cn.md` | Same, in Chinese. | Chinese translation. |
| `n-<slug>.llms.md` | YAML frontmatter + flat structured sections. | LLM-friendly summary. |
| `n-<slug>.faq.yml` | Bilingual `question` + `answer`. | FAQ + JSON-LD. |

## Slot conventions

| Slot | Article | Style |
| --- | --- | --- |
| `1-seo-basics` | What is SEO + small-site indexing. | Definitions + practical tips. |
| `2-google-seo` | Google SEO + Search Console. | Google-specific. |
| `3-bing-indexnow` | Bing + IndexNow protocol. | Bing-specific. |
| `4-yahoo` | Yahoo Search (independent). | Yahoo-specific. |
| `5-duckduckgo` | DuckDuckGo SEO. | DuckDuckGo-specific. |
| `6-baidu` | Baidu SEO. | Baidu-specific (Chinese). |
| `7-shenma` | Shenma SEO (mobile). | Shenma-specific (Chinese). |

## Common agent queries

```sh
# "How do I get my site indexed on Google?" — read 1-seo-basics, then 2-google-seo.
# "How do I submit URLs to Bing fast?" — read 3-bing-indexnow.
# "How do I optimize for Baidu?" — read 6-baidu.
# "Why doesn't my site appear on DuckDuckGo?" — read 5-duckduckgo.
# "What's IndexNow?" — read 3-bing-indexnow.
# "What does Search Console do?" — read 2-google-seo.
```

When a question requires per-engine guidance, **always cross-
check** the relevant per-engine article — do not invent
guidance from memory. The articles are the source of truth.

## Sources

- <https://github.com/x-cmd/seo> — this repo.
- <https://x-cmd.com/seo> — published articles.
- [Google Search Central](https://developers.google.com/search) — Google's official SEO docs.
- [Bing Webmaster Tools](https://www.bing.com/webmasters) — Bing's official tool.
- [IndexNow](https://www.indexnow.org/) — the IndexNow protocol site.
- [Baidu Search Resource Platform](https://ziyuan.baidu.com/) — Baidu's official tool.