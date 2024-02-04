# Task Management Application

The Task Management application is a Spring Boot project designed to demonstrate the implementation of a To-Do List system. Users can efficiently manage tasks through basic CRUD (Create, Read, Update, Delete) operations.

## Technologies Used

- **Spring Boot:** The core framework providing a robust foundation for application development.
- **Spring Data JPA:** Simplifies database operations, seamlessly integrated with Spring Boot.
- **Spring Web:** Facilitates the development of RESTful APIs for handling HTTP requests.
- **H2 Database (for tests):** In-memory database employed for unit testing purposes.
- **PostgreSQL:** Main database utilized for storing and retrieving task information.
- **Docker:** Embraces containerization with a Docker Compose file orchestrating the PostgreSQL database container.

## Features

- Basic CRUD operations for effective task management.
- Comprehensive unit and integration tests to ensure application reliability.
- Dockerized setup using Docker Compose for the PostgreSQL database and a Dockerfile for building an application image.

## UML Class Diagram

The UML class diagram presented below offers a visual representation of the foundational classes within the Task Management application. At its core is the `Task` class, encapsulating essential attributes such as title, description, due date, and completion status.
![UML Class Diagram](https://github.com/ZinebElJanyani/taskManagement/blob/master/classDiagram_taskManagement.drawio.png)
## How to Run

1. Clone the repository.
2. Build the Docker image using the provided Dockerfile.
3. Use Docker Compose to start the PostgreSQL container.
4. Run the Spring Boot application.

Explore the codebase to gain insights into the implementation of Spring Boot, JPA, and Docker concepts. This project serves as an invaluable resource for learning and practicing these technologies.
