FROM alpine:latest

RUN mkdir /node
WORKDIR /node
ADD target/release/node /node/node
RUN chmod +x /node/node

ENTRYPOINT ["/node/node"]