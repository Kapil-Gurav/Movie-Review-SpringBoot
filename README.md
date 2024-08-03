# CineCritique

This Spring Boot application serves as a backend system for managing movie reviews. It provides RESTful APIs for performing CRUD operations on movie reviews stored in MongoDB. The application also includes functionality for user authentication and authorization.

## Technologies Used

- **Spring Boot**: Framework for creating Java-based applications.
- **MongoDB**: NoSQL database for storing movie reviews.
- **Postman**: Used for testing the APIs during development.
- **Maven**: Dependency management and build tool.

## Features

- **CRUD Operations**: Allows users to perform Create, Read, Update, and Delete operations on movie reviews.
- **User Authentication**: Supports user registration, login, and access control for managing reviews.
- **Validation**: Input validation and error handling to ensure data integrity.
- **API Documentation**: Utilizes Swagger or similar tools for API documentation.
- **Testing**: Integration tests using JUnit and Postman for API endpoint testing.

## Getting Started

To run the application locally, follow these steps:

1. **Clone the repository:**


2. **Navigate to the project directory:**


3. **Set up MongoDB:**

- Install MongoDB if not already installed.
- Create a database named `movies_review`.

4. **Configure application properties:**

- Update `application.properties` with MongoDB connection details (`spring.data.mongodb.*`).

5. **Run the application:**


6. **Access the application:**

The application will start at `http://localhost:8080`. You can use tools like Postman to interact with the APIs.

## API Endpoints

- **POST /api/reviews**: Create a new movie review.
- **GET /api/reviews**: Get all movie reviews.
- **GET /api/reviews/{id}**: Get a movie review by ID.
- **PUT /api/reviews/{id}**: Update a movie review.
- **DELETE /api/reviews/{id}**: Delete a movie review by ID.
- **POST /api/users/register**: Register a new user.
- **POST /api/users/login**: Authenticate and generate a token for accessing protected endpoints.

For detailed API documentation, run the application and navigate to `http://localhost:8080/swagger-ui.html`.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Inspired by [Spring Boot](https://spring.io/projects/spring-boot)
- MongoDB documentation
