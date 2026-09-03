# Data Warehouse & Analytics Project

This repository contains a data warehouse project focused on transforming raw sales data into structured and useful information for analysis. The project covers the main stages of a data engineering workflow, including data ingestion, transformation, data modeling, and analytical reporting.

## Data Architecture

The project uses a **Medallion Architecture**, divided into three layers: **Bronze, Silver, and Gold**.

1. **Bronze Layer**: Contains the original data imported from the source CSV files into SQL Server. The data is kept in its raw form with minimal changes.

2. **Silver Layer**: The data is cleaned and transformed at this stage. This includes tasks such as handling inconsistent values, standardizing formats, and preparing the data for further processing.

3. **Gold Layer**: Contains the final, analysis-ready datasets. The information is organized using a **Star Schema**, with fact and dimension tables designed for reporting and analytical queries.

---

## Project Overview

The main goal of this project is to build a complete data warehouse and use it to extract meaningful information from sales data.

The project covers:

* **Data Architecture** – Building the warehouse using the Bronze, Silver, and Gold layers.
* **ETL Processes** – Extracting data from the source files, transforming it, and loading it into the appropriate warehouse layers.
* **Data Modeling** – Creating fact and dimension tables to organize the data for analytical purposes.
* **Analytics & Reporting** – Using SQL queries to analyze the data and generate useful business insights.

This project provides practical experience with areas such as:

* SQL
* Data Engineering
* ETL
* Data Warehousing
* Data Modeling
* Data Analytics

---

## Tools & Resources

The project was developed using freely available tools and resources:

* **Datasets** – CSV files containing the source ERP and CRM data.
* **SQL Server Express** – Used to host and manage the project database.
* **SQL Server Management Studio (SSMS)** – Used to create, manage, and query the SQL Server database.
* **Git & GitHub** – Used for version control and project organization.
* **Draw.io** – Used to create the architecture and data model diagrams.

---

## Project Requirements

### Data Warehouse

#### Objective

Build a SQL Server data warehouse capable of combining sales information from different source systems and making it easier to analyze and report on.

#### Main Requirements

* **Data Sources**: Use data from two different systems, ERP and CRM, provided as CSV files.
* **Data Cleaning**: Identify and correct data quality problems before making the data available for analysis.
* **Data Integration**: Bring the information from both sources together into a consistent data model.
* **Data Scope**: Work only with the most recent available data. Historical tracking is outside the scope of this project.
* **Documentation**: Document the data model and the main processes to make the project easier to understand and maintain.

---

### Analytics & Reporting

#### Objective

Use SQL to analyze the data warehouse and generate insights related to the company's sales activity.

The analysis focuses mainly on:

* **Customer Behavior**
* **Product Performance**
* **Sales Trends**


