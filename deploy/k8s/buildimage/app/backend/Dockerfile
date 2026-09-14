# Use an OpenJDK base image for Java
FROM eclipse-temurin:17

# Use ADD to download the JAR directly from GitHub
ADD https://github.com/herbertkb/spring-rhdh-demo/raw/refs/heads/main/backend/target/weather-0.0.1-SNAPSHOT.jar main.jar

EXPOSE 7890

CMD ["java", "-Dserver.port=7890", "-jar", "main.jar"]
