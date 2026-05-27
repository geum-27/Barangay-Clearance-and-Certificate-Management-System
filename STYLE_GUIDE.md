# Team Style Guide
Barangay Clearance and Certificate Management System

## 2.1 Naming Conventions

| Element | Convention | Example |
|----------|------------|----------|
| Variables | camelCase | appointmentId, residentName |
| Functions / Methods | camelCase | generateReferenceNumber(), approveAppointment() |
| Classes | PascalCase | DatabaseConnection, DashboardMetrics |
| Files | kebab-case | staff-login.html, main-dashboard.html |
| Constants | UPPER_SNAKE_CASE | DB_HOST, STR_PAD_LEFT |
| Database tables / fields | snake_case | appointment_statuses, reference_number |

---

## 2.2 Formatting Rules

| Rule | Team Decision |
|------|---------------|
| Indentation | 4 spaces |
| Line length limit | max 120 characters |
| Brace style | One True Brace Style (1TBS) |
| Spaces vs tabs | Spaces only |
| Blank lines between functions | Exactly 1 blank line |
| Max function length | 30 lines |

---

## 2.3 Commenting Standards

| Commenting Rule | Team Standard |
|----------------|---------------|
| File/module header comment | Multi-line comment documenting module purpose and system layer (frontend/backend/database) |
| Function/method doc comment | Structural PHPDoc standard summarizing inputs, outputs, and behaviors |
| Inline comments | Only for non-obvious logic calculations or contextual step workflows |
| TODO comment format | `// TODO: description of feature modification` |
| Language for comments | English (Professional / Technical phrasing) |

---

## 2.4 Branch Naming Strategy

| Branch Type | Naming Format | Example |
|-------------|---------------|---------|
| Feature branch | feature/<short-desc> | feature/staff-dashboard |
| Bug fix branch | bugfix/<issue-id-desc> | bugfix/fix-modal-overflow |
| Hotfix branch | hotfix/<emergency-desc> | hotfix/session-timeout-leak |
| Release branch | release/v<version-num> | release/v1.0.0 |

---

## Commit Message Format

Format:

```txt
<type>(<scope>): <short description>
```

Example:

```txt
feat(auth): add password reset flow
```

Allowed types:

- feat → New features
- fix → Bug fixes
- docs → Documentation changes
- style → Formatting only
- refactor → Code restructuring
- test → Tests
- chore → Maintenance/configuration

---

Prepared for: Software Engineering — Lab Worksheet 10