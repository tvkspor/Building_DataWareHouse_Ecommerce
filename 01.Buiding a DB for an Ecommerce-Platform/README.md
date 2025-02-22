# Building Database for E-commerce Platform

## 1. Overview

This project focuses on designing a database for an E-commerce platform based on specific requirements. The database is structured to support various functionalities such as product management, customer information, order processing, and revenue analysis.

## 2. Data and Design Requirement

For detail information about data requirement and design requirement please visit:
[Building a DB for an Ecommerce Platform (1) (PDF)](Building_a_DB_for_an_Ecommerce-Platform(1).pdf)



## 3. Features

- **Scalable Database Design**: Optimized for performance and efficiency.
- **Comprehensive Data Schema**: Includes tables for products, customers, orders, payments, and sales analytics.
- **Data Integrity & Normalization**: Ensures data consistency and reduces redundancy.

## 4. Database Schema

The database follows a relational model with the following key tables:

- `Users` – Stores customer and admin details.
- `Products` – Contains product information such as name, category, and price.
- `Orders` – Tracks customer orders and their statuses.
- `Payments` – Manages transaction details.
- `Sales` – Records sales data for revenue analysis.

EERD design for DB:
![EERD of E-Commerce Database](EERD_E-Commercial_DB.png)

RM design for DB:
![RelationalMapping of E-Commerce Database](RM_E-Commercial_DB.png)

## 5. Technologies Used

- **Database Management System (DBMS)**: Microsoft SQL Server
- **Entity-Relationship Diagram (ERD)**: Designed to visualize data relationships.
- **Data Warehousing Concepts**: Used for revenue analysis and reporting.

## 6. Insert data into database and buiding API ( build with NodeJS ) to test some function with database
For more information please visit:
[Building a DB for an Ecommerce Platform (2) (PDF)](Building_a_DB_for_an_Ecommerce-Platform(2).pdf)

Link API repo: [Link](https://github.com/livensmi1e/database-assignment)

## 7. Future Enhancements

- Implement data indexing for faster queries.
- Add NoSQL support for handling unstructured data.
- Integrate with BI tools for advanced analytics.

