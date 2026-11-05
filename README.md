# Database Project

## Development of an E-Commerce and Management System for Norminring Motorbikes

## Project Overview

This project focuses on the database design and development of an **E-Commerce and Management System for Norminring Motorbikes**.

The system is designed to manage business operations such as products, categories, customers, inventory, orders, payments, suppliers, and purchase transactions.

The database uses **MySQL** to store, organize, and manage information efficiently while maintaining relationships between different tables.

## Technologies Used

- **Database Management System:** MySQL
- **Database Name:** `norminring_db`
- **Database Tool:** phpMyAdmin / XAMPP
- **Query Language:** SQL
- **Database Design:** Entity Relationship Diagram (ERD)

## Database Tables

The `norminring_db` database consists of 23 tables:

| No. | Table Name | Description |
|---|---|---|
| 1 | `categories` | Stores product categories. |
| 2 | `customers` | Stores customer information. |
| 3 | `customer_addresses` | Stores customer addresses. |
| 4 | `inventory` | Tracks available product stocks. |
| 5 | `orders` | Stores customer order information. |
| 6 | `order_items` | Stores the products included in each order. |
| 7 | `payments` | Records payment transactions. |
| 8 | `payment_methods` | Stores available payment methods. |
| 9 | `products` | Stores product information and details. |
| 10 | `product_suppliers` | Connects products with their suppliers. |
| 11 | `purchase_orders` | Stores purchase orders from suppliers. |
| 12 | `purchase_order_items` | Stores products included in purchase orders. |
| 13 | `returns` | Records customer product returns. |
| 14 | `return_items` | Stores the individual items included in returns. |
| 15 | `roles` | Stores user roles and permissions. |
| 16 | `stock_movements` | Tracks inventory stock changes. |
| 17 | `suppliers` | Stores supplier information. |
| 18 | `supplier_addresses` | Stores supplier addresses. |
| 19 | `system_audit_logs` | Records system activities and changes. |
| 20 | `users` | Stores system user accounts. |
| 21 | `vehicle_fitments` | Stores product compatibility information for vehicles. |
| 22 | `vehicle_models` | Stores motorcycle and vehicle model information. |

## Main Database Modules

The database is organized into the following functional areas:

- **Product Management** – Manages products, categories, and vehicle compatibility.
- **Customer Management** – Handles customer information and addresses.
- **Inventory Management** – Tracks product stocks and stock movements.
- **Order Management** – Manages customer orders and order items.
- **Payment Management** – Handles payment transactions and payment methods.
- **Supplier Management** – Manages suppliers, addresses, and product suppliers.
- **Purchase Order Management** – Records purchases from suppliers.
- **Returns Management** – Tracks returned products and return items.
- **User Management** – Handles user accounts and roles.
- **System Monitoring** – Records system activities through audit logs.

## Project Status

**Current Status:** Initial Database Design and Implementation

This repository contains the database structure and related documentation, including:

- Entity Relationship Diagram (ERD)
- MySQL Database Tables
- SQL Queries
- Data Dictionary
- Database Relationships

## Installation and Setup

1. Install XAMPP or MySQL.
2. Start the MySQL service.
3. Open phpMyAdmin or MySQL Workbench.
4. Create a database named `norminring_db`.
5. Import the provided SQL file.
6. Execute the SQL script to create the database tables and relationships.

## Project Purpose

This project is developed as part of an academic database project to apply database design principles and MySQL implementation in creating an organized e-commerce and management database for Norminring Motorbikes.

---

**Note:** This project is currently under development. The database structure and documentation may be updated as development progresses.
