# Power BI E-Commerce Analytics Portfolio

A collection of **6 interactive Power BI dashboards** built for comprehensive analysis of an e-commerce platform (likely Brazilian marketplace style, based on states like SP, RJ, MG, RS and payment types like boleto/credit_card).

These reports focus on **customers**, **orders**, **products**, **sellers**, **fiscal year trends**, and **executive-level KPIs** — using clean visuals, slicers, conditional formatting, and drill-down capabilities.

## 🎯 Dashboards Overview

| # | Dashboard Name                  | Main Focus Areas                                      | Key Visuals Used                          |
|---|---------------------------------|-------------------------------------------------------|-------------------------------------------|
| 1 | Customer Analysis Dashboard     | Customer behavior, repeat rate, geographic distribution | Cards, bar charts, stacked bar, treemap-like state comparison |
| 2 | Fiscal Year Analysis            | Year-over-year orders & revenue trends, monthly/quarterly breakdown | Cards, column charts, table with YoY % change |
| 3 | Orders Summary Dashboard        | Order volume KPIs, category & state distribution, payment & status | Cards, line/bar charts, pie chart, treemap |
| 4 | Sellers Summary Dashboard       | Seller performance, late delivery, top performers     | Cards, bar charts, scatter plot, top-N tables |
| 5 | Products Summary Dashboard      | Product revenue & order contribution, category breakdown | Cards, bar charts, scatter plot, pie chart, treemap/matrix |
| 6 | Executive Summary Dashboard     | High-level KPIs + navigation to detailed pages        | KPI cards, line/area charts, bar chart, geographic map |

## ✨ Key Features & Techniques Demonstrated

- Star schema data modeling (likely Fact_Orders + dimensions: Customer, Product, Seller, Date, Location)
- DAX measures for:
  - Time intelligence (YoY %, YTD, previous year comparison)
  - Custom calculations (Repeat Customer %, Late Delivery %, Delivery Success Rate, Average Order Value)
  - Dynamic titles / conditional formatting
- Slicers & filters (Year, Fiscal Quarter/Month, Customer State, Product Category)
- Bookmarks / buttons for view switching (Normal View ↔ Top 10)
- Geographic visualization (customer states on map – focused on South America)
- Mobile-responsive layouts
- Clean color scheme with blue headers and meaningful conditional colors (green/red for growth/late)

## 🛠️ Tech Stack

- **Power BI Desktop** (2023–2025 version features used)
- **DAX** (advanced time-intelligence, context modifiers)
- **Power Query** (data cleaning, fiscal calendar likely created here)
- **Data Sources** (assumed): CSV/Excel files (Orders, Customers, Products, Sellers, Geolocation)
- Custom visuals: None (all native visuals used)
- Theme: Modern blue-based corporate look
