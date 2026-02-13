# telemt-docker

Docker setup for [telemt](https://github.com/telemt/telemt).

- [English](#english)
- [Русская версия](#русская-версия)

## English

### Quick start

```bash
git clone https://github.com/telemt/telemt-docker.git
cd telemt-docker
# put your settings into config.toml
docker compose up -d
```

To watch logs:
```bash
docker compose logs -f
```

### What’s inside

- **Dockerfile** — multi-stage build, runs as non-root
- **docker-compose.yml** — dropped caps, read-only filesystem
---

## Русская версия

### Быстрый старт

```bash
git clone https://github.com/telemt/telemt-docker.git
cd telemt-docker
# правишь config.toml под себя
docker compose up -d
```

Логи:
```bash
docker compose logs -f
```

### Что внутри

- **Dockerfile** — многоэтапная сборка, запуск от имени непривилегированного пользователя
- **docker-compose.yml** — минимум прав, файловая система в режиме только чтение
