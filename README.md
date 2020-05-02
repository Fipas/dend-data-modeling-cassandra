# Project 2 - Data Modeling with Cassandra

This project was made as part of the Udacity Data Engineering Nanodegree. \
Its goal is to apply concepts of NoSQL data modeling with Apache Cassandra and build an ETL pipeline using Python.

To complete it, it was necessary to define tables to answer particular queries, and write an ETL pipeline that transfers data from .csv files into these tables in Cassandra using Python and CQL.

# Introduction

A startup called Sparkify wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. The analysis team is particularly interested in understanding what songs users are listening to. Currently, there is no easy way to query the data to generate the results, since the data reside in a directory of CSV files on user activity on the app.

They'd like a data engineer to create an Apache Cassandra database which can create queries on song play data to answer the questions. The data engineer role is to create a database for this analysis.

# Files in repository

## Dataset

A event dataset, contained inside `event data` folder was used for this. The directory of CSV files are partitioned by date. Here are examples of filepaths to two files in the dataset:

```
event_data/2018-11-08-events.csv
event_data/2018-11-09-events.csv
```


## Database management files and ETL process

The database schema is contained within the file and the the queries used during the ETL process are in the notebook `Project_1B_ Project_Template`. The ETL process is contained extracts data from the .csv files and load into three tables to awnser three different queries.

# How to run

To be able to run the ETL pipeline, Python 3 and Apache Cassandra are required. \
Just load the notebook on your favorite tool and walk through it.

# License

This project is licensed under the MIT License. For more information about it, please visit https://opensource.org/licenses/MIT