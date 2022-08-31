# ETL-projects-python-postgres

#### Author : Achmad Adyatma Ardi
##### Email : achmad541997@gmail.com
##### IG : [@adyatmaardi](https://www.instagram.com/adyatmaardi/?hl=id)

## Prerequisites
1. Postgres database already installed locally
2. Install necessary Python-module

   - [pandas](https://pypi.org/project/pandas/) module - it makes you to use high-performance data structures and data analysis tools.
   
           pip install pandas
   
   
   - [datetime](https://pypi.org/project/DateTime/) module - it supplies classes for manipulating dates and times. 

           pip install DateTime

   - [sqlalchemy](https://pypi.org/project/SQLAlchemy/) module - it facilitates the communication between Python scripts or programs to the databases. It is used as an Object Relational Mapper (ORM) tool.

           pip install SQLAlchemy


   - [psycopg2](https://pypi.org/project/psycopg2/) module - is a PostgreSQL database driver, its mainly used to perform operations on PostgreSQL using python and it designed for multi-threaded applications.

           pip install psycopg2


## Objectives
1. To do ETL (Extract, Transform, Load) through Python-PostgreSQL
2. Exract CSVs files from your computer path directory to Jupyter Notebook
3. Transform CSV files
   - drop columns
   - rename the spesific column
   - convert date column (as object type) to datetime object
   - merge datas
4. Connecto to PostgreSQL database
   - method 1 : using sqlalchemy
   - method 2 : using psycopg2
5. Test - CRUD operations using both methods (sqlalchemy & psycopg2)
6. Load data
   - create schema table
   - load to the postgreSQL database
   - try query the data from database that has been created

## Results
1. Jupyter notebook [source code](https://drive.google.com/file/d/1fbzJdpEXbiKjmeCDVWLxYKWcGgYjblyB/view?usp=sharing) 
