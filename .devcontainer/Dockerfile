FROM mcr.microsoft.com/devcontainers/universal:2-linux
# Install the xz-utils package
RUN apt-get update -y && apt-get install -y nodejs npm python3 python3-pip

# Install Vue.js
RUN npm install -g @vue/cli

# Install Flask
RUN pip3 install flask