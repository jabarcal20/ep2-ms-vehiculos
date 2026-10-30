# Imagen base oficial de nginx
FROM nginx:latest

# Copiar nuestra página a la carpeta web de nginx
COPY ".taget/cl-matiivilla-vehiculos-0.0.1-SNAPSHOT" "app.jar"

# Puerto que usa nginx
EXPOSE 80

ENTRYPOINT ["java", "-jar", "app.jar"]
