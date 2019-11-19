FROM python:3.7

WORKDIR /usr/local/app

RUN apt-get update && apt-get install libffi-dev openssl-dev

COPY requirements.txt .

RUN pip install -r requirements.txt