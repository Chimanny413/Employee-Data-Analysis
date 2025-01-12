The SQL script is creating a database structure for managing employee and department-related information.

## Pewlett Hackard SQL 

### Overview
This project involved designing a SQL database to analyze historical employee data from Pewlett Hackard during the 1980s and 1990s. Using relational database design principles, I built a normalized schema, imported data from CSV files, and ran complex SQL queries to derive insights.

### Tools and Skills
- SQL (PostgreSQL)
- Data Modeling (dbdiagram.io for ERD)
- Data Engineering (ETL processes) 
- Data Analysis (SQL queries)

### Key Features
- **Entity Relationship Diagram (ERD)**
- **Sample Query:**  
  *List employees hired in 1986:*
  ```sql
  SELECT first_name, last_name, hire_date
  FROM employees
  WHERE EXTRACT(YEAR FROM hire_date) = 1986;

## Queries
The queries are examples of how you can extract useful information by combining, filtering, and grouping data from the tables. Each query has a specific goal, such as finding employees in a department, managers, or specific names, and uses SQL functions and clauses to achieve it.
