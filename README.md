📊 Sales Performance & Trend Analysis Dashboard (Power BI)
📌 Project Overview

This project involves building an enterprise-style Sales Performance & Trend Analysis Dashboard using Power BI Desktop.
The dashboard helps analyze sales, profit, quantity, and target achievement across time, regions, categories, and products, enabling data-driven decision-making.

🎯 Objectives

Analyze overall sales performance

Track sales and profit trends over time

Compare actual sales vs targets

Identify top-performing and underperforming categories and regions

Enable interactive analysis using slicers (user controls)

🗂️ Data Sources

All data is sourced from Excel files, which act as the single source of truth.

Excel Files Used

FactSales.xlsx – Transaction-level sales data

DimDate.xlsx – Date dimension (2019–2025)

DimProduct.xlsx – Product hierarchy

DimCustomer.xlsx – Customer details

DimRegion.xlsx – Geographic information

Targets.xlsx – Monthly sales targets

🔄 Data Preparation (Power Query)

Data transformation was performed using Power Query Editor:

Corrected data types (Date, Numeric, Text)

Removed duplicates and ensured clean schema

Converted Excel serial dates into proper Date format

Ensured one-row-per-day in the Date dimension

🧩 Data Model Design

A Star Schema was implemented for optimal performance and clarity.

Fact Table

FactSales

Dimension Tables

DimDate

DimProduct

DimCustomer

DimRegion

Targets

Relationships

One-to-Many relationships from dimensions to FactSales

DimDate marked as the official Date table

Targets linked via Year for time-based comparison

🧮 DAX Measures Created

Key measures were created using DAX for reusable and efficient calculations.

Core Measures

Total Sales

Total Profit

Total Quantity

Time Intelligence

Sales YTD

Sales LY

YoY Growth %

Target Analysis

Target Sales

Target Achievement %

📈 Report Pages & Visuals
1️⃣ Executive Dashboard

KPI Cards: Total Sales, Total Profit, YoY Growth %

Donut Chart: Sales by Category

Ribbon Chart: Category Rank Over Time

Line Chart: Monthly Sales Trend

2️⃣ Trend Analysis

Line Chart: Sales vs Profit

Line & Column Chart: Actual Sales vs Target Sales

Map Visual: Sales by Region (bubble size represents sales)

3️⃣ Product Performance

Matrix: Category → Subcategory → Product

Conditional formatting for Sales & Profit

Top N products by sales

🎛️ User Controls (Interactivity)

User interaction is enabled using Slicers:

Year

Region

Category

These slicers allow users to dynamically filter data across all report pages.

🧠 Key Insights Enabled

Identify trends and seasonality in sales

Monitor target achievement across time

Compare performance across regions and categories

Drill down into product-level performance

💾 File Structure
Sales_Performance_Analysis.pbix
DimDate.xlsx
DimProduct.xlsx
DimCustomer.xlsx
DimRegion.xlsx
FactSales.xlsx
Targets.xlsx
README.md

🚀 Tools & Technologies

Power BI Desktop

Power Query

DAX

Microsoft Excel

✅ Conclusion

This dashboard provides a scalable, interactive, and professional solution for analyzing sales performance.
It follows industry best practices in data modeling, DAX, and visualization design.

🧑‍💻 Author

Bandaru Kaushik
