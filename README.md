# Cloudmart e-commerce demo <hr />

# Local env setup <hr />
- To spin up postgresql db in docker
```shell
docker run --name graphqldemo -p 5433:5432 -e POSTGRES_DB=graphqldemo -e POSTGRES_PASSWORD=sp -e POSTGRES_USER=postgres -d postgres:15
```