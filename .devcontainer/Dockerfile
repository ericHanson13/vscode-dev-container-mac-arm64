# creates base docker containter
FROM --platform=linux/amd64 mcr.microsoft.com/devcontainers/python:0-3.11

# Install chromium for web automation
RUN apt-get update && apt-get install -y \
    chromium \
    chromium-driver \
 && rm -rf /var/lib/apt/lists/*

# Install libre office
RUN apt-get update && apt-get install -y \
    libreoffice \
 && rm -rf /var/lib/apt/lists/*

# Install ca-certificates
RUN apt-get update && apt-get install -y \
    ca-certificates \
 && rm -rf /var/lib/apt/lists/*

# Install zip support
RUN apt-get update && apt-get install -y \
    zip \
    unzip \
 && rm -rf /var/lib/apt/lists/*