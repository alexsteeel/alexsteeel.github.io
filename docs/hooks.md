# Hooks

Workflow automation hooks for Claude Code.

## Available Hooks

| Hook | Purpose |
|------|---------|
| check_workflow.py | Controls /execute-python-task |
| check_workflow_ralph.py | Controls /ralph-implement |
| enforce_isolated_skills.py | Skill isolation |
| notify.sh | Desktop notifications |

## Location

```
~/.claude/hooks/
├── check_workflow.py
├── check_workflow_ralph.py
├── enforce_isolated_skills.py
├── hook_utils.py
└── notify.sh
```

## Example: check_workflow_ralph.py

```python
CONFIRMATION_PHRASE = "i confirm that all task phases are fully completed"

# Blocks stop until Claude confirms completion
# Allows stop on hold (## Blocks + status=hold)
```

## Hook Types

- **PreToolUse** — before tool execution
- **PostToolUse** — after tool execution
- **Stop** — before session ends

## Links

- [Claude Code Hooks](https://docs.anthropic.com/en/docs/claude-code)
