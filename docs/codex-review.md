# codex-review

Automated code review using Codex CLI.

## Usage

```
/codex-review project#N
```

## Features

- Uses `gpt-5.2-codex` with `xhigh` reasoning
- Iterative review with fixes
- UI verification via Playwright
- Results in task's `review` field

## Severity Levels

| Level | Action |
|-------|--------|
| CRITICAL | Must fix |
| HIGH | Must fix |
| MEDIUM | Should fix |
| LOW | Optional |

## Checks

- Requirements compliance
- Security (SQLi, XSS, CSRF)
- Business logic
- Test coverage
- Code quality
- UI verification

## Links

- [Source](https://github.com/alexsteeel/.claude/blob/master/commands/codex-review.md)
