# US Regional Sales Data Exploratory Data Analysis

This repository contains an exploratory data analysis (EDA) of US regional sales data. The analysis is performed using a Jupyter Notebook (`EDA.ipynb`) and covers various aspects of the sales data to uncover trends and patterns.

## Overview

The dataset analyzed contains historical sales data for 45 stores and 81 departments, spanning from `2010-02-05` to `2012-10-26`. The total revenue recorded in this dataset is `$6.74B` across `421,570` rows.

## Analysis Performed

The notebook performs the following analyses:

1.  **Data Loading and Initial Overview:**
    *   Loads the dataset from `sales data-set.csv`.
    *   Formats date columns and extracts year and month information.
    *   Provides basic statistics like the number of rows, unique stores, unique departments, date range, and total revenue.
2.  **Monthly Revenue Trend (All Stores):**
    *   Calculates and visualizes the total weekly sales aggregated by month, showing the overall revenue trend over time.
3.  **Top 10 Stores by Total Revenue:**
    *   Identifies and visualizes the top 10 stores that generated the highest total revenue.
4.  **Top 10 Departments by Total Revenue:**
    *   Identifies and visualizes the top 10 departments that generated the highest total revenue.
5.  **Average Weekly Sales: Holiday vs Non-Holiday:**
    *   Compares the average weekly sales during holiday weeks versus non-holiday weeks to assess the impact of holidays on sales.
6.  **Distribution of Weekly Sales:**
    *   Visualizes the distribution of weekly sales values using a histogram and Kernel Density Estimate (KDE) to understand the spread and skewness of the sales data.
7.  **Average Weekly Sales by Month:**
    *   Calculates and visualizes the average weekly sales for each month across all years to identify seasonal patterns.

## Requirements

To run the notebook, you will need the following Python libraries:

*   `pandas`
*   `matplotlib`
*   `seaborn`

## Usage

1.  Ensure you have the required libraries installed.
2.  Place the `sales data-set.csv` file in the appropriate directory (or update the file path in the notebook).
3.  Open and run the Jupyter Notebook to reproduce the analysis and visualizations.









**Supply Chain Analysis — Power BI Dashboard Project**

An interactive Power BI dashboard analyzing product, supplier, inventory, and logistics data to surface revenue, quality, and profitability insights across a supply chain.

📌 Overview

This project consolidates a supply chain dataset into a 4-page Power BI report, allowing stakeholders to monitor product performance, supplier reliability, logistics cost, and profitability from a single, unified view — replacing fragmented, manual spreadsheet reporting.

📊 Dataset
Metric	Value
Records (SKUs)	100
Attributes per record	27
Product categories	3 — Skincare, Haircare, Cosmetics
Suppliers tracked	5 — Supplier 1 to Supplier 5
Transportation modes	4 — Road, Rail, Air, Sea
Inspection results	3 — Pass, Fail, Pending

Key fields: product type, price, revenue, stock levels, order quantities, inspection results, defect rates, supplier name/location, production volume, manufacturing cost/lead time, shipping cost/time/carrier, transportation mode, and route.

Derived (calculated) fields: Profit Margin, Revenue Category, Shipping Efficiency.

🛠️ Tools & Methodology
Raw Data (CSV) — sourced the 100-record supply chain dataset
Power Query — cleaned, renamed, and validated columns; handled data types
Data Modeling — structured fields into product, supplier, and logistics dimensions
DAX Measures — built KPIs including Profit Margin, Revenue Category, Shipping Efficiency
Power BI Visuals — designed a 4-page interactive dashboard with synchronized slicers

Stack: Microsoft Power BI Desktop · Power Query Editor · DAX · Excel/CSV

📁 Dashboard Pages
Page	Focus
1. Executive Overview	Company-wide KPIs — revenue, units sold, shipping cost, defect rate
2. Inventory & Supplier Analysis	Stock levels, production volumes, defect/inspection breakdowns by supplier
3. Logistics & Profitability Analysis	Shipping cost/time by transport mode, profit margin, supplier lead times
4. Business Insights & Recommendations	Consolidated takeaways and recommended actions

All pages share synchronized slicers: Product Type, Supplier Name, Transportation Mode, Inspection Result.

🔍 Key Findings
Skincare generates the highest revenue (₹0.24M, ~42% of total)
Supplier 1 is the top revenue contributor and most reliable (lowest defect rate, 1.80%)
Haircare has the highest stock level (1,644 units) and highest defect rate (2.48%)
Air freight is the costliest transport mode (₹6.02/unit); Sea is cheapest (₹4.97/unit)
Cosmetics delivers the highest profit margin (99.16%)
Supplier 3 has the longest average lead time (20.13 days) — a bottleneck risk
💡 Recommendations
Focus promotional spend on skincare; investigate Supplier 1's demand drivers
Strengthen QC for Supplier 5 (highest defect rate); investigate haircare defect causes
Review haircare stock allocation and skincare manufacturing costs
Shift volume to Sea/Rail where possible; work with Supplier 3 to cut lead time
Prioritize high-margin categories such as cosmetics
⚠️ Limitations
Small sample size (100 SKU-level records)
No time dimension — single snapshot, no seasonality analysis
Simulated/synthetic cost and defect figures
No customer-level behavioral data
Static file — not connected to a live/refreshing data source
🚀 Future Scope
Connect to a live/refreshing data source for real-time monitoring
Add predictive analytics (demand/defect forecasting)
Expand dataset with a longer time period for trend analysis
Add drill-through pages for SKU- and route-level detail
Incorporate customer feedback data
📂 Files
File	Description
Supply_Chain_Analysis.pbix	Power BI report source file
supply_chain_data.csv	Raw dataset
supply_chain_clean_data.csv	Cleaned dataset with derived fields
Supply_Chain_Analysis_Report.docx	Detailed project report
Supply_Chain_Analysis_Presentation.pptx	Presentation deck
👥 Author
Abhiyuday Sharma
