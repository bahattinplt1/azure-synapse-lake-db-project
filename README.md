# azure-synapse-lake-db-project
Lake Database with SQL &amp; Spark in Azure Synapse Analytics

# Lake Database with SQL & Spark in Azure Synapse Analytics

This project demonstrates how to create and query a Lake Database using Azure Synapse Analytics, built-in serverless SQL pool, and Apache Spark.

## 🧰 Tools & Technologies

- **Azure Synapse Analytics**
- **Azure Data Lake Storage Gen2**
- **Serverless SQL Pool**
- **Apache Spark Pool**
- **Synapse Studio**
- **GitHub**

## 📁 Project Structure


## 📊 Tables Created in Lake Database

- `Customer`  
- `Product` (from template)  
- `SalesOrder` (from existing data)

Tables are stored in folders inside the Azure Data Lake under `files/RetailDB`.

## 🧪 SQL Scripts

- `Customer_Select.sql`: Retrieves all customer data  
- `product_join.sql`: Joins SalesOrder with Product and Customer tables to return enriched order info

## 🔥 Spark Notebook

The notebook includes:

- Insertion of a sample order into `SalesOrder` table
- Verification query using `%sql` in PySpark

## 💾 How to Run

> Prerequisites: Azure subscription, Synapse workspace, Spark pool, access to Synapse Studio

1. Clone this repository
2. Create a Lake Database in Synapse Studio
3. Upload CSVs to Data Lake
4. Use provided scripts to create tables and query data
5. Run notebook inside Spark pool

## 📸 Screenshots

> Visual highlights from the project

![Lake DB Created](screenshots/lake-db-created.png)  
![Query Result](screenshots/query-result.png)  
![Spark Insert](screenshots/spark-insert.png)

## 🧠 Learning Goals

- Understand how Lake Databases work in Azure  
- Practice creating structured tables over raw files  
- Learn how to use Spark + SQL in Synapse Studio  
- Get hands-on with data lake querying and schema overlay
