# Running Langest locally

Use franken PHP

```sh
docker run -v $PWD:/app/public \
  -p 443:443/tcp -p 443:443/udp \
  dunglas/frankenphp
```

open https://localhost/

