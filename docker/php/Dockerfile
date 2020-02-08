FROM php:7.4-cli

# Install SUPERVISOR
RUN apt-get update && apt-get install -y supervisor

# Set USER
RUN useradd -ms /bin/bash project
USER project
WORKDIR /home/project/app
