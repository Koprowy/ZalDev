# Użyj oficjalnego obrazu JDK
FROM openjdk:17-jdk-slim

# Ustaw katalog roboczy
WORKDIR /app

# Skopiuj plik JAR
COPY target/demo-0.0.1-SNAPSHOT.jar app.jar

# Expose port
EXPOSE 8080

# Uruchom aplikację
CMD ["java", "-jar", "app.jar"]

