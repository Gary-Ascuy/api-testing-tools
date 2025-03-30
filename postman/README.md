# Postman

## Run CLI for Version 1 - Postman

```sh
postman collection run \
    --environment ./env/Echov1-Postman.postman_environment.json \
    ./collection/ApiMigrationUseCase.postman_collection.json
```

## Run CLI for Version 2 - Hoppscotch

```sh
postman collection run \
    --environment ./env/Echov2-Hoppscotch.postman_environment.json \
    ./collection/ApiMigrationUseCase.postman_collection.json
```
