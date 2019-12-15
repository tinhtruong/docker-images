FROM alpine:3.8
MAINTAINER noreply+dockerhub [at] tinhtruong [dot] me

RUN echo "@main http://nl.alpinelinux.org/alpine/edge/main" >> /etc/apk/repositories && \
    echo "@community http://nl.alpinelinux.org/alpine/edge/community" >> /etc/apk/repositories && \
    apk add --no-cache pdftk@community libgcj@main

ENTRYPOINT ["pdftk"]
