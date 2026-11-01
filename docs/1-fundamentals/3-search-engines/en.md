---
x-title: Search Engines of the World — A One-Table Field Guide
x-desc: >-
  Every search engine this library covers, in one place — which country it
  belongs to, whether it runs its own index, how big it is at home, roughly
  how many users it has, when it matters for SEO, and how a site gets
  indexed in it. Each row links to the article that covers it in depth.
x-sidebar: Search engines at a glance
x-keywords: search engine list, all search engines, search engine by country, own index, market share, naver, yandex, seznam, coccoc, baidu, search engine comparison
x-json-ld:
  '@context': https://schema.org
  '@graph':
    - '@type': TechArticle
      headline: 'Search engines of the world — a one-table field guide'
      inLanguage: 'en'
      about: 'A comparison of the world''s search engines: index ownership, home-market share, user estimates, SEO relevance, and how to get indexed'
---

# Search Engines of the World — A One-Table Field Guide

This page is the map for the whole library. Every engine covered by a
dedicated article appears here once, with the five facts that explain
what it is: where it is at home, whether it runs its own index, how
big it is there, roughly how many people use it, and what it takes for
a site to appear in its results. Each engine name links to its full
article.

Two notes on reading the columns, because they are where most
misreadings happen:

**"Index" is the most predictive column on the page.** An engine that
crawls and ranks the web itself — own index — is a genuinely separate
destination that needs its own submission and its own ranking work.
An engine listed as *Bing* or *Google* serves another company's
results under its own interface: reach the upstream index and you have
already reached it. *Meta* engines forward the query to several others
and merge what comes back. There are only about seven own-index
engines left at national scale or larger, and the whole shape of the
table follows from who they are.

**"Share" and "Users" measure different things.** Share is the
engine's slice of searches in its home market on 2025 monthly averages
from [StatCounter](https://gs.statcounter.com/search-engine-market-share)
— an outbound-referral basis, which undercounts engines that answer
queries on their own pages (Naver most of all; see
[Korea](https://x-cmd.com/seo/korea) for the query-volume view). User
figures come from different published sources with different
definitions — app MAU, site visits, daily query estimates — so treat
them as order-of-magnitude context, not comparable statistics. Where
no solid published figure is at hand, the cell says "—".

## The global engines

| Engine | Home | Index | Share (2025) | Users (est.) | When it matters | How to get in |
| --- | --- | --- | --- | --- | --- | --- |
| [Google](https://x-cmd.com/seo/google-seo) | US | Own | ~89.9% worldwide | billions of queries a day (third-party estimates) | The first engine almost everywhere | [Search Console](https://search.google.com/search-console) + sitemap |
| [Bing](https://x-cmd.com/seo/bing-indexnow) | US | Own | ~4.0% worldwide; 19.0% of Japanese desktop, 15.8% of German desktop | — | Office-desktop audiences; one submission feeds its satellites | [Bing Webmaster Tools](https://www.bing.com/webmasters) + [IndexNow](https://www.indexnow.org/) |
| [DuckDuckGo](https://x-cmd.com/seo/duckduckgo) | US | Mostly Bing's | ~0.8% worldwide | — | Privacy-minded users; no separate action exists | Covered via Bing |
| [Yahoo! Search](https://x-cmd.com/seo/yahoo) | US | Bing's | ~1.4% worldwide | — | A portal audience, mostly older, outside the US too | Covered via Bing |
| [Ecosia](https://x-cmd.com/seo/western-europe) | Germany | Bing's | 1.1% in Germany | — | A weather vane for privacy sentiment, not a target | Covered via Bing |
| [Startpage](https://x-cmd.com/seo/western-europe) | Netherlands | Google's (proxied) | under 1% in NL | — | Same, for the Google index | Covered via Google |
| [Qwant](https://x-cmd.com/seo/western-europe) | France | Own (small) | 0.9% in France | — | The EU data-sovereignty story | No major portal; index finds sites by crawling |
| [MetaGer](https://x-cmd.com/seo/western-europe) | Germany | Meta-search | under 0.5% in Germany | — | A non-profit meta-search, oldest of the cluster | Nothing to submit — it queries others live |

## The national engines

These are the engines that beat, or seriously contest, the global ones
at home. This is where the own-index column does its work.

| Engine | Home | Index | Share (2025) | Users (est.) | When it matters | How to get in |
| --- | --- | --- | --- | --- | --- | --- |
| [Naver](https://x-cmd.com/seo/korea) | Korea | Own | 45.6% of referrals, 62.9% of queries | app MAU ≈ 46.9M (Jul 2026, Mobile Index) | Korean-language, local and shopping queries — the main entrance to the Korean web | [Naver Search Advisor](https://searchadvisor.naver.com/) + presence in its own verticals |
| [Daum](https://x-cmd.com/seo/korea) (Kakao) | Korea | Own, shrinking | 1.2% | Daum app MAU ≈ 6.3M (Jul 2026) | Lives on as the search inside KakaoTalk (`#`) | KakaoTalk ecosystem, not web submission |
| [Yahoo! JAPAN](https://x-cmd.com/seo/japan) | Japan | Google's | 9.4% (12.2% mobile) | — | The habit of two decades of Japanese phone users; strongest on mobile | Covered via Google — no separate index |
| [Yahoo! Taiwan](https://x-cmd.com/seo/taiwan) | Taiwan | Google's | 13.3% (17.1% desktop) | — | The persistent desktop second place in Taiwan | Covered via Google |
| [Yandex](https://x-cmd.com/seo/russia) | Russia | Own | 73.2% | — | The Russian-language market, full stop | [Yandex.Webmaster](https://webmaster.yandex.com/) + IndexNow |
| [Seznam](https://x-cmd.com/seo/czech) | Czechia | Own (since 2005) | 11.6% (14.1% desktop) | ≈ 214M visits/month (SimilarWeb, Apr 2025) | Czech-language search; the only EU national index left | [Seznam Webmaster Tools](https://reporter.seznam.cz/wm/) + IndexNow |
| [Cốc Cốc](https://x-cmd.com/seo/vietnam) | Vietnam | Own | 4.4% (5.3–6.0% in late 2025) | — | Vietnamese-language queries and its own browser | Allow `coccocbot` in robots.txt — it finds sites by crawling |
| [Baidu](https://x-cmd.com/seo/baidu) | China | Own | dominant in Chinese-language search | — | The Chinese-language web | [Baidu Search Resource Platform](https://ziyuan.baidu.com/) (ICP 备案 often required) |
| [Shenma](https://x-cmd.com/seo/shenma) | China | Own | mobile-first, inside UC Browser | — | Mobile Chinese users; UC's installed base | Baidu ecosystem + UC Browser presence |
| [Sogou](https://x-cmd.com/seo/sogou) | China | Own | the WeChat-content search layer | — | Searches inside WeChat's walled content | [Sogou webmaster platform](https://zhanzhang.sogou.com/) + WeChat presence |

## Not engines, but they take the queries anyway

A share table counts searches that went through a search engine. In
several markets a growing slice of looking-things-up never does, and
no SEO list is complete without them:

| Surface | Where | What it answers | Reach (est.) | Covered in |
| --- | --- | --- | --- | --- |
| TikTok search | Younger users, worldwide; strongest in [Southeast Asia](https://x-cmd.com/seo/southeast-asia) | food, travel, products, "is it worth it" — answered in video | — | [Southeast Asia](https://x-cmd.com/seo/southeast-asia) |
| Shopee / Lazada / Tokopedia | Southeast Asia | product queries with buying intent | — | [Southeast Asia](https://x-cmd.com/seo/southeast-asia) |
| Mercado Livre / Shopee BR | Brazil | the same, in Portuguese | — | [Brazil](https://x-cmd.com/seo/brazil) |
| KakaoTalk `#` search | Korea | queries typed inside chat, answered by Daum | KakaoTalk reaches ~90%+ of Korean users | [Korea](https://x-cmd.com/seo/korea) |
| LINE | Japan, Taiwan | services, official accounts, local intent | — | [Japan](https://x-cmd.com/seo/japan), [Taiwan](https://x-cmd.com/seo/taiwan) |
| WhatsApp Business | Brazil, India | the landing surface search traffic converts on | 90%+ of Brazilian internet users | [Brazil](https://x-cmd.com/seo/brazil) |

## Three facts this table encodes

**Only about seven own-index engines remain at scale**: Google, Bing,
Yandex, Baidu, Naver, Seznam and Cốc Cốc (Qwant's is small but real).
Every other row is a product built on one of those seven — which is
why "how to get in" repeats: there are only seven front doors.

**The wrapper families are bigger than they look.** Bing's index
quietly serves DuckDuckGo, Yahoo! Search, Ecosia and (with its own
ranking layer) Yahoo!'s portals in various markets; Google's serves
Yahoo! JAPAN, Yahoo! Taiwan and Startpage. A "small" engine with 1%
share may simply be the visible edge of a big index.

**IndexNow covers three of the seven doors at once.** Bing, Yandex
and Seznam all accept it, so one endpoint plus Google Search Console
covers four of the seven own-index engines — and through them, most
of the wrapper rows too.

## Where to go from here

Start with the [regional overview](https://x-cmd.com/seo/overview)
for how local markets differ, or pick the row above that matches your
audience. The mechanics behind the table — crawling, indexing,
ranking — are in [SEO Basics](https://x-cmd.com/seo/seo-basics), and
the link-authority metrics used to compare sites across all of these
engines are in [DA / DR](https://x-cmd.com/seo/da).

## Source & Official Resources

- **[StatCounter — search engine market share](https://gs.statcounter.com/search-engine-market-share)** — the 2025 referral averages in the Share column.
- **[IndexNow](https://www.indexnow.org/)** — the shared instant-submission protocol (Bing, Yandex, Seznam).
- **[Google Search Console](https://search.google.com/search-console)**, **[Bing Webmaster Tools](https://www.bing.com/webmasters)**, **[Naver Search Advisor](https://searchadvisor.naver.com/)**, **[Yandex.Webmaster](https://webmaster.yandex.com/)**, **[Seznam Webmaster Tools](https://reporter.seznam.cz/wm/)**, **[Baidu Search Resource Platform](https://ziyuan.baidu.com/)**, **[Sogou webmaster platform](https://zhanzhang.sogou.com/)** — the seven front doors.
