```bash
curl http://localhost:8080/
```

```bash
curl -H "Content-Type: application/json" -X POST -d '{
    "firstName": "Bruno",
    "lastName": "Krebs"
}'  http://localhost:8080/
```


```bash
curl -X DELETE http://localhost:8080/1
```

```bash
curl -H "Content-Type: application/json" -X PUT -d '{
    "id": 6,
    "firstName": "Bruno",
    "lastName": "Simões Krebs"
}'  http://localhost:8080/6
```

```
The initial code was taken from this site: https://auth0.com/blog/developing-restful-apis-with-kotlin/
My intention is to evolve it.
```
