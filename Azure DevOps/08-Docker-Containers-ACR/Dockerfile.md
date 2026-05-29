# Dockerfile

A Dockerfile defines how to build a container image.

Basic example:

```dockerfile
FROM node:20-alpine
WORKDIR /app
COPY package*.json ./
RUN npm ci
COPY . .
CMD ["npm", "start"]
```

Good practices:

- Use small base images.
- Do not copy secrets.
- Use `.dockerignore`.
- Pin versions where useful.
- Run as non-root when possible.

