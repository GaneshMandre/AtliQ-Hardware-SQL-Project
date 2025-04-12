# 📊 AtliQ Hardware – SQL Project  
**Business Analytics & Forecast Accuracy using SQL**

## 🔍 Project Overview  
This real-world SQL project is based on **AtliQ Hardware**, a company in the PC and accessories industry. The goal was to analyze business performance, classify markets, and evaluate forecast accuracy using SQL.

## 🧠 Skills Demonstrated  
- SQL Joins & Aggregations  
- User-Defined Functions  
- Views & Stored Procedures  
- Forecast Accuracy Calculation  
- Business Logic Implementation  

## 🛠️ Tools & Technologies  
- MySQL  
- MySQL Workbench  
- Structured Datasets  

## 📂 Data Used  
- `dim_date`  
- `dim_product`  
- `dim_customer`  
- `fact_sales_monthly`  
- `fact_gross_price`  
- `fact_pre_invoice_deductions`  
- `fact_post_invoice_deductions`  
- `fact_forecast_monthly`

## ✅ Key Tasks & Features

### 1. Fiscal Year Function (`get_fiscal_year`)
Created a function to return a structured table with:
- Month, Fiscal Year, Product, Variant, Sold Quantity, Gross Price per Item, Gross Price Total

### 2. Gross Sales View (`gross_sales`)
A view built using sales and pricing tables to simplify gross revenue analysis.

### 3. Market Badge Classification
Stored procedure to assign:
- **Gold** badge if total sold quantity > 5 million  
- **Silver** badge otherwise

### 4. Net Sales View (`net_sales`)
Calculated net sales using deductions and joins with:
- `fact_sales_monthly`, `fact_gross_price`, `pre_invoice`, `post_invoice`, `dim_product`, and `dim_customer`

### 5. Top Performer Procedures
Stored procedures to identify:
- Top Market, Product, and Customer based on Net Sales

### 6. Forecast Accuracy Table (`fact_act_est`)
Final output includes:
- Fiscal Year, Market, Customer, Product  
- Total Gross Price, Sold Quantity, Forecast Quantity  
- Net Error, Absolute Error, Forecast Accuracy %

## 📈 Business Impact  
This project showcases how SQL can be used to solve real business problems, evaluate performance, and drive insight-based decision making.

## 🎥 Video Presentation  
Watch the full project presentation here 👉 [Click to Watch on YouTube](https://www.youtube.com/embed/xic6Nyg2ZIQ?si=MWG1Of3YydXiOowz)

📌 I also shared this project on LinkedIn — check out the post and join the discussion 👉 [View LinkedIn Post](https://www.linkedin.com/posts/ganesh-mandre_sql-dataanalytics-learningjourney-activity-7316463118132355072-x8Ri?utm_source=share&utm_medium=member_desktop&rcm=ACoAAChUMqgBCcYrTDPLI0kmw-oI62JvH6YGYKM)


---

