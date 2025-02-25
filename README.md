📌 Customer API

🛠️ About the Project

This is a RESTful API developed in Java with Spring Boot for customer management. The project follows a microservices architecture and includes basic CRUD operations (Create, Read, Update, Delete).

🚀 Technologies Used

☕ Java 17

🌱 Spring Boot 3

🗄️ Spring Data JPA

🛢️ H2 Database (in-memory database for testing)

✅ JUnit for unit testing

📂 Project Structure

customer-api/
│── src/main/java/com/example/customerapi
│   ├── CustomerApiApplication.java  # Main Spring Boot class
│   ├── entity/Customer.java          # Customer entity
│   ├── repository/CustomerRepository.java # JPA repository interface
│   ├── service/CustomerService.java  # Business logic
│   ├── controller/CustomerController.java  # API endpoints
│── src/test/java/com/example/customerapi
│   ├── CustomerApiApplicationTests.java  # Unit tests

📌 Available Endpoints

📌 List all customers

GET /customers

🔍 Get a customer by ID

GET /customers/{id}

➕ Create a new customer

POST /customers
Content-Type: application/json
{
  "name": "John Doe",
  "email": "john@example.com"
}

✅ Testing

The project includes unit tests using JUnit to ensure code quality.

📜 How to Run the Project

Clone this repository

Navigate to the project folder

Run the command:

mvn spring-boot:run

The API will be available at http://localhost:8080

📝 License

This project is open-source and can be used as needed.

🚀 Developed by Cristian Fernandes

