# Library Management System

## Overview
This project is a **Library Management System** built using **Spring Boot**. It provides RESTful APIs to manage book details, user details, and borrowing/returning books.

## Features
- Developed APIs for managing **book details, user details**, and **borrowing/returning books**.
- Implemented **CRUD operations** on book data stored in a **MySQL database**.
- Used **Collections and Streams** for better data maintenance and logic building.
- Interacted with the application using **Postman** to send HTTP requests and receive responses from the backend.

## Tech Stack
- **Core Java**
- **Collection Framework**
- **Spring Boot**
- **Spring MVC**
- **MySQL**
- **Maven**
- **Postman**

## Installation and Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/library-management-system.git
   ```
2. Navigate to the project folder:
   ```bash
   cd library-management-system
   ```
3. Install dependencies:
   ```bash
   mvn clean install
   ```
4. Configure the **application.properties** file with your MySQL database details.
5. Run the Spring Boot application:
   ```bash
   mvn spring-boot:run
   ```

## API Endpoints
| Method | Endpoint | Description |
|--------|---------|------------|
| GET | `/books` | Get all books |
| POST | `/books` | Add a new book |
| PUT | `/books/{id}` | Update book details |
| DELETE | `/books/{id}` | Delete a book |
| GET | `/users` | Get all users |
| POST | `/users` | Add a new user |
| PUT | `/users/{id}` | Update user details |
| DELETE | `/users/{id}` | Delete a user |
| POST | `/borrow/{userId}/{bookId}` | Borrow a book |
| POST | `/return/{userId}/{bookId}` | Return a book |

## Author
**Supriya**  

---
