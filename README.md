# PHP 8.1 Docker Image

Copy docker file from Laravel Sail
https://github.com/laravel/sail/tree/1.x/runtimes/8.1

## Docker Container
```
jagdeepbanga/php81
```

## Use Container
```
docker run jagdeepbanga/php81
docker exec -it {containerName} /bin/sh
php -v
PHP 8.1
```

## Build & Push to DockerHub
```
docker build -t jagdeepbanga/php81 .
docker login && docker push jagdeepbanga/php81
```
