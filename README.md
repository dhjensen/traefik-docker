# traefik-docker

[Traefik](https://github.com/traefik/traefik) reverse proxy docker compose

## .env example

```bash
TRAEFIK_VERSION=3.5.4
CF_API_EMAIL=dhjen@outlook.com
CF_DNS_API_TOKEN=token
CF_ZONE_API_TOKEN=token
DASHBOARD_USERS=User hash
DASHBOARD_FQDN="traefik.dhjensen.tech"
IPALLOWLIST='192.168.86.0/24,172.23.0.1,79.76.106.250'
```

## traefik.yml

Static Traefik configuration

## dynamic/traefik-dynamic.yml

Dynamic Traefik configuration
