FROM openjdk:17-oracle
LABEL authors="Alphousseyni Mané"
VOLUME /tmp
COPY target/*.jar  /app/gateway-service.jar
ENTRYPOINT ["java", "-jar", "/app/gateway-service.jar"]