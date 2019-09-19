# SQL (Structured Query Language)

## Summary

- In current times data is more valuable than Gold and Oil.
- Datas are recorded in a Database.
- Database is a structured set of Data held in a computer that is accessible in various ways
- SQL is a Database language which can be used to perform certain operations and also create a new database

## Types of database

- Flat field Database - Stores everything in one single table
- Relational Database - Separates masses of databases into numerous table and link them through keys
- Big Data - Used for Data analytics and Business Intelligence

### Relational database

#### Three types of relationship

- One to One - Each row in table A is linked to no more than one row in table B
- One to Many - Each row can be related to many rows in the relating table
- Many to Many - One or more rows in a table can be related to one or more in another table

#### Keys

- Primary Key
  - Column or group of columns in a table which helps us to uniquely identify every row in that table
  - Each table can have only one
  - Most tables should have it
  - Values must never change
  - DBMS will enforce the uniqueness of the primary key
  - Auto incremented number would make a good primary key
- Foreign Keys
  - Used to create solid relationship between tables in a Database
  - Ensure the rows of information between two tables corresponds correctly
  - A table can have any amount of Foreign Key

## Types of SQL Command

### DDL - Data Definition Language

This Language Consists of Commands which can be used to define the database framework.
- CREATE - used to create the database or its objects (like table, index, function, views, store procedure and triggers).

- ALTER - used to alter the structure of the database.

- DROP - used to delete objects from the database.

- TRUNCATE - used to remove all records from a table, including all spaces allocated for the records are removed.

- COMMENT - used to add comments to the data dictionary.

- RENAME - used to rename an object existing in the database.

### DML - Data Manipulation Language

Commands that deals with the manipulation of data present in the database
- INSERT
- UPDATE
- DELETE

### DQL - Data Query Language

To get some schema relation based on the query passed to it.
- SELECT

### DCL - Data Control Language

Commands that deals with the rights, permissions and other controls of the database system.
- GRANT - gives user access privilege to databases
- REVOKE - reverses GRANT

### TCL - Transaction Control Language

Commands that deals with the transaction within the database.
- COMMIT - commits a transaction
- ROLLBACK - rollbacks a transaction
- SAVEPOINT - sets a savepoint within a transaction
- SET Transaction - specify characteristics of transaction

## Example Commands used
| COMMANDS                                                                | RESULTS                                                                            |
|-------------------------------------------------------------------------|------------------------------------------------------------------------------------|
| CREATE my-db                                                            | Creates database called my-db                                                      |
| USE my-db                                                               | Uses data from my-db Databse                                                       |
| CREATE TABLE film_table  ( flim_name VARCHAR(10) film_type VARCHAR(6) ) | Creates a table named film_table with column names called film_name and film_type. |
| SP_HELP film_table                                                      | Gives information on the data type of the columns                                  |
