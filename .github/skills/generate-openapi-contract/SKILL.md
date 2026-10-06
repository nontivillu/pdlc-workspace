---
name: generate-openapi-contract
description: Use when defining or updating REST endpoints in the OpenAPI spec from requirements.
---
1. Read the requirements in `docs/requirements/`.
2. Update `docs/api/openapi.yaml` (OpenAPI 3.1) with paths, schemas, operationIds, error responses, and examples.
3. Keep changes additive; record breaking changes in an ADR.
4. Summarize the contract delta for the UI and API developers.
