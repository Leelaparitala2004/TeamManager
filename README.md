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
├── controller/
│ ├── AuthController.java
│ ├── ProjectController.java
│ ├── TaskController.java
│ ├── UserController.java
│ └── DashboardController.java
│
├── service/
│ ├── UserService.java
│ ├── ProjectService.java
│ └── TaskService.java
│
├── repository/
│ ├── UserRepository.java
│ ├── ProjectRepository.java
│ └── TaskRepository.java
│
├── security/
│ ├── JwtAuthFilter.java
│ ├── JwtService.java
│ └── RoleBasedAuthConfig.java
│
└── model/
├── User.java
├── Project.java
├── Task.java
├── Role.java
└── UserRole.java


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
