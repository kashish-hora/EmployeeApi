# EmployeeApi

Project Name: Spring Boot CRUD Operations with MongoDB

Name: Kashish Hora

Description:
This project demonstrates basic CRUD (Create, Read, Update, Delete) operations using Spring Boot with Maven and MongoDB. It provides RESTful API endpoints to interact with the MongoDB database.

Requirements:
- Java Development Kit (JDK) 8 or higher
- Apache Maven
- MongoDB installed and running locally or on a remote server
- Spring Tool Suite or any other IDE
- Visual Studio Code or any other IDE

Setup Instructions:
1. Clone the repository from GitHub:
   $ git clone [repository_url]
   
2. Navigate to the project directory:
   $ cd spring-boot-crud-mongodb
   
3. Build the project using Maven:
   $ mvn clean package
   
4. Run the Spring Boot application:
   $ java -jar target/spring-boot-crud-mongodb.jar

Running the Project:
- Once the application is running, you can access the API endpoints using tools like Thunder Client, Postman, or cURL.

Sending API Requests using Visual Studio Thunder Client:
1. Open Visual Studio Code.
2. Install the Thunder Client extension if not already installed.
3. Open Thunder Client and create a new request file.
4. Set the request method (GET, POST, PUT, DELETE) and specify the URL of the API endpoint.
5. Add request headers and body as needed.
6. Send the request and observe the response.

API Endpoints:
- GET /api/employees: Retrieve all employees.
- GET /api/employees/{id}: Retrieve an employee by ID.
- POST /api/employees: Create a new employee.
- PUT /api/employees/{id}: Update an existing employee.
- DELETE /api/employees/{id}: Delete an employee by ID.

Example Request (Thunder Client):
- Method: GET
- URL: http://localhost:8080/api/employees
- Headers: Content-Type: application/json
- Body: None

Example Response:
{
  "id": "1",
  "name": "John Doe",
  "profileUrl": "http://example.com/johndoe"
}

Note: Make sure to replace the URL with your actual endpoint URL and adjust the request body accordingly for POST and PUT requests.

This project is built using Spring Tool Suite (STS) or any other compatible IDE.

