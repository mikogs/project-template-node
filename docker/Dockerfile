FROM ubuntu:22.04

RUN mkdir /node
WORKDIR /node
ADD target/release/node /node
RUN chmod +x /node/node

ENTRYPOINT ["/node/node"]