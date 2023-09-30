A compose.yaml file for running [gotify](https://github.com/gotify/server) with [caddy](https://github.com/caddyserver/caddy) as reverse proxy.



# Running
Adjust variables to your fit in `.env.example` file and rename it to `.env`.
Change `gotify.example.org` in `caddy/Caddyfile` to your domain.

And run
``` shell
docker-compose up -d
```
# Config
For more enviroments for [gotify](https://github.com/gotify/server) see [this](https://gotify.net/docs/config).
