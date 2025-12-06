# Student Management System

This is a Java console-based Student Management System that performs CRUD (Create, Read, Update, Delete) operations on student records stored in a MySQL database.

## Features

- Add new students with name, age, and email  
- View all students in the database  
- Update existing student records  
- Delete student records  
- Menu-driven console interface  

## Project Structure

- `StudentDAO.java` — Handles all database operations using JDBC  
- `Main.java` — Provides a console menu for user interaction  
- Database: MySQL with a table `students` (id, name, age, email)  

## How to Run

1. Make sure MySQL is installed and running.  
2. Create a database named `StudentDB` and a table `students`:

```sql
CREATE TABLE students (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(50),
    age INT,
    email VARCHAR(50)
);
