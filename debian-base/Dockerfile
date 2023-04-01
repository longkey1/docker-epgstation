FROM debian:stable-slim

# Fix frontend not set error
ARG DEBIAN_FRONTEND=noninteractive

# Update package and install depended packages
RUN apt-get -y update && apt-get -y install curl

# Install node
RUN curl -fsSL https://deb.nodesource.com/setup_16.x | bash -
RUN apt-get -y install nodejs

# Confirm node version
RUN node -v
