# CF8 SchoolApp Project (Coding Factory)

A full-stack SSR School Management System developed as part of the Coding Factory bootcamp curriculum. This project demonstrates real-world web application development skills acquired during the program.

## Project Overview

SchoolApp is a complete school management system built with Spring Boot, designed to handle student information, teacher management, and administrative operations in an educational institution.

## Bootcamp Learning Objectives

This project was developed to practice and demonstrate:
- **Enterprise Java Development** - Spring Boot framework
- **Object-Oriented Programming** - Java design patterns and principles
- **Database Integration** - JPA/Hibernate with MySQL
- **REST API Development** - Spring MVC and REST controllers
- **Layered Architecture** - Service-Repository-Controller pattern

### **Backend**
- Java 17 (Amazon Corretto 17.0.15_6)
- Spring Boot 3.5.3
- Spring Data JPA
- Spring Security
- Spring MVC
- Gradle 8.14.3

### **Frontend**
- **Thymeleaf**
- **HTML5**
- **CSS3**
- **JavaScript**
- **Bootstrap**
- 
  ### **Database**
- MySQL
- Hibernate ORM
- JPA specifications

### Running the application
BUILD -> gradle clean build

RUN -> java -jar ./build/libs/schoolapp.jar

 ### Configuration
```properties
# application.properties
spring.datasource.url=jdbc:mysql://localhost:3306/schoolapp
spring.datasource.username=your_username
spring.datasource.password=your_password
spring.jpa.hibernate.ddl-auto=update
