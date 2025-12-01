Business Request Demand Overview Dashboard
Project Overview:
This project analyzes business request demand by extracting, transforming, and structuring datasets using SQL, and visualizing them through a Power BI dashboard.
The goal is to monitor request volume, customer demand patterns, priority distribution, and resolution timelines to improve transparency and operational efficiency.

Key Objectives:
1. Build a clean dimensional data model using SQL (Star Schema)
2. Create KPIs for analyzing demand and performance
3. Develop an interactive Power BI dashboard with drilldowns and slicers
4. Provide insights for business decision-making

Repository Structure:
├── SQL/                      # SQL queries for ETL and data extraction
│   ├── AdventureWorks_DimDate_Query.sql
│   ├── Dim_Customer_Query.sql
│   ├── Dim_Product_Query.sql
│   ├── Fact_Query.sql
│
├── Data/                     # Cleaned datasets used for the dashboard
│   ├── Dim_Calendar.csv
│   ├── Dim_Customer.csv
│   ├── Dim_Products.csv
│   ├── Fact_Internet_sales.csv
│
├── Reports/                  # Power BI dashboard
│   ├── Sales_Report_Finished.pbix
│
├── Assets/                   # (Optional) Dashboard images or documentation
│   ├── README.md
│
└── README.md

Dashboard Overview:
Screenshots are not included due to upload limitations.
You can explore the full interactive dashboard by downloading the .pbix file from the Reports folder.

Key Insights Delivered:
✔ Request volume trends across time
✔ Customer-wise and product-wise demand distribution
✔ Priority distribution of business requests
✔ Resolution time tracking and comparisons
✔ Drilldown features for deeper analysis

Technologies Used:
1.SQL (T-SQL) – Data extraction & transformation
2.Power BI – Data modeling, KPIs, and visual analytics
3.Star Schema Modeling – Fact & dimension tables
4.CSV / Flat File ETL

Future Enhancements:
1.Add more DAX measures (MTD, QTD, YoY trends)
2.Publish the dashboard to Power BI Service
3.Automate refresh using Power BI Gateway
4.Add SLA compliance KPIs and request aging metrics

Author:
Rupesh Kumbhakar
Data Analyst | Power BI | SQL | Python
