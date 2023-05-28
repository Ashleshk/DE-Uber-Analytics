# Notes

# Data Engineering GCP Project 

# GCP Services
1. **Cloud Storage** 
    - Google Cloud Storage is an online file storage service provided by Google as part of its cloud computing platform. 
    - It allows you to store and retrieve your data in the cloud, making it accessible from anywhere with an internet connection.

2. **Compute Engine**
    - Google Compute Engine is a cloud computing service that provides virtual machines for running applications and services. 
    - It allows you to easily create, configure, and manage virtual machines with various operating systems and hardware configurations.

3. **BigQuery**
    - BigQuery is a cloud-based data warehouse provided by Google Cloud Platform that allows you to store, analyze, and query large datasets using SQL-like syntax. 
    - It is a serverless, highly scalable, and cost-effective solution that can process and analyze terabytes to petabytes of data in real-time.

4. **Looker** 
    - Looker Studio is a web-based data visualization and reporting tool that allows you to create interactive dashboards and reports from a variety of data sources, including Google Analytics, Google Sheets, and BigQuery. 
    - It enables you to turn your data into informative and engaging visualizations, which can be easily shared and collaborated on with others.


## Main Tools
**Data pipeline tools** 
- These are software solutions used to automate the process of extracting, transforming, and loading (ETL) data from various sources into a data warehouse or data lake. 
    - These tools provide a way to efficiently collect, process, and deliver data for analysis, reporting, and other data-driven tasks. Here are some popular data pipeline tools:
        - **Apache Airflow**: open-source platform used to programmatically author, schedule, and monitor workflows.
        - **Apache Kafka**: Kafka is a distributed streaming platform,high-throughput, fault-tolerant messaging and allows you to build real-time data pipelines by efficiently collecting, processing, and delivering data streams.
        - **AWS Glue**: Glue is a fully managed ETL service by AWS. It simplifies the process of building and managing data pipelines by providing a serverless environment for data preparation and transformation. Glue integrates with other AWS services like S3, Redshift, and Athena Mage, Amazon Kinesis, etc
        - **Google Cloud Dataflow**: It supports both batch and stream processing and provides a programming model based on Apache Beam for building data transformation workflows.
        - **Informatica PowerCenter**: PowerCenter is a popular enterprise ETL tool that enables organizations to extract, transform, and load data from various sources. 

    - AND THERE IS One More - **MAGE** (says, just write code logic, Mage will handle DE)

1. **Mage**
    - Open-source data pipeline tool for transforming and integrating data.



## Concepts: 
1. Fact & Dimension Table
    - **Fact Table:**
        - Contains quantitative measures or metrics that are used for analysis
        - Typically contains foreign keys that link to dimension tables
        - Contains columns that have high cardinality and change frequently
        - Contains columns that are not useful for analysis by themselves, but are necessary for calculating metrics
    - **Dimension Table:**
        - Contains columns that describe attributes of the data being analyzed
        - Typically contains primary keys that link to fact tables
        - Contains columns that have low cardinality and don't change frequently
        - Contains columns that can be used for grouping or filtering data for analysis