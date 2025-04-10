# 📊 E-Commerce Sales Analytics with SQL

This project analyzes an e-commerce dataset using PostgreSQL. It uncovers valuable business insights like top-performing product categories, customer behavior, and sales trends over time.

## 🧠 Business Goal

> Identify which product categories are driving the most revenue, understand customer purchase behavior, and forecast sales trends.

---

## 🔧 Tools Used

- **PostgreSQL**: Data cleaning and analysis
- **SQL**: Data aggregation, window functions, and trend analysis

---

## 📂 Dataset Columns

| Column           | Type         | Description                          |
|------------------|--------------|--------------------------------------|
| order_id         | VARCHAR(15)  | Unique ID for each order             |
| order_date       | DATE         | Date of order                        |
| product_category | VARCHAR(100) | Product category                     |
| sales_amount     | FLOAT        | Revenue generated per order          |
| quantity         | INT          | Number of units sold                 |
| customer_id      | VARCHAR(15)  | Unique ID for each customer          |

---

## ✅ Project Workflow

1. **Data Validation**
   - Checked for duplicate `order_id`s ✅
   - Verified absence of nulls and incorrect formats ✅

2. **Exploratory Data Analysis**
   - Revenue and quantity by product category
   - Market share by category
   - Top customers by sales and quantity
   - Customer Lifetime Value (CLV)
   - Yearly and quarterly trends
   - Category-wise year-on-year growth

---

## 📈 Key Insights

- **Electronics** is the top revenue-generating category.
- **Clothing** has the highest number of units sold.
- **Customer 1053 & 1058** consistently rank in both sales and quantity.
- 2024 was the peak year; 2025 showed a significant decline in all categories.
- Business may need strategy revision for 2025 due to overall downturn.

---

## 🗂 Files

- `e-commerce.sql`: Full SQL code for data cleaning and analysis
- `insights.md`: Key observations and business findings

---

## 📝 How to Run

1. Load the SQL file into a PostgreSQL environment.
2. Run the queries in the given order to replicate the analysis.
3. Optional: Plug data into a visualization tool like Tableau or Power BI for dashboarding.

---


