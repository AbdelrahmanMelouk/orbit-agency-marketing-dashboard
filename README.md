# Orbit Agency: Marketing Performance Dashboard

> **Data Drives Growth**
> An interactive dashboard that turns marketing data into better campaign decisions. Explore performance across channels, audiences, and campaigns in one place.

---

## Overview

**Orbit Agency Dashboard** is a multi-page marketing analytics report built on a dataset of **200,000 campaign records**. It gives marketing teams and executives a fast way to see what is working, where the budget goes, and which audiences and campaigns deliver the best return.

The report uses a dark, neon-styled UI with a left-hand navigation bar and a global **date filter (Last 30 Days)**.

---

## Pages

### 1. Home
The landing page with a welcome banner and four quick-access cards that link to the main sections: **Executive**, **Channel**, **Audience**, and **Campaign**.

### 2. Executive
A high-level view of overall performance.

| KPI | Value shown |
|---|---|
| Average ROI | 5.00 |
| Marketing Spend | 3B $ |
| Total Impressions | 1.10 B |
| Total Clicks | 110.0 M |
| Average CTR | 14.04% |

**Visuals**
- **Total ROI**: donut chart by audience segment
- **Conversion Rate**: share by target audience (about 20.2% overall)
- **Conversion Rate by Channel**: bar chart (Email, Google Ads, Website, Facebook, YouTube)
- **Average of ROI**: trend line over time

### 3. Channel
Marketing Channels Executive Dashboard (6 active channels).

- **KPI cards**: average cost per channel, best ROI, best CTR, best conversion rate
- **Channel Data Mining & Insight**: an auto-generated insight on the best and most cost-efficient channels
- **Share of Spend by Channel**: Email, Google Ads, Instagram, Facebook, Website
- **Conversions by Channel**: bar chart
- **Cost Efficiency by Audience**: bubble chart of acquisition cost vs. ROI
- **Channel Performance Summary**: card per channel with average score

### 4. Audience
Audience Champions & Personas (200,000 total records, 25 personas).

- **Top performers**: highest ROI, highest CTR, top conversion, lowest cost, each with its top persona
- **Total CPC**: donut chart by audience group (Women 25-34, Women 35-44, Men 18-24, Men 25-34, All Ages)
- **Top Customer Segments Performance**: Foodies, Outdoor Adventurers, Tech Enthusiasts, Health & Wellness, Fashionistas
- **Cost Efficiency by Audience**: ROI vs. cost scatter
- **Audience Cost Breakdown**: spend ranking per audience group

### 5. Campaign
Campaign Performance Executive Summary (200,000 total campaigns).

- **KPI cards**: average cost per campaign, best ROI, best CTR, best conversion rate, lowest CPC
- **Performance Insight**: text summary of which campaign type leads
- **Campaigns by Location**: Miami, New York, Chicago, Los Angeles, Houston
- **Campaign Distribution**: share by type (Influencer, Search, Display, Email)
- **Conversion Rate Performance**: ranked campaign types
- **Performance Pulse & Insights**: campaign execution rate and an AI recommendation

---

## Key Metrics Explained

| Metric | Meaning |
|---|---|
| **ROI** | Return on investment |
| **CTR** | Click-through rate (clicks ÷ impressions) |
| **CPC** | Cost per click |
| **Conversion Rate** | Share of clicks or engagements that become conversions |
| **Acquisition Cost** | Cost of acquiring one customer |
| **Impressions** | Number of times an ad or campaign was viewed |

---

## Dimensions

- **Channels**: Email, Google Ads, Instagram, Facebook, Website, YouTube
- **Audiences**: Men 18-24, Men 25-34, Women 25-34, Women 35-44, All Ages
- **Campaign types**: Influencer, Search, Display, Email, Social Media
- **Locations**: Miami, New York, Chicago, Los Angeles, Houston
- **Personas**: Foodies, Outdoor Adventurers, Tech Enthusiasts, Health & Wellness, Fashionistas

---

## Tools & Tech

> Update this section to match your actual stack.

- BI tool: Power BI *(the ribbon in the screenshots suggests this)*
- Data prep: Power Query
- Measures: DAX
- Design: custom dark theme, background images, and custom icons

---

## Project Structure

```
orbit-agency-dashboard/
├── data/                 # Raw and cleaned datasets
├── report/               # Dashboard file (.pbix)
├── assets/               # Backgrounds, logo, icons
├── screenshots/          # Page previews
└── README.md
```

---

## Getting Started

1. Clone or download this repository.
2. Open the dashboard file from the `report/` folder.
3. If prompted, point the data source to the dataset in the `data/` folder and refresh.
4. Use the left navigation bar to move between pages, and the date filter to change the time range.

---

## Screenshots

| Home | Executive |
|---|---|
| ![Home](screenshots/home.png) | ![Executive](screenshots/executive.png) |

| Channel | Audience | Campaign |
|---|---|---|
| ![Channel](screenshots/channel.png) | ![Audience](screenshots/audience.png) | ![Campaign](screenshots/campaign.png) |

---

## Key Insights

- Channel performance is spread fairly evenly: each channel takes roughly 17% of total spend.
- Influencer campaigns lead on ROI and conversion, while Display has the lowest CPC.
- Spend and conversion are close to evenly split across audience groups, so the differences between segments are small.
- The dashboard recommends scaling Search budget to increase conversion velocity.

---

## Author

Abdelrahman Melouk

GitHub: https://github.com/AbdelrahmanMelouk
LinkedIn: https://www.linkedin.com/in/abdelrahman-melouk

---

## License

This project is shared for portfolio and educational purposes.

© Abdelrahman Melouk
