# Agents-native Repository

Repository structure optimized for AI agents.

## Components

| Component | Description |
|-----------|-------------|
| Code, tests | Source code and test suite |
| CLAUDE.md | Instructions for Claude |
| .devcontainer | Dev environment config |

## Structure

```
project/
├── CLAUDE.md           # Agent instructions
├── .devcontainer/      # Dev container config
├── src/                # Source code
├── tests/              # Test suite
└── services/           # Microservices
    └── */CLAUDE.md     # Service-specific instructions
```

## CLAUDE.md

Instructions file that Claude Code reads automatically. Contains:
- Project conventions
- Build/test commands
- Known issues and solutions

## Links

- [ai-agents-sandbox](https://github.com/alexsteeel/ai-agents-sandbox)
