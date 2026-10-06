---
description: Testing standards
applyTo: "**/*{Test,.test,.spec}.*"
---
- Arrange-Act-Assert; one behavior per test; descriptive names.
- Cover acceptance criteria from `docs/requirements/` explicitly.
- No real network or shared state; use fakes or Testcontainers.
