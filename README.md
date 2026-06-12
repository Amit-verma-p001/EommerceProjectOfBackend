# Dream Shops - E-Commerce Backend

A complete E-Commerce Backend application built using Java, Spring Boot, Spring Data JPA, Hibernate, and MySQL.

## Features

- User Management
- Category Management
- Product Management
- Shopping Cart
- Order Management
- Product Image Upload
- Global Exception Handling
- RESTful APIs

## Tech Stack

- Java 21
- Spring Boot
- Spring Data JPA
- Hibernate
- MySQL
- Maven
- Lombok

## Database

MySQL

## API Base URL

http://localhost:9191/api/v1

## Modules

### User
- Create User
- Update User
- Delete User
- Get User By Id

### Category
- Add Category
- Update Category
- Delete Category
- Get Category

### Product
- Add Product
- Update Product
- Delete Product
- Search Product

### Cart
- Add Item To Cart
- Update Quantity
- Remove Item
- Clear Cart

### Orders
- Place Order
- Get Order Details
- Get User Orders

## Run Project

1. Clone Repository

```bash
git clone <repository-url>
```

2. Create MySQL Database

```sql
CREATE DATABASE dream_shops_db;
```

3. Configure application.properties

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/dream_shops_db
spring.datasource.username=root
spring.datasource.password=your_password
```

4. Run Application

```bash
mvn spring-boot:run
```

## Author

Amit Verma
Java Backend Developer
