FROM python:3.5.1

RUN mkdir -p /usr/src/app
COPY . /usr/src/app
WORKDIR /usr/src/app

RUN \
   pip install -r requirements.txt && \
   chmod +x ./wait-for-it.sh