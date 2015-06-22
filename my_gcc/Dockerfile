FROM ubuntu
MAINTAINER roylee0704 <roylee0704@gmail.com>
RUN apt-get update
RUN apt-get install -y \
    curl \
    gcc-4.7 \
    git \
    make
RUN mkdir -p /usr/local
RUN update-alternatives --install /usr/bin/gcc gcc /usr/bin/gcc-4.7 60
ENV PATH /usr/local:$PATH
WORKDIR /usr/local