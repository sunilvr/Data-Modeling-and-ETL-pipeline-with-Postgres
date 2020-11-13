# Data-Modeling-and-ETL-pipeline-with-Postgres

Introduction

A music company might want to analyze the data they've been collecting on songs and user activity on their new music streaming app. The analytics team will be particularly interested in understanding what songs users are listening to. This data which resides in a directory of JSON logs on user activity on the app along with JSON metadata on songs will need a way to be queried upon. This data engineering project creates a Postgres database with appropriate design schema and tables to optimize queries on song play analysis.

Project Description
In this project, the data modeling was done in Postgres to build an ETL pipeline using Python. The project schema is based on star design with fact and dimension tables for a particular analytic focus. The ETL pipeline transfers data from files in two local directories into Postgres tables using Python and SQL.


## How to run the project?

Step 1 - Run the below command in the terminal to create and connect to postgres database followed by creation of tables
>python3 create_tables.py

Step 2 - Run the etl.py file to activate/run the etl pipeline  
>python3 etl.py

## Files in the repository

1) data - folder with logs and songs data files

2) create_tables.py - this is the driver python file which should be run to create the database and all the necessary tables 

3) etl.ipynb - jupyter notebook which explains step by step execution of the etl pipleine

4) etl.py - the etl pipeline code which loads and processes the logs and songs data files to store in appropriate database tables

5) sql_queries.py - python file that contains all the sql queries

6) test.ipynb - displays the first few rows of each table to let the users check their database.
