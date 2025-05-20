# 📚SQL-Project-Liabrary_Management_System_Analysis

![library](https://github.com/user-attachments/assets/f229b751-b489-4861-bdb9-9f71a7e87680)


This project is a **SQL-based Library Management System** designed to manage and query a fictional library's database. It includes core datasets like books, branches, employees, members, issued statuses, and return records. The project features both basic and advanced SQL queries to answer a range of real-world data problems.

🗂️ **Project Structure :**

The following CSV files were used to build and query the database:

books.csv — Details of books in the library

branches.csv — Information about library branches

employees.csv — Staff information

members.csv — Library members data

issued_status.csv — Track of issued books

return.csv — Track of returned books

🛠️ **Features :**

📌 Database schema design using real-world library structure

📊 Data ingestion from CSV files

🧾 Basic SQL Queries:

Fetching records

Filtering and sorting

Simple joins

🧠 **Advanced SQL Queries :**

Complex joins

Aggregation and grouping

Subqueries and nested logic

Date-based analysis

🧪 **Sample Queries Solved**

Which members have issued the most books?

What is the return rate by branch?

Which employee has issued the most books?

List overdue returns with member names

Books not issued in the last 3 months

All queries are provided in a structured format within the SQL script or notebook files.


📁 **Folder Structure**

pgsql

Copy

Edit

📦library-management-sql/

 ┣ 📄 README.md
 ┣ 📁 data/
 ┃ ┣ 📄 books.csv
 ┃ ┣ 📄 branches.csv
 ┃ ┣ 📄 employees.csv
 ┃ ┣ 📄 members.csv
 ┃ ┣ 📄 issued_status.csv
 ┃ ┗ 📄 return.csv
 ┗ 📁 queries/
   ┣ 📄 basic_queries.sql
   ┗ 📄 advanced_queries.sql
   
📌 **Future Improvements**

Add stored procedures and views

Create a front-end for query interaction

Add constraints and indexes for optimization
