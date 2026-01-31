# ralph-batch-check

Post-batch test verification command.

## Usage

```
/ralph-batch-check project#1 project#2 ...
```

## Purpose

Runs after batch of tasks to catch:
- Indirect test failures
- Cross-task regressions
- Integration issues

## Workflow

1. Run full test suite
2. Identify failures
3. Fix or create new tasks
4. Report results

## Links

- [Source](https://github.com/alexsteeel/.claude/blob/master/commands/ralph-batch-check.md)
