# MySQL_1 practice repository
Contains SQL scripts demonstrating typical operations such as table creation, data insertion, schema modifications, constraints, and renaming.

📂 Project Files contain
- create_tables.sql/ Data Definition Language
- insert_data.sql / DML & DQL
- alter_tables.sql / DML
- README.md

# 🚀 Getting Started
Prerequisites
- MySQL installed (v5.7 or later recommended)
- Access to a SQL client or command-line interface

# Execute the scripts in order:
**create_tables.sql**
- Defines the students table with columns like sid, name, city, and age.
- Defines the employee and employees tables with appropriate constraints such as PRIMARY KEY and UNIQUE


**insert_data.sql**
- Inserts example records into tables (e.g., students, employees):
- INSERT INTO students VALUES (1, 'Text', 'city', 20)
<img width="602" height="211" alt="Insert into student" src="https://github.com/user-attachments/assets/566b1977-6886-40f3-888b-ddeffd36b874" />

<img width="602" height="571" alt="Insert into employee-1" src="https://github.com/user-attachments/assets/edb75571-6c44-4f33-96e8-aae4bd2c943a" />

**alter_tables.sql**
- Demonstrates schema modifications such as:
- Adding/dropping columns
- Renaming tables and columns
- Modifying column attributes (e.g. NOT NULL)
<img width="390" height="566" alt="query_1" src="https://github.com/user-attachments/assets/3cbb27ec-8540-429e-9e3a-992ea489a40f" />

<img width="602" height="318" alt="query_2" src="https://github.com/user-attachments/assets/97c7bbeb-394a-4ca2-90d3-ca39a8f24973" />

<img width="580" height="284" alt="query_3" src="https://github.com/user-attachments/assets/68b16b4e-3801-4463-a166-bdb54d188d36" />

<img width="569" height="267" alt="query_4" src="https://github.com/user-attachments/assets/fd4e8021-a65a-425a-aecd-b5333f48937d" />

<img width="522" height="263" alt="query_5" src="https://github.com/user-attachments/assets/5e453bfe-7307-4360-bc9c-8f9829560bbd" />

# Questions solved using Queries

1.	Find all employees older than 35.
2.	Retrieve student names and total marks in all semesters.
3.	Get all employee names who work in Mumbai.
________________________________________
**📊 Aggregation-Based Questions**

4.	What is the average stipend of all students?
5.	Find the highest salary among employees.
6.	Get the average marks per semester.
7.	Get the average marks per semester of each student.
8.	Find the number of employees in each city.
________________________________________
**🔄 JOINs & Relational Thinking**

9.	Find matching students and employees in the same city.
________________________________________
**🧠 Advanced Interview-Style SQL Questions**

10.	Find students whose average marks across all semesters is above 500.
11.	Find employees with the second-highest salary.
12.	List top 3 students by total marks.
13.	Which departments (SubjectsHandled) have more than one employee?
14.	Which students have the same city as any employee qualified in MBA?
________________________________________
**🛠️ Data Manipulation & Update Tasks**

15.	Update all students' stipend to 15000 where city is 'Mumbai'.
16.	Insert a new employee into the table.
17.	Delete all students who scored less than 400 in any semester.
18.	Delete all students who scored less than 450 in any semester.
