ARG PYTHON_VERSION=3.11
FROM mcr.microsoft.com/devcontainers/python:${PYTHON_VERSION}
RUN pip install --upgrade pip
COPY requirements.txt /tmp/requirements.txt
RUN pip install -r /tmp/requirements.txt && \
    rm /tmp/requirements.txt
USER vscode 
