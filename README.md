# docker-basic-auth-proxy

This is a simple basic auth proxy running inside of a docker container. It requires a `TARGET` env var that serves specifying the target host as well as a `htpasswd` formatted file, the path to the file can be specified via `BASIC_AUTH_FILE` env var (defaults to `/etc/nginx/basic_auth`).

This image is available at docker hub as `apinnecke/basic-auth-proxy`

## Example docker-compose.yml

```yml

```
