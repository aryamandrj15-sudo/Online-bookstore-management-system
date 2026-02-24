# 📚 Online Bookstore Management System (SQL Project)

## 📌 Project Overview

This project implements a **database backend for an Online Bookstore Management System** using MySQL.
It demonstrates database design concepts such as table creation, constraints, relationships, schema modification, and real-world database operations.

The system manages authors, books, customers, orders, payments, delivery agents, reviews, returns, and more.

This project was implemented using **SQL Data Definition Language (DDL)** queries.

---

## 🛠️ Technologies Used

* MySQL
* SQL (DDL Commands)
* MySQL Workbench

---

## 🎯 Features Implemented

### ✅ Database Creation

* Created database `Onlinebookstore`
* Structured relational schema for bookstore management

### ✅ Entity Tables

The following main tables were created:

* **Authors** – Stores author details
* **Categories** – Book categories
* **Books** – Book inventory with constraints
* **Customers** – Customer information
* **Orders** – Customer orders
* **OrderDetails** – Order items with composite primary key
* **Payments** – Payment details
* **DeliveryAgents / DeliveryTeam** – Delivery personnel
* **ReturnRequests** – Book return management
* **Wishlists** – Customer wishlist system
* **DeliveryLogs** – Delivery tracking
* **BookReviews** – Book feedback
* **Coupons** – Discount management
* **OrderNotes** – Order notes

---

## 🔐 Constraints Implemented

### ✔ Primary Keys

* Unique identification of records
* Composite primary keys used (e.g., OrderDetails, Wishlists)

### ✔ Foreign Keys

* Maintains relationships between tables
* Ensures referential integrity

Examples:

* Books → Authors, Categories
* Orders → Customers
* OrderDetails → Orders, Books
* Payments → Orders

### ✔ CHECK Constraints

* Phone validation (starts with 7, 8, or 9)
* Price and quantity restrictions
* Rating limits (1–5)
* Region validation
* Discount limits

### ✔ UNIQUE Constraints

* Category name uniqueness
* Email uniqueness
* ISBN uniqueness
* Coupon codes uniqueness

### ✔ DEFAULT Values

* Order status = "Pending"
* Payment method = "Cash"
* Region = "North"
* Edition = "First"
* Coupon status = "Active"

---

## 🔄 Schema Modifications Performed

The project also demonstrates advanced schema operations:

* Adding and dropping columns
* Renaming tables and columns
* Modifying data types
* Adding and removing constraints
* Truncating tables
* Dropping tables
* Recreating tables

---

## 👁️ View Creation

### **TopSellingBooks View**

Displays:

* Book ID
* Book title
* Total quantity sold

Used to identify best-selling books.

---

## 🏗️ Database Design Concepts Demonstrated

* Relational database modeling
* Data integrity enforcement
* Constraint management
* Table relationships
* Schema evolution
* Real-world database operations

---

## ▶️ How to Run the Project

1. Open **MySQL Workbench**
2. Create a new SQL script
3. Copy and paste the SQL code
4. Execute the script
5. The `Onlinebookstore` database and tables will be created

---

## 📂 Project Structure

```
Online-Bookstore-Management-System/
│
├── online_bookstore.sql
└── README.md
```

---

## 👨‍💻 Author

**Aryaman Kumar**

* Bachelor of Engineering (Computer Science)
* Interest: Finance, Stock Market, and FinTech
