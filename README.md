# Data Warehouse and Analytics Project

Welcome this project showcases the design and implementation of a modern data warehouse and analytics solution using industry-standard data engineering practices. It covers the complete data lifecycle—from data ingestion and ETL pipelines to dimensional modeling and analytical reporting—transforming raw data into meaningful business insights.

Built as a portfolio project, this repository demonstrates best practices in SQL development, data warehouse architecture, and analytics engineering, reflecting the skills and methodologies used in real-world enterprise environments.

---

## 🧱 Data Architecture

This project follows the Medallion Architecture framework, organizing data into Bronze, Silver, and Gold layers to create a scalable, maintainable, and analytics-ready data warehouse.

**Bronze Layer**: Raw Data
Stores data in its original format as it is received from the source systems. Raw data is ingested from CSV files into a SQL Server database, preserving the original records for traceability and auditing.

**Silver Layer**: Cleansed & Transformed Data
Applies data cleansing, standardization, validation, and normalization to improve data quality and prepare datasets for downstream processing and analysis.

**Gold Layer**: Business-Ready Data
Delivers curated, analytics-ready datasets modeled using a star schema. This layer is optimized for business intelligence, reporting, and analytics.

---

## 📖 Project Overview

This project demonstrates the end-to-end development of a modern data warehouse and analytics solution using SQL Server and industry-standard data engineering practices. Key components include:

**Data Architecture**: Designing a scalable data warehouse using the Medallion Architecture with Bronze, Silver, and Gold layers.

**ETL Pipelines**: Building robust Extract, Transform, and Load (ETL) processes to ingest, cleanse, and integrate data from multiple source systems.

**Data Modeling**: Designing optimized fact and dimension tables using a star schema to support high-performance analytical queries.

**Analytics & Reporting**: Developing SQL-based analytical queries and reporting datasets that deliver actionable business insights and support data-driven decision-making.

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
