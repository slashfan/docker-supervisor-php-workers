FROM php:7.4-cli

# Install SUPERVISOR
RUN apt-get update \
    && apt-get install -y supervisor \
    && rm -rf /var/lib/apt/lists/*

# Set USER
RUN useradd -ms /bin/bash project
USER project
WORKDIR /home/project/app
