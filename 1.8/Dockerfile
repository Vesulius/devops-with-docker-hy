FROM ubuntu:20.04

WORKDIR /usr/src

COPY curling.sh .

RUN chmod +x curling.sh

RUN apt-get update

RUN apt-get install -y curl

CMD ./curling.sh
