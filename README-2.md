Project Template

Project Template include three files:

1. etl.py reads data from S3, processes that data using Spark and writes them back to S3

2. dl.cfg contains AWS Credentials

3. README.md provides discussion on your process and decisions

ETL Pipeline

Load the credentials from dl.cfg
Load the Data which are in JSON Files(Song Data and Log Data)
After loading the JSON Files from S3 4.Use Spark process this JSON files and then generate a set of Fact and Dimension Tables
Load back these dimensional process to S3
Final Instructions

Write correct keys in dl.cfg
Open Terminal write the command "python etl.py"
Should take about 2-4 mins in total