# Introduction

A music streaming startup, Sparkify, has grown their user base and song database even more and want to move their data warehouse to a data lake. Their data resides in S3, in a directory of JSON logs on user activity on the app, as well as a directory with JSON metadata on the songs in their app.

As a data engineer, I have assinged to build an ETL pipeline that extracts their data from S3, processes them using Spark, and loads the data back into S3 as a set of dimensional tables. This will allow their analytics team to continue finding insights in what songs their users are listening to.

 I was  able to test the database and ETL pipeline by running queries given to you by the analytics team from Sparkify and compare your results with their expected results.

# Project Description
In this project, I was able to  build an ETL pipeline for a data lake hosted on S3. I  completed it by loaded the  data from S3, and processed it  into analytics tables using Spark,then loaded them back into S3. I have used AWS to  deploy Spark process.

# Project Datasets
Ther are two datasets reside in S3:

- Song data: s3://udacity-dend/song_data
- Log data: s3://udacity-dend/log_data


# Database Design
Star schema is created, that include the following tables :
- `songplays` is a fact table.
- `songs`, `artists`, `users` and `time` are dimension tables.

# ETL Pipeline
ETL pipeline that extracts the data from S3, processes them using Spark, and loads the data back into S3 as a set of five tables bye execute the  etl.py file and configure the dl.cfg by adding the Access Key and secret access key .

