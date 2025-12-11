FROM mcr.microsoft.com/devcontainers/universal:2-linux
# Install Vue.js
RUN apt-get update && \
    npm install -g @vue/cli
# Install Flask
RUN apt-get update && \
    apt-get install -y python3 && \
    pip3 install Flask