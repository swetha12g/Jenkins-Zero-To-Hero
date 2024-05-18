FROM ubuntu:18.04
RUN apt-get update \
  && apt-get -y install \
    build-essential \
    cmake vim \
    clang-9 \
    gettext \
    git \
    libpcre2-dev \
    locales \
    ninja-build \
    python3 \
    python3-pexpect \
    sudo \
  && locale-gen en_US.UTF-8 \
  && apt-get clean

