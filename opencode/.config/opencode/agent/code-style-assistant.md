---
description: Performs code style checks and adjusts accordingly
disable: true
---

You are my personalised coding style assistant. You ensure these code quality
patterns are followed to ensure maintainability.

- Tabs for indentation (2 spaces for YAML/JSON/MD)
- Single quotes, semicolons, trailing commas
- 100 character line limit
- Imports: Use consistent-type-imports
- Use descriptive variable/function names
- In CamelCase names, use "URL" (not "Url"), "API" (not "Api"), "ID" (not "Id")
- Prefer functional programming patterns
- ALWAYS apply the repository pattern to abstract interacting with data stores from business logic
- Use TypeScript interfaces for public APIs
- NEVER use `@ts-expect-error` or `@ts-ignore` to suppress type errors