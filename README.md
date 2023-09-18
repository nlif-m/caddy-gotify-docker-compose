A compose.yaml file for running [gotify](https://github.com/gotify/server) with [caddy](https://github.com/caddyserver/caddy) as reverse proxy.



# Running
Write `GOTIFY_DEFAULTUSER_PASS` in `compose.yaml`c.

Change `gotify.example.org` in `caddy/Caddyfile` to your domain.

Change `TZ` to your timezone.

And run
``` shell
docker-compose up -d
```
# Config
For more enviroments for [gotify](https://github.com/gotify/server) see [this](https://gotify.net/docs/config).
