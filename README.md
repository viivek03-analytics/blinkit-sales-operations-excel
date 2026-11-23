# Blinkit Quick-Commerce Sales & Dark Store Analytics (Excel)

## Business Overview
An end-to-end Excel analytics project evaluating order revenue, dark store delivery efficiency, and product category performance across **Tier 1, Tier 2, and Tier 3** cities for **Blinkit** (600 orders across 6 outlets).

## Executive Dashboard Preview
![Blinkit Executive Dashboard](blinkit-dashboard.png)

## Data Cleaning & Modeling Highlights
- **Data Standardization:** Cleaned inconsistent raw labels (`LF`, `low fat`, `reg`) in `Raw_Data` into standardized `Low Fat` and `Regular` categories using `TRIM`, `LOWER`, and `IF` formulas.
- **SLA Tracking:** Built calculated columns for **Total Sales** and **Delivery SLA Status** (`On-Time <=15m` vs `Delayed (>15m)`).
- **Dynamic Aggregations:** Automated category, city-tier, outlet-format, and monthly trend summaries using `SUMIF`, `COUNTIF`, and `AVERAGEIF`.

## Key Analytical Insights
- **Top Revenue Categories:** `Fruits & Vegetables` and `Dairy & Breakfast` generate the highest GMV share, requiring priority dark-store cold-chain allocation.
- **Dark Store Speed Advantage:** Medium-sized Dark Stores achieve fast average delivery times with strong customer ratings, outperforming traditional Grocery Stores.
- **Tier 2 Growth Potential:** Tier 2 outlets deliver strong order volume and healthy average order values, highlighting clear ROI for dark-store expansion.

## Repository Contents
- `Blinkit_Sales_Operations_Analytics.xlsx` — Multi-tab Excel workbook (`Executive_Dashboard`, `Summary_Analysis`, `Cleaned_Data`, `Raw_Data`)
- `blinkit-dashboard.png` — Snapshot of the final executive dashboard
-
