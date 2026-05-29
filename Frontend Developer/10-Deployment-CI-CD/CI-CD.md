# CI/CD

Frontend CI/CD flow:

```txt
Git push -> Install dependencies -> Lint -> Test -> Build -> Deploy preview -> Deploy production
```

Good pipeline:

- Runs checks on PR.
- Blocks broken builds.
- Creates preview links.
- Keeps secrets safe.

