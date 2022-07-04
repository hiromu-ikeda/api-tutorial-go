# syntax=docker/dockerfile:1

FROM golang:latest

WORKDIR /go/src

COPY . /go/src

RUN go mod init api-tutorial

RUN go get -u github.com/gin-gonic/gin
