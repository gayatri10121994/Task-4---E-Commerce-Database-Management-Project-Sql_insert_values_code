 # Task-4---E-Commerce-Database-Management-Project-Sql_insert_values_code

E-Commerce-Database-management-project
As a part of our course, I made this project for Database Management Systems (DBMS). This project contains theoretical as well as implementation in SQL.
 Implementation

o	Creating tables

o	Inserting data
Contents
• Project Description

• Basic structure

o	Functional requirements

o	Entity Relation (ER) diagram and constraints

o	Relational database schema

Pre-requisite
• MySQL

Project Description
The E-Commerce Database Management Project (DBMD) is a comprehensive solution designed to streamline and optimize the operations of an e-commerce business. This project focuses on creating a robust database management system that facilitates efficient handling of various aspects of an online store, from product inventory to customer

Relational Database Schema - e-commerce -ER diagram

![E commerce ER Diagram](https://github.com/user-attachments/assets/89e5105a-ae26-4752-8101-523c6701ecc6)

ER diagram

![ECommerce](https://github.com/user-attachments/assets/daa5afdf-90bc-4802-953f-022ff45ffa65)

Create Schema(database) in MySQL
  create schema e_commerce;

  Create Tables
Customer Table

   create table e_commerce.customer (
     customer_id int primary key,
     FirstName varchar(50),
     MiddleName varchar(50),
     LastName varchar(50),
     Email varchar(100),
     DateOfBirth date,
     phone INT(10),
     age int null
   );




