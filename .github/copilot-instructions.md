---
description: "Global coding style for this Next.js + TypeScript project"
---

# Global Style

- Always use arrow functions for components, hooks, and utilities.
- Prefer Server Components by default. Use `"use client"` only if browser APIs or interactivity are required.

# Naming Conventions

- React components: **PascalCase** (e.g. `UserCard.tsx` → `UserCard`).
- Hooks: **camelCase** with `use` prefix (e.g. `useUserData`).
- Utility functions & variables: **camelCase**.
- TypeScript types & interfaces: **PascalCase** (e.g. `UserProfile`).
- Files: **kebab-case** (e.g. `user-card.tsx`, `use-user-data.ts`).
- Constants: **UPPER_SNAKE_CASE** (e.g. `DEFAULT_TIMEOUT_MS`).
