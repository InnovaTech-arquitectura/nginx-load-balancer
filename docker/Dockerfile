# Usamos la imagen oficial de Nginx
FROM nginx:latest

# Copiamos el archivo de configuración personalizado de Nginx al contenedor
COPY nginx.conf /etc/nginx/nginx.conf

# Exponemos el puerto 80 para el tráfico HTTP
EXPOSE 80

# Comando por defecto para iniciar Nginx
CMD ["nginx", "-g", "daemon off;"]
