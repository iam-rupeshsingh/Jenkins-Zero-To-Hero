FROM maven:3.9.2-eclipse-temurin-17

USER root

RUN apt-get update && \
    apt-get install -y docker.io && \
    apt-get clean

RUN docker --version
