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


![image](https://github.com/dineshgl/G2_DBMS/assets/113975318/173b4769-f935-460b-9323-5562528fae49)


### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
```sql
alter table student add department char(30);
```
### OUTPUT:


![image](https://github.com/dineshgl/G2_DBMS/assets/113975318/d4c05cc8-b206-465d-910c-0a3bc973c02b)



### 3) Drop the student table
 
### SQL QUERY: 
```sql
drop table student;
```



### OUTPUT:


![image](https://github.com/dineshgl/G2_DBMS/assets/113975318/243ce00f-590b-4911-bcb8-b504c37a29bd)



### 4) Delete the student table using truncate keyword

### SQL QUERY: 
```sql
truncate table student;
```

### OUTPUT:


![image](https://github.com/dineshgl/G2_DBMS/assets/113975318/7751dab2-52d2-4f01-a856-648b2bf75f3c)




### 5) Rename the student table to mystudent

### SQL QUERY: 
```sql
alter table student rename to mystudent;
```

### OUTPUT:


![image](https://github.com/dineshgl/G2_DBMS/assets/113975318/62867aa1-0fcf-4d32-b5cd-31ad0020f23d)

### RESULT:
To create a student database and execute DDL queries using SQL is executed successfully...
