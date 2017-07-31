# Pandas-Library
-----------------

Overview
---------------
This code was written to test my ability to write a few functions the pandas libray perfoms using basic functions. 

-------------------

### The following tasks were carried out in the code:

#### Task 1: 

- The DataFrame object checks to make sure all the column names in the header(first row of the data) are unique, i.e. no duplicates are allowed.
- If a duplicate header occurs, it raises an expception. 


#### Task 2:

-Performed cleaning/stripping any leading and trailing whitespaces from strings in the data. 

#### Task 3:

- Created instace methods for the minimum, maximum, sum, median, mean and standard deviation of a given column.
- Each method takes a string as an argument for the column name to perfom the operation on.
- If an invalid column is passed, such as one that contains text based strings, (e.g. Product1), it raises an Exception explaining what the problem is. 
- The functions in this task work on numeric and timestamp columns. Datetime objects were used to convert timestamp strings to perfom calcuations. 

#### Task 4:

- Created an instance method that allows the user to add rows to the DataFrame instance. 
- This method takes one argument : A list of rows of data where each row is a list of values. 
-It raises an exception if the rows of data does not contain the correct number of columns. 

#### Task 5:

- Created an instance method that allows the user to add columns to the DataFrame instance.
- This method takes two argument : A list of values and a string for the new column name to add to the header. It raises an exception if the values do not contain the same number of values as the DataFrame has rows.
