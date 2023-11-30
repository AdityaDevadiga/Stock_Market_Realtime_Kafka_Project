# Stock Market Kafka Real-Time Data Engineering Project

## Introduction 
In this project, you will execute an End-To-End Data Engineering Project on Real-Time Stock Market Data using Kafka.

We are going to use different technologies such as Python, Amazon Web Services (AWS), Apache Kafka, Glue, Athena, and SQL.

## Architecture 
![Architecture](https://github.com/AdityaDevadiga/Stock_Market_Realtime_Kafka_Project/assets/72966036/db22559d-8bba-4e6b-84b2-7d13d14b3e1b)


## Technology Used
- **Programming Language:** Python
- **Amazon Web Service (AWS):**
  1. **S3 (Simple Storage Service):** Used for storing raw and processed data.
  2. **Athena:** Query service to analyze data directly in S3 using SQL.
  3. **Glue Crawler:** Discovers and catalogs metadata about your data sources.
  4. **Glue Catalog:** Manages metadata tables for Glue and Athena.
  5. **EC2 (Elastic Compute Cloud):** Used for running applications on the AWS cloud.
- **Apache Kafka:** Distributed event streaming platform for building real-time data pipelines and streaming applications.

## Dataset Used
You can use any dataset; we are mainly interested in the operational side of Data Engineering (building a data pipeline).

## Additional Features
### AWS Services Overview
#### S3 (Simple Storage Service)
Amazon S3 is an object storage service that offers industry-leading scalability, data availability, security, and performance. It can be used to store and retrieve any amount of data at any time.

#### Athena
Amazon Athena is an interactive query service that makes it easy to analyze data directly in Amazon S3 using standard SQL. You can use Athena to run ad-hoc queries on your data stored in S3 without the need for complex ETL processes.

#### Glue Crawler
AWS Glue Crawler is a programmatic way to extract metadata from your data source. It identifies the schema and properties of your source data and stores this information in the AWS Glue Data Catalog.

#### Glue Catalog
AWS Glue Data Catalog is a fully managed metadata repository that makes it easy to find, access, and manage data in Amazon S3 and other data stores.

#### EC2 (Elastic Compute Cloud)
Amazon EC2 provides resizable compute capacity in the cloud. It is designed to make web-scale cloud computing easier for developers.

# Stock_Market_Realtime_Kafka_Project
