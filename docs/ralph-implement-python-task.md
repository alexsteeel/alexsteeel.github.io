# ralph-implement-python-task

Autonomous Python task implementation command.

## Usage

```
/ralph-implement-python-task project#N
```

## Prerequisites

- Task must have `## Plan` section
- No user interaction during execution

## Workflow (12 phases)

0. Validate Task
1. Update Task (status=work)
2. Read Plan Context
3. Implementation
4. Initial Testing
5. UI Review
6. Reviews (`ralph review`)
7. Final Testing
8. Linters
9. Cleanup
10. Documentation
11. Complete (commit + report)

## Key Rules

- **No AskUserQuestion** — fully autonomous
- **All tests must pass** — no skipped tests
- **All reviews processed** — Fixed/Deferred/Declined
- **On block** → WIP commit + status=hold + exit
