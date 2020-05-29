# Dockerized Pi-hole and DNS-over-HTTPS via cloudflared

Based on [pihole](https://hub.docker.com/r/pihole/pihole) and [cloudflared](https://hub.docker.com/r/visibilityspots/cloudflared) docker images.

## Usage

Start the containers with `docker-compose`, adjust the parameters as necessary.

```shell
SERVER_IP=... WEB_PASSWORD=... docker-compose up -d
```

Both `SERVER_IP` and `WEB_PASSWORD` parameters are optional, their default values are `127.0.0.1` and empty string, respectively.
