🍽️ Swiggy Analytics using Microsoft Fabric

End-to-End Modern Data Analytics Project | Microsoft Fabric • SQL • Power BI • Data Warehouse

![Swiggy Analytics](https://github.com/Adarsh0722/Swiggy-Analytics-Project/blob/main/Swiggy%20Analytics.png)


🔍 Project Overview

This project demonstrates a complete modern cloud-based analytics workflow using Microsoft Fabric and Power BI to analyze Swiggy food delivery data and generate business insights.

The project focuses on transforming raw operational data into a scalable analytics solution through:

Data Ingestion → Lakehouse Storage → SQL Transformation → Data Warehouse Modeling → Dashboard Reporting

The solution simulates a real-world enterprise analytics architecture used by organizations for business intelligence and reporting.

🎯 Business Problem

Food delivery platforms generate large amounts of operational data daily. Businesses often struggle to:

Identify top-performing restaurants

Analyze customer ordering behavior

Monitor regional sales performance

Track ratings and delivery trends

Understand product category contribution

Build scalable reporting systems

This project addresses these challenges using Microsoft Fabric’s modern analytics ecosystem.

📂 Project Workflow

🔹 1. Data Ingestion using Fabric Pipeline

Built an automated ETL pipeline in Microsoft Fabric to ingest raw Swiggy datasets into the Lakehouse.

✅ Pipeline Features
Automated Data Flow

Sequential Execution

Scalable Data Processing

Centralized Data Movement

Enterprise-style ETL Workflow

📌 Datasets Ingested

1. Orders

2. Restaurants

3. Locations

4. Dishes

5. Dates

![Swiggy Analytics](https://github.com/Adarsh0722/Swiggy-Analytics-Project/blob/main/PIPELINES.png)

🏞️ 2. Data Storage using Lakehouse

All raw datasets were stored inside the Microsoft Fabric Lakehouse before transformation and modeling.

✅ Benefits of Lakehouse

Centralized Raw Data Storage

Easy SQL Integration

Scalable Cloud Architecture

Structured Data Management

🧹 3. SQL Data Cleaning & Transformation

Performed SQL-based transformation and validation processes to prepare analytics-ready datasets.

✅ Data Cleaning Tasks

✔ Removed Null Values

✔ Corrected Invalid Date Formats

✔ Standardized Column Values

✔ Added Derived Columns

✔ Changed Data Types

✔ Performed Validation Checks

![Swiggy Analytics](https://github.com/Adarsh0722/Swiggy-Analytics-Project/blob/main/SQL%20DATA%20CLEANING.png)

🧩 4. Data Warehouse Modeling

Designed a Star Schema Data Model for optimized reporting and analytics performance.

📌 Dimension Tables

dim_date

dim_dish

dim_location

dim_restaurant

📌 Fact Table

  fact_orders
  
✅ Benefits
Faster Query Performance

Simplified Reporting

Better Dashboard Optimization

Industry-standard Warehouse Design

![Swiggy Analytics](https://github.com/Adarsh0722/Swiggy-Analytics-Project/blob/main/MANAGING%20RELATIONSHIPS.png)

📊 5. Power BI Dashboard

Developed an interactive Power BI dashboard inside Microsoft Fabric to monitor Swiggy business performance.

📌 Dashboard KPIs

💰 Total Sales

🛒 Total Orders

⭐ Average Rating

📈 Average Order Value

🧾 Rating Count

![Swiggy Analytics](https://github.com/Adarsh0722/Swiggy-Analytics-Project/blob/main/DASHBOARD.png)


📈 Key Insights

Top-performing restaurants contribute a major share of total revenue

Certain states consistently generate higher order volumes

Veg and Non-Veg categories show different purchasing patterns

Higher-rated restaurants receive more repeat orders

Sales trends fluctuate across weekdays and months

Average order value helps identify premium customer segments

💼 Business Impact

This analytics solution helps businesses:

Improve restaurant partnership strategies

Optimize regional marketing campaigns

Enable data-driven decision-making

Track operational performance effectively

Build scalable analytics infrastructure

