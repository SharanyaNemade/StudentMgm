# StudentMgm
The Student Management System is a web-based application built using Spring Boot, following the MVC (Model-View-Controller) design pattern. It provides a structured way to manage student information, including functionalities such as creating, viewing, and managing student records. CRUD operation have been performed


# 🎓 Student Management System

This is a **Spring Boot** based web application that allows users to manage student records. It supports creating, viewing, and listing students using a simple and clean UI built with **Thymeleaf**.

---

## 📁 Project Structure




FinalProject
├── src
│ └── main
│ ├── java
│ │ └── com.example
│ │ ├── StudentManagementSystemApplication.java
│ │ ├── controller
│ │ │ └── StudentController.java
│ │ ├── entity
│ │ │ └── Student.java
│ │ ├── repository
│ │ │ └── StudentRepository.java
│ │ └── service
│ │ ├── StudentService.java
│ │ └── StudentServiceImplement.java
│ └── resources
│ ├── static
│ ├── templates
│ │ ├── base.html
│ │ ├── create_student.html
│ │ ├── footer.html
│ │ ├── header.html
│ │ └── students.html
│ └── application.properties






---

## 🚀 Features

- 📋 View list of students
- ➕ Add new student
- 📄 Dynamic HTML templates using Thymeleaf
- 🗂️ Organized using Spring Boot MVC architecture

---

## 🛠️ Technologies Used

- **Java 17+**
- **Spring Boot**
- **Spring Data JPA**
- **Thymeleaf**
- **H2 / MySQL** *(configure in `application.properties`)*
- **Maven** or **Gradle**

---

## 🔧 Configuration

Make sure to configure your database settings in the `application.properties` file:

```properties
# Example for H2 (in-memory)
spring.datasource.url=jdbc:h2:mem:testdb
spring.datasource.driverClassName=org.h2.Driver
spring.datasource.username=sa
spring.datasource.password=
spring.jpa.database-platform=org.hibernate.dialect.H2Dialect
spring.h2.console.enabled=true




📂 Templates Overview
base.html – Layout file for shared UI structure

header.html / footer.html – Fragments for consistent layout

students.html – List all students

create_student.html – Form for creating a new student






▶️ Running the Project
Clone the repository:

git clone https://github.com/your-username/student-management-system.git
cd student-management-system


Build and run:
./mvnw spring-boot:run




Open in browser:
http://localhost:8080/students




📌 Future Improvements
Edit and delete student records
Add validation to forms
Add Security and JWT + oauth 2.0 
Pagination and search functionality
Add user authentication




📃 License
This project is licensed under the MIT License.



🙌 Acknowledgements
This project structure follows standard Spring Boot MVC architecture and is great for learning CRUD operations with Spring and Thymeleaf.
