FROM mcr.microsoft.com/devcontainers/ruby:3.2

WORKDIR /workspace

RUN apt-get update && apt-get install -y \
    build-essential \
    ca-certificates \
    curl \
    git \
    gnupg \
    jq \
    less \
    libssl-dev \
    libpq-dev \
    locales \
    ncdu \
    openssh-client \
    postgresql-client \
    rsync \
    shellcheck \
    sudo \
    tree \
    unzip \
    wget \
    vim \
    zip \
    zsh \
    && apt-get autoremove -y \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/*

EXPOSE 3000
