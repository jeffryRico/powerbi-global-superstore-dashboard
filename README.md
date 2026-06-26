# Global Superstore Sales & Profit Analysis | Power BI

# Overview

This project presents an end-to-end Business Intelligence solution built with Power BI using the Global Superstore dataset.

The objective was to transform raw sales data into meaningful business insights through data modeling, DAX calculations, and interactive dashboards for executive decision-making.

The project includes data cleaning, star schema modeling, KPI development, and interactive reports focused on sales performance, profitability, and customer behavior.

# Business Objectives

* Analyze overall sales performance.
* Evaluate business profitability.
* Identify top-performing and low-performing products.
* Understand customer purchasing behavior.
* Compare performance across markets and business segments.
* Evaluate the impact of discounts on profitability.

# Technologies Used

* Power BI Desktop
* Power Query
* DAX (Data Analysis Expressions)
* Star Schema Data Modeling
* ETL Process
* Data Visualization

# Data Model

The report follows a Star Schema design.

## Fact Table
* Orders

## Dimension Tables
* Calendar
* People
* Returns
* Order Table

Relationships were optimized using one-to-many relationships to improve model performance and scalability.

# Dashboards

## 1) Executive Dashboard

1) Provides a high-level overview of business performance.

## KPIs

* Total Sales
* Total Profit
* Profit Margin
* Total Orders
* Total Quantity
* Average Order Value

## Visualizations

* Monthly Sales Trend
* Sales by Market
* Profit by Category
* Profit by Sub-Category
* Sales by Country

## 2) Profitability Analysis

Focused on understanding business profitability.

## KPIs

* Total Profit
* Profit Margin
* Unique Products
* Average Discount

## Visualizations

* Top 10 Most Profitable Products
* Top 10 Least Profitable Products
* Profit by Market
* Profit Distribution by Segment
* Discount Impact on Profit (Scatter Plot)
* Product Detail Table

## 3) Sales & Customer Analysis

Focused on customer behavior and sales performance.

## KPIs

* Total Sales
* Total Orders
* Average Order Value
* Unique Customers

## Visualizations

* Top 10 Customers by Sales
* Sales by Category
* Sales Distribution by Segment
* Sales by Country
* Monthly Sales Trend
* Customer Detail Table

# Key DAX Measures

Total Sales 
Total Profit 
Total Orders 
Total Quantity 
Profit Margin % 
Average Order Value 
Average Discount 
Unique Customers

# Key Business Insights

* Technology products generated the highest sales.
* Consumer was the largest customer segment.
* Higher discounts were associated with lower profitability.
* APAC was one of the highest-performing markets.
* A small group of products generated a significant portion of total profit.

# Dashboard Preview

## Executive Dashboard

<img width="1378" height="776" alt="image" src="https://github.com/user-attachments/assets/95e0ddbd-f21d-4989-aacc-349d8dda6bbb" />

## Profitability Analysis

<img width="1377" height="772" alt="image" src="https://github.com/user-attachments/assets/1acfc2c8-8e62-4c19-9c52-f47c0779bd20" />

## Sales & Customer Analysis

<img width="1378" height="770" alt="image" src="https://github.com/user-attachments/assets/27edb95c-1dfc-45de-b0e8-5b513a0e6fcd" />

# Repository Structure

powerbi-global-superstore-dashboard 
│ 
├── Dashboard.pbix 
├── README.md 
├── images 
│ ├── executive-dashboard.png 
│ ├── profitability-analysis.png 
│ └── sales-customer-analysis.png 
└── dataset

# Skills Demonstrated

* Data Cleaning
* ETL
* Data Modeling
* DAX
* Power Query
* Business Intelligence
* Dashboard Design
* KPI Development
* Executive Reporting
* Data Visualization

# Author

Jeffry David Rico Castiblanco
Mechanical Engineer | Data Analyst | Power BI Developer | Full Stack Developer

LinkedIn:
https://www.linkedin.com/in/jeffry-rico/

GitHub:
https://github.com/JeffryRico
