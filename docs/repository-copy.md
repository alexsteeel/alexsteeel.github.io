# Repository Copy

Automated git worktree management in ai-agents-sandbox.

## Purpose

- Isolated copy per task
- No conflicts between parallel tasks
- Clean state for each agent session

## Automation

ai-agents-sandbox automatically:
1. Creates worktree for the task
2. Switches to the required branch
3. Mounts into devcontainer
4. Removes after completion

## Benefits

- Parallel task execution
- Change isolation
- Automatic cleanup

## Links

- [ai-agents-sandbox](https://github.com/alexsteeel/ai-agents-sandbox)
- [Git Worktree](https://git-scm.com/docs/git-worktree)
