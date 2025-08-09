# 📊 SQL Basics – SELECT Queries & Filtering Guide

This repository contains a concise guide for **SQL SELECT statements**, filtering, and sorting data.  
It also includes interview-style questions, task instructions, and guidelines for completing SQL basics assignments.

---

## 📌 What's Inside
- **Mini Guide / Hints**
- **Key Concepts**: Filtering, Projection
- **Interview Questions**
- **Task 3: Writing Basic SELECT Queries**
- **Submission Guidelines**
- Example SQL queries

---

## 📝 Mini Guide
- Use `SELECT *` and specific columns
- Apply `WHERE`, `AND`, `OR`, `LIKE`, `BETWEEN`
- Sort results with `ORDER BY`

---

## 🎯 Outcome
Clear understanding of how to retrieve data from one or more SQL tables.

---

## 💬 Interview Questions
1. What does `SELECT *` do?
2. How do you filter rows?
3. What is `LIKE '%value%'`?
4. What is `BETWEEN` used for?
5. How do you limit output rows?
6. Difference between `=` and `IN`
7. How to sort in descending order?
8. What is aliasing?
9. Explain `DISTINCT`.
10. What is the default sort order?

---

## 🛠 Task 3: Writing Basic SELECT Queries
**Objective:** Extract data from one or more tables.

**Tools:**  
- DB Browser for SQLite  
- MySQL Workbench

**Deliverables:**  
- SQL script with `SELECT`, `WHERE`, `ORDER BY`, `LIMIT`

---

## 📚 Example Queries
```sql
-- Select all columns
SELECT * FROM employees;

-- Select specific columns
SELECT first_name, last_name FROM employees;

-- Filtering with WHERE
SELECT * FROM employees WHERE department = 'IT';

-- LIKE for pattern matching
SELECT * FROM employees WHERE first_name LIKE 'A%';

-- BETWEEN for range filtering
SELECT * FROM products WHERE price BETWEEN 100 AND 500;

-- Sorting results
SELECT * FROM orders ORDER BY order_date DESC;

-- Limiting rows
SELECT * FROM customers LIMIT 5;
