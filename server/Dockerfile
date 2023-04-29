# Dockerfile for node backend
FROM node:20-alpine

WORKDIR /var/www/html/gw2pvp

RUN apk add --no-cache --update tzdata \
  git \
  openssh \
  && mkdir -p /var/opt/certs \
  && mkdir -p /root/.ssh \
  && chown -R root:root /root/.ssh

ENV TZ America/Los_Angeles
ENV SHELL /bin/ash

# Expose port
EXPOSE 554 555
EXPOSE 3000
