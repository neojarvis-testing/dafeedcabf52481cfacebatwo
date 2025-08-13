# Employee CRUD Application

This project is a simple CRUD (Create, Read, Update, Delete) application for managing employee data. It consists of a backend built with Spring Boot and a frontend developed using Angular. The application allows users to perform operations on an employee database.

## Project Structure

The project is organized into two main parts: the backend and the frontend.

### Backend

The backend is built using Spring Boot and connects to a MySQL database. It includes the following components:

- **EmployeeApplication.java**: The entry point of the Spring Boot application.
- **EmployeeController.java**: Handles HTTP requests related to Employee entities.
- **Employee.java**: Represents the Employee entity with properties such as id, name, position, and department.
- **EmployeeRepository.java**: Interface for CRUD operations on Employee entities.
- **EmployeeService.java**: Contains business logic for managing Employee entities.
- **application.properties**: Configuration properties for the Spring Boot application, including database connection settings.
- **schema.sql**: SQL statements for initializing the database schema.

### Frontend

The frontend is developed using Angular and provides a user interface for interacting with the employee data. It includes the following components:

- **EmployeeListComponent**: Displays a list of employees.
- **EmployeeDetailComponent**: Shows details of a selected employee.
- **EmployeeFormComponent**: Provides a form for adding or editing employee information.
- **EmployeeService**: Contains methods for making HTTP requests to the backend API for employee data.
- **app.module.ts**: The root module of the Angular application.
- **app.component.ts**: The main component of the application.

## Getting Started

### Prerequisites

- Java 11 or higher
- Maven
- MySQL
- Node.js and npm
- Angular CLI

### Backend Setup

1. Navigate to the `backend` directory.
2. Update the `application.properties` file with your MySQL database connection settings.
3. Run the application using Maven:

   ```
   mvn spring-boot:run
   ```

### Frontend Setup

1. Navigate to the `frontend` directory.
2. Install the required npm packages:

   ```
   npm install
   ```

3. Start the Angular application:

   ```
   ng serve
   ```

## API Endpoints

The backend exposes the following API endpoints for managing employees:

- `GET /api/employees`: Retrieve a list of all employees.
- `GET /api/employees/{id}`: Retrieve details of a specific employee.
- `POST /api/employees`: Create a new employee.
- `PUT /api/employees/{id}`: Update an existing employee.
- `DELETE /api/employees/{id}`: Delete an employee.

## License

This project is licensed under the MIT License.