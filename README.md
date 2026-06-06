# Gravity Books ETL Project

## Overview

This project demonstrates the design and implementation of an end-to-end ETL (Extract, Transform, Load) solution using SQL Server Integration Services (SSIS).

The objective was to extract data from the Gravity Books operational database, apply data cleansing and transformation rules, and load the processed data into a structured data warehouse to support reporting and business analytics.

---

## Project Objectives

* Extract data from multiple source tables.
* Perform data cleansing and transformation.
* Load data into a dimensional data warehouse.
* Improve data quality and consistency.
* Create an analytical foundation for reporting and decision-making.

---

## ETL Workflow

### Extract

Data was extracted from the Gravity Books source database, including information related to:

* Books
* Authors
* Customers
* Orders
* Order Details
* Publishers
* Shipping Information

### Transform

Several transformation operations were applied, including:

* Data validation and cleansing
* Handling null and missing values
* Data type conversion
* Standardization of data formats
* Business rule implementation
* Lookup transformations
* Derived column calculations

### Load

The transformed data was loaded into a data warehouse environment following dimensional modeling principles.

Typical warehouse components include:

* Fact Tables
* Dimension Tables
* Surrogate Keys
* Star Schema Design

---

## Tools & Technologies

* SQL Server Integration Services (SSIS)
* Microsoft SQL Server
* SQL
* SQL Server Data Tools (SSDT)
* Data Warehousing Concepts

---

## Data Warehouse Architecture

Source Database (Gravity Books)
↓
SSIS ETL Process
↓
Data Cleansing & Transformations
↓
Dimension Tables
↓
Fact Tables
↓
Reporting & Analytics

---

## Key Skills Demonstrated

* ETL Development
* Data Integration
* Data Transformation
* Data Warehousing
* Dimensional Modeling
* SSIS Package Development
* SQL Development
* Data Quality Management

---

## Learning Outcomes

Through this project, I gained hands-on experience in building ETL pipelines using SSIS, designing data warehouse structures, implementing transformation logic, and preparing business data for analytical reporting.

