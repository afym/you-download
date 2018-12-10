FROM alpine:latest

RUN set -xe \
    && apk add --no-cache ca-certificates ffmpeg openssl python3
    && pip3 install youtube-dl

WORKDIR /downloads

ENTRYPOINT ["youtube-dl"]
CMD ["--help"]