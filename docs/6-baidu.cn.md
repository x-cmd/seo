---
x-title: 百度 SEO — 中文搜索、ICP 备案、百度搜索资源平台
x-desc: >-
  百度是中文搜索的龙头，2026 年占据中文搜索市场约 75%。大陆站点需 ICP 备案。
  百度搜索资源平台（ziyuan.baidu.com）用于 sitemap 与手动提交。
x-sidebar: 百度 SEO
x-keywords: 百度 seo, 百度搜索资源平台, icp 备案, 百度蜘蛛, 百度站长
x-json-ld:
  '@context': https://schema.org
  '@graph':
    - '@type': TechArticle
      headline: '百度 SEO'
      inLanguage: 'cn'
      about: '百度搜索引擎优化'
---

# 百度 SEO — 中文搜索、ICP 备案、百度搜索资源平台

**百度**是中文搜索的龙头，2026 年占据中文搜索市场约 **75%**。对
面向中国大陆的中文内容，百度是默认搜索引擎——Google 在中国大陆基本
被屏蔽。

百度有自己的排名因素、自己的爬虫（Baiduspider / Baiduspider-image）、
自己的站长工具（**百度搜索资源平台**）、以及自己的产品生态（百度贴吧、
百科、知道、地图）。

本文覆盖百度专属 SEO：如何为百度优化、ICP 备案要求、百度与 Google 的
区别。

> **TL;DR。** 百度 SEO = ICP 备案 + 中文内容 + 百度搜索资源平台
> + 百度自有产品关联。收录比 Google 慢；偏爱老域名；权重高在标题 /
> meta / 关键词密度；支持 Schema.org JSON-LD。

## 为什么百度？

- **中文搜索市场约 75%**（StatCounter 2026 Q2）。
- **大陆搜索流量按查询量计 50%+**。
- **中文浏览器的默认搜索引擎。**
- **大力投入 AI 功能**——百度文心一言、中文 AI 摘要。

如果你的受众在中国大陆或讲中文，百度是主要目标。香港 / 台湾 / 海外
华人受众也用百度，但 Google 作为次要更强。

## 百度 vs Google — 区别

百度的算法与 Google 在基础上相似（内容质量、反向链接、技术健康）但
侧重点不同。

### 百度与 Google 不同的地方

- **需要 ICP 备案**（大陆站点）—— 否则搜索结果可能受限或被移除。
- **标题 + meta keywords 更重要。** 百度历史上看重 `<meta
  name="keywords">`（Google 忽略）。
- **关键词密度** —— 百度比 Google 更看重正文中的关键词重复。
- **域名年龄** —— 百度比 Google 更偏爱老域名。
- **贴吧 / 百科 / 知道链接** —— 百度在搜索结果中给自己的产品更高排名。
- **HTTPS** —— 自 2015 年起必需。
- **收录慢** —— 新站 1-4 周对比 Google 的 1-7 天。
- **移动友好性** —— 百度有自己的一套移动规则。

### 百度与 Google 一致的地方

- **内容质量 + E-E-A-T 类信号**（百度有自己的版本，有时叫"搜索结果
  质量"）。
- **反向链接** —— 质量与数量。
- **结构化数据** —— 百度支持 Schema.org JSON-LD。
- **移动** —— 移动友好是必需的。
- **页面速度** —— 包括百度自己的 MIP 框架（2026 年大部分弃用，被标准
  加速移动页面取代）。
- **Sitemap** —— 接受 XML sitemap。

## ICP 备案

对于大陆服务器，中国要求向工业和信息化部（MIIT）做 **ICP 备案**
（"bei'an"）。

没有 ICP 备案：

- 大陆服务器上的站点可能遭中国 ISP 屏蔽。
- 百度可能在搜索结果中压制未备案的站点。
- Apple 要求非中国 App 发行人在中国大陆发 App 也需 ICP 备案。

如何备案：

1. 把站点托管在大陆服务器（阿里云、腾讯云等）。
2. 在主机商注册。
3. 通过主机商门户提交备案 —— 主机商代表你向 MIIT 备案。
4. 等 7-20 天批准。
5. 在站点页脚添加 ICP 号（必需）。

两类：

- **ICP 备案** —— 大陆所有站点必需。
- **公安备案** —— 有用户生成内容的站点必需（论坛、评论）。

对海外服务器（香港、新加坡、美国），ICP 备案**不是**必需的。百度仍
会收录你的站，但你可能比大陆托管的站竞争优势小。

## 百度搜索资源平台

**百度搜索资源平台**（<https://ziyuan.baidu.com/>）是百度免费的
站长工具。Google Search Console + Bing Webmaster Tools 的镜像。

### 设置

1. 访问 <https://ziyuan.baidu.com/>。
2. 用百度账号登录。
3. 通过以下方式验证：
   - **HTML 文件** —— 根目录的 `baidu_verify_*.html`。
   - **Meta 标签** —— `<meta name="baidu-site-verification" content="...">`。
   - **DNS CNAME** —— 百度特定的验证记录。
4. 验证后，数据在 24-72 小时内开始收集。

### 每日 / 每周工作流

1. **数据监控** → 搜索查询、收录页面、爬取错误。
2. **链接提交** → 提交 sitemap、手动 URL 提交、API 提交。
3. **抓取诊断** → 爬虫状态、robots.txt 检查。
4. **搜索展现** → SERP 展现、富结果。
5. **移动适配** → 移动友好测试。
6. **百度站长工具** → 反向链接分析、关键词分析。

## 提交 URL 到百度

百度提供四种 URL 提交方式：

### 1. Sitemap 提交

与 Google / Bing 同一 XML sitemap 格式。通过百度搜索资源平台的
Sitemap 工具提交。

### 2. 手动提交

在搜索资源平台，粘贴单个 URL 或最多 20 个 URL。谨慎使用——给重要的
新内容用。

### 3. API 提交

```sh
curl -X POST "https://ziyuan.baidu.com/linksubmit/jsonandsubmit" \
  -d 'site=example.com&token=YOUR_TOKEN&type=original' \
  -F "urls[]=https://example.com/new-page-1" \
  -F "urls[]=https://example.com/new-page-2"
```

限制：每次提交 1,000 URL；每站每天 10 次提交。

### 4. 自动推送（JS 代码段）

百度提供一段 JavaScript 代码段嵌入页面，在用户访问时推送 URL 给百度。

```html
<script>
(function(){
    var bp = document.createElement('script');
    bp.src = '//push.zhanzhang.baidu.com/push.js';
    var s = document.getElementsByTagName("script")[0];
    s.parentNode.insertBefore(bp, s);
})();
</script>
```

这是百度最简单的"自动推送"机制——每次页面访问把 URL 推到百度队列。

## 百度专属排名因素

### 内容

- **标题** —— 最重的页面内信号。包含主关键词。
- **Meta 描述** —— 百度看重（Google 不用它排名）。
- **Meta keywords** —— 百度读它（Google 忽略它）。
- **H1 / H2 / H3** —— 结构重要。
- **关键词密度** —— 2-3% 是历史最佳（Google 忽略）。
- **原创内容** —— 百度惩罚抓取 / 聚合内容。
- **百度贴吧 / 百科 / 知道存在** —— 在百度自家产品上有相关页面
  可以间接提升你的站。

### 技术

- **ICP 备案** —— 大陆必需。
- **HTTPS** —— 必需。
- **移动友好** —— 必需。
- **页面速度** —— 百度的 MIP（移动加速页）框架 2026 年大部分
  弃用。
- **结构化数据** —— 百度支持 Schema.org JSON-LD；也支持百度
  自己的百度通用 schema。
- **Sitemap** —— 通过搜索资源平台提交。

### 页外

- **反向链接** —— 质量与数量。百度比 Google 更看重中国域反向
  链接（`.cn`、`.com.cn`、`.com`）。
- **锚文本** —— 百度比 Google 更看重精确匹配锚文本。
- **域名年龄** —— 老的中国域名排名更好。

## 百度 AI 功能

2026 年，百度提供：

- **AI 摘要** —— 中文查询的 AI Overview 对应物。
- **百度文心一言** —— 百度底层的 LLM。
- **AI Search** —— 基于聊天的查询界面。

与 Google / DuckDuckGo 同样模式：引用高质量来源，长篇一手中文内容
胜出。

## 百度 SEO 常见错误

- **没 ICP 备案** —— 海外站点不需要，但大陆托管的站没备案
  处于劣势。
- **针对中国用纯英文内容** —— 百度给中文内容更高排名。翻译成
  简体中文，用简体中文关键词。
- **标题关键词堆砌** —— `<title>SEO|SEM|PPC|...
  </title>` 被惩罚。
- **隐藏文本** —— 同色背景和文本被惩罚。
- **买链接** —— 百度可能压制。
- **没提交 sitemap** —— 没 sitemap，百度爬虫可能漏页面。
- **没贴吧 / 百科 / 知道存在** —— 在百度自家产品上有存在可以
  间接帮忙。

## 百度速查清单

面向中文市场的站点 1 小时清单：

- [ ] ICP 备案已获取（大陆服务器）。
- [ ] ICP 号显示在页脚。
- [ ] 百度搜索资源平台账号已创建。
- [ ] 站点通过 HTML / meta / DNS 验证。
- [ ] XML sitemap 已提交。
- [ ] 自动推送 JS 代码段已安装。
- [ ] 所有标题 + meta 描述都用简体中文。
- [ ] 强制 HTTPS。
- [ ] 移动友好测试通过。
- [ ] 结构化数据到位（JSON-LD 或百度通用）。
- [ ] 来自中国 `.cn` / `.com.cn` 域的 3+ 反向链接。

## 百度 vs Google — 概览

| 维度 | 百度 | Google |
| --- | --- | --- |
| 语言 | 简体中文为主 | 全球 |
| ICP 备案 | 大陆必需 | 无 |
| Meta keywords | 看重 | 忽略 |
| 关键词密度 | 看重 | 忽略 |
| 域名年龄 | 看重 | 略微看重 |
| 贴吧 / 百科 | 自有产品排得高 | N/A |
| Sitemap | ✅ | ✅ |
| 结构化数据 | Schema.org + 百度通用 | Schema.org |
| 收录速度 | 1-4 周（慢） | 1-7 天 |
| AI 功能 | AI 摘要 + 文心一言 | AI Overviews + Gemini |
| 市场份额（2026 Q2） | 中文约 75% | 全球约 91% |

## 下一步？

- **7-shenma** — 神马 SEO（移动端，中文）。

## 源码与官方资源

- **百度搜索资源平台：** <https://ziyuan.baidu.com/>
- **百度贴吧：** <https://tieba.baidu.com/>
- **百度百科：** <https://baike.baidu.com/>
- **百度知道：** <https://zhidao.baidu.com/>
- **百度地图：** <https://map.baidu.com/>
- **ICP 备案信息（阿里云）：** <https://help.aliyun.com/knowledge_detail/31745.html>
- **百度搜索帮助：** <https://help.baidu.com/question?prod_en=zhidao>