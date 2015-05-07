# a naive Redis image

FROM ubuntu:14.04

# copy to image/container
COPY redis-server_2.8.19.deb myredis.deb

# install from deb
RUN dpkg -i myredis.deb

# start Redis server
CMD [ "redis-server" ]
