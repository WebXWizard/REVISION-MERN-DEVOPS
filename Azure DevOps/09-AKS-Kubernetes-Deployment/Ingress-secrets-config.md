# Ingress, Secrets, And Config

Ingress:

- Routes HTTP or HTTPS traffic into the cluster.

ConfigMap:

- Stores non-secret configuration.

Secret:

- Stores sensitive values.

Good practice:

- Keep secrets out of Git.
- Use Key Vault integration where possible.
- Use separate values per environment.

