# AI-Powered Developer Toolkit

This document compiles 42 use cases for leveraging AI (LLMs) throughout the software development lifecycle, organized by functional category.

---

## 1. Project Understanding

This category helps new developers — or any team member — quickly get up to speed on a project without having to manually read through the entire codebase.

**1. Architecture document** — High-level overview of modules, components, and data flow across the system.

**2. Codebase onboarding** — Explains the project to a new developer, covering directory structure, core processing flows, and coding conventions.

**3. Dependency map** — Shows relationships between modules and the rationale behind each library choice.

**4. Tech stack summary** — Lists languages, frameworks, versions, and the reasoning behind each technology decision.

---

## 2. Code Generation

This category automates repetitive coding tasks, accelerating development speed and reducing human error.

**5. Boilerplate generator** — Scaffolds a new module, service, or component that matches the project's existing structure.

**6. CRUD generator** — Given a model, generates full create, read, update, and delete operations.

**7. API endpoint generator** — Produces a complete endpoint with route, handler, validation, and error handling.

**8. Test file generator** — Creates unit and integration tests from an existing source file.

**9. Type/interface generator** — Infers and generates type definitions from JSON, a DB schema, or sample data.

**10. Migration generator** — Generates a DB migration script when transitioning from an old schema to a new one.

---

## 3. Code Review & Analysis

This category helps surface hidden issues in code before they become real bugs in production.

**11. Code review checklist** — Covers security, performance, readability, and edge cases.

**12. Bug finder** — Identifies potential bugs or runtime errors lurking in the code.

**13. Dead code detector** — Finds unused variables, imports, and functions.

**14. Complexity analyzer** — Pinpoints overly complex functions and suggests ways to simplify them.

**15. Security audit** — Detects SQL injection, XSS, unvalidated input, and exposed secrets.

---

## 4. Refactoring

This category improves the quality of existing code without changing system behavior.

**16. Rename & restructure** — Applies consistent renaming across the entire codebase.

**17. Extract function/module** — Breaks large functions into smaller, single-responsibility units.

**18. Design pattern applier** — Refactors code to use patterns such as Strategy, Factory, Observer, etc.

**19. DRY enforcer** — Identifies and consolidates duplicated logic.

**20. Style converter** — Transforms code between styles: callback → Promise → async/await, class → functional, etc.

---

## 5. Testing

This category ensures high test coverage and better test quality through automated test case generation.

**21. Unit test writer** — Writes tests for a specific function, including important edge cases.

**22. Mock generator** — Generates mocks and stubs for external dependencies.

**23. Test case expander** — Suggests missing scenarios based on existing tests.

**24. E2E scenario writer** — Writes user flow test scenarios in Playwright or Cypress format.

---

## 6. Documentation

This category keeps documentation complete and up to date, reducing the documentation burden on developers.

**25. Architecture document** — A system-wide description intended for the engineering team and stakeholders.

**26. JSDoc / docstring writer** — Adds inline documentation to functions and classes.

**27. README generator** — Covers setup, usage, environment variables, and contribution guidelines.

**28. Changelog writer** — Generates structured release notes from a diff or list of commits.

**29. API reference doc** — Documents endpoints, parameters, and responses in OpenAPI or Markdown format.

**30. ADR (Architecture Decision Record)** — Captures the reasoning behind a significant architectural decision.

---

## 7. Debugging

This category shortens the time spent tracking down the root cause of an issue and provides concrete fix suggestions.

**31. Error explainer** — Paste in a stack trace, receive the root cause and a recommended fix.

**32. Log analyzer** — Detects anomalies or noteworthy patterns in log output.

**33. Reproduce case writer** — Writes a minimal reproduction from a bug description.

**34. Fix suggester** — Given a specific bug, proposes three different approaches to resolve it.

---

## 8. DevOps & Infrastructure

This category automates the creation of infrastructure configuration files that are typically tedious to write by hand.

**35. Dockerfile generator** — Produces an optimized Dockerfile for a given project.

**36. CI/CD pipeline writer** — Generates a GitHub Actions or GitLab CI pipeline from requirements.

**37. ENV variable auditor** — Lists and documents all required environment variables.

**38. Kubernetes manifest generator** — Scaffolds deployment, service, and ingress manifests for Kubernetes.

---

## 9. LLM Context Priming

This category optimizes working with AI across multiple sessions, ensuring no context is lost between conversations.

**39. Project context snapshot** — A compact summary of the entire project, ready to paste into a new session.

**40. "Continue from here" prompt** — Resumes a coding session with full context from where it left off.

**41. Role primer** — Sets a role for the AI, e.g., "Act as a senior engineer on this stack: …"

**42. Constraint setter** — Defines boundaries for the AI, e.g., "Only use the stdlib, no external dependencies."
