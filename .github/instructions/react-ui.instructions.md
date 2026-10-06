---
description: React UI conventions
applyTo: "ui/**/*.{ts,tsx}"
---
- TypeScript strict; function components and hooks only.
- Use TanStack Query for server state and the API client generated from `docs/api/openapi.yaml`.
- Feature-based folders: `src/features/<name>/{components,hooks,api,__tests__}`.
- Accessible by default (semantic HTML, labels, keyboard support).
- Test with Vitest and Testing Library; query by role.
