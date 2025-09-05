# 📘 Conventional Commits Guide

## What are Conventional Commits?

Conventional Commits is a standard for writing commit messages that follow a consistent structure. This makes your git history easier to read and enables automation (like changelog generation and semantic versioning).

---

## 📝 Commit Message Format

Each commit message should follow this structure:

```
<type>[optional scope]: <description>

[optional body]

[optional footer(s)]
```

### Example:

```
feat(auth): add JWT-based login functionality
```

---

## 🔑 Commit Types

### 1. `feat` – New Feature

A **new feature** for the user or the system. Use this when you add something that did not exist before.  
✅ Adds value to users or stakeholders.

```
feat(api): add pagination to account list
feat(ui): implement dark mode toggle
```

### 2. `fix` – Bug Fix

A **bug fix**. Use this when you resolve an error, crash, or incorrect behavior.  
✅ Always improves correctness of existing functionality.

```
fix(billing): correct invoice total calculation
fix(auth): handle null reference when user session expires
```

### 3. `docs` – Documentation Only

Changes to **documentation only**. No code behavior is changed.  
✅ Great for README updates, API docs, or in-code documentation.

```
docs(readme): add guide for conventional commits
docs(api): update usage examples for account endpoint
```

### 4. `style` – Code Style

Changes that do **not affect code logic**, only formatting or styling.  
✅ Covers whitespace, formatting, missing semicolons, indentation, or style rules.

```
style: format code with Prettier
style(ui): fix spacing in login form
```

### 5. `refactor` – Code Refactoring

Restructuring or rewriting existing code without changing its **external behavior**.  
✅ Makes code cleaner, easier to read, or maintainable.

```
refactor(service): extract billing logic into helper function
refactor(auth): simplify JWT validation
```

### 6. `perf` – Performance Improvements

A change that improves the **performance** of the application.  
✅ Optimizations that make things faster or reduce memory/CPU usage.

```
perf(api): optimize SQL query for account retrieval
perf(ui): reduce bundle size by lazy loading routes
```

### 7. `test` – Adding or Updating Tests

Changes that add or improve **tests**.  
✅ Helps ensure correctness, but doesn’t change runtime behavior.

```
test(auth): add unit tests for login handler
test(api): improve coverage for billing endpoint
```

### 8. `chore` – Maintenance Tasks

Routine tasks that do not affect user-facing features.  
✅ Covers dependency updates, build scripts, CI/CD pipelines, configs.

```
chore(deps): update to latest ASP.NET Core version
chore(ci): add GitHub Actions workflow for testing
```

---

## ✅ Best Practices

- Keep descriptions short and clear (≤ 50 characters).
- Use the imperative mood (e.g., _add_ instead of _added_).
- Add details in the body if needed.
- Use a **scope** (inside parentheses) to clarify the area (optional).

---

Happy committing! 🚀
