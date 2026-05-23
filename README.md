                                                       🍽️ Swiggy Analytics Project

📌 Project Overview

This project demonstrates a complete modern data analytics workflow built using Microsoft Fabric and Power BI.
The objective of this project was to transform raw Swiggy food delivery data into meaningful business insights by building a scalable analytics solution that includes:
Data Ingestion using Fabric Pipelines
Data Storage in Lakehouse
SQL-based Data Cleaning & Transformation
Data Warehouse Modeling
Semantic Modeling
Interactive Dashboard Development in Power BI 

📂 Project Workflow

🔹 1. Data Ingestion using Fabric Pipeline

Built an automated ETL pipeline in Microsoft Fabric to move raw Swiggy datasets into the Lakehouse.

Pipeline Features
Automated data flow
Sequential execution
Scalable ingestion process
Centralized data movement

Tables Ingested
Orders
Restaurants
Locations
Dishes
Dates

🔹 2. Data Storage in Lakehouse

All raw datasets were stored inside the Microsoft Fabric Lakehouse before transformation.

Purpose of Lakehouse
Centralized raw data storage
Easy integration with SQL and Warehouse
Supports structured and scalable analytics architecture

🔹 3. SQL Data Cleaning & Transformation

Performed multiple SQL transformations and validations before loading data into the warehouse.

Data Cleaning Tasks

✔ Removed null values

✔ Corrected invalid date formats

✔ Added new columns

✔ Changed column data types

✔ Standardized values

✔ Performed validation checks

🧩 Data Warehouse Modeling

Created a Star Schema Data Model for optimized reporting and analytics.

📌 Dimension Tables
dim_date
dim_dish
dim_location
dim_restaurant

📌 Fact Table
fact_orders
Benefits
Improved query performance
Better dashboard optimization
Simplified reporting structure

📊 Power BI Dashboard 

Built an interactive Power BI dashboard directly inside Microsoft Fabric to analyze Swiggy business performance.

Dashboard KPIs
💰 Total Sales

🛒 Total Orders

⭐ Average Rating

📈 Average Order Value

🧾 Rating Count

Top Restaurants by Revenue

State-wise Sales Analysis

📈 Key Insights Generated

Identified top-performing restaurants

Analyzed sales trends across months and days

Compared Veg vs Non-Veg sales contribution

Evaluated customer ratings and order behavior

Tracked state-wise revenue performance
