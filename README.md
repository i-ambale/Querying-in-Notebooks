Querying in Notebooks - Northwind Database

© ExploreAI Academy

📚 Overview

This project contains an introductory SQL notebook where we explore and query a sample SQLite database for a retail company called Northwind. The Northwind database consists of multiple interrelated tables such as Employees, Orders, Customers, Products, and Suppliers.

The notebook is designed as part of a learning journey at ExploreAI Academy and is ideal for beginners looking to strengthen their SQL querying skills.

🎯 Learning Objectives

By the end of this notebook, you will be able to:

✅ Use the SELECT statement to retrieve specific columns from tables in a SQLite database.
✅ Apply the WHERE clause to filter results based on conditions.
✅ Use the IN operator to match multiple values in a column.
✅ Combine multiple conditions using logical operators such as AND and OR.
✅ Execute practical queries to retrieve meaningful insights from the Northwind database.

💁️ Topics Covered

Selecting columns from a table

Filtering rows with WHERE

Using logical operators like AND and OR

Applying the IN clause to match multiple values

Querying and analyzing business-related data

📂 Files Included

Northwind.db – SQLite database used for this exercise.

Basic_SQL_Queries.ipynb – Jupyter notebook containing all queries and explanations.

README.md – This file.

💡 Prerequisites

Basic knowledge of SQL syntax

Jupyter Notebook or Google Colab environment

SQLite or a SQL client for testing queries

🚀 How to Run

Clone this repository.

Open the notebook Basic_SQL_Queries.ipynb using Jupyter Notebook or upload it to Google Colab.

Ensure the Northwind.db file is accessible in the same directory.

Follow the instructions and run each cell to explore SQL basics.

📈 Exercises

Below are the exercises included in the notebook:

Exercise 1: Customers from Germany

Retrieve the names of all customers located in Germany.

SELECT ContactName FROM Customers WHERE Country = 'Germany';

Exercise 2: Discontinued Products Over 30

Find all products with a unit price greater than 30 that have been discontinued.

SELECT ProductName, Discontinued FROM Products WHERE UnitPrice > 30 AND Discontinued = 1;

Exercise 3: Customers from USA or Canada

Retrieve the contact names and phone numbers of customers from either 'USA' or 'Canada'.

SELECT ContactName, Phone FROM Customers WHERE Country IN ('USA', 'Canada');

Exercise 4: Orders from Specific Customers

Retrieve all orders placed by customers 'VINET', 'QUICK', or 'SUPRD' and shipped via shipper 1 or 2.

SELECT * FROM Orders WHERE CustomerID IN ('VINET', 'QUICK', 'SUPRD') AND ShipVia IN (1, 2);

Challenge Question: Employees in Sales Based in London

Find employees who are either Sales Representatives or Sales Managers and are based in London.

SELECT LastName, FirstName FROM Employees WHERE Title IN ('Sales Representative', 'Sales Manager') AND City = 'London';

💍 Contact

If you have any feedback or suggestions, feel free to reach out or open an issue.

Happy querying! 🚀

