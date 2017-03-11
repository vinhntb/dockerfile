FROM alpine:latest

MAINTAINER vinhntb "vinhnt.bit@gmail.com"


# Initialize
RUN mkdir -p /data/webapp
WORKDIR /data/webapp


# Setup
RUN apk update
RUN apk upgrade
RUN apk add --update python python-dev py-pip postgresql-client postgresql-dev build-base gettext bash git
RUN pip install --upgrade pip && pip install -r requirements.txt


