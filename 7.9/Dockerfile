FROM node:7.9
MAINTAINER Jonathan Azoff <dev@beomni.com>

RUN apt-get install -y bzip2 zip git
RUN npm install -g webpack webpack-dev-server yarn

VOLUME /app

EXPOSE 3000

WORKDIR /app