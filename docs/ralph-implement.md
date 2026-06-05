# ralph implement

CLI tool for autonomous task implementation.

## Usage

```bash
ralph implement <project> <task_numbers...>
```

## Example

```bash
ralph implement myproject 1 2 3
```

## Features

- Runs `/ralph-implement-python-task` for each task
- Autonomous mode (no user interaction)
- Auto-retries on API timeout
- Runs `/ralph-batch-check` after all tasks

## Options

| Flag | Description |
|------|-------------|
| `-w, --working-dir` | Working directory for Claude |
| `--max-budget` | Maximum budget in USD per task |
| `--no-recovery` | Disable automatic API recovery |

## Recovery (`~/.claude/.env`)

| Variable | Description |
|----------|-------------|
| `RECOVERY_ENABLED` | Enable automatic recovery |
| `TRANSIENT_DELAYS` | Delays for API timeout / overload |
| `RECOVERY_DELAYS` | Delays for rate limits |
| `CONTEXT_OVERFLOW_MAX_RETRIES` | Retries on context overflow |

## Links

- [GitHub](https://github.com/alexsteeel/.claude/tree/master/cli)
