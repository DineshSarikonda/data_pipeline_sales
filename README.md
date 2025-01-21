🔧 Analyzing Sales of AdventureWorks
On-Premises Database to Azure Cloud Data Pipeline
Technologies: Azure Data Factory, Data Lake Storage, Databricks, Synapse Analytics, Power BI

📝 Table of Contents
Project Overview
Dataset
Project Goals
Key Insights
Project Architecture
Data Ingestion
Data Transformation
Data Loading
Data Reporting
Technologies Used
Credits
Contact
🔬 Project Overview
This project is an end-to-end data engineering solution implemented on Azure. It demonstrates how to migrate data from an on-premises SQL Server to Azure Cloud for data transformation, analysis, and reporting.
Key highlights include:

Data Ingestion: Using Azure Data Factory to migrate data into Azure Data Lake.
Data Transformation: Cleaning and optimizing data with Databricks and Spark.
Data Loading: Efficiently loading transformed data into Synapse Analytics.
Data Reporting: Creating interactive visualizations with Power BI.
Governance: Implementing Azure Active Directory (AAD) and Key Vault for secure data handling.
💾 Dataset
The project uses the AdventureWorks sample database by Microsoft.
Key points about the dataset:

Represents a manufacturing company, Adventure Works Cycles.
Designed as an OLTP (Online Transaction Processing) database.
Includes tables for sales, customers, products, and more.
For this project, the Lightweight (LT) version of the dataset was used.
Download AdventureWorks LT Database

🎯 Project Goals
Establish a connection between an on-premises SQL Server and Azure Cloud.
Ingest data into Azure Data Lake Gen2.
Perform data cleaning and transformation using Databricks and Spark.
Load clean and optimized data into Azure Synapse Analytics.
Build interactive reports and dashboards with Power BI.
Ensure secure data handling with AAD and Key Vault.
🕵️ Key Insights
💸 Revenue by Product Category:
Top categories: Touring Bikes (32%), Road Bikes (26%), Mountain Bikes (24%).
🌍 Sales by Country:
United Kingdom (UK): $572,000 total revenue.
USA: $383,810 total revenue.
🚻 Revenue by Gender:
Male customers: 81% of total revenue.
Female customers: 19% of total revenue.
📝 Project Architecture
This project follows a modular architecture for efficient data processing and reporting.

📤 Data Ingestion
Connected the on-premises SQL Server to Azure via Microsoft Integration Runtime.
Migrated tables to Azure Data Lake Gen2 using Azure Data Factory.
Organized resources into a dedicated Resource Group.
⚙️ Data Transformation
Mounted Azure Blob Storage to Databricks.
Cleaned and transformed raw data using Spark Clusters.
Saved processed data in Delta format for optimization.
📥 Data Loading
Loaded refined data into Azure Synapse Analytics.
Created a SQL database connected to the Data Lake for analysis.
📊 Data Reporting
Connected Power BI to Azure Synapse to access clean data.
Designed interactive dashboards for insights into sales and revenue.
🛠️ Technologies Used
Data Source: SQL Server
Orchestration: Azure Data Factory
Storage: Azure Data Lake Gen2, Azure Synapse Analytics
Transformation: Databricks, Spark
Governance: Azure Active Directory (AAD), Azure Key Vault
Reporting: Microsoft Power BI
👥 Credits
This project was designed and implemented by Dinesh Sarikonda.

📬 Contact
For inquiries or collaboration:

Email: sarikondadinesh23@gmail.com
GitHub: DineshSarikonda
