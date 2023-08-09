# Shopme - eCommerce Web App using Spring Boot

Welcome to the **Shopme - eCommerce Web App** repository! This project is a demonstration of building a fully functional ecommerce web application using the Spring Boot framework. The application provides a platform for users to browse, search, and purchase products online.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Technologies](#technologies)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This Ecommerce Web App is built using the Spring Boot framework, which simplifies the development of robust, scalable, and maintainable web applications. The app demonstrates best practices for building an ecommerce platform, including user authentication, product management, cart functionality, and order processing.

## Features

- User registration and authentication
- Product browsing and searching
- Shopping cart management
- Secure payment processing
- Order history and tracking
- Admin dashboard for product and order management

## Getting Started

### Prerequisites

Before you begin, ensure you have met the following requirements:

- Java Development Kit (JDK) 11 or later installed
- Apache Maven installed
- MySQL or another compatible database system

### Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/rustheviking/shopme.git
   ```
      ```bash
   cd shopme
   ```

2. Configure the database:

   - Create a new MySQL database named `shopmedb`.
   - Update the `application.properties` file with your database connection details.

3. Build the application:

   ```bash
   mvn install
   
   ```

4. Run the application:

   To run Back-End page
   ```bash 
   cd ShopmeProject/ShopmeWebParent/ShopmeBackEnd/target
   ```
      ```bash 
   java -jar ShopmeBackEnd-0.0.1-SNAPSHOT.jar
   ```

   To run Front-End page
   ```bash
   cd ShopmeProject/ShopmeWebParent/ShopmeFrontEnd/target
   ```
   ```bash
   java -jar ShopmeFrontEnd-0.0.1-SNAPSHOT.jar
   ```


## Usage

- Visit `http://localhost:8080/Shopme` in your web browser to access the Shopme - Ecommerce Web App.
- Register a new user account or log in with an existing account.
- Browse products, add items to your cart, and proceed to checkout.
- As an admin, log in to the admin dashboard `http://localhost:8082/ShopmeAdmin` to manage products and orders.

## Technologies

- Spring Boot
- Spring Security
- Thymeleaf (for server-side templating)
- MySQL (or your preferred database system)
- Bootstrap (for responsive design)

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or create a pull request.

1. Fork the repository.
2. Create a new branch for your feature/bug fix.
3. Make your changes and commit them with descriptive messages.
4. Push your changes to your fork.
5. Open a pull request describing your changes.

## License

This project is licensed under the [MIT License](LICENSE).

---

Happy coding! If you have any questions or need further assistance, feel free to contact us or open an issue. We hope this Shopme - eCommerce Web App project serves as a valuable resource for your Spring Boot development endeavors.
