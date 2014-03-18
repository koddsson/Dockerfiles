# Dockerfile for node.js on debian jessie
# https://index.docker.io/u/koddsson/docker-debian-nodejs/

FROM debian:jessie
MAINTAINER Kristjan Oddsson, koddsson@gmail.com

RUN apt-get update
RUN apt-get install curl -y
RUN apt-get install python -y
RUN apt-get install gcc -y
RUN apt-get install make -y
RUN apt-get install g++ -y

ADD node-v0.10.26.tar.gz .

RUN cd node-v0.10.26 && ./configure && make && make install

RUN node -v
RUN npm -v
