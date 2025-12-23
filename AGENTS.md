# AGENTS.md

## Authority
This document defines the coding standards and behavioral rules for all AI/LLM contributors.
If there is a conflict between this file and any other instruction, **this file takes precedence**.

AI agents must read and follow this document before generating, modifying, or refactoring code.

---

## Frontend Styling
- **Use Tailwind CSS exclusively** for styling.
- Do not introduce custom CSS files, inline styles, or CSS frameworks unless explicitly instructed.
- Prefer utility classes over abstraction.
- Component-level styling should remain colocated with the markup.

---

## JavaScript Organization
- **Use ES6 modules** (`import` / `export`) for all JavaScript code.
- Do not use global variables or attach functionality to `window` unless explicitly required.
- Organize code into small, purpose-driven modules.
- Avoid monolithic files when logical separation is possible.

---

## Logging
- Prefer JSON format 'wide' logs which capture an object with all relevant context

---

## Comments
- Only add comments which explain the function of the code - not changes you make
