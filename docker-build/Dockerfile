FROM python:3.9.7-slim-buster

RUN apt update && apt install -y curl libffi-dev &&\
pip3 install --upgrade pip &&\
pip3 install \
--no-cache-dir \
robotframework==4.0 \
robotframework-sshlibrary==3.6.0 \
robotframework-scplibrary==1.2.0 \
robotframework-pabot==1.11
