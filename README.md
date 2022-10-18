# n8n-selfhosted

Self-hosted n8n setup.

Requirements:
- NodeJS 18
- Yarn
- MySQL
- Redis
- Nginx reverse proxy, public domain with https


## Installation, setting up

1. Create corresponding configurations with real data for example files `config.example.json`, `config.webhook.example.json` and `.env.example` (by copying them to file without `.example` in name).
2. Setup systemd units for them (by example from `conf/systemd`).
3. Setup nginx configuration (by example from `conf/nginx`).


## Notes

- `yarn.lock` was not included intentionally.
- was tested with version 0.193.5.
