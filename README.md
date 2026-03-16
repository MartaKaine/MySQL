## 🗄️ SQL Data Analysis Project (Bootcamp)

This project was completed during my **Data Technician Bootcamp** and focuses on analysing structured data using **SQL and relational databases**.

The project demonstrates how SQL queries can be used to **retrieve, filter, combine, and analyse data** to extract meaningful insights from business datasets such as **retail, customer, and global demographic data**.

---

## 📁 Project Overview

In this project, I worked with relational databases using **MySQL Workbench** to explore and analyse datasets.

Tasks included:

- Designing a relational database structure
- Writing SQL queries to retrieve and filter data
- Combining data from multiple tables using JOINs
- Aggregating data to produce business insights

The exercises simulate real-world tasks a **Data Technician or Junior Data Analyst** might perform when analysing company data.

---

## 🛠 SQL Skills Demonstrated

### Data Retrieval

Used SQL queries to extract specific information from database tables.

Key commands used:

- `SELECT` – retrieving columns from tables
- `DISTINCT` – identifying unique values
- `LIMIT` – controlling result size

Example:

```sql
SELECT CustomerName, City
FROM Customers;
```

---

### Filtering Data

Applied filtering conditions to focus on relevant subsets of data.

Key commands used:

- `WHERE`
- `BETWEEN`
- `LIKE`
- `IN`

Example:

```sql
SELECT *
FROM Products
WHERE Price BETWEEN 20 AND 50
ORDER BY Price DESC;
```

This allows analysts to quickly identify **specific products, customers, or records** within large datasets.

---

### Sorting Data

Used sorting to organise query results in a meaningful way.

Key command used:

- `ORDER BY`

Example:

```sql
SELECT *
FROM Orders
ORDER BY OrderDate DESC;
```

This is useful when identifying **recent activity, top performers, or trends over time**.

---

## 🔗 Working with Multiple Tables

A key part of relational databases is combining information stored across multiple tables.

### SQL JOINs Used

- `INNER JOIN`
- `LEFT JOIN`

Example:

```sql
SELECT ProductName, SupplierName
FROM Products
LEFT JOIN Suppliers
ON Products.SupplierID = Suppliers.SupplierID;
```

This allows analysts to connect related data such as:

- products and suppliers
- orders and customers
- categories and products

---

## 📊 Data Aggregation & Analysis

Used grouping and aggregation to generate insights from datasets.

Key commands used:

- `GROUP BY`
- `COUNT`
- `SUM`
- `AVG`

Example:

```sql
SELECT CategoryName, COUNT(ProductID)
FROM Categories
LEFT JOIN Products
ON Categories.CategoryID = Products.CategoryID
GROUP BY CategoryName;
```

This type of analysis helps answer business questions such as:

- How many products exist in each category?
- Which products are ordered most frequently?
- What is the average population of cities per country?

---

## 🌍 Example Analyses

Examples of insights explored during this project include:

- Identifying **high-value products** in a retail database
- Analysing **customer locations for marketing campaigns**
- Linking **products to suppliers and categories**
- Finding **cities with the highest populations**
- Comparing **global demographic data across countries**

These tasks demonstrate how SQL can be used to support **business reporting and decision-making**.

---

## 🗃 Database Concepts Applied

In addition to writing queries, the project also covered **relational database design**, including:

- Database normalisation
- Primary keys
- Foreign keys
- One-to-many relationships between tables

This ensures databases are **efficient, organised, and scalable**.

---

### Query Example
Screenshot showing:
- SQL query in **MySQL Workbench**
- Result table output

Example screenshot ideas:

- Customer data query results
- Product price filtering query
- JOIN query combining products and suppliers

#### Aggregation Query
Example showing:

- `GROUP BY` query
- Result table summarising categories or products

#### Database Exploration
Screenshot showing:

- Database schema or table structure
- Multiple related tables in MySQL Workbench

---

## 🚀 Why This Project Matters

SQL is one of the most important skills for **data analysts and data technicians**.

This project demonstrates my ability to:

- Query relational databases using SQL
- Filter and sort data efficiently
- Combine tables using JOINs
- Generate insights using aggregation and grouping

These are essential skills for **Data Technician and Junior Data Analyst roles**.

---

📁 **Repository Contents**

- SQL query files (`.sql`)
- Dataset files used during analysis
- Screenshots of SQL queries and results
