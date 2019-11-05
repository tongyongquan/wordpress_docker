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

## 迁移已有wordpress
1.phpmyadmin导入数据库
2.覆盖wp-content
3.删除或重新配置wp-config.php
