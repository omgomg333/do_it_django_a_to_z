# pull official base image
FROM python:3.8.0-slim-buster

# set work diretory
WORKDIR /usr/src/app

# set environment variables
ENV PYTHONDONTWRITEBYTECODE 1
ENV PYTHONUNBUFFERD 1


COPY . /usr/src/app/
# install dependencies
RUN pip install --upgrade pip
RUN pip install -r requirements.txt