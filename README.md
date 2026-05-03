# Nykaa Marketing Campaign Performance Dashboard
### Power BI | 55,555 Records | 4 Pages
---

## 📽️ Dashboard Walkthrough — Watch This First

> **Don't just read — see it in action.**

🎥 **[Click here to watch the full dashboard walkthrough](https://www.loom.com/share/c3173eec93a44069a7c6c0da274a34ba)**

*A complete video walkthrough of all 4 pages — business insights, DAX measures explained, and key findings.*

---
---

Was looking for a dataset online to build a dashboard. Found a Nykaa campaign dataset on Kaggle — 55,555 rows, 16 columns, good enough to calculate a lot of things. So I got to work.

---

## How I Approached It

Sat with the data before opening Power BI. Went through every column. Asked myself — if I was a marketing analyst here what would i want to know.

That became the dashboard.

Kept the design clean — dark background, Nykaa pink, white text.

---

## Page by Page

**Page 1 — Campaign Overview**
Five KPI cards up top. Revenue, ROI, Clicks, Conversions, Acquisition Cost. Anyone who opens this knows the full picture in 5 seconds. Below that a scatter plot — Revenue vs Acquisition Cost by Campaign Type. Social Media sits top left, low cost high revenue. Email sits bottom right, opposite story. Interactive slicer at the bottom lets you filter everything by campaign type with one click.

**Page 2 — Performance Trends**
Monthly conversion line chart across the full year. Everything looks normal until June — conversions crash 65% from 5M to 1.8M. That anomaly jumped out immediately. Below that a Cost Per Lead chart built using a custom DAX measure — Total Acquisition Cost divided by Total Leads. Didn't exist in the raw data. Had to build it.

**Page 3 — Customer Segment Analysis**
Waterfall chart showing revenue contribution by customer segment. Premium Shoppers at the top. Senior Customers at the bottom. The gap is clear and the growth opportunity is clear. Donut chart showing regional revenue split — all four regions contribute roughly equally at 25% each. Balanced reach nationally.

**Page 4 — Strategic Insights & Recommendations**
Most dashboards stop at the visuals. This page pulls the key findings together, ties specific recommendations to each one, and documents the source and tools.

---

## What I Took Away

The insight is always more important than the visual. Anyone can drag a chart onto a canvas. The hard part is knowing what it's telling you and what to do about it.

Also — the ROI column in this dataset was pre-calculated inconsistently and didn't match the actual revenue and cost figures. Spotting that and calling it out honestly was one of the more useful things about this project.

---

## Tools

Power BI Desktop — DAX — Excel — Canva — Kaggle

---

## Repo Structure

| Folder | Contents |
|--------|----------|
| [Dashboard](./Dashboard) | PBIX file + PDF export |
| [Data](./Data) | Kaggle CSV dataset |
| [Image Preview](./Image%20Preview) | Screenshots of the report |

---

*Jacinth Samuel CK | 2026*
