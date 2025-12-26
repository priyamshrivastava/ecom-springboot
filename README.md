# 🛒 E-Commerce Backend – Spring Boot

A robust **backend-only E-Commerce application** built using **Spring Boot**, focused on clean architecture, RESTful APIs, and scalable backend design.  
This project is designed to serve as the core backend for an e-commerce platform and is tested using **Postman** with an **H2 in-memory database** for fast development.

---

## 🚀 Features

- RESTful APIs for e-commerce operations
- Layered architecture (Controller → Service → Repository)
- In-memory database using **H2**
- API testing via **Postman**
- Clean and scalable Spring Boot project structure
- Maven-based dependency management

---

## 🛠️ Tech Stack

- **Java**
- **Spring Boot**
- **Spring Web**
- **Spring Data JPA**
- **H2 Database**
- **Maven**
- **Postman**

---
src/main/java/com/example/ecom
│
├── controller # REST Controllers
├── service # Business logic
├── repo # Data access layer (JPA repositories)
├── model # Entity classes
└── EcomApplication.java
## 📂 Project Structure


---

## 🧪 API Testing (Postman)

All APIs are tested using **Postman**.  
You can import the Postman collection or manually hit endpoints after running the application.

Example:
GET /products
POST /products


---

## 🗄️ Database (H2)

- Uses **H2 In-Memory Database** for development and testing
- No external database setup required
- Data resets on application restart

### H2 Console
http://localhost:8080/h2-console


(Default credentials can be found in `application.properties`)

---

## ▶️ How to Run Locally

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/priyamshrivastava/ecom-springboot.git
cd ecom-springboot
mvn spring-boot:run
```

---

📌 Purpose of This Project

Practice backend development with Spring Boot

Build a real-world e-commerce backend

Demonstrate clean architecture and REST API design

Suitable for internships, backend roles, and portfolio

---

🔮 Future Enhancements

Authentication & Authorization (JWT)

User & Order management

Pagination & sorting

Swagger / OpenAPI documentation

Integration with MySQL / PostgreSQL

Deployment (Docker / Cloud)
