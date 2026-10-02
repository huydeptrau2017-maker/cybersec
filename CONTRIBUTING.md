# Contributing

## Workflow

1. Update local `main`.
2. Create a focused branch such as `docs/http-cookies`.
3. Make one coherent change.
4. Review `git diff` and ensure no secrets are included.
5. Commit with a clear message.
6. Open a pull request and merge only after reviewing the diff.

## Commit examples

```text
docs(web): add HTTP cookie notes
docs(linux): document file permissions
feat(script): add URL parser
fix(crypto): correct XOR example
chore: update gitignore
```

## File naming

- Use lowercase kebab-case: `http-request-basics.md`.
- Give each document one clear subject.
- Keep generated exports separate from editable source files.
- Do not commit passwords, tokens, private keys, personal data, or live credentials.

## Walkthrough publication

Publish a solution only when the platform permits it and the competition has ended. Remove reusable credentials and sensitive target information before publishing.

