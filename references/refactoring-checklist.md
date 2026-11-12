# Refactoring Checklist

Use this checklist before and after a focused simplification.

## Before editing
- [ ] Confirm the requested scope and identify changed files.
- [ ] Read repository instructions and nearby implementations.
- [ ] Trace callers, inputs, outputs, side effects, and error paths.
- [ ] Identify behavior that must remain unchanged.
- [ ] Check existing tests and choose the narrowest relevant verification.

## During editing
- [ ] Prefer the smallest coherent change.
- [ ] Preserve API contracts, ordering, exceptions, and side effects.
- [ ] Keep project naming, formatting, and architectural conventions.
- [ ] Avoid new dependencies and abstractions without clear value.
- [ ] Leave unrelated files untouched.

## After editing
- [ ] Review the complete diff.
- [ ] Check edge cases and error handling.
- [ ] Run relevant tests, lint, type checks, or build commands.
- [ ] Compare behavior-sensitive paths with the original implementation.
- [ ] Report exact checks and any remaining uncertainty.
