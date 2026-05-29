# Dockerfile

Dockerfile defines image build steps.

Good practices:

- Use small base image.
- Copy only needed files.
- Use `.dockerignore`.
- Do not include secrets.
- Run as non-root when possible.
- Pin versions where useful.

