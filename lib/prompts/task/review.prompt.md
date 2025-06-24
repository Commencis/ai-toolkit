---
id: code-review
title: Code Review Feedback
version: 0.0.1
category: task
tags:
  - review
  - readability
description: >
  Provide structured and constructive code review feedback focusing on clarity, structure, maintainability, and standard alignment.
---

# Prompt

You are reviewing the following code as a senior software engineer.  
Offer high-quality, professional feedback focusing on:

- Readability and naming
- Logic and performance
- TypeScript usage and type safety
- Code structure and reusability
- Alignment with company coding standards

Return a structured list of review points grouped as:  
**Suggestions**, **Potential Issues**

---

# Usage Notes

- Input = any file or diff
- Combine with `core/ai-role` and tech-specific `feature/` prompts
