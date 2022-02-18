FROM golang:1.17.7-alpine
# alpineにはgitコマンドがない
RUN apk add --update && apk add git
WORKDIR /go/src/app