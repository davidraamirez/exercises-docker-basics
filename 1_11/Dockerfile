FROM amazoncorretto:8

WORKDIR /usr/src/app

EXPOSE 8080

COPY . .

RUN ./mvnw package

CMD ["java", "-jar", "/usr/src/app/target/docker-example-1.1.3.jar"]
