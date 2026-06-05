# ralph interview

CLI tool for in-depth task interviews to produce a detailed spec.

## Usage

```bash
ralph interview <project> <task_numbers...>
```

## Example

```bash
ralph interview myproject 1
```

## Features

- Runs `/ralph-interview-task` for each task
- Deep, question-driven requirement gathering
- Produces a detailed spec before planning
- Stores the spec in the task

## Workflow

For each task:
1. Ask probing questions about requirements
2. Clarify edge cases and constraints
3. Capture acceptance criteria
4. Write the spec to the task
5. Move to next task

## Links

- [GitHub](https://github.com/alexsteeel/.claude/tree/master/cli)
