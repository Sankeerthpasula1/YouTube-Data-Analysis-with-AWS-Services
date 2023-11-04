# Data Engineering YouTube Analysis Project

This repository contains the code and visualizations for a data engineering project focused on analyzing YouTube data using AWS services and generating insights through Amazon QuickSight.

## Overview

This project aims to securely manage, transform, and analyze structured and semi-structured YouTube video data. It leverages various AWS services for data ingestion, ETL, and visualization through QuickSight. The analysis includes insights such as category-wise likes, regional viewership metrics, and highest viewed categories.

## Files and Folders

- **Lambda_Code/**: Contains the Lambda function code used for data ingestion and transformation.
- **Glue_Scripts/**: Includes the Glue ETL script used for cataloging and transforming the dataset.
- **SQL_Queries/**: Holds SQL queries used in Amazon Athena for data analysis.
- **QuickSight_Images/**: Contains screenshots and images of visualizations and dashboards created in Amazon QuickSight.
- **Datasets/**: Includes the YouTube dataset files, organized by regions in S3 buckets.

## QuickSight Visualizations

The QuickSight_Images folder contains visualizations created in Amazon QuickSight, displaying analytical insights derived from the processed YouTube dataset. These images showcase data visualizations, including graphs, charts, and dashboards.

## Getting Started

To navigate through the project:
1. Refer to the specific folders for Lambda code, Glue scripts, SQL queries, and dataset files.
2. Explore the QuickSight_Images folder to view the visualizations generated.

## Usage

- Review the Lambda and Glue scripts for understanding the data transformation process.
- Utilize the SQL queries in Athena for performing analyses on the stored dataset.
- Refer to the QuickSight images to understand the visualized insights and dashboards.

## Prerequisites

- AWS Account with access to Lambda, Glue, S3, Athena, and QuickSight services.
- Basic knowledge of AWS services and SQL would be helpful for implementation and analysis.

## License

This project is licensed under the [MIT License](link-to-license).
