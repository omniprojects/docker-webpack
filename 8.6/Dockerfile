FROM node:8.6
MAINTAINER Jonathan Azoff <dev@beomni.com>

RUN apt-get install -y bzip2 git
RUN npm install -g webpack webpack-dev-server

VOLUME /app

EXPOSE 3000 9222

WORKDIR /app