Querying in Notebooks - Northwind Database

Overview

This repository contains SQL queries and exercises for querying the Northwind SQLite database. These exercises are designed to help users gain hands-on experience with SQL and data analysis in Jupyter Notebooks.

Learning Objectives

By working through these exercises, you will learn how to:

Use basic SELECT statements to retrieve specific data from a database.

Apply the WHERE clause to filter data based on conditions.

Combine multiple conditions using logical operators such as AND and OR.

Use different logical operators to include or exclude specific values in a table, including the IN operator for multiple values.

Getting Started

Prerequisites

To run the SQL queries in this repository, ensure you have:

SQLite installed on your machine or access to an SQLite-compatible environment.

Jupyter Notebook installed with the ipython-sql extension enabled.

Northwind.db database file downloaded and placed in the working directory.

Installation

Clone this repository:

git clone https://github.com/i-ambale/Basic-SQL-Query.git
cd Basic-SQL-Query

Ensure you have sqlite3 installed:

sqlite3 --version

Install Jupyter Notebook (if not already installed):

pip install notebook

Install the required Jupyter SQL extension:

pip install ipython-sql

Start Jupyter Notebook:
Running Queries

Open the Jupyter Notebook file (.ipynb).

Ensure that Northwind.db is in the working directory.

Use %%sql magic commands in notebook cells to execute SQL queries.

Example query:

%%sql
SELECT * FROM Customers WHERE Country = 'Germany';

Repository Structure

Basic-SQL-Query/
│── notebooks/          # Jupyter notebooks with SQL queries
│── Northwind.db        # SQLite database file
│── README.md           # This README file

Troubleshooting

If sqlite3 is not recognized, ensure SQLite is properly installed.

If no output is displayed in queries, check for typos in table or column names.

Ensure that Northwind.db is in the correct location and accessible.

License

This project is licensed under the MIT License.

Acknowledgments

ExploreAI Academy for providing structured SQL training materials.

The Northwind Database is a commonly used dataset for SQL practice.

Happy querying! 🚀

