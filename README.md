# Contact_Management_System
# 📇 Contact Management CRUD Application


### Java Practical Exam File

---



---

## 📌 Project Overview

This project is a Contact Management CRUD Application developed using Spring Boot.  
It allows users to Create, Read, Update, and Delete contact details using RESTful APIs.  
The application uses an H2 in-memory database and follows a layered architecture.

---

## 🛠️ Technologies Used

- Java 17  
- Spring Boot  
- Spring Data JPA  
- H2 Database  
- Maven  
- REST APIs  

---

## 🏗️ Project Architecture

Controller → Service → Repository → Database

---

## 📂 Project Structure

contactmanagement  
├── controller  
│   └── ContactController.java  
├── service  
│   └── ContactService.java  
├── repository  
│   └── ContactRepository.java  
├── model  
│   └── Contact.java  
├── ContactManagementApplication.java  
└── application.properties  

---

## ⚙️ Application Features

- Create new contact  
- Read all contacts  
- Update contact details  
- Delete contact  
- RESTful API implementation  
- H2 database integration  

---

## 🔗 REST API Endpoints

POST    /contacts        → Add a new contact  
GET     /contacts        → Get all contacts  
PUT     /contacts/{id}   → Update a contact  
DELETE  /contacts/{id}   → Delete a contact  

---

## 🧪 H2 Database Console

- URL: http://localhost:8080/h2-console  
- JDBC URL: jdbc:h2:mem:testdb  
- Username: sa  
- Password: (empty)  

---

## ▶️ How to Run the Project

1. Open the project in IntelliJ IDEA or Eclipse  
2. Ensure Java 17 is installed  
3. Run the application using:

   mvn spring-boot:run  

4. Test APIs using Postman or browser  

---

## 📄 application.properties

spring.datasource.url=jdbc:h2:mem:testdb  
spring.datasource.driverClassName=org.h2.Driver  
spring.datasource.username=sa  
spring.datasource.password=  

spring.jpa.hibernate.ddl-auto=update  
spring.jpa.database-platform=org.hibernate.dialect.H2Dialect  
spring.h2.console.enabled=true  

---

## 📦 Build Tool

Maven is used for dependency management and project build using pom.xml.

---

## ✅ Conclusion

This project demonstrates a simple Spring Boot CRUD application using REST APIs and Spring Data JPA.  
It is suitable for Java practical exams and beginner-level Spring Boot learning.
