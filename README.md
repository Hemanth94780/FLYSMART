
# 🛫 FlySmart – Smart Flight Guide

**FlySmart** is a full-featured **Flight Booking Management System** developed as a part of the Database Management Systems (CSBB 204) course. This project demonstrates the practical application of DBMS concepts through a dynamic, user-friendly flight reservation platform that caters to both passengers and administrators.

---

## 📌 Project Overview

In the complex domain of air travel, **FlySmart** aims to simplify and optimize flight booking and management. It integrates critical functionalities such as real-time flight updates, ticket generation, payment processing, and admin dashboards — all built on a solid relational database foundation.

---

## ✨ Features

- ✅ **User Registration & Login**
- 🛫 **Flight Search & Booking**
- 🧾 **E-ticket Generation & Printing**
- 💳 **Secure Payment Integration**
- 🔁 **Ticket Cancellation & Refund**
- 📋 **Admin Dashboard to Add/Update Flights**
- 🔍 **Flight Status & Booking History**
- 💬 **Passenger Feedback Submission**
- 🔐 **Data Security & Access Control**

---

## 🧰 Tech Stack

| Layer       | Technology               |
|-------------|---------------------------|
| Frontend    | HTML, CSS, JavaScript     |
| Backend     | PHP                       |
| Database    | MySQL                     |
| Local Server| XAMPP                     |

---

## 📚 DBMS Concepts Applied

- Entity-Relationship (ER) Diagram
- Mapping ER Model to Relational Model
- SQL Queries (Basic and Advanced)
- Relational Schema Design
- Data Dictionary
- Populated Tables
- Foreign Key Constraints
- PHP-MySQL Connectivity

---

## 🗂️ Folder Structure

```
📦FlySmart
 ┣ 📁frontend
 ┃ ┣ 📄index.html
 ┃ ┣ 📄login.php
 ┃ ┣ 📄register.php
 ┃ ┣ 📄book_ticket.php
 ┃ ┗ 📄...
 ┣ 📁backend
 ┃ ┣ 📄db_connect.php
 ┃ ┣ 📄insert_user.php
 ┃ ┣ 📄fetch_flights.php
 ┃ ┗ 📄...
 ┣ 📁sql
 ┃ ┣ 📄schema.sql
 ┃ ┣ 📄sample_data.sql
 ┃ ┗ 📄advanced_queries.sql
 ┗ 📄README.md
```

---

## ⚙️ System Requirements

### Hardware:
- OS: Windows 7 or later
- RAM: 1 GB or more
- Disk: 200 MB free space
- Processor: Intel Pentium 4 or higher

### Software:
- Web Browser (Chrome/Firefox)
- XAMPP (for Apache + MySQL)
- Text Editor (VS Code, Sublime, etc.)

---

## 🔗 Database Connectivity

FlySmart uses PHP and MySQL to establish backend connectivity:
```php
$servername = "localhost";
$username = "root";
$password = "root";
$dbname = "flysmart";

$conn = new mysqli($servername, $username, $password, $dbname);
if ($conn->connect_error) {
    die("Connection failed: " . $conn->connect_error);
}
```

---


