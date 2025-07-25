#  Maven Market Sales & Returns Dashboard

This project contains a Power BI dashboard created for Maven Market, focusing on transaction analytics, brand profitability, return patterns, and geographic sales insights. The interactive visualizations are designed to help stakeholders quickly understand business performance at both macro and micro levels.

---

##  Dashboard Overview

The dashboard is split into two primary pages:

---

## Page 1: **Top Brands Performance & Regional Summary**

<img width="1146" height="762" alt="page 1" src="https://github.com/user-attachments/assets/33f28ea0-120b-4df6-8d3e-536650bc721b" />


This page gives a high-level overview of the business's overall performance and product-level insights.

### Key Metrics:
- **Total Transactions:** `270K`
- **Total Profit:** `₹ 1,053K`
- **Total Returns:** `7K`

### Top 30 Product Brands
A tabular breakdown of top-performing brands based on:
- **Total Transactions**
- **Total Profit**
- **Profit Margin**
- **Return Rate**

## Notable Insights:
- *Horatio*, *Hermano*, and *Nationeel* are the highest-profit brands.
- Brands with higher profit margins (>60%) include *Nationeel*, *Fast*, *Better*, and *Big Time*.
- Return rates are generally below 1.5%, showing strong product satisfaction.

### Map Visualization
An interactive geographic heatmap showing transaction density across:
- **USA**
- **Mexico**
- **Canada**

This helps identify where most transactions are concentrated geographically.

### Country Performance (Tree Map)
A color-coded area chart breaks down transactions by:
- Country (USA dominates)
- Volume contribution of Mexico and Canada

### Revenue Trend (Line Graph)
Revenue by month visualized over time:
- Strong growth seen post-January 1998
- Monthly revenue stabilizes around ₹90–₹110K

### KPI Gauge
Displays latest monthly revenue against maximum capacity.

---

## Page 2: **Product Brand Deep Dive – Horatio Apple Fruit Roll**

<img width="1242" height="767" alt="page 2" src="https://github.com/user-attachments/assets/caef8eb4-b46e-4bce-b8fa-96f74352b8d5" />


This page zooms into the brand "Horatio Apple Fruit Roll", analyzing its performance in the current month.

### Current Month KPIs:
- **Transactions:** `393` (Goal: 377, +4.24%)
- **Profit:** `₹ 1.66K` (Goal: ₹ 1.59K, +4.54%)
- **Returns:** `13` (Goal: 14, -7.14%)

### Pie Charts:
- **Return vs Transaction Ratio**: 3.3% return rate, 96.7% successful transactions.
- **Cost vs Revenue Split**: ₹18.2K cost vs ₹43.79K revenue

### Regional Distribution Map:
A detailed map showing where Horatio brand products are performing:
- High density in **California**, **Washington**, **Mexico City**, and **Guadalajara**
- Includes markers for each selected region across **USA**, **Mexico**, and **Canada**

---

## 🔧 Tools Used
- Power BI for data visualization
- DAX for calculated KPIs and metrics
- Microsoft Bing Maps integration for geospatial analysis
