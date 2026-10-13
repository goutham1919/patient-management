## Patient Management Microservices

A learning project that explores a patient management system built as a set of Spring Boot microservices. The repository includes separate service areas for patient management, billing, analytics, API requests, and gRPC requests.

> This is a learning project, not a production healthcare system. Do not use real patient information or credentials with it.

## Repository layout

- `patient-service/` — patient management service
- `billing-service/` — billing service
- `analytics-service/` — analytics service
- `api-requests/` — API request examples
- `grpc-requests/` — gRPC request examples

## Technologies explored

- Java and Spring Boot
- Microservices and REST APIs
- Docker and Docker Compose
- gRPC and Protocol Buffers
- Apache Kafka
- API Gateway
- Authentication and authorization

## Getting started

### Prerequisites

Install the versions required by the individual services and their configuration files:

- Java JDK
- Maven or Gradle, as used by each service
- Docker Desktop (for the containerized services and dependencies)

### Run the project

1. Clone the repository:

   ```bash
   git clone https://github.com/goutham1919/patient-management.git
   cd patient-management
   ```

2. Check the README and configuration files inside each service folder for its exact build command, port, and required environment variables.
3. Start any required databases or infrastructure using the Docker configuration provided in the repository.
4. Start the services in the order required by their configuration, then use the request examples in `api-requests/` and `grpc-requests/`.

> The exact startup commands and environment variables depend on the files in the repository. Add them here after confirming them against the service configuration.

## Configuration and secrets

Keep passwords, API keys, tokens, and local `.env` files out of Git. Use local environment variables or an untracked configuration file for private values. If a secret was already committed, revoke or rotate it; deleting the file in a later commit does not remove it from Git history.

## Learning goals

This project is intended to practice designing services that communicate through HTTP, gRPC, and Kafka, and running the services and their dependencies with Docker.

## License

No license is specified yet. Add a `LICENSE` file before presenting this repository as open source.


