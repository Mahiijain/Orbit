FROM golang:1.21-alpine

WORKDIR /app

COPY . .

RUN go build -o log-generator .

CMD ["./log-generator"]