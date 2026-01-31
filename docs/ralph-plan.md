# ralph plan

CLI tool for interactive task planning.

## Usage

```bash
ralph plan <project> <task_numbers...>
```

## Example

```bash
ralph plan myproject 1 2 3
```

## Features

- Runs `/ralph-plan-task` for each task
- Interactive mode with user feedback
- Creates implementation plans
- Stores plans in task's `plan` field

## Workflow

For each task:
1. Analyze requirements
2. Ask clarifying questions
3. Create detailed plan
4. Get user approval
5. Move to next task

## Links

- [GitHub](https://github.com/alexsteeel/.claude/tree/master/cli)
