# docker_compose_config_NGINX_PHP
My training simple php config with docker compose

Your need docker and docker-compose in your operation system.

CLONE:
git clone https://github.com/codesshaman/simple_docker_php_nginx.git

GO TO FOLDER:
cd simple_docker_php_nginx

Every commands executed into the root folder with docker-compose.yml file.

RUN:
docker-compose up -d

STOP:
docker-compose down

CONNECT:
docker exec -it nginx_simple_php sh

OPEN:
http://localhost/






Minimal docker nginx and php-fpm configuration

Clone: git clone https://github.com/codesshaman/simple_docker_php_nginx.git

RUN:

cd simple_docker_php_nginx

sudo docker-compose up -d --build

Connect:

http://localhost