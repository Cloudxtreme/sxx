FROM debian:9

RUN apt update -y &&\
    apt install -y init cmake g++ clang libpoco-dev lsb-release perl\
      libboost-test-dev &&\
    rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*

