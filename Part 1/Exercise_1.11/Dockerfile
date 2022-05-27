FROM openjdk:8

EXPOSE 8080

WORKDIR /usr/src/app  

COPY . .

RUN apt-get update 

RUN apt-get install -y dos2unix 

RUN dos2unix mvnw

RUN ./mvnw package

CMD ["java", "-jar", "./target/docker-example-1.1.3.jar"]
