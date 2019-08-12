##Pull jdk11 from DockerHub
FROM openjdk:11
##Specify the work directory
WORKDIR usr/src
##Add the jar file to be executed
ADD ./target/eruka-service-0.0.1-SNAPSHOT.jar /usr/src/eruka-service-0.0.1-SNAPSHOT.jar
##ENTRYPOINT allows you to configure a container that will run as an executable
ENTRYPOINT ["java","-jar","eruka-service-0.0.1-SNAPSHOT.jar"]
EXPOSE:9002