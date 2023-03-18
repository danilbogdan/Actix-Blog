FROM rust:latest as builder

WORKDIR /app
COPY ../Cargo.toml ./
RUN cargo install diesel_cli --no-default-features --features "postgres"
COPY .. .
