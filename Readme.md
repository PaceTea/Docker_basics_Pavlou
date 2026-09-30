# Docker Grundlagen inkl. Docker Compose

Repo für die Abgabe "Docker Grundlagen inkl. Docker Compose" (Einführung in die Docker-Welt).

## Struktur

```
|-Readme.md
|-pihole
  |-pihole.yml
|-portainer
  |-portainer.yml
|-watchtower
  |-watchtower.yml
|-nginx
  |-nginx.yml
  |-html
    |-index.html
```

## Setup

1. Repo klonen
2. Docker / Docker Desktop installieren
3. Compose-Dateien nacheinander starten, z.B.:
   ```
   docker compose -f pihole/pihole.yml up -d
   ```
4. Laufende Container prüfen: `docker ps`
5. Über die jeweilige Webschnittstelle einloggen

| Dienst     | Adresse                      |
|------------|------------------------------|
| Pi-hole    | http://localhost/admin       |
| Portainer  | https://localhost:9443       |
| Nginx      | http://localhost:8080        |
| Watchtower | keine Weboberfläche (`docker logs watchtower`) |

## Pi-hole

<!-- TODO: eigene Erklärung, was Pi-hole macht und wie du es getestet hast -->

## Portainer

<!-- TODO: eigene Erklärung, was Portainer macht und wie du es getestet hast -->

## Watchtower

<!-- TODO: eigene Erklärung, was Watchtower macht und wie du es getestet hast -->

## Nginx

<!-- TODO: eigene Erklärung, was Nginx macht und wie du es getestet hast -->
