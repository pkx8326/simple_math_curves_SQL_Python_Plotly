# simple_math_curves_SQL_Python_Plotly
This project demonstrates the use of mysql.connect package with Python and Plotly to create an SQL database, tables, and visualize data from those tables.

This project demonstrates that you can create a MySQL database and tables with Python and the mysql.connect library. You can also write queries and interact with the database and tables with Python just like you can with MySQL Workbench.

The Jupyter Notebook file shows how you can connect with MySQL database server. It also shows you how to create a database, tables, and interact with those tables to change them, add more columns, or put data in the tables with Python code.

The mysql.connect library will be very useful only when you can quickly visualize data pulled from a relational database with SQL queries. This operation is also demonstrated in this project. After connecting with MySQL database servr and creating and inserting data into tables, the Python code shows you how to prepare the data for plotting by querying the data with MySQL query commands which include joining multiple data tables. Then the code shows how to create a pandas dataframe from a set of data pulled from SQL queries, and  how to visualize the data quickly with Plotly.

The data in this demonstration project is from simple algebraric quations wich include linear, parabola, cubic, and hyperbola equations. The values from these equations were created in the form of x, y relational datapoints with MySQL queries from Python code, then visualized to show their signature curves with Plotly.

The resulting line chart is as the following:
![simple_math_curves](https://user-images.githubusercontent.com/65524471/154792232-2b2369f8-ee7e-4740-936e-e6dd172ed24b.png)
