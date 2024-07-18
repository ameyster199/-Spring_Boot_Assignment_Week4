# Spring Boot Assignment Week 4

## Overview
This project demonstrates the integration of validation and error handling into a Spring Boot application. The application manages CRUD operations for a `Product` entity with validation and error handling.

## Running the Application
1. Clone the repository.
2. Navigate to the project directory.
3. Run the application using `mvn spring-boot:run`.

## Testing Validation and Error Handling
- Use Postman or a similar tool to test the CRUD endpoints.
- Try creating or updating a product with invalid data to trigger validation errors.
- Access a non-existing product to see the custom error messages.

## Code Navigation
- `entity/`: Contains the `Product` entity class with validation constraints.
- `controller/`: Contains the `ProductController` class for handling HTTP requests.
- `service/`: Contains the `ProductService` class for business logic.
- `repository/`: Contains the `ProductRepository` interface for database operations.
- `globalhandler/`: Contains the `GlobalExceptionHandler` class for handling exceptions globally.
- `controllerhandler/`: Contains the `ControllerExceptionHandler` class for handling exceptions at the controller level.
- `exception/`: Contains custom exception classes.

## Group Information
- List the names and student IDs of each group member here.
