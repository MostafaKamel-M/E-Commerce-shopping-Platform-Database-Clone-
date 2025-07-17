# E-Commerce-shopping-Platform-Database-Clone
A comprehensive relational database system designed to simulate the core functionalities of an e-commerce platform, inspired by Lazada Malaysia. This project demonstrates robust database design principles, efficient data management, and advanced SQL capabilities to handle various aspects of an online marketplace.

## 🗂 Project Overview

This project was developed as a core assignment for the "TIS1101 Database Fundamentals" course, where I had the privilege of leading the group. It provided an invaluable opportunity to delve deep into the theoretical and practical aspects of relational databases and SQL. The primary objective was to construct a simplified yet functional backend database for an e-commerce system, mirroring key operations found in platforms like Lazada. The project encompasses:

- **Conceptual Design**: Creation of a detailed Entity-Relationship Diagram (ERD) to map out entities and their relationships.
- **Logical Design**: Development of a comprehensive data dictionary specifying table structures, data types, constraints, and relationships.
- **Physical Implementation**: Translation of the logical design into executable SQL `CREATE TABLE` statements.
- **Data Initialization**: Populating the database with realistic sample transactional data using SQL `INSERT` statements.
- **Advanced Data Manipulation**: Implementation of various SQL queries and database objects to manage, analyze, and automate e-commerce operations.

## 📌 Key Features

This database system incorporates several key features to ensure data integrity, efficiency, and practical utility:

- ✅ **Relational Schema with Strong Constraints**: All tables are designed with proper **Primary Key** and **Foreign Key** constraints to enforce data integrity and define clear relationships between entities such as Customers, Products, Orders, Vendors, and Ratings.
- ✅ **Normalized Tables (up to 3NF)**: The database schema adheres to third normal form (3NF) to minimize data redundancy and improve data consistency, ensuring efficient storage and retrieval of information.
- ✅ **Comprehensive Sample Transactional Data**: The database is pre-populated with a diverse set of sample data for all entities, facilitating immediate testing, demonstration, and analysis of e-commerce operations.
- ✅ **Advanced SQL Querying Capabilities**: The project showcases a wide array of SQL queries for critical e-commerce operations, including:
  - **Order Tracking**: Monitoring the status and location of customer orders.
  - **Customer Credit Management**: Handling and tracking customer credit balances.
  - **Vendor Performance Analysis**: Evaluating vendor sales and product contributions.
  - **Product Inventory Management**: Keeping track of product quantities on hand.
- ✅ **Implementation of Database Objects for Automation and Reporting**:
  - **Views for Reporting**: Utilized to create virtual tables for simplified data retrieval and reporting, such as `ORDERS_OUT_FOR_DELIVERY`.
  - **Triggers for Inventory Updates**: Conceptual triggers are designed to automatically adjust product quantities upon listing or sale, ensuring real-time inventory accuracy.
  - **Stored Procedures for Business Logic Automation**: Conceptual stored procedures are outlined for automating complex business processes, such as retrieving all products from a specific vendor.
  - **Aggregate Functions**: Extensive use of `MAX()`, `MIN()`, `COUNT()`, `SUM()`, and `AVG()` for data summarization and analytical reporting.
  - **Subqueries/Nested Queries**: Employed for complex data retrieval scenarios, such as identifying high-value customers based on order patterns.
  - **`GROUP BY` and `HAVING` Clauses**: Used for grouping data and filtering aggregated results, enabling detailed categorical analysis.
  - **Advanced SQL Functions**: Demonstrations of `RAND()` for random product selection, `FETCH` for limiting query results, and `RANK()` for data ranking and ordering.

## 📊 Example Use Cases

The implemented database and its features support various practical e-commerce use cases:

- **Inventory Management**: Easily track current inventory levels for all products and automatically update stock based on sales or new listings.
- **Order Fulfillment**: Monitor and automatically update order statuses from placement to delivery, providing real-time tracking information.
- **Customer Relationship Management (CRM)**: Analyze customer behavior, manage credit, and track ratings to enhance customer satisfaction and targeted marketing efforts.
- **Vendor Management**: Evaluate vendor performance through sales data and product contributions, fostering better vendor relationships.
- **Sales Analysis**: Simulate and analyze e-commerce transactions to identify trends, popular products, and revenue streams.
- **Reporting**: Generate quick reports on key metrics like products out for delivery, top-rated products, or category-wise sales.

## 📄 Report

A detailed PDF report, `Database_Assignment.pdf`, is included in the repository. This report provides an in-depth explanation of the database schema, the rationale behind the query designs, and the conceptual implementation of automation features like triggers and stored procedures. It serves as a comprehensive guide to understanding the project's architecture and functionality.

---
