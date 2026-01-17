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




