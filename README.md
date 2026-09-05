# 🏗️ SQL Data Warehouse & Analytics Project

Building a modern data warehouse with **SQL Server**, covering ETL, data modeling, and analytics — from raw source data to business-ready insights.

This project follows the **Medallion Architecture** (Bronze → Silver → Gold), then layers SQL-based analytics on top of the final model.

## 📐 Data Architecture

- **Bronze** – Raw data loaded as-is from source systems (ERP & CRM CSV files) into SQL Server.
- **Silver** – Cleansed, standardized, and normalized data, ready for modeling.
- **Gold** – Business-ready data modeled into a star schema for reporting and analytics.

## 🎯 What's Included

- **Data Architecture** – Bronze/Silver/Gold warehouse design
- **ETL Pipelines** – Load and transform ERP + CRM source data
- **Data Modeling** – Fact and dimension tables (star schema)
- **Analytics** – SQL scripts for exploration, ranking, magnitude, change-over-time, cumulative, segmentation, part-to-whole, and customer/product reports

## 🗂️ Repository Structure

```
sql-data-warehouse-project/
├── datasets/                # Raw ERP & CRM source CSVs
├── scripts/                 # Bronze → Silver → Gold ETL scripts
├── data_for_analytics/      # Data feeding the analytics layer
├── scripts-for analytics/   # SQL scripts for business analysis
├── tests/                   # Data quality checks
└── README.md
```

## ⚙️ Tech Stack

SQL Server, SSMS, Medallion Architecture, Star Schema

