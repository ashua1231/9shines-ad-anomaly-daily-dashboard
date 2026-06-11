# 9shines label — Ad Anomaly Dashboard

Live daily ad-anomaly dashboard for 9shines label.

- **Live link:** deployed via Cloudflare Pages (connect this repo in Cloudflare → Pages).
- **Data:** Meta Ads (3 accounts) + Google Ads — 7-day actuals vs 30-day normalised baseline.
- **Refresh:** `index.html` is regenerated and committed by the daily 9am IST anomaly-detection run.

No build step — Cloudflare Pages serves `index.html` from the repo root directly.
