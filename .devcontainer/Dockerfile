FROM mcr.microsoft.com/devcontainers/javascript-node:20-bullseye

RUN apt-get update \
  && apt-get install -y --no-install-recommends zstd \
  && rm -rf /var/lib/apt/lists/*
