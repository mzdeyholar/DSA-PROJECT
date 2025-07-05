# DSA-PROJECT
My developmental milestone in DSA

## MY CAPSTONE PROJECT

###AMAZON PROJECT

####PROJECT OVERVIEW

A project analysed to generate insights that can guide product improvement, marketing strategies, and customer engagement in Amazon. 

##### TOOLS USED
- Microsoft EXCEL [Download Here] {microsoft.com}
  -- For data cleaning
  -- Data mnipulation
- SQL
  ###### DATA ANALYSIS
  ```Step 1: Create the database
CREATE DATABASE KMS_database;

-- Use the database
USE KMS_database;

Create the sales table with all your listed columns
CREATE TABLE sales (
    row_id INT PRIMARY KEY AUTO_INCREMENT,
    order_id VARCHAR(50),
    order_date DATE,
    order_priority VARCHAR(20),
    order_quantity INT,
    sales DECIMAL(10,2),
    discount DECIMAL(5,2),
    ship_mode VARCHAR(30),
    profit DECIMAL(10,2),
    unit_price DECIMAL(10,2),
    shipping_cost DECIMAL(10,2),
    customer_name VARCHAR(100),
    province VARCHAR(100),
    region VARCHAR(50),
    customer_segment VARCHAR(50),
    product_category VARCHAR(50),
    product_sub_category VARCHAR(50),
    product_name VARCHAR(150)
);

``` USE KMS_database;

ALTER TABLE sales
ADD COLUMN product_container VARCHAR(50),
ADD COLUMN product_base_margin DECIMAL(5,2),
ADD COLUMN ship_date DATE;


![Screenshot (53)](https://github.com/user-attachments/assets/c28bf82a-45cb-4b3a-b8bb-480684efad6c)



![Screenshot (54)](https://github.com/user-attachments/assets/27c0bd12-4e0d-4fb8-84cb-3838432074a3)
