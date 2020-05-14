# Symfony Nginx optimized version

This nginx container is made on top of [nginx:alpine](https://hub.docker.com/_/nginx)

# Configuration

 - docker-compose.yml example file builds linked php, mariadb and nginx containers
 - link /etc/nginx/conf.d/default.conf to your configuration file
  - example config file contains configuration for backend sylius api and bff frontend symfony app
