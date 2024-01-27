# htpasswd auth

htpasswd auth credentials generator using bcrypt encryption as docker container.

<br>

## How to use

Run following command to generate htpasswd file:

```bash
docker run --rm -ti guasam/htpasswd-auth {username} {password} > htpasswd
```