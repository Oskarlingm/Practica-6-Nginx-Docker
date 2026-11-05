# Practica 6: Ejecutar servidor web Nginx con Docker

En esta practica se ejecuta un servidor web Nginx dentro de un contenedor Docker utilizando Docker Compose. El archivo `src/index.html` contiene la pagina que muestra el servidor.

## Estructura

- `src/index.html`: pagina web con el mensaje "Hola mundo".
- `docker-compose.yml`: configuracion del contenedor Nginx, puerto 8080 y volumen de la carpeta `src`.

## Como ejecutarlo

1. Abrir Docker Desktop y esperar que el motor este funcionando.
2. Abrir una terminal en la carpeta principal del proyecto.
3. Ejecutar:

```bash
docker compose up -d
```

4. Abrir http://localhost:8080 en un navegador.
5. Verificar el contenedor con:

```bash
docker ps
```

Para detener y eliminar el contenedor de esta practica:

```bash
docker compose down
```

## Datos del estudiante

Oskarling Moises Mendez Mercedes - Matricula 2025-1058
