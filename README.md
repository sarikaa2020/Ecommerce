Ecommerce Application:

->A Spring Boot–based E-commerce application developed using Java, Maven, and MVC architecture.

->This project implements user management (signup) and follows a clean layered structure suitable for scalable enterprise applications.

Features:

->User Registration (Signup)

->Layered Architecture (Controller, Service, Repository)

->JPA Entity-based data handling

->Thymeleaf template support

->Maven dependency management

->Spring Boot auto-configuration

Tech Stack:

| Layer         | Technology                  |
| ------------- | --------------------------- |
| Backend       | Java, Spring Boot           |
| ORM           | Spring Data JPA             |
| Build Tool    | Maven                       |
| Frontend      | Thymeleaf, HTML             |
| Configuration | application.properties      |
| Architecture  | MVC (Model–View–Controller) |

Project Structure:

Ecommerce/
│
├── src/main/java/com/ecommerce
│   ├── controller
│   │   └── UserController.java
│   │
│   ├── entity
│   │   └── User.java
│   │
│   ├── repository
│   │   └── UserRepository.java
│   │
│   ├── service
│   │   └── UserService.java
│   │
│   └── EcommerceApplication.java
│
├── src/main/resources
│   ├── templates
│   │   └── signup.html
│   └── application.properties
│
├── pom.xml
├── target/
└── README.md

How to Run the Project:

🔹 Prerequisites

->Java 8 or higher

->Maven

->Git

->IDE (IntelliJ / VS Code / Eclipse)

Steps to Run:
# Clone the repository
git clone https://github.com/sarikaa2020/Ecommerce.git

# Navigate to project directory
cd Ecommerce

# Run Spring Boot application
mvn spring-boot:run


Application will run at:
http://localhost:8080

Module Description:
User Module

->User.java – Entity class for user data

->UserRepository.java – Database operations using JPA

->UserService.java – Business logic layer

->UserController.java – Handles HTTP requests

->signup.html – User registration page

Current Status:

✔ Project setup completed
✔ User signup functionality
✔ MVC architecture implemented

 Future Enhancements:

->Product Management

-> Cart & Checkout System

-> Login & Authentication

-> Payment Gateway Integration

-> Admin Dashboard

-> Database integration (MySQL/PostgreSQL)

Contribution Guidelines:

->Fork the repository

->Create a new branch

->Commit your changes

->Submit a Pull Request

License:
This project is developed for educational and learning purposes.

Author-Sarikaa Ashree
🔗 GitHub: https://github.com/sarikaa2020






