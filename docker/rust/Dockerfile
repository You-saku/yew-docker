FROM rust:1.72.0-slim

EXPOSE 3000/tcp

COPY ./ /usr/src
WORKDIR /usr/src/yew

RUN apt-get update && apt-get install -y \
    git \
    curl \
    build-essential \
    && rm -rf /var/lib/apt/lists/*


RUN rustup target add wasm32-unknown-unknown
RUN cargo install trunk
