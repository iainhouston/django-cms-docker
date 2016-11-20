FROM python:3.5

ENV BUILD_TIMESTAMP 2016-10-17T:18:00

RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app
COPY requirements.txt /usr/src/app/
RUN pip install --no-cache-dir -r requirements.txt

COPY . /usr/src/app