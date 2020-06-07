FROM openjdk:8
WORKDIR /spring

RUN apt update && apt install -y git
RUN git clone https://github.com/docker-hy/spring-example-project /spring

RUN ./mvnw package

EXPOSE 8080
CMD ["java", "-jar", "./target/docker-example-1.1.3.jar"]
