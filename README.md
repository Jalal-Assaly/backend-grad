# Graduation Project Backend System
#### Collaborators: [Ahmed Salah Shalabi](https://github.com/AhmedShalabi01) and [Jalal Assaly](https://github.com/Jalal-Assaly)
This repository contains the backend subsystem of the IoT physical access control system. Programmed using Java 17, Spring Boot, and MongoDB.

## Microservices

### [User Credentials API](https://github.com/Jalal-Assaly/user-credentials-api)
This microservice handles user credentials management service with basic CRUD operations. It provides endpoints for managing user credentials securely.

### [Company Data Gateway API](https://github.com/Jalal-Assaly/company-data-gateway-api)
The Company Data Gateway API serves as an interface for accessing and managing company-specific data within the physical access control system.

### [Visitor Management API](https://github.com/Jalal-Assaly/visitor-management-api)
This microservice performs and facilitates the management of visitors, including registration, check-in, and check-out functionalities.

### [Attributes Management API](https://github.com/AhmedShalabi01/attributes-management-api)
The Attributes Management API allows the management of various attributes associated with users and access points within the system.

### [User Login Registration API](https://github.com/AhmedShalabi01/user-login-registration-api)
This microservice handles user registration and login processes, providing endpoints for user account management.

### [Access Policy Management API](https://github.com/AhmedShalabi01/access-policy-management-api)
The Access Policy Management API is responsible for defining, managing and enforcing access control policies within the system.

### [CoAP Server API](https://github.com/Jalal-Assaly/coap-server-api)
This microservice implements a CoAP server using the Californium(Cf) library, providing an interface for communication with CoAP-enabled devices.

### [CoAP Client API](https://github.com/Jalal-Assaly/coap-client-emulator)
The CoAP Client Emulator allows communication with CoAP servers from within the system. Used to test the CoAP implementation of the CoAP server API.

### [Access Control API](https://github.com/Jalal-Assaly/access-control-api)
This microservice implements the core access control functionalities, including granting or denying access based on predefined access policies.

### [Admin Server API](https://github.com/Jalal-Assaly/admin-server-api)
The Admin Server API provides administrative functionalities for managing and monitoring the backend system performance. Uses Codecentric's Spring Admin Server dependency based upon Spring Actuator to reveal information endpoints such as the system's health, metrics, http traces and more.
