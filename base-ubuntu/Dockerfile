FROM ubuntu:17.10
LABEL maintainer="me@ssgreg.com"

RUN set -ex ; \
    apt-get update ; \
    apt-get install -y \
        autogen \
        automake \
        build-essential \
        ca-certificates \
        clang \
        curl \
        g++-5-multilib \ 
        g++-mingw-w64 \
        gcc-5-multilib \
        gcc-mingw-w64 \
        git \
        libssl-dev \
        libtool \
        llvm-dev \
        make \
        python \
        unzip \
        zip \
        --no-install-recommends \
        -- ; \
    apt-get clean all
