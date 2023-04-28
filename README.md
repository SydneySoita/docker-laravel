# docker-laravel
<!-- Create laravel project -->

docker-compose create-project --prefer-dist laravel/laravel .   

<!-- Start Containers -->

docker-compose up -d --build server

<!-- Make Migrations -->

docker-compose run --rm artisan migrate


