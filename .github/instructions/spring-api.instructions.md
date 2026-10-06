---
description: Spring Boot API conventions
applyTo: "api/**/*.java"
---
- Layers: controller -> service -> repository; no business logic in controllers.
- Separate DTOs from JPA entities; constructor injection only.
- Validate input with Bean Validation; return RFC 7807 problem details via `@ControllerAdvice`.
- Schema changes via Flyway migrations only.
- Integration tests use Testcontainers.
