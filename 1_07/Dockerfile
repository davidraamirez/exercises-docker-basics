FROM ubuntu:24.04

RUN apt-get -y update && apt-get -y install curl

WORKDIR /usr/src/app

COPY script.sh .

CMD ["./script.sh"]