FROM python:3.11.2 AS build

RUN pip install pipenv

WORKDIR /
COPY . .

FROM build AS development