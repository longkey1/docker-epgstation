FROM ghcr.io/longkey1/raspios:arm64-lite

# Fix frontend not set error
ARG DEBIAN_FRONTEND=noninteractive

# Update package
RUN apt-get -y update

# Install node
RUN curl -fsSL https://deb.nodesource.com/setup_16.x | bash -
RUN apt-get -y install nodejs

# Confirm node version
RUN node -v
