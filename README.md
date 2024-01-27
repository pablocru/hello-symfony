# Hello Symfony

My first Symfony project

## Install twig

```bash
cd my-project

docker run --rm --interactive --tty --volume .:/app composer require twig
```

## Start an existing App

1. Start `docker-compose`
1. Enter to `symfony docker`
1. Install dependencies and exit it.

```bash
docker-compose up -d \
docker-compose exec <symfony-docker-name> bash -c "composer install && exit"
```
