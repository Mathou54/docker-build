
FROM alpine:3.10

RUN apt-get update && \
    apt-get install -y aircrack-ng && \
    rm -rf /var/lib/apt/lists/*

ENTRYPOINT ["aircrack-ng"]

CMD ["--help"]
