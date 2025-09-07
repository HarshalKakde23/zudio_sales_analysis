# 🛍️ Zudio Retail Sales Analytics — SQL Project

This project analyzes retail sales data from Zudio stores using SQL. The goal is to extract actionable insights related to store performance, customer behavior, product trends, and revenue generation.

---

## 📊 Project Overview

This SQL project answers **17 key business questions** using data from tables such as:

- `zudio_sales_items`
- `zudio_sales`
- `zudio_stores`
- `products`
- `customers`

The analysis provides insights like:

- Top-performing stores and cities  
- Best-selling products and categories  
- Customer demographics and loyalty trends  
- Payment method preferences  
- Average transaction and basket sizes

---

## 📁 Dataset Structure

Assumed tables:

- **`zudio_sales`**: Sale metadata (store, customer, date, payment)
- **`zudio_sales_items`**: Line items (product, quantity, unit_price)
- **`products`**: Product details (name, category, price)
- **`zudio_stores`**: Store information (name, city)
- **`customers`**: Customer demographic data (age, city, etc.)

---

## 📌 Key Business Questions Answered

| #   | Question                                                                 |
|-----|--------------------------------------------------------------------------|
| 1   | What is the total revenue generated per store?                          |
| 2   | Which product category generates the highest total sales in ₹?         |
| 3   | Which store has the highest average sales per transaction?             |
| 4   | What is the monthly sales trend across all stores?                     |
| 5   | What are the total sales made in each city?                            |
| 6   | Which are the top 5 best-selling products by quantity and revenue?     |
| 7   | Which products have the lowest total quantity sold?                    |
| 8   | What is the total quantity sold for each product category?             |
| 9   | What is the average unit price of products in each category?           |
| 10  | Which age group spends the most money on average?                      |
| 11  | How many unique customers visited each store?                          |
| 12  | Which customers made the most purchases?                               |
| 13  | What is the average number of items bought per customer?               |
| 14  | Which cities have the highest number of loyal customers (>5 purchases)?|
| 15  | Which payment mode is used the most overall and per store?            |
| 16  | What is the average transaction value by payment mode?                 |
| 17  | What is the average basket size (number of items) by store and city?   |

---

## 🧰 Technologies Used

- **SQL** (PostgreSQL / MySQL compatible)
- **Database**: Any SQL-compatible DBMS (e.g., MySQL, PostgreSQL, SQLite)
- **Optional**: Power BI / Tableau / Excel (for visualization)

---

## 🚀 How to Use

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/zudio-retail-sales-sql.git
Load the database:

Import CSV files or use a SQL dump to create and populate tables.

Run the SQL queries:

Use any SQL editor (e.g., DBeaver, MySQL Workbench, pgAdmin).

Run queries individually or all at once.

Analyze results:

Review insights in the console or export to your visualization tool.

📈 Sample Insights
Mumbai stores generate the highest revenue.

Casual wear is the best-selling category.

The 25–34 age group spends the most on average.

UPI and Wallets are the most-used payment methods.

---

## 📊 Power BI Dashboard

This project includes a fully interactive Power BI dashboard that visualizes key sales and customer insights from the SQL analysis.

### 🔍 Key Dashboard Features:
- Total revenue by store and city
- Monthly sales trends
- Best-selling products and categories
- Customer age group spending analysis
- Most used payment methods
- Loyal customer distribution by city

📂 Folder Structure

zudio-retail-sales-sql/

├── README.md
├── analysis_queries.sql
└── data/
    ├── zudio_sales.csv
    ├── zudio_sales_items.csv
    ├── customers.csv
    ├── products.csv
    └── zudio_stores.csv
✅ Requirements
SQL-compatible database (e.g., MySQL, PostgreSQL)

SQL editor like DBeaver, pgAdmin, MySQL Workbench, etc.

Optional: Data visualization tools (Power BI, Tableau, Excel)

📜 License
This project is licensed under the MIT License.

🙌 Acknowledgments
Thanks to the Zudio-style retail sales structure and analytics KPIs for guiding this SQL analysis project.


---
