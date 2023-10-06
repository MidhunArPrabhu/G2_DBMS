# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS

## AIM:
To create a student database and execute DDL queries using SQL.


## DDL (Data Definition Language)
<div align="justify">
DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema. It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database. DDL is a set of SQL commands used to create, modify, and delete database structures but not data. These commands are normally not used by a general user, who should be accessing the database via an application.
</div>
 
## List of DDL commands: 
<div align="justify">
CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers).
DROP: This command is used to delete objects from the database.
ALTER: This is used to alter the structure of the database.
TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed.
RENAME: This is used to rename an object existing in the database.
</div>

## Query:
### 1) Create a table student with the following fieds rollno,name,age,address,phoneno.

### SQL QUERY: 
```
create table student (RollNo NUMBER,Name char(20),Age NUMBER,Address char(20),PhoneNo NUMBER);
```
### OUTPUT:

![image](https://github.com/MidhunArPrabhu/G2_DBMS/assets/118054670/a0b4d107-6c3c-4825-8d42-f318a8211af0)


### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
```
 alter table student add Dept char(10);
```
### OUTPUT:

![image](https://github.com/MidhunArPrabhu/G2_DBMS/assets/118054670/11da8edb-9e7c-416a-9ae4-7df5ee7a6569)


### 3) Drop the student table
 
### SQL QUERY: 
```
drop table student;
```
### OUTPUT:

![image](https://github.com/MidhunArPrabhu/G2_DBMS/assets/118054670/be663a40-5c4d-40d2-b9cf-9357deb5e96f)

### 4) Delete the student table using truncate keyword

### SQL QUERY: 
```
TRUNCATE TABLE student;
```
### OUTPUT:

![image](https://github.com/MidhunArPrabhu/G2_DBMS/assets/118054670/8f5695b7-3266-4ddf-af37-ff9ed59aa19a)

### 5) Rename the student table to my_student

### SQL QUERY: 
```
 RENAME student to my_student;
```
### OUTPUT:

![image](https://github.com/MidhunArPrabhu/G2_DBMS/assets/118054670/d4ac907e-9831-449e-bbac-7632220b1a32)

### RESULT:

Hence successfully created a student database and execute DDL queries using SQL.


