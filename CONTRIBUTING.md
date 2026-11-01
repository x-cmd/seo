# Contributing — `x-cmd/seo`

This page covers how to add or modify an article in the SEO
topic library.

**Looking to read?** See [`README.md`](./README.md) or
[`SKILL.md`](./SKILL.md).

## Chapters and article slots

Articles are grouped into **chapters**. The chapter directory and the
leaf's `<n>-` order prefix are organization only; the site strips the
prefix, so the URL slug is the name after it (`2-korea/` →
`x-cmd.com/seo/korea/`).

| Chapter | Slot | Article | Add a new one? |
| --- | --- | --- | --- |
| `1-fundamentals` | `seo-basics` | What is SEO + small-site indexing. | Refresh in place. |
| `1-fundamentals` | `da` | DA / DR — Moz Domain Authority vs Ahrefs Domain Rating. | Refresh in place. |
| `2-global-engines` | `google-seo` | Google SEO + Search Console. | Refresh in place. |
| `2-global-engines` | `bing-indexnow` | Bing + IndexNow. | Refresh in place. |
| `2-global-engines` | `duckduckgo` | DuckDuckGo SEO. | Refresh in place. |
| `2-global-engines` | `yahoo` | Yahoo Search. | Refresh in place. |
| `2-global-engines` | `yandex` | Yandex SEO (Russian-language). | Refresh in place. |
| `3-china-engines` | `baidu` | Baidu SEO. | Refresh in place. |
| `3-china-engines` | `shenma` | Shenma SEO. | Refresh in place. |
| `3-china-engines` | `sogou` | Sogou SEO (Tencent / WeChat). | Refresh in place. |
| `4-regional-markets` | `overview` | Local engines: three shapes, and how to pick. | Refresh in place. |
| `4-regional-markets` | `korea` | Korea — Naver / Daum / Kakao. | Refresh in place. |
| `4-regional-markets` | `japan` | Japan — Yahoo! JAPAN + carrier engines. | Refresh in place. |
| `4-regional-markets` | `taiwan` | Taiwan — Google + Yahoo! Taiwan. | Refresh in place. |
| `4-regional-markets` | `vietnam` | Vietnam — Cốc Cốc. | Refresh in place. |
| `4-regional-markets` | `southeast-asia` | Indonesia / Thailand / Philippines. | Refresh in place. |
| `4-regional-markets` | `czech` | Czech Republic — Seznam. | Refresh in place. |
| `4-regional-markets` | `western-europe` | Germany / France / Netherlands. | Refresh in place. |
| `4-regional-markets` | `russia` | Russia — Yandex's home turf. | Refresh in place. |
| `4-regional-markets` | `india` | India — Google's near-monopoly. | Refresh in place. |
| `4-regional-markets` | `brazil` | Brazil — Bing / Yahoo over-index. | Refresh in place. |

New slots can introduce additional topics (Brave Search, on-page
SEO, technical SEO, …) — open a PR with a new 4-tuple slot inside
the chapter it belongs to.

## Per-slot file convention

Every article slot is a **folder of four files, kept in sync**:

| File | Purpose | Required? |
| --- | --- | --- |
| `docs/<chapter>/<slug>/en.md` | Canonical English article. | ✅ |
| `docs/<chapter>/<slug>/cn.md` | Chinese translation. | ✅ |
| `docs/<chapter>/<slug>/llms.md` | LLM-friendly summary — YAML frontmatter + flat prose. | ✅ |
| `docs/<chapter>/<slug>/faq.yml` | Structured Q&A used for FAQ + JSON-LD. | ✅ |

If you change `en.md`, change `cn.md` in the same commit.

## English frontmatter

```yaml
---
x-title: Google SEO — Ranking Factors, Search Console, and Sitemaps
x-desc: >-
  A practical guide to ranking on Google in 2026 — E-E-A-T, Core Web
  Vitals, structured data, and how to use Google Search Console.
x-sidebar: Google SEO
x-keywords: google seo, search console, eeat, core web vitals, sitemap
x-json-ld:
  '@context': https://schema.org
  '@graph':
    - '@type': TechArticle
      headline: 'Google SEO'
      inLanguage: 'en'
      about: 'Google search engine optimization'
---
```

## `.llms.md` format

```markdown
---
name: 3-google-seo
description: Practical guide to ranking on Google in 2026 — E-E-A-T,
  Core Web Vitals, structured data, Search Console workflow.
type: summary
---

# Core Content

core_features:
  - E-E-A-T signals (Experience, Expertise, Authoritativeness, Trust)
  - Core Web Vitals (LCP, INP, CLS)
  - Structured data (JSON-LD, Schema.org)

# Key Information

highlights:
  - Google holds ~91% of global search market
  - Search Console is the free tool to monitor indexing

# Summary

…
```

## `.faq.yml` format

```yaml
id: x-seo-google-seo

data:
  - name:
      en: overview
      cn: 概览
    qa:
      - id: what-is-google-search-console
        question:
          en: What is Google Search Console?
          cn: 什么是 Google Search Console？
        answer:
          en: A free tool from Google that shows how Google sees your site — indexing status, search queries, sitemaps, manual actions.
          cn: Google 提供的免费工具，展示 Google 如何看待你的网站——收录状态、搜索查询、sitemap、人工操作。
        confidence: 9
        reference:
          - docs/2-global-engines/1-google-seo/en.md
          - docs/2-global-engines/1-google-seo/cn.md
```

Each FAQ entry has:

- `id` — kebab-case, unique within the file
- `question` — bilingual `en` + `cn`
- `answer` — bilingual `en` + `cn`, ≤ 4 sentences each
- `confidence` (1–9) — how confident the team is
- `reference` — list of article files that back the answer

## Editing rules

- **One slot per commit.** Don't mix two engines or two markets.
- **Both languages in the same commit.**
- **Links use `[label](url)`.** No bare URLs and no `<url>`
  autolinks — including in the source lists.
- **Quote from official sources only** — Google's official
  docs, Bing's Webmaster Tools, Baidu's Search Resource
  Platform, etc.
- **Don't quote from `x-cmd-install/mneme`.** Private repo.
- **Don't discuss intent.** Articles are content-only.

## CI

The site's build pipeline validates:

1. Every `en.md` has a matching `cn.md`.
2. Every slot has an `llms.md` and a `faq.yml`.
3. The `faq.yml` is valid YAML and `id`s are unique.

## What this repo is NOT

- **Not** a course or tutorial — articles are factual and
  tool-focused, not commercial-coaching material.
- **Not** a place for SEO "growth hacks" that violate search
  engine guidelines.
- **Not** an SEO agency pitch.