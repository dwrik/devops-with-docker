FROM amazoncorretto:8

WORKDIR /usr/src/app

COPY . .

RUN ./mvnw package

EXPOSE 8080

ENTRYPOINT ["java", "-jar", "./target/docker-example-1.1.3.jar"]
