Pewlett Hackard Employee Database - SQL Challenge
Project Description
The purpose of this project is to perform data modeling, data engineering, and data analysis on Pewlett Hackard's employee database from the 1980s and 1990s. The employee data is stored across six CSV files, and our task is to import this data into a SQL database.

Instructions
1. Data Modeling:
Inspect the structure of the CSV files and create an Entity Relationship Diagram (ERD) that illustrates the relationships between these tables.

2. Data Engineering:
Create a table schema for each of the six CSV files. The schema should include:

Data types for each column
Primary keys and foreign keys
Other constraints as necessary
Ensure that the tables are created in the correct order to handle foreign key constraints.

Import each CSV file into its corresponding SQL table.

3. Data Analysis:
Perform various data analysis tasks such as:

Listing details of each employee like employee number, last name, first name, sex, and salary.
Listing employees hired in a specific year.
Listing the manager of each department with their details.
Listing the department number for each employee with their details.
Listing all employees with a certain first name and last name starting with a certain letter.
Listing all employees in a specific department.
Listing the frequency counts of employee last names in descending order.

Getting Started
Clone this repository to your local machine. The repository should include a directory called EmployeeSQL which contains all the necessary SQL scripts and CSV files.

Prerequisites
Ensure you have PostgreSQL installed on your machine. If not, you can download it here.

Installation
Open PostgreSQL and create a new database.
Run the SQL scripts provided in the EmployeeSQL directory to create the tables and import the data. Make sure you run the table creation scripts before the data import scripts to avoid foreign key conflicts.
Now that the database is set up, you can start querying the data.
Built With
PostgreSQL
QuickDBD for the ERD
Acknowledgements
This project has been assigned as part of the Data Engineering module. It is intended to provide practical exposure to designing and working with databases.
