FROM golang:1.16.15

WORKDIR /app

EXPOSE 8080

COPY . .

RUN go build

ENV REQUEST_ORIGIN=http://10.0.0.108

CMD ["./server"]
