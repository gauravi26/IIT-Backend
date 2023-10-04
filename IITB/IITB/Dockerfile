#FROM ubuntu:latest
#LABEL authors="hp"
#
#ENTRYPOINT ["top", "-b"]
FROM openjdk:8
EXPOSE 8080
ADD target/IITB-0.0.1-SNAPSHOT.jar IITB-0.0.1-SNAPSHOT.jar

ENTRYPOINT ["java", "-jar","IITB-0.0.1-SNAPSHOT.jar"]
