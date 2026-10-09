# Caparana - Docker

Stack: Angular + Spring Boot + PostgreSQL.

## Levantar el proyecto

git clone --recurse-submodules https://github.com/juliMillen/caparana-docker.git
cd caparana-docker
cp .env.example .env     # completar con valores reales
docker compose up --build

- Front: http://localhost:4200
- Back: http://localhost:8080