FROM ubuntu:xenial-20210416


RUN apt-get update
RUN apt-get install -y iputils-ping
RUN apt-get install -y wget
ENTRYPOINT ["ping","-c", "3"]
CMD ["127.0.0.1"]
