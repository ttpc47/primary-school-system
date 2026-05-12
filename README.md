# Web-Based Primary School Enrollment and Academic Management System

A beginner-friendly academic web application developed using **HTML, CSS, JavaScript, PHP, and MySQL** for managing primary school enrollment, student records, academic results, and school fee payments.

This project is designed for students learning:

- CRUD Operations
- Frontend Development
- Backend Development
- Database Management
- Authentication Systems
- Software Engineering Fundamentals

The application runs completely offline using:

- XAMPP
- WAMP

---

# Project Objectives

This project aims to teach students how to:

- Build a complete web application from scratch
- Design and manage relational databases
- Implement CRUD operations
- Create responsive user interfaces
- Handle authentication and authorization
- Connect frontend and backend systems
- Generate academic reports
- Organize software projects professionally

---

# System Features

## Administrator Features

The administrator can:

- Register students
- Edit student records
- Delete student records
- Manage teachers
- Manage classes
- Manage subjects
- Record school fee payments
- Print receipts
- View reports
- Manage system users

---

## Teacher Features

Teachers can:

- Login securely
- Enter student marks
- Edit marks
- Calculate totals and averages
- Generate report cards
- View student academic records

---

# Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Page structure |
| CSS3 | Styling and layout |
| JavaScript | Frontend interactivity |
| PHP | Backend development |
| MySQL | Database management |
| Apache | Local web server |

---

# Project Structure

```text
primary-school-system/
│
├── admin/
├── teacher/
├── actions/
├── auth/
├── config/
├── css/
├── js/
├── includes/
├── database/
├── reports/
├── images/
│
├── index.php
├── login.php
└── README.md
```

---

# Folder Descriptions

| Folder | Purpose |
|---|---|
| admin | Administrator pages |
| teacher | Teacher pages |
| actions | CRUD processing scripts |
| auth | Login/logout/session files |
| config | Database connection |
| css | Stylesheets |
| js | JavaScript files |
| includes | Shared reusable components |
| database | SQL database files |
| reports | Report generation pages |
| images | System images/icons |

---

# System Modules

The system contains the following major modules:

| Module | Description |
|---|---|
| Authentication Module | Login/logout and session management |
| Student Management | Student CRUD operations |
| Teacher Management | Teacher CRUD operations |
| Class Management | Manage school classes |
| Subject Management | Manage school subjects |
| Marks Management | Record and manage results |
| Payment Management | School fee payment tracking |
| Reporting Module | Generate reports and report cards |

---

# Database Name

```sql
primary_school
```

---

# Main Database Tables

| Table | Purpose |
|---|---|
| users | Authentication accounts |
| students | Student records |
| teachers | Teacher records |
| classes | School classes |
| subjects | Subject information |
| marks | Student results |
| payments | Fee payment records |

---

# Installation Guide

## Step 1 — Install XAMPP/WAMP

Install one of the following:

- XAMPP
- WampServer

---

## Step 2 — Copy Project Folder

Copy the project folder into:

### XAMPP

```text
C:\xampp\htdocs\
```

### WAMP

```text
C:\wamp64\www\
```

---

## Step 3 — Start Apache and MySQL

Open:

- Apache
- MySQL

from the XAMPP/WAMP control panel.

---

## Step 4 — Create Database

Open:

```text
http://localhost/phpmyadmin
```

Create database:

```sql
CREATE DATABASE primary_school;
```

---

## Step 5 — Import SQL File

Import:

```text
database/primary_school.sql
```

---

## Step 6 — Configure Database Connection

Edit:

```text
config/database.php
```

Example:

```php
<?php

$host = "localhost";
$username = "root";
$password = "";
$database = "primary_school";

$conn = mysqli_connect(
    $host,
    $username,
    $password,
    $database
);

?>
```

---

## Step 7 — Run the Project

Open browser:

```text
http://localhost/primary-school-system
```

---

# Default Login Example

## Administrator

| Username | Password |
|---|---|
| admin | admin123 |

---

## Teacher

| Username | Password |
|---|---|
| teacher1 | teacher123 |

---

# Recommended Development Workflow

Students should build the system in this order:

| Phase | Task |
|---|---|
| 1 | Database setup |
| 2 | Authentication system |
| 3 | Student CRUD |
| 4 | Teacher CRUD |
| 5 | Class management |
| 6 | Subject management |
| 7 | Marks management |
| 8 | Payment system |
| 9 | Report generation |
| 10 | Testing and polishing |

---

# Educational Concepts Covered

This project teaches:

- HTML forms
- CSS layouts
- Responsive design
- JavaScript validation
- DOM manipulation
- PHP form processing
- Sessions and authentication
- MySQL CRUD operations
- Prepared statements
- Database relationships
- Software modularization

---

# Security Features

The system includes beginner-level security practices:

- Password hashing
- Session management
- Input validation
- Input sanitization
- Prepared SQL statements
- Role-based access control

---

# Responsive Design

The frontend is designed to work on:

- Desktop computers
- Tablets
- Small laptop screens

Using:

- Flexbox
- CSS Grid
- Media queries

---

# Sample CRUD Workflow

```text
User fills form
        ↓
PHP receives data
        ↓
Validation performed
        ↓
Data saved into MySQL
        ↓
Updated records displayed
```

---

# Academic Purpose

This project is intended for:

- Software Engineering students
- Computer Science students
- Web Development learners
- Database Systems learners
- Academic CRUD practice

It is suitable for:

- Final-year projects
- Semester projects
- Mini-projects
- Practical laboratory sessions

---

# Future Improvements

Possible future extensions include:

- Attendance management
- SMS notifications
- Parent portal
- Online deployment
- Mobile application
- Timetable management
- PDF report export
- AJAX-based updates

---

# Common Beginner Mistakes

| Mistake | Solution |
|---|---|
| Mixing HTML and PHP excessively | Separate logic clearly |
| No validation | Validate all inputs |
| Using plain passwords | Use hashing |
| Poor file organization | Follow folder structure |
| No session protection | Protect restricted pages |

---

# Recommended Coding Standards

Students should:

- Use meaningful variable names
- Comment important code sections
- Indent code properly
- Separate CSS and JavaScript files
- Reuse components using includes
- Keep functions simple and readable

---

# Learning Outcomes

After completing this project, students should be able to:

- Build a complete PHP/MySQL application
- Implement CRUD systems
- Create responsive interfaces
- Design relational databases
- Manage authentication systems
- Organize software projects professionally
- Apply foundational software engineering principles

---

# Author Notes

This project was intentionally designed to remain:

- Beginner-friendly
- Educational
- Modular
- Expandable
- Framework-free

The goal is to help students understand the fundamentals of full-stack web development before moving to advanced technologies such as:

- Laravel
- REST APIs
- React
- Node.js
- Cloud deployment

---

# License

This project is intended for:

- Educational purposes
- Academic learning
- Software engineering training
- Classroom demonstrations

Free to modify and extend for learning purposes."# primary-school-system" 
