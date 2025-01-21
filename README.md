Java-CRUD

This project is a simple implementation of a Student CRUD (Create, Read, Update, Delete) System using Java and Spring Boot. It includes functionality for managing student data with login credentials, providing an intuitive user interface for interacting with the system. The project was completed as a collaborative effort with my friends.

Features

Student Management:

Add new students.

View student details.

Update existing student information.

Delete student records.

Authentication:

Secure login system for accessing the application.

Frontend:

Responsive and user-friendly design.

Utilizes HTML, CSS, and JavaScript for a seamless experience.

Backend:

Built using Spring Boot.

RESTful API endpoints for CRUD operations.

Technologies Used

Frontend:

HTML5

CSS3

JavaScript

Backend:

Java

Spring Boot

Database:

MySQL (or replace with your chosen database system)

Prerequisites

Before running this project, ensure you have the following installed:

Java Development Kit (JDK) 8 or above

MySQL Database

Maven (for building the project)

Spring Boot

Installation and Setup

Clone the Repository:

git clone https://github.com/your-username/java-crud.git
cd java-crud

Configure the Database:

Create a database named student_db.

Update the application.properties file in the Spring Boot project with your database credentials:

spring.datasource.url=jdbc:mysql://localhost:3306/student_db
spring.datasource.username=your-username
spring.datasource.password=your-password
spring.jpa.hibernate.ddl-auto=update

Build the Project:

mvn clean install

Run the Application:

mvn spring-boot:run

Access the Application:

Open your browser and navigate to http://localhost:8080.

API Endpoints

Get All Students: GET /api/v1/students1

Add a Student: POST /api/v1/students1

Update a Student: PUT /api/v1/students1/{id}

Delete a Student: DELETE /api/v1/students1/{id}

Usage

Login: Enter valid credentials to access the student management system.

Manage Students: Use the table interface to view, add, update, or delete student records.

Logout: Securely log out after completing your tasks.

Project Structure

java-crud/
├── src/
│   ├── main/
│   │   ├── java/net/javaguides/springboot/
│   │   │   ├── controller/
│   │   │   ├── model/
│   │   ├── resources/
│   └── test/
└── pom.xml

Contributors

This project was developed in collaboration with:

Your Name

Friend 1 Name

Friend 2 Name

License

This project is licensed under the MIT License.

Acknowledgments

Spring Boot Documentation: https://spring.io/projects/spring-boot

MySQL Documentation: https://dev.mysql.com/doc/

CSS Gradient Generator: https://cssgradient.io/

