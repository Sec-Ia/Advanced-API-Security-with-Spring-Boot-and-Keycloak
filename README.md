# Advanced API Security with Spring Boot and Keycloak

This project demonstrates how to integrate **Keycloak** with **Spring Boot** to secure API endpoints using OAuth2 and OpenID Connect. It provides role-based access control (RBAC) and robust authentication mechanisms for modern applications.

## Features
- Authentication and authorization using Keycloak.
- Role-based access control (RBAC).
- Token-based security for API endpoints.
- Integration with Docker for simplified deployment.

## Technology Stack
- **Spring Boot**
- **Keycloak**
- **Docker**
- **Java 17**

## Prerequisites
- **Java 17+**
- **Docker**
- **Maven**

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/username/Advanced-API-Security-with-Spring-Boot-and-Keycloak.git
   ```
2. Navigate to the project directory:
 ```bash
cd Advanced-API-Security-with-Spring-Boot-and-Keycloak
Build the project using Maven:
   ```
 ```bash
mvn clean install
   ```
3. Start Keycloak using Docker:
   ```bash
docker-compose up
   ```
4. Run the Spring Boot application:
 ```bash
mvn spring-boot:run
 ```
## Usage
-  Open Postman or any API client to send requests to protected endpoints. Use Keycloak to authenticate users and obtain tokens for API access.
Usage
-  Open Keycloak Admin Console and log in using the default admin credentials (admin/admin if unchanged).
-  Create a realm, client, and roles in Keycloak to configure your API authentication flow.
-  Use Postman or any API client to send requests to the protected endpoints.
-  Obtain a token from Keycloak by authenticating a user, and include the token in your API requests' Authorization header.

## Contribution
Contributions are welcome! Please fork the repository and submit a pull request for review.

## License
This project is licensed under the MIT License - see the LICENSE file for details.


