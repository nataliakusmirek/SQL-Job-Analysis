# SQL Job Analysis

## Introduction
I used the provided dataset on jobs around the world to answer the following questions:
1. What are the top paying jobs in the specified role?
2. What skills are required for these top paying jobs?
3. What are the most 'in-demand' skills for the specified role?
4. What are the top skills based on salary for the specified role?
5. What are the most optimal skills to learn? 
    Note: 'optimal' is classified as being a high demand AND high paying skill.

## Tools Used
* **SQL**: to query the database
* **PostgreSQL**: personal DMS preference
* **Visual Studio Code**: for coding!
* **Git**: for sharing SQL scripts and analysis

## The Analysis
**1. Top Paying Analyst Jobs**

Queries based on average yearly salary and specified analyst job.

[Q1](assets/Q1.png)
*Generated by ChatGPT based on results*

**2. Skills Required for Top Paying Analyst Jobs**

Queries based on average yearly salary and specified analyst job.

[Q2](assets/Q2.png)
*Generated by ChatGPT based on results*

**3. Most In-Demand Skills for Top Paying Analyst Jobs**

Queries based on most frequent skills and in top analyst jobs.

[Q3](assets/Q3.png)
*Generated by ChatGPT based on results*

**4. Top Skills Based on Salary**

Queries based on average yearly salary and specified analyst job in conjunction to most frequent skills.

[Q4](assets/Q4.png)
*Generated by ChatGPT based on results*

**5. Most Optimal Skills to Learn for Analyst Jobs**

Queries based on specified analyst job in conjunction to most frequent skills.

[Q5](assets/Q5.png)
*Generated by ChatGPT based on results*


## What I Learned
- **SQL Syntax**: Learned the fundamental syntax of SQL, including `SELECT`, `INSERT`, `UPDATE`, `DELETE`, and `WHERE` clauses.
- **Data Types**: Gained knowledge about different data types such as `INTEGER`, `VARCHAR`, `DATE`, and `BOOLEAN`.
- **Query Writing**: Practiced writing simple to complex queries to fetch data based on specific criteria.
- **Joins**: Understood how to use different types of joins (`INNER`, `LEFT`, `RIGHT`, `FULL`) to combine data from multiple tables.
- **Database Creation**: Gained experience in creating databases and tables within PostgreSQL.
- **Data Importing**: Understood the process of importing data from CSV files into PostgreSQL tables using the `COPY` command.
- **psql Tool**: Familiarized with the `psql` command-line tool for executing SQL queries and managing the database.
- **Aggregation**: Utilized aggregate functions (`COUNT`, `SUM`, `AVG`, `MAX`, `MIN`) to summarize data and extract meaningful insights.
- **Grouping Data**: Used the `GROUP BY` clause to organize data into groups based on specific columns, enabling more detailed analysis.
- **Filtering Data**: Applied the `HAVING` clause to filter groups based on aggregate values, refining the analysis further.
- **Subqueries and CTEs**: Leveraged subqueries and Common Table Expressions (CTEs) for more complex data manipulation and to simplify large queries.

