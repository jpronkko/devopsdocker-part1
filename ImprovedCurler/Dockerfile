FROM ubuntu:22.04

RUN apt update
RUN apt install -y curl

COPY ./script.sh .
RUN chmod u+x ./script.sh

ENTRYPOINT  ["./script.sh"]

