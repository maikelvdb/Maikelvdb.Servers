# Prepare for Traefik deployment

## Password

```bash
htpasswd -nb admin PSSWORD
```

## Create a new network for Traefik

```bash
docker network create proxy
```

## Let's Encrypt

```bash
mkdir -p letsencrypt
touch letsencrypt/acme.json
chmod 600 letsencrypt/acme.json
```
