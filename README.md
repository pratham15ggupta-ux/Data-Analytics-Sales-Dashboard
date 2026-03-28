# Sales Data Analytics Dashboard (SQL + Power BI)

## Project Overview
This project analyzes motorcycle and accessories sales data using SQL (SSMS) and Power BI.  
The objective is to extract meaningful business insights related to customers, products, and sales performance, and present them through an interactive dashboard.

The project follows an end-to-end analytics approach:
- Data extraction and transformation using SQL  
- Data cleaning and modeling using Power Query  
- Data visualization and insights using Power BI  

---

## Business Objectives

- Create structured datasets for further analysis using BI tools  
- Evaluate revenue contribution by product categories  
- Analyze sales trends over time  
- Identify top-performing products  
- Understand geographical sales distribution  
- Track key business KPIs for performance evaluation  

---

## 🗄️ Data Model 

The project follows a star schema design where:
- fact_sales is the central fact table containing transaction-level data  
- dim_products and dim_customers are dimension tables  
- One-to-many relationships connect dimension tables to the fact table  

<img width="933" height="376" alt="Data Model" src="https://github.com/user-attachments/assets/31a66e29-26fd-4b78-aaa4-9112fdf90f19" />

dim_products.product_key → fact_sales.product_key  
dim_customers.customer_key → fact_sales.customer_key  

Each customer and product can have multiple sales records.

---

## SQL Concepts Used

- SELECT statements  
- INNER JOIN  
- GROUP BY  
- ORDER BY  
- Aggregate Functions (SUM, COUNT, AVG)  
- Subqueries  
- Filtering using WHERE and HAVING  
- CTE  
- Views  

---

## Power BI Dashboard

The Power BI dashboard provides a visual representation of business performance and key insights.

Key features:
- KPI cards (Total Revenue, Orders, Customers, AOV)  
- Revenue trend analysis (Year-wise)  
- Category-wise revenue distribution  
- Country-wise sales performance  
- Product-level performance analysis  
- Gender-based revenue insights  

---

## 📊 Top Business Insights

Below are key insights derived from both SQL analysis and Power BI dashboard.

---

### Overall Business Performance  
Snapshot of core KPIs showing overall scale and performance.  

**Report:**  
- **Total Revenue:** `<29M>`  
- **Total Orders:** `<28K>`  
- **Total Customers:** `<18.47K>`  
- **Average Order Value:** `<1.06K>`  

---

### Sales Trends Over Time  
Revenue shows a consistent upward trend across years, indicating business growth.  

**Insight:**  
- Significant increase in revenue in recent years  
- Clear upward trajectory visible in dashboard trend analysis  

---

### Category Contribution  
Product categories contribute unevenly to total revenue.  

**Report:**  
- Bikes dominate overall revenue contribution  
- Accessories and clothing contribute comparatively less  

**Insight:**  
- Business is heavily dependent on core product category (Bikes)  

---

### Top Performing Products  
Identifies products driving maximum revenue.  

**Report:**  
- **Top product:** `<Mountain-200>`  

**Insight:**  
- A small set of products contributes a large share of total revenue  

---

### Geographic Performance  
Sales distribution across countries highlights key markets.  

**Insight:**  
- United States leads in total orders  
- Followed by Australia and Canada  
- Other countries contribute smaller shares  

---

### Product Segment Performance  
Different product segments contribute differently to revenue.  

**Insight:**  
- Mid-range products generate the highest revenue share  
- High-performance and low-performance segments contribute less  

---

### Customer Demographics Insight  
Revenue comparison based on gender.  

**Insight:**  
- Female customers contribute slightly higher revenue (~50%+)  
- Revenue distribution between genders is relatively balanced  

---

## Key Learnings

- Writing complex SQL queries for business analysis  
- Building a star schema data model  
- Translating raw data into actionable insights  
- Data transformation using Power Query Editor  
- Designing interactive dashboards in Power BI  
- Combining SQL and BI tools for end-to-end analytics  

---

## Future Improvements

- Add advanced DAX calculations for deeper insights  
- Implement drill-through and interactive filtering  
- Optimize SQL queries for performance  
- Add forecasting and trend analysis  

---

## ▶ How to Run

1. Import the SQL file into MySQL / SSMS  
2. Execute database initialization script  
3. Run SQL queries to generate datasets  
4. Load data into Power BI  
5. Use Power Query for transformation  
6. Build dashboard visuals  

---

## Acknowledgment

This project was developed as part of my SQL learning journey through the Data With Baraa course.  
Only the SQL framework and dataset structure were inspired by the course material.  

The Power BI dashboard, data transformation using Power Query Editor, and all visualizations were independently created by me without using any reference dashboard from the course.

---

## About Me

**Pratham Gupta**  
Economics Honours Student | Aspiring Data Analyst  

📧 Email: pratham15ggupta@gmail.com  

🔗 LinkedIn: www.linkedin.com/in/pratham-gupta-860749273  

---

If you found this project interesting or would like to connect, feel free to reach out!

