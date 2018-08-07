FROM python:3
LABEL maintainer="hamakou108 <kosuke1602177mteitm19@gmail.com>"

ENV PYTHONUNBUFFERED 1
RUN mkdir /code
WORKDIR /code
ADD requirements.txt /code/
RUN pip install -r requirements.txt
ADD . /code/
