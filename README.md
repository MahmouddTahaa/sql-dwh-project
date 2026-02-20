# SQL Data Warehouse Project

A comprehensive, production-ready data warehouse solution demonstrating modern data engineering practices using the Medallion Architecture pattern. This project showcases the complete ETL pipeline from raw data ingestion through to business-ready analytics.

---

## 🏗️ Architecture Overview

### Medallion Architecture
This project implements a three-layered data warehouse design:

![Data Architecture](./docs/data_architecture-1.png)

| Layer | Purpose | Characteristics |
|-------|---------|-----------------|
| **Bronze** | Raw Data | CSV ingestion from source systems (ERP, CRM) stored as-is |
| **Silver** | Cleansed Data | Data quality checks, standardization, and normalization |
| **Gold** | Analytics-Ready | Star schema with dimension and fact tables optimized for queries |

---

## 📊 Technical Competencies Demonstrated

This project covers essential data engineering and analytics competencies:

- **Data Architecture & Modeling** – Designing scalable, efficient data warehouses
- **ETL Pipeline Development** – Building robust extract, transform, load processes
- **SQL Optimization** – Writing efficient queries for data transformation and analysis
- **Data Quality Assurance** – Implementing validation and quality checks
- **Documentation Standards** – Maintaining clear naming conventions and data catalogs

---

## 📚 Project Scope

### Data Engineering: Building the Warehouse

**Objective:** Consolidate multi-source sales data into a unified, analytical data warehouse.

**Key Activities:**
- Extract and load raw data from ERP and CRM CSV files into the Bronze layer
- Implement data cleansing and transformations in the Silver layer
- Build a star schema (dimensions & facts) in the Gold layer for analytical queries
- Validate data quality and integrity at each layer

**Output:** A production-grade data warehouse ready for reporting and analytics

### Analytics: Insights & Reporting

**Objective:** Generate actionable business intelligence from the warehouse.

**Focus Areas:**
- **Customer Analytics** – Segmentation, demographics, and behavior patterns
- **Product Performance** – Sales velocity, margins, and category trends
- **Sales Analysis** – Revenue trends, seasonal patterns, and forecast drivers

For additional technical details, see [docs/data_catalog.md](docs/data_catalog.md) and [docs/naming_conventions.md](docs/naming_conventions.md).

## 📂 Repository Structure
```
data-warehouse-project/
│
├── datasets/                           # Raw datasets used for the project (ERP and CRM data)
│
├── docs/                               # Project documentation and architecture details
│   ├── etl.png                      # png file shows all different techniquies and methods of ETL
│   ├── data_architecture.png        # png file shows the project's architecture
│   ├── data_catalog.md                 # Catalog of datasets, including field descriptions and metadata
│   ├── data_flow.png                # png file for the data flow diagram
│   ├── data_models.png              # png file for data models (star schema)
│   ├── naming-conventions.md           # Consistent naming guidelines for tables, columns, and files
│
├── scripts/                            # SQL scripts for ETL and transformations
│   ├── bronze/                         # Scripts for extracting and loading raw data
│   ├── silver/                         # Scripts for cleaning and transforming data
│   ├── gold/                           # Scripts for creating analytical models
│
├── tests/                              # Test scripts and quality files
│
├── README.md                           # Project overview and instructions
├── LICENSE                             # License information for the repository
├── .gitignore                          # Files and directories to be ignored by Git
└── requirements.txt                    # Dependencies and requirements for the project
```
---

## ☕ Let's Connect

Let's stay in touch! Feel free to connect with me on the following platforms:

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mahmoud-taha-abdelaal/)
---
---
## 🛡️ License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and share this project with proper attribution.

