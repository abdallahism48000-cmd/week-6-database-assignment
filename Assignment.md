Week 6 Assignment: SQL Joins and Relationships
Description

Week 6 Assignment: SQL Joins and Relationships
Assignment Overview

This week's assignment focuses on SQL Joins and table relationships. You will practise combining data from multiple related tables using INNER JOIN, LEFT JOIN, and RIGHT JOIN.

Learning Objectives

By the end of this assignment, you should be able to:

Understand and implement INNER JOIN, LEFT JOIN, and RIGHT JOIN in SQL.

Retrieve data from multiple related tables using SQL queries.

Understand relationships between tables such as employees, offices, products, orders, and customers.

Apply SQL joins to solve real-world database problems.

What You'll Need

A computer with internet access.

Visual Studio Code or another code editor.

MySQL Workbench or another SQL database environment.

The MySQL Classic Models database.



Submission Instructions

Write your SQL queries for Questions 1, 2, and 3 in the answer.sql file.

Important: All three SQL queries must be submitted in the answer.sql file. Do not submit screenshots or separate SQL files.

Assessment Criteria

Correct implementation of INNER JOIN, LEFT JOIN, and RIGHT JOIN.

Correct use of table relationships and joining columns.

Accurate retrieval of the requested columns.

Proper SQL syntax, formatting, and organization.

Successful submission through GitHub.



Assignment Questions
Question 1: INNER JOIN – Employees and Offices

Write an SQL query to retrieve the following information for all employees:

firstName

lastName

email

officeCode

Use an INNER JOIN to combine the employees table with the offices table using the officeCode column.

Question 2: LEFT JOIN – Products and Product Lines

Write an SQL query to retrieve the following information:

productName

productVendor

productLine

Use a LEFT JOIN to combine the products table with the productlines table using the productLine column.

Question 3: RIGHT JOIN – Customers and Orders

Write an SQL query to retrieve the following information for the first 10 orders:

orderDate

shippedDate

status

customerNumber

Use a RIGHT JOIN to combine the customers table with the orders table using the customerNumber column.