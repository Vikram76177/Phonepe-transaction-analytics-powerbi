
# Task 3 – SQL for Data Analysis (Updated Version)

## 📌 Overview
This task demonstrates SQL data analysis using a 500‑row ecommerce dataset.  
It covers everything given in the **Hints / Mini Guide**:
- SELECT, WHERE, ORDER BY, GROUP BY  
- JOINS (INNER, LEFT, RIGHT)  
- Subqueries  
- Aggregate functions (SUM, AVG, COUNT)  
- Views for analysis  
- Query optimization using indexes  

---

## 📁 Files Included
- **task3_queries.sql** — complete SQL queries for the task  
- **ecommerce_dataset_500_rows.csv** — the dataset  
- **README.md** — documentation for GitHub submission  

---

## 🛠 Recommended Tools
- DB Browser for SQLite (Free & easy)
- MySQL Workbench
- PGAdmin (PostgreSQL)
- VS Code SQLite Plugin

---

## 🚀 Steps to Execute
1. Import the CSV file into a database table named **orders**.
2. Run queries from `task3_queries.sql` one by one.
3. Capture screenshots of outputs (as required in assignment).
4. Upload everything to a new GitHub repository:
   - Dataset  
   - SQL file  
   - Screenshots folder  
   - README.md  

---

## 📚 What’s Inside task3_queries.sql?

### ✔ SELECT, WHERE, ORDER BY  
Basic filtering and sorting queries.

### ✔ GROUP BY  
Revenue grouped by country.

### ✔ JOINS  
INNER, LEFT, RIGHT (or RIGHT emulation in SQLite).

### ✔ SUBQUERIES  
- Orders above average  
- Users above average spending  

### ✔ Aggregations  
SUM, AVG, COUNT, MAX.

### ✔ Views  
Monthly revenue view.

### ✔ Index optimization  
Indexes on:
- user_id  
- order_date  
- country  

---

## 📝 Notes
- SQLite uses `strftime()` for date formatting  
- MySQL may require `DATE_FORMAT()`  
- SQLite doesn’t support RIGHT JOIN — we used LEFT JOIN reverse method  

---

## 🎯 Final Deliverables for Submission
| File | Description |
|------|-------------|
| **task3_queries.sql** | All SQL queries for the task |
| **ecommerce_dataset_500_rows.csv** | Your dataset |
| **README.md** | Explanation + instructions |
| **screenshots/** | Folder with query output screenshots |

---

If you need ZIP packaging or screenshots template, let me know!
