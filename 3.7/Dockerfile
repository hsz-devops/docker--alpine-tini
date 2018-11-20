FROM alpine:3.7

RUN apk add --no-cache tini bash

ENTRYPOINT ["/sbin/tini", "--"]
