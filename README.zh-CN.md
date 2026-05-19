# Open Paywall Gallery

## 语言版本

- [English](README.md)
- [简体中文](README.zh-CN.md)

由 [PaywallPro](https://www.paywallpro.app/?utm_source=github&utm_medium=open_dataset&utm_campaign=paywall_gallery) 发布的开放、精选 iOS App 付费墙与 Onboarding 案例数据集。

你可以通过这个仓库研究头部 iOS App 如何设计付费墙、设置价格、使用免费试用、展示订阅权益、设计 Onboarding 流程，并在不同品类中实现订阅变现。

如果你希望我们持续开放更多付费墙和 Onboarding 案例，欢迎 Star 这个仓库。

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

你可以用它理解：

- 头部 App 如何呈现订阅价值
- 不同价格档位如何组织
- 免费试用如何被包装和强调
- Onboarding 如何为购买转化做铺垫
- 月付与年付方案如何建立价格锚点
- 不同品类的付费墙模式有什么差异
- 真实 App 中可以观察到哪些变现信号

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

## 哪些内容保留在 PaywallPro 中？

这个仓库提供每个 App 的精选公开预览。

完整的 PaywallPro 产品包含：

- 完整付费墙截图集
- 完整 Onboarding 流程
- 所有历史付费墙版本
- 逐版本变化记录
- 改版前后的付费墙对比
- 历史定价实验
- A/B 对比参考
- 收入、MRR、RPD、ARPU 和排名信号
- 按品类、地区、定价模型和 App 类型筛选的高级能力

查看完整数据库：

[https://www.paywallpro.app](https://www.paywallpro.app/?utm_source=github&utm_medium=open_dataset&utm_campaign=paywall_gallery)

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
| Peacock TV: Stream TV & Movies | Entertainment | $24.85M | No Free Trial - Soft Paywall | [打开](apps/peacock-tv-stream-tv-and-movies-1508186374.md) |
| HBO Max: Stream Movies & TV | Entertainment | $19.00M | No Free Trial - Soft Paywall | [打开](apps/hbo-max-stream-movies-and-tv-1666653815.md) |
| Tinder Dating App: Date & Chat | Lifestyle | $17.12M | No Free Trial - Soft Paywall | [打开](apps/tinder-dating-app-date-and-chat-547702041.md) |
| Paramount+ | Entertainment | $13.34M | Free Trial - Soft Paywall | [打开](apps/paramount-530168168.md) |
| Crunchyroll | Entertainment | $9.18M | Free Trial - Soft Paywall | [打开](apps/crunchyroll-329913454.md) |
| Audible: Audiobooks & Podcasts | Books | $8.84M | No Free Trial - Soft Paywall | [打开](apps/audible-audiobooks-and-podcasts-379693831.md) |
| ReelShort - Stream Drama & TV | Entertainment | $7.60M | No Free Trial - Soft Paywall | [打开](apps/reelshort-stream-drama-and-tv-1636235979.md) |
| Bumble Dating App: Meet & Date | Lifestyle | $7.26M | Credit Paywall | [打开](apps/bumble-dating-app-meet-and-date-930441707.md) |
| Life360: Stay Connected & Safe | Social Networking | $6.63M | Free Trial - Soft Paywall | [打开](apps/life360-stay-connected-and-safe-384830320.md) |
| Hulu: Stream TV shows & movies | Entertainment | $6.57M | No Free Trial - Soft Paywall | [打开](apps/hulu-stream-tv-shows-and-movies-376510438.md) |

---

## 按品类浏览

- [Entertainment](categories/entertainment.md)
- [Lifestyle](categories/lifestyle.md)
- [Books](categories/books.md)
- [Social Networking](categories/social-networking.md)

---

## 按付费墙模式浏览

- [Free Trial Paywalls](docs/free-trial-paywalls.md)
- [Monthly vs Annual Pricing](docs/monthly-vs-annual-pricing.md)
- [Paywall Pattern Taxonomy](docs/paywall-pattern-taxonomy.md)

---

## 适合哪些使用场景？

对独立开发者：

- 在上线订阅 App 前查找定价参考
- 学习头部 App 如何解释订阅价值
- 对比免费试用与非试用付费墙结构

对产品经理：

- Benchmark 不同品类的付费墙模式
- 为付费墙改版准备参考案例
- 理解竞品如何组织套餐和权益

对增长团队：

- 分析价格锚点
- 研究试用期呈现方式
- 寻找付费墙 A/B 测试方向

对设计师：

- 研究布局、视觉层级、套餐卡片、CTA 和权益表达方式
- 建立订阅 UX 参考库

---

## 路线图

- 格式校验批处理
- Top 100 精选数据集
- Top 500 公开数据集
- 品类索引页
- 付费墙模式索引页
- 持续扩展和更新
- 基于 GitHub Actions 的自动更新流水线

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
