# NYC-911-Data-Warehouse

## NYC 311 Service Request Data Warehouse

### Overview

The NYC 311 Service Request Data Warehouse project focuses on designing and implementing a data warehouse solution to analyze public service request data from the NYC 311 system. The project involves transforming raw service request data into a structured dimensional model to support efficient data analysis and reporting.

The data warehouse was developed using a fact and dimension table approach, following a star schema design. ETL processes were implemented to extract, clean, transform, and load data into the warehouse using SQL Server Integration Services (SSIS). Slowly Changing Dimensions (SCD Type 1 and Type 2) were applied to manage changes in dimension data over time.

A Power BI dashboard was developed on top of the data warehouse to visualize service request trends, identify patterns, and provide meaningful insights through interactive reports and analytics.

### Objectives

* Design and implement a data warehouse for NYC 311 service request data.
* Perform ETL operations to clean and transform raw data.
* Apply dimensional modelling techniques using fact and dimension tables.
* Implement Slowly Changing Dimensions for effective historical data management.
* Create interactive Power BI dashboards for data visualization and analysis.

### Technologies Used

* Microsoft SQL Server
* SQL Server Integration Services (SSIS)
* Power BI
* SQL
* Data Warehousing Concepts
* Star Schema Modelling
