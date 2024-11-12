## commands

1. `create table employee(fname varchar(30),Mname varchar(20),Lname varchar(30),SSN int,B_date date,addr varchar(60),gender varchar(5),salary float);`

2. `create table department(Dname varchar(30),Dnumber int,MgrSSN int,Mgr_startdate date);`

3. `create table project(pname varchar(20),pnumber int,plocation varchar(150),dnum int);`

4. `create table department(Dname varchar(30),Dnumber int,MgrSSN int,Mgr_startdate date);`

5. `create table Works_on(ESSN int,P_no int,Hours float);`

6. `create table Dept_Location(Dnumber int,D_Location varchar(50));`

7. `create table Dependent(ESSN int,Dep_name varchar(30),Gender varchar(5),B_date date,Reltion varchar(30));`

## query

1. `alter table employee alter column ssn type varchar(9);`

2. ` insert into employee values('john','bishmillah','smith','2345678','12-11-2024','pune','male',57267964.23);`

3. ` alter table department add location varchar(150);`

4. ` insert into department values('IT',101,1101,'6-11-2022','pune');`
