# Sandbox

Isolated development environment for AI agents.

## Purpose

- Safe code execution
- Isolated infrastructure
- Reproducible environment
- No access to host system

## Components

- **Dev Container** — VS Code development environment
- **Infrastructure** — Postgres, Redis, MinIO
- **Repository copy** — git worktree for isolation
- **Claude Code** — AI agent CLI

## Security

- Runs as non-root user (`claude`)
- Network isolated from host
- File system sandboxed
- No sudo access

## Links

- [ai-agents-sandbox](https://github.com/alexsteeel/ai-agents-sandbox)
