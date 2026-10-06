---
name: scaffold-spring-endpoint
description: Use when adding a REST endpoint to the Spring Boot API.
---
1. Find the operation in `docs/api/openapi.yaml`.
2. Create request/response DTOs, controller, service, repository, and a Flyway migration if the schema changes.
3. Add validation and problem-details error handling.
4. Add controller slice tests and a Testcontainers integration test.
5. Run `./mvnw verify`.
