Employee and Department Microservices
About the Project
This is a Java Spring Boot project with two microservices: Employee Service and Department Service. Both services provide REST APIs to perform CRUD operations.

Technologies Used
Java 17
Spring Boot
Spring Data JPA
H2 Database
Maven
Postman
Services and Ports
Employee Service: 8081
Department Service: 8082
API Endpoints
Employee Service: http://localhost:8081/api/employees

Department Service: http://localhost:8082/api/departments

Both services support:

POST – Create a record
GET – Get all records or a record by ID
PUT – Update a record
DELETE – Delete a record
Features
CRUD operations for employees and departments
Input validation
Exception handling
H2 database integration
How to Run
Import both projects into Spring Tool Suite (STS).
Run EmployeeServiceApplication.java.
Run DepartmentServiceApplication.java.
Test the APIs using Postman.
Testing
The APIs were tested using Postman, including CRUD operations, invalid input, and requests for nonexistent IDs.