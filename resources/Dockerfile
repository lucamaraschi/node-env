FROM debian:sid

RUN apt-get update && apt-get install -y \
  build-essential \
  g++ \
  python

COPY . /src/node-core

WORKDIR /src/node-core

RUN ./configure \
    && make \
    && make install

EXPOSE 22
