# .devcontainer/Dockerfile
FROM mcr.microsoft.com/vscode/devcontainers/python:1-3.12-bullseye

# Install your package
COPY ./runtime/prompty /workspace
RUN pip install /workspace