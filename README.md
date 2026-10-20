The Business Problem
E-commerce businesses often struggle to identify which product categories actually drive their revenue and when their peak sales seasons occur. This project provides a complete Python pipeline that cleans raw transaction data, calculates total revenue, and generates an interactive dashboard to help business owners make data-driven inventory and marketing decisions.

What This Project Demonstrates
If you have a messy dataset and need a clean, interactive dashboard, this project shows my exact workflow:
- Data Wrangling: Merging multiple messy tables and handling dates, missing values, and duplicates.
- Feature Engineering: Creating new metrics like Total Revenue to uncover hidden business value.
- Interactive Dashboards: Building web-based Plotly charts that allow clients to hover, zoom, and filter data without writing code.

Project Overview
- Dataset: 100,000+ orders from the Olist Brazilian E-Commerce public dataset.
- Tools Used: Python (Pandas, NumPy), Plotly.
- Output: An interactive HTML dashboard showing Top 10 Revenue Categories and Monthly Revenue Trends.

Key Insights Uncovered
- The Cash Cow: The beleza_saude (Health & Beauty) and relogios_presentes (Watches & Gifts) categories generate the highest revenue.
- Seasonal Peaks: Revenue peaked massively in November 2017 (Black Friday effect), showing the importance of seasonal inventory planning.
- Logistics Impact: Freight costs eat into a significant portion of revenue, meaning logistics optimization is key for profitability.

How to Review This Project
- Interactive Dashboard: Download the ecommerce_dashboard.html file and open it in any web browser to interact with the charts.
- The Code: View the olist_analysis.ipynb notebook to see the exact Python code used for data cleaning and visualization.
- The Data: The olist_cleaned_data.csv is the cleaned dataset, ready for Pivot Tables in Excel or Power BI.
