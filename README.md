# 📚 Bookstore Management System – SQL Project

## 📌 Project Overview

The **Bookstore Management System** is a SQL-based database project developed using **PostgreSQL** to efficiently manage books, customers, orders, inventory, and sales information.

The project demonstrates practical SQL skills such as **database design, table creation, primary and foreign keys, data import, filtering, aggregation, joins, grouping, sorting, and subqueries/advanced queries**.

## 🛠️ Technologies Used

* **PostgreSQL**
* **SQL**
* **CSV Data**

## 🗂️ Database Structure

The project consists of three main tables:

### 1. Books

Stores information about books available in the bookstore.

**Columns:**

* Book_ID
* Title
* Author
* Genre
* Published_Year
* Price
* Stock

### 2. Customers

Stores customer information.

**Columns:**

* Customer_ID
* Name
* Email
* Phone
* City
* Country

### 3. Orders

Stores customer order and transaction details.

**Columns:**

* Order_ID
* Customer_ID
* Book_ID
* Order_Date
* Quantity
* Total_Amount

The `Orders` table uses foreign keys to establish relationships with the `Customers` and `Books` tables.

## 🔑 Key Features

* Create and manage book records
* Maintain customer information
* Track customer orders
* Manage book stock and inventory
* Analyze sales and revenue
* Filter books by genre and publication year
* Identify expensive and low-stock books
* Analyze customer purchasing behavior
* Calculate total books sold by genre and author
* Identify frequently ordered books
* Find high-spending customers
* Calculate remaining stock after fulfilling orders

## 📊 SQL Concepts Demonstrated

This project covers several important SQL concepts:

* `CREATE TABLE`
* `DROP TABLE`
* Primary Keys
* Foreign Keys
* `COPY` for CSV data import
* `SELECT`
* `WHERE`
* `BETWEEN`
* `ORDER BY`
* `GROUP BY`
* `HAVING`
* `JOIN`
* `SUM()`
* `AVG()`
* `COUNT()`
* `DISTINCT`
* `LIMIT`
* `COALESCE()`
* Aggregate Functions
* Inventory and sales analysis

## 🔍 Sample Analysis

The project includes SQL queries to:

* Retrieve books from the Fiction genre
* Find books published after 1950
* Identify customers from Canada
* Retrieve orders placed during November 2023
* Calculate total available book stock
* Find the most expensive book
* Calculate total revenue
* Find the average price of Fantasy books
* Identify customers with at least two orders
* Find the most frequently ordered book
* Retrieve the top three most expensive Fantasy books
* Calculate books sold by each author
* Identify cities with customers spending more than $30
* Find the customer with the highest total spending
* Calculate remaining stock after fulfilling orders

## 📁 Project Files

```text
bookstore-management-system-sql/
│
├── Project.sql
├── Books.csv
├── Customers.csv
├── Orders.csv
└── README.md
```

## ⚙️ How to Run the Project

### Step 1: Install PostgreSQL

Install PostgreSQL and open **pgAdmin** or another PostgreSQL-compatible SQL editor.

### Step 2: Create a Database

Create a new database, for example:

```sql
CREATE DATABASE bookstore_management;
```

### Step 3: Connect to the Database

Connect to the newly created database using pgAdmin or PostgreSQL.

### Step 4: Run the SQL Script

Open `Project.sql` and execute the SQL commands.

### Step 5: Import CSV Data

The project uses CSV files for importing data into the Books, Customers, and Orders tables.

Make sure the CSV file paths in the SQL script match the location of your files.

## 🎯 Project Objective

The main objective of this project is to demonstrate the practical application of **SQL and relational database concepts** for managing bookstore data and performing meaningful business analysis using structured queries.

## 👨‍💻 Skills Demonstrated

**SQL | PostgreSQL | Database Management | Data Analysis | Joins | Aggregations | Relational Database Design | Inventory Analysis | Sales Analysis**
