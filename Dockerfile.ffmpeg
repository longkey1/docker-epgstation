FROM ghcr.io/longkey1/raspios:arm64-lite

# Fix frontend not set error
ARG DEBIAN_FRONTEND=noninteractive

# Update package
RUN apt-get -y update

# Install ffmpeg
RUN apt-get -y install ffmpeg

# Confirm node version
RUN ffmpeg -version
