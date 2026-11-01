---
x-title: Search Engines in Vietnam — Cốc Cốc, Google and a Real Local Index
x-desc: >-
  How Vietnamese search works in 2026 — Google's dominance, Cốc Cốc as the rare
  example of a national-scale independent index, Vietnamese diacritics, and
  what an optimizer has to do in the Vietnamese market.
x-sidebar: Search engines in Vietnam
x-keywords: vietnam search engine, coccoc, coc coc browser, vietnamese seo, diacritics, coccocbot, google vietnam
x-json-ld:
  '@context': https://schema.org
  '@graph':
    - '@type': TechArticle
      headline: 'Search engines in Vietnam — Cốc Cốc and a real local index'
      inLanguage: 'en'
      about: 'Vietnamese search engine market share and Cốc Cốc SEO'
---

# Search Engines in Vietnam — Cốc Cốc, Google and a Real Local Index

Vietnam looks at first like another Google-only market — and mostly it
is. But it holds one of only a handful of genuinely independent national
search indexes left anywhere: **Cốc Cốc**, a Vietnamese company that
crawls the Vietnamese web with its own bot, ranks it with its own
signals, and ships it inside its own Chromium-based browser. If you
want to understand what a "local search engine" can still be in 2026,
this is one of the few live examples.

> **TL;DR.** 2025 referrals: Google 94.2%, Cốc Cốc 4.4%, Bing 0.7%,
> Yahoo! 0.5%. Google is the strategy. Cốc Cốc is the interesting part —
> an independent Vietnamese index with its own crawler
> (`coccocbot`), its own browser, and a share that has been *rising*
> (5.6% by late 2025). Vietnamese diacritics are the practical trap for
> content: keep them in the text, and do not assume an English page
> will ever surface.

## What is the market actually like?

Here is Vietnam's 2025 share, all devices, from
[StatCounter](https://gs.statcounter.com/search-engine-market-share/all/viet-nam)
monthly averages:

[![Vietnam search share 2025](https://x-cmd.com/draw?type=hbar&t=opendata&unit=%25&title=Vietnam%20search%20share%202025&labels=Google,CocCoc,Bing,Yahoo!,DuckDuckGo&values=94.2,4.4,0.7,0.5,0.1)](https://x-cmd.com/draw/explore?type=hbar&t=opendata&unit=%25&title=Vietnam%20search%20share%202025&labels=Google,CocCoc,Bing,Yahoo!,DuckDuckGo&values=94.2,4.4,0.7,0.5,0.1)

Google above 94%, and everything that remains is essentially Cốc Cốc.
Bing is unusually *small* here — 0.7% against a ~4% global average —
which is itself informative: where Windows defaults are not enough,
Bing does not travel on its own.

## Cốc Cốc — what an independent index still looks like

Cốc Cốc is the interesting object in this market, and worth
understanding even if you never optimize for it.

The company started as a Vietnamese browser maker — **Cốc Cốc
Browser**, a Chromium fork tuned for the Vietnamese web — and built a
search engine to go inside it. The engine is not a wrapper and not a
metasearch. It maintains **its own index of the Vietnamese web**,
crawled by its own bot (`coccocbot` / `coccocbot-web`), with ranking
signals tuned for Vietnamese.

That combination — a national-scale index plus the browser that ships
it — is nearly extinct. The short list of engines that crawl and rank
their own national web at scale runs: Google, Bing, Yandex, Baidu,
Naver, Seznam, and Cốc Cốc. Everyone else either licenses an index or
merges other people's results.

Cốc Cốc's share has also been moving the right way: roughly 3.5–4% for
years, then rising through 2025 to about 5.6% by the autumn. Its
strength is in the queries where being Vietnamese actually helps —
local services, Vietnamese-language e-commerce, and queries typed
without diacritics, where its handling of Vietnamese orthography is
more forgiving than Google's.

The engine's stated direction is AI-first search built on its own
Vietnamese corpus, and its public materials emphasize that owning a
national-scale index is what makes its AI answers grounded in
Vietnamese sources. That argument — an independent index as the
moat for a national AI-search product — is exactly the argument
Seznam makes in Czech and Naver makes in Korea.

## Vietnamese diacritics — the practical trap

Vietnamese is written with a Latin alphabet plus a heavy layer of
diacritics: **tiếng Việt** carries both tone marks and vowel marks, and
the difference between a marked and an unmarked word is often the
difference between two different words.

Two consequences for search:

**Type the query without diacritics and the engine has to guess.**
Vietnamese users frequently type `nha hang` rather than `nhà hàng`,
partly because keyboard entry of tone marks is slow. Google handles
this well but not perfectly; Cốc Cốc markets its handling of
unmarked Vietnamese as a specific strength. Either way: a page that
only ever spells its keywords with full diacritics may not match the
way half its audience actually types.

**Do not strip diacritics from URLs — or from content.** The content
should carry full, correct Vietnamese with all its marks. For URLs,
the safe convention is to transliterate to ASCII (`nha-hang-ha-noi`),
and make sure the CMS does it consistently. The mistake to avoid is
inconsistent encoding — the same word appearing marked in one place
and unmarked in another, in URLs that change between versions.

For an English-language site hoping to reach Vietnam: assume it will
not, organically. Vietnamese users search in Vietnamese, and a page
with no Vietnamese on it has nothing for the query to match. If the
market matters, the content has to be written Vietnamese, not
translated token by token.

## What to actually do

1. **Google, in Vietnamese.** The usual discipline — Search Console,
   sitemap, structured data, mobile-first performance — done with
   Vietnamese keywords and Vietnamese content. Mobile is the majority
   of Vietnamese traffic, so mobile performance leads.
2. **Keep full diacritics in content.** Write đúng chính tả — correct
   Vietnamese spelling, all marks in place — in titles, descriptions,
   body and alt text.
3. **ASCII-transliterate URLs**, consistently, via the CMS.
4. **Allow `coccocbot` in robots.txt** and let it crawl. There is no
   separate submission portal comparable to Search Console; the way
   in is to be crawlable. If Vietnamese traffic matters to you, the
   4–6% that Cốc Cốc holds is real traffic, and it costs you one line
   in a robots file.
5. **Do not spend on Bing** for Vietnam specifically. Its 0.7% there
   is covered by the Bing work you would do for other markets anyway.
6. **Local links and local listings.** Vietnamese directories and
   local media are the citation layer for local queries.

## Where to go from here

Vietnam pairs naturally with the
[Czech Republic](https://x-cmd.com/seo/czech) — Seznam is the other
surviving national-scale independent index in this chapter, and the
comparison shows what that shape of engine can and cannot hold against
Google. The [regional overview](https://x-cmd.com/seo/overview)
explains the measurement caveats behind every number on this page, and
[SEO Basics](https://x-cmd.com/seo/seo-basics) covers crawling and
indexing mechanics.

## Source & Official Resources

- **[StatCounter — Vietnam search engine market share](https://gs.statcounter.com/search-engine-market-share/all/viet-nam)** — the referral-based figures.
- **[Cốc Cốc](https://coccoc.com)** — the search engine and browser.
- **[Cốc Cốc — advertising](https://ads.coccoc.com)** — its ad platform and merchant tools.
- **[coccocbot — crawler documentation](https://bot.coccoc.com)** — the bot's user agents and robots handling.
- **[Google Search Console](https://search.google.com/search-console)** — the tool for the engine that matters most.
- **[Google Vietnam](https://www.google.com.vn)** — the local Google front end.
