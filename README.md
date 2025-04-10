# SAMSTRACK_API

# Student Management System

A full-stack **Student Management System** built with **Angular** (frontend) and **Spring Boot** (backend). This application allows administrators to manage student data including creating, updating, listing, and deleting records.

## 🛠️ Tech Stack

**Frontend:**  
- Angular 16  
- TypeScript  
- HTML5, CSS3  
- Bootstrap (optional)

**Backend:**  
- Spring Boot  
- Java  
- Spring Data JPA  
- MySQL (or any relational database)

## 📌 Features

- Add new students
- Update student details
- Delete student records
- View all students
- Responsive UI with Angular
- RESTful APIs with Spring Boot

## 📁 Project Structure

### Backend (`/student-management-backend`)
- `Student.java` - Entity class
- `StudentRepository.java` - JPA Repository
- `StudentService.java` - Service layer
- `StudentController.java` - REST Controller
- `application.properties` - DB configuration

### Frontend (`/student-management-frontend`)
- `student-list` component
- `add-student` component
- `update-student` component
- `student.service.ts` - HTTP Client Service
- Angular Routing module

## 🚀 Getting Started

### Prerequisites
- Node.js & npm
- Angular CLI
- Java 17+
- Maven
- MySQL

### Backend Setup
1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/student-management-system.git
   cd student-management-system/student-management-backend

2. Configure application.properties:
    spring.datasource.url=jdbc:mysql://localhost:3306/studentdb
    spring.datasource.username=root
    spring.datasource.password=yourpassword
    spring.jpa.hibernate.ddl-auto=update
   
4.  Run the Spring Boot application:
      mvn spring-boot:run

### Frontend Setup

1.   Navigate to the frontend folder:
      cd ../student-management-frontend

2.   Install dependencies:
       npm install

3.   Run the Angular application:
        ng serve

4.   Open in browser: http://localhost:4200


### 📂 Database Schema

      CREATE TABLE students (
        id BIGINT AUTO_INCREMENT PRIMARY KEY,
        first_name VARCHAR(50),
        last_name VARCHAR(50),
        email VARCHAR(100)
      );

Made with ❤️ by Om Sanjay Bhamare


