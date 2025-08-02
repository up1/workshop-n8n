# Self-host n8n
* https://docs.n8n.io/hosting/

## NodeJS
```
$npx n8n start --tunnel

or 

$npm install n8n -g
$n8n start --tunnel
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

## [n8n with tunnel](https://docs.n8n.io/hosting/installation/docker/#n8n-with-tunnel)

```

```

Other tools
* [ngrok](https://ngrok.com/)


## Bot supported features

### Variables
* Use environment variable
```
{{ $env.LINE_ACCESS_TOKEN }}
```