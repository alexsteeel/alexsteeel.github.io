# create-tasks

Create tasks from notes/ideas.

## Usage

```
/create-tasks "note1, note2, note3"
```

## Workflow

1. Parse notes list
2. Quick analysis
3. Clarify with user
4. Create tasks via md-task-mcp
5. Show summary

## Features

- Auto-detects format (lines, numbers, commas)
- Suggests grouping related tasks
- Batch clarification questions

## Output

```
✅ Created N tasks:

| # | Task | Description |
|---|------|-------------|
| 1 | proj#5 | Add export |
| 2 | proj#6 | Fix bug |
```
