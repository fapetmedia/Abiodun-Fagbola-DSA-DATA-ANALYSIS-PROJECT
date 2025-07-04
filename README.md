# Abiodun-Fagbola-DSA-DATA-ANALYSIS-PROJECT
This project demonstrates a comprehensive SQL-based analysis of a fictional retail company, KMS, using structured datasets to uncover key business insights and performance metrics.
## Project Overview
The SQL script includes data import, transformation, and analysis using T-SQL. A consolidated view named KMSORDER was created by joining sales records with order status to provide a full picture of transactions, returns, customer behavior, and shipping performance.
## Key Features
- Data cleansing using COALESCE to handle nulls
- View creation for efficient querying (CREATE VIEW)
- Aggregation and grouping to analyze:
  - Top-performing product categories
  - Best and worst sales regions
  - Most and least valuable customers
  - Shipping cost efficiency by delivery mode
  - Return rates by segment
## List of Questions in the SQL Project
-	Which product category had the highest sales?
-	What are the top 3 and bottom 3 regions in terms of sales?
-	What were the total sales of appliances in Ontario?
-	Advise the management of KMS on what to do to increase the revenue from the bottom 10 customers.
-	KMS incurred the most shipping cost using which shipping method?
-	Who are the most valuable customers, and what products or services do they typically purchase?
-	Which small business customer had the highest sales?
-	Which corporate customer placed the most number of orders between 2009 and 2012?
-	Which consumer customer was the most profitable one?
-	Which customer returned items, and what segment do they belong to?
-	Did the company appropriately spend shipping costs based on the order priority, considering that delivery truck is the most economical but slowest and Express Air is the fastest but most expensive?
## Tools Used
- Microsoft SQL Server / SSMS
- Structured retail data (Sales, Profit, Shipping and Customer Segments)
## Outcome
This project reveals how SQL can power business intelligence by transforming raw data into actionable insights. It also provides a foundation for integrating visual tools like Power BI for further analysis.



## Power BI Retail Dashboard (KMS Case Study)
This Power BI project visualizes insights derived from the KMS retail dataset, originally structured and cleaned using SQL. It showcases how data storytelling and interactive dashboards can drive better decision-making across sales, customer engagement, and logistics.
## Project Overview
The dataset includes customer transactions, shipping records, and product categories. After transformation via SQL, the data was imported into Power BI to build dynamic reports highlighting key performance indicators and patterns.
## Key Dashboards & Insights
- Sales Overview Dashboard: Total sales, profit, trends by category, segment and region
- Customer Performance: Top and bottom customers, segmented by behavior and value
- Shipping Analysis: Shipping cost verse method efficiency and delivery priority
- Product Analytics: Best-selling products and high-margin categories
- Return Trends: Customer return patterns and segment insights
## Tools and Techniques Used
- Power BI Desktop
- Custom DAX measures and calculated columns
- Visual elements: bar charts, slicers, KPIs, stacked columns and maps
- Drill-through filters for interactive exploration
## Outcome
The Power BI dashboard transforms raw transactional data into actionable business intelligence. It empowers stakeholders to identify revenue opportunities, improve logistics efficiency and understand customer value at a glance.
