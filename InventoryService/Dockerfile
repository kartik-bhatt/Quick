FROM openjdk:17-jdk-slim

WORKDIR /app

COPY target/InventoryService-0.0.1-SNAPSHOT.jar app.jar

EXPOSE 8082

ENTRYPOINT ["java", "-jar", "/app/app.jar"]

