\# BrewMetrics BI



Business Intelligence solution for BrewMetrics Coffee Co.



\## Project Overview



This project analyzes BrewMetrics Coffee Co. sales data

using Power BI and a star-schema data model.



\## Data Model



\### Fact\_Sales



Contains transaction-level sales data:



\- Date

\- City

\- Store Format

\- Category

\- Item

\- Quantity

\- Unit Price

\- Sales Amount



\### Dim\_Date



Contains date-related information.



\### Dim\_City



Contains city information.



\### Dim\_Product



Contains product and category information.



\## DAX Measures



\- Total Sales

\- MoM Sales Growth

\- Running Total Sales

\- Product Rank

\- Average Sales per Transaction



\## Dashboard



The dashboard provides:



\- Total sales

\- City-level sales comparison

\- Cold Brew monthly trend

\- Product sales ranking

\- City slicer

\- City → Store Format drill-down



\## Key Insights



1\. Cold Brew sales show a noticeable seasonal pattern

&#x20;  during April and May.



2\. Bengaluru shows stronger sales performance than the

&#x20;  other cities in the dataset.



3\. Product-level sales ranking helps identify the

&#x20;  highest-performing products.

