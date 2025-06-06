# 🚀 SQL Case Study: Sales & Profit Analytics

As part of my hands-on practice with SQL, I worked on a comprehensive **Sales and Marketing Analytics case study** using three relational datasets to draw business insights for a fictional retail company. This exercise involved real-world use cases such as identifying top-performing products, analyzing marketing spends, and comparing profits across states.

---

## 🧠 Problem Statement

As a database analyst, my objective was to explore sales and profitability data across different states, products, and time periods. The goal was to extract actionable insights from sample customer data related to:

* Sales trends 📈
* Profit margins 💰
* Marketing expenditure 📣
* Inventory and budget analysis 📊

---

## 🗃️ Dataset Overview

Here are the three datasets I worked with:

| Table Name        | Description                                                                     |
| ----------------- | ------------------------------------------------------------------------------- |
| **FactTable**     | 4200 rows of metrics: `Date`, `ProductID`, `Profit`, `Sales`, `Marketing`, etc. |
| **ProductTable**  | 13 rows: maps `ProductID` to `Product`, `Type`, and `Product Type`.             |
| **LocationTable** | 156 rows: maps `Area Code` to `State`, `Market`, and `Market Size`.             |

---

## 📊 Interactive Tasks Checklist

Here’s a list of tasks performed using SQL queries. ✅ = Done

```markdown
- [x] Count unique states in LocationTable
- [x] Identify regular type products
- [x] Marketing spend for ProductID = 1
- [x] Minimum product sales
- [x] Maximum COGS
- [x] Products where type is 'Coffee'
- [x] Records with total expenses > 40
- [x] Avg. sales in area code 719
- [x] Total profit from Colorado
- [x] Avg. inventory per Product ID
- [x] State list in alphabetical order
- [x] Avg. budget where budget margin > 100
- [x] Sales on 2010-01-01
- [x] Avg. total expense by ProductID/date
- [x] Detailed joined table for selected columns
- [x] Sales-wise rank (dense)
- [x] State-wise profit and sales
- [x] State-wise sales/profit per product
- [x] Simulated 5% sales increase
- [x] ProductID & ProductType for max profit
- [x] Stored procedure: filter by Product Type
- [x] IF logic: Profit or Loss
- [x] Weekly sales with ROLLUP
- [x] UNION & INTERSECT on Area Code
- [x] UDF: fetch product type by input
- [x] UPDATE + ROLLBACK: Change Coffee to Tea
- [x] Sales with expenses between 100–200
- [x] DELETE records: Regular type
- [x] ASCII of 5th char in Product name
```

---

## 🧰 Tools & Techniques Used

* 🔄 **Joins**
* 🧮 **Aggregates (SUM, AVG, MAX, MIN)**
* 📌 **Subqueries & CTEs**
* 📊 **ROLLUP for hierarchical data**
* ⚙️ **Stored Procedures & Functions**
* 💾 **Transactions (UPDATE, DELETE, ROLLBACK)**

---


Want to try the queries yourself? Clone the repo, load the data into your SQL environment, and start exploring with the checklist above!

---

Have questions or suggestions? Open an issue on GitHub or connect with me on [LinkedIn](https://www.linkedin.com/in/rajvardhan-jadhav-858507245/).
