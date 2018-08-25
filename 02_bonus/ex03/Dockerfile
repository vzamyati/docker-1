FROM ubuntu

MAINTAINER vzamyati <vzamyati@student.unit.ua>

RUN apt-get update && apt-get upgrade -y && apt-get install -y nodejs npm git vim emacs

RUN npm install yarn --global && npm install npm --global

# How to build it?
# docker build -t ex03 .

# How to run it?
# docker run --rm -ti ex03