# Data Modeling with PostSQL
In this project I create a database and implement an star schema with the following tables:
- users: dimension table
- songs: dimension table
- artists: dimension table
- time: dimension table
- songplays: fact table

The files fund in the repository are the following:
- create_tables.py: a python file with functions defined to create the database, the tables and other sql functionalities.
- etl.ipynb: jupyter notebook used to develop the pipeline
- etl.py: the actual pipeline script
- sql_queries.py: contains python variables with sql queries to create and update the database.
- test.ipynb: jupyter notebook with some test to assure the quality of the proccess

This project has been developed as part of the Udacity Data Engineer Nanodegree.