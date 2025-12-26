📊 Sales & Product Performance Analysis Dashboard (Power BI)
📌 Project Overview

This project focuses on analyzing sales performance, product profitability, regional trends, and the impact of discounting strategies using Microsoft Power BI.
The objective is to transform raw transactional data into actionable business insights that support data-driven decision-making.

The dashboard is designed from a Business Analyst perspective, emphasizing clarity, usability, and executive-level reporting.

🧠 Business Problem

The organization has historical sales data but lacks visibility into:

Overall business performance and profitability

High-performing and underperforming regions

Product categories and sub-categories driving profit or loss

The impact of discount strategies on profit margins

This project aims to address these gaps through interactive dashboards.

🗂️ Dataset

Source: Sample Superstore Dataset

Type: Retail sales transactional data

Key Fields:

Order Date, Ship Date

Sales, Profit, Discount

Product Category & Sub-Category

Region, Customer, Product details

🧹 Data Cleaning & Preparation

Data cleaning and transformation were performed using Power Query:

Removed non-analytical fields (Row ID)

Corrected data types for date and numeric fields

Created time-intelligence columns:

Year, Month Name, Month Number

Derived business metrics:

Profit Margin

Discount Band (No / Low / Medium / High)

Shipping Delay (Days)

Standardized text fields for consistency

📐 Data Modeling & Measures

Key KPIs were implemented using DAX measures to ensure dynamic calculations:

Total Sales

Total Profit

Total Orders (Distinct Count)

Profit Margin %

Average Order Value

All KPIs respond dynamically to slicers and filters.

📊 Dashboard Pages
🔹 Page 1: Executive Overview

Provides a high-level summary for decision-makers:

KPI cards for Sales, Profit, Margin, and Orders

Monthly Sales Trend analysis

Sales distribution by Region

Interactive slicers (Year, Region, Category)

📌 Purpose: Quick understanding of overall business performance.

🔹 Page 2: Product & Discount Analysis

Focuses on deeper operational insights:

Sales by Product Category

Profit contribution by Sub-Category

Profit Margin analysis by Discount Band

Top-performing products with conditional formatting

📌 Purpose: Identify profitability drivers and areas needing corrective action.

🔍 Key Business Insights

Strong revenue performance does not always translate into high profitability.

The West region contributes the highest share of sales, while some regions lag behind.

Technology products are major revenue drivers, while certain sub-categories operate at low or negative margins.

Higher discount bands significantly reduce profit margins, highlighting the risks of aggressive discounting.

A small number of products contribute disproportionately to total revenue (Pareto effect).

🛠️ Tools & Technologies

Microsoft Power BI

Power Query (Data Transformation)

DAX (Measures & KPIs)

Excel / CSV Data Source

🎯 Key Learnings

Importance of using DAX measures instead of raw columns for KPIs

Translating raw data into business-oriented insights

Designing dashboards that balance clarity, interactivity, and usability

Understanding how pricing and discount strategies affect profitability

📌 Use Cases

Business performance tracking

Sales and profitability analysis

Product and discount strategy evaluation

Executive reporting and decision support

🚀 Future Enhancements

Add forecasting and trend comparison

Drill-through analysis at customer level

Integration with real-time or larger datasets

👤 Author

Prathamesh Gaikwad
Final-year Computer Science Engineering student
Interested in Business Analysis, Data Analytics, and Software Development

✅ HOW TO USE THIS REPO

Download the .pbix file

Open using Power BI Desktop

Explore dashboards using slicers and filters
