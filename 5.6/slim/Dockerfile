FROM jmfirth/webpack:5.6-slim
MAINTAINER Jonathan Azoff <dev@beomni.com>

RUN apt-get update
RUN apt-get install -y zip git
RUN cd $(npm root -g)/npm && npm install fs-extra && sed -i -e s/graceful-fs/fs-extra/ -e s/fs\.rename/fs.move/ ./lib/utils/rename.js
RUN npm install -g pnpm