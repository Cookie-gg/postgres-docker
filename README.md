# PostgresSQL - docker container for development

### setup

- make a env file

```
touch .env
vim .env

POSTGRES_USER="<username>"
POSTGRES_PASSWORD="<password>"
```

- run a container

```
docker-compose up (-d: run in the background)
```

- enter a container

```
docker-compose exec -it postgres bash
```

- enter postgres

```
psql -h <localhost> -U <username> -d <database>
```
