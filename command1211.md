## commands

1. `create table employee(fname varchar(30),Mname varchar(20),Lname varchar(30),SSN int,B_date date,addr varchar(60),gender varchar(5),salary float);`

2. `create table department(Dname varchar(30),Dnumber int,MgrSSN int,Mgr_startdate date);`

3. `create table project(pname varchar(20),pnumber int,plocation varchar(150),dnum int);`

4. `create table Works_on(ESSN int,P_no int,Hours float);`

5. `create table Dept_Location(Dnumber int,D_Location varchar(50));`

6. `create table Dependent(ESSN int,Dep_name varchar(30),Gender varchar(5),B_date date,Reltion varchar(30));`

## query

1. `alter table employee alter column ssn type varchar(9);`

2. ` insert into employee values('john','bishmillah','smith','2345678','12-11-2024','pune','male',57267964.23);`

3. ` alter table department add location varchar(150);`

4. ` insert into department values('IT',101,1101,'6-11-2022','pune');`

## insert

`insert department values('Research', 5, 333445555, '1988-05-22'),('Administration', 4, 987654321, '1995-01-01'),('Headquarters', 1, 888665555, '1981-06-09'),('Accounting', 2, 453453453, '1992-04-01'),('Marketing', 6, 765432123, '1998-11-10'),('Production', 7, 987987987, '1999-10-01');`

`insert into project values('ProductX', 1, 'Bellaire, Texas', 5),('ProductY', 2, 'Sugarland, Texas', 5),('ProductZ', 3, 'Houston, Texas', 5),('Computerization', 10, 'Stafford, Texas', 4),('Reorganization', 20, 'Houston, Texas', 1),('Newbenefits', 30, 'Stafford, Texas', 4);`

`insert into Works_on values(123456789, 1, 32.5),(123456789, 2, 7.5),(333445555, 1, 10),(333445555, 2, 10),(333445555, 3, 10),(453453453, 10, 10),(453453453, 20, 10),(453453453, 30, 10),(666884444, 30, 30),(765432123, 30, 20),(888665555, 20, 10),(987654321, 10, 40),(987987987, 10, 20),(987987987, 20, 20);`

`insert into Dept_Location values(1, 'Houston, Texas'),(4, 'Stafford, Texas'),(5, 'Bellaire, Texas'),(5, 'Sugarland, Texas'),(5, 'Houston, Texas'),(7, 'Houston, Texas');`

`insert into Dependent values(123456789, 'Alice', 'F', '1988-12-30', 'Daughter'),(123456789, 'Bob', 'M', '1986-01-29', 'Son'),(333445555, 'Carol', 'F', '1987-08-09', 'Daughter'),(333445555, 'David', 'M', '1983-10-25', 'Son'),(453453453, 'Erin', 'F', '1989-01-12', 'Daughter'),(765432123, 'Frank', 'M', '1985-04-16', 'Son');`
