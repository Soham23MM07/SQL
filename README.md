SQL (Structured Query Language) is a programming language used to manage and manipulate relational databases. It allows you to store, retrieve, update, and delete data efficiently.

Relational Database
A Database which stores data in the form of table (rows and coloumns).

imagine excel sheet
creation of tables
connection of table (forgien key and primary key)

examples
MYSQL
POSTGRESQL
SQLITE

MYSQL is a software which is known as Relational Database Management System.

MySQL is also a database these two terms RDBMs and datbase is used interchangebly

Terminology

Datum:Data
Database:collection of data
Table: rows and coloumns
Record: a single row
RDBMS:Relational Database Management System

PostgreSQL

This we get in installation of postgresql

PostgreSQL Server is the database management system (DBMS) that runs in the background, managing and storing data.

pgAdmin 4 is a GUI (Graphical User Interface) tool for managing PostgreSQL databases. Instead of running SQL commands in the terminal, you can use pgAdmin’s user-friendly interface to:

DDL --> Data Definition Language --> list of commands for creating, modifying and deleting database objects (use to alter table coloumn and to add some new ones)

create table --> create new table
alter table --> modify existing table
drop table --> delete existing table
truncate table --> delete all rows but retains schema
rename table --> rename existing table

DML --> Data Manipulation Language --> list of commands for inserting, updating and deleting data

insert into --> insert data into table
update --> update existing data
delete --> delete existing data
select --> retrieve existing data

DCL --> Data Control Language --> list of commands for granting and revoking access to database objects

grant --> grant access to database objects
revoke --> revoke access to database objects

TCL --> Transaction Control Language --> list of commands for starting, committing and rolling back transactions

begin --> start a transaction
commit --> commit a transaction
rollback --> roll back a transaction
savepoint --> save a transaction point

DTO --> Data Transfer Object --> object used to transfer data between different layers of an application

DQL --> Data Query Language --> list of commands for querying data  
select --> retrieve existing data

Normaization
No Data redundancy and maintain data integrity

1NF--> 1st Normal Form
2NF--> 2nd Normal Form
3NF--> 3rd Normal Form
BCNF--> Boyce Codd Normal Form

JOINS

1. Inner Join --> return rows that have matching values in both tables
2. Left Join --> return all rows from the left table, and the matched rows from the right table
3. Right Join --> return all rows from the right table, and the matched rows from the left table
4. Full Join --> return all rows when there is a match in either left or right table
5. Cross Join --> return all rows from one table crossed with all rows from another table
