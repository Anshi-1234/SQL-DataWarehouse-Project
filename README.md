
# Data Warehouse and Analytics Project

Welcome to the **Data Warehouse and Analytics Project** repository! 🚀  
This portfolio project showcases a complete data warehousing and analytics solution — from raw data ingestion to generating business insights — following industry-standard practices in data engineering and analytics.

---

## 🏗️ Data Architecture

The architecture adopts the **Medallion Architecture**, structured into three layers:

1. **Bronze Layer**: Ingests raw data directly from source systems (CSV files) into SQL Server without transformations.
2. **Silver Layer**: Performs data cleaning, standardization, and normalization to ensure data quality and consistency.
3. **Gold Layer**: Stores refined, business-ready data modeled in a star schema for advanced reporting and analytics.

---

## 📖 Project Overview

Key components of the project include:

1. **Data Architecture**: Implementation of Medallion Architecture with clearly defined Bronze, Silver, and Gold layers.
2. **ETL Pipelines**: Extraction, transformation, and loading processes for moving and shaping data.
3. **Data Modeling**: Creation of optimized fact and dimension tables for analytical workloads.
4. **Analytics & Reporting**: Development of SQL-based reports and dashboards to generate actionable business insights.

🎯 This project is ideal for those looking to demonstrate skills in:
- SQL Development  
- Data Architecture  
- Data Engineering  
- ETL Pipeline Design  
- Data Modeling  
- Business Intelligence and Analytics

---

## 🛠️ Important Links & Tools:

Everything is for Free!
- **[Datasets](datasets/):** Access to the project dataset (csv files).
- **[SQL Server Express](https://www.microsoft.com/en-us/sql-server/sql-server-downloads):** Lightweight server for hosting your SQL database.
- **[SQL Server Management Studio (SSMS)](https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver16):** GUI for managing and interacting with databases.
- **[Git Repository](https://github.com/):** Set up a GitHub account and repository to manage, version, and collaborate on your code efficiently.

---

## 🚀 Project Requirements

### Building the Data Warehouse (Data Engineering)

#### Objective
Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.

#### Specifications
- **Data Sources**: Import data from two source systems (ERP and CRM) provided as CSV files.
- **Data Quality**: Cleanse and resolve data quality issues prior to analysis.
- **Integration**: Combine both sources into a single, user-friendly data model designed for analytical queries.
- **Scope**: Focus on the latest dataset only; historization of data is not required.
- **Documentation**: Provide clear documentation of the data model to support both business stakeholders and analytics teams.

---

### BI: Analytics & Reporting (Data Analysis)

#### Objective
Develop SQL-based analytics to deliver detailed insights into:
- **Customer Behavior**
- **Product Performance**
- **Sales Trends**

These insights empower stakeholders with key business metrics, enabling strategic decision-making.  


## 📂 Repository Structure
```
data-warehouse-project/
│
├── datasets/                           # Raw datasets used for the project (ERP and CRM data)
│
├── scripts/                            # SQL scripts for ETL and transformations
│   ├── bronze/                         # Scripts for extracting and loading raw data
│   ├── silver/                         # Scripts for cleaning and transforming data
│   ├── gold/                           # Scripts for creating analytical models
│
├── README.md                           # Project overview and instructions
├── LICENSE                             # License information for the repository
```
---


## 🛡️ License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and share this project with proper attribution.

#
