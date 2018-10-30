FROM golang:1-alpine

RUN apk update && apk upgrade && apk add --update --no-cache alpine-sdk tzdata mysql-dev nodejs
RUN apk add --update --no-cache \
      bash \
      git \
      openssh \
      mysql \
      tzdata \
      yaml

RUN mkdir /app
WORKDIR /app

