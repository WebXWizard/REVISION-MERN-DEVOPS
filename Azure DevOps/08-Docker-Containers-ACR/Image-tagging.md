# Image Tagging

Good image tags help trace deployments.

Useful tags:

- Build ID
- Git commit SHA
- Semantic version
- Environment tag

Avoid:

- Only using `latest` for production deployments.

Good practice:

```txt
Deploy immutable image tags so you know exactly what version is running.
```

