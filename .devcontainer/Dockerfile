FROM mcr.microsoft.com/devcontainers/cpp:ubuntu-22.04

RUN apt-get update && \
      TZ=Etc/UTC DEBIAN_FRONTEND=noninteractive apt-get install -y --no-install-recommends \
      git \
      g++ \
      cmake \
      docker \
      ninja-build \
      libssl-dev \
      sudo \
      vim \
      build-essential \
      libpq-dev \
      postgresql-server-dev-all \
      ssh && \
    apt-get clean && \
    rm -rf /var/lib/apt/lists/*
