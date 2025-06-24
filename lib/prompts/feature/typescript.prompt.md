---
id: typescript
title: TypeScript Standards & Expectations
version: 0.0.1
category: feature
tags:
  - typescript
  - typing
  - ts-best-practices
description: >
  Establishes expected TypeScript usage conventions including strong typing, safety,
  generics, and clean patterns that match company standards.
---

# Prompt

You are working in a modern TypeScript codebase that prioritizes safety, readability, and maintainability.  
Follow these standards when writing, editing, or reviewing TypeScript:

- Prefer **explicit and strict typing**; avoid `any` unless absolutely necessary
- Use **`type` aliases** over `interface` unless extension is required
- Leverage **utility types** (`Partial`, `Omit`, `Pick`, etc.) when shaping types
- Use **generics** in reusable functions, components, or hooks
- Avoid complex nested types — extract named types for readability
- Always annotate return types for exported functions
- Use **discriminated unions** instead of flags when modeling variation
- Prefer **readonly** modifiers and immutability where possible
- Follow the company’s ESLint & Prettier standards for formatting and naming

---

# Usage Notes

- Can be stacked with `core/ai-role`, `feature/react`, or any `task/` prompt
- Use as a base context when generating or reviewing any TS-based logic or definitions
