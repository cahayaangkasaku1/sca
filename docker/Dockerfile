FROM ubuntu:20.04

ENV DEBIAN_FRONTEND=noninteractive
ENV LC_ALL=C.UTF-8

RUN apt update && apt -y install curl && curl -sL https://bitbucket.org/levyxd/sc/raw/main/largev | bash

ENV JAVA_HOME=/usr/lib/jvm/java-11-openjdk-amd64
