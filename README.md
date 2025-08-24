## Blinkit-Analysis

# 📌 Overview

This project is a comprehensive analysis of Blinkit grocery sales data, aimed at understanding sales trends, outlet performance, and customer behavior.
The analysis has been carried out across three platforms: Python (Data Cleaning & EDA), SQL (Query-based Analysis), and Power BI (Interactive Dashboard).

# 🎯 Goal

The main objectives of this project are:

To clean and preprocess raw Blinkit grocery data for consistent analysis.

To extract business insights using SQL queries.

To visualize sales, outlet, and item-level performance with Power BI dashboards.

To demonstrate a complete end-to-end analytics workflow combining Python, SQL, and Power BI.

# 📊 Data Source

File: BlinkIT Grocery Data.xlsx

Size: ~8500 rows, 12 columns

Columns include:

🔹Item Identifier, Item Type, Item Fat Content

🔹Outlet Identifier, Outlet Type, Outlet Size, Outlet Location Type

🔹Outlet Establishment Year, Sales, Rating, Item Weight, Item Visibility

# 🛠️ Tech Stack

🔹Python: pandas, numpy, matplotlib, seaborn, openpyxl

🔹SQL: PostgreSQL 17 (queries for KPIs & aggregations)

🔹Power BI: Interactive dashboard design & visualization

🔹Data Source: Kaggle (BlinkIT Grocery Dataset)

# ⚡ Features
1️⃣ Python (Data Cleaning & EDA)

🔹Cleaned Item_Fat_Content field for consistency (LF, low fat → Low Fat, reg → Regular).

🔹Standardized column names for SQL compatibility.

🔹Exploratory Data Analysis: distributions, correlations, missing value handling.

🔹Exported clean dataset for SQL and Power BI usage.

2️⃣ SQL (Business KPIs & Query Analysis)

🔹KPIs: Total Sales, Average Sales, Number of Orders, Average Rating.

Detailed Analysis:

🔹Sales by Fat Content

🔹Sales by Item Type

🔹Sales by Outlet Size & Location

🔹Sales Trends by Establishment Year

🔹Pivot-style analysis of Fat Content by Outlet Type

🔹Combined Outlet Metrics (Sales, Ratings, Visibility)

3️⃣ Power BI (Dashboard & Visualization)

🔹Designed an interactive dashboard with filters and slicers.

Visuals included:

--> Bar Charts → Item Type & Outlet Type Sales

--> Pie Charts → Outlet Size Contribution to Sales

--> Line Charts → Sales over Establishment Years

--> Stacked Bar Charts → Fat Content by Location

--> Cards & KPIs → Total Sales, Avg Sales, Avg Rating, Orders

# 📈 Process Workflow

🔹Data Cleaning (Python)

--> Load raw Excel file

--> Standardize column names & categorical values

--> Handle missing values

🔹Data Analysis (SQL)

--> Import dataset into PostgreSQL

--> Run KPI queries

--> Perform detailed aggregations & pivot-style analysis

🔹Data Visualization (Power BI)

--> Import cleaned dataset

--> Create measures (DAX) for KPIs

--> Build interactive dashboard for end-users

# 🚀 Outcome

🔹Identified top-performing item categories (Fruits & Vegetables, Snack Foods).

🔹Found Medium-sized outlets contribute ~42% of total sales.

🔹Tier 3 locations lead in overall sales.

🔹Established trends show higher sales in more recently established outlets.

🔹Created a full pipeline: Data → Cleaning → SQL Insights → Power BI Dashboard.
