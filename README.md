# Retail Store Inventory Management—Data Analytics Project

> **Tools Used:** Microsoft Excel · SQL · Power BI  
> **Domain:** Retail & Supply Chain Analytics  
> **Dataset:** 73,100 records | 5 Stores | 2 Years (2022–2024)

---
## Business Problem

Retail businesses lose billions every year due to poor inventory management—either running out of stock (lost sales) or holding too much stock (wasted capital). The management team of this 5-store retail chain identified the following critical pain points:

Frequent stockouts in high-demand categories are leading to lost revenue and customer dissatisfaction.
Excess inventory in slow-moving products is tying up working capital and increasing warehousing costs.
Inaccurate demand forecasting means stores are either over-ordering or under-ordering without a data-driven basis.
Promotions are not delivering ROI—discounts are being offered without clarity on whether they actually drive volume.
Regional performance gaps exist, but the root cause (supply issue vs. demand issue) is unknown.
No centralized visibility—store managers lack a single dashboard to monitor inventory health across regions, categories, and seasons.


## Project Objective: Analyze 2 years of retail inventory data across 5 stores to identify stockout and overstock risks, evaluate demand forecast accuracy, assess the impact of promotions and seasonality on sales, and deliver an interactive dashboard that gives management real-time visibility into inventory health—enabling smarter restocking decisions and reducing revenue leakage.



## Project Overview

This end-to-end data analytics project simulates a real-world retail inventory management scenario across a chain of 5 stores operating in 4 regions (North, South, East, West). The goal was to extract actionable business insights from raw transactional inventory data using industry-standard tools — Excel for data cleaning & exploration, SQL for querying & aggregations, and Power BI for interactive dashboards.

The project demonstrates proficiency in the full analytics pipeline: **data cleaning → exploratory analysis → SQL querying → business reporting → visual storytelling**.

---

## Dataset Description

Date - Transaction date
Store ID - Store identifier
Product ID - Unique product identifier
Category - Product category (Groceries, Electronics, Clothing, Toys, Furniture)
Region - Store region (North, South, East, West)
Inventory Level - Current stock on hand (units)
Units Sold - Units sold on that date
Units Ordered - Replenishment order placed
Demand Forecast - Predicted demand
Price - Selling price
Discount - Discount percentage applied
Weather Condition - weather
Holiday/Promotion - Binary flag — 1 if holiday/promo day
Competitor Pricing - Competitor's price for same product
Seasonality - Season


## Tools & Techniques Used

### Microsoft Excel
- Data cleaning and validation (checked for nulls, type mismatches, duplicates)
- Pivot Tables for category-wise and region-wise sales summaries
- Conditional formatting to flag low inventory and overstock rows
- Calculated columns: Revenue = Units Sold × Price etc.

### SQL
- Database ingestion of CSV into relational tables
- Aggregation queries: `SUM`, `AVG`, `COUNT`, `GROUP BY` for category & region analysis
- Filtering with `WHERE` clauses to isolate stockout/overstock risk records
- Window functions (`RANK`, `PARTITION BY`) for store-level performance ranking
- `CASE WHEN` logic to classify inventory health (Healthy / Low / Overstock)

### Power BI
- Connected to cleaned dataset and built a multi-page interactive dashboard
- KPI cards: Total Revenue, Total Units Sold, Avg forcaste accuracy, overstock count
- Slicers: Filter by Region, Category, Store
- Visuals: Clustered bar charts, donut charts, line trend charts
- Published report for stakeholder sharing

## About This Project

This project was built as part of a **Data Analytics Portfolio** to demonstrate hands-on skills with real-world business data. The dataset simulates a retail chain environment and the analysis follows industry-standard practices used by supply chain and retail analysts.