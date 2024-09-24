# YouTube Data Engineering Analysis Project

This project focuses on managing, streamlining, and analyzing structured and semi-structured YouTube video data. The goal is to build a scalable ETL pipeline that processes large datasets from multiple sources, ensuring data integrity and creating insightful reports using AWS services.

## Project Overview
This project aims to securely manage, streamline, and perform analysis on YouTube videos based on various categories and trending metrics. Data is processed through an ETL pipeline, stored in a centralized data lake, and visualized using reporting tools to derive actionable insights.

### Key Features:
- **Data Ingestion:** Use AWS S3 to ingest structured and semi-structured data from multiple sources.
- **Data Transformation:** AWS Glue for data cleaning and transformation.
- **Querying:** AWS Athena for efficient querying of large datasets directly from S3.
- **Serverless Computing:** AWS Lambda to automate tasks without managing servers.
- **Visualization:** Amazon QuickSight for generating reports and visualizing YouTube video trends and metrics.

## Technologies Used
- **Amazon S3**: Centralized data lake to store raw and processed data.
- **AWS Glue**: Serverless ETL tool for data transformation and cataloging.
- **AWS Lambda**: Automates code execution for data pipeline tasks.
- **AWS Athena**: Query service to analyze data stored in S3.
- **Amazon QuickSight**: For building interactive dashboards and visualizations.
- **AWS IAM**: Secured access management for AWS resources.

## Dataset
The dataset contains daily statistics for popular YouTube videos from multiple locations, including video titles, channel names, views, likes, dislikes, and more.

- [YouTube Trending Dataset](https://www.kaggle.com/datasets/datasnaek/youtube-new)

## Architecture
The following architecture was implemented:
1. Data Ingestion from Kaggle to AWS S3.
2. Data transformation using AWS Glue.
3. Querying and analytics with AWS Athena.
4. Automating tasks using AWS Lambda.
5. Creating visual reports using Amazon QuickSight.


