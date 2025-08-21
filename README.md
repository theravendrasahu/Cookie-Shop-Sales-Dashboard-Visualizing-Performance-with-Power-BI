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

[1] https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/images/70547786/d5782d97-c130-4b51-8a16-841dfded27f8/image.jpg?AWSAccessKeyId=ASIA2F3EMEYE7BNS7W4U&Signature=nhqXfs5sBe%2BQBh8WJb%2FsIcCAjTQ%3D&x-amz-security-token=IQoJb3JpZ2luX2VjEKP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLWVhc3QtMSJIMEYCIQC9tMJJK5XtbuyDRd2tU9SE422kLIMnI%2BkcP4rdQ8hEKwIhAL%2BKfHMeC%2BIRLTQnSBkJxSilzr6y9aKdETAx316%2FnsI1KvoECOz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQARoMNjk5NzUzMzA5NzA1Igzi%2F03FA9uC8WAdOBkqzgSrgM5igNii3aSWk1Pi9qI6Z9nZkaqzFqFukw6BEoakF5%2FgPwi9kgMdDHQedRkuubnSc2kBcI0vrs2uv5N0dyJQiVYL07JPWo2w3fHVQJ5z6%2Bfk6i8mKvx1Xkg%2BhmtahntK5VE8QX4nBcI5c0gGQdSSa0TJFz8pEj153ya5nLG48fCgSY2HwK3PZGLbb1tE9FimQJ4yIDWGGvooRBhsuW6%2BC%2FrbIhkIQk%2BvWOVGsVzhsUz0bkVauQ6rn5q6xz%2Ftyip%2FGw8dPMeJu39Eh0nPJtIwXvOmttlYPAucl%2BhpwcnCEFtU26rOYme5nQMcf27jiC5MYQgkz6cMVAXqxaD56MMYHwbVRCxT342SkyGjxo8ua1B3ePtFLaq5YoSzMZjUV5LeNEDJP8ej2WdJV6mJ1hYnWwy3O7M2A0p01Bk5BDsCF3uv%2BVZanZJI05ffnzN3fCAfllhtmGei9RS0xHYmLZf6xzkqZscBFnGFYLSXj1YExINCOCQGJWpapgysHi7hd4INhYKKTuT3I04X3e6hyuVRsOdDUMGgkstoSFiuH3TXyO%2Bkko%2Fak5i1J1Ot7zpKYmVaW%2BOGO6DP8xnAPHQY8wFKgVlSBFd3y9Oen2Rpmc%2B0oy6EyI1GmtAorYjQtXKfRBr0jyxSgdVLJVc8eb8p1Rlf7gbVZXsXNpztic5ioaCMeLI6sbEKI%2B1LZffT97SwO02Ro5glDldQg0Z0KIZFbjIqVtqwX7WFxz%2BNmaRBk1RnDgoyEceBnqf4Af3Qv%2B9hKL%2FkjZ78SQfATV3b%2FiF3BTCB75vFBjqZATbtprnCjw8fbJUwjaVe5SznDCBgfxHiwLtoWkkKVLP130GcqzQigSJC9K5Car0fSuaeDRv0Ng%2F8ef1viXKvx462RiUP22BuuCzv2R4FsrslP94rugfZ22bKV3EA2PljLck1%2BPwXuVof%2FQUyR9wSEUXADJA%2BRHrVTOxiuFzWPyjdrgsDLa0TQl1Z8voGvyxNb6cTV118R1Gbdg%3D%3D&Expires=1755774313
