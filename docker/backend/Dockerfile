# Dockerfile for go
FROM golang:1.13.1-alpine

ENV G0111MODULE=on

RUN apk update && \
    apk add emacs curl git && \
    go get github.com/pilu/fresh