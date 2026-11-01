---
x-title: 世界の検索エンジン — 一枚の表で見るフィールドガイド
x-desc: >-
  このライブラリが扱うすべての検索エンジンを一箇所に —— どこを本国とするか、
  自前のインデックスを持つか、地元市場でどれほど大きいか、ユーザーはおよそ
  何人か、SEO の観点でいつ意味を持つか、そしてサイトがどうすればその結果に
  出るか。各行は詳説記事へリンクします。
x-sidebar: 検索エンジン一覧
x-keywords: 検索エンジン一覧, 国別検索エンジン, 自前インデックス, 市場シェア, naver, yandex, seznam, coccoc, baidu, 検索エンジン比較
x-json-ld:
  '@context': https://schema.org
  '@graph':
    - '@type': TechArticle
      headline: '世界の検索エンジン — 一枚の表で見るフィールドガイド'
      inLanguage: 'ja'
      about: '世界の検索エンジン比較：インデックスの帰属、地元シェア、ユーザー推計、SEO 上の意味と収録方法'
---

# 世界の検索エンジン — 一枚の表で見るフィールドガイド

このページはライブラリ全体の地図です。専用記事のある検索エンジンが
それぞれ一度ずつ現れ、それが何であるかを説明する五つの事実 —— 本国は
どこか、自前のインデックスを持つか、地元でどれほど大きいか、ユーザーは
およそどれだけか、サイトがその結果に現れるには何が必要か —— が添えられ
ます。各エンジン名は完全な記事へリンクします。

読み方について二つだけ。誤読のほとんどはこの二つの列で起きます：

**「インデックス」がこの表で最も予測力のある列です。** 自分でウェブを
クロールし自分で順位をつけるエンジン —— 自前インデックス —— は、独立した
受け入れ口として独自の登録と独自のランキング作業を要する本物の別目的地
です。*Bing* や *Google* と記されたエンジンは、別会社の結果を自社の
インターフェースで表示しています。上流のインデックスに届けば、そこに
届いたのと同じです。*メタ*検索はクエリを複数の他社へ転送し、返ってきた
結果を混ぜます。国規模以上で自前インデックスを持つエンジンはもはや
七つほどしかなく、表全体の形は「それが誰か」から決まっています。

**「シェア」と「ユーザー」は別のものを測ります。** シェアは
[StatCounter](https://gs.statcounter.com/search-engine-market-share)
の 2025 年月次平均による地元市場での検索シェアで、**送出参照**ベース ——
自社ページ内で質問に答えてしまうエンジンを過小評価します（最も顕著な
のは Naver。検索量ベースの見方は[韓国](https://x-cmd.com/seo/korea)の
記事にあります）。ユーザー数は定義の異なる複数の公開資料 —— アプリ MAU、
サイト訪問数、一日の検索回数推計 —— に由来するため、比較可能な統計では
なく規模の目安としてだけ読んでください。確かな公開数値のない枠は
「—」です。

## グローバルエンジン

| エンジン | 本国 | インデックス | シェア（2025） | ユーザー（推計） | 意味を持つとき | 収録されるには |
| --- | --- | --- | --- | --- | --- | --- |
| [Google](https://x-cmd.com/seo/google-seo) | 米国 | 自前 | 世界で約 89.9 % | 1 日数十億回の検索（第三者推計） | ほぼすべての市場で第一の入口 | [Search Console](https://search.google.com/search-console) + サイトマップ |
| [Bing](https://x-cmd.com/seo/bing-indexnow) | 米国 | 自前 | 世界で約 4.0 %；日本のデスクトップで 19.0 %、ドイツで 15.8 % | — | オフィスのデスクトップ層；一回の登録で衛星たちを賄う | [Bing Webmaster Tools](https://www.bing.com/webmasters) + [IndexNow](https://www.indexnow.org/) |
| [DuckDuckGo](https://x-cmd.com/seo/duckduckgo) | 米国 | 主に Bing | 世界で約 0.8 % | — | プライバシー志向の層；個別の手段は存在しない | Bing 経由でカバー |
| [Yahoo! Search](https://x-cmd.com/seo/yahoo) | 米国 | Bing | 世界で約 1.4 % | — | ポータル時代の層、やや高年齢、米国外にも | Bing 経由でカバー |
| [Ecosia](https://x-cmd.com/seo/western-europe) | ドイツ | Bing | ドイツで 1.1 % | — | プライバシー世論の風向計、目標ではない | Bing 経由でカバー |
| [Startpage](https://x-cmd.com/seo/western-europe) | オランダ | Google（プロキシ） | オランダで 1 % 未満 | — | 同上、Google の索引について | Google 経由でカバー |
| [Qwant](https://x-cmd.com/seo/western-europe) | フランス | 自前（小規模） | フランスで 0.9 % | — | EU データ主権の物語 | 大きな窓口なし；クローラが発見 |
| [MetaGer](https://x-cmd.com/seo/western-europe) | ドイツ | メタ検索 | ドイツで 0.5 % 未満 | — | 非営利のメタ検索、この群れで最も古い | 提出ものなし —— 他社へ直接問い合わせ |

## 国別エンジン

本国でグローバル勢に打ち勝つ、あるいは真剣に食い込むエンジンたち。
インデックス列が本領を発揮するのはここです。

| エンジン | 本国 | インデックス | シェア（2025） | ユーザー（推計） | 意味を持つとき | 収録されるには |
| --- | --- | --- | --- | --- | --- | --- |
| [Naver](https://x-cmd.com/seo/korea) | 韓国 | 自前 | 参照で 45.6 %、検索量で 62.9 % | アプリ MAU 約 4,690 万（2026 年 7 月、Mobile Index） | 韓国語・ローカル・ショッピングの検索 —— 韓国ウェブの正門 | [Naver Search Advisor](https://searchadvisor.naver.com/) + 自前のバーティカル内での存在 |
| [Daum](https://x-cmd.com/seo/korea)（Kakao 系） | 韓国 | 自前・縮小中 | 1.2 % | Daum アプリ MAU 約 630 万（2026 年 7 月） | KakaoTalk 内の `#` 検索として存続 | KakaoTalk のエコシステム、ウェブ登録ではない |
| [Yahoo! JAPAN](https://x-cmd.com/seo/japan) | 日本 | Google | 9.4 %（モバイル 12.2 %） | — | 二世代にわたる日本の携帯ユーザーの習慣；モバイルで最強 | Google 経由でカバー —— 独自インデックスなし |
| [Yahoo! 台湾](https://x-cmd.com/seo/taiwan) | 台湾 | Google | 13.3 %（デスクトップ 17.1 %） | — | 台湾デスクトップで粘る第二位 | Google 経由でカバー |
| [Yandex](https://x-cmd.com/seo/russia) | ロシア | 自前 | 73.2 % | — | ロシア語圏市場、それだけ | [Yandex.Webmaster](https://webmaster.yandex.com/) + IndexNow |
| [Seznam](https://x-cmd.com/seo/czech) | チェコ | 自前（2005 年〜） | 11.6 %（デスクトップ 14.1 %） | 月間訪問約 2.14 億（SimilarWeb、2025 年 4 月） | チェコ語検索；EU に残る唯一の国別インデックス | [Seznam Webmaster Tools](https://reporter.seznam.cz/wm/) + IndexNow |
| [Cốc Cốc](https://x-cmd.com/seo/vietnam) | ベトナム | 自前 | 4.4 %（2025 年末 5.3〜6.0 %） | — | ベトナム語検索と自社ブラウザ | robots.txt で `coccocbot` を許可 —— クロールで発見 |
| [Baidu](https://x-cmd.com/seo/baidu) | 中国 | 自前 | 中国語検索で支配的 | — | 中国語圏ウェブ | [Baidu 搜索资源平台](https://ziyuan.baidu.com/)（ICP 備案が多くの場合必要） |
| [神馬（Shenma）](https://x-cmd.com/seo/shenma) | 中国 | 自前 | モバイル前提、UC ブラウザ内 | — | 中国のモバイルユーザー；UC のインストール基盤 | Baidu エコシステム + UC ブラウザでの存在 |
| [搜狗（Sogou）](https://x-cmd.com/seo/sogou) | 中国 | 自前 | WeChat コンテンツの検索層 | — | WeChat の囲い込まれたコンテンツを検索 | [Sogou 站長平台](https://zhanzhang.sogou.com/) + WeChat での存在 |

## 検索エンジンではないが、クエリは同じように奪う

シェアの表は検索エンジンを経由した検索だけを数えます。いくつかの市場
では、検索エンジンを一度も通らない「調べもの」の割合が伸びており、
この行たちなしの地図は不完全です：

| 場 | どこで | 何に答えるか | リーチ（推計） | 詳説 |
| --- | --- | --- | --- | --- |
| TikTok 検索 | 世界中の若い層；[東南アジア](https://x-cmd.com/seo/southeast-asia)で最強 | 食べ物・旅行・商品・「買う価値があるか」—— 動画で答える | — | [東南アジア](https://x-cmd.com/seo/southeast-asia) |
| Shopee / Lazada / Tokopedia | 東南アジア | 購買意図を伴う商品検索 | — | [東南アジア](https://x-cmd.com/seo/southeast-asia) |
| Mercado Livre / Shopee BR | ブラジル | 同じことのポルトガル語版 | — | [ブラジル](https://x-cmd.com/seo/brazil) |
| KakaoTalk の `#` 検索 | 韓国 | チャット内で打たれたクエリ、Daum が回答 | KakaoTalk は韓国ユーザーの約 90 %+ に到達 | [韓国](https://x-cmd.com/seo/korea) |
| LINE | 日本・台湾 | サービス、公式アカウント、ローカルの意図 | — | [日本](https://x-cmd.com/seo/japan)、[台湾](https://x-cmd.com/seo/taiwan) |
| WhatsApp Business | ブラジル・インド | 検索トラフィックが最終的に conversion に至る受け皿 | ブラジルのネットユーザーの 90 %+ | [ブラジル](https://x-cmd.com/seo/brazil) |

## この表が内包する三つの事実

**自前インデックスのエンジンはもはや七つほどしかありません**：Google、
Bing、Yandex、Baidu、Naver、Seznam、Cốc Cốc（Qwant は小さいが本物）。
他のすべての行はその七つの上に築かれた製品です —— 「収録されるには」の
列が繰り返されるのはそのためで、正面の扉は七つしかないのです。

**ラッパーの家系は見た目より大きい。** Bing のインデックスは静かに
DuckDuckGo、Yahoo! Search、Ecosia に供給し、Google のは Yahoo! JAPAN、
Yahoo! 台湾、Startpage に供給しています。シェア 1 % の「小さい」エンジン
は、単に大きなインデックスが外に見せている一角にすぎないことがあります。

**IndexNow は七つの扉のうち三つを一度に開きます。** Bing、Yandex、
Seznam が受け入れるので、一つのエンドポイントに Google Search Console
を加えれば七つのうち四つをカバーし —— それを通じて表のラッパー行の
大半も同時に賄えます。

## 次に読むもの

ローカル市場が何が違うのかを知りたければ[地域市場の概観](https://x-cmd.com/seo/overview)から。
あるいは上の表から、あなたの読者に合う行を選んでください。表の背後の
仕組み —— クロール、インデックス、ランキング —— は
[SEO の基礎](https://x-cmd.com/seo/seo-basics)（英語）に、これらすべての
エンジンを横断してサイトを比べる指標は [DA / DR](https://x-cmd.com/seo/da)
にあります。

## 出典と公式資料

- **[StatCounter — Search Engine Market Share](https://gs.statcounter.com/search-engine-market-share)** —— シェア列の 2025 年参照平均。
- **[IndexNow](https://www.indexnow.org/)** —— 共通の即時送信プロトコル（Bing、Yandex、Seznam）。
- **[Google Search Console](https://search.google.com/search-console)**、**[Bing Webmaster Tools](https://www.bing.com/webmasters)**、**[Naver Search Advisor](https://searchadvisor.naver.com/)**、**[Yandex.Webmaster](https://webmaster.yandex.com/)**、**[Seznam Webmaster Tools](https://reporter.seznam.cz/wm/)**、**[Baidu 搜索资源平台](https://ziyuan.baidu.com/)**、**[Sogou 站長平台](https://zhanzhang.sogou.com/)** —— 七つの正面の扉。
