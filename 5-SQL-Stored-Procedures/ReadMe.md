# Stored Procedures

Stored procedures are a collection of Transact-SQL statements stored within the database. They are used to encapsulate oft-used queries, such as conditional statements, loops, and other powerful programming features.

Stored procedures are similar to functions in high-level programming languages. They support both input and output parameters, as well as a return value. Stored procedures can return rows of data or single values.

## CREATE PROCEDURE 

To create stored procedures, the T-SQL statement CREATE PROCEDURE is used.

CREATE PROCEDURE procedure_name
AS
sql_statement
GO;


The CREATE PROCEDURE statement must be the only one in the T-SQL batch. All statements from the AS keyword until the end of the script or until the end of the batch (using a batch separator such as GO) will become the body of the stored procedure.

## Executing Stored Procedures

The EXECUTE statement is used to execute stored procedures. It is recommended that you qualify the procedure name with the schema name when executing stored procedures. This helps the database engine improve its performance as it does not have to search multiple schemas to find the required procedure. Moreover, it also prevents you from executing the wrong procedure if a database has procedures with the same name in different schemas.\





![image](https://user-images.githubusercontent.com/68102477/156908586-91aa8515-f251-4741-b37a-04f30e25c12c.png)

## USE CASE

![image](https://user-images.githubusercontent.com/68102477/156908711-d470b570-2636-40bb-b042-d03f87c84289.png)

![image](https://user-images.githubusercontent.com/68102477/156909335-2e8df993-1a18-4882-8aee-44dc8a9e6479.png)

![image](https://user-images.githubusercontent.com/68102477/156909344-89cd2564-2647-4250-a8e9-7e2d4bbac72a.png)

SQL Server, Oracle, MySQL and the like support stored procedures. Stored Procedures are a piece of code that perform some repetitive set of actions. They perform a particular task by executing a set of actions or queries against the database.

![image](https://user-images.githubusercontent.com/68102477/156909635-199ff443-0cda-480d-afeb-bc8d79a5d8f8.png)

![image](https://user-images.githubusercontent.com/68102477/156909728-33858189-5845-49e1-a741-410755e7eb19.png)

### Better Security with SPs. Users only have access to execute SPs rathher than having to grant accesses to tables. 

![image](https://user-images.githubusercontent.com/68102477/156909754-c6bfda54-a4d5-4d3b-98ff-70493e0d54f6.png)

![image](https://user-images.githubusercontent.com/68102477/156909807-745cf4ee-4128-4b8f-b4ff-4aacb7195cac.png)

![image](https://user-images.githubusercontent.com/68102477/156909834-f980ed80-d440-451f-ac82-cd7350ea2657.png)








