# Data-Modeling-and-ETL-pipeline-with-Postgres

Introduction
An music company might want to analyze the data they've been collecting on songs and user activity on their new music streaming app. The analytics team will be particularly interested in understanding what songs users are listening to. This data which resides in a directory of JSON logs on user activity on the app along with JSON metadata on songs will need a way to be queried upon. This data engineering project creates a Postgres database with appropriate design schema and tables to optimize queries on song play analysis.

Project Description
In this project, the data modeling was done in Postgres to build an ETL pipeline using Python. The project schema is based on star design with fact and dimension tables for a particular analytic focus. The ETL pipeline transfers data from files in two local directories into Postgres tables using Python and SQL.
