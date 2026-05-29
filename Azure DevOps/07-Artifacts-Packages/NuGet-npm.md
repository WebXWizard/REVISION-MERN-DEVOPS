# NuGet And npm

NuGet:

- Common for .NET packages.

npm:

- Common for JavaScript and Node.js packages.

Pipeline flow:

```txt
Build library -> Run tests -> Version package -> Publish to feed -> Consume in app pipeline
```

Security:

- Avoid publishing secrets.
- Control who can publish.
- Scan dependencies where possible.

