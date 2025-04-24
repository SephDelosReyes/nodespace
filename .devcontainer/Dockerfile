FROM mcr.microsoft.com/vscode/devcontainers/typescript-node
RUN apt-get update && apt-get install -y postgresql postgresql-contrib
RUN npm install -g tailwindcss
WORKDIR /workspace
COPY . .
RUN npm install
