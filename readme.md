# Relational Database ETL project
## Installation and execution
In order to run this project it is necessary to have installed python locally and to have the source datasets. 

Execute the notebook NoSQL-DB-ETL-Data-Modeling.ypynb

## Motivation
The goal of this project is to build a data model for a NoSQL Database, Cassandra. 

Data are extracted from a csv and tranformed in order to be ready for being loaded into the database.

## Details
The exercise provided three questions to be answered quering the database. As NoSQL data modeling is based on creating one table for each query,
the first step was translating the questions into queries and then creating one table for each query.
The most important step in creating a table is deciding the PRIMARY KEYS:

first table: PRIMAY KEY was defined considering the WHERE part of the query

second table: PRIMAY KEY was defined considering the WHERE part of the query and adding a CLUSTERING COLUMN to order data

third table: PRIMAY KEY was defined considering that the goal is to provide unique values on user first and last name 


## File Description 
```NoSQL-DB-ETL-Data-Modeling```: notebook to perform initial ETL on the csv files and to create and insert data into the database.

```event_datafile_new.csv```: data produced as output of the ETL, which are used to create the tables of the database

```event_data```: source dataset to be processed

```images```: example image of the event_datafile file

## Acknowledgements
Udacity provided the course material necessary to implement the project
