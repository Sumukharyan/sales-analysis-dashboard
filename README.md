# Sales Analysis Dashboard

An interactive Excel dashboard analyzing 4 years of US Superstore retail sales data — built with PivotTables, PivotCharts, and slicers to surface trends, category performance, and regional gaps.

## Business Problem
Retail leadership needs a fast, self-serve way to see how sales are trending, which categories and regions are winning or lagging, and where to focus attention next quarter — without opening raw transaction data or waiting on a custom report each time.

## Dataset
US Superstore Sales dataset (Kaggle) — 9,800 order-line records, 18 columns, spanning January 2015 to December 2018. Includes order/ship dates, customer, region, product category/sub-category, and sales value.

## Tools Used
Excel — PivotTables, PivotCharts, Slicers & Timeline, SUMIFS-based KPI formulas, data cleaning (Text to Columns, TRIM, Remove Duplicates).

## Approach
- Cleaned raw data: standardized inconsistent date formats, trimmed whitespace from text fields, filled one missing postal code, and added Year/Month/Month-Year helper columns for grouping.
- Structured the cleaned data as an Excel Table so all downstream PivotTables and charts auto-expand.
- Built three PivotTables answering distinct business questions: monthly sales trend, top-performing categories, and region × category breakdown.
- Converted each into a PivotChart (line, horizontal bar, stacked column) with insight-driven titles.
- Added Category and Region slicers plus an Order Date timeline, connected across all three PivotTables so one click filters the whole dashboard.
- Built 6 KPI cards (Total Sales, Total Orders, Average Order Value, Top Category, YoY Growth, Repeat Customer Rate) with live formulas, plus two original KPIs not in the base tutorial: YoY growth and repeat customer rate.

## Key Findings
- Total sales reached **$2.26M** across **4,922 orders** (avg order value **$459**), growing from $479.9K in 2015 to $722.1K in 2018 — a **20.3% jump in 2018 alone**.
- Q4 is consistently the strongest quarter every year; Q4 2018 sales were up **18.8% YoY**, pointing to a seasonal holiday pattern worth planning inventory around.
- **Technology** is the top category ($827.5K), but Furniture ($728.7K) and Office Supplies ($705.4K) trail closely — no single category dominates the business.
- The **South region underperforms significantly**: $389K vs. $710K in the West — a 45% gap despite having a full customer base.
- **98.4%** of customers placed more than one order, indicating a loyal, repeat-purchase customer base rather than one-time buyers.

## Recommendation
Prioritize a targeted South-region sales push ahead of Q4, and rebalance Office Supplies inventory away from low-velocity sub-categories (Fasteners, Labels) toward Technology and Furniture, which are compounding faster.

## Screenshots

<img width="1749" height="681" alt="image" src="https://github.com/user-attachments/assets/55c77a3d-63a4-4ca2-bc7b-6acfe7c15165" />
