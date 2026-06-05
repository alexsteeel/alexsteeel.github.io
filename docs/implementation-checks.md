# Implementation Checks

Hook that validates task completion.

## Purpose

Ensures all workflow phases are completed before task closes.

## Checks

- All workflow phases (0–12) executed
- Tests passing
- Reviews processed
- Linters clean
- Cleanup done

## Confirmation

Requires phrase before completion:
```
I confirm that all task phases are fully completed.
```

## On Failure

- Blocks session stop
- Shows checklist of missing items
