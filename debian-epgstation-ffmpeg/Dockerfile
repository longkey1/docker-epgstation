FROM ghcr.io/longkey1/epgstationr:debian-epgstation

# Fix frontend not set error
ARG DEBIAN_FRONTEND=noninteractive

# Update package
RUN apt-get -y update

# Install ffmpeg
RUN apt-get -y install ffmpeg

# Confirm ffmpeg version
RUN ffmpeg -version
