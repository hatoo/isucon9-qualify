FROM golang:buster

RUN apt update && apt install default-mysql-client -y

WORKDIR /go/isucari
COPY . .
RUN make

CMD ["./isucari"]