# 🛒 Zepto SQL Mini Project

## 📌 Project Overview

This project is a **SQL mini project** based on a dataset inspired by **Zepto (Quick Commerce)**. The goal of the project is to design a structured database and perform **basic data exploration queries** to understand product availability, pricing, discounts, and stock status.

The project demonstrates **database design, table creation, and exploratory SQL queries**, making it suitable for beginners and students learning SQL.

---

## 🗂️ Database Details

* **Database/Table Name:** `zepto`
* **Database Type:** Relational Database (SQL)
* **Project Type:** SQL Mini Project / Data Exploration

---

## 📊 Table Schema

The project consists of a single table named **`zepto`** with the following columns:

| Column Name              | Data Type            | Description                 |
| ------------------------ | -------------------- | --------------------------- |
| `sku_id`                 | SERIAL (Primary Key) | Unique product identifier   |
| `category`               | VARCHAR(120)         | Product category            |
| `name`                   | VARCHAR(150)         | Product name                |
| `mrp`                    | NUMERIC(8,2)         | Maximum Retail Price        |
| `discountPercent`        | NUMERIC(5,2)         | Discount percentage         |
| `availableQuantity`      | INTEGER              | Quantity available in stock |
| `discountedSellingPrice` | NUMERIC(8,2)         | Price after discount        |
| `weightInGms`            | INTEGER              | Product weight in grams     |
| `outOfStock`             | BOOLEAN              | Stock availability status   |
| `quantity`               | INTEGER              | Quantity per product unit   |

---

## 🛠️ SQL Features Used

* `CREATE TABLE`
* `DROP TABLE IF EXISTS`
* `PRIMARY KEY`
* `SERIAL`
* Data types: `VARCHAR`, `NUMERIC`, `INTEGER`, `BOOLEAN`
* Aggregate function: `COUNT()`

---

## 🔍 Queries Implemented

### 1️⃣ Data Exploration

* Count total number of records in the table

```sql
SELECT COUNT(*) FROM zepto;
```

This query helps in understanding the size of the dataset.

---

## 🎯 Learning Objectives

* Understand **table creation and schema design**
* Practice **data types and constraints**
* Perform **basic data exploration** using SQL
* Learn how real-world e-commerce data can be structured


---

## 📌 Use Cases

* SQL practice for beginners
* Mini project for college submissions
* Understanding e-commerce product data
* Interview preparation for SQL basics

