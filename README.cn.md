# x-cmd/seo — SEO 专题文库

搜索引擎优化的文章、横向对比与按引擎的深度介绍。在
<https://x-cmd.com/seo> 以专题文库形式发布。

> 🌐 **English version: [README.md](./README.md)** — same
> content, English front matter.

本仓库托管 x-cmd 官网「SEO」专题的英中双语文章。文章为内容导向，
事实优先，欢迎任何人提交**修改 PR** — 见
[`CONTRIBUTING.md`](./CONTRIBUTING.md)。

## 仓库结构

```
x-cmd/seo/
├── README.md                 # 本文件（英文）
├── README.cn.md              # 中文版
├── CONTRIBUTING.md           # 文章写作流程 + frontmatter 规范 + FAQ schema
├── SKILL.md                  # AI agent 配方
├── LICENSE                   # Apache-2.0
└── docs/
    ├── 1-seo-basics.{en,cn,llms,faq}.md          # 什么是 SEO + 小站收录
    ├── 2-google-seo.{en,cn,llms,faq}.md          # 谷歌 SEO + Search Console
    ├── 3-bing-indexnow.{en,cn,llms,faq}.md       # Bing Webmaster Tools + IndexNow
    ├── 4-yahoo.{en,cn,llms,faq}.md               # Yahoo Search（独立）
    ├── 5-duckduckgo.{en,cn,llms,faq}.md          # DuckDuckGo SEO
    ├── 6-baidu.{en,cn,llms,faq}.md               # 百度 SEO
    └── 7-shenma.{en,cn,llms,faq}.md              # 神马 SEO（移动端）
```

文件名前缀的数字是阅读顺序。每个槽位的四个文件保持同步：
`.en.md`、`.cn.md`、`.llms.md`、`.faq.yml`。

## 文章槽位

| 槽位 | 文章 | 用途 |
| --- | --- | --- |
| `1-seo-basics` | 什么是 SEO + 小站收录 | 第一篇——定义、核心概念、sitemap / robots.txt / 结构化数据 / 反向链接。 |
| `2-google-seo` | 谷歌 SEO + Search Console | 最大的搜索引擎；如何优化；如何用 Search Console。 |
| `3-bing-indexnow` | Bing Webmaster Tools + IndexNow | Bing 站长工具；IndexNow 协议。 |
| `4-yahoo` | Yahoo Search | Yahoo 作为独立搜索引擎（由 Bing 驱动，但有自己的产品）。 |
| `5-duckduckgo` | DuckDuckGo SEO | 注重隐私；Bing 衍生结果；市场份额较小但在增长。 |
| `6-baidu` | 百度 SEO | 中文搜索巨头；百度搜索资源平台。 |
| `7-shenma` | 神马 SEO | UC 浏览器背后的移动端中文搜索引擎。 |

## 姊妹仓库

- [`x-cmd/cve`](https://github.com/x-cmd/cve) — 专题文库模式参考。
- [`x-cmd/gpg`](https://github.com/x-cmd/gpg) — 专题文库模式参考。
- [`x-cmd/terminal`](https://github.com/x-cmd/terminal) — 终端专题文库。
- [`x-cmd/browser`](https://github.com/x-cmd/browser) — 浏览器专题文库。
- [`x-cmd/ghclaw`](https://github.com/x-cmd/ghclaw) — GitHub 事件 claw 设计。

## 许可

Apache License 2.0 — 见 [`LICENSE`](./LICENSE)。