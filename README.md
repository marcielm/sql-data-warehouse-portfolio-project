# Data Warehouse and Analytics Project

This portfolio project demonstrates the end-to-end design and implementation of a modern data warehouse. It covers the full data lifecycle, including data ingestion, ETL processing, data cleansing, dimensional modeling, and analytical reporting, transforming raw ERP and CRM data into structured, business-ready insights. Implementing industry-standard practices in data engineering and analytics.

---

## 🧱 Data Architecture

This project follows the Medallion Architecture framework, organizing data into Bronze, Silver, and Gold layers to create a scalable, maintainable, and analytics-ready data warehouse.

<img width="890" height="698" alt="data_architecture_final" src="https://github.com/user-attachments/assets/0f1224fc-8ca7-41ab-92ff-df151df889ee" />

**1. Bronze Layer**: Raw Data
Stores data in its original format as it is received from the source systems. Raw data is ingested from CSV files into a SQL Server database, preserving the original records for traceability and auditing.

**2. Silver Layer**: Cleaned & Standardized Data
Applies data cleansing, standardization, validation, and normalization to improve data quality and prepare datasets for downstream processing and analysis.

**3. Gold Layer**: Business-Ready Data
Delivers curated, analytics-ready datasets modeled using a star schema. This layer is optimized for business intelligence, reporting, and analytics.

---

## 📖 Project Overview

This project demonstrates the end-to-end development of a modern data warehouse and analytics solution using SQL Server and industry-standard data engineering practices. Key components include:

**Data Architecture**: Designing a scalable data warehouse using the Medallion Architecture with Bronze, Silver, and Gold layers.

**ETL Pipelines**: Building robust Extract, Transform, and Load (ETL) processes to ingest, cleanse, and integrate data from multiple source systems.

**Data Modeling**: Designing optimized fact and dimension tables using a star schema to support analytical queries.

**Analytics & Reporting**: Developing SQL-based analytical queries, reports, and dashboards that deliver actionable business insights and support data-driven decision-making.

---

## 📋 Project Requirements

### Building the Data Warehouse (Data Engineering)

#### Objective:

Build a modern SQL Server data warehouse that consolidates data from multiple business systems into a centralized, analytics-ready repository for reporting and decision-making.

#### Specifications:

- **Data Sources**: Load data from ERP and CRM CSV files.
- **Data Quality**: Cleanse, standardize, and validate the data.
- **Data Integration**: Combine both sources into a unified dimensional model.
- **Data Modeling**: Design a star schema with fact and dimension tables.
- **Scope**: Process only the latest dataset; no historical tracking or SCDs.
- **Documentation**: Provide clear documentation for the data model, ETL, and architecture.

---

### 📊 BI: Analytics & Reporting (Data Analysis)

#### Objective:

Develop SQL-based analytical solutions that deliver actionable insights into:

- **Customer Behavior** 
- **Product Performance** 
- **Sales Trends** 

These analyses provide stakeholders with meaningful business metrics, reveal performance patterns, and support informed strategic decision-making.

---

## 📂 Repository Structure
```
data-warehouse-project/
│
├── datasets/                           # Source datasets used in the project, including ERP and CRM data
│
├── docs/                               # Project documentation, architecture diagrams, and design standards
│   ├── etl.drawio                      # Visual overview of the ETL processes, techniques, and workflow
│   ├── data_architecture.drawio        # High-level diagram of the data warehouse architecture
│   ├── data_catalog.md                 # Data dictionary containing field definitions, data types, and metadata
│   ├── data_flow.drawio                # Diagram illustrating the movement of data through each warehouse layer
│   ├── data_models.drawio              # Dimensional data models, including the star schema design
│   ├── naming-conventions.md           # Naming standards for database objects, columns, scripts, and files
│
├── scripts/                            # SQL scripts used for data ingestion, transformation, and modeling
│   ├── bronze/                         # Scripts for loading raw source data into the bronze layer
│   ├── silver/                         # Scripts for cleansing, standardizing, and transforming data
│   ├── gold/                           # Scripts for creating business-ready analytical tables and models
│
├── tests/                              # Data quality checks and validation scripts
│
├── README.md                           # Project overview, architecture, setup instructions, and usage guidance
├── LICENSE                             # Repository licensing terms and usage permissions
├── .gitignore                          # Files and directories excluded from version control
└── requirements.txt                    # Project dependencies and required software packages
```
---

## 🌟 About Me

Hi, I'm **Marc Marciel** an IT graduate and aspiring Data Analyst with a strong interest in using data to solve business problems and support better decision-making.

Through hands-on projects, I apply SQL and analytical techniques to clean, explore, and interpret complex datasets, identify meaningful trends, and transform raw information into clear, actionable insights.

My portfolio reflects my continued growth in data analytics, technical problem-solving, and business-focused analysis. Each project is designed not only to strengthen my technical skills, but also to demonstrate how data can be used to answer important questions, improve processes, and create measurable value. 

