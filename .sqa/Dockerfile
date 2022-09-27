FROM alpine/helm:3.9.4

USER root
RUN apk update \
    && apk add openssh-client \
    && rm -rf /var/cache/apk/*
