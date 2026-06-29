 
# DATA-WAREHOUSE-SQL-PROJECT
Building a Modern Data WaeHouse with SQL Sever Including SQL Sever, ETL Process, Data Modeling and Analytics
...

# Data Warehouse and Analytics Project

Welcome to the **Data Warehouse and Analytics Project** repository! 🚀  
This project demonstrates a comprehensive data warehousing and analytics solution, from building a data warehouse to generating actionable insights. Designed as a portfolio project, it highlights industry best practices in data engineering and analytics.
## DIAGRAMS FLOW

<img width="527" height="430" alt="Screenshot 2026-06-29 060307" src="https://github.com/user-attachments/assets/32b1c8ee-7f71-480a-8355-0f79d340b491" />
<img width="479" height="439" alt="Screenshot 2026-06-29 064048" src="https://github.com/user-attachments/assets/e13e9ac0-e8a2-45de-8a92-2d031963e76b" />

<img width="497" height="437" alt="Screenshot 2026-06-29 064313" src="https://github.com/user-attachments/assets/efae6ede-04b5-4be9-b21b-68647bcd5e9a" />
<img width="584" height="411" alt="Screenshot 2026-06-29 064418" src="https://github.com/user-attachments/assets/02d13ff5-68ed-4b68-9846-f32444b97668" />


---
## 🏗️ Data Architecture

The data architecture for this project follows Medallion Architecture **Bronze**, **Silver**, and **Gold** layers:
![Data Architecture]  <img width="527" height="430" alt="Screenshot 2026-06-29 060307" src="https://github.com/user-attachments/assets/e04aaf39-ca08-41b4-8097-9039e1481377" />
 [Data ArchiTecture_Diagram.drawio…]()


1. **Bronze Layer**: Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.
2. **Silver Layer**: This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.
3. **Gold Layer**: Houses business-ready data modeled into a star schema required for reporting and analytics.

---
## 📖 Project Overview

This project involves:

1. **Data Architecture**: Designing a Modern Data Warehouse Using Medallion Architecture **Bronze**, **Silver**, and **Gold** layers.
2. **ETL Pipelines**: Extracting, transforming, and loading data from source systems into the warehouse.
3. **Data Modeling**: Developing fact and dimension tables optimized for analytical queries.
4. **Analytics & Reporting**: Creating SQL-based reports and dashboards for actionable insights.

🎯 This repository is an excellent resource for professionals and students looking to showcase expertise in:
- SQL Development
- Data Architect
- Data Engineering  
- <img width="160" height="160" alt="img icons8" src="https://github.com/user-attachments/assets/84a50a4f-dd15-4ba7-b80d-6937cf2afb29" />
 ETL Pipeline Developer  
- Data Modeling  
- Data Analytics  

---

## 🛠️ Important Links & Tools:

Everything is for Free!
- **[  <img width="60" height="60" alt="img icons8" src="https://github.com/user-attachments/assets/bb7fcb6f-c7d9-45b8-9f37-94bcc40ca288" />
Datasets](datasets/):** Access to the project dataset (csv files).
- **[SQL Server Express](https://www.microsoft.com/en-us/sql-server/sql-server-downloads):** Lightweight server for hosting your SQL database.
- **[SQL Server Management Studio (SSMS)](https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver16):** GUI for managing and interacting with databases.
- **[Git Repository](https://github.com/):** Set up a GitHub account and repository to manage, version, and collaborate on your code efficiently.
- **[  <img width="160" height="160" alt="img icons8" src="https://github.com/user-attachments/assets/e7a819d8-8f51-4fb5-82db-e0b124ca3927" />
DrawIO](https://www.drawio.com/):** Design data architecture, models, flows, and diagrams.
- **[  <img width="160" height="160" alt="img icons8" src="https://github.com/user-attachments/assets/c6c4418f-9259-4eb9-b1c3-d0534abc4e88" />
Notion](https://www.notion.com/):** All-in-one tool for project management and organization.
- **[VISIT MY PROFILE IN Notion Project Steps]( https://www.notion.so/DATA-WAREHOUSE-3888690bba8380eb83e1dde4d99b96a1?source=copy_link 
):** Access to All Project Phases and Tasks.

---

## 🚀 Project Requirements

### Building the Data Warehouse (Data Engineering)

#### Objective
Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.

#### Specifications
- **Data Sources**: Import data from two source systems (ERP and CRM) provided as CSV files.
- **Data Quality**: Cleanse and resolve data quality issues prior to analysis.
- **Integration**: Combine both sources into a single, user-friendly data model designed for analytical queries.
- **Scope**: Focus on the latest dataset only; historization of data is not required.
- **Documentation**: Provide clear documentation of the data model to support both business stakeholders and analytics teams.

---

### BI: Analytics & Reporting (Data Analysis)

#### Objective
Develop SQL-based analytics to deliver detailed insights into:
- **Customer Behavior**
- **Product Performance**
- **Sales Trends**

These insights empower stakeholders with key business metrics, enabling strategic decision-making.  

For more details, refer to [docs/requirements.md](docs/requirements.md).

## 📂 Repository Structure
```
data-warehouse-project/
│
├── datasets/                           # Raw datasets used for the project (ERP and CRM data)
│
├── docs/                               # Project documentation and architecture details
│   ├── etl.drawio                      # Draw.io file shows all different techniquies and methods of ETL
│   ├── data_architecture.drawio        # Draw.io file shows the project's architecture
│   ├── data_catalog.md                 # Catalog of datasets, including field descriptions and metadata
│   ├── data_flow.drawio                # Draw.io file for the data flow diagram
│   ├── data_models.drawio              # Draw.io file for data models (star schema)
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


## 🛡️ License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and share this project with proper attribution.

## 🌟 About Me

Hi there! I'm **ALLY SUDI**, also known as **DATA IN MOTION**. I’m an IT professional and   on a mission to share knowledge and make working with data enjoyable and engaging!

Let's stay in touch! Feel free to connect with me on the following platforms:
 WHATSAPP <img width="96" height="96" alt="img icons8" src="https://github.com/user-attachments/assets/d1e75870-5652-4e27-8cbd-aa2cccce01af" />  <img width="60" height="60" alt="img icons8" src="https://github.com/user-attachments/assets/2bee14f2-6ab6-464e-9aff-79b9b724d61b" />
0693470106
 
