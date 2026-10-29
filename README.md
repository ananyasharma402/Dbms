# DBMS Query Practice

## About
This repository contains basic SQL queries practiced as part of learning Database Management Systems (DBMS). It includes common operations performed on tables using SQL.

## Topics Covered
- Creating a database and tables
- Inserting records into tables
- Displaying table data
- Updating records
- Deleting records
- Filtering data using `WHERE`
- Sorting data using `ORDER BY`
- Removing duplicates using `DISTINCT`
- Using aggregate functions such as `COUNT()`, `SUM()`, `AVG()`, `MIN()`, and `MAX()`
- Altering and dropping tables

## Sample Queries

### 1. Create a Table
```sql
CREATE TABLE Student (
    id INT PRIMARY KEY,
    name VARCHAR(50),
    age INT,
    marks INT
);
```

### 2. Insert Records
```sql
INSERT INTO Student VALUES
(1, 'Ananya', 20, 85),
(2, 'Rahul', 21, 78),
(3, 'Priya', 19, 92);
```

### 3. Display All Records
```sql
SELECT * FROM Student;
```

### 4. Filter Records
```sql
SELECT * FROM Student
WHERE marks > 80;
```

### 5. Update Records
```sql
UPDATE Student
SET marks = 90
WHERE id = 1;
```

### 6. Delete Records
```sql
DELETE FROM Student
WHERE id = 2;
```

### 7. Sort Records
```sql
SELECT * FROM Student
ORDER BY marks DESC;
```

### 8. Count Records
```sql
SELECT COUNT(*) FROM Student;
```

## Tools Used
- SQL
- MySQL

## Purpose
To practice basic SQL queries, understand table operations, and improve database querying skills.

## Author
Ananya Sharma

---
This repository will be updated regularly with more SQL practice questions and solutions.
