# Markdown Tasks (md-task-mcp)

MCP server for markdown-based task management.

## Features

- Task CRUD via MCP tools
- CLI tool `tm` for terminal access
- Web UI at localhost:8080
- File-based storage in `~/.md-task-mcp/`

## MCP Tools

| Tool | Description |
|------|-------------|
| `tasks()` | List all projects |
| `tasks(project)` | List tasks in project |
| `tasks(project, N)` | Get task details |
| `create_task(...)` | Create new task |
| `update_task(...)` | Update task fields |

## CLI Commands

```bash
tm p              # List projects
tm t              # Tree view of tasks
tm t list <proj>  # List project tasks
tm t add <proj>   # Add task
tm t open <proj> N  # Edit task in editor
```

## Links

- [GitHub](https://github.com/alexsteeel/md-task-mcp)
