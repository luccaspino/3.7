# Stage de configuração

# Stage de configuração
FROM ubuntu:latest as builder
RUN apt-get update && apt-get install -y git
RUN git config --global user.name "usuario_test"

# Stage final
FROM ubuntu:latest
RUN apt-get update && apt-get install -y git
