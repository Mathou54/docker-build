
FROM alpine:3.10

RUN apk update && \
    apk add aircrack-ng && \
    rm -rf /var/cache/apk/*

ENTRYPOINT ["aircrack-ng"]

CMD ["--help"]
