FROM golang:1.21

WORKDIR /app
COPY . .
RUN go mod init service_1 && go mod tidy
RUN go build -o main .
EXPOSE 8001
CMD ["./main"]
