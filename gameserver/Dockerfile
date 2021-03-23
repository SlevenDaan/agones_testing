FROM ubuntu:latest
WORKDIR /GameServer
ADD Game_Server /GameServer
RUN chmod 777 -R *
EXPOSE 7777
CMD ["/GameServer/Mirror.x86_64", "-ipaddress=0.0.0.0", "-runAsServer"]