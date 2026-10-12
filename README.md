# Superstore Sales Interactive Dashboard

An Excel-based sales analytics project built with the Sample Superstore dataset. The workbook demonstrates data cleaning, analysis with Pivot Tables, advanced Excel formulas, and dashboard-style reporting.

## Project Overview

- **Project:** Superstore Sales Interactive Dashboard
- **Workbook:** `chandan_ExcelDashboard.xlsx`
- **Dataset:** Sample Superstore dataset (inspired by publicly used Superstore datasets)
- **Tools:** Microsoft Excel, Excel Tables, Pivot Tables, formulas, charts, conditional formatting
- **Reporting period noted in workbook:** 2021–2023

## Dashboard Preview

![Dashboard KPI snapshot](screenshots/01_dashboard_kpis.png)

> These preview images are documentation visuals generated from the values and summary tables in the workbook. Open the Excel workbook to view the original dashboard and charts.

## Charts and Tables

### Sales and Profit by Region

![Sales and profit by region](screenshots/02_sales_profit_by_region.png)

The dashboard summary compares regional sales and profit. The West region has the highest sales in the displayed summary.

### Sales by Category

![Sales by category](screenshots/03_sales_by_category.png)

This chart compares Technology, Furniture, and Office Supplies sales.

### Monthly Sales Trend

![Monthly sales trend](screenshots/04_monthly_sales_trend.png)

The monthly trend view helps compare sales and profit across the months shown in the dashboard.

### Top 5 Profitable Sub-Categories

![Top profitable sub-categories table](screenshots/05_top_profitable_subcategories.png)

The table highlights the five sub-categories listed as most profitable in the workbook.

## Workbook Structure

| Sheet | Purpose |
|---|---|
| `Instructions` | Project brief, tasks, and weightage |
| `Raw_Data` | Original dataset with intentional data-quality issues for cleaning practice |
| `Cleaned_Data` | Prepared data for analysis |
| `Pivot_Tables` | Summaries by region and other business dimensions |
| `Advanced_Formulas` | Examples of lookup formulas, IF logic, and related formula practice |
| `Dashboard` | KPI summary, regional/category/segment analysis, monthly trend, and key insights |

## Key KPIs Shown in the Workbook

| KPI | Value |
|---|---:|
| Total Sales | $2,297,201 |
| Total Profit | $286,393 |
| Total Orders | 9,994 |
| Average Order Value | $229.86 |
| Profit Margin | 12.5% |
| Total Quantity | 37,874 |

*Values above are copied from the workbook's Dashboard sheet; rounding follows the displayed dashboard.*

## Key Insights Listed in the Workbook

- The West region leads in sales.
- Technology is shown with the highest profit margin among the categories.
- The Consumer segment contributes the largest share of sales among the listed segments.
- The workbook recommends reviewing discounts on low-margin products, especially Tables.

## Excel Skills Demonstrated

- Importing and organizing tabular data
- Cleaning and preparing data
- Creating Pivot Tables and summarized views
- Using advanced formulas such as lookup and conditional logic
- Presenting KPIs and charts for business reporting
- Documenting workbook structure and analytical findings

## How to Use

1. Download or clone this project folder.
2. Open `chandan_ExcelDashboard.xlsx` in Microsoft Excel (or a compatible spreadsheet application).
3. Review `Instructions` first.
4. Explore `Raw_Data` and `Cleaned_Data` to understand the preparation steps.
5. Review `Pivot_Tables` and `Advanced_Formulas`.
6. Open `Dashboard` to view the summary and visual analysis.

## Repository Layout

```text
Superstore-Sales-Dashboard/
├── chandan_ExcelDashboard.xlsx
├── README.md
└── screenshots/
    ├── 01_dashboard_kpis.png
    ├── 02_sales_profit_by_region.png
    ├── 03_sales_by_category.png
    ├── 04_monthly_sales_trend.png
    └── 05_top_profitable_subcategories.png
```

## Notes

- The screenshots in this README are generated preview images based on the dashboard's summary values; they are not direct screen captures of the Excel application.
- For GitHub, keep the `screenshots` folder in the same repository as `README.md` so the images render correctly.
