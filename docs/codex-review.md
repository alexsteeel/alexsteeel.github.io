# codex-review

Automated code review using Codex CLI.

Runs automatically as a review→fix→re-review loop at the CLI level after
`ralph implement` completes a task — the `/codex-review` slash command is
the manual fallback and is not normally invoked by hand.

## Usage

```
/codex-review project#N
```

## Features

- Uses `gpt-5.5-codex` with `xhigh` reasoning
- Iterative loop (up to 3 iterations) with `claude --resume` fixes
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
