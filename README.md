# SQL-TASK-7-
#  SQL Internship – Task 7: Creating Views

## Objective
To understand and implement SQL Views for reusable logic, security, and abstraction in database systems.

---

##  Tools Used
- **DB Browser for SQLite**
- **MySQL Workbench**

---

##  Dataset
Two tables were created:

### 1. `products`
Contains product details like name, category, price, and stock.

### 2. `orders`
Contains customer orders with product references, quantity, and date.

Both tables have **15 rows each**, simulating a realistic e-commerce system.

---

## Key Concepts Practiced
- `CREATE VIEW` with complex joins
- Using views to simplify SELECT queries
- Calculating derived columns (e.g., `total_cost`)
- Filtering inside views (`WHERE`, `JOIN`)
- Creating summarized views (`GROUP BY`)
- Dropping views using `DROP VIEW`

---

##  Views Implemented
1. **order_summary** – Combines product and order info including total cost.
2. **high_value_orders** – Shows orders where total cost exceeds ₹10,000.
3. **product_sales** – Aggregated quantity sold by each product.

---

##  Outcome
- Reusable and simplified query structure  
- Better abstraction and security in SQL development  
- Ability to create both **simple** and **aggregate** views

---



