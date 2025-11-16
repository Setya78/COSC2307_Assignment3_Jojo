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

- QUERY 1: “List Operators and Their Current Job Assignments"
  ![Query 1 Output]  https://github.com/Setya78/COSC2307_Assignment3_Jojo/blob/main/query_1_List_Operators_and_Their_Current_Job_Assignments.png
  
- QUERY 2: “List All Projects and Their Client Names with Upcoming Deadlines”
  ![Query 2 Output] https://github.com/Setya78/COSC2307_Assignment3_Jojo/blob/main/query_2_List_All_Projects_and_Their_Client_Names_with_Upcoming_Deadlines.png
  
- QUERY 3: “Get the Number of Completed Job Orders for Each Machine”
  ![Query 3 Output] https://github.com/Setya78/COSC2307_Assignment3_Jojo/blob/main/query_3_Get_the_Number_of_Completed_Job_Orders_for_Each%20Machine_1.png
  https://github.com/Setya78/COSC2307_Assignment3_Jojo/blob/main/query_3_Get_the_Number_of_Completed_Job_Orders_for_Each%20Machine_2.png
  
- QUERY 4: “Identify Projects Exceeding a Budget of $20,000”
  ![Query 4 Output] https://github.com/Setya78/COSC2307_Assignment3_Jojo/blob/main/query_4_Identify_Projects_Exceeding_a_Budget_of_20000.png
  
- QUERY 5: “Calculate the Total Budget Allocated for All Projects”
  ![Query 5 Output] https://github.com/Setya78/COSC2307_Assignment3_Jojo/blob/main/query_5_Calculate_the_Total_Budget_Allocated_for_All_Projects.png
  
- QUERY 6: “Find Machines That Are Currently Not Available and their Last Maintenance Date”  
  ![Query 6 Output] https://github.com/Setya78/COSC2307_Assignment3_Jojo/blob/main/query_%206_Find%20_Machines_That_Are_Currently_Not_Available_and_their_Last_Maintenance_Date.png
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

