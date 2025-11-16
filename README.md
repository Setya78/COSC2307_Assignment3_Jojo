# COSC2307 – Assignment 3  
### Database Programming (Manufacturing Management System)

This repository contains the full SQL implementation for Assignment 3 of the COSC2307 Database Programming course.  
The project simulates a simple **manufacturing management system**, including clients, projects, machines, operators, and job orders.

---

## 📁 Repository Structure

01_create_database_and_tables.sql
02_insert_tables.sql
03_queries.sql
README.md


---

## 🧱 1. Database & Tables

The script **01_create_database_and_tables.sql** includes:

- Creation of database `manufacturing_db`
- Table structures:
  - **Clients**
  - **Projects**
  - **Machines**
  - **Operators**
  - **JobOrders**
- Primary keys, foreign keys, and indexes
- Clean and normalized schema for relational operations

---

## 📝 2. Insert Sample Data

The script **02_insert_tables.sql** includes:

- 25 sample clients  
- Example projects with deadlines and budgets  
- Machine list with availability and maintenance dates  
- Operators with specializations  
- Job orders linking projects, machines, and operators  

This dataset is designed to support realistic query outputs.

---

## 🔍 3. Query Collection (Section C)

The script **03_queries.sql** includes answers to Assignment Section C, such as:

- Listing operators and their job assignments  
- Projects with upcoming deadlines  
- Machines with completed job counts  
- Budget analysis queries  
- Identifying unavailable machines and maintenance dates  
- Aggregate and JOIN-based queries  

All queries are formatted, labeled, and ready for export or screenshot.

---

## ▶️ How to Use

1. Run **01_create_database_and_tables.sql** to set up the schema  
2. Run **02_insert_tables.sql** to populate sample data  
3. Run **03_queries.sql** to generate outputs for assignment submission  

Can be executed using MySQL Workbench or any MySQL-compatible environment.

---

## 📌 Notes

- The project uses MySQL 8 syntax  
- Boolean fields are stored as TINYINT(1)  
- Dates are provided as realistic sample manufacturing values  
- Indexes applied for optimized query performance  

---

## 👤 Author

**Jojo (Deny Setiawan Rahardjo)**  
Algoma University – COSC2307 Database Programming  
Assignment 3 — Manufacturing Management System

