# University Management System: SQL Project

## Abstract

This project develops a **University Management System** using SQL and SQLite within Google Colab. The system manages academic and administrative data, including students, professors, courses, departments, library, clubs, scholarships, and attendance. By designing a normalized relational database schema and applying SQL queries, the project demonstrates efficient information retrieval and management.

Key steps included building an Entity-Relationship Diagram (ERD) to model university operations, implementing SQL tables with constraints, and populating them with sample data. Queries such as GPA calculation, scholarship eligibility, student-faculty mapping, and library usage analysis were executed. Advanced concepts like aggregation, joins, subqueries, and views were also used. The project highlights database design, query optimization, and practical applications of SQL in higher education systems.

---

## Introduction & Background

### University Data Management and SQL

Universities handle vast amounts of structured data, from course registrations to faculty assignments. A relational database provides an efficient way to organize and retrieve this data. SQL, as a declarative query language, is well-suited for tasks like student analytics, resource allocation, and decision support.

### Internship/Project Learning

This project was carried out as part of SQL practice in Google Colab, enabling seamless integration of Python for data visualization. It also served as hands-on training in schema design, normalization, and analytical querying.

---

## Problem Statement

### Challenges in University Data Management

* **Data Redundancy:** Risk of duplication without proper schema design.
* **Complex Relationships:** Many-to-many links between students, professors, and courses.
* **Efficient Querying:** Need for optimized queries to extract insights (e.g., top performers, active clubs).

---

## Database Schema Design (ERD)

The **ERD** was designed to represent real-world university operations:

* **Students** enrolled in multiple **Courses**.
* **Professors** teaching multiple **Courses**.
* **Departments** managing both students and faculty.
* **Library** records tracking book borrowing by students.
* **Clubs** and **Scholarships** linked to student participation and performance.
* **Attendance** monitoring classroom engagement.

The ERD ensures data normalization, integrity, and efficient query processing.



<img width="768" height="547" alt="university_erd" src="https://github.com/user-attachments/assets/e7b68fbf-63d3-4491-bba2-ebe43d9e9475" />

---

## Key Solutions Implemented

* **Schema Creation:** Normalized design with primary/foreign keys.
* **Data Insertion:** Populated realistic datasets.
* **Complex Queries:** GPA calculation, faculty-course mapping, scholarship filtering.
* **Views & Joins:** Simplified access to aggregated results.
* **Visualization:** SQL queries integrated with Python charts.

---

## How to Run

1. Open the Colab notebook.
2. Run the setup cell to create the SQLite database.
3. Execute schema creation and data insertion cells.
4. Run SQL queries to generate insights.
5. Visualize results using matplotlib in Colab.

---

## Future Work

* Implement stored procedures and triggers.
* Add student portal simulation with Flask/Django.
* Scale to MySQL/PostgreSQL for larger datasets.
