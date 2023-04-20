FROM ubuntu:lunar

ARG DEBIAN_FRONTEND=noninteractive

RUN apt-get update
RUN apt-get upgrade -y
RUN apt-get install -y nodejs npm
RUN npm install -g localtunnel
RUN npm install -g typescript
