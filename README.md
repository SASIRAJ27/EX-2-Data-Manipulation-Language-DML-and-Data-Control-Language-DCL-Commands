# EX 2 Data Manipulation Language (DML) Commands and built in functions in SQL
## AIM:
To create a manager database and execute DML queries using SQL.


## DML(Data Manipulation Language)
<div align="justify">
The SQL commands that deal with the manipulation of data present in the database belong to DML or Data Manipulation Language and this includes most of the SQL statements. It is the component of the SQL statement that controls access to data and to the database. Basically, DCL statements are grouped with DML statements.
</div>

## List of DML commands: 
<div align="justify">
INSERT: It is used to insert data into a table.<br>
UPDATE: It is used to update existing data within a table.<br>
DELETE: It is used to delete records from a database table.<br>
</div>

## Create the table as given below:
```sql
create table manager(enumber number(6),ename char(15),salary number(5),commission number(4),annualsalary number(7),Hiredate date,designation char(10),deptno number(2),reporting char(10));
```
## insert the following values into the table
```sql
insert into manager values(7369,'Dharsan',2500,500,30000,'30-June-81','clerk',10,'John');
insert into manager values(7839,'Subu',3000,400,36000,'1-Jul-82','manager',null,'James');
insert into manager values(7934,'Aadhi',3500,300,42000,'1-May-82','manager',30,NULL);
insert into manager values(7788,'Vikash',4000,0,48000,'12-Aug-82','clerk',50,'Bond');
```

### Q1) Update all the records of manager table by increasing 10% of their salary as bonus.

### QUERY:
![1](https://github.com/SASIRAJ27/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497176/2eb14720-0458-4e8e-88fd-af25cc2deec2)


### OUTPUT:
![2](https://github.com/SASIRAJ27/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497176/4d4b6a3d-5737-4dde-8beb-2d270964ced0)



### Q2) Delete the records from manager table where the salary less than 2750.


### QUERY:
![3](https://github.com/SASIRAJ27/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497176/2fc2438b-5398-40b7-ba0f-e250ac26cd1b)




### OUTPUT:
![4](https://github.com/SASIRAJ27/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497176/db3ef5dd-aadb-4d72-92a1-76c3e0dee0a2)



### Q3) Display each name of the employee as “Name” and annual salary as “Annual Salary” (Note: Salary in emp table is the monthly salary)


### QUERY:
![5](https://github.com/SASIRAJ27/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497176/8d5fac50-525c-47c9-a850-00031f303ad8)



### OUTPUT:
![6](https://github.com/SASIRAJ27/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497176/5217537b-eb2a-4b2e-bcfa-a900ef4a756f)


### Q5)	List the names of Clerks from emp table.

### QUERY:
![7](https://github.com/SASIRAJ27/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497176/9eeaca03-2e3f-4c4e-95ac-18eb0e32961e)

### OUTPUT:
![8](https://github.com/SASIRAJ27/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497176/7d568547-fb05-4681-9e44-7e7feecb84e7)



### Q6)	List the names of employee who are not Managers.

### QUERY:
![9](https://github.com/SASIRAJ27/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497176/984373cc-56c2-4df1-9c45-c98072f5295c)


### OUTPUT:
![10](https://github.com/SASIRAJ27/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497176/a8acd4a7-4a50-4bf3-9d87-fc2b97fbf2d5)


### Q7)	List the names of employees not eligible for commission.

### QUERY:
![11](https://github.com/SASIRAJ27/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497176/f74ef225-8b89-4dcd-be22-06b2ea09de63)


### OUTPUT:
![12](https://github.com/SASIRAJ27/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497176/1f73daa3-2afb-42d9-890a-2a64dad7df7c)


### Q8)	List employees whose name either start or end with ‘s’.
### QUERY:
![13](https://github.com/SASIRAJ27/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497176/39e26acc-71a9-4611-b896-537a61096bf6)

### OUTPUT:
![14](https://github.com/SASIRAJ27/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497176/080a49ab-236d-43da-8762-833e1f61ebeb)



### Q9) Sort emp table in ascending order by hire-date and list ename, job, deptno and hire-date.

### QUERY:
![15](https://github.com/SASIRAJ27/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497176/6e8cd40f-d622-4032-87c2-5543df9a96f6)


### OUTPUT:
![16](https://github.com/SASIRAJ27/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497176/29cd13a8-4fb6-42df-a68a-57896f681e51)


### Q10) List the Details of Employees who have joined before 30 Sept 81.

### QUERY:
![19](https://github.com/SASIRAJ27/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497176/c6067c7c-d3c8-4f8f-b185-33b794b13625)



### OUTPUT:
![20](https://github.com/SASIRAJ27/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497176/d20156cb-ff58-4b17-ad4e-8e54c464d97e)




### Q11)	List ename, deptno and sal after sorting emp table in ascending order by deptno and then descending order by sal.

### QUERY:
![a](https://github.com/SASIRAJ27/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497176/93877142-929b-4e13-87a5-448228a37ce3)

### OUTPUT:
![b](https://github.com/SASIRAJ27/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497176/67786faa-f24c-4ec0-9175-e794413e5365)



### Q12) List the names of employees not belonging to dept no 30,40 & 10

### QUERY:
![c](https://github.com/SASIRAJ27/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497176/809101cd-1e60-479a-943b-90638cf2370d)


### OUTPUT:
![d](https://github.com/SASIRAJ27/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497176/0a399e0b-5482-40ae-9fee-183967a20b7a)


### Q13) Find number of rows in the table EMP

### QUERY:
![e](https://github.com/SASIRAJ27/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497176/0f147537-f472-4e87-ac34-034a85eece38)


### OUTPUT:
![f](https://github.com/SASIRAJ27/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497176/b4f7cdf4-0c37-4cc6-8dd1-a2c575bb0bf9)

### Q14) Find maximum, minimum and average salary in EMP table.
### QUERY:
![g](https://github.com/SASIRAJ27/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497176/a020a1b8-fc99-4217-bc29-53d45b7ab0c9)

### OUTPUT:
![h](https://github.com/SASIRAJ27/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497176/9667228f-cb9a-4f31-ae8c-a8e7162f5cd4)


### Q15) List the jobs and number of employees in each job. The result should be in the descending order of the number of employees.
### QUERY:
![i](https://github.com/SASIRAJ27/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497176/67ef18f8-c786-423c-972d-b0e96b84f915)


### OUTPUT:
![j](https://github.com/SASIRAJ27/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497176/b109d5f9-24cd-4163-ad27-00be69669821)


