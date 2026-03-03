# 🚀 Data Warehouse Project

## 📌 Overview

Welcome to the **Data Warehouse and Analytics Project** repository!

This project demonstrates an end-to-end data engineering solution — from raw data ingestion to business-ready analytical reporting. It showcases the implementation of a modern **Medallion Architecture (Bronze, Silver, Gold layers)** using an ETL process to transform raw data into structured, analytics-ready datasets.

The final output follows a **Star Schema design**, optimized for reporting and business intelligence tools.

---

## 🏗️ Architecture

This project follows the **Medallion Architecture**:

### 🥉 Bronze Layer – Raw Data

* Stores raw source data
* No transformations applied
* Acts as the data ingestion layer

### 🥈 Silver Layer – Cleaned & Transformed Data

* Data cleansing
* Standardization
* Deduplication
* Business rule application
* Structured intermediate tables

### 🥇 Gold Layer – Business-Ready Data

* Star Schema implementation
* Dimension tables with surrogate keys
* Fact tables for analytical metrics
* Optimized for reporting and BI tools

---

## 📊 Data Modeling

The Gold layer is designed using a **Star Schema** model:

### Dimension Tables

* `gold.dim_customers`
* `gold.dim_products`

### Fact Table

* `gold.fact_sales`

### Key Design Decisions

* Surrogate keys used in dimension tables
* Fact table references dimension surrogate keys
* Logical relationships maintained for analytics
* Optimized for aggregation and reporting performance

---

## 🔄 ETL Process

The ETL pipeline performs:

* Data extraction from source systems
* Data validation and cleansing
* Transformation using business logic
* Surrogate key generation
* Data enrichment through joins
* Loading into dimensional model

The pipeline ensures:

* Clean and reliable datasets
* Consistent business definitions
* Analytics-ready outputs

---

## 🛠️ Technologies Used

* SQL
* Microsoft SQL Server
* Star Schema Data Modeling
* ETL Development
* Medallion Architecture
* Data Warehousing Best Practices

---

## 📈 Analytics & Reporting

The Gold layer is designed to integrate seamlessly with BI tools such as:

* Microsoft Power BI
* Tableau

It supports:

* Aggregations
* Drill-down analysis
* Filtering & slicing
* Performance-optimized reporting

---

## 🎯 Project Objectives

* Demonstrate real-world data warehouse design
* Implement industry-standard ETL workflows
* Apply dimensional modeling best practices
* Build a scalable analytics foundation
* Create a portfolio-ready enterprise project

---

## 💡 Key Highlights

✔ Medallion architecture implementation
✔ Star schema dimensional modeling
✔ Surrogate key strategy
✔ Clean separation of layers
✔ Production-style SQL scripting
✔ Scalable analytics foundation

---

## 👨‍💻 Author

**Vaibhav Thareja**
Data Engineer at LTM (LTIMindtree)
Data Engineering Enthusiast
