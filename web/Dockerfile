FROM python:3.6.3

RUN apt-get update && apt-get install -y nano

ENV TERM xterm

WORKDIR /usr/src/app

# Download app and install requirements
RUN git clone -b stable https://github.com/maxplanck-ie/parkour.git .
RUN pip install -r requirements/prod.txt