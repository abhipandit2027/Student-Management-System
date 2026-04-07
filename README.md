# Student Management System
### Advanced Java Desktop Application

**Developed by:** Abhishek Tiwari  
**Registration Number:** 24BCE11220

---

## Project Overview

The **Student Management System** is a desktop-based application developed using **Advanced Java concepts**. It enables users to manage student records efficiently through a modern, intuitive graphical user interface.

This project demonstrates real-world implementation of:

- Java GUI (Swing)
- JDBC (Database Connectivity)
- MySQL Integration
- Object-Oriented Programming Principles

---

## Features

- Add new student records
- View all students in a structured table format
- Update existing student details
- Delete student records
- Auto-refresh table after every operation
- Modern and user-friendly GUI design
- **Automatic database & table creation — no manual setup required**

---

## Technologies Used

| Technology | Purpose |
|---|---|
| Java (JDK 8+) | Core application logic |
| Swing | Graphical User Interface |
| JDBC API | Database connectivity |
| MySQL | Backend data storage |
| MySQL Connector JAR | JDBC driver for MySQL |

## Project Structure
StudentManagementSystem/
│
├── lib/
│   └── mysql-connector-j-9.6.0.jar
│
├── src/
│   ├── Main.java
│   ├── GUI.java
│   ├── Student.java
│   ├── StudentDAO.java
│   └── DBConnection.java
│
├── .gitignore
└── README.md
---

## Setup Instructions

### Prerequisites

- Java JDK 8 or higher
- MySQL Server

### Running the Project — No Database Setup Needed!

There is **no need to manually create a database or table.**  
On first launch, the application automatically:

- Creates the `studentdb` database
- Creates the `students` table

### Compile the Project
```bash
javac -cp ".;lib/mysql-connector-j-9.6.0.jar" src/*.java
```

### Run the Project
```bash
java -cp ".;lib/mysql-connector-j-9.6.0.jar;src" Main
```

---

## Application Interface

### Input Fields

- Name
- Course
- Registration Number
- Email

### Functional Buttons

| Button | Action |
|---|---|
| Add | Inserts a new student record |
| Update | Modifies an existing record |
| Delete | Removes a selected record |

### Table View

Displays all student records dynamically, with automatic refresh after every operation.

---

## Future Enhancements

- Search and filter functionality
- Login and authentication system
- Export data to CSV or PDF
- UI upgrade using JavaFX

---

## Author

**Abhishek Tiwari**  
Registration No: `24BCE11220`  
B.Tech – Computer Science and Engineering

---

## Project Structure
