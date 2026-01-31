# Infrastructure

Isolated infrastructure services for development sandbox.

## Services

| Service | Purpose |
|---------|---------|
| PostgreSQL | Database |
| Redis | Caching, queues |
| MinIO | S3-compatible storage |

## Docker Compose

All services run in docker compose alongside devcontainer.

## Network

Services communicate via internal docker network, isolated from host.

## Links

- [PostgreSQL](https://www.postgresql.org/)
- [Redis](https://redis.io/)
- [MinIO](https://min.io/)
