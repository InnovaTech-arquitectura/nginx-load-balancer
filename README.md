# Nginx Load Balancer with Docker

Este repositorio contiene la configuración para un balanceador de carga Nginx ejecutándose dentro de un contenedor Docker. El balanceador de carga distribuye las solicitudes entre múltiples instancias de API Gateway.

## Estructura del proyecto

- **docker/Dockerfile**: Dockerfile para construir la imagen del balanceador de carga Nginx.
- **docker/nginx.conf**: Configuración personalizada de Nginx como balanceador de carga.
- **docker-compose.yml**: Archivo para levantar el stack completo utilizando Docker Compose.
