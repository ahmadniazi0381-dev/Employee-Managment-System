# 🏢 Employee Management System (EMS)

![Java](https://img.shields.io/badge/Java-JDK%2017%2F21-orange?style=for-the-badge\&logo=openjdk)
![Java Swing](https://img.shields.io/badge/Java%20Swing-GUI-blue?style=for-the-badge)
![MySQL](https://img.shields.io/badge/MySQL-8.x-4479A1?style=for-the-badge\&logo=mysql\&logoColor=white)
![JDBC](https://img.shields.io/badge/JDBC-Database-red?style=for-the-badge)
![Maven](https://img.shields.io/badge/Maven-Build-C71A36?style=for-the-badge\&logo=apachemaven\&logoColor=white)
![MIT License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

---

A desktop-based **Human Resource Management System** developed using **Java Swing, JDBC, and MySQL**. The application provides a centralized platform for managing employee information, departments, authentication, reports, and organizational data through an intuitive graphical user interface.

---

## 👨‍💻 Author

**Muhammad Ahmad Khan Niazi**

BS Software Engineering
University of Central Punjab (UCP)

GitHub: https://github.com/ahmadniazi0381-dev

---

## 🚀 Quick Links

* Features
* Technology Stack
* Project Structure
* Installation
* Database
* User Authentication
* Reports
* License

---

## 📚 Table of Contents

* Features
* Technology Stack
* Architecture
* Project Structure
* Installation
* Database
* Reports
* Screenshots
* License

---

## ✨ Features

* Secure Login & Authentication
* Employee CRUD Operations
* Department Management
* Advanced Employee Search
* Dashboard with Statistics
* Department-wise Reports
* Salary Reports
* Input Validation
* Exception Handling
* JDBC Database Connectivity
* Modular OOP Architecture

---

## 🛠 Technology Stack

| Category        | Technology       |
| --------------- | ---------------- |
| Language        | Java (JDK 17/21) |
| GUI             | Java Swing       |
| Database        | MySQL 8.x        |
| Connectivity    | JDBC             |
| Build Tool      | Maven            |
| Version Control | Git & GitHub     |

---

## 🏗 Architecture

The application follows a layered architecture based on Object-Oriented Programming principles.

### Layers

* UI Layer
* Model Layer
* DAO Layer
* Utility Layer
* Database Layer

This architecture separates presentation, business logic, and database operations, making the project easier to maintain and extend.

---

## 📂 Project Structure

```text
EmployeeManagementSystem/
│
├── src/
│   ├── database/
│   ├── model/
│   ├── util/
│   ├── ui/
│   └── Main.java
│
├── pom.xml
├── README.md
└── employee_management.sql
```

---

## 🚀 Installation

### Requirements

* Java JDK 17 or 21
* MySQL 8.x
* Maven
* Git

### Clone Repository

```bash
git clone https://github.com/ahmadniazi0381-dev/Employee-Managment-System.git
```

### Open Project

Import the project into your preferred Java IDE (IntelliJ IDEA, Eclipse, or VS Code).

### Configure Database

1. Create a MySQL database.
2. Import the provided SQL file.
3. Update the database credentials in the project configuration.

### Build

```bash
mvn clean install
```

### Run

Execute the `Main.java` file.

---

## 🗄 Database

The system uses **MySQL** for persistent storage.

Main entities include:

* Employees
* Departments
* Users
* Authentication

The database is accessed using **JDBC Prepared Statements** for improved security and protection against SQL injection.

---

## 📊 Reports

The system provides:

* Employee List
* Department-wise Reports
* Salary Reports
* Dashboard Statistics

---

## 🔒 Authentication

The application includes a login system that authenticates users before allowing access to the Employee Management Dashboard.

---

## 📸 Screenshots

Screenshots will be added in a future update.

---

## 📄 License

This project is licensed under the MIT License.

See the `LICENSE` file for details.

---

## 🎓 Academic Information

This project was developed as a semester project for the **Software Construction & Development** course at the **University of Central Punjab (UCP)**.

The project demonstrates practical implementation of:

* Object-Oriented Programming
* Java Swing GUI Development
* Database Management
* JDBC Connectivity
* Software Engineering Principles
* CRUD Operations
* Layered Software Architecture
