# 概要
XAMPPと同等のものをDockerで動かします。

- PHP 8
- Apache
- MySQL 8
- PHPMyAdmin 

# 構築方法
```
git clone https://github.com/KaguraGateway/xampp-docker.git
docker compose build
docker compose up
```

[http://localhost/info.php](http://localhost/info.php) にアクセスできるか、確認する。

# コンテナアクセス方法
### PHP Apache
```
docker compose exec php bash
```
