# NGINX + Let's Encrypt SSL Certificate (docker-compose.yml)

### How to use it?

1. Install **docker** and **docker-compose** on your server.
2. Create folder on your server with name like `nginx`.
3. Copy files `docker-compose.yml` and `init-letsencrypt.sh` and `data` folder to your nginx folder.

You must have structure like this.

```
nginx/
  data/
  docker-compose.yml
  init-letsencrypt.sh
```

4. Change dummy `domain.com` to your domain which already configured to server. Files which require this changes is `data/nginx.conf` and `init-letsencrypt.sh`. As well change inside `init-letsencrypt.sh`email to yours.
