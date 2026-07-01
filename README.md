# Employee Management API

A **Spring Boot REST API** for managing employee records with JWT-based authentication and role-based access control.

## 🚀 Features
- ✅ CRUD Operations (Create, Read, Update, Delete)
- ✅ Input Validation (@NotBlank, @Email, @Positive)
- ✅ Exception Handling (404, 400 errors)
- ✅ JWT Authentication & Authorization
- ✅ Password Encryption with BCrypt
- ✅ API Documentation with Swagger UI

## 🛠️ Tech Stack
- Java 17
- Spring Boot
- Spring Security + JWT
- Spring Data JPA
- MySQL
- Maven
- Swagger (SpringDoc OpenAPI)

## 📸 Screenshots
<img width="1867" height="886" alt="Swagger" src="https://github.com/user-attachments/assets/aa5f31fc-1d89-43fd-b99d-eed63d8c400e" />

## 📌 API Endpoints

### Auth
| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | /api/auth/register | Register new user |
| POST | /api/auth/login | Login and get JWT token |

### Employee
| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | /api/employees | Get all employees |
| GET | /api/employees/{id} | Get employee by ID |
| POST | /api/employees | Create new employee |
| PUT | /api/employees/{id} | Update employee |
| DELETE | /api/employees/{id} | Delete employee |

## ⚙️ Setup
1. Clone the repository
2. Configure MySQL in `application.properties`
3. Run the application
4. Access Swagger UI at `http://localhost:8080/swagger-ui/index.html`

## 👩‍💻 Developer
**Gayatri Dnyaneshwar Chaudhari**  
🔗 [LinkedIn](https://linkedin.com/in/gayatri-chaudhari-1023)  
🐙 [GitHub](https://github.com/gayatrichaudhari1023)
