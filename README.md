# Data_Engineering_Project

Stock Market Real Time Data Engineering Project 

This project covers end-to-end real time data streaming pipeline of Stock Market data using Apache Kafka and AWS Services like EC2, S3, Glue Crawler, Glue Catalog and Athena. Scripts are created using Python programming language and Jupyter notebooks.

Below steps are used for the overall pipeline:

1. Launch an EC2 Instance.
2. Kafka and its dependencies are installed on an EC2 Instance.
3. Producer and Consumer scripts are created through Jupyter notebook.
4. Producer Script is extracting data from a CSV dataset and sending the data to a topic to kafka broker.
5. Consumer script will get the data from topic and it will upload it to S3.
6. Further, AWS Glue Crawler and Glue Catalog will read all the Json files and create a table.
7. Then, we can query the data using AWS Athena.
