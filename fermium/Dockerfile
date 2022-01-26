FROM node:fermium-slim

RUN apt-get update && \
  apt-get install -y awscli && \
  apt-get autoremove -y && \
  apt-get clean -y && \
  rm -rf /var/lib/apt/lists/*