# Contributing to Open Paywall Gallery

## Languages

- [English](CONTRIBUTING.md)
- [简体中文](CONTRIBUTING.zh-CN.md)

Thanks for your interest in contributing to Open Paywall Gallery.

Open Paywall Gallery is a public research gallery of iOS subscription paywalls and onboarding flows, published by PaywallPro.

The goal of this repository is to help app developers, product managers, growth teams, UX designers, and researchers study real subscription paywall examples from top iOS apps.

---

## What You Can Contribute

You can help improve this repository by:

- Requesting an app to be added
- Reporting broken screenshots or missing preview images
- Suggesting better paywall pattern labels
- Suggesting better category pages or index pages
- Suggesting new public data fields
- Correcting public metadata
- Improving README wording
- Improving documentation
- Sharing useful paywall research questions

---

## Request an App

If you want us to add a specific app, please open an Issue and include:

```txt
App name:
App Store URL:
Country or region:
Why this app is interesting:
What you want to learn from its paywall or onboarding flow:
```

Good app requests usually include one of the following reasons:

- The app has strong subscription revenue
- The app has an interesting paywall structure
- The app uses a notable free trial or pricing strategy
- The app has a strong onboarding flow before the paywall
- The app is an important competitor in a specific category
- The app recently changed its paywall, pricing, or subscription flow

---

## Report a Broken Screenshot

If a screenshot is missing, broken, duplicated, or displayed incorrectly, please open an Issue and include:

```txt
App page:
Broken image URL or filename:
What happened:
What you expected to see:
```

---

## Suggest a Paywall Pattern

If you think a paywall pattern label can be improved, please open an Issue and include:

```txt
App name:
Current pattern:
Suggested pattern:
Reason:
Similar examples, if any:
```

Common paywall patterns include:

- Free Trial - Soft Paywall
- Hard Paywall
- Multi-Offer Paywall
- Promotional Paywall
- Onboarding Paywall
- Monthly vs Annual Pricing
- Freemium Upgrade Paywall

---

## Suggest a Data Field

If you think a new public field would make the dataset more useful, please open an Issue and include:

```txt
Suggested field name:
Why this field is useful:
Example value:
Who would use this field:
```

Examples of possible fields:

- trial_duration
- default_selected_plan
- has_close_button
- has_discount_badge
- has_countdown_timer
- onboarding_steps_count
- paywall_entry_point
- primary_cta_copy

---

## Generated Files

Some files in this repository may be generated from PaywallPro's internal data pipeline.

Please avoid manually editing generated app pages, screenshots, or data files unless the maintainers confirm the change.

Files that may be generated include:

```txt
apps/*
screenshots/*
data/*
```

Safer files to suggest improvements for include:

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

## Attribution

If you reference this project in an article, post, research note, internal document, newsletter, video, or presentation, please cite it as:

```txt
Open Paywall Gallery by PaywallPro
https://github.com/paywallpro/paywall-gallery
https://www.paywallpro.app
```

Please keep the PaywallPro attribution when using public data from this repository.

---

## License and Usage

This repository is published as a public research gallery.

You may use it for learning, research, commentary, internal product reference, educational writing, and public posts with attribution.

You may not bulk copy the dataset, repackage it as your own database, resell the data, remove PaywallPro attribution, or use the dataset to build a competing commercial paywall intelligence product.

App screenshots and UI belong to their respective app owners.

See [LICENSE](LICENSE) for full terms.

---

## About PaywallPro

PaywallPro is a subscription intelligence platform for iOS apps.

It helps app developers, product managers, growth teams, and designers study real paywalls, onboarding flows, pricing models, historical changes, and monetization signals from leading subscription apps.

Learn more:

https://www.paywallpro.app
