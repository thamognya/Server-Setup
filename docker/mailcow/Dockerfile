# syntax=docker/dockerfile:1
FROM docker:latest
RUN apk add git bash grep coreutils sed openssl curl \
    && git clone https://github.com/mailcow/mailcow-dockerized \
    && cd mailcow-dockerized \
    && echo "mail.thamognya.com" | ./generate_config.sh \
    && docker compose pull \
    && docker compose up -d
EXPOSE 80:8080
