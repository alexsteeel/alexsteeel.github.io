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

| Variable | Default | Description |
|----------|---------|-------------|
| `WORKING_DIR` | `$(pwd)` | Working directory |
| `MAX_BUDGET` | unlimited | Budget per task |
| `MAX_RETRIES` | 3 | Retry attempts |
| `RETRY_DELAY` | 30 | Delay between retries |

## Links

- [GitHub](https://github.com/alexsteeel/.claude/tree/master/cli)
