# 🚀 Employee Management System

![Java](https://img.shields.io/badge/Java-17-orange)
![Spring Boot](https://img.shields.io/badge/SpringBoot-3.x-green)
![MySQL](https://img.shields.io/badge/MySQL-Database-blue)
![Maven](https://img.shields.io/badge/Maven-Build-red)
![License](https://img.shields.io/badge/License-MIT-yellow)

A **Spring Boot REST API project** that allows organizations to manage employee records efficiently.
This system provides APIs to **create, retrieve, and delete employee data** using a **MySQL database**.

The project demonstrates **backend development skills including REST API design, database integration, and API testing**.

---

# 📌 Features

✔ Add new employee records
✔ View all employees
✔ Retrieve employee details by ID
✔ Delete employee records
✔ RESTful API architecture
✔ MySQL database integration
✔ Swagger API documentation
✔ API testing using Postman

---

# 🛠️ Tech Stack

Backend
• Java
• Spring Boot
• Spring Data JPA
• Hibernate

Database
• MySQL

Tools
• Maven
• Postman
• Git & GitHub
• IntelliJ IDEA

---

# 📂 Project Structure

employee-management-system

src/main/java/com/example/employeemanagement

controller
EmployeeController.java

entity
Employee.java

repository
EmployeeRepository.java

EmployeeManagementApplication.java

src/main/resources
application.properties

pom.xml

---

# ⚙️ Installation & Setup

## 1️⃣ Clone the Repository

git clone https://github.com/rajgaurav07/employee-management-system.git

cd employee-management-system

---

## 2️⃣ Configure Database

Update **application.properties**

spring.datasource.url=jdbc:mysql://localhost:3306/employee_db
spring.datasource.username=root
spring.datasource.password=yourpassword

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true

---

## 3️⃣ Run the Application

Run the main class:

EmployeeManagementApplication.java

Application will start on:

http://localhost:8081

---

# 🌐 API Endpoints

### 🔹 Get All Employees

GET /employees

---

### 🔹 Get Employee By ID

GET /employees/{id}

Example

GET /employees/1

---

### 🔹 Add Employee

POST /employees

Example JSON

{
"name": "Raj Gaurav",
"email": "[rajgaurav@gmail.com](mailto:rajgaurav@gmail.com)",
"department": "IT"
}

---

### 🔹 Delete Employee

DELETE /employees/{id}

Example

DELETE /employees/1

---

# 📄 Swagger API Documentation

Access API documentation at:

http://localhost:8081/swagger-ui/index.html

Swagger provides an interactive interface to test APIs directly from the browser.

---

# 🧪 API Testing

APIs can be tested using:

• Postman
• Swagger UI
• Browser (for GET requests)

---

# 🚀 Future Enhancements

• Add Update Employee API
• Implement Authentication using JWT
• Add role-based authorization
• Develop a frontend using React
• Deploy application to cloud (AWS / Render / Railway)

---

# 👨‍💻 Author

Raj Gaurav Kumar Singh
Bengal Institute of Technology

GitHub
https://github.com/rajgaurav07

---

# ⭐ If you like this project

Give it a ⭐ on GitHub to support the project.
