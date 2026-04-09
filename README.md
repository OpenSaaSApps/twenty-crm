# twenty-crm

> Click To Deploy Twenty CRM — Open Source CRM built for the modern era

[![Sync](https://github.com/opensaasapps/twenty-crm/actions/workflows/sync.yml/badge.svg)](https://github.com/opensaasapps/twenty-crm/actions/workflows/sync.yml) [![Docker](https://github.com/opensaasapps/twenty-crm/actions/workflows/docker.yml/badge.svg)](https://github.com/opensaasapps/twenty-crm/actions/workflows/docker.yml) [![Docker Pulls](https://img.shields.io/docker/pulls/thefractionalpm/twenty-crm)](https://hub.docker.com/r/thefractionalpm/twenty-crm)

Upstream: [twentyhq/twenty](https://github.com/twentyhq/twenty) · Auto-synced daily

---

## One-Command Deploy

```bash
cp .env.example .env && nano .env
docker compose up -d
```

## Coolify / Dokploy

1. New service → **Docker Compose**
2. Paste `docker-compose.yml`
3. Set env vars in UI
4. Deploy

## Environment Variables

| Variable | Required | Description |
|---|---|---|
| `SERVER_URL` | ⚪ | |
| `PG_DATABASE_URL` | ⚪ | |
| `REDIS_URL` | ⚪ | |
| `ACCESS_TOKEN_SECRET` | ✅ | |
| `LOGIN_TOKEN_SECRET` | ✅ | |
| `REFRESH_TOKEN_SECRET` | ✅ | |
| `FILE_TOKEN_SECRET` | ✅ | |
| `STORAGE_TYPE` | ⚪ | |

## Image

```
docker pull twentycrm/twenty:latest
docker pull thefractionalpm/twenty-crm:latest
```

## Ports

| Port | Service |
|---|---|
| `3000` | Main app |

---

*Part of the [OpenSaaSApps](https://github.com/opensaasapps) Click-To-Deploy collection.*
