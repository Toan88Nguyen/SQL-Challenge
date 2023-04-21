# Background

It’s been two weeks since you were hired as a new data engineer at Pewlett Hackard (a fictional company). My first major task is to do a research project about people whom the company employed during the 1980s and 1990s. All that remains of the employee database from that period are six CSV files.

For this project, I'll design the tables to hold the data from the CSV files, import the CSV files into a SQL database, and then answer questions about the data. I will performed the following:

1. Data Modeling
2. Data Engineering
3. Data Analysis


## Data Modeling

Inspected the CSVs and sketched out an ERD of the tables using QuickDBD.

employees_database_erd_quickdbd.png

## Data Engineering

* Created a table schema for each of the six CSV files and be sure to do the following:

1. specified data types, primary keys, foreign keys, and other constraints.

* Imported each CSV file into the corresponding SQL table.


## Data Analysis

After the database was completed, the following was completed:

1. List the following details of each employee: employee number, last name, first name, sex, and salary.

2. List first name, last name, and hire date for employees who were hired in 1986.

3. List the manager of each department with the following information: department number, department name, the manager's employee number, last name, first name.

4. List the department of each employee with the following information: employee number, last name, first name, and department name.

5. List first name, last name, and sex for employees whose first name is "Hercules" and last names begin with "B."

6. List all employees in the Sales department, including their employee number, last name, first name, and department name.

7. List all employees in the Sales and Development departments, including their employee number, last name, first name, and department name.

8. List the frequency count of employee last names (i.e., how many employees share each last name) in descending order.












# Data Analysis
- 1. List the employee number, last name, first name, sex, and salary of each employee.
- 2. List the first name, last name, and hire date for the employees who were hired in 1986.
- 3. List the manager of each department along with their department number, department name, employee number, last name, and first name.
- 4. List the department number for each employee along with that employee’s employee number, last name, first name, and department name.
- 5. List first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B.
- 6. List each employee in the Sales department, including their employee number, last name, and first name.
- 7. List each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.
- 8. List the frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name).
