FROM golang:1.16.15

WORKDIR /app

COPY . .

RUN go build

ENV REQUEST_ORIGIN=https://example.com

CMD ["./server"]