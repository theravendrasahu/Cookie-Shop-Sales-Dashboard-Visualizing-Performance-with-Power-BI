# Cookie Shop Sales Dashboard — Visualizing Performance with Power BI

A end‑to‑end Power BI project that models raw sales data for “Cookiewala” into an interactive, executive‑ready dashboard. The repo includes the complete PBIX file, reusable theme, and clean, well‑labeled CSV datasets so others can learn, modify, or extend the solution.

## What this project delivers
- A single Power BI report (PBIX) that tracks sales performance across time, stores, products, and employees.
- KPI tiles for revenue, orders, and goal attainment, with conditional formatting to highlight under/over‑performance.
- Drill‑downs from company to store/product level, enabling quick root‑cause analysis.
- A consistent visual identity using a custom JSON theme (Cool Green).

## Key features
- Time intelligence: month/quarter/year views, cumulative trends, and goal vs. actual comparisons powered by DAX.
- Goal tracking: Sales goals by period with variance and % to target.
- Product and store analysis: Best/worst performers, contribution analysis, and distribution across locations.
- Employee insights: Tie sales to staff for performance reviews and incentives.
- Clean navigation and “top bar” highlighting using an alternate DAX technique (documented in notes).

## Repo contents
- Power BI Dashboard.pbix — complete interactive report.
- SalesOrders.csv, SalesOrderLines.csv — transactional sales data.
- Product.csv — product master.
- Stores.csv — store/location master.
- Employees.csv — employee master.
- Date.txt — date table seed for robust time intelligence.
- Sales Goals.csv — period goals used for target vs. actual.
- Theme – Cool Green.json — custom theme for consistent styling.
- ALTERNATE DAX – highlight top bar.txt — helper notes/snippets.
- README.md — setup and usage instructions.

## Data model overview
- Star schema with SalesOrderLines as the fact table.
- Dimensions: Date, Product, Stores, Employees.
- Additional table for Sales Goals to enable target tracking and variance measures.

## DAX highlights
- Time intelligence measures (MTD/QTD/YTD).
- Variance and % to target measures.
- Dynamic titles/labels and highlight logic for the header bar.

## How to use
1. Clone or download the repository.
2. Open Power BI Dashboard.pbix in Power BI Desktop.
3. If prompted, point data sources to the included CSV files.
4. Refresh to load data and explore the report pages, slicers, and drill‑downs.

## Customization ideas
- Replace CSVs with a live database or dataflow.
- Extend the date table and goals for rolling targets.
- Add profitability (costs/margin) or inventory pages.
- Localize the theme or branding to match an organization.

## Purpose
This project serves as a practical template for building retail/consumer sales analytics in Power BI—ideal for portfolios, learning advanced DAX/time intelligence, and demonstrating dashboard design best practices.
