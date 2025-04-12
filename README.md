📊 AtliQ Hardware – SQL Project
Business Analytics & Forecast Accuracy using SQL

🔍 Project Overview
This real-world SQL project is based on AtliQ Hardware, a company operating in the PC and accessories industry. The project focuses on analyzing business performance, market classification, and forecast accuracy using raw sales and pricing data.

🧠 Skills Demonstrated
SQL Joins & Aggregations

User-Defined Functions

Views & Stored Procedures

Forecast Accuracy Calculation

Business Logic Implementation

🛠️ Tools & Technologies
SQL

MySQL (Workbench)

Real-world structured datasets

📂 Data Used
dim_date

dim_product

dim_customer

fact_sales_monthly

fact_gross_price

fact_pre_invoice_deductions

fact_post_invoice_deductions

fact_forecast_monthly

✅ Key Features / Tasks
1. get_fiscal_year Function
Created a function to calculate the fiscal year from the date and return a table containing:

Month, Fiscal Year, Product, Variant, Sold Quantity, Gross Price per Item, Gross Price Total

2. gross_sales View
A simplified view of gross revenue derived from fact_sales_monthly and fact_gross_price.

3. Market Badge Classification – Stored Procedure
Assigned Gold or Silver badge to markets based on sales volume:

Gold if total sold quantity > 5 million

Silver otherwise

4. net_sales View
Net sales = Gross Sales – Pre-Invoice – Post-Invoice deductions
Used joins on:

fact_sales_monthly, fact_gross_price, pre_invoice, post_invoice, dim_product, dim_customer

5. Top Market, Product, Customer – Stored Procedures
Created stored procedures to identify top-performing market, product, and customer by net sales.

6. Forecast Accuracy Report
Final output: fact_act_est
Fields included:

Fiscal Year, Market, Customer, Product,

Total Gross Price, Sold Quantity, Forecast Quantity

Net Error, Absolute Error, Forecast Accuracy %

📈 Business Impact
This project demonstrates how SQL can be used to support strategic decisions through data-driven insights. It showcases the practical use of SQL in sales tracking, market performance evaluation, and forecast validation.

📹 Video Presentation
🎥 Link to YouTube Video Presentation (https://youtu.be/xic6Nyg2ZIQ)

