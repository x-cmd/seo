---
x-title: DA vs DR — Moz 域名权重 vs Ahrefs 域名评分，以及如何快速查询
x-desc: >-
  DA（Domain Authority，Moz）与 DR（Domain Rating，Ahrefs）是
  SEO 链接权重最常被引用的两个第三方指标。分数不一样是因为
  标准不一样——它们适合做相对对比，不能当成绝对排名信号。
  最快的无登录查询入口：Ahrefs 网站权重检查器，只需人机验证，
  无需账号。
x-sidebar: DA / DR
x-keywords: domain authority, da, moz da, domain rating, dr, ahrefs dr, 域名权重, 第三方 seo 指标, moz, ahrefs
x-json-ld:
  '@context': https://schema.org
  '@graph':
    - '@type': TechArticle
      headline: 'DA vs DR — Moz 域名权重 vs Ahrefs 域名评分'
      inLanguage: 'cn'
      about: '域名权重与域名评分指标'
---

# DA vs DR — Moz 域名权重 vs Ahrefs 域名评分，以及如何快速查询

DA 和 DR 在 SEO 圈里到处出现。卖外链的人会标"DA 60"的位；
做竞品分析的帖子会用 PR / 排名排站；Moz 的报告会告诉你
"Domain Authority" 分数。但 DA 和 DR **不是**一回事，两个
数字不能直接比较。这篇文章讲清它们各自是什么、为什么不同、
以及最省事的不登录查询方式。

> **速读。** DA 是 Moz 的指标，DR 是 Ahrefs 的指标。两者
> 都是 0–100 对数刻度，都可能在你没改站点的情况下波动，
> 都只适合在**各自工具内**做相对对比，不能跨工具下绝对
> 结论。最快的无登录查询入口是
> [ahrefs.com/zh/website-authority-checker](https://ahrefs.com/zh/website-authority-checker/)——
> 只需人机验证，无账号。

## DA 是什么

**Domain Authority（域名权重）** 是 Moz 的产品，0–100 对数
刻度（每往上一级都比上一级更难），从 2010 年代初就有了，
比现在大多数第三方 SEO 工具都早。分数由这几个东西算出：

- 指向你的唯一根域名数。
- 这些根域名自己的 DA。
- Moz 加的几个次要信号（链接模式质量、站点层面的权威
  信号）。

"对数刻度"这一点最容易把人坑：DA 从 30 涨到 40 比从 20
涨到 30 难不止两倍。新站正常积累反向链接，几个月可以爬到
10–20；70+ 通常需要长期大量外链指向一个有知名度的域名。

## DR 是什么

**Domain Rating（域名评分）** 是 Ahrefs 的对应指标，同样
0–100 对数。DR 比 DA 晚几年上线，只看：

- 至少有一条 dofollow 反向链接指向你的唯一域名数。
- 这些根域名自己的 DR。

没了——DR 忽略 nofollow、忽略锚文本、忽略流量，几乎只看
链接图本身。这让 DR 比 DA 更"纯"，是纯链接图指标，Ahrefs
也乐意这么宣传。

DR 的对数刻度跟 DA 类似：DR 20 比 DR 10 难打得多。两个
指标强相关但不完全一致——一个站可能是 DR 70 / DA 40，
反过来也常见，看各自链接图能看到哪些。

## 为什么数字不一样

DA 和 DR 用的是**不同的链接图**。Moz 用自己的爬虫
（Mozscape / Rogerbot），Ahrefs 用自己的爬虫（AhrefsBot）。
两边索引都不一致——一个爬虫看到的站另一个未必看到；
一边计入数一边的链接另一边可能不数。

打分公式也不同。DA 混合了好几个信号，不只是链接数；DR
更接近纯链接图测量。所以即便两边看到相同的链接集，给出的
分数也不会相等。

结论：**DA 和 DR 适合在各自工具内做相对对比，不适合跨
工具下绝对结论。**"我的 DR 半年从 12 涨到 35"是个有用
的陈述；"我的 DA 是 35 所以我排名高"不是。

## 怎么快速查

如果只是想查一个域名的 DA 或 DR，不想为这一次查询开个
付费账号，路径如下。

### Ahrefs——不登录，只需人机验证

**[Ahrefs 网站权重检查器](https://ahrefs.com/zh/website-authority-checker/)**
是查 DR 最省事的方法。无需账号、无需信用卡。做一下
人机验证（"我不是机器人"那种），贴入域名，回车，就能
看到 DR 加上几个相关指标（引用域名数、外链趋势等）。

`/zh/` 路径给中文界面，对 CN / HK / TW 受众更顺手。去掉
`/zh/` 是英文版。两个都行。

如果只是想看一眼 DR，或者付钱买外链前先核一下卖家的数据，
这里就是推荐的第一站。

### Moz——需要登录

Moz 没有完全免登录的查询入口。
**[Domain Analysis](https://moz.com/domain-analysis)** 页
面给你 DA 加几个相关指标（链接根域名数、Spam Score 等），
但要先登录。免费 Moz 账号每月只有少量查询次数；付费 Moz Pro
账号不限次且能完整访问 Mozscape 链接图。

如果你已经有 Moz 账号（免费或付费），就走这里。如果还没
账号、只是想看一眼数字，用上面的 Ahrefs 检查器就够了。

### Semrush——也需要登录，第三方参照

Semrush 的对应指标是 **Authority Score**，也是 0–100 对数，
混合外链信号加几个其他信号。Semrush 的工具也要登录
（免费试用或付费）。如果你已经在用 Semrush，能拿到一个
跟 Moz / Ahrefs 并列的第三参照点。

### Majestic——部分免费

Majestic 的 **Trust Flow**（链接质量）和 **Citation Flow**
（链接数量）比 DA 和 DR 都早。这俩配合起来能快速给一个站
打分。Majestic 的深度查询要登录，但有免费公共版深度有限。

## 这些分数实际意味着什么（又不能意味着什么）

第三方权重指标是**相对信号**，不是直接的排名因子。Moz、
Ahrefs、Semrush、Majestic 都无法告诉你你的页面会不会
排第 1——那是搜索引擎的事，而搜索引擎没公布自己的权重
指标。

有意义的解读：

- "DR / DA 在涨"——通常好，链接图在涨。
- "我的 DR / DA 比竞品高"——通常好，链接图有先发优势。
- "我的 DR 是 70"——筛选卖外链的粗略门槛。
- "DR = 50 所以我排名好"——**错**。DR 高不直接换排名。

没意义的解读：

- 想靠买廉价外链把 DR 推上去（往往适得其反——Google 会
  惩罚明显的链接买卖）。

- 把"DA 30 / DR 50"和"DA 50 / DR 30"当成一回事。它们不是。

## 几个常见的坑

- **分数不动也会动。** 两家都在滚动更新自己的索引——DR
  一周可能波动 ±2-5 分，你啥都没改。小波动不用慌。
- **缓存的分数。** 一些站嵌入的"DA / DR"徽章是好几个月
  前的快照。看一眼时间戳。
- **Spam Score。** Moz 在 DA 旁边会报一个 Spam Score——
  高 Spam + 高 DA 通常意味着这个域名是被低质量链接推上去
  的。要把它当过滤项，不是事后补的。
- **Nofollow / ugc / sponsored 链接。** DR 完全忽略这些；
  DA 给部分权重。一个全是 nofollow 的链接档案（比如论坛
  profile），DR 会显得很低，DA 看起来还行。
- **子域名 vs 根域名。** 两个工具都打根域名，不打子域名。
  `blog.example.com` 上的强链接贡献给 `example.com`，不贡献
  给 `blog.example.com` 自己。
- **时间衰减。** DR 来自 Ahrefs 的"实时"索引；DA 来自
  Mozscape 的快照。如果 Moz 的上一次爬取过去好久了，你的
  DA 可能没反映出你最近建的链接。

## 一览表

| 工具 | 指标 | 刻度 | 要登录？ | 查询入口 |
| --- | --- | --- | --- | --- |
| Moz | DA（Domain Authority） | 0–100 对数 | 是（免费 / 付费） | moz.com/domain-analysis |
| Ahrefs | DR（Domain Rating） | 0–100 对数 | **否**——只人机验证 | ahrefs.com/zh/website-authority-checker/ |
| Semrush | Authority Score | 0–100 对数 | 是（免费 / 付费） | semrush.com |
| Majestic | Trust Flow / Citation Flow | 各 0–100 | 部分——有限免费 | majestic.com/reports/site-explorer |

## 快速查询的工作流

如果有一批站要筛（比如外链 outreach 或竞品研究）：

1. 先过一遍 Ahrefs 检查器——最快、不注册。记下 DR。
2. 如果有 Moz 账号，再过一遍 Moz 的 Domain Analysis。记下
   DA。
3. 比 DR 和 DA ——两边差距大的（比如 DR 60 但 DA 30），
   说明各家链接图看到的是不同的链接。
4. 想看第三视角用 Majestic 的 Trust / Citation Flow。
5. 用数字排序、推比较**，**别**只追数字。你领域的 DR 30
   站依然打得到。

## 资料与工具

- **Ahrefs 网站权重检查器（DR，无需登录）：**
  <https://ahrefs.com/zh/website-authority-checker/>
- **Moz Domain Analysis（DA，需登录）：**
  <https://moz.com/domain-analysis>
- **Semrush Authority Score：**
  <https://www.semrush.com/analytics/overview/>
- **Majestic Site Explorer：**
  <https://majestic.com/reports/site-explorer>
- **Moz 对 DA 的解释：**
  <https://moz.com/learn/seo/domain-authority>
- **Ahrefs 对 DR 的解释：**
  <https://ahrefs.com/blog/domain-rating/>

DA 和 DR 是有用的诊断，不是排名的杠杆。落到实操还是要按引擎
走——以这个数量级，**`3-google-seo`** 是最大引擎，看受众
需要再看其他。