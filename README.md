
# Product Catalog Management System

This repository contains a Spring Boot application for managing a product catalog.


## Video Demo

Watch the demo video [here](https://vimeo.com/986254677).

## Technologies Used

- **Backend**:
  - Spring Boot
  - PostgreSQL

- **Frontend**:
  - Thymeleaf

## Getting Started

### Prerequisites

List any prerequisites or dependencies that need to be installed before running the project.

### Installation

Provide step-by-step instructions on how to install and run the project locally.

1. Clone the repository:

   ```bash
   git clone https://github.com/your/repository.git
   cd repository-name
   ```

2. Build the project:

   ```bash
   ./mvnw clean package
   ```

3. Run the application:

   ```bash
   java -jar target/project-name.jar
   ```

   Alternatively, you can run it using Maven:

   ```bash
   ./mvnw spring-boot:run
   ```

### Usage

Explain how to use the product catalog management system.

1. **Adding a Product**:
   - Access the homepage at `http://localhost:8080/`.
   - Fill out the form to add a new product.
   - Click "Add" to save the product.

2. **Viewing Products**:
   - Navigate to `http://localhost:8080/products`.
   - See the list of products with details like name, price, and category.

### Endpoints

Describe the endpoints available in your application:

- `GET /`: Displays the homepage where you can add a new product.
- `POST /addProduct`: Adds a new product to the catalog.
- `GET /products`: Displays all products in the catalog.

### Project Structure

Briefly explain the structure of your project, focusing on important directories or files.

```
project-root/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/
│   │   │       └── example/
│   │   │           └── productcatalog/
│   │   │               ├── controller/
│   │   │               │   └── ProductController.java
│   │   │               ├── entity/
│   │   │               │   └── Product.java
│   │   │               ├── repository/
│   │   │               │   └── ProductRepository.java
│   │   │               └── service/
│   │   │                   └── ProductService.java
│   │   └── resources/
│   │       ├── static/
│   │       │   └── css/
│   │       │       └── styles.css
│   │       └── templates/
│   │           ├── index.html
│   │           └── products.html
│   └── test/
│       └── java/
│           └── com/
│               └── example/
│                   └── productcatalog/
│                       └── ProductCatalogApplicationTests.java
└── pom.xml
```

