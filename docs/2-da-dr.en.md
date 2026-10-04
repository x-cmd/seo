---
x-title: DA vs DR — Moz Domain Authority, Ahrefs Domain Rating, and How to Query Them
x-desc: >-
  DA (Domain Authority, Moz) and DR (Domain Rating, Ahrefs) are the
  most cited third-party metrics for SEO link authority. Scores
  differ across tools because the standards differ — they are
  useful for relative comparison, not as absolute signals. Fastest
  query: Ahrefs Website Authority Checker — human verification only,
  no login required.
x-sidebar: DA / DR
x-keywords: domain authority, da, moz da, domain rating, dr, ahrefs dr, link authority, third-party seo metrics, moz, ahrefs
x-json-ld:
  '@context': https://schema.org
  '@graph':
    - '@type': TechArticle
      headline: 'DA vs DR — Moz Domain Authority vs Ahrefs Domain Rating'
      inLanguage: 'en'
      about: 'Domain Authority and Domain Rating SEO metrics'
---

# DA vs DR — Moz Domain Authority, Ahrefs Domain Rating, and How to Query Them

DA and DR show up everywhere in SEO conversations. A backlink
seller will claim a "DA 60" placement; a competitor analysis
blog will rank sites by DR; a Moz report will quote your
"Domain Authority" score. But DA and DR are **not** the same
thing, and the numbers don't compare directly. This page
explains what each is, why they differ, and the quickest way
to look one up without signing in for anything.

> **Quick read.** DA is Moz's metric. DR is Ahrefs's metric.
> Both are 0–100 on a logarithmic scale. Both can move without
> your site changing. Both are useful for **relative**
> comparison within each tool — not for absolute claims across
> tools. The fastest lookup with no login is
> [ahrefs.com/zh/website-authority-checker](https://ahrefs.com/zh/website-authority-checker/)
> — one human verification, no account.

## What DA is

**Domain Authority** is a Moz product, scored 0–100 on a
logarithmic scale (each step up is harder than the last).
It has been around since the early 2010s, predating most of
the modern third-party SEO toolkit. The score is computed
from:

- The number of unique root domains linking to you.
- The DA of those linking domains.
- A few secondary signals Moz weighs in (link pattern
  quality, site-level authority signals).

The "logarithmic" part is the bit that trips people up: a
DA 30 → DA 40 jump is not twice as hard as a DA 20 → DA 30.
A genuinely new site can hit DA 10–20 in a few months with
normal backlink acquisition; DA 70+ usually requires
sustained mass linking to a well-known domain.

## What DR is

**Domain Rating** is Ahrefs's equivalent, also 0–100
logarithmic. It launched a few years after DA. DR is
calculated from:

- The number of unique domains with at least one dofollow
  link to you.
- The DR of those linking domains.

That's it — DR ignores nofollow links, ignores anchor text,
ignores traffic, ignores almost everything except the link
graph itself. This makes DR a "purer" link-graph metric
than DA, and Ahrefs is happy to market it that way.

DR's logarithmic scale behaves similarly to DA: a DR 20 site
is much harder to beat than a DR 10 site. The two metrics
correlate strongly but not perfectly — a site can be DR 70
and DA 40, or vice versa, depending on which link graph each
tool sees.

## Why the numbers differ

DA and DR use **different link graphs**. Moz crawls the web
with its own crawler (Mozscape / Rogerbot) and has its own
index of the web. Ahrefs runs its own crawler (AhrefsBot)
and has its own, generally larger, index. The two indices
don't agree on what the web looks like — some sites one
crawler sees the other doesn't, some links one counts the
other doesn't.

The scoring formulas also differ. DA blends several signals
beyond raw links; DR is closer to a pure link-graph
measurement. So even if both tools saw the same set of
links, the resulting scores wouldn't equal.

The takeaway: **DA and DR are useful for relative comparison
within each tool, not for absolute claims across tools.**
"My DR went from 12 to 35 over six months" is a useful
statement. "My DA is 35, therefore I rank highly" is not.

## How to query quickly

If you just want to look up a domain's DA or DR without
committing to a subscription, here's the path of least
friction.

### Ahrefs — no login, just a human check

The **[Ahrefs Website Authority Checker](https://ahrefs.com/zh/website-authority-checker/)**
is the fastest path to a DR number. No account. No credit
card. You complete a human verification (the usual "I am not
a robot" prompt), paste a domain, hit enter, and you see DR
plus a few related metrics (number of referring domains,
backlinks trend, etc.).

The `/zh/` path gives the Chinese UI — useful for audiences
in CN / HK / TW. The English version sits at the same root
path with the locale stripped. Either works.

This is the recommended first stop if you're just curious
about a site's DR or want to sanity-check a backlink seller
before paying.

### Moz — login required

Moz doesn't have a fully anonymous lookup. Their
**[Domain Analysis](https://moz.com/domain-analysis)** page
gives you DA plus a few related metrics (linking root
domains, Spam Score, etc.), but only after you sign in. Free
Moz accounts get a small number of lookups per month; paid
Moz Pro accounts get unlimited lookups and full access to
the Mozscape link graph.

If you already have a Moz account (free or paid), this is
the path. If you don't have one and just want the number,
the Ahrefs checker above will do.

### Semrush — login required, third player

Semrush's competing metric is **Authority Score**, also 0–100
logarithmic, blended from backlinks and a few other signals.
Semrush's tools are behind a login (free trial or paid). If
you're already paying for Semrush, this gives you a third
data point alongside Moz and Ahrefs.

### Majestic — partial free tier

Majestic's **Trust Flow** (link quality) and **Citation
Flow** (link quantity) predate both DA and DR by years. They
give a quick read on a domain. Majestic requires login for
deep lookups but has a free public tier with limited depth.

## What these scores actually mean (and don't)

Third-party authority metrics are **relative signals**, not
direct ranking factors. None of Moz, Ahrefs, Semrush, or
Majestic can tell you whether your page will rank #1 for a
query — that's the search engine's job, and the search
engines don't publish their own authority metric.

Useful interpretations:

- "DR / DA went up over time" — generally good; your link
  profile is growing.
- "DR / DA is higher than a competitor's" — usually good; you
  have a head start in link-graph terms.
- "My DR is 70" — a useful rough number for backlink-seller
  screening.
- "DR = 50 means I rank well" — **false**. A high DR doesn't
  directly translate to ranking.

Useless interpretations:

- Trying to game your DR by buying cheap backlinks (often
  counterproductive — Google penalizes obvious link buying).
- Treating a DA 30 / DR 50 site as equivalent to a DA 50 /
  DR 30 site. They aren't.

## Common pitfalls worth flagging

- **Score moves without you doing anything.** Moz and Ahrefs
  update their indices on their own cadences — DR can shift
  ±2-5 points in a week without you changing a thing.
  Don't panic over small fluctuations.
- **Cached scores.** Some sites embed a "DA / DR" badge from
  months ago. Always check the timestamp on the underlying
  metric.
- **Spam Score.** Moz reports a Spam Score alongside DA —
  high Spam Score + high DA can indicate a domain that's
  been spammed into a high DA via low-quality links. Use it
  as a filter, not an afterthought.
- **Nofollow / ugc / sponsored links.** DR ignores these
  entirely. DA gives them partial weight. A backlink profile
  that's mostly nofollow (e.g., forum profiles) will look
  weak in DR even if it looks healthy in DA.
- **Subdomain vs root domain.** Both tools score root
  domains, not subdomains. A strong blog on
  `blog.example.com` contributes to `example.com`'s score,
  not its own.
- **Time decay.** DR is built from a "live" Ahrefs index;
  DA is built from a Mozscape snapshot. If Moz's last crawl
  was a while ago, your DA may not reflect links you've
  built recently.

## Comparison at a glance

| Tool | Metric | Scale | Login? | Where to check |
| --- | --- | --- | --- | --- |
| Moz | DA (Domain Authority) | 0–100 log | Yes (free / paid) | moz.com/domain-analysis |
| Ahrefs | DR (Domain Rating) | 0–100 log | **No** — human verification only | ahrefs.com/zh/website-authority-checker/ |
| Semrush | Authority Score | 0–100 log | Yes (free / paid) | semrush.com |
| Majestic | Trust Flow / Citation Flow | 0–100 each | Partial — limited free | majestic.com/reports/site-explorer |

## Quick lookup workflow

If you have a list of sites to screen (e.g., for backlink
outreach or competitor research):

1. Run them through the Ahrefs checker first — fastest, no
   signup. Note the DR.
2. If you have a Moz account, run the same list through
   Moz's Domain Analysis. Note the DA.
3. Compare DR vs DA — large gaps between the two (e.g.,
   DR 60 but DA 30) tell you which link graph each tool is
   seeing more of.
4. Trust Flow / Citation Flow from Majestic, if you want a
   third view.
5. Use the numbers to **rank your targets**, not to chase
   them. A DR 30 site in your niche is still reachable.

## Sources and tools

- **Ahrefs Website Authority Checker (DR, no login):**
  <https://ahrefs.com/zh/website-authority-checker/>
- **Moz Domain Analysis (DA, login required):**
  <https://moz.com/domain-analysis>
- **Semrush Authority Score:**
  <https://www.semrush.com/analytics/overview/>
- **Majestic Site Explorer:**
  <https://majestic.com/reports/site-explorer>
- **Moz's explanation of DA:**
  <https://moz.com/learn/seo/domain-authority>
- **Ahrefs's explanation of DR:**
  <https://ahrefs.com/blog/domain-rating/>

DA and DR are useful diagnostics, not ranking levers. The
practical work happens at the engine level — start with
`3-google-seo` for the biggest engine, then move on to the
others as your audience requires.