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

For new features.

```
feat(api): add pagination to account list
feat(ui): implement dark mode toggle
```

### 2. `fix` – Bug Fix

For bug fixes.

```
fix(billing): correct invoice total calculation
fix(auth): handle null reference when user session expires
```

### 3. `docs` – Documentation Only

For documentation changes.

```
docs(readme): add guide for conventional commits
docs(api): update usage examples for account endpoint
```

### 4. `style` – Code Style

Code formatting changes, no logic impact.

```
style: format code with Prettier
style(ui): fix spacing in login form
```

### 5. `refactor` – Code Refactoring

Restructuring code without changing behavior.

```
refactor(service): extract billing logic into helper function
refactor(auth): simplify JWT validation
```

### 6. `perf` – Performance Improvements

Improving performance.

```
perf(api): optimize SQL query for account retrieval
perf(ui): reduce bundle size by lazy loading routes
```

### 7. `test` – Adding or Updating Tests

For test changes.

```
test(auth): add unit tests for login handler
test(api): improve coverage for billing endpoint
```

### 8. `chore` – Maintenance Tasks

Tooling, CI/CD, dependencies, etc.

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
