# Excel PivotTable Basics: Superstore Sales Analysis

**Internship:** Veda Technology, Data Analytics Track
**Task:** 24, Excel PivotTable Basics (Level 1, Day 24)
**Intern:** Rathod Harshvardhansinh J

## Objective
Build quick summaries of sales data using Excel PivotTables.

## Description
Create PivotTables for sales by category, region, and month using the Superstore dataset.

## Tools Used
- Microsoft Excel

## Dataset
- Superstore-style sales dataset, 1,000 orders, 2025-2026 (`Superstore_Sample.csv`)

## Approach
1. Loaded the Superstore dataset into Excel and cleaned it: removed duplicates, fixed data types, and made sure the date columns were real dates.
2. Converted the data into an Excel Table so the PivotTable source range updates automatically.
3. Built three PivotTables:
   - **Sales by Category**: Category and Sub-Category in rows, Sum of Sales (and Profit) in values.
   - **Sales by Region**: Region in rows, Sum of Sales in values.
   - **Sales by Month**: Order Date grouped by Month and Year in rows, Sum of Sales in values.
4. Added a chart to each PivotTable for quick reading.
5. Wrote short insights from each summary.

## Deliverables
- 3 PivotTables (`Superstore_PivotTables.xlsx`)
- Short insights (see below)

## Key Insights
- **Category:** Technology is the top category in both sales (577,621) and profit (93,864).
- **Region:** South leads in sales (301,646); Central is the lowest (225,706).
- **Month:** July 2025 was the best month (61,531) and February 2025 the weakest (33,026).
- Discounts of 20-30% reduce profit sharply. See `insights.md` for details.

## Interview Notes
- **Why use PivotTables?** They summarise large datasets quickly without formulas. You can group, filter, and re-arrange the data by dragging fields.
- **What is a PivotTable source range?** The block of cells or Excel Table the PivotTable reads from. Using an Excel Table keeps it updating as rows are added.

## Repository Structure
```
excel-pivottable-basics/
├── README.md
├── Superstore_PivotTables.xlsx
├── Superstore_Sample.csv
└── insights.md
```

## Outcome
Three PivotTables summarising Superstore sales by category, region, and month, with short insights drawn from each.
