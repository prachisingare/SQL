# SQL
Welcome to the  SQL Repository ! 

# 🗄️ SQL Repository – Learn, Practice, and Master SQL

Welcome to the **SQL Repository** – your go-to resource for learning and practicing Structured Query Language (SQL). Whether you're a beginner or preparing for interviews, this collection of scripts and examples will guide you through the essential concepts of working with relational databases.

---

## 📚 What is SQL?

**SQL (Structured Query Language)** is the standard language used to manage and manipulate relational databases. With SQL, you can:

- Create databases and tables
- Insert, update, and delete data
- Retrieve data using queries
- Apply conditions, filters, and sorting
- Join multiple tables
- Use functions for aggregation
- Manage access control and permissions

---

## 📁 Repository Contents

```bash
sql-repository/
├── 01_create_tables.sql         # Script to create tables
├── 02_insert_data.sql           # Insert sample data into tables
├── 03_basic_select.sql          # Basic SELECT queries with WHERE, ORDER BY
├── 04_joins.sql                 # Examples of INNER, LEFT, RIGHT, FULL JOIN
├── 05_aggregate_functions.sql   # Using COUNT, SUM, AVG, MAX, MIN
├── 06_groupby_having.sql        # GROUP BY with HAVING clause
├── 07_subqueries.sql            # Nested SELECTs and correlated subqueries
├── 08_constraints.sql           # PRIMARY KEY, FOREIGN KEY, UNIQUE, NOT NULL
├── 09_views_indexes.sql         # Creating and using views and indexes
├── 10_transactions.sql          # COMMIT, ROLLBACK, SAVEPOINT usage
├── 11_ddl_dml_dcl.sql           # Overview of SQL command types
└── README.md                    # Documentation (this file)
```

---

## 🔍 Topics Covered

### ✅ SQL Command Categories
- **DDL (Data Definition Language)** – CREATE, ALTER, DROP
- **DML (Data Manipulation Language)** – INSERT, UPDATE, DELETE
- **DCL (Data Control Language)** – GRANT, REVOKE
- **TCL (Transaction Control Language)** – COMMIT, ROLLBACK

### ✅ Querying Data
- SELECT queries with filters, sorting, and limiting
- Pattern matching with `LIKE`
- Use of aliases and expressions

### ✅ Joins
- INNER JOIN
- LEFT JOIN
- RIGHT JOIN
- FULL OUTER JOIN

### ✅ Grouping & Aggregation
- GROUP BY and HAVING clauses
- Aggregate functions like `COUNT`, `SUM`, `AVG`, `MAX`, `MIN`

### ✅ Subqueries
- Simple subqueries
- Correlated subqueries
- Use in WHERE, FROM, and SELECT

### ✅ Constraints
- NOT NULL, UNIQUE, PRIMARY KEY, FOREIGN KEY, CHECK

### ✅ Views and Indexes
- Creating reusable virtual tables with views
- Improving performance with indexes

### ✅ Transactions
- Atomic operations using BEGIN, COMMIT, ROLLBACK
- Savepoint for intermediate rollbacks

---

## 🧪 Sample Query

```sql
SELECT department, COUNT(*) AS total_employees
FROM employees
GROUP BY department
HAVING COUNT(*) > 5;
```

---

## 🧩 SQL Project Ideas

- 🏫 Student Record Management
- 🏥 Hospital Patient Database
- 🏬 Inventory & Order Management
- 🧾 Invoice and Billing System
- 🏦 Bank Transaction Management

---


## 🎯 Who Is This For?

- Beginners learning SQL syntax
- Students working on database projects
- Aspiring Data Analysts or Data Scientists
- Software Developers needing backend SQL skills
- Anyone preparing for technical interviews

---



