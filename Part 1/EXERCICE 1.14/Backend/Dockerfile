FROM golang:1.16.15

WORKDIR /app

COPY . .

RUN go build

EXPOSE 8080

ENV REQUEST_ORIGIN=http://192.168.3.18:5000
CMD ["./server"]