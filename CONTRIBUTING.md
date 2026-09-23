# Contributing — `x-cmd/seo`

This page covers how to add or modify an article in the SEO
topic library.

**Looking to read?** See [`README.md`](./README.md) or
[`SKILL.md`](./SKILL.md).

## Article slots

| Slot | Article | Add a new one? |
| --- | --- | --- |
| `1-seo-basics` | What is SEO + small-site indexing. | Refresh in place. |
| `2-google-seo` | Google SEO + Search Console. | Refresh in place. |
| `3-bing-indexnow` | Bing + IndexNow. | Refresh in place. |
| `4-yahoo` | Yahoo Search. | Refresh in place. |
| `5-duckduckgo` | DuckDuckGo SEO. | Refresh in place. |
| `6-baidu` | Baidu SEO. | Refresh in place. |
| `7-shenma` | Shenma SEO. | Refresh in place. |

Future slots (`8-…`, `9-…`, …) can introduce additional engines
(Yandex, Naver, Sogou, etc.) — open a PR with a new 4-tuple
slot.

## Per-slot file convention

Every article slot is **four files, kept in sync**:

| File | Purpose | Required? |
| --- | --- | --- |
| `n-<slug>.en.md` | Canonical English article. | ✅ |
| `n-<slug>.cn.md` | Chinese translation. | ✅ |
| `n-<slug>.llms.md` | LLM-friendly summary — YAML frontmatter + flat prose. | ✅ |
| `n-<slug>.faq.yml` | Structured Q&A used for FAQ + JSON-LD. | ✅ |

If you change `.en.md`, change `.cn.md` in the same commit.

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
name: 2-google-seo
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
id: x-seo-2-google-seo

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
          - docs/2-google-seo.en.md
          - docs/2-google-seo.cn.md
```

Each FAQ entry has:

- `id` — kebab-case, unique within the file
- `question` — bilingual `en` + `cn`
- `answer` — bilingual `en` + `cn`, ≤ 4 sentences each
- `confidence` (1–9) — how confident the team is
- `reference` — list of article files that back the answer

## Editing rules

- **One slot per commit.** Don't mix two engines.
- **Both languages in the same commit.**
- **Quote from official sources only** — Google's official
  docs, Bing's Webmaster Tools, Baidu's Search Resource
  Platform, etc.
- **Don't quote from `x-cmd-install/mneme`.** Private repo.
- **Don't discuss intent.** Articles are content-only.

## CI

The site's build pipeline validates:

1. Every `.en.md` has a matching `.cn.md`.
2. Every slot has a `.llms.md` and a `.faq.yml`.
3. The `.faq.yml` is valid YAML and `id`s are unique.

## What this repo is NOT

- **Not** a course or tutorial — articles are factual and
  tool-focused, not commercial-coaching material.
- **Not** a place for SEO "growth hacks" that violate search
  engine guidelines.
- **Not** an SEO agency pitch.