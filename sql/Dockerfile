FROM mysql:latest
ENV MYSQL_ROOT:PASSWORD=contrasenyaRoot
#Tener en cuenta la BD!!!!!!
ENV MYSQL_DATABASE=cine
ENV MYSQL_USER=usuario1
ENV MYSQL_PASSWORD=contrasenyaUsuario1
#Tener en cuenta la BD!!!!!!
COPY cine.sql /docker-entrypoint-initdb.d/ 