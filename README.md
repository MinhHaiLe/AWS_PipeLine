# AWS Data Pipeline Project

## Overview

This project implements a complete data pipeline deployed on AWS. The pipeline is designed to automatically ingest daily data, redirect the flow based on the package size, and store cleaned data in Amazon S3 using a track pathing method. The data is then crawled into the AWS Glue database and queried by Amazon Athena to update the dashboard.

## Features

- **Automated Data Ingestion**: Daily data ingestion is handled automatically.
- **Flow Diversion**: Data flow is redirected based on the size of the incoming package.
- **Data Storage**: Cleaned data is stored in Amazon S3 using a structured track pathing system.
- **Data Crawling and Querying**: Data is crawled into the AWS Glue database and queried by Amazon Athena.
- **Dashboard Updates**: The pipeline runs daily to ensure the dashboard is updated, providing the company with up-to-date insights for well-informed business decisions.
- **Error Notification**: If there are errors at any stage, the engineering team is notified promptly.

## Benefits

- **Timely Insights**: Ensure your business decisions are based on the latest data.
- **Automated Processing**: Reduce manual intervention with automated data handling.
- **Scalability**: Easily scale your data processing with AWS services.
- **Reliability**: Maintain a robust and dependable data pipeline.
- **Error Handling**: Stay informed about any issues with prompt error notifications.

## Getting Started

To deploy this pipeline on AWS, follow the setup instructions provided in the `INSTALL.md` file. Ensure you have the necessary AWS services configured, including S3, Glue, and Athena.

For more details on the project structure and implementation, refer to the `docs` folder.

---

This README provides a concise overview of the AWS Data Pipeline Project. For further assistance, please contact the project maintainers or open an issue in this repository.
