FROM ubuntu:18.04
LABEL maintainer = "gabe7murphy@gmail.com"

RUN apt-get update -y
RUN apt-get install python3-pip -y
RUN apt-get install gunicorn3 -y

COPY requirements.txt requirements.txt
COPY dev /opt/