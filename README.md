# SCD2_Implementation

![alt text](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRz_8XWkAfUkg4zF5KmwBuxyIzkoILBhMYtqA&usqp=CAU)


# Introduction:
                                                            
                                                            
A company X wants to keep its employee data up to date in their central database.  
Since, over the time, many employees prefer to change their base location, it is essential to update the employee information in the company's central database. 
 


# Problem Statement:

The field 'Location' is a Slowly changing Dimension (  a dimension whose attribute or attributes for a record (row) change slowly over time). We will be using SCD-2 type implementation to keep a full history of dimension data in the table. The Type 2 Dimension mapping filters source rows based on user-defined comparisons and inserts both new and changed dimensions into the target. Changes are tracked in the target table by looking up the primary key and creating a version number for each dimension in the table called a surrogate key.  
 


# ETL Process:

We are sourcing the data from MS SQL Server, transforming it using Informatica and loading it to Oracle server.


# Source table in MySQL server
![MySql source](https://user-images.githubusercontent.com/100331434/155978959-860d7752-365f-47d5-ae6b-0a74ec260d2b.png)


# Target table in Oracle
<img width="661" alt="Oracle_Result" src="https://user-images.githubusercontent.com/100331434/155978124-61e08f92-a50f-485a-918c-7f49b96134b4.png">

