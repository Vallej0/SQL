# SQLBackground
It is a beautiful spring day, and it is two weeks since you have been hired as a new data engineer at Pewlett Hackard. Your first major task is a research project on employees of the corporation from the 1980s and 1990s. All that remain of the database of employees from that period are six CSV files.
In this assignment, you will design the tables to hold data in the CSVs, import the CSVs into a SQL database, and answer questions about the data. In other words, you will perform:



Instructions

Data Modeling
I inspected the CSVs and sketched out an ERD of the tables. I used the ERD tool found on the following website: http://www.quickdatabasediagrams.com.

Data Engineering


I used the information I had to create a table schema for each of the six CSV files. I was able to specify data types, primary keys, foreign keys, and other constraints.

I checked to make sure the primary keys were unique otherwise I created a composite key. Which takes to primary keys in order to uniquely identify a row.
I made sure to create tables in the correct order to handle foreign keys.



I imported each CSV file into the corresponding SQL table. I made sure to import the data in the same order that the tables were created and account for the headers when importing to avoid errors.



Data Analysis
Once I had a complete database, I did the following:


List the following details of each employee: employee number, last name, first name, sex, and salary.


List first name, last name, and hire date for employees who were hired in 1986.


List the manager of each department with the following information: department number, department name, the manager's employee number, last name, first name.


List the department of each employee with the following information: employee number, last name, first name, and department name.


List first name, last name, and sex for employees whose first name is "Hercules" and last names begin with "B."


List all employees in the Sales department, including their employee number, last name, first name, and department name.


List all employees in the Sales and Development departments, including their employee number, last name, first name, and department name.


In descending order, list the frequency count of employee last names, i.e., how many employees share each last name.