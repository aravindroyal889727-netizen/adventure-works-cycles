# adventure-works-cycles
End-to-end sales analysis project using MySQL, Excel, Power BI, and Tableau — solving the same business requirements across all four tools.
# Adventure Works Cycles – End-to-End Sales Analysis

A 3-week, 4-module project solving the same business requirement set — laid out in `Questionnaire.xlsx` — using MySQL, Excel, Power BI, and Tableau.

## Timeline

| Week | Module | Folder |
|---|---|---|
| Week 1 | Excel | `01-excel/` |
| Week 2 | SQL (MySQL) + Tableau | `02-sql-tableau/` |
| Week 3 | Power BI | `03-powerbi/` |

## What this project covers
- Data merging and lookups across sales, product, customer, and territory tables
- Date-dimension fields: Year, Month, Quarter, Financial Month/Quarter, Weekday
- Calculated Sales Amount, Production Cost, and Profit fields
- Pivot tables, bar/line/pie/combination charts, and KPI dashboards
- Performance breakdowns by Product, Customer, and Region

## Folder contents

**`01-excel/`**
- `Adventure_Works_Cycles.xlsx` — full workbook with pivot tables, formulas, and charts

**`02-sql-tableau/`**
- `00_analysis_build_script.sql` — **start here.** The full documented build, question by question (Q0–Q13): combining sales tables, joining product/customer/date dimensions, calculating Sales Amount, Production Cost, Profit, and Profit Margin, then year/month/quarter/region/country/top-5 breakdowns and the final dashboard view.
- `dim_customer.sql`, `dim_date.sql`, `dim_product.sql`, `dim_product_subcategory.sql`, `dim_sales_territory.sql` — source dimension tables
- `fact_internet_sales.sql`, `fact_internet_sales_new.sql`, `sales_combined.sql`, `sales_product.sql`, `sales_date.sql`, `final_table.sql`, `final_dashboard.sql` — intermediate and final tables produced by the build script
- `routines.sql` — stored routines/procedures used in the analysis
- Tableau workbook not included here — add your `.twbx` file to this folder if you have one.

**`03-powerbi/`**
- `Adventure_Works_Cycles.pbix` — Power BI dashboard file

**`Questionnaire.xlsx`** — the business requirement questions this project answers, common across all four modules

## Tools used
`MySQL` `Microsoft Excel` `Power BI` `Tableau`

## Author
Ayya Aravind — [LinkedIn](https://linkedin.com/in/aravind-ayya-3133a039a) · [GitHub](https://github.com/aravindroyal889727-netizen)
