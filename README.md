**Overview**

This project demonstrates the implementation of a multi-layered SQL Data Warehouse using a Bronze-Silver-Gold architecture. It involves data ingestion from CRM and ERP systems, staging and transformation in structured layers, and final reporting-ready data in the Gold layer.


**Technologies Used**

**SQL (DDL/DML):** For table creation and data manipulation

**ETL Concepts:** Applied through structured procedural scripts

**Data Sources:** CSV files from CRM and ERP systems

**Data Quality:** Test scripts ensure integrity in Silver and Gold layers


**Setup Instructions**

Create the database environment.

Run init_database.sql to initialize schema.

Execute the DDL and procedure scripts in the bronze, silver, and gold folders sequentially.

Use the test scripts in the tests/ directory to validate data quality.


**Project Goal**

The aim is to create a clean, well-structured data warehouse that integrates CRM and ERP data sources, supports transformation layers, and ensures reliable, analytics-ready datasets.
