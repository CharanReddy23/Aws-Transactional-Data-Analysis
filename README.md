Transactional Data Analysis & Batch Processing on AWS

This project demonstrates an Automated cloud based ETL pipeline for batch processing and analysis of transactional data using AWS services.  

 Project Overview

Objective:Automate ingestion, transformation, and analysis of large transactional datasets
Pipeline Components:
  1.Amazon S3 → Raw data storage
  2.AWS Glue → ETL jobs for data cleaning and transformation using PySpark
  3.Amazon Athena→ Serverless SQL queries for analysis
  4.Amazon QuickSight→ Interactive dashboards and visualization
  5.AWS Data Catalog / Redshift→ Structured storage and queries


Key Features

- Automated ETL pipeline using AWS Glue and PySpark
- Data cleaning & transformation for transactions, cards, and financial records
- Serverless SQL-based analysis using Athena
- Real-time dashboards using QuickSight for business insights
- Achieved 50% reduction in manual analysis time through automation

Architecture

1. Raw data ingested into Amazon S3  
2. Glue ETL jobs process and transform data  
3. Processed data stored in S3 / Data Catalog / Redshift  
4. Athena queries data for analysis  
5. QuickSight visualizes results in dashboards

Tech Stack

-AWS Services: S3, Glue, Athena, QuickSight, Data Catalog, IAM
-Programming: Python (PySpark for ETL)
-Analytics: SQL for Athena
-Visualization: AWS QuickSight

Results

- Automated batch ETL pipeline for transactional data  
- Enabled self-service analytics through Athena and QuickSight  
- Reduced manual analysis time by 50%  
- Provided scalable, cloud-native data solution

