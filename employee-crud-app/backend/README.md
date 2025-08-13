# Employee CRUD Application - Backend

This is the backend part of the Employee CRUD application built using Spring Boot and MySQL. The application provides a RESTful API for managing employee data.

## Project Structure

- `src/main/java/com/example/employee/`
  - `EmployeeApplication.java`: Entry point of the Spring Boot application.
  - `controller/EmployeeController.java`: Handles HTTP requests related to Employee entities.
  - `model/Employee.java`: Represents the Employee entity with properties such as id, name, position, and department.
  - `repository/EmployeeRepository.java`: Interface for CRUD operations on Employee entities.
  - `service/EmployeeService.java`: Contains business logic for managing Employee entities.

- `src/main/resources/`
  - `application.properties`: Configuration properties for the Spring Boot application, including database connection settings.
  - `schema.sql`: SQL statements for initializing the database schema.

## Getting Started

### Prerequisites

- Java 11 or higher
- Maven
- MySQL Database

### Installation

1. Clone the repository:
   ```
   git clone <repository-url>
   ```

2. Navigate to the backend directory:
   ```
   cd employee-crud-app/backend
   ```

3. Update the `application.properties` file with your MySQL database connection settings.

4. Run the application:
   ```
   mvn spring-boot:run
   ```

### API Endpoints

- `POST /employees`: Create a new employee
- `GET /employees`: Retrieve all employees
- `GET /employees/{id}`: Retrieve a specific employee by ID
- `PUT /employees/{id}`: Update an existing employee
- `DELETE /employees/{id}`: Delete an employee

## License

This project is licensed under the MIT License.