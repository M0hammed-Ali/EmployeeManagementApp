# Employee Management Web Application

This is a web application for managing employees with CRUD (Create, Read, Update, Delete) operations. It provides a user-friendly interface for performing various actions related to employee management.

## Technologies Used

- **Frontend**: React.js
- **Backend**: Java Spring Boot
- **API Testing**: Postman
- **Database**: PostgreSQL

## Features

- **Create Employee**: Add new employees to the database with relevant information such as name, email, department, etc.
- **Read Employee**: View the list of employees along with their details.
- **Update Employee**: Modify existing employee information.
- **Delete Employee**: Remove employees from the database.

## Getting Started

### Prerequisites

- Node.js and npm installed for frontend setup.
- Java Development Kit (JDK) installed for backend development.
- Postman installed for testing APIs.
- PostgreSQL installed and running.

### Frontend Setup

1. Navigate to the frontend directory.
2. Install dependencies:
npm install
3. Start the development server:
npm start
4. Access the application at http://localhost:3000.

### Backend Setup

1. Navigate to the backend directory.
2. Build the project:
./gradlew build
3. Run the application:
java -jar build/libs/your-application-name.jar
The backend server will start at http://localhost:8080.

### Database Setup

1. Create a PostgreSQL database named `employee_management`.
2. Configure the database connection in the backend application properties (`application.properties`).

## API Endpoints

- **GET /api/employees**: Retrieve all employees.
- **GET /api/employees/{id}**: Retrieve a specific employee by ID.
- **POST /api/employees**: Create a new employee.
- **PUT /api/employees/{id}**: Update an existing employee.
- **DELETE /api/employees/{id}**: Delete an employee by ID.

## Testing

Use Postman or any other API testing tool to test the endpoints listed above.

## Contributing

Contributions are welcome! Feel free to fork the repository and submit pull requests.

## License

This project is licensed under the MIT License.
