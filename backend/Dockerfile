FROM golang:1.20.1-alpine
WORKDIR /app

COPY . .

RUN go mod download && \
    go build -o main *.go

CMD ["/app/main"]