# Refresh Tokens

Refresh tokens help issue new access tokens.

Common pattern:

- Short-lived access token
- Longer-lived refresh token
- Refresh endpoint
- Token rotation
- Logout invalidates refresh token

Security:

- Store refresh token securely.
- Rotate on use.
- Revoke on suspicious activity.

