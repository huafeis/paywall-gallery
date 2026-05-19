# 为 Open Paywall Gallery 做贡献

## 语言版本

- [English](CONTRIBUTING.md)
- [简体中文](CONTRIBUTING.zh-CN.md)

感谢你对 Open Paywall Gallery 的关注。

Open Paywall Gallery 是由 PaywallPro 发布的公开研究型案例库，收录 iOS 订阅 App 的付费墙和 Onboarding 流程。

这个仓库的目标是帮助 App 开发者、产品经理、增长团队、UX 设计师和研究者，研究真实头部 iOS App 的订阅付费墙案例。

---

## 你可以贡献什么？

你可以通过以下方式帮助改进这个仓库：

- 请求添加某个 App
- 报告损坏的截图或缺失的预览图片
- 建议更准确的付费墙模式标签
- 建议更好的品类页面或索引页面
- 建议新增公开数据字段
- 修正公开元数据
- 改进 README 文案
- 改进说明文档
- 分享有价值的付费墙研究问题

---

## 请求添加 App

如果你希望我们添加某个具体 App，请提交 Issue，并包含以下信息：

```txt
App 名称：
App Store 链接：
国家或地区：
为什么这个 App 值得研究：
你希望从它的付费墙或 Onboarding 流程中了解什么：
```

---

## 报告损坏的截图

如果某张截图缺失、损坏、重复或显示异常，请提交 Issue，并包含以下信息：

```txt
App 页面：
损坏的图片 URL 或文件名：
发生了什么问题：
你预期看到什么：
```

---

## 建议付费墙模式

如果你认为某个 App 的付费墙模式标签可以优化，请提交 Issue，并包含 App 名称、当前模式、建议模式、原因和类似案例。

常见付费墙模式包括：

- Free Trial - Soft Paywall
- Hard Paywall
- Multi-Offer Paywall
- Promotional Paywall
- Onboarding Paywall
- Monthly vs Annual Pricing
- Freemium Upgrade Paywall

---

## 建议数据字段

如果你认为某个新的公开字段能让数据集更有价值，请提交 Issue，并包含以下信息：

```txt
建议字段名称：
为什么这个字段有价值：
示例值：
谁会使用这个字段：
```

可能有价值的字段示例：

- trial_duration
- default_selected_plan
- has_close_button
- has_discount_badge
- has_countdown_timer
- onboarding_steps_count
- paywall_entry_point
- primary_cta_copy

---

## 自动生成文件

这个仓库中的部分文件可能由 PaywallPro 内部数据流程自动生成。除非维护者确认，否则请尽量避免手动修改自动生成的 App 页面、截图或数据文件。

可能由系统生成的文件包括：

```txt
apps/*
screenshots/*
data/*
```

更适合提交修改建议的文件包括：

```txt
README.md
README.zh-CN.md
CONTRIBUTING.md
CONTRIBUTING.zh-CN.md
docs/*
categories/*
.github/ISSUE_TEMPLATE/*
```

---

## 署名

如果你在文章、帖子、研究笔记、内部文档、Newsletter、视频或演示文稿中引用这个项目，请按以下方式署名：

```txt
Open Paywall Gallery by PaywallPro
https://github.com/paywallpro/paywall-gallery
https://www.paywallpro.app
```

---

## License 和使用说明

这个仓库作为公开研究型案例库发布。你可以将它用于学习、研究、评论、内部产品参考、教育写作和带署名的公开内容。

你不能批量复制该数据集、将其重新包装成自己的数据库、转售这些数据、移除 PaywallPro 署名，或使用该数据集构建商业化竞品付费墙情报产品。

App 截图和 UI 版权归各自 App 开发者所有。完整条款请查看 [LICENSE](LICENSE)。

---

## 关于 PaywallPro

PaywallPro 是一个面向 iOS App 的订阅智能分析平台。

它帮助 App 开发者、产品经理、增长团队和设计师研究头部 App 的真实付费墙、Onboarding 流程、定价模型、历史变化和变现数据信号。

了解更多：

https://www.paywallpro.app
