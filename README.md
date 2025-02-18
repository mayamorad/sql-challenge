# sql-challenge

_Project Overview_

As a newly hired Data Engineer at Pewlett Hackard (a fictional company), my first major task is to analyze employee records from the 1980s and 1990s. The only remaining data exists in six CSV fil es, which need to be imported into a SQL database for further analysis. This project involves data modeling, data engineering, and data analysis. 

---------
**Part 1: Data Modeling**
To properly structure the database, I analyzed the CSV files and designed an Entity Relationship Diagram (ERD) that visualizes how the tables are connected.
- ERD file: Entity Realtionship Diagram.png

Key considerations:
- Identified primary keys and foreign keys to establish relationships
- Ensured data integrity with appropriate constraints
- Normalized the data to remove redundancy

**Part 2: Data Engineering:** 
I created a PostgreSQL database to store the data and defined the required tables based on the ERD.
- Schema file: schema.sql

Steps:
- Defined the six tables with appropriate data types and constraints
- Established foreign key relationships for department and employee connections
- Ensured proper ordering of table creation to avoid reference errors
- Imported the data using COPY statements or INSERT INTO queries

**Part 3: Data Analysis:**
Once the database was populated, I ran SQL queries to analyze the employee records.
- Queries file: queries.sql

Key Queries:
- List all employees with their employee number, name, sex, and salary
- Find employees hired in 1986
- Identify department managers with their department details
- Retrieve employees by department (Sales, Development, etc.)
- Find employees named Hercules with last names starting with B
- Count how many employees share the same last name

----------
Technologies Used: 
QuickDBD for ERD design
pgAdming 4 for database creation and querying
QuickDBD for ERD design

----------
**Summary:**
- Modeled the database structure using ERD.
- Engineered tables in PostgreSQL with appropriate constraints.
- Imported historical employee data from CSV files.
- Analyzed data using complex SQL queries.
