FROM alpine:latest
MAINTAINER Vipin Sati


RUN apk --update add openjdk7-jre
 
COPY ./DockImg-0.0.1-SNAPSHOT.jar  /usr/local/bin/

CMD java -jar /usr/local/bin/DockImg-0.0.1-SNAPSHOT.jar
