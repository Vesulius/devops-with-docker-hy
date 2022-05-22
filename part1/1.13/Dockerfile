FROM golang:1.16

EXPOSE 8080

WORKDIR /usr/app

COPY ./ /usr/app

ENV REQUEST_ORIGIN=http://localhost:5000

RUN go build

CMD ["./server"]