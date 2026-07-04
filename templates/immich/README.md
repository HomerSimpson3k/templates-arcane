# Immich

This template follows the upstream Docker Compose layout for Immich and keeps media files and database files in separate host paths.

Keep `DB_DATA_LOCATION` on local SSD-backed storage. Immich upstream does not recommend network shares for PostgreSQL data. Hardware acceleration requires extra Compose sections from the Immich documentation and is intentionally not enabled by default here.
