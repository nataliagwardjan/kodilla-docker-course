FROM golang:1.19

WORKDIR /src/app

RUN go mod init gohelloworld

COPY . .

RUN go build -v -o /usr/local/bin/app ./...

EXPOSE 8080

CMD ["go", "run", "main.go"]
