FROM eclipse-temurin:17-jdk
WORKDIR /app
COPY . .
RUN ./mvnw -DskipTests package
EXPOSE 8080
CMD ["java", "-jar", "target/backend-0.0.1-SNAPSHOT.jar"]
