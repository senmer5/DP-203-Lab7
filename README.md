# DP-203-Lab7

# Using Delta Lake with Apache Spark in Azure Synapse Analytics

## 📊 Overview

Welcome to this project! In this exercise, you will learn how to use Delta Lake with Apache Spark in the context of Azure Synapse Analytics. You will build a modern Lakehouse architecture that can process both batch and streaming data, which is crucial for a scalable and efficient data engineering workflow.

## 📝 What You Will Do

During this exercise, you will perform the following steps:

### 🔧 Set Up an Azure Synapse Analytics Workspace
1. **Create Data Lake Storage Gen2**: Set up a storage account to hold your data and enable the use of Azure Data Lake Storage Gen2, which is a highly scalable and secure data storage solution.
2. **Set Up Apache Spark Pool**: Create an Apache Spark pool, which provides the necessary compute resources to run Spark-based processing jobs.

### 📁 Explore Data in the Data Lake
1. **Load CSV Files as DataFrames**: You will load CSV files into Spark as DataFrames, allowing you to process and transform the data.
2. **Convert Data to Delta Tables**: After loading the CSV data, you will convert it into Delta tables, which offer more advanced features like ACID transactions and schema enforcement compared to standard Parquet or CSV formats.

### 💾 Work with Delta Tables
1. **Update Existing Data**: Learn how to perform updates on Delta tables, including modifying records, which is essential for maintaining up-to-date datasets.
2. **Time Travel**: Utilize Delta Lake’s time travel feature to query previous versions of data. This allows you to recover older data states or debug issues by comparing different versions.
3. **Create Catalog Tables (External and Managed)**: You will create external and managed Delta tables in the Synapse catalog. Managed tables are fully managed by Synapse, while external tables link to data stored outside of the system.

### 📡 Simulate Streaming Data
1. **Process IoT Events with Delta as Sink**: Simulate IoT events and write them in real-time to a Delta table, providing an efficient and reliable way to handle streaming data.
2. **Store and Analyze Real-Time Data**: You will learn how to store real-time streaming data and perform analysis on it, enabling real-time decision-making processes.

### 🧠 Use SQL
1. **Query Delta Files Using Serverless SQL Pools**: Finally, you will use Synapse’s serverless SQL pool to execute SQL queries directly on Delta tables, without needing to provision dedicated resources, providing flexibility and cost-efficiency.

## 🧹 Clean Up Resources

After completing the exercise, don’t forget to clean up your resources to avoid unnecessary cost.

## 🔗 Resources

This exercise is based on the official Microsoft Learn material for the DP-203 certification:
- [Microsoft Learn GitHub - dp-203-azure-data-engineer](https://github.com/secedit/dp-203-azure-data-engineer)

## 🎯 Key Learning Outcomes

By the end of this project, you will be able to:
- Create, manage, and modify Delta tables in Azure Synapse Analytics.
- Write streaming data to Delta tables.
- Use Delta Time Travel to query historical data versions.
- Understand the differences between external and managed Delta tables.
- Run SQL queries on Delta files us
ing the serverless SQL pool in Synapse.

## Screenshots

<img width="978" alt="1" src="https://github.com/user-attachments/assets/8bd0fd3a-baad-4db2-82de-9fa804884e8f" />

<img width="977" alt="2" src="https://github.com/user-attachments/assets/b225e46b-8b55-43c5-8f30-4ea98277e1df" />

<img width="976" alt="3" src="https://github.com/user-attachments/assets/4a079a9e-0a3e-408e-a0f0-0c2b6016e8a4" />

<img width="976" alt="4" src="https://github.com/user-attachments/assets/177a6628-0c3b-4da1-90ee-2f06c63e5120" />

<img width="979" alt="5" src="https://github.com/user-attachments/assets/7b070998-e1d8-42e3-89f7-dd0a7114a5eb" />

<img width="977" alt="7" src="https://github.com/user-attachments/assets/0dc7459d-1d44-4a17-a99e-7a08461b25ec" />

<img width="975" alt="9" src="https://github.com/user-attachments/assets/3a9343c8-a3e7-4140-b719-06dd1075ffb7" />

<img width="979" alt="10" src="https://github.com/user-attachments/assets/b456c9a4-70d0-4b02-b89e-bf303d673966" />
