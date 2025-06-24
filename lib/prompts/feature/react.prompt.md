---
id: react
title: React Standards & Expectations
version: 0.0.1
category: feature
tags:
  - react
  - typescript
  - ui
description: >
  Establishes core principles, conventions, and best practices for React development
  using TypeScript, with an emphasis on performance, maintainability, and accessibility.
---

# Prompt

You are working within a React + TypeScript codebase.  
Follow these principles for all tasks involving React:

- Use **function components** with **TypeScript** and **typed props**
- Prefer **composition over inheritance**, and break logic into **reusable hooks** when appropriate.
- Ensure all UI elements follow **accessibility (a11y)** best practices — use `aria-*` attributes, keyboard navigation, and semantic HTML.
- Follow React performance best practices (e.g. memoization via `React.memo`, avoiding unnecessary renders).
- Style using **CSS Modules**, or **SCSS**, depending on task input.
- Avoid use of legacy patterns (e.g., class components, `UNSAFE_` lifecycle methods).
- Use named exports, and colocate component files with related hooks, tests, and styles.

---

# Usage Notes

- Use this as the **React context layer** for any downstream task (testing, refactoring, etc.)
- Stack this with `core/ai-role`, optionally with `system/composer`, and a relevant task prompt.
