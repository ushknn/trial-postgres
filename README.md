# trial-postgres
trial environment for postgres on docker

### 1. environment

#### postgres 14.2

### 2. usage

#### container up 
`docker-compose up -d`

#### enter container
`docker-compose exec postgres bash`

#### access to postgres(in container)
`psql -U postgres -h localhost -p 5432`
