# Baserow
Opensource no-code online database an airtable alternatice.

## Technology stack
* python
* postgresql

## Installation
```
docker run -d --name baserow -e BASEROW_PUBLIC_URL=http://localhost -v baserow_data:/baserow/data -p 80:80 -p 443:443 --restart unless-stopped baserow/baserow:1.11.0
```


## Resource
* [Docker Installation](https://baserow.io/docs/installation/install-with-docker)
