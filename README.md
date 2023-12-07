# Azure_Data_Lakehouse_ETL_Pipeline-Project

This project is designed to showcase the end-to-end process of migrating data from an On-Premise database to the cloud, transforming it through a lakehouse architecture, and performing data analysis using Azure services. 

## Tools Used
* Azure Data Factory (ADF)
* Azure Data Lake Storage Gen2
* Azure Databricks
* Azure Synapse Analytics
* Azure Key Vault
* Azure Active Directory (AAD)
* Microsoft Power BI

## Architecture
The project follows a Lakehouse architecture with data layers (bronze, silver, gold) for different stages of data transformation and storage.

## Steps
1. **Environment Setup:** Creation of a resource group, including Azure Data Factory (ADF), Azure Data Lake Storage Gen2, Azure Databricks, Azure Synapse Analytics, Azure Key Vault, and Azure Active Directory (AAD).and deployment of Azure services.
2. **Data Ingestion:** Transferring data from on-prem SQL server to Azure Data Lake Storage Gen2 using ADF.
3. **Data Transformation:** Utilizing Azure Databricks for transforming raw data into curated data through the implementation of a Lakehouse architecture. Implemented Bronze, Silver, and Gold layers for progressively refining and cleaning the data.
4. **Data Loading:**  Transfer the processed data from the Gold layer of Azure Data Lake Storage Gen2 to Azure Synapse Analytics, setting up databases and tables to resemble the on-premise SQL database.
5. **Data Reporting:** Using Power BI to create interactive Dashboard on the migrated data stored in Azure Synapse Analytics.
6. **Security and Governance:** Implementing security using Azure Active Directory and Azure Key Vault.
7. **End-to-End Pipeline Testing:** Thoroughly test the entire ETL pipeline to ensure seamless data flow and identify and resolve any potential issues.
   

