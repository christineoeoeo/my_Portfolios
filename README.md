
# My Portfolio
big data projects

# [Project 1: Implement Big Data System for E-Commerce using AWS services ](https://github.com/christineoeoeo/bdsystem_aws)
* Create order history on mobile app, publish data using kinesis ds into lambda in order to handle massive amount of data
* Present product reccomendations to customers by aggregating and publishing customer data to Kinesis Firehose into s3 data lake, and use apache spark to spin up EMR cluster for recommendation model.
* create transaction alert when there's unexpected rate of orders coming, using Lambda ot fire off alarm as well as SNS for cellphone text/email.
* analyze near real time server log data using Kinesis Firehose to pump Apache log data into Elastic Search so we can easily query data for dashboards use.



# [Project 2: Youtube Analysis using AWS](https://github.com/christineoeoeo/dataengineering-youtube-analysis-project)

* Landing data on S3, perform Data Processing using Lambda and Glue crawler, put data into cleansed version in parquet format
* Writing ETL job with lambda function that triggers whenever we have changes/new upload for data extraction and writing it to table and bringing it back to S3 bucket



# [Project 3: Analyzing Student Scores using Hadoop and Apache Spark : Project Overview ](https://github.com/christineoeoeo/studentScores)
* The dataset used in this project : Student_scores.csv. This file has student scores by subject during a school year. 
* There are 4 attributes in this data source, the student name, the subject, the class score, which indicates the score the student got from his assignments, and the test score, which indicates the score the student got from his final examination. 

* From Data Loading that involves Loading the CSV into HDFS. The data should be loaded in Parquet format, and the compression used should be GZIP. Follow by choosing a partitioning scheme that would fit this data based on the analytics problems solved in this use case. Read the data from this HDFS store and analyze


