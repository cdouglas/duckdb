FROM mcr.microsoft.com/devcontainers/cpp:ubuntu-22.04

RUN apt-get update && \
      TZ=Etc/UTC DEBIAN_FRONTEND=noninteractive apt-get install -y --no-install-recommends \
      git \
      g++ \
      cmake \
      ninja-build \
      libssl-dev \
      sudo \
      vim \
      build-essential \
      ssh && \
    apt-get clean && \
    rm -rf /var/lib/apt/lists/*
