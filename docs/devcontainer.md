# .devcontainer

VS Code Dev Container configuration for isolated development.

## Features

- Docker Compose based environment
- Isolated infrastructure (Postgres, Redis, MinIO)
- Pre-configured Claude Code
- User: `claude` (not root)

## Structure

```
.devcontainer/
├── devcontainer.json    # VS Code config
├── docker-compose.base.yaml
├── docker-compose.override.yaml
└── init.sh
```

## Key Settings

| Setting | Value |
|---------|-------|
| User | claude |
| Workspace | /workspace |
| Node memory | 4GB |

## Links

- [Dev Containers Spec](https://containers.dev/)
- [ai-agents-sandbox](https://github.com/alexsteeel/ai-agents-sandbox)
