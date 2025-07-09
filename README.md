# 🧠 TeamFlow Backend

TeamFlow is a collaborative task and project management platform built with a layered backend architecture using **Spring Boot**, **PostgreSQL**, and **JWT-based authentication**. It allows teams to manage users, projects, and tasks with role-based access control.

---

## 📦 Tech Stack

- **Java 17+**
- **Spring Boot**
  - Spring Security
  - Spring Data JPA
- **PostgreSQL**
- **JWT (JSON Web Token)**
- **Maven**

---

## 📂 Project Structure

src/
├── controller
│   ├── AuthController.java
│   ├── DashboardController.java
│   ├── ProjectController.java
│   ├── TaskController.java
│   └── UserController.java
├── model
│   ├── Project.java
│   ├── Role.java
│   ├── Task.java
│   ├── User.java
│   └── UserRole.java
├── repository
│   ├── ProjectRepository.java
│   ├── TaskRepository.java
│   └── UserRepository.java
├── security
│   ├── JwtAuthFilter.java
│   ├── JwtService.java
│   └── RoleBasedAuthConfig.java
└── service
    ├── ProjectService.java
    ├── TaskService.java
    └── UserService.java


---

## 🛡️ Security

- JWT-based stateless authentication
- Role-based access control for securing REST endpoints
- Custom `JwtAuthFilter` and authentication manager for validating tokens

---

## 📊 Modules & Features

### 🔐 AuthController
- Register / Login
- JWT token generation
- Token validation

### 👥 UserController
- Create / Update user
- Assign roles
- List users

### 📁 ProjectController
- Create / View / Delete Projects
- Assign users to projects

### ✅ TaskController
- CRUD operations on Tasks
- Assign tasks to users in a project

### 📊 DashboardController
- Project and task summaries for users

---

## 🧪 Database Schema

Tables:
- `users`
- `roles`
- `user_roles`
- `projects`
- `tasks`

Auto-created and managed via Spring JPA with:

```properties
spring.jpa.hibernate.ddl-auto=update


---

Let me know if you want to generate Swagger docs, write the frontend `README.md`, or make it look good on GitHub Pages.

---

Let me know if you want to generate Swagger docs, write the frontend `README.md`, or make it look good on GitHub Pages.

---

Let me know if you want to generate Swagger docs, write the frontend `README.md`, or make it look good on GitHub Pages.

---

Let me know if you want to generate Swagger docs, write the frontend `README.md`, or make it look good on GitHub Pages.
