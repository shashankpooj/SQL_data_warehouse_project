 📊 Data Warehouse & Analytics Project

A complete **end-to-end Data Warehouse and Analytics solution**, showcasing modern data engineering best practices—from raw data ingestion to analytics-ready data models and SQL-based insights.

This project is designed as a  demonstration of skills in SQL development, ETL pipelines, data modeling, and analytics.

---

## 🏗️ Data Architecture (Medallion Architecture)

This project follows the **Medallion Architecture** across three layers:

### 🥉 Bronze Layer

* Stores raw data exactly as received
* Data ingested from CSV files into SQL Server
* No transformations (raw zone)

### 🥈 Silver Layer

* Data cleansing
* Standardization
* Deduplication
* Normalization
* Ready for dimension & fact modeling

### 🥇 Gold Layer

* Business-ready analytical data
* Modeled using a Star Schema
* Used for BI dashboards and reporting

---

## 📖 Project Overview

This project includes:

### Data Architecture

* Modern Data Warehouse design
* Bronze → Silver → Gold transformation flow

### ETL Pipelines

* Fully SQL-based ETL
* Scripts organized by layers
* Handles data cleaning, joining, enrichment

### Data Modeling

* Star schema design
* Fact & dimension tables optimized for analytical queries

### Analytics & Reporting

Insights generated using SQL:

* Customer behavior
* Product performance
* Sales trends
* Key metrics for business decision-making

---

## 🎯 Skills Demonstrated

This project highlights expertise in:

* SQL Development
* Data Engineering
* ETL Pipeline Development
* Data Architecture
* Data Modeling (Star Schema)
* Data Analytics

---

## 🛠️ Tools & Resources

* CSV Datasets
* SQL Server Express
* SQL Server Management Studio (SSMS)
* Git & GitHub
* DrawIO
* Notion templates and project steps

---

## 🚀 Project Requirements

### Objective (Data Engineering)

Build a data warehouse that consolidates sales data from multiple source systems to support analytics.

### Key Specifications

* Import data from ERP and CRM CSV files
* Clean and resolve data quality issues
* Integrate sources into one analytics-ready model
* No historization required (latest load only)
* Document all models, datasets, and flows

### Objective (Analytics)

Use SQL to generate insights on:

* Customer behavior
* Product performance
* Sales & revenue trends


---

## 📂 Repository Structure

```
data-warehouse-project/
│
├── datasets/                     # Raw ERP & CRM CSV files
│
├── docs/                         # Architecture diagrams & documentation
│   ├── etl.drawio
│   ├── data_architecture.drawio
│   ├── data_catalog.md
│   ├── data_flow.drawio
│   ├── data_models.drawio
│   ├── naming-conventions.md
│
├── scripts/                      # SQL ETL scripts
│   ├── bronze/                   # Raw data ingestion
│   ├── silver/                   # Cleaning & transformation
│   ├── gold/                     # Star schema & analytical models
│
├── tests/                        # Validation & quality checks
│
├── README.md                     # Project overview
├── LICENSE                       # License information
├── .gitignore                    # Git ignore rules
└── requirements.txt              # Dependencies list
```

---



### Connect With Me
LinkedIn


