# 1. 
Para instalar bind9 utilizamos sudo apt update y sudo apt install bind9. 
Después usamos docker pull internetsystemsconsortium/bind9:9.18 para descargar la imagen que necesitamos. 

# 2.
Ahora creamos y configuramos nuestro archivo docker-compose.yml. 
Para lanzar el contenedor utilizamos el comando docker-compose up -d

# 3.
sevices: servicio a ejecutar.  
bind9: nombre servicio.  
container_name: nombre contenedor.  
ports:  puertos a mapear del contenedor al host.  
volumes: mapear un volumen local para los datos de configuración de bind9.  


