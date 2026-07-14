# Employee Management System (Spring Boot)

A Spring Boot REST API for managing employee records using Spring Data JPA and Oracle Database.

## Features

- Add Employee
- View All Employees
- View Employee by ID
- Update Employee
- Delete Employee
- REST API
- Oracle Database Integration
- Spring Data JPA
- Hibernate ORM
- Maven Project

## Technologies Used

- Java 21
- Spring Boot
- Spring Data JPA
- Hibernate
- Maven
- Oracle Database
- REST API

## Project Structure

```
src
 ├── main
 │   ├── java
 │   │    └── com.example.demo
 │   │          ├── controller
 │   │          ├── entity
 │   │          ├── service
 │   │          └── EmployeeSpringApplication.java
 │   └── resources
 │         └── application.properties
```

## API Endpoints

| Method | Endpoint | Description |
|---------|----------|-------------|
| GET | /employees | Get All Employees |
| GET | /employees/{id} | Get Employee by ID |
| POST | /employees | Add Employee |
| PUT | /employees/{id} | Update Employee |
| DELETE | /employees/{id} | Delete Employee |

## Employee Model

```java
Long id
String name
String email
String department
BigDecimal salary
LocalDate joinDate
```

## Run the Project

### Clone

```bash
git clone https://github.com/yourusername/employee-management-system-springboot.git
```

### Go to project

```bash
cd employee-management-system-springboot
```

### Run

```bash
mvn spring-boot:run
target/

*.class

.settings/

.project

.classpath

.factorypath

.springBeans

.sts4-cache/

.idea/

*.iml

.vscode/

bin/

logs/

*.log
```

## Author

Sathish
