-- Create the sales database (if it doesn't already exist)
CREATE DATABASE IF NOT EXISTS sales;

-- Switch to the sales database
USE sales;

-- Create the orders table
CREATE TABLE IF NOT EXISTS orders (
  order_id INT,
  customer_id INT,
  order_date DATE,
  order_total DECIMAL(10, 2),
  PRIMARY KEY (order_id)
);
