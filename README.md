# technical_concepts
Note: This repository stores information about all the jargons in data

## Data WareHouse:
A subject-oriented, integrated, time-variant and non-volatile collection of data in support of the management's decision making process.

Subject-oriented? How?
-- A DWH is always focused on a specific business area, like 'Sales', 'Customers', 'Products', etc...

Integrated? How?
-- It helps in integrating or combining multiple source systems.
-- Usually, a DWH will integrate data from multiple sources like, 'APIs', 'Files', 'SQL Servers', etc...

Time-variant
-- A user can store historical data in the DWH

Non-volatile
-- Once the data is stored in the DWH, the data is not deleted nor modified.

----------------------------------------------------------------------------------------------------------------------------------------------------------------

## ETL:
-- It is a data integration process used to collect data from multiple sources, clean & transform it, & then load it into a data warehouse for analysis & reporting.
-- In simple words, ETL is the pipeline that moves raw data → into meaningful, analysis-ready data.

### Why is ETL Needed?
In real-world systems, data is scattered across different places:
1. Databases (SQL Server, Oracle, MySQL)
2. Applications (CRM, ERP systems)
3. Files (Excel, CSV, JSON)
4. APIs / Web services

### ❗ Problems without ETL:
1. Data is inconsistent --> Different formats (e.g., dates, currencies).
2. Data is incomplete or dirty --> Missing values, duplicates, etc...
3. Data is siloed --> No single source of truth.
4. Reporting becomes slow and unreliable.

### ✅ ETL solves these problems:
1. Data from multiple sources --> Combines data into one place.
2. Dirty data --> Cleans & standardizes.
3. Inconsistent formats --> Applies transformation rules.
4. Slow reporting --> Prepares data for fast querying.

### ETL Architecture:
🔹 Components:
1. Source Systems --> OLTP databases, APIs, files.
2. Staging Area --> Temporary storage for raw data.
3. ETL Engine --> Performs transformation logic.
4. Data Warehouse --> Stores structured, analytical data.

Source Systems → Staging Area → ETL Processing → Data Warehouse → Reports/Dashboards

### Types of ETL:
1. Batch ETL: Runs at scheduled intervals (daily, hourly).
2. Real-time ETL: Processes data instantly (streaming).
3. Near Real-time ETL: Small delays (minutes).



<img width="1907" height="861" alt="Data Architecture" src="https://github.com/user-attachments/assets/02ea8acb-70dc-41ca-b1e2-9fbcd34d8475" />



