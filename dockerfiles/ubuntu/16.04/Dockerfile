FROM ubuntu:16.04

RUN apt update -y &&\
    apt install -y cmake g++ libpoco-dev lsb-release libboost-test-dev perl\
      clang &&\
    rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*

