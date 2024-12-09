FROM openjdk:17-oracle
LABEL authors="Alphousseyni Mané"
VOLUME /tmp
COPY target/*.jar  /app/orders-service.jar
ENTRYPOINT ["java", "-jar", "/app/orders-service.jar"]