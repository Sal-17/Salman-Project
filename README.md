Online Retail App Database Schema
This repository contains the SQL schema design for an online retail application. The database schema includes tables to handle user login, customer details, product management, shopping cart, orders, payment, shipment tracking, employee management, product reviews, and loyalty program transactions. The goal of this schema is to create a scalable and secure structure for a retail platform with a focus on ease of querying and future scalability.

Table Structure
1. User Login
Table: user_login
Stores user credentials, sign-up date, and other account-related information.
2. Customer Details
Table: customers
Stores additional details about customers, including loyalty points, address, and contact information.
3. Product Categories and Items
Tables: product_categories, product_items
product_categories organizes items into categories, while product_items holds details about each product.
4. Shopping Cart
Tables: cart, cart_items
cart maintains active shopping carts, while cart_items links products in each cart.
5. Orders and Payments
Tables: orders, order_items, payment
orders stores order status and customer ID, order_items links ordered products, and payment tracks payment methods and statuses.
6. Shipment Tracking
Table: shipments
Contains shipment tracking information, delivery statuses, and carrier information.
7. Employee Management
Tables: employment_type, employees
Stores employee information and employment types, including contractors and internal employees.
8. Product Reviews
Table: reviews
Allows customers to leave product feedback with ratings and review text.
9. Loyalty Program Transactions
Table: loyalty_transactions
Tracks loyalty points earned and redeemed by customers, encouraging return visits.
