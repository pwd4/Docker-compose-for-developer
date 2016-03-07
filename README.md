# Docker Compose files for PHP development

# Apache + PostgreSQL
    docker-compose -f docker-compose.apache.yml up

# nginx + Apache + PostgreSQL
    docker-compose -f docker-compose.nginx+apache.yml up

# nginx + PHP-FPM + PostgreSQL
    docker-compose -f docker-compose.nginx+php-fpm.yml up

# How to connect to PostgreSQL
    $dbh = new PDO('pgsql:host=postgres;dbname=postgres;user=postgres')
