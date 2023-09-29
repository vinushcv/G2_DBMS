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
```sql
create table student(rollno int,name char(20),age int,addr varchar(20),phoneno int);
```

### OUTPUT:

![image](https://github.com/vinushcv/G2_DBMS/assets/113975318/5ab33412-3d99-4e50-b5a5-0fd48be3506e)


### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
```sql
alter table student add department char(30);
```
### OUTPUT:

![image](https://github.com/vinushcv/G2_DBMS/assets/113975318/71ae574b-46d8-4df7-921d-c8d6aa891324)



### 3) Drop the student table
 
### SQL QUERY: 
```sql
drop table student;
```

### OUTPUT:

![image](https://github.com/vinushcv/G2_DBMS/assets/113975318/f4c514c5-eb6f-44c2-85cc-34c6e781bd68)



### 4) Delete the student table using truncate keyword

### SQL QUERY: 
```sql
truncate table student;
```

### OUTPUT:

![image](https://github.com/vinushcv/G2_DBMS/assets/113975318/1757ca54-de36-4d09-b959-429d9397e11c)




### 5) Rename the student table to mystudent

### SQL QUERY: 
```sql
alter table student rename to mystudent;

```

### OUTPUT:

![image](https://github.com/vinushcv/G2_DBMS/assets/113975318/f5d40338-d410-4323-8af7-16bf75aa3cb8)


### RESULT:
To create a student database and execute DDL queries using SQL is executed successfully...


