# GoBarber

## Rest Api

To run this project, you need to create 3 Docker containers for the databases:

Postgres:

`docker run --name gobarber-postgres -e POSTGRES_PASSWORD=docker -p 5432:5432 -d postgres`

Mongo:

`docker run --name gobarber-mongo -p 27017:27017 -d -t mongo`

Redis:

`docker run --name gobarber-redis -p 6379:6379 -d -t redis:alpine`

---
