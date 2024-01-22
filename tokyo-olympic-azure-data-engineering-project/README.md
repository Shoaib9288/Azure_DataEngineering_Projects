# Tokyo Olympics Data Analytics | Azure End-To-End Data Engineering Project
<img align="center" width="500" src="https://github.com/Shoaib9288/Study_Materials/blob/main/Images_GIF/Tokyo%20Olympics.jpg">

## Table of Contents
- [Introduction](#introduction)
- [Architecture](#architecture)
- [Dataset Used](#Dataset-Used)
- [Azure Services Used](#Azure-Services-Used)
  - [Prerequisites](#prerequisites)
- [Data Ingestion](#Data-Ingestion)
- [Data Processing](#Data-Transformation)
- [Data Analysis](#Data-Analysis)

## Introduction
This project provides a data engineering and anlytical journey on the Tokyo Olympic dataset. Starting with a CSV on GitHub, the data is ingested into the Azure ecosystem via Azure Data Factory. It's initially stored in Azure Data Lake Storage Gen2, then transformed in Azure Databricks. The enriched data, once again housed in ADLS Gen2, undergoes advanced analytics in Azure Synapse. The insights are finally visualized in Azure Synapse or Power BI, offering a comprehensive view of the dataset.

## Architecture
<img align="center" width="900" src="https://github.com/Shoaib9288/Azure_DataEngineering_Projects/blob/main/tokyo-olympic-azure-data-engineering-project/Snapshots/Architecture.JPG">

## Dataset Used
This contains the details of over 11,000 athletes, with 47 disciplines, along with 743 Teams taking part in the 2021(2020) Tokyo Olympics. This dataset contains the details of the Athletes, Coaches, Teams participating as well as the Entries by gender. It contains their names, countries represented, discipline, gender of competitors, name of the coaches.

Source(Kaggle): [2021 Olympics in Tokyo](https://www.kaggle.com/datasets/arjunprasadsarkhel/2021-olympics-in-tokyo)

## Azure Services Used

1. **Azure Data Factory**: For data ingestion from GitHub.
2. **Azure Data Lake Storage Gen2**: As the primary data storage solution.
3. **Azure Databricks**: For data transformation tasks.
4. **Azure Synapse Analytics**: To perform in-depth data analytics.

## Prerequisites

- Azure subscription
- Azure Databricks workspace
- Azure Data Factory instance
<img align="center" width="800" src="https://github.com/Shoaib9288/Azure_DataEngineering_Projects/blob/main/tokyo-olympic-azure-data-engineering-project/Snapshots/Resource%20Groups.PNG">

## Data Ingestion
- Ingesting the source data using Azure Data Factory(ADF)
<img align="center" width="800" src="https://github.com/Shoaib9288/Azure_DataEngineering_Projects/blob/main/tokyo-olympic-azure-data-engineering-project/Snapshots/Data%20Ingestion.PNG">

## Data Transformation
- Transforming the data using Azure Databricks
<img align="center" width="800" src="https://github.com/Shoaib9288/Azure_DataEngineering_Projects/blob/main/tokyo-olympic-azure-data-engineering-project/Snapshots/Data%20Transformation-Using-Databricks.gif">

## Data Analysis
- Analyzing the transformed data using Azure Synapse Analytics & PowerBI tool

1. Using Azure Synapse to find the Number of Athletes from each country
<img align="center" width="700" src="https://github.com/Shoaib9288/Azure_DataEngineering_Projects/blob/main/tokyo-olympic-azure-data-engineering-project/Snapshots/Data%20Analytics-1.PNG">

2. Using PowerBI tool to create a visualization report
<img align="center" width="700" src="https://github.com/Shoaib9288/Azure_DataEngineering_Projects/blob/main/tokyo-olympic-azure-data-engineering-project/Snapshots/PowerBIDashboard.png">







