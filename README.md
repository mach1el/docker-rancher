# Rancher docker container 
Run rancher on docker

## Variables

| Name | Description | Default |
|------|-------------|---------|
|<a name="DOMAIN"></a> [DOMAIN](#) | Set DNS for cotainers resource | `traefik.me` |
|<a name="TRAEFIK_USER"></a> [TRAEFIK_USER](#) | User for traefik middlewares authentication  | `Not set` |
|<a name="TRAEFIK_PASSWD"></a> [TRAEFIK_PASSWORD](#) | Password for traefik middlewares authentication  | `Not set` |

* **Note**: for `*_PASSWORD` it must be generated by htpasswd

```
htpasswd -nBC 10 $TRAEFIK_USER
```