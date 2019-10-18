FROM ubuntu:18.04
ENV DEBIAN_FRONTEND=noninteractive
ENV DEBCONF_NONINTERACTIVE_SEEN=true
RUN apt-get update  -y \
 && apt-get install -y \
    --no-install-recommends \
    tar \
    curl \
    python3-pip \
    python3-setuptools \
    libcurl4 \
    libcurl4-openssl-dev \
    p7zip-full \
    vim \
    openssh-server \
    p7zip-rar

