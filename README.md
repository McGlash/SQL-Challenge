# SQL Challenge - Employee Database: A Mystery in Two Parts

![sql.png](sql.png)

## Background

In this challenge, I designed tables to hold data in the six employees CSVs, importedhe CSVs into a SQL database, and answer questions about the data. 

#### Data Modeling

* Developed a an entity-relationship model

![ERD](sql.png)

#### Data Engineering

* Used the information to create a table schema for each of the six CSV files. 

* Imported each CSV file into the corresponding SQL table. 

#### Data Analysis

Conducted the following queries:

1. List the following details of each employee: employee number, last name, first name, sex, and salary.

2. List first name, last name, and hire date for employees who were hired in 1986.

3. List the manager of each department with the following information: department number, department name, the manager's employee number, last name, first name.

4. List the department of each employee with the following information: employee number, last name, first name, and department name.

5. List first name, last name, and sex for employees whose first name is "Hercules" and last names begin with "B."

6. List all employees in the Sales department, including their employee number, last name, first name, and department name.

7. List all employees in the Sales and Development departments, including their employee number, last name, first name, and department name.

8. In descending order, list the frequency count of employee last names, i.e., how many employees share each last name.

### Analysis

1. Imported the SQL database into Pandas. 

2. Created a histogram to visualize the most common salary ranges for employees.

3. Created a bar chart of average salary by title.
