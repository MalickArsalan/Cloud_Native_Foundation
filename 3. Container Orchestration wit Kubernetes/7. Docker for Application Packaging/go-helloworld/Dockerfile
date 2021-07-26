FROM golang:alpine
LABEL maintainer="Malick Arsalan"

WORKDIR /go/src/app

ADD . .

RUN go mod init && go build -o helloworld

EXPOSE 6111

CMD ["./helloworld"]
