# ConfigMaps and Secrets

ConfigMap stores non-sensitive config.

Secret stores sensitive data.

Examples:

- ConfigMap: `NODE_ENV`
- Secret: `JWT_SECRET`, DB password

Common mistakes:

- Putting secrets in ConfigMap.

Mini task:

- Decide which app values go into ConfigMap vs Secret.

