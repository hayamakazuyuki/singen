FROM node:18-alpine 

WORKDIR /usr/src/app

RUN apk update && \
    apk add git && \
    apk add openssh

ENV HOST 0.0.0.0
EXPOSE 3000
