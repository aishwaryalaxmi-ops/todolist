# todolist
Java Swing and MySQL based Student Management System

## Features

- Add student details
- Store student information in MySQL
- Fetch student data
- Java Swing GUI
- MySQL database connectivity
- JDBC integration

## Technologies Used

- Java
- Java Swing
- JDBC
- MySQL
- MySQL Connector/J

## Student Information

The system stores:

- Name
- Registration Number
- Branch
- Age
- Sex

## Database Setup

Create the database:

```sql
CREATE DATABASE testb;

USE testb;

CREATE TABLE students (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(100),
    regno VARCHAR(50),
    branch VARCHAR(100),
    age INT,
    sex VARCHAR(20)
);
