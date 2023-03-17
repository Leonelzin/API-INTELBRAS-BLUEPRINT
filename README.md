# API Intelbras v4

https://apiintelbrasv4.docs.apiary.io

We kindly ask you to **TEST** your changes before opening a merge request.

## Docker Setup

```bash
git clone -b api_v4 https://git.intelbras.com.br/zeus-api/api-blueprint.git
cd api-blueprint
docker-compose build
docker-compose up
```

## Debian Setup

```bash
apt-get install ruby-dev make gcc
gem install apiaryio
apiary preview --server --path="api.apib" --port 9000
```

### Local Access

http://localhost:9000
