FROM eclipse-temurin:21-jdk

WORKDIR /app

# Copy the pre-built JAR
COPY target/alert_service-0.0.1-SNAPSHOT.jar app.jar

# Expose service port
EXPOSE 8091

# Run the service
ENTRYPOINT ["java", "-jar", "app.jar"]

