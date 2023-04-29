# sql-challenge

## Background
It’s been two weeks since you were hired as a new data engineer at Pewlett Hackard (a fictional company). Your first major task is to do a research project about people whom the company employed during the 1980s and 1990s. All that remains of the employee database from that period are six CSV files.

For this project, you’ll design the tables to hold the data from the CSV files, import the CSV files into a SQL database, and then answer questions about the data. That is, you’ll perform data modeling, data engineering, and data analysis, respectively.

## Topics Covered
- Data Modeling
    - Create entity relationship diagrams (ERD) with [QuickDBD](https://www.quickdatabasediagrams.com/)
    ![ERD Diagram](EmployeeSQL/ERD%20screenshot.png)
        - One-to-one, one-to-many, many-to-many
        - Junction Table
    - Data normalization
- Data Engineering
    - PostgreSQL data types
        - `varchar`
    - `PRIMARY KEY`
    - `SERIAL`
    - Foreign keys: `FOREIGN KEY (col) REFERENCES table(col)`
    - `NOT NULL`
- Data Analysis
    - Data Definition Language (DDL)
        - `CREATE`
        - `DROP TABLE IF EXIST table_name;`
    - Data Retrieval Language (DRL)
        - `SELECT`
        - `FROM`
        - Wildcards
        - `WHERE`
        - `ORDER BY DESC`
        - `GROUP BY`
        - `IN`
        - Subquery
        - `BETWEEN`
            - `WHERE hire_date BETWEEN '1986-01-01' AND '1986-12-31'`
        - `JOIN`
        - Aggregating Data