FROM golang:latest
WORKDIR /usr/src/app
COPY go.mod ./
COPY hello.go ./
RUN go build -o hello
CMD ["./hello"]
