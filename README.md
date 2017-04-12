# Docavel

A simple containerised laravel application using docker-compose.

### Commands:
- `docker-compose build` to build the containers.
- `docker-compose up -d` to run the containers (in the background).
- `docker-compose down` to shutdown the containers.
- `docker exec -it docavel_php_1 bash` to ssh into the php container. And get access to `composer` & `php artisan`.