# JOINS-PRACTICE

**COMPANY NAME**: CODTECH IT SOLUTIONS

**NAME**: PAUL GIJU THANNICKAL

**INTERN ID** : CT08JWE

**DOMAIN**: SQL

**BATCH DURATION**: JANUARY 20th to FEBRUARY 20th, 2024

**MENTOR NAME**: NIKHILA SANTHOSH

#DESCRIPTION 

A "joins practice task" involves exercises to understand SQL joins by combining data from multiple tables using keys like primary or foreign keys. It covers:

INNER JOIN: Returns matching rows from both tables.
LEFT JOIN: Returns all rows from the left table and matching ones from the right.
RIGHT JOIN: Returns all rows from the right table and matching ones from the left.
FULL OUTER JOIN: Returns rows with matches in either table.
CROSS JOIN: Produces the Cartesian product of both tables.
SELF JOIN: Joins a table with itself.
Database Setup: Use related tables like Customers & Orders, Students & Courses, or Employees & Departments.



Created two tables:

table Employees:
(https://github.com/user-attachments/assets/19828157-d708-40cc-8f36-651f7d69dfc0)

table Departments:
(https://github.com/user-attachments/assets/8857d5ea-caff-4aec-846d-26d8ea94caba)





Task 1: Joins Practice

Objective: To demonstrate proficiency in using different types of SQL joins (INNER, LEFT, RIGHT, and FULL) to combine data from multiple tables.

Purpose: Joins are essential for integrating data from multiple tables in a relational database. Mastering them is crucial for meaningful data analysis.

Deliverable:

Queries for INNER, LEFT, RIGHT, and FULL joins
Corresponding output datasets
Outputs:

INNER JOIN: Retrieves employees along with their respective departments by linking records from both tables using a shared key.
(https://github.com/user-attachments/assets/5e07adbf-9ab3-4cf9-b02f-719a5106e922)

LEFT JOIN: Returns all employees, including those without an assigned department, filling unmatched department data with NULL values.
(https://github.com/user-attachments/assets/3b1194f7-8df1-4db6-8af1-7ed08fd8a51c)

RIGHT JOIN: Displays all departments, ensuring those without employees are included, with missing employee details represented as NULLs.
(https://github.com/user-attachments/assets/83679c5f-f032-4372-a620-de27faa6875e)

FULL JOIN: Combines both LEFT and RIGHT JOINs, presenting all employees and departments while inserting NULLs where no direct match exists.
(https://github.com/user-attachments/assets/3ca716de-ed83-4ee9-8f50-b0da9863eb13)






