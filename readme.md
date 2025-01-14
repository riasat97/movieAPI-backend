# Movie-App Full Stack Project

This project demonstrates the development of a full-stack Movie-App, featuring a Spring Boot backend and an Angular frontend. It showcases key backend features like JWT authentication and pagination, and essential frontend features such as CRUD operations and token handling.

## Features

- **Backend with Spring Boot**:
  - RESTful APIs
  - File handling
  - CRUD operations
  - Exception handling
  - Pagination and sorting
  - Spring Security with JWT authentication
  - Forgot/Reset Password API
- **Frontend with Angular**:
  - User login and registration
  - CRUD operations
  - Token refresh using interceptors
  - Forgot password UI

## Source Code

- **Backend**: [GitHub Repository](https://github.com/riasat97/movieAPI-backend)
- **Frontend**: [GitHub Repository](https://github.com/riasat97/movieAPI-frontend)

## Prerequisites

- **Backend**:
  - Java 11+
  - Spring Boot
  - MySQL or any relational database
- **Frontend**:
  - Node.js
  - Angular CLI version 17.3.0
- **Tools**:
  - Postman for API testing
  - Any IDE (e.g., IntelliJ IDEA for backend, VS Code for frontend)

---

## Frontend Setup (MovieApiUi)

This project was generated with Angular CLI version 17.3.0.

### Development Server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

### Code Scaffolding

Run `ng generate component component-name` to generate a new component. You can also use:

- `ng generate directive`
- `ng generate pipe`
- `ng generate service`
- `ng generate class`
- `ng generate guard`
- `ng generate interface`
- `ng generate enum`
- `ng generate module`

### Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

### Running Unit Tests

Run `ng test` to execute the unit tests via Karma.

### Running End-to-End Tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

---

## Getting Started

### Backend Setup

1. Clone the backend repository.
2. Configure the database in `application.properties`.
3. Run the project using your IDE or `mvn spring-boot:run`.

### Frontend Setup

1. Clone the frontend repository.
2. Install dependencies using `npm install`.
3. Start the development server with `ng serve`.
