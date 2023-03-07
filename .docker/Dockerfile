FROM python:3.11.2-alpine AS build

RUN apk update && apk add bash git make

RUN pip install pipenv

WORKDIR /
COPY . .

FROM build AS development