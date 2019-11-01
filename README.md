# wordpress_docker
docker-compose配置 wordpress+nginx+mysql 

## config

```
cp .env_example .env
```

## start

```
mkdir -p certs/ certs-data/ logs/nginx/ mysql/ wordpress/
docker-compose up -d
```
