FROM openjdk:8-jre

RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app

COPY /build/libs /usr/src/app

EXPOSE 8080
EXPOSE 5683


CMD ["java","-jar","thingweb-repository-0.6.jar"]
