# Mattermost

Mattermost notifications for the AI agents workflow, sent via the ralph-tasks API.

## Features

- Task completion notifications
- Blocked-task alerts (`status=hold`)
- Recovery failure alerts (API timeout, rate limit, overload)

## Usage

```bash
ralph notify "Message text"   # Send a message
ralph notify -t               # Send a test message
```

## Configuration

Set in `~/.claude/.env`:

```bash
RALPH_TASKS_API_URL="http://ai-sbx-ralph-tasks:8000"
RALPH_TASKS_API_KEY=""
```

## In Workflow

`ralph implement` sends a Mattermost alert when the recovery loop gives up
(all health checks fail) or when the pipeline is stopped, so a human can step in.

## Links

- [Mattermost](https://mattermost.com/)
