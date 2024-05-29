# Notes
Notes for tools, knowledge and concepts about Data Engineering and and some other roles (DevOps, DA, ...)


## Table of Contents
- [Notes](#notes)
  - [Table of Contents](#table-of-contents)
  - [Terms \& Concepts](#terms--concepts)
  - [Tools](#tools)
  - [Blogs](#blogs)
- [References](#references)


## Terms & Concepts
Data Engineering is a set of operations aimed at creating interfaces and mechanisms for the flow and access of data. It is a field that is responsible for the architecture that brings data from one place to another, and it is also responsible for working with data and making it available to data scientists for analysis. 

- **Data Pipeline**: A data pipeline is a series of data processing elements connected in series, where the output of one element is the input of the next. Elements can include sources, processors, sinks, and storage.
- **ETL**: ETL stands for Extract, Transform, Load. It is a process in data warehousing responsible for pulling data out of the source systems and placing it into a data warehouse.
- **Data Lake**: A data lake is a system or repository of data stored in its natural/raw format, usually object blobs or files. A data lake is usually a single store of all enterprise data including raw copies of source system data and transformed data used for tasks such as reporting, visualization, advanced analytics, and machine learning.
- **Data Warehouse**: A data warehouse is a system that stores data from multiple sources and transforms it into a format that analysts and business intelligence tools can use to perform complex queries and analysis.
- **Data Mart**: A data mart is a subset of a data warehouse that is designed for a particular line of business, such as sales, marketing, or finance.
- **Data Lakehouse**: A data lakehouse is a new data management paradigm that combines the best of data warehouses and data lakes. It provides the scalability and flexibility of a data lake with the performance and reliability of a data warehouse.
- **Data Modeling**: Data modeling is the process of creating a data model for an information system by applying formal data modeling techniques.
- **Data Integration**: Data integration is the process of combining data from different sources into a single, unified view.
- **Data Transformation**: Data transformation is the process of converting data from one format or structure into another format or structure.
- **Data Ingestion**: Data ingestion is the process of bringing data from external sources into a data storage system.
- **Data Analysis**: Data analysis is the process of inspecting, cleaning, transforming, and modeling data with the goal of discovering useful information, informing conclusions, and supporting decision-making.

## Tools
The nearly full list of tools for Data Engineering is mentioned in [this repo](https://github.com/DataExpert-io/data-engineer-handbook)

- **Orchestration**
  - [Airflow](https://airflow.apache.org/), [Astronomer](https://www.astronomer.io/), 
  - [Prefect](https://www.prefect.io/)
  - [Dagster](https://dagster.io/)
  - [Mage](https://www.mage.ai/)
- **Data Lake**
  - [AWS S3](https://aws.amazon.com/s3/) - Cloud storage
  - [Google Cloud Storage](https://cloud.google.com/storage) - Cloud storage
  - [Azure Data Lake Storage](https://azure.microsoft.com/en-us/services/storage/data-lake-storage/) - Cloud storage
  - [MinIO](https://min.io/) - Open-source object storage
  - [HDFS](https://hadoop.apache.org/docs/r1.2.1/hdfs_design.html) - Hadoop Distributed File System
- **Data Warehouse**
  - [AWS Redshift](https://aws.amazon.com/redshift/) - Cloud data warehouse
  - [Google BigQuery](https://cloud.google.com/bigquery) - Cloud data warehouse
  - [Azure Synapse Analytics](https://azure.microsoft.com/en-us/services/synapse-analytics/) - Cloud data warehouse
  - [Snowflake](https://www.snowflake.com/) - Cloud data warehouse
  - [PostgreSQL](https://www.postgresql.org/) - Open-source relational database
  - [Databrick](https://databricks.com/) - Unified data analytics platform


## Blogs
- [De Manejar](https://demanejar.github.io/) - Vietnamese
- [Long Nguyen](https://longcnttbkhn.github.io/blog/) - Vietnamese
- [Data Guy Story](https://www.dataguystory.com/) - Vietnamese
- [200Labs](https://200lab.io/blog/) - Vietnamese

# References
- [NTPH](https://ntphiep.github.io) 