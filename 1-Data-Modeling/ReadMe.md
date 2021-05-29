# Notes

## Basics

### Databases: 
A database is a structured repository or collection of data that is stored and retrieved electronically for use in applications. 
Data can be stored, updated, or deleted from a database.

**Database Management System (DBMS):** The software used to access the database by the user and application is the database management system. Check out these few links describing a DBMS in more detail.

**DDL** is short name of Data Definition Language, which deals with database schemas and descriptions, of how the data should reside in the database.

**CREATE:** to create a database and its objects like (table, index, views, store procedure, function, and triggers)
**ALTER:** alters the structure of the existing database
**DROP:** delete objects from the database
**TRUNCATE:** remove all records from a table, including all spaces allocated for the records are removed
**COMMENT:** add comments to the data dictionary
**RENAME:** rename an object

**DML** is short name of Data Manipulation Language which deals with data manipulation and includes most common SQL statements such SELECT, INSERT, UPDATE, DELETE, etc., and it is used to store, modify, retrieve, delete and update data in a database.

**SELECT:** retrieve data from a database
**INSERT:** insert data into a table
**UPDATE:** updates existing data within a table
**DELETE:** Delete all records from a database table
**MERGE:** UPSERT operation (insert or update)
**CALL:** call a PL/SQL or Java subprogram
**EXPLAIN PLAN:** interpretation of the data access path
**LOCK TABLE:** concurrency Control

[Introduction to DBMS](https://www.geeksforgeeks.org/database-management-system-introduction-set-1/)

[DBMS as per Wikipedia](https://en.wikipedia.org/wiki/Database#Database_management_system)

## What is Data Modeling?


![image](https://user-images.githubusercontent.com/68102477/120060597-f783b580-c09b-11eb-9089-7acec763ca3f.png)

**Does data modeling happen before you create a database, or is it an iterative process?**

It's definitely an iterative process. Data engineers continually reorganize, restructure, and optimize data models to fit the needs of the organization.

**How is data modeling different from machine learning modeling?**

Machine learning includes a lot of data wrangling to create the inputs for machine learning models, but data modeling is more about how to structure data to be used by different people within an organization. You can think of data modeling as the process of designing data and making it available to machine learning engineers, data scientists, business analytics, etc., so they can make use of it easily.

![image](https://user-images.githubusercontent.com/68102477/120060706-94465300-c09c-11eb-9081-4c6b21891011.png)

![image](https://user-images.githubusercontent.com/68102477/120061039-8eea0800-c09e-11eb-8cea-140fa1b33454.png)
