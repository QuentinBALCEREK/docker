# Projet Docker Web (Juste for working in my project)

php:7.2.7-fpm-alpine3.7  
httpd:2.4.33-alpine  
MariaDB 5.5  

> git clone git@github.com:QuentinBALCEREK/docker.git

> cd docker

## Configuration
> cp docker/mysql/sf_mysql.env.dist docker/mysql/sf_mysql.env

> cp docker/apache/sf_mail.env.dist docker/apache/sf_mail.env

> cp docker/php/sf.env.dist docker/php/sf.env

## Test
> echo coucou >> src/index.html

> docker-compose -f docker/docker-compose.yml build

> docker-compose -f docker/docker-compose.yml up -d
