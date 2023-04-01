FROM ghcr.io/longkey1/epgstation:raspios64-epgstation

# Fix frontend not set error
ARG DEBIAN_FRONTEND=noninteractive

# Update package
RUN apt-get -y update

# Install ffmpeg
RUN apt-get -y install ffmpeg

# Confirm ffmpeg version and codecs
RUN ffmpeg -codecs
