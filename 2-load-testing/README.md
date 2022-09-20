This repository features source code from this [great article by Adrian Gonciarz](https://medium.com/swlh/feed-prometheus-with-locust-performance-tests-as-a-metrics-source-d8d2bfec918c)

Pre-requisites:

- Docker (or Podman/Colima)
- Fiberplane CLI + Account ([fiberplane.dev](https://fiberplane.dev))

# Steps to get started

1. Create a Proxy token: `fp proxies create`
2. Add the Proxy token to a `.env` file as `TOKEN={ProxyApiToken}`
3. Run `docker-compose up -d`
