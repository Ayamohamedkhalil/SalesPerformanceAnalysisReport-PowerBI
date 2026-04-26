
 📊 AdventureWorks Sales Analytics – Power BI Project

📌 Overview

This project is an end-to-end Business Intelligence solution built using the AdventureWorks dataset.
It focuses on transforming raw data into a scalable data model and delivering actionable business insights through an interactive Power BI dashboard.

The project demonstrates the full analytics lifecycle:

> Data Preparation → Data Modeling → DAX → Visualization → Insights

🎯 Objectives

* Convert raw, unstructured data into a clean analytical dataset
* Build a high-performance Star Schema data model
* Create dynamic KPIs using DAX
* Design an intuitive, user-friendly dashboard
* Extract meaningful insights to support decision-making

🧱 Data Preparation (Power Query)

The dataset initially contained inconsistencies and scattered tables.
The following steps were applied:

* Handling missing and null values
* Removing duplicates and inconsistencies
* Standardizing formats (Date, Categories, Territories)
* Creating clean and structured tables
* Preparing data for modeling

🏗️ Data Modeling (Star Schema)

Star Schema => model was implemented to ensure performance and scalability.
🔹 Fact Table

* Sales

  * Sales Amount
  * Order Quantity
  * Tax
  * Freight

🔹 Dimension Tables

* Date
* Product
* Territory
* SalesPerson
* Status
* ShipMethod
 ✅ Benefits

* Faster query performance
* Simplified DAX calculations
* Efficient filtering across visuals
* Scalable architecture


🧮 DAX Measures

Custom measures were created to drive the dashboard:

📊 Core KPIs

*Total Sales: 123.22M
* Total Orders: 121K
* Total Quantity:274,914
* Total Tax:10.19M
*Total Freight:3.18M

⚙️ Advanced Calculations

* Year-over-Year (YoY) Growth
* Top N Products
* Top N Salespersons
* Dynamic filtering across all visuals

🎨 Dashboard Features

The report was designed as an interactive analytical experience, not just static visuals.

🧭 Pages

* Sales Overview
* SalesPerson Analysis
* Product Analysis
* 
🎛️ Interactivity

* Dynamic filters:

  * Product
  * Category
  * Territory
  * City
  * Ship Method
  * Status
* Reset button for quick navigation
* Drill-down capabilities

📈 Key Insights

📊 Business Scale

* Total Sales: 123M
* Total Orders: 121K

⚠️ Category Dependency

* Bikes contribute 86% of total revenue

👉 Indicates high concentration risk

🌍 Geographic Performance

* Southwest leads with 22% of sales
* Canada & Northwest ~15% each

👉 Sales distribution is uneven → expansion opportunity

📉 Time Trend

* Peak performance in **2013 (~50M)**
* Drop observed in **2014**

👉 Requires further business investigation

👥 Sales Team Analysis

* Total Salespersons: 18
* Significant performance gap

👉 Opportunity for performance optimization

🚴 Product Insights

* Top-performing products:Mountain Bikes
* Some products show declining trends

👉 Possible lifecycle or demand issues

🚚 Operational Insight

Example Drill-down:

* Category: Clothing
* Territory: Canada
* Ship Method: Cargo Transport 5

Result:

* Sales ≈ 426K
* Heavy reliance on one shipping method

👉 Indicates logistics dependency risk

🛠️ Tools & Technologies

* Power BI
* Power Query
* DAX
* Data Modeling (Star Schema)
* Sql Server

