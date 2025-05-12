**SQL Data Warehouse Project | End-to-End ETL Architecture**


🔹**Overview**:

➔This project demonstrates the design and implementation of a complete Data Warehouse pipeline using Microsoft SQL Server.
It simulates CRM and ERP data integration through a Bronze → Silver → Gold layered architecture, emphasizing data quality, transformation, and reporting readiness.

➔The project showcases advanced SQL skills in data ingestion, cleansing, aggregation, and validation, following industry-standard best practices.



🔹**Technologies Used**:

➤SQL Server / Azure SQL Database

➤T-SQL (Stored Procedures, DDL, DML, Testing)

➤CSV Files (Source system simulation)



🔹**Project Objectives**:

➤Ingest structured data from multiple source systems (CRM and ERP).

➤Apply data quality checks to ensure consistency, accuracy, and completeness.

➤Transform raw data into cleaned, standardized formats.

➤Aggregate key business metrics for analytics and reporting.

➤Build a scalable warehouse structure ready for BI tools.



🔹**Key Components**:

| Layer  | Purpose                                                |
| :----- | :----------------------------------------------------- |
| Bronze | Raw data ingestion with minimal transformations.       |
| Silver | Cleaned, deduplicated, and standardized business data. |
| Gold   | Aggregated, analytics-ready datasets for reporting.    |



🔹**Process Workflow**:

❖ **Database Initialization**:

➤Setup schema and structure using init_database.sql.

❖ **Bronze Layer**:

➤Create Bronze tables: bronze/ddl_bronze.sql

➤Load raw CRM and ERP data: bronze/proc_load_bronze.sql

❖ **Silver Layer**:

➤Create Silver tables: silver/ddl_silver.sql

➤Transform and cleanse data: silver/proc_load_silver.sql

❖ **Gold Layer**:

➤Create Gold tables: gold/ddl_gold.sql

➤Aggregate metrics for business reporting.

❖ **Data Quality Assurance**:

➤Validate data at Silver and Gold stages using tests/quality_checks_silver.sql and tests/quality_checks_gold.sql.



🔹**Business Problems Addressed**:

❖ **Data Consistency**: Standardized customer, product, and transaction records.

❖ **Inventory Management**: Simulated ERP stock updates post-sales.

❖ **Revenue Tracking**: Prepared Gold tables with revenue, profit, and trend metrics.

❖ **Anomaly Detection**: Built-in quality checks for missing data and outliers.



🔹**Dataset Summary**:

| Source | Files                                                | Description                                                        |
| :----- | :--------------------------------------------------- | :----------------------------------------------------------------- |
| CRM    | `cust_info.csv`, `prd_info.csv`, `sales_details.csv` | Customer profiles, product catalog, and sales transactions.        |
| ERP    | `CUST_AZ12.csv`, `LOC_A101.csv`, `PX_CAT_G1V2.csv`   | Customer master records, location details, and product categories. |




🔹**Highlights**:

➤End-to-End ETL Process designed and built fully with SQL.

➤Comprehensive Data Cleansing to prepare trusted datasets.

➤Business-Ready Outputs for seamless BI integration.

➤Data Validation at multiple layers to ensure integrity.



🔹**Future Enhancements**:

➤Enable real-time data ingestion using streaming architecture.

➤Integrate predictive analytics for revenue forecasting.

➤Expand the model to additional business domains (logistics, finance).



🔹**About**:

➔This project reflects a real-world Data Engineering and ETL scenario using SQL technologies, demonstrating best practices in data ingestion, cleaning, transformation, validation, and reporting preparation.

➔It serves as a strong portfolio project for roles in Data Engineering, Business Intelligence, and Analytics Engineering.
