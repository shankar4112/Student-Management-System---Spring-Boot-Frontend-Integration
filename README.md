# Java-CRUD

This project is a simple implementation of a **Student Management System** using **Java** and **Spring Boot**. It provides basic **CRUD (Create, Read, Update, Delete)** operations for managing student information. The system includes features such as login authentication and a responsive frontend for user interaction.

## Features

- **Add New Students:** Enter details like roll number, first name, last name, and email.
- **View All Students:** Display a list of all students in a tabular format.
- **Update Student Details:** Modify student information.
- **Delete Students:** Remove a student's record from the system.
- **Login Functionality:** Secure access using login credentials.
- **User-Friendly UI:** Responsive and easy-to-navigate interface.

## Technologies Used

### Backend
- **Java**: Core programming language.
- **Spring Boot**: Framework for building REST APIs.
- **Jakarta Persistence API (JPA)**: For database operations.
- **H2 Database**: In-memory database for testing.

### Frontend
- **HTML/CSS**: For responsive design.
- **JavaScript**: To handle dynamic data rendering and event handling.

### Tools
- **Postman**: For testing APIs.
- **Maven**: Build automation tool.
- **IDE**: IntelliJ IDEA or Eclipse.

## Prerequisites

- Java Development Kit (JDK 11 or higher)
- Maven
- Spring Boot
- IDE (IntelliJ IDEA, Eclipse, or similar)

## Getting Started

### Clone the Repository
```bash
git clone https://github.com/your-username/java-crud.git
cd java-crud
```

### Backend Setup
1. Open the project in your preferred IDE.
2. Update `application.properties` if needed (e.g., database configuration):
   ```properties
   spring.datasource.url=jdbc:h2:mem:testdb
   spring.datasource.driverClassName=org.h2.Driver
   spring.datasource.username=sa
   spring.datasource.password=password
   spring.jpa.database-platform=org.hibernate.dialect.H2Dialect
   ```
3. Build and run the application:
   ```bash
   mvn spring-boot:run
   ```

### Frontend Setup
1. Open the `index.html` file in any browser to access the frontend.
2. Ensure the backend is running at `http://localhost:8080`.

## API Endpoints

| HTTP Method | Endpoint                 | Description              |
|-------------|--------------------------|--------------------------|
| GET         | `/api/v1/students1`      | Get all students         |
| POST        | `/api/v1/students1`      | Add a new student        |
| PUT         | `/api/v1/students1/{id}` | Update a student by ID   |
| DELETE      | `/api/v1/students1/{id}` | Delete a student by ID   |

## Usage

1. Start the Spring Boot server using Maven.
2. Access the frontend through `index.html`.
3. Use the web interface to manage student records.
4. Test API endpoints using tools like Postman or cURL.

## Screenshots

### Homepage
![Homepage Screenshot](https://via.placeholder.com/800x400.png?text=Homepage)

### Student Table
![Student Table Screenshot](https://via.placeholder.com/800x400.png?text=Student+Table)

## Contributors

- **[Your Name](https://github.com/your-username)**
- **Friends' Names**

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to contribute to this project by submitting issues or pull requests. Happy coding!
