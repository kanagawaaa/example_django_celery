FROM python:3.10

WORKDIR /usr/src/app
COPY . /usr/src/app/

ENV PYTHONDONTWRITEBYTECODE 1
ENV PYTHONUNBUFFERED 1

RUN pip3 install --upgrade pip
RUN pip3 install -r requirements.txt
