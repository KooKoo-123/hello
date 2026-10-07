FROM eclipse-temurin:8-jdk-jammy
WORKDIR /app
COPY target/hello-1.0.0.war app.war
EXPOSE 8080
CMD ["java", "-jar", "/app/app.war"]