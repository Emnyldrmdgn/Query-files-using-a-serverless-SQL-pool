# Query-files-using-a-serverless-SQL-pool
Azure Synapse Analytics provides serverless SQL pools that enable you to decouple the SQL query engine from the data storage and run queries against data files in common file formats such as delimited text and Parquet.

# Azure Synapse Analytics - Data Querying and Visualization

This project involves querying, analyzing, and visualizing data using Azure Synapse Analytics. Various data file formats (CSV, JSON, Parquet) were queried using SQL, and meaningful insights were derived from the data. Additionally, the results were visualized to present the data analysis more effectively.

## Contents

1. **Azure Synapse Analytics Workspace Setup**  
   An Azure Synapse Analytics workspace was created in the Azure portal, and the Azure Data Lake Storage connection was established.

2. **Data Querying and File Types**  
   - **CSV Files**: SQL queries were executed on CSV files to retrieve the first 100 rows of data.  
   - **JSON Files**: SQL queries were run on JSON files to extract values from the JSON data.  
   - **Parquet Files**: SQL queries were executed on Parquet files to analyze the data.

3. **Data Visualization**  
   - SQL query results were visualized using the integrated charting tools in Synapse Studio.  
   - Line and column charts were used to visualize the annual revenue trend.

4. **Data Sources and External Databases**  
   External data sources were created using PolyBase to reference data stored in the data lake for more complex queries.  
   - **External Data Source**: An external data source was set up to allow SQL querying of data from the data lake.  
   - **External Table**: External tables were created to query data from CSV files.

5. **Resource Cleanup**  
   After completing the project, Azure Synapse Analytics resources were cleaned up to avoid unnecessary costs.

## Requirements

- Azure Subscription (Administrator-level access)
- Azure Synapse Analytics Workspace
- Azure Data Lake Storage Gen2
- SQL Knowledge

## Technologies Used

- **Azure Synapse Analytics**
- **SQL (Structured Query Language)**
- **Azure Data Lake Storage Gen2**
- **PolyBase**
- **Synapse Studio**

## Steps

1. Create an Azure Synapse Analytics workspace.
2. Upload data files to Azure Data Lake.
3. Query the data using SQL in Synapse Studio.
4. Visualize the query results.
5. Clean up resources once the project is completed.

## Outcomes

This project demonstrates how data querying and visualization processes can be simplified and how Azure Synapse Analytics can be used effectively for data analysis.

## ScreenShots

![lab21](https://github.com/user-attachments/assets/263806bb-620c-403c-800d-ddefda5cfad0)
![lab22](https://github.com/user-attachments/assets/71d7bdab-edbd-4dc1-8329-54bde4ab0ef8)
![lab23](https://github.com/user-attachments/assets/cb3e58ea-1c86-49c1-aa48-f6fef9958e8b)
![lab24](https://github.com/user-attachments/assets/cfe801a8-d519-4c72-9972-6866870eed41)
![lab25](https://github.com/user-attachments/assets/69c466aa-f24f-4518-afe2-ce071c616f40)
![lab26](https://github.com/user-attachments/assets/bd0f222d-b87e-4798-b926-8f2f4b098e38)
![lab27](https://github.com/user-attachments/assets/31f83b32-6fce-4cde-a37d-34ab256c35af)
![lab27properties](https://github.com/user-attachments/assets/977d9a5c-b2e4-46d9-b819-d91bbb9ba67a)
![lab28code](https://github.com/user-attachments/assets/b45568a8-fda1-441b-910c-c227b5b31789)
![lab28code2](https://github.com/user-attachments/assets/d80d65f3-8e47-4205-8941-18954be83841)
![lab28code3](https://github.com/user-attachments/assets/c3198210-98d3-4eab-b123-1d5b2d69878f)
![lab28code4](https://github.com/user-attachments/assets/5762e745-8d66-42dc-8f40-0d9d45d0f49c)
![lab29code](https://github.com/user-attachments/assets/98ab0d93-602b-4bb9-af28-06490534671d)
![lab29code2](https://github.com/user-attachments/assets/363c5f5d-1cc5-4225-ad49-ead5d5758280)
![lab210code](https://github.com/user-attachments/assets/332758ac-8bd3-4f06-bc61-651b1b67b913)
![lab2sqldatacode1-2](https://github.com/user-attachments/assets/c3e0bc63-d2dd-4a4b-85a2-6cbfe753bd23)
![lab2sqldatacode3](https://github.com/user-attachments/assets/ac2762ad-bf02-45b3-9c71-acb9e13dd355)
![lab2sqlchart1](https://github.com/user-attachments/assets/08658207-40da-4dd7-8d4a-4f5a39ecc236)
![lab2sqlchart2](https://github.com/user-attachments/assets/0d04546d-68c9-4c5b-883c-f23e582a5974)
![lab2sqlchart3](https://github.com/user-attachments/assets/b99e65e9-e3d1-4850-b56d-8fb7b5fed5cc)
