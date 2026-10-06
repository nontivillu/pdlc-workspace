# Project Instructions

## Repo map
- `ui/` React + TypeScript (Vite)
- `api/` Spring Boot 3, Java 21, Maven
- `docs/requirements/`, `docs/adr/`, `docs/api/` (OpenAPI is the source of truth), `docs/test-plans/`

## Commands
- UI: `cd ui && npm ci && npm test && npm run build`
- API: `cd api && ./mvnw verify`

## Rules
- The OpenAPI spec in `docs/api/openapi.yaml` is the contract; UI and API both code against it.
- Do not change the contract without going through the Architect agent.
- Conventional commits; small PRs; every change ships with tests.
- Definition of done: build passes, tests pass, no new lint issues, docs updated.
