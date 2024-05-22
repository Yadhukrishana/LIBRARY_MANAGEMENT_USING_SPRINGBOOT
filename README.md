# Library Management System

A comprehensive Library Management System built using Spring Boot. This application provides functionalities to manage books, users, and borrowing activities in a library.

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Endpoints](#endpoints)
- [Contributing](#contributing)
- [License](#license)

## Features

- Manage books: add, update, delete, and view book details
- User management: register, login, and view user details
- Borrowing management: borrow and return books
- Search functionality for books and users
- Authentication and authorization

## Tech Stack

- **Backend:** Spring Boot, Spring Security, JPA/Hibernate
- **Database:** MySQL
- **Frontend:** Thymeleaf (or specify if using a different frontend framework)
- **Build Tool:** Maven

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Yadhukrishana/LIBRARY_MANAGEMENT_USING_SPRINGBOOT.git
   cd LIBRARY_MANAGEMENT_USING_SPRINGBOOT

   
spring.datasource.url=jdbc:mysql://localhost:3306/library_db
spring.datasource.username=yourUsername
spring.datasource.password=yourPassword

mvn clean install

mvn spring-boot:run
