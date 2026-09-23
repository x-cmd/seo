---
x-title: Baidu SEO — Chinese-Language Search, ICP Filing, and Baidu Search Resource Platform
x-desc: >-
  Baidu is the dominant Chinese-language search engine, holding
  ~75% of the Chinese-language search market in 2026. ICP filing
  requirement for mainland-China sites. Baidu Search Resource
  Platform (ziyuan.baidu.com) for sitemap + manual submissions.
x-sidebar: Baidu SEO
x-keywords: baidu seo, baidu search resource platform, icp filing, baidu spider, baidu zhanzhang
x-json-ld:
  '@context': https://schema.org
  '@graph':
    - '@type': TechArticle
      headline: 'Baidu SEO'
      inLanguage: 'en'
      about: 'Baidu search engine optimization'
---

# Baidu SEO — Chinese-Language Search, ICP Filing, and Baidu Search Resource Platform

**Baidu** is the dominant Chinese-language search engine,
holding roughly **75% of the Chinese-language search market**
in 2026. For Chinese-language content targeting mainland
China, Baidu is the default search engine — Google is mostly
blocked there.

Baidu has its own ranking factors, its own crawlers
(Baiduspider / Baiduspider-image), its own webmaster tool
(Baidu Search Resource Platform, 百度搜索资源平台), and its
own ecosystem of products (Baidu Tieba, Baike, Zhidao,
Maps).

This article covers Baidu-specific SEO: how to optimize for
Baidu, ICP filing requirements, and how Baidu differs from
Google.

> **TL;DR.** Baidu SEO = ICP filing + Chinese-language content
> + Baidu Search Resource Platform + ties to Baidu's own
> products. Slower indexing than Google; favors older domains;
> heavy weight on title / meta / keyword density; supports
> Schema.org JSON-LD.

## Why Baidu?

- **~75% of Chinese-language search market** (StatCounter
  Q2 2026).
- **~50%+ of mainland China's search traffic** by query
  volume.
- **Default search engine in Chinese-language browsers.**
- **Heavy investment in AI features** — Baidu Ernie, AI
  Overviews in Chinese.

If your audience is in mainland China or speaks Chinese,
Baidu is the primary target. Hong Kong / Taiwan / overseas
Chinese audiences also use Baidu but with Google as a
stronger secondary.

## Baidu vs Google — what's different

Baidu's algorithm is similar to Google's at the foundation
(content quality, backlinks, technical health) but with
distinct emphases.

### Where Baidu differs from Google

- **ICP filing required** for mainland-China sites
  (otherwise search results may be restricted or removed).
- **Title + meta keywords matter more.** Baidu historically
  weighs the `<meta name="keywords">` tag (which Google
  ignores).
- **Keyword density** — Baidu weighs keyword repetition in
  body content more than Google.
- **Domain age** — Baidu favors older domains more than
  Google.
- **Tieba / Baike / Zhidao links** — Baidu ranks its own
  products higher in search results.
- **HTTPS** — required since 2015.
- **Slow indexing** — 1-4 weeks for new sites vs Google's
  1-7 days.
- **Mobile-friendliness** — has its own mobile rules.

### Where Baidu agrees with Google

- **Content quality + E-E-A-T-like signals** (Baidu has its
  own version, sometimes called "搜索结果质量").
- **Backlinks** — quality and quantity.
- **Structured data** — Baidu supports Schema.org JSON-LD.
- **Mobile** — mobile-friendly is required.
- **Page speed** — including Baidu's own MIP framework
  (mostly deprecated in 2026, replaced by standard
  Accelerated Mobile Pages).
- **Sitemap** — XML sitemaps accepted.

## ICP filing (备案)

For mainland-China servers, China requires an **ICP filing**
(备案, "bei'an") with the Ministry of Industry and
Information Technology (MIIT).

Without ICP filing:

- Sites served from mainland China servers may be blocked
  by Chinese ISPs.
- Baidu may suppress unfiled sites in search results.
- Apple requires ICP filing for non-Chinese app publishers
  to serve apps in China.

How to file:

1. Host your site on a mainland-China server (Aliyun,
   Tencent Cloud, etc.).
2. Register with the host provider.
3. Submit the filing through the host provider's portal —
   they file with MIIT on your behalf.
4. Wait 7-20 days for approval.
5. Add the ICP number to your site's footer (required).

Two types:

- **ICP备案** (bei'an) — required for all sites served
  from China.
- **公安备案** (gongan bei'an) — required for sites with
  user-generated content (forums, comments).

For overseas servers (Hong Kong, Singapore, US), ICP filing
is **not** required. Baidu will still index your site, but
you may have less competitive advantage than Chinese-hosted
sites.

## Baidu Search Resource Platform

**百度搜索资源平台** (<https://ziyuan.baidu.com/>) is
Baidu's free webmaster tool. Mirror of Google Search
Console + Bing Webmaster Tools.

### Setup

1. Go to <https://ziyuan.baidu.com/>.
2. Sign in with a Baidu account (百度账号).
3. Verify your site via:
   - **HTML file** — `baidu_verify_*.html` at the root.
   - **Meta tag** — `<meta name="baidu-site-verification" content="...">`.
   - **DNS CNAME** — Baidu-specific verification record.
4. Once verified, data starts collecting within 24-72
   hours.

### Daily / weekly workflow

1. **数据监控** → search queries, indexed pages, crawl
   errors.
2. **链接提交** → submit sitemap, manual URL submission,
   API submission.
3. **抓取诊断** → crawler status, robots.txt check.
4. **搜索展现** → SERP appearance, rich results.
5. **移动适配** → mobile-friendly test.
6. **百度站长工具** → backlink analysis, keyword
   analysis.

## Submitting URLs to Baidu

Baidu offers four ways to submit URLs:

### 1. Sitemap submission

Same XML sitemap format as Google / Bing. Submit via the
Sitemap tool in Baidu Search Resource Platform.

### 2. Manual submission

In the Search Resource Platform, paste a single URL or up
to 20 URLs. Use sparingly — for important new content.

### 3. API submission

```sh
curl -X POST "https://ziyuan.baidu.com/linksubmit/jsonandsubmit" \
  -d 'site=example.com&token=YOUR_TOKEN&type=original' \
  -F "urls[]=https://example.com/new-page-1" \
  -F "urls[]=https://example.com/new-page-2"
```

Limits: 1,000 URLs per submit; 10 submits per day per
site.

### 4. Auto-push (JS snippet)

Baidu provides a JavaScript snippet to embed in your page
that pushes URLs to Baidu as users visit them.

```html
<script>
(function(){
    var bp = document.createElement('script');
    bp.src = '//push.zhanzhang.baidu.com/push.js';
    var s = document.getElementsByTagName("script")[0];
    s.parentNode.insertBefore(bp, s);
})();
</script>
```

This is the easiest "auto push" mechanism for Baidu —
every page-view pushes the URL to Baidu's queue.

## Baidu-specific ranking factors

### Content

- **Title** — most-weighted on-page signal. Include
  primary keyword.
- **Meta description** — Baidu weighs it (Google doesn't
  use it for ranking).
- **Meta keywords** — Baidu reads it (Google ignores it).
- **H1 / H2 / H3** — structure matters.
- **Keyword density** — 2-3% is the historical sweet spot
  (Google ignores this).
- **Original content** — Baidu penalizes scraped /
  aggregated content.
- **Baidu Tieba / Baike / Zhidao presence** — having
  relevant Baidu-product pages can boost your site
  indirectly.

### Technical

- **ICP filing** — for mainland China.
- **HTTPS** — required.
- **Mobile-friendly** — required.
- **Page speed** — Baidu's MIP (mobile instant page)
  framework mostly deprecated in 2026.
- **Structured data** — Baidu supports Schema.org JSON-LD;
  also supports its own Baidu-specific schemas (Baidu
  Tongyong, 百度通用).
- **Sitemap** — submit via the Search Resource Platform.

### Off-page

- **Backlinks** — quality and quantity. Baidu weights
  Chinese-domain backlinks (`.cn`, `.com.cn`, `.com`)
  more than foreign-domain.
- **Anchor text** — Baidu weighs exact-match anchor text
  more than Google.
- **Domain age** — older Chinese domains rank better.

## Baidu AI features

In 2026, Baidu ships:

- **AI 摘要** — AI Overview equivalent for Chinese
  queries.
- **Baidu Ernie** — Baidu's underlying LLM.
- **AI Search** — chat-based query interface.

Same pattern as Google / DuckDuckGo: cite high-quality
sources, long-form first-hand Chinese content wins.

## Common Baidu SEO mistakes

- **No ICP filing** — sites hosted outside China don't need
  it, but mainland-hosted sites without ICP are at a
  disadvantage.
- **English-only content targeting China** — Baidu ranks
  Chinese content higher. Translate to Simplified Chinese,
  use Simplified Chinese keywords.
- **Title keyword stuffing** — `<title>SEO|SEM|PPC|...
  </title>` is penalized.
- **Hidden text** — same color background and text is
  penalized.
- **Buying links** — Baidu may suppress.
- **Sitemap not submitted** — without sitemap, Baidu's
  crawler can miss pages.
- **No Tieba / Baike / Zhidao presence** — having a
  presence on Baidu's own products helps indirectly.

## Quick Baidu checklist

A 1-hour checklist for Chinese-market sites:

- [ ] ICP filing obtained (mainland China servers).
- [ ] ICP number displayed in footer.
- [ ] Baidu Search Resource Platform account created.
- [ ] Site verified via HTML / meta / DNS.
- [ ] XML sitemap submitted.
- [ ] Auto-push JS snippet installed.
- [ ] All titles + meta descriptions in Simplified Chinese.
- [ ] HTTPS enforced.
- [ ] Mobile-friendly test passes.
- [ ] Structured data in place (JSON-LD or Baidu-specific).
- [ ] 3+ backlinks from Chinese `.cn` / `.com.cn` domains.

## Baidu vs Google — at a glance

| Dimension | Baidu | Google |
| --- | --- | --- |
| Language | Chinese (Simplified) primary | Global |
| ICP filing | Required (mainland China) | None |
| Meta keywords | Weighed | Ignored |
| Keyword density | Weighted | Ignored |
| Domain age | Weighted | Slightly weighted |
| Tieba / Baike | Self-products ranked high | N/A |
| Sitemap | ✅ | ✅ |
| Structured data | Schema.org + Baidu-specific | Schema.org |
| Indexing speed | 1-4 weeks (slow) | 1-7 days |
| AI features | AI 摘要 + Ernie | AI Overviews + Gemini |
| Market share (Q2 2026) | ~75% Chinese-language | ~91% global |

## What's next?

- **7-shenma** — Shenma SEO (mobile, Chinese).

## Source & Official Resources

- **Baidu Search Resource Platform:**
  <https://ziyuan.baidu.com/>
- **Baidu Tieba:** <https://tieba.baidu.com/>
- **Baidu Baike:** <https://baike.baidu.com/>
- **Baidu Zhidao:** <https://zhidao.baidu.com/>
- **Baidu Maps:** <https://map.baidu.com/>
- **ICP filing info (Aliyun):**
  <https://help.aliyun.com/knowledge_detail/31745.html>
- **Baidu Search Help (zh):**
  <https://help.baidu.com/question?prod_en=zhidao>