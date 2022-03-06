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
