# Use OpenJDK 17 as the base image
FROM openjdk:17-jdk-slim

# Set the working directory
WORKDIR /app

# Copy the built JAR file into the container
COPY target/serviceRegistry-0.0.1-SNAPSHOT.jar app.jar

# Expose the required port
EXPOSE 8761

# Run the application
ENTRYPOINT ["java", "-jar", "/app/app.jar"]

