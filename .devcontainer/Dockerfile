FROM mcr.microsoft.com/devcontainers/base:ubuntu
WORKDIR /workspace/.devcontainer
COPY install-devkitpro-pacman.sh /tmp/install-devkitpro-pacman.sh
RUN apt-get update && apt-get upgrade -y \
    && chmod +x /tmp/install-devkitpro-pacman.sh && /tmp/install-devkitpro-pacman.sh \
    && rm /tmp/install-devkitpro-pacman.sh 
