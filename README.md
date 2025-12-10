📚 Book Store Management System

A full-stack web application designed to manage books, customers, and sales in a bookstore. 
This system helps in reducing manual record-keeping and makes book inventory management easier and faster.

🚀 Project Overview

This application allows the admin to:

Add, update, and delete books

Manage customer information

Track sales and inventory

View all book details in a user-friendly interface

The system is built using Spring Boot and Hibernate, with a MySQL database to store all book and sales records. The frontend is developed using Thymeleaf, HTML, and CSS.

🛠️ Tech Stack
Layer	Technology Used
Backend	Spring Boot, Hibernate, REST APIs
Frontend	HTML, CSS, Thymeleaf
Database	MySQL
Build Tool	Maven
Architecture	Layered Architecture (Controller → Service → Repository)

🔍 Key Features
✔ CRUD operations for Books & Customers
✔ Inventory and Sales Management
✔ Form validation & exception handling
✔ Secure and reliable data persistence using Hibernate ORM
✔ Clean and responsive UI using Thymeleaf

📐 System Architecture
Client (Thymeleaf UI)
       ↓
Controller Layer
       ↓
Service Layer (Business Logic)
       ↓
Repository Layer (Hibernate JPA)
       ↓
MySQL Database


📊 Workflow

Admin interacts with the UI

Controller accepts the request

Service layer processes logic

Repository accesses MySQL using JPA/Hibernate

Response returned back to UI


🎯 Learning Outcomes

Gained hands-on experience with Spring Boot and Hibernate

Learned CRUD operations with ORM and MySQL

Improved understanding of layered architecture and validation

Enhanced skills in full-stack development and REST API integration

📌 Conclusion

This project effectively digitalizes bookstore operations and helps in accurate inventory and sales tracking.
The architecture supports future enhancements like authentication, advanced dashboards, and online ordering.
