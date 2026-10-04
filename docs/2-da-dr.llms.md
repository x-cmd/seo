---
name: 2-da-dr
description: DA (Moz) vs DR (Ahrefs) — third-party SEO link-authority metrics, both 0–100 logarithmic, scores differ across tools. Fastest no-login query: ahrefs.com/zh/website-authority-checker/ (human verification only).
type: summary
---

# Core Content

core_features:
  - DA = Moz's Domain Authority metric (0–100 logarithmic)
  - DR = Ahrefs's Domain Rating metric (0–100 logarithmic)
  - Both are third-party link-graph signals — not direct ranking factors
  - Each tool uses its own link graph (Mozscape vs AhrefsBot index)
  - DA blends several signals; DR is closer to a pure link-graph measurement
  - Scores can move without your site changing (rolling index updates)
  - Useful for relative comparison within a tool, not absolute claims across tools
  - Free, no-login DR lookup at ahrefs.com/zh/website-authority-checker/

# Key Information

highlights:
  - Fastest no-login lookup: ahrefs.com/zh/website-authority-checker/ (human verification only, no account)
  - Moz Domain Analysis requires login: moz.com/domain-analysis
  - Semrush Authority Score — third player, login required
  - Majestic Trust Flow / Citation Flow — older metrics, partial free tier
  - Logarithmic scale: each step up is harder than the last
  - DR ignores nofollow / ugc / sponsored; DA gives them partial weight
  - Both score root domains, not subdomains
  - High DA + high Spam Score (Moz) often means low-quality link spam

# Use Cases

use_cases:
  - Quickly looking up a site's DR without signing up for Ahrefs
  - Comparing DA vs DR across a list of competitor domains
  - Screening backlink sellers by their domain metrics
  - Tracking your own DA / DR trend over months
  - Spotting spam-flagged domains via Moz Spam Score
  - Sanity-checking link graphs before buying placements

# Related Resources

official:
  website: https://x-cmd.com/seo
related:
  - name: Ahrefs Website Authority Checker (DR, no login)
    url: https://ahrefs.com/zh/website-authority-checker/
  - name: Moz Domain Analysis (DA, login)
    url: https://moz.com/domain-analysis
  - name: Semrush Authority Score
    url: https://www.semrush.com/analytics/overview/
  - name: Majestic Site Explorer
    url: https://majestic.com/reports/site-explorer
  - name: Moz's explanation of DA
    url: https://moz.com/learn/seo/domain-authority
  - name: Ahrefs's explanation of DR
    url: https://ahrefs.com/blog/domain-rating/

# Summary

DA (Moz) and DR (Ahrefs) are the two most-cited third-party metrics for SEO link authority. Both are scored 0–100 on a logarithmic scale; both move on rolling index updates so a site's score can shift without you changing anything; both are useful for **relative** comparison within each tool, not absolute claims across tools. They differ in input signals (DA blends several, DR is closer to a pure link graph) and in the underlying crawler (Mozscape vs AhrefsBot), so even on the same site the two scores don't equal. The fastest no-login lookup is Ahrefs's Website Authority Checker (one human verification, no account) — recommended first stop. Moz's Domain Analysis gives you DA plus Spam Score but requires login (free or paid). Semrush's Authority Score and Majestic's Trust Flow / Citation Flow are alternative perspectives, both with login or partial-free access. Third-party authority scores are useful diagnostics, not ranking levers — a high DR doesn't directly translate to ranking. Practical ranking work happens at the engine level (start with `3-google-seo` and add engines as your audience requires).