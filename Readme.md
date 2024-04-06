# Docker

docker run -e MYSQL_ROOT_PASSWORD=root mysql ls

docker run -v $PWD:/var/www/laravel php-fpm

docker run -v $PWD:/var/www/laravel -p 8080:80 nginx

mysql -uroot -proot --port 33061 --host 127.0.0.1

docker-compose up -d --scale mysql=3

docker-compose up --build -d

docker exec [container-name] php artisan migrate
