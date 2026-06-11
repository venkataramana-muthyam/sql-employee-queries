# sql-employee-queries
SQL Employee Queries Assignment using WHERE Clause Conditions
# SQL Employee Queries Assignment

## Description
This assignment demonstrates the use of SQL WHERE clause conditions to retrieve specific records from the employees table.

## Tasks Completed

### Task 1
Retrieve all employees whose salary is greater than $50,000.

SELECT DISTINCT *
FROM employees
WHERE salary > 50000;


### Task 2
Find all employees who are between 25 and 40 years old (inclusive).

SELECT DISTINCT *
FROM employees
WHERE age BETWEEN 25 AND 40;

### Task 3
Select all employees who work in the Marketing department and have a salary less than $60,000.

SELECT DISTINCT *
FROM employees
WHERE depatment = 'Marketing'
AND salary < 60000;

## Concepts Used

- WHERE Clause
- Comparison Operators
- BETWEEN Operator
- Logical Operators (AND)
- DISTINCT Keyword


## Author

Venkata Ramana
