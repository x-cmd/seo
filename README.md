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
    ├── 1-seo-basics.{en,cn,llms,faq}.md          # what is SEO + small-site indexing
    ├── 2-da.{en,cn,llms,faq}.md               # DA / DR — Moz + Ahrefs link authority metrics
    ├── 3-google-seo.{en,cn,llms,faq}.md          # Google SEO + Search Console
    ├── 4-bing-indexnow.{en,cn,llms,faq}.md       # Bing Webmaster Tools + IndexNow
    ├── 5-duckduckgo.{en,cn,llms,faq}.md          # DuckDuckGo SEO
    ├── 6-yahoo.{en,cn,llms,faq}.md               # Yahoo Search (independent)
    ├── 7-yandex.{en,cn,llms,faq}.md              # Yandex SEO (Russian-language)
    ├── 8-baidu.{en,cn,llms,faq}.md               # Baidu SEO
    ├── 9-shenma.{en,cn,llms,faq}.md              # Shenma SEO (UC / mobile)
    └── 10-sogou.{en,cn,llms,faq}.md               # Sogou SEO (Tencent / WeChat)
```

The leading integer is the reading order. Articles are kept in
sync across all four files per slot: `.en.md`, `.cn.md`,
`.llms.md`, `.faq.yml`.

## Article slots

| Slot | Article | Purpose |
| --- | --- | --- |
| `1-seo-basics` | What is SEO + how small sites improve indexing | The first article — definitions, core concepts, sitemap / robots.txt / structured data / backlinks. |
| `2-da` | DA / DR — Moz Domain Authority vs Ahrefs Domain Rating | The two leading third-party link-authority metrics, why they don't agree, and the fastest no-login lookup. |
| `3-google-seo` | Google SEO + Search Console | The biggest search engine; how to optimize for it; how to use Google Search Console. |
| `4-bing-indexnow` | Bing Webmaster Tools + IndexNow | Bing Webmaster Tools; the IndexNow protocol. |
| `5-duckduckgo` | DuckDuckGo SEO | Privacy-focused; Bing-derived; smaller market share but growing. |
| `6-yahoo` | Yahoo Search | Yahoo as a separate search engine (powered by Bing, but with its own products). |
| `7-yandex` | Yandex SEO | The Russian-language search giant; Yandex.Webmaster + Yandex.Metrica ecosystem. |
| `8-baidu` | Baidu SEO | The Chinese-language search giant; Baidu Search Resource Platform. |
| `9-shenma` | Shenma SEO | The mobile-focused Chinese search engine by UC Browser. |
| `10-sogou` | Sogou SEO | Tencent-backed Chinese search; deep WeChat / QQ ecosystem integration. |

## Sister repos

- [`x-cmd/cve`](https://github.com/x-cmd/cve) — topic library pattern reference.
- [`x-cmd/gpg`](https://github.com/x-cmd/gpg) — topic library pattern reference.
- [`x-cmd/terminal`](https://github.com/x-cmd/terminal) — terminal topic library.
- [`x-cmd/browser`](https://github.com/x-cmd/browser) — browser topic library.
- [`x-cmd/ghclaw`](https://github.com/x-cmd/ghclaw) — GitHub event claw design.

## License

Apache License 2.0 — see [`LICENSE`](./LICENSE).