# Token Verification Service for E-commerce Application

This project is a Token Verification Service for an e-commerce application. The Token Verification Service is designed to manage and verify user accounts through token-based authentication. By centralizing token verification, it ensures security and consistency in user authentication across the e-commerce platform.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Configuration](#configuration)
- [Running the Service](#running-the-service)
- [Contributing](#contributing)
- [License](#license)

## Overview

The Token Verification Service is a RESTful API built using Spring Boot. It provides endpoints for generating and verifying tokens used for user authentication. This service integrates with other microservices to ensure that only authenticated users can access protected resources.

## Features

- **Generate Tokens:** Allows the creation of new authentication tokens for users.
- **Verify Tokens:** Enables the verification of existing tokens to authenticate users.

## Prerequisites

- Java 17 or higher
- Maven 3.6.3 or higher
- Spring Boot 3 or higher

## Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/Agustin199811/token-service.git
    cd token-verification-service
    ```

2. Build the project using Maven:

    ```sh
    mvn clean install
    ```

## Configuration

The configuration for the Token Verification Service is located in `src/main/resources/application.properties`. Below is an example configuration:

```properties
spring.datasource.url=jdbc:mysql://your-database-url:3306/your-database
spring.datasource.username=your-username
spring.datasource.password=your-password

eureka.client.service-url.defaultZone=http://your-eureka-server-url/eureka/
eureka.client.register-with-eureka=true
eureka.client.fetch-registry=true
Running the Service
To run the Token Verification Service, use the following command:
```

## Running the Service

To run the service registry, use the following command:

 ```sh
    mvn spring-boot:run
```

## Contributing

Contributions are welcome! If you would like to contribute to this project, please send us an email at
`toapantaagustin9c@gmail.com` with details about your proposed changes or improvements. We look forward to hearing from you!

## License

This project is licensed under the MIT License - see the LICENSE file for details.
