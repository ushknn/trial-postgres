# trial-postgres
trial environment for postgres on docker

### 1. environment

#### postgres 14.2

### 2. usage

#### 2.1 container up 
`docker-compose up -d`

#### 2.2 enter container
`docker-compose exec postgres bash`

#### 2.3 access to postgres(in container)
`psql -U postgres -h localhost -p 5432`
