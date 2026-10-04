---
x-title: What is DA? A Plain-English Guide to Moz's Domain Authority (and Ahrefs's DR)
x-desc: >-
  DA (Domain Authority) is Moz's third-party trust score for websites,
  scored 0 to 100. Ahrefs's similar score is called DR (Domain Rating).
  This page explains both in plain words, addresses the most common
  beginner question ("is DA from Google?"), and walks you through looking
  one up without an account.
x-sidebar: What is DA?
x-keywords: da, domain authority, moz da, dr, domain rating, ahrefs dr, link authority, third-party seo metrics, beginner guide
x-json-ld:
  '@context': https://schema.org
  '@graph':
    - '@type': TechArticle
      headline: 'What is DA — Moz Domain Authority and Ahrefs DR explained'
      inLanguage: 'en'
      about: 'Domain Authority and Domain Rating explained simply'
---

# What is DA? A Plain-English Guide to Moz's Domain Authority (and Ahrefs's DR)

Let's start with the question you probably typed into a search engine to land here:

**"Is DA from Google?"**

The answer is no. DA is **not** Google's score. It is not Bing's score, not Baidu's, not any search engine's score. DA is made by a company called [Moz](https://moz.com/), and it has been around since the mid-2000s. Ahrefs, a different company, makes a similar score called DR.

If you wanted to know what Google thinks of your site's authority, that is a separate question — and Google does not publish an authority score at all. (Google used to publish something called [PageRank](https://en.wikipedia.org/wiki/PageRank), which is the grandparent of all these scores, but they retired the public PageRank bar in 2016.) The closest thing Google gives you is **[Google Search Console](https://search.google.com/search-console)**, which shows you how Google indexes your site, what queries bring you traffic, and whether you have received any manual actions — but it does not give you a "DA" number.

So when you hear someone say "my DA is 35," they mean Moz's number for their site, not Google's. Keep that distinction in mind and the rest of this article falls into place.

## The three-second version

If you only read one paragraph, read this one.

**DA (Domain Authority) and DR (Domain Rating) are third-party trust scores made by SEO tool companies.** They run from 0 to 100. Higher is better. They are useful for comparing one site to another within the same tool, but they are not direct ranking factors — Google does not use DA or DR when deciding where to rank your page. They are rough proxies built from each site's backlink profile.

That is it. The rest of this page goes through each piece in plain words.

## What DA actually is, in plain words

DA stands for **Domain Authority**. It is a number from 0 to 100 that [Moz](https://moz.com/) gives to every website it knows about. Moz came up with the idea around 2005, when the company was still called "SEOmoz." It is the original link-authority score — most other scores in this space are descendants of it.

When Moz calculates your DA, it looks at two main things:

- **How many different websites link to yours.** A link from `cnn.com` and a link from `mycousinsblog.com` both count, but they count as **two different linking domains**, not as two links. So 100 links from one site is worth less than 100 links from 100 different sites.
- **How authoritative are the sites that link to you.** If the sites linking to you have high DA themselves, that boosts your DA more than links from low-DA sites. A single link from the BBC is worth a thousand links from random blogs.

Moz also folds in a few smaller signals — how natural your link pattern looks, whether your site has spammy signals — but the bulk of DA is just "how many sites link to you, and how good are they."

Most real websites sit somewhere between DA 10 and DA 70. New sites start near 0. Established brand-name sites tend to be in the 70 to 90 range. A DA of 100 is reserved for sites like google.com or facebook.com — sites that basically every other site on the web already links to.

## What DR is, and how it compares to DA

DR stands for **Domain Rating**. [Ahrefs](https://ahrefs.com/) launched it a few years after DA. It is the same general idea — a 0 to 100 score that says "how strong is this site's backlink profile" — but with a different recipe.

The biggest practical difference is that **DR only counts dofollow links**. A "dofollow" link is the default kind — when one website links to another and does not add any special markup, search engines follow it as a vote of support. The opposite is a **nofollow** link, which tells search engines "do not count this as a vote." DR ignores nofollow links entirely. DA gives them partial credit.

DR also stays narrower in what it looks at — just how many dofollow referring domains you have, and the DR of those referring domains. It does not look at traffic. It does not look at anchor text (the clickable words inside the link). It does not blend in any extra signals. That makes DR a "purer" link-graph metric than DA.

In practice, the two scores tend to land in the same ballpark for any given site, but they will not match exactly. A site that has been around for a long time and gets links from well-known places will probably score high on both. A site with an unusual link profile — say, mostly forum signatures or mostly nofollow press mentions — might score very differently between the two tools.

## How the 0-to-100 scale works

Both DA and DR use a **logarithmic** scale. "Logarithmic" sounds like jargon, but the practical meaning is simple: **each step up is harder than the last**.

If you have ever heard of the Richter scale for earthquakes, you have already met a logarithmic scale. A magnitude 5 earthquake is not 5 times bigger than a magnitude 1 earthquake — it is about 100,000 times bigger. Each step is bigger than the one before. The Richter scale is logarithmic.

DA and DR work the same way:

- Going from DA 10 to DA 20 — achievable in a few months with normal backlink building.
- Going from DA 30 to DA 40 — noticeably harder.
- Going from DA 50 to DA 60 — harder still.
- Going from DA 70 to DA 80 — very hard.
- Going from DA 80 to DA 90 — elite tier, only sites with sustained mass coverage reach this.

So when someone says "we got our DR from 12 to 35 in six months," that is a meaningful gain — a big swing across the lower-to-mid range. When someone says "we got our DR from 78 to 82 in six months," that is actually a much bigger accomplishment, even though the number itself only changed by 4. The top of the scale moves in bigger steps than the bottom.

## Why the two numbers don't match

If you check the same site on Moz and on Ahrefs, you will likely get two different numbers. There are two reasons.

**They see different parts of the web.** Moz has its own crawler — the database is called Mozscape, and the crawler itself is Rogerbot. Ahrefs has its own crawler too, called AhrefsBot. Two different crawlers, two different views. A site one crawler saw and the other did not will only show up on one tool. A link one crawler found and the other did not will only count on one tool.

**They use different formulas.** DA blends in some extra signals beyond raw links — things like site-wide authority, link pattern quality. DR stays closer to pure link counting. So even if both tools saw exactly the same set of links, the resulting scores would not equal, because the math is different.

The practical takeaway is simple: **DA and DR are useful for comparing sites within that tool, not across tools.** "My DR is higher than my competitor's" is a useful comparison. "My DA is 35 and theirs is 50, so I rank lower" is not a valid inference.

## How to look up DA or DR for any site

This is the practical part. There are four tools worth knowing, in order of how easy they are to use.

### Ahrefs Website Authority Checker — no login, just a human check

The fastest, no-login way to get a DR number is the **[Ahrefs Website Authority Checker](https://ahrefs.com/zh/website-authority-checker/)**. It only gives you DR (Ahrefs makes DR, not DA), but it is the quickest lookup and it costs nothing.

Here is what you do:

1. Open [ahrefs.com/zh/website-authority-checker](https://ahrefs.com/zh/website-authority-checker/) in your browser.
2. The page asks you to complete a "human verification" — the usual "I am not a robot" checkbox. Click through it.
3. Type a domain like `example.com` into the input box.
4. Hit enter.
5. You will see a DR number for the domain, plus a few related metrics — how many sites link to it, how the link count has trended over time, top countries linking to it, and so on.

No account. No credit card. No email. The `/zh/` part of the URL gives you a Chinese-language UI, which can be more comfortable for Chinese-speaking users. If you prefer English, just remove the `/zh/` and visit the page at the bare root URL.

This is the recommended first stop for almost everyone — it takes about a minute and gives you a useful number.

### Moz Domain Analysis — login required, gives you DA

Moz, who invented DA, does not have a free anonymous lookup. To see DA, you need a Moz account.

The page to use is **[Moz Domain Analysis](https://moz.com/domain-analysis)**. Free Moz accounts get a small number of lookups per month (last we knew, around 10 per month). Paid Moz Pro accounts get unlimited lookups plus full access to Moz's backlink database.

If you already have a Moz account — free or paid — log in and check. If you do not have one and just want the number, the Ahrefs checker above will give you DR for free. DA and DR are similar enough that DR alone is enough for most purposes.

### Semrush Authority Score — login required, third player

If you already pay for Semrush, their competing metric is **[Semrush Authority Score](https://www.semrush.com/analytics/overview/)**, also 0 to 100, blended from backlinks plus some additional signals. Semrush does not give anonymous lookups either — you need a free trial or a paid account. If you are already paying for Semrush, it is worth using Authority Score as a second opinion alongside Moz and Ahrefs.

### Majestic Trust Flow and Citation Flow — partial free tier

[Majestic](https://majestic.com/) is older than both Moz and Ahrefs. Their two scores are **Trust Flow** (link quality) and **Citation Flow** (link quantity), each 0 to 100. They predate DA and DR by years. Majestic has a [free public Site Explorer](https://majestic.com/reports/site-explorer) but the depth is limited — full lookups require login.

## What the score actually means (and what it does not)

This is the part most guides skip, and it is the part that matters most.

DA and DR are useful for **relative comparison**, not as an absolute judgment. A few examples of useful and useless interpretations.

### Useful interpretations

- "My DR went from 12 to 35 over six months." This means your backlink profile has grown substantially. Good signal.
- "My competitor has DR 65, mine is DR 30." You have a meaningful link gap to close before you compete on link-graph terms. Plan accordingly.
- "My DR is 70." A reasonable filter for backlink marketplaces — most "DR 50+" link sellers are pitching sites around this tier.

### Useless interpretations

- "My DA is 35, so my pages will rank highly." No. DA does not tell you whether your page answers the query, how fast it loads, whether it is mobile-friendly, or whether Google thinks it is trustworthy. DA is one input among many.
- "I should buy cheap backlinks to boost my DR." Buying low-quality links to game DR is usually counterproductive. Google penalizes obvious link buying. And even when it works, it does not move the needle as much as you would hope — DR weights high-DR links much more heavily than low-DR ones.
- "DA 30 plus DR 50 is the same as DA 50 plus DR 30." They are not. Each tool measures a slightly different thing, and the gap tells you about the link graph, not about ranking.

## Common confusions

A few things that trip people up. None of these are deal-breakers — just worth knowing.

**Your score can move without you doing anything.** Both Moz and Ahrefs update their link indexes on rolling schedules. A site can shift plus or minus 2 to 5 DR points in a week without anyone building or losing a single link. Do not panic over small fluctuations.

**Cached scores lie.** Some sites embed a "DR / DA" badge on their homepage that has not been updated in months. Always check the timestamp on the underlying metric, or just look it up fresh.

**Spam Score is a separate Moz metric.** Moz reports a [Spam Score](https://moz.com/learn/seo/spam-score) alongside DA — a separate 0 to 100 score that estimates whether a domain looks spammy. A high DA plus a high Spam Score is a red flag — it usually means the DA was inflated by low-quality links. Use it when judging a domain, not as an afterthought.

**Nofollow versus dofollow matters.** DR ignores nofollow links entirely. DA gives them partial credit. If your backlink profile is mostly nofollow (a bunch of forum profile links, for example), DR will look weak while DA may look healthy. Both views are useful.

**It is the root domain that scores, not the subdomain.** DA and DR score root domains. A strong blog on `blog.example.com` contributes to `example.com`'s score, not `blog.example.com`'s own score. If you have content on a subdomain, the credit goes to the parent.

**Moz's index is not always fresh.** Moz's crawler is slower than Ahrefs's. If Moz has not crawled your links recently, your DA might lag the truth by weeks. DR (from Ahrefs) tends to be more up-to-date.

## A walk-through: checking a site

Let's say you want to look up the DR for `wikipedia.org`. Here is what you would actually do.

**Step 1.** Go to [ahrefs.com/zh/website-authority-checker](https://ahrefs.com/zh/website-authority-checker/) in your browser.

**Step 2.** Click the "I am not a robot" checkbox to pass the human verification. This usually takes one click.

**Step 3.** Type `wikipedia.org` into the input box and press enter.

**Step 4.** You will see Wikipedia's DR — somewhere in the 90s, since Wikipedia is one of the most-linked sites on the internet — plus a few related numbers: how many sites link to it, how the link count has trended, the top countries linking to it, and so on.

**Step 5.** That is your DR. Done in under a minute, no account needed.

If you also want DA specifically, you would then go to [Moz Domain Analysis](https://moz.com/domain-analysis), sign in with a Moz account, type the same domain, and see Wikipedia's DA. Wikipedia's DA is also very high (90 plus), but probably slightly different from its DR — because of the index and formula differences covered above.

That is the whole lookup. For most purposes, DR alone is enough. DA adds information if you already have a Moz subscription.

## Comparison at a glance

| Tool | Metric | Score range | Login? | Where to check |
| --- | --- | --- | --- | --- |
| Moz | DA (Domain Authority) | 0–100 | Yes — free or paid account | [Moz Domain Analysis](https://moz.com/domain-analysis) |
| Ahrefs | DR (Domain Rating) | 0–100 | **No** — just a human check | [Ahrefs Website Authority Checker](https://ahrefs.com/zh/website-authority-checker/) |
| Semrush | Authority Score | 0–100 | Yes — free trial or paid | [Semrush Analytics Overview](https://www.semrush.com/analytics/overview/) |
| Majestic | Trust Flow / Citation Flow | 0–100 each | Partial — limited free tier | [Majestic Site Explorer](https://majestic.com/reports/site-explorer) |

## Where to go from here

DA and DR are useful as a quick read on a site's authority — they are not the goal itself. The actual ranking work happens at the search-engine level. If you are optimizing for Google (the biggest engine by far), the next thing to read is [3-google-seo](https://x-cmd.com/seo/google-seo). Add the other engines as your audience requires.

For the official definitions, here are the source pages:

- [Moz's explanation of DA](https://moz.com/learn/seo/domain-authority)
- [Ahrefs's explanation of DR](https://ahrefs.com/blog/domain-rating/)
- [Moz's explanation of Spam Score](https://moz.com/learn/seo/spam-score)

The Wikipedia article on [PageRank](https://en.wikipedia.org/wiki/PageRank) is also worth a read — PageRank was Google's original link-based score from the late 1990s, and DA, DR, and every other authority metric in this space are spiritual descendants of it.