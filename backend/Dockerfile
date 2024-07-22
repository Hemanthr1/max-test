FROM openjdk:17-jdk-slim
WORKDIR /app/backend
COPY ./quash-0.0.1-SNAPSHOT.jar ./quash-backend.jar
COPY ./application.properties ./application.properties
EXPOSE 8080
CMD ["sh", "-c", "java -jar quash-backend.jar"]