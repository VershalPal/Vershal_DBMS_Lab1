# E-Commerce Database Management System

This project involves designing a database schema for an E-Commerce website and developing SQL queries to retrieve data from the database. The schema includes tables for managing suppliers, customers, categories, products, supplier pricing, orders, and ratings.

## Database Schema

- **Supplier**: Stores information about suppliers such as ID, name, city, and phone number.
- **Customer**: Contains details of customers including ID, name, phone number, city, and gender.
- **Category**: Stores categories of products.
- **Product**: Contains information about products such as ID, name, description, and category ID.
- **Supplier_Pricing**: Stores pricing information for products supplied by each supplier.
- **Order**: Contains order details including ID, amount, date, customer ID, and pricing ID.
- **Rating**: Stores ratings provided by customers for products and suppliers.

## Queries

1. Display the total number of customers based on gender who have placed individual orders of worth at least Rs. 3000.
2. Display all the orders along with product name ordered by a customer with Customer_ID = 2.
3. Display the Supplier details who can supply more than one product.
4. Find the least expensive product from each category and print the table with category ID, name, product name, and price.
5. Display the ID and Name of the products ordered after "2021-10-05".
6. Display customer name and gender whose names start or end with the character 'A'.
7. Create a stored procedure to display supplier ID, name, average rating of all products sold by every customer, and type of service based on the average rating.

## Learning Objectives

- Understand database schemas for a business organization.
- Design the database and corresponding tables needed for an E-Commerce website.
- Design SQL queries to retrieve data involving select queries, group by, order by, having clauses, joins, subqueries, and procedures.

## IDE used :
- MySQL Workbench v8.0.32
