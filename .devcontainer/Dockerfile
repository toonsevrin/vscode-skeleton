FROM docker:19.03.12-dind-rootless@sha256:7606255ca83a7f516fae1b78299b79774f1f798ba9fc792a7231e7b0967ddb05
USER root
RUN apk add git bash curl go make
USER rootless
ENV DOCKER_HOST=unix:///var/run/user/1000/docker.sock
