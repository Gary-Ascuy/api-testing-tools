# Hoppscotch CLI

#### Requirements (issues & constraints)

- Python >= v3.12
- clang, clang++, and make
- Node v20
- node-gyp - https://github.com/nodejs/node-gyp
- hopp - `npm i -g @hoppscotch/cli`

#### Run CLI for Version 1 - Postman

```sh
hopp test --env ./env/Echov1-Postman.env.json ./collection/ApiMigrationUseCase.json
```

#### Run CLI for Version 2 - Hoppscotch

```sh
hopp test --env ./env/Echov2-Hoppscotch.env.json ./collection/ApiMigrationUseCase.json
```

# Hoppscotch Docker

#### Requirements

- Docker

Download Image
```sh
docker pull garyascuy/hoppscotch-cli:latest
```

Add Alias 
```sh
alias dhopp="docker run --rm -t --network host -v $(pwd):/usr/app garyascuy/hoppscotch-cli:latest"
```

#### Run CLI for Version 1 - Postman

```sh
dhopp test --env ./env/Echov1-Postman.env.json ./collection/ApiMigrationUseCase.json
```


#### Run CLI for Version 2 - Hoppscotch

```sh
dhopp test --env ./env/Echov2-Hoppscotch.env.json ./collection/ApiMigrationUseCase.json
```
