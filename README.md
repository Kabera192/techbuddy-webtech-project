# TechBuddy Project

![Java](https://img.shields.io/badge/Java-17-blue?logo=java&style=flat-square)
![MySQL](https://img.shields.io/badge/MySQL-8-blue?logo=mysql&style=flat-square)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3-green?logo=spring&style=flat-square)
![Thymeleaf](https://img.shields.io/badge/Thymeleaf-3-orange?logo=thymeleaf&style=flat-square)

TechBuddy is a web application built with Spring Boot and Thymeleaf for managing and storing images and videos. The project is secured using Spring Security.

## Getting Started

Follow these steps to get the project up and running on your local machine.

### Prerequisites

- Java 17 installed
- MySQL 8 installed
- Maven installed

### Clone the Repository

```bash
git clone https://github.com/your-username/TechBuddy.git
cd TechBuddy
```

### Configure Database
#### Create a MySQL database named techbuddy.

Update the ```src/main/resources/application.properties``` file with your MySQL username and password.

```
spring.datasource.url=jdbc:mysql://localhost:3306/techbuddy
spring.datasource.username=your-username
spring.datasource.password=your-password
```

### Run Application
```mvn spring-boot:run```

Visit ```http://localhost:8080``` in your browser.
