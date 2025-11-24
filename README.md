# SQL Exercise 1

Sample data is given in data.txt file. You should execute sql code in database management system.

## Examples:

### 1. Find all customers from New York.

`SELECT *
FROM Customers
WHERE city = 'New York';`

### 2. List all electronics products, ordered by price in descending order.

`SELECT *
FROM Products
WHERE category = 'Electronics'
ORDER BY price DESC;`

### 3. Count the total number of customers.

`SELECT COUNT(*) AS total_customers
FROM Customers;`

---

## Exercises:   

1. Show all customers who live in “Chicago”.

2. List all products that cost less than 50.

3. Count how many products are in the “Clothing” category.

4. Find the total revenue (sum of total_price) from all sales.

5. Find all sales where total_price is more than 200.

6. Find the number of sales made after March 1, 2024.

7. Find all sales where the quantity is more than 3.

### 8. Find the total number of items sold.

---



 
