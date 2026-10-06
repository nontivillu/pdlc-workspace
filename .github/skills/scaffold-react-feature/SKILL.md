---
name: scaffold-react-feature
description: Use when adding a new React feature or screen that consumes the API.
---
1. Create `ui/src/features/<name>/{components,hooks,api,__tests__}`.
2. Use the generated API client and TanStack Query hooks.
3. Handle loading, empty, and error states; ensure accessibility.
4. Add Testing Library tests.
5. Run `npm test` and `npm run build`.
