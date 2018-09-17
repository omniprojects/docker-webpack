FROM node
MAINTAINER Clinton Reece <dev@beomni.com>

RUN apt-get update && \
	apt-get install -y bzip2 git python-pip python-dev build-essential && \
	rm -rf /var/lib/apt/lists/*
RUN pip install awscli --upgrade --user
RUN echo 'export PATH=~/.local/bin:$PATH' >> /root/.bashrc

VOLUME /app

EXPOSE 3000 9222

WORKDIR /app
