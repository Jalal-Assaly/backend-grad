# Backend-Grad

This repository contains the backend subsystem of the IoT physical access control system. Programmed using Java 17, Spring Boot, and MongoDB.

## Microservices

### [User credentials API](https://github.com/Jalal-Assaly/user-credentials-api)

This microservice handles user authentication and authorization. It provides endpoints for managing user credentials securely.

### Company Data Gateway API
The Company Data Gateway API serves as an interface for accessing and managing company-specific data within the system.

### Visitor Management API
This microservice facilitates the management of visitors, including registration, check-in, and check-out functionalities.

### Attributes Management API
The Attributes Management API allows the management of various attributes associated with users and entities within the system.

### User Login Registration API
This microservice handles user registration and login processes, providing endpoints for user account management.

### Access Policy Management API
The Access Policy Management API is responsible for defining and enforcing access control policies within the system.

### CoAP Server API
This microservice implements a CoAP server, providing an interface for communication with CoAP-enabled devices.

### CoAP Client API
The CoAP Client API allows communication with CoAP servers from within the system, enabling interaction with CoAP-enabled devices.

### Access Control API
This microservice implements the core access control functionalities, including granting or denying access based on predefined policies.

### Admin Server API
The Admin Server API provides administrative functionalities for managing and monitoring the backend system.
