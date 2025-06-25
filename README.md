# E-commerce Sales and Customer Analytics using SQL

This project involves analyzing the sales, customer behavior, product performance, and payment trends of a simulated E-commerce company using **SQL (MySQL)**.

---

## 📌 Project Objective:

To extract actionable business insights from an e-commerce sales database by performing various SQL-based analysis on customer data, orders, products, and payments.

---

## 🗃️ Dataset Description:

The dataset contains 5 main tables:

| Table Name | Description |
|------------|-------------|
| **customers** | Customer information like name, city, country, signup date |
| **products** | Product details like name, category, and price |
| **orders** | Order information such as order date, customer id, and order value |
| **order_items** | Detailed order breakdown showing products per order |
| **payments** | Payment method, status, and date for each order |

---

## ✅ SQL Skills Applied:

- Joins (INNER JOIN, LEFT JOIN)
- Aggregations (SUM, COUNT, AVG)
- GROUP BY and HAVING clauses
- Subqueries
- Common Table Expressions (CTEs)
- Window Functions (RANK, LAG, LEAD)
- Date Functions (MONTH, YEAR)

---

## ✅ Analysis Performed:

- Total and Monthly Revenue Trends
- Top Customers by Revenue
- New vs Returning Customers
- Top Selling Products and Categories
- Customer Churn Analysis (Inactive Users)
- Payment Success and Failure Rates
- Ranking Customers by Total Spend
- Month-over-Month Revenue Growth

---

## 📂 Project Files:

- **Ecommerce_SQL_Project_LargeDataset.sql** → Database schema and sample data ,All analysis queries written and executed on the dataset
- **README.md** → Project documentation (this file)

---

## ✅ How to Run This Project:

1. Open MySQL Workbench or your preferred SQL client.
2. Create a new database (Example: `ecommerce_project`).
3. Import and run the script:  
   `Ecommerce-sql-analysis.sql`
4. Once data is loaded, execute queries from:  
   `ecommerce_analysis_queries.sql`

---

## ✅ Tools Used:

- MySQL
- MySQL Workbench

---




