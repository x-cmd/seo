---
x-title: Google SEO — Ranking Factors, Search Console, and Workflow
x-desc: >-
  A practical guide to ranking on Google in 2026 — E-E-A-T, Core Web
  Vitals, structured data, helpful content, AI Overviews, and how to
  use Google Search Console day-to-day.
x-sidebar: Google SEO
x-keywords: google seo, search console, eeat, core web vitals, helpful content, ai overviews, sitemap
x-json-ld:
  '@context': https://schema.org
  '@graph':
    - '@type': TechArticle
      headline: 'Google SEO'
      inLanguage: 'en'
      about: 'Google search engine optimization'
---

# Google SEO — Ranking Factors, Search Console, and Workflow

Google holds roughly **91% of the global search market** as of
2026. If you only optimize for one engine, optimize for
Google. This article covers Google-specific SEO: the
ranking-factor landscape, the daily Search Console workflow,
and the 2026 specifics (Helpful Content, AI Overviews,
structured data).

> **TL;DR.** Google SEO = E-E-A-T + Core Web Vitals + helpful
> content + structured data. Free tool: Google Search
> Console. Submit sitemap, monitor Coverage + Performance,
> fix issues. AI Overviews shift clicks down; long-form
> first-hand content wins.

## Why Google?

- **~91% of global search market** (StatCounter Q2 2026).
- **~88% of mobile search market**.
- **~85% of US desktop search market**.

Alternatives (Bing, DuckDuckGo, Baidu) matter — see the
follow-up articles — but Google is the default. A site that
ranks well on Google usually also ranks well on Bing
(similar ranking factors).

## Google Search Console — the free tool

**Google Search Console (GSC)** is the free tool every
Google SEO needs. Verify your domain, then use it daily.

### Setup

1. Go to <https://search.google.com/search-console>.
2. Add a property — either **URL prefix** (verify via HTML
   file, DNS record, or Google Analytics) or **Domain**
   (verify via DNS TXT record).
3. Once verified, GSC starts collecting data within 24-72
   hours.

### Daily / weekly workflow

1. **Performance** → check top queries and pages. Look for
   pages with high impressions but low CTR — they need a
   better title and meta description.
2. **Coverage** → check the **Excluded** tab. Errors are
   pages that failed to index; warnings are pages with
   issues.
3. **URL Inspection** → paste a URL to see exactly how
   Google renders it, whether it's indexed, and any issues.
4. **Sitemaps** → submit new sitemaps; check status of
   existing ones.
5. **Enhancements** → if you have structured data, check
   the per-type reports (Articles, FAQ, Products, etc.).
6. **Links** → see what external sites link to you.
7. **Manual Actions** → red banner if Google has penalized
   your site. Read each carefully and fix.

### Reading the Performance report

The Performance report shows:

- **Total clicks** — how many times your page was clicked
  from Google Search.
- **Total impressions** — how many times your page
  appeared in Google Search.
- **Average CTR** — clicks / impressions. Benchmarks:
  - Position 1: ~30% CTR
  - Position 2-3: ~15%
  - Position 4-10: ~5%
  - Position 11+: < 2%
- **Average position** — your average rank.

Filter by:

- **Query** — what users searched.
- **Page** — which of your pages ranked.
- **Country** — geography.
- **Device** — desktop / mobile / tablet.
- **Date** — last 7 / 28 / 90 days / 16 months.

## Google's ranking factors in 2026

Google's algorithm has hundreds of signals. The major buckets:

### Content quality — E-E-A-T

**E-E-A-T** (Experience, Expertise, Authoritativeness,
Trustworthiness) is Google's framework for content quality.

| Signal | What it means |
| --- | --- |
| **Experience** | First-hand experience with the topic. Have you done it? |
| **Expertise** | Domain knowledge. Are you qualified? |
| **Authoritativeness** | Industry / web recognition. Do other sources cite you? |
| **Trustworthiness** | Accuracy, transparency, security. Can users trust you? |

For YMYL (Your Money or Your Life) topics — health, finance,
legal, safety — E-E-A-T is enforced more strictly. A medical
article by an unverified author may rank poorly even if
factually correct.

### Helpful Content

Google's **Helpful Content Update (HCU)** launched in 2022
and has rolled out several iterations since. It targets
"content written for search engines rather than people" —
content that:

- Aggregates other sources without adding value.
- Targets many keywords without depth on any.
- Has no clear point of view.
- Doesn't demonstrate first-hand experience.

The fix: write content for humans first. Use SEO as a guide,
not the goal.

### Core Web Vitals

Google's user-experience signals:

- **LCP (Largest Contentful Paint)** — < 2.5s for "Good".
- **INP (Interaction to Next Paint)** — < 200ms.
- **CLS (Cumulative Layout Shift)** — < 0.1.

Measure via:

- **Lighthouse** (Chrome DevTools → Lighthouse tab).
- **PageSpeed Insights** (<https://pagespeed.web.dev/>).
- **Chrome User Experience Report (CrUX)** — real-user data,
  integrated into GSC under Experience.

### Structured data (Schema.org / JSON-LD)

Google uses structured data to enable rich results. Without
structured data, your page appears as a blue link. With:

| Type | Rich result |
| --- | --- |
| `Article` | Top Stories carousel, article card. |
| `FAQPage` | Expandable FAQ accordion. |
| `HowTo` | Step-by-step card. |
| `Product` | Price, availability, rating. |
| `Recipe` | Image, rating, cook time. |
| `BreadcrumbList` | Breadcrumb in SERP. |
| `Organization` | Knowledge panel. |
| `LocalBusiness` | Map + hours + reviews. |

Validate with <https://search.google.com/test/rich-results>.

### Mobile-first

Since 2018, Google indexes the **mobile version** of your
page. If mobile is broken, desktop doesn't matter.

Check mobile-friendliness:

- **GSC → Experience → Mobile Usability** — Google
  notifies about mobile issues here.
- **Lighthouse** with mobile emulation.
- **Chrome DevTools** mobile emulator.

### HTTPS

Required since 2014. Free certificates via Let's Encrypt.
Mixed content (HTTPS page loading HTTP subresources) hurts.

### Page speed

Core Web Vitals are one part. Other speed signals:

- **TTFB (Time to First Byte)** — < 800ms for "Good".
- **FCP (First Contentful Paint)** — < 1.8s.
- **TBT (Total Blocking Time)** — < 200ms.

### On-page SEO

- **Title tag** — `<title>` — 50-60 chars, primary keyword.
- **Meta description** — 150-160 chars, call to action.
- **H1** — one per page, includes primary keyword.
- **URL** — short, descriptive, kebab-case.
- **Internal links** — every page linked from at least one
  other page on the site.
- **Image alt text** — descriptive, includes keyword when
  natural.

### Backlinks

The #1 off-page factor. Quality matters more than quantity.
A single link from a top-tier source (NYT, Wikipedia, a
top-3 industry site) outweighs 10,000 low-quality links.

## AI Overviews (formerly SGE)

In May 2025, Google rebranded **Search Generative Experience
(SGE)** to **AI Overviews**. AI-generated summaries now
appear at the top of many search results, with citations.

What this means for SEO:

- **Clicks shift down.** Users get answers from AI
  Overviews and may not click through to your page.
- **Citations are still visible.** Being cited in an AI
  Overview drives brand awareness and clicks (lower CTR
  but higher quality).
- **Long-form first-hand content wins.** AI Overviews
  cite sources with original research, expert commentary,
  or unique data.

The fix: write content that AI Overviews want to cite —
content with first-hand experience, original data, clear
expertise.

## Local SEO

For local businesses:

- **Google Business Profile** — claim at
  <https://business.google.com/>.
- **NAP consistency** — Name, Address, Phone consistent
  across all web listings.
- **Reviews** — quantity + recency + response.
- **Local backlinks** — local press, local directories,
  sponsorships.

## Google penalties

Google can penalize your site manually or algorithmically.

| Type | How to detect | How to fix |
| --- | --- | --- |
| **Manual action** | GSC → Manual Actions | Read the description, fix, request reconsideration. |
| **Helpful content demotion** | Site-wide traffic drop with no obvious cause | Audit content for first-hand experience + value. |
| **Link spam** | GSC → Manual Actions → Unnatural links | Disavow bad links; request removal. |
| **Cloaking / sneaky redirects** | GSC → Manual Actions | Remove cloaking; serve same content to bots and users. |
| **Thin content** | Coverage → "Crawled, currently not indexed" | Add value or remove. |

## Quick Google SEO checklist

A 1-hour checklist for a small site:

- [ ] Domain verified in Google Search Console.
- [ ] Sitemap submitted; status OK.
- [ ] All pages return 200, no 404s.
- [ ] Every page has unique `<title>` and `<meta name="description">`.
- [ ] HTTPS enforced (HTTP → 301 to HTTPS).
- [ ] Core Web Vitals all "Good" on mobile + desktop.
- [ ] Homepage has at least one `Organization` JSON-LD.
- [ ] Article pages have `Article` JSON-LD.
- [ ] Internal linking: every page has ≥ 1 internal link.
- [ ] Mobile usability OK in GSC.
- [ ] No manual actions.
- [ ] 3+ quality backlinks from external sources.

## What's next?

- **3-bing-indexnow** — Bing Webmaster Tools + the
  IndexNow protocol.
- **4-yahoo** — Yahoo Search.
- **5-duckduckgo** — DuckDuckGo SEO.
- **6-baidu** — Baidu SEO.
- **7-shenma** — Shenma (mobile).

## Source & Official Resources

- **Google Search Central:** <https://developers.google.com/search>
- **Search Console:** <https://search.google.com/search-console>
- **Rich Results Test:** <https://search.google.com/test/rich-results>
- **PageSpeed Insights:** <https://pagespeed.web.dev/>
- **Lighthouse:** <https://developer.chrome.com/docs/lighthouse/overview>
- **Schema.org:** <https://schema.org/>