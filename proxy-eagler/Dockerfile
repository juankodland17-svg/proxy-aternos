FROM eclipse-temurin:17-jre-alpine
WORKDIR /app
COPY . /app
EXPOSE 8080
CMD ["java", "-Xms256M", "-Xmx512M", "-jar", "waterfall.jar"]