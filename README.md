## laravel composer create project
```sh
docker compose run --rm --build composer create-project --prefer-dist laravel/laravel .
```

## modify some permissions
```sh
sudo chmod -R o+w src/storage src/bootstrap/cache
```

## startup

```sh
docker compose up -d --build server
```
