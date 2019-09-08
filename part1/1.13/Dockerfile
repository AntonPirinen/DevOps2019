FROM openjdk:8-jdk

WORKDIR /app
COPY spring-example-project /app
RUN ./mvnw package
EXPOSE 8080

CMD FRONT_URL=http://localhost:3006 java -jar ./target/docker-example-1.1.3.jar
