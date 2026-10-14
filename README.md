# Amazon PPC Campaign Analysis & Optimization

## Project Overview

This project analyzes Amazon Sponsored Products advertising data for a skincare brand to identify wasted ad spend, evaluate campaign performance, and recommend data-driven optimization strategies.

Using Microsoft Excel, I cleaned and validated advertising data, calculated key PPC performance metrics, built PivotTable-based analyses and a dashboard, and developed an action list to help improve advertising efficiency and profitability.

## Business Objectives

- Identify search terms generating advertising spend without orders.
- Evaluate campaign performance across match types and ad placements.
- Compare advertising costs against product-level break-even ACOS.
- Identify profitable search terms and opportunities to scale.
- Recommend actions to reduce wasted spend and improve return on advertising investment.

## Tools & Technologies

- **Microsoft Excel**
- PivotTables and PivotCharts
- Excel formulas and lookup functions
- Conditional formatting and data validation
- KPI dashboards and data visualization

## Data Cleaning & Preparation

The original dataset contained approximately 3,000 advertising records. The cleaning process included:

- Removing blank rows and duplicate records.
- Standardizing dates, SKUs, search terms, match types, and regional fields.
- Correcting identified date and SKU inconsistencies.
- Converting text-formatted sales and spend values into numeric data.
- Recalculating PPC metrics instead of relying on pre-filled values.
- Documenting data-quality issues and decisions in a Cleaning Log.

## Key Metrics

| Metric | Formula | Purpose |
|---|---|---|
| CTR | Clicks ÷ Impressions | Measures how often impressions lead to clicks |
| CPC | Spend ÷ Clicks | Measures average cost per click |
| ACOS | Spend ÷ Sales | Measures advertising cost relative to attributed sales |
| ROAS | Sales ÷ Spend | Measures sales generated per unit of ad spend |
| CVR | Orders ÷ Clicks | Measures the percentage of clicks converting into orders |
| Break-even ACOS | (Selling Price − Product Cost − Amazon Fees) ÷ Selling Price | Estimates the maximum advertising cost ratio before product contribution is exhausted |
| Profit After Ads | Units × (Selling Price − Product Cost − Amazon Fees) − Spend | Estimates contribution after product costs, fees, and ad spend |

## Analysis Performed

### 1. Campaign Performance
Compared spend, attributed sales, orders, ACOS, ROAS, and profit after advertising across campaigns.

### 2. Match-Type Analysis
Evaluated Auto, Broad, Exact, Phrase, and Product targeting to understand differences in advertising efficiency.

### 3. Placement Analysis
Compared performance across Top of Search, Rest of Search, and Product Pages.

### 4. Search-Term Analysis
Identified high-spend search terms with zero orders, reviewed search-term efficiency, and highlighted potentially irrelevant queries.

### 5. Weekly Trend Analysis
Compared weekly advertising spend, sales, orders, ACOS, and conversion rate to identify performance changes during the reporting period.

### 6. Action List
Organized optimization recommendations using the rules provided in the assignment, including wasted-spend review, profitable-term scaling, high-ACOS bid adjustments, and competitor-brand term review.

## Key Findings

- Overall advertising performance was approximately **32.88% ACOS** and **3.04 ROAS** in the analyzed dataset.
- Some search terms accumulated substantial spend without generating orders, making them priorities for review.
- Performance varied across campaigns, match types, and placements.
- Product-level break-even ACOS provided a profitability benchmark beyond revenue and ROAS alone.
- Data-quality exceptions required validation before making certain optimization decisions.

## Recommendations

1. Review high-spend search terms with zero orders and consider bid reductions or negative keywords where appropriate.
2. Reduce bids on converting search terms whose ACOS exceeds the product's break-even ACOS.
3. Gradually scale search terms that consistently generate orders at comfortably profitable ACOS levels.
4. Reallocate budget toward campaigns with stronger profit and advertising efficiency.
5. Monitor weekly performance and investigate unusual metric values before making significant changes.
6. Validate missing product costs, negative-spend records, and anomalous click-through rates before final decisions.

## Data Limitations

- Missing product cost or fee information can limit profit calculations for affected records.
- Unusual CTR values and negative-spend records require source validation.
- Attributed sales represent advertising-attributed sales, not necessarily total business revenue.
- Estimated savings from optimization are potential savings, not guaranteed outcomes.
- Recommendations should be validated against current campaign settings and business context before implementation.

## Project Deliverables

- Cleaned advertising dataset
- Cleaning Log documenting data-quality issues
- Campaign, match-type, placement, search-term, and weekly analyses
- PPC KPI calculations
- Search-term Action List
- Excel dashboard and visual summaries

## Conclusion

This project demonstrates how Excel-based data cleaning, metric calculation, performance analysis, and dashboard reporting can support practical Amazon PPC optimization. By focusing on profitability, reducing wasted spend, and making decisions based on validated data, sellers can improve advertising efficiency and allocate budgets more effectively.

---

**Skills Demonstrated:** Data Cleaning · Microsoft Excel · PivotTables · KPI Analysis · Dashboard Development · Business Analysis · Data-Driven Decision Making
