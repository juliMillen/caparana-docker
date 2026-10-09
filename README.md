# Caparana - Docker

Stack: Angular + Spring Boot + PostgreSQL, orquestado con Docker Compose.

# Estructura

- 'caparana-back': backend (submodulo)

- 'front-caparana': frontend (submodulo)

- 'docker-compose.yml': levanta db, back y front.

## Levantar el proyecto
```bash
git clone --recurse-submodules https://github.com/juliMillen/caparana-docker.git

cd caparana-docker

cp .env.example .env     # completar con valores reales

docker compose up --build
```
# URLS
- Front: http://localhost:4200

- Back: http://localhost:8080

# NOTA

La base de datos arranca vacía. Los datos se cargan desde la app o importando un dump SQL.
