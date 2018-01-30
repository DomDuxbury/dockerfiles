FROM python:alpine3.7

# Install packages
RUN apk add --no-cache --update postgresql-dev gcc python3-dev \
                                musl-dev openblas openblas-dev
RUN apk add --no-cache --virtual .build-deps g++

RUN ln -s /usr/include/locale.h /usr/include/xlocale.h 

RUN pip3 install --upgrade pip
RUN pip3 install scipy
RUN pip3 install pandas

WORKDIR /opt/app
