# ETL-projects-python-postgres

### Data Engineering Projects #1

##### Author : Achmad Adyatma Ardi
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
4. Connect to PostgreSQL database
   - method 1 : using sqlalchemy
   - method 2 : using psycopg2
5. Test - CRUD operations using both methods (sqlalchemy & psycopg2)
6. Load data
   - create schema table
   - load merged data to the postgreSQL database
   - try to show head() and tail() data using Jupyter Notebook from database that has been created

## Results
Jupyter notebook [source code](https://drive.google.com/file/d/1fbzJdpEXbiKjmeCDVWLxYKWcGgYjblyB/view?usp=sharing) 

capture :
1. test CRUD operations - sqlalchemy
   - Create table named 'persons' [see picture](https://drive.google.com/file/d/1QDrsvEkNzaP0QQPODgk3g6HDbV-XpPx6/view?usp=sharing)
   - Create 2 records into 'persons' table [see picture](https://drive.google.com/file/d/1Q47w8oiPZykfxKebYjknFFUaz-DlhAAr/view?usp=sharing)
   - Update existing record where ID = 1 [see picture](https://drive.google.com/file/d/1ekGaK-qxYdQeso7DD52srXAuk7DwelTq/view?usp=sharing)
   - Delete existing record where ID = 1 [see picture](https://drive.google.com/file/d/14Laq5ckmZiY4heZywek9nffIdytGCGJw/view?usp=sharing)

2. test CRUD operations - psycopg2
   - Create table named 'customers' [see picture](https://drive.google.com/file/d/1ppF5gkbNIP5u4m80pl-ei9lqNTSYlRFy/view?usp=sharing)
   - Create 2 records into 'customers' table [see picture](https://drive.google.com/file/d/1VWp8JLxinTd9MZkqWqRYsbqsaurTiAV7/view?usp=sharing)
   - Update existing record where ID = 1 [see picture](https://drive.google.com/file/d/1BEZVHCsYsH2NN0ufRdcpjZCHMPQYxFCB/view?usp=sharing)
   - Delete existing record where ID = 2 [see picture](https://drive.google.com/file/d/13pCw1wgkBOzBKrvEY1MOqvnkRmTZlfYe/view?usp=sharing)

3. Show loaded data - pgadmin [see picture](https://drive.google.com/file/d/1bqlU8Z2VxuYw0ohTjkL6_fZDgs2GGdKY/view?usp=sharing)
