# Real-Time Stock Market Data Pipeline with Kafka and AWS

## Project Overview
This project demonstrates a real-time data pipeline for stock market data. It integrates Apache Kafka for data streaming and multiple AWS services for data storage and querying.

![Architecture-Diagram](https://github.com/user-attachments/assets/fbe4cc9f-7a65-4779-9b6b-f481dc79b948)

### Key Features:
- **Real-time data ingestion** using Kafka Producer.
- **Data storage** in AWS S3 via Kafka Consumer.
- **Data cataloging** using AWS Glue Crawler.
- **Data querying** with AWS Athena for analysis.

## Architecture
1. **EC2 Instance**: Hosts Kafka and Zookeeper.
2. **Kafka Producer**: Generates stock market data.
3. **Kafka Consumer**: Consumes data and sends it to S3.
4. **S3 Bucket**: Stores real-time data.
5. **AWS Glue Crawler**: Creates data catalog from S3.
6. **AWS Athena**: Queries data for insights.

## Technologies Used:
- Apache Kafka
- AWS S3
- AWS Glue Crawler
- AWS Athena
- EC2 Instance

## Conclusion:
This pipeline ensures efficient handling of real-time data for analysis and decision-making in financial markets.

---

## Author:
Umair - *Data Engineering Enthusiast*
