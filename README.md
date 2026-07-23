# FMCG-Financial-Performance-Budget-Variance-Analysis

# Project Overview

This project delivers an end-to-end financial performance and budget variance analysis for a Nigerian FMCG distribution company selling across six regions and four channels. Built entirely from a structured Excel star schema dataset covering two full fiscal years (2023 and 2024), the project examines revenue attainment, gross margin performance, operating expense control, and net profit delivery against budget across 10 products and 3 product categories.

The analysis spans 24 months (January 2023 – December 2024) and is designed to answer two core business questions: where did performance deviate from plan, and is the business improving year on year?

# Tools & Technologies
Microsoft Excel : dataset generation, star schema design, data cleaning, feature engineering, change log and data dictionary documentation

Power BI Desktop : star schema model, DAX measures, time intelligence, dashboard design

Power Query (M) : data type enforcement and column validation across all five tables

DAX : 30+ measures covering revenue, COGS, gross profit, opex, net profit, variance, YoY comparison, and time intelligence

# Dataset Attribute
Records: 1,440 rows × 37 columns

Grain	One row per product per region per month

Time period	January 2023 – December 2024 (24 months)

Products:10 SKUs across Home Care, Personal Care, Food & Beverage

Regions:	6 Nigerian regions — South West, South East, South South, North West, North Central, North East

Channels: Retail, Wholesale, E-Commerce, Direct

Financial columns per row — budget and actual side by side:
Revenue, COGS, Gross Profit, Operating Expenses, Net Profit — each with a corresponding variance column and variance percentage column. 37 columns total covering the full P&L structure at SKU-region-month level.


# Key Findings

Headline Performance — 2023
Total actual revenue in 2023 came in at ₦77.8M against a budget of ₦80.3M — a shortfall of approximately ₦2.5M representing a 3% miss. Net profit of ₦16.1M fell short of the ₦17.9M budget — a 10.1% underdelivery. Gross margin held steady at a healthy level, indicating the revenue shortfall was the primary driver of net profit underperformance rather than cost overruns.

Headline Performance — 2024
Revenue improved to ₦85.3M in 2024 — a 9.6% year-on-year increase from 2023 — but still missed the ₦87.9M budget by 2.9%. Net profit of ₦17.8M similarly missed the ₦19.6M budget while showing a 10.4% YoY improvement on 2023. The pattern of consistent budget misses across both years suggests the budget-setting process may be systematically optimistic rather than performance being structurally weak.

Product Performance
Indomie Noodles and Maggi Seasoning Cubes are the consistent outperformers — both carry a performance factor above 1.1 and beat budget across most months in both years. Sunlight Dish Soap and Vaseline Body Lotion are the chronic underperformers — both carry factors below 0.90 and miss budget in the majority of months. These two products represent the highest-priority area for commercial review.

Category Performance
Food & Beverage generates the highest revenue volume driven by the high transaction frequency of Indomie and Maggi. Home Care shows the widest variance spread — Omo overperforms while Sunlight and Ariel underperform — suggesting the category has internal polarisation rather than a uniform performance story. Personal Care sits between the two, broadly tracking budget with modest underperformance from Vaseline.

Regional Performance
South West (Lagos) dominates revenue contribution at approximately 35% of total volume — consistent across both years. North East (Borno) is the smallest region at 7% volume with the most volatile variance. The North/South split reveals the South generates roughly 62% of total revenue against 38% from the North — a distribution worth monitoring for geographic over-concentration risk.

Seasonality
December is the strongest month in both years — seasonal factor of 1.25 — driven by festive demand across all categories. Q4 is consistently the best-performing quarter. January and February are the weakest months — lowest seasonal factor at 0.85 and 0.80 respectively. This pattern is stable across both years and should inform the budget-setting cadence.

YoY Growth
Revenue grew 9.6% from 2023 to 2024. Net profit grew 10.4% YoY. Gross margin percentage remained stable — indicating cost of goods was managed proportionally with volume growth. The business is growing but the gap between budget and actual has not closed — the budget is growing faster than the business's ability to deliver against it.

DAX Measures Library

30+ measures organised into six folders in the Power BI model:

Revenue
Total Budget Revenue, Total Actual Revenue, Revenue Variance, Revenue Variance %, Revenue Attainment %, Revenue YTD, Budget Revenue YTD, Revenue PY, Revenue YoY Change, Revenue YoY %

COGS
Total Budget COGS, Total Actual COGS, COGS Variance

Gross Profit
Total Budget Gross Profit, Total Actual Gross Profit, Gross Profit Variance, Gross Profit Variance %, Actual Gross Margin %, Budget Gross Margin %

Opex
Total Budget Opex, Total Actual Opex, Opex Variance, Opex Variance %

Net Profit
Total Budget Net Profit, Total Actual Net Profit, Net Profit Variance, Net Profit Variance %, Actual Net Margin %, Budget Net Margin %, Net Profit PY, Net Profit YoY %

Performance
Outperform Count, Critical Count, Underperform Count, Top Product, Top Region, Best Month
