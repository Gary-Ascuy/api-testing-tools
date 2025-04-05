# Bruno CLI

#### Requirements 

- Bruno CLI (Requires NodeJS)

```sh
npm install -g @usebruno/cli
```

```sh
cd usebruno/ApiMigrationUseCase
```

#### Run CLI for Version 1 - Postman

```sh
bru run --env "Echo v1 - Postman"
```

#### Run CLI for Version 2 - Hoppscotch

```sh
bru run --env "Echo v2 - Hoppscotch"
```

#### Useful Commands 

```sh
bru --help 
bru run --help 

# Reports
bru run --env "Echo v1 - Postman" --output results.html --format html 
```
