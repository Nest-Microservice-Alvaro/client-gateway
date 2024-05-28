<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

# Development pasos

1. Clonar proyecto
2. Crear un archivo `.env` basado en el archivo `.env.template`
3. Tener levantado los microservicios que se van a consumir
4. Tener levantado el servidor NAST
```
docker run -d --name nats-server -p 4222:4222 -p 8222:8222 nats
```
5. Levantar el proyecto con `npm run start:dev`

## Nats
```
docker run -d --name nats-server -p 4222:4222 -p 8222:8222 nats
```
