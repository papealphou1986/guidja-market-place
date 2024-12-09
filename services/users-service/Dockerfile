FROM openjdk:17-oracle
LABEL authors="Alphousseyni Mané"
VOLUME /tmp
COPY target/*.jar  /app/users-service.jar
ENTRYPOINT ["java", "-jar", "/app/users-service.jar"]