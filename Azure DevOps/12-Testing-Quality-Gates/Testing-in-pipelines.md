# Testing In Pipelines

Common pipeline tests:

- Unit tests
- Integration tests
- End-to-end tests
- Smoke tests
- Security tests

Good flow:

```txt
Install dependencies -> Run lint -> Run unit tests -> Build -> Run integration tests -> Publish reports
```

Fail fast:

- Run faster checks earlier.
- Stop pipeline when critical tests fail.

