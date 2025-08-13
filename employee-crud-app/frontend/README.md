# Employee CRUD Application - Frontend

This project is a simple single entity CRUD application for managing an employee database. It is built using Angular for the frontend and Spring Boot with MySQL for the backend.

## Project Structure

The frontend of the application is structured as follows:

- `src/app`: Contains the main application code.
  - `employee`: Contains components and services related to employee management.
    - `employee-list`: Displays a list of employees.
    - `employee-detail`: Shows details of a selected employee.
    - `employee-form`: Provides a form for adding or editing employee information.
    - `employee.service.ts`: Contains methods for making HTTP requests to the backend API for employee data.
  - `app.module.ts`: The root module of the Angular application.
  - `app.component.ts`: The main component of the application.

- `src/environments`: Contains environment-specific settings.
  - `environment.ts`: Development environment settings.
  - `environment.prod.ts`: Production environment settings.

## Getting Started

To run the frontend application, follow these steps:

1. Ensure you have Node.js and Angular CLI installed on your machine.
2. Navigate to the `frontend` directory.
3. Install the project dependencies by running:
   ```
   npm install
   ```
4. Start the development server:
   ```
   ng serve
   ```
5. Open your browser and navigate to `http://localhost:4200` to view the application.

## API Integration

The frontend communicates with the backend API to perform CRUD operations on employee data. Ensure that the backend server is running and accessible.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any enhancements or bug fixes.

## License

This project is licensed under the MIT License.