# Open Paywall Gallery

由 [PaywallPro](https://www.paywallpro.app/?utm_source=github&utm_medium=open_dataset&utm_campaign=paywall_gallery) 发布的开放、精选 iOS App 付费墙与 Onboarding 案例数据集。

你可以通过这个仓库研究头部 iOS App 如何设计付费墙、设置价格、使用免费试用、展示订阅权益、设计 Onboarding 流程，并在不同品类中实现订阅变现。

如果你希望我们持续开放更多付费墙和 Onboarding 案例，欢迎 Star 这个仓库。

## 语言版本

- [English](README.md)
- [简体中文](README.zh-CN.md)

---

## 什么是 PaywallPro？

PaywallPro 是一个面向 App 开发者、产品经理、增长团队和设计师的订阅智能分析平台。

它帮助团队研究真实 iOS App 的付费墙、Onboarding 流程、定价模型、历史版本变化和变现数据信号。

PaywallPro 目前追踪：

- 46,000+ iOS 付费墙截图
- 2,000+ Onboarding 流程
- 付费墙历史版本
- 定价与试用变化
- MRR、RPD、ARPU 和订阅基准等收入信号

---

## 为什么我们做这个仓库？

订阅 App 正在快速增长，但很多团队在做付费墙和定价决策时，依然主要依赖经验、审美判断，或者孤立的 A/B 测试。

Open Paywall Gallery 希望帮助开发者在设计、开发或测试之前，先研究真实的付费墙案例。

---

## 关于这个仓库

`paywall-gallery` 是一个开放的 iOS App 付费墙与 Onboarding 预览数据集，以机器可读的 Markdown 文件形式发布。

它是 PaywallPro 数据库中的精选子集，设计目标是：

- 免费访问，无需注册
- 机器可读，使用结构化 frontmatter，方便程序化读取
- 易于浏览，包含人工可读的摘要和预览截图
- 适合产品研究、定价研究、UX 参考和增长分析

当前评审版本：10 个 App。目标公开版本：Top 500 iOS 订阅 App，并持续扩展。

---

## 这个仓库包含什么？

- 代表性的付费墙截图
- 可用时提供 Onboarding 预览
- 简洁的 App 案例页面
- 定价模型摘要
- 付费墙模式分类
- 部分公开的变现数据信号
- 品类索引
- 跳转到 PaywallPro 查看更多信息的链接

---

## 数据格式

每个 App 条目位于：

```txt
apps/{app-name}-{app_id}.md
```

字段说明请查看 [Data Dictionary](docs/data-dictionary.md)。

---

## 代表性 App

| App | 品类 | 预估 MRR | 付费墙模式 | 页面 |
|---|---|---:|---|---|
| YouTube | Photo & Video | $55.84M | Free Trial - Soft Paywall | [打开](apps/youtube-544007664.md) |
| ChatGPT | Productivity | $44.30M | No Free Trial - Soft Paywall | [打开](apps/chatgpt-6448311069.md) |
| Peacock TV: Stream TV & Movies | Entertainment | $24.85M | No Free Trial - Soft Paywall | [打开](apps/peacock-tv-stream-tv-and-movies-1508186374.md) |
| HBO Max: Stream Movies & TV | Entertainment | $19.00M | No Free Trial - Soft Paywall | [打开](apps/hbo-max-stream-movies-and-tv-1666653815.md) |
| Tinder Dating App: Date & Chat | Lifestyle | $17.12M | No Free Trial - Soft Paywall | [打开](apps/tinder-dating-app-date-and-chat-547702041.md) |
| Paramount+ | Entertainment | $13.34M | Free Trial - Soft Paywall | [打开](apps/paramount-530168168.md) |
| LinkedIn: Network & Job Finder | Business | $12.27M | Free Trial - Soft Paywall | [打开](apps/linkedin-network-and-job-finder-288429040.md) |
| Snapchat | Photo & Video | $11.86M | No Free Trial - Soft Paywall | [打开](apps/snapchat-447188370.md) |
| Crunchyroll | Entertainment | $9.18M | Free Trial - Soft Paywall | [打开](apps/crunchyroll-329913454.md) |
| YouTube Music | Music | $8.85M | Free Trial - Soft Paywall | [打开](apps/youtube-music-1017492454.md) |

---

## 按品类浏览

- [Entertainment](categories/entertainment.md)
- [Photo & Video](categories/photo-video.md)
- [Productivity](categories/productivity.md)
- [Lifestyle](categories/lifestyle.md)
- [Business](categories/business.md)
- [Music](categories/music.md)

---

## 贡献

发现值得记录的付费墙？发现数据错误？

请查看 [CONTRIBUTING.zh-CN.md](CONTRIBUTING.zh-CN.md)。

---

## License 和使用说明

本仓库中的结构化元数据可用于学习、研究、评论和内部产品参考，使用时请注明出处。

你不能批量复制、重新包装、转售这些数据，或使用该数据集构建商业化竞品付费墙情报产品。

截图和 UI 版权归各自 App 开发者所有。完整条款请查看 [LICENSE](LICENSE)。

---

## Powered by PaywallPro

Open Paywall Gallery 由 PaywallPro 发布。

PaywallPro 帮助订阅 App 团队研究头部 iOS App 的付费墙、Onboarding 流程、定价模型、历史变化和变现数据信号。
