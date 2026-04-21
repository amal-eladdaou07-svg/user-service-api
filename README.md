# User Service API

Spring Boot REST API for managing users with MySQL database integration and Swagger OpenAPI documentation.

---

## Project Overview

This project is a backend REST API developed using **Spring Boot**.  
It provides CRUD operations for managing users and follows a clean layered architecture commonly used in professional backend systems.

The API is documented using **Swagger OpenAPI**, allowing interactive testing of endpoints.

---

## Features

- Create new users
- Retrieve all users
- Retrieve user by ID
- Update existing users
- Delete users
- MySQL database integration
- Swagger interactive documentation
- Clean layered architecture

---

## Technologies Used

- Java 17
- Spring Boot
- Spring Data JPA
- MySQL
- Maven
- Swagger OpenAPI

---

## Project Structure


src/main/java/com/amal/userservice

controller → REST API endpoints
service → business logic
repository → database access layer
entity → database models
config → Swagger configuration


---

## API Documentation

Swagger UI available at:


http://localhost:8081/swagger-ui/index.html


Example endpoints:


GET /api/users
GET /api/users/{id}
POST /api/users
PUT /api/users/{id}
DELETE /api/users/{id}


---

## Database Configuration

Before running the project, configure your MySQL credentials inside:


src/main/resources/application.properties


Example:


spring.datasource.url=jdbc:mysql://localhost:3306/user_service_db
spring.datasource.username=root
spring.datasource.password=YOUR_PASSWORD_HERE


---

## How to Run the Project

Clone repository:


git clone https://github.com/amal-eladdaou07-svg/user-service-api.git


Navigate into project:


cd user-service-api


Run application:


mvn spring-boot:run


Server starts at:


http://localhost:8081


---

## Architecture

This project follows a standard Spring Boot layered architecture:


Controller → Service → Repository → Database


This structure improves:

- maintainability
- scalability
- readability
- testability

---

## Author

Amal EL ADDAOU
Engineering Student – Software Engineering and Distributed Systems (GLSID)  
ENSET Mohammedia
