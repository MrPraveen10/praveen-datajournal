---
title: Praveen's Data Science Journey
---

# Praveen's Data Science Journey

Welcome to my GitHub Pages site where I document my journey in data science.

## Sidebar Menu

- [Introduction to SQL](sql.html)
- [Machine Learning](ml.html)

---

## 01 Aug 2024: Introduction to SQL

SQL (Structured Query Language) is a powerful tool for managing and manipulating relational databases. It allows you to perform operations such as:

- **Selecting data**: Retrieving specific data from one or more tables.
- **Inserting data**: Adding new data into a database table.
- **Updating data**: Modifying existing data within a table.
- **Deleting data**: Removing data from a table.

### Basic SQL Commands

Here are some basic SQL commands:

- `SELECT`: Retrieves data from a database.
- `INSERT`: Adds new data to a database.
- `UPDATE`: Modifies existing data.
- `DELETE`: Removes data.

#### Example of a `SELECT` Statement

`SELECT first_name, last_name FROM employees WHERE department = 'Sales';`

In this post, I cover the basics of SQL, including how to select, insert, update, and delete data in a relational database.

---

## Machine Learning

Let’s break down **variance** and **bias** using a simple example of **throwing darts** at a target!

### **Variance:**

- **What It Means:** Variance is about how spread out your dart throws are from each other. 
- **Example:** Imagine you’re throwing darts at a target. If your darts are scattered all over the target (some on the bullseye, some far away), you have **high variance**. If your darts are all clustered together in one spot (maybe near the bullseye), you have **low variance**.

In other words, variance tells us how much the results (dart throws) differ from each other.

### **Bias:**

- **What It Means:** Bias is about how far off your average dart throw is from the bullseye.
- **Example:** If all your darts are consistently hitting the same spot but that spot is far from the bullseye, you have **high bias**. This means there’s a consistent error in your throws. If your average spot is close to the bullseye, you have **low bias**.

In other words, bias tells us how far off the average result (dart throws) is from the target (bullseye).

### **Putting It Together:**

- **Low Variance & Low Bias:** Your darts are all grouped closely together and near the bullseye.
- **High Variance & Low Bias:** Your darts are all over the place but the average spot is near the bullseye.
- **Low Variance & High Bias:** Your darts are closely grouped but all are away from the bullseye.
- **High Variance & High Bias:** Your darts are scattered all over the target and none are near the bullseye.

### **In Simple Terms:**

- **Variance:** How much your results (dart throws) differ from each other.
- **Bias:** How far off your average result (dart throws) is from the correct or ideal spot (bullseye).

**To summarize**: 
- **Variance** is about the spread of your results.
- **Bias** is about the accuracy of your average result.

Imagine you’re trying to be both accurate and consistent with your dart throws. Your goal is to have both low variance (consistent results) and low bias (accurate results)!
