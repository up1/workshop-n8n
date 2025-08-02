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
* For development only

Other tools
* [ngrok](https://ngrok.com/)
* [Cloudflare tunnel](https://developers.cloudflare.com/cloudflare-one/connections/connect-networks/)


## Not supported features

### Variables
* Use environment variable
```
{{ $env.LINE_ACCESS_TOKEN }}
```

## Start Vector Database
* [Qdrant](https://qdrant.tech/)
```
$docker compose up -d qdrant
$docker compose ps
```

List of URLs
* [Qdrant Dashboard](http://localhost:6333/dashboard)
