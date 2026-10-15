# Google Play Store App Market Strategy: Tableau Visual Analytics

Leveraging Tableau Dashboard Storytelling Across 10,800+ Android Apps to Optimize Development, Conversion, and Revenue Models.

---

## Executive Diagnostics and Overview
An end-to-end Tableau data pipeline analyzing category dynamics, pricing thresholds, app size elasticity, and user rating sentiment across 10,841 Android application profiles.

### Key Performance Benchmarks
- Total App Profiles: 10,841 standardized records
- Freemium Store Share: 92.6% of apps are free, capturing 98.4% of total download volume
- Rating Threshold: Apps rated 4.2 or above capture 85%+ of total store downloads
- Payload Sensitivity: Binaries under 30MB yield 2.4x higher conversion in emerging markets

---

## Tableau Data Architecture
- Tableau Prep Pipeline: Standardized install intervals (10K+ to 1B+) and converted text strings into numerical MB measures.
- Calculated Fields: Built weighted rating scores, estimated total revenue (Installs * Price), and log-scale download indexes.
- Interactive Parameters: Enabled dynamic filtering by category groups, price tiers ($0.99-$2.99, $3.00-$9.99, $10.00+), and minimum review counts.

---

## Core Market Insights

### 1. Downloads Across Price Tiers (Log Scale)
- Free applications average 13.5M+ downloads.
- Low-cost paid apps ($0.99-$2.99) drop to 145,000 installs, highlighting immediate payment friction.
- Higher paid tiers ($3.00-$9.99 @ 38,000 installs; $10.00+ @ 1,500 installs) show steep drop-offs suitable only for specialized enterprise tools.

### 2. Category Opportunity Grid
- Family & Casual (~20%) and Game (~15%) categories occupy ~35% of total listings (~3,800 apps), indicating high saturation.
- Finance, Health & Fitness, and Productivity sectors represent high-intent Blue Oceans with favorable install-per-app metrics.

### 3. Review Velocity and Social Proof
- Review volume is identified as the primary driver of organic store ranking.
- Reaching 10,000+ positive reviews creates a viral organic acquisition loop.

---

## Category Performance Matrix

| Category Sector | Avg App Size | Avg Rating | Monetization Model | Tableau Opportunity Score |
| :--- | :--- | :--- | :--- | :--- |
| Game | 64.3 MB | 4.28 / 5.0 | In-App Purchases (IAP) + Ads | High Revenue Target |
| Finance | 28.1 MB | 4.13 / 5.0 | Freemium Subscriptions | High LTV Growth |
| Health & Fitness | 31.5 MB | 4.25 / 5.0 | Monthly Tiered Plans | Strategic Opportunity |
| Tools & Utilities | 18.2 MB | 4.04 / 5.0 | In-App Ad Network | Volume Growth |
| Family & Casual | 42.7 MB | 4.19 / 5.0 | Hybrid Ad & Micro-IAP | High Saturation |

---

## Product Growth Roadmap

- Q1 - Lightweight Build: Engineer app binaries under 30MB to eliminate download abandonment.
- Q2 - ASO and Rating Prompts: Implement milestone-triggered review prompts to maintain a 4.2+ rating.
- Q3 - Hybrid Monetization: Launch free installs alongside in-app purchases and tiered subscriptions.
- Q4 - Tableau Story Monitoring: Connect live Tableau dashboards to monitor rating sentiment shifts and category trends.

---

## Repository Structure
```text
├── data/
│   └── googleplaystore_tableau_dataset.csv
├── tableau_files/
│   ├── Google_Play_Store_Tableau_Analytics_Working_File.xlsx
│   └── Google_Play_Store_Tableau_App_Strategy.twbx
├── screenshots/
│   └── google_play_tableau_dashboard_clean.png
├── presentation/
│   └── Google Play Store Tableau Analytics.pptx
└── README.md
