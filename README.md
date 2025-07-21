# 🪑 Furniture Sales Analysis Dashboard

## 📌 Overview
This project explores sales data from a furniture retailer using Microsoft Excel to uncover insights into revenue performance, profitability, and customer purchasing behavior. The project simulates aspects of a BI dashboard and also draws parallels with SQL-style data querying.

## 📊 Objectives
- Analyze sales and profit trends by product category and region.
- Identify the most profitable and least profitable product lines.
- Evaluate customer segments and their impact on revenue.
- Calculate shipping duration and its influence on sales.

## 🗂️ Dataset Structure
- **Order Info:** Order ID, Order Date, Ship Date, Ship Mode
- **Customer Info:** Name, Segment, Region
- **Product Info:** Category, Sub-Category, Product Name
- **Metrics:** Sales, Quantity, Profit, Duration

## 🛠 Tools & Skills Used
- **Microsoft Excel**
  - Pivot Tables & Slicers
  - IF, TEXT, MONTH, VLOOKUP
  - Conditional Formatting
  - Charts (Column, Line, Pie)
- **SQL Concepts Applied**
  - Aggregations (SUM, AVG)
  - Filtering (WHERE conditions)
  - Grouping (GROUP BY Category, Region)
  - Date parsing (`MONTH(Order Date)`)

## 💡 Key Insights
- Chairs and tables are top-selling items but not always the most profitable.
- West region dominates sales; however, the East shows higher profit margins.
- Most sales come from the "Consumer" segment, followed by "Corporate."
- Orders shipped within 3–5 days have better profit margins.

## 📁 Files Included
- `Furniture Sales.xlsx`: Raw and processed data
