---
name: 2-da
description: What is DA (Domain Authority, Moz) — beginner's plain-English guide covering DR (Domain Rating, Ahrefs), why the numbers don't match, how to look either up without login, and Google's own score (Google does not publish one; the closest thing is Search Console).
type: summary
---

# Core Content

core_features:
  - DA = Moz's Domain Authority score (0–100 logarithmic)
  - DR = Ahrefs's Domain Rating score (0–100 logarithmic)
  - DA is NOT Google's score — it is made by Moz, not by any search engine
  - Google does not publish any authority score (PageRank bar retired 2016)
  - Google Search Console is the closest thing to "Google's view of your site"
  - Both DA and DR are third-party link-graph signals — not direct ranking factors
  - Each tool uses its own crawler (Mozscape/Rogerbot vs AhrefsBot)
  - DA blends several signals; DR only counts dofollow links
  - Logarithmic scale: each step up is harder than the last (like earthquake magnitude)

# Key Information

highlights:
  - Fastest no-login lookup: ahrefs.com/zh/website-authority-checker/ (human verification only)
  - Moz Domain Analysis requires login: moz.com/domain-analysis
  - Moz ≠ Mozilla (different companies — Mozilla makes Firefox; Moz makes SEO tools)
  - For Google's view of your site: Google Search Console (search.google.com/search-console)
  - Semrush Authority Score — third player, login required
  - Majestic Trust Flow / Citation Flow — older metrics, partial free tier
  - DR ignores nofollow / ugc / sponsored; DA gives them partial weight
  - Both score root domains, not subdomains
  - Scores can move ±2-5 points in a week without you changing anything

# Use Cases

use_cases:
  - Quickly looking up a site's DR without signing up for Ahrefs
  - Comparing DA vs DR across a list of competitor domains
  - Screening backlink sellers by their domain metrics
  - Tracking your own DA / DR trend over months
  - Spotting spam-flagged domains via Moz Spam Score
  - Sanity-checking link graphs before buying placements
  - Understanding "Google's view" via Google Search Console when you can't get a Google DA
  - Explaining DA / DR to non-SEO colleagues in plain words

# Related Resources

official:
  website: https://x-cmd.com/seo
related:
  - name: Ahrefs Website Authority Checker (DR, no login)
    url: https://ahrefs.com/zh/website-authority-checker/
  - name: Moz Domain Analysis (DA, login)
    url: https://moz.com/domain-analysis
  - name: Google Search Console (Google's view of your site)
    url: https://search.google.com/search-console
  - name: Semrush Authority Score
    url: https://www.semrush.com/analytics/overview/
  - name: Majestic Site Explorer
    url: https://majestic.com/reports/site-explorer
  - name: Moz's explanation of DA
    url: https://moz.com/learn/seo/domain-authority
  - name: Ahrefs's explanation of DR
    url: https://ahrefs.com/blog/domain-rating/
  - name: Wikipedia — PageRank
    url: https://en.wikipedia.org/wiki/PageRank

# Summary

DA (Moz) and DR (Ahrefs) are the two most-cited third-party metrics for SEO link authority, both scored 0–100 on a logarithmic scale. The most common beginner question — "is DA from Google?" — the answer is no: DA is Moz's score, not Google's. Google does not publish an authority score at all; Google's retired PageRank bar (2016) was the historical ancestor. The closest thing to "Google's view of your site" today is Google Search Console, which shows indexing status, queries, and manual actions — but no DA number. The fastest no-login DR lookup is ahrefs.com/zh/website-authority-checker/ (one human verification, no account). Moz's Domain Analysis gives you DA plus Spam Score but requires login (free tier is limited). DA and DR differ because they use different link graphs (Mozscape vs AhrefsBot) and different formulas; they are useful for comparing sites within each tool, not for absolute cross-tool claims. The logarithmic scale means each step up is harder than the last — like earthquake magnitude. Practical ranking work happens at the engine level; start with `3-google-seo` and add engines as your audience requires.