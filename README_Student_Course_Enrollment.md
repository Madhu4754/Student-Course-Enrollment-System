# 🎓 Student Course Enrollment System (Java + Spring Boot)

A backend REST API system that allows students to enroll in courses and manage their academic data efficiently. Built with clean code practices using Java, Spring Boot, MySQL, and JPA.

---

## 🛠️ Tech Stack

- **Language**: Java 17
- **Framework**: Spring Boot 3.x
- **Database**: MySQL
- **ORM**: Spring Data JPA
- **Build Tool**: Maven
- **Testing**: JUnit, Postman
- **Version Control**: Git

---

##  Features

-  Student registration and course enrollment
-  Add, update, delete courses and students
-  RESTful API endpoints (GET, POST, PUT, DELETE)
-  Layered architecture: Controller, Service, Repository, Model
-  Input validation and error handling
-  Integrated with MySQL using Spring JPA
-  Unit testing with JUnit and API tested using Postman

---

##  Design Principles

-  Object-Oriented Design (OOP)
-  Reusability and clean separation of concerns
-  Follows REST architectural style
-  Dependency Injection via Spring Boot
-  Externalized configuration via `application.properties`

---

## Getting Started

### Prerequisites
- Java 17+
- Maven
- MySQL Server
- IDE (IntelliJ, Eclipse, VS Code)

### Clone the Repository
```bash
git clone https://github.com/yourusername/student-course-enrollment-system.git
cd student-course-enrollment-system
```

### MySQL Setup
```sql
CREATE DATABASE enrollmentdb;
```

### Update `src/main/resources/application.properties`
```properties
spring.datasource.url=jdbc:mysql://localhost:3306/enrollmentdb
spring.datasource.username=root
spring.datasource.password=yourpassword
```

### Build & Run
```bash
mvn spring-boot:run
```

---

##  Sample API Endpoints

| Method | Endpoint               | Description             |
|--------|------------------------|-------------------------|
| GET    | /students              | Fetch all students      |
| POST   | /students              | Add new student         |
| GET    | /courses               | Fetch all courses       |
| POST   | /courses               | Add new course          |

> You can test APIs using Postman or any REST client.

---

##  Testing

-  Unit tests with JUnit
-  API testing with Postman
-  Integration test-ready structure

---

##  License

This project is open-source and available under the [MIT License](LICENSE).

---

##  Author

**Madhu Bathula**  
[GitHub](https://github.com/Madhu4754) • [LinkedIn](https://linkedin.com/in/yourprofile)  

---

**Give a star** to the repo if you find it helpful!