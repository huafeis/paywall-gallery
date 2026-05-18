# Field Reference

The Markdown pages are optimized for human reading. Structured metadata lives in [data/apps.json](../data/apps.json).

| Field | Description |
|---|---|
| app_id | App Store numeric identifier. |
| app_name | App Store display name in the US storefront. |
| slug | Stable repository slug generated from the App name. |
| developer | App developer or seller name. |
| category | App Store category. |
| mrr_usd | Estimated monthly recurring revenue in USD. |
| category_rank | App Store category ranking where available. |
| current_version | Captured App version. |
| version_release_date | Release date for the captured version. |
| paywall_type | Paywall classification from PaywallPro. |
| pricing | Human-readable pricing summary extracted from the captured paywall. |
| markdown_path | Relative path to the App case page. |
| paywall_image | Relative path to the 360px-displayed WebP screenshot. |
| paywallpro_url | PaywallPro detail link with GitHub campaign attribution. |
