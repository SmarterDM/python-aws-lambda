FROM python:latest

RUN apt-get -qq update && apt-get -qq install -y python python-virtualenv python-pip
RUN virtualenv venv
RUN . venv/bin/activate
RUN pip install pip
RUN apt-get update
RUN apt-get -y install zip unzip
RUN pip install awscli