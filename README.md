# SQL Work

![sql.png](sql.png)

## Data Analysis/Engineering with SQl

In this project, I modified tables of data from CSVs from Old employee Company information, then imported the CSVs into a SQL database, quiered the data and organized into intelligible insights.

![Screen Shot 2022-01-12 at 4 20 17 AM](https://user-images.githubusercontent.com/33403205/149118166-e1ebbdc9-112c-4237-b40c-4706adaeb47b.png)




#### Data Modeling

Here is where I used the tools to  Inspect the CSVs and sketch out an Entity Relational Diagram (EDRD) and constructed them into tables.
![QuickDBD-Free Diagram](https://user-images.githubusercontent.com/33403205/147866016-62f28f19-00a4-4c4b-a900-bca2be3b83c0.png)
#### Data Engineering

* Use the information you have to create a table schema for each of the six CSV files. Remember to specify data types, primary keys, foreign keys, and other constraints.

  * Created Constrains to keep links between column from being destroyed and configured incorrectly and keeping parent table intact.
![Screen Shot 2022-01-12 at 5 01 29 AM](https://user-images.githubusercontent.com/33403205/149119234-4bf12ced-f9dd-44dd-adc0-898fe2558a41.png)

* Imported each CSV file into the corresponding SQL table. 
* 
#### Data Analysis

After organizing the Data in the CSV, SQL was used to organize the Data details from categories of each Employee,Emplyee number,Last name, First Name , Sex and Salary.



Also List were made with the following details of each manager,and listed Department number,department name,and the Managers employeee number along with Last and First names. Categorized the following..

* Listed the departments of each employee with the following information: employee number, last name, first name, and department name.

* Created list for  first name, last name, and sex for employees whose first name is "Hercules" and last names begin with "B."

* All employees in the Sales department listed, including their employee number, last name, first name, and department name.

* All employees in the Sales and Development departments listed , including their employee number, last name, first name, and department name.

* In descending order, listed the frequency count of employee last names, i.e., how many employees share each last name.

![Screen Shot 2022-01-12 at 4 26 00 AM](https://user-images.githubusercontent.com/33403205/149108132-2b76f7b3-a97d-445f-82eb-4303b9bc2711.png)



   ```sql
   from sqlalchemy import create_engine
   engine = create_engine('postgresql://localhost:5432/<your_db_name>')
   connection = engine.connect()
   ```

*  [SQLAlchemy documentation](https://docs.sqlalchemy.org/en/latest/core/engines.html#postgresql) 




