# Unified_UW_data_pipeline

## Overview
This project extracts data from Unified_UW_queue, transforms the data, and loads it into a Snowflake database. The process uses AWS Lambda, AWS Glue, and S3 for the ETL (Extract, Transform, Load) process.

## Components
1. **Lambda Function**: Extracts data from Unified_UW_queue and stores it in S3.
2. **Glue Job**: Transforms the raw Unified_UW_queue data (policy, customer, agent).
3. **Snowflake**: Loads the transformed data into tables for querying and analysis.

## Files:
- **lambda_function.py**: Code for the AWS Lambda function to extract Unified_UW_queue data.
- **glue_job.py**: AWS Glue job to transform the raw data.
- **snowflake_queries.sql**: SQL queries and Snowpipe to load data into Snowflake.

## How to Use
1. Deploy the Lambda function in AWS.
2. Set up the Glue job with the provided script.
3. Use the SQL queries to create tables and load data into Snowflake.

## Contact
For questions, contact me at [anwar.shan2009@example.com].
