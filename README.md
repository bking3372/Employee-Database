# Building and Querying an Employee Database

Step 1:  Build an employee database from six CSV files

* An ERD diagram was created to visualize the database design and outline the schema specifying data types, primary and foreign keys, and any constraints
* Using the ERD schema and the CSV files, the employee database was created in pgAdmin

![ERD Image](https://github.com/bking3372/Employee-Database/blob/master/EmployeeSQL/images/ERD%20Diagram.PNG)

Step 2:  Perform a series of SQL queries on the data

* Using pgAdmin, a variety of queries were performed on the data such as:
    -  Listing the employees (first name, last name, hire date) hired in 1986
    -  Listing the employees (first name, last name, gender) with the first name 'Hercules' and last name starting with 'B'
    -  Listing the frequency count of employee last names in descending order


Step 3:  Import the SQL database into Pandas and create data visualizations

*  These data visualizations included:
    -  A histogram of salary ranges:  salaries range from $40,000 to $110,000 with the majority between $40,000 and $50,000
    
    ![Histogram](https://github.com/bking3372/Employee-Database/blob/master/EmployeeSQL/images/Salary%20Histogram.PNG)
    
    -  A bar chart of the average salary by title:  average salaries range from just under $50,000 to almost $60,000 with the highest average salaries for Staff and Senior Staff employees

    ![Bar](https://github.com/bking3372/Employee-Database/blob/master/EmployeeSQL/images/Avg%20Salary%20by%20Title.PNG)
