FROM mcr.microsoft.com/devcontainers/cpp:0-debian-11

RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
     && apt-get -y install --no-install-recommends -yq \ 
        git psmisc build-essential lcov curl netcat-openbsd \
        cpp-aarch64-linux-gnu gcc-aarch64-linux-gnu \
        > /dev/null && \
        sudo apt-get clean -q
