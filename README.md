# DataCleaning-SQL
In this project I cleaned a synthetically generated employee data set generated by ChatGpt.
-The employee data set contained 100 employee records simulating real world data quality issues 
-including duplicated values in rows suppossing to contain unique values
-incosistent formatting like the date coloumn having different formats
-and missing values where some rows had empty and null values, while numeric coloumns(Salaries) contained 0s

In order to clean and fix these issues:
-I used CTEs with Window functions Like ROW_Number() in order to fix duplicates
-Used SQL Server string functions like Trim(),Replace(),Lower(),Upper(),Substring() to standardize text fields
-Used Select And Update statements to the dataset

After Cleaning the data I finally exported it into a CSV file(Clean_employees) where it is ready for Exploratory Data Analysis and visualizations to gain insights


