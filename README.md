# docker-centos-apache-php7.1
Docker with CentOS 7, systemd, Apache2, PHP7.1, crond, composer and pagespeed

# Pull

```
docker pull kokspflanze/centos-apache-php71
```

# Running Container

```
docker run -v /opt/docker/docker_test/data:/var/www/page  --restart=always -d -it kokspflanze/centos-apache-php71
```

# Attach Container

```
docker exec kokspflanze/centos-apache-php71 /bin/bash
```