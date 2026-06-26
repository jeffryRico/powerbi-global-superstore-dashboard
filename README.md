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

