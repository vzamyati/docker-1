FROM debian

MAINTAINER vzamyati <vzamyati@student.unit.ua>

RUN apt-get update && apt-get install -y cowsay fortune lolcat

ENTRYPOINT /usr/games/fortune | /usr/games/cowsay | /usr/games/lolcat

# How to build it?
# docker build -t ex00 .

# How to run it?
# docker run --rm -t ex00