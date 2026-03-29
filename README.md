# Store Sales Power BI Dashboard

## Overview
An interactive sales dashboard built in Power BI using 
the Superstore dataset (9,800 rows). Analyzes sales 
performance across regions, categories and years.

## Dashboard Features
- KPI cards: Total Sales, Order Count, Avg Order Value
- Sales trend by year (2015-2018)
- Sales breakdown by Category and Sub-Category
- Regional performance comparison
- Interactive slicers for Year and Region
- Drill-through to Region Detail page
- Advanced hover tooltips with mini charts

## Tools Used
- Power BI Desktop
- DAX (Data Analysis Expressions)
- Power Query (M language)

## Dataset
Superstore Sales dataset from Kaggle
Rows: 9,800 | Columns: 18

## Key DAX Measures
- Total Sales = SUM(Orders[Sales])
- Order Count = DISTINCTCOUNT(Orders[Order ID])
- Sales YoY Growth = (current - previous) / previous

## Preview
![Dashboard Preview](dashboard-preview.png)