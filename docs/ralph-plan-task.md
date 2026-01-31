# ralph-plan-task

Interactive task planning command.

## Usage

```
/ralph-plan-task project#N
```

## Purpose

- Analyze task requirements
- Create implementation plan
- Get user approval

## Rules

- **Read-only** — no code changes
- **Interactive** — clarify with user
- **Plan goes to task** — stored in `plan` field

## Workflow

1. Get task from md-task-mcp
2. Enter plan mode
3. Analyze codebase
4. Ask clarifying questions
5. Write plan to task
6. Exit — do NOT implement

## Output

Plan includes: Scope, Steps, Testing, Code context.

## Links

- [Source](https://github.com/alexsteeel/.claude/blob/master/commands/ralph-plan-task.md)
