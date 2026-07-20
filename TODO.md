# Spring Boot CRUD with MySQL

## Project Overview
Basic Spring Boot REST API performing CRUD (Create, Read, Update, Delete) operations on a `User` entity using MySQL database.

## CRUD Endpoints (Base URL: `/api/users`)

| Method | Endpoint       | Description          |
|--------|---------------|----------------------|
| POST   | `/api/users`  | Create a new user    |
| GET    | `/api/users`  | Get all users        |
| GET    | `/api/users/{id}` | Get user by ID   |
| PUT    | `/api/users/{id}` | Update user by ID |
| DELETE | `/api/users/{id}` | Delete user by ID |

## Tech Stack
- **Backend:** Spring Boot 4.1.0, Spring Data JPA
- **Database:** MySQL (schema: `demo_db`)
- **Build Tool:** Maven
- **Java Version:** 21

## To Run
1. Ensure MySQL is running with database `demo_db` created.
2. Update `application.properties` with your MySQL credentials.
3. Run: `./mvnw spring-boot:run`

