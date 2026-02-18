# Sales-Dashboard-Project
Power BI Sales Performance Dashboard Project

**Project Overview**

This project analyzes a sales dataset of 1000+ records to understand business performance, identify profit trends, and generate actionable insights using Power BI, SQL, and Excel.

The goal was to transform raw sales data into a professional interactive dashboard that helps businesses make data-driven decisions.

**Objectives**

Analyze overall sales and profit performance

Identify top-performing regions and product categories

Track monthly sales trends

Detect loss-making products

Create interactive business dashboards

**Tools & Technologies Used**

Power BI — Data visualization & dashboard creation

SQL — Data analysis & aggregation queries

Excel — Data cleaning and preprocessing

**Key Business Insights**

Identified highest revenue-generating regions

Found most profitable product categories

Discovered loss-making products

Observed seasonal sales trends

**Dashboard Preview**
![Dashboard Screenshot](<img width="1142" height="642" alt="Screenshot jpg" src="https://github.com/user-attachments/assets/a586cec6-9b89-45b8-9064-35e2ad9852cd" />)

**Sample SQL Queries Used**
**Total Sales**
SELECT SUM(Sales) FROM sales;
**Profit by Category**
SELECT Category, SUM(Profit)
FROM sales
GROUP BY Category;


