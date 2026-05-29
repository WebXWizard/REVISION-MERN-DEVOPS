# Release Strategies

Common strategies:

- Rolling deployment
- Blue-green deployment
- Canary deployment
- Feature flag release

Canary release:

- Send small traffic percentage to new version.
- Watch metrics.
- Increase traffic if healthy.
- Roll back if errors rise.

Blue-green release:

- Keep old and new environments.
- Switch traffic when new version is verified.

