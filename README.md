# Symfony Entity Soft Delete

This repository was created to show step by step how to perform a Soft Delete on an Entity in Smfony 7.x

The article is --> https://proyectosbeta.net/2024/09/guia-completa-como-implementar-soft-delete-en-symfony-7-x-paso-a-paso/

## Technologies 

* Symfony 7.x and Symfony cli
* API Platform 3.x
* PostgreSQL
* Docker and Docker Compose

## Install

```bash
composer install
```

### Docker Compose

```bash
docker compose up -d
```

### Migrations

```bash
php bin/console doctrine:migrations:migrate
```

### Server dev run

```basg
symfony server:start --port=8080
```

Open your favorite browser and type: https://127.0.0.1:8080

### Swagger

https://127.0.0.1:8080/api
