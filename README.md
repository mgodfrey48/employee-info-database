# Storing Employee Data
Using employee information from a hypothetical company contained in six CSV files, I create a table schema specifying data types, primary keys, foreign keys, and other constraints.

![image](https://user-images.githubusercontent.com/87830922/160930689-c9b256b0-2670-4b7c-bee7-2949fac1611a.png)

I then create queries to do the following:
* List the following details of each employee: employee number, last name, first name, sex, and salary.
* List first name, last name, and hire date for employees who were hired in 1986.
* List the manager of each department with the following information: department number, department name, the manager's employee number, last name, first name.
* List the department of each employee with the following information: employee number, last name, first name, and department name.
* List first name, last name, and sex for employees whose first name is "Hercules" and last names begin with "B."
* List all employees in the Sales department, including their employee number, last name, first name, and department name.
* List all employees in the Sales and Development departments, including their employee number, last name, first name, and department name.
* In descending order, list the frequency count of employee last names, i.e., how many employees share each last name.

Here are all files and code to create a database containing this employee information:
* `ERD.png` - A sketch of an entity relationship diagram for employee data 
* `table_schema.sql` - A SQL table schema for employee data
* `queries.sql` - Various SQL queries to pull out specific information
* `EmployeeSQL`/`data` - CSV files containing all employee data

## Instructions:
1. Clone this repository to your computer
2. Create a new database called `Employee_Info`
3. Open a query tool and run the commands from `table_schema.sql`
4. Open another query tool and run the commands from `queries.sql`
* *Note: be sure to import the data in the same order that the tables are created and account for the headers when importing to avoid errors.
