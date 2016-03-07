# Docker Compose files for PHP development

# Apache + PostgreSQL
docker-compose -f docker-compose.apache.yml up

# nginx + Apache + PostgreSQL
docker-compose -f docker-compose.nginx+apache.yml up

# nginx + PHP-FPM + PostgreSQL
docker-compose -f docker-compose.nginx+php-fpm.yml up
