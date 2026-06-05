# Codex CLI

OpenAI's CLI tool for code tasks.

## Features

- Code generation
- Code review
- Bug fixing
- Refactoring suggestions

## Models

- `gpt-5.5-codex` — latest model
- Reasoning effort: low/medium/high/xhigh

## Usage

```bash
codex review \
  -c 'profiles.review.model="gpt-5.5-codex"' \
  -c 'profiles.review.model_reasoning_effort="xhigh"' \
  "Review git changes"
```

## Integration

Used by `/codex-review` command for automated reviews.

## Links

- [GitHub](https://github.com/openai/codex)
- [npm](https://www.npmjs.com/package/@openai/codex)
