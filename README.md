# ApnoMart Q2 2026 Executive Dashboard

**Created by:** Divya Dalvi
**Tool:** Microsoft Power BI

## Project Overview

This project analyzes 1,200 ApnoMart sales records to identify revenue
trends, profitability patterns, regional performance, customer behavior,
and payment preferences. The dashboard is built for executives who need
a quick, interactive view of business performance.

## Dashboard Preview

![Dashboard](dashboard.png)

## Dashboard Features

- KPI cards: Total Sales, Total Profit, Total Orders, Profit Margin %
- Sales by Category
- Monthly Sales Trend
- Profit by Region
- Sales by Customer Segment
- Sales by Payment Method
- Discount vs Profit analysis
- Interactive Region slicer

## Key Metrics

| Metric | Value |
|---|---|
| Total Sales | [e.g. 3.75M] |
| Total Profit | [e.g. 1.01M] |
| Total Orders | [your value] |
| Profit Margin % | [e.g. 26.9%] |

## DAX Measures

Total Sales = SUM('apnomart-sales-data'[Sales])
Total Profit = SUM('apnomart-sales-data'[Profit])
Total Orders = [your final formula]
Profit Margin % = DIVIDE([Total Profit], [Total Sales], 0)

## Key Insights

1. **Revenue:** [Top category] generated the highest sales at [value],
   about [x]% of total revenue.
2. **Profitability:** [Best region] earned the most profit ([value]),
   while [worst region] earned the least ([value]).
3. **Customer Behavior:** The [top segment] segment contributes [x]% of
   sales, and [top payment method] is the most used payment method
   ([x]%).

## Strategic Recommendation

[Finding] -> [Action] -> [Expected benefit]

Example structure: Increase marketing and inventory for [top category]
in [best region], and reduce heavy discounts on low-margin products to
protect profit while keeping revenue growing.

## Files in this Repository

- `dashboard.png` - dashboard screenshot
- `ApnoMart_Executive_Insights.pdf` - insights document
- `ApnoMart_Dashboard.pbix` - Power BI file
- `README.md` - project documentation

## Tool Used

Microsoft Power BI Desktop
