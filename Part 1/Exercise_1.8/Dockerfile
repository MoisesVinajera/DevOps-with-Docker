FROM ubuntu:20.04

COPY script.sh .

RUN chmod +x script.sh

RUN apt-get update

RUN apt-get install -y curl

CMD ./script.sh