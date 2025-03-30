# USE CASE: Api Migration

We need to test and compare the old and new versions of our API to ensure the latest update is at least as reliable as the previous one. By testing both versions under the same conditions, we can identify any issues and confirm the changes have the desired effect.

## Post Echo v1 - Current Version by Postman

#### REQUEST

```sh
curl --request POST \
  --url 'http://postman-echo.com/post?search=raichu' \
  --header 'content-type: application/json' \
  --header 'x-gary-testing: info' \
  --data '{
  "name": "Gary",
  "lastName": "Ascuy Anturiano"
}'
```

#### RESPONSE

```json
{
  "args": {
    "search": "raichu"
  },
  "data": {
    "lastName": "Ascuy Anturiano",
    "name": "Gary"
  },
  "files": {},
  "form": {},
  "headers": {},
  "json": {
    "lastName": "Ascuy Anturiano",
    "name": "Gary"
  },
  "url": "http://postman-echo.com/post?search=raichu"
}
```

## Post Echo v2 - New Version by Hoppscotch Team

#### REQUEST

```sh
curl --request POST \
  --url 'https://echo.hoppscotch.io/post?search=raichu' \
  --header 'content-type: application/json' \
  --header 'x-gary-testing: info' \
  --data '{
  "name": "Gary",
  "lastName": "Ascuy Anturiano"
}'
```

#### RESPONSE

```json
{
  "method": "POST",
  "args": {
    "search": "raichu"
  },
  "data": "{\"lastName\":\"Ascuy Anturiano\",\"name\":\"Gary\"}",
  "headers": { },
  "path": "/post",
  "isBase64Encoded": false
}
```
