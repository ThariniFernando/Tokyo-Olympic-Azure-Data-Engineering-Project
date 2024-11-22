Azure Data Engineering Project: Tokyo 2021 Olympics Data Pipeline

This project demonstrates an end-to-end Azure Data Engineering pipeline, built to process and analyze 2021 Tokyo Olympics data. The solution leverages multiple Azure services to handle data ingestion, transformation, and analytics seamlessly.

Architecture Overview

Data Ingestion:
Azure Data Factory was used to ingest raw data from the source system into Azure Data Lake Gen2, ensuring efficient and reliable data transfer.
Data Storage:
Raw data is stored in Azure Data Lake Gen2 as the centralized data store for further processing.

Data Transformation:
Azure Databricks (PySpark) was employed for cleaning, transforming, and aggregating data into a structured format.
Transformed Data Storage:
The cleaned and processed data was stored back in Azure Data Lake Gen2 to serve as the foundation for analytics.

Data Analytics and Reporting:
Azure Synapse Analytics was used to query and analyze the transformed data, enabling advanced insights and visualizations.

Technologies Used:
Azure Data Factory for data ingestion.
Azure Data Lake Gen2 for raw and transformed data storage.
Azure Databricks (PySpark) for data processing and transformation.
Azure Synapse Analytics for querying and analysis.
