# st2195_assignment__3

### Using Data Expo 2009 data from the Harvard Dataverse
[https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/HG7NV7]
### , construct an SQLite Database called 'airline2.db' with the following tables:
#### 1. ontime(with the data from 2000-2005 - including 2000 and 2005)
#### 2. airports(with the data in airports.csv)
#### 3. carriers(with the data in carriers.csv)
#### 4. planes(with the data in plane-data.csv)

list:
1. A 'README.md' file with a short markdown description of assignment and reference to DataExpo 2009 data, and the Harvard Dataverse.
2. A folder called 'r_sql' with a R code for constructing the database (from csv inputs) and executing the following queries. The latter should be done using both DBI and dplyr notation. 
a. Which airplanes has the lowest associated average departure delay(excluding cancelled and diverted flights?
b. Which cities has the highest number of inbound flights(excluding cancelled flights)?
c. Which companies has the highest number of cancelled flights?
d. Which companies has the highest number of cancelled flights, relative to their number of total flights?

3. A folder called 'python_sql' with a Python version of the code in point2, based on sqlite3. 

4. A simplified solution fo the query in point 2(d) in either R or Python (placed either in the R or Python "*_sql" folder) 

*** R and Python Scripts should save the output of the queries in csv within their respective folders.
