# Dockerfile for the dev container.

FROM python:3.10

ENV PATH $PATH:/root/.local/bin
RUN curl -sSL https://install.python-poetry.org | python3 - --version 1.1.12 && poetry config virtualenvs.create false
