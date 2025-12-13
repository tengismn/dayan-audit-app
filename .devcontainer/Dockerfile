FROM mcr.microsoft.com/devcontainers/php:8.3

# Install required libraries and PHP extensions
RUN apt-get update && apt-get install -y \
    git unzip zip curl \
    libzip-dev \
 && docker-php-ext-install zip intl \
 && rm -rf /var/lib/apt/lists/*
