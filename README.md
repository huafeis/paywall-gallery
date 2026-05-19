# Open Paywall Gallery

Languages: [English](README.md) | [简体中文](README.zh-CN.md)

An open, curated dataset of iOS app paywalls and onboarding flows, published by [PaywallPro](https://www.paywallpro.app/?utm_source=github&utm_medium=open_dataset&utm_campaign=paywall_gallery).

Study how top iOS apps design paywalls, structure pricing, use free trials, present offers, onboard users, and monetize across different categories.

Star this repo if you want us to keep adding more public paywall and onboarding examples.

---

## What is PaywallPro?

PaywallPro is a subscription intelligence platform for app developers, product managers, growth teams, and designers.

It helps teams study real iOS paywalls, onboarding flows, pricing models, historical changes, and monetization signals from leading subscription apps.

PaywallPro tracks:

- 46,000+ iOS paywall screenshots
- 2,000+ onboarding flows
- Historical paywall versions
- Pricing and trial changes
- Revenue signals such as MRR, RPD, ARPU, and subscription benchmarks

Built for professionals who want real subscription insights, not just visual inspiration:

- Explore competitor paywalls and learn what drives conversions
- Track how pricing, trials, and design evolve over time
- Analyze revenue with RPD, ARPU, and subscription benchmarks
- Discover monetization strategies from top-performing apps

This open dataset is published by the PaywallPro team to give the developer and product community free access to curated paywall intelligence.

---

## Why this exists

Subscription apps are growing fast, but most teams still make paywall and pricing decisions based on guesswork, personal taste, or isolated A/B tests.

Open Paywall Gallery helps builders study real paywall examples before deciding what to design, build, or test.

Use it to understand:

- How top apps present subscription value
- How pricing options are structured
- How free trials are positioned
- How onboarding flows prepare users for purchase
- How monthly and annual plans are framed
- How paywall patterns differ by category
- What monetization signals can be learned from real apps

---

## About this repository

`paywall-gallery` is an open dataset of iOS app paywall and onboarding previews, published as machine-readable Markdown files.

It is a curated subset of the PaywallPro database, designed to be:

- Freely accessible, no signup required
- Machine-readable, with structured frontmatter for programmatic access
- Easy to browse, with human-readable summaries and preview screenshots
- Useful for product research, pricing research, UX reference, and growth analysis

Current review release: 10 apps. Target public release: Top 500 iOS subscription apps, ongoing expansion.

---

## What's included

This public repository includes:

- Representative paywall screenshots
- Onboarding flow previews where available
- Compact app case pages
- Pricing model summaries
- Paywall pattern classification
- Selected public-facing monetization signals
- Category-level indexes
- Links to explore more on PaywallPro

---

## What's kept on PaywallPro

This repository offers a curated public preview of each app.

The full PaywallPro product includes:

- Full paywall screenshot sets
- Complete onboarding flows
- All historical paywall versions
- Version-by-version changes
- Before and after paywall comparisons
- Historical pricing experiments
- A/B comparison references
- Revenue, MRR, RPD, ARPU, and ranking signals
- Advanced filters by category, region, pricing model, and app type

Explore the full database:

[https://www.paywallpro.app](https://www.paywallpro.app/?utm_source=github&utm_medium=open_dataset&utm_campaign=paywall_gallery)

---

## Data format

Each app entry lives in:

```txt
apps/{app-name}-{app_id}.md
```

Example:

```yaml
---
app_name: "YouTube"
app_id: 544007664
developer: "Google"
category: "Photo & Video"
paywall_type: "Free Trial - Soft Paywall"
pricing_model: "2 offer sets across month"
mrr: "$55.84M"
rating: 4.68
versions_count: 1
offers:
  - period: "month"
    prices: ["$18.99", "$18.99/$29.99"]
screenshots_count: 2
onboarding_flows_count: 1
app_detail_url: "https://www.paywallpro.app/apps/youtube?id=544007664"
---
```

See [Data Dictionary](docs/data-dictionary.md) for field definitions.

---

## Featured apps

| App | Category | Estimated MRR | Pattern | Page |
|---|---|---:|---|---|
| YouTube | Photo & Video | $55.84M | Free Trial - Soft Paywall | [Open](apps/youtube-544007664.md) |
| ChatGPT | Productivity | $44.30M | No Free Trial - Soft Paywall | [Open](apps/chatgpt-6448311069.md) |
| Peacock TV: Stream TV & Movies | Entertainment | $24.85M | No Free Trial - Soft Paywall | [Open](apps/peacock-tv-stream-tv-and-movies-1508186374.md) |
| HBO Max: Stream Movies & TV | Entertainment | $19.00M | No Free Trial - Soft Paywall | [Open](apps/hbo-max-stream-movies-and-tv-1666653815.md) |
| Tinder Dating App: Date & Chat | Lifestyle | $17.12M | No Free Trial - Soft Paywall | [Open](apps/tinder-dating-app-date-and-chat-547702041.md) |
| Paramount+ | Entertainment | $13.34M | Free Trial - Soft Paywall | [Open](apps/paramount-530168168.md) |
| LinkedIn: Network & Job Finder | Business | $12.27M | Free Trial - Soft Paywall | [Open](apps/linkedin-network-and-job-finder-288429040.md) |
| Snapchat | Photo & Video | $11.86M | No Free Trial - Soft Paywall | [Open](apps/snapchat-447188370.md) |
| Crunchyroll | Entertainment | $9.18M | Free Trial - Soft Paywall | [Open](apps/crunchyroll-329913454.md) |
| YouTube Music | Music | $8.85M | Free Trial - Soft Paywall | [Open](apps/youtube-music-1017492454.md) |

---

## Browse by category

- [Entertainment](categories/entertainment.md)
- [Photo & Video](categories/photo-video.md)
- [Productivity](categories/productivity.md)
- [Lifestyle](categories/lifestyle.md)
- [Business](categories/business.md)
- [Music](categories/music.md)

---

## Browse by paywall pattern

- [Free Trial Paywalls](docs/free-trial-paywalls.md)
- [Monthly vs Annual Pricing](docs/monthly-vs-annual-pricing.md)
- [Paywall Pattern Taxonomy](docs/paywall-pattern-taxonomy.md)

---

## Suggested use cases

For indie developers:

- Find pricing references before launching a subscription app
- Study how top apps explain subscription value
- Compare free trial and non-trial paywall structures

For product managers:

- Benchmark paywall patterns across categories
- Prepare paywall redesign references
- Understand how competitors package plans and benefits

For growth teams:

- Analyze pricing anchors
- Study trial positioning
- Find ideas for paywall A/B tests

For designers:

- Study layout, visual hierarchy, offer cards, CTA design, and benefit presentation
- Build a reference library for subscription UX

---

## Roadmap

- Format validation batch
- Top 100 curated dataset
- Top 500 public dataset
- Category index pages
- Paywall pattern index pages
- Continuous expansion and updates
- Automated update pipeline with GitHub Actions

---

## Contributing

Found a paywall worth documenting? Spotted a data error?

See [CONTRIBUTING.md](CONTRIBUTING.md) for contribution guidelines.

---

## License and usage

Structured metadata in this repository is available for learning, research, commentary, and internal product reference with attribution.

You may not bulk copy, repackage, resell, or use this dataset to build a competing commercial paywall intelligence product.

Screenshots are copyrighted by their respective app developers.

See [LICENSE](LICENSE) for details.

---

## Powered by PaywallPro

Open Paywall Gallery is published by PaywallPro.

PaywallPro helps subscription app teams research paywalls, onboarding flows, pricing models, historical changes, and monetization signals from top iOS apps.
