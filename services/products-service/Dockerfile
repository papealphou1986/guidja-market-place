FROM openjdk:17-oracle
LABEL authors="Alphousseyni Mané"
VOLUME /tmp
COPY target/*.jar  /app/products-service.jar
ENTRYPOINT ["java", "-jar", "/app/products-service.jar"]