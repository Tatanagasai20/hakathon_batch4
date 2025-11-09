# Use a lightweight Java runtime
FROM eclipse-temurin:21-jdk

# Set working directory
WORKDIR /app

# Copy the pre-built jar
COPY target/alert_service-0.0.1-SNAPSHOT.jar app.jar

# Expose the service port
EXPOSE 8091

# Run the jar
ENTRYPOINT ["java", "-jar", "app.jar"]

