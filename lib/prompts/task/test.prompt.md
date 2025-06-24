---
id: generate-tests
title: Generate Unit & Integration Tests
version: 0.0.1
category: task
tags:
  - testing
  - unit
  - integration
description: >
  Generate well-structured and relevant unit or integration tests for the given code using preferred test libraries.
---

# Prompt

Generate comprehensive unit and/or integration tests for the following code.

Guidelines:

- Use preferred libraries (e.g., `jest`, `react-testing-library`, `vitest`)
- Cover edge cases, expected behavior, and failure modes
- Include appropriate mocks/stubs where necessary
- Follow naming and structuring conventions of the company

Include both the test file and brief explanation of what’s being tested.

---

# Usage Notes

- Input = function, component, hook, or API logic
- Stack with `feature/react`, `feature/typescript`, `core/testing-style` (if exists)
