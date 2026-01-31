# Code and Tests

Source code and test suite in agents-native repository.

## Structure

```
project/
├── src/           # Source code
├── tests/         # Test suite
│   ├── unit/      # Unit tests
│   ├── api/       # API tests
│   └── ui/        # UI tests (Playwright)
└── services/      # Microservices
```

## Test Types

| Type | Purpose |
|------|---------|
| Unit | Functions, methods |
| API | Endpoints, auth |
| UI | Browser, forms |

## Requirements

- All tests must pass
- No skipped tests
- Edge cases covered
