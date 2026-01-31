# Security Checks

Security review in workflow.

## Checks

| Category | Examples |
|----------|----------|
| Injection | SQL, XSS, Command |
| Auth | Missing checks, weak tokens |
| Secrets | Hardcoded credentials |
| Input | Missing validation |

## In Workflow

Part of Phase 6 Reviews via `ralph review`.

## Severity

- **CRITICAL** — must fix immediately
- **HIGH** — must fix before merge
- **MEDIUM** — should fix
- **LOW** — optional
