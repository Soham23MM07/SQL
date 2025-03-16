# 📌 Structured Query Language (SQL)

SQL (Structured Query Language) is a programming language used to manage and manipulate relational databases. It allows you to store, retrieve, update, and delete data efficiently.

---

## 📂 **Relational Database**

A database that stores data in the form of tables (rows and columns).

### 📝 **Think of it like an Excel Sheet:**

- **Creation of Tables**
- **Connection of Tables** (Foreign Key & Primary Key)

### 🔹 **Examples of Relational Databases:**

- **MySQL**
- **PostgreSQL**
- **SQLite**

> **MySQL** is a software known as a **Relational Database Management System (RDBMS)**.
>
> MySQL is also a **database**, and these two terms (RDBMS and database) are often used interchangeably.

---

## 📖 **Terminology**

- **Datum** → Data
- **Database** → Collection of data
- **Table** → Rows and columns
- **Record** → A single row
- **RDBMS** → Relational Database Management System

---

## 🛠️ **PostgreSQL**

This is what we get when we install **PostgreSQL**:

### 🚀 **PostgreSQL Server**

> The database management system (DBMS) that runs in the background, managing and storing data.

### 🎛️ **pgAdmin 4**

> A GUI (Graphical User Interface) tool for managing PostgreSQL databases.
> Instead of running SQL commands in the terminal, you can use **pgAdmin's user-friendly interface** to manage your database.

---

## 🔧 **SQL Commands Categories**

### 📌 **DDL - Data Definition Language**

> Commands for creating, modifying, and deleting database objects.

| Command          | Description                       |
| ---------------- | --------------------------------- |
| `CREATE TABLE`   | Create a new table                |
| `ALTER TABLE`    | Modify an existing table          |
| `DROP TABLE`     | Delete an existing table          |
| `TRUNCATE TABLE` | Delete all rows but retain schema |
| `RENAME TABLE`   | Rename an existing table          |

---

### 📌 **DML - Data Manipulation Language**

> Commands for inserting, updating, and deleting data.

| Command       | Description              |
| ------------- | ------------------------ |
| `INSERT INTO` | Insert data into a table |
| `UPDATE`      | Update existing data     |
| `DELETE`      | Delete existing data     |
| `SELECT`      | Retrieve existing data   |

---

### 📌 **DCL - Data Control Language**

> Commands for granting and revoking access to database objects.

| Command  | Description                       |
| -------- | --------------------------------- |
| `GRANT`  | Grant access to database objects  |
| `REVOKE` | Revoke access to database objects |

---

### 📌 **TCL - Transaction Control Language**

> Commands for managing transactions.

| Command     | Description              |
| ----------- | ------------------------ |
| `BEGIN`     | Start a transaction      |
| `COMMIT`    | Commit a transaction     |
| `ROLLBACK`  | Rollback a transaction   |
| `SAVEPOINT` | Save a transaction point |

---

### 📌 **DQL - Data Query Language**

> Commands for querying data.

| Command  | Description            |
| -------- | ---------------------- |
| `SELECT` | Retrieve existing data |

---

## 🛡️ **Data Transfer Object (DTO)**

> An object used to transfer data between different layers of an application.

---

## 🔄 **Normalization**

> Ensures **no data redundancy** and **maintains data integrity**.

| Normal Form | Description            |
| ----------- | ---------------------- |
| **1NF**     | First Normal Form      |
| **2NF**     | Second Normal Form     |
| **3NF**     | Third Normal Form      |
| **BCNF**    | Boyce-Codd Normal Form |

---

## 🔗 **JOINS in SQL**

> Used to retrieve data from multiple tables based on relationships.

| Join Type      | Description                                                                |
| -------------- | -------------------------------------------------------------------------- |
| **Inner Join** | Returns rows that have matching values in both tables                      |
| **Left Join**  | Returns all rows from the left table and matched rows from the right table |
| **Right Join** | Returns all rows from the right table and matched rows from the left table |
| **Full Join**  | Returns all rows when there is a match in either left or right table       |
| **Cross Join** | Returns all rows from one table crossed with all rows from another table   |

---

📢 **Happy Coding!** 🚀
