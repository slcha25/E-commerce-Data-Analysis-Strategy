# 🎲 Online Board Game Retailer — E-Commerce & Marketing Data Analysis Externship
### A 7-Project Externship — Diagnosing a Real E-Commerce Company's Ad-to-Sale Funnel

![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=flat-square)
![Duration](https://img.shields.io/badge/Duration-2%20Weeks-blue?style=flat-square)
![Role](https://img.shields.io/badge/Role-Marketing%20Data%20Analyst%20Extern-orange?style=flat-square)
![Stack](https://img.shields.io/badge/Stack-Google%20Analytics%20%7C%20Google%20Ads%20%7C%20Meta%20Ads%20%7C%20Shopify%20%7C%20Claude%20AI-informational?style=flat-square)
![Data](https://img.shields.io/badge/Data-Real%20%26%20Anonymized-lightgrey?style=flat-square)

> *"Getting traffic is easy; turning it into sales is the hard part."*
> Seven projects, four data platforms, one real online board game company's sales funnel — pulled apart, diagnosed, and put back together into a growth strategy.

> **A note on confidentiality**: This externship used a real company's live operational data under an NDA. Per the externship's terms, I can share the analysis, methodology, and findings — but not the client's name or any identifying details. Throughout this README, the company is referred to only as **"the Client."**

---

## 📖 Overview

This repository documents a hands-on marketing/e-commerce data analysis externship through **Extern**, working with **real operational data from an online board game publisher and retailer**. Unlike a classroom dataset, this was the actual data the company uses to run its business — real Google Analytics traffic, real Google Ads and Meta Ads campaign exports, and real Shopify checkout and product data.

The brief across all seven projects was the same underlying question, asked from a different angle each time: **where in the journey from ad click to completed order is the Client losing customers, and where should they invest next?**

Working alone through raw, messy, real-world exports — the kind where Shopify calls every source "web" and no platform shares a common user ID — I moved from foundational marketing literacy, to spreadsheet-level analysis of each platform individually, to a consolidated cross-platform funnel view built with Claude AI, and finally to a business-ready growth strategy presentation.

---

## 🌐 Live Interactive HTML Projects

The four deliverables below are interactive web pages. Open them through **GitHub Pages** to use their tabs, navigation, charts, and presentation controls.

> **GitHub Pages setup:** Replace `YOUR-GITHUB-USERNAME` and `YOUR-REPOSITORY` in the links below with your actual GitHub username and repository name. Then enable Pages from the repository's `/docs` folder by following the setup instructions below.

| Interactive deliverable | Description | Links |
|---|---|---|
| **Cross-Platform Dashboard** | Explore advertising, traffic, conversion, revenue, data-audit, and strategic-insight tabs. | [▶ Open Live Dashboard](https://YOUR-GITHUB-USERNAME.github.io/YOUR-REPOSITORY/docs/cross-platform-dashboard.html) · [View HTML Source](docs/cross-platform-dashboard.html) |
| **Dashboard Presentation** | A presentation-style walkthrough of the Project 6 dashboard findings. | [▶ Open Presentation](https://YOUR-GITHUB-USERNAME.github.io/YOUR-REPOSITORY/docs/dashboard-presentation.html) · [View HTML Source](docs/dashboard-presentation.html) |
| **Strategy Report** | Read the complete cross-platform analysis, limitations, insights, and recommendations. | [▶ Open Strategy Report](https://YOUR-GITHUB-USERNAME.github.io/YOUR-REPOSITORY/docs/strategy-report.html) · [View HTML Source](docs/strategy-report.html) |
| **Final Growth Strategy Presentation** | Navigate the final Project 7 presentation in a full-screen interactive format. | [▶ Open Final Presentation](https://YOUR-GITHUB-USERNAME.github.io/YOUR-REPOSITORY/docs/final-presentation.html) · [View HTML Source](docs/final-presentation.html) |

### GitHub Pages setup

1. Upload this `README.md`, the `.nojekyll` file, and the complete `docs` folder to the root of your GitHub repository.
2. Open the repository on GitHub and select **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select your default branch—usually `main`—and choose `/(root)`. Click **Save**. The HTML files remain inside the repository's `docs` folder, which is why each public URL contains `/docs/`.
5. Wait a few minutes for GitHub Pages to publish the site.
6. In this README, use **Ctrl+H** and replace:
   - `YOUR-GITHUB-USERNAME` with your GitHub username.
   - `YOUR-REPOSITORY` with the exact repository name.
7. Commit the updated README. The four **Open** links above will then launch the live, interactive versions.

> GitHub does not run an HTML file inside a README page. The README can show a link or preview image, while GitHub Pages runs the actual HTML and keeps its interactive features working.

---

## 🎥 Video Demonstrations

### Final Growth Strategy Presentation

[![Watch the Final Growth Strategy Presentation](https://img.youtube.com/vi/gxLf9POly1U/maxresdefault.jpg)](https://www.youtube.com/watch?v=gxLf9POly1U&t=44s)

[▶ Watch the final presentation on YouTube](https://www.youtube.com/watch?v=gxLf9POly1U&t=44s)

### Cross-Platform Dashboard Explanation

[![Watch the Cross-Platform Dashboard Explanation](https://img.youtube.com/vi/CUBsA6Djgbs/maxresdefault.jpg)](https://youtu.be/CUBsA6Djgbs)

[▶ Watch the dashboard explanation on YouTube](https://youtu.be/CUBsA6Djgbs)

> Click either thumbnail to open the video on YouTube. GitHub README files do not support an embedded YouTube player, so a clickable thumbnail is the most reliable presentation method.

---

## 🎯 The Client (Anonymized)

| | |
|---|---|
| **Company** | Online board game publisher & e-commerce retailer *(name withheld per externship confidentiality agreement)* |
| **Sample products analyzed** | 3 flagship product pages across the Client's board game catalog *(specific titles withheld)* |
| **Related entities in the raw data** | Two internally affiliated brands appeared in the raw exports — explicitly excluded from all analysis (every dataset was filtered down to the Client's own campaigns only) |
| **Platforms in scope** | Google Analytics, Google Ads, Meta Ads, Shopify |
| **Data sensitivity** | Real production data — company identity anonymized per the externship's confidentiality terms. Methodology and findings below are shareable; the source company is not |

---

## 🗺️ The Analysis Pipeline — Ad Click to Growth Strategy

Each project moved the work one stage further down the funnel — from raw exports to a boardroom-ready recommendation. No single platform tells the whole story; each stage below closes a gap the previous one leaves open.

```
 [1] COLLECT           [2] CLEAN & CALCULATE      [3] ANALYZE PER-PLATFORM        [4] CONSOLIDATE (AI)         [5] DIAGNOSE              [6] COMMUNICATE
 Raw Exports      ──▶   Sheets / Excel        ──▶  GA · Ads · Shopify        ──▶  Claude AI Dashboard    ──▶   Cross-Funnel Insight ──▶  Slides Presentation
 (GA, Ads,               Filter · Sort               Traffic · Engagement          Consolidated funnel          Where budget should         Executive Summary →
  Shopify)                Formulas · Charts           Ad Efficiency · Funnel        view across platforms        move, and why                Challenge → Insights →
                                                        Drop-off                                                                                Recommendations → Roadmap
```

| # | Stage | Tool / Platform | What Happens |
|---|---|---|---|
| **1** | **Collect** | Raw exports (GA, Google Ads, Meta Ads, Shopify) | Real, messy, unlabeled exports — the same files a marketing team pulls weekly |
| **2** | **Clean & Calculate** | Google Sheets / Excel | Filter out unrelated affiliated-brand noise, sort, and calculate core metrics: conversion rate, AOV, CTR, CPC |
| **3** | **Analyze Per-Platform** | GA · Google Ads · Meta Ads · Shopify | Each platform diagnosed on its own terms — engagement quality, ad efficiency, checkout drop-off, product performance |
| **4** | **Consolidate (AI)** | Claude AI | Because there's no shared user/session ID across platforms, Claude was used to align, summarize, and visualize a cross-platform funnel dashboard |
| **5** | **Diagnose** | Cross-platform synthesis | Turn scattered per-platform findings into a single view of where the funnel leaks and why |
| **6** | **Communicate** | Google Slides | Package 2–3 data-backed recommendations into a strategic story for a non-analyst audience |

> **Why not just merge everything?** Shopify labels all traffic "web," Google Ads and Meta Ads use different attribution windows (30-day last-click vs. 7-day click/1-day view), and none of the platforms share a transaction ID. Part of the actual skill being tested here was knowing **what can't be perfectly measured** — and building a credible story anyway.

---

## 📊 Key Findings & Recommendations

| Project | Deliverable | Key Finding |
|---|---|---|
| **3 — Google Analytics** | [Weak Landing Page Fixes (Doc)](https://docs.google.com/document/d/1pVzPqooBN8rQF7ODPyIJsZgoYKfsGB6g3_R3n5BqdX4/edit?tab=t.0) | Identified 3 underperforming product landing pages and one case of likely referrer-spam traffic (an unrelated retailer referring visitors to `/search`) — a mismatch that would have wasted optimization effort if not flagged |
| **4 — Google Ads vs. Meta Ads** | [Channel Comparison & Recommendations (Doc)](https://docs.google.com/document/d/1NIHchnVt4yNn_roF6VxupDZy3toeG9wWmsvWf_FJOQw/edit?usp=sharing) | Flagged the attribution-window mismatch (Google: 30-day last-click vs. Meta: 7-day click) before comparing platforms, then recommended shifting more budget toward Meta for traffic/conversion volume while keeping Google for its stronger real-sale ROAS |
| **5 — Shopify Funnel** | Shopify Funnel Report | Diagnosed checkout completion and cart-abandonment rates against store benchmarks, and identified which products carried the store's revenue vs. which were dragging on inventory |
| **6 — Cross-Platform Dashboard** | [Claude AI Dashboard (Artifact)](https://claude.ai/public/artifacts/3903d819-ef34-4b31-a789-dd8c0cc16e6d) | Meta Ads drives the highest traffic but the lowest conversion — recommended retargeting that campaign. Google Ads and Bing show higher purchase intent (Bing: 4.1% conversion rate; paid search sessions: 60.2% engagement) but are underinvested — recommended reallocating $1,000–$2,000 of budget toward Google Ads and Bing |
| **7 — Growth Strategy** | Final Slides Presentation | Synthesized all of the above into a business-ready narrative: Executive Summary → Challenge → Insights → Recommendations → Roadmap |

---

## 🧰 Tech Stack

- **Spreadsheets**: Google Sheets & Excel — filtering, sorting, formulas (conversion rate, AOV, CTR, CPC, ROAS), pivot-style analysis, chart building
- **Web Analytics**: Google Analytics — engagement metrics, segmentation (new vs. returning), traffic source & landing page analysis
- **Paid Media**: Google Ads & Meta Ads — impressions, CTR, CPC, conversions, attribution modeling
- **E-Commerce**: Shopify — checkout funnel data, product-level sales, cart abandonment, AOV, sell-through rate
- **AI**: Claude AI — cross-platform data consolidation, dashboard generation, recommendation refinement
- **Documentation & Delivery**: Google Docs (per-platform analysis write-ups), Google Slides (final growth strategy presentation)

---

## 📁 Folder Structure

```
Online Board Game Retailer /
├── docs/
│   ├── cross-platform-dashboard.html                                  — Interactive cross-platform dashboard
│   ├── dashboard-presentation.html                                    — Project 6 dashboard presentation
│   ├── strategy-report.html                                           — Full strategy report
│   └── final-presentation.html                                        — Project 7 final presentation
├── Project 1 Explore How Business Drive Online Sales/                      — Customer journey & sales funnel foundations
├── Project 2 Get Hands-On With Online Sales Data/                          — Sheets/Excel fundamentals on raw exports
├── Project 3 Analyze Traffic & Engagement From google Analytics/           — Real GA data: engagement, segmentation, landing pages
├── Project 4 Measure Paid Ad Campaign Effectiveness/                       — Real Google Ads & Meta Ads data + attribution
├── Project 5 Break down Shopify Data to Understand Sales/                  — Real Shopify checkout & product data
├── Project 6 Consolidate & Visualize the E Commerce Funnel With Claude/    — Cross-platform AI dashboard
├── Project 7 Turn Your Findings into a Growth Strategy & Presentation/     — Final strategy presentation
└── README.md                                                                — This file
```

---

## 🧩 Project-by-Project Breakdown

### Project 1 — Explore How Business Drive Online Sales
**Building marketing literacy before touching any real data.**
- Learned the **customer journey / sales funnel framework** that underlies every business decision
- Learned **performance marketing** fundamentals and the digital channels where businesses meet customers
- Studied the four key metrics businesses track obsessively, and the tools used to track them
- Reverse-engineered my own recent buying journey using marketing frameworks, and decoded the strategic moves a brand made to influence that decision
- **Outcome**: foundational literacy connecting customer behavior to data-driven business decisions — the lens used for every project that followed

### Project 2 — Get Hands-On With Online Sales Data
**Learning to read raw exports the way marketers actually do.**
- Practiced navigating unfiltered, real-world export files from Google Ads, Meta Ads, Google Analytics, and Shopify
- Built comfort with **filtering, sorting, and cleaning** data in Sheets/Excel
- Applied simple formulas to calculate totals, averages, and ratios (conversion rate, average order value)
- Built charts to visualize trends and spot the story hiding in the numbers
- **Outcome**: the baseline spreadsheet fluency required before any platform-specific analysis could begin

### Project 3 — Analyze Traffic & Engagement From Google Analytics
**First contact with the Client's real data.**
- Worked with **actual GA exports from the Client** — not demo data — under the externship's confidentiality terms
- Learned the core engagement metrics: bounce rate, session duration, landing page performance
- Applied **segmentation** — comparing new vs. returning visitor behavior
- Diagnosed traffic sources and landing pages together to understand visitor journeys
- Shortlisted 3 weak product landing pages, diagnosed the likely cause for each (design, traffic mismatch, or content), and proposed 2–3 concrete fixes per page
- Caught a data-quality issue along the way: traffic reaching `/search` from an unrelated national retailer with no logical connection to a board game store — flagged as likely referrer spam rather than a real optimization opportunity
- **Deliverable**: [Weak Landing Page Fixes (Google Doc)](https://docs.google.com/document/d/1pVzPqooBN8rQF7ODPyIJsZgoYKfsGB6g3_R3n5BqdX4/edit?tab=t.0)

### Project 4 — Measure Paid Ad Campaign Effectiveness
**Real Google Ads and Meta Ads data — and the attribution trap.**
- Worked with **real Google Ads and Meta Ads campaign exports** from the Client
- Learned the core ad metrics (impressions, clicks, CTR, CPC, conversions) and how **attribution** determines which platform gets credit for a sale
- Identified the key pitfall: Google Ads' 30-day last-click window vs. Meta's 7-day click/1-day view window makes raw conversion counts non-comparable — flagged this explicitly rather than treating "bigger number" as "better channel"
- Built a side-by-side comparison table and a stacked column chart ("Google vs. Meta Ads — Side-by-Side Efficiency")
- Delivered a reasoned budget recommendation: Meta Ads shows undervalued traffic and conversion potential and merits more spend, while Google Ads' higher ROAS on real sales means it can't be deprioritized either
- **Deliverable**: [Google vs. Meta Ads: Channel Comparison & Recommendations (Google Doc)](https://docs.google.com/document/d/1NIHchnVt4yNn_roF6VxupDZy3toeG9wWmsvWf_FJOQw/edit?usp=sharing)

### Project 5 — Break Down Shopify Data to Understand Sales
**Moving from clicks to checkout — where the real leaks are.**
- Worked with **real, anonymized Shopify checkout and product-level exports** from the Client
- Learned to calculate and interpret funnel health metrics: checkout completion rate, cart abandonment rate, and Average Order Value (AOV)
- Studied the full **19 Key Shopify Metrics** framework (Sales, Traffic, Customer, Product/Inventory) to know which numbers actually matter and which to check first (AOV + Conversion Rate + Returning Customer Rate)
- Identified high- and low-performing products and connected funnel drop-off points to specific, fixable store issues (pricing clarity, checkout friction, shipping costs)
- **Outcome**: a **Shopify Funnel Report** — moving from "we had 200 checkouts" to "checkout abandonment rose after shipping fees were added," with concrete store-level fixes attached

### Project 6 — Consolidate & Visualize the E-Commerce Funnel With Claude
**Bringing four disconnected platforms into one story — with AI as the tool, not the shortcut.**
- Confronted the core limitation of cross-platform analysis head-on: no shared user, session, or transaction ID exists across GA, Ads platforms, and Shopify — so a naive "dump it all into AI" approach fails
- Filtered every dataset down to the Client's own campaigns only, explicitly excluding two affiliated but out-of-scope brands present in the raw exports
- Used **Claude AI** to consolidate, summarize, and visualize the aligned dataset into a single cross-platform funnel dashboard
- **Key insight surfaced**: Meta Ads drives the highest traffic but the lowest conversion (candidate for retargeting); Google Ads and Bing show stronger purchase intent (Bing: 4.1% conversion; paid search sessions: 60.2% engagement) but are underinvested — recommended shifting **$1,000–$2,000** of budget toward Google Ads and Bing
- **Deliverable**: [Cross-Platform Funnel Dashboard (Claude AI Artifact)](https://claude.ai/public/artifacts/3903d819-ef34-4b31-a789-dd8c0cc16e6d)

### Project 7 — Turn Your Findings Into a Growth Strategy & Presentation
**From analysis to a story a marketing team would actually act on.**
- Reviewed the full body of work across Projects 1–6 and distilled it down to the **2–3 biggest, most defensible insights**
- Structured the presentation using a proven narrative arc: **Executive Summary → Challenge → Insights → Recommendations → Roadmap**
- Wrote action-oriented slide titles, backed each claim with the underlying chart or data point, and used AI to tighten wording and simplify complex points
- Practiced explaining the story out loud, as if presenting to the Client's actual marketing team
- **Outcome**: a business-ready growth strategy presentation connecting ad spend, analytics, and Shopify sales data into 2–3 realistic, measurable recommendations

---

## 🎓 Skills Demonstrated

`Customer Journey Mapping` `Sales Funnel Analysis` `Performance Marketing` `Google Analytics` `Google Ads` `Meta Ads` `Attribution Modeling` `Shopify Analytics` `Spreadsheet Formulas` `Data Visualization` `Cross-Platform Data Consolidation` `AI-Assisted Analysis` `Budget Allocation Recommendations` `Stakeholder Presentation` `Business Storytelling`

---

## 📊 Outcome

- Delivered a full **funnel diagnosis** spanning Google Analytics, Google Ads, Meta Ads, and Shopify — from first click to completed order
- Surfaced a concrete, data-backed **budget reallocation recommendation** ($1,000–$2,000 shift toward Google Ads and Bing) grounded in conversion rate and engagement data rather than surface-level metrics
- Identified and diagnosed **3 weak landing pages** with specific, actionable fixes, plus one referrer-spam data-quality catch that could have wasted optimization effort
- Packaged the full analysis into a **growth strategy presentation** built for a non-analyst business audience

---

*This project was completed as part of the Extern Marketing/E-Commerce Data Analysis Externship, working with real operational data from an online board game publisher and retailer. The company's identity has been withheld throughout this document per the externship's confidentiality terms. All data was handled responsibly and used solely for the learning activities within the program.*
