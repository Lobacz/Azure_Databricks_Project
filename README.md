# Star Schema and SCD1 with Azure Data Factory and Databricks

## 📖 Project Overview  

In this project, I used Azure Data Factory (ADF) and Databricks to build a data pipeline that extracts data from GitHub, processes it, and loads it into Azure Data Lake Storage Gen2. I created dimension and fact tables in Databricks, applying SCD Type 1 to manage historical data changes. A SQL Database was also used to store processed data for further analysis. ADF orchestrated the ETL process, while Azure Storage Gen2 provided scalable and secure data storage.

---
## 🏠 Project Architecture
![architecture](ScreenShots/Architecture.png)


## 📊 Dataset  
The dataset comprises ten CSV files, one for 
- **SalesDate**: Contains information about car sales
- **IncrementalSales**: Includes new data to test incremental load
---

## 🔧 Azure Services Utilized
### 1. Azure Data Factory (ADF)
### 2. Azure Data Lake Storage Gen2 (ADLS Gen2)
### 3. Azure Databricks

---
## 🛠️ ETL Process  

1. **Data Ingestion**

- **CopySalesData**: Bulk load all sales data from Github repository to `bronze` folder in ADLS Gen2.
- **Increm_data_pipeline**: Pipleline for incremental load new sales data

![ADF1](ScreenShots/adf1.png)
![ADF2](ScreenShots/adf1.png)


2. **Data Transformation**  
in proggres


## ✨ Key Features  
in proggres

---

 ## 📌 Conclusion 
 
in proggres
---
## 👤 Author
- **Name**: Adrian Łobacz
- **Contact**: adrianlobacz.1998@wp.pl
- **LinkedIn**: https://www.linkedin.com/in/adrian-%C5%82obacz-37b66a206/
  
Feel free to contact with me!
