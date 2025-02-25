<h1>📌 Customer API</h1>

<h2>🛠️ About the Project</h2>

This is a small piece of code from a RESTful API developed in Java with Spring Boot for client management. The project follows the microservices architecture and includes basic CRUD operations (Create, Read, Update, Delete).

<h3>🚀 Technologies Used</h3>

<li>☕ Java 17</li>

<li>🌱 Spring Boot 3</li>

<li>🗄️ Spring Data JPA</li>

<li>🛢️ H2 Database (in-memory database for testing)</li>

<li>✅ JUnit for unit testing</li>

<h3>📂 Project Structure</h3>

```java
customer-api/
│── src/main/java/com/example/customerapi
│   ├── CustomerApiApplication.java  # Main Spring Boot class
│   ├── entity/Customer.java          # Customer entity
│   ├── repository/CustomerRepository.java # JPA repository interface
│   ├── service/CustomerService.java  # Business logic
│   ├── controller/CustomerController.java  # API endpoints
│── src/test/java/com/example/customerapi
│   ├── CustomerApiApplicationTests.java  # Unit tests
```

<h2>📌 Available Endpoints</h2>

<h3>📌 List all customers</h3>

```java
GET /customers
```

<h3>🔍 Get a customer by ID</h3>

```java
GET /customers/{id}
```
<h3>➕ Create a new customer</h3>

```java
POST /customers
Content-Type: application/json
{
  "name": "John Doe",
  "email": "john@example.com"
}
```

<h3>✅ Testing</h3>

The project includes unit tests using JUnit to ensure code quality.

<h2>📜 How to Run the Project</h2>

1. Clone this repository

2. Navigate to the project folder

3. Run the command:

```java
mvn spring-boot:run
```

4. The API will be available at http://localhost:8080

<h2>📝 License</h2>

This project is open-source and can be used as needed.
