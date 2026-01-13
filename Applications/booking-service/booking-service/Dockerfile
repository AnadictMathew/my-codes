FROM eclipse-temurin:17-jdk-alpine
WORKDIR /app
COPY target/booking-service.jar app.jar
EXPOSE 8020
ENTRYPOINT ["java","-jar","app.jar"]