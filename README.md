Rogith28-E-Commerce-Dashboard-Excel-SQL-and-Power-BI

Power BI Dashboard

Due to GitHub's file size limits, the PBIX file is hosted externally.

Download the Power BI file here:
https://1drv.ms/u/c/69556de2cfa39c4b/IQAxciV7_kZcQZtrsaV5v4ODAar7UFbgprV5wNRwjSwQakg?e=6BsV0D

E-Commerce Analytics Dashboard | SQL Server + Power BI
📌 Project Overview

This project demonstrates an end-to-end Business Intelligence solution using Microsoft Excel, SQL Server, and Power BI. The workflow includes data extraction, transformation, loading (ETL), SQL-based data management, data modeling, DAX calculations, and interactive dashboard development to analyze sales, customers, products, and order performance.

🎯 Project Objectives
Analyze overall sales performance.
Monitor customer demographics and purchasing behavior.
Evaluate product performance and category-wise revenue.
Track order status, including completed, pending, and cancelled orders.
Build interactive dashboards for business decision-making.
🛠️ Tech Stack
Microsoft Excel – Raw data source
SQL Server (SSMS) – Database creation and SQL queries
Power BI Desktop – Data modeling, DAX, and dashboard development
📂 Dataset

The project uses three relational tables:

Customers
Customer ID
Customer Name
Gender
City
State
Email
Phone Number
Products
Product ID
Product Name
Category
Price
Orders
Order ID
Customer ID
Product ID
Order Date
Quantity
Sales Amount
Order Status
🔄 ETL Process
Extract
Imported data from Microsoft Excel.
Transform
Removed duplicate records.
Handled missing values.
Standardized gender, category, and order status values.
Corrected data types.
Validated primary and foreign keys.
Cleaned text values using Excel and Power Query.
Load
Loaded cleaned data into SQL Server.
Connected SQL Server to Power BI.
🗄️ Data Model

The project follows a Star Schema.

Customers
     │
     │
Orders
     │
Products

Relationships

Customers (1) → Orders (*)
Products (1) → Orders (*)
📊 Dashboard Pages
📈 Page 1 – Executive Sales Dashboard

KPIs

Total Sales
Total Orders
Total Customers
Total Quantity Sold
Average Order Value

Visuals

Monthly Sales Trend
Sales by Category
Top Products
Sales by State
Revenue Distribution
👥 Page 2 – Customer Insights Dashboard

KPIs

Total Customers
Male Customers
Female Customers
Repeat Customers
Average Revenue per Customer

Visuals

Customer Distribution by Gender
Top Customers by Sales
Customers by State
Customers by City
Customer Details
📦 Page 3 – Product & Order Performance Dashboard

KPIs

Total Products Sold
Completed Orders
Pending Orders
Cancelled Orders

Visuals

Orders by Status
Top Selling Products
Revenue by Product
Category-wise Sales
Order Details
📐 DAX Measures

Some key DAX measures used in this project:

Total Sales
Total Orders
Total Customers
Average Order Value
Repeat Customers
Total Quantity Sold
Sales YTD
Sales MTD
Male Customers
Female Customers
💡 SQL Concepts Used
SELECT
WHERE
ORDER BY
GROUP BY
HAVING
INNER JOIN
LEFT JOIN
RIGHT JOIN
FULL OUTER JOIN
Aggregate Functions
Primary Key & Foreign Key Relationships
📈 Business Insights
Identified top-performing products.
Analyzed customer purchasing behavior.
Compared male and female customer distribution.
Tracked sales trends over time.
Evaluated cancelled, pending, and completed orders.
Measured revenue by category and location.
📷 Dashboard Preview

Add screenshots of each dashboard page here.

Example:

images/
│── Executive_Sales_Dashboard.png
│── Customer_Insights_Dashboard.png
│── Product_Order_Dashboard.png
📁 Repository Structure
E-Commerce-Analytics-Dashboard/
│
├── Dataset/
│   └── ECommerce_SQL_PowerBI_Tables.xlsx
│
├── SQL/
│   ├── Create_Database.sql
│   ├── Create_Tables.sql
│   └── SQL_Queries.sql
│
├── PowerBI/
│   └── E-Commerce Dashboard.pbit
│
├── Images/
│   ├── Sales_Dashboard.png
│   ├── Customer_Dashboard.png
│   └── Product_Dashboard.png
│
└── README.md
🚀 Key Skills Demonstrated
Data Cleaning (ETL)
SQL Server Database Design
Relational Data Modeling
Power BI Data Modeling
DAX Calculations
Interactive Dashboard Design
Business Analytics
Data Visualization
KPI Reporting
👤 Author

Rogith Kumar

If you found this project useful, feel free to ⭐ the repository and connect with me on LinkedIn.
