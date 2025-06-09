# Data Warehouse and Analytics Project

Welcome to the **Data Warehouse and Analytics Project** repository.
This project shows a comprehensive data warehousing and analystics solution, fom building a data warehouse to generating actionable insights. It is designed as a portfolio project highlights industry best practices in data engineering and analytics.

---
## Data Architecture
The data architecture for this project follows Medallion Architecture Bronze, Silver, and Gold layers: 
1.	Bronze Layer: Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.
2.	Silver Layer: This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.
3.	Gold Layer: Houses business-ready data modeled into a star schema required for reporting and analytics.


## Project Overview
This project involves:
1.	Data Architecture: Designing a Modern Data Warehouse Using Medallion Architecture Bronze, Silver, and Gold layers.
2.	ETL Pipelines: Extracting, transforming, and loading data from source systems into the warehouse.
3.	Data Modeling: Developing fact and dimension tables optimized for analytical queries.
4.	Analytics & Reporting: Creating SQL-based reports and dashboards for actionable insights.


## Project Requirements

### Building the Data Warehouse (Data Engineering)

#### Objective
Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.

#### Specifications

- **Data Sources**: Import Data from two source systems (ERP and CRM) provided as CSV files.
- **Data Quality**: Clenase and resolve data quality issues prior to analysis.
- **Data Integration**: Combine both sources into a single, user-friendly data model designed for analytical queries.
- **Scope**: Focus on the latest dataset only: historization of data is not required.
- **Documentation**: Provide clear documentation of the data model to support both business stakeholders and analystics teams.

---

### BI: Analytics & Reporting (Data Analytics)

#### Objective
Develop SQL-based analytics to deliver detailed insights into:
- **Customer Behaviour**
- **Product Performance**
- **Sales Trends**

These insights empower stakeholders with key business metrics, enabling strategic decision-making.

---


##License
This project is licensed under the [MIT License].(License). You are free to use, modify and share with proper attribution.

## About Me
Hi! I am Nebil Divay. I am a passionate data analyst with an ability to transform data into stories and help in making informed decisions!

