# SQL Practice Notebooks
 
A collection of hands-on SQL notebooks completed while practicing and strengthening my SQL and data analysis skills.
 
These notebooks document practical work across SQL fundamentals, data querying and filtering, numeric functions, aggregations, multi-table queries, and window functions.
 
## Skills Practiced
 
- Writing and executing SQL queries in Jupyter Notebook
- Retrieving and filtering data with `SELECT` and `WHERE`
- Using logical and comparison operators
- Writing readable SQL with aliases and comments
- Applying numeric functions and data transformations
- Creating aggregations and summary statistics
- Working with data across multiple tables
- Using SQL window functions
- Performing ranking and Top-N analysis
- Analyzing changes between consecutive records
 
## Tools & Technologies
 
- SQL
- MySQL
- SQLite
- Jupyter Notebook
- SQLAlchemy
- PyMySQL
- ipython-sql
- PrettyTable
 
## Practice Notebooks
 
| # | Notebook | Description |
|---|---|---|
| 01 | `Aggregation using window functions [Notebook].ipynb` | Uses window functions for aggregation and partitioning to perform analytical calculations across related groups of records. |
| 02 | `Aliasing and commenting in SQL.ipynb` | Improves SQL readability using column and table aliases, single-line and multi-line comments, and notebook documentation. |
| 03 | `Basic SQL queries in a notebook 1 [Exercise].ipynb` | Practices fundamental SQL queries on the Chinook database using `SELECT`, `WHERE`, `LIMIT`, and `AND`. |
| 04 | `chinook_serverless_sql_arch.ipynb` | Sets up SQL inside Jupyter Notebook, connects to the Chinook SQLite database, explores its tables, and executes SQL queries. |
| 05 | `client_server_architicture'notebook'3invisible-pass.ipynb` | Demonstrates a safer MySQL connection setup by entering the database password without displaying it and preparing it for the connection string. |
| 06 | `Create a summary statistic report in SQL [Notebook].ipynb` | Creates summary statistics using SQL numeric functions, aggregations, and `GROUP BY` to examine data at different levels of granularity. |
| 07 | `Filtering and analysing summary statistic report [Notebook].ipynb` | Extends summary statistics analysis by filtering aggregated results using `WHERE` and `HAVING`. |
| 08 | `Initial data analysis with numeric functions [Notebook].ipynb` | Performs initial SQL analysis to explore the range and numerical characteristics of the dataset. |
| 09 | `Logical and comparison operators ii.ipynb` | Uses `IS NULL`, `IS NOT NULL`, `IN`, and `NOT IN` while examining GDP and access to drinking water and sanitation services in Sub-Saharan Africa. |
| 10 | `Querying in notebooks[Exercise].ipynb` | Queries the Northwind database using `SELECT`, `WHERE`, `AND`, `OR`, and `IN` to retrieve and filter records. |
| 11 | `Reading data across multiple tables.ipynb` | Practices retrieving data from individual columns, multiple columns, and multiple related tables in the Chinook database. |
| 12 | `select&select_where_excercise.ipynb` | Practices retrieving and filtering data from the United Nations database using `SELECT` and `WHERE`. |
| 13 | `SQL numeric functions and aggregations [Exercise].ipynb` | Applies `AVG`, `SUM`, `MAX`, `MIN`, and `COUNT`, together with `GROUP BY`, ordering, and limiting results in the Northwind database. |
| 14 | `SQL window functions [Exercise].ipynb` | Practices SQL window functions and their use in analytical queries. |
| 15 | `Top-N analysis using ranking window functions [Notebook].ipynb` | Performs Top-N analysis using `ROW_NUMBER()` and `RANK()` and compares ranking behavior within partitions. |
| 16 | `Transform columns using numeric functions[Notebook].ipynb` | Transforms numerical data using SQL functions such as `ROUND()`, `LOG()`, and `SQRT()`. |
| 17 | `Using logical and comparison operators.ipynb` | Filters data using logical and comparison operators, including `WHERE`, `OR`, `IN`, `BETWEEN`, and comparison conditions. |
| 18 | `Using value based window functions [Notebook].ipynb` | Uses `LAG()` to access previous-row values and analyze changes between consecutive periods. |
 
## Databases Used
 
### Chinook
A sample digital media database used for practicing SQL fundamentals and querying data across multiple related tables.
 
### Northwind
A sample retail database used for practicing querying, filtering, numeric functions, and aggregations.
 
### United Nations Access to Basic Services
Used for analytical SQL practice involving population, GDP, drinking water, sanitation services, aggregations, and window functions.
 
## Topics Covered
 
`SELECT` • `WHERE` • `DISTINCT` • `LIMIT` • `AND` • `OR` • `IN` • `NOT IN` • `BETWEEN` • `IS NULL` • `IS NOT NULL` • `GROUP BY` • `HAVING` • `ORDER BY` • `COUNT()` • `SUM()` • `AVG()` • `MIN()` • `MAX()` • `ROUND()` • `LOG()` • `SQRT()` • Window Functions • `PARTITION BY` • `ROW_NUMBER()` • `RANK()` • `LAG()`
 
## Repository Notes
 
This repository contains a selection of SQL practice notebooks completed as part of my hands-on data analysis training.
 
It is not intended to represent every exercise or notebook from the training material. Instead, it documents the practical SQL work I completed and preserved.
 
Some notebooks use local MySQL or SQLite databases and may require the corresponding database files and connection setup to run successfully.
 
---
 
**Christina Tawfiq**
*SQL Practice & Data Analysis*
