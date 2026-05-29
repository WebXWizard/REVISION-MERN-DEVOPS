# State And Workspaces

Terraform state tracks real infrastructure.

Important:

- Store state remotely.
- Lock state during changes.
- Restrict state access.
- Avoid editing state manually.
- Separate environments carefully.

Workspaces can separate environments, but many teams prefer separate state backends per environment for clarity.

