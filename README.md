# 🎓 University Course Management System

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=26&pause=1000&color=36BCF7&center=true&vCenter=true&width=800&lines=UNIVERSITY+COURSE+MANAGEMENT+SYSTEM;Manage+Students%2C+Courses+%26+Enrollments;Powered+by+MySQL+8.0" alt="Animated Project Title"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Database-MySQL%208.0-blue?style=for-the-badge&logo=mysql"/>
  <img src="https://img.shields.io/badge/Language-SQL-orange?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Project-Completed-brightgreen?style=for-the-badge"/>
</p>

---

## 📌 Project Overview

The **University Course Management System** is a SQL-based database project developed using MySQL 8.0.

This project is designed to manage university information, including students, departments, courses, instructors, and enrollments.

It demonstrates practical SQL concepts such as database creation, CRUD operations, joins, subqueries, aggregate functions, date functions, string functions, and window functions.

## 🎯 Project Objectives

- Create and manage a university database.
- Store student and instructor information.
- Manage courses and departments.
- Perform CRUD operations.
- Retrieve data using SQL queries.
- Analyze records using joins and subqueries.
- Apply advanced SQL functions.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| MySQL 8.0 | Database Management |
| SQL | Data Manipulation |
| MySQL Workbench | Query Execution |

## 🗄️ Database Structure

**Database Name:** `UniversityCourseManagement`

The project contains five tables:

### 1. Departments
Stores department IDs and department names.

### 2. Students
Stores student information, including name, email, birth date, and enrollment date.

### 3. Courses
Stores course names, department IDs, and credit values.

### 4. Instructors
Stores instructor details, department information, email, and salary.

### 5. Enrollments
Stores student-course relationships and enrollment dates.

## ✨ Key Features

### 1. Database & Table Creation
- Create database.
- Create five related tables.
- Define Primary Keys and Foreign Keys.
- Apply UNIQUE, NOT NULL, DEFAULT, and CHECK constraints.

### 2. CRUD Operations
- CREATE – Insert records.
- READ – Retrieve records.
- UPDATE – Modify existing records.
- DELETE – Remove records.

### 3. Filtering & Sorting
- Retrieve students enrolled after 2022.
- Retrieve Mathematics department courses.
- Sort and limit query results.

### 4. Aggregate Functions
- COUNT()
- AVG()
- MAX()
- GROUP BY
- HAVING

### 5. JOIN Operations
- INNER JOIN
- LEFT JOIN

### 6. Subqueries
- Find students enrolled in both specified courses.
- Find students enrolled in either specified course.
- Find students enrolled in courses with more than 10 students.

### 7. Date Functions
- YEAR()
- CURDATE()
- DATE_SUB()

### 8. String Functions
- CONCAT()

### 9. Window Functions
- COUNT() OVER()
- Running Total of Enrollments.

### 10. Conditional Statements
- CASE statement.
- Classify students as Senior or Junior based on enrollment date.

## 📂 Project Structure

```text
University Course Management System/
│
├── UniversityCourseManagement.sql
│
└── README.md
```

## ▶️ How to Run the Project

1. Open MySQL Workbench.
2. Open a new SQL query tab.
3. Copy the SQL project code.
4. Paste the code into the editor.
5. Execute the complete SQL script.
6. Refresh the Schemas panel.
7. Select `UniversityCourseManagement`.
8. Execute individual SELECT queries to view results.

## 📊 Expected Output

The project generates results such as:

- Student records.
- Course details.
- Instructor information.
- Department-wise student counts.
- Students enrolled after 2022.
- Students enrolled in multiple courses.
- Average course credits.
- Maximum instructor salary.
- Running total of enrollments.
- Senior and Junior student categories.

## 📚 Learning Outcomes

Through this project, I learned:

- Relational Database Management.
- Database and table creation.
- Primary and Foreign Key relationships.
- CRUD operations.
- SQL JOIN operations.
- Subqueries and aggregate functions.
- Date and string functions.
- Window functions.
- Conditional statements using CASE.

## 🏁 Conclusion

The **University Course Management System** helped me understand how SQL is used to manage, organize, retrieve, and analyze university data.

This project provided practical experience with MySQL database management and different SQL operations.

---

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=2ECC71&center=true&vCenter=true&width=500&lines=THANK+YOU+FOR+VISITING!;Keep+Learning+Keep+Practising" alt="Animated Thank You"/>
</p>
