FROM ubuntu

MAINTAINER vbrazhni <vbrazhni@student.unit.ua>

RUN apt-get update && apt-get upgrade -y && apt-get install -y nodejs npm git vim emacs

RUN npm install yarn --global && npm install npm --global

# How to build it?
# docker build -t a03 .

# How to run it?
# docker run --rm -ti a03