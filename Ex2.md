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
![image](https://github.com/selva258963/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121961701/dc03b5e7-d5c5-4416-bdf0-b222ee6f2786)



### OUTPUT:
![image](https://github.com/selva258963/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121961701/9cff815e-19ff-4683-95cb-3f7903fd33c8)


### Q2) Delete the records from manager table where the salary less than 2750.


### QUERY:
![image](https://github.com/selva258963/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121961701/d2c4deef-6a53-4941-85a0-da30456ccc8f)


### OUTPUT:
![image](https://github.com/selva258963/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121961701/3e6e6301-0cd8-49f1-939d-e6c0629f6102)


### Q3) Display each name of the employee as “Name” and annual salary as “Annual Salary” (Note: Salary in emp table is the monthly salary)


### QUERY:

![image](https://github.com/selva258963/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121961701/74d634cc-3815-40bb-8029-0e07506bff7e)


### OUTPUT:
![image](https://github.com/selva258963/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121961701/eea50424-b56a-4334-af5b-74facdeddb35)


### Q5)	List the names of Clerks from emp table.


### QUERY:
![image](https://github.com/selva258963/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121961701/e9c06a85-f22f-467c-9997-e7c10c93d826)


### OUTPUT:
![image](https://github.com/selva258963/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121961701/de19e7b4-807d-47ff-b796-21e883bc49f9)



### Q6)	List the names of employee who are not Managers.


### QUERY:
![image](https://github.com/selva258963/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121961701/f704d0bf-ee9c-43fd-b4cf-9bf4e86ab1d2)


### OUTPUT:
![image](https://github.com/selva258963/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121961701/bd028d8e-35b0-4f17-8ae0-3e4c04bfd3e0)


### Q7)	List the names of employees not eligible for commission.


### QUERY:
![image](https://github.com/selva258963/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121961701/2c101ed0-3eba-4beb-a77c-1b3dcdc2f49f)


### OUTPUT:
![image](https://github.com/selva258963/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121961701/193cf0bc-5a65-411b-b68a-d55ad1492973)


### Q8)	List employees whose name either start or end with ‘s’.


### QUERY:
![image](https://github.com/selva258963/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121961701/35ece593-3023-4dc7-81c1-866a135ab1ea)


### OUTPUT:
![image](https://github.com/selva258963/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121961701/7be3b77c-28ad-49af-a230-be8da1c713b5)


### Q9) Sort emp table in ascending order by hire-date and list ename, job, deptno and hire-date.


### QUERY:

![image](https://github.com/selva258963/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121961701/d8a473ba-6296-4a44-9c22-fb9c074e0054)

### OUTPUT:
![image](https://github.com/selva258963/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121961701/590cfb4b-86eb-4b74-9b02-4d0611144983)


### Q10) List the Details of Employees who have joined before 30 Sept 81.


### QUERY:
![image](https://github.com/selva258963/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121961701/a467e5b0-ab19-479b-8b15-189f8b5cda78)


### OUTPUT:

![image](https://github.com/selva258963/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121961701/d9dcf856-2e8b-454b-9cac-5894f4a89f08)

### Q11)	List ename, deptno and sal after sorting emp table in ascending order by deptno and then descending order by sal.


### QUERY:
![image](https://github.com/selva258963/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121961701/df69d7ee-de8c-49b3-b98b-a029f0467220)


### OUTPUT:
![image](https://github.com/selva258963/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121961701/39b5b3ff-3806-4045-b583-13c313a7e97f)


### Q12) List the names of employees not belonging to dept no 30,40 & 10


### QUERY:
![image](https://github.com/selva258963/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121961701/29a25e35-61db-46b3-a2e2-25863d837177)


### OUTPUT:
![image](https://github.com/selva258963/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121961701/68c15df7-9b76-4404-820a-8f64f014a472)

### Q13) Find number of rows in the table EMP

### QUERY:
![image](https://github.com/selva258963/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121961701/beeb3254-7c78-4e0a-be27-7b7bc5323637)


### OUTPUT:
![image](https://github.com/selva258963/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121961701/b1f67fcb-8155-432f-aacf-d765da881730)


### Q14) Find maximum, minimum and average salary in EMP table.

### QUERY:
![image](https://github.com/selva258963/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121961701/70d4640d-26b9-456d-af40-f366f1c77e9f)


### OUTPUT:
![image](https://github.com/selva258963/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121961701/8d78aa90-cc71-487e-9296-1b68b4855118)


### Q15) List the jobs and number of employees in each job. The result should be in the descending order of the number of employees.

### QUERY:
![image](https://github.com/selva258963/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121961701/99beace1-e1c8-43a9-93e2-df97520be3a9)


### OUTPUT:
![image](https://github.com/selva258963/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121961701/e01336db-520b-4acb-bd71-7ea5cd060c54)
