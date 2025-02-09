FROM ubuntu:22.04
  RUN apt-get update -y
  RUN apt-get upgrade -y
  RUN apt-get install -y curl
  RUN curl https://github.com/ovh/venom/releases/download/v1.1.0/venom.linux-amd64 -L -o /usr/local/bin/venom && chmod +x /usr/local/bin/venom