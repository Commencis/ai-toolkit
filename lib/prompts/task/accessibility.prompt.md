---
id: accessibility-check
title: Accessibility Audit
version: 0.0.1
category: task
tags:
  - accessibility
  - a11y
  - semantic
description: >
  Analyze a component or page for accessibility issues and suggest improvements 
  following WCAG and best practices.
---

# Prompt

You're reviewing a React component or UI snippet for accessibility.  
Carefully audit the code and provide actionable suggestions, aligned with WCAG and common best practices.

Checklist:

- Are all interactive elements keyboard-accessible?
- Are `aria-*` attributes used appropriately?
- Are semantic HTML elements used instead of `div`/`span`?
- Is color contrast acceptable?
- Are labels and roles clearly defined?

Be concise but thorough. Return a list of findings and fixes.

---

# Usage Notes

- Input = code snippet of the component or page
- Stack with `feature/react`, optionally with a11y-ruleset (if available)
