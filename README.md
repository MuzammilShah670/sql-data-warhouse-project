# Data Warehouse and Analytics Project

## Overview

This repository presents an end-to-end **data warehouse and analytics solution**, covering everything from data ingestion to business-ready insights. It is designed as a portfolio project to demonstrate industry-standard practices in **data engineering, data modeling, and analytics**.

---

## 🏗️ Data Architecture

The project follows the **Medallion Architecture** approach, consisting of three layers:

* **Bronze Layer**
  Stores raw data ingested directly from source systems (CSV files) into a SQL Server database.

* **Silver Layer**
  Performs data cleansing, standardization, and transformation to ensure consistency and quality.

* **Gold Layer**
  Contains business-ready data structured into a **star schema**, optimized for reporting and analytical queries.

---

## 📖 Project Scope

This project includes the following components:

* **Data Architecture**
  Design and implementation of a modern data warehouse using Medallion Architecture.

* **ETL Pipelines**
  Extraction, transformation, and loading of data from multiple sources into the warehouse.

* **Data Modeling**
  Creation of fact and dimension tables to support efficient analytical queries.

* **Analytics & Reporting**
  Development of SQL-based reports to generate actionable business insights.

---

## 🎯 Key Skills Demonstrated

This project highlights practical expertise in:

* SQL Development
* Data Engineering
* ETL Pipeline Design
* Data Modeling (Star Schema)
* Data Analytics

---

## 🚀 Project Requirements

### 1. Data Warehouse Development (Data Engineering)

**Objective:**
Build a centralized data warehouse in SQL Server to consolidate sales data for analytical reporting.

**Specifications:**

* **Data Sources:**
  Two source systems (ERP and CRM) provided as CSV files.

* **Data Quality:**
  Clean and resolve inconsistencies before analysis.

* **Integration:**
  Merge data into a unified, analysis-friendly data model.

* **Scope:**
  Focus on the latest available dataset (no historization required).

* **Documentation:**
  Provide clear and structured documentation for both technical and business users.

---

### 2. Analytics & Reporting (Data Analysis)

**Objective:**
Develop SQL-based analytics to generate insights into:

* Customer Behavior
* Product Performance
* Sales Trends

These insights support data-driven decision-making.

---

## 📂 Repository Structure

```
data-warehouse-project/
│
├── datasets/                    # Raw ERP and CRM datasets (CSV files)
│
├── docs/                        # Documentation and architecture files
│   ├── etl.drawio              # ETL process diagrams
│   ├── data_architecture.drawio# Overall architecture design
│   ├── data_catalog.md         # Dataset metadata and descriptions
│   ├── data_flow.drawio        # Data flow diagrams
│   ├── data_models.drawio      # Star schema data models
│   ├── naming-conventions.md   # Naming standards for consistency
│
├── scripts/                     # SQL scripts for ETL and transformations
│   ├── bronze/                 # Raw data ingestion scripts
│   ├── silver/                 # Data cleaning and transformation
│   ├── gold/                   # Analytical model creation
│
├── tests/                       # Data validation and quality checks
│
├── README.md                    # Project documentation
├── LICENSE                      # License information
├── .gitignore                   # Ignored files and directories
└── requirements.txt             # Project dependencies
```

---

## 🛡️ License

This project is licensed under the **MIT License**. You are free to use, modify, and distribute this project with proper attribution.

---

