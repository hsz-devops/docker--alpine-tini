FROM alpine:edge

RUN apk add --no-cache tini bash

ENTRYPOINT ["/sbin/tini", "--"]
