FROM ubuntu:24.04

RUN apt-get update \
    && apt-get install -y curl golang-go

WORKDIR /usr/src/app

COPY . . 

RUN go build 

EXPOSE 8080 

CMD ["./server"]