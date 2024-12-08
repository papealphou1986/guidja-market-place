FROM openjdk:17-oracle
LABEL authors="Alphousseyni Mané"
VOLUME /tmp
COPY target/*.jar  /app/config-server-service.jar
ENTRYPOINT ["java", "-jar", "/app/config-server-service.jar"]