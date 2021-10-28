#  sql-challenge
#  Employee Database: A Mystery in Two Parts

## Overview

The first major task is a research project on employees of the corporation from the 1980s and 1990s. All that remain of the database of employees from that period are six CSV files.
I designed tables to hold data in the CSVs, import the CSVs into a SQL database, and performed Data Engineering/Modeling and Data Analysis

### Data Modeling
Inspected the CSVs and sketched out an ERD of the tables using http://www.quickdatabasediagrams.com.

### Data Engineering

Created a table schema for each of the six CSV files and imported each CSV file into the corresponding SQL table. 

### Data Analysis

Queried the tables to list employee details and performed tasks such as frequency counts and arranged outputs in ascending/descending orders. 

## Bonus (Optional)

*  Imported the SQL database into Pandas (instead of reading the CSVs directly in Pandas) using the following: 

    from sqlalchemy import create_engine
    engine = create_engine('postgresql://localhost:5432/<your_db_name>')
    connection = engine.connect()

*  Created a histogram and a bar chart.
