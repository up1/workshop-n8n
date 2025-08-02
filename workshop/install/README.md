# Self-host n8n
* https://docs.n8n.io/hosting/

## NodeJS
```
$npx n8n
```
Access to n8n
* http://localhost:5678/


## Docker
```
$docker compose up -d postgres
$docker compose up -d n8n
$docker compose ps
```

Access to n8n
* http://localhost:5678/

## Bot supported features

### Variables
* Use environment variable
```
{{ $env.LINE_ACCESS_TOKEN }}
```