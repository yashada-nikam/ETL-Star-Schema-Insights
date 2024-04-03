# ETL Star Schema Insights

**Overview**
The ETL Star Schema Insights project is an Extract, Transform, Load (ETL) pipeline implemented using PostgreSQL and SQL. It aims to transform JSON data into a star schema database, enabling insightful analytics on user song preferences and usage patterns. This project provides a streamlined approach to extracting raw data, processing it, and loading it into a structured database schema, facilitating efficient analysis by data analysts and stakeholders.

**Key Features**
1. ETL Pipeline: Implements an end-to-end ETL pipeline for transforming JSON data into a star schema database.
2. Star Schema Database: Utilizes a star schema consisting of a Fact table and Dimension tables for optimized data querying and analysis.
3. SQL Queries: Includes SQL queries for creating tables and inserting data into the database, ensuring data integrity and performance.
Pandas Data Processing: Utilizes the pandas Python library for data processing and filtering, enhancing data quality before insertion into the database.
4. Analytics Insights: Enables analytics on user song preferences and usage patterns, providing valuable insights for decision-making.

**Getting Started**
To get started with the ETL Star Schema Insights project, follow these steps:

1. Clone the repository: git clone <repository_url>
2. Install the required dependencies: pip install -r requirements.txt
3. Set up the PostgreSQL database using the provided SQL scripts in create_tables.py and sql_queries.py.
4. Run the ETL pipeline using the etl.py script to extract, transform, and load data into the database.

**Dependencies**

PostgreSQL

Python 3.x

pandas

numpy

psycopg2

ipython-sql

**Usage**

1. Set up the PostgreSQL database by executing the SQL scripts in the create_tables.py file.
2. Run the ETL pipeline using the etl.py script to process and load data into the database.
3. Perform analytics queries on the database to gain insights into user song preferences and usage patterns.
