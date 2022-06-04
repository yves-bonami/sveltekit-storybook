# See here for image contents: https://github.com/microsoft/vscode-dev-containers/tree/v0.236.0/containers/typescript-node/.devcontainer/base.Dockerfile

ARG VARIANT="18-bullseye"
FROM mcr.microsoft.com/vscode/devcontainers/typescript-node:0-${VARIANT}

# Install PNPM
RUN su node -c "npm install -g pnpm"
