# Authentik

Generate a strong `AUTHENTIK_SECRET_KEY` and database password before using this for real identity data.

The worker mounts the Docker socket because Authentik's official Compose stack uses it for Docker integrations. Remove that mount if you do not need those integrations.
