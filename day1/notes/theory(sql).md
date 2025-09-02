# SQL Basics

## 📌 What I Learned Today
1. **SQL (Structured Query Language)** is used to communicate with relational databases.
2. Basic commands:
   - `CREATE TABLE` → To define a new table.
   - `INSERT INTO` → To add new rows.
   - `SELECT *` → To retrieve all data from a table.
   - `WHERE` clause → To filter records.
3. Example:
   ```sql
   CREATE TABLE Student (
       id INT,
       name VARCHAR(50),
       marks INT
   );

   INSERT INTO Student VALUES (1, 'Arun', 75);
   INSERT INTO Student VALUES (2, 'Meena', 90);

   SELECT * FROM Student WHERE marks > 50;
