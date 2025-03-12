# SQL-Based Data Analysis Project

## Overview

This project demonstrates end-to-end **Data Analysis** using **SQL** on an **Oracle Database 21c** environment. It includes **DDL**, **DML**, and **DQL** operations on a simulated **Employee-Department** dataset. The analysis focuses on extracting actionable insights from data through query-based manipulation and exploration techniques. This project can serve as a great reference for beginners and intermediates working on database management, data retrieval, and data pipeline development using SQL.

---

## Table of Contents

- [Project Description](#project-description)
- [Installation & Setup](#installation--setup)
- [Solution Methodology](#solution-methodology)
- [Key Features](#key-features)
- [SQL Commands Covered](#sql-commands-covered)
- [Project Folder Structure](#project-folder-structure)
- [Author](#author)

---

## Project Description

The **Data Analysis Project** focuses on understanding datasets through SQL queries by performing various **CRUD (Create, Read, Update, Delete)** operations. We utilize **Oracle SQL Developer** and **Oracle Database 21c** for executing all the queries.

The agenda includes:
- Creating databases and tables.
- Populating datasets using **DML** operations.
- Retrieving data based on specific conditions.
- Handling NULLs, sorting, and filtering using complex nested queries.
- Backing up data and implementing transaction control using **COMMIT** and **ROLLBACK**.
- Conducting exploratory data analysis (EDA) via SQL.

---

## Installation & Setup

1. Download and install **Oracle Database 21c** from the official Oracle website.
2. Launch the installer and follow these steps:
   - Accept terms and conditions.
   - Provide a destination folder.
   - Set a password for the `SYSTEM` user.
   - Complete the installation.
3. Download and install **SQL Developer**.
4. Connect to the Oracle Database via SQL Developer:
   - Enter connection details (hostname, port, SID/Service, username, password).
   - Establish a successful connection to the `SYSTEM` user.

_For MAC users:_ Oracle Database isn't supported. Use the provided labs or a Windows virtual machine.

---

## Solution Methodology

The methodology applied in this project follows the **Data Pipeline** approach:
1. **Data Extraction**: SQL queries are used to extract employee and department data.
2. **Data Transformation**: Apply DML operations to manipulate data (INSERT, UPDATE, DELETE).
3. **Data Loading**: Perform data loading into Oracle Database tables.
4. **Data Analysis**:
   - Display records based on conditions and sort them accordingly.
   - Handle NULL values efficiently.
   - Implement pattern searching using `LIKE`, wildcards, and logical operators.
   - Backup tables and use **transaction control** commands.
   - Execute complex nested queries for deeper insights.

---

## Key Features

✔️ Creation of database schemas using **DDL**  
✔️ Data manipulation and retrieval using **DML** and **DQL**  
✔️ Handling complex queries with nested conditions  
✔️ Transaction control using **COMMIT** and **ROLLBACK**  
✔️ Backup management and recovery operations  
✔️ Extensive use of SQL Developer shortcuts for efficiency  
✔️ Best practices in **SQL query optimization**

---

## SQL Commands Covered

- **DDL (Data Definition Language)**:
  - `CREATE`, `ALTER`, `DROP`
- **DML (Data Manipulation Language)**:
  - `INSERT`, `UPDATE`, `DELETE`
- **DQL (Data Query Language)**:
  - `SELECT`, `WHERE`, `ORDER BY`, `GROUP BY`, `HAVING`
- **Transaction Control**:
  - `COMMIT`, `ROLLBACK`
- **Advanced Queries**:
  - Complex nested queries  
  - Handling `NULL` values  
  - Pattern matching with `LIKE` and wildcards  
  - Joins and subqueries  
  - Backup and data restoration operations

---

## Project Folder Structure

```
📂 SQL-Data-Analysis-Project
├── 📁 Installation & Execution
├── 📁 Codes
│   ├── Data_Analysis_Part_1.sql
│   ├── Data_Analysis_Part_2.sql
│   └── DDL.sql
├── 📄 Notes.pdf
├── 📄 Oracle_Database_Setup_v1.docx
├── 📄 Solution Methodology - 1.pdf
└── 📄 README.md
```

---

## Author

👨‍💻 **Lakshmipathiraju Pericharla**  
📅 Date: **March 11, 2025**

---
